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

Total: 6367

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Y520-15IKBN 80WK            | [9f2441851f](https://linux-hardware.org/?probe=9f2441851f) | Dec 31, 2022 |
| HP            | EliteBook 8740w (WH274UT... | [e42d4e66a0](https://linux-hardware.org/?probe=e42d4e66a0) | Dec 31, 2022 |
| MSI           | GE60 2OC\2OE                | [c307379c36](https://linux-hardware.org/?probe=c307379c36) | Dec 30, 2022 |
| Dell          | G3 3500                     | [6be65a4ee5](https://linux-hardware.org/?probe=6be65a4ee5) | Dec 30, 2022 |
| Lenovo        | Z50-70 20354                | [29984f68c6](https://linux-hardware.org/?probe=29984f68c6) | Dec 30, 2022 |
| Apple         | MacBookPro7,1               | [db4379ed1e](https://linux-hardware.org/?probe=db4379ed1e) | Dec 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3f1ca6740d](https://linux-hardware.org/?probe=3f1ca6740d) | Dec 30, 2022 |
| Dell          | Latitude E7240              | [5f83c8f4ad](https://linux-hardware.org/?probe=5f83c8f4ad) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [d048930c78](https://linux-hardware.org/?probe=d048930c78) | Dec 30, 2022 |
| Dell          | G5 5590                     | [dada63bf04](https://linux-hardware.org/?probe=dada63bf04) | Dec 30, 2022 |
| HP            | Pavilion 15                 | [956866bbdd](https://linux-hardware.org/?probe=956866bbdd) | Dec 29, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [aa2aad674b](https://linux-hardware.org/?probe=aa2aad674b) | Dec 29, 2022 |
| Lenovo        | ThinkPad W510 4389W14       | [c83a9ac8a9](https://linux-hardware.org/?probe=c83a9ac8a9) | Dec 29, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [467a749806](https://linux-hardware.org/?probe=467a749806) | Dec 29, 2022 |
| System76      | Lemur Pro                   | [0a61e4fe8d](https://linux-hardware.org/?probe=0a61e4fe8d) | Dec 29, 2022 |
| HP            | ENVY dv7                    | [97e029af78](https://linux-hardware.org/?probe=97e029af78) | Dec 29, 2022 |
| Apple         | MacBookPro14,1              | [2bd4899c8a](https://linux-hardware.org/?probe=2bd4899c8a) | Dec 29, 2022 |
| Apple         | MacBookPro14,1              | [919cfc2c9c](https://linux-hardware.org/?probe=919cfc2c9c) | Dec 29, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [f2ea0a18c8](https://linux-hardware.org/?probe=f2ea0a18c8) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [2e62e57e1c](https://linux-hardware.org/?probe=2e62e57e1c) | Dec 28, 2022 |
| ASUSTek       | P453UA                      | [0bf89f0f8f](https://linux-hardware.org/?probe=0bf89f0f8f) | Dec 28, 2022 |
| Lenovo        | Y50-70 20378                | [fe7926d39a](https://linux-hardware.org/?probe=fe7926d39a) | Dec 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c844147ffd](https://linux-hardware.org/?probe=c844147ffd) | Dec 28, 2022 |
| Alienware     | M11x R2                     | [a0da72bec0](https://linux-hardware.org/?probe=a0da72bec0) | Dec 28, 2022 |
| Dell          | Inspiron 5505               | [ba2d75cfa7](https://linux-hardware.org/?probe=ba2d75cfa7) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [9cc79e51c0](https://linux-hardware.org/?probe=9cc79e51c0) | Dec 28, 2022 |
| HUAWEI        | HVY-WXX9                    | [069f0917d6](https://linux-hardware.org/?probe=069f0917d6) | Dec 28, 2022 |
| Apple         | MacBookPro8,2               | [e4255e8ed7](https://linux-hardware.org/?probe=e4255e8ed7) | Dec 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | [6a2f859c67](https://linux-hardware.org/?probe=6a2f859c67) | Dec 27, 2022 |
| Acer          | Aspire A515-57              | [470c8d54ba](https://linux-hardware.org/?probe=470c8d54ba) | Dec 27, 2022 |
| Apple         | MacBookPro8,2               | [c62b37d15c](https://linux-hardware.org/?probe=c62b37d15c) | Dec 27, 2022 |
| Acer          | Aspire A515-57              | [c0a659dbb1](https://linux-hardware.org/?probe=c0a659dbb1) | Dec 27, 2022 |
| Dell          | XPS 15 9500                 | [d1d8257c05](https://linux-hardware.org/?probe=d1d8257c05) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [2195143f19](https://linux-hardware.org/?probe=2195143f19) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [73e9da47ae](https://linux-hardware.org/?probe=73e9da47ae) | Dec 27, 2022 |
| HP            | Pavilion dv6                | [d759125511](https://linux-hardware.org/?probe=d759125511) | Dec 26, 2022 |
| Acer          | Swift SF314-511             | [b8ad48c33c](https://linux-hardware.org/?probe=b8ad48c33c) | Dec 26, 2022 |
| Apple         | MacBookPro14,1              | [eb6c6ee49e](https://linux-hardware.org/?probe=eb6c6ee49e) | Dec 26, 2022 |
| ASUSTek       | N550JV                      | [748284a21e](https://linux-hardware.org/?probe=748284a21e) | Dec 26, 2022 |
| Dell          | XPS 13 9360                 | [bddcc1503f](https://linux-hardware.org/?probe=bddcc1503f) | Dec 26, 2022 |
| Acer          | Aspire A114-32              | [593969da1f](https://linux-hardware.org/?probe=593969da1f) | Dec 26, 2022 |
| Avell High... | C62 MOB                     | [658f34e70d](https://linux-hardware.org/?probe=658f34e70d) | Dec 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [46687a6be3](https://linux-hardware.org/?probe=46687a6be3) | Dec 26, 2022 |
| Sony          | SVF15213CBB                 | [f8a95f249c](https://linux-hardware.org/?probe=f8a95f249c) | Dec 26, 2022 |
| Sony          | VGN-FW21E                   | [e5eb6c865f](https://linux-hardware.org/?probe=e5eb6c865f) | Dec 25, 2022 |
| GPD           | G1621-02                    | [10a7e912f8](https://linux-hardware.org/?probe=10a7e912f8) | Dec 25, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [576fb3852f](https://linux-hardware.org/?probe=576fb3852f) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9ea4a13b0f](https://linux-hardware.org/?probe=9ea4a13b0f) | Dec 25, 2022 |
| HP            | 255 G8 Notebook PC          | [3f72d88324](https://linux-hardware.org/?probe=3f72d88324) | Dec 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [de111c3be5](https://linux-hardware.org/?probe=de111c3be5) | Dec 24, 2022 |
| HP            | EliteBook 865 16 inch G9... | [857cb922f9](https://linux-hardware.org/?probe=857cb922f9) | Dec 24, 2022 |
| Dell          | Latitude E7470              | [8e6bdc1809](https://linux-hardware.org/?probe=8e6bdc1809) | Dec 24, 2022 |
| System76      | Pangolin                    | [2ee273cbcf](https://linux-hardware.org/?probe=2ee273cbcf) | Dec 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [214b2a3235](https://linux-hardware.org/?probe=214b2a3235) | Dec 23, 2022 |
| HP            | Laptop 14s-dk0xxx           | [53aa474cf5](https://linux-hardware.org/?probe=53aa474cf5) | Dec 23, 2022 |
| Timi          | TM1703                      | [5e25655f36](https://linux-hardware.org/?probe=5e25655f36) | Dec 23, 2022 |
| Toshiba       | Satellite Pro C50-A-1MX     | [78487975ce](https://linux-hardware.org/?probe=78487975ce) | Dec 23, 2022 |
| Dell          | Latitude E7240              | [918223cece](https://linux-hardware.org/?probe=918223cece) | Dec 23, 2022 |
| Medion        | X6816                       | [bafbf1ea90](https://linux-hardware.org/?probe=bafbf1ea90) | Dec 23, 2022 |
| Medion        | X6816                       | [ac9627e5d4](https://linux-hardware.org/?probe=ac9627e5d4) | Dec 23, 2022 |
| Dell          | Latitude E7240              | [7bd2309063](https://linux-hardware.org/?probe=7bd2309063) | Dec 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [d7b8ef01e2](https://linux-hardware.org/?probe=d7b8ef01e2) | Dec 23, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [db7dc4fa25](https://linux-hardware.org/?probe=db7dc4fa25) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [e8ac233c29](https://linux-hardware.org/?probe=e8ac233c29) | Dec 22, 2022 |
| ASUSTek       | K53SJ                       | [341becfd8a](https://linux-hardware.org/?probe=341becfd8a) | Dec 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [ad4be7f0fa](https://linux-hardware.org/?probe=ad4be7f0fa) | Dec 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [a70ba97a7a](https://linux-hardware.org/?probe=a70ba97a7a) | Dec 22, 2022 |
| ASUSTek       | K53SJ                       | [e60df2d8ba](https://linux-hardware.org/?probe=e60df2d8ba) | Dec 22, 2022 |
| Acer          | Swift SF314-512             | [505ab3f60a](https://linux-hardware.org/?probe=505ab3f60a) | Dec 22, 2022 |
| Dell          | Latitude E7240              | [d81efafde1](https://linux-hardware.org/?probe=d81efafde1) | Dec 22, 2022 |
| System76      | Lemur Pro                   | [ed549bfe74](https://linux-hardware.org/?probe=ed549bfe74) | Dec 21, 2022 |
| System76      | Lemur Pro                   | [30be17e71c](https://linux-hardware.org/?probe=30be17e71c) | Dec 21, 2022 |
| Dell          | Precision 3520              | [1763494294](https://linux-hardware.org/?probe=1763494294) | Dec 21, 2022 |
| ASUSTek       | Strix 15 GL503GE            | [0377cc3170](https://linux-hardware.org/?probe=0377cc3170) | Dec 21, 2022 |
| Dell          | Latitude E7240              | [545294a23a](https://linux-hardware.org/?probe=545294a23a) | Dec 21, 2022 |
| Apple         | MacBookPro12,1              | [debd2eb829](https://linux-hardware.org/?probe=debd2eb829) | Dec 21, 2022 |
| Dell          | Inspiron 5515               | [b0df20f3d1](https://linux-hardware.org/?probe=b0df20f3d1) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7d5914dcb2](https://linux-hardware.org/?probe=7d5914dcb2) | Dec 21, 2022 |
| Dell          | Latitude E7240              | [a368a7be00](https://linux-hardware.org/?probe=a368a7be00) | Dec 21, 2022 |
| ASUSTek       | VivoBook S14 X411UF         | [894f0ab5df](https://linux-hardware.org/?probe=894f0ab5df) | Dec 21, 2022 |
| ASUSTek       | N53SM                       | [9c9b1d3f5b](https://linux-hardware.org/?probe=9c9b1d3f5b) | Dec 21, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | [d5a877b2c6](https://linux-hardware.org/?probe=d5a877b2c6) | Dec 20, 2022 |
| Acer          | Aspire A315-23G             | [b7999f8a61](https://linux-hardware.org/?probe=b7999f8a61) | Dec 20, 2022 |
| Acer          | Aspire A315-23G             | [04b9163920](https://linux-hardware.org/?probe=04b9163920) | Dec 19, 2022 |
| Lenovo        | IdeaPad Z410 20292          | [e46710b0cf](https://linux-hardware.org/?probe=e46710b0cf) | Dec 19, 2022 |
| Dell          | Vostro 15 3510              | [f2467d713d](https://linux-hardware.org/?probe=f2467d713d) | Dec 19, 2022 |
| Dell          | Inspiron 7572               | [418178c3ca](https://linux-hardware.org/?probe=418178c3ca) | Dec 19, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1QX0... | [76771fa0aa](https://linux-hardware.org/?probe=76771fa0aa) | Dec 19, 2022 |
| Chuwi         | GemiBook Pro                | [b34ce3474d](https://linux-hardware.org/?probe=b34ce3474d) | Dec 19, 2022 |
| System76      | Gazelle                     | [da46fb926a](https://linux-hardware.org/?probe=da46fb926a) | Dec 19, 2022 |
| Dell          | Inspiron 15-3567            | [f58039213b](https://linux-hardware.org/?probe=f58039213b) | Dec 18, 2022 |
| GPU Compan... | GWNR71517                   | [e680612eb4](https://linux-hardware.org/?probe=e680612eb4) | Dec 18, 2022 |
| Lenovo        | ThinkPad Edge E430 62718... | [92fede3d5a](https://linux-hardware.org/?probe=92fede3d5a) | Dec 18, 2022 |
| Avell High... | B.ON                        | [9661ece374](https://linux-hardware.org/?probe=9661ece374) | Dec 17, 2022 |
| Dell          | XPS 15 9510                 | [1641d91910](https://linux-hardware.org/?probe=1641d91910) | Dec 17, 2022 |
| Dell          | Inspiron 5458               | [8ed4687f2f](https://linux-hardware.org/?probe=8ed4687f2f) | Dec 16, 2022 |
| System76      | Gazelle                     | [b5ef8cec53](https://linux-hardware.org/?probe=b5ef8cec53) | Dec 16, 2022 |
| Acer          | Aspire V5-571G              | [575a61802b](https://linux-hardware.org/?probe=575a61802b) | Dec 16, 2022 |
| Dell          | Latitude 3310               | [4066d1434e](https://linux-hardware.org/?probe=4066d1434e) | Dec 16, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [544e464dab](https://linux-hardware.org/?probe=544e464dab) | Dec 15, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [18d67ba2ab](https://linux-hardware.org/?probe=18d67ba2ab) | Dec 15, 2022 |
| ALLDOCUBE     | i1405C                      | [10d8101488](https://linux-hardware.org/?probe=10d8101488) | Dec 15, 2022 |
| Fujitsu       | FMVNS6C3                    | [d7a6961431](https://linux-hardware.org/?probe=d7a6961431) | Dec 15, 2022 |
| Apple         | MacBookPro10,1              | [a22dd35e04](https://linux-hardware.org/?probe=a22dd35e04) | Dec 14, 2022 |
| Apple         | MacBookPro11,3              | [d0c2bf600a](https://linux-hardware.org/?probe=d0c2bf600a) | Dec 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [d623f983cd](https://linux-hardware.org/?probe=d623f983cd) | Dec 13, 2022 |
| Lenovo        | G505 20240                  | [e6777c2fbc](https://linux-hardware.org/?probe=e6777c2fbc) | Dec 13, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [b08795ce45](https://linux-hardware.org/?probe=b08795ce45) | Dec 13, 2022 |
| Lenovo        | ThinkPad T530 23943J8       | [e5d69d9f81](https://linux-hardware.org/?probe=e5d69d9f81) | Dec 13, 2022 |
| Apple         | MacBookPro9,2               | [2981da7231](https://linux-hardware.org/?probe=2981da7231) | Dec 12, 2022 |
| MSI           | Summit E16Flip A12UCT       | [1db3976bb5](https://linux-hardware.org/?probe=1db3976bb5) | Dec 12, 2022 |
| Toshiba       | Satellite C55-C             | [777b365c04](https://linux-hardware.org/?probe=777b365c04) | Dec 12, 2022 |
| System76      | Gazelle                     | [8498636db6](https://linux-hardware.org/?probe=8498636db6) | Dec 12, 2022 |
| Lenovo        | Legion S7 16ARHA7 82UG      | [d438f3f50a](https://linux-hardware.org/?probe=d438f3f50a) | Dec 12, 2022 |
| Apple         | MacBookPro13,3              | [10b29f88c5](https://linux-hardware.org/?probe=10b29f88c5) | Dec 12, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [75a9a0c076](https://linux-hardware.org/?probe=75a9a0c076) | Dec 12, 2022 |
| ASUSTek       | K56CB                       | [94b056f1f4](https://linux-hardware.org/?probe=94b056f1f4) | Dec 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E4C... | [7ffd00681b](https://linux-hardware.org/?probe=7ffd00681b) | Dec 12, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6de2a0ad33](https://linux-hardware.org/?probe=6de2a0ad33) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [4b0492b053](https://linux-hardware.org/?probe=4b0492b053) | Dec 11, 2022 |
| Dell          | Latitude E7240              | [d6dddd9632](https://linux-hardware.org/?probe=d6dddd9632) | Dec 11, 2022 |
| Acer          | Aspire A515-44G             | [b85a211b25](https://linux-hardware.org/?probe=b85a211b25) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [ca7d835a38](https://linux-hardware.org/?probe=ca7d835a38) | Dec 11, 2022 |
| System76      | Gazelle                     | [8b0297b19e](https://linux-hardware.org/?probe=8b0297b19e) | Dec 11, 2022 |
| Lenovo        | G470 20078                  | [65264ef208](https://linux-hardware.org/?probe=65264ef208) | Dec 11, 2022 |
| Fujitsu       | FMVNS6C3                    | [2cdacbc923](https://linux-hardware.org/?probe=2cdacbc923) | Dec 11, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [15695e4deb](https://linux-hardware.org/?probe=15695e4deb) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1a7d599cd5](https://linux-hardware.org/?probe=1a7d599cd5) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [040652df3d](https://linux-hardware.org/?probe=040652df3d) | Dec 10, 2022 |
| Lenovo        | G470 20078                  | [ea75ebf831](https://linux-hardware.org/?probe=ea75ebf831) | Dec 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [2dc32e31b3](https://linux-hardware.org/?probe=2dc32e31b3) | Dec 09, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | [e8fe4392be](https://linux-hardware.org/?probe=e8fe4392be) | Dec 09, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | [cf32d7158c](https://linux-hardware.org/?probe=cf32d7158c) | Dec 09, 2022 |
| GPU Compan... | GWNR71517                   | [ef20df1d4f](https://linux-hardware.org/?probe=ef20df1d4f) | Dec 09, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [8ce314db56](https://linux-hardware.org/?probe=8ce314db56) | Dec 08, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [858f06f0e5](https://linux-hardware.org/?probe=858f06f0e5) | Dec 08, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [30cc472125](https://linux-hardware.org/?probe=30cc472125) | Dec 08, 2022 |
| Acer          | TravelMate P214-41-G2       | [cb52e49fa2](https://linux-hardware.org/?probe=cb52e49fa2) | Dec 08, 2022 |
| Dell          | G15 5515                    | [861bd0cabf](https://linux-hardware.org/?probe=861bd0cabf) | Dec 08, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [ca25d43c56](https://linux-hardware.org/?probe=ca25d43c56) | Dec 08, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [104e0e02d1](https://linux-hardware.org/?probe=104e0e02d1) | Dec 08, 2022 |
| LG Electro... | 16Z90P-K.AA78A1             | [1646f1763d](https://linux-hardware.org/?probe=1646f1763d) | Dec 08, 2022 |
| Avell High... | A62 LIV                     | [a4f96694c4](https://linux-hardware.org/?probe=a4f96694c4) | Dec 07, 2022 |
| Acer          | Aspire A515-45              | [7eebb7f601](https://linux-hardware.org/?probe=7eebb7f601) | Dec 07, 2022 |
| Dell          | Latitude E7240              | [632cda6ecd](https://linux-hardware.org/?probe=632cda6ecd) | Dec 07, 2022 |
| HP            | ENVY 17                     | [a19d90a89f](https://linux-hardware.org/?probe=a19d90a89f) | Dec 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [b5f311cc8f](https://linux-hardware.org/?probe=b5f311cc8f) | Dec 07, 2022 |
| Dell          | Inspiron 1750               | [e369c14198](https://linux-hardware.org/?probe=e369c14198) | Dec 07, 2022 |
| Lenovo        | IdeaPad Y560                | [64abd8c6fe](https://linux-hardware.org/?probe=64abd8c6fe) | Dec 06, 2022 |
| Fujitsu       | FMVNS6C3                    | [5b60c9dfd0](https://linux-hardware.org/?probe=5b60c9dfd0) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [05f4b7d7cf](https://linux-hardware.org/?probe=05f4b7d7cf) | Dec 06, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [86cd634760](https://linux-hardware.org/?probe=86cd634760) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [6f0ceb7a46](https://linux-hardware.org/?probe=6f0ceb7a46) | Dec 05, 2022 |
| Dell          | G5 5505                     | [f19a76c344](https://linux-hardware.org/?probe=f19a76c344) | Dec 05, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [1798adf382](https://linux-hardware.org/?probe=1798adf382) | Dec 05, 2022 |
| ASUSTek       | UL50VT                      | [ff4edb7010](https://linux-hardware.org/?probe=ff4edb7010) | Dec 05, 2022 |
| HP            | ProBook 6450b               | [f602f6c0bc](https://linux-hardware.org/?probe=f602f6c0bc) | Dec 05, 2022 |
| HP            | ProBook 6450b               | [de39c86a4c](https://linux-hardware.org/?probe=de39c86a4c) | Dec 05, 2022 |
| System76      | Gazelle                     | [deb2c9b6c9](https://linux-hardware.org/?probe=deb2c9b6c9) | Dec 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | [7687bdc111](https://linux-hardware.org/?probe=7687bdc111) | Dec 04, 2022 |
| Acer          | Nitro AN515-54              | [33f26cca4f](https://linux-hardware.org/?probe=33f26cca4f) | Dec 04, 2022 |
| HP            | Notebook                    | [610cea9ebc](https://linux-hardware.org/?probe=610cea9ebc) | Dec 04, 2022 |
| Dell          | Latitude E7240              | [6f34110d45](https://linux-hardware.org/?probe=6f34110d45) | Dec 04, 2022 |
| Unknown       | Unknown                     | [54c6593c53](https://linux-hardware.org/?probe=54c6593c53) | Dec 03, 2022 |
| Unknown       | Unknown                     | [7668b4d9a2](https://linux-hardware.org/?probe=7668b4d9a2) | Dec 03, 2022 |
| HP            | EliteBook 820 G3            | [6913ec89c8](https://linux-hardware.org/?probe=6913ec89c8) | Dec 03, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [4f36906529](https://linux-hardware.org/?probe=4f36906529) | Dec 02, 2022 |
| HP            | ProBook 450 G7 HP NOTEBO... | [2fe5c76c3c](https://linux-hardware.org/?probe=2fe5c76c3c) | Dec 02, 2022 |
| HP            | Notebook                    | [4184c8fa06](https://linux-hardware.org/?probe=4184c8fa06) | Dec 02, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [9c5bc7ca10](https://linux-hardware.org/?probe=9c5bc7ca10) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [0ade3eaab1](https://linux-hardware.org/?probe=0ade3eaab1) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [a3746e8985](https://linux-hardware.org/?probe=a3746e8985) | Dec 01, 2022 |
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
| Pop!_OS 20.04 | 1148      | 24.74%  |
| Pop!_OS 22.04 | 1034      | 22.28%  |
| Pop!_OS 21.04 | 957       | 20.62%  |
| Pop!_OS 20.10 | 856       | 18.44%  |
| Pop!_OS 21.10 | 599       | 12.91%  |
| Pop!_OS 19.10 | 30        | 0.65%   |
| Pop!_OS 18.04 | 7         | 0.15%   |
| Pop!_OS 19.04 | 6         | 0.13%   |
| Pop!_OS 18.10 | 4         | 0.09%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Pop!_OS | 4406      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.11.0-7620-generic      | 441       | 8.96%   |
| 5.8.0-7630-generic       | 381       | 7.74%   |
| 5.4.0-7634-generic       | 346       | 7.03%   |
| 5.19.0-76051900-generic  | 268       | 5.45%   |
| 5.13.0-7614-generic      | 262       | 5.32%   |
| 5.4.0-7642-generic       | 256       | 5.2%    |
| 5.17.5-76051705-generic  | 246       | 5%      |
| 5.8.0-7642-generic       | 242       | 4.92%   |
| 5.11.0-7614-generic      | 227       | 4.61%   |
| 5.13.0-7620-generic      | 217       | 4.41%   |
| 6.0.6-76060006-generic   | 155       | 3.15%   |
| 5.15.15-76051515-generic | 154       | 3.13%   |
| 5.16.11-76051611-generic | 138       | 2.8%    |
| 5.11.0-7612-generic      | 127       | 2.58%   |
| 5.15.5-76051505-generic  | 123       | 2.5%    |
| 5.18.10-76051810-generic | 117       | 2.38%   |
| 5.8.0-7625-generic       | 105       | 2.13%   |
| 5.17.15-76051715-generic | 105       | 2.13%   |
| 5.11.0-7633-generic      | 99        | 2.01%   |
| 5.15.8-76051508-generic  | 98        | 1.99%   |
| 5.16.19-76051619-generic | 95        | 1.93%   |
| 5.16.15-76051615-generic | 91        | 1.85%   |
| 5.4.0-7626-generic       | 84        | 1.71%   |
| 5.15.11-76051511-generic | 61        | 1.24%   |
| 6.0.2-76060002-generic   | 59        | 1.2%    |
| 5.15.23-76051523-generic | 56        | 1.14%   |
| 5.4.0-7625-generic       | 44        | 0.89%   |
| 6.0.12-76060006-generic  | 39        | 0.79%   |
| 5.4.0-7629-generic       | 35        | 0.71%   |
| 6.0.3-76060003-generic   | 23        | 0.47%   |
| 5.19.16-76051916-generic | 21        | 0.43%   |
| 5.3.0-7625-generic       | 10        | 0.2%    |
| 5.3.0-7648-generic       | 6         | 0.12%   |
| 5.11.0-051100-generic    | 6         | 0.12%   |
| 5.3.0-7642-generic       | 4         | 0.08%   |
| 5.3.0-7629-generic       | 4         | 0.08%   |
| 5.3.0-20-generic         | 4         | 0.08%   |
| 5.7.1-050701-generic     | 3         | 0.06%   |
| 4.18.0-16-generic        | 3         | 0.06%   |
| 5.9.12-xanmod1           | 2         | 0.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 872       | 18.1%   |
| 5.4.0   | 744       | 15.44%  |
| 5.8.0   | 698       | 14.49%  |
| 5.13.0  | 466       | 9.67%   |
| 5.19.0  | 270       | 5.6%    |
| 5.17.5  | 249       | 5.17%   |
| 6.0.6   | 155       | 3.22%   |
| 5.15.15 | 154       | 3.2%    |
| 5.16.11 | 138       | 2.86%   |
| 5.15.5  | 123       | 2.55%   |
| 5.18.10 | 117       | 2.43%   |
| 5.17.15 | 105       | 2.18%   |
| 5.15.8  | 98        | 2.03%   |
| 5.16.19 | 95        | 1.97%   |
| 5.16.15 | 91        | 1.89%   |
| 5.15.11 | 61        | 1.27%   |
| 6.0.2   | 60        | 1.25%   |
| 5.15.23 | 56        | 1.16%   |
| 6.0.12  | 39        | 0.81%   |
| 5.3.0   | 32        | 0.66%   |
| 6.0.3   | 23        | 0.48%   |
| 5.19.16 | 21        | 0.44%   |
| 5.0.0   | 6         | 0.12%   |
| 4.18.0  | 6         | 0.12%   |
| 5.7.0   | 4         | 0.08%   |
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

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 878       | 18.36%  |
| 5.4     | 745       | 15.58%  |
| 5.8     | 712       | 14.89%  |
| 5.15    | 490       | 10.25%  |
| 5.13    | 477       | 9.97%   |
| 5.17    | 353       | 7.38%   |
| 5.16    | 322       | 6.73%   |
| 5.19    | 292       | 6.11%   |
| 6.0     | 275       | 5.75%   |
| 5.18    | 121       | 2.53%   |
| 5.3     | 32        | 0.67%   |
| 5.10    | 18        | 0.38%   |
| 5.12    | 13        | 0.27%   |
| 5.7     | 11        | 0.23%   |
| 5.14    | 11        | 0.23%   |
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
| x86_64 | 4406      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 4266      | 96.28%  |
| KDE5            | 38        | 0.86%   |
| Unknown         | 36        | 0.81%   |
| KDE             | 25        | 0.56%   |
| X-Cinnamon      | 15        | 0.34%   |
| GNOME Flashback | 10        | 0.23%   |
| XFCE            | 9         | 0.2%    |
| MATE            | 8         | 0.18%   |
| LXQt            | 8         | 0.18%   |
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
| X11     | 4268      | 96.41%  |
| Wayland | 138       | 3.12%   |
| Unknown | 14        | 0.32%   |
| Tty     | 7         | 0.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3382      | 75.93%  |
| GDM     | 772       | 17.33%  |
| GDM3    | 287       | 6.44%   |
| SDDM    | 7         | 0.16%   |
| TDM     | 5         | 0.11%   |
| LightDM | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 2536      | 57.21%  |
| pt_BR   | 336       | 7.58%   |
| en_GB   | 324       | 7.31%   |
| de_DE   | 188       | 4.24%   |
| C       | 110       | 2.48%   |
| es_ES   | 93        | 2.1%    |
| en_AU   | 93        | 2.1%    |
| it_IT   | 92        | 2.08%   |
| fr_FR   | 88        | 1.99%   |
| en_CA   | 82        | 1.85%   |
| ru_RU   | 59        | 1.33%   |
| Unknown | 48        | 1.08%   |
| pl_PL   | 39        | 0.88%   |
| pt_PT   | 38        | 0.86%   |
| sv_SE   | 29        | 0.65%   |
| en_IN   | 26        | 0.59%   |
| nl_NL   | 19        | 0.43%   |
| nb_NO   | 17        | 0.38%   |
| es_MX   | 16        | 0.36%   |
| en_ZA   | 16        | 0.36%   |
| fi_FI   | 15        | 0.34%   |
| tr_TR   | 11        | 0.25%   |
| fr_CA   | 11        | 0.25%   |
| es_AR   | 11        | 0.25%   |
| hr_HR   | 8         | 0.18%   |
| en_NZ   | 8         | 0.18%   |
| en_IE   | 8         | 0.18%   |
| en_DK   | 8         | 0.18%   |
| hu_HU   | 7         | 0.16%   |
| da_DK   | 7         | 0.16%   |
| ro_RO   | 6         | 0.14%   |
| es_CL   | 6         | 0.14%   |
| de_CH   | 6         | 0.14%   |
| cs_CZ   | 6         | 0.14%   |
| sk_SK   | 5         | 0.11%   |
| zh_CN   | 4         | 0.09%   |
| nl_BE   | 4         | 0.09%   |
| es_CO   | 4         | 0.09%   |
| en_IL   | 4         | 0.09%   |
| zh_TW   | 3         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 3110      | 69.47%  |
| EFI  | 1367      | 30.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 4226      | 95.63%  |
| Btrfs   | 105       | 2.38%   |
| Overlay | 64        | 1.45%   |
| Xfs     | 17        | 0.38%   |
| Unknown | 7         | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3354      | 75.4%   |
| GPT     | 994       | 22.35%  |
| MBR     | 100       | 2.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4309      | 97.53%  |
| Yes       | 109       | 2.47%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4021      | 90.83%  |
| Yes       | 406       | 9.17%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 846       | 19.2%   |
| Dell                   | 781       | 17.73%  |
| Hewlett-Packard        | 592       | 13.44%  |
| ASUSTek Computer       | 514       | 11.67%  |
| Acer                   | 353       | 8.01%   |
| Apple                  | 248       | 5.63%   |
| System76               | 166       | 3.77%   |
| MSI                    | 149       | 3.38%   |
| Toshiba                | 91        | 2.07%   |
| Samsung Electronics    | 81        | 1.84%   |
| HUAWEI                 | 54        | 1.23%   |
| Sony                   | 47        | 1.07%   |
| Notebook               | 41        | 0.93%   |
| Alienware              | 34        | 0.77%   |
| Google                 | 33        | 0.75%   |
| Fujitsu                | 27        | 0.61%   |
| Positivo               | 24        | 0.54%   |
| Razer                  | 20        | 0.45%   |
| PC Specialist          | 16        | 0.36%   |
| Timi                   | 15        | 0.34%   |
| Gigabyte Technology    | 15        | 0.34%   |
| LG Electronics         | 12        | 0.27%   |
| TUXEDO                 | 11        | 0.25%   |
| Medion                 | 11        | 0.25%   |
| GPU Company            | 11        | 0.25%   |
| Framework              | 11        | 0.25%   |
| Unknown                | 11        | 0.25%   |
| Packard Bell           | 9         | 0.2%    |
| Avell High Performance | 9         | 0.2%    |
| Eluktronics            | 7         | 0.16%   |
| Teclast                | 6         | 0.14%   |
| Panasonic              | 6         | 0.14%   |
| Intel                  | 6         | 0.14%   |
| Gateway                | 6         | 0.14%   |
| Clevo                  | 5         | 0.11%   |
| Chuwi                  | 5         | 0.11%   |
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
| System76 Oryx Pro                         | 41        | 0.93%   |
| System76 Lemur Pro                        | 36        | 0.82%   |
| Dell XPS 15 7590                          | 29        | 0.66%   |
| Apple MacBookPro9,2                       | 23        | 0.52%   |
| Unknown                                   | 22        | 0.5%    |
| System76 Gazelle                          | 21        | 0.48%   |
| System76 Galago Pro                       | 20        | 0.45%   |
| Dell XPS 15 9500                          | 20        | 0.45%   |
| HP Pavilion Notebook                      | 19        | 0.43%   |
| System76 Darter Pro                       | 16        | 0.36%   |
| HP Notebook                               | 16        | 0.36%   |
| Apple MacBookPro8,1                       | 16        | 0.36%   |
| HP Pavilion 15                            | 15        | 0.34%   |
| Apple MacBookPro12,1                      | 15        | 0.34%   |
| HP Pavilion dv6                           | 14        | 0.32%   |
| Dell XPS 15 9560                          | 14        | 0.32%   |
| Apple MacBookAir7,2                       | 14        | 0.32%   |
| Apple MacBookAir6,2                       | 14        | 0.32%   |
| Lenovo IdeaPad S145-15API 81V7            | 13        | 0.3%    |
| Dell Latitude E6420                       | 13        | 0.3%    |
| Apple MacBookPro7,1                       | 13        | 0.3%    |
| Dell XPS 15 9570                          | 12        | 0.27%   |
| Dell XPS 17 9700                          | 11        | 0.25%   |
| Dell XPS 13 9380                          | 11        | 0.25%   |
| Apple MacBookPro5,5                       | 11        | 0.25%   |
| Acer Aspire E5-575G                       | 11        | 0.25%   |
| HP Pavilion g6                            | 10        | 0.23%   |
| Dell Latitude E7240                       | 10        | 0.23%   |
| Dell Inspiron N5110                       | 10        | 0.23%   |
| ASUS TUF Gaming FX505DT_FX505DT           | 10        | 0.23%   |
| Samsung 340XAA/350XAA/550XAA              | 9         | 0.2%    |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW | 9         | 0.2%    |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY      | 9         | 0.2%    |
| Lenovo IdeaPad 330-15IKB 81FE             | 9         | 0.2%    |
| HP Pavilion Laptop 15-cw1xxx              | 9         | 0.2%    |
| Framework Laptop                          | 9         | 0.2%    |
| Dell XPS 13 9310                          | 9         | 0.2%    |
| Dell Latitude E7470                       | 9         | 0.2%    |
| Dell Inspiron 3542                        | 9         | 0.2%    |
| Dell Inspiron 3521                        | 9         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 415       | 9.42%   |
| Dell Inspiron      | 260       | 5.9%    |
| Acer Aspire        | 246       | 5.58%   |
| Lenovo IdeaPad     | 231       | 5.24%   |
| Dell Latitude      | 184       | 4.18%   |
| Dell XPS           | 170       | 3.86%   |
| HP Pavilion        | 148       | 3.36%   |
| HP EliteBook       | 90        | 2.04%   |
| HP Laptop          | 87        | 1.97%   |
| Toshiba Satellite  | 79        | 1.79%   |
| ASUS VivoBook      | 76        | 1.72%   |
| ASUS ROG           | 74        | 1.68%   |
| HP ProBook         | 71        | 1.61%   |
| Lenovo Legion      | 63        | 1.43%   |
| Dell Precision     | 53        | 1.2%    |
| Dell Vostro        | 46        | 1.04%   |
| Acer Nitro         | 42        | 0.95%   |
| System76 Oryx      | 41        | 0.93%   |
| ASUS ASUS          | 40        | 0.91%   |
| System76 Lemur     | 39        | 0.89%   |
| HP ENVY            | 30        | 0.68%   |
| ASUS TUF           | 30        | 0.68%   |
| Apple MacBookPro9  | 30        | 0.68%   |
| Acer Swift         | 30        | 0.68%   |
| Apple MacBookPro11 | 29        | 0.66%   |
| ASUS ZenBook       | 27        | 0.61%   |
| HP OMEN            | 25        | 0.57%   |
| Apple MacBookPro8  | 24        | 0.54%   |
| System76 Gazelle   | 23        | 0.52%   |
| System76 Galago    | 23        | 0.52%   |
| Apple MacBookPro5  | 23        | 0.52%   |
| Lenovo ThinkBook   | 22        | 0.5%    |
| Unknown            | 22        | 0.5%    |
| Razer Blade        | 20        | 0.45%   |
| Fujitsu LIFEBOOK   | 20        | 0.45%   |
| Lenovo Yoga        | 17        | 0.39%   |
| HP ZBook           | 17        | 0.39%   |
| System76 Darter    | 16        | 0.36%   |
| HP Notebook        | 16        | 0.36%   |
| Apple MacBookAir6  | 16        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 579       | 13.14%  |
| 2020    | 540       | 12.26%  |
| 2021    | 427       | 9.69%   |
| 2018    | 419       | 9.51%   |
| 2012    | 324       | 7.35%   |
| 2013    | 286       | 6.49%   |
| 2017    | 281       | 6.38%   |
| 2015    | 274       | 6.22%   |
| 2011    | 267       | 6.06%   |
| 2016    | 239       | 5.42%   |
| 2014    | 218       | 4.95%   |
| 2010    | 184       | 4.18%   |
| 2009    | 113       | 2.56%   |
| 2008    | 104       | 2.36%   |
| 2022    | 103       | 2.34%   |
| 2007    | 35        | 0.79%   |
| 2006    | 9         | 0.2%    |
| Unknown | 2         | 0.05%   |
| 2005    | 1         | 0.02%   |
| 2004    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4406      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4403      | 99.93%  |
| Enabled  | 3         | 0.07%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4272      | 96.96%  |
| Yes  | 134       | 3.04%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1313      | 29.57%  |
| 16.01-24.0  | 997       | 22.45%  |
| 8.01-16.0   | 814       | 18.33%  |
| 3.01-4.0    | 681       | 15.33%  |
| 32.01-64.0  | 399       | 8.98%   |
| 64.01-256.0 | 85        | 1.91%   |
| 1.01-2.0    | 66        | 1.49%   |
| 24.01-32.0  | 54        | 1.22%   |
| 2.01-3.0    | 32        | 0.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1571      | 32.86%  |
| 1.01-2.0   | 1276      | 26.69%  |
| 3.01-4.0   | 880       | 18.41%  |
| 4.01-8.0   | 820       | 17.15%  |
| 8.01-16.0  | 195       | 4.08%   |
| 16.01-24.0 | 22        | 0.46%   |
| 0.51-1.0   | 10        | 0.21%   |
| 24.01-32.0 | 6         | 0.13%   |
| 0.01-0.5   | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3112      | 69.45%  |
| 2      | 1177      | 26.27%  |
| 3      | 145       | 3.24%   |
| 0      | 20        | 0.45%   |
| 4      | 19        | 0.42%   |
| 5      | 6         | 0.13%   |
| 7      | 1         | 0.02%   |
| 6      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3140      | 71.09%  |
| Yes       | 1277      | 28.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3535      | 79.85%  |
| No        | 892       | 20.15%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4356      | 98.8%   |
| No        | 53        | 1.2%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3723      | 83.76%  |
| No        | 722       | 16.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 1157      | 26.14%  |
| Brazil       | 468       | 10.57%  |
| Germany      | 267       | 6.03%   |
| UK           | 200       | 4.52%   |
| India        | 193       | 4.36%   |
| Canada       | 159       | 3.59%   |
| Italy        | 145       | 3.28%   |
| France       | 131       | 2.96%   |
| Australia    | 101       | 2.28%   |
| Netherlands  | 91        | 2.06%   |
| Russia       | 79        | 1.78%   |
| Sweden       | 74        | 1.67%   |
| Spain        | 72        | 1.63%   |
| Poland       | 66        | 1.49%   |
| Mexico       | 64        | 1.45%   |
| Portugal     | 62        | 1.4%    |
| Romania      | 53        | 1.2%    |
| Switzerland  | 45        | 1.02%   |
| Norway       | 45        | 1.02%   |
| South Africa | 42        | 0.95%   |
| Turkey       | 39        | 0.88%   |
| Finland      | 36        | 0.81%   |
| Philippines  | 35        | 0.79%   |
| Greece       | 35        | 0.79%   |
| Indonesia    | 34        | 0.77%   |
| Belgium      | 34        | 0.77%   |
| Argentina    | 34        | 0.77%   |
| Denmark      | 31        | 0.7%    |
| Austria      | 29        | 0.66%   |
| New Zealand  | 25        | 0.56%   |
| Chile        | 24        | 0.54%   |
| Croatia      | 22        | 0.5%    |
| Colombia     | 20        | 0.45%   |
| Malaysia     | 19        | 0.43%   |
| Ireland      | 19        | 0.43%   |
| Hungary      | 19        | 0.43%   |
| Bulgaria     | 19        | 0.43%   |
| Czechia      | 18        | 0.41%   |
| Vietnam      | 17        | 0.38%   |
| Japan        | 17        | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 51        | 1.11%   |
| Bengaluru      | 30        | 0.65%   |
| Milan          | 29        | 0.63%   |
| Brisbane       | 27        | 0.59%   |
| Sydney         | 25        | 0.54%   |
| Rio de Janeiro | 24        | 0.52%   |
| Dallas         | 23        | 0.5%    |
| Paris          | 22        | 0.48%   |
| London         | 22        | 0.48%   |
| Vienna         | 20        | 0.43%   |
| Moscow         | 20        | 0.43%   |
| Melbourne      | 20        | 0.43%   |
| Bucharest      | 20        | 0.43%   |
| Rome           | 19        | 0.41%   |
| Berlin         | 19        | 0.41%   |
| Athens         | 19        | 0.41%   |
| New York       | 18        | 0.39%   |
| Istanbul       | 18        | 0.39%   |
| Helsinki       | 18        | 0.39%   |
| Zagreb         | 17        | 0.37%   |
| Warsaw         | 17        | 0.37%   |
| Madrid         | 17        | 0.37%   |
| Amsterdam      | 17        | 0.37%   |
| Los Angeles    | 15        | 0.33%   |
| Johannesburg   | 15        | 0.33%   |
| Zurich         | 14        | 0.3%    |
| Toronto        | 14        | 0.3%    |
| Stockholm      | 14        | 0.3%    |
| Sofia          | 14        | 0.3%    |
| Mexico City    | 14        | 0.3%    |
| Fortaleza      | 14        | 0.3%    |
| Chicago        | 14        | 0.3%    |
| St Petersburg  | 13        | 0.28%   |
| Singapore      | 13        | 0.28%   |
| Oslo           | 13        | 0.28%   |
| Edmonton       | 13        | 0.28%   |
| Calgary        | 13        | 0.28%   |
| Buenos Aires   | 13        | 0.28%   |
| Brooklyn       | 13        | 0.28%   |
| Belo Horizonte | 13        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 1022      | 1363   | 18.02%  |
| WDC                            | 607       | 692    | 10.7%   |
| Seagate                        | 571       | 669    | 10.07%  |
| SanDisk                        | 403       | 523    | 7.1%    |
| Toshiba                        | 374       | 439    | 6.59%   |
| Kingston                       | 306       | 361    | 5.39%   |
| Unknown                        | 268       | 326    | 4.72%   |
| SK hynix                       | 268       | 343    | 4.72%   |
| Crucial                        | 205       | 237    | 3.61%   |
| Intel                          | 181       | 224    | 3.19%   |
| HGST                           | 170       | 195    | 3%      |
| Micron Technology              | 148       | 163    | 2.61%   |
| Apple                          | 117       | 124    | 2.06%   |
| Hitachi                        | 93        | 101    | 1.64%   |
| A-DATA Technology              | 86        | 104    | 1.52%   |
| Phison                         | 73        | 90     | 1.29%   |
| PNY                            | 43        | 49     | 0.76%   |
| China                          | 42        | 47     | 0.74%   |
| LITEON                         | 40        | 46     | 0.71%   |
| Silicon Motion                 | 38        | 46     | 0.67%   |
| KIOXIA                         | 37        | 44     | 0.65%   |
| Micron/Crucial Technology      | 32        | 42     | 0.56%   |
| Transcend                      | 30        | 35     | 0.53%   |
| LITEONIT                       | 26        | 34     | 0.46%   |
| ADATA Technology               | 21        | 30     | 0.37%   |
| Fujitsu                        | 18        | 19     | 0.32%   |
| Team                           | 17        | 21     | 0.3%    |
| SPCC                           | 17        | 18     | 0.3%    |
| JMicron Technology             | 16        | 22     | 0.28%   |
| Union Memory (Shenzhen)        | 15        | 18     | 0.26%   |
| KingSpec                       | 14        | 16     | 0.25%   |
| Solid State Storage Technology | 12        | 15     | 0.21%   |
| Patriot                        | 12        | 13     | 0.21%   |
| OCZ                            | 12        | 12     | 0.21%   |
| Corsair                        | 12        | 14     | 0.21%   |
| Netac                          | 11        | 11     | 0.19%   |
| Hewlett-Packard                | 11        | 13     | 0.19%   |
| Unknown                        | 11        | 12     | 0.19%   |
| Lexar                          | 10        | 10     | 0.18%   |
| UMIS                           | 9         | 9      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB         | 99        | 1.67%   |
| Kingston SA400S37240G 240GB SSD        | 82        | 1.38%   |
| Samsung NVMe SSD Drive 512GB           | 80        | 1.35%   |
| HGST HTS721010A9E630 1TB               | 73        | 1.23%   |
| Unknown MMC Card  64GB                 | 65        | 1.09%   |
| Samsung NVMe SSD Drive 1TB             | 64        | 1.08%   |
| SK hynix NVMe SSD Drive 512GB          | 59        | 0.99%   |
| Toshiba MQ01ABD100 1TB                 | 57        | 0.96%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 57        | 0.96%   |
| SanDisk NVMe SSD Drive 512GB           | 52        | 0.88%   |
| Samsung NVMe SSD Drive 500GB           | 52        | 0.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 51        | 0.86%   |
| Unknown MMC Card  32GB                 | 47        | 0.79%   |
| Intel NVMe SSD Drive 512GB             | 47        | 0.79%   |
| Toshiba MQ04ABF100 1TB                 | 42        | 0.71%   |
| Samsung NVMe SSD Drive 1024GB          | 40        | 0.67%   |
| WDC WD10SPZX-24Z10 1TB                 | 38        | 0.64%   |
| SanDisk NVMe SSD Drive 1TB             | 36        | 0.61%   |
| Seagate ST9500325AS 500GB              | 35        | 0.59%   |
| SanDisk NVMe SSD Drive 256GB           | 35        | 0.59%   |
| Seagate ST1000LM049-2GH172 1TB         | 33        | 0.56%   |
| Samsung SSD 860 EVO 500GB              | 33        | 0.56%   |
| WDC WD10SPZX-21Z10T0 1TB               | 32        | 0.54%   |
| SK hynix NVMe SSD Drive 1024GB         | 31        | 0.52%   |
| Kingston SA400S37480G 480GB SSD        | 30        | 0.5%    |
| Crucial CT500MX500SSD1 500GB           | 30        | 0.5%    |
| SK hynix NVMe SSD Drive 256GB          | 29        | 0.49%   |
| Samsung SSD 850 EVO 250GB              | 29        | 0.49%   |
| Unknown MMC Card  128GB                | 28        | 0.47%   |
| Toshiba NVMe SSD Drive 512GB           | 28        | 0.47%   |
| Seagate ST500LT012-1DG142 500GB        | 28        | 0.47%   |
| SanDisk NVMe SSD Drive 500GB           | 28        | 0.47%   |
| HGST HTS541010A9E680 1TB               | 27        | 0.45%   |
| Crucial CT240BX500SSD1 240GB           | 27        | 0.45%   |
| Samsung SSD 860 EVO 1TB                | 26        | 0.44%   |
| Samsung NVMe SSD Drive 2TB             | 26        | 0.44%   |
| Micron NVMe SSD Drive 512GB            | 26        | 0.44%   |
| Kingston SA400S37120G 120GB SSD        | 26        | 0.44%   |
| Seagate Expansion 4TB                  | 24        | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB           | 24        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 547       | 629    | 36.08%  |
| WDC                 | 375       | 410    | 24.74%  |
| Toshiba             | 230       | 259    | 15.17%  |
| HGST                | 170       | 195    | 11.21%  |
| Hitachi             | 93        | 101    | 6.13%   |
| Samsung Electronics | 28        | 29     | 1.85%   |
| Unknown             | 23        | 25     | 1.52%   |
| Fujitsu             | 18        | 19     | 1.19%   |
| Apple               | 15        | 15     | 0.99%   |
| ASMT                | 5         | 6      | 0.33%   |
| JMicron Technology  | 2         | 5      | 0.13%   |
| Intenso             | 2         | 2      | 0.13%   |
| USB3.0              | 1         | 1      | 0.07%   |
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
| Samsung Electronics | 424       | 548    | 21.71%  |
| Kingston            | 236       | 264    | 12.08%  |
| SanDisk             | 199       | 242    | 10.19%  |
| Crucial             | 190       | 222    | 9.73%   |
| WDC                 | 127       | 154    | 6.5%    |
| Apple               | 87        | 91     | 4.45%   |
| A-DATA Technology   | 58        | 69     | 2.97%   |
| SK hynix            | 49        | 57     | 2.51%   |
| Micron Technology   | 49        | 52     | 2.51%   |
| Toshiba             | 48        | 58     | 2.46%   |
| PNY                 | 42        | 48     | 2.15%   |
| China               | 41        | 46     | 2.1%    |
| Intel               | 40        | 43     | 2.05%   |
| LITEON              | 38        | 44     | 1.95%   |
| Transcend           | 29        | 34     | 1.48%   |
| LITEONIT            | 26        | 34     | 1.33%   |
| SPCC                | 15        | 16     | 0.77%   |
| Seagate             | 14        | 15     | 0.72%   |
| KingSpec            | 13        | 15     | 0.67%   |
| Patriot             | 12        | 13     | 0.61%   |
| OCZ                 | 12        | 12     | 0.61%   |
| Team                | 11        | 15     | 0.56%   |
| Netac               | 10        | 10     | 0.51%   |
| Lexar               | 9         | 9      | 0.46%   |
| JMicron Technology  | 9         | 10     | 0.46%   |
| Corsair             | 9         | 10     | 0.46%   |
| Hewlett-Packard     | 8         | 10     | 0.41%   |
| KingDian            | 7         | 8      | 0.36%   |
| Intenso             | 6         | 6      | 0.31%   |
| Dogfish             | 6         | 8      | 0.31%   |
| BHT                 | 6         | 6      | 0.31%   |
| Apacer              | 6         | 8      | 0.31%   |
| TO Exter            | 5         | 5      | 0.26%   |
| Plextor             | 5         | 7      | 0.26%   |
| GOODRAM             | 5         | 6      | 0.26%   |
| Mushkin             | 4         | 4      | 0.2%    |
| Maxtor              | 4         | 4      | 0.2%    |
| Gigabyte Technology | 4         | 6      | 0.2%    |
| FORESEE             | 4         | 5      | 0.2%    |
| Unknown             | 4         | 4      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1817      | 2303   | 33.81%  |
| NVMe    | 1795      | 2493   | 33.4%   |
| HDD     | 1470      | 1707   | 27.35%  |
| MMC     | 219       | 265    | 4.08%   |
| Unknown | 73        | 94     | 1.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2875      | 3867   | 56.62%  |
| NVMe | 1791      | 2483   | 35.27%  |
| MMC  | 219       | 265    | 4.31%   |
| SAS  | 193       | 247    | 3.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2075      | 2632   | 63.89%  |
| 0.51-1.0   | 1042      | 1215   | 32.08%  |
| 1.01-2.0   | 95        | 117    | 2.92%   |
| 3.01-4.0   | 27        | 33     | 0.83%   |
| 4.01-10.0  | 6         | 9      | 0.18%   |
| 10.01-20.0 | 2         | 3      | 0.06%   |
| 2.01-3.0   | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1541      | 33.95%  |
| 251-500        | 1285      | 28.31%  |
| 501-1000       | 820       | 18.07%  |
| 1001-2000      | 305       | 6.72%   |
| 51-100         | 231       | 5.09%   |
| 21-50          | 115       | 2.53%   |
| 1-20           | 104       | 2.29%   |
| 2001-3000      | 63        | 1.39%   |
| More than 3000 | 47        | 1.04%   |
| Unknown        | 28        | 0.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1919      | 40.36%  |
| 21-50          | 1027      | 21.6%   |
| 101-250        | 618       | 13%     |
| 51-100         | 608       | 12.79%  |
| 251-500        | 305       | 6.41%   |
| 501-1000       | 165       | 3.47%   |
| 1001-2000      | 59        | 1.24%   |
| Unknown        | 28        | 0.59%   |
| More than 3000 | 14        | 0.29%   |
| 2001-3000      | 12        | 0.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB               | 5         | 8      | 4.76%   |
| Seagate ST1000LM035-1RK172 1TB           | 4         | 4      | 3.81%   |
| HGST HTS721010A9E630 1TB                 | 4         | 4      | 3.81%   |
| Seagate ST500LT012-1DG142 500GB          | 3         | 3      | 2.86%   |
| Seagate ST1000LX015-1U7172 1TB           | 3         | 3      | 2.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 3         | 3      | 2.86%   |
| Hitachi HTS545050A7E380 500GB            | 3         | 5      | 2.86%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 2.86%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 2         | 2      | 1.9%    |
| Seagate ST9500325AS 500GB                | 2         | 3      | 1.9%    |
| Seagate ST500LT012-9WS142 500GB          | 2         | 2      | 1.9%    |
| Seagate ST500LM012 HN-M500MBB 500GB      | 2         | 2      | 1.9%    |
| SanDisk SD9SN8W-128G-1006 128GB SSD      | 2         | 2      | 1.9%    |
| Kingston SUV400S37120G 120GB SSD         | 2         | 2      | 1.9%    |
| Crucial CT1000P1SSD8 1TB                 | 2         | 2      | 1.9%    |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 0.95%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 0.95%   |
| WDC WD5000LPCX-21VHAT0 500GB             | 1         | 1      | 0.95%   |
| WDC WD5000BPVT-22HXZT3 500GB             | 1         | 1      | 0.95%   |
| WDC WD5000BPVT-08HXZT3 500GB             | 1         | 1      | 0.95%   |
| WDC WD2500BEVT-22A23T0 250GB             | 1         | 1      | 0.95%   |
| WDC WD1600BJKT-75F4T0 160GB              | 1         | 1      | 0.95%   |
| WDC WD10SPZX-75Z10T1 1TB                 | 1         | 1      | 0.95%   |
| WDC WD10SPZX-24Z10 1TB                   | 1         | 1      | 0.95%   |
| WDC WD10SPZX-22Z10T0 1TB                 | 1         | 1      | 0.95%   |
| WDC WD10SPCX-24HWST1 1TB                 | 1         | 1      | 0.95%   |
| WDC WD10JPVX-75JC3T0 1TB                 | 1         | 1      | 0.95%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 2      | 0.95%   |
| Toshiba MQ02ABD100H 1TB                  | 1         | 1      | 0.95%   |
| Toshiba MQ01ACF050 500GB                 | 1         | 1      | 0.95%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 1      | 0.95%   |
| Toshiba MQ01ABD032 320GB                 | 1         | 1      | 0.95%   |
| Toshiba MK7559GSXP 752GB                 | 1         | 1      | 0.95%   |
| Toshiba MK5059GSXP 500GB                 | 1         | 1      | 0.95%   |
| Toshiba MK2035GSS 200GB                  | 1         | 1      | 0.95%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD  | 1         | 1      | 0.95%   |
| Team TM8FP4004T 4TB                      | 1         | 1      | 0.95%   |
| SK hynix SC210 mSATA 256GB SSD           | 1         | 2      | 0.95%   |
| SK hynix PC711 HFS001TDE9X073N 1024GB    | 1         | 1      | 0.95%   |
| SK hynix HFS512G39TND-N210A 512GB SSD    | 1         | 1      | 0.95%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 26     | 23.81%  |
| WDC                 | 14        | 14     | 13.33%  |
| HGST                | 12        | 15     | 11.43%  |
| Toshiba             | 9         | 10     | 8.57%   |
| SK hynix            | 6         | 7      | 5.71%   |
| Samsung Electronics | 6         | 6      | 5.71%   |
| Hitachi             | 6         | 8      | 5.71%   |
| Crucial             | 5         | 5      | 4.76%   |
| A-DATA Technology   | 5         | 5      | 4.76%   |
| Micron Technology   | 4         | 4      | 3.81%   |
| Kingston            | 4         | 4      | 3.81%   |
| Intel               | 3         | 3      | 2.86%   |
| SanDisk             | 2         | 2      | 1.9%    |
| Team                | 1         | 1      | 0.95%   |
| Lexar               | 1         | 1      | 0.95%   |
| Leven               | 1         | 1      | 0.95%   |
| China               | 1         | 1      | 0.95%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 25        | 26     | 39.68%  |
| WDC     | 13        | 13     | 20.63%  |
| HGST    | 12        | 15     | 19.05%  |
| Toshiba | 7         | 7      | 11.11%  |
| Hitachi | 6         | 8      | 9.52%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 63        | 69     | 60%     |
| SSD  | 28        | 30     | 26.67%  |
| NVMe | 14        | 14     | 13.33%  |

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
| Detected | 3419      | 5295   | 74.2%   |
| Works    | 1083      | 1453   | 23.5%   |
| Malfunc  | 105       | 113    | 2.28%   |
| Failed   | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2995      | 54.33%  |
| Samsung Electronics              | 659       | 11.95%  |
| AMD                              | 559       | 10.14%  |
| SanDisk                          | 303       | 5.5%    |
| SK hynix                         | 218       | 3.95%   |
| Toshiba America Info Systems     | 104       | 1.89%   |
| Micron Technology                | 99        | 1.8%    |
| Phison Electronics               | 84        | 1.52%   |
| Kingston Technology Company      | 74        | 1.34%   |
| Nvidia                           | 72        | 1.31%   |
| ADATA Technology                 | 50        | 0.91%   |
| Silicon Motion                   | 45        | 0.82%   |
| Micron/Crucial Technology        | 43        | 0.78%   |
| KIOXIA                           | 41        | 0.74%   |
| Union Memory (Shenzhen)          | 30        | 0.54%   |
| Solid State Storage Technology   | 30        | 0.54%   |
| Realtek Semiconductor            | 17        | 0.31%   |
| Marvell Technology Group         | 17        | 0.31%   |
| Apple                            | 15        | 0.27%   |
| Seagate Technology               | 11        | 0.2%    |
| Silicon Integrated Systems [SiS] | 8         | 0.15%   |
| Shenzhen Longsys Electronics     | 7         | 0.13%   |
| Lite-On Technology               | 7         | 0.13%   |
| Lenovo                           | 6         | 0.11%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.07%   |
| JMicron Technology               | 4         | 0.07%   |
| ASMedia Technology               | 3         | 0.05%   |
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
| AMD FCH SATA Controller [AHCI mode]                                            | 530       | 9.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 369       | 6.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 356       | 6.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 319       | 5.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 285       | 4.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 243       | 4.21%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 227       | 3.93%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 183       | 3.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 147       | 2.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 128       | 2.22%   |
| Intel Volume Management Device NVMe RAID Controller                            | 116       | 2.01%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 109       | 1.89%   |
| Samsung NVMe SSD Controller 980                                                | 102       | 1.77%   |
| Micron Non-Volatile memory controller                                          | 99        | 1.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 96        | 1.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 93        | 1.61%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 84        | 1.46%   |
| Intel SSD 660P Series                                                          | 83        | 1.44%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 81        | 1.4%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 81        | 1.4%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 77        | 1.33%   |
| Intel Comet Lake SATA AHCI Controller                                          | 76        | 1.32%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 67        | 1.16%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 64        | 1.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 62        | 1.07%   |
| SanDisk Non-Volatile memory controller                                         | 56        | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 49        | 0.85%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 48        | 0.83%   |
| Phison E12 NVMe Controller                                                     | 47        | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 47        | 0.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 47        | 0.81%   |
| SK hynix Non-Volatile memory controller                                        | 45        | 0.78%   |
| Nvidia MCP79 AHCI Controller                                                   | 41        | 0.71%   |
| Intel Tiger Lake-LP SATA Controller                                            | 41        | 0.71%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 41        | 0.71%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 39        | 0.68%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 38        | 0.66%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 38        | 0.66%   |
| Samsung Electronics SATA controller                                            | 36        | 0.62%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 33        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3164      | 57.19%  |
| NVMe | 1789      | 32.34%  |
| RAID | 426       | 7.7%    |
| IDE  | 153       | 2.77%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 3595      | 81.59%  |
| AMD    | 811       | 18.41%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 112       | 2.54%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 92        | 2.09%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 88        | 2%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 80        | 1.81%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 76        | 1.72%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 68        | 1.54%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 65        | 1.47%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 64        | 1.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 63        | 1.43%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 62        | 1.41%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 62        | 1.41%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 59        | 1.34%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 54        | 1.23%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 51        | 1.16%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 51        | 1.16%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 50        | 1.13%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 48        | 1.09%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 45        | 1.02%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 44        | 1%      |
| Intel Core i5-9300H CPU @ 2.40GHz             | 39        | 0.88%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 39        | 0.88%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 37        | 0.84%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 36        | 0.82%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 36        | 0.82%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 36        | 0.82%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 34        | 0.77%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 33        | 0.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 33        | 0.75%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 32        | 0.73%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 32        | 0.73%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 31        | 0.7%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 31        | 0.7%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 29        | 0.66%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 28        | 0.64%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 27        | 0.61%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 27        | 0.61%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 27        | 0.61%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 27        | 0.61%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 27        | 0.61%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 26        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1324      | 30.05%  |
| Intel Core i5           | 1135      | 25.76%  |
| Other                   | 329       | 7.47%   |
| Intel Core i3           | 280       | 6.35%   |
| AMD Ryzen 5             | 228       | 5.17%   |
| AMD Ryzen 7             | 216       | 4.9%    |
| Intel Core 2 Duo        | 164       | 3.72%   |
| Intel Celeron           | 144       | 3.27%   |
| AMD Ryzen 3             | 55        | 1.25%   |
| Intel Pentium           | 54        | 1.23%   |
| AMD Ryzen 9             | 52        | 1.18%   |
| Intel Core i9           | 48        | 1.09%   |
| AMD A6                  | 48        | 1.09%   |
| Intel Pentium Dual-Core | 31        | 0.7%    |
| AMD A8                  | 31        | 0.7%    |
| AMD A10                 | 28        | 0.64%   |
| AMD Ryzen 7 PRO         | 24        | 0.54%   |
| AMD A4                  | 24        | 0.54%   |
| Intel Atom              | 19        | 0.43%   |
| Intel Core 2            | 16        | 0.36%   |
| Intel Pentium Dual      | 13        | 0.3%    |
| Intel Genuine           | 13        | 0.3%    |
| Intel Xeon              | 12        | 0.27%   |
| Intel Core m3           | 12        | 0.27%   |
| AMD E1                  | 10        | 0.23%   |
| AMD Athlon              | 10        | 0.23%   |
| AMD Ryzen 5 PRO         | 9         | 0.2%    |
| AMD E                   | 8         | 0.18%   |
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
| 2      | 1932      | 43.85%  |
| 4      | 1554      | 35.27%  |
| 6      | 450       | 10.21%  |
| 8      | 385       | 8.74%   |
| 14     | 28        | 0.64%   |
| 1      | 23        | 0.52%   |
| 12     | 17        | 0.39%   |
| 10     | 13        | 0.3%    |
| 16     | 2         | 0.05%   |
| 7      | 1         | 0.02%   |
| 5      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4406      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3675      | 83.37%  |
| 1      | 733       | 16.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4399      | 99.84%  |
| Unknown        | 7         | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2811      | 62.22%  |
| 0x906ea    | 147       | 3.25%   |
| 0x806ea    | 100       | 2.21%   |
| 0x306a9    | 98        | 2.17%   |
| 0x806ec    | 97        | 2.15%   |
| 0x206a7    | 89        | 1.97%   |
| 0x806c1    | 83        | 1.84%   |
| 0x406e3    | 82        | 1.81%   |
| 0x40651    | 78        | 1.73%   |
| 0xa0652    | 71        | 1.57%   |
| 0x806e9    | 57        | 1.26%   |
| 0x306c3    | 56        | 1.24%   |
| 0x906e9    | 53        | 1.17%   |
| 0x08108102 | 44        | 0.97%   |
| 0x0a50000c | 41        | 0.91%   |
| 0x306d4    | 37        | 0.82%   |
| 0x806d1    | 35        | 0.77%   |
| 0x806eb    | 33        | 0.73%   |
| 0x506e3    | 33        | 0.73%   |
| 0x1067a    | 32        | 0.71%   |
| 0x08600106 | 31        | 0.69%   |
| 0x906ed    | 27        | 0.6%    |
| 0x08108109 | 27        | 0.6%    |
| 0x08600104 | 23        | 0.51%   |
| 0x20655    | 22        | 0.49%   |
| 0x706e5    | 19        | 0.42%   |
| 0x906a3    | 18        | 0.4%    |
| 0x08600103 | 17        | 0.38%   |
| 0x06006705 | 17        | 0.38%   |
| 0x08608103 | 16        | 0.35%   |
| 0x0810100b | 15        | 0.33%   |
| 0x706a1    | 13        | 0.29%   |
| 0x40661    | 11        | 0.24%   |
| 0x10676    | 11        | 0.24%   |
| 0xa0660    | 9         | 0.2%    |
| 0x07030105 | 9         | 0.2%    |
| 0x0a404101 | 8         | 0.18%   |
| 0x08600102 | 8         | 0.18%   |
| 0x06001119 | 8         | 0.18%   |
| 0x406c4    | 7         | 0.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1059      | 24.02%  |
| Haswell          | 394       | 8.94%   |
| IvyBridge        | 320       | 7.26%   |
| SandyBridge      | 318       | 7.21%   |
| Skylake          | 254       | 5.76%   |
| TigerLake        | 193       | 4.38%   |
| Zen+             | 181       | 4.11%   |
| Penryn           | 178       | 4.04%   |
| CometLake        | 177       | 4.02%   |
| Zen 2            | 171       | 3.88%   |
| Broadwell        | 154       | 3.49%   |
| Unknown          | 148       | 3.36%   |
| Westmere         | 138       | 3.13%   |
| Zen 3            | 122       | 2.77%   |
| IceLake          | 84        | 1.91%   |
| Silvermont       | 74        | 1.68%   |
| Core             | 70        | 1.59%   |
| Excavator        | 62        | 1.41%   |
| Zen              | 47        | 1.07%   |
| Goldmont plus    | 46        | 1.04%   |
| Puma             | 37        | 0.84%   |
| Piledriver       | 34        | 0.77%   |
| Alderlake Hybrid | 22        | 0.5%    |
| Bobcat           | 21        | 0.48%   |
| Goldmont         | 20        | 0.45%   |
| Nehalem          | 16        | 0.36%   |
| Jaguar           | 13        | 0.29%   |
| Steamroller      | 12        | 0.27%   |
| K10 Llano        | 12        | 0.27%   |
| K8 Hammer        | 11        | 0.25%   |
| K10              | 8         | 0.18%   |
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
| Intel                            | 3255      | 55.27%  |
| Nvidia                           | 1599      | 27.15%  |
| AMD                              | 1028      | 17.46%  |
| Silicon Integrated Systems [SiS] | 6         | 0.1%    |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 305       | 5.06%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 294       | 4.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 290       | 4.81%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 220       | 3.65%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 182       | 3.02%   |
| Intel UHD Graphics 620                                                                   | 181       | 3%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 181       | 3%      |
| AMD Renoir                                                                               | 162       | 2.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 155       | 2.57%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 148       | 2.46%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 138       | 2.29%   |
| Intel HD Graphics 620                                                                    | 131       | 2.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 128       | 2.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 115       | 1.91%   |
| Intel HD Graphics 630                                                                    | 113       | 1.87%   |
| Intel HD Graphics 5500                                                                   | 111       | 1.84%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 109       | 1.81%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 108       | 1.79%   |
| Intel Core Processor Integrated Graphics Controller                                      | 104       | 1.73%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 80        | 1.33%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 76        | 1.26%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 66        | 1.09%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 65        | 1.08%   |
| Intel HD Graphics 530                                                                    | 65        | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 62        | 1.03%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 55        | 0.91%   |
| AMD Lucienne                                                                             | 54        | 0.9%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 51        | 0.85%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 51        | 0.85%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 50        | 0.83%   |
| Nvidia GP108M [GeForce MX150]                                                            | 49        | 0.81%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 48        | 0.8%    |
| Nvidia TU117M                                                                            | 47        | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 45        | 0.75%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 44        | 0.73%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 43        | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 43        | 0.71%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 41        | 0.68%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 35        | 0.58%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 35        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1990      | 44.88%  |
| Intel + Nvidia     | 1102      | 24.85%  |
| 1 x AMD            | 592       | 13.35%  |
| 1 x Nvidia         | 296       | 6.68%   |
| AMD + Nvidia       | 180       | 4.06%   |
| Intel + AMD        | 170       | 3.83%   |
| 2 x AMD            | 87        | 1.96%   |
| 2 x Nvidia         | 9         | 0.2%    |
| 1 x SiS            | 6         | 0.14%   |
| 1 x S3 Graphics    | 1         | 0.02%   |
| Intel + 2 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3043      | 68.47%  |
| Proprietary | 1276      | 28.71%  |
| Unknown     | 125       | 2.81%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3286      | 73.3%   |
| 1.01-2.0   | 322       | 7.18%   |
| 3.01-4.0   | 302       | 6.74%   |
| 5.01-6.0   | 176       | 3.93%   |
| 0.01-0.5   | 171       | 3.81%   |
| 7.01-8.0   | 100       | 2.23%   |
| 0.51-1.0   | 87        | 1.94%   |
| 2.01-3.0   | 29        | 0.65%   |
| 8.01-16.0  | 10        | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 925       | 18.01%  |
| Chimei Innolux          | 740       | 14.41%  |
| LG Display              | 730       | 14.21%  |
| BOE                     | 651       | 12.67%  |
| Samsung Electronics     | 479       | 9.32%   |
| Apple                   | 208       | 4.05%   |
| Sharp                   | 189       | 3.68%   |
| Goldstar                | 159       | 3.1%    |
| Dell                    | 149       | 2.9%    |
| PANDA                   | 129       | 2.51%   |
| Chi Mei Optoelectronics | 79        | 1.54%   |
| Lenovo                  | 63        | 1.23%   |
| AOC                     | 54        | 1.05%   |
| Hewlett-Packard         | 52        | 1.01%   |
| Acer                    | 52        | 1.01%   |
| BenQ                    | 42        | 0.82%   |
| Philips                 | 41        | 0.8%    |
| InfoVision              | 38        | 0.74%   |
| Ancor Communications    | 32        | 0.62%   |
| ASUSTek Computer        | 27        | 0.53%   |
| CSO                     | 25        | 0.49%   |
| ViewSonic               | 19        | 0.37%   |
| LG Philips              | 14        | 0.27%   |
| Sony                    | 13        | 0.25%   |
| TMX                     | 12        | 0.23%   |
| Vizio                   | 11        | 0.21%   |
| Panasonic               | 11        | 0.21%   |
| InnoLux Display         | 10        | 0.19%   |
| Toshiba                 | 8         | 0.16%   |
| Sceptre Tech            | 8         | 0.16%   |
| Iiyama                  | 8         | 0.16%   |
| JDI                     | 7         | 0.14%   |
| MSI                     | 6         | 0.12%   |
| Vestel Elektronik       | 5         | 0.1%    |
| LGD                     | 5         | 0.1%    |
| Insignia                | 4         | 0.08%   |
| Hitachi                 | 4         | 0.08%   |
| HannStar                | 4         | 0.08%   |
| Eizo                    | 4         | 0.08%   |
| CPT                     | 4         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 55        | 1.06%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 49        | 0.94%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 43        | 0.83%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 41        | 0.79%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 39        | 0.75%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 37        | 0.71%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch          | 33        | 0.64%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 33        | 0.64%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 25        | 0.48%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 24        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 24        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 24        | 0.46%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 24        | 0.46%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 24        | 0.46%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 23        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 23        | 0.44%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 22        | 0.42%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 20        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 20        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 19        | 0.37%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 19        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 18        | 0.35%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 18        | 0.35%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 18        | 0.35%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 17        | 0.33%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 17        | 0.33%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 16        | 0.31%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 16        | 0.31%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 15        | 0.29%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 15        | 0.29%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 15        | 0.29%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 14        | 0.27%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 14        | 0.27%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 14        | 0.27%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x194mm 15.5-inch        | 14        | 0.27%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 14        | 0.27%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                | 14        | 0.27%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 14        | 0.27%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 14        | 0.27%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 13        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2260      | 47.02%  |
| 1366x768 (WXGA)    | 1245      | 25.91%  |
| 3840x2160 (4K)     | 244       | 5.08%   |
| 1600x900 (HD+)     | 205       | 4.27%   |
| 2560x1440 (QHD)    | 148       | 3.08%   |
| 1280x800 (WXGA)    | 116       | 2.41%   |
| 1920x1200 (WUXGA)  | 95        | 1.98%   |
| 1440x900 (WXGA+)   | 91        | 1.89%   |
| 2560x1600          | 63        | 1.31%   |
| 2880x1800          | 50        | 1.04%   |
| 2560x1080          | 42        | 0.87%   |
| 3840x2400          | 30        | 0.62%   |
| 3440x1440          | 29        | 0.6%    |
| 1680x1050 (WSXGA+) | 28        | 0.58%   |
| 2160x1440          | 18        | 0.37%   |
| 1360x768           | 17        | 0.35%   |
| 3200x1800 (QHD+)   | 16        | 0.33%   |
| 2256x1504          | 13        | 0.27%   |
| 1920x540           | 13        | 0.27%   |
| 1280x1024 (SXGA)   | 11        | 0.23%   |
| 3000x2000          | 10        | 0.21%   |
| 3840x1080          | 9         | 0.19%   |
| 3456x2160          | 6         | 0.12%   |
| Unknown            | 6         | 0.12%   |
| 3200x2000          | 4         | 0.08%   |
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
| 15      | 2187      | 42.6%   |
| 13      | 784       | 15.27%  |
| 14      | 565       | 11.01%  |
| 17      | 379       | 7.38%   |
| 27      | 173       | 3.37%   |
| 24      | 148       | 2.88%   |
| 23      | 134       | 2.61%   |
| 12      | 107       | 2.08%   |
| 21      | 97        | 1.89%   |
| 31      | 76        | 1.48%   |
| 11      | 63        | 1.23%   |
| 34      | 62        | 1.21%   |
| 16      | 62        | 1.21%   |
| 18      | 47        | 0.92%   |
| Unknown | 42        | 0.82%   |
| 19      | 28        | 0.55%   |
| 32      | 19        | 0.37%   |
| 84      | 17        | 0.33%   |
| 20      | 17        | 0.33%   |
| 72      | 13        | 0.25%   |
| 22      | 13        | 0.25%   |
| 40      | 11        | 0.21%   |
| 48      | 10        | 0.19%   |
| 54      | 9         | 0.18%   |
| 25      | 7         | 0.14%   |
| 26      | 6         | 0.12%   |
| 52      | 5         | 0.1%    |
| 28      | 5         | 0.1%    |
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
| 301-350        | 3139      | 61.59%  |
| 201-300        | 553       | 10.85%  |
| 351-400        | 461       | 9.04%   |
| 501-600        | 414       | 8.12%   |
| 401-500        | 195       | 3.83%   |
| 601-700        | 109       | 2.14%   |
| 701-800        | 85        | 1.67%   |
| 1001-1500      | 42        | 0.82%   |
| Unknown        | 42        | 0.82%   |
| 1501-2000      | 31        | 0.61%   |
| 801-900        | 20        | 0.39%   |
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
| 16/9    | 3779      | 84.86%  |
| 16/10   | 483       | 10.85%  |
| 21/9    | 73        | 1.64%   |
| 3/2     | 52        | 1.17%   |
| Unknown | 23        | 0.52%   |
| 5/4     | 14        | 0.31%   |
| 32/9    | 10        | 0.22%   |
| 4/3     | 8         | 0.18%   |
| 3.40    | 3         | 0.07%   |
| 3.73    | 2         | 0.04%   |
| 0.62    | 2         | 0.04%   |
| 6/5     | 1         | 0.02%   |
| 3.20    | 1         | 0.02%   |
| 0.67    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2199      | 42.92%  |
| 81-90          | 1092      | 21.31%  |
| 121-130        | 354       | 6.91%   |
| 201-250        | 326       | 6.36%   |
| 71-80          | 255       | 4.98%   |
| 301-350        | 177       | 3.45%   |
| 351-500        | 164       | 3.2%    |
| 61-70          | 101       | 1.97%   |
| 151-200        | 68        | 1.33%   |
| 51-60          | 66        | 1.29%   |
| More than 1000 | 59        | 1.15%   |
| 251-300        | 54        | 1.05%   |
| 141-150        | 49        | 0.96%   |
| 111-120        | 45        | 0.88%   |
| Unknown        | 42        | 0.82%   |
| 501-1000       | 37        | 0.72%   |
| 131-140        | 22        | 0.43%   |
| 91-100         | 7         | 0.14%   |
| 41-50          | 5         | 0.1%    |
| 1-40           | 2         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2204      | 43.94%  |
| 101-120       | 1421      | 28.33%  |
| 51-100        | 702       | 14%     |
| 161-240       | 367       | 7.32%   |
| More than 240 | 215       | 4.29%   |
| 1-50          | 65        | 1.3%    |
| Unknown       | 42        | 0.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3480      | 77.21%  |
| 2     | 777       | 17.24%  |
| 0     | 156       | 3.46%   |
| 3     | 88        | 1.95%   |
| 4     | 6         | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2419      | 33.79%  |
| Intel                             | 2358      | 32.94%  |
| Qualcomm Atheros                  | 1016      | 14.19%  |
| Broadcom                          | 493       | 6.89%   |
| Broadcom Limited                  | 140       | 1.96%   |
| MediaTek                          | 100       | 1.4%    |
| Marvell Technology Group          | 63        | 0.88%   |
| Nvidia                            | 51        | 0.71%   |
| Ralink                            | 49        | 0.68%   |
| TP-Link                           | 45        | 0.63%   |
| ASIX Electronics                  | 43        | 0.6%    |
| Ralink Technology                 | 37        | 0.52%   |
| Samsung Electronics               | 34        | 0.47%   |
| DisplayLink                       | 27        | 0.38%   |
| Dell                              | 23        | 0.32%   |
| Lenovo                            | 20        | 0.28%   |
| Ericsson Business Mobile Networks | 20        | 0.28%   |
| Sierra Wireless                   | 19        | 0.27%   |
| Xiaomi                            | 16        | 0.22%   |
| Qualcomm                          | 16        | 0.22%   |
| JMicron Technology                | 15        | 0.21%   |
| Google                            | 13        | 0.18%   |
| Hewlett-Packard                   | 12        | 0.17%   |
| NetGear                           | 11        | 0.15%   |
| ASUSTek Computer                  | 11        | 0.15%   |
| Huawei Technologies               | 10        | 0.14%   |
| OnePlus Technology (Shenzhen)     | 9         | 0.13%   |
| D-Link                            | 9         | 0.13%   |
| Silicon Integrated Systems [SiS]  | 8         | 0.11%   |
| Motorola PCS                      | 8         | 0.11%   |
| Apple                             | 6         | 0.08%   |
| OPPO Electronics                  | 5         | 0.07%   |
| Microsoft                         | 4         | 0.06%   |
| Linksys                           | 4         | 0.06%   |
| Qualcomm Atheros Communications   | 3         | 0.04%   |
| Fibocom                           | 3         | 0.04%   |
| Edimax Technology                 | 3         | 0.04%   |
| U-Blox                            | 2         | 0.03%   |
| T & A Mobile Phones               | 2         | 0.03%   |
| Shenzhen Goodix Technology        | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1575      | 18.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 396       | 4.71%   |
| Intel Wi-Fi 6 AX200                                               | 303       | 3.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 223       | 2.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 183       | 2.18%   |
| Intel Wireless 8265 / 8275                                        | 170       | 2.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 164       | 1.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 158       | 1.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 150       | 1.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 150       | 1.78%   |
| Intel Wireless 7260                                               | 148       | 1.76%   |
| Intel Wi-Fi 6 AX201                                               | 143       | 1.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 138       | 1.64%   |
| Intel Wireless 7265                                               | 134       | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 134       | 1.59%   |
| Intel Wireless 8260                                               | 110       | 1.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 107       | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 106       | 1.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 102       | 1.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 99        | 1.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 96        | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 82        | 0.98%   |
| Broadcom BCM43142 802.11b/g/n                                     | 77        | 0.92%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 74        | 0.88%   |
| Intel Wireless 3165                                               | 69        | 0.82%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 57        | 0.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 57        | 0.68%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 54        | 0.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 53        | 0.63%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 53        | 0.63%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 52        | 0.62%   |
| Intel Ethernet Connection I218-LM                                 | 51        | 0.61%   |
| Intel Wireless 3160                                               | 50        | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 50        | 0.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 49        | 0.58%   |
| Intel Wireless-AC 9260                                            | 47        | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 47        | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 45        | 0.54%   |
| Intel Centrino Ultimate-N 6300                                    | 45        | 0.54%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 44        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2273      | 49.59%  |
| Qualcomm Atheros                      | 847       | 18.48%  |
| Realtek Semiconductor                 | 602       | 13.13%  |
| Broadcom                              | 419       | 9.14%   |
| Broadcom Limited                      | 111       | 2.42%   |
| MediaTek                              | 96        | 2.09%   |
| Ralink                                | 49        | 1.07%   |
| TP-Link                               | 40        | 0.87%   |
| Ralink Technology                     | 37        | 0.81%   |
| Dell                                  | 20        | 0.44%   |
| Sierra Wireless                       | 19        | 0.41%   |
| Qualcomm                              | 13        | 0.28%   |
| NetGear                               | 10        | 0.22%   |
| D-Link                                | 9         | 0.2%    |
| ASUSTek Computer                      | 9         | 0.2%    |
| Hewlett-Packard                       | 4         | 0.09%   |
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
| Intel Wi-Fi 6 AX200                                            | 303       | 6.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 223       | 4.83%   |
| Intel Wireless 8265 / 8275                                     | 170       | 3.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 158       | 3.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 150       | 3.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 150       | 3.25%   |
| Intel Wireless 7260                                            | 148       | 3.21%   |
| Intel Wi-Fi 6 AX201                                            | 143       | 3.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 138       | 2.99%   |
| Intel Wireless 7265                                            | 134       | 2.9%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 134       | 2.9%    |
| Intel Wireless 8260                                            | 110       | 2.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 107       | 2.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 106       | 2.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 102       | 2.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 99        | 2.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 96        | 2.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 82        | 1.78%   |
| Broadcom BCM43142 802.11b/g/n                                  | 77        | 1.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 74        | 1.6%    |
| Intel Wireless 3165                                            | 69        | 1.49%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 57        | 1.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 57        | 1.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 53        | 1.15%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 53        | 1.15%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 52        | 1.13%   |
| Intel Wireless 3160                                            | 50        | 1.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 49        | 1.06%   |
| Intel Wireless-AC 9260                                         | 47        | 1.02%   |
| Intel Centrino Ultimate-N 6300                                 | 45        | 0.97%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 44        | 0.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 42        | 0.91%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 41        | 0.89%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 40        | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 40        | 0.87%   |
| Intel Centrino Advanced-N 6235                                 | 39        | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 38        | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 33        | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 33        | 0.71%   |
| Intel Centrino Wireless-N 2230                                 | 29        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2200      | 59.57%  |
| Intel                            | 670       | 18.14%  |
| Qualcomm Atheros                 | 268       | 7.26%   |
| Broadcom                         | 167       | 4.52%   |
| Marvell Technology Group         | 63        | 1.71%   |
| Nvidia                           | 51        | 1.38%   |
| ASIX Electronics                 | 43        | 1.16%   |
| Samsung Electronics              | 33        | 0.89%   |
| Broadcom Limited                 | 33        | 0.89%   |
| DisplayLink                      | 27        | 0.73%   |
| Lenovo                           | 20        | 0.54%   |
| Xiaomi                           | 16        | 0.43%   |
| JMicron Technology               | 15        | 0.41%   |
| Google                           | 13        | 0.35%   |
| Silicon Integrated Systems [SiS] | 8         | 0.22%   |
| OnePlus Technology (Shenzhen)    | 8         | 0.22%   |
| Huawei Technologies              | 7         | 0.19%   |
| Motorola PCS                     | 6         | 0.16%   |
| TP-Link                          | 5         | 0.14%   |
| OPPO Electronics                 | 5         | 0.14%   |
| Apple                            | 5         | 0.14%   |
| Qualcomm                         | 3         | 0.08%   |
| MediaTek                         | 3         | 0.08%   |
| Linksys                          | 3         | 0.08%   |
| T & A Mobile Phones              | 2         | 0.05%   |
| LSI                              | 2         | 0.05%   |
| LG Electronics                   | 2         | 0.05%   |
| ICS Advent                       | 2         | 0.05%   |
| Hewlett-Packard                  | 2         | 0.05%   |
| ASUSTek Computer                 | 2         | 0.05%   |
| Aquantia                         | 2         | 0.05%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1575      | 42.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 396       | 10.59%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 183       | 4.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 164       | 4.39%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 54        | 1.44%   |
| Intel Ethernet Connection I218-LM                                 | 51        | 1.36%   |
| Intel Ethernet Connection (4) I219-LM                             | 50        | 1.34%   |
| Intel Ethernet Connection I219-LM                                 | 47        | 1.26%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 45        | 1.2%    |
| Intel Ethernet Connection I217-LM                                 | 41        | 1.1%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 38        | 1.02%   |
| Nvidia MCP79 Ethernet                                             | 37        | 0.99%   |
| ASIX AX88179 Gigabit Ethernet                                     | 35        | 0.94%   |
| Intel Ethernet Connection (3) I218-LM                             | 34        | 0.91%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 33        | 0.88%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 30        | 0.8%    |
| Intel 82577LM Gigabit Network Connection                          | 30        | 0.8%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 26        | 0.7%    |
| Intel Ethernet Connection (4) I219-V                              | 26        | 0.7%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 26        | 0.7%    |
| Intel Ethernet Connection (7) I219-LM                             | 25        | 0.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 24        | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 22        | 0.59%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 20        | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 19        | 0.51%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 18        | 0.48%   |
| Intel Ethernet Connection (7) I219-V                              | 18        | 0.48%   |
| Intel 82567LM Gigabit Network Connection                          | 18        | 0.48%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 18        | 0.48%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 17        | 0.45%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 17        | 0.45%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 17        | 0.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 16        | 0.43%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 16        | 0.43%   |
| Intel Ethernet Connection I219-V                                  | 16        | 0.43%   |
| Intel Ethernet Connection (13) I219-V                             | 16        | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 15        | 0.4%    |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.4%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 14        | 0.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 13        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4359      | 54.93%  |
| Ethernet | 3526      | 44.43%  |
| Modem    | 38        | 0.48%   |
| Unknown  | 13        | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3711      | 78.91%  |
| Ethernet | 992       | 21.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3225      | 73.15%  |
| 1     | 1124      | 25.49%  |
| 3     | 30        | 0.68%   |
| 0     | 30        | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3560      | 79.82%  |
| Yes  | 900       | 20.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1908      | 50.89%  |
| Qualcomm Atheros Communications | 372       | 9.92%   |
| Realtek Semiconductor           | 306       | 8.16%   |
| Apple                           | 229       | 6.11%   |
| IMC Networks                    | 200       | 5.33%   |
| Lite-On Technology              | 182       | 4.85%   |
| Broadcom                        | 181       | 4.83%   |
| Foxconn / Hon Hai               | 101       | 2.69%   |
| Dell                            | 60        | 1.6%    |
| Cambridge Silicon Radio         | 38        | 1.01%   |
| Toshiba                         | 28        | 0.75%   |
| Realtek                         | 27        | 0.72%   |
| Ralink                          | 27        | 0.72%   |
| Hewlett-Packard                 | 26        | 0.69%   |
| ASUSTek Computer                | 14        | 0.37%   |
| Foxconn International           | 11        | 0.29%   |
| Ralink Technology               | 7         | 0.19%   |
| Alps Electric                   | 7         | 0.19%   |
| Askey Computer                  | 4         | 0.11%   |
| USI                             | 3         | 0.08%   |
| Unknown                         | 3         | 0.08%   |
| Taiyo Yuden                     | 3         | 0.08%   |
| Qcom                            | 3         | 0.08%   |
| Opticis                         | 2         | 0.05%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| MediaTek                        | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Dynex                           | 1         | 0.03%   |
| Creative Technology             | 1         | 0.03%   |
| Actions                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 669       | 17.84%  |
| Intel AX201 Bluetooth                               | 369       | 9.84%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 324       | 8.64%   |
| Intel AX200 Bluetooth                               | 298       | 7.94%   |
| Qualcomm Atheros  Bluetooth Device                  | 206       | 5.49%   |
| Realtek Bluetooth Radio                             | 194       | 5.17%   |
| Apple Bluetooth Host Controller                     | 127       | 3.39%   |
| Realtek  Bluetooth 4.2 Adapter                      | 89        | 2.37%   |
| Apple Bluetooth USB Host Controller                 | 73        | 1.95%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 71        | 1.89%   |
| IMC Networks Bluetooth Radio                        | 64        | 1.71%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 60        | 1.6%    |
| IMC Networks Wireless_Device                        | 52        | 1.39%   |
| Intel AX210 Bluetooth                               | 49        | 1.31%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 47        | 1.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 43        | 1.15%   |
| Foxconn / Hon Hai Bluetooth Device                  | 43        | 1.15%   |
| Lite-On Bluetooth Device                            | 41        | 1.09%   |
| IMC Networks Bluetooth Device                       | 41        | 1.09%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 38        | 1.01%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 38        | 1.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 36        | 0.96%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 33        | 0.88%   |
| Intel Wireless-AC 3168 Bluetooth                    | 33        | 0.88%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 33        | 0.88%   |
| Intel Bluetooth Device                              | 32        | 0.85%   |
| Broadcom BCM2045B (BDC-2.1)                         | 28        | 0.75%   |
| Realtek Bluetooth Radio                             | 27        | 0.72%   |
| Ralink RT3290 Bluetooth                             | 27        | 0.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 24        | 0.64%   |
| Dell DW375 Bluetooth Module                         | 22        | 0.59%   |
| Lite-On Atheros AR3012 Bluetooth                    | 20        | 0.53%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 19        | 0.51%   |
| Foxconn / Hon Hai Wireless_Device                   | 19        | 0.51%   |
| Apple Bluetooth HCI                                 | 18        | 0.48%   |
| Lite-On Wireless_Device                             | 16        | 0.43%   |
| HP Broadcom 2070 Bluetooth Combo                    | 16        | 0.43%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 15        | 0.4%    |
| Dell BCM20702A0 Bluetooth Module                    | 14        | 0.37%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 14        | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3507      | 60.98%  |
| Nvidia                               | 1000      | 17.39%  |
| AMD                                  | 885       | 15.39%  |
| C-Media Electronics                  | 45        | 0.78%   |
| Realtek Semiconductor                | 37        | 0.64%   |
| Logitech                             | 33        | 0.57%   |
| Lenovo                               | 19        | 0.33%   |
| JMTek                                | 19        | 0.33%   |
| GN Netcom                            | 18        | 0.31%   |
| Texas Instruments                    | 13        | 0.23%   |
| Kingston Technology                  | 13        | 0.23%   |
| Apple                                | 12        | 0.21%   |
| Razer USA                            | 9         | 0.16%   |
| Silicon Integrated Systems [SiS]     | 8         | 0.14%   |
| Hewlett-Packard                      | 8         | 0.14%   |
| Generalplus Technology               | 8         | 0.14%   |
| Corsair                              | 8         | 0.14%   |
| SteelSeries ApS                      | 7         | 0.12%   |
| Sony                                 | 7         | 0.12%   |
| Plantronics                          | 7         | 0.12%   |
| Focusrite-Novation                   | 5         | 0.09%   |
| Sennheiser Communications            | 4         | 0.07%   |
| Creative Technology                  | 4         | 0.07%   |
| Tenx Technology                      | 3         | 0.05%   |
| Samson Technologies                  | 3         | 0.05%   |
| No brand                             | 3         | 0.05%   |
| ASUSTek Computer                     | 3         | 0.05%   |
| Yamaha                               | 2         | 0.03%   |
| XMOS                                 | 2         | 0.03%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.03%   |
| TerraTec Electronic                  | 2         | 0.03%   |
| Pioneer DJ                           | 2         | 0.03%   |
| GYROCOM C&C                          | 2         | 0.03%   |
| FiiO Electronics Technology          | 2         | 0.03%   |
| DSEA A/S                             | 2         | 0.03%   |
| CMX Systems                          | 2         | 0.03%   |
| Blue Microphones                     | 2         | 0.03%   |
| AudioQuest                           | 2         | 0.03%   |
| Astro Gaming                         | 2         | 0.03%   |
| Vestax                               | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 574       | 8.26%   |
| Intel Sunrise Point-LP HD Audio                                            | 503       | 7.24%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 364       | 5.24%   |
| Intel Cannon Lake PCH cAVS                                                 | 328       | 4.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 272       | 3.92%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 259       | 3.73%   |
| Intel 8 Series HD Audio Controller                                         | 221       | 3.18%   |
| Intel Haswell-ULT HD Audio Controller                                      | 219       | 3.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 202       | 2.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 193       | 2.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 176       | 2.53%   |
| Intel Comet Lake PCH cAVS                                                  | 163       | 2.35%   |
| Intel Broadwell-U Audio Controller                                         | 154       | 2.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 154       | 2.22%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 147       | 2.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 145       | 2.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 143       | 2.06%   |
| Intel Comet Lake PCH-LP cAVS                                               | 130       | 1.87%   |
| Intel CM238 HD Audio Controller                                            | 126       | 1.81%   |
| Nvidia TU106 High Definition Audio Controller                              | 125       | 1.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 122       | 1.76%   |
| AMD FCH Azalia Controller                                                  | 118       | 1.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 110       | 1.58%   |
| Nvidia GP107GL High Definition Audio Controller                            | 89        | 1.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 82        | 1.18%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 72        | 1.04%   |
| AMD Kabini HDMI/DP Audio                                                   | 68        | 0.98%   |
| Nvidia GA106 High Definition Audio Controller                              | 66        | 0.95%   |
| Nvidia GP106 High Definition Audio Controller                              | 63        | 0.91%   |
| Nvidia GA104 High Definition Audio Controller                              | 62        | 0.89%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 62        | 0.89%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 53        | 0.76%   |
| Nvidia TU116 High Definition Audio Controller                              | 52        | 0.75%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 49        | 0.71%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 48        | 0.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 46        | 0.66%   |
| AMD High Definition Audio Controller                                       | 44        | 0.63%   |
| Nvidia GK107 HDMI Audio Controller                                         | 43        | 0.62%   |
| Nvidia MCP79 High Definition Audio                                         | 41        | 0.59%   |
| Nvidia GF108 High Definition Audio Controller                              | 38        | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 414       | 29.18%  |
| SK hynix            | 315       | 22.2%   |
| Micron Technology   | 191       | 13.46%  |
| Kingston            | 120       | 8.46%   |
| Crucial             | 78        | 5.5%    |
| Unknown             | 48        | 3.38%   |
| A-DATA Technology   | 32        | 2.26%   |
| Smart               | 26        | 1.83%   |
| Ramaxel Technology  | 23        | 1.62%   |
| Corsair             | 21        | 1.48%   |
| Goldkey             | 20        | 1.41%   |
| Elpida              | 18        | 1.27%   |
| Neo Forza           | 16        | 1.13%   |
| G.Skill             | 13        | 0.92%   |
| Unknown             | 10        | 0.7%    |
| Unknown (ABCD)      | 9         | 0.63%   |
| Smart Brazil        | 9         | 0.63%   |
| Teikon              | 6         | 0.42%   |
| Team                | 6         | 0.42%   |
| Nanya Technology    | 6         | 0.42%   |
| Apacer              | 5         | 0.35%   |
| Patriot             | 3         | 0.21%   |
| High Bridge         | 3         | 0.21%   |
| Avant               | 3         | 0.21%   |
| Timetec             | 2         | 0.14%   |
| PNY                 | 2         | 0.14%   |
| GSkill              | 2         | 0.14%   |
| GOODRAM             | 2         | 0.14%   |
| Gold Key            | 2         | 0.14%   |
| ChangXin Memory     | 2         | 0.14%   |
| Unknown (8A02)      | 1         | 0.07%   |
| Unknown (898F)      | 1         | 0.07%   |
| Transcend           | 1         | 0.07%   |
| Silicon Power       | 1         | 0.07%   |
| RZX                 | 1         | 0.07%   |
| PUSKILL             | 1         | 0.07%   |
| Multilaser          | 1         | 0.07%   |
| Magnum Tech         | 1         | 0.07%   |
| Lenovo              | 1         | 0.07%   |
| Hewlett-Packard     | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 35        | 2.35%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 26        | 1.75%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 23        | 1.54%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 21        | 1.41%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 17        | 1.14%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 17        | 1.14%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 17        | 1.14%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 1.01%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 15        | 1.01%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 15        | 1.01%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.94%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.94%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 13        | 0.87%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 11        | 0.74%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.74%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.74%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.74%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 11        | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.67%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 10        | 0.67%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 10        | 0.67%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 0.67%   |
| Unknown                                                          | 10        | 0.67%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 9         | 0.6%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 9         | 0.6%    |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 9         | 0.6%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 9         | 0.6%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 9         | 0.6%    |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 9         | 0.6%    |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 9         | 0.6%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 9         | 0.6%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.54%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 8         | 0.54%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.54%   |
| Samsung RAM K4AAG165WA-BCTD 8GB SODIMM DDR4 2667MT/s             | 8         | 0.54%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 8         | 0.54%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 7         | 0.47%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.47%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.47%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 7         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 789       | 66.86%  |
| DDR3    | 231       | 19.58%  |
| LPDDR4  | 61        | 5.17%   |
| LPDDR3  | 55        | 4.66%   |
| DDR5    | 16        | 1.36%   |
| DDR2    | 10        | 0.85%   |
| LPDDR5  | 9         | 0.76%   |
| Unknown | 5         | 0.42%   |
| SDRAM   | 4         | 0.34%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1035      | 86.11%  |
| Row Of Chips | 152       | 12.65%  |
| Chip         | 11        | 0.92%   |
| DIMM         | 3         | 0.25%   |
| Unknown      | 1         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 588       | 45.51%  |
| 4096  | 316       | 24.46%  |
| 16384 | 252       | 19.5%   |
| 2048  | 67        | 5.19%   |
| 32768 | 61        | 4.72%   |
| 1024  | 8         | 0.62%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 385       | 29.87%  |
| 3200    | 294       | 22.81%  |
| 1600    | 187       | 14.51%  |
| 2400    | 124       | 9.62%   |
| 2133    | 80        | 6.21%   |
| 4267    | 28        | 2.17%   |
| 1334    | 28        | 2.17%   |
| 3266    | 23        | 1.78%   |
| 1333    | 21        | 1.63%   |
| 8400    | 17        | 1.32%   |
| 4800    | 16        | 1.24%   |
| 1867    | 15        | 1.16%   |
| 4266    | 11        | 0.85%   |
| 6400    | 10        | 0.78%   |
| 800     | 9         | 0.7%    |
| 1067    | 8         | 0.62%   |
| 3733    | 7         | 0.54%   |
| 1866    | 5         | 0.39%   |
| 2933    | 4         | 0.31%   |
| 667     | 4         | 0.31%   |
| Unknown | 3         | 0.23%   |
| 4199    | 2         | 0.16%   |
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
| Hewlett-Packard     | 7         | 30.43%  |
| Seiko Epson         | 5         | 21.74%  |
| Canon               | 4         | 17.39%  |
| Brother Industries  | 3         | 13.04%  |
| Xerox               | 1         | 4.35%   |
| Samsung Electronics | 1         | 4.35%   |
| MIIIW               | 1         | 4.35%   |
| ICS Advent          | 1         | 4.35%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Xerox B215                      | 1         | 4.35%   |
| Seiko Epson WF-3520 Series      | 1         | 4.35%   |
| Seiko Epson L4150 Series        | 1         | 4.35%   |
| Seiko Epson L3110 Series        | 1         | 4.35%   |
| Seiko Epson L132 Series         | 1         | 4.35%   |
| Seiko Epson ET-3750 Series      | 1         | 4.35%   |
| Samsung M2020 Series            | 1         | 4.35%   |
| MIIIW MW Keyboard Air Mini      | 1         | 4.35%   |
| ICS Advent Parallel Adapter     | 1         | 4.35%   |
| HP Ink Tank Wireless 410 series | 1         | 4.35%   |
| HP ENVY Photo 7800 series       | 1         | 4.35%   |
| HP ENVY 4520 series             | 1         | 4.35%   |
| HP Deskjet 3050 J610 series     | 1         | 4.35%   |
| HP Deskjet 2540 series          | 1         | 4.35%   |
| HP Deskjet 2050 J510            | 1         | 4.35%   |
| HP Color LaserJet CP2025dn      | 1         | 4.35%   |
| Canon PIXMA MX920 Series        | 1         | 4.35%   |
| Canon GX7000 series             | 1         | 4.35%   |
| Canon G4010 series              | 1         | 4.35%   |
| Canon E400 series               | 1         | 4.35%   |
| Brother HL-L2320D series        | 1         | 4.35%   |
| Brother HL-3170CDW series       | 1         | 4.35%   |
| Brother HL-2270DW Laser Printer | 1         | 4.35%   |

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
| Chicony Electronics                    | 946       | 24.13%  |
| IMC Networks                           | 428       | 10.92%  |
| Acer                                   | 401       | 10.23%  |
| Microdia                               | 395       | 10.08%  |
| Realtek Semiconductor                  | 326       | 8.32%   |
| Sunplus Innovation Technology          | 216       | 5.51%   |
| Quanta                                 | 190       | 4.85%   |
| Apple                                  | 173       | 4.41%   |
| Cheng Uei Precision Industry (Foxlink) | 142       | 3.62%   |
| Suyin                                  | 120       | 3.06%   |
| Syntek                                 | 98        | 2.5%    |
| Lite-On Technology                     | 75        | 1.91%   |
| Silicon Motion                         | 58        | 1.48%   |
| Logitech                               | 51        | 1.3%    |
| Luxvisions Innotech Limited            | 49        | 1.25%   |
| Ricoh                                  | 37        | 0.94%   |
| Alcor Micro                            | 28        | 0.71%   |
| Samsung Electronics                    | 21        | 0.54%   |
| Sonix Technology                       | 16        | 0.41%   |
| ALi                                    | 11        | 0.28%   |
| SunplusIT                              | 10        | 0.26%   |
| Primax Electronics                     | 10        | 0.26%   |
| DigiTech                               | 10        | 0.26%   |
| Microsoft                              | 9         | 0.23%   |
| Importek                               | 9         | 0.23%   |
| Z-Star Microelectronics                | 8         | 0.2%    |
| Lenovo                                 | 8         | 0.2%    |
| Intel                                  | 7         | 0.18%   |
| Unknown                                | 5         | 0.13%   |
| OmniVision Technologies                | 5         | 0.13%   |
| Generalplus Technology                 | 5         | 0.13%   |
| Foxconn / Hon Hai                      | 4         | 0.1%    |
| DJJHFA1BIF5595                         | 4         | 0.1%    |
| USB Camera                             | 3         | 0.08%   |
| Razer USA                              | 3         | 0.08%   |
| MacroSilicon                           | 3         | 0.08%   |
| AVerMedia Technologies                 | 3         | 0.08%   |
| Tobii Technology AB                    | 2         | 0.05%   |
| Sunplus Technology                     | 2         | 0.05%   |
| Mustek Systems                         | 2         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 221       | 5.61%   |
| Chicony Integrated Camera                           | 172       | 4.37%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 139       | 3.53%   |
| Realtek Integrated_Webcam_HD                        | 135       | 3.43%   |
| Chicony HD WebCam                                   | 129       | 3.27%   |
| IMC Networks Integrated Camera                      | 118       | 2.99%   |
| Chicony USB2.0 Camera                               | 93        | 2.36%   |
| Acer BisonCam,NB Pro                                | 88        | 2.23%   |
| Acer Integrated Camera                              | 86        | 2.18%   |
| Sunplus Integrated_Webcam_HD                        | 63        | 1.6%    |
| Syntek Integrated Camera                            | 59        | 1.5%    |
| Apple Built-in iSight                               | 59        | 1.5%    |
| Apple FaceTime HD Camera                            | 55        | 1.4%    |
| Acer HD Webcam                                      | 51        | 1.29%   |
| Quanta HD User Facing                               | 46        | 1.17%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 45        | 1.14%   |
| Acer BisonCam, NB Pro                               | 39        | 0.99%   |
| Chicony USB 2.0 Camera                              | 37        | 0.94%   |
| Apple iPhone5/5C/5S/6                               | 36        | 0.91%   |
| Chicony TOSHIBA Web Camera - HD                     | 33        | 0.84%   |
| Quanta HD Webcam                                    | 31        | 0.79%   |
| Sunplus HD WebCam                                   | 30        | 0.76%   |
| Microdia Integrated Webcam                          | 30        | 0.76%   |
| Lite-On Integrated Camera                           | 30        | 0.76%   |
| Chicony Integrated Camera (1280x720@30)             | 30        | 0.76%   |
| Chicony HD User Facing                              | 29        | 0.74%   |
| Sunplus ASUS Webcam                                 | 28        | 0.71%   |
| Microdia Laptop_Integrated_Webcam_HD                | 28        | 0.71%   |
| Chicony USB2.0 HD UVC WebCam                        | 27        | 0.69%   |
| Acer SunplusIT Integrated Camera                    | 26        | 0.66%   |
| Chicony USB2.0 VGA UVC WebCam                       | 25        | 0.63%   |
| Realtek USB Camera                                  | 23        | 0.58%   |
| Chicony HP HD Camera                                | 23        | 0.58%   |
| Acer Lenovo EasyCamera                              | 23        | 0.58%   |
| Realtek Integrated Webcam                           | 22        | 0.56%   |
| Quanta VGA WebCam                                   | 22        | 0.56%   |
| Chicony HP TrueVision HD Camera                     | 22        | 0.56%   |
| Quanta HP TrueVision HD Camera                      | 21        | 0.53%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 21        | 0.53%   |
| Chicony HP Wide Vision HD Camera                    | 21        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 227       | 30.11%  |
| Synaptics                          | 226       | 29.97%  |
| Shenzhen Goodix Technology         | 139       | 18.44%  |
| Upek                               | 43        | 5.7%    |
| Elan Microelectronics              | 41        | 5.44%   |
| LighTuning Technology              | 35        | 4.64%   |
| AuthenTec                          | 26        | 3.45%   |
| STMicroelectronics                 | 7         | 0.93%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.4%    |
| Focal-systems.Corp                 | 3         | 0.4%    |
| HOLTEK                             | 2         | 0.27%   |
| Samsung Electronics                | 1         | 0.13%   |
| DigitalPersona                     | 1         | 0.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 71        | 9.42%   |
| Shenzhen Goodix  Fingerprint Device                                        | 65        | 8.62%   |
| Unknown                                                                    | 65        | 8.62%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 53        | 7.03%   |
| Shenzhen Goodix FingerPrint                                                | 45        | 5.97%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 42        | 5.57%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 40        | 5.31%   |
| Elan ELAN:Fingerprint                                                      | 31        | 4.11%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 30        | 3.98%   |
| Shenzhen Goodix Fingerprint Reader                                         | 29        | 3.85%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 19        | 2.52%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 2.39%   |
| Validity Sensors VFS491                                                    | 18        | 2.39%   |
| Validity Sensors Fingerprint scanner                                       | 18        | 2.39%   |
| Synaptics WBDI Device                                                      | 18        | 2.39%   |
| Validity Sensors Synaptics WBDI                                            | 17        | 2.25%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 1.99%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 14        | 1.86%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 1.86%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 10        | 1.33%   |
| Elan ELAN:ARM-M4                                                           | 10        | 1.33%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 9         | 1.19%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 9         | 1.19%   |
| Synaptics  WBDI                                                            | 8         | 1.06%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 1.06%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 1.06%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 0.93%   |
| AuthenTec AES2810                                                          | 7         | 0.93%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 0.8%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 0.8%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 0.66%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 0.66%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.53%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.4%    |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.4%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.4%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 0.4%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.4%    |
| AuthenTec AES1600                                                          | 3         | 0.4%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 135       | 46.55%  |
| Alcor Micro               | 80        | 27.59%  |
| Upek                      | 28        | 9.66%   |
| O2 Micro                  | 22        | 7.59%   |
| Lenovo                    | 17        | 5.86%   |
| Aladdin Knowledge Systems | 2         | 0.69%   |
| SCM Microsystems          | 1         | 0.34%   |
| OmniKey                   | 1         | 0.34%   |
| Giesecke & Devrient       | 1         | 0.34%   |
| Gemalto (was Gemplus)     | 1         | 0.34%   |
| Clay Logic                | 1         | 0.34%   |
| Advanced Card Systems     | 1         | 0.34%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 80        | 27.59%  |
| Broadcom BCM5880 Secure Applications Processor                               | 44        | 15.17%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 36        | 12.41%  |
| Broadcom 5880                                                                | 36        | 12.41%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 28        | 9.66%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 6.21%   |
| Lenovo Integrated Smart Card Reader                                          | 17        | 5.86%   |
| Broadcom 58200                                                               | 17        | 5.86%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.38%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.69%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.69%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.34%   |
| OmniKey CardMan 4321                                                         | 1         | 0.34%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.34%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.34%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.34%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.34%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2821      | 63%     |
| 1     | 1299      | 29.01%  |
| 2     | 306       | 6.83%   |
| 3     | 46        | 1.03%   |
| 4     | 5         | 0.11%   |
| 5     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 736       | 36.74%  |
| Chipcard                 | 282       | 14.08%  |
| Multimedia controller    | 277       | 13.83%  |
| Net/wireless             | 243       | 12.13%  |
| Graphics card            | 220       | 10.98%  |
| Bluetooth                | 63        | 3.15%   |
| Camera                   | 38        | 1.9%    |
| Storage                  | 37        | 1.85%   |
| Net/ethernet             | 27        | 1.35%   |
| Sound                    | 21        | 1.05%   |
| Communication controller | 14        | 0.7%    |
| Card reader              | 14        | 0.7%    |
| Network                  | 9         | 0.45%   |
| Modem                    | 9         | 0.45%   |
| Storage/ide              | 5         | 0.25%   |
| Storage/nvme             | 2         | 0.1%    |
| Flash memory             | 2         | 0.1%    |
| Firewire controller      | 2         | 0.1%    |
| Unclassified device      | 1         | 0.05%   |
| Dvb card                 | 1         | 0.05%   |


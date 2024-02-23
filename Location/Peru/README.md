Linux in Peru - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Linux in Peru.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Peru/Desktop/README.md) and [notebooks](/Location/Peru/Notebook/README.md).

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

Total: 676

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 05XGC8 A01                  | Desktop     | [29ae38936a](https://linux-hardware.org/?probe=29ae38936a) | Feb 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [6f80a7214c](https://linux-hardware.org/?probe=6f80a7214c) | Feb 01, 2024 |
| ASUSTek       | G75VX                       | Notebook    | [5c270f1082](https://linux-hardware.org/?probe=5c270f1082) | Jan 30, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [0a1087fdad](https://linux-hardware.org/?probe=0a1087fdad) | Jan 29, 2024 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [3f4325d337](https://linux-hardware.org/?probe=3f4325d337) | Jan 29, 2024 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [8c1fb214b8](https://linux-hardware.org/?probe=8c1fb214b8) | Jan 25, 2024 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [f3512d75e9](https://linux-hardware.org/?probe=f3512d75e9) | Jan 24, 2024 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [ff5718cb34](https://linux-hardware.org/?probe=ff5718cb34) | Jan 20, 2024 |
| Dell          | Latitude 7430               | Notebook    | [153f1a144c](https://linux-hardware.org/?probe=153f1a144c) | Jan 19, 2024 |
| Dell          | Latitude 7430               | Notebook    | [a05210eeb4](https://linux-hardware.org/?probe=a05210eeb4) | Jan 19, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [947096fa7f](https://linux-hardware.org/?probe=947096fa7f) | Jan 16, 2024 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [89b8dbd2bb](https://linux-hardware.org/?probe=89b8dbd2bb) | Jan 13, 2024 |
| System76      | Adder WS                    | Notebook    | [94120ee028](https://linux-hardware.org/?probe=94120ee028) | Jan 11, 2024 |
| ASUSTek       | UX510UXK                    | Notebook    | [17be26f2de](https://linux-hardware.org/?probe=17be26f2de) | Jan 04, 2024 |
| Toshiba       | Satellite P55-B             | Notebook    | [9a1e5dc1f6](https://linux-hardware.org/?probe=9a1e5dc1f6) | Dec 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [460fe0575c](https://linux-hardware.org/?probe=460fe0575c) | Dec 30, 2023 |
| ASRock        | X570 Taichi Razer Editio... | Desktop     | [08d900cdbb](https://linux-hardware.org/?probe=08d900cdbb) | Dec 27, 2023 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [1594f8077b](https://linux-hardware.org/?probe=1594f8077b) | Dec 27, 2023 |
| Sony          | SVS13A25PLB                 | Notebook    | [9b32de2519](https://linux-hardware.org/?probe=9b32de2519) | Dec 27, 2023 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [c4fe258ada](https://linux-hardware.org/?probe=c4fe258ada) | Dec 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bcae8d434f](https://linux-hardware.org/?probe=bcae8d434f) | Dec 19, 2023 |
| Dell          | Latitude E5470              | Notebook    | [9aa1f53217](https://linux-hardware.org/?probe=9aa1f53217) | Dec 18, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [f306ab4590](https://linux-hardware.org/?probe=f306ab4590) | Dec 17, 2023 |
| Toshiba       | Satellite A300              | Notebook    | [5e373b58ac](https://linux-hardware.org/?probe=5e373b58ac) | Dec 15, 2023 |
| ASRock        | B560M Pro4/ac               | Notebook    | [0dd2927c25](https://linux-hardware.org/?probe=0dd2927c25) | Dec 14, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [57a63775b2](https://linux-hardware.org/?probe=57a63775b2) | Dec 05, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [5dcf20cb88](https://linux-hardware.org/?probe=5dcf20cb88) | Dec 04, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [2f07094763](https://linux-hardware.org/?probe=2f07094763) | Dec 04, 2023 |
| ASRock        | H310CM-HDV/M.2              | Desktop     | [4b91971e62](https://linux-hardware.org/?probe=4b91971e62) | Dec 01, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [fb45c81af9](https://linux-hardware.org/?probe=fb45c81af9) | Nov 26, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [5be7c208c3](https://linux-hardware.org/?probe=5be7c208c3) | Nov 20, 2023 |
| Gigabyte      | B550M K                     | Notebook    | [989886ee56](https://linux-hardware.org/?probe=989886ee56) | Nov 19, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [f4de613bd5](https://linux-hardware.org/?probe=f4de613bd5) | Nov 15, 2023 |
| Dell          | Latitude 5490               | Notebook    | [ac938f1435](https://linux-hardware.org/?probe=ac938f1435) | Nov 08, 2023 |
| Dell          | Latitude E5470              | Notebook    | [bbbdcac07b](https://linux-hardware.org/?probe=bbbdcac07b) | Nov 07, 2023 |
| Dell          | Latitude E5470              | Notebook    | [19fc06d0b2](https://linux-hardware.org/?probe=19fc06d0b2) | Nov 07, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [de293a4621](https://linux-hardware.org/?probe=de293a4621) | Nov 03, 2023 |
| HP            | 18E7                        | Desktop     | [212d6dba47](https://linux-hardware.org/?probe=212d6dba47) | Nov 02, 2023 |
| HP            | 18E7                        | Desktop     | [7064df5d87](https://linux-hardware.org/?probe=7064df5d87) | Nov 02, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [d0be3aec4e](https://linux-hardware.org/?probe=d0be3aec4e) | Nov 01, 2023 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [8a9f37b293](https://linux-hardware.org/?probe=8a9f37b293) | Oct 31, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [c3d5a72f41](https://linux-hardware.org/?probe=c3d5a72f41) | Oct 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [8f20a345e3](https://linux-hardware.org/?probe=8f20a345e3) | Oct 24, 2023 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [dbc150b2b5](https://linux-hardware.org/?probe=dbc150b2b5) | Oct 13, 2023 |
| HP            | 14                          | Notebook    | [e207fce0d4](https://linux-hardware.org/?probe=e207fce0d4) | Oct 12, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [2bb1495e06](https://linux-hardware.org/?probe=2bb1495e06) | Oct 08, 2023 |
| GIADA         | Braswell JHS60S             | Desktop     | [ed113a0bc0](https://linux-hardware.org/?probe=ed113a0bc0) | Oct 08, 2023 |
| HP            | EliteBook 2760p             | Notebook    | [e9d026d0df](https://linux-hardware.org/?probe=e9d026d0df) | Sep 29, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [e998b320d8](https://linux-hardware.org/?probe=e998b320d8) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [952169c1ce](https://linux-hardware.org/?probe=952169c1ce) | Sep 24, 2023 |
| HP            | Pavilion dv4                | Notebook    | [b1ee39c175](https://linux-hardware.org/?probe=b1ee39c175) | Sep 24, 2023 |
| ASRock        | G31M-S                      | Desktop     | [f1325a7f15](https://linux-hardware.org/?probe=f1325a7f15) | Sep 23, 2023 |
| ASUSTek       | V230IC                      | Desktop     | [aea46e7fc6](https://linux-hardware.org/?probe=aea46e7fc6) | Sep 21, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [9d8e946b59](https://linux-hardware.org/?probe=9d8e946b59) | Sep 21, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [18a02021f6](https://linux-hardware.org/?probe=18a02021f6) | Sep 21, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [e9c24b2427](https://linux-hardware.org/?probe=e9c24b2427) | Sep 18, 2023 |
| ASUSTek       | G752VY                      | Notebook    | [7d3353b537](https://linux-hardware.org/?probe=7d3353b537) | Sep 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [9d3a7e1014](https://linux-hardware.org/?probe=9d3a7e1014) | Sep 14, 2023 |
| HP            | 8433 11                     | Desktop     | [6160c13209](https://linux-hardware.org/?probe=6160c13209) | Sep 12, 2023 |
| HP            | 8433 11                     | Desktop     | [2fbe297e6c](https://linux-hardware.org/?probe=2fbe297e6c) | Sep 12, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [09c2d451ab](https://linux-hardware.org/?probe=09c2d451ab) | Sep 11, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [38a80416eb](https://linux-hardware.org/?probe=38a80416eb) | Sep 10, 2023 |
| Google        | Treeya                      | Notebook    | [a4db63abbe](https://linux-hardware.org/?probe=a4db63abbe) | Sep 10, 2023 |
| HP            | Pavilion dv4                | Notebook    | [0b01aaddd6](https://linux-hardware.org/?probe=0b01aaddd6) | Sep 06, 2023 |
| Google        | Treeya                      | Notebook    | [fcc8d7d8a1](https://linux-hardware.org/?probe=fcc8d7d8a1) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX B460-H GAMING     | Desktop     | [865ce7b55b](https://linux-hardware.org/?probe=865ce7b55b) | Sep 04, 2023 |
| HP            | Notebook                    | Notebook    | [3a7a5608af](https://linux-hardware.org/?probe=3a7a5608af) | Sep 04, 2023 |
| Dell          | Latitude 5490               | Notebook    | [392d7335ed](https://linux-hardware.org/?probe=392d7335ed) | Sep 03, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [47ef8122dc](https://linux-hardware.org/?probe=47ef8122dc) | Sep 03, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [89e3ba3d7d](https://linux-hardware.org/?probe=89e3ba3d7d) | Aug 28, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [0150e826ac](https://linux-hardware.org/?probe=0150e826ac) | Aug 28, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [4c9a89e532](https://linux-hardware.org/?probe=4c9a89e532) | Aug 27, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [c3b97aa105](https://linux-hardware.org/?probe=c3b97aa105) | Aug 27, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [82923ee337](https://linux-hardware.org/?probe=82923ee337) | Aug 18, 2023 |
| ASUSTek       | GL552VX                     | Notebook    | [fbe195ec09](https://linux-hardware.org/?probe=fbe195ec09) | Aug 17, 2023 |
| ASUSTek       | GL552VX                     | Notebook    | [37a66a073b](https://linux-hardware.org/?probe=37a66a073b) | Aug 17, 2023 |
| HP            | ZBook 15                    | Notebook    | [97923a8762](https://linux-hardware.org/?probe=97923a8762) | Aug 15, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [b5685bdafc](https://linux-hardware.org/?probe=b5685bdafc) | Aug 10, 2023 |
| ASRock        | B460M Pro4                  | Desktop     | [66f1fd8cc5](https://linux-hardware.org/?probe=66f1fd8cc5) | Aug 07, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [87d27d2a99](https://linux-hardware.org/?probe=87d27d2a99) | Aug 04, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [08e20bb994](https://linux-hardware.org/?probe=08e20bb994) | Jul 31, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [bb88f3afdc](https://linux-hardware.org/?probe=bb88f3afdc) | Jul 31, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [c51105da6a](https://linux-hardware.org/?probe=c51105da6a) | Jul 28, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [8cde0390c4](https://linux-hardware.org/?probe=8cde0390c4) | Jul 26, 2023 |
| HP            | ProBook 440 G2              | Notebook    | [85168259e3](https://linux-hardware.org/?probe=85168259e3) | Jul 25, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [71ca83faee](https://linux-hardware.org/?probe=71ca83faee) | Jul 23, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [c7a062709f](https://linux-hardware.org/?probe=c7a062709f) | Jul 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [51128412d5](https://linux-hardware.org/?probe=51128412d5) | Jul 16, 2023 |
| Acer          | Predator PH16-71            | Notebook    | [1917d24a87](https://linux-hardware.org/?probe=1917d24a87) | Jul 15, 2023 |
| HP            | 83EE                        | Desktop     | [af63e7b8fd](https://linux-hardware.org/?probe=af63e7b8fd) | Jul 12, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [477ec4d403](https://linux-hardware.org/?probe=477ec4d403) | Jul 11, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [32659f379c](https://linux-hardware.org/?probe=32659f379c) | Jul 09, 2023 |
| HP            | 240 G7 Notebook PC          | Notebook    | [e7d87f5a64](https://linux-hardware.org/?probe=e7d87f5a64) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [265dc6c0e9](https://linux-hardware.org/?probe=265dc6c0e9) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [335f69285d](https://linux-hardware.org/?probe=335f69285d) | Jul 05, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [99c60820c5](https://linux-hardware.org/?probe=99c60820c5) | Jul 05, 2023 |
| HP            | 1493                        | Desktop     | [b22e0342bc](https://linux-hardware.org/?probe=b22e0342bc) | Jun 25, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [2b4069db98](https://linux-hardware.org/?probe=2b4069db98) | Jun 25, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [99341c9ba0](https://linux-hardware.org/?probe=99341c9ba0) | Jun 23, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [1d6a241c9e](https://linux-hardware.org/?probe=1d6a241c9e) | Jun 23, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [34cfc4a037](https://linux-hardware.org/?probe=34cfc4a037) | Jun 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [57f37d5836](https://linux-hardware.org/?probe=57f37d5836) | Jun 10, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [1794287cf0](https://linux-hardware.org/?probe=1794287cf0) | Jun 09, 2023 |
| HP            | 14                          | Notebook    | [1540a787fb](https://linux-hardware.org/?probe=1540a787fb) | Jun 09, 2023 |
| HP            | 14                          | Notebook    | [1404218cab](https://linux-hardware.org/?probe=1404218cab) | Jun 09, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [576a624a1b](https://linux-hardware.org/?probe=576a624a1b) | Jun 09, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c22081b097](https://linux-hardware.org/?probe=c22081b097) | Jun 09, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [97d002b53a](https://linux-hardware.org/?probe=97d002b53a) | Jun 08, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [8f160a999a](https://linux-hardware.org/?probe=8f160a999a) | Jun 08, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [bb571d888d](https://linux-hardware.org/?probe=bb571d888d) | Jun 08, 2023 |
| AMI           | Cherry Trail CR             | Desktop     | [5816e6a1cf](https://linux-hardware.org/?probe=5816e6a1cf) | Jun 07, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [8d70c1dd42](https://linux-hardware.org/?probe=8d70c1dd42) | Jun 07, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [d981de6f45](https://linux-hardware.org/?probe=d981de6f45) | Jun 06, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [a1bcda2245](https://linux-hardware.org/?probe=a1bcda2245) | Jun 05, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [a2c31cdc69](https://linux-hardware.org/?probe=a2c31cdc69) | Jun 05, 2023 |
| HP            | 1493                        | Desktop     | [b7432a020a](https://linux-hardware.org/?probe=b7432a020a) | Jun 04, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [cadfadec0e](https://linux-hardware.org/?probe=cadfadec0e) | Jun 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e242ec473b](https://linux-hardware.org/?probe=e242ec473b) | Jun 01, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [a5ebbfe1ef](https://linux-hardware.org/?probe=a5ebbfe1ef) | May 31, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [24775c04a5](https://linux-hardware.org/?probe=24775c04a5) | May 30, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [d6a2216b0f](https://linux-hardware.org/?probe=d6a2216b0f) | May 30, 2023 |
| HP            | 14                          | Notebook    | [977d26c9b5](https://linux-hardware.org/?probe=977d26c9b5) | May 29, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [193fbef9a1](https://linux-hardware.org/?probe=193fbef9a1) | May 28, 2023 |
| Lenovo        | 3111 NOK                    | Mini pc     | [00e1812234](https://linux-hardware.org/?probe=00e1812234) | May 28, 2023 |
| ASUSTek       | PRIME X299-A                | Desktop     | [e52868c107](https://linux-hardware.org/?probe=e52868c107) | May 25, 2023 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [3ab3a101e8](https://linux-hardware.org/?probe=3ab3a101e8) | May 21, 2023 |
| Sony          | VPCEL36FJ                   | Notebook    | [c372bac204](https://linux-hardware.org/?probe=c372bac204) | May 21, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [8f2ccf9c6d](https://linux-hardware.org/?probe=8f2ccf9c6d) | May 21, 2023 |
| Lenovo        | ThinkPad L460 20FVS3JK00    | Notebook    | [c812ee44af](https://linux-hardware.org/?probe=c812ee44af) | May 18, 2023 |
| Dell          | Latitude E7450              | Notebook    | [cb96fcfaff](https://linux-hardware.org/?probe=cb96fcfaff) | May 12, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [b63292a4f9](https://linux-hardware.org/?probe=b63292a4f9) | May 11, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [21ecf73d3a](https://linux-hardware.org/?probe=21ecf73d3a) | May 09, 2023 |
| MSI           | PS42 Modern 8RA             | Notebook    | [8371e35044](https://linux-hardware.org/?probe=8371e35044) | May 08, 2023 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [f79b5c8672](https://linux-hardware.org/?probe=f79b5c8672) | May 08, 2023 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [223431f202](https://linux-hardware.org/?probe=223431f202) | May 08, 2023 |
| Dell          | G5 5505                     | Notebook    | [94e01ce854](https://linux-hardware.org/?probe=94e01ce854) | May 07, 2023 |
| Dell          | G5 5505                     | Notebook    | [b484646926](https://linux-hardware.org/?probe=b484646926) | May 07, 2023 |
| HP            | Pavilion 11                 | Notebook    | [696ac990d2](https://linux-hardware.org/?probe=696ac990d2) | May 07, 2023 |
| HP            | Pavilion g4                 | Notebook    | [5e3bd3ea22](https://linux-hardware.org/?probe=5e3bd3ea22) | May 06, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [d1dc588f69](https://linux-hardware.org/?probe=d1dc588f69) | May 05, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [9d3ea79ded](https://linux-hardware.org/?probe=9d3ea79ded) | May 04, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [f922f80a69](https://linux-hardware.org/?probe=f922f80a69) | Apr 28, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [b4d8bd0f23](https://linux-hardware.org/?probe=b4d8bd0f23) | Apr 24, 2023 |
| Toshiba       | Satellite C45-A             | Notebook    | [3fd496c5f8](https://linux-hardware.org/?probe=3fd496c5f8) | Apr 16, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [426140ece2](https://linux-hardware.org/?probe=426140ece2) | Apr 12, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [7c32eb6bf9](https://linux-hardware.org/?probe=7c32eb6bf9) | Apr 11, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [cabf7adac2](https://linux-hardware.org/?probe=cabf7adac2) | Apr 11, 2023 |
| HP            | 86F3 00100                  | All in one  | [5ed7d0b86c](https://linux-hardware.org/?probe=5ed7d0b86c) | Apr 06, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [8c33d7498d](https://linux-hardware.org/?probe=8c33d7498d) | Apr 05, 2023 |
| eMachines     | D725                        | Notebook    | [f3cdf26e60](https://linux-hardware.org/?probe=f3cdf26e60) | Apr 04, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [3995abb8b8](https://linux-hardware.org/?probe=3995abb8b8) | Apr 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7a61d16701](https://linux-hardware.org/?probe=7a61d16701) | Apr 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | Notebook    | [a6c0f30f2f](https://linux-hardware.org/?probe=a6c0f30f2f) | Apr 03, 2023 |
| HP            | 1850                        | Desktop     | [162ec03859](https://linux-hardware.org/?probe=162ec03859) | Apr 02, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [5be9a0230e](https://linux-hardware.org/?probe=5be9a0230e) | Apr 01, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [1f0b0c32ca](https://linux-hardware.org/?probe=1f0b0c32ca) | Apr 01, 2023 |
| Acer          | Aspire ES1-531              | Notebook    | [aedba72f70](https://linux-hardware.org/?probe=aedba72f70) | Mar 31, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [871c53d3f3](https://linux-hardware.org/?probe=871c53d3f3) | Mar 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [0d7e6b4a80](https://linux-hardware.org/?probe=0d7e6b4a80) | Mar 12, 2023 |
| HP            | 2B3B                        | All in one  | [cb25c51987](https://linux-hardware.org/?probe=cb25c51987) | Mar 11, 2023 |
| Lenovo        | ThinkPad T450 20BUA05K00    | Notebook    | [a496755d7a](https://linux-hardware.org/?probe=a496755d7a) | Mar 10, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a0ac521beb](https://linux-hardware.org/?probe=a0ac521beb) | Mar 07, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [3710f0f407](https://linux-hardware.org/?probe=3710f0f407) | Mar 07, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [5a1521197e](https://linux-hardware.org/?probe=5a1521197e) | Mar 07, 2023 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [e05606240c](https://linux-hardware.org/?probe=e05606240c) | Feb 28, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [9f543932d2](https://linux-hardware.org/?probe=9f543932d2) | Feb 26, 2023 |
| HP            | Notebook                    | Notebook    | [b929a8ff3c](https://linux-hardware.org/?probe=b929a8ff3c) | Feb 24, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [f6c80ff7a9](https://linux-hardware.org/?probe=f6c80ff7a9) | Feb 20, 2023 |
| HP            | 14                          | Notebook    | [0244e880e1](https://linux-hardware.org/?probe=0244e880e1) | Feb 19, 2023 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [4bcd17d5a6](https://linux-hardware.org/?probe=4bcd17d5a6) | Feb 17, 2023 |
| Intel         | H61                         | Desktop     | [90e4a9358f](https://linux-hardware.org/?probe=90e4a9358f) | Feb 17, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [e4ee3e1438](https://linux-hardware.org/?probe=e4ee3e1438) | Feb 15, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [2e006be72e](https://linux-hardware.org/?probe=2e006be72e) | Feb 11, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [07eabc1dbf](https://linux-hardware.org/?probe=07eabc1dbf) | Feb 11, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [335f1a844e](https://linux-hardware.org/?probe=335f1a844e) | Feb 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U3S... | Notebook    | [ad0b876d84](https://linux-hardware.org/?probe=ad0b876d84) | Feb 10, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [8d0a0a0422](https://linux-hardware.org/?probe=8d0a0a0422) | Feb 06, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [d693442f27](https://linux-hardware.org/?probe=d693442f27) | Feb 03, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [2e458676e4](https://linux-hardware.org/?probe=2e458676e4) | Feb 01, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [5dbc5260b2](https://linux-hardware.org/?probe=5dbc5260b2) | Jan 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [7c0c804a3e](https://linux-hardware.org/?probe=7c0c804a3e) | Jan 29, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [7b08eeb50c](https://linux-hardware.org/?probe=7b08eeb50c) | Jan 29, 2023 |
| HP            | ProLiant DL380e Gen8        | Server      | [72b9753b42](https://linux-hardware.org/?probe=72b9753b42) | Jan 26, 2023 |
| HP            | ProLiant DL380e Gen8        | Server      | [2bc6c62201](https://linux-hardware.org/?probe=2bc6c62201) | Jan 26, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [b1e29a464f](https://linux-hardware.org/?probe=b1e29a464f) | Jan 26, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [d2ec58874c](https://linux-hardware.org/?probe=d2ec58874c) | Jan 21, 2023 |
| HP            | 1850                        | Desktop     | [ccad003ff4](https://linux-hardware.org/?probe=ccad003ff4) | Jan 20, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | Notebook    | [07b3eb6453](https://linux-hardware.org/?probe=07b3eb6453) | Jan 20, 2023 |
| Toshiba       | Satellite C45-A             | Notebook    | [16f5bae11f](https://linux-hardware.org/?probe=16f5bae11f) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c16356f056](https://linux-hardware.org/?probe=c16356f056) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [70b8007dcc](https://linux-hardware.org/?probe=70b8007dcc) | Jan 17, 2023 |
| MSI           | B350M GAMING PRO            | Desktop     | [df317ef3c8](https://linux-hardware.org/?probe=df317ef3c8) | Jan 11, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [1e3f42b7d1](https://linux-hardware.org/?probe=1e3f42b7d1) | Jan 10, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [d35d765c2f](https://linux-hardware.org/?probe=d35d765c2f) | Jan 09, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [afd3f452a1](https://linux-hardware.org/?probe=afd3f452a1) | Jan 07, 2023 |
| Acer          | Aspire VN7-571G             | Notebook    | [88e5718807](https://linux-hardware.org/?probe=88e5718807) | Jan 03, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [a30f96dea4](https://linux-hardware.org/?probe=a30f96dea4) | Dec 31, 2022 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [d7daff3ed1](https://linux-hardware.org/?probe=d7daff3ed1) | Dec 27, 2022 |
| HP            | Compaq Mini CQ10-100        | Notebook    | [8b34b357bb](https://linux-hardware.org/?probe=8b34b357bb) | Dec 27, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [08800ce691](https://linux-hardware.org/?probe=08800ce691) | Dec 19, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [36a0b6f8d9](https://linux-hardware.org/?probe=36a0b6f8d9) | Dec 16, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [61dd034d23](https://linux-hardware.org/?probe=61dd034d23) | Dec 16, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [8525777743](https://linux-hardware.org/?probe=8525777743) | Dec 13, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [951b5a453d](https://linux-hardware.org/?probe=951b5a453d) | Dec 11, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [17cbc91488](https://linux-hardware.org/?probe=17cbc91488) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [4b9eb9fcab](https://linux-hardware.org/?probe=4b9eb9fcab) | Dec 10, 2022 |
| Lenovo        | IdeaPad U400 099342G        | Notebook    | [9ecbde32ab](https://linux-hardware.org/?probe=9ecbde32ab) | Dec 06, 2022 |
| HP            | 8767 A                      | Desktop     | [1d4dc77fa3](https://linux-hardware.org/?probe=1d4dc77fa3) | Dec 06, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [2436f4cf5e](https://linux-hardware.org/?probe=2436f4cf5e) | Nov 30, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [0bd83a29f4](https://linux-hardware.org/?probe=0bd83a29f4) | Nov 29, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [763f309094](https://linux-hardware.org/?probe=763f309094) | Nov 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [10b5bb5eab](https://linux-hardware.org/?probe=10b5bb5eab) | Nov 17, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c765249482](https://linux-hardware.org/?probe=c765249482) | Nov 17, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [8600d864a4](https://linux-hardware.org/?probe=8600d864a4) | Nov 13, 2022 |
| Deltron       | H81H3-M4                    | Desktop     | [49530f2e0b](https://linux-hardware.org/?probe=49530f2e0b) | Nov 13, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [eebc3537d1](https://linux-hardware.org/?probe=eebc3537d1) | Nov 09, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [b4d22497e8](https://linux-hardware.org/?probe=b4d22497e8) | Nov 08, 2022 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [b97ba1d3f0](https://linux-hardware.org/?probe=b97ba1d3f0) | Nov 07, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [e8a62297a5](https://linux-hardware.org/?probe=e8a62297a5) | Nov 05, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [88a69a9a20](https://linux-hardware.org/?probe=88a69a9a20) | Nov 05, 2022 |
| Dell          | Latitude E5470              | Notebook    | [4de6b7bdb8](https://linux-hardware.org/?probe=4de6b7bdb8) | Nov 04, 2022 |
| Dell          | Latitude 5420               | Notebook    | [717e0e6d40](https://linux-hardware.org/?probe=717e0e6d40) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [209e99f964](https://linux-hardware.org/?probe=209e99f964) | Nov 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [f12fc289fa](https://linux-hardware.org/?probe=f12fc289fa) | Nov 02, 2022 |
| HP            | 2B3B                        | All in one  | [a42ac6f6c7](https://linux-hardware.org/?probe=a42ac6f6c7) | Nov 01, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [dca18dced0](https://linux-hardware.org/?probe=dca18dced0) | Oct 30, 2022 |
| Acer          | Aspire 5745                 | Notebook    | [2f79de6974](https://linux-hardware.org/?probe=2f79de6974) | Oct 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [8d93ee0286](https://linux-hardware.org/?probe=8d93ee0286) | Oct 28, 2022 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [a977f9c3e9](https://linux-hardware.org/?probe=a977f9c3e9) | Oct 26, 2022 |
| ASUSTek       | X205TA                      | Notebook    | [2da58f110d](https://linux-hardware.org/?probe=2da58f110d) | Oct 24, 2022 |
| ADVANCE       | PS5077                      | Notebook    | [998e544711](https://linux-hardware.org/?probe=998e544711) | Oct 22, 2022 |
| ADVANCE       | PS5077                      | Notebook    | [97bfff0fc6](https://linux-hardware.org/?probe=97bfff0fc6) | Oct 22, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [07acd27a70](https://linux-hardware.org/?probe=07acd27a70) | Oct 21, 2022 |
| Dell          | Latitude E5470              | Notebook    | [11ad7cd084](https://linux-hardware.org/?probe=11ad7cd084) | Oct 20, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [ee436e327b](https://linux-hardware.org/?probe=ee436e327b) | Oct 16, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [86e01f1479](https://linux-hardware.org/?probe=86e01f1479) | Oct 16, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [0dd7c3989e](https://linux-hardware.org/?probe=0dd7c3989e) | Oct 12, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [744091dcaa](https://linux-hardware.org/?probe=744091dcaa) | Oct 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7dce56f55d](https://linux-hardware.org/?probe=7dce56f55d) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [f15acdf9d4](https://linux-hardware.org/?probe=f15acdf9d4) | Oct 09, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [5e33c2b674](https://linux-hardware.org/?probe=5e33c2b674) | Oct 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [6fec6456bc](https://linux-hardware.org/?probe=6fec6456bc) | Oct 07, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [fb954f84b4](https://linux-hardware.org/?probe=fb954f84b4) | Oct 07, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [d56cf9868c](https://linux-hardware.org/?probe=d56cf9868c) | Oct 07, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [acf2f9d381](https://linux-hardware.org/?probe=acf2f9d381) | Sep 25, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [21407ce4a8](https://linux-hardware.org/?probe=21407ce4a8) | Sep 21, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [44afa82c4a](https://linux-hardware.org/?probe=44afa82c4a) | Sep 19, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [a403b2a79d](https://linux-hardware.org/?probe=a403b2a79d) | Sep 17, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [dd55f6960d](https://linux-hardware.org/?probe=dd55f6960d) | Sep 15, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [0a91582802](https://linux-hardware.org/?probe=0a91582802) | Sep 14, 2022 |
| Intel         | D945GCNL AAD97184-106       | Desktop     | [a2bdc2d18c](https://linux-hardware.org/?probe=a2bdc2d18c) | Sep 11, 2022 |
| AZW           | GK mini                     | Mini pc     | [b2d573f8e2](https://linux-hardware.org/?probe=b2d573f8e2) | Sep 10, 2022 |
| AZW           | GK mini                     | Mini pc     | [58c74cb934](https://linux-hardware.org/?probe=58c74cb934) | Sep 09, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [2be9b66ba1](https://linux-hardware.org/?probe=2be9b66ba1) | Aug 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2267f01dee](https://linux-hardware.org/?probe=2267f01dee) | Aug 27, 2022 |
| Lenovo        | G570 4334                   | Notebook    | [7bea18122c](https://linux-hardware.org/?probe=7bea18122c) | Aug 27, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [c001653a5a](https://linux-hardware.org/?probe=c001653a5a) | Aug 20, 2022 |
| MSI           | X370 KRAIT GAMING           | Desktop     | [ea80c11a16](https://linux-hardware.org/?probe=ea80c11a16) | Aug 20, 2022 |
| Lenovo        | Yoga 9 15IMH5 82DE          | Convertible | [e6a9f975ae](https://linux-hardware.org/?probe=e6a9f975ae) | Aug 18, 2022 |
| Dell          | Vostro 3405                 | Notebook    | [2b5840062a](https://linux-hardware.org/?probe=2b5840062a) | Aug 18, 2022 |
| Lenovo        | Yoga 9 15IMH5 82DE          | Convertible | [c1e007def0](https://linux-hardware.org/?probe=c1e007def0) | Aug 15, 2022 |
| Dell          | Latitude E6430              | Notebook    | [91a44f9b39](https://linux-hardware.org/?probe=91a44f9b39) | Aug 13, 2022 |
| Dell          | Latitude E6430              | Notebook    | [864ad41c22](https://linux-hardware.org/?probe=864ad41c22) | Aug 13, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [ca185c2301](https://linux-hardware.org/?probe=ca185c2301) | Aug 10, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [49390f2f0e](https://linux-hardware.org/?probe=49390f2f0e) | Aug 06, 2022 |
| HP            | 1493                        | Desktop     | [2ac16ddc1f](https://linux-hardware.org/?probe=2ac16ddc1f) | Aug 03, 2022 |
| ASUSTek       | M5A97                       | Desktop     | [e5b05f8e39](https://linux-hardware.org/?probe=e5b05f8e39) | Aug 02, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [1c92a49cd4](https://linux-hardware.org/?probe=1c92a49cd4) | Aug 01, 2022 |
| Lenovo        | ThinkPad T60 1953D9U        | Notebook    | [1c31cb6b44](https://linux-hardware.org/?probe=1c31cb6b44) | Jul 21, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [27bf18a32e](https://linux-hardware.org/?probe=27bf18a32e) | Jul 20, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [8d52662820](https://linux-hardware.org/?probe=8d52662820) | Jul 19, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [4414dd4c1b](https://linux-hardware.org/?probe=4414dd4c1b) | Jul 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b511d2883b](https://linux-hardware.org/?probe=b511d2883b) | Jul 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [f0952d8c25](https://linux-hardware.org/?probe=f0952d8c25) | Jul 13, 2022 |
| Lenovo        | ThinkPad X140e 20BLA00C0... | Notebook    | [8c160ae192](https://linux-hardware.org/?probe=8c160ae192) | Jul 12, 2022 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [0ebf0eb484](https://linux-hardware.org/?probe=0ebf0eb484) | Jul 08, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [aa2ad87835](https://linux-hardware.org/?probe=aa2ad87835) | Jul 08, 2022 |
| Acer          | Aspire V3-471               | Notebook    | [75664ddf0f](https://linux-hardware.org/?probe=75664ddf0f) | Jul 07, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [8ed63bbdfd](https://linux-hardware.org/?probe=8ed63bbdfd) | Jul 01, 2022 |
| MSI           | GL65 Leopard 10SEK          | Notebook    | [5043bf1cd4](https://linux-hardware.org/?probe=5043bf1cd4) | Jun 29, 2022 |
| Lenovo        | ThinkPad X140e 20BLA00C0... | Notebook    | [01fbfc98f8](https://linux-hardware.org/?probe=01fbfc98f8) | Jun 27, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [1023ca742e](https://linux-hardware.org/?probe=1023ca742e) | Jun 27, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [d0200625ac](https://linux-hardware.org/?probe=d0200625ac) | Jun 27, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [e6d22a4d34](https://linux-hardware.org/?probe=e6d22a4d34) | Jun 27, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [fac01563a9](https://linux-hardware.org/?probe=fac01563a9) | Jun 24, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [1d18aab349](https://linux-hardware.org/?probe=1d18aab349) | Jun 23, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [4a61f83195](https://linux-hardware.org/?probe=4a61f83195) | Jun 23, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [c7c236e5a1](https://linux-hardware.org/?probe=c7c236e5a1) | Jun 23, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [9538654245](https://linux-hardware.org/?probe=9538654245) | Jun 21, 2022 |
| Intel         | D102GGC2 AAD42789-204       | Desktop     | [3ed07edb6a](https://linux-hardware.org/?probe=3ed07edb6a) | Jun 21, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [67c7179045](https://linux-hardware.org/?probe=67c7179045) | Jun 15, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [47f52294bb](https://linux-hardware.org/?probe=47f52294bb) | Jun 14, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [e24239a843](https://linux-hardware.org/?probe=e24239a843) | Jun 09, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [9ba4a449c6](https://linux-hardware.org/?probe=9ba4a449c6) | Jun 09, 2022 |
| Dell          | Latitude E7450              | Notebook    | [29219339b2](https://linux-hardware.org/?probe=29219339b2) | Jun 05, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [49c400d1f7](https://linux-hardware.org/?probe=49c400d1f7) | May 31, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c1db97e482](https://linux-hardware.org/?probe=c1db97e482) | May 31, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c274a43a82](https://linux-hardware.org/?probe=c274a43a82) | May 30, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [be0f84abb3](https://linux-hardware.org/?probe=be0f84abb3) | May 30, 2022 |
| ASUSTek       | X555UQ                      | Notebook    | [c266f3d070](https://linux-hardware.org/?probe=c266f3d070) | May 30, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2ce35a0cba](https://linux-hardware.org/?probe=2ce35a0cba) | May 30, 2022 |
| Lenovo        | ThinkPad P52 20MAS3X200     | Notebook    | [da2a67f904](https://linux-hardware.org/?probe=da2a67f904) | May 28, 2022 |
| Intel         | DP67BA AAG10219-300         | Desktop     | [005b9cdb8e](https://linux-hardware.org/?probe=005b9cdb8e) | May 26, 2022 |
| Acer          | TravelMate 5320             | Notebook    | [4d7e13024d](https://linux-hardware.org/?probe=4d7e13024d) | May 19, 2022 |
| Lenovo        | ThinkPad P52 20MAS3X200     | Notebook    | [7f0fc0c72e](https://linux-hardware.org/?probe=7f0fc0c72e) | May 19, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [2ee4916960](https://linux-hardware.org/?probe=2ee4916960) | May 18, 2022 |
| Dell          | Vostro 3405                 | Notebook    | [fcec5f1cdd](https://linux-hardware.org/?probe=fcec5f1cdd) | May 17, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [21f3f7368f](https://linux-hardware.org/?probe=21f3f7368f) | May 17, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [3bf7390ce3](https://linux-hardware.org/?probe=3bf7390ce3) | May 16, 2022 |
| HP            | 8056                        | Desktop     | [e9d15128a7](https://linux-hardware.org/?probe=e9d15128a7) | May 16, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [03581837bc](https://linux-hardware.org/?probe=03581837bc) | May 14, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [e436a62479](https://linux-hardware.org/?probe=e436a62479) | May 13, 2022 |
| Dell          | 0773VG A02                  | Desktop     | [0743f4573d](https://linux-hardware.org/?probe=0743f4573d) | May 12, 2022 |
| Dell          | Vostro 3405                 | Notebook    | [3c8e334d43](https://linux-hardware.org/?probe=3c8e334d43) | May 12, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [358cadc7df](https://linux-hardware.org/?probe=358cadc7df) | May 09, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [9b0f684d99](https://linux-hardware.org/?probe=9b0f684d99) | May 09, 2022 |
| Lenovo        | Legion 5 17ITH6H 82JM       | Notebook    | [451c9ea765](https://linux-hardware.org/?probe=451c9ea765) | May 08, 2022 |
| Lenovo        | ThinkPad T530 24296G9       | Notebook    | [934e13a24c](https://linux-hardware.org/?probe=934e13a24c) | May 08, 2022 |
| HP            | ZBook 15                    | Notebook    | [bd8e2ed626](https://linux-hardware.org/?probe=bd8e2ed626) | May 07, 2022 |
| SZMZ          | X99 DUAL Z8                 | Desktop     | [f68946f3d4](https://linux-hardware.org/?probe=f68946f3d4) | May 06, 2022 |
| Compal        | QAQXX                       | Notebook    | [d3211e6bc6](https://linux-hardware.org/?probe=d3211e6bc6) | May 05, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [d2eb5ae290](https://linux-hardware.org/?probe=d2eb5ae290) | May 05, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [7b488333bb](https://linux-hardware.org/?probe=7b488333bb) | May 05, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cbe76ee3d3](https://linux-hardware.org/?probe=cbe76ee3d3) | May 04, 2022 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [1a791b0fd5](https://linux-hardware.org/?probe=1a791b0fd5) | May 04, 2022 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [3846d07c7f](https://linux-hardware.org/?probe=3846d07c7f) | May 04, 2022 |
| HP            | ENVY dv6                    | Notebook    | [23ad3290c2](https://linux-hardware.org/?probe=23ad3290c2) | May 03, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [80f3ccadb9](https://linux-hardware.org/?probe=80f3ccadb9) | May 02, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U3S... | Notebook    | [74eec8c684](https://linux-hardware.org/?probe=74eec8c684) | May 01, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [05db30a69b](https://linux-hardware.org/?probe=05db30a69b) | Apr 30, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [ebdc8b1380](https://linux-hardware.org/?probe=ebdc8b1380) | Apr 30, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [865091bbc1](https://linux-hardware.org/?probe=865091bbc1) | Apr 30, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [5ee29c3982](https://linux-hardware.org/?probe=5ee29c3982) | Apr 30, 2022 |
| ASUSTek       | X556UR                      | Notebook    | [3f920954f7](https://linux-hardware.org/?probe=3f920954f7) | Apr 30, 2022 |
| MSI           | A88XM-E45 V2                | Desktop     | [a50ad068b1](https://linux-hardware.org/?probe=a50ad068b1) | Apr 30, 2022 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [0003f9342e](https://linux-hardware.org/?probe=0003f9342e) | Apr 30, 2022 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [7c9e2f4d8f](https://linux-hardware.org/?probe=7c9e2f4d8f) | Apr 30, 2022 |
| Foxconn       | H61MXE                      | Desktop     | [d8168e72e7](https://linux-hardware.org/?probe=d8168e72e7) | Apr 27, 2022 |
| HP            | Notebook                    | Notebook    | [94f0ce7610](https://linux-hardware.org/?probe=94f0ce7610) | Apr 26, 2022 |
| Dell          | Vostro 3405                 | Notebook    | [2d5bae0eeb](https://linux-hardware.org/?probe=2d5bae0eeb) | Apr 24, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e0e448efcb](https://linux-hardware.org/?probe=e0e448efcb) | Apr 24, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [ed62d97841](https://linux-hardware.org/?probe=ed62d97841) | Apr 18, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [a33d067e62](https://linux-hardware.org/?probe=a33d067e62) | Apr 18, 2022 |
| HP            | Compaq Mini CQ10-100        | Notebook    | [89c92e2cf7](https://linux-hardware.org/?probe=89c92e2cf7) | Apr 15, 2022 |
| Dell          | Latitude 3410               | Notebook    | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | Notebook    | [0e9e99acae](https://linux-hardware.org/?probe=0e9e99acae) | Apr 13, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [a00c0b503b](https://linux-hardware.org/?probe=a00c0b503b) | Apr 06, 2022 |
| ASUSTek       | A68HM-E                     | Desktop     | [af6b7df94c](https://linux-hardware.org/?probe=af6b7df94c) | Apr 06, 2022 |
| Lenovo        | ThinkPad X140e 20BLA00C0... | Notebook    | [9cad677222](https://linux-hardware.org/?probe=9cad677222) | Mar 24, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [9b99145008](https://linux-hardware.org/?probe=9b99145008) | Mar 21, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [53ca03e8ec](https://linux-hardware.org/?probe=53ca03e8ec) | Mar 17, 2022 |
| Foxconn       | 2A8C                        | Desktop     | [80e5e3a26c](https://linux-hardware.org/?probe=80e5e3a26c) | Mar 15, 2022 |
| Intel         | DX79SR AAG57199-200         | Desktop     | [1ab5b833d9](https://linux-hardware.org/?probe=1ab5b833d9) | Mar 12, 2022 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [92c7141f37](https://linux-hardware.org/?probe=92c7141f37) | Mar 12, 2022 |
| HP            | 340 G2                      | Notebook    | [c4f663b37b](https://linux-hardware.org/?probe=c4f663b37b) | Mar 04, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [eeaed94df7](https://linux-hardware.org/?probe=eeaed94df7) | Feb 23, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [b8f02b07fb](https://linux-hardware.org/?probe=b8f02b07fb) | Feb 18, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [3269f565c4](https://linux-hardware.org/?probe=3269f565c4) | Feb 18, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [91e577540a](https://linux-hardware.org/?probe=91e577540a) | Feb 11, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [03f63a3789](https://linux-hardware.org/?probe=03f63a3789) | Feb 09, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [15dd0e4767](https://linux-hardware.org/?probe=15dd0e4767) | Feb 08, 2022 |
| efirstview    | v01099                      | Notebook    | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| Toshiba       | Satellite C645              | Notebook    | [d552c9b132](https://linux-hardware.org/?probe=d552c9b132) | Feb 04, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [50fae55964](https://linux-hardware.org/?probe=50fae55964) | Jan 30, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [5f679efaa1](https://linux-hardware.org/?probe=5f679efaa1) | Jan 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b7cb93aff2](https://linux-hardware.org/?probe=b7cb93aff2) | Jan 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f36cdb65e7](https://linux-hardware.org/?probe=f36cdb65e7) | Jan 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f6a7e71141](https://linux-hardware.org/?probe=f6a7e71141) | Jan 18, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [1f065ea4dd](https://linux-hardware.org/?probe=1f065ea4dd) | Jan 12, 2022 |
| Sony          | VGN-FW56M                   | Notebook    | [9fb3fa0f32](https://linux-hardware.org/?probe=9fb3fa0f32) | Jan 09, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [eb23bd590c](https://linux-hardware.org/?probe=eb23bd590c) | Jan 07, 2022 |
| Toshiba       | Satellite E205              | Notebook    | [92431da366](https://linux-hardware.org/?probe=92431da366) | Dec 24, 2021 |
| Lenovo        | G400 20235                  | Notebook    | [c2bb5d0010](https://linux-hardware.org/?probe=c2bb5d0010) | Dec 18, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a3c85ddcb3](https://linux-hardware.org/?probe=a3c85ddcb3) | Dec 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [020b7460a1](https://linux-hardware.org/?probe=020b7460a1) | Dec 11, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fefa594281](https://linux-hardware.org/?probe=fefa594281) | Dec 10, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [3cd230924a](https://linux-hardware.org/?probe=3cd230924a) | Dec 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [54f954491a](https://linux-hardware.org/?probe=54f954491a) | Nov 21, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [9dccdb1f45](https://linux-hardware.org/?probe=9dccdb1f45) | Nov 17, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [180b98585e](https://linux-hardware.org/?probe=180b98585e) | Nov 11, 2021 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [e995b26637](https://linux-hardware.org/?probe=e995b26637) | Nov 11, 2021 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [83ce5b471d](https://linux-hardware.org/?probe=83ce5b471d) | Nov 10, 2021 |
| MSI           | B560M PRO-VDH               | Desktop     | [140cf1defc](https://linux-hardware.org/?probe=140cf1defc) | Nov 09, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [e085c7e42a](https://linux-hardware.org/?probe=e085c7e42a) | Nov 09, 2021 |
| ASRock        | B460M-HDV                   | Desktop     | [f343673932](https://linux-hardware.org/?probe=f343673932) | Nov 08, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [90fbcc38c3](https://linux-hardware.org/?probe=90fbcc38c3) | Nov 08, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [61db5bc9b5](https://linux-hardware.org/?probe=61db5bc9b5) | Nov 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [df2d173d7c](https://linux-hardware.org/?probe=df2d173d7c) | Nov 01, 2021 |
| Lenovo        | V14-ARE 82DQ                | Notebook    | [8948989999](https://linux-hardware.org/?probe=8948989999) | Oct 31, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f4d2f1104e](https://linux-hardware.org/?probe=f4d2f1104e) | Oct 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e071387ed6](https://linux-hardware.org/?probe=e071387ed6) | Oct 22, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [849c03d63c](https://linux-hardware.org/?probe=849c03d63c) | Oct 21, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [87d959803d](https://linux-hardware.org/?probe=87d959803d) | Oct 15, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [9343a7aac0](https://linux-hardware.org/?probe=9343a7aac0) | Oct 13, 2021 |
| MSI           | H170A GAMING PRO            | Desktop     | [2a068afc0c](https://linux-hardware.org/?probe=2a068afc0c) | Oct 11, 2021 |
| Lenovo        | 3098 SDK0E50510 PRO or W... | Desktop     | [57fb928b65](https://linux-hardware.org/?probe=57fb928b65) | Oct 03, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [8bb0307157](https://linux-hardware.org/?probe=8bb0307157) | Sep 25, 2021 |
| HP            | Notebook                    | Notebook    | [36fd24364d](https://linux-hardware.org/?probe=36fd24364d) | Sep 24, 2021 |
| ASUSTek       | A88XM-A                     | Desktop     | [72114a075d](https://linux-hardware.org/?probe=72114a075d) | Sep 24, 2021 |
| Dell          | 0773VG A02                  | Desktop     | [5b63f0fc0a](https://linux-hardware.org/?probe=5b63f0fc0a) | Sep 16, 2021 |
| Advance       | AN-5431                     | Notebook    | [d48465a943](https://linux-hardware.org/?probe=d48465a943) | Sep 14, 2021 |
| HP            | Notebook                    | Notebook    | [2a564798fd](https://linux-hardware.org/?probe=2a564798fd) | Sep 11, 2021 |
| Intel         | DH55TC AAE70932-302         | Desktop     | [e5f7233230](https://linux-hardware.org/?probe=e5f7233230) | Sep 04, 2021 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [72a24d0b34](https://linux-hardware.org/?probe=72a24d0b34) | Sep 01, 2021 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [92fb750c2f](https://linux-hardware.org/?probe=92fb750c2f) | Sep 01, 2021 |
| Lenovo        | ThinkPad T440 20B7A08500    | Notebook    | [b7e859020c](https://linux-hardware.org/?probe=b7e859020c) | Aug 26, 2021 |
| HP            | 450                         | Notebook    | [9f5d03c478](https://linux-hardware.org/?probe=9f5d03c478) | Aug 19, 2021 |
| Intel         | DG33BU AAD79951-413         | Desktop     | [9824fedcc4](https://linux-hardware.org/?probe=9824fedcc4) | Aug 16, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [0ffe99b73b](https://linux-hardware.org/?probe=0ffe99b73b) | Aug 14, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [392df1ef2b](https://linux-hardware.org/?probe=392df1ef2b) | Aug 13, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [46cd16e708](https://linux-hardware.org/?probe=46cd16e708) | Aug 13, 2021 |
| ASUSTek       | X542UQ                      | Notebook    | [63d2276d55](https://linux-hardware.org/?probe=63d2276d55) | Aug 03, 2021 |
| Gigabyte      | B550M H                     | Desktop     | [b26c567912](https://linux-hardware.org/?probe=b26c567912) | Aug 03, 2021 |
| Advance       | AN-5431                     | Notebook    | [06409d8637](https://linux-hardware.org/?probe=06409d8637) | Aug 01, 2021 |
| Lenovo        | ThinkPad T580 20LAS0XD00    | Notebook    | [36f1b3eb94](https://linux-hardware.org/?probe=36f1b3eb94) | Jul 31, 2021 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [5b80d3040f](https://linux-hardware.org/?probe=5b80d3040f) | Jul 25, 2021 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [771ef872d9](https://linux-hardware.org/?probe=771ef872d9) | Jul 25, 2021 |
| Dell          | Latitude E5540              | Notebook    | [44b8f3a781](https://linux-hardware.org/?probe=44b8f3a781) | Jul 23, 2021 |
| MSI           | B460M-A PRO                 | Desktop     | [da8382cb33](https://linux-hardware.org/?probe=da8382cb33) | Jul 15, 2021 |
| MSI           | B460M-A PRO                 | Desktop     | [146ce74ec9](https://linux-hardware.org/?probe=146ce74ec9) | Jul 15, 2021 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [6001052e23](https://linux-hardware.org/?probe=6001052e23) | Jul 15, 2021 |
| HP            | Pavilion dv6                | Notebook    | [3e69858907](https://linux-hardware.org/?probe=3e69858907) | Jul 09, 2021 |
| Lenovo        | ThinkPad L460 20FVA0G400    | Notebook    | [378021c178](https://linux-hardware.org/?probe=378021c178) | Jul 06, 2021 |
| ASUSTek       | ROG Strix G532LW_G532LWI    | Notebook    | [b36be47753](https://linux-hardware.org/?probe=b36be47753) | Jun 27, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [95fcf3868f](https://linux-hardware.org/?probe=95fcf3868f) | Jun 26, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [7684808016](https://linux-hardware.org/?probe=7684808016) | Jun 24, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [003f0d1c2a](https://linux-hardware.org/?probe=003f0d1c2a) | Jun 21, 2021 |
| ASUSTek       | ROG Strix G532LW_G532LWI    | Notebook    | [1344b72b26](https://linux-hardware.org/?probe=1344b72b26) | Jun 20, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [cebf94c181](https://linux-hardware.org/?probe=cebf94c181) | Jun 15, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [6670e1c145](https://linux-hardware.org/?probe=6670e1c145) | Jun 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [af8045a7b3](https://linux-hardware.org/?probe=af8045a7b3) | May 31, 2021 |
| HP            | 8054                        | Desktop     | [b0662fd84b](https://linux-hardware.org/?probe=b0662fd84b) | May 30, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [89bed4ca0a](https://linux-hardware.org/?probe=89bed4ca0a) | May 28, 2021 |
| HP            | 8054                        | Desktop     | [37f65c4171](https://linux-hardware.org/?probe=37f65c4171) | May 27, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [ee9233be38](https://linux-hardware.org/?probe=ee9233be38) | May 26, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [6d64546949](https://linux-hardware.org/?probe=6d64546949) | May 23, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [1b52ac3979](https://linux-hardware.org/?probe=1b52ac3979) | May 23, 2021 |
| HP            | 2B2F MVB,A                  | All in one  | [093f49b44c](https://linux-hardware.org/?probe=093f49b44c) | May 20, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a1959c22e0](https://linux-hardware.org/?probe=a1959c22e0) | May 20, 2021 |
| HP            | 240 G7                      | Notebook    | [9fff9c48ab](https://linux-hardware.org/?probe=9fff9c48ab) | May 16, 2021 |
| MSI           | A88X-G45 GAMING             | Desktop     | [930993fd14](https://linux-hardware.org/?probe=930993fd14) | May 16, 2021 |
| MSI           | A88X-G45 GAMING             | Desktop     | [f7a3ab5c2f](https://linux-hardware.org/?probe=f7a3ab5c2f) | May 16, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [57b918a36e](https://linux-hardware.org/?probe=57b918a36e) | May 15, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [23a000c11b](https://linux-hardware.org/?probe=23a000c11b) | May 05, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [d50b1f77d7](https://linux-hardware.org/?probe=d50b1f77d7) | May 05, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [6eb605ae36](https://linux-hardware.org/?probe=6eb605ae36) | Apr 21, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [642a8e122e](https://linux-hardware.org/?probe=642a8e122e) | Apr 18, 2021 |
| Toshiba       | Satellite L35               | Notebook    | [1abffa2c4c](https://linux-hardware.org/?probe=1abffa2c4c) | Apr 16, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [4bd5425a6b](https://linux-hardware.org/?probe=4bd5425a6b) | Apr 11, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [59cb82d24c](https://linux-hardware.org/?probe=59cb82d24c) | Apr 09, 2021 |
| HP            | 14                          | Notebook    | [9d65301476](https://linux-hardware.org/?probe=9d65301476) | Apr 09, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [14e58f968d](https://linux-hardware.org/?probe=14e58f968d) | Apr 07, 2021 |
| MSI           | B75A-G43                    | Desktop     | [87a3e8d42c](https://linux-hardware.org/?probe=87a3e8d42c) | Apr 07, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [b02d3fa1c0](https://linux-hardware.org/?probe=b02d3fa1c0) | Apr 04, 2021 |
| Lenovo        | ThinkCentre M91 7516AD1     | Desktop     | [91ae7f221c](https://linux-hardware.org/?probe=91ae7f221c) | Apr 01, 2021 |
| Toshiba       | Satellite C655D             | Notebook    | [1959880e8f](https://linux-hardware.org/?probe=1959880e8f) | Mar 28, 2021 |
| Dell          | Latitude E5470              | Notebook    | [6ade45ee37](https://linux-hardware.org/?probe=6ade45ee37) | Mar 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [860e86fde0](https://linux-hardware.org/?probe=860e86fde0) | Mar 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [4d1099b04c](https://linux-hardware.org/?probe=4d1099b04c) | Mar 18, 2021 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [529bb59872](https://linux-hardware.org/?probe=529bb59872) | Mar 12, 2021 |
| Toshiba       | Satellite A665              | Notebook    | [23143ad7ae](https://linux-hardware.org/?probe=23143ad7ae) | Mar 07, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [96dd155871](https://linux-hardware.org/?probe=96dd155871) | Mar 07, 2021 |
| Intel         | H61                         | Desktop     | [77b62ac54a](https://linux-hardware.org/?probe=77b62ac54a) | Mar 05, 2021 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [b2e0735680](https://linux-hardware.org/?probe=b2e0735680) | Feb 28, 2021 |
| MSI           | Prestige 14 A10SC           | Notebook    | [26f40cdcba](https://linux-hardware.org/?probe=26f40cdcba) | Feb 25, 2021 |
| HP            | Stream x360 Convertible ... | Convertible | [ccb97bb311](https://linux-hardware.org/?probe=ccb97bb311) | Feb 23, 2021 |
| HP            | ProBook 5330m               | Notebook    | [4a66a57a41](https://linux-hardware.org/?probe=4a66a57a41) | Feb 23, 2021 |
| Razer         | Blade                       | Notebook    | [58fcda1ac4](https://linux-hardware.org/?probe=58fcda1ac4) | Feb 18, 2021 |
| PCChips       | P49G                        | Desktop     | [a2f19ae622](https://linux-hardware.org/?probe=a2f19ae622) | Feb 17, 2021 |
| MSI           | A88X-G45 GAMING             | Desktop     | [05d5a888d4](https://linux-hardware.org/?probe=05d5a888d4) | Feb 16, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c4f6a52387](https://linux-hardware.org/?probe=c4f6a52387) | Feb 13, 2021 |
| Intel         | D945GTP AAC97834-305        | Desktop     | [fa876f7290](https://linux-hardware.org/?probe=fa876f7290) | Feb 10, 2021 |
| ASUSTek       | N56JN                       | Notebook    | [02008fdd48](https://linux-hardware.org/?probe=02008fdd48) | Jan 31, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [3c0bc82dde](https://linux-hardware.org/?probe=3c0bc82dde) | Jan 16, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [48d877b127](https://linux-hardware.org/?probe=48d877b127) | Jan 07, 2021 |
| HP            | Pavilion dv7                | Notebook    | [7591424ea2](https://linux-hardware.org/?probe=7591424ea2) | Jan 06, 2021 |
| HP            | Pavilion dv7                | Notebook    | [d660b968a4](https://linux-hardware.org/?probe=d660b968a4) | Jan 06, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [fe678ae6f5](https://linux-hardware.org/?probe=fe678ae6f5) | Jan 04, 2021 |
| Intel         | DP965LT AAD41694-209        | Desktop     | [c577103201](https://linux-hardware.org/?probe=c577103201) | Jan 02, 2021 |
| Dell          | G5 5505                     | Notebook    | [156236cc47](https://linux-hardware.org/?probe=156236cc47) | Dec 30, 2020 |
| Dell          | Latitude E5470              | Notebook    | [f6a3bc1097](https://linux-hardware.org/?probe=f6a3bc1097) | Dec 28, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [033a1ff3cd](https://linux-hardware.org/?probe=033a1ff3cd) | Dec 07, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [35757b1c8c](https://linux-hardware.org/?probe=35757b1c8c) | Dec 06, 2020 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [228dc321d9](https://linux-hardware.org/?probe=228dc321d9) | Dec 05, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [f0c3c358a0](https://linux-hardware.org/?probe=f0c3c358a0) | Dec 03, 2020 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [5837b78f0c](https://linux-hardware.org/?probe=5837b78f0c) | Nov 26, 2020 |
| ASUSTek       | N56JN                       | Notebook    | [776cb81132](https://linux-hardware.org/?probe=776cb81132) | Nov 25, 2020 |
| ASUSTek       | N56JN                       | Notebook    | [e14774acd5](https://linux-hardware.org/?probe=e14774acd5) | Nov 25, 2020 |
| HP            | 14                          | Notebook    | [918fb071c2](https://linux-hardware.org/?probe=918fb071c2) | Nov 22, 2020 |
| Dell          | Latitude 3440               | Notebook    | [17db1f31f6](https://linux-hardware.org/?probe=17db1f31f6) | Nov 13, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [751f746aaf](https://linux-hardware.org/?probe=751f746aaf) | Nov 09, 2020 |
| Lenovo        | Larne CRB SDK0J40679 WIN... | All in one  | [9a0e5bd73b](https://linux-hardware.org/?probe=9a0e5bd73b) | Oct 31, 2020 |
| Lenovo        | Larne CRB SDK0J40679 WIN... | All in one  | [8d1e7af345](https://linux-hardware.org/?probe=8d1e7af345) | Oct 31, 2020 |
| Dell          | 0DR845                      | Desktop     | [80aa8797b0](https://linux-hardware.org/?probe=80aa8797b0) | Oct 29, 2020 |
| MSI           | B360M PRO-VH                | Desktop     | [d8eb2de621](https://linux-hardware.org/?probe=d8eb2de621) | Oct 21, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [943240cc2a](https://linux-hardware.org/?probe=943240cc2a) | Oct 09, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [07ac3c5495](https://linux-hardware.org/?probe=07ac3c5495) | Oct 07, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [123eb500e2](https://linux-hardware.org/?probe=123eb500e2) | Oct 06, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [735aea26c5](https://linux-hardware.org/?probe=735aea26c5) | Sep 28, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [8987176239](https://linux-hardware.org/?probe=8987176239) | Sep 28, 2020 |
| HP            | 240 G7                      | Notebook    | [2507cc1bc7](https://linux-hardware.org/?probe=2507cc1bc7) | Sep 28, 2020 |
| Intel         | 945GCT-M                    | Desktop     | [c00c60e193](https://linux-hardware.org/?probe=c00c60e193) | Sep 26, 2020 |
| Intel         | 945GCT-M                    | Desktop     | [f714eaf1b2](https://linux-hardware.org/?probe=f714eaf1b2) | Sep 26, 2020 |
| Lenovo        | ThinkPad T470 20HES0JQ00    | Notebook    | [4235f1fc42](https://linux-hardware.org/?probe=4235f1fc42) | Sep 20, 2020 |
| Acer          | Nitro AN515-54              | Notebook    | [60efe004ff](https://linux-hardware.org/?probe=60efe004ff) | Sep 19, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [123ba2dd21](https://linux-hardware.org/?probe=123ba2dd21) | Sep 15, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [e193207a8f](https://linux-hardware.org/?probe=e193207a8f) | Sep 14, 2020 |
| MSI           | H81M-E33                    | Desktop     | [313883253c](https://linux-hardware.org/?probe=313883253c) | Sep 07, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [d043bf1b42](https://linux-hardware.org/?probe=d043bf1b42) | Sep 06, 2020 |
| Lenovo        | ThinkPad T430 2349LRS       | Notebook    | [d886cd5c31](https://linux-hardware.org/?probe=d886cd5c31) | Sep 05, 2020 |
| Lenovo        | ThinkPad T430 2349LRS       | Notebook    | [38284d9848](https://linux-hardware.org/?probe=38284d9848) | Sep 05, 2020 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [fc06b19016](https://linux-hardware.org/?probe=fc06b19016) | Sep 05, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [395b3e9836](https://linux-hardware.org/?probe=395b3e9836) | Sep 05, 2020 |
| Lenovo        | ThinkPad T430s 23539KU      | Notebook    | [2f700d4f41](https://linux-hardware.org/?probe=2f700d4f41) | Sep 03, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [47c7bf1c93](https://linux-hardware.org/?probe=47c7bf1c93) | Aug 30, 2020 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [3ac15dbee9](https://linux-hardware.org/?probe=3ac15dbee9) | Aug 28, 2020 |
| Lenovo        | G475 20080                  | Notebook    | [c97ad59308](https://linux-hardware.org/?probe=c97ad59308) | Aug 26, 2020 |
| Acer          | Aspire A515-52G             | Notebook    | [86a890eb18](https://linux-hardware.org/?probe=86a890eb18) | Aug 23, 2020 |
| Acer          | Aspire A515-52G             | Notebook    | [5034bf6bc3](https://linux-hardware.org/?probe=5034bf6bc3) | Aug 23, 2020 |
| Toshiba       | Satellite C845              | Notebook    | [7e218cb089](https://linux-hardware.org/?probe=7e218cb089) | Aug 22, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [31a8ca3766](https://linux-hardware.org/?probe=31a8ca3766) | Aug 18, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2098b09526](https://linux-hardware.org/?probe=2098b09526) | Aug 17, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [39ccf30487](https://linux-hardware.org/?probe=39ccf30487) | Aug 17, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [26fe839699](https://linux-hardware.org/?probe=26fe839699) | Aug 14, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [55d2d92173](https://linux-hardware.org/?probe=55d2d92173) | Aug 14, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [2adefb78ad](https://linux-hardware.org/?probe=2adefb78ad) | Aug 13, 2020 |
| Lenovo        | ThinkPad P50 20EQA09900     | Notebook    | [4360f8c6a6](https://linux-hardware.org/?probe=4360f8c6a6) | Aug 12, 2020 |
| Lenovo        | ThinkPad P50 20EQA09900     | Notebook    | [76f4cf6487](https://linux-hardware.org/?probe=76f4cf6487) | Aug 12, 2020 |
| Toshiba       | Satellite L45-B             | Notebook    | [ce51a04f5d](https://linux-hardware.org/?probe=ce51a04f5d) | Aug 01, 2020 |
| Lenovo        | ThinkPad T60 1953D9U        | Notebook    | [45c01e0aca](https://linux-hardware.org/?probe=45c01e0aca) | Jul 30, 2020 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [02c231ca67](https://linux-hardware.org/?probe=02c231ca67) | Jul 27, 2020 |
| HP            | 245 G3                      | Notebook    | [044b206096](https://linux-hardware.org/?probe=044b206096) | Jul 26, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [fda411a3d7](https://linux-hardware.org/?probe=fda411a3d7) | Jul 24, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [4e0fee8549](https://linux-hardware.org/?probe=4e0fee8549) | Jul 20, 2020 |
| Intel         | DG31PR AAD97573-305         | Desktop     | [e3bd0984ee](https://linux-hardware.org/?probe=e3bd0984ee) | Jul 17, 2020 |
| Intel         | H61M-DS2                    | Desktop     | [2e847ac1d0](https://linux-hardware.org/?probe=2e847ac1d0) | Jul 16, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [7fdfad1fc4](https://linux-hardware.org/?probe=7fdfad1fc4) | Jul 11, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f0ed82358a](https://linux-hardware.org/?probe=f0ed82358a) | Jul 05, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [b0f11672bb](https://linux-hardware.org/?probe=b0f11672bb) | Jul 05, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [4716a84af9](https://linux-hardware.org/?probe=4716a84af9) | Jul 03, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [c9d75e29d3](https://linux-hardware.org/?probe=c9d75e29d3) | Jun 30, 2020 |
| HP            | 09E8h                       | Desktop     | [d9b1f1bf60](https://linux-hardware.org/?probe=d9b1f1bf60) | Jun 28, 2020 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [f073723231](https://linux-hardware.org/?probe=f073723231) | Jun 27, 2020 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [7f8abda42c](https://linux-hardware.org/?probe=7f8abda42c) | Jun 27, 2020 |
| Intel         | H61M-DS2                    | Desktop     | [aef4861ab1](https://linux-hardware.org/?probe=aef4861ab1) | Jun 25, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [2fb2b6ad63](https://linux-hardware.org/?probe=2fb2b6ad63) | Jun 22, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [844f7b115e](https://linux-hardware.org/?probe=844f7b115e) | Jun 21, 2020 |
| HP            | 3397                        | Desktop     | [3421ad000d](https://linux-hardware.org/?probe=3421ad000d) | Jun 21, 2020 |
| HP            | 09E8h                       | Desktop     | [14e6514858](https://linux-hardware.org/?probe=14e6514858) | Jun 20, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [0803c9f10d](https://linux-hardware.org/?probe=0803c9f10d) | Jun 18, 2020 |
| Intel         | DG41WV AAE90316-104         | Desktop     | [3b021c1b62](https://linux-hardware.org/?probe=3b021c1b62) | Jun 17, 2020 |
| Intel         | DG41WV AAE90316-104         | Desktop     | [821a7a7b85](https://linux-hardware.org/?probe=821a7a7b85) | Jun 17, 2020 |
| ASUSTek       | X540LA                      | Notebook    | [333139a886](https://linux-hardware.org/?probe=333139a886) | Jun 17, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [1c258b2abb](https://linux-hardware.org/?probe=1c258b2abb) | Jun 15, 2020 |
| Dell          | 0DR845                      | Desktop     | [cb4b80e381](https://linux-hardware.org/?probe=cb4b80e381) | Jun 14, 2020 |
| Dell          | 0DR845                      | Desktop     | [107ec57e94](https://linux-hardware.org/?probe=107ec57e94) | Jun 13, 2020 |
| Toshiba       | Satellite L855              | Notebook    | [adbdc1e191](https://linux-hardware.org/?probe=adbdc1e191) | Jun 13, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | Desktop     | [89182244dc](https://linux-hardware.org/?probe=89182244dc) | Jun 12, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [97237c08ac](https://linux-hardware.org/?probe=97237c08ac) | Jun 11, 2020 |
| Intel         | DH61WW AAG23116-302         | Desktop     | [615d9bbafb](https://linux-hardware.org/?probe=615d9bbafb) | Jun 07, 2020 |
| Intel         | DH61WW AAG23116-302         | Desktop     | [db6aa4b6fa](https://linux-hardware.org/?probe=db6aa4b6fa) | Jun 07, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [371c5ccd5a](https://linux-hardware.org/?probe=371c5ccd5a) | May 31, 2020 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b803424e29](https://linux-hardware.org/?probe=b803424e29) | May 31, 2020 |
| HP            | ENVY 15                     | Notebook    | [9075368552](https://linux-hardware.org/?probe=9075368552) | May 29, 2020 |
| MSI           | A68HM-E33 V2                | Desktop     | [ea48f46d27](https://linux-hardware.org/?probe=ea48f46d27) | May 27, 2020 |
| Foxconn       | H61MXE/-S/-V/-K             | Desktop     | [3d5fc4df20](https://linux-hardware.org/?probe=3d5fc4df20) | May 27, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [fb33cd7cef](https://linux-hardware.org/?probe=fb33cd7cef) | May 26, 2020 |
| Biostar       | GF7025-M2                   | Desktop     | [66b5de774d](https://linux-hardware.org/?probe=66b5de774d) | May 26, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [07829f089a](https://linux-hardware.org/?probe=07829f089a) | May 24, 2020 |
| Dell          | 0WMJ54 A01                  | Desktop     | [4c93d3634b](https://linux-hardware.org/?probe=4c93d3634b) | May 24, 2020 |
| HP            | ENVY 15                     | Notebook    | [afcc7af453](https://linux-hardware.org/?probe=afcc7af453) | May 23, 2020 |
| Gigabyte      | G41MT-S2                    | Desktop     | [f8702707c6](https://linux-hardware.org/?probe=f8702707c6) | May 22, 2020 |
| Unknown       | Unknown                     | Notebook    | [aabfc32771](https://linux-hardware.org/?probe=aabfc32771) | May 19, 2020 |
| Unknown       | Unknown                     | Notebook    | [3bcd40acc0](https://linux-hardware.org/?probe=3bcd40acc0) | May 19, 2020 |
| Intel         | D945GCNL AAD97184-102       | Desktop     | [72691e43eb](https://linux-hardware.org/?probe=72691e43eb) | May 14, 2020 |
| Gigabyte      | B450 GAMING X               | Desktop     | [404ef9032e](https://linux-hardware.org/?probe=404ef9032e) | May 12, 2020 |
| Dell          | Precision M4600             | Notebook    | [7060267281](https://linux-hardware.org/?probe=7060267281) | May 08, 2020 |
| HP            | 0A58h                       | Desktop     | [a3a4679ef9](https://linux-hardware.org/?probe=a3a4679ef9) | May 05, 2020 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [c513103ac9](https://linux-hardware.org/?probe=c513103ac9) | May 05, 2020 |
| Intel         | DX58SO AAE29331-703         | Desktop     | [08c0779e95](https://linux-hardware.org/?probe=08c0779e95) | May 02, 2020 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [d5880c1076](https://linux-hardware.org/?probe=d5880c1076) | May 02, 2020 |
| HP            | 450                         | Notebook    | [22b90eb634](https://linux-hardware.org/?probe=22b90eb634) | May 02, 2020 |
| HP            | 450                         | Notebook    | [0da93b6fce](https://linux-hardware.org/?probe=0da93b6fce) | May 02, 2020 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [eb77b46e2f](https://linux-hardware.org/?probe=eb77b46e2f) | Apr 30, 2020 |
| Dell          | System XPS L502X            | Notebook    | [939683d725](https://linux-hardware.org/?probe=939683d725) | Apr 27, 2020 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [e2ab73d9cf](https://linux-hardware.org/?probe=e2ab73d9cf) | Apr 26, 2020 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [32546cbd9d](https://linux-hardware.org/?probe=32546cbd9d) | Apr 26, 2020 |
| Dell          | System XPS L502X            | Notebook    | [c893f3f105](https://linux-hardware.org/?probe=c893f3f105) | Apr 24, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [97261529e7](https://linux-hardware.org/?probe=97261529e7) | Apr 21, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [babdfebf40](https://linux-hardware.org/?probe=babdfebf40) | Apr 17, 2020 |
| MSI           | A68HM-E33 V2                | Desktop     | [d88e072663](https://linux-hardware.org/?probe=d88e072663) | Apr 15, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [71673b2f86](https://linux-hardware.org/?probe=71673b2f86) | Apr 09, 2020 |
| MSI           | A68HM-E33 V2                | Desktop     | [6277a6ec0b](https://linux-hardware.org/?probe=6277a6ec0b) | Apr 08, 2020 |
| HP            | 0A60h                       | Desktop     | [e929430fd0](https://linux-hardware.org/?probe=e929430fd0) | Apr 08, 2020 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [bbd3b573e1](https://linux-hardware.org/?probe=bbd3b573e1) | Apr 05, 2020 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [51c0fd8c5c](https://linux-hardware.org/?probe=51c0fd8c5c) | Apr 05, 2020 |
| Toshiba       | NB505                       | Notebook    | [934ebfe06b](https://linux-hardware.org/?probe=934ebfe06b) | Apr 05, 2020 |
| PCChips       | P49G                        | Desktop     | [57f11f5c76](https://linux-hardware.org/?probe=57f11f5c76) | Apr 04, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [b112c2d6c6](https://linux-hardware.org/?probe=b112c2d6c6) | Mar 30, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [7dee8ed61e](https://linux-hardware.org/?probe=7dee8ed61e) | Mar 26, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [e274c73209](https://linux-hardware.org/?probe=e274c73209) | Mar 23, 2020 |
| Sony          | SVF15A17CLB                 | Notebook    | [6f9e42f276](https://linux-hardware.org/?probe=6f9e42f276) | Mar 22, 2020 |
| HP            | 3397                        | Desktop     | [71764f18dd](https://linux-hardware.org/?probe=71764f18dd) | Mar 21, 2020 |
| HP            | 09E8h                       | Desktop     | [57904c47e1](https://linux-hardware.org/?probe=57904c47e1) | Mar 21, 2020 |
| HP            | 09E8h                       | Desktop     | [4c44586ba9](https://linux-hardware.org/?probe=4c44586ba9) | Mar 21, 2020 |
| PCChips       | P49G                        | Desktop     | [1cedc0a4f7](https://linux-hardware.org/?probe=1cedc0a4f7) | Mar 17, 2020 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [88cf0450ac](https://linux-hardware.org/?probe=88cf0450ac) | Mar 15, 2020 |
| Gigabyte      | B450 GAMING X               | Desktop     | [145e6998fc](https://linux-hardware.org/?probe=145e6998fc) | Mar 06, 2020 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [baaf155c68](https://linux-hardware.org/?probe=baaf155c68) | Mar 04, 2020 |
| Lenovo        | MAHOBAY                     | Desktop     | [651d7ac7be](https://linux-hardware.org/?probe=651d7ac7be) | Feb 28, 2020 |
| Lenovo        | MAHOBAY                     | Desktop     | [5b33f9565a](https://linux-hardware.org/?probe=5b33f9565a) | Feb 28, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [e598212cee](https://linux-hardware.org/?probe=e598212cee) | Feb 28, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2eebfcd5e9](https://linux-hardware.org/?probe=2eebfcd5e9) | Feb 27, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1335c3693b](https://linux-hardware.org/?probe=1335c3693b) | Feb 27, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [9344a74aa9](https://linux-hardware.org/?probe=9344a74aa9) | Feb 26, 2020 |
| Gigabyte      | M68MT-S2                    | Desktop     | [6a5c6cf0dc](https://linux-hardware.org/?probe=6a5c6cf0dc) | Feb 23, 2020 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [8a4a2a6066](https://linux-hardware.org/?probe=8a4a2a6066) | Feb 21, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b253180703](https://linux-hardware.org/?probe=b253180703) | Feb 20, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [ad43873fae](https://linux-hardware.org/?probe=ad43873fae) | Feb 19, 2020 |
| Intel         | CM8V5CB8N K53774-201        | Desktop     | [4ba8cd9ca2](https://linux-hardware.org/?probe=4ba8cd9ca2) | Feb 16, 2020 |
| Intel         | CM8V5CB8N K53774-201        | Desktop     | [19086b2ac2](https://linux-hardware.org/?probe=19086b2ac2) | Feb 16, 2020 |
| Toshiba       | QOSMIO X775                 | Notebook    | [6abcb623e3](https://linux-hardware.org/?probe=6abcb623e3) | Feb 02, 2020 |
| Toshiba       | QOSMIO X775                 | Notebook    | [a2cf60ec44](https://linux-hardware.org/?probe=a2cf60ec44) | Feb 02, 2020 |
| MSI           | 970 GAMING                  | Desktop     | [7ae91dcf15](https://linux-hardware.org/?probe=7ae91dcf15) | Jan 21, 2020 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [12b760b696](https://linux-hardware.org/?probe=12b760b696) | Jan 20, 2020 |
| ASUSTek       | M5A97                       | Desktop     | [a381f0be23](https://linux-hardware.org/?probe=a381f0be23) | Jan 17, 2020 |
| Gigabyte      | B75M-D3H                    | Desktop     | [5b67f6ed83](https://linux-hardware.org/?probe=5b67f6ed83) | Dec 26, 2019 |
| Acer          | Aspire ES1-572              | Notebook    | [8bc74bd7fb](https://linux-hardware.org/?probe=8bc74bd7fb) | Dec 06, 2019 |
| Dell          | 0G261D A00                  | Desktop     | [c05b5b48de](https://linux-hardware.org/?probe=c05b5b48de) | Dec 05, 2019 |
| Dell          | 0G261D A00                  | Desktop     | [3862b040a2](https://linux-hardware.org/?probe=3862b040a2) | Dec 04, 2019 |
| Unknown       | Unknown                     | Notebook    | [cd4af41624](https://linux-hardware.org/?probe=cd4af41624) | Nov 30, 2019 |
| Dell          | 0G261D A00                  | Desktop     | [50ef5c54ef](https://linux-hardware.org/?probe=50ef5c54ef) | Nov 29, 2019 |
| HP            | Pavilion g4                 | Notebook    | [cb1f2e06e7](https://linux-hardware.org/?probe=cb1f2e06e7) | Nov 28, 2019 |
| Dell          | Latitude 5580               | Notebook    | [7abf5fbce7](https://linux-hardware.org/?probe=7abf5fbce7) | Nov 21, 2019 |
| Dell          | Latitude 5580               | Notebook    | [521a1d30b6](https://linux-hardware.org/?probe=521a1d30b6) | Nov 21, 2019 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [dfa431bef9](https://linux-hardware.org/?probe=dfa431bef9) | Nov 13, 2019 |
| Toshiba       | Satellite C55-B             | Notebook    | [ef97116a29](https://linux-hardware.org/?probe=ef97116a29) | Nov 12, 2019 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [d0612d575f](https://linux-hardware.org/?probe=d0612d575f) | Nov 04, 2019 |
| Foxconn       | A76GMV                      | Desktop     | [ddfa1ad143](https://linux-hardware.org/?probe=ddfa1ad143) | Oct 22, 2019 |
| Dell          | Inspiron 3443               | Notebook    | [daa04d519c](https://linux-hardware.org/?probe=daa04d519c) | Oct 15, 2019 |
| Sony          | VPCEC2JFX                   | Notebook    | [ad30a52539](https://linux-hardware.org/?probe=ad30a52539) | Oct 03, 2019 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [e486c2c05f](https://linux-hardware.org/?probe=e486c2c05f) | Sep 12, 2019 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [b09160e7cf](https://linux-hardware.org/?probe=b09160e7cf) | Sep 10, 2019 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [333fbc5a3b](https://linux-hardware.org/?probe=333fbc5a3b) | Aug 16, 2019 |
| Sony          | VPCEC2JFX                   | Notebook    | [f28ba85f16](https://linux-hardware.org/?probe=f28ba85f16) | Aug 04, 2019 |
| Acer          | Aspire ES1-572              | Notebook    | [432212e4c9](https://linux-hardware.org/?probe=432212e4c9) | Jul 31, 2019 |
| Acer          | Aspire ES1-572              | Notebook    | [8783b0d26c](https://linux-hardware.org/?probe=8783b0d26c) | Jul 31, 2019 |
| HP            | ProBook 440 G4              | Notebook    | [b0ae12ca81](https://linux-hardware.org/?probe=b0ae12ca81) | Jun 27, 2019 |
| Gigabyte      | EP35C-DS3R                  | Desktop     | [048c1a4f90](https://linux-hardware.org/?probe=048c1a4f90) | Jun 25, 2019 |
| Gigabyte      | A55M-DS2                    | Desktop     | [9e2c603e49](https://linux-hardware.org/?probe=9e2c603e49) | Jun 23, 2019 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [07dd5b8424](https://linux-hardware.org/?probe=07dd5b8424) | Jun 14, 2019 |
| Toshiba       | Satellite P755              | Notebook    | [8eaca3c3df](https://linux-hardware.org/?probe=8eaca3c3df) | Jun 13, 2019 |
| HP            | ProBook 645 G4              | Notebook    | [f2f88aaa9d](https://linux-hardware.org/?probe=f2f88aaa9d) | May 24, 2019 |
| HP            | ProBook 645 G4              | Notebook    | [049bd45822](https://linux-hardware.org/?probe=049bd45822) | May 24, 2019 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [cdf8203e8f](https://linux-hardware.org/?probe=cdf8203e8f) | Apr 24, 2019 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [5ca60ce3ac](https://linux-hardware.org/?probe=5ca60ce3ac) | Apr 06, 2019 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [c7dd2b6e26](https://linux-hardware.org/?probe=c7dd2b6e26) | Mar 26, 2019 |
| Lenovo        | B50-80 80EW                 | Notebook    | [275d0c887d](https://linux-hardware.org/?probe=275d0c887d) | Dec 28, 2018 |
| Lenovo        | B50-80 80EW                 | Notebook    | [603e6d3da4](https://linux-hardware.org/?probe=603e6d3da4) | Dec 28, 2018 |
| AMI           | Cherry Trail CR             | Desktop     | [e248592999](https://linux-hardware.org/?probe=e248592999) | Nov 03, 2018 |
| HP            | 1000                        | Notebook    | [9bf9fc957a](https://linux-hardware.org/?probe=9bf9fc957a) | Sep 04, 2018 |
| MSI           | A68HM-E33 V2                | Desktop     | [765c79328e](https://linux-hardware.org/?probe=765c79328e) | Jun 26, 2018 |
| ECS           | MCP61M-M3                   | Desktop     | [a51a8c96df](https://linux-hardware.org/?probe=a51a8c96df) | Apr 08, 2018 |
| HP            | Stream x360 Convertible ... | Convertible | [be4128010b](https://linux-hardware.org/?probe=be4128010b) | Feb 12, 2018 |
| HP            | 1000                        | Notebook    | [684f6b1db8](https://linux-hardware.org/?probe=684f6b1db8) | Jan 30, 2018 |
| Sony          | VGN-FW170J                  | Notebook    | [2ac505bc7b](https://linux-hardware.org/?probe=2ac505bc7b) | Jan 04, 2018 |
| HP            | 1000                        | Notebook    | [0e00b75fea](https://linux-hardware.org/?probe=0e00b75fea) | Dec 19, 2017 |
| Sony          | VGN-FW170J                  | Notebook    | [d2b4cdb291](https://linux-hardware.org/?probe=d2b4cdb291) | Nov 21, 2017 |
| Acer          | Aspire S3                   | Notebook    | [db53fb01bd](https://linux-hardware.org/?probe=db53fb01bd) | May 26, 2017 |
| Acer          | Aspire S3                   | Notebook    | [a3cfad5de1](https://linux-hardware.org/?probe=a3cfad5de1) | May 26, 2017 |
| HP            | Stream x360 Convertible ... | Convertible | [e721d571fe](https://linux-hardware.org/?probe=e721d571fe) | May 15, 2017 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [4d498130d3](https://linux-hardware.org/?probe=4d498130d3) | Dec 24, 2016 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [58bc94c592](https://linux-hardware.org/?probe=58bc94c592) | Dec 24, 2016 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [7201ee94b8](https://linux-hardware.org/?probe=7201ee94b8) | Nov 07, 2016 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [4567d9bca4](https://linux-hardware.org/?probe=4567d9bca4) | Nov 02, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Peru/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 57        | 11.45%  |
| Ubuntu 22.04                 | 26        | 5.22%   |
| Ubuntu 18.04                 | 22        | 4.42%   |
| OpenMandriva 4.3             | 20        | 4.02%   |
| Arch Rolling                 | 15        | 3.01%   |
| OpenMandriva 4.2             | 12        | 2.41%   |
| Manjaro                      | 12        | 2.41%   |
| Zorin 15                     | 10        | 2.01%   |
| OpenMandriva 23.03           | 10        | 2.01%   |
| Linux Mint 21.1              | 10        | 2.01%   |
| Fedora 38                    | 10        | 2.01%   |
| Ubuntu 19.10                 | 9         | 1.81%   |
| Debian 11                    | 9         | 1.81%   |
| openSUSE Tumbleweed-XXXXXXXX | 8         | 1.61%   |
| OpenMandriva 23.01           | 6         | 1.2%    |
| Linux Mint 20.3              | 6         | 1.2%    |
| KDE neon 20.04               | 6         | 1.2%    |
| Fedora 37                    | 6         | 1.2%    |
| Arch                         | 6         | 1.2%    |
| Zorin 16                     | 5         | 1%      |
| Xubuntu 20.04                | 5         | 1%      |
| ROSA R9                      | 5         | 1%      |
| Pop!_OS 22.04                | 5         | 1%      |
| Linux Mint 21.2              | 5         | 1%      |
| Kubuntu 20.04                | 5         | 1%      |
| Debian 10                    | 5         | 1%      |
| ArcoLinux Rolling            | 5         | 1%      |
| Ubuntu 23.04                 | 4         | 0.8%    |
| Ubuntu 21.10                 | 4         | 0.8%    |
| Ubuntu 21.04                 | 4         | 0.8%    |
| Pop!_OS 21.10                | 4         | 0.8%    |
| OpenMandriva 23.08           | 4         | 0.8%    |
| Linux Mint 20.1              | 4         | 0.8%    |
| Linux Mint 19.3              | 4         | 0.8%    |
| KDE neon 22.04               | 4         | 0.8%    |
| Debian                       | 4         | 0.8%    |
| CentOS 8                     | 4         | 0.8%    |
| Ubuntu 19.04                 | 3         | 0.6%    |
| ROSA R11.1                   | 3         | 0.6%    |
| ROSA R10                     | 3         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 124       | 25.94%  |
| OpenMandriva  | 58        | 12.13%  |
| Linux Mint    | 37        | 7.74%   |
| Fedora        | 30        | 6.28%   |
| Manjaro       | 22        | 4.6%    |
| Debian        | 22        | 4.6%    |
| Arch          | 22        | 4.6%    |
| ROSA          | 20        | 4.18%   |
| Zorin         | 17        | 3.56%   |
| Pop!_OS       | 15        | 3.14%   |
| openSUSE      | 11        | 2.3%    |
| Kubuntu       | 11        | 2.3%    |
| KDE neon      | 10        | 2.09%   |
| Ubuntu MATE   | 8         | 1.67%   |
| Xubuntu       | 7         | 1.46%   |
| Lubuntu       | 6         | 1.26%   |
| Endless       | 5         | 1.05%   |
| Elementary    | 5         | 1.05%   |
| ArcoLinux     | 5         | 1.05%   |
| CentOS        | 4         | 0.84%   |
| SteamOS       | 3         | 0.63%   |
| Parrot        | 3         | 0.63%   |
| Linux Lite    | 3         | 0.63%   |
| Kali          | 3         | 0.63%   |
| EndeavourOS   | 3         | 0.63%   |
| Ubuntu Unity  | 2         | 0.42%   |
| Ubuntu Budgie | 2         | 0.42%   |
| Peppermint    | 2         | 0.42%   |
| LMDE          | 2         | 0.42%   |
| Xero          | 1         | 0.21%   |
| Void Linux    | 1         | 0.21%   |
| Ubuntu Studio | 1         | 0.21%   |
| Solus         | 1         | 0.21%   |
| Q4OS          | 1         | 0.21%   |
| Oracle Linux  | 1         | 0.21%   |
| NixOS         | 1         | 0.21%   |
| MX            | 1         | 0.21%   |
| Manjaro-ARM   | 1         | 0.21%   |
| Laxer OS      | 1         | 0.21%   |
| Garuda Linux  | 1         | 0.21%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003            | 19        | 3.49%   |
| 5.10.14-desktop-1omv4002           | 10        | 1.83%   |
| 6.2.6-desktop-1omv2390             | 9         | 1.65%   |
| 5.3.0-40-generic                   | 8         | 1.47%   |
| 5.4.0-66-generic                   | 5         | 0.92%   |
| 5.4.0-28-generic                   | 5         | 0.92%   |
| 5.13.0-40-generic                  | 5         | 0.92%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 5         | 0.92%   |
| 6.1.1-desktop-1omv2290             | 4         | 0.73%   |
| 5.4.0-70-generic                   | 4         | 0.73%   |
| 5.4.0-58-generic                   | 4         | 0.73%   |
| 5.4.0-52-generic                   | 4         | 0.73%   |
| 5.4.0-42-generic                   | 4         | 0.73%   |
| 5.4.0-37-generic                   | 4         | 0.73%   |
| 5.4.0-31-generic                   | 4         | 0.73%   |
| 5.4.0-26-generic                   | 4         | 0.73%   |
| 5.15.0-52-generic                  | 4         | 0.73%   |
| 5.11.0-40-generic                  | 4         | 0.73%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 4         | 0.73%   |
| 5.10.0-13-amd64                    | 4         | 0.73%   |
| 6.5.0-15-generic                   | 3         | 0.55%   |
| 6.4.11-desktop-1omv2390            | 3         | 0.55%   |
| 6.3.5-desktop-3omv2390             | 3         | 0.55%   |
| 6.3.5-200.fc38.x86_64              | 3         | 0.55%   |
| 6.2.0-20-generic                   | 3         | 0.55%   |
| 5.4.0-73-generic                   | 3         | 0.55%   |
| 5.4.0-40-generic                   | 3         | 0.55%   |
| 5.4.0-39-generic                   | 3         | 0.55%   |
| 5.4.0-33-generic                   | 3         | 0.55%   |
| 5.3.0-46-generic                   | 3         | 0.55%   |
| 5.3.0-42-generic                   | 3         | 0.55%   |
| 5.3.0-26-generic                   | 3         | 0.55%   |
| 5.18.12-desktop-3omv4090           | 3         | 0.55%   |
| 5.17.5-arch1-1                     | 3         | 0.55%   |
| 5.15.0-91-generic                  | 3         | 0.55%   |
| 5.15.0-76-generic                  | 3         | 0.55%   |
| 5.15.0-71-generic                  | 3         | 0.55%   |
| 5.15.0-60-generic                  | 3         | 0.55%   |
| 5.15.0-58-generic                  | 3         | 0.55%   |
| 5.15.0-57-generic                  | 3         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 70        | 13.57%  |
| 5.15.0  | 46        | 8.91%   |
| 5.3.0   | 23        | 4.46%   |
| 5.13.0  | 21        | 4.07%   |
| 5.11.0  | 20        | 3.88%   |
| 5.16.7  | 19        | 3.68%   |
| 4.15.0  | 19        | 3.68%   |
| 6.2.0   | 16        | 3.1%    |
| 5.8.0   | 13        | 2.52%   |
| 5.10.0  | 12        | 2.33%   |
| 4.18.0  | 12        | 2.33%   |
| 6.2.6   | 11        | 2.13%   |
| 6.5.0   | 10        | 1.94%   |
| 5.10.14 | 10        | 1.94%   |
| 5.19.0  | 9         | 1.74%   |
| 5.0.0   | 8         | 1.55%   |
| 6.3.5   | 7         | 1.36%   |
| 6.1.1   | 5         | 0.97%   |
| 4.9.20  | 5         | 0.97%   |
| 6.4.11  | 4         | 0.78%   |
| 6.3.6   | 4         | 0.78%   |
| 5.17.5  | 4         | 0.78%   |
| 5.10.74 | 4         | 0.78%   |
| 4.9.60  | 4         | 0.78%   |
| 6.6.6   | 3         | 0.58%   |
| 6.4.6   | 3         | 0.58%   |
| 6.0.0   | 3         | 0.58%   |
| 5.18.12 | 3         | 0.58%   |
| 5.17.1  | 3         | 0.58%   |
| 6.6.2   | 2         | 0.39%   |
| 6.1.9   | 2         | 0.39%   |
| 6.1.4   | 2         | 0.39%   |
| 6.1.31  | 2         | 0.39%   |
| 6.1.20  | 2         | 0.39%   |
| 6.1.11  | 2         | 0.39%   |
| 6.1.0   | 2         | 0.39%   |
| 6.0.7   | 2         | 0.39%   |
| 6.0.15  | 2         | 0.39%   |
| 6.0.10  | 2         | 0.39%   |
| 5.9.11  | 2         | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 76        | 14.96%  |
| 5.15    | 60        | 11.81%  |
| 6.2     | 33        | 6.5%    |
| 5.10    | 33        | 6.5%    |
| 5.3     | 25        | 4.92%   |
| 5.16    | 25        | 4.92%   |
| 5.11    | 24        | 4.72%   |
| 5.13    | 22        | 4.33%   |
| 6.1     | 20        | 3.94%   |
| 4.15    | 19        | 3.74%   |
| 5.8     | 17        | 3.35%   |
| 6.5     | 16        | 3.15%   |
| 6.4     | 15        | 2.95%   |
| 6.3     | 15        | 2.95%   |
| 6.0     | 14        | 2.76%   |
| 5.19    | 13        | 2.56%   |
| 4.18    | 12        | 2.36%   |
| 5.17    | 10        | 1.97%   |
| 6.6     | 9         | 1.77%   |
| 5.0     | 8         | 1.57%   |
| 4.9     | 8         | 1.57%   |
| 5.18    | 6         | 1.18%   |
| 5.6     | 5         | 0.98%   |
| 5.7     | 4         | 0.79%   |
| 5.14    | 4         | 0.79%   |
| 5.12    | 4         | 0.79%   |
| 5.9     | 3         | 0.59%   |
| 4.19    | 2         | 0.39%   |
| 4.1     | 2         | 0.39%   |
| 5.1     | 1         | 0.2%    |
| 4.8     | 1         | 0.2%    |
| 4.4     | 1         | 0.2%    |
| 4.16    | 1         | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 441       | 96.08%  |
| i686    | 16        | 3.49%   |
| aarch64 | 2         | 0.44%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 197       | 41.47%  |
| KDE5            | 110       | 23.16%  |
| XFCE            | 39        | 8.21%   |
| X-Cinnamon      | 32        | 6.74%   |
| Unknown         | 26        | 5.47%   |
| MATE            | 16        | 3.37%   |
| KDE4            | 9         | 1.89%   |
| KDE             | 9         | 1.89%   |
| LXQt            | 6         | 1.26%   |
| Pantheon        | 5         | 1.05%   |
| i3              | 5         | 1.05%   |
| Budgie          | 5         | 1.05%   |
| LXDE            | 4         | 0.84%   |
| Unity           | 2         | 0.42%   |
| sway            | 2         | 0.42%   |
| GNOME Flashback | 2         | 0.42%   |
| spectrwm        | 1         | 0.21%   |
| qtile           | 1         | 0.21%   |
| icewm           | 1         | 0.21%   |
| Hyprland        | 1         | 0.21%   |
| Deepin          | 1         | 0.21%   |
| awesome         | 1         | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 354       | 74.37%  |
| Wayland | 96        | 20.17%  |
| Unknown | 23        | 4.83%   |
| Tty     | 3         | 0.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 213       | 44.65%  |
| SDDM    | 92        | 19.29%  |
| GDM     | 57        | 11.95%  |
| GDM3    | 48        | 10.06%  |
| LightDM | 47        | 9.85%   |
| KDM     | 9         | 1.89%   |
| TDM     | 6         | 1.26%   |
| XDM     | 1         | 0.21%   |
| SLIMSKI | 1         | 0.21%   |
| LY-DM   | 1         | 0.21%   |
| Ly      | 1         | 0.21%   |
| LXDM    | 1         | 0.21%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_PE   | 229       | 48.62%  |
| en_US   | 127       | 26.96%  |
| es_ES   | 43        | 9.13%   |
| Unknown | 28        | 5.94%   |
| es_MX   | 12        | 2.55%   |
| en_GB   | 6         | 1.27%   |
| C       | 6         | 1.27%   |
| en_CA   | 3         | 0.64%   |
| it_IT   | 2         | 0.42%   |
| fr_FR   | 2         | 0.42%   |
| de_DE   | 2         | 0.42%   |
| ca_ES   | 2         | 0.42%   |
| ru_RU   | 1         | 0.21%   |
| POSIX   | 1         | 0.21%   |
| es_VE   | 1         | 0.21%   |
| es_US   | 1         | 0.21%   |
| es_CO   | 1         | 0.21%   |
| es_AR   | 1         | 0.21%   |
| en_NZ   | 1         | 0.21%   |
| en_DK   | 1         | 0.21%   |
| Default | 1         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 238       | 50.96%  |
| BIOS | 229       | 49.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 340       | 71.73%  |
| Btrfs   | 48        | 10.13%  |
| Overlay | 45        | 9.49%   |
| Unknown | 15        | 3.16%   |
| Xfs     | 12        | 2.53%   |
| Tmpfs   | 11        | 2.32%   |
| Ext3    | 3         | 0.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 238       | 50.53%  |
| GPT     | 184       | 39.07%  |
| MBR     | 49        | 10.4%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 394       | 83.3%   |
| Yes       | 79        | 16.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 283       | 60.21%  |
| Yes       | 187       | 39.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 95        | 20.74%  |
| Lenovo                  | 77        | 16.81%  |
| ASUSTek Computer        | 64        | 13.97%  |
| Gigabyte Technology     | 41        | 8.95%   |
| Dell                    | 34        | 7.42%   |
| MSI                     | 27        | 5.9%    |
| Intel                   | 24        | 5.24%   |
| Toshiba                 | 19        | 4.15%   |
| Acer                    | 16        | 3.49%   |
| ASRock                  | 9         | 1.97%   |
| Sony                    | 6         | 1.31%   |
| Foxconn                 | 6         | 1.31%   |
| Chuwi                   | 6         | 1.31%   |
| Apple                   | 4         | 0.87%   |
| HUAWEI                  | 3         | 0.66%   |
| Unknown                 | 3         | 0.66%   |
| Samsung Electronics     | 2         | 0.44%   |
| Raspberry Pi Foundation | 2         | 0.44%   |
| ECS                     | 2         | 0.44%   |
| AMI                     | 2         | 0.44%   |
| Advance                 | 2         | 0.44%   |
| SZMZ                    | 1         | 0.22%   |
| System76                | 1         | 0.22%   |
| Razer                   | 1         | 0.22%   |
| PCChips                 | 1         | 0.22%   |
| Microsoft               | 1         | 0.22%   |
| Google                  | 1         | 0.22%   |
| GIADA                   | 1         | 0.22%   |
| eMachines               | 1         | 0.22%   |
| efirstview              | 1         | 0.22%   |
| Deltron                 | 1         | 0.22%   |
| Compal                  | 1         | 0.22%   |
| Biostar                 | 1         | 0.22%   |
| AZW                     | 1         | 0.22%   |
| Acidanthera             | 1         | 0.22%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chuwi GemiBook Pro                     | 5         | 1.09%   |
| MSI MS-7721                            | 4         | 0.87%   |
| Lenovo V330-15IKB 81AX                 | 4         | 0.87%   |
| HP Pavilion Laptop 15-cw1xxx           | 4         | 0.87%   |
| HP 14                                  | 4         | 0.87%   |
| Gigabyte B75M-D3H                      | 4         | 0.87%   |
| Gigabyte 970A-DS3P                     | 4         | 0.87%   |
| Toshiba Satellite L45-B                | 3         | 0.66%   |
| Lenovo V310-15ISK 80SY                 | 3         | 0.66%   |
| Lenovo IdeaPad 3 14ADA05 81W0          | 3         | 0.66%   |
| Gigabyte F2A68HM-H                     | 3         | 0.66%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA | 3         | 0.66%   |
| ASUS All Series                        | 3         | 0.66%   |
| Unknown                                | 3         | 0.66%   |
| Toshiba Satellite C45-A                | 2         | 0.44%   |
| Lenovo IdeaPad S540-14API 81NH         | 2         | 0.44%   |
| Lenovo IdeaPad S145-15IWL 81MV         | 2         | 0.44%   |
| Lenovo IdeaPad 330S-14IKB 81F4         | 2         | 0.44%   |
| Lenovo G400 20235                      | 2         | 0.44%   |
| Intel H61                              | 2         | 0.44%   |
| Intel DH55PJ AAE93812-303              | 2         | 0.44%   |
| HP ProBook 645 G4                      | 2         | 0.44%   |
| HP Pavilion Gaming Laptop 15-dk1xxx    | 2         | 0.44%   |
| HP Pavilion g4                         | 2         | 0.44%   |
| HP Pavilion dv4                        | 2         | 0.44%   |
| HP Notebook                            | 2         | 0.44%   |
| HP Laptop 15-ef1xxx                    | 2         | 0.44%   |
| HP Compaq Presario C700                | 2         | 0.44%   |
| HP Compaq 4000 Pro SFF PC              | 2         | 0.44%   |
| HP 450                                 | 2         | 0.44%   |
| HP 250 G7 Notebook PC                  | 2         | 0.44%   |
| HP 250 G5 Notebook PC                  | 2         | 0.44%   |
| Gigabyte Z77X-UD5H                     | 2         | 0.44%   |
| Gigabyte X570 AORUS MASTER             | 2         | 0.44%   |
| Gigabyte A520M H                       | 2         | 0.44%   |
| Foxconn 500B Microtower                | 2         | 0.44%   |
| Dell XPS 13 9360                       | 2         | 0.44%   |
| Dell OptiPlex 7010                     | 2         | 0.44%   |
| Dell Latitude E7450                    | 2         | 0.44%   |
| Dell Latitude E5470                    | 2         | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 26        | 5.68%   |
| HP Pavilion        | 22        | 4.8%    |
| Lenovo ThinkPad    | 18        | 3.93%   |
| Toshiba Satellite  | 17        | 3.71%   |
| ASUS VivoBook      | 14        | 3.06%   |
| Dell Latitude      | 13        | 2.84%   |
| Acer Aspire        | 13        | 2.84%   |
| HP Laptop          | 11        | 2.4%    |
| HP ProBook         | 10        | 2.18%   |
| HP Compaq          | 10        | 2.18%   |
| ASUS PRIME         | 9         | 1.97%   |
| ASUS ROG           | 8         | 1.75%   |
| Dell OptiPlex      | 7         | 1.53%   |
| Dell Inspiron      | 7         | 1.53%   |
| Lenovo ThinkCentre | 5         | 1.09%   |
| Lenovo Legion      | 5         | 1.09%   |
| Chuwi GemiBook     | 5         | 1.09%   |
| ASUS TUF           | 5         | 1.09%   |
| MSI MS-7721        | 4         | 0.87%   |
| Lenovo V330-15IKB  | 4         | 0.87%   |
| HP 250             | 4         | 0.87%   |
| HP 14              | 4         | 0.87%   |
| Gigabyte B75M-D3H  | 4         | 0.87%   |
| Gigabyte 970A-DS3P | 4         | 0.87%   |
| Lenovo V310-15ISK  | 3         | 0.66%   |
| HP OMEN            | 3         | 0.66%   |
| HP ENVY            | 3         | 0.66%   |
| HP EliteBook       | 3         | 0.66%   |
| Gigabyte X570      | 3         | 0.66%   |
| Gigabyte F2A68HM-H | 3         | 0.66%   |
| ASUS ASUS          | 3         | 0.66%   |
| ASUS All           | 3         | 0.66%   |
| ASRock X570        | 3         | 0.66%   |
| Unknown            | 3         | 0.66%   |
| RPi Raspberry      | 2         | 0.44%   |
| Lenovo Yoga        | 2         | 0.44%   |
| Lenovo G400        | 2         | 0.44%   |
| Intel H61          | 2         | 0.44%   |
| Intel DH61WW       | 2         | 0.44%   |
| Intel DH55PJ       | 2         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 54        | 11.79%  |
| 2019    | 42        | 9.17%   |
| 2018    | 40        | 8.73%   |
| 2012    | 37        | 8.08%   |
| 2014    | 35        | 7.64%   |
| 2016    | 34        | 7.42%   |
| 2013    | 32        | 6.99%   |
| 2021    | 30        | 6.55%   |
| 2017    | 29        | 6.33%   |
| 2011    | 27        | 5.9%    |
| 2015    | 20        | 4.37%   |
| 2010    | 19        | 4.15%   |
| 2008    | 14        | 3.06%   |
| 2022    | 13        | 2.84%   |
| 2007    | 11        | 2.4%    |
| 2009    | 9         | 1.97%   |
| 2023    | 6         | 1.31%   |
| 2006    | 3         | 0.66%   |
| Unknown | 2         | 0.44%   |
| 2004    | 1         | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 278       | 60.7%   |
| Desktop        | 162       | 35.37%  |
| Convertible    | 5         | 1.09%   |
| All in one     | 5         | 1.09%   |
| Mini pc        | 3         | 0.66%   |
| System on chip | 2         | 0.44%   |
| Tablet         | 2         | 0.44%   |
| Server         | 1         | 0.22%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 424       | 92.37%  |
| Enabled  | 35        | 7.63%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 456       | 99.56%  |
| Yes  | 2         | 0.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 122       | 25.96%  |
| 4.01-8.0    | 119       | 25.32%  |
| 3.01-4.0    | 88        | 18.72%  |
| 16.01-24.0  | 69        | 14.68%  |
| 32.01-64.0  | 21        | 4.47%   |
| 1.01-2.0    | 18        | 3.83%   |
| 24.01-32.0  | 11        | 2.34%   |
| 64.01-256.0 | 11        | 2.34%   |
| 2.01-3.0    | 8         | 1.7%    |
| 0.51-1.0    | 3         | 0.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 163       | 31.53%  |
| 2.01-3.0   | 143       | 27.66%  |
| 4.01-8.0   | 84        | 16.25%  |
| 3.01-4.0   | 64        | 12.38%  |
| 0.51-1.0   | 37        | 7.16%   |
| 8.01-16.0  | 21        | 4.06%   |
| 16.01-24.0 | 3         | 0.58%   |
| 32.01-64.0 | 1         | 0.19%   |
| 0.01-0.5   | 1         | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 298       | 63.54%  |
| 2      | 127       | 27.08%  |
| 3      | 26        | 5.54%   |
| 4      | 11        | 2.35%   |
| 5      | 3         | 0.64%   |
| 6      | 2         | 0.43%   |
| 9      | 1         | 0.21%   |
| 0      | 1         | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 288       | 62.61%  |
| Yes       | 172       | 37.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 400       | 86.96%  |
| No        | 60        | 13.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 346       | 74.73%  |
| No        | 117       | 25.27%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 284       | 61.61%  |
| No        | 177       | 38.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Peru    | 458       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lima                  | 311       | 65.61%  |
| Arequipa              | 34        | 7.17%   |
| Trujillo              | 28        | 5.91%   |
| Huancayo              | 11        | 2.32%   |
| Chiclayo              | 10        | 2.11%   |
| Piura                 | 9         | 1.9%    |
| Cusco                 | 9         | 1.9%    |
| Tacna                 | 6         | 1.27%   |
| Ica                   | 6         | 1.27%   |
| Moquegua              | 4         | 0.84%   |
| La Victoria           | 3         | 0.63%   |
| Villa                 | 2         | 0.42%   |
| Santiago de Surco     | 2         | 0.42%   |
| San Isidro            | 2         | 0.42%   |
| Puno                  | 2         | 0.42%   |
| Junin                 | 2         | 0.42%   |
| Juliaca               | 2         | 0.42%   |
| Iquitos               | 2         | 0.42%   |
| Ilo                   | 2         | 0.42%   |
| Distrito de Lima      | 2         | 0.42%   |
| Callao                | 2         | 0.42%   |
| Barranco              | 2         | 0.42%   |
| Abancay               | 2         | 0.42%   |
| Tarapoto              | 1         | 0.21%   |
| Surquillo             | 1         | 0.21%   |
| Sullana               | 1         | 0.21%   |
| San Vicente de Canete | 1         | 0.21%   |
| San Borja             | 1         | 0.21%   |
| Punta Colorada        | 1         | 0.21%   |
| Pucallpa              | 1         | 0.21%   |
| Pisco                 | 1         | 0.21%   |
| Oxapampa              | 1         | 0.21%   |
| Miraflores District   | 1         | 0.21%   |
| Machupicchu           | 1         | 0.21%   |
| Lurin                 | 1         | 0.21%   |
| La Libertad           | 1         | 0.21%   |
| Huaraz                | 1         | 0.21%   |
| Huancavelica          | 1         | 0.21%   |
| Chimbote              | 1         | 0.21%   |
| Cajamarca             | 1         | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate                        | 121       | 187    | 19.61%  |
| WDC                            | 111       | 166    | 17.99%  |
| Kingston                       | 75        | 92     | 12.16%  |
| Toshiba                        | 62        | 73     | 10.05%  |
| Samsung Electronics            | 46        | 64     | 7.46%   |
| SanDisk                        | 26        | 30     | 4.21%   |
| Crucial                        | 21        | 30     | 3.4%    |
| Unknown                        | 17        | 25     | 2.76%   |
| Hewlett-Packard                | 11        | 12     | 1.78%   |
| Intel                          | 10        | 12     | 1.62%   |
| SK hynix                       | 9         | 13     | 1.46%   |
| Micron Technology              | 9         | 10     | 1.46%   |
| Hitachi                        | 9         | 13     | 1.46%   |
| HGST                           | 8         | 8      | 1.3%    |
| KIOXIA                         | 7         | 8      | 1.13%   |
| Kingston Technology Company    | 7         | 9      | 1.13%   |
| A-DATA Technology              | 6         | 6      | 0.97%   |
| Netac                          | 5         | 5      | 0.81%   |
| Gigabyte Technology            | 5         | 5      | 0.81%   |
| Silicon Motion                 | 4         | 4      | 0.65%   |
| Phison Electronics             | 4         | 4      | 0.65%   |
| Micron/Crucial Technology      | 4         | 10     | 0.65%   |
| LITEON                         | 4         | 4      | 0.65%   |
| TO Exter                       | 3         | 7      | 0.49%   |
| PNY                            | 3         | 3      | 0.49%   |
| Unknown                        | 3         | 5      | 0.49%   |
| UMIS                           | 2         | 2      | 0.32%   |
| Team                           | 2         | 2      | 0.32%   |
| China                          | 2         | 2      | 0.32%   |
| Apple                          | 2         | 2      | 0.32%   |
| WD MediaMax                    | 1         | 1      | 0.16%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.16%   |
| SSSTC                          | 1         | 1      | 0.16%   |
| Solid State Storage Technology | 1         | 1      | 0.16%   |
| Reletech-P400                  | 1         | 1      | 0.16%   |
| Phison                         | 1         | 1      | 0.16%   |
| NGFF                           | 1         | 1      | 0.16%   |
| Mushkin                        | 1         | 2      | 0.16%   |
| MSI                            | 1         | 1      | 0.16%   |
| Maxone                         | 1         | 2      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 24        | 3.51%   |
| Seagate ST1000LM035-1RK172 1TB     | 21        | 3.07%   |
| Seagate ST500DM002-1BD142 500GB    | 15        | 2.2%    |
| Seagate ST1000DM010-2EP102 1TB     | 12        | 1.76%   |
| Toshiba MQ04ABF100 1TB             | 11        | 1.61%   |
| Kingston SA400S37480G 480GB SSD    | 11        | 1.61%   |
| Toshiba MQ01ABD100 1TB             | 10        | 1.46%   |
| Kingston SA400S37120G 120GB SSD    | 9         | 1.32%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 8         | 1.17%   |
| WDC WD10EZEX-08WN4A0 1TB           | 7         | 1.02%   |
| Toshiba DT01ACA100 1TB             | 6         | 0.88%   |
| Seagate ST2000DM001-1ER164 2TB     | 6         | 0.88%   |
| HP SSD S700 500GB                  | 6         | 0.88%   |
| Unknown MMC Card  32GB             | 5         | 0.73%   |
| Toshiba MQ01ABF050 500GB           | 5         | 0.73%   |
| Seagate ST9500325AS 500GB          | 5         | 0.73%   |
| Seagate ST3500418AS 500GB          | 5         | 0.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 5         | 0.73%   |
| Seagate ST1000DM003-1CH162 1TB     | 5         | 0.73%   |
| Netac SSD 256GB                    | 5         | 0.73%   |
| Crucial CT500MX500SSD4 500GB       | 5         | 0.73%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 4         | 0.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 4         | 0.59%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 4         | 0.59%   |
| WDC WDS100T3X0C-00SJG0 1TB         | 4         | 0.59%   |
| WDC WD10SPZX-24Z10 1TB             | 4         | 0.59%   |
| WDC WD10JPCX-24UE4T0 1TB           | 4         | 0.59%   |
| Unknown SD32G  32GB                | 4         | 0.59%   |
| Seagate ST500LT012-1DG142 500GB    | 4         | 0.59%   |
| Seagate ST3500413AS 500GB          | 4         | 0.59%   |
| Seagate ST3500312CS 500GB          | 4         | 0.59%   |
| Seagate ST2000DM006-2DM164 2TB     | 4         | 0.59%   |
| Seagate ST1000LM049-2GH172 1TB     | 4         | 0.59%   |
| SanDisk NVMe SSD Drive 1TB         | 4         | 0.59%   |
| Kingston Company SNV2S1000G 1TB    | 4         | 0.59%   |
| Kingston SNVS500G 500GB            | 4         | 0.59%   |
| Kingston SNVS250G 250GB            | 4         | 0.59%   |
| Kingston SA400S37960G 960GB SSD    | 4         | 0.59%   |
| Intel SSDPEKNU512GZ 512GB          | 4         | 0.59%   |
| WDC WD3200AAJS-56M0A0 320GB        | 3         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 119       | 179    | 40.34%  |
| WDC                 | 80        | 107    | 27.12%  |
| Toshiba             | 60        | 71     | 20.34%  |
| Samsung Electronics | 12        | 16     | 4.07%   |
| Hitachi             | 9         | 13     | 3.05%   |
| HGST                | 8         | 8      | 2.71%   |
| TO Exter            | 3         | 7      | 1.02%   |
| KESU                | 1         | 1      | 0.34%   |
| Fujitsu             | 1         | 1      | 0.34%   |
| Apple               | 1         | 1      | 0.34%   |
| ACASIS              | 1         | 1      | 0.34%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 60        | 70     | 33.52%  |
| WDC                 | 31        | 42     | 17.32%  |
| Crucial             | 17        | 24     | 9.5%    |
| Hewlett-Packard     | 11        | 11     | 6.15%   |
| Samsung Electronics | 9         | 11     | 5.03%   |
| SanDisk             | 7         | 9      | 3.91%   |
| A-DATA Technology   | 6         | 6      | 3.35%   |
| Netac               | 5         | 5      | 2.79%   |
| LITEON              | 4         | 4      | 2.23%   |
| Gigabyte Technology | 4         | 4      | 2.23%   |
| Seagate             | 3         | 7      | 1.68%   |
| PNY                 | 3         | 3      | 1.68%   |
| Team                | 2         | 2      | 1.12%   |
| Intel               | 2         | 2      | 1.12%   |
| China               | 2         | 2      | 1.12%   |
| Toshiba             | 1         | 1      | 0.56%   |
| SSSTC               | 1         | 1      | 0.56%   |
| SK hynix            | 1         | 4      | 0.56%   |
| Reletech-P400       | 1         | 1      | 0.56%   |
| NGFF                | 1         | 1      | 0.56%   |
| MSI                 | 1         | 1      | 0.56%   |
| Maxone              | 1         | 2      | 0.56%   |
| Lenovo              | 1         | 1      | 0.56%   |
| KingSpec            | 1         | 1      | 0.56%   |
| GLOWAY              | 1         | 1      | 0.56%   |
| Dogfish             | 1         | 1      | 0.56%   |
| Apple               | 1         | 1      | 0.56%   |
| Unknown             | 1         | 1      | 0.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 269       | 405    | 46.06%  |
| SSD     | 163       | 219    | 27.91%  |
| NVMe    | 129       | 179    | 22.09%  |
| MMC     | 18        | 23     | 3.08%   |
| Unknown | 5         | 10     | 0.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 359       | 615    | 69.31%  |
| NVMe | 129       | 179    | 24.9%   |
| MMC  | 18        | 23     | 3.47%   |
| SAS  | 12        | 19     | 2.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 236       | 353    | 54.13%  |
| 0.51-1.0   | 169       | 219    | 38.76%  |
| 1.01-2.0   | 20        | 36     | 4.59%   |
| 3.01-4.0   | 4         | 6      | 0.92%   |
| 4.01-10.0  | 4         | 7      | 0.92%   |
| 2.01-3.0   | 3         | 3      | 0.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 119       | 24.59%  |
| 101-250        | 103       | 21.28%  |
| 501-1000       | 91        | 18.8%   |
| 51-100         | 35        | 7.23%   |
| 21-50          | 33        | 6.82%   |
| 1001-2000      | 33        | 6.82%   |
| 1-20           | 33        | 6.82%   |
| More than 3000 | 15        | 3.1%    |
| 2001-3000      | 15        | 3.1%    |
| Unknown        | 7         | 1.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 192       | 38.4%   |
| 21-50          | 92        | 18.4%   |
| 101-250        | 62        | 12.4%   |
| 51-100         | 48        | 9.6%    |
| 251-500        | 47        | 9.4%    |
| 501-1000       | 26        | 5.2%    |
| 1001-2000      | 16        | 3.2%    |
| Unknown        | 7         | 1.4%    |
| More than 3000 | 6         | 1.2%    |
| 2001-3000      | 4         | 0.8%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD3200AAJS-56M0A0 320GB          | 3         | 4      | 5%      |
| Seagate ST1000DM003-9YN162 1TB       | 3         | 3      | 5%      |
| Seagate ST1000DM003-1CH162 1TB       | 3         | 4      | 5%      |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 2         | 2      | 3.33%   |
| WDC WD10JPCX-24UE4T0 1TB             | 2         | 2      | 3.33%   |
| Seagate ST9500325AS 500GB            | 2         | 2      | 3.33%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 3      | 3.33%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 2      | 3.33%   |
| Seagate ST3500418AS 500GB            | 2         | 2      | 3.33%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 2      | 3.33%   |
| WDC WDS100T2G0A-00JH30 1TB SSD       | 1         | 1      | 1.67%   |
| WDC WD800BD-00MRA1 80GB              | 1         | 1      | 1.67%   |
| WDC WD5000AAKS-00V1A0 500GB          | 1         | 1      | 1.67%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 1      | 1.67%   |
| WDC WD3200AAJS-00L7A0 320GB          | 1         | 1      | 1.67%   |
| WDC WD20EARX-00PASB0 2TB             | 1         | 1      | 1.67%   |
| WDC WD1600AAJS-75M0A0 160GB          | 1         | 1      | 1.67%   |
| Toshiba MQ04ABF100 1TB               | 1         | 1      | 1.67%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1      | 1.67%   |
| Toshiba MK6475GSX 640GB              | 1         | 1      | 1.67%   |
| Toshiba MK5065GSXN 500GB             | 1         | 1      | 1.67%   |
| Toshiba MK5056GSY 500GB              | 1         | 1      | 1.67%   |
| Toshiba MK4058GSX 400GB              | 1         | 1      | 1.67%   |
| Toshiba MK2035GSS 200GB              | 1         | 1      | 1.67%   |
| Toshiba HDWJ110 1TB                  | 1         | 1      | 1.67%   |
| Toshiba DT01ACA100 1TB               | 1         | 1      | 1.67%   |
| SSSTC CVB-8D128-HP 128GB             | 1         | 1      | 1.67%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 1         | 1      | 1.67%   |
| Seagate ST980811AS 80GB              | 1         | 1      | 1.67%   |
| Seagate ST9250315AS 250GB            | 1         | 1      | 1.67%   |
| Seagate ST500DM002-9YN14C 500GB      | 1         | 2      | 1.67%   |
| Seagate ST3500312CS 500GB            | 1         | 1      | 1.67%   |
| Seagate ST3320820SCE 320GB           | 1         | 2      | 1.67%   |
| Seagate ST3250820AS 249GB            | 1         | 1      | 1.67%   |
| Seagate ST1000LM014-1EJ164 1TB       | 1         | 1      | 1.67%   |
| Samsung Electronics SP1644N 160GB    | 1         | 1      | 1.67%   |
| Samsung Electronics HD161HJ 160GB    | 1         | 2      | 1.67%   |
| Kingston SA400S37480G 480GB SSD      | 1         | 1      | 1.67%   |
| Hitachi HTS725050A7E630 500GB        | 1         | 1      | 1.67%   |
| Hitachi HTS545050B9A300 500GB        | 1         | 1      | 1.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 27     | 38.98%  |
| WDC                 | 14        | 15     | 23.73%  |
| Toshiba             | 8         | 9      | 13.56%  |
| Hitachi             | 5         | 7      | 8.47%   |
| Samsung Electronics | 2         | 3      | 3.39%   |
| HGST                | 2         | 2      | 3.39%   |
| SSSTC               | 1         | 1      | 1.69%   |
| SK hynix            | 1         | 1      | 1.69%   |
| Kingston            | 1         | 1      | 1.69%   |
| Hewlett-Packard     | 1         | 1      | 1.69%   |
| A-DATA Technology   | 1         | 1      | 1.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 27     | 45.1%   |
| WDC                 | 11        | 12     | 21.57%  |
| Toshiba             | 8         | 9      | 15.69%  |
| Hitachi             | 5         | 7      | 9.8%    |
| Samsung Electronics | 2         | 3      | 3.92%   |
| HGST                | 2         | 2      | 3.92%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 45        | 60     | 84.91%  |
| SSD  | 7         | 7      | 13.21%  |
| NVMe | 1         | 1      | 1.89%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                   | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba MK3252GSX 320GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 273       | 475    | 53.95%  |
| Works    | 180       | 291    | 35.57%  |
| Malfunc  | 52        | 68     | 10.28%  |
| Failed   | 1         | 2      | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 300       | 54.45%  |
| AMD                              | 104       | 18.87%  |
| SanDisk                          | 29        | 5.26%   |
| Samsung Electronics              | 26        | 4.72%   |
| Kingston Technology Company      | 24        | 4.36%   |
| Micron Technology                | 9         | 1.63%   |
| SK hynix                         | 8         | 1.45%   |
| Micron/Crucial Technology        | 8         | 1.45%   |
| KIOXIA                           | 7         | 1.27%   |
| Silicon Motion                   | 6         | 1.09%   |
| Marvell Technology Group         | 6         | 1.09%   |
| Phison Electronics               | 5         | 0.91%   |
| Nvidia                           | 5         | 0.91%   |
| JMicron Technology               | 3         | 0.54%   |
| Union Memory (Shenzhen)          | 2         | 0.36%   |
| Toshiba America Info Systems     | 1         | 0.18%   |
| Solid State Storage Technology   | 1         | 0.18%   |
| Silicon Integrated Systems [SiS] | 1         | 0.18%   |
| LSI Logic / Symbios Logic        | 1         | 0.18%   |
| INNOGRIT                         | 1         | 0.18%   |
| Hewlett-Packard                  | 1         | 0.18%   |
| Broadcom / LSI                   | 1         | 0.18%   |
| Biwin Storage Technology         | 1         | 0.18%   |
| ASMedia Technology               | 1         | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 70        | 11.2%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 34        | 5.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 24        | 3.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 21        | 3.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 16        | 2.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 16        | 2.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 13        | 2.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 13        | 2.08%   |
| AMD 500 Series Chipset SATA Controller                                         | 13        | 2.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 11        | 1.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 1.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 10        | 1.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 1.44%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 9         | 1.44%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 9         | 1.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 9         | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 9         | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 9         | 1.44%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 8         | 1.28%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                             | 8         | 1.28%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 1.28%   |
| Intel Comet Lake SATA AHCI Controller                                          | 8         | 1.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 8         | 1.28%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 7         | 1.12%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 7         | 1.12%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 7         | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 7         | 1.12%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 6         | 0.96%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 6         | 0.96%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 5         | 0.8%    |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton2]                                     | 5         | 0.8%    |
| Intel SATA Controller [RAID mode]                                              | 5         | 0.8%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 5         | 0.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 0.8%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 0.8%    |
| SK hynix BC511 NVMe SSD                                                        | 4         | 0.64%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                             | 4         | 0.64%   |
| Intel Tiger Lake-LP SATA Controller                                            | 4         | 0.64%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 0.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 333       | 59.25%  |
| NVMe | 129       | 22.95%  |
| IDE  | 56        | 9.96%   |
| RAID | 41        | 7.3%    |
| SAS  | 2         | 0.36%   |
| SCSI | 1         | 0.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 326       | 71.18%  |
| AMD    | 130       | 28.38%  |
| ARM    | 2         | 0.44%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 2.18%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 1.74%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 1.53%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 7         | 1.53%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 7         | 1.53%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 1.31%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 5         | 1.09%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 1.09%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 1.09%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 1.09%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 5         | 1.09%   |
| Intel Celeron J4115 CPU @ 1.80GHz             | 5         | 1.09%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 1.09%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 5         | 1.09%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 1.09%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 0.87%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.87%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 4         | 0.87%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 0.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 0.87%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz   | 3         | 0.65%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 3         | 0.65%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 0.65%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 3         | 0.65%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 0.65%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 3         | 0.65%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 3         | 0.65%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 3         | 0.65%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 0.65%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3         | 0.65%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 3         | 0.65%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.65%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 0.65%   |
| Intel Celeron CPU 550 @ 2.00GHz               | 3         | 0.65%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 0.65%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 3         | 0.65%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 0.65%   |
| AMD FX-8350 Eight-Core Processor              | 3         | 0.65%   |
| AMD Athlon Silver 3050U with Radeon Graphics  | 3         | 0.65%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 2         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 95        | 20.74%  |
| Intel Core i7           | 92        | 20.09%  |
| Intel Core i3           | 44        | 9.61%   |
| AMD Ryzen 7             | 31        | 6.77%   |
| AMD Ryzen 5             | 31        | 6.77%   |
| Other                   | 26        | 5.68%   |
| Intel Celeron           | 18        | 3.93%   |
| Intel Core 2 Duo        | 11        | 2.4%    |
| Intel Atom              | 8         | 1.75%   |
| Intel Pentium           | 7         | 1.53%   |
| AMD Ryzen 9             | 7         | 1.53%   |
| AMD Ryzen 3             | 7         | 1.53%   |
| AMD FX                  | 7         | 1.53%   |
| Intel Xeon              | 6         | 1.31%   |
| Intel Pentium Dual-Core | 6         | 1.31%   |
| AMD A8                  | 6         | 1.31%   |
| Intel Pentium Dual      | 5         | 1.09%   |
| AMD A4                  | 5         | 1.09%   |
| AMD A10                 | 5         | 1.09%   |
| AMD Athlon              | 4         | 0.87%   |
| AMD A6                  | 4         | 0.87%   |
| AMD Phenom II X4        | 3         | 0.66%   |
| AMD E1                  | 3         | 0.66%   |
| Intel Pentium Gold      | 2         | 0.44%   |
| Intel Pentium 4         | 2         | 0.44%   |
| Intel Core 2 Quad       | 2         | 0.44%   |
| Intel Core 2            | 2         | 0.44%   |
| AMD Sempron             | 2         | 0.44%   |
| AMD Ryzen 7 PRO         | 2         | 0.44%   |
| AMD E                   | 2         | 0.44%   |
| Intel Pentium D         | 1         | 0.22%   |
| Intel Genuine           | 1         | 0.22%   |
| Intel Core i9           | 1         | 0.22%   |
| Intel Celeron M         | 1         | 0.22%   |
| AMD Ryzen 5 PRO         | 1         | 0.22%   |
| AMD Quad-Core           | 1         | 0.22%   |
| AMD Phenom II X3        | 1         | 0.22%   |
| AMD C-50                | 1         | 0.22%   |
| AMD Athlon X4           | 1         | 0.22%   |
| AMD Athlon II X3        | 1         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 180       | 39.3%   |
| 4       | 172       | 37.55%  |
| 8       | 37        | 8.08%   |
| 6       | 32        | 6.99%   |
| 1       | 15        | 3.28%   |
| 16      | 5         | 1.09%   |
| 12      | 4         | 0.87%   |
| 3       | 4         | 0.87%   |
| 10      | 3         | 0.66%   |
| 14      | 2         | 0.44%   |
| Unknown | 2         | 0.44%   |
| 24      | 1         | 0.22%   |
| 20      | 1         | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 457       | 99.78%  |
| 2      | 1         | 0.22%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 330       | 72.05%  |
| 1       | 126       | 27.51%  |
| Unknown | 2         | 0.44%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 447       | 96.75%  |
| 64-bit         | 6         | 1.3%    |
| Unknown        | 6         | 1.3%    |
| 32-bit         | 3         | 0.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 138       | 28.93%  |
| 0x306a9    | 26        | 5.45%   |
| 0x206a7    | 23        | 4.82%   |
| 0x306c3    | 15        | 3.14%   |
| 0x806ec    | 12        | 2.52%   |
| 0x806ea    | 11        | 2.31%   |
| 0x40651    | 11        | 2.31%   |
| 0x08108109 | 11        | 2.31%   |
| 0x806e9    | 10        | 2.1%    |
| 0x406e3    | 10        | 2.1%    |
| 0x1067a    | 10        | 2.1%    |
| 0x306d4    | 9         | 1.89%   |
| 0x906ea    | 7         | 1.47%   |
| 0x506e3    | 7         | 1.47%   |
| 0x0a50000c | 7         | 1.47%   |
| 0x08701021 | 7         | 1.47%   |
| 0x08108102 | 7         | 1.47%   |
| 0x6fd      | 6         | 1.26%   |
| 0x20655    | 6         | 1.26%   |
| 0x906e9    | 5         | 1.05%   |
| 0x806c1    | 5         | 1.05%   |
| 0x706e5    | 5         | 1.05%   |
| 0x06003106 | 5         | 1.05%   |
| 0x06000852 | 5         | 1.05%   |
| 0x010000c8 | 5         | 1.05%   |
| 0xa0652    | 4         | 0.84%   |
| 0x406c4    | 4         | 0.84%   |
| 0x08600106 | 4         | 0.84%   |
| 0x0810100b | 4         | 0.84%   |
| 0x07030105 | 4         | 0.84%   |
| 0x806eb    | 3         | 0.63%   |
| 0x6fb      | 3         | 0.63%   |
| 0x30678    | 3         | 0.63%   |
| 0x20652    | 3         | 0.63%   |
| 0x10676    | 3         | 0.63%   |
| 0x10661    | 3         | 0.63%   |
| 0x08608103 | 3         | 0.63%   |
| 0x06001119 | 3         | 0.63%   |
| 0xf64      | 2         | 0.42%   |
| 0xa0655    | 2         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 76        | 16.56%  |
| IvyBridge        | 36        | 7.84%   |
| Haswell          | 36        | 7.84%   |
| SandyBridge      | 28        | 6.1%    |
| Skylake          | 27        | 5.88%   |
| Zen+             | 26        | 5.66%   |
| Zen 2            | 22        | 4.79%   |
| Penryn           | 17        | 3.7%    |
| Unknown          | 17        | 3.7%    |
| Zen 3            | 16        | 3.49%   |
| Core             | 14        | 3.05%   |
| Silvermont       | 13        | 2.83%   |
| Westmere         | 12        | 2.61%   |
| Piledriver       | 12        | 2.61%   |
| Broadwell        | 12        | 2.61%   |
| IceLake          | 11        | 2.4%    |
| CometLake        | 10        | 2.18%   |
| Zen              | 9         | 1.96%   |
| K10              | 9         | 1.96%   |
| TigerLake        | 7         | 1.53%   |
| Steamroller      | 7         | 1.53%   |
| Goldmont plus    | 7         | 1.53%   |
| Excavator        | 6         | 1.31%   |
| Alderlake Hybrid | 6         | 1.31%   |
| Puma             | 5         | 1.09%   |
| NetBurst         | 3         | 0.65%   |
| Jaguar           | 3         | 0.65%   |
| Bobcat           | 3         | 0.65%   |
| P6               | 2         | 0.44%   |
| Nehalem          | 2         | 0.44%   |
| Bonnell          | 2         | 0.44%   |
| K8 Hammer        | 1         | 0.22%   |
| K10 Llano        | 1         | 0.22%   |
| Bulldozer        | 1         | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 272       | 48.92%  |
| AMD                              | 149       | 26.8%   |
| Nvidia                           | 133       | 23.92%  |
| Silicon Integrated Systems [SiS] | 1         | 0.18%   |
| Matrox Electronics Systems       | 1         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 24        | 4.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 22        | 3.83%   |
| Intel UHD Graphics 620                                                                   | 20        | 3.48%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 3.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 17        | 2.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 2.09%   |
| Intel HD Graphics 620                                                                    | 12        | 2.09%   |
| Intel HD Graphics 5500                                                                   | 11        | 1.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 1.92%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 11        | 1.92%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 10        | 1.74%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 10        | 1.74%   |
| Intel HD Graphics 530                                                                    | 9         | 1.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 1.39%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 8         | 1.39%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 1.39%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 1.22%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 1.22%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 1.22%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7         | 1.22%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 1.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.05%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.87%   |
| Nvidia GT218 [GeForce 210]                                                               | 5         | 0.87%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 0.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 0.87%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 0.87%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 0.87%   |
| Intel HD Graphics 630                                                                    | 5         | 0.87%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 0.87%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 4         | 0.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 0.7%    |
| Nvidia GM108M [GeForce MX110]                                                            | 4         | 0.7%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.7%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.7%    |
| Nvidia GF108 [GeForce GT 730]                                                            | 4         | 0.7%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 4         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 183       | 39.87%  |
| 1 x AMD        | 103       | 22.44%  |
| 1 x Nvidia     | 61        | 13.29%  |
| Intel + Nvidia | 59        | 12.85%  |
| Intel + AMD    | 23        | 5.01%   |
| AMD + Nvidia   | 13        | 2.83%   |
| 2 x AMD        | 10        | 2.18%   |
| 2 x Intel      | 3         | 0.65%   |
| Other          | 2         | 0.44%   |
| 1 x SiS        | 1         | 0.22%   |
| 1 x Matrox     | 1         | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 383       | 82.54%  |
| Proprietary | 69        | 14.87%  |
| Unknown     | 12        | 2.59%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 249       | 52.75%  |
| 1.01-2.0   | 78        | 16.53%  |
| 0.01-0.5   | 55        | 11.65%  |
| 3.01-4.0   | 29        | 6.14%   |
| 0.51-1.0   | 29        | 6.14%   |
| 7.01-8.0   | 17        | 3.6%    |
| 5.01-6.0   | 11        | 2.33%   |
| 8.01-16.0  | 3         | 0.64%   |
| 2.01-3.0   | 1         | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 87        | 17.61%  |
| Chimei Innolux       | 72        | 14.57%  |
| Goldstar             | 53        | 10.73%  |
| BOE                  | 53        | 10.73%  |
| AU Optronics         | 49        | 9.92%   |
| LG Display           | 39        | 7.89%   |
| Hewlett-Packard      | 21        | 4.25%   |
| AOC                  | 15        | 3.04%   |
| Dell                 | 10        | 2.02%   |
| ViewSonic            | 8         | 1.62%   |
| PANDA                | 7         | 1.42%   |
| Lenovo               | 7         | 1.42%   |
| BenQ                 | 6         | 1.21%   |
| Sony                 | 5         | 1.01%   |
| ASUSTek Computer     | 5         | 1.01%   |
| Unknown              | 4         | 0.81%   |
| Apple                | 4         | 0.81%   |
| Sharp                | 3         | 0.61%   |
| JRY                  | 3         | 0.61%   |
| TMX                  | 2         | 0.4%    |
| Panasonic            | 2         | 0.4%    |
| LG Philips           | 2         | 0.4%    |
| LG Electronics       | 2         | 0.4%    |
| Lenovo Group Limited | 2         | 0.4%    |
| HannStar             | 2         | 0.4%    |
| Ancor Communications | 2         | 0.4%    |
| AGO                  | 2         | 0.4%    |
| Unknown              | 2         | 0.4%    |
| Yuraku               | 1         | 0.2%    |
| Viotek               | 1         | 0.2%    |
| Unknown (XXX)        | 1         | 0.2%    |
| TopView              | 1         | 0.2%    |
| Sceptre Tech         | 1         | 0.2%    |
| NEW                  | 1         | 0.2%    |
| MStar                | 1         | 0.2%    |
| MSI                  | 1         | 0.2%    |
| MSD                  | 1         | 0.2%    |
| Mi                   | 1         | 0.2%    |
| LGD                  | 1         | 0.2%    |
| InnoLux Display      | 1         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 12        | 2.39%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch        | 10        | 1.99%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 9         | 1.79%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 5         | 0.99%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch       | 5         | 0.99%   |
| Samsung Electronics SA300/SA350 SAM078D 1600x900 443x249mm 20.0-inch   | 4         | 0.8%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 4         | 0.8%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 4         | 0.8%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch          | 4         | 0.8%    |
| JRY DX238A1 JRY2380 1920x1080 368x207mm 16.6-inch                      | 3         | 0.6%    |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                   | 3         | 0.6%    |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                    | 3         | 0.6%    |
| Goldstar E1951 GSM4BFD 1366x768 410x230mm 18.5-inch                    | 3         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch        | 3         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 3         | 0.6%    |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch        | 3         | 0.6%    |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                   | 3         | 0.6%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                   | 3         | 0.6%    |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                      | 3         | 0.6%    |
| AU Optronics LCD Monitor AUO459D 1920x1200 344x215mm 16.0-inch         | 3         | 0.6%    |
| ViewSonic VA2246 SERIES VSC6F2E 1920x1080 480x270mm 21.7-inch          | 2         | 0.4%    |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 2         | 0.4%    |
| Samsung Electronics SyncMaster SAM0272 1280x1024 338x270mm 17.0-inch   | 2         | 0.4%    |
| Samsung Electronics SA300/SA350 SAM078A 1366x768 410x230mm 18.5-inch   | 2         | 0.4%    |
| Samsung Electronics S20B300 SAM08A7 1600x900 443x249mm 20.0-inch       | 2         | 0.4%    |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch       | 2         | 0.4%    |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch   | 2         | 0.4%    |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch   | 2         | 0.4%    |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch   | 2         | 0.4%    |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch   | 2         | 0.4%    |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch   | 2         | 0.4%    |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch | 2         | 0.4%    |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 480x270mm 21.7-inch  | 2         | 0.4%    |
| Samsung Electronics LCD Monitor SAM07D0 1360x768 700x390mm 31.5-inch   | 2         | 0.4%    |
| Samsung Electronics LCD Monitor SAM04FD 1280x720                       | 2         | 0.4%    |
| Samsung Electronics C27F591 SAM0D36 1920x1080 598x336mm 27.0-inch      | 2         | 0.4%    |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                | 2         | 0.4%    |
| LG Display LCD Monitor LGD062F 1920x1080 344x194mm 15.5-inch           | 2         | 0.4%    |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch           | 2         | 0.4%    |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch            | 2         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 181       | 37.71%  |
| 1366x768 (WXGA)   | 165       | 34.38%  |
| 1600x900 (HD+)    | 30        | 6.25%   |
| 3840x2160 (4K)    | 15        | 3.13%   |
| 1360x768          | 15        | 3.13%   |
| 2560x1440 (QHD)   | 10        | 2.08%   |
| 1440x900 (WXGA+)  | 10        | 2.08%   |
| 1280x800 (WXGA)   | 9         | 1.88%   |
| 1920x1200 (WUXGA) | 6         | 1.25%   |
| 2160x1440         | 5         | 1.04%   |
| 1280x1024 (SXGA)  | 5         | 1.04%   |
| 1024x768 (XGA)    | 5         | 1.04%   |
| 2560x1600         | 4         | 0.83%   |
| Unknown           | 4         | 0.83%   |
| 3840x1080         | 3         | 0.63%   |
| 3200x1800 (QHD+)  | 2         | 0.42%   |
| 2560x1080         | 2         | 0.42%   |
| 1024x600          | 2         | 0.42%   |
| 640x480           | 1         | 0.21%   |
| 3440x1440         | 1         | 0.21%   |
| 3200x2000         | 1         | 0.21%   |
| 2880x1800         | 1         | 0.21%   |
| 2736x1824         | 1         | 0.21%   |
| 2520x1680         | 1         | 0.21%   |
| 1280x720 (HD)     | 1         | 0.21%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 152       | 30.96%  |
| 13      | 56        | 11.41%  |
| 21      | 51        | 10.39%  |
| 14      | 41        | 8.35%   |
| 23      | 36        | 7.33%   |
| 18      | 22        | 4.48%   |
| 20      | 17        | 3.46%   |
| Unknown | 16        | 3.26%   |
| 27      | 15        | 3.05%   |
| 17      | 15        | 3.05%   |
| 24      | 12        | 2.44%   |
| 19      | 10        | 2.04%   |
| 31      | 7         | 1.43%   |
| 16      | 6         | 1.22%   |
| 11      | 6         | 1.22%   |
| 12      | 5         | 1.02%   |
| 48      | 4         | 0.81%   |
| 32      | 3         | 0.61%   |
| 84      | 2         | 0.41%   |
| 72      | 2         | 0.41%   |
| 34      | 2         | 0.41%   |
| 30      | 2         | 0.41%   |
| 10      | 2         | 0.41%   |
| 60      | 1         | 0.2%    |
| 54      | 1         | 0.2%    |
| 52      | 1         | 0.2%    |
| 46      | 1         | 0.2%    |
| 43      | 1         | 0.2%    |
| 39      | 1         | 0.2%    |
| 22      | 1         | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 240       | 49.59%  |
| 401-500     | 96        | 19.83%  |
| 501-600     | 62        | 12.81%  |
| 201-300     | 28        | 5.79%   |
| Unknown     | 16        | 3.31%   |
| 351-400     | 14        | 2.89%   |
| 601-700     | 9         | 1.86%   |
| 1001-1500   | 8         | 1.65%   |
| 701-800     | 5         | 1.03%   |
| 1501-2000   | 4         | 0.83%   |
| 801-900     | 1         | 0.21%   |
| 901-1000    | 1         | 0.21%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 369       | 83.48%  |
| 16/10   | 34        | 7.69%   |
| Unknown | 15        | 3.39%   |
| 4/3     | 8         | 1.81%   |
| 5/4     | 7         | 1.58%   |
| 3/2     | 7         | 1.58%   |
| 21/9    | 2         | 0.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 152       | 31.21%  |
| 81-90          | 83        | 17.04%  |
| 201-250        | 83        | 17.04%  |
| 151-200        | 40        | 8.21%   |
| 141-150        | 25        | 5.13%   |
| Unknown        | 16        | 3.29%   |
| 301-350        | 15        | 3.08%   |
| 71-80          | 14        | 2.87%   |
| 351-500        | 14        | 2.87%   |
| More than 1000 | 11        | 2.26%   |
| 121-130        | 7         | 1.44%   |
| 51-60          | 6         | 1.23%   |
| 111-120        | 6         | 1.23%   |
| 131-140        | 4         | 0.82%   |
| 501-1000       | 3         | 0.62%   |
| 61-70          | 2         | 0.41%   |
| 41-50          | 2         | 0.41%   |
| 251-300        | 2         | 0.41%   |
| 91-100         | 2         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 202       | 42.26%  |
| 51-100        | 128       | 26.78%  |
| 121-160       | 96        | 20.08%  |
| 1-50          | 16        | 3.35%   |
| Unknown       | 16        | 3.35%   |
| 161-240       | 15        | 3.14%   |
| More than 240 | 5         | 1.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 384       | 81.7%   |
| 2     | 67        | 14.26%  |
| 0     | 14        | 2.98%   |
| 3     | 5         | 1.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 287       | 43.22%  |
| Intel                            | 167       | 25.15%  |
| Qualcomm Atheros                 | 91        | 13.7%   |
| Broadcom                         | 23        | 3.46%   |
| TP-Link                          | 18        | 2.71%   |
| MediaTek                         | 11        | 1.66%   |
| Xiaomi                           | 7         | 1.05%   |
| Ralink Technology                | 7         | 1.05%   |
| Ralink                           | 7         | 1.05%   |
| Nvidia                           | 5         | 0.75%   |
| Marvell Technology Group         | 5         | 0.75%   |
| Qualcomm Atheros Communications  | 4         | 0.6%    |
| Broadcom Limited                 | 4         | 0.6%    |
| ASIX Electronics                 | 4         | 0.6%    |
| Motorola PCS                     | 3         | 0.45%   |
| Microsoft                        | 3         | 0.45%   |
| ICS Advent                       | 3         | 0.45%   |
| Samsung Electronics              | 2         | 0.3%    |
| Huawei Technologies              | 2         | 0.3%    |
| D-Link System                    | 2         | 0.3%    |
| ZTE WCDMA Technologies MSM       | 1         | 0.15%   |
| T & A Mobile Phones              | 1         | 0.15%   |
| Silicon Integrated Systems [SiS] | 1         | 0.15%   |
| Qualcomm                         | 1         | 0.15%   |
| OPPO Electronics                 | 1         | 0.15%   |
| Lenovo                           | 1         | 0.15%   |
| DisplayLink                      | 1         | 0.15%   |
| D-Link                           | 1         | 0.15%   |
| Apple                            | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 195       | 24.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 42        | 5.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 30        | 3.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 2.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 19        | 2.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 13        | 1.66%   |
| Realtek RTL8125 2.5GbE Controller                                       | 12        | 1.53%   |
| Intel Wi-Fi 6 AX200                                                     | 12        | 1.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 10        | 1.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 10        | 1.27%   |
| Intel Wireless 8265 / 8275                                              | 9         | 1.15%   |
| Intel Wireless 8260                                                     | 9         | 1.15%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 1.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 1.02%   |
| Intel Wireless 7265                                                     | 8         | 1.02%   |
| Intel Ethernet Connection (2) I219-V                                    | 8         | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 1.02%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 7         | 0.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 7         | 0.89%   |
| Intel I211 Gigabit Network Connection                                   | 7         | 0.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 0.89%   |
| Intel 82579V Gigabit Network Connection                                 | 7         | 0.89%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 6         | 0.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 6         | 0.76%   |
| Intel Wireless 7260                                                     | 6         | 0.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 0.76%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 5         | 0.64%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 0.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 0.64%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 5         | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                                   | 5         | 0.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 4         | 0.51%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 0.51%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 119       | 33.24%  |
| Realtek Semiconductor           | 88        | 24.58%  |
| Qualcomm Atheros                | 79        | 22.07%  |
| Broadcom                        | 21        | 5.87%   |
| TP-Link                         | 16        | 4.47%   |
| MediaTek                        | 11        | 3.07%   |
| Ralink Technology               | 7         | 1.96%   |
| Ralink                          | 7         | 1.96%   |
| Qualcomm Atheros Communications | 4         | 1.12%   |
| Microsoft                       | 2         | 0.56%   |
| Marvell Technology Group        | 1         | 0.28%   |
| D-Link System                   | 1         | 0.28%   |
| D-Link                          | 1         | 0.28%   |
| Broadcom Limited                | 1         | 0.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 30        | 8.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 5.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 19        | 5.31%   |
| Intel Wi-Fi 6 AX200                                                     | 12        | 3.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 3.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 10        | 2.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 2.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 10        | 2.79%   |
| Intel Wireless 8265 / 8275                                              | 9         | 2.51%   |
| Intel Wireless 8260                                                     | 9         | 2.51%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 2.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 2.23%   |
| Intel Wireless 7265                                                     | 8         | 2.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 2.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.96%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 6         | 1.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 1.68%   |
| Intel Wireless 7260                                                     | 6         | 1.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 1.68%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 5         | 1.4%    |
| Ralink MT7601U Wireless Adapter                                         | 5         | 1.4%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.4%    |
| Intel Gemini Lake PCH CNVi WiFi                                         | 5         | 1.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.12%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 1.12%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 1.12%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.12%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.12%   |
| TP-Link 802.11n NIC                                                     | 3         | 0.84%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.84%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 3         | 0.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.84%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.84%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 3         | 0.84%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.84%   |
| Intel WiFi Link 5100                                                    | 3         | 0.84%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.84%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.84%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 3         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 259       | 61.67%  |
| Intel                            | 90        | 21.43%  |
| Qualcomm Atheros                 | 23        | 5.48%   |
| Xiaomi                           | 7         | 1.67%   |
| Nvidia                           | 5         | 1.19%   |
| Marvell Technology Group         | 4         | 0.95%   |
| Broadcom                         | 4         | 0.95%   |
| ASIX Electronics                 | 4         | 0.95%   |
| ICS Advent                       | 3         | 0.71%   |
| Broadcom Limited                 | 3         | 0.71%   |
| TP-Link                          | 2         | 0.48%   |
| Samsung Electronics              | 2         | 0.48%   |
| Motorola PCS                     | 2         | 0.48%   |
| Huawei Technologies              | 2         | 0.48%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.24%   |
| T & A Mobile Phones              | 1         | 0.24%   |
| Silicon Integrated Systems [SiS] | 1         | 0.24%   |
| Qualcomm                         | 1         | 0.24%   |
| OPPO Electronics                 | 1         | 0.24%   |
| Microsoft                        | 1         | 0.24%   |
| Lenovo                           | 1         | 0.24%   |
| DisplayLink                      | 1         | 0.24%   |
| D-Link System                    | 1         | 0.24%   |
| Apple                            | 1         | 0.24%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 195       | 45.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 42        | 9.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13        | 3.05%   |
| Realtek RTL8125 2.5GbE Controller                                      | 12        | 2.82%   |
| Intel Ethernet Connection (2) I219-V                                   | 8         | 1.88%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 7         | 1.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 7         | 1.64%   |
| Intel I211 Gigabit Network Connection                                  | 7         | 1.64%   |
| Intel 82579V Gigabit Network Connection                                | 7         | 1.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 1.41%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 1.17%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4         | 0.94%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 4         | 0.94%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 0.7%    |
| Nvidia MCP61 Ethernet                                                  | 3         | 0.7%    |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 0.7%    |
| Intel Ethernet Connection (12) I219-V                                  | 3         | 0.7%    |
| Intel Ethernet Connection (10) I219-V                                  | 3         | 0.7%    |
| Intel 82578DC Gigabit Network Connection                               | 3         | 0.7%    |
| ICS Advent DM9601 Fast Ethernet Adapter                                | 3         | 0.7%    |
| TP-Link USB 10/100 LAN                                                 | 2         | 0.47%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 2         | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.47%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 0.47%   |
| Motorola PCS moto g52                                                  | 2         | 0.47%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 0.47%   |
| Intel Ethernet Connection I219-V                                       | 2         | 0.47%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.47%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.47%   |
| Intel Ethernet Connection I217-V                                       | 2         | 0.47%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.47%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.47%   |
| Intel Ethernet Connection (5) I219-LM                                  | 2         | 0.47%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.47%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 0.47%   |
| Intel 82567V-4 Gigabit Network Connection                              | 2         | 0.47%   |
| Huawei STG-LX1                                                         | 2         | 0.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 0.47%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 400       | 53.55%  |
| WiFi     | 346       | 46.32%  |
| Unknown  | 1         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 262       | 54.93%  |
| Ethernet | 215       | 45.07%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 247       | 53.81%  |
| 1     | 197       | 42.92%  |
| 0     | 9         | 1.96%   |
| 3     | 5         | 1.09%   |
| 4     | 1         | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 369       | 79.01%  |
| Yes  | 98        | 20.99%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 99        | 34.74%  |
| Realtek Semiconductor           | 55        | 19.3%   |
| Qualcomm Atheros Communications | 39        | 13.68%  |
| IMC Networks                    | 21        | 7.37%   |
| Cambridge Silicon Radio         | 15        | 5.26%   |
| Lite-On Technology              | 12        | 4.21%   |
| Toshiba                         | 8         | 2.81%   |
| Broadcom                        | 7         | 2.46%   |
| Ralink                          | 6         | 2.11%   |
| Foxconn / Hon Hai               | 5         | 1.75%   |
| Apple                           | 4         | 1.4%    |
| TP-Link                         | 3         | 1.05%   |
| Hewlett-Packard                 | 3         | 1.05%   |
| Dell                            | 2         | 0.7%    |
| TRENDnet                        | 1         | 0.35%   |
| Realtek                         | 1         | 0.35%   |
| MediaTek                        | 1         | 0.35%   |
| Integrated System Solution      | 1         | 0.35%   |
| Foxconn International           | 1         | 0.35%   |
| Alps Electric                   | 1         | 0.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 34        | 11.93%  |
| Realtek Bluetooth Radio                             | 27        | 9.47%   |
| Realtek  Bluetooth 4.2 Adapter                      | 26        | 9.12%   |
| Qualcomm Atheros  Bluetooth Device                  | 23        | 8.07%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 22        | 7.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 15        | 5.26%   |
| Intel AX201 Bluetooth                               | 13        | 4.56%   |
| Intel AX200 Bluetooth                               | 12        | 4.21%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 2.81%   |
| Intel Bluetooth Device                              | 8         | 2.81%   |
| IMC Networks Wireless_Device                        | 8         | 2.81%   |
| IMC Networks Bluetooth Radio                        | 7         | 2.46%   |
| Ralink RT3290 Bluetooth                             | 6         | 2.11%   |
| Toshiba Bluetooth Device                            | 5         | 1.75%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.4%    |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.4%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.4%    |
| IMC Networks Bluetooth Device                       | 4         | 1.4%    |
| TP-Link UB500 Adapter                               | 3         | 1.05%   |
| Lite-On Bluetooth Radio                             | 3         | 1.05%   |
| Lite-On Bluetooth Device                            | 3         | 1.05%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.05%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.7%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 0.7%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.7%    |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.7%    |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.7%    |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.7%    |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.7%    |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 0.7%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.7%    |
| Apple Bluetooth USB Host Controller                 | 2         | 0.7%    |
| Apple Bluetooth Host Controller                     | 2         | 0.7%    |
| TRENDnet TBW-108UB USB Adapter                      | 1         | 0.35%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.35%   |
| Toshiba BCM43142A0                                  | 1         | 0.35%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.35%   |
| Realtek Bluetooth Radio                             | 1         | 0.35%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 313       | 52.34%  |
| AMD                              | 150       | 25.08%  |
| Nvidia                           | 98        | 16.39%  |
| C-Media Electronics              | 8         | 1.34%   |
| Logitech                         | 3         | 0.5%    |
| Kingston Technology              | 3         | 0.5%    |
| Generalplus Technology           | 3         | 0.5%    |
| Texas Instruments                | 2         | 0.33%   |
| Sony                             | 2         | 0.33%   |
| Microsoft                        | 2         | 0.33%   |
| GN Netcom                        | 2         | 0.33%   |
| BEHRINGER International          | 2         | 0.33%   |
| Tenx Technology                  | 1         | 0.17%   |
| Silicon Integrated Systems [SiS] | 1         | 0.17%   |
| Samson Technologies              | 1         | 0.17%   |
| Razer USA                        | 1         | 0.17%   |
| Pixart Imaging                   | 1         | 0.17%   |
| Panasonic (Matsushita)           | 1         | 0.17%   |
| Micro Star International         | 1         | 0.17%   |
| Hewlett-Packard                  | 1         | 0.17%   |
| Creative Labs                    | 1         | 0.17%   |
| Chicony Electronics              | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 60        | 8.11%   |
| Intel Sunrise Point-LP HD Audio                                            | 46        | 6.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 35        | 4.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 29        | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 25        | 3.38%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 23        | 3.11%   |
| AMD FCH Azalia Controller                                                  | 23        | 3.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17        | 2.3%    |
| Intel 8 Series HD Audio Controller                                         | 17        | 2.3%    |
| AMD Starship/Matisse HD Audio Controller                                   | 17        | 2.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 16        | 2.16%   |
| Intel Haswell-ULT HD Audio Controller                                      | 16        | 2.16%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 16        | 2.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 15        | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13        | 1.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 13        | 1.76%   |
| Nvidia GF108 High Definition Audio Controller                              | 12        | 1.62%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12        | 1.62%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 11        | 1.49%   |
| Intel Comet Lake PCH-LP cAVS                                               | 11        | 1.49%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 1.49%   |
| Intel Broadwell-U Audio Controller                                         | 11        | 1.49%   |
| AMD Kabini HDMI/DP Audio                                                   | 10        | 1.35%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 1.22%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 9         | 1.22%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 8         | 1.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8         | 1.08%   |
| Intel 200 Series PCH HD Audio                                              | 8         | 1.08%   |
| AMD Navi 10 HDMI Audio                                                     | 8         | 1.08%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7         | 0.95%   |
| Nvidia Audio device                                                        | 7         | 0.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 0.95%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 7         | 0.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 7         | 0.95%   |
| Nvidia TU106 High Definition Audio Controller                              | 6         | 0.81%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 0.81%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 0.81%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 0.68%   |
| Nvidia High Definition Audio Controller                                    | 5         | 0.68%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 78        | 24.38%  |
| Kingston                     | 72        | 22.5%   |
| SK hynix                     | 50        | 15.63%  |
| Micron Technology            | 36        | 11.25%  |
| Unknown                      | 19        | 5.94%   |
| Ramaxel Technology           | 11        | 3.44%   |
| Corsair                      | 9         | 2.81%   |
| Crucial                      | 8         | 2.5%    |
| Team                         | 7         | 2.19%   |
| Unknown (ABCD)               | 6         | 1.88%   |
| Hewlett-Packard              | 4         | 1.25%   |
| Elpida                       | 3         | 0.94%   |
| A-DATA Technology            | 3         | 0.94%   |
| Patriot                      | 2         | 0.63%   |
| Unknown (0x7FA8000000000000) | 1         | 0.31%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1         | 0.31%   |
| S                            | 1         | 0.31%   |
| Qumo                         | 1         | 0.31%   |
| Princeton                    | 1         | 0.31%   |
| Nanya Technology             | 1         | 0.31%   |
| M                            | 1         | 0.31%   |
| Kllisre                      | 1         | 0.31%   |
| Goldkey                      | 1         | 0.31%   |
| GeIL                         | 1         | 0.31%   |
| CSX                          | 1         | 0.31%   |
| Unknown                      | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 6         | 1.7%    |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 6         | 1.7%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                   | 6         | 1.7%    |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 5         | 1.42%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 5         | 1.42%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 5         | 1.42%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s                | 4         | 1.14%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 1.14%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 4         | 1.14%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 4         | 1.14%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s                 | 4         | 1.14%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.85%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 3         | 0.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 0.85%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 3         | 0.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.85%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 3         | 0.85%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 0.85%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 3         | 0.85%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 3         | 0.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 0.85%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 3         | 0.85%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 3         | 0.85%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s                 | 3         | 0.85%   |
| Kingston RAM 99U5428-046.A00LF 4GB SODIMM DDR3 1600MT/s             | 3         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 2         | 0.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.57%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.57%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                | 2         | 0.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.57%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 2         | 0.57%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 2         | 0.57%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.57%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 2         | 0.57%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 2         | 0.57%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 2         | 0.57%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 0.57%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 0.57%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.57%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 2         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 120       | 46.88%  |
| DDR3    | 94        | 36.72%  |
| LPDDR4  | 13        | 5.08%   |
| DDR2    | 10        | 3.91%   |
| LPDDR3  | 5         | 1.95%   |
| SDRAM   | 4         | 1.56%   |
| DDR5    | 4         | 1.56%   |
| Unknown | 4         | 1.56%   |
| LPDDR5  | 2         | 0.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 159       | 62.35%  |
| DIMM         | 85        | 33.33%  |
| Row Of Chips | 10        | 3.92%   |
| Unknown      | 1         | 0.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 122       | 40.94%  |
| 4096  | 92        | 30.87%  |
| 16384 | 35        | 11.74%  |
| 2048  | 30        | 10.07%  |
| 32768 | 9         | 3.02%   |
| 1024  | 7         | 2.35%   |
| 512   | 3         | 1.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 61        | 20.61%  |
| 2667    | 52        | 17.57%  |
| 3200    | 48        | 16.22%  |
| 1333    | 22        | 7.43%   |
| 2400    | 21        | 7.09%   |
| 2133    | 16        | 5.41%   |
| 3466    | 8         | 2.7%    |
| 3266    | 6         | 2.03%   |
| 1334    | 6         | 2.03%   |
| Unknown | 6         | 2.03%   |
| 3733    | 4         | 1.35%   |
| 1867    | 4         | 1.35%   |
| 4800    | 3         | 1.01%   |
| 1067    | 3         | 1.01%   |
| 800     | 3         | 1.01%   |
| 533     | 3         | 1.01%   |
| 3800    | 2         | 0.68%   |
| 3534    | 2         | 0.68%   |
| 3400    | 2         | 0.68%   |
| 3000    | 2         | 0.68%   |
| 1800    | 2         | 0.68%   |
| 1066    | 2         | 0.68%   |
| 667     | 2         | 0.68%   |
| 6400    | 1         | 0.34%   |
| 5500    | 1         | 0.34%   |
| 5200    | 1         | 0.34%   |
| 4267    | 1         | 0.34%   |
| 4199    | 1         | 0.34%   |
| 3600    | 1         | 0.34%   |
| 3151    | 1         | 0.34%   |
| 3100    | 1         | 0.34%   |
| 3066    | 1         | 0.34%   |
| 2933    | 1         | 0.34%   |
| 2733    | 1         | 0.34%   |
| 2666    | 1         | 0.34%   |
| 2200    | 1         | 0.34%   |
| 2134    | 1         | 0.34%   |
| 1866    | 1         | 0.34%   |
| 400     | 1         | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Hewlett-Packard               | 3         | 20%     |
| Canon                         | 3         | 20%     |
| Brother Industries            | 3         | 20%     |
| Seiko Epson                   | 2         | 13.33%  |
| Samsung Info. Systems America | 2         | 13.33%  |
| Star Micronics                | 1         | 6.67%   |
| Prolific Technology           | 1         | 6.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Samsung Info. Systems America SAMSUNG SRP-270 | 2         | 13.33%  |
| Brother DCP-T310                              | 2         | 13.33%  |
| Star Micronics TUP592 (STR_T-001)             | 1         | 6.67%   |
| Seiko Epson L3250 Series                      | 1         | 6.67%   |
| Seiko Epson L3150 Series                      | 1         | 6.67%   |
| Prolific PL2305 Parallel Port                 | 1         | 6.67%   |
| HP PSC 1400                                   | 1         | 6.67%   |
| HP LaserJet Professional P 1102w              | 1         | 6.67%   |
| HP DeskJet 2700 series                        | 1         | 6.67%   |
| Canon PIXMA MG3600 Series                     | 1         | 6.67%   |
| Canon G2010 series                            | 1         | 6.67%   |
| Canon E400 series                             | 1         | 6.67%   |
| Brother DCP-T300                              | 1         | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 66.67%  |
| Hewlett-Packard | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 2         | 66.67%  |
| HP ScanJet 2400c       | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 61        | 19.55%  |
| Microdia                               | 29        | 9.29%   |
| IMC Networks                           | 29        | 9.29%   |
| Realtek Semiconductor                  | 23        | 7.37%   |
| Bison Electronics                      | 19        | 6.09%   |
| Syntek                                 | 18        | 5.77%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 5.13%   |
| Quanta                                 | 14        | 4.49%   |
| Sunplus Innovation Technology          | 13        | 4.17%   |
| Suyin                                  | 12        | 3.85%   |
| Lite-On Technology                     | 12        | 3.85%   |
| Logitech                               | 9         | 2.88%   |
| Generalplus Technology                 | 7         | 2.24%   |
| Microsoft                              | 5         | 1.6%    |
| Apple                                  | 5         | 1.6%    |
| Acer                                   | 5         | 1.6%    |
| Z-Star Microelectronics                | 4         | 1.28%   |
| Sonix Technology                       | 4         | 1.28%   |
| Luxvisions Innotech Limited            | 4         | 1.28%   |
| Importek                               | 4         | 1.28%   |
| Samsung Electronics                    | 3         | 0.96%   |
| ShineTech                              | 2         | 0.64%   |
| Ricoh                                  | 2         | 0.64%   |
| Jieli Technology                       | 2         | 0.64%   |
| Cubeternet                             | 2         | 0.64%   |
| Alcor Micro                            | 2         | 0.64%   |
| Xiongmai                               | 1         | 0.32%   |
| Silicon Motion                         | 1         | 0.32%   |
| Aveo Technology                        | 1         | 0.32%   |
| ASUSTek Computer                       | 1         | 0.32%   |
| ANYKA                                  | 1         | 0.32%   |
| 8SSC20F27114V1SR0BK1X4S                | 1         | 0.32%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                                   | 12        | 3.82%   |
| Bison Integrated Camera                                                    | 9         | 2.87%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 8         | 2.55%   |
| Chicony Integrated Camera                                                  | 7         | 2.23%   |
| Microdia Webcam Vitade AF                                                  | 6         | 1.91%   |
| Chicony HP Truevision HD                                                   | 6         | 1.91%   |
| Chicony EasyCamera                                                         | 6         | 1.91%   |
| Realtek Integrated_Webcam_HD                                               | 5         | 1.59%   |
| Microdia Integrated_Webcam_HD                                              | 5         | 1.59%   |
| Lite-On Integrated Camera                                                  | 5         | 1.59%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 5         | 1.59%   |
| IMC Networks Integrated Camera                                             | 5         | 1.59%   |
| IMC Networks HP TrueVision HD Camera                                       | 5         | 1.59%   |
| Generalplus GENERAL WEBCAM                                                 | 5         | 1.59%   |
| Sunplus Integrated_Webcam_HD                                               | 4         | 1.27%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 4         | 1.27%   |
| Chicony USB2.0 HD UVC WebCam                                               | 4         | 1.27%   |
| Chicony TOSHIBA Web Camera - HD                                            | 4         | 1.27%   |
| Chicony HP TrueVision HD Camera                                            | 4         | 1.27%   |
| Chicony HD WebCam                                                          | 4         | 1.27%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 3         | 0.96%   |
| Realtek USB Camera                                                         | 3         | 0.96%   |
| Microdia USB 2.0 Camera                                                    | 3         | 0.96%   |
| Lite-On HP HD Camera                                                       | 3         | 0.96%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 0.96%   |
| Chicony HP Wide Vision HD Camera                                           | 3         | 0.96%   |
| Chicony HP HD Webcam                                                       | 3         | 0.96%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 3         | 0.96%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 0.96%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 3         | 0.96%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 3         | 0.96%   |
| Suyin 1.3M HD WebCam                                                       | 2         | 0.64%   |
| Sunplus Integrated Webcam                                                  | 2         | 0.64%   |
| ShineTech USB2.0 HD UVC WebCam                                             | 2         | 0.64%   |
| Ricoh Sony Vaio Integrated Webcam                                          | 2         | 0.64%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 2         | 0.64%   |
| Realtek Integrated Webcam                                                  | 2         | 0.64%   |
| Realtek HP Wide Vision HD Camera                                           | 2         | 0.64%   |
| Quanta HP Wide Vision HD Camera                                            | 2         | 0.64%   |
| Quanta HP Webcam                                                           | 2         | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 24        | 47.06%  |
| Synaptics                  | 14        | 27.45%  |
| Shenzhen Goodix Technology | 6         | 11.76%  |
| Elan Microelectronics      | 4         | 7.84%   |
| AuthenTec                  | 2         | 3.92%   |
| STMicroelectronics         | 1         | 1.96%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 8         | 15.69%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 7         | 13.73%  |
| Synaptics  WBDI                                           | 4         | 7.84%   |
| Shenzhen Goodix  FingerPrint Device                       | 3         | 5.88%   |
| Shenzhen Goodix Fingerprint Reader                        | 3         | 5.88%   |
| Elan ELAN:Fingerprint                                     | 3         | 5.88%   |
| Validity Sensors Synaptics WBDI                           | 2         | 3.92%   |
| Validity Sensors Fingerprint scanner                      | 2         | 3.92%   |
| Synaptics WBDI Fingerprint Reader USB 086                 | 2         | 3.92%   |
| Synaptics WBDI                                            | 2         | 3.92%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 3.92%   |
| AuthenTec AES1660 Fingerprint Sensor                      | 2         | 3.92%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 1         | 1.96%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 1.96%   |
| Validity Sensors VFS451 Fingerprint Reader                | 1         | 1.96%   |
| Validity Sensors VFS301 Fingerprint Reader                | 1         | 1.96%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 1.96%   |
| Synaptics UWP WBDI Device                                 | 1         | 1.96%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 1.96%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 1.96%   |
| Synaptics Fingerprint reader [HP G6]                      | 1         | 1.96%   |
| STMicroelectronics Fingerprint Reader                     | 1         | 1.96%   |
| Elan ELAN:ARM-M4                                          | 1         | 1.96%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 7         | 41.18%  |
| Alcor Micro | 5         | 29.41%  |
| Upek        | 3         | 17.65%  |
| Yubico.com  | 1         | 5.88%   |
| O2 Micro    | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 29.41%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 17.65%  |
| Broadcom 5880                                                                | 3         | 17.65%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 11.76%  |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 5.88%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.88%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 5.88%   |
| Broadcom 58200                                                               | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 332       | 70.79%  |
| 1     | 109       | 23.24%  |
| 2     | 22        | 4.69%   |
| 3     | 5         | 1.07%   |
| 5     | 1         | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 51        | 31.29%  |
| Graphics card            | 40        | 24.54%  |
| Net/wireless             | 23        | 14.11%  |
| Chipcard                 | 14        | 8.59%   |
| Bluetooth                | 9         | 5.52%   |
| Multimedia controller    | 5         | 3.07%   |
| Sound                    | 4         | 2.45%   |
| Net/ethernet             | 3         | 1.84%   |
| Communication controller | 3         | 1.84%   |
| Card reader              | 3         | 1.84%   |
| Camera                   | 3         | 1.84%   |
| Storage                  | 2         | 1.23%   |
| Unassigned class         | 1         | 0.61%   |
| Network                  | 1         | 0.61%   |
| Firewire controller      | 1         | 0.61%   |


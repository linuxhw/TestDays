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

Total: 662

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 57        | 11.73%  |
| Ubuntu 22.04                 | 24        | 4.94%   |
| Ubuntu 18.04                 | 22        | 4.53%   |
| OpenMandriva 4.3             | 20        | 4.12%   |
| Arch Rolling                 | 15        | 3.09%   |
| OpenMandriva 4.2             | 12        | 2.47%   |
| Manjaro                      | 12        | 2.47%   |
| Zorin 15                     | 10        | 2.06%   |
| OpenMandriva 23.03           | 10        | 2.06%   |
| Linux Mint 21.1              | 10        | 2.06%   |
| Fedora 38                    | 10        | 2.06%   |
| Ubuntu 19.10                 | 9         | 1.85%   |
| Debian 11                    | 9         | 1.85%   |
| openSUSE Tumbleweed-XXXXXXXX | 8         | 1.65%   |
| OpenMandriva 23.01           | 6         | 1.23%   |
| Linux Mint 20.3              | 6         | 1.23%   |
| KDE neon 20.04               | 6         | 1.23%   |
| Fedora 37                    | 6         | 1.23%   |
| Arch                         | 6         | 1.23%   |
| Zorin 16                     | 5         | 1.03%   |
| Xubuntu 20.04                | 5         | 1.03%   |
| ROSA R9                      | 5         | 1.03%   |
| Kubuntu 20.04                | 5         | 1.03%   |
| Debian 10                    | 5         | 1.03%   |
| ArcoLinux Rolling            | 5         | 1.03%   |
| Ubuntu 23.04                 | 4         | 0.82%   |
| Ubuntu 21.10                 | 4         | 0.82%   |
| Ubuntu 21.04                 | 4         | 0.82%   |
| Pop!_OS 22.04                | 4         | 0.82%   |
| Pop!_OS 21.10                | 4         | 0.82%   |
| OpenMandriva 23.08           | 4         | 0.82%   |
| Linux Mint 21.2              | 4         | 0.82%   |
| Linux Mint 20.1              | 4         | 0.82%   |
| Linux Mint 19.3              | 4         | 0.82%   |
| KDE neon 22.04               | 4         | 0.82%   |
| Debian                       | 4         | 0.82%   |
| CentOS 8                     | 4         | 0.82%   |
| Ubuntu 19.04                 | 3         | 0.62%   |
| ROSA R11.1                   | 3         | 0.62%   |
| ROSA R10                     | 3         | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 122       | 26.12%  |
| OpenMandriva  | 58        | 12.42%  |
| Linux Mint    | 36        | 7.71%   |
| Fedora        | 30        | 6.42%   |
| Debian        | 22        | 4.71%   |
| Arch          | 22        | 4.71%   |
| Manjaro       | 21        | 4.5%    |
| ROSA          | 20        | 4.28%   |
| Zorin         | 15        | 3.21%   |
| Pop!_OS       | 14        | 3%      |
| openSUSE      | 10        | 2.14%   |
| Kubuntu       | 10        | 2.14%   |
| KDE neon      | 10        | 2.14%   |
| Ubuntu MATE   | 8         | 1.71%   |
| Xubuntu       | 7         | 1.5%    |
| Lubuntu       | 6         | 1.28%   |
| Endless       | 5         | 1.07%   |
| Elementary    | 5         | 1.07%   |
| ArcoLinux     | 5         | 1.07%   |
| CentOS        | 4         | 0.86%   |
| SteamOS       | 3         | 0.64%   |
| Linux Lite    | 3         | 0.64%   |
| Kali          | 3         | 0.64%   |
| EndeavourOS   | 3         | 0.64%   |
| Ubuntu Unity  | 2         | 0.43%   |
| Ubuntu Budgie | 2         | 0.43%   |
| Peppermint    | 2         | 0.43%   |
| Parrot        | 2         | 0.43%   |
| LMDE          | 2         | 0.43%   |
| Xero          | 1         | 0.21%   |
| Void Linux    | 1         | 0.21%   |
| Ubuntu Studio | 1         | 0.21%   |
| Solus         | 1         | 0.21%   |
| Q4OS          | 1         | 0.21%   |
| NixOS         | 1         | 0.21%   |
| MX            | 1         | 0.21%   |
| Manjaro-ARM   | 1         | 0.21%   |
| Laxer OS      | 1         | 0.21%   |
| Garuda Linux  | 1         | 0.21%   |
| Feren OS      | 1         | 0.21%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003            | 19        | 3.56%   |
| 5.10.14-desktop-1omv4002           | 10        | 1.87%   |
| 6.2.6-desktop-1omv2390             | 9         | 1.69%   |
| 5.3.0-40-generic                   | 8         | 1.5%    |
| 5.4.0-66-generic                   | 5         | 0.94%   |
| 5.4.0-28-generic                   | 5         | 0.94%   |
| 5.13.0-40-generic                  | 5         | 0.94%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 5         | 0.94%   |
| 6.1.1-desktop-1omv2290             | 4         | 0.75%   |
| 5.4.0-70-generic                   | 4         | 0.75%   |
| 5.4.0-58-generic                   | 4         | 0.75%   |
| 5.4.0-52-generic                   | 4         | 0.75%   |
| 5.4.0-42-generic                   | 4         | 0.75%   |
| 5.4.0-37-generic                   | 4         | 0.75%   |
| 5.4.0-31-generic                   | 4         | 0.75%   |
| 5.4.0-26-generic                   | 4         | 0.75%   |
| 5.15.0-52-generic                  | 4         | 0.75%   |
| 5.11.0-40-generic                  | 4         | 0.75%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 4         | 0.75%   |
| 5.10.0-13-amd64                    | 4         | 0.75%   |
| 6.4.11-desktop-1omv2390            | 3         | 0.56%   |
| 6.3.5-desktop-3omv2390             | 3         | 0.56%   |
| 6.3.5-200.fc38.x86_64              | 3         | 0.56%   |
| 6.2.0-20-generic                   | 3         | 0.56%   |
| 5.4.0-73-generic                   | 3         | 0.56%   |
| 5.4.0-40-generic                   | 3         | 0.56%   |
| 5.4.0-39-generic                   | 3         | 0.56%   |
| 5.4.0-33-generic                   | 3         | 0.56%   |
| 5.3.0-46-generic                   | 3         | 0.56%   |
| 5.3.0-42-generic                   | 3         | 0.56%   |
| 5.3.0-26-generic                   | 3         | 0.56%   |
| 5.18.12-desktop-3omv4090           | 3         | 0.56%   |
| 5.17.5-arch1-1                     | 3         | 0.56%   |
| 5.15.0-91-generic                  | 3         | 0.56%   |
| 5.15.0-76-generic                  | 3         | 0.56%   |
| 5.15.0-71-generic                  | 3         | 0.56%   |
| 5.15.0-60-generic                  | 3         | 0.56%   |
| 5.15.0-58-generic                  | 3         | 0.56%   |
| 5.15.0-57-generic                  | 3         | 0.56%   |
| 5.15.0-48-generic                  | 3         | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 70        | 13.86%  |
| 5.15.0  | 45        | 8.91%   |
| 5.3.0   | 23        | 4.55%   |
| 5.13.0  | 21        | 4.16%   |
| 5.11.0  | 20        | 3.96%   |
| 5.16.7  | 19        | 3.76%   |
| 4.15.0  | 19        | 3.76%   |
| 6.2.0   | 16        | 3.17%   |
| 5.8.0   | 13        | 2.57%   |
| 5.10.0  | 12        | 2.38%   |
| 4.18.0  | 12        | 2.38%   |
| 6.2.6   | 11        | 2.18%   |
| 5.10.14 | 10        | 1.98%   |
| 5.19.0  | 9         | 1.78%   |
| 5.0.0   | 8         | 1.58%   |
| 6.3.5   | 7         | 1.39%   |
| 6.1.1   | 5         | 0.99%   |
| 4.9.20  | 5         | 0.99%   |
| 6.5.0   | 4         | 0.79%   |
| 6.4.11  | 4         | 0.79%   |
| 6.3.6   | 4         | 0.79%   |
| 5.17.5  | 4         | 0.79%   |
| 5.10.74 | 4         | 0.79%   |
| 4.9.60  | 4         | 0.79%   |
| 6.4.6   | 3         | 0.59%   |
| 6.0.0   | 3         | 0.59%   |
| 5.18.12 | 3         | 0.59%   |
| 5.17.1  | 3         | 0.59%   |
| 6.6.6   | 2         | 0.4%    |
| 6.6.2   | 2         | 0.4%    |
| 6.1.9   | 2         | 0.4%    |
| 6.1.4   | 2         | 0.4%    |
| 6.1.31  | 2         | 0.4%    |
| 6.1.20  | 2         | 0.4%    |
| 6.1.11  | 2         | 0.4%    |
| 6.0.7   | 2         | 0.4%    |
| 6.0.15  | 2         | 0.4%    |
| 6.0.10  | 2         | 0.4%    |
| 5.9.11  | 2         | 0.4%    |
| 5.4.83  | 2         | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 76        | 15.29%  |
| 5.15    | 59        | 11.87%  |
| 6.2     | 33        | 6.64%   |
| 5.10    | 33        | 6.64%   |
| 5.3     | 25        | 5.03%   |
| 5.16    | 25        | 5.03%   |
| 5.11    | 24        | 4.83%   |
| 5.13    | 22        | 4.43%   |
| 6.1     | 19        | 3.82%   |
| 4.15    | 19        | 3.82%   |
| 5.8     | 17        | 3.42%   |
| 6.4     | 15        | 3.02%   |
| 6.3     | 15        | 3.02%   |
| 6.0     | 14        | 2.82%   |
| 5.19    | 13        | 2.62%   |
| 4.18    | 12        | 2.41%   |
| 6.5     | 10        | 2.01%   |
| 5.17    | 10        | 2.01%   |
| 5.0     | 8         | 1.61%   |
| 4.9     | 8         | 1.61%   |
| 6.6     | 7         | 1.41%   |
| 5.18    | 6         | 1.21%   |
| 5.6     | 5         | 1.01%   |
| 5.7     | 4         | 0.8%    |
| 5.12    | 4         | 0.8%    |
| 5.9     | 3         | 0.6%    |
| 5.14    | 3         | 0.6%    |
| 4.19    | 2         | 0.4%    |
| 4.1     | 2         | 0.4%    |
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
| x86_64  | 430       | 95.98%  |
| i686    | 16        | 3.57%   |
| aarch64 | 2         | 0.45%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 190       | 40.95%  |
| KDE5            | 108       | 23.28%  |
| XFCE            | 39        | 8.41%   |
| X-Cinnamon      | 31        | 6.68%   |
| Unknown         | 26        | 5.6%    |
| MATE            | 15        | 3.23%   |
| KDE4            | 9         | 1.94%   |
| KDE             | 9         | 1.94%   |
| LXQt            | 6         | 1.29%   |
| Pantheon        | 5         | 1.08%   |
| i3              | 5         | 1.08%   |
| Budgie          | 5         | 1.08%   |
| LXDE            | 4         | 0.86%   |
| Unity           | 2         | 0.43%   |
| sway            | 2         | 0.43%   |
| GNOME Flashback | 2         | 0.43%   |
| spectrwm        | 1         | 0.22%   |
| qtile           | 1         | 0.22%   |
| icewm           | 1         | 0.22%   |
| Hyprland        | 1         | 0.22%   |
| Deepin          | 1         | 0.22%   |
| awesome         | 1         | 0.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 347       | 74.62%  |
| Wayland | 92        | 19.78%  |
| Unknown | 23        | 4.95%   |
| Tty     | 3         | 0.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 209       | 44.95%  |
| SDDM    | 90        | 19.35%  |
| GDM     | 55        | 11.83%  |
| GDM3    | 46        | 9.89%   |
| LightDM | 45        | 9.68%   |
| KDM     | 9         | 1.94%   |
| TDM     | 6         | 1.29%   |
| XDM     | 1         | 0.22%   |
| SLIMSKI | 1         | 0.22%   |
| LY-DM   | 1         | 0.22%   |
| Ly      | 1         | 0.22%   |
| LXDM    | 1         | 0.22%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_PE   | 226       | 49.13%  |
| en_US   | 121       | 26.3%   |
| es_ES   | 42        | 9.13%   |
| Unknown | 28        | 6.09%   |
| es_MX   | 12        | 2.61%   |
| en_GB   | 6         | 1.3%    |
| C       | 6         | 1.3%    |
| en_CA   | 3         | 0.65%   |
| it_IT   | 2         | 0.43%   |
| fr_FR   | 2         | 0.43%   |
| de_DE   | 2         | 0.43%   |
| ca_ES   | 2         | 0.43%   |
| ru_RU   | 1         | 0.22%   |
| es_VE   | 1         | 0.22%   |
| es_US   | 1         | 0.22%   |
| es_CO   | 1         | 0.22%   |
| es_AR   | 1         | 0.22%   |
| en_NZ   | 1         | 0.22%   |
| en_DK   | 1         | 0.22%   |
| Default | 1         | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 232       | 50.88%  |
| BIOS | 224       | 49.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 333       | 72.08%  |
| Btrfs   | 46        | 9.96%   |
| Overlay | 45        | 9.74%   |
| Unknown | 15        | 3.25%   |
| Xfs     | 11        | 2.38%   |
| Tmpfs   | 9         | 1.95%   |
| Ext3    | 3         | 0.65%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 234       | 50.98%  |
| GPT     | 177       | 38.56%  |
| MBR     | 48        | 10.46%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 383       | 83.08%  |
| Yes       | 78        | 16.92%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 276       | 60.26%  |
| Yes       | 182       | 39.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 95        | 21.25%  |
| Lenovo                  | 77        | 17.23%  |
| ASUSTek Computer        | 60        | 13.42%  |
| Gigabyte Technology     | 41        | 9.17%   |
| Dell                    | 32        | 7.16%   |
| MSI                     | 24        | 5.37%   |
| Intel                   | 24        | 5.37%   |
| Toshiba                 | 19        | 4.25%   |
| Acer                    | 16        | 3.58%   |
| ASRock                  | 9         | 2.01%   |
| Sony                    | 6         | 1.34%   |
| Foxconn                 | 6         | 1.34%   |
| Chuwi                   | 6         | 1.34%   |
| Apple                   | 4         | 0.89%   |
| HUAWEI                  | 3         | 0.67%   |
| Unknown                 | 3         | 0.67%   |
| Raspberry Pi Foundation | 2         | 0.45%   |
| ECS                     | 2         | 0.45%   |
| AMI                     | 2         | 0.45%   |
| Advance                 | 2         | 0.45%   |
| SZMZ                    | 1         | 0.22%   |
| Samsung Electronics     | 1         | 0.22%   |
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
| Chuwi GemiBook Pro                     | 5         | 1.12%   |
| MSI MS-7721                            | 4         | 0.89%   |
| Lenovo V330-15IKB 81AX                 | 4         | 0.89%   |
| HP Pavilion Laptop 15-cw1xxx           | 4         | 0.89%   |
| HP 14                                  | 4         | 0.89%   |
| Gigabyte B75M-D3H                      | 4         | 0.89%   |
| Gigabyte 970A-DS3P                     | 4         | 0.89%   |
| Toshiba Satellite L45-B                | 3         | 0.67%   |
| Lenovo V310-15ISK 80SY                 | 3         | 0.67%   |
| Lenovo IdeaPad 3 14ADA05 81W0          | 3         | 0.67%   |
| Gigabyte F2A68HM-H                     | 3         | 0.67%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA | 3         | 0.67%   |
| ASUS All Series                        | 3         | 0.67%   |
| Unknown                                | 3         | 0.67%   |
| Toshiba Satellite C45-A                | 2         | 0.45%   |
| Lenovo IdeaPad S540-14API 81NH         | 2         | 0.45%   |
| Lenovo IdeaPad S145-15IWL 81MV         | 2         | 0.45%   |
| Lenovo IdeaPad 330S-14IKB 81F4         | 2         | 0.45%   |
| Lenovo G400 20235                      | 2         | 0.45%   |
| Intel H61                              | 2         | 0.45%   |
| Intel DH55PJ AAE93812-303              | 2         | 0.45%   |
| HP ProBook 645 G4                      | 2         | 0.45%   |
| HP Pavilion Gaming Laptop 15-dk1xxx    | 2         | 0.45%   |
| HP Pavilion g4                         | 2         | 0.45%   |
| HP Pavilion dv4                        | 2         | 0.45%   |
| HP Notebook                            | 2         | 0.45%   |
| HP Laptop 15-ef1xxx                    | 2         | 0.45%   |
| HP Compaq Presario C700                | 2         | 0.45%   |
| HP Compaq 4000 Pro SFF PC              | 2         | 0.45%   |
| HP 450                                 | 2         | 0.45%   |
| HP 250 G7 Notebook PC                  | 2         | 0.45%   |
| HP 250 G5 Notebook PC                  | 2         | 0.45%   |
| Gigabyte Z77X-UD5H                     | 2         | 0.45%   |
| Gigabyte X570 AORUS MASTER             | 2         | 0.45%   |
| Gigabyte A520M H                       | 2         | 0.45%   |
| Foxconn 500B Microtower                | 2         | 0.45%   |
| Dell XPS 13 9360                       | 2         | 0.45%   |
| Dell OptiPlex 7010                     | 2         | 0.45%   |
| Dell Latitude E7450                    | 2         | 0.45%   |
| Dell Latitude E5470                    | 2         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 26        | 5.82%   |
| HP Pavilion        | 22        | 4.92%   |
| Lenovo ThinkPad    | 18        | 4.03%   |
| Toshiba Satellite  | 17        | 3.8%    |
| ASUS VivoBook      | 13        | 2.91%   |
| Acer Aspire        | 13        | 2.91%   |
| Dell Latitude      | 12        | 2.68%   |
| HP Laptop          | 11        | 2.46%   |
| HP ProBook         | 10        | 2.24%   |
| HP Compaq          | 10        | 2.24%   |
| ASUS PRIME         | 9         | 2.01%   |
| Dell Inspiron      | 7         | 1.57%   |
| ASUS ROG           | 7         | 1.57%   |
| Dell OptiPlex      | 6         | 1.34%   |
| Lenovo ThinkCentre | 5         | 1.12%   |
| Lenovo Legion      | 5         | 1.12%   |
| Chuwi GemiBook     | 5         | 1.12%   |
| ASUS TUF           | 5         | 1.12%   |
| MSI MS-7721        | 4         | 0.89%   |
| Lenovo V330-15IKB  | 4         | 0.89%   |
| HP 250             | 4         | 0.89%   |
| HP 14              | 4         | 0.89%   |
| Gigabyte B75M-D3H  | 4         | 0.89%   |
| Gigabyte 970A-DS3P | 4         | 0.89%   |
| Lenovo V310-15ISK  | 3         | 0.67%   |
| HP OMEN            | 3         | 0.67%   |
| HP ENVY            | 3         | 0.67%   |
| HP EliteBook       | 3         | 0.67%   |
| Gigabyte X570      | 3         | 0.67%   |
| Gigabyte F2A68HM-H | 3         | 0.67%   |
| ASUS ASUS          | 3         | 0.67%   |
| ASUS All           | 3         | 0.67%   |
| ASRock X570        | 3         | 0.67%   |
| Unknown            | 3         | 0.67%   |
| RPi Raspberry      | 2         | 0.45%   |
| Lenovo Yoga        | 2         | 0.45%   |
| Lenovo G400        | 2         | 0.45%   |
| Intel H61          | 2         | 0.45%   |
| Intel DH61WW       | 2         | 0.45%   |
| Intel DH55PJ       | 2         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 54        | 12.08%  |
| 2019    | 42        | 9.4%    |
| 2018    | 39        | 8.72%   |
| 2012    | 36        | 8.05%   |
| 2016    | 34        | 7.61%   |
| 2014    | 34        | 7.61%   |
| 2013    | 32        | 7.16%   |
| 2021    | 30        | 6.71%   |
| 2017    | 28        | 6.26%   |
| 2011    | 27        | 6.04%   |
| 2010    | 19        | 4.25%   |
| 2015    | 18        | 4.03%   |
| 2008    | 14        | 3.13%   |
| 2007    | 11        | 2.46%   |
| 2022    | 10        | 2.24%   |
| 2009    | 9         | 2.01%   |
| 2023    | 4         | 0.89%   |
| 2006    | 3         | 0.67%   |
| Unknown | 2         | 0.45%   |
| 2004    | 1         | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 272       | 60.85%  |
| Desktop        | 157       | 35.12%  |
| Convertible    | 5         | 1.12%   |
| All in one     | 5         | 1.12%   |
| Mini pc        | 3         | 0.67%   |
| System on chip | 2         | 0.45%   |
| Tablet         | 2         | 0.45%   |
| Server         | 1         | 0.22%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 415       | 92.63%  |
| Enabled  | 33        | 7.37%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 446       | 99.78%  |
| Yes  | 1         | 0.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 118       | 25.71%  |
| 4.01-8.0    | 117       | 25.49%  |
| 3.01-4.0    | 87        | 18.95%  |
| 16.01-24.0  | 68        | 14.81%  |
| 32.01-64.0  | 20        | 4.36%   |
| 1.01-2.0    | 18        | 3.92%   |
| 24.01-32.0  | 11        | 2.4%    |
| 64.01-256.0 | 9         | 1.96%   |
| 2.01-3.0    | 8         | 1.74%   |
| 0.51-1.0    | 3         | 0.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 161       | 31.88%  |
| 2.01-3.0   | 140       | 27.72%  |
| 4.01-8.0   | 79        | 15.64%  |
| 3.01-4.0   | 63        | 12.48%  |
| 0.51-1.0   | 37        | 7.33%   |
| 8.01-16.0  | 21        | 4.16%   |
| 16.01-24.0 | 2         | 0.4%    |
| 32.01-64.0 | 1         | 0.2%    |
| 0.01-0.5   | 1         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 292       | 63.76%  |
| 2      | 123       | 26.86%  |
| 3      | 26        | 5.68%   |
| 4      | 11        | 2.4%    |
| 6      | 2         | 0.44%   |
| 5      | 2         | 0.44%   |
| 9      | 1         | 0.22%   |
| 0      | 1         | 0.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 279       | 62.14%  |
| Yes       | 170       | 37.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 390       | 86.86%  |
| No        | 59        | 13.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 337       | 74.56%  |
| No        | 115       | 25.44%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 277       | 61.56%  |
| No        | 173       | 38.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Peru    | 447       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lima                  | 302       | 65.23%  |
| Arequipa              | 33        | 7.13%   |
| Trujillo              | 28        | 6.05%   |
| Huancayo              | 11        | 2.38%   |
| Chiclayo              | 10        | 2.16%   |
| Piura                 | 9         | 1.94%   |
| Cusco                 | 9         | 1.94%   |
| Tacna                 | 6         | 1.3%    |
| Ica                   | 6         | 1.3%    |
| Moquegua              | 4         | 0.86%   |
| La Victoria           | 3         | 0.65%   |
| Villa                 | 2         | 0.43%   |
| Santiago de Surco     | 2         | 0.43%   |
| San Isidro            | 2         | 0.43%   |
| Puno                  | 2         | 0.43%   |
| Junin                 | 2         | 0.43%   |
| Juliaca               | 2         | 0.43%   |
| Iquitos               | 2         | 0.43%   |
| Ilo                   | 2         | 0.43%   |
| Distrito de Lima      | 2         | 0.43%   |
| Callao                | 2         | 0.43%   |
| Barranco              | 2         | 0.43%   |
| Abancay               | 2         | 0.43%   |
| Tarapoto              | 1         | 0.22%   |
| Surquillo             | 1         | 0.22%   |
| Sullana               | 1         | 0.22%   |
| San Vicente de Canete | 1         | 0.22%   |
| San Borja             | 1         | 0.22%   |
| Punta Colorada        | 1         | 0.22%   |
| Pucallpa              | 1         | 0.22%   |
| Pisco                 | 1         | 0.22%   |
| Oxapampa              | 1         | 0.22%   |
| Miraflores District   | 1         | 0.22%   |
| Machupicchu           | 1         | 0.22%   |
| Lurin                 | 1         | 0.22%   |
| La Libertad           | 1         | 0.22%   |
| Huaraz                | 1         | 0.22%   |
| Huancavelica          | 1         | 0.22%   |
| Cajamarca             | 1         | 0.22%   |
| Bellavista            | 1         | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate                        | 118       | 181    | 19.63%  |
| WDC                            | 107       | 160    | 17.8%   |
| Kingston                       | 73        | 90     | 12.15%  |
| Toshiba                        | 62        | 73     | 10.32%  |
| Samsung Electronics            | 42        | 59     | 6.99%   |
| SanDisk                        | 25        | 29     | 4.16%   |
| Crucial                        | 21        | 30     | 3.49%   |
| Unknown                        | 17        | 24     | 2.83%   |
| Hewlett-Packard                | 11        | 12     | 1.83%   |
| Intel                          | 10        | 12     | 1.66%   |
| SK hynix                       | 9         | 13     | 1.5%    |
| Micron Technology              | 9         | 10     | 1.5%    |
| Hitachi                        | 9         | 13     | 1.5%    |
| HGST                           | 8         | 8      | 1.33%   |
| KIOXIA                         | 7         | 8      | 1.16%   |
| A-DATA Technology              | 6         | 6      | 1%      |
| Netac                          | 5         | 5      | 0.83%   |
| Kingston Technology Company    | 5         | 7      | 0.83%   |
| Gigabyte Technology            | 5         | 5      | 0.83%   |
| Silicon Motion                 | 4         | 4      | 0.67%   |
| Phison Electronics             | 4         | 4      | 0.67%   |
| Micron/Crucial Technology      | 4         | 9      | 0.67%   |
| LITEON                         | 4         | 4      | 0.67%   |
| TO Exter                       | 3         | 7      | 0.5%    |
| PNY                            | 3         | 3      | 0.5%    |
| Unknown                        | 3         | 4      | 0.5%    |
| UMIS                           | 2         | 2      | 0.33%   |
| Team                           | 2         | 2      | 0.33%   |
| China                          | 2         | 2      | 0.33%   |
| Apple                          | 2         | 2      | 0.33%   |
| WD MediaMax                    | 1         | 1      | 0.17%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.17%   |
| SSSTC                          | 1         | 1      | 0.17%   |
| Solid State Storage Technology | 1         | 1      | 0.17%   |
| Reletech-P400                  | 1         | 1      | 0.17%   |
| Phison                         | 1         | 1      | 0.17%   |
| NGFF                           | 1         | 1      | 0.17%   |
| Mushkin                        | 1         | 2      | 0.17%   |
| MSI                            | 1         | 1      | 0.17%   |
| Maxone                         | 1         | 2      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 23        | 3.45%   |
| Seagate ST1000LM035-1RK172 1TB     | 21        | 3.15%   |
| Seagate ST500DM002-1BD142 500GB    | 15        | 2.25%   |
| Toshiba MQ04ABF100 1TB             | 11        | 1.65%   |
| Seagate ST1000DM010-2EP102 1TB     | 11        | 1.65%   |
| Kingston SA400S37480G 480GB SSD    | 11        | 1.65%   |
| Toshiba MQ01ABD100 1TB             | 10        | 1.5%    |
| Kingston SA400S37120G 120GB SSD    | 9         | 1.35%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 8         | 1.2%    |
| WDC WD10EZEX-08WN4A0 1TB           | 7         | 1.05%   |
| Toshiba DT01ACA100 1TB             | 6         | 0.9%    |
| Seagate ST2000DM001-1ER164 2TB     | 6         | 0.9%    |
| HP SSD S700 500GB                  | 6         | 0.9%    |
| Unknown MMC Card  32GB             | 5         | 0.75%   |
| Toshiba MQ01ABF050 500GB           | 5         | 0.75%   |
| Seagate ST9500325AS 500GB          | 5         | 0.75%   |
| Seagate ST3500418AS 500GB          | 5         | 0.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 5         | 0.75%   |
| Seagate ST1000DM003-1CH162 1TB     | 5         | 0.75%   |
| Netac SSD 256GB                    | 5         | 0.75%   |
| Crucial CT500MX500SSD4 500GB       | 5         | 0.75%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 4         | 0.6%    |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 4         | 0.6%    |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 4         | 0.6%    |
| WDC WDS100T3X0C-00SJG0 1TB         | 4         | 0.6%    |
| WDC WD10SPZX-24Z10 1TB             | 4         | 0.6%    |
| WDC WD10JPCX-24UE4T0 1TB           | 4         | 0.6%    |
| Unknown SD32G  32GB                | 4         | 0.6%    |
| Seagate ST500LT012-1DG142 500GB    | 4         | 0.6%    |
| Seagate ST3500413AS 500GB          | 4         | 0.6%    |
| Seagate ST3500312CS 500GB          | 4         | 0.6%    |
| Seagate ST2000DM006-2DM164 2TB     | 4         | 0.6%    |
| Seagate ST1000LM049-2GH172 1TB     | 4         | 0.6%    |
| SanDisk NVMe SSD Drive 1TB         | 4         | 0.6%    |
| Kingston SNVS500G 500GB            | 4         | 0.6%    |
| Kingston SNVS250G 250GB            | 4         | 0.6%    |
| Kingston SA400S37960G 960GB SSD    | 4         | 0.6%    |
| Intel SSDPEKNU512GZ 512GB          | 4         | 0.6%    |
| WDC WD3200AAJS-56M0A0 320GB        | 3         | 0.45%   |
| WDC WD10SPZX-08Z10 1TB             | 3         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 116       | 173    | 40.14%  |
| WDC                 | 77        | 103    | 26.64%  |
| Toshiba             | 60        | 71     | 20.76%  |
| Samsung Electronics | 12        | 16     | 4.15%   |
| Hitachi             | 9         | 13     | 3.11%   |
| HGST                | 8         | 8      | 2.77%   |
| TO Exter            | 3         | 7      | 1.04%   |
| KESU                | 1         | 1      | 0.35%   |
| Fujitsu             | 1         | 1      | 0.35%   |
| Apple               | 1         | 1      | 0.35%   |
| ACASIS              | 1         | 1      | 0.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 58        | 68     | 33.33%  |
| WDC                 | 30        | 40     | 17.24%  |
| Crucial             | 17        | 24     | 9.77%   |
| Hewlett-Packard     | 11        | 11     | 6.32%   |
| Samsung Electronics | 8         | 10     | 4.6%    |
| SanDisk             | 7         | 9      | 4.02%   |
| A-DATA Technology   | 6         | 6      | 3.45%   |
| Netac               | 5         | 5      | 2.87%   |
| LITEON              | 4         | 4      | 2.3%    |
| Gigabyte Technology | 4         | 4      | 2.3%    |
| Seagate             | 3         | 7      | 1.72%   |
| PNY                 | 3         | 3      | 1.72%   |
| Team                | 2         | 2      | 1.15%   |
| Intel               | 2         | 2      | 1.15%   |
| China               | 2         | 2      | 1.15%   |
| Toshiba             | 1         | 1      | 0.57%   |
| SSSTC               | 1         | 1      | 0.57%   |
| SK hynix            | 1         | 4      | 0.57%   |
| Reletech-P400       | 1         | 1      | 0.57%   |
| NGFF                | 1         | 1      | 0.57%   |
| Maxone              | 1         | 2      | 0.57%   |
| Lenovo              | 1         | 1      | 0.57%   |
| KingSpec            | 1         | 1      | 0.57%   |
| GLOWAY              | 1         | 1      | 0.57%   |
| Dogfish             | 1         | 1      | 0.57%   |
| Apple               | 1         | 1      | 0.57%   |
| Unknown             | 1         | 1      | 0.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 265       | 395    | 46.49%  |
| SSD     | 158       | 213    | 27.72%  |
| NVMe    | 123       | 171    | 21.58%  |
| MMC     | 18        | 23     | 3.16%   |
| Unknown | 6         | 9      | 1.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 353       | 600    | 69.9%   |
| NVMe | 123       | 171    | 24.36%  |
| MMC  | 18        | 23     | 3.56%   |
| SAS  | 11        | 17     | 2.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 232       | 353    | 54.46%  |
| 0.51-1.0   | 161       | 202    | 37.79%  |
| 1.01-2.0   | 23        | 38     | 5.4%    |
| 4.01-10.0  | 4         | 7      | 0.94%   |
| 3.01-4.0   | 3         | 5      | 0.7%    |
| 2.01-3.0   | 3         | 3      | 0.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 119       | 25.16%  |
| 101-250        | 102       | 21.56%  |
| 501-1000       | 89        | 18.82%  |
| 51-100         | 34        | 7.19%   |
| 1-20           | 32        | 6.77%   |
| 21-50          | 31        | 6.55%   |
| 1001-2000      | 31        | 6.55%   |
| 2001-3000      | 15        | 3.17%   |
| More than 3000 | 14        | 2.96%   |
| Unknown        | 6         | 1.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 187       | 38.24%  |
| 21-50          | 92        | 18.81%  |
| 101-250        | 60        | 12.27%  |
| 51-100         | 48        | 9.82%   |
| 251-500        | 47        | 9.61%   |
| 501-1000       | 25        | 5.11%   |
| 1001-2000      | 14        | 2.86%   |
| More than 3000 | 6         | 1.23%   |
| Unknown        | 6         | 1.23%   |
| 2001-3000      | 4         | 0.82%   |

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
| SSSTC CVB-8D128-HP 128GB SSD         | 1         | 1      | 1.67%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 1         | 1      | 1.67%   |
| Seagate ST980811AS 80GB              | 1         | 1      | 1.67%   |
| Seagate ST9250315AS 250GB            | 1         | 1      | 1.67%   |
| Seagate ST500DM002-9YN14C 500GB      | 1         | 2      | 1.67%   |
| Seagate ST3500312CS 500GB            | 1         | 1      | 1.67%   |
| Seagate ST3320820SCE 320GB           | 1         | 2      | 1.67%   |
| Seagate ST3250820AS 250GB            | 1         | 1      | 1.67%   |
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
| Detected | 267       | 460    | 53.94%  |
| Works    | 175       | 281    | 35.35%  |
| Malfunc  | 52        | 68     | 10.51%  |
| Failed   | 1         | 2      | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 294       | 54.95%  |
| AMD                              | 101       | 18.88%  |
| SanDisk                          | 28        | 5.23%   |
| Samsung Electronics              | 23        | 4.3%    |
| Kingston Technology Company      | 22        | 4.11%   |
| Micron Technology                | 9         | 1.68%   |
| SK hynix                         | 8         | 1.5%    |
| Micron/Crucial Technology        | 8         | 1.5%    |
| KIOXIA                           | 7         | 1.31%   |
| Silicon Motion                   | 6         | 1.12%   |
| Marvell Technology Group         | 6         | 1.12%   |
| Phison Electronics               | 5         | 0.93%   |
| Nvidia                           | 5         | 0.93%   |
| JMicron Technology               | 3         | 0.56%   |
| Union Memory (Shenzhen)          | 2         | 0.37%   |
| Toshiba America Info Systems     | 1         | 0.19%   |
| Solid State Storage Technology   | 1         | 0.19%   |
| Silicon Integrated Systems [SiS] | 1         | 0.19%   |
| LSI Logic / Symbios Logic        | 1         | 0.19%   |
| INNOGRIT                         | 1         | 0.19%   |
| Hewlett-Packard                  | 1         | 0.19%   |
| Broadcom / LSI                   | 1         | 0.19%   |
| Biwin Storage Technology         | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 68        | 11.18%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 33        | 5.43%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 24        | 3.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 20        | 3.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16        | 2.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 16        | 2.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 13        | 2.14%   |
| AMD 500 Series Chipset SATA Controller                                                  | 13        | 2.14%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 12        | 1.97%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 11        | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 11        | 1.81%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10        | 1.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 9         | 1.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9         | 1.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9         | 1.48%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 9         | 1.48%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 8         | 1.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8         | 1.32%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 8         | 1.32%   |
| Kingston Company NV1 NVMe SSD SM2263XT                                                  | 8         | 1.32%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 1.32%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 8         | 1.32%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 7         | 1.15%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 7         | 1.15%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 7         | 1.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7         | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7         | 1.15%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 6         | 0.99%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 6         | 0.99%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 5         | 0.82%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton2]                                              | 5         | 0.82%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 5         | 0.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 5         | 0.82%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 5         | 0.82%   |
| SK hynix BC511 NVMe SSD                                                                 | 4         | 0.66%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 4         | 0.66%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 0.66%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4         | 0.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 0.66%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 325       | 59.41%  |
| NVMe | 123       | 22.49%  |
| IDE  | 56        | 10.24%  |
| RAID | 40        | 7.31%   |
| SAS  | 2         | 0.37%   |
| SCSI | 1         | 0.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 318       | 71.14%  |
| AMD    | 127       | 28.41%  |
| ARM    | 2         | 0.45%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 2.23%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 1.79%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 7         | 1.56%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 7         | 1.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 1.34%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 1.34%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 5         | 1.12%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 1.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 1.12%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 1.12%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 5         | 1.12%   |
| Intel Celeron J4115 CPU @ 1.80GHz             | 5         | 1.12%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 1.12%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 5         | 1.12%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 1.12%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 0.89%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.89%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 4         | 0.89%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 0.89%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 0.89%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz   | 3         | 0.67%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 3         | 0.67%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 0.67%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 0.67%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 3         | 0.67%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 3         | 0.67%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 3         | 0.67%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 0.67%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3         | 0.67%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 3         | 0.67%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.67%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 0.67%   |
| Intel Celeron CPU 550 @ 2.00GHz               | 3         | 0.67%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 0.67%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 3         | 0.67%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 0.67%   |
| AMD FX-8350 Eight-Core Processor              | 3         | 0.67%   |
| AMD Athlon Silver 3050U with Radeon Graphics  | 3         | 0.67%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 2         | 0.45%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 95        | 21.25%  |
| Intel Core i7           | 89        | 19.91%  |
| Intel Core i3           | 43        | 9.62%   |
| AMD Ryzen 5             | 31        | 6.94%   |
| AMD Ryzen 7             | 29        | 6.49%   |
| Other                   | 22        | 4.92%   |
| Intel Celeron           | 18        | 4.03%   |
| Intel Core 2 Duo        | 11        | 2.46%   |
| Intel Atom              | 8         | 1.79%   |
| Intel Pentium           | 7         | 1.57%   |
| AMD Ryzen 9             | 7         | 1.57%   |
| AMD Ryzen 3             | 7         | 1.57%   |
| AMD FX                  | 7         | 1.57%   |
| Intel Xeon              | 6         | 1.34%   |
| Intel Pentium Dual-Core | 6         | 1.34%   |
| AMD A8                  | 6         | 1.34%   |
| Intel Pentium Dual      | 5         | 1.12%   |
| AMD A4                  | 5         | 1.12%   |
| AMD A10                 | 5         | 1.12%   |
| AMD Athlon              | 4         | 0.89%   |
| AMD A6                  | 4         | 0.89%   |
| AMD Phenom II X4        | 3         | 0.67%   |
| AMD E1                  | 3         | 0.67%   |
| Intel Pentium Gold      | 2         | 0.45%   |
| Intel Pentium 4         | 2         | 0.45%   |
| Intel Core 2 Quad       | 2         | 0.45%   |
| Intel Core 2            | 2         | 0.45%   |
| AMD Sempron             | 2         | 0.45%   |
| AMD Ryzen 7 PRO         | 2         | 0.45%   |
| AMD E                   | 2         | 0.45%   |
| Intel Pentium D         | 1         | 0.22%   |
| Intel Genuine           | 1         | 0.22%   |
| Intel Core i9           | 1         | 0.22%   |
| Intel Celeron M         | 1         | 0.22%   |
| AMD Ryzen 5 PRO         | 1         | 0.22%   |
| AMD Phenom II X3        | 1         | 0.22%   |
| AMD C-50                | 1         | 0.22%   |
| AMD Athlon X4           | 1         | 0.22%   |
| AMD Athlon II X3        | 1         | 0.22%   |
| AMD Athlon II X2        | 1         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 179       | 40.04%  |
| 4       | 167       | 37.36%  |
| 8       | 35        | 7.83%   |
| 6       | 32        | 7.16%   |
| 1       | 15        | 3.36%   |
| 16      | 5         | 1.12%   |
| 3       | 4         | 0.89%   |
| 12      | 3         | 0.67%   |
| 10      | 3         | 0.67%   |
| Unknown | 2         | 0.45%   |
| 20      | 1         | 0.22%   |
| 14      | 1         | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 446       | 99.78%  |
| 2      | 1         | 0.22%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 322       | 72.04%  |
| 1       | 123       | 27.52%  |
| Unknown | 2         | 0.45%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 436       | 96.67%  |
| 64-bit         | 6         | 1.33%   |
| Unknown        | 6         | 1.33%   |
| 32-bit         | 3         | 0.67%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 130       | 27.9%   |
| 0x306a9    | 26        | 5.58%   |
| 0x206a7    | 23        | 4.94%   |
| 0x306c3    | 15        | 3.22%   |
| 0x806ec    | 12        | 2.58%   |
| 0x806ea    | 11        | 2.36%   |
| 0x40651    | 11        | 2.36%   |
| 0x08108109 | 11        | 2.36%   |
| 0x406e3    | 10        | 2.15%   |
| 0x1067a    | 10        | 2.15%   |
| 0x806e9    | 9         | 1.93%   |
| 0x306d4    | 9         | 1.93%   |
| 0x906ea    | 7         | 1.5%    |
| 0x506e3    | 7         | 1.5%    |
| 0x0a50000c | 7         | 1.5%    |
| 0x08701021 | 7         | 1.5%    |
| 0x08108102 | 7         | 1.5%    |
| 0x6fd      | 6         | 1.29%   |
| 0x20655    | 6         | 1.29%   |
| 0x906e9    | 5         | 1.07%   |
| 0x806c1    | 5         | 1.07%   |
| 0x706e5    | 5         | 1.07%   |
| 0x06003106 | 5         | 1.07%   |
| 0x06000852 | 5         | 1.07%   |
| 0x010000c8 | 5         | 1.07%   |
| 0xa0652    | 4         | 0.86%   |
| 0x406c4    | 4         | 0.86%   |
| 0x08600106 | 4         | 0.86%   |
| 0x0810100b | 4         | 0.86%   |
| 0x07030105 | 4         | 0.86%   |
| 0x806eb    | 3         | 0.64%   |
| 0x6fb      | 3         | 0.64%   |
| 0x30678    | 3         | 0.64%   |
| 0x20652    | 3         | 0.64%   |
| 0x10676    | 3         | 0.64%   |
| 0x10661    | 3         | 0.64%   |
| 0x08608103 | 3         | 0.64%   |
| 0x06001119 | 3         | 0.64%   |
| 0xf64      | 2         | 0.43%   |
| 0xa0655    | 2         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 74        | 16.52%  |
| Haswell          | 36        | 8.04%   |
| IvyBridge        | 35        | 7.81%   |
| SandyBridge      | 28        | 6.25%   |
| Skylake          | 26        | 5.8%    |
| Zen+             | 25        | 5.58%   |
| Zen 2            | 22        | 4.91%   |
| Penryn           | 17        | 3.79%   |
| Zen 3            | 16        | 3.57%   |
| Core             | 14        | 3.13%   |
| Unknown          | 14        | 3.13%   |
| Silvermont       | 13        | 2.9%    |
| Westmere         | 12        | 2.68%   |
| Piledriver       | 12        | 2.68%   |
| Broadwell        | 12        | 2.68%   |
| Icelake          | 11        | 2.46%   |
| CometLake        | 10        | 2.23%   |
| Zen              | 9         | 2.01%   |
| K10              | 9         | 2.01%   |
| TigerLake        | 7         | 1.56%   |
| Steamroller      | 7         | 1.56%   |
| Goldmont plus    | 7         | 1.56%   |
| Excavator        | 6         | 1.34%   |
| Puma             | 5         | 1.12%   |
| Alderlake Hybrid | 4         | 0.89%   |
| NetBurst         | 3         | 0.67%   |
| Bobcat           | 3         | 0.67%   |
| P6               | 2         | 0.45%   |
| Nehalem          | 2         | 0.45%   |
| Jaguar           | 2         | 0.45%   |
| Bonnell          | 2         | 0.45%   |
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
| Intel                            | 266       | 49.08%  |
| AMD                              | 145       | 26.75%  |
| Nvidia                           | 129       | 23.8%   |
| Silicon Integrated Systems [SiS] | 1         | 0.18%   |
| Matrox Electronics Systems       | 1         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 24        | 4.29%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 22        | 3.93%   |
| Intel UHD Graphics 620                                                                   | 20        | 3.57%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 3.21%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 17        | 3.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 2.14%   |
| Intel HD Graphics 620                                                                    | 11        | 1.96%   |
| Intel HD Graphics 5500                                                                   | 11        | 1.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 1.96%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 10        | 1.79%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 10        | 1.79%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 10        | 1.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 1.43%   |
| Intel HD Graphics 530                                                                    | 8         | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 1.43%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 8         | 1.43%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 1.43%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 1.25%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 1.25%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 1.25%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7         | 1.25%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 1.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.07%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.07%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.89%   |
| Nvidia GT218 [GeForce 210]                                                               | 5         | 0.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 0.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 0.89%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 0.89%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 0.89%   |
| Intel HD Graphics 630                                                                    | 5         | 0.89%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 0.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 4         | 0.71%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 0.71%   |
| Nvidia GM108M [GeForce MX110]                                                            | 4         | 0.71%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.71%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.71%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 4         | 0.71%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 4         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 179       | 39.96%  |
| 1 x AMD        | 100       | 22.32%  |
| 1 x Nvidia     | 60        | 13.39%  |
| Intel + Nvidia | 57        | 12.72%  |
| Intel + AMD    | 23        | 5.13%   |
| AMD + Nvidia   | 12        | 2.68%   |
| 2 x AMD        | 10        | 2.23%   |
| 2 x Intel      | 3         | 0.67%   |
| Other          | 2         | 0.45%   |
| 1 x SiS        | 1         | 0.22%   |
| 1 x Matrox     | 1         | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 375       | 82.78%  |
| Proprietary | 67        | 14.79%  |
| Unknown     | 11        | 2.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 241       | 52.39%  |
| 1.01-2.0   | 77        | 16.74%  |
| 0.01-0.5   | 54        | 11.74%  |
| 3.01-4.0   | 29        | 6.3%    |
| 0.51-1.0   | 29        | 6.3%    |
| 7.01-8.0   | 16        | 3.48%   |
| 5.01-6.0   | 11        | 2.39%   |
| 8.01-16.0  | 3         | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 86        | 17.84%  |
| Chimei Innolux       | 72        | 14.94%  |
| BOE                  | 52        | 10.79%  |
| Goldstar             | 51        | 10.58%  |
| AU Optronics         | 46        | 9.54%   |
| LG Display           | 39        | 8.09%   |
| Hewlett-Packard      | 21        | 4.36%   |
| AOC                  | 15        | 3.11%   |
| Dell                 | 9         | 1.87%   |
| ViewSonic            | 7         | 1.45%   |
| PANDA                | 7         | 1.45%   |
| Lenovo               | 7         | 1.45%   |
| BenQ                 | 6         | 1.24%   |
| Sony                 | 5         | 1.04%   |
| ASUSTek Computer     | 5         | 1.04%   |
| Unknown              | 4         | 0.83%   |
| Apple                | 4         | 0.83%   |
| Sharp                | 3         | 0.62%   |
| JRY                  | 3         | 0.62%   |
| TMX                  | 2         | 0.41%   |
| Panasonic            | 2         | 0.41%   |
| LG Philips           | 2         | 0.41%   |
| LG Electronics       | 2         | 0.41%   |
| Lenovo Group Limited | 2         | 0.41%   |
| HannStar             | 2         | 0.41%   |
| Unknown              | 2         | 0.41%   |
| Yuraku               | 1         | 0.21%   |
| Viotek               | 1         | 0.21%   |
| Unknown (XXX)        | 1         | 0.21%   |
| TopView              | 1         | 0.21%   |
| Sceptre Tech         | 1         | 0.21%   |
| NEW                  | 1         | 0.21%   |
| MStar                | 1         | 0.21%   |
| MSI                  | 1         | 0.21%   |
| MSD                  | 1         | 0.21%   |
| Mi                   | 1         | 0.21%   |
| LGD                  | 1         | 0.21%   |
| InnoLux Display      | 1         | 0.21%   |
| InfoVision           | 1         | 0.21%   |
| Hyundai ImageQuest   | 1         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 12        | 2.44%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch        | 10        | 2.04%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 9         | 1.83%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 5         | 1.02%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch       | 5         | 1.02%   |
| Samsung Electronics SA300/SA350 SAM078D 1600x900 443x249mm 20.0-inch   | 4         | 0.81%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 4         | 0.81%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch           | 4         | 0.81%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch          | 4         | 0.81%   |
| JRY DX238A1 JRY2380 1920x1080 368x207mm 16.6-inch                      | 3         | 0.61%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                   | 3         | 0.61%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                    | 3         | 0.61%   |
| Goldstar E1951 GSM4BFD 1366x768 410x230mm 18.5-inch                    | 3         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch        | 3         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 3         | 0.61%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch        | 3         | 0.61%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                   | 3         | 0.61%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                   | 3         | 0.61%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                      | 3         | 0.61%   |
| ViewSonic VA2246 SERIES VSC6F2E 1920x1080 480x270mm 21.7-inch          | 2         | 0.41%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 2         | 0.41%   |
| Samsung Electronics SyncMaster SAM0272 1280x1024 338x270mm 17.0-inch   | 2         | 0.41%   |
| Samsung Electronics SA300/SA350 SAM078A 1366x768 410x230mm 18.5-inch   | 2         | 0.41%   |
| Samsung Electronics S20B300 SAM08A7 1600x900 443x249mm 20.0-inch       | 2         | 0.41%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch       | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch   | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch   | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch   | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch   | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch   | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1020x570mm 46.0-inch | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SAM07D0 1360x768 700x390mm 31.5-inch   | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SAM04FD 1280x720                       | 2         | 0.41%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 598x336mm 27.0-inch      | 2         | 0.41%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                | 2         | 0.41%   |
| LG Display LCD Monitor LGD062F 1920x1080 344x194mm 15.5-inch           | 2         | 0.41%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch           | 2         | 0.41%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch            | 2         | 0.41%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 2         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 173       | 36.97%  |
| 1366x768 (WXGA)   | 164       | 35.04%  |
| 1600x900 (HD+)    | 29        | 6.2%    |
| 3840x2160 (4K)    | 15        | 3.21%   |
| 1360x768          | 15        | 3.21%   |
| 2560x1440 (QHD)   | 10        | 2.14%   |
| 1440x900 (WXGA+)  | 9         | 1.92%   |
| 1280x800 (WXGA)   | 9         | 1.92%   |
| 2160x1440         | 5         | 1.07%   |
| 1920x1200 (WUXGA) | 5         | 1.07%   |
| 1280x1024 (SXGA)  | 5         | 1.07%   |
| 1024x768 (XGA)    | 5         | 1.07%   |
| 2560x1600         | 4         | 0.85%   |
| Unknown           | 4         | 0.85%   |
| 3840x1080         | 3         | 0.64%   |
| 3200x1800 (QHD+)  | 2         | 0.43%   |
| 2560x1080         | 2         | 0.43%   |
| 1024x600          | 2         | 0.43%   |
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
| 15      | 150       | 31.25%  |
| 13      | 55        | 11.46%  |
| 21      | 50        | 10.42%  |
| 14      | 41        | 8.54%   |
| 23      | 35        | 7.29%   |
| 18      | 22        | 4.58%   |
| 20      | 17        | 3.54%   |
| Unknown | 16        | 3.33%   |
| 27      | 15        | 3.13%   |
| 17      | 14        | 2.92%   |
| 24      | 11        | 2.29%   |
| 19      | 9         | 1.88%   |
| 31      | 6         | 1.25%   |
| 11      | 6         | 1.25%   |
| 16      | 5         | 1.04%   |
| 48      | 4         | 0.83%   |
| 12      | 4         | 0.83%   |
| 32      | 3         | 0.63%   |
| 84      | 2         | 0.42%   |
| 72      | 2         | 0.42%   |
| 34      | 2         | 0.42%   |
| 30      | 2         | 0.42%   |
| 10      | 2         | 0.42%   |
| 60      | 1         | 0.21%   |
| 54      | 1         | 0.21%   |
| 52      | 1         | 0.21%   |
| 46      | 1         | 0.21%   |
| 43      | 1         | 0.21%   |
| 39      | 1         | 0.21%   |
| 22      | 1         | 0.21%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 237       | 50%     |
| 401-500     | 94        | 19.83%  |
| 501-600     | 60        | 12.66%  |
| 201-300     | 27        | 5.7%    |
| Unknown     | 16        | 3.38%   |
| 351-400     | 13        | 2.74%   |
| 601-700     | 8         | 1.69%   |
| 1001-1500   | 8         | 1.69%   |
| 701-800     | 5         | 1.05%   |
| 1501-2000   | 4         | 0.84%   |
| 801-900     | 1         | 0.21%   |
| 901-1000    | 1         | 0.21%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 360       | 83.72%  |
| 16/10   | 32        | 7.44%   |
| Unknown | 15        | 3.49%   |
| 5/4     | 7         | 1.63%   |
| 4/3     | 7         | 1.63%   |
| 3/2     | 7         | 1.63%   |
| 21/9    | 2         | 0.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 150       | 31.51%  |
| 81-90          | 83        | 17.44%  |
| 201-250        | 82        | 17.23%  |
| 151-200        | 38        | 7.98%   |
| 141-150        | 25        | 5.25%   |
| Unknown        | 16        | 3.36%   |
| 301-350        | 15        | 3.15%   |
| 71-80          | 13        | 2.73%   |
| 351-500        | 13        | 2.73%   |
| More than 1000 | 11        | 2.31%   |
| 51-60          | 6         | 1.26%   |
| 121-130        | 6         | 1.26%   |
| 111-120        | 5         | 1.05%   |
| 131-140        | 3         | 0.63%   |
| 501-1000       | 3         | 0.63%   |
| 61-70          | 2         | 0.42%   |
| 41-50          | 2         | 0.42%   |
| 91-100         | 2         | 0.42%   |
| 251-300        | 1         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 200       | 42.92%  |
| 51-100        | 123       | 26.39%  |
| 121-160       | 92        | 19.74%  |
| 1-50          | 16        | 3.43%   |
| Unknown       | 16        | 3.43%   |
| 161-240       | 14        | 3%      |
| More than 240 | 5         | 1.07%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 376       | 81.92%  |
| 2     | 65        | 14.16%  |
| 0     | 13        | 2.83%   |
| 3     | 5         | 1.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 283       | 43.81%  |
| Intel                            | 161       | 24.92%  |
| Qualcomm Atheros                 | 89        | 13.78%  |
| Broadcom                         | 22        | 3.41%   |
| TP-Link                          | 16        | 2.48%   |
| MediaTek                         | 9         | 1.39%   |
| Ralink Technology                | 7         | 1.08%   |
| Ralink                           | 7         | 1.08%   |
| Xiaomi                           | 6         | 0.93%   |
| Nvidia                           | 5         | 0.77%   |
| Marvell Technology Group         | 5         | 0.77%   |
| Qualcomm Atheros Communications  | 4         | 0.62%   |
| Broadcom Limited                 | 4         | 0.62%   |
| ASIX Electronics                 | 4         | 0.62%   |
| Motorola PCS                     | 3         | 0.46%   |
| Microsoft                        | 3         | 0.46%   |
| ICS Advent                       | 3         | 0.46%   |
| Samsung Electronics              | 2         | 0.31%   |
| Huawei Technologies              | 2         | 0.31%   |
| D-Link System                    | 2         | 0.31%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 193       | 25.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 42        | 5.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 30        | 3.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 2.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 18        | 2.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 13        | 1.7%    |
| Intel Wi-Fi 6 AX200                                                     | 12        | 1.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.44%   |
| Realtek RTL8125 2.5GbE Controller                                       | 11        | 1.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 10        | 1.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 1.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 10        | 1.31%   |
| Intel Wireless 8265 / 8275                                              | 9         | 1.17%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 1.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 1.04%   |
| Intel Wireless 8260                                                     | 8         | 1.04%   |
| Intel Wireless 7265                                                     | 8         | 1.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 1.04%   |
| Intel Ethernet Connection (2) I219-V                                    | 7         | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 0.91%   |
| Intel 82579V Gigabit Network Connection                                 | 7         | 0.91%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 6         | 0.78%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 6         | 0.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 6         | 0.78%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.78%   |
| Intel Wireless 7260                                                     | 6         | 0.78%   |
| Intel I211 Gigabit Network Connection                                   | 6         | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 0.78%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 0.65%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 5         | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                                   | 5         | 0.65%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 4         | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 0.52%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 4         | 0.52%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 0.52%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 116       | 33.24%  |
| Realtek Semiconductor           | 88        | 25.21%  |
| Qualcomm Atheros                | 78        | 22.35%  |
| Broadcom                        | 20        | 5.73%   |
| TP-Link                         | 14        | 4.01%   |
| MediaTek                        | 9         | 2.58%   |
| Ralink Technology               | 7         | 2.01%   |
| Ralink                          | 7         | 2.01%   |
| Qualcomm Atheros Communications | 4         | 1.15%   |
| Microsoft                       | 2         | 0.57%   |
| Marvell Technology Group        | 1         | 0.29%   |
| D-Link System                   | 1         | 0.29%   |
| D-Link                          | 1         | 0.29%   |
| Broadcom Limited                | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 30        | 8.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 5.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 18        | 5.16%   |
| Intel Wi-Fi 6 AX200                                                     | 12        | 3.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 3.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 10        | 2.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 2.87%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 10        | 2.87%   |
| Intel Wireless 8265 / 8275                                              | 9         | 2.58%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 2.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 2.29%   |
| Intel Wireless 8260                                                     | 8         | 2.29%   |
| Intel Wireless 7265                                                     | 8         | 2.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 2.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 2.01%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 6         | 1.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 1.72%   |
| Intel Wireless 7260                                                     | 6         | 1.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 1.72%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 1.43%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.43%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 5         | 1.43%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 4         | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.15%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 1.15%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 1.15%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.15%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.15%   |
| TP-Link 802.11n NIC                                                     | 3         | 0.86%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.86%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 3         | 0.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.86%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.86%   |
| Intel WiFi Link 5100                                                    | 3         | 0.86%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.86%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.86%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 3         | 0.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.86%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                 | 2         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 255       | 62.35%  |
| Intel                            | 86        | 21.03%  |
| Qualcomm Atheros                 | 22        | 5.38%   |
| Xiaomi                           | 6         | 1.47%   |
| Nvidia                           | 5         | 1.22%   |
| Marvell Technology Group         | 4         | 0.98%   |
| Broadcom                         | 4         | 0.98%   |
| ASIX Electronics                 | 4         | 0.98%   |
| ICS Advent                       | 3         | 0.73%   |
| Broadcom Limited                 | 3         | 0.73%   |
| TP-Link                          | 2         | 0.49%   |
| Motorola PCS                     | 2         | 0.49%   |
| Huawei Technologies              | 2         | 0.49%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.24%   |
| T & A Mobile Phones              | 1         | 0.24%   |
| Silicon Integrated Systems [SiS] | 1         | 0.24%   |
| Samsung Electronics              | 1         | 0.24%   |
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


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 193       | 46.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 42        | 10.12%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 3.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 2.65%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 1.69%   |
| Intel 82579V Gigabit Network Connection                           | 7         | 1.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6         | 1.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.45%   |
| Intel I211 Gigabit Network Connection                             | 6         | 1.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 1.2%    |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 1.2%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 0.96%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 0.96%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.72%   |
| Nvidia MCP61 Ethernet                                             | 3         | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.72%   |
| Intel Ethernet Connection (12) I219-V                             | 3         | 0.72%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.72%   |
| Intel 82578DC Gigabit Network Connection                          | 3         | 0.72%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 3         | 0.72%   |
| TP-Link USB 10/100 LAN                                            | 2         | 0.48%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.48%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.48%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.48%   |
| Motorola PCS motorola edge 40                                     | 2         | 0.48%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.48%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.48%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.48%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.48%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.48%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.48%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.48%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.48%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.48%   |
| Intel 82567V-4 Gigabit Network Connection                         | 2         | 0.48%   |
| Huawei MAR-LX1M                                                   | 2         | 0.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.48%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 390       | 53.5%   |
| WiFi     | 337       | 46.23%  |
| Modem    | 1         | 0.14%   |
| Unknown  | 1         | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 257       | 54.91%  |
| Ethernet | 211       | 45.09%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 243       | 54.24%  |
| 1     | 190       | 42.41%  |
| 0     | 9         | 2.01%   |
| 3     | 5         | 1.12%   |
| 4     | 1         | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 359       | 78.73%  |
| Yes  | 97        | 21.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 96        | 34.66%  |
| Realtek Semiconductor           | 54        | 19.49%  |
| Qualcomm Atheros Communications | 38        | 13.72%  |
| IMC Networks                    | 19        | 6.86%   |
| Cambridge Silicon Radio         | 15        | 5.42%   |
| Lite-On Technology              | 12        | 4.33%   |
| Toshiba                         | 8         | 2.89%   |
| Broadcom                        | 7         | 2.53%   |
| Ralink                          | 6         | 2.17%   |
| Foxconn / Hon Hai               | 5         | 1.81%   |
| Apple                           | 4         | 1.44%   |
| TP-Link                         | 3         | 1.08%   |
| Hewlett-Packard                 | 3         | 1.08%   |
| Dell                            | 2         | 0.72%   |
| TRENDnet                        | 1         | 0.36%   |
| Realtek                         | 1         | 0.36%   |
| Integrated System Solution      | 1         | 0.36%   |
| Foxconn International           | 1         | 0.36%   |
| Alps Electric                   | 1         | 0.36%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 33        | 11.91%  |
| Realtek  Bluetooth 4.2 Adapter                      | 26        | 9.39%   |
| Realtek Bluetooth Radio                             | 24        | 8.66%   |
| Qualcomm Atheros  Bluetooth Device                  | 23        | 8.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 22        | 7.94%   |
| Intel Bluetooth Device                              | 15        | 5.42%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 15        | 5.42%   |
| Intel AX200 Bluetooth                               | 12        | 4.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 2.53%   |
| IMC Networks Wireless_Device                        | 7         | 2.53%   |
| IMC Networks Bluetooth Radio                        | 7         | 2.53%   |
| Ralink RT3290 Bluetooth                             | 6         | 2.17%   |
| Toshiba Bluetooth Device                            | 5         | 1.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.44%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.44%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.44%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 1.44%   |
| IMC Networks Bluetooth Device                       | 4         | 1.44%   |
| TP-Link UB500 Adapter                               | 3         | 1.08%   |
| Lite-On Bluetooth Radio                             | 3         | 1.08%   |
| Lite-On Bluetooth Device                            | 3         | 1.08%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.08%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.72%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.72%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 0.72%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.72%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.72%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.72%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.72%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.72%   |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 0.72%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.72%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.72%   |
| Apple Bluetooth Host Controller                     | 2         | 0.72%   |
| TRENDnet TBW-108UB USB Adapter                      | 1         | 0.36%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.36%   |
| Toshiba BCM43142A0                                  | 1         | 0.36%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.36%   |
| Realtek Bluetooth Radio                             | 1         | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 305       | 52.41%  |
| AMD                              | 146       | 25.09%  |
| Nvidia                           | 95        | 16.32%  |
| C-Media Electronics              | 8         | 1.37%   |
| Logitech                         | 3         | 0.52%   |
| Kingston Technology              | 3         | 0.52%   |
| Generalplus Technology           | 3         | 0.52%   |
| Texas Instruments                | 2         | 0.34%   |
| Sony                             | 2         | 0.34%   |
| Microsoft                        | 2         | 0.34%   |
| GN Netcom                        | 2         | 0.34%   |
| BEHRINGER International          | 2         | 0.34%   |
| Tenx Technology                  | 1         | 0.17%   |
| Silicon Integrated Systems [SiS] | 1         | 0.17%   |
| Samson Technologies              | 1         | 0.17%   |
| Razer USA                        | 1         | 0.17%   |
| Pixart Imaging                   | 1         | 0.17%   |
| Panasonic (Matsushita)           | 1         | 0.17%   |
| Hewlett-Packard                  | 1         | 0.17%   |
| Creative Labs                    | 1         | 0.17%   |
| Chicony Electronics              | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 59        | 8.18%   |
| Intel Sunrise Point-LP HD Audio                                            | 45        | 6.24%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 34        | 4.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 29        | 4.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 25        | 3.47%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 23        | 3.19%   |
| AMD FCH Azalia Controller                                                  | 22        | 3.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17        | 2.36%   |
| Intel 8 Series HD Audio Controller                                         | 17        | 2.36%   |
| AMD Starship/Matisse HD Audio Controller                                   | 17        | 2.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 16        | 2.22%   |
| Intel Haswell-ULT HD Audio Controller                                      | 16        | 2.22%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 16        | 2.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14        | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13        | 1.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 13        | 1.8%    |
| Nvidia GF108 High Definition Audio Controller                              | 12        | 1.66%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 11        | 1.53%   |
| Intel Comet Lake PCH-LP cAVS                                               | 11        | 1.53%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 1.53%   |
| Intel Broadwell-U Audio Controller                                         | 11        | 1.53%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11        | 1.53%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 1.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 9         | 1.25%   |
| AMD Kabini HDMI/DP Audio                                                   | 9         | 1.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 8         | 1.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8         | 1.11%   |
| AMD Navi 10 HDMI Audio                                                     | 8         | 1.11%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7         | 0.97%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 0.97%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 7         | 0.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 7         | 0.97%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 0.97%   |
| Nvidia TU106 High Definition Audio Controller                              | 6         | 0.83%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 0.83%   |
| Nvidia Audio device                                                        | 6         | 0.83%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 0.83%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 0.69%   |
| Nvidia High Definition Audio Controller                                    | 5         | 0.69%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 76        | 24.28%  |
| Kingston                     | 71        | 22.68%  |
| SK hynix                     | 47        | 15.02%  |
| Micron Technology            | 36        | 11.5%   |
| Unknown                      | 19        | 6.07%   |
| Ramaxel Technology           | 11        | 3.51%   |
| Corsair                      | 9         | 2.88%   |
| Crucial                      | 8         | 2.56%   |
| Team                         | 7         | 2.24%   |
| Unknown (ABCD)               | 6         | 1.92%   |
| Hewlett-Packard              | 4         | 1.28%   |
| Elpida                       | 3         | 0.96%   |
| A-DATA Technology            | 3         | 0.96%   |
| Patriot                      | 2         | 0.64%   |
| Unknown (0x7FA8000000000000) | 1         | 0.32%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1         | 0.32%   |
| S                            | 1         | 0.32%   |
| Qumo                         | 1         | 0.32%   |
| Princeton                    | 1         | 0.32%   |
| Nanya Technology             | 1         | 0.32%   |
| M                            | 1         | 0.32%   |
| Kllisre                      | 1         | 0.32%   |
| Goldkey                      | 1         | 0.32%   |
| GeIL                         | 1         | 0.32%   |
| CSX                          | 1         | 0.32%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 1.74%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 6         | 1.74%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 1.45%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 5         | 1.45%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.45%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 1.45%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 4         | 1.16%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.16%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 1.16%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s              | 4         | 1.16%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.87%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.87%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 3         | 0.87%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.87%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 0.87%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.87%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 3         | 0.87%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.87%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.87%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.87%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 0.87%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.87%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 1600MT/s           | 3         | 0.87%   |
| Kingston RAM 99U5428-046.A00LF 4GB SODIMM DDR3 1600MT/s          | 3         | 0.87%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 0.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.58%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.58%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.58%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 2         | 0.58%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.58%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.58%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.58%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.58%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.58%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 2         | 0.58%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.58%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.58%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.58%   |
| Samsung RAM M378B5173EB0 4GB DIMM DDR3 1600MT/s                  | 2         | 0.58%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 118       | 47.39%  |
| DDR3    | 92        | 36.95%  |
| LPDDR4  | 12        | 4.82%   |
| DDR2    | 10        | 4.02%   |
| LPDDR3  | 5         | 2.01%   |
| SDRAM   | 4         | 1.61%   |
| Unknown | 4         | 1.61%   |
| DDR5    | 3         | 1.2%    |
| LPDDR5  | 1         | 0.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 156       | 62.65%  |
| DIMM         | 83        | 33.33%  |
| Row Of Chips | 9         | 3.61%   |
| Unknown      | 1         | 0.4%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 119       | 40.75%  |
| 4096  | 91        | 31.16%  |
| 16384 | 35        | 11.99%  |
| 2048  | 29        | 9.93%   |
| 32768 | 8         | 2.74%   |
| 1024  | 7         | 2.4%    |
| 512   | 3         | 1.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 59        | 20.42%  |
| 2667    | 51        | 17.65%  |
| 3200    | 47        | 16.26%  |
| 1333    | 22        | 7.61%   |
| 2400    | 21        | 7.27%   |
| 2133    | 15        | 5.19%   |
| 3466    | 8         | 2.77%   |
| 3266    | 6         | 2.08%   |
| 1334    | 6         | 2.08%   |
| Unknown | 6         | 2.08%   |
| 3733    | 4         | 1.38%   |
| 1867    | 4         | 1.38%   |
| 4800    | 3         | 1.04%   |
| 3400    | 3         | 1.04%   |
| 1067    | 3         | 1.04%   |
| 800     | 3         | 1.04%   |
| 533     | 3         | 1.04%   |
| 3534    | 2         | 0.69%   |
| 3000    | 2         | 0.69%   |
| 1800    | 2         | 0.69%   |
| 1066    | 2         | 0.69%   |
| 667     | 2         | 0.69%   |
| 5500    | 1         | 0.35%   |
| 4267    | 1         | 0.35%   |
| 4199    | 1         | 0.35%   |
| 3800    | 1         | 0.35%   |
| 3600    | 1         | 0.35%   |
| 3151    | 1         | 0.35%   |
| 3100    | 1         | 0.35%   |
| 2933    | 1         | 0.35%   |
| 2800    | 1         | 0.35%   |
| 2733    | 1         | 0.35%   |
| 2666    | 1         | 0.35%   |
| 2200    | 1         | 0.35%   |
| 2134    | 1         | 0.35%   |
| 1866    | 1         | 0.35%   |
| 400     | 1         | 0.35%   |

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
| Seiko Epson L3150 Series                      | 1         | 6.67%   |
| Seiko Epson ET-2810 Series                    | 1         | 6.67%   |
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
| Chicony Electronics                    | 60        | 19.87%  |
| IMC Networks                           | 29        | 9.6%    |
| Microdia                               | 28        | 9.27%   |
| Realtek Semiconductor                  | 21        | 6.95%   |
| Bison Electronics                      | 21        | 6.95%   |
| Syntek                                 | 18        | 5.96%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 5.3%    |
| Quanta                                 | 14        | 4.64%   |
| Suyin                                  | 12        | 3.97%   |
| Sunplus Innovation Technology          | 12        | 3.97%   |
| Lite-On Technology                     | 12        | 3.97%   |
| Logitech                               | 9         | 2.98%   |
| Microsoft                              | 5         | 1.66%   |
| Generalplus Technology                 | 5         | 1.66%   |
| Z-Star Microelectronics                | 4         | 1.32%   |
| Sonix Technology                       | 4         | 1.32%   |
| Luxvisions Innotech Limited            | 4         | 1.32%   |
| Importek                               | 4         | 1.32%   |
| Apple                                  | 4         | 1.32%   |
| Samsung Electronics                    | 3         | 0.99%   |
| Acer                                   | 3         | 0.99%   |
| Ricoh                                  | 2         | 0.66%   |
| Jieli Technology                       | 2         | 0.66%   |
| Cubeternet                             | 2         | 0.66%   |
| Alcor Micro                            | 2         | 0.66%   |
| Xiongmai                               | 1         | 0.33%   |
| ShineTech                              | 1         | 0.33%   |
| Aveo Technology                        | 1         | 0.33%   |
| ASUSTek Computer                       | 1         | 0.33%   |
| ANYKA                                  | 1         | 0.33%   |
| 8SSC20F27114V1SR0BK1X4S                | 1         | 0.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                                   | 12        | 3.95%   |
| Bison Integrated Camera                                                    | 9         | 2.96%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 8         | 2.63%   |
| Chicony Integrated Camera                                                  | 7         | 2.3%    |
| Microdia Webcam Vitade AF                                                  | 6         | 1.97%   |
| Chicony HP Truevision HD                                                   | 6         | 1.97%   |
| Chicony EasyCamera                                                         | 6         | 1.97%   |
| Realtek Integrated_Webcam_HD                                               | 5         | 1.64%   |
| Microdia Integrated_Webcam_HD                                              | 5         | 1.64%   |
| Lite-On Integrated Camera                                                  | 5         | 1.64%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 5         | 1.64%   |
| IMC Networks Integrated Camera                                             | 5         | 1.64%   |
| IMC Networks HP TrueVision HD Camera                                       | 5         | 1.64%   |
| Sunplus Integrated_Webcam_HD                                               | 4         | 1.32%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 4         | 1.32%   |
| Chicony USB2.0 HD UVC WebCam                                               | 4         | 1.32%   |
| Chicony TOSHIBA Web Camera - HD                                            | 4         | 1.32%   |
| Chicony HP TrueVision HD Camera                                            | 4         | 1.32%   |
| Chicony HD WebCam                                                          | 4         | 1.32%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 3         | 0.99%   |
| Realtek USB Camera                                                         | 3         | 0.99%   |
| Microdia USB 2.0 Camera                                                    | 3         | 0.99%   |
| Lite-On HP HD Camera                                                       | 3         | 0.99%   |
| Generalplus GENERAL WEBCAM                                                 | 3         | 0.99%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 0.99%   |
| Chicony HP Wide Vision HD Camera                                           | 3         | 0.99%   |
| Chicony HP HD Webcam                                                       | 3         | 0.99%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 3         | 0.99%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 0.99%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 3         | 0.99%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 3         | 0.99%   |
| Suyin 1.3M HD WebCam                                                       | 2         | 0.66%   |
| Sunplus Integrated Webcam                                                  | 2         | 0.66%   |
| Ricoh Sony Vaio Integrated Webcam                                          | 2         | 0.66%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 2         | 0.66%   |
| Realtek Integrated Webcam                                                  | 2         | 0.66%   |
| Realtek HP Wide Vision HD Camera                                           | 2         | 0.66%   |
| Quanta HP Wide Vision HD Camera                                            | 2         | 0.66%   |
| Quanta HP Webcam                                                           | 2         | 0.66%   |
| Quanta HP TrueVision HD Camera                                             | 2         | 0.66%   |

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
| Broadcom    | 6         | 37.5%   |
| Alcor Micro | 5         | 31.25%  |
| Upek        | 3         | 18.75%  |
| Yubico.com  | 1         | 6.25%   |
| O2 Micro    | 1         | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 31.25%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 18.75%  |
| Broadcom 5880                                                                | 3         | 18.75%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 12.5%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 6.25%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 328       | 71.77%  |
| 1     | 103       | 22.54%  |
| 2     | 21        | 4.6%    |
| 3     | 4         | 0.88%   |
| 5     | 1         | 0.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 51        | 33.55%  |
| Graphics card            | 33        | 21.71%  |
| Net/wireless             | 21        | 13.82%  |
| Chipcard                 | 13        | 8.55%   |
| Bluetooth                | 9         | 5.92%   |
| Multimedia controller    | 5         | 3.29%   |
| Sound                    | 4         | 2.63%   |
| Communication controller | 3         | 1.97%   |
| Card reader              | 3         | 1.97%   |
| Camera                   | 3         | 1.97%   |
| Storage                  | 2         | 1.32%   |
| Net/ethernet             | 2         | 1.32%   |
| Unassigned class         | 1         | 0.66%   |
| Network                  | 1         | 0.66%   |
| Firewire controller      | 1         | 0.66%   |


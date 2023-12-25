Linux in Slovakia - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Slovakia.

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

Total: 742

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProBook 4330s               | [fce67d52c0](https://linux-hardware.org/?probe=fce67d52c0) | Dec 22, 2023 |
| HP            | ProBook 450 G1              | [980f7dfed7](https://linux-hardware.org/?probe=980f7dfed7) | Dec 22, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [d33b5845ef](https://linux-hardware.org/?probe=d33b5845ef) | Dec 20, 2023 |
| Valve         | Jupiter                     | [6235a63aa5](https://linux-hardware.org/?probe=6235a63aa5) | Dec 17, 2023 |
| Dell          | Latitude E7450              | [f429af38c1](https://linux-hardware.org/?probe=f429af38c1) | Dec 17, 2023 |
| Apple         | MacBookAir7,2               | [5b6d840c0a](https://linux-hardware.org/?probe=5b6d840c0a) | Dec 12, 2023 |
| Dell          | Latitude 5400               | [b4317f7856](https://linux-hardware.org/?probe=b4317f7856) | Dec 11, 2023 |
| Acer          | Extensa 5630                | [4709657363](https://linux-hardware.org/?probe=4709657363) | Dec 11, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [2a22b3adb4](https://linux-hardware.org/?probe=2a22b3adb4) | Dec 10, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [8395e5f595](https://linux-hardware.org/?probe=8395e5f595) | Dec 08, 2023 |
| ASUSTek       | K54C                        | [8f1abfdd9a](https://linux-hardware.org/?probe=8f1abfdd9a) | Dec 03, 2023 |
| ASUSTek       | K54C                        | [6702d5257d](https://linux-hardware.org/?probe=6702d5257d) | Dec 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [0869816e7a](https://linux-hardware.org/?probe=0869816e7a) | Dec 02, 2023 |
| HP            | Pavilion dv6                | [6c2a58400d](https://linux-hardware.org/?probe=6c2a58400d) | Dec 01, 2023 |
| HP            | Pavilion dv6                | [6ee138ba11](https://linux-hardware.org/?probe=6ee138ba11) | Dec 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [9d88b4ad0b](https://linux-hardware.org/?probe=9d88b4ad0b) | Nov 28, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [f813230b08](https://linux-hardware.org/?probe=f813230b08) | Nov 27, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [23d18fc15e](https://linux-hardware.org/?probe=23d18fc15e) | Nov 27, 2023 |
| Lenovo        | ThinkPad L480 20LS0015UK    | [5f786955fc](https://linux-hardware.org/?probe=5f786955fc) | Nov 26, 2023 |
| MSI           | GT60 2OC/2OD                | [11086675c9](https://linux-hardware.org/?probe=11086675c9) | Nov 26, 2023 |
| HP            | Pavilion dv6                | [2f757867e7](https://linux-hardware.org/?probe=2f757867e7) | Nov 26, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [41443f69e3](https://linux-hardware.org/?probe=41443f69e3) | Nov 26, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [5a01c502bd](https://linux-hardware.org/?probe=5a01c502bd) | Nov 24, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | [8806cbd1e7](https://linux-hardware.org/?probe=8806cbd1e7) | Nov 23, 2023 |
| ASUSTek       | X555LN                      | [e2f9466842](https://linux-hardware.org/?probe=e2f9466842) | Nov 19, 2023 |
| UMAX          | 13Wa_Flex                   | [621a71f736](https://linux-hardware.org/?probe=621a71f736) | Nov 19, 2023 |
| Lenovo        | 3000 V100 076346G           | [039632f3f3](https://linux-hardware.org/?probe=039632f3f3) | Nov 18, 2023 |
| MSI           | GT60 2OC/2OD                | [a29bea944f](https://linux-hardware.org/?probe=a29bea944f) | Nov 16, 2023 |
| MSI           | GT60 2OC/2OD                | [3648bc5b55](https://linux-hardware.org/?probe=3648bc5b55) | Nov 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [2a8696e0f5](https://linux-hardware.org/?probe=2a8696e0f5) | Nov 10, 2023 |
| HP            | 255 15.6 inch G10 Notebo... | [df5983435c](https://linux-hardware.org/?probe=df5983435c) | Nov 08, 2023 |
| Dell          | Latitude E7270              | [0410c1ba06](https://linux-hardware.org/?probe=0410c1ba06) | Nov 08, 2023 |
| Lenovo        | ThinkPad P16v Gen 1 21FE... | [d0d84fed9a](https://linux-hardware.org/?probe=d0d84fed9a) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [c07d28d9bc](https://linux-hardware.org/?probe=c07d28d9bc) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [00cab2c4d1](https://linux-hardware.org/?probe=00cab2c4d1) | Nov 04, 2023 |
| HP            | Pavilion dv6                | [bf6361ff84](https://linux-hardware.org/?probe=bf6361ff84) | Nov 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [0b00fd801c](https://linux-hardware.org/?probe=0b00fd801c) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [7c297acb1f](https://linux-hardware.org/?probe=7c297acb1f) | Nov 01, 2023 |
| Lenovo        | ThinkPad T490 20N3000FRT    | [14710d3709](https://linux-hardware.org/?probe=14710d3709) | Oct 31, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [b553bb2a36](https://linux-hardware.org/?probe=b553bb2a36) | Oct 31, 2023 |
| Dell          | Latitude E7250              | [a83b95ce44](https://linux-hardware.org/?probe=a83b95ce44) | Oct 30, 2023 |
| Lenovo        | B575 Brazos                 | [189361193e](https://linux-hardware.org/?probe=189361193e) | Oct 29, 2023 |
| HP            | 250 15.6 inch G10 Notebo... | [f5f8e6f37d](https://linux-hardware.org/?probe=f5f8e6f37d) | Oct 21, 2023 |
| HP            | ProBook 4535s               | [e52e92c95b](https://linux-hardware.org/?probe=e52e92c95b) | Oct 14, 2023 |
| MSI           | GT60 2OC/2OD                | [1d1d1e17eb](https://linux-hardware.org/?probe=1d1d1e17eb) | Oct 11, 2023 |
| MSI           | GT60 2OC/2OD                | [12d88836d5](https://linux-hardware.org/?probe=12d88836d5) | Oct 11, 2023 |
| Sony          | VPCEJ1L1E                   | [a51252de41](https://linux-hardware.org/?probe=a51252de41) | Oct 03, 2023 |
| MSI           | MS-1651 Ver                 | [7450925b18](https://linux-hardware.org/?probe=7450925b18) | Oct 02, 2023 |
| Acer          | Aspire A315-24P             | [f8033479b2](https://linux-hardware.org/?probe=f8033479b2) | Oct 02, 2023 |
| Dell          | Latitude E7270              | [bf1def4fc3](https://linux-hardware.org/?probe=bf1def4fc3) | Oct 01, 2023 |
| Packard Be... | DOT S                       | [ccf952e34c](https://linux-hardware.org/?probe=ccf952e34c) | Sep 28, 2023 |
| HP            | Notebook                    | [b13debd2fa](https://linux-hardware.org/?probe=b13debd2fa) | Sep 27, 2023 |
| Acer          | Aspire A315-510P            | [794f8f35c8](https://linux-hardware.org/?probe=794f8f35c8) | Sep 25, 2023 |
| Acer          | Aspire A315-510P            | [89ba5bd7dd](https://linux-hardware.org/?probe=89ba5bd7dd) | Sep 25, 2023 |
| MSI           | MS-1651 Ver                 | [93cfb04861](https://linux-hardware.org/?probe=93cfb04861) | Sep 23, 2023 |
| MSI           | MS-1651 Ver                 | [e71155ca01](https://linux-hardware.org/?probe=e71155ca01) | Sep 23, 2023 |
| Acer          | Aspire 5732Z                | [c86094eac8](https://linux-hardware.org/?probe=c86094eac8) | Sep 23, 2023 |
| MSI           | GT60 2OC/2OD                | [0b5a8a95dc](https://linux-hardware.org/?probe=0b5a8a95dc) | Sep 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [ed4753b8e2](https://linux-hardware.org/?probe=ed4753b8e2) | Sep 21, 2023 |
| Acer          | Aspire E1-531               | [f0173f0458](https://linux-hardware.org/?probe=f0173f0458) | Sep 20, 2023 |
| Lenovo        | ThinkPad P50 20EQS0VV2S     | [b7d1f6f3cf](https://linux-hardware.org/?probe=b7d1f6f3cf) | Sep 20, 2023 |
| Acer          | Aspire 5750ZG               | [c9ce4cde54](https://linux-hardware.org/?probe=c9ce4cde54) | Sep 13, 2023 |
| Acer          | Aspire 5750ZG               | [9029730ffb](https://linux-hardware.org/?probe=9029730ffb) | Sep 12, 2023 |
| HP            | ProBook 4740s               | [7166a2d286](https://linux-hardware.org/?probe=7166a2d286) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [dbad37486d](https://linux-hardware.org/?probe=dbad37486d) | Sep 11, 2023 |
| HUAWEI        | MACHC-WAX9                  | [5dde8dd026](https://linux-hardware.org/?probe=5dde8dd026) | Sep 08, 2023 |
| HP            | ProBook 455 G7              | [7ae653c6c1](https://linux-hardware.org/?probe=7ae653c6c1) | Sep 05, 2023 |
| HP            | ZBook 15 G3                 | [faac131992](https://linux-hardware.org/?probe=faac131992) | Sep 05, 2023 |
| HP            | Pavilion dv6                | [cf6a67d073](https://linux-hardware.org/?probe=cf6a67d073) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | [9ab1a9731d](https://linux-hardware.org/?probe=9ab1a9731d) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | [78d7ccad98](https://linux-hardware.org/?probe=78d7ccad98) | Sep 02, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [db2e607ae6](https://linux-hardware.org/?probe=db2e607ae6) | Sep 02, 2023 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | [d70ba1aaf4](https://linux-hardware.org/?probe=d70ba1aaf4) | Sep 01, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [6f5bafed6c](https://linux-hardware.org/?probe=6f5bafed6c) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [48450e1a26](https://linux-hardware.org/?probe=48450e1a26) | Aug 29, 2023 |
| MSI           | GT60 2OC/2OD                | [998ee50b04](https://linux-hardware.org/?probe=998ee50b04) | Aug 27, 2023 |
| Toshiba       | Satellite P770              | [8618c83c93](https://linux-hardware.org/?probe=8618c83c93) | Aug 26, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [475563b8b4](https://linux-hardware.org/?probe=475563b8b4) | Aug 24, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [7975d95ea8](https://linux-hardware.org/?probe=7975d95ea8) | Aug 21, 2023 |
| MSI           | GT60 2OC/2OD                | [e610051fdc](https://linux-hardware.org/?probe=e610051fdc) | Aug 20, 2023 |
| HP            | Pavilion dv6                | [a6d62bc041](https://linux-hardware.org/?probe=a6d62bc041) | Aug 18, 2023 |
| Lenovo        | ThinkPad X200 7459Y8Y       | [3a707993c2](https://linux-hardware.org/?probe=3a707993c2) | Aug 16, 2023 |
| Lenovo        | ThinkPad X200 7459Y8Y       | [2f98dd0ac1](https://linux-hardware.org/?probe=2f98dd0ac1) | Aug 16, 2023 |
| HP            | Pavilion g7                 | [43351d6476](https://linux-hardware.org/?probe=43351d6476) | Aug 12, 2023 |
| Acer          | Extensa 5220                | [92605dd73d](https://linux-hardware.org/?probe=92605dd73d) | Aug 12, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | [30c7051967](https://linux-hardware.org/?probe=30c7051967) | Aug 11, 2023 |
| HP            | ProBook 4330s               | [5c854bed9f](https://linux-hardware.org/?probe=5c854bed9f) | Aug 09, 2023 |
| HP            | ProBook 4330s               | [d23ce497d2](https://linux-hardware.org/?probe=d23ce497d2) | Aug 09, 2023 |
| ASUSTek       | F3L                         | [b97c082eff](https://linux-hardware.org/?probe=b97c082eff) | Aug 09, 2023 |
| ASUSTek       | G750JW                      | [fe527d6231](https://linux-hardware.org/?probe=fe527d6231) | Aug 08, 2023 |
| ASUSTek       | 1001P                       | [b4326c3c45](https://linux-hardware.org/?probe=b4326c3c45) | Aug 08, 2023 |
| HP            | Laptop 15s-eq2xxx           | [4a4ac95dcc](https://linux-hardware.org/?probe=4a4ac95dcc) | Aug 01, 2023 |
| Dell          | Latitude 3510               | [8bfe0fe5fb](https://linux-hardware.org/?probe=8bfe0fe5fb) | Jul 30, 2023 |
| Dell          | Latitude E5570              | [1f9be76313](https://linux-hardware.org/?probe=1f9be76313) | Jul 30, 2023 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [451cbfaee5](https://linux-hardware.org/?probe=451cbfaee5) | Jul 29, 2023 |
| Dell          | Latitude 5290 2-in-1        | [26f325a346](https://linux-hardware.org/?probe=26f325a346) | Jul 23, 2023 |
| ASUSTek       | X505BA                      | [fcd96492f0](https://linux-hardware.org/?probe=fcd96492f0) | Jul 17, 2023 |
| Toshiba       | Satellite C650              | [252f8adf16](https://linux-hardware.org/?probe=252f8adf16) | Jul 15, 2023 |
| Lenovo        | ThinkPad T460s 20FAS42W0... | [add1dac3cb](https://linux-hardware.org/?probe=add1dac3cb) | Jul 11, 2023 |
| ASUSTek       | N61Vn                       | [6bbb5b2105](https://linux-hardware.org/?probe=6bbb5b2105) | Jul 10, 2023 |
| ASUSTek       | N61Vn                       | [dd1a0f1acf](https://linux-hardware.org/?probe=dd1a0f1acf) | Jul 10, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [68daff498d](https://linux-hardware.org/?probe=68daff498d) | Jul 02, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [f587b9a46c](https://linux-hardware.org/?probe=f587b9a46c) | Jul 02, 2023 |
| HP            | Pavilion g6                 | [ec6a70b7d4](https://linux-hardware.org/?probe=ec6a70b7d4) | Jun 27, 2023 |
| HUAWEI        | NBD-WXX9                    | [4e7d62b30a](https://linux-hardware.org/?probe=4e7d62b30a) | Jun 21, 2023 |
| Acer          | Aspire VN7-792G             | [ab55f9b492](https://linux-hardware.org/?probe=ab55f9b492) | Jun 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5141d5dd1a](https://linux-hardware.org/?probe=5141d5dd1a) | Jun 15, 2023 |
| Dell          | XPS 15 9510                 | [9a8a71741e](https://linux-hardware.org/?probe=9a8a71741e) | Jun 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [5349772ea1](https://linux-hardware.org/?probe=5349772ea1) | Jun 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c0d6d68272](https://linux-hardware.org/?probe=c0d6d68272) | Jun 12, 2023 |
| MSI           | GT60 2OC/2OD                | [f5a1226b72](https://linux-hardware.org/?probe=f5a1226b72) | Jun 12, 2023 |
| Toshiba       | Satellite C660D             | [a6c222681d](https://linux-hardware.org/?probe=a6c222681d) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | [7381bd00f3](https://linux-hardware.org/?probe=7381bd00f3) | Jun 07, 2023 |
| MSI           | GT60 2OC/2OD                | [ed3b6abc56](https://linux-hardware.org/?probe=ed3b6abc56) | Jun 05, 2023 |
| Dell          | Latitude E4300              | [cfd95b7e5e](https://linux-hardware.org/?probe=cfd95b7e5e) | Jun 05, 2023 |
| Lenovo        | ThinkPad X61 76738AG        | [7f52d18c2f](https://linux-hardware.org/?probe=7f52d18c2f) | May 30, 2023 |
| Dell          | Latitude E5430 non-vPro     | [278fefa10a](https://linux-hardware.org/?probe=278fefa10a) | May 24, 2023 |
| Dell          | Latitude E5430 non-vPro     | [6ab7e9c82d](https://linux-hardware.org/?probe=6ab7e9c82d) | May 23, 2023 |
| Lenovo        | ThinkPad T410s 2904FAG      | [742f2c09c5](https://linux-hardware.org/?probe=742f2c09c5) | May 21, 2023 |
| HP            | EliteBook 2570p             | [60ec2d6e04](https://linux-hardware.org/?probe=60ec2d6e04) | May 21, 2023 |
| Dell          | Latitude E5430 non-vPro     | [51827f5ae5](https://linux-hardware.org/?probe=51827f5ae5) | May 19, 2023 |
| MSI           | GF63 Thin 11SC              | [89e05e4477](https://linux-hardware.org/?probe=89e05e4477) | May 17, 2023 |
| Dell          | Latitude E5430 non-vPro     | [a1fb71ff2f](https://linux-hardware.org/?probe=a1fb71ff2f) | May 17, 2023 |
| Hampoo        | Cherry Trail CR V200        | [1167f27914](https://linux-hardware.org/?probe=1167f27914) | May 15, 2023 |
| Samsung       | R530/R730/P530              | [9f619133b7](https://linux-hardware.org/?probe=9f619133b7) | May 15, 2023 |
| HP            | Pavilion dv6                | [733703c761](https://linux-hardware.org/?probe=733703c761) | May 09, 2023 |
| ASUSTek       | X553MA                      | [4ab42c06ea](https://linux-hardware.org/?probe=4ab42c06ea) | May 09, 2023 |
| ASUSTek       | X553MA                      | [0952e2922b](https://linux-hardware.org/?probe=0952e2922b) | May 09, 2023 |
| Apple         | MacBook3,1                  | [fca1201c9f](https://linux-hardware.org/?probe=fca1201c9f) | May 07, 2023 |
| HP            | Pavilion g6                 | [d6e340501e](https://linux-hardware.org/?probe=d6e340501e) | May 07, 2023 |
| HP            | ProBook 445 G7              | [c78f20f332](https://linux-hardware.org/?probe=c78f20f332) | May 06, 2023 |
| HP            | Pavilion g6                 | [6c8f0f4521](https://linux-hardware.org/?probe=6c8f0f4521) | May 06, 2023 |
| MSI           | GT60 2OC/2OD                | [8754e79840](https://linux-hardware.org/?probe=8754e79840) | May 04, 2023 |
| Lenovo        | Z50-75 80EC                 | [af5d37f4f7](https://linux-hardware.org/?probe=af5d37f4f7) | Apr 30, 2023 |
| Lenovo        | G50-30 80G0                 | [c8d8595af5](https://linux-hardware.org/?probe=c8d8595af5) | Apr 29, 2023 |
| Dell          | Vostro 3500                 | [7719e2a6c9](https://linux-hardware.org/?probe=7719e2a6c9) | Apr 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [e0f4a4d0f4](https://linux-hardware.org/?probe=e0f4a4d0f4) | Apr 26, 2023 |
| Dell          | Latitude E5570              | [1a6b35e077](https://linux-hardware.org/?probe=1a6b35e077) | Apr 22, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [040d876c1e](https://linux-hardware.org/?probe=040d876c1e) | Apr 16, 2023 |
| MSI           | GT60 2OC/2OD                | [2a389c9c58](https://linux-hardware.org/?probe=2a389c9c58) | Apr 16, 2023 |
| MSI           | GT60 2OC/2OD                | [af0678336d](https://linux-hardware.org/?probe=af0678336d) | Apr 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | [abedf2741f](https://linux-hardware.org/?probe=abedf2741f) | Apr 12, 2023 |
| Acer          | Swift SF314-43              | [95cf4404c3](https://linux-hardware.org/?probe=95cf4404c3) | Apr 08, 2023 |
| Dell          | Latitude E5570              | [7d6ff0e0d8](https://linux-hardware.org/?probe=7d6ff0e0d8) | Apr 07, 2023 |
| Acer          | Aspire E1-532               | [ba90a2c123](https://linux-hardware.org/?probe=ba90a2c123) | Apr 05, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [c529f9d1cc](https://linux-hardware.org/?probe=c529f9d1cc) | Apr 03, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [b9a98e8656](https://linux-hardware.org/?probe=b9a98e8656) | Apr 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [3034a3d11a](https://linux-hardware.org/?probe=3034a3d11a) | Apr 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [2f2326e574](https://linux-hardware.org/?probe=2f2326e574) | Apr 02, 2023 |
| HP            | 250 G7 Notebook PC          | [fcb8359930](https://linux-hardware.org/?probe=fcb8359930) | Mar 28, 2023 |
| HP            | 250 G7 Notebook PC          | [2558605a4b](https://linux-hardware.org/?probe=2558605a4b) | Mar 28, 2023 |
| Toshiba       | Satellite C855-1TT          | [ac8e41d993](https://linux-hardware.org/?probe=ac8e41d993) | Mar 27, 2023 |
| Valve         | Jupiter                     | [3ad7937aaf](https://linux-hardware.org/?probe=3ad7937aaf) | Mar 26, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c17f20a679](https://linux-hardware.org/?probe=c17f20a679) | Mar 23, 2023 |
| HP            | ProBook 6470b               | [dd23ab1a2e](https://linux-hardware.org/?probe=dd23ab1a2e) | Mar 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | [1ca9befb7a](https://linux-hardware.org/?probe=1ca9befb7a) | Mar 18, 2023 |
| HP            | Pavilion dv6                | [9c24401930](https://linux-hardware.org/?probe=9c24401930) | Mar 18, 2023 |
| Lenovo        | ThinkPad T590 20N4000DXS    | [c145898fae](https://linux-hardware.org/?probe=c145898fae) | Mar 17, 2023 |
| Lenovo        | ThinkPad T590 20N4000DXS    | [293fe8b4ab](https://linux-hardware.org/?probe=293fe8b4ab) | Mar 17, 2023 |
| HP            | EliteBook 2570p             | [374bab39d7](https://linux-hardware.org/?probe=374bab39d7) | Mar 17, 2023 |
| MSI           | CR500                       | [28eeb3bd71](https://linux-hardware.org/?probe=28eeb3bd71) | Mar 16, 2023 |
| Dell          | Latitude 5580               | [819b5d8dc2](https://linux-hardware.org/?probe=819b5d8dc2) | Mar 14, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | [ae9f2da5a4](https://linux-hardware.org/?probe=ae9f2da5a4) | Mar 14, 2023 |
| Acer          | Aspire VN7-791              | [ca10594901](https://linux-hardware.org/?probe=ca10594901) | Mar 12, 2023 |
| ASUSTek       | X541SA                      | [4adcb5ab0f](https://linux-hardware.org/?probe=4adcb5ab0f) | Mar 08, 2023 |
| Acer          | Aspire VN7-792G             | [3b4a3b74a1](https://linux-hardware.org/?probe=3b4a3b74a1) | Mar 07, 2023 |
| Lenovo        | G505s 20255                 | [b338e704d9](https://linux-hardware.org/?probe=b338e704d9) | Mar 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [925e02d1dc](https://linux-hardware.org/?probe=925e02d1dc) | Mar 04, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [7d9acf8639](https://linux-hardware.org/?probe=7d9acf8639) | Mar 04, 2023 |
| HP            | 255 G8 Notebook PC          | [0c76255503](https://linux-hardware.org/?probe=0c76255503) | Mar 04, 2023 |
| HP            | Pavilion 11 x360 PC         | [a7860ee046](https://linux-hardware.org/?probe=a7860ee046) | Mar 04, 2023 |
| HP            | Pavilion 11 x360 PC         | [82847b3b1f](https://linux-hardware.org/?probe=82847b3b1f) | Mar 02, 2023 |
| Google        | Voxel                       | [ce917fe8ec](https://linux-hardware.org/?probe=ce917fe8ec) | Feb 25, 2023 |
| Google        | Voxel                       | [93ea143f69](https://linux-hardware.org/?probe=93ea143f69) | Feb 25, 2023 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | [faeee1c46c](https://linux-hardware.org/?probe=faeee1c46c) | Feb 24, 2023 |
| HP            | ProBook 4540s               | [cc3e78f73f](https://linux-hardware.org/?probe=cc3e78f73f) | Feb 18, 2023 |
| Medion        | P651x series                | [23b3fb7ce5](https://linux-hardware.org/?probe=23b3fb7ce5) | Feb 16, 2023 |
| HP            | Pavilion 11 x360 PC         | [b2a1267353](https://linux-hardware.org/?probe=b2a1267353) | Feb 15, 2023 |
| HP            | ProBook 4340s               | [caed0e9f2d](https://linux-hardware.org/?probe=caed0e9f2d) | Feb 13, 2023 |
| Lenovo        | IdeaPad Y580                | [f396fdb21f](https://linux-hardware.org/?probe=f396fdb21f) | Feb 05, 2023 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [bac184b151](https://linux-hardware.org/?probe=bac184b151) | Feb 04, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E1S    | [3f3e5b3a1e](https://linux-hardware.org/?probe=3f3e5b3a1e) | Feb 03, 2023 |
| Dell          | Vostro 5481                 | [40bc04540d](https://linux-hardware.org/?probe=40bc04540d) | Feb 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [1cfa73407d](https://linux-hardware.org/?probe=1cfa73407d) | Jan 31, 2023 |
| HP            | 255 G8 Notebook PC          | [d8e161e2b0](https://linux-hardware.org/?probe=d8e161e2b0) | Jan 25, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [e589b4bd78](https://linux-hardware.org/?probe=e589b4bd78) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | [92a3e34781](https://linux-hardware.org/?probe=92a3e34781) | Jan 24, 2023 |
| Acer          | Aspire E3-111               | [fde7baf9e8](https://linux-hardware.org/?probe=fde7baf9e8) | Jan 19, 2023 |
| Dell          | Inspiron 5770               | [64976ae263](https://linux-hardware.org/?probe=64976ae263) | Jan 19, 2023 |
| PC Special... | Recoil II RTX               | [33850c8810](https://linux-hardware.org/?probe=33850c8810) | Jan 16, 2023 |
| Dell          | Precision 7520              | [c57fdfbe1e](https://linux-hardware.org/?probe=c57fdfbe1e) | Jan 15, 2023 |
| HUAWEI        | KLVL-WXX9                   | [2687f89612](https://linux-hardware.org/?probe=2687f89612) | Jan 14, 2023 |
| Dell          | Latitude E6410              | [a11818f59a](https://linux-hardware.org/?probe=a11818f59a) | Jan 13, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | [22d0c82134](https://linux-hardware.org/?probe=22d0c82134) | Jan 12, 2023 |
| ASUSTek       | G53SX                       | [ef2d9747e2](https://linux-hardware.org/?probe=ef2d9747e2) | Jan 12, 2023 |
| HP            | ProBook 6450b               | [0ae783d261](https://linux-hardware.org/?probe=0ae783d261) | Jan 11, 2023 |
| Dell          | XPS 15 9570                 | [8032d8e1be](https://linux-hardware.org/?probe=8032d8e1be) | Jan 07, 2023 |
| MSI           | Prestige 14 A10RAS          | [fc119df9bc](https://linux-hardware.org/?probe=fc119df9bc) | Jan 02, 2023 |
| Dell          | Latitude E5500              | [f04cd8f466](https://linux-hardware.org/?probe=f04cd8f466) | Dec 31, 2022 |
| Dell          | Latitude E5500              | [24a0ca1b65](https://linux-hardware.org/?probe=24a0ca1b65) | Dec 31, 2022 |
| Google        | Voxel                       | [430244f188](https://linux-hardware.org/?probe=430244f188) | Dec 28, 2022 |
| ASUSTek       | K52Je                       | [28cac9b262](https://linux-hardware.org/?probe=28cac9b262) | Dec 27, 2022 |
| Acer          | Swift SF314-43              | [3d9a51ce6e](https://linux-hardware.org/?probe=3d9a51ce6e) | Dec 27, 2022 |
| Dell          | Latitude 3510               | [ac931934de](https://linux-hardware.org/?probe=ac931934de) | Dec 27, 2022 |
| Dell          | Latitude 3510               | [5db1cf6cb6](https://linux-hardware.org/?probe=5db1cf6cb6) | Dec 27, 2022 |
| Samsung       | 270E5G/270E5U               | [705baed85a](https://linux-hardware.org/?probe=705baed85a) | Dec 26, 2022 |
| ASUSTek       | K52Je                       | [dc13c122ed](https://linux-hardware.org/?probe=dc13c122ed) | Dec 26, 2022 |
| HP            | Pavilion g6                 | [71d7947da6](https://linux-hardware.org/?probe=71d7947da6) | Dec 24, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [30c3f8d777](https://linux-hardware.org/?probe=30c3f8d777) | Dec 21, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [0d273375d6](https://linux-hardware.org/?probe=0d273375d6) | Dec 18, 2022 |
| HP            | Pavilion g6                 | [b5662e5fec](https://linux-hardware.org/?probe=b5662e5fec) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c715acf0ea](https://linux-hardware.org/?probe=c715acf0ea) | Dec 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [18b2579f75](https://linux-hardware.org/?probe=18b2579f75) | Dec 09, 2022 |
| HP            | Pavilion g6                 | [d2b43c2803](https://linux-hardware.org/?probe=d2b43c2803) | Dec 05, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | [fa46f1d34a](https://linux-hardware.org/?probe=fa46f1d34a) | Dec 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c0f7c4b788](https://linux-hardware.org/?probe=c0f7c4b788) | Dec 03, 2022 |
| Google        | Voxel                       | [b64ebf7db7](https://linux-hardware.org/?probe=b64ebf7db7) | Dec 03, 2022 |
| HP            | 620                         | [6be09298b6](https://linux-hardware.org/?probe=6be09298b6) | Dec 01, 2022 |
| HUAWEI        | KLVL-WXX9                   | [af7d162434](https://linux-hardware.org/?probe=af7d162434) | Nov 28, 2022 |
| Dell          | XPS 15 7590                 | [2355853fda](https://linux-hardware.org/?probe=2355853fda) | Nov 23, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [326b5bad4c](https://linux-hardware.org/?probe=326b5bad4c) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d7992855ba](https://linux-hardware.org/?probe=d7992855ba) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [8e17476123](https://linux-hardware.org/?probe=8e17476123) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f48e29fef2](https://linux-hardware.org/?probe=f48e29fef2) | Nov 16, 2022 |
| Acer          | Aspire VN7-791              | [736c2f5664](https://linux-hardware.org/?probe=736c2f5664) | Nov 14, 2022 |
| Lenovo        | V14-IIL 82C4                | [ca336329c8](https://linux-hardware.org/?probe=ca336329c8) | Nov 12, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [4f40815737](https://linux-hardware.org/?probe=4f40815737) | Nov 12, 2022 |
| GPD           | G1619-04                    | [cf4cb47a12](https://linux-hardware.org/?probe=cf4cb47a12) | Nov 09, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [87cfe8ed2e](https://linux-hardware.org/?probe=87cfe8ed2e) | Oct 11, 2022 |
| HP            | ENVY Laptop 13-ad0xx        | [52658eb393](https://linux-hardware.org/?probe=52658eb393) | Oct 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [19c7d98b00](https://linux-hardware.org/?probe=19c7d98b00) | Oct 06, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [72163c289e](https://linux-hardware.org/?probe=72163c289e) | Oct 05, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [97d1b5e6c5](https://linux-hardware.org/?probe=97d1b5e6c5) | Sep 30, 2022 |
| Dell          | Vostro 5391                 | [61a25cdb83](https://linux-hardware.org/?probe=61a25cdb83) | Sep 28, 2022 |
| ASUSTek       | K55VJ                       | [8e87d041c3](https://linux-hardware.org/?probe=8e87d041c3) | Sep 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [afd66066bc](https://linux-hardware.org/?probe=afd66066bc) | Sep 21, 2022 |
| Lenovo        | G780                        | [04f924450d](https://linux-hardware.org/?probe=04f924450d) | Sep 17, 2022 |
| Valve         | Jupiter                     | [1dc4620833](https://linux-hardware.org/?probe=1dc4620833) | Sep 10, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [ecaa040ba1](https://linux-hardware.org/?probe=ecaa040ba1) | Sep 04, 2022 |
| Dell          | Latitude 3510               | [9477575b26](https://linux-hardware.org/?probe=9477575b26) | Sep 03, 2022 |
| UMAX          | VisionBook 14Wr Plus        | [6a2cb26049](https://linux-hardware.org/?probe=6a2cb26049) | Sep 02, 2022 |
| Toshiba       | TECRA S5                    | [121c8e110b](https://linux-hardware.org/?probe=121c8e110b) | Aug 31, 2022 |
| Toshiba       | TECRA S5                    | [6ec2bd9539](https://linux-hardware.org/?probe=6ec2bd9539) | Aug 31, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c407e3a17c](https://linux-hardware.org/?probe=c407e3a17c) | Aug 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [4b56f15871](https://linux-hardware.org/?probe=4b56f15871) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [dd415db306](https://linux-hardware.org/?probe=dd415db306) | Aug 28, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [8756581baa](https://linux-hardware.org/?probe=8756581baa) | Aug 21, 2022 |
| Samsung       | NC210/NC110                 | [3dcdc1dc6a](https://linux-hardware.org/?probe=3dcdc1dc6a) | Aug 15, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [1bcc13e6b4](https://linux-hardware.org/?probe=1bcc13e6b4) | Aug 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9a06c0c10c](https://linux-hardware.org/?probe=9a06c0c10c) | Aug 09, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [7e5a0c0004](https://linux-hardware.org/?probe=7e5a0c0004) | Aug 06, 2022 |
| Acer          | Aspire VN7-791G             | [3e72040097](https://linux-hardware.org/?probe=3e72040097) | Jul 31, 2022 |
| Dell          | XPS 15 9570                 | [e7f56631b1](https://linux-hardware.org/?probe=e7f56631b1) | Jul 27, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [b4a9542143](https://linux-hardware.org/?probe=b4a9542143) | Jul 27, 2022 |
| Dell          | XPS 15 9570                 | [f3972b3a7d](https://linux-hardware.org/?probe=f3972b3a7d) | Jul 26, 2022 |
| HP            | ProBook 440 G3              | [04b2ed9273](https://linux-hardware.org/?probe=04b2ed9273) | Jul 19, 2022 |
| UMAX          | VisionBook-N12R             | [9ccb1f57ab](https://linux-hardware.org/?probe=9ccb1f57ab) | Jul 16, 2022 |
| HP            | ProBook 440 G3              | [c546e3b537](https://linux-hardware.org/?probe=c546e3b537) | Jul 13, 2022 |
| ASUSTek       | N550JK                      | [bc0c9431e1](https://linux-hardware.org/?probe=bc0c9431e1) | Jul 04, 2022 |
| ASUSTek       | N550JK                      | [539ce50149](https://linux-hardware.org/?probe=539ce50149) | Jul 04, 2022 |
| MSI           | EX705                       | [d85dfacff5](https://linux-hardware.org/?probe=d85dfacff5) | Jun 30, 2022 |
| MSI           | EX705                       | [3de108279f](https://linux-hardware.org/?probe=3de108279f) | Jun 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [5ebcb2f152](https://linux-hardware.org/?probe=5ebcb2f152) | Jun 29, 2022 |
| HP            | ZBook 15 G6                 | [2e4663e8c3](https://linux-hardware.org/?probe=2e4663e8c3) | Jun 22, 2022 |
| HP            | Pavilion dv6                | [1ba5e6c491](https://linux-hardware.org/?probe=1ba5e6c491) | Jun 18, 2022 |
| Dell          | Latitude 3510               | [4b6e3aeb9e](https://linux-hardware.org/?probe=4b6e3aeb9e) | Jun 16, 2022 |
| Dell          | Latitude E5570              | [ce4d3bb373](https://linux-hardware.org/?probe=ce4d3bb373) | Jun 09, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [fdda1deb12](https://linux-hardware.org/?probe=fdda1deb12) | Jun 07, 2022 |
| Valve         | Jupiter                     | [cc0a20bb93](https://linux-hardware.org/?probe=cc0a20bb93) | Jun 06, 2022 |
| Dell          | Latitude E6440              | [dd05b883a6](https://linux-hardware.org/?probe=dd05b883a6) | Jun 04, 2022 |
| Dell          | Vostro 5515                 | [ae8649e10b](https://linux-hardware.org/?probe=ae8649e10b) | May 28, 2022 |
| MSI           | GT60 2OC/2OD                | [c3b5eb704d](https://linux-hardware.org/?probe=c3b5eb704d) | May 22, 2022 |
| MSI           | GT60 2OC/2OD                | [96f6fda5d5](https://linux-hardware.org/?probe=96f6fda5d5) | May 22, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [0793a5608a](https://linux-hardware.org/?probe=0793a5608a) | May 15, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [d8361f7895](https://linux-hardware.org/?probe=d8361f7895) | May 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3ba9de57d1](https://linux-hardware.org/?probe=3ba9de57d1) | May 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [96be9cb5e7](https://linux-hardware.org/?probe=96be9cb5e7) | May 12, 2022 |
| Acer          | Aspire E5-575G              | [71e7f1c760](https://linux-hardware.org/?probe=71e7f1c760) | May 09, 2022 |
| MSI           | GT60 2OC/2OD                | [21f08dbab6](https://linux-hardware.org/?probe=21f08dbab6) | May 06, 2022 |
| Dell          | Inspiron 3576               | [85901f28cb](https://linux-hardware.org/?probe=85901f28cb) | May 05, 2022 |
| Acer          | Extensa 5635G               | [6e69a86d63](https://linux-hardware.org/?probe=6e69a86d63) | Apr 28, 2022 |
| HP            | ProBook 4540s               | [17272efb83](https://linux-hardware.org/?probe=17272efb83) | Apr 22, 2022 |
| Dell          | G3 3579                     | [a85e01d9d0](https://linux-hardware.org/?probe=a85e01d9d0) | Apr 20, 2022 |
| Dell          | Latitude E6520              | [33502900d8](https://linux-hardware.org/?probe=33502900d8) | Apr 19, 2022 |
| Fujitsu       | LIFEBOOK E751               | [54de39efb5](https://linux-hardware.org/?probe=54de39efb5) | Apr 12, 2022 |
| HP            | 15                          | [443dd5b9e8](https://linux-hardware.org/?probe=443dd5b9e8) | Apr 02, 2022 |
| Dell          | XPS 13 9333                 | [f4fb42182f](https://linux-hardware.org/?probe=f4fb42182f) | Apr 01, 2022 |
| ASUSTek       | X555LF                      | [35cceb0f0a](https://linux-hardware.org/?probe=35cceb0f0a) | Mar 31, 2022 |
| Fujitsu Si... | AMILO Pi 3525               | [b77907b9b6](https://linux-hardware.org/?probe=b77907b9b6) | Mar 31, 2022 |
| HP            | ProBook 4340s               | [787443949a](https://linux-hardware.org/?probe=787443949a) | Mar 27, 2022 |
| Lenovo        | ThinkPad T420 42364F2       | [d82acaba71](https://linux-hardware.org/?probe=d82acaba71) | Mar 23, 2022 |
| HP            | EliteBook 8740w             | [3ae23e0d6b](https://linux-hardware.org/?probe=3ae23e0d6b) | Mar 22, 2022 |
| ASUSTek       | K50IN                       | [02326ae250](https://linux-hardware.org/?probe=02326ae250) | Mar 22, 2022 |
| ASUSTek       | X555LNB                     | [ae49172b0f](https://linux-hardware.org/?probe=ae49172b0f) | Mar 21, 2022 |
| ASUSTek       | X555LNB                     | [33e081f100](https://linux-hardware.org/?probe=33e081f100) | Mar 21, 2022 |
| Dell          | Latitude 3510               | [f24ba2791e](https://linux-hardware.org/?probe=f24ba2791e) | Mar 19, 2022 |
| ASUSTek       | N53SN                       | [f335baa4a4](https://linux-hardware.org/?probe=f335baa4a4) | Mar 18, 2022 |
| Lenovo        | B580 20144                  | [9918c132f0](https://linux-hardware.org/?probe=9918c132f0) | Mar 13, 2022 |
| Lenovo        | B580 20144                  | [fd9ec44205](https://linux-hardware.org/?probe=fd9ec44205) | Mar 13, 2022 |
| HP            | ProBook 4340s               | [01af2dee98](https://linux-hardware.org/?probe=01af2dee98) | Mar 13, 2022 |
| HP            | EliteBook 8470p             | [76e54baafe](https://linux-hardware.org/?probe=76e54baafe) | Mar 09, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [f78b6db0bd](https://linux-hardware.org/?probe=f78b6db0bd) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [351e05ccc8](https://linux-hardware.org/?probe=351e05ccc8) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [dc09f11788](https://linux-hardware.org/?probe=dc09f11788) | Mar 08, 2022 |
| Dell          | Vostro 5515                 | [7707d7dc14](https://linux-hardware.org/?probe=7707d7dc14) | Feb 23, 2022 |
| Sony          | VPCEH3S6E                   | [334451b6e7](https://linux-hardware.org/?probe=334451b6e7) | Feb 23, 2022 |
| UMAX          | VisionBook 14Wr Plus        | [2e2c2de75c](https://linux-hardware.org/?probe=2e2c2de75c) | Feb 20, 2022 |
| ASUSTek       | K56CM                       | [c6e3cad977](https://linux-hardware.org/?probe=c6e3cad977) | Feb 19, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [9df089b1ef](https://linux-hardware.org/?probe=9df089b1ef) | Feb 19, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | [c9b5c461da](https://linux-hardware.org/?probe=c9b5c461da) | Feb 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [b4d07e8ab1](https://linux-hardware.org/?probe=b4d07e8ab1) | Feb 15, 2022 |
| Dell          | Latitude E6500              | [4b35cc763b](https://linux-hardware.org/?probe=4b35cc763b) | Feb 11, 2022 |
| Dell          | Latitude E6500              | [097664c430](https://linux-hardware.org/?probe=097664c430) | Feb 11, 2022 |
| HP            | EliteBook 840 G3            | [383572d5be](https://linux-hardware.org/?probe=383572d5be) | Feb 08, 2022 |
| Toshiba       | Satellite C855-1TT          | [87eacffdb8](https://linux-hardware.org/?probe=87eacffdb8) | Feb 07, 2022 |
| MSI           | VR201                       | [5d514ac721](https://linux-hardware.org/?probe=5d514ac721) | Feb 01, 2022 |
| HP            | ProBook 450 G5              | [39511f4010](https://linux-hardware.org/?probe=39511f4010) | Jan 29, 2022 |
| ASUSTek       | K50C                        | [a285a1e873](https://linux-hardware.org/?probe=a285a1e873) | Jan 27, 2022 |
| Dell          | Latitude E5570              | [7b6a4470d6](https://linux-hardware.org/?probe=7b6a4470d6) | Jan 27, 2022 |
| Acer          | Swift SF314-43              | [11f5908f13](https://linux-hardware.org/?probe=11f5908f13) | Jan 26, 2022 |
| Lenovo        | ThinkPad 20TDZMS            | [143bc3f79b](https://linux-hardware.org/?probe=143bc3f79b) | Jan 23, 2022 |
| MSI           | MS-163B Ver                 | [2e2d0c47bd](https://linux-hardware.org/?probe=2e2d0c47bd) | Jan 23, 2022 |
| Dell          | Latitude 3510               | [47793faf9f](https://linux-hardware.org/?probe=47793faf9f) | Jan 18, 2022 |
| MSI           | EX705                       | [bf23179311](https://linux-hardware.org/?probe=bf23179311) | Jan 17, 2022 |
| ASUSTek       | X553MA                      | [a1f88f8fc7](https://linux-hardware.org/?probe=a1f88f8fc7) | Jan 15, 2022 |
| HP            | Pavilion Gaming Laptop-c... | [bc679e8ef6](https://linux-hardware.org/?probe=bc679e8ef6) | Jan 14, 2022 |
| ASUSTek       | X553MA                      | [3260495670](https://linux-hardware.org/?probe=3260495670) | Jan 13, 2022 |
| HP            | ZBook 15 G3                 | [e91280cb30](https://linux-hardware.org/?probe=e91280cb30) | Dec 31, 2021 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | [b5709d8fd1](https://linux-hardware.org/?probe=b5709d8fd1) | Dec 31, 2021 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | [b79036063e](https://linux-hardware.org/?probe=b79036063e) | Dec 31, 2021 |
| ASUSTek       | G751JY                      | [e7a5fad002](https://linux-hardware.org/?probe=e7a5fad002) | Dec 29, 2021 |
| HP            | ZBook 15 G3                 | [a2a0923008](https://linux-hardware.org/?probe=a2a0923008) | Dec 20, 2021 |
| HP            | ZBook 15 G3                 | [0cba25aac5](https://linux-hardware.org/?probe=0cba25aac5) | Dec 20, 2021 |
| Lenovo        | G505 20240                  | [e29df1e2a0](https://linux-hardware.org/?probe=e29df1e2a0) | Dec 19, 2021 |
| ASUSTek       | X555BP                      | [770e3752e6](https://linux-hardware.org/?probe=770e3752e6) | Dec 18, 2021 |
| Dell          | Latitude E6430              | [5d4005ae4c](https://linux-hardware.org/?probe=5d4005ae4c) | Dec 13, 2021 |
| Dell          | Latitude 3510               | [e2834c5ef6](https://linux-hardware.org/?probe=e2834c5ef6) | Dec 08, 2021 |
| Dell          | Latitude 5401               | [796c461b16](https://linux-hardware.org/?probe=796c461b16) | Dec 01, 2021 |
| Dell          | Latitude D630               | [6044bc3e07](https://linux-hardware.org/?probe=6044bc3e07) | Nov 28, 2021 |
| Apple         | MacBookPro14,1              | [795a9ffd0f](https://linux-hardware.org/?probe=795a9ffd0f) | Nov 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e1827cbbc6](https://linux-hardware.org/?probe=e1827cbbc6) | Nov 24, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [6fb3466f59](https://linux-hardware.org/?probe=6fb3466f59) | Nov 23, 2021 |
| Dell          | Latitude 5590               | [d8b69c36bd](https://linux-hardware.org/?probe=d8b69c36bd) | Nov 23, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6189028e3d](https://linux-hardware.org/?probe=6189028e3d) | Nov 23, 2021 |
| Toshiba       | Satellite Pro C850-1D5      | [22ed560714](https://linux-hardware.org/?probe=22ed560714) | Nov 21, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [55384cc552](https://linux-hardware.org/?probe=55384cc552) | Nov 18, 2021 |
| Lenovo        | Z50-70 20354                | [4c1c718d65](https://linux-hardware.org/?probe=4c1c718d65) | Nov 14, 2021 |
| Toshiba       | Satellite L500              | [82d6b16382](https://linux-hardware.org/?probe=82d6b16382) | Nov 08, 2021 |
| Toshiba       | Satellite L500              | [70e2057cff](https://linux-hardware.org/?probe=70e2057cff) | Nov 07, 2021 |
| Toshiba       | Satellite U400              | [7b2364e53a](https://linux-hardware.org/?probe=7b2364e53a) | Nov 04, 2021 |
| HP            | Presario CQ57               | [8e3ceb5db9](https://linux-hardware.org/?probe=8e3ceb5db9) | Oct 23, 2021 |
| HP            | Presario CQ57               | [78828b2790](https://linux-hardware.org/?probe=78828b2790) | Oct 21, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [644553839a](https://linux-hardware.org/?probe=644553839a) | Oct 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| ASUSTek       | K50C                        | [02e59a3759](https://linux-hardware.org/?probe=02e59a3759) | Oct 16, 2021 |
| ASUSTek       | K50C                        | [c47941a383](https://linux-hardware.org/?probe=c47941a383) | Oct 16, 2021 |
| HP            | Pavilion dv6                | [dbfa388218](https://linux-hardware.org/?probe=dbfa388218) | Oct 10, 2021 |
| HP            | 15                          | [6974f988e3](https://linux-hardware.org/?probe=6974f988e3) | Oct 06, 2021 |
| Dell          | Studio XPS 1340             | [e54daea8f9](https://linux-hardware.org/?probe=e54daea8f9) | Oct 06, 2021 |
| Dell          | Studio XPS 1340             | [ed56dc2a85](https://linux-hardware.org/?probe=ed56dc2a85) | Oct 06, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [0540c800c7](https://linux-hardware.org/?probe=0540c800c7) | Oct 02, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [a508d7f60d](https://linux-hardware.org/?probe=a508d7f60d) | Oct 02, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [1e0f7c12ef](https://linux-hardware.org/?probe=1e0f7c12ef) | Oct 01, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [7efbe48343](https://linux-hardware.org/?probe=7efbe48343) | Oct 01, 2021 |
| Dell          | Latitude E6440              | [14a1218871](https://linux-hardware.org/?probe=14a1218871) | Sep 26, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [fd875fbe8c](https://linux-hardware.org/?probe=fd875fbe8c) | Sep 24, 2021 |
| Lenovo        | G580                        | [d7e35103d9](https://linux-hardware.org/?probe=d7e35103d9) | Sep 20, 2021 |
| HP            | Pavilion Notebook           | [835f183d57](https://linux-hardware.org/?probe=835f183d57) | Sep 17, 2021 |
| Toshiba       | Satellite C660              | [b2f55e8760](https://linux-hardware.org/?probe=b2f55e8760) | Sep 16, 2021 |
| Lenovo        | ThinkPad T450 20BV003SMS    | [352b2b53b8](https://linux-hardware.org/?probe=352b2b53b8) | Sep 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [727f3718a1](https://linux-hardware.org/?probe=727f3718a1) | Sep 08, 2021 |
| Dell          | Latitude 3510               | [797c9c49c9](https://linux-hardware.org/?probe=797c9c49c9) | Sep 02, 2021 |
| HP            | Pavilion dv6700             | [48ef40abbf](https://linux-hardware.org/?probe=48ef40abbf) | Sep 02, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [05d2b6e067](https://linux-hardware.org/?probe=05d2b6e067) | Sep 01, 2021 |
| Dell          | Latitude E5570              | [7e6202db9d](https://linux-hardware.org/?probe=7e6202db9d) | Aug 31, 2021 |
| Dell          | Latitude E5570              | [95667a8c8f](https://linux-hardware.org/?probe=95667a8c8f) | Aug 31, 2021 |
| HP            | EliteBook 745 G6            | [71e3489cd9](https://linux-hardware.org/?probe=71e3489cd9) | Aug 18, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | [9e66245080](https://linux-hardware.org/?probe=9e66245080) | Aug 17, 2021 |
| ASUSTek       | X51R                        | [1d1aad3900](https://linux-hardware.org/?probe=1d1aad3900) | Aug 08, 2021 |
| Teclast       | F15S                        | [49f33bd674](https://linux-hardware.org/?probe=49f33bd674) | Jul 28, 2021 |
| ASUSTek       | N551JM                      | [4334fcb285](https://linux-hardware.org/?probe=4334fcb285) | Jul 27, 2021 |
| Dell          | Latitude E5470              | [f26e3c7b39](https://linux-hardware.org/?probe=f26e3c7b39) | Jul 26, 2021 |
| Timi          | TM1701                      | [2d44d6cccb](https://linux-hardware.org/?probe=2d44d6cccb) | Jul 23, 2021 |
| HP            | Presario CQ57               | [3726c1e8c4](https://linux-hardware.org/?probe=3726c1e8c4) | Jul 15, 2021 |
| HP            | Pavilion dv6                | [4ffd108654](https://linux-hardware.org/?probe=4ffd108654) | Jul 15, 2021 |
| Lenovo        | ThinkPad L560 20F10029MC    | [a96e4cc1a5](https://linux-hardware.org/?probe=a96e4cc1a5) | Jul 12, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [8ed58d00f1](https://linux-hardware.org/?probe=8ed58d00f1) | Jun 19, 2021 |
| HP            | Pavilion dv6700             | [8d86cdfbad](https://linux-hardware.org/?probe=8d86cdfbad) | Jun 19, 2021 |
| Lenovo        | ThinkPad L540 20AUS0DW00    | [a3e83938c3](https://linux-hardware.org/?probe=a3e83938c3) | Jun 19, 2021 |
| HP            | Pavilion dv6700             | [44b174fec2](https://linux-hardware.org/?probe=44b174fec2) | Jun 18, 2021 |
| Unknown       | Unknown                     | [001462994e](https://linux-hardware.org/?probe=001462994e) | Jun 18, 2021 |
| Unknown       | Unknown                     | [049e5221b4](https://linux-hardware.org/?probe=049e5221b4) | Jun 18, 2021 |
| HP            | Pavilion dv6700             | [56342fd485](https://linux-hardware.org/?probe=56342fd485) | Jun 17, 2021 |
| Dell          | Precision 7530              | [3e5d3c4292](https://linux-hardware.org/?probe=3e5d3c4292) | Jun 15, 2021 |
| Sony          | VPCEB3L1E                   | [9048edb5d2](https://linux-hardware.org/?probe=9048edb5d2) | Jun 13, 2021 |
| Sony          | VPCEB3L1E                   | [93557b8c32](https://linux-hardware.org/?probe=93557b8c32) | Jun 13, 2021 |
| Sony          | VPCEB3L1E                   | [b90e553e8e](https://linux-hardware.org/?probe=b90e553e8e) | Jun 11, 2021 |
| Sony          | VPCEB3L1E                   | [bc3c3b537b](https://linux-hardware.org/?probe=bc3c3b537b) | Jun 06, 2021 |
| ASUSTek       | K54C                        | [dcdfadb154](https://linux-hardware.org/?probe=dcdfadb154) | May 31, 2021 |
| ASUSTek       | K54C                        | [252cf3ef89](https://linux-hardware.org/?probe=252cf3ef89) | May 31, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | [07b30926e1](https://linux-hardware.org/?probe=07b30926e1) | May 29, 2021 |
| ASUSTek       | F3M                         | [05d9306fcc](https://linux-hardware.org/?probe=05d9306fcc) | May 28, 2021 |
| eMachines     | E725                        | [f573488bda](https://linux-hardware.org/?probe=f573488bda) | May 25, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | [95b045c1a1](https://linux-hardware.org/?probe=95b045c1a1) | May 25, 2021 |
| ASUSTek       | X550CC                      | [26f506ff94](https://linux-hardware.org/?probe=26f506ff94) | May 23, 2021 |
| HP            | Unknown                     | [3584a13ae5](https://linux-hardware.org/?probe=3584a13ae5) | May 22, 2021 |
| HP            | Laptop 15-bw0xx             | [535d153c75](https://linux-hardware.org/?probe=535d153c75) | May 21, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | [01af2920f0](https://linux-hardware.org/?probe=01af2920f0) | May 19, 2021 |
| Acer          | Nitro AN515-54              | [c8ac6c4b93](https://linux-hardware.org/?probe=c8ac6c4b93) | May 16, 2021 |
| Lenovo        | ThinkPad T490 20N20048GE    | [7c9dbf982e](https://linux-hardware.org/?probe=7c9dbf982e) | May 14, 2021 |
| Toshiba       | Satellite L735              | [177d534fdc](https://linux-hardware.org/?probe=177d534fdc) | May 11, 2021 |
| HP            | Pavilion dv6                | [63656472a4](https://linux-hardware.org/?probe=63656472a4) | May 10, 2021 |
| Toshiba       | Satellite L735              | [52e1221ae0](https://linux-hardware.org/?probe=52e1221ae0) | May 09, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [bc90a54ebf](https://linux-hardware.org/?probe=bc90a54ebf) | May 06, 2021 |
| Dell          | Latitude 5401               | [660bb28d6a](https://linux-hardware.org/?probe=660bb28d6a) | May 04, 2021 |
| Lenovo        | ThinkPad X200T 7449FWG      | [2d8d1beca4](https://linux-hardware.org/?probe=2d8d1beca4) | May 03, 2021 |
| Lenovo        | V110-15IAP 80TG             | [d4307627a7](https://linux-hardware.org/?probe=d4307627a7) | May 01, 2021 |
| Dell          | Latitude 5520               | [d339546263](https://linux-hardware.org/?probe=d339546263) | Apr 30, 2021 |
| Acer          | Aspire 3690                 | [96bd8e49db](https://linux-hardware.org/?probe=96bd8e49db) | Apr 27, 2021 |
| Lenovo        | V110-15IAP 80TG             | [530bf24d20](https://linux-hardware.org/?probe=530bf24d20) | Apr 25, 2021 |
| ASUSTek       | X550CA                      | [103cc770c2](https://linux-hardware.org/?probe=103cc770c2) | Apr 18, 2021 |
| Dell          | System XPS L702X            | [6752a255ca](https://linux-hardware.org/?probe=6752a255ca) | Apr 18, 2021 |
| Dell          | System XPS L702X            | [20c39630ac](https://linux-hardware.org/?probe=20c39630ac) | Apr 18, 2021 |
| HP            | Pavilion 11 x360 PC         | [8aab148f59](https://linux-hardware.org/?probe=8aab148f59) | Apr 17, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | [1b8f927465](https://linux-hardware.org/?probe=1b8f927465) | Apr 16, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | [7878f15fa6](https://linux-hardware.org/?probe=7878f15fa6) | Apr 15, 2021 |
| Dell          | Latitude 5490               | [bb7e4cf726](https://linux-hardware.org/?probe=bb7e4cf726) | Apr 13, 2021 |
| Sony          | VGN-FW31ZJ                  | [b1bc398f58](https://linux-hardware.org/?probe=b1bc398f58) | Apr 10, 2021 |
| HP            | EliteBook 840 G1            | [c6fc94dd62](https://linux-hardware.org/?probe=c6fc94dd62) | Apr 08, 2021 |
| Sony          | VGN-FW31ZJ                  | [9de66e685f](https://linux-hardware.org/?probe=9de66e685f) | Apr 05, 2021 |
| HP            | ProBook 650 G1              | [051017604f](https://linux-hardware.org/?probe=051017604f) | Apr 04, 2021 |
| Dell          | Latitude E6400              | [f4e375c3e4](https://linux-hardware.org/?probe=f4e375c3e4) | Apr 01, 2021 |
| Dell          | Latitude E5440              | [757746e097](https://linux-hardware.org/?probe=757746e097) | Apr 01, 2021 |
| ASUSTek       | X550CL                      | [72ec76771c](https://linux-hardware.org/?probe=72ec76771c) | Mar 24, 2021 |
| Toshiba       | Satellite C850-13Z          | [f8b44b58ee](https://linux-hardware.org/?probe=f8b44b58ee) | Mar 21, 2021 |
| ASUSTek       | X550CC                      | [67ef60c8b1](https://linux-hardware.org/?probe=67ef60c8b1) | Mar 20, 2021 |
| HP            | Pavilion dv5                | [f84bed8734](https://linux-hardware.org/?probe=f84bed8734) | Mar 19, 2021 |
| ASUSTek       | X550CC                      | [2f2bf700ae](https://linux-hardware.org/?probe=2f2bf700ae) | Mar 18, 2021 |
| ASUSTek       | X550CC                      | [0f7e04c439](https://linux-hardware.org/?probe=0f7e04c439) | Mar 17, 2021 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | [60ad7c7aec](https://linux-hardware.org/?probe=60ad7c7aec) | Mar 17, 2021 |
| Dell          | Latitude 3510               | [24bc2a77b2](https://linux-hardware.org/?probe=24bc2a77b2) | Mar 16, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [fbebe98252](https://linux-hardware.org/?probe=fbebe98252) | Mar 13, 2021 |
| HP            | Pavilion dv6500             | [4aae1e6d26](https://linux-hardware.org/?probe=4aae1e6d26) | Mar 11, 2021 |
| HP            | Laptop 15-db1xxx            | [3d4aacd619](https://linux-hardware.org/?probe=3d4aacd619) | Mar 05, 2021 |
| HP            | Pavilion dv6                | [c26d9748f4](https://linux-hardware.org/?probe=c26d9748f4) | Mar 05, 2021 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [aedc60a146](https://linux-hardware.org/?probe=aedc60a146) | Mar 04, 2021 |
| Lenovo        | ThinkPad SL 2746AEG         | [4591f5d5af](https://linux-hardware.org/?probe=4591f5d5af) | Mar 03, 2021 |
| Lenovo        | ThinkPad T540p 20BFS14A0... | [5f75eafa25](https://linux-hardware.org/?probe=5f75eafa25) | Feb 28, 2021 |
| Google        | Gnawty                      | [252bc4cb46](https://linux-hardware.org/?probe=252bc4cb46) | Feb 25, 2021 |
| Dell          | Inspiron 5559               | [eca76d9f64](https://linux-hardware.org/?probe=eca76d9f64) | Feb 25, 2021 |
| Dell          | Latitude D430               | [63906404d0](https://linux-hardware.org/?probe=63906404d0) | Feb 25, 2021 |
| ASUSTek       | X101CH                      | [7897616bb0](https://linux-hardware.org/?probe=7897616bb0) | Feb 25, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [b91a419a64](https://linux-hardware.org/?probe=b91a419a64) | Feb 25, 2021 |
| ASUSTek       | X200CA                      | [2817beb96d](https://linux-hardware.org/?probe=2817beb96d) | Feb 25, 2021 |
| Dell          | Latitude 3510               | [8a6676e538](https://linux-hardware.org/?probe=8a6676e538) | Feb 25, 2021 |
| Acer          | Extensa 5235                | [48868a0c5e](https://linux-hardware.org/?probe=48868a0c5e) | Feb 24, 2021 |
| ASUSTek       | K52F                        | [1492b277a3](https://linux-hardware.org/?probe=1492b277a3) | Feb 24, 2021 |
| ASUSTek       | K52F                        | [0369d16c88](https://linux-hardware.org/?probe=0369d16c88) | Feb 24, 2021 |
| Lenovo        | ThinkPad T540p 20BFS14A0... | [3103f52c54](https://linux-hardware.org/?probe=3103f52c54) | Feb 24, 2021 |
| Dell          | Inspiron 5559               | [08723d28a4](https://linux-hardware.org/?probe=08723d28a4) | Feb 24, 2021 |
| HP            | Pavilion g6                 | [f23e85a87a](https://linux-hardware.org/?probe=f23e85a87a) | Feb 23, 2021 |
| Google        | Gnawty                      | [7614a9a19c](https://linux-hardware.org/?probe=7614a9a19c) | Feb 23, 2021 |
| eMachines     | eM350                       | [7826551972](https://linux-hardware.org/?probe=7826551972) | Feb 20, 2021 |
| Dell          | Inspiron 5559               | [cc6c16c095](https://linux-hardware.org/?probe=cc6c16c095) | Feb 19, 2021 |
| Dell          | Inspiron 7559               | [4d4377253f](https://linux-hardware.org/?probe=4d4377253f) | Feb 15, 2021 |
| Lenovo        | IdeaPad Z460 20059          | [b0b1eb3196](https://linux-hardware.org/?probe=b0b1eb3196) | Feb 14, 2021 |
| Lenovo        | IdeaPad Z460 20059          | [68fdda8114](https://linux-hardware.org/?probe=68fdda8114) | Feb 14, 2021 |
| Dell          | Inspiron 5559               | [4f0639f7c9](https://linux-hardware.org/?probe=4f0639f7c9) | Feb 10, 2021 |
| Dell          | Inspiron 5559               | [e3d953f88d](https://linux-hardware.org/?probe=e3d953f88d) | Feb 10, 2021 |
| Dell          | XPS 13 7390                 | [9d9da95c79](https://linux-hardware.org/?probe=9d9da95c79) | Feb 10, 2021 |
| Dell          | XPS 13 7390                 | [4b6ec0748c](https://linux-hardware.org/?probe=4b6ec0748c) | Feb 10, 2021 |
| Lenovo        | G500 20236                  | [bef7d62361](https://linux-hardware.org/?probe=bef7d62361) | Feb 03, 2021 |
| Dell          | Latitude D620               | [8f4c2819b9](https://linux-hardware.org/?probe=8f4c2819b9) | Feb 01, 2021 |
| HP            | ProBook 4545s               | [9c55ad844b](https://linux-hardware.org/?probe=9c55ad844b) | Jan 28, 2021 |
| HP            | Laptop 15-db1xxx            | [b38aa1a092](https://linux-hardware.org/?probe=b38aa1a092) | Jan 25, 2021 |
| HP            | Laptop 15-db1xxx            | [7a321f0327](https://linux-hardware.org/?probe=7a321f0327) | Jan 25, 2021 |
| HP            | Presario CQ57               | [7dcbdb9d0d](https://linux-hardware.org/?probe=7dcbdb9d0d) | Jan 25, 2021 |
| Lenovo        | IdeaPad 120S-14IAP          | [1469bc5f96](https://linux-hardware.org/?probe=1469bc5f96) | Jan 21, 2021 |
| Toshiba       | Satellite L850-1HP          | [1e0aa7f353](https://linux-hardware.org/?probe=1e0aa7f353) | Jan 17, 2021 |
| Lenovo        | IdeaPad 120S-14IAP          | [ce71ff03d7](https://linux-hardware.org/?probe=ce71ff03d7) | Jan 16, 2021 |
| HP            | Pavilion g6                 | [c4b4831246](https://linux-hardware.org/?probe=c4b4831246) | Jan 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [989e87e18e](https://linux-hardware.org/?probe=989e87e18e) | Jan 15, 2021 |
| ASUSTek       | X101CH                      | [3dfb714393](https://linux-hardware.org/?probe=3dfb714393) | Jan 15, 2021 |
| Google        | Gnawty                      | [b110360fd0](https://linux-hardware.org/?probe=b110360fd0) | Jan 15, 2021 |
| MSI           | CR500                       | [ff982a100f](https://linux-hardware.org/?probe=ff982a100f) | Jan 14, 2021 |
| MSI           | CR500                       | [509fd7cfd1](https://linux-hardware.org/?probe=509fd7cfd1) | Jan 14, 2021 |
| Dell          | Latitude D430               | [874d8f3925](https://linux-hardware.org/?probe=874d8f3925) | Jan 14, 2021 |
| ASUSTek       | X556UQK                     | [f70c845b60](https://linux-hardware.org/?probe=f70c845b60) | Jan 13, 2021 |
| HP            | ProBook 455 G6              | [da3110fdce](https://linux-hardware.org/?probe=da3110fdce) | Jan 11, 2021 |
| ASUSTek       | X550CC                      | [95a034c1f0](https://linux-hardware.org/?probe=95a034c1f0) | Jan 10, 2021 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [77af1025e7](https://linux-hardware.org/?probe=77af1025e7) | Jan 08, 2021 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [f3d55068a4](https://linux-hardware.org/?probe=f3d55068a4) | Jan 06, 2021 |
| HP            | EliteBook 8730w (VQ683EA... | [9650848634](https://linux-hardware.org/?probe=9650848634) | Jan 05, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | [70b6c077a6](https://linux-hardware.org/?probe=70b6c077a6) | Jan 05, 2021 |
| Acer          | Swift sf514-54t             | [f56b772338](https://linux-hardware.org/?probe=f56b772338) | Jan 05, 2021 |
| HP            | ProBook 4540s               | [03c94ff635](https://linux-hardware.org/?probe=03c94ff635) | Jan 04, 2021 |
| HP            | ProBook 4540s               | [eb99a077b0](https://linux-hardware.org/?probe=eb99a077b0) | Jan 04, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [caa3d1d91f](https://linux-hardware.org/?probe=caa3d1d91f) | Jan 03, 2021 |
| MSI           | MS-163B Ver                 | [2406d3e9a2](https://linux-hardware.org/?probe=2406d3e9a2) | Jan 02, 2021 |
| Acer          | Aspire A515-51G             | [0440c76ce6](https://linux-hardware.org/?probe=0440c76ce6) | Jan 01, 2021 |
| MSI           | MS-163B Ver                 | [d3f6e8b5b6](https://linux-hardware.org/?probe=d3f6e8b5b6) | Dec 30, 2020 |
| Acer          | Extensa 5635G               | [a089e8fb2a](https://linux-hardware.org/?probe=a089e8fb2a) | Dec 27, 2020 |
| HP            | ProBook 450 G5              | [183d05951e](https://linux-hardware.org/?probe=183d05951e) | Dec 22, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [bab0eb442f](https://linux-hardware.org/?probe=bab0eb442f) | Dec 22, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [e59a36ff39](https://linux-hardware.org/?probe=e59a36ff39) | Dec 22, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [d239275c54](https://linux-hardware.org/?probe=d239275c54) | Dec 21, 2020 |
| Lenovo        | IdeaPad U260 20067          | [f8b68b1481](https://linux-hardware.org/?probe=f8b68b1481) | Dec 19, 2020 |
| ASUSTek       | X200MA                      | [662934e08a](https://linux-hardware.org/?probe=662934e08a) | Dec 18, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | [a30ab2cb96](https://linux-hardware.org/?probe=a30ab2cb96) | Dec 16, 2020 |
| Fujitsu       | CELSIUS H760                | [bf6b408b8a](https://linux-hardware.org/?probe=bf6b408b8a) | Dec 15, 2020 |
| Toshiba       | Satellite P300              | [207e6367f2](https://linux-hardware.org/?probe=207e6367f2) | Dec 13, 2020 |
| Toshiba       | Satellite P300              | [3c0a54f9df](https://linux-hardware.org/?probe=3c0a54f9df) | Dec 11, 2020 |
| HP            | ProBook 4330s               | [22a64b85be](https://linux-hardware.org/?probe=22a64b85be) | Dec 06, 2020 |
| Dell          | Precision 7530              | [0d9da6571f](https://linux-hardware.org/?probe=0d9da6571f) | Dec 04, 2020 |
| HP            | ProBook 4330s               | [d7d25ffae4](https://linux-hardware.org/?probe=d7d25ffae4) | Dec 03, 2020 |
| Dell          | Precision 7530              | [2ea7f280b2](https://linux-hardware.org/?probe=2ea7f280b2) | Dec 02, 2020 |
| Acer          | Aspire 5742G                | [c17b4a5c87](https://linux-hardware.org/?probe=c17b4a5c87) | Nov 29, 2020 |
| ASUSTek       | ROG Zephyrus S17 GX701LW... | [f0b41bab99](https://linux-hardware.org/?probe=f0b41bab99) | Nov 28, 2020 |
| Lenovo        | ThinkPad P50 20EQS0VV2S     | [e89b91cab1](https://linux-hardware.org/?probe=e89b91cab1) | Nov 25, 2020 |
| Dell          | Vostro 5370                 | [653a970a7e](https://linux-hardware.org/?probe=653a970a7e) | Nov 22, 2020 |
| ASUSTek       | X550CC                      | [0d8cea2372](https://linux-hardware.org/?probe=0d8cea2372) | Nov 21, 2020 |
| HP            | Presario CQ57               | [43ffcec233](https://linux-hardware.org/?probe=43ffcec233) | Nov 18, 2020 |
| HP            | Presario CQ57               | [ff87b0c6d6](https://linux-hardware.org/?probe=ff87b0c6d6) | Nov 16, 2020 |
| HP            | ProBook 4330s               | [c9597f3a0d](https://linux-hardware.org/?probe=c9597f3a0d) | Nov 15, 2020 |
| Acer          | Swift SF315-41              | [43d05784be](https://linux-hardware.org/?probe=43d05784be) | Nov 12, 2020 |
| Dell          | Latitude E6540              | [33d4c9409a](https://linux-hardware.org/?probe=33d4c9409a) | Nov 11, 2020 |
| Lenovo        | G780                        | [145d3ccb54](https://linux-hardware.org/?probe=145d3ccb54) | Nov 08, 2020 |
| Lenovo        | G780                        | [56faed1607](https://linux-hardware.org/?probe=56faed1607) | Nov 06, 2020 |
| Dell          | Latitude 5411               | [e880b200a0](https://linux-hardware.org/?probe=e880b200a0) | Nov 06, 2020 |
| ASUSTek       | K75VJ                       | [aa4d1aabd8](https://linux-hardware.org/?probe=aa4d1aabd8) | Nov 03, 2020 |
| MSI           | EX705                       | [4307aff155](https://linux-hardware.org/?probe=4307aff155) | Nov 02, 2020 |
| MSI           | EX705                       | [c93a29a4ec](https://linux-hardware.org/?probe=c93a29a4ec) | Nov 02, 2020 |
| HP            | 15                          | [8d582da744](https://linux-hardware.org/?probe=8d582da744) | Nov 01, 2020 |
| HP            | 15                          | [0f0be86a64](https://linux-hardware.org/?probe=0f0be86a64) | Nov 01, 2020 |
| ASUSTek       | F5GL                        | [03675a2262](https://linux-hardware.org/?probe=03675a2262) | Oct 31, 2020 |
| Packard Be... | EasyNote TK85               | [544a018464](https://linux-hardware.org/?probe=544a018464) | Oct 30, 2020 |
| Dell          | G7 7790                     | [7dd8ac2676](https://linux-hardware.org/?probe=7dd8ac2676) | Oct 30, 2020 |
| ASUSTek       | UX32VD                      | [6c9095c4b8](https://linux-hardware.org/?probe=6c9095c4b8) | Oct 30, 2020 |
| Packard Be... | EasyNote TK85               | [0d1db60c39](https://linux-hardware.org/?probe=0d1db60c39) | Oct 24, 2020 |
| Lenovo        | ThinkPad T480 20L50006XS    | [782fe456b2](https://linux-hardware.org/?probe=782fe456b2) | Oct 16, 2020 |
| Lenovo        | ThinkPad T480 20L50006XS    | [51a31505c0](https://linux-hardware.org/?probe=51a31505c0) | Oct 16, 2020 |
| HP            | Presario CQ57               | [d2883f7a48](https://linux-hardware.org/?probe=d2883f7a48) | Oct 14, 2020 |
| HP            | Presario CQ57               | [3646e51370](https://linux-hardware.org/?probe=3646e51370) | Oct 13, 2020 |
| HP            | ProBook 4540s               | [095196f795](https://linux-hardware.org/?probe=095196f795) | Oct 09, 2020 |
| HP            | ProBook 4540s               | [0272418c87](https://linux-hardware.org/?probe=0272418c87) | Oct 09, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [dd1a01df40](https://linux-hardware.org/?probe=dd1a01df40) | Oct 09, 2020 |
| HP            | EliteBook 8470p             | [51aeeb5a22](https://linux-hardware.org/?probe=51aeeb5a22) | Oct 07, 2020 |
| HP            | EliteBook 8470p             | [6bd0eacb71](https://linux-hardware.org/?probe=6bd0eacb71) | Oct 07, 2020 |
| Toshiba       | Satellite P770              | [9a6b14ab65](https://linux-hardware.org/?probe=9a6b14ab65) | Oct 07, 2020 |
| Fujitsu Si... | LIFEBOOK S6420              | [cea718db3d](https://linux-hardware.org/?probe=cea718db3d) | Sep 30, 2020 |
| Dell          | XPS 13 9380                 | [1bcd88fae1](https://linux-hardware.org/?probe=1bcd88fae1) | Sep 30, 2020 |
| HP            | ProBook 6570b               | [c36d7a3815](https://linux-hardware.org/?probe=c36d7a3815) | Sep 27, 2020 |
| Lenovo        | ThinkPad T460s 20F9003SG... | [5ee1f4ba42](https://linux-hardware.org/?probe=5ee1f4ba42) | Sep 21, 2020 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | [25a18b6913](https://linux-hardware.org/?probe=25a18b6913) | Sep 20, 2020 |
| Lenovo        | IdeaPad U260 20067          | [c7ee126272](https://linux-hardware.org/?probe=c7ee126272) | Sep 18, 2020 |
| Lenovo        | G710 20252                  | [bda90e6285](https://linux-hardware.org/?probe=bda90e6285) | Sep 16, 2020 |
| MSI           | Prestige 15 A10SC           | [f9c109d38a](https://linux-hardware.org/?probe=f9c109d38a) | Sep 14, 2020 |
| Lenovo        | B590 20206                  | [241a96fabe](https://linux-hardware.org/?probe=241a96fabe) | Sep 13, 2020 |
| Lenovo        | B590 20206                  | [68c8013cac](https://linux-hardware.org/?probe=68c8013cac) | Sep 13, 2020 |
| ASUSTek       | X550CC                      | [c28899f07f](https://linux-hardware.org/?probe=c28899f07f) | Sep 10, 2020 |
| ASUSTek       | X550CC                      | [3a6d68dfe1](https://linux-hardware.org/?probe=3a6d68dfe1) | Sep 10, 2020 |
| ASUSTek       | X550CC                      | [654281ba17](https://linux-hardware.org/?probe=654281ba17) | Sep 02, 2020 |
| Dell          | Inspiron 7577               | [9243047fd5](https://linux-hardware.org/?probe=9243047fd5) | Aug 30, 2020 |
| ASUSTek       | X550CC                      | [92266759e0](https://linux-hardware.org/?probe=92266759e0) | Aug 29, 2020 |
| ASUSTek       | X550CC                      | [93baa51bda](https://linux-hardware.org/?probe=93baa51bda) | Aug 29, 2020 |
| Acer          | Swift SF314-58              | [3aa1021468](https://linux-hardware.org/?probe=3aa1021468) | Aug 28, 2020 |
| Toshiba       | Satellite C855-1TT          | [7a5dc01f13](https://linux-hardware.org/?probe=7a5dc01f13) | Aug 22, 2020 |
| Toshiba       | Satellite C855-1TT          | [98b59c7ddf](https://linux-hardware.org/?probe=98b59c7ddf) | Aug 21, 2020 |
| Lenovo        | G580                        | [e6435f1530](https://linux-hardware.org/?probe=e6435f1530) | Aug 13, 2020 |
| Sony          | VPCEH1S1E                   | [10c3c1d9d0](https://linux-hardware.org/?probe=10c3c1d9d0) | Aug 13, 2020 |
| MSI           | CR500                       | [6b04b72ba8](https://linux-hardware.org/?probe=6b04b72ba8) | Aug 06, 2020 |
| Lenovo        | ThinkPad T61 7659AB7        | [371a42eb7e](https://linux-hardware.org/?probe=371a42eb7e) | Jul 26, 2020 |
| Acer          | Aspire ES1-523              | [030cf77080](https://linux-hardware.org/?probe=030cf77080) | Jul 20, 2020 |
| Acer          | Aspire ES1-523              | [4d9339959a](https://linux-hardware.org/?probe=4d9339959a) | Jul 20, 2020 |
| HP            | Presario CQ57               | [680685ed32](https://linux-hardware.org/?probe=680685ed32) | Jul 19, 2020 |
| Dell          | Vostro 5370                 | [f8487e0c66](https://linux-hardware.org/?probe=f8487e0c66) | Jul 13, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [51d0966405](https://linux-hardware.org/?probe=51d0966405) | Jul 07, 2020 |
| UMAX          | VisionBook 14Wg Pro         | [5d2b6ed775](https://linux-hardware.org/?probe=5d2b6ed775) | Jul 06, 2020 |
| Fujitsu       | LIFEBOOK U904               | [57ca2c447b](https://linux-hardware.org/?probe=57ca2c447b) | Jul 06, 2020 |
| Lenovo        | IdeaPad Z500 20202          | [dc66cb5caf](https://linux-hardware.org/?probe=dc66cb5caf) | Jun 25, 2020 |
| UMAX          | VisionBook 14Wg Pro         | [a50a75e674](https://linux-hardware.org/?probe=a50a75e674) | Jun 21, 2020 |
| HP            | ProBook 6570b               | [f2370339d5](https://linux-hardware.org/?probe=f2370339d5) | Jun 21, 2020 |
| HP            | ProBook 6570b               | [c477dc5d5b](https://linux-hardware.org/?probe=c477dc5d5b) | Jun 18, 2020 |
| HP            | ProBook 6570b               | [d1f562df2f](https://linux-hardware.org/?probe=d1f562df2f) | Jun 18, 2020 |
| Sony          | VPCEH1L8E                   | [3b8814bf8e](https://linux-hardware.org/?probe=3b8814bf8e) | Jun 15, 2020 |
| Acer          | Aspire 5100                 | [481320cdb6](https://linux-hardware.org/?probe=481320cdb6) | Jun 09, 2020 |
| Acer          | Aspire 5100                 | [0e89938085](https://linux-hardware.org/?probe=0e89938085) | Jun 09, 2020 |
| ASUSTek       | X550CC                      | [d832045294](https://linux-hardware.org/?probe=d832045294) | Jun 06, 2020 |
| Lenovo        | ThinkPad Edge E220s 5038... | [e37f8c0d24](https://linux-hardware.org/?probe=e37f8c0d24) | Jun 05, 2020 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [a570720ce6](https://linux-hardware.org/?probe=a570720ce6) | May 26, 2020 |
| ASUSTek       | X550CC                      | [82c8b62b02](https://linux-hardware.org/?probe=82c8b62b02) | May 24, 2020 |
| ASUSTek       | X550CC                      | [8ebd135c78](https://linux-hardware.org/?probe=8ebd135c78) | May 23, 2020 |
| HP            | EliteBook 745 G3            | [1d082fe95a](https://linux-hardware.org/?probe=1d082fe95a) | May 14, 2020 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | [b8dfa98b13](https://linux-hardware.org/?probe=b8dfa98b13) | May 10, 2020 |
| Lenovo        | ThinkPad P50 20EQS0VV2S     | [31d9941f79](https://linux-hardware.org/?probe=31d9941f79) | May 05, 2020 |
| Lenovo        | ThinkPad P50 20EQS0VV2S     | [ddfe727f57](https://linux-hardware.org/?probe=ddfe727f57) | May 04, 2020 |
| HP            | EliteBook 850 G5            | [3e455caa1a](https://linux-hardware.org/?probe=3e455caa1a) | Apr 25, 2020 |
| HP            | Presario CQ57               | [0ba9cb0077](https://linux-hardware.org/?probe=0ba9cb0077) | Apr 25, 2020 |
| Acer          | Swift SF314-41              | [00dcbaa8f0](https://linux-hardware.org/?probe=00dcbaa8f0) | Apr 24, 2020 |
| Lenovo        | Z710 20250                  | [cf3d4e04cc](https://linux-hardware.org/?probe=cf3d4e04cc) | Apr 19, 2020 |
| ASUSTek       | T100TA                      | [ba03f5b5dd](https://linux-hardware.org/?probe=ba03f5b5dd) | Apr 19, 2020 |
| Dell          | Latitude E6540              | [0a2c664d30](https://linux-hardware.org/?probe=0a2c664d30) | Apr 19, 2020 |
| Lenovo        | B51-80 80LM                 | [b54cb44723](https://linux-hardware.org/?probe=b54cb44723) | Apr 17, 2020 |
| HP            | EliteBook 2760p             | [6631b4c0f1](https://linux-hardware.org/?probe=6631b4c0f1) | Apr 17, 2020 |
| HP            | Presario CQ57               | [9e1ad378a1](https://linux-hardware.org/?probe=9e1ad378a1) | Apr 13, 2020 |
| Lenovo        | B51-80 80LM                 | [054456ab1e](https://linux-hardware.org/?probe=054456ab1e) | Apr 12, 2020 |
| Dell          | Latitude E6540              | [1daf9c5f1a](https://linux-hardware.org/?probe=1daf9c5f1a) | Apr 10, 2020 |
| HP            | ProBook 450 G4              | [9c62a9edc6](https://linux-hardware.org/?probe=9c62a9edc6) | Apr 09, 2020 |
| Lenovo        | ThinkPad Edge E531 6885B... | [9dd9a20b65](https://linux-hardware.org/?probe=9dd9a20b65) | Apr 05, 2020 |
| Toshiba       | Satellite L450              | [b18b01a081](https://linux-hardware.org/?probe=b18b01a081) | Apr 04, 2020 |
| Lenovo        | Z710 20250                  | [0f9b8a8fc0](https://linux-hardware.org/?probe=0f9b8a8fc0) | Mar 31, 2020 |
| HP            | EliteBook 850 G6            | [f638a70ec4](https://linux-hardware.org/?probe=f638a70ec4) | Mar 30, 2020 |
| HP            | 530 Notebook PC(KD080AA#... | [aec394a418](https://linux-hardware.org/?probe=aec394a418) | Mar 27, 2020 |
| Packard Be... | EasyNote TE11BZ             | [5aaa403dee](https://linux-hardware.org/?probe=5aaa403dee) | Mar 26, 2020 |
| ASUSTek       | A6Km                        | [2c47a900f8](https://linux-hardware.org/?probe=2c47a900f8) | Mar 25, 2020 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [3f0773955d](https://linux-hardware.org/?probe=3f0773955d) | Mar 25, 2020 |
| ASUSTek       | A6Km                        | [3183eb860e](https://linux-hardware.org/?probe=3183eb860e) | Mar 24, 2020 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [56566f3fbb](https://linux-hardware.org/?probe=56566f3fbb) | Mar 23, 2020 |
| Toshiba       | Satellite P300              | [e51afe4271](https://linux-hardware.org/?probe=e51afe4271) | Mar 23, 2020 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [d5242f2534](https://linux-hardware.org/?probe=d5242f2534) | Mar 15, 2020 |
| ASUSTek       | X51L                        | [3ce2f3c47e](https://linux-hardware.org/?probe=3ce2f3c47e) | Mar 11, 2020 |
| Lenovo        | 3000 V100 07635CG           | [8c9c933a22](https://linux-hardware.org/?probe=8c9c933a22) | Mar 07, 2020 |
| Dell          | Latitude 5490               | [ab3da12d55](https://linux-hardware.org/?probe=ab3da12d55) | Feb 22, 2020 |
| Dell          | Latitude 5490               | [6b43e4ae7f](https://linux-hardware.org/?probe=6b43e4ae7f) | Feb 22, 2020 |
| ASUSTek       | F3Ke                        | [f1eaad7ea4](https://linux-hardware.org/?probe=f1eaad7ea4) | Feb 22, 2020 |
| Toshiba       | Satellite P300              | [f4642d40d8](https://linux-hardware.org/?probe=f4642d40d8) | Feb 11, 2020 |
| Google        | Gnawty                      | [4a2e211ce1](https://linux-hardware.org/?probe=4a2e211ce1) | Feb 08, 2020 |
| Toshiba       | EQUIUM A300D                | [f77888b435](https://linux-hardware.org/?probe=f77888b435) | Feb 07, 2020 |
| HP            | 635                         | [e1ed2f20e6](https://linux-hardware.org/?probe=e1ed2f20e6) | Feb 07, 2020 |
| HP            | 635                         | [0dbde497ec](https://linux-hardware.org/?probe=0dbde497ec) | Feb 06, 2020 |
| HP            | 635                         | [17396458ac](https://linux-hardware.org/?probe=17396458ac) | Feb 06, 2020 |
| HP            | 635                         | [2b47dfbcac](https://linux-hardware.org/?probe=2b47dfbcac) | Feb 06, 2020 |
| HP            | 635                         | [d980853d87](https://linux-hardware.org/?probe=d980853d87) | Feb 06, 2020 |
| HP            | 250 G3                      | [bdaa75d7d9](https://linux-hardware.org/?probe=bdaa75d7d9) | Feb 04, 2020 |
| HP            | 250 G3                      | [1a62acba2c](https://linux-hardware.org/?probe=1a62acba2c) | Feb 04, 2020 |
| HP            | ProBook 650 G1              | [897b50b880](https://linux-hardware.org/?probe=897b50b880) | Feb 03, 2020 |
| Lenovo        | ThinkPad T490 20N2S2UH00    | [693c5998b1](https://linux-hardware.org/?probe=693c5998b1) | Jan 31, 2020 |
| Timi          | TM1701                      | [921a36a46c](https://linux-hardware.org/?probe=921a36a46c) | Jan 31, 2020 |
| HP            | Pavilion Notebook           | [b677c3926c](https://linux-hardware.org/?probe=b677c3926c) | Jan 29, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [e5af1f2975](https://linux-hardware.org/?probe=e5af1f2975) | Jan 27, 2020 |
| Toshiba       | Satellite C50-A             | [fb518d95db](https://linux-hardware.org/?probe=fb518d95db) | Jan 27, 2020 |
| Toshiba       | Satellite C50-A             | [a4a37c8c40](https://linux-hardware.org/?probe=a4a37c8c40) | Jan 27, 2020 |
| Dell          | Latitude E5470              | [6fb212c97d](https://linux-hardware.org/?probe=6fb212c97d) | Jan 24, 2020 |
| Dell          | Vostro 3700                 | [bb0ea1ffd5](https://linux-hardware.org/?probe=bb0ea1ffd5) | Jan 19, 2020 |
| Acer          | Aspire 3610                 | [93dae491f3](https://linux-hardware.org/?probe=93dae491f3) | Jan 18, 2020 |
| Acer          | Aspire 3610                 | [33bbdb19d0](https://linux-hardware.org/?probe=33bbdb19d0) | Jan 18, 2020 |
| ASUSTek       | N73SV                       | [bafe93eacb](https://linux-hardware.org/?probe=bafe93eacb) | Jan 15, 2020 |
| Dell          | XPS M1530                   | [8ab2f0c35b](https://linux-hardware.org/?probe=8ab2f0c35b) | Jan 05, 2020 |
| ASUSTek       | K50IJ                       | [78b35a3d1d](https://linux-hardware.org/?probe=78b35a3d1d) | Jan 05, 2020 |
| Dell          | Vostro V130                 | [aae8826349](https://linux-hardware.org/?probe=aae8826349) | Jan 03, 2020 |
| Lenovo        | G575 20081                  | [bfd443284d](https://linux-hardware.org/?probe=bfd443284d) | Jan 01, 2020 |
| Lenovo        | G575 20081                  | [ec00d77a1a](https://linux-hardware.org/?probe=ec00d77a1a) | Jan 01, 2020 |
| Dell          | Studio 1535                 | [67d4b75167](https://linux-hardware.org/?probe=67d4b75167) | Dec 29, 2019 |
| Lenovo        | Z710 20250                  | [9ddb10548b](https://linux-hardware.org/?probe=9ddb10548b) | Dec 27, 2019 |
| Acer          | Extensa 5620                | [ba9eff4f3b](https://linux-hardware.org/?probe=ba9eff4f3b) | Dec 26, 2019 |
| Toshiba       | Satellite Pro C660          | [a36fc6a447](https://linux-hardware.org/?probe=a36fc6a447) | Dec 26, 2019 |
| Toshiba       | Satellite P300              | [6108b0c47e](https://linux-hardware.org/?probe=6108b0c47e) | Dec 25, 2019 |
| Google        | Gnawty                      | [2332ed0dd8](https://linux-hardware.org/?probe=2332ed0dd8) | Dec 23, 2019 |
| HP            | Pavilion g6                 | [9c722b6763](https://linux-hardware.org/?probe=9c722b6763) | Dec 21, 2019 |
| Acer          | Aspire 3610                 | [77353d6c03](https://linux-hardware.org/?probe=77353d6c03) | Dec 14, 2019 |
| Sony          | VPCEE2M1E                   | [9afef9e3e5](https://linux-hardware.org/?probe=9afef9e3e5) | Nov 24, 2019 |
| Sony          | SVE1713F1EW                 | [a1de0ea6f8](https://linux-hardware.org/?probe=a1de0ea6f8) | Nov 24, 2019 |
| Acer          | Crane II                    | [50122b9e8e](https://linux-hardware.org/?probe=50122b9e8e) | Nov 22, 2019 |
| Lenovo        | IdeaPad U260 20067          | [f592337622](https://linux-hardware.org/?probe=f592337622) | Nov 17, 2019 |
| eMachines     | E627                        | [874a5386c1](https://linux-hardware.org/?probe=874a5386c1) | Nov 16, 2019 |
| Medion        | E6435 MD60939               | [012a12549f](https://linux-hardware.org/?probe=012a12549f) | Nov 13, 2019 |
| eMachines     | E627                        | [55ba59c740](https://linux-hardware.org/?probe=55ba59c740) | Nov 13, 2019 |
| eMachines     | E627                        | [f984c92be5](https://linux-hardware.org/?probe=f984c92be5) | Nov 09, 2019 |
| Acer          | Crane II                    | [eba60f8297](https://linux-hardware.org/?probe=eba60f8297) | Nov 08, 2019 |
| Acer          | Crane II                    | [6c2e93de66](https://linux-hardware.org/?probe=6c2e93de66) | Nov 08, 2019 |
| eMachines     | E627                        | [0b1acfd5a2](https://linux-hardware.org/?probe=0b1acfd5a2) | Nov 06, 2019 |
| Dell          | Vostro 3700                 | [dc6f95878c](https://linux-hardware.org/?probe=dc6f95878c) | Nov 05, 2019 |
| Lenovo        | ThinkPad X230 2324HZ9       | [faddcc4f2b](https://linux-hardware.org/?probe=faddcc4f2b) | Nov 04, 2019 |
| HP            | Pavilion dv7                | [ff9ced6ef0](https://linux-hardware.org/?probe=ff9ced6ef0) | Nov 04, 2019 |
| ASUSTek       | X101CH                      | [b17de4dbad](https://linux-hardware.org/?probe=b17de4dbad) | Nov 04, 2019 |
| HP            | Notebook                    | [df94931018](https://linux-hardware.org/?probe=df94931018) | Nov 03, 2019 |
| HP            | Notebook                    | [cd5f971a86](https://linux-hardware.org/?probe=cd5f971a86) | Nov 03, 2019 |
| Lenovo        | IdeaPad Y560                | [6ca3597271](https://linux-hardware.org/?probe=6ca3597271) | Nov 03, 2019 |
| HP            | Pavilion g6                 | [2cb09606ed](https://linux-hardware.org/?probe=2cb09606ed) | Nov 01, 2019 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [cb80682975](https://linux-hardware.org/?probe=cb80682975) | Oct 20, 2019 |
| HP            | Pavilion g6                 | [6bde777445](https://linux-hardware.org/?probe=6bde777445) | Oct 20, 2019 |
| Google        | Gnawty                      | [c0b7f226f9](https://linux-hardware.org/?probe=c0b7f226f9) | Oct 20, 2019 |
| Dell          | Vostro 5370                 | [f2c990d6ba](https://linux-hardware.org/?probe=f2c990d6ba) | Oct 12, 2019 |
| Lenovo        | ThinkPad X220 42914BG       | [edfe201446](https://linux-hardware.org/?probe=edfe201446) | Oct 08, 2019 |
| Acer          | Aspire V5-531G              | [396cfb8284](https://linux-hardware.org/?probe=396cfb8284) | Oct 06, 2019 |
| ASUSTek       | X505BA                      | [85cb3c5515](https://linux-hardware.org/?probe=85cb3c5515) | Oct 05, 2019 |
| Lenovo        | ThinkPad X200 Tablet 745... | [fb6e962768](https://linux-hardware.org/?probe=fb6e962768) | Sep 27, 2019 |
| Lenovo        | ThinkPad T430 2349U2B       | [b6b8e23a2d](https://linux-hardware.org/?probe=b6b8e23a2d) | Sep 15, 2019 |
| Lenovo        | ThinkPad T430 2349U2B       | [72825d26f3](https://linux-hardware.org/?probe=72825d26f3) | Sep 15, 2019 |
| ASUSTek       | 1000H                       | [7d83011877](https://linux-hardware.org/?probe=7d83011877) | Aug 31, 2019 |
| ASUSTek       | B400VC                      | [3f5a088240](https://linux-hardware.org/?probe=3f5a088240) | Aug 29, 2019 |
| Sony          | SVE1713F1EW                 | [d5c33713cb](https://linux-hardware.org/?probe=d5c33713cb) | Aug 22, 2019 |
| Sony          | SVE1713F1EW                 | [2aa9a3f6a0](https://linux-hardware.org/?probe=2aa9a3f6a0) | Aug 20, 2019 |
| ASUSTek       | K52Jc                       | [4570331fe2](https://linux-hardware.org/?probe=4570331fe2) | Aug 15, 2019 |
| Apple         | MacBook1,1                  | [c13279cf0f](https://linux-hardware.org/?probe=c13279cf0f) | Aug 14, 2019 |
| Lenovo        | ThinkPad T570 20H90017MC    | [e51b525663](https://linux-hardware.org/?probe=e51b525663) | Aug 10, 2019 |
| Lenovo        | ThinkPad X250 20CLS23500    | [8a4778de5b](https://linux-hardware.org/?probe=8a4778de5b) | Aug 01, 2019 |
| Lenovo        | ThinkPad L470 20J4003TXS    | [6c4dc05e0c](https://linux-hardware.org/?probe=6c4dc05e0c) | Jul 09, 2019 |
| Acer          | Aspire E1-531               | [a396fdf6c6](https://linux-hardware.org/?probe=a396fdf6c6) | Jun 29, 2019 |
| Acer          | Aspire E1-531               | [dbb78eb76e](https://linux-hardware.org/?probe=dbb78eb76e) | Jun 24, 2019 |
| HP            | ProBook 4730s               | [cb342b6572](https://linux-hardware.org/?probe=cb342b6572) | Jun 05, 2019 |
| HP            | Pavilion Notebook           | [5048eb8853](https://linux-hardware.org/?probe=5048eb8853) | May 17, 2019 |
| Acer          | AOD257                      | [d95215116b](https://linux-hardware.org/?probe=d95215116b) | May 06, 2019 |
| Acer          | AOD257                      | [589983c598](https://linux-hardware.org/?probe=589983c598) | May 05, 2019 |
| Sony          | SVE1713F1EW                 | [67b367b96f](https://linux-hardware.org/?probe=67b367b96f) | Apr 23, 2019 |
| ASUSTek       | E200HA                      | [c4e22bb515](https://linux-hardware.org/?probe=c4e22bb515) | Apr 11, 2019 |
| HP            | 510 Notebook PC (RU963AA... | [87f8ef65ae](https://linux-hardware.org/?probe=87f8ef65ae) | Apr 08, 2019 |
| MSI           | GX630/GX633                 | [12132d4ebd](https://linux-hardware.org/?probe=12132d4ebd) | Mar 26, 2019 |
| Lenovo        | ThinkPad T440p 20AW0047M... | [243988734d](https://linux-hardware.org/?probe=243988734d) | Mar 25, 2019 |
| Dell          | Vostro 3700                 | [459c56742e](https://linux-hardware.org/?probe=459c56742e) | Mar 10, 2019 |
| Lenovo        | ThinkPad Edge E545 20B2S... | [d5472dae8e](https://linux-hardware.org/?probe=d5472dae8e) | Feb 21, 2019 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [f422d122fa](https://linux-hardware.org/?probe=f422d122fa) | Feb 16, 2019 |
| HP            | Compaq Presario CQ50        | [7a5481cc61](https://linux-hardware.org/?probe=7a5481cc61) | Feb 11, 2019 |
| ASUSTek       | X51R                        | [67c7bfe084](https://linux-hardware.org/?probe=67c7bfe084) | Jan 30, 2019 |
| ASUSTek       | X51R                        | [c746805402](https://linux-hardware.org/?probe=c746805402) | Jan 30, 2019 |
| HP            | ProBook 4540s               | [e7d5fe03ba](https://linux-hardware.org/?probe=e7d5fe03ba) | Jan 26, 2019 |
| MSI           | GX630/GX633                 | [42e7957235](https://linux-hardware.org/?probe=42e7957235) | Jan 22, 2019 |
| HP            | ProBook 4540s               | [2f0dc95a92](https://linux-hardware.org/?probe=2f0dc95a92) | Dec 27, 2018 |
| Lenovo        | ThinkPad L430 24655K5       | [27aaa085bb](https://linux-hardware.org/?probe=27aaa085bb) | Dec 25, 2018 |
| HP            | Compaq 6720s                | [d7475ab15e](https://linux-hardware.org/?probe=d7475ab15e) | Dec 20, 2018 |
| HP            | Compaq 6720s                | [e5cdafcee2](https://linux-hardware.org/?probe=e5cdafcee2) | Dec 20, 2018 |
| HP            | Compaq 6720s                | [83a7e31dd4](https://linux-hardware.org/?probe=83a7e31dd4) | Dec 20, 2018 |
| Lenovo        | ThinkPad T430 2349Y12       | [27f3486119](https://linux-hardware.org/?probe=27f3486119) | Dec 14, 2018 |
| Lenovo        | ThinkPad T430 2349Y12       | [94d298a37a](https://linux-hardware.org/?probe=94d298a37a) | Dec 14, 2018 |
| ASUSTek       | N55SF                       | [8b49ac8515](https://linux-hardware.org/?probe=8b49ac8515) | Nov 30, 2018 |
| Acer          | Aspire V5-572P              | [46820db730](https://linux-hardware.org/?probe=46820db730) | Nov 08, 2018 |
| Sony          | VGN-NR21J_S                 | [4cce581173](https://linux-hardware.org/?probe=4cce581173) | Oct 31, 2018 |
| Lenovo        | ThinkPad E520 1143ENG       | [107f78f681](https://linux-hardware.org/?probe=107f78f681) | Oct 30, 2018 |
| Lenovo        | ThinkPad E520 1143ENG       | [bfb0367c84](https://linux-hardware.org/?probe=bfb0367c84) | Oct 30, 2018 |
| HP            | ProBook 4330s               | [4ce0dfe7c0](https://linux-hardware.org/?probe=4ce0dfe7c0) | Oct 28, 2018 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [d5c9be9ec4](https://linux-hardware.org/?probe=d5c9be9ec4) | Oct 27, 2018 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [49aacee5b4](https://linux-hardware.org/?probe=49aacee5b4) | Oct 27, 2018 |
| ASUSTek       | X550VB                      | [931d58d353](https://linux-hardware.org/?probe=931d58d353) | Oct 21, 2018 |
| Dell          | Inspiron 7566               | [6682a76496](https://linux-hardware.org/?probe=6682a76496) | Aug 27, 2018 |
| HP            | ProBook 4545s               | [4598e67cd6](https://linux-hardware.org/?probe=4598e67cd6) | Jul 19, 2018 |
| HP            | ProBook 430 G2              | [d62a1df5c6](https://linux-hardware.org/?probe=d62a1df5c6) | May 29, 2018 |
| HP            | ProBook 430 G2              | [80ba1f23b5](https://linux-hardware.org/?probe=80ba1f23b5) | May 19, 2018 |
| Fujitsu Si... | LIFEBOOK S7220              | [d834a892f8](https://linux-hardware.org/?probe=d834a892f8) | Apr 17, 2018 |
| Toshiba       | Satellite P300              | [977054f744](https://linux-hardware.org/?probe=977054f744) | Dec 07, 2017 |
| Lenovo        | IdeaPad 305-15ABM 80NL      | [51938564c0](https://linux-hardware.org/?probe=51938564c0) | Nov 22, 2017 |
| ASUSTek       | X51L                        | [cd24ea4640](https://linux-hardware.org/?probe=cd24ea4640) | May 31, 2017 |
| Lenovo        | IdeaPad 305-15ABM 80NL      | [2524f15422](https://linux-hardware.org/?probe=2524f15422) | Mar 18, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Slovakia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 53        | 10.43%  |
| Ubuntu 18.04       | 39        | 7.68%   |
| BlackPanther 18.1  | 33        | 6.5%    |
| Ubuntu 22.04       | 17        | 3.35%   |
| OpenMandriva 4.3   | 16        | 3.15%   |
| OpenMandriva 4.2   | 12        | 2.36%   |
| Arch Rolling       | 11        | 2.17%   |
| Linux Mint 21.2    | 10        | 1.97%   |
| Linux Mint 21.1    | 10        | 1.97%   |
| Linux Mint 19.3    | 9         | 1.77%   |
| Debian 11          | 9         | 1.77%   |
| ROSA R10           | 8         | 1.57%   |
| Linux Mint 21      | 8         | 1.57%   |
| Linux Mint 20.3    | 8         | 1.57%   |
| Linux Mint 20.1    | 8         | 1.57%   |
| Pop!_OS 22.04      | 7         | 1.38%   |
| OpenMandriva 23.01 | 7         | 1.38%   |
| Fedora 37          | 7         | 1.38%   |
| Fedora 34          | 7         | 1.38%   |
| Xubuntu 18.04      | 6         | 1.18%   |
| Ubuntu 19.04       | 6         | 1.18%   |
| MX 19              | 6         | 1.18%   |
| Fedora 38          | 6         | 1.18%   |
| Zorin 16           | 5         | 0.98%   |
| Ubuntu 20.10       | 5         | 0.98%   |
| ROSA R11.1         | 5         | 0.98%   |
| Pop!_OS 20.10      | 5         | 0.98%   |
| OpenMandriva 23.03 | 5         | 0.98%   |
| Linux Mint 20.2    | 5         | 0.98%   |
| Zorin 15           | 4         | 0.79%   |
| Pop!_OS 21.10      | 4         | 0.79%   |
| OpenMandriva 23.08 | 4         | 0.79%   |
| Manjaro            | 4         | 0.79%   |
| Linux Mint 20      | 4         | 0.79%   |
| Linux Mint 19.1    | 4         | 0.79%   |
| Kubuntu 22.10      | 4         | 0.79%   |
| KDE neon 22.04     | 4         | 0.79%   |
| KDE neon 20.04     | 4         | 0.79%   |
| Fedora 39          | 4         | 0.79%   |
| Fedora 32          | 4         | 0.79%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 130       | 27.14%  |
| Linux Mint   | 59        | 12.32%  |
| OpenMandriva | 44        | 9.19%   |
| Fedora       | 39        | 8.14%   |
| BlackPanther | 35        | 7.31%   |
| Pop!_OS      | 17        | 3.55%   |
| Debian       | 17        | 3.55%   |
| ROSA         | 16        | 3.34%   |
| Arch         | 15        | 3.13%   |
| Kubuntu      | 14        | 2.92%   |
| Xubuntu      | 12        | 2.51%   |
| Zorin        | 11        | 2.3%    |
| Manjaro      | 10        | 2.09%   |
| MX           | 7         | 1.46%   |
| KDE neon     | 7         | 1.46%   |
| Gentoo       | 5         | 1.04%   |
| SteamOS      | 4         | 0.84%   |
| Lubuntu      | 4         | 0.84%   |
| Endless      | 4         | 0.84%   |
| Ubuntu Unity | 3         | 0.63%   |
| openSUSE     | 3         | 0.63%   |
| ArcoLinux    | 3         | 0.63%   |
| Ubuntu MATE  | 2         | 0.42%   |
| EndeavourOS  | 2         | 0.42%   |
| Elementary   | 2         | 0.42%   |
| Alpine       | 2         | 0.42%   |
| Rocky Linux  | 1         | 0.21%   |
| RHEL         | 1         | 0.21%   |
| Parrot       | 1         | 0.21%   |
| Linux Lite   | 1         | 0.21%   |
| Kaisen       | 1         | 0.21%   |
| GNOME OS     | 1         | 0.21%   |
| GalliumOS    | 1         | 0.21%   |
| Devuan       | 1         | 0.21%   |
| Clear Linux  | 1         | 0.21%   |
| CentOS       | 1         | 0.21%   |
| CachyOS      | 1         | 0.21%   |
| Artix        | 1         | 0.21%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Notebooks | Percent |
|----------------------------------|-----------|---------|
| 4.18.16-desktop-1bP              | 26        | 4.78%   |
| 5.16.7-desktop-1omv4003          | 14        | 2.57%   |
| 5.6.14-desktop-2bP               | 12        | 2.21%   |
| 5.10.14-desktop-1omv4002         | 12        | 2.21%   |
| 5.15.0-56-generic                | 9         | 1.65%   |
| 5.4.0-58-generic                 | 8         | 1.47%   |
| 6.1.1-desktop-1omv2290           | 7         | 1.29%   |
| 5.4.0-42-generic                 | 7         | 1.29%   |
| 6.2.0-26-generic                 | 6         | 1.1%    |
| 6.2.6-desktop-1omv2390           | 5         | 0.92%   |
| 5.4.0-52-generic                 | 5         | 0.92%   |
| 5.15.0-58-generic                | 5         | 0.92%   |
| 5.11.0-27-generic                | 5         | 0.92%   |
| 6.2.0-33-generic                 | 4         | 0.74%   |
| 5.8.0-43-generic                 | 4         | 0.74%   |
| 5.4.0-73-generic                 | 4         | 0.74%   |
| 5.4.0-47-generic                 | 4         | 0.74%   |
| 5.19.0-35-generic                | 4         | 0.74%   |
| 5.15.0-83-generic                | 4         | 0.74%   |
| 5.15.0-67-generic                | 4         | 0.74%   |
| 4.9.60-nrj-desktop-1rosa-x86_64  | 4         | 0.74%   |
| 4.15.0-66-generic                | 4         | 0.74%   |
| 5.8.0-50-generic                 | 3         | 0.55%   |
| 5.8.0-29-generic                 | 3         | 0.55%   |
| 5.4.0-91-generic                 | 3         | 0.55%   |
| 5.4.0-88-generic                 | 3         | 0.55%   |
| 5.4.0-26-generic                 | 3         | 0.55%   |
| 5.3.0-40-generic                 | 3         | 0.55%   |
| 5.3.0-26-generic                 | 3         | 0.55%   |
| 5.15.0-47-generic                | 3         | 0.55%   |
| 5.13.0-40-generic                | 3         | 0.55%   |
| 5.13.0-35-generic                | 3         | 0.55%   |
| 5.10.0-23-amd64                  | 3         | 0.55%   |
| 5.0.0-25-generic                 | 3         | 0.55%   |
| 4.9.124-nrj-desktop-1rosa-x86_64 | 3         | 0.55%   |
| 4.19.0-13-amd64                  | 3         | 0.55%   |
| 4.15.0-55-generic                | 3         | 0.55%   |
| 6.5.6-76060506-generic           | 2         | 0.37%   |
| 6.5.12-300.fc39.x86_64           | 2         | 0.37%   |
| 6.4.8-desktop-2omv2390           | 2         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 69        | 13.42%  |
| 5.15.0  | 42        | 8.17%   |
| 4.15.0  | 35        | 6.81%   |
| 4.18.16 | 26        | 5.06%   |
| 5.8.0   | 23        | 4.47%   |
| 6.2.0   | 18        | 3.5%    |
| 5.13.0  | 18        | 3.5%    |
| 5.3.0   | 17        | 3.31%   |
| 5.11.0  | 16        | 3.11%   |
| 5.0.0   | 15        | 2.92%   |
| 5.19.0  | 14        | 2.72%   |
| 5.16.7  | 14        | 2.72%   |
| 5.6.14  | 12        | 2.33%   |
| 5.10.14 | 12        | 2.33%   |
| 5.10.0  | 12        | 2.33%   |
| 6.2.6   | 7         | 1.36%   |
| 6.1.1   | 7         | 1.36%   |
| 4.19.0  | 7         | 1.36%   |
| 4.18.0  | 7         | 1.36%   |
| 6.1.0   | 4         | 0.78%   |
| 4.9.60  | 4         | 0.78%   |
| 5.9.16  | 3         | 0.58%   |
| 5.17.5  | 3         | 0.58%   |
| 5.11.11 | 3         | 0.58%   |
| 4.9.20  | 3         | 0.58%   |
| 4.9.124 | 3         | 0.58%   |
| 6.6.2   | 2         | 0.39%   |
| 6.5.8   | 2         | 0.39%   |
| 6.5.6   | 2         | 0.39%   |
| 6.5.12  | 2         | 0.39%   |
| 6.4.8   | 2         | 0.39%   |
| 6.4.12  | 2         | 0.39%   |
| 6.4.11  | 2         | 0.39%   |
| 6.2.14  | 2         | 0.39%   |
| 5.4.83  | 2         | 0.39%   |
| 5.17.1  | 2         | 0.39%   |
| 5.16.13 | 2         | 0.39%   |
| 5.15.75 | 2         | 0.39%   |
| 5.11.3  | 2         | 0.39%   |
| 4.4.0   | 2         | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 73        | 14.23%  |
| 5.15    | 57        | 11.11%  |
| 4.15    | 35        | 6.82%   |
| 4.18    | 33        | 6.43%   |
| 5.10    | 32        | 6.24%   |
| 6.2     | 30        | 5.85%   |
| 5.8     | 24        | 4.68%   |
| 5.11    | 22        | 4.29%   |
| 5.13    | 21        | 4.09%   |
| 5.3     | 19        | 3.7%    |
| 6.1     | 18        | 3.51%   |
| 5.16    | 18        | 3.51%   |
| 5.19    | 17        | 3.31%   |
| 5.0     | 17        | 3.31%   |
| 5.6     | 15        | 2.92%   |
| 4.9     | 12        | 2.34%   |
| 6.5     | 9         | 1.75%   |
| 6.4     | 8         | 1.56%   |
| 4.19    | 8         | 1.56%   |
| 5.17    | 7         | 1.36%   |
| 6.3     | 5         | 0.97%   |
| 5.5     | 5         | 0.97%   |
| 6.6     | 4         | 0.78%   |
| 6.0     | 4         | 0.78%   |
| 5.9     | 4         | 0.78%   |
| 5.12    | 3         | 0.58%   |
| 5.7     | 2         | 0.39%   |
| 5.18    | 2         | 0.39%   |
| 5.14    | 2         | 0.39%   |
| 4.4     | 2         | 0.39%   |
| 5.2     | 1         | 0.19%   |
| 4.17    | 1         | 0.19%   |
| 4.16    | 1         | 0.19%   |
| 4.12    | 1         | 0.19%   |
| 4.1     | 1         | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 436       | 93.36%  |
| i686   | 31        | 6.64%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 168       | 35%     |
| KDE5            | 121       | 25.21%  |
| Unknown         | 53        | 11.04%  |
| X-Cinnamon      | 46        | 9.58%   |
| XFCE            | 45        | 9.38%   |
| MATE            | 10        | 2.08%   |
| KDE4            | 8         | 1.67%   |
| KDE             | 7         | 1.46%   |
| LXQt            | 5         | 1.04%   |
| LXDE            | 4         | 0.83%   |
| Cinnamon        | 4         | 0.83%   |
| Unity           | 3         | 0.63%   |
| Pantheon        | 2         | 0.42%   |
| Hyprland        | 1         | 0.21%   |
| GNOME Flashback | 1         | 0.21%   |
| Budgie          | 1         | 0.21%   |
| awesome         | 1         | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 371       | 78.6%   |
| Wayland     | 72        | 15.25%  |
| Unknown     | 24        | 5.08%   |
| Tty         | 4         | 0.85%   |
| Unspecified | 1         | 0.21%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 222       | 46.64%  |
| SDDM    | 104       | 21.85%  |
| LightDM | 49        | 10.29%  |
| GDM3    | 41        | 8.61%   |
| GDM     | 38        | 7.98%   |
| TDM     | 11        | 2.31%   |
| KDM     | 8         | 1.68%   |
| XDM     | 1         | 0.21%   |
| Ly      | 1         | 0.21%   |
| LXDM    | 1         | 0.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 196       | 40.5%   |
| sk_SK   | 133       | 27.48%  |
| Unknown | 98        | 20.25%  |
| cs_CZ   | 15        | 3.1%    |
| C       | 14        | 2.89%   |
| en_GB   | 10        | 2.07%   |
| hu_HU   | 9         | 1.86%   |
| ru_RU   | 3         | 0.62%   |
| ru_UA   | 1         | 0.21%   |
| pl_PL   | 1         | 0.21%   |
| it_IT   | 1         | 0.21%   |
| en_US  | 1         | 0.21%   |
| de_DE   | 1         | 0.21%   |
| C.UTF8  | 1         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 265       | 55.67%  |
| EFI  | 211       | 44.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 317       | 65.9%   |
| Overlay | 79        | 16.42%  |
| Btrfs   | 42        | 8.73%   |
| Unknown | 16        | 3.33%   |
| Tmpfs   | 12        | 2.49%   |
| Xfs     | 6         | 1.25%   |
| Zfs     | 5         | 1.04%   |
| Ext3    | 2         | 0.42%   |
| Ext2    | 2         | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 233       | 48.95%  |
| GPT     | 154       | 32.35%  |
| MBR     | 89        | 18.7%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 405       | 84.73%  |
| Yes       | 73        | 15.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 321       | 68.3%   |
| Yes       | 149       | 31.7%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 123       | 26.39%  |
| Hewlett-Packard     | 84        | 18.03%  |
| ASUSTek Computer    | 75        | 16.09%  |
| Dell                | 62        | 13.3%   |
| Acer                | 36        | 7.73%   |
| Toshiba             | 18        | 3.86%   |
| MSI                 | 11        | 2.36%   |
| Sony                | 9         | 1.93%   |
| UMAX                | 5         | 1.07%   |
| Apple               | 5         | 1.07%   |
| Valve               | 4         | 0.86%   |
| Samsung Electronics | 4         | 0.86%   |
| HUAWEI              | 4         | 0.86%   |
| Fujitsu Siemens     | 4         | 0.86%   |
| Fujitsu             | 4         | 0.86%   |
| Timi                | 3         | 0.64%   |
| Packard Bell        | 3         | 0.64%   |
| eMachines           | 3         | 0.64%   |
| Medion              | 2         | 0.43%   |
| Google              | 2         | 0.43%   |
| Teclast             | 1         | 0.21%   |
| PC Specialist       | 1         | 0.21%   |
| Hampoo              | 1         | 0.21%   |
| GPD                 | 1         | 0.21%   |
| Unknown             | 1         | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| HP Pavilion dv6                     | 5         | 1.07%   |
| Valve Jupiter                       | 4         | 0.86%   |
| ASUS X550CC                         | 4         | 0.86%   |
| HP ProBook 4540s                    | 3         | 0.64%   |
| HP ProBook 4330s                    | 3         | 0.64%   |
| HP Pavilion g6                      | 3         | 0.64%   |
| Acer Swift SF314-43                 | 3         | 0.64%   |
| UMAX VisionBook 14Wr Plus           | 2         | 0.43%   |
| Toshiba Satellite P300              | 2         | 0.43%   |
| Timi Redmi Book Pro 15 2022         | 2         | 0.43%   |
| MSI VR610                           | 2         | 0.43%   |
| Lenovo Yoga Slim 7 Pro 14ITL5 82FX  | 2         | 0.43%   |
| Lenovo Y520-15IKBN 80WK             | 2         | 0.43%   |
| Lenovo ThinkPad P50 20EQS0VV2S      | 2         | 0.43%   |
| Lenovo ThinkBook 15 G3 ACL 21A4     | 2         | 0.43%   |
| Lenovo IdeaPad Z500 20202           | 2         | 0.43%   |
| Lenovo IdeaPad U260 20067           | 2         | 0.43%   |
| Lenovo IdeaPad S145-14AST 81ST      | 2         | 0.43%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2 | 2         | 0.43%   |
| Lenovo IdeaPad 5 15ABA7 82SG        | 2         | 0.43%   |
| Lenovo IdeaPad 320-15IAP 80XR       | 2         | 0.43%   |
| Lenovo G580                         | 2         | 0.43%   |
| HUAWEI KLVL-WXX9                    | 2         | 0.43%   |
| HP ZBook 15 G3                      | 2         | 0.43%   |
| HP ProBook 6570b                    | 2         | 0.43%   |
| HP ProBook 650 G1                   | 2         | 0.43%   |
| HP ProBook 4545s                    | 2         | 0.43%   |
| HP ProBook 450 G5                   | 2         | 0.43%   |
| HP ProBook 4340s                    | 2         | 0.43%   |
| HP Pavilion 11 x360 PC              | 2         | 0.43%   |
| HP Notebook                         | 2         | 0.43%   |
| HP EliteBook 8470p                  | 2         | 0.43%   |
| HP EliteBook 2570p                  | 2         | 0.43%   |
| Dell XPS 15 9570                    | 2         | 0.43%   |
| Dell Precision 7530                 | 2         | 0.43%   |
| Dell Latitude E7270                 | 2         | 0.43%   |
| Dell Latitude E6540                 | 2         | 0.43%   |
| Dell Latitude E5430 non-vPro        | 2         | 0.43%   |
| Dell Latitude 5490                  | 2         | 0.43%   |
| Dell Latitude 5401                  | 2         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 54        | 11.59%  |
| Lenovo IdeaPad           | 36        | 7.73%   |
| Dell Latitude            | 33        | 7.08%   |
| HP ProBook               | 29        | 6.22%   |
| Acer Aspire              | 20        | 4.29%   |
| HP Pavilion              | 17        | 3.65%   |
| Toshiba Satellite        | 16        | 3.43%   |
| HP EliteBook             | 14        | 3%      |
| Dell XPS                 | 8         | 1.72%   |
| ASUS VivoBook            | 8         | 1.72%   |
| Dell Vostro              | 7         | 1.5%    |
| Acer Swift               | 7         | 1.5%    |
| Dell Inspiron            | 6         | 1.29%   |
| Acer Extensa             | 6         | 1.29%   |
| ASUS ROG                 | 5         | 1.07%   |
| Valve Jupiter            | 4         | 0.86%   |
| Lenovo Yoga              | 4         | 0.86%   |
| HP ZBook                 | 4         | 0.86%   |
| ASUS Zenbook             | 4         | 0.86%   |
| ASUS X550CC              | 4         | 0.86%   |
| UMAX VisionBook          | 3         | 0.64%   |
| Lenovo Legion            | 3         | 0.64%   |
| HP Laptop                | 3         | 0.64%   |
| HP 250                   | 3         | 0.64%   |
| Fujitsu LIFEBOOK         | 3         | 0.64%   |
| Dell Precision           | 3         | 0.64%   |
| Timi Redmi               | 2         | 0.43%   |
| Packard Bell EasyNote    | 2         | 0.43%   |
| MSI VR610                | 2         | 0.43%   |
| MSI Prestige             | 2         | 0.43%   |
| Lenovo Y520-15IKBN       | 2         | 0.43%   |
| Lenovo V15               | 2         | 0.43%   |
| Lenovo ThinkBook         | 2         | 0.43%   |
| Lenovo G580              | 2         | 0.43%   |
| Lenovo 3000              | 2         | 0.43%   |
| HUAWEI KLVL-WXX9         | 2         | 0.43%   |
| HP Notebook              | 2         | 0.43%   |
| HP Compaq                | 2         | 0.43%   |
| HP 255                   | 2         | 0.43%   |
| Fujitsu Siemens LIFEBOOK | 2         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 48        | 10.3%   |
| 2013 | 42        | 9.01%   |
| 2019 | 37        | 7.94%   |
| 2011 | 37        | 7.94%   |
| 2008 | 31        | 6.65%   |
| 2021 | 30        | 6.44%   |
| 2020 | 28        | 6.01%   |
| 2010 | 28        | 6.01%   |
| 2017 | 27        | 5.79%   |
| 2018 | 25        | 5.36%   |
| 2016 | 23        | 4.94%   |
| 2007 | 22        | 4.72%   |
| 2014 | 20        | 4.29%   |
| 2009 | 20        | 4.29%   |
| 2022 | 18        | 3.86%   |
| 2015 | 17        | 3.65%   |
| 2006 | 8         | 1.72%   |
| 2023 | 4         | 0.86%   |
| 2005 | 1         | 0.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 466       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 421       | 89.77%  |
| Enabled  | 48        | 10.23%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 464       | 99.57%  |
| Yes  | 2         | 0.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 128       | 27.18%  |
| 3.01-4.0    | 123       | 26.11%  |
| 16.01-24.0  | 72        | 15.29%  |
| 8.01-16.0   | 69        | 14.65%  |
| 1.01-2.0    | 32        | 6.79%   |
| 32.01-64.0  | 18        | 3.82%   |
| 2.01-3.0    | 14        | 2.97%   |
| 0.51-1.0    | 6         | 1.27%   |
| 24.01-32.0  | 5         | 1.06%   |
| 64.01-256.0 | 4         | 0.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 190       | 37.4%   |
| 2.01-3.0   | 108       | 21.26%  |
| 0.51-1.0   | 68        | 13.39%  |
| 3.01-4.0   | 57        | 11.22%  |
| 4.01-8.0   | 52        | 10.24%  |
| 8.01-16.0  | 19        | 3.74%   |
| 0.01-0.5   | 11        | 2.17%   |
| 16.01-24.0 | 2         | 0.39%   |
| 32.01-64.0 | 1         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 345       | 71.43%  |
| 2      | 111       | 22.98%  |
| 3      | 19        | 3.93%   |
| 0      | 8         | 1.66%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 264       | 56.53%  |
| Yes       | 203       | 43.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 390       | 83.51%  |
| No        | 77        | 16.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 460       | 98.71%  |
| No        | 6         | 1.29%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 349       | 74.26%  |
| No        | 121       | 25.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Slovakia | 466       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Bratislava             | 174       | 34.12%  |
| Košice                | 25        | 4.9%    |
| Banská Bystrica       | 23        | 4.51%   |
| Nitra                  | 20        | 3.92%   |
| Prešov                | 11        | 2.16%   |
| Žilina                | 10        | 1.96%   |
| Trnava                 | 10        | 1.96%   |
| Martin                 | 9         | 1.76%   |
| Humenné               | 8         | 1.57%   |
| Bardejov               | 6         | 1.18%   |
| Poprad                 | 5         | 0.98%   |
| Nové Zámky           | 5         | 0.98%   |
| Levice                 | 5         | 0.98%   |
| Brezno                 | 5         | 0.98%   |
| Zvolen                 | 4         | 0.78%   |
| Trenčín              | 4         | 0.78%   |
| Tornaľa               | 4         | 0.78%   |
| Topoľčany            | 4         | 0.78%   |
| Soblahov               | 4         | 0.78%   |
| Senec                  | 4         | 0.78%   |
| Lučenec               | 4         | 0.78%   |
| Galanta                | 4         | 0.78%   |
| Velky Krtis            | 3         | 0.59%   |
| Štúrovo              | 3         | 0.59%   |
| Rožňava              | 3         | 0.59%   |
| Pezinok                | 3         | 0.59%   |
| Nové Mesto nad Váhom | 3         | 0.59%   |
| Námestovo             | 3         | 0.59%   |
| Kysucké Nové Mesto   | 3         | 0.59%   |
| Dunajská Streda       | 3         | 0.59%   |
| Voderady               | 2         | 0.39%   |
| Vlkova                 | 2         | 0.39%   |
| Velky Meder            | 2         | 0.39%   |
| Stara Tura             | 2         | 0.39%   |
| Spišská Nová Ves    | 2         | 0.39%   |
| Skalica                | 2         | 0.39%   |
| Sereg                  | 2         | 0.39%   |
| Šaľa                 | 2         | 0.39%   |
| Šahy                  | 2         | 0.39%   |
| Ružomberok            | 2         | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 79        | 96     | 13.26%  |
| Seagate                     | 77        | 89     | 12.92%  |
| WDC                         | 74        | 106    | 12.42%  |
| Toshiba                     | 42        | 59     | 7.05%   |
| Kingston                    | 38        | 52     | 6.38%   |
| SanDisk                     | 33        | 42     | 5.54%   |
| Unknown                     | 32        | 51     | 5.37%   |
| Intel                       | 23        | 31     | 3.86%   |
| Hitachi                     | 22        | 22     | 3.69%   |
| Patriot                     | 21        | 30     | 3.52%   |
| Micron Technology           | 21        | 26     | 3.52%   |
| SK hynix                    | 20        | 24     | 3.36%   |
| Crucial                     | 15        | 19     | 2.52%   |
| A-DATA Technology           | 15        | 22     | 2.52%   |
| HGST                        | 14        | 18     | 2.35%   |
| Apacer                      | 6         | 8      | 1.01%   |
| Verbatim                    | 5         | 6      | 0.84%   |
| Fujitsu                     | 5         | 5      | 0.84%   |
| Phison Electronics          | 4         | 4      | 0.67%   |
| LITEON                      | 4         | 4      | 0.67%   |
| KIOXIA                      | 4         | 15     | 0.67%   |
| Unknown                     | 4         | 4      | 0.67%   |
| Apple                       | 3         | 4      | 0.5%    |
| Union Memory                | 2         | 2      | 0.34%   |
| Transcend                   | 2         | 2      | 0.34%   |
| Phison                      | 2         | 2      | 0.34%   |
| OCZ                         | 2         | 2      | 0.34%   |
| LITEONIT                    | 2         | 2      | 0.34%   |
| China                       | 2         | 3      | 0.34%   |
| ZTE                         | 1         | 1      | 0.17%   |
| WDC WDS2                    | 1         | 1      | 0.17%   |
| StoreJet                    | 1         | 1      | 0.17%   |
| Solid State Storage         | 1         | 1      | 0.17%   |
| Micron/Crucial Technology   | 1         | 1      | 0.17%   |
| Lenovo                      | 1         | 1      | 0.17%   |
| Kingston Technology Company | 1         | 1      | 0.17%   |
| KingSpec                    | 1         | 1      | 0.17%   |
| KingDian                    | 1         | 3      | 0.17%   |
| KBG50ZNV                    | 1         | 1      | 0.17%   |
| JMicron Technology          | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Patriot Burst 240GB SSD                             | 11        | 1.76%   |
| Samsung SSD 860 EVO 500GB                           | 10        | 1.6%    |
| Unknown MMC Card  64GB                              | 7         | 1.12%   |
| Patriot Burst 480GB SSD                             | 7         | 1.12%   |
| Seagate ST9500325AS 500GB                           | 6         | 0.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 6         | 0.96%   |
| Kingston SA400S37240G 240GB SSD                     | 6         | 0.96%   |
| Kingston SA400S37120G 120GB SSD                     | 6         | 0.96%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 5         | 0.8%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 5         | 0.8%    |
| Seagate ST9500420AS 500GB                           | 5         | 0.8%    |
| Seagate ST1000LM035-1RK172 1TB                      | 5         | 0.8%    |
| SanDisk NVMe SSD Drive 1024GB                       | 5         | 0.8%    |
| Samsung SSD 850 EVO 500GB                           | 5         | 0.8%    |
| Kingston SV300S37A120G 120GB SSD                    | 5         | 0.8%    |
| Unknown MMC Card  1GB                               | 4         | 0.64%   |
| Toshiba MQ01ABF050 500GB                            | 4         | 0.64%   |
| Seagate ST500LT012-9WS142 500GB                     | 4         | 0.64%   |
| SanDisk NVMe SSD Drive 512GB                        | 4         | 0.64%   |
| Samsung SSD 870 EVO 500GB                           | 4         | 0.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 4         | 0.64%   |
| HGST HTS725050A7E630 500GB                          | 4         | 0.64%   |
| Crucial CT120BX500SSD1 120GB                        | 4         | 0.64%   |
| Unknown                                             | 4         | 0.64%   |
| Unknown MMC Card  32GB                              | 3         | 0.48%   |
| Unknown MMC Card  16GB                              | 3         | 0.48%   |
| Toshiba NVMe SSD Drive 512GB                        | 3         | 0.48%   |
| Toshiba MQ04ABF100 1TB                              | 3         | 0.48%   |
| Toshiba MQ01ABD100 1TB                              | 3         | 0.48%   |
| Toshiba MQ01ABD050 500GB                            | 3         | 0.48%   |
| SK hynix NVMe SSD Drive 512GB                       | 3         | 0.48%   |
| Seagate ST9750420AS 752GB                           | 3         | 0.48%   |
| Seagate ST9250827AS 250GB                           | 3         | 0.48%   |
| Seagate ST9250315AS 250GB                           | 3         | 0.48%   |
| Seagate ST500LM000-SSHD-8GB                         | 3         | 0.48%   |
| Seagate ST500LM000-1EJ162 500GB                     | 3         | 0.48%   |
| Seagate ST2000LM007-1R8174 2TB                      | 3         | 0.48%   |
| Samsung SSD 860 EVO 250GB                           | 3         | 0.48%   |
| Samsung SSD 850 EVO 250GB                           | 3         | 0.48%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 3         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 77        | 89     | 38.31%  |
| WDC                 | 50        | 77     | 24.88%  |
| Toshiba             | 29        | 46     | 14.43%  |
| Hitachi             | 22        | 22     | 10.95%  |
| HGST                | 14        | 18     | 6.97%   |
| Fujitsu             | 5         | 5      | 2.49%   |
| StoreJet            | 1         | 1      | 0.5%    |
| Samsung Electronics | 1         | 2      | 0.5%    |
| IBM/Hitachi         | 1         | 1      | 0.5%    |
| HGST HTS            | 1         | 1      | 0.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 44        | 48     | 20.18%  |
| Kingston            | 31        | 45     | 14.22%  |
| Patriot             | 20        | 28     | 9.17%   |
| SanDisk             | 17        | 20     | 7.8%    |
| WDC                 | 15        | 18     | 6.88%   |
| Crucial             | 15        | 19     | 6.88%   |
| A-DATA Technology   | 13        | 20     | 5.96%   |
| Intel               | 11        | 15     | 5.05%   |
| Micron Technology   | 7         | 9      | 3.21%   |
| Toshiba             | 6         | 6      | 2.75%   |
| Verbatim            | 5         | 6      | 2.29%   |
| Apacer              | 5         | 7      | 2.29%   |
| SK hynix            | 4         | 4      | 1.83%   |
| LITEON              | 4         | 4      | 1.83%   |
| Union Memory        | 2         | 2      | 0.92%   |
| Transcend           | 2         | 2      | 0.92%   |
| OCZ                 | 2         | 2      | 0.92%   |
| LITEONIT            | 2         | 2      | 0.92%   |
| China               | 2         | 3      | 0.92%   |
| WDC WDS2            | 1         | 1      | 0.46%   |
| KingSpec            | 1         | 1      | 0.46%   |
| KingDian            | 1         | 3      | 0.46%   |
| Intenso             | 1         | 1      | 0.46%   |
| IM3D                | 1         | 1      | 0.46%   |
| HS-SSD-E100         | 1         | 1      | 0.46%   |
| Hewlett-Packard     | 1         | 1      | 0.46%   |
| Gigabyte Technology | 1         | 1      | 0.46%   |
| Faspeed             | 1         | 1      | 0.46%   |
| Apple               | 1         | 1      | 0.46%   |
| 2.5                 | 1         | 1      | 0.46%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 195       | 273    | 35.07%  |
| HDD     | 190       | 262    | 34.17%  |
| NVMe    | 130       | 180    | 23.38%  |
| MMC     | 36        | 55     | 6.47%   |
| Unknown | 5         | 5      | 0.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 336       | 519    | 64.24%  |
| NVMe | 130       | 178    | 24.86%  |
| MMC  | 36        | 55     | 6.88%   |
| SAS  | 21        | 23     | 4.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 277       | 404    | 74.86%  |
| 0.51-1.0   | 81        | 115    | 21.89%  |
| 1.01-2.0   | 11        | 15     | 2.97%   |
| 3.01-4.0   | 1         | 1      | 0.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 131       | 26.25%  |
| 251-500        | 107       | 21.44%  |
| 501-1000       | 67        | 13.43%  |
| 1-20           | 52        | 10.42%  |
| 51-100         | 39        | 7.82%   |
| Unknown        | 39        | 7.82%   |
| 21-50          | 30        | 6.01%   |
| 1001-2000      | 24        | 4.81%   |
| 2001-3000      | 6         | 1.2%    |
| More than 3000 | 4         | 0.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 206       | 40.63%  |
| 21-50          | 87        | 17.16%  |
| 101-250        | 60        | 11.83%  |
| 51-100         | 58        | 11.44%  |
| Unknown        | 39        | 7.69%   |
| 251-500        | 32        | 6.31%   |
| 501-1000       | 15        | 2.96%   |
| 1001-2000      | 8         | 1.58%   |
| More than 3000 | 2         | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MK7575GSX 752GB                        | 2         | 3      | 3.45%   |
| Seagate ST500LM000-SSHD-8GB                    | 2         | 2      | 3.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 1         | 1      | 1.72%   |
| WDC WD7500BPVT-80HXZT3 752GB                   | 1         | 1      | 1.72%   |
| WDC WD5000LPVT-24G33T1 500GB                   | 1         | 1      | 1.72%   |
| WDC WD5000BPVT-00HXZT1 500GB                   | 1         | 1      | 1.72%   |
| WDC WD5000BEKT-22KA9T0 500GB                   | 1         | 2      | 1.72%   |
| WDC WD3200BEVT-75ZCT2 320GB                    | 1         | 1      | 1.72%   |
| WDC WD10JPLX-00MBPT0 1TB                       | 1         | 8      | 1.72%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 3      | 1.72%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 1.72%   |
| Toshiba MQ01ABD075 752GB                       | 1         | 1      | 1.72%   |
| Toshiba MK5056GSY 500GB                        | 1         | 1      | 1.72%   |
| Toshiba MK3252GSX 320GB                        | 1         | 1      | 1.72%   |
| Toshiba MK1646GSX 160GB                        | 1         | 2      | 1.72%   |
| Toshiba MK1637GSX 160GB                        | 1         | 1      | 1.72%   |
| SK hynix SC300 mSATA 512GB SSD                 | 1         | 1      | 1.72%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB        | 1         | 1      | 1.72%   |
| Seagate ST980811AS 80GB                        | 1         | 1      | 1.72%   |
| Seagate ST96812AS 64GB                         | 1         | 1      | 1.72%   |
| Seagate ST9500423AS 500GB                      | 1         | 1      | 1.72%   |
| Seagate ST9500420AS 500GB                      | 1         | 1      | 1.72%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 1.72%   |
| Seagate ST940210AS 40GB                        | 1         | 1      | 1.72%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 1.72%   |
| Seagate ST9120823ASG 120GB                     | 1         | 1      | 1.72%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 1.72%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 1.72%   |
| Seagate ST500LM000-1EJ162 500GB                | 1         | 2      | 1.72%   |
| Seagate ST320LT020-9YG142 320GB                | 1         | 3      | 1.72%   |
| Seagate ST320LT007-9ZV142 320GB                | 1         | 1      | 1.72%   |
| Seagate ST2000LX001-1RG174 2TB                 | 1         | 1      | 1.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 1         | 1      | 1.72%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD            | 1         | 1      | 1.72%   |
| SanDisk iSSD P4 8GB                            | 1         | 2      | 1.72%   |
| Samsung Electronics SSD 960 EVO 500GB          | 1         | 1      | 1.72%   |
| Samsung Electronics HS122JC 120GB              | 1         | 2      | 1.72%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 1.72%   |
| Micron Technology 1100 SATA 256GB SSD          | 1         | 1      | 1.72%   |
| Lenovo LENSE30256GMSP34MEAT3TA 256GB           | 1         | 1      | 1.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 20     | 29.82%  |
| Hitachi             | 10        | 10     | 17.54%  |
| Toshiba             | 9         | 13     | 15.79%  |
| WDC                 | 6         | 15     | 10.53%  |
| SK hynix            | 2         | 2      | 3.51%   |
| SanDisk             | 2         | 3      | 3.51%   |
| Samsung Electronics | 2         | 3      | 3.51%   |
| Micron Technology   | 2         | 2      | 3.51%   |
| Kingston            | 2         | 2      | 3.51%   |
| Intel               | 2         | 2      | 3.51%   |
| Lenovo              | 1         | 1      | 1.75%   |
| IM3D                | 1         | 1      | 1.75%   |
| HGST                | 1         | 1      | 1.75%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 20     | 39.53%  |
| Hitachi             | 10        | 10     | 23.26%  |
| Toshiba             | 9         | 13     | 20.93%  |
| WDC                 | 5         | 14     | 11.63%  |
| Samsung Electronics | 1         | 2      | 2.33%   |
| HGST                | 1         | 1      | 2.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 41        | 60     | 74.55%  |
| SSD  | 11        | 12     | 20%     |
| NVMe | 3         | 3      | 5.45%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 272       | 413    | 54.4%   |
| Works    | 172       | 286    | 34.4%   |
| Malfunc  | 55        | 75     | 11%     |
| Failed   | 1         | 1      | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 322       | 61.22%  |
| AMD                              | 66        | 12.55%  |
| Samsung Electronics              | 39        | 7.41%   |
| SanDisk                          | 24        | 4.56%   |
| SK hynix                         | 16        | 3.04%   |
| Micron Technology                | 14        | 2.66%   |
| Kingston Technology Company      | 8         | 1.52%   |
| Toshiba America Info Systems     | 7         | 1.33%   |
| Nvidia                           | 7         | 1.33%   |
| Phison Electronics               | 6         | 1.14%   |
| KIOXIA                           | 4         | 0.76%   |
| Silicon Integrated Systems [SiS] | 3         | 0.57%   |
| ADATA Technology                 | 3         | 0.57%   |
| Apple                            | 2         | 0.38%   |
| Solid State Storage Technology   | 1         | 0.19%   |
| Silicon Image                    | 1         | 0.19%   |
| Micron/Crucial Technology        | 1         | 0.19%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.19%   |
| Lenovo                           | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 51        | 8.66%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 47        | 7.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 26        | 4.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 25        | 4.24%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 21        | 3.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 21        | 3.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 20        | 3.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 20        | 3.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 18        | 3.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 16        | 2.72%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 13        | 2.21%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 11        | 1.87%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 10        | 1.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 1.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 10        | 1.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 9         | 1.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 1.53%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 1.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 8         | 1.36%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 1.19%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 6         | 1.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 1.02%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 6         | 1.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 6         | 1.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 1.02%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 6         | 1.02%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 6         | 1.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 6         | 1.02%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 6         | 1.02%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 6         | 1.02%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 6         | 1.02%   |
| AMD SB600 IDE                                                                  | 6         | 1.02%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 5         | 0.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 5         | 0.85%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 4         | 0.68%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 4         | 0.68%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 4         | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 0.68%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 4         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 332       | 59.18%  |
| NVMe | 131       | 23.35%  |
| IDE  | 68        | 12.12%  |
| RAID | 30        | 5.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 371       | 79.61%  |
| AMD    | 95        | 20.39%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz           | 9         | 1.93%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 8         | 1.72%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 7         | 1.5%    |
| AMD Ryzen 5 5500U with Radeon Graphics      | 7         | 1.5%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 6         | 1.29%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 6         | 1.29%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 6         | 1.29%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 5         | 1.07%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 5         | 1.07%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 5         | 1.07%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz      | 4         | 0.86%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 4         | 0.86%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 4         | 0.86%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 4         | 0.86%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 4         | 0.86%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 4         | 0.86%   |
| Intel Core i3-5010U CPU @ 2.10GHz           | 4         | 0.86%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 4         | 0.86%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 4         | 0.86%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 0.86%   |
| AMD Custom APU 0405                         | 4         | 0.86%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 3         | 0.64%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz      | 3         | 0.64%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 3         | 0.64%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 3         | 0.64%   |
| Intel Pentium CPU 2117U @ 1.80GHz           | 3         | 0.64%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 3         | 0.64%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 3         | 0.64%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 0.64%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 3         | 0.64%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 3         | 0.64%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 3         | 0.64%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 3         | 0.64%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 3         | 0.64%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 3         | 0.64%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 0.64%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 0.64%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 0.64%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 3         | 0.64%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 3         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 104       | 22.32%  |
| Intel Core i7                        | 71        | 15.24%  |
| Intel Core i3                        | 43        | 9.23%   |
| Intel Core 2 Duo                     | 31        | 6.65%   |
| Other                                | 30        | 6.44%   |
| Intel Pentium                        | 30        | 6.44%   |
| Intel Celeron                        | 24        | 5.15%   |
| AMD Ryzen 5                          | 21        | 4.51%   |
| AMD Ryzen 7                          | 13        | 2.79%   |
| Intel Atom                           | 10        | 2.15%   |
| Intel Pentium Dual                   | 9         | 1.93%   |
| Intel Pentium Dual-Core              | 7         | 1.5%    |
| AMD E                                | 5         | 1.07%   |
| AMD A8                               | 5         | 1.07%   |
| AMD A6                               | 5         | 1.07%   |
| Intel Celeron M                      | 4         | 0.86%   |
| Intel Celeron Dual-Core              | 4         | 0.86%   |
| AMD Ryzen 9                          | 4         | 0.86%   |
| AMD Ryzen 7 PRO                      | 4         | 0.86%   |
| AMD Ryzen 3                          | 4         | 0.86%   |
| AMD A10                              | 4         | 0.86%   |
| Intel Genuine                        | 3         | 0.64%   |
| Intel Core 2                         | 3         | 0.64%   |
| AMD Athlon 64 X2                     | 3         | 0.64%   |
| AMD A4                               | 3         | 0.64%   |
| Intel Pentium M                      | 2         | 0.43%   |
| Intel Core 2 Quad                    | 2         | 0.43%   |
| AMD Turion 64 Mobile                 | 2         | 0.43%   |
| AMD Ryzen 5 PRO                      | 2         | 0.43%   |
| AMD E1                               | 2         | 0.43%   |
| AMD Athlon II                        | 2         | 0.43%   |
| AMD Athlon                           | 2         | 0.43%   |
| Intel Pentium Silver                 | 1         | 0.21%   |
| AMD V140                             | 1         | 0.21%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.21%   |
| AMD Turion X2 Dual-Core Mobile       | 1         | 0.21%   |
| AMD Turion 64 X2 Mobile              | 1         | 0.21%   |
| AMD PRO A10                          | 1         | 0.21%   |
| AMD Mobile Sempron                   | 1         | 0.21%   |
| AMD E2                               | 1         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 259       | 55.58%  |
| 4       | 126       | 27.04%  |
| 6       | 32        | 6.87%   |
| 8       | 23        | 4.94%   |
| 1       | 20        | 4.29%   |
| 12      | 2         | 0.43%   |
| 10      | 2         | 0.43%   |
| 16      | 1         | 0.21%   |
| Unknown | 1         | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 466       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 296       | 63.52%  |
| 1       | 168       | 36.05%  |
| 4       | 1         | 0.21%   |
| Unknown | 1         | 0.21%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 451       | 95.96%  |
| Unknown        | 10        | 2.13%   |
| 32-bit         | 9         | 1.91%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 114       | 23.7%   |
| 0x306a9    | 43        | 8.94%   |
| 0x206a7    | 32        | 6.65%   |
| 0x1067a    | 20        | 4.16%   |
| 0x806ea    | 14        | 2.91%   |
| 0x306c3    | 13        | 2.7%    |
| 0x20655    | 13        | 2.7%    |
| 0x6fd      | 12        | 2.49%   |
| 0x906ea    | 11        | 2.29%   |
| 0x406e3    | 10        | 2.08%   |
| 0x806ec    | 9         | 1.87%   |
| 0x806e9    | 9         | 1.87%   |
| 0x806c1    | 9         | 1.87%   |
| 0x10676    | 9         | 1.87%   |
| 0x506e3    | 7         | 1.46%   |
| 0x40651    | 7         | 1.46%   |
| 0x30678    | 7         | 1.46%   |
| 0x20652    | 7         | 1.46%   |
| 0x0a50000c | 7         | 1.46%   |
| 0x08608103 | 7         | 1.46%   |
| 0x306d4    | 6         | 1.25%   |
| 0x06006705 | 6         | 1.25%   |
| 0x506c9    | 4         | 0.83%   |
| 0x406c3    | 4         | 0.83%   |
| 0x106ca    | 4         | 0.83%   |
| 0x08600106 | 4         | 0.83%   |
| 0x08108109 | 4         | 0.83%   |
| 0x08108102 | 4         | 0.83%   |
| 0x07030105 | 4         | 0.83%   |
| 0x05000119 | 4         | 0.83%   |
| 0xa0652    | 3         | 0.62%   |
| 0x906ed    | 3         | 0.62%   |
| 0x906e9    | 3         | 0.62%   |
| 0x706a8    | 3         | 0.62%   |
| 0x706a1    | 3         | 0.62%   |
| 0x6e8      | 3         | 0.62%   |
| 0x6d8      | 3         | 0.62%   |
| 0x10661    | 3         | 0.62%   |
| 0x08608102 | 3         | 0.62%   |
| 0x706e5    | 2         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 65        | 13.95%  |
| IvyBridge        | 48        | 10.3%   |
| SandyBridge      | 37        | 7.94%   |
| Penryn           | 35        | 7.51%   |
| Haswell          | 28        | 6.01%   |
| Unknown          | 27        | 5.79%   |
| Core             | 26        | 5.58%   |
| Westmere         | 24        | 5.15%   |
| Skylake          | 24        | 5.15%   |
| Silvermont       | 16        | 3.43%   |
| TigerLake        | 13        | 2.79%   |
| Zen 3            | 11        | 2.36%   |
| Excavator        | 11        | 2.36%   |
| Zen 2            | 10        | 2.15%   |
| Zen+             | 9         | 1.93%   |
| Broadwell        | 9         | 1.93%   |
| P6               | 8         | 1.72%   |
| K8 Hammer        | 8         | 1.72%   |
| Bonnell          | 7         | 1.5%    |
| Goldmont plus    | 6         | 1.29%   |
| Goldmont         | 6         | 1.29%   |
| Bobcat           | 5         | 1.07%   |
| Puma             | 4         | 0.86%   |
| Piledriver       | 4         | 0.86%   |
| IceLake          | 4         | 0.86%   |
| CometLake        | 4         | 0.86%   |
| Zen              | 3         | 0.64%   |
| K8 & K10 hybrid  | 3         | 0.64%   |
| K10              | 3         | 0.64%   |
| Alderlake Hybrid | 3         | 0.64%   |
| K10 Llano        | 2         | 0.43%   |
| Steamroller      | 1         | 0.21%   |
| Nehalem          | 1         | 0.21%   |
| Jaguar           | 1         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 322       | 55.42%  |
| Nvidia                           | 134       | 23.06%  |
| AMD                              | 123       | 21.17%  |
| Silicon Integrated Systems [SiS] | 2         | 0.34%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 45        | 7.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 32        | 5.19%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 18        | 2.92%   |
| Intel Core Processor Integrated Graphics Controller                                      | 18        | 2.92%   |
| Intel UHD Graphics 620                                                                   | 16        | 2.6%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 16        | 2.6%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 16        | 2.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 2.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 2.27%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 1.95%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 1.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 1.79%   |
| AMD Lucienne                                                                             | 11        | 1.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 1.62%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 1.62%   |
| Intel HD Graphics 620                                                                    | 9         | 1.46%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 1.46%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 9         | 1.46%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 8         | 1.3%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 8         | 1.3%    |
| Intel HD Graphics 5500                                                                   | 8         | 1.3%    |
| Intel HD Graphics 530                                                                    | 8         | 1.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 1.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 1.3%    |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 1.14%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 1.14%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 7         | 1.14%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 1.14%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 0.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.65%   |
| Nvidia GK208M [GeForce GT 720M]                                                          | 4         | 0.65%   |
| Intel HD Graphics 630                                                                    | 4         | 0.65%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 0.65%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 4         | 0.65%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 4         | 0.65%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 4         | 0.65%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 0.65%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 217       | 46.17%  |
| Intel + Nvidia | 86        | 18.3%   |
| 1 x AMD        | 82        | 17.45%  |
| 1 x Nvidia     | 38        | 8.09%   |
| Intel + AMD    | 19        | 4.04%   |
| 2 x AMD        | 12        | 2.55%   |
| AMD + Nvidia   | 10        | 2.13%   |
| 2 x Intel      | 4         | 0.85%   |
| 1 x SiS        | 2         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 406       | 86.38%  |
| Proprietary | 51        | 10.85%  |
| Unknown     | 13        | 2.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 256       | 53.67%  |
| 0.01-0.5   | 89        | 18.66%  |
| 1.01-2.0   | 69        | 14.47%  |
| 0.51-1.0   | 34        | 7.13%   |
| 3.01-4.0   | 20        | 4.19%   |
| 2.01-3.0   | 4         | 0.84%   |
| 5.01-6.0   | 3         | 0.63%   |
| 7.01-8.0   | 1         | 0.21%   |
| 8.01-16.0  | 1         | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 89        | 16.82%  |
| LG Display              | 82        | 15.5%   |
| Samsung Electronics     | 71        | 13.42%  |
| Chimei Innolux          | 59        | 11.15%  |
| BOE                     | 53        | 10.02%  |
| Chi Mei Optoelectronics | 32        | 6.05%   |
| Dell                    | 19        | 3.59%   |
| Lenovo                  | 16        | 3.02%   |
| Philips                 | 12        | 2.27%   |
| PANDA                   | 10        | 1.89%   |
| Sharp                   | 9         | 1.7%    |
| Hewlett-Packard         | 9         | 1.7%    |
| Apple                   | 8         | 1.51%   |
| LG Philips              | 7         | 1.32%   |
| Acer                    | 6         | 1.13%   |
| Goldstar                | 4         | 0.76%   |
| CSO                     | 4         | 0.76%   |
| AOC                     | 4         | 0.76%   |
| TMX                     | 3         | 0.57%   |
| HannStar                | 3         | 0.57%   |
| Valve                   | 2         | 0.38%   |
| Toshiba                 | 2         | 0.38%   |
| JDI                     | 2         | 0.38%   |
| InfoVision              | 2         | 0.38%   |
| Iiyama                  | 2         | 0.38%   |
| CPT                     | 2         | 0.38%   |
| Ancor Communications    | 2         | 0.38%   |
| ViewSonic               | 1         | 0.19%   |
| Sony                    | 1         | 0.19%   |
| Seiko/Epson             | 1         | 0.19%   |
| Quanta Display          | 1         | 0.19%   |
| Plain Tree Systems      | 1         | 0.19%   |
| Panasonic               | 1         | 0.19%   |
| MSI                     | 1         | 0.19%   |
| LGD                     | 1         | 0.19%   |
| InnoLux Display         | 1         | 0.19%   |
| HKC                     | 1         | 0.19%   |
| Gigabyte Technology     | 1         | 0.19%   |
| Fujitsu Siemens         | 1         | 0.19%   |
| cPATH                   | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 1.31%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 6         | 1.12%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 6         | 1.12%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.94%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 4         | 0.75%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 0.75%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x194mm 15.5-inch | 4         | 0.75%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 4         | 0.75%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 4         | 0.75%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 330x210mm 15.4-inch     | 3         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 398x232mm 18.1-inch     | 3         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch     | 3         | 0.56%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 3         | 0.56%   |
| BOE LCD Monitor BOE07BB 1920x1080 309x173mm 13.9-inch                    | 3         | 0.56%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 3         | 0.56%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch           | 3         | 0.56%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.56%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 2         | 0.37%   |
| TMX LCD Monitor TMX1560 1920x1080 344x194mm 15.5-inch                    | 2         | 0.37%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3859 1366x768 293x165mm 13.2-inch     | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch    | 2         | 0.37%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                   | 2         | 0.37%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                  | 2         | 0.37%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.37%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch              | 2         | 0.37%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch              | 2         | 0.37%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 2         | 0.37%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch              | 2         | 0.37%   |
| LG Display LCD Monitor LGD054F 1920x1080 344x194mm 15.5-inch             | 2         | 0.37%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 2         | 0.37%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 2         | 0.37%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 2         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 178       | 36.11%  |
| 1366x768 (WXGA)    | 151       | 30.63%  |
| 1280x800 (WXGA)    | 39        | 7.91%   |
| 1600x900 (HD+)     | 28        | 5.68%   |
| 2560x1440 (QHD)    | 16        | 3.25%   |
| 1440x900 (WXGA+)   | 14        | 2.84%   |
| 3840x2160 (4K)     | 13        | 2.64%   |
| 1920x1200 (WUXGA)  | 10        | 2.03%   |
| 1680x1050 (WSXGA+) | 10        | 2.03%   |
| 1024x600           | 6         | 1.22%   |
| 2880x1800          | 4         | 0.81%   |
| 3440x1440          | 3         | 0.61%   |
| 2560x1600          | 3         | 0.61%   |
| 800x1280           | 2         | 0.41%   |
| 3840x2400          | 2         | 0.41%   |
| 3200x2000          | 2         | 0.41%   |
| 2160x1440          | 2         | 0.41%   |
| 3200x1800 (QHD+)   | 1         | 0.2%    |
| 3000x2000          | 1         | 0.2%    |
| 2880x1620          | 1         | 0.2%    |
| 2560x1080          | 1         | 0.2%    |
| 2256x1504          | 1         | 0.2%    |
| 1920x1280          | 1         | 0.2%    |
| 1680x945           | 1         | 0.2%    |
| 1280x720 (HD)      | 1         | 0.2%    |
| 1280x1024 (SXGA)   | 1         | 0.2%    |
| 1024x768 (XGA)     | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 238       | 45.08%  |
| 13      | 62        | 11.74%  |
| 14      | 55        | 10.42%  |
| 24      | 26        | 4.92%   |
| 17      | 25        | 4.73%   |
| 12      | 17        | 3.22%   |
| 23      | 13        | 2.46%   |
| 27      | 12        | 2.27%   |
| 11      | 11        | 2.08%   |
| 18      | 9         | 1.7%    |
| 22      | 8         | 1.52%   |
| 21      | 8         | 1.52%   |
| 10      | 6         | 1.14%   |
| Unknown | 6         | 1.14%   |
| 16      | 5         | 0.95%   |
| 34      | 4         | 0.76%   |
| 31      | 4         | 0.76%   |
| 19      | 4         | 0.76%   |
| 25      | 2         | 0.38%   |
| 20      | 2         | 0.38%   |
| 7       | 2         | 0.38%   |
| 86      | 1         | 0.19%   |
| 84      | 1         | 0.19%   |
| 58      | 1         | 0.19%   |
| 54      | 1         | 0.19%   |
| 50      | 1         | 0.19%   |
| 46      | 1         | 0.19%   |
| 40      | 1         | 0.19%   |
| 33      | 1         | 0.19%   |
| 32      | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 323       | 61.64%  |
| 201-300     | 65        | 12.4%   |
| 501-600     | 47        | 8.97%   |
| 351-400     | 33        | 6.3%    |
| 401-500     | 29        | 5.53%   |
| 701-800     | 6         | 1.15%   |
| 601-700     | 6         | 1.15%   |
| Unknown     | 6         | 1.15%   |
| 1001-1500   | 5         | 0.95%   |
| 1-100       | 2         | 0.38%   |
| 801-900     | 1         | 0.19%   |
| 1501-2000   | 1         | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 367       | 77.75%  |
| 16/10   | 84        | 17.8%   |
| 3/2     | 7         | 1.48%   |
| Unknown | 5         | 1.06%   |
| 21/9    | 4         | 0.85%   |
| 0.67    | 2         | 0.42%   |
| 5/4     | 1         | 0.21%   |
| 4/3     | 1         | 0.21%   |
| 0.56    | 1         | 0.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 235       | 44.68%  |
| 81-90          | 94        | 17.87%  |
| 201-250        | 45        | 8.56%   |
| 71-80          | 23        | 4.37%   |
| 121-130        | 19        | 3.61%   |
| 61-70          | 17        | 3.23%   |
| 301-350        | 12        | 2.28%   |
| 51-60          | 11        | 2.09%   |
| 351-500        | 10        | 1.9%    |
| 141-150        | 10        | 1.9%    |
| 251-300        | 9         | 1.71%   |
| 151-200        | 7         | 1.33%   |
| 131-140        | 7         | 1.33%   |
| 41-50          | 6         | 1.14%   |
| Unknown        | 6         | 1.14%   |
| More than 1000 | 5         | 0.95%   |
| 111-120        | 4         | 0.76%   |
| 1-40           | 2         | 0.38%   |
| 501-1000       | 2         | 0.38%   |
| 91-100         | 2         | 0.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 192       | 36.92%  |
| 101-120       | 156       | 30%     |
| 51-100        | 120       | 23.08%  |
| 161-240       | 23        | 4.42%   |
| More than 240 | 16        | 3.08%   |
| 1-50          | 7         | 1.35%   |
| Unknown       | 6         | 1.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 371       | 78.6%   |
| 2     | 79        | 16.74%  |
| 0     | 14        | 2.97%   |
| 3     | 8         | 1.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 234       | 30.47%  |
| Intel                             | 229       | 29.82%  |
| Qualcomm Atheros                  | 134       | 17.45%  |
| Broadcom                          | 56        | 7.29%   |
| Marvell Technology Group          | 15        | 1.95%   |
| Ralink                            | 14        | 1.82%   |
| Broadcom Limited                  | 14        | 1.82%   |
| MediaTek                          | 8         | 1.04%   |
| Nvidia                            | 6         | 0.78%   |
| Hewlett-Packard                   | 5         | 0.65%   |
| Xiaomi                            | 4         | 0.52%   |
| TP-Link                           | 4         | 0.52%   |
| Dell                              | 4         | 0.52%   |
| Sierra Wireless                   | 3         | 0.39%   |
| Ralink Technology                 | 3         | 0.39%   |
| Qualcomm Atheros Communications   | 3         | 0.39%   |
| Lenovo                            | 3         | 0.39%   |
| JMicron Technology                | 3         | 0.39%   |
| Fibocom                           | 3         | 0.39%   |
| Ericsson Business Mobile Networks | 3         | 0.39%   |
| DisplayLink                       | 3         | 0.39%   |
| Huawei Technologies               | 2         | 0.26%   |
| D-Link                            | 2         | 0.26%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.13%   |
| T & A Mobile Phones               | 1         | 0.13%   |
| Spreadtrum Communications         | 1         | 0.13%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.13%   |
| Sigma Sport                       | 1         | 0.13%   |
| Samsung Electronics               | 1         | 0.13%   |
| Qualcomm                          | 1         | 0.13%   |
| Nokia Mobile Phones               | 1         | 0.13%   |
| ICS Advent                        | 1         | 0.13%   |
| Google                            | 1         | 0.13%   |
| Attansic Technology               | 1         | 0.13%   |
| ASUSTek Computer                  | 1         | 0.13%   |
| ASIX Electronics                  | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 137       | 15.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 48        | 5.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 37        | 4.06%   |
| Intel Wireless 8265 / 8275                                              | 23        | 2.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 18        | 1.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 18        | 1.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 18        | 1.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 17        | 1.87%   |
| Intel Wireless 8260                                                     | 14        | 1.54%   |
| Intel Wi-Fi 6 AX200                                                     | 13        | 1.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 12        | 1.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 12        | 1.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.21%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 1.21%   |
| Intel Wireless 7260                                                     | 11        | 1.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 1.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 1.1%    |
| Intel Wireless 3165                                                     | 10        | 1.1%    |
| Intel Wi-Fi 6 AX201                                                     | 10        | 1.1%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 0.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 9         | 0.99%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 8         | 0.88%   |
| Intel Wireless 7265                                                     | 8         | 0.88%   |
| Intel WiFi Link 5100                                                    | 8         | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 0.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 0.77%   |
| Intel Ethernet Connection I219-LM                                       | 7         | 0.77%   |
| Intel Centrino Wireless-N 2230                                          | 7         | 0.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 0.77%   |
| Intel 82567LM Gigabit Network Connection                                | 7         | 0.77%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 6         | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 6         | 0.66%   |
| Intel Wireless-AC 9260                                                  | 6         | 0.66%   |
| Intel Ethernet Connection (4) I219-LM                                   | 6         | 0.66%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 0.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 0.66%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 0.66%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 5         | 0.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 215       | 44.61%  |
| Qualcomm Atheros                | 114       | 23.65%  |
| Realtek Semiconductor           | 58        | 12.03%  |
| Broadcom                        | 37        | 7.68%   |
| Ralink                          | 14        | 2.9%    |
| Broadcom Limited                | 12        | 2.49%   |
| MediaTek                        | 8         | 1.66%   |
| TP-Link                         | 4         | 0.83%   |
| Dell                            | 4         | 0.83%   |
| Sierra Wireless                 | 3         | 0.62%   |
| Ralink Technology               | 3         | 0.62%   |
| Qualcomm Atheros Communications | 3         | 0.62%   |
| Fibocom                         | 3         | 0.62%   |
| D-Link                          | 2         | 0.41%   |
| Qualcomm                        | 1         | 0.21%   |
| ASUSTek Computer                | 1         | 0.21%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 37        | 7.61%   |
| Intel Wireless 8265 / 8275                                              | 23        | 4.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 18        | 3.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 17        | 3.5%    |
| Intel Wireless 8260                                                     | 14        | 2.88%   |
| Intel Wi-Fi 6 AX200                                                     | 13        | 2.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 2.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 12        | 2.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 12        | 2.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 2.26%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 2.26%   |
| Intel Wireless 7260                                                     | 11        | 2.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 2.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 2.06%   |
| Intel Wireless 3165                                                     | 10        | 2.06%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 2.06%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 1.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 9         | 1.85%   |
| Intel Wireless 7265                                                     | 8         | 1.65%   |
| Intel WiFi Link 5100                                                    | 8         | 1.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 1.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 1.44%   |
| Intel Centrino Wireless-N 2230                                          | 7         | 1.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 1.44%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.23%   |
| Intel Wireless-AC 9260                                                  | 6         | 1.23%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.23%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 1.03%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 1.03%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 5         | 1.03%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 1.03%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 1.03%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 1.03%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 5         | 1.03%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 4         | 0.82%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 0.82%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 4         | 0.82%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 3         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 211       | 51.97%  |
| Intel                     | 95        | 23.4%   |
| Qualcomm Atheros          | 34        | 8.37%   |
| Broadcom                  | 21        | 5.17%   |
| Marvell Technology Group  | 15        | 3.69%   |
| Nvidia                    | 6         | 1.48%   |
| Xiaomi                    | 4         | 0.99%   |
| Lenovo                    | 3         | 0.74%   |
| JMicron Technology        | 3         | 0.74%   |
| DisplayLink               | 3         | 0.74%   |
| Broadcom Limited          | 2         | 0.49%   |
| T & A Mobile Phones       | 1         | 0.25%   |
| Spreadtrum Communications | 1         | 0.25%   |
| Samsung Electronics       | 1         | 0.25%   |
| Nokia Mobile Phones       | 1         | 0.25%   |
| ICS Advent                | 1         | 0.25%   |
| Huawei Technologies       | 1         | 0.25%   |
| Google                    | 1         | 0.25%   |
| Attansic Technology       | 1         | 0.25%   |
| ASIX Electronics          | 1         | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 137       | 33.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 48        | 11.71%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 18        | 4.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 18        | 4.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 8         | 1.95%   |
| Intel Ethernet Connection I219-LM                                              | 7         | 1.71%   |
| Intel 82567LM Gigabit Network Connection                                       | 7         | 1.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 6         | 1.46%   |
| Intel Ethernet Connection (4) I219-LM                                          | 6         | 1.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 5         | 1.22%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 5         | 1.22%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 5         | 1.22%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.22%   |
| Intel Ethernet Connection (7) I219-LM                                          | 5         | 1.22%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 1.22%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 4         | 0.98%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 4         | 0.98%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 0.98%   |
| Intel Ethernet Connection (6) I219-V                                           | 4         | 0.98%   |
| Intel Ethernet Connection (4) I219-V                                           | 4         | 0.98%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 0.98%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 0.73%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 3         | 0.73%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 0.73%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 3         | 0.73%   |
| Intel Ethernet Connection I217-V                                               | 3         | 0.73%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 0.73%   |
| Intel 82566MM Gigabit Network Connection                                       | 3         | 0.73%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 0.73%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 0.73%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.49%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 2         | 0.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 2         | 0.49%   |
| Nvidia MCP77 Ethernet                                                          | 2         | 0.49%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.49%   |
| Lenovo USB-C Dock Ethernet                                                     | 2         | 0.49%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.49%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 0.49%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 0.49%   |
| DisplayLink UG69PD10 Docking                                                   | 2         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 460       | 53.18%  |
| Ethernet | 390       | 45.09%  |
| Modem    | 15        | 1.73%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 375       | 76.53%  |
| Ethernet | 115       | 23.47%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 363       | 77.9%   |
| 1     | 94        | 20.17%  |
| 0     | 7         | 1.5%    |
| 3     | 2         | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 435       | 92.95%  |
| Yes  | 33        | 7.05%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 138       | 38.98%  |
| Qualcomm Atheros Communications | 33        | 9.32%   |
| Realtek Semiconductor           | 30        | 8.47%   |
| IMC Networks                    | 28        | 7.91%   |
| Broadcom                        | 26        | 7.34%   |
| Lite-On Technology              | 19        | 5.37%   |
| Foxconn / Hon Hai               | 13        | 3.67%   |
| Ralink                          | 9         | 2.54%   |
| Hewlett-Packard                 | 9         | 2.54%   |
| Dell                            | 9         | 2.54%   |
| ASUSTek Computer                | 9         | 2.54%   |
| Cambridge Silicon Radio         | 8         | 2.26%   |
| Toshiba                         | 6         | 1.69%   |
| Apple                           | 5         | 1.41%   |
| Foxconn International           | 3         | 0.85%   |
| Taiyo Yuden                     | 2         | 0.56%   |
| Realtek                         | 2         | 0.56%   |
| Micro Star International        | 2         | 0.56%   |
| USI                             | 1         | 0.28%   |
| Fujitsu                         | 1         | 0.28%   |
| Alps Electric                   | 1         | 0.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 64        | 18.08%  |
| Realtek Bluetooth Radio                             | 24        | 6.78%   |
| Intel AX201 Bluetooth                               | 24        | 6.78%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 17        | 4.8%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 17        | 4.8%    |
| Intel AX200 Bluetooth                               | 13        | 3.67%   |
| IMC Networks Bluetooth Radio                        | 10        | 2.82%   |
| Ralink RT3290 Bluetooth                             | 9         | 2.54%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 9         | 2.54%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 2.26%   |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 1.98%   |
| IMC Networks Bluetooth Device                       | 7         | 1.98%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 7         | 1.98%   |
| Lite-On Bluetooth Device                            | 6         | 1.69%   |
| Broadcom HP Portable SoftSailing                    | 6         | 1.69%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 6         | 1.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 1.41%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 5         | 1.41%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 1.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 1.13%   |
| Lite-On Wireless_Device                             | 4         | 1.13%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 1.13%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 0.85%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 0.85%   |
| Intel Bluetooth Device                              | 3         | 0.85%   |
| Intel AX210 Bluetooth                               | 3         | 0.85%   |
| IMC Networks Wireless_Device                        | 3         | 0.85%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.85%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 0.85%   |
| Dell Wireless 370 Bluetooth Mini-card               | 3         | 0.85%   |
| Dell BCM20702A0 Bluetooth Module                    | 3         | 0.85%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.85%   |
| Toshiba Integrated Bluetooth HCI                    | 2         | 0.56%   |
| Toshiba Askey Bluetooth Module                      | 2         | 0.56%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 2         | 0.56%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 0.56%   |
| Micro Star International Bluetooth EDR Device       | 2         | 0.56%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.56%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter          | 2         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 360       | 63.72%  |
| AMD                              | 109       | 19.29%  |
| Nvidia                           | 59        | 10.44%  |
| GN Netcom                        | 5         | 0.88%   |
| C-Media Electronics              | 5         | 0.88%   |
| Lenovo                           | 4         | 0.71%   |
| Silicon Integrated Systems [SiS] | 3         | 0.53%   |
| Realtek Semiconductor            | 3         | 0.53%   |
| Samson Technologies              | 2         | 0.35%   |
| JMTek                            | 2         | 0.35%   |
| Focusrite-Novation               | 2         | 0.35%   |
| Yamaha                           | 1         | 0.18%   |
| Trust                            | 1         | 0.18%   |
| Textech International            | 1         | 0.18%   |
| Texas Instruments                | 1         | 0.18%   |
| Plantronics                      | 1         | 0.18%   |
| Logitech                         | 1         | 0.18%   |
| Hewlett-Packard                  | 1         | 0.18%   |
| DCMT Technology                  | 1         | 0.18%   |
| Behringer.......                 | 1         | 0.18%   |
| Apple                            | 1         | 0.18%   |
| AKAI Professional M.I.           | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 57        | 8.48%   |
| AMD Family 17h/19h HD Audio Controller                                     | 47        | 6.99%   |
| Intel Sunrise Point-LP HD Audio                                            | 41        | 6.1%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 29        | 4.32%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 29        | 4.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 28        | 4.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 25        | 3.72%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 22        | 3.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 19        | 2.83%   |
| Intel Cannon Lake PCH cAVS                                                 | 16        | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 15        | 2.23%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 15        | 2.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 14        | 2.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 13        | 1.93%   |
| AMD FCH Azalia Controller                                                  | 13        | 1.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11        | 1.64%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 11        | 1.64%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 10        | 1.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 10        | 1.49%   |
| Nvidia GF108 High Definition Audio Controller                              | 9         | 1.34%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 9         | 1.34%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 1.34%   |
| Intel Comet Lake PCH-LP cAVS                                               | 9         | 1.34%   |
| Intel Broadwell-U Audio Controller                                         | 9         | 1.34%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 1.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 1.34%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 9         | 1.34%   |
| AMD High Definition Audio Controller                                       | 9         | 1.34%   |
| AMD Kabini HDMI/DP Audio                                                   | 7         | 1.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 6         | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 6         | 0.89%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5         | 0.74%   |
| Intel CM238 HD Audio Controller                                            | 5         | 0.74%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 0.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 0.6%    |
| Nvidia MCP79 High Definition Audio                                         | 4         | 0.6%    |
| Nvidia High Definition Audio Controller                                    | 4         | 0.6%    |
| AMD Trinity HDMI Audio Controller                                          | 4         | 0.6%    |
| Realtek Semiconductor USB Audio                                            | 3         | 0.45%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 78        | 24.3%   |
| SK hynix            | 76        | 23.68%  |
| Kingston            | 37        | 11.53%  |
| Unknown             | 36        | 11.21%  |
| Micron Technology   | 35        | 10.9%   |
| Crucial             | 13        | 4.05%   |
| Elpida              | 9         | 2.8%    |
| Ramaxel Technology  | 8         | 2.49%   |
| Unknown (ABCD)      | 5         | 1.56%   |
| Patriot             | 4         | 1.25%   |
| Nanya Technology    | 4         | 1.25%   |
| Corsair             | 4         | 1.25%   |
| A-DATA Technology   | 3         | 0.93%   |
| Apacer              | 2         | 0.62%   |
| Unigen              | 1         | 0.31%   |
| Transcend           | 1         | 0.31%   |
| SHARETRONIC         | 1         | 0.31%   |
| G.Skill             | 1         | 0.31%   |
| Atermiter           | 1         | 0.31%   |
| ASint Technology    | 1         | 0.31%   |
| 48spaces            | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 6         | 1.73%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 1.73%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 1.73%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 1.44%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 5         | 1.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 1.44%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 4         | 1.15%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.15%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.15%   |
| Micron RAM MT8KTF51264HZ-1G6 4GB SODIMM DDR3 1600MT/s            | 4         | 1.15%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.86%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 0.86%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 3         | 0.86%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 3         | 0.86%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.86%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 3         | 0.86%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.86%   |
| Patriot RAM PSD34G16002S 4GB SODIMM DDR3 1600MT/s                | 3         | 0.86%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 3         | 0.86%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s           | 3         | 0.86%   |
| Kingston RAM KHX1866C11S3L/8G 8GB SODIMM DDR3 1867MT/s           | 3         | 0.86%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 3         | 0.86%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 2         | 0.58%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 0.58%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.58%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 2         | 0.58%   |
| SK hynix RAM HYMP112S64CP6-Y5 1GB SODIMM DDR2 667MT/s            | 2         | 0.58%   |
| SK hynix RAM HMT425S6AFR6A-PB 2048MB SODIMM DDR3 3200MT/s        | 2         | 0.58%   |
| SK hynix RAM HMT125S6BFR8C-G7 2048MB SODIMM DDR3 1067MT/s        | 2         | 0.58%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.58%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.58%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.58%   |
| SK hynix RAM H9HCNNNBKMMLXR-NEE 4GB SODIMM LPDDR4 4266MT/s       | 2         | 0.58%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 2         | 0.58%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 0.58%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s            | 2         | 0.58%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.58%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.58%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.58%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 99        | 38.37%  |
| DDR4    | 88        | 34.11%  |
| DDR2    | 27        | 10.47%  |
| LPDDR4  | 14        | 5.43%   |
| SDRAM   | 12        | 4.65%   |
| Unknown | 6         | 2.33%   |
| LPDDR3  | 5         | 1.94%   |
| LPDDR5  | 3         | 1.16%   |
| DDR     | 2         | 0.78%   |
| DRAM    | 1         | 0.39%   |
| DDR5    | 1         | 0.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 233       | 89.62%  |
| Row Of Chips | 21        | 8.08%   |
| Chip         | 4         | 1.54%   |
| DIMM         | 1         | 0.38%   |
| Unknown      | 1         | 0.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 88        | 29.73%  |
| 4096  | 88        | 29.73%  |
| 2048  | 58        | 19.59%  |
| 16384 | 32        | 10.81%  |
| 1024  | 22        | 7.43%   |
| 32768 | 6         | 2.03%   |
| 512   | 2         | 0.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 68        | 23.53%  |
| 2667    | 40        | 13.84%  |
| 3200    | 39        | 13.49%  |
| 667     | 20        | 6.92%   |
| 1334    | 16        | 5.54%   |
| 2400    | 15        | 5.19%   |
| 2133    | 13        | 4.5%    |
| 1333    | 12        | 4.15%   |
| Unknown | 9         | 3.11%   |
| 1067    | 8         | 2.77%   |
| 4199    | 7         | 2.42%   |
| 800     | 6         | 2.08%   |
| 2048    | 5         | 1.73%   |
| 4266    | 4         | 1.38%   |
| 1867    | 4         | 1.38%   |
| 533     | 4         | 1.38%   |
| 4267    | 3         | 1.04%   |
| 8400    | 2         | 0.69%   |
| 6400    | 2         | 0.69%   |
| 4800    | 2         | 0.69%   |
| 3266    | 2         | 0.69%   |
| 975     | 2         | 0.69%   |
| 5500    | 1         | 0.35%   |
| 2933    | 1         | 0.35%   |
| 1866    | 1         | 0.35%   |
| 1639    | 1         | 0.35%   |
| 1066    | 1         | 0.35%   |
| 333     | 1         | 0.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 2         | 40%     |
| Seiko Epson           | 1         | 20%     |
| Samsung Electronics   | 1         | 20%     |
| Lexmark International | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Seiko Epson L382 Series           | 1         | 20%     |
| Samsung M2070 Series              | 1         | 20%     |
| Lexmark International 2600 Series | 1         | 20%     |
| HP LaserJet P1006                 | 1         | 20%     |
| HP LaserJet CP 1025nw             | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 123       | 31.54%  |
| IMC Networks                           | 41        | 10.51%  |
| Bison Electronics                      | 31        | 7.95%   |
| Realtek Semiconductor                  | 30        | 7.69%   |
| Microdia                               | 30        | 7.69%   |
| Suyin                                  | 20        | 5.13%   |
| Sunplus Innovation Technology          | 20        | 5.13%   |
| Syntek                                 | 14        | 3.59%   |
| Quanta                                 | 13        | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 3.33%   |
| Lite-On Technology                     | 8         | 2.05%   |
| Acer                                   | 6         | 1.54%   |
| Alcor Micro                            | 4         | 1.03%   |
| SunplusIT                              | 3         | 0.77%   |
| Silicon Motion                         | 3         | 0.77%   |
| Ricoh                                  | 3         | 0.77%   |
| Logitech                               | 3         | 0.77%   |
| Sonix Technology                       | 2         | 0.51%   |
| Samsung Electronics                    | 2         | 0.51%   |
| Luxvisions Innotech Limited            | 2         | 0.51%   |
| Lenovo                                 | 2         | 0.51%   |
| Importek                               | 2         | 0.51%   |
| GEMBIRD                                | 2         | 0.51%   |
| Apple                                  | 2         | 0.51%   |
| Z-Star Microelectronics                | 1         | 0.26%   |
| Tripath Technology                     | 1         | 0.26%   |
| SN0002                                 | 1         | 0.26%   |
| Primax Electronics                     | 1         | 0.26%   |
| OmniVision Technologies                | 1         | 0.26%   |
| MacroSilicon                           | 1         | 0.26%   |
| LG Electronics                         | 1         | 0.26%   |
| icSpring                               | 1         | 0.26%   |
| Elecom                                 | 1         | 0.26%   |
| DigiTech                               | 1         | 0.26%   |
| ALi                                    | 1         | 0.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 25        | 6.38%   |
| Microdia Integrated_Webcam_HD            | 14        | 3.57%   |
| IMC Networks Integrated Camera           | 11        | 2.81%   |
| Chicony HP HD Webcam [Fixed]             | 10        | 2.55%   |
| Bison Integrated Camera                  | 9         | 2.3%    |
| Realtek Integrated_Webcam_HD             | 8         | 2.04%   |
| Chicony HD WebCam                        | 8         | 2.04%   |
| Syntek Integrated Camera                 | 7         | 1.79%   |
| Realtek USB2.0 HD UVC WebCam             | 7         | 1.79%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 7         | 1.79%   |
| IMC Networks USB2.0 HD UVC WebCam        | 7         | 1.79%   |
| Sunplus Integrated_Webcam_HD             | 6         | 1.53%   |
| Quanta HP HD Camera                      | 6         | 1.53%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 5         | 1.28%   |
| Chicony USB2.0 VGA UVC WebCam            | 5         | 1.28%   |
| Bison Lenovo Integrated Webcam           | 5         | 1.28%   |
| Syntek Lenovo EasyCamera                 | 4         | 1.02%   |
| Suyin HP Webcam                          | 4         | 1.02%   |
| Sunplus HP HD Webcam [Fixed]             | 4         | 1.02%   |
| Microdia Integrated Webcam               | 4         | 1.02%   |
| Lite-On HP HD Camera                     | 4         | 1.02%   |
| IMC Networks Integrated Webcam           | 4         | 1.02%   |
| Chicony USB 2.0 Camera                   | 4         | 1.02%   |
| Chicony Lenovo EasyCamera                | 4         | 1.02%   |
| Chicony HP HD Camera                     | 4         | 1.02%   |
| Bison EasyCamera                         | 4         | 1.02%   |
| Sunplus HD WebCam                        | 3         | 0.77%   |
| Realtek USB Camera                       | 3         | 0.77%   |
| Lite-On Integrated Camera                | 3         | 0.77%   |
| Chicony WebCam                           | 3         | 0.77%   |
| Chicony USB2.0 HD UVC WebCam             | 3         | 0.77%   |
| Chicony USB2.0 0.3M UVC WebCam           | 3         | 0.77%   |
| Chicony TOSHIBA Web Camera - HD          | 3         | 0.77%   |
| Chicony Thinkpad T430 camera             | 3         | 0.77%   |
| Chicony Integrated Camera (1280x720@30)  | 3         | 0.77%   |
| Chicony HP TrueVision HD Camera          | 3         | 0.77%   |
| Chicony HP HD Webcam                     | 3         | 0.77%   |
| Chicony HD User Facing                   | 3         | 0.77%   |
| Chicony EasyCamera                       | 3         | 0.77%   |
| Chicony CNF9055 Toshiba Webcam           | 3         | 0.77%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 43        | 44.79%  |
| Synaptics                          | 23        | 23.96%  |
| AuthenTec                          | 9         | 9.38%   |
| Shenzhen Goodix Technology         | 8         | 8.33%   |
| LighTuning Technology              | 5         | 5.21%   |
| STMicroelectronics                 | 3         | 3.13%   |
| Upek                               | 2         | 2.08%   |
| Elan Microelectronics              | 2         | 2.08%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.04%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 11.46%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 9.38%   |
| Validity Sensors VFS491                                                    | 6         | 6.25%   |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 4.17%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 4.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 4.17%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 4.17%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 3.13%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 3.13%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 3.13%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 3.13%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 3.13%   |
| AuthenTec AES2810                                                          | 3         | 3.13%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 2.08%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 2.08%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.08%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 2.08%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 2.08%   |
| Synaptics  WBDI                                                            | 2         | 2.08%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 2.08%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 2.08%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 2.08%   |
| Elan ELAN:Fingerprint                                                      | 2         | 2.08%   |
| AuthenTec AES1600                                                          | 2         | 2.08%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 1.04%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.04%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.04%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.04%   |
| Synaptics WBDI                                                             | 1         | 1.04%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.04%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 1.04%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.04%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 19        | 43.18%  |
| Alcor Micro | 16        | 36.36%  |
| O2 Micro    | 5         | 11.36%  |
| Lenovo      | 2         | 4.55%   |
| Bit4id      | 2         | 4.55%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 16        | 36.36%  |
| Broadcom 5880                                                                | 7         | 15.91%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 13.64%  |
| Broadcom 58200                                                               | 4         | 9.09%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 6.82%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 4.55%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 4.55%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 4.55%   |
| Bit4id miniLector EVO                                                        | 2         | 4.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 262       | 55.04%  |
| 1     | 169       | 35.5%   |
| 2     | 36        | 7.56%   |
| 3     | 8         | 1.68%   |
| 4     | 1         | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 96        | 36.5%   |
| Graphics card            | 56        | 21.29%  |
| Chipcard                 | 36        | 13.69%  |
| Net/wireless             | 15        | 5.7%    |
| Multimedia controller    | 11        | 4.18%   |
| Bluetooth                | 11        | 4.18%   |
| Storage                  | 8         | 3.04%   |
| Communication controller | 7         | 2.66%   |
| Modem                    | 6         | 2.28%   |
| Card reader              | 6         | 2.28%   |
| Camera                   | 4         | 1.52%   |
| Sound                    | 2         | 0.76%   |
| Network                  | 2         | 0.76%   |
| Flash memory             | 2         | 0.76%   |
| Storage/ide              | 1         | 0.38%   |


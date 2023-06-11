Linux in Netherlands - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Netherlands.

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

Total: 3055

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Samsung       | N150/N210/N220              | [977d645961](https://linux-hardware.org/?probe=977d645961) | Jun 10, 2023 |
| Apple         | MacBookPro9,2               | [f502f89e9d](https://linux-hardware.org/?probe=f502f89e9d) | Jun 10, 2023 |
| Valve         | Jupiter                     | [7a36bdb92a](https://linux-hardware.org/?probe=7a36bdb92a) | Jun 09, 2023 |
| HUAWEI        | MACHC-WAX9                  | [6f26f51ef6](https://linux-hardware.org/?probe=6f26f51ef6) | Jun 09, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [ab95a219f5](https://linux-hardware.org/?probe=ab95a219f5) | Jun 09, 2023 |
| Dell          | Precision 7540              | [41fe2f93ff](https://linux-hardware.org/?probe=41fe2f93ff) | Jun 09, 2023 |
| Lenovo        | ThinkPad T590 20N5000AMH    | [91c0d99427](https://linux-hardware.org/?probe=91c0d99427) | Jun 06, 2023 |
| Dell          | Latitude 7480               | [61c800a3b4](https://linux-hardware.org/?probe=61c800a3b4) | Jun 06, 2023 |
| Dell          | XPS 15 9560                 | [0d326774c9](https://linux-hardware.org/?probe=0d326774c9) | Jun 06, 2023 |
| Dell          | Precision 7540              | [a10ecca056](https://linux-hardware.org/?probe=a10ecca056) | Jun 04, 2023 |
| Toshiba       | Satellite Pro C70-B         | [d4bc6d6c8c](https://linux-hardware.org/?probe=d4bc6d6c8c) | Jun 04, 2023 |
| HP            | Laptop 17-cp0xxx            | [253c561829](https://linux-hardware.org/?probe=253c561829) | Jun 04, 2023 |
| AMI           | Intel                       | [cd2beb79d2](https://linux-hardware.org/?probe=cd2beb79d2) | Jun 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | [6d8d7f6384](https://linux-hardware.org/?probe=6d8d7f6384) | Jun 04, 2023 |
| ASUSTek       | X553MA                      | [d07b3215b1](https://linux-hardware.org/?probe=d07b3215b1) | Jun 03, 2023 |
| Dell          | Latitude E6420              | [4d1ad8d52a](https://linux-hardware.org/?probe=4d1ad8d52a) | Jun 03, 2023 |
| Dell          | XPS 17 9720                 | [71c4a65aae](https://linux-hardware.org/?probe=71c4a65aae) | Jun 03, 2023 |
| Apple         | MacBookAir6,1               | [20a14caf03](https://linux-hardware.org/?probe=20a14caf03) | Jun 03, 2023 |
| Dell          | XPS 15 9530                 | [31400c0b8a](https://linux-hardware.org/?probe=31400c0b8a) | Jun 02, 2023 |
| HUAWEI        | MACHC-WAX9                  | [c87d784c98](https://linux-hardware.org/?probe=c87d784c98) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [6b1168349b](https://linux-hardware.org/?probe=6b1168349b) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [3da98cc9bb](https://linux-hardware.org/?probe=3da98cc9bb) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [98b0b355db](https://linux-hardware.org/?probe=98b0b355db) | Jun 01, 2023 |
| Dell          | Precision 7540              | [de2fc5bc92](https://linux-hardware.org/?probe=de2fc5bc92) | Jun 01, 2023 |
| Valve         | Jupiter                     | [06000e9b0e](https://linux-hardware.org/?probe=06000e9b0e) | Jun 01, 2023 |
| ASUSTek       | X200LA                      | [ae3925153d](https://linux-hardware.org/?probe=ae3925153d) | May 31, 2023 |
| HP            | Laptop 15s-fq1xxx           | [743741a477](https://linux-hardware.org/?probe=743741a477) | May 31, 2023 |
| HP            | Laptop 15s-fq1xxx           | [4c7348e8b3](https://linux-hardware.org/?probe=4c7348e8b3) | May 31, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [87d9c3f3a1](https://linux-hardware.org/?probe=87d9c3f3a1) | May 31, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [7210e5c07e](https://linux-hardware.org/?probe=7210e5c07e) | May 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [6d6d7c65a8](https://linux-hardware.org/?probe=6d6d7c65a8) | May 31, 2023 |
| Dell          | XPS 13 9310                 | [a3e4ffb4fd](https://linux-hardware.org/?probe=a3e4ffb4fd) | May 30, 2023 |
| Acer          | Aspire 5750                 | [fa8eeaabff](https://linux-hardware.org/?probe=fa8eeaabff) | May 30, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [541e16d421](https://linux-hardware.org/?probe=541e16d421) | May 29, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [9178413d40](https://linux-hardware.org/?probe=9178413d40) | May 28, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [cc9d03264f](https://linux-hardware.org/?probe=cc9d03264f) | May 27, 2023 |
| Toshiba       | Satellite Pro C70-B         | [3058a75499](https://linux-hardware.org/?probe=3058a75499) | May 26, 2023 |
| MSI           | CX700                       | [ecb1aaf9c1](https://linux-hardware.org/?probe=ecb1aaf9c1) | May 26, 2023 |
| Dell          | XPS 13 9310                 | [689eec8b51](https://linux-hardware.org/?probe=689eec8b51) | May 26, 2023 |
| Dell          | Latitude 5290               | [fb6cbb6a2f](https://linux-hardware.org/?probe=fb6cbb6a2f) | May 26, 2023 |
| Dell          | Precision 7540              | [99c7b41c6b](https://linux-hardware.org/?probe=99c7b41c6b) | May 25, 2023 |
| Dell          | Inspiron 5759               | [52b95d45ca](https://linux-hardware.org/?probe=52b95d45ca) | May 23, 2023 |
| Apple         | MacBookPro9,1               | [b880d4f8c1](https://linux-hardware.org/?probe=b880d4f8c1) | May 23, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [c77cb59a5c](https://linux-hardware.org/?probe=c77cb59a5c) | May 23, 2023 |
| Dell          | Precision 7540              | [95bbab11f1](https://linux-hardware.org/?probe=95bbab11f1) | May 23, 2023 |
| Packard Be... | EasyNote MH35               | [ea7710b373](https://linux-hardware.org/?probe=ea7710b373) | May 22, 2023 |
| ASUSTek       | X551MA                      | [7a302f637c](https://linux-hardware.org/?probe=7a302f637c) | May 22, 2023 |
| ASUSTek       | X551MA                      | [d0466f101a](https://linux-hardware.org/?probe=d0466f101a) | May 22, 2023 |
| Dell          | XPS 9315                    | [6c3fdbf590](https://linux-hardware.org/?probe=6c3fdbf590) | May 22, 2023 |
| HP            | ZBook 14u G5                | [a655c52b88](https://linux-hardware.org/?probe=a655c52b88) | May 22, 2023 |
| HUAWEI        | MACHC-WAX9                  | [536b91dce1](https://linux-hardware.org/?probe=536b91dce1) | May 21, 2023 |
| MSI           | GF63 Thin 11UC              | [ca280c2e18](https://linux-hardware.org/?probe=ca280c2e18) | May 21, 2023 |
| Lenovo        | ThinkPad T410 2537V32       | [cece14e931](https://linux-hardware.org/?probe=cece14e931) | May 21, 2023 |
| Toshiba       | Satellite C870-1FZ          | [1f2563578e](https://linux-hardware.org/?probe=1f2563578e) | May 20, 2023 |
| HP            | ProBook 650 G3              | [ce80a21736](https://linux-hardware.org/?probe=ce80a21736) | May 19, 2023 |
| Sony          | SVF1521A6EW                 | [49a9f77ea9](https://linux-hardware.org/?probe=49a9f77ea9) | May 18, 2023 |
| Dell          | Latitude 5500               | [f03dddbf42](https://linux-hardware.org/?probe=f03dddbf42) | May 18, 2023 |
| Acer          | Aspire A114-32              | [d17a909427](https://linux-hardware.org/?probe=d17a909427) | May 18, 2023 |
| Acer          | Aspire 7535                 | [32b02980a7](https://linux-hardware.org/?probe=32b02980a7) | May 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [6c83146909](https://linux-hardware.org/?probe=6c83146909) | May 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [1ed7f81c69](https://linux-hardware.org/?probe=1ed7f81c69) | May 18, 2023 |
| HP            | EliteBook 840 14 inch G9... | [004f548439](https://linux-hardware.org/?probe=004f548439) | May 17, 2023 |
| Dell          | Latitude E5510              | [74ecc09f16](https://linux-hardware.org/?probe=74ecc09f16) | May 17, 2023 |
| Dell          | Inspiron 5759               | [228fa2798d](https://linux-hardware.org/?probe=228fa2798d) | May 16, 2023 |
| Dell          | Inspiron 5759               | [32d4567b37](https://linux-hardware.org/?probe=32d4567b37) | May 16, 2023 |
| Framework     | Laptop                      | [b8739c141d](https://linux-hardware.org/?probe=b8739c141d) | May 16, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | [de2456eae8](https://linux-hardware.org/?probe=de2456eae8) | May 16, 2023 |
| Dell          | Latitude 5320               | [c33be8e25c](https://linux-hardware.org/?probe=c33be8e25c) | May 16, 2023 |
| Dell          | Latitude 5320               | [5e8463c682](https://linux-hardware.org/?probe=5e8463c682) | May 16, 2023 |
| Dell          | Latitude 5320               | [093e6a63c8](https://linux-hardware.org/?probe=093e6a63c8) | May 16, 2023 |
| Samsung       | N150/N210/N220              | [3f18889439](https://linux-hardware.org/?probe=3f18889439) | May 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7978974828](https://linux-hardware.org/?probe=7978974828) | May 14, 2023 |
| HP            | ZBook 15u G5                | [4f1f52ce64](https://linux-hardware.org/?probe=4f1f52ce64) | May 14, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [acc449dad2](https://linux-hardware.org/?probe=acc449dad2) | May 14, 2023 |
| SKIKK         | Niflheim 17 II              | [ce9c27f16f](https://linux-hardware.org/?probe=ce9c27f16f) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [58557ae6a2](https://linux-hardware.org/?probe=58557ae6a2) | May 12, 2023 |
| MSI           | Stealth GS77 12UH           | [08fdf9cb20](https://linux-hardware.org/?probe=08fdf9cb20) | May 12, 2023 |
| HP            | EliteBook 720 G2            | [d6a156003b](https://linux-hardware.org/?probe=d6a156003b) | May 12, 2023 |
| Dell          | Latitude E7450              | [9dbbae1356](https://linux-hardware.org/?probe=9dbbae1356) | May 12, 2023 |
| HP            | 255 G7 Notebook PC          | [341a5673f2](https://linux-hardware.org/?probe=341a5673f2) | May 12, 2023 |
| HP            | EliteBook 820 G4            | [34bd8e2402](https://linux-hardware.org/?probe=34bd8e2402) | May 12, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [e855bafa57](https://linux-hardware.org/?probe=e855bafa57) | May 11, 2023 |
| Notebook      | N14xWU                      | [0e4f386b46](https://linux-hardware.org/?probe=0e4f386b46) | May 11, 2023 |
| HP            | EliteBook 820 G4            | [a7327f2e2e](https://linux-hardware.org/?probe=a7327f2e2e) | May 11, 2023 |
| Acer          | TravelMate P653-M           | [a0f805c8ca](https://linux-hardware.org/?probe=a0f805c8ca) | May 10, 2023 |
| Dell          | XPS 9315                    | [291a190f04](https://linux-hardware.org/?probe=291a190f04) | May 10, 2023 |
| Dell          | XPS 15 9520                 | [86136dd98f](https://linux-hardware.org/?probe=86136dd98f) | May 09, 2023 |
| Toshiba       | Satellite L650              | [ba32d27df1](https://linux-hardware.org/?probe=ba32d27df1) | May 08, 2023 |
| Acer          | Aspire 5732Z                | [ec45ea6206](https://linux-hardware.org/?probe=ec45ea6206) | May 08, 2023 |
| PC Special... | NP5x_NP6x_NP7xPNP           | [72d9dac16b](https://linux-hardware.org/?probe=72d9dac16b) | May 07, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | [148433c97e](https://linux-hardware.org/?probe=148433c97e) | May 07, 2023 |
| Timi          | TM1701                      | [c41d566374](https://linux-hardware.org/?probe=c41d566374) | May 07, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | [0d6a9b046a](https://linux-hardware.org/?probe=0d6a9b046a) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | [0304fddec7](https://linux-hardware.org/?probe=0304fddec7) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | [2a30823af1](https://linux-hardware.org/?probe=2a30823af1) | May 07, 2023 |
| Dell          | Latitude E5530 non-vPro     | [3bea2bcd99](https://linux-hardware.org/?probe=3bea2bcd99) | May 05, 2023 |
| Unknown       | Cherry Trail CR             | [9569a530e8](https://linux-hardware.org/?probe=9569a530e8) | May 05, 2023 |
| Dell          | Precision 7720              | [b6c3392263](https://linux-hardware.org/?probe=b6c3392263) | May 05, 2023 |
| Acer          | TravelMate P214-53          | [8e78c8d139](https://linux-hardware.org/?probe=8e78c8d139) | May 05, 2023 |
| HP            | EliteBook 8470p             | [9684be9c3a](https://linux-hardware.org/?probe=9684be9c3a) | May 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [4aec6123b0](https://linux-hardware.org/?probe=4aec6123b0) | May 04, 2023 |
| Valve         | Jupiter                     | [0a6a9a6675](https://linux-hardware.org/?probe=0a6a9a6675) | May 03, 2023 |
| Dell          | Latitude 7420               | [7986f6779d](https://linux-hardware.org/?probe=7986f6779d) | May 03, 2023 |
| HP            | EliteBook Folio G1          | [a31ef5e00e](https://linux-hardware.org/?probe=a31ef5e00e) | May 02, 2023 |
| Toshiba       | Satellite C870-1FZ          | [dfbf38e06f](https://linux-hardware.org/?probe=dfbf38e06f) | May 01, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [6c1969f77e](https://linux-hardware.org/?probe=6c1969f77e) | May 01, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | [6c58138c35](https://linux-hardware.org/?probe=6c58138c35) | May 01, 2023 |
| VIOS          | LTH17                       | [4d1a86ee61](https://linux-hardware.org/?probe=4d1a86ee61) | Apr 30, 2023 |
| HP            | Compaq Mini CQ10-500        | [9a1134210f](https://linux-hardware.org/?probe=9a1134210f) | Apr 30, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | [edf1d60e46](https://linux-hardware.org/?probe=edf1d60e46) | Apr 29, 2023 |
| Insyde        | M890BAP                     | [151efb0278](https://linux-hardware.org/?probe=151efb0278) | Apr 29, 2023 |
| Insyde        | CherryTrail                 | [a9f658c8af](https://linux-hardware.org/?probe=a9f658c8af) | Apr 29, 2023 |
| Lenovo        | ThinkPad P50 20EQS5C701     | [e84690f2d5](https://linux-hardware.org/?probe=e84690f2d5) | Apr 29, 2023 |
| Dell          | Latitude 3301               | [3a0aad0e75](https://linux-hardware.org/?probe=3a0aad0e75) | Apr 29, 2023 |
| HP            | Pavilion dv7                | [e3f05fe37f](https://linux-hardware.org/?probe=e3f05fe37f) | Apr 28, 2023 |
| HP            | Pavilion dv7                | [da542ba626](https://linux-hardware.org/?probe=da542ba626) | Apr 28, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [b5a953a984](https://linux-hardware.org/?probe=b5a953a984) | Apr 28, 2023 |
| Dell          | Latitude 3301               | [855564b077](https://linux-hardware.org/?probe=855564b077) | Apr 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | [858404838d](https://linux-hardware.org/?probe=858404838d) | Apr 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | [0bf066e179](https://linux-hardware.org/?probe=0bf066e179) | Apr 27, 2023 |
| Medion        | E2215T MD60198              | [390ccbba6f](https://linux-hardware.org/?probe=390ccbba6f) | Apr 26, 2023 |
| Acer          | Swift SF114-34              | [693f0cea98](https://linux-hardware.org/?probe=693f0cea98) | Apr 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [5236dde38f](https://linux-hardware.org/?probe=5236dde38f) | Apr 25, 2023 |
| HUAWEI        | BOHB-WAX9                   | [40df32580a](https://linux-hardware.org/?probe=40df32580a) | Apr 25, 2023 |
| Notebook      | P95_96_97Ex,Rx              | [297da8c979](https://linux-hardware.org/?probe=297da8c979) | Apr 24, 2023 |
| Apple         | MacBookPro15,2              | [09eb88ba6c](https://linux-hardware.org/?probe=09eb88ba6c) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [6cacf7a9f9](https://linux-hardware.org/?probe=6cacf7a9f9) | Apr 24, 2023 |
| BTO           | 17X1183                     | [134a6ead50](https://linux-hardware.org/?probe=134a6ead50) | Apr 23, 2023 |
| BTO           | 17X1183                     | [181163b5e8](https://linux-hardware.org/?probe=181163b5e8) | Apr 23, 2023 |
| Dell          | Latitude 9520               | [0ab9a83db6](https://linux-hardware.org/?probe=0ab9a83db6) | Apr 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | [b906572f4b](https://linux-hardware.org/?probe=b906572f4b) | Apr 23, 2023 |
| Notebook      | NLxxPUx                     | [3648be5b0f](https://linux-hardware.org/?probe=3648be5b0f) | Apr 23, 2023 |
| Notebook      | W54_55_94_95_97AU,AUQ       | [f4e4c58948](https://linux-hardware.org/?probe=f4e4c58948) | Apr 23, 2023 |
| Apple         | MacBookPro12,1              | [65ba6571a2](https://linux-hardware.org/?probe=65ba6571a2) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [72088721ec](https://linux-hardware.org/?probe=72088721ec) | Apr 22, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [112a18b586](https://linux-hardware.org/?probe=112a18b586) | Apr 22, 2023 |
| Dell          | Latitude E4300              | [f58f44d242](https://linux-hardware.org/?probe=f58f44d242) | Apr 22, 2023 |
| Medion        | E4251                       | [76820d982c](https://linux-hardware.org/?probe=76820d982c) | Apr 22, 2023 |
| HP            | EliteBook 2570p             | [a26039eb50](https://linux-hardware.org/?probe=a26039eb50) | Apr 22, 2023 |
| HP            | EliteBook 2570p             | [7e7a982c3c](https://linux-hardware.org/?probe=7e7a982c3c) | Apr 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [1c76d0f5a4](https://linux-hardware.org/?probe=1c76d0f5a4) | Apr 22, 2023 |
| Acer          | TP-SW3-013-181M             | [d231dc8846](https://linux-hardware.org/?probe=d231dc8846) | Apr 22, 2023 |
| Notebook      | N13_N140ZU                  | [51ee77485d](https://linux-hardware.org/?probe=51ee77485d) | Apr 21, 2023 |
| ASUSTek       | ZenBook UX333FN_RX333FN     | [8027ff2b04](https://linux-hardware.org/?probe=8027ff2b04) | Apr 21, 2023 |
| Apple         | MacBookAir7,2               | [8c9f6ec7ef](https://linux-hardware.org/?probe=8c9f6ec7ef) | Apr 20, 2023 |
| Chuwi         | HeroBook Pro                | [e8332849a1](https://linux-hardware.org/?probe=e8332849a1) | Apr 20, 2023 |
| Dell          | Latitude 5400               | [f0e05c9726](https://linux-hardware.org/?probe=f0e05c9726) | Apr 20, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [9093d27c30](https://linux-hardware.org/?probe=9093d27c30) | Apr 19, 2023 |
| ASUSTek       | K501LX                      | [00676747c4](https://linux-hardware.org/?probe=00676747c4) | Apr 19, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [f691871296](https://linux-hardware.org/?probe=f691871296) | Apr 19, 2023 |
| Acer          | Swift SF314-57              | [5fc25cc033](https://linux-hardware.org/?probe=5fc25cc033) | Apr 19, 2023 |
| Dell          | XPS 15 7590                 | [abcb6ed7e8](https://linux-hardware.org/?probe=abcb6ed7e8) | Apr 19, 2023 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | [17b3242021](https://linux-hardware.org/?probe=17b3242021) | Apr 18, 2023 |
| Acer          | Iconia                      | [1ebc88d3ab](https://linux-hardware.org/?probe=1ebc88d3ab) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | [f045e3f800](https://linux-hardware.org/?probe=f045e3f800) | Apr 18, 2023 |
| Apple         | MacBookPro9,2               | [9f2a7943c7](https://linux-hardware.org/?probe=9f2a7943c7) | Apr 17, 2023 |
| Dell          | Latitude 5500               | [f4ac637463](https://linux-hardware.org/?probe=f4ac637463) | Apr 16, 2023 |
| HP            | EliteBook 840 G1            | [5994a04ee0](https://linux-hardware.org/?probe=5994a04ee0) | Apr 16, 2023 |
| HP            | ZBook 14u G5                | [fcf729207a](https://linux-hardware.org/?probe=fcf729207a) | Apr 15, 2023 |
| HP            | EliteBook 830 G6            | [75ce029800](https://linux-hardware.org/?probe=75ce029800) | Apr 13, 2023 |
| ASUSTek       | GL502VM                     | [4d31e0eb90](https://linux-hardware.org/?probe=4d31e0eb90) | Apr 13, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [6b481f17c2](https://linux-hardware.org/?probe=6b481f17c2) | Apr 13, 2023 |
| Wortmann      | TERRA_MOBILE_1160           | [d40eed27fd](https://linux-hardware.org/?probe=d40eed27fd) | Apr 13, 2023 |
| HP            | Compaq Presario C700        | [0519471935](https://linux-hardware.org/?probe=0519471935) | Apr 13, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [0a09da06be](https://linux-hardware.org/?probe=0a09da06be) | Apr 13, 2023 |
| HP            | ZBook 15 G3                 | [5411d789c3](https://linux-hardware.org/?probe=5411d789c3) | Apr 12, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [dc40d51336](https://linux-hardware.org/?probe=dc40d51336) | Apr 12, 2023 |
| Notebook      | NH55RGQ                     | [7fc1310fc2](https://linux-hardware.org/?probe=7fc1310fc2) | Apr 11, 2023 |
| Apple         | MacBookAir7,2               | [94efe20a0f](https://linux-hardware.org/?probe=94efe20a0f) | Apr 10, 2023 |
| Apple         | MacBookPro8,1               | [5a903505c7](https://linux-hardware.org/?probe=5a903505c7) | Apr 10, 2023 |
| HP            | EliteBook 8570p             | [854ec28c71](https://linux-hardware.org/?probe=854ec28c71) | Apr 09, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | [02bbb66fe9](https://linux-hardware.org/?probe=02bbb66fe9) | Apr 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [ea22560713](https://linux-hardware.org/?probe=ea22560713) | Apr 09, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [76af734c86](https://linux-hardware.org/?probe=76af734c86) | Apr 07, 2023 |
| Notebook      | N141CU                      | [8648ddb323](https://linux-hardware.org/?probe=8648ddb323) | Apr 07, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [8d68ef79c3](https://linux-hardware.org/?probe=8d68ef79c3) | Apr 06, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [c2195f003d](https://linux-hardware.org/?probe=c2195f003d) | Apr 06, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [405f73f1fd](https://linux-hardware.org/?probe=405f73f1fd) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [0af2f7cc7f](https://linux-hardware.org/?probe=0af2f7cc7f) | Apr 05, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [10213d8aa1](https://linux-hardware.org/?probe=10213d8aa1) | Apr 05, 2023 |
| Valve         | Jupiter                     | [e8a69f8de9](https://linux-hardware.org/?probe=e8a69f8de9) | Apr 05, 2023 |
| Dell          | XPS 9320                    | [c78c87474d](https://linux-hardware.org/?probe=c78c87474d) | Apr 05, 2023 |
| HP            | EliteBook 2530p             | [519d2a4d5a](https://linux-hardware.org/?probe=519d2a4d5a) | Apr 04, 2023 |
| HP            | ProBook 6570b               | [d42564b34f](https://linux-hardware.org/?probe=d42564b34f) | Apr 04, 2023 |
| HP            | EliteBook 850 G6            | [1af731cc92](https://linux-hardware.org/?probe=1af731cc92) | Apr 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [3125aa5d21](https://linux-hardware.org/?probe=3125aa5d21) | Apr 03, 2023 |
| Toxic         | GM5MPHY                     | [9ce64fb49a](https://linux-hardware.org/?probe=9ce64fb49a) | Apr 02, 2023 |
| ilife         | S806                        | [d089301e66](https://linux-hardware.org/?probe=d089301e66) | Apr 02, 2023 |
| Apple         | MacBookPro11,2              | [f78d5a9d04](https://linux-hardware.org/?probe=f78d5a9d04) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ac5393930b](https://linux-hardware.org/?probe=ac5393930b) | Apr 02, 2023 |
| ilife         | S806                        | [3a3ccd7c55](https://linux-hardware.org/?probe=3a3ccd7c55) | Apr 02, 2023 |
| HUAWEI        | MACHC-WAX9                  | [3494157f4b](https://linux-hardware.org/?probe=3494157f4b) | Apr 01, 2023 |
| Dell          | Latitude E7450              | [8bf693a890](https://linux-hardware.org/?probe=8bf693a890) | Apr 01, 2023 |
| Acer          | Aspire 7741                 | [34bd6f42b1](https://linux-hardware.org/?probe=34bd6f42b1) | Mar 30, 2023 |
| HUAWEI        | BOHB-WAX9                   | [6ade0ea04f](https://linux-hardware.org/?probe=6ade0ea04f) | Mar 30, 2023 |
| Apple         | MacBookPro11,3              | [0028f21c3e](https://linux-hardware.org/?probe=0028f21c3e) | Mar 30, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [de3828d539](https://linux-hardware.org/?probe=de3828d539) | Mar 29, 2023 |
| HP            | ZBook 15 G5                 | [059358e49b](https://linux-hardware.org/?probe=059358e49b) | Mar 29, 2023 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [61ede0b764](https://linux-hardware.org/?probe=61ede0b764) | Mar 29, 2023 |
| Acer          | Aspire E5-773G              | [3cb72ca21c](https://linux-hardware.org/?probe=3cb72ca21c) | Mar 29, 2023 |
| HP            | Pavilion g7                 | [5b1e547f92](https://linux-hardware.org/?probe=5b1e547f92) | Mar 29, 2023 |
| HP            | Pavilion g7                 | [ce74564fd9](https://linux-hardware.org/?probe=ce74564fd9) | Mar 28, 2023 |
| Apple         | MacBookPro11,2              | [422e4056ea](https://linux-hardware.org/?probe=422e4056ea) | Mar 28, 2023 |
| Valve         | Jupiter                     | [68175ccbea](https://linux-hardware.org/?probe=68175ccbea) | Mar 27, 2023 |
| Unknown       | Unknown                     | [1988691e71](https://linux-hardware.org/?probe=1988691e71) | Mar 27, 2023 |
| Unknown       | Unknown                     | [dd081eb573](https://linux-hardware.org/?probe=dd081eb573) | Mar 27, 2023 |
| ASUSTek       | N76VM                       | [0a05b4b5ce](https://linux-hardware.org/?probe=0a05b4b5ce) | Mar 26, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [79c876bced](https://linux-hardware.org/?probe=79c876bced) | Mar 25, 2023 |
| Haier         | S15                         | [497105206c](https://linux-hardware.org/?probe=497105206c) | Mar 25, 2023 |
| MSI           | Summit E16FlipEvo A11MT     | [62839dd4ac](https://linux-hardware.org/?probe=62839dd4ac) | Mar 24, 2023 |
| Acer          | Aspire 5733Z                | [8a7f87172d](https://linux-hardware.org/?probe=8a7f87172d) | Mar 24, 2023 |
| Framework     | Laptop                      | [4e1bd28ce3](https://linux-hardware.org/?probe=4e1bd28ce3) | Mar 24, 2023 |
| Dell          | XPS 15 9520                 | [06d6af1db0](https://linux-hardware.org/?probe=06d6af1db0) | Mar 23, 2023 |
| Dell          | XPS 13 9310                 | [386f37d114](https://linux-hardware.org/?probe=386f37d114) | Mar 22, 2023 |
| HP            | EliteBook 725 G2            | [5112f86dde](https://linux-hardware.org/?probe=5112f86dde) | Mar 21, 2023 |
| HP            | ZBook 15 G5                 | [83ddb49a8a](https://linux-hardware.org/?probe=83ddb49a8a) | Mar 21, 2023 |
| Hampoo        | Cherry Trail CR Hampoo_r... | [e7eb855568](https://linux-hardware.org/?probe=e7eb855568) | Mar 20, 2023 |
| Dell          | Latitude E6520              | [82f97b14f4](https://linux-hardware.org/?probe=82f97b14f4) | Mar 20, 2023 |
| Valve         | Jupiter                     | [b73f7b46c4](https://linux-hardware.org/?probe=b73f7b46c4) | Mar 20, 2023 |
| Dell          | Latitude E6520              | [7f92514d4e](https://linux-hardware.org/?probe=7f92514d4e) | Mar 20, 2023 |
| Dell          | XPS 9315                    | [3a6814a18f](https://linux-hardware.org/?probe=3a6814a18f) | Mar 20, 2023 |
| Dell          | XPS 9315                    | [a6054e6f0e](https://linux-hardware.org/?probe=a6054e6f0e) | Mar 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [92ae74e13d](https://linux-hardware.org/?probe=92ae74e13d) | Mar 19, 2023 |
| Dell          | Inspiron 15-3567            | [e90a87f6f2](https://linux-hardware.org/?probe=e90a87f6f2) | Mar 18, 2023 |
| Dell          | Latitude E7240              | [cbcae7df75](https://linux-hardware.org/?probe=cbcae7df75) | Mar 17, 2023 |
| HP            | Compaq 6730s                | [7e2310fcf0](https://linux-hardware.org/?probe=7e2310fcf0) | Mar 17, 2023 |
| Dell          | Latitude E7440              | [edf7e8521c](https://linux-hardware.org/?probe=edf7e8521c) | Mar 17, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [a78f938382](https://linux-hardware.org/?probe=a78f938382) | Mar 15, 2023 |
| HP            | EliteBook 2570p             | [1c6475f7da](https://linux-hardware.org/?probe=1c6475f7da) | Mar 15, 2023 |
| HUAWEI        | MACHC-WAX9                  | [fcb50f0e4f](https://linux-hardware.org/?probe=fcb50f0e4f) | Mar 14, 2023 |
| HUAWEI        | MACHC-WAX9                  | [fc7320db54](https://linux-hardware.org/?probe=fc7320db54) | Mar 14, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [b3e091147a](https://linux-hardware.org/?probe=b3e091147a) | Mar 14, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [e6d2f2a3b4](https://linux-hardware.org/?probe=e6d2f2a3b4) | Mar 14, 2023 |
| Acer          | Aspire A715-74G             | [57000f8a86](https://linux-hardware.org/?probe=57000f8a86) | Mar 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [a826b1cd32](https://linux-hardware.org/?probe=a826b1cd32) | Mar 13, 2023 |
| HP            | Pavilion dv7                | [66f70aa8f4](https://linux-hardware.org/?probe=66f70aa8f4) | Mar 12, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | [2b864d8f97](https://linux-hardware.org/?probe=2b864d8f97) | Mar 12, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [eb987f6db2](https://linux-hardware.org/?probe=eb987f6db2) | Mar 12, 2023 |
| Medion        | E4251                       | [8b057f3a15](https://linux-hardware.org/?probe=8b057f3a15) | Mar 12, 2023 |
| Acer          | Aspire 8930                 | [7434247d21](https://linux-hardware.org/?probe=7434247d21) | Mar 12, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [66094e937a](https://linux-hardware.org/?probe=66094e937a) | Mar 11, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | [c8d3cf3a4b](https://linux-hardware.org/?probe=c8d3cf3a4b) | Mar 11, 2023 |
| Lenovo        | ThinkPad T510 4384VJZ       | [d9c87b4795](https://linux-hardware.org/?probe=d9c87b4795) | Mar 11, 2023 |
| ASUSTek       | T100TAM                     | [1d647e564b](https://linux-hardware.org/?probe=1d647e564b) | Mar 10, 2023 |
| Acer          | Aspire A715-75G             | [3283454c2d](https://linux-hardware.org/?probe=3283454c2d) | Mar 10, 2023 |
| HP            | ProBook 430 G2              | [21595cd5ed](https://linux-hardware.org/?probe=21595cd5ed) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [276ce8bd7c](https://linux-hardware.org/?probe=276ce8bd7c) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3daf833362](https://linux-hardware.org/?probe=3daf833362) | Mar 09, 2023 |
| HP            | Laptop 15s-fq4xxx           | [e8e1e04dbd](https://linux-hardware.org/?probe=e8e1e04dbd) | Mar 08, 2023 |
| HP            | Laptop 15s-fq4xxx           | [2dd91e2cd2](https://linux-hardware.org/?probe=2dd91e2cd2) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [8a6c736217](https://linux-hardware.org/?probe=8a6c736217) | Mar 07, 2023 |
| HP            | ZBook 15 G3                 | [b00f87c99b](https://linux-hardware.org/?probe=b00f87c99b) | Mar 06, 2023 |
| Fujitsu       | LIFEBOOK U9312              | [19a72f502b](https://linux-hardware.org/?probe=19a72f502b) | Mar 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [98a2c9f264](https://linux-hardware.org/?probe=98a2c9f264) | Mar 06, 2023 |
| Google        | Rammus                      | [0d905c6981](https://linux-hardware.org/?probe=0d905c6981) | Mar 05, 2023 |
| HUAWEI        | MACHC-WAX9                  | [53b112adac](https://linux-hardware.org/?probe=53b112adac) | Mar 05, 2023 |
| ASUSTek       | T200TA                      | [4d2a27cffa](https://linux-hardware.org/?probe=4d2a27cffa) | Mar 05, 2023 |
| Dell          | Studio XPS 1647             | [484c629656](https://linux-hardware.org/?probe=484c629656) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [4a80c78c43](https://linux-hardware.org/?probe=4a80c78c43) | Mar 03, 2023 |
| Alienware     | m15                         | [180a0251f5](https://linux-hardware.org/?probe=180a0251f5) | Mar 02, 2023 |
| HP            | Notebook                    | [453811c44a](https://linux-hardware.org/?probe=453811c44a) | Mar 02, 2023 |
| Apple         | MacBookAir5,2               | [6b7925d129](https://linux-hardware.org/?probe=6b7925d129) | Mar 02, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [5cb58db69b](https://linux-hardware.org/?probe=5cb58db69b) | Mar 02, 2023 |
| ASUSTek       | N76VB                       | [0043164762](https://linux-hardware.org/?probe=0043164762) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | [3b70c27ca4](https://linux-hardware.org/?probe=3b70c27ca4) | Feb 28, 2023 |
| HP            | ProBook 6570b               | [3692011e3f](https://linux-hardware.org/?probe=3692011e3f) | Feb 28, 2023 |
| Sony          | VGN-FW11M                   | [06b355e1de](https://linux-hardware.org/?probe=06b355e1de) | Feb 28, 2023 |
| Unknown       | Unknown                     | [1dfaaf5a59](https://linux-hardware.org/?probe=1dfaaf5a59) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3aae5788cf](https://linux-hardware.org/?probe=3aae5788cf) | Feb 25, 2023 |
| HP            | Pavilion g7                 | [8f46d24897](https://linux-hardware.org/?probe=8f46d24897) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b5f840e593](https://linux-hardware.org/?probe=b5f840e593) | Feb 25, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [2978ec71b8](https://linux-hardware.org/?probe=2978ec71b8) | Feb 25, 2023 |
| HP            | Laptop 15s-fq1xxx           | [ca2ef50547](https://linux-hardware.org/?probe=ca2ef50547) | Feb 25, 2023 |
| HP            | Laptop 15s-fq1xxx           | [3899b2f13e](https://linux-hardware.org/?probe=3899b2f13e) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2bbce041f5](https://linux-hardware.org/?probe=2bbce041f5) | Feb 24, 2023 |
| Acer          | Aspire 5732Z                | [2cb9f58eae](https://linux-hardware.org/?probe=2cb9f58eae) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [a0bf98bcab](https://linux-hardware.org/?probe=a0bf98bcab) | Feb 23, 2023 |
| HP            | Laptop 14s-dq1xxx           | [1cca7fe830](https://linux-hardware.org/?probe=1cca7fe830) | Feb 22, 2023 |
| HP            | EliteBook 820 G4            | [de79cbb975](https://linux-hardware.org/?probe=de79cbb975) | Feb 22, 2023 |
| Valve         | Jupiter                     | [5e92cdeee7](https://linux-hardware.org/?probe=5e92cdeee7) | Feb 22, 2023 |
| HP            | Pavilion dv7                | [1ecf49cbaf](https://linux-hardware.org/?probe=1ecf49cbaf) | Feb 21, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [e1c694b371](https://linux-hardware.org/?probe=e1c694b371) | Feb 20, 2023 |
| Dell          | Latitude 7300               | [65690f7efc](https://linux-hardware.org/?probe=65690f7efc) | Feb 20, 2023 |
| Dell          | Latitude E6320              | [0b5bcfefc5](https://linux-hardware.org/?probe=0b5bcfefc5) | Feb 20, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [8ca2b786db](https://linux-hardware.org/?probe=8ca2b786db) | Feb 19, 2023 |
| Unknown       | Unknown                     | [f73ae7038f](https://linux-hardware.org/?probe=f73ae7038f) | Feb 19, 2023 |
| Dell          | Inspiron 15-3567            | [c2e0245ec5](https://linux-hardware.org/?probe=c2e0245ec5) | Feb 19, 2023 |
| Dell          | Latitude E6320              | [8110ff7717](https://linux-hardware.org/?probe=8110ff7717) | Feb 19, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | [2daf635e15](https://linux-hardware.org/?probe=2daf635e15) | Feb 18, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [c4a1fe4a4f](https://linux-hardware.org/?probe=c4a1fe4a4f) | Feb 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [3886d9287f](https://linux-hardware.org/?probe=3886d9287f) | Feb 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [1b401aa3cf](https://linux-hardware.org/?probe=1b401aa3cf) | Feb 17, 2023 |
| Unknown       | Unknown                     | [c59694e05c](https://linux-hardware.org/?probe=c59694e05c) | Feb 17, 2023 |
| Unknown       | Unknown                     | [c614caec4a](https://linux-hardware.org/?probe=c614caec4a) | Feb 17, 2023 |
| Alienware     | 15 R3                       | [c273319d9d](https://linux-hardware.org/?probe=c273319d9d) | Feb 17, 2023 |
| HP            | EliteBook 2570p             | [4fe16ec4fe](https://linux-hardware.org/?probe=4fe16ec4fe) | Feb 16, 2023 |
| HP            | Notebook                    | [3de841fd56](https://linux-hardware.org/?probe=3de841fd56) | Feb 16, 2023 |
| HP            | Pavilion dv7                | [130fe12846](https://linux-hardware.org/?probe=130fe12846) | Feb 16, 2023 |
| HP            | Pavilion dv7                | [7ca9bf386b](https://linux-hardware.org/?probe=7ca9bf386b) | Feb 16, 2023 |
| Google        | Helios                      | [4505c27d12](https://linux-hardware.org/?probe=4505c27d12) | Feb 16, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [ddc2c7ec7a](https://linux-hardware.org/?probe=ddc2c7ec7a) | Feb 16, 2023 |
| Dell          | Latitude 3320               | [fecee449d4](https://linux-hardware.org/?probe=fecee449d4) | Feb 15, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [3039ccd4b0](https://linux-hardware.org/?probe=3039ccd4b0) | Feb 14, 2023 |
| HP            | EliteBook 8570w             | [0d16c9013f](https://linux-hardware.org/?probe=0d16c9013f) | Feb 14, 2023 |
| Toshiba       | Satellite P870              | [dcfa5b1fc5](https://linux-hardware.org/?probe=dcfa5b1fc5) | Feb 13, 2023 |
| Toshiba       | Satellite P870              | [3a4a4dedc3](https://linux-hardware.org/?probe=3a4a4dedc3) | Feb 13, 2023 |
| Dell          | Latitude E5570              | [16e090c63c](https://linux-hardware.org/?probe=16e090c63c) | Feb 13, 2023 |
| Acer          | TravelMate P215-53          | [7c1423b767](https://linux-hardware.org/?probe=7c1423b767) | Feb 13, 2023 |
| Dell          | Precision 3571              | [8f7f52dcaa](https://linux-hardware.org/?probe=8f7f52dcaa) | Feb 13, 2023 |
| Acer          | Predator PH315-52           | [480da10129](https://linux-hardware.org/?probe=480da10129) | Feb 12, 2023 |
| Valve         | Jupiter                     | [5629f3ed8c](https://linux-hardware.org/?probe=5629f3ed8c) | Feb 12, 2023 |
| HP            | Compaq 6820s                | [6c67866714](https://linux-hardware.org/?probe=6c67866714) | Feb 12, 2023 |
| Acer          | Aspire V3-772               | [95875d4afc](https://linux-hardware.org/?probe=95875d4afc) | Feb 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e4340c10db](https://linux-hardware.org/?probe=e4340c10db) | Feb 10, 2023 |
| ASUSTek       | N751JX                      | [fd591a3e67](https://linux-hardware.org/?probe=fd591a3e67) | Feb 10, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [7ac6f508b2](https://linux-hardware.org/?probe=7ac6f508b2) | Feb 10, 2023 |
| Dell          | Precision 3571              | [85985612ac](https://linux-hardware.org/?probe=85985612ac) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [353bd3a5b2](https://linux-hardware.org/?probe=353bd3a5b2) | Feb 09, 2023 |
| Acer          | TravelMate P215-53          | [f3eb8a2592](https://linux-hardware.org/?probe=f3eb8a2592) | Feb 09, 2023 |
| HP            | EliteBook 850 G3            | [7091e6ba95](https://linux-hardware.org/?probe=7091e6ba95) | Feb 08, 2023 |
| Dell          | Latitude E7450              | [2513ec83c8](https://linux-hardware.org/?probe=2513ec83c8) | Feb 08, 2023 |
| HP            | ZBook 15 G2                 | [20d7058e4f](https://linux-hardware.org/?probe=20d7058e4f) | Feb 08, 2023 |
| Valve         | Jupiter                     | [b376c55e80](https://linux-hardware.org/?probe=b376c55e80) | Feb 07, 2023 |
| Dell          | Latitude E6320              | [6d1fe4f041](https://linux-hardware.org/?probe=6d1fe4f041) | Feb 06, 2023 |
| Lenovo        | ThinkPad T510 4349AF5       | [5d737e59ae](https://linux-hardware.org/?probe=5d737e59ae) | Feb 06, 2023 |
| Apple         | MacBookPro8,2               | [ffc97bf3de](https://linux-hardware.org/?probe=ffc97bf3de) | Feb 06, 2023 |
| Standard      | Unknown                     | [c983c471de](https://linux-hardware.org/?probe=c983c471de) | Feb 05, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [b6333de3ab](https://linux-hardware.org/?probe=b6333de3ab) | Feb 05, 2023 |
| Valve         | Jupiter                     | [8dee1d9415](https://linux-hardware.org/?probe=8dee1d9415) | Feb 03, 2023 |
| HP            | Compaq Presario CQ60        | [c6d48c9847](https://linux-hardware.org/?probe=c6d48c9847) | Feb 03, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [1e38d08821](https://linux-hardware.org/?probe=1e38d08821) | Feb 03, 2023 |
| Toshiba       | Satellite C660              | [2a25e1c4d6](https://linux-hardware.org/?probe=2a25e1c4d6) | Feb 02, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | [b829e9afbd](https://linux-hardware.org/?probe=b829e9afbd) | Feb 01, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | [f05a20fe00](https://linux-hardware.org/?probe=f05a20fe00) | Feb 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [db8bdbd72b](https://linux-hardware.org/?probe=db8bdbd72b) | Jan 31, 2023 |
| HP            | EliteBook 2560p             | [798466ab86](https://linux-hardware.org/?probe=798466ab86) | Jan 31, 2023 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | [2469884587](https://linux-hardware.org/?probe=2469884587) | Jan 30, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [debdb8208f](https://linux-hardware.org/?probe=debdb8208f) | Jan 29, 2023 |
| HP            | Pavilion Sleekbook 15       | [d17dc00a8a](https://linux-hardware.org/?probe=d17dc00a8a) | Jan 29, 2023 |
| Lenovo        | G550 2958                   | [8bee986aca](https://linux-hardware.org/?probe=8bee986aca) | Jan 28, 2023 |
| HP            | Compaq nc6320 (RH569ET#A... | [bf4432a140](https://linux-hardware.org/?probe=bf4432a140) | Jan 28, 2023 |
| Lenovo        | G550 2958                   | [a50b0e3645](https://linux-hardware.org/?probe=a50b0e3645) | Jan 28, 2023 |
| Acer          | Aspire E5-774               | [86e3285b31](https://linux-hardware.org/?probe=86e3285b31) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [d3adeb692c](https://linux-hardware.org/?probe=d3adeb692c) | Jan 27, 2023 |
| HP            | ZBook 15 G2                 | [b9793eca79](https://linux-hardware.org/?probe=b9793eca79) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [46b1227255](https://linux-hardware.org/?probe=46b1227255) | Jan 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [ee769c62bf](https://linux-hardware.org/?probe=ee769c62bf) | Jan 27, 2023 |
| Dell          | XPS 13 9305                 | [c0468fe8fd](https://linux-hardware.org/?probe=c0468fe8fd) | Jan 27, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0P    | [1a36af70e8](https://linux-hardware.org/?probe=1a36af70e8) | Jan 26, 2023 |
| Valve         | Jupiter                     | [cb8c4c9711](https://linux-hardware.org/?probe=cb8c4c9711) | Jan 26, 2023 |
| Valve         | Jupiter                     | [076783b777](https://linux-hardware.org/?probe=076783b777) | Jan 26, 2023 |
| Toshiba       | Satellite C870-12F          | [fc9a6d3a7e](https://linux-hardware.org/?probe=fc9a6d3a7e) | Jan 25, 2023 |
| HP            | Laptop 17-cp0xxx            | [70019cbdbf](https://linux-hardware.org/?probe=70019cbdbf) | Jan 25, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [dd2f21ab84](https://linux-hardware.org/?probe=dd2f21ab84) | Jan 25, 2023 |
| ASUSTek       | K72Jr                       | [9b7c80b059](https://linux-hardware.org/?probe=9b7c80b059) | Jan 25, 2023 |
| MSI           | CX700ND/CX70 0NF/CX70 0N... | [dad68fd07f](https://linux-hardware.org/?probe=dad68fd07f) | Jan 24, 2023 |
| MSI           | CX700ND/CX70 0NF/CX70 0N... | [b61b0f981e](https://linux-hardware.org/?probe=b61b0f981e) | Jan 24, 2023 |
| HP            | ZBook 15 G3                 | [0bde1ca99a](https://linux-hardware.org/?probe=0bde1ca99a) | Jan 24, 2023 |
| MSI           | GE70 2QD                    | [3194fb8316](https://linux-hardware.org/?probe=3194fb8316) | Jan 24, 2023 |
| MSI           | GE70 2QD                    | [8e124bc501](https://linux-hardware.org/?probe=8e124bc501) | Jan 24, 2023 |
| Acer          | Aspire A715-51G             | [75362fb07d](https://linux-hardware.org/?probe=75362fb07d) | Jan 24, 2023 |
| Valve         | Jupiter                     | [8c427938e2](https://linux-hardware.org/?probe=8c427938e2) | Jan 24, 2023 |
| HP            | EliteBook 735 G6            | [bb321263f8](https://linux-hardware.org/?probe=bb321263f8) | Jan 24, 2023 |
| Valve         | Jupiter                     | [5ca72b0d88](https://linux-hardware.org/?probe=5ca72b0d88) | Jan 24, 2023 |
| Acer          | Aspire SW5-012              | [247455614c](https://linux-hardware.org/?probe=247455614c) | Jan 23, 2023 |
| HP            | ZBook 15 G2                 | [5e4253b22d](https://linux-hardware.org/?probe=5e4253b22d) | Jan 23, 2023 |
| realme        | CloudProXXXX                | [8ba70a4617](https://linux-hardware.org/?probe=8ba70a4617) | Jan 23, 2023 |
| Acer          | Aspire 5680                 | [b4b7ebe3f9](https://linux-hardware.org/?probe=b4b7ebe3f9) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | [6e7a21c6d5](https://linux-hardware.org/?probe=6e7a21c6d5) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | [7d6077c27c](https://linux-hardware.org/?probe=7d6077c27c) | Jan 23, 2023 |
| ASUSTek       | K72Jr                       | [54313c1c76](https://linux-hardware.org/?probe=54313c1c76) | Jan 23, 2023 |
| HP            | EliteBook 840 G4            | [459ab8ae3d](https://linux-hardware.org/?probe=459ab8ae3d) | Jan 23, 2023 |
| Medion        | E4251                       | [7c90da8c5f](https://linux-hardware.org/?probe=7c90da8c5f) | Jan 23, 2023 |
| Acer          | Aspire 5680                 | [b2792832c2](https://linux-hardware.org/?probe=b2792832c2) | Jan 22, 2023 |
| Dell          | Latitude 5520               | [a3541758f7](https://linux-hardware.org/?probe=a3541758f7) | Jan 22, 2023 |
| ASUSTek       | GL553VD                     | [eeea0542b8](https://linux-hardware.org/?probe=eeea0542b8) | Jan 21, 2023 |
| Dell          | XPS 13 9310                 | [5d606f2c60](https://linux-hardware.org/?probe=5d606f2c60) | Jan 21, 2023 |
| Lenovo        | ThinkPad T490 20N3S0E000    | [d324a863a5](https://linux-hardware.org/?probe=d324a863a5) | Jan 20, 2023 |
| HP            | ProBook 650 G1              | [9620f447dd](https://linux-hardware.org/?probe=9620f447dd) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | [2135c30983](https://linux-hardware.org/?probe=2135c30983) | Jan 19, 2023 |
| HP            | Notebook                    | [63f0c0b90c](https://linux-hardware.org/?probe=63f0c0b90c) | Jan 19, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [da0d1f442a](https://linux-hardware.org/?probe=da0d1f442a) | Jan 19, 2023 |
| HP            | ProBook 430 G1              | [3591fb1d6c](https://linux-hardware.org/?probe=3591fb1d6c) | Jan 19, 2023 |
| Acer          | Aspire A715-75G             | [68d2fcbdcf](https://linux-hardware.org/?probe=68d2fcbdcf) | Jan 18, 2023 |
| Dell          | Latitude E6540              | [440b0eec1c](https://linux-hardware.org/?probe=440b0eec1c) | Jan 18, 2023 |
| Dell          | Precision M6800             | [62d01a5b26](https://linux-hardware.org/?probe=62d01a5b26) | Jan 18, 2023 |
| Dell          | Precision M6800             | [09e31ee1c8](https://linux-hardware.org/?probe=09e31ee1c8) | Jan 18, 2023 |
| Dell          | Latitude 5530               | [f9325236bb](https://linux-hardware.org/?probe=f9325236bb) | Jan 17, 2023 |
| Dell          | Latitude 5530               | [fafa35ef88](https://linux-hardware.org/?probe=fafa35ef88) | Jan 17, 2023 |
| HP            | ProBook 4540s               | [3f9e3a1cbb](https://linux-hardware.org/?probe=3f9e3a1cbb) | Jan 17, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [856324369f](https://linux-hardware.org/?probe=856324369f) | Jan 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d6b6c22af1](https://linux-hardware.org/?probe=d6b6c22af1) | Jan 17, 2023 |
| HP            | ProBook 4540s               | [7b9cd1b51c](https://linux-hardware.org/?probe=7b9cd1b51c) | Jan 16, 2023 |
| Dell          | XPS 15 9550                 | [4da81f73f5](https://linux-hardware.org/?probe=4da81f73f5) | Jan 16, 2023 |
| Google        | Banon                       | [6bb3ed04f9](https://linux-hardware.org/?probe=6bb3ed04f9) | Jan 16, 2023 |
| Lenovo        | ThinkPad T490s 20NX0076M... | [4c896e2c0e](https://linux-hardware.org/?probe=4c896e2c0e) | Jan 16, 2023 |
| Acer          | Aspire 5680                 | [dc5f6d7ac6](https://linux-hardware.org/?probe=dc5f6d7ac6) | Jan 16, 2023 |
| HP            | Pavilion 17                 | [895f75daf7](https://linux-hardware.org/?probe=895f75daf7) | Jan 16, 2023 |
| Dell          | Latitude E5430 non-vPro     | [57cd4eaca3](https://linux-hardware.org/?probe=57cd4eaca3) | Jan 15, 2023 |
| Acer          | Aspire 5736Z                | [bdfc087b4d](https://linux-hardware.org/?probe=bdfc087b4d) | Jan 15, 2023 |
| Acer          | Nitro AN515-43              | [4621c0d31b](https://linux-hardware.org/?probe=4621c0d31b) | Jan 15, 2023 |
| Apple         | MacBookPro5,5               | [2f2fec82c8](https://linux-hardware.org/?probe=2f2fec82c8) | Jan 15, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | [dd0a234ebb](https://linux-hardware.org/?probe=dd0a234ebb) | Jan 14, 2023 |
| Dell          | Latitude E5410              | [909ca0fd93](https://linux-hardware.org/?probe=909ca0fd93) | Jan 14, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [116b26047d](https://linux-hardware.org/?probe=116b26047d) | Jan 14, 2023 |
| Apple         | MacBookAir5,2               | [c4cfa1aa47](https://linux-hardware.org/?probe=c4cfa1aa47) | Jan 13, 2023 |
| HP            | ZBook Studio G4             | [67168cc8a9](https://linux-hardware.org/?probe=67168cc8a9) | Jan 13, 2023 |
| Lenovo        | ThinkPad X270 20K5S1A524    | [e4eaef80f8](https://linux-hardware.org/?probe=e4eaef80f8) | Jan 13, 2023 |
| realme        | CloudProXXXX                | [25d1a9b890](https://linux-hardware.org/?probe=25d1a9b890) | Jan 13, 2023 |
| Dell          | Latitude 3350               | [065c4a4a95](https://linux-hardware.org/?probe=065c4a4a95) | Jan 12, 2023 |
| Lenovo        | G770 1037                   | [da21020be1](https://linux-hardware.org/?probe=da21020be1) | Jan 12, 2023 |
| Notebook      | NS50MU                      | [7d94a36b67](https://linux-hardware.org/?probe=7d94a36b67) | Jan 12, 2023 |
| Standard      | Unknown                     | [b6f4b12847](https://linux-hardware.org/?probe=b6f4b12847) | Jan 12, 2023 |
| HP            | Pavilion dv9500             | [0f8c99e8d7](https://linux-hardware.org/?probe=0f8c99e8d7) | Jan 11, 2023 |
| Sony          | VPCEB3L9E                   | [5a7ea474fd](https://linux-hardware.org/?probe=5a7ea474fd) | Jan 11, 2023 |
| Dell          | XPS 15 9500                 | [69b3403f94](https://linux-hardware.org/?probe=69b3403f94) | Jan 10, 2023 |
| Acer          | Aspire 5735                 | [27b63fd8b1](https://linux-hardware.org/?probe=27b63fd8b1) | Jan 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [5663965a51](https://linux-hardware.org/?probe=5663965a51) | Jan 09, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [774902b83f](https://linux-hardware.org/?probe=774902b83f) | Jan 09, 2023 |
| Acer          | Aspire One 721              | [4b9311cfed](https://linux-hardware.org/?probe=4b9311cfed) | Jan 08, 2023 |
| HP            | ZBook 15 G3                 | [648dcae4c6](https://linux-hardware.org/?probe=648dcae4c6) | Jan 08, 2023 |
| Acer          | TravelMate P614-51-G2       | [0d0c035342](https://linux-hardware.org/?probe=0d0c035342) | Jan 08, 2023 |
| Lenovo        | ThinkPad Edge E145 20BC0... | [8ca4d7b38b](https://linux-hardware.org/?probe=8ca4d7b38b) | Jan 08, 2023 |
| Apple         | MacBookAir7,2               | [a4e777ea7d](https://linux-hardware.org/?probe=a4e777ea7d) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [782467ee8c](https://linux-hardware.org/?probe=782467ee8c) | Jan 07, 2023 |
| Medion        | E4251 MD61435               | [7f3f24b812](https://linux-hardware.org/?probe=7f3f24b812) | Jan 05, 2023 |
| HP            | Pavilion 17                 | [fe325358d6](https://linux-hardware.org/?probe=fe325358d6) | Jan 04, 2023 |
| Dell          | Latitude E6330              | [0341a89f2f](https://linux-hardware.org/?probe=0341a89f2f) | Jan 04, 2023 |
| Sony          | VPCEB3L1E                   | [e8ac8a5d95](https://linux-hardware.org/?probe=e8ac8a5d95) | Jan 04, 2023 |
| Apple         | MacBookAir7,2               | [2f148d690a](https://linux-hardware.org/?probe=2f148d690a) | Jan 03, 2023 |
| Acer          | Aspire E5-774               | [96c68886cf](https://linux-hardware.org/?probe=96c68886cf) | Jan 03, 2023 |
| HP            | 240 G8 Notebook PC          | [a316608c78](https://linux-hardware.org/?probe=a316608c78) | Jan 03, 2023 |
| Acer          | Aspire V3-574G              | [a889bba557](https://linux-hardware.org/?probe=a889bba557) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [08fb8de608](https://linux-hardware.org/?probe=08fb8de608) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [bca75efbe5](https://linux-hardware.org/?probe=bca75efbe5) | Jan 02, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1E70... | [e8b6dd6f1f](https://linux-hardware.org/?probe=e8b6dd6f1f) | Jan 01, 2023 |
| Notebook      | PB50_70RF,RD,RC             | [d1f655b9b1](https://linux-hardware.org/?probe=d1f655b9b1) | Dec 31, 2022 |
| HP            | Pavilion 17                 | [c87d61d0cd](https://linux-hardware.org/?probe=c87d61d0cd) | Dec 31, 2022 |
| HP            | Pavilion 17                 | [bbf52af119](https://linux-hardware.org/?probe=bbf52af119) | Dec 31, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [fc108fb0d8](https://linux-hardware.org/?probe=fc108fb0d8) | Dec 31, 2022 |
| HP            | EliteBook 820 G4            | [9e794046d8](https://linux-hardware.org/?probe=9e794046d8) | Dec 30, 2022 |
| Acer          | Aspire 5680                 | [c14cfe5386](https://linux-hardware.org/?probe=c14cfe5386) | Dec 29, 2022 |
| Acer          | Aspire V3-772               | [9f431b484a](https://linux-hardware.org/?probe=9f431b484a) | Dec 29, 2022 |
| Alienware     | x17 R2                      | [5a7ea2683a](https://linux-hardware.org/?probe=5a7ea2683a) | Dec 28, 2022 |
| Dell          | Latitude 2120               | [b52922b482](https://linux-hardware.org/?probe=b52922b482) | Dec 27, 2022 |
| Valve         | Jupiter                     | [488d26f3e8](https://linux-hardware.org/?probe=488d26f3e8) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0763603d12](https://linux-hardware.org/?probe=0763603d12) | Dec 27, 2022 |
| LG Electro... | 17Z90Q-G.AA79G              | [59d7266746](https://linux-hardware.org/?probe=59d7266746) | Dec 26, 2022 |
| Apple         | MacBookPro8,2               | [3d8320e362](https://linux-hardware.org/?probe=3d8320e362) | Dec 25, 2022 |
| Medion        | E4251 MD61435               | [0ef8f76193](https://linux-hardware.org/?probe=0ef8f76193) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [0c1d9b9b28](https://linux-hardware.org/?probe=0c1d9b9b28) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [000660b461](https://linux-hardware.org/?probe=000660b461) | Dec 23, 2022 |
| Toshiba       | Satellite C70D-B            | [82cc0b362d](https://linux-hardware.org/?probe=82cc0b362d) | Dec 23, 2022 |
| Lenovo        | IdeaPad 3 14IAU7 82RJ       | [b5c5aba33a](https://linux-hardware.org/?probe=b5c5aba33a) | Dec 22, 2022 |
| Lenovo        | ThinkPad T470s 20HF003QU... | [5145350f9a](https://linux-hardware.org/?probe=5145350f9a) | Dec 21, 2022 |
| Acer          | Aspire 5680                 | [9b188c358e](https://linux-hardware.org/?probe=9b188c358e) | Dec 21, 2022 |
| Valve         | Jupiter                     | [90331ea7da](https://linux-hardware.org/?probe=90331ea7da) | Dec 21, 2022 |
| Dell          | Latitude 5521               | [6fcbfd9271](https://linux-hardware.org/?probe=6fcbfd9271) | Dec 21, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [638667a90f](https://linux-hardware.org/?probe=638667a90f) | Dec 20, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [2aeb8fd0cd](https://linux-hardware.org/?probe=2aeb8fd0cd) | Dec 19, 2022 |
| ASUSTek       | N750JK                      | [8d876c21b0](https://linux-hardware.org/?probe=8d876c21b0) | Dec 18, 2022 |
| ASUSTek       | N750JK                      | [71575f3d8c](https://linux-hardware.org/?probe=71575f3d8c) | Dec 18, 2022 |
| Acer          | Aspire 5680                 | [64f5eb2f4b](https://linux-hardware.org/?probe=64f5eb2f4b) | Dec 17, 2022 |
| ASUSTek       | K50IE                       | [5681babfa5](https://linux-hardware.org/?probe=5681babfa5) | Dec 17, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [30f6db8749](https://linux-hardware.org/?probe=30f6db8749) | Dec 17, 2022 |
| Acer          | Aspire E5-575               | [3fd939cef5](https://linux-hardware.org/?probe=3fd939cef5) | Dec 17, 2022 |
| Toshiba       | Satellite C70D-B            | [182e467ce6](https://linux-hardware.org/?probe=182e467ce6) | Dec 17, 2022 |
| Lenovo        | G50-70 20351                | [4d39c63e0a](https://linux-hardware.org/?probe=4d39c63e0a) | Dec 17, 2022 |
| Dell          | XPS 15 7590                 | [e070540587](https://linux-hardware.org/?probe=e070540587) | Dec 16, 2022 |
| Dell          | Latitude 3120               | [e886df2722](https://linux-hardware.org/?probe=e886df2722) | Dec 16, 2022 |
| Acer          | Nitro AN517-54              | [cb963df304](https://linux-hardware.org/?probe=cb963df304) | Dec 16, 2022 |
| MSI           | GP75 Leopard 10SEK          | [9eda9896f3](https://linux-hardware.org/?probe=9eda9896f3) | Dec 15, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [de26ffa293](https://linux-hardware.org/?probe=de26ffa293) | Dec 14, 2022 |
| Dell          | Inspiron 15-3567            | [e94792b948](https://linux-hardware.org/?probe=e94792b948) | Dec 13, 2022 |
| Acer          | Aspire 5742G                | [ee22896cd2](https://linux-hardware.org/?probe=ee22896cd2) | Dec 12, 2022 |
| MSI           | Summit E16Flip A12UCT       | [1db3976bb5](https://linux-hardware.org/?probe=1db3976bb5) | Dec 12, 2022 |
| Toshiba       | Satellite C70D-B            | [56adac1fcb](https://linux-hardware.org/?probe=56adac1fcb) | Dec 12, 2022 |
| Medion        | E4251                       | [f7303bf4c9](https://linux-hardware.org/?probe=f7303bf4c9) | Dec 11, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | [cd7399049b](https://linux-hardware.org/?probe=cd7399049b) | Dec 11, 2022 |
| Medion        | E4251                       | [a16b01515b](https://linux-hardware.org/?probe=a16b01515b) | Dec 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [173f4b722f](https://linux-hardware.org/?probe=173f4b722f) | Dec 10, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [25d5b5623b](https://linux-hardware.org/?probe=25d5b5623b) | Dec 10, 2022 |
| Acer          | Aspire 5742G                | [869e2a9671](https://linux-hardware.org/?probe=869e2a9671) | Dec 09, 2022 |
| HP            | Compaq Presario CQ71        | [503b61f120](https://linux-hardware.org/?probe=503b61f120) | Dec 09, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [95d47d14cb](https://linux-hardware.org/?probe=95d47d14cb) | Dec 09, 2022 |
| MSI           | Modern 15 A11MU             | [e5ba0c8749](https://linux-hardware.org/?probe=e5ba0c8749) | Dec 09, 2022 |
| Apple         | MacBookPro9,2               | [27dc9420ed](https://linux-hardware.org/?probe=27dc9420ed) | Dec 07, 2022 |
| Apple         | MacBookPro9,2               | [9b7c1953a6](https://linux-hardware.org/?probe=9b7c1953a6) | Dec 07, 2022 |
| Lenovo        | ThinkPad T510 4349AF5       | [a7d8d66fb7](https://linux-hardware.org/?probe=a7d8d66fb7) | Dec 07, 2022 |
| Dell          | XPS 9320                    | [34c3b0b6a0](https://linux-hardware.org/?probe=34c3b0b6a0) | Dec 06, 2022 |
| Medion        | E4251                       | [a515c5c071](https://linux-hardware.org/?probe=a515c5c071) | Dec 05, 2022 |
| Acer          | Aspire 5742G                | [da82fb083d](https://linux-hardware.org/?probe=da82fb083d) | Dec 05, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [1798adf382](https://linux-hardware.org/?probe=1798adf382) | Dec 05, 2022 |
| ASUSTek       | X756UQK                     | [b473216b84](https://linux-hardware.org/?probe=b473216b84) | Dec 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [05f6a48b4a](https://linux-hardware.org/?probe=05f6a48b4a) | Dec 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c22a748043](https://linux-hardware.org/?probe=c22a748043) | Dec 05, 2022 |
| Acer          | Aspire V3-772               | [942312fe9e](https://linux-hardware.org/?probe=942312fe9e) | Dec 05, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [344b0c3082](https://linux-hardware.org/?probe=344b0c3082) | Dec 05, 2022 |
| Medion        | E4251 MD61435               | [481a9c958a](https://linux-hardware.org/?probe=481a9c958a) | Dec 04, 2022 |
| Acer          | Aspire ES1-732              | [7000f5ee26](https://linux-hardware.org/?probe=7000f5ee26) | Dec 04, 2022 |
| Valve         | Jupiter                     | [d8890572a5](https://linux-hardware.org/?probe=d8890572a5) | Dec 03, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [2cf560b162](https://linux-hardware.org/?probe=2cf560b162) | Dec 03, 2022 |
| Medion        | E4251 MD61435               | [c3f4fd226e](https://linux-hardware.org/?probe=c3f4fd226e) | Dec 03, 2022 |
| Medion        | E4251                       | [3167cbece1](https://linux-hardware.org/?probe=3167cbece1) | Dec 03, 2022 |
| HP            | EliteBook 820 G4            | [b0437249b0](https://linux-hardware.org/?probe=b0437249b0) | Dec 03, 2022 |
| Packard Be... | EasyNote TE11HC             | [5864876eff](https://linux-hardware.org/?probe=5864876eff) | Dec 02, 2022 |
| Acer          | Iconia W4-820               | [cf25eeba85](https://linux-hardware.org/?probe=cf25eeba85) | Dec 01, 2022 |
| MSI           | GL62M 7RE                   | [5fcb394edb](https://linux-hardware.org/?probe=5fcb394edb) | Dec 01, 2022 |
| Lenovo        | ThinkPad L560 20F2S2UR02    | [29c5e0f7b1](https://linux-hardware.org/?probe=29c5e0f7b1) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | [cdd03a3498](https://linux-hardware.org/?probe=cdd03a3498) | Dec 01, 2022 |
| Lenovo        | 3000 V100 076346G           | [bb04272723](https://linux-hardware.org/?probe=bb04272723) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | [2731961e4c](https://linux-hardware.org/?probe=2731961e4c) | Nov 30, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [dae405ee81](https://linux-hardware.org/?probe=dae405ee81) | Nov 29, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [9216162e85](https://linux-hardware.org/?probe=9216162e85) | Nov 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [39e771bd92](https://linux-hardware.org/?probe=39e771bd92) | Nov 28, 2022 |
| Lenovo        | ThinkPad T420 4236WR1       | [43fa54b5bc](https://linux-hardware.org/?probe=43fa54b5bc) | Nov 28, 2022 |
| Dell          | Latitude E6320              | [bcbdb4bf67](https://linux-hardware.org/?probe=bcbdb4bf67) | Nov 28, 2022 |
| Dell          | Latitude E6320              | [f77e444066](https://linux-hardware.org/?probe=f77e444066) | Nov 28, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [4c6d3faf86](https://linux-hardware.org/?probe=4c6d3faf86) | Nov 28, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [cd98ebccb9](https://linux-hardware.org/?probe=cd98ebccb9) | Nov 28, 2022 |
| Valve         | Jupiter                     | [81b0ea6c7a](https://linux-hardware.org/?probe=81b0ea6c7a) | Nov 27, 2022 |
| HP            | ProBook 5330m               | [3763f505a0](https://linux-hardware.org/?probe=3763f505a0) | Nov 27, 2022 |
| Valve         | Jupiter                     | [bee2852cb0](https://linux-hardware.org/?probe=bee2852cb0) | Nov 27, 2022 |
| HP            | EliteBook 830 G5            | [bda395e731](https://linux-hardware.org/?probe=bda395e731) | Nov 26, 2022 |
| HP            | EliteBook 830 G5            | [0138561b29](https://linux-hardware.org/?probe=0138561b29) | Nov 26, 2022 |
| ASUSTek       | A6R                         | [68f38deab1](https://linux-hardware.org/?probe=68f38deab1) | Nov 26, 2022 |
| HP            | ProBook 450 G5              | [9a8373739a](https://linux-hardware.org/?probe=9a8373739a) | Nov 26, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [8de1db7f12](https://linux-hardware.org/?probe=8de1db7f12) | Nov 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [fa4e2d1d61](https://linux-hardware.org/?probe=fa4e2d1d61) | Nov 23, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [eaab6a8319](https://linux-hardware.org/?probe=eaab6a8319) | Nov 23, 2022 |
| Valve         | Jupiter                     | [6049221fab](https://linux-hardware.org/?probe=6049221fab) | Nov 23, 2022 |
| ASUSTek       | X551MA                      | [4adc436e33](https://linux-hardware.org/?probe=4adc436e33) | Nov 23, 2022 |
| ASUSTek       | X551MA                      | [84a0005ad3](https://linux-hardware.org/?probe=84a0005ad3) | Nov 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [c799c028af](https://linux-hardware.org/?probe=c799c028af) | Nov 23, 2022 |
| Dell          | Latitude 5401               | [f964652e0c](https://linux-hardware.org/?probe=f964652e0c) | Nov 22, 2022 |
| Dell          | Latitude E6530              | [e40986d2fb](https://linux-hardware.org/?probe=e40986d2fb) | Nov 22, 2022 |
| Dell          | Latitude E6530              | [14debbe3e5](https://linux-hardware.org/?probe=14debbe3e5) | Nov 22, 2022 |
| Acer          | Aspire A715-74G             | [7e8b56ff73](https://linux-hardware.org/?probe=7e8b56ff73) | Nov 21, 2022 |
| ASUSTek       | E200HA                      | [635e9fe863](https://linux-hardware.org/?probe=635e9fe863) | Nov 21, 2022 |
| Dell          | XPS 15 9510                 | [09e98d8c02](https://linux-hardware.org/?probe=09e98d8c02) | Nov 21, 2022 |
| Apple         | MacBookPro11,5              | [e80e97466d](https://linux-hardware.org/?probe=e80e97466d) | Nov 21, 2022 |
| Apple         | MacBookPro11,5              | [12799c9216](https://linux-hardware.org/?probe=12799c9216) | Nov 21, 2022 |
| Valve         | Jupiter                     | [1e7b9730a4](https://linux-hardware.org/?probe=1e7b9730a4) | Nov 21, 2022 |
| HP            | Unknown                     | [4530507592](https://linux-hardware.org/?probe=4530507592) | Nov 20, 2022 |
| HP            | Compaq Presario CQ71        | [52c86bac3f](https://linux-hardware.org/?probe=52c86bac3f) | Nov 20, 2022 |
| Apple         | MacBookPro11,2              | [03447c1967](https://linux-hardware.org/?probe=03447c1967) | Nov 20, 2022 |
| Acer          | Aspire 5742G                | [9c9af5a79e](https://linux-hardware.org/?probe=9c9af5a79e) | Nov 20, 2022 |
| Apple         | MacBookPro11,5              | [3b5c35b319](https://linux-hardware.org/?probe=3b5c35b319) | Nov 19, 2022 |
| HP            | Notebook                    | [ded915d6cd](https://linux-hardware.org/?probe=ded915d6cd) | Nov 18, 2022 |
| Apple         | MacBookAir7,2               | [f0fa194e20](https://linux-hardware.org/?probe=f0fa194e20) | Nov 18, 2022 |
| Lenovo        | ThinkPad L560 20F2S2UR02    | [5170b27e5c](https://linux-hardware.org/?probe=5170b27e5c) | Nov 17, 2022 |
| Acer          | Aspire 7741                 | [4197d5fccf](https://linux-hardware.org/?probe=4197d5fccf) | Nov 17, 2022 |
| Apple         | MacBookPro11,5              | [62586ed7f9](https://linux-hardware.org/?probe=62586ed7f9) | Nov 16, 2022 |
| HP            | EliteBook 8570w             | [d5a16ba775](https://linux-hardware.org/?probe=d5a16ba775) | Nov 16, 2022 |
| HP            | Pavilion dv9500             | [65a473401c](https://linux-hardware.org/?probe=65a473401c) | Nov 16, 2022 |
| Acer          | Aspire 5742G                | [4a80ba0608](https://linux-hardware.org/?probe=4a80ba0608) | Nov 15, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [d2cf28fbb9](https://linux-hardware.org/?probe=d2cf28fbb9) | Nov 15, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [e9182b2177](https://linux-hardware.org/?probe=e9182b2177) | Nov 15, 2022 |
| Dell          | Latitude E6510              | [21a6415538](https://linux-hardware.org/?probe=21a6415538) | Nov 15, 2022 |
| Dell          | Latitude E6510              | [3ce2f9981f](https://linux-hardware.org/?probe=3ce2f9981f) | Nov 15, 2022 |
| Dell          | Latitude E7450              | [3020a4edfc](https://linux-hardware.org/?probe=3020a4edfc) | Nov 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [1798f04a0b](https://linux-hardware.org/?probe=1798f04a0b) | Nov 14, 2022 |
| SLIMBOOK      | PROX14                      | [a109c5bf52](https://linux-hardware.org/?probe=a109c5bf52) | Nov 14, 2022 |
| Valve         | Jupiter                     | [92eb4009f3](https://linux-hardware.org/?probe=92eb4009f3) | Nov 14, 2022 |
| Dell          | XPS 15 9510                 | [85c469c069](https://linux-hardware.org/?probe=85c469c069) | Nov 13, 2022 |
| Dell          | XPS 15 9510                 | [dc86aa7d1e](https://linux-hardware.org/?probe=dc86aa7d1e) | Nov 13, 2022 |
| Dell          | Latitude 3380               | [f770a70f68](https://linux-hardware.org/?probe=f770a70f68) | Nov 12, 2022 |
| HP            | Compaq 6820s                | [c852376664](https://linux-hardware.org/?probe=c852376664) | Nov 12, 2022 |
| HP            | Compaq 6820s                | [dee9dbd56f](https://linux-hardware.org/?probe=dee9dbd56f) | Nov 12, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [70d68c6ca1](https://linux-hardware.org/?probe=70d68c6ca1) | Nov 10, 2022 |
| ASUSTek       | N752VX                      | [a5b6d827b2](https://linux-hardware.org/?probe=a5b6d827b2) | Nov 10, 2022 |
| Panasonic     | CF-R9KWCTDR                 | [2a414f5dc5](https://linux-hardware.org/?probe=2a414f5dc5) | Nov 10, 2022 |
| HP            | ProBook 430 G4              | [ef9d0cf774](https://linux-hardware.org/?probe=ef9d0cf774) | Nov 09, 2022 |
| Lenovo        | ThinkPad X200 7458FDG       | [e7de2507a0](https://linux-hardware.org/?probe=e7de2507a0) | Nov 09, 2022 |
| Acer          | Aspire 5750G                | [8383f208a6](https://linux-hardware.org/?probe=8383f208a6) | Nov 09, 2022 |
| MSI           | Modern 15 A11MU             | [b10bd50d9c](https://linux-hardware.org/?probe=b10bd50d9c) | Nov 09, 2022 |
| MSI           | MS-1688                     | [d8c76d2264](https://linux-hardware.org/?probe=d8c76d2264) | Nov 09, 2022 |
| Dell          | Precision 5550              | [16b375ce77](https://linux-hardware.org/?probe=16b375ce77) | Nov 08, 2022 |
| Dell          | Precision 5550              | [1499c28fe9](https://linux-hardware.org/?probe=1499c28fe9) | Nov 08, 2022 |
| Acer          | SW5-017                     | [d4ff3ee29e](https://linux-hardware.org/?probe=d4ff3ee29e) | Nov 08, 2022 |
| ASUSTek       | FX503VD                     | [0373b83f63](https://linux-hardware.org/?probe=0373b83f63) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | [0eef83e969](https://linux-hardware.org/?probe=0eef83e969) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | [3268b6af5f](https://linux-hardware.org/?probe=3268b6af5f) | Nov 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [3d53b3616f](https://linux-hardware.org/?probe=3d53b3616f) | Nov 06, 2022 |
| HP            | Pavilion g6                 | [43eefaca07](https://linux-hardware.org/?probe=43eefaca07) | Nov 06, 2022 |
| ASUSTek       | K56CA                       | [032fa97b2a](https://linux-hardware.org/?probe=032fa97b2a) | Nov 05, 2022 |
| ASUSTek       | FX503VD                     | [f80b5eaa0b](https://linux-hardware.org/?probe=f80b5eaa0b) | Nov 05, 2022 |
| Lenovo        | ThinkPad L380 20M50013MH    | [80ac51627a](https://linux-hardware.org/?probe=80ac51627a) | Nov 05, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [eeda582315](https://linux-hardware.org/?probe=eeda582315) | Nov 04, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [afeb473322](https://linux-hardware.org/?probe=afeb473322) | Nov 04, 2022 |
| HP            | EliteBook 745 G6            | [d4d0f735d4](https://linux-hardware.org/?probe=d4d0f735d4) | Nov 03, 2022 |
| HP            | EliteBook 745 G6            | [04e15fb2d7](https://linux-hardware.org/?probe=04e15fb2d7) | Nov 03, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [29617200dd](https://linux-hardware.org/?probe=29617200dd) | Nov 03, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [24f27140f8](https://linux-hardware.org/?probe=24f27140f8) | Nov 03, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [11d229ea2c](https://linux-hardware.org/?probe=11d229ea2c) | Nov 03, 2022 |
| Dell          | XPS 15 9520                 | [24eea2c3f7](https://linux-hardware.org/?probe=24eea2c3f7) | Nov 03, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [08a8e0079a](https://linux-hardware.org/?probe=08a8e0079a) | Nov 03, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0235661dbe](https://linux-hardware.org/?probe=0235661dbe) | Nov 03, 2022 |
| Apple         | MacBookPro8,1               | [b4f9d04f4d](https://linux-hardware.org/?probe=b4f9d04f4d) | Nov 03, 2022 |
| Dell          | XPS 15 9510                 | [fea56b5428](https://linux-hardware.org/?probe=fea56b5428) | Nov 03, 2022 |
| HP            | EliteBook 865 16 inch G9... | [d1b0eff99b](https://linux-hardware.org/?probe=d1b0eff99b) | Nov 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [020d8fd7e0](https://linux-hardware.org/?probe=020d8fd7e0) | Nov 03, 2022 |
| HP            | Pavilion g6                 | [22b32d9bac](https://linux-hardware.org/?probe=22b32d9bac) | Nov 02, 2022 |
| HP            | Pavilion g6                 | [24c2a01761](https://linux-hardware.org/?probe=24c2a01761) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| HP            | ProBook 4530s               | [6490664312](https://linux-hardware.org/?probe=6490664312) | Nov 01, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [a85aef0a90](https://linux-hardware.org/?probe=a85aef0a90) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | [46f1da66b6](https://linux-hardware.org/?probe=46f1da66b6) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | [1409a7f78d](https://linux-hardware.org/?probe=1409a7f78d) | Oct 31, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [221710c9ea](https://linux-hardware.org/?probe=221710c9ea) | Oct 31, 2022 |
| Lenovo        | ThinkPad T490 20N3000KMH    | [3cb8d29f84](https://linux-hardware.org/?probe=3cb8d29f84) | Oct 31, 2022 |
| Lenovo        | ThinkPad T490 20N3000KMH    | [c54736f079](https://linux-hardware.org/?probe=c54736f079) | Oct 30, 2022 |
| Lenovo        | Legion Y740-17ICHg 81HH     | [ea1c9e069e](https://linux-hardware.org/?probe=ea1c9e069e) | Oct 29, 2022 |
| Medion        | X682X                       | [f05dd25a08](https://linux-hardware.org/?probe=f05dd25a08) | Oct 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3e6896ee0a](https://linux-hardware.org/?probe=3e6896ee0a) | Oct 28, 2022 |
| HP            | ZBook 15 G3                 | [2b886c255e](https://linux-hardware.org/?probe=2b886c255e) | Oct 27, 2022 |
| Dell          | Inspiron 7773               | [34d97b7ea2](https://linux-hardware.org/?probe=34d97b7ea2) | Oct 26, 2022 |
| Dell          | Inspiron 7773               | [c2cff54e7c](https://linux-hardware.org/?probe=c2cff54e7c) | Oct 26, 2022 |
| HP            | ZBook 15 G5                 | [0cb3fb3efc](https://linux-hardware.org/?probe=0cb3fb3efc) | Oct 25, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [28c38a498d](https://linux-hardware.org/?probe=28c38a498d) | Oct 25, 2022 |
| Dell          | XPS 15 9510                 | [b14c37f999](https://linux-hardware.org/?probe=b14c37f999) | Oct 25, 2022 |
| Acer          | Aspire VN7-792G             | [2c1e50d1a2](https://linux-hardware.org/?probe=2c1e50d1a2) | Oct 22, 2022 |
| HP            | Pavilion TS 11              | [6437fb22e1](https://linux-hardware.org/?probe=6437fb22e1) | Oct 22, 2022 |
| HP            | Pavilion TS 11              | [a19b5987c6](https://linux-hardware.org/?probe=a19b5987c6) | Oct 22, 2022 |
| ASUSTek       | X756UQK                     | [2570a4e51f](https://linux-hardware.org/?probe=2570a4e51f) | Oct 22, 2022 |
| Dell          | Latitude 7480               | [2b377dce0a](https://linux-hardware.org/?probe=2b377dce0a) | Oct 21, 2022 |
| Dell          | Latitude 3380               | [352bedd96b](https://linux-hardware.org/?probe=352bedd96b) | Oct 18, 2022 |
| Dell          | Precision 5530              | [9b344fe820](https://linux-hardware.org/?probe=9b344fe820) | Oct 18, 2022 |
| Dell          | Latitude 7480               | [7919e68317](https://linux-hardware.org/?probe=7919e68317) | Oct 18, 2022 |
| Dell          | Latitude E6540              | [8ba8f257d2](https://linux-hardware.org/?probe=8ba8f257d2) | Oct 18, 2022 |
| HP            | ZBook 14u G5                | [151433ee2e](https://linux-hardware.org/?probe=151433ee2e) | Oct 18, 2022 |
| Dell          | Inspiron 7720               | [1117fe6b9e](https://linux-hardware.org/?probe=1117fe6b9e) | Oct 17, 2022 |
| Dell          | Latitude 7480               | [8d55df4648](https://linux-hardware.org/?probe=8d55df4648) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [6243f8cdb8](https://linux-hardware.org/?probe=6243f8cdb8) | Oct 17, 2022 |
| Dell          | XPS 15 9510                 | [9e1f6ae49e](https://linux-hardware.org/?probe=9e1f6ae49e) | Oct 17, 2022 |
| HP            | Pavilion g6                 | [c19a6241e1](https://linux-hardware.org/?probe=c19a6241e1) | Oct 17, 2022 |
| Dell          | XPS 15 9510                 | [2fd734cbfb](https://linux-hardware.org/?probe=2fd734cbfb) | Oct 17, 2022 |
| Dell          | Latitude 3380               | [ab6969eabd](https://linux-hardware.org/?probe=ab6969eabd) | Oct 17, 2022 |
| HP            | ZBook Studio G5             | [0a9b0167c7](https://linux-hardware.org/?probe=0a9b0167c7) | Oct 17, 2022 |
| Acer          | Aspire 5742G                | [79a5162024](https://linux-hardware.org/?probe=79a5162024) | Oct 16, 2022 |
| Dell          | Latitude E7450              | [500311a1b8](https://linux-hardware.org/?probe=500311a1b8) | Oct 16, 2022 |
| Packard Be... | EasyNote TJ66               | [e5f4bf84f8](https://linux-hardware.org/?probe=e5f4bf84f8) | Oct 14, 2022 |
| Acer          | Aspire E5-553G              | [fcf93f53f4](https://linux-hardware.org/?probe=fcf93f53f4) | Oct 13, 2022 |
| Acer          | Aspire 5732Z                | [b75d98cfc2](https://linux-hardware.org/?probe=b75d98cfc2) | Oct 13, 2022 |
| Dell          | Latitude E7250              | [f397f81353](https://linux-hardware.org/?probe=f397f81353) | Oct 12, 2022 |
| Lenovo        | Y310                        | [0fe2ca4221](https://linux-hardware.org/?probe=0fe2ca4221) | Oct 12, 2022 |
| Dell          | Latitude E6420              | [0083bd14b8](https://linux-hardware.org/?probe=0083bd14b8) | Oct 12, 2022 |
| Acer          | Aspire A715-75G             | [93ca81946a](https://linux-hardware.org/?probe=93ca81946a) | Oct 11, 2022 |
| Acer          | Aspire A715-75G             | [921c4a26d1](https://linux-hardware.org/?probe=921c4a26d1) | Oct 11, 2022 |
| Acer          | Predator PH317-52           | [379aad9180](https://linux-hardware.org/?probe=379aad9180) | Oct 10, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | [cc663da2bc](https://linux-hardware.org/?probe=cc663da2bc) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [6c2f880759](https://linux-hardware.org/?probe=6c2f880759) | Oct 09, 2022 |
| HP            | Pavilion TS 11              | [1a6ea38863](https://linux-hardware.org/?probe=1a6ea38863) | Oct 09, 2022 |
| MSI           | GP60 2PE                    | [530a81df09](https://linux-hardware.org/?probe=530a81df09) | Oct 09, 2022 |
| Packard Be... | EasyNote LE69KB             | [8858f6d8f3](https://linux-hardware.org/?probe=8858f6d8f3) | Oct 08, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [b3b9f964b7](https://linux-hardware.org/?probe=b3b9f964b7) | Oct 08, 2022 |
| Toshiba       | Satellite Pro P200          | [1ca9c6c574](https://linux-hardware.org/?probe=1ca9c6c574) | Oct 07, 2022 |
| Dell          | Latitude E6510              | [67f07a2413](https://linux-hardware.org/?probe=67f07a2413) | Oct 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [afeba82ecf](https://linux-hardware.org/?probe=afeba82ecf) | Oct 07, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [c8c6a428db](https://linux-hardware.org/?probe=c8c6a428db) | Oct 06, 2022 |
| HP            | ZBook 15 G5                 | [ae7f5753fd](https://linux-hardware.org/?probe=ae7f5753fd) | Oct 05, 2022 |
| Acer          | Aspire 7741                 | [55afdd2a98](https://linux-hardware.org/?probe=55afdd2a98) | Oct 04, 2022 |
| Dell          | Precision 7560              | [877583cc90](https://linux-hardware.org/?probe=877583cc90) | Oct 04, 2022 |
| Lenovo        | ThinkPad T430s 2356B46      | [defefb2514](https://linux-hardware.org/?probe=defefb2514) | Oct 04, 2022 |
| Toshiba       | Satellite Pro P200          | [d08fe22261](https://linux-hardware.org/?probe=d08fe22261) | Oct 03, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | [0d67980efe](https://linux-hardware.org/?probe=0d67980efe) | Oct 03, 2022 |
| Samsung       | 550XED                      | [f2e8965164](https://linux-hardware.org/?probe=f2e8965164) | Oct 03, 2022 |
| HP            | OMEN by Laptop              | [971859f63e](https://linux-hardware.org/?probe=971859f63e) | Oct 02, 2022 |
| Dell          | Inspiron 16 Plus 7620       | [23475045f2](https://linux-hardware.org/?probe=23475045f2) | Oct 02, 2022 |
| Apple         | MacBookPro5,5               | [42113dd7e3](https://linux-hardware.org/?probe=42113dd7e3) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | [5bc67115db](https://linux-hardware.org/?probe=5bc67115db) | Oct 01, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [6525098252](https://linux-hardware.org/?probe=6525098252) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | [4758af490a](https://linux-hardware.org/?probe=4758af490a) | Oct 01, 2022 |
| System76      | Darter Pro                  | [2829e72506](https://linux-hardware.org/?probe=2829e72506) | Oct 01, 2022 |
| System76      | Darter Pro                  | [c142cf370a](https://linux-hardware.org/?probe=c142cf370a) | Oct 01, 2022 |
| ASUSTek       | X580VD                      | [e7ef06706d](https://linux-hardware.org/?probe=e7ef06706d) | Sep 30, 2022 |
| Dell          | Inspiron 16 Plus 7620       | [73e2559339](https://linux-hardware.org/?probe=73e2559339) | Sep 30, 2022 |
| Dell          | Latitude 5400               | [66a5bc26f0](https://linux-hardware.org/?probe=66a5bc26f0) | Sep 30, 2022 |
| Dell          | Latitude 3310               | [3c4874fa51](https://linux-hardware.org/?probe=3c4874fa51) | Sep 30, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [d5c0e2c5d3](https://linux-hardware.org/?probe=d5c0e2c5d3) | Sep 30, 2022 |
| Dell          | Latitude 5400               | [4536a4b473](https://linux-hardware.org/?probe=4536a4b473) | Sep 29, 2022 |
| Dell          | Latitude 5400               | [972e4ab3fa](https://linux-hardware.org/?probe=972e4ab3fa) | Sep 29, 2022 |
| Dell          | Latitude E6520              | [e228fa6546](https://linux-hardware.org/?probe=e228fa6546) | Sep 28, 2022 |
| Dell          | Latitude 3310               | [c21a321dce](https://linux-hardware.org/?probe=c21a321dce) | Sep 28, 2022 |
| Acer          | Aspire A715-75G             | [9489561c26](https://linux-hardware.org/?probe=9489561c26) | Sep 28, 2022 |
| Dell          | XPS 13 9310                 | [4073c084df](https://linux-hardware.org/?probe=4073c084df) | Sep 28, 2022 |
| Lenovo        | ThinkPad E550 20DF00CUFR    | [7b5e707097](https://linux-hardware.org/?probe=7b5e707097) | Sep 27, 2022 |
| Samsung       | 750XED                      | [dcb54d69f8](https://linux-hardware.org/?probe=dcb54d69f8) | Sep 27, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [d0f8e8a0f6](https://linux-hardware.org/?probe=d0f8e8a0f6) | Sep 27, 2022 |
| Dell          | Latitude 3300               | [365349d964](https://linux-hardware.org/?probe=365349d964) | Sep 27, 2022 |
| Dell          | Latitude 3310               | [313ab64584](https://linux-hardware.org/?probe=313ab64584) | Sep 27, 2022 |
| Dell          | Precision M6800             | [a2f07e79d3](https://linux-hardware.org/?probe=a2f07e79d3) | Sep 27, 2022 |
| Dell          | Latitude 3420               | [ee7c1fce66](https://linux-hardware.org/?probe=ee7c1fce66) | Sep 26, 2022 |
| Dell          | Latitude 3310               | [0f1fb4687f](https://linux-hardware.org/?probe=0f1fb4687f) | Sep 26, 2022 |
| Dell          | Latitude 3310               | [a6ce17cd6b](https://linux-hardware.org/?probe=a6ce17cd6b) | Sep 26, 2022 |
| Dell          | Latitude 3310               | [87af9a8980](https://linux-hardware.org/?probe=87af9a8980) | Sep 26, 2022 |
| Valve         | Jupiter                     | [8c94cd9bd3](https://linux-hardware.org/?probe=8c94cd9bd3) | Sep 26, 2022 |
| Dell          | Latitude 13                 | [28d623103e](https://linux-hardware.org/?probe=28d623103e) | Sep 25, 2022 |
| Dell          | Precision M6800             | [83c3e91298](https://linux-hardware.org/?probe=83c3e91298) | Sep 24, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | [ccba8f6c1a](https://linux-hardware.org/?probe=ccba8f6c1a) | Sep 24, 2022 |
| Dell          | Inspiron 16 Plus 7620       | [977d73b98a](https://linux-hardware.org/?probe=977d73b98a) | Sep 24, 2022 |
| Dell          | Latitude E5570              | [df18be69a3](https://linux-hardware.org/?probe=df18be69a3) | Sep 24, 2022 |
| Dell          | Latitude E6520              | [81612aa665](https://linux-hardware.org/?probe=81612aa665) | Sep 24, 2022 |
| Dell          | Latitude E6520              | [fc343204c6](https://linux-hardware.org/?probe=fc343204c6) | Sep 23, 2022 |
| Dell          | Latitude E6520              | [79aa87fb47](https://linux-hardware.org/?probe=79aa87fb47) | Sep 23, 2022 |
| Dell          | Latitude 3310               | [4c5dc33267](https://linux-hardware.org/?probe=4c5dc33267) | Sep 23, 2022 |
| Dell          | Latitude E6320              | [452304d040](https://linux-hardware.org/?probe=452304d040) | Sep 22, 2022 |
| Dell          | XPS 9320                    | [6866f3105c](https://linux-hardware.org/?probe=6866f3105c) | Sep 22, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [efaa235d34](https://linux-hardware.org/?probe=efaa235d34) | Sep 22, 2022 |
| Valve         | Jupiter                     | [ce15d6d4bb](https://linux-hardware.org/?probe=ce15d6d4bb) | Sep 22, 2022 |
| ASUSTek       | 1201PN                      | [3dd4546344](https://linux-hardware.org/?probe=3dd4546344) | Sep 21, 2022 |
| ASUSTek       | 1201PN                      | [080d9c8964](https://linux-hardware.org/?probe=080d9c8964) | Sep 21, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [3e80cdec5b](https://linux-hardware.org/?probe=3e80cdec5b) | Sep 20, 2022 |
| Notebook      | NH55RGQ                     | [f4aade3998](https://linux-hardware.org/?probe=f4aade3998) | Sep 20, 2022 |
| Notebook      | NH55RGQ                     | [95c8201663](https://linux-hardware.org/?probe=95c8201663) | Sep 20, 2022 |
| ASUSTek       | X555LAB                     | [71339e0cfb](https://linux-hardware.org/?probe=71339e0cfb) | Sep 19, 2022 |
| ASUSTek       | X555LAB                     | [a0acb674df](https://linux-hardware.org/?probe=a0acb674df) | Sep 19, 2022 |
| Dell          | Latitude 3310               | [0e1784b38d](https://linux-hardware.org/?probe=0e1784b38d) | Sep 19, 2022 |
| HUAWEI        | WRT-WX9                     | [4c8883345d](https://linux-hardware.org/?probe=4c8883345d) | Sep 19, 2022 |
| Dell          | Latitude 3310               | [55332651e0](https://linux-hardware.org/?probe=55332651e0) | Sep 19, 2022 |
| Dell          | Latitude 3120               | [558e95141d](https://linux-hardware.org/?probe=558e95141d) | Sep 19, 2022 |
| Dell          | Latitude 3300               | [a2513a9849](https://linux-hardware.org/?probe=a2513a9849) | Sep 19, 2022 |
| Chuwi         | GemiBook                    | [c6ec4f6320](https://linux-hardware.org/?probe=c6ec4f6320) | Sep 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [daa76ef1c9](https://linux-hardware.org/?probe=daa76ef1c9) | Sep 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [b0a2728114](https://linux-hardware.org/?probe=b0a2728114) | Sep 17, 2022 |
| Acer          | Swift SF314-57              | [8c905d820d](https://linux-hardware.org/?probe=8c905d820d) | Sep 17, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [59369fa3fb](https://linux-hardware.org/?probe=59369fa3fb) | Sep 17, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [cf4e574788](https://linux-hardware.org/?probe=cf4e574788) | Sep 16, 2022 |
| ASUSTek       | X75VC                       | [c8abec750c](https://linux-hardware.org/?probe=c8abec750c) | Sep 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [54ea6ab133](https://linux-hardware.org/?probe=54ea6ab133) | Sep 14, 2022 |
| Valve         | Jupiter                     | [9817414c4e](https://linux-hardware.org/?probe=9817414c4e) | Sep 14, 2022 |
| Lenovo        | G50-70 20351                | [4105fc929e](https://linux-hardware.org/?probe=4105fc929e) | Sep 13, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | [b7eb07ec8d](https://linux-hardware.org/?probe=b7eb07ec8d) | Sep 12, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [7064ea27f5](https://linux-hardware.org/?probe=7064ea27f5) | Sep 11, 2022 |
| Packard Be... | EasyNote LE69KB             | [a008db4da9](https://linux-hardware.org/?probe=a008db4da9) | Sep 11, 2022 |
| HP            | Laptop 15s-eq2xxx           | [c0adc468b3](https://linux-hardware.org/?probe=c0adc468b3) | Sep 10, 2022 |
| Packard Be... | EasyNote MH36               | [32025f0e69](https://linux-hardware.org/?probe=32025f0e69) | Sep 10, 2022 |
| SKIKK         | Standard                    | [3d7a0b8762](https://linux-hardware.org/?probe=3d7a0b8762) | Sep 08, 2022 |
| Dell          | XPS 15 9510                 | [db80996c7a](https://linux-hardware.org/?probe=db80996c7a) | Sep 08, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [ea53dc8c02](https://linux-hardware.org/?probe=ea53dc8c02) | Sep 07, 2022 |
| Alienware     | x15 R2                      | [28e491fc3f](https://linux-hardware.org/?probe=28e491fc3f) | Sep 07, 2022 |
| Alienware     | x15 R2                      | [8acf26b5a3](https://linux-hardware.org/?probe=8acf26b5a3) | Sep 06, 2022 |
| HP            | ZBook 15u G6                | [af658eb920](https://linux-hardware.org/?probe=af658eb920) | Sep 06, 2022 |
| Dell          | Latitude 5530               | [4a2fb0c4c2](https://linux-hardware.org/?probe=4a2fb0c4c2) | Sep 06, 2022 |
| Dell          | Latitude 5530               | [a0896a063c](https://linux-hardware.org/?probe=a0896a063c) | Sep 06, 2022 |
| Apple         | MacBookPro5,5               | [70de682c06](https://linux-hardware.org/?probe=70de682c06) | Sep 03, 2022 |
| HP            | EliteBook 8460p             | [8aac8566b3](https://linux-hardware.org/?probe=8aac8566b3) | Sep 03, 2022 |
| Dell          | Latitude 3120               | [8716f564d8](https://linux-hardware.org/?probe=8716f564d8) | Sep 02, 2022 |
| Dell          | Inspiron 5490               | [3ef6519b6d](https://linux-hardware.org/?probe=3ef6519b6d) | Sep 01, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d34c9cb705](https://linux-hardware.org/?probe=d34c9cb705) | Sep 01, 2022 |
| Dell          | Latitude 3190               | [d30269b33c](https://linux-hardware.org/?probe=d30269b33c) | Sep 01, 2022 |
| HP            | ProBook 6460b               | [a0e3db2eed](https://linux-hardware.org/?probe=a0e3db2eed) | Sep 01, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [c86e73aed6](https://linux-hardware.org/?probe=c86e73aed6) | Sep 01, 2022 |
| ASUSTek       | UX550VD                     | [a43d53b3b7](https://linux-hardware.org/?probe=a43d53b3b7) | Sep 01, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X8... | [df33320d10](https://linux-hardware.org/?probe=df33320d10) | Aug 30, 2022 |
| Acer          | Aspire SW5-271              | [3446f93f1d](https://linux-hardware.org/?probe=3446f93f1d) | Aug 29, 2022 |
| Apple         | MacBookPro7,1               | [a879fb8249](https://linux-hardware.org/?probe=a879fb8249) | Aug 29, 2022 |
| ASUSTek       | N550JV                      | [059ab7e21e](https://linux-hardware.org/?probe=059ab7e21e) | Aug 29, 2022 |
| Dell          | XPS 15 9510                 | [45bba02b35](https://linux-hardware.org/?probe=45bba02b35) | Aug 29, 2022 |
| Dell          | Latitude 3300               | [bea8e53929](https://linux-hardware.org/?probe=bea8e53929) | Aug 29, 2022 |
| Dell          | Vostro 14 5410              | [2d4b907d84](https://linux-hardware.org/?probe=2d4b907d84) | Aug 29, 2022 |
| Dell          | Latitude 5590               | [e06f40dae9](https://linux-hardware.org/?probe=e06f40dae9) | Aug 29, 2022 |
| Fujitsu       | LIFEBOOK E746               | [5b0eba15c2](https://linux-hardware.org/?probe=5b0eba15c2) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [c63d9bede8](https://linux-hardware.org/?probe=c63d9bede8) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a4a7c87b06](https://linux-hardware.org/?probe=a4a7c87b06) | Aug 27, 2022 |
| Acer          | Nitro AN515-57              | [8d314e1557](https://linux-hardware.org/?probe=8d314e1557) | Aug 27, 2022 |
| ASUSTek       | N76VB                       | [e488dd7682](https://linux-hardware.org/?probe=e488dd7682) | Aug 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [b28edd3886](https://linux-hardware.org/?probe=b28edd3886) | Aug 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [97770c5716](https://linux-hardware.org/?probe=97770c5716) | Aug 26, 2022 |
| Lenovo        | ThinkPad E580 20KS003GMH    | [5cadf3c5d2](https://linux-hardware.org/?probe=5cadf3c5d2) | Aug 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [4378f177a8](https://linux-hardware.org/?probe=4378f177a8) | Aug 24, 2022 |
| MSI           | Prestige 15 A10SC           | [35ffc8d54b](https://linux-hardware.org/?probe=35ffc8d54b) | Aug 23, 2022 |
| TEKNOSERVI... | PORTATIL TTL 15             | [054d000bb1](https://linux-hardware.org/?probe=054d000bb1) | Aug 23, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [1b1c9cb460](https://linux-hardware.org/?probe=1b1c9cb460) | Aug 23, 2022 |
| MSI           | PS63 Modern 8RC             | [33a1092c01](https://linux-hardware.org/?probe=33a1092c01) | Aug 22, 2022 |
| Dell          | XPS 15 9520                 | [33ff4e4962](https://linux-hardware.org/?probe=33ff4e4962) | Aug 22, 2022 |
| Dell          | Latitude 7420               | [ebbef2bf39](https://linux-hardware.org/?probe=ebbef2bf39) | Aug 22, 2022 |
| Dell          | Latitude 3300               | [e8b139ecad](https://linux-hardware.org/?probe=e8b139ecad) | Aug 22, 2022 |
| Dell          | Latitude 3310               | [dedda1b96c](https://linux-hardware.org/?probe=dedda1b96c) | Aug 22, 2022 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | [1380621999](https://linux-hardware.org/?probe=1380621999) | Aug 21, 2022 |
| Apple         | MacBookPro8,2               | [b01d72c341](https://linux-hardware.org/?probe=b01d72c341) | Aug 20, 2022 |
| HP            | ENVY Notebook               | [7d790e2b4d](https://linux-hardware.org/?probe=7d790e2b4d) | Aug 20, 2022 |
| Dell          | Latitude E6430              | [c7a98ce916](https://linux-hardware.org/?probe=c7a98ce916) | Aug 20, 2022 |
| HP            | Laptop 17-cp0xxx            | [9e72f598eb](https://linux-hardware.org/?probe=9e72f598eb) | Aug 19, 2022 |
| Dell          | Inspiron 5490               | [98f795ee5f](https://linux-hardware.org/?probe=98f795ee5f) | Aug 19, 2022 |
| Dell          | Latitude E6420              | [588755599f](https://linux-hardware.org/?probe=588755599f) | Aug 18, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9619850e97](https://linux-hardware.org/?probe=9619850e97) | Aug 18, 2022 |
| Dell          | Latitude 3380               | [a99b3cef26](https://linux-hardware.org/?probe=a99b3cef26) | Aug 17, 2022 |
| Dell          | Latitude 3310               | [92f66bf3aa](https://linux-hardware.org/?probe=92f66bf3aa) | Aug 17, 2022 |
| Unknown       | Unknown                     | [66053f0e50](https://linux-hardware.org/?probe=66053f0e50) | Aug 17, 2022 |
| Dell          | Latitude 3310               | [1694bfcea7](https://linux-hardware.org/?probe=1694bfcea7) | Aug 16, 2022 |
| ASUSTek       | K53TA                       | [db6525efb3](https://linux-hardware.org/?probe=db6525efb3) | Aug 15, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [ffe1757df5](https://linux-hardware.org/?probe=ffe1757df5) | Aug 15, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [caf6393a95](https://linux-hardware.org/?probe=caf6393a95) | Aug 15, 2022 |
| HP            | Elite x2 1012 G1            | [94fb37c745](https://linux-hardware.org/?probe=94fb37c745) | Aug 14, 2022 |
| MSI           | CX705                       | [d2c7d43ba9](https://linux-hardware.org/?probe=d2c7d43ba9) | Aug 14, 2022 |
| HP            | EliteBook 745 G3            | [913928c7ee](https://linux-hardware.org/?probe=913928c7ee) | Aug 13, 2022 |
| HP            | EliteBook 745 G3            | [bfc035a690](https://linux-hardware.org/?probe=bfc035a690) | Aug 13, 2022 |
| Apple         | MacBookPro9,2               | [f48110428f](https://linux-hardware.org/?probe=f48110428f) | Aug 11, 2022 |
| Apple         | MacBookPro14,2              | [9e297d5dde](https://linux-hardware.org/?probe=9e297d5dde) | Aug 11, 2022 |
| HP            | Elite x2 1012 G1            | [a76e460266](https://linux-hardware.org/?probe=a76e460266) | Aug 11, 2022 |
| Dell          | Latitude E6420              | [c5ce4b0bff](https://linux-hardware.org/?probe=c5ce4b0bff) | Aug 10, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [bd5bfb000b](https://linux-hardware.org/?probe=bd5bfb000b) | Aug 10, 2022 |
| Acer          | Aspire 7720                 | [0ceb259a2f](https://linux-hardware.org/?probe=0ceb259a2f) | Aug 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [9cdc2bc860](https://linux-hardware.org/?probe=9cdc2bc860) | Aug 08, 2022 |
| Notebook      | P64_HJ,HK1                  | [942bd9a76d](https://linux-hardware.org/?probe=942bd9a76d) | Aug 08, 2022 |
| Notebook      | P64_HJ,HK1                  | [0de18680fd](https://linux-hardware.org/?probe=0de18680fd) | Aug 08, 2022 |
| Dell          | Latitude E6420              | [54981e31fa](https://linux-hardware.org/?probe=54981e31fa) | Aug 08, 2022 |
| HP            | ProBook 430 G4              | [616a031820](https://linux-hardware.org/?probe=616a031820) | Aug 08, 2022 |
| HP            | ProBook 455 G7              | [c563966e9c](https://linux-hardware.org/?probe=c563966e9c) | Aug 06, 2022 |
| HP            | Notebook                    | [d9806ef95e](https://linux-hardware.org/?probe=d9806ef95e) | Aug 06, 2022 |
| Dell          | Precision 3570              | [fd1c9b5ad9](https://linux-hardware.org/?probe=fd1c9b5ad9) | Aug 06, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [eedde9d976](https://linux-hardware.org/?probe=eedde9d976) | Aug 05, 2022 |
| Dell          | Latitude 3310               | [97ac18f196](https://linux-hardware.org/?probe=97ac18f196) | Aug 05, 2022 |
| Dell          | Latitude 3410               | [8181c3588f](https://linux-hardware.org/?probe=8181c3588f) | Aug 05, 2022 |
| Apple         | MacBookPro14,2              | [d1079f3fba](https://linux-hardware.org/?probe=d1079f3fba) | Aug 04, 2022 |
| Medion        | E7419 MD60990               | [e1b74852bd](https://linux-hardware.org/?probe=e1b74852bd) | Aug 04, 2022 |
| HONOR         | BOHK-WAX9X                  | [3d426cb1de](https://linux-hardware.org/?probe=3d426cb1de) | Aug 04, 2022 |
| Dell          | Latitude 3490               | [fa1c5f753f](https://linux-hardware.org/?probe=fa1c5f753f) | Aug 04, 2022 |
| Dell          | Latitude 3310               | [9b9bed6ac6](https://linux-hardware.org/?probe=9b9bed6ac6) | Aug 04, 2022 |
| Apple         | MacBookPro16,1              | [0886c5ef7f](https://linux-hardware.org/?probe=0886c5ef7f) | Aug 04, 2022 |
| Apple         | MacBookPro9,2               | [f0479b116f](https://linux-hardware.org/?probe=f0479b116f) | Aug 03, 2022 |
| Apple         | MacBookPro9,2               | [245834865d](https://linux-hardware.org/?probe=245834865d) | Aug 03, 2022 |
| Toshiba       | Satellite P200              | [87bf7fcb48](https://linux-hardware.org/?probe=87bf7fcb48) | Aug 03, 2022 |
| ASUSTek       | X756UQK                     | [97b2316a06](https://linux-hardware.org/?probe=97b2316a06) | Aug 03, 2022 |
| Dell          | XPS 13 7390                 | [05e8b8d782](https://linux-hardware.org/?probe=05e8b8d782) | Aug 03, 2022 |
| Dell          | Latitude E6420              | [59c6623274](https://linux-hardware.org/?probe=59c6623274) | Aug 02, 2022 |
| HP            | Laptop 17-cp0xxx            | [eedeb321f6](https://linux-hardware.org/?probe=eedeb321f6) | Aug 02, 2022 |
| Dell          | XPS 13 9360                 | [f34ae117a3](https://linux-hardware.org/?probe=f34ae117a3) | Aug 02, 2022 |
| Apple         | MacBookPro5,5               | [4eeca116f8](https://linux-hardware.org/?probe=4eeca116f8) | Aug 01, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [16a3f81537](https://linux-hardware.org/?probe=16a3f81537) | Aug 01, 2022 |
| HP            | EliteBook 745 G6            | [2546e4a593](https://linux-hardware.org/?probe=2546e4a593) | Aug 01, 2022 |
| HP            | ProBook 6570b               | [333a24bdee](https://linux-hardware.org/?probe=333a24bdee) | Jul 31, 2022 |
| Fujitsu       | LIFEBOOK S936               | [90a08a49a3](https://linux-hardware.org/?probe=90a08a49a3) | Jul 31, 2022 |
| Fujitsu       | LIFEBOOK S936               | [1af46d1c56](https://linux-hardware.org/?probe=1af46d1c56) | Jul 31, 2022 |
| Dell          | Latitude E7470              | [ca7878faab](https://linux-hardware.org/?probe=ca7878faab) | Jul 30, 2022 |
| HP            | Notebook                    | [ac46775f8b](https://linux-hardware.org/?probe=ac46775f8b) | Jul 30, 2022 |
| Lenovo        | G700 20251                  | [24a9e92897](https://linux-hardware.org/?probe=24a9e92897) | Jul 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ef7aa9cb2e](https://linux-hardware.org/?probe=ef7aa9cb2e) | Jul 29, 2022 |
| ASUSTek       | N76VB                       | [15cea344b9](https://linux-hardware.org/?probe=15cea344b9) | Jul 27, 2022 |
| HP            | Pavilion g7                 | [75fa7f0ce4](https://linux-hardware.org/?probe=75fa7f0ce4) | Jul 27, 2022 |
| Lenovo        | ThinkPad E550 20DF0040CA    | [f54dc4ee78](https://linux-hardware.org/?probe=f54dc4ee78) | Jul 26, 2022 |
| Dell          | Latitude 3300               | [64cf4b87d9](https://linux-hardware.org/?probe=64cf4b87d9) | Jul 26, 2022 |
| Dell          | Latitude 3310               | [0fe12d0d48](https://linux-hardware.org/?probe=0fe12d0d48) | Jul 25, 2022 |
| Lenovo        | ThinkPad E550 20DF0040CA    | [276e2a32dc](https://linux-hardware.org/?probe=276e2a32dc) | Jul 25, 2022 |
| MSI           | GP60 2PE                    | [0fa37c70f5](https://linux-hardware.org/?probe=0fa37c70f5) | Jul 24, 2022 |
| ASUSTek       | X751MA                      | [4986a5eabc](https://linux-hardware.org/?probe=4986a5eabc) | Jul 24, 2022 |
| ASUSTek       | GL702VI                     | [7bb350de7e](https://linux-hardware.org/?probe=7bb350de7e) | Jul 24, 2022 |
| HP            | EliteBook 840 G4            | [d8d889ef85](https://linux-hardware.org/?probe=d8d889ef85) | Jul 23, 2022 |
| ASUSTek       | GL702VI                     | [ca8b9fbf8f](https://linux-hardware.org/?probe=ca8b9fbf8f) | Jul 22, 2022 |
| Dell          | Latitude 3310               | [bc6103f96b](https://linux-hardware.org/?probe=bc6103f96b) | Jul 21, 2022 |
| Dell          | Latitude 3310               | [abe159e82a](https://linux-hardware.org/?probe=abe159e82a) | Jul 21, 2022 |
| Dell          | Latitude 3310               | [d90f147df3](https://linux-hardware.org/?probe=d90f147df3) | Jul 21, 2022 |
| Dell          | Latitude 3310               | [324b95a49a](https://linux-hardware.org/?probe=324b95a49a) | Jul 21, 2022 |
| Dell          | Latitude 3310               | [086f88be40](https://linux-hardware.org/?probe=086f88be40) | Jul 20, 2022 |
| Dell          | Latitude 3310               | [0cb2abc6bc](https://linux-hardware.org/?probe=0cb2abc6bc) | Jul 20, 2022 |
| Dell          | Latitude 3310               | [dbd9b101c2](https://linux-hardware.org/?probe=dbd9b101c2) | Jul 20, 2022 |
| Acer          | Aspire 7560                 | [a0f1f7abee](https://linux-hardware.org/?probe=a0f1f7abee) | Jul 19, 2022 |
| Apple         | MacBookPro14,2              | [4f1ce227b5](https://linux-hardware.org/?probe=4f1ce227b5) | Jul 18, 2022 |
| Sony          | VPCEA1C5E                   | [4592d973d6](https://linux-hardware.org/?probe=4592d973d6) | Jul 18, 2022 |
| HP            | Pavilion g7                 | [5129e33508](https://linux-hardware.org/?probe=5129e33508) | Jul 18, 2022 |
| Acer          | Aspire 7560                 | [5bf15dc370](https://linux-hardware.org/?probe=5bf15dc370) | Jul 17, 2022 |
| ASUSTek       | 1201N                       | [05eb1e3b1b](https://linux-hardware.org/?probe=05eb1e3b1b) | Jul 17, 2022 |
| HP            | Pavilion g7                 | [9230cd5f0e](https://linux-hardware.org/?probe=9230cd5f0e) | Jul 16, 2022 |
| Dell          | Latitude E6510              | [42fcd7f8c8](https://linux-hardware.org/?probe=42fcd7f8c8) | Jul 16, 2022 |
| HP            | Laptop 17-cp0xxx            | [476ab880f4](https://linux-hardware.org/?probe=476ab880f4) | Jul 15, 2022 |
| HP            | Pavilion Laptop 13-an0xx... | [6021e75347](https://linux-hardware.org/?probe=6021e75347) | Jul 13, 2022 |
| Apple         | MacBookPro11,2              | [11e98244ac](https://linux-hardware.org/?probe=11e98244ac) | Jul 12, 2022 |
| Jumper        | EZbook                      | [2515427610](https://linux-hardware.org/?probe=2515427610) | Jul 12, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [9703351d30](https://linux-hardware.org/?probe=9703351d30) | Jul 12, 2022 |
| Notebook      | NL5xRU                      | [a4bc7e790c](https://linux-hardware.org/?probe=a4bc7e790c) | Jul 11, 2022 |
| Insyde        | Skylake                     | [3c3afd7b46](https://linux-hardware.org/?probe=3c3afd7b46) | Jul 10, 2022 |
| Dell          | XPS 13 9333                 | [e464cd5823](https://linux-hardware.org/?probe=e464cd5823) | Jul 08, 2022 |
| Notebook      | NH55RGQ                     | [37de891a60](https://linux-hardware.org/?probe=37de891a60) | Jul 08, 2022 |
| HP            | ProBook 4540s               | [6b67ccac52](https://linux-hardware.org/?probe=6b67ccac52) | Jul 08, 2022 |
| Lenovo        | ThinkPad X200 7458FDG       | [435e7998bd](https://linux-hardware.org/?probe=435e7998bd) | Jul 08, 2022 |
| AZW           | T3 MRD                      | [7f8d8245e1](https://linux-hardware.org/?probe=7f8d8245e1) | Jul 08, 2022 |
| HP            | EliteBook 745 G4            | [cb445678be](https://linux-hardware.org/?probe=cb445678be) | Jul 08, 2022 |
| Acer          | Aspire V3-771               | [e8488fb0e2](https://linux-hardware.org/?probe=e8488fb0e2) | Jul 07, 2022 |
| Google        | Cave                        | [fd843b1768](https://linux-hardware.org/?probe=fd843b1768) | Jul 07, 2022 |
| Dell          | Inspiron 16 5625            | [dcbe63005c](https://linux-hardware.org/?probe=dcbe63005c) | Jul 06, 2022 |
| Alienware     | 13 R2                       | [ec877e9a2e](https://linux-hardware.org/?probe=ec877e9a2e) | Jul 06, 2022 |
| Alienware     | m15                         | [9578c619e6](https://linux-hardware.org/?probe=9578c619e6) | Jul 06, 2022 |
| Purism        | Librem 15 v3                | [1e39d0bba8](https://linux-hardware.org/?probe=1e39d0bba8) | Jul 06, 2022 |
| Dell          | Latitude 5421               | [8a40be5ce5](https://linux-hardware.org/?probe=8a40be5ce5) | Jul 05, 2022 |
| Toshiba       | Satellite P50-A-12P         | [6fc4be2ae8](https://linux-hardware.org/?probe=6fc4be2ae8) | Jul 04, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [2afdf76afd](https://linux-hardware.org/?probe=2afdf76afd) | Jul 04, 2022 |
| Apple         | MacBookPro11,2              | [fe19e0e611](https://linux-hardware.org/?probe=fe19e0e611) | Jul 03, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [763752db1c](https://linux-hardware.org/?probe=763752db1c) | Jul 03, 2022 |
| Dell          | Latitude E7450              | [6dc8d46993](https://linux-hardware.org/?probe=6dc8d46993) | Jul 02, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [e13cada6ae](https://linux-hardware.org/?probe=e13cada6ae) | Jul 02, 2022 |
| Medion        | E122X                       | [ccc1d37532](https://linux-hardware.org/?probe=ccc1d37532) | Jul 02, 2022 |
| HP            | ProBook 4540s               | [c47e971697](https://linux-hardware.org/?probe=c47e971697) | Jul 01, 2022 |
| ASUSTek       | X756UQK                     | [62595fe324](https://linux-hardware.org/?probe=62595fe324) | Jul 01, 2022 |
| Fujitsu       | LIFEBOOK U938               | [c959653e4f](https://linux-hardware.org/?probe=c959653e4f) | Jun 27, 2022 |
| Fujitsu       | LIFEBOOK U938               | [be4fb4ad71](https://linux-hardware.org/?probe=be4fb4ad71) | Jun 27, 2022 |
| Apple         | MacBookPro14,2              | [7fe621e5a7](https://linux-hardware.org/?probe=7fe621e5a7) | Jun 27, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [f1b7197958](https://linux-hardware.org/?probe=f1b7197958) | Jun 25, 2022 |
| Lenovo        | ThinkPad T520 4243VE1       | [7fcfec26eb](https://linux-hardware.org/?probe=7fcfec26eb) | Jun 24, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [b450b0c2dc](https://linux-hardware.org/?probe=b450b0c2dc) | Jun 24, 2022 |
| Dell          | Latitude 3420               | [027b943645](https://linux-hardware.org/?probe=027b943645) | Jun 24, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [223e43004a](https://linux-hardware.org/?probe=223e43004a) | Jun 23, 2022 |
| Dell          | Latitude 3300               | [5275529516](https://linux-hardware.org/?probe=5275529516) | Jun 22, 2022 |
| HP            | EliteBook 830 G6            | [7c7d9af667](https://linux-hardware.org/?probe=7c7d9af667) | Jun 21, 2022 |
| Dell          | XPS 15 9570                 | [c6c4eda2cb](https://linux-hardware.org/?probe=c6c4eda2cb) | Jun 21, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1D00... | [eacaed715b](https://linux-hardware.org/?probe=eacaed715b) | Jun 21, 2022 |
| Dell          | Latitude 3190               | [14521bc3eb](https://linux-hardware.org/?probe=14521bc3eb) | Jun 20, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | [ff63b72fd2](https://linux-hardware.org/?probe=ff63b72fd2) | Jun 19, 2022 |
| Sony          | SVD1321Z9RW                 | [adc9da6fe8](https://linux-hardware.org/?probe=adc9da6fe8) | Jun 19, 2022 |
| Lenovo        | ThinkPad X240 20AMS75900    | [47b7f42708](https://linux-hardware.org/?probe=47b7f42708) | Jun 18, 2022 |
| Dell          | Latitude 3380               | [0ccd773de6](https://linux-hardware.org/?probe=0ccd773de6) | Jun 17, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | [3ec9bac70f](https://linux-hardware.org/?probe=3ec9bac70f) | Jun 17, 2022 |
| Dell          | Latitude 3420               | [178e3cbcba](https://linux-hardware.org/?probe=178e3cbcba) | Jun 17, 2022 |
| Dell          | Latitude 3300               | [ed133c13de](https://linux-hardware.org/?probe=ed133c13de) | Jun 17, 2022 |
| Dell          | Latitude 3310               | [4715235090](https://linux-hardware.org/?probe=4715235090) | Jun 17, 2022 |
| Dell          | Latitude E6420              | [5ed4263a65](https://linux-hardware.org/?probe=5ed4263a65) | Jun 17, 2022 |
| Lenovo        | G500 20236                  | [512450d910](https://linux-hardware.org/?probe=512450d910) | Jun 17, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [e21faf995b](https://linux-hardware.org/?probe=e21faf995b) | Jun 16, 2022 |
| Acer          | Aspire A515-44              | [5da40d4fd6](https://linux-hardware.org/?probe=5da40d4fd6) | Jun 16, 2022 |
| Notebook      | PA70ES                      | [7024a9dc03](https://linux-hardware.org/?probe=7024a9dc03) | Jun 16, 2022 |
| Dell          | Latitude 3310               | [549b7595b7](https://linux-hardware.org/?probe=549b7595b7) | Jun 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [6fa09c2dd0](https://linux-hardware.org/?probe=6fa09c2dd0) | Jun 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [d3f9fd8f0c](https://linux-hardware.org/?probe=d3f9fd8f0c) | Jun 16, 2022 |
| Dell          | XPS 15 9510                 | [61104911ed](https://linux-hardware.org/?probe=61104911ed) | Jun 14, 2022 |
| Google        | Quawks                      | [c513bb8294](https://linux-hardware.org/?probe=c513bb8294) | Jun 14, 2022 |
| Lenovo        | G50-70 20351                | [b4b03244a8](https://linux-hardware.org/?probe=b4b03244a8) | Jun 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [0da40dea6c](https://linux-hardware.org/?probe=0da40dea6c) | Jun 12, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [dbe7d6b6bf](https://linux-hardware.org/?probe=dbe7d6b6bf) | Jun 12, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [554002fe47](https://linux-hardware.org/?probe=554002fe47) | Jun 12, 2022 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | [283958f1a4](https://linux-hardware.org/?probe=283958f1a4) | Jun 12, 2022 |
| HP            | ProBook 4540s               | [6688afd4f5](https://linux-hardware.org/?probe=6688afd4f5) | Jun 11, 2022 |
| HP            | Pavilion dv7                | [7f7678265b](https://linux-hardware.org/?probe=7f7678265b) | Jun 11, 2022 |
| HP            | Laptop 17-bs1xx             | [aa23e1d53e](https://linux-hardware.org/?probe=aa23e1d53e) | Jun 11, 2022 |
| HP            | Pavilion dv7                | [c8d1e1be32](https://linux-hardware.org/?probe=c8d1e1be32) | Jun 10, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [1967d32245](https://linux-hardware.org/?probe=1967d32245) | Jun 10, 2022 |
| HP            | ProBook 4540s               | [d0a6dcaa92](https://linux-hardware.org/?probe=d0a6dcaa92) | Jun 09, 2022 |
| Apple         | MacBookPro5,5               | [0970e891ee](https://linux-hardware.org/?probe=0970e891ee) | Jun 07, 2022 |
| Apple         | MacBookPro5,5               | [3b33a1b625](https://linux-hardware.org/?probe=3b33a1b625) | Jun 07, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [56ab62d27b](https://linux-hardware.org/?probe=56ab62d27b) | Jun 06, 2022 |
| HP            | EliteBook 2560p             | [9cd1c3d383](https://linux-hardware.org/?probe=9cd1c3d383) | Jun 05, 2022 |
| HP            | ProBook 450 G3              | [654b62a3bb](https://linux-hardware.org/?probe=654b62a3bb) | Jun 05, 2022 |
| HP            | ProBook 4540s               | [b74c4304e9](https://linux-hardware.org/?probe=b74c4304e9) | Jun 05, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [de4976b9dd](https://linux-hardware.org/?probe=de4976b9dd) | Jun 04, 2022 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [7583c09b9d](https://linux-hardware.org/?probe=7583c09b9d) | Jun 04, 2022 |
| Schenker      | VIA_14_SVI14E20             | [3adb69bbf5](https://linux-hardware.org/?probe=3adb69bbf5) | Jun 03, 2022 |
| HP            | Pavilion dm1                | [a808588581](https://linux-hardware.org/?probe=a808588581) | Jun 03, 2022 |
| Dell          | Latitude 3189               | [f1899ceede](https://linux-hardware.org/?probe=f1899ceede) | Jun 03, 2022 |
| Dell          | XPS 15 9510                 | [5eff529610](https://linux-hardware.org/?probe=5eff529610) | Jun 02, 2022 |
| HP            | ProBook 4540s               | [da53c77e1a](https://linux-hardware.org/?probe=da53c77e1a) | Jun 02, 2022 |
| HP            | EliteBook 2560p             | [af6a91d3c7](https://linux-hardware.org/?probe=af6a91d3c7) | Jun 01, 2022 |
| Dell          | Inspiron 14 7420 2-in-1     | [131a117ca2](https://linux-hardware.org/?probe=131a117ca2) | May 31, 2022 |
| Medion        | X6816                       | [6d7996894c](https://linux-hardware.org/?probe=6d7996894c) | May 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [61cbe48681](https://linux-hardware.org/?probe=61cbe48681) | May 28, 2022 |
| Unknown       | Unknown                     | [7ca69b6206](https://linux-hardware.org/?probe=7ca69b6206) | May 28, 2022 |
| HP            | Pavilion Power Laptop 15... | [4813c4e0b4](https://linux-hardware.org/?probe=4813c4e0b4) | May 28, 2022 |
| Medion        | P6812                       | [b5416af5fd](https://linux-hardware.org/?probe=b5416af5fd) | May 28, 2022 |
| Medion        | X6816                       | [69e3c742fe](https://linux-hardware.org/?probe=69e3c742fe) | May 27, 2022 |
| Alienware     | 17 R4                       | [0a7c1705c9](https://linux-hardware.org/?probe=0a7c1705c9) | May 27, 2022 |
| Dell          | XPS 15 9570                 | [93d1ebbb72](https://linux-hardware.org/?probe=93d1ebbb72) | May 27, 2022 |
| Acer          | Aspire 7750G                | [d059ef8864](https://linux-hardware.org/?probe=d059ef8864) | May 26, 2022 |
| MSI           | GP62MVR 7RF                 | [2690f91679](https://linux-hardware.org/?probe=2690f91679) | May 25, 2022 |
| Valve         | Jupiter                     | [dee0bbedd1](https://linux-hardware.org/?probe=dee0bbedd1) | May 25, 2022 |
| Acer          | TravelMate 8372             | [fda4340056](https://linux-hardware.org/?probe=fda4340056) | May 25, 2022 |
| Lenovo        | ThinkPad W520 428223G       | [5672a27a7e](https://linux-hardware.org/?probe=5672a27a7e) | May 24, 2022 |
| Notebook      | NL5xRU                      | [fa1c36e965](https://linux-hardware.org/?probe=fa1c36e965) | May 23, 2022 |
| Dell          | XPS 13 9310                 | [a76a3417d7](https://linux-hardware.org/?probe=a76a3417d7) | May 23, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [952fd6afe9](https://linux-hardware.org/?probe=952fd6afe9) | May 22, 2022 |
| Lenovo        | ThinkPad Edge 03193TG       | [1ef9886070](https://linux-hardware.org/?probe=1ef9886070) | May 22, 2022 |
| Acer          | Aspire E5-573               | [e31114a6b2](https://linux-hardware.org/?probe=e31114a6b2) | May 21, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [086fceea4f](https://linux-hardware.org/?probe=086fceea4f) | May 19, 2022 |
| Dell          | XPS 15 9560                 | [d1575ec23a](https://linux-hardware.org/?probe=d1575ec23a) | May 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [124aa63eaf](https://linux-hardware.org/?probe=124aa63eaf) | May 17, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [e0697c999e](https://linux-hardware.org/?probe=e0697c999e) | May 17, 2022 |
| ASUSTek       | UL30A                       | [c121dd37ba](https://linux-hardware.org/?probe=c121dd37ba) | May 16, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [a32c82c654](https://linux-hardware.org/?probe=a32c82c654) | May 16, 2022 |
| Packard Be... | EasyNote LE69KB             | [71c0982b04](https://linux-hardware.org/?probe=71c0982b04) | May 15, 2022 |
| Dell          | Precision 3551              | [8685d59ac6](https://linux-hardware.org/?probe=8685d59ac6) | May 14, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [4fe9787a82](https://linux-hardware.org/?probe=4fe9787a82) | May 14, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [5dea5cd6ff](https://linux-hardware.org/?probe=5dea5cd6ff) | May 14, 2022 |
| Dell          | G3 3779                     | [75a0c428dd](https://linux-hardware.org/?probe=75a0c428dd) | May 13, 2022 |
| HP            | ZBook Studio G5             | [32358d7f08](https://linux-hardware.org/?probe=32358d7f08) | May 13, 2022 |
| HONOR         | BOHK-WAX9X                  | [e6c4aaa3d8](https://linux-hardware.org/?probe=e6c4aaa3d8) | May 12, 2022 |
| Dell          | Inspiron 1525               | [a9e9868b12](https://linux-hardware.org/?probe=a9e9868b12) | May 12, 2022 |
| HP            | ZBook 15 G6                 | [a4ce7187a6](https://linux-hardware.org/?probe=a4ce7187a6) | May 12, 2022 |
| Acer          | Swift SF514-55T             | [02cae91736](https://linux-hardware.org/?probe=02cae91736) | May 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [cbced4dcff](https://linux-hardware.org/?probe=cbced4dcff) | May 11, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [a63f7cf593](https://linux-hardware.org/?probe=a63f7cf593) | May 10, 2022 |
| HP            | ProBook x360 11 G1 EE       | [cfe7a62390](https://linux-hardware.org/?probe=cfe7a62390) | May 08, 2022 |
| Panasonic     | CF-AX2LDCZMF                | [0eb2c8ff07](https://linux-hardware.org/?probe=0eb2c8ff07) | May 08, 2022 |
| MSI           | GS63 7RD                    | [eff12e3973](https://linux-hardware.org/?probe=eff12e3973) | May 08, 2022 |
| Dell          | Latitude 3120               | [0da044ae6c](https://linux-hardware.org/?probe=0da044ae6c) | May 06, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [ef836a5eca](https://linux-hardware.org/?probe=ef836a5eca) | May 06, 2022 |
| ASUSTek       | UX430UAR                    | [6d471de246](https://linux-hardware.org/?probe=6d471de246) | May 05, 2022 |
| ASUSTek       | UX430UAR                    | [4aea04443a](https://linux-hardware.org/?probe=4aea04443a) | May 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [8919eebaa3](https://linux-hardware.org/?probe=8919eebaa3) | May 05, 2022 |
| HP            | ProBook 6560b               | [10ed31948a](https://linux-hardware.org/?probe=10ed31948a) | May 04, 2022 |
| Dell          | Latitude 3520               | [586dc3475e](https://linux-hardware.org/?probe=586dc3475e) | May 04, 2022 |
| Lenovo        | ThinkPad X240 20AMS1S800    | [a00b8586b6](https://linux-hardware.org/?probe=a00b8586b6) | May 03, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [2cf6d0c3f9](https://linux-hardware.org/?probe=2cf6d0c3f9) | May 02, 2022 |
| Dell          | Latitude 3310               | [2b74207996](https://linux-hardware.org/?probe=2b74207996) | May 02, 2022 |
| Dell          | Latitude E6510              | [916f405c55](https://linux-hardware.org/?probe=916f405c55) | May 02, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Netherlands/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 297       | 13.49%  |
| Ubuntu 18.04                 | 156       | 7.09%   |
| Ubuntu 22.04                 | 119       | 5.41%   |
| OpenMandriva 4.3             | 84        | 3.82%   |
| Debian 11                    | 53        | 2.41%   |
| Zorin 16                     | 44        | 2%      |
| Linux Mint 20.3              | 41        | 1.86%   |
| Arch                         | 38        | 1.73%   |
| Fedora 34                    | 37        | 1.68%   |
| openSUSE Tumbleweed-XXXXXXXX | 35        | 1.59%   |
| Linux Mint 20.2              | 32        | 1.45%   |
| Fedora 36                    | 32        | 1.45%   |
| Manjaro                      | 31        | 1.41%   |
| Arch Rolling                 | 31        | 1.41%   |
| Xubuntu 20.04                | 29        | 1.32%   |
| Ubuntu 21.10                 | 28        | 1.27%   |
| Fedora 37                    | 28        | 1.27%   |
| Linux Mint 21.1              | 27        | 1.23%   |
| Pop!_OS 22.04                | 26        | 1.18%   |
| KDE neon 20.04               | 26        | 1.18%   |
| Fedora 31                    | 26        | 1.18%   |
| Ubuntu 21.04                 | 25        | 1.14%   |
| Linux Mint 20.1              | 25        | 1.14%   |
| Fedora 35                    | 25        | 1.14%   |
| Pop!_OS 20.10                | 24        | 1.09%   |
| Ubuntu 20.10                 | 23        | 1.04%   |
| Pop!_OS 21.04                | 23        | 1.04%   |
| Fedora 33                    | 23        | 1.04%   |
| Fedora 32                    | 22        | 1%      |
| OpenMandriva 4.2             | 21        | 0.95%   |
| Linux Mint 19.3              | 21        | 0.95%   |
| Zorin 15                     | 20        | 0.91%   |
| Pop!_OS 20.04                | 20        | 0.91%   |
| OpenMandriva 23.01           | 20        | 0.91%   |
| Ubuntu 22.10                 | 19        | 0.86%   |
| Ubuntu 19.04                 | 19        | 0.86%   |
| Linux Mint 21                | 19        | 0.86%   |
| Linux Mint 20                | 19        | 0.86%   |
| Ubuntu 19.10                 | 18        | 0.82%   |
| Kubuntu 20.04                | 18        | 0.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 700       | 33.46%  |
| Fedora        | 194       | 9.27%   |
| Linux Mint    | 188       | 8.99%   |
| OpenMandriva  | 145       | 6.93%   |
| Pop!_OS       | 100       | 4.78%   |
| Manjaro       | 93        | 4.45%   |
| Debian        | 82        | 3.92%   |
| Zorin         | 69        | 3.3%    |
| Arch          | 68        | 3.25%   |
| Xubuntu       | 49        | 2.34%   |
| openSUSE      | 44        | 2.1%    |
| Kubuntu       | 43        | 2.06%   |
| KDE neon      | 36        | 1.72%   |
| SteamOS       | 19        | 0.91%   |
| Kali          | 19        | 0.91%   |
| Gentoo        | 19        | 0.91%   |
| EndeavourOS   | 19        | 0.91%   |
| Elementary    | 18        | 0.86%   |
| ArcoLinux     | 18        | 0.86%   |
| Lubuntu       | 16        | 0.76%   |
| Clear Linux   | 12        | 0.57%   |
| Ubuntu MATE   | 11        | 0.53%   |
| Parrot        | 11        | 0.53%   |
| Ubuntu Unity  | 9         | 0.43%   |
| Ubuntu Budgie | 9         | 0.43%   |
| ROSA          | 9         | 0.43%   |
| Peppermint    | 9         | 0.43%   |
| MX            | 9         | 0.43%   |
| LMDE          | 7         | 0.33%   |
| Endless       | 7         | 0.33%   |
| Solus         | 5         | 0.24%   |
| Garuda Linux  | 5         | 0.24%   |
| RHEL          | 3         | 0.14%   |
| Oracle Linux  | 3         | 0.14%   |
| NixOS         | 3         | 0.14%   |
| Chrome OS     | 3         | 0.14%   |
| CentOS        | 3         | 0.14%   |
| BlackPanther  | 3         | 0.14%   |
| Artix         | 3         | 0.14%   |
| antiX         | 3         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 84        | 3.46%   |
| 5.4.0-42-generic         | 30        | 1.24%   |
| 5.15.0-58-generic        | 22        | 0.91%   |
| 5.15.0-56-generic        | 22        | 0.91%   |
| 5.10.14-desktop-1omv4002 | 21        | 0.86%   |
| 5.4.0-58-generic         | 20        | 0.82%   |
| 5.15.0-46-generic        | 18        | 0.74%   |
| 5.11.0-38-generic        | 18        | 0.74%   |
| 5.8.0-50-generic         | 17        | 0.7%    |
| 5.4.0-48-generic         | 17        | 0.7%    |
| 5.15.0-43-generic        | 17        | 0.7%    |
| 5.8.0-43-generic         | 16        | 0.66%   |
| 5.4.0-26-generic         | 15        | 0.62%   |
| 5.13.0-28-generic        | 15        | 0.62%   |
| 6.1.1-desktop-1omv2290   | 14        | 0.58%   |
| 5.4.0-29-generic         | 14        | 0.58%   |
| 5.15.0-60-generic        | 14        | 0.58%   |
| 5.8.0-53-generic         | 13        | 0.54%   |
| 5.4.0-77-generic         | 13        | 0.54%   |
| 5.4.0-52-generic         | 13        | 0.54%   |
| 5.4.0-33-generic         | 13        | 0.54%   |
| 5.15.0-52-generic        | 13        | 0.54%   |
| 5.15.0-48-generic        | 13        | 0.54%   |
| 5.11.0-27-generic        | 13        | 0.54%   |
| 6.2.6-desktop-1omv2390   | 12        | 0.49%   |
| 5.8.0-7630-generic       | 12        | 0.49%   |
| 5.4.0-74-generic         | 12        | 0.49%   |
| 5.4.0-45-generic         | 12        | 0.49%   |
| 5.3.0-46-generic         | 12        | 0.49%   |
| 5.19.0-35-generic        | 12        | 0.49%   |
| 5.13.0-39-generic        | 11        | 0.45%   |
| 5.4.0-89-generic         | 10        | 0.41%   |
| 5.4.0-7634-generic       | 10        | 0.41%   |
| 5.4.0-65-generic         | 10        | 0.41%   |
| 5.4.0-37-generic         | 10        | 0.41%   |
| 5.15.0-41-generic        | 10        | 0.41%   |
| 5.13.0-valve36-1-neptune | 10        | 0.41%   |
| 5.8.0-48-generic         | 9         | 0.37%   |
| 5.4.0-91-generic         | 9         | 0.37%   |
| 5.4.0-47-generic         | 9         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 360       | 15.83%  |
| 5.15.0  | 198       | 8.71%   |
| 5.8.0   | 137       | 6.02%   |
| 4.15.0  | 122       | 5.36%   |
| 5.11.0  | 120       | 5.28%   |
| 5.13.0  | 118       | 5.19%   |
| 5.16.7  | 85        | 3.74%   |
| 5.3.0   | 70        | 3.08%   |
| 5.10.0  | 69        | 3.03%   |
| 5.19.0  | 67        | 2.95%   |
| 5.0.0   | 53        | 2.33%   |
| 4.18.0  | 39        | 1.72%   |
| 5.10.14 | 22        | 0.97%   |
| 4.19.0  | 19        | 0.84%   |
| 6.2.6   | 16        | 0.7%    |
| 6.1.1   | 16        | 0.7%    |
| 5.14.0  | 16        | 0.7%    |
| 6.2.0   | 11        | 0.48%   |
| 6.1.0   | 11        | 0.48%   |
| 5.6.0   | 11        | 0.48%   |
| 6.0.0   | 9         | 0.4%    |
| 5.9.16  | 9         | 0.4%    |
| 6.3.0   | 8         | 0.35%   |
| 6.0.6   | 8         | 0.35%   |
| 5.17.1  | 8         | 0.35%   |
| 6.2.10  | 7         | 0.31%   |
| 6.1.4   | 7         | 0.31%   |
| 5.4.8   | 7         | 0.31%   |
| 5.18.0  | 7         | 0.31%   |
| 5.17.0  | 7         | 0.31%   |
| 4.4.0   | 7         | 0.31%   |
| 6.2.9   | 6         | 0.26%   |
| 6.1.11  | 6         | 0.26%   |
| 5.17.4  | 6         | 0.26%   |
| 5.16.0  | 6         | 0.26%   |
| 5.15.78 | 6         | 0.26%   |
| 5.11.12 | 6         | 0.26%   |
| 4.9.0   | 6         | 0.26%   |
| 6.3.4   | 5         | 0.22%   |
| 6.2.8   | 5         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 398       | 17.72%  |
| 5.15    | 255       | 11.35%  |
| 5.8     | 167       | 7.44%   |
| 5.11    | 150       | 6.68%   |
| 5.13    | 143       | 6.37%   |
| 4.15    | 122       | 5.43%   |
| 5.10    | 120       | 5.34%   |
| 5.16    | 115       | 5.12%   |
| 5.19    | 90        | 4.01%   |
| 5.3     | 88        | 3.92%   |
| 6.1     | 61        | 2.72%   |
| 6.2     | 60        | 2.67%   |
| 5.0     | 56        | 2.49%   |
| 6.0     | 48        | 2.14%   |
| 5.17    | 46        | 2.05%   |
| 4.18    | 44        | 1.96%   |
| 5.14    | 43        | 1.91%   |
| 5.9     | 32        | 1.42%   |
| 5.18    | 31        | 1.38%   |
| 5.6     | 30        | 1.34%   |
| 5.7     | 23        | 1.02%   |
| 5.12    | 23        | 1.02%   |
| 4.19    | 23        | 1.02%   |
| 6.3     | 21        | 0.93%   |
| 5.5     | 15        | 0.67%   |
| 4.9     | 11        | 0.49%   |
| 4.4     | 8         | 0.36%   |
| 5.2     | 6         | 0.27%   |
| 4.16    | 3         | 0.13%   |
| 4.12    | 3         | 0.13%   |
| 4.10    | 3         | 0.13%   |
| 4.20    | 2         | 0.09%   |
| 5.17.1  | 1         | 0.04%   |
| 5.1     | 1         | 0.04%   |
| 4.7     | 1         | 0.04%   |
| 4.17    | 1         | 0.04%   |
| 4.14    | 1         | 0.04%   |
| 3.16    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1968      | 96.99%  |
| i686    | 60        | 2.96%   |
| aarch64 | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 957       | 45.29%  |
| KDE5             | 364       | 17.23%  |
| Unknown          | 258       | 12.21%  |
| XFCE             | 155       | 7.34%   |
| X-Cinnamon       | 144       | 6.81%   |
| KDE              | 50        | 2.37%   |
| MATE             | 44        | 2.08%   |
| Cinnamon         | 21        | 0.99%   |
| Pantheon         | 18        | 0.85%   |
| LXQt             | 15        | 0.71%   |
| Budgie           | 14        | 0.66%   |
| LXDE             | 13        | 0.62%   |
| i3               | 11        | 0.52%   |
| Unity            | 9         | 0.43%   |
| GNOME Flashback  | 6         | 0.28%   |
| KDE4             | 5         | 0.24%   |
| icewm            | 5         | 0.24%   |
| sway             | 4         | 0.19%   |
| qtile            | 3         | 0.14%   |
| Deepin           | 3         | 0.14%   |
| GNOME Classic    | 2         | 0.09%   |
| awesome          | 2         | 0.09%   |
| xmonad           | 1         | 0.05%   |
| Trinity          | 1         | 0.05%   |
| openbox          | 1         | 0.05%   |
| lightdm-xsession | 1         | 0.05%   |
| herbstluftwm     | 1         | 0.05%   |
| fluxbox          | 1         | 0.05%   |
| enlightenment    | 1         | 0.05%   |
| DWM              | 1         | 0.05%   |
| Core             | 1         | 0.05%   |
| bspwm            | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1538      | 74.01%  |
| Wayland | 381       | 18.33%  |
| Unknown | 136       | 6.54%   |
| Tty     | 23        | 1.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1030      | 49.12%  |
| GDM     | 289       | 13.78%  |
| SDDM    | 285       | 13.59%  |
| GDM3    | 232       | 11.06%  |
| LightDM | 200       | 9.54%   |
| TDM     | 47        | 2.24%   |
| KDM     | 5         | 0.24%   |
| XDM     | 4         | 0.19%   |
| GREETD  | 2         | 0.1%    |
| NODM    | 1         | 0.05%   |
| Ly      | 1         | 0.05%   |
| LXDM    | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 1035      | 49.69%  |
| nl_NL       | 537       | 25.78%  |
| Unknown     | 227       | 10.9%   |
| en_GB       | 98        | 4.7%    |
| pl_PL       | 23        | 1.1%    |
| C           | 23        | 1.1%    |
| ru_RU       | 19        | 0.91%   |
| de_DE       | 19        | 0.91%   |
| POSIX       | 10        | 0.48%   |
| en_NL       | 9         | 0.43%   |
| fr_FR       | 6         | 0.29%   |
| en_IN       | 6         | 0.29%   |
| en_IE       | 6         | 0.29%   |
| it_IT       | 4         | 0.19%   |
| es_MX       | 4         | 0.19%   |
| en_DK       | 4         | 0.19%   |
| pt_PT       | 3         | 0.14%   |
| nl_BE       | 3         | 0.14%   |
| nb_NO       | 3         | 0.14%   |
| es_ES       | 3         | 0.14%   |
| en_CA       | 3         | 0.14%   |
| zh_CN       | 2         | 0.1%    |
| uk_UA       | 2         | 0.1%    |
| sv_SE       | 2         | 0.1%    |
| sk_SK       | 2         | 0.1%    |
| hu_HU       | 2         | 0.1%    |
| fr_BE       | 2         | 0.1%    |
| en_ZA       | 2         | 0.1%    |
| en_US.utf-8 | 2         | 0.1%    |
| en_SG       | 2         | 0.1%    |
| cs_CZ       | 2         | 0.1%    |
| tr_TR       | 1         | 0.05%   |
| ru_UA       | 1         | 0.05%   |
| ro_RO       | 1         | 0.05%   |
| nl_AW       | 1         | 0.05%   |
| lt_LT       | 1         | 0.05%   |
| hr_HR       | 1         | 0.05%   |
| fi_FI       | 1         | 0.05%   |
| es_CR       | 1         | 0.05%   |
| es_CO       | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1142      | 55.09%  |
| BIOS | 931       | 44.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1572      | 75.76%  |
| Btrfs   | 212       | 10.22%  |
| Overlay | 163       | 7.86%   |
| Unknown | 62        | 2.99%   |
| Xfs     | 27        | 1.3%    |
| Tmpfs   | 13        | 0.63%   |
| Zfs     | 12        | 0.58%   |
| F2fs    | 6         | 0.29%   |
| Ext2    | 3         | 0.14%   |
| Ext3    | 2         | 0.1%    |
| Aufs    | 2         | 0.1%    |
| Jfs     | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1121      | 54.15%  |
| GPT     | 786       | 37.97%  |
| MBR     | 163       | 7.87%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1809      | 87.6%   |
| Yes       | 256       | 12.4%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1506      | 73.46%  |
| Yes       | 544       | 26.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Hewlett-Packard      | 409       | 20.19%  |
| Dell                 | 397       | 19.6%   |
| Lenovo               | 354       | 17.47%  |
| ASUSTek Computer     | 188       | 9.28%   |
| Acer                 | 184       | 9.08%   |
| Apple                | 75        | 3.7%    |
| Toshiba              | 55        | 2.71%   |
| Notebook             | 51        | 2.52%   |
| MSI                  | 42        | 2.07%   |
| Medion               | 25        | 1.23%   |
| Samsung Electronics  | 22        | 1.09%   |
| Packard Bell         | 20        | 0.99%   |
| Valve                | 18        | 0.89%   |
| Sony                 | 16        | 0.79%   |
| Google               | 15        | 0.74%   |
| Fujitsu              | 14        | 0.69%   |
| HUAWEI               | 13        | 0.64%   |
| Alienware            | 9         | 0.44%   |
| Unknown              | 9         | 0.44%   |
| Fujitsu Siemens      | 7         | 0.35%   |
| TUXEDO               | 6         | 0.3%    |
| Timi                 | 6         | 0.3%    |
| Insyde               | 6         | 0.3%    |
| PC Specialist        | 5         | 0.25%   |
| Gigabyte Technology  | 5         | 0.25%   |
| System76             | 4         | 0.2%    |
| SLIMBOOK             | 4         | 0.2%    |
| Chuwi                | 4         | 0.2%    |
| TrekStor             | 3         | 0.15%   |
| Intel                | 3         | 0.15%   |
| Hampoo               | 3         | 0.15%   |
| Toxic                | 2         | 0.1%    |
| TongFang             | 2         | 0.1%    |
| Standard             | 2         | 0.1%    |
| SKIKK                | 2         | 0.1%    |
| Schenker             | 2         | 0.1%    |
| Panasonic            | 2         | 0.1%    |
| Intel Client Systems | 2         | 0.1%    |
| ilife                | 2         | 0.1%    |
| Getac                | 2         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Dell Latitude 3310                  | 31        | 1.53%   |
| Valve Jupiter                       | 18        | 0.89%   |
| Unknown                             | 18        | 0.89%   |
| Dell XPS 15 7590                    | 12        | 0.59%   |
| HP Notebook                         | 10        | 0.49%   |
| HP Pavilion dv7                     | 9         | 0.44%   |
| Dell XPS 15 9560                    | 9         | 0.44%   |
| Apple MacBookPro9,2                 | 9         | 0.44%   |
| HP ZBook Studio G5                  | 8         | 0.39%   |
| HP Pavilion g7                      | 8         | 0.39%   |
| Dell Latitude 3300                  | 8         | 0.39%   |
| HP Pavilion Laptop 15-cw1xxx        | 7         | 0.35%   |
| HP Pavilion Gaming Laptop 15-cx0xxx | 7         | 0.35%   |
| HP Pavilion g6                      | 7         | 0.35%   |
| Dell XPS 13 9310                    | 7         | 0.35%   |
| Dell Latitude E6410                 | 7         | 0.35%   |
| HP ProBook 6570b                    | 6         | 0.3%    |
| HP Pavilion dv6                     | 6         | 0.3%    |
| HP EliteBook 8570w                  | 6         | 0.3%    |
| HP EliteBook 8460p                  | 6         | 0.3%    |
| Dell XPS 15 9570                    | 6         | 0.3%    |
| Dell XPS 15 9550                    | 6         | 0.3%    |
| Dell XPS 15 9500                    | 6         | 0.3%    |
| Dell XPS 13 9360                    | 6         | 0.3%    |
| Dell Latitude E6320                 | 6         | 0.3%    |
| Dell Latitude D630                  | 6         | 0.3%    |
| Dell Latitude 3189                  | 6         | 0.3%    |
| Apple MacBookPro12,1                | 6         | 0.3%    |
| Lenovo Yoga Slim 7 13ACN5 82CY      | 5         | 0.25%   |
| Lenovo ThinkBook 15 G2 ITL 20VE     | 5         | 0.25%   |
| Lenovo IdeaPad 5 15ARE05 81YQ       | 5         | 0.25%   |
| HP ProBook 650 G1                   | 5         | 0.25%   |
| HP Laptop 17-cp0xxx                 | 5         | 0.25%   |
| HP EliteBook 850 G3                 | 5         | 0.25%   |
| HP EliteBook 8470p                  | 5         | 0.25%   |
| HP EliteBook 840 G1                 | 5         | 0.25%   |
| Dell XPS 15 9510                    | 5         | 0.25%   |
| Dell Latitude E7450                 | 5         | 0.25%   |
| Dell Latitude E6520                 | 5         | 0.25%   |
| Dell Latitude E6510                 | 5         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 213       | 10.51%  |
| Lenovo ThinkPad       | 206       | 10.17%  |
| Acer Aspire           | 132       | 6.52%   |
| HP EliteBook          | 98        | 4.84%   |
| HP Pavilion           | 89        | 4.39%   |
| Dell XPS              | 88        | 4.34%   |
| Lenovo IdeaPad        | 67        | 3.31%   |
| HP ProBook            | 66        | 3.26%   |
| Toshiba Satellite     | 51        | 2.52%   |
| Dell Inspiron         | 39        | 1.92%   |
| HP ZBook              | 35        | 1.73%   |
| HP Compaq             | 34        | 1.68%   |
| Dell Precision        | 25        | 1.23%   |
| Lenovo Legion         | 24        | 1.18%   |
| HP Laptop             | 21        | 1.04%   |
| Packard Bell EasyNote | 20        | 0.99%   |
| ASUS VivoBook         | 20        | 0.99%   |
| Valve Jupiter         | 18        | 0.89%   |
| Unknown               | 18        | 0.89%   |
| Lenovo ThinkBook      | 15        | 0.74%   |
| Acer Swift            | 14        | 0.69%   |
| Lenovo Yoga           | 13        | 0.64%   |
| Fujitsu LIFEBOOK      | 13        | 0.64%   |
| Acer TravelMate       | 13        | 0.64%   |
| ASUS ZenBook          | 12        | 0.59%   |
| ASUS ROG              | 11        | 0.54%   |
| HP Notebook           | 10        | 0.49%   |
| Apple MacBookPro9     | 10        | 0.49%   |
| Apple MacBookPro8     | 10        | 0.49%   |
| Apple MacBookPro11    | 10        | 0.49%   |
| HP ENVY               | 9         | 0.44%   |
| Dell System           | 9         | 0.44%   |
| HP OMEN               | 8         | 0.39%   |
| Dell Vostro           | 7         | 0.35%   |
| Dell Studio           | 7         | 0.35%   |
| Acer Nitro            | 7         | 0.35%   |
| Apple MacBookPro5     | 6         | 0.3%    |
| Apple MacBookPro12    | 6         | 0.3%    |
| HP 250                | 5         | 0.25%   |
| ASUS K52F             | 5         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 252       | 12.44%  |
| 2018    | 169       | 8.34%   |
| 2020    | 163       | 8.05%   |
| 2012    | 153       | 7.55%   |
| 2021    | 150       | 7.4%    |
| 2011    | 143       | 7.06%   |
| 2017    | 125       | 6.17%   |
| 2013    | 122       | 6.02%   |
| 2015    | 120       | 5.92%   |
| 2016    | 108       | 5.33%   |
| 2010    | 107       | 5.28%   |
| 2014    | 97        | 4.79%   |
| 2008    | 82        | 4.05%   |
| 2022    | 80        | 3.95%   |
| 2009    | 73        | 3.6%    |
| 2007    | 56        | 2.76%   |
| 2006    | 17        | 0.84%   |
| 2023    | 3         | 0.15%   |
| 2005    | 3         | 0.15%   |
| Unknown | 2         | 0.1%    |
| 2004    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2026      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1812      | 88.82%  |
| Enabled  | 228       | 11.18%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2005      | 98.96%  |
| Yes  | 21        | 1.04%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 542       | 26.43%  |
| 3.01-4.0    | 418       | 20.38%  |
| 16.01-24.0  | 369       | 17.99%  |
| 8.01-16.0   | 329       | 16.04%  |
| 32.01-64.0  | 169       | 8.24%   |
| 1.01-2.0    | 89        | 4.34%   |
| 2.01-3.0    | 53        | 2.58%   |
| 24.01-32.0  | 34        | 1.66%   |
| 64.01-256.0 | 29        | 1.41%   |
| 0.51-1.0    | 19        | 0.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 787       | 35.2%   |
| 2.01-3.0   | 554       | 24.78%  |
| 4.01-8.0   | 314       | 14.04%  |
| 3.01-4.0   | 290       | 12.97%  |
| 0.51-1.0   | 148       | 6.62%   |
| 8.01-16.0  | 111       | 4.96%   |
| 16.01-24.0 | 15        | 0.67%   |
| 0.01-0.5   | 13        | 0.58%   |
| 24.01-32.0 | 3         | 0.13%   |
| 32.01-64.0 | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1468      | 71.19%  |
| 2      | 490       | 23.76%  |
| 3      | 62        | 3.01%   |
| 0      | 33        | 1.6%    |
| 4      | 7         | 0.34%   |
| 7      | 1         | 0.05%   |
| 5      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1349      | 66.22%  |
| Yes       | 688       | 33.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1652      | 81.22%  |
| No        | 382       | 18.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1975      | 97.39%  |
| No        | 53        | 2.61%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1566      | 76.09%  |
| No        | 492       | 23.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Netherlands | 2026      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Amsterdam              | 396       | 18.44%  |
| The Hague              | 112       | 5.22%   |
| Rotterdam              | 71        | 3.31%   |
| Utrecht                | 59        | 2.75%   |
| Schagen                | 58        | 2.7%    |
| Delft                  | 54        | 2.52%   |
| Haarlem                | 46        | 2.14%   |
| Eindhoven              | 37        | 1.72%   |
| Groningen              | 34        | 1.58%   |
| Almere Stad            | 28        | 1.3%    |
| Naaldwijk              | 27        | 1.26%   |
| Tilburg                | 25        | 1.16%   |
| Amersfoort             | 25        | 1.16%   |
| Enschede               | 23        | 1.07%   |
| Leiden                 | 19        | 0.88%   |
| Apeldoorn              | 19        | 0.88%   |
| Zoetermeer             | 18        | 0.84%   |
| Nijmegen               | 16        | 0.75%   |
| Breda                  | 16        | 0.75%   |
| Heerlen                | 15        | 0.7%    |
| Zwolle                 | 14        | 0.65%   |
| Arnhem                 | 14        | 0.65%   |
| Zeist                  | 13        | 0.61%   |
| Capelle aan den IJssel | 13        | 0.61%   |
| Amstelveen             | 13        | 0.61%   |
| Alkmaar                | 13        | 0.61%   |
| Maastricht             | 12        | 0.56%   |
| Dordrecht              | 12        | 0.56%   |
| Almelo                 | 12        | 0.56%   |
| 's-Hertogenbosch       | 11        | 0.51%   |
| Rijswijk               | 10        | 0.47%   |
| Oss                    | 10        | 0.47%   |
| Meppel                 | 10        | 0.47%   |
| Hilversum              | 10        | 0.47%   |
| Nieuwegein             | 9         | 0.42%   |
| Leeuwarden             | 9         | 0.42%   |
| Gouda                  | 9         | 0.42%   |
| Dronten                | 9         | 0.42%   |
| Diemen                 | 9         | 0.42%   |
| Weert                  | 8         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 562       | 819    | 22.58%  |
| WDC                         | 233       | 287    | 9.36%   |
| Seagate                     | 212       | 269    | 8.52%   |
| Toshiba                     | 183       | 223    | 7.35%   |
| Unknown                     | 143       | 168    | 5.75%   |
| SK hynix                    | 140       | 171    | 5.62%   |
| Sandisk                     | 138       | 166    | 5.54%   |
| Kingston                    | 137       | 172    | 5.5%    |
| Crucial                     | 89        | 105    | 3.58%   |
| Hitachi                     | 84        | 96     | 3.37%   |
| Intel                       | 80        | 98     | 3.21%   |
| HGST                        | 67        | 84     | 2.69%   |
| Micron Technology           | 61        | 71     | 2.45%   |
| Apple                       | 42        | 58     | 1.69%   |
| LITEON                      | 32        | 42     | 1.29%   |
| KIOXIA                      | 32        | 33     | 1.29%   |
| A-DATA Technology           | 22        | 24     | 0.88%   |
| LITEONIT                    | 19        | 21     | 0.76%   |
| Fujitsu                     | 19        | 21     | 0.76%   |
| Phison                      | 12        | 17     | 0.48%   |
| China                       | 12        | 22     | 0.48%   |
| OCZ                         | 10        | 13     | 0.4%    |
| PNY                         | 8         | 9      | 0.32%   |
| Intenso                     | 8         | 8      | 0.32%   |
| Unknown                     | 8         | 9      | 0.32%   |
| Kingston Technology Company | 7         | 9      | 0.28%   |
| Transcend                   | 6         | 7      | 0.24%   |
| O2 Micro                    | 6         | 6      | 0.24%   |
| KingFast                    | 6         | 9      | 0.24%   |
| Corsair                     | 6         | 6      | 0.24%   |
| SSSTC                       | 5         | 6      | 0.2%    |
| SPCC                        | 5         | 5      | 0.2%    |
| Phison Electronics          | 5         | 7      | 0.2%    |
| GOODRAM                     | 5         | 5      | 0.2%    |
| ASMT                        | 5         | 5      | 0.2%    |
| Gigabyte Technology         | 4         | 5      | 0.16%   |
| Team                        | 3         | 5      | 0.12%   |
| Realtek                     | 3         | 3      | 0.12%   |
| Netac                       | 3         | 3      | 0.12%   |
| KingSpec                    | 3         | 3      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 33        | 1.26%   |
| Unknown MMC Card  32GB                              | 30        | 1.15%   |
| Samsung SSD 850 EVO 250GB                           | 28        | 1.07%   |
| HGST HTS721010A9E630 1TB                            | 24        | 0.92%   |
| Seagate ST1000LM035-1RK172 1TB                      | 23        | 0.88%   |
| Seagate ST9500325AS 500GB                           | 20        | 0.76%   |
| Kingston SA400S37120G 120GB SSD                     | 20        | 0.76%   |
| Samsung SSD 850 EVO 500GB                           | 19        | 0.73%   |
| Toshiba MQ01ABF050 500GB                            | 18        | 0.69%   |
| Samsung SSD 860 EVO 500GB                           | 18        | 0.69%   |
| Samsung NVMe SSD Drive 1TB                          | 18        | 0.69%   |
| Samsung NVMe SSD Drive 256GB                        | 17        | 0.65%   |
| Toshiba MQ01ABD100 1TB                              | 16        | 0.61%   |
| SanDisk NVMe SSD Drive 512GB                        | 16        | 0.61%   |
| Samsung NVMe SSD Drive 512GB                        | 16        | 0.61%   |
| Samsung NVMe SSD Drive 500GB                        | 15        | 0.57%   |
| Samsung NVMe SSD Drive 1024GB                       | 15        | 0.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 15        | 0.57%   |
| Kingston SA400S37240G 240GB SSD                     | 15        | 0.57%   |
| Unknown MMC Card  64GB                              | 14        | 0.53%   |
| Toshiba NVMe SSD Drive 512GB                        | 14        | 0.53%   |
| Samsung SSD 840 EVO 250GB                           | 13        | 0.5%    |
| HGST HTS725050A7E630 500GB                          | 13        | 0.5%    |
| Toshiba NVMe SSD Drive 256GB                        | 12        | 0.46%   |
| SK hynix NVMe SSD Drive 512GB                       | 12        | 0.46%   |
| Seagate ST500LT012-1DG142 500GB                     | 12        | 0.46%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 12        | 0.46%   |
| Samsung SSD 980 1TB                                 | 12        | 0.46%   |
| Crucial CT240BX500SSD1 240GB                        | 12        | 0.46%   |
| Seagate Expansion 1TB                               | 11        | 0.42%   |
| SanDisk NVMe SSD Drive 256GB                        | 11        | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB                        | 11        | 0.42%   |
| Samsung SSD 860 EVO 1TB                             | 11        | 0.42%   |
| Kingston SV300S37A120G 120GB SSD                    | 11        | 0.42%   |
| HGST HTS541010A9E680 1TB                            | 11        | 0.42%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 10        | 0.38%   |
| Seagate ST1000LM049-2GH172 1TB                      | 10        | 0.38%   |
| Samsung SSD 970 EVO 1TB                             | 10        | 0.38%   |
| Crucial CT500MX500SSD1 500GB                        | 10        | 0.38%   |
| Crucial CT1000MX500SSD1 1TB                         | 10        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 209       | 264    | 32.01%  |
| WDC                 | 147       | 173    | 22.51%  |
| Toshiba             | 102       | 129    | 15.62%  |
| Hitachi             | 84        | 96     | 12.86%  |
| HGST                | 67        | 84     | 10.26%  |
| Fujitsu             | 19        | 21     | 2.91%   |
| Samsung Electronics | 13        | 15     | 1.99%   |
| Apple               | 3         | 4      | 0.46%   |
| Unknown             | 2         | 2      | 0.31%   |
| External            | 2         | 4      | 0.31%   |
| SSK                 | 1         | 1      | 0.15%   |
| KESU                | 1         | 1      | 0.15%   |
| Intenso             | 1         | 1      | 0.15%   |
| HGST HTS            | 1         | 1      | 0.15%   |
| ASMedia             | 1         | 3      | 0.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 276       | 387    | 31.08%  |
| Kingston            | 103       | 127    | 11.6%   |
| Crucial             | 85        | 101    | 9.57%   |
| SanDisk             | 82        | 92     | 9.23%   |
| WDC                 | 33        | 51     | 3.72%   |
| SK hynix            | 31        | 42     | 3.49%   |
| Intel               | 29        | 31     | 3.27%   |
| Micron Technology   | 28        | 36     | 3.15%   |
| Apple               | 28        | 34     | 3.15%   |
| LITEON              | 24        | 34     | 2.7%    |
| Toshiba             | 19        | 23     | 2.14%   |
| LITEONIT            | 19        | 21     | 2.14%   |
| A-DATA Technology   | 18        | 20     | 2.03%   |
| China               | 12        | 22     | 1.35%   |
| OCZ                 | 10        | 13     | 1.13%   |
| PNY                 | 8         | 9      | 0.9%    |
| Intenso             | 7         | 7      | 0.79%   |
| Corsair             | 6         | 6      | 0.68%   |
| Transcend           | 5         | 6      | 0.56%   |
| SPCC                | 5         | 5      | 0.56%   |
| GOODRAM             | 5         | 5      | 0.56%   |
| ASMT                | 5         | 5      | 0.56%   |
| KingFast            | 4         | 5      | 0.45%   |
| Team                | 3         | 5      | 0.34%   |
| Netac               | 3         | 3      | 0.34%   |
| KingSpec            | 3         | 3      | 0.34%   |
| Vaseky              | 2         | 2      | 0.23%   |
| Unknown             | 2         | 2      | 0.23%   |
| SSSTC               | 2         | 2      | 0.23%   |
| SABRENT             | 2         | 2      | 0.23%   |
| Patriot             | 2         | 4      | 0.23%   |
| KingDian            | 2         | 2      | 0.23%   |
| JMicron Technology  | 2         | 2      | 0.23%   |
| WDC WDS2            | 1         | 1      | 0.11%   |
| ValueTech           | 1         | 1      | 0.11%   |
| TrekStor            | 1         | 1      | 0.11%   |
| Teclast             | 1         | 2      | 0.11%   |
| StoreJet            | 1         | 1      | 0.11%   |
| Seagate             | 1         | 1      | 0.11%   |
| Reeinno             | 1         | 1      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 834       | 1137   | 34.84%  |
| NVMe    | 769       | 1042   | 32.12%  |
| HDD     | 630       | 799    | 26.32%  |
| MMC     | 147       | 171    | 6.14%   |
| Unknown | 14        | 15     | 0.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1282      | 1841   | 56.03%  |
| NVMe | 768       | 1038   | 33.57%  |
| MMC  | 147       | 171    | 6.42%   |
| SAS  | 91        | 114    | 3.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1064      | 1440   | 74.09%  |
| 0.51-1.0   | 324       | 432    | 22.56%  |
| 1.01-2.0   | 33        | 43     | 2.3%    |
| 4.01-10.0  | 6         | 8      | 0.42%   |
| 3.01-4.0   | 5         | 9      | 0.35%   |
| 2.01-3.0   | 2         | 2      | 0.14%   |
| 10.01-20.0 | 2         | 2      | 0.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 637       | 29.88%  |
| 251-500        | 493       | 23.12%  |
| 501-1000       | 269       | 12.62%  |
| 1-20           | 201       | 9.43%   |
| 51-100         | 148       | 6.94%   |
| 1001-2000      | 143       | 6.71%   |
| 21-50          | 103       | 4.83%   |
| Unknown        | 53        | 2.49%   |
| More than 3000 | 51        | 2.39%   |
| 2001-3000      | 34        | 1.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 905       | 40.95%  |
| 21-50          | 366       | 16.56%  |
| 101-250        | 283       | 12.81%  |
| 51-100         | 263       | 11.9%   |
| 251-500        | 175       | 7.92%   |
| 501-1000       | 103       | 4.66%   |
| Unknown        | 53        | 2.4%    |
| 1001-2000      | 38        | 1.72%   |
| More than 3000 | 13        | 0.59%   |
| 2001-3000      | 10        | 0.45%   |
| 0              | 1         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST9250410AS 250GB             | 3         | 3      | 3.23%   |
| HGST HTS725050A7E630 500GB            | 3         | 3      | 3.23%   |
| HGST HTS721010A9E630 1TB              | 3         | 4      | 3.23%   |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 2.15%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 2      | 2.15%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 2.15%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 2.15%   |
| Kingston SA400S37120G 120GB SSD       | 2         | 3      | 2.15%   |
| Hitachi HTS725050A7E630 500GB         | 2         | 2      | 2.15%   |
| Fujitsu MHZ2320BH G2 320GB            | 2         | 2      | 2.15%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 1.08%   |
| WDC WD7500BPVT-08HXZT3 752GB          | 1         | 1      | 1.08%   |
| WDC WD600UE-22HCT0 64GB               | 1         | 1      | 1.08%   |
| WDC WD3200BPVT-80ZEST0 320GB          | 1         | 1      | 1.08%   |
| WDC WD3200BPVT-22JJ5T0 320GB          | 1         | 1      | 1.08%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 1.08%   |
| WDC WD2500BEVT-22ZCT0 250GB           | 1         | 1      | 1.08%   |
| WDC WD1600BEVT-75A23T0 160GB          | 1         | 1      | 1.08%   |
| WDC WD1600BEVT-22A23T0 160GB          | 1         | 1      | 1.08%   |
| WDC WD10SPZX-24Z10T0 1TB              | 1         | 1      | 1.08%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 1.08%   |
| Toshiba THNSNK128GCS8 SATA 128GB SSD  | 1         | 1      | 1.08%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 1.08%   |
| Toshiba MK5061GSYN 500GB              | 1         | 1      | 1.08%   |
| Toshiba MK3265GSX 320GB               | 1         | 1      | 1.08%   |
| Toshiba MK1252GSX 120GB               | 1         | 1      | 1.08%   |
| Toshiba MK1234GSX 120GB               | 1         | 1      | 1.08%   |
| SK hynix SC401 SATA 512GB SSD         | 1         | 1      | 1.08%   |
| SK hynix SC210 mSATA 256GB SSD        | 1         | 1      | 1.08%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 1         | 1      | 1.08%   |
| Seagate ST9200420ASG 200GB            | 1         | 2      | 1.08%   |
| Seagate ST9160821A 137GB              | 1         | 1      | 1.08%   |
| Seagate ST1000LX015-1U7172 1TB        | 1         | 1      | 1.08%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 1.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 1.08%   |
| SanDisk SDSSDX240GG25 240GB           | 1         | 1      | 1.08%   |
| SanDisk SDSSDP064G 64GB               | 1         | 1      | 1.08%   |
| SanDisk SD9SN8W-256G-1006 256GB SSD   | 1         | 1      | 1.08%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD   | 1         | 1      | 1.08%   |
| SanDisk SD6SF1M128G1022I 128GB SSD    | 1         | 1      | 1.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 12        | 13     | 12.9%   |
| WDC                         | 11        | 11     | 11.83%  |
| Hitachi                     | 10        | 10     | 10.75%  |
| HGST                        | 9         | 10     | 9.68%   |
| Toshiba                     | 8         | 8      | 8.6%    |
| Kingston                    | 6         | 8      | 6.45%   |
| SK hynix                    | 5         | 5      | 5.38%   |
| SanDisk                     | 5         | 5      | 5.38%   |
| Intel                       | 4         | 4      | 4.3%    |
| Fujitsu                     | 4         | 4      | 4.3%    |
| Samsung Electronics         | 3         | 3      | 3.23%   |
| Micron Technology           | 3         | 3      | 3.23%   |
| LITEON                      | 3         | 6      | 3.23%   |
| Crucial                     | 2         | 2      | 2.15%   |
| Realtek                     | 1         | 1      | 1.08%   |
| OCZ                         | 1         | 1      | 1.08%   |
| Kingston Technology Company | 1         | 1      | 1.08%   |
| Intenso                     | 1         | 1      | 1.08%   |
| GOODRAM                     | 1         | 1      | 1.08%   |
| Corsair                     | 1         | 1      | 1.08%   |
| Apple                       | 1         | 1      | 1.08%   |
| A-DATA Technology           | 1         | 1      | 1.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 22.22%  |
| WDC                 | 10        | 10     | 18.52%  |
| Hitachi             | 10        | 10     | 18.52%  |
| HGST                | 9         | 10     | 16.67%  |
| Toshiba             | 7         | 7      | 12.96%  |
| Fujitsu             | 4         | 4      | 7.41%   |
| Samsung Electronics | 1         | 1      | 1.85%   |
| Apple               | 1         | 1      | 1.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 54        | 56     | 58.06%  |
| SSD  | 33        | 38     | 35.48%  |
| NVMe | 6         | 6      | 6.45%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Toshiba MK5065GSXN 500GB     | 1         | 1      | 50%     |
| Crucial M4-CT256M4SSD3 256GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| Crucial | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1300      | 2066   | 61%     |
| Works    | 737       | 996    | 34.58%  |
| Malfunc  | 92        | 100    | 4.32%   |
| Failed   | 2         | 2      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1383      | 58.33%  |
| Samsung Electronics              | 323       | 13.62%  |
| AMD                              | 153       | 6.45%   |
| SK hynix                         | 107       | 4.51%   |
| SanDisk                          | 105       | 4.43%   |
| Toshiba America Info Systems     | 70        | 2.95%   |
| Kingston Technology Company      | 41        | 1.73%   |
| Micron Technology                | 33        | 1.39%   |
| KIOXIA                           | 31        | 1.31%   |
| Nvidia                           | 25        | 1.05%   |
| Phison Electronics               | 19        | 0.8%    |
| Silicon Integrated Systems [SiS] | 13        | 0.55%   |
| Apple                            | 12        | 0.51%   |
| Lite-On Technology               | 11        | 0.46%   |
| O2 Micro                         | 6         | 0.25%   |
| Union Memory (Shenzhen)          | 5         | 0.21%   |
| Micron/Crucial Technology        | 5         | 0.21%   |
| Solid State Storage Technology   | 4         | 0.17%   |
| Realtek Semiconductor            | 4         | 0.17%   |
| VIA Technologies                 | 3         | 0.13%   |
| JMicron Technology               | 3         | 0.13%   |
| Silicon Motion                   | 2         | 0.08%   |
| Seagate Technology               | 2         | 0.08%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.08%   |
| ASMedia Technology               | 2         | 0.08%   |
| ADATA Technology                 | 2         | 0.08%   |
| Transcend                        | 1         | 0.04%   |
| Silicon Image                    | 1         | 0.04%   |
| Marvell Technology Group         | 1         | 0.04%   |
| Lenovo                           | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 164       | 6.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 160       | 6.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 139       | 5.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 130       | 5.11%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 124       | 4.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 108       | 4.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 88        | 3.46%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 72        | 2.83%   |
| Samsung NVMe SSD Controller 980                                                | 71        | 2.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 64        | 2.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 63        | 2.48%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 56        | 2.2%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 54        | 2.12%   |
| Intel Volume Management Device NVMe RAID Controller                            | 51        | 2.01%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 45        | 1.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 45        | 1.77%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 37        | 1.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 36        | 1.42%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 35        | 1.38%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 32        | 1.26%   |
| Micron NVMe Storage Controller                                                 | 32        | 1.26%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 31        | 1.22%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 31        | 1.22%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 30        | 1.18%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 27        | 1.06%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 23        | 0.9%    |
| SK hynix Non-Volatile memory controller                                        | 22        | 0.87%   |
| SK hynix BC511                                                                 | 22        | 0.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 21        | 0.83%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 20        | 0.79%   |
| Intel Comet Lake SATA AHCI Controller                                          | 20        | 0.79%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 19        | 0.75%   |
| Intel SSD 660P Series                                                          | 18        | 0.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 18        | 0.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 18        | 0.71%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 17        | 0.67%   |
| Intel Tiger Lake-LP SATA Controller                                            | 17        | 0.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 17        | 0.67%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 16        | 0.63%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 15        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1308      | 53.69%  |
| NVMe | 777       | 31.9%   |
| RAID | 196       | 8.05%   |
| IDE  | 155       | 6.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1742      | 85.98%  |
| AMD    | 283       | 13.97%  |
| ARM    | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 44        | 2.17%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 40        | 1.97%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 36        | 1.78%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 34        | 1.68%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 31        | 1.53%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 27        | 1.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 26        | 1.28%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 26        | 1.28%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 24        | 1.18%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 23        | 1.14%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 23        | 1.14%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 23        | 1.14%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 22        | 1.09%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 20        | 0.99%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 20        | 0.99%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 19        | 0.94%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 19        | 0.94%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 18        | 0.89%   |
| AMD Custom APU 0405                           | 18        | 0.89%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 16        | 0.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 16        | 0.79%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 16        | 0.79%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 15        | 0.74%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 15        | 0.74%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 15        | 0.74%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 13        | 0.64%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 13        | 0.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 13        | 0.64%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 13        | 0.64%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 13        | 0.64%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 12        | 0.59%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 12        | 0.59%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 12        | 0.59%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 12        | 0.59%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 12        | 0.59%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 11        | 0.54%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 11        | 0.54%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 11        | 0.54%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 11        | 0.54%   |
| Intel 12th Gen Core i7-12700H                 | 11        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 507       | 25.02%  |
| Intel Core i7                  | 506       | 24.98%  |
| Intel Core i3                  | 167       | 8.24%   |
| Other                          | 161       | 7.95%   |
| Intel Core 2 Duo               | 98        | 4.84%   |
| AMD Ryzen 7                    | 77        | 3.8%    |
| Intel Celeron                  | 75        | 3.7%    |
| Intel Pentium                  | 57        | 2.81%   |
| Intel Atom                     | 56        | 2.76%   |
| AMD Ryzen 5                    | 49        | 2.42%   |
| Intel Pentium Dual-Core        | 26        | 1.28%   |
| AMD Ryzen 7 PRO                | 22        | 1.09%   |
| Intel Pentium Dual             | 21        | 1.04%   |
| Intel Genuine                  | 19        | 0.94%   |
| Intel Core i9                  | 19        | 0.94%   |
| AMD A6                         | 16        | 0.79%   |
| Intel Core 2                   | 15        | 0.74%   |
| AMD Ryzen 5 PRO                | 15        | 0.74%   |
| AMD Ryzen 9                    | 11        | 0.54%   |
| Intel Pentium Silver           | 9         | 0.44%   |
| AMD E1                         | 8         | 0.39%   |
| AMD A10                        | 8         | 0.39%   |
| AMD E                          | 7         | 0.35%   |
| AMD A4                         | 7         | 0.35%   |
| Intel Xeon                     | 6         | 0.3%    |
| Intel Core m3                  | 6         | 0.3%    |
| AMD A8                         | 6         | 0.3%    |
| Intel Celeron M                | 4         | 0.2%    |
| Intel Celeron Dual-Core        | 4         | 0.2%    |
| AMD E2                         | 4         | 0.2%    |
| AMD Athlon X2                  | 4         | 0.2%    |
| AMD Ryzen 3                    | 3         | 0.15%   |
| AMD Athlon II                  | 3         | 0.15%   |
| AMD Athlon 64 X2               | 3         | 0.15%   |
| Intel Core m7                  | 2         | 0.1%    |
| Intel Core m5                  | 2         | 0.1%    |
| Intel Core Duo                 | 2         | 0.1%    |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.1%    |
| AMD Ryzen 3 PRO                | 2         | 0.1%    |
| AMD PRO A10                    | 2         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 971       | 47.9%   |
| 4      | 676       | 33.35%  |
| 6      | 154       | 7.6%    |
| 8      | 135       | 6.66%   |
| 1      | 45        | 2.22%   |
| 10     | 17        | 0.84%   |
| 14     | 16        | 0.79%   |
| 12     | 12        | 0.59%   |
| 24     | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2026      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1530      | 75.52%  |
| 1      | 494       | 24.38%  |
| 8      | 1         | 0.05%   |
| 4      | 1         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1983      | 97.54%  |
| Unknown        | 29        | 1.43%   |
| 32-bit         | 20        | 0.98%   |
| 64-bit         | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 511       | 24.37%  |
| 0x306a9    | 134       | 6.39%   |
| 0x206a7    | 116       | 5.53%   |
| 0x806ec    | 103       | 4.91%   |
| 0x906ea    | 75        | 3.58%   |
| 0x40651    | 66        | 3.15%   |
| 0x1067a    | 63        | 3%      |
| 0x406e3    | 60        | 2.86%   |
| 0x806ea    | 57        | 2.72%   |
| 0x806c1    | 57        | 2.72%   |
| 0x20655    | 54        | 2.58%   |
| 0x306c3    | 49        | 2.34%   |
| 0x6fd      | 48        | 2.29%   |
| 0x806e9    | 47        | 2.24%   |
| 0x306d4    | 43        | 2.05%   |
| 0x0a50000c | 32        | 1.53%   |
| 0x08600106 | 31        | 1.48%   |
| 0x806eb    | 30        | 1.43%   |
| 0x30678    | 30        | 1.43%   |
| 0x906e9    | 29        | 1.38%   |
| 0xa0652    | 27        | 1.29%   |
| 0x506e3    | 25        | 1.19%   |
| 0x08108102 | 21        | 1%      |
| 0x20652    | 20        | 0.95%   |
| 0x506c9    | 18        | 0.86%   |
| 0x906a3    | 17        | 0.81%   |
| 0x706e5    | 15        | 0.72%   |
| 0x10676    | 15        | 0.72%   |
| 0x08108109 | 15        | 0.72%   |
| 0x906ed    | 14        | 0.67%   |
| 0x806d1    | 14        | 0.67%   |
| 0x406c3    | 13        | 0.62%   |
| 0x08608103 | 13        | 0.62%   |
| 0x08600103 | 13        | 0.62%   |
| 0x906a4    | 12        | 0.57%   |
| 0x406c4    | 12        | 0.57%   |
| 0x40661    | 11        | 0.52%   |
| 0x6f6      | 10        | 0.48%   |
| 0x6e8      | 10        | 0.48%   |
| 0x706a8    | 9         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 467       | 23.03%  |
| IvyBridge        | 166       | 8.19%   |
| Haswell          | 152       | 7.5%    |
| SandyBridge      | 147       | 7.25%   |
| Skylake          | 117       | 5.77%   |
| Penryn           | 100       | 4.93%   |
| Westmere         | 95        | 4.68%   |
| Core             | 83        | 4.09%   |
| Silvermont       | 78        | 3.85%   |
| TigerLake        | 74        | 3.65%   |
| Unknown          | 62        | 3.06%   |
| Broadwell        | 60        | 2.96%   |
| Zen 2            | 58        | 2.86%   |
| Zen 3            | 54        | 2.66%   |
| Zen+             | 39        | 1.92%   |
| CometLake        | 39        | 1.92%   |
| Alderlake Hybrid | 32        | 1.58%   |
| IceLake          | 31        | 1.53%   |
| Goldmont         | 23        | 1.13%   |
| Goldmont plus    | 16        | 0.79%   |
| P6               | 15        | 0.74%   |
| Bonnell          | 15        | 0.74%   |
| Excavator        | 14        | 0.69%   |
| Jaguar           | 11        | 0.54%   |
| Bobcat           | 11        | 0.54%   |
| Piledriver       | 9         | 0.44%   |
| K8 & K10 hybrid  | 9         | 0.44%   |
| Puma             | 8         | 0.39%   |
| K8 Hammer        | 8         | 0.39%   |
| Zen              | 7         | 0.35%   |
| Nehalem          | 7         | 0.35%   |
| K10 Llano        | 7         | 0.35%   |
| K10              | 6         | 0.3%    |
| Tremont          | 5         | 0.25%   |
| Steamroller      | 3         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1544      | 60.43%  |
| Nvidia                           | 598       | 23.41%  |
| AMD                              | 402       | 15.73%  |
| Silicon Integrated Systems [SiS] | 8         | 0.31%   |
| VIA Technologies                 | 3         | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 150       | 5.71%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 135       | 5.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 114       | 4.34%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 109       | 4.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 73        | 2.78%   |
| Intel UHD Graphics 620                                                                   | 71        | 2.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 69        | 2.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 64        | 2.44%   |
| Intel Core Processor Integrated Graphics Controller                                      | 61        | 2.32%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 61        | 2.32%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 59        | 2.25%   |
| AMD Renoir                                                                               | 55        | 2.09%   |
| Intel HD Graphics 620                                                                    | 54        | 2.06%   |
| Intel HD Graphics 630                                                                    | 43        | 1.64%   |
| Intel HD Graphics 5500                                                                   | 43        | 1.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 43        | 1.64%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 43        | 1.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 42        | 1.6%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 41        | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 39        | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 35        | 1.33%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 34        | 1.29%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 32        | 1.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 30        | 1.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 30        | 1.14%   |
| Intel HD Graphics 530                                                                    | 29        | 1.1%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 26        | 0.99%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 22        | 0.84%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 19        | 0.72%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 18        | 0.69%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 17        | 0.65%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 17        | 0.65%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 17        | 0.65%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 16        | 0.61%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 16        | 0.61%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 16        | 0.61%   |
| AMD Lucienne                                                                             | 16        | 0.61%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 14        | 0.53%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 14        | 0.53%   |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1044      | 51.25%  |
| Intel + Nvidia | 432       | 21.21%  |
| 1 x AMD        | 289       | 14.19%  |
| 1 x Nvidia     | 137       | 6.73%   |
| Intel + AMD    | 63        | 3.09%   |
| AMD + Nvidia   | 29        | 1.42%   |
| 2 x AMD        | 20        | 0.98%   |
| 1 x SiS        | 8         | 0.39%   |
| 2 x Intel      | 6         | 0.29%   |
| 2 x Nvidia     | 4         | 0.2%    |
| 1 x VIA        | 3         | 0.15%   |
| Other          | 2         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1714      | 83.33%  |
| Proprietary | 285       | 13.86%  |
| Unknown     | 58        | 2.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1378      | 66.28%  |
| 0.01-0.5   | 210       | 10.1%   |
| 1.01-2.0   | 195       | 9.38%   |
| 3.01-4.0   | 127       | 6.11%   |
| 0.51-1.0   | 106       | 5.1%    |
| 7.01-8.0   | 31        | 1.49%   |
| 5.01-6.0   | 21        | 1.01%   |
| 2.01-3.0   | 9         | 0.43%   |
| 8.01-16.0  | 2         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 491       | 21.26%  |
| LG Display              | 328       | 14.21%  |
| Chimei Innolux          | 259       | 11.22%  |
| Samsung Electronics     | 247       | 10.7%   |
| BOE                     | 233       | 10.09%  |
| Sharp                   | 82        | 3.55%   |
| Apple                   | 75        | 3.25%   |
| Dell                    | 72        | 3.12%   |
| Chi Mei Optoelectronics | 59        | 2.56%   |
| Goldstar                | 52        | 2.25%   |
| Philips                 | 40        | 1.73%   |
| Iiyama                  | 36        | 1.56%   |
| Lenovo                  | 35        | 1.52%   |
| LG Philips              | 34        | 1.47%   |
| Hewlett-Packard         | 34        | 1.47%   |
| Acer                    | 20        | 0.87%   |
| CSO                     | 18        | 0.78%   |
| PANDA                   | 17        | 0.74%   |
| InfoVision              | 16        | 0.69%   |
| AOC                     | 15        | 0.65%   |
| Valve                   | 11        | 0.48%   |
| BenQ                    | 11        | 0.48%   |
| Sony                    | 10        | 0.43%   |
| Ancor Communications    | 9         | 0.39%   |
| LGD                     | 8         | 0.35%   |
| Toshiba                 | 6         | 0.26%   |
| Seiko/Epson             | 6         | 0.26%   |
| CPT                     | 6         | 0.26%   |
| MSI                     | 5         | 0.22%   |
| HannStar                | 5         | 0.22%   |
| Unknown                 | 4         | 0.17%   |
| Quanta Display          | 4         | 0.17%   |
| Panasonic               | 4         | 0.17%   |
| JDI                     | 4         | 0.17%   |
| Analogix                | 4         | 0.17%   |
| ViewSonic               | 3         | 0.13%   |
| Vestel Elektronik       | 3         | 0.13%   |
| ASUSTek Computer        | 3         | 0.13%   |
| RTK                     | 2         | 0.09%   |
| Medion                  | 2         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 25        | 1.07%   |
| AU Optronics LCD Monitor AUO202D 1920x1080 293x165mm 13.2-inch            | 22        | 0.94%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch      | 18        | 0.77%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 16        | 0.68%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 15        | 0.64%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 14        | 0.6%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 12        | 0.51%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 12        | 0.51%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 11        | 0.47%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 11        | 0.47%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 11        | 0.47%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch      | 10        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 10        | 0.43%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 10        | 0.43%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 9         | 0.38%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 9         | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 9         | 0.38%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 9         | 0.38%   |
| LGD LCD Monitor 1920x1080                                                 | 8         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 8         | 0.34%   |
| BOE LCD Monitor BOE07B9 1920x1080 293x165mm 13.2-inch                     | 8         | 0.34%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch               | 7         | 0.3%    |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch          | 7         | 0.3%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 7         | 0.3%    |
| AU Optronics LCD Monitor AUO35ED 1920x1080 344x193mm 15.5-inch            | 7         | 0.3%    |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch             | 7         | 0.3%    |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 7         | 0.3%    |
| AU Optronics LCD Monitor AUO213D 1920x1080 309x173mm 13.9-inch            | 7         | 0.3%    |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 7         | 0.3%    |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch            | 7         | 0.3%    |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                      | 7         | 0.3%    |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                   | 6         | 0.26%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch               | 6         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 6         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 6         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch           | 6         | 0.26%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 6         | 0.26%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 6         | 0.26%   |
| AU Optronics LCD Monitor AUO6287 1440x900 367x229mm 17.0-inch             | 6         | 0.26%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch             | 6         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 942       | 42.92%  |
| 1366x768 (WXGA)    | 452       | 20.59%  |
| 1600x900 (HD+)     | 163       | 7.43%   |
| 1280x800 (WXGA)    | 107       | 4.87%   |
| 3840x2160 (4K)     | 103       | 4.69%   |
| 2560x1440 (QHD)    | 82        | 3.74%   |
| 1440x900 (WXGA+)   | 63        | 2.87%   |
| 1920x1200 (WUXGA)  | 40        | 1.82%   |
| 2560x1600          | 32        | 1.46%   |
| 2880x1800          | 26        | 1.18%   |
| 3840x2400          | 23        | 1.05%   |
| 1680x1050 (WSXGA+) | 20        | 0.91%   |
| 1280x1024 (SXGA)   | 19        | 0.87%   |
| 3440x1440          | 17        | 0.77%   |
| 800x1280           | 14        | 0.64%   |
| 1360x768           | 13        | 0.59%   |
| 2560x1080          | 12        | 0.55%   |
| Unknown            | 7         | 0.32%   |
| 3456x2160          | 5         | 0.23%   |
| 3200x1800 (QHD+)   | 5         | 0.23%   |
| 3000x2000          | 5         | 0.23%   |
| 1024x600           | 5         | 0.23%   |
| 1024x768 (XGA)     | 4         | 0.18%   |
| 3840x1600          | 3         | 0.14%   |
| 3072x1920          | 3         | 0.14%   |
| 2160x1440          | 3         | 0.14%   |
| 1920x540           | 3         | 0.14%   |
| 1680x945           | 3         | 0.14%   |
| 3840x1080          | 2         | 0.09%   |
| 2304x1440          | 2         | 0.09%   |
| 2256x1504          | 2         | 0.09%   |
| 1280x720 (HD)      | 2         | 0.09%   |
| 8960x2160          | 1         | 0.05%   |
| 5440x1800          | 1         | 0.05%   |
| 4480x1600          | 1         | 0.05%   |
| 3840x1100          | 1         | 0.05%   |
| 3600x1080          | 1         | 0.05%   |
| 3200x1080          | 1         | 0.05%   |
| 2880x864           | 1         | 0.05%   |
| 2880x1620          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 869       | 37.64%  |
| 13      | 315       | 13.64%  |
| 17      | 266       | 11.52%  |
| 14      | 221       | 9.57%   |
| 24      | 87        | 3.77%   |
| 27      | 84        | 3.64%   |
| 12      | 70        | 3.03%   |
| 11      | 55        | 2.38%   |
| Unknown | 47        | 2.04%   |
| 23      | 46        | 1.99%   |
| 21      | 35        | 1.52%   |
| 34      | 27        | 1.17%   |
| 31      | 27        | 1.17%   |
| 16      | 25        | 1.08%   |
| 18      | 17        | 0.74%   |
| 19      | 13        | 0.56%   |
| 22      | 11        | 0.48%   |
| 10      | 11        | 0.48%   |
| 7       | 11        | 0.48%   |
| 25      | 9         | 0.39%   |
| 84      | 6         | 0.26%   |
| 72      | 5         | 0.22%   |
| 54      | 5         | 0.22%   |
| 20      | 5         | 0.22%   |
| 40      | 4         | 0.17%   |
| 37      | 4         | 0.17%   |
| 3       | 4         | 0.17%   |
| 65      | 3         | 0.13%   |
| 47      | 3         | 0.13%   |
| 32      | 3         | 0.13%   |
| 46      | 2         | 0.09%   |
| 35      | 2         | 0.09%   |
| 29      | 2         | 0.09%   |
| 28      | 2         | 0.09%   |
| 26      | 2         | 0.09%   |
| 8       | 2         | 0.09%   |
| 86      | 1         | 0.04%   |
| 60      | 1         | 0.04%   |
| 57      | 1         | 0.04%   |
| 50      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1196      | 52.27%  |
| 201-300     | 340       | 14.86%  |
| 351-400     | 302       | 13.2%   |
| 501-600     | 208       | 9.09%   |
| 401-500     | 68        | 2.97%   |
| Unknown     | 47        | 2.05%   |
| 601-700     | 38        | 1.66%   |
| 701-800     | 32        | 1.4%    |
| 1001-1500   | 16        | 0.7%    |
| 1-100       | 14        | 0.61%   |
| 801-900     | 12        | 0.52%   |
| 1501-2000   | 12        | 0.52%   |
| 101-200     | 2         | 0.09%   |
| 901-1000    | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1604      | 78.32%  |
| 16/10   | 311       | 15.19%  |
| Unknown | 36        | 1.76%   |
| 21/9    | 32        | 1.56%   |
| 3/2     | 20        | 0.98%   |
| 5/4     | 17        | 0.83%   |
| 0.67    | 11        | 0.54%   |
| 4/3     | 8         | 0.39%   |
| 6/5     | 4         | 0.2%    |
| 32/9    | 1         | 0.05%   |
| 3.40    | 1         | 0.05%   |
| 3.33    | 1         | 0.05%   |
| 0.62    | 1         | 0.05%   |
| 0.56    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 858       | 37.21%  |
| 81-90          | 372       | 16.13%  |
| 121-130        | 214       | 9.28%   |
| 71-80          | 160       | 6.94%   |
| 201-250        | 143       | 6.2%    |
| 301-350        | 86        | 3.73%   |
| 61-70          | 70        | 3.04%   |
| 351-500        | 66        | 2.86%   |
| 51-60          | 57        | 2.47%   |
| Unknown        | 47        | 2.04%   |
| 131-140        | 46        | 1.99%   |
| 251-300        | 34        | 1.47%   |
| 111-120        | 33        | 1.43%   |
| 151-200        | 31        | 1.34%   |
| More than 1000 | 23        | 1%      |
| 141-150        | 19        | 0.82%   |
| 1-40           | 16        | 0.69%   |
| 501-1000       | 15        | 0.65%   |
| 41-50          | 10        | 0.43%   |
| 91-100         | 6         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 926       | 40.79%  |
| 101-120       | 569       | 25.07%  |
| 51-100        | 373       | 16.43%  |
| 161-240       | 205       | 9.03%   |
| More than 240 | 119       | 5.24%   |
| Unknown       | 47        | 2.07%   |
| 1-50          | 31        | 1.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1590      | 76.3%   |
| 2     | 373       | 17.9%   |
| 0     | 81        | 3.89%   |
| 3     | 36        | 1.73%   |
| 4     | 3         | 0.14%   |
| 5     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 1200      | 36.9%   |
| Realtek Semiconductor                  | 974       | 29.95%  |
| Qualcomm Atheros                       | 405       | 12.45%  |
| Broadcom                               | 237       | 7.29%   |
| Broadcom Limited                       | 59        | 1.81%   |
| Ralink                                 | 35        | 1.08%   |
| Marvell Technology Group               | 32        | 0.98%   |
| MediaTek                               | 31        | 0.95%   |
| ASIX Electronics                       | 30        | 0.92%   |
| Dell                                   | 28        | 0.86%   |
| TP-Link                                | 24        | 0.74%   |
| DisplayLink                            | 24        | 0.74%   |
| Hewlett-Packard                        | 23        | 0.71%   |
| Nvidia                                 | 19        | 0.58%   |
| Ralink Technology                      | 18        | 0.55%   |
| Silicon Integrated Systems [SiS]       | 12        | 0.37%   |
| Ericsson Business Mobile Networks      | 12        | 0.37%   |
| JMicron Technology                     | 10        | 0.31%   |
| Sierra Wireless                        | 9         | 0.28%   |
| Samsung Electronics                    | 8         | 0.25%   |
| Qualcomm                               | 7         | 0.22%   |
| Lenovo                                 | 7         | 0.22%   |
| Huawei Technologies                    | 7         | 0.22%   |
| ASUSTek Computer                       | 4         | 0.12%   |
| VIA Technologies                       | 3         | 0.09%   |
| Sitecom Europe                         | 3         | 0.09%   |
| NetGear                                | 3         | 0.09%   |
| Fibocom                                | 3         | 0.09%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.06%   |
| Xiaomi                                 | 2         | 0.06%   |
| MosChip Semiconductor                  | 2         | 0.06%   |
| Dresden Elektronik                     | 2         | 0.06%   |
| D-Link                                 | 2         | 0.06%   |
| Arduino SA                             | 2         | 0.06%   |
| Spreadtrum Communications              | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| Senao                                  | 1         | 0.03%   |
| Sagem                                  | 1         | 0.03%   |
| Prusa                                  | 1         | 0.03%   |
| Motorola PCS                           | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 629       | 16.08%  |
| Intel Wi-Fi 6 AX200                                                     | 139       | 3.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 134       | 3.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 103       | 2.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 100       | 2.56%   |
| Intel Wireless 8265 / 8275                                              | 95        | 2.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 95        | 2.43%   |
| Intel Wireless 7265                                                     | 77        | 1.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 63        | 1.61%   |
| Intel Wireless 7260                                                     | 63        | 1.61%   |
| Intel Wi-Fi 6 AX201                                                     | 57        | 1.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 56        | 1.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 55        | 1.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 55        | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 51        | 1.3%    |
| Intel Wireless 8260                                                     | 47        | 1.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 44        | 1.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 42        | 1.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 38        | 0.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 38        | 0.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 37        | 0.95%   |
| Intel Centrino Ultimate-N 6300                                          | 36        | 0.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 36        | 0.92%   |
| Intel 82577LM Gigabit Network Connection                                | 32        | 0.82%   |
| Intel Wireless-AC 9260                                                  | 31        | 0.79%   |
| Intel Wireless 3165                                                     | 31        | 0.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 31        | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 29        | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                                   | 29        | 0.74%   |
| Intel Centrino Advanced-N 6200                                          | 29        | 0.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 27        | 0.69%   |
| ASIX AX88179 Gigabit Ethernet                                           | 27        | 0.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 26        | 0.66%   |
| Intel Ethernet Connection I219-LM                                       | 26        | 0.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 26        | 0.66%   |
| Intel Wireless 3160                                                     | 25        | 0.64%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 25        | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 24        | 0.61%   |
| Intel Ethernet Connection I218-LM                                       | 24        | 0.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 22        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1153      | 55.49%  |
| Qualcomm Atheros                      | 346       | 16.65%  |
| Realtek Semiconductor                 | 230       | 11.07%  |
| Broadcom                              | 171       | 8.23%   |
| Ralink                                | 35        | 1.68%   |
| MediaTek                              | 30        | 1.44%   |
| Broadcom Limited                      | 28        | 1.35%   |
| Ralink Technology                     | 18        | 0.87%   |
| TP-Link                               | 16        | 0.77%   |
| Dell                                  | 11        | 0.53%   |
| Sierra Wireless                       | 9         | 0.43%   |
| Qualcomm                              | 5         | 0.24%   |
| Hewlett-Packard                       | 4         | 0.19%   |
| ASUSTek Computer                      | 4         | 0.19%   |
| Sitecom Europe                        | 3         | 0.14%   |
| NetGear                               | 3         | 0.14%   |
| Fibocom                               | 3         | 0.14%   |
| D-Link                                | 2         | 0.1%    |
| Silicon Integrated Systems [SiS]      | 1         | 0.05%   |
| Senao                                 | 1         | 0.05%   |
| Sagem                                 | 1         | 0.05%   |
| Microsoft                             | 1         | 0.05%   |
| Linksys                               | 1         | 0.05%   |
| BUFFALO                               | 1         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 139       | 6.66%   |
| Intel Wireless 8265 / 8275                                              | 95        | 4.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 95        | 4.55%   |
| Intel Wireless 7265                                                     | 77        | 3.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 63        | 3.02%   |
| Intel Wireless 7260                                                     | 63        | 3.02%   |
| Intel Wi-Fi 6 AX201                                                     | 57        | 2.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 56        | 2.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 55        | 2.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 55        | 2.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 51        | 2.44%   |
| Intel Wireless 8260                                                     | 47        | 2.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 44        | 2.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 42        | 2.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 38        | 1.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 38        | 1.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 37        | 1.77%   |
| Intel Centrino Ultimate-N 6300                                          | 36        | 1.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 36        | 1.72%   |
| Intel Wireless-AC 9260                                                  | 31        | 1.49%   |
| Intel Wireless 3165                                                     | 31        | 1.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 31        | 1.49%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 29        | 1.39%   |
| Intel Centrino Advanced-N 6200                                          | 29        | 1.39%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 27        | 1.29%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 26        | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 26        | 1.25%   |
| Intel Wireless 3160                                                     | 25        | 1.2%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 25        | 1.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 22        | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 20        | 0.96%   |
| Intel Centrino Advanced-N 6235                                          | 20        | 0.96%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 20        | 0.96%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 19        | 0.91%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 19        | 0.91%   |
| Broadcom BCM43142 802.11b/g/n                                           | 19        | 0.91%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 18        | 0.86%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 17        | 0.81%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 16        | 0.77%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 16        | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 880       | 50.72%  |
| Intel                                  | 427       | 24.61%  |
| Qualcomm Atheros                       | 116       | 6.69%   |
| Broadcom                               | 109       | 6.28%   |
| Marvell Technology Group               | 32        | 1.84%   |
| Broadcom Limited                       | 31        | 1.79%   |
| ASIX Electronics                       | 30        | 1.73%   |
| DisplayLink                            | 24        | 1.38%   |
| Nvidia                                 | 18        | 1.04%   |
| Silicon Integrated Systems [SiS]       | 11        | 0.63%   |
| JMicron Technology                     | 10        | 0.58%   |
| TP-Link                                | 8         | 0.46%   |
| Lenovo                                 | 7         | 0.4%    |
| Samsung Electronics                    | 6         | 0.35%   |
| Hewlett-Packard                        | 5         | 0.29%   |
| Huawei Technologies                    | 4         | 0.23%   |
| VIA Technologies                       | 3         | 0.17%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.12%   |
| Xiaomi                                 | 2         | 0.12%   |
| Qualcomm                               | 2         | 0.12%   |
| MosChip Semiconductor                  | 2         | 0.12%   |
| Spreadtrum Communications              | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| Motorola PCS                           | 1         | 0.06%   |
| Jolla Oy                               | 1         | 0.06%   |
| Apple                                  | 1         | 0.06%   |
| ADMtek                                 | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 629       | 35.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 134       | 7.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 103       | 5.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 100       | 5.66%   |
| Intel 82577LM Gigabit Network Connection                          | 32        | 1.81%   |
| Intel Ethernet Connection (4) I219-LM                             | 29        | 1.64%   |
| ASIX AX88179 Gigabit Ethernet                                     | 27        | 1.53%   |
| Intel Ethernet Connection I219-LM                                 | 26        | 1.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 24        | 1.36%   |
| Intel Ethernet Connection I218-LM                                 | 24        | 1.36%   |
| Intel Ethernet Connection (6) I219-V                              | 20        | 1.13%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 20        | 1.13%   |
| Intel Ethernet Connection (3) I218-LM                             | 18        | 1.02%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 17        | 0.96%   |
| Intel Ethernet Connection I217-LM                                 | 16        | 0.91%   |
| Intel Ethernet Connection (4) I219-V                              | 16        | 0.91%   |
| Intel Ethernet Connection (6) I219-LM                             | 15        | 0.85%   |
| Intel Ethernet Connection (7) I219-LM                             | 14        | 0.79%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 13        | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 13        | 0.74%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 13        | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 12        | 0.68%   |
| Intel 82579V Gigabit Network Connection                           | 12        | 0.68%   |
| Intel 82567LM Gigabit Network Connection                          | 12        | 0.68%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 11        | 0.62%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 11        | 0.62%   |
| Nvidia MCP79 Ethernet                                             | 11        | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 11        | 0.62%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 10        | 0.57%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 10        | 0.57%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 10        | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 9         | 0.51%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 9         | 0.51%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 9         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8         | 0.45%   |
| Intel Ethernet Connection I217-V                                  | 8         | 0.45%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 8         | 0.45%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 8         | 0.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 0.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 7         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1975      | 53.62%  |
| Ethernet | 1652      | 44.85%  |
| Modem    | 55        | 1.49%   |
| Unknown  | 1         | 0.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1648      | 75.29%  |
| Ethernet | 541       | 24.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1488      | 73.3%   |
| 1     | 483       | 23.79%  |
| 0     | 37        | 1.82%   |
| 3     | 22        | 1.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1631      | 78.6%   |
| Yes  | 444       | 21.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 865       | 54.82%  |
| Realtek Semiconductor           | 112       | 7.1%    |
| Qualcomm Atheros Communications | 103       | 6.53%   |
| Broadcom                        | 92        | 5.83%   |
| IMC Networks                    | 69        | 4.37%   |
| Apple                           | 63        | 3.99%   |
| Foxconn / Hon Hai               | 55        | 3.49%   |
| Lite-On Technology              | 53        | 3.36%   |
| Hewlett-Packard                 | 42        | 2.66%   |
| Dell                            | 35        | 2.22%   |
| Cambridge Silicon Radio         | 29        | 1.84%   |
| Toshiba                         | 19        | 1.2%    |
| Ralink                          | 9         | 0.57%   |
| ASUSTek Computer                | 9         | 0.57%   |
| Realtek                         | 4         | 0.25%   |
| Alps Electric                   | 4         | 0.25%   |
| Ralink Technology               | 3         | 0.19%   |
| Integrated System Solution      | 3         | 0.19%   |
| Foxconn International           | 2         | 0.13%   |
| USI                             | 1         | 0.06%   |
| TP-Link                         | 1         | 0.06%   |
| Sitecom Europe                  | 1         | 0.06%   |
| Micro Star International        | 1         | 0.06%   |
| MediaTek                        | 1         | 0.06%   |
| Chicony Electronics             | 1         | 0.06%   |
| Unknown                         | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 318       | 20.13%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 150       | 9.49%   |
| Intel AX200 Bluetooth                               | 136       | 8.61%   |
| Intel AX201 Bluetooth                               | 125       | 7.91%   |
| Realtek Bluetooth Radio                             | 64        | 4.05%   |
| Intel Bluetooth Device                              | 46        | 2.91%   |
| Apple Bluetooth Host Controller                     | 40        | 2.53%   |
| Qualcomm Atheros  Bluetooth Device                  | 38        | 2.41%   |
| Realtek  Bluetooth 4.2 Adapter                      | 35        | 2.22%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 31        | 1.96%   |
| IMC Networks Bluetooth Radio                        | 30        | 1.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 29        | 1.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 29        | 1.84%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 26        | 1.65%   |
| Foxconn / Hon Hai Bluetooth Device                  | 23        | 1.46%   |
| Lite-On Bluetooth Device                            | 21        | 1.33%   |
| HP Broadcom 2070 Bluetooth Combo                    | 21        | 1.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 20        | 1.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 19        | 1.2%    |
| Dell DW375 Bluetooth Module                         | 19        | 1.2%    |
| Apple Bluetooth USB Host Controller                 | 18        | 1.14%   |
| Intel AX210 Bluetooth                               | 17        | 1.08%   |
| Broadcom BCM2045B (BDC-2.1)                         | 17        | 1.08%   |
| Broadcom HP Portable SoftSailing                    | 16        | 1.01%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 0.89%   |
| Intel Wireless-AC 3168 Bluetooth                    | 14        | 0.89%   |
| IMC Networks Bluetooth Device                       | 14        | 0.89%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 12        | 0.76%   |
| Dell BCM20702A0 Bluetooth Module                    | 12        | 0.76%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 12        | 0.76%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 11        | 0.7%    |
| Broadcom BCM2045 Bluetooth                          | 11        | 0.7%    |
| IMC Networks Wireless_Device                        | 10        | 0.63%   |
| Ralink RT3290 Bluetooth                             | 9         | 0.57%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 9         | 0.57%   |
| Broadcom HP Portable Bumble Bee                     | 9         | 0.57%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.44%   |
| Realtek RTL8723B Bluetooth                          | 6         | 0.38%   |
| Foxconn / Hon Hai BCM20702A0                        | 6         | 0.38%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 5         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1662      | 65.72%  |
| AMD                              | 352       | 13.92%  |
| Nvidia                           | 314       | 12.42%  |
| Realtek Semiconductor            | 28        | 1.11%   |
| C-Media Electronics              | 21        | 0.83%   |
| GN Netcom                        | 19        | 0.75%   |
| Logitech                         | 18        | 0.71%   |
| Silicon Integrated Systems [SiS] | 13        | 0.51%   |
| Hewlett-Packard                  | 12        | 0.47%   |
| Plantronics                      | 8         | 0.32%   |
| Apple                            | 7         | 0.28%   |
| Texas Instruments                | 5         | 0.2%    |
| Lenovo                           | 5         | 0.2%    |
| BEHRINGER International          | 5         | 0.2%    |
| Kingston Technology              | 4         | 0.16%   |
| JMTek                            | 4         | 0.16%   |
| VIA Technologies                 | 3         | 0.12%   |
| No brand                         | 3         | 0.12%   |
| GYROCOM C&C                      | 3         | 0.12%   |
| Veho                             | 2         | 0.08%   |
| SteelSeries ApS                  | 2         | 0.08%   |
| Sony                             | 2         | 0.08%   |
| Razer USA                        | 2         | 0.08%   |
| Focusrite-Novation               | 2         | 0.08%   |
| DSEA A/S                         | 2         | 0.08%   |
| Creative Technology              | 2         | 0.08%   |
| Corsair                          | 2         | 0.08%   |
| YZ Technology                    | 1         | 0.04%   |
| XMOS                             | 1         | 0.04%   |
| Tenx Technology                  | 1         | 0.04%   |
| Syntek                           | 1         | 0.04%   |
| Shenzhen Riitek Technology       | 1         | 0.04%   |
| Sennheiser Communications        | 1         | 0.04%   |
| SAVITECH                         | 1         | 0.04%   |
| RODE Microphones                 | 1         | 0.04%   |
| PreSonus Audio Electronics       | 1         | 0.04%   |
| Polycom                          | 1         | 0.04%   |
| Pioneer DJ                       | 1         | 0.04%   |
| Other World Computing            | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 214       | 7.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 188       | 6.35%   |
| AMD Family 17h/19h HD Audio Controller                                     | 176       | 5.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 125       | 4.22%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 119       | 4.02%   |
| Intel Cannon Lake PCH cAVS                                                 | 119       | 4.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 102       | 3.45%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 102       | 3.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 82        | 2.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 76        | 2.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 74        | 2.5%    |
| Intel Haswell-ULT HD Audio Controller                                      | 74        | 2.5%    |
| Intel 8 Series HD Audio Controller                                         | 74        | 2.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 60        | 2.03%   |
| Intel Broadwell-U Audio Controller                                         | 60        | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 54        | 1.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 52        | 1.76%   |
| Intel CM238 HD Audio Controller                                            | 48        | 1.62%   |
| Intel Comet Lake PCH-LP cAVS                                               | 44        | 1.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 43        | 1.45%   |
| AMD FCH Azalia Controller                                                  | 43        | 1.45%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 39        | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                            | 38        | 1.28%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 38        | 1.28%   |
| Intel Comet Lake PCH cAVS                                                  | 37        | 1.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 37        | 1.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 32        | 1.08%   |
| Nvidia GF108 High Definition Audio Controller                              | 32        | 1.08%   |
| Realtek Semiconductor USB Audio                                            | 27        | 0.91%   |
| Nvidia TU106 High Definition Audio Controller                              | 26        | 0.88%   |
| AMD Kabini HDMI/DP Audio                                                   | 25        | 0.84%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 23        | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 22        | 0.74%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 22        | 0.74%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 21        | 0.71%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 20        | 0.68%   |
| Nvidia GK107 HDMI Audio Controller                                         | 19        | 0.64%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 19        | 0.64%   |
| Nvidia High Definition Audio Controller                                    | 18        | 0.61%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 17        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 334       | 27.86%  |
| Samsung Electronics | 326       | 27.19%  |
| Micron Technology   | 149       | 12.43%  |
| Kingston            | 92        | 7.67%   |
| Unknown             | 72        | 6.01%   |
| Crucial             | 52        | 4.34%   |
| Corsair             | 24        | 2%      |
| Ramaxel Technology  | 23        | 1.92%   |
| A-DATA Technology   | 23        | 1.92%   |
| Nanya Technology    | 17        | 1.42%   |
| Elpida              | 15        | 1.25%   |
| G.Skill             | 10        | 0.83%   |
| Unknown             | 8         | 0.67%   |
| Team                | 7         | 0.58%   |
| GOODRAM             | 6         | 0.5%    |
| Unknown (ABCD)      | 5         | 0.42%   |
| ASint Technology    | 5         | 0.42%   |
| Qimonda             | 4         | 0.33%   |
| 48spaces            | 4         | 0.33%   |
| Wilk                | 3         | 0.25%   |
| Transcend           | 3         | 0.25%   |
| Toshiba             | 2         | 0.17%   |
| Lexar               | 2         | 0.17%   |
| Goldkey             | 2         | 0.17%   |
| ZIFEI               | 1         | 0.08%   |
| Timetec             | 1         | 0.08%   |
| tigo                | 1         | 0.08%   |
| Smart               | 1         | 0.08%   |
| SHARETRONIC         | 1         | 0.08%   |
| Sesame              | 1         | 0.08%   |
| PKI/Kingston        | 1         | 0.08%   |
| Micron/Elpida       | 1         | 0.08%   |
| Kllisre             | 1         | 0.08%   |
| Golden Empire       | 1         | 0.08%   |
| Apacer              | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 26        | 2.06%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 16        | 1.27%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 14        | 1.11%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 13        | 1.03%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.95%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 12        | 0.95%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.87%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 11        | 0.87%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 11        | 0.87%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 11        | 0.87%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.87%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.79%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 10        | 0.79%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 10        | 0.79%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 0.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.71%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 8         | 0.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 0.63%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 0.63%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.63%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.63%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 8         | 0.63%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 8         | 0.63%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 8         | 0.63%   |
| Unknown                                                          | 8         | 0.63%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 7         | 0.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.56%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 7         | 0.56%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 7         | 0.56%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 7         | 0.56%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.56%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.56%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                      | 6         | 0.48%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 6         | 0.48%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.48%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 6         | 0.48%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.48%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.48%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 521       | 50.19%  |
| DDR3    | 325       | 31.31%  |
| LPDDR3  | 48        | 4.62%   |
| LPDDR4  | 47        | 4.53%   |
| DDR2    | 37        | 3.56%   |
| SDRAM   | 23        | 2.22%   |
| DDR5    | 14        | 1.35%   |
| LPDDR5  | 12        | 1.16%   |
| DDR     | 4         | 0.39%   |
| Unknown | 4         | 0.39%   |
| DRAM    | 3         | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 914       | 87.21%  |
| Row Of Chips | 111       | 10.59%  |
| DIMM         | 10        | 0.95%   |
| Unknown      | 7         | 0.67%   |
| Chip         | 6         | 0.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 431       | 38.11%  |
| 4096  | 284       | 25.11%  |
| 16384 | 188       | 16.62%  |
| 2048  | 139       | 12.29%  |
| 1024  | 44        | 3.89%   |
| 32768 | 39        | 3.45%   |
| 512   | 5         | 0.44%   |
| 64    | 1         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 237       | 21.62%  |
| 1600    | 204       | 18.61%  |
| 3200    | 201       | 18.34%  |
| 2133    | 68        | 6.2%    |
| 2400    | 65        | 5.93%   |
| 1334    | 56        | 5.11%   |
| 1333    | 49        | 4.47%   |
| 4267    | 25        | 2.28%   |
| 667     | 22        | 2.01%   |
| Unknown | 21        | 1.92%   |
| 1867    | 20        | 1.82%   |
| 4800    | 13        | 1.19%   |
| 800     | 13        | 1.19%   |
| 8400    | 12        | 1.09%   |
| 6400    | 12        | 1.09%   |
| 1067    | 12        | 1.09%   |
| 3266    | 11        | 1%      |
| 4199    | 8         | 0.73%   |
| 2048    | 8         | 0.73%   |
| 1066    | 8         | 0.73%   |
| 4266    | 7         | 0.64%   |
| 1866    | 6         | 0.55%   |
| 1639    | 5         | 0.46%   |
| 533     | 3         | 0.27%   |
| 3000    | 2         | 0.18%   |
| 31582   | 1         | 0.09%   |
| 5200    | 1         | 0.09%   |
| 3733    | 1         | 0.09%   |
| 3600    | 1         | 0.09%   |
| 3500    | 1         | 0.09%   |
| 3400    | 1         | 0.09%   |
| 1200    | 1         | 0.09%   |
| 975     | 1         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 4         | 40%     |
| Hewlett-Packard | 3         | 30%     |
| Seiko Epson     | 2         | 20%     |
| Dymo-CoStar     | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Seiko Epson XP-200 Series   | 1         | 10%     |
| Seiko Epson ET-2720 Series  | 1         | 10%     |
| HP Printing Support         | 1         | 10%     |
| HP OfficeJet 3830 series    | 1         | 10%     |
| HP DeskJet 2700 series      | 1         | 10%     |
| Dymo-CoStar LabelWriter 400 | 1         | 10%     |
| Canon PIXMA MX920 Series    | 1         | 10%     |
| Canon MG5600 series         | 1         | 10%     |
| Canon LBP6680/3480 UFR II   | 1         | 10%     |
| Canon LBP2900               | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Canon          | 4         | 66.67%  |
| Seiko Epson    | 1         | 16.67%  |
| Mustek Systems | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan N650U/N656U                    | 2         | 33.33%  |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 16.67%  |
| Mustek Systems BearPaw 2400 CU Plus           | 1         | 16.67%  |
| Canon CanoScan LiDE 210                       | 1         | 16.67%  |
| Canon CanoScan 5600F                          | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 453       | 25.58%  |
| Microdia                               | 186       | 10.5%   |
| IMC Networks                           | 166       | 9.37%   |
| Realtek Semiconductor                  | 145       | 8.19%   |
| Sunplus Innovation Technology          | 117       | 6.61%   |
| Cheng Uei Precision Industry (Foxlink) | 92        | 5.19%   |
| Acer                                   | 79        | 4.46%   |
| Suyin                                  | 70        | 3.95%   |
| Quanta                                 | 67        | 3.78%   |
| Bison Electronics                      | 66        | 3.73%   |
| Apple                                  | 51        | 2.88%   |
| Lite-On Technology                     | 43        | 2.43%   |
| Logitech                               | 35        | 1.98%   |
| Luxvisions Innotech Limited            | 24        | 1.36%   |
| Syntek                                 | 22        | 1.24%   |
| Silicon Motion                         | 18        | 1.02%   |
| Ricoh                                  | 18        | 1.02%   |
| Lenovo                                 | 14        | 0.79%   |
| Primax Electronics                     | 13        | 0.73%   |
| Alcor Micro                            | 13        | 0.73%   |
| Samsung Electronics                    | 11        | 0.62%   |
| Importek                               | 7         | 0.4%    |
| Microsoft                              | 6         | 0.34%   |
| Sonix Technology                       | 5         | 0.28%   |
| ALi                                    | 4         | 0.23%   |
| Z-Star Microelectronics                | 3         | 0.17%   |
| Y Media                                | 3         | 0.17%   |
| SunplusIT                              | 3         | 0.17%   |
| Tobii Technology AB                    | 2         | 0.11%   |
| MacroSilicon                           | 2         | 0.11%   |
| Jieli Technology                       | 2         | 0.11%   |
| Intel                                  | 2         | 0.11%   |
| icSpring                               | 2         | 0.11%   |
| Genesys Logic                          | 2         | 0.11%   |
| Generalplus Technology                 | 2         | 0.11%   |
| DigiTech                               | 2         | 0.11%   |
| Creative Technology                    | 2         | 0.11%   |
| Alpha Imaging Technology               | 2         | 0.11%   |
| Xiongmai                               | 1         | 0.06%   |
| Xiaomi                                 | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                   | 108       | 6.07%   |
| Chicony integrated camera                                       | 70        | 3.93%   |
| Realtek Integrated_Webcam_HD                                    | 69        | 3.88%   |
| IMC Networks Integrated Camera                                  | 58        | 3.26%   |
| Chicony HD WebCam                                               | 57        | 3.2%    |
| Sunplus Integrated_Webcam_HD                                    | 36        | 2.02%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 35        | 1.97%   |
| Chicony HP HD Camera                                            | 30        | 1.69%   |
| Chicony USB2.0 Camera                                           | 25        | 1.4%    |
| Acer Integrated Camera                                          | 21        | 1.18%   |
| Apple FaceTime HD Camera                                        | 19        | 1.07%   |
| Acer BisonCam,NB Pro                                            | 19        | 1.07%   |
| Chicony USB 2.0 Camera                                          | 18        | 1.01%   |
| Bison Integrated Camera                                         | 18        | 1.01%   |
| Chicony TOSHIBA Web Camera - HD                                 | 17        | 0.96%   |
| Lite-On HP HD Camera                                            | 16        | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera             | 16        | 0.9%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                        | 15        | 0.84%   |
| Sunplus HD WebCam                                               | 15        | 0.84%   |
| Chicony HP Wide Vision HD Camera                                | 14        | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 14        | 0.79%   |
| Microdia Integrated Webcam                                      | 13        | 0.73%   |
| Apple Built-in iSight                                           | 13        | 0.73%   |
| Syntek Integrated Camera                                        | 12        | 0.67%   |
| Quanta HD User Facing                                           | 12        | 0.67%   |
| Lite-On Integrated Camera                                       | 12        | 0.67%   |
| IMC Networks Integrated Webcam                                  | 12        | 0.67%   |
| Chicony Integrated HP HD Webcam                                 | 12        | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam             | 12        | 0.67%   |
| Bison SunplusIT Integrated Camera                               | 12        | 0.67%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 11        | 0.62%   |
| Quanta HP HD Camera                                             | 11        | 0.62%   |
| Primax HP HD Webcam [Fixed]                                     | 11        | 0.62%   |
| IMC Networks USB2.0 UVC HD Webcam                               | 11        | 0.62%   |
| Chicony USB2.0 HD UVC WebCam                                    | 11        | 0.62%   |
| Chicony FJ Camera                                               | 11        | 0.62%   |
| Suyin HP TrueVision HD                                          | 10        | 0.56%   |
| Quanta HP Wide Vision HD Camera                                 | 10        | 0.56%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 10        | 0.56%   |
| Chicony HP HD Webcam [Fixed]                                    | 10        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 146       | 35.52%  |
| Synaptics                          | 114       | 27.74%  |
| Shenzhen Goodix Technology         | 50        | 12.17%  |
| AuthenTec                          | 32        | 7.79%   |
| Elan Microelectronics              | 24        | 5.84%   |
| LighTuning Technology              | 22        | 5.35%   |
| Upek                               | 19        | 4.62%   |
| STMicroelectronics                 | 3         | 0.73%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.24%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 48        | 11.68%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 40        | 9.73%   |
| Shenzhen Goodix  FingerPrint Device                                        | 23        | 5.6%    |
| Validity Sensors VFS491                                                    | 19        | 4.62%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 19        | 4.62%   |
| Shenzhen Goodix FingerPrint                                                | 19        | 4.62%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 3.41%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 3.41%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 13        | 3.16%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 12        | 2.92%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 2.92%   |
| Elan ELAN:Fingerprint                                                      | 12        | 2.92%   |
| Elan ELAN:ARM-M4                                                           | 12        | 2.92%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 12        | 2.92%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 11        | 2.68%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 11        | 2.68%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 2.19%   |
| AuthenTec AES2810                                                          | 9         | 2.19%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 1.95%   |
| Unknown                                                                    | 7         | 1.7%    |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.46%   |
| Synaptics UWP WBDI                                                         | 6         | 1.46%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.46%   |
| AuthenTec AES1600                                                          | 6         | 1.46%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 1.22%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 1.22%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 1.22%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 0.97%   |
| Synaptics WBDI Device                                                      | 4         | 0.97%   |
| Synaptics WBDI                                                             | 4         | 0.97%   |
| Synaptics  WBDI                                                            | 4         | 0.97%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 0.73%   |
| Synaptics UWP WBDI Device                                                  | 3         | 0.73%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.73%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 0.73%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.73%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.73%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.49%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.49%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.49%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 107       | 53.5%   |
| Alcor Micro               | 52        | 26%     |
| O2 Micro                  | 23        | 11.5%   |
| Upek                      | 6         | 3%      |
| Lenovo                    | 6         | 3%      |
| Gemalto (was Gemplus)     | 2         | 1%      |
| Yubico.com                | 1         | 0.5%    |
| SCM Microsystems          | 1         | 0.5%    |
| Fujitsu Siemens Computers | 1         | 0.5%    |
| Advanced Card Systems     | 1         | 0.5%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 52        | 26%     |
| Broadcom BCM5880 Secure Applications Processor                               | 35        | 17.5%   |
| Broadcom 58200                                                               | 29        | 14.5%   |
| Broadcom 5880                                                                | 22        | 11%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 10.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 21        | 10.5%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 3%      |
| Lenovo Integrated Smart Card Reader                                          | 6         | 3%      |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1%      |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.5%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.5%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.5%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.5%    |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.5%    |
| Advanced Card Systems ACR122U                                                | 1         | 0.5%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1197      | 57.36%  |
| 1     | 685       | 32.82%  |
| 2     | 168       | 8.05%   |
| 3     | 27        | 1.29%   |
| 4     | 6         | 0.29%   |
| 5     | 2         | 0.1%    |
| 8     | 1         | 0.05%   |
| 6     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 408       | 37.02%  |
| Graphics card            | 206       | 18.69%  |
| Chipcard                 | 176       | 15.97%  |
| Net/wireless             | 98        | 8.89%   |
| Multimedia controller    | 72        | 6.53%   |
| Camera                   | 33        | 2.99%   |
| Storage                  | 20        | 1.81%   |
| Communication controller | 19        | 1.72%   |
| Bluetooth                | 18        | 1.63%   |
| Card reader              | 13        | 1.18%   |
| Sound                    | 10        | 0.91%   |
| Net/ethernet             | 9         | 0.82%   |
| Flash memory             | 8         | 0.73%   |
| Network                  | 5         | 0.45%   |
| Modem                    | 3         | 0.27%   |
| Storage/nvme             | 1         | 0.09%   |
| Storage/ide              | 1         | 0.09%   |
| Storage/ata              | 1         | 0.09%   |
| Firewire controller      | 1         | 0.09%   |


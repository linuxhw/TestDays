BlackPanther - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for BlackPanther.

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

Total: 3980

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire E1-532               | [84cbdf027b](https://linux-hardware.org/?probe=84cbdf027b) | Aug 12, 2023 |
| HP            | ProBook 650 G2              | [8fbbf1483d](https://linux-hardware.org/?probe=8fbbf1483d) | Aug 09, 2023 |
| HP            | Notebook                    | [59e006f729](https://linux-hardware.org/?probe=59e006f729) | Aug 09, 2023 |
| ASUSTek       | X540LJ                      | [e28870563c](https://linux-hardware.org/?probe=e28870563c) | Aug 09, 2023 |
| HP            | ProBook 650 G2              | [78859b39fb](https://linux-hardware.org/?probe=78859b39fb) | Aug 09, 2023 |
| HP            | Notebook                    | [5cfbf14023](https://linux-hardware.org/?probe=5cfbf14023) | Aug 07, 2023 |
| ASUSTek       | X540SA                      | [db952b584b](https://linux-hardware.org/?probe=db952b584b) | Aug 07, 2023 |
| Dell          | Inspiron 15-3567            | [cf49ab1496](https://linux-hardware.org/?probe=cf49ab1496) | Aug 04, 2023 |
| Dell          | Inspiron 15-3567            | [49e694bb22](https://linux-hardware.org/?probe=49e694bb22) | Aug 04, 2023 |
| Lenovo        | V15-ADA 82C7                | [effe3c3d6d](https://linux-hardware.org/?probe=effe3c3d6d) | Aug 04, 2023 |
| HP            | Laptop 17-ak0xx             | [30b14bc4f6](https://linux-hardware.org/?probe=30b14bc4f6) | Aug 04, 2023 |
| HP            | Laptop 17-ak0xx             | [0e36ac41e4](https://linux-hardware.org/?probe=0e36ac41e4) | Aug 04, 2023 |
| HP            | Pavilion 17                 | [e0cf9c4fce](https://linux-hardware.org/?probe=e0cf9c4fce) | Aug 03, 2023 |
| Acer          | Aspire ES1-533              | [4c45ace98b](https://linux-hardware.org/?probe=4c45ace98b) | Aug 03, 2023 |
| Acer          | Aspire ES1-533              | [b7ffeb681e](https://linux-hardware.org/?probe=b7ffeb681e) | Aug 03, 2023 |
| ASUSTek       | X541NA                      | [b8ece2fce1](https://linux-hardware.org/?probe=b8ece2fce1) | Aug 03, 2023 |
| HP            | Pavilion 17                 | [abad0a7963](https://linux-hardware.org/?probe=abad0a7963) | Aug 02, 2023 |
| HP            | Notebook                    | [b73fa31837](https://linux-hardware.org/?probe=b73fa31837) | Aug 02, 2023 |
| Lenovo        | Z50-75 80EC                 | [0b22fa6444](https://linux-hardware.org/?probe=0b22fa6444) | Aug 02, 2023 |
| HP            | Notebook                    | [329c725795](https://linux-hardware.org/?probe=329c725795) | Jul 31, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [c3b01ce24d](https://linux-hardware.org/?probe=c3b01ce24d) | Jul 30, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [8e26feba38](https://linux-hardware.org/?probe=8e26feba38) | Jul 30, 2023 |
| Fujitsu       | LIFEBOOK A512               | [7bcd0d7683](https://linux-hardware.org/?probe=7bcd0d7683) | Jul 30, 2023 |
| Dell          | Inspiron 7737               | [6fd92e6150](https://linux-hardware.org/?probe=6fd92e6150) | Jul 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [68d5cb02bf](https://linux-hardware.org/?probe=68d5cb02bf) | Jul 29, 2023 |
| ASUSTek       | X550CL                      | [3c326304ab](https://linux-hardware.org/?probe=3c326304ab) | Jul 29, 2023 |
| ASUSTek       | X550CL                      | [4e19477a40](https://linux-hardware.org/?probe=4e19477a40) | Jul 29, 2023 |
| Fujitsu       | LIFEBOOK A512               | [404f75d04c](https://linux-hardware.org/?probe=404f75d04c) | Jul 28, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [19d341d49d](https://linux-hardware.org/?probe=19d341d49d) | Jul 28, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [a7c322fa40](https://linux-hardware.org/?probe=a7c322fa40) | Jul 28, 2023 |
| Lenovo        | ThinkPad T500 2056CL8       | [180a80b4fe](https://linux-hardware.org/?probe=180a80b4fe) | Jul 26, 2023 |
| Dell          | Latitude E5410              | [e26148754b](https://linux-hardware.org/?probe=e26148754b) | Jul 25, 2023 |
| Toshiba       | Satellite C660              | [11a6a3a607](https://linux-hardware.org/?probe=11a6a3a607) | Jul 23, 2023 |
| Acer          | Aspire ES1-571              | [8f2c838141](https://linux-hardware.org/?probe=8f2c838141) | Jul 22, 2023 |
| ASUSTek       | X550CL                      | [c4da72acde](https://linux-hardware.org/?probe=c4da72acde) | Jul 21, 2023 |
| ASUSTek       | X550CL                      | [2d8ae98d9c](https://linux-hardware.org/?probe=2d8ae98d9c) | Jul 21, 2023 |
| Acer          | Aspire ES1-571              | [e022b7bd64](https://linux-hardware.org/?probe=e022b7bd64) | Jul 21, 2023 |
| Dell          | Inspiron 7737               | [1faafe201d](https://linux-hardware.org/?probe=1faafe201d) | Jul 19, 2023 |
| Acer          | Aspire One 753              | [f2b71747bc](https://linux-hardware.org/?probe=f2b71747bc) | Jul 18, 2023 |
| Acer          | Aspire One 753              | [53d0821b75](https://linux-hardware.org/?probe=53d0821b75) | Jul 18, 2023 |
| Acer          | Aspire 8930                 | [8b9534387b](https://linux-hardware.org/?probe=8b9534387b) | Jul 17, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [b6925518be](https://linux-hardware.org/?probe=b6925518be) | Jul 16, 2023 |
| HP            | EliteBook 8570w             | [05a330fa6c](https://linux-hardware.org/?probe=05a330fa6c) | Jul 16, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [60947b35a4](https://linux-hardware.org/?probe=60947b35a4) | Jul 16, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [856a25b9d5](https://linux-hardware.org/?probe=856a25b9d5) | Jul 16, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [1ccdf38dfa](https://linux-hardware.org/?probe=1ccdf38dfa) | Jul 16, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [71045dea53](https://linux-hardware.org/?probe=71045dea53) | Jul 16, 2023 |
| Lenovo        | ThinkPad R400 7440EL1       | [8cc38e55a2](https://linux-hardware.org/?probe=8cc38e55a2) | Jul 15, 2023 |
| Lenovo        | ThinkPad R400 7440EL1       | [c0101c7ae1](https://linux-hardware.org/?probe=c0101c7ae1) | Jul 15, 2023 |
| Acer          | Aspire 6930G                | [ba12b5ff3e](https://linux-hardware.org/?probe=ba12b5ff3e) | Jul 14, 2023 |
| RM            | Mobile ONE WIDESCREEN       | [34e242c377](https://linux-hardware.org/?probe=34e242c377) | Jul 13, 2023 |
| RM            | Mobile ONE WIDESCREEN       | [bc67d71f5f](https://linux-hardware.org/?probe=bc67d71f5f) | Jul 13, 2023 |
| HP            | EliteBook 8570w             | [5d1ed4c0a4](https://linux-hardware.org/?probe=5d1ed4c0a4) | Jul 12, 2023 |
| Fujitsu       | LIFEBOOK U745               | [c23f2219b4](https://linux-hardware.org/?probe=c23f2219b4) | Jul 12, 2023 |
| Fujitsu       | LIFEBOOK U745               | [e169b67c63](https://linux-hardware.org/?probe=e169b67c63) | Jul 12, 2023 |
| Toshiba       | Satellite C55-A-1NV         | [8528943b9e](https://linux-hardware.org/?probe=8528943b9e) | Jul 11, 2023 |
| Toshiba       | Satellite C55-A-1NV         | [1f9c336539](https://linux-hardware.org/?probe=1f9c336539) | Jul 11, 2023 |
| eMachines     | E725                        | [69e7b54469](https://linux-hardware.org/?probe=69e7b54469) | Jul 10, 2023 |
| eMachines     | E725                        | [307f75ef0a](https://linux-hardware.org/?probe=307f75ef0a) | Jul 09, 2023 |
| Lenovo        | B50-30 20382                | [fe0bc25044](https://linux-hardware.org/?probe=fe0bc25044) | Jul 09, 2023 |
| Lenovo        | B50-30 20382                | [70e2ac254a](https://linux-hardware.org/?probe=70e2ac254a) | Jul 09, 2023 |
| eMachines     | E725                        | [c70b217933](https://linux-hardware.org/?probe=c70b217933) | Jul 08, 2023 |
| Acer          | Aspire One 753              | [f47888ce55](https://linux-hardware.org/?probe=f47888ce55) | Jul 08, 2023 |
| Acer          | Aspire One 753              | [9f56cc566d](https://linux-hardware.org/?probe=9f56cc566d) | Jul 08, 2023 |
| Sony          | VPCYB3V1E                   | [2dd9b76ce0](https://linux-hardware.org/?probe=2dd9b76ce0) | Jul 06, 2023 |
| Acer          | Aspire E5-575G              | [713b52b0c5](https://linux-hardware.org/?probe=713b52b0c5) | Jul 05, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [11537fb0f5](https://linux-hardware.org/?probe=11537fb0f5) | Jul 04, 2023 |
| Acer          | Aspire E5-575G              | [fe616ea0ed](https://linux-hardware.org/?probe=fe616ea0ed) | Jul 03, 2023 |
| Dell          | Inspiron 5558               | [22879dbc9e](https://linux-hardware.org/?probe=22879dbc9e) | Jul 03, 2023 |
| Dell          | Inspiron 5558               | [496b83b6b8](https://linux-hardware.org/?probe=496b83b6b8) | Jul 03, 2023 |
| eMachines     | E725                        | [ca2b670023](https://linux-hardware.org/?probe=ca2b670023) | Jul 03, 2023 |
| Dell          | Inspiron 15-3567            | [efa8ecd790](https://linux-hardware.org/?probe=efa8ecd790) | Jul 03, 2023 |
| Dell          | Inspiron 15-3567            | [72af61849b](https://linux-hardware.org/?probe=72af61849b) | Jul 03, 2023 |
| eMachines     | E725                        | [622425a84f](https://linux-hardware.org/?probe=622425a84f) | Jul 02, 2023 |
| Dell          | Inspiron 15-3567            | [ef1c856eb5](https://linux-hardware.org/?probe=ef1c856eb5) | Jul 02, 2023 |
| HP            | 650                         | [279f48a7df](https://linux-hardware.org/?probe=279f48a7df) | Jul 01, 2023 |
| HP            | Notebook                    | [552c6713e1](https://linux-hardware.org/?probe=552c6713e1) | Jun 30, 2023 |
| Dell          | Inspiron 15-3567            | [d3f7bcfb2c](https://linux-hardware.org/?probe=d3f7bcfb2c) | Jun 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [1efefadbdf](https://linux-hardware.org/?probe=1efefadbdf) | Jun 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e304e9beeb](https://linux-hardware.org/?probe=e304e9beeb) | Jun 27, 2023 |
| Dell          | Inspiron 5558               | [126187748f](https://linux-hardware.org/?probe=126187748f) | Jun 27, 2023 |
| eMachines     | E725                        | [e1ed487442](https://linux-hardware.org/?probe=e1ed487442) | Jun 26, 2023 |
| eMachines     | E725                        | [909f61c87a](https://linux-hardware.org/?probe=909f61c87a) | Jun 26, 2023 |
| HP            | Notebook                    | [ce52423528](https://linux-hardware.org/?probe=ce52423528) | Jun 26, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [604d6b2b6f](https://linux-hardware.org/?probe=604d6b2b6f) | Jun 26, 2023 |
| HP            | ProBook 650 G2              | [d34d125de2](https://linux-hardware.org/?probe=d34d125de2) | Jun 26, 2023 |
| HP            | ProBook 650 G2              | [1858ae62ee](https://linux-hardware.org/?probe=1858ae62ee) | Jun 26, 2023 |
| Dell          | Inspiron 5558               | [43849169cb](https://linux-hardware.org/?probe=43849169cb) | Jun 25, 2023 |
| HP            | EliteBook 2540p             | [2b3a2327fb](https://linux-hardware.org/?probe=2b3a2327fb) | Jun 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [186b2c5cb7](https://linux-hardware.org/?probe=186b2c5cb7) | Jun 24, 2023 |
| Acer          | Aspire A114-31              | [3cb015a09d](https://linux-hardware.org/?probe=3cb015a09d) | Jun 23, 2023 |
| HP            | Notebook                    | [6710ed8c9c](https://linux-hardware.org/?probe=6710ed8c9c) | Jun 21, 2023 |
| Dell          | Latitude E6410              | [1d89edd254](https://linux-hardware.org/?probe=1d89edd254) | Jun 20, 2023 |
| Dell          | Latitude E6410              | [5230b985a8](https://linux-hardware.org/?probe=5230b985a8) | Jun 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [9fa828d2e4](https://linux-hardware.org/?probe=9fa828d2e4) | Jun 20, 2023 |
| Dell          | Latitude E6400              | [9dca1fab41](https://linux-hardware.org/?probe=9dca1fab41) | Jun 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [53b1d3f262](https://linux-hardware.org/?probe=53b1d3f262) | Jun 20, 2023 |
| Dell          | Latitude 7390               | [98d09ed56c](https://linux-hardware.org/?probe=98d09ed56c) | Jun 20, 2023 |
| eMachines     | E725                        | [4317f04272](https://linux-hardware.org/?probe=4317f04272) | Jun 19, 2023 |
| Lenovo        | V15-ADA 82C7                | [0423e23a21](https://linux-hardware.org/?probe=0423e23a21) | Jun 19, 2023 |
| Dell          | Inspiron 7737               | [8ccea52f65](https://linux-hardware.org/?probe=8ccea52f65) | Jun 19, 2023 |
| Dell          | Inspiron 5558               | [a1bb681c50](https://linux-hardware.org/?probe=a1bb681c50) | Jun 17, 2023 |
| ASUSTek       | K54HR                       | [6fd4c94830](https://linux-hardware.org/?probe=6fd4c94830) | Jun 16, 2023 |
| eMachines     | E725                        | [c2ffc64913](https://linux-hardware.org/?probe=c2ffc64913) | Jun 15, 2023 |
| eMachines     | E725                        | [6a88f4f2be](https://linux-hardware.org/?probe=6a88f4f2be) | Jun 14, 2023 |
| Dell          | Latitude 7390               | [aad70ac5b5](https://linux-hardware.org/?probe=aad70ac5b5) | Jun 14, 2023 |
| Dell          | Latitude 7390               | [b718d8d672](https://linux-hardware.org/?probe=b718d8d672) | Jun 14, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [26493eeedc](https://linux-hardware.org/?probe=26493eeedc) | Jun 13, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [03f59dc88a](https://linux-hardware.org/?probe=03f59dc88a) | Jun 13, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [e68c648de4](https://linux-hardware.org/?probe=e68c648de4) | Jun 13, 2023 |
| HP            | Laptop 15-dw1xxx            | [058f5805e3](https://linux-hardware.org/?probe=058f5805e3) | Jun 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [8c939c89a3](https://linux-hardware.org/?probe=8c939c89a3) | Jun 13, 2023 |
| Dell          | Latitude E5520              | [a86c677685](https://linux-hardware.org/?probe=a86c677685) | Jun 13, 2023 |
| HP            | 250 G1                      | [f8406758e3](https://linux-hardware.org/?probe=f8406758e3) | Jun 13, 2023 |
| HP            | 250 G1                      | [477f9bbabd](https://linux-hardware.org/?probe=477f9bbabd) | Jun 13, 2023 |
| HP            | Notebook                    | [aa5016380c](https://linux-hardware.org/?probe=aa5016380c) | Jun 13, 2023 |
| MSI           | GP75 Leopard 9SE            | [9e763f2e63](https://linux-hardware.org/?probe=9e763f2e63) | Jun 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [93fe499e47](https://linux-hardware.org/?probe=93fe499e47) | Jun 12, 2023 |
| Acer          | TravelMate P259-G2-M        | [abc5444c45](https://linux-hardware.org/?probe=abc5444c45) | Jun 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c0d6d68272](https://linux-hardware.org/?probe=c0d6d68272) | Jun 12, 2023 |
| MSI           | GT60 2OC/2OD                | [f5a1226b72](https://linux-hardware.org/?probe=f5a1226b72) | Jun 12, 2023 |
| Lenovo        | ThinkPad X200 74595FG       | [6d6fb0c276](https://linux-hardware.org/?probe=6d6fb0c276) | Jun 12, 2023 |
| Apple         | MacBookAir5,2               | [4b84ec2ade](https://linux-hardware.org/?probe=4b84ec2ade) | Jun 12, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [5286f937d8](https://linux-hardware.org/?probe=5286f937d8) | Jun 11, 2023 |
| Dell          | Latitude E6230              | [c46f103733](https://linux-hardware.org/?probe=c46f103733) | Jun 11, 2023 |
| Dell          | Latitude E6230              | [390606f3f6](https://linux-hardware.org/?probe=390606f3f6) | Jun 11, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [43d52c8efe](https://linux-hardware.org/?probe=43d52c8efe) | Jun 11, 2023 |
| HP            | 250 G1                      | [e229888d41](https://linux-hardware.org/?probe=e229888d41) | Jun 11, 2023 |
| Lenovo        | V15-ADA 82C7                | [aee2df0fb7](https://linux-hardware.org/?probe=aee2df0fb7) | Jun 11, 2023 |
| Dell          | Inspiron 7737               | [eff8eec9d8](https://linux-hardware.org/?probe=eff8eec9d8) | Jun 11, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [068826c25b](https://linux-hardware.org/?probe=068826c25b) | Jun 10, 2023 |
| HP            | 250 G1                      | [1b9c881cae](https://linux-hardware.org/?probe=1b9c881cae) | Jun 10, 2023 |
| HP            | 250 G1                      | [0591407196](https://linux-hardware.org/?probe=0591407196) | Jun 10, 2023 |
| ASUSTek       | K54HR                       | [6eada916c0](https://linux-hardware.org/?probe=6eada916c0) | Jun 10, 2023 |
| Toshiba       | Satellite C660D             | [a6c222681d](https://linux-hardware.org/?probe=a6c222681d) | Jun 09, 2023 |
| Acer          | Aspire 8930                 | [f8eb3278fe](https://linux-hardware.org/?probe=f8eb3278fe) | Jun 09, 2023 |
| Dell          | Inspiron 7737               | [6f7077634a](https://linux-hardware.org/?probe=6f7077634a) | Jun 08, 2023 |
| Lenovo        | ThinkPad X200 74595FG       | [26f1962805](https://linux-hardware.org/?probe=26f1962805) | Jun 07, 2023 |
| HP            | EliteBook 2540p             | [96a6ae8f4d](https://linux-hardware.org/?probe=96a6ae8f4d) | Jun 07, 2023 |
| Apple         | MacBookAir5,2               | [8ef73cacf2](https://linux-hardware.org/?probe=8ef73cacf2) | Jun 07, 2023 |
| HP            | 250 G1                      | [f5c0548f17](https://linux-hardware.org/?probe=f5c0548f17) | Jun 07, 2023 |
| ASUSTek       | K73SJ                       | [a77a12f870](https://linux-hardware.org/?probe=a77a12f870) | Jun 06, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [bb5f9c1964](https://linux-hardware.org/?probe=bb5f9c1964) | Jun 06, 2023 |
| ASUSTek       | X200MA                      | [7c0552ad30](https://linux-hardware.org/?probe=7c0552ad30) | Jun 06, 2023 |
| MSI           | GP75 Leopard 9SE            | [05530e670e](https://linux-hardware.org/?probe=05530e670e) | Jun 06, 2023 |
| HP            | 250 G1                      | [f6cab30981](https://linux-hardware.org/?probe=f6cab30981) | Jun 06, 2023 |
| eMachines     | E725                        | [4e50fbb5a2](https://linux-hardware.org/?probe=4e50fbb5a2) | Jun 05, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [413ef09459](https://linux-hardware.org/?probe=413ef09459) | Jun 05, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [5b7617b9c0](https://linux-hardware.org/?probe=5b7617b9c0) | Jun 05, 2023 |
| MSI           | GT60 2OC/2OD                | [ed3b6abc56](https://linux-hardware.org/?probe=ed3b6abc56) | Jun 05, 2023 |
| Dell          | Latitude E5520              | [ab87df9910](https://linux-hardware.org/?probe=ab87df9910) | Jun 05, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [e1fabecae3](https://linux-hardware.org/?probe=e1fabecae3) | Jun 04, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [66ed048f40](https://linux-hardware.org/?probe=66ed048f40) | Jun 04, 2023 |
| Lenovo        | V15-ADA 82C7                | [0fb6670b07](https://linux-hardware.org/?probe=0fb6670b07) | Jun 03, 2023 |
| ASUSTek       | X540SA                      | [e9e8995d2e](https://linux-hardware.org/?probe=e9e8995d2e) | Jun 03, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [bcf794dd14](https://linux-hardware.org/?probe=bcf794dd14) | Jun 03, 2023 |
| Dell          | Inspiron 5558               | [746c0d0644](https://linux-hardware.org/?probe=746c0d0644) | Jun 03, 2023 |
| Dell          | Vostro 1015                 | [055866f703](https://linux-hardware.org/?probe=055866f703) | Jun 02, 2023 |
| Dell          | Inspiron 5558               | [c747f45c48](https://linux-hardware.org/?probe=c747f45c48) | Jun 02, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [c0d0a7cb50](https://linux-hardware.org/?probe=c0d0a7cb50) | Jun 01, 2023 |
| Fujitsu       | LIFEBOOK A555               | [f7e3bde58c](https://linux-hardware.org/?probe=f7e3bde58c) | Jun 01, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [871cbcbb88](https://linux-hardware.org/?probe=871cbcbb88) | May 31, 2023 |
| Lenovo        | Z50-75 80EC                 | [6dd815a00b](https://linux-hardware.org/?probe=6dd815a00b) | May 31, 2023 |
| Lenovo        | Z50-75 80EC                 | [36767ec389](https://linux-hardware.org/?probe=36767ec389) | May 31, 2023 |
| HP            | Notebook                    | [7d7934f727](https://linux-hardware.org/?probe=7d7934f727) | May 31, 2023 |
| HP            | Notebook                    | [161aaf4150](https://linux-hardware.org/?probe=161aaf4150) | May 31, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [f0d7ab6b7e](https://linux-hardware.org/?probe=f0d7ab6b7e) | May 31, 2023 |
| ASUSTek       | X550CL                      | [ac1e17e897](https://linux-hardware.org/?probe=ac1e17e897) | May 30, 2023 |
| Toshiba       | Satellite M50D-A            | [9f7a16aa7b](https://linux-hardware.org/?probe=9f7a16aa7b) | May 25, 2023 |
| Toshiba       | Satellite M50D-A            | [bbb23b2823](https://linux-hardware.org/?probe=bbb23b2823) | May 25, 2023 |
| Fujitsu       | LIFEBOOK A555               | [920a4901d9](https://linux-hardware.org/?probe=920a4901d9) | May 24, 2023 |
| Lenovo        | V15-ADA 82C7                | [5fff4f66c1](https://linux-hardware.org/?probe=5fff4f66c1) | May 22, 2023 |
| eMachines     | E725                        | [c75d7eb314](https://linux-hardware.org/?probe=c75d7eb314) | May 22, 2023 |
| eMachines     | E725                        | [f32fb866fa](https://linux-hardware.org/?probe=f32fb866fa) | May 22, 2023 |
| Lenovo        | V15-ADA 82C7                | [6e859c48e1](https://linux-hardware.org/?probe=6e859c48e1) | May 21, 2023 |
| Dell          | Inspiron 5558               | [958b40f42c](https://linux-hardware.org/?probe=958b40f42c) | May 21, 2023 |
| Dell          | Inspiron 5558               | [5043ac245f](https://linux-hardware.org/?probe=5043ac245f) | May 21, 2023 |
| Dell          | Inspiron 15-3567            | [7db14b0f6f](https://linux-hardware.org/?probe=7db14b0f6f) | May 20, 2023 |
| eMachines     | E725                        | [517ba05822](https://linux-hardware.org/?probe=517ba05822) | May 19, 2023 |
| Dell          | Latitude D630               | [9526ff1765](https://linux-hardware.org/?probe=9526ff1765) | May 19, 2023 |
| Dell          | Latitude D630               | [7a7497a4b3](https://linux-hardware.org/?probe=7a7497a4b3) | May 18, 2023 |
| HUAWEI        | HVY-WXX9                    | [eb15dc415d](https://linux-hardware.org/?probe=eb15dc415d) | May 18, 2023 |
| HUAWEI        | HVY-WXX9                    | [b30078ae71](https://linux-hardware.org/?probe=b30078ae71) | May 18, 2023 |
| Fujitsu       | LIFEBOOK A555               | [400b91098c](https://linux-hardware.org/?probe=400b91098c) | May 18, 2023 |
| Lenovo        | V15-ADA 82C7                | [6856deb5d7](https://linux-hardware.org/?probe=6856deb5d7) | May 16, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [e228d9926b](https://linux-hardware.org/?probe=e228d9926b) | May 16, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [f286932235](https://linux-hardware.org/?probe=f286932235) | May 15, 2023 |
| Samsung       | R530/R730/P530              | [9f619133b7](https://linux-hardware.org/?probe=9f619133b7) | May 15, 2023 |
| eMachines     | E725                        | [32c12bfb05](https://linux-hardware.org/?probe=32c12bfb05) | May 14, 2023 |
| eMachines     | E725                        | [8768af826f](https://linux-hardware.org/?probe=8768af826f) | May 14, 2023 |
| Lenovo        | G580 20150                  | [f6cf41154f](https://linux-hardware.org/?probe=f6cf41154f) | May 14, 2023 |
| eMachines     | E725                        | [fed9273467](https://linux-hardware.org/?probe=fed9273467) | May 14, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [ae4ee3c43d](https://linux-hardware.org/?probe=ae4ee3c43d) | May 13, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [0ae54cb7c4](https://linux-hardware.org/?probe=0ae54cb7c4) | May 13, 2023 |
| Dell          | Latitude 5480               | [63cd615fa8](https://linux-hardware.org/?probe=63cd615fa8) | May 13, 2023 |
| HP            | Notebook                    | [9840f334f5](https://linux-hardware.org/?probe=9840f334f5) | May 13, 2023 |
| HP            | Notebook                    | [db9aaf4ce9](https://linux-hardware.org/?probe=db9aaf4ce9) | May 13, 2023 |
| eMachines     | E725                        | [52848aa6bd](https://linux-hardware.org/?probe=52848aa6bd) | May 13, 2023 |
| Toshiba       | Satellite C55-A-1NV         | [d06987bfd6](https://linux-hardware.org/?probe=d06987bfd6) | May 12, 2023 |
| HP            | Notebook                    | [bc25329bce](https://linux-hardware.org/?probe=bc25329bce) | May 12, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [8bad0045f6](https://linux-hardware.org/?probe=8bad0045f6) | May 12, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [78e2c8b948](https://linux-hardware.org/?probe=78e2c8b948) | May 12, 2023 |
| HP            | Notebook                    | [d527d781af](https://linux-hardware.org/?probe=d527d781af) | May 11, 2023 |
| Dell          | Latitude 7390               | [ab2ea4f7a0](https://linux-hardware.org/?probe=ab2ea4f7a0) | May 11, 2023 |
| eMachines     | E725                        | [94e51437e6](https://linux-hardware.org/?probe=94e51437e6) | May 11, 2023 |
| Sony          | VPCEH2J1E                   | [fb307bc1bb](https://linux-hardware.org/?probe=fb307bc1bb) | May 11, 2023 |
| Lenovo        | V15-ADA 82C7                | [0c8d19bdf0](https://linux-hardware.org/?probe=0c8d19bdf0) | May 10, 2023 |
| Dell          | Inspiron 5558               | [dbc75c5600](https://linux-hardware.org/?probe=dbc75c5600) | May 10, 2023 |
| Dell          | Inspiron 5558               | [396be908b5](https://linux-hardware.org/?probe=396be908b5) | May 10, 2023 |
| HP            | 250 G1                      | [09879bd463](https://linux-hardware.org/?probe=09879bd463) | May 10, 2023 |
| Apple         | MacBookAir5,2               | [bd3934d526](https://linux-hardware.org/?probe=bd3934d526) | May 10, 2023 |
| Fujitsu       | LIFEBOOK U745               | [7a97cdf93b](https://linux-hardware.org/?probe=7a97cdf93b) | May 09, 2023 |
| HP            | Pavilion dv6                | [733703c761](https://linux-hardware.org/?probe=733703c761) | May 09, 2023 |
| Dell          | Inspiron 7737               | [f900658289](https://linux-hardware.org/?probe=f900658289) | May 09, 2023 |
| Packard Be... | EasyNote TK36               | [18f7e68fb1](https://linux-hardware.org/?probe=18f7e68fb1) | May 09, 2023 |
| Acer          | V5-131                      | [d68eaead66](https://linux-hardware.org/?probe=d68eaead66) | May 08, 2023 |
| Lenovo        | G570 20079                  | [bd15eaa1e6](https://linux-hardware.org/?probe=bd15eaa1e6) | May 08, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [ad9af07a7c](https://linux-hardware.org/?probe=ad9af07a7c) | May 08, 2023 |
| eMachines     | E725                        | [bb9c7992f8](https://linux-hardware.org/?probe=bb9c7992f8) | May 08, 2023 |
| HP            | Laptop 15-dw1xxx            | [1f677501c0](https://linux-hardware.org/?probe=1f677501c0) | May 07, 2023 |
| HP            | 650                         | [3ece9ca18a](https://linux-hardware.org/?probe=3ece9ca18a) | May 07, 2023 |
| Acer          | TravelMate P215-52          | [b76e0e7397](https://linux-hardware.org/?probe=b76e0e7397) | May 06, 2023 |
| Acer          | TravelMate P215-52          | [5cad7b7e28](https://linux-hardware.org/?probe=5cad7b7e28) | May 06, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [a7ef6c976c](https://linux-hardware.org/?probe=a7ef6c976c) | May 06, 2023 |
| ASUSTek       | K53BY                       | [6a9ae368ba](https://linux-hardware.org/?probe=6a9ae368ba) | May 06, 2023 |
| eMachines     | E725                        | [15807b1086](https://linux-hardware.org/?probe=15807b1086) | May 06, 2023 |
| eMachines     | E725                        | [290d356d4c](https://linux-hardware.org/?probe=290d356d4c) | May 05, 2023 |
| Acer          | Aspire A114-31              | [a7e0c2d3b6](https://linux-hardware.org/?probe=a7e0c2d3b6) | May 05, 2023 |
| Fujitsu       | LIFEBOOK A555               | [9640ef7fa5](https://linux-hardware.org/?probe=9640ef7fa5) | May 05, 2023 |
| Toshiba       | Satellite U300              | [470632e542](https://linux-hardware.org/?probe=470632e542) | May 05, 2023 |
| Lenovo        | ThinkPad T500 2056CL8       | [df56d361ef](https://linux-hardware.org/?probe=df56d361ef) | May 05, 2023 |
| ASUSTek       | X550CC                      | [0e338f138d](https://linux-hardware.org/?probe=0e338f138d) | May 04, 2023 |
| ASUSTek       | K54HR                       | [4114d6e81c](https://linux-hardware.org/?probe=4114d6e81c) | May 04, 2023 |
| Sony          | VPCEH2J1E                   | [c9b6063699](https://linux-hardware.org/?probe=c9b6063699) | May 04, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | [aaad7b3a55](https://linux-hardware.org/?probe=aaad7b3a55) | May 04, 2023 |
| Lenovo        | ThinkPad X200 74595FG       | [45035a5981](https://linux-hardware.org/?probe=45035a5981) | May 04, 2023 |
| ASUSTek       | K54HR                       | [77cbfa62cd](https://linux-hardware.org/?probe=77cbfa62cd) | May 04, 2023 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | [438c1a31ea](https://linux-hardware.org/?probe=438c1a31ea) | May 04, 2023 |
| MSI           | GT60 2OC/2OD                | [8754e79840](https://linux-hardware.org/?probe=8754e79840) | May 04, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [182df1bb15](https://linux-hardware.org/?probe=182df1bb15) | May 04, 2023 |
| MSI           | GP75 Leopard 9SE            | [425ecbf896](https://linux-hardware.org/?probe=425ecbf896) | May 04, 2023 |
| Acer          | Aspire 8930                 | [6e2629de4d](https://linux-hardware.org/?probe=6e2629de4d) | May 03, 2023 |
| Lenovo        | E50-80 80J2                 | [c82dd5d579](https://linux-hardware.org/?probe=c82dd5d579) | May 03, 2023 |
| Dell          | Latitude E5520              | [0861e85947](https://linux-hardware.org/?probe=0861e85947) | May 03, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [7e731cb85c](https://linux-hardware.org/?probe=7e731cb85c) | May 03, 2023 |
| ASUSTek       | 1001PX                      | [7a04e30859](https://linux-hardware.org/?probe=7a04e30859) | May 03, 2023 |
| ASUSTek       | X200MA                      | [31e08853ae](https://linux-hardware.org/?probe=31e08853ae) | May 03, 2023 |
| Lenovo        | V15-ADA 82C7                | [c8a19f5567](https://linux-hardware.org/?probe=c8a19f5567) | May 02, 2023 |
| Fujitsu       | LIFEBOOK A555               | [2280876e20](https://linux-hardware.org/?probe=2280876e20) | May 02, 2023 |
| Dell          | Inspiron 7737               | [9fcb4f708c](https://linux-hardware.org/?probe=9fcb4f708c) | May 02, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [31e13940be](https://linux-hardware.org/?probe=31e13940be) | May 01, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | [96a8ba3062](https://linux-hardware.org/?probe=96a8ba3062) | May 01, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | [856577ad04](https://linux-hardware.org/?probe=856577ad04) | May 01, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [f84a692777](https://linux-hardware.org/?probe=f84a692777) | Apr 30, 2023 |
| eMachines     | E725                        | [282c0c9f11](https://linux-hardware.org/?probe=282c0c9f11) | Apr 30, 2023 |
| eMachines     | E725                        | [25da91560d](https://linux-hardware.org/?probe=25da91560d) | Apr 30, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | [25c6042b4e](https://linux-hardware.org/?probe=25c6042b4e) | Apr 30, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | [230f3dd04b](https://linux-hardware.org/?probe=230f3dd04b) | Apr 30, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [9d5cd21a8f](https://linux-hardware.org/?probe=9d5cd21a8f) | Apr 30, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [9bb7a9b712](https://linux-hardware.org/?probe=9bb7a9b712) | Apr 30, 2023 |
| Acer          | Aspire 5110                 | [b43b059257](https://linux-hardware.org/?probe=b43b059257) | Apr 28, 2023 |
| Dell          | Inspiron 5558               | [ada78ae33d](https://linux-hardware.org/?probe=ada78ae33d) | Apr 28, 2023 |
| Dell          | Inspiron 5558               | [9c2dd52f1e](https://linux-hardware.org/?probe=9c2dd52f1e) | Apr 28, 2023 |
| eMachines     | E725                        | [668de483ca](https://linux-hardware.org/?probe=668de483ca) | Apr 27, 2023 |
| Dell          | Latitude E5410              | [1efb62110c](https://linux-hardware.org/?probe=1efb62110c) | Apr 27, 2023 |
| Dell          | Latitude E5410              | [02be2c8f0b](https://linux-hardware.org/?probe=02be2c8f0b) | Apr 26, 2023 |
| Dell          | Inspiron 5558               | [9dd9301581](https://linux-hardware.org/?probe=9dd9301581) | Apr 26, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [6b9130ca88](https://linux-hardware.org/?probe=6b9130ca88) | Apr 23, 2023 |
| Dell          | Latitude E6230              | [3ec9acadaa](https://linux-hardware.org/?probe=3ec9acadaa) | Apr 23, 2023 |
| Dell          | Latitude E6230              | [8114b606fb](https://linux-hardware.org/?probe=8114b606fb) | Apr 23, 2023 |
| Lenovo        | ThinkPad T420 4236B87       | [f855722ff3](https://linux-hardware.org/?probe=f855722ff3) | Apr 23, 2023 |
| Dell          | Inspiron 5558               | [174aa789ca](https://linux-hardware.org/?probe=174aa789ca) | Apr 22, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [dfbfce9d2e](https://linux-hardware.org/?probe=dfbfce9d2e) | Apr 21, 2023 |
| Sony          | VPCS13V9E                   | [c0f35fa0d2](https://linux-hardware.org/?probe=c0f35fa0d2) | Apr 21, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [66f95f2851](https://linux-hardware.org/?probe=66f95f2851) | Apr 21, 2023 |
| Dell          | Latitude D630               | [4e4c4f519b](https://linux-hardware.org/?probe=4e4c4f519b) | Apr 18, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [bd73c6ceb9](https://linux-hardware.org/?probe=bd73c6ceb9) | Apr 18, 2023 |
| Fujitsu       | LIFEBOOK U745               | [fd7551020f](https://linux-hardware.org/?probe=fd7551020f) | Apr 17, 2023 |
| MSI           | GT60 2OC/2OD                | [2a389c9c58](https://linux-hardware.org/?probe=2a389c9c58) | Apr 16, 2023 |
| MSI           | GT60 2OC/2OD                | [af0678336d](https://linux-hardware.org/?probe=af0678336d) | Apr 16, 2023 |
| Sony          | VPCS13V9E                   | [40d1573897](https://linux-hardware.org/?probe=40d1573897) | Apr 16, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [f9b8914504](https://linux-hardware.org/?probe=f9b8914504) | Apr 15, 2023 |
| Fujitsu       | LIFEBOOK U745               | [3c0ca40bc5](https://linux-hardware.org/?probe=3c0ca40bc5) | Apr 15, 2023 |
| Toshiba       | Satellite M50D-A            | [17fc6af63a](https://linux-hardware.org/?probe=17fc6af63a) | Apr 15, 2023 |
| eMachines     | E725                        | [bd87462ced](https://linux-hardware.org/?probe=bd87462ced) | Apr 13, 2023 |
| Lenovo        | ThinkPad T420 4236B87       | [6d2971f926](https://linux-hardware.org/?probe=6d2971f926) | Apr 13, 2023 |
| eMachines     | E725                        | [7cd5cba939](https://linux-hardware.org/?probe=7cd5cba939) | Apr 13, 2023 |
| THD           | PX1 01                      | [c2c6b63123](https://linux-hardware.org/?probe=c2c6b63123) | Apr 12, 2023 |
| THD           | PX1 01                      | [f4efc1c20d](https://linux-hardware.org/?probe=f4efc1c20d) | Apr 12, 2023 |
| Dell          | Latitude D630               | [8c211bb7c5](https://linux-hardware.org/?probe=8c211bb7c5) | Apr 12, 2023 |
| Dell          | Inspiron M5030              | [a5dd0e262b](https://linux-hardware.org/?probe=a5dd0e262b) | Apr 10, 2023 |
| Dell          | Inspiron M5030              | [03fb4c2b22](https://linux-hardware.org/?probe=03fb4c2b22) | Apr 10, 2023 |
| Dell          | Inspiron 5558               | [57ed286290](https://linux-hardware.org/?probe=57ed286290) | Apr 09, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [ae224a45a1](https://linux-hardware.org/?probe=ae224a45a1) | Apr 06, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [a451cfcce3](https://linux-hardware.org/?probe=a451cfcce3) | Apr 05, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [1e40d6be20](https://linux-hardware.org/?probe=1e40d6be20) | Apr 04, 2023 |
| HP            | Notebook                    | [d8951b66b8](https://linux-hardware.org/?probe=d8951b66b8) | Apr 03, 2023 |
| HP            | Notebook                    | [05bdafdb5a](https://linux-hardware.org/?probe=05bdafdb5a) | Apr 03, 2023 |
| HP            | Notebook                    | [7b9f1f44c9](https://linux-hardware.org/?probe=7b9f1f44c9) | Mar 31, 2023 |
| HP            | Notebook                    | [ad90621225](https://linux-hardware.org/?probe=ad90621225) | Mar 31, 2023 |
| Dell          | Inspiron 5558               | [796d0b6775](https://linux-hardware.org/?probe=796d0b6775) | Mar 28, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | [bc301a57a0](https://linux-hardware.org/?probe=bc301a57a0) | Mar 27, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | [e31b586083](https://linux-hardware.org/?probe=e31b586083) | Mar 27, 2023 |
| Dell          | Inspiron 5558               | [fd675e2bf8](https://linux-hardware.org/?probe=fd675e2bf8) | Mar 27, 2023 |
| ASUSTek       | X540SA                      | [b2586a8e30](https://linux-hardware.org/?probe=b2586a8e30) | Mar 27, 2023 |
| ASUSTek       | X540SA                      | [b165f6aa7a](https://linux-hardware.org/?probe=b165f6aa7a) | Mar 27, 2023 |
| Toshiba       | Satellite L650              | [5006536f60](https://linux-hardware.org/?probe=5006536f60) | Mar 27, 2023 |
| eMachines     | E725                        | [5212ab8375](https://linux-hardware.org/?probe=5212ab8375) | Mar 26, 2023 |
| eMachines     | E725                        | [8e1945a2c2](https://linux-hardware.org/?probe=8e1945a2c2) | Mar 26, 2023 |
| Dell          | Latitude 5480               | [a663d3bc84](https://linux-hardware.org/?probe=a663d3bc84) | Mar 26, 2023 |
| Lenovo        | G570 20079                  | [ed6328937a](https://linux-hardware.org/?probe=ed6328937a) | Mar 24, 2023 |
| ASUSTek       | X540SA                      | [bbb8b8bc48](https://linux-hardware.org/?probe=bbb8b8bc48) | Mar 23, 2023 |
| eMachines     | E725                        | [a5d9ff191b](https://linux-hardware.org/?probe=a5d9ff191b) | Mar 23, 2023 |
| eMachines     | E725                        | [4204fbff83](https://linux-hardware.org/?probe=4204fbff83) | Mar 23, 2023 |
| ASUSTek       | X540SA                      | [7216fd6d18](https://linux-hardware.org/?probe=7216fd6d18) | Mar 22, 2023 |
| THD           | PX1 01                      | [d210243a53](https://linux-hardware.org/?probe=d210243a53) | Mar 20, 2023 |
| THD           | PX1 01                      | [246c888564](https://linux-hardware.org/?probe=246c888564) | Mar 20, 2023 |
| HP            | ProBook 6470b               | [dd23ab1a2e](https://linux-hardware.org/?probe=dd23ab1a2e) | Mar 19, 2023 |
| Dell          | Inspiron 5558               | [79324bb5ca](https://linux-hardware.org/?probe=79324bb5ca) | Mar 19, 2023 |
| Dell          | Inspiron 5558               | [aad9ecc316](https://linux-hardware.org/?probe=aad9ecc316) | Mar 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c89c2e1369](https://linux-hardware.org/?probe=c89c2e1369) | Mar 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [31299394e0](https://linux-hardware.org/?probe=31299394e0) | Mar 18, 2023 |
| Toshiba       | Satellite C50-B             | [338da8730f](https://linux-hardware.org/?probe=338da8730f) | Mar 18, 2023 |
| HP            | Notebook                    | [aa27725a50](https://linux-hardware.org/?probe=aa27725a50) | Mar 18, 2023 |
| HP            | Laptop 17-ak0xx             | [32fbf8242d](https://linux-hardware.org/?probe=32fbf8242d) | Mar 17, 2023 |
| HP            | EliteBook 2570p             | [374bab39d7](https://linux-hardware.org/?probe=374bab39d7) | Mar 17, 2023 |
| Dell          | Inspiron 5558               | [b0fa0d95b6](https://linux-hardware.org/?probe=b0fa0d95b6) | Mar 17, 2023 |
| Dell          | Inspiron 5558               | [871677af38](https://linux-hardware.org/?probe=871677af38) | Mar 17, 2023 |
| eMachines     | E725                        | [0ea3d3a0ca](https://linux-hardware.org/?probe=0ea3d3a0ca) | Mar 17, 2023 |
| MSI           | CR500                       | [28eeb3bd71](https://linux-hardware.org/?probe=28eeb3bd71) | Mar 16, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [d7fbdbbc9f](https://linux-hardware.org/?probe=d7fbdbbc9f) | Mar 15, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [34a0e74a78](https://linux-hardware.org/?probe=34a0e74a78) | Mar 15, 2023 |
| Lenovo        | G570 20079                  | [aad6765ba3](https://linux-hardware.org/?probe=aad6765ba3) | Mar 14, 2023 |
| HP            | Laptop 17-ak0xx             | [0acca6eb92](https://linux-hardware.org/?probe=0acca6eb92) | Mar 14, 2023 |
| ASUSTek       | X551CA                      | [08924a17f9](https://linux-hardware.org/?probe=08924a17f9) | Mar 14, 2023 |
| ASUSTek       | X551CA                      | [ba5c82bc14](https://linux-hardware.org/?probe=ba5c82bc14) | Mar 14, 2023 |
| eMachines     | E725                        | [9a49d6defc](https://linux-hardware.org/?probe=9a49d6defc) | Mar 12, 2023 |
| HP            | ProBook 650 G2              | [2eb6d39ced](https://linux-hardware.org/?probe=2eb6d39ced) | Mar 12, 2023 |
| HP            | ProBook 650 G2              | [01f61fad51](https://linux-hardware.org/?probe=01f61fad51) | Mar 12, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [eca94a98c0](https://linux-hardware.org/?probe=eca94a98c0) | Mar 09, 2023 |
| eMachines     | E725                        | [a4a1665906](https://linux-hardware.org/?probe=a4a1665906) | Mar 09, 2023 |
| eMachines     | E725                        | [8efce0fe6f](https://linux-hardware.org/?probe=8efce0fe6f) | Mar 08, 2023 |
| HP            | Laptop 17-ak0xx             | [cda5fafaf9](https://linux-hardware.org/?probe=cda5fafaf9) | Mar 07, 2023 |
| HP            | Laptop 17-ak0xx             | [c27eecca48](https://linux-hardware.org/?probe=c27eecca48) | Mar 07, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [5f336adb00](https://linux-hardware.org/?probe=5f336adb00) | Mar 07, 2023 |
| Toshiba       | Satellite L650              | [ee9717cba3](https://linux-hardware.org/?probe=ee9717cba3) | Mar 07, 2023 |
| Toshiba       | Satellite L650              | [77f0d6b014](https://linux-hardware.org/?probe=77f0d6b014) | Mar 07, 2023 |
| Toshiba       | Satellite L650              | [267c62f49a](https://linux-hardware.org/?probe=267c62f49a) | Mar 07, 2023 |
| Alcor         | SnugBook Q series           | [3b3c4fd9fd](https://linux-hardware.org/?probe=3b3c4fd9fd) | Mar 05, 2023 |
| HP            | ProBook 650 G2              | [886fdbe7c9](https://linux-hardware.org/?probe=886fdbe7c9) | Mar 05, 2023 |
| HP            | ProBook 650 G2              | [2fdc151d2f](https://linux-hardware.org/?probe=2fdc151d2f) | Mar 05, 2023 |
| Lenovo        | Y50-70 20378                | [c564adb32c](https://linux-hardware.org/?probe=c564adb32c) | Mar 04, 2023 |
| HP            | 650                         | [f595da7b8c](https://linux-hardware.org/?probe=f595da7b8c) | Mar 04, 2023 |
| HP            | 650                         | [9d0b38c967](https://linux-hardware.org/?probe=9d0b38c967) | Mar 04, 2023 |
| ASUSTek       | X540SA                      | [497c564d49](https://linux-hardware.org/?probe=497c564d49) | Mar 01, 2023 |
| ASUSTek       | X540SA                      | [b2c4dbb868](https://linux-hardware.org/?probe=b2c4dbb868) | Mar 01, 2023 |
| Acer          | Nitro AN515-51              | [984b6e660d](https://linux-hardware.org/?probe=984b6e660d) | Feb 28, 2023 |
| HP            | ProBook 650 G2              | [a9a8184201](https://linux-hardware.org/?probe=a9a8184201) | Feb 27, 2023 |
| HP            | ProBook 650 G2              | [07f46e8e62](https://linux-hardware.org/?probe=07f46e8e62) | Feb 27, 2023 |
| Acer          | Nitro AN515-51              | [e5fa16c859](https://linux-hardware.org/?probe=e5fa16c859) | Feb 25, 2023 |
| HP            | Unknown                     | [18a8d556cb](https://linux-hardware.org/?probe=18a8d556cb) | Feb 25, 2023 |
| HP            | Unknown                     | [dc26b08a65](https://linux-hardware.org/?probe=dc26b08a65) | Feb 25, 2023 |
| HP            | Laptop 15-dw1xxx            | [bf47e38ec4](https://linux-hardware.org/?probe=bf47e38ec4) | Feb 22, 2023 |
| Acer          | Nitro AN515-51              | [c2be84fb6c](https://linux-hardware.org/?probe=c2be84fb6c) | Feb 21, 2023 |
| HP            | Laptop 17-ak0xx             | [d282ac975d](https://linux-hardware.org/?probe=d282ac975d) | Feb 21, 2023 |
| eMachines     | E725                        | [d982b1aa72](https://linux-hardware.org/?probe=d982b1aa72) | Feb 20, 2023 |
| Acer          | Nitro AN515-51              | [5df682e5d6](https://linux-hardware.org/?probe=5df682e5d6) | Feb 20, 2023 |
| ASUSTek       | K52F                        | [2cbb8f3f38](https://linux-hardware.org/?probe=2cbb8f3f38) | Feb 20, 2023 |
| HP            | Laptop 15-dw1xxx            | [22dfb58516](https://linux-hardware.org/?probe=22dfb58516) | Feb 19, 2023 |
| HP            | ProBook 650 G2              | [58ca93166c](https://linux-hardware.org/?probe=58ca93166c) | Feb 18, 2023 |
| HP            | ProBook 650 G2              | [9ab628bcf2](https://linux-hardware.org/?probe=9ab628bcf2) | Feb 18, 2023 |
| HP            | ProBook 650 G2              | [33d9c73cb9](https://linux-hardware.org/?probe=33d9c73cb9) | Feb 17, 2023 |
| Dell          | Inspiron 5558               | [40f71233c4](https://linux-hardware.org/?probe=40f71233c4) | Feb 17, 2023 |
| Dell          | Inspiron 5558               | [44e9817292](https://linux-hardware.org/?probe=44e9817292) | Feb 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a4f7bc0d84](https://linux-hardware.org/?probe=a4f7bc0d84) | Feb 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a6bde6db60](https://linux-hardware.org/?probe=a6bde6db60) | Feb 17, 2023 |
| Fujitsu       | LIFEBOOK U745               | [4f0e88ce52](https://linux-hardware.org/?probe=4f0e88ce52) | Feb 16, 2023 |
| Fujitsu       | LIFEBOOK U745               | [eac8d6ab9d](https://linux-hardware.org/?probe=eac8d6ab9d) | Feb 16, 2023 |
| HP            | 250 G1                      | [a673746c67](https://linux-hardware.org/?probe=a673746c67) | Feb 16, 2023 |
| HP            | 250 G1                      | [cc5e272ca9](https://linux-hardware.org/?probe=cc5e272ca9) | Feb 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [33b1f65ec0](https://linux-hardware.org/?probe=33b1f65ec0) | Feb 15, 2023 |
| Lenovo        | Z710 20250                  | [7b40745c7f](https://linux-hardware.org/?probe=7b40745c7f) | Feb 14, 2023 |
| Lenovo        | Z710 20250                  | [903deba17a](https://linux-hardware.org/?probe=903deba17a) | Feb 14, 2023 |
| HP            | Pavilion dv5                | [fd6bd7275b](https://linux-hardware.org/?probe=fd6bd7275b) | Feb 14, 2023 |
| Acer          | TravelMate 8571             | [609cc404fb](https://linux-hardware.org/?probe=609cc404fb) | Feb 12, 2023 |
| HP            | Compaq 6910p                | [328acaf5ee](https://linux-hardware.org/?probe=328acaf5ee) | Feb 12, 2023 |
| ASUSTek       | K52F                        | [ee35b00a7e](https://linux-hardware.org/?probe=ee35b00a7e) | Feb 12, 2023 |
| ASUSTek       | K52F                        | [364c41f9aa](https://linux-hardware.org/?probe=364c41f9aa) | Feb 11, 2023 |
| Dell          | Latitude E6230              | [d0a04b130a](https://linux-hardware.org/?probe=d0a04b130a) | Feb 09, 2023 |
| Dell          | Latitude E6230              | [11a1ba46f3](https://linux-hardware.org/?probe=11a1ba46f3) | Feb 09, 2023 |
| HP            | Unknown                     | [eb01c0393d](https://linux-hardware.org/?probe=eb01c0393d) | Feb 07, 2023 |
| HP            | Unknown                     | [db607a1e03](https://linux-hardware.org/?probe=db607a1e03) | Feb 07, 2023 |
| Dell          | Latitude D630               | [a1ea4874cf](https://linux-hardware.org/?probe=a1ea4874cf) | Feb 03, 2023 |
| Toshiba       | Satellite C660              | [9cabffbc86](https://linux-hardware.org/?probe=9cabffbc86) | Feb 03, 2023 |
| Dell          | Latitude D630               | [7f34868246](https://linux-hardware.org/?probe=7f34868246) | Feb 02, 2023 |
| Dell          | Inspiron 7737               | [fb42f48fbe](https://linux-hardware.org/?probe=fb42f48fbe) | Feb 01, 2023 |
| eMachines     | E725                        | [4b1805b3f6](https://linux-hardware.org/?probe=4b1805b3f6) | Feb 01, 2023 |
| Apple         | MacBookAir5,2               | [8a90f64e68](https://linux-hardware.org/?probe=8a90f64e68) | Feb 01, 2023 |
| HP            | 250 G1                      | [41f3eccf2e](https://linux-hardware.org/?probe=41f3eccf2e) | Feb 01, 2023 |
| Apple         | MacBookAir5,2               | [2bdd007ce6](https://linux-hardware.org/?probe=2bdd007ce6) | Feb 01, 2023 |
| HP            | 250 G1                      | [345cb01bcc](https://linux-hardware.org/?probe=345cb01bcc) | Feb 01, 2023 |
| Acer          | Aspire A315-21G             | [1a3af834c9](https://linux-hardware.org/?probe=1a3af834c9) | Feb 01, 2023 |
| Acer          | Aspire A315-21G             | [78f5b5c42b](https://linux-hardware.org/?probe=78f5b5c42b) | Feb 01, 2023 |
| Lenovo        | Y50-70 20378                | [04c77927f5](https://linux-hardware.org/?probe=04c77927f5) | Jan 31, 2023 |
| Lenovo        | Y50-70 20378                | [5dc21f30b5](https://linux-hardware.org/?probe=5dc21f30b5) | Jan 31, 2023 |
| Lenovo        | G580 20150                  | [339aef175f](https://linux-hardware.org/?probe=339aef175f) | Jan 30, 2023 |
| Lenovo        | G580 20150                  | [e0b08d335b](https://linux-hardware.org/?probe=e0b08d335b) | Jan 30, 2023 |
| Lenovo        | ThinkPad W510 431924G       | [c899463c77](https://linux-hardware.org/?probe=c899463c77) | Jan 30, 2023 |
| Samsung       | N102S                       | [c23908cf42](https://linux-hardware.org/?probe=c23908cf42) | Jan 28, 2023 |
| Lenovo        | G580 20150                  | [7597b19143](https://linux-hardware.org/?probe=7597b19143) | Jan 26, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [4804425adc](https://linux-hardware.org/?probe=4804425adc) | Jan 25, 2023 |
| HP            | EliteBook Folio 9480m       | [39c54a5f09](https://linux-hardware.org/?probe=39c54a5f09) | Jan 24, 2023 |
| HP            | EliteBook Folio 9480m       | [ae139e78a0](https://linux-hardware.org/?probe=ae139e78a0) | Jan 22, 2023 |
| HP            | EliteBook Folio 9480m       | [d43d26ff9f](https://linux-hardware.org/?probe=d43d26ff9f) | Jan 22, 2023 |
| Acer          | TravelMate 8571             | [2933c64a6d](https://linux-hardware.org/?probe=2933c64a6d) | Jan 15, 2023 |
| Acer          | TravelMate 8571             | [ad01651917](https://linux-hardware.org/?probe=ad01651917) | Jan 15, 2023 |
| Acer          | TravelMate B117-M           | [c760a021bf](https://linux-hardware.org/?probe=c760a021bf) | Jan 14, 2023 |
| Acer          | TravelMate B117-M           | [bee982f325](https://linux-hardware.org/?probe=bee982f325) | Jan 14, 2023 |
| Dell          | Inspiron 5558               | [798c78aaf7](https://linux-hardware.org/?probe=798c78aaf7) | Jan 14, 2023 |
| Fujitsu       | LIFEBOOK U745               | [e3eb62db83](https://linux-hardware.org/?probe=e3eb62db83) | Jan 12, 2023 |
| Fujitsu       | LIFEBOOK U745               | [b36d8e79ea](https://linux-hardware.org/?probe=b36d8e79ea) | Jan 12, 2023 |
| HP            | EliteBook 2540p             | [9eebe49454](https://linux-hardware.org/?probe=9eebe49454) | Jan 11, 2023 |
| HP            | EliteBook 2540p             | [106e3d9073](https://linux-hardware.org/?probe=106e3d9073) | Jan 11, 2023 |
| Lenovo        | G580 20150                  | [b1fb0a1f64](https://linux-hardware.org/?probe=b1fb0a1f64) | Jan 10, 2023 |
| ASUSTek       | Strix 15 GL503GE            | [07b77ef803](https://linux-hardware.org/?probe=07b77ef803) | Jan 09, 2023 |
| HP            | Laptop 17-ak0xx             | [beef7a74d4](https://linux-hardware.org/?probe=beef7a74d4) | Jan 08, 2023 |
| HP            | ProBook 6570b               | [ac7eff1b5e](https://linux-hardware.org/?probe=ac7eff1b5e) | Jan 08, 2023 |
| HP            | ProBook 6570b               | [819a1c02df](https://linux-hardware.org/?probe=819a1c02df) | Jan 08, 2023 |
| HP            | Laptop 17-ak0xx             | [ffed123536](https://linux-hardware.org/?probe=ffed123536) | Jan 07, 2023 |
| Lenovo        | G580 20150                  | [daad153e9a](https://linux-hardware.org/?probe=daad153e9a) | Jan 06, 2023 |
| HP            | 255 G5 Notebook PC          | [7c62a0a238](https://linux-hardware.org/?probe=7c62a0a238) | Jan 06, 2023 |
| Dell          | Inspiron 5558               | [1473e6f0d9](https://linux-hardware.org/?probe=1473e6f0d9) | Jan 06, 2023 |
| Dell          | Inspiron 5558               | [74f479bd3e](https://linux-hardware.org/?probe=74f479bd3e) | Jan 06, 2023 |
| Lenovo        | G580 20150                  | [9a16949691](https://linux-hardware.org/?probe=9a16949691) | Jan 05, 2023 |
| Lenovo        | G580 20150                  | [b7119b52a7](https://linux-hardware.org/?probe=b7119b52a7) | Jan 05, 2023 |
| Lenovo        | ThinkPad T410 2537BF9       | [30195a4ca0](https://linux-hardware.org/?probe=30195a4ca0) | Jan 04, 2023 |
| Lenovo        | ThinkPad T410 2537BF9       | [2e29dd8142](https://linux-hardware.org/?probe=2e29dd8142) | Jan 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [4247d8d8b0](https://linux-hardware.org/?probe=4247d8d8b0) | Jan 04, 2023 |
| HP            | 255 G5 Notebook PC          | [cdb140b891](https://linux-hardware.org/?probe=cdb140b891) | Jan 03, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ed9ddacdce](https://linux-hardware.org/?probe=ed9ddacdce) | Jan 01, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cc19d2cf24](https://linux-hardware.org/?probe=cc19d2cf24) | Dec 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e0f696a9b9](https://linux-hardware.org/?probe=e0f696a9b9) | Dec 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6c00206f7e](https://linux-hardware.org/?probe=6c00206f7e) | Dec 30, 2022 |
| Dell          | Latitude 5480               | [e02be15b45](https://linux-hardware.org/?probe=e02be15b45) | Dec 30, 2022 |
| Dell          | Latitude 5480               | [5afd8e73be](https://linux-hardware.org/?probe=5afd8e73be) | Dec 30, 2022 |
| Dell          | Latitude 5480               | [64aa4b9161](https://linux-hardware.org/?probe=64aa4b9161) | Dec 30, 2022 |
| Dell          | Latitude 5480               | [b578e196dd](https://linux-hardware.org/?probe=b578e196dd) | Dec 29, 2022 |
| Dell          | Latitude E6230              | [a8df3d8262](https://linux-hardware.org/?probe=a8df3d8262) | Dec 29, 2022 |
| Dell          | Latitude E6230              | [a57d2f5ccb](https://linux-hardware.org/?probe=a57d2f5ccb) | Dec 29, 2022 |
| Dell          | Latitude 5480               | [4b2fda33f4](https://linux-hardware.org/?probe=4b2fda33f4) | Dec 28, 2022 |
| Dell          | Latitude 5480               | [abcd3bea2f](https://linux-hardware.org/?probe=abcd3bea2f) | Dec 28, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | [5cbcee30c7](https://linux-hardware.org/?probe=5cbcee30c7) | Dec 28, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | [743ed4d93a](https://linux-hardware.org/?probe=743ed4d93a) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [819f9be803](https://linux-hardware.org/?probe=819f9be803) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ad4d919e36](https://linux-hardware.org/?probe=ad4d919e36) | Dec 27, 2022 |
| Acer          | Aspire A515-51G             | [56ceb67978](https://linux-hardware.org/?probe=56ceb67978) | Dec 26, 2022 |
| Acer          | Aspire A515-51G             | [e44b069b44](https://linux-hardware.org/?probe=e44b069b44) | Dec 26, 2022 |
| HP            | Compaq 610                  | [198b4d0586](https://linux-hardware.org/?probe=198b4d0586) | Dec 25, 2022 |
| HP            | Compaq 610                  | [0e9ab46e66](https://linux-hardware.org/?probe=0e9ab46e66) | Dec 25, 2022 |
| Acer          | E1-510                      | [463c668d4e](https://linux-hardware.org/?probe=463c668d4e) | Dec 23, 2022 |
| HP            | Laptop 17-ak0xx             | [7e77870894](https://linux-hardware.org/?probe=7e77870894) | Dec 21, 2022 |
| HP            | Laptop 17-ak0xx             | [04c205c943](https://linux-hardware.org/?probe=04c205c943) | Dec 21, 2022 |
| Dell          | Latitude E6230              | [80012cb415](https://linux-hardware.org/?probe=80012cb415) | Dec 19, 2022 |
| Dell          | Latitude E6230              | [ba7fa25841](https://linux-hardware.org/?probe=ba7fa25841) | Dec 17, 2022 |
| Dell          | Inspiron M5030              | [265739601c](https://linux-hardware.org/?probe=265739601c) | Dec 16, 2022 |
| HP            | Laptop 17-ak0xx             | [0ed9c8a241](https://linux-hardware.org/?probe=0ed9c8a241) | Dec 16, 2022 |
| Lenovo        | E50-80 80J2                 | [9dc9070ae6](https://linux-hardware.org/?probe=9dc9070ae6) | Dec 13, 2022 |
| Lenovo        | E50-80 80J2                 | [cf9f4d4a79](https://linux-hardware.org/?probe=cf9f4d4a79) | Dec 13, 2022 |
| HP            | 650                         | [add4ca69e3](https://linux-hardware.org/?probe=add4ca69e3) | Dec 11, 2022 |
| Acer          | TravelMate 8571             | [63aa77ba8d](https://linux-hardware.org/?probe=63aa77ba8d) | Dec 10, 2022 |
| ASUSTek       | X540SA                      | [ac26a0f572](https://linux-hardware.org/?probe=ac26a0f572) | Dec 10, 2022 |
| ASUSTek       | K54HR                       | [32870f2fa3](https://linux-hardware.org/?probe=32870f2fa3) | Dec 10, 2022 |
| ASUSTek       | K54HR                       | [fac8091847](https://linux-hardware.org/?probe=fac8091847) | Dec 10, 2022 |
| ASUSTek       | X540SA                      | [abda33d50f](https://linux-hardware.org/?probe=abda33d50f) | Dec 10, 2022 |
| ASUSTek       | X200MA                      | [1cb00c612b](https://linux-hardware.org/?probe=1cb00c612b) | Dec 09, 2022 |
| HP            | Laptop 15-db0xxx            | [9617825518](https://linux-hardware.org/?probe=9617825518) | Dec 09, 2022 |
| HP            | Laptop 15-db0xxx            | [7b1075fd9b](https://linux-hardware.org/?probe=7b1075fd9b) | Dec 09, 2022 |
| Acer          | TravelMate 8571             | [89270d1f7c](https://linux-hardware.org/?probe=89270d1f7c) | Dec 08, 2022 |
| Acer          | Nitro AN515-51              | [177d3d8e16](https://linux-hardware.org/?probe=177d3d8e16) | Dec 08, 2022 |
| Dell          | Inspiron M5030              | [f73021e3c7](https://linux-hardware.org/?probe=f73021e3c7) | Dec 08, 2022 |
| ASUSTek       | K54HR                       | [66433bdc5e](https://linux-hardware.org/?probe=66433bdc5e) | Dec 07, 2022 |
| Acer          | TravelMate 8571             | [9e7f0672b2](https://linux-hardware.org/?probe=9e7f0672b2) | Dec 06, 2022 |
| ASUSTek       | K54HR                       | [264d0d02bb](https://linux-hardware.org/?probe=264d0d02bb) | Dec 04, 2022 |
| Acer          | TravelMate 8571             | [df032cacb6](https://linux-hardware.org/?probe=df032cacb6) | Dec 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [32dbbbf380](https://linux-hardware.org/?probe=32dbbbf380) | Dec 03, 2022 |
| Dell          | Latitude E5520              | [1b3b69b19f](https://linux-hardware.org/?probe=1b3b69b19f) | Nov 28, 2022 |
| Dell          | Latitude E5520              | [ce72f1c2a9](https://linux-hardware.org/?probe=ce72f1c2a9) | Nov 25, 2022 |
| HP            | Unknown                     | [f76118ac5f](https://linux-hardware.org/?probe=f76118ac5f) | Nov 13, 2022 |
| HP            | Unknown                     | [8cd95516d0](https://linux-hardware.org/?probe=8cd95516d0) | Nov 13, 2022 |
| HP            | 650                         | [100707d1eb](https://linux-hardware.org/?probe=100707d1eb) | Nov 13, 2022 |
| HP            | 650                         | [fd3b93e8fb](https://linux-hardware.org/?probe=fd3b93e8fb) | Nov 05, 2022 |
| Dell          | Inspiron 5558               | [416655ce7d](https://linux-hardware.org/?probe=416655ce7d) | Oct 30, 2022 |
| Dell          | Inspiron 5558               | [ae71fe1a19](https://linux-hardware.org/?probe=ae71fe1a19) | Oct 30, 2022 |
| HP            | Compaq nx6310 (EY589ES#A... | [a80d2e7626](https://linux-hardware.org/?probe=a80d2e7626) | Oct 27, 2022 |
| Fujitsu       | LIFEBOOK U745               | [7cb792e432](https://linux-hardware.org/?probe=7cb792e432) | Oct 27, 2022 |
| Fujitsu       | LIFEBOOK U745               | [0c33d71210](https://linux-hardware.org/?probe=0c33d71210) | Oct 27, 2022 |
| HP            | Compaq 6910p (GH717AW#AB... | [02d31506a2](https://linux-hardware.org/?probe=02d31506a2) | Oct 24, 2022 |
| Dell          | Latitude E6230              | [73ee8be4e9](https://linux-hardware.org/?probe=73ee8be4e9) | Oct 23, 2022 |
| Dell          | Latitude E6230              | [52ee15a8f5](https://linux-hardware.org/?probe=52ee15a8f5) | Oct 23, 2022 |
| eMachines     | E725                        | [ea21ca2d78](https://linux-hardware.org/?probe=ea21ca2d78) | Oct 19, 2022 |
| eMachines     | E725                        | [6d5ddca6c9](https://linux-hardware.org/?probe=6d5ddca6c9) | Oct 18, 2022 |
| eMachines     | E725                        | [f365f1eaa7](https://linux-hardware.org/?probe=f365f1eaa7) | Oct 17, 2022 |
| eMachines     | E725                        | [7003528b88](https://linux-hardware.org/?probe=7003528b88) | Oct 17, 2022 |
| Unknown       | Unknown                     | [07a141abbb](https://linux-hardware.org/?probe=07a141abbb) | Oct 14, 2022 |
| eMachines     | E725                        | [77e7244d88](https://linux-hardware.org/?probe=77e7244d88) | Oct 14, 2022 |
| eMachines     | E725                        | [34538c32c5](https://linux-hardware.org/?probe=34538c32c5) | Oct 14, 2022 |
| Unknown       | Unknown                     | [0d8c24c367](https://linux-hardware.org/?probe=0d8c24c367) | Oct 13, 2022 |
| Lenovo        | ThinkPad W530 2463A58       | [dc933df0a9](https://linux-hardware.org/?probe=dc933df0a9) | Oct 10, 2022 |
| ASUSTek       | X550VX                      | [63a8f1baa1](https://linux-hardware.org/?probe=63a8f1baa1) | Oct 10, 2022 |
| ASUSTek       | X550VX                      | [7f9e9ab40b](https://linux-hardware.org/?probe=7f9e9ab40b) | Oct 10, 2022 |
| Lenovo        | V145-15AST 81MT             | [91163f885b](https://linux-hardware.org/?probe=91163f885b) | Oct 07, 2022 |
| eMachines     | E725                        | [9a77e04f3c](https://linux-hardware.org/?probe=9a77e04f3c) | Oct 05, 2022 |
| eMachines     | E725                        | [e413d82fa5](https://linux-hardware.org/?probe=e413d82fa5) | Oct 05, 2022 |
| Dell          | Latitude D630               | [90dc2dddf8](https://linux-hardware.org/?probe=90dc2dddf8) | Oct 02, 2022 |
| Sony          | SVS13118GBB                 | [48dd8fb419](https://linux-hardware.org/?probe=48dd8fb419) | Oct 01, 2022 |
| Fujitsu       | LIFEBOOK S904               | [c9c83f0112](https://linux-hardware.org/?probe=c9c83f0112) | Oct 01, 2022 |
| Dell          | Latitude D630               | [d00c756052](https://linux-hardware.org/?probe=d00c756052) | Oct 01, 2022 |
| Sony          | SVS13118GBB                 | [75e6dbe3d2](https://linux-hardware.org/?probe=75e6dbe3d2) | Oct 01, 2022 |
| ASUSTek       | Strix 15 GL503GE            | [e48bab666f](https://linux-hardware.org/?probe=e48bab666f) | Oct 01, 2022 |
| Sony          | SVS13118GBB                 | [0e0ca26d00](https://linux-hardware.org/?probe=0e0ca26d00) | Sep 30, 2022 |
| Sony          | SVS13118GBB                 | [12868cf90f](https://linux-hardware.org/?probe=12868cf90f) | Sep 30, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [1ff8e037f4](https://linux-hardware.org/?probe=1ff8e037f4) | Sep 30, 2022 |
| Dell          | Latitude E6420              | [cdd7bd1cc2](https://linux-hardware.org/?probe=cdd7bd1cc2) | Sep 29, 2022 |
| eMachines     | E725                        | [04c9a24d86](https://linux-hardware.org/?probe=04c9a24d86) | Sep 28, 2022 |
| eMachines     | E725                        | [f99f2244c7](https://linux-hardware.org/?probe=f99f2244c7) | Sep 28, 2022 |
| Acer          | Aspire E1-531               | [b7d37d0c6f](https://linux-hardware.org/?probe=b7d37d0c6f) | Sep 27, 2022 |
| Acer          | Aspire E1-531               | [90856d2122](https://linux-hardware.org/?probe=90856d2122) | Sep 27, 2022 |
| ASUSTek       | 1015BX                      | [5190c360db](https://linux-hardware.org/?probe=5190c360db) | Sep 25, 2022 |
| HP            | 650                         | [f835e52a64](https://linux-hardware.org/?probe=f835e52a64) | Sep 25, 2022 |
| HP            | Compaq 6710b (KE125ET#AB... | [fc7831b371](https://linux-hardware.org/?probe=fc7831b371) | Sep 23, 2022 |
| HP            | Compaq 6710b (KE125ET#AB... | [15cffbb03b](https://linux-hardware.org/?probe=15cffbb03b) | Sep 23, 2022 |
| Pegatron      | A15                         | [a865984ad5](https://linux-hardware.org/?probe=a865984ad5) | Sep 23, 2022 |
| Pegatron      | A15                         | [ea527d6d5a](https://linux-hardware.org/?probe=ea527d6d5a) | Sep 23, 2022 |
| Fujitsu       | LIFEBOOK U745               | [0570d2318c](https://linux-hardware.org/?probe=0570d2318c) | Sep 23, 2022 |
| ASUSTek       | K54HR                       | [dbf0f3b1c8](https://linux-hardware.org/?probe=dbf0f3b1c8) | Sep 21, 2022 |
| ASUSTek       | K54HR                       | [25fd2ae90c](https://linux-hardware.org/?probe=25fd2ae90c) | Sep 21, 2022 |
| Toshiba       | Satellite L450              | [20b85987c4](https://linux-hardware.org/?probe=20b85987c4) | Sep 20, 2022 |
| Toshiba       | Satellite L450              | [9f694612d3](https://linux-hardware.org/?probe=9f694612d3) | Sep 20, 2022 |
| ASUSTek       | X550CL                      | [16d313fefa](https://linux-hardware.org/?probe=16d313fefa) | Sep 20, 2022 |
| eMachines     | E725                        | [141723a3e2](https://linux-hardware.org/?probe=141723a3e2) | Sep 16, 2022 |
| eMachines     | E725                        | [bf27205286](https://linux-hardware.org/?probe=bf27205286) | Sep 15, 2022 |
| Acer          | Aspire 5310                 | [963a5bcade](https://linux-hardware.org/?probe=963a5bcade) | Sep 15, 2022 |
| Acer          | Aspire 5820                 | [1820ffa037](https://linux-hardware.org/?probe=1820ffa037) | Sep 09, 2022 |
| Acer          | Aspire 5820                 | [3f0d8d8ff5](https://linux-hardware.org/?probe=3f0d8d8ff5) | Sep 09, 2022 |
| Acer          | Aspire R3-471T              | [05edd6d4ae](https://linux-hardware.org/?probe=05edd6d4ae) | Sep 08, 2022 |
| Dell          | Latitude E6230              | [41c1130440](https://linux-hardware.org/?probe=41c1130440) | Sep 07, 2022 |
| Dell          | Latitude E6230              | [5e0436a64a](https://linux-hardware.org/?probe=5e0436a64a) | Sep 07, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [32715c6eb9](https://linux-hardware.org/?probe=32715c6eb9) | Sep 06, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [cbc35f08cb](https://linux-hardware.org/?probe=cbc35f08cb) | Sep 06, 2022 |
| HP            | 650                         | [526b86a559](https://linux-hardware.org/?probe=526b86a559) | Sep 04, 2022 |
| HP            | 650                         | [6f184e96df](https://linux-hardware.org/?probe=6f184e96df) | Sep 04, 2022 |
| Acer          | Aspire R3-471T              | [eeedafee37](https://linux-hardware.org/?probe=eeedafee37) | Sep 04, 2022 |
| Acer          | Aspire R3-471T              | [01b021f810](https://linux-hardware.org/?probe=01b021f810) | Aug 31, 2022 |
| eMachines     | E725                        | [3e5c01d133](https://linux-hardware.org/?probe=3e5c01d133) | Aug 28, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [1dd156b433](https://linux-hardware.org/?probe=1dd156b433) | Aug 27, 2022 |
| ASUSTek       | X200MA                      | [dcadb94c69](https://linux-hardware.org/?probe=dcadb94c69) | Aug 27, 2022 |
| ASUSTek       | X200MA                      | [5d22a1baa9](https://linux-hardware.org/?probe=5d22a1baa9) | Aug 27, 2022 |
| eMachines     | E725                        | [b73baa0850](https://linux-hardware.org/?probe=b73baa0850) | Aug 25, 2022 |
| ASUSTek       | X200MA                      | [8d375ef1fd](https://linux-hardware.org/?probe=8d375ef1fd) | Aug 24, 2022 |
| ASUSTek       | X200MA                      | [69af3fb82a](https://linux-hardware.org/?probe=69af3fb82a) | Aug 24, 2022 |
| Lenovo        | ThinkPad T410 2537BF9       | [be0227ed47](https://linux-hardware.org/?probe=be0227ed47) | Aug 23, 2022 |
| ASUSTek       | 1015BX                      | [94f3284833](https://linux-hardware.org/?probe=94f3284833) | Aug 21, 2022 |
| Lenovo        | ThinkPad X220 4290L39       | [31a7893b95](https://linux-hardware.org/?probe=31a7893b95) | Aug 20, 2022 |
| Dell          | Latitude 5580               | [5c9db9ff58](https://linux-hardware.org/?probe=5c9db9ff58) | Aug 18, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [6649d66a82](https://linux-hardware.org/?probe=6649d66a82) | Aug 15, 2022 |
| eMachines     | E725                        | [928cfd8881](https://linux-hardware.org/?probe=928cfd8881) | Aug 13, 2022 |
| eMachines     | E725                        | [e1d0d38a1c](https://linux-hardware.org/?probe=e1d0d38a1c) | Aug 13, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [1d7c1c5212](https://linux-hardware.org/?probe=1d7c1c5212) | Aug 13, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [70b0d2bb45](https://linux-hardware.org/?probe=70b0d2bb45) | Aug 13, 2022 |
| eMachines     | E520 V1.10                  | [a5c7ca58d9](https://linux-hardware.org/?probe=a5c7ca58d9) | Aug 06, 2022 |
| Fujitsu       | LIFEBOOK U745               | [c6d5fcceee](https://linux-hardware.org/?probe=c6d5fcceee) | Aug 05, 2022 |
| Fujitsu       | LIFEBOOK U745               | [0e067ccc56](https://linux-hardware.org/?probe=0e067ccc56) | Aug 05, 2022 |
| eMachines     | E725                        | [8028786618](https://linux-hardware.org/?probe=8028786618) | Aug 04, 2022 |
| ASUSTek       | X550JX                      | [469c737a9b](https://linux-hardware.org/?probe=469c737a9b) | Aug 03, 2022 |
| eMachines     | E725                        | [fe35b6624b](https://linux-hardware.org/?probe=fe35b6624b) | Aug 02, 2022 |
| eMachines     | E725                        | [25d51b3945](https://linux-hardware.org/?probe=25d51b3945) | Aug 02, 2022 |
| ASUSTek       | X550JX                      | [edf8c765aa](https://linux-hardware.org/?probe=edf8c765aa) | Aug 02, 2022 |
| eMachines     | E520 V1.10                  | [bb16305e18](https://linux-hardware.org/?probe=bb16305e18) | Aug 01, 2022 |
| HP            | EliteBook 8470p             | [a1d5593420](https://linux-hardware.org/?probe=a1d5593420) | Aug 01, 2022 |
| HP            | EliteBook 8470p             | [0cecb854f4](https://linux-hardware.org/?probe=0cecb854f4) | Jul 31, 2022 |
| HP            | EliteBook 8470p             | [5e73e33a77](https://linux-hardware.org/?probe=5e73e33a77) | Jul 31, 2022 |
| eMachines     | E725                        | [ca033cf053](https://linux-hardware.org/?probe=ca033cf053) | Jul 26, 2022 |
| eMachines     | E725                        | [b975298e85](https://linux-hardware.org/?probe=b975298e85) | Jul 25, 2022 |
| Alcor         | Intel Education Tablet      | [a04ad41c5a](https://linux-hardware.org/?probe=a04ad41c5a) | Jul 24, 2022 |
| Alcor         | Intel Education Tablet      | [700f83a555](https://linux-hardware.org/?probe=700f83a555) | Jul 24, 2022 |
| Dell          | Latitude D630               | [a9fc5a41aa](https://linux-hardware.org/?probe=a9fc5a41aa) | Jul 24, 2022 |
| Dell          | Latitude D630               | [7476af3363](https://linux-hardware.org/?probe=7476af3363) | Jul 23, 2022 |
| ASUSTek       | Strix 15 GL503GE            | [e543e58f00](https://linux-hardware.org/?probe=e543e58f00) | Jul 22, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [33f5176a6c](https://linux-hardware.org/?probe=33f5176a6c) | Jul 21, 2022 |
| Dell          | Precision M4400             | [cf3bbe255a](https://linux-hardware.org/?probe=cf3bbe255a) | Jul 20, 2022 |
| Dell          | Latitude D630C              | [124c9fa2bd](https://linux-hardware.org/?probe=124c9fa2bd) | Jul 15, 2022 |
| eMachines     | E725                        | [771942dd5e](https://linux-hardware.org/?probe=771942dd5e) | Jul 15, 2022 |
| Dell          | Latitude D630C              | [41d2b7ede2](https://linux-hardware.org/?probe=41d2b7ede2) | Jul 15, 2022 |
| HP            | 255 G5 Notebook PC          | [86b8dc8c6d](https://linux-hardware.org/?probe=86b8dc8c6d) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [23077c70b2](https://linux-hardware.org/?probe=23077c70b2) | Jul 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [10192c3d0b](https://linux-hardware.org/?probe=10192c3d0b) | Jul 14, 2022 |
| HP            | 255 G5 Notebook PC          | [fa6486dcd9](https://linux-hardware.org/?probe=fa6486dcd9) | Jul 13, 2022 |
| eMachines     | E725                        | [27fb6a6cab](https://linux-hardware.org/?probe=27fb6a6cab) | Jul 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [9ae6c29438](https://linux-hardware.org/?probe=9ae6c29438) | Jul 08, 2022 |
| Dell          | Latitude D630C              | [5e5cd08804](https://linux-hardware.org/?probe=5e5cd08804) | Jul 08, 2022 |
| Packard Be... | EasyNote ML65               | [c8c6125dc3](https://linux-hardware.org/?probe=c8c6125dc3) | Jul 06, 2022 |
| Packard Be... | EasyNote ML65               | [09d1580fd5](https://linux-hardware.org/?probe=09d1580fd5) | Jul 06, 2022 |
| Sony          | VPCEH2J1E                   | [e51b908744](https://linux-hardware.org/?probe=e51b908744) | Jul 06, 2022 |
| Lenovo        | ThinkPad W510 431924G       | [d65b149a5f](https://linux-hardware.org/?probe=d65b149a5f) | Jul 04, 2022 |
| eMachines     | E725                        | [18d7561b19](https://linux-hardware.org/?probe=18d7561b19) | Jul 04, 2022 |
| eMachines     | E725                        | [8ba1579921](https://linux-hardware.org/?probe=8ba1579921) | Jul 01, 2022 |
| eMachines     | E725                        | [874b6bd7de](https://linux-hardware.org/?probe=874b6bd7de) | Jul 01, 2022 |
| eMachines     | E725                        | [021bcca061](https://linux-hardware.org/?probe=021bcca061) | Jun 30, 2022 |
| eMachines     | E725                        | [b8b332e92f](https://linux-hardware.org/?probe=b8b332e92f) | Jun 30, 2022 |
| eMachines     | E725                        | [3b272a4e25](https://linux-hardware.org/?probe=3b272a4e25) | Jun 26, 2022 |
| Dell          | Latitude E5500              | [8002c78586](https://linux-hardware.org/?probe=8002c78586) | Jun 25, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [a26161ba2f](https://linux-hardware.org/?probe=a26161ba2f) | Jun 23, 2022 |
| Dell          | Latitude D630               | [60c9b1089c](https://linux-hardware.org/?probe=60c9b1089c) | Jun 23, 2022 |
| Dell          | Latitude E5500              | [ad849dbfe7](https://linux-hardware.org/?probe=ad849dbfe7) | Jun 22, 2022 |
| HP            | 255 G5 Notebook PC          | [d230e8311a](https://linux-hardware.org/?probe=d230e8311a) | Jun 21, 2022 |
| HP            | 255 G5 Notebook PC          | [7d1b0cfc99](https://linux-hardware.org/?probe=7d1b0cfc99) | Jun 21, 2022 |
| eMachines     | E725                        | [6e81be09d2](https://linux-hardware.org/?probe=6e81be09d2) | Jun 19, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [e9eb39efa4](https://linux-hardware.org/?probe=e9eb39efa4) | Jun 16, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [bffb7f61cb](https://linux-hardware.org/?probe=bffb7f61cb) | Jun 15, 2022 |
| Lenovo        | Z50-75 80EC                 | [2600b8aa7a](https://linux-hardware.org/?probe=2600b8aa7a) | Jun 14, 2022 |
| HP            | Compaq 6710b (KE121EA#AK... | [940eb51107](https://linux-hardware.org/?probe=940eb51107) | Jun 09, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [15e4cca5bc](https://linux-hardware.org/?probe=15e4cca5bc) | Jun 03, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [b99a9b1bce](https://linux-hardware.org/?probe=b99a9b1bce) | Jun 03, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [96768b6e5c](https://linux-hardware.org/?probe=96768b6e5c) | Jun 02, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [d11a49f42b](https://linux-hardware.org/?probe=d11a49f42b) | Jun 02, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [968decd1af](https://linux-hardware.org/?probe=968decd1af) | Jun 02, 2022 |
| Dell          | Latitude E6400              | [cea3337908](https://linux-hardware.org/?probe=cea3337908) | Jun 01, 2022 |
| HP            | 255 G5 Notebook PC          | [4ff7c85a84](https://linux-hardware.org/?probe=4ff7c85a84) | May 31, 2022 |
| HP            | 255 G5 Notebook PC          | [c65fb5ddb9](https://linux-hardware.org/?probe=c65fb5ddb9) | May 31, 2022 |
| ASUSTek       | K53U                        | [efd067c3a8](https://linux-hardware.org/?probe=efd067c3a8) | May 30, 2022 |
| ASUSTek       | K53U                        | [a26756238b](https://linux-hardware.org/?probe=a26756238b) | May 30, 2022 |
| Dell          | Latitude E6230              | [068d9b4143](https://linux-hardware.org/?probe=068d9b4143) | May 29, 2022 |
| Dell          | Latitude E6230              | [c50bb14e9a](https://linux-hardware.org/?probe=c50bb14e9a) | May 29, 2022 |
| HP            | 255 G5 Notebook PC          | [672f924aec](https://linux-hardware.org/?probe=672f924aec) | May 28, 2022 |
| HP            | 255 G5 Notebook PC          | [7f91291747](https://linux-hardware.org/?probe=7f91291747) | May 28, 2022 |
| HP            | 620                         | [b5bf98b16a](https://linux-hardware.org/?probe=b5bf98b16a) | May 23, 2022 |
| HP            | 620                         | [8bf9517a97](https://linux-hardware.org/?probe=8bf9517a97) | May 23, 2022 |
| HP            | Presario CQ58               | [bdf8b7e229](https://linux-hardware.org/?probe=bdf8b7e229) | May 22, 2022 |
| HP            | Presario CQ58               | [383a27dd29](https://linux-hardware.org/?probe=383a27dd29) | May 22, 2022 |
| MSI           | GT60 2OC/2OD                | [c3b5eb704d](https://linux-hardware.org/?probe=c3b5eb704d) | May 22, 2022 |
| MSI           | GT60 2OC/2OD                | [96f6fda5d5](https://linux-hardware.org/?probe=96f6fda5d5) | May 22, 2022 |
| Lenovo        | B590 20208                  | [b32a821a4c](https://linux-hardware.org/?probe=b32a821a4c) | May 21, 2022 |
| Lenovo        | B590 20208                  | [3386aeef48](https://linux-hardware.org/?probe=3386aeef48) | May 21, 2022 |
| Fujitsu       | LIFEBOOK U745               | [9003466ff8](https://linux-hardware.org/?probe=9003466ff8) | May 21, 2022 |
| Fujitsu       | LIFEBOOK U745               | [2e05001696](https://linux-hardware.org/?probe=2e05001696) | May 21, 2022 |
| HP            | 620                         | [babb1f392a](https://linux-hardware.org/?probe=babb1f392a) | May 21, 2022 |
| Lenovo        | G570 20079                  | [f4b9c3997d](https://linux-hardware.org/?probe=f4b9c3997d) | May 16, 2022 |
| Toshiba       | Satellite L775-18R          | [ec012c6b3d](https://linux-hardware.org/?probe=ec012c6b3d) | May 16, 2022 |
| Lenovo        | G580 20150                  | [75f2c0ab4e](https://linux-hardware.org/?probe=75f2c0ab4e) | May 15, 2022 |
| Lenovo        | G580 20150                  | [8d710ae7c3](https://linux-hardware.org/?probe=8d710ae7c3) | May 15, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [758e2b869d](https://linux-hardware.org/?probe=758e2b869d) | May 15, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [91c6da69a9](https://linux-hardware.org/?probe=91c6da69a9) | May 15, 2022 |
| Dell          | Latitude E6430              | [e805d60a6b](https://linux-hardware.org/?probe=e805d60a6b) | May 14, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [bfc1a518db](https://linux-hardware.org/?probe=bfc1a518db) | May 14, 2022 |
| HP            | 620                         | [62369d924a](https://linux-hardware.org/?probe=62369d924a) | May 12, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [af186fe9e3](https://linux-hardware.org/?probe=af186fe9e3) | May 10, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [b6fed1d4fe](https://linux-hardware.org/?probe=b6fed1d4fe) | May 10, 2022 |
| Dell          | Latitude E6230              | [d9d1e38394](https://linux-hardware.org/?probe=d9d1e38394) | May 09, 2022 |
| Acer          | Aspire 6930G                | [49228d9f61](https://linux-hardware.org/?probe=49228d9f61) | May 08, 2022 |
| Acer          | Aspire 6930G                | [912dbb8280](https://linux-hardware.org/?probe=912dbb8280) | May 08, 2022 |
| MSI           | GT60 2OC/2OD                | [21f08dbab6](https://linux-hardware.org/?probe=21f08dbab6) | May 06, 2022 |
| HUAWEI        | HVY-WXX9                    | [fbd1c44f53](https://linux-hardware.org/?probe=fbd1c44f53) | May 02, 2022 |
| Sony          | VPCEH2J1E                   | [86f6b8c750](https://linux-hardware.org/?probe=86f6b8c750) | Apr 30, 2022 |
| Dell          | Inspiron MP061              | [e41e5725a7](https://linux-hardware.org/?probe=e41e5725a7) | Apr 28, 2022 |
| Toshiba       | NB550D                      | [386409d233](https://linux-hardware.org/?probe=386409d233) | Apr 24, 2022 |
| Lenovo        | B590 20208                  | [af6b076e21](https://linux-hardware.org/?probe=af6b076e21) | Apr 18, 2022 |
| Hungaro Fl... | Navon Loop 360              | [48b6f0e313](https://linux-hardware.org/?probe=48b6f0e313) | Apr 18, 2022 |
| Hungaro Fl... | Navon Loop 360              | [cde65f88c1](https://linux-hardware.org/?probe=cde65f88c1) | Apr 17, 2022 |
| ASUSTek       | TP201SA                     | [2898b67bff](https://linux-hardware.org/?probe=2898b67bff) | Apr 16, 2022 |
| HP            | ProBook 470 G1              | [ee1f05022a](https://linux-hardware.org/?probe=ee1f05022a) | Apr 10, 2022 |
| Lenovo        | G580 20150                  | [00215e25c0](https://linux-hardware.org/?probe=00215e25c0) | Apr 10, 2022 |
| Acer          | Aspire A114-31              | [8779ba2891](https://linux-hardware.org/?probe=8779ba2891) | Apr 09, 2022 |
| Fujitsu       | LIFEBOOK U745               | [9dc3653255](https://linux-hardware.org/?probe=9dc3653255) | Apr 09, 2022 |
| Acer          | Aspire A114-31              | [298acab48c](https://linux-hardware.org/?probe=298acab48c) | Apr 08, 2022 |
| Lenovo        | ThinkPad T61 6458WK6        | [5303af9863](https://linux-hardware.org/?probe=5303af9863) | Apr 07, 2022 |
| ASUSTek       | N75SF                       | [e3f8003fb7](https://linux-hardware.org/?probe=e3f8003fb7) | Apr 07, 2022 |
| Fujitsu       | LIFEBOOK U745               | [5d73ae026b](https://linux-hardware.org/?probe=5d73ae026b) | Apr 05, 2022 |
| Acer          | TravelMate P215-52          | [a5d16dc93e](https://linux-hardware.org/?probe=a5d16dc93e) | Apr 03, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [495e271511](https://linux-hardware.org/?probe=495e271511) | Apr 03, 2022 |
| Dell          | Latitude E5420              | [a60c1a4785](https://linux-hardware.org/?probe=a60c1a4785) | Apr 03, 2022 |
| Lenovo        | G780 20138                  | [a7cad8a09a](https://linux-hardware.org/?probe=a7cad8a09a) | Apr 02, 2022 |
| Acer          | TravelMate P215-52          | [752d283e54](https://linux-hardware.org/?probe=752d283e54) | Apr 01, 2022 |
| ASUSTek       | X540LA                      | [732406d8b0](https://linux-hardware.org/?probe=732406d8b0) | Apr 01, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [666c8daa31](https://linux-hardware.org/?probe=666c8daa31) | Apr 01, 2022 |
| HP            | Unknown                     | [c6a02a2df5](https://linux-hardware.org/?probe=c6a02a2df5) | Apr 01, 2022 |
| HP            | Unknown                     | [71ae764e9f](https://linux-hardware.org/?probe=71ae764e9f) | Apr 01, 2022 |
| HP            | Compaq nx6125 (PZ896UA#A... | [bba6b8d33d](https://linux-hardware.org/?probe=bba6b8d33d) | Mar 30, 2022 |
| HP            | Compaq nx6125 (PZ896UA#A... | [9f382b5166](https://linux-hardware.org/?probe=9f382b5166) | Mar 30, 2022 |
| HP            | Pavilion dv8000 (EP409UA... | [56c91c9396](https://linux-hardware.org/?probe=56c91c9396) | Mar 29, 2022 |
| eMachines     | E725                        | [475f79831d](https://linux-hardware.org/?probe=475f79831d) | Mar 29, 2022 |
| eMachines     | E725                        | [f8e777c318](https://linux-hardware.org/?probe=f8e777c318) | Mar 29, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [60da33f3aa](https://linux-hardware.org/?probe=60da33f3aa) | Mar 28, 2022 |
| Dell          | Latitude E5540              | [838350f357](https://linux-hardware.org/?probe=838350f357) | Mar 28, 2022 |
| Lenovo        | ThinkPad W530 2463A58       | [8e8bd0aad5](https://linux-hardware.org/?probe=8e8bd0aad5) | Mar 28, 2022 |
| Sony          | VPCEH2J1E                   | [23d5b99aca](https://linux-hardware.org/?probe=23d5b99aca) | Mar 27, 2022 |
| Lenovo        | G580 20150                  | [ec430f1afc](https://linux-hardware.org/?probe=ec430f1afc) | Mar 27, 2022 |
| Dell          | Inspiron M5030              | [a36af1ef0f](https://linux-hardware.org/?probe=a36af1ef0f) | Mar 27, 2022 |
| Dell          | Inspiron M5030              | [c3b9926b94](https://linux-hardware.org/?probe=c3b9926b94) | Mar 27, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [ed4ed6851f](https://linux-hardware.org/?probe=ed4ed6851f) | Mar 23, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [5b8c4678af](https://linux-hardware.org/?probe=5b8c4678af) | Mar 22, 2022 |
| Acer          | TravelMate P238-G2-M        | [7aa968ca84](https://linux-hardware.org/?probe=7aa968ca84) | Mar 22, 2022 |
| Apple         | MacBookPro6,2               | [5611c90f20](https://linux-hardware.org/?probe=5611c90f20) | Mar 21, 2022 |
| Apple         | MacBookPro6,2               | [2a71c88e71](https://linux-hardware.org/?probe=2a71c88e71) | Mar 21, 2022 |
| Lenovo        | G505s 20255                 | [9f18cfb328](https://linux-hardware.org/?probe=9f18cfb328) | Mar 19, 2022 |
| Sony          | VPCEH2J1E                   | [ae54fc4033](https://linux-hardware.org/?probe=ae54fc4033) | Mar 19, 2022 |
| Lenovo        | G505s 20255                 | [716d4ed3be](https://linux-hardware.org/?probe=716d4ed3be) | Mar 18, 2022 |
| ASUSTek       | X201EP                      | [864fc80ac3](https://linux-hardware.org/?probe=864fc80ac3) | Mar 17, 2022 |
| HP            | Compaq CQ58                 | [ef6cbc7487](https://linux-hardware.org/?probe=ef6cbc7487) | Mar 17, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [6ae5708fe3](https://linux-hardware.org/?probe=6ae5708fe3) | Mar 16, 2022 |
| Fujitsu       | LIFEBOOK U745               | [e8e4e5d953](https://linux-hardware.org/?probe=e8e4e5d953) | Mar 15, 2022 |
| HP            | 650                         | [3266dba7df](https://linux-hardware.org/?probe=3266dba7df) | Mar 14, 2022 |
| HP            | 650                         | [54df12f572](https://linux-hardware.org/?probe=54df12f572) | Mar 14, 2022 |
| HP            | Pavilion 17                 | [d623639513](https://linux-hardware.org/?probe=d623639513) | Mar 14, 2022 |
| ASUSTek       | Strix 15 GL503GE            | [29c3688c05](https://linux-hardware.org/?probe=29c3688c05) | Mar 13, 2022 |
| ASUSTek       | X541UVK                     | [74ba6d5353](https://linux-hardware.org/?probe=74ba6d5353) | Mar 12, 2022 |
| eMachines     | E725                        | [05b157a340](https://linux-hardware.org/?probe=05b157a340) | Mar 12, 2022 |
| HP            | Pavilion 17                 | [f5ff2a8a14](https://linux-hardware.org/?probe=f5ff2a8a14) | Mar 10, 2022 |
| HP            | Pavilion 17                 | [b6bfe40827](https://linux-hardware.org/?probe=b6bfe40827) | Mar 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [299209635a](https://linux-hardware.org/?probe=299209635a) | Mar 09, 2022 |
| Dell          | Latitude E6230              | [20ca54a46c](https://linux-hardware.org/?probe=20ca54a46c) | Mar 09, 2022 |
| Sony          | VPCEH2J1E                   | [713f08757a](https://linux-hardware.org/?probe=713f08757a) | Mar 09, 2022 |
| Sony          | SVS13118GBB                 | [64dc07d0af](https://linux-hardware.org/?probe=64dc07d0af) | Mar 08, 2022 |
| Sony          | SVS13118GBB                 | [76afe39f5e](https://linux-hardware.org/?probe=76afe39f5e) | Mar 08, 2022 |
| Toshiba       | Satellite Pro C50-A-1E5     | [ac3b4acda7](https://linux-hardware.org/?probe=ac3b4acda7) | Mar 06, 2022 |
| Lenovo        | ThinkPad T60 6370A55        | [3a01549416](https://linux-hardware.org/?probe=3a01549416) | Mar 06, 2022 |
| Lenovo        | ThinkPad T60 6370A55        | [48d2d5d234](https://linux-hardware.org/?probe=48d2d5d234) | Mar 06, 2022 |
| HP            | Compaq 6710b (GB890EA#AK... | [c313b8ee39](https://linux-hardware.org/?probe=c313b8ee39) | Mar 05, 2022 |
| HP            | Compaq 6720s                | [f83b83214e](https://linux-hardware.org/?probe=f83b83214e) | Mar 04, 2022 |
| Toshiba       | dynabook RX3 SN240Y/3HD     | [2f2d99c83f](https://linux-hardware.org/?probe=2f2d99c83f) | Mar 03, 2022 |
| Toshiba       | dynabook RX3 SN240Y/3HD     | [0d0a2bab7a](https://linux-hardware.org/?probe=0d0a2bab7a) | Mar 03, 2022 |
| MSI           | GP75 Leopard 9SE            | [6090fb66ea](https://linux-hardware.org/?probe=6090fb66ea) | Mar 02, 2022 |
| Dell          | Latitude E5540              | [0e5ce3685b](https://linux-hardware.org/?probe=0e5ce3685b) | Mar 02, 2022 |
| HP            | G60                         | [3921a7d345](https://linux-hardware.org/?probe=3921a7d345) | Mar 02, 2022 |
| HP            | Compaq 6720s                | [9d3882f4c5](https://linux-hardware.org/?probe=9d3882f4c5) | Mar 02, 2022 |
| MSI           | GP75 Leopard 9SE            | [c56a98389f](https://linux-hardware.org/?probe=c56a98389f) | Mar 01, 2022 |
| Acer          | Aspire ES1-571              | [acc272ef5a](https://linux-hardware.org/?probe=acc272ef5a) | Feb 28, 2022 |
| Acer          | Aspire ES1-571              | [cf51003466](https://linux-hardware.org/?probe=cf51003466) | Feb 28, 2022 |
| Dell          | Latitude 5480               | [43ae797918](https://linux-hardware.org/?probe=43ae797918) | Feb 28, 2022 |
| ASUSTek       | K53U                        | [16c5ebe7c3](https://linux-hardware.org/?probe=16c5ebe7c3) | Feb 27, 2022 |
| HP            | Pavilion g6                 | [2aea4ab8f4](https://linux-hardware.org/?probe=2aea4ab8f4) | Feb 27, 2022 |
| HP            | ProBook 6470b               | [76e9b5f896](https://linux-hardware.org/?probe=76e9b5f896) | Feb 26, 2022 |
| HP            | ProBook 6470b               | [3b86510929](https://linux-hardware.org/?probe=3b86510929) | Feb 26, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | [f247d6c3ca](https://linux-hardware.org/?probe=f247d6c3ca) | Feb 25, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | [ececeadefe](https://linux-hardware.org/?probe=ececeadefe) | Feb 25, 2022 |
| HP            | Pavilion 17                 | [97c44abef4](https://linux-hardware.org/?probe=97c44abef4) | Feb 22, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [80ceccfdc7](https://linux-hardware.org/?probe=80ceccfdc7) | Feb 22, 2022 |
| eMachines     | E725                        | [4aa5e2b180](https://linux-hardware.org/?probe=4aa5e2b180) | Feb 21, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [d1f67de0fb](https://linux-hardware.org/?probe=d1f67de0fb) | Feb 21, 2022 |
| Dell          | Latitude D630               | [067e57eab9](https://linux-hardware.org/?probe=067e57eab9) | Feb 20, 2022 |
| Packard Be... | EasyNote ENLG81BA           | [fb281e6c00](https://linux-hardware.org/?probe=fb281e6c00) | Feb 20, 2022 |
| Packard Be... | EasyNote ENLG81BA           | [58e5e2c95c](https://linux-hardware.org/?probe=58e5e2c95c) | Feb 20, 2022 |
| ASUSTek       | X550VX                      | [2cf18df101](https://linux-hardware.org/?probe=2cf18df101) | Feb 19, 2022 |
| HP            | Compaq 6530b (NJ641UC#AB... | [ab91a058c0](https://linux-hardware.org/?probe=ab91a058c0) | Feb 19, 2022 |
| HP            | Compaq 6530b (NJ641UC#AB... | [70ab79b3b4](https://linux-hardware.org/?probe=70ab79b3b4) | Feb 19, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [dc8d1eb5eb](https://linux-hardware.org/?probe=dc8d1eb5eb) | Feb 18, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [58b92a0176](https://linux-hardware.org/?probe=58b92a0176) | Feb 18, 2022 |
| HP            | ProBook 6470b               | [4c37154dc3](https://linux-hardware.org/?probe=4c37154dc3) | Feb 17, 2022 |
| Dell          | Latitude E5430 non-vPro     | [a7afdd9d95](https://linux-hardware.org/?probe=a7afdd9d95) | Feb 17, 2022 |
| HP            | Pavilion 17                 | [166e1147d2](https://linux-hardware.org/?probe=166e1147d2) | Feb 17, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [934591472d](https://linux-hardware.org/?probe=934591472d) | Feb 16, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [c5eab4c7d9](https://linux-hardware.org/?probe=c5eab4c7d9) | Feb 16, 2022 |
| HP            | EliteBook 8570w             | [bdfcf410e6](https://linux-hardware.org/?probe=bdfcf410e6) | Feb 16, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [23e6094c83](https://linux-hardware.org/?probe=23e6094c83) | Feb 16, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [a0a9cf96a8](https://linux-hardware.org/?probe=a0a9cf96a8) | Feb 15, 2022 |
| HP            | Compaq 6530b (NJ641UC#AB... | [357881c642](https://linux-hardware.org/?probe=357881c642) | Feb 15, 2022 |
| Dell          | Latitude D630               | [17929b78ff](https://linux-hardware.org/?probe=17929b78ff) | Feb 15, 2022 |
| HP            | Compaq 6530b (NJ641UC#AB... | [1cfe8d6cc4](https://linux-hardware.org/?probe=1cfe8d6cc4) | Feb 14, 2022 |
| HP            | 250 G1                      | [0c35eb7e0c](https://linux-hardware.org/?probe=0c35eb7e0c) | Feb 14, 2022 |
| HP            | 250 G1                      | [0e47dcd6ff](https://linux-hardware.org/?probe=0e47dcd6ff) | Feb 14, 2022 |
| Lenovo        | ThinkPad T410 2537VFQ       | [004fd97714](https://linux-hardware.org/?probe=004fd97714) | Feb 13, 2022 |
| Lenovo        | 3000 N500 423332G           | [5f673420ca](https://linux-hardware.org/?probe=5f673420ca) | Feb 13, 2022 |
| Fujitsu Si... | LIFEBOOK S7110              | [a3f36901a2](https://linux-hardware.org/?probe=a3f36901a2) | Feb 13, 2022 |
| HP            | 255 G6 Notebook PC          | [30c3320bb3](https://linux-hardware.org/?probe=30c3320bb3) | Feb 12, 2022 |
| HP            | 255 G6 Notebook PC          | [d4f9b2d0e3](https://linux-hardware.org/?probe=d4f9b2d0e3) | Feb 12, 2022 |
| Lenovo        | 3000 N500 423332G           | [aa5079471b](https://linux-hardware.org/?probe=aa5079471b) | Feb 12, 2022 |
| Acer          | TravelMate 8571             | [df168b8134](https://linux-hardware.org/?probe=df168b8134) | Feb 11, 2022 |
| Acer          | TravelMate 8571             | [c8493474f0](https://linux-hardware.org/?probe=c8493474f0) | Feb 11, 2022 |
| Acer          | Predator PH517-51           | [de32d3b86d](https://linux-hardware.org/?probe=de32d3b86d) | Feb 10, 2022 |
| Acer          | F                           | [a5dd4a459a](https://linux-hardware.org/?probe=a5dd4a459a) | Feb 10, 2022 |
| ASUSTek       | X550VX                      | [8fd69ee74c](https://linux-hardware.org/?probe=8fd69ee74c) | Feb 09, 2022 |
| Dell          | Latitude 5480               | [0d2e568733](https://linux-hardware.org/?probe=0d2e568733) | Feb 09, 2022 |
| ASUSTek       | X541UVK                     | [c4556ed732](https://linux-hardware.org/?probe=c4556ed732) | Feb 08, 2022 |
| Dell          | Latitude E6410              | [c71db9d118](https://linux-hardware.org/?probe=c71db9d118) | Feb 08, 2022 |
| Dell          | Latitude E6410              | [61aae88463](https://linux-hardware.org/?probe=61aae88463) | Feb 08, 2022 |
| ASUSTek       | X541UVK                     | [f293b3a040](https://linux-hardware.org/?probe=f293b3a040) | Feb 07, 2022 |
| Dell          | Inspiron 15-3567            | [e897975636](https://linux-hardware.org/?probe=e897975636) | Feb 06, 2022 |
| Dell          | Latitude D630               | [553512c6fa](https://linux-hardware.org/?probe=553512c6fa) | Feb 06, 2022 |
| Acer          | Aspire A114-31              | [caa9365785](https://linux-hardware.org/?probe=caa9365785) | Feb 04, 2022 |
| Sony          | VPCEH2J1E                   | [f5ed0cbaa4](https://linux-hardware.org/?probe=f5ed0cbaa4) | Feb 04, 2022 |
| HP            | 650                         | [63c7a9f5bc](https://linux-hardware.org/?probe=63c7a9f5bc) | Feb 03, 2022 |
| Sony          | SVS13118GBB                 | [44ef5a252e](https://linux-hardware.org/?probe=44ef5a252e) | Feb 01, 2022 |
| HP            | Unknown                     | [6aa3eb854c](https://linux-hardware.org/?probe=6aa3eb854c) | Jan 31, 2022 |
| ASUSTek       | X541UVK                     | [e923d26564](https://linux-hardware.org/?probe=e923d26564) | Jan 30, 2022 |
| ASUSTek       | X541UVK                     | [01a2239429](https://linux-hardware.org/?probe=01a2239429) | Jan 30, 2022 |
| ASUSTek       | X541UVK                     | [d231ae37d8](https://linux-hardware.org/?probe=d231ae37d8) | Jan 29, 2022 |
| Sony          | SVS13118GBB                 | [1e7063ddb5](https://linux-hardware.org/?probe=1e7063ddb5) | Jan 28, 2022 |
| HP            | 250 G6 Notebook PC          | [1168d4d65b](https://linux-hardware.org/?probe=1168d4d65b) | Jan 28, 2022 |
| HP            | 250 G6 Notebook PC          | [975facb986](https://linux-hardware.org/?probe=975facb986) | Jan 28, 2022 |
| Lenovo        | ThinkPad T61 6458Y56        | [4cef262fd4](https://linux-hardware.org/?probe=4cef262fd4) | Jan 28, 2022 |
| Apple         | MacBookPro6,2               | [a2475cad56](https://linux-hardware.org/?probe=a2475cad56) | Jan 27, 2022 |
| HP            | ProBook 6470b               | [81afdce4bb](https://linux-hardware.org/?probe=81afdce4bb) | Jan 27, 2022 |
| ASUSTek       | X550VX                      | [a92b98a4cf](https://linux-hardware.org/?probe=a92b98a4cf) | Jan 26, 2022 |
| Insyde        | Braswell                    | [0d8764b0d5](https://linux-hardware.org/?probe=0d8764b0d5) | Jan 26, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [242f7d0fec](https://linux-hardware.org/?probe=242f7d0fec) | Jan 25, 2022 |
| Insyde        | Braswell                    | [c082266f28](https://linux-hardware.org/?probe=c082266f28) | Jan 25, 2022 |
| HP            | ProBook 6470b               | [820d0a16ea](https://linux-hardware.org/?probe=820d0a16ea) | Jan 24, 2022 |
| Sony          | VGN-N31S_W                  | [ce8de203fb](https://linux-hardware.org/?probe=ce8de203fb) | Jan 24, 2022 |
| Sony          | VGN-N31S_W                  | [fed17ac82e](https://linux-hardware.org/?probe=fed17ac82e) | Jan 24, 2022 |
| Dell          | Inspiron M5030              | [0918a672e0](https://linux-hardware.org/?probe=0918a672e0) | Jan 22, 2022 |
| Lenovo        | ThinkPad L420 78544UG       | [26c13c7d16](https://linux-hardware.org/?probe=26c13c7d16) | Jan 22, 2022 |
| Lenovo        | ThinkPad L420 78544UG       | [dc6c0d3559](https://linux-hardware.org/?probe=dc6c0d3559) | Jan 22, 2022 |
| ASUSTek       | K50IN                       | [64a1640588](https://linux-hardware.org/?probe=64a1640588) | Jan 21, 2022 |
| ASUSTek       | K50IN                       | [43c8a1b1ec](https://linux-hardware.org/?probe=43c8a1b1ec) | Jan 21, 2022 |
| Dell          | Inspiron 5558               | [fc8a233818](https://linux-hardware.org/?probe=fc8a233818) | Jan 21, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [87bd7d315f](https://linux-hardware.org/?probe=87bd7d315f) | Jan 18, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [42a841fb5b](https://linux-hardware.org/?probe=42a841fb5b) | Jan 17, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [10983d5883](https://linux-hardware.org/?probe=10983d5883) | Jan 17, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [0bd3f0c6c1](https://linux-hardware.org/?probe=0bd3f0c6c1) | Jan 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [30c367f8ca](https://linux-hardware.org/?probe=30c367f8ca) | Jan 15, 2022 |
| Packard Be... | EasyNote TK37               | [4b9de8a4a2](https://linux-hardware.org/?probe=4b9de8a4a2) | Jan 15, 2022 |
| Packard Be... | EasyNote TK37               | [b511ea2a93](https://linux-hardware.org/?probe=b511ea2a93) | Jan 14, 2022 |
| Packard Be... | EasyNote TK37               | [28b9c9ef8e](https://linux-hardware.org/?probe=28b9c9ef8e) | Jan 14, 2022 |
| HP            | 255 G5 Notebook PC          | [6f20015e15](https://linux-hardware.org/?probe=6f20015e15) | Jan 13, 2022 |
| Medion        | CRAWLER E10                 | [d658e7cd88](https://linux-hardware.org/?probe=d658e7cd88) | Jan 13, 2022 |
| Lenovo        | ThinkPad T500 2056CL8       | [ef244e06d3](https://linux-hardware.org/?probe=ef244e06d3) | Jan 10, 2022 |
| Lenovo        | ThinkPad X61 76753BJ        | [8f0b1342b0](https://linux-hardware.org/?probe=8f0b1342b0) | Jan 10, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [81f7bfbced](https://linux-hardware.org/?probe=81f7bfbced) | Jan 10, 2022 |
| Lenovo        | ThinkPad X61 76753BJ        | [73ff2bcb33](https://linux-hardware.org/?probe=73ff2bcb33) | Jan 10, 2022 |
| ASUSTek       | K53U                        | [d39f634e72](https://linux-hardware.org/?probe=d39f634e72) | Jan 10, 2022 |
| ASUSTek       | K53U                        | [a174ee5aa1](https://linux-hardware.org/?probe=a174ee5aa1) | Jan 10, 2022 |
| Dell          | Latitude E6430              | [e25ec7e140](https://linux-hardware.org/?probe=e25ec7e140) | Jan 09, 2022 |
| Acer          | Aspire ES1-532G             | [7cecf04619](https://linux-hardware.org/?probe=7cecf04619) | Jan 09, 2022 |
| Acer          | Aspire ES1-532G             | [d2dfc8da4c](https://linux-hardware.org/?probe=d2dfc8da4c) | Jan 09, 2022 |
| Acer          | Aspire F5-573G              | [719238f99c](https://linux-hardware.org/?probe=719238f99c) | Jan 08, 2022 |
| Acer          | Aspire F5-573G              | [3d833877a7](https://linux-hardware.org/?probe=3d833877a7) | Jan 08, 2022 |
| Dell          | Inspiron 1525               | [11ecdbec1b](https://linux-hardware.org/?probe=11ecdbec1b) | Jan 02, 2022 |
| Dell          | Inspiron 1525               | [c1c0a04b87](https://linux-hardware.org/?probe=c1c0a04b87) | Jan 02, 2022 |
| HP            | EliteBook 820 G1            | [a474addf38](https://linux-hardware.org/?probe=a474addf38) | Jan 01, 2022 |
| Lenovo        | ThinkPad W510 431924G       | [c0ef5f6b84](https://linux-hardware.org/?probe=c0ef5f6b84) | Dec 29, 2021 |
| Lenovo        | B590 20208                  | [84ca821541](https://linux-hardware.org/?probe=84ca821541) | Dec 29, 2021 |
| MSI           | GP75 Leopard 9SE            | [af923f06cc](https://linux-hardware.org/?probe=af923f06cc) | Dec 29, 2021 |
| Toshiba       | dynabook RX3 SN240Y/3HD     | [0b20db823c](https://linux-hardware.org/?probe=0b20db823c) | Dec 29, 2021 |
| MSI           | GP75 Leopard 9SE            | [a7a37c26c7](https://linux-hardware.org/?probe=a7a37c26c7) | Dec 29, 2021 |
| HP            | 15                          | [76fef17b30](https://linux-hardware.org/?probe=76fef17b30) | Dec 27, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [988628f6b6](https://linux-hardware.org/?probe=988628f6b6) | Dec 25, 2021 |
| Dell          | Latitude E6410              | [0588df88b2](https://linux-hardware.org/?probe=0588df88b2) | Dec 24, 2021 |
| Dell          | Latitude E6410              | [c30a066afc](https://linux-hardware.org/?probe=c30a066afc) | Dec 24, 2021 |
| HP            | EliteBook 8760w             | [5eac4e1b94](https://linux-hardware.org/?probe=5eac4e1b94) | Dec 24, 2021 |
| Dell          | Precision M6600             | [6be07fde65](https://linux-hardware.org/?probe=6be07fde65) | Dec 23, 2021 |
| Dell          | Precision M6600             | [a4f1415897](https://linux-hardware.org/?probe=a4f1415897) | Dec 23, 2021 |
| Medion        | E7218                       | [8d6ee5cd3e](https://linux-hardware.org/?probe=8d6ee5cd3e) | Dec 23, 2021 |
| Medion        | E7218                       | [6b930af32f](https://linux-hardware.org/?probe=6b930af32f) | Dec 22, 2021 |
| HP            | EliteBook 8570w             | [3d19abb9a8](https://linux-hardware.org/?probe=3d19abb9a8) | Dec 22, 2021 |
| Acer          | Aspire 3050                 | [888f7795aa](https://linux-hardware.org/?probe=888f7795aa) | Dec 22, 2021 |
| Acer          | Aspire 3050                 | [cfec9fece6](https://linux-hardware.org/?probe=cfec9fece6) | Dec 21, 2021 |
| Acer          | Aspire ES1-532G             | [cf832b7bf6](https://linux-hardware.org/?probe=cf832b7bf6) | Dec 19, 2021 |
| Acer          | Aspire ES1-532G             | [23d3dd911d](https://linux-hardware.org/?probe=23d3dd911d) | Dec 19, 2021 |
| Dell          | Latitude E6430              | [5b026ea45f](https://linux-hardware.org/?probe=5b026ea45f) | Dec 19, 2021 |
| Dell          | Latitude E6430              | [ae951db282](https://linux-hardware.org/?probe=ae951db282) | Dec 18, 2021 |
| Dell          | Precision M2800             | [0a3b99488f](https://linux-hardware.org/?probe=0a3b99488f) | Dec 11, 2021 |
| HP            | Pavilion dv7                | [394ba3e1b7](https://linux-hardware.org/?probe=394ba3e1b7) | Dec 06, 2021 |
| Dell          | Latitude E6420              | [51073dcf26](https://linux-hardware.org/?probe=51073dcf26) | Dec 05, 2021 |
| Dell          | Latitude E6420              | [6826928218](https://linux-hardware.org/?probe=6826928218) | Dec 05, 2021 |
| MSI           | CX600                       | [38b84f0feb](https://linux-hardware.org/?probe=38b84f0feb) | Dec 05, 2021 |
| Dell          | Latitude 5480               | [412919400e](https://linux-hardware.org/?probe=412919400e) | Dec 05, 2021 |
| Dell          | Latitude D630               | [718e2268fa](https://linux-hardware.org/?probe=718e2268fa) | Dec 04, 2021 |
| Lenovo        | ThinkPad T61 6458WK6        | [e24ba2f637](https://linux-hardware.org/?probe=e24ba2f637) | Dec 03, 2021 |
| HP            | Pavilion dv7                | [445f67242b](https://linux-hardware.org/?probe=445f67242b) | Dec 03, 2021 |
| Dell          | Latitude 5480               | [d1a9d603a9](https://linux-hardware.org/?probe=d1a9d603a9) | Nov 30, 2021 |
| Apple         | MacBookPro5,5               | [c32c22a4b9](https://linux-hardware.org/?probe=c32c22a4b9) | Nov 30, 2021 |
| Apple         | MacBookPro5,5               | [01a1e9ffb0](https://linux-hardware.org/?probe=01a1e9ffb0) | Nov 30, 2021 |
| Acer          | Aspire 5930                 | [17eed17c54](https://linux-hardware.org/?probe=17eed17c54) | Nov 29, 2021 |
| Acer          | Aspire 5930                 | [9a4712d7ad](https://linux-hardware.org/?probe=9a4712d7ad) | Nov 29, 2021 |
| Dell          | Latitude E6430              | [39087042b7](https://linux-hardware.org/?probe=39087042b7) | Nov 28, 2021 |
| Dell          | Latitude 5480               | [70e231854b](https://linux-hardware.org/?probe=70e231854b) | Nov 28, 2021 |
| HP            | EliteBook 8540p             | [38dd850a7c](https://linux-hardware.org/?probe=38dd850a7c) | Nov 26, 2021 |
| HP            | EliteBook 8540p             | [e6df5b59a8](https://linux-hardware.org/?probe=e6df5b59a8) | Nov 26, 2021 |
| BenQ          | Joybook A52                 | [f11e0f093f](https://linux-hardware.org/?probe=f11e0f093f) | Nov 26, 2021 |
| Lenovo        | G40-45 80E1                 | [0460c1b728](https://linux-hardware.org/?probe=0460c1b728) | Nov 25, 2021 |
| Dell          | Latitude 5480               | [c2079e6c03](https://linux-hardware.org/?probe=c2079e6c03) | Nov 23, 2021 |
| HP            | ProBook 4330s               | [74e6151748](https://linux-hardware.org/?probe=74e6151748) | Nov 23, 2021 |
| Dell          | Latitude E6230              | [5df4406c5b](https://linux-hardware.org/?probe=5df4406c5b) | Nov 23, 2021 |
| Toshiba       | NB550D                      | [ff322fa9a1](https://linux-hardware.org/?probe=ff322fa9a1) | Nov 21, 2021 |
| Apple         | MacBookPro6,2               | [33f1433007](https://linux-hardware.org/?probe=33f1433007) | Nov 21, 2021 |
| Lenovo        | G550 20023                  | [531304bd76](https://linux-hardware.org/?probe=531304bd76) | Nov 20, 2021 |
| MSI           | CR610                       | [63411cafc4](https://linux-hardware.org/?probe=63411cafc4) | Nov 20, 2021 |
| MSI           | CR610                       | [6f2f218e21](https://linux-hardware.org/?probe=6f2f218e21) | Nov 20, 2021 |
| Lenovo        | G550 20023                  | [ce28fd38d4](https://linux-hardware.org/?probe=ce28fd38d4) | Nov 20, 2021 |
| HP            | ENVY 15                     | [f4752615c9](https://linux-hardware.org/?probe=f4752615c9) | Nov 19, 2021 |
| Lenovo        | ThinkPad T530 2429NL6       | [44649d8cb3](https://linux-hardware.org/?probe=44649d8cb3) | Nov 19, 2021 |
| Lenovo        | ThinkPad T530 2429NL6       | [40e07deebb](https://linux-hardware.org/?probe=40e07deebb) | Nov 19, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [2f5c8e09bf](https://linux-hardware.org/?probe=2f5c8e09bf) | Nov 19, 2021 |
| Dell          | Latitude E6410              | [17e575c418](https://linux-hardware.org/?probe=17e575c418) | Nov 19, 2021 |
| Dell          | Latitude E7470              | [9fb42a7a17](https://linux-hardware.org/?probe=9fb42a7a17) | Nov 19, 2021 |
| Apple         | MacBookPro6,2               | [0dd964d22b](https://linux-hardware.org/?probe=0dd964d22b) | Nov 18, 2021 |
| Lenovo        | ThinkPad A475 20KMS0EJ00    | [e029652647](https://linux-hardware.org/?probe=e029652647) | Nov 18, 2021 |
| Fujitsu       | LIFEBOOK U745               | [647cd257ec](https://linux-hardware.org/?probe=647cd257ec) | Nov 18, 2021 |
| Apple         | MacBookPro5,5               | [e56e34b28a](https://linux-hardware.org/?probe=e56e34b28a) | Nov 18, 2021 |
| Apple         | MacBookPro5,5               | [35206eb5d3](https://linux-hardware.org/?probe=35206eb5d3) | Nov 18, 2021 |
| Dell          | Inspiron 5558               | [e86c8890fa](https://linux-hardware.org/?probe=e86c8890fa) | Nov 18, 2021 |
| Lenovo        | ThinkPad A475 20KMS0EJ00    | [26a144a0c7](https://linux-hardware.org/?probe=26a144a0c7) | Nov 17, 2021 |
| Lenovo        | Z50-75 80EC                 | [cbca714862](https://linux-hardware.org/?probe=cbca714862) | Nov 17, 2021 |
| Dell          | Latitude E5430 non-vPro     | [d4cf8a16f2](https://linux-hardware.org/?probe=d4cf8a16f2) | Nov 16, 2021 |
| Dell          | Latitude E5430 non-vPro     | [8d694f749f](https://linux-hardware.org/?probe=8d694f749f) | Nov 16, 2021 |
| Toshiba       | Satellite L750              | [f6ddfdb8ce](https://linux-hardware.org/?probe=f6ddfdb8ce) | Nov 16, 2021 |
| Toshiba       | Satellite L750              | [cc7c9dddca](https://linux-hardware.org/?probe=cc7c9dddca) | Nov 16, 2021 |
| Lenovo        | B50-70 20384                | [da69364d7a](https://linux-hardware.org/?probe=da69364d7a) | Nov 16, 2021 |
| Lenovo        | B50-70 20384                | [ec91da9f30](https://linux-hardware.org/?probe=ec91da9f30) | Nov 16, 2021 |
| Lenovo        | G550 20023                  | [520ebfcf8a](https://linux-hardware.org/?probe=520ebfcf8a) | Nov 16, 2021 |
| HP            | ProBook 4330s               | [4682329a97](https://linux-hardware.org/?probe=4682329a97) | Nov 14, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [1db693cc35](https://linux-hardware.org/?probe=1db693cc35) | Nov 14, 2021 |
| Acer          | Aspire A315-55KG            | [eddf767a4f](https://linux-hardware.org/?probe=eddf767a4f) | Nov 13, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [9b3707de59](https://linux-hardware.org/?probe=9b3707de59) | Nov 13, 2021 |
| Samsung       | NC210/NC110                 | [126116dbac](https://linux-hardware.org/?probe=126116dbac) | Nov 12, 2021 |
| Acer          | Aspire ES1-572              | [871bd7121a](https://linux-hardware.org/?probe=871bd7121a) | Nov 11, 2021 |
| Lenovo        | Z50-75 80EC                 | [f49b4f30dc](https://linux-hardware.org/?probe=f49b4f30dc) | Nov 11, 2021 |
| Dell          | Latitude D630               | [bd546ec46b](https://linux-hardware.org/?probe=bd546ec46b) | Nov 11, 2021 |
| Jumper        | EZbook                      | [f1391c1f4b](https://linux-hardware.org/?probe=f1391c1f4b) | Nov 10, 2021 |
| Dell          | Latitude 7280               | [c59152a648](https://linux-hardware.org/?probe=c59152a648) | Nov 10, 2021 |
| eMachines     | eME732G                     | [1e7c39c762](https://linux-hardware.org/?probe=1e7c39c762) | Nov 09, 2021 |
| Acer          | Aspire A315-55KG            | [14826ce238](https://linux-hardware.org/?probe=14826ce238) | Nov 09, 2021 |
| eMachines     | eME732G                     | [b0c186d2e4](https://linux-hardware.org/?probe=b0c186d2e4) | Nov 09, 2021 |
| HP            | Pavilion Notebook           | [6ed0c89edd](https://linux-hardware.org/?probe=6ed0c89edd) | Nov 08, 2021 |
| Toshiba       | Satellite L500              | [82d6b16382](https://linux-hardware.org/?probe=82d6b16382) | Nov 08, 2021 |
| Toshiba       | Satellite L500              | [70e2057cff](https://linux-hardware.org/?probe=70e2057cff) | Nov 07, 2021 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [3ad8721d2a](https://linux-hardware.org/?probe=3ad8721d2a) | Nov 07, 2021 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [0807858e11](https://linux-hardware.org/?probe=0807858e11) | Nov 07, 2021 |
| Dell          | Vostro 1540                 | [1372b6afee](https://linux-hardware.org/?probe=1372b6afee) | Nov 07, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | [6787f46858](https://linux-hardware.org/?probe=6787f46858) | Nov 06, 2021 |
| Sony          | VPCEH2J1E                   | [02a4a3ea01](https://linux-hardware.org/?probe=02a4a3ea01) | Nov 06, 2021 |
| HP            | 250 G4                      | [8167957b46](https://linux-hardware.org/?probe=8167957b46) | Nov 06, 2021 |
| Sony          | SVS13118GBB                 | [741a2c8c9e](https://linux-hardware.org/?probe=741a2c8c9e) | Nov 06, 2021 |
| ASUSTek       | K53U                        | [6c7d579e49](https://linux-hardware.org/?probe=6c7d579e49) | Nov 05, 2021 |
| ASUSTek       | K50IN                       | [8c356405f0](https://linux-hardware.org/?probe=8c356405f0) | Nov 05, 2021 |
| Toshiba       | Satellite U400              | [7b2364e53a](https://linux-hardware.org/?probe=7b2364e53a) | Nov 04, 2021 |
| Lenovo        | G505s 20255                 | [c9fb91eefc](https://linux-hardware.org/?probe=c9fb91eefc) | Nov 04, 2021 |
| ASUSTek       | K53U                        | [15adf4f30a](https://linux-hardware.org/?probe=15adf4f30a) | Nov 03, 2021 |
| ASUSTek       | K50IN                       | [570da581ab](https://linux-hardware.org/?probe=570da581ab) | Nov 02, 2021 |
| Dell          | Vostro 1540                 | [0e6d351a5f](https://linux-hardware.org/?probe=0e6d351a5f) | Nov 01, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | [e5a8a22561](https://linux-hardware.org/?probe=e5a8a22561) | Nov 01, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [f55ff834af](https://linux-hardware.org/?probe=f55ff834af) | Nov 01, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [56fe9a754b](https://linux-hardware.org/?probe=56fe9a754b) | Nov 01, 2021 |
| Dell          | Latitude E6530              | [40d78b6ddd](https://linux-hardware.org/?probe=40d78b6ddd) | Nov 01, 2021 |
| Acer          | TravelMate 8571             | [57ed306b65](https://linux-hardware.org/?probe=57ed306b65) | Oct 31, 2021 |
| Dell          | Vostro 1700                 | [a9ba9df656](https://linux-hardware.org/?probe=a9ba9df656) | Oct 30, 2021 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [1517ac0d45](https://linux-hardware.org/?probe=1517ac0d45) | Oct 30, 2021 |
| HP            | Pavilion 15                 | [1014243935](https://linux-hardware.org/?probe=1014243935) | Oct 29, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [dad06f3e70](https://linux-hardware.org/?probe=dad06f3e70) | Oct 29, 2021 |
| Lenovo        | G570 20079                  | [b2f7ab7e8a](https://linux-hardware.org/?probe=b2f7ab7e8a) | Oct 28, 2021 |
| Lenovo        | G570 20079                  | [b16cb4d0dc](https://linux-hardware.org/?probe=b16cb4d0dc) | Oct 28, 2021 |
| HP            | EliteBook 6930p             | [77895f2a3b](https://linux-hardware.org/?probe=77895f2a3b) | Oct 28, 2021 |
| HP            | ProBook 6475b               | [c4c890f06a](https://linux-hardware.org/?probe=c4c890f06a) | Oct 27, 2021 |
| Lenovo        | G70-70 80HW                 | [3cdde1061c](https://linux-hardware.org/?probe=3cdde1061c) | Oct 26, 2021 |
| HP            | ProBook 6470b               | [1b2fbcdfa0](https://linux-hardware.org/?probe=1b2fbcdfa0) | Oct 26, 2021 |
| HP            | OMEN by Laptop 17-an0xx     | [57cd00ef8b](https://linux-hardware.org/?probe=57cd00ef8b) | Oct 25, 2021 |
| HP            | OMEN by Laptop 17-an0xx     | [e6f20aae28](https://linux-hardware.org/?probe=e6f20aae28) | Oct 24, 2021 |
| HP            | ProBook 6470b               | [bef890f3d9](https://linux-hardware.org/?probe=bef890f3d9) | Oct 23, 2021 |
| HP            | Presario CQ57               | [8e3ceb5db9](https://linux-hardware.org/?probe=8e3ceb5db9) | Oct 23, 2021 |
| HP            | 255 G5 Notebook PC          | [421c375338](https://linux-hardware.org/?probe=421c375338) | Oct 22, 2021 |
| Acer          | Aspire A315-53G             | [ebb8572b41](https://linux-hardware.org/?probe=ebb8572b41) | Oct 22, 2021 |
| Fujitsu Si... | AMILO Li1705                | [a61c777014](https://linux-hardware.org/?probe=a61c777014) | Oct 21, 2021 |
| Fujitsu Si... | AMILO Li1705                | [3a627aab0a](https://linux-hardware.org/?probe=3a627aab0a) | Oct 21, 2021 |
| Acer          | Aspire A315-53G             | [9231eabdb2](https://linux-hardware.org/?probe=9231eabdb2) | Oct 21, 2021 |
| HP            | Presario CQ57               | [78828b2790](https://linux-hardware.org/?probe=78828b2790) | Oct 21, 2021 |
| HP            | 250 G1                      | [b0ed67249e](https://linux-hardware.org/?probe=b0ed67249e) | Oct 21, 2021 |
| HP            | 250 G1                      | [0790e099fa](https://linux-hardware.org/?probe=0790e099fa) | Oct 21, 2021 |
| speedmaste... | E131x series                | [44a79e6330](https://linux-hardware.org/?probe=44a79e6330) | Oct 21, 2021 |
| speedmaste... | E131x series                | [e539db1fcd](https://linux-hardware.org/?probe=e539db1fcd) | Oct 20, 2021 |
| Fujitsu       | LIFEBOOK AH531              | [e8729886f0](https://linux-hardware.org/?probe=e8729886f0) | Oct 19, 2021 |
| Fujitsu       | LIFEBOOK A530               | [1c293cc8f0](https://linux-hardware.org/?probe=1c293cc8f0) | Oct 18, 2021 |
| HP            | 650                         | [f27e07a82b](https://linux-hardware.org/?probe=f27e07a82b) | Oct 17, 2021 |
| Lenovo        | Z710 20250                  | [d2a9cd32b1](https://linux-hardware.org/?probe=d2a9cd32b1) | Oct 17, 2021 |
| Acer          | Aspire A315-21G             | [e740a4de27](https://linux-hardware.org/?probe=e740a4de27) | Oct 17, 2021 |
| Fujitsu       | LIFEBOOK A512               | [7a71621dde](https://linux-hardware.org/?probe=7a71621dde) | Oct 17, 2021 |
| Dell          | Latitude D630               | [b3e12559af](https://linux-hardware.org/?probe=b3e12559af) | Oct 17, 2021 |
| ASUSTek       | N50Vn                       | [3494a7c5b6](https://linux-hardware.org/?probe=3494a7c5b6) | Oct 16, 2021 |
| ASUSTek       | N50Vn                       | [a725c6feba](https://linux-hardware.org/?probe=a725c6feba) | Oct 16, 2021 |
| Fujitsu       | LIFEBOOK A530               | [8bf8b89539](https://linux-hardware.org/?probe=8bf8b89539) | Oct 15, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [70cb0eacd3](https://linux-hardware.org/?probe=70cb0eacd3) | Oct 15, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [b2342ea37d](https://linux-hardware.org/?probe=b2342ea37d) | Oct 15, 2021 |
| Lenovo        | ThinkPad R500 27147KG       | [610e2ba453](https://linux-hardware.org/?probe=610e2ba453) | Oct 14, 2021 |
| HP            | Presario CQ58               | [595d5385bc](https://linux-hardware.org/?probe=595d5385bc) | Oct 14, 2021 |
| HP            | Presario CQ58               | [8c8587b079](https://linux-hardware.org/?probe=8c8587b079) | Oct 14, 2021 |
| HP            | 250 G1                      | [2ec296247f](https://linux-hardware.org/?probe=2ec296247f) | Oct 14, 2021 |
| HP            | 250 G1                      | [c0cff54f9d](https://linux-hardware.org/?probe=c0cff54f9d) | Oct 14, 2021 |
| Toshiba       | Satellite C55D-A            | [087fc97d07](https://linux-hardware.org/?probe=087fc97d07) | Oct 13, 2021 |
| Fujitsu Si... | AMILO Xi 3650               | [6b1cf875fd](https://linux-hardware.org/?probe=6b1cf875fd) | Oct 11, 2021 |
| HUAWEI        | HVY-WXX9                    | [0ef9f6ae5f](https://linux-hardware.org/?probe=0ef9f6ae5f) | Oct 11, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [bf181ddf64](https://linux-hardware.org/?probe=bf181ddf64) | Oct 10, 2021 |
| HP            | ProBook 645 G1              | [102902cf2b](https://linux-hardware.org/?probe=102902cf2b) | Oct 10, 2021 |
| HP            | Pavilion dv6                | [dbfa388218](https://linux-hardware.org/?probe=dbfa388218) | Oct 10, 2021 |
| Lenovo        | E50-80 80J2                 | [80fc6ad252](https://linux-hardware.org/?probe=80fc6ad252) | Oct 08, 2021 |
| Lenovo        | E50-80 80J2                 | [ffdda637c6](https://linux-hardware.org/?probe=ffdda637c6) | Oct 08, 2021 |
| Dell          | Inspiron M5040              | [170de9cffb](https://linux-hardware.org/?probe=170de9cffb) | Oct 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [fe285a30ea](https://linux-hardware.org/?probe=fe285a30ea) | Oct 07, 2021 |
| Dell          | Studio XPS 1340             | [e54daea8f9](https://linux-hardware.org/?probe=e54daea8f9) | Oct 06, 2021 |
| Dell          | Studio XPS 1340             | [ed56dc2a85](https://linux-hardware.org/?probe=ed56dc2a85) | Oct 06, 2021 |
| Dell          | Inspiron 3537               | [db580317ec](https://linux-hardware.org/?probe=db580317ec) | Oct 01, 2021 |
| Fujitsu       | LIFEBOOK AH531              | [4df59159e7](https://linux-hardware.org/?probe=4df59159e7) | Sep 30, 2021 |
| Fujitsu       | LIFEBOOK AH531              | [36d1048928](https://linux-hardware.org/?probe=36d1048928) | Sep 30, 2021 |
| Fujitsu       | LIFEBOOK AH531              | [fbf1e4bd46](https://linux-hardware.org/?probe=fbf1e4bd46) | Sep 30, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/BlackPanther/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| BlackPanther 18.1 | 1534      | 88.82%  |
| BlackPanther 16.2 | 185       | 10.71%  |
| BlackPanther 22.1 | 7         | 0.41%   |
| BlackPanther 16.1 | 1         | 0.06%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| BlackPanther | 1694      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 4.18.16-desktop-1bP     | 1136      | 59.57%  |
| 5.6.14-desktop-2bP      | 465       | 24.38%  |
| 4.9.20-desktop-pae-1bP  | 175       | 9.18%   |
| 5.1.15-desktop-1bP      | 79        | 4.14%   |
| 5.15.85-desktop-1bP     | 25        | 1.31%   |
| 4.9.20-desktop-1bP      | 5         | 0.26%   |
| 4.7.0-desktop-1bP       | 3         | 0.16%   |
| 6.4.3-desktop-1bP       | 2         | 0.1%    |
| 6.3.8-desktop-1bP       | 2         | 0.1%    |
| 6.3.3-desktop-1bP       | 2         | 0.1%    |
| 6.2.9-desktop-1bP       | 2         | 0.1%    |
| 5.10.1-desktop-1bP      | 2         | 0.1%    |
| 4.14.14-desktop-pae-1bP | 2         | 0.1%    |
| 6.1.0-1bP               | 1         | 0.05%   |
| 5.8.11-desktop-2bP      | 1         | 0.05%   |
| 5.6.14-server-2bP       | 1         | 0.05%   |
| 5.15.6-desktop-1bP      | 1         | 0.05%   |
| 5.10.1-desktop-2bP      | 1         | 0.05%   |
| 5.1.15-server-1bP       | 1         | 0.05%   |
| 4.15.0-desktop-pae-1bP  | 1         | 0.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.16 | 1136      | 59.6%   |
| 5.6.14  | 466       | 24.45%  |
| 4.9.20  | 180       | 9.44%   |
| 5.1.15  | 79        | 4.14%   |
| 5.15.85 | 25        | 1.31%   |
| 5.10.1  | 3         | 0.16%   |
| 4.7.0   | 3         | 0.16%   |
| 6.4.3   | 2         | 0.1%    |
| 6.3.8   | 2         | 0.1%    |
| 6.3.3   | 2         | 0.1%    |
| 6.2.9   | 2         | 0.1%    |
| 4.14.14 | 2         | 0.1%    |
| 6.1.0   | 1         | 0.05%   |
| 5.8.11  | 1         | 0.05%   |
| 5.15.6  | 1         | 0.05%   |
| 4.15.0  | 1         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 1136      | 59.63%  |
| 5.6     | 466       | 24.46%  |
| 4.9     | 180       | 9.45%   |
| 5.1     | 79        | 4.15%   |
| 5.15    | 26        | 1.36%   |
| 6.3     | 3         | 0.16%   |
| 5.10    | 3         | 0.16%   |
| 4.7     | 3         | 0.16%   |
| 6.4     | 2         | 0.1%    |
| 6.2     | 2         | 0.1%    |
| 4.14    | 2         | 0.1%    |
| 6.1     | 1         | 0.05%   |
| 5.8     | 1         | 0.05%   |
| 4.15    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1537      | 89.2%   |
| i686   | 186       | 10.8%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 1681      | 98.88%  |
| Unknown  | 14        | 0.82%   |
| KDE      | 3         | 0.18%   |
| Cinnamon | 1         | 0.06%   |
| Budgie   | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1691      | 99.71%  |
| Wayland | 4         | 0.24%   |
| Unknown | 1         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 1689      | 99.47%  |
| Unknown | 8         | 0.47%   |
| LightDM | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1693      | 99.76%  |
| hu_HU   | 4         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1179      | 66.24%  |
| EFI  | 601       | 33.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Overlay | 1123      | 58.61%  |
| Ext4    | 778       | 40.61%  |
| Unknown | 6         | 0.31%   |
| Ext2    | 3         | 0.16%   |
| Ext3    | 2         | 0.1%    |
| Btrfs   | 2         | 0.1%    |
| Xfs     | 1         | 0.05%   |
| Ntfs    | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 1133      | 63.4%   |
| GPT     | 639       | 35.76%  |
| Unknown | 15        | 0.84%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1211      | 64.48%  |
| Yes       | 667       | 35.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 955       | 52.19%  |
| Yes       | 875       | 47.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 357       | 21.07%  |
| Lenovo                         | 303       | 17.89%  |
| Dell                           | 251       | 14.82%  |
| ASUSTek Computer               | 227       | 13.4%   |
| Acer                           | 195       | 11.51%  |
| Toshiba                        | 79        | 4.66%   |
| Samsung Electronics            | 39        | 2.3%    |
| Fujitsu                        | 30        | 1.77%   |
| Packard Bell                   | 26        | 1.53%   |
| Fujitsu Siemens                | 26        | 1.53%   |
| Sony                           | 23        | 1.36%   |
| MSI                            | 23        | 1.36%   |
| eMachines                      | 19        | 1.12%   |
| Medion                         | 15        | 0.89%   |
| Apple                          | 15        | 0.89%   |
| Alcor                          | 6         | 0.35%   |
| Hungaro Flotta Kft             | 5         | 0.3%    |
| Gateway                        | 4         | 0.24%   |
| BANGHO                         | 4         | 0.24%   |
| Unknown                        | 4         | 0.24%   |
| Insyde                         | 3         | 0.18%   |
| speedmaster                    | 2         | 0.12%   |
| Positivo                       | 2         | 0.12%   |
| Panasonic                      | 2         | 0.12%   |
| Notebook                       | 2         | 0.12%   |
| Jumper                         | 2         | 0.12%   |
| Intel                          | 2         | 0.12%   |
| Gigabyte Technology            | 2         | 0.12%   |
| Alienware                      | 2         | 0.12%   |
| TUXEDO                         | 1         | 0.06%   |
| Timi                           | 1         | 0.06%   |
| THD                            | 1         | 0.06%   |
| RM                             | 1         | 0.06%   |
| Philco                         | 1         | 0.06%   |
| Pegatron                       | 1         | 0.06%   |
| ONE-NETBOOK TECHNOLOGY         | 1         | 0.06%   |
| NOBLEX                         | 1         | 0.06%   |
| NEC Computers                  | 1         | 0.06%   |
| Minix                          | 1         | 0.06%   |
| Matsushita Electric Industrial | 1         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| HP 250 G1                            | 40        | 2.36%   |
| Dell Latitude E6410                  | 19        | 1.12%   |
| HP Notebook                          | 15        | 0.89%   |
| Unknown                              | 14        | 0.83%   |
| Lenovo IdeaPad 330-15IKB 81DE        | 11        | 0.65%   |
| Lenovo G50-45 80E3                   | 10        | 0.59%   |
| Toshiba Satellite C660               | 9         | 0.53%   |
| Lenovo IdeaPad 100-15IBD 80QQ        | 9         | 0.53%   |
| HP Pavilion g6                       | 9         | 0.53%   |
| HP 650                               | 9         | 0.53%   |
| ASUS X550CC                          | 8         | 0.47%   |
| ASUS K50IJ                           | 8         | 0.47%   |
| HP Pavilion Notebook                 | 7         | 0.41%   |
| HP 620                               | 7         | 0.41%   |
| Dell Latitude E6430                  | 7         | 0.41%   |
| Dell Latitude E6400                  | 7         | 0.41%   |
| ASUS VivoBook 15_ASUS Laptop X540UBR | 7         | 0.41%   |
| HP Pavilion dv6                      | 6         | 0.35%   |
| HP EliteBook 8470p                   | 6         | 0.35%   |
| HP EliteBook 8460p                   | 6         | 0.35%   |
| Dell Latitude E6420                  | 6         | 0.35%   |
| Dell Latitude E4310                  | 6         | 0.35%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR | 6         | 0.35%   |
| Acer Aspire 5732Z                    | 6         | 0.35%   |
| Toshiba Satellite L300               | 5         | 0.3%    |
| Lenovo Z50-75 80EC                   | 5         | 0.3%    |
| Lenovo G550 20023                    | 5         | 0.3%    |
| Lenovo G505s 20255                   | 5         | 0.3%    |
| Lenovo G50-30 80G0                   | 5         | 0.3%    |
| HP ProBook 6450b                     | 5         | 0.3%    |
| HP EliteBook 8440p                   | 5         | 0.3%    |
| HP EliteBook 6930p                   | 5         | 0.3%    |
| HP 250 G5 Notebook PC                | 5         | 0.3%    |
| HP 15                                | 5         | 0.3%    |
| eMachines E725                       | 5         | 0.3%    |
| eMachines E525                       | 5         | 0.3%    |
| Dell Latitude E7240                  | 5         | 0.3%    |
| Dell Latitude E5420                  | 5         | 0.3%    |
| Dell Latitude D630                   | 5         | 0.3%    |
| Dell Inspiron 3521                   | 5         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Acer Aspire              | 151       | 8.91%   |
| Dell Latitude            | 124       | 7.32%   |
| Lenovo ThinkPad          | 110       | 6.49%   |
| Dell Inspiron            | 91        | 5.37%   |
| Lenovo IdeaPad           | 87        | 5.14%   |
| Toshiba Satellite        | 71        | 4.19%   |
| HP EliteBook             | 58        | 3.42%   |
| HP 250                   | 52        | 3.07%   |
| HP ProBook               | 51        | 3.01%   |
| HP Pavilion              | 48        | 2.83%   |
| HP Compaq                | 37        | 2.18%   |
| ASUS VivoBook            | 29        | 1.71%   |
| Packard Bell EasyNote    | 25        | 1.48%   |
| Fujitsu LIFEBOOK         | 23        | 1.36%   |
| Fujitsu Siemens AMILO    | 18        | 1.06%   |
| Acer TravelMate          | 17        | 1%      |
| HP Notebook              | 15        | 0.89%   |
| HP Laptop                | 15        | 0.89%   |
| Unknown                  | 14        | 0.83%   |
| Lenovo G50-45            | 10        | 0.59%   |
| Dell Vostro              | 10        | 0.59%   |
| Dell Precision           | 10        | 0.59%   |
| Lenovo 3000              | 9         | 0.53%   |
| HP 650                   | 9         | 0.53%   |
| HP Presario              | 8         | 0.47%   |
| ASUS X550CC              | 8         | 0.47%   |
| ASUS K50IJ               | 8         | 0.47%   |
| HP 620                   | 7         | 0.41%   |
| HP 255                   | 7         | 0.41%   |
| HP 15                    | 6         | 0.35%   |
| Lenovo Z50-75            | 5         | 0.3%    |
| Lenovo G580              | 5         | 0.3%    |
| Lenovo G550              | 5         | 0.3%    |
| Lenovo G505s             | 5         | 0.3%    |
| Lenovo G50-30            | 5         | 0.3%    |
| Hungaro Flotta Kft Navon | 5         | 0.3%    |
| Fujitsu Siemens LIFEBOOK | 5         | 0.3%    |
| eMachines E725           | 5         | 0.3%    |
| eMachines E525           | 5         | 0.3%    |
| Dell System              | 5         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 217       | 12.81%  |
| 2013    | 188       | 11.1%   |
| 2010    | 183       | 10.8%   |
| 2012    | 148       | 8.74%   |
| 2008    | 140       | 8.26%   |
| 2014    | 128       | 7.56%   |
| 2009    | 119       | 7.02%   |
| 2016    | 101       | 5.96%   |
| 2015    | 98        | 5.79%   |
| 2007    | 90        | 5.31%   |
| 2018    | 85        | 5.02%   |
| 2017    | 80        | 4.72%   |
| 2019    | 42        | 2.48%   |
| 2006    | 39        | 2.3%    |
| 2020    | 20        | 1.18%   |
| 2005    | 9         | 0.53%   |
| 2021    | 6         | 0.35%   |
| Unknown | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1694      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1694      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1693      | 99.94%  |
| Yes  | 1         | 0.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 708       | 40.57%  |
| 4.01-8.0   | 368       | 21.09%  |
| 1.01-2.0   | 237       | 13.58%  |
| 8.01-16.0  | 224       | 12.84%  |
| 2.01-3.0   | 86        | 4.93%   |
| 16.01-24.0 | 71        | 4.07%   |
| 0.51-1.0   | 35        | 2.01%   |
| 24.01-32.0 | 8         | 0.46%   |
| 32.01-64.0 | 7         | 0.4%    |
| Unknown    | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.51-1.0  | 1052      | 52.78%  |
| 1.01-2.0  | 595       | 29.85%  |
| 0.01-0.5  | 266       | 13.35%  |
| 2.01-3.0  | 52        | 2.61%   |
| 3.01-4.0  | 17        | 0.85%   |
| 4.01-8.0  | 9         | 0.45%   |
| 8.01-16.0 | 1         | 0.05%   |
| Unknown   | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1434      | 80.61%  |
| 2      | 290       | 16.3%   |
| 3      | 35        | 1.97%   |
| 0      | 16        | 0.9%    |
| 4      | 3         | 0.17%   |
| 5      | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1136      | 66.24%  |
| No        | 579       | 33.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1586      | 93.57%  |
| No        | 109       | 6.43%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1670      | 98.58%  |
| No        | 24        | 1.42%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1188      | 68.87%  |
| No        | 537       | 31.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Hungary     | 1206      | 70.65%  |
| Germany     | 93        | 5.45%   |
| USA         | 74        | 4.34%   |
| Slovakia    | 34        | 1.99%   |
| Romania     | 31        | 1.82%   |
| UK          | 28        | 1.64%   |
| Austria     | 21        | 1.23%   |
| Italy       | 20        | 1.17%   |
| France      | 19        | 1.11%   |
| Argentina   | 17        | 1%      |
| Spain       | 16        | 0.94%   |
| Canada      | 16        | 0.94%   |
| Japan       | 11        | 0.64%   |
| Brazil      | 11        | 0.64%   |
| Serbia      | 10        | 0.59%   |
| Poland      | 7         | 0.41%   |
| Russia      | 6         | 0.35%   |
| Australia   | 6         | 0.35%   |
| Switzerland | 5         | 0.29%   |
| Belgium     | 5         | 0.29%   |
| Sweden      | 4         | 0.23%   |
| Ireland     | 4         | 0.23%   |
| Netherlands | 3         | 0.18%   |
| Greece      | 3         | 0.18%   |
| Finland     | 3         | 0.18%   |
| Czechia     | 3         | 0.18%   |
| China       | 3         | 0.18%   |
| UAE         | 2         | 0.12%   |
| Turkey      | 2         | 0.12%   |
| Puerto Rico | 2         | 0.12%   |
| Philippines | 2         | 0.12%   |
| Moldova     | 2         | 0.12%   |
| Mexico      | 2         | 0.12%   |
| Madagascar  | 2         | 0.12%   |
| Israel      | 2         | 0.12%   |
| Indonesia   | 2         | 0.12%   |
| India       | 2         | 0.12%   |
| Ghana       | 2         | 0.12%   |
| Ecuador     | 2         | 0.12%   |
| Cyprus      | 2         | 0.12%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Budapest          | 460       | 22.31%  |
| Pécs             | 29        | 1.41%   |
| Miskolc           | 29        | 1.41%   |
| Győr             | 29        | 1.41%   |
| Debrecen          | 29        | 1.41%   |
| Tatabánya        | 28        | 1.36%   |
| Veszprém         | 23        | 1.12%   |
| Szeged            | 23        | 1.12%   |
| Székesfehérvár | 22        | 1.07%   |
| Zalaegerszeg      | 21        | 1.02%   |
| Nyiregyhaza       | 20        | 0.97%   |
| Szolnok           | 17        | 0.82%   |
| Szombathely       | 16        | 0.78%   |
| Vienna            | 13        | 0.63%   |
| Toekoel           | 13        | 0.63%   |
| Salgotarjan       | 13        | 0.63%   |
| Szorgalmatos      | 12        | 0.58%   |
| Szekszárd        | 12        | 0.58%   |
| Kecskemét        | 12        | 0.58%   |
| Érd              | 12        | 0.58%   |
| Szigetszentmiklos | 11        | 0.53%   |
| Bratislava        | 11        | 0.53%   |
| Târgu Mureş     | 10        | 0.48%   |
| Regensburg        | 10        | 0.48%   |
| Kiskunfelegyhaza  | 10        | 0.48%   |
| Kazincbarcika     | 10        | 0.48%   |
| Karcag            | 10        | 0.48%   |
| Kaposvár         | 10        | 0.48%   |
| Dunaújváros     | 10        | 0.48%   |
| Cegled            | 9         | 0.44%   |
| Banská Bystrica  | 9         | 0.44%   |
| Ajka              | 9         | 0.44%   |
| Tiszaujvaros      | 8         | 0.39%   |
| Sopron            | 8         | 0.39%   |
| Pomaz             | 8         | 0.39%   |
| Obertraubling     | 8         | 0.39%   |
| Nagykanizsa       | 8         | 0.39%   |
| Tarnok            | 7         | 0.34%   |
| Gyomro            | 7         | 0.34%   |
| Gödöllő        | 7         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 350       | 530    | 16.58%  |
| WDC                 | 303       | 442    | 14.35%  |
| Toshiba             | 231       | 349    | 10.94%  |
| Kingston            | 216       | 334    | 10.23%  |
| Samsung Electronics | 166       | 289    | 7.86%   |
| Hitachi             | 145       | 202    | 6.87%   |
| HGST                | 145       | 208    | 6.87%   |
| Unknown             | 73        | 113    | 3.46%   |
| SanDisk             | 70        | 130    | 3.32%   |
| Fujitsu             | 45        | 55     | 2.13%   |
| Intel               | 34        | 51     | 1.61%   |
| A-DATA Technology   | 34        | 47     | 1.61%   |
| Crucial             | 32        | 44     | 1.52%   |
| SK hynix            | 26        | 36     | 1.23%   |
| Micron Technology   | 17        | 35     | 0.81%   |
| Apacer              | 17        | 26     | 0.81%   |
| Intenso             | 16        | 33     | 0.76%   |
| PNY                 | 15        | 19     | 0.71%   |
| SPCC                | 14        | 18     | 0.66%   |
| JMicron Technology  | 14        | 15     | 0.66%   |
| Patriot             | 13        | 18     | 0.62%   |
| LITEON              | 12        | 16     | 0.57%   |
| China               | 12        | 23     | 0.57%   |
| LITEONIT            | 8         | 13     | 0.38%   |
| Transcend           | 7         | 7      | 0.33%   |
| Kingmax             | 7         | 7      | 0.33%   |
| OCZ                 | 6         | 7      | 0.28%   |
| Gigabyte Technology | 6         | 9      | 0.28%   |
| Team                | 4         | 7      | 0.19%   |
| KingSpec            | 4         | 5      | 0.19%   |
| BHT                 | 4         | 4      | 0.19%   |
| Apple               | 4         | 6      | 0.19%   |
| Verbatim            | 3         | 6      | 0.14%   |
| SSSTC               | 3         | 9      | 0.14%   |
| Netac               | 3         | 3      | 0.14%   |
| Hewlett-Packard     | 3         | 3      | 0.14%   |
| GOODRAM             | 3         | 3      | 0.14%   |
| Unknown             | 3         | 4      | 0.14%   |
| ShanDianZhe         | 2         | 2      | 0.09%   |
| Plextor             | 2         | 3      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 52        | 2.37%   |
| Kingston SA400S37120G 120GB SSD    | 51        | 2.33%   |
| Seagate ST1000LM035-1RK172 1TB     | 47        | 2.14%   |
| Toshiba MQ01ABD100 1TB             | 38        | 1.73%   |
| Toshiba MQ01ABF050 500GB           | 36        | 1.64%   |
| Seagate ST500LT012-1DG142 500GB    | 36        | 1.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 34        | 1.55%   |
| HGST HTS545050A7E680 500GB         | 34        | 1.55%   |
| HGST HTS545032A7E380 320GB         | 33        | 1.51%   |
| Kingston SV300S37A120G 120GB SSD   | 26        | 1.19%   |
| Kingston SA400S37480G 480GB SSD    | 22        | 1%      |
| Seagate ST9320325AS 320GB          | 20        | 0.91%   |
| Seagate ST9500325AS 500GB          | 19        | 0.87%   |
| WDC WD10JPVX-22JC3T0 1TB           | 18        | 0.82%   |
| Toshiba MQ04ABF100 1TB             | 18        | 0.82%   |
| Seagate ST9250315AS 250GB          | 14        | 0.64%   |
| HGST HTS721010A9E630 1TB           | 14        | 0.64%   |
| Kingston SUV400S37120G 120GB SSD   | 13        | 0.59%   |
| HGST HTS725050A7E630 500GB         | 13        | 0.59%   |
| HGST HTS541010A9E680 1TB           | 13        | 0.59%   |
| Seagate ST500LT012-9WS142 500GB    | 12        | 0.55%   |
| HGST HTS545050A7E380 500GB         | 12        | 0.55%   |
| Toshiba MQ01ABD050 500GB           | 11        | 0.5%    |
| Seagate ST500LM000-1EJ162 500GB    | 11        | 0.5%    |
| Seagate M3 Portable 1TB            | 11        | 0.5%    |
| Samsung SSD 860 EVO 500GB          | 11        | 0.5%    |
| WDC WD1600BEVT-22ZCT0 160GB        | 10        | 0.46%   |
| Samsung SSD 850 EVO 250GB          | 10        | 0.46%   |
| Samsung HM160HI 160GB              | 10        | 0.46%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 9         | 0.41%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 9         | 0.41%   |
| Toshiba MQ01ABD075 752GB           | 9         | 0.41%   |
| Hitachi HTS723232A7A364 320GB      | 9         | 0.41%   |
| Hitachi HTS543232A7A384 320GB      | 9         | 0.41%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 8         | 0.36%   |
| WDC WD2500BEVS-22UST0 250GB        | 8         | 0.36%   |
| WDC WD10JPVX-60JC3T0 1TB           | 8         | 0.36%   |
| Hitachi HTS547550A9E384 500GB      | 8         | 0.36%   |
| Hitachi HTS545025B9A300 250GB      | 8         | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 7         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 339       | 514    | 27.99%  |
| WDC                 | 276       | 397    | 22.79%  |
| Toshiba             | 210       | 302    | 17.34%  |
| Hitachi             | 145       | 202    | 11.97%  |
| HGST                | 145       | 208    | 11.97%  |
| Fujitsu             | 45        | 55     | 3.72%   |
| Samsung Electronics | 32        | 44     | 2.64%   |
| JMicron Technology  | 8         | 8      | 0.66%   |
| Unknown             | 3         | 4      | 0.25%   |
| IBM/Hitachi         | 2         | 3      | 0.17%   |
| QC-FT-D             | 1         | 1      | 0.08%   |
| MARSHAL             | 1         | 2      | 0.08%   |
| Initio              | 1         | 2      | 0.08%   |
| IB-1122             | 1         | 1      | 0.08%   |
| HGST HTS            | 1         | 6      | 0.08%   |
| CSD                 | 1         | 2      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 210       | 321    | 29.01%  |
| Samsung Electronics | 108       | 182    | 14.92%  |
| SanDisk             | 60        | 114    | 8.29%   |
| Crucial             | 32        | 44     | 4.42%   |
| A-DATA Technology   | 32        | 45     | 4.42%   |
| Intel               | 27        | 41     | 3.73%   |
| WDC                 | 25        | 37     | 3.45%   |
| SK hynix            | 23        | 30     | 3.18%   |
| Intenso             | 16        | 33     | 2.21%   |
| PNY                 | 15        | 19     | 2.07%   |
| Micron Technology   | 15        | 28     | 2.07%   |
| Apacer              | 15        | 24     | 2.07%   |
| SPCC                | 13        | 17     | 1.8%    |
| Patriot             | 13        | 18     | 1.8%    |
| China               | 12        | 23     | 1.66%   |
| Toshiba             | 11        | 27     | 1.52%   |
| LITEON              | 11        | 15     | 1.52%   |
| LITEONIT            | 8         | 13     | 1.1%    |
| Transcend           | 7         | 7      | 0.97%   |
| Kingmax             | 7         | 7      | 0.97%   |
| OCZ                 | 6         | 7      | 0.83%   |
| Gigabyte Technology | 6         | 9      | 0.83%   |
| Team                | 4         | 7      | 0.55%   |
| KingSpec            | 4         | 5      | 0.55%   |
| BHT                 | 4         | 4      | 0.55%   |
| Apple               | 4         | 6      | 0.55%   |
| Verbatim            | 3         | 6      | 0.41%   |
| Netac               | 3         | 3      | 0.41%   |
| GOODRAM             | 3         | 3      | 0.41%   |
| ShanDianZhe         | 2         | 2      | 0.28%   |
| HS-SSD-C100         | 2         | 2      | 0.28%   |
| Hewlett-Packard     | 2         | 3      | 0.28%   |
| Corsair             | 2         | 3      | 0.28%   |
| Zheino              | 1         | 1      | 0.14%   |
| Unknown             | 1         | 3      | 0.14%   |
| Union Memory        | 1         | 5      | 0.14%   |
| Timetec             | 1         | 4      | 0.14%   |
| TCSUNBOW            | 1         | 1      | 0.14%   |
| T-FORCE             | 1         | 1      | 0.14%   |
| Solid               | 1         | 6      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1143      | 1751   | 57.47%  |
| SSD     | 666       | 1140   | 33.48%  |
| MMC     | 84        | 130    | 4.22%   |
| NVMe    | 69        | 146    | 3.47%   |
| Unknown | 27        | 30     | 1.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1612      | 2826   | 87.94%  |
| MMC  | 84        | 130    | 4.58%   |
| NVMe | 69        | 146    | 3.76%   |
| SAS  | 68        | 95     | 3.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1373      | 2281   | 78.95%  |
| 0.51-1.0   | 343       | 570    | 19.72%  |
| 1.01-2.0   | 20        | 37     | 1.15%   |
| 4.01-10.0  | 3         | 3      | 0.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 1069      | 52.82%  |
| 101-250        | 369       | 18.23%  |
| 251-500        | 220       | 10.87%  |
| 51-100         | 134       | 6.62%   |
| 501-1000       | 84        | 4.15%   |
| 21-50          | 81        | 4%      |
| 1-20           | 27        | 1.33%   |
| 1001-2000      | 25        | 1.24%   |
| 2001-3000      | 13        | 0.64%   |
| More than 3000 | 1         | 0.05%   |
| 0              | 1         | 0.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| Unknown   | 1069      | 52.53%  |
| 1-20      | 716       | 35.18%  |
| 21-50     | 83        | 4.08%   |
| 51-100    | 60        | 2.95%   |
| 101-250   | 50        | 2.46%   |
| 251-500   | 28        | 1.38%   |
| 1001-2000 | 14        | 0.69%   |
| 501-1000  | 13        | 0.64%   |
| 2001-3000 | 1         | 0.05%   |
| 0         | 1         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| HGST HTS545032A7E380 320GB              | 32        | 47     | 5.26%   |
| HGST HTS545050A7E680 500GB              | 24        | 33     | 3.95%   |
| Seagate ST500LT012-1DG142 500GB         | 14        | 20     | 2.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 12        | 16     | 1.97%   |
| Toshiba MQ01ABD100 1TB                  | 11        | 12     | 1.81%   |
| Seagate ST9500325AS 500GB               | 11        | 16     | 1.81%   |
| Toshiba MQ01ABF050 500GB                | 10        | 30     | 1.64%   |
| Seagate ST9320325AS 320GB               | 10        | 21     | 1.64%   |
| Seagate ST500LT012-9WS142 500GB         | 10        | 12     | 1.64%   |
| Seagate ST9250315AS 250GB               | 9         | 11     | 1.48%   |
| Samsung Electronics HM160HI 160GB       | 9         | 14     | 1.48%   |
| HGST HTS541010A9E680 1TB                | 9         | 19     | 1.48%   |
| Hitachi HTS723232A7A364 320GB           | 8         | 8      | 1.32%   |
| HGST HTS545050A7E380 500GB              | 8         | 12     | 1.32%   |
| Seagate ST1000LM035-1RK172 1TB          | 7         | 8      | 1.15%   |
| Kingston SV300S37A120G 120GB SSD        | 7         | 10     | 1.15%   |
| WDC WD10JPVX-22JC3T0 1TB                | 6         | 9      | 0.99%   |
| Seagate ST9320423AS 320GB               | 6         | 6      | 0.99%   |
| Hitachi HTS547550A9E384 500GB           | 6         | 17     | 0.99%   |
| Hitachi HTS543232A7A384 320GB           | 6         | 8      | 0.99%   |
| HGST HTS725050A7E630 500GB              | 6         | 6      | 0.99%   |
| Toshiba MQ01ABD050 500GB                | 5         | 5      | 0.82%   |
| Seagate ST9500420AS 500GB               | 5         | 7      | 0.82%   |
| Hitachi HTS545050B9A300 500GB           | 5         | 7      | 0.82%   |
| Hitachi HTS545050A7E380 500GB           | 5         | 7      | 0.82%   |
| Hitachi HTS545016B9A300 160GB           | 5         | 5      | 0.82%   |
| Hitachi HTS541680J9SA00 80GB            | 5         | 5      | 0.82%   |
| WDC WD2500BEKT-75PVMT0 250GB            | 4         | 5      | 0.66%   |
| Seagate ST980811AS 80GB                 | 4         | 5      | 0.66%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 4         | 5      | 0.66%   |
| Seagate ST500LM000-1EJ162 500GB         | 4         | 6      | 0.66%   |
| Seagate ST320LT007-9ZV142 320GB         | 4         | 4      | 0.66%   |
| Samsung Electronics HM321HI 320GB       | 4         | 6      | 0.66%   |
| Hitachi HTS725025A9A364 250GB           | 4         | 5      | 0.66%   |
| Hitachi HTS545032B9A300 320GB           | 4         | 5      | 0.66%   |
| Hitachi HTS545025B9A300 250GB           | 4         | 9      | 0.66%   |
| Hitachi HTS542516K9SA00 160GB           | 4         | 4      | 0.66%   |
| Toshiba MQ01ABD075 752GB                | 3         | 5      | 0.49%   |
| Toshiba MK2035GSS 200GB                 | 3         | 3      | 0.49%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 3         | 6      | 0.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 146       | 213    | 24.21%  |
| Hitachi             | 97        | 136    | 16.09%  |
| Toshiba             | 94        | 136    | 15.59%  |
| HGST                | 86        | 127    | 14.26%  |
| WDC                 | 78        | 106    | 12.94%  |
| Samsung Electronics | 25        | 41     | 4.15%   |
| Kingston            | 18        | 28     | 2.99%   |
| Fujitsu             | 18        | 25     | 2.99%   |
| Intel               | 10        | 18     | 1.66%   |
| SK hynix            | 6         | 7      | 1%      |
| SanDisk             | 3         | 4      | 0.5%    |
| A-DATA Technology   | 3         | 3      | 0.5%    |
| Intenso             | 2         | 2      | 0.33%   |
| Crucial             | 2         | 2      | 0.33%   |
| Apple               | 2         | 4      | 0.33%   |
| Timetec             | 1         | 2      | 0.17%   |
| SPCC                | 1         | 1      | 0.17%   |
| Netac               | 1         | 1      | 0.17%   |
| Micron Technology   | 1         | 1      | 0.17%   |
| MARSHAL             | 1         | 1      | 0.17%   |
| LITEONIT            | 1         | 2      | 0.17%   |
| Kingmax             | 1         | 1      | 0.17%   |
| JMicron Technology  | 1         | 1      | 0.17%   |
| Initio              | 1         | 2      | 0.17%   |
| IBM/Hitachi         | 1         | 1      | 0.17%   |
| CSD                 | 1         | 2      | 0.17%   |
| China               | 1         | 1      | 0.17%   |
| Apacer              | 1         | 2      | 0.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 146       | 213    | 27.19%  |
| Hitachi             | 97        | 136    | 18.06%  |
| Toshiba             | 89        | 123    | 16.57%  |
| HGST                | 86        | 127    | 16.01%  |
| WDC                 | 76        | 104    | 14.15%  |
| Samsung Electronics | 21        | 30     | 3.91%   |
| Fujitsu             | 18        | 25     | 3.35%   |
| MARSHAL             | 1         | 1      | 0.19%   |
| Initio              | 1         | 2      | 0.19%   |
| IBM/Hitachi         | 1         | 1      | 0.19%   |
| CSD                 | 1         | 2      | 0.19%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 520       | 764    | 88.74%  |
| SSD     | 63        | 102    | 10.75%  |
| NVMe    | 2         | 3      | 0.34%   |
| Unknown | 1         | 1      | 0.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB        | 2         | 2      | 9.09%   |
| Toshiba MQ01ABD100 1TB             | 2         | 2      | 9.09%   |
| Toshiba MK6475GSX 640GB            | 2         | 2      | 9.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 2      | 9.09%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 7      | 4.55%   |
| WDC WD3200BVVT-63A26Y0 320GB       | 1         | 1      | 4.55%   |
| WDC WD3200BPVT-24JJ5T0 320GB       | 1         | 1      | 4.55%   |
| WDC WD3200BEVT-08A23T1 320GB       | 1         | 1      | 4.55%   |
| WDC WD2500LPCX-24C6HT0 250GB       | 1         | 1      | 4.55%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 1         | 1      | 4.55%   |
| Toshiba MQ01ABD050V 500GB          | 1         | 1      | 4.55%   |
| Toshiba MK5055GSX 500GB            | 1         | 1      | 4.55%   |
| Toshiba MK3275GSX 320GB            | 1         | 1      | 4.55%   |
| Toshiba MK1665GSX 160GB            | 1         | 1      | 4.55%   |
| Toshiba MK1646GSX 160GB            | 1         | 1      | 4.55%   |
| Seagate ST9320325AS 320GB          | 1         | 1      | 4.55%   |
| Samsung Electronics HM060HI 64GB   | 1         | 1      | 4.55%   |
| Intel SSDPEKKW256G7 256GB          | 1         | 1      | 4.55%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 9         | 9      | 40.91%  |
| WDC                 | 8         | 14     | 36.36%  |
| Seagate             | 3         | 3      | 13.64%  |
| Samsung Electronics | 1         | 1      | 4.55%   |
| Intel               | 1         | 1      | 4.55%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1164      | 2064   | 60.88%  |
| Malfunc  | 578       | 870    | 30.23%  |
| Detected | 148       | 235    | 7.74%   |
| Failed   | 22        | 28     | 1.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1414      | 81.31%  |
| AMD                              | 225       | 12.94%  |
| Samsung Electronics              | 31        | 1.78%   |
| Nvidia                           | 16        | 0.92%   |
| SanDisk                          | 9         | 0.52%   |
| Toshiba America Info Systems     | 8         | 0.46%   |
| VIA Technologies                 | 6         | 0.35%   |
| Kingston Technology Company      | 6         | 0.35%   |
| JMicron Technology               | 4         | 0.23%   |
| Solid State Storage Technology   | 3         | 0.17%   |
| Phison Electronics               | 3         | 0.17%   |
| KIOXIA                           | 3         | 0.17%   |
| Silicon Integrated Systems [SiS] | 2         | 0.12%   |
| Micron Technology                | 2         | 0.12%   |
| Lite-On Technology               | 2         | 0.12%   |
| ADATA Technology                 | 2         | 0.12%   |
| Silicon Motion                   | 1         | 0.06%   |
| Silicon Image                    | 1         | 0.06%   |
| Realtek Semiconductor            | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 199       | 9.94%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 153       | 7.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 145       | 7.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 133       | 6.64%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 113       | 5.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 90        | 4.49%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 89        | 4.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 80        | 3.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 75        | 3.74%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 75        | 3.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 53        | 2.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 51        | 2.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 46        | 2.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 44        | 2.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 41        | 2.05%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 36        | 1.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 34        | 1.7%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 33        | 1.65%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 31        | 1.55%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 30        | 1.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 26        | 1.3%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 21        | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 21        | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 19        | 0.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 19        | 0.95%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 19        | 0.95%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 16        | 0.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 15        | 0.75%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 14        | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 14        | 0.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 13        | 0.65%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 12        | 0.6%    |
| AMD FCH SATA Controller [IDE mode]                                                     | 12        | 0.6%    |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 11        | 0.55%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 11        | 0.55%   |
| Nvidia MCP79 AHCI Controller                                                           | 10        | 0.5%    |
| Intel Mobile PM965/GM965 PT IDER Controller                                            | 10        | 0.5%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 9         | 0.45%   |
| Samsung NVMe SSD Controller 980                                                        | 8         | 0.4%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 8         | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1430      | 75.07%  |
| IDE  | 310       | 16.27%  |
| RAID | 96        | 5.04%   |
| NVMe | 69        | 3.62%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1462      | 86.3%   |
| AMD          | 231       | 13.64%  |
| CentaurHauls | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron CPU 1000M @ 1.80GHz           | 41        | 2.41%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 39        | 2.29%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 25        | 1.47%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 23        | 1.35%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 22        | 1.29%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 20        | 1.18%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 20        | 1.18%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 19        | 1.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 18        | 1.06%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 18        | 1.06%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 17        | 1%      |
| Intel Core i5-3210M CPU @ 2.50GHz           | 17        | 1%      |
| Intel Core i3-7020U CPU @ 2.30GHz           | 17        | 1%      |
| Intel Atom CPU N455 @ 1.66GHz               | 17        | 1%      |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 16        | 0.94%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 16        | 0.94%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 16        | 0.94%   |
| Intel Atom CPU N450 @ 1.66GHz               | 15        | 0.88%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 14        | 0.82%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 14        | 0.82%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 14        | 0.82%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 14        | 0.82%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 14        | 0.82%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 14        | 0.82%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 13        | 0.76%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 13        | 0.76%   |
| Intel Core i5 CPU M 540 @ 2.53GHz           | 13        | 0.76%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 13        | 0.76%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 12        | 0.71%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 12        | 0.71%   |
| Intel Core 2 CPU T5500 @ 1.66GHz            | 12        | 0.71%   |
| Intel Atom CPU N270 @ 1.60GHz               | 12        | 0.71%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 11        | 0.65%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 11        | 0.65%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 11        | 0.65%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 11        | 0.65%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 10        | 0.59%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 10        | 0.59%   |
| Intel Pentium CPU 2117U @ 1.80GHz           | 10        | 0.59%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 10        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 371       | 21.84%  |
| Intel Core i3                        | 223       | 13.13%  |
| Intel Celeron                        | 192       | 11.3%   |
| Intel Core 2 Duo                     | 181       | 10.65%  |
| Intel Core i7                        | 167       | 9.83%   |
| Intel Pentium                        | 92        | 5.41%   |
| Intel Atom                           | 73        | 4.3%    |
| Intel Pentium Dual-Core              | 50        | 2.94%   |
| AMD A4                               | 32        | 1.88%   |
| Intel Core 2                         | 31        | 1.82%   |
| AMD A8                               | 30        | 1.77%   |
| AMD A6                               | 25        | 1.47%   |
| Intel Pentium Dual                   | 23        | 1.35%   |
| AMD E                                | 19        | 1.12%   |
| AMD E1                               | 18        | 1.06%   |
| AMD E2                               | 16        | 0.94%   |
| Intel Genuine                        | 13        | 0.77%   |
| Other                                | 12        | 0.71%   |
| AMD Ryzen 5                          | 11        | 0.65%   |
| AMD A10                              | 11        | 0.65%   |
| Intel Celeron M                      | 10        | 0.59%   |
| Intel Celeron Dual-Core              | 10        | 0.59%   |
| Intel Pentium Silver                 | 8         | 0.47%   |
| Intel Pentium M                      | 7         | 0.41%   |
| Intel Core Duo                       | 7         | 0.41%   |
| AMD Turion 64 X2 Mobile              | 7         | 0.41%   |
| AMD C-60                             | 7         | 0.41%   |
| AMD Athlon II                        | 6         | 0.35%   |
| AMD FX                               | 5         | 0.29%   |
| AMD C-50                             | 4         | 0.24%   |
| AMD Athlon X2                        | 4         | 0.24%   |
| AMD Athlon II Dual-Core              | 4         | 0.24%   |
| AMD Mobile Sempron                   | 3         | 0.18%   |
| AMD A12                              | 3         | 0.18%   |
| AMD V140                             | 2         | 0.12%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 2         | 0.12%   |
| AMD Turion 64 Mobile                 | 2         | 0.12%   |
| AMD Ryzen 3                          | 2         | 0.12%   |
| AMD C-70                             | 2         | 0.12%   |
| AMD Athlon 64 X2                     | 2         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1287      | 75.66%  |
| 4      | 248       | 14.58%  |
| 1      | 145       | 8.52%   |
| 6      | 18        | 1.06%   |
| 8      | 3         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1694      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 869       | 50.94%  |
| 2      | 837       | 49.06%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1647      | 97.11%  |
| 32-bit         | 44        | 2.59%   |
| Unknown        | 5         | 0.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 187       | 10.75%  |
| 0x306a9    | 180       | 10.35%  |
| 0x1067a    | 142       | 8.17%   |
| 0x20655    | 110       | 6.33%   |
| Unknown    | 97        | 5.58%   |
| 0x40651    | 74        | 4.26%   |
| 0x6fd      | 68        | 3.91%   |
| 0x306d4    | 57        | 3.28%   |
| 0x306c3    | 47        | 2.7%    |
| 0x406c4    | 44        | 2.53%   |
| 0x10676    | 44        | 2.53%   |
| 0x406e3    | 42        | 2.42%   |
| 0x20652    | 42        | 2.42%   |
| 0x806e9    | 41        | 2.36%   |
| 0x106ca    | 41        | 2.36%   |
| 0x30678    | 34        | 1.96%   |
| 0x806ea    | 32        | 1.84%   |
| 0x05000119 | 32        | 1.84%   |
| 0x07030105 | 29        | 1.67%   |
| 0x6f6      | 20        | 1.15%   |
| 0x0700010f | 19        | 1.09%   |
| 0x6fb      | 18        | 1.04%   |
| 0x406c3    | 18        | 1.04%   |
| 0x506c9    | 17        | 0.98%   |
| 0x906ea    | 16        | 0.92%   |
| 0x106c2    | 16        | 0.92%   |
| 0x06006705 | 16        | 0.92%   |
| 0x706a1    | 14        | 0.81%   |
| 0x6f2      | 13        | 0.75%   |
| 0x506e3    | 13        | 0.75%   |
| 0x06001119 | 13        | 0.75%   |
| 0x906e9    | 11        | 0.63%   |
| 0x806ec    | 11        | 0.63%   |
| 0x10661    | 11        | 0.63%   |
| 0x6ec      | 10        | 0.58%   |
| 0x05000029 | 10        | 0.58%   |
| 0x06003106 | 9         | 0.52%   |
| 0x6d8      | 8         | 0.46%   |
| 0x03000027 | 8         | 0.46%   |
| 0x010000c8 | 8         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SandyBridge     | 187       | 11.04%  |
| Penryn          | 187       | 11.04%  |
| IvyBridge       | 182       | 10.74%  |
| Westmere        | 154       | 9.09%   |
| Core            | 138       | 8.15%   |
| Haswell         | 127       | 7.5%    |
| KabyLake        | 124       | 7.32%   |
| Silvermont      | 104       | 6.14%   |
| Skylake         | 63        | 3.72%   |
| Broadwell       | 60        | 3.54%   |
| Bonnell         | 60        | 3.54%   |
| Bobcat          | 46        | 2.72%   |
| Puma            | 42        | 2.48%   |
| Excavator       | 32        | 1.89%   |
| P6              | 27        | 1.59%   |
| Jaguar          | 22        | 1.3%    |
| Goldmont        | 21        | 1.24%   |
| Piledriver      | 17        | 1%      |
| K8 Hammer       | 16        | 0.94%   |
| Goldmont plus   | 16        | 0.94%   |
| K10             | 15        | 0.89%   |
| Steamroller     | 11        | 0.65%   |
| K10 Llano       | 8         | 0.47%   |
| Zen             | 7         | 0.41%   |
| K8 & K10 hybrid | 7         | 0.41%   |
| TigerLake       | 5         | 0.3%    |
| Zen 2           | 4         | 0.24%   |
| CometLake       | 4         | 0.24%   |
| Zen+            | 3         | 0.18%   |
| Nehalem         | 3         | 0.18%   |
| Zen 3           | 1         | 0.06%   |
| Unknown         | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1288      | 64.21%  |
| AMD                              | 362       | 18.05%  |
| Nvidia                           | 349       | 17.4%   |
| VIA Technologies                 | 6         | 0.3%    |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 175       | 8.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 170       | 7.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 142       | 6.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 109       | 5%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 76        | 3.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 64        | 2.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 63        | 2.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 63        | 2.89%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 59        | 2.71%   |
| Intel HD Graphics 5500                                                                   | 52        | 2.39%   |
| Intel HD Graphics 620                                                                    | 49        | 2.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 45        | 2.07%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 44        | 2.02%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 42        | 1.93%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 42        | 1.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 40        | 1.84%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 30        | 1.38%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 26        | 1.19%   |
| Intel UHD Graphics 620                                                                   | 25        | 1.15%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 23        | 1.06%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 22        | 1.01%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 22        | 1.01%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 20        | 0.92%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 18        | 0.83%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 17        | 0.78%   |
| Intel HD Graphics 500                                                                    | 17        | 0.78%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 16        | 0.73%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 13        | 0.6%    |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                         | 13        | 0.6%    |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 11        | 0.51%   |
| Intel HD Graphics 530                                                                    | 11        | 0.51%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 11        | 0.51%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 10        | 0.46%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 10        | 0.46%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 10        | 0.46%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 10        | 0.46%   |
| Nvidia GM108M [GeForce MX110]                                                            | 9         | 0.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 0.41%   |
| Intel HD Graphics 630                                                                    | 9         | 0.41%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 9         | 0.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 983       | 57.96%  |
| 1 x AMD        | 241       | 14.21%  |
| Intel + Nvidia | 238       | 14.03%  |
| 1 x Nvidia     | 106       | 6.25%   |
| Intel + AMD    | 68        | 4.01%   |
| 2 x AMD        | 49        | 2.89%   |
| 1 x VIA        | 6         | 0.35%   |
| AMD + Nvidia   | 4         | 0.24%   |
| 1 x SiS        | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1674      | 98.64%  |
| Unknown     | 21        | 1.24%   |
| Proprietary | 2         | 0.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 964       | 55.47%  |
| 0.01-0.5   | 358       | 20.6%   |
| 1.01-2.0   | 219       | 12.6%   |
| 0.51-1.0   | 137       | 7.88%   |
| 3.01-4.0   | 43        | 2.47%   |
| 5.01-6.0   | 10        | 0.58%   |
| 2.01-3.0   | 4         | 0.23%   |
| 7.01-8.0   | 3         | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 357       | 20.51%  |
| AU Optronics            | 333       | 19.13%  |
| Samsung Electronics     | 291       | 16.71%  |
| Chimei Innolux          | 186       | 10.68%  |
| BOE                     | 144       | 8.27%   |
| Chi Mei Optoelectronics | 113       | 6.49%   |
| Lenovo                  | 62        | 3.56%   |
| LG Philips              | 35        | 2.01%   |
| InfoVision              | 22        | 1.26%   |
| Apple                   | 17        | 0.98%   |
| Goldstar                | 15        | 0.86%   |
| CPT                     | 15        | 0.86%   |
| HannStar                | 13        | 0.75%   |
| Hewlett-Packard         | 11        | 0.63%   |
| Dell                    | 10        | 0.57%   |
| Quanta Display          | 9         | 0.52%   |
| PANDA                   | 8         | 0.46%   |
| Vestel Elektronik       | 7         | 0.4%    |
| Sony                    | 7         | 0.4%    |
| Sharp                   | 7         | 0.4%    |
| Philips                 | 7         | 0.4%    |
| InnoLux Display         | 6         | 0.34%   |
| Toshiba                 | 5         | 0.29%   |
| BenQ                    | 5         | 0.29%   |
| Acer                    | 5         | 0.29%   |
| Fujitsu Siemens         | 4         | 0.23%   |
| ASUSTek Computer        | 4         | 0.23%   |
| Ancor Communications    | 4         | 0.23%   |
| Panasonic               | 3         | 0.17%   |
| IBM                     | 3         | 0.17%   |
| AOC                     | 3         | 0.17%   |
| Unknown                 | 2         | 0.11%   |
| SKY                     | 2         | 0.11%   |
| Plain Tree Systems      | 2         | 0.11%   |
| NEC Computers           | 2         | 0.11%   |
| MiTAC                   | 2         | 0.11%   |
| Hitachi                 | 2         | 0.11%   |
| Eizo                    | 2         | 0.11%   |
| CTV                     | 2         | 0.11%   |
| ViewSonic               | 1         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 47        | 2.68%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 30        | 1.71%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 26        | 1.48%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 24        | 1.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 24        | 1.37%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 22        | 1.25%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 21        | 1.2%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 18        | 1.03%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 17        | 0.97%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 16        | 0.91%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 13        | 0.74%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 13        | 0.74%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 12        | 0.68%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 12        | 0.68%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 12        | 0.68%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 10        | 0.57%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 10        | 0.57%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 10        | 0.57%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch     | 9         | 0.51%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 9         | 0.51%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 9         | 0.51%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 8         | 0.46%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x189mm 14.1-inch                  | 8         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch          | 8         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 8         | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 8         | 0.46%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 8         | 0.46%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                         | 7         | 0.4%    |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 7         | 0.4%    |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 7         | 0.4%    |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 7         | 0.4%    |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 7         | 0.4%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 7         | 0.4%    |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch              | 7         | 0.4%    |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch              | 7         | 0.4%    |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch                  | 7         | 0.4%    |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 7         | 0.4%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 7         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 7         | 0.4%    |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 7         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 857       | 49.77%  |
| 1920x1080 (FHD)    | 318       | 18.47%  |
| 1280x800 (WXGA)    | 186       | 10.8%   |
| 1600x900 (HD+)     | 138       | 8.01%   |
| 1440x900 (WXGA+)   | 58        | 3.37%   |
| 1024x600           | 44        | 2.56%   |
| 3840x2160 (4K)     | 29        | 1.68%   |
| 1680x1050 (WSXGA+) | 20        | 1.16%   |
| 1920x1200 (WUXGA)  | 17        | 0.99%   |
| 1024x768 (XGA)     | 11        | 0.64%   |
| 1360x768           | 10        | 0.58%   |
| 1280x1024 (SXGA)   | 9         | 0.52%   |
| 2560x1440 (QHD)    | 4         | 0.23%   |
| 1920x540           | 4         | 0.23%   |
| 2288x1287          | 3         | 0.17%   |
| 1280x720 (HD)      | 3         | 0.17%   |
| 2560x1080          | 2         | 0.12%   |
| 1280x768           | 2         | 0.12%   |
| 3840x2400          | 1         | 0.06%   |
| 3440x1440          | 1         | 0.06%   |
| 2560x1600          | 1         | 0.06%   |
| 2160x1440          | 1         | 0.06%   |
| 1680x945           | 1         | 0.06%   |
| 1400x1050          | 1         | 0.06%   |
| 1024x576           | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1009      | 57.66%  |
| 14      | 176       | 10.06%  |
| 17      | 137       | 7.83%   |
| 13      | 101       | 5.77%   |
| 12      | 57        | 3.26%   |
| 10      | 49        | 2.8%    |
| 11      | 45        | 2.57%   |
| 23      | 28        | 1.6%    |
| 21      | 19        | 1.09%   |
| 18      | 19        | 1.09%   |
| 27      | 16        | 0.91%   |
| 24      | 16        | 0.91%   |
| 19      | 9         | 0.51%   |
| 84      | 7         | 0.4%    |
| 22      | 7         | 0.4%    |
| 20      | 7         | 0.4%    |
| 31      | 6         | 0.34%   |
| 32      | 5         | 0.29%   |
| 8       | 5         | 0.29%   |
| Unknown | 5         | 0.29%   |
| 72      | 3         | 0.17%   |
| 54      | 3         | 0.17%   |
| 52      | 3         | 0.17%   |
| 34      | 3         | 0.17%   |
| 142     | 2         | 0.11%   |
| 65      | 2         | 0.11%   |
| 49      | 2         | 0.11%   |
| 40      | 2         | 0.11%   |
| 16      | 2         | 0.11%   |
| 50      | 1         | 0.06%   |
| 39      | 1         | 0.06%   |
| 37      | 1         | 0.06%   |
| 26      | 1         | 0.06%   |
| 9       | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1192      | 68.39%  |
| 201-300        | 206       | 11.82%  |
| 351-400        | 181       | 10.38%  |
| 501-600        | 60        | 3.44%   |
| 401-500        | 51        | 2.93%   |
| 1001-1500      | 11        | 0.63%   |
| 1501-2000      | 10        | 0.57%   |
| 701-800        | 8         | 0.46%   |
| 601-700        | 7         | 0.4%    |
| 101-200        | 6         | 0.34%   |
| Unknown        | 5         | 0.29%   |
| 801-900        | 4         | 0.23%   |
| More than 2000 | 2         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1342      | 81.23%  |
| 16/10   | 274       | 16.59%  |
| 4/3     | 12        | 0.73%   |
| 5/4     | 9         | 0.54%   |
| 3/2     | 8         | 0.48%   |
| 21/9    | 3         | 0.18%   |
| 1.00    | 2         | 0.12%   |
| 0.62    | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1006      | 57.72%  |
| 81-90          | 234       | 13.43%  |
| 121-130        | 95        | 5.45%   |
| 61-70          | 55        | 3.16%   |
| 201-250        | 55        | 3.16%   |
| 41-50          | 49        | 2.81%   |
| 51-60          | 45        | 2.58%   |
| 71-80          | 42        | 2.41%   |
| 131-140        | 38        | 2.18%   |
| 141-150        | 23        | 1.32%   |
| More than 1000 | 21        | 1.2%    |
| 151-200        | 20        | 1.15%   |
| 301-350        | 16        | 0.92%   |
| 351-500        | 13        | 0.75%   |
| 251-300        | 9         | 0.52%   |
| 91-100         | 7         | 0.4%    |
| 1-40           | 6         | 0.34%   |
| Unknown        | 5         | 0.29%   |
| 501-1000       | 4         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 901       | 52.2%   |
| 121-160       | 408       | 23.64%  |
| 51-100        | 367       | 21.26%  |
| 161-240       | 25        | 1.45%   |
| 1-50          | 16        | 0.93%   |
| Unknown       | 5         | 0.29%   |
| More than 240 | 4         | 0.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1586      | 91.31%  |
| 2     | 135       | 7.77%   |
| 0     | 10        | 0.58%   |
| 4     | 3         | 0.17%   |
| 3     | 3         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 870       | 30.5%   |
| Intel                             | 695       | 24.37%  |
| Qualcomm Atheros                  | 597       | 20.93%  |
| Broadcom                          | 278       | 9.75%   |
| Ralink                            | 88        | 3.09%   |
| Broadcom Limited                  | 84        | 2.95%   |
| Marvell Technology Group          | 57        | 2%      |
| Ralink Technology                 | 15        | 0.53%   |
| JMicron Technology                | 15        | 0.53%   |
| Huawei Technologies               | 15        | 0.53%   |
| Hewlett-Packard                   | 15        | 0.53%   |
| Dell                              | 15        | 0.53%   |
| Ericsson Business Mobile Networks | 14        | 0.49%   |
| Nvidia                            | 10        | 0.35%   |
| Sierra Wireless                   | 9         | 0.32%   |
| Samsung Electronics               | 9         | 0.32%   |
| Attansic Technology               | 8         | 0.28%   |
| Xiaomi                            | 6         | 0.21%   |
| VIA Technologies                  | 5         | 0.18%   |
| TP-Link                           | 5         | 0.18%   |
| Qualcomm Atheros Communications   | 4         | 0.14%   |
| MediaTek                          | 4         | 0.14%   |
| ASIX Electronics                  | 4         | 0.14%   |
| T & A Mobile Phones               | 3         | 0.11%   |
| D-Link                            | 3         | 0.11%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.07%   |
| NetGear                           | 2         | 0.07%   |
| LG Electronics                    | 2         | 0.07%   |
| Belkin Components                 | 2         | 0.07%   |
| ASUSTek Computer                  | 2         | 0.07%   |
| AMD                               | 2         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.04%   |
| Toshiba                           | 1         | 0.04%   |
| Spreadtrum Communications         | 1         | 0.04%   |
| Shenzhen Goodix Technology        | 1         | 0.04%   |
| OPPO Electronics                  | 1         | 0.04%   |
| Motorola PCS                      | 1         | 0.04%   |
| Micro Star International          | 1         | 0.04%   |
| ICS Advent                        | 1         | 0.04%   |
| HMD Global                        | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 495       | 14.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 303       | 8.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 136       | 3.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 113       | 3.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 91        | 2.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 80        | 2.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 75        | 2.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 70        | 2.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 68        | 1.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 68        | 1.99%   |
| Intel Wireless 7260                                                     | 60        | 1.75%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 56        | 1.64%   |
| Intel 82577LM Gigabit Network Connection                                | 56        | 1.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 54        | 1.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 48        | 1.4%    |
| Intel 82567LM Gigabit Network Connection                                | 45        | 1.31%   |
| Intel Centrino Advanced-N 6200                                          | 44        | 1.29%   |
| Intel Wireless 3165                                                     | 35        | 1.02%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 34        | 0.99%   |
| Intel Centrino Ultimate-N 6300                                          | 33        | 0.96%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 32        | 0.93%   |
| Intel Wireless 3160                                                     | 32        | 0.93%   |
| Intel Wireless 7265                                                     | 31        | 0.91%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 31        | 0.91%   |
| Intel WiFi Link 5100                                                    | 30        | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                           | 30        | 0.88%   |
| Intel Wireless 8265 / 8275                                              | 28        | 0.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 26        | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 24        | 0.7%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 24        | 0.7%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 22        | 0.64%   |
| Intel Ethernet Connection I218-LM                                       | 22        | 0.64%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 22        | 0.64%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 20        | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 19        | 0.55%   |
| Intel 82566MM Gigabit Network Connection                                | 19        | 0.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 18        | 0.53%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 18        | 0.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 17        | 0.5%    |
| Intel Ultimate N WiFi Link 5300                                         | 17        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 641       | 36.69%  |
| Qualcomm Atheros                  | 526       | 30.11%  |
| Realtek Semiconductor             | 216       | 12.36%  |
| Broadcom                          | 178       | 10.19%  |
| Ralink                            | 88        | 5.04%   |
| Broadcom Limited                  | 39        | 2.23%   |
| Ralink Technology                 | 15        | 0.86%   |
| Sierra Wireless                   | 9         | 0.52%   |
| Dell                              | 8         | 0.46%   |
| TP-Link                           | 5         | 0.29%   |
| Qualcomm Atheros Communications   | 4         | 0.23%   |
| Hewlett-Packard                   | 3         | 0.17%   |
| D-Link                            | 3         | 0.17%   |
| NetGear                           | 2         | 0.11%   |
| MediaTek                          | 2         | 0.11%   |
| Ericsson Business Mobile Networks | 2         | 0.11%   |
| Belkin Components                 | 2         | 0.11%   |
| ASUSTek Computer                  | 2         | 0.11%   |
| Micro Star International          | 1         | 0.06%   |
| Fujitsu Siemens Computers         | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 136       | 7.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 113       | 6.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 80        | 4.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 75        | 4.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 70        | 3.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 68        | 3.87%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 68        | 3.87%   |
| Intel Wireless 7260                                                     | 60        | 3.42%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 56        | 3.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 54        | 3.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 48        | 2.74%   |
| Intel Centrino Advanced-N 6200                                          | 44        | 2.51%   |
| Intel Wireless 3165                                                     | 35        | 1.99%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 34        | 1.94%   |
| Intel Centrino Ultimate-N 6300                                          | 33        | 1.88%   |
| Intel Wireless 3160                                                     | 32        | 1.82%   |
| Intel Wireless 7265                                                     | 31        | 1.77%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 31        | 1.77%   |
| Intel WiFi Link 5100                                                    | 30        | 1.71%   |
| Broadcom BCM43142 802.11b/g/n                                           | 30        | 1.71%   |
| Intel Wireless 8265 / 8275                                              | 28        | 1.6%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 26        | 1.48%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 24        | 1.37%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 22        | 1.25%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 19        | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 18        | 1.03%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 18        | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 17        | 0.97%   |
| Intel Ultimate N WiFi Link 5300                                         | 17        | 0.97%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 17        | 0.97%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 15        | 0.85%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 13        | 0.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 13        | 0.74%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 12        | 0.68%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 12        | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 12        | 0.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 12        | 0.68%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 12        | 0.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 0.63%   |
| Intel Centrino Wireless-N 2230                                          | 10        | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 825       | 50.99%  |
| Intel                            | 323       | 19.96%  |
| Qualcomm Atheros                 | 161       | 9.95%   |
| Broadcom                         | 125       | 7.73%   |
| Marvell Technology Group         | 57        | 3.52%   |
| Broadcom Limited                 | 46        | 2.84%   |
| JMicron Technology               | 15        | 0.93%   |
| Huawei Technologies              | 11        | 0.68%   |
| Nvidia                           | 10        | 0.62%   |
| Attansic Technology              | 8         | 0.49%   |
| Samsung Electronics              | 7         | 0.43%   |
| Xiaomi                           | 6         | 0.37%   |
| VIA Technologies                 | 5         | 0.31%   |
| ASIX Electronics                 | 4         | 0.25%   |
| T & A Mobile Phones              | 3         | 0.19%   |
| Silicon Integrated Systems [SiS] | 2         | 0.12%   |
| LG Electronics                   | 2         | 0.12%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.06%   |
| Spreadtrum Communications        | 1         | 0.06%   |
| OPPO Electronics                 | 1         | 0.06%   |
| Motorola PCS                     | 1         | 0.06%   |
| MediaTek                         | 1         | 0.06%   |
| ICS Advent                       | 1         | 0.06%   |
| HMD Global                       | 1         | 0.06%   |
| Davicom Semiconductor            | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 495       | 30.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 303       | 18.7%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 91        | 5.62%   |
| Intel 82577LM Gigabit Network Connection                          | 56        | 3.46%   |
| Intel 82567LM Gigabit Network Connection                          | 45        | 2.78%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 32        | 1.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 24        | 1.48%   |
| Intel Ethernet Connection I218-LM                                 | 22        | 1.36%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 22        | 1.36%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 20        | 1.23%   |
| Intel 82566MM Gigabit Network Connection                          | 19        | 1.17%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 16        | 0.99%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 16        | 0.99%   |
| Intel Ethernet Connection I217-LM                                 | 16        | 0.99%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 15        | 0.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 14        | 0.86%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 14        | 0.86%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 14        | 0.86%   |
| Intel 82579V Gigabit Network Connection                           | 13        | 0.8%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 13        | 0.8%    |
| Broadcom BCM4401-B0 100Base-TX                                    | 13        | 0.8%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 12        | 0.74%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 12        | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 0.68%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 11        | 0.68%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 11        | 0.68%   |
| Huawei WLZ-AN00                                                   | 10        | 0.62%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 10        | 0.62%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 10        | 0.62%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 9         | 0.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 9         | 0.56%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 9         | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 0.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 8         | 0.49%   |
| Intel 82577LC Gigabit Network Connection                          | 8         | 0.49%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 8         | 0.49%   |
| Nvidia MCP79 Ethernet                                             | 7         | 0.43%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 7         | 0.43%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6         | 0.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 6         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1670      | 50.54%  |
| Ethernet | 1585      | 47.97%  |
| Modem    | 47        | 1.42%   |
| Unknown  | 2         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1348      | 72.94%  |
| Ethernet | 500       | 27.06%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1541      | 90.75%  |
| 1     | 131       | 7.71%   |
| 0     | 22        | 1.3%    |
| 3     | 4         | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1547      | 87.75%  |
| Yes  | 216       | 12.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 291       | 24.29%  |
| Qualcomm Atheros Communications | 155       | 12.94%  |
| Broadcom                        | 141       | 11.77%  |
| Realtek Semiconductor           | 113       | 9.43%   |
| Dell                            | 73        | 6.09%   |
| Lite-On Technology              | 70        | 5.84%   |
| Hewlett-Packard                 | 64        | 5.34%   |
| Foxconn / Hon Hai               | 64        | 5.34%   |
| Ralink                          | 56        | 4.67%   |
| IMC Networks                    | 46        | 3.84%   |
| Toshiba                         | 34        | 2.84%   |
| Cambridge Silicon Radio         | 26        | 2.17%   |
| Apple                           | 15        | 1.25%   |
| ASUSTek Computer                | 11        | 0.92%   |
| Ralink Technology               | 7         | 0.58%   |
| Foxconn International           | 7         | 0.58%   |
| Askey Computer                  | 6         | 0.5%    |
| Alps Electric                   | 5         | 0.42%   |
| Realtek                         | 3         | 0.25%   |
| Micro Star International        | 3         | 0.25%   |
| Chicony Electronics             | 3         | 0.25%   |
| Taiyo Yuden                     | 2         | 0.17%   |
| MediaTek                        | 1         | 0.08%   |
| Fujitsu Siemens Computers       | 1         | 0.08%   |
| Fujitsu                         | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 204       | 16.99%  |
| Realtek Bluetooth Radio                             | 60        | 5%      |
| Ralink RT3290 Bluetooth                             | 56        | 4.66%   |
| Qualcomm Atheros  Bluetooth Device                  | 55        | 4.58%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 39        | 3.25%   |
| Dell DW375 Bluetooth Module                         | 34        | 2.83%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 32        | 2.66%   |
| HP Broadcom 2070 Bluetooth Combo                    | 32        | 2.66%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 31        | 2.58%   |
| Broadcom BCM2045B (BDC-2.1)                         | 28        | 2.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 26        | 2.16%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 25        | 2.08%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 23        | 1.92%   |
| Foxconn / Hon Hai Bluetooth Device                  | 23        | 1.92%   |
| Broadcom HP Portable SoftSailing                    | 22        | 1.83%   |
| Lite-On Atheros AR3012 Bluetooth                    | 21        | 1.75%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 20        | 1.67%   |
| IMC Networks Bluetooth Device                       | 19        | 1.58%   |
| Realtek RTL8821A Bluetooth                          | 18        | 1.5%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 18        | 1.5%    |
| Realtek RTL8723B Bluetooth                          | 17        | 1.42%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 17        | 1.42%   |
| Realtek  Bluetooth 4.2 Adapter                      | 15        | 1.25%   |
| Toshiba Bluetooth Device                            | 14        | 1.17%   |
| Dell BCM20702A0 Bluetooth Module                    | 13        | 1.08%   |
| Lite-On Bluetooth Device                            | 12        | 1%      |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 1%      |
| Intel AX201 Bluetooth                               | 11        | 0.92%   |
| Broadcom BCM2070 Bluetooth Device                   | 11        | 0.92%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 10        | 0.83%   |
| IMC Networks Bluetooth Radio                        | 9         | 0.75%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 9         | 0.75%   |
| Foxconn / Hon Hai BCM20702A0                        | 9         | 0.75%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 9         | 0.75%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 9         | 0.75%   |
| Dell Wireless 355 Bluetooth                         | 8         | 0.67%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 0.67%   |
| Apple Bluetooth Host Controller                     | 8         | 0.67%   |
| Toshiba Integrated Bluetooth HCI                    | 7         | 0.58%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 7         | 0.58%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1430      | 77.3%   |
| AMD                              | 279       | 15.08%  |
| Nvidia                           | 111       | 6%      |
| C-Media Electronics              | 8         | 0.43%   |
| VIA Technologies                 | 6         | 0.32%   |
| Logitech                         | 3         | 0.16%   |
| Creative Technology              | 3         | 0.16%   |
| Texas Instruments                | 2         | 0.11%   |
| Silicon Integrated Systems [SiS] | 2         | 0.11%   |
| Tenx Technology                  | 1         | 0.05%   |
| PreSonus Audio Electronics       | 1         | 0.05%   |
| Numark                           | 1         | 0.05%   |
| M-Audio                          | 1         | 0.05%   |
| Focusrite-Novation               | 1         | 0.05%   |
| ASUSTek Computer                 | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 221       | 9.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 178       | 7.95%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 157       | 7.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 148       | 6.61%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 127       | 5.67%   |
| AMD FCH Azalia Controller                                                                         | 119       | 5.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 109       | 4.87%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 97        | 4.33%   |
| Intel 8 Series HD Audio Controller                                                                | 79        | 3.53%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 78        | 3.49%   |
| AMD Kabini HDMI/DP Audio                                                                          | 74        | 3.31%   |
| Intel Broadwell-U Audio Controller                                                                | 60        | 2.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 59        | 2.64%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 55        | 2.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 52        | 2.32%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 48        | 2.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 43        | 1.92%   |
| AMD Wrestler HDMI Audio                                                                           | 42        | 1.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 39        | 1.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 32        | 1.43%   |
| AMD High Definition Audio Controller                                                              | 22        | 0.98%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 21        | 0.94%   |
| Intel Cannon Lake PCH cAVS                                                                        | 19        | 0.85%   |
| AMD Trinity HDMI Audio Controller                                                                 | 17        | 0.76%   |
| Nvidia High Definition Audio Controller                                                           | 16        | 0.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 16        | 0.71%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 16        | 0.71%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 15        | 0.67%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 13        | 0.58%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 13        | 0.58%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 13        | 0.58%   |
| Nvidia MCP79 High Definition Audio                                                                | 12        | 0.54%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 12        | 0.54%   |
| Intel CM238 HD Audio Controller                                                                   | 11        | 0.49%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 0.49%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 11        | 0.49%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 10        | 0.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 10        | 0.45%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 8         | 0.36%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 8         | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 533       | 26.52%  |
| SK hynix              | 501       | 24.93%  |
| Unknown               | 229       | 11.39%  |
| Kingston              | 206       | 10.25%  |
| Micron Technology     | 173       | 8.61%   |
| Elpida                | 80        | 3.98%   |
| Nanya Technology      | 69        | 3.43%   |
| Ramaxel Technology    | 51        | 2.54%   |
| A-DATA Technology     | 35        | 1.74%   |
| Crucial               | 20        | 1%      |
| Corsair               | 16        | 0.8%    |
| Kingmax               | 14        | 0.7%    |
| ASint Technology      | 11        | 0.55%   |
| 48spaces              | 11        | 0.55%   |
| Transcend             | 10        | 0.5%    |
| Qimonda               | 7         | 0.35%   |
| Unknown (ABCD)        | 5         | 0.25%   |
| Toshiba               | 4         | 0.2%    |
| Patriot               | 4         | 0.2%    |
| SHARETRONIC           | 3         | 0.15%   |
| Kingmax Semiconductor | 3         | 0.15%   |
| Apacer                | 3         | 0.15%   |
| Melco                 | 2         | 0.1%    |
| Infineon              | 2         | 0.1%    |
| CSX                   | 2         | 0.1%    |
| Axiom                 | 2         | 0.1%    |
| Unifosa               | 1         | 0.05%   |
| Teikon                | 1         | 0.05%   |
| Smart Brazil          | 1         | 0.05%   |
| PUSKILL               | 1         | 0.05%   |
| PNY                   | 1         | 0.05%   |
| Memory Solution       | 1         | 0.05%   |
| Magnum Tech           | 1         | 0.05%   |
| Hikvision             | 1         | 0.05%   |
| GOODRAM               | 1         | 0.05%   |
| Goldkey               | 1         | 0.05%   |
| G.Skill               | 1         | 0.05%   |
| Catalyst              | 1         | 0.05%   |
| Aeneon                | 1         | 0.05%   |
| Unknown               | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 48        | 2.21%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 41        | 1.89%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                             | 40        | 1.84%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 38        | 1.75%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s                  | 34        | 1.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 33        | 1.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 32        | 1.48%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                     | 30        | 1.38%   |
| SK hynix RAM HMT325S6CFR8A-PB 2048MB SODIMM DDR3 1600MT/s                 | 25        | 1.15%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                     | 24        | 1.11%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 24        | 1.11%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s                  | 23        | 1.06%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 22        | 1.01%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM 1600MT/s                          | 22        | 1.01%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 21        | 0.97%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 20        | 0.92%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s                 | 20        | 0.92%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                     | 20        | 0.92%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                             | 19        | 0.88%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s                  | 19        | 0.88%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s                     | 19        | 0.88%   |
| Unknown RAM Module 1024MB SODIMM DDR2                                     | 18        | 0.83%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 16        | 0.74%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s                    | 16        | 0.74%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 14        | 0.65%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 14        | 0.65%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                                  | 13        | 0.6%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM 1600MT/s                         | 13        | 0.6%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 12        | 0.55%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s                    | 12        | 0.55%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 12        | 0.55%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s                      | 12        | 0.55%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                     | 12        | 0.55%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s                     | 12        | 0.55%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 11        | 0.51%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s                   | 11        | 0.51%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                      | 11        | 0.51%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s                     | 11        | 0.51%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s                     | 11        | 0.51%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 11        | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 1025      | 60.29%  |
| DDR2    | 254       | 14.94%  |
| DDR4    | 230       | 13.53%  |
| SDRAM   | 97        | 5.71%   |
| Unknown | 31        | 1.82%   |
| LPDDR4  | 28        | 1.65%   |
| DDR     | 22        | 1.29%   |
| DRAM    | 8         | 0.47%   |
| LPDDR3  | 5         | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1618      | 98.3%   |
| DIMM         | 14        | 0.85%   |
| Row Of Chips | 9         | 0.55%   |
| Chip         | 5         | 0.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 798       | 42.22%  |
| 2048    | 560       | 29.63%  |
| 8192    | 308       | 16.3%   |
| 1024    | 173       | 9.15%   |
| 512     | 25        | 1.32%   |
| 16384   | 24        | 1.27%   |
| Unknown | 2         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 668       | 35.76%  |
| 1334    | 212       | 11.35%  |
| 667     | 154       | 8.24%   |
| 2667    | 145       | 7.76%   |
| 1333    | 112       | 6%      |
| 1067    | 88        | 4.71%   |
| 2400    | 73        | 3.91%   |
| Unknown | 72        | 3.85%   |
| 800     | 65        | 3.48%   |
| 4199    | 49        | 2.62%   |
| 2048    | 39        | 2.09%   |
| 533     | 31        | 1.66%   |
| 2133    | 30        | 1.61%   |
| 975     | 25        | 1.34%   |
| 1066    | 21        | 1.12%   |
| 3266    | 20        | 1.07%   |
| 3200    | 17        | 0.91%   |
| 333     | 12        | 0.64%   |
| 1867    | 10        | 0.54%   |
| 1639    | 9         | 0.48%   |
| 1776    | 3         | 0.16%   |
| 8400    | 2         | 0.11%   |
| 2267    | 2         | 0.11%   |
| 400     | 2         | 0.11%   |
| 3733    | 1         | 0.05%   |
| 2134    | 1         | 0.05%   |
| 1866    | 1         | 0.05%   |
| 1400    | 1         | 0.05%   |
| 1200    | 1         | 0.05%   |
| 266     | 1         | 0.05%   |
| 200     | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 11        | 55%     |
| Samsung Electronics   | 2         | 10%     |
| Canon                 | 2         | 10%     |
| Brother Industries    | 2         | 10%     |
| Seiko Epson           | 1         | 5%      |
| Oki Data              | 1         | 5%      |
| Lexmark International | 1         | 5%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP Officejet J4500 series               | 2         | 10%     |
| HP DeskJet 2130 series                  | 2         | 10%     |
| Seiko Epson XP-240 Series               | 1         | 5%      |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 5%      |
| Samsung Composite Device                | 1         | 5%      |
| Oki Data USB Device                     | 1         | 5%      |
| Lexmark International Lexmark X203n     | 1         | 5%      |
| HP LaserJet P1102                       | 1         | 5%      |
| HP LaserJet 1022                        | 1         | 5%      |
| HP LaserJet 1020                        | 1         | 5%      |
| HP ENVY 4520 series                     | 1         | 5%      |
| HP DeskJet 5550                         | 1         | 5%      |
| HP DeskJet 3630 series                  | 1         | 5%      |
| HP Deskjet 1510                         | 1         | 5%      |
| Canon TS5100 series                     | 1         | 5%      |
| Canon LBP6020                           | 1         | 5%      |
| Brother HL-1110 series                  | 1         | 5%      |
| Brother DCP-1610W                       | 1         | 5%      |

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
| Chicony Electronics                    | 396       | 28.43%  |
| Realtek Semiconductor                  | 123       | 8.83%   |
| IMC Networks                           | 122       | 8.76%   |
| Microdia                               | 103       | 7.39%   |
| Suyin                                  | 102       | 7.32%   |
| Sunplus Innovation Technology          | 94        | 6.75%   |
| Bison Electronics                      | 70        | 5.03%   |
| Cheng Uei Precision Industry (Foxlink) | 58        | 4.16%   |
| Syntek                                 | 47        | 3.37%   |
| Silicon Motion                         | 31        | 2.23%   |
| Quanta                                 | 31        | 2.23%   |
| Lenovo                                 | 23        | 1.65%   |
| Alcor Micro                            | 23        | 1.65%   |
| Primax Electronics                     | 21        | 1.51%   |
| Ricoh                                  | 20        | 1.44%   |
| Acer                                   | 17        | 1.22%   |
| ALi                                    | 15        | 1.08%   |
| Lite-On Technology                     | 14        | 1.01%   |
| Apple                                  | 13        | 0.93%   |
| Z-Star Microelectronics                | 11        | 0.79%   |
| OmniVision Technologies                | 11        | 0.79%   |
| Importek                               | 10        | 0.72%   |
| Logitech                               | 6         | 0.43%   |
| DigiTech                               | 5         | 0.36%   |
| Genesys Logic                          | 4         | 0.29%   |
| Samsung Electronics                    | 3         | 0.22%   |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.14%   |
| Nebraska Furniture Mart                | 2         | 0.14%   |
| Intel                                  | 2         | 0.14%   |
| GEMBIRD                                | 2         | 0.14%   |
| Xiaomi                                 | 1         | 0.07%   |
| Trust                                  | 1         | 0.07%   |
| Sunplus Technology                     | 1         | 0.07%   |
| Spreadtrum Communications              | 1         | 0.07%   |
| Luxvisions Innotech Limited            | 1         | 0.07%   |
| KYE Systems (Mouse Systems)            | 1         | 0.07%   |
| Hewlett-Packard                        | 1         | 0.07%   |
| Google                                 | 1         | 0.07%   |
| Generalplus Technology                 | 1         | 0.07%   |
| Cubeternet                             | 1         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony HP Truevision HD                                | 39        | 2.8%    |
| IMC Networks USB2.0 VGA UVC WebCam                      | 35        | 2.51%   |
| Chicony HD Webcam                                       | 32        | 2.3%    |
| Bison Lenovo EasyCamera                                 | 27        | 1.94%   |
| Sunplus HP Truevision HD                                | 24        | 1.72%   |
| Chicony USB2.0 VGA UVC WebCam                           | 24        | 1.72%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 22        | 1.58%   |
| Realtek USB Camera                                      | 20        | 1.43%   |
| Microdia Integrated Webcam                              | 20        | 1.43%   |
| Chicony integrated camera                               | 20        | 1.43%   |
| Chicony Lenovo EasyCamera                               | 18        | 1.29%   |
| Sunplus HD WebCam                                       | 17        | 1.22%   |
| IMC Networks EasyCamera                                 | 17        | 1.22%   |
| Chicony USB2.0 HD UVC WebCam                            | 17        | 1.22%   |
| Chicony FJ Camera                                       | 17        | 1.22%   |
| Syntek EasyCamera                                       | 16        | 1.15%   |
| Sunplus Integrated_Webcam_HD                            | 16        | 1.15%   |
| Primax HP HD Webcam [Fixed]                             | 15        | 1.08%   |
| Chicony EasyCamera                                      | 14        | 1%      |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 14        | 1%      |
| Realtek Lenovo EasyCamera                               | 13        | 0.93%   |
| Chicony VGA Webcam                                      | 13        | 0.93%   |
| Chicony TOSHIBA Web Camera - HD                         | 13        | 0.93%   |
| Chicony 2.0M UVC Webcam / CNF7129                       | 13        | 0.93%   |
| Realtek USB2.0 VGA UVC WebCam                           | 12        | 0.86%   |
| Realtek Integrated Webcam                               | 12        | 0.86%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 12        | 0.86%   |
| Chicony Integrated HP HD Webcam                         | 12        | 0.86%   |
| ALi Gateway Webcam                                      | 12        | 0.86%   |
| Silicon Motion WebCam SC-0311139N                       | 11        | 0.79%   |
| Quanta VGA Webcam                                       | 11        | 0.79%   |
| OmniVision OV2640 Webcam                                | 11        | 0.79%   |
| IMC Networks Integrated Webcam                          | 11        | 0.79%   |
| Chicony CNF9055 Toshiba Webcam                          | 11        | 0.79%   |
| Bison Lenovo Integrated Webcam                          | 11        | 0.79%   |
| Suyin HD WebCam                                         | 10        | 0.72%   |
| Suyin Acer CrystalEye Webcam                            | 10        | 0.72%   |
| Microdia Integrated_Webcam_HD                           | 10        | 0.72%   |
| Lenovo Integrated Webcam [R5U877]                       | 10        | 0.72%   |
| Lenovo Integrated Webcam                                | 10        | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 68        | 40.72%  |
| AuthenTec                  | 57        | 34.13%  |
| Upek                       | 19        | 11.38%  |
| LighTuning Technology      | 10        | 5.99%   |
| STMicroelectronics         | 8         | 4.79%   |
| Synaptics                  | 2         | 1.2%    |
| Elan Microelectronics      | 2         | 1.2%    |
| Shenzhen Goodix Technology | 1         | 0.6%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AuthenTec AES2810                                                          | 23        | 13.77%  |
| AuthenTec AES2501 Fingerprint Sensor                                       | 20        | 11.98%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 18        | 10.78%  |
| Validity Sensors VFS491                                                    | 12        | 7.19%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 6.59%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 9         | 5.39%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 8         | 4.79%   |
| STMicroelectronics Fingerprint Reader                                      | 8         | 4.79%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 4.79%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 4.19%   |
| LighTuning Fingerprint Reader                                              | 6         | 3.59%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 2.99%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 2.4%    |
| AuthenTec AES1600                                                          | 4         | 2.4%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 1.8%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1.8%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.2%    |
| Synaptics  WBDI                                                            | 2         | 1.2%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.2%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.2%    |
| Elan ELAN:Fingerprint                                                      | 2         | 1.2%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.6%    |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.6%    |
| Validity Sensors Synaptics WBDI                                            | 1         | 0.6%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.6%    |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.6%    |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 0.6%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.6%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.6%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 74        | 56.06%  |
| O2 Micro              | 25        | 18.94%  |
| Lenovo                | 19        | 14.39%  |
| Alcor Micro           | 9         | 6.82%   |
| Upek                  | 4         | 3.03%   |
| Gemalto (was Gemplus) | 1         | 0.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 59        | 44.7%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 22        | 16.67%  |
| Lenovo Integrated Smart Card Reader                                          | 19        | 14.39%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 8.33%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 6.82%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 3.03%   |
| Broadcom 5880                                                                | 4         | 3.03%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 2.27%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1198      | 68.93%  |
| 1     | 451       | 25.95%  |
| 2     | 80        | 4.6%    |
| 3     | 6         | 0.35%   |
| 10    | 1         | 0.06%   |
| 5     | 1         | 0.06%   |
| 4     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 167       | 27.11%  |
| Chipcard                 | 132       | 21.43%  |
| Graphics card            | 114       | 18.51%  |
| Bluetooth                | 59        | 9.58%   |
| Net/wireless             | 43        | 6.98%   |
| Storage                  | 36        | 5.84%   |
| Multimedia controller    | 18        | 2.92%   |
| Flash memory             | 17        | 2.76%   |
| Communication controller | 14        | 2.27%   |
| Camera                   | 8         | 1.3%    |
| Sound                    | 3         | 0.49%   |
| Storage/raid             | 1         | 0.16%   |
| Storage/ata              | 1         | 0.16%   |
| Network                  | 1         | 0.16%   |
| Net/ethernet             | 1         | 0.16%   |
| Card reader              | 1         | 0.16%   |


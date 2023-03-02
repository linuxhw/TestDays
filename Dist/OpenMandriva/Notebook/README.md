OpenMandriva - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva.

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

Total: 5694

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Medion        | Erazer X7851 MD60583        | [9ddd4f88b4](https://linux-hardware.org/?probe=9ddd4f88b4) | Feb 28, 2023 |
| ASUSTek       | X55A                        | [1429627725](https://linux-hardware.org/?probe=1429627725) | Feb 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8ec75c8681](https://linux-hardware.org/?probe=8ec75c8681) | Feb 28, 2023 |
| ASUSTek       | N76VB                       | [0043164762](https://linux-hardware.org/?probe=0043164762) | Feb 28, 2023 |
| Dell          | Latitude 3400               | [2936e7f368](https://linux-hardware.org/?probe=2936e7f368) | Feb 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [87022bd601](https://linux-hardware.org/?probe=87022bd601) | Feb 28, 2023 |
| Acer          | Aspire V3-772               | [5a0c297e10](https://linux-hardware.org/?probe=5a0c297e10) | Feb 28, 2023 |
| Philco        | 10D                         | [dd709d35db](https://linux-hardware.org/?probe=dd709d35db) | Feb 28, 2023 |
| Dell          | Latitude D630               | [5175558c99](https://linux-hardware.org/?probe=5175558c99) | Feb 28, 2023 |
| Sony          | VPCZ21Z9R                   | [4d3f0c27cd](https://linux-hardware.org/?probe=4d3f0c27cd) | Feb 28, 2023 |
| Sony          | VGN-FW11M                   | [06b355e1de](https://linux-hardware.org/?probe=06b355e1de) | Feb 28, 2023 |
| HP            | EliteBook 8540w             | [057c307bf5](https://linux-hardware.org/?probe=057c307bf5) | Feb 28, 2023 |
| Dell          | Latitude E6420              | [a84f4dbcbb](https://linux-hardware.org/?probe=a84f4dbcbb) | Feb 28, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [021853dafb](https://linux-hardware.org/?probe=021853dafb) | Feb 28, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [594ff7091b](https://linux-hardware.org/?probe=594ff7091b) | Feb 27, 2023 |
| ASUSTek       | X550CA                      | [0ce966b8fa](https://linux-hardware.org/?probe=0ce966b8fa) | Feb 27, 2023 |
| ASUSTek       | K75VJ                       | [7fc0fff829](https://linux-hardware.org/?probe=7fc0fff829) | Feb 27, 2023 |
| Acer          | Aspire 8930                 | [837e36aa25](https://linux-hardware.org/?probe=837e36aa25) | Feb 27, 2023 |
| HP            | Notebook                    | [7e64e6bc1b](https://linux-hardware.org/?probe=7e64e6bc1b) | Feb 27, 2023 |
| Acer          | Aspire E5-571               | [5f035002e1](https://linux-hardware.org/?probe=5f035002e1) | Feb 27, 2023 |
| HP            | Notebook                    | [a1180ad479](https://linux-hardware.org/?probe=a1180ad479) | Feb 27, 2023 |
| Lenovo        | G700 20251                  | [8dc4179bbd](https://linux-hardware.org/?probe=8dc4179bbd) | Feb 27, 2023 |
| Acer          | Aspire 1410                 | [40b5704a1c](https://linux-hardware.org/?probe=40b5704a1c) | Feb 26, 2023 |
| Acer          | Aspire ES1-711              | [8e397cc54f](https://linux-hardware.org/?probe=8e397cc54f) | Feb 26, 2023 |
| ASUSTek       | X751LK                      | [f312f303e0](https://linux-hardware.org/?probe=f312f303e0) | Feb 26, 2023 |
| Dell          | Latitude E5530 non-vPro     | [5634c4795c](https://linux-hardware.org/?probe=5634c4795c) | Feb 26, 2023 |
| eMachines     | eME728                      | [2331984fc8](https://linux-hardware.org/?probe=2331984fc8) | Feb 26, 2023 |
| Dell          | Latitude D630               | [cfdc009ff1](https://linux-hardware.org/?probe=cfdc009ff1) | Feb 26, 2023 |
| Google        | Lars                        | [ec4b0e7bbc](https://linux-hardware.org/?probe=ec4b0e7bbc) | Feb 25, 2023 |
| Lenovo        | ThinkPad L412 0585A38       | [da6493ef82](https://linux-hardware.org/?probe=da6493ef82) | Feb 25, 2023 |
| Acer          | Acadia V1.45                | [faee032e6c](https://linux-hardware.org/?probe=faee032e6c) | Feb 25, 2023 |
| Samsung       | 550XBE/350XBE               | [d9f49e98fd](https://linux-hardware.org/?probe=d9f49e98fd) | Feb 25, 2023 |
| HP            | Pavilion g7                 | [8f46d24897](https://linux-hardware.org/?probe=8f46d24897) | Feb 25, 2023 |
| Sony          | SVE1513B1EW                 | [c99ef001e4](https://linux-hardware.org/?probe=c99ef001e4) | Feb 25, 2023 |
| ASUSTek       | GL702ZC                     | [a40afcb1d9](https://linux-hardware.org/?probe=a40afcb1d9) | Feb 25, 2023 |
| Toshiba       | Satellite C850              | [99d4efbb52](https://linux-hardware.org/?probe=99d4efbb52) | Feb 25, 2023 |
| ASUSTek       | GL553VD                     | [302b65ed41](https://linux-hardware.org/?probe=302b65ed41) | Feb 25, 2023 |
| ASUSTek       | Z450LA                      | [304be04748](https://linux-hardware.org/?probe=304be04748) | Feb 25, 2023 |
| Unknown       | Unknown                     | [6707aef886](https://linux-hardware.org/?probe=6707aef886) | Feb 25, 2023 |
| Dell          | Latitude D630               | [433f06ecbb](https://linux-hardware.org/?probe=433f06ecbb) | Feb 24, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a8a2fc9d83](https://linux-hardware.org/?probe=a8a2fc9d83) | Feb 24, 2023 |
| HP            | 650                         | [ab0b350259](https://linux-hardware.org/?probe=ab0b350259) | Feb 24, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [c19b7cd0f5](https://linux-hardware.org/?probe=c19b7cd0f5) | Feb 24, 2023 |
| HP            | ProBook 4530s               | [305f79455e](https://linux-hardware.org/?probe=305f79455e) | Feb 24, 2023 |
| Fujitsu       | LIFEBOOK A530               | [9035e056b4](https://linux-hardware.org/?probe=9035e056b4) | Feb 24, 2023 |
| HP            | ProBook 4730s               | [6d563800a1](https://linux-hardware.org/?probe=6d563800a1) | Feb 24, 2023 |
| HP            | Compaq CQ58                 | [cfff7e8c96](https://linux-hardware.org/?probe=cfff7e8c96) | Feb 24, 2023 |
| HP            | Notebook                    | [b929a8ff3c](https://linux-hardware.org/?probe=b929a8ff3c) | Feb 24, 2023 |
| Acer          | Aspire S3                   | [9d0301c490](https://linux-hardware.org/?probe=9d0301c490) | Feb 24, 2023 |
| Dell          | Inspiron 15-3567            | [f6b6b24623](https://linux-hardware.org/?probe=f6b6b24623) | Feb 24, 2023 |
| Acer          | Aspire A517-51G             | [12040fcd10](https://linux-hardware.org/?probe=12040fcd10) | Feb 24, 2023 |
| Acer          | AO725                       | [9c6719e733](https://linux-hardware.org/?probe=9c6719e733) | Feb 24, 2023 |
| Acer          | Aspire E5-575G              | [f7d34fdd3a](https://linux-hardware.org/?probe=f7d34fdd3a) | Feb 24, 2023 |
| Packard Be... | EasyNote TS44HR             | [b0d713ec14](https://linux-hardware.org/?probe=b0d713ec14) | Feb 24, 2023 |
| NEC Comput... | PC-VY25AAZR7                | [bc17a98c15](https://linux-hardware.org/?probe=bc17a98c15) | Feb 24, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [c0af9c8bdb](https://linux-hardware.org/?probe=c0af9c8bdb) | Feb 24, 2023 |
| Positivo      | N1103                       | [b89c4551aa](https://linux-hardware.org/?probe=b89c4551aa) | Feb 24, 2023 |
| Toshiba       | Satellite C850-1GF          | [f568855409](https://linux-hardware.org/?probe=f568855409) | Feb 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d8d531c22a](https://linux-hardware.org/?probe=d8d531c22a) | Feb 24, 2023 |
| Lenovo        | Legion 5 15IMH05C 82AU      | [a5a58a8dc4](https://linux-hardware.org/?probe=a5a58a8dc4) | Feb 23, 2023 |
| Lenovo        | ThinkPad T520 4243F53       | [2e904cc4d7](https://linux-hardware.org/?probe=2e904cc4d7) | Feb 23, 2023 |
| Samsung       | RV413/RV513                 | [5b524ddbb0](https://linux-hardware.org/?probe=5b524ddbb0) | Feb 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [df8ac668e2](https://linux-hardware.org/?probe=df8ac668e2) | Feb 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [0f5352f94f](https://linux-hardware.org/?probe=0f5352f94f) | Feb 23, 2023 |
| Acer          | Aspire A515-46              | [009fbacf68](https://linux-hardware.org/?probe=009fbacf68) | Feb 23, 2023 |
| Dell          | Latitude E7470              | [5e445bd00a](https://linux-hardware.org/?probe=5e445bd00a) | Feb 23, 2023 |
| Dell          | Latitude 5420               | [948cbeda59](https://linux-hardware.org/?probe=948cbeda59) | Feb 23, 2023 |
| Lenovo        | V15-ADA 82C7                | [d19ee09dd3](https://linux-hardware.org/?probe=d19ee09dd3) | Feb 23, 2023 |
| Acer          | Nitro AN515-52              | [05f7c375b7](https://linux-hardware.org/?probe=05f7c375b7) | Feb 23, 2023 |
| HP            | mt40                        | [16e5f8eb5d](https://linux-hardware.org/?probe=16e5f8eb5d) | Feb 23, 2023 |
| Toshiba       | dynabook T653/46JR          | [ac156d2c80](https://linux-hardware.org/?probe=ac156d2c80) | Feb 22, 2023 |
| HP            | 15                          | [470b07302a](https://linux-hardware.org/?probe=470b07302a) | Feb 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [d488fc0d9a](https://linux-hardware.org/?probe=d488fc0d9a) | Feb 22, 2023 |
| ASUSTek       | 1215B                       | [970d77d150](https://linux-hardware.org/?probe=970d77d150) | Feb 22, 2023 |
| Positivo      | S14SL01                     | [914a9e691e](https://linux-hardware.org/?probe=914a9e691e) | Feb 22, 2023 |
| Positivo      | S14CT01                     | [af73fc0481](https://linux-hardware.org/?probe=af73fc0481) | Feb 22, 2023 |
| Lenovo        | ThinkPad T430s 23551M9      | [91b6a109b4](https://linux-hardware.org/?probe=91b6a109b4) | Feb 22, 2023 |
| ASUSTek       | X555DG                      | [5e7abe271f](https://linux-hardware.org/?probe=5e7abe271f) | Feb 22, 2023 |
| Lenovo        | V130-15IGM 81HL             | [40205862f6](https://linux-hardware.org/?probe=40205862f6) | Feb 22, 2023 |
| Lenovo        | ThinkPad T520 4242NS9       | [6e2e5c8285](https://linux-hardware.org/?probe=6e2e5c8285) | Feb 22, 2023 |
| Gateway       | NV53A                       | [1e2b4ec4d3](https://linux-hardware.org/?probe=1e2b4ec4d3) | Feb 22, 2023 |
| Dell          | Latitude E5420              | [f5a1982d9c](https://linux-hardware.org/?probe=f5a1982d9c) | Feb 22, 2023 |
| Dell          | Inspiron 5547               | [ff88bcbafc](https://linux-hardware.org/?probe=ff88bcbafc) | Feb 22, 2023 |
| Timi          | TM1707                      | [9bc429fbd6](https://linux-hardware.org/?probe=9bc429fbd6) | Feb 22, 2023 |
| Fujitsu Si... | AMILO Li3910                | [28890c5346](https://linux-hardware.org/?probe=28890c5346) | Feb 21, 2023 |
| HP            | Pavilion dv6                | [526430f218](https://linux-hardware.org/?probe=526430f218) | Feb 21, 2023 |
| Apple         | MacBookPro9,2               | [80df77e6a1](https://linux-hardware.org/?probe=80df77e6a1) | Feb 21, 2023 |
| Dell          | Vostro 15 7510              | [df764baed8](https://linux-hardware.org/?probe=df764baed8) | Feb 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7e5789e02b](https://linux-hardware.org/?probe=7e5789e02b) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [50f5c21eeb](https://linux-hardware.org/?probe=50f5c21eeb) | Feb 21, 2023 |
| Lenovo        | ThinkPad T430s 2356CV6      | [bb18722cf2](https://linux-hardware.org/?probe=bb18722cf2) | Feb 21, 2023 |
| Dell          | XPS 15 7590                 | [f613ecb9b2](https://linux-hardware.org/?probe=f613ecb9b2) | Feb 20, 2023 |
| Dell          | Inspiron 5493               | [ad7bee8a6e](https://linux-hardware.org/?probe=ad7bee8a6e) | Feb 20, 2023 |
| Dell          | G15 5510                    | [a1edb7b376](https://linux-hardware.org/?probe=a1edb7b376) | Feb 20, 2023 |
| Dell          | Inspiron 3502               | [224f4edab7](https://linux-hardware.org/?probe=224f4edab7) | Feb 20, 2023 |
| Toshiba       | TECRA R850                  | [082f5559c7](https://linux-hardware.org/?probe=082f5559c7) | Feb 20, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [40468a72ce](https://linux-hardware.org/?probe=40468a72ce) | Feb 20, 2023 |
| Lenovo        | IdeaPad L340-17API 81LY     | [e26b379150](https://linux-hardware.org/?probe=e26b379150) | Feb 20, 2023 |
| Unknown       | Unknown                     | [cccf0ea7f3](https://linux-hardware.org/?probe=cccf0ea7f3) | Feb 20, 2023 |
| Acer          | Aspire 6530G                | [c1d73e8ceb](https://linux-hardware.org/?probe=c1d73e8ceb) | Feb 20, 2023 |
| ASUSTek       | GL702VM                     | [daa3e0f7df](https://linux-hardware.org/?probe=daa3e0f7df) | Feb 20, 2023 |
| HP            | Pavilion 17                 | [1a50084a52](https://linux-hardware.org/?probe=1a50084a52) | Feb 19, 2023 |
| HP            | 14                          | [0244e880e1](https://linux-hardware.org/?probe=0244e880e1) | Feb 19, 2023 |
| ASUSTek       | X541NA                      | [b9ddd17e6c](https://linux-hardware.org/?probe=b9ddd17e6c) | Feb 19, 2023 |
| HP            | Pavilion g6                 | [f3552f5183](https://linux-hardware.org/?probe=f3552f5183) | Feb 19, 2023 |
| ASUSTek       | X55U                        | [15322abeb5](https://linux-hardware.org/?probe=15322abeb5) | Feb 19, 2023 |
| Dell          | Vostro1710                  | [91b1af7ed6](https://linux-hardware.org/?probe=91b1af7ed6) | Feb 19, 2023 |
| HP            | 250 G6 Notebook PC          | [c32182253e](https://linux-hardware.org/?probe=c32182253e) | Feb 19, 2023 |
| Lenovo        | B560 43308VG                | [c30b594458](https://linux-hardware.org/?probe=c30b594458) | Feb 19, 2023 |
| HP            | ProBook 4520s               | [8192287499](https://linux-hardware.org/?probe=8192287499) | Feb 19, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [b0941b8ef0](https://linux-hardware.org/?probe=b0941b8ef0) | Feb 18, 2023 |
| HP            | 255 G8 Notebook PC          | [ecf73f400b](https://linux-hardware.org/?probe=ecf73f400b) | Feb 18, 2023 |
| HP            | Notebook                    | [2d03543f4c](https://linux-hardware.org/?probe=2d03543f4c) | Feb 18, 2023 |
| HP            | 15                          | [60ecad0be7](https://linux-hardware.org/?probe=60ecad0be7) | Feb 18, 2023 |
| HP            | Notebook                    | [3eff638ead](https://linux-hardware.org/?probe=3eff638ead) | Feb 18, 2023 |
| HP            | Pavilion g6                 | [2b4de6efbe](https://linux-hardware.org/?probe=2b4de6efbe) | Feb 18, 2023 |
| HP            | 15                          | [4db2520843](https://linux-hardware.org/?probe=4db2520843) | Feb 18, 2023 |
| Samsung       | RF511/RF411/RF711           | [355838f8b2](https://linux-hardware.org/?probe=355838f8b2) | Feb 18, 2023 |
| ASUSTek       | X756UB                      | [713121e0fc](https://linux-hardware.org/?probe=713121e0fc) | Feb 18, 2023 |
| ASUSTek       | UX31E                       | [4c3c50a992](https://linux-hardware.org/?probe=4c3c50a992) | Feb 18, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [27958da7cc](https://linux-hardware.org/?probe=27958da7cc) | Feb 18, 2023 |
| ASUSTek       | X555DA                      | [2ac23d19ec](https://linux-hardware.org/?probe=2ac23d19ec) | Feb 18, 2023 |
| HP            | ProBook 4540s               | [cc3e78f73f](https://linux-hardware.org/?probe=cc3e78f73f) | Feb 18, 2023 |
| Sony          | VGN-FW270J                  | [81ce2212e9](https://linux-hardware.org/?probe=81ce2212e9) | Feb 18, 2023 |
| HP            | G62                         | [59a7a48e19](https://linux-hardware.org/?probe=59a7a48e19) | Feb 18, 2023 |
| Dell          | XPS 13 9370                 | [96b350db9f](https://linux-hardware.org/?probe=96b350db9f) | Feb 18, 2023 |
| Acer          | Aspire A515-45              | [ce9f366d7e](https://linux-hardware.org/?probe=ce9f366d7e) | Feb 17, 2023 |
| ASUSTek       | UX31E                       | [e6391763b2](https://linux-hardware.org/?probe=e6391763b2) | Feb 17, 2023 |
| PC Special... | NJ50_70CU                   | [68dd853397](https://linux-hardware.org/?probe=68dd853397) | Feb 17, 2023 |
| ASUSTek       | K53SC                       | [df5351b94d](https://linux-hardware.org/?probe=df5351b94d) | Feb 17, 2023 |
| Dell          | Inspiron 17-7779            | [da4ee713d7](https://linux-hardware.org/?probe=da4ee713d7) | Feb 17, 2023 |
| Samsung       | 550XDA                      | [d7f1482689](https://linux-hardware.org/?probe=d7f1482689) | Feb 17, 2023 |
| Dell          | Inspiron 5555               | [2051d9e516](https://linux-hardware.org/?probe=2051d9e516) | Feb 17, 2023 |
| Acer          | Aspire 7750G                | [e4b193c332](https://linux-hardware.org/?probe=e4b193c332) | Feb 17, 2023 |
| ASUSTek       | X555LJ                      | [a524479b7a](https://linux-hardware.org/?probe=a524479b7a) | Feb 17, 2023 |
| Toshiba       | Satellite C70-C-18E         | [7642482909](https://linux-hardware.org/?probe=7642482909) | Feb 17, 2023 |
| Dell          | Latitude E6400              | [d9fc10c008](https://linux-hardware.org/?probe=d9fc10c008) | Feb 17, 2023 |
| HP            | Pavilion 17                 | [058dbd3d5a](https://linux-hardware.org/?probe=058dbd3d5a) | Feb 17, 2023 |
| HP            | Pavilion 15                 | [a48098f6fc](https://linux-hardware.org/?probe=a48098f6fc) | Feb 17, 2023 |
| Acer          | Aspire V3-771               | [caeb6bc93f](https://linux-hardware.org/?probe=caeb6bc93f) | Feb 17, 2023 |
| HP            | Laptop 15-da0xxx            | [ac458108b4](https://linux-hardware.org/?probe=ac458108b4) | Feb 17, 2023 |
| ASUSTek       | K54C                        | [ea944628df](https://linux-hardware.org/?probe=ea944628df) | Feb 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [66c33604c4](https://linux-hardware.org/?probe=66c33604c4) | Feb 17, 2023 |
| Dell          | Latitude E5450              | [cd7e5d61f2](https://linux-hardware.org/?probe=cd7e5d61f2) | Feb 17, 2023 |
| Samsung       | R519/R719                   | [1dc4bc1b72](https://linux-hardware.org/?probe=1dc4bc1b72) | Feb 17, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [ffd622d65f](https://linux-hardware.org/?probe=ffd622d65f) | Feb 17, 2023 |
| Lenovo        | ThinkPad X270 20HN0015GE    | [f546833d76](https://linux-hardware.org/?probe=f546833d76) | Feb 17, 2023 |
| Dell          | Latitude E6410              | [58d4c40618](https://linux-hardware.org/?probe=58d4c40618) | Feb 17, 2023 |
| Dell          | Studio 1558                 | [4a2f0524b9](https://linux-hardware.org/?probe=4a2f0524b9) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [85fd62f731](https://linux-hardware.org/?probe=85fd62f731) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61 7661BM5        | [c829d5ed74](https://linux-hardware.org/?probe=c829d5ed74) | Feb 16, 2023 |
| Dell          | Inspiron 3793               | [08b4259fa6](https://linux-hardware.org/?probe=08b4259fa6) | Feb 16, 2023 |
| Unknown       | Unknown                     | [e8183bc042](https://linux-hardware.org/?probe=e8183bc042) | Feb 16, 2023 |
| eMachines     | eMachiens G443              | [096a4bb9e4](https://linux-hardware.org/?probe=096a4bb9e4) | Feb 16, 2023 |
| HP            | Pavilion dv6500             | [95a9115968](https://linux-hardware.org/?probe=95a9115968) | Feb 16, 2023 |
| Sony          | VGN-NW240F                  | [6e63237e66](https://linux-hardware.org/?probe=6e63237e66) | Feb 16, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [42b7f88059](https://linux-hardware.org/?probe=42b7f88059) | Feb 16, 2023 |
| ASUSTek       | GL553VD                     | [97f3fd27fa](https://linux-hardware.org/?probe=97f3fd27fa) | Feb 16, 2023 |
| ASUSTek       | X555QG                      | [75924d49a1](https://linux-hardware.org/?probe=75924d49a1) | Feb 16, 2023 |
| HP            | Notebook                    | [3de841fd56](https://linux-hardware.org/?probe=3de841fd56) | Feb 16, 2023 |
| Positivo      | S14BW01                     | [c14428167e](https://linux-hardware.org/?probe=c14428167e) | Feb 16, 2023 |
| Gigabyte      | GB-BSi7A-6500               | [9c461d33db](https://linux-hardware.org/?probe=9c461d33db) | Feb 16, 2023 |
| Lenovo        | V15-IGL 82C3                | [76f2f157a5](https://linux-hardware.org/?probe=76f2f157a5) | Feb 16, 2023 |
| Dell          | Inspiron 1545               | [32794e5a2e](https://linux-hardware.org/?probe=32794e5a2e) | Feb 16, 2023 |
| ASUSTek       | S551LN                      | [676c244c1d](https://linux-hardware.org/?probe=676c244c1d) | Feb 16, 2023 |
| ASUSTek       | N76VZ                       | [ed9bd6b127](https://linux-hardware.org/?probe=ed9bd6b127) | Feb 16, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [abc91903be](https://linux-hardware.org/?probe=abc91903be) | Feb 16, 2023 |
| Dell          | Latitude E7440              | [86f8d34ba7](https://linux-hardware.org/?probe=86f8d34ba7) | Feb 16, 2023 |
| Dell          | Studio 1555                 | [64746b1c7d](https://linux-hardware.org/?probe=64746b1c7d) | Feb 16, 2023 |
| Toshiba       | dynabook R73/BN             | [df7e69c5c4](https://linux-hardware.org/?probe=df7e69c5c4) | Feb 16, 2023 |
| ASUSTek       | UX31E                       | [0255141f61](https://linux-hardware.org/?probe=0255141f61) | Feb 15, 2023 |
| Acer          | Swift SF314-59              | [fcf01071e5](https://linux-hardware.org/?probe=fcf01071e5) | Feb 15, 2023 |
| Lenovo        | ThinkPad X230 23066RC       | [6a223f0a71](https://linux-hardware.org/?probe=6a223f0a71) | Feb 15, 2023 |
| HP            | ProBook 470 G4              | [8730091665](https://linux-hardware.org/?probe=8730091665) | Feb 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [62c4a2d52d](https://linux-hardware.org/?probe=62c4a2d52d) | Feb 15, 2023 |
| HP            | Notebook                    | [21442c303e](https://linux-hardware.org/?probe=21442c303e) | Feb 15, 2023 |
| HP            | 250 G6 Notebook PC          | [745ae4d0fb](https://linux-hardware.org/?probe=745ae4d0fb) | Feb 15, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [b3d3904cef](https://linux-hardware.org/?probe=b3d3904cef) | Feb 15, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [bc69f33fa2](https://linux-hardware.org/?probe=bc69f33fa2) | Feb 15, 2023 |
| ASUSTek       | K52N                        | [f87ece85e9](https://linux-hardware.org/?probe=f87ece85e9) | Feb 15, 2023 |
| Lenovo        | ThinkPad Edge E530 62724... | [fcf87be002](https://linux-hardware.org/?probe=fcf87be002) | Feb 15, 2023 |
| HP            | 1000                        | [57de0f3103](https://linux-hardware.org/?probe=57de0f3103) | Feb 15, 2023 |
| Apple         | MacBookPro8,1               | [7aa1ad0f5b](https://linux-hardware.org/?probe=7aa1ad0f5b) | Feb 15, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [9368822d6a](https://linux-hardware.org/?probe=9368822d6a) | Feb 14, 2023 |
| Samsung       | RV419/RV420                 | [7ec9e518c4](https://linux-hardware.org/?probe=7ec9e518c4) | Feb 14, 2023 |
| Medion        | E7220                       | [a1b4318b54](https://linux-hardware.org/?probe=a1b4318b54) | Feb 14, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [dddbb2d135](https://linux-hardware.org/?probe=dddbb2d135) | Feb 14, 2023 |
| MSI           | GP73 Leopard 8RE            | [1d754a5fa3](https://linux-hardware.org/?probe=1d754a5fa3) | Feb 14, 2023 |
| Lenovo        | ThinkPad X240 20AMS4AN00    | [ec8fbb6350](https://linux-hardware.org/?probe=ec8fbb6350) | Feb 14, 2023 |
| Lenovo        | ThinkPad T410 25376B8       | [fc0430b8fe](https://linux-hardware.org/?probe=fc0430b8fe) | Feb 14, 2023 |
| Acer          | Aspire 4732Z                | [abf9d41a29](https://linux-hardware.org/?probe=abf9d41a29) | Feb 14, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [bf015f98c2](https://linux-hardware.org/?probe=bf015f98c2) | Feb 14, 2023 |
| Google        | Lulu                        | [15fa093522](https://linux-hardware.org/?probe=15fa093522) | Feb 14, 2023 |
| HP            | OMEN by Laptop 17-ck1xxx    | [18f60be847](https://linux-hardware.org/?probe=18f60be847) | Feb 13, 2023 |
| Lenovo        | ThinkPad Edge 057872G       | [98ed3bb274](https://linux-hardware.org/?probe=98ed3bb274) | Feb 13, 2023 |
| Medion        | Akoya THE TOUCH 10          | [ec6afad108](https://linux-hardware.org/?probe=ec6afad108) | Feb 13, 2023 |
| Apple         | MacBook4,1                  | [dfb5b14f25](https://linux-hardware.org/?probe=dfb5b14f25) | Feb 13, 2023 |
| ASUSTek       | X555DG                      | [3f51c3533f](https://linux-hardware.org/?probe=3f51c3533f) | Feb 13, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [c72c5cf640](https://linux-hardware.org/?probe=c72c5cf640) | Feb 13, 2023 |
| Dell          | Inspiron 1420               | [77c6839e06](https://linux-hardware.org/?probe=77c6839e06) | Feb 13, 2023 |
| Gigabyte      | AORUS 17G XC                | [b178c8781a](https://linux-hardware.org/?probe=b178c8781a) | Feb 13, 2023 |
| ASUSTek       | N552VX                      | [0291bab69a](https://linux-hardware.org/?probe=0291bab69a) | Feb 13, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [617c2c847a](https://linux-hardware.org/?probe=617c2c847a) | Feb 12, 2023 |
| Acer          | Aspire E5-574G              | [cdbd2ad757](https://linux-hardware.org/?probe=cdbd2ad757) | Feb 12, 2023 |
| Dell          | Vostro 15 3510              | [8291db193a](https://linux-hardware.org/?probe=8291db193a) | Feb 11, 2023 |
| Fujitsu       | LIFEBOOK U748               | [2a189f2497](https://linux-hardware.org/?probe=2a189f2497) | Feb 11, 2023 |
| HP            | Laptop 14s-fq1xxx           | [afe2d79c09](https://linux-hardware.org/?probe=afe2d79c09) | Feb 11, 2023 |
| Apple         | MacBookAir5,2               | [4f99163f99](https://linux-hardware.org/?probe=4f99163f99) | Feb 11, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [1aba056aa4](https://linux-hardware.org/?probe=1aba056aa4) | Feb 11, 2023 |
| Lenovo        | ThinkPad T450 20BUS1110E    | [d08c46c46d](https://linux-hardware.org/?probe=d08c46c46d) | Feb 10, 2023 |
| HP            | ProBook 450 G6              | [427533836c](https://linux-hardware.org/?probe=427533836c) | Feb 10, 2023 |
| ASUSTek       | UX31E                       | [e8fdc1676a](https://linux-hardware.org/?probe=e8fdc1676a) | Feb 10, 2023 |
| Acer          | Aspire One 753              | [b3ef912b35](https://linux-hardware.org/?probe=b3ef912b35) | Feb 10, 2023 |
| Toshiba       | Satellite L750              | [b6239c152e](https://linux-hardware.org/?probe=b6239c152e) | Feb 10, 2023 |
| HP            | 635                         | [c29c6a3347](https://linux-hardware.org/?probe=c29c6a3347) | Feb 09, 2023 |
| Lenovo        | ThinkPad T530 2429MY2       | [9b5ffc7c58](https://linux-hardware.org/?probe=9b5ffc7c58) | Feb 09, 2023 |
| HP            | 255 G4                      | [00870a3da9](https://linux-hardware.org/?probe=00870a3da9) | Feb 09, 2023 |
| Lenovo        | ThinkPad T440p 20AWA1MDJ... | [cc5f5375d2](https://linux-hardware.org/?probe=cc5f5375d2) | Feb 09, 2023 |
| Toshiba       | dynabook T653/46JR          | [2422c70d2e](https://linux-hardware.org/?probe=2422c70d2e) | Feb 09, 2023 |
| Sony          | SVE1513U1ESI                | [77dafc35f5](https://linux-hardware.org/?probe=77dafc35f5) | Feb 09, 2023 |
| HP            | Laptop 14-fq0xxx            | [307b9d4a7b](https://linux-hardware.org/?probe=307b9d4a7b) | Feb 09, 2023 |
| HP            | Pavilion 17                 | [6ef7e95717](https://linux-hardware.org/?probe=6ef7e95717) | Feb 09, 2023 |
| HUAWEI        | KPL-W0X                     | [43c589627c](https://linux-hardware.org/?probe=43c589627c) | Feb 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [f163a3dd38](https://linux-hardware.org/?probe=f163a3dd38) | Feb 09, 2023 |
| Acer          | Aspire A515-51              | [5e1eb34232](https://linux-hardware.org/?probe=5e1eb34232) | Feb 09, 2023 |
| Dell          | Inspiron 3576               | [69949c02d9](https://linux-hardware.org/?probe=69949c02d9) | Feb 09, 2023 |
| Dell          | Precision M6500             | [dcabcd8d63](https://linux-hardware.org/?probe=dcabcd8d63) | Feb 09, 2023 |
| EXTRA Comp... | A9100                       | [67278c37d9](https://linux-hardware.org/?probe=67278c37d9) | Feb 08, 2023 |
| Dell          | Inspiron 3558               | [310425ba43](https://linux-hardware.org/?probe=310425ba43) | Feb 08, 2023 |
| HP            | Notebook                    | [7d4a89adea](https://linux-hardware.org/?probe=7d4a89adea) | Feb 08, 2023 |
| Lenovo        | G780 2182                   | [7a27aa3d93](https://linux-hardware.org/?probe=7a27aa3d93) | Feb 08, 2023 |
| Dell          | Latitude E7440              | [ac0e96d86c](https://linux-hardware.org/?probe=ac0e96d86c) | Feb 08, 2023 |
| HP            | Compaq Presario CQ61        | [df4d59acd5](https://linux-hardware.org/?probe=df4d59acd5) | Feb 07, 2023 |
| HP            | ProBook 4530s               | [c081fdc9be](https://linux-hardware.org/?probe=c081fdc9be) | Feb 07, 2023 |
| Acer          | AO722                       | [d8552fd97a](https://linux-hardware.org/?probe=d8552fd97a) | Feb 07, 2023 |
| HP            | Laptop 15-db0xxx            | [8cb1801046](https://linux-hardware.org/?probe=8cb1801046) | Feb 07, 2023 |
| Lenovo        | ThinkPad X240 20AL00FMGE    | [0ac2678512](https://linux-hardware.org/?probe=0ac2678512) | Feb 06, 2023 |
| Wortmann      | TERRA_MOBILE_1512/1712      | [d929f6ba34](https://linux-hardware.org/?probe=d929f6ba34) | Feb 06, 2023 |
| Acer          | Aspire E5-573G              | [b0c2be9f04](https://linux-hardware.org/?probe=b0c2be9f04) | Feb 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a2378e95f6](https://linux-hardware.org/?probe=a2378e95f6) | Feb 06, 2023 |
| HP            | 250 G5 Notebook PC          | [d389ca29d1](https://linux-hardware.org/?probe=d389ca29d1) | Feb 06, 2023 |
| Acer          | Extensa 5635                | [8f8f4d24f9](https://linux-hardware.org/?probe=8f8f4d24f9) | Feb 06, 2023 |
| Lenovo        | ThinkPad E590 20NBCTO1WW    | [5260560c15](https://linux-hardware.org/?probe=5260560c15) | Feb 06, 2023 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | [e55411b47c](https://linux-hardware.org/?probe=e55411b47c) | Feb 06, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [1867884ede](https://linux-hardware.org/?probe=1867884ede) | Feb 06, 2023 |
| HP            | EliteBook 8570p             | [93c3d6c151](https://linux-hardware.org/?probe=93c3d6c151) | Feb 06, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [7ca566f68b](https://linux-hardware.org/?probe=7ca566f68b) | Feb 05, 2023 |
| Quanta        | TWS                         | [275ccf1b58](https://linux-hardware.org/?probe=275ccf1b58) | Feb 05, 2023 |
| Standard      | Unknown                     | [c983c471de](https://linux-hardware.org/?probe=c983c471de) | Feb 05, 2023 |
| HP            | Pro x2 612 G1 Tablet        | [6e00c72683](https://linux-hardware.org/?probe=6e00c72683) | Feb 05, 2023 |
| Samsung       | Q330                        | [feddb64b95](https://linux-hardware.org/?probe=feddb64b95) | Feb 05, 2023 |
| HP            | EliteBook 8540p             | [1614d002e0](https://linux-hardware.org/?probe=1614d002e0) | Feb 05, 2023 |
| Acer          | Aspire A315-21              | [b452c164d0](https://linux-hardware.org/?probe=b452c164d0) | Feb 05, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [295fd70d70](https://linux-hardware.org/?probe=295fd70d70) | Feb 05, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5829f2d4a3](https://linux-hardware.org/?probe=5829f2d4a3) | Feb 05, 2023 |
| PCsmart       | PCSGOB14p-C                 | [9cf7aff807](https://linux-hardware.org/?probe=9cf7aff807) | Feb 05, 2023 |
| Toshiba       | Satellite P875              | [9f70f3ba02](https://linux-hardware.org/?probe=9f70f3ba02) | Feb 05, 2023 |
| Lenovo        | G400s VILG1                 | [426348e103](https://linux-hardware.org/?probe=426348e103) | Feb 05, 2023 |
| Toshiba       | Satellite C55-A-168         | [e92c2babc4](https://linux-hardware.org/?probe=e92c2babc4) | Feb 05, 2023 |
| Toshiba       | Satellite C855-1LG          | [26ce54002a](https://linux-hardware.org/?probe=26ce54002a) | Feb 05, 2023 |
| Notebook      | W25CSW                      | [b63184cd07](https://linux-hardware.org/?probe=b63184cd07) | Feb 05, 2023 |
| HP            | 255 G8 Notebook PC          | [c373d892e3](https://linux-hardware.org/?probe=c373d892e3) | Feb 05, 2023 |
| Lenovo        | ThinkPad X260 20F5S65B0J    | [cca484a94e](https://linux-hardware.org/?probe=cca484a94e) | Feb 04, 2023 |
| Apple         | MacBookPro8,1               | [d6adca1255](https://linux-hardware.org/?probe=d6adca1255) | Feb 04, 2023 |
| Acer          | Aspire ES1-531              | [4d2872e685](https://linux-hardware.org/?probe=4d2872e685) | Feb 04, 2023 |
| Apple         | MacBookPro8,1               | [9765b77a43](https://linux-hardware.org/?probe=9765b77a43) | Feb 04, 2023 |
| Toshiba       | dynabook T653/46JR          | [6c1119bb00](https://linux-hardware.org/?probe=6c1119bb00) | Feb 04, 2023 |
| Google        | Peppy                       | [75cf34ef43](https://linux-hardware.org/?probe=75cf34ef43) | Feb 04, 2023 |
| Acer          | Aspire A715-42G             | [b983191b0d](https://linux-hardware.org/?probe=b983191b0d) | Feb 04, 2023 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [d6d63e0add](https://linux-hardware.org/?probe=d6d63e0add) | Feb 04, 2023 |
| HP            | ProBook 6465b               | [00b2021fae](https://linux-hardware.org/?probe=00b2021fae) | Feb 04, 2023 |
| ASUSTek       | K52JT                       | [fa36e91793](https://linux-hardware.org/?probe=fa36e91793) | Feb 04, 2023 |
| Dell          | Latitude 3500               | [79cdb991bf](https://linux-hardware.org/?probe=79cdb991bf) | Feb 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [c6dae92093](https://linux-hardware.org/?probe=c6dae92093) | Feb 03, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | [524d0c0226](https://linux-hardware.org/?probe=524d0c0226) | Feb 03, 2023 |
| Acer          | Aspire A315-58              | [32563eeffc](https://linux-hardware.org/?probe=32563eeffc) | Feb 03, 2023 |
| Dell          | Inspiron N5040              | [fc65b60f9b](https://linux-hardware.org/?probe=fc65b60f9b) | Feb 03, 2023 |
| Acer          | Aspire A715-42G             | [0a29f42fab](https://linux-hardware.org/?probe=0a29f42fab) | Feb 03, 2023 |
| Dell          | Inspiron 7720               | [724d6ad4ed](https://linux-hardware.org/?probe=724d6ad4ed) | Feb 03, 2023 |
| HP            | Unknown                     | [4b28efe30c](https://linux-hardware.org/?probe=4b28efe30c) | Feb 03, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [e3ab731c3c](https://linux-hardware.org/?probe=e3ab731c3c) | Feb 02, 2023 |
| HP            | Notebook                    | [82068da14b](https://linux-hardware.org/?probe=82068da14b) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [992dfcbbe6](https://linux-hardware.org/?probe=992dfcbbe6) | Feb 02, 2023 |
| MSI           | GV62 7RD                    | [c22fffb4e9](https://linux-hardware.org/?probe=c22fffb4e9) | Feb 02, 2023 |
| Insyde        | Braswell                    | [928b461a5b](https://linux-hardware.org/?probe=928b461a5b) | Feb 02, 2023 |
| Gateway       | LT41P                       | [1684d937e7](https://linux-hardware.org/?probe=1684d937e7) | Feb 02, 2023 |
| Philco        | 14I                         | [8f9833285e](https://linux-hardware.org/?probe=8f9833285e) | Feb 01, 2023 |
| ASUSTek       | S551LN                      | [b7361dbc53](https://linux-hardware.org/?probe=b7361dbc53) | Feb 01, 2023 |
| Google        | Pantheon                    | [12e0b96dd1](https://linux-hardware.org/?probe=12e0b96dd1) | Feb 01, 2023 |
| Dell          | Precision M6700             | [743cb766c2](https://linux-hardware.org/?probe=743cb766c2) | Feb 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [08e071efa2](https://linux-hardware.org/?probe=08e071efa2) | Feb 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [ab57658c86](https://linux-hardware.org/?probe=ab57658c86) | Jan 31, 2023 |
| HP            | Laptop 14s-dq3xxx           | [12ebaf0896](https://linux-hardware.org/?probe=12ebaf0896) | Jan 31, 2023 |
| Dell          | Latitude 5480               | [8b43efc7ea](https://linux-hardware.org/?probe=8b43efc7ea) | Jan 31, 2023 |
| Aquarius      | Cmp NS685U                  | [b067e76e64](https://linux-hardware.org/?probe=b067e76e64) | Jan 31, 2023 |
| Dell          | Studio 1558                 | [acfea4cd33](https://linux-hardware.org/?probe=acfea4cd33) | Jan 31, 2023 |
| Unknown       | Unknown                     | [e6c824b966](https://linux-hardware.org/?probe=e6c824b966) | Jan 31, 2023 |
| Dell          | Latitude E5420              | [ccc3ca9853](https://linux-hardware.org/?probe=ccc3ca9853) | Jan 31, 2023 |
| ASUSTek       | X55VD                       | [4120c1019c](https://linux-hardware.org/?probe=4120c1019c) | Jan 30, 2023 |
| HP            | 3115-AEC13432GR1            | [98eb70341a](https://linux-hardware.org/?probe=98eb70341a) | Jan 30, 2023 |
| Toshiba       | Satellite P750              | [1cc0f342b5](https://linux-hardware.org/?probe=1cc0f342b5) | Jan 30, 2023 |
| HP            | Compaq Presario CQ70        | [07e9e57b88](https://linux-hardware.org/?probe=07e9e57b88) | Jan 30, 2023 |
| Dell          | Inspiron 5758               | [de58233dca](https://linux-hardware.org/?probe=de58233dca) | Jan 30, 2023 |
| Dell          | Latitude E6400              | [a195487665](https://linux-hardware.org/?probe=a195487665) | Jan 30, 2023 |
| Acer          | Aspire E1-572G              | [6064a923c6](https://linux-hardware.org/?probe=6064a923c6) | Jan 30, 2023 |
| Acer          | Aspire 5755G                | [03c2f11b67](https://linux-hardware.org/?probe=03c2f11b67) | Jan 30, 2023 |
| Acer          | Aspire A515-41G             | [88db10e257](https://linux-hardware.org/?probe=88db10e257) | Jan 30, 2023 |
| Acer          | Aspire A515-52              | [51fa3ff577](https://linux-hardware.org/?probe=51fa3ff577) | Jan 30, 2023 |
| Unknown       | Unknown                     | [d780984cf9](https://linux-hardware.org/?probe=d780984cf9) | Jan 30, 2023 |
| HP            | ProBook 5320m               | [b8fc81e61c](https://linux-hardware.org/?probe=b8fc81e61c) | Jan 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [51245400df](https://linux-hardware.org/?probe=51245400df) | Jan 29, 2023 |
| ASUSTek       | K55A                        | [e3088b45e1](https://linux-hardware.org/?probe=e3088b45e1) | Jan 29, 2023 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [3912652a13](https://linux-hardware.org/?probe=3912652a13) | Jan 29, 2023 |
| Dell          | Inspiron 5520               | [6de5bc549f](https://linux-hardware.org/?probe=6de5bc549f) | Jan 29, 2023 |
| Positivo      | Q464C-O                     | [e61f2d0622](https://linux-hardware.org/?probe=e61f2d0622) | Jan 29, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [e2fa9aa820](https://linux-hardware.org/?probe=e2fa9aa820) | Jan 29, 2023 |
| TUXEDO        | N14xWU                      | [5681ab6b5d](https://linux-hardware.org/?probe=5681ab6b5d) | Jan 28, 2023 |
| HP            | Notebook                    | [d38e078368](https://linux-hardware.org/?probe=d38e078368) | Jan 28, 2023 |
| ASUSTek       | K43SJ                       | [0cff4ad069](https://linux-hardware.org/?probe=0cff4ad069) | Jan 28, 2023 |
| ASUSTek       | 1215B                       | [8d26a8d157](https://linux-hardware.org/?probe=8d26a8d157) | Jan 28, 2023 |
| Lenovo        | ThinkPad X61 7674BE1        | [a22ac0a9f5](https://linux-hardware.org/?probe=a22ac0a9f5) | Jan 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0245809d6a](https://linux-hardware.org/?probe=0245809d6a) | Jan 28, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [2b2401b0f0](https://linux-hardware.org/?probe=2b2401b0f0) | Jan 28, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [796df2715d](https://linux-hardware.org/?probe=796df2715d) | Jan 28, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [25ea296433](https://linux-hardware.org/?probe=25ea296433) | Jan 28, 2023 |
| HP            | EliteBook 8540w (VD444AD... | [eeb394333a](https://linux-hardware.org/?probe=eeb394333a) | Jan 28, 2023 |
| ASUSTek       | X540SA                      | [93aed28230](https://linux-hardware.org/?probe=93aed28230) | Jan 27, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [d825caa85e](https://linux-hardware.org/?probe=d825caa85e) | Jan 27, 2023 |
| Acer          | Peppy                       | [9a16262be8](https://linux-hardware.org/?probe=9a16262be8) | Jan 27, 2023 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [ee351959a0](https://linux-hardware.org/?probe=ee351959a0) | Jan 27, 2023 |
| Acer          | Aspire E1-522               | [b1e1e4bb29](https://linux-hardware.org/?probe=b1e1e4bb29) | Jan 27, 2023 |
| Apple         | MacBook4,1                  | [e00443a9cc](https://linux-hardware.org/?probe=e00443a9cc) | Jan 27, 2023 |
| ASUSTek       | UX31E                       | [d87ac57c19](https://linux-hardware.org/?probe=d87ac57c19) | Jan 27, 2023 |
| Schenker      | XMG FOCUS (M22)             | [b04fdbb6da](https://linux-hardware.org/?probe=b04fdbb6da) | Jan 27, 2023 |
| HP            | 14                          | [53d080d83a](https://linux-hardware.org/?probe=53d080d83a) | Jan 27, 2023 |
| MSI           | CX600                       | [643c7effe7](https://linux-hardware.org/?probe=643c7effe7) | Jan 27, 2023 |
| NEC Comput... | PC-NS350AAR-KS              | [c4aa0da6f4](https://linux-hardware.org/?probe=c4aa0da6f4) | Jan 27, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [85dbbce597](https://linux-hardware.org/?probe=85dbbce597) | Jan 27, 2023 |
| Dell          | Inspiron 3585               | [b41a540bb4](https://linux-hardware.org/?probe=b41a540bb4) | Jan 27, 2023 |
| Lenovo        | V15-ADA 82C7                | [5e42d7b8a7](https://linux-hardware.org/?probe=5e42d7b8a7) | Jan 27, 2023 |
| Acer          | Aspire R3-131T              | [021d999708](https://linux-hardware.org/?probe=021d999708) | Jan 27, 2023 |
| ASUSTek       | X541UJ                      | [d9ceb3c732](https://linux-hardware.org/?probe=d9ceb3c732) | Jan 27, 2023 |
| EVOO          | TEV-CE-141-2                | [21e4d23b45](https://linux-hardware.org/?probe=21e4d23b45) | Jan 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [e35fa4ee0f](https://linux-hardware.org/?probe=e35fa4ee0f) | Jan 26, 2023 |
| HP            | ProBook 640 G2              | [4e8cd1aa46](https://linux-hardware.org/?probe=4e8cd1aa46) | Jan 26, 2023 |
| Dell          | Inspiron 15 3521            | [41f89081ff](https://linux-hardware.org/?probe=41f89081ff) | Jan 26, 2023 |
| ASUSTek       | X501A1                      | [a0493c6731](https://linux-hardware.org/?probe=a0493c6731) | Jan 26, 2023 |
| Dell          | Latitude 7400               | [697e996615](https://linux-hardware.org/?probe=697e996615) | Jan 26, 2023 |
| Lenovo        | ThinkPad T440p 20AN0079M... | [0065b33518](https://linux-hardware.org/?probe=0065b33518) | Jan 26, 2023 |
| Lenovo        | ThinkPad T440p 20AWS24B0... | [e4ddea6092](https://linux-hardware.org/?probe=e4ddea6092) | Jan 26, 2023 |
| Dell          | Precision 7720              | [f5e8281d01](https://linux-hardware.org/?probe=f5e8281d01) | Jan 26, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0Q... | [cdd3eb5723](https://linux-hardware.org/?probe=cdd3eb5723) | Jan 26, 2023 |
| HONOR         | HLYL-WXX9                   | [00c90b28ca](https://linux-hardware.org/?probe=00c90b28ca) | Jan 26, 2023 |
| Lenovo        | G50-45 80E3                 | [bad5c1a1b8](https://linux-hardware.org/?probe=bad5c1a1b8) | Jan 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [08204bf161](https://linux-hardware.org/?probe=08204bf161) | Jan 26, 2023 |
| HP            | Laptop 15-ef1xxx            | [5ccbc70956](https://linux-hardware.org/?probe=5ccbc70956) | Jan 25, 2023 |
| Notebook      | NL40_50CU                   | [5029ce2c1e](https://linux-hardware.org/?probe=5029ce2c1e) | Jan 25, 2023 |
| Toshiba       | Satellite C870-12F          | [fc9a6d3a7e](https://linux-hardware.org/?probe=fc9a6d3a7e) | Jan 25, 2023 |
| Toshiba       | Satellite Pro R50-B         | [d08118920b](https://linux-hardware.org/?probe=d08118920b) | Jan 25, 2023 |
| OEGStone      | C4100/C5100                 | [4365b7b231](https://linux-hardware.org/?probe=4365b7b231) | Jan 25, 2023 |
| HP            | Pavilion g6                 | [a247cbd6d4](https://linux-hardware.org/?probe=a247cbd6d4) | Jan 25, 2023 |
| HP            | ProBook 4545s               | [1d832fb2f4](https://linux-hardware.org/?probe=1d832fb2f4) | Jan 25, 2023 |
| HP            | EliteBook 8460p             | [bb83f545f7](https://linux-hardware.org/?probe=bb83f545f7) | Jan 24, 2023 |
| Acer          | Aspire A315-22              | [7c048a8058](https://linux-hardware.org/?probe=7c048a8058) | Jan 24, 2023 |
| Dell          | Inspiron 3421               | [02491de92f](https://linux-hardware.org/?probe=02491de92f) | Jan 24, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [a1a1be6b56](https://linux-hardware.org/?probe=a1a1be6b56) | Jan 24, 2023 |
| Acer          | Aspire V5-132               | [7f74397112](https://linux-hardware.org/?probe=7f74397112) | Jan 24, 2023 |
| Toshiba       | dynabook T653/46JR          | [00cabfbb97](https://linux-hardware.org/?probe=00cabfbb97) | Jan 24, 2023 |
| Acer          | Aspire A515-51              | [418e5a2787](https://linux-hardware.org/?probe=418e5a2787) | Jan 24, 2023 |
| Insyde        | Braswell                    | [6abab0adc1](https://linux-hardware.org/?probe=6abab0adc1) | Jan 24, 2023 |
| Toshiba       | Satellite C655D             | [bf86cea0ec](https://linux-hardware.org/?probe=bf86cea0ec) | Jan 24, 2023 |
| Toshiba       | Satellite Pro C660          | [3ffb5ed458](https://linux-hardware.org/?probe=3ffb5ed458) | Jan 24, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [7b23698a1e](https://linux-hardware.org/?probe=7b23698a1e) | Jan 24, 2023 |
| Lenovo        | ThinkPad W541 20EF0020MD    | [fca73ad2a9](https://linux-hardware.org/?probe=fca73ad2a9) | Jan 24, 2023 |
| ASUSTek       | X51L                        | [b482dc649b](https://linux-hardware.org/?probe=b482dc649b) | Jan 23, 2023 |
| Dell          | Latitude E5530 non-vPro     | [5ddcb9f78b](https://linux-hardware.org/?probe=5ddcb9f78b) | Jan 23, 2023 |
| Packard Be... | PB56                        | [f26fcb7ee5](https://linux-hardware.org/?probe=f26fcb7ee5) | Jan 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [a05bb7e519](https://linux-hardware.org/?probe=a05bb7e519) | Jan 23, 2023 |
| Lenovo        | ThinkPad T430 2344BZU       | [5e8acadc64](https://linux-hardware.org/?probe=5e8acadc64) | Jan 23, 2023 |
| HP            | EliteBook 745 G3            | [1fda4d1e4a](https://linux-hardware.org/?probe=1fda4d1e4a) | Jan 23, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [40719006ae](https://linux-hardware.org/?probe=40719006ae) | Jan 23, 2023 |
| Dell          | Latitude E6430s             | [8d46b5ae49](https://linux-hardware.org/?probe=8d46b5ae49) | Jan 23, 2023 |
| HP            | Pavilion Notebook           | [6383000f9e](https://linux-hardware.org/?probe=6383000f9e) | Jan 23, 2023 |
| Acer          | Nitro AN515-42              | [8692de1465](https://linux-hardware.org/?probe=8692de1465) | Jan 23, 2023 |
| ASUSTek       | K45VM                       | [7fef453cdb](https://linux-hardware.org/?probe=7fef453cdb) | Jan 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [89c37ebdfa](https://linux-hardware.org/?probe=89c37ebdfa) | Jan 22, 2023 |
| MSI           | PX60 6QE                    | [d820232c9c](https://linux-hardware.org/?probe=d820232c9c) | Jan 22, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [36d99ec94e](https://linux-hardware.org/?probe=36d99ec94e) | Jan 22, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7d4406c9bc](https://linux-hardware.org/?probe=7d4406c9bc) | Jan 22, 2023 |
| Lenovo        | ThinkPad W530 244723G       | [d0e5903d6c](https://linux-hardware.org/?probe=d0e5903d6c) | Jan 22, 2023 |
| HP            | Laptop 15-dw3xxx            | [50d894fc60](https://linux-hardware.org/?probe=50d894fc60) | Jan 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [09650cf189](https://linux-hardware.org/?probe=09650cf189) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a09d1d224c](https://linux-hardware.org/?probe=a09d1d224c) | Jan 22, 2023 |
| Dell          | Latitude E5430 non-vPro     | [4ff88ad220](https://linux-hardware.org/?probe=4ff88ad220) | Jan 22, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [f3e565ffa6](https://linux-hardware.org/?probe=f3e565ffa6) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [6ae7274931](https://linux-hardware.org/?probe=6ae7274931) | Jan 22, 2023 |
| Acer          | Aspire E1-531               | [217c63b8f6](https://linux-hardware.org/?probe=217c63b8f6) | Jan 22, 2023 |
| Toshiba       | dynabook T653/46JR          | [1acfabc208](https://linux-hardware.org/?probe=1acfabc208) | Jan 22, 2023 |
| ASUSTek       | ROG Strix G733CX_G733CX     | [a02df0f932](https://linux-hardware.org/?probe=a02df0f932) | Jan 21, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [40560e6bcd](https://linux-hardware.org/?probe=40560e6bcd) | Jan 21, 2023 |
| HP            | EliteBook 8570p             | [66c806fbfe](https://linux-hardware.org/?probe=66c806fbfe) | Jan 21, 2023 |
| Acer          | Aspire A515-45G             | [df633f4583](https://linux-hardware.org/?probe=df633f4583) | Jan 21, 2023 |
| ASUSTek       | N56VZ                       | [46ec3e0f8f](https://linux-hardware.org/?probe=46ec3e0f8f) | Jan 21, 2023 |
| HP            | EliteBook 850 G2            | [a7ba34fed5](https://linux-hardware.org/?probe=a7ba34fed5) | Jan 21, 2023 |
| Philco        | OEM                         | [a39f50ccfd](https://linux-hardware.org/?probe=a39f50ccfd) | Jan 21, 2023 |
| Lenovo        | ThinkPad X120e 05962RU      | [1628e3e66e](https://linux-hardware.org/?probe=1628e3e66e) | Jan 21, 2023 |
| HP            | Compaq Presario C700        | [d2ec58874c](https://linux-hardware.org/?probe=d2ec58874c) | Jan 21, 2023 |
| Acer          | Aspire E1-530               | [af5f0b7f58](https://linux-hardware.org/?probe=af5f0b7f58) | Jan 21, 2023 |
| Acer          | Aspire 7745G                | [98d6ab791c](https://linux-hardware.org/?probe=98d6ab791c) | Jan 21, 2023 |
| HP            | Laptop 17-by0xxx            | [88958e2846](https://linux-hardware.org/?probe=88958e2846) | Jan 20, 2023 |
| HP            | Victus by Laptop 16-e1xx... | [65919b95b4](https://linux-hardware.org/?probe=65919b95b4) | Jan 20, 2023 |
| HP            | Pavilion dv5                | [94ba65752b](https://linux-hardware.org/?probe=94ba65752b) | Jan 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6364be5249](https://linux-hardware.org/?probe=6364be5249) | Jan 20, 2023 |
| Dell          | Inspiron N4050              | [46e35da681](https://linux-hardware.org/?probe=46e35da681) | Jan 20, 2023 |
| Lenovo        | V570 1066AWU                | [7d86d12566](https://linux-hardware.org/?probe=7d86d12566) | Jan 20, 2023 |
| Dell          | Inspiron 15-3567            | [33a3aac223](https://linux-hardware.org/?probe=33a3aac223) | Jan 20, 2023 |
| Lenovo        | Z710 20250                  | [f59ce535eb](https://linux-hardware.org/?probe=f59ce535eb) | Jan 20, 2023 |
| Acer          | Aspire E1-531               | [614c392e0f](https://linux-hardware.org/?probe=614c392e0f) | Jan 20, 2023 |
| Toshiba       | Satellite C45-A             | [16f5bae11f](https://linux-hardware.org/?probe=16f5bae11f) | Jan 20, 2023 |
| Acer          | Aspire E3-111               | [fde7baf9e8](https://linux-hardware.org/?probe=fde7baf9e8) | Jan 19, 2023 |
| Dell          | Inspiron 5567               | [a993e95dde](https://linux-hardware.org/?probe=a993e95dde) | Jan 19, 2023 |
| Dell          | Vostro 1220                 | [6cd42b6be3](https://linux-hardware.org/?probe=6cd42b6be3) | Jan 19, 2023 |
| Apple         | MacBookPro8,1               | [b7f8407c8f](https://linux-hardware.org/?probe=b7f8407c8f) | Jan 19, 2023 |
| Alienware     | 15 R2                       | [3d9c86b05e](https://linux-hardware.org/?probe=3d9c86b05e) | Jan 19, 2023 |
| Dell          | Inspiron 3585               | [9790dcdef4](https://linux-hardware.org/?probe=9790dcdef4) | Jan 19, 2023 |
| Dell          | Inspiron 5770               | [64976ae263](https://linux-hardware.org/?probe=64976ae263) | Jan 19, 2023 |
| Toshiba       | Satellite L650D             | [86d99d74cd](https://linux-hardware.org/?probe=86d99d74cd) | Jan 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | [8bcbca2ea9](https://linux-hardware.org/?probe=8bcbca2ea9) | Jan 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | [3572cb486b](https://linux-hardware.org/?probe=3572cb486b) | Jan 19, 2023 |
| Lenovo        | ThinkPad SL510 2847CZU      | [710998b216](https://linux-hardware.org/?probe=710998b216) | Jan 19, 2023 |
| Sony          | VPCF236FM                   | [c2ed0fe829](https://linux-hardware.org/?probe=c2ed0fe829) | Jan 19, 2023 |
| HP            | Notebook                    | [63f0c0b90c](https://linux-hardware.org/?probe=63f0c0b90c) | Jan 19, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [da0d1f442a](https://linux-hardware.org/?probe=da0d1f442a) | Jan 19, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [2e66a90abd](https://linux-hardware.org/?probe=2e66a90abd) | Jan 19, 2023 |
| Toshiba       | Satellite C70-A             | [ffaa715bdd](https://linux-hardware.org/?probe=ffaa715bdd) | Jan 19, 2023 |
| Dell          | Inspiron 1525               | [f4df69624c](https://linux-hardware.org/?probe=f4df69624c) | Jan 19, 2023 |
| Lenovo        | ThinkPad T450 20BUS39J00    | [d5c413e815](https://linux-hardware.org/?probe=d5c413e815) | Jan 19, 2023 |
| Acer          | Aspire ES1-432              | [4a81caf8b2](https://linux-hardware.org/?probe=4a81caf8b2) | Jan 18, 2023 |
| Toshiba       | Satellite L70-C-12H         | [aa6340dd48](https://linux-hardware.org/?probe=aa6340dd48) | Jan 18, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [3fa537973f](https://linux-hardware.org/?probe=3fa537973f) | Jan 18, 2023 |
| Lenovo        | ThinkPad X200 7459VB9       | [a58c604cf7](https://linux-hardware.org/?probe=a58c604cf7) | Jan 18, 2023 |
| Dell          | Inspiron 3501               | [a9cad4d873](https://linux-hardware.org/?probe=a9cad4d873) | Jan 18, 2023 |
| HP            | Pavilion dv5                | [2ab5c1d05d](https://linux-hardware.org/?probe=2ab5c1d05d) | Jan 18, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [377dd4141e](https://linux-hardware.org/?probe=377dd4141e) | Jan 18, 2023 |
| Panasonic     | CF-53JULCV1M                | [89c1166efc](https://linux-hardware.org/?probe=89c1166efc) | Jan 18, 2023 |
| ASUSTek       | X411UN                      | [fad0f7ce44](https://linux-hardware.org/?probe=fad0f7ce44) | Jan 18, 2023 |
| Dell          | Inspiron N5110              | [bf606ed50a](https://linux-hardware.org/?probe=bf606ed50a) | Jan 18, 2023 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [04d0c02d29](https://linux-hardware.org/?probe=04d0c02d29) | Jan 18, 2023 |
| Acer          | Aspire 5750G                | [d696233b84](https://linux-hardware.org/?probe=d696233b84) | Jan 18, 2023 |
| Acer          | Aspire ES1-533              | [96f20a9e2f](https://linux-hardware.org/?probe=96f20a9e2f) | Jan 18, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | [5b0e671bb8](https://linux-hardware.org/?probe=5b0e671bb8) | Jan 18, 2023 |
| Dell          | Latitude E6510              | [d26d229a4d](https://linux-hardware.org/?probe=d26d229a4d) | Jan 18, 2023 |
| HP            | EliteBook 850 G5            | [4afba6f67d](https://linux-hardware.org/?probe=4afba6f67d) | Jan 18, 2023 |
| MSI           | Katana GF76 11UC            | [8c0b32cf24](https://linux-hardware.org/?probe=8c0b32cf24) | Jan 18, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1400CDA... | [7969ad351d](https://linux-hardware.org/?probe=7969ad351d) | Jan 18, 2023 |
| Lenovo        | G550 2958                   | [7b255b7fe7](https://linux-hardware.org/?probe=7b255b7fe7) | Jan 18, 2023 |
| Dell          | XPS 15 7590                 | [9a7659a260](https://linux-hardware.org/?probe=9a7659a260) | Jan 18, 2023 |
| Toshiba       | QOSMIO X505                 | [8b6dfa9517](https://linux-hardware.org/?probe=8b6dfa9517) | Jan 18, 2023 |
| HP            | ProBook 440 G1              | [035c7a4e2d](https://linux-hardware.org/?probe=035c7a4e2d) | Jan 18, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [03c7a9b8a1](https://linux-hardware.org/?probe=03c7a9b8a1) | Jan 18, 2023 |
| Dell          | Latitude 7490               | [b611fc6b64](https://linux-hardware.org/?probe=b611fc6b64) | Jan 18, 2023 |
| Dell          | Latitude D630               | [0d267a0217](https://linux-hardware.org/?probe=0d267a0217) | Jan 17, 2023 |
| Packard Be... | EasyNote LE69KB             | [b1caf1d323](https://linux-hardware.org/?probe=b1caf1d323) | Jan 17, 2023 |
| HUAWEI        | KLVL-WXX9                   | [bf8a560f29](https://linux-hardware.org/?probe=bf8a560f29) | Jan 17, 2023 |
| Toshiba       | Satellite L655D             | [38b26485d3](https://linux-hardware.org/?probe=38b26485d3) | Jan 17, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a20814cabc](https://linux-hardware.org/?probe=a20814cabc) | Jan 17, 2023 |
| Lenovo        | ThinkPad T61 766112G        | [fb772cc0cf](https://linux-hardware.org/?probe=fb772cc0cf) | Jan 17, 2023 |
| Toshiba       | Satellite C660              | [5012a7ccfc](https://linux-hardware.org/?probe=5012a7ccfc) | Jan 17, 2023 |
| HP            | Pavilion Gaming Notebook    | [03a01ae5f7](https://linux-hardware.org/?probe=03a01ae5f7) | Jan 17, 2023 |
| Dell          | Latitude E5540              | [e8e30eb563](https://linux-hardware.org/?probe=e8e30eb563) | Jan 17, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [d05225350d](https://linux-hardware.org/?probe=d05225350d) | Jan 17, 2023 |
| Dell          | Inspiron 14 5418            | [e3bfdaa6a4](https://linux-hardware.org/?probe=e3bfdaa6a4) | Jan 17, 2023 |
| Unknown       | Unknown                     | [aea2d1af0a](https://linux-hardware.org/?probe=aea2d1af0a) | Jan 17, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [395a44652b](https://linux-hardware.org/?probe=395a44652b) | Jan 17, 2023 |
| MSI           | GP70 2OD                    | [7405037963](https://linux-hardware.org/?probe=7405037963) | Jan 17, 2023 |
| HP            | EliteBook 820 G3            | [4abc3c8796](https://linux-hardware.org/?probe=4abc3c8796) | Jan 17, 2023 |
| Acer          | Aspire A315-58              | [7a697f398d](https://linux-hardware.org/?probe=7a697f398d) | Jan 17, 2023 |
| Positivo      | N1103                       | [e5b41b9ed2](https://linux-hardware.org/?probe=e5b41b9ed2) | Jan 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [d7e87dd461](https://linux-hardware.org/?probe=d7e87dd461) | Jan 17, 2023 |
| Acer          | Aspire E1-572P              | [72afaf995e](https://linux-hardware.org/?probe=72afaf995e) | Jan 17, 2023 |
| Lenovo        | B50-10 80QR                 | [e5903bfd98](https://linux-hardware.org/?probe=e5903bfd98) | Jan 17, 2023 |
| Lenovo        | ThinkPad T420 4236AK9       | [1bd88ff8c7](https://linux-hardware.org/?probe=1bd88ff8c7) | Jan 17, 2023 |
| Dell          | Inspiron N4050              | [2de561e7f5](https://linux-hardware.org/?probe=2de561e7f5) | Jan 16, 2023 |
| ASUSTek       | 1018P                       | [45cdf08df5](https://linux-hardware.org/?probe=45cdf08df5) | Jan 16, 2023 |
| Google        | Lulu                        | [b0e2a5a9b3](https://linux-hardware.org/?probe=b0e2a5a9b3) | Jan 16, 2023 |
| Aquarius      | AQNS685V4                   | [1f0cd980d8](https://linux-hardware.org/?probe=1f0cd980d8) | Jan 16, 2023 |
| Acer          | Aspire 5742G                | [5cda575387](https://linux-hardware.org/?probe=5cda575387) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [fa4fd9061f](https://linux-hardware.org/?probe=fa4fd9061f) | Jan 16, 2023 |
| Lenovo        | G505 20240                  | [ef2fdd351c](https://linux-hardware.org/?probe=ef2fdd351c) | Jan 16, 2023 |
| Sony          | SVT1312M1ES                 | [9244e6ad96](https://linux-hardware.org/?probe=9244e6ad96) | Jan 16, 2023 |
| Lenovo        | ThinkPad T440s 20AQCTO1W... | [e04d230b62](https://linux-hardware.org/?probe=e04d230b62) | Jan 16, 2023 |
| Dell          | Latitude E7450              | [127258c518](https://linux-hardware.org/?probe=127258c518) | Jan 16, 2023 |
| HP            | Pavilion dv6500             | [33985f088a](https://linux-hardware.org/?probe=33985f088a) | Jan 16, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [a80f36a4eb](https://linux-hardware.org/?probe=a80f36a4eb) | Jan 16, 2023 |
| Acer          | Aspire ES1-711              | [1aef2805c2](https://linux-hardware.org/?probe=1aef2805c2) | Jan 16, 2023 |
| Acer          | Aspire E5-574               | [758f7a4cad](https://linux-hardware.org/?probe=758f7a4cad) | Jan 16, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [21c91371cc](https://linux-hardware.org/?probe=21c91371cc) | Jan 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | [32e5de4912](https://linux-hardware.org/?probe=32e5de4912) | Jan 15, 2023 |
| Sony          | VGN-AR51J                   | [ff9806f1ac](https://linux-hardware.org/?probe=ff9806f1ac) | Jan 15, 2023 |
| HP            | Compaq 15                   | [ddfd4fd188](https://linux-hardware.org/?probe=ddfd4fd188) | Jan 15, 2023 |
| Dell          | Precision 7520              | [c57fdfbe1e](https://linux-hardware.org/?probe=c57fdfbe1e) | Jan 15, 2023 |
| Dell          | Latitude E5430 non-vPro     | [57cd4eaca3](https://linux-hardware.org/?probe=57cd4eaca3) | Jan 15, 2023 |
| eMachines     | eME442                      | [9de636b72e](https://linux-hardware.org/?probe=9de636b72e) | Jan 15, 2023 |
| Acer          | Aspire 5736Z                | [bdfc087b4d](https://linux-hardware.org/?probe=bdfc087b4d) | Jan 15, 2023 |
| HP            | EliteBook 2560p             | [7d0cedda95](https://linux-hardware.org/?probe=7d0cedda95) | Jan 15, 2023 |
| HP            | ENVY dv7                    | [4b7b0f98af](https://linux-hardware.org/?probe=4b7b0f98af) | Jan 15, 2023 |
| HP            | 15                          | [3faa6c9265](https://linux-hardware.org/?probe=3faa6c9265) | Jan 15, 2023 |
| HP            | Presario CQ57               | [f223ceb77a](https://linux-hardware.org/?probe=f223ceb77a) | Jan 15, 2023 |
| Acer          | Nitro AN515-44              | [f1e7eba4ca](https://linux-hardware.org/?probe=f1e7eba4ca) | Jan 15, 2023 |
| Acer          | Aspire 7250                 | [bcb2916be8](https://linux-hardware.org/?probe=bcb2916be8) | Jan 15, 2023 |
| Toshiba       | Satellite L650              | [b893aecea2](https://linux-hardware.org/?probe=b893aecea2) | Jan 15, 2023 |
| Dell          | Latitude 3540               | [01688be251](https://linux-hardware.org/?probe=01688be251) | Jan 15, 2023 |
| HP            | EliteBook 745 G3            | [c20a339ddb](https://linux-hardware.org/?probe=c20a339ddb) | Jan 15, 2023 |
| Lenovo        | ThinkPad T490s 20NX001KM... | [e24691c830](https://linux-hardware.org/?probe=e24691c830) | Jan 15, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [f0b2886993](https://linux-hardware.org/?probe=f0b2886993) | Jan 15, 2023 |
| Dell          | Inspiron 5749               | [445264f815](https://linux-hardware.org/?probe=445264f815) | Jan 15, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [80ab61d971](https://linux-hardware.org/?probe=80ab61d971) | Jan 15, 2023 |
| Acer          | Aspire 5349                 | [c52d3b2b2f](https://linux-hardware.org/?probe=c52d3b2b2f) | Jan 15, 2023 |
| HP            | ZBook Firefly 14 inch G9... | [ca73cb526c](https://linux-hardware.org/?probe=ca73cb526c) | Jan 15, 2023 |
| Acer          | Aspire 7551                 | [b3e5df94f4](https://linux-hardware.org/?probe=b3e5df94f4) | Jan 15, 2023 |
| Monster       | TULPAR T5 V19.2             | [46bd0385fa](https://linux-hardware.org/?probe=46bd0385fa) | Jan 15, 2023 |
| HP            | ProBook 455 G1              | [8fbd7eb667](https://linux-hardware.org/?probe=8fbd7eb667) | Jan 15, 2023 |
| Apple         | MacBookPro9,2               | [2265827caa](https://linux-hardware.org/?probe=2265827caa) | Jan 14, 2023 |
| Kiano         | SlimNote 14,2               | [7596dc87b3](https://linux-hardware.org/?probe=7596dc87b3) | Jan 14, 2023 |
| Lenovo        | G50-45 80E3                 | [ab05084e01](https://linux-hardware.org/?probe=ab05084e01) | Jan 14, 2023 |
| Acer          | Aspire A315-34              | [656b21ed21](https://linux-hardware.org/?probe=656b21ed21) | Jan 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [03f7a5fdea](https://linux-hardware.org/?probe=03f7a5fdea) | Jan 14, 2023 |
| Acer          | AO725                       | [739986d5fa](https://linux-hardware.org/?probe=739986d5fa) | Jan 14, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [80f9124e5a](https://linux-hardware.org/?probe=80f9124e5a) | Jan 14, 2023 |
| Lenovo        | ThinkPad T540p 20BFS2G00... | [6c7af52ee2](https://linux-hardware.org/?probe=6c7af52ee2) | Jan 14, 2023 |
| Dell          | Precision M4700             | [64bd9a7627](https://linux-hardware.org/?probe=64bd9a7627) | Jan 14, 2023 |
| HP            | ZBook 17 G3                 | [9e4c15fff7](https://linux-hardware.org/?probe=9e4c15fff7) | Jan 14, 2023 |
| HP            | Pavilion g6                 | [fba7cebfff](https://linux-hardware.org/?probe=fba7cebfff) | Jan 14, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [d113da489f](https://linux-hardware.org/?probe=d113da489f) | Jan 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7cb08d37fb](https://linux-hardware.org/?probe=7cb08d37fb) | Jan 14, 2023 |
| HP            | Notebook                    | [4c9b4e3b67](https://linux-hardware.org/?probe=4c9b4e3b67) | Jan 14, 2023 |
| Acer          | Aspire M3-581T              | [f0ed3b4989](https://linux-hardware.org/?probe=f0ed3b4989) | Jan 14, 2023 |
| MSI           | GP72 7RDX                   | [9cf1da2d69](https://linux-hardware.org/?probe=9cf1da2d69) | Jan 14, 2023 |
| MSI           | GE62 6QF                    | [5ac082fab9](https://linux-hardware.org/?probe=5ac082fab9) | Jan 14, 2023 |
| Dell          | Latitude 3350               | [d7ca8710c2](https://linux-hardware.org/?probe=d7ca8710c2) | Jan 14, 2023 |
| Lenovo        | G585                        | [c7453a5e19](https://linux-hardware.org/?probe=c7453a5e19) | Jan 14, 2023 |
| Lenovo        | B51-80 80LM                 | [0c5b712b3e](https://linux-hardware.org/?probe=0c5b712b3e) | Jan 14, 2023 |
| Lenovo        | ThinkPad W540 20BHS1840P    | [0046521475](https://linux-hardware.org/?probe=0046521475) | Jan 14, 2023 |
| Samsung       | N150/N210/N220              | [5d2c7b7ded](https://linux-hardware.org/?probe=5d2c7b7ded) | Jan 14, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [b3c2be78b3](https://linux-hardware.org/?probe=b3c2be78b3) | Jan 14, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [116b26047d](https://linux-hardware.org/?probe=116b26047d) | Jan 14, 2023 |
| Lenovo        | ThinkPad L510 2873A17       | [13f5fd23e5](https://linux-hardware.org/?probe=13f5fd23e5) | Jan 14, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [da829cbbc7](https://linux-hardware.org/?probe=da829cbbc7) | Jan 14, 2023 |
| HUAWEI        | KPL-W0X                     | [d1175d8dba](https://linux-hardware.org/?probe=d1175d8dba) | Jan 14, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [56c9afafb4](https://linux-hardware.org/?probe=56c9afafb4) | Jan 14, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [e4e7a1d245](https://linux-hardware.org/?probe=e4e7a1d245) | Jan 14, 2023 |
| Dell          | Latitude E7440              | [9c4aac8b46](https://linux-hardware.org/?probe=9c4aac8b46) | Jan 14, 2023 |
| MSI           | GE70 2QD                    | [5e408d7d3d](https://linux-hardware.org/?probe=5e408d7d3d) | Jan 14, 2023 |
| Acer          | Aspire V3-571G              | [e3b9b73877](https://linux-hardware.org/?probe=e3b9b73877) | Jan 14, 2023 |
| Dell          | Latitude E6440              | [d04d05f246](https://linux-hardware.org/?probe=d04d05f246) | Jan 14, 2023 |
| Fujitsu       | LIFEBOOK A531               | [7157b47b73](https://linux-hardware.org/?probe=7157b47b73) | Jan 14, 2023 |
| Acer          | Aspire 5935                 | [40a8c82828](https://linux-hardware.org/?probe=40a8c82828) | Jan 14, 2023 |
| HP            | ProBook 4330s               | [e51cc0e32e](https://linux-hardware.org/?probe=e51cc0e32e) | Jan 14, 2023 |
| HP            | Laptop 15s-eq2xxx           | [29ff669f2c](https://linux-hardware.org/?probe=29ff669f2c) | Jan 14, 2023 |
| Samsung       | RV413/RV513                 | [4acb924b75](https://linux-hardware.org/?probe=4acb924b75) | Jan 14, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [b6c21b8d35](https://linux-hardware.org/?probe=b6c21b8d35) | Jan 14, 2023 |
| Dell          | Precision 3541              | [5691f35a09](https://linux-hardware.org/?probe=5691f35a09) | Jan 14, 2023 |
| Panasonic     | CF-SX2JDHYS                 | [fa1ebc0951](https://linux-hardware.org/?probe=fa1ebc0951) | Jan 14, 2023 |
| Dell          | Inspiron 5559               | [2cb923c446](https://linux-hardware.org/?probe=2cb923c446) | Jan 14, 2023 |
| Sony          | VPCEH10EB                   | [c9127c6375](https://linux-hardware.org/?probe=c9127c6375) | Jan 14, 2023 |
| Acer          | Calpella                    | [108843a25a](https://linux-hardware.org/?probe=108843a25a) | Jan 14, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [6cc913ff8f](https://linux-hardware.org/?probe=6cc913ff8f) | Jan 14, 2023 |
| Alienware     | 17 R3                       | [d4cf3c4f4d](https://linux-hardware.org/?probe=d4cf3c4f4d) | Jan 14, 2023 |
| ASUSTek       | X541UV                      | [d45c8ef0ac](https://linux-hardware.org/?probe=d45c8ef0ac) | Jan 13, 2023 |
| HP            | EliteBook 820 G3            | [3a330d3173](https://linux-hardware.org/?probe=3a330d3173) | Jan 13, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DK      | [3df12b0c9c](https://linux-hardware.org/?probe=3df12b0c9c) | Jan 13, 2023 |
| HP            | ProBook 4540s               | [9b33dc4291](https://linux-hardware.org/?probe=9b33dc4291) | Jan 13, 2023 |
| ASUSTek       | UX31E                       | [d60bab803e](https://linux-hardware.org/?probe=d60bab803e) | Jan 13, 2023 |
| Acer          | Nitro AN515-42              | [940dcb54ef](https://linux-hardware.org/?probe=940dcb54ef) | Jan 13, 2023 |
| eMachines     | E725                        | [048d832cef](https://linux-hardware.org/?probe=048d832cef) | Jan 13, 2023 |
| Dell          | Latitude E6410              | [a11818f59a](https://linux-hardware.org/?probe=a11818f59a) | Jan 13, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [0536f685a0](https://linux-hardware.org/?probe=0536f685a0) | Jan 13, 2023 |
| ASUSTek       | X751LJ                      | [2cbaf315da](https://linux-hardware.org/?probe=2cbaf315da) | Jan 13, 2023 |
| Apple         | MacBookAir5,2               | [c4cfa1aa47](https://linux-hardware.org/?probe=c4cfa1aa47) | Jan 13, 2023 |
| MSI           | CX61 0NC/CX61 0ND/CX61 0... | [fafc15930a](https://linux-hardware.org/?probe=fafc15930a) | Jan 13, 2023 |
| Fujitsu       | LIFEBOOK T730               | [f9ba03526e](https://linux-hardware.org/?probe=f9ba03526e) | Jan 13, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [968604ceb2](https://linux-hardware.org/?probe=968604ceb2) | Jan 13, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [f59adc6dcd](https://linux-hardware.org/?probe=f59adc6dcd) | Jan 13, 2023 |
| Acer          | Aspire A515-52              | [217353eb32](https://linux-hardware.org/?probe=217353eb32) | Jan 13, 2023 |
| Unknown       | Unknown                     | [d0391da5d8](https://linux-hardware.org/?probe=d0391da5d8) | Jan 13, 2023 |
| HP            | Notebook                    | [1baf122d48](https://linux-hardware.org/?probe=1baf122d48) | Jan 13, 2023 |
| Dell          | Vostro 3549                 | [b6970533c4](https://linux-hardware.org/?probe=b6970533c4) | Jan 13, 2023 |
| Lenovo        | B490 20205                  | [14243e79d2](https://linux-hardware.org/?probe=14243e79d2) | Jan 13, 2023 |
| Dell          | Latitude 7400               | [865f5e0e20](https://linux-hardware.org/?probe=865f5e0e20) | Jan 13, 2023 |
| Dell          | XPS 15 9570                 | [89b4a28536](https://linux-hardware.org/?probe=89b4a28536) | Jan 13, 2023 |
| HP            | EliteBook 2560p             | [9ac8dc707a](https://linux-hardware.org/?probe=9ac8dc707a) | Jan 13, 2023 |
| Acer          | Aspire E1-421               | [ebfd029f41](https://linux-hardware.org/?probe=ebfd029f41) | Jan 13, 2023 |
| Positivo      | Smash2                      | [d160522fb3](https://linux-hardware.org/?probe=d160522fb3) | Jan 13, 2023 |
| Acer          | Aspire E1-572               | [fa6e296766](https://linux-hardware.org/?probe=fa6e296766) | Jan 13, 2023 |
| TUXEDO        | Book XA15 / XA17 Gen10      | [343813c285](https://linux-hardware.org/?probe=343813c285) | Jan 13, 2023 |
| Acer          | Swift SF514-54GT            | [748c1e00d7](https://linux-hardware.org/?probe=748c1e00d7) | Jan 12, 2023 |
| MSI           | Katana GF66 11UC            | [39b5188695](https://linux-hardware.org/?probe=39b5188695) | Jan 12, 2023 |
| Lenovo        | ThinkPad T450 20BUA0UG00    | [b0854ecbf8](https://linux-hardware.org/?probe=b0854ecbf8) | Jan 12, 2023 |
| Acer          | Aspire V5-122               | [a25a7c3fb1](https://linux-hardware.org/?probe=a25a7c3fb1) | Jan 12, 2023 |
| Dell          | Inspiron 5520               | [56efcb1e01](https://linux-hardware.org/?probe=56efcb1e01) | Jan 12, 2023 |
| HP            | Laptop 15-dw3xxx            | [f37bb8688f](https://linux-hardware.org/?probe=f37bb8688f) | Jan 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [50dfb4259a](https://linux-hardware.org/?probe=50dfb4259a) | Jan 12, 2023 |
| Acer          | Aspire A315-56              | [6ea0b8eab9](https://linux-hardware.org/?probe=6ea0b8eab9) | Jan 12, 2023 |
| Acer          | Aspire 7730G                | [ba1e942da3](https://linux-hardware.org/?probe=ba1e942da3) | Jan 12, 2023 |
| Fujitsu Si... | AMILO Xi 3650               | [1f238129d8](https://linux-hardware.org/?probe=1f238129d8) | Jan 12, 2023 |
| Lenovo        | ThinkPad X230 23245J8       | [c20b87316b](https://linux-hardware.org/?probe=c20b87316b) | Jan 12, 2023 |
| Dell          | Latitude 3350               | [065c4a4a95](https://linux-hardware.org/?probe=065c4a4a95) | Jan 12, 2023 |
| TUXEDO        | Unknown                     | [ae60044fa6](https://linux-hardware.org/?probe=ae60044fa6) | Jan 12, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [58f2d0e1b4](https://linux-hardware.org/?probe=58f2d0e1b4) | Jan 12, 2023 |
| Dell          | Inspiron 1545               | [fbe5836f4f](https://linux-hardware.org/?probe=fbe5836f4f) | Jan 12, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [ee7b0c337b](https://linux-hardware.org/?probe=ee7b0c337b) | Jan 12, 2023 |
| Acer          | Aspire E5-471P              | [c50e807e64](https://linux-hardware.org/?probe=c50e807e64) | Jan 12, 2023 |
| Lenovo        | ThinkPad T60 8744HDG        | [10c4bcf564](https://linux-hardware.org/?probe=10c4bcf564) | Jan 12, 2023 |
| Google        | Link                        | [f73704d47a](https://linux-hardware.org/?probe=f73704d47a) | Jan 12, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [c3b6b8b400](https://linux-hardware.org/?probe=c3b6b8b400) | Jan 12, 2023 |
| Lenovo        | ThinkPad T530 2392AQU       | [0be364c65c](https://linux-hardware.org/?probe=0be364c65c) | Jan 12, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [a8d6ad51af](https://linux-hardware.org/?probe=a8d6ad51af) | Jan 12, 2023 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | [7a2cdcb0ab](https://linux-hardware.org/?probe=7a2cdcb0ab) | Jan 12, 2023 |
| ASUSTek       | X550LN                      | [791cd47247](https://linux-hardware.org/?probe=791cd47247) | Jan 12, 2023 |
| Lenovo        | G50-70 20351                | [239e9a9620](https://linux-hardware.org/?probe=239e9a9620) | Jan 12, 2023 |
| ASUSTek       | G53SX                       | [ef2d9747e2](https://linux-hardware.org/?probe=ef2d9747e2) | Jan 12, 2023 |
| HP            | ZBook 15 G3                 | [c44ad0b618](https://linux-hardware.org/?probe=c44ad0b618) | Jan 12, 2023 |
| HP            | Laptop 15-gw0xxx            | [d534567752](https://linux-hardware.org/?probe=d534567752) | Jan 12, 2023 |
| Dell          | Inspiron 5770               | [7435d85aca](https://linux-hardware.org/?probe=7435d85aca) | Jan 12, 2023 |
| HP            | Compaq 6530b                | [8ebd66e8e6](https://linux-hardware.org/?probe=8ebd66e8e6) | Jan 12, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [e607ba7fc4](https://linux-hardware.org/?probe=e607ba7fc4) | Jan 12, 2023 |
| Lenovo        | ThinkPad X230 2325AH7       | [c1080083c4](https://linux-hardware.org/?probe=c1080083c4) | Jan 12, 2023 |
| Standard      | Unknown                     | [b6f4b12847](https://linux-hardware.org/?probe=b6f4b12847) | Jan 12, 2023 |
| Gateway       | NV55C                       | [b8ae4adfdc](https://linux-hardware.org/?probe=b8ae4adfdc) | Jan 12, 2023 |
| Unknown       | Unknown                     | [5f6b66b79b](https://linux-hardware.org/?probe=5f6b66b79b) | Jan 12, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [907784afb2](https://linux-hardware.org/?probe=907784afb2) | Jan 12, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [ff12fe840d](https://linux-hardware.org/?probe=ff12fe840d) | Jan 12, 2023 |
| Acer          | Nitro AN515-54              | [9f56f94323](https://linux-hardware.org/?probe=9f56f94323) | Jan 12, 2023 |
| Acer          | Aspire V5-561G              | [1551c2b90c](https://linux-hardware.org/?probe=1551c2b90c) | Jan 12, 2023 |
| Lenovo        | Legion Y740S-15IMH 81YX     | [b61eb04be5](https://linux-hardware.org/?probe=b61eb04be5) | Jan 11, 2023 |
| ALLDOCUBE     | i1405C                      | [0713c94107](https://linux-hardware.org/?probe=0713c94107) | Jan 11, 2023 |
| HP            | ProBook 4535s               | [47cd489d8b](https://linux-hardware.org/?probe=47cd489d8b) | Jan 11, 2023 |
| Dell          | Inspiron 5558               | [5b5ff96ffd](https://linux-hardware.org/?probe=5b5ff96ffd) | Jan 11, 2023 |
| HP            | Pavilion dv9500             | [0f8c99e8d7](https://linux-hardware.org/?probe=0f8c99e8d7) | Jan 11, 2023 |
| Lenovo        | S20-30 20421                | [43bee9503c](https://linux-hardware.org/?probe=43bee9503c) | Jan 11, 2023 |
| Medion        | E6222                       | [e3b3da28fa](https://linux-hardware.org/?probe=e3b3da28fa) | Jan 11, 2023 |
| Acer          | Aspire E1-572               | [43c14a1e54](https://linux-hardware.org/?probe=43c14a1e54) | Jan 11, 2023 |
| HP            | Laptop 14-fq1xxx            | [1c46ef773f](https://linux-hardware.org/?probe=1c46ef773f) | Jan 11, 2023 |
| Lenovo        | G50-45 80E3                 | [80f84b2854](https://linux-hardware.org/?probe=80f84b2854) | Jan 11, 2023 |
| Lenovo        | ThinkPad T430 2349MPS       | [c04ba99a13](https://linux-hardware.org/?probe=c04ba99a13) | Jan 11, 2023 |
| Lenovo        | ThinkPad R61 8935AC7        | [4128f195f0](https://linux-hardware.org/?probe=4128f195f0) | Jan 11, 2023 |
| HP            | EliteBook 8460p             | [a941237bf3](https://linux-hardware.org/?probe=a941237bf3) | Jan 11, 2023 |
| HP            | Presario C700               | [3674a9a180](https://linux-hardware.org/?probe=3674a9a180) | Jan 11, 2023 |
| Samsung       | 270E5G/270E5U               | [0ddeecd2b8](https://linux-hardware.org/?probe=0ddeecd2b8) | Jan 11, 2023 |
| Lenovo        | ThinkPad W510 439123G       | [4fd1a4a217](https://linux-hardware.org/?probe=4fd1a4a217) | Jan 11, 2023 |
| HP            | ProBook 6450b               | [0ae783d261](https://linux-hardware.org/?probe=0ae783d261) | Jan 11, 2023 |
| Toshiba       | Satellite P50-C             | [1da161195b](https://linux-hardware.org/?probe=1da161195b) | Jan 11, 2023 |
| Eluktronic... | Prometheus XVII             | [9060298ec4](https://linux-hardware.org/?probe=9060298ec4) | Jan 11, 2023 |
| ASUSTek       | ROG Strix G713RC_G713RC     | [53656f6ceb](https://linux-hardware.org/?probe=53656f6ceb) | Jan 11, 2023 |
| Sony          | VPCEJ2S1E                   | [f387a3dcf6](https://linux-hardware.org/?probe=f387a3dcf6) | Jan 11, 2023 |
| HP            | EliteBook 840 G4            | [680b0adb7b](https://linux-hardware.org/?probe=680b0adb7b) | Jan 11, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [0eb269d3a7](https://linux-hardware.org/?probe=0eb269d3a7) | Jan 11, 2023 |
| Acer          | Nitro AN515-43              | [6488b3dc3c](https://linux-hardware.org/?probe=6488b3dc3c) | Jan 11, 2023 |
| Acer          | Aspire 5742G                | [07f15478a7](https://linux-hardware.org/?probe=07f15478a7) | Jan 11, 2023 |
| MSI           | GL75 9SE                    | [e3478b20bd](https://linux-hardware.org/?probe=e3478b20bd) | Jan 11, 2023 |
| HP            | Unknown                     | [604bea5ac6](https://linux-hardware.org/?probe=604bea5ac6) | Jan 11, 2023 |
| Razer         | Blade 17 (2022) - RZ09-0... | [a25c10f2dd](https://linux-hardware.org/?probe=a25c10f2dd) | Jan 11, 2023 |
| Fujitsu       | LIFEBOOK A512               | [4bb2de67c9](https://linux-hardware.org/?probe=4bb2de67c9) | Jan 11, 2023 |
| Toshiba       | Satellite C850-B561         | [562d6cde14](https://linux-hardware.org/?probe=562d6cde14) | Jan 11, 2023 |
| Toshiba       | Satellite Pro NB10-A-12Q    | [f0c82d2046](https://linux-hardware.org/?probe=f0c82d2046) | Jan 11, 2023 |
| Acer          | Extensa 2519                | [c044faaa05](https://linux-hardware.org/?probe=c044faaa05) | Jan 11, 2023 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [1ebf7a4a09](https://linux-hardware.org/?probe=1ebf7a4a09) | Jan 11, 2023 |
| Dell          | Inspiron 1545               | [20bc38b554](https://linux-hardware.org/?probe=20bc38b554) | Jan 11, 2023 |
| Sony          | VPCEH1AFX                   | [3f64681bc7](https://linux-hardware.org/?probe=3f64681bc7) | Jan 11, 2023 |
| HP            | EliteBook 840 G2            | [72a6b9a90b](https://linux-hardware.org/?probe=72a6b9a90b) | Jan 11, 2023 |
| Sony          | VPCEA23FB                   | [d6a7454695](https://linux-hardware.org/?probe=d6a7454695) | Jan 11, 2023 |
| Acer          | Aspire E1-571               | [77e844abaf](https://linux-hardware.org/?probe=77e844abaf) | Jan 11, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [4065e955cd](https://linux-hardware.org/?probe=4065e955cd) | Jan 11, 2023 |
| UMAX          | VisionBook 15Wg Plus        | [e4c19089b5](https://linux-hardware.org/?probe=e4c19089b5) | Jan 11, 2023 |
| Lenovo        | ThinkPad X240 20AM001RGE    | [f4aafcf7a9](https://linux-hardware.org/?probe=f4aafcf7a9) | Jan 11, 2023 |
| Compaq        | 420                         | [65070f85d5](https://linux-hardware.org/?probe=65070f85d5) | Jan 11, 2023 |
| Acer          | Nitro AN515-44              | [aacfe1b351](https://linux-hardware.org/?probe=aacfe1b351) | Jan 11, 2023 |
| Dell          | Latitude D630               | [64877fdf78](https://linux-hardware.org/?probe=64877fdf78) | Jan 11, 2023 |
| ASUSTek       | TUF Gaming FX505DU_TUF50... | [05a4b5d681](https://linux-hardware.org/?probe=05a4b5d681) | Jan 10, 2023 |
| Dell          | G5 5590                     | [846a462365](https://linux-hardware.org/?probe=846a462365) | Jan 10, 2023 |
| MSI           | Stealth GS77 12UE           | [3711622844](https://linux-hardware.org/?probe=3711622844) | Jan 10, 2023 |
| ASUSTek       | ZenBook Pro Duo UX582HM_... | [47d808cdc7](https://linux-hardware.org/?probe=47d808cdc7) | Jan 10, 2023 |
| Lenovo        | ThinkPad X270 20HN0015FR    | [e303c543ba](https://linux-hardware.org/?probe=e303c543ba) | Jan 10, 2023 |
| Sony          | VPCCW1S1E                   | [5cc5248e94](https://linux-hardware.org/?probe=5cc5248e94) | Jan 10, 2023 |
| Apple         | MacBookAir5,1               | [ce911686b3](https://linux-hardware.org/?probe=ce911686b3) | Jan 10, 2023 |
| Acer          | Aspire A515-41G             | [e5ef8ca744](https://linux-hardware.org/?probe=e5ef8ca744) | Jan 10, 2023 |
| System76      | Darter Pro                  | [ffaaf5c90e](https://linux-hardware.org/?probe=ffaaf5c90e) | Jan 10, 2023 |
| Dell          | XPS M1330                   | [e3d66114f6](https://linux-hardware.org/?probe=e3d66114f6) | Jan 10, 2023 |
| HP            | EliteBook 8460p             | [27ab381a1d](https://linux-hardware.org/?probe=27ab381a1d) | Jan 10, 2023 |
| Lenovo        | ThinkPad X201 3680AQ1       | [4a65277a98](https://linux-hardware.org/?probe=4a65277a98) | Jan 10, 2023 |
| ASUSTek       | TUF Gaming FX505GM_FX86F... | [5ab0bf0018](https://linux-hardware.org/?probe=5ab0bf0018) | Jan 10, 2023 |
| Acer          | TMP645-M                    | [8e0b2f5e90](https://linux-hardware.org/?probe=8e0b2f5e90) | Jan 10, 2023 |
| ASUSTek       | X550CC                      | [2aa757ef35](https://linux-hardware.org/?probe=2aa757ef35) | Jan 10, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [dfca68067c](https://linux-hardware.org/?probe=dfca68067c) | Jan 10, 2023 |
| Acer          | Aspire 5735                 | [27b63fd8b1](https://linux-hardware.org/?probe=27b63fd8b1) | Jan 10, 2023 |
| MSI           | Modern 15 A5M               | [18654d5f58](https://linux-hardware.org/?probe=18654d5f58) | Jan 10, 2023 |
| ASUSTek       | GL702VM                     | [31345092f4](https://linux-hardware.org/?probe=31345092f4) | Jan 10, 2023 |
| HP            | 255 G4                      | [1893637142](https://linux-hardware.org/?probe=1893637142) | Jan 10, 2023 |
| Dell          | Inspiron N5010              | [f5d1f04d89](https://linux-hardware.org/?probe=f5d1f04d89) | Jan 10, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [010a4fc9bd](https://linux-hardware.org/?probe=010a4fc9bd) | Jan 10, 2023 |
| Lenovo        | ThinkPad T440 20B7000LGE    | [e094c1d3f4](https://linux-hardware.org/?probe=e094c1d3f4) | Jan 10, 2023 |
| Lenovo        | B50-70 80EU                 | [e11621e300](https://linux-hardware.org/?probe=e11621e300) | Jan 10, 2023 |
| HP            | ProBook 645 G2              | [1298e3efb0](https://linux-hardware.org/?probe=1298e3efb0) | Jan 10, 2023 |
| Acer          | Aspire F5-573               | [56819b1d05](https://linux-hardware.org/?probe=56819b1d05) | Jan 10, 2023 |
| Acer          | Extensa 2540                | [6bddd00c3f](https://linux-hardware.org/?probe=6bddd00c3f) | Jan 10, 2023 |
| Acer          | Aspire E5-575G              | [21bfdfce4b](https://linux-hardware.org/?probe=21bfdfce4b) | Jan 10, 2023 |
| MSI           | Modern 14 B10RBSW           | [3dea4fbc97](https://linux-hardware.org/?probe=3dea4fbc97) | Jan 10, 2023 |
| ASUSTek       | K53SM                       | [f1ac679157](https://linux-hardware.org/?probe=f1ac679157) | Jan 10, 2023 |
| Acer          | Aspire E1-531G              | [2476cc24c1](https://linux-hardware.org/?probe=2476cc24c1) | Jan 10, 2023 |
| HP            | Unknown                     | [63d24f2719](https://linux-hardware.org/?probe=63d24f2719) | Jan 10, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [acab6ec02e](https://linux-hardware.org/?probe=acab6ec02e) | Jan 10, 2023 |
| HP            | Compaq 6730s                | [46c8c987e6](https://linux-hardware.org/?probe=46c8c987e6) | Jan 10, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [17dc10d7bb](https://linux-hardware.org/?probe=17dc10d7bb) | Jan 10, 2023 |
| Google        | Sand                        | [f539d17e9a](https://linux-hardware.org/?probe=f539d17e9a) | Jan 10, 2023 |
| Acer          | Aspire A315-56              | [b89e68d5ab](https://linux-hardware.org/?probe=b89e68d5ab) | Jan 10, 2023 |
| Dell          | Inspiron 5577               | [86cfa19622](https://linux-hardware.org/?probe=86cfa19622) | Jan 10, 2023 |
| Clevo         | W240HU/W250HUQ              | [b572e2679d](https://linux-hardware.org/?probe=b572e2679d) | Jan 10, 2023 |
| Lenovo        | ThinkPad L540 20AUS2MN00    | [b7ee1243ad](https://linux-hardware.org/?probe=b7ee1243ad) | Jan 10, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [6aa615094c](https://linux-hardware.org/?probe=6aa615094c) | Jan 10, 2023 |
| Acer          | Aspire A514-54              | [a786a0640f](https://linux-hardware.org/?probe=a786a0640f) | Jan 10, 2023 |
| Dell          | Latitude E4310              | [1cd2d3300a](https://linux-hardware.org/?probe=1cd2d3300a) | Jan 09, 2023 |
| Dell          | Inspiron 3442               | [f540a5f964](https://linux-hardware.org/?probe=f540a5f964) | Jan 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [2bbe617df6](https://linux-hardware.org/?probe=2bbe617df6) | Jan 09, 2023 |
| MSI           | GP60 2PE                    | [e1506ca6f6](https://linux-hardware.org/?probe=e1506ca6f6) | Jan 09, 2023 |
| Dell          | Precision 7540              | [77b35e556c](https://linux-hardware.org/?probe=77b35e556c) | Jan 09, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [7e32892067](https://linux-hardware.org/?probe=7e32892067) | Jan 09, 2023 |
| Lenovo        | ThinkPad E570 20H50048US    | [1184938f85](https://linux-hardware.org/?probe=1184938f85) | Jan 09, 2023 |
| ASUSTek       | K50IJ                       | [9d476dfade](https://linux-hardware.org/?probe=9d476dfade) | Jan 09, 2023 |
| Lenovo        | G480 20150                  | [31f01e01fe](https://linux-hardware.org/?probe=31f01e01fe) | Jan 09, 2023 |
| Dell          | System XPS L502X            | [7d053f0ab1](https://linux-hardware.org/?probe=7d053f0ab1) | Jan 09, 2023 |
| Dell          | Latitude 7490               | [0780580a38](https://linux-hardware.org/?probe=0780580a38) | Jan 09, 2023 |
| Lenovo        | ThinkPad T450 20BV000AUS    | [bd0dc145be](https://linux-hardware.org/?probe=bd0dc145be) | Jan 09, 2023 |
| ASUSTek       | X301A1                      | [c98ae98676](https://linux-hardware.org/?probe=c98ae98676) | Jan 09, 2023 |
| Acer          | Aspire E5-511               | [e16bac2828](https://linux-hardware.org/?probe=e16bac2828) | Jan 09, 2023 |
| Acer          | Aspire A315-41              | [6c7f37297d](https://linux-hardware.org/?probe=6c7f37297d) | Jan 09, 2023 |
| ASUSTek       | X75A1                       | [02ad2b36f1](https://linux-hardware.org/?probe=02ad2b36f1) | Jan 09, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [d6115e24c1](https://linux-hardware.org/?probe=d6115e24c1) | Jan 09, 2023 |
| Dell          | Latitude E5470              | [41c1a02ca6](https://linux-hardware.org/?probe=41c1a02ca6) | Jan 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [5663965a51](https://linux-hardware.org/?probe=5663965a51) | Jan 09, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [e86a06caea](https://linux-hardware.org/?probe=e86a06caea) | Jan 09, 2023 |
| Lenovo        | ThinkPad T430s 2356AF9      | [eca34fb600](https://linux-hardware.org/?probe=eca34fb600) | Jan 09, 2023 |
| ASUSTek       | K50IE                       | [4fdb15502c](https://linux-hardware.org/?probe=4fdb15502c) | Jan 09, 2023 |
| Star Labs     | Lite                        | [6614e226df](https://linux-hardware.org/?probe=6614e226df) | Jan 09, 2023 |
| Acer          | Aspire 7560                 | [58cd9d7ad2](https://linux-hardware.org/?probe=58cd9d7ad2) | Jan 09, 2023 |
| Lenovo        | ThinkPad A275 20KCS0FT02    | [fc35d7e62b](https://linux-hardware.org/?probe=fc35d7e62b) | Jan 09, 2023 |
| HP            | 255 G7 Notebook PC          | [532f3544a2](https://linux-hardware.org/?probe=532f3544a2) | Jan 09, 2023 |
| Acer          | Aspire 5755G                | [f6ecd5ed6e](https://linux-hardware.org/?probe=f6ecd5ed6e) | Jan 09, 2023 |
| Dell          | XPS L521X                   | [2930493243](https://linux-hardware.org/?probe=2930493243) | Jan 09, 2023 |
| Lenovo        | ThinkPad R61 7743W6L        | [f5df0d79bf](https://linux-hardware.org/?probe=f5df0d79bf) | Jan 09, 2023 |
| Lenovo        | IdeaPad Z580                | [6cb922bbdf](https://linux-hardware.org/?probe=6cb922bbdf) | Jan 09, 2023 |
| Lenovo        | ThinkPad X201 3626D15       | [3d615a1b12](https://linux-hardware.org/?probe=3d615a1b12) | Jan 09, 2023 |
| System76      | Darter Pro                  | [a6703dafe6](https://linux-hardware.org/?probe=a6703dafe6) | Jan 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [606c8dfd43](https://linux-hardware.org/?probe=606c8dfd43) | Jan 09, 2023 |
| Dell          | Studio 1558                 | [0e01a19694](https://linux-hardware.org/?probe=0e01a19694) | Jan 09, 2023 |
| HP            | Notebook                    | [c4cc7fb9f6](https://linux-hardware.org/?probe=c4cc7fb9f6) | Jan 09, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [ebcaf16c78](https://linux-hardware.org/?probe=ebcaf16c78) | Jan 09, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [c8572f304a](https://linux-hardware.org/?probe=c8572f304a) | Jan 09, 2023 |
| ASUSTek       | K95VB                       | [f42992ef2a](https://linux-hardware.org/?probe=f42992ef2a) | Jan 09, 2023 |
| Schenker      | WORK15 17 SWO15 17L19       | [2294afc503](https://linux-hardware.org/?probe=2294afc503) | Jan 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a712e2524b](https://linux-hardware.org/?probe=a712e2524b) | Jan 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3444G... | [29331861b5](https://linux-hardware.org/?probe=29331861b5) | Jan 09, 2023 |
| Lenovo        | IdeaPadFlex 10 20324        | [1d0cd9b040](https://linux-hardware.org/?probe=1d0cd9b040) | Jan 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [7ef1600aaf](https://linux-hardware.org/?probe=7ef1600aaf) | Jan 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ee26fd6a5c](https://linux-hardware.org/?probe=ee26fd6a5c) | Jan 09, 2023 |
| Acer          | Aspire A314-22              | [5729420a54](https://linux-hardware.org/?probe=5729420a54) | Jan 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [364cc4a06d](https://linux-hardware.org/?probe=364cc4a06d) | Jan 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [ab227bc376](https://linux-hardware.org/?probe=ab227bc376) | Jan 09, 2023 |
| Itautec       | Infoway w7535               | [36f64a3242](https://linux-hardware.org/?probe=36f64a3242) | Jan 09, 2023 |
| ASUSTek       | X550ZA                      | [272bff51c5](https://linux-hardware.org/?probe=272bff51c5) | Jan 09, 2023 |
| Acer          | Aspire 5750                 | [54ad46d626](https://linux-hardware.org/?probe=54ad46d626) | Jan 09, 2023 |
| HP            | OMEN by Laptop              | [84aa790d17](https://linux-hardware.org/?probe=84aa790d17) | Jan 09, 2023 |
| MSI           | Katana GF76 11UD            | [2ab31d8124](https://linux-hardware.org/?probe=2ab31d8124) | Jan 08, 2023 |
| Dell          | Latitude E6500              | [eefe535778](https://linux-hardware.org/?probe=eefe535778) | Jan 08, 2023 |
| Dell          | Latitude 5480               | [4fe0c25059](https://linux-hardware.org/?probe=4fe0c25059) | Jan 08, 2023 |
| Lenovo        | B50-30 80ES                 | [ad63e7abaf](https://linux-hardware.org/?probe=ad63e7abaf) | Jan 08, 2023 |
| HP            | Laptop 15s-eq2xxx           | [2cb8833274](https://linux-hardware.org/?probe=2cb8833274) | Jan 08, 2023 |
| Samsung       | R780/R778                   | [e26d6dd084](https://linux-hardware.org/?probe=e26d6dd084) | Jan 08, 2023 |
| ASUSTek       | GL753VE                     | [7e0d372f98](https://linux-hardware.org/?probe=7e0d372f98) | Jan 08, 2023 |
| HP            | Pavilion 15                 | [2937882035](https://linux-hardware.org/?probe=2937882035) | Jan 08, 2023 |
| MSI           | GP70 2PE                    | [697974aa68](https://linux-hardware.org/?probe=697974aa68) | Jan 08, 2023 |
| Acer          | Aspire ES1-311              | [6f857b7e85](https://linux-hardware.org/?probe=6f857b7e85) | Jan 08, 2023 |
| Dell          | Inspiron 5593               | [7ada807633](https://linux-hardware.org/?probe=7ada807633) | Jan 08, 2023 |
| Dell          | Inspiron 3537               | [234580243d](https://linux-hardware.org/?probe=234580243d) | Jan 08, 2023 |
| Lenovo        | ThinkPad T410 2516F9U       | [02a02d5713](https://linux-hardware.org/?probe=02a02d5713) | Jan 08, 2023 |
| Apple         | MacBook5,1                  | [55008626da](https://linux-hardware.org/?probe=55008626da) | Jan 08, 2023 |
| HP            | Compaq 6730b                | [e90b19a605](https://linux-hardware.org/?probe=e90b19a605) | Jan 08, 2023 |
| Lenovo        | ThinkPad W500 4061WFA       | [4850dba7c8](https://linux-hardware.org/?probe=4850dba7c8) | Jan 08, 2023 |
| Lenovo        | G51-35 80M8                 | [fe19098e1d](https://linux-hardware.org/?probe=fe19098e1d) | Jan 08, 2023 |
| Dell          | Latitude 7280               | [931dcfb8be](https://linux-hardware.org/?probe=931dcfb8be) | Jan 08, 2023 |
| Toshiba       | Satellite Pro L450D         | [a2a9c2e730](https://linux-hardware.org/?probe=a2a9c2e730) | Jan 08, 2023 |
| Dell          | Latitude 3490               | [7cf81f6b69](https://linux-hardware.org/?probe=7cf81f6b69) | Jan 08, 2023 |
| Apple         | MacBook6,1                  | [1f38721115](https://linux-hardware.org/?probe=1f38721115) | Jan 08, 2023 |
| Itautec       | Infoway w7535               | [6b8430c407](https://linux-hardware.org/?probe=6b8430c407) | Jan 08, 2023 |
| Acer          | TravelMate P614-51-G2       | [0d0c035342](https://linux-hardware.org/?probe=0d0c035342) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [ac6e888a8c](https://linux-hardware.org/?probe=ac6e888a8c) | Jan 08, 2023 |
| Lenovo        | G505 20240                  | [e8611b7b9b](https://linux-hardware.org/?probe=e8611b7b9b) | Jan 08, 2023 |
| Toshiba       | Satellite L775-18J          | [556a819738](https://linux-hardware.org/?probe=556a819738) | Jan 08, 2023 |
| Dell          | Latitude E7450              | [635ef7be4a](https://linux-hardware.org/?probe=635ef7be4a) | Jan 08, 2023 |
| Dell          | Inspiron 3793               | [67be2bc16f](https://linux-hardware.org/?probe=67be2bc16f) | Jan 08, 2023 |
| Gigabyte      | GB-BKi3A-7100               | [8263d65b20](https://linux-hardware.org/?probe=8263d65b20) | Jan 08, 2023 |
| Gateway       | MX8716B                     | [b8b9890719](https://linux-hardware.org/?probe=b8b9890719) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [d32518b04e](https://linux-hardware.org/?probe=d32518b04e) | Jan 08, 2023 |
| HP            | 655                         | [4c7544d7ad](https://linux-hardware.org/?probe=4c7544d7ad) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [5936a203cc](https://linux-hardware.org/?probe=5936a203cc) | Jan 08, 2023 |
| Dell          | Inspiron N4030              | [efaaf759cb](https://linux-hardware.org/?probe=efaaf759cb) | Jan 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d7b3bed98d](https://linux-hardware.org/?probe=d7b3bed98d) | Jan 08, 2023 |
| Sony          | VGN-Z16GN_B                 | [63bb6c7c43](https://linux-hardware.org/?probe=63bb6c7c43) | Jan 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4334ec8d00](https://linux-hardware.org/?probe=4334ec8d00) | Jan 08, 2023 |
| ODM           | MS-16K2                     | [f9a7d267e5](https://linux-hardware.org/?probe=f9a7d267e5) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [2e22cc1bb2](https://linux-hardware.org/?probe=2e22cc1bb2) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [e94cd234ee](https://linux-hardware.org/?probe=e94cd234ee) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [333358164d](https://linux-hardware.org/?probe=333358164d) | Jan 08, 2023 |
| Dell          | Precision M2800             | [3eaf20227d](https://linux-hardware.org/?probe=3eaf20227d) | Jan 08, 2023 |
| Dell          | Latitude E6400              | [70bce3a55c](https://linux-hardware.org/?probe=70bce3a55c) | Jan 08, 2023 |
| Toshiba       | dynabook T653/46JR          | [8fe8187a9e](https://linux-hardware.org/?probe=8fe8187a9e) | Jan 08, 2023 |
| Lenovo        | IdeaPad 300S-11IBR 80KU     | [6335e974a1](https://linux-hardware.org/?probe=6335e974a1) | Jan 08, 2023 |
| Dell          | Latitude E6510              | [e56f9529d6](https://linux-hardware.org/?probe=e56f9529d6) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [3c19dc43b2](https://linux-hardware.org/?probe=3c19dc43b2) | Jan 08, 2023 |
| HP            | EliteBook 8540p             | [64b63632cc](https://linux-hardware.org/?probe=64b63632cc) | Jan 08, 2023 |
| Dell          | Inspiron 3505               | [4098b3a322](https://linux-hardware.org/?probe=4098b3a322) | Jan 08, 2023 |
| HP            | Notebook                    | [1174de12fc](https://linux-hardware.org/?probe=1174de12fc) | Jan 08, 2023 |
| Dell          | XPS 9320                    | [55be119900](https://linux-hardware.org/?probe=55be119900) | Jan 08, 2023 |
| Dell          | Vostro 1400                 | [557ff8af74](https://linux-hardware.org/?probe=557ff8af74) | Jan 08, 2023 |
| Dell          | Latitude E6400              | [9f15bde3f6](https://linux-hardware.org/?probe=9f15bde3f6) | Jan 08, 2023 |
| Dell          | Latitude E5440              | [91bedeb5e1](https://linux-hardware.org/?probe=91bedeb5e1) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [50d2637c41](https://linux-hardware.org/?probe=50d2637c41) | Jan 07, 2023 |
| Dell          | Latitude 5290               | [1cd20e22fc](https://linux-hardware.org/?probe=1cd20e22fc) | Jan 07, 2023 |
| Gateway       | NE570                       | [3f65734a89](https://linux-hardware.org/?probe=3f65734a89) | Jan 07, 2023 |
| Cepter        | N530-01                     | [2b5d455bfd](https://linux-hardware.org/?probe=2b5d455bfd) | Jan 07, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [8056078760](https://linux-hardware.org/?probe=8056078760) | Jan 07, 2023 |
| Dell          | Inspiron N4010              | [5f1d6f0533](https://linux-hardware.org/?probe=5f1d6f0533) | Jan 07, 2023 |
| Notebook      | W9x0LU                      | [a81dd09b0c](https://linux-hardware.org/?probe=a81dd09b0c) | Jan 07, 2023 |
| HP            | 15 TS Notebook PC           | [5c4e966fda](https://linux-hardware.org/?probe=5c4e966fda) | Jan 07, 2023 |
| Medion        | Defender E15                | [fe5335c438](https://linux-hardware.org/?probe=fe5335c438) | Jan 07, 2023 |
| Acer          | Aspire ES1-572              | [dbbd130a08](https://linux-hardware.org/?probe=dbbd130a08) | Jan 07, 2023 |
| HP            | Pavilion dv4                | [5caee4abe0](https://linux-hardware.org/?probe=5caee4abe0) | Jan 07, 2023 |
| HP            | Laptop 15-db0xxx            | [ff51bb2dd9](https://linux-hardware.org/?probe=ff51bb2dd9) | Jan 07, 2023 |
| Lenovo        | ThinkPad T430 2349E56       | [ff2639c47b](https://linux-hardware.org/?probe=ff2639c47b) | Jan 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [f33ea77f0b](https://linux-hardware.org/?probe=f33ea77f0b) | Jan 07, 2023 |
| Dell          | Inspiron 15-3567            | [e9dadf5a23](https://linux-hardware.org/?probe=e9dadf5a23) | Jan 07, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1EQ0... | [45fa41817e](https://linux-hardware.org/?probe=45fa41817e) | Jan 07, 2023 |
| Dell          | Latitude E6530              | [d2e700fe98](https://linux-hardware.org/?probe=d2e700fe98) | Jan 07, 2023 |
| HP            | Laptop 14-dk1xxx            | [d94c2ed84e](https://linux-hardware.org/?probe=d94c2ed84e) | Jan 07, 2023 |
| HP            | 250 G7 Notebook PC          | [96625b7aa9](https://linux-hardware.org/?probe=96625b7aa9) | Jan 07, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [0e19bf61cf](https://linux-hardware.org/?probe=0e19bf61cf) | Jan 07, 2023 |
| Apple         | MacBookAir7,2               | [ef45fa4056](https://linux-hardware.org/?probe=ef45fa4056) | Jan 07, 2023 |
| ASUSTek       | S500CA                      | [d742870a51](https://linux-hardware.org/?probe=d742870a51) | Jan 07, 2023 |
| ASUSTek       | K53U                        | [46610b735e](https://linux-hardware.org/?probe=46610b735e) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [90dea18a86](https://linux-hardware.org/?probe=90dea18a86) | Jan 07, 2023 |
| HP            | ProBook 5330m               | [37416931cd](https://linux-hardware.org/?probe=37416931cd) | Jan 07, 2023 |
| Acer          | Aspire V5-573G              | [a6aea9e1f9](https://linux-hardware.org/?probe=a6aea9e1f9) | Jan 07, 2023 |
| Google        | Swanky                      | [234d5823f7](https://linux-hardware.org/?probe=234d5823f7) | Jan 07, 2023 |
| HP            | 255 G5 Notebook PC          | [69969b5a27](https://linux-hardware.org/?probe=69969b5a27) | Jan 07, 2023 |
| Acer          | Aspire E5-772G              | [c840cf9ca5](https://linux-hardware.org/?probe=c840cf9ca5) | Jan 07, 2023 |
| HP            | EliteBook 6930p             | [9a59c21db0](https://linux-hardware.org/?probe=9a59c21db0) | Jan 07, 2023 |
| HUAWEI        | BOHB-WAX9                   | [9c9e1b06f9](https://linux-hardware.org/?probe=9c9e1b06f9) | Jan 07, 2023 |
| Lenovo        | G505 20240                  | [a2910be7b2](https://linux-hardware.org/?probe=a2910be7b2) | Jan 07, 2023 |
| HP            | Compaq CQ58                 | [fae1531801](https://linux-hardware.org/?probe=fae1531801) | Jan 07, 2023 |
| Dell          | Inspiron 15-3567            | [173b427c35](https://linux-hardware.org/?probe=173b427c35) | Jan 07, 2023 |
| Notebook      | P17SM                       | [1822a60f02](https://linux-hardware.org/?probe=1822a60f02) | Jan 07, 2023 |
| Intel         | Jasper Lake Client Platf... | [24fef9e401](https://linux-hardware.org/?probe=24fef9e401) | Jan 07, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [93fd2967ab](https://linux-hardware.org/?probe=93fd2967ab) | Jan 07, 2023 |
| Toshiba       | Satellite Pro C850-10N      | [8f013ca042](https://linux-hardware.org/?probe=8f013ca042) | Jan 07, 2023 |
| Lenovo        | 3000 G530 444622G           | [7f1a67e904](https://linux-hardware.org/?probe=7f1a67e904) | Jan 07, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [782467ee8c](https://linux-hardware.org/?probe=782467ee8c) | Jan 07, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [a56af08eb5](https://linux-hardware.org/?probe=a56af08eb5) | Jan 07, 2023 |
| Acer          | Aspire A315-58              | [ac9e3aa480](https://linux-hardware.org/?probe=ac9e3aa480) | Jan 07, 2023 |
| Acer          | Aspire 7741                 | [d0e4567b4a](https://linux-hardware.org/?probe=d0e4567b4a) | Jan 07, 2023 |
| HP            | 255 G4                      | [9c0a1f78a9](https://linux-hardware.org/?probe=9c0a1f78a9) | Jan 07, 2023 |
| HP            | 2000                        | [0f801f2309](https://linux-hardware.org/?probe=0f801f2309) | Jan 07, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [1239be31f9](https://linux-hardware.org/?probe=1239be31f9) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b235be23a9](https://linux-hardware.org/?probe=b235be23a9) | Jan 07, 2023 |
| HP            | Laptop 15-bw0xx             | [36c97306ae](https://linux-hardware.org/?probe=36c97306ae) | Jan 07, 2023 |
| Dell          | Latitude E6230              | [7a7cd04af0](https://linux-hardware.org/?probe=7a7cd04af0) | Jan 07, 2023 |
| Lenovo        | G500 20236                  | [62646e885a](https://linux-hardware.org/?probe=62646e885a) | Jan 07, 2023 |
| Dell          | XPS 15 9570                 | [8032d8e1be](https://linux-hardware.org/?probe=8032d8e1be) | Jan 07, 2023 |
| Lenovo        | V15-IGL 82C3                | [3bc9e3b318](https://linux-hardware.org/?probe=3bc9e3b318) | Jan 07, 2023 |
| Acer          | Aspire A315-21G             | [cc98c43ea0](https://linux-hardware.org/?probe=cc98c43ea0) | Jan 07, 2023 |
| Acer          | Nitro AN515-55              | [800f20e309](https://linux-hardware.org/?probe=800f20e309) | Jan 07, 2023 |
| Lenovo        | S145-15API 81UT             | [fafc9e3fb7](https://linux-hardware.org/?probe=fafc9e3fb7) | Jan 07, 2023 |
| Acer          | Aspire V3-571G              | [67103caf92](https://linux-hardware.org/?probe=67103caf92) | Jan 07, 2023 |
| HP            | Laptop 17-cp0xxx            | [467b323e3a](https://linux-hardware.org/?probe=467b323e3a) | Jan 07, 2023 |
| Toshiba       | Satellite L755              | [a250fb6156](https://linux-hardware.org/?probe=a250fb6156) | Jan 07, 2023 |
| MicroByte     | ezbook                      | [f0db1fef46](https://linux-hardware.org/?probe=f0db1fef46) | Jan 07, 2023 |
| HP            | Laptop 14-dk0xxx            | [4517d8fb6a](https://linux-hardware.org/?probe=4517d8fb6a) | Jan 07, 2023 |
| HP            | EliteBook 2740p             | [db87df4376](https://linux-hardware.org/?probe=db87df4376) | Jan 07, 2023 |
| HP            | 250 G3                      | [227b44bf7c](https://linux-hardware.org/?probe=227b44bf7c) | Jan 06, 2023 |
| HP            | Laptop 15-db0xxx            | [0232b39536](https://linux-hardware.org/?probe=0232b39536) | Jan 06, 2023 |
| eMachines     | E725                        | [0655d63f70](https://linux-hardware.org/?probe=0655d63f70) | Jan 06, 2023 |
| ASUSTek       | K52JT                       | [77abcf7aee](https://linux-hardware.org/?probe=77abcf7aee) | Jan 05, 2023 |
| ASUSTek       | K55VM                       | [d4d53ed49f](https://linux-hardware.org/?probe=d4d53ed49f) | Jan 04, 2023 |
| HP            | Pavilion g6                 | [6cae064dc5](https://linux-hardware.org/?probe=6cae064dc5) | Jan 04, 2023 |
| HP            | ProBook 470 G2              | [1f62ff6417](https://linux-hardware.org/?probe=1f62ff6417) | Jan 04, 2023 |
| HP            | Compaq 15                   | [c282ede7c5](https://linux-hardware.org/?probe=c282ede7c5) | Jan 04, 2023 |
| HP            | EliteBook 725 G3            | [174e0c5f05](https://linux-hardware.org/?probe=174e0c5f05) | Jan 04, 2023 |
| Dell          | Latitude D520               | [7f05ddf105](https://linux-hardware.org/?probe=7f05ddf105) | Jan 04, 2023 |
| Dell          | Latitude 7490               | [7e445638b6](https://linux-hardware.org/?probe=7e445638b6) | Jan 04, 2023 |
| Sony          | VJF153                      | [f3643923cc](https://linux-hardware.org/?probe=f3643923cc) | Jan 04, 2023 |
| ASUSTek       | K501UW                      | [22218917b9](https://linux-hardware.org/?probe=22218917b9) | Jan 04, 2023 |
| Lenovo        | ThinkPad T500 2089W3A       | [77d8aae87c](https://linux-hardware.org/?probe=77d8aae87c) | Jan 03, 2023 |
| Acer          | Nitro AN515-55              | [c5bc3a8eae](https://linux-hardware.org/?probe=c5bc3a8eae) | Jan 03, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [a73ca839a1](https://linux-hardware.org/?probe=a73ca839a1) | Jan 03, 2023 |
| Positivo      | Z100                        | [58b7c4d1ff](https://linux-hardware.org/?probe=58b7c4d1ff) | Jan 02, 2023 |
| Acer          | Aspire E1-571               | [eb3f1a0f5f](https://linux-hardware.org/?probe=eb3f1a0f5f) | Jan 02, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [287840d797](https://linux-hardware.org/?probe=287840d797) | Jan 02, 2023 |
| Toshiba       | dynabook T653/46JR          | [cac689a705](https://linux-hardware.org/?probe=cac689a705) | Jan 02, 2023 |
| Acer          | Aspire 5732Z                | [86b79bce9e](https://linux-hardware.org/?probe=86b79bce9e) | Jan 01, 2023 |
| Dell          | System Inspiron N411Z       | [21f279751c](https://linux-hardware.org/?probe=21f279751c) | Jan 01, 2023 |
| Medion        | E14412                      | [0e49564d0e](https://linux-hardware.org/?probe=0e49564d0e) | Jan 01, 2023 |
| Packard Be... | EasyNote TM97               | [fad44d67ab](https://linux-hardware.org/?probe=fad44d67ab) | Jan 01, 2023 |
| ASUSTek       | S551LN                      | [12629ba25d](https://linux-hardware.org/?probe=12629ba25d) | Jan 01, 2023 |
| HP            | 1000                        | [5634ff72b1](https://linux-hardware.org/?probe=5634ff72b1) | Jan 01, 2023 |
| Acer          | Aspire A114-33              | [bba53b0159](https://linux-hardware.org/?probe=bba53b0159) | Jan 01, 2023 |
| Toshiba       | Satellite A305D             | [b85a377462](https://linux-hardware.org/?probe=b85a377462) | Dec 31, 2022 |
| Dynabook      | Satellite Pro C40-G         | [e7555a4df8](https://linux-hardware.org/?probe=e7555a4df8) | Dec 31, 2022 |
| Lenovo        | ThinkPad T410 2537BF9       | [f83ed1dd39](https://linux-hardware.org/?probe=f83ed1dd39) | Dec 30, 2022 |
| ASUSTek       | TP501UA                     | [1f2aaf8804](https://linux-hardware.org/?probe=1f2aaf8804) | Dec 30, 2022 |
| Lenovo        | ThinkPad X250 20CLS2D404    | [68afcc38f2](https://linux-hardware.org/?probe=68afcc38f2) | Dec 30, 2022 |
| ASUSTek       | K55VD                       | [e4c90250df](https://linux-hardware.org/?probe=e4c90250df) | Dec 30, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [7a685e175c](https://linux-hardware.org/?probe=7a685e175c) | Dec 30, 2022 |
| ASUSTek       | X555UJ                      | [f4ba8643aa](https://linux-hardware.org/?probe=f4ba8643aa) | Dec 30, 2022 |
| ASUSTek       | X556UQK                     | [42a9dc760d](https://linux-hardware.org/?probe=42a9dc760d) | Dec 30, 2022 |
| Medion        | Akoya E6416                 | [ddd9ba1ffc](https://linux-hardware.org/?probe=ddd9ba1ffc) | Dec 29, 2022 |
| Acer          | Nitro AN515-57              | [b0bfa9530a](https://linux-hardware.org/?probe=b0bfa9530a) | Dec 29, 2022 |
| Toshiba       | dynabook T653/46JR          | [a1f59f6ff9](https://linux-hardware.org/?probe=a1f59f6ff9) | Dec 29, 2022 |
| ASUSTek       | G1                          | [1f8e426f96](https://linux-hardware.org/?probe=1f8e426f96) | Dec 29, 2022 |
| Lenovo        | ThinkPad T500 2089W3A       | [401f529e18](https://linux-hardware.org/?probe=401f529e18) | Dec 29, 2022 |
| HP            | Notebook                    | [91bc85bf6e](https://linux-hardware.org/?probe=91bc85bf6e) | Dec 29, 2022 |
| Samsung       | NB30/N146                   | [7f9b976789](https://linux-hardware.org/?probe=7f9b976789) | Dec 29, 2022 |
| Apple         | MacBookAir7,2               | [0ad2bdf744](https://linux-hardware.org/?probe=0ad2bdf744) | Dec 29, 2022 |
| Fujitsu       | LIFEBOOK P702               | [4734f4370b](https://linux-hardware.org/?probe=4734f4370b) | Dec 28, 2022 |
| Lenovo        | V560                        | [f937de4c61](https://linux-hardware.org/?probe=f937de4c61) | Dec 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1ff4c4bf09](https://linux-hardware.org/?probe=1ff4c4bf09) | Dec 28, 2022 |
| HP            | Compaq Presario CQ60        | [92ece593f5](https://linux-hardware.org/?probe=92ece593f5) | Dec 28, 2022 |
| HP            | EliteBook 820 G2            | [bd56ec4f01](https://linux-hardware.org/?probe=bd56ec4f01) | Dec 28, 2022 |
| Google        | Gnawty                      | [98902e9806](https://linux-hardware.org/?probe=98902e9806) | Dec 28, 2022 |
| Acer          | Aspire E5-573G              | [6e1255aa44](https://linux-hardware.org/?probe=6e1255aa44) | Dec 28, 2022 |
| Positivo      | Hendrix                     | [55aa2f92d7](https://linux-hardware.org/?probe=55aa2f92d7) | Dec 27, 2022 |
| Dell          | Latitude 7480               | [45b0f992f6](https://linux-hardware.org/?probe=45b0f992f6) | Dec 27, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [7a3513a2e1](https://linux-hardware.org/?probe=7a3513a2e1) | Dec 27, 2022 |
| Acer          | Nitro AN515-44              | [58b02cceb0](https://linux-hardware.org/?probe=58b02cceb0) | Dec 27, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [9e6b5e5ebf](https://linux-hardware.org/?probe=9e6b5e5ebf) | Dec 27, 2022 |
| Acer          | Nitro AN515-57              | [8ecb7e11b3](https://linux-hardware.org/?probe=8ecb7e11b3) | Dec 26, 2022 |
| Samsung       | 270E5G/270E5U               | [705baed85a](https://linux-hardware.org/?probe=705baed85a) | Dec 26, 2022 |
| MSI           | GS76 Stealth 11UG           | [10e22b317f](https://linux-hardware.org/?probe=10e22b317f) | Dec 26, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [6703f01cfc](https://linux-hardware.org/?probe=6703f01cfc) | Dec 26, 2022 |
| HP            | EliteBook 820 G1            | [6a2c20cb74](https://linux-hardware.org/?probe=6a2c20cb74) | Dec 26, 2022 |
| Toshiba       | Satellite L500              | [08b4f83030](https://linux-hardware.org/?probe=08b4f83030) | Dec 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34604... | [dfb555f802](https://linux-hardware.org/?probe=dfb555f802) | Dec 26, 2022 |
| Apple         | MacBookAir7,2               | [9d48f30feb](https://linux-hardware.org/?probe=9d48f30feb) | Dec 25, 2022 |
| Acer          | Aspire A315-53              | [e012bb5bc1](https://linux-hardware.org/?probe=e012bb5bc1) | Dec 25, 2022 |
| Gigabyte      | AERO 17 XD                  | [c45ec6b46d](https://linux-hardware.org/?probe=c45ec6b46d) | Dec 25, 2022 |
| ASUSTek       | M51Tr                       | [dffa412a98](https://linux-hardware.org/?probe=dffa412a98) | Dec 25, 2022 |
| Dell          | G7 7790                     | [da767d5fd4](https://linux-hardware.org/?probe=da767d5fd4) | Dec 24, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [8c835888d6](https://linux-hardware.org/?probe=8c835888d6) | Dec 24, 2022 |
| ASUSTek       | UX31E                       | [08a1ad1c63](https://linux-hardware.org/?probe=08a1ad1c63) | Dec 24, 2022 |
| Acer          | Aspire A315-21G             | [435933801a](https://linux-hardware.org/?probe=435933801a) | Dec 24, 2022 |
| Toshiba       | Satellite C55-A             | [02a3f1cf18](https://linux-hardware.org/?probe=02a3f1cf18) | Dec 24, 2022 |
| Dell          | XPS L322X                   | [c127721464](https://linux-hardware.org/?probe=c127721464) | Dec 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [cf4ba78c7d](https://linux-hardware.org/?probe=cf4ba78c7d) | Dec 24, 2022 |
| Acer          | Aspire VX5-591G             | [f2e0369ba1](https://linux-hardware.org/?probe=f2e0369ba1) | Dec 24, 2022 |
| Positivo      | Mobile                      | [6031910e64](https://linux-hardware.org/?probe=6031910e64) | Dec 24, 2022 |
| Lenovo        | ThinkPad SL 2746N8G         | [f540a3a892](https://linux-hardware.org/?probe=f540a3a892) | Dec 23, 2022 |
| Positivo      | H14BT58                     | [9914219613](https://linux-hardware.org/?probe=9914219613) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [beb602dcf6](https://linux-hardware.org/?probe=beb602dcf6) | Dec 23, 2022 |
| ASUSTek       | K53SC                       | [5105f25e5e](https://linux-hardware.org/?probe=5105f25e5e) | Dec 23, 2022 |
| Acer          | Aspire VX5-591G             | [7defe87998](https://linux-hardware.org/?probe=7defe87998) | Dec 23, 2022 |
| Apple         | MacBookAir7,2               | [00e62a7231](https://linux-hardware.org/?probe=00e62a7231) | Dec 23, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [791ace450e](https://linux-hardware.org/?probe=791ace450e) | Dec 23, 2022 |
| ASUSTek       | M51Vr                       | [ffc48a52ea](https://linux-hardware.org/?probe=ffc48a52ea) | Dec 22, 2022 |
| Dell          | Latitude 5280               | [59002e923b](https://linux-hardware.org/?probe=59002e923b) | Dec 22, 2022 |
| HP            | Pavilion dv9000 (RR329EA... | [6fc7281f2f](https://linux-hardware.org/?probe=6fc7281f2f) | Dec 22, 2022 |
| ASUSTek       | 1015BXO                     | [7cce9a65ec](https://linux-hardware.org/?probe=7cce9a65ec) | Dec 22, 2022 |
| Toshiba       | dynabook T653/46JR          | [1f10cd2a64](https://linux-hardware.org/?probe=1f10cd2a64) | Dec 22, 2022 |
| HP            | Pavilion 11 x360 PC         | [1397ed80b3](https://linux-hardware.org/?probe=1397ed80b3) | Dec 21, 2022 |
| Toshiba       | Satellite C55-B             | [8f81c02bbf](https://linux-hardware.org/?probe=8f81c02bbf) | Dec 21, 2022 |
| Samsung       | R540/R580/R780/SA41/E452... | [044928d818](https://linux-hardware.org/?probe=044928d818) | Dec 21, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [06d78a17c1](https://linux-hardware.org/?probe=06d78a17c1) | Dec 21, 2022 |
| Acer          | Aspire 5336                 | [9724b5d705](https://linux-hardware.org/?probe=9724b5d705) | Dec 20, 2022 |
| RM Educati... | RM                          | [758b521362](https://linux-hardware.org/?probe=758b521362) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [7c07fab7e4](https://linux-hardware.org/?probe=7c07fab7e4) | Dec 20, 2022 |
| Lenovo        | ThinkPad W510 4318CTO       | [215feb2d5e](https://linux-hardware.org/?probe=215feb2d5e) | Dec 20, 2022 |
| MSI           | GE62 6QD                    | [20d959e778](https://linux-hardware.org/?probe=20d959e778) | Dec 19, 2022 |
| LG Electro... | 17Z90P-G.AA56F              | [fa43417151](https://linux-hardware.org/?probe=fa43417151) | Dec 19, 2022 |
| Toshiba       | EQUIUM A300D                | [ffde5ccef4](https://linux-hardware.org/?probe=ffde5ccef4) | Dec 19, 2022 |
| ASUSTek       | S551LN                      | [df4a754b5d](https://linux-hardware.org/?probe=df4a754b5d) | Dec 19, 2022 |
| ASUSTek       | X555LD                      | [d1d5c6a19e](https://linux-hardware.org/?probe=d1d5c6a19e) | Dec 19, 2022 |
| ASUSTek       | UX31E                       | [4f41f354cd](https://linux-hardware.org/?probe=4f41f354cd) | Dec 18, 2022 |
| ASUSTek       | N551JM                      | [e02ba85a63](https://linux-hardware.org/?probe=e02ba85a63) | Dec 18, 2022 |
| Acer          | Aspire ES1-531              | [28dc03a1bc](https://linux-hardware.org/?probe=28dc03a1bc) | Dec 18, 2022 |
| Toshiba       | dynabook T653/46JR          | [5a05dc8c43](https://linux-hardware.org/?probe=5a05dc8c43) | Dec 17, 2022 |
| Dell          | Latitude E6330              | [ca6551bf8e](https://linux-hardware.org/?probe=ca6551bf8e) | Dec 17, 2022 |
| Notebook      | W65_67SZ                    | [770c00f7d9](https://linux-hardware.org/?probe=770c00f7d9) | Dec 17, 2022 |
| Lenovo        | ThinkPad X200s 7466A17      | [1831439f56](https://linux-hardware.org/?probe=1831439f56) | Dec 16, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [0d7a54bc21](https://linux-hardware.org/?probe=0d7a54bc21) | Dec 16, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [ffa7e28596](https://linux-hardware.org/?probe=ffa7e28596) | Dec 16, 2022 |
| Lenovo        | Yoga 2-11 20332             | [92a038a164](https://linux-hardware.org/?probe=92a038a164) | Dec 16, 2022 |
| Lenovo        | ThinkPad X240 20AL007AMZ    | [8290c7e597](https://linux-hardware.org/?probe=8290c7e597) | Dec 16, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [04cc986bf6](https://linux-hardware.org/?probe=04cc986bf6) | Dec 15, 2022 |
| HP            | Presario CQ62               | [fce21eae2c](https://linux-hardware.org/?probe=fce21eae2c) | Dec 15, 2022 |
| Lenovo        | B590 20206                  | [b2b98c19da](https://linux-hardware.org/?probe=b2b98c19da) | Dec 15, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| OpenMandriva 4.2    | 2177      | 39.08%  |
| OpenMandriva 4.3    | 2020      | 36.26%  |
| OpenMandriva 23.01  | 746       | 13.39%  |
| OpenMandriva 4.50   | 415       | 7.45%   |
| OpenMandriva 4.90   | 168       | 3.02%   |
| OpenMandriva 22.12  | 30        | 0.54%   |
| OpenMandriva 4.1    | 4         | 0.07%   |
| OpenMandriva 23.90  | 4         | 0.07%   |
| OpenMandriva 22.90  | 3         | 0.05%   |
| OpenMandriva 3.0    | 2         | 0.04%   |
| OpenMandriva 22.11  | 1         | 0.02%   |
| OpenMandriva 2014.0 | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| OpenMandriva | 5495      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Notebooks | Percent |
|-------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002      | 2091      | 37.27%  |
| 5.16.7-desktop-1omv4003       | 1937      | 34.53%  |
| 6.1.1-desktop-1omv2290        | 685       | 12.21%  |
| 5.12.4-desktop-1omv4050       | 149       | 2.66%   |
| 5.18.12-desktop-3omv4090      | 133       | 2.37%   |
| 5.11.12-desktop-1omv4002      | 98        | 1.75%   |
| 5.14.7-desktop-1omv4050       | 83        | 1.48%   |
| 5.16.13-desktop-1omv4003      | 77        | 1.37%   |
| 5.19.5-desktop-1omv4090       | 73        | 1.3%    |
| 5.19.12-desktop-2omv4090      | 60        | 1.07%   |
| 6.1.4-desktop-1omv2301        | 50        | 0.89%   |
| 6.0.10-desktop-2omv22090      | 32        | 0.57%   |
| 5.14.14-desktop-1omv4050      | 17        | 0.3%    |
| 6.0.2-desktop-1omv4090        | 15        | 0.27%   |
| 5.17.1-desktop-2omv4050       | 13        | 0.23%   |
| 5.12.7-desktop-1omv4003       | 11        | 0.2%    |
| 6.0.2-desktop-1omv4050        | 6         | 0.11%   |
| 5.19.11-desktop-2omv4090      | 6         | 0.11%   |
| 5.19.1-desktop-1omv4090       | 5         | 0.09%   |
| 5.11.0-desktop-clang-1omv4002 | 5         | 0.09%   |
| 6.2.1-desktop-1omv2390        | 3         | 0.05%   |
| 5.5.12-desktop-1omv4001       | 3         | 0.05%   |
| 5.16.9-desktop-1omv4003       | 3         | 0.05%   |
| 6.2.0-desktop-0.rc2.1omv2301  | 2         | 0.04%   |
| 6.1.2-desktop-1omv2301        | 2         | 0.04%   |
| 6.1.11-desktop-1omv2390       | 2         | 0.04%   |
| 6.0.9-desktop-1omv22090       | 2         | 0.04%   |
| 5.9.12-desktop-1omv4002       | 2         | 0.04%   |
| 5.19.3-desktop-1omv4090       | 2         | 0.04%   |
| 5.18.9-desktop-gcc-1omv4090   | 2         | 0.04%   |
| 5.18.13-desktop-1omv4090      | 2         | 0.04%   |
| 5.17.1-desktop-clang-2omv4050 | 2         | 0.04%   |
| 6.1.5-desktop-1omv2390        | 1         | 0.02%   |
| 6.1.4-desktop-gcc-1omv2301    | 1         | 0.02%   |
| 6.1.10                        | 1         | 0.02%   |
| 6.1.0-desktop-1omv2290        | 1         | 0.02%   |
| 6.0.5-desktop-1omv4090        | 1         | 0.02%   |
| 6.0.0-desktop-1omv4090        | 1         | 0.02%   |
| 6.0.0-desktop-1omv4050        | 1         | 0.02%   |
| 5.8.13-desktop-1omv4002       | 1         | 0.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.14 | 2091      | 37.27%  |
| 5.16.7  | 1938      | 34.55%  |
| 6.1.1   | 685       | 12.21%  |
| 5.12.4  | 149       | 2.66%   |
| 5.18.12 | 133       | 2.37%   |
| 5.11.12 | 98        | 1.75%   |
| 5.14.7  | 83        | 1.48%   |
| 5.16.13 | 78        | 1.39%   |
| 5.19.5  | 73        | 1.3%    |
| 5.19.12 | 60        | 1.07%   |
| 6.1.4   | 51        | 0.91%   |
| 6.0.10  | 32        | 0.57%   |
| 6.0.2   | 21        | 0.37%   |
| 5.14.14 | 17        | 0.3%    |
| 5.17.1  | 15        | 0.27%   |
| 5.12.7  | 12        | 0.21%   |
| 5.11.0  | 7         | 0.12%   |
| 5.19.11 | 6         | 0.11%   |
| 5.19.1  | 5         | 0.09%   |
| 5.16.9  | 4         | 0.07%   |
| 6.2.1   | 3         | 0.05%   |
| 5.5.12  | 3         | 0.05%   |
| 6.2.0   | 2         | 0.04%   |
| 6.1.2   | 2         | 0.04%   |
| 6.1.11  | 2         | 0.04%   |
| 6.0.9   | 2         | 0.04%   |
| 6.0.0   | 2         | 0.04%   |
| 5.9.12  | 2         | 0.04%   |
| 5.19.3  | 2         | 0.04%   |
| 5.18.9  | 2         | 0.04%   |
| 5.18.13 | 2         | 0.04%   |
| 5.18.11 | 2         | 0.04%   |
| 6.1.5   | 1         | 0.02%   |
| 6.1.10  | 1         | 0.02%   |
| 6.1.0   | 1         | 0.02%   |
| 6.0.5   | 1         | 0.02%   |
| 5.8.13  | 1         | 0.02%   |
| 5.5.0   | 1         | 0.02%   |
| 5.19.8  | 1         | 0.02%   |
| 5.19.2  | 1         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 2093      | 37.39%  |
| 5.16    | 2013      | 35.96%  |
| 6.1     | 743       | 13.27%  |
| 5.12    | 161       | 2.88%   |
| 5.19    | 148       | 2.64%   |
| 5.18    | 139       | 2.48%   |
| 5.11    | 109       | 1.95%   |
| 5.14    | 100       | 1.79%   |
| 6.0     | 58        | 1.04%   |
| 5.17    | 15        | 0.27%   |
| 6.2     | 5         | 0.09%   |
| 5.5     | 4         | 0.07%   |
| 5.9     | 2         | 0.04%   |
| 5.15    | 2         | 0.04%   |
| 4.19    | 2         | 0.04%   |
| 5.8     | 1         | 0.02%   |
| 5.13    | 1         | 0.02%   |
| 4.1     | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 5494      | 99.98%  |
| Unknown | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 5368      | 97.62%  |
| GNOME    | 108       | 1.96%   |
| Unknown  | 10        | 0.18%   |
| LXQt     | 7         | 0.13%   |
| XFCE     | 2         | 0.04%   |
| Cinnamon | 2         | 0.04%   |
| KDE4     | 1         | 0.02%   |
| Budgie   | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 5381      | 97.87%  |
| Wayland | 116       | 2.11%   |
| Tty     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 5385      | 97.93%  |
| GDM     | 107       | 1.95%   |
| LightDM | 4         | 0.07%   |
| Unknown | 2         | 0.04%   |
| KDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 2974      | 53.78%  |
| de_DE   | 425       | 7.69%   |
| fr_FR   | 323       | 5.84%   |
| pl_PL   | 240       | 4.34%   |
| ru_RU   | 235       | 4.25%   |
| pt_BR   | 230       | 4.16%   |
| it_IT   | 157       | 2.84%   |
| cs_CZ   | 153       | 2.77%   |
| en_GB   | 140       | 2.53%   |
| es_ES   | 131       | 2.37%   |
| es_MX   | 50        | 0.9%    |
| es_AR   | 37        | 0.67%   |
| de_AT   | 31        | 0.56%   |
| hu_HU   | 27        | 0.49%   |
| es_CO   | 24        | 0.43%   |
| nl_NL   | 23        | 0.42%   |
| pt_PT   | 22        | 0.4%    |
| es_CL   | 21        | 0.38%   |
| fr_BE   | 20        | 0.36%   |
| en_CA   | 17        | 0.31%   |
| en_IN   | 16        | 0.29%   |
| en_AU   | 16        | 0.29%   |
| de_CH   | 16        | 0.29%   |
| tr_TR   | 15        | 0.27%   |
| fr_CA   | 14        | 0.25%   |
| ro_RO   | 12        | 0.22%   |
| nl_BE   | 12        | 0.22%   |
| fr_CH   | 12        | 0.22%   |
| da_DK   | 12        | 0.22%   |
| ru_UA   | 10        | 0.18%   |
| es_PE   | 10        | 0.18%   |
| Unknown | 10        | 0.18%   |
| es_VE   | 9         | 0.16%   |
| es_UY   | 8         | 0.14%   |
| en_NZ   | 8         | 0.14%   |
| nb_NO   | 7         | 0.13%   |
| uk_UA   | 5         | 0.09%   |
| es_CR   | 5         | 0.09%   |
| es_BO   | 5         | 0.09%   |
| es_EC   | 4         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2769      | 50.3%   |
| BIOS | 2736      | 49.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Overlay  | 4272      | 76.46%  |
| Ext4     | 1236      | 22.12%  |
| Btrfs    | 41        | 0.73%   |
| F2fs     | 15        | 0.27%   |
| Xfs      | 9         | 0.16%   |
| Ext2     | 6         | 0.11%   |
| Unknown  | 4         | 0.07%   |
| Ext3     | 2         | 0.04%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 3577      | 64.87%  |
| MBR     | 1932      | 35.04%  |
| Unknown | 5         | 0.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2846      | 51.31%  |
| No        | 2701      | 48.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3206      | 58.21%  |
| Yes       | 2302      | 41.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo                | 1039      | 18.91%  |
| Hewlett-Packard       | 963       | 17.53%  |
| Dell                  | 813       | 14.8%   |
| ASUSTek Computer      | 690       | 12.56%  |
| Acer                  | 628       | 11.43%  |
| Toshiba               | 272       | 4.95%   |
| Sony                  | 136       | 2.47%   |
| Samsung Electronics   | 125       | 2.27%   |
| Apple                 | 92        | 1.67%   |
| MSI                   | 89        | 1.62%   |
| Fujitsu               | 69        | 1.26%   |
| Positivo              | 48        | 0.87%   |
| Packard Bell          | 48        | 0.87%   |
| Medion                | 41        | 0.75%   |
| HUAWEI                | 30        | 0.55%   |
| Unknown               | 29        | 0.53%   |
| Notebook              | 25        | 0.45%   |
| eMachines             | 24        | 0.44%   |
| TUXEDO                | 22        | 0.4%    |
| Philco                | 21        | 0.38%   |
| Fujitsu Siemens       | 15        | 0.27%   |
| LG Electronics        | 14        | 0.25%   |
| Gateway               | 12        | 0.22%   |
| Google                | 11        | 0.2%    |
| Clevo                 | 11        | 0.2%    |
| Chuwi                 | 11        | 0.2%    |
| NEC Computers         | 9         | 0.16%   |
| Compaq                | 9         | 0.16%   |
| Alienware             | 9         | 0.16%   |
| Timi                  | 8         | 0.15%   |
| System76              | 8         | 0.15%   |
| Panasonic             | 8         | 0.15%   |
| Intel                 | 8         | 0.15%   |
| Gigabyte Technology   | 8         | 0.15%   |
| Wortmann AG           | 6         | 0.11%   |
| Teclast               | 6         | 0.11%   |
| Positivo Bahia - VAIO | 6         | 0.11%   |
| UMAX                  | 5         | 0.09%   |
| PC Specialist         | 5         | 0.09%   |
| Digibras              | 5         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| ASUS UX31E                     | 113       | 2.06%   |
| Unknown                        | 63        | 1.15%   |
| HP Notebook                    | 61        | 1.11%   |
| Dell Inspiron 3451             | 32        | 0.58%   |
| Dell Latitude 3310             | 29        | 0.53%   |
| HP Pavilion g6                 | 27        | 0.49%   |
| Toshiba dynabook T653/46JR     | 22        | 0.4%    |
| HP Pavilion dv6                | 21        | 0.38%   |
| Sony VGN-FZ31Z                 | 20        | 0.36%   |
| Dell Latitude E6430            | 19        | 0.35%   |
| HP Pavilion 15                 | 18        | 0.33%   |
| Dell Latitude D630             | 17        | 0.31%   |
| Dell Latitude E6410            | 16        | 0.29%   |
| HP 15                          | 15        | 0.27%   |
| Dell Latitude E6400            | 15        | 0.27%   |
| Dell Inspiron 15-3567          | 15        | 0.27%   |
| Positivo Mobile                | 14        | 0.25%   |
| Lenovo IdeaPad 3 15ADA05 81W1  | 14        | 0.25%   |
| Dell Latitude E6420            | 14        | 0.25%   |
| Lenovo IdeaPad S145-15AST 81N3 | 13        | 0.24%   |
| Lenovo IdeaPad 1 14ADA05 82GW  | 12        | 0.22%   |
| Apple MacBookPro9,2            | 12        | 0.22%   |
| Lenovo IdeaPad 330-15IKB 81DE  | 11        | 0.2%    |
| HP Pavilion Notebook           | 11        | 0.2%    |
| Dell Latitude E7450            | 11        | 0.2%    |
| Apple MacBookPro8,1            | 11        | 0.2%    |
| Lenovo G50-45 80E3             | 10        | 0.18%   |
| HP 2000                        | 10        | 0.18%   |
| Dell Inspiron N5110            | 10        | 0.18%   |
| Toshiba Satellite A300         | 9         | 0.16%   |
| HP Pavilion dv7                | 9         | 0.16%   |
| HP Laptop 15-db0xxx            | 9         | 0.16%   |
| HP EliteBook 8460p             | 9         | 0.16%   |
| HP Compaq 15                   | 9         | 0.16%   |
| Dell Latitude E6540            | 9         | 0.16%   |
| Dell Latitude E6500            | 9         | 0.16%   |
| Dell Inspiron 1525             | 9         | 0.16%   |
| ASUS S551LN                    | 9         | 0.16%   |
| ASUS K53U                      | 9         | 0.16%   |
| Acer Aspire 5738               | 9         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 464       | 8.44%   |
| Lenovo ThinkPad       | 425       | 7.73%   |
| Dell Latitude         | 404       | 7.35%   |
| Lenovo IdeaPad        | 334       | 6.08%   |
| Dell Inspiron         | 244       | 4.44%   |
| Toshiba Satellite     | 210       | 3.82%   |
| HP Pavilion           | 205       | 3.73%   |
| HP Laptop             | 143       | 2.6%    |
| HP ProBook            | 118       | 2.15%   |
| ASUS UX31E            | 113       | 2.06%   |
| HP EliteBook          | 111       | 2.02%   |
| ASUS VivoBook         | 108       | 1.97%   |
| HP Compaq             | 76        | 1.38%   |
| Unknown               | 63        | 1.15%   |
| HP Notebook           | 61        | 1.11%   |
| Fujitsu LIFEBOOK      | 54        | 0.98%   |
| Dell XPS              | 40        | 0.73%   |
| Packard Bell EasyNote | 39        | 0.71%   |
| Dell Vostro           | 39        | 0.71%   |
| Toshiba dynabook      | 34        | 0.62%   |
| Dell Precision        | 34        | 0.62%   |
| Acer TravelMate       | 33        | 0.6%    |
| Acer Nitro            | 33        | 0.6%    |
| Acer Extensa          | 33        | 0.6%    |
| HP 250                | 27        | 0.49%   |
| Acer Swift            | 24        | 0.44%   |
| HP 255                | 21        | 0.38%   |
| Sony VGN-FZ31Z        | 20        | 0.36%   |
| ASUS ZenBook          | 20        | 0.36%   |
| Lenovo Legion         | 19        | 0.35%   |
| HP ENVY               | 19        | 0.35%   |
| Dell Studio           | 19        | 0.35%   |
| Lenovo Yoga           | 18        | 0.33%   |
| HP Stream             | 17        | 0.31%   |
| HP 15                 | 17        | 0.31%   |
| ASUS ROG              | 16        | 0.29%   |
| HP OMEN               | 15        | 0.27%   |
| ASUS TUF              | 15        | 0.27%   |
| Apple MacBookPro9     | 15        | 0.27%   |
| Positivo Mobile       | 14        | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 678       | 12.34%  |
| 2012    | 542       | 9.86%   |
| 2013    | 450       | 8.19%   |
| 2019    | 404       | 7.35%   |
| 2014    | 391       | 7.12%   |
| 2010    | 391       | 7.12%   |
| 2020    | 349       | 6.35%   |
| 2015    | 328       | 5.97%   |
| 2016    | 308       | 5.61%   |
| 2008    | 305       | 5.55%   |
| 2018    | 298       | 5.42%   |
| 2017    | 282       | 5.13%   |
| 2021    | 245       | 4.46%   |
| 2009    | 238       | 4.33%   |
| 2007    | 187       | 3.4%    |
| 2022    | 60        | 1.09%   |
| 2006    | 25        | 0.45%   |
| Unknown | 8         | 0.15%   |
| 2005    | 3         | 0.05%   |
| 2004    | 2         | 0.04%   |
| 2023    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 5495      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 5495      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5470      | 99.55%  |
| Yes  | 25        | 0.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 2001      | 36.35%  |
| 4.01-8.0    | 1729      | 31.41%  |
| 8.01-16.0   | 784       | 14.24%  |
| 16.01-24.0  | 487       | 8.85%   |
| 1.01-2.0    | 236       | 4.29%   |
| 32.01-64.0  | 114       | 2.07%   |
| 2.01-3.0    | 106       | 1.93%   |
| 24.01-32.0  | 22        | 0.4%    |
| 64.01-256.0 | 14        | 0.25%   |
| 0.51-1.0    | 11        | 0.2%    |
| Unknown     | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 4448      | 80.01%  |
| 0.51-1.0  | 507       | 9.12%   |
| 2.01-3.0  | 496       | 8.92%   |
| 0.01-0.5  | 48        | 0.86%   |
| 3.01-4.0  | 44        | 0.79%   |
| 4.01-8.0  | 12        | 0.22%   |
| 8.01-16.0 | 3         | 0.05%   |
| Unknown   | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4085      | 74.04%  |
| 2      | 1187      | 21.52%  |
| 3      | 142       | 2.57%   |
| 0      | 80        | 1.45%   |
| 4      | 21        | 0.38%   |
| 5      | 2         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2800      | 50.88%  |
| No        | 2703      | 49.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4806      | 87.46%  |
| No        | 689       | 12.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5439      | 98.98%  |
| No        | 56        | 1.02%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3899      | 70.88%  |
| No        | 1602      | 29.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Germany      | 613       | 11.14%  |
| USA          | 580       | 10.54%  |
| France       | 402       | 7.31%   |
| Brazil       | 386       | 7.02%   |
| Poland       | 345       | 6.27%   |
| Russia       | 311       | 5.65%   |
| Italy        | 254       | 4.62%   |
| UK           | 198       | 3.6%    |
| Spain        | 183       | 3.33%   |
| Czechia      | 178       | 3.24%   |
| Canada       | 133       | 2.42%   |
| Netherlands  | 128       | 2.33%   |
| Mexico       | 101       | 1.84%   |
| Japan        | 83        | 1.51%   |
| India        | 80        | 1.45%   |
| Portugal     | 72        | 1.31%   |
| Indonesia    | 67        | 1.22%   |
| Australia    | 66        | 1.2%    |
| Romania      | 62        | 1.13%   |
| Belgium      | 59        | 1.07%   |
| Switzerland  | 53        | 0.96%   |
| Ukraine      | 51        | 0.93%   |
| Argentina    | 50        | 0.91%   |
| Sweden       | 49        | 0.89%   |
| Hungary      | 48        | 0.87%   |
| Austria      | 46        | 0.84%   |
| Finland      | 45        | 0.82%   |
| Turkey       | 43        | 0.78%   |
| Colombia     | 43        | 0.78%   |
| Greece       | 37        | 0.67%   |
| Chile        | 34        | 0.62%   |
| Slovakia     | 33        | 0.6%    |
| Bulgaria     | 32        | 0.58%   |
| China        | 31        | 0.56%   |
| Serbia       | 26        | 0.47%   |
| New Zealand  | 25        | 0.45%   |
| Norway       | 23        | 0.42%   |
| Denmark      | 22        | 0.4%    |
| South Africa | 20        | 0.36%   |
| Peru         | 20        | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Prague         | 115       | 2.06%   |
| Moscow         | 62        | 1.11%   |
| Warsaw         | 57        | 1.02%   |
| Schagen        | 56        | 1.01%   |
| Paris          | 56        | 1.01%   |
| Berlin         | 46        | 0.83%   |
| Krakow         | 44        | 0.79%   |
| Milan          | 38        | 0.68%   |
| Sao Paulo      | 36        | 0.65%   |
| Munich         | 34        | 0.61%   |
| Rome           | 29        | 0.52%   |
| Vienna         | 26        | 0.47%   |
| St Petersburg  | 26        | 0.47%   |
| Mexico City    | 26        | 0.47%   |
| Rio de Janeiro | 21        | 0.38%   |
| Helsinki       | 21        | 0.38%   |
| Funchal        | 20        | 0.36%   |
| Madrid         | 19        | 0.34%   |
| Hamburg        | 19        | 0.34%   |
| Sydney         | 18        | 0.32%   |
| Jakarta        | 18        | 0.32%   |
| Wroclaw        | 17        | 0.31%   |
| Krasnodar      | 17        | 0.31%   |
| Stuttgart      | 16        | 0.29%   |
| Cologne        | 15        | 0.27%   |
| Bucharest      | 15        | 0.27%   |
| Bogotá        | 15        | 0.27%   |
| Poznan         | 14        | 0.25%   |
| Istanbul       | 14        | 0.25%   |
| Buenos Aires   | 14        | 0.25%   |
| Barcelona      | 14        | 0.25%   |
| Athens         | 14        | 0.25%   |
| Budapest       | 13        | 0.23%   |
| Bengaluru      | 13        | 0.23%   |
| Belgrade       | 13        | 0.23%   |
| Auckland       | 13        | 0.23%   |
| Thessaloniki   | 12        | 0.22%   |
| Queens         | 12        | 0.22%   |
| Porto Alegre   | 12        | 0.22%   |
| Lima           | 12        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 974       | 1011   | 15.04%  |
| Seagate             | 808       | 847    | 12.48%  |
| Samsung Electronics | 744       | 818    | 11.49%  |
| Toshiba             | 616       | 644    | 9.51%   |
| Kingston            | 394       | 408    | 6.09%   |
| SanDisk             | 358       | 372    | 5.53%   |
| Hitachi             | 304       | 315    | 4.7%    |
| Unknown             | 255       | 263    | 3.94%   |
| Crucial             | 235       | 251    | 3.63%   |
| HGST                | 206       | 215    | 3.18%   |
| SK hynix            | 182       | 190    | 2.81%   |
| Intel               | 121       | 135    | 1.87%   |
| A-DATA Technology   | 113       | 118    | 1.75%   |
| Micron Technology   | 93        | 96     | 1.44%   |
| China               | 60        | 60     | 0.93%   |
| Fujitsu             | 56        | 57     | 0.86%   |
| GOODRAM             | 50        | 53     | 0.77%   |
| PNY                 | 44        | 46     | 0.68%   |
| KIOXIA              | 44        | 45     | 0.68%   |
| Apple               | 42        | 45     | 0.65%   |
| LITEON              | 40        | 40     | 0.62%   |
| Unknown             | 38        | 40     | 0.59%   |
| JMicron Technology  | 37        | 38     | 0.57%   |
| SPCC                | 35        | 36     | 0.54%   |
| Intenso             | 35        | 37     | 0.54%   |
| Patriot             | 30        | 32     | 0.46%   |
| Transcend           | 28        | 28     | 0.43%   |
| Phison              | 24        | 24     | 0.37%   |
| KingSpec            | 20        | 20     | 0.31%   |
| OCZ                 | 19        | 19     | 0.29%   |
| LITEONIT            | 19        | 20     | 0.29%   |
| UMIS                | 17        | 17     | 0.26%   |
| Silicon Motion      | 17        | 19     | 0.26%   |
| SABRENT             | 17        | 20     | 0.26%   |
| ASMT                | 17        | 17     | 0.26%   |
| Apacer              | 17        | 17     | 0.26%   |
| Hewlett-Packard     | 16        | 16     | 0.25%   |
| Gigabyte Technology | 16        | 16     | 0.25%   |
| SSSTC               | 15        | 16     | 0.23%   |
| Lexar               | 14        | 14     | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB     | 119       | 1.81%   |
| SanDisk SSD U100 256GB              | 113       | 1.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 96        | 1.46%   |
| Toshiba MQ01ABF050 500GB            | 94        | 1.43%   |
| Kingston SA400S37240G 240GB SSD     | 82        | 1.25%   |
| Toshiba MQ01ABD100 1TB              | 80        | 1.21%   |
| Seagate ST1000LM035-1RK172 1TB      | 78        | 1.18%   |
| Toshiba MQ04ABF100 1TB              | 61        | 0.93%   |
| Seagate ST9500325AS 500GB           | 49        | 0.74%   |
| Kingston SA400S37480G 480GB SSD     | 46        | 0.7%    |
| HGST HTS721010A9E630 1TB            | 45        | 0.68%   |
| Kingston SA400S37120G 120GB SSD     | 43        | 0.65%   |
| HGST HTS545050A7E680 500GB          | 42        | 0.64%   |
| Crucial CT240BX500SSD1 240GB        | 42        | 0.64%   |
| WDC WD10JPVX-22JC3T0 1TB            | 41        | 0.62%   |
| Samsung SSD 860 EVO 500GB           | 41        | 0.62%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 40        | 0.61%   |
| HGST HTS541010A9E680 1TB            | 39        | 0.59%   |
| Unknown                             | 38        | 0.58%   |
| Toshiba MQ01ABD075 752GB            | 36        | 0.55%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 34        | 0.52%   |
| Seagate ST500LT012-9WS142 500GB     | 30        | 0.46%   |
| Kingston SV300S37A120G 120GB SSD    | 30        | 0.46%   |
| Samsung SSD 850 EVO 250GB           | 29        | 0.44%   |
| Unknown SD/MMC/MS PRO 16GB          | 28        | 0.43%   |
| Samsung SSD 850 EVO 500GB           | 28        | 0.43%   |
| Crucial CT500MX500SSD1 500GB        | 28        | 0.43%   |
| Seagate ST9320325AS 320GB           | 27        | 0.41%   |
| Hitachi HTS547550A9E384 500GB       | 26        | 0.39%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 25        | 0.38%   |
| WDC WD10SPZX-21Z10T0 1TB            | 24        | 0.36%   |
| Samsung SSD 860 EVO 250GB           | 24        | 0.36%   |
| Hitachi HTS543232A7A384 320GB       | 24        | 0.36%   |
| HGST HTS545050A7E380 500GB          | 23        | 0.35%   |
| Hitachi HTS547575A9E384 752GB       | 22        | 0.33%   |
| Toshiba MQ01ABD050 500GB            | 20        | 0.3%    |
| PNY CS900 120GB SSD                 | 20        | 0.3%    |
| JMicron Generic 200GB               | 20        | 0.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 19        | 0.29%   |
| WDC WD10JPCX-24UE4T0 1TB            | 19        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 797       | 829    | 28.95%  |
| WDC                 | 703       | 726    | 25.54%  |
| Toshiba             | 536       | 555    | 19.47%  |
| Hitachi             | 304       | 315    | 11.04%  |
| HGST                | 206       | 215    | 7.48%   |
| Samsung Electronics | 58        | 60     | 2.11%   |
| Fujitsu             | 56        | 57     | 2.03%   |
| Unknown             | 28        | 28     | 1.02%   |
| JMicron Technology  | 20        | 20     | 0.73%   |
| SABRENT             | 12        | 14     | 0.44%   |
| Apple               | 12        | 12     | 0.44%   |
| SAGE                | 4         | 4      | 0.15%   |
| USB                 | 3         | 3      | 0.11%   |
| ASMedia             | 3         | 3      | 0.11%   |
| HGST HTS            | 2         | 2      | 0.07%   |
| ASMT                | 2         | 2      | 0.07%   |
| WD MediaMax         | 1         | 1      | 0.04%   |
| USB3.0              | 1         | 1      | 0.04%   |
| QC-FT-D             | 1         | 1      | 0.04%   |
| Magnetic Data       | 1         | 1      | 0.04%   |
| Intenso             | 1         | 1      | 0.04%   |
| IBM/Hitachi         | 1         | 1      | 0.04%   |
| Hewlett-Packard     | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 461       | 490    | 18.71%  |
| Kingston            | 326       | 338    | 13.23%  |
| SanDisk             | 321       | 331    | 13.03%  |
| Crucial             | 215       | 230    | 8.73%   |
| WDC                 | 128       | 128    | 5.19%   |
| A-DATA Technology   | 88        | 91     | 3.57%   |
| SK hynix            | 60        | 62     | 2.44%   |
| China               | 60        | 60     | 2.44%   |
| Toshiba             | 53        | 57     | 2.15%   |
| Micron Technology   | 52        | 54     | 2.11%   |
| GOODRAM             | 50        | 53     | 2.03%   |
| Intel               | 48        | 51     | 1.95%   |
| PNY                 | 38        | 39     | 1.54%   |
| LITEON              | 37        | 37     | 1.5%    |
| Intenso             | 32        | 34     | 1.3%    |
| SPCC                | 31        | 32     | 1.26%   |
| Patriot             | 29        | 31     | 1.18%   |
| Transcend           | 27        | 27     | 1.1%    |
| Apple               | 26        | 26     | 1.06%   |
| KingSpec            | 20        | 20     | 0.81%   |
| OCZ                 | 19        | 19     | 0.77%   |
| LITEONIT            | 19        | 20     | 0.77%   |
| Unknown             | 18        | 18     | 0.73%   |
| Apacer              | 17        | 17     | 0.69%   |
| Netac               | 12        | 12     | 0.49%   |
| Lexar               | 12        | 12     | 0.49%   |
| Hewlett-Packard     | 12        | 12     | 0.49%   |
| ASMT                | 12        | 12     | 0.49%   |
| Unknown             | 10        | 10     | 0.41%   |
| Plextor             | 10        | 10     | 0.41%   |
| Gigabyte Technology | 9         | 9      | 0.37%   |
| Corsair             | 8         | 10     | 0.32%   |
| KIOXIA-EXCERIA      | 7         | 7      | 0.28%   |
| KingDian            | 7         | 7      | 0.28%   |
| Dogfish             | 7         | 7      | 0.28%   |
| Teclast             | 6         | 6      | 0.24%   |
| Team                | 6         | 6      | 0.24%   |
| Seagate             | 6         | 7      | 0.24%   |
| KingFast            | 6         | 6      | 0.24%   |
| JMicron Technology  | 6         | 7      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2676      | 2852   | 42.96%  |
| SSD     | 2311      | 2562   | 37.1%   |
| NVMe    | 915       | 1024   | 14.69%  |
| MMC     | 264       | 282    | 4.24%   |
| Unknown | 63        | 66     | 1.01%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4560      | 5203   | 76.15%  |
| NVMe | 911       | 1015   | 15.21%  |
| MMC  | 264       | 282    | 4.41%   |
| SAS  | 253       | 286    | 4.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3647      | 4070   | 74.38%  |
| 0.51-1.0   | 1156      | 1238   | 23.58%  |
| 1.01-2.0   | 83        | 88     | 1.69%   |
| 4.01-10.0  | 9         | 10     | 0.18%   |
| 3.01-4.0   | 7         | 7      | 0.14%   |
| 2.01-3.0   | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 3087      | 55.24%  |
| 101-250        | 898       | 16.07%  |
| 251-500        | 583       | 10.43%  |
| 501-1000       | 277       | 4.96%   |
| 51-100         | 260       | 4.65%   |
| Unknown        | 215       | 3.85%   |
| 21-50          | 201       | 3.6%    |
| 1001-2000      | 55        | 0.98%   |
| 2001-3000      | 8         | 0.14%   |
| More than 3000 | 4         | 0.07%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 4883      | 87.65%  |
| Unknown        | 215       | 3.86%   |
| 21-50          | 154       | 2.76%   |
| 51-100         | 114       | 2.05%   |
| 101-250        | 110       | 1.97%   |
| 251-500        | 61        | 1.09%   |
| 501-1000       | 21        | 0.38%   |
| 1001-2000      | 10        | 0.18%   |
| More than 3000 | 1         | 0.02%   |
| 2001-3000      | 1         | 0.02%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB              | 113       | 113    | 8%      |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 37        | 37     | 2.62%   |
| Seagate ST500LT012-1DG142 500GB     | 36        | 36     | 2.55%   |
| Seagate ST9500325AS 500GB           | 34        | 36     | 2.41%   |
| HGST HTS545050A7E680 500GB          | 31        | 31     | 2.2%    |
| Toshiba MQ01ABF050 500GB            | 30        | 30     | 2.12%   |
| Toshiba MQ01ABD075 752GB            | 29        | 30     | 2.05%   |
| Seagate ST500LT012-9WS142 500GB     | 28        | 29     | 1.98%   |
| HGST HTS541010A9E680 1TB            | 24        | 25     | 1.7%    |
| Seagate ST9320325AS 320GB           | 23        | 23     | 1.63%   |
| Hitachi HTS543232A7A384 320GB       | 16        | 16     | 1.13%   |
| Toshiba MQ01ABD100 1TB              | 15        | 15     | 1.06%   |
| Seagate ST1000LM035-1RK172 1TB      | 15        | 15     | 1.06%   |
| Toshiba MQ01ABD050 500GB            | 14        | 14     | 0.99%   |
| Crucial CT240M500SSD1 240GB         | 14        | 14     | 0.99%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 13        | 13     | 0.92%   |
| Hitachi HTS545050A7E380 500GB       | 13        | 14     | 0.92%   |
| WDC WD10JPVX-22JC3T0 1TB            | 12        | 12     | 0.85%   |
| Kingston SV300S37A120G 120GB SSD    | 11        | 11     | 0.78%   |
| Hitachi HTS547575A9E384 752GB       | 11        | 11     | 0.78%   |
| Hitachi HTS547550A9E384 500GB       | 11        | 12     | 0.78%   |
| HGST HTS545050A7E380 500GB          | 11        | 11     | 0.78%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 10        | 10     | 0.71%   |
| Toshiba MK3265GSX 320GB             | 10        | 11     | 0.71%   |
| HGST HTS725050A7E630 500GB          | 10        | 10     | 0.71%   |
| HGST HTS721010A9E630 1TB            | 10        | 10     | 0.71%   |
| HGST HTS541075A9E680 752GB          | 10        | 11     | 0.71%   |
| Seagate ST9500420AS 500GB           | 9         | 9      | 0.64%   |
| Seagate ST9250827AS 250GB           | 9         | 9      | 0.64%   |
| Seagate ST500LM021-1KJ152 500GB     | 9         | 9      | 0.64%   |
| Hitachi HTS545050B9A300 500GB       | 9         | 10     | 0.64%   |
| Seagate ST9250410AS 250GB           | 8         | 9      | 0.57%   |
| Seagate ST9250315AS 250GB           | 8         | 8      | 0.57%   |
| Hitachi HTS547564A9E384 640GB       | 8         | 9      | 0.57%   |
| Seagate ST9320423AS 320GB           | 7         | 8      | 0.5%    |
| Seagate ST320LT007-9ZV142 320GB     | 7         | 7      | 0.5%    |
| Samsung Electronics HM641JI 640GB   | 7         | 8      | 0.5%    |
| Hitachi HTS725032A7E630 320GB       | 7         | 7      | 0.5%    |
| Hitachi HTS545025B9A300 250GB       | 7         | 7      | 0.5%    |
| Hitachi HTS542516K9SA00 160GB       | 7         | 7      | 0.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 328       | 337    | 23.26%  |
| Toshiba             | 228       | 232    | 16.17%  |
| WDC                 | 193       | 197    | 13.69%  |
| Hitachi             | 174       | 179    | 12.34%  |
| SanDisk             | 137       | 137    | 9.72%   |
| HGST                | 106       | 108    | 7.52%   |
| Samsung Electronics | 53        | 54     | 3.76%   |
| Crucial             | 30        | 30     | 2.13%   |
| Kingston            | 28        | 28     | 1.99%   |
| Fujitsu             | 20        | 20     | 1.42%   |
| SK hynix            | 15        | 16     | 1.06%   |
| Intel               | 14        | 15     | 0.99%   |
| A-DATA Technology   | 14        | 15     | 0.99%   |
| China               | 9         | 9      | 0.64%   |
| Micron Technology   | 7         | 8      | 0.5%    |
| Apple               | 6         | 6      | 0.43%   |
| OCZ                 | 5         | 5      | 0.35%   |
| LITEON              | 4         | 4      | 0.28%   |
| Transcend           | 2         | 2      | 0.14%   |
| SPCC                | 2         | 2      | 0.14%   |
| Plextor             | 2         | 2      | 0.14%   |
| KingSpec            | 2         | 2      | 0.14%   |
| Dogfish             | 2         | 2      | 0.14%   |
| Corsair             | 2         | 3      | 0.14%   |
| ASMT                | 2         | 2      | 0.14%   |
| ASMedia             | 2         | 2      | 0.14%   |
| XrayDisk            | 1         | 1      | 0.07%   |
| Vaseky              | 1         | 1      | 0.07%   |
| USB                 | 1         | 1      | 0.07%   |
| Unknown             | 1         | 1      | 0.07%   |
| Teclast             | 1         | 1      | 0.07%   |
| TakeMS              | 1         | 1      | 0.07%   |
| Smartbuy            | 1         | 1      | 0.07%   |
| PNY                 | 1         | 1      | 0.07%   |
| Platinet            | 1         | 1      | 0.07%   |
| Magnetic Data       | 1         | 1      | 0.07%   |
| LITEONIT            | 1         | 1      | 0.07%   |
| KLEVV               | 1         | 1      | 0.07%   |
| KingDian            | 1         | 1      | 0.07%   |
| JMicron Technology  | 1         | 1      | 0.07%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 328       | 337    | 30.6%   |
| Toshiba             | 224       | 228    | 20.9%   |
| WDC                 | 181       | 185    | 16.88%  |
| Hitachi             | 174       | 179    | 16.23%  |
| HGST                | 106       | 108    | 9.89%   |
| Samsung Electronics | 31        | 32     | 2.89%   |
| Fujitsu             | 20        | 20     | 1.87%   |
| ASMedia             | 2         | 2      | 0.19%   |
| Apple               | 2         | 2      | 0.19%   |
| USB                 | 1         | 1      | 0.09%   |
| Magnetic Data       | 1         | 1      | 0.09%   |
| IBM/Hitachi         | 1         | 1      | 0.09%   |
| ASMT                | 1         | 1      | 0.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1064      | 1097   | 75.89%  |
| SSD     | 325       | 330    | 23.18%  |
| NVMe    | 12        | 12     | 0.86%   |
| Unknown | 1         | 1      | 0.07%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-11ZCT0 320GB           | 2         | 2      | 5.88%   |
| WDC WD2500BEVS-22UST0 250GB           | 2         | 2      | 5.88%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 5.88%   |
| Hitachi HTS545050A7E380 500GB         | 2         | 2      | 5.88%   |
| Crucial CT500P2SSD8 500GB             | 2         | 2      | 5.88%   |
| WDC WD5000M22K-24Z1LT0-SSHD-16GB      | 1         | 1      | 2.94%   |
| WDC WD5000LPLX-75ZNTT0 500GB          | 1         | 1      | 2.94%   |
| WDC WD5000BPVT-60HXZT1 500GB          | 1         | 1      | 2.94%   |
| WDC WD5000BEVT-22ZAT0 500GB           | 1         | 1      | 2.94%   |
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 2.94%   |
| WDC WD3200BEKT-60KA9T0 320GB          | 1         | 1      | 2.94%   |
| WDC WD2500BEVT-60ZCT1 250GB           | 1         | 1      | 2.94%   |
| WDC WD2500BEVT-35A23T0 250GB          | 1         | 1      | 2.94%   |
| WDC WD1600BEVT-75A23T0 160GB          | 1         | 1      | 2.94%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1         | 1      | 2.94%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 2.94%   |
| Toshiba MK3265GSXN 320GB              | 1         | 1      | 2.94%   |
| Toshiba MK3259GSXP 320GB              | 1         | 2      | 2.94%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 2.94%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 2.94%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 2.94%   |
| Samsung Electronics SSD PM800 TM 64GB | 1         | 1      | 2.94%   |
| Samsung Electronics HM500JI 500GB     | 1         | 1      | 2.94%   |
| Samsung Electronics HM321HI 320GB     | 1         | 1      | 2.94%   |
| Samsung Electronics HM251JI 250GB     | 1         | 1      | 2.94%   |
| Intel SSDSA2BW160G3 160GB             | 1         | 1      | 2.94%   |
| Hitachi HTS723232A7A364 320GB         | 1         | 1      | 2.94%   |
| HGST HTS541010A9E680 1TB              | 1         | 1      | 2.94%   |
| Apple HDD HTS545050A7E362 500GB       | 1         | 1      | 2.94%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 14     | 41.18%  |
| Toshiba             | 5         | 6      | 14.71%  |
| Samsung Electronics | 4         | 4      | 11.76%  |
| Hitachi             | 3         | 3      | 8.82%   |
| Seagate             | 2         | 2      | 5.88%   |
| Crucial             | 2         | 2      | 5.88%   |
| SK hynix            | 1         | 1      | 2.94%   |
| Intel               | 1         | 1      | 2.94%   |
| HGST                | 1         | 1      | 2.94%   |
| Apple               | 1         | 1      | 2.94%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 4019      | 4761   | 67.87%  |
| Malfunc  | 1390      | 1440   | 23.47%  |
| Detected | 479       | 550    | 8.09%   |
| Failed   | 34        | 35     | 0.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4227      | 70.45%  |
| AMD                              | 800       | 13.33%  |
| Samsung Electronics              | 262       | 4.37%   |
| SanDisk                          | 161       | 2.68%   |
| SK hynix                         | 112       | 1.87%   |
| Kingston Technology Company      | 70        | 1.17%   |
| Nvidia                           | 52        | 0.87%   |
| Phison Electronics               | 47        | 0.78%   |
| KIOXIA                           | 45        | 0.75%   |
| Micron Technology                | 42        | 0.7%    |
| Toshiba America Info Systems     | 31        | 0.52%   |
| Silicon Motion                   | 27        | 0.45%   |
| Union Memory (Shenzhen)          | 21        | 0.35%   |
| Micron/Crucial Technology        | 20        | 0.33%   |
| ADATA Technology                 | 16        | 0.27%   |
| Solid State Storage Technology   | 15        | 0.25%   |
| Realtek Semiconductor            | 11        | 0.18%   |
| Silicon Integrated Systems [SiS] | 7         | 0.12%   |
| JMicron Technology               | 5         | 0.08%   |
| ASMedia Technology               | 5         | 0.08%   |
| Apple                            | 4         | 0.07%   |
| Silicon Image                    | 3         | 0.05%   |
| Seagate Technology               | 3         | 0.05%   |
| Lite-On Technology               | 3         | 0.05%   |
| Biwin Storage Technology         | 3         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.03%   |
| Marvell Technology Group         | 2         | 0.03%   |
| Lenovo                           | 2         | 0.03%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| Shenzhen Longsys Electronics     | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 608       | 9.34%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 578       | 8.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 498       | 7.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 427       | 6.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 331       | 5.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 310       | 4.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 221       | 3.39%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 219       | 3.36%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 212       | 3.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 180       | 2.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 175       | 2.69%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 149       | 2.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 146       | 2.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 122       | 1.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 107       | 1.64%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 105       | 1.61%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 104       | 1.6%    |
| Samsung NVMe SSD Controller 980                                                  | 88        | 1.35%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 79        | 1.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 78        | 1.2%    |
| Intel Volume Management Device NVMe RAID Controller                              | 70        | 1.07%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 61        | 0.94%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 58        | 0.89%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 57        | 0.88%   |
| Intel Tiger Lake-LP SATA Controller                                              | 53        | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 48        | 0.74%   |
| Intel Comet Lake SATA AHCI Controller                                            | 46        | 0.71%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 43        | 0.66%   |
| Micron Non-Volatile memory controller                                            | 42        | 0.64%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 40        | 0.61%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 39        | 0.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 38        | 0.58%   |
| Intel SSD 660P Series                                                            | 37        | 0.57%   |
| SK hynix BC511                                                                   | 34        | 0.52%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 32        | 0.49%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 30        | 0.46%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 30        | 0.46%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 28        | 0.43%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 28        | 0.43%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 28        | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 4507      | 71.48%  |
| NVMe | 910       | 14.43%  |
| IDE  | 494       | 7.84%   |
| RAID | 394       | 6.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 4497      | 81.84%  |
| AMD    | 998       | 18.16%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz             | 113       | 2.06%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 82        | 1.49%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 80        | 1.46%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 74        | 1.35%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 67        | 1.22%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 67        | 1.22%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 67        | 1.22%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 60        | 1.09%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 58        | 1.06%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 53        | 0.96%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 53        | 0.96%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 47        | 0.86%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 47        | 0.86%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 46        | 0.84%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 46        | 0.84%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 45        | 0.82%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 43        | 0.78%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 43        | 0.78%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 41        | 0.75%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 41        | 0.75%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 40        | 0.73%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 40        | 0.73%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 39        | 0.71%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 37        | 0.67%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 37        | 0.67%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 37        | 0.67%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 37        | 0.67%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 36        | 0.66%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 36        | 0.66%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 35        | 0.64%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 35        | 0.64%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 35        | 0.64%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 34        | 0.62%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 33        | 0.6%    |
| Intel Core i3-3110M CPU @ 2.40GHz             | 32        | 0.58%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 31        | 0.56%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 30        | 0.55%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 30        | 0.55%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 30        | 0.55%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 30        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1358      | 24.71%  |
| Intel Core i7           | 826       | 15.03%  |
| Intel Core i3           | 666       | 12.12%  |
| Intel Celeron           | 517       | 9.41%   |
| Intel Core 2 Duo        | 440       | 8.01%   |
| Intel Pentium           | 232       | 4.22%   |
| Other                   | 185       | 3.37%   |
| AMD Ryzen 5             | 166       | 3.02%   |
| AMD Ryzen 7             | 116       | 2.11%   |
| Intel Pentium Dual-Core | 99        | 1.8%    |
| AMD A6                  | 80        | 1.46%   |
| AMD E                   | 72        | 1.31%   |
| AMD E1                  | 67        | 1.22%   |
| AMD Ryzen 3             | 61        | 1.11%   |
| Intel Pentium Dual      | 55        | 1%      |
| AMD A8                  | 55        | 1%      |
| AMD A4                  | 50        | 0.91%   |
| Intel Atom              | 47        | 0.86%   |
| AMD A10                 | 39        | 0.71%   |
| AMD E2                  | 36        | 0.66%   |
| Intel Pentium Silver    | 32        | 0.58%   |
| Intel Core 2            | 27        | 0.49%   |
| AMD C-60                | 26        | 0.47%   |
| AMD Athlon              | 26        | 0.47%   |
| Intel Celeron Dual-Core | 17        | 0.31%   |
| AMD Ryzen 9             | 17        | 0.31%   |
| Intel Genuine           | 16        | 0.29%   |
| AMD Athlon II           | 14        | 0.25%   |
| AMD Turion 64 X2 Mobile | 12        | 0.22%   |
| AMD Phenom II           | 11        | 0.2%    |
| AMD Athlon X2           | 10        | 0.18%   |
| AMD C-70                | 8         | 0.15%   |
| AMD Athlon 64 X2        | 7         | 0.13%   |
| AMD A12                 | 7         | 0.13%   |
| Intel Core m3           | 6         | 0.11%   |
| AMD Turion II Dual-Core | 6         | 0.11%   |
| AMD Sempron             | 6         | 0.11%   |
| AMD Ryzen 7 PRO         | 6         | 0.11%   |
| AMD Mobile Sempron      | 5         | 0.09%   |
| Intel Core i9           | 4         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3911      | 71.16%  |
| 4      | 1166      | 21.22%  |
| 6      | 148       | 2.69%   |
| 8      | 130       | 2.37%   |
| 1      | 116       | 2.11%   |
| 14     | 12        | 0.22%   |
| 12     | 4         | 0.07%   |
| 3      | 4         | 0.07%   |
| 10     | 3         | 0.05%   |
| 16     | 1         | 0.02%   |
| 5      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5495      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3410      | 62.03%  |
| 1      | 2065      | 37.57%  |
| 8      | 12        | 0.22%   |
| 4      | 9         | 0.16%   |
| 12     | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5492      | 99.95%  |
| Unknown        | 3         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 675       | 12.26%  |
| 0x306a9    | 508       | 9.23%   |
| 0x1067a    | 321       | 5.83%   |
| 0x20655    | 262       | 4.76%   |
| 0x40651    | 236       | 4.29%   |
| 0x406e3    | 207       | 3.76%   |
| 0x306d4    | 204       | 3.71%   |
| Unknown    | 177       | 3.21%   |
| 0x806e9    | 173       | 3.14%   |
| 0x6fd      | 159       | 2.89%   |
| 0x306c3    | 146       | 2.65%   |
| 0x806ea    | 138       | 2.51%   |
| 0x30678    | 138       | 2.51%   |
| 0x806ec    | 121       | 2.2%    |
| 0x10676    | 121       | 2.2%    |
| 0x08108109 | 105       | 1.91%   |
| 0x806c1    | 88        | 1.6%    |
| 0x406c4    | 81        | 1.47%   |
| 0x706e5    | 76        | 1.38%   |
| 0x20652    | 76        | 1.38%   |
| 0x06006705 | 74        | 1.34%   |
| 0x906ea    | 70        | 1.27%   |
| 0x07030105 | 65        | 1.18%   |
| 0x506e3    | 64        | 1.16%   |
| 0x0500010d | 62        | 1.13%   |
| 0x706a1    | 61        | 1.11%   |
| 0x506c9    | 60        | 1.09%   |
| 0x706a8    | 53        | 0.96%   |
| 0x08108102 | 53        | 0.96%   |
| 0x08608103 | 44        | 0.8%    |
| 0x906e9    | 42        | 0.76%   |
| 0xa0652    | 35        | 0.64%   |
| 0x6fb      | 35        | 0.64%   |
| 0x08600106 | 35        | 0.64%   |
| 0x0a50000c | 34        | 0.62%   |
| 0x406c3    | 33        | 0.6%    |
| 0x05000101 | 31        | 0.56%   |
| 0x806eb    | 27        | 0.49%   |
| 0x0700010b | 25        | 0.45%   |
| 0x05000119 | 24        | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 681       | 12.39%  |
| KabyLake         | 598       | 10.88%  |
| IvyBridge        | 512       | 9.32%   |
| Penryn           | 443       | 8.06%   |
| Haswell          | 389       | 7.08%   |
| Westmere         | 343       | 6.24%   |
| Skylake          | 286       | 5.2%    |
| Silvermont       | 271       | 4.93%   |
| Core             | 256       | 4.66%   |
| Broadwell        | 210       | 3.82%   |
| Zen+             | 170       | 3.09%   |
| Bobcat           | 145       | 2.64%   |
| Excavator        | 116       | 2.11%   |
| Goldmont plus    | 114       | 2.07%   |
| Puma             | 99        | 1.8%    |
| TigerLake        | 94        | 1.71%   |
| Unknown          | 82        | 1.49%   |
| IceLake          | 81        | 1.47%   |
| Zen 2            | 79        | 1.44%   |
| Goldmont         | 62        | 1.13%   |
| Zen              | 56        | 1.02%   |
| Zen 3            | 49        | 0.89%   |
| Jaguar           | 46        | 0.84%   |
| Piledriver       | 45        | 0.82%   |
| CometLake        | 44        | 0.8%    |
| K10              | 42        | 0.76%   |
| Bonnell          | 36        | 0.66%   |
| K8 Hammer        | 33        | 0.6%    |
| Nehalem          | 23        | 0.42%   |
| K8 & K10 hybrid  | 23        | 0.42%   |
| K10 Llano        | 22        | 0.4%    |
| Tremont          | 17        | 0.31%   |
| Alderlake Hybrid | 16        | 0.29%   |
| Steamroller      | 12        | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4010      | 61.63%  |
| AMD                              | 1337      | 20.55%  |
| Nvidia                           | 1154      | 17.73%  |
| Silicon Integrated Systems [SiS] | 6         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 633       | 9.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 479       | 7.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 293       | 4.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 252       | 3.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 234       | 3.46%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 192       | 2.84%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 192       | 2.84%   |
| Intel HD Graphics 5500                                                                   | 181       | 2.67%   |
| Intel HD Graphics 620                                                                    | 175       | 2.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 157       | 2.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 141       | 2.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 141       | 2.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 130       | 1.92%   |
| Intel UHD Graphics 620                                                                   | 127       | 1.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 114       | 1.68%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 92        | 1.36%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 87        | 1.29%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 83        | 1.23%   |
| AMD Renoir                                                                               | 75        | 1.11%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 73        | 1.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 69        | 1.02%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 65        | 0.96%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 60        | 0.89%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 60        | 0.89%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 56        | 0.83%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 56        | 0.83%   |
| Intel HD Graphics 530                                                                    | 54        | 0.8%    |
| AMD Lucienne                                                                             | 52        | 0.77%   |
| Intel HD Graphics 500                                                                    | 48        | 0.71%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 45        | 0.66%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 44        | 0.65%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 44        | 0.65%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 42        | 0.62%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 41        | 0.61%   |
| Intel HD Graphics 630                                                                    | 39        | 0.58%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 36        | 0.53%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 34        | 0.5%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 34        | 0.5%    |
| Nvidia GM108M [GeForce 840M]                                                             | 32        | 0.47%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 31        | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 2993      | 54.37%  |
| 1 x AMD        | 986       | 17.91%  |
| Intel + Nvidia | 769       | 13.97%  |
| 1 x Nvidia     | 320       | 5.81%   |
| Intel + AMD    | 183       | 3.32%   |
| 2 x AMD        | 109       | 1.98%   |
| 2 x Intel      | 73        | 1.33%   |
| AMD + Nvidia   | 59        | 1.07%   |
| 2 x Nvidia     | 7         | 0.13%   |
| 1 x SiS        | 6         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 5444      | 99.04%  |
| Unknown     | 48        | 0.87%   |
| Proprietary | 5         | 0.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3202      | 58.21%  |
| 0.01-0.5   | 911       | 16.56%  |
| 1.01-2.0   | 625       | 11.36%  |
| 0.51-1.0   | 457       | 8.31%   |
| 3.01-4.0   | 198       | 3.6%    |
| 5.01-6.0   | 57        | 1.04%   |
| 7.01-8.0   | 32        | 0.58%   |
| 2.01-3.0   | 16        | 0.29%   |
| 8.01-16.0  | 3         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1193      | 21.02%  |
| LG Display              | 978       | 17.23%  |
| Chimei Innolux          | 778       | 13.71%  |
| BOE                     | 733       | 12.92%  |
| Samsung Electronics     | 688       | 12.12%  |
| Chi Mei Optoelectronics | 217       | 3.82%   |
| Lenovo                  | 140       | 2.47%   |
| CPT                     | 132       | 2.33%   |
| Apple                   | 91        | 1.6%    |
| LG Philips              | 78        | 1.37%   |
| Sharp                   | 63        | 1.11%   |
| InfoVision              | 51        | 0.9%    |
| Eizo                    | 50        | 0.88%   |
| PANDA                   | 47        | 0.83%   |
| Dell                    | 44        | 0.78%   |
| Goldstar                | 42        | 0.74%   |
| Hewlett-Packard         | 33        | 0.58%   |
| Acer                    | 31        | 0.55%   |
| Sony                    | 24        | 0.42%   |
| Philips                 | 23        | 0.41%   |
| AOC                     | 22        | 0.39%   |
| BenQ                    | 18        | 0.32%   |
| Toshiba                 | 15        | 0.26%   |
| InnoLux Display         | 13        | 0.23%   |
| Panasonic               | 12        | 0.21%   |
| Iiyama                  | 12        | 0.21%   |
| CSO                     | 12        | 0.21%   |
| Ancor Communications    | 11        | 0.19%   |
| HannStar                | 10        | 0.18%   |
| ViewSonic               | 9         | 0.16%   |
| ASUSTek Computer        | 9         | 0.16%   |
| Vizio                   | 6         | 0.11%   |
| KDC                     | 6         | 0.11%   |
| Vestel Elektronik       | 5         | 0.09%   |
| Unknown                 | 5         | 0.09%   |
| Quanta Display          | 5         | 0.09%   |
| IBM                     | 5         | 0.09%   |
| Fujitsu Siemens         | 5         | 0.09%   |
| ___                     | 3         | 0.05%   |
| STA                     | 3         | 0.05%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 113       | 1.99%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 63        | 1.11%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 55        | 0.97%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 54        | 0.95%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 48        | 0.84%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 48        | 0.84%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                        | 46        | 0.81%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 44        | 0.77%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 43        | 0.76%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 40        | 0.7%    |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 34        | 0.6%    |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 32        | 0.56%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 32        | 0.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 31        | 0.54%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 31        | 0.54%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 29        | 0.51%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 26        | 0.46%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 26        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 25        | 0.44%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 24        | 0.42%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 24        | 0.42%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 24        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 22        | 0.39%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 22        | 0.39%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 21        | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 21        | 0.37%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 21        | 0.37%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 21        | 0.37%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 21        | 0.37%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 20        | 0.35%   |
| AU Optronics LCD Monitor AUO202D 1920x1080 293x165mm 13.2-inch           | 20        | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 19        | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 19        | 0.33%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 19        | 0.33%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 19        | 0.33%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 19        | 0.33%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 18        | 0.32%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 18        | 0.32%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 18        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 18        | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 2539      | 45.57%  |
| 1920x1080 (FHD)    | 1606      | 28.82%  |
| 1600x900 (HD+)     | 512       | 9.19%   |
| 1280x800 (WXGA)    | 334       | 5.99%   |
| 1440x900 (WXGA+)   | 135       | 2.42%   |
| 3840x2160 (4K)     | 126       | 2.26%   |
| 1680x1050 (WSXGA+) | 48        | 0.86%   |
| 1920x1200 (WUXGA)  | 47        | 0.84%   |
| 2560x1440 (QHD)    | 45        | 0.81%   |
| 2560x1600          | 29        | 0.52%   |
| 1024x600           | 18        | 0.32%   |
| 3200x1800 (QHD+)   | 17        | 0.31%   |
| 1280x1024 (SXGA)   | 17        | 0.31%   |
| 1360x768           | 12        | 0.22%   |
| 2880x1800          | 11        | 0.2%    |
| 1680x945           | 10        | 0.18%   |
| 1024x768 (XGA)     | 10        | 0.18%   |
| 1920x540           | 7         | 0.13%   |
| 2256x1504          | 6         | 0.11%   |
| 2160x1440          | 6         | 0.11%   |
| 1920x1280          | 5         | 0.09%   |
| 3840x2400          | 4         | 0.07%   |
| 2560x1080          | 4         | 0.07%   |
| 1400x1050          | 3         | 0.05%   |
| 800x1280           | 2         | 0.04%   |
| 3456x2160          | 2         | 0.04%   |
| 3440x1440          | 2         | 0.04%   |
| 2288x1287          | 2         | 0.04%   |
| 2240x1400          | 2         | 0.04%   |
| 3840x1100          | 1         | 0.02%   |
| 3840x1080          | 1         | 0.02%   |
| 3300x2200          | 1         | 0.02%   |
| 3200x2000          | 1         | 0.02%   |
| 3000x2000          | 1         | 0.02%   |
| 2560x1700          | 1         | 0.02%   |
| 2304x1440          | 1         | 0.02%   |
| 1920x550           | 1         | 0.02%   |
| 1600x1200          | 1         | 0.02%   |
| 1360x765           | 1         | 0.02%   |
| 1280x720 (HD)      | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2708      | 47.66%  |
| 13      | 880       | 15.49%  |
| 14      | 637       | 11.21%  |
| 17      | 552       | 9.71%   |
| 12      | 191       | 3.36%   |
| 11      | 131       | 2.31%   |
| 23      | 80        | 1.41%   |
| 31      | 74        | 1.3%    |
| 27      | 59        | 1.04%   |
| 24      | 52        | 0.92%   |
| 18      | 51        | 0.9%    |
| 21      | 48        | 0.84%   |
| 16      | 32        | 0.56%   |
| 10      | 28        | 0.49%   |
| 20      | 22        | 0.39%   |
| 19      | 17        | 0.3%    |
| 22      | 14        | 0.25%   |
| 54      | 13        | 0.23%   |
| 84      | 12        | 0.21%   |
| Unknown | 9         | 0.16%   |
| 26      | 8         | 0.14%   |
| 72      | 7         | 0.12%   |
| 40      | 7         | 0.12%   |
| 32      | 7         | 0.12%   |
| 65      | 5         | 0.09%   |
| 34      | 5         | 0.09%   |
| 25      | 5         | 0.09%   |
| 48      | 4         | 0.07%   |
| 37      | 3         | 0.05%   |
| 142     | 2         | 0.04%   |
| 74      | 2         | 0.04%   |
| 55      | 2         | 0.04%   |
| 47      | 2         | 0.04%   |
| 46      | 2         | 0.04%   |
| 42      | 2         | 0.04%   |
| 7       | 2         | 0.04%   |
| 52      | 1         | 0.02%   |
| 50      | 1         | 0.02%   |
| 49      | 1         | 0.02%   |
| 39      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 3702      | 65.3%   |
| 201-300        | 788       | 13.9%   |
| 351-400        | 673       | 11.87%  |
| 501-600        | 195       | 3.44%   |
| 401-500        | 138       | 2.43%   |
| 601-700        | 81        | 1.43%   |
| 1001-1500      | 31        | 0.55%   |
| 1501-2000      | 21        | 0.37%   |
| 701-800        | 14        | 0.25%   |
| 801-900        | 11        | 0.19%   |
| Unknown        | 9         | 0.16%   |
| More than 2000 | 2         | 0.04%   |
| 901-1000       | 2         | 0.04%   |
| 1-100          | 2         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 4653      | 87.04%  |
| 16/10 | 609       | 11.39%  |
| 3/2   | 34        | 0.64%   |
| 5/4   | 18        | 0.34%   |
| 4/3   | 17        | 0.32%   |
| 21/9  | 5         | 0.09%   |
| 32/9  | 4         | 0.07%   |
| 1.00  | 2         | 0.04%   |
| 0.67  | 2         | 0.04%   |
| 3.40  | 1         | 0.02%   |
| 1.96  | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2709      | 47.69%  |
| 81-90          | 1139      | 20.05%  |
| 121-130        | 459       | 8.08%   |
| 71-80          | 378       | 6.65%   |
| 61-70          | 184       | 3.24%   |
| 201-250        | 170       | 2.99%   |
| 51-60          | 133       | 2.34%   |
| 351-500        | 88        | 1.55%   |
| 131-140        | 88        | 1.55%   |
| 301-350        | 61        | 1.07%   |
| 141-150        | 53        | 0.93%   |
| 151-200        | 52        | 0.92%   |
| More than 1000 | 48        | 0.84%   |
| 41-50          | 27        | 0.48%   |
| 251-300        | 25        | 0.44%   |
| 501-1000       | 20        | 0.35%   |
| 111-120        | 18        | 0.32%   |
| 91-100         | 18        | 0.32%   |
| Unknown        | 9         | 0.16%   |
| 1-40           | 2         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 2573      | 45.97%  |
| 121-160       | 1852      | 33.09%  |
| 51-100        | 840       | 15.01%  |
| 161-240       | 224       | 4%      |
| More than 240 | 55        | 0.98%   |
| 1-50          | 44        | 0.79%   |
| Unknown       | 9         | 0.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 5032      | 91.49%  |
| 2     | 439       | 7.98%   |
| 0     | 21        | 0.38%   |
| 3     | 6         | 0.11%   |
| 4     | 2         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2980      | 33.18%  |
| Intel                             | 2376      | 26.45%  |
| Qualcomm Atheros                  | 1880      | 20.93%  |
| Broadcom                          | 617       | 6.87%   |
| Marvell Technology Group          | 160       | 1.78%   |
| Broadcom Limited                  | 143       | 1.59%   |
| Samsung Electronics               | 134       | 1.49%   |
| Ralink                            | 120       | 1.34%   |
| JMicron Technology                | 63        | 0.7%    |
| MediaTek                          | 53        | 0.59%   |
| Huawei Technologies               | 49        | 0.55%   |
| Dell                              | 49        | 0.55%   |
| Ericsson Business Mobile Networks | 41        | 0.46%   |
| Ralink Technology                 | 35        | 0.39%   |
| TP-Link                           | 34        | 0.38%   |
| Nvidia                            | 34        | 0.38%   |
| ASIX Electronics                  | 21        | 0.23%   |
| Sierra Wireless                   | 20        | 0.22%   |
| Hewlett-Packard                   | 18        | 0.2%    |
| Qualcomm Atheros Communications   | 12        | 0.13%   |
| D-Link                            | 12        | 0.13%   |
| Xiaomi                            | 11        | 0.12%   |
| DisplayLink                       | 11        | 0.12%   |
| Motorola PCS                      | 9         | 0.1%    |
| Linksys                           | 8         | 0.09%   |
| Silicon Integrated Systems [SiS]  | 7         | 0.08%   |
| Qualcomm                          | 7         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 6         | 0.07%   |
| NetGear                           | 5         | 0.06%   |
| D-Link System                     | 5         | 0.06%   |
| Belkin Components                 | 5         | 0.06%   |
| T & A Mobile Phones               | 4         | 0.04%   |
| Edimax Technology                 | 4         | 0.04%   |
| ASUSTek Computer                  | 4         | 0.04%   |
| Qcom                              | 3         | 0.03%   |
| OPPO                              | 3         | 0.03%   |
| ICS Advent                        | 3         | 0.03%   |
| Google                            | 3         | 0.03%   |
| AVM                               | 3         | 0.03%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1696      | 15.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 767       | 7.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 348       | 3.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 339       | 3.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 307       | 2.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 279       | 2.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 254       | 2.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 188       | 1.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 179       | 1.68%   |
| Intel Wireless 7265                                                     | 161       | 1.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 149       | 1.39%   |
| Intel Wireless 7260                                                     | 135       | 1.26%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 129       | 1.21%   |
| Intel Wireless 8265 / 8275                                              | 129       | 1.21%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 128       | 1.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 124       | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 109       | 1.02%   |
| Intel Wi-Fi 6 AX200                                                     | 109       | 1.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 105       | 0.98%   |
| Intel Wireless 8260                                                     | 103       | 0.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 102       | 0.95%   |
| Intel Wireless 3165                                                     | 100       | 0.94%   |
| Intel WiFi Link 5100                                                    | 94        | 0.88%   |
| Intel 82577LM Gigabit Network Connection                                | 88        | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 87        | 0.81%   |
| Intel Wireless 3160                                                     | 86        | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 83        | 0.78%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 79        | 0.74%   |
| Intel Centrino Advanced-N 6200                                          | 76        | 0.71%   |
| Intel 82567LM Gigabit Network Connection                                | 76        | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 67        | 0.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 67        | 0.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 66        | 0.62%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 65        | 0.61%   |
| Intel Centrino Ultimate-N 6300                                          | 64        | 0.6%    |
| Intel Wi-Fi 6 AX201                                                     | 62        | 0.58%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 61        | 0.57%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 61        | 0.57%   |
| Broadcom BCM43142 802.11b/g/n                                           | 60        | 0.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 59        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2255      | 40.07%  |
| Qualcomm Atheros                      | 1647      | 29.27%  |
| Realtek Semiconductor                 | 931       | 16.55%  |
| Broadcom                              | 405       | 7.2%    |
| Ralink                                | 120       | 2.13%   |
| Broadcom Limited                      | 69        | 1.23%   |
| MediaTek                              | 36        | 0.64%   |
| Ralink Technology                     | 35        | 0.62%   |
| Dell                                  | 26        | 0.46%   |
| Sierra Wireless                       | 20        | 0.36%   |
| TP-Link                               | 13        | 0.23%   |
| Qualcomm Atheros Communications       | 12        | 0.21%   |
| D-Link                                | 8         | 0.14%   |
| Ericsson Business Mobile Networks     | 7         | 0.12%   |
| Linksys                               | 6         | 0.11%   |
| Hewlett-Packard                       | 6         | 0.11%   |
| D-Link System                         | 5         | 0.09%   |
| Edimax Technology                     | 4         | 0.07%   |
| Belkin Components                     | 4         | 0.07%   |
| ASUSTek Computer                      | 4         | 0.07%   |
| Qcom                                  | 3         | 0.05%   |
| AVM                                   | 3         | 0.05%   |
| NetGear                               | 2         | 0.04%   |
| FIBOCOM                               | 2         | 0.04%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Senao                                 | 1         | 0.02%   |
| Elecom                                | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 348       | 6.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 339       | 6.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 307       | 5.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 279       | 4.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 188       | 3.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 179       | 3.17%   |
| Intel Wireless 7265                                                     | 161       | 2.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 149       | 2.64%   |
| Intel Wireless 7260                                                     | 135       | 2.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 129       | 2.29%   |
| Intel Wireless 8265 / 8275                                              | 129       | 2.29%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 124       | 2.2%    |
| Intel Wi-Fi 6 AX200                                                     | 109       | 1.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 105       | 1.86%   |
| Intel Wireless 8260                                                     | 103       | 1.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 102       | 1.81%   |
| Intel Wireless 3165                                                     | 100       | 1.77%   |
| Intel WiFi Link 5100                                                    | 94        | 1.67%   |
| Intel Wireless 3160                                                     | 86        | 1.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 83        | 1.47%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 79        | 1.4%    |
| Intel Centrino Advanced-N 6200                                          | 76        | 1.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 67        | 1.19%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 67        | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 66        | 1.17%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 65        | 1.15%   |
| Intel Centrino Ultimate-N 6300                                          | 64        | 1.13%   |
| Intel Wi-Fi 6 AX201                                                     | 62        | 1.1%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 61        | 1.08%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 61        | 1.08%   |
| Broadcom BCM43142 802.11b/g/n                                           | 60        | 1.06%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 55        | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 55        | 0.98%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 54        | 0.96%   |
| Intel Centrino Wireless-N 2230                                          | 53        | 0.94%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 50        | 0.89%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 49        | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 49        | 0.87%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 46        | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 46        | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2624      | 53.27%  |
| Intel                            | 878       | 17.82%  |
| Qualcomm Atheros                 | 465       | 9.44%   |
| Broadcom                         | 303       | 6.15%   |
| Marvell Technology Group         | 160       | 3.25%   |
| Samsung Electronics              | 134       | 2.72%   |
| Broadcom Limited                 | 76        | 1.54%   |
| JMicron Technology               | 63        | 1.28%   |
| Huawei Technologies              | 42        | 0.85%   |
| Nvidia                           | 33        | 0.67%   |
| TP-Link                          | 21        | 0.43%   |
| ASIX Electronics                 | 21        | 0.43%   |
| MediaTek                         | 17        | 0.35%   |
| Xiaomi                           | 11        | 0.22%   |
| DisplayLink                      | 11        | 0.22%   |
| Silicon Integrated Systems [SiS] | 7         | 0.14%   |
| Qualcomm                         | 7         | 0.14%   |
| Motorola PCS                     | 7         | 0.14%   |
| OnePlus Technology (Shenzhen)    | 6         | 0.12%   |
| Hewlett-Packard                  | 4         | 0.08%   |
| D-Link                           | 4         | 0.08%   |
| OPPO                             | 3         | 0.06%   |
| NetGear                          | 3         | 0.06%   |
| ICS Advent                       | 3         | 0.06%   |
| Google                           | 3         | 0.06%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.04%   |
| T & A Mobile Phones              | 2         | 0.04%   |
| Linksys                          | 2         | 0.04%   |
| Lenovo                           | 2         | 0.04%   |
| Attansic Technology              | 2         | 0.04%   |
| Apple                            | 2         | 0.04%   |
| vivo                             | 1         | 0.02%   |
| Spreadtrum Communications        | 1         | 0.02%   |
| Sitecom Europe                   | 1         | 0.02%   |
| HTC (High Tech Computer)         | 1         | 0.02%   |
| HMD Global                       | 1         | 0.02%   |
| Belkin Components                | 1         | 0.02%   |
| Archos                           | 1         | 0.02%   |
| Allwinner Technology             | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 1696      | 34.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 767       | 15.47%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 254       | 5.12%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 128       | 2.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 109       | 2.2%    |
| Intel 82577LM Gigabit Network Connection                                       | 88        | 1.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 87        | 1.75%   |
| Intel 82567LM Gigabit Network Connection                                       | 76        | 1.53%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 59        | 1.19%   |
| Intel Ethernet Connection I218-LM                                              | 56        | 1.13%   |
| Intel Ethernet Connection (3) I218-LM                                          | 54        | 1.09%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 53        | 1.07%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 52        | 1.05%   |
| Intel Ethernet Connection I219-LM                                              | 48        | 0.97%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 46        | 0.93%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 43        | 0.87%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 41        | 0.83%   |
| Intel Ethernet Connection I217-LM                                              | 41        | 0.83%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 40        | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 37        | 0.75%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 35        | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                                          | 34        | 0.69%   |
| Huawei E353/E3131                                                              | 34        | 0.69%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 34        | 0.69%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 31        | 0.63%   |
| Intel 82566MM Gigabit Network Connection                                       | 30        | 0.61%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 29        | 0.58%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 27        | 0.54%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 27        | 0.54%   |
| Intel 82579V Gigabit Network Connection                                        | 27        | 0.54%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 24        | 0.48%   |
| Intel Ethernet Connection I219-V                                               | 24        | 0.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 23        | 0.46%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 23        | 0.46%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 22        | 0.44%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 22        | 0.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 21        | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 20        | 0.4%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 20        | 0.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 19        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5440      | 52.67%  |
| Ethernet | 4802      | 46.49%  |
| Modem    | 80        | 0.77%   |
| Unknown  | 7         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3720      | 69.21%  |
| Ethernet | 1655      | 30.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 4394      | 79.96%  |
| 1     | 1039      | 18.91%  |
| 0     | 45        | 0.82%   |
| 3     | 17        | 0.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4024      | 72.96%  |
| Yes  | 1491      | 27.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1424      | 36.36%  |
| Qualcomm Atheros Communications | 503       | 12.84%  |
| Realtek Semiconductor           | 436       | 11.13%  |
| Broadcom                        | 313       | 7.99%   |
| Lite-On Technology              | 275       | 7.02%   |
| IMC Networks                    | 188       | 4.8%    |
| Foxconn / Hon Hai               | 173       | 4.42%   |
| Dell                            | 113       | 2.89%   |
| Apple                           | 88        | 2.25%   |
| Toshiba                         | 85        | 2.17%   |
| Hewlett-Packard                 | 77        | 1.97%   |
| Ralink                          | 54        | 1.38%   |
| Cambridge Silicon Radio         | 51        | 1.3%    |
| Realtek                         | 20        | 0.51%   |
| Alps Electric                   | 19        | 0.49%   |
| Foxconn International           | 18        | 0.46%   |
| ASUSTek Computer                | 18        | 0.46%   |
| Ralink Technology               | 13        | 0.33%   |
| Chicony Electronics             | 13        | 0.33%   |
| Askey Computer                  | 10        | 0.26%   |
| Fujitsu                         | 5         | 0.13%   |
| Taiyo Yuden                     | 4         | 0.1%    |
| MediaTek                        | 4         | 0.1%    |
| Micro Star International        | 3         | 0.08%   |
| Edimax Technology               | 2         | 0.05%   |
| USI                             | 1         | 0.03%   |
| Unknown                         | 1         | 0.03%   |
| TP-Link                         | 1         | 0.03%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| D-Link System                   | 1         | 0.03%   |
| Belkin Components               | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 740       | 18.89%  |
| Realtek Bluetooth Radio                                                             | 267       | 6.82%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 222       | 5.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 193       | 4.93%   |
| Intel AX201 Bluetooth                                                               | 131       | 3.34%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 109       | 2.78%   |
| Intel AX200 Bluetooth                                                               | 109       | 2.78%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 100       | 2.55%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 97        | 2.48%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 88        | 2.25%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 85        | 2.17%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 71        | 1.81%   |
| IMC Networks Bluetooth Radio                                                        | 68        | 1.74%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 67        | 1.71%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 66        | 1.68%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 62        | 1.58%   |
| Lite-On Bluetooth Device                                                            | 57        | 1.46%   |
| IMC Networks Bluetooth Device                                                       | 55        | 1.4%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 55        | 1.4%    |
| Ralink RT3290 Bluetooth                                                             | 54        | 1.38%   |
| Dell DW375 Bluetooth Module                                                         | 51        | 1.3%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 51        | 1.3%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 49        | 1.25%   |
| Apple Bluetooth Host Controller                                                     | 48        | 1.23%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 47        | 1.2%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 44        | 1.12%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 38        | 0.97%   |
| Realtek RTL8723B Bluetooth                                                          | 34        | 0.87%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 33        | 0.84%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 31        | 0.79%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 28        | 0.71%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 28        | 0.71%   |
| Apple Bluetooth USB Host Controller                                                 | 28        | 0.71%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 27        | 0.69%   |
| Toshiba Bluetooth Device                                                            | 26        | 0.66%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 24        | 0.61%   |
| Broadcom HP Portable SoftSailing                                                    | 22        | 0.56%   |
| Intel AX210 Bluetooth                                                               | 21        | 0.54%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 21        | 0.54%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 20        | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4443      | 70.52%  |
| AMD                                          | 1142      | 18.13%  |
| Nvidia                                       | 608       | 9.65%   |
| C-Media Electronics                          | 12        | 0.19%   |
| Logitech                                     | 11        | 0.17%   |
| Realtek Semiconductor                        | 8         | 0.13%   |
| Silicon Integrated Systems [SiS]             | 7         | 0.11%   |
| JMTek                                        | 6         | 0.1%    |
| Creative Technology                          | 6         | 0.1%    |
| Generalplus Technology                       | 5         | 0.08%   |
| Texas Instruments                            | 4         | 0.06%   |
| Lenovo                                       | 4         | 0.06%   |
| GN Netcom                                    | 4         | 0.06%   |
| ASUSTek Computer                             | 4         | 0.06%   |
| Focusrite-Novation                           | 3         | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.03%   |
| Razer USA                                    | 2         | 0.03%   |
| Plantronics                                  | 2         | 0.03%   |
| M-Audio                                      | 2         | 0.03%   |
| Conexant Systems                             | 2         | 0.03%   |
| Apple                                        | 2         | 0.03%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.02%   |
| Yamaha                                       | 1         | 0.02%   |
| XMOS                                         | 1         | 0.02%   |
| TTGK Technology                              | 1         | 0.02%   |
| TerraTec Electronic                          | 1         | 0.02%   |
| Tenx Technology                              | 1         | 0.02%   |
| TEAC                                         | 1         | 0.02%   |
| Schiit Audio                                 | 1         | 0.02%   |
| Samsung Electronics                          | 1         | 0.02%   |
| Samson Technologies                          | 1         | 0.02%   |
| RODE Microphones                             | 1         | 0.02%   |
| Phison Electronics                           | 1         | 0.02%   |
| Native Instruments                           | 1         | 0.02%   |
| MosArt Semiconductor                         | 1         | 0.02%   |
| ESS Technology                               | 1         | 0.02%   |
| Elitegroup Computer Systems (ECS)            | 1         | 0.02%   |
| Dell                                         | 1         | 0.02%   |
| Corsair                                      | 1         | 0.02%   |
| Cambridge Audio                              | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 651       | 8.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 542       | 6.97%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 538       | 6.92%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 407       | 5.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 399       | 5.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 366       | 4.71%   |
| AMD FCH Azalia Controller                                                                         | 273       | 3.51%   |
| Intel 8 Series HD Audio Controller                                                                | 238       | 3.06%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 235       | 3.02%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 228       | 2.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 211       | 2.71%   |
| Intel Broadwell-U Audio Controller                                                                | 210       | 2.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 209       | 2.69%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 175       | 2.25%   |
| AMD Kabini HDMI/DP Audio                                                                          | 174       | 2.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 157       | 2.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 152       | 1.95%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 147       | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 135       | 1.74%   |
| AMD Wrestler HDMI Audio                                                                           | 120       | 1.54%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 116       | 1.49%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 115       | 1.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 113       | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 106       | 1.36%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 94        | 1.21%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 92        | 1.18%   |
| AMD High Definition Audio Controller                                                              | 87        | 1.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 78        | 1%      |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 76        | 0.98%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 70        | 0.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 63        | 0.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 63        | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 62        | 0.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 50        | 0.64%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 50        | 0.64%   |
| Intel CM238 HD Audio Controller                                                                   | 49        | 0.63%   |
| AMD Trinity HDMI Audio Controller                                                                 | 45        | 0.58%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 40        | 0.51%   |
| Nvidia High Definition Audio Controller                                                           | 37        | 0.48%   |
| Intel Comet Lake PCH cAVS                                                                         | 36        | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1740      | 26.29%  |
| SK hynix            | 1395      | 21.08%  |
| Micron Technology   | 639       | 9.65%   |
| Kingston            | 602       | 9.1%    |
| Unknown             | 590       | 8.91%   |
| Elpida              | 290       | 4.38%   |
| Crucial             | 211       | 3.19%   |
| Ramaxel Technology  | 173       | 2.61%   |
| A-DATA Technology   | 167       | 2.52%   |
| Nanya Technology    | 125       | 1.89%   |
| Smart               | 110       | 1.66%   |
| Corsair             | 68        | 1.03%   |
| Unknown (ABCD)      | 55        | 0.83%   |
| Unknown             | 37        | 0.56%   |
| G.Skill             | 29        | 0.44%   |
| Teikon              | 28        | 0.42%   |
| ASint Technology    | 27        | 0.41%   |
| Patriot             | 23        | 0.35%   |
| Team                | 21        | 0.32%   |
| Transcend           | 20        | 0.3%    |
| High Bridge         | 20        | 0.3%    |
| AMD                 | 18        | 0.27%   |
| Apacer              | 17        | 0.26%   |
| Toshiba             | 16        | 0.24%   |
| Smart Brazil        | 15        | 0.23%   |
| GOODRAM             | 14        | 0.21%   |
| Qimonda             | 11        | 0.17%   |
| Avant               | 9         | 0.14%   |
| CSX                 | 8         | 0.12%   |
| Silicon Power       | 7         | 0.11%   |
| SHARETRONIC         | 7         | 0.11%   |
| PNY                 | 7         | 0.11%   |
| 48spaces            | 7         | 0.11%   |
| Multilaser          | 6         | 0.09%   |
| Timetec             | 5         | 0.08%   |
| Kingmax             | 5         | 0.08%   |
| Goldkey             | 5         | 0.08%   |
| V-GeN               | 4         | 0.06%   |
| Neo Forza           | 4         | 0.06%   |
| HT Micron           | 4         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 133       | 1.88%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 132       | 1.86%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 116       | 1.64%   |
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 116       | 1.64%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 110       | 1.55%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 103       | 1.45%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 94        | 1.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 94        | 1.33%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 92        | 1.3%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 89        | 1.25%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 69        | 0.97%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 66        | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 60        | 0.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 58        | 0.82%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 52        | 0.73%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 51        | 0.72%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 51        | 0.72%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 50        | 0.71%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 49        | 0.69%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 48        | 0.68%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 48        | 0.68%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 47        | 0.66%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 44        | 0.62%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 43        | 0.61%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 42        | 0.59%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 41        | 0.58%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 40        | 0.56%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 39        | 0.55%   |
| Micron RAM 4ATF51264HZ-2G3B1 4096MB SODIMM DDR4 2400MT/s         | 39        | 0.55%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 38        | 0.54%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 38        | 0.54%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 37        | 0.52%   |
| Unknown                                                          | 37        | 0.52%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 34        | 0.48%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 31        | 0.44%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 31        | 0.44%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 30        | 0.42%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 30        | 0.42%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 30        | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 29        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 2950      | 53.55%  |
| DDR4    | 1507      | 27.36%  |
| DDR2    | 522       | 9.48%   |
| SDRAM   | 192       | 3.49%   |
| LPDDR4  | 170       | 3.09%   |
| Unknown | 59        | 1.07%   |
| LPDDR3  | 51        | 0.93%   |
| DRAM    | 22        | 0.4%    |
| DDR     | 17        | 0.31%   |
| DDR5    | 15        | 0.27%   |
| LPDDR5  | 4         | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 5197      | 95.36%  |
| Row Of Chips | 201       | 3.69%   |
| Chip         | 23        | 0.42%   |
| DIMM         | 18        | 0.33%   |
| Unknown      | 11        | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 2713      | 44.35%  |
| 8192  | 1467      | 23.98%  |
| 2048  | 1407      | 23%     |
| 16384 | 239       | 3.91%   |
| 1024  | 239       | 3.91%   |
| 32768 | 41        | 0.67%   |
| 512   | 11        | 0.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 1883      | 30.72%  |
| 2667    | 772       | 12.6%   |
| 1334    | 582       | 9.5%    |
| 1333    | 455       | 7.42%   |
| 3200    | 428       | 6.98%   |
| 2400    | 414       | 6.75%   |
| 667     | 279       | 4.55%   |
| 1067    | 195       | 3.18%   |
| Unknown | 171       | 2.79%   |
| 2133    | 162       | 2.64%   |
| 800     | 144       | 2.35%   |
| 4199    | 110       | 1.79%   |
| 3266    | 94        | 1.53%   |
| 975     | 71        | 1.16%   |
| 2048    | 70        | 1.14%   |
| 1066    | 57        | 0.93%   |
| 1867    | 54        | 0.88%   |
| 533     | 41        | 0.67%   |
| 4267    | 31        | 0.51%   |
| 4266    | 22        | 0.36%   |
| 4800    | 16        | 0.26%   |
| 1866    | 16        | 0.26%   |
| 8400    | 13        | 0.21%   |
| 333     | 10        | 0.16%   |
| 1639    | 9         | 0.15%   |
| 6400    | 5         | 0.08%   |
| 3733    | 5         | 0.08%   |
| 2933    | 5         | 0.08%   |
| 400     | 3         | 0.05%   |
| 3000    | 2         | 0.03%   |
| 2267    | 2         | 0.03%   |
| 666     | 2         | 0.03%   |
| 266     | 2         | 0.03%   |
| 1776    | 1         | 0.02%   |
| 1596    | 1         | 0.02%   |
| 1200    | 1         | 0.02%   |
| 933     | 1         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 22        | 39.29%  |
| Canon                 | 13        | 23.21%  |
| Brother Industries    | 7         | 12.5%   |
| Samsung Electronics   | 6         | 10.71%  |
| Seiko Epson           | 5         | 8.93%   |
| Xerox                 | 1         | 1.79%   |
| Prolific Technology   | 1         | 1.79%   |
| Lexmark International | 1         | 1.79%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Brother DCP-7055W                       | 4         | 7.14%   |
| Samsung ML-1640 Series Laser Printer    | 2         | 3.57%   |
| HP LaserJet 1020                        | 2         | 3.57%   |
| HP ENVY Photo 6200 series               | 2         | 3.57%   |
| HP DeskJet 3630 series                  | 2         | 3.57%   |
| HP Deskjet 2050 J510                    | 2         | 3.57%   |
| Canon TR8500 series                     | 2         | 3.57%   |
| Canon PIXMA MG2500 Series               | 2         | 3.57%   |
| Xerox Phaser 6000B                      | 1         | 1.79%   |
| Seiko Epson L355 Series                 | 1         | 1.79%   |
| Seiko Epson L310 Series                 | 1         | 1.79%   |
| Seiko Epson L220 Series                 | 1         | 1.79%   |
| Seiko Epson L210 Series                 | 1         | 1.79%   |
| Seiko Epson ET-2710 Series              | 1         | 1.79%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 1.79%   |
| Samsung SCX-3400 Series                 | 1         | 1.79%   |
| Samsung M2070 Series                    | 1         | 1.79%   |
| Samsung CLP-325 Color Laser Printer     | 1         | 1.79%   |
| Prolific PL2305 Parallel Port           | 1         | 1.79%   |
| Lexmark International E360d             | 1         | 1.79%   |
| HP OfficeJet Pro 69                     | 1         | 1.79%   |
| HP OfficeJet 4300                       | 1         | 1.79%   |
| HP LaserJet P1102                       | 1         | 1.79%   |
| HP LaserJet 3055                        | 1         | 1.79%   |
| HP LaserJet 200 colorMFP M275nw         | 1         | 1.79%   |
| HP LaserJet 1018                        | 1         | 1.79%   |
| HP ENVY 6000 series                     | 1         | 1.79%   |
| HP ENVY 4520 series                     | 1         | 1.79%   |
| HP DeskJet D1360                        | 1         | 1.79%   |
| HP DeskJet 6122                         | 1         | 1.79%   |
| HP DeskJet 5820 series                  | 1         | 1.79%   |
| HP DeskJet 2620 All-in-One Printer      | 1         | 1.79%   |
| HP DeskJet 2300 series                  | 1         | 1.79%   |
| HP DeskJet 2130 series                  | 1         | 1.79%   |
| Canon PIXMA MP280                       | 1         | 1.79%   |
| Canon PIXMA MG3600 Series               | 1         | 1.79%   |
| Canon PIXMA MG3500 Series               | 1         | 1.79%   |
| Canon MP160                             | 1         | 1.79%   |
| Canon MF3010                            | 1         | 1.79%   |
| Canon LBP2900                           | 1         | 1.79%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 4         | 44.44%  |
| Seiko Epson     | 3         | 33.33%  |
| Hewlett-Packard | 2         | 22.22%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| HP ScanJet 5590                                          | 2         | 22.22%  |
| Canon CanoScan LiDE 110                                  | 2         | 22.22%  |
| Seiko Epson Scanner                                      | 1         | 11.11%  |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 1         | 11.11%  |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 11.11%  |
| Canon CanoScan N1240U/LiDE 30                            | 1         | 11.11%  |
| Canon CanoScan LiDE 600F                                 | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1274      | 27.59%  |
| Realtek Semiconductor                  | 394       | 8.53%   |
| IMC Networks                           | 382       | 8.27%   |
| Microdia                               | 373       | 8.08%   |
| Acer                                   | 328       | 7.1%    |
| Suyin                                  | 309       | 6.69%   |
| Sunplus Innovation Technology          | 232       | 5.02%   |
| Quanta                                 | 198       | 4.29%   |
| Cheng Uei Precision Industry (Foxlink) | 197       | 4.27%   |
| Syntek                                 | 154       | 3.34%   |
| Silicon Motion                         | 102       | 2.21%   |
| Lite-On Technology                     | 95        | 2.06%   |
| Ricoh                                  | 93        | 2.01%   |
| Alcor Micro                            | 76        | 1.65%   |
| Apple                                  | 70        | 1.52%   |
| Lenovo                                 | 49        | 1.06%   |
| Importek                               | 40        | 0.87%   |
| Primax Electronics                     | 33        | 0.71%   |
| ALi                                    | 33        | 0.71%   |
| Luxvisions Innotech Limited            | 29        | 0.63%   |
| Z-Star Microelectronics                | 19        | 0.41%   |
| DigiTech                               | 17        | 0.37%   |
| OmniVision Technologies                | 15        | 0.32%   |
| Sonix Technology                       | 13        | 0.28%   |
| Logitech                               | 13        | 0.28%   |
| DLEQNA19IFK6G2                         | 12        | 0.26%   |
| Bison Electronics                      | 8         | 0.17%   |
| Genesys Logic                          | 6         | 0.13%   |
| Sunplus Technology                     | 5         | 0.11%   |
| Samsung Electronics                    | 5         | 0.11%   |
| Intel                                  | 5         | 0.11%   |
| Cubeternet                             | 4         | 0.09%   |
| Nebraska Furniture Mart                | 3         | 0.06%   |
| GEMBIRD                                | 3         | 0.06%   |
| Foxconn / Hon Hai                      | 3         | 0.06%   |
| WaveRider Communications               | 2         | 0.04%   |
| Unknown                                | 2         | 0.04%   |
| SunplusIT                              | 2         | 0.04%   |
| Microsoft                              | 2         | 0.04%   |
| icSpring                               | 2         | 0.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 151       | 3.27%   |
| Chicony HD WebCam                                       | 138       | 2.99%   |
| Microdia Integrated_Webcam_HD                           | 104       | 2.25%   |
| Realtek Integrated_Webcam_HD                            | 90        | 1.95%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 85        | 1.84%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 74        | 1.6%    |
| Microdia Integrated Webcam                              | 65        | 1.41%   |
| Sunplus Integrated_Webcam_HD                            | 63        | 1.36%   |
| IMC Networks Integrated Camera                          | 60        | 1.3%    |
| Acer Integrated Camera                                  | 60        | 1.3%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 59        | 1.28%   |
| Chicony VGA Webcam                                      | 59        | 1.28%   |
| Syntek Integrated Camera                                | 57        | 1.23%   |
| Acer Lenovo EasyCamera                                  | 55        | 1.19%   |
| Chicony USB 2.0 Camera                                  | 52        | 1.12%   |
| Realtek USB Camera                                      | 48        | 1.04%   |
| Chicony TOSHIBA Web Camera - HD                         | 47        | 1.02%   |
| Chicony HP TrueVision HD                                | 47        | 1.02%   |
| Sunplus HD WebCam                                       | 46        | 1%      |
| Syntek Lenovo EasyCamera                                | 44        | 0.95%   |
| Chicony Lenovo EasyCamera                               | 42        | 0.91%   |
| Chicony USB2.0 HD UVC WebCam                            | 41        | 0.89%   |
| Suyin Integrated_Webcam_HD                              | 38        | 0.82%   |
| Lite-On Integrated Camera                               | 38        | 0.82%   |
| Chicony USB2.0 VGA UVC WebCam                           | 37        | 0.8%    |
| Chicony HP Truevision HD camera                         | 36        | 0.78%   |
| Acer Lenovo Integrated Webcam                           | 36        | 0.78%   |
| Chicony HP Webcam                                       | 35        | 0.76%   |
| Quanta VGA WebCam                                       | 33        | 0.71%   |
| Quanta HD User Facing                                   | 33        | 0.71%   |
| Chicony FJ Camera                                       | 33        | 0.71%   |
| Chicony EasyCamera                                      | 33        | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 32        | 0.69%   |
| Chicony HD User Facing                                  | 31        | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 31        | 0.67%   |
| Acer EasyCamera                                         | 31        | 0.67%   |
| IMC Networks UVC VGA Webcam                             | 30        | 0.65%   |
| Quanta HP Webcam                                        | 29        | 0.63%   |
| Apple FaceTime HD Camera                                | 29        | 0.63%   |
| Syntek EasyCamera                                       | 28        | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 236       | 39.27%  |
| AuthenTec                  | 97        | 16.14%  |
| Upek                       | 69        | 11.48%  |
| Synaptics                  | 49        | 8.15%   |
| Elan Microelectronics      | 46        | 7.65%   |
| Shenzhen Goodix Technology | 44        | 7.32%   |
| LighTuning Technology      | 30        | 4.99%   |
| STMicroelectronics         | 26        | 4.33%   |
| Focal-systems.Corp         | 2         | 0.33%   |
| Samsung Electronics        | 1         | 0.17%   |
| HOLTEK                     | 1         | 0.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 64        | 10.65%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 47        | 7.82%   |
| Shenzhen Goodix  FingerPrint Device                                        | 36        | 5.99%   |
| AuthenTec AES2810                                                          | 35        | 5.82%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 31        | 5.16%   |
| Elan ELAN:Fingerprint                                                      | 30        | 4.99%   |
| STMicroelectronics Fingerprint Reader                                      | 26        | 4.33%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 25        | 4.16%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 24        | 3.99%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 20        | 3.33%   |
| Validity Sensors VFS491                                                    | 20        | 3.33%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 20        | 3.33%   |
| Elan ELAN:ARM-M4                                                           | 16        | 2.66%   |
| AuthenTec AES1600                                                          | 16        | 2.66%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 13        | 2.16%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 13        | 2.16%   |
| AuthenTec Fingerprint Sensor                                               | 13        | 2.16%   |
| Validity Sensors Fingerprint scanner                                       | 12        | 2%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 12        | 2%      |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 12        | 2%      |
| Unknown                                                                    | 12        | 2%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 10        | 1.66%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 1.5%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 8         | 1.33%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 8         | 1.33%   |
| Synaptics  WBDI                                                            | 7         | 1.16%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 1%      |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.83%   |
| LighTuning Fingerprint Reader                                              | 5         | 0.83%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 0.83%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.67%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 0.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 0.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 0.67%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.67%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.5%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 0.5%    |
| Synaptics WBDI Device                                                      | 3         | 0.5%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.5%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 195       | 53.28%  |
| Alcor Micro           | 57        | 15.57%  |
| O2 Micro              | 45        | 12.3%   |
| Upek                  | 32        | 8.74%   |
| Lenovo                | 29        | 7.92%   |
| SCM Microsystems      | 3         | 0.82%   |
| Gemalto (was Gemplus) | 2         | 0.55%   |
| OmniKey               | 1         | 0.27%   |
| Microchip Technology  | 1         | 0.27%   |
| Hewlett-Packard       | 1         | 0.27%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 102       | 27.87%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 56        | 15.3%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 48        | 13.11%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 44        | 12.02%  |
| Broadcom 5880                                                                | 34        | 9.29%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 32        | 8.74%   |
| Lenovo Integrated Smart Card Reader                                          | 29        | 7.92%   |
| Broadcom 58200                                                               | 10        | 2.73%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 3         | 0.82%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.55%   |
| OmniKey CardMan 4321                                                         | 1         | 0.27%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.27%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.27%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.27%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.27%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.27%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 4170      | 75.75%  |
| 1     | 1131      | 20.54%  |
| 2     | 189       | 3.43%   |
| 3     | 14        | 0.25%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 601       | 39.18%  |
| Chipcard                 | 358       | 23.34%  |
| Graphics card            | 228       | 14.86%  |
| Net/wireless             | 97        | 6.32%   |
| Bluetooth                | 83        | 5.41%   |
| Storage                  | 66        | 4.3%    |
| Multimedia controller    | 39        | 2.54%   |
| Camera                   | 29        | 1.89%   |
| Communication controller | 11        | 0.72%   |
| Sound                    | 7         | 0.46%   |
| Network                  | 5         | 0.33%   |
| Flash memory             | 5         | 0.33%   |
| Card reader              | 3         | 0.2%    |
| Net/ethernet             | 1         | 0.07%   |
| Modem                    | 1         | 0.07%   |


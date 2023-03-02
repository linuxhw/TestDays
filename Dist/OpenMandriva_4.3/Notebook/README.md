OpenMandriva 4.3 - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 4.3.

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

Total: 2049

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire V3-772               | [5a0c297e10](https://linux-hardware.org/?probe=5a0c297e10) | Feb 28, 2023 |
| Dell          | Latitude E6420              | [a84f4dbcbb](https://linux-hardware.org/?probe=a84f4dbcbb) | Feb 28, 2023 |
| ASUSTek       | K75VJ                       | [7fc0fff829](https://linux-hardware.org/?probe=7fc0fff829) | Feb 27, 2023 |
| Acer          | Aspire E5-571               | [5f035002e1](https://linux-hardware.org/?probe=5f035002e1) | Feb 27, 2023 |
| eMachines     | eME728                      | [2331984fc8](https://linux-hardware.org/?probe=2331984fc8) | Feb 26, 2023 |
| Samsung       | 550XBE/350XBE               | [d9f49e98fd](https://linux-hardware.org/?probe=d9f49e98fd) | Feb 25, 2023 |
| Toshiba       | Satellite C850              | [99d4efbb52](https://linux-hardware.org/?probe=99d4efbb52) | Feb 25, 2023 |
| HP            | 650                         | [ab0b350259](https://linux-hardware.org/?probe=ab0b350259) | Feb 24, 2023 |
| Acer          | Aspire A517-51G             | [12040fcd10](https://linux-hardware.org/?probe=12040fcd10) | Feb 24, 2023 |
| Toshiba       | Satellite C850-1GF          | [f568855409](https://linux-hardware.org/?probe=f568855409) | Feb 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [d488fc0d9a](https://linux-hardware.org/?probe=d488fc0d9a) | Feb 22, 2023 |
| Positivo      | S14SL01                     | [914a9e691e](https://linux-hardware.org/?probe=914a9e691e) | Feb 22, 2023 |
| Lenovo        | ThinkPad T430s 23551M9      | [91b6a109b4](https://linux-hardware.org/?probe=91b6a109b4) | Feb 22, 2023 |
| Gateway       | NV53A                       | [1e2b4ec4d3](https://linux-hardware.org/?probe=1e2b4ec4d3) | Feb 22, 2023 |
| Fujitsu Si... | AMILO Li3910                | [28890c5346](https://linux-hardware.org/?probe=28890c5346) | Feb 21, 2023 |
| HP            | Pavilion dv6                | [526430f218](https://linux-hardware.org/?probe=526430f218) | Feb 21, 2023 |
| Apple         | MacBookPro9,2               | [80df77e6a1](https://linux-hardware.org/?probe=80df77e6a1) | Feb 21, 2023 |
| Lenovo        | B560 43308VG                | [c30b594458](https://linux-hardware.org/?probe=c30b594458) | Feb 19, 2023 |
| HP            | ProBook 4520s               | [8192287499](https://linux-hardware.org/?probe=8192287499) | Feb 19, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [b0941b8ef0](https://linux-hardware.org/?probe=b0941b8ef0) | Feb 18, 2023 |
| HP            | 15                          | [4db2520843](https://linux-hardware.org/?probe=4db2520843) | Feb 18, 2023 |
| HP            | ProBook 4540s               | [cc3e78f73f](https://linux-hardware.org/?probe=cc3e78f73f) | Feb 18, 2023 |
| PC Special... | NJ50_70CU                   | [68dd853397](https://linux-hardware.org/?probe=68dd853397) | Feb 17, 2023 |
| ASUSTek       | X555LJ                      | [a524479b7a](https://linux-hardware.org/?probe=a524479b7a) | Feb 17, 2023 |
| Toshiba       | Satellite C70-C-18E         | [7642482909](https://linux-hardware.org/?probe=7642482909) | Feb 17, 2023 |
| HP            | Pavilion 15                 | [a48098f6fc](https://linux-hardware.org/?probe=a48098f6fc) | Feb 17, 2023 |
| HP            | Laptop 15-da0xxx            | [ac458108b4](https://linux-hardware.org/?probe=ac458108b4) | Feb 17, 2023 |
| ASUSTek       | K54C                        | [ea944628df](https://linux-hardware.org/?probe=ea944628df) | Feb 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [66c33604c4](https://linux-hardware.org/?probe=66c33604c4) | Feb 17, 2023 |
| Samsung       | R519/R719                   | [1dc4bc1b72](https://linux-hardware.org/?probe=1dc4bc1b72) | Feb 17, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [ffd622d65f](https://linux-hardware.org/?probe=ffd622d65f) | Feb 17, 2023 |
| eMachines     | eMachiens G443              | [096a4bb9e4](https://linux-hardware.org/?probe=096a4bb9e4) | Feb 16, 2023 |
| HP            | Pavilion dv6500             | [95a9115968](https://linux-hardware.org/?probe=95a9115968) | Feb 16, 2023 |
| ASUSTek       | N76VZ                       | [ed9bd6b127](https://linux-hardware.org/?probe=ed9bd6b127) | Feb 16, 2023 |
| Dell          | Latitude E7440              | [86f8d34ba7](https://linux-hardware.org/?probe=86f8d34ba7) | Feb 16, 2023 |
| Toshiba       | dynabook R73/BN             | [df7e69c5c4](https://linux-hardware.org/?probe=df7e69c5c4) | Feb 16, 2023 |
| HP            | ProBook 470 G4              | [8730091665](https://linux-hardware.org/?probe=8730091665) | Feb 15, 2023 |
| HP            | Notebook                    | [21442c303e](https://linux-hardware.org/?probe=21442c303e) | Feb 15, 2023 |
| HP            | 250 G6 Notebook PC          | [745ae4d0fb](https://linux-hardware.org/?probe=745ae4d0fb) | Feb 15, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [bc69f33fa2](https://linux-hardware.org/?probe=bc69f33fa2) | Feb 15, 2023 |
| ASUSTek       | K52N                        | [f87ece85e9](https://linux-hardware.org/?probe=f87ece85e9) | Feb 15, 2023 |
| HP            | 1000                        | [57de0f3103](https://linux-hardware.org/?probe=57de0f3103) | Feb 15, 2023 |
| Samsung       | RV419/RV420                 | [7ec9e518c4](https://linux-hardware.org/?probe=7ec9e518c4) | Feb 14, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [dddbb2d135](https://linux-hardware.org/?probe=dddbb2d135) | Feb 14, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [bf015f98c2](https://linux-hardware.org/?probe=bf015f98c2) | Feb 14, 2023 |
| Apple         | MacBookAir5,2               | [4f99163f99](https://linux-hardware.org/?probe=4f99163f99) | Feb 11, 2023 |
| ASUSTek       | UX31E                       | [e8fdc1676a](https://linux-hardware.org/?probe=e8fdc1676a) | Feb 10, 2023 |
| HP            | Compaq Presario CQ61        | [df4d59acd5](https://linux-hardware.org/?probe=df4d59acd5) | Feb 07, 2023 |
| Lenovo        | ThinkPad X240 20AL00FMGE    | [0ac2678512](https://linux-hardware.org/?probe=0ac2678512) | Feb 06, 2023 |
| Acer          | Extensa 5635                | [8f8f4d24f9](https://linux-hardware.org/?probe=8f8f4d24f9) | Feb 06, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [7ca566f68b](https://linux-hardware.org/?probe=7ca566f68b) | Feb 05, 2023 |
| Apple         | MacBookPro8,1               | [d6adca1255](https://linux-hardware.org/?probe=d6adca1255) | Feb 04, 2023 |
| HP            | ProBook 6465b               | [00b2021fae](https://linux-hardware.org/?probe=00b2021fae) | Feb 04, 2023 |
| Dell          | Latitude E5420              | [ccc3ca9853](https://linux-hardware.org/?probe=ccc3ca9853) | Jan 31, 2023 |
| HP            | 3115-AEC13432GR1            | [98eb70341a](https://linux-hardware.org/?probe=98eb70341a) | Jan 30, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [e2fa9aa820](https://linux-hardware.org/?probe=e2fa9aa820) | Jan 29, 2023 |
| HP            | Notebook                    | [d38e078368](https://linux-hardware.org/?probe=d38e078368) | Jan 28, 2023 |
| Apple         | MacBook4,1                  | [e00443a9cc](https://linux-hardware.org/?probe=e00443a9cc) | Jan 27, 2023 |
| ASUSTek       | UX31E                       | [d87ac57c19](https://linux-hardware.org/?probe=d87ac57c19) | Jan 27, 2023 |
| HP            | 14                          | [53d080d83a](https://linux-hardware.org/?probe=53d080d83a) | Jan 27, 2023 |
| Dell          | Inspiron 15 3521            | [41f89081ff](https://linux-hardware.org/?probe=41f89081ff) | Jan 26, 2023 |
| OEGStone      | C4100/C5100                 | [4365b7b231](https://linux-hardware.org/?probe=4365b7b231) | Jan 25, 2023 |
| Lenovo        | ThinkPad W541 20EF0020MD    | [fca73ad2a9](https://linux-hardware.org/?probe=fca73ad2a9) | Jan 24, 2023 |
| Packard Be... | PB56                        | [f26fcb7ee5](https://linux-hardware.org/?probe=f26fcb7ee5) | Jan 23, 2023 |
| HP            | Pavilion dv5                | [94ba65752b](https://linux-hardware.org/?probe=94ba65752b) | Jan 20, 2023 |
| Panasonic     | CF-53JULCV1M                | [89c1166efc](https://linux-hardware.org/?probe=89c1166efc) | Jan 18, 2023 |
| Dell          | Inspiron N5110              | [bf606ed50a](https://linux-hardware.org/?probe=bf606ed50a) | Jan 18, 2023 |
| HP            | ProBook 440 G1              | [035c7a4e2d](https://linux-hardware.org/?probe=035c7a4e2d) | Jan 18, 2023 |
| Dell          | Latitude 7490               | [b611fc6b64](https://linux-hardware.org/?probe=b611fc6b64) | Jan 18, 2023 |
| HP            | Pavilion dv6500             | [33985f088a](https://linux-hardware.org/?probe=33985f088a) | Jan 16, 2023 |
| HP            | EliteBook 745 G3            | [c20a339ddb](https://linux-hardware.org/?probe=c20a339ddb) | Jan 15, 2023 |
| Acer          | Aspire 7551                 | [b3e5df94f4](https://linux-hardware.org/?probe=b3e5df94f4) | Jan 15, 2023 |
| Dell          | Latitude E7440              | [9c4aac8b46](https://linux-hardware.org/?probe=9c4aac8b46) | Jan 14, 2023 |
| ASUSTek       | UX31E                       | [d60bab803e](https://linux-hardware.org/?probe=d60bab803e) | Jan 13, 2023 |
| Toshiba       | Satellite C850-B561         | [562d6cde14](https://linux-hardware.org/?probe=562d6cde14) | Jan 11, 2023 |
| Lenovo        | ThinkPad X240 20AM001RGE    | [f4aafcf7a9](https://linux-hardware.org/?probe=f4aafcf7a9) | Jan 11, 2023 |
| Apple         | MacBookAir5,1               | [ce911686b3](https://linux-hardware.org/?probe=ce911686b3) | Jan 10, 2023 |
| Dell          | XPS M1330                   | [e3d66114f6](https://linux-hardware.org/?probe=e3d66114f6) | Jan 10, 2023 |
| Dell          | Inspiron 3442               | [f540a5f964](https://linux-hardware.org/?probe=f540a5f964) | Jan 09, 2023 |
| Star Labs     | Lite                        | [6614e226df](https://linux-hardware.org/?probe=6614e226df) | Jan 09, 2023 |
| HP            | OMEN by Laptop              | [84aa790d17](https://linux-hardware.org/?probe=84aa790d17) | Jan 09, 2023 |
| Dell          | Latitude E6400              | [70bce3a55c](https://linux-hardware.org/?probe=70bce3a55c) | Jan 08, 2023 |
| Dell          | Latitude E5440              | [91bedeb5e1](https://linux-hardware.org/?probe=91bedeb5e1) | Jan 07, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [782467ee8c](https://linux-hardware.org/?probe=782467ee8c) | Jan 07, 2023 |
| Acer          | Aspire 7741                 | [d0e4567b4a](https://linux-hardware.org/?probe=d0e4567b4a) | Jan 07, 2023 |
| Lenovo        | V15-IGL 82C3                | [3bc9e3b318](https://linux-hardware.org/?probe=3bc9e3b318) | Jan 07, 2023 |
| HP            | 250 G3                      | [227b44bf7c](https://linux-hardware.org/?probe=227b44bf7c) | Jan 06, 2023 |
| HP            | Laptop 15-db0xxx            | [0232b39536](https://linux-hardware.org/?probe=0232b39536) | Jan 06, 2023 |
| eMachines     | E725                        | [0655d63f70](https://linux-hardware.org/?probe=0655d63f70) | Jan 06, 2023 |
| ASUSTek       | K55VM                       | [d4d53ed49f](https://linux-hardware.org/?probe=d4d53ed49f) | Jan 04, 2023 |
| HP            | Pavilion g6                 | [6cae064dc5](https://linux-hardware.org/?probe=6cae064dc5) | Jan 04, 2023 |
| HP            | ProBook 470 G2              | [1f62ff6417](https://linux-hardware.org/?probe=1f62ff6417) | Jan 04, 2023 |
| HP            | Compaq 15                   | [c282ede7c5](https://linux-hardware.org/?probe=c282ede7c5) | Jan 04, 2023 |
| HP            | EliteBook 725 G3            | [174e0c5f05](https://linux-hardware.org/?probe=174e0c5f05) | Jan 04, 2023 |
| Dell          | Latitude D520               | [7f05ddf105](https://linux-hardware.org/?probe=7f05ddf105) | Jan 04, 2023 |
| Dell          | Latitude 7490               | [7e445638b6](https://linux-hardware.org/?probe=7e445638b6) | Jan 04, 2023 |
| Sony          | VJF153                      | [f3643923cc](https://linux-hardware.org/?probe=f3643923cc) | Jan 04, 2023 |
| Acer          | Nitro AN515-55              | [c5bc3a8eae](https://linux-hardware.org/?probe=c5bc3a8eae) | Jan 03, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [a73ca839a1](https://linux-hardware.org/?probe=a73ca839a1) | Jan 03, 2023 |
| Positivo      | Z100                        | [58b7c4d1ff](https://linux-hardware.org/?probe=58b7c4d1ff) | Jan 02, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [287840d797](https://linux-hardware.org/?probe=287840d797) | Jan 02, 2023 |
| Acer          | Aspire 5732Z                | [86b79bce9e](https://linux-hardware.org/?probe=86b79bce9e) | Jan 01, 2023 |
| Dell          | System Inspiron N411Z       | [21f279751c](https://linux-hardware.org/?probe=21f279751c) | Jan 01, 2023 |
| Packard Be... | EasyNote TM97               | [fad44d67ab](https://linux-hardware.org/?probe=fad44d67ab) | Jan 01, 2023 |
| HP            | 1000                        | [5634ff72b1](https://linux-hardware.org/?probe=5634ff72b1) | Jan 01, 2023 |
| Acer          | Aspire A114-33              | [bba53b0159](https://linux-hardware.org/?probe=bba53b0159) | Jan 01, 2023 |
| Toshiba       | Satellite A305D             | [b85a377462](https://linux-hardware.org/?probe=b85a377462) | Dec 31, 2022 |
| Lenovo        | ThinkPad T410 2537BF9       | [f83ed1dd39](https://linux-hardware.org/?probe=f83ed1dd39) | Dec 30, 2022 |
| ASUSTek       | TP501UA                     | [1f2aaf8804](https://linux-hardware.org/?probe=1f2aaf8804) | Dec 30, 2022 |
| ASUSTek       | K55VD                       | [e4c90250df](https://linux-hardware.org/?probe=e4c90250df) | Dec 30, 2022 |
| ASUSTek       | X555UJ                      | [f4ba8643aa](https://linux-hardware.org/?probe=f4ba8643aa) | Dec 30, 2022 |
| Acer          | Nitro AN515-57              | [b0bfa9530a](https://linux-hardware.org/?probe=b0bfa9530a) | Dec 29, 2022 |
| ASUSTek       | G1                          | [1f8e426f96](https://linux-hardware.org/?probe=1f8e426f96) | Dec 29, 2022 |
| HP            | Notebook                    | [91bc85bf6e](https://linux-hardware.org/?probe=91bc85bf6e) | Dec 29, 2022 |
| Samsung       | NB30/N146                   | [7f9b976789](https://linux-hardware.org/?probe=7f9b976789) | Dec 29, 2022 |
| Fujitsu       | LIFEBOOK P702               | [4734f4370b](https://linux-hardware.org/?probe=4734f4370b) | Dec 28, 2022 |
| Lenovo        | V560                        | [f937de4c61](https://linux-hardware.org/?probe=f937de4c61) | Dec 28, 2022 |
| HP            | Compaq Presario CQ60        | [92ece593f5](https://linux-hardware.org/?probe=92ece593f5) | Dec 28, 2022 |
| HP            | EliteBook 820 G2            | [bd56ec4f01](https://linux-hardware.org/?probe=bd56ec4f01) | Dec 28, 2022 |
| Acer          | Aspire E5-573G              | [6e1255aa44](https://linux-hardware.org/?probe=6e1255aa44) | Dec 28, 2022 |
| Positivo      | Hendrix                     | [55aa2f92d7](https://linux-hardware.org/?probe=55aa2f92d7) | Dec 27, 2022 |
| Dell          | Latitude 7480               | [45b0f992f6](https://linux-hardware.org/?probe=45b0f992f6) | Dec 27, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [7a3513a2e1](https://linux-hardware.org/?probe=7a3513a2e1) | Dec 27, 2022 |
| Acer          | Nitro AN515-44              | [58b02cceb0](https://linux-hardware.org/?probe=58b02cceb0) | Dec 27, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [9e6b5e5ebf](https://linux-hardware.org/?probe=9e6b5e5ebf) | Dec 27, 2022 |
| Acer          | Nitro AN515-57              | [8ecb7e11b3](https://linux-hardware.org/?probe=8ecb7e11b3) | Dec 26, 2022 |
| Samsung       | 270E5G/270E5U               | [705baed85a](https://linux-hardware.org/?probe=705baed85a) | Dec 26, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [6703f01cfc](https://linux-hardware.org/?probe=6703f01cfc) | Dec 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34604... | [dfb555f802](https://linux-hardware.org/?probe=dfb555f802) | Dec 26, 2022 |
| Acer          | Aspire A315-53              | [e012bb5bc1](https://linux-hardware.org/?probe=e012bb5bc1) | Dec 25, 2022 |
| ASUSTek       | M51Tr                       | [dffa412a98](https://linux-hardware.org/?probe=dffa412a98) | Dec 25, 2022 |
| Dell          | G7 7790                     | [da767d5fd4](https://linux-hardware.org/?probe=da767d5fd4) | Dec 24, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [8c835888d6](https://linux-hardware.org/?probe=8c835888d6) | Dec 24, 2022 |
| ASUSTek       | UX31E                       | [08a1ad1c63](https://linux-hardware.org/?probe=08a1ad1c63) | Dec 24, 2022 |
| Acer          | Aspire A315-21G             | [435933801a](https://linux-hardware.org/?probe=435933801a) | Dec 24, 2022 |
| Acer          | Aspire VX5-591G             | [f2e0369ba1](https://linux-hardware.org/?probe=f2e0369ba1) | Dec 24, 2022 |
| Positivo      | Mobile                      | [6031910e64](https://linux-hardware.org/?probe=6031910e64) | Dec 24, 2022 |
| Lenovo        | ThinkPad SL 2746N8G         | [f540a3a892](https://linux-hardware.org/?probe=f540a3a892) | Dec 23, 2022 |
| Positivo      | H14BT58                     | [9914219613](https://linux-hardware.org/?probe=9914219613) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [beb602dcf6](https://linux-hardware.org/?probe=beb602dcf6) | Dec 23, 2022 |
| ASUSTek       | K53SC                       | [5105f25e5e](https://linux-hardware.org/?probe=5105f25e5e) | Dec 23, 2022 |
| Apple         | MacBookAir7,2               | [00e62a7231](https://linux-hardware.org/?probe=00e62a7231) | Dec 23, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [791ace450e](https://linux-hardware.org/?probe=791ace450e) | Dec 23, 2022 |
| Dell          | Latitude 5280               | [59002e923b](https://linux-hardware.org/?probe=59002e923b) | Dec 22, 2022 |
| HP            | Pavilion dv9000 (RR329EA... | [6fc7281f2f](https://linux-hardware.org/?probe=6fc7281f2f) | Dec 22, 2022 |
| ASUSTek       | 1015BXO                     | [7cce9a65ec](https://linux-hardware.org/?probe=7cce9a65ec) | Dec 22, 2022 |
| Toshiba       | Satellite C55-B             | [8f81c02bbf](https://linux-hardware.org/?probe=8f81c02bbf) | Dec 21, 2022 |
| Acer          | Aspire 5336                 | [9724b5d705](https://linux-hardware.org/?probe=9724b5d705) | Dec 20, 2022 |
| RM Educati... | RM                          | [758b521362](https://linux-hardware.org/?probe=758b521362) | Dec 20, 2022 |
| Lenovo        | ThinkPad W510 4318CTO       | [215feb2d5e](https://linux-hardware.org/?probe=215feb2d5e) | Dec 20, 2022 |
| MSI           | GE62 6QD                    | [20d959e778](https://linux-hardware.org/?probe=20d959e778) | Dec 19, 2022 |
| LG Electro... | 17Z90P-G.AA56F              | [fa43417151](https://linux-hardware.org/?probe=fa43417151) | Dec 19, 2022 |
| Toshiba       | EQUIUM A300D                | [ffde5ccef4](https://linux-hardware.org/?probe=ffde5ccef4) | Dec 19, 2022 |
| ASUSTek       | X555LD                      | [d1d5c6a19e](https://linux-hardware.org/?probe=d1d5c6a19e) | Dec 19, 2022 |
| ASUSTek       | UX31E                       | [4f41f354cd](https://linux-hardware.org/?probe=4f41f354cd) | Dec 18, 2022 |
| Dell          | Latitude E6330              | [ca6551bf8e](https://linux-hardware.org/?probe=ca6551bf8e) | Dec 17, 2022 |
| Notebook      | W65_67SZ                    | [770c00f7d9](https://linux-hardware.org/?probe=770c00f7d9) | Dec 17, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [0d7a54bc21](https://linux-hardware.org/?probe=0d7a54bc21) | Dec 16, 2022 |
| Lenovo        | Yoga 2-11 20332             | [92a038a164](https://linux-hardware.org/?probe=92a038a164) | Dec 16, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [04cc986bf6](https://linux-hardware.org/?probe=04cc986bf6) | Dec 15, 2022 |
| Lenovo        | B590 20206                  | [b2b98c19da](https://linux-hardware.org/?probe=b2b98c19da) | Dec 15, 2022 |
| ASUSTek       | K40IJ                       | [191b6ded65](https://linux-hardware.org/?probe=191b6ded65) | Dec 15, 2022 |
| Lenovo        | ThinkPad X230 23245QP       | [e525a77c95](https://linux-hardware.org/?probe=e525a77c95) | Dec 15, 2022 |
| Lenovo        | G460 20041                  | [b76fa704f7](https://linux-hardware.org/?probe=b76fa704f7) | Dec 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [259226594a](https://linux-hardware.org/?probe=259226594a) | Dec 14, 2022 |
| Dell          | Inspiron 11 - 3147          | [d5aa2c3900](https://linux-hardware.org/?probe=d5aa2c3900) | Dec 14, 2022 |
| Dell          | Latitude E7250              | [3e40466ae4](https://linux-hardware.org/?probe=3e40466ae4) | Dec 13, 2022 |
| HP            | Pavilion 15                 | [5d88eed564](https://linux-hardware.org/?probe=5d88eed564) | Dec 13, 2022 |
| HP            | Notebook                    | [07b9e8995f](https://linux-hardware.org/?probe=07b9e8995f) | Dec 12, 2022 |
| ASUSTek       | UX31E                       | [651fa58fbd](https://linux-hardware.org/?probe=651fa58fbd) | Dec 12, 2022 |
| MSI           | GS65 Stealth Thin 8RF       | [074195107c](https://linux-hardware.org/?probe=074195107c) | Dec 12, 2022 |
| Lenovo        | IdeaPad Z580                | [4784b53f14](https://linux-hardware.org/?probe=4784b53f14) | Dec 12, 2022 |
| HP            | Laptop 15-bw0xx             | [1d2ea30fb2](https://linux-hardware.org/?probe=1d2ea30fb2) | Dec 11, 2022 |
| HP            | 650                         | [9bb3729969](https://linux-hardware.org/?probe=9bb3729969) | Dec 11, 2022 |
| Acer          | Aspire V5-573               | [1d88db5ee2](https://linux-hardware.org/?probe=1d88db5ee2) | Dec 10, 2022 |
| Sony          | VGN-FZ31Z                   | [4f392d3575](https://linux-hardware.org/?probe=4f392d3575) | Dec 10, 2022 |
| Acer          | Aspire E1-571G              | [344383d85d](https://linux-hardware.org/?probe=344383d85d) | Dec 10, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [e0584a11c0](https://linux-hardware.org/?probe=e0584a11c0) | Dec 10, 2022 |
| Positivo      | Mobile                      | [bc5f4e6c85](https://linux-hardware.org/?probe=bc5f4e6c85) | Dec 09, 2022 |
| Acer          | TravelMate 5720             | [d0a54f621e](https://linux-hardware.org/?probe=d0a54f621e) | Dec 09, 2022 |
| Acer          | Aspire A515-52              | [99e671f55f](https://linux-hardware.org/?probe=99e671f55f) | Dec 09, 2022 |
| HP            | 15                          | [20dfd7b8f5](https://linux-hardware.org/?probe=20dfd7b8f5) | Dec 08, 2022 |
| Packard Be... | DOT S                       | [753f17a658](https://linux-hardware.org/?probe=753f17a658) | Dec 08, 2022 |
| Lenovo        | ThinkPad L530 24783R8       | [406c066d36](https://linux-hardware.org/?probe=406c066d36) | Dec 08, 2022 |
| ASUSTek       | K55VD                       | [469f0a1d1f](https://linux-hardware.org/?probe=469f0a1d1f) | Dec 07, 2022 |
| Acer          | Aspire A315-51              | [3ab56a93d6](https://linux-hardware.org/?probe=3ab56a93d6) | Dec 07, 2022 |
| Toshiba       | Satellite C855              | [1a35ba24c1](https://linux-hardware.org/?probe=1a35ba24c1) | Dec 07, 2022 |
| ASUSTek       | K53SV                       | [a745b1ead9](https://linux-hardware.org/?probe=a745b1ead9) | Dec 07, 2022 |
| Positivo      | H14BT58                     | [c038df5c8c](https://linux-hardware.org/?probe=c038df5c8c) | Dec 07, 2022 |
| Toshiba       | Satellite L655              | [741c3e22b7](https://linux-hardware.org/?probe=741c3e22b7) | Dec 06, 2022 |
| Acer          | Nitro AN515-57              | [b0bc15145c](https://linux-hardware.org/?probe=b0bc15145c) | Dec 06, 2022 |
| HP            | 15                          | [e5a0cdc9de](https://linux-hardware.org/?probe=e5a0cdc9de) | Dec 06, 2022 |
| Dell          | Latitude E6540              | [20786b000c](https://linux-hardware.org/?probe=20786b000c) | Dec 05, 2022 |
| HP            | Pavilion dv6000 (RV009UA... | [6dcd661136](https://linux-hardware.org/?probe=6dcd661136) | Dec 05, 2022 |
| MSI           | GF63 Thin 9RCX              | [1bf4364f61](https://linux-hardware.org/?probe=1bf4364f61) | Dec 05, 2022 |
| Sony          | VPCEL2S1E                   | [0c98b9d570](https://linux-hardware.org/?probe=0c98b9d570) | Dec 04, 2022 |
| Apple         | MacBookAir6,1               | [af63449087](https://linux-hardware.org/?probe=af63449087) | Dec 04, 2022 |
| Lenovo        | G770 20089                  | [d35d60f972](https://linux-hardware.org/?probe=d35d60f972) | Dec 04, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [fd9114a304](https://linux-hardware.org/?probe=fd9114a304) | Dec 04, 2022 |
| ASUSTek       | UX31E                       | [7bde8b90c7](https://linux-hardware.org/?probe=7bde8b90c7) | Dec 04, 2022 |
| Sony          | VGN-NW31JF_S                | [ebfbfb034a](https://linux-hardware.org/?probe=ebfbfb034a) | Dec 04, 2022 |
| ASUSTek       | K42F                        | [05ddce411d](https://linux-hardware.org/?probe=05ddce411d) | Dec 04, 2022 |
| Acer          | Aspire 5750                 | [bfe28498bd](https://linux-hardware.org/?probe=bfe28498bd) | Dec 04, 2022 |
| Dell          | Latitude E5510              | [6027856ab6](https://linux-hardware.org/?probe=6027856ab6) | Dec 03, 2022 |
| HP            | ProBook 4530s               | [f8f94617e8](https://linux-hardware.org/?probe=f8f94617e8) | Dec 03, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [78f2f440eb](https://linux-hardware.org/?probe=78f2f440eb) | Dec 02, 2022 |
| ASUSTek       | X550CL                      | [8a2aad437e](https://linux-hardware.org/?probe=8a2aad437e) | Dec 02, 2022 |
| Dell          | Latitude E6420              | [011df4cb7f](https://linux-hardware.org/?probe=011df4cb7f) | Dec 02, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [929550dc41](https://linux-hardware.org/?probe=929550dc41) | Dec 01, 2022 |
| Lenovo        | ThinkPad T530 24297ZG       | [422f84a794](https://linux-hardware.org/?probe=422f84a794) | Nov 30, 2022 |
| Samsung       | 550XDA                      | [7614fde301](https://linux-hardware.org/?probe=7614fde301) | Nov 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [9505f905e8](https://linux-hardware.org/?probe=9505f905e8) | Nov 30, 2022 |
| Dell          | Inspiron 5423               | [db57850733](https://linux-hardware.org/?probe=db57850733) | Nov 29, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [1a742c23df](https://linux-hardware.org/?probe=1a742c23df) | Nov 29, 2022 |
| Toshiba       | Satellite L40               | [fa36933936](https://linux-hardware.org/?probe=fa36933936) | Nov 29, 2022 |
| Apple         | MacBookPro12,1              | [f03f3a9325](https://linux-hardware.org/?probe=f03f3a9325) | Nov 29, 2022 |
| Dell          | Inspiron 15-3567            | [20219ca82a](https://linux-hardware.org/?probe=20219ca82a) | Nov 29, 2022 |
| HP            | 255 G7 Notebook PC          | [0bd83a29f4](https://linux-hardware.org/?probe=0bd83a29f4) | Nov 29, 2022 |
| ASUSTek       | UX31E                       | [97c63f232d](https://linux-hardware.org/?probe=97c63f232d) | Nov 28, 2022 |
| Toshiba       | Satellite L875              | [2d5e211d72](https://linux-hardware.org/?probe=2d5e211d72) | Nov 28, 2022 |
| Toshiba       | PORTEGE Z30t-A              | [8af94993bd](https://linux-hardware.org/?probe=8af94993bd) | Nov 28, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [51d2b67ca3](https://linux-hardware.org/?probe=51d2b67ca3) | Nov 28, 2022 |
| Medion        | E11201                      | [0838f9db75](https://linux-hardware.org/?probe=0838f9db75) | Nov 27, 2022 |
| Gateway       | M-1631U                     | [f0f0517dab](https://linux-hardware.org/?probe=f0f0517dab) | Nov 27, 2022 |
| Lenovo        | 3000 N500 42336DS           | [f3d917b782](https://linux-hardware.org/?probe=f3d917b782) | Nov 26, 2022 |
| ASUSTek       | X550CL                      | [06c7fdf5c9](https://linux-hardware.org/?probe=06c7fdf5c9) | Nov 26, 2022 |
| Dell          | Latitude E6220              | [aa8d2d2fc7](https://linux-hardware.org/?probe=aa8d2d2fc7) | Nov 26, 2022 |
| Dell          | Inspiron MP061              | [d70d7496df](https://linux-hardware.org/?probe=d70d7496df) | Nov 26, 2022 |
| Acer          | Aspire A315-42              | [3413fb7947](https://linux-hardware.org/?probe=3413fb7947) | Nov 26, 2022 |
| Acer          | NC-ES1-512-C3AH             | [0670f9ed15](https://linux-hardware.org/?probe=0670f9ed15) | Nov 25, 2022 |
| Lenovo        | B590 20208                  | [9f49ff06cf](https://linux-hardware.org/?probe=9f49ff06cf) | Nov 24, 2022 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [418849100f](https://linux-hardware.org/?probe=418849100f) | Nov 24, 2022 |
| HP            | 650                         | [15c69c43ca](https://linux-hardware.org/?probe=15c69c43ca) | Nov 24, 2022 |
| HP            | EliteBook 8560p             | [e7bf51183d](https://linux-hardware.org/?probe=e7bf51183d) | Nov 24, 2022 |
| HP            | ProBook 430 G3              | [0fa29b61e3](https://linux-hardware.org/?probe=0fa29b61e3) | Nov 24, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [600e3f0f09](https://linux-hardware.org/?probe=600e3f0f09) | Nov 24, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [adcb4db30d](https://linux-hardware.org/?probe=adcb4db30d) | Nov 24, 2022 |
| Unknown       | Unknown                     | [9b50d75b30](https://linux-hardware.org/?probe=9b50d75b30) | Nov 24, 2022 |
| Lenovo        | ThinkPad T420 4180GH5       | [8dba4b2123](https://linux-hardware.org/?probe=8dba4b2123) | Nov 23, 2022 |
| Sony          | VPCEG16EG                   | [ee22559858](https://linux-hardware.org/?probe=ee22559858) | Nov 23, 2022 |
| HP            | Notebook                    | [616c071073](https://linux-hardware.org/?probe=616c071073) | Nov 23, 2022 |
| Apple         | MacBookPro12,1              | [063ffbb0e8](https://linux-hardware.org/?probe=063ffbb0e8) | Nov 23, 2022 |
| Lenovo        | IdeaPad U310 Touch          | [09beadc5ae](https://linux-hardware.org/?probe=09beadc5ae) | Nov 22, 2022 |
| Intel         | powered classmate PC        | [d74f69f66a](https://linux-hardware.org/?probe=d74f69f66a) | Nov 22, 2022 |
| Lenovo        | ThinkPad R500 2716AZJ       | [ecf18761e4](https://linux-hardware.org/?probe=ecf18761e4) | Nov 22, 2022 |
| Dell          | Inspiron 3501               | [1c7b4c3780](https://linux-hardware.org/?probe=1c7b4c3780) | Nov 21, 2022 |
| Dell          | Latitude E6410              | [22585074f3](https://linux-hardware.org/?probe=22585074f3) | Nov 21, 2022 |
| Alienware     | M17xR3                      | [d472e55685](https://linux-hardware.org/?probe=d472e55685) | Nov 20, 2022 |
| Sony          | VPCEB2M1E                   | [eeefed51e4](https://linux-hardware.org/?probe=eeefed51e4) | Nov 20, 2022 |
| Apple         | MacBookAir4,2               | [7d3f0e5604](https://linux-hardware.org/?probe=7d3f0e5604) | Nov 20, 2022 |
| Chuwi         | LapBook SE                  | [ecc56a3703](https://linux-hardware.org/?probe=ecc56a3703) | Nov 19, 2022 |
| HP            | EliteBook 840 G1            | [45a5881e61](https://linux-hardware.org/?probe=45a5881e61) | Nov 19, 2022 |
| Lenovo        | S145-15API 81UT             | [fd832d05e2](https://linux-hardware.org/?probe=fd832d05e2) | Nov 19, 2022 |
| HP            | Pavilion g7                 | [fae1d08109](https://linux-hardware.org/?probe=fae1d08109) | Nov 19, 2022 |
| HP            | Pavilion dm4                | [d90ac7b5c2](https://linux-hardware.org/?probe=d90ac7b5c2) | Nov 19, 2022 |
| HP            | Notebook                    | [ded915d6cd](https://linux-hardware.org/?probe=ded915d6cd) | Nov 18, 2022 |
| HP            | Presario CQ43               | [0ed80872c0](https://linux-hardware.org/?probe=0ed80872c0) | Nov 18, 2022 |
| Acer          | Aspire one 1-431            | [c27978fdc4](https://linux-hardware.org/?probe=c27978fdc4) | Nov 18, 2022 |
| Acer          | Aspire 6930G                | [05ad62f97d](https://linux-hardware.org/?probe=05ad62f97d) | Nov 17, 2022 |
| Packard Be... | EasyNote TK81               | [c396423368](https://linux-hardware.org/?probe=c396423368) | Nov 17, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [dd25be7aef](https://linux-hardware.org/?probe=dd25be7aef) | Nov 17, 2022 |
| ASUSTek       | K54HR                       | [ba95174feb](https://linux-hardware.org/?probe=ba95174feb) | Nov 17, 2022 |
| Compaq        | 420                         | [07ab1c2b0f](https://linux-hardware.org/?probe=07ab1c2b0f) | Nov 17, 2022 |
| MSI           | CR620                       | [4d90de18ca](https://linux-hardware.org/?probe=4d90de18ca) | Nov 16, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [9c25ade74d](https://linux-hardware.org/?probe=9c25ade74d) | Nov 16, 2022 |
| Toshiba       | Satellite Pro U500          | [064a36a5bb](https://linux-hardware.org/?probe=064a36a5bb) | Nov 16, 2022 |
| Apple         | MacBookPro8,1               | [6f3ecf327d](https://linux-hardware.org/?probe=6f3ecf327d) | Nov 16, 2022 |
| HP            | EliteBook Folio 1040 G2     | [3f95d3f191](https://linux-hardware.org/?probe=3f95d3f191) | Nov 15, 2022 |
| LDLC          | SPC-N                       | [acec489419](https://linux-hardware.org/?probe=acec489419) | Nov 15, 2022 |
| ASUSTek       | N751JX                      | [cea52af467](https://linux-hardware.org/?probe=cea52af467) | Nov 14, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [298f1bd357](https://linux-hardware.org/?probe=298f1bd357) | Nov 14, 2022 |
| Lenovo        | G550 20023                  | [80be7e8e25](https://linux-hardware.org/?probe=80be7e8e25) | Nov 14, 2022 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | [4121297e16](https://linux-hardware.org/?probe=4121297e16) | Nov 14, 2022 |
| Sony          | SVE1411EGXB                 | [dafea482eb](https://linux-hardware.org/?probe=dafea482eb) | Nov 14, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [9506350a75](https://linux-hardware.org/?probe=9506350a75) | Nov 13, 2022 |
| Apple         | MacBookPro5,5               | [9ef06fcef1](https://linux-hardware.org/?probe=9ef06fcef1) | Nov 13, 2022 |
| Fujitsu       | LIFEBOOK E782               | [f6b2530682](https://linux-hardware.org/?probe=f6b2530682) | Nov 12, 2022 |
| HP            | ProBook 455 G2              | [1a5d0a1618](https://linux-hardware.org/?probe=1a5d0a1618) | Nov 12, 2022 |
| Dell          | Vostro 3300                 | [be3a3b081d](https://linux-hardware.org/?probe=be3a3b081d) | Nov 12, 2022 |
| Acer          | Aspire 7741                 | [d5166a002a](https://linux-hardware.org/?probe=d5166a002a) | Nov 11, 2022 |
| HP            | 250 G5 Notebook PC          | [d710968897](https://linux-hardware.org/?probe=d710968897) | Nov 11, 2022 |
| Toshiba       | Satellite C870-D7K          | [b2f60a1b4d](https://linux-hardware.org/?probe=b2f60a1b4d) | Nov 11, 2022 |
| ASUSTek       | UX31E                       | [fa27762189](https://linux-hardware.org/?probe=fa27762189) | Nov 11, 2022 |
| MSI           | U270DX                      | [2a68a6ba02](https://linux-hardware.org/?probe=2a68a6ba02) | Nov 10, 2022 |
| Acer          | Nitro AN515-43              | [0e624570e1](https://linux-hardware.org/?probe=0e624570e1) | Nov 10, 2022 |
| Dell          | Inspiron N7010              | [8d43f2e3fc](https://linux-hardware.org/?probe=8d43f2e3fc) | Nov 10, 2022 |
| ASUSTek       | X553MA                      | [673c961915](https://linux-hardware.org/?probe=673c961915) | Nov 09, 2022 |
| Acer          | Aspire 5750G                | [8383f208a6](https://linux-hardware.org/?probe=8383f208a6) | Nov 09, 2022 |
| Fujitsu       | FMVXN4MN2Z                  | [7a08a94b1e](https://linux-hardware.org/?probe=7a08a94b1e) | Nov 09, 2022 |
| Unknown       | Unknown                     | [c46b9195f3](https://linux-hardware.org/?probe=c46b9195f3) | Nov 09, 2022 |
| HP            | Pavilion dv2700             | [a8e36a1579](https://linux-hardware.org/?probe=a8e36a1579) | Nov 08, 2022 |
| Dell          | Latitude E6400              | [22ccbac81a](https://linux-hardware.org/?probe=22ccbac81a) | Nov 07, 2022 |
| HP            | Notebook                    | [0164126ac9](https://linux-hardware.org/?probe=0164126ac9) | Nov 07, 2022 |
| HP            | ProBook 4530s               | [afb0629ea9](https://linux-hardware.org/?probe=afb0629ea9) | Nov 07, 2022 |
| ASUSTek       | K53E                        | [07d6d01b99](https://linux-hardware.org/?probe=07d6d01b99) | Nov 06, 2022 |
| HP            | Notebook                    | [59b70f4c7c](https://linux-hardware.org/?probe=59b70f4c7c) | Nov 06, 2022 |
| Lenovo        | G485 20136                  | [f8ee5082f8](https://linux-hardware.org/?probe=f8ee5082f8) | Nov 06, 2022 |
| Acer          | TravelMate P259-G2-M        | [4a85f586b3](https://linux-hardware.org/?probe=4a85f586b3) | Nov 05, 2022 |
| Acer          | Aspire A717-71G             | [a6fa794196](https://linux-hardware.org/?probe=a6fa794196) | Nov 05, 2022 |
| ASUSTek       | K56CM                       | [c93289dc28](https://linux-hardware.org/?probe=c93289dc28) | Nov 05, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [e2cadc512e](https://linux-hardware.org/?probe=e2cadc512e) | Nov 05, 2022 |
| Dell          | XPS 15 9530                 | [5ffd5ed23d](https://linux-hardware.org/?probe=5ffd5ed23d) | Nov 05, 2022 |
| Toshiba       | Satellite C75D-B            | [c125fc089c](https://linux-hardware.org/?probe=c125fc089c) | Nov 05, 2022 |
| Lenovo        | ThinkPad L520 78596CG       | [094f09bcf8](https://linux-hardware.org/?probe=094f09bcf8) | Nov 04, 2022 |
| Toshiba       | Satellite Pro A200          | [09ae3b0b13](https://linux-hardware.org/?probe=09ae3b0b13) | Nov 04, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMC    | [010fd86c32](https://linux-hardware.org/?probe=010fd86c32) | Nov 04, 2022 |
| Lenovo        | B50-45 80F0                 | [2d36803ec6](https://linux-hardware.org/?probe=2d36803ec6) | Nov 04, 2022 |
| ASUSTek       | K50IN                       | [8c069a1707](https://linux-hardware.org/?probe=8c069a1707) | Nov 03, 2022 |
| Packard Be... | EasyNote MZ45               | [93dada1577](https://linux-hardware.org/?probe=93dada1577) | Nov 03, 2022 |
| HP            | Stream Laptop 14-cb0XX      | [1d618807a7](https://linux-hardware.org/?probe=1d618807a7) | Nov 03, 2022 |
| Samsung       | 400B2B/400B2B               | [a909b4b203](https://linux-hardware.org/?probe=a909b4b203) | Nov 03, 2022 |
| HP            | ENVY m6                     | [9043724da5](https://linux-hardware.org/?probe=9043724da5) | Nov 02, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [0a79270558](https://linux-hardware.org/?probe=0a79270558) | Nov 02, 2022 |
| Panasonic     | CF-C1BWFBZ1M                | [18a81d5db2](https://linux-hardware.org/?probe=18a81d5db2) | Nov 02, 2022 |
| Acer          | Nitro AN515-57              | [44f768478e](https://linux-hardware.org/?probe=44f768478e) | Nov 02, 2022 |
| Toshiba       | Satellite C660              | [44c6e56cd9](https://linux-hardware.org/?probe=44c6e56cd9) | Nov 01, 2022 |
| Lenovo        | G50-80 80E5                 | [0470f02ccb](https://linux-hardware.org/?probe=0470f02ccb) | Nov 01, 2022 |
| ASUSTek       | S551LN                      | [67e15a659d](https://linux-hardware.org/?probe=67e15a659d) | Oct 31, 2022 |
| Acer          | Extensa 5635Z               | [35ce596e08](https://linux-hardware.org/?probe=35ce596e08) | Oct 31, 2022 |
| Dell          | Latitude E5500              | [c64399793c](https://linux-hardware.org/?probe=c64399793c) | Oct 31, 2022 |
| Dell          | Latitude E6400              | [8f2639b285](https://linux-hardware.org/?probe=8f2639b285) | Oct 31, 2022 |
| Acer          | Aspire E5-573G              | [acfa0d90d6](https://linux-hardware.org/?probe=acfa0d90d6) | Oct 31, 2022 |
| Intel         | powered classmate PC        | [5555da7553](https://linux-hardware.org/?probe=5555da7553) | Oct 31, 2022 |
| Prestigio     | PSB133S01ZFP                | [e10becbd35](https://linux-hardware.org/?probe=e10becbd35) | Oct 30, 2022 |
| Dell          | Latitude E7240              | [7605a5bf1c](https://linux-hardware.org/?probe=7605a5bf1c) | Oct 30, 2022 |
| ASUSTek       | X556UQK                     | [f8bdcbce4e](https://linux-hardware.org/?probe=f8bdcbce4e) | Oct 29, 2022 |
| Dell          | Studio 1737                 | [97f398804e](https://linux-hardware.org/?probe=97f398804e) | Oct 29, 2022 |
| HP            | Compaq 615                  | [ae90fa3742](https://linux-hardware.org/?probe=ae90fa3742) | Oct 29, 2022 |
| ASUSTek       | UX31E                       | [6e9cb9c0e0](https://linux-hardware.org/?probe=6e9cb9c0e0) | Oct 29, 2022 |
| Dell          | Inspiron 1525               | [ffb4369f83](https://linux-hardware.org/?probe=ffb4369f83) | Oct 29, 2022 |
| Dell          | XPS 15 9530                 | [fc7ef1ce9a](https://linux-hardware.org/?probe=fc7ef1ce9a) | Oct 29, 2022 |
| Acer          | Aspire 5745                 | [2f79de6974](https://linux-hardware.org/?probe=2f79de6974) | Oct 28, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [6b57390808](https://linux-hardware.org/?probe=6b57390808) | Oct 28, 2022 |
| HP            | Pavilion Laptop 15-cc0xx    | [0ca2ea7180](https://linux-hardware.org/?probe=0ca2ea7180) | Oct 28, 2022 |
| Acer          | Aspire 8730                 | [86bffd9523](https://linux-hardware.org/?probe=86bffd9523) | Oct 27, 2022 |
| Acer          | Aspire E3-112               | [fd34f66305](https://linux-hardware.org/?probe=fd34f66305) | Oct 26, 2022 |
| Toshiba       | Satellite L45-B             | [e2f30e0f1e](https://linux-hardware.org/?probe=e2f30e0f1e) | Oct 26, 2022 |
| Acer          | Aspire ES1-571              | [f9f7926da2](https://linux-hardware.org/?probe=f9f7926da2) | Oct 25, 2022 |
| Panasonic     | CFSX4-1                     | [2ddae6e0e1](https://linux-hardware.org/?probe=2ddae6e0e1) | Oct 25, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [ede3bcd3f3](https://linux-hardware.org/?probe=ede3bcd3f3) | Oct 24, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [bfa28dd791](https://linux-hardware.org/?probe=bfa28dd791) | Oct 24, 2022 |
| Dell          | Studio 1737                 | [d6e17c05b2](https://linux-hardware.org/?probe=d6e17c05b2) | Oct 24, 2022 |
| Lenovo        | G400s VILG1                 | [b7315785a1](https://linux-hardware.org/?probe=b7315785a1) | Oct 24, 2022 |
| ASUSTek       | A7U                         | [867f26dde1](https://linux-hardware.org/?probe=867f26dde1) | Oct 24, 2022 |
| Acer          | TravelMate B311-31          | [010dd1e876](https://linux-hardware.org/?probe=010dd1e876) | Oct 24, 2022 |
| Packard Be... | EasyNote ENTE70BH           | [2135a5aed7](https://linux-hardware.org/?probe=2135a5aed7) | Oct 23, 2022 |
| Lenovo        | ThinkPad X240 20AMS01M00    | [2f1c7b7716](https://linux-hardware.org/?probe=2f1c7b7716) | Oct 23, 2022 |
| Fujitsu       | LIFEBOOK AH532              | [d806b92948](https://linux-hardware.org/?probe=d806b92948) | Oct 22, 2022 |
| Dell          | Precision M6800             | [9b909039ee](https://linux-hardware.org/?probe=9b909039ee) | Oct 21, 2022 |
| Lenovo        | ThinkPad T520 42434WU       | [d118d39c58](https://linux-hardware.org/?probe=d118d39c58) | Oct 21, 2022 |
| MSI           | GT70 0NC/GT70 0NC           | [592b788d62](https://linux-hardware.org/?probe=592b788d62) | Oct 20, 2022 |
| Dell          | Latitude E5410              | [f3b5d196ef](https://linux-hardware.org/?probe=f3b5d196ef) | Oct 20, 2022 |
| Sony          | SVE1513B1EW                 | [77ef0b542b](https://linux-hardware.org/?probe=77ef0b542b) | Oct 20, 2022 |
| Acer          | Aspire E5-574               | [d9797d9fa7](https://linux-hardware.org/?probe=d9797d9fa7) | Oct 19, 2022 |
| Dell          | Inspiron 13-7359            | [239627f1d1](https://linux-hardware.org/?probe=239627f1d1) | Oct 19, 2022 |
| Samsung       | 550XDA                      | [fcfceeaf04](https://linux-hardware.org/?probe=fcfceeaf04) | Oct 19, 2022 |
| MSI           | GE62 6QC                    | [92ac4fbaa6](https://linux-hardware.org/?probe=92ac4fbaa6) | Oct 19, 2022 |
| Lenovo        | G480                        | [984691a38d](https://linux-hardware.org/?probe=984691a38d) | Oct 18, 2022 |
| HP            | Unknown                     | [4a0df43034](https://linux-hardware.org/?probe=4a0df43034) | Oct 17, 2022 |
| Dell          | Latitude E6330              | [d4d6ca7ae9](https://linux-hardware.org/?probe=d4d6ca7ae9) | Oct 17, 2022 |
| Lenovo        | G50-70 20351                | [a1e9be5323](https://linux-hardware.org/?probe=a1e9be5323) | Oct 17, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [9e37b60507](https://linux-hardware.org/?probe=9e37b60507) | Oct 16, 2022 |
| Dell          | Latitude E6430              | [2e8f3bd664](https://linux-hardware.org/?probe=2e8f3bd664) | Oct 16, 2022 |
| Dell          | Latitude E6420              | [913e2b1acd](https://linux-hardware.org/?probe=913e2b1acd) | Oct 15, 2022 |
| Lenovo        | ThinkPad L560 20F1000TJP    | [e9b7a4ffc2](https://linux-hardware.org/?probe=e9b7a4ffc2) | Oct 15, 2022 |
| Acer          | Aspire A515-44              | [a19fc69283](https://linux-hardware.org/?probe=a19fc69283) | Oct 15, 2022 |
| LG Electro... | S460-G.BG31P1               | [a0b3b8e905](https://linux-hardware.org/?probe=a0b3b8e905) | Oct 15, 2022 |
| Dell          | Latitude 3340               | [d99dbe3b99](https://linux-hardware.org/?probe=d99dbe3b99) | Oct 14, 2022 |
| ASUSTek       | UX31E                       | [bddc33ef5a](https://linux-hardware.org/?probe=bddc33ef5a) | Oct 14, 2022 |
| Packard Be... | EasyNote TJ66               | [e5f4bf84f8](https://linux-hardware.org/?probe=e5f4bf84f8) | Oct 14, 2022 |
| Compaq        | PRESARIOCQ18                | [5172032993](https://linux-hardware.org/?probe=5172032993) | Oct 14, 2022 |
| Dell          | Latitude E5440              | [432aa93109](https://linux-hardware.org/?probe=432aa93109) | Oct 14, 2022 |
| Dell          | Inspiron 5551               | [64865d9bb5](https://linux-hardware.org/?probe=64865d9bb5) | Oct 13, 2022 |
| Dell          | Precision 7720              | [4cadd86832](https://linux-hardware.org/?probe=4cadd86832) | Oct 13, 2022 |
| Dell          | Studio 1555                 | [52104abe69](https://linux-hardware.org/?probe=52104abe69) | Oct 13, 2022 |
| HP            | Laptop 14-bw0xx             | [3a190d5718](https://linux-hardware.org/?probe=3a190d5718) | Oct 13, 2022 |
| Acer          | Aspire E5-573G              | [bccf0a4ebe](https://linux-hardware.org/?probe=bccf0a4ebe) | Oct 13, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [bb386c7d60](https://linux-hardware.org/?probe=bb386c7d60) | Oct 13, 2022 |
| Toshiba       | Satellite C855              | [65e0a41b8d](https://linux-hardware.org/?probe=65e0a41b8d) | Oct 13, 2022 |
| Acer          | Aspire 7250G                | [34966259d6](https://linux-hardware.org/?probe=34966259d6) | Oct 13, 2022 |
| HP            | G42                         | [fd42e3aedb](https://linux-hardware.org/?probe=fd42e3aedb) | Oct 12, 2022 |
| Dell          | XPS 15 9530                 | [ad2b1ab7b8](https://linux-hardware.org/?probe=ad2b1ab7b8) | Oct 12, 2022 |
| Star Labs     | StarLite                    | [627ad33197](https://linux-hardware.org/?probe=627ad33197) | Oct 12, 2022 |
| Dell          | Latitude E6440              | [3b13c28e46](https://linux-hardware.org/?probe=3b13c28e46) | Oct 12, 2022 |
| Lenovo        | ThinkPad T440s 20ARS4PR0... | [18c02300b9](https://linux-hardware.org/?probe=18c02300b9) | Oct 11, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [87cfe8ed2e](https://linux-hardware.org/?probe=87cfe8ed2e) | Oct 11, 2022 |
| Dell          | Latitude E6540              | [d1b0bd16b5](https://linux-hardware.org/?probe=d1b0bd16b5) | Oct 11, 2022 |
| ASUSTek       | UX31E                       | [22cf469faa](https://linux-hardware.org/?probe=22cf469faa) | Oct 10, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [792528e3b2](https://linux-hardware.org/?probe=792528e3b2) | Oct 10, 2022 |
| Dell          | Latitude E6410              | [4f6730e0f2](https://linux-hardware.org/?probe=4f6730e0f2) | Oct 09, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [3e7ef86329](https://linux-hardware.org/?probe=3e7ef86329) | Oct 09, 2022 |
| ASUSTek       | X550VB                      | [a7c1c1cb1b](https://linux-hardware.org/?probe=a7c1c1cb1b) | Oct 09, 2022 |
| Dell          | Inspiron N7010              | [8d58156239](https://linux-hardware.org/?probe=8d58156239) | Oct 09, 2022 |
| Dell          | Inspiron 5558               | [8918b1b82e](https://linux-hardware.org/?probe=8918b1b82e) | Oct 09, 2022 |
| HP            | Laptop 15-da0xxx            | [d172225c0b](https://linux-hardware.org/?probe=d172225c0b) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3665682cc6](https://linux-hardware.org/?probe=3665682cc6) | Oct 08, 2022 |
| HP            | Laptop 15-ef1xxx            | [9d44a35e48](https://linux-hardware.org/?probe=9d44a35e48) | Oct 08, 2022 |
| Fujitsu       | LIFEBOOK E736               | [3e7cc2c14a](https://linux-hardware.org/?probe=3e7cc2c14a) | Oct 07, 2022 |
| HP            | Laptop 15-da2xxx            | [b699753cc6](https://linux-hardware.org/?probe=b699753cc6) | Oct 07, 2022 |
| Dell          | Latitude E6400              | [509deb10b3](https://linux-hardware.org/?probe=509deb10b3) | Oct 07, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [8061516838](https://linux-hardware.org/?probe=8061516838) | Oct 06, 2022 |
| Toshiba       | Satellite R830              | [0a5299f7e0](https://linux-hardware.org/?probe=0a5299f7e0) | Oct 06, 2022 |
| Positivo      | C14CR01                     | [7c0d0b2efd](https://linux-hardware.org/?probe=7c0d0b2efd) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [f9224c972e](https://linux-hardware.org/?probe=f9224c972e) | Oct 05, 2022 |
| HP            | Pavilion 17                 | [f7626421b2](https://linux-hardware.org/?probe=f7626421b2) | Oct 05, 2022 |
| Acer          | Aspire 5250                 | [8a18115a5b](https://linux-hardware.org/?probe=8a18115a5b) | Oct 04, 2022 |
| Dell          | Inspiron 3442               | [612b4b36a1](https://linux-hardware.org/?probe=612b4b36a1) | Oct 04, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [b8ad7a8464](https://linux-hardware.org/?probe=b8ad7a8464) | Oct 04, 2022 |
| Acer          | Aspire E5-575G              | [5e60e8faae](https://linux-hardware.org/?probe=5e60e8faae) | Oct 04, 2022 |
| Dell          | Latitude E6420              | [cc0d33aedb](https://linux-hardware.org/?probe=cc0d33aedb) | Oct 03, 2022 |
| Acer          | TravelMate 5744             | [4817d4810d](https://linux-hardware.org/?probe=4817d4810d) | Oct 03, 2022 |
| Dell          | XPS 15 9530                 | [abfab502a6](https://linux-hardware.org/?probe=abfab502a6) | Oct 02, 2022 |
| ASUSTek       | UX303UB                     | [d67f04fc6e](https://linux-hardware.org/?probe=d67f04fc6e) | Oct 02, 2022 |
| Dell          | Inspiron 5559               | [47a7282318](https://linux-hardware.org/?probe=47a7282318) | Oct 02, 2022 |
| ASUSTek       | X550JX                      | [43694e5952](https://linux-hardware.org/?probe=43694e5952) | Oct 02, 2022 |
| Acer          | Aspire V3-571G              | [bfd8dc3c18](https://linux-hardware.org/?probe=bfd8dc3c18) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [516795a4a8](https://linux-hardware.org/?probe=516795a4a8) | Oct 02, 2022 |
| HP            | ProBook 450 G4              | [9c6340e585](https://linux-hardware.org/?probe=9c6340e585) | Oct 01, 2022 |
| Dell          | Inspiron 1545               | [ba72c7ee42](https://linux-hardware.org/?probe=ba72c7ee42) | Oct 01, 2022 |
| Lenovo        | 3000 N200 0769B4G           | [947f124efc](https://linux-hardware.org/?probe=947f124efc) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [7ff2c5ad1c](https://linux-hardware.org/?probe=7ff2c5ad1c) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [a64cec6a4d](https://linux-hardware.org/?probe=a64cec6a4d) | Oct 01, 2022 |
| ASUSTek       | UX303UB                     | [e09f793c1a](https://linux-hardware.org/?probe=e09f793c1a) | Oct 01, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [68b0c0ca1a](https://linux-hardware.org/?probe=68b0c0ca1a) | Oct 01, 2022 |
| Sony          | VPCYB3V1E                   | [de50c8a304](https://linux-hardware.org/?probe=de50c8a304) | Oct 01, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [f50a823779](https://linux-hardware.org/?probe=f50a823779) | Oct 01, 2022 |
| HP            | Laptop 15-bs0xx             | [646f4ffa8e](https://linux-hardware.org/?probe=646f4ffa8e) | Oct 01, 2022 |
| Dell          | Inspiron 11-3162            | [8cd15b2f0c](https://linux-hardware.org/?probe=8cd15b2f0c) | Sep 30, 2022 |
| Dell          | Latitude E6520              | [04817b4ceb](https://linux-hardware.org/?probe=04817b4ceb) | Sep 30, 2022 |
| Lenovo        | G460 20041                  | [9018f40ad5](https://linux-hardware.org/?probe=9018f40ad5) | Sep 30, 2022 |
| Dell          | Latitude 3310               | [3c4874fa51](https://linux-hardware.org/?probe=3c4874fa51) | Sep 30, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [d153a4f97a](https://linux-hardware.org/?probe=d153a4f97a) | Sep 29, 2022 |
| Toshiba       | Satellite L505              | [3e91e2bfaf](https://linux-hardware.org/?probe=3e91e2bfaf) | Sep 29, 2022 |
| HP            | Laptop 14s-fq1xxx           | [3990ec6cb0](https://linux-hardware.org/?probe=3990ec6cb0) | Sep 29, 2022 |
| HP            | Compaq 6720s                | [ddb5163310](https://linux-hardware.org/?probe=ddb5163310) | Sep 29, 2022 |
| Apple         | MacBook7,1                  | [88d57c6319](https://linux-hardware.org/?probe=88d57c6319) | Sep 29, 2022 |
| Dell          | Inspiron 15-3552            | [9414d73ae0](https://linux-hardware.org/?probe=9414d73ae0) | Sep 29, 2022 |
| Dell          | XPS 13 9360                 | [6f1ecca2f0](https://linux-hardware.org/?probe=6f1ecca2f0) | Sep 28, 2022 |
| Dell          | Latitude 3310               | [c21a321dce](https://linux-hardware.org/?probe=c21a321dce) | Sep 28, 2022 |
| Dell          | Inspiron 5558               | [a42a4722f7](https://linux-hardware.org/?probe=a42a4722f7) | Sep 28, 2022 |
| Dell          | Vostro 5391                 | [61a25cdb83](https://linux-hardware.org/?probe=61a25cdb83) | Sep 28, 2022 |
| Sony          | VPCEH1S1R                   | [5214bb023f](https://linux-hardware.org/?probe=5214bb023f) | Sep 27, 2022 |
| Dell          | Latitude 3300               | [365349d964](https://linux-hardware.org/?probe=365349d964) | Sep 27, 2022 |
| Dell          | Latitude 3310               | [313ab64584](https://linux-hardware.org/?probe=313ab64584) | Sep 27, 2022 |
| Lenovo        | IdeaPad Z580                | [a33ab40c8b](https://linux-hardware.org/?probe=a33ab40c8b) | Sep 27, 2022 |
| Packard Be... | EasyNote LS44SB             | [184a0768bd](https://linux-hardware.org/?probe=184a0768bd) | Sep 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [898f9bf963](https://linux-hardware.org/?probe=898f9bf963) | Sep 26, 2022 |
| Dell          | Latitude 3420               | [ee7c1fce66](https://linux-hardware.org/?probe=ee7c1fce66) | Sep 26, 2022 |
| Dell          | Latitude 3310               | [0f1fb4687f](https://linux-hardware.org/?probe=0f1fb4687f) | Sep 26, 2022 |
| Dell          | Latitude 3310               | [a6ce17cd6b](https://linux-hardware.org/?probe=a6ce17cd6b) | Sep 26, 2022 |
| Acer          | Aspire V5-471               | [66437a2187](https://linux-hardware.org/?probe=66437a2187) | Sep 26, 2022 |
| Dell          | Latitude 3310               | [87af9a8980](https://linux-hardware.org/?probe=87af9a8980) | Sep 26, 2022 |
| HP            | Laptop 17-by3xxx            | [41db205ec7](https://linux-hardware.org/?probe=41db205ec7) | Sep 25, 2022 |
| Lenovo        | ThinkPad SL500 27464DG      | [6c2b4ce4b1](https://linux-hardware.org/?probe=6c2b4ce4b1) | Sep 25, 2022 |
| HP            | 250 G5 Notebook PC          | [6c6ae30eba](https://linux-hardware.org/?probe=6c6ae30eba) | Sep 24, 2022 |
| HP            | Pavilion 15                 | [32670a0451](https://linux-hardware.org/?probe=32670a0451) | Sep 24, 2022 |
| Dell          | Inspiron 3721               | [7411a700cf](https://linux-hardware.org/?probe=7411a700cf) | Sep 24, 2022 |
| HP            | Laptop 17-cp0xxx            | [dafafa97a4](https://linux-hardware.org/?probe=dafafa97a4) | Sep 24, 2022 |
| Fujitsu       | LIFEBOOK S760               | [ceda61113a](https://linux-hardware.org/?probe=ceda61113a) | Sep 23, 2022 |
| Dell          | Latitude 3310               | [4c5dc33267](https://linux-hardware.org/?probe=4c5dc33267) | Sep 23, 2022 |
| Dell          | Latitude 7480               | [e1a3ca1d32](https://linux-hardware.org/?probe=e1a3ca1d32) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [2b37d81d4c](https://linux-hardware.org/?probe=2b37d81d4c) | Sep 22, 2022 |
| HP            | ProBook 450 G1              | [2527dc6ea0](https://linux-hardware.org/?probe=2527dc6ea0) | Sep 22, 2022 |
| Acer          | Nitro AN515-31              | [9b451feb14](https://linux-hardware.org/?probe=9b451feb14) | Sep 22, 2022 |
| HP            | Compaq 15                   | [345fe48777](https://linux-hardware.org/?probe=345fe48777) | Sep 22, 2022 |
| Lenovo        | ThinkPad X200s 7470WWD      | [268aa65de3](https://linux-hardware.org/?probe=268aa65de3) | Sep 22, 2022 |
| ASUSTek       | K70AD                       | [49dff3ffb5](https://linux-hardware.org/?probe=49dff3ffb5) | Sep 22, 2022 |
| ASUSTek       | X441BA                      | [e542a68ddf](https://linux-hardware.org/?probe=e542a68ddf) | Sep 21, 2022 |
| Dell          | G5 5505                     | [82017aa2ae](https://linux-hardware.org/?probe=82017aa2ae) | Sep 21, 2022 |
| Acer          | Aspire A315-23              | [dd730980b1](https://linux-hardware.org/?probe=dd730980b1) | Sep 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [8003baae8c](https://linux-hardware.org/?probe=8003baae8c) | Sep 19, 2022 |
| Acer          | Nitro AN515-31              | [33e582251a](https://linux-hardware.org/?probe=33e582251a) | Sep 19, 2022 |
| Lenovo        | G50-80 80R0                 | [f04ed15344](https://linux-hardware.org/?probe=f04ed15344) | Sep 19, 2022 |
| Samsung       | R530/R730                   | [0d4e13e70f](https://linux-hardware.org/?probe=0d4e13e70f) | Sep 19, 2022 |
| Dell          | Latitude 3310               | [0e1784b38d](https://linux-hardware.org/?probe=0e1784b38d) | Sep 19, 2022 |
| Dell          | Latitude 3310               | [55332651e0](https://linux-hardware.org/?probe=55332651e0) | Sep 19, 2022 |
| Dell          | Latitude 3120               | [558e95141d](https://linux-hardware.org/?probe=558e95141d) | Sep 19, 2022 |
| Dell          | Latitude 3300               | [a2513a9849](https://linux-hardware.org/?probe=a2513a9849) | Sep 19, 2022 |
| HP            | Laptop 15-ef2xxx            | [c9ab60a094](https://linux-hardware.org/?probe=c9ab60a094) | Sep 19, 2022 |
| Lenovo        | ThinkPad T400 6474WPU       | [892c3fb361](https://linux-hardware.org/?probe=892c3fb361) | Sep 18, 2022 |
| NEC Comput... | PC-VK26MXZCE                | [db8f5e4181](https://linux-hardware.org/?probe=db8f5e4181) | Sep 18, 2022 |
| Lenovo        | ThinkPad T430 23501M2       | [b9503c9c28](https://linux-hardware.org/?probe=b9503c9c28) | Sep 18, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [65c4f113d8](https://linux-hardware.org/?probe=65c4f113d8) | Sep 18, 2022 |
| HP            | ProBook 6470b               | [3821322b95](https://linux-hardware.org/?probe=3821322b95) | Sep 18, 2022 |
| HP            | Notebook                    | [d29681d2ed](https://linux-hardware.org/?probe=d29681d2ed) | Sep 17, 2022 |
| Lenovo        | ThinkPad E570 20H5009NUS    | [c64258edc0](https://linux-hardware.org/?probe=c64258edc0) | Sep 17, 2022 |
| Toshiba       | TECRA S10                   | [602d81b7c5](https://linux-hardware.org/?probe=602d81b7c5) | Sep 17, 2022 |
| Toshiba       | Satellite P845T             | [0d5f5ac925](https://linux-hardware.org/?probe=0d5f5ac925) | Sep 17, 2022 |
| HP            | Laptop 15-ef0xxx            | [19d0260ef6](https://linux-hardware.org/?probe=19d0260ef6) | Sep 17, 2022 |
| HP            | 255 G5 Notebook PC          | [6d8f7ffe97](https://linux-hardware.org/?probe=6d8f7ffe97) | Sep 17, 2022 |
| Apple         | MacBook6,1                  | [93b43e5bb5](https://linux-hardware.org/?probe=93b43e5bb5) | Sep 16, 2022 |
| Lenovo        | ThinkPad T420 4180A32       | [44841341fd](https://linux-hardware.org/?probe=44841341fd) | Sep 16, 2022 |
| Chuwi         | HeroBook Pro                | [9a7d178f1b](https://linux-hardware.org/?probe=9a7d178f1b) | Sep 15, 2022 |
| Lenovo        | IdeaPad Y570 20091          | [5e2681360e](https://linux-hardware.org/?probe=5e2681360e) | Sep 15, 2022 |
| Lenovo        | ThinkPad T530 2429F33       | [790a0f2a25](https://linux-hardware.org/?probe=790a0f2a25) | Sep 14, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [b552f0482d](https://linux-hardware.org/?probe=b552f0482d) | Sep 14, 2022 |
| Dell          | Latitude E7470              | [9d15a7c8a2](https://linux-hardware.org/?probe=9d15a7c8a2) | Sep 14, 2022 |
| Toshiba       | Satellite C660              | [39b26715f0](https://linux-hardware.org/?probe=39b26715f0) | Sep 14, 2022 |
| Dell          | Inspiron 5584               | [677d683644](https://linux-hardware.org/?probe=677d683644) | Sep 14, 2022 |
| Timi          | TM1612                      | [536fc04dcb](https://linux-hardware.org/?probe=536fc04dcb) | Sep 14, 2022 |
| Lenovo        | ThinkPad X230 2324GA1       | [c4e6cc1489](https://linux-hardware.org/?probe=c4e6cc1489) | Sep 14, 2022 |
| Toshiba       | Satellite L55-B             | [b593ff9e20](https://linux-hardware.org/?probe=b593ff9e20) | Sep 14, 2022 |
| HP            | Notebook                    | [963af7e07b](https://linux-hardware.org/?probe=963af7e07b) | Sep 13, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [e558fd5212](https://linux-hardware.org/?probe=e558fd5212) | Sep 13, 2022 |
| Medion        | E4251 MD61227               | [8b3475f65b](https://linux-hardware.org/?probe=8b3475f65b) | Sep 13, 2022 |
| Compal        | NCL60/61                    | [f1f5499af8](https://linux-hardware.org/?probe=f1f5499af8) | Sep 12, 2022 |
| Toshiba       | Satellite C655              | [16a4aa3cd8](https://linux-hardware.org/?probe=16a4aa3cd8) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | [fbb3c09289](https://linux-hardware.org/?probe=fbb3c09289) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | [fccf3eb345](https://linux-hardware.org/?probe=fccf3eb345) | Sep 12, 2022 |
| HP            | ProBook 440 G1              | [58b48039ce](https://linux-hardware.org/?probe=58b48039ce) | Sep 12, 2022 |
| ASUSTek       | UX31E                       | [910cdee832](https://linux-hardware.org/?probe=910cdee832) | Sep 11, 2022 |
| HP            | Notebook                    | [2984aef090](https://linux-hardware.org/?probe=2984aef090) | Sep 11, 2022 |
| ASUSTek       | K46CA                       | [9e730cbd6a](https://linux-hardware.org/?probe=9e730cbd6a) | Sep 11, 2022 |
| Lenovo        | Unknown                     | [b5842ca017](https://linux-hardware.org/?probe=b5842ca017) | Sep 10, 2022 |
| Samsung       | R530/R730/R540              | [72aea277e6](https://linux-hardware.org/?probe=72aea277e6) | Sep 10, 2022 |
| Lenovo        | ThinkPad L420 7829H86       | [406535e915](https://linux-hardware.org/?probe=406535e915) | Sep 10, 2022 |
| HP            | Pavilion g6                 | [0774a3c97d](https://linux-hardware.org/?probe=0774a3c97d) | Sep 10, 2022 |
| LG Electro... | U560-G.BG31P1               | [741c3eddbe](https://linux-hardware.org/?probe=741c3eddbe) | Sep 10, 2022 |
| Samsung       | SX60P                       | [1e0ea8e787](https://linux-hardware.org/?probe=1e0ea8e787) | Sep 09, 2022 |
| Dell          | Precision 7560              | [3e2d1a120c](https://linux-hardware.org/?probe=3e2d1a120c) | Sep 09, 2022 |
| Dell          | Latitude E4300              | [634c1467f8](https://linux-hardware.org/?probe=634c1467f8) | Sep 09, 2022 |
| Acer          | Aspire 5738                 | [5c21c2acc6](https://linux-hardware.org/?probe=5c21c2acc6) | Sep 09, 2022 |
| Positivo      | H14BT58                     | [669a466b1c](https://linux-hardware.org/?probe=669a466b1c) | Sep 09, 2022 |
| Lenovo        | IdeaPad S400 20195          | [6bd3292f42](https://linux-hardware.org/?probe=6bd3292f42) | Sep 08, 2022 |
| Lenovo        | B5400 20278                 | [1c9d752f91](https://linux-hardware.org/?probe=1c9d752f91) | Sep 07, 2022 |
| HP            | Pavilion dv7                | [4a39ae67d5](https://linux-hardware.org/?probe=4a39ae67d5) | Sep 07, 2022 |
| Lenovo        | G580                        | [922ede2a50](https://linux-hardware.org/?probe=922ede2a50) | Sep 07, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [22171cc2a6](https://linux-hardware.org/?probe=22171cc2a6) | Sep 07, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [14f91e3a08](https://linux-hardware.org/?probe=14f91e3a08) | Sep 07, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [cf398ae303](https://linux-hardware.org/?probe=cf398ae303) | Sep 07, 2022 |
| HP            | ProBook 430 G1              | [cca59cbb3c](https://linux-hardware.org/?probe=cca59cbb3c) | Sep 07, 2022 |
| Positivo      | Mobile                      | [1378222b07](https://linux-hardware.org/?probe=1378222b07) | Sep 07, 2022 |
| LG Electro... | A530-T.BE76P1               | [46161b573f](https://linux-hardware.org/?probe=46161b573f) | Sep 06, 2022 |
| Lenovo        | ThinkPad Edge E531 68856... | [498682ac13](https://linux-hardware.org/?probe=498682ac13) | Sep 06, 2022 |
| Sony          | VPCSB3X9E                   | [03bd901e4f](https://linux-hardware.org/?probe=03bd901e4f) | Sep 06, 2022 |
| Lenovo        | ThinkPad T420 4236PNP       | [7c3dc0af20](https://linux-hardware.org/?probe=7c3dc0af20) | Sep 06, 2022 |
| Toshiba       | Satellite C75D-B            | [78e0cb1ca2](https://linux-hardware.org/?probe=78e0cb1ca2) | Sep 06, 2022 |
| Acer          | Aspire 5745                 | [39bc7728ac](https://linux-hardware.org/?probe=39bc7728ac) | Sep 06, 2022 |
| Lenovo        | B71-80 80RJ                 | [c16dc3a768](https://linux-hardware.org/?probe=c16dc3a768) | Sep 06, 2022 |
| Lenovo        | ThinkPad L440 20ASS11T00    | [526d97c730](https://linux-hardware.org/?probe=526d97c730) | Sep 06, 2022 |
| HP            | Stream Laptop 14-cb0XX      | [6f848cd309](https://linux-hardware.org/?probe=6f848cd309) | Sep 06, 2022 |
| Dell          | Vostro 14-5480              | [fb3ae25db8](https://linux-hardware.org/?probe=fb3ae25db8) | Sep 06, 2022 |
| Dell          | Latitude E6220              | [af87786838](https://linux-hardware.org/?probe=af87786838) | Sep 05, 2022 |
| Lenovo        | ThinkPad T530 2429W4Y       | [572b46f025](https://linux-hardware.org/?probe=572b46f025) | Sep 05, 2022 |
| ASUSTek       | K53BY                       | [efbc2be1a7](https://linux-hardware.org/?probe=efbc2be1a7) | Sep 05, 2022 |
| HP            | ProBook 450 G1              | [d9a3103936](https://linux-hardware.org/?probe=d9a3103936) | Sep 05, 2022 |
| Toshiba       | Satellite C55-A-157         | [483a0f4f49](https://linux-hardware.org/?probe=483a0f4f49) | Sep 05, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [a783dcd3ca](https://linux-hardware.org/?probe=a783dcd3ca) | Sep 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cb809c935a](https://linux-hardware.org/?probe=cb809c935a) | Sep 05, 2022 |
| ASUSTek       | X45C                        | [7267b251b6](https://linux-hardware.org/?probe=7267b251b6) | Sep 05, 2022 |
| Apple         | MacBookPro8,1               | [113f737135](https://linux-hardware.org/?probe=113f737135) | Sep 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | [96d17dc188](https://linux-hardware.org/?probe=96d17dc188) | Sep 04, 2022 |
| ASUSTek       | X540LA                      | [3ba0635033](https://linux-hardware.org/?probe=3ba0635033) | Sep 04, 2022 |
| MSI           | MS-168B                     | [a0a6645eef](https://linux-hardware.org/?probe=a0a6645eef) | Sep 04, 2022 |
| Jumper        | EZbook                      | [d67fae436c](https://linux-hardware.org/?probe=d67fae436c) | Sep 04, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [66724351c4](https://linux-hardware.org/?probe=66724351c4) | Sep 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d7c3304983](https://linux-hardware.org/?probe=d7c3304983) | Sep 04, 2022 |
| Samsung       | 300E5M/300E5L               | [3d542c8484](https://linux-hardware.org/?probe=3d542c8484) | Sep 03, 2022 |
| Sony          | VGN-FZ31Z                   | [b99831e9f4](https://linux-hardware.org/?probe=b99831e9f4) | Sep 03, 2022 |
| Acer          | Extensa 5635ZG              | [f79a7aaa6f](https://linux-hardware.org/?probe=f79a7aaa6f) | Sep 03, 2022 |
| HP            | Compaq Presario CQ60        | [c2251f33ef](https://linux-hardware.org/?probe=c2251f33ef) | Sep 03, 2022 |
| HP            | 620                         | [34002dc814](https://linux-hardware.org/?probe=34002dc814) | Sep 02, 2022 |
| ASUSTek       | UX31E                       | [21183dcf00](https://linux-hardware.org/?probe=21183dcf00) | Sep 02, 2022 |
| UMAX          | VisionBook 14Wr Plus        | [6a2cb26049](https://linux-hardware.org/?probe=6a2cb26049) | Sep 02, 2022 |
| Getac         | B300-X                      | [927b99c2e0](https://linux-hardware.org/?probe=927b99c2e0) | Sep 02, 2022 |
| Toshiba       | Satellite C660              | [448c7a24e2](https://linux-hardware.org/?probe=448c7a24e2) | Sep 02, 2022 |
| Dell          | Latitude 3120               | [8716f564d8](https://linux-hardware.org/?probe=8716f564d8) | Sep 02, 2022 |
| HP            | Laptop 17-by4xxx            | [b9502cc4a9](https://linux-hardware.org/?probe=b9502cc4a9) | Sep 02, 2022 |
| HP            | Laptop 15-ef1xxx            | [d27c20dcf9](https://linux-hardware.org/?probe=d27c20dcf9) | Sep 01, 2022 |
| Packard Be... | DOT S                       | [b5b03f1cf7](https://linux-hardware.org/?probe=b5b03f1cf7) | Sep 01, 2022 |
| HP            | ZBook 17 G2                 | [e2fc506c38](https://linux-hardware.org/?probe=e2fc506c38) | Sep 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [8a7e7ce8ea](https://linux-hardware.org/?probe=8a7e7ce8ea) | Sep 01, 2022 |
| Dell          | Latitude 3190               | [d30269b33c](https://linux-hardware.org/?probe=d30269b33c) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [c48154f5f4](https://linux-hardware.org/?probe=c48154f5f4) | Sep 01, 2022 |
| ASUSTek       | X550ZE                      | [187a6feadf](https://linux-hardware.org/?probe=187a6feadf) | Sep 01, 2022 |
| HP            | Laptop 14s-fq1xxx           | [1a173c5ea0](https://linux-hardware.org/?probe=1a173c5ea0) | Sep 01, 2022 |
| HP            | Pavilion g6                 | [cc725d880c](https://linux-hardware.org/?probe=cc725d880c) | Aug 31, 2022 |
| Apple         | MacBookPro9,2               | [3662302886](https://linux-hardware.org/?probe=3662302886) | Aug 31, 2022 |
| Dell          | Inspiron 15-3567            | [710d1e9a9b](https://linux-hardware.org/?probe=710d1e9a9b) | Aug 31, 2022 |
| Dell          | Precision M6400             | [3cf32e24fa](https://linux-hardware.org/?probe=3cf32e24fa) | Aug 30, 2022 |
| Dell          | Latitude 3300               | [bea8e53929](https://linux-hardware.org/?probe=bea8e53929) | Aug 29, 2022 |
| Apple         | MacBookPro5,5               | [97fdbc4a5b](https://linux-hardware.org/?probe=97fdbc4a5b) | Aug 29, 2022 |
| Lenovo        | V14-ADA 82C6                | [ce25a77e25](https://linux-hardware.org/?probe=ce25a77e25) | Aug 29, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [3b26a2ffe2](https://linux-hardware.org/?probe=3b26a2ffe2) | Aug 29, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [98ac365e3c](https://linux-hardware.org/?probe=98ac365e3c) | Aug 28, 2022 |
| Dell          | Studio 1735                 | [912f409b37](https://linux-hardware.org/?probe=912f409b37) | Aug 28, 2022 |
| HP            | 620                         | [b16c60f4cf](https://linux-hardware.org/?probe=b16c60f4cf) | Aug 28, 2022 |
| Acer          | AO722                       | [377ad8686f](https://linux-hardware.org/?probe=377ad8686f) | Aug 28, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [ee07c7a93a](https://linux-hardware.org/?probe=ee07c7a93a) | Aug 27, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [d6c013a669](https://linux-hardware.org/?probe=d6c013a669) | Aug 27, 2022 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [1ea46f19be](https://linux-hardware.org/?probe=1ea46f19be) | Aug 27, 2022 |
| HP            | 15                          | [310d617e09](https://linux-hardware.org/?probe=310d617e09) | Aug 26, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [72888e9acb](https://linux-hardware.org/?probe=72888e9acb) | Aug 25, 2022 |
| HP            | Laptop 14-dk0xxx            | [82da7782ec](https://linux-hardware.org/?probe=82da7782ec) | Aug 25, 2022 |
| HP            | Laptop 15-dy1xxx            | [b201192ebb](https://linux-hardware.org/?probe=b201192ebb) | Aug 25, 2022 |
| Dell          | Latitude E5510              | [c237161d31](https://linux-hardware.org/?probe=c237161d31) | Aug 24, 2022 |
| Lenovo        | ThinkPad T420 4180F75       | [f4a6e9705d](https://linux-hardware.org/?probe=f4a6e9705d) | Aug 24, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [f20e68e820](https://linux-hardware.org/?probe=f20e68e820) | Aug 24, 2022 |
| Lenovo        | IdeaPad 320-15IAP 81A3      | [81b42d221d](https://linux-hardware.org/?probe=81b42d221d) | Aug 24, 2022 |
| Acer          | Aspire A315-54K             | [685d6acc51](https://linux-hardware.org/?probe=685d6acc51) | Aug 23, 2022 |
| Dell          | Latitude E5470              | [4cf5f4680f](https://linux-hardware.org/?probe=4cf5f4680f) | Aug 23, 2022 |
| Google        | Galtic                      | [f06baf315d](https://linux-hardware.org/?probe=f06baf315d) | Aug 22, 2022 |
| Acer          | Enduro EUN314-51WG          | [aa9ea3d520](https://linux-hardware.org/?probe=aa9ea3d520) | Aug 22, 2022 |
| Acer          | TravelMate 5760             | [3d9c208d81](https://linux-hardware.org/?probe=3d9c208d81) | Aug 22, 2022 |
| Dell          | Latitude 3300               | [e8b139ecad](https://linux-hardware.org/?probe=e8b139ecad) | Aug 22, 2022 |
| Dell          | Latitude 3310               | [dedda1b96c](https://linux-hardware.org/?probe=dedda1b96c) | Aug 22, 2022 |
| Acer          | TravelMate 5730             | [ec6fd6cddb](https://linux-hardware.org/?probe=ec6fd6cddb) | Aug 22, 2022 |
| Lenovo        | IdeaPad 500S-14ISK 80Q3     | [fdbec5aab2](https://linux-hardware.org/?probe=fdbec5aab2) | Aug 22, 2022 |
| Fujitsu       | LIFEBOOK UH552              | [15a1f49654](https://linux-hardware.org/?probe=15a1f49654) | Aug 21, 2022 |
| Acer          | AO725                       | [5eed64f77d](https://linux-hardware.org/?probe=5eed64f77d) | Aug 21, 2022 |
| Lenovo        | ThinkPad X200 7458FZ3       | [232835b00b](https://linux-hardware.org/?probe=232835b00b) | Aug 21, 2022 |
| Acer          | Aspire E1-531               | [1292b2297f](https://linux-hardware.org/?probe=1292b2297f) | Aug 21, 2022 |
| HP            | Pavilion dv6                | [0aae35eb95](https://linux-hardware.org/?probe=0aae35eb95) | Aug 19, 2022 |
| Dell          | XPS 13 9360                 | [74b0bedd54](https://linux-hardware.org/?probe=74b0bedd54) | Aug 19, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [c954da96ad](https://linux-hardware.org/?probe=c954da96ad) | Aug 18, 2022 |
| ASUSTek       | X75A1                       | [870fcf0f3c](https://linux-hardware.org/?probe=870fcf0f3c) | Aug 18, 2022 |
| Dell          | Latitude E5510              | [c7defb71d5](https://linux-hardware.org/?probe=c7defb71d5) | Aug 18, 2022 |
| Medion        | Akoya E6418 MD99620         | [6817b38103](https://linux-hardware.org/?probe=6817b38103) | Aug 18, 2022 |
| Acer          | Aspire A515-51G             | [d29438c201](https://linux-hardware.org/?probe=d29438c201) | Aug 18, 2022 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [d78fb85708](https://linux-hardware.org/?probe=d78fb85708) | Aug 18, 2022 |
| Positivo B... | S14SL03                     | [558f5a2f24](https://linux-hardware.org/?probe=558f5a2f24) | Aug 18, 2022 |
| Acer          | Nitro AN515-31              | [471659ffff](https://linux-hardware.org/?probe=471659ffff) | Aug 17, 2022 |
| Dell          | Latitude 3380               | [a99b3cef26](https://linux-hardware.org/?probe=a99b3cef26) | Aug 17, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [9bdceca056](https://linux-hardware.org/?probe=9bdceca056) | Aug 17, 2022 |
| ASUSTek       | N75SF                       | [3b6f89e145](https://linux-hardware.org/?probe=3b6f89e145) | Aug 17, 2022 |
| NEC Comput... | PC-LJ730MG6W                | [c0e6c7edb7](https://linux-hardware.org/?probe=c0e6c7edb7) | Aug 17, 2022 |
| Dell          | Latitude 3310               | [92f66bf3aa](https://linux-hardware.org/?probe=92f66bf3aa) | Aug 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [59080cc039](https://linux-hardware.org/?probe=59080cc039) | Aug 17, 2022 |
| ASUSTek       | Z550SA                      | [03ef043fd9](https://linux-hardware.org/?probe=03ef043fd9) | Aug 17, 2022 |
| HP            | Laptop 14s-fq1xxx           | [92c0a6fe2a](https://linux-hardware.org/?probe=92c0a6fe2a) | Aug 17, 2022 |
| Dell          | XPS 15 9530                 | [71f62cef7a](https://linux-hardware.org/?probe=71f62cef7a) | Aug 16, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [a880d764be](https://linux-hardware.org/?probe=a880d764be) | Aug 16, 2022 |
| Lenovo        | ThinkPad L412 0585A84       | [637fa23dca](https://linux-hardware.org/?probe=637fa23dca) | Aug 16, 2022 |
| Dell          | Latitude 3310               | [1694bfcea7](https://linux-hardware.org/?probe=1694bfcea7) | Aug 16, 2022 |
| Acer          | Aspire ES1-532G             | [cf05c858ab](https://linux-hardware.org/?probe=cf05c858ab) | Aug 15, 2022 |
| Dell          | Latitude E6430              | [6c31827147](https://linux-hardware.org/?probe=6c31827147) | Aug 15, 2022 |
| Dell          | Inspiron 1501               | [11b4c83b79](https://linux-hardware.org/?probe=11b4c83b79) | Aug 15, 2022 |
| Samsung       | NC210/NC110                 | [3dcdc1dc6a](https://linux-hardware.org/?probe=3dcdc1dc6a) | Aug 15, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [4b1440875b](https://linux-hardware.org/?probe=4b1440875b) | Aug 14, 2022 |
| ASUSTek       | X540LA                      | [15ffff65c0](https://linux-hardware.org/?probe=15ffff65c0) | Aug 14, 2022 |
| HP            | ProBook 4330s               | [62ff6ffc08](https://linux-hardware.org/?probe=62ff6ffc08) | Aug 14, 2022 |
| Acer          | Aspire A515-54G             | [e9c64a8a5c](https://linux-hardware.org/?probe=e9c64a8a5c) | Aug 14, 2022 |
| Acer          | Aspire VN7-571G             | [0d6dfdd6e0](https://linux-hardware.org/?probe=0d6dfdd6e0) | Aug 14, 2022 |
| HP            | Pavilion dv9500             | [fd3bd18049](https://linux-hardware.org/?probe=fd3bd18049) | Aug 14, 2022 |
| Toshiba       | Satellite P200              | [83fcabac55](https://linux-hardware.org/?probe=83fcabac55) | Aug 13, 2022 |
| Dell          | Vostro 1520                 | [9dab88f3ee](https://linux-hardware.org/?probe=9dab88f3ee) | Aug 13, 2022 |
| Positivo      | EC10IS1                     | [b66cd42f99](https://linux-hardware.org/?probe=b66cd42f99) | Aug 13, 2022 |
| Toshiba       | Satellite L500              | [0d58c17039](https://linux-hardware.org/?probe=0d58c17039) | Aug 13, 2022 |
| Positivo      | Mobile                      | [bddf3b59d4](https://linux-hardware.org/?probe=bddf3b59d4) | Aug 12, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [40814201a2](https://linux-hardware.org/?probe=40814201a2) | Aug 12, 2022 |
| Lenovo        | ThinkPad T61 64665DG        | [ff1be50f8c](https://linux-hardware.org/?probe=ff1be50f8c) | Aug 12, 2022 |
| Lenovo        | ThinkPad X201 3626HMG       | [1d08c103c7](https://linux-hardware.org/?probe=1d08c103c7) | Aug 12, 2022 |
| ASUSTek       | K73BR                       | [67f5d3f176](https://linux-hardware.org/?probe=67f5d3f176) | Aug 12, 2022 |
| Acer          | Aspire 4330 V1.22           | [dee8895134](https://linux-hardware.org/?probe=dee8895134) | Aug 12, 2022 |
| HP            | EliteBook 820 G3            | [c1b14847f1](https://linux-hardware.org/?probe=c1b14847f1) | Aug 12, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | [d949d71a19](https://linux-hardware.org/?probe=d949d71a19) | Aug 12, 2022 |
| Lenovo        | Unknown                     | [79688945e1](https://linux-hardware.org/?probe=79688945e1) | Aug 11, 2022 |
| Dell          | G5 5505                     | [cbbcb7c9a2](https://linux-hardware.org/?probe=cbbcb7c9a2) | Aug 11, 2022 |
| Dell          | Vostro 3401                 | [29f3354492](https://linux-hardware.org/?probe=29f3354492) | Aug 11, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [cac00fb432](https://linux-hardware.org/?probe=cac00fb432) | Aug 11, 2022 |
| HP            | Pavilion dm3                | [7152a48ede](https://linux-hardware.org/?probe=7152a48ede) | Aug 10, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cc51e49c51](https://linux-hardware.org/?probe=cc51e49c51) | Aug 10, 2022 |
| HP            | 240 G3                      | [77225815d2](https://linux-hardware.org/?probe=77225815d2) | Aug 10, 2022 |
| Toshiba       | Satellite A300              | [4f83e69c06](https://linux-hardware.org/?probe=4f83e69c06) | Aug 09, 2022 |
| HP            | 630                         | [fc9bc69e9a](https://linux-hardware.org/?probe=fc9bc69e9a) | Aug 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9d6be5eb68](https://linux-hardware.org/?probe=9d6be5eb68) | Aug 08, 2022 |
| Acer          | Nitro AN515-31              | [0dbab56588](https://linux-hardware.org/?probe=0dbab56588) | Aug 08, 2022 |
| HP            | 15                          | [ef66e0296e](https://linux-hardware.org/?probe=ef66e0296e) | Aug 08, 2022 |
| HP            | ProBook 430 G4              | [616a031820](https://linux-hardware.org/?probe=616a031820) | Aug 08, 2022 |
| Dell          | Latitude E7240              | [1f20b0f54b](https://linux-hardware.org/?probe=1f20b0f54b) | Aug 08, 2022 |
| Dell          | Latitude E6420              | [3817e724ac](https://linux-hardware.org/?probe=3817e724ac) | Aug 08, 2022 |
| HP            | Compaq 15                   | [de4b6e0511](https://linux-hardware.org/?probe=de4b6e0511) | Aug 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f9850e0a1e](https://linux-hardware.org/?probe=f9850e0a1e) | Aug 07, 2022 |
| Timi          | RedmiBook Pro 15S           | [4e36acba35](https://linux-hardware.org/?probe=4e36acba35) | Aug 07, 2022 |
| Dell          | Latitude 3189               | [63c2818521](https://linux-hardware.org/?probe=63c2818521) | Aug 07, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [810a9d1c2c](https://linux-hardware.org/?probe=810a9d1c2c) | Aug 07, 2022 |
| MSI           | GL75 Leopard 10SDK          | [bfceb8ba35](https://linux-hardware.org/?probe=bfceb8ba35) | Aug 07, 2022 |
| Lenovo        | IdeaPad S145-15IKB 81VD     | [f3a36d0f3a](https://linux-hardware.org/?probe=f3a36d0f3a) | Aug 07, 2022 |
| Acer          | Swift SF114-31              | [b1cba472dc](https://linux-hardware.org/?probe=b1cba472dc) | Aug 06, 2022 |
| Lenovo        | ThinkPad T430s 2356LNG      | [255560d675](https://linux-hardware.org/?probe=255560d675) | Aug 06, 2022 |
| ASUSTek       | X555LN                      | [77092711a0](https://linux-hardware.org/?probe=77092711a0) | Aug 06, 2022 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [6b1d79046a](https://linux-hardware.org/?probe=6b1d79046a) | Aug 06, 2022 |
| ASUSTek       | UX303UA                     | [73145490fa](https://linux-hardware.org/?probe=73145490fa) | Aug 06, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [b9a68ae76c](https://linux-hardware.org/?probe=b9a68ae76c) | Aug 06, 2022 |
| Acer          | E1-510                      | [05ea3ff386](https://linux-hardware.org/?probe=05ea3ff386) | Aug 05, 2022 |
| Dell          | Latitude 3310               | [97ac18f196](https://linux-hardware.org/?probe=97ac18f196) | Aug 05, 2022 |
| Dell          | Latitude 3410               | [8181c3588f](https://linux-hardware.org/?probe=8181c3588f) | Aug 05, 2022 |
| Dell          | Precision M4700             | [25efd53898](https://linux-hardware.org/?probe=25efd53898) | Aug 05, 2022 |
| HP            | ProBook 6450b               | [699b27e34f](https://linux-hardware.org/?probe=699b27e34f) | Aug 05, 2022 |
| Lenovo        | ThinkPad X230 2325U9T       | [0f0e8ec24f](https://linux-hardware.org/?probe=0f0e8ec24f) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [cdc1f14772](https://linux-hardware.org/?probe=cdc1f14772) | Aug 04, 2022 |
| Dell          | Latitude 3490               | [fa1c5f753f](https://linux-hardware.org/?probe=fa1c5f753f) | Aug 04, 2022 |
| Dell          | Latitude 3310               | [9b9bed6ac6](https://linux-hardware.org/?probe=9b9bed6ac6) | Aug 04, 2022 |
| Dell          | System Inspiron N4110       | [22938e2e62](https://linux-hardware.org/?probe=22938e2e62) | Aug 03, 2022 |
| Lenovo        | ThinkPad T530 2429W4Z       | [2d95f7cc7e](https://linux-hardware.org/?probe=2d95f7cc7e) | Aug 03, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [f1d5a6ab3f](https://linux-hardware.org/?probe=f1d5a6ab3f) | Aug 03, 2022 |
| Lenovo        | ThinkPad SL510 28477NG      | [5ddf195177](https://linux-hardware.org/?probe=5ddf195177) | Aug 03, 2022 |
| Dell          | Latitude E6430              | [15e26c7cc5](https://linux-hardware.org/?probe=15e26c7cc5) | Aug 02, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [71c6ba6061](https://linux-hardware.org/?probe=71c6ba6061) | Aug 01, 2022 |
| Dell          | Latitude E7450              | [38051fe609](https://linux-hardware.org/?probe=38051fe609) | Aug 01, 2022 |
| Packard Be... | EasyNote TK13BZ             | [530d3ad8db](https://linux-hardware.org/?probe=530d3ad8db) | Aug 01, 2022 |
| HP            | ProBook 440 G2              | [00dd80ba31](https://linux-hardware.org/?probe=00dd80ba31) | Aug 01, 2022 |
| Acer          | Z476                        | [ade85b90c1](https://linux-hardware.org/?probe=ade85b90c1) | Aug 01, 2022 |
| Toshiba       | Satellite-C845              | [6ee9ea90a5](https://linux-hardware.org/?probe=6ee9ea90a5) | Aug 01, 2022 |
| GPU Compan... | GWNR71517                   | [72278643e8](https://linux-hardware.org/?probe=72278643e8) | Aug 01, 2022 |
| Acer          | Aspire ES1-523              | [d14f053671](https://linux-hardware.org/?probe=d14f053671) | Aug 01, 2022 |
| Acer          | Aspire E1-571               | [7102c56d5b](https://linux-hardware.org/?probe=7102c56d5b) | Aug 01, 2022 |
| Packard Be... | EasyNote TM85               | [a6df06f9e5](https://linux-hardware.org/?probe=a6df06f9e5) | Jul 31, 2022 |
| Lenovo        | ThinkPad T460 20FMS02R0G    | [0aa31e3c39](https://linux-hardware.org/?probe=0aa31e3c39) | Jul 31, 2022 |
| Acer          | TravelMate B118-M           | [490edd75cf](https://linux-hardware.org/?probe=490edd75cf) | Jul 31, 2022 |
| HP            | ProBook 6570b               | [333a24bdee](https://linux-hardware.org/?probe=333a24bdee) | Jul 31, 2022 |
| Acer          | Aspire VN7-791G             | [3e72040097](https://linux-hardware.org/?probe=3e72040097) | Jul 31, 2022 |
| HP            | 250 G7 Notebook PC          | [6204ce9d95](https://linux-hardware.org/?probe=6204ce9d95) | Jul 31, 2022 |
| eMachines     | Unknown                     | [8c6dcb08a7](https://linux-hardware.org/?probe=8c6dcb08a7) | Jul 31, 2022 |
| Notebook      | W54_W94_W955TU,-T,-C        | [7b0b52e138](https://linux-hardware.org/?probe=7b0b52e138) | Jul 31, 2022 |
| Compaq        | Presario CQ-23              | [76ea82c314](https://linux-hardware.org/?probe=76ea82c314) | Jul 30, 2022 |
| HP            | EliteBook 8470p             | [2171abfd3d](https://linux-hardware.org/?probe=2171abfd3d) | Jul 30, 2022 |
| Apple         | MacBookPro7,1               | [b846739765](https://linux-hardware.org/?probe=b846739765) | Jul 30, 2022 |
| ASUSTek       | K501LX                      | [8ea0c7daa9](https://linux-hardware.org/?probe=8ea0c7daa9) | Jul 30, 2022 |
| HP            | Laptop 15s-eq1xxx           | [ee5c151c3a](https://linux-hardware.org/?probe=ee5c151c3a) | Jul 30, 2022 |
| ASUSTek       | K53E                        | [3ca340212e](https://linux-hardware.org/?probe=3ca340212e) | Jul 30, 2022 |
| Lenovo        | G570 4334                   | [a29c1c816a](https://linux-hardware.org/?probe=a29c1c816a) | Jul 30, 2022 |
| Fujitsu       | LIFEBOOK V1020              | [e33ac2916d](https://linux-hardware.org/?probe=e33ac2916d) | Jul 30, 2022 |
| MSI           | GF63 8RD                    | [fdb72c3ec3](https://linux-hardware.org/?probe=fdb72c3ec3) | Jul 29, 2022 |
| Acer          | Aspire A317-33              | [ab07e43574](https://linux-hardware.org/?probe=ab07e43574) | Jul 29, 2022 |
| Sony          | VPCEA45FL                   | [8079ec1351](https://linux-hardware.org/?probe=8079ec1351) | Jul 29, 2022 |
| Lenovo        | ThinkPad T440s 20ARS4PR0... | [5b91ff037d](https://linux-hardware.org/?probe=5b91ff037d) | Jul 29, 2022 |
| HP            | ProBook 6570b               | [231ebd2edc](https://linux-hardware.org/?probe=231ebd2edc) | Jul 29, 2022 |
| Acer          | Aspire 7741                 | [02e9f6a808](https://linux-hardware.org/?probe=02e9f6a808) | Jul 29, 2022 |
| Dell          | Vostro 15-3568              | [a42627d17e](https://linux-hardware.org/?probe=a42627d17e) | Jul 29, 2022 |
| Lenovo        | ThinkPad S5 Yoga 15 20DR... | [147d305ac1](https://linux-hardware.org/?probe=147d305ac1) | Jul 29, 2022 |
| Lenovo        | ThinkPad X230 23253B3       | [fa19ec3adf](https://linux-hardware.org/?probe=fa19ec3adf) | Jul 29, 2022 |
| Google        | Candy                       | [cba2906cfd](https://linux-hardware.org/?probe=cba2906cfd) | Jul 29, 2022 |
| HP            | ProBook 430 G5              | [f424705bd7](https://linux-hardware.org/?probe=f424705bd7) | Jul 29, 2022 |
| Acer          | Aspire 5750                 | [e3f2dd0271](https://linux-hardware.org/?probe=e3f2dd0271) | Jul 29, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [03b39a36f1](https://linux-hardware.org/?probe=03b39a36f1) | Jul 29, 2022 |
| Lenovo        | G50-45 80E3                 | [61a6277614](https://linux-hardware.org/?probe=61a6277614) | Jul 28, 2022 |
| ASUSTek       | X551MA                      | [668a02296d](https://linux-hardware.org/?probe=668a02296d) | Jul 28, 2022 |
| HP            | ProBook 4515s               | [b9759d3b5d](https://linux-hardware.org/?probe=b9759d3b5d) | Jul 28, 2022 |
| HP            | 250 G5 Notebook PC          | [75477a4d7a](https://linux-hardware.org/?probe=75477a4d7a) | Jul 28, 2022 |
| ASUSTek       | K53U                        | [7db28a1538](https://linux-hardware.org/?probe=7db28a1538) | Jul 28, 2022 |
| Acer          | Aspire 3100                 | [26c6af2a55](https://linux-hardware.org/?probe=26c6af2a55) | Jul 28, 2022 |
| Toshiba       | Satellite P50-B-118         | [b46f72c280](https://linux-hardware.org/?probe=b46f72c280) | Jul 28, 2022 |
| HP            | 2000                        | [531b786836](https://linux-hardware.org/?probe=531b786836) | Jul 28, 2022 |
| Wortmann      | TERRA_MOBILE_1528P/1748P    | [7bcdc30be3](https://linux-hardware.org/?probe=7bcdc30be3) | Jul 28, 2022 |
| Digibras      | NH4CU03                     | [bf8a8c589a](https://linux-hardware.org/?probe=bf8a8c589a) | Jul 28, 2022 |
| Positivo      | H14BT58                     | [7f271e5d68](https://linux-hardware.org/?probe=7f271e5d68) | Jul 28, 2022 |
| Toshiba       | Satellite C850D-11K         | [544f2db462](https://linux-hardware.org/?probe=544f2db462) | Jul 28, 2022 |
| Sony          | VPCS110FL                   | [8576955f3c](https://linux-hardware.org/?probe=8576955f3c) | Jul 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [94a6b79798](https://linux-hardware.org/?probe=94a6b79798) | Jul 27, 2022 |
| Samsung       | 550XBE/350XBE               | [b7fabad758](https://linux-hardware.org/?probe=b7fabad758) | Jul 27, 2022 |
| HP            | Pavilion g7                 | [75fa7f0ce4](https://linux-hardware.org/?probe=75fa7f0ce4) | Jul 27, 2022 |
| Dell          | XPS 13 9300                 | [8f0daaf341](https://linux-hardware.org/?probe=8f0daaf341) | Jul 27, 2022 |
| ASUSTek       | S551LB                      | [8660a06086](https://linux-hardware.org/?probe=8660a06086) | Jul 27, 2022 |
| Dell          | Latitude E6330              | [5ee8d985ed](https://linux-hardware.org/?probe=5ee8d985ed) | Jul 27, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [17f64584bb](https://linux-hardware.org/?probe=17f64584bb) | Jul 27, 2022 |
| HP            | Compaq 6720s                | [d8546f791c](https://linux-hardware.org/?probe=d8546f791c) | Jul 27, 2022 |
| HP            | EliteBook 8460p             | [7b2de05256](https://linux-hardware.org/?probe=7b2de05256) | Jul 27, 2022 |
| Acer          | TravelMate P633-M           | [7d346db799](https://linux-hardware.org/?probe=7d346db799) | Jul 27, 2022 |
| Lenovo        | ThinkPad T420 4236CTO       | [6797b09b3b](https://linux-hardware.org/?probe=6797b09b3b) | Jul 27, 2022 |
| Apple         | MacBookPro8,1               | [cf1f919243](https://linux-hardware.org/?probe=cf1f919243) | Jul 27, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [44954e91a2](https://linux-hardware.org/?probe=44954e91a2) | Jul 27, 2022 |
| Sony          | VPCEB26FG                   | [49c139799c](https://linux-hardware.org/?probe=49c139799c) | Jul 27, 2022 |
| HP            | Compaq Presario CQ60        | [06fe56588b](https://linux-hardware.org/?probe=06fe56588b) | Jul 27, 2022 |
| Dell          | Latitude E7240              | [6af993caf7](https://linux-hardware.org/?probe=6af993caf7) | Jul 27, 2022 |
| Toshiba       | Satellite C870D-116         | [d92af8246c](https://linux-hardware.org/?probe=d92af8246c) | Jul 26, 2022 |
| HP            | ProBook 645 G1              | [457c35707a](https://linux-hardware.org/?probe=457c35707a) | Jul 26, 2022 |
| Acer          | Aspire 3810T                | [92f9c99b5e](https://linux-hardware.org/?probe=92f9c99b5e) | Jul 26, 2022 |
| Dell          | Latitude 131L               | [ec8717bc3f](https://linux-hardware.org/?probe=ec8717bc3f) | Jul 26, 2022 |
| Dell          | Latitude 3300               | [64cf4b87d9](https://linux-hardware.org/?probe=64cf4b87d9) | Jul 26, 2022 |
| Toshiba       | dynabook R734/K             | [a5e7d4c919](https://linux-hardware.org/?probe=a5e7d4c919) | Jul 26, 2022 |
| Dell          | Vostro 15-3568              | [da71f235a2](https://linux-hardware.org/?probe=da71f235a2) | Jul 25, 2022 |
| HP            | Pavilion Notebook           | [660665c762](https://linux-hardware.org/?probe=660665c762) | Jul 25, 2022 |
| Dell          | Latitude 3310               | [0fe12d0d48](https://linux-hardware.org/?probe=0fe12d0d48) | Jul 25, 2022 |
| Acer          | Aspire 5741G                | [a4f8482423](https://linux-hardware.org/?probe=a4f8482423) | Jul 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [375ba933ba](https://linux-hardware.org/?probe=375ba933ba) | Jul 25, 2022 |
| Lenovo        | G50-45 80E3                 | [e6b9106560](https://linux-hardware.org/?probe=e6b9106560) | Jul 24, 2022 |
| Lenovo        | ThinkPad P50 20EN0008GE     | [93ec0d85ab](https://linux-hardware.org/?probe=93ec0d85ab) | Jul 24, 2022 |
| Toshiba       | Portable PC                 | [00cd85e866](https://linux-hardware.org/?probe=00cd85e866) | Jul 24, 2022 |
| Apple         | MacBookAir9,1               | [cf4d815653](https://linux-hardware.org/?probe=cf4d815653) | Jul 24, 2022 |
| HP            | Notebook                    | [17893fb905](https://linux-hardware.org/?probe=17893fb905) | Jul 24, 2022 |
| ASUSTek       | X455LJ                      | [49af56cbe0](https://linux-hardware.org/?probe=49af56cbe0) | Jul 24, 2022 |
| ASUSTek       | K50IJ                       | [60af40882b](https://linux-hardware.org/?probe=60af40882b) | Jul 24, 2022 |
| Dell          | Latitude E6430              | [8bc3b0f962](https://linux-hardware.org/?probe=8bc3b0f962) | Jul 23, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c4c41ad0b5](https://linux-hardware.org/?probe=c4c41ad0b5) | Jul 23, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [acdc35979c](https://linux-hardware.org/?probe=acdc35979c) | Jul 23, 2022 |
| AZW           | GT-R                        | [eb7604ea1c](https://linux-hardware.org/?probe=eb7604ea1c) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480 20L6A0XKUK    | [fe5dae3d4a](https://linux-hardware.org/?probe=fe5dae3d4a) | Jul 22, 2022 |
| Lenovo        | ThinkPad T61 6458W4B        | [3d51bdb900](https://linux-hardware.org/?probe=3d51bdb900) | Jul 22, 2022 |
| Acer          | Aspire 5738                 | [8b9c2d3dc0](https://linux-hardware.org/?probe=8b9c2d3dc0) | Jul 22, 2022 |
| Lenovo        | ThinkPad Helix 36986EU      | [294d96aff6](https://linux-hardware.org/?probe=294d96aff6) | Jul 22, 2022 |
| Positivo      | J14AL11                     | [7510e905d8](https://linux-hardware.org/?probe=7510e905d8) | Jul 22, 2022 |
| HP            | Notebook                    | [e859de5718](https://linux-hardware.org/?probe=e859de5718) | Jul 21, 2022 |
| Dell          | Latitude 3310               | [bc6103f96b](https://linux-hardware.org/?probe=bc6103f96b) | Jul 21, 2022 |
| Dell          | Latitude 3310               | [abe159e82a](https://linux-hardware.org/?probe=abe159e82a) | Jul 21, 2022 |
| Dell          | Latitude 3310               | [d90f147df3](https://linux-hardware.org/?probe=d90f147df3) | Jul 21, 2022 |
| Dell          | Latitude 3310               | [324b95a49a](https://linux-hardware.org/?probe=324b95a49a) | Jul 21, 2022 |
| METAPHYUNI    | MetamechBook                | [169a9a0636](https://linux-hardware.org/?probe=169a9a0636) | Jul 21, 2022 |
| Sony          | SVE1513R1EB                 | [61c51541dd](https://linux-hardware.org/?probe=61c51541dd) | Jul 21, 2022 |
| Dell          | Latitude E5450              | [c8243bf1a8](https://linux-hardware.org/?probe=c8243bf1a8) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [9863a7ed67](https://linux-hardware.org/?probe=9863a7ed67) | Jul 20, 2022 |
| Lenovo        | V130-15IKB 81HN             | [fe2f5a993c](https://linux-hardware.org/?probe=fe2f5a993c) | Jul 20, 2022 |
| Dell          | Latitude 3310               | [086f88be40](https://linux-hardware.org/?probe=086f88be40) | Jul 20, 2022 |
| Dell          | Inspiron 5579               | [52e88ad171](https://linux-hardware.org/?probe=52e88ad171) | Jul 20, 2022 |
| Dell          | Latitude 3310               | [0cb2abc6bc](https://linux-hardware.org/?probe=0cb2abc6bc) | Jul 20, 2022 |
| Dell          | Latitude 3310               | [dbd9b101c2](https://linux-hardware.org/?probe=dbd9b101c2) | Jul 20, 2022 |
| Dell          | Latitude 5285               | [2b46125d79](https://linux-hardware.org/?probe=2b46125d79) | Jul 20, 2022 |
| HP            | Dev One Notebook PC         | [e386bc211b](https://linux-hardware.org/?probe=e386bc211b) | Jul 20, 2022 |
| HP            | Laptop 14-ck0xxx            | [78c2b82b87](https://linux-hardware.org/?probe=78c2b82b87) | Jul 19, 2022 |
| HP            | 250 G6 Notebook PC          | [83d1355e61](https://linux-hardware.org/?probe=83d1355e61) | Jul 19, 2022 |
| Gateway       | NV53A                       | [2674f3160f](https://linux-hardware.org/?probe=2674f3160f) | Jul 19, 2022 |
| Acer          | Aspire A515-51G             | [4414dd4c1b](https://linux-hardware.org/?probe=4414dd4c1b) | Jul 19, 2022 |
| Samsung       | 270E5G/270E5U               | [c26ed846e9](https://linux-hardware.org/?probe=c26ed846e9) | Jul 19, 2022 |
| Acer          | Aspire E3-112               | [475d626fd5](https://linux-hardware.org/?probe=475d626fd5) | Jul 19, 2022 |
| HUAWEI        | MateBook D                  | [5d7a616dd1](https://linux-hardware.org/?probe=5d7a616dd1) | Jul 18, 2022 |
| Acer          | Aspire ES1-411              | [5d551a94bd](https://linux-hardware.org/?probe=5d551a94bd) | Jul 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [68a78a8ed1](https://linux-hardware.org/?probe=68a78a8ed1) | Jul 18, 2022 |
| Teclast       | F15 Plus                    | [6201934176](https://linux-hardware.org/?probe=6201934176) | Jul 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [14d23344e2](https://linux-hardware.org/?probe=14d23344e2) | Jul 17, 2022 |
| HP            | ProBook 4441s               | [b108eaada9](https://linux-hardware.org/?probe=b108eaada9) | Jul 17, 2022 |
| Digibras      | NH4CU03                     | [803b7d3211](https://linux-hardware.org/?probe=803b7d3211) | Jul 16, 2022 |
| Sony          | VPCEA3M1R                   | [0bdfc50874](https://linux-hardware.org/?probe=0bdfc50874) | Jul 16, 2022 |
| Digibras      | NH4CU53                     | [f6b402afe8](https://linux-hardware.org/?probe=f6b402afe8) | Jul 16, 2022 |
| MSI           | GP62 6QE                    | [7e7c05c6b6](https://linux-hardware.org/?probe=7e7c05c6b6) | Jul 16, 2022 |
| Acer          | Nitro AN517-54              | [68f6109054](https://linux-hardware.org/?probe=68f6109054) | Jul 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b511d2883b](https://linux-hardware.org/?probe=b511d2883b) | Jul 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [eb5b940f17](https://linux-hardware.org/?probe=eb5b940f17) | Jul 16, 2022 |
| Sony          | SVE1513H1EW                 | [6e4d66c2ee](https://linux-hardware.org/?probe=6e4d66c2ee) | Jul 15, 2022 |
| HP            | ProBook 4545s               | [12575a32d1](https://linux-hardware.org/?probe=12575a32d1) | Jul 15, 2022 |
| MSI           | GE72 6QL                    | [7c22c38989](https://linux-hardware.org/?probe=7c22c38989) | Jul 15, 2022 |
| Dell          | Latitude E6530              | [67eec0ba19](https://linux-hardware.org/?probe=67eec0ba19) | Jul 15, 2022 |
| HP            | Pavilion dv6700             | [4d653cf4e6](https://linux-hardware.org/?probe=4d653cf4e6) | Jul 15, 2022 |
| Fujitsu       | LIFEBOOK A512               | [7e9ba006f3](https://linux-hardware.org/?probe=7e9ba006f3) | Jul 15, 2022 |
| HP            | Pavilion dv7                | [4065c23b56](https://linux-hardware.org/?probe=4065c23b56) | Jul 15, 2022 |
| HP            | EliteBook 8540p             | [52a3abee65](https://linux-hardware.org/?probe=52a3abee65) | Jul 15, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | [7a661a1449](https://linux-hardware.org/?probe=7a661a1449) | Jul 15, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | [b85cc7c80c](https://linux-hardware.org/?probe=b85cc7c80c) | Jul 14, 2022 |
| HP            | Pavilion dv6700             | [c8bf7e091c](https://linux-hardware.org/?probe=c8bf7e091c) | Jul 14, 2022 |
| HP            | EliteBook 8460p             | [c3f5c82808](https://linux-hardware.org/?probe=c3f5c82808) | Jul 14, 2022 |
| ASUSTek       | UX301LA                     | [3d4655e7cf](https://linux-hardware.org/?probe=3d4655e7cf) | Jul 14, 2022 |
| Purism        | Librem 14                   | [5a0337506b](https://linux-hardware.org/?probe=5a0337506b) | Jul 14, 2022 |
| Notebook      | NL40_50GU                   | [d4e652dc65](https://linux-hardware.org/?probe=d4e652dc65) | Jul 13, 2022 |
| Toshiba       | Satellite Pro R50-C         | [25d6e4de23](https://linux-hardware.org/?probe=25d6e4de23) | Jul 13, 2022 |
| HP            | Dev One Notebook PC         | [24c64c6221](https://linux-hardware.org/?probe=24c64c6221) | Jul 13, 2022 |
| HP            | Laptop 15s-eq1xxx           | [1c3c80b88e](https://linux-hardware.org/?probe=1c3c80b88e) | Jul 13, 2022 |
| Dell          | XPS 13 9360                 | [ef3bc84295](https://linux-hardware.org/?probe=ef3bc84295) | Jul 13, 2022 |
| Acer          | Predator PH315-51           | [37b04a8093](https://linux-hardware.org/?probe=37b04a8093) | Jul 12, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [b0b89af62e](https://linux-hardware.org/?probe=b0b89af62e) | Jul 12, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [bbb311969a](https://linux-hardware.org/?probe=bbb311969a) | Jul 12, 2022 |
| Lenovo        | G575 4383                   | [8bd6296a3e](https://linux-hardware.org/?probe=8bd6296a3e) | Jul 12, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [1599e9e013](https://linux-hardware.org/?probe=1599e9e013) | Jul 11, 2022 |
| HP            | Pavilion g4                 | [87a044a9c7](https://linux-hardware.org/?probe=87a044a9c7) | Jul 11, 2022 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [d088d6021c](https://linux-hardware.org/?probe=d088d6021c) | Jul 11, 2022 |
| Apple         | MacBookAir3,2               | [e3f89d4d16](https://linux-hardware.org/?probe=e3f89d4d16) | Jul 10, 2022 |
| HP            | Laptop 15-dy1xxx            | [36b1a0480d](https://linux-hardware.org/?probe=36b1a0480d) | Jul 10, 2022 |
| Acer          | Aspire A515-44              | [c0d1086ae8](https://linux-hardware.org/?probe=c0d1086ae8) | Jul 09, 2022 |
| Acer          | Swift SF114-34              | [cf0d8e217c](https://linux-hardware.org/?probe=cf0d8e217c) | Jul 09, 2022 |
| Lenovo        | V15-ADA 82C7                | [3324f369f7](https://linux-hardware.org/?probe=3324f369f7) | Jul 09, 2022 |
| Lenovo        | G40-30 80FY                 | [35d55776f6](https://linux-hardware.org/?probe=35d55776f6) | Jul 09, 2022 |
| Framework     | Laptop                      | [09fa73cc57](https://linux-hardware.org/?probe=09fa73cc57) | Jul 09, 2022 |
| Dell          | Vostro 15 3515              | [c6e9a42a66](https://linux-hardware.org/?probe=c6e9a42a66) | Jul 08, 2022 |
| HP            | ProBook 4510s               | [ae51b4e466](https://linux-hardware.org/?probe=ae51b4e466) | Jul 08, 2022 |
| ASUSTek       | S551LN                      | [1e64e5d64e](https://linux-hardware.org/?probe=1e64e5d64e) | Jul 08, 2022 |
| HP            | Notebook                    | [0dc44e8da9](https://linux-hardware.org/?probe=0dc44e8da9) | Jul 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [4f02f261b3](https://linux-hardware.org/?probe=4f02f261b3) | Jul 08, 2022 |
| Toshiba       | Satellite C75D-B            | [3624ac1024](https://linux-hardware.org/?probe=3624ac1024) | Jul 08, 2022 |
| Acer          | Aspire ES1-512              | [aa2ad87835](https://linux-hardware.org/?probe=aa2ad87835) | Jul 08, 2022 |
| HP            | EliteBook 8460p             | [4f0cf74fe4](https://linux-hardware.org/?probe=4f0cf74fe4) | Jul 07, 2022 |
| HP            | ProBook 4310s               | [86ae79b260](https://linux-hardware.org/?probe=86ae79b260) | Jul 07, 2022 |
| ASUSTek       | GL553VD                     | [6b5e1735a7](https://linux-hardware.org/?probe=6b5e1735a7) | Jul 07, 2022 |
| HP            | G56                         | [5c38722298](https://linux-hardware.org/?probe=5c38722298) | Jul 07, 2022 |
| Acer          | Aspire V3-471               | [75664ddf0f](https://linux-hardware.org/?probe=75664ddf0f) | Jul 07, 2022 |
| Lenovo        | ThinkPad T470s 20HGS0KE0... | [2d63b4ba76](https://linux-hardware.org/?probe=2d63b4ba76) | Jul 06, 2022 |
| Unknown       | Unknown                     | [e4a8ad0984](https://linux-hardware.org/?probe=e4a8ad0984) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | [498f4edafb](https://linux-hardware.org/?probe=498f4edafb) | Jul 05, 2022 |
| ASUSTek       | K53SC                       | [4f31f807cb](https://linux-hardware.org/?probe=4f31f807cb) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | [1264fab131](https://linux-hardware.org/?probe=1264fab131) | Jul 05, 2022 |
| HP            | Compaq CQ58                 | [d46da7be57](https://linux-hardware.org/?probe=d46da7be57) | Jul 05, 2022 |
| HP            | EliteBook 8570p             | [8782b09be9](https://linux-hardware.org/?probe=8782b09be9) | Jul 05, 2022 |
| Dell          | Inspiron 14-3467            | [b9a61ec06d](https://linux-hardware.org/?probe=b9a61ec06d) | Jul 05, 2022 |
| HP            | Laptop 15-da0xxx            | [5c39c57896](https://linux-hardware.org/?probe=5c39c57896) | Jul 04, 2022 |
| ASUSTek       | GL703VD                     | [dc966787de](https://linux-hardware.org/?probe=dc966787de) | Jul 04, 2022 |
| Sony          | VGN-FZ31Z                   | [62d8b20ff8](https://linux-hardware.org/?probe=62d8b20ff8) | Jul 04, 2022 |
| HP            | Pavilion dv4                | [d40a5bd13e](https://linux-hardware.org/?probe=d40a5bd13e) | Jul 04, 2022 |
| Dell          | Latitude E7450              | [6dc8d46993](https://linux-hardware.org/?probe=6dc8d46993) | Jul 02, 2022 |
| Dell          | Precision M6800             | [ba446bde45](https://linux-hardware.org/?probe=ba446bde45) | Jul 02, 2022 |
| Samsung       | 300E5M/300E5L               | [497939c649](https://linux-hardware.org/?probe=497939c649) | Jul 02, 2022 |
| Samsung       | Q210/P210                   | [dfc97062be](https://linux-hardware.org/?probe=dfc97062be) | Jul 01, 2022 |
| Acer          | Extensa 5220                | [1ee1e31b52](https://linux-hardware.org/?probe=1ee1e31b52) | Jul 01, 2022 |
| Apple         | MacBookPro8,1               | [88e0a63fab](https://linux-hardware.org/?probe=88e0a63fab) | Jun 30, 2022 |
| Acer          | Aspire 4732Z                | [1bf580aa91](https://linux-hardware.org/?probe=1bf580aa91) | Jun 30, 2022 |
| Dell          | Precision M6800             | [1eccdbb04e](https://linux-hardware.org/?probe=1eccdbb04e) | Jun 30, 2022 |
| Acer          | Aspire 5735                 | [b930fd3fcd](https://linux-hardware.org/?probe=b930fd3fcd) | Jun 29, 2022 |
| Dell          | Precision M6800             | [5b30cb4b9a](https://linux-hardware.org/?probe=5b30cb4b9a) | Jun 29, 2022 |
| AMI           | Intel                       | [2b592e2f4a](https://linux-hardware.org/?probe=2b592e2f4a) | Jun 29, 2022 |
| HP            | Compaq CQ45                 | [74948790d0](https://linux-hardware.org/?probe=74948790d0) | Jun 29, 2022 |
| Dell          | Precision M6800             | [49b1b7edec](https://linux-hardware.org/?probe=49b1b7edec) | Jun 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [ed40a2bae5](https://linux-hardware.org/?probe=ed40a2bae5) | Jun 28, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | [a767fd4cb1](https://linux-hardware.org/?probe=a767fd4cb1) | Jun 28, 2022 |
| HP            | Laptop 14-dk1xxx            | [6932a00eed](https://linux-hardware.org/?probe=6932a00eed) | Jun 28, 2022 |
| Lenovo        | Z40-75 80DW                 | [1fc3b34132](https://linux-hardware.org/?probe=1fc3b34132) | Jun 27, 2022 |
| Acer          | Aspire A515-41G             | [cbb6f48321](https://linux-hardware.org/?probe=cbb6f48321) | Jun 27, 2022 |
| Dell          | Latitude E6430              | [76c22c2645](https://linux-hardware.org/?probe=76c22c2645) | Jun 26, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [240018e48a](https://linux-hardware.org/?probe=240018e48a) | Jun 26, 2022 |
| Lenovo        | S20-30 Touch 20434          | [b4ebe70967](https://linux-hardware.org/?probe=b4ebe70967) | Jun 26, 2022 |
| Toshiba       | Satellite C855-2CF          | [9e062a8425](https://linux-hardware.org/?probe=9e062a8425) | Jun 26, 2022 |
| HP            | Pavilion dv6700             | [352a224c3f](https://linux-hardware.org/?probe=352a224c3f) | Jun 26, 2022 |
| Toshiba       | Satellite C660D             | [fc25883979](https://linux-hardware.org/?probe=fc25883979) | Jun 25, 2022 |
| ASUSTek       | X555QG                      | [53e208736b](https://linux-hardware.org/?probe=53e208736b) | Jun 25, 2022 |
| ASUSTek       | X551MA                      | [e5780aff8c](https://linux-hardware.org/?probe=e5780aff8c) | Jun 24, 2022 |
| Dell          | Latitude 3420               | [027b943645](https://linux-hardware.org/?probe=027b943645) | Jun 24, 2022 |
| ASUSTek       | N61Vn                       | [72d62f755d](https://linux-hardware.org/?probe=72d62f755d) | Jun 24, 2022 |
| HP            | ZBook 15 G2                 | [cfa8a05299](https://linux-hardware.org/?probe=cfa8a05299) | Jun 23, 2022 |
| Fujitsu       | FMVS02003                   | [3536a9951f](https://linux-hardware.org/?probe=3536a9951f) | Jun 23, 2022 |
| Dell          | Latitude E5570              | [7f3b4b77f7](https://linux-hardware.org/?probe=7f3b4b77f7) | Jun 23, 2022 |
| Shuttle       | DS47D                       | [685a228ad8](https://linux-hardware.org/?probe=685a228ad8) | Jun 23, 2022 |
| Acer          | Aspire E1-531               | [415b93724e](https://linux-hardware.org/?probe=415b93724e) | Jun 22, 2022 |
| Dell          | Latitude 3300               | [5275529516](https://linux-hardware.org/?probe=5275529516) | Jun 22, 2022 |
| HP            | Spectre x2 Detachable       | [f42403915a](https://linux-hardware.org/?probe=f42403915a) | Jun 22, 2022 |
| eMachines     | E527                        | [a987a6cac2](https://linux-hardware.org/?probe=a987a6cac2) | Jun 22, 2022 |
| Dell          | Vostro 15 3515              | [f8a037663f](https://linux-hardware.org/?probe=f8a037663f) | Jun 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [8a530af324](https://linux-hardware.org/?probe=8a530af324) | Jun 21, 2022 |
| HP            | Laptop 15-bs1xx             | [11f173103f](https://linux-hardware.org/?probe=11f173103f) | Jun 21, 2022 |
| Acer          | Aspire E5-771G              | [dac3ae2eba](https://linux-hardware.org/?probe=dac3ae2eba) | Jun 21, 2022 |
| Acer          | Extensa 5635ZG              | [d1c48399ae](https://linux-hardware.org/?probe=d1c48399ae) | Jun 20, 2022 |
| Dell          | Latitude 3190               | [14521bc3eb](https://linux-hardware.org/?probe=14521bc3eb) | Jun 20, 2022 |
| HP            | Laptop 17-by4xxx            | [13fd86fd67](https://linux-hardware.org/?probe=13fd86fd67) | Jun 20, 2022 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [ee2f7822c9](https://linux-hardware.org/?probe=ee2f7822c9) | Jun 18, 2022 |
| Acer          | Swift SF314-41              | [735d7a92b5](https://linux-hardware.org/?probe=735d7a92b5) | Jun 18, 2022 |
| HP            | Laptop 14-fq0xxx            | [bc61209d78](https://linux-hardware.org/?probe=bc61209d78) | Jun 18, 2022 |
| Dell          | Latitude 3380               | [0ccd773de6](https://linux-hardware.org/?probe=0ccd773de6) | Jun 17, 2022 |
| Lenovo        | ThinkPad T460s 20FAS76R0... | [21d6816b13](https://linux-hardware.org/?probe=21d6816b13) | Jun 17, 2022 |
| Dell          | Latitude 3420               | [178e3cbcba](https://linux-hardware.org/?probe=178e3cbcba) | Jun 17, 2022 |
| Dell          | Latitude 3300               | [ed133c13de](https://linux-hardware.org/?probe=ed133c13de) | Jun 17, 2022 |
| Dell          | Latitude 3310               | [4715235090](https://linux-hardware.org/?probe=4715235090) | Jun 17, 2022 |
| Lenovo        | ThinkPad T60 2007FUG        | [2c1a306677](https://linux-hardware.org/?probe=2c1a306677) | Jun 16, 2022 |
| Acer          | Aspire A515-44              | [5da40d4fd6](https://linux-hardware.org/?probe=5da40d4fd6) | Jun 16, 2022 |
| Dell          | Latitude 3310               | [549b7595b7](https://linux-hardware.org/?probe=549b7595b7) | Jun 16, 2022 |
| ASUSTek       | ET2040I                     | [45273f0675](https://linux-hardware.org/?probe=45273f0675) | Jun 15, 2022 |
| Unknown       | Unknown                     | [00090936e8](https://linux-hardware.org/?probe=00090936e8) | Jun 15, 2022 |
| HP            | Laptop 14-fq0xxx            | [d7cccd8f1d](https://linux-hardware.org/?probe=d7cccd8f1d) | Jun 14, 2022 |
| HP            | Compaq Presario CQ41        | [95ffc69f82](https://linux-hardware.org/?probe=95ffc69f82) | Jun 14, 2022 |
| Acer          | AO722                       | [29c2adc56d](https://linux-hardware.org/?probe=29c2adc56d) | Jun 13, 2022 |
| Dell          | Latitude E5450              | [b8d806d8a4](https://linux-hardware.org/?probe=b8d806d8a4) | Jun 13, 2022 |
| ASUSTek       | N53SV                       | [fa9f250b51](https://linux-hardware.org/?probe=fa9f250b51) | Jun 13, 2022 |
| TUXEDO        | Unknown                     | [c351e553d3](https://linux-hardware.org/?probe=c351e553d3) | Jun 13, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [b65abaf14a](https://linux-hardware.org/?probe=b65abaf14a) | Jun 12, 2022 |
| Dell          | Inspiron N4050              | [32f413134f](https://linux-hardware.org/?probe=32f413134f) | Jun 12, 2022 |
| ASUSTek       | X553MA                      | [1794b92b61](https://linux-hardware.org/?probe=1794b92b61) | Jun 12, 2022 |
| Acer          | Aspire ES1-523              | [89fbabafb5](https://linux-hardware.org/?probe=89fbabafb5) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3910                | [4abeebc707](https://linux-hardware.org/?probe=4abeebc707) | Jun 12, 2022 |
| ASUSTek       | K53BR                       | [b64b9e0f4a](https://linux-hardware.org/?probe=b64b9e0f4a) | Jun 12, 2022 |
| Dell          | Vostro 3500                 | [1eda18f249](https://linux-hardware.org/?probe=1eda18f249) | Jun 12, 2022 |
| HP            | Pavilion dv6                | [0bf35c5293](https://linux-hardware.org/?probe=0bf35c5293) | Jun 11, 2022 |
| Dell          | Latitude E6410              | [184348232a](https://linux-hardware.org/?probe=184348232a) | Jun 11, 2022 |
| HP            | ProBook 450 G0              | [2d87379b89](https://linux-hardware.org/?probe=2d87379b89) | Jun 11, 2022 |
| Acer          | Aspire A515-51G             | [785b725767](https://linux-hardware.org/?probe=785b725767) | Jun 10, 2022 |
| HUAWEI        | HN-WX9X                     | [d57d295c58](https://linux-hardware.org/?probe=d57d295c58) | Jun 10, 2022 |
| Dell          | Latitude 5290               | [930e34a606](https://linux-hardware.org/?probe=930e34a606) | Jun 10, 2022 |
| HP            | Pavilion g6                 | [63dcba0c57](https://linux-hardware.org/?probe=63dcba0c57) | Jun 10, 2022 |
| Dell          | Latitude E5550              | [95baf2f400](https://linux-hardware.org/?probe=95baf2f400) | Jun 10, 2022 |
| Acer          | AO756                       | [008fa33f13](https://linux-hardware.org/?probe=008fa33f13) | Jun 09, 2022 |
| Dell          | Inspiron 1545               | [7ed42ed0a1](https://linux-hardware.org/?probe=7ed42ed0a1) | Jun 09, 2022 |
| HP            | ProBook 450 G5              | [cec4cb4af4](https://linux-hardware.org/?probe=cec4cb4af4) | Jun 09, 2022 |
| HP            | EliteBook 8570p             | [bd545aec1b](https://linux-hardware.org/?probe=bd545aec1b) | Jun 09, 2022 |
| Dell          | Latitude E5430 non-vPro     | [ff7b51ffc8](https://linux-hardware.org/?probe=ff7b51ffc8) | Jun 08, 2022 |
| HP            | ProBook 640 G1              | [34ecb184f9](https://linux-hardware.org/?probe=34ecb184f9) | Jun 08, 2022 |
| Sony          | VGN-Z71JB                   | [95a370d4e4](https://linux-hardware.org/?probe=95a370d4e4) | Jun 08, 2022 |
| Lenovo        | ThinkPad T400 2767AL9       | [8084a9ed95](https://linux-hardware.org/?probe=8084a9ed95) | Jun 08, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c6975f2914](https://linux-hardware.org/?probe=c6975f2914) | Jun 07, 2022 |
| Acer          | Aspire A315-32              | [a610c5537a](https://linux-hardware.org/?probe=a610c5537a) | Jun 07, 2022 |
| LG Electro... | 15Z970-E.BH71P1             | [cc464203ff](https://linux-hardware.org/?probe=cc464203ff) | Jun 07, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [4eb8e0924d](https://linux-hardware.org/?probe=4eb8e0924d) | Jun 07, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [039d0b1cdc](https://linux-hardware.org/?probe=039d0b1cdc) | Jun 07, 2022 |
| HP            | Laptop 14-fq0xxx            | [d88feaaf5e](https://linux-hardware.org/?probe=d88feaaf5e) | Jun 06, 2022 |
| Unknown       | Unknown                     | [c0625a957b](https://linux-hardware.org/?probe=c0625a957b) | Jun 06, 2022 |
| DNS           | MB50II1                     | [b4882bff99](https://linux-hardware.org/?probe=b4882bff99) | Jun 06, 2022 |
| HP            | ProBook 4530s               | [0ff1032a69](https://linux-hardware.org/?probe=0ff1032a69) | Jun 06, 2022 |
| Alienware     | 13 R3                       | [1431b0b659](https://linux-hardware.org/?probe=1431b0b659) | Jun 06, 2022 |
| TUXEDO        | Unknown                     | [ef40511693](https://linux-hardware.org/?probe=ef40511693) | Jun 05, 2022 |
| Dell          | Inspiron 15 3511            | [8f0924eb80](https://linux-hardware.org/?probe=8f0924eb80) | Jun 05, 2022 |
| Acer          | Aspire ES1-572              | [9c48d4f977](https://linux-hardware.org/?probe=9c48d4f977) | Jun 05, 2022 |
| AZW           | GT-R                        | [d86ab00f24](https://linux-hardware.org/?probe=d86ab00f24) | Jun 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ff882995b0](https://linux-hardware.org/?probe=ff882995b0) | Jun 05, 2022 |
| Dell          | Latitude D630               | [fb28805860](https://linux-hardware.org/?probe=fb28805860) | Jun 05, 2022 |
| HP            | Pavilion 15                 | [5e4d9a126e](https://linux-hardware.org/?probe=5e4d9a126e) | Jun 05, 2022 |
| Acer          | Aspire A315-32              | [124288f4e9](https://linux-hardware.org/?probe=124288f4e9) | Jun 05, 2022 |
| Dell          | Latitude E7450              | [29219339b2](https://linux-hardware.org/?probe=29219339b2) | Jun 05, 2022 |
| HYPA          | FLUX                        | [76b0337ef8](https://linux-hardware.org/?probe=76b0337ef8) | Jun 05, 2022 |
| Fujitsu       | FMVA0800C                   | [bacd4a55bb](https://linux-hardware.org/?probe=bacd4a55bb) | Jun 05, 2022 |
| HP            | Laptop 14-fq0xxx            | [3ebcdc19fa](https://linux-hardware.org/?probe=3ebcdc19fa) | Jun 04, 2022 |
| Acer          | Swift SF314-41G             | [aad6ae85d1](https://linux-hardware.org/?probe=aad6ae85d1) | Jun 04, 2022 |
| Sony          | VGN-FZ31Z                   | [f9b7b79d5a](https://linux-hardware.org/?probe=f9b7b79d5a) | Jun 04, 2022 |
| Sony          | VPCSB4AFX                   | [b676e37b94](https://linux-hardware.org/?probe=b676e37b94) | Jun 04, 2022 |
| Dell          | Latitude 3189               | [f1899ceede](https://linux-hardware.org/?probe=f1899ceede) | Jun 03, 2022 |
| LG Electro... | 15Z970-E.BH71P1             | [e073539ce5](https://linux-hardware.org/?probe=e073539ce5) | Jun 02, 2022 |
| Acer          | AO722                       | [73850c23ac](https://linux-hardware.org/?probe=73850c23ac) | Jun 02, 2022 |
| LG Electro... | 15Z970-E.BH71P1             | [3b5f142164](https://linux-hardware.org/?probe=3b5f142164) | Jun 02, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [a27fbb040b](https://linux-hardware.org/?probe=a27fbb040b) | Jun 02, 2022 |
| Acer          | AOD260                      | [f5c031faa5](https://linux-hardware.org/?probe=f5c031faa5) | Jun 02, 2022 |
| Dell          | Latitude E6540              | [9cbdc3f892](https://linux-hardware.org/?probe=9cbdc3f892) | Jun 02, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_4.3/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Notebooks | Percent |
|-------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003       | 1934      | 95.18%  |
| 5.16.13-desktop-1omv4003      | 73        | 3.59%   |
| 5.17.1-desktop-2omv4050       | 12        | 0.59%   |
| 5.14.14-desktop-1omv4050      | 5         | 0.25%   |
| 5.17.1-desktop-clang-2omv4050 | 2         | 0.1%    |
| 5.16.9-desktop-1omv4003       | 2         | 0.1%    |
| 6.1.10                        | 1         | 0.05%   |
| 5.16.9-desktop-1omv4050       | 1         | 0.05%   |
| 5.16.5-desktop-2omv4003       | 1         | 0.05%   |
| 5.15.14-1-lts                 | 1         | 0.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16.7  | 1934      | 95.18%  |
| 5.16.13 | 73        | 3.59%   |
| 5.17.1  | 14        | 0.69%   |
| 5.14.14 | 5         | 0.25%   |
| 5.16.9  | 3         | 0.15%   |
| 6.1.10  | 1         | 0.05%   |
| 5.16.5  | 1         | 0.05%   |
| 5.15.14 | 1         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16    | 2000      | 98.96%  |
| 5.17    | 14        | 0.69%   |
| 5.14    | 5         | 0.25%   |
| 6.1     | 1         | 0.05%   |
| 5.15    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2020      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDE5    | 2011      | 99.55%  |
| LXQt    | 6         | 0.3%    |
| Unknown | 3         | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2017      | 99.85%  |
| Wayland | 3         | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 2019      | 99.95%  |
| LightDM | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 1103      | 54.55%  |
| de_DE | 170       | 8.41%   |
| fr_FR | 117       | 5.79%   |
| pt_BR | 87        | 4.3%    |
| it_IT | 69        | 3.41%   |
| pl_PL | 68        | 3.36%   |
| ru_RU | 67        | 3.31%   |
| en_GB | 52        | 2.57%   |
| es_ES | 42        | 2.08%   |
| cs_CZ | 28        | 1.38%   |
| es_MX | 23        | 1.14%   |
| de_AT | 20        | 0.99%   |
| pt_PT | 13        | 0.64%   |
| es_AR | 13        | 0.64%   |
| hu_HU | 12        | 0.59%   |
| tr_TR | 11        | 0.54%   |
| es_CO | 10        | 0.49%   |
| es_CL | 9         | 0.45%   |
| en_CA | 9         | 0.45%   |
| fr_BE | 8         | 0.4%    |
| nl_NL | 7         | 0.35%   |
| nl_BE | 7         | 0.35%   |
| fr_CA | 7         | 0.35%   |
| en_IN | 7         | 0.35%   |
| de_CH | 7         | 0.35%   |
| es_VE | 6         | 0.3%    |
| en_AU | 5         | 0.25%   |
| fr_CH | 4         | 0.2%    |
| es_PE | 4         | 0.2%    |
| es_BO | 4         | 0.2%    |
| ro_RO | 3         | 0.15%   |
| da_DK | 3         | 0.15%   |
| ru_UA | 2         | 0.1%    |
| nb_NO | 2         | 0.1%    |
| es_UY | 2         | 0.1%    |
| es_EC | 2         | 0.1%    |
| es_CR | 2         | 0.1%    |
| en_NZ | 2         | 0.1%    |
| uk_UA | 1         | 0.05%   |
| tr_CY | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1098      | 54.36%  |
| BIOS | 922       | 45.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Overlay | 1611      | 79.24%  |
| Ext4    | 413       | 20.31%  |
| Xfs     | 4         | 0.2%    |
| Btrfs   | 3         | 0.15%   |
| Jfs     | 1         | 0.05%   |
| F2fs    | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 1375      | 68%     |
| MBR     | 646       | 31.95%  |
| Unknown | 1         | 0.05%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1028      | 50.74%  |
| No        | 998       | 49.26%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1186      | 58.71%  |
| Yes       | 834       | 41.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo                | 384       | 19.01%  |
| Hewlett-Packard       | 368       | 18.22%  |
| Dell                  | 327       | 16.19%  |
| Acer                  | 221       | 10.94%  |
| ASUSTek Computer      | 215       | 10.64%  |
| Toshiba               | 99        | 4.9%    |
| Samsung Electronics   | 47        | 2.33%   |
| Sony                  | 44        | 2.18%   |
| Apple                 | 40        | 1.98%   |
| Fujitsu               | 35        | 1.73%   |
| MSI                   | 28        | 1.39%   |
| Positivo              | 23        | 1.14%   |
| Packard Bell          | 21        | 1.04%   |
| Medion                | 11        | 0.54%   |
| TUXEDO                | 10        | 0.5%    |
| HUAWEI                | 10        | 0.5%    |
| Unknown               | 9         | 0.45%   |
| eMachines             | 8         | 0.4%    |
| Philco                | 7         | 0.35%   |
| Notebook              | 7         | 0.35%   |
| LG Electronics        | 7         | 0.35%   |
| Compaq                | 6         | 0.3%    |
| Fujitsu Siemens       | 5         | 0.25%   |
| Chuwi                 | 5         | 0.25%   |
| Alienware             | 5         | 0.25%   |
| Positivo Bahia - VAIO | 4         | 0.2%    |
| Panasonic             | 4         | 0.2%    |
| Intel                 | 4         | 0.2%    |
| Gateway               | 4         | 0.2%    |
| Digibras              | 4         | 0.2%    |
| AZW                   | 4         | 0.2%    |
| PC Specialist         | 3         | 0.15%   |
| Wortmann AG           | 2         | 0.1%    |
| UMAX                  | 2         | 0.1%    |
| Timi                  | 2         | 0.1%    |
| Star Labs             | 2         | 0.1%    |
| NEC Computers         | 2         | 0.1%    |
| HYPA                  | 2         | 0.1%    |
| Google                | 2         | 0.1%    |
| Gigabyte Technology   | 2         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Dell Latitude 3310                     | 29        | 1.44%   |
| Unknown                                | 24        | 1.19%   |
| HP Notebook                            | 22        | 1.09%   |
| ASUS UX31E                             | 14        | 0.69%   |
| Lenovo IdeaPad 1 14ADA05 82GW          | 11        | 0.54%   |
| HP Pavilion g6                         | 10        | 0.5%    |
| Positivo Mobile                        | 8         | 0.4%    |
| Lenovo IdeaPad S145-15AST 81N3         | 8         | 0.4%    |
| Dell Latitude 3300                     | 8         | 0.4%    |
| Sony VGN-FZ31Z                         | 7         | 0.35%   |
| HP Pavilion dv6                        | 7         | 0.35%   |
| HP 15                                  | 7         | 0.35%   |
| Dell XPS 15 9530                       | 7         | 0.35%   |
| Dell Latitude E7450                    | 7         | 0.35%   |
| Dell Latitude E6420                    | 7         | 0.35%   |
| HP Pavilion 15                         | 6         | 0.3%    |
| HP Laptop 15-da0xxx                    | 6         | 0.3%    |
| HP Laptop 14-fq0xxx                    | 6         | 0.3%    |
| HP Compaq 15                           | 6         | 0.3%    |
| Dell Precision M6800                   | 6         | 0.3%    |
| Dell Latitude E7240                    | 6         | 0.3%    |
| Dell Latitude E6430                    | 6         | 0.3%    |
| Dell Latitude 3189                     | 6         | 0.3%    |
| Apple MacBookPro8,1                    | 6         | 0.3%    |
| Acer Aspire A515-51G                   | 6         | 0.3%    |
| Lenovo IdeaPad S340-14API 81NB         | 5         | 0.25%   |
| Lenovo IdeaPad 3 15ADA05 81W1          | 5         | 0.25%   |
| HP Pavilion g7                         | 5         | 0.25%   |
| HP Pavilion dv7                        | 5         | 0.25%   |
| Dell XPS 13 9360                       | 5         | 0.25%   |
| Dell Latitude E6540                    | 5         | 0.25%   |
| Dell Latitude E6410                    | 5         | 0.25%   |
| Dell Latitude E6400                    | 5         | 0.25%   |
| Dell Latitude E6220                    | 5         | 0.25%   |
| Dell Latitude E5410                    | 5         | 0.25%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA | 5         | 0.25%   |
| Apple MacBookPro9,2                    | 5         | 0.25%   |
| Acer AO722                             | 5         | 0.25%   |
| Toshiba Satellite P200                 | 4         | 0.2%    |
| Toshiba Satellite C660                 | 4         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 196       | 9.7%    |
| Lenovo ThinkPad       | 156       | 7.72%   |
| Acer Aspire           | 150       | 7.43%   |
| Lenovo IdeaPad        | 131       | 6.49%   |
| HP Pavilion           | 83        | 4.11%   |
| Toshiba Satellite     | 82        | 4.06%   |
| Dell Inspiron         | 63        | 3.12%   |
| HP Laptop             | 59        | 2.92%   |
| HP ProBook            | 52        | 2.57%   |
| ASUS VivoBook         | 38        | 1.88%   |
| HP EliteBook          | 29        | 1.44%   |
| HP Compaq             | 27        | 1.34%   |
| Fujitsu LIFEBOOK      | 25        | 1.24%   |
| Unknown               | 24        | 1.19%   |
| HP Notebook           | 22        | 1.09%   |
| Dell XPS              | 18        | 0.89%   |
| Acer Nitro            | 18        | 0.89%   |
| Packard Bell EasyNote | 17        | 0.84%   |
| Dell Precision        | 15        | 0.74%   |
| Dell Vostro           | 14        | 0.69%   |
| ASUS UX31E            | 14        | 0.69%   |
| Acer Swift            | 13        | 0.64%   |
| Acer Extensa          | 12        | 0.59%   |
| HP 250                | 11        | 0.54%   |
| Acer TravelMate       | 11        | 0.54%   |
| Positivo Mobile       | 8         | 0.4%    |
| HP 255                | 8         | 0.4%    |
| Dell Studio           | 8         | 0.4%    |
| Sony VGN-FZ31Z        | 7         | 0.35%   |
| Lenovo Legion         | 7         | 0.35%   |
| HP Stream             | 7         | 0.35%   |
| HP OMEN               | 7         | 0.35%   |
| HP 15                 | 7         | 0.35%   |
| Dell System           | 7         | 0.35%   |
| Toshiba dynabook      | 6         | 0.3%    |
| Lenovo Yoga           | 6         | 0.3%    |
| HP ENVY               | 6         | 0.3%    |
| ASUS ZenBook          | 6         | 0.3%    |
| Apple MacBookPro8     | 6         | 0.3%    |
| HP ZBook              | 5         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 225       | 11.14%  |
| 2012    | 215       | 10.64%  |
| 2019    | 161       | 7.97%   |
| 2013    | 160       | 7.92%   |
| 2020    | 145       | 7.18%   |
| 2014    | 145       | 7.18%   |
| 2010    | 133       | 6.58%   |
| 2015    | 122       | 6.04%   |
| 2016    | 121       | 5.99%   |
| 2021    | 112       | 5.54%   |
| 2018    | 106       | 5.25%   |
| 2017    | 105       | 5.2%    |
| 2008    | 93        | 4.6%    |
| 2009    | 85        | 4.21%   |
| 2007    | 62        | 3.07%   |
| 2006    | 13        | 0.64%   |
| 2022    | 12        | 0.59%   |
| Unknown | 4         | 0.2%    |
| 2005    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2020      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2020      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2014      | 99.7%   |
| Yes  | 6         | 0.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 703       | 34.8%   |
| 4.01-8.0    | 695       | 34.41%  |
| 8.01-16.0   | 267       | 13.22%  |
| 16.01-24.0  | 182       | 9.01%   |
| 1.01-2.0    | 79        | 3.91%   |
| 32.01-64.0  | 38        | 1.88%   |
| 2.01-3.0    | 35        | 1.73%   |
| 24.01-32.0  | 10        | 0.5%    |
| 0.51-1.0    | 7         | 0.35%   |
| 64.01-256.0 | 4         | 0.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 1636      | 80.63%  |
| 0.51-1.0  | 233       | 11.48%  |
| 2.01-3.0  | 125       | 6.16%   |
| 0.01-0.5  | 16        | 0.79%   |
| 3.01-4.0  | 10        | 0.49%   |
| 4.01-8.0  | 6         | 0.3%    |
| 8.01-16.0 | 3         | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1479      | 73.15%  |
| 2      | 440       | 21.76%  |
| 3      | 59        | 2.92%   |
| 0      | 31        | 1.53%   |
| 4      | 12        | 0.59%   |
| 5      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1063      | 52.62%  |
| Yes       | 957       | 47.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1724      | 85.35%  |
| No        | 296       | 14.65%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2000      | 99.01%  |
| No        | 20        | 0.99%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1485      | 73.48%  |
| No        | 536       | 26.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 234       | 11.57%  |
| USA         | 203       | 10.04%  |
| Brazil      | 145       | 7.17%   |
| France      | 139       | 6.87%   |
| Poland      | 103       | 5.09%   |
| Italy       | 98        | 4.85%   |
| Russia      | 92        | 4.55%   |
| UK          | 83        | 4.1%    |
| Netherlands | 83        | 4.1%    |
| Spain       | 59        | 2.92%   |
| Canada      | 50        | 2.47%   |
| Mexico      | 44        | 2.18%   |
| Indonesia   | 35        | 1.73%   |
| Czechia     | 35        | 1.73%   |
| Portugal    | 30        | 1.48%   |
| India       | 27        | 1.34%   |
| Romania     | 26        | 1.29%   |
| Japan       | 25        | 1.24%   |
| Turkey      | 24        | 1.19%   |
| Austria     | 24        | 1.19%   |
| Australia   | 24        | 1.19%   |
| Colombia    | 23        | 1.14%   |
| Switzerland | 22        | 1.09%   |
| Belgium     | 21        | 1.04%   |
| Sweden      | 20        | 0.99%   |
| Argentina   | 20        | 0.99%   |
| Hungary     | 17        | 0.84%   |
| Ukraine     | 15        | 0.74%   |
| Slovakia    | 14        | 0.69%   |
| Greece      | 14        | 0.69%   |
| Finland     | 14        | 0.69%   |
| Chile       | 14        | 0.69%   |
| Bulgaria    | 14        | 0.69%   |
| China       | 12        | 0.59%   |
| Serbia      | 11        | 0.54%   |
| New Zealand | 11        | 0.54%   |
| Peru        | 10        | 0.49%   |
| Venezuela   | 8         | 0.4%    |
| Morocco     | 8         | 0.4%    |
| Egypt       | 8         | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Schagen              | 56        | 2.75%   |
| Paris                | 24        | 1.18%   |
| Moscow               | 22        | 1.08%   |
| Prague               | 20        | 0.98%   |
| Berlin               | 19        | 0.93%   |
| Warsaw               | 18        | 0.89%   |
| Sao Paulo            | 17        | 0.84%   |
| Milan                | 14        | 0.69%   |
| Vienna               | 12        | 0.59%   |
| Cascais              | 11        | 0.54%   |
| Mexico City          | 10        | 0.49%   |
| Hamburg              | 10        | 0.49%   |
| Sydney               | 9         | 0.44%   |
| Istanbul             | 9         | 0.44%   |
| Madrid               | 8         | 0.39%   |
| Krakow               | 8         | 0.39%   |
| Jakarta              | 8         | 0.39%   |
| Belgrade             | 8         | 0.39%   |
| Rio de Janeiro       | 7         | 0.34%   |
| Munich               | 7         | 0.34%   |
| Cluj-Napoca          | 7         | 0.34%   |
| Bengaluru            | 7         | 0.34%   |
| Surabaya             | 6         | 0.3%    |
| Salach               | 6         | 0.3%    |
| Novosibirsk          | 6         | 0.3%    |
| Montreal             | 6         | 0.3%    |
| Madison              | 6         | 0.3%    |
| Lima                 | 6         | 0.3%    |
| Gorzów Wielkopolski | 6         | 0.3%    |
| Funchal              | 6         | 0.3%    |
| Curitiba             | 6         | 0.3%    |
| Cologne              | 6         | 0.3%    |
| Bratislava           | 6         | 0.3%    |
| Barranquilla         | 6         | 0.3%    |
| Barcelona            | 6         | 0.3%    |
| Auckland             | 6         | 0.3%    |
| Athens               | 6         | 0.3%    |
| Zagreb               | 5         | 0.25%   |
| Wroclaw              | 5         | 0.25%   |
| Thessaloniki         | 5         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 327       | 340    | 13.61%  |
| Samsung Electronics | 284       | 301    | 11.82%  |
| Seagate             | 263       | 274    | 10.95%  |
| Toshiba             | 224       | 232    | 9.33%   |
| Kingston            | 138       | 142    | 5.75%   |
| Hitachi             | 114       | 116    | 4.75%   |
| Unknown             | 113       | 114    | 4.7%    |
| SanDisk             | 102       | 104    | 4.25%   |
| Crucial             | 94        | 101    | 3.91%   |
| SK hynix            | 86        | 90     | 3.58%   |
| HGST                | 85        | 86     | 3.54%   |
| A-DATA Technology   | 42        | 42     | 1.75%   |
| Intel               | 39        | 44     | 1.62%   |
| Micron Technology   | 35        | 35     | 1.46%   |
| KIOXIA              | 23        | 23     | 0.96%   |
| Fujitsu             | 23        | 24     | 0.96%   |
| GOODRAM             | 22        | 22     | 0.92%   |
| China               | 22        | 22     | 0.92%   |
| LITEON              | 21        | 21     | 0.87%   |
| Intenso             | 19        | 19     | 0.79%   |
| Unknown             | 19        | 20     | 0.79%   |
| Apple               | 17        | 17     | 0.71%   |
| PNY                 | 16        | 17     | 0.67%   |
| Patriot             | 14        | 14     | 0.58%   |
| ASMT                | 14        | 14     | 0.58%   |
| JMicron Technology  | 13        | 13     | 0.54%   |
| SSSTC               | 11        | 11     | 0.46%   |
| SPCC                | 11        | 11     | 0.46%   |
| KingSpec            | 10        | 10     | 0.42%   |
| Apacer              | 9         | 9      | 0.37%   |
| Transcend           | 8         | 8      | 0.33%   |
| Silicon Motion      | 8         | 9      | 0.33%   |
| LITEONIT            | 8         | 8      | 0.33%   |
| Lexar               | 8         | 8      | 0.33%   |
| Hewlett-Packard     | 8         | 8      | 0.33%   |
| Gigabyte Technology | 8         | 8      | 0.33%   |
| UMIS                | 7         | 7      | 0.29%   |
| Corsair             | 7         | 8      | 0.29%   |
| Phison              | 6         | 6      | 0.25%   |
| Team                | 5         | 5      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB            | 38        | 1.56%   |
| Kingston SA400S37240G 240GB SSD     | 37        | 1.51%   |
| Toshiba MQ01ABD100 1TB              | 33        | 1.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 32        | 1.31%   |
| Seagate ST500LT012-1DG142 500GB     | 29        | 1.19%   |
| Toshiba MQ04ABF100 1TB              | 26        | 1.06%   |
| Seagate ST1000LM035-1RK172 1TB      | 25        | 1.02%   |
| Unknown                             | 19        | 0.78%   |
| HGST HTS545050A7E680 500GB          | 18        | 0.74%   |
| Seagate ST9500325AS 500GB           | 17        | 0.7%    |
| HGST HTS541010A9E680 1TB            | 17        | 0.7%    |
| Unknown SD/MMC/MS PRO 16GB          | 15        | 0.61%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 15        | 0.61%   |
| HGST HTS721010A9E630 1TB            | 15        | 0.61%   |
| Crucial CT240BX500SSD1 240GB        | 15        | 0.61%   |
| SanDisk SSD U100 256GB              | 14        | 0.57%   |
| Kingston SA400S37480G 480GB SSD     | 14        | 0.57%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 13        | 0.53%   |
| Samsung SSD 860 EVO 500GB           | 13        | 0.53%   |
| Samsung SSD 860 EVO 250GB           | 13        | 0.53%   |
| Samsung SSD 850 EVO 250GB           | 13        | 0.53%   |
| Kingston SA400S37120G 120GB SSD     | 13        | 0.53%   |
| Hitachi HTS543232A7A384 320GB       | 12        | 0.49%   |
| Unknown MMC64G  64GB                | 11        | 0.45%   |
| Unknown DA4064  64GB                | 10        | 0.41%   |
| Seagate ST2000LM015-2E8174 2TB      | 10        | 0.41%   |
| Samsung SSD 850 EVO 500GB           | 10        | 0.41%   |
| Hitachi HTS547550A9E384 500GB       | 10        | 0.41%   |
| Crucial CT1000BX500SSD1 1TB         | 10        | 0.41%   |
| SK hynix BC511 NVMe 256GB           | 9         | 0.37%   |
| Seagate ST9320325AS 320GB           | 9         | 0.37%   |
| SanDisk DF4032  32GB                | 9         | 0.37%   |
| JMicron Generic 200GB               | 9         | 0.37%   |
| Hitachi HTS547575A9E384 752GB       | 9         | 0.37%   |
| HGST HTS545050A7E380 500GB          | 9         | 0.37%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 8         | 0.33%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 8         | 0.33%   |
| Samsung SSD 860 QVO 1TB             | 8         | 0.33%   |
| Crucial CT500MX500SSD1 500GB        | 8         | 0.33%   |
| WDC WD10SPZX-21Z10T0 1TB            | 7         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 260       | 270    | 26.45%  |
| WDC                 | 241       | 247    | 24.52%  |
| Toshiba             | 198       | 202    | 20.14%  |
| Hitachi             | 114       | 116    | 11.6%   |
| HGST                | 85        | 86     | 8.65%   |
| Fujitsu             | 23        | 24     | 2.34%   |
| Samsung Electronics | 19        | 19     | 1.93%   |
| Unknown             | 15        | 15     | 1.53%   |
| JMicron Technology  | 9         | 9      | 0.92%   |
| SAGE                | 3         | 3      | 0.31%   |
| SABRENT             | 3         | 3      | 0.31%   |
| ASMedia             | 3         | 3      | 0.31%   |
| Apple               | 3         | 3      | 0.31%   |
| WD MediaMax         | 1         | 1      | 0.1%    |
| USB                 | 1         | 1      | 0.1%    |
| QC-FT-D             | 1         | 1      | 0.1%    |
| Magnetic Data       | 1         | 1      | 0.1%    |
| HGST HTS            | 1         | 1      | 0.1%    |
| Hewlett-Packard     | 1         | 1      | 0.1%    |
| ASMT                | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 186       | 193    | 20.11%  |
| Kingston            | 113       | 116    | 12.22%  |
| SanDisk             | 87        | 89     | 9.41%   |
| Crucial             | 86        | 93     | 9.3%    |
| WDC                 | 41        | 41     | 4.43%   |
| A-DATA Technology   | 31        | 31     | 3.35%   |
| SK hynix            | 25        | 26     | 2.7%    |
| Micron Technology   | 25        | 25     | 2.7%    |
| GOODRAM             | 22        | 22     | 2.38%   |
| China               | 22        | 22     | 2.38%   |
| Toshiba             | 20        | 21     | 2.16%   |
| LITEON              | 19        | 19     | 2.05%   |
| Intenso             | 17        | 17     | 1.84%   |
| PNY                 | 16        | 17     | 1.73%   |
| Patriot             | 13        | 13     | 1.41%   |
| Apple               | 13        | 13     | 1.41%   |
| Intel               | 12        | 13     | 1.3%    |
| KingSpec            | 10        | 10     | 1.08%   |
| ASMT                | 10        | 10     | 1.08%   |
| SPCC                | 9         | 9      | 0.97%   |
| Apacer              | 9         | 9      | 0.97%   |
| Transcend           | 8         | 8      | 0.86%   |
| LITEONIT            | 8         | 8      | 0.86%   |
| Lexar               | 8         | 8      | 0.86%   |
| Unknown             | 7         | 7      | 0.76%   |
| OCZ                 | 5         | 5      | 0.54%   |
| Netac               | 5         | 5      | 0.54%   |
| Hewlett-Packard     | 5         | 5      | 0.54%   |
| Corsair             | 5         | 6      | 0.54%   |
| Team                | 4         | 4      | 0.43%   |
| Gigabyte Technology | 4         | 4      | 0.43%   |
| TCSUNBOW            | 3         | 3      | 0.32%   |
| Plextor             | 3         | 3      | 0.32%   |
| Leven               | 3         | 3      | 0.32%   |
| KIOXIA-EXCERIA      | 3         | 3      | 0.32%   |
| KingDian            | 3         | 3      | 0.32%   |
| Dogfish             | 3         | 3      | 0.32%   |
| BHT                 | 3         | 3      | 0.32%   |
| XrayDisk            | 2         | 2      | 0.22%   |
| Verbatim            | 2         | 2      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 955       | 1007   | 41.29%  |
| SSD     | 865       | 950    | 37.4%   |
| NVMe    | 348       | 376    | 15.05%  |
| MMC     | 121       | 125    | 5.23%   |
| Unknown | 24        | 25     | 1.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1652      | 1871   | 74.38%  |
| NVMe | 347       | 374    | 15.62%  |
| MMC  | 121       | 125    | 5.45%   |
| SAS  | 101       | 113    | 4.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1328      | 1481   | 74.56%  |
| 0.51-1.0   | 404       | 426    | 22.68%  |
| 1.01-2.0   | 42        | 43     | 2.36%   |
| 4.01-10.0  | 5         | 5      | 0.28%   |
| 3.01-4.0   | 2         | 2      | 0.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1182      | 58.23%  |
| 101-250        | 315       | 15.52%  |
| 251-500        | 195       | 9.61%   |
| 51-100         | 95        | 4.68%   |
| 501-1000       | 90        | 4.43%   |
| 21-50          | 67        | 3.3%    |
| Unknown        | 61        | 3%      |
| 1001-2000      | 21        | 1.03%   |
| More than 3000 | 2         | 0.1%    |
| 2001-3000      | 2         | 0.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1818      | 89.69%  |
| Unknown        | 61        | 3.01%   |
| 21-50          | 43        | 2.12%   |
| 51-100         | 39        | 1.92%   |
| 101-250        | 37        | 1.83%   |
| 251-500        | 19        | 0.94%   |
| 1001-2000      | 5         | 0.25%   |
| 501-1000       | 3         | 0.15%   |
| More than 3000 | 1         | 0.05%   |
| 2001-3000      | 1         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB              | 15        | 15     | 3.01%   |
| SanDisk SSD U100 256GB                  | 14        | 14     | 2.81%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 13        | 13     | 2.61%   |
| HGST HTS541010A9E680 1TB                | 13        | 13     | 2.61%   |
| Toshiba MQ01ABF050 500GB                | 12        | 12     | 2.41%   |
| Seagate ST9500325AS 500GB               | 10        | 10     | 2.01%   |
| Hitachi HTS543232A7A384 320GB           | 9         | 9      | 1.81%   |
| Seagate ST9320325AS 320GB               | 8         | 8      | 1.61%   |
| Seagate ST500LT012-1DG142 500GB         | 8         | 8      | 1.61%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 7         | 7      | 1.41%   |
| Hitachi HTS725032A7E630 320GB           | 7         | 7      | 1.41%   |
| HGST HTS721010A9E630 1TB                | 7         | 7      | 1.41%   |
| Toshiba MQ01ABD100 1TB                  | 6         | 6      | 1.2%    |
| Toshiba MQ01ABD050 500GB                | 6         | 6      | 1.2%    |
| Seagate ST1000LM035-1RK172 1TB          | 6         | 6      | 1.2%    |
| Crucial CT240M500SSD1 240GB             | 6         | 6      | 1.2%    |
| Seagate ST500LT012-9WS142 500GB         | 5         | 5      | 1%      |
| Hitachi HTS547575A9E384 752GB           | 5         | 5      | 1%      |
| HGST HTS545050A7E380 500GB              | 5         | 5      | 1%      |
| Toshiba MQ04ABF100 1TB                  | 4         | 4      | 0.8%    |
| Toshiba MK1246GSX 120GB                 | 4         | 4      | 0.8%    |
| Seagate ST9250410AS 250GB               | 4         | 4      | 0.8%    |
| Seagate ST500LM021-1KJ152 500GB         | 4         | 4      | 0.8%    |
| Seagate ST500LM000-1EJ162 500GB         | 4         | 4      | 0.8%    |
| Hitachi HTS545050A7E380 500GB           | 4         | 4      | 0.8%    |
| HGST HTS725050A7E630 500GB              | 4         | 4      | 0.8%    |
| HGST HTS541075A9E680 752GB              | 4         | 5      | 0.8%    |
| Crucial M4-CT256M4SSD3 256GB            | 4         | 4      | 0.8%    |
| WDC WD3200BPVT-24JJ5T0 320GB            | 3         | 3      | 0.6%    |
| WDC WD3200BEVT-22A23T0 320GB            | 3         | 3      | 0.6%    |
| Toshiba MK2555GSX 250GB                 | 3         | 3      | 0.6%    |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 3         | 3      | 0.6%    |
| Seagate ST9320423AS 320GB               | 3         | 3      | 0.6%    |
| Seagate ST9160314AS 160GB               | 3         | 3      | 0.6%    |
| Samsung Electronics HM160HI 160GB       | 3         | 3      | 0.6%    |
| Kingston SV300S37A120G 120GB SSD        | 3         | 3      | 0.6%    |
| Hitachi HTS547550A9E384 500GB           | 3         | 3      | 0.6%    |
| Hitachi HTS545050B9A300 500GB           | 3         | 3      | 0.6%    |
| Hitachi HTS541612J9SA00 120GB           | 3         | 4      | 0.6%    |
| WDC WD5000LPVX-22V0TT0 500GB            | 2         | 2      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 109       | 111    | 21.93%  |
| Toshiba             | 83        | 84     | 16.7%   |
| Hitachi             | 69        | 70     | 13.88%  |
| WDC                 | 61        | 63     | 12.27%  |
| HGST                | 53        | 54     | 10.66%  |
| SanDisk             | 21        | 21     | 4.23%   |
| Samsung Electronics | 17        | 17     | 3.42%   |
| Crucial             | 15        | 15     | 3.02%   |
| Kingston            | 9         | 9      | 1.81%   |
| Fujitsu             | 9         | 9      | 1.81%   |
| SK hynix            | 8         | 9      | 1.61%   |
| A-DATA Technology   | 7         | 7      | 1.41%   |
| Micron Technology   | 5         | 5      | 1.01%   |
| Intel               | 5         | 5      | 1.01%   |
| China               | 5         | 5      | 1.01%   |
| Apple               | 5         | 5      | 1.01%   |
| LITEON              | 2         | 2      | 0.4%    |
| Corsair             | 2         | 3      | 0.4%    |
| ASMedia             | 2         | 2      | 0.4%    |
| Vaseky              | 1         | 1      | 0.2%    |
| Transcend           | 1         | 1      | 0.2%    |
| PNY                 | 1         | 1      | 0.2%    |
| OCZ                 | 1         | 1      | 0.2%    |
| Magnetic Data       | 1         | 1      | 0.2%    |
| KingSpec            | 1         | 1      | 0.2%    |
| JMicron Technology  | 1         | 1      | 0.2%    |
| Hewlett-Packard     | 1         | 1      | 0.2%    |
| Drevo               | 1         | 1      | 0.2%    |
| Dogfish             | 1         | 1      | 0.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 109       | 111    | 27.81%  |
| Toshiba             | 80        | 81     | 20.41%  |
| Hitachi             | 69        | 70     | 17.6%   |
| WDC                 | 59        | 61     | 15.05%  |
| HGST                | 53        | 54     | 13.52%  |
| Samsung Electronics | 9         | 9      | 2.3%    |
| Fujitsu             | 9         | 9      | 2.3%    |
| ASMedia             | 2         | 2      | 0.51%   |
| Magnetic Data       | 1         | 1      | 0.26%   |
| Apple               | 1         | 1      | 0.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 389       | 399    | 78.74%  |
| SSD     | 99        | 101    | 20.04%  |
| NVMe    | 5         | 5      | 1.01%   |
| Unknown | 1         | 1      | 0.2%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-11ZCT0 320GB         | 2         | 2      | 12.5%   |
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 12.5%   |
| WDC WD5000BEVT-22ZAT0 500GB         | 1         | 1      | 6.25%   |
| WDC WD5000BEVT-22A0RT0 500GB        | 1         | 1      | 6.25%   |
| WDC WD3200BEKT-60KA9T0 320GB        | 1         | 1      | 6.25%   |
| WDC WD2500BEVT-60ZCT1 250GB         | 1         | 1      | 6.25%   |
| WDC WD1600BEVT-75A23T0 160GB        | 1         | 1      | 6.25%   |
| WDC WD10JPVX-60JC3T0 1TB            | 1         | 1      | 6.25%   |
| Toshiba MK3265GSXN 320GB            | 1         | 1      | 6.25%   |
| Toshiba MK3259GSXP 320GB            | 1         | 1      | 6.25%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 6.25%   |
| Intel SSDSA2BW160G3 160GB           | 1         | 1      | 6.25%   |
| Hitachi HTS545050A7E380 500GB       | 1         | 1      | 6.25%   |
| Apple HDD HTS545050A7E362 500GB     | 1         | 1      | 6.25%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 8         | 8      | 50%     |
| Toshiba | 4         | 4      | 25%     |
| Seagate | 1         | 1      | 6.25%   |
| Intel   | 1         | 1      | 6.25%   |
| Hitachi | 1         | 1      | 6.25%   |
| Apple   | 1         | 1      | 6.25%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1491      | 1737   | 67.93%  |
| Malfunc  | 490       | 506    | 22.32%  |
| Detected | 198       | 224    | 9.02%   |
| Failed   | 16        | 16     | 0.73%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1524      | 69.97%  |
| AMD                              | 288       | 13.22%  |
| Samsung Electronics              | 90        | 4.13%   |
| SK hynix                         | 56        | 2.57%   |
| SanDisk                          | 51        | 2.34%   |
| Kingston Technology Company      | 25        | 1.15%   |
| KIOXIA                           | 22        | 1.01%   |
| Nvidia                           | 20        | 0.92%   |
| Phison Electronics               | 14        | 0.64%   |
| Silicon Motion                   | 12        | 0.55%   |
| Micron Technology                | 11        | 0.51%   |
| Toshiba America Info Systems     | 10        | 0.46%   |
| Solid State Storage Technology   | 10        | 0.46%   |
| ADATA Technology                 | 9         | 0.41%   |
| Union Memory (Shenzhen)          | 7         | 0.32%   |
| Micron/Crucial Technology        | 7         | 0.32%   |
| Silicon Integrated Systems [SiS] | 4         | 0.18%   |
| ASMedia Technology               | 4         | 0.18%   |
| Realtek Semiconductor            | 3         | 0.14%   |
| Lite-On Technology               | 2         | 0.09%   |
| JMicron Technology               | 2         | 0.09%   |
| Yangtze Memory Technologies      | 1         | 0.05%   |
| Shenzhen Longsys Electronics     | 1         | 0.05%   |
| Seagate Technology               | 1         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.05%   |
| Marvell Technology Group         | 1         | 0.05%   |
| Biwin Storage Technology         | 1         | 0.05%   |
| Apple                            | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 224       | 9.45%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 214       | 9.03%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 164       | 6.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 153       | 6.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 128       | 5.4%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 112       | 4.72%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 75        | 3.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 71        | 2.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 67        | 2.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 67        | 2.83%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 59        | 2.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 56        | 2.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 55        | 2.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 43        | 1.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 42        | 1.77%   |
| Samsung NVMe SSD Controller 980                                                  | 36        | 1.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 34        | 1.43%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 32        | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 30        | 1.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 30        | 1.27%   |
| Intel Volume Management Device NVMe RAID Controller                              | 23        | 0.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 23        | 0.97%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 23        | 0.97%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 22        | 0.93%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 22        | 0.93%   |
| Intel Tiger Lake-LP SATA Controller                                              | 22        | 0.93%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 20        | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 20        | 0.84%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 17        | 0.72%   |
| SK hynix BC511                                                                   | 16        | 0.67%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 16        | 0.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 15        | 0.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 12        | 0.51%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 12        | 0.51%   |
| Intel Comet Lake SATA AHCI Controller                                            | 12        | 0.51%   |
| Micron Non-Volatile memory controller                                            | 11        | 0.46%   |
| Intel Non-Volatile memory controller                                             | 11        | 0.46%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 11        | 0.46%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 11        | 0.46%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 11        | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1610      | 70.15%  |
| NVMe | 346       | 15.08%  |
| IDE  | 184       | 8.02%   |
| RAID | 155       | 6.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1640      | 81.19%  |
| AMD    | 380       | 18.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz             | 36        | 1.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 30        | 1.49%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 30        | 1.49%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 28        | 1.39%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 26        | 1.29%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 26        | 1.29%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 24        | 1.19%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 23        | 1.14%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 21        | 1.04%   |
| AMD 3020e with Radeon Graphics                | 21        | 1.04%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 20        | 0.99%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 20        | 0.99%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 19        | 0.94%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 18        | 0.89%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 17        | 0.84%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 17        | 0.84%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 16        | 0.79%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 16        | 0.79%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 16        | 0.79%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 16        | 0.79%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 15        | 0.74%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 15        | 0.74%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 15        | 0.74%   |
| Intel Core i7-2677M CPU @ 1.80GHz             | 14        | 0.69%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 14        | 0.69%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 14        | 0.69%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 13        | 0.64%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 13        | 0.64%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 13        | 0.64%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 13        | 0.64%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 13        | 0.64%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 13        | 0.64%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 0.64%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 12        | 0.59%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 12        | 0.59%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 12        | 0.59%   |
| AMD E-450 APU with Radeon HD Graphics         | 12        | 0.59%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 0.54%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 11        | 0.54%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 11        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 539       | 26.68%  |
| Intel Core i3           | 259       | 12.82%  |
| Intel Core i7           | 255       | 12.62%  |
| Intel Celeron           | 194       | 9.6%    |
| Intel Core 2 Duo        | 138       | 6.83%   |
| Intel Pentium           | 85        | 4.21%   |
| Other                   | 69        | 3.42%   |
| AMD Ryzen 5             | 55        | 2.72%   |
| AMD Ryzen 7             | 47        | 2.33%   |
| Intel Pentium Dual-Core | 34        | 1.68%   |
| AMD A6                  | 31        | 1.53%   |
| AMD E1                  | 27        | 1.34%   |
| AMD E                   | 25        | 1.24%   |
| AMD Ryzen 3             | 22        | 1.09%   |
| AMD A4                  | 20        | 0.99%   |
| Intel Pentium Silver    | 19        | 0.94%   |
| Intel Atom              | 18        | 0.89%   |
| AMD A8                  | 18        | 0.89%   |
| AMD A10                 | 16        | 0.79%   |
| Intel Pentium Dual      | 14        | 0.69%   |
| Intel Core 2            | 12        | 0.59%   |
| AMD E2                  | 11        | 0.54%   |
| AMD Athlon              | 11        | 0.54%   |
| AMD C-60                | 10        | 0.5%    |
| Intel Genuine           | 9         | 0.45%   |
| AMD Turion 64 X2 Mobile | 8         | 0.4%    |
| Intel Celeron Dual-Core | 6         | 0.3%    |
| AMD Athlon II           | 6         | 0.3%    |
| AMD Ryzen 9             | 5         | 0.25%   |
| AMD Ryzen 7 PRO         | 4         | 0.2%    |
| AMD Athlon X2           | 4         | 0.2%    |
| Intel Core m5           | 3         | 0.15%   |
| Intel Core m3           | 3         | 0.15%   |
| Intel Core M            | 3         | 0.15%   |
| AMD Sempron             | 3         | 0.15%   |
| AMD Phenom II           | 3         | 0.15%   |
| AMD FX                  | 3         | 0.15%   |
| Intel Core i9           | 2         | 0.1%    |
| Intel Core 2 Quad       | 2         | 0.1%    |
| Intel Celeron M         | 2         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1436      | 71.09%  |
| 4      | 427       | 21.14%  |
| 6      | 59        | 2.92%   |
| 8      | 51        | 2.52%   |
| 1      | 45        | 2.23%   |
| 10     | 1         | 0.05%   |
| 3      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2020      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1253      | 62.03%  |
| 1      | 757       | 37.48%  |
| 8      | 9         | 0.45%   |
| 4      | 1         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2019      | 99.95%  |
| Unknown        | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 220       | 10.88%  |
| 0x306a9    | 196       | 9.69%   |
| 0x1067a    | 112       | 5.54%   |
| 0x20655    | 85        | 4.2%    |
| 0x306d4    | 81        | 4.01%   |
| 0x406e3    | 80        | 3.96%   |
| 0x40651    | 77        | 3.81%   |
| 0x806e9    | 70        | 3.46%   |
| Unknown    | 62        | 3.07%   |
| 0x306c3    | 60        | 2.97%   |
| 0x806ea    | 56        | 2.77%   |
| 0x806ec    | 54        | 2.67%   |
| 0x6fd      | 52        | 2.57%   |
| 0x30678    | 52        | 2.57%   |
| 0x08108109 | 45        | 2.23%   |
| 0x06006705 | 32        | 1.58%   |
| 0x706e5    | 31        | 1.53%   |
| 0x406c4    | 31        | 1.53%   |
| 0x20652    | 29        | 1.43%   |
| 0x10676    | 29        | 1.43%   |
| 0x806c1    | 28        | 1.38%   |
| 0x906ea    | 27        | 1.34%   |
| 0x706a8    | 27        | 1.34%   |
| 0x506e3    | 26        | 1.29%   |
| 0x506c9    | 22        | 1.09%   |
| 0x07030105 | 21        | 1.04%   |
| 0x0500010d | 21        | 1.04%   |
| 0x08200103 | 20        | 0.99%   |
| 0x706a1    | 19        | 0.94%   |
| 0x08608103 | 17        | 0.84%   |
| 0x0a50000c | 16        | 0.79%   |
| 0x08108102 | 16        | 0.79%   |
| 0x906e9    | 14        | 0.69%   |
| 0x906c0    | 13        | 0.64%   |
| 0x406c3    | 13        | 0.64%   |
| 0x05000101 | 13        | 0.64%   |
| 0xa0652    | 12        | 0.59%   |
| 0x806eb    | 12        | 0.59%   |
| 0x08600106 | 12        | 0.59%   |
| 0x6fb      | 11        | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 244       | 12.08%  |
| SandyBridge     | 221       | 10.94%  |
| IvyBridge       | 198       | 9.8%    |
| Penryn          | 141       | 6.98%   |
| Haswell         | 140       | 6.93%   |
| Westmere        | 117       | 5.79%   |
| Skylake         | 111       | 5.5%    |
| Silvermont      | 106       | 5.25%   |
| Core            | 90        | 4.46%   |
| Broadwell       | 83        | 4.11%   |
| Zen+            | 62        | 3.07%   |
| Bobcat          | 49        | 2.43%   |
| Goldmont plus   | 46        | 2.28%   |
| Excavator       | 44        | 2.18%   |
| Icelake         | 33        | 1.63%   |
| Unknown         | 32        | 1.58%   |
| Puma            | 31        | 1.53%   |
| TigerLake       | 30        | 1.49%   |
| Zen 2           | 29        | 1.44%   |
| Zen             | 26        | 1.29%   |
| Zen 3           | 24        | 1.19%   |
| Goldmont        | 23        | 1.14%   |
| Piledriver      | 18        | 0.89%   |
| K8 Hammer       | 17        | 0.84%   |
| Jaguar          | 17        | 0.84%   |
| Bonnell         | 16        | 0.79%   |
| CometLake       | 15        | 0.74%   |
| Tremont         | 13        | 0.64%   |
| K10             | 13        | 0.64%   |
| K8 & K10 hybrid | 11        | 0.54%   |
| K10 Llano       | 11        | 0.54%   |
| Steamroller     | 5         | 0.25%   |
| Nehalem         | 4         | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1475      | 61.64%  |
| AMD                              | 486       | 20.31%  |
| Nvidia                           | 428       | 17.89%  |
| Silicon Integrated Systems [SiS] | 4         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 206       | 8.32%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 192       | 7.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 91        | 3.68%   |
| Intel Core Processor Integrated Graphics Controller                                      | 85        | 3.43%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 83        | 3.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 76        | 3.07%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 74        | 2.99%   |
| Intel HD Graphics 620                                                                    | 71        | 2.87%   |
| Intel HD Graphics 5500                                                                   | 71        | 2.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 62        | 2.51%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 53        | 2.14%   |
| Intel UHD Graphics 620                                                                   | 49        | 1.98%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 45        | 1.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 44        | 1.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 43        | 1.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 43        | 1.74%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 36        | 1.45%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 35        | 1.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 28        | 1.13%   |
| AMD Renoir                                                                               | 27        | 1.09%   |
| Intel HD Graphics 530                                                                    | 23        | 0.93%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 22        | 0.89%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 22        | 0.89%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 22        | 0.89%   |
| AMD Lucienne                                                                             | 21        | 0.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 20        | 0.81%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 20        | 0.81%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 19        | 0.77%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 18        | 0.73%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 17        | 0.69%   |
| Intel HD Graphics 500                                                                    | 16        | 0.65%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 16        | 0.65%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 14        | 0.57%   |
| Intel HD Graphics 630                                                                    | 14        | 0.57%   |
| Intel JasperLake [UHD Graphics]                                                          | 13        | 0.53%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 12        | 0.48%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 12        | 0.48%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 12        | 0.48%   |
| Nvidia GM108M [GeForce 840M]                                                             | 11        | 0.44%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 11        | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1119      | 55.37%  |
| 1 x AMD        | 373       | 18.46%  |
| Intel + Nvidia | 294       | 14.55%  |
| 1 x Nvidia     | 117       | 5.79%   |
| Intel + AMD    | 62        | 3.07%   |
| 2 x AMD        | 35        | 1.73%   |
| AMD + Nvidia   | 16        | 0.79%   |
| 1 x SiS        | 4         | 0.2%    |
| 2 x Nvidia     | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1997      | 98.86%  |
| Unknown     | 22        | 1.09%   |
| Proprietary | 1         | 0.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1183      | 58.54%  |
| 0.01-0.5   | 356       | 17.62%  |
| 1.01-2.0   | 207       | 10.24%  |
| 0.51-1.0   | 158       | 7.82%   |
| 3.01-4.0   | 74        | 3.66%   |
| 5.01-6.0   | 22        | 1.09%   |
| 7.01-8.0   | 13        | 0.64%   |
| 2.01-3.0   | 7         | 0.35%   |
| 8.01-16.0  | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 440       | 21.17%  |
| LG Display              | 392       | 18.86%  |
| Chimei Innolux          | 305       | 14.68%  |
| BOE                     | 254       | 12.22%  |
| Samsung Electronics     | 233       | 11.21%  |
| Chi Mei Optoelectronics | 76        | 3.66%   |
| Lenovo                  | 44        | 2.12%   |
| Apple                   | 38        | 1.83%   |
| LG Philips              | 27        | 1.3%    |
| Sharp                   | 25        | 1.2%    |
| InfoVision              | 21        | 1.01%   |
| CPT                     | 19        | 0.91%   |
| Hewlett-Packard         | 17        | 0.82%   |
| Dell                    | 17        | 0.82%   |
| Goldstar                | 15        | 0.72%   |
| Eizo                    | 14        | 0.67%   |
| PANDA                   | 13        | 0.63%   |
| Toshiba                 | 10        | 0.48%   |
| Philips                 | 10        | 0.48%   |
| AOC                     | 10        | 0.48%   |
| BenQ                    | 9         | 0.43%   |
| Sony                    | 8         | 0.38%   |
| Acer                    | 8         | 0.38%   |
| Iiyama                  | 6         | 0.29%   |
| CSO                     | 6         | 0.29%   |
| KDC                     | 4         | 0.19%   |
| HannStar                | 4         | 0.19%   |
| ___                     | 3         | 0.14%   |
| ViewSonic               | 3         | 0.14%   |
| Unknown                 | 3         | 0.14%   |
| Quanta Display          | 3         | 0.14%   |
| InnoLux Display         | 3         | 0.14%   |
| ASUSTek Computer        | 3         | 0.14%   |
| Ancor Communications    | 3         | 0.14%   |
| Vizio                   | 2         | 0.1%    |
| Vestel Elektronik       | 2         | 0.1%    |
| STA                     | 2         | 0.1%    |
| Panasonic               | 2         | 0.1%    |
| NEC Computers           | 2         | 0.1%    |
| IBM                     | 2         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 24        | 1.15%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 24        | 1.15%   |
| AU Optronics LCD Monitor AUO202D 1920x1080 293x165mm 13.2-inch           | 20        | 0.96%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 17        | 0.82%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 17        | 0.82%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 16        | 0.77%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 15        | 0.72%   |
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 14        | 0.67%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 14        | 0.67%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.62%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 13        | 0.62%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 13        | 0.62%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 13        | 0.62%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                        | 12        | 0.58%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 12        | 0.58%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.58%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.53%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 11        | 0.53%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch     | 10        | 0.48%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 10        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 10        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 10        | 0.48%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 9         | 0.43%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 9         | 0.43%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 9         | 0.43%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 9         | 0.43%   |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch                  | 8         | 0.38%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 8         | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 8         | 0.38%   |
| BOE LCD Monitor BOE07B9 1920x1080 293x165mm 13.2-inch                    | 8         | 0.38%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 8         | 0.38%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 8         | 0.38%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 8         | 0.38%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                  | 7         | 0.34%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 7         | 0.34%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 7         | 0.34%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 7         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 7         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 7         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 7         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 972       | 47.88%  |
| 1920x1080 (FHD)    | 598       | 29.46%  |
| 1600x900 (HD+)     | 144       | 7.09%   |
| 1280x800 (WXGA)    | 108       | 5.32%   |
| 1440x900 (WXGA+)   | 51        | 2.51%   |
| 3840x2160 (4K)     | 44        | 2.17%   |
| 2560x1440 (QHD)    | 16        | 0.79%   |
| 1920x1200 (WUXGA)  | 16        | 0.79%   |
| 1680x1050 (WSXGA+) | 15        | 0.74%   |
| 3200x1800 (QHD+)   | 12        | 0.59%   |
| 2560x1600          | 10        | 0.49%   |
| 1280x1024 (SXGA)   | 7         | 0.34%   |
| 1360x768           | 6         | 0.3%    |
| 2880x1800          | 4         | 0.2%    |
| 1920x1280          | 4         | 0.2%    |
| 1024x600           | 4         | 0.2%    |
| 2160x1440          | 3         | 0.15%   |
| 1024x768 (XGA)     | 3         | 0.15%   |
| 2256x1504          | 2         | 0.1%    |
| 1920x540           | 2         | 0.1%    |
| 1680x945           | 2         | 0.1%    |
| 3840x2400          | 1         | 0.05%   |
| 3840x1080          | 1         | 0.05%   |
| 3456x2160          | 1         | 0.05%   |
| 3200x2000          | 1         | 0.05%   |
| 2560x1080          | 1         | 0.05%   |
| 2288x1287          | 1         | 0.05%   |
| 1400x1050          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 951       | 45.72%  |
| 13      | 338       | 16.25%  |
| 14      | 233       | 11.2%   |
| 17      | 197       | 9.47%   |
| 12      | 83        | 3.99%   |
| 11      | 60        | 2.88%   |
| 24      | 28        | 1.35%   |
| 23      | 25        | 1.2%    |
| 27      | 23        | 1.11%   |
| 31      | 21        | 1.01%   |
| 21      | 19        | 0.91%   |
| 18      | 16        | 0.77%   |
| 16      | 14        | 0.67%   |
| 19      | 9         | 0.43%   |
| 10      | 9         | 0.43%   |
| 84      | 5         | 0.24%   |
| 22      | 5         | 0.24%   |
| 20      | 5         | 0.24%   |
| 54      | 4         | 0.19%   |
| 40      | 4         | 0.19%   |
| 32      | 4         | 0.19%   |
| 65      | 3         | 0.14%   |
| 26      | 3         | 0.14%   |
| 74      | 2         | 0.1%    |
| 72      | 2         | 0.1%    |
| 48      | 2         | 0.1%    |
| 37      | 2         | 0.1%    |
| Unknown | 2         | 0.1%    |
| 142     | 1         | 0.05%   |
| 55      | 1         | 0.05%   |
| 52      | 1         | 0.05%   |
| 50      | 1         | 0.05%   |
| 49      | 1         | 0.05%   |
| 47      | 1         | 0.05%   |
| 39      | 1         | 0.05%   |
| 36      | 1         | 0.05%   |
| 34      | 1         | 0.05%   |
| 28      | 1         | 0.05%   |
| 25      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1337      | 64.34%  |
| 201-300        | 319       | 15.35%  |
| 351-400        | 234       | 11.26%  |
| 501-600        | 73        | 3.51%   |
| 401-500        | 49        | 2.36%   |
| 601-700        | 27        | 1.3%    |
| 1001-1500      | 14        | 0.67%   |
| 1501-2000      | 9         | 0.43%   |
| 801-900        | 7         | 0.34%   |
| 701-800        | 6         | 0.29%   |
| Unknown        | 2         | 0.1%    |
| More than 2000 | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 1725      | 87.92%  |
| 16/10 | 207       | 10.55%  |
| 3/2   | 13        | 0.66%   |
| 5/4   | 7         | 0.36%   |
| 4/3   | 6         | 0.31%   |
| 32/9  | 1         | 0.05%   |
| 21/9  | 1         | 0.05%   |
| 1.96  | 1         | 0.05%   |
| 1.00  | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 954       | 45.84%  |
| 81-90          | 428       | 20.57%  |
| 121-130        | 162       | 7.78%   |
| 71-80          | 144       | 6.92%   |
| 61-70          | 81        | 3.89%   |
| 201-250        | 64        | 3.08%   |
| 51-60          | 60        | 2.88%   |
| 131-140        | 34        | 1.63%   |
| 351-500        | 27        | 1.3%    |
| 301-350        | 25        | 1.2%    |
| More than 1000 | 21        | 1.01%   |
| 151-200        | 18        | 0.86%   |
| 141-150        | 16        | 0.77%   |
| 251-300        | 13        | 0.62%   |
| 501-1000       | 11        | 0.53%   |
| 41-50          | 9         | 0.43%   |
| 111-120        | 7         | 0.34%   |
| 91-100         | 5         | 0.24%   |
| Unknown        | 2         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 941       | 45.79%  |
| 121-160       | 679       | 33.04%  |
| 51-100        | 293       | 14.26%  |
| 161-240       | 102       | 4.96%   |
| More than 240 | 19        | 0.92%   |
| 1-50          | 19        | 0.92%   |
| Unknown       | 2         | 0.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1849      | 91.53%  |
| 2     | 158       | 7.82%   |
| 0     | 8         | 0.4%    |
| 3     | 5         | 0.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1133      | 34.85%  |
| Intel                             | 894       | 27.5%   |
| Qualcomm Atheros                  | 615       | 18.92%  |
| Broadcom                          | 218       | 6.71%   |
| Ralink                            | 60        | 1.85%   |
| Marvell Technology Group          | 52        | 1.6%    |
| Broadcom Limited                  | 47        | 1.45%   |
| Samsung Electronics               | 25        | 0.77%   |
| MediaTek                          | 19        | 0.58%   |
| JMicron Technology                | 19        | 0.58%   |
| TP-Link                           | 18        | 0.55%   |
| Ericsson Business Mobile Networks | 18        | 0.55%   |
| Dell                              | 18        | 0.55%   |
| Nvidia                            | 15        | 0.46%   |
| Ralink Technology                 | 14        | 0.43%   |
| Huawei Technologies               | 11        | 0.34%   |
| Sierra Wireless                   | 8         | 0.25%   |
| Hewlett-Packard                   | 8         | 0.25%   |
| ASIX Electronics                  | 7         | 0.22%   |
| Silicon Integrated Systems [SiS]  | 4         | 0.12%   |
| Motorola PCS                      | 4         | 0.12%   |
| D-Link                            | 4         | 0.12%   |
| Xiaomi                            | 3         | 0.09%   |
| Google                            | 3         | 0.09%   |
| Qualcomm Atheros Communications   | 2         | 0.06%   |
| Qcom                              | 2         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.06%   |
| NetGear                           | 2         | 0.06%   |
| ICS Advent                        | 2         | 0.06%   |
| DisplayLink                       | 2         | 0.06%   |
| D-Link System                     | 2         | 0.06%   |
| AVM                               | 2         | 0.06%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.03%   |
| vivo                              | 1         | 0.03%   |
| U-Blox                            | 1         | 0.03%   |
| T & A Mobile Phones               | 1         | 0.03%   |
| Spreadtrum Communications         | 1         | 0.03%   |
| Sigma Sport                       | 1         | 0.03%   |
| Shenzhen Goodix Technology        | 1         | 0.03%   |
| Qualcomm                          | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 638       | 16.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 271       | 6.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 103       | 2.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 97        | 2.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 96        | 2.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 89        | 2.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 88        | 2.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 87        | 2.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 72        | 1.85%   |
| Intel Wireless 7265                                               | 71        | 1.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 57        | 1.46%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 56        | 1.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 54        | 1.39%   |
| Intel Wireless 7260                                               | 52        | 1.33%   |
| Intel Wireless 8265 / 8275                                        | 50        | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 44        | 1.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 43        | 1.1%    |
| Intel Wireless 8260                                               | 42        | 1.08%   |
| Intel Wireless 3165                                               | 42        | 1.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 39        | 1%      |
| Intel Wi-Fi 6 AX200                                               | 37        | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 36        | 0.92%   |
| Intel Wireless 3160                                               | 34        | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 30        | 0.77%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 28        | 0.72%   |
| Intel WiFi Link 5100                                              | 27        | 0.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 27        | 0.69%   |
| Intel Centrino Wireless-N 2230                                    | 27        | 0.69%   |
| Intel Ethernet Connection I218-LM                                 | 26        | 0.67%   |
| Intel Centrino Ultimate-N 6300                                    | 26        | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 25        | 0.64%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 24        | 0.62%   |
| Intel 82577LM Gigabit Network Connection                          | 24        | 0.62%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 23        | 0.59%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 23        | 0.59%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 23        | 0.59%   |
| Intel Ethernet Connection (3) I218-LM                             | 23        | 0.59%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 23        | 0.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 22        | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 22        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 847       | 40.8%   |
| Qualcomm Atheros                      | 527       | 25.39%  |
| Realtek Semiconductor                 | 379       | 18.26%  |
| Broadcom                              | 164       | 7.9%    |
| Ralink                                | 60        | 2.89%   |
| Broadcom Limited                      | 24        | 1.16%   |
| MediaTek                              | 15        | 0.72%   |
| Ralink Technology                     | 14        | 0.67%   |
| Dell                                  | 11        | 0.53%   |
| Sierra Wireless                       | 8         | 0.39%   |
| TP-Link                               | 4         | 0.19%   |
| Hewlett-Packard                       | 4         | 0.19%   |
| D-Link                                | 4         | 0.19%   |
| Ericsson Business Mobile Networks     | 3         | 0.14%   |
| Qualcomm Atheros Communications       | 2         | 0.1%    |
| Qcom                                  | 2         | 0.1%    |
| D-Link System                         | 2         | 0.1%    |
| AVM                                   | 2         | 0.1%    |
| Linksys                               | 1         | 0.05%   |
| Edimax Technology                     | 1         | 0.05%   |
| ASUSTek Computer                      | 1         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 97        | 4.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 96        | 4.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 89        | 4.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 88        | 4.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 87        | 4.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 72        | 3.46%   |
| Intel Wireless 7265                                                     | 71        | 3.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 57        | 2.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 56        | 2.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 54        | 2.6%    |
| Intel Wireless 7260                                                     | 52        | 2.5%    |
| Intel Wireless 8265 / 8275                                              | 50        | 2.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 44        | 2.12%   |
| Intel Wireless 8260                                                     | 42        | 2.02%   |
| Intel Wireless 3165                                                     | 42        | 2.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 39        | 1.88%   |
| Intel Wi-Fi 6 AX200                                                     | 37        | 1.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 36        | 1.73%   |
| Intel Wireless 3160                                                     | 34        | 1.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 28        | 1.35%   |
| Intel WiFi Link 5100                                                    | 27        | 1.3%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 27        | 1.3%    |
| Intel Centrino Wireless-N 2230                                          | 27        | 1.3%    |
| Intel Centrino Ultimate-N 6300                                          | 26        | 1.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 25        | 1.2%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 24        | 1.15%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 23        | 1.11%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 23        | 1.11%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 23        | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 22        | 1.06%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 21        | 1.01%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 20        | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 20        | 0.96%   |
| Intel Centrino Advanced-N 6200                                          | 20        | 0.96%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 20        | 0.96%   |
| Intel Wi-Fi 6 AX201                                                     | 19        | 0.91%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 17        | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 17        | 0.82%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 15        | 0.72%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 15        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 976       | 55.11%  |
| Intel                            | 342       | 19.31%  |
| Qualcomm Atheros                 | 161       | 9.09%   |
| Broadcom                         | 93        | 5.25%   |
| Marvell Technology Group         | 52        | 2.94%   |
| Samsung Electronics              | 25        | 1.41%   |
| Broadcom Limited                 | 23        | 1.3%    |
| JMicron Technology               | 19        | 1.07%   |
| Nvidia                           | 15        | 0.85%   |
| TP-Link                          | 14        | 0.79%   |
| ASIX Electronics                 | 7         | 0.4%    |
| Huawei Technologies              | 6         | 0.34%   |
| Silicon Integrated Systems [SiS] | 4         | 0.23%   |
| MediaTek                         | 4         | 0.23%   |
| Xiaomi                           | 3         | 0.17%   |
| Motorola PCS                     | 3         | 0.17%   |
| Hewlett-Packard                  | 3         | 0.17%   |
| Google                           | 3         | 0.17%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.11%   |
| NetGear                          | 2         | 0.11%   |
| ICS Advent                       | 2         | 0.11%   |
| DisplayLink                      | 2         | 0.11%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.06%   |
| vivo                             | 1         | 0.06%   |
| T & A Mobile Phones              | 1         | 0.06%   |
| Spreadtrum Communications        | 1         | 0.06%   |
| Qualcomm                         | 1         | 0.06%   |
| OPPO                             | 1         | 0.06%   |
| Lenovo                           | 1         | 0.06%   |
| HTC (High Tech Computer)         | 1         | 0.06%   |
| Belkin Components                | 1         | 0.06%   |
| Attansic Technology              | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 638       | 35.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 271       | 15.2%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 103       | 5.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 43        | 2.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 30        | 1.68%   |
| Intel Ethernet Connection I218-LM                                              | 26        | 1.46%   |
| Intel 82577LM Gigabit Network Connection                                       | 24        | 1.35%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 23        | 1.29%   |
| Intel Ethernet Connection (3) I218-LM                                          | 23        | 1.29%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 22        | 1.23%   |
| Intel 82567LM Gigabit Network Connection                                       | 21        | 1.18%   |
| Intel Ethernet Connection I219-LM                                              | 19        | 1.07%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 18        | 1.01%   |
| Intel Ethernet Connection I217-LM                                              | 18        | 1.01%   |
| Intel 82579V Gigabit Network Connection                                        | 16        | 0.9%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 15        | 0.84%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 15        | 0.84%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 14        | 0.79%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 14        | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                                          | 13        | 0.73%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 12        | 0.67%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 12        | 0.67%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 12        | 0.67%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 11        | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 11        | 0.62%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 11        | 0.62%   |
| Intel 82566MM Gigabit Network Connection                                       | 11        | 0.62%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 11        | 0.62%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 10        | 0.56%   |
| Intel Ethernet Connection I219-V                                               | 10        | 0.56%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 9         | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 8         | 0.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 8         | 0.45%   |
| Nvidia MCP79 Ethernet                                                          | 8         | 0.45%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 8         | 0.45%   |
| Intel WiMAX Connection 2400m                                                   | 8         | 0.45%   |
| Intel Ethernet Connection (4) I219-V                                           | 8         | 0.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 8         | 0.45%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 8         | 0.45%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 7         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2000      | 53.23%  |
| Ethernet | 1723      | 45.86%  |
| Modem    | 31        | 0.83%   |
| Unknown  | 3         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1395      | 70.56%  |
| Ethernet | 582       | 29.44%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1601      | 79.26%  |
| 1     | 390       | 19.31%  |
| 0     | 20        | 0.99%   |
| 3     | 9         | 0.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1430      | 70.62%  |
| Yes  | 595       | 29.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 563       | 37.71%  |
| Realtek Semiconductor           | 173       | 11.59%  |
| Qualcomm Atheros Communications | 166       | 11.12%  |
| Broadcom                        | 120       | 8.04%   |
| Lite-On Technology              | 92        | 6.16%   |
| IMC Networks                    | 71        | 4.76%   |
| Foxconn / Hon Hai               | 63        | 4.22%   |
| Dell                            | 44        | 2.95%   |
| Apple                           | 39        | 2.61%   |
| Toshiba                         | 34        | 2.28%   |
| Ralink                          | 28        | 1.88%   |
| Hewlett-Packard                 | 28        | 1.88%   |
| Cambridge Silicon Radio         | 19        | 1.27%   |
| ASUSTek Computer                | 9         | 0.6%    |
| Realtek                         | 8         | 0.54%   |
| Alps Electric                   | 8         | 0.54%   |
| Ralink Technology               | 6         | 0.4%    |
| Fujitsu                         | 4         | 0.27%   |
| Foxconn International           | 3         | 0.2%    |
| Askey Computer                  | 3         | 0.2%    |
| MediaTek                        | 2         | 0.13%   |
| Edimax Technology               | 2         | 0.13%   |
| Chicony Electronics             | 2         | 0.13%   |
| USI                             | 1         | 0.07%   |
| Unknown                         | 1         | 0.07%   |
| TP-Link                         | 1         | 0.07%   |
| Taiyo Yuden                     | 1         | 0.07%   |
| Opticis                         | 1         | 0.07%   |
| D-Link System                   | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 295       | 19.76%  |
| Realtek Bluetooth Radio                                                             | 103       | 6.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 87        | 5.83%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 61        | 4.09%   |
| Intel AX201 Bluetooth                                                               | 52        | 3.48%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 51        | 3.42%   |
| Intel AX200 Bluetooth                                                               | 37        | 2.48%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 36        | 2.41%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 34        | 2.28%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 32        | 2.14%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 31        | 2.08%   |
| IMC Networks Bluetooth Radio                                                        | 30        | 2.01%   |
| Ralink RT3290 Bluetooth                                                             | 28        | 1.88%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 28        | 1.88%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 27        | 1.81%   |
| Lite-On Bluetooth Device                                                            | 26        | 1.74%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 25        | 1.67%   |
| Dell DW375 Bluetooth Module                                                         | 24        | 1.61%   |
| IMC Networks Bluetooth Device                                                       | 23        | 1.54%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 22        | 1.47%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 21        | 1.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 19        | 1.27%   |
| Apple Bluetooth Host Controller                                                     | 19        | 1.27%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 18        | 1.21%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 18        | 1.21%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 15        | 1%      |
| Realtek RTL8723B Bluetooth                                                          | 11        | 0.74%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 11        | 0.74%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 11        | 0.74%   |
| Apple Bluetooth USB Host Controller                                                 | 11        | 0.74%   |
| Toshiba RT Bluetooth Radio                                                          | 10        | 0.67%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 10        | 0.67%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 9         | 0.6%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 8         | 0.54%   |
| Broadcom HP Portable SoftSailing                                                    | 8         | 0.54%   |
| Broadcom BCM2045A0                                                                  | 8         | 0.54%   |
| Broadcom BCM2045 Bluetooth                                                          | 8         | 0.54%   |
| Toshiba Integrated Bluetooth HCI                                                    | 7         | 0.47%   |
| Toshiba Bluetooth Device                                                            | 7         | 0.47%   |
| Realtek 802.11ac WLAN Adapter                                                       | 7         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1620      | 69.86%  |
| AMD                                          | 424       | 18.28%  |
| Nvidia                                       | 229       | 9.87%   |
| Logitech                                     | 6         | 0.26%   |
| Generalplus Technology                       | 5         | 0.22%   |
| C-Media Electronics                          | 5         | 0.22%   |
| Silicon Integrated Systems [SiS]             | 4         | 0.17%   |
| Realtek Semiconductor                        | 3         | 0.13%   |
| Texas Instruments                            | 2         | 0.09%   |
| Lenovo                                       | 2         | 0.09%   |
| JMTek                                        | 2         | 0.09%   |
| Focusrite-Novation                           | 2         | 0.09%   |
| Creative Technology                          | 2         | 0.09%   |
| Conexant Systems                             | 2         | 0.09%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.04%   |
| Yamaha                                       | 1         | 0.04%   |
| XMOS                                         | 1         | 0.04%   |
| Schiit Audio                                 | 1         | 0.04%   |
| Samsung Electronics                          | 1         | 0.04%   |
| Samson Technologies                          | 1         | 0.04%   |
| Plantronics                                  | 1         | 0.04%   |
| Native Instruments                           | 1         | 0.04%   |
| M-Audio                                      | 1         | 0.04%   |
| Cambridge Audio                              | 1         | 0.04%   |
| Apple                                        | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 249       | 8.65%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 208       | 7.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 170       | 5.91%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 163       | 5.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 130       | 4.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 121       | 4.21%   |
| AMD FCH Azalia Controller                                                                         | 96        | 3.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 84        | 2.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 83        | 2.88%   |
| Intel Broadwell-U Audio Controller                                                                | 83        | 2.88%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 78        | 2.71%   |
| Intel 8 Series HD Audio Controller                                                                | 78        | 2.71%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 71        | 2.47%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 66        | 2.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 62        | 2.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 62        | 2.16%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 59        | 2.05%   |
| AMD Kabini HDMI/DP Audio                                                                          | 57        | 1.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 55        | 1.91%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 51        | 1.77%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 46        | 1.6%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 44        | 1.53%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 43        | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 42        | 1.46%   |
| AMD Wrestler HDMI Audio                                                                           | 39        | 1.36%   |
| AMD High Definition Audio Controller                                                              | 35        | 1.22%   |
| Intel Cannon Lake PCH cAVS                                                                        | 31        | 1.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 30        | 1.04%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 30        | 1.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 28        | 0.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 28        | 0.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 23        | 0.8%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 22        | 0.76%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 19        | 0.66%   |
| AMD Trinity HDMI Audio Controller                                                                 | 18        | 0.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 17        | 0.59%   |
| Intel CM238 HD Audio Controller                                                                   | 17        | 0.59%   |
| Nvidia High Definition Audio Controller                                                           | 14        | 0.49%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 13        | 0.45%   |
| Intel Jasper Lake HD Audio                                                                        | 13        | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 654       | 26.8%   |
| SK hynix            | 540       | 22.13%  |
| Micron Technology   | 248       | 10.16%  |
| Unknown             | 210       | 8.61%   |
| Kingston            | 200       | 8.2%    |
| Crucial             | 80        | 3.28%   |
| A-DATA Technology   | 66        | 2.7%    |
| Elpida              | 65        | 2.66%   |
| Ramaxel Technology  | 62        | 2.54%   |
| Smart               | 45        | 1.84%   |
| Nanya Technology    | 38        | 1.56%   |
| Corsair             | 27        | 1.11%   |
| Unknown (ABCD)      | 24        | 0.98%   |
| Unknown             | 19        | 0.78%   |
| Teikon              | 14        | 0.57%   |
| ASint Technology    | 10        | 0.41%   |
| Team                | 9         | 0.37%   |
| G.Skill             | 9         | 0.37%   |
| Patriot             | 8         | 0.33%   |
| AMD                 | 8         | 0.33%   |
| Smart Brazil        | 6         | 0.25%   |
| High Bridge         | 6         | 0.25%   |
| Qimonda             | 5         | 0.2%    |
| Goodram             | 5         | 0.2%    |
| CSX                 | 5         | 0.2%    |
| Apacer              | 5         | 0.2%    |
| Multilaser          | 4         | 0.16%   |
| Goldkey             | 4         | 0.16%   |
| Avant               | 4         | 0.16%   |
| 48spaces            | 4         | 0.16%   |
| Transcend           | 3         | 0.12%   |
| Toshiba             | 3         | 0.12%   |
| Timetec             | 3         | 0.12%   |
| Silicon Power       | 3         | 0.12%   |
| HT Micron           | 3         | 0.12%   |
| Unknown (0x0C26)    | 2         | 0.08%   |
| SHARETRONIC         | 2         | 0.08%   |
| Sesame              | 2         | 0.08%   |
| Novatech            | 2         | 0.08%   |
| Netlist             | 2         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 54        | 2.05%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 52        | 1.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 48        | 1.83%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 48        | 1.83%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 44        | 1.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 44        | 1.67%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 35        | 1.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 32        | 1.22%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 31        | 1.18%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 31        | 1.18%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 30        | 1.14%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 24        | 0.91%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 22        | 0.84%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 21        | 0.8%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 21        | 0.8%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 20        | 0.76%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 19        | 0.72%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 19        | 0.72%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 19        | 0.72%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 19        | 0.72%   |
| Unknown                                                          | 19        | 0.72%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 18        | 0.68%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 18        | 0.68%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 17        | 0.65%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.65%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 16        | 0.61%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 16        | 0.61%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 16        | 0.61%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 15        | 0.57%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 15        | 0.57%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 14        | 0.53%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 14        | 0.53%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 14        | 0.53%   |
| Micron RAM 4ATF51264HZ-2G3B1 4096MB SODIMM DDR4 2400MT/s         | 14        | 0.53%   |
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 14        | 0.53%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 13        | 0.49%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 13        | 0.49%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.49%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 13        | 0.49%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 1060      | 52.04%  |
| DDR4    | 609       | 29.9%   |
| DDR2    | 169       | 8.3%    |
| SDRAM   | 70        | 3.44%   |
| LPDDR4  | 66        | 3.24%   |
| LPDDR3  | 22        | 1.08%   |
| Unknown | 21        | 1.03%   |
| DRAM    | 10        | 0.49%   |
| DDR     | 8         | 0.39%   |
| DDR5    | 2         | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1914      | 94.99%  |
| Row Of Chips | 81        | 4.02%   |
| Chip         | 11        | 0.55%   |
| Unknown      | 5         | 0.25%   |
| DIMM         | 4         | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 993       | 44.25%  |
| 8192  | 601       | 26.78%  |
| 2048  | 471       | 20.99%  |
| 1024  | 80        | 3.57%   |
| 16384 | 76        | 3.39%   |
| 32768 | 18        | 0.8%    |
| 512   | 5         | 0.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 705       | 31.31%  |
| 2667    | 299       | 13.28%  |
| 1334    | 206       | 9.15%   |
| 3200    | 193       | 8.57%   |
| 2400    | 157       | 6.97%   |
| 1333    | 139       | 6.17%   |
| 667     | 89        | 3.95%   |
| 1067    | 67        | 2.98%   |
| Unknown | 57        | 2.53%   |
| 2133    | 53        | 2.35%   |
| 800     | 53        | 2.35%   |
| 4199    | 36        | 1.6%    |
| 3266    | 32        | 1.42%   |
| 2048    | 29        | 1.29%   |
| 1867    | 28        | 1.24%   |
| 975     | 26        | 1.15%   |
| 1066    | 17        | 0.75%   |
| 4267    | 13        | 0.58%   |
| 533     | 12        | 0.53%   |
| 1866    | 9         | 0.4%    |
| 8400    | 7         | 0.31%   |
| 4266    | 7         | 0.31%   |
| 333     | 6         | 0.27%   |
| 1639    | 3         | 0.13%   |
| 4800    | 2         | 0.09%   |
| 3733    | 2         | 0.09%   |
| 2933    | 2         | 0.09%   |
| 666     | 2         | 0.09%   |
| 2267    | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 34.78%  |
| Canon               | 7         | 30.43%  |
| Brother Industries  | 5         | 21.74%  |
| Seiko Epson         | 1         | 4.35%   |
| Samsung Electronics | 1         | 4.35%   |
| Prolific Technology | 1         | 4.35%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Brother DCP-7055W                   | 4         | 17.39%  |
| Seiko Epson L355 Series             | 1         | 4.35%   |
| Samsung CLP-325 Color Laser Printer | 1         | 4.35%   |
| Prolific PL2305 Parallel Port       | 1         | 4.35%   |
| HP OfficeJet Pro 69                 | 1         | 4.35%   |
| HP OfficeJet 4300                   | 1         | 4.35%   |
| HP LaserJet 1018                    | 1         | 4.35%   |
| HP ENVY Photo 6200 series           | 1         | 4.35%   |
| HP DeskJet D1360                    | 1         | 4.35%   |
| HP DeskJet 6122                     | 1         | 4.35%   |
| HP DeskJet 5820 series              | 1         | 4.35%   |
| HP DeskJet 2620 All-in-One Printer  | 1         | 4.35%   |
| Canon TR8500 series                 | 1         | 4.35%   |
| Canon PIXMA MP280                   | 1         | 4.35%   |
| Canon MP160                         | 1         | 4.35%   |
| Canon MF3010                        | 1         | 4.35%   |
| Canon iP7200 series                 | 1         | 4.35%   |
| Canon G3000 series                  | 1         | 4.35%   |
| Canon G2010 series                  | 1         | 4.35%   |
| Brother MFC-J245                    | 1         | 4.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 50%     |
| Canon CanoScan LiDE 600F                                 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 467       | 27.04%  |
| Realtek Semiconductor                  | 176       | 10.19%  |
| Microdia                               | 170       | 9.84%   |
| IMC Networks                           | 119       | 6.89%   |
| Acer                                   | 108       | 6.25%   |
| Sunplus Innovation Technology          | 94        | 5.44%   |
| Suyin                                  | 89        | 5.15%   |
| Cheng Uei Precision Industry (Foxlink) | 78        | 4.52%   |
| Quanta                                 | 75        | 4.34%   |
| Syntek                                 | 49        | 2.84%   |
| Silicon Motion                         | 43        | 2.49%   |
| Lite-On Technology                     | 42        | 2.43%   |
| Ricoh                                  | 33        | 1.91%   |
| Apple                                  | 30        | 1.74%   |
| Alcor Micro                            | 29        | 1.68%   |
| ALi                                    | 20        | 1.16%   |
| Lenovo                                 | 16        | 0.93%   |
| Importek                               | 16        | 0.93%   |
| Primax Electronics                     | 11        | 0.64%   |
| Z-Star Microelectronics                | 9         | 0.52%   |
| Sonix Technology                       | 8         | 0.46%   |
| Luxvisions Innotech Limited            | 8         | 0.46%   |
| DigiTech                               | 5         | 0.29%   |
| DLEQNA19IFK6G2                         | 4         | 0.23%   |
| Sunplus Technology                     | 3         | 0.17%   |
| OmniVision Technologies                | 3         | 0.17%   |
| Logitech                               | 3         | 0.17%   |
| Nebraska Furniture Mart                | 2         | 0.12%   |
| Intel                                  | 2         | 0.12%   |
| GEMBIRD                                | 2         | 0.12%   |
| Bison Electronics                      | 2         | 0.12%   |
| WaveRider Communications               | 1         | 0.06%   |
| Unknown                                | 1         | 0.06%   |
| Tobii Technology AB                    | 1         | 0.06%   |
| SunplusIT                              | 1         | 0.06%   |
| Samsung Electronics                    | 1         | 0.06%   |
| OYT Tech                               | 1         | 0.06%   |
| Novatek Microelectronics               | 1         | 0.06%   |
| LG Electronics                         | 1         | 0.06%   |
| HRY                                    | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 65        | 3.76%   |
| Microdia Integrated_Webcam_HD                           | 54        | 3.12%   |
| Chicony HD Webcam                                       | 53        | 3.06%   |
| Realtek Integrated_Webcam_HD                            | 43        | 2.48%   |
| Microdia Integrated Webcam                              | 32        | 1.85%   |
| Sunplus Integrated_Webcam_HD                            | 23        | 1.33%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 22        | 1.27%   |
| Syntek Integrated Camera                                | 21        | 1.21%   |
| IMC Networks Integrated Camera                          | 21        | 1.21%   |
| Chicony TOSHIBA Web Camera - HD                         | 21        | 1.21%   |
| Chicony VGA WebCam                                      | 20        | 1.16%   |
| Chicony USB 2.0 Camera                                  | 20        | 1.16%   |
| Chicony Lenovo EasyCamera                               | 20        | 1.16%   |
| Acer Integrated Camera                                  | 20        | 1.16%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 19        | 1.1%    |
| IMC Networks USB2.0 VGA UVC WebCam                      | 19        | 1.1%    |
| Chicony USB2.0 VGA UVC WebCam                           | 19        | 1.1%    |
| Realtek USB Camera                                      | 17        | 0.98%   |
| Quanta HD User Facing                                   | 16        | 0.92%   |
| Chicony HD User Facing                                  | 16        | 0.92%   |
| Chicony FJ Camera                                       | 16        | 0.92%   |
| Acer Lenovo EasyCamera                                  | 16        | 0.92%   |
| Sunplus HD WebCam                                       | 15        | 0.87%   |
| Realtek EasyCamera                                      | 15        | 0.87%   |
| Chicony HP TrueVision HD Camera                         | 15        | 0.87%   |
| Chicony HP Truevision HD                                | 15        | 0.87%   |
| Microdia USB 2.0 Camera                                 | 14        | 0.81%   |
| Lite-On Integrated Camera                               | 14        | 0.81%   |
| Realtek Lenovo EasyCamera                               | 13        | 0.75%   |
| Quanta HD Webcam                                        | 13        | 0.75%   |
| Chicony USB2.0 HD UVC WebCam                            | 13        | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 13        | 0.75%   |
| ALi Gateway Webcam                                      | 13        | 0.75%   |
| Quanta HP TrueVision HD Camera                          | 12        | 0.69%   |
| Lite-On HP HD Webcam                                    | 12        | 0.69%   |
| Chicony HP Webcam                                       | 12        | 0.69%   |
| Apple Built-in iSight                                   | 12        | 0.69%   |
| Acer Lenovo Integrated Webcam                           | 12        | 0.69%   |
| Syntek Lenovo EasyCamera                                | 11        | 0.64%   |
| Realtek USB2.0 HD UVC WebCam                            | 11        | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 72        | 37.89%  |
| AuthenTec                  | 30        | 15.79%  |
| Upek                       | 23        | 12.11%  |
| Elan Microelectronics      | 17        | 8.95%   |
| Shenzhen Goodix Technology | 14        | 7.37%   |
| Synaptics                  | 13        | 6.84%   |
| STMicroelectronics         | 9         | 4.74%   |
| LighTuning Technology      | 9         | 4.74%   |
| Samsung Electronics        | 1         | 0.53%   |
| HOLTEK                     | 1         | 0.53%   |
| Focal-systems.Corp         | 1         | 0.53%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 22        | 11.58%  |
| Validity Sensors VFS495 Fingerprint Reader                  | 21        | 11.05%  |
| Shenzhen Goodix  Fingerprint Device                         | 11        | 5.79%   |
| STMicroelectronics Fingerprint Reader                       | 9         | 4.74%   |
| Elan ELAN:Fingerprint                                       | 9         | 4.74%   |
| Elan ELAN:ARM-M4                                            | 8         | 4.21%   |
| Validity Sensors VFS491                                     | 7         | 3.68%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 7         | 3.68%   |
| AuthenTec AES2810                                           | 7         | 3.68%   |
| AuthenTec AES2501 Fingerprint Sensor                        | 7         | 3.68%   |
| AuthenTec AES1600                                           | 7         | 3.68%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor           | 5         | 2.63%   |
| Validity Sensors VFS5011 Fingerprint Reader                 | 5         | 2.63%   |
| Validity Sensors Swipe Fingerprint Sensor                   | 5         | 2.63%   |
| AuthenTec Fingerprint Sensor                                | 5         | 2.63%   |
| Validity Sensors VFS471 Fingerprint Reader                  | 4         | 2.11%   |
| Validity Sensors Fingerprint scanner                        | 4         | 2.11%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 4         | 2.11%   |
| LighTuning EgisTec Touch Fingerprint Sensor                 | 4         | 2.11%   |
| Unknown                                                     | 4         | 2.11%   |
| Validity Sensors VFS451 Fingerprint Reader                  | 3         | 1.58%   |
| Validity Sensors VFS301 Fingerprint Reader                  | 3         | 1.58%   |
| LighTuning ES603 Swipe Fingerprint Sensor                   | 3         | 1.58%   |
| AuthenTec AES2550 Fingerprint Sensor                        | 3         | 1.58%   |
| Validity Sensors VFS300 Fingerprint Reader                  | 2         | 1.05%   |
| Validity Sensors VFS101 Fingerprint Reader                  | 2         | 1.05%   |
| Validity Sensors Synaptics WBDI                             | 2         | 1.05%   |
| Shenzhen Goodix Fingerprint Reader                          | 2         | 1.05%   |
| LighTuning Fingerprint Reader                               | 2         | 1.05%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor           | 1         | 0.53%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 0.53%   |
| Upek TCS5B Fingerprint sensor                               | 1         | 0.53%   |
| Synaptics WBDI Device                                       | 1         | 0.53%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint  | 1         | 0.53%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint   | 1         | 0.53%   |
| Synaptics Metallica MOH Touch Fingerprint Reader            | 1         | 0.53%   |
| Synaptics Metallica MIS Touch Fingerprint Reader            | 1         | 0.53%   |
| Shenzhen Goodix FingerPrint                                 | 1         | 0.53%   |
| Samsung Fingerprint Sensor Device - 730B                    | 1         | 0.53%   |
| HOLTEK FocalTech Fingerprint Device                         | 1         | 0.53%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 82        | 56.94%  |
| O2 Micro              | 17        | 11.81%  |
| Alcor Micro           | 17        | 11.81%  |
| Upek                  | 14        | 9.72%   |
| Lenovo                | 11        | 7.64%   |
| SCM Microsystems      | 2         | 1.39%   |
| Gemalto (was Gemplus) | 1         | 0.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 38        | 26.39%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 24        | 16.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 16        | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 16        | 11.11%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 9.72%   |
| Broadcom 5880                                                                | 14        | 9.72%   |
| Lenovo Integrated Smart Card Reader                                          | 11        | 7.64%   |
| Broadcom 58200                                                               | 5         | 3.47%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.39%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.69%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.69%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1534      | 75.9%   |
| 1     | 410       | 20.29%  |
| 2     | 69        | 3.41%   |
| 3     | 7         | 0.35%   |
| 6     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 190       | 33.63%  |
| Chipcard                 | 141       | 24.96%  |
| Graphics card            | 78        | 13.81%  |
| Bluetooth                | 49        | 8.67%   |
| Net/wireless             | 33        | 5.84%   |
| Storage                  | 27        | 4.78%   |
| Multimedia controller    | 18        | 3.19%   |
| Camera                   | 13        | 2.3%    |
| Communication controller | 6         | 1.06%   |
| Network                  | 4         | 0.71%   |
| Sound                    | 3         | 0.53%   |
| Flash memory             | 3         | 0.53%   |


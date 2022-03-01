Zorin 16 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ZenBook UX425QA_UM425QA     | [1df5245912](https://linux-hardware.org/?probe=1df5245912) | Mar 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [bd438d0f08](https://linux-hardware.org/?probe=bd438d0f08) | Mar 01, 2022 |
| Dell          | Latitude 3550               | [5b0d9e3d13](https://linux-hardware.org/?probe=5b0d9e3d13) | Feb 28, 2022 |
| Dell          | Precision M4800             | [546f292b66](https://linux-hardware.org/?probe=546f292b66) | Feb 27, 2022 |
| Dell          | G5 5590                     | [f553433011](https://linux-hardware.org/?probe=f553433011) | Feb 27, 2022 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [f67c401f47](https://linux-hardware.org/?probe=f67c401f47) | Feb 27, 2022 |
| Acer          | Swift SF114-34              | [49fb58c88b](https://linux-hardware.org/?probe=49fb58c88b) | Feb 27, 2022 |
| Dell          | Latitude E5500              | [c84caad5a2](https://linux-hardware.org/?probe=c84caad5a2) | Feb 26, 2022 |
| Dell          | Latitude E5500              | [38a51b4721](https://linux-hardware.org/?probe=38a51b4721) | Feb 26, 2022 |
| HP            | 630                         | [6bf505d86b](https://linux-hardware.org/?probe=6bf505d86b) | Feb 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [359368d345](https://linux-hardware.org/?probe=359368d345) | Feb 26, 2022 |
| HP            | EliteBook 840 G6            | [fabf12f128](https://linux-hardware.org/?probe=fabf12f128) | Feb 26, 2022 |
| Dell          | Inspiron 5448               | [2458e07e0d](https://linux-hardware.org/?probe=2458e07e0d) | Feb 25, 2022 |
| Lenovo        | G40-80 80JE                 | [c55ba8cab2](https://linux-hardware.org/?probe=c55ba8cab2) | Feb 25, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [b1354ad7df](https://linux-hardware.org/?probe=b1354ad7df) | Feb 24, 2022 |
| Toshiba       | Satellite C55-B             | [ae66a9051d](https://linux-hardware.org/?probe=ae66a9051d) | Feb 24, 2022 |
| Packard Be... | DOT S                       | [e90543b727](https://linux-hardware.org/?probe=e90543b727) | Feb 24, 2022 |
| Fujitsu       | LIFEBOOK AH512              | [d7889a52d1](https://linux-hardware.org/?probe=d7889a52d1) | Feb 24, 2022 |
| HP            | Stream Laptop 11-ah0XX      | [e224468100](https://linux-hardware.org/?probe=e224468100) | Feb 23, 2022 |
| HP            | Pavilion g6                 | [1c1f4685eb](https://linux-hardware.org/?probe=1c1f4685eb) | Feb 22, 2022 |
| Dell          | XPS 15 9510                 | [6c5203e00a](https://linux-hardware.org/?probe=6c5203e00a) | Feb 22, 2022 |
| Acer          | V5-171                      | [2ef877834d](https://linux-hardware.org/?probe=2ef877834d) | Feb 22, 2022 |
| Gigabyte      | P64V7                       | [fdac76c228](https://linux-hardware.org/?probe=fdac76c228) | Feb 22, 2022 |
| Toshiba       | Satellite S55t-C            | [45b90ca745](https://linux-hardware.org/?probe=45b90ca745) | Feb 21, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [85c2284ffa](https://linux-hardware.org/?probe=85c2284ffa) | Feb 21, 2022 |
| Multilaser    | PC130                       | [4a49294d21](https://linux-hardware.org/?probe=4a49294d21) | Feb 20, 2022 |
| Multilaser    | PC130                       | [4681b7ae9e](https://linux-hardware.org/?probe=4681b7ae9e) | Feb 20, 2022 |
| Dell          | Studio 1555                 | [19d02a6eb8](https://linux-hardware.org/?probe=19d02a6eb8) | Feb 20, 2022 |
| Dell          | Precision M4800             | [9734390386](https://linux-hardware.org/?probe=9734390386) | Feb 19, 2022 |
| GEO           | GeoBook 120                 | [3eeed29e23](https://linux-hardware.org/?probe=3eeed29e23) | Feb 19, 2022 |
| GEO           | GeoBook 120                 | [5c26a23921](https://linux-hardware.org/?probe=5c26a23921) | Feb 19, 2022 |
| Google        | Akemi                       | [fc9b479395](https://linux-hardware.org/?probe=fc9b479395) | Feb 19, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4425c178f2](https://linux-hardware.org/?probe=4425c178f2) | Feb 19, 2022 |
| Lenovo        | Yoga 2 Pro 20266            | [dda75e3ba9](https://linux-hardware.org/?probe=dda75e3ba9) | Feb 19, 2022 |
| Lenovo        | ThinkPad T61 7658CTO        | [99465a8eb3](https://linux-hardware.org/?probe=99465a8eb3) | Feb 19, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [aad26f0aa8](https://linux-hardware.org/?probe=aad26f0aa8) | Feb 19, 2022 |
| ASUSTek       | X555LAB                     | [413a122ef8](https://linux-hardware.org/?probe=413a122ef8) | Feb 19, 2022 |
| Lenovo        | ThinkPad T440 20B7008ABR    | [b690de8548](https://linux-hardware.org/?probe=b690de8548) | Feb 19, 2022 |
| Dell          | Inspiron MM061              | [bc37eeb385](https://linux-hardware.org/?probe=bc37eeb385) | Feb 19, 2022 |
| Dell          | Inspiron MM061              | [e5dd39a008](https://linux-hardware.org/?probe=e5dd39a008) | Feb 18, 2022 |
| Gigabyte      | P64V7                       | [646aa28c13](https://linux-hardware.org/?probe=646aa28c13) | Feb 18, 2022 |
| Dell          | Latitude 5179               | [b28766add3](https://linux-hardware.org/?probe=b28766add3) | Feb 18, 2022 |
| HP            | 255 G2                      | [f4f4bcc310](https://linux-hardware.org/?probe=f4f4bcc310) | Feb 17, 2022 |
| HP            | 255 G2                      | [2eee7b6928](https://linux-hardware.org/?probe=2eee7b6928) | Feb 17, 2022 |
| Acer          | Predator G9-792             | [e516ba85b9](https://linux-hardware.org/?probe=e516ba85b9) | Feb 17, 2022 |
| HP            | OMEN Notebook               | [a952f9c2f2](https://linux-hardware.org/?probe=a952f9c2f2) | Feb 17, 2022 |
| ASUSTek       | ZenBook UX334FL_UX334FL     | [89c2a0f939](https://linux-hardware.org/?probe=89c2a0f939) | Feb 17, 2022 |
| Lenovo        | ThinkPad Edge E530 32599... | [d6fafc8b8b](https://linux-hardware.org/?probe=d6fafc8b8b) | Feb 17, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [59f1a1a3e0](https://linux-hardware.org/?probe=59f1a1a3e0) | Feb 16, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [a62793c371](https://linux-hardware.org/?probe=a62793c371) | Feb 16, 2022 |
| Packard Be... | EasyNote TK85               | [9abcb12076](https://linux-hardware.org/?probe=9abcb12076) | Feb 16, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [311429d9ef](https://linux-hardware.org/?probe=311429d9ef) | Feb 16, 2022 |
| Dell          | Vostro 1700                 | [efaa6a2512](https://linux-hardware.org/?probe=efaa6a2512) | Feb 16, 2022 |
| Dell          | Vostro 1700                 | [d003670f08](https://linux-hardware.org/?probe=d003670f08) | Feb 16, 2022 |
| HP            | Pavilion dv6500             | [70b0938bc3](https://linux-hardware.org/?probe=70b0938bc3) | Feb 15, 2022 |
| HP            | Pavilion dv6500             | [918d93ea7a](https://linux-hardware.org/?probe=918d93ea7a) | Feb 15, 2022 |
| Acer          | E1-510                      | [0120aaf250](https://linux-hardware.org/?probe=0120aaf250) | Feb 15, 2022 |
| Acer          | E1-510                      | [7a3678f7d1](https://linux-hardware.org/?probe=7a3678f7d1) | Feb 15, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [8306c2af49](https://linux-hardware.org/?probe=8306c2af49) | Feb 15, 2022 |
| Dell          | Vostro 1500                 | [1780b4d18b](https://linux-hardware.org/?probe=1780b4d18b) | Feb 14, 2022 |
| Dell          | XPS 15 9510                 | [79e65b1e06](https://linux-hardware.org/?probe=79e65b1e06) | Feb 14, 2022 |
| Toshiba       | QOSMIO X70-A                | [c3c921f8e2](https://linux-hardware.org/?probe=c3c921f8e2) | Feb 14, 2022 |
| Lenovo        | ThinkPad T420 4178A47       | [cda9da09dc](https://linux-hardware.org/?probe=cda9da09dc) | Feb 14, 2022 |
| e-shop.gr     | V113                        | [e9a1ae2e96](https://linux-hardware.org/?probe=e9a1ae2e96) | Feb 14, 2022 |
| Lenovo        | ThinkPad T420 4236KU9       | [0412384bc2](https://linux-hardware.org/?probe=0412384bc2) | Feb 13, 2022 |
| HP            | Unknown                     | [2f4edd8b04](https://linux-hardware.org/?probe=2f4edd8b04) | Feb 13, 2022 |
| HP            | Unknown                     | [1284e8c58f](https://linux-hardware.org/?probe=1284e8c58f) | Feb 13, 2022 |
| Toshiba       | Satellite C50-A283          | [66f810c5f5](https://linux-hardware.org/?probe=66f810c5f5) | Feb 13, 2022 |
| e-shop.gr     | V113                        | [6d015f399b](https://linux-hardware.org/?probe=6d015f399b) | Feb 12, 2022 |
| Lenovo        | Flex 2-15 20405             | [7ae6513197](https://linux-hardware.org/?probe=7ae6513197) | Feb 12, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [bd8bfe9447](https://linux-hardware.org/?probe=bd8bfe9447) | Feb 12, 2022 |
| Sony          | VGN-Z575FN                  | [4998f7ae6d](https://linux-hardware.org/?probe=4998f7ae6d) | Feb 11, 2022 |
| HP            | ProBook 4525s               | [2db6879863](https://linux-hardware.org/?probe=2db6879863) | Feb 11, 2022 |
| HP            | ProBook 450 G5              | [804f3b74e0](https://linux-hardware.org/?probe=804f3b74e0) | Feb 10, 2022 |
| HP            | ProBook 450 G5              | [9e1c3acaf3](https://linux-hardware.org/?probe=9e1c3acaf3) | Feb 10, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [3dffdcc5d3](https://linux-hardware.org/?probe=3dffdcc5d3) | Feb 09, 2022 |
| HP            | 550                         | [7e286dd830](https://linux-hardware.org/?probe=7e286dd830) | Feb 08, 2022 |
| Samsung       | 600B4B/600B5B               | [2558403513](https://linux-hardware.org/?probe=2558403513) | Feb 08, 2022 |
| Samsung       | 600B4B/600B5B               | [f37984fec2](https://linux-hardware.org/?probe=f37984fec2) | Feb 08, 2022 |
| Apple         | MacBookPro11,1              | [8233b1191c](https://linux-hardware.org/?probe=8233b1191c) | Feb 07, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [7f24cf6cc9](https://linux-hardware.org/?probe=7f24cf6cc9) | Feb 07, 2022 |
| Dell          | Inspiron N5010              | [d14b339c4f](https://linux-hardware.org/?probe=d14b339c4f) | Feb 07, 2022 |
| ASUSTek       | T101HA                      | [3ec67a3424](https://linux-hardware.org/?probe=3ec67a3424) | Feb 06, 2022 |
| Dell          | Vostro 1700                 | [56ab8ae4cc](https://linux-hardware.org/?probe=56ab8ae4cc) | Feb 06, 2022 |
| Lenovo        | G40-80 80JE                 | [dd6e3f3a64](https://linux-hardware.org/?probe=dd6e3f3a64) | Feb 06, 2022 |
| HP            | 635                         | [3f689c9c23](https://linux-hardware.org/?probe=3f689c9c23) | Feb 06, 2022 |
| ASUSTek       | X405UA                      | [bf196d4470](https://linux-hardware.org/?probe=bf196d4470) | Feb 05, 2022 |
| Unknown       | Unknown                     | [7848918b1d](https://linux-hardware.org/?probe=7848918b1d) | Feb 05, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [b1106ffeae](https://linux-hardware.org/?probe=b1106ffeae) | Feb 05, 2022 |
| ASUSTek       | ROG Strix G513QR            | [f562940afa](https://linux-hardware.org/?probe=f562940afa) | Feb 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [25fa8ea018](https://linux-hardware.org/?probe=25fa8ea018) | Feb 04, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [4b20e9f979](https://linux-hardware.org/?probe=4b20e9f979) | Feb 04, 2022 |
| HP            | ProBook 445 G7              | [3f45fd6cf2](https://linux-hardware.org/?probe=3f45fd6cf2) | Feb 03, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [71b93f7b57](https://linux-hardware.org/?probe=71b93f7b57) | Feb 03, 2022 |
| Novatech      | 15.6 nSpire Laptop          | [6fe78d2f4b](https://linux-hardware.org/?probe=6fe78d2f4b) | Feb 02, 2022 |
| HP            | ProBook 4310s               | [6d2a66aa1e](https://linux-hardware.org/?probe=6d2a66aa1e) | Feb 02, 2022 |
| Lenovo        | G710 20252                  | [5683d776e0](https://linux-hardware.org/?probe=5683d776e0) | Feb 02, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [e14121100b](https://linux-hardware.org/?probe=e14121100b) | Feb 02, 2022 |
| Lenovo        | ThinkPad T420 4236KU9       | [ae25a7a57d](https://linux-hardware.org/?probe=ae25a7a57d) | Feb 02, 2022 |
| Dell          | Inspiron 5748               | [07c8076d3e](https://linux-hardware.org/?probe=07c8076d3e) | Feb 01, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [3e6d5943dd](https://linux-hardware.org/?probe=3e6d5943dd) | Feb 01, 2022 |
| HP            | Pavilion Laptop 15z-eh00... | [76a973d25c](https://linux-hardware.org/?probe=76a973d25c) | Feb 01, 2022 |
| Apple         | MacBookPro8,1               | [70e86eb89a](https://linux-hardware.org/?probe=70e86eb89a) | Jan 31, 2022 |
| Sony          | SVF15213CBW                 | [cf01ca64c3](https://linux-hardware.org/?probe=cf01ca64c3) | Jan 31, 2022 |
| Sony          | SVF15213CBW                 | [17015b4fbe](https://linux-hardware.org/?probe=17015b4fbe) | Jan 30, 2022 |
| Dell          | Latitude E5420              | [89a74ff338](https://linux-hardware.org/?probe=89a74ff338) | Jan 29, 2022 |
| HP            | Pavilion dv7                | [504e2036d3](https://linux-hardware.org/?probe=504e2036d3) | Jan 29, 2022 |
| Dell          | Latitude E6220              | [808db5a1c8](https://linux-hardware.org/?probe=808db5a1c8) | Jan 29, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [95423d6649](https://linux-hardware.org/?probe=95423d6649) | Jan 28, 2022 |
| ASUSTek       | TAICHI21                    | [ccc3361d04](https://linux-hardware.org/?probe=ccc3361d04) | Jan 28, 2022 |
| Apple         | MacBookPro6,2               | [0143cbef50](https://linux-hardware.org/?probe=0143cbef50) | Jan 28, 2022 |
| ASUSTek       | TAICHI21                    | [6b9b9f727e](https://linux-hardware.org/?probe=6b9b9f727e) | Jan 28, 2022 |
| Jumper        | EZbook                      | [4fa449c0ce](https://linux-hardware.org/?probe=4fa449c0ce) | Jan 27, 2022 |
| Acer          | Aspire 5552                 | [ef57c29f8c](https://linux-hardware.org/?probe=ef57c29f8c) | Jan 27, 2022 |
| HP            | Pavilion dv7                | [927e580b5a](https://linux-hardware.org/?probe=927e580b5a) | Jan 26, 2022 |
| ASUSTek       | ROG Strix G513QR            | [fb81914651](https://linux-hardware.org/?probe=fb81914651) | Jan 26, 2022 |
| Lenovo        | ThinkPad X61 7673C44        | [ab461bd99e](https://linux-hardware.org/?probe=ab461bd99e) | Jan 26, 2022 |
| HP            | Pavilion dv7                | [c639bc4c98](https://linux-hardware.org/?probe=c639bc4c98) | Jan 25, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [7078a1a373](https://linux-hardware.org/?probe=7078a1a373) | Jan 25, 2022 |
| Acer          | Aspire V3-571               | [ed5c6cf88d](https://linux-hardware.org/?probe=ed5c6cf88d) | Jan 24, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | [cd8aef64e1](https://linux-hardware.org/?probe=cd8aef64e1) | Jan 24, 2022 |
| Toshiba       | Satellite C660              | [b3aec22953](https://linux-hardware.org/?probe=b3aec22953) | Jan 24, 2022 |
| ASUSTek       | ROG Strix G513QR            | [a31fd268eb](https://linux-hardware.org/?probe=a31fd268eb) | Jan 24, 2022 |
| ASUSTek       | X550CC                      | [5fa0a123f4](https://linux-hardware.org/?probe=5fa0a123f4) | Jan 24, 2022 |
| Dell          | Latitude E6420              | [1cf74dd114](https://linux-hardware.org/?probe=1cf74dd114) | Jan 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [06eb5b9d8d](https://linux-hardware.org/?probe=06eb5b9d8d) | Jan 23, 2022 |
| Toshiba       | TECRA A9                    | [7ba32a721d](https://linux-hardware.org/?probe=7ba32a721d) | Jan 23, 2022 |
| Acer          | NC-E1-572-54208G            | [02d40169ec](https://linux-hardware.org/?probe=02d40169ec) | Jan 23, 2022 |
| Clevo         | W24/250CU                   | [64c6f06849](https://linux-hardware.org/?probe=64c6f06849) | Jan 22, 2022 |
| ASUSTek       | T100TAS                     | [a37b7c51fd](https://linux-hardware.org/?probe=a37b7c51fd) | Jan 22, 2022 |
| HP            | Laptop 14q-cs0xxx           | [ec9061dcb1](https://linux-hardware.org/?probe=ec9061dcb1) | Jan 22, 2022 |
| Lenovo        | G780 20138                  | [4b5e81151e](https://linux-hardware.org/?probe=4b5e81151e) | Jan 22, 2022 |
| ASUSTek       | E200HA                      | [0d0222d2e9](https://linux-hardware.org/?probe=0d0222d2e9) | Jan 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [4c95ae549f](https://linux-hardware.org/?probe=4c95ae549f) | Jan 21, 2022 |
| Dell          | Latitude E5470              | [df22d71530](https://linux-hardware.org/?probe=df22d71530) | Jan 21, 2022 |
| HP            | EliteBook 820 G3            | [81cbc7d48a](https://linux-hardware.org/?probe=81cbc7d48a) | Jan 21, 2022 |
| HP            | EliteBook 820 G3            | [c56fbf1529](https://linux-hardware.org/?probe=c56fbf1529) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [c996d7e988](https://linux-hardware.org/?probe=c996d7e988) | Jan 20, 2022 |
| HP            | Notebook                    | [25a9e6d8a1](https://linux-hardware.org/?probe=25a9e6d8a1) | Jan 20, 2022 |
| ASUSTek       | X540YA                      | [99ff6cb58a](https://linux-hardware.org/?probe=99ff6cb58a) | Jan 20, 2022 |
| HP            | Pavilion dv7                | [e22a47facd](https://linux-hardware.org/?probe=e22a47facd) | Jan 20, 2022 |
| Acer          | Aspire V5-571PG             | [19c732cd05](https://linux-hardware.org/?probe=19c732cd05) | Jan 20, 2022 |
| Multilaser    | UB32X                       | [bd6f4152df](https://linux-hardware.org/?probe=bd6f4152df) | Jan 20, 2022 |
| ASUSTek       | GL552VW                     | [4544642750](https://linux-hardware.org/?probe=4544642750) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [81be3d94a3](https://linux-hardware.org/?probe=81be3d94a3) | Jan 18, 2022 |
| Acer          | Aspire ES1-531              | [d089029f6c](https://linux-hardware.org/?probe=d089029f6c) | Jan 18, 2022 |
| ASUSTek       | K93SV                       | [30f5830a2d](https://linux-hardware.org/?probe=30f5830a2d) | Jan 18, 2022 |
| ASUSTek       | T100TAS                     | [86df8cdba1](https://linux-hardware.org/?probe=86df8cdba1) | Jan 18, 2022 |
| Acer          | Predator G9-792             | [06a6edfaae](https://linux-hardware.org/?probe=06a6edfaae) | Jan 17, 2022 |
| HP            | 15                          | [4dde4c5c0e](https://linux-hardware.org/?probe=4dde4c5c0e) | Jan 17, 2022 |
| Google        | Ultima                      | [d942b9081b](https://linux-hardware.org/?probe=d942b9081b) | Jan 16, 2022 |
| HP            | 250 G4                      | [4de0cf1eb0](https://linux-hardware.org/?probe=4de0cf1eb0) | Jan 16, 2022 |
| Lenovo        | ThinkPad T460s 20FAS09Y0... | [339ea299c8](https://linux-hardware.org/?probe=339ea299c8) | Jan 16, 2022 |
| Acer          | Aspire A315-53              | [4bcdec655f](https://linux-hardware.org/?probe=4bcdec655f) | Jan 16, 2022 |
| Lenovo        | ThinkPad X230 2325WR3       | [decbecce89](https://linux-hardware.org/?probe=decbecce89) | Jan 16, 2022 |
| HP            | ProBook 445 G7              | [04e666772c](https://linux-hardware.org/?probe=04e666772c) | Jan 15, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [7136b51cd1](https://linux-hardware.org/?probe=7136b51cd1) | Jan 15, 2022 |
| Acer          | Aspire 5552                 | [5d3b462042](https://linux-hardware.org/?probe=5d3b462042) | Jan 14, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | [df5d687786](https://linux-hardware.org/?probe=df5d687786) | Jan 14, 2022 |
| ASUSTek       | K52JT                       | [8545fedf93](https://linux-hardware.org/?probe=8545fedf93) | Jan 14, 2022 |
| ASUSTek       | X550CC                      | [0607e7f57e](https://linux-hardware.org/?probe=0607e7f57e) | Jan 14, 2022 |
| HP            | ProBook 640 G1              | [6261e290d6](https://linux-hardware.org/?probe=6261e290d6) | Jan 13, 2022 |
| ASUSTek       | GL552VW                     | [de99d855c5](https://linux-hardware.org/?probe=de99d855c5) | Jan 13, 2022 |
| Dell          | XPS 15 9510                 | [edb752adea](https://linux-hardware.org/?probe=edb752adea) | Jan 13, 2022 |
| ASUSTek       | K54C                        | [048477ec85](https://linux-hardware.org/?probe=048477ec85) | Jan 13, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [b694d6fa5f](https://linux-hardware.org/?probe=b694d6fa5f) | Jan 13, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [0f2222fc06](https://linux-hardware.org/?probe=0f2222fc06) | Jan 13, 2022 |
| Dell          | XPS 15 9510                 | [eb7e68d366](https://linux-hardware.org/?probe=eb7e68d366) | Jan 13, 2022 |
| Razer         | Blade Stealth               | [3e3430ddeb](https://linux-hardware.org/?probe=3e3430ddeb) | Jan 13, 2022 |
| Acer          | Aspire E5-774G              | [bd6fa29ee0](https://linux-hardware.org/?probe=bd6fa29ee0) | Jan 13, 2022 |
| Toshiba       | Satellite C660              | [a4b1346944](https://linux-hardware.org/?probe=a4b1346944) | Jan 13, 2022 |
| Mediacom      | GTZS                        | [ad6de0b39b](https://linux-hardware.org/?probe=ad6de0b39b) | Jan 12, 2022 |
| HP            | Laptop 15-dy2xxx            | [086b27dc7a](https://linux-hardware.org/?probe=086b27dc7a) | Jan 12, 2022 |
| HP            | Laptop 15-dy2xxx            | [c7e776c4f2](https://linux-hardware.org/?probe=c7e776c4f2) | Jan 12, 2022 |
| HP            | Laptop 15-dy2xxx            | [c16f448f2e](https://linux-hardware.org/?probe=c16f448f2e) | Jan 12, 2022 |
| HP            | Pavilion g6                 | [e14f742bb9](https://linux-hardware.org/?probe=e14f742bb9) | Jan 12, 2022 |
| HP            | Pavilion g6                 | [62f049acf1](https://linux-hardware.org/?probe=62f049acf1) | Jan 12, 2022 |
| ASUSTek       | X542BA                      | [d5180ebfbc](https://linux-hardware.org/?probe=d5180ebfbc) | Jan 12, 2022 |
| Lenovo        | G500 20236                  | [2e7bd2b772](https://linux-hardware.org/?probe=2e7bd2b772) | Jan 12, 2022 |
| Acer          | Predator G9-792             | [870f7b6ea5](https://linux-hardware.org/?probe=870f7b6ea5) | Jan 11, 2022 |
| Acer          | Predator G9-792             | [908edac358](https://linux-hardware.org/?probe=908edac358) | Jan 11, 2022 |
| Dell          | Vostro 1500                 | [d81572b40f](https://linux-hardware.org/?probe=d81572b40f) | Jan 11, 2022 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | [4013d5dc28](https://linux-hardware.org/?probe=4013d5dc28) | Jan 11, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [3cd5068430](https://linux-hardware.org/?probe=3cd5068430) | Jan 10, 2022 |
| HP            | ProBook 6450b               | [73b06fa964](https://linux-hardware.org/?probe=73b06fa964) | Jan 10, 2022 |
| Lenovo        | V14-IIL 82C4                | [8fd207e668](https://linux-hardware.org/?probe=8fd207e668) | Jan 10, 2022 |
| Dell          | Latitude E6510              | [df2d1f8aa1](https://linux-hardware.org/?probe=df2d1f8aa1) | Jan 09, 2022 |
| HP            | Pavilion 15                 | [95f3d87b66](https://linux-hardware.org/?probe=95f3d87b66) | Jan 09, 2022 |
| HP            | Compaq 8510p                | [94c5350957](https://linux-hardware.org/?probe=94c5350957) | Jan 09, 2022 |
| ASUSTek       | K52JT                       | [c5d880e138](https://linux-hardware.org/?probe=c5d880e138) | Jan 09, 2022 |
| Unknown       | SCHNEIDER                   | [03b1f6dfed](https://linux-hardware.org/?probe=03b1f6dfed) | Jan 09, 2022 |
| ASUSTek       | GL552VW                     | [69a4959007](https://linux-hardware.org/?probe=69a4959007) | Jan 09, 2022 |
| ASUSTek       | X553MA                      | [cdf5230fdb](https://linux-hardware.org/?probe=cdf5230fdb) | Jan 09, 2022 |
| Samsung       | R59P/R60P/R61P              | [dd061ae267](https://linux-hardware.org/?probe=dd061ae267) | Jan 08, 2022 |
| HP            | Laptop 15s-du2xxx           | [e6c704567e](https://linux-hardware.org/?probe=e6c704567e) | Jan 08, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [95c067b96e](https://linux-hardware.org/?probe=95c067b96e) | Jan 07, 2022 |
| MSI           | GE75 Raider 8SF             | [23aab4b14f](https://linux-hardware.org/?probe=23aab4b14f) | Jan 06, 2022 |
| ASUSTek       | X542BP                      | [1f13c19485](https://linux-hardware.org/?probe=1f13c19485) | Jan 06, 2022 |
| Toshiba       | Satellite A200              | [613096a5ad](https://linux-hardware.org/?probe=613096a5ad) | Jan 06, 2022 |
| HP            | Laptop 15s-dr0xxx           | [be60e498db](https://linux-hardware.org/?probe=be60e498db) | Jan 06, 2022 |
| HP            | ProBook 4510s               | [cb983f7833](https://linux-hardware.org/?probe=cb983f7833) | Jan 06, 2022 |
| Dell          | Inspiron M5030              | [1715a3e584](https://linux-hardware.org/?probe=1715a3e584) | Jan 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS03Y00    | [64d6a48fd3](https://linux-hardware.org/?probe=64d6a48fd3) | Jan 06, 2022 |
| Acer          | Aspire 7741                 | [2f03831c23](https://linux-hardware.org/?probe=2f03831c23) | Jan 05, 2022 |
| Acer          | E1-510                      | [f5a0998e25](https://linux-hardware.org/?probe=f5a0998e25) | Jan 05, 2022 |
| ASUSTek       | X555QG                      | [a10e6b5ec0](https://linux-hardware.org/?probe=a10e6b5ec0) | Jan 04, 2022 |
| Acer          | Aspire 6930G                | [929cea53e3](https://linux-hardware.org/?probe=929cea53e3) | Jan 04, 2022 |
| Dell          | Inspiron 1750               | [827adb411f](https://linux-hardware.org/?probe=827adb411f) | Jan 04, 2022 |
| Lenovo        | G50-70 20351                | [04b904c594](https://linux-hardware.org/?probe=04b904c594) | Jan 04, 2022 |
| NEC Comput... | PC-LL550RG                  | [43435578b7](https://linux-hardware.org/?probe=43435578b7) | Jan 04, 2022 |
| Toshiba       | TECRA A9                    | [783735cff8](https://linux-hardware.org/?probe=783735cff8) | Jan 04, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [9f6ca62b59](https://linux-hardware.org/?probe=9f6ca62b59) | Jan 04, 2022 |
| ASUSTek       | X555QG                      | [9062bc4b1d](https://linux-hardware.org/?probe=9062bc4b1d) | Jan 03, 2022 |
| Dell          | Inspiron 13-5378            | [8d019441d1](https://linux-hardware.org/?probe=8d019441d1) | Jan 03, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [22a9d41db0](https://linux-hardware.org/?probe=22a9d41db0) | Jan 02, 2022 |
| Dell          | Latitude E7440              | [9df6480d3e](https://linux-hardware.org/?probe=9df6480d3e) | Jan 02, 2022 |
| Toshiba       | Satellite C870-1C2          | [1d759e7171](https://linux-hardware.org/?probe=1d759e7171) | Jan 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [6100abe0e1](https://linux-hardware.org/?probe=6100abe0e1) | Jan 02, 2022 |
| Dell          | Latitude E7440              | [60b74121ad](https://linux-hardware.org/?probe=60b74121ad) | Jan 02, 2022 |
| Lenovo        | ThinkPad T490 20N3S6US00    | [087fbff7d6](https://linux-hardware.org/?probe=087fbff7d6) | Jan 02, 2022 |
| Dell          | Inspiron 5770               | [0e81199f2c](https://linux-hardware.org/?probe=0e81199f2c) | Jan 02, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [367ef74be3](https://linux-hardware.org/?probe=367ef74be3) | Jan 01, 2022 |
| Lenovo        | V14-IIL 82C4                | [7dcf51eb69](https://linux-hardware.org/?probe=7dcf51eb69) | Jan 01, 2022 |
| Lenovo        | ThinkPad T490 20N3S6US00    | [f748f15a80](https://linux-hardware.org/?probe=f748f15a80) | Jan 01, 2022 |
| Jumper        | EZbook                      | [aed28b71f9](https://linux-hardware.org/?probe=aed28b71f9) | Jan 01, 2022 |
| MSI           | EX705                       | [a969bd4369](https://linux-hardware.org/?probe=a969bd4369) | Dec 31, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [0bfa74fa9f](https://linux-hardware.org/?probe=0bfa74fa9f) | Dec 31, 2021 |
| HP            | EliteBook Folio 9470m       | [90d57a20ee](https://linux-hardware.org/?probe=90d57a20ee) | Dec 31, 2021 |
| HP            | EliteBook Folio 9470m       | [4db624e8a0](https://linux-hardware.org/?probe=4db624e8a0) | Dec 31, 2021 |
| HP            | EliteBook Folio 9470m       | [b79e118712](https://linux-hardware.org/?probe=b79e118712) | Dec 31, 2021 |
| MSI           | GE-700                      | [9ccf434539](https://linux-hardware.org/?probe=9ccf434539) | Dec 31, 2021 |
| MSI           | GE-700                      | [dd9998069e](https://linux-hardware.org/?probe=dd9998069e) | Dec 31, 2021 |
| Toshiba       | Satellite L300              | [fc547136cc](https://linux-hardware.org/?probe=fc547136cc) | Dec 31, 2021 |
| ASUSTek       | GL552VW                     | [42fd7ed22b](https://linux-hardware.org/?probe=42fd7ed22b) | Dec 31, 2021 |
| HP            | Pavilion dv5                | [7017ea359e](https://linux-hardware.org/?probe=7017ea359e) | Dec 31, 2021 |
| Acer          | Aspire 1810TZ               | [0b7bd5c1fa](https://linux-hardware.org/?probe=0b7bd5c1fa) | Dec 30, 2021 |
| MSI           | GT70 2OC/2OD                | [baefd0bda3](https://linux-hardware.org/?probe=baefd0bda3) | Dec 30, 2021 |
| Dell          | XPS 13 9370                 | [f20a77fa7e](https://linux-hardware.org/?probe=f20a77fa7e) | Dec 29, 2021 |
| Packard Be... | EasyNote TK85               | [cef3f4f826](https://linux-hardware.org/?probe=cef3f4f826) | Dec 28, 2021 |
| HP            | ProBook 4730s               | [08cca0b4b5](https://linux-hardware.org/?probe=08cca0b4b5) | Dec 28, 2021 |
| Lenovo        | ThinkPad L540 20AV0031MB    | [5abe6c6347](https://linux-hardware.org/?probe=5abe6c6347) | Dec 28, 2021 |
| ASUSTek       | X302LA                      | [3c747e6bb0](https://linux-hardware.org/?probe=3c747e6bb0) | Dec 28, 2021 |
| Dell          | Latitude 7490               | [044b1ea3d3](https://linux-hardware.org/?probe=044b1ea3d3) | Dec 28, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [55b2c93259](https://linux-hardware.org/?probe=55b2c93259) | Dec 28, 2021 |
| Lenovo        | ThinkPad X201 Tablet 311... | [82c3a0ea01](https://linux-hardware.org/?probe=82c3a0ea01) | Dec 28, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [fa2df1f6f0](https://linux-hardware.org/?probe=fa2df1f6f0) | Dec 27, 2021 |
| MSI           | GT70 2OC/2OD                | [8445e5b6fe](https://linux-hardware.org/?probe=8445e5b6fe) | Dec 27, 2021 |
| Lenovo        | V14-IIL 82C4                | [b525e5f8c0](https://linux-hardware.org/?probe=b525e5f8c0) | Dec 27, 2021 |
| MSI           | GT70 2OC/2OD                | [624f5a11a8](https://linux-hardware.org/?probe=624f5a11a8) | Dec 27, 2021 |
| HP            | EliteBook 2760p             | [1cd129ee35](https://linux-hardware.org/?probe=1cd129ee35) | Dec 27, 2021 |
| HP            | EliteBook 2760p             | [f2deb9ec59](https://linux-hardware.org/?probe=f2deb9ec59) | Dec 27, 2021 |
| Dell          | Inspiron 3583               | [adcf14bf31](https://linux-hardware.org/?probe=adcf14bf31) | Dec 27, 2021 |
| Acer          | Aspire M5-481T              | [2515a869a5](https://linux-hardware.org/?probe=2515a869a5) | Dec 26, 2021 |
| Acer          | Aspire M5-481T              | [1ef9b940b2](https://linux-hardware.org/?probe=1ef9b940b2) | Dec 26, 2021 |
| Fusion5       | FWIN232_PLUS                | [ce10f25e8c](https://linux-hardware.org/?probe=ce10f25e8c) | Dec 25, 2021 |
| Dell          | Latitude 12 Rugged Table... | [13cc8e2abf](https://linux-hardware.org/?probe=13cc8e2abf) | Dec 25, 2021 |
| ASUSTek       | M50Vm                       | [bc36782a82](https://linux-hardware.org/?probe=bc36782a82) | Dec 25, 2021 |
| HP            | Pavilion dv7                | [67230f9226](https://linux-hardware.org/?probe=67230f9226) | Dec 25, 2021 |
| Dell          | Latitude 3440               | [e80fdcee0c](https://linux-hardware.org/?probe=e80fdcee0c) | Dec 25, 2021 |
| Toshiba       | TECRA S11                   | [b846fd9c93](https://linux-hardware.org/?probe=b846fd9c93) | Dec 24, 2021 |
| Dell          | Latitude 3540               | [7e7f291d68](https://linux-hardware.org/?probe=7e7f291d68) | Dec 24, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [3415419b6b](https://linux-hardware.org/?probe=3415419b6b) | Dec 23, 2021 |
| Acer          | Aspire E1-531               | [d1d6054fc3](https://linux-hardware.org/?probe=d1d6054fc3) | Dec 22, 2021 |
| HP            | Pavilion dv7                | [5823ca14b0](https://linux-hardware.org/?probe=5823ca14b0) | Dec 22, 2021 |
| ASUSTek       | K53E                        | [0a089d38c0](https://linux-hardware.org/?probe=0a089d38c0) | Dec 21, 2021 |
| Sony          | VGN-FW21E                   | [0c58cd8d69](https://linux-hardware.org/?probe=0c58cd8d69) | Dec 20, 2021 |
| Sony          | VPCF23M1E                   | [a7e83ee775](https://linux-hardware.org/?probe=a7e83ee775) | Dec 20, 2021 |
| Sony          | VPCF23M1E                   | [f10ab27170](https://linux-hardware.org/?probe=f10ab27170) | Dec 20, 2021 |
| HP            | EliteBook 2570p             | [462b93b05b](https://linux-hardware.org/?probe=462b93b05b) | Dec 20, 2021 |
| Digibras      | NH4CU03                     | [517425552d](https://linux-hardware.org/?probe=517425552d) | Dec 19, 2021 |
| Sony          | VGN-FW21E                   | [d90a22e7b0](https://linux-hardware.org/?probe=d90a22e7b0) | Dec 19, 2021 |
| Acer          | Aspire V3-571               | [5189bf7726](https://linux-hardware.org/?probe=5189bf7726) | Dec 19, 2021 |
| ASUSTek       | X751LD                      | [2013d9d5d8](https://linux-hardware.org/?probe=2013d9d5d8) | Dec 19, 2021 |
| ASUSTek       | X751LD                      | [67286f0d11](https://linux-hardware.org/?probe=67286f0d11) | Dec 19, 2021 |
| Packard Be... | EasyNote TE11BZ             | [24fef50189](https://linux-hardware.org/?probe=24fef50189) | Dec 19, 2021 |
| HP            | EliteBook 8440p             | [0dc23e59a4](https://linux-hardware.org/?probe=0dc23e59a4) | Dec 19, 2021 |
| HP            | EliteBook 8440p             | [6eab2c603a](https://linux-hardware.org/?probe=6eab2c603a) | Dec 19, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [897b589a83](https://linux-hardware.org/?probe=897b589a83) | Dec 19, 2021 |
| ASUSTek       | K53SD                       | [68a3cbb84c](https://linux-hardware.org/?probe=68a3cbb84c) | Dec 18, 2021 |
| HP            | Laptop 15-db1xxx            | [20f9c7a4ef](https://linux-hardware.org/?probe=20f9c7a4ef) | Dec 18, 2021 |
| Toshiba       | Satellite C660              | [6f860db242](https://linux-hardware.org/?probe=6f860db242) | Dec 18, 2021 |
| Dell          | Latitude E6500              | [5a29db9bdf](https://linux-hardware.org/?probe=5a29db9bdf) | Dec 18, 2021 |
| Lenovo        | ThinkPad X230 2325SYU       | [3b01a9e8eb](https://linux-hardware.org/?probe=3b01a9e8eb) | Dec 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dda5e17a21](https://linux-hardware.org/?probe=dda5e17a21) | Dec 17, 2021 |
| Toshiba       | TECRA A9                    | [53cba6b9d1](https://linux-hardware.org/?probe=53cba6b9d1) | Dec 16, 2021 |
| Login Info... | LOG-MB47II7                 | [58eb588f8b](https://linux-hardware.org/?probe=58eb588f8b) | Dec 16, 2021 |
| Login Info... | LOG-MB47II7                 | [84cabc70f7](https://linux-hardware.org/?probe=84cabc70f7) | Dec 16, 2021 |
| Compaq        | Presario 21                 | [86e7a85db3](https://linux-hardware.org/?probe=86e7a85db3) | Dec 16, 2021 |
| Toshiba       | QOSMIO X770                 | [c8c9ab4cf8](https://linux-hardware.org/?probe=c8c9ab4cf8) | Dec 16, 2021 |
| HP            | ZBook 17 G5                 | [761a2419e5](https://linux-hardware.org/?probe=761a2419e5) | Dec 16, 2021 |
| RCA           | WT9503W004                  | [c858eb3cbc](https://linux-hardware.org/?probe=c858eb3cbc) | Dec 15, 2021 |
| Dell          | Latitude E6400              | [dc0d35221e](https://linux-hardware.org/?probe=dc0d35221e) | Dec 15, 2021 |
| HP            | EliteBook 8730w             | [e35ce8395b](https://linux-hardware.org/?probe=e35ce8395b) | Dec 15, 2021 |
| HP            | ProBook 450 G3              | [d197761676](https://linux-hardware.org/?probe=d197761676) | Dec 15, 2021 |
| Google        | Squawks                     | [e75aa07dad](https://linux-hardware.org/?probe=e75aa07dad) | Dec 15, 2021 |
| Acer          | Aspire V3-571               | [071a8f0709](https://linux-hardware.org/?probe=071a8f0709) | Dec 15, 2021 |
| Dell          | Inspiron 3501               | [6cf66f6290](https://linux-hardware.org/?probe=6cf66f6290) | Dec 15, 2021 |
| Lenovo        | G580 20150                  | [6ff1581ca6](https://linux-hardware.org/?probe=6ff1581ca6) | Dec 14, 2021 |
| Acer          | AOD255                      | [08a007120e](https://linux-hardware.org/?probe=08a007120e) | Dec 14, 2021 |
| HP            | EliteBook Folio 9480m       | [11eea57427](https://linux-hardware.org/?probe=11eea57427) | Dec 14, 2021 |
| Toshiba       | Satellite L655              | [0db50aad32](https://linux-hardware.org/?probe=0db50aad32) | Dec 14, 2021 |
| Digibras      | NH4CU03                     | [97b0f21219](https://linux-hardware.org/?probe=97b0f21219) | Dec 14, 2021 |
| MSI           | PS42 Modern 8RC             | [2686d73cb8](https://linux-hardware.org/?probe=2686d73cb8) | Dec 13, 2021 |
| Lenovo        | ThinkPad X270 20HN0043AD    | [24160af893](https://linux-hardware.org/?probe=24160af893) | Dec 13, 2021 |
| Google        | Squawks                     | [31cb595893](https://linux-hardware.org/?probe=31cb595893) | Dec 13, 2021 |
| Digibras      | NH4CU03                     | [5ffb383677](https://linux-hardware.org/?probe=5ffb383677) | Dec 13, 2021 |
| Acer          | Aspire V3-571               | [54680bac44](https://linux-hardware.org/?probe=54680bac44) | Dec 12, 2021 |
| Dell          | Precision M4600             | [32034c26c7](https://linux-hardware.org/?probe=32034c26c7) | Dec 12, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d364ff0c44](https://linux-hardware.org/?probe=d364ff0c44) | Dec 12, 2021 |
| HP            | ProBook 450 G3              | [54846cdc88](https://linux-hardware.org/?probe=54846cdc88) | Dec 12, 2021 |
| Dell          | Latitude E5410              | [8b6bc5cf8e](https://linux-hardware.org/?probe=8b6bc5cf8e) | Dec 12, 2021 |
| Apple         | MacBook4,1                  | [7bf355c3c1](https://linux-hardware.org/?probe=7bf355c3c1) | Dec 12, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [807bd77769](https://linux-hardware.org/?probe=807bd77769) | Dec 12, 2021 |
| Positivo      | CHT14B                      | [6ebdfd7b1f](https://linux-hardware.org/?probe=6ebdfd7b1f) | Dec 12, 2021 |
| Acer          | Aspire 4830T                | [554d2d7ce0](https://linux-hardware.org/?probe=554d2d7ce0) | Dec 12, 2021 |
| Acer          | Aspire 4830T                | [cbf04f6efb](https://linux-hardware.org/?probe=cbf04f6efb) | Dec 12, 2021 |
| Dell          | Precision M4600             | [f3f7be37a2](https://linux-hardware.org/?probe=f3f7be37a2) | Dec 12, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [0fb07d458a](https://linux-hardware.org/?probe=0fb07d458a) | Dec 12, 2021 |
| Acer          | Aspire A517-52              | [a51b1f9eb7](https://linux-hardware.org/?probe=a51b1f9eb7) | Dec 11, 2021 |
| Acer          | Aspire A517-52              | [bbf5c7ea28](https://linux-hardware.org/?probe=bbf5c7ea28) | Dec 11, 2021 |
| Dell          | Latitude E5400              | [2444de97e0](https://linux-hardware.org/?probe=2444de97e0) | Dec 11, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [a5528e8f98](https://linux-hardware.org/?probe=a5528e8f98) | Dec 11, 2021 |
| Chuwi         | GemiBook Pro                | [493d55cb16](https://linux-hardware.org/?probe=493d55cb16) | Dec 11, 2021 |
| TCL Commun... | 8085                        | [3d795ceee0](https://linux-hardware.org/?probe=3d795ceee0) | Dec 11, 2021 |
| Dell          | Latitude E5400              | [212020992c](https://linux-hardware.org/?probe=212020992c) | Dec 11, 2021 |
| HP            | Pavilion dv3                | [484e48a117](https://linux-hardware.org/?probe=484e48a117) | Dec 11, 2021 |
| HP            | 15 Notebook PC              | [3be4065d87](https://linux-hardware.org/?probe=3be4065d87) | Dec 10, 2021 |
| HP            | 15 Notebook PC              | [c06d1d8915](https://linux-hardware.org/?probe=c06d1d8915) | Dec 10, 2021 |
| Dell          | Latitude E7440              | [ff067012c5](https://linux-hardware.org/?probe=ff067012c5) | Dec 09, 2021 |
| Samsung       | N150P/N210P/N220P           | [eed2dcde15](https://linux-hardware.org/?probe=eed2dcde15) | Dec 09, 2021 |
| Apple         | MacBook4,1                  | [cfa6005bc4](https://linux-hardware.org/?probe=cfa6005bc4) | Dec 09, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [dc07419c59](https://linux-hardware.org/?probe=dc07419c59) | Dec 08, 2021 |
| Dell          | Latitude E5400              | [a4fa2f67d3](https://linux-hardware.org/?probe=a4fa2f67d3) | Dec 08, 2021 |
| Lenovo        | ThinkPad T400 741722U       | [2739940ec1](https://linux-hardware.org/?probe=2739940ec1) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [c31f062314](https://linux-hardware.org/?probe=c31f062314) | Dec 07, 2021 |
| HP            | HDX 16                      | [cf114f9094](https://linux-hardware.org/?probe=cf114f9094) | Dec 07, 2021 |
| Unknown       | Unknown                     | [9e9e0598b6](https://linux-hardware.org/?probe=9e9e0598b6) | Dec 07, 2021 |
| HP            | Stream Laptop 14-cb1XX      | [4853c251a8](https://linux-hardware.org/?probe=4853c251a8) | Dec 07, 2021 |
| Apple         | MacBookPro8,1               | [85d594af54](https://linux-hardware.org/?probe=85d594af54) | Dec 07, 2021 |
| Razer         | Blade 15 Base Model (Ear... | [9c64eb115e](https://linux-hardware.org/?probe=9c64eb115e) | Dec 07, 2021 |
| Lenovo        | ThinkPad T400 741722U       | [2933ad8c69](https://linux-hardware.org/?probe=2933ad8c69) | Dec 07, 2021 |
| Dell          | Inspiron 5748               | [77f278682e](https://linux-hardware.org/?probe=77f278682e) | Dec 06, 2021 |
| Apple         | MacBookPro11,1              | [f454c30e46](https://linux-hardware.org/?probe=f454c30e46) | Dec 05, 2021 |
| Acer          | Aspire V3-571G              | [3acb23e27c](https://linux-hardware.org/?probe=3acb23e27c) | Dec 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [fc540c3951](https://linux-hardware.org/?probe=fc540c3951) | Dec 05, 2021 |
| Dell          | Inspiron 5770               | [c8a717a1c9](https://linux-hardware.org/?probe=c8a717a1c9) | Dec 05, 2021 |
| ASUSTek       | X553MA                      | [958551b7eb](https://linux-hardware.org/?probe=958551b7eb) | Dec 05, 2021 |
| Sony          | SVF1532Z1EB                 | [d65626b69d](https://linux-hardware.org/?probe=d65626b69d) | Dec 04, 2021 |
| ASUSTek       | X553MA                      | [78414b8bc4](https://linux-hardware.org/?probe=78414b8bc4) | Dec 04, 2021 |
| Lenovo        | G700                        | [2b7a430fcd](https://linux-hardware.org/?probe=2b7a430fcd) | Dec 04, 2021 |
| Toshiba       | Satellite C660              | [4d64247a8a](https://linux-hardware.org/?probe=4d64247a8a) | Dec 04, 2021 |
| ASUSTek       | K53TK                       | [043ef58552](https://linux-hardware.org/?probe=043ef58552) | Dec 03, 2021 |
| HUAWEI        | KLVL-WXX9                   | [6c468accc0](https://linux-hardware.org/?probe=6c468accc0) | Dec 03, 2021 |
| HUAWEI        | KLVL-WXX9                   | [ee27adb248](https://linux-hardware.org/?probe=ee27adb248) | Dec 03, 2021 |
| Acer          | Aspire A315-58G             | [48e3c0e6c7](https://linux-hardware.org/?probe=48e3c0e6c7) | Dec 03, 2021 |
| HP            | OMEN Notebook               | [5b8b235c98](https://linux-hardware.org/?probe=5b8b235c98) | Dec 03, 2021 |
| Samsung       | 700T                        | [efe2d4bd92](https://linux-hardware.org/?probe=efe2d4bd92) | Dec 03, 2021 |
| Dell          | Latitude E6530              | [fe6dbdef48](https://linux-hardware.org/?probe=fe6dbdef48) | Dec 03, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [29ff3edb05](https://linux-hardware.org/?probe=29ff3edb05) | Dec 03, 2021 |
| Toshiba       | Satellite L655              | [0e3a82aad6](https://linux-hardware.org/?probe=0e3a82aad6) | Dec 03, 2021 |
| HUAWEI        | KLVL-WXX9                   | [c806323840](https://linux-hardware.org/?probe=c806323840) | Dec 03, 2021 |
| Dell          | Latitude 7280               | [8baf21a38d](https://linux-hardware.org/?probe=8baf21a38d) | Dec 02, 2021 |
| HUAWEI        | KLVL-WXX9                   | [57b4dae376](https://linux-hardware.org/?probe=57b4dae376) | Dec 02, 2021 |
| HP            | 15                          | [8d1ef12e0e](https://linux-hardware.org/?probe=8d1ef12e0e) | Dec 02, 2021 |
| HP            | ProBook 450 G3              | [ca49dc0eee](https://linux-hardware.org/?probe=ca49dc0eee) | Dec 02, 2021 |
| HP            | 15                          | [b374916ca6](https://linux-hardware.org/?probe=b374916ca6) | Dec 02, 2021 |
| Toshiba       | Satellite L55-B             | [0bc52401f0](https://linux-hardware.org/?probe=0bc52401f0) | Dec 02, 2021 |
| mPTech        | ARC 11.6 128GB HD           | [cb2302b704](https://linux-hardware.org/?probe=cb2302b704) | Dec 02, 2021 |
| mPTech        | ARC 11.6 128GB HD           | [f580be444b](https://linux-hardware.org/?probe=f580be444b) | Dec 02, 2021 |
| mPTech        | ARC 11.6 128GB HD           | [e2fbd06e2a](https://linux-hardware.org/?probe=e2fbd06e2a) | Dec 02, 2021 |
| TUXEDO        | Pulse 14 Gen1               | [c7eeb775f9](https://linux-hardware.org/?probe=c7eeb775f9) | Dec 02, 2021 |
| HP            | 15                          | [cb278b1a6b](https://linux-hardware.org/?probe=cb278b1a6b) | Dec 02, 2021 |
| Dell          | Latitude E5570              | [d7beab52f4](https://linux-hardware.org/?probe=d7beab52f4) | Dec 02, 2021 |
| Avell High... | B.ON                        | [a7513f22ee](https://linux-hardware.org/?probe=a7513f22ee) | Dec 02, 2021 |
| Primux        | 15R5A                       | [3aef7d25e8](https://linux-hardware.org/?probe=3aef7d25e8) | Dec 01, 2021 |
| ASUSTek       | X751LAB                     | [4383b601f4](https://linux-hardware.org/?probe=4383b601f4) | Nov 30, 2021 |
| MSI           | GF63 Thin 10SC              | [5f908f227a](https://linux-hardware.org/?probe=5f908f227a) | Nov 30, 2021 |
| HP            | EliteBook 8440p             | [cecc697189](https://linux-hardware.org/?probe=cecc697189) | Nov 30, 2021 |
| Dell          | Inspiron 15-3567            | [3a2bf12582](https://linux-hardware.org/?probe=3a2bf12582) | Nov 29, 2021 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | [7184635417](https://linux-hardware.org/?probe=7184635417) | Nov 29, 2021 |
| Dell          | Latitude 7275               | [bf808d506c](https://linux-hardware.org/?probe=bf808d506c) | Nov 29, 2021 |
| Chuwi         | GemiBook                    | [911b855817](https://linux-hardware.org/?probe=911b855817) | Nov 28, 2021 |
| Chuwi         | GemiBook                    | [b8f87029fa](https://linux-hardware.org/?probe=b8f87029fa) | Nov 28, 2021 |
| Dell          | Latitude E5420              | [9f504b4e6b](https://linux-hardware.org/?probe=9f504b4e6b) | Nov 28, 2021 |
| ASUSTek       | P453UJ                      | [056cba6efd](https://linux-hardware.org/?probe=056cba6efd) | Nov 28, 2021 |
| ASUSTek       | X455LJ                      | [018d5bcbac](https://linux-hardware.org/?probe=018d5bcbac) | Nov 27, 2021 |
| Acer          | Aspire 4830T                | [205025f3c7](https://linux-hardware.org/?probe=205025f3c7) | Nov 27, 2021 |
| Acer          | Aspire A315-42              | [a0483c5539](https://linux-hardware.org/?probe=a0483c5539) | Nov 27, 2021 |
| Toshiba       | Satellite L500              | [24645f6ab5](https://linux-hardware.org/?probe=24645f6ab5) | Nov 26, 2021 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | [25e2834604](https://linux-hardware.org/?probe=25e2834604) | Nov 25, 2021 |
| Acer          | Aspire 4830T                | [757863f7de](https://linux-hardware.org/?probe=757863f7de) | Nov 25, 2021 |
| Notebook      | NH50_70RA                   | [baa1c5d2ca](https://linux-hardware.org/?probe=baa1c5d2ca) | Nov 24, 2021 |
| HP            | Elite x2 1012 G1            | [5e2d2a574d](https://linux-hardware.org/?probe=5e2d2a574d) | Nov 24, 2021 |
| Lenovo        | Flex 2-14 20404             | [74894434bb](https://linux-hardware.org/?probe=74894434bb) | Nov 24, 2021 |
| ASUSTek       | GL552VW                     | [77929060f7](https://linux-hardware.org/?probe=77929060f7) | Nov 24, 2021 |
| Sony          | SVE1713Y1EB                 | [755b7b85f5](https://linux-hardware.org/?probe=755b7b85f5) | Nov 24, 2021 |
| HP            | EliteBook 8460p             | [ca30b13118](https://linux-hardware.org/?probe=ca30b13118) | Nov 24, 2021 |
| HP            | EliteBook 8570p             | [6c08986736](https://linux-hardware.org/?probe=6c08986736) | Nov 24, 2021 |
| Acer          | Okinawa                     | [2953f32ed9](https://linux-hardware.org/?probe=2953f32ed9) | Nov 23, 2021 |
| HP            | Pavilion 17                 | [315037ddfd](https://linux-hardware.org/?probe=315037ddfd) | Nov 23, 2021 |
| Sony          | VPCSA3N9E                   | [33a3597313](https://linux-hardware.org/?probe=33a3597313) | Nov 23, 2021 |
| Sony          | VPCSA3N9E                   | [c1bf05d67a](https://linux-hardware.org/?probe=c1bf05d67a) | Nov 23, 2021 |
| ASUSTek       | GL552VW                     | [59670a3933](https://linux-hardware.org/?probe=59670a3933) | Nov 23, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [56ff76e064](https://linux-hardware.org/?probe=56ff76e064) | Nov 23, 2021 |
| ASUSTek       | G750JX                      | [f503f26e28](https://linux-hardware.org/?probe=f503f26e28) | Nov 23, 2021 |
| HP            | Pavilion dv7                | [fa2ac7c179](https://linux-hardware.org/?probe=fa2ac7c179) | Nov 23, 2021 |
| Lenovo        | G580 20150                  | [baade6ba54](https://linux-hardware.org/?probe=baade6ba54) | Nov 22, 2021 |
| Lenovo        | G580 20150                  | [b7718027af](https://linux-hardware.org/?probe=b7718027af) | Nov 22, 2021 |
| HP            | 15                          | [1753404669](https://linux-hardware.org/?probe=1753404669) | Nov 22, 2021 |
| HP            | Notebook                    | [9e9ce14e95](https://linux-hardware.org/?probe=9e9ce14e95) | Nov 22, 2021 |
| ASUSTek       | X751SA                      | [d19fd8c59f](https://linux-hardware.org/?probe=d19fd8c59f) | Nov 22, 2021 |
| Toshiba       | Satellite L500              | [30bfdcb5ff](https://linux-hardware.org/?probe=30bfdcb5ff) | Nov 22, 2021 |
| HP            | ENVY TS 15                  | [ca6e82745c](https://linux-hardware.org/?probe=ca6e82745c) | Nov 22, 2021 |
| Fujitsu Si... | AMILO Pa 1510               | [9f731acb7e](https://linux-hardware.org/?probe=9f731acb7e) | Nov 22, 2021 |
| HP            | 15                          | [bca58eb5e0](https://linux-hardware.org/?probe=bca58eb5e0) | Nov 22, 2021 |
| Apple         | MacBookPro5,3               | [5a4e91eace](https://linux-hardware.org/?probe=5a4e91eace) | Nov 22, 2021 |
| ASUSTek       | U56E                        | [2b347f1923](https://linux-hardware.org/?probe=2b347f1923) | Nov 22, 2021 |
| Lenovo        | G560 0679                   | [15348ebbf9](https://linux-hardware.org/?probe=15348ebbf9) | Nov 22, 2021 |
| HP            | Pavilion 15                 | [0f1442bb2c](https://linux-hardware.org/?probe=0f1442bb2c) | Nov 22, 2021 |
| Toshiba       | PORTEGE R705                | [47688cd36a](https://linux-hardware.org/?probe=47688cd36a) | Nov 21, 2021 |
| Toshiba       | Satellite U300              | [827ec6ed62](https://linux-hardware.org/?probe=827ec6ed62) | Nov 21, 2021 |
| HP            | Pavilion dv7                | [7c745f9e5a](https://linux-hardware.org/?probe=7c745f9e5a) | Nov 21, 2021 |
| HP            | ENVY Notebook               | [09767edae3](https://linux-hardware.org/?probe=09767edae3) | Nov 21, 2021 |
| Dell          | Latitude E6440              | [babff23db6](https://linux-hardware.org/?probe=babff23db6) | Nov 21, 2021 |
| Dell          | G7 7700                     | [730daa1080](https://linux-hardware.org/?probe=730daa1080) | Nov 21, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6505        | [c99c5700f6](https://linux-hardware.org/?probe=c99c5700f6) | Nov 20, 2021 |
| HP            | Pavilion Notebook           | [ca1ccc6e65](https://linux-hardware.org/?probe=ca1ccc6e65) | Nov 20, 2021 |
| ASUSTek       | K53U                        | [12136b1cbd](https://linux-hardware.org/?probe=12136b1cbd) | Nov 20, 2021 |
| HP            | Pavilion 15                 | [687ecf1c58](https://linux-hardware.org/?probe=687ecf1c58) | Nov 20, 2021 |
| Sony          | SVE1713D1EW                 | [20d3ee7401](https://linux-hardware.org/?probe=20d3ee7401) | Nov 20, 2021 |
| ASUSTek       | K53U                        | [5a5b8c420f](https://linux-hardware.org/?probe=5a5b8c420f) | Nov 20, 2021 |
| Dell          | Latitude E7440              | [89fdff42c1](https://linux-hardware.org/?probe=89fdff42c1) | Nov 20, 2021 |
| Dell          | Precision M6700             | [a8bf3915fb](https://linux-hardware.org/?probe=a8bf3915fb) | Nov 20, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [7ddd35d3e8](https://linux-hardware.org/?probe=7ddd35d3e8) | Nov 20, 2021 |
| Sony          | SVE1713Y1EB                 | [4a77a751d9](https://linux-hardware.org/?probe=4a77a751d9) | Nov 20, 2021 |
| Toshiba       | Satellite C50D-B            | [6c92d7fef6](https://linux-hardware.org/?probe=6c92d7fef6) | Nov 19, 2021 |
| Dell          | Latitude E5550              | [2f52aa274c](https://linux-hardware.org/?probe=2f52aa274c) | Nov 19, 2021 |
| LG Electro... | S460-G.BG31P1               | [96d8266022](https://linux-hardware.org/?probe=96d8266022) | Nov 19, 2021 |
| Sony          | SVE1713D1EW                 | [cf21ed12bc](https://linux-hardware.org/?probe=cf21ed12bc) | Nov 18, 2021 |
| Lenovo        | ThinkPad X260 20F5S1GW1Q    | [3b8a61e460](https://linux-hardware.org/?probe=3b8a61e460) | Nov 18, 2021 |
| Google        | Lars                        | [c346746b7e](https://linux-hardware.org/?probe=c346746b7e) | Nov 18, 2021 |
| Dell          | Latitude 5590               | [8bef1790bd](https://linux-hardware.org/?probe=8bef1790bd) | Nov 18, 2021 |
| Toshiba       | Satellite C870-1C2          | [e3e16a0c1f](https://linux-hardware.org/?probe=e3e16a0c1f) | Nov 17, 2021 |
| Acer          | TravelMate 6292             | [2cec3b7547](https://linux-hardware.org/?probe=2cec3b7547) | Nov 17, 2021 |
| HP            | ENVY m7 Notebook            | [4b101cc132](https://linux-hardware.org/?probe=4b101cc132) | Nov 17, 2021 |
| HP            | Stream Notebook PC 14       | [31499aa79d](https://linux-hardware.org/?probe=31499aa79d) | Nov 17, 2021 |
| HP            | Stream Notebook PC 14       | [8c30001e99](https://linux-hardware.org/?probe=8c30001e99) | Nov 17, 2021 |
| Dell          | Precision M6700             | [fb4051d1de](https://linux-hardware.org/?probe=fb4051d1de) | Nov 17, 2021 |
| Lenovo        | ThinkPad T430 23445PU       | [e5fe64db56](https://linux-hardware.org/?probe=e5fe64db56) | Nov 16, 2021 |
| Toshiba       | Satellite C655D             | [cd8abc5170](https://linux-hardware.org/?probe=cd8abc5170) | Nov 16, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | [bfef77542f](https://linux-hardware.org/?probe=bfef77542f) | Nov 15, 2021 |
| Samsung       | 900X3C/900X3D/900X4C/900... | [76b69deb69](https://linux-hardware.org/?probe=76b69deb69) | Nov 14, 2021 |
| ASUSTek       | Vivobook_ASUSLaptop M350... | [3a3f503917](https://linux-hardware.org/?probe=3a3f503917) | Nov 14, 2021 |
| HP            | Notebook                    | [226dc7dc39](https://linux-hardware.org/?probe=226dc7dc39) | Nov 12, 2021 |
| HP            | Notebook                    | [c03f407f50](https://linux-hardware.org/?probe=c03f407f50) | Nov 12, 2021 |
| HP            | Notebook                    | [a2bae8d4b8](https://linux-hardware.org/?probe=a2bae8d4b8) | Nov 12, 2021 |
| HP            | Notebook                    | [87dec3cf7c](https://linux-hardware.org/?probe=87dec3cf7c) | Nov 12, 2021 |
| HP            | EliteBook 2560p             | [e3997c3bcb](https://linux-hardware.org/?probe=e3997c3bcb) | Nov 12, 2021 |
| Dell          | Inspiron 15-3567            | [e8879e98df](https://linux-hardware.org/?probe=e8879e98df) | Nov 12, 2021 |
| Google        | Kindred                     | [0046ef8942](https://linux-hardware.org/?probe=0046ef8942) | Nov 12, 2021 |
| Google        | Kindred                     | [9d72c8972c](https://linux-hardware.org/?probe=9d72c8972c) | Nov 12, 2021 |
| Acer          | Aspire 4830T                | [9ae2c69b2a](https://linux-hardware.org/?probe=9ae2c69b2a) | Nov 12, 2021 |
| Dell          | Precision M6700             | [9bf18c23c6](https://linux-hardware.org/?probe=9bf18c23c6) | Nov 12, 2021 |
| Notebook      | N85_N87HCHNHZ               | [32988fae95](https://linux-hardware.org/?probe=32988fae95) | Nov 11, 2021 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [c948868090](https://linux-hardware.org/?probe=c948868090) | Nov 11, 2021 |
| Dell          | Inspiron 1750               | [6ffff20ec8](https://linux-hardware.org/?probe=6ffff20ec8) | Nov 11, 2021 |
| Sony          | SVF14211CLB                 | [7c0dacdd54](https://linux-hardware.org/?probe=7c0dacdd54) | Nov 10, 2021 |
| HUAWEI        | BOHB-WAX9                   | [3b1f90f3ab](https://linux-hardware.org/?probe=3b1f90f3ab) | Nov 10, 2021 |
| HUAWEI        | BOHB-WAX9                   | [3858faa240](https://linux-hardware.org/?probe=3858faa240) | Nov 10, 2021 |
| Sony          | SVF14211CLB                 | [fdfd650fcc](https://linux-hardware.org/?probe=fdfd650fcc) | Nov 10, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [94da614270](https://linux-hardware.org/?probe=94da614270) | Nov 10, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6505        | [72dd15e9c5](https://linux-hardware.org/?probe=72dd15e9c5) | Nov 10, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [0d017f9835](https://linux-hardware.org/?probe=0d017f9835) | Nov 10, 2021 |
| ASUSTek       | U46E                        | [d52a43c7fd](https://linux-hardware.org/?probe=d52a43c7fd) | Nov 10, 2021 |
| Dell          | Latitude 3440               | [eb76b9d1cf](https://linux-hardware.org/?probe=eb76b9d1cf) | Nov 09, 2021 |
| HP            | Pavilion dv6                | [605479abf7](https://linux-hardware.org/?probe=605479abf7) | Nov 08, 2021 |
| HP            | Pavilion dv6                | [b7a410c2e6](https://linux-hardware.org/?probe=b7a410c2e6) | Nov 08, 2021 |
| MSI           | GF63 Thin 9SC               | [d85e7a0ad3](https://linux-hardware.org/?probe=d85e7a0ad3) | Nov 07, 2021 |
| Dell          | Latitude E5420              | [b53c6bd6d2](https://linux-hardware.org/?probe=b53c6bd6d2) | Nov 07, 2021 |
| Acer          | Swift SF314-56G             | [bf298c7d2d](https://linux-hardware.org/?probe=bf298c7d2d) | Nov 07, 2021 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [520a472266](https://linux-hardware.org/?probe=520a472266) | Nov 07, 2021 |
| HP            | Compaq 8510p                | [ddecc261a1](https://linux-hardware.org/?probe=ddecc261a1) | Nov 07, 2021 |
| HP            | Compaq 8510p                | [c2434c1c08](https://linux-hardware.org/?probe=c2434c1c08) | Nov 07, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [a0d13572a5](https://linux-hardware.org/?probe=a0d13572a5) | Nov 06, 2021 |
| HP            | Laptop 15-bw0xx             | [746f64d20b](https://linux-hardware.org/?probe=746f64d20b) | Nov 06, 2021 |
| HP            | Laptop 15-bw0xx             | [245941966f](https://linux-hardware.org/?probe=245941966f) | Nov 06, 2021 |
| Sony          | SVE1713D1EW                 | [64fd6b328f](https://linux-hardware.org/?probe=64fd6b328f) | Nov 06, 2021 |
| Sony          | SVE1713D1EW                 | [45609f28be](https://linux-hardware.org/?probe=45609f28be) | Nov 06, 2021 |
| HP            | Compaq 6710b (KE121ET#AB... | [5d577f71a4](https://linux-hardware.org/?probe=5d577f71a4) | Nov 06, 2021 |
| HP            | Compaq 6710b (KE121ET#AB... | [c37780e9ad](https://linux-hardware.org/?probe=c37780e9ad) | Nov 06, 2021 |
| ASUSTek       | K53TA                       | [e924b214bc](https://linux-hardware.org/?probe=e924b214bc) | Nov 06, 2021 |
| Acer          | Aspire ES1-521              | [5ef4af5924](https://linux-hardware.org/?probe=5ef4af5924) | Nov 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [73b5ea9e0b](https://linux-hardware.org/?probe=73b5ea9e0b) | Nov 06, 2021 |
| HP            | ProBook 450 G4              | [a96a96d455](https://linux-hardware.org/?probe=a96a96d455) | Nov 05, 2021 |
| ASUSTek       | K45A                        | [f9bc7efe7b](https://linux-hardware.org/?probe=f9bc7efe7b) | Nov 05, 2021 |
| ASUSTek       | K45A                        | [096deec12d](https://linux-hardware.org/?probe=096deec12d) | Nov 05, 2021 |
| Sony          | VPCEG23EL                   | [cc967c03fb](https://linux-hardware.org/?probe=cc967c03fb) | Nov 05, 2021 |
| Acer          | Swift SF314-54              | [b506625dc2](https://linux-hardware.org/?probe=b506625dc2) | Nov 05, 2021 |
| ASUSTek       | X751NV                      | [ecf08805fe](https://linux-hardware.org/?probe=ecf08805fe) | Nov 03, 2021 |
| Dell          | Precision M6700             | [1865ed7cca](https://linux-hardware.org/?probe=1865ed7cca) | Nov 03, 2021 |
| Dell          | Latitude 5490               | [c5c1f555f1](https://linux-hardware.org/?probe=c5c1f555f1) | Nov 03, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | [9e7a883a59](https://linux-hardware.org/?probe=9e7a883a59) | Nov 03, 2021 |
| HP            | Notebook                    | [ee3bc3deef](https://linux-hardware.org/?probe=ee3bc3deef) | Nov 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [3acc230d6a](https://linux-hardware.org/?probe=3acc230d6a) | Nov 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c88adaac6e](https://linux-hardware.org/?probe=c88adaac6e) | Nov 02, 2021 |
| Lenovo        | ThinkPad T430 2349ED5       | [0697993e7c](https://linux-hardware.org/?probe=0697993e7c) | Nov 02, 2021 |
| Lenovo        | IdeaPad Z580                | [0f9c8eb860](https://linux-hardware.org/?probe=0f9c8eb860) | Nov 02, 2021 |
| Toshiba       | Satellite C870-1C2          | [7e5a2d91f8](https://linux-hardware.org/?probe=7e5a2d91f8) | Nov 02, 2021 |
| HP            | ProBook 440 G4              | [695b9a4e0c](https://linux-hardware.org/?probe=695b9a4e0c) | Nov 01, 2021 |
| HP            | ProBook 440 G4              | [4bba4734e8](https://linux-hardware.org/?probe=4bba4734e8) | Nov 01, 2021 |
| Dell          | XPS 15 9510                 | [9ad082f18e](https://linux-hardware.org/?probe=9ad082f18e) | Nov 01, 2021 |
| ASUSTek       | K52Jc                       | [dfb687f14d](https://linux-hardware.org/?probe=dfb687f14d) | Nov 01, 2021 |
| HP            | 255 G8 Notebook PC          | [600b7b9957](https://linux-hardware.org/?probe=600b7b9957) | Nov 01, 2021 |
| Acer          | Aspire E1-522               | [56b475a93d](https://linux-hardware.org/?probe=56b475a93d) | Nov 01, 2021 |
| Toshiba       | Satellite Pro T110          | [3ae7a19459](https://linux-hardware.org/?probe=3ae7a19459) | Oct 31, 2021 |
| ASUSTek       | N61Ja                       | [e3fc4e0622](https://linux-hardware.org/?probe=e3fc4e0622) | Oct 31, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [83d642714b](https://linux-hardware.org/?probe=83d642714b) | Oct 31, 2021 |
| Apple         | MacBookPro11,2              | [eabb3946ad](https://linux-hardware.org/?probe=eabb3946ad) | Oct 31, 2021 |
| ASUSTek       | N61Ja                       | [3861fce83e](https://linux-hardware.org/?probe=3861fce83e) | Oct 31, 2021 |
| Apple         | MacBookPro11,2              | [2388e68622](https://linux-hardware.org/?probe=2388e68622) | Oct 31, 2021 |
| Dell          | Inspiron 7720               | [9f298535a5](https://linux-hardware.org/?probe=9f298535a5) | Oct 31, 2021 |
| HP            | 255 G8 Notebook PC          | [cb9c15cf6f](https://linux-hardware.org/?probe=cb9c15cf6f) | Oct 30, 2021 |
| Dell          | Latitude E6500              | [e475348b1e](https://linux-hardware.org/?probe=e475348b1e) | Oct 30, 2021 |
| MECER         | Z140C+Home                  | [2fbf6f153b](https://linux-hardware.org/?probe=2fbf6f153b) | Oct 30, 2021 |
| HP            | Pavilion Notebook           | [85a55f5c3c](https://linux-hardware.org/?probe=85a55f5c3c) | Oct 30, 2021 |
| Lenovo        | IdeaPad Z580                | [16ebdc4388](https://linux-hardware.org/?probe=16ebdc4388) | Oct 30, 2021 |
| Lenovo        | IdeaPad Z580                | [6260be6de5](https://linux-hardware.org/?probe=6260be6de5) | Oct 30, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | [af0a995721](https://linux-hardware.org/?probe=af0a995721) | Oct 30, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [88286c36e9](https://linux-hardware.org/?probe=88286c36e9) | Oct 29, 2021 |
| Acer          | Aspire A315-21              | [f5f4e2457b](https://linux-hardware.org/?probe=f5f4e2457b) | Oct 29, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [c74557d180](https://linux-hardware.org/?probe=c74557d180) | Oct 29, 2021 |
| Acer          | Aspire A315-21              | [35b5fcb787](https://linux-hardware.org/?probe=35b5fcb787) | Oct 28, 2021 |
| ASUSTek       | N71Jv                       | [29e3747e17](https://linux-hardware.org/?probe=29e3747e17) | Oct 28, 2021 |
| ASUSTek       | X750JB                      | [90fd9f38fc](https://linux-hardware.org/?probe=90fd9f38fc) | Oct 27, 2021 |
| Lenovo        | G570 4334                   | [cc07ebf9b6](https://linux-hardware.org/?probe=cc07ebf9b6) | Oct 27, 2021 |
| HP            | EliteBook 8440p             | [f527983cc9](https://linux-hardware.org/?probe=f527983cc9) | Oct 27, 2021 |
| Toshiba       | PORTEGE Z20t-C              | [ed1722174a](https://linux-hardware.org/?probe=ed1722174a) | Oct 27, 2021 |
| Lenovo        | Legion Y920-17IKB Laptop... | [830d4c9d9d](https://linux-hardware.org/?probe=830d4c9d9d) | Oct 26, 2021 |
| Acer          | Aspire 5737Z                | [9bbf3befab](https://linux-hardware.org/?probe=9bbf3befab) | Oct 26, 2021 |
| Lenovo        | ThinkPad T520 4242W4F       | [4104e265ea](https://linux-hardware.org/?probe=4104e265ea) | Oct 26, 2021 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | [3da20846f5](https://linux-hardware.org/?probe=3da20846f5) | Oct 26, 2021 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | [2d19155e7f](https://linux-hardware.org/?probe=2d19155e7f) | Oct 26, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [ed4e9d1a03](https://linux-hardware.org/?probe=ed4e9d1a03) | Oct 26, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [f5b1e904b7](https://linux-hardware.org/?probe=f5b1e904b7) | Oct 26, 2021 |
| HP            | ProBook 445 G7              | [87b3274937](https://linux-hardware.org/?probe=87b3274937) | Oct 26, 2021 |
| HP            | Stream Notebook PC 11       | [c240a088a9](https://linux-hardware.org/?probe=c240a088a9) | Oct 26, 2021 |
| HP            | ENVY m7 Notebook            | [235fa5cacd](https://linux-hardware.org/?probe=235fa5cacd) | Oct 25, 2021 |
| Dell          | Latitude E6430              | [fa4d12994d](https://linux-hardware.org/?probe=fa4d12994d) | Oct 25, 2021 |
| Schenker      | VIA 15 Pro                  | [7242436545](https://linux-hardware.org/?probe=7242436545) | Oct 24, 2021 |
| Toshiba       | Satellite C70-B             | [a17b7c3888](https://linux-hardware.org/?probe=a17b7c3888) | Oct 24, 2021 |
| Thomson       | N17C512                     | [20abb09d3a](https://linux-hardware.org/?probe=20abb09d3a) | Oct 24, 2021 |
| Notebook      | X170SM                      | [2054d0dee6](https://linux-hardware.org/?probe=2054d0dee6) | Oct 24, 2021 |
| Notebook      | X170SM                      | [f704af17a3](https://linux-hardware.org/?probe=f704af17a3) | Oct 24, 2021 |
| Dell          | Latitude D630               | [1cfebe8169](https://linux-hardware.org/?probe=1cfebe8169) | Oct 23, 2021 |
| Dell          | Latitude E6410              | [f4cdc942dc](https://linux-hardware.org/?probe=f4cdc942dc) | Oct 23, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [fe4aa7e54d](https://linux-hardware.org/?probe=fe4aa7e54d) | Oct 23, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [db85bd77fc](https://linux-hardware.org/?probe=db85bd77fc) | Oct 23, 2021 |
| HP            | ProBook 6550b               | [4db59c8489](https://linux-hardware.org/?probe=4db59c8489) | Oct 23, 2021 |
| Acer          | Aspire ES1-521              | [c6582bba7d](https://linux-hardware.org/?probe=c6582bba7d) | Oct 23, 2021 |
| Acer          | Aspire ES1-521              | [248ab157b8](https://linux-hardware.org/?probe=248ab157b8) | Oct 23, 2021 |
| HP            | Notebook                    | [11013f1334](https://linux-hardware.org/?probe=11013f1334) | Oct 22, 2021 |
| Google        | Kindred                     | [675265477a](https://linux-hardware.org/?probe=675265477a) | Oct 22, 2021 |
| HP            | 255 G4 Notebook PC          | [e7e49e8cc0](https://linux-hardware.org/?probe=e7e49e8cc0) | Oct 22, 2021 |
| Dell          | Latitude E7470              | [061c5e449c](https://linux-hardware.org/?probe=061c5e449c) | Oct 22, 2021 |
| MSI           | Modern 14 B10MW             | [ae43e74753](https://linux-hardware.org/?probe=ae43e74753) | Oct 21, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | [8668abcc62](https://linux-hardware.org/?probe=8668abcc62) | Oct 21, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | [18cf55aa72](https://linux-hardware.org/?probe=18cf55aa72) | Oct 21, 2021 |
| Toshiba       | Satellite L755              | [985ff9ba03](https://linux-hardware.org/?probe=985ff9ba03) | Oct 21, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [63c9d05f24](https://linux-hardware.org/?probe=63c9d05f24) | Oct 20, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [85036968bb](https://linux-hardware.org/?probe=85036968bb) | Oct 20, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3F30... | [6d2d97674c](https://linux-hardware.org/?probe=6d2d97674c) | Oct 19, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3F30... | [facdd98487](https://linux-hardware.org/?probe=facdd98487) | Oct 19, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [961f066acf](https://linux-hardware.org/?probe=961f066acf) | Oct 19, 2021 |
| Dell          | Latitude E7470              | [fdc6203a6e](https://linux-hardware.org/?probe=fdc6203a6e) | Oct 18, 2021 |
| Dell          | Latitude E6420              | [027441e6d4](https://linux-hardware.org/?probe=027441e6d4) | Oct 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6210b749a1](https://linux-hardware.org/?probe=6210b749a1) | Oct 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dbf1e020b0](https://linux-hardware.org/?probe=dbf1e020b0) | Oct 18, 2021 |
| Dell          | Inspiron 3521               | [2ffe8489e1](https://linux-hardware.org/?probe=2ffe8489e1) | Oct 18, 2021 |
| Toshiba       | Satellite C870-1C2          | [076883700d](https://linux-hardware.org/?probe=076883700d) | Oct 17, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [10f8e5f5cf](https://linux-hardware.org/?probe=10f8e5f5cf) | Oct 17, 2021 |
| Acer          | Aspire R3-131T              | [014464c088](https://linux-hardware.org/?probe=014464c088) | Oct 17, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [15ce74dcd6](https://linux-hardware.org/?probe=15ce74dcd6) | Oct 17, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [97c3495c65](https://linux-hardware.org/?probe=97c3495c65) | Oct 17, 2021 |
| Unknown       | CherryTrail                 | [01d095b201](https://linux-hardware.org/?probe=01d095b201) | Oct 17, 2021 |
| Acer          | Aspire E5-571               | [76090a2652](https://linux-hardware.org/?probe=76090a2652) | Oct 16, 2021 |
| HP            | Stream Laptop 14-ax0XX      | [ff6de8e062](https://linux-hardware.org/?probe=ff6de8e062) | Oct 16, 2021 |
| Lenovo        | G50-70 20351                | [d0d0d99be6](https://linux-hardware.org/?probe=d0d0d99be6) | Oct 16, 2021 |
| Lenovo        | Flex 2-14 20404             | [ef609865b5](https://linux-hardware.org/?probe=ef609865b5) | Oct 16, 2021 |
| Lenovo        | Flex 2-14 20404             | [4fc5c2f99f](https://linux-hardware.org/?probe=4fc5c2f99f) | Oct 16, 2021 |
| Dell          | Latitude E7440              | [cfe53904bc](https://linux-hardware.org/?probe=cfe53904bc) | Oct 16, 2021 |
| Unknown       | Unknown                     | [3233e1293c](https://linux-hardware.org/?probe=3233e1293c) | Oct 15, 2021 |
| Acer          | Aspire E5-576G              | [6f17f5d2c0](https://linux-hardware.org/?probe=6f17f5d2c0) | Oct 15, 2021 |
| HP            | Pavilion dv7                | [2d35a2ee5d](https://linux-hardware.org/?probe=2d35a2ee5d) | Oct 15, 2021 |
| HP            | ENVY m7 Notebook            | [f0af05f6f9](https://linux-hardware.org/?probe=f0af05f6f9) | Oct 15, 2021 |
| Unknown       | Unknown                     | [ddc6d80716](https://linux-hardware.org/?probe=ddc6d80716) | Oct 15, 2021 |
| Toshiba       | Satellite L755              | [fdaa2dd77e](https://linux-hardware.org/?probe=fdaa2dd77e) | Oct 14, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [6edbff3019](https://linux-hardware.org/?probe=6edbff3019) | Oct 14, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [3f90ae6d67](https://linux-hardware.org/?probe=3f90ae6d67) | Oct 14, 2021 |
| Dell          | Latitude E6420              | [14b08ab14d](https://linux-hardware.org/?probe=14b08ab14d) | Oct 14, 2021 |
| ASUSTek       | GL702VI                     | [c342d6fdc1](https://linux-hardware.org/?probe=c342d6fdc1) | Oct 14, 2021 |
| HP            | 15                          | [5534f9e3fc](https://linux-hardware.org/?probe=5534f9e3fc) | Oct 14, 2021 |
| Acer          | Swift SF314-59              | [2cd9b13bb1](https://linux-hardware.org/?probe=2cd9b13bb1) | Oct 14, 2021 |
| HP            | 15                          | [bfc196e22b](https://linux-hardware.org/?probe=bfc196e22b) | Oct 13, 2021 |
| ASUSTek       | X501A1                      | [0494cb6f11](https://linux-hardware.org/?probe=0494cb6f11) | Oct 13, 2021 |
| HP            | Notebook                    | [58c6628ba2](https://linux-hardware.org/?probe=58c6628ba2) | Oct 12, 2021 |
| HP            | Notebook                    | [f3f5e6256d](https://linux-hardware.org/?probe=f3f5e6256d) | Oct 12, 2021 |
| Dell          | Inspiron 5721               | [a13d0383b6](https://linux-hardware.org/?probe=a13d0383b6) | Oct 12, 2021 |
| Dell          | Inspiron 5721               | [686377ccd0](https://linux-hardware.org/?probe=686377ccd0) | Oct 12, 2021 |
| HP            | EliteBook 840 G1            | [9bb8ba744e](https://linux-hardware.org/?probe=9bb8ba744e) | Oct 12, 2021 |
| Apple         | MacBookPro8,1               | [01a3f25bec](https://linux-hardware.org/?probe=01a3f25bec) | Oct 12, 2021 |
| Apple         | MacBookPro8,1               | [d8de6fc953](https://linux-hardware.org/?probe=d8de6fc953) | Oct 12, 2021 |
| Giani Limi... | ENY1158M                    | [1f9a85e980](https://linux-hardware.org/?probe=1f9a85e980) | Oct 11, 2021 |
| Giani Limi... | ENY1158M                    | [4516242881](https://linux-hardware.org/?probe=4516242881) | Oct 11, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | [471414140c](https://linux-hardware.org/?probe=471414140c) | Oct 11, 2021 |
| Unknown       | Z3735F-T02 V1.2             | [6ef4e9edf6](https://linux-hardware.org/?probe=6ef4e9edf6) | Oct 11, 2021 |
| Dell          | Inspiron 3537               | [9614492711](https://linux-hardware.org/?probe=9614492711) | Oct 11, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [f5147cd609](https://linux-hardware.org/?probe=f5147cd609) | Oct 10, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | [fc28e4f7f8](https://linux-hardware.org/?probe=fc28e4f7f8) | Oct 10, 2021 |
| HP            | x2 210                      | [ccf01919ab](https://linux-hardware.org/?probe=ccf01919ab) | Oct 09, 2021 |
| HP            | x2 210                      | [a35274c0a7](https://linux-hardware.org/?probe=a35274c0a7) | Oct 09, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [e1a73cbf10](https://linux-hardware.org/?probe=e1a73cbf10) | Oct 09, 2021 |
| Samsung       | 700Z3C/700Z5C               | [007ba2bac1](https://linux-hardware.org/?probe=007ba2bac1) | Oct 09, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [63e608b4af](https://linux-hardware.org/?probe=63e608b4af) | Oct 09, 2021 |
| Acer          | Aspire E5-571               | [e988105956](https://linux-hardware.org/?probe=e988105956) | Oct 09, 2021 |
| ASUSTek       | X555YA                      | [7bbcc6c5af](https://linux-hardware.org/?probe=7bbcc6c5af) | Oct 09, 2021 |
| HP            | Laptop 17z-cp000            | [db7c1566db](https://linux-hardware.org/?probe=db7c1566db) | Oct 09, 2021 |
| HP            | ENVY dv6                    | [21a3477c3d](https://linux-hardware.org/?probe=21a3477c3d) | Oct 08, 2021 |
| MSI           | GE66 Raider 10UH            | [43c72c2ff3](https://linux-hardware.org/?probe=43c72c2ff3) | Oct 08, 2021 |
| HP            | Unknown                     | [c65be179d9](https://linux-hardware.org/?probe=c65be179d9) | Oct 08, 2021 |
| Acer          | TravelMate P259-MG          | [c62543cf86](https://linux-hardware.org/?probe=c62543cf86) | Oct 07, 2021 |
| HP            | Laptop 15s-fq1xxx           | [b81ab61049](https://linux-hardware.org/?probe=b81ab61049) | Oct 07, 2021 |
| HP            | Pavilion dv7                | [e139664dbf](https://linux-hardware.org/?probe=e139664dbf) | Oct 07, 2021 |
| Lenovo        | Z50-75 80EC                 | [2550a17ad0](https://linux-hardware.org/?probe=2550a17ad0) | Oct 07, 2021 |
| Star Labs     | LabTop                      | [711f2b9e6d](https://linux-hardware.org/?probe=711f2b9e6d) | Oct 07, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [ae113c0df0](https://linux-hardware.org/?probe=ae113c0df0) | Oct 06, 2021 |
| Dell          | Latitude E5400              | [6878f58676](https://linux-hardware.org/?probe=6878f58676) | Oct 06, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [a87e581c64](https://linux-hardware.org/?probe=a87e581c64) | Oct 06, 2021 |
| Dell          | Latitude E5400              | [b69897eca3](https://linux-hardware.org/?probe=b69897eca3) | Oct 06, 2021 |
| Dell          | Latitude E5530 non-vPro     | [afe8fca994](https://linux-hardware.org/?probe=afe8fca994) | Oct 06, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [dc9074514c](https://linux-hardware.org/?probe=dc9074514c) | Oct 06, 2021 |
| ASUSTek       | X550LB                      | [d96d114426](https://linux-hardware.org/?probe=d96d114426) | Oct 06, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [6717c35dc9](https://linux-hardware.org/?probe=6717c35dc9) | Oct 05, 2021 |
| Dell          | Inspiron 3542               | [f67c2f8d32](https://linux-hardware.org/?probe=f67c2f8d32) | Oct 05, 2021 |
| Acer          | Aspire V5-471               | [6a5bc4355e](https://linux-hardware.org/?probe=6a5bc4355e) | Oct 05, 2021 |
| HP            | Notebook                    | [88b07c9f57](https://linux-hardware.org/?probe=88b07c9f57) | Oct 05, 2021 |
| HP            | Notebook                    | [28c9b584b1](https://linux-hardware.org/?probe=28c9b584b1) | Oct 05, 2021 |
| Dell          | Inspiron 3521               | [9e18ebff31](https://linux-hardware.org/?probe=9e18ebff31) | Oct 05, 2021 |
| Lenovo        | ThinkPad L470 20J5A00FLM    | [ccc6db1c41](https://linux-hardware.org/?probe=ccc6db1c41) | Oct 05, 2021 |
| Lenovo        | ThinkPad L470 20J5A00FLM    | [55ec005acb](https://linux-hardware.org/?probe=55ec005acb) | Oct 05, 2021 |
| Acer          | Aspire V5-471               | [4b9f0ceb64](https://linux-hardware.org/?probe=4b9f0ceb64) | Oct 05, 2021 |
| HP            | ProBook 430 G1              | [01109c5fde](https://linux-hardware.org/?probe=01109c5fde) | Oct 04, 2021 |
| Toshiba       | Satellite C70-B             | [2d4b467fdc](https://linux-hardware.org/?probe=2d4b467fdc) | Oct 04, 2021 |
| Dell          | Latitude E5570              | [bfc3702626](https://linux-hardware.org/?probe=bfc3702626) | Oct 04, 2021 |
| HP            | EliteBook 8440p             | [0890806446](https://linux-hardware.org/?probe=0890806446) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [6d94d45cf0](https://linux-hardware.org/?probe=6d94d45cf0) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [ab6b537db8](https://linux-hardware.org/?probe=ab6b537db8) | Oct 04, 2021 |
| HP            | Notebook                    | [c405133048](https://linux-hardware.org/?probe=c405133048) | Oct 03, 2021 |
| Dell          | Latitude 7390               | [50080eb85e](https://linux-hardware.org/?probe=50080eb85e) | Oct 03, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [a2ee189c63](https://linux-hardware.org/?probe=a2ee189c63) | Oct 03, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [a4f833babc](https://linux-hardware.org/?probe=a4f833babc) | Oct 03, 2021 |
| HP            | Pavilion dv7                | [30875abc8f](https://linux-hardware.org/?probe=30875abc8f) | Oct 03, 2021 |
| Dell          | Inspiron 7773               | [2713f21dd7](https://linux-hardware.org/?probe=2713f21dd7) | Oct 03, 2021 |
| Dell          | Latitude E5400              | [ffc2d5a399](https://linux-hardware.org/?probe=ffc2d5a399) | Oct 03, 2021 |
| Toshiba       | Satellite L455D             | [9413906eaa](https://linux-hardware.org/?probe=9413906eaa) | Oct 03, 2021 |
| Dell          | Inspiron 3542               | [e3247b14fa](https://linux-hardware.org/?probe=e3247b14fa) | Oct 02, 2021 |
| Dell          | Latitude E5400              | [529e29fb9d](https://linux-hardware.org/?probe=529e29fb9d) | Oct 02, 2021 |
| Toshiba       | Satellite Pro T110          | [3bd8210e7e](https://linux-hardware.org/?probe=3bd8210e7e) | Oct 01, 2021 |
| HP            | Laptop 15-bw0xx             | [642e96374e](https://linux-hardware.org/?probe=642e96374e) | Oct 01, 2021 |
| Dell          | Latitude E6520              | [e1bf1df5ae](https://linux-hardware.org/?probe=e1bf1df5ae) | Oct 01, 2021 |
| Unknown       | Unknown                     | [f92fca6d48](https://linux-hardware.org/?probe=f92fca6d48) | Oct 01, 2021 |
| Acer          | Nitro AN515-44              | [a7a50b0dbf](https://linux-hardware.org/?probe=a7a50b0dbf) | Oct 01, 2021 |
| HP            | Pavilion dv7                | [590a48aff9](https://linux-hardware.org/?probe=590a48aff9) | Sep 30, 2021 |
| Apple         | MacBook5,2                  | [359171629f](https://linux-hardware.org/?probe=359171629f) | Sep 30, 2021 |
| Apple         | MacBook5,2                  | [4e125287e4](https://linux-hardware.org/?probe=4e125287e4) | Sep 30, 2021 |
| HP            | EliteBook 830 G5            | [d0c34db7d4](https://linux-hardware.org/?probe=d0c34db7d4) | Sep 29, 2021 |
| HP            | ENVY 15                     | [4b949c1a1b](https://linux-hardware.org/?probe=4b949c1a1b) | Sep 29, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [3688fae067](https://linux-hardware.org/?probe=3688fae067) | Sep 29, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [3befe3f6e3](https://linux-hardware.org/?probe=3befe3f6e3) | Sep 29, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [c5f4555ed5](https://linux-hardware.org/?probe=c5f4555ed5) | Sep 29, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [fb88fc18f4](https://linux-hardware.org/?probe=fb88fc18f4) | Sep 29, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [cc9cc9e925](https://linux-hardware.org/?probe=cc9cc9e925) | Sep 28, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [6cf7de2b6b](https://linux-hardware.org/?probe=6cf7de2b6b) | Sep 28, 2021 |
| HP            | Pavilion dv7                | [7e0b76f736](https://linux-hardware.org/?probe=7e0b76f736) | Sep 28, 2021 |
| Acer          | Aspire 4830T                | [d36367eb22](https://linux-hardware.org/?probe=d36367eb22) | Sep 28, 2021 |
| Acer          | Aspire A315-56              | [3fc47b2c92](https://linux-hardware.org/?probe=3fc47b2c92) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | [d573d0691e](https://linux-hardware.org/?probe=d573d0691e) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | [f322cce11b](https://linux-hardware.org/?probe=f322cce11b) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | [6aa9666f2c](https://linux-hardware.org/?probe=6aa9666f2c) | Sep 27, 2021 |
| Dell          | Latitude E5570              | [b4f22d5062](https://linux-hardware.org/?probe=b4f22d5062) | Sep 27, 2021 |
| Dell          | Latitude E5570              | [42c88d1bb8](https://linux-hardware.org/?probe=42c88d1bb8) | Sep 27, 2021 |
| Toshiba       | PORTEGE R700                | [b7b8adedee](https://linux-hardware.org/?probe=b7b8adedee) | Sep 27, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [00b95678dd](https://linux-hardware.org/?probe=00b95678dd) | Sep 27, 2021 |
| ASUSTek       | X405UA                      | [3a78f7edf5](https://linux-hardware.org/?probe=3a78f7edf5) | Sep 26, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [a49a61fb7d](https://linux-hardware.org/?probe=a49a61fb7d) | Sep 26, 2021 |
| Lenovo        | ThinkPad T520 4242W19       | [0bbb8d9004](https://linux-hardware.org/?probe=0bbb8d9004) | Sep 26, 2021 |
| Acer          | Aspire 5738                 | [3a72e534d3](https://linux-hardware.org/?probe=3a72e534d3) | Sep 26, 2021 |
| Acer          | Aspire V3-571G              | [8bc152aa27](https://linux-hardware.org/?probe=8bc152aa27) | Sep 25, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [9267f59e81](https://linux-hardware.org/?probe=9267f59e81) | Sep 25, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [5404d5874a](https://linux-hardware.org/?probe=5404d5874a) | Sep 25, 2021 |
| Apple         | MacBook3,1                  | [67212f51d0](https://linux-hardware.org/?probe=67212f51d0) | Sep 25, 2021 |
| Dell          | Latitude E6220              | [08e1d2f464](https://linux-hardware.org/?probe=08e1d2f464) | Sep 25, 2021 |
| Acer          | Aspire V3-571G              | [9d3daebd14](https://linux-hardware.org/?probe=9d3daebd14) | Sep 25, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [6b6f1c017d](https://linux-hardware.org/?probe=6b6f1c017d) | Sep 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [953ed13df8](https://linux-hardware.org/?probe=953ed13df8) | Sep 24, 2021 |
| Toshiba       | PORTEGE Z30-A               | [a65f8af3ac](https://linux-hardware.org/?probe=a65f8af3ac) | Sep 24, 2021 |
| Apple         | MacBookPro14,1              | [2d0d6ceff3](https://linux-hardware.org/?probe=2d0d6ceff3) | Sep 24, 2021 |
| KOGAN         | KAL11C250SB                 | [b76a44f6d5](https://linux-hardware.org/?probe=b76a44f6d5) | Sep 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [1af2027db5](https://linux-hardware.org/?probe=1af2027db5) | Sep 24, 2021 |
| Dell          | Latitude E6430              | [5e66bde0c9](https://linux-hardware.org/?probe=5e66bde0c9) | Sep 24, 2021 |
| ASUSTek       | E403NA                      | [382c1a7b47](https://linux-hardware.org/?probe=382c1a7b47) | Sep 24, 2021 |
| HP            | Presario V6000 (GM018UA#... | [944d6af89a](https://linux-hardware.org/?probe=944d6af89a) | Sep 23, 2021 |
| MSI           | Modern 15 A11M              | [fe99af6254](https://linux-hardware.org/?probe=fe99af6254) | Sep 23, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [25d01e8fc6](https://linux-hardware.org/?probe=25d01e8fc6) | Sep 23, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [4d2aa790e0](https://linux-hardware.org/?probe=4d2aa790e0) | Sep 23, 2021 |
| Apple         | MacBookPro9,2               | [effa7b0365](https://linux-hardware.org/?probe=effa7b0365) | Sep 22, 2021 |
| HP            | Notebook                    | [91d439a6a4](https://linux-hardware.org/?probe=91d439a6a4) | Sep 22, 2021 |
| Dynabook      | PORTEGE A30-E               | [93fd738472](https://linux-hardware.org/?probe=93fd738472) | Sep 21, 2021 |
| Dynabook      | PORTEGE A30-E               | [0ec5acd020](https://linux-hardware.org/?probe=0ec5acd020) | Sep 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [a43f2dc4bf](https://linux-hardware.org/?probe=a43f2dc4bf) | Sep 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [069c0cafd0](https://linux-hardware.org/?probe=069c0cafd0) | Sep 21, 2021 |
| Toshiba       | Satellite L755              | [10baeecbf5](https://linux-hardware.org/?probe=10baeecbf5) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | [36c622eabc](https://linux-hardware.org/?probe=36c622eabc) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | [0ce8da0fe0](https://linux-hardware.org/?probe=0ce8da0fe0) | Sep 21, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [699803b74c](https://linux-hardware.org/?probe=699803b74c) | Sep 21, 2021 |
| UNOWHY        | Y13G011S4EI                 | [70511c9675](https://linux-hardware.org/?probe=70511c9675) | Sep 21, 2021 |
| Lenovo        | G580                        | [d7e35103d9](https://linux-hardware.org/?probe=d7e35103d9) | Sep 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [91055c07be](https://linux-hardware.org/?probe=91055c07be) | Sep 20, 2021 |
| LG Electro... | C400-G.BC22P1               | [ae16407ef3](https://linux-hardware.org/?probe=ae16407ef3) | Sep 20, 2021 |
| Acer          | Aspire E1-532               | [b0407bdd1c](https://linux-hardware.org/?probe=b0407bdd1c) | Sep 20, 2021 |
| Acer          | Aspire 5738                 | [01bb66e2a1](https://linux-hardware.org/?probe=01bb66e2a1) | Sep 20, 2021 |
| TianBei       | TB-H7                       | [06300b96a7](https://linux-hardware.org/?probe=06300b96a7) | Sep 19, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [d80cdfb094](https://linux-hardware.org/?probe=d80cdfb094) | Sep 19, 2021 |
| Toshiba       | Satellite C870-1C2          | [6129e531d9](https://linux-hardware.org/?probe=6129e531d9) | Sep 19, 2021 |
| Apple         | MacBookPro9,2               | [37f34b16c5](https://linux-hardware.org/?probe=37f34b16c5) | Sep 19, 2021 |
| Acer          | Aspire 4352                 | [3a9aedb538](https://linux-hardware.org/?probe=3a9aedb538) | Sep 19, 2021 |
| ASUSTek       | U31F                        | [908a7184ae](https://linux-hardware.org/?probe=908a7184ae) | Sep 19, 2021 |
| Dell          | XPS 13 9350                 | [4dda7e9a7e](https://linux-hardware.org/?probe=4dda7e9a7e) | Sep 18, 2021 |
| ASUSTek       | U31F                        | [7cf4ac39de](https://linux-hardware.org/?probe=7cf4ac39de) | Sep 18, 2021 |
| Dell          | System XPS L321X            | [2345076968](https://linux-hardware.org/?probe=2345076968) | Sep 18, 2021 |
| Dell          | Latitude E6430              | [2d96c4a645](https://linux-hardware.org/?probe=2d96c4a645) | Sep 17, 2021 |
| Dell          | Vostro 15-3568              | [42d68963c6](https://linux-hardware.org/?probe=42d68963c6) | Sep 17, 2021 |
| Dell          | Vostro 15-3568              | [50f90e7684](https://linux-hardware.org/?probe=50f90e7684) | Sep 17, 2021 |
| Lenovo        | ThinkPad T520 42435GG       | [73a4cd0692](https://linux-hardware.org/?probe=73a4cd0692) | Sep 17, 2021 |
| HP            | Unknown                     | [b0b3846ace](https://linux-hardware.org/?probe=b0b3846ace) | Sep 17, 2021 |
| Lenovo        | ThinkPad T520 42435GG       | [518209a322](https://linux-hardware.org/?probe=518209a322) | Sep 17, 2021 |
| Dell          | Latitude E5470              | [9a036a26a4](https://linux-hardware.org/?probe=9a036a26a4) | Sep 17, 2021 |
| HP            | Notebook                    | [6b2785c2e0](https://linux-hardware.org/?probe=6b2785c2e0) | Sep 17, 2021 |
| Dell          | Latitude E5500              | [286c99863b](https://linux-hardware.org/?probe=286c99863b) | Sep 16, 2021 |
| HP            | 245 G5 Notebook PC          | [ece740cf39](https://linux-hardware.org/?probe=ece740cf39) | Sep 16, 2021 |
| Lenovo        | ThinkPad P50 20EN001EUS     | [04ba56c326](https://linux-hardware.org/?probe=04ba56c326) | Sep 16, 2021 |
| Toshiba       | Satellite L755              | [142e3e40c2](https://linux-hardware.org/?probe=142e3e40c2) | Sep 16, 2021 |
| Toshiba       | Satellite C75D-B            | [152dd3680d](https://linux-hardware.org/?probe=152dd3680d) | Sep 16, 2021 |
| Jumper        | EZpad .A002                 | [c62d842a68](https://linux-hardware.org/?probe=c62d842a68) | Sep 16, 2021 |
| Lenovo        | ThinkPad P50 20EN001EUS     | [6d381b570b](https://linux-hardware.org/?probe=6d381b570b) | Sep 15, 2021 |
| HP            | 255 G4 Notebook PC          | [c8a384ed00](https://linux-hardware.org/?probe=c8a384ed00) | Sep 15, 2021 |
| HP            | EliteBook 840 G5            | [68305a2ede](https://linux-hardware.org/?probe=68305a2ede) | Sep 15, 2021 |
| Dell          | Latitude E7440              | [803cfd7e73](https://linux-hardware.org/?probe=803cfd7e73) | Sep 15, 2021 |
| Dell          | Latitude E6520              | [1bd8b6a82f](https://linux-hardware.org/?probe=1bd8b6a82f) | Sep 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [983922cfbf](https://linux-hardware.org/?probe=983922cfbf) | Sep 15, 2021 |
| Acer          | Aspire 5733Z                | [6cfdfd04c6](https://linux-hardware.org/?probe=6cfdfd04c6) | Sep 14, 2021 |
| HP            | Notebook                    | [d6825ad86c](https://linux-hardware.org/?probe=d6825ad86c) | Sep 14, 2021 |
| Lenovo        | G50-80 80E5                 | [ef850713da](https://linux-hardware.org/?probe=ef850713da) | Sep 14, 2021 |
| Sony          | VGN-SR5                     | [199ae9a9dd](https://linux-hardware.org/?probe=199ae9a9dd) | Sep 14, 2021 |
| Dell          | Latitude E5470              | [032f256bab](https://linux-hardware.org/?probe=032f256bab) | Sep 14, 2021 |
| Sony          | VPCF215FX                   | [173d8636d4](https://linux-hardware.org/?probe=173d8636d4) | Sep 14, 2021 |
| HP            | EliteBook Folio 9470m       | [b054524aac](https://linux-hardware.org/?probe=b054524aac) | Sep 14, 2021 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [29d5b02719](https://linux-hardware.org/?probe=29d5b02719) | Sep 13, 2021 |
| HP            | Pavilion Notebook           | [864dde8a99](https://linux-hardware.org/?probe=864dde8a99) | Sep 13, 2021 |
| Toshiba       | Satellite C870-1C2          | [3818ff8f07](https://linux-hardware.org/?probe=3818ff8f07) | Sep 12, 2021 |
| HP            | Victus by HP Laptop 16-e... | [6a980ac620](https://linux-hardware.org/?probe=6a980ac620) | Sep 12, 2021 |
| Dell          | Latitude E6430              | [aff84b5ec1](https://linux-hardware.org/?probe=aff84b5ec1) | Sep 12, 2021 |
| Google        | Kindred                     | [c9ee8560b8](https://linux-hardware.org/?probe=c9ee8560b8) | Sep 12, 2021 |
| Dell          | XPS M1330                   | [404d33775d](https://linux-hardware.org/?probe=404d33775d) | Sep 12, 2021 |
| Dell          | Latitude E5500              | [1e20247950](https://linux-hardware.org/?probe=1e20247950) | Sep 12, 2021 |
| Dell          | XPS M1330                   | [3dcddbd59e](https://linux-hardware.org/?probe=3dcddbd59e) | Sep 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b565f4eee3](https://linux-hardware.org/?probe=b565f4eee3) | Sep 11, 2021 |
| HP            | Laptop 15-dy1xxx            | [728e0facd6](https://linux-hardware.org/?probe=728e0facd6) | Sep 11, 2021 |
| Acer          | Aspire 4830T                | [4e69ac73e4](https://linux-hardware.org/?probe=4e69ac73e4) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | [33fd6d8c8f](https://linux-hardware.org/?probe=33fd6d8c8f) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | [fa33f94b27](https://linux-hardware.org/?probe=fa33f94b27) | Sep 11, 2021 |
| MSI           | GE75 Raider 8RF             | [350527f093](https://linux-hardware.org/?probe=350527f093) | Sep 10, 2021 |
| Toshiba       | Satellite Pro L450D         | [a15c916899](https://linux-hardware.org/?probe=a15c916899) | Sep 10, 2021 |
| Toshiba       | Satellite C850-1CP          | [8cec9884a8](https://linux-hardware.org/?probe=8cec9884a8) | Sep 10, 2021 |
| Unknown       | Unknown                     | [bbf81cb33e](https://linux-hardware.org/?probe=bbf81cb33e) | Sep 10, 2021 |
| Dell          | Latitude E5470              | [f6d8fa5367](https://linux-hardware.org/?probe=f6d8fa5367) | Sep 10, 2021 |
| Dell          | Latitude E5470              | [87b52d41c7](https://linux-hardware.org/?probe=87b52d41c7) | Sep 10, 2021 |
| HP            | Notebook                    | [24690d1b8b](https://linux-hardware.org/?probe=24690d1b8b) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | [38098784dd](https://linux-hardware.org/?probe=38098784dd) | Sep 09, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [53c03e65ce](https://linux-hardware.org/?probe=53c03e65ce) | Sep 09, 2021 |
| HP            | 255 G7 Notebook PC          | [6ab68f26ba](https://linux-hardware.org/?probe=6ab68f26ba) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | [e480169372](https://linux-hardware.org/?probe=e480169372) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | [c06b09d9c4](https://linux-hardware.org/?probe=c06b09d9c4) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | [87e79937c9](https://linux-hardware.org/?probe=87e79937c9) | Sep 09, 2021 |
| Lenovo        | IdeaPad 310 Touch-15IKB ... | [ccb4dc3d9a](https://linux-hardware.org/?probe=ccb4dc3d9a) | Sep 09, 2021 |
| Toshiba       | Satellite C75D-B            | [0f52ac751b](https://linux-hardware.org/?probe=0f52ac751b) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | [97b34f8c7f](https://linux-hardware.org/?probe=97b34f8c7f) | Sep 08, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8404b1fc92](https://linux-hardware.org/?probe=8404b1fc92) | Sep 08, 2021 |
| Lenovo        | ThinkPad E14 20RAS1Q800     | [a4d93ee5d2](https://linux-hardware.org/?probe=a4d93ee5d2) | Sep 08, 2021 |
| HP            | EliteBook 8560p             | [6bff88fb9e](https://linux-hardware.org/?probe=6bff88fb9e) | Sep 08, 2021 |
| Sony          | VGN-SR5                     | [7f93c9c366](https://linux-hardware.org/?probe=7f93c9c366) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | [3fc588a18d](https://linux-hardware.org/?probe=3fc588a18d) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | [fd38e5bf9d](https://linux-hardware.org/?probe=fd38e5bf9d) | Sep 08, 2021 |
| HP            | EliteBook 840 G3            | [22d88098a9](https://linux-hardware.org/?probe=22d88098a9) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | [be8d4bd453](https://linux-hardware.org/?probe=be8d4bd453) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | [47317abce2](https://linux-hardware.org/?probe=47317abce2) | Sep 08, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [e8f88bd1b2](https://linux-hardware.org/?probe=e8f88bd1b2) | Sep 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [98874d48b2](https://linux-hardware.org/?probe=98874d48b2) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f872b42a74](https://linux-hardware.org/?probe=f872b42a74) | Sep 07, 2021 |
| Acer          | V5-171                      | [8068be142e](https://linux-hardware.org/?probe=8068be142e) | Sep 07, 2021 |
| HP            | Notebook                    | [62a2618cde](https://linux-hardware.org/?probe=62a2618cde) | Sep 07, 2021 |
| Toshiba       | Satellite L755              | [92d22f65bf](https://linux-hardware.org/?probe=92d22f65bf) | Sep 07, 2021 |
| Samsung       | 550P5C/550P7C               | [a2a7c20bf7](https://linux-hardware.org/?probe=a2a7c20bf7) | Sep 07, 2021 |
| Dell          | Precision 3520              | [15e6e2c91d](https://linux-hardware.org/?probe=15e6e2c91d) | Sep 07, 2021 |
| Dell          | Precision 5550              | [8ae36d685d](https://linux-hardware.org/?probe=8ae36d685d) | Sep 07, 2021 |
| Dell          | Latitude E5430 non-vPro     | [368f488133](https://linux-hardware.org/?probe=368f488133) | Sep 07, 2021 |
| MSI           | GL62 7RDX                   | [be53fd4c86](https://linux-hardware.org/?probe=be53fd4c86) | Sep 07, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | [3eaf057f6f](https://linux-hardware.org/?probe=3eaf057f6f) | Sep 07, 2021 |
| Acer          | Swift SF114-34              | [8a66ec8e37](https://linux-hardware.org/?probe=8a66ec8e37) | Sep 07, 2021 |
| Lenovo        | B50-30 20382                | [f91b1f41fc](https://linux-hardware.org/?probe=f91b1f41fc) | Sep 06, 2021 |
| HP            | Pavilion dv5                | [27607d962e](https://linux-hardware.org/?probe=27607d962e) | Sep 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d1af312696](https://linux-hardware.org/?probe=d1af312696) | Sep 06, 2021 |
| Acer          | Aspire V3-571G              | [46499caf7a](https://linux-hardware.org/?probe=46499caf7a) | Sep 05, 2021 |
| Sony          | VPCS135FX                   | [55c2fa54ae](https://linux-hardware.org/?probe=55c2fa54ae) | Sep 05, 2021 |
| Apple         | MacBook3,1                  | [1473909011](https://linux-hardware.org/?probe=1473909011) | Sep 05, 2021 |
| Lenovo        | G505s 20255                 | [263eeefef0](https://linux-hardware.org/?probe=263eeefef0) | Sep 04, 2021 |
| Lenovo        | G505s 20255                 | [8cd745db58](https://linux-hardware.org/?probe=8cd745db58) | Sep 04, 2021 |
| HP            | ProBook 6450b               | [960930d457](https://linux-hardware.org/?probe=960930d457) | Sep 04, 2021 |
| HP            | ProBook 6450b               | [98041e0acd](https://linux-hardware.org/?probe=98041e0acd) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [303c36ac93](https://linux-hardware.org/?probe=303c36ac93) | Sep 03, 2021 |
| HP            | 255 G3                      | [bd1a8b58da](https://linux-hardware.org/?probe=bd1a8b58da) | Sep 03, 2021 |
| HP            | 255 G3                      | [b5f1c73339](https://linux-hardware.org/?probe=b5f1c73339) | Sep 03, 2021 |
| Acer          | Aspire A315-31              | [f07f0d19ca](https://linux-hardware.org/?probe=f07f0d19ca) | Sep 03, 2021 |
| HP            | EliteBook 840 G1            | [980716e0a8](https://linux-hardware.org/?probe=980716e0a8) | Sep 03, 2021 |
| ASUSTek       | GR8                         | [eb4fb4e1f2](https://linux-hardware.org/?probe=eb4fb4e1f2) | Sep 03, 2021 |
| Lenovo        | ThinkPad W520 4284AW3       | [6647a6a4b4](https://linux-hardware.org/?probe=6647a6a4b4) | Sep 03, 2021 |
| Acer          | Aspire R3-131T              | [62485c81e9](https://linux-hardware.org/?probe=62485c81e9) | Sep 02, 2021 |
| Acer          | Aspire E5-521G              | [d1aa71f003](https://linux-hardware.org/?probe=d1aa71f003) | Sep 02, 2021 |
| Acer          | Aspire 4830T                | [52441614fe](https://linux-hardware.org/?probe=52441614fe) | Sep 02, 2021 |
| Acer          | Aspire E1-522               | [8cd8899bae](https://linux-hardware.org/?probe=8cd8899bae) | Sep 02, 2021 |
| Toshiba       | Satellite C850D-11C         | [51748f289f](https://linux-hardware.org/?probe=51748f289f) | Sep 01, 2021 |
| HP            | ENVY 15                     | [d2bb5f165e](https://linux-hardware.org/?probe=d2bb5f165e) | Sep 01, 2021 |
| ASUSTek       | X405UA                      | [9bf230ee3f](https://linux-hardware.org/?probe=9bf230ee3f) | Aug 31, 2021 |
| Insyde        | i101c                       | [de0a5f2925](https://linux-hardware.org/?probe=de0a5f2925) | Aug 31, 2021 |
| HP            | EliteBook 840 G1            | [8439784c2b](https://linux-hardware.org/?probe=8439784c2b) | Aug 31, 2021 |
| HP            | Pavilion 15                 | [13ae124697](https://linux-hardware.org/?probe=13ae124697) | Aug 31, 2021 |
| ASUSTek       | K73SV                       | [e7c8d68b00](https://linux-hardware.org/?probe=e7c8d68b00) | Aug 31, 2021 |
| Dell          | XPS 15 9560                 | [fe38c67cd2](https://linux-hardware.org/?probe=fe38c67cd2) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | [80412fd612](https://linux-hardware.org/?probe=80412fd612) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | [f2542100bc](https://linux-hardware.org/?probe=f2542100bc) | Aug 30, 2021 |
| Lenovo        | B50-70 80EU                 | [9507d559fc](https://linux-hardware.org/?probe=9507d559fc) | Aug 30, 2021 |
| Apple         | MacBookPro11,1              | [1dbc26a990](https://linux-hardware.org/?probe=1dbc26a990) | Aug 29, 2021 |
| Packard Be... | DOT S                       | [0231531196](https://linux-hardware.org/?probe=0231531196) | Aug 29, 2021 |
| Packard Be... | DOT S                       | [4f0a335506](https://linux-hardware.org/?probe=4f0a335506) | Aug 29, 2021 |
| Lenovo        | ThinkPad T520 4242W4F       | [150dd830ac](https://linux-hardware.org/?probe=150dd830ac) | Aug 29, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [e63b8b96dd](https://linux-hardware.org/?probe=e63b8b96dd) | Aug 29, 2021 |
| Acer          | Aspire 5100                 | [2b16fed8a1](https://linux-hardware.org/?probe=2b16fed8a1) | Aug 28, 2021 |
| Toshiba       | Satellite S75Dt-A           | [c3e9c3d13b](https://linux-hardware.org/?probe=c3e9c3d13b) | Aug 28, 2021 |
| Acer          | Aspire A515-51              | [6acb0f573a](https://linux-hardware.org/?probe=6acb0f573a) | Aug 28, 2021 |
| ASUSTek       | K56CA                       | [90d571608f](https://linux-hardware.org/?probe=90d571608f) | Aug 28, 2021 |
| Dell          | Inspiron 5566               | [2c2761e770](https://linux-hardware.org/?probe=2c2761e770) | Aug 27, 2021 |
| Dell          | XPS 13 9310                 | [08009ad892](https://linux-hardware.org/?probe=08009ad892) | Aug 26, 2021 |
| Acer          | AO722                       | [e303d0c046](https://linux-hardware.org/?probe=e303d0c046) | Aug 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Dell          | Inspiron 7520               | [1798e6404c](https://linux-hardware.org/?probe=1798e6404c) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e18bc8fe09](https://linux-hardware.org/?probe=e18bc8fe09) | Aug 25, 2021 |
| Acer          | Aspire ES1-512              | [48b43bd242](https://linux-hardware.org/?probe=48b43bd242) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e576736426](https://linux-hardware.org/?probe=e576736426) | Aug 25, 2021 |
| TianBei       | TB-H7                       | [455dce9834](https://linux-hardware.org/?probe=455dce9834) | Aug 25, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [a64e3a0513](https://linux-hardware.org/?probe=a64e3a0513) | Aug 25, 2021 |
| LG Electro... | S460-G.BG31P1               | [99df59aebd](https://linux-hardware.org/?probe=99df59aebd) | Aug 24, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [3d58cb6ce0](https://linux-hardware.org/?probe=3d58cb6ce0) | Aug 24, 2021 |
| Acer          | Aspire 7715Z                | [4de4de1a31](https://linux-hardware.org/?probe=4de4de1a31) | Aug 24, 2021 |
| Lenovo        | G50-30 80G0                 | [27cdfce14b](https://linux-hardware.org/?probe=27cdfce14b) | Aug 24, 2021 |
| LG Electro... | A410-K.BE47P1               | [bfc75c9c3d](https://linux-hardware.org/?probe=bfc75c9c3d) | Aug 24, 2021 |
| Acer          | Aspire 8940G                | [24ff3cf596](https://linux-hardware.org/?probe=24ff3cf596) | Aug 23, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b0830bd154](https://linux-hardware.org/?probe=b0830bd154) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | [c56758deca](https://linux-hardware.org/?probe=c56758deca) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | [eaef6e8392](https://linux-hardware.org/?probe=eaef6e8392) | Aug 23, 2021 |
| Dell          | Precision M4800             | [9766c85e7d](https://linux-hardware.org/?probe=9766c85e7d) | Aug 23, 2021 |
| Dell          | Precision M4800             | [cd3dbe3a32](https://linux-hardware.org/?probe=cd3dbe3a32) | Aug 23, 2021 |
| Unknown       | Unknown                     | [b1587c998f](https://linux-hardware.org/?probe=b1587c998f) | Aug 23, 2021 |
| TianBei       | TB-H7                       | [2d1b3b2756](https://linux-hardware.org/?probe=2d1b3b2756) | Aug 23, 2021 |
| ASUSTek       | X550LD                      | [04365cbbbf](https://linux-hardware.org/?probe=04365cbbbf) | Aug 22, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | [43f252f22a](https://linux-hardware.org/?probe=43f252f22a) | Aug 22, 2021 |
| Apple         | MacBookPro11,5              | [814f16635c](https://linux-hardware.org/?probe=814f16635c) | Aug 22, 2021 |
| HP            | ProBook 450 G2              | [99f47f1645](https://linux-hardware.org/?probe=99f47f1645) | Aug 21, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | [7b1954838a](https://linux-hardware.org/?probe=7b1954838a) | Aug 21, 2021 |
| HP            | Notebook                    | [2586dc3a41](https://linux-hardware.org/?probe=2586dc3a41) | Aug 21, 2021 |
| Lenovo        | G50-30 80G0                 | [afbefeb6d3](https://linux-hardware.org/?probe=afbefeb6d3) | Aug 21, 2021 |
| Lenovo        | ThinkPad X131e 3371AL2      | [1963322393](https://linux-hardware.org/?probe=1963322393) | Aug 21, 2021 |
| ASUSTek       | GR8                         | [88416da5e8](https://linux-hardware.org/?probe=88416da5e8) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [ad6e3e064f](https://linux-hardware.org/?probe=ad6e3e064f) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [9a5653e44d](https://linux-hardware.org/?probe=9a5653e44d) | Aug 21, 2021 |
| Sony          | VGN-SR5                     | [3bbd8b33f0](https://linux-hardware.org/?probe=3bbd8b33f0) | Aug 20, 2021 |
| HP            | ENVY 14                     | [34f9505762](https://linux-hardware.org/?probe=34f9505762) | Aug 20, 2021 |
| Lenovo        | G50-70 20351                | [40249b1ea8](https://linux-hardware.org/?probe=40249b1ea8) | Aug 20, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [231e17454e](https://linux-hardware.org/?probe=231e17454e) | Aug 19, 2021 |
| Dell          | Inspiron N5040              | [0554d06022](https://linux-hardware.org/?probe=0554d06022) | Aug 19, 2021 |
| LG Electro... | 17U70N-R.AAS7U1             | [fd3572c46a](https://linux-hardware.org/?probe=fd3572c46a) | Aug 19, 2021 |
| Acer          | Nitro AN515-55              | [3a47dca146](https://linux-hardware.org/?probe=3a47dca146) | Aug 18, 2021 |
| HP            | ProBook 450 G2              | [a3e170c339](https://linux-hardware.org/?probe=a3e170c339) | Aug 17, 2021 |
| Acer          | Swift SF114-34              | [0a37eed9e8](https://linux-hardware.org/?probe=0a37eed9e8) | Aug 15, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fcfd1e5ba9](https://linux-hardware.org/?probe=fcfd1e5ba9) | Aug 15, 2021 |
| HP            | ProBook 430 G6              | [c5467376e9](https://linux-hardware.org/?probe=c5467376e9) | Aug 13, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [9718804b4a](https://linux-hardware.org/?probe=9718804b4a) | Aug 12, 2021 |
| HP            | ProBook 450 G2              | [67956ca49e](https://linux-hardware.org/?probe=67956ca49e) | Aug 10, 2021 |
| Acer          | Aspire E1-571               | [146f910c76](https://linux-hardware.org/?probe=146f910c76) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c7a0820fe0](https://linux-hardware.org/?probe=c7a0820fe0) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [950d41dbb8](https://linux-hardware.org/?probe=950d41dbb8) | Aug 09, 2021 |
| Dell          | Inspiron 7537               | [7a35ed5eb1](https://linux-hardware.org/?probe=7a35ed5eb1) | Aug 03, 2021 |
| Dell          | Inspiron 7537               | [3c865e72d1](https://linux-hardware.org/?probe=3c865e72d1) | Aug 03, 2021 |
| Acer          | Aspire E5-551G              | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Dell          | XPS L501X                   | [a3d8e737a5](https://linux-hardware.org/?probe=a3d8e737a5) | Jul 08, 2021 |
| Dell          | G3 3579                     | [92a8136dc4](https://linux-hardware.org/?probe=92a8136dc4) | Jul 03, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [1196d6821c](https://linux-hardware.org/?probe=1196d6821c) | Jul 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [d63c7755ee](https://linux-hardware.org/?probe=d63c7755ee) | Jun 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [369a214905](https://linux-hardware.org/?probe=369a214905) | Jun 25, 2021 |
| Dell          | Inspiron 3576               | [849d571ef0](https://linux-hardware.org/?probe=849d571ef0) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [9957b51bea](https://linux-hardware.org/?probe=9957b51bea) | Jun 24, 2021 |
| Dell          | Inspiron 3582               | [e2cd9a9c36](https://linux-hardware.org/?probe=e2cd9a9c36) | Jun 20, 2021 |
| Dell          | XPS 13 9370                 | [9e3a58b257](https://linux-hardware.org/?probe=9e3a58b257) | Jun 12, 2021 |
| Dell          | XPS 13 9370                 | [2aa1efb008](https://linux-hardware.org/?probe=2aa1efb008) | Jun 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [01cf29ba72](https://linux-hardware.org/?probe=01cf29ba72) | Jun 10, 2021 |
| HP            | 15                          | [f2132922af](https://linux-hardware.org/?probe=f2132922af) | Jun 08, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [a1dd6df8e7](https://linux-hardware.org/?probe=a1dd6df8e7) | Jun 07, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [957048adbb](https://linux-hardware.org/?probe=957048adbb) | Jun 06, 2021 |
| Dell          | Inspiron 3582               | [229600e417](https://linux-hardware.org/?probe=229600e417) | Jun 06, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [719041c9d4](https://linux-hardware.org/?probe=719041c9d4) | Jun 04, 2021 |
| HP            | ProBook 650 G2              | [bb92ab2244](https://linux-hardware.org/?probe=bb92ab2244) | May 30, 2021 |
| HP            | Unknown                     | [e6e060ca51](https://linux-hardware.org/?probe=e6e060ca51) | May 29, 2021 |
| HP            | Unknown                     | [324d49aba6](https://linux-hardware.org/?probe=324d49aba6) | May 29, 2021 |
| Razer         | Book 13 - RZ09-0357         | [c1cc1fcf2e](https://linux-hardware.org/?probe=c1cc1fcf2e) | May 27, 2021 |
| Dell          | Vostro 5490                 | [9d8401675e](https://linux-hardware.org/?probe=9d8401675e) | May 18, 2021 |
| Dell          | Vostro 5490                 | [3f02204090](https://linux-hardware.org/?probe=3f02204090) | May 18, 2021 |
| Acer          | Swift SF313-51              | [2b27dc30ac](https://linux-hardware.org/?probe=2b27dc30ac) | May 17, 2021 |
| ASUSTek       | X406UAR                     | [5c50159b19](https://linux-hardware.org/?probe=5c50159b19) | May 16, 2021 |
| ASUSTek       | X406UAR                     | [e3be0eaa69](https://linux-hardware.org/?probe=e3be0eaa69) | May 16, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [b71b291af5](https://linux-hardware.org/?probe=b71b291af5) | May 10, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [157ae0cc83](https://linux-hardware.org/?probe=157ae0cc83) | May 02, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [12081d4e79](https://linux-hardware.org/?probe=12081d4e79) | Apr 25, 2021 |
| Lenovo        | IdeaPad Y570 0862           | [94d22e7673](https://linux-hardware.org/?probe=94d22e7673) | Apr 23, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.11.0-27-generic           | 92        | 13.43%  |
| 5.11.0-38-generic           | 91        | 13.28%  |
| 5.11.0-37-generic           | 72        | 10.51%  |
| 5.11.0-40-generic           | 64        | 9.34%   |
| 5.11.0-41-generic           | 61        | 8.91%   |
| 5.11.0-43-generic           | 59        | 8.61%   |
| 5.11.0-34-generic           | 57        | 8.32%   |
| 5.13.0-28-generic           | 36        | 5.26%   |
| 5.13.0-27-generic           | 26        | 3.8%    |
| 5.11.0-46-generic           | 25        | 3.65%   |
| 5.11.0-36-generic           | 22        | 3.21%   |
| 5.13.0-30-generic           | 21        | 3.07%   |
| 5.11.0-44-generic           | 18        | 2.63%   |
| 5.11.0-25-generic           | 9         | 1.31%   |
| 5.8.0-53-generic            | 6         | 0.88%   |
| 5.8.0-59-generic            | 5         | 0.73%   |
| 5.8.0-55-generic            | 5         | 0.73%   |
| 5.8.0-50-generic            | 4         | 0.58%   |
| 5.8.0-63-generic            | 1         | 0.15%   |
| 5.8.0-49-generic            | 1         | 0.15%   |
| 5.16.0-051600rc8-lowlatency | 1         | 0.15%   |
| 5.16.0-051600rc4-generic    | 1         | 0.15%   |
| 5.15.24-xanmod1             | 1         | 0.15%   |
| 5.15.0-8.1-liquorix-amd64   | 1         | 0.15%   |
| 5.14.0-15.1-liquorix-amd64  | 1         | 0.15%   |
| 5.13.18-xanmod1             | 1         | 0.15%   |
| 5.13.0-25-generic           | 1         | 0.15%   |
| 5.13.0-1020-oem             | 1         | 0.15%   |
| 5.10.0-1052-oem             | 1         | 0.15%   |
| 5.10.0-1044-oem             | 1         | 0.15%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 535       | 82.43%  |
| 5.13.0  | 84        | 12.94%  |
| 5.8.0   | 22        | 3.39%   |
| 5.16.0  | 2         | 0.31%   |
| 5.10.0  | 2         | 0.31%   |
| 5.15.24 | 1         | 0.15%   |
| 5.15.0  | 1         | 0.15%   |
| 5.14.0  | 1         | 0.15%   |
| 5.13.18 | 1         | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 535       | 82.43%  |
| 5.13    | 85        | 13.1%   |
| 5.8     | 22        | 3.39%   |
| 5.16    | 2         | 0.31%   |
| 5.15    | 2         | 0.31%   |
| 5.10    | 2         | 0.31%   |
| 5.14    | 1         | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 632       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 595       | 93.7%   |
| XFCE       | 33        | 5.2%    |
| Unknown    | 5         | 0.79%   |
| X-Cinnamon | 1         | 0.16%   |
| KDE        | 1         | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 621       | 97.95%  |
| Wayland | 11        | 1.74%   |
| Unknown | 2         | 0.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 494       | 77.43%  |
| GDM3    | 71        | 11.13%  |
| GDM     | 66        | 10.34%  |
| LightDM | 6         | 0.94%   |
| SDDM    | 1         | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 251       | 39.53%  |
| de_DE | 58        | 9.13%   |
| en_GB | 51        | 8.03%   |
| pt_BR | 36        | 5.67%   |
| en_IN | 24        | 3.78%   |
| es_ES | 21        | 3.31%   |
| en_CA | 18        | 2.83%   |
| pl_PL | 16        | 2.52%   |
| fr_FR | 16        | 2.52%   |
| it_IT | 13        | 2.05%   |
| en_AU | 13        | 2.05%   |
| nl_NL | 11        | 1.73%   |
| es_MX | 11        | 1.73%   |
| ru_RU | 8         | 1.26%   |
| pt_PT | 7         | 1.1%    |
| fr_BE | 7         | 1.1%    |
| es_CL | 7         | 1.1%    |
| cs_CZ | 7         | 1.1%    |
| en_ZA | 6         | 0.94%   |
| sv_SE | 4         | 0.63%   |
| en_NZ | 4         | 0.63%   |
| de_AT | 4         | 0.63%   |
| hu_HU | 3         | 0.47%   |
| de_CH | 3         | 0.47%   |
| bg_BG | 3         | 0.47%   |
| ru_UA | 2         | 0.31%   |
| nl_BE | 2         | 0.31%   |
| nb_NO | 2         | 0.31%   |
| ja_JP | 2         | 0.31%   |
| hr_HR | 2         | 0.31%   |
| en_IL | 2         | 0.31%   |
| ar_EG | 2         | 0.31%   |
| tr_TR | 1         | 0.16%   |
| sl_SI | 1         | 0.16%   |
| sk_SK | 1         | 0.16%   |
| ro_RO | 1         | 0.16%   |
| fr_CA | 1         | 0.16%   |
| fi_FI | 1         | 0.16%   |
| es_UY | 1         | 0.16%   |
| es_PE | 1         | 0.16%   |
| es_PA | 1         | 0.16%   |
| es_EC | 1         | 0.16%   |
| es_CR | 1         | 0.16%   |
| es_CO | 1         | 0.16%   |
| es_BO | 1         | 0.16%   |
| es_AR | 1         | 0.16%   |
| en_SG | 1         | 0.16%   |
| en_PH | 1         | 0.16%   |
| el_GR | 1         | 0.16%   |
| da_DK | 1         | 0.16%   |
| C     | 1         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 385       | 60.34%  |
| BIOS | 253       | 39.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 600       | 94.94%  |
| Zfs     | 11        | 1.74%   |
| Overlay | 9         | 1.42%   |
| Btrfs   | 9         | 1.42%   |
| Xfs     | 2         | 0.32%   |
| Ext2    | 1         | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 567       | 88.87%  |
| GPT     | 63        | 9.87%   |
| MBR     | 8         | 1.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 621       | 98.1%   |
| Yes       | 12        | 1.9%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 574       | 90.39%  |
| Yes       | 61        | 9.61%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 131       | 20.73%  |
| Lenovo                 | 103       | 16.3%   |
| Dell                   | 100       | 15.82%  |
| ASUSTek Computer       | 80        | 12.66%  |
| Acer                   | 60        | 9.49%   |
| Toshiba                | 30        | 4.75%   |
| Apple                  | 16        | 2.53%   |
| MSI                    | 13        | 2.06%   |
| Sony                   | 12        | 1.9%    |
| Samsung Electronics    | 11        | 1.74%   |
| Unknown                | 10        | 1.58%   |
| Google                 | 6         | 0.95%   |
| Packard Bell           | 4         | 0.63%   |
| Notebook               | 4         | 0.63%   |
| LG Electronics         | 4         | 0.63%   |
| Razer                  | 3         | 0.47%   |
| Jumper                 | 3         | 0.47%   |
| HUAWEI                 | 3         | 0.47%   |
| Fujitsu                | 3         | 0.47%   |
| TUXEDO                 | 2         | 0.32%   |
| Multilaser             | 2         | 0.32%   |
| Fujitsu Siemens        | 2         | 0.32%   |
| Digibras               | 2         | 0.32%   |
| Chuwi                  | 2         | 0.32%   |
| UNOWHY                 | 1         | 0.16%   |
| TianBei                | 1         | 0.16%   |
| Thomson                | 1         | 0.16%   |
| TCL Communication      | 1         | 0.16%   |
| Star Labs              | 1         | 0.16%   |
| Schenker               | 1         | 0.16%   |
| RCA                    | 1         | 0.16%   |
| Primux                 | 1         | 0.16%   |
| Positivo               | 1         | 0.16%   |
| Novatech               | 1         | 0.16%   |
| NEC Computers          | 1         | 0.16%   |
| mPTech                 | 1         | 0.16%   |
| Mediacom               | 1         | 0.16%   |
| MECER                  | 1         | 0.16%   |
| Login Informatica      | 1         | 0.16%   |
| KOGAN                  | 1         | 0.16%   |
| Insyde                 | 1         | 0.16%   |
| Gigabyte Technology    | 1         | 0.16%   |
| Giani Limited          | 1         | 0.16%   |
| GEO                    | 1         | 0.16%   |
| Fusion5                | 1         | 0.16%   |
| e-shop.gr              | 1         | 0.16%   |
| Dynabook               | 1         | 0.16%   |
| Compaq                 | 1         | 0.16%   |
| Clevo                  | 1         | 0.16%   |
| Avell High Performance | 1         | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 12        | 1.9%    |
| HP Notebook                    | 8         | 1.27%   |
| HP 15                          | 6         | 0.95%   |
| HP Pavilion 15                 | 4         | 0.63%   |
| Dell Latitude E7440            | 4         | 0.63%   |
| Lenovo IdeaPad S340-14API 81NB | 3         | 0.47%   |
| Lenovo IdeaPad S145-15API 81V7 | 3         | 0.47%   |
| HP Pavilion Notebook           | 3         | 0.47%   |
| HP OMEN by Laptop 15-dc1xxx    | 3         | 0.47%   |
| Dell Latitude E6420            | 3         | 0.47%   |
| Apple MacBookPro8,1            | 3         | 0.47%   |
| Apple MacBookPro11,1           | 3         | 0.47%   |
| Packard Bell EasyNote TK85     | 2         | 0.32%   |
| Lenovo Yoga 3 Pro-1370 80HE    | 2         | 0.32%   |
| Lenovo IdeaPad Yoga 13 20175   | 2         | 0.32%   |
| Lenovo IdeaPad Flex-14API 81SS | 2         | 0.32%   |
| Lenovo IdeaPad 3 15IIL05 81WE  | 2         | 0.32%   |
| Lenovo G50-70 20351            | 2         | 0.32%   |
| Jumper EZbook                  | 2         | 0.32%   |
| HP ProBook 6450b               | 2         | 0.32%   |
| HP Pavilion Laptop 15-cs3xxx   | 2         | 0.32%   |
| HP Pavilion g6                 | 2         | 0.32%   |
| HP Pavilion dv7                | 2         | 0.32%   |
| HP Pavilion dv5                | 2         | 0.32%   |
| HP OMEN Notebook               | 2         | 0.32%   |
| HP Laptop 15-bw0xx             | 2         | 0.32%   |
| HP ENVY Sleekbook 4 PC         | 2         | 0.32%   |
| HP EliteBook Folio 9470m       | 2         | 0.32%   |
| HP EliteBook 8440p             | 2         | 0.32%   |
| HP EliteBook 840 G1            | 2         | 0.32%   |
| HP Compaq 8510p                | 2         | 0.32%   |
| Google Kindred                 | 2         | 0.32%   |
| Digibras NH4CU03               | 2         | 0.32%   |
| Dell XPS 15 9510               | 2         | 0.32%   |
| Dell Precision M4800           | 2         | 0.32%   |
| Dell Precision M4600           | 2         | 0.32%   |
| Dell Latitude E7470            | 2         | 0.32%   |
| Dell Latitude E6520            | 2         | 0.32%   |
| Dell Latitude E6430            | 2         | 0.32%   |
| Dell Latitude E5570            | 2         | 0.32%   |
| Dell Latitude E5500            | 2         | 0.32%   |
| Dell Latitude E5470            | 2         | 0.32%   |
| Dell Latitude 3440             | 2         | 0.32%   |
| Dell Inspiron 5770             | 2         | 0.32%   |
| Dell Inspiron 5566             | 2         | 0.32%   |
| Dell Inspiron 3542             | 2         | 0.32%   |
| Dell Inspiron 1750             | 2         | 0.32%   |
| Dell Inspiron 15-3567          | 2         | 0.32%   |
| Dell Inspiron 15 7000 Gaming   | 2         | 0.32%   |
| ASUS X553MA                    | 2         | 0.32%   |
| ASUS X405UA                    | 2         | 0.32%   |
| Apple MacBook4,1               | 2         | 0.32%   |
| Acer V5-171                    | 2         | 0.32%   |
| Acer E1-510                    | 2         | 0.32%   |
| Acer Aspire V3-571G            | 2         | 0.32%   |
| Acer Aspire V3-571             | 2         | 0.32%   |
| Acer Aspire ES1-512            | 2         | 0.32%   |
| Acer Aspire E1-522             | 2         | 0.32%   |
| UNOWHY Y13G011S4EI             | 1         | 0.16%   |
| TUXEDO Pulse 14 Gen1           | 1         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 45        | 7.12%   |
| Lenovo ThinkPad       | 43        | 6.8%    |
| Acer Aspire           | 42        | 6.65%   |
| Lenovo IdeaPad        | 30        | 4.75%   |
| Dell Inspiron         | 30        | 4.75%   |
| HP Pavilion           | 27        | 4.27%   |
| Toshiba Satellite     | 22        | 3.48%   |
| HP EliteBook          | 19        | 3.01%   |
| HP ProBook            | 17        | 2.69%   |
| ASUS VivoBook         | 12        | 1.9%    |
| Unknown               | 12        | 1.9%    |
| HP Laptop             | 10        | 1.58%   |
| HP ENVY               | 9         | 1.42%   |
| HP Notebook           | 8         | 1.27%   |
| Dell XPS              | 8         | 1.27%   |
| HP 15                 | 7         | 1.11%   |
| Dell Precision        | 7         | 1.11%   |
| HP Stream             | 6         | 0.95%   |
| HP OMEN               | 6         | 0.95%   |
| ASUS ZenBook          | 6         | 0.95%   |
| HP 255                | 5         | 0.79%   |
| Dell Vostro           | 5         | 0.79%   |
| Apple MacBookPro11    | 5         | 0.79%   |
| Acer Swift            | 5         | 0.79%   |
| Toshiba PORTEGE       | 4         | 0.63%   |
| HP Compaq             | 4         | 0.63%   |
| ASUS ASUS             | 4         | 0.63%   |
| Packard Bell EasyNote | 3         | 0.47%   |
| Lenovo Yoga           | 3         | 0.47%   |
| Lenovo ThinkBook      | 3         | 0.47%   |
| Fujitsu LIFEBOOK      | 3         | 0.47%   |
| ASUS TUF              | 3         | 0.47%   |
| ASUS ROG              | 3         | 0.47%   |
| Apple MacBookPro8     | 3         | 0.47%   |
| Toshiba TECRA         | 2         | 0.32%   |
| Toshiba QOSMIO        | 2         | 0.32%   |
| Razer Blade           | 2         | 0.32%   |
| MSI Modern            | 2         | 0.32%   |
| MSI GF63              | 2         | 0.32%   |
| MSI GE75              | 2         | 0.32%   |
| Lenovo Legion         | 2         | 0.32%   |
| Lenovo G580           | 2         | 0.32%   |
| Lenovo G50-70         | 2         | 0.32%   |
| Lenovo Flex           | 2         | 0.32%   |
| Jumper EZbook         | 2         | 0.32%   |
| Google Kindred        | 2         | 0.32%   |
| Digibras NH4CU03      | 2         | 0.32%   |
| Chuwi GemiBook        | 2         | 0.32%   |
| ASUS X553MA           | 2         | 0.32%   |
| ASUS X405UA           | 2         | 0.32%   |
| Apple MacBook4        | 2         | 0.32%   |
| Acer V5-171           | 2         | 0.32%   |
| Acer TravelMate       | 2         | 0.32%   |
| Acer Nitro            | 2         | 0.32%   |
| Acer E1-510           | 2         | 0.32%   |
| UNOWHY Y13G011S4EI    | 1         | 0.16%   |
| TUXEDO Pulse          | 1         | 0.16%   |
| TUXEDO InfinityBook   | 1         | 0.16%   |
| TianBei TB-H7         | 1         | 0.16%   |
| Thomson N17C512       | 1         | 0.16%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 64        | 10.13%  |
| 2011 | 61        | 9.65%   |
| 2019 | 56        | 8.86%   |
| 2013 | 55        | 8.7%    |
| 2020 | 50        | 7.91%   |
| 2017 | 49        | 7.75%   |
| 2014 | 48        | 7.59%   |
| 2021 | 44        | 6.96%   |
| 2016 | 39        | 6.17%   |
| 2018 | 37        | 5.85%   |
| 2010 | 35        | 5.54%   |
| 2015 | 29        | 4.59%   |
| 2008 | 28        | 4.43%   |
| 2009 | 18        | 2.85%   |
| 2007 | 16        | 2.53%   |
| 2006 | 3         | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 632       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 543       | 85.38%  |
| Enabled  | 93        | 14.62%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 625       | 98.89%  |
| Yes  | 7         | 1.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 221       | 34.97%  |
| 3.01-4.0    | 170       | 26.9%   |
| 8.01-16.0   | 91        | 14.4%   |
| 16.01-24.0  | 69        | 10.92%  |
| 1.01-2.0    | 35        | 5.54%   |
| 32.01-64.0  | 29        | 4.59%   |
| 2.01-3.0    | 9         | 1.42%   |
| 64.01-256.0 | 6         | 0.95%   |
| 24.01-32.0  | 1         | 0.16%   |
| 0.51-1.0    | 1         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 292       | 43.58%  |
| 2.01-3.0   | 217       | 32.39%  |
| 3.01-4.0   | 85        | 12.69%  |
| 4.01-8.0   | 56        | 8.36%   |
| 0.51-1.0   | 13        | 1.94%   |
| 8.01-16.0  | 5         | 0.75%   |
| 24.01-32.0 | 2         | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 480       | 75.47%  |
| 2      | 136       | 21.38%  |
| 3      | 15        | 2.36%   |
| 4      | 4         | 0.63%   |
| 0      | 1         | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 347       | 54.65%  |
| Yes       | 288       | 45.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 520       | 82.28%  |
| No        | 112       | 17.72%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 611       | 96.68%  |
| No        | 21        | 3.32%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 474       | 74.76%  |
| No        | 160       | 25.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| USA                    | 138       | 21.8%   |
| Germany                | 66        | 10.43%  |
| Brazil                 | 44        | 6.95%   |
| UK                     | 37        | 5.85%   |
| Spain                  | 26        | 4.11%   |
| India                  | 25        | 3.95%   |
| Canada                 | 20        | 3.16%   |
| Netherlands            | 16        | 2.53%   |
| Mexico                 | 15        | 2.37%   |
| Italy                  | 15        | 2.37%   |
| France                 | 15        | 2.37%   |
| Poland                 | 13        | 2.05%   |
| Belgium                | 13        | 2.05%   |
| Austria                | 13        | 2.05%   |
| Australia              | 13        | 2.05%   |
| South Africa           | 10        | 1.58%   |
| Sweden                 | 8         | 1.26%   |
| Russia                 | 8         | 1.26%   |
| Czechia                | 7         | 1.11%   |
| Chile                  | 7         | 1.11%   |
| Switzerland            | 6         | 0.95%   |
| Portugal               | 6         | 0.95%   |
| Turkey                 | 5         | 0.79%   |
| Norway                 | 5         | 0.79%   |
| Japan                  | 5         | 0.79%   |
| Hungary                | 5         | 0.79%   |
| Bulgaria               | 5         | 0.79%   |
| Romania                | 4         | 0.63%   |
| New Zealand            | 4         | 0.63%   |
| Indonesia              | 4         | 0.63%   |
| Greece                 | 4         | 0.63%   |
| Ukraine                | 3         | 0.47%   |
| Saudi Arabia           | 3         | 0.47%   |
| Morocco                | 3         | 0.47%   |
| Kenya                  | 3         | 0.47%   |
| Israel                 | 3         | 0.47%   |
| Ireland                | 3         | 0.47%   |
| Finland                | 3         | 0.47%   |
| Colombia               | 3         | 0.47%   |
| Vietnam                | 2         | 0.32%   |
| Singapore              | 2         | 0.32%   |
| Philippines            | 2         | 0.32%   |
| Moldova                | 2         | 0.32%   |
| Malaysia               | 2         | 0.32%   |
| Croatia                | 2         | 0.32%   |
| Bosnia and Herzegovina | 2         | 0.32%   |
| Bangladesh             | 2         | 0.32%   |
| Argentina              | 2         | 0.32%   |
| Venezuela              | 1         | 0.16%   |
| Uruguay                | 1         | 0.16%   |
| Thailand               | 1         | 0.16%   |
| Tanzania               | 1         | 0.16%   |
| Slovenia               | 1         | 0.16%   |
| Slovakia               | 1         | 0.16%   |
| Qatar                  | 1         | 0.16%   |
| Puerto Rico            | 1         | 0.16%   |
| Paraguay               | 1         | 0.16%   |
| Panama                 | 1         | 0.16%   |
| Palestine              | 1         | 0.16%   |
| Pakistan               | 1         | 0.16%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Vienna                 | 7         | 1.08%   |
| Sydney                 | 5         | 0.77%   |
| Amsterdam              | 5         | 0.77%   |
| Hamburg                | 4         | 0.62%   |
| Glasgow                | 4         | 0.62%   |
| Bernissart             | 4         | 0.62%   |
| Berlin                 | 4         | 0.62%   |
| Athens                 | 4         | 0.62%   |
| Warsaw                 | 3         | 0.46%   |
| SÃ£o Paulo           | 3         | 0.46%   |
| SÃ£o LuÃ­s         | 3         | 0.46%   |
| Rome                   | 3         | 0.46%   |
| Perth                  | 3         | 0.46%   |
| Paris                  | 3         | 0.46%   |
| New York               | 3         | 0.46%   |
| Nairobi                | 3         | 0.46%   |
| Moscow                 | 3         | 0.46%   |
| Melbourne              | 3         | 0.46%   |
| Madrid                 | 3         | 0.46%   |
| London                 | 3         | 0.46%   |
| Johannesburg           | 3         | 0.46%   |
| Dallas                 | 3         | 0.46%   |
| Chicago                | 3         | 0.46%   |
| Chennai                | 3         | 0.46%   |
| Brussels               | 3         | 0.46%   |
| Blue Springs           | 3         | 0.46%   |
| Barcelona              | 3         | 0.46%   |
| Zagreb                 | 2         | 0.31%   |
| Washington             | 2         | 0.31%   |
| Vicenza                | 2         | 0.31%   |
| Valencia               | 2         | 0.31%   |
| Taboao da Serra        | 2         | 0.31%   |
| Stuttgart              | 2         | 0.31%   |
| Stockholm              | 2         | 0.31%   |
| Smyrna                 | 2         | 0.31%   |
| Seattle                | 2         | 0.31%   |
| Sarajevo               | 2         | 0.31%   |
| Santiago               | 2         | 0.31%   |
| San Francisco          | 2         | 0.31%   |
| Red Deer               | 2         | 0.31%   |
| Recife                 | 2         | 0.31%   |
| RÃ¼sselsheim am Main | 2         | 0.31%   |
| Pucking                | 2         | 0.31%   |
| Providence             | 2         | 0.31%   |
| Porto Alegre           | 2         | 0.31%   |
| Munich                 | 2         | 0.31%   |
| Morrow                 | 2         | 0.31%   |
| Montreal               | 2         | 0.31%   |
| Minneapolis            | 2         | 0.31%   |
| Mexico City            | 2         | 0.31%   |
| MacaÃ©               | 2         | 0.31%   |
| La LouviÃ¨re         | 2         | 0.31%   |
| Kansas City            | 2         | 0.31%   |
| Hyderabad              | 2         | 0.31%   |
| Herzberg am Harz       | 2         | 0.31%   |
| Helsinki               | 2         | 0.31%   |
| Freising               | 2         | 0.31%   |
| Ernakulam              | 2         | 0.31%   |
| Ecatepec               | 2         | 0.31%   |
| Dortmund               | 2         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 114       | 139    | 15.28%  |
| Seagate                     | 97        | 112    | 13%     |
| WDC                         | 83        | 94     | 11.13%  |
| Toshiba                     | 72        | 76     | 9.65%   |
| Unknown                     | 56        | 67     | 7.51%   |
| SanDisk                     | 55        | 63     | 7.37%   |
| Kingston                    | 31        | 38     | 4.16%   |
| Crucial                     | 29        | 35     | 3.89%   |
| Hitachi                     | 23        | 28     | 3.08%   |
| SK Hynix                    | 18        | 25     | 2.41%   |
| Intel                       | 18        | 20     | 2.41%   |
| HGST                        | 18        | 23     | 2.41%   |
| Micron Technology           | 15        | 16     | 2.01%   |
| A-DATA Technology           | 13        | 14     | 1.74%   |
| Intenso                     | 7         | 7      | 0.94%   |
| Apple                       | 7         | 8      | 0.94%   |
| KIOXIA                      | 6         | 6      | 0.8%    |
| Transcend                   | 5         | 5      | 0.67%   |
| SPCC                        | 5         | 7      | 0.67%   |
| Fujitsu                     | 5         | 6      | 0.67%   |
| PNY                         | 4         | 5      | 0.54%   |
| LITEONIT                    | 4         | 5      | 0.54%   |
| GOODRAM                     | 4         | 4      | 0.54%   |
| China                       | 4         | 5      | 0.54%   |
| Phison                      | 3         | 4      | 0.4%    |
| Patriot                     | 3         | 3      | 0.4%    |
| Netac                       | 3         | 3      | 0.4%    |
| Lite-On                     | 3         | 5      | 0.4%    |
| Team                        | 2         | 2      | 0.27%   |
| SABRENT                     | 2         | 3      | 0.27%   |
| OCZ                         | 2         | 2      | 0.27%   |
| LITEON                      | 2         | 2      | 0.27%   |
| KingSpec                    | 2         | 2      | 0.27%   |
| JMicron                     | 2         | 3      | 0.27%   |
| Hewlett-Packard             | 2         | 2      | 0.27%   |
| BHT                         | 2         | 2      | 0.27%   |
| Unknown                     | 2         | 2      | 0.27%   |
| Yangtze Memory Technologies | 1         | 1      | 0.13%   |
| Verbatim                    | 1         | 1      | 0.13%   |
| Vaseky                      | 1         | 2      | 0.13%   |
| TO Exter                    | 1         | 1      | 0.13%   |
| Teclast                     | 1         | 1      | 0.13%   |
| T-FORCE                     | 1         | 1      | 0.13%   |
| Star                        | 1         | 1      | 0.13%   |
| Space ke                    | 1         | 1      | 0.13%   |
| Realtek Semiconductor       | 1         | 1      | 0.13%   |
| PLEXTOR                     | 1         | 1      | 0.13%   |
| OSCOO                       | 1         | 1      | 0.13%   |
| MidasForce                  | 1         | 1      | 0.13%   |
| Micron/Crucial Technology   | 1         | 1      | 0.13%   |
| LS                          | 1         | 1      | 0.13%   |
| Lexar                       | 1         | 1      | 0.13%   |
| KIOXIA-EXCERIA              | 1         | 1      | 0.13%   |
| KESU                        | 1         | 1      | 0.13%   |
| HS-SSD-E100                 | 1         | 1      | 0.13%   |
| FORESEE                     | 1         | 1      | 0.13%   |
| E535N                       | 1         | 1      | 0.13%   |
| DragonDiamond               | 1         | 1      | 0.13%   |
| BUFFALO                     | 1         | 1      | 0.13%   |
| ASMT                        | 1         | 1      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                 | 23        | 2.96%   |
| Unknown MMC Card  64GB                 | 16        | 2.06%   |
| Seagate ST1000LM035-1RK172 1TB         | 13        | 1.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 13        | 1.67%   |
| Samsung NVMe SSD Drive 512GB           | 13        | 1.67%   |
| Sandisk NVMe SSD Drive 256GB           | 12        | 1.54%   |
| Toshiba MQ04ABF100 1TB                 | 10        | 1.29%   |
| Toshiba MQ01ABD100 1TB                 | 10        | 1.29%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 10        | 1.29%   |
| Kingston SA400S37240G 240GB SSD        | 9         | 1.16%   |
| Toshiba MQ01ABF050 500GB               | 8         | 1.03%   |
| Unknown MMC Card  128GB                | 7         | 0.9%    |
| Seagate ST9500325AS 500GB              | 7         | 0.9%    |
| Sandisk NVMe SSD Drive 512GB           | 7         | 0.9%    |
| Samsung SSD 860 EVO 500GB              | 6         | 0.77%   |
| Kingston SA400S37120G 120GB SSD        | 6         | 0.77%   |
| Crucial CT240BX500SSD1 240GB           | 6         | 0.77%   |
| Samsung SSD 850 EVO 500GB              | 5         | 0.64%   |
| Kingston SA400S37480G 480GB SSD        | 5         | 0.64%   |
| Intel NVMe SSD Drive 512GB             | 5         | 0.64%   |
| HGST HTS721010A9E630 1TB               | 5         | 0.64%   |
| Crucial CT500MX500SSD1 500GB           | 5         | 0.64%   |
| WDC WD10SPZX-24Z10 1TB                 | 4         | 0.51%   |
| WDC WD10JPVX-22JC3T0 1TB               | 4         | 0.51%   |
| Unknown SD/MMC/MS PRO 64GB             | 4         | 0.51%   |
| SK Hynix NVMe SSD Drive 256GB          | 4         | 0.51%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 4         | 0.51%   |
| Seagate ST2000LM007-1R8174 2TB         | 4         | 0.51%   |
| Seagate ST1000LM049-2GH172 1TB         | 4         | 0.51%   |
| Samsung SSD 860 EVO 250GB              | 4         | 0.51%   |
| Samsung SSD 860 EVO 1TB                | 4         | 0.51%   |
| Samsung NVMe SSD Drive 500GB           | 4         | 0.51%   |
| Micron NVMe SSD Drive 512GB            | 4         | 0.51%   |
| Intel NVMe SSD Drive 1024GB            | 4         | 0.51%   |
| HGST HTS725050A7E630 500GB             | 4         | 0.51%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 3         | 0.39%   |
| Toshiba MK2555GSX 250GB                | 3         | 0.39%   |
| Toshiba MK2552GSX 250GB                | 3         | 0.39%   |
| SK Hynix NVMe SSD Drive 512GB          | 3         | 0.39%   |
| Seagate ST9500420AS 500GB              | 3         | 0.39%   |
| Seagate ST750LM022 HN-M750MBB 752GB    | 3         | 0.39%   |
| Seagate ST500LT012-9WS142 500GB        | 3         | 0.39%   |
| Seagate ST500LT012-1DG142 500GB        | 3         | 0.39%   |
| Seagate ST500LM021-1KJ152 500GB        | 3         | 0.39%   |
| Seagate ST1000LM014-1EJ164 1TB         | 3         | 0.39%   |
| Seagate Expansion+ 2TB                 | 3         | 0.39%   |
| SanDisk X400 M.2 2280 256GB SSD        | 3         | 0.39%   |
| Sandisk NVMe SSD Drive 1TB             | 3         | 0.39%   |
| Samsung SSD 850 EVO 250GB              | 3         | 0.39%   |
| Samsung SSD 840 EVO 250GB              | 3         | 0.39%   |
| Samsung NVMe SSD Drive 2TB             | 3         | 0.39%   |
| Samsung NVMe SSD Drive 1TB             | 3         | 0.39%   |
| PNY CS900 120GB SSD                    | 3         | 0.39%   |
| KIOXIA NVMe SSD Drive 512GB            | 3         | 0.39%   |
| Hitachi HTS725032A9A364 320GB          | 3         | 0.39%   |
| Hitachi HTS547575A9E384 752GB          | 3         | 0.39%   |
| HGST HTS541010A9E680 1TB               | 3         | 0.39%   |
| Crucial CT480BX500SSD1 480GB           | 3         | 0.39%   |
| Crucial CT1000MX500SSD1 1TB            | 3         | 0.39%   |
| Apple SSD SM0256F 256GB                | 3         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 96        | 110    | 35.29%  |
| WDC                 | 61        | 66     | 22.43%  |
| Toshiba             | 54        | 57     | 19.85%  |
| Hitachi             | 23        | 28     | 8.46%   |
| HGST                | 18        | 23     | 6.62%   |
| Samsung Electronics | 5         | 5      | 1.84%   |
| Fujitsu             | 5         | 6      | 1.84%   |
| Unknown             | 4         | 4      | 1.47%   |
| SABRENT             | 2         | 3      | 0.74%   |
| KESU                | 1         | 1      | 0.37%   |
| Intenso             | 1         | 1      | 0.37%   |
| ASMT                | 1         | 1      | 0.37%   |
| Apple               | 1         | 1      | 0.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 67        | 76     | 24.45%  |
| Crucial             | 29        | 34     | 10.58%  |
| SanDisk             | 28        | 33     | 10.22%  |
| Kingston            | 27        | 34     | 9.85%   |
| WDC                 | 14        | 18     | 5.11%   |
| Toshiba             | 13        | 13     | 4.74%   |
| A-DATA Technology   | 9         | 10     | 3.28%   |
| SK Hynix            | 8         | 8      | 2.92%   |
| Micron Technology   | 8         | 9      | 2.92%   |
| Intenso             | 6         | 6      | 2.19%   |
| Transcend           | 5         | 5      | 1.82%   |
| Intel               | 5         | 5      | 1.82%   |
| Apple               | 5         | 5      | 1.82%   |
| SPCC                | 4         | 6      | 1.46%   |
| PNY                 | 4         | 5      | 1.46%   |
| LITEONIT            | 4         | 5      | 1.46%   |
| GOODRAM             | 4         | 4      | 1.46%   |
| China               | 4         | 5      | 1.46%   |
| Patriot             | 3         | 3      | 1.09%   |
| Netac               | 3         | 3      | 1.09%   |
| Team                | 2         | 2      | 0.73%   |
| OCZ                 | 2         | 2      | 0.73%   |
| LITEON              | 2         | 2      | 0.73%   |
| KingSpec            | 2         | 2      | 0.73%   |
| Hewlett-Packard     | 2         | 2      | 0.73%   |
| BHT                 | 2         | 2      | 0.73%   |
| Verbatim            | 1         | 1      | 0.36%   |
| TO Exter            | 1         | 1      | 0.36%   |
| Teclast             | 1         | 1      | 0.36%   |
| Star                | 1         | 1      | 0.36%   |
| PLEXTOR             | 1         | 1      | 0.36%   |
| OSCOO               | 1         | 1      | 0.36%   |
| MidasForce          | 1         | 1      | 0.36%   |
| Lexar               | 1         | 1      | 0.36%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.36%   |
| HS-SSD-E100         | 1         | 1      | 0.36%   |
| FORESEE             | 1         | 1      | 0.36%   |
| BUFFALO             | 1         | 1      | 0.36%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 267       | 306    | 36.78%  |
| SSD     | 262       | 311    | 36.09%  |
| NVMe    | 132       | 173    | 18.18%  |
| MMC     | 56        | 66     | 7.71%   |
| Unknown | 9         | 11     | 1.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 494       | 603    | 70.37%  |
| NVMe | 131       | 171    | 18.66%  |
| MMC  | 56        | 66     | 7.98%   |
| SAS  | 21        | 27     | 2.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 359       | 421    | 68.38%  |
| 0.51-1.0   | 148       | 173    | 28.19%  |
| 1.01-2.0   | 15        | 18     | 2.86%   |
| 3.01-4.0   | 1         | 3      | 0.19%   |
| 2.01-3.0   | 1         | 1      | 0.19%   |
| 4.01-10.0  | 1         | 1      | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 226       | 35.42%  |
| 251-500        | 177       | 27.74%  |
| 501-1000       | 89        | 13.95%  |
| 51-100         | 59        | 9.25%   |
| 21-50          | 36        | 5.64%   |
| 1001-2000      | 19        | 2.98%   |
| 1-20           | 12        | 1.88%   |
| Unknown        | 9         | 1.41%   |
| 2001-3000      | 6         | 0.94%   |
| More than 3000 | 5         | 0.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 309       | 46.89%  |
| 21-50          | 178       | 27.01%  |
| 51-100         | 62        | 9.41%   |
| 101-250        | 58        | 8.8%    |
| 251-500        | 25        | 3.79%   |
| 501-1000       | 15        | 2.28%   |
| Unknown        | 9         | 1.37%   |
| More than 3000 | 2         | 0.3%    |
| 2001-3000      | 1         | 0.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Toshiba MQ02ABD100H 1TB            | 2         | 2      | 18.18%  |
| WDC WD10SPZX-75Z10T2 1TB           | 1         | 1      | 9.09%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 9.09%   |
| Seagate ST9500420AS 500GB          | 1         | 1      | 9.09%   |
| Seagate ST9200420ASG 200GB         | 1         | 1      | 9.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 9.09%   |
| Hitachi HTS725032A9A364 320GB      | 1         | 1      | 9.09%   |
| HGST HTS725050A7E630 500GB         | 1         | 1      | 9.09%   |
| HGST HTS545050A7E680 500GB         | 1         | 1      | 9.09%   |
| Hewlett-Packard SSD S600 240GB     | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| Seagate         | 3         | 3      | 27.27%  |
| WDC             | 2         | 2      | 18.18%  |
| Toshiba         | 2         | 2      | 18.18%  |
| HGST            | 2         | 2      | 18.18%  |
| Hitachi         | 1         | 1      | 9.09%   |
| Hewlett-Packard | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 30%     |
| WDC     | 2         | 2      | 20%     |
| Toshiba | 2         | 2      | 20%     |
| HGST    | 2         | 2      | 20%     |
| Hitachi | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 90.91%  |
| SSD  | 1         | 1      | 9.09%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                 | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| SanDisk SSD i100 24GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 566       | 774    | 87.62%  |
| Works    | 68        | 81     | 10.53%  |
| Malfunc  | 11        | 11     | 1.7%    |
| Failed   | 1         | 1      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 474       | 68.4%   |
| AMD                              | 79        | 11.4%   |
| Samsung Electronics              | 51        | 7.36%   |
| Sandisk                          | 29        | 4.18%   |
| SK Hynix                         | 10        | 1.44%   |
| Micron Technology                | 7         | 1.01%   |
| KIOXIA                           | 7         | 1.01%   |
| Toshiba America Info Systems     | 5         | 0.72%   |
| Kingston Technology Company      | 4         | 0.58%   |
| ADATA Technology                 | 4         | 0.58%   |
| Phison Electronics               | 3         | 0.43%   |
| Nvidia                           | 3         | 0.43%   |
| Marvell Technology Group         | 3         | 0.43%   |
| Lite-On Technology               | 3         | 0.43%   |
| Realtek Semiconductor            | 2         | 0.29%   |
| Micron/Crucial Technology        | 2         | 0.29%   |
| ASMedia Technology               | 2         | 0.29%   |
| Yangtze Memory Technologies      | 1         | 0.14%   |
| VIA Technologies                 | 1         | 0.14%   |
| Silicon Motion                   | 1         | 0.14%   |
| Silicon Integrated Systems [SiS] | 1         | 0.14%   |
| Apple                            | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 64        | 8.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 60        | 8.02%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 52        | 6.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 45        | 6.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 44        | 5.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 35        | 4.68%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 24        | 3.21%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 24        | 3.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 22        | 2.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 21        | 2.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 20        | 2.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 20        | 2.67%   |
| Samsung NVMe SSD Controller 980                                                  | 13        | 1.74%   |
| Intel Volume Management Device NVMe RAID Controller                              | 13        | 1.74%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 12        | 1.6%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 12        | 1.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 12        | 1.6%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 12        | 1.6%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 11        | 1.47%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 11        | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 10        | 1.34%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 9         | 1.2%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 9         | 1.2%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 9         | 1.2%    |
| Intel SSD 660P Series                                                            | 8         | 1.07%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 7         | 0.94%   |
| Micron Non-Volatile memory controller                                            | 7         | 0.94%   |
| KIOXIA Non-Volatile memory controller                                            | 7         | 0.94%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 7         | 0.94%   |
| Intel Comet Lake SATA AHCI Controller                                            | 7         | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 0.8%    |
| SK Hynix BC501 NVMe Solid State Drive                                            | 5         | 0.67%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 5         | 0.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5         | 0.67%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 4         | 0.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 0.53%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 4         | 0.53%   |
| SK Hynix BC511                                                                   | 3         | 0.4%    |
| Sandisk Non-Volatile memory controller                                           | 3         | 0.4%    |
| Samsung Apple PCIe SSD                                                           | 3         | 0.4%    |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 0.4%    |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 3         | 0.4%    |
| Lite-On Non-Volatile memory controller                                           | 3         | 0.4%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 0.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3         | 0.4%    |
| AMD FCH IDE Controller                                                           | 3         | 0.4%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2         | 0.27%   |
| SK Hynix Gold P31 SSD                                                            | 2         | 0.27%   |
| Sandisk PC SN520 NVMe SSD                                                        | 2         | 0.27%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 0.27%   |
| Realtek Realtek Non-Volatile memory controller                                   | 2         | 0.27%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.27%   |
| Intel SSD 600P Series                                                            | 2         | 0.27%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 0.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.27%   |
| Intel Non-Volatile memory controller                                             | 2         | 0.27%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 2         | 0.27%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]    | 2         | 0.27%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile       | 2         | 0.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 485       | 67.08%  |
| NVMe | 131       | 18.12%  |
| RAID | 62        | 8.58%   |
| IDE  | 45        | 6.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 535       | 84.65%  |
| AMD    | 97        | 15.35%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 12        | 1.9%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 11        | 1.74%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 1.58%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 10        | 1.58%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 1.42%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 9         | 1.42%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 8         | 1.27%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 1.27%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 1.27%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 8         | 1.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 1.27%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 1.11%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 1.11%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 1.11%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 7         | 1.11%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 6         | 0.95%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 6         | 0.95%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 5         | 0.79%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 0.79%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 5         | 0.79%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 5         | 0.79%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 5         | 0.79%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.79%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 5         | 0.79%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 5         | 0.79%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 5         | 0.79%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 5         | 0.79%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 0.79%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 0.79%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 4         | 0.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.63%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 4         | 0.63%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 0.63%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 4         | 0.63%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 0.63%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 4         | 0.63%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 4         | 0.63%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 4         | 0.63%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 4         | 0.63%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 4         | 0.63%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 4         | 0.63%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 0.63%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 4         | 0.63%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 4         | 0.63%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 4         | 0.63%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 3         | 0.47%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.47%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 3         | 0.47%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 0.47%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 0.47%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 3         | 0.47%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 3         | 0.47%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 3         | 0.47%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 0.47%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 3         | 0.47%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 3         | 0.47%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 3         | 0.47%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.47%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 3         | 0.47%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 3         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 170       | 26.9%   |
| Intel Core i7                        | 121       | 19.15%  |
| Intel Core i3                        | 67        | 10.6%   |
| Intel Celeron                        | 44        | 6.96%   |
| Intel Core 2 Duo                     | 41        | 6.49%   |
| Intel Pentium                        | 28        | 4.43%   |
| Other                                | 24        | 3.8%    |
| AMD Ryzen 5                          | 23        | 3.64%   |
| Intel Atom                           | 21        | 3.32%   |
| AMD Ryzen 7                          | 13        | 2.06%   |
| AMD A6                               | 11        | 1.74%   |
| AMD A10                              | 8         | 1.27%   |
| AMD E1                               | 6         | 0.95%   |
| AMD E                                | 5         | 0.79%   |
| Intel Pentium Dual                   | 4         | 0.63%   |
| Intel Core m5                        | 4         | 0.63%   |
| AMD Ryzen 3                          | 4         | 0.63%   |
| AMD A8                               | 4         | 0.63%   |
| Intel Pentium Dual-Core              | 3         | 0.47%   |
| AMD A4                               | 3         | 0.47%   |
| Intel Pentium Silver                 | 2         | 0.32%   |
| Intel Core M                         | 2         | 0.32%   |
| Intel Celeron Dual-Core              | 2         | 0.32%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 2         | 0.32%   |
| AMD FX                               | 2         | 0.32%   |
| AMD E2                               | 2         | 0.32%   |
| Intel Xeon                           | 1         | 0.16%   |
| Intel Genuine                        | 1         | 0.16%   |
| Intel Core i9                        | 1         | 0.16%   |
| Intel Core 2                         | 1         | 0.16%   |
| Intel Celeron M                      | 1         | 0.16%   |
| AMD Turion II                        | 1         | 0.16%   |
| AMD Turion 64 X2 Mobile              | 1         | 0.16%   |
| AMD Turion 64 Mobile                 | 1         | 0.16%   |
| AMD Sempron                          | 1         | 0.16%   |
| AMD Ryzen 9                          | 1         | 0.16%   |
| AMD Ryzen 7 PRO                      | 1         | 0.16%   |
| AMD Phenom II                        | 1         | 0.16%   |
| AMD C-60                             | 1         | 0.16%   |
| AMD Athlon X2                        | 1         | 0.16%   |
| AMD Athlon II                        | 1         | 0.16%   |
| AMD Athlon                           | 1         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 380       | 60.13%  |
| 4      | 202       | 31.96%  |
| 6      | 25        | 3.96%   |
| 8      | 17        | 2.69%   |
| 1      | 6         | 0.95%   |
| 10     | 1         | 0.16%   |
| 3      | 1         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 632       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 434       | 68.67%  |
| 1      | 198       | 31.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 632       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 62        | 9.72%   |
| 0x306a9    | 53        | 8.31%   |
| Unknown    | 41        | 6.43%   |
| 0x40651    | 38        | 5.96%   |
| 0x406e3    | 27        | 4.23%   |
| 0x806ea    | 24        | 3.76%   |
| 0x20655    | 23        | 3.61%   |
| 0x306d4    | 21        | 3.29%   |
| 0x1067a    | 21        | 3.29%   |
| 0x806ec    | 19        | 2.98%   |
| 0x806c1    | 16        | 2.51%   |
| 0x306c3    | 16        | 2.51%   |
| 0x806e9    | 15        | 2.35%   |
| 0x406c4    | 15        | 2.35%   |
| 0x30678    | 15        | 2.35%   |
| 0x906ea    | 12        | 1.88%   |
| 0x10676    | 12        | 1.88%   |
| 0x08108102 | 12        | 1.88%   |
| 0x906e9    | 11        | 1.72%   |
| 0x706e5    | 11        | 1.72%   |
| 0x506c9    | 11        | 1.72%   |
| 0x6fd      | 10        | 1.57%   |
| 0x20652    | 10        | 1.57%   |
| 0x706a8    | 9         | 1.41%   |
| 0x07030105 | 9         | 1.41%   |
| 0x406c3    | 8         | 1.25%   |
| 0x08108109 | 8         | 1.25%   |
| 0x08600106 | 7         | 1.1%    |
| 0xa0652    | 6         | 0.94%   |
| 0x6fb      | 6         | 0.94%   |
| 0x05000119 | 6         | 0.94%   |
| 0x806eb    | 4         | 0.63%   |
| 0x506e3    | 4         | 0.63%   |
| 0x106e5    | 4         | 0.63%   |
| 0x07030106 | 4         | 0.63%   |
| 0x06006704 | 4         | 0.63%   |
| 0x806d1    | 3         | 0.47%   |
| 0x706a1    | 3         | 0.47%   |
| 0x0a50000c | 3         | 0.47%   |
| 0x08608103 | 3         | 0.47%   |
| 0x08600104 | 3         | 0.47%   |
| 0x08600103 | 3         | 0.47%   |
| 0x0700010f | 3         | 0.47%   |
| 0x06006705 | 3         | 0.47%   |
| 0x0600611a | 3         | 0.47%   |
| 0x06003106 | 3         | 0.47%   |
| 0x03000027 | 3         | 0.47%   |
| 0x02000057 | 3         | 0.47%   |
| 0x010000c8 | 3         | 0.47%   |
| 0x6fa      | 2         | 0.31%   |
| 0x6f6      | 2         | 0.31%   |
| 0x40661    | 2         | 0.31%   |
| 0x30673    | 2         | 0.31%   |
| 0x30661    | 2         | 0.31%   |
| 0x106ca    | 2         | 0.31%   |
| 0x06001119 | 2         | 0.31%   |
| 0xa0655    | 1         | 0.16%   |
| 0x906ed    | 1         | 0.16%   |
| 0x906c0    | 1         | 0.16%   |
| 0x506ca    | 1         | 0.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 99        | 15.66%  |
| SandyBridge     | 64        | 10.13%  |
| Haswell         | 59        | 9.34%   |
| IvyBridge       | 55        | 8.7%    |
| Silvermont      | 41        | 6.49%   |
| Westmere        | 34        | 5.38%   |
| Skylake         | 33        | 5.22%   |
| Penryn          | 33        | 5.22%   |
| Zen+            | 21        | 3.32%   |
| Core            | 21        | 3.32%   |
| Broadwell       | 21        | 3.32%   |
| TigerLake       | 18        | 2.85%   |
| IceLake         | 15        | 2.37%   |
| Puma            | 14        | 2.22%   |
| Zen 2           | 13        | 2.06%   |
| Goldmont plus   | 12        | 1.9%    |
| Goldmont        | 12        | 1.9%    |
| Excavator       | 11        | 1.74%   |
| CometLake       | 8         | 1.27%   |
| Bobcat          | 7         | 1.11%   |
| Zen 3           | 5         | 0.79%   |
| Nehalem         | 5         | 0.79%   |
| K8 & K10 hybrid | 4         | 0.63%   |
| Jaguar          | 4         | 0.63%   |
| Bonnell         | 4         | 0.63%   |
| Unknown         | 4         | 0.63%   |
| Steamroller     | 3         | 0.47%   |
| Piledriver      | 3         | 0.47%   |
| K10 Llano       | 3         | 0.47%   |
| K10             | 3         | 0.47%   |
| K8 Hammer       | 2         | 0.32%   |
| Tremont         | 1         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 486       | 63.7%   |
| Nvidia                           | 146       | 19.13%  |
| AMD                              | 130       | 17.04%  |
| Silicon Integrated Systems [SiS] | 1         | 0.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 56        | 7.08%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 55        | 6.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 40        | 5.06%   |
| Intel Core Processor Integrated Graphics Controller                                      | 30        | 3.79%   |
| Intel UHD Graphics 620                                                                   | 25        | 3.16%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 23        | 2.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 23        | 2.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 21        | 2.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 18        | 2.28%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 17        | 2.15%   |
| Intel HD Graphics 620                                                                    | 16        | 2.02%   |
| Intel HD Graphics 5500                                                                   | 16        | 2.02%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 15        | 1.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 1.77%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 1.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 13        | 1.64%   |
| AMD Renoir                                                                               | 13        | 1.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 12        | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 12        | 1.52%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 11        | 1.39%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 11        | 1.39%   |
| Intel HD Graphics 630                                                                    | 11        | 1.39%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 1.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 1.26%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 9         | 1.14%   |
| Intel HD Graphics 500                                                                    | 9         | 1.14%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 9         | 1.14%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 0.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 7         | 0.88%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 6         | 0.76%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 0.76%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 0.63%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 4         | 0.51%   |
| Intel HD Graphics 530                                                                    | 4         | 0.51%   |
| Intel HD Graphics 515                                                                    | 4         | 0.51%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 0.51%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 4         | 0.51%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 0.51%   |
| AMD Lucienne                                                                             | 4         | 0.51%   |
| AMD Cezanne                                                                              | 4         | 0.51%   |
| Nvidia TU117M                                                                            | 3         | 0.38%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 3         | 0.38%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.38%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.38%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.38%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.38%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 3         | 0.38%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 0.38%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 3         | 0.38%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.38%   |
| Intel Tiger Lake UHD Graphics                                                            | 3         | 0.38%   |
| Intel HD Graphics 5300                                                                   | 3         | 0.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.38%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3         | 0.38%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.38%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 3         | 0.38%   |
| AMD RS780M [Mobility Radeon HD 3200]                                                     | 3         | 0.38%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 3         | 0.38%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 2         | 0.25%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 365       | 57.75%  |
| Intel + Nvidia | 102       | 16.14%  |
| 1 x AMD        | 88        | 13.92%  |
| 1 x Nvidia     | 33        | 5.22%   |
| Intel + AMD    | 19        | 3.01%   |
| 2 x AMD        | 13        | 2.06%   |
| AMD + Nvidia   | 10        | 1.58%   |
| 2 x Nvidia     | 1         | 0.16%   |
| 1 x SiS        | 1         | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 543       | 85.92%  |
| Proprietary | 81        | 12.82%  |
| Unknown     | 8         | 1.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 414       | 64.79%  |
| 0.01-0.5   | 70        | 10.95%  |
| 1.01-2.0   | 63        | 9.86%   |
| 0.51-1.0   | 46        | 7.2%    |
| 3.01-4.0   | 23        | 3.6%    |
| 5.01-6.0   | 11        | 1.72%   |
| 7.01-8.0   | 8         | 1.25%   |
| 2.01-3.0   | 3         | 0.47%   |
| 8.01-16.0  | 1         | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 129       | 19.23%  |
| Chimei Innolux          | 103       | 15.35%  |
| LG Display              | 96        | 14.31%  |
| Samsung Electronics     | 92        | 13.71%  |
| BOE                     | 77        | 11.48%  |
| Chi Mei Optoelectronics | 25        | 3.73%   |
| Apple                   | 16        | 2.38%   |
| Sharp                   | 15        | 2.24%   |
| Dell                    | 13        | 1.94%   |
| PANDA                   | 12        | 1.79%   |
| Lenovo                  | 12        | 1.79%   |
| Goldstar                | 9         | 1.34%   |
| LG Philips              | 8         | 1.19%   |
| LGD                     | 5         | 0.75%   |
| Vizio                   | 4         | 0.6%    |
| Acer                    | 4         | 0.6%    |
| Philips                 | 3         | 0.45%   |
| InfoVision              | 3         | 0.45%   |
| Hewlett-Packard         | 3         | 0.45%   |
| CPT                     | 3         | 0.45%   |
| BenQ                    | 3         | 0.45%   |
| AOC                     | 3         | 0.45%   |
| Sony                    | 2         | 0.3%    |
| Quanta Display          | 2         | 0.3%    |
| KDC                     | 2         | 0.3%    |
| Iiyama                  | 2         | 0.3%    |
| HannStar                | 2         | 0.3%    |
| BOE Technology Group    | 2         | 0.3%    |
| VIE                     | 1         | 0.15%   |
| Unknown                 | 1         | 0.15%   |
| Toshiba                 | 1         | 0.15%   |
| SLD                     | 1         | 0.15%   |
| Sceptre Tech            | 1         | 0.15%   |
| Sanyo                   | 1         | 0.15%   |
| Panasonic               | 1         | 0.15%   |
| MStar                   | 1         | 0.15%   |
| KDB                     | 1         | 0.15%   |
| ITE                     | 1         | 0.15%   |
| InnoLux Display         | 1         | 0.15%   |
| HSI                     | 1         | 0.15%   |
| HRG                     | 1         | 0.15%   |
| HIC                     | 1         | 0.15%   |
| Gateway                 | 1         | 0.15%   |
| Fujitsu Siemens         | 1         | 0.15%   |
| ELD                     | 1         | 0.15%   |
| Eizo                    | 1         | 0.15%   |
| Belinea                 | 1         | 0.15%   |
| Ancor Communications    | 1         | 0.15%   |
| Unknown                 | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 7         | 1.04%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 0.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 0.89%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 5         | 0.74%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 5         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 5         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 5         | 0.74%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.74%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 5         | 0.74%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 4         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 4         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x194mm 15.5-inch          | 4         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 4         | 0.59%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 4         | 0.59%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 4         | 0.59%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 4         | 0.59%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 4         | 0.59%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 3         | 0.44%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 3         | 0.44%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.44%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 293x165mm 13.2-inch    | 3         | 0.44%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 3         | 0.44%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch          | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 3         | 0.44%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 350x190mm 15.7-inch | 3         | 0.44%   |
| Chi Mei Optoelectronics LCD Monitor CMO1590 1366x768 344x194mm 15.5-inch | 3         | 0.44%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 0.44%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 3         | 0.44%   |
| BOE LCD Monitor BOE0653 1920x1080 309x173mm 13.9-inch                    | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO113D 1920x1080 309x173mm 13.9-inch           | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 3         | 0.44%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch     | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SEC3959 1366x768 344x194mm 15.5-inch     | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch     | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch     | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch    | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch     | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch     | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch    | 2         | 0.3%    |
| LGD LCD Monitor 1920x1080                                                | 2         | 0.3%    |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 2         | 0.3%    |
| LG Display LCD Monitor LGD0493 1366x768 344x194mm 15.5-inch              | 2         | 0.3%    |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 2         | 0.3%    |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch              | 2         | 0.3%    |
| LG Display LCD Monitor LGD0360 1600x900 294x166mm 13.3-inch              | 2         | 0.3%    |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch              | 2         | 0.3%    |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 2         | 0.3%    |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch              | 2         | 0.3%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 2         | 0.3%    |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 2         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 268       | 40.85%  |
| 1920x1080 (FHD)    | 215       | 32.77%  |
| 1600x900 (HD+)     | 49        | 7.47%   |
| 1280x800 (WXGA)    | 33        | 5.03%   |
| 3840x2160 (4K)     | 17        | 2.59%   |
| 1440x900 (WXGA+)   | 10        | 1.52%   |
| 2560x1440 (QHD)    | 7         | 1.07%   |
| Unknown            | 6         | 0.91%   |
| 2560x1600          | 5         | 0.76%   |
| 3200x1800 (QHD+)   | 4         | 0.61%   |
| 1920x1200 (WUXGA)  | 4         | 0.61%   |
| 1680x1050 (WSXGA+) | 4         | 0.61%   |
| 1280x1024 (SXGA)   | 4         | 0.61%   |
| 3840x2400          | 3         | 0.46%   |
| 2880x1800          | 3         | 0.46%   |
| 2256x1504          | 3         | 0.46%   |
| 2160x1440          | 3         | 0.46%   |
| 1360x768           | 3         | 0.46%   |
| 1024x600           | 3         | 0.46%   |
| 5760x1080          | 2         | 0.3%    |
| 1920x515           | 2         | 0.3%    |
| 4480x1600          | 1         | 0.15%   |
| 3840x1200          | 1         | 0.15%   |
| 3840x1080          | 1         | 0.15%   |
| 3600x1080          | 1         | 0.15%   |
| 2560x1080          | 1         | 0.15%   |
| 1920x540           | 1         | 0.15%   |
| 1920x1280          | 1         | 0.15%   |
| 1680x945           | 1         | 0.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 286       | 42.94%  |
| 13      | 105       | 15.77%  |
| 14      | 75        | 11.26%  |
| 17      | 60        | 9.01%   |
| 12      | 22        | 3.3%    |
| Unknown | 18        | 2.7%    |
| 11      | 17        | 2.55%   |
| 24      | 14        | 2.1%    |
| 27      | 11        | 1.65%   |
| 23      | 8         | 1.2%    |
| 18      | 8         | 1.2%    |
| 31      | 5         | 0.75%   |
| 21      | 5         | 0.75%   |
| 20      | 4         | 0.6%    |
| 10      | 4         | 0.6%    |
| 16      | 3         | 0.45%   |
| 72      | 2         | 0.3%    |
| 34      | 2         | 0.3%    |
| 25      | 2         | 0.3%    |
| 19      | 2         | 0.3%    |
| 84      | 1         | 0.15%   |
| 74      | 1         | 0.15%   |
| 64      | 1         | 0.15%   |
| 54      | 1         | 0.15%   |
| 52      | 1         | 0.15%   |
| 49      | 1         | 0.15%   |
| 48      | 1         | 0.15%   |
| 47      | 1         | 0.15%   |
| 46      | 1         | 0.15%   |
| 40      | 1         | 0.15%   |
| 37      | 1         | 0.15%   |
| 32      | 1         | 0.15%   |
| 26      | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 406       | 61.24%  |
| 201-300     | 95        | 14.33%  |
| 351-400     | 70        | 10.56%  |
| 501-600     | 31        | 4.68%   |
| 401-500     | 19        | 2.87%   |
| Unknown     | 18        | 2.71%   |
| 601-700     | 8         | 1.21%   |
| 1001-1500   | 7         | 1.06%   |
| 1501-2000   | 4         | 0.6%    |
| 701-800     | 3         | 0.45%   |
| 801-900     | 2         | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 522       | 85.29%  |
| 16/10   | 60        | 9.8%    |
| Unknown | 13        | 2.12%   |
| 3/2     | 8         | 1.31%   |
| 5/4     | 3         | 0.49%   |
| 4/3     | 2         | 0.33%   |
| 3.73    | 2         | 0.33%   |
| 21/9    | 2         | 0.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 287       | 43.03%  |
| 81-90          | 140       | 20.99%  |
| 121-130        | 50        | 7.5%    |
| 71-80          | 40        | 6%      |
| 201-250        | 25        | 3.75%   |
| 61-70          | 21        | 3.15%   |
| Unknown        | 18        | 2.7%    |
| 51-60          | 17        | 2.55%   |
| 301-350        | 12        | 1.8%    |
| 141-150        | 10        | 1.5%    |
| More than 1000 | 9         | 1.35%   |
| 351-500        | 8         | 1.2%    |
| 151-200        | 8         | 1.2%    |
| 131-140        | 7         | 1.05%   |
| 41-50          | 4         | 0.6%    |
| 501-1000       | 4         | 0.6%    |
| 251-300        | 3         | 0.45%   |
| 111-120        | 2         | 0.3%    |
| 91-100         | 2         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 281       | 42.51%  |
| 121-160       | 205       | 31.01%  |
| 51-100        | 96        | 14.52%  |
| 161-240       | 36        | 5.45%   |
| Unknown       | 18        | 2.72%   |
| More than 240 | 13        | 1.97%   |
| 1-50          | 12        | 1.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 550       | 86.34%  |
| 2     | 77        | 12.09%  |
| 0     | 7         | 1.1%    |
| 3     | 2         | 0.31%   |
| 4     | 1         | 0.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 325       | 31.93%  |
| Intel                             | 296       | 29.08%  |
| Qualcomm Atheros                  | 173       | 16.99%  |
| Broadcom                          | 82        | 8.06%   |
| Broadcom Limited                  | 28        | 2.75%   |
| ASIX Electronics                  | 12        | 1.18%   |
| Marvell Technology Group          | 11        | 1.08%   |
| Ralink                            | 10        | 0.98%   |
| Dell                              | 9         | 0.88%   |
| Xiaomi                            | 7         | 0.69%   |
| Samsung Electronics               | 7         | 0.69%   |
| Ralink Technology                 | 6         | 0.59%   |
| DisplayLink                       | 5         | 0.49%   |
| TP-Link                           | 4         | 0.39%   |
| Huawei Technologies               | 4         | 0.39%   |
| Hewlett-Packard                   | 4         | 0.39%   |
| Sierra Wireless                   | 3         | 0.29%   |
| MEDIATEK                          | 3         | 0.29%   |
| JMicron Technology                | 3         | 0.29%   |
| T & A Mobile Phones               | 2         | 0.2%    |
| Qualcomm                          | 2         | 0.2%    |
| Nvidia                            | 2         | 0.2%    |
| Ericsson Business Mobile Networks | 2         | 0.2%    |
| Edimax Technology                 | 2         | 0.2%    |
| D-Link System                     | 2         | 0.2%    |
| ZyXEL Communications              | 1         | 0.1%    |
| Silicon Integrated Systems [SiS]  | 1         | 0.1%    |
| Qualcomm Atheros Communications   | 1         | 0.1%    |
| OPPO Electronics                  | 1         | 0.1%    |
| OnePlus                           | 1         | 0.1%    |
| Novatel Wireless                  | 1         | 0.1%    |
| NetGear                           | 1         | 0.1%    |
| Motorola PCS                      | 1         | 0.1%    |
| Motorola BCS                      | 1         | 0.1%    |
| Linksys                           | 1         | 0.1%    |
| Lenovo                            | 1         | 0.1%    |
| ICS Advent                        | 1         | 0.1%    |
| Exar                              | 1         | 0.1%    |
| DJI Technology                    | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 188       | 15.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 78        | 6.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 46        | 3.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 33        | 2.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 27        | 2.24%   |
| Intel Wireless 7260                                                     | 24        | 1.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 23        | 1.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 22        | 1.83%   |
| Intel Wireless 8260                                                     | 21        | 1.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 20        | 1.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 19        | 1.58%   |
| Intel Wireless 8265 / 8275                                              | 19        | 1.58%   |
| Intel Wireless 7265                                                     | 19        | 1.58%   |
| Broadcom BCM43142 802.11b/g/n                                           | 19        | 1.58%   |
| Intel Wi-Fi 6 AX200                                                     | 17        | 1.41%   |
| Intel Wi-Fi 6 AX201                                                     | 14        | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 13        | 1.08%   |
| Intel Wireless 3165                                                     | 13        | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 13        | 1.08%   |
| Intel Ethernet Connection I219-LM                                       | 12        | 1%      |
| Intel Cannon Lake PCH CNVi WiFi                                         | 12        | 1%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 11        | 0.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 11        | 0.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 11        | 0.91%   |
| Intel WiFi Link 5100                                                    | 11        | 0.91%   |
| ASIX AX88179 Gigabit Ethernet                                           | 11        | 0.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 0.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 0.75%   |
| Intel Centrino Ultimate-N 6300                                          | 9         | 0.75%   |
| Intel 82577LM Gigabit Network Connection                                | 9         | 0.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 9         | 0.75%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 8         | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 0.66%   |
| Intel Ethernet Connection I218-LM                                       | 8         | 0.66%   |
| Intel Centrino Advanced-N 6200                                          | 8         | 0.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 0.66%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 6         | 0.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 0.5%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 6         | 0.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 6         | 0.5%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 0.5%    |
| Intel Centrino Wireless-N 2230                                          | 6         | 0.5%    |
| Intel Centrino Advanced-N 6235                                          | 6         | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                           | 5         | 0.42%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 5         | 0.42%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 0.42%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 0.42%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 0.42%   |
| Intel 82566MM Gigabit Network Connection                                | 5         | 0.42%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 0.33%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 0.33%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 0.33%   |
| Realtek 802.11ac NIC                                                    | 4         | 0.33%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 4         | 0.33%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 4         | 0.33%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 4         | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 280       | 43.75%  |
| Qualcomm Atheros                | 147       | 22.97%  |
| Realtek Semiconductor           | 97        | 15.16%  |
| Broadcom                        | 60        | 9.38%   |
| Broadcom Limited                | 18        | 2.81%   |
| Ralink                          | 10        | 1.56%   |
| Ralink Technology               | 6         | 0.94%   |
| Dell                            | 5         | 0.78%   |
| Sierra Wireless                 | 3         | 0.47%   |
| TP-Link                         | 2         | 0.31%   |
| MEDIATEK                        | 2         | 0.31%   |
| Edimax Technology               | 2         | 0.31%   |
| D-Link System                   | 2         | 0.31%   |
| ZyXEL Communications            | 1         | 0.16%   |
| Qualcomm Atheros Communications | 1         | 0.16%   |
| Qualcomm                        | 1         | 0.16%   |
| NetGear                         | 1         | 0.16%   |
| Linksys                         | 1         | 0.16%   |
| Hewlett-Packard                 | 1         | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 46        | 7.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 27        | 4.19%   |
| Intel Wireless 7260                                                     | 24        | 3.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 23        | 3.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 22        | 3.41%   |
| Intel Wireless 8260                                                     | 21        | 3.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 20        | 3.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 19        | 2.95%   |
| Intel Wireless 8265 / 8275                                              | 19        | 2.95%   |
| Intel Wireless 7265                                                     | 19        | 2.95%   |
| Broadcom BCM43142 802.11b/g/n                                           | 19        | 2.95%   |
| Intel Wi-Fi 6 AX200                                                     | 17        | 2.64%   |
| Intel Wi-Fi 6 AX201                                                     | 14        | 2.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 13        | 2.02%   |
| Intel Wireless 3165                                                     | 13        | 2.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 13        | 2.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 12        | 1.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 11        | 1.71%   |
| Intel WiFi Link 5100                                                    | 11        | 1.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 1.4%    |
| Intel Centrino Ultimate-N 6300                                          | 9         | 1.4%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 8         | 1.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 1.24%   |
| Intel Centrino Advanced-N 6200                                          | 8         | 1.24%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.24%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 1.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 0.93%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 6         | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.93%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 6         | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 0.93%   |
| Intel Centrino Wireless-N 2230                                          | 6         | 0.93%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 0.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 0.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 0.62%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 0.62%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 0.62%   |
| Realtek 802.11ac NIC                                                    | 4         | 0.62%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.62%   |
| Intel Wireless 3160                                                     | 4         | 0.62%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.62%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 0.62%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 4         | 0.62%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 0.62%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 0.62%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 4         | 0.62%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 4         | 0.62%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3         | 0.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 0.47%   |
| Intel Ultimate N WiFi Link 5300                                         | 3         | 0.47%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 0.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.47%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 3         | 0.47%   |
| Dell Wireless 5570 HSPA+ (42Mbps) Mobile Broadband Card                 | 3         | 0.47%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 0.47%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 3         | 0.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 284       | 52.4%   |
| Intel                            | 111       | 20.48%  |
| Qualcomm Atheros                 | 43        | 7.93%   |
| Broadcom                         | 30        | 5.54%   |
| Broadcom Limited                 | 12        | 2.21%   |
| ASIX Electronics                 | 12        | 2.21%   |
| Marvell Technology Group         | 11        | 2.03%   |
| Xiaomi                           | 7         | 1.29%   |
| Samsung Electronics              | 6         | 1.11%   |
| DisplayLink                      | 5         | 0.92%   |
| JMicron Technology               | 3         | 0.55%   |
| Huawei Technologies              | 3         | 0.55%   |
| TP-Link                          | 2         | 0.37%   |
| Nvidia                           | 2         | 0.37%   |
| Silicon Integrated Systems [SiS] | 1         | 0.18%   |
| Qualcomm                         | 1         | 0.18%   |
| OPPO Electronics                 | 1         | 0.18%   |
| OnePlus                          | 1         | 0.18%   |
| Novatel Wireless                 | 1         | 0.18%   |
| Motorola PCS                     | 1         | 0.18%   |
| Motorola BCS                     | 1         | 0.18%   |
| MediaTek                         | 1         | 0.18%   |
| Lenovo                           | 1         | 0.18%   |
| ICS Advent                       | 1         | 0.18%   |
| Hewlett-Packard                  | 1         | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 188       | 34.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 78        | 14.31%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 33        | 6.06%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 2.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 2.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 11        | 2.02%   |
| ASIX AX88179 Gigabit Ethernet                                     | 11        | 2.02%   |
| Intel 82577LM Gigabit Network Connection                          | 9         | 1.65%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 9         | 1.65%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 1.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6         | 1.1%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.92%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 5         | 0.92%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.92%   |
| Intel 82566MM Gigabit Network Connection                          | 5         | 0.92%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 0.73%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.73%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 4         | 0.73%   |
| Intel Ethernet Connection I219-V                                  | 4         | 0.73%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.73%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.73%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.73%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.73%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 0.73%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.55%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.55%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.55%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 3         | 0.55%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.55%   |
| Intel 82577LC Gigabit Network Connection                          | 3         | 0.55%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 3         | 0.55%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 2         | 0.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.37%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.37%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.37%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.37%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.37%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 2         | 0.37%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.37%   |
| Intel Ethernet controller                                         | 2         | 0.37%   |
| Intel Ethernet Connection I218-V                                  | 2         | 0.37%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.37%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.37%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.37%   |
| Intel 82562GT 10/100 Network Connection                           | 2         | 0.37%   |
| Huawei E353/E3131                                                 | 2         | 0.37%   |
| DisplayLink USB-C Dual-4K Dock                                    | 2         | 0.37%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.37%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 0.37%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 0.37%   |
| Broadcom Limited NetLink BCM5784M Gigabit Ethernet PCIe           | 2         | 0.37%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 2         | 0.37%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 2         | 0.37%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.18%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.18%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.18%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.18%   |
| Qualcomm FP3                                                      | 1         | 0.18%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 611       | 53.46%  |
| Ethernet | 518       | 45.32%  |
| Modem    | 12        | 1.05%   |
| Unknown  | 2         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 586       | 55.49%  |
| Ethernet | 467       | 44.22%  |
| Modem    | 2         | 0.19%   |
| Unknown  | 1         | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 474       | 75%     |
| 1     | 130       | 20.57%  |
| 0     | 24        | 3.8%    |
| 3     | 4         | 0.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 453       | 71.11%  |
| Yes  | 184       | 28.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 194       | 40.42%  |
| Realtek Semiconductor           | 51        | 10.63%  |
| Qualcomm Atheros Communications | 51        | 10.63%  |
| Broadcom                        | 33        | 6.88%   |
| Lite-On Technology              | 22        | 4.58%   |
| IMC Networks                    | 22        | 4.58%   |
| Foxconn / Hon Hai               | 22        | 4.58%   |
| Dell                            | 14        | 2.92%   |
| Apple                           | 14        | 2.92%   |
| Toshiba                         | 10        | 2.08%   |
| Qualcomm Atheros                | 9         | 1.88%   |
| Hewlett-Packard                 | 9         | 1.88%   |
| Cambridge Silicon Radio         | 7         | 1.46%   |
| Ralink                          | 6         | 1.25%   |
| Foxconn International           | 4         | 0.83%   |
| ASUSTek Computer                | 3         | 0.63%   |
| Alps Electric                   | 3         | 0.63%   |
| Realtek                         | 2         | 0.42%   |
| Integrated System Solution      | 2         | 0.42%   |
| MediaTek                        | 1         | 0.21%   |
| Askey Computer                  | 1         | 0.21%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 71        | 14.79%  |
| Intel Bluetooth wireless interface                                                  | 61        | 12.71%  |
| Realtek Bluetooth Radio                                                             | 35        | 7.29%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 32        | 6.67%   |
| Intel AX201 Bluetooth                                                               | 29        | 6.04%   |
| Intel AX200 Bluetooth                                                               | 17        | 3.54%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 13        | 2.71%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 13        | 2.71%   |
| Lite-On Bluetooth Device                                                            | 11        | 2.29%   |
| IMC Networks Bluetooth Device                                                       | 11        | 2.29%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 9         | 1.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 9         | 1.88%   |
| Apple Bluetooth Host Controller                                                     | 9         | 1.88%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 8         | 1.67%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 8         | 1.67%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 8         | 1.67%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 7         | 1.46%   |
| IMC Networks Bluetooth Radio                                                        | 7         | 1.46%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 1.46%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 7         | 1.46%   |
| Ralink RT3290 Bluetooth                                                             | 6         | 1.25%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 6         | 1.25%   |
| Dell DW375 Bluetooth Module                                                         | 5         | 1.04%   |
| Dell BCM20702A0                                                                     | 5         | 1.04%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 4         | 0.83%   |
| Toshiba Bluetooth Device                                                            | 3         | 0.63%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 0.63%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 3         | 0.63%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 3         | 0.63%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 3         | 0.63%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 0.63%   |
| Apple Bluetooth HCI                                                                 | 3         | 0.63%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 3         | 0.63%   |
| Toshiba Integrated Bluetooth HCI                                                    | 2         | 0.42%   |
| Toshiba BCM43142A0                                                                  | 2         | 0.42%   |
| Realtek Bluetooth Radio                                                             | 2         | 0.42%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.42%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 2         | 0.42%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.42%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.42%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 2         | 0.42%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 2         | 0.42%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.42%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.42%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.21%   |
| Toshiba BRCM Bluetooth Controller BCM2070                                           | 1         | 0.21%   |
| Toshiba Askey for                                                                   | 1         | 0.21%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.21%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.21%   |
| Realtek CSR BS8510                                                                  | 1         | 0.21%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.21%   |
| Qualcomm Atheros Bluetooth (AR3011)                                                 | 1         | 0.21%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.21%   |
| MediaTek MT7630e Bluetooth Adapter                                                  | 1         | 0.21%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.21%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.21%   |
| Lite-On BCM43142A0                                                                  | 1         | 0.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.21%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.21%   |
| IMC Networks Bluetooth                                                              | 1         | 0.21%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 513       | 70.56%  |
| AMD                                  | 113       | 15.54%  |
| Nvidia                               | 84        | 11.55%  |
| SteelSeries ApS                      | 2         | 0.28%   |
| Realtek Semiconductor                | 2         | 0.28%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.14%   |
| Tenx Technology                      | 1         | 0.14%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.14%   |
| Sennheiser Communications            | 1         | 0.14%   |
| Razer USA                            | 1         | 0.14%   |
| Lenovo                               | 1         | 0.14%   |
| GN Netcom                            | 1         | 0.14%   |
| Generalplus Technology               | 1         | 0.14%   |
| Focusrite-Novation                   | 1         | 0.14%   |
| Creative Technology                  | 1         | 0.14%   |
| Corsair                              | 1         | 0.14%   |
| Conexant Systems                     | 1         | 0.14%   |
| C-Media Electronics                  | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 74        | 8.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 69        | 7.79%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 50        | 5.64%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 42        | 4.74%   |
| Intel 8 Series HD Audio Controller                                                                | 40        | 4.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 39        | 4.4%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 37        | 4.18%   |
| AMD FCH Azalia Controller                                                                         | 30        | 3.39%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 25        | 2.82%   |
| AMD Kabini HDMI/DP Audio                                                                          | 22        | 2.48%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 21        | 2.37%   |
| Intel Broadwell-U Audio Controller                                                                | 21        | 2.37%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 21        | 2.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 19        | 2.14%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 19        | 2.14%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 18        | 2.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 18        | 2.03%   |
| Intel Cannon Lake PCH cAVS                                                                        | 17        | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 14        | 1.58%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 14        | 1.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 14        | 1.58%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 13        | 1.47%   |
| Intel CM238 HD Audio Controller                                                                   | 13        | 1.47%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 12        | 1.35%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 12        | 1.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 12        | 1.35%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 12        | 1.35%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 11        | 1.24%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 11        | 1.24%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 10        | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 10        | 1.13%   |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 0.9%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 7         | 0.79%   |
| AMD High Definition Audio Controller                                                              | 7         | 0.79%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 0.68%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 0.68%   |
| AMD Wrestler HDMI Audio                                                                           | 6         | 0.68%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.56%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 0.56%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 0.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 0.45%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.34%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.34%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.34%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 0.34%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.34%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.34%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.34%   |
| Nvidia Audio device                                                                               | 3         | 0.34%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.34%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.34%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 3         | 0.34%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 0.34%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 3         | 0.34%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 3         | 0.34%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.23%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 2         | 0.23%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.23%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.23%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                                            | 2         | 0.23%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 35        | 26.72%  |
| SK Hynix            | 33        | 25.19%  |
| Micron Technology   | 19        | 14.5%   |
| Unknown             | 8         | 6.11%   |
| Kingston            | 8         | 6.11%   |
| Unknown (ABCD)      | 5         | 3.82%   |
| A-DATA Technology   | 5         | 3.82%   |
| Nanya Technology    | 3         | 2.29%   |
| Crucial             | 3         | 2.29%   |
| Ramaxel Technology  | 2         | 1.53%   |
| Patriot             | 2         | 1.53%   |
| TIMETEC             | 1         | 0.76%   |
| Teikon              | 1         | 0.76%   |
| Team                | 1         | 0.76%   |
| Strontium           | 1         | 0.76%   |
| Puskill             | 1         | 0.76%   |
| ELPIDA              | 1         | 0.76%   |
| AXIOM               | 1         | 0.76%   |
| Avant               | 1         | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s    | 4         | 2.92%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 4         | 2.92%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s           | 4         | 2.92%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 4         | 2.92%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 3         | 2.19%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s              | 3         | 2.19%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 2         | 1.46%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 2         | 1.46%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.46%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 2         | 1.46%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 1.46%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.46%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s               | 2         | 1.46%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 2         | 1.46%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s             | 2         | 1.46%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 2         | 1.46%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 2         | 1.46%   |
| A-DATA RAM AE4S240038G17-BHYA 8192MB SODIMM DDR4 2400MT/s           | 2         | 1.46%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                         | 1         | 0.73%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                      | 1         | 0.73%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                        | 1         | 0.73%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 0.73%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 0.73%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s        | 1         | 0.73%   |
| TIMETEC RAM SD3-1600 8192MB SODIMM DDR3 1600MT/s                    | 1         | 0.73%   |
| Teikon RAM TMT351S6EFR8A-PBHJ 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.73%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 8400MT/s                | 1         | 0.73%   |
| Strontium RAM SRT4G86S1-P9H 4GB SODIMM DDR3 1600MT/s                | 1         | 0.73%   |
| SK Hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                   | 1         | 0.73%   |
| SK Hynix RAM HYMP112S64CP6-Y5 1024MB SODIMM DDR 667MT/s             | 1         | 0.73%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.73%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.73%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.73%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.73%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.73%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s              | 1         | 0.73%   |
| SK Hynix RAM HMT112S6BFR6C-G7 1024MB SODIMM DDR3 1067MT/s           | 1         | 0.73%   |
| SK Hynix RAM HMP351S6AFR8C-S6 4GB SODIMM DDR2 800MT/s               | 1         | 0.73%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.73%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 0.73%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 0.73%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.73%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s           | 1         | 0.73%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.73%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 1         | 0.73%   |
| SK Hynix RAM HCNNNCPMBLHR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 0.73%   |
| SK Hynix RAM H9CCNNNCPTMLBR-NTE 4096MB SODIMM LPDDR3 1600MT/s       | 1         | 0.73%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s          | 1         | 0.73%   |
| Samsung RAM U6E3S4AA-MGCR 4096MB Row Of Chips LPDDR4 4267MT/s       | 1         | 0.73%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 1         | 0.73%   |
| Samsung RAM Module 4096MB SODIMM LPDDR3 1600MT/s                    | 1         | 0.73%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s            | 1         | 0.73%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 1         | 0.73%   |
| Samsung RAM M471B5674BM0-CK0 2GB SODIMM DDR3 1600MT/s               | 1         | 0.73%   |
| Samsung RAM M471B5673EH1-CH9 2GB SODIMM DDR3 1334MT/s               | 1         | 0.73%   |
| Samsung RAM M471B5673EH1-CF8 2048MB SODIMM DDR3 4199MT/s            | 1         | 0.73%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s               | 1         | 0.73%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.73%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.73%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.73%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 52        | 46.02%  |
| DDR3   | 36        | 31.86%  |
| LPDDR4 | 10        | 8.85%   |
| LPDDR3 | 7         | 6.19%   |
| SDRAM  | 4         | 3.54%   |
| DDR2   | 4         | 3.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 97        | 87.39%  |
| Row Of Chips | 12        | 10.81%  |
| DIMM         | 1         | 0.9%    |
| Chip         | 1         | 0.9%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 55        | 43.65%  |
| 8192  | 40        | 31.75%  |
| 2048  | 14        | 11.11%  |
| 16384 | 13        | 10.32%  |
| 1024  | 3         | 2.38%   |
| 32768 | 1         | 0.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 30        | 24.59%  |
| 1600    | 27        | 22.13%  |
| 3200    | 13        | 10.66%  |
| 2400    | 12        | 9.84%   |
| 1334    | 7         | 5.74%   |
| 2133    | 5         | 4.1%    |
| 4267    | 4         | 3.28%   |
| 3266    | 4         | 3.28%   |
| Unknown | 4         | 3.28%   |
| 1333    | 3         | 2.46%   |
| 800     | 3         | 2.46%   |
| 4199    | 2         | 1.64%   |
| 2048    | 2         | 1.64%   |
| 1867    | 2         | 1.64%   |
| 667     | 2         | 1.64%   |
| 8400    | 1         | 0.82%   |
| 1067    | 1         | 0.82%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 4         | 57.14%  |
| Canon           | 2         | 28.57%  |
| Seiko Epson     | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| Seiko Epson L3110 Series  | 1         | 14.29%  |
| HP LaserJet 1200          | 1         | 14.29%  |
| HP LaserJet 1000          | 1         | 14.29%  |
| HP ENVY Photo 6200 series | 1         | 14.29%  |
| HP DeskJet 1110 series    | 1         | 14.29%  |
| Canon TS3100 series       | 1         | 14.29%  |
| Canon PIXMA MG3000 series | 1         | 14.29%  |

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


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 1         | 50%     |
| Canon CanoScan LiDE 90                      | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 139       | 25.5%   |
| Realtek Semiconductor                  | 60        | 11.01%  |
| IMC Networks                           | 55        | 10.09%  |
| Microdia                               | 41        | 7.52%   |
| Cheng Uei Precision Industry (Foxlink) | 32        | 5.87%   |
| Acer                                   | 31        | 5.69%   |
| Sunplus Innovation Technology          | 30        | 5.5%    |
| Suyin                                  | 23        | 4.22%   |
| Quanta                                 | 21        | 3.85%   |
| Syntek                                 | 19        | 3.49%   |
| Apple                                  | 11        | 2.02%   |
| Ricoh                                  | 10        | 1.83%   |
| Lite-On Technology                     | 10        | 1.83%   |
| Silicon Motion                         | 9         | 1.65%   |
| Alcor Micro                            | 9         | 1.65%   |
| Samsung Electronics                    | 5         | 0.92%   |
| Primax Electronics                     | 4         | 0.73%   |
| Luxvisions Innotech Limited            | 3         | 0.55%   |
| DJKANA1BIF866I                         | 3         | 0.55%   |
| Z-Star Microelectronics                | 2         | 0.37%   |
| Sunplus Technology                     | 2         | 0.37%   |
| Logitech                               | 2         | 0.37%   |
| icSpring                               | 2         | 0.37%   |
| Genesys Logic                          | 2         | 0.37%   |
| ALi                                    | 2         | 0.37%   |
| YGTek                                  | 1         | 0.18%   |
| Y Media                                | 1         | 0.18%   |
| SunplusIT                              | 1         | 0.18%   |
| Pixart Imaging                         | 1         | 0.18%   |
| Panasonic (Matsushita)                 | 1         | 0.18%   |
| OmniVision Technologies                | 1         | 0.18%   |
| Microsoft                              | 1         | 0.18%   |
| LG Electronics                         | 1         | 0.18%   |
| Lenovo                                 | 1         | 0.18%   |
| KYE Systems (Mouse Systems)            | 1         | 0.18%   |
| Importek                               | 1         | 0.18%   |
| Huawei Technologies                    | 1         | 0.18%   |
| GenesysLogic Technology                | 1         | 0.18%   |
| Generalplus Technology                 | 1         | 0.18%   |
| GEMBIRD                                | 1         | 0.18%   |
| DigiTech                               | 1         | 0.18%   |
| Denron                                 | 1         | 0.18%   |
| ARC International                      | 1         | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 17        | 3.11%   |
| Chicony HD WebCam                                                          | 17        | 3.11%   |
| Microdia Integrated_Webcam_HD                                              | 15        | 2.75%   |
| Chicony Integrated Camera                                                  | 15        | 2.75%   |
| Realtek Integrated_Webcam_HD                                               | 14        | 2.56%   |
| Realtek USB Camera                                                         | 12        | 2.2%    |
| Chicony TOSHIBA Web Camera - HD                                            | 11        | 2.01%   |
| Microdia Integrated Webcam                                                 | 10        | 1.83%   |
| Acer Integrated Camera                                                     | 10        | 1.83%   |
| Syntek Integrated Camera                                                   | 9         | 1.65%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 9         | 1.65%   |
| IMC Networks Integrated Camera                                             | 8         | 1.47%   |
| Chicony HP Truevision HD                                                   | 7         | 1.28%   |
| Sunplus Integrated_Webcam_HD                                               | 6         | 1.1%    |
| Sunplus HD WebCam                                                          | 6         | 1.1%    |
| Realtek Integrated Webcam                                                  | 6         | 1.1%    |
| Chicony USB2.0 VGA UVC WebCam                                              | 6         | 1.1%    |
| Syntek Lenovo EasyCamera                                                   | 5         | 0.92%   |
| Samsung Galaxy A5 (MTP)                                                    | 5         | 0.92%   |
| Quanta HD User Facing                                                      | 5         | 0.92%   |
| Chicony VGA Webcam                                                         | 5         | 0.92%   |
| Chicony USB 2.0 Camera                                                     | 5         | 0.92%   |
| Chicony Lenovo EasyCamera                                                  | 5         | 0.92%   |
| Chicony HP Webcam                                                          | 5         | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 5         | 0.92%   |
| Acer Lenovo Integrated Webcam                                              | 5         | 0.92%   |
| Acer Lenovo EasyCamera                                                     | 5         | 0.92%   |
| Suyin Laptop_Integrated_Webcam_HD                                          | 4         | 0.73%   |
| Suyin HP TrueVision HD                                                     | 4         | 0.73%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 4         | 0.73%   |
| Realtek Lenovo EasyCamera                                                  | 4         | 0.73%   |
| Realtek Integrated Webcam HD                                               | 4         | 0.73%   |
| Realtek HP Truevision HD integrated webcam                                 | 4         | 0.73%   |
| Quanta VGA WebCam                                                          | 4         | 0.73%   |
| Microdia Webcam Vitade AF                                                  | 4         | 0.73%   |
| Lite-On HP HD Camera                                                       | 4         | 0.73%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 4         | 0.73%   |
| Chicony HP Truevision HD camera                                            | 4         | 0.73%   |
| Chicony EasyCamera                                                         | 4         | 0.73%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 4         | 0.73%   |
| Apple FaceTime HD Camera                                                   | 4         | 0.73%   |
| Alcor Micro USB 2.0 Camera                                                 | 4         | 0.73%   |
| Alcor Micro Asus Integrated Webcam                                         | 4         | 0.73%   |
| Ricoh USB2.0 Camera                                                        | 3         | 0.55%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 3         | 0.55%   |
| Realtek USB2.0 HD UVC WebCam                                               | 3         | 0.55%   |
| Quanta HP Wide Vision HD Camera                                            | 3         | 0.55%   |
| Quanta HP TrueVision HD Camera                                             | 3         | 0.55%   |
| IMC Networks USB Camera                                                    | 3         | 0.55%   |
| IMC Networks Lenovo EasyCamera                                             | 3         | 0.55%   |
| DJKANA1BIF866I HP Wide Vision HD Camera                                    | 3         | 0.55%   |
| Chicony USB2.0 HD UVC WebCam                                               | 3         | 0.55%   |
| Chicony USB2.0 Camera                                                      | 3         | 0.55%   |
| Chicony HP HD Webcam [Fixed]                                               | 3         | 0.55%   |
| Chicony HP HD Camera                                                       | 3         | 0.55%   |
| Chicony HD User Facing                                                     | 3         | 0.55%   |
| Chicony CNFA078                                                            | 3         | 0.55%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 3         | 0.55%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 0.55%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 3         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 44        | 46.32%  |
| Upek                       | 13        | 13.68%  |
| Shenzhen Goodix Technology | 11        | 11.58%  |
| AuthenTec                  | 11        | 11.58%  |
| Synaptics                  | 7         | 7.37%   |
| STMicroelectronics         | 4         | 4.21%   |
| LighTuning Technology      | 4         | 4.21%   |
| Focal-systems.Corp         | 1         | 1.05%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 12.63%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 10.53%  |
| Shenzhen Goodix  Fingerprint Device                                        | 6         | 6.32%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 5.26%   |
| Validity Sensors VFS491                                                    | 4         | 4.21%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 4.21%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 4.21%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 4.21%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 3.16%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 3.16%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 3.16%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 3.16%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 3.16%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 3.16%   |
| AuthenTec AES2810                                                          | 3         | 3.16%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 3.16%   |
| Unknown                                                                    | 3         | 3.16%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 2.11%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 2.11%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 2.11%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 2.11%   |
| AuthenTec AES1600                                                          | 2         | 2.11%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.05%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.05%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.05%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.05%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.05%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.05%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.05%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 1.05%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.05%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 30        | 58.82%  |
| Alcor Micro                       | 8         | 15.69%  |
| O2 Micro                          | 4         | 7.84%   |
| Yubico.com                        | 2         | 3.92%   |
| Upek                              | 2         | 3.92%   |
| Lenovo                            | 2         | 3.92%   |
| VASCO Data Security International | 1         | 1.96%   |
| SCM Microsystems                  | 1         | 1.96%   |
| OmniKey                           | 1         | 1.96%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 19.61%  |
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 19.61%  |
| Broadcom 5880                                                                | 9         | 17.65%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 8         | 15.69%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 7.84%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 2         | 3.92%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.92%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 3.92%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 1.96%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 1.96%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 1.96%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.96%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 426       | 66.67%  |
| 1     | 161       | 25.2%   |
| 2     | 48        | 7.51%   |
| 3     | 4         | 0.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 94        | 35.74%  |
| Chipcard                 | 44        | 16.73%  |
| Graphics card            | 41        | 15.59%  |
| Multimedia controller    | 29        | 11.03%  |
| Net/wireless             | 25        | 9.51%   |
| Storage                  | 11        | 4.18%   |
| Bluetooth                | 8         | 3.04%   |
| Flash memory             | 2         | 0.76%   |
| Camera                   | 2         | 0.76%   |
| Storage/ide              | 1         | 0.38%   |
| Sound                    | 1         | 0.38%   |
| Network                  | 1         | 0.38%   |
| Net/ethernet             | 1         | 0.38%   |
| Dvb card                 | 1         | 0.38%   |
| Communication controller | 1         | 0.38%   |
| Card reader              | 1         | 0.38%   |


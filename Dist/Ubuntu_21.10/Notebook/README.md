Ubuntu 21.10 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 21.10.

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
| HP            | Pavilion Gaming Laptop 1... | [3fc1d4b98d](https://linux-hardware.org/?probe=3fc1d4b98d) | Dec 31, 2021 |
| Samsung       | NC210/NC110                 | [4d26b14130](https://linux-hardware.org/?probe=4d26b14130) | Dec 31, 2021 |
| Samsung       | NC210/NC110                 | [bb92ee12a5](https://linux-hardware.org/?probe=bb92ee12a5) | Dec 31, 2021 |
| HP            | EliteBook 840 G2            | [3e2bf79497](https://linux-hardware.org/?probe=3e2bf79497) | Dec 31, 2021 |
| Lenovo        | ThinkPad T440s 20ARS05V0... | [7c496e685d](https://linux-hardware.org/?probe=7c496e685d) | Dec 31, 2021 |
| Acer          | Aspire 5920                 | [b492dec09b](https://linux-hardware.org/?probe=b492dec09b) | Dec 31, 2021 |
| Dell          | XPS 13 9300                 | [50206d4c03](https://linux-hardware.org/?probe=50206d4c03) | Dec 30, 2021 |
| Medion        | E6224                       | [4ebf65b683](https://linux-hardware.org/?probe=4ebf65b683) | Dec 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [c14a0f6bed](https://linux-hardware.org/?probe=c14a0f6bed) | Dec 30, 2021 |
| Lenovo        | G40-80 80E4                 | [993fe7cef6](https://linux-hardware.org/?probe=993fe7cef6) | Dec 30, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [7c11e2a10b](https://linux-hardware.org/?probe=7c11e2a10b) | Dec 30, 2021 |
| Dell          | XPS 17 9710                 | [cf5002d9df](https://linux-hardware.org/?probe=cf5002d9df) | Dec 29, 2021 |
| Lenovo        | V330-14ARR 81B1             | [290d6b4ad5](https://linux-hardware.org/?probe=290d6b4ad5) | Dec 29, 2021 |
| Acer          | Predator G3-572             | [87dc579598](https://linux-hardware.org/?probe=87dc579598) | Dec 29, 2021 |
| Lenovo        | ThinkPad E595 20NF0005IX    | [33b1bcf72f](https://linux-hardware.org/?probe=33b1bcf72f) | Dec 29, 2021 |
| Dell          | G3 3579                     | [873c470afd](https://linux-hardware.org/?probe=873c470afd) | Dec 29, 2021 |
| Dell          | Latitude 5420               | [42e63fd746](https://linux-hardware.org/?probe=42e63fd746) | Dec 29, 2021 |
| Dell          | Inspiron 1720               | [b40685ea7b](https://linux-hardware.org/?probe=b40685ea7b) | Dec 29, 2021 |
| Dell          | Latitude 5420               | [ae4bf2544b](https://linux-hardware.org/?probe=ae4bf2544b) | Dec 29, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [484cb2f9cf](https://linux-hardware.org/?probe=484cb2f9cf) | Dec 29, 2021 |
| HP            | Pavilion g7                 | [751d37e5fd](https://linux-hardware.org/?probe=751d37e5fd) | Dec 29, 2021 |
| Lenovo        | Ducati 5 82ES               | [646ce5947c](https://linux-hardware.org/?probe=646ce5947c) | Dec 28, 2021 |
| HUAWEI        | KLVL-WXX9                   | [88344cd6d3](https://linux-hardware.org/?probe=88344cd6d3) | Dec 28, 2021 |
| Lenovo        | Ducati 5 82ES               | [f53e88bfa4](https://linux-hardware.org/?probe=f53e88bfa4) | Dec 28, 2021 |
| Lenovo        | V330-15IKB 81AX             | [f68615959b](https://linux-hardware.org/?probe=f68615959b) | Dec 28, 2021 |
| Dell          | Latitude 5410               | [0e38439f9e](https://linux-hardware.org/?probe=0e38439f9e) | Dec 28, 2021 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [a4a4581b6d](https://linux-hardware.org/?probe=a4a4581b6d) | Dec 28, 2021 |
| Dell          | Inspiron 5537               | [f29a5f0ecb](https://linux-hardware.org/?probe=f29a5f0ecb) | Dec 28, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [a9e50f6f42](https://linux-hardware.org/?probe=a9e50f6f42) | Dec 28, 2021 |
| Acidanther... | MacBookPro12,1              | [82e00560e5](https://linux-hardware.org/?probe=82e00560e5) | Dec 28, 2021 |
| Dell          | Latitude E7470              | [55e3078baf](https://linux-hardware.org/?probe=55e3078baf) | Dec 28, 2021 |
| Google        | Akemi                       | [b2edfd3821](https://linux-hardware.org/?probe=b2edfd3821) | Dec 28, 2021 |
| HP            | ProBook 6450b               | [3b1bcce13d](https://linux-hardware.org/?probe=3b1bcce13d) | Dec 28, 2021 |
| eMachines     | E525                        | [fd80580005](https://linux-hardware.org/?probe=fd80580005) | Dec 28, 2021 |
| Sony          | VPCEL1E1E                   | [4deb7655c4](https://linux-hardware.org/?probe=4deb7655c4) | Dec 27, 2021 |
| Avell High... | A70 MOB                     | [dac7555e81](https://linux-hardware.org/?probe=dac7555e81) | Dec 27, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [938d24e76e](https://linux-hardware.org/?probe=938d24e76e) | Dec 27, 2021 |
| Acer          | Predator G3-572             | [ea72b1c252](https://linux-hardware.org/?probe=ea72b1c252) | Dec 27, 2021 |
| Acer          | Aspire ES1-132              | [bb6f2edc27](https://linux-hardware.org/?probe=bb6f2edc27) | Dec 27, 2021 |
| MSI           | GL62M 7RDX                  | [3f8cb0706d](https://linux-hardware.org/?probe=3f8cb0706d) | Dec 27, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [6a4ffab5ad](https://linux-hardware.org/?probe=6a4ffab5ad) | Dec 27, 2021 |
| Sony          | VGN-CS320J                  | [1b74edca8c](https://linux-hardware.org/?probe=1b74edca8c) | Dec 27, 2021 |
| Sony          | VGN-CS320J                  | [2dbfd6ad98](https://linux-hardware.org/?probe=2dbfd6ad98) | Dec 27, 2021 |
| Dell          | Inspiron 3543               | [30756486fd](https://linux-hardware.org/?probe=30756486fd) | Dec 26, 2021 |
| Dell          | Precision M6700             | [5a31793e53](https://linux-hardware.org/?probe=5a31793e53) | Dec 26, 2021 |
| Acer          | Aspire 5750G                | [052954142f](https://linux-hardware.org/?probe=052954142f) | Dec 26, 2021 |
| ASUSTek       | X550CL                      | [4eb9e6a01b](https://linux-hardware.org/?probe=4eb9e6a01b) | Dec 25, 2021 |
| Acer          | Swift SF315-41              | [92f264978e](https://linux-hardware.org/?probe=92f264978e) | Dec 25, 2021 |
| Acer          | Swift SF315-41              | [d94d38f29b](https://linux-hardware.org/?probe=d94d38f29b) | Dec 25, 2021 |
| ASUSTek       | X705NC                      | [c3cdc81bd8](https://linux-hardware.org/?probe=c3cdc81bd8) | Dec 25, 2021 |
| Lenovo        | ThinkPad T14s 20UJ0014FR    | [e7ccf2fa85](https://linux-hardware.org/?probe=e7ccf2fa85) | Dec 25, 2021 |
| eMachines     | E525                        | [fcc3b2a5e3](https://linux-hardware.org/?probe=fcc3b2a5e3) | Dec 25, 2021 |
| eMachines     | E525                        | [e5853e5629](https://linux-hardware.org/?probe=e5853e5629) | Dec 25, 2021 |
| HP            | EliteBook 840 G3            | [d149e3e8cd](https://linux-hardware.org/?probe=d149e3e8cd) | Dec 24, 2021 |
| Dell          | Inspiron N5050              | [df6e5df46d](https://linux-hardware.org/?probe=df6e5df46d) | Dec 24, 2021 |
| Sony          | VPCEA3S1E                   | [15bf845627](https://linux-hardware.org/?probe=15bf845627) | Dec 24, 2021 |
| HP            | EliteBook 840 G2            | [2be9e8fd67](https://linux-hardware.org/?probe=2be9e8fd67) | Dec 23, 2021 |
| HP            | EliteBook 840 G2            | [024febade8](https://linux-hardware.org/?probe=024febade8) | Dec 23, 2021 |
| Dell          | Inspiron 1720               | [6d1e22e244](https://linux-hardware.org/?probe=6d1e22e244) | Dec 23, 2021 |
| HP            | ENVY 17                     | [1601038695](https://linux-hardware.org/?probe=1601038695) | Dec 23, 2021 |
| Samsung       | 700T                        | [dcd96a051e](https://linux-hardware.org/?probe=dcd96a051e) | Dec 23, 2021 |
| HP            | ProBook 6450b               | [da7840b49c](https://linux-hardware.org/?probe=da7840b49c) | Dec 23, 2021 |
| HP            | ProBook 6450b               | [0bad0405df](https://linux-hardware.org/?probe=0bad0405df) | Dec 23, 2021 |
| Apple         | MacBookPro11,1              | [187a32ebb8](https://linux-hardware.org/?probe=187a32ebb8) | Dec 23, 2021 |
| Schenker T... | VIA13                       | [91faaef5d1](https://linux-hardware.org/?probe=91faaef5d1) | Dec 22, 2021 |
| ASUSTek       | TP300LD                     | [b6a5dd1c92](https://linux-hardware.org/?probe=b6a5dd1c92) | Dec 22, 2021 |
| ASUSTek       | TP300LD                     | [7c11fdeeeb](https://linux-hardware.org/?probe=7c11fdeeeb) | Dec 22, 2021 |
| MSI           | GF65 Thin 9SEXR             | [2be4e41c8e](https://linux-hardware.org/?probe=2be4e41c8e) | Dec 22, 2021 |
| HP            | Pavilion g7                 | [68d9fe0608](https://linux-hardware.org/?probe=68d9fe0608) | Dec 22, 2021 |
| Sony          | VGN-CS320J                  | [9f1e770843](https://linux-hardware.org/?probe=9f1e770843) | Dec 22, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [985fc37716](https://linux-hardware.org/?probe=985fc37716) | Dec 22, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | [40282bb1fd](https://linux-hardware.org/?probe=40282bb1fd) | Dec 21, 2021 |
| Dell          | Latitude E6400              | [e09bc74c03](https://linux-hardware.org/?probe=e09bc74c03) | Dec 21, 2021 |
| Dell          | Latitude E6400              | [b4e84b9759](https://linux-hardware.org/?probe=b4e84b9759) | Dec 21, 2021 |
| Sony          | VPCEA3S1E                   | [17a79ba919](https://linux-hardware.org/?probe=17a79ba919) | Dec 21, 2021 |
| Acer          | Swift SF114-34              | [84c382b787](https://linux-hardware.org/?probe=84c382b787) | Dec 21, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [13ec8a9420](https://linux-hardware.org/?probe=13ec8a9420) | Dec 21, 2021 |
| Razer         | Blade 15 Advanced Model ... | [5408a1a82b](https://linux-hardware.org/?probe=5408a1a82b) | Dec 21, 2021 |
| Toshiba       | Satellite C55-B             | [fb0b43fb55](https://linux-hardware.org/?probe=fb0b43fb55) | Dec 21, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [0e34c5b120](https://linux-hardware.org/?probe=0e34c5b120) | Dec 21, 2021 |
| Acer          | Aspire V5-531               | [0a0ee7ecaf](https://linux-hardware.org/?probe=0a0ee7ecaf) | Dec 20, 2021 |
| Dell          | Latitude 5400               | [692bc521a6](https://linux-hardware.org/?probe=692bc521a6) | Dec 20, 2021 |
| Sony          | VGN-CS320J                  | [7143ced3cd](https://linux-hardware.org/?probe=7143ced3cd) | Dec 20, 2021 |
| Dell          | XPS 15 9500                 | [e5592dfde0](https://linux-hardware.org/?probe=e5592dfde0) | Dec 20, 2021 |
| Lenovo        | ThinkPad T430 2349MMS       | [d14536043e](https://linux-hardware.org/?probe=d14536043e) | Dec 20, 2021 |
| MSI           | GS66 Stealth 11UE           | [ab09d4463d](https://linux-hardware.org/?probe=ab09d4463d) | Dec 20, 2021 |
| Dell          | G15 5510                    | [1209f0844f](https://linux-hardware.org/?probe=1209f0844f) | Dec 20, 2021 |
| Acer          | TravelMate8472TG            | [28362377e3](https://linux-hardware.org/?probe=28362377e3) | Dec 20, 2021 |
| Acer          | Swift SF114-34              | [f7d3352cbc](https://linux-hardware.org/?probe=f7d3352cbc) | Dec 19, 2021 |
| Samsung       | 270E5J/2570EJ               | [a15986fe04](https://linux-hardware.org/?probe=a15986fe04) | Dec 19, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [183c18d8a8](https://linux-hardware.org/?probe=183c18d8a8) | Dec 19, 2021 |
| HUAWEI        | MACH-WX9                    | [033e872459](https://linux-hardware.org/?probe=033e872459) | Dec 19, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [79165f1ffe](https://linux-hardware.org/?probe=79165f1ffe) | Dec 19, 2021 |
| Schenker      | XMG CORE (REN/E21)          | [8fc46b7322](https://linux-hardware.org/?probe=8fc46b7322) | Dec 19, 2021 |
| Samsung       | R430/P430/R480              | [a45bad76ae](https://linux-hardware.org/?probe=a45bad76ae) | Dec 19, 2021 |
| HP            | Pavilion dv7                | [bfc5e45295](https://linux-hardware.org/?probe=bfc5e45295) | Dec 19, 2021 |
| HP            | Pavilion dv7                | [184202cc4e](https://linux-hardware.org/?probe=184202cc4e) | Dec 19, 2021 |
| HP            | Presario CQ61               | [de2053aa1e](https://linux-hardware.org/?probe=de2053aa1e) | Dec 19, 2021 |
| MSI           | GT80 2QC                    | [68b70c6ff9](https://linux-hardware.org/?probe=68b70c6ff9) | Dec 19, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [515a90b57b](https://linux-hardware.org/?probe=515a90b57b) | Dec 18, 2021 |
| Fujitsu       | LIFEBOOK S782               | [2fed9ebf97](https://linux-hardware.org/?probe=2fed9ebf97) | Dec 18, 2021 |
| HP            | Pro x2 612 G1 Tablet        | [ec2c4c7d27](https://linux-hardware.org/?probe=ec2c4c7d27) | Dec 18, 2021 |
| Dell          | G15 5510                    | [e5039b3b7d](https://linux-hardware.org/?probe=e5039b3b7d) | Dec 18, 2021 |
| Dell          | Inspiron 5515               | [2e61608393](https://linux-hardware.org/?probe=2e61608393) | Dec 18, 2021 |
| Dell          | Precision 5520              | [2b76ccd66c](https://linux-hardware.org/?probe=2b76ccd66c) | Dec 18, 2021 |
| MSI           | Katana GF66 11UE            | [36aea8dc19](https://linux-hardware.org/?probe=36aea8dc19) | Dec 18, 2021 |
| MSI           | Katana GF66 11UE            | [56be528067](https://linux-hardware.org/?probe=56be528067) | Dec 18, 2021 |
| Acer          | Swift SF314-51              | [6b157ea1d6](https://linux-hardware.org/?probe=6b157ea1d6) | Dec 18, 2021 |
| Dell          | XPS 15 9500                 | [7bb94e89f6](https://linux-hardware.org/?probe=7bb94e89f6) | Dec 18, 2021 |
| Dell          | 500                         | [b0e7e6d913](https://linux-hardware.org/?probe=b0e7e6d913) | Dec 17, 2021 |
| ASUSTek       | T300CHI                     | [87feb239ae](https://linux-hardware.org/?probe=87feb239ae) | Dec 17, 2021 |
| Apple         | MacBookPro5,5               | [5de20fd13d](https://linux-hardware.org/?probe=5de20fd13d) | Dec 17, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [3f89172d4b](https://linux-hardware.org/?probe=3f89172d4b) | Dec 17, 2021 |
| HUAWEI        | KLVL-WXX9                   | [99473bac5d](https://linux-hardware.org/?probe=99473bac5d) | Dec 17, 2021 |
| Acer          | Aspire A515-56              | [a50b285530](https://linux-hardware.org/?probe=a50b285530) | Dec 17, 2021 |
| Sony          | SVF1521L6EW                 | [64160de19b](https://linux-hardware.org/?probe=64160de19b) | Dec 17, 2021 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [6ac6be1d38](https://linux-hardware.org/?probe=6ac6be1d38) | Dec 17, 2021 |
| Dell          | Latitude 5420 Rugged        | [34eebffb9b](https://linux-hardware.org/?probe=34eebffb9b) | Dec 17, 2021 |
| Dell          | Latitude 7389               | [9c25379d7d](https://linux-hardware.org/?probe=9c25379d7d) | Dec 16, 2021 |
| Dell          | Latitude 5420 Rugged        | [e5337761c4](https://linux-hardware.org/?probe=e5337761c4) | Dec 16, 2021 |
| Alienware     | 17 R5                       | [8a377c49a4](https://linux-hardware.org/?probe=8a377c49a4) | Dec 16, 2021 |
| Fujitsu       | LIFEBOOK E752               | [0b84572cff](https://linux-hardware.org/?probe=0b84572cff) | Dec 16, 2021 |
| HP            | ProBook 650 G8 Notebook ... | [6e8ba23594](https://linux-hardware.org/?probe=6e8ba23594) | Dec 16, 2021 |
| HP            | ProBook 650 G8 Notebook ... | [70a9d341b1](https://linux-hardware.org/?probe=70a9d341b1) | Dec 16, 2021 |
| Wortmann      | 1220679_1470212             | [798fc3faee](https://linux-hardware.org/?probe=798fc3faee) | Dec 16, 2021 |
| HP            | EliteBook 840 G6            | [46dab8c74a](https://linux-hardware.org/?probe=46dab8c74a) | Dec 16, 2021 |
| ASUSTek       | X550VX                      | [db3cd6403d](https://linux-hardware.org/?probe=db3cd6403d) | Dec 16, 2021 |
| Acer          | Swift SF314-51              | [3a62e5502b](https://linux-hardware.org/?probe=3a62e5502b) | Dec 15, 2021 |
| Dell          | Vostro 5402                 | [2cc6e5b35b](https://linux-hardware.org/?probe=2cc6e5b35b) | Dec 15, 2021 |
| Dell          | Latitude E6400              | [2936dcb6ab](https://linux-hardware.org/?probe=2936dcb6ab) | Dec 14, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | [0705e530b4](https://linux-hardware.org/?probe=0705e530b4) | Dec 14, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9b89720cb4](https://linux-hardware.org/?probe=9b89720cb4) | Dec 14, 2021 |
| Sony          | VPCF130FD                   | [4ff7ca9b6c](https://linux-hardware.org/?probe=4ff7ca9b6c) | Dec 14, 2021 |
| Lenovo        | ThinkPad T430 2349MMS       | [191acd1645](https://linux-hardware.org/?probe=191acd1645) | Dec 14, 2021 |
| HP            | ProBook 4530s               | [0003fe091b](https://linux-hardware.org/?probe=0003fe091b) | Dec 14, 2021 |
| Lenovo        | V15 G2 ALC 82KD             | [d391c926e7](https://linux-hardware.org/?probe=d391c926e7) | Dec 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a22c6968b8](https://linux-hardware.org/?probe=a22c6968b8) | Dec 13, 2021 |
| Toshiba       | Satellite L755              | [62e66068da](https://linux-hardware.org/?probe=62e66068da) | Dec 13, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [2e8509fb8b](https://linux-hardware.org/?probe=2e8509fb8b) | Dec 12, 2021 |
| HP            | EliteBook 725 G3            | [88a4be9c2e](https://linux-hardware.org/?probe=88a4be9c2e) | Dec 12, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [3228031778](https://linux-hardware.org/?probe=3228031778) | Dec 12, 2021 |
| HP            | ZBook 15 G6                 | [b241f46e61](https://linux-hardware.org/?probe=b241f46e61) | Dec 12, 2021 |
| HP            | Laptop 14-cf0xxx            | [2f4ec869f9](https://linux-hardware.org/?probe=2f4ec869f9) | Dec 12, 2021 |
| Framework     | Laptop                      | [3f9c87fb23](https://linux-hardware.org/?probe=3f9c87fb23) | Dec 12, 2021 |
| Dell          | XPS 17 9700                 | [eef9ef9d60](https://linux-hardware.org/?probe=eef9ef9d60) | Dec 12, 2021 |
| Dell          | Inspiron 3501               | [3b33dbdc6b](https://linux-hardware.org/?probe=3b33dbdc6b) | Dec 12, 2021 |
| Lenovo        | Z50-75 80EC                 | [94bfedf240](https://linux-hardware.org/?probe=94bfedf240) | Dec 11, 2021 |
| Acer          | ConceptD CN315-71P          | [ac834a5768](https://linux-hardware.org/?probe=ac834a5768) | Dec 11, 2021 |
| Dell          | Inspiron 3501               | [61e912c283](https://linux-hardware.org/?probe=61e912c283) | Dec 11, 2021 |
| HP            | ProBook 440 G6              | [b7313134e3](https://linux-hardware.org/?probe=b7313134e3) | Dec 11, 2021 |
| Dell          | Inspiron 3421               | [b18adbf17f](https://linux-hardware.org/?probe=b18adbf17f) | Dec 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5740d7d60c](https://linux-hardware.org/?probe=5740d7d60c) | Dec 11, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [22eeff89e5](https://linux-hardware.org/?probe=22eeff89e5) | Dec 11, 2021 |
| Dell          | Latitude 7370               | [d2bbf57105](https://linux-hardware.org/?probe=d2bbf57105) | Dec 11, 2021 |
| Fujitsu       | LIFEBOOK AH530/HD6          | [232b26315a](https://linux-hardware.org/?probe=232b26315a) | Dec 10, 2021 |
| Toshiba       | PORTEGE A600                | [7a5e987cb3](https://linux-hardware.org/?probe=7a5e987cb3) | Dec 10, 2021 |
| Dell          | Inspiron 13 5310            | [70a974c325](https://linux-hardware.org/?probe=70a974c325) | Dec 10, 2021 |
| Dell          | Latitude 9420               | [5e00e700d4](https://linux-hardware.org/?probe=5e00e700d4) | Dec 10, 2021 |
| Lenovo        | ThinkPad Edge E531 68852... | [bb53c502d7](https://linux-hardware.org/?probe=bb53c502d7) | Dec 09, 2021 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [45674cbd76](https://linux-hardware.org/?probe=45674cbd76) | Dec 09, 2021 |
| Samsung       | 750XDA                      | [30d61197a1](https://linux-hardware.org/?probe=30d61197a1) | Dec 09, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [bb9141f09c](https://linux-hardware.org/?probe=bb9141f09c) | Dec 09, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [b3c42ca2c2](https://linux-hardware.org/?probe=b3c42ca2c2) | Dec 09, 2021 |
| YJKC          | vBOOK Plus RVP7             | [5a0e887e34](https://linux-hardware.org/?probe=5a0e887e34) | Dec 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [e82de9b10d](https://linux-hardware.org/?probe=e82de9b10d) | Dec 09, 2021 |
| Dell          | Inspiron 7472               | [64b7b3a797](https://linux-hardware.org/?probe=64b7b3a797) | Dec 09, 2021 |
| HP            | Pavilion dv6                | [46ad5598d6](https://linux-hardware.org/?probe=46ad5598d6) | Dec 09, 2021 |
| HP            | Pavilion dv6                | [6bc2a41542](https://linux-hardware.org/?probe=6bc2a41542) | Dec 09, 2021 |
| Razer         | Blade 15 Advanced Model ... | [ccc253bb9a](https://linux-hardware.org/?probe=ccc253bb9a) | Dec 08, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [e3be4cf88c](https://linux-hardware.org/?probe=e3be4cf88c) | Dec 08, 2021 |
| Toshiba       | PORTEGE A600                | [2ecaddef09](https://linux-hardware.org/?probe=2ecaddef09) | Dec 08, 2021 |
| Lenovo        | ThinkPad T520 4243CJ2       | [15d1aafe1d](https://linux-hardware.org/?probe=15d1aafe1d) | Dec 08, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [98f25277f5](https://linux-hardware.org/?probe=98f25277f5) | Dec 08, 2021 |
| Avell High... | B.ON                        | [5bfb9e677a](https://linux-hardware.org/?probe=5bfb9e677a) | Dec 07, 2021 |
| Avell High... | B.ON                        | [d2b832ea0a](https://linux-hardware.org/?probe=d2b832ea0a) | Dec 07, 2021 |
| Toshiba       | Satellite Pro L650          | [fd40a9d639](https://linux-hardware.org/?probe=fd40a9d639) | Dec 07, 2021 |
| Dell          | Inspiron 5775               | [60c2ee09f1](https://linux-hardware.org/?probe=60c2ee09f1) | Dec 07, 2021 |
| Dell          | Inspiron 14-3467            | [c53e56384e](https://linux-hardware.org/?probe=c53e56384e) | Dec 07, 2021 |
| Dell          | Latitude E7470              | [06666f541b](https://linux-hardware.org/?probe=06666f541b) | Dec 07, 2021 |
| Lenovo        | ThinkPad T440 20B7S06M00    | [66c0123f35](https://linux-hardware.org/?probe=66c0123f35) | Dec 07, 2021 |
| Sony          | SVF14211CLB                 | [d25b1846ff](https://linux-hardware.org/?probe=d25b1846ff) | Dec 07, 2021 |
| Acer          | Aspire E5-511               | [9e8fd519f0](https://linux-hardware.org/?probe=9e8fd519f0) | Dec 07, 2021 |
| Sony          | SVF14211CLB                 | [41bfe6e292](https://linux-hardware.org/?probe=41bfe6e292) | Dec 06, 2021 |
| HP            | Pavilion dv6                | [38e3ffa8ec](https://linux-hardware.org/?probe=38e3ffa8ec) | Dec 06, 2021 |
| HP            | Pavilion dv6                | [c0ecac4d9e](https://linux-hardware.org/?probe=c0ecac4d9e) | Dec 06, 2021 |
| Acer          | Swift SF314-51              | [8d158d2fb2](https://linux-hardware.org/?probe=8d158d2fb2) | Dec 06, 2021 |
| HP            | ENVY dv7                    | [1ab140a424](https://linux-hardware.org/?probe=1ab140a424) | Dec 06, 2021 |
| Dell          | Latitude E6410              | [69e0c044fe](https://linux-hardware.org/?probe=69e0c044fe) | Dec 06, 2021 |
| Packard Be... | EasyNote TJ66               | [8083f4fc11](https://linux-hardware.org/?probe=8083f4fc11) | Dec 06, 2021 |
| Acer          | Swift SF314-43              | [ed43af14cf](https://linux-hardware.org/?probe=ed43af14cf) | Dec 06, 2021 |
| Acer          | Aspire 7715Z                | [8124f61a3f](https://linux-hardware.org/?probe=8124f61a3f) | Dec 06, 2021 |
| Dell          | Venue 11 Pro 7140           | [2cda03e17b](https://linux-hardware.org/?probe=2cda03e17b) | Dec 06, 2021 |
| Dell          | Latitude E6410              | [0b4762f0fd](https://linux-hardware.org/?probe=0b4762f0fd) | Dec 05, 2021 |
| Acer          | Aspire VN7-792G             | [4cbc6b946a](https://linux-hardware.org/?probe=4cbc6b946a) | Dec 05, 2021 |
| HP            | 15 Notebook PC              | [88f8ff50c8](https://linux-hardware.org/?probe=88f8ff50c8) | Dec 05, 2021 |
| ASUSTek       | Vivobook_ASUSLaptop X740... | [9bbc3af34c](https://linux-hardware.org/?probe=9bbc3af34c) | Dec 05, 2021 |
| Google        | Rammus                      | [5cdd87fe56](https://linux-hardware.org/?probe=5cdd87fe56) | Dec 04, 2021 |
| HP            | EliteBook 8460p             | [0dc1338ba5](https://linux-hardware.org/?probe=0dc1338ba5) | Dec 04, 2021 |
| Toshiba       | Satellite C50-A489          | [4d29ea3b9c](https://linux-hardware.org/?probe=4d29ea3b9c) | Dec 04, 2021 |
| Avell High... | B.ON                        | [91a81934ed](https://linux-hardware.org/?probe=91a81934ed) | Dec 04, 2021 |
| ASUSTek       | X505BA                      | [ed64395695](https://linux-hardware.org/?probe=ed64395695) | Dec 04, 2021 |
| Jooyontech... | J3GP Pro                    | [6f13d68344](https://linux-hardware.org/?probe=6f13d68344) | Dec 04, 2021 |
| HP            | ProBook 6450b               | [df1987d444](https://linux-hardware.org/?probe=df1987d444) | Dec 04, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [b90a8aa2b6](https://linux-hardware.org/?probe=b90a8aa2b6) | Dec 04, 2021 |
| HP            | 250 G5 Notebook PC          | [c977d7c465](https://linux-hardware.org/?probe=c977d7c465) | Dec 04, 2021 |
| Dell          | Inspiron 5490               | [21da3b7e37](https://linux-hardware.org/?probe=21da3b7e37) | Dec 03, 2021 |
| Acer          | Extensa 5620                | [1f4dcd31db](https://linux-hardware.org/?probe=1f4dcd31db) | Dec 03, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [61ace3554b](https://linux-hardware.org/?probe=61ace3554b) | Dec 03, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [bedc746ec5](https://linux-hardware.org/?probe=bedc746ec5) | Dec 03, 2021 |
| Packard Be... | EasyNote ENLG81BA           | [65df411fac](https://linux-hardware.org/?probe=65df411fac) | Dec 03, 2021 |
| Packard Be... | EasyNote ENLG81BA           | [2e396ceaf9](https://linux-hardware.org/?probe=2e396ceaf9) | Dec 03, 2021 |
| LG Electro... | 16ZD90P-GX5LK               | [c7cc850f29](https://linux-hardware.org/?probe=c7cc850f29) | Dec 03, 2021 |
| LG Electro... | 16ZD90P-GX5LK               | [901fdc3726](https://linux-hardware.org/?probe=901fdc3726) | Dec 03, 2021 |
| Apple         | MacBookPro12,1              | [48284cb8a5](https://linux-hardware.org/?probe=48284cb8a5) | Dec 02, 2021 |
| Toshiba       | Satellite L655              | [6cf5d39778](https://linux-hardware.org/?probe=6cf5d39778) | Dec 02, 2021 |
| Lenovo        | ThinkPad T410 2537W2L       | [92068cb097](https://linux-hardware.org/?probe=92068cb097) | Dec 02, 2021 |
| Lenovo        | ThinkPad T410 2537N99       | [a77255409f](https://linux-hardware.org/?probe=a77255409f) | Dec 02, 2021 |
| Lenovo        | ThinkPad T410 2537N99       | [ef02c2fb6c](https://linux-hardware.org/?probe=ef02c2fb6c) | Dec 02, 2021 |
| Apple         | MacBookPro14,3              | [d5c66e036d](https://linux-hardware.org/?probe=d5c66e036d) | Dec 02, 2021 |
| Dell          | XPS 13 9310                 | [fa0051b73b](https://linux-hardware.org/?probe=fa0051b73b) | Dec 02, 2021 |
| Dell          | XPS 17 9710                 | [e34c5d610c](https://linux-hardware.org/?probe=e34c5d610c) | Dec 02, 2021 |
| ASUSTek       | ROG Zephyrus S17 GX703HS... | [32a7506932](https://linux-hardware.org/?probe=32a7506932) | Dec 01, 2021 |
| DukaPC        | Notebook                    | [cfb399153a](https://linux-hardware.org/?probe=cfb399153a) | Dec 01, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [74b0b6dc77](https://linux-hardware.org/?probe=74b0b6dc77) | Dec 01, 2021 |
| Acer          | Swift SF314-43              | [dc17b5db95](https://linux-hardware.org/?probe=dc17b5db95) | Dec 01, 2021 |
| MSI           | Prestige 15 A11SCS          | [1de5756d09](https://linux-hardware.org/?probe=1de5756d09) | Dec 01, 2021 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [a42ba12bea](https://linux-hardware.org/?probe=a42ba12bea) | Dec 01, 2021 |
| Dell          | Inspiron 5770               | [207ec37d70](https://linux-hardware.org/?probe=207ec37d70) | Dec 01, 2021 |
| HP            | ZBook Fury 15.6 inch G8 ... | [0ebc40df56](https://linux-hardware.org/?probe=0ebc40df56) | Dec 01, 2021 |
| Lenovo        | G500 20236                  | [f61434ecc0](https://linux-hardware.org/?probe=f61434ecc0) | Nov 30, 2021 |
| HP            | ProBook 440 G6              | [c819afbd7a](https://linux-hardware.org/?probe=c819afbd7a) | Nov 30, 2021 |
| HP            | ProBook 440 G6              | [a30cacf7ad](https://linux-hardware.org/?probe=a30cacf7ad) | Nov 30, 2021 |
| Timi          | A35S                        | [dbb600147d](https://linux-hardware.org/?probe=dbb600147d) | Nov 30, 2021 |
| Framework     | Laptop                      | [e5f72bfb66](https://linux-hardware.org/?probe=e5f72bfb66) | Nov 30, 2021 |
| Dell          | Latitude 5420               | [b0f561b8a8](https://linux-hardware.org/?probe=b0f561b8a8) | Nov 30, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [29a3dcf41b](https://linux-hardware.org/?probe=29a3dcf41b) | Nov 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ae6614d6fb](https://linux-hardware.org/?probe=ae6614d6fb) | Nov 29, 2021 |
| Sony          | SVE1713Y1EB                 | [317b686b33](https://linux-hardware.org/?probe=317b686b33) | Nov 29, 2021 |
| Acer          | Aspire 5560                 | [db900fbb00](https://linux-hardware.org/?probe=db900fbb00) | Nov 29, 2021 |
| Acer          | Aspire A315-57G             | [cfc036a421](https://linux-hardware.org/?probe=cfc036a421) | Nov 29, 2021 |
| Packard Be... | EasyNote ENLG81BA           | [c596ffcab5](https://linux-hardware.org/?probe=c596ffcab5) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [3a85954b66](https://linux-hardware.org/?probe=3a85954b66) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [5271c46262](https://linux-hardware.org/?probe=5271c46262) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [dddc3d3a11](https://linux-hardware.org/?probe=dddc3d3a11) | Nov 29, 2021 |
| Lenovo        | G500 20236                  | [e97bbbd7a9](https://linux-hardware.org/?probe=e97bbbd7a9) | Nov 29, 2021 |
| Panasonic     | CF-19RDRAMGA                | [5aaebfbf19](https://linux-hardware.org/?probe=5aaebfbf19) | Nov 29, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [fb633e3cb9](https://linux-hardware.org/?probe=fb633e3cb9) | Nov 29, 2021 |
| Samsung       | R520/R522/R620              | [babd307b08](https://linux-hardware.org/?probe=babd307b08) | Nov 29, 2021 |
| Dell          | Inspiron 15-3567            | [2ae4de7517](https://linux-hardware.org/?probe=2ae4de7517) | Nov 29, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [4aa9def017](https://linux-hardware.org/?probe=4aa9def017) | Nov 29, 2021 |
| Acer          | Aspire A515-56              | [b0ed9bece9](https://linux-hardware.org/?probe=b0ed9bece9) | Nov 28, 2021 |
| HP            | EliteBook 845 G8 Noteboo... | [8d962864f8](https://linux-hardware.org/?probe=8d962864f8) | Nov 28, 2021 |
| Lenovo        | G780 2182                   | [2eeaf69158](https://linux-hardware.org/?probe=2eeaf69158) | Nov 28, 2021 |
| Razer         | Blade Stealth               | [54acf9844b](https://linux-hardware.org/?probe=54acf9844b) | Nov 28, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [5e38544a06](https://linux-hardware.org/?probe=5e38544a06) | Nov 28, 2021 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [1a717e5780](https://linux-hardware.org/?probe=1a717e5780) | Nov 28, 2021 |
| Dell          | XPS 15 9570                 | [ee3aa93d09](https://linux-hardware.org/?probe=ee3aa93d09) | Nov 28, 2021 |
| Acer          | Aspire A315-51              | [397f62191b](https://linux-hardware.org/?probe=397f62191b) | Nov 28, 2021 |
| Apple         | MacBook7,1                  | [22e54de439](https://linux-hardware.org/?probe=22e54de439) | Nov 27, 2021 |
| HP            | ProBook 450 G5              | [dd2b422dd8](https://linux-hardware.org/?probe=dd2b422dd8) | Nov 27, 2021 |
| Acer          | Swift SF314-42              | [c5b8c42409](https://linux-hardware.org/?probe=c5b8c42409) | Nov 27, 2021 |
| PC Special... | X170KM-G                    | [6321e2900b](https://linux-hardware.org/?probe=6321e2900b) | Nov 27, 2021 |
| Packard Be... | EasyNote ENLG81BA           | [f85f2dbd4e](https://linux-hardware.org/?probe=f85f2dbd4e) | Nov 27, 2021 |
| Packard Be... | EasyNote ENLG81BA           | [3fcadd0f73](https://linux-hardware.org/?probe=3fcadd0f73) | Nov 27, 2021 |
| Dell          | Precision 7530              | [2b64eebf55](https://linux-hardware.org/?probe=2b64eebf55) | Nov 27, 2021 |
| HP            | ProBook 4540s               | [f047b9db0a](https://linux-hardware.org/?probe=f047b9db0a) | Nov 27, 2021 |
| HP            | ProBook 4540s               | [d8d17c1820](https://linux-hardware.org/?probe=d8d17c1820) | Nov 27, 2021 |
| Lenovo        | G500 20236                  | [c1dd144b77](https://linux-hardware.org/?probe=c1dd144b77) | Nov 27, 2021 |
| HP            | EliteBook 745 G3            | [92968d4a23](https://linux-hardware.org/?probe=92968d4a23) | Nov 27, 2021 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [50e118bf49](https://linux-hardware.org/?probe=50e118bf49) | Nov 27, 2021 |
| HP            | Laptop 15z-ef2xxx           | [8acaaafb63](https://linux-hardware.org/?probe=8acaaafb63) | Nov 27, 2021 |
| Lenovo        | G780                        | [ffeaa607f9](https://linux-hardware.org/?probe=ffeaa607f9) | Nov 27, 2021 |
| Lenovo        | G780                        | [26ea5410e6](https://linux-hardware.org/?probe=26ea5410e6) | Nov 27, 2021 |
| Dell          | XPS 13 9310                 | [c3abf33b86](https://linux-hardware.org/?probe=c3abf33b86) | Nov 27, 2021 |
| Dell          | XPS 13 9310                 | [87c80403ae](https://linux-hardware.org/?probe=87c80403ae) | Nov 27, 2021 |
| Lenovo        | ThinkPad T510 43494JG       | [3564b21c35](https://linux-hardware.org/?probe=3564b21c35) | Nov 26, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [8a5475fd42](https://linux-hardware.org/?probe=8a5475fd42) | Nov 26, 2021 |
| Dell          | Latitude D830               | [080fac6354](https://linux-hardware.org/?probe=080fac6354) | Nov 26, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | [fbec23b579](https://linux-hardware.org/?probe=fbec23b579) | Nov 26, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [9240ce23bd](https://linux-hardware.org/?probe=9240ce23bd) | Nov 26, 2021 |
| Notebook      | PCX0DX                      | [dd551e6aad](https://linux-hardware.org/?probe=dd551e6aad) | Nov 26, 2021 |
| Apple         | MacBookPro8,1               | [a0b9aec393](https://linux-hardware.org/?probe=a0b9aec393) | Nov 26, 2021 |
| Apple         | MacBookPro8,1               | [62a1aeadc4](https://linux-hardware.org/?probe=62a1aeadc4) | Nov 26, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [5a1e505112](https://linux-hardware.org/?probe=5a1e505112) | Nov 25, 2021 |
| Medion        | P15648                      | [1328e63002](https://linux-hardware.org/?probe=1328e63002) | Nov 25, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [dea62ab6ef](https://linux-hardware.org/?probe=dea62ab6ef) | Nov 25, 2021 |
| Lenovo        | ThinkPad Edge E431 62779... | [1ec79ee5e6](https://linux-hardware.org/?probe=1ec79ee5e6) | Nov 25, 2021 |
| ASUSTek       | X751LN                      | [2c8e1bfecd](https://linux-hardware.org/?probe=2c8e1bfecd) | Nov 25, 2021 |
| Dell          | Vostro 5402                 | [a10a19ecfb](https://linux-hardware.org/?probe=a10a19ecfb) | Nov 25, 2021 |
| Dell          | Latitude 5520               | [6fae6c9e46](https://linux-hardware.org/?probe=6fae6c9e46) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXXW                   | [806d1fa87a](https://linux-hardware.org/?probe=806d1fa87a) | Nov 25, 2021 |
| Dell          | Inspiron 5593               | [fb416125d9](https://linux-hardware.org/?probe=fb416125d9) | Nov 25, 2021 |
| Jemper        | EZPAD WS_reserve            | [de173db361](https://linux-hardware.org/?probe=de173db361) | Nov 25, 2021 |
| Fujitsu       | LIFEBOOK E751               | [3f1db85e8a](https://linux-hardware.org/?probe=3f1db85e8a) | Nov 25, 2021 |
| Dell          | Latitude 7420               | [648247b3cc](https://linux-hardware.org/?probe=648247b3cc) | Nov 24, 2021 |
| Toshiba       | Satellite Pro C850-1GU      | [46a6f52122](https://linux-hardware.org/?probe=46a6f52122) | Nov 24, 2021 |
| ASUSTek       | UX331UA                     | [7aee71ceed](https://linux-hardware.org/?probe=7aee71ceed) | Nov 24, 2021 |
| Lenovo        | ThinkPad W530 2447GW3       | [893bad1753](https://linux-hardware.org/?probe=893bad1753) | Nov 24, 2021 |
| Chuwi         | GemiBook Pro                | [1dc5d193a3](https://linux-hardware.org/?probe=1dc5d193a3) | Nov 24, 2021 |
| Dell          | XPS 17 9710                 | [c97bbaf0c5](https://linux-hardware.org/?probe=c97bbaf0c5) | Nov 24, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [5632c40eac](https://linux-hardware.org/?probe=5632c40eac) | Nov 24, 2021 |
| Lenovo        | ThinkPad X230 23252FG       | [35508b1562](https://linux-hardware.org/?probe=35508b1562) | Nov 24, 2021 |
| Dell          | Latitude 5421               | [4f39514ffc](https://linux-hardware.org/?probe=4f39514ffc) | Nov 24, 2021 |
| Acer          | Nitro AN515-54              | [bf1ef9f271](https://linux-hardware.org/?probe=bf1ef9f271) | Nov 24, 2021 |
| Dell          | XPS 17 9710                 | [fb1cce8ab4](https://linux-hardware.org/?probe=fb1cce8ab4) | Nov 24, 2021 |
| Dell          | Inspiron 5570               | [774f732180](https://linux-hardware.org/?probe=774f732180) | Nov 24, 2021 |
| Dell          | XPS 15 9560                 | [ed470afd8a](https://linux-hardware.org/?probe=ed470afd8a) | Nov 24, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2fc0deb231](https://linux-hardware.org/?probe=2fc0deb231) | Nov 24, 2021 |
| Dell          | XPS 15 9570                 | [524d775cd9](https://linux-hardware.org/?probe=524d775cd9) | Nov 24, 2021 |
| Dell          | Inspiron 5558               | [772ca16963](https://linux-hardware.org/?probe=772ca16963) | Nov 23, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [30e9ef2236](https://linux-hardware.org/?probe=30e9ef2236) | Nov 23, 2021 |
| HP            | ProBook 440 G7              | [7863ad05f4](https://linux-hardware.org/?probe=7863ad05f4) | Nov 23, 2021 |
| Toshiba       | TECRA R940                  | [778fe1dfcc](https://linux-hardware.org/?probe=778fe1dfcc) | Nov 23, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [35b7ff3a68](https://linux-hardware.org/?probe=35b7ff3a68) | Nov 23, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [ec94d40844](https://linux-hardware.org/?probe=ec94d40844) | Nov 23, 2021 |
| Toshiba       | Satellite C855-1JD          | [9ead13671d](https://linux-hardware.org/?probe=9ead13671d) | Nov 22, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f1620f693d](https://linux-hardware.org/?probe=f1620f693d) | Nov 22, 2021 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [d0a08a7a23](https://linux-hardware.org/?probe=d0a08a7a23) | Nov 22, 2021 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [507c380abb](https://linux-hardware.org/?probe=507c380abb) | Nov 22, 2021 |
| Lenovo        | ThinkPad T520 4243CJ2       | [418a8830c3](https://linux-hardware.org/?probe=418a8830c3) | Nov 22, 2021 |
| HP            | 550                         | [bbbca1ed06](https://linux-hardware.org/?probe=bbbca1ed06) | Nov 22, 2021 |
| Lenovo        | V145-15AST 81MT             | [941396daf4](https://linux-hardware.org/?probe=941396daf4) | Nov 22, 2021 |
| ASUSTek       | X751LN                      | [50d304e970](https://linux-hardware.org/?probe=50d304e970) | Nov 22, 2021 |
| Dell          | Inspiron 5558               | [bae9fdec30](https://linux-hardware.org/?probe=bae9fdec30) | Nov 22, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [3964ebaadd](https://linux-hardware.org/?probe=3964ebaadd) | Nov 22, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [61308173d9](https://linux-hardware.org/?probe=61308173d9) | Nov 22, 2021 |
| Exo           | Smart Serie M               | [cbf705cf51](https://linux-hardware.org/?probe=cbf705cf51) | Nov 22, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [af11f87974](https://linux-hardware.org/?probe=af11f87974) | Nov 22, 2021 |
| Dell          | XPS 15 9510                 | [c89373bfad](https://linux-hardware.org/?probe=c89373bfad) | Nov 21, 2021 |
| Apple         | MacBookPro12,1              | [685ef4de17](https://linux-hardware.org/?probe=685ef4de17) | Nov 21, 2021 |
| Dell          | XPS 15 9570                 | [09557621d2](https://linux-hardware.org/?probe=09557621d2) | Nov 21, 2021 |
| Apple         | MacBookPro14,3              | [a5935d753d](https://linux-hardware.org/?probe=a5935d753d) | Nov 21, 2021 |
| Lenovo        | ThinkPad T430 2349DS1       | [1ad2d01280](https://linux-hardware.org/?probe=1ad2d01280) | Nov 21, 2021 |
| Dell          | Inspiron 1545               | [11710ca51d](https://linux-hardware.org/?probe=11710ca51d) | Nov 21, 2021 |
| Dell          | Inspiron 5570               | [d73b7c147b](https://linux-hardware.org/?probe=d73b7c147b) | Nov 21, 2021 |
| ASUSTek       | N751JK                      | [f64a3f1fc2](https://linux-hardware.org/?probe=f64a3f1fc2) | Nov 20, 2021 |
| HP            | ZBook 17                    | [dddc9c534d](https://linux-hardware.org/?probe=dddc9c534d) | Nov 20, 2021 |
| HP            | G62                         | [7659359d92](https://linux-hardware.org/?probe=7659359d92) | Nov 20, 2021 |
| HP            | Unknown                     | [23dc38032d](https://linux-hardware.org/?probe=23dc38032d) | Nov 20, 2021 |
| HP            | G62                         | [5e62f156d2](https://linux-hardware.org/?probe=5e62f156d2) | Nov 20, 2021 |
| Dell          | Latitude E5400              | [062c0d6df1](https://linux-hardware.org/?probe=062c0d6df1) | Nov 20, 2021 |
| Dell          | Inspiron 7577               | [06399f0deb](https://linux-hardware.org/?probe=06399f0deb) | Nov 20, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [04fa536869](https://linux-hardware.org/?probe=04fa536869) | Nov 20, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [097de81570](https://linux-hardware.org/?probe=097de81570) | Nov 20, 2021 |
| HUAWEI        | KLVL-WXX9                   | [0bccbf892a](https://linux-hardware.org/?probe=0bccbf892a) | Nov 19, 2021 |
| HUAWEI        | KLVL-WXX9                   | [7a4c2319fa](https://linux-hardware.org/?probe=7a4c2319fa) | Nov 19, 2021 |
| HUAWEI        | HVY-WXX9                    | [5825bb233c](https://linux-hardware.org/?probe=5825bb233c) | Nov 19, 2021 |
| HP            | OMEN by Laptop              | [0b8f3a5da9](https://linux-hardware.org/?probe=0b8f3a5da9) | Nov 19, 2021 |
| Dell          | Latitude E4300              | [7bb479a55e](https://linux-hardware.org/?probe=7bb479a55e) | Nov 19, 2021 |
| HP            | OMEN by Laptop              | [dc7136f307](https://linux-hardware.org/?probe=dc7136f307) | Nov 19, 2021 |
| Acer          | Aspire E5-551               | [7ae0f74c7d](https://linux-hardware.org/?probe=7ae0f74c7d) | Nov 19, 2021 |
| HP            | Pavilion Laptop             | [ab2e04130f](https://linux-hardware.org/?probe=ab2e04130f) | Nov 19, 2021 |
| Dell          | Latitude 3510               | [9d4db04732](https://linux-hardware.org/?probe=9d4db04732) | Nov 19, 2021 |
| ASUSTek       | X401A1                      | [fa9b9fa473](https://linux-hardware.org/?probe=fa9b9fa473) | Nov 19, 2021 |
| Sony          | VPCF130FD                   | [e4468538f5](https://linux-hardware.org/?probe=e4468538f5) | Nov 19, 2021 |
| System76      | Gazelle                     | [939b96106b](https://linux-hardware.org/?probe=939b96106b) | Nov 19, 2021 |
| Acer          | Swift SF314-42              | [264bebca57](https://linux-hardware.org/?probe=264bebca57) | Nov 18, 2021 |
| Framework     | Laptop                      | [0d635923b5](https://linux-hardware.org/?probe=0d635923b5) | Nov 18, 2021 |
| HP            | Laptop 14-fq1xxx            | [2d996858ab](https://linux-hardware.org/?probe=2d996858ab) | Nov 18, 2021 |
| Lenovo        | ThinkPad X220 4291CA0       | [94cebfa456](https://linux-hardware.org/?probe=94cebfa456) | Nov 18, 2021 |
| Packard Be... | EasyNote LJ75               | [7ec0fdf75d](https://linux-hardware.org/?probe=7ec0fdf75d) | Nov 18, 2021 |
| Timi          | RedmiBook 16                | [0b9130726c](https://linux-hardware.org/?probe=0b9130726c) | Nov 18, 2021 |
| HP            | ProBook 4510s               | [46c61312c4](https://linux-hardware.org/?probe=46c61312c4) | Nov 18, 2021 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [80168c4938](https://linux-hardware.org/?probe=80168c4938) | Nov 18, 2021 |
| Framework     | Laptop                      | [3772cd7a6e](https://linux-hardware.org/?probe=3772cd7a6e) | Nov 17, 2021 |
| Acer          | TravelMate 6292             | [0acf22106c](https://linux-hardware.org/?probe=0acf22106c) | Nov 17, 2021 |
| Dell          | Latitude 5520               | [e398be8e26](https://linux-hardware.org/?probe=e398be8e26) | Nov 17, 2021 |
| Dell          | XPS 15 9500                 | [a77e5494bf](https://linux-hardware.org/?probe=a77e5494bf) | Nov 17, 2021 |
| Dell          | XPS 15 9500                 | [526d5c7a21](https://linux-hardware.org/?probe=526d5c7a21) | Nov 17, 2021 |
| HUAWEI        | KLVL-WXX9                   | [c80aeaf7b0](https://linux-hardware.org/?probe=c80aeaf7b0) | Nov 17, 2021 |
| Lenovo        | ThinkPad Edge E431 62779... | [30520d2f19](https://linux-hardware.org/?probe=30520d2f19) | Nov 17, 2021 |
| Dell          | XPS 15 9500                 | [be45eea786](https://linux-hardware.org/?probe=be45eea786) | Nov 17, 2021 |
| Dell          | Inspiron 7586               | [188923fc9c](https://linux-hardware.org/?probe=188923fc9c) | Nov 17, 2021 |
| HP            | ProBook 4510s               | [cf53b2e2db](https://linux-hardware.org/?probe=cf53b2e2db) | Nov 17, 2021 |
| Positivo      | Mobile                      | [9b83c09ad3](https://linux-hardware.org/?probe=9b83c09ad3) | Nov 17, 2021 |
| HP            | Laptop 15-db1xxx            | [cd32f937e9](https://linux-hardware.org/?probe=cd32f937e9) | Nov 17, 2021 |
| HP            | ProBook 650 G1              | [07597b6850](https://linux-hardware.org/?probe=07597b6850) | Nov 16, 2021 |
| HP            | ProBook 650 G1              | [21f9af6edb](https://linux-hardware.org/?probe=21f9af6edb) | Nov 16, 2021 |
| Dell          | Latitude E7470              | [0358863974](https://linux-hardware.org/?probe=0358863974) | Nov 16, 2021 |
| HP            | ProBook 4520s               | [1d9f0ec825](https://linux-hardware.org/?probe=1d9f0ec825) | Nov 16, 2021 |
| HP            | ProBook 4520s               | [1fb5221e00](https://linux-hardware.org/?probe=1fb5221e00) | Nov 16, 2021 |
| Medion        | P6630                       | [235a9a3ced](https://linux-hardware.org/?probe=235a9a3ced) | Nov 16, 2021 |
| Apple         | MacBook4,1                  | [f9ee489abd](https://linux-hardware.org/?probe=f9ee489abd) | Nov 16, 2021 |
| ASUSTek       | X540YA                      | [72e7bebf84](https://linux-hardware.org/?probe=72e7bebf84) | Nov 16, 2021 |
| ASUSTek       | X540YA                      | [39d8ea222a](https://linux-hardware.org/?probe=39d8ea222a) | Nov 16, 2021 |
| Medion        | Akoya E6240T                | [9f7f0a3a96](https://linux-hardware.org/?probe=9f7f0a3a96) | Nov 16, 2021 |
| HP            | Laptop 15-bs0xx             | [d33bc4ef7c](https://linux-hardware.org/?probe=d33bc4ef7c) | Nov 16, 2021 |
| HP            | Laptop 15-bs0xx             | [048cf14d2f](https://linux-hardware.org/?probe=048cf14d2f) | Nov 16, 2021 |
| HP            | 15                          | [43b117b7a1](https://linux-hardware.org/?probe=43b117b7a1) | Nov 16, 2021 |
| ASUSTek       | X580VD                      | [3c83607d76](https://linux-hardware.org/?probe=3c83607d76) | Nov 16, 2021 |
| Lenovo        | IdeaPad 300-14IBR 80M2      | [34fb650910](https://linux-hardware.org/?probe=34fb650910) | Nov 16, 2021 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [10a3cb9d12](https://linux-hardware.org/?probe=10a3cb9d12) | Nov 15, 2021 |
| Dell          | XPS 13 9305                 | [efa5ec3ed4](https://linux-hardware.org/?probe=efa5ec3ed4) | Nov 15, 2021 |
| HP            | Pavilion dv5                | [ec4890a33b](https://linux-hardware.org/?probe=ec4890a33b) | Nov 15, 2021 |
| Lenovo        | ThinkPad 25 20K70000MX      | [86d3ea8b6a](https://linux-hardware.org/?probe=86d3ea8b6a) | Nov 15, 2021 |
| HP            | 15                          | [d1c144c887](https://linux-hardware.org/?probe=d1c144c887) | Nov 15, 2021 |
| Dell          | Vostro 3400                 | [f6ba3e3359](https://linux-hardware.org/?probe=f6ba3e3359) | Nov 15, 2021 |
| Lenovo        | ThinkPad Edge E431 62779... | [f998266e76](https://linux-hardware.org/?probe=f998266e76) | Nov 15, 2021 |
| Acer          | Nitro AN515-54              | [a9d34635cf](https://linux-hardware.org/?probe=a9d34635cf) | Nov 15, 2021 |
| HP            | ProBook 455 G4              | [e7976c31a1](https://linux-hardware.org/?probe=e7976c31a1) | Nov 15, 2021 |
| HP            | Pavilion dv5                | [4ddaeca48c](https://linux-hardware.org/?probe=4ddaeca48c) | Nov 15, 2021 |
| Dell          | Latitude E7440              | [60d06b6cfe](https://linux-hardware.org/?probe=60d06b6cfe) | Nov 15, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HM    | [8809001b3c](https://linux-hardware.org/?probe=8809001b3c) | Nov 14, 2021 |
| HP            | EliteBook 835 G8 Noteboo... | [2b9e3a56a5](https://linux-hardware.org/?probe=2b9e3a56a5) | Nov 14, 2021 |
| HP            | Pavilion Notebook           | [d2eb7d0dc2](https://linux-hardware.org/?probe=d2eb7d0dc2) | Nov 14, 2021 |
| Dell          | XPS 13 9310                 | [0f6c2b21cf](https://linux-hardware.org/?probe=0f6c2b21cf) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DV_TUF50... | [3559f352cf](https://linux-hardware.org/?probe=3559f352cf) | Nov 14, 2021 |
| HP            | ProBook 455 G6              | [2a37f0ed64](https://linux-hardware.org/?probe=2a37f0ed64) | Nov 14, 2021 |
| ASUSTek       | X540SA                      | [1292ab6f15](https://linux-hardware.org/?probe=1292ab6f15) | Nov 14, 2021 |
| Dell          | Latitude E7270              | [b462d15a6b](https://linux-hardware.org/?probe=b462d15a6b) | Nov 14, 2021 |
| Acer          | Aspire E5-553G              | [b22df8f53d](https://linux-hardware.org/?probe=b22df8f53d) | Nov 14, 2021 |
| Acer          | Aspire E5-553G              | [93d20530a1](https://linux-hardware.org/?probe=93d20530a1) | Nov 14, 2021 |
| Timi          | A35S                        | [68a0b2e6bd](https://linux-hardware.org/?probe=68a0b2e6bd) | Nov 14, 2021 |
| HP            | Pavilion Notebook           | [1b93110fd9](https://linux-hardware.org/?probe=1b93110fd9) | Nov 13, 2021 |
| ASUSTek       | X540SA                      | [463e1f35a9](https://linux-hardware.org/?probe=463e1f35a9) | Nov 13, 2021 |
| HP            | Stream Laptop 14-ax0XX      | [3bd51f200e](https://linux-hardware.org/?probe=3bd51f200e) | Nov 13, 2021 |
| Lenovo        | Yoga710-15ISK 80U0          | [4bbd057aa1](https://linux-hardware.org/?probe=4bbd057aa1) | Nov 13, 2021 |
| Lenovo        | IdeaPad 720S-14IKB 80XC     | [d0f383a016](https://linux-hardware.org/?probe=d0f383a016) | Nov 13, 2021 |
| Apple         | MacBook7,1                  | [b898d5a09c](https://linux-hardware.org/?probe=b898d5a09c) | Nov 13, 2021 |
| Dell          | XPS 13 9310                 | [01c20231f2](https://linux-hardware.org/?probe=01c20231f2) | Nov 13, 2021 |
| HP            | Laptop 14-fq1xxx            | [cc7fba67fd](https://linux-hardware.org/?probe=cc7fba67fd) | Nov 12, 2021 |
| HP            | Pavilion Notebook           | [0d96ccbe28](https://linux-hardware.org/?probe=0d96ccbe28) | Nov 12, 2021 |
| HP            | ProBook 450 G5              | [984b162f45](https://linux-hardware.org/?probe=984b162f45) | Nov 12, 2021 |
| Dell          | XPS 15 9570                 | [abb7877540](https://linux-hardware.org/?probe=abb7877540) | Nov 12, 2021 |
| Dell          | Latitude E6520              | [e795da8420](https://linux-hardware.org/?probe=e795da8420) | Nov 12, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [9ba065b607](https://linux-hardware.org/?probe=9ba065b607) | Nov 12, 2021 |
| ASUSTek       | N501VW                      | [8701c7e1c8](https://linux-hardware.org/?probe=8701c7e1c8) | Nov 12, 2021 |
| ASUSTek       | N501VW                      | [fe236eaa88](https://linux-hardware.org/?probe=fe236eaa88) | Nov 12, 2021 |
| Acer          | Aspire 5755G                | [23a8df3372](https://linux-hardware.org/?probe=23a8df3372) | Nov 12, 2021 |
| Dell          | Inspiron 15-3573            | [0c659e62e6](https://linux-hardware.org/?probe=0c659e62e6) | Nov 12, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [9d3272960f](https://linux-hardware.org/?probe=9d3272960f) | Nov 12, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [31e2521af4](https://linux-hardware.org/?probe=31e2521af4) | Nov 12, 2021 |
| Acer          | Swift SF315-41              | [744b18ebd1](https://linux-hardware.org/?probe=744b18ebd1) | Nov 12, 2021 |
| HP            | OMEN by Laptop              | [207d9a7985](https://linux-hardware.org/?probe=207d9a7985) | Nov 12, 2021 |
| ASUSTek       | GL553VD                     | [d152d41284](https://linux-hardware.org/?probe=d152d41284) | Nov 12, 2021 |
| Dell          | Latitude E6410              | [08fde74c0e](https://linux-hardware.org/?probe=08fde74c0e) | Nov 12, 2021 |
| Dell          | Precision M4700             | [8d8a2dcc96](https://linux-hardware.org/?probe=8d8a2dcc96) | Nov 12, 2021 |
| Dell          | Inspiron 5570               | [be0e281ff8](https://linux-hardware.org/?probe=be0e281ff8) | Nov 12, 2021 |
| Dell          | XPS 15 9570                 | [7d4e321511](https://linux-hardware.org/?probe=7d4e321511) | Nov 12, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [fdb480d5f4](https://linux-hardware.org/?probe=fdb480d5f4) | Nov 12, 2021 |
| HP            | Pavilion g6                 | [0332d112e9](https://linux-hardware.org/?probe=0332d112e9) | Nov 12, 2021 |
| Dell          | Latitude D630               | [e034675b55](https://linux-hardware.org/?probe=e034675b55) | Nov 12, 2021 |
| Dell          | Latitude D630               | [8227457c3b](https://linux-hardware.org/?probe=8227457c3b) | Nov 12, 2021 |
| HP            | ProBook 455 G6              | [6045aa2b3a](https://linux-hardware.org/?probe=6045aa2b3a) | Nov 12, 2021 |
| Dell          | XPS 15 9570                 | [d22d46f646](https://linux-hardware.org/?probe=d22d46f646) | Nov 11, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [2f75d80207](https://linux-hardware.org/?probe=2f75d80207) | Nov 11, 2021 |
| Lenovo        | ThinkPad Edge E431 62779... | [0d059f1720](https://linux-hardware.org/?probe=0d059f1720) | Nov 11, 2021 |
| Notebook      | P64_HJ,HK1                  | [f15a333240](https://linux-hardware.org/?probe=f15a333240) | Nov 11, 2021 |
| win elemen... | MoreFine S500+              | [ace08cf199](https://linux-hardware.org/?probe=ace08cf199) | Nov 11, 2021 |
| win elemen... | MoreFine S500+              | [0e31d4b6fa](https://linux-hardware.org/?probe=0e31d4b6fa) | Nov 11, 2021 |
| Packard Be... | EasyNote TE69BM             | [5041e2b272](https://linux-hardware.org/?probe=5041e2b272) | Nov 10, 2021 |
| Dell          | Inspiron 15 7510            | [ba69916825](https://linux-hardware.org/?probe=ba69916825) | Nov 10, 2021 |
| Packard Be... | EasyNote TE69BM             | [fcb5b11b8c](https://linux-hardware.org/?probe=fcb5b11b8c) | Nov 10, 2021 |
| Timi          | A35                         | [f8818e4273](https://linux-hardware.org/?probe=f8818e4273) | Nov 10, 2021 |
| HP            | ProBook x360 11 G5 EE       | [ec64c11055](https://linux-hardware.org/?probe=ec64c11055) | Nov 10, 2021 |
| ASUSTek       | X55A                        | [a55961748f](https://linux-hardware.org/?probe=a55961748f) | Nov 10, 2021 |
| ASUSTek       | X55A                        | [8c59513ced](https://linux-hardware.org/?probe=8c59513ced) | Nov 10, 2021 |
| Dell          | Inspiron 5558               | [c4e563c1ab](https://linux-hardware.org/?probe=c4e563c1ab) | Nov 10, 2021 |
| Sony          | VPCCB25FX                   | [c42c92c898](https://linux-hardware.org/?probe=c42c92c898) | Nov 09, 2021 |
| Lenovo        | ThinkPad L450 20DTCTO1WW    | [ad9b4ec784](https://linux-hardware.org/?probe=ad9b4ec784) | Nov 09, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [aad3e601ad](https://linux-hardware.org/?probe=aad3e601ad) | Nov 09, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [dd5b331a4c](https://linux-hardware.org/?probe=dd5b331a4c) | Nov 09, 2021 |
| Dell          | Inspiron 1764               | [319a6efc5a](https://linux-hardware.org/?probe=319a6efc5a) | Nov 09, 2021 |
| Dell          | XPS 13 9310                 | [94b138fb37](https://linux-hardware.org/?probe=94b138fb37) | Nov 09, 2021 |
| Dell          | XPS 13 9310                 | [3f47def69d](https://linux-hardware.org/?probe=3f47def69d) | Nov 09, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [94448a14f7](https://linux-hardware.org/?probe=94448a14f7) | Nov 09, 2021 |
| Timi          | A30                         | [63583fcf04](https://linux-hardware.org/?probe=63583fcf04) | Nov 09, 2021 |
| HP            | ProBook 445 G7              | [eecec0bcf8](https://linux-hardware.org/?probe=eecec0bcf8) | Nov 08, 2021 |
| HP            | ProBook 445 G7              | [cb60701cba](https://linux-hardware.org/?probe=cb60701cba) | Nov 08, 2021 |
| Sony          | VPCEL2S1E                   | [00df9cdeb3](https://linux-hardware.org/?probe=00df9cdeb3) | Nov 08, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [76de163bc3](https://linux-hardware.org/?probe=76de163bc3) | Nov 08, 2021 |
| HP            | Pavilion dv7                | [a19e73fd27](https://linux-hardware.org/?probe=a19e73fd27) | Nov 08, 2021 |
| Dell          | XPS 13 9310                 | [0c99cea4ba](https://linux-hardware.org/?probe=0c99cea4ba) | Nov 07, 2021 |
| Notebook      | W54_55SU1,SUW               | [a0e93f5294](https://linux-hardware.org/?probe=a0e93f5294) | Nov 07, 2021 |
| Toshiba       | Satellite Pro S300          | [a9dd74e832](https://linux-hardware.org/?probe=a9dd74e832) | Nov 07, 2021 |
| Acer          | Swift SF314-43              | [8540ada375](https://linux-hardware.org/?probe=8540ada375) | Nov 07, 2021 |
| Jumper        | EZbook                      | [d9f2b0f1b2](https://linux-hardware.org/?probe=d9f2b0f1b2) | Nov 07, 2021 |
| Jumper        | EZbook                      | [2752cc575b](https://linux-hardware.org/?probe=2752cc575b) | Nov 07, 2021 |
| Dell          | Inspiron 5558               | [94c8a2df98](https://linux-hardware.org/?probe=94c8a2df98) | Nov 07, 2021 |
| Dell          | XPS 15 9510                 | [6f9b7bffd1](https://linux-hardware.org/?probe=6f9b7bffd1) | Nov 06, 2021 |
| Dell          | G15 5515                    | [1e5e0ab274](https://linux-hardware.org/?probe=1e5e0ab274) | Nov 06, 2021 |
| Dell          | Inspiron 15-3567            | [630a9144f1](https://linux-hardware.org/?probe=630a9144f1) | Nov 06, 2021 |
| PC Special... | W94_95_97PU                 | [2c6e08bf5d](https://linux-hardware.org/?probe=2c6e08bf5d) | Nov 06, 2021 |
| Toshiba       | Dakar10FW8                  | [ca1da89f22](https://linux-hardware.org/?probe=ca1da89f22) | Nov 06, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [999eb9102a](https://linux-hardware.org/?probe=999eb9102a) | Nov 06, 2021 |
| HP            | ProBook 440 G4              | [e0b2ef1603](https://linux-hardware.org/?probe=e0b2ef1603) | Nov 06, 2021 |
| HUAWEI        | MACHD-WXX9                  | [364fb5b6b7](https://linux-hardware.org/?probe=364fb5b6b7) | Nov 06, 2021 |
| Dell          | Vostro 3478                 | [f88e5eec69](https://linux-hardware.org/?probe=f88e5eec69) | Nov 05, 2021 |
| Dell          | Vostro 3478                 | [8174188077](https://linux-hardware.org/?probe=8174188077) | Nov 05, 2021 |
| HP            | ProBook 430 G4              | [d5ff59ee05](https://linux-hardware.org/?probe=d5ff59ee05) | Nov 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [cf7dc59b1a](https://linux-hardware.org/?probe=cf7dc59b1a) | Nov 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [aad7742ae7](https://linux-hardware.org/?probe=aad7742ae7) | Nov 05, 2021 |
| Dell          | Latitude 7390 2-in-1        | [4b1fcf5e24](https://linux-hardware.org/?probe=4b1fcf5e24) | Nov 05, 2021 |
| HP            | Laptop 15-dw3xxx            | [966b61331a](https://linux-hardware.org/?probe=966b61331a) | Nov 05, 2021 |
| HP            | Laptop 15-dw3xxx            | [e1c9be9f1d](https://linux-hardware.org/?probe=e1c9be9f1d) | Nov 05, 2021 |
| Dell          | XPS 13 9300                 | [babbbc5e56](https://linux-hardware.org/?probe=babbbc5e56) | Nov 05, 2021 |
| Avell High... | A70 LIV                     | [b4d7b0e021](https://linux-hardware.org/?probe=b4d7b0e021) | Nov 05, 2021 |
| Lenovo        | G40-80 80E4                 | [57b9418a9c](https://linux-hardware.org/?probe=57b9418a9c) | Nov 05, 2021 |
| HP            | EliteBook 8540p             | [048c1d5d30](https://linux-hardware.org/?probe=048c1d5d30) | Nov 05, 2021 |
| HUAWEI        | KLVD-WXX9                   | [b69ad25203](https://linux-hardware.org/?probe=b69ad25203) | Nov 04, 2021 |
| HP            | Laptop 15-dw1xxx            | [07b1660d10](https://linux-hardware.org/?probe=07b1660d10) | Nov 04, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [701adbe249](https://linux-hardware.org/?probe=701adbe249) | Nov 04, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [c221fbfc80](https://linux-hardware.org/?probe=c221fbfc80) | Nov 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [dc8f8db0fd](https://linux-hardware.org/?probe=dc8f8db0fd) | Nov 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [dc325a808a](https://linux-hardware.org/?probe=dc325a808a) | Nov 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9fe96f497b](https://linux-hardware.org/?probe=9fe96f497b) | Nov 04, 2021 |
| HUAWEI        | HVY-WXX9                    | [c338e7c775](https://linux-hardware.org/?probe=c338e7c775) | Nov 04, 2021 |
| HP            | ProBook 455 G3              | [ccd4bcc603](https://linux-hardware.org/?probe=ccd4bcc603) | Nov 04, 2021 |
| HP            | EliteBook 8540p             | [c7ca645211](https://linux-hardware.org/?probe=c7ca645211) | Nov 04, 2021 |
| Timi          | TM1701                      | [40dc454159](https://linux-hardware.org/?probe=40dc454159) | Nov 03, 2021 |
| Lenovo        | ThinkPad T420 4180ED3       | [dbc9c2369a](https://linux-hardware.org/?probe=dbc9c2369a) | Nov 03, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | [17339fe912](https://linux-hardware.org/?probe=17339fe912) | Nov 03, 2021 |
| HUAWEI        | HVY-WXX9                    | [fdb3a089a2](https://linux-hardware.org/?probe=fdb3a089a2) | Nov 03, 2021 |
| ASUSTek       | X550VX                      | [5718178f4b](https://linux-hardware.org/?probe=5718178f4b) | Nov 03, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [fe34c12d67](https://linux-hardware.org/?probe=fe34c12d67) | Nov 03, 2021 |
| Samsung       | R530/R730                   | [a62fb59972](https://linux-hardware.org/?probe=a62fb59972) | Nov 03, 2021 |
| MOTILE        | M141                        | [00f4ccf1de](https://linux-hardware.org/?probe=00f4ccf1de) | Nov 03, 2021 |
| Acer          | Swift SF314-42              | [07025c7436](https://linux-hardware.org/?probe=07025c7436) | Nov 02, 2021 |
| Dell          | XPS 15 9500                 | [fc7604b4bc](https://linux-hardware.org/?probe=fc7604b4bc) | Nov 02, 2021 |
| Dell          | XPS 15 9500                 | [7f8efd83d8](https://linux-hardware.org/?probe=7f8efd83d8) | Nov 02, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [f5a1f78297](https://linux-hardware.org/?probe=f5a1f78297) | Nov 02, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [5158fb179d](https://linux-hardware.org/?probe=5158fb179d) | Nov 02, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [3296f4587d](https://linux-hardware.org/?probe=3296f4587d) | Nov 02, 2021 |
| Lenovo        | G40-80 80E4                 | [f89ddc0ebd](https://linux-hardware.org/?probe=f89ddc0ebd) | Nov 02, 2021 |
| HP            | Laptop 14-bs0xx             | [3ab642249c](https://linux-hardware.org/?probe=3ab642249c) | Nov 02, 2021 |
| HP            | OMEN by Laptop              | [d5eda0a4df](https://linux-hardware.org/?probe=d5eda0a4df) | Nov 01, 2021 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [638e01b2f1](https://linux-hardware.org/?probe=638e01b2f1) | Nov 01, 2021 |
| Fujitsu       | LIFEBOOK S751               | [0365e0be95](https://linux-hardware.org/?probe=0365e0be95) | Nov 01, 2021 |
| Toshiba       | Satellite U920T             | [2151ed88f7](https://linux-hardware.org/?probe=2151ed88f7) | Nov 01, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DK      | [fdda57d98e](https://linux-hardware.org/?probe=fdda57d98e) | Nov 01, 2021 |
| ASUSTek       | K52F                        | [34a9f3b662](https://linux-hardware.org/?probe=34a9f3b662) | Nov 01, 2021 |
| Dell          | Inspiron 5570               | [ddb12be458](https://linux-hardware.org/?probe=ddb12be458) | Nov 01, 2021 |
| Lenovo        | V14-ARE 82DQ                | [8948989999](https://linux-hardware.org/?probe=8948989999) | Oct 31, 2021 |
| HP            | Laptop 14-bs0xx             | [93c1d9bd4f](https://linux-hardware.org/?probe=93c1d9bd4f) | Oct 31, 2021 |
| HP            | OMEN by Laptop              | [d55ac505b9](https://linux-hardware.org/?probe=d55ac505b9) | Oct 31, 2021 |
| HP            | OMEN by Laptop              | [65a70acf15](https://linux-hardware.org/?probe=65a70acf15) | Oct 31, 2021 |
| Dell          | Inspiron 5558               | [d876caae1e](https://linux-hardware.org/?probe=d876caae1e) | Oct 31, 2021 |
| Apple         | MacBookPro11,1              | [0c24caf245](https://linux-hardware.org/?probe=0c24caf245) | Oct 31, 2021 |
| HP            | Pavilion Notebook           | [9c8bb9558a](https://linux-hardware.org/?probe=9c8bb9558a) | Oct 31, 2021 |
| HP            | Pavilion Laptop 15-cs300    | [bcc27223cc](https://linux-hardware.org/?probe=bcc27223cc) | Oct 31, 2021 |
| HP            | Laptop 14-bs0xx             | [ebc6fe2060](https://linux-hardware.org/?probe=ebc6fe2060) | Oct 31, 2021 |
| Dell          | XPS 15 7590                 | [58e43f0514](https://linux-hardware.org/?probe=58e43f0514) | Oct 31, 2021 |
| Acer          | Swift SF314-43              | [be8229729b](https://linux-hardware.org/?probe=be8229729b) | Oct 31, 2021 |
| HP            | Pavilion dv6                | [2e9d378e76](https://linux-hardware.org/?probe=2e9d378e76) | Oct 31, 2021 |
| Lenovo        | ThinkPad Edge 0578A21       | [570863fd8c](https://linux-hardware.org/?probe=570863fd8c) | Oct 31, 2021 |
| Acer          | Swift SF314-43              | [4881a9a93c](https://linux-hardware.org/?probe=4881a9a93c) | Oct 31, 2021 |
| Lenovo        | ThinkPad T410 2537GH6       | [8b21b7cffe](https://linux-hardware.org/?probe=8b21b7cffe) | Oct 31, 2021 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [ba228b1ed7](https://linux-hardware.org/?probe=ba228b1ed7) | Oct 31, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [f7309ef31a](https://linux-hardware.org/?probe=f7309ef31a) | Oct 30, 2021 |
| MSI           | GT75VR 7RF                  | [edd545a455](https://linux-hardware.org/?probe=edd545a455) | Oct 30, 2021 |
| ASUSTek       | N751JK                      | [739623468a](https://linux-hardware.org/?probe=739623468a) | Oct 30, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [47907aec3e](https://linux-hardware.org/?probe=47907aec3e) | Oct 30, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [0c865ddf24](https://linux-hardware.org/?probe=0c865ddf24) | Oct 30, 2021 |
| Dell          | Latitude E5570              | [d926705b17](https://linux-hardware.org/?probe=d926705b17) | Oct 30, 2021 |
| Dell          | Latitude E5570              | [b8515cfe6b](https://linux-hardware.org/?probe=b8515cfe6b) | Oct 30, 2021 |
| Dell          | Latitude 5490               | [4efdbaeea5](https://linux-hardware.org/?probe=4efdbaeea5) | Oct 30, 2021 |
| Acer          | Swift SF314-511             | [43faa95812](https://linux-hardware.org/?probe=43faa95812) | Oct 30, 2021 |
| Dell          | XPS 17 9700                 | [5e25d50915](https://linux-hardware.org/?probe=5e25d50915) | Oct 30, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | [3802a77d98](https://linux-hardware.org/?probe=3802a77d98) | Oct 29, 2021 |
| Dell          | Inspiron 15-3573            | [141148ec26](https://linux-hardware.org/?probe=141148ec26) | Oct 29, 2021 |
| HP            | Laptop 17z-ca300            | [0071faabac](https://linux-hardware.org/?probe=0071faabac) | Oct 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2b4a1a20d9](https://linux-hardware.org/?probe=2b4a1a20d9) | Oct 29, 2021 |
| Lenovo        | V580c 20160                 | [779684e41d](https://linux-hardware.org/?probe=779684e41d) | Oct 29, 2021 |
| Medion        | Akoya E6240T                | [1a0a5790b3](https://linux-hardware.org/?probe=1a0a5790b3) | Oct 29, 2021 |
| Acer          | Aspire F5-573G              | [9b5832381a](https://linux-hardware.org/?probe=9b5832381a) | Oct 29, 2021 |
| MSI           | GE62 7RD                    | [95616813e6](https://linux-hardware.org/?probe=95616813e6) | Oct 29, 2021 |
| MSI           | GE62 6QF                    | [1c48df3fa2](https://linux-hardware.org/?probe=1c48df3fa2) | Oct 29, 2021 |
| realme        | RMNBXXXX                    | [70b65bbcf8](https://linux-hardware.org/?probe=70b65bbcf8) | Oct 28, 2021 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [75c43f02bf](https://linux-hardware.org/?probe=75c43f02bf) | Oct 28, 2021 |
| Toshiba       | Satellite C75-B             | [fe77011ed7](https://linux-hardware.org/?probe=fe77011ed7) | Oct 28, 2021 |
| Sony          | SVS1312G3EW                 | [7951439c81](https://linux-hardware.org/?probe=7951439c81) | Oct 28, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [9276790a36](https://linux-hardware.org/?probe=9276790a36) | Oct 28, 2021 |
| HP            | ENVY dv6                    | [31ff7dd229](https://linux-hardware.org/?probe=31ff7dd229) | Oct 28, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | [e0d6eafd15](https://linux-hardware.org/?probe=e0d6eafd15) | Oct 28, 2021 |
| Lenovo        | ThinkPad L590 20Q8S1FX00    | [7555bbd3c1](https://linux-hardware.org/?probe=7555bbd3c1) | Oct 27, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [3377403e20](https://linux-hardware.org/?probe=3377403e20) | Oct 27, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [1b93e3c1c9](https://linux-hardware.org/?probe=1b93e3c1c9) | Oct 27, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [3f7c00c1ef](https://linux-hardware.org/?probe=3f7c00c1ef) | Oct 27, 2021 |
| Dell          | Latitude 5420               | [6eef53ac22](https://linux-hardware.org/?probe=6eef53ac22) | Oct 27, 2021 |
| Fujitsu Si... | ESPRIMO Mobile M9410        | [2cec9ef3cc](https://linux-hardware.org/?probe=2cec9ef3cc) | Oct 27, 2021 |
| Dell          | Latitude 5420               | [6d4e346031](https://linux-hardware.org/?probe=6d4e346031) | Oct 27, 2021 |
| Dell          | Latitude 5521               | [e40947106a](https://linux-hardware.org/?probe=e40947106a) | Oct 27, 2021 |
| Dell          | Latitude 5521               | [7fed676309](https://linux-hardware.org/?probe=7fed676309) | Oct 27, 2021 |
| Toshiba       | PORTEGE R830                | [6378d53c40](https://linux-hardware.org/?probe=6378d53c40) | Oct 27, 2021 |
| Apple         | MacBook2,1                  | [0346bc764a](https://linux-hardware.org/?probe=0346bc764a) | Oct 27, 2021 |
| Dell          | Inspiron 3595               | [1df662506b](https://linux-hardware.org/?probe=1df662506b) | Oct 27, 2021 |
| Acer          | Aspire A315-21              | [e179a0974d](https://linux-hardware.org/?probe=e179a0974d) | Oct 27, 2021 |
| Dell          | Inspiron 5558               | [e22971aa36](https://linux-hardware.org/?probe=e22971aa36) | Oct 27, 2021 |
| Dell          | XPS 15 9570                 | [0fa8c3ed0c](https://linux-hardware.org/?probe=0fa8c3ed0c) | Oct 26, 2021 |
| Acer          | Swift SF314-43              | [4c750c8b99](https://linux-hardware.org/?probe=4c750c8b99) | Oct 26, 2021 |
| Direkt-Tek    | DTLAPY133-1                 | [63facc4838](https://linux-hardware.org/?probe=63facc4838) | Oct 26, 2021 |
| Direkt-Tek    | DTLAPY133-1                 | [a2d784b2ea](https://linux-hardware.org/?probe=a2d784b2ea) | Oct 26, 2021 |
| Packard Be... | EasyNote TS11HR             | [1217a94f61](https://linux-hardware.org/?probe=1217a94f61) | Oct 26, 2021 |
| Acer          | Aspire ES1-523              | [59ab566702](https://linux-hardware.org/?probe=59ab566702) | Oct 25, 2021 |
| Acer          | Aspire ES1-523              | [d215eb8353](https://linux-hardware.org/?probe=d215eb8353) | Oct 25, 2021 |
| HP            | Laptop 15-da0xxx            | [f0a8fa5e7a](https://linux-hardware.org/?probe=f0a8fa5e7a) | Oct 25, 2021 |
| Acer          | Swift SF314-56G             | [55a32ef8dc](https://linux-hardware.org/?probe=55a32ef8dc) | Oct 25, 2021 |
| Acer          | Aspire VX5-591G             | [6ad3cf44dc](https://linux-hardware.org/?probe=6ad3cf44dc) | Oct 24, 2021 |
| HP            | Pavilion dv6                | [bf8422ec46](https://linux-hardware.org/?probe=bf8422ec46) | Oct 24, 2021 |
| Samsung       | 530U3C/530U4C               | [07df07de7d](https://linux-hardware.org/?probe=07df07de7d) | Oct 24, 2021 |
| Acer          | Aspire ES1-512              | [aa7dd43b73](https://linux-hardware.org/?probe=aa7dd43b73) | Oct 24, 2021 |
| Acer          | Swift SF314-57              | [b416f8b251](https://linux-hardware.org/?probe=b416f8b251) | Oct 24, 2021 |
| Acer          | Swift SF314-57              | [5cfaf3df18](https://linux-hardware.org/?probe=5cfaf3df18) | Oct 24, 2021 |
| HP            | Laptop 15s-eq2xxx           | [1e9f6f2d44](https://linux-hardware.org/?probe=1e9f6f2d44) | Oct 24, 2021 |
| HP            | ProBook 440 G5              | [508961bc42](https://linux-hardware.org/?probe=508961bc42) | Oct 24, 2021 |
| Acer          | Swift SF314-43              | [5de95b5df3](https://linux-hardware.org/?probe=5de95b5df3) | Oct 23, 2021 |
| HP            | ProBook 440 G5              | [db61c07848](https://linux-hardware.org/?probe=db61c07848) | Oct 23, 2021 |
| Acer          | Swift SF314-43              | [8d0af565c3](https://linux-hardware.org/?probe=8d0af565c3) | Oct 23, 2021 |
| Fujitsu       | LIFEBOOK U772               | [7fab4f85e2](https://linux-hardware.org/?probe=7fab4f85e2) | Oct 23, 2021 |
| HUAWEI        | MACH-WX9                    | [68c01947c9](https://linux-hardware.org/?probe=68c01947c9) | Oct 23, 2021 |
| Dell          | Inspiron 5558               | [bb40091a40](https://linux-hardware.org/?probe=bb40091a40) | Oct 23, 2021 |
| Acer          | Swift SF114-32              | [87697aa300](https://linux-hardware.org/?probe=87697aa300) | Oct 23, 2021 |
| Dell          | Latitude E7470              | [69a251cc1f](https://linux-hardware.org/?probe=69a251cc1f) | Oct 22, 2021 |
| Dell          | Inspiron 15 5501            | [d252623e18](https://linux-hardware.org/?probe=d252623e18) | Oct 22, 2021 |
| Acer          | Swift SF314-43              | [8275d5fa0b](https://linux-hardware.org/?probe=8275d5fa0b) | Oct 22, 2021 |
| HP            | ProBook 450 G5              | [5909be5c82](https://linux-hardware.org/?probe=5909be5c82) | Oct 22, 2021 |
| Sony          | VGN-FW550F                  | [c2b95c9dfa](https://linux-hardware.org/?probe=c2b95c9dfa) | Oct 22, 2021 |
| Clevo         | M740TU(N)/M760TU(N)/W7X0... | [85ccf0afc5](https://linux-hardware.org/?probe=85ccf0afc5) | Oct 22, 2021 |
| HP            | Pavilion g4                 | [3b86797a83](https://linux-hardware.org/?probe=3b86797a83) | Oct 22, 2021 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [b198944ad7](https://linux-hardware.org/?probe=b198944ad7) | Oct 22, 2021 |
| Dell          | Inspiron 5558               | [6ada321924](https://linux-hardware.org/?probe=6ada321924) | Oct 22, 2021 |
| MSI           | GF63 Thin 9RCX              | [c4768bba2d](https://linux-hardware.org/?probe=c4768bba2d) | Oct 22, 2021 |
| Lenovo        | ThinkPad T430s 23561R0      | [bef1593d06](https://linux-hardware.org/?probe=bef1593d06) | Oct 22, 2021 |
| Toshiba       | PORTEGE R830                | [5d6b560499](https://linux-hardware.org/?probe=5d6b560499) | Oct 22, 2021 |
| MSI           | GF63 Thin 9RCX              | [aa2a33d3f0](https://linux-hardware.org/?probe=aa2a33d3f0) | Oct 21, 2021 |
| Lenovo        | ThinkPad T15g Gen 1 20UR... | [55de21b8b0](https://linux-hardware.org/?probe=55de21b8b0) | Oct 21, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [1b5cd08b30](https://linux-hardware.org/?probe=1b5cd08b30) | Oct 21, 2021 |
| Apple         | MacBookPro12,1              | [271e56e195](https://linux-hardware.org/?probe=271e56e195) | Oct 21, 2021 |
| Apple         | MacBookPro12,1              | [3735576026](https://linux-hardware.org/?probe=3735576026) | Oct 21, 2021 |
| realme        | RMNBXXXX                    | [daa57fd7da](https://linux-hardware.org/?probe=daa57fd7da) | Oct 21, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0004... | [9facbd3d72](https://linux-hardware.org/?probe=9facbd3d72) | Oct 21, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [463b15301d](https://linux-hardware.org/?probe=463b15301d) | Oct 21, 2021 |
| HP            | 15                          | [b01898bb59](https://linux-hardware.org/?probe=b01898bb59) | Oct 21, 2021 |
| MSI           | GP72 2QD                    | [75801b27ae](https://linux-hardware.org/?probe=75801b27ae) | Oct 20, 2021 |
| MSI           | GP72 2QD                    | [bd12b3e948](https://linux-hardware.org/?probe=bd12b3e948) | Oct 20, 2021 |
| HP            | 650                         | [c32592cabb](https://linux-hardware.org/?probe=c32592cabb) | Oct 20, 2021 |
| HP            | ProBook 450 G7              | [c86d75dbbb](https://linux-hardware.org/?probe=c86d75dbbb) | Oct 20, 2021 |
| Medion        | E6226                       | [ebc0f3d72b](https://linux-hardware.org/?probe=ebc0f3d72b) | Oct 20, 2021 |
| Acer          | Nitro AN515-43              | [ac5870ab3d](https://linux-hardware.org/?probe=ac5870ab3d) | Oct 20, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [14d159c564](https://linux-hardware.org/?probe=14d159c564) | Oct 20, 2021 |
| HUAWEI        | KLVL-WXX9                   | [4517a98ebf](https://linux-hardware.org/?probe=4517a98ebf) | Oct 20, 2021 |
| Apple         | MacBookPro9,2               | [0ec3c548af](https://linux-hardware.org/?probe=0ec3c548af) | Oct 19, 2021 |
| Lenovo        | ThinkPad T590 20N5S4Y100    | [f00be1a69f](https://linux-hardware.org/?probe=f00be1a69f) | Oct 19, 2021 |
| Dell          | Latitude 5400               | [8a880e6565](https://linux-hardware.org/?probe=8a880e6565) | Oct 19, 2021 |
| Dell          | Latitude 5400               | [0a94130eb2](https://linux-hardware.org/?probe=0a94130eb2) | Oct 19, 2021 |
| Lenovo        | ThinkPad T500 22437SG       | [0e26427d3d](https://linux-hardware.org/?probe=0e26427d3d) | Oct 19, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [8e04250418](https://linux-hardware.org/?probe=8e04250418) | Oct 19, 2021 |
| Lenovo        | G505 20240                  | [a878fe1079](https://linux-hardware.org/?probe=a878fe1079) | Oct 19, 2021 |
| Lenovo        | G505 20240                  | [4c254474e3](https://linux-hardware.org/?probe=4c254474e3) | Oct 19, 2021 |
| HUAWEI        | MACHD-WXX9                  | [8563f3786e](https://linux-hardware.org/?probe=8563f3786e) | Oct 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [a16f7dac18](https://linux-hardware.org/?probe=a16f7dac18) | Oct 18, 2021 |
| Lenovo        | ThinkPad W530 244759G       | [e80bbd929f](https://linux-hardware.org/?probe=e80bbd929f) | Oct 18, 2021 |
| HP            | Compaq Presario CQ50        | [bb34275819](https://linux-hardware.org/?probe=bb34275819) | Oct 18, 2021 |
| MSI           | GF62 8RC                    | [89d77a3654](https://linux-hardware.org/?probe=89d77a3654) | Oct 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [080c5280d0](https://linux-hardware.org/?probe=080c5280d0) | Oct 17, 2021 |
| Lenovo        | ThinkPad T500 22437SG       | [751041603e](https://linux-hardware.org/?probe=751041603e) | Oct 17, 2021 |
| Dell          | Inspiron 15-3573            | [0eae8a7bf7](https://linux-hardware.org/?probe=0eae8a7bf7) | Oct 17, 2021 |
| ASUSTek       | G72GX                       | [48f6c89377](https://linux-hardware.org/?probe=48f6c89377) | Oct 17, 2021 |
| Dell          | XPS 15 9570                 | [26d1a4225d](https://linux-hardware.org/?probe=26d1a4225d) | Oct 17, 2021 |
| HP            | Pavilion dv6                | [b60dd43240](https://linux-hardware.org/?probe=b60dd43240) | Oct 17, 2021 |
| ASUSTek       | X501A                       | [b3e4d8035d](https://linux-hardware.org/?probe=b3e4d8035d) | Oct 17, 2021 |
| HP            | Laptop 17-by3xxx            | [e16a18bc8b](https://linux-hardware.org/?probe=e16a18bc8b) | Oct 17, 2021 |
| Dell          | Latitude 7490               | [adb96facbb](https://linux-hardware.org/?probe=adb96facbb) | Oct 17, 2021 |
| Acer          | Aspire A715-75G             | [87c7c24dcc](https://linux-hardware.org/?probe=87c7c24dcc) | Oct 17, 2021 |
| Acer          | ConceptD CN315-71P          | [50385dde8b](https://linux-hardware.org/?probe=50385dde8b) | Oct 16, 2021 |
| realme        | RMNBXXXX                    | [968a52c56a](https://linux-hardware.org/?probe=968a52c56a) | Oct 16, 2021 |
| HP            | EliteBook 8570w             | [492907a363](https://linux-hardware.org/?probe=492907a363) | Oct 16, 2021 |
| Medion        | E7218                       | [cca261a107](https://linux-hardware.org/?probe=cca261a107) | Oct 16, 2021 |
| Acer          | Extensa 2519                | [5b33aac7c5](https://linux-hardware.org/?probe=5b33aac7c5) | Oct 16, 2021 |
| Toshiba       | Satellite C660              | [c70057c643](https://linux-hardware.org/?probe=c70057c643) | Oct 16, 2021 |
| HUAWEI        | KLVL-WXX9                   | [ff0e6377ee](https://linux-hardware.org/?probe=ff0e6377ee) | Oct 16, 2021 |
| HP            | ZBook 17 G3                 | [11b17af506](https://linux-hardware.org/?probe=11b17af506) | Oct 16, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [c7fc550482](https://linux-hardware.org/?probe=c7fc550482) | Oct 16, 2021 |
| Apple         | MacBookPro12,1              | [4bfee9269a](https://linux-hardware.org/?probe=4bfee9269a) | Oct 16, 2021 |
| Sony          | VPCEB2S1E                   | [b42e7996bf](https://linux-hardware.org/?probe=b42e7996bf) | Oct 15, 2021 |
| Acer          | Aspire 7530G                | [09694e2816](https://linux-hardware.org/?probe=09694e2816) | Oct 15, 2021 |
| Dell          | Inspiron 15-3567            | [a629aeaa1b](https://linux-hardware.org/?probe=a629aeaa1b) | Oct 15, 2021 |
| Lenovo        | B570 1068GEG                | [cb2f8c100b](https://linux-hardware.org/?probe=cb2f8c100b) | Oct 15, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [c6478e67c7](https://linux-hardware.org/?probe=c6478e67c7) | Oct 15, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | [00196d9727](https://linux-hardware.org/?probe=00196d9727) | Oct 15, 2021 |
| Acer          | Aspire A715-75G             | [0d9ad64b08](https://linux-hardware.org/?probe=0d9ad64b08) | Oct 15, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0180... | [11539dc528](https://linux-hardware.org/?probe=11539dc528) | Oct 15, 2021 |
| Acer          | Aspire 7741                 | [2f093c19bf](https://linux-hardware.org/?probe=2f093c19bf) | Oct 15, 2021 |
| Dell          | XPS 13 9300                 | [22029905ac](https://linux-hardware.org/?probe=22029905ac) | Oct 15, 2021 |
| ASUSTek       | GL753VD                     | [a63eee78d3](https://linux-hardware.org/?probe=a63eee78d3) | Oct 14, 2021 |
| Dell          | Latitude E6520              | [b84ef4472b](https://linux-hardware.org/?probe=b84ef4472b) | Oct 14, 2021 |
| Google        | Treeya                      | [82b0964b6d](https://linux-hardware.org/?probe=82b0964b6d) | Oct 14, 2021 |
| Framework     | Laptop                      | [bd65852653](https://linux-hardware.org/?probe=bd65852653) | Oct 14, 2021 |
| Dell          | Latitude E6320              | [e8538ce77d](https://linux-hardware.org/?probe=e8538ce77d) | Oct 12, 2021 |
| Lenovo        | ThinkPad X201T 3113CC7      | [47f63d40d5](https://linux-hardware.org/?probe=47f63d40d5) | Oct 09, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [f8d957d29f](https://linux-hardware.org/?probe=f8d957d29f) | Oct 09, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [954005ca3d](https://linux-hardware.org/?probe=954005ca3d) | Oct 08, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [6c5495590b](https://linux-hardware.org/?probe=6c5495590b) | Oct 08, 2021 |
| Lenovo        | G570 20079                  | [81875a0613](https://linux-hardware.org/?probe=81875a0613) | Oct 06, 2021 |
| Dell          | XPS 13 7390                 | [66d13e4e24](https://linux-hardware.org/?probe=66d13e4e24) | Oct 03, 2021 |
| Lenovo        | ThinkPad T15g Gen 1 20UR... | [08a44500da](https://linux-hardware.org/?probe=08a44500da) | Oct 03, 2021 |
| Lenovo        | G570 20079                  | [a0cac25f22](https://linux-hardware.org/?probe=a0cac25f22) | Oct 02, 2021 |
| Lenovo        | G570 20079                  | [93f8496968](https://linux-hardware.org/?probe=93f8496968) | Oct 02, 2021 |
| Dell          | XPS 13 7390                 | [c6882f7282](https://linux-hardware.org/?probe=c6882f7282) | Oct 01, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [2b03e34e82](https://linux-hardware.org/?probe=2b03e34e82) | Sep 30, 2021 |
| Lenovo        | ThinkPad T15g Gen 1 20UR... | [1b81ca9e7a](https://linux-hardware.org/?probe=1b81ca9e7a) | Sep 29, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [51b49beb10](https://linux-hardware.org/?probe=51b49beb10) | Sep 28, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [fc93efcead](https://linux-hardware.org/?probe=fc93efcead) | Sep 25, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [8a2d72befe](https://linux-hardware.org/?probe=8a2d72befe) | Sep 24, 2021 |
| TUXEDO        | N7x0WU                      | [10f446b51e](https://linux-hardware.org/?probe=10f446b51e) | Sep 24, 2021 |
| Dell          | Precision 7710              | [fa8e5cdff5](https://linux-hardware.org/?probe=fa8e5cdff5) | Sep 23, 2021 |
| Acer          | Swift SFX14-41G             | [6b06b9e5dd](https://linux-hardware.org/?probe=6b06b9e5dd) | Sep 23, 2021 |
| Apple         | MacBookPro8,1               | [5b337fdb0a](https://linux-hardware.org/?probe=5b337fdb0a) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | [7c806aa7c5](https://linux-hardware.org/?probe=7c806aa7c5) | Sep 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [824a26d7e0](https://linux-hardware.org/?probe=824a26d7e0) | Sep 18, 2021 |
| Dell          | Vostro 3550                 | [1fe8420099](https://linux-hardware.org/?probe=1fe8420099) | Sep 17, 2021 |
| Dell          | Vostro 3550                 | [10f08c1bfd](https://linux-hardware.org/?probe=10f08c1bfd) | Sep 17, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [77d801bf3c](https://linux-hardware.org/?probe=77d801bf3c) | Sep 15, 2021 |
| HP            | ProBook 455 G6              | [8c5aa4304c](https://linux-hardware.org/?probe=8c5aa4304c) | Sep 14, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [c105819db0](https://linux-hardware.org/?probe=c105819db0) | Sep 13, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [04299c1c72](https://linux-hardware.org/?probe=04299c1c72) | Sep 10, 2021 |
| Lenovo        | G570 20079                  | [070f80905a](https://linux-hardware.org/?probe=070f80905a) | Sep 09, 2021 |
| Dell          | XPS 13 9310                 | [ce30239886](https://linux-hardware.org/?probe=ce30239886) | Sep 08, 2021 |
| Lenovo        | ThinkPad T470 20JNS3M500    | [1dcfa059c1](https://linux-hardware.org/?probe=1dcfa059c1) | Sep 07, 2021 |
| Lenovo        | V310-14IKB 80T2             | [9036570a3d](https://linux-hardware.org/?probe=9036570a3d) | Sep 07, 2021 |
| Dell          | XPS 13 9310                 | [a23d662013](https://linux-hardware.org/?probe=a23d662013) | Sep 06, 2021 |
| Lenovo        | G570 20079                  | [92d47c8db5](https://linux-hardware.org/?probe=92d47c8db5) | Sep 05, 2021 |
| Google        | Nautilus                    | [3b25f1b84a](https://linux-hardware.org/?probe=3b25f1b84a) | Sep 05, 2021 |
| Lenovo        | G570 20079                  | [897adf5520](https://linux-hardware.org/?probe=897adf5520) | Sep 04, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [a66a6f00e4](https://linux-hardware.org/?probe=a66a6f00e4) | Sep 03, 2021 |
| Lenovo        | V310-14IKB 80T2             | [682d409384](https://linux-hardware.org/?probe=682d409384) | Sep 02, 2021 |
| Dell          | Latitude E6410              | [8b57d50d95](https://linux-hardware.org/?probe=8b57d50d95) | Sep 02, 2021 |
| ASUSTek       | GL753VD                     | [d17c6ba3fc](https://linux-hardware.org/?probe=d17c6ba3fc) | Sep 01, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [cae806f49d](https://linux-hardware.org/?probe=cae806f49d) | Aug 22, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [b8aa2e41d5](https://linux-hardware.org/?probe=b8aa2e41d5) | Aug 16, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [612dda8fba](https://linux-hardware.org/?probe=612dda8fba) | Aug 13, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [1eb6008b88](https://linux-hardware.org/?probe=1eb6008b88) | Aug 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [808cfab06b](https://linux-hardware.org/?probe=808cfab06b) | Aug 12, 2021 |
| Lenovo        | ThinkPad T510 4484A63       | [c1bcb3451f](https://linux-hardware.org/?probe=c1bcb3451f) | Aug 09, 2021 |
| Lenovo        | ThinkPad T510 4484A63       | [4336b50906](https://linux-hardware.org/?probe=4336b50906) | Aug 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [961031411d](https://linux-hardware.org/?probe=961031411d) | Aug 03, 2021 |
| Lenovo        | ZhaoYang K3-ITL 82E3        | [ee2be4cea9](https://linux-hardware.org/?probe=ee2be4cea9) | Aug 03, 2021 |
| ASUSTek       | GL753VD                     | [eabe6a8723](https://linux-hardware.org/?probe=eabe6a8723) | Jul 31, 2021 |
| Acer          | Aspire 5920                 | [f41defe215](https://linux-hardware.org/?probe=f41defe215) | Jul 31, 2021 |
| Dell          | XPS 13 7390                 | [901bcb991b](https://linux-hardware.org/?probe=901bcb991b) | Jul 31, 2021 |
| Teclast       | F6 Pro                      | [e28004c24b](https://linux-hardware.org/?probe=e28004c24b) | Jul 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f5458b4f56](https://linux-hardware.org/?probe=f5458b4f56) | Jul 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [5ac65f3389](https://linux-hardware.org/?probe=5ac65f3389) | Jul 18, 2021 |
| Lenovo        | Z50-70 20354                | [85aadf8abd](https://linux-hardware.org/?probe=85aadf8abd) | Jul 16, 2021 |
| Lenovo        | Z50-70 20354                | [b2c80f450e](https://linux-hardware.org/?probe=b2c80f450e) | Jul 14, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f024f2512e](https://linux-hardware.org/?probe=f024f2512e) | Jul 14, 2021 |
| Lenovo        | ThinkPad X201 3626FAG       | [259908557b](https://linux-hardware.org/?probe=259908557b) | Jun 28, 2021 |
| Positivo      | H14BT58                     | [51b9ba65e0](https://linux-hardware.org/?probe=51b9ba65e0) | Jun 18, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | [4befd5f360](https://linux-hardware.org/?probe=4befd5f360) | Jun 04, 2021 |
| Dell          | XPS 13 9343                 | [4ee08e92ae](https://linux-hardware.org/?probe=4ee08e92ae) | May 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 5.13.0-21-generic         | 146       | 25.93%  |
| 5.13.0-22-generic         | 145       | 25.75%  |
| 5.13.0-20-generic         | 107       | 19.01%  |
| 5.13.0-19-generic         | 76        | 13.5%   |
| 5.13.0-16-generic         | 14        | 2.49%   |
| 5.13.0-23-generic         | 12        | 2.13%   |
| 5.13.0-14-generic         | 8         | 1.42%   |
| 5.15.2-051502-generic     | 4         | 0.71%   |
| 5.11.0-20-generic         | 4         | 0.71%   |
| 5.15.5-051505-generic     | 2         | 0.36%   |
| 5.15.4-051504-generic     | 2         | 0.36%   |
| 5.15.0-051500rc5-generic  | 2         | 0.36%   |
| 5.15.0-051500-generic     | 2         | 0.36%   |
| 5.13.0-20-lowlatency      | 2         | 0.36%   |
| 5.11.0-40-generic         | 2         | 0.36%   |
| 5.11.0-38-generic         | 2         | 0.36%   |
| 5.11.0-37-generic         | 2         | 0.36%   |
| 5.11.0-25-generic         | 2         | 0.36%   |
| 5.11.0-18-generic         | 2         | 0.36%   |
| 5.16.0-051600rc3-generic  | 1         | 0.18%   |
| 5.16.0-051600rc2-generic  | 1         | 0.18%   |
| 5.16.0-051600rc1-generic  | 1         | 0.18%   |
| 5.15.7-051507-generic     | 1         | 0.18%   |
| 5.15.12-xanmod1           | 1         | 0.18%   |
| 5.15.1-051501-generic     | 1         | 0.18%   |
| 5.15.0-5.4-liquorix-amd64 | 1         | 0.18%   |
| 5.14.17-051417-generic    | 1         | 0.18%   |
| 5.14.14-051414-generic    | 1         | 0.18%   |
| 5.14.13-051413-generic    | 1         | 0.18%   |
| 5.14.11-051411-generic    | 1         | 0.18%   |
| 5.14.0-1005-oem           | 1         | 0.18%   |
| 5.13.6-xanmod2-edge       | 1         | 0.18%   |
| 5.13.4-051304-generic     | 1         | 0.18%   |
| 5.13.2-051302-generic     | 1         | 0.18%   |
| 5.13.11-051311-generic    | 1         | 0.18%   |
| 5.13.0-23-lowlatency      | 1         | 0.18%   |
| 5.13.0-21-lowlatency      | 1         | 0.18%   |
| 5.13.0-13-generic         | 1         | 0.18%   |
| 5.12.19-051219-generic    | 1         | 0.18%   |
| 5.11.0-31-generic         | 1         | 0.18%   |
| 5.11.0-26-generic         | 1         | 0.18%   |
| 5.11.0-22-generic         | 1         | 0.18%   |
| 5.11.0-16-generic         | 1         | 0.18%   |
| 5.10.77-051077-generic    | 1         | 0.18%   |
| 5.10.65-051065-generic    | 1         | 0.18%   |
| 5.10.0-1050-oem           | 1         | 0.18%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13.0  | 496       | 90.84%  |
| 5.11.0  | 18        | 3.3%    |
| 5.15.0  | 5         | 0.92%   |
| 5.15.2  | 4         | 0.73%   |
| 5.16.0  | 3         | 0.55%   |
| 5.15.5  | 2         | 0.37%   |
| 5.15.4  | 2         | 0.37%   |
| 5.15.7  | 1         | 0.18%   |
| 5.15.12 | 1         | 0.18%   |
| 5.15.1  | 1         | 0.18%   |
| 5.14.17 | 1         | 0.18%   |
| 5.14.14 | 1         | 0.18%   |
| 5.14.13 | 1         | 0.18%   |
| 5.14.11 | 1         | 0.18%   |
| 5.14.0  | 1         | 0.18%   |
| 5.13.6  | 1         | 0.18%   |
| 5.13.4  | 1         | 0.18%   |
| 5.13.2  | 1         | 0.18%   |
| 5.13.11 | 1         | 0.18%   |
| 5.12.19 | 1         | 0.18%   |
| 5.10.77 | 1         | 0.18%   |
| 5.10.65 | 1         | 0.18%   |
| 5.10.0  | 1         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13    | 500       | 91.74%  |
| 5.11    | 18        | 3.3%    |
| 5.15    | 15        | 2.75%   |
| 5.14    | 5         | 0.92%   |
| 5.16    | 3         | 0.55%   |
| 5.10    | 3         | 0.55%   |
| 5.12    | 1         | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 543       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 492       | 90.44%  |
| Unknown         | 32        | 5.88%   |
| GNOME Flashback | 6         | 1.1%    |
| X-Cinnamon      | 4         | 0.74%   |
| Unity           | 4         | 0.74%   |
| i3              | 2         | 0.37%   |
| Cinnamon        | 2         | 0.37%   |
| ICEWM           | 1         | 0.18%   |
| GNOME Classic   | 1         | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 368       | 67.4%   |
| X11     | 160       | 29.3%   |
| Unknown | 16        | 2.93%   |
| Tty     | 2         | 0.37%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM3    | 292       | 53.48%  |
| GDM     | 191       | 34.98%  |
| Unknown | 50        | 9.16%   |
| LightDM | 8         | 1.47%   |
| SDDM    | 3         | 0.55%   |
| TDM     | 1         | 0.18%   |
| Ly      | 1         | 0.18%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 240       | 44.2%   |
| de_DE   | 59        | 10.87%  |
| en_GB   | 38        | 7%      |
| fr_FR   | 25        | 4.6%    |
| ru_RU   | 21        | 3.87%   |
| it_IT   | 17        | 3.13%   |
| en_IN   | 14        | 2.58%   |
| es_ES   | 13        | 2.39%   |
| pt_BR   | 12        | 2.21%   |
| en_CA   | 12        | 2.21%   |
| en_AU   | 12        | 2.21%   |
| cs_CZ   | 11        | 2.03%   |
| Unknown | 6         | 1.1%    |
| zh_CN   | 5         | 0.92%   |
| hu_HU   | 5         | 0.92%   |
| es_MX   | 5         | 0.92%   |
| sv_SE   | 4         | 0.74%   |
| C       | 4         | 0.74%   |
| tr_TR   | 3         | 0.55%   |
| es_CL   | 3         | 0.55%   |
| da_DK   | 3         | 0.55%   |
| pt_PT   | 2         | 0.37%   |
| pl_PL   | 2         | 0.37%   |
| nl_NL   | 2         | 0.37%   |
| ko_KR   | 2         | 0.37%   |
| fi_FI   | 2         | 0.37%   |
| es_AR   | 2         | 0.37%   |
| en_NZ   | 2         | 0.37%   |
| de_CH   | 2         | 0.37%   |
| de_AT   | 2         | 0.37%   |
| sl_SI   | 1         | 0.18%   |
| ro_RO   | 1         | 0.18%   |
| nl_BE   | 1         | 0.18%   |
| lt_LT   | 1         | 0.18%   |
| id_ID   | 1         | 0.18%   |
| fr_CA   | 1         | 0.18%   |
| es_UY   | 1         | 0.18%   |
| es_PE   | 1         | 0.18%   |
| en_ZM   | 1         | 0.18%   |
| en_ZA   | 1         | 0.18%   |
| en_IL   | 1         | 0.18%   |
| en_IE   | 1         | 0.18%   |
| de_IT   | 1         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 316       | 57.66%  |
| EFI  | 232       | 42.34%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 495       | 91.16%  |
| Overlay  | 17        | 3.13%   |
| Zfs      | 14        | 2.58%   |
| Btrfs    | 10        | 1.84%   |
| Ext3     | 2         | 0.37%   |
| Ext2     | 2         | 0.37%   |
| Xfs      | 1         | 0.18%   |
| Reiserfs | 1         | 0.18%   |
| Unknown  | 1         | 0.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 333       | 61.1%   |
| GPT     | 202       | 37.06%  |
| MBR     | 10        | 1.83%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 488       | 89.54%  |
| Yes       | 57        | 10.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 331       | 60.62%  |
| Yes       | 215       | 39.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Lenovo                                       | 106       | 19.52%  |
| Dell                                         | 105       | 19.34%  |
| Hewlett-Packard                              | 92        | 16.94%  |
| Acer                                         | 50        | 9.21%   |
| ASUSTek Computer                             | 43        | 7.92%   |
| HUAWEI                                       | 16        | 2.95%   |
| Toshiba                                      | 13        | 2.39%   |
| MSI                                          | 13        | 2.39%   |
| Apple                                        | 13        | 2.39%   |
| Sony                                         | 12        | 2.21%   |
| Samsung Electronics                          | 12        | 2.21%   |
| Timi                                         | 6         | 1.1%    |
| Medion                                       | 6         | 1.1%    |
| Fujitsu                                      | 6         | 1.1%    |
| Packard Bell                                 | 4         | 0.74%   |
| Google                                       | 4         | 0.74%   |
| Avell High Performance                       | 4         | 0.74%   |
| realme                                       | 3         | 0.55%   |
| Razer                                        | 3         | 0.55%   |
| Notebook                                     | 3         | 0.55%   |
| TUXEDO                                       | 2         | 0.37%   |
| Positivo                                     | 2         | 0.37%   |
| PC Specialist                                | 2         | 0.37%   |
| Framework                                    | 2         | 0.37%   |
| YJKC                                         | 1         | 0.18%   |
| Wortmann AG                                  | 1         | 0.18%   |
| win element                                  | 1         | 0.18%   |
| Teclast                                      | 1         | 0.18%   |
| System76                                     | 1         | 0.18%   |
| Schenker                                     | 1         | 0.18%   |
| Panasonic                                    | 1         | 0.18%   |
| MOTILE                                       | 1         | 0.18%   |
| LG Electronics                               | 1         | 0.18%   |
| Jumper                                       | 1         | 0.18%   |
| Jooyontech Computer                          | 1         | 0.18%   |
| Jemper                                       | 1         | 0.18%   |
| Fujitsu Siemens                              | 1         | 0.18%   |
| Exo                                          | 1         | 0.18%   |
| eMachines                                    | 1         | 0.18%   |
| DukaPC                                       | 1         | 0.18%   |
| Direkt-Tek                                   | 1         | 0.18%   |
| Clevo                                        | 1         | 0.18%   |
| CHUWI Innovation And Technology(ShenZhen)c0. | 1         | 0.18%   |
| Alienware                                    | 1         | 0.18%   |
| Acidanthera                                  | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Dell XPS 13 9310                                      | 6         | 1.1%    |
| Acer Swift SF314-43                                   | 6         | 1.1%    |
| HUAWEI KLVL-WXX9                                      | 5         | 0.92%   |
| Dell XPS 15 9570                                      | 5         | 0.92%   |
| Dell XPS 15 9500                                      | 5         | 0.92%   |
| realme RMNBXXXX                                       | 3         | 0.55%   |
| HP Pavilion Notebook                                  | 3         | 0.55%   |
| HP Pavilion dv6                                       | 3         | 0.55%   |
| HP Pavilion Aero Laptop 13-be0xxx                     | 3         | 0.55%   |
| Dell XPS 13 9300                                      | 3         | 0.55%   |
| Dell Latitude E6410                                   | 3         | 0.55%   |
| Dell Latitude 5420                                    | 3         | 0.55%   |
| Dell Inspiron 15-3567                                 | 3         | 0.55%   |
| Apple MacBookPro12,1                                  | 3         | 0.55%   |
| Acer Swift SF314-42                                   | 3         | 0.55%   |
| Timi A35S                                             | 2         | 0.37%   |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 2         | 0.37%   |
| Lenovo ThinkPad T400 2768WGB                          | 2         | 0.37%   |
| Lenovo Legion Y530-15ICH 81FV                         | 2         | 0.37%   |
| Lenovo IdeaPad 330-15AST 81D6                         | 2         | 0.37%   |
| HUAWEI NBLK-WAX9X                                     | 2         | 0.37%   |
| HUAWEI MACHD-WXX9                                     | 2         | 0.37%   |
| HUAWEI MACH-WX9                                       | 2         | 0.37%   |
| HUAWEI HVY-WXX9                                       | 2         | 0.37%   |
| HP ProBook 6450b                                      | 2         | 0.37%   |
| HP ProBook 440 G6                                     | 2         | 0.37%   |
| HP Pavilion Gaming Laptop 15-dk0xxx                   | 2         | 0.37%   |
| HP Pavilion dv7                                       | 2         | 0.37%   |
| HP Laptop 14-fq1xxx                                   | 2         | 0.37%   |
| HP EliteBook 840 G2                                   | 2         | 0.37%   |
| HP 15                                                 | 2         | 0.37%   |
| Framework Laptop                                      | 2         | 0.37%   |
| Dell XPS 17 9700                                      | 2         | 0.37%   |
| Dell XPS 15 9510                                      | 2         | 0.37%   |
| Dell XPS 13 7390                                      | 2         | 0.37%   |
| Dell Latitude E7470                                   | 2         | 0.37%   |
| Dell Latitude E6520                                   | 2         | 0.37%   |
| Dell Latitude E6400                                   | 2         | 0.37%   |
| Dell Latitude 5520                                    | 2         | 0.37%   |
| Dell Inspiron 5570                                    | 2         | 0.37%   |
| Avell High Performance B.ON                           | 2         | 0.37%   |
| ASUS X550VX                                           | 2         | 0.37%   |
| Apple MacBookPro8,1                                   | 2         | 0.37%   |
| Apple MacBookPro11,1                                  | 2         | 0.37%   |
| Acer Swift SF315-41                                   | 2         | 0.37%   |
| Acer Swift SF314-51                                   | 2         | 0.37%   |
| Acer ConceptD CN315-71P                               | 2         | 0.37%   |
| Acer Aspire A515-56                                   | 2         | 0.37%   |
| YJKC vBOOK Plus                                       | 1         | 0.18%   |
| Wortmann AG 1220679_1470212                           | 1         | 0.18%   |
| win element MoreFine S500+                            | 1         | 0.18%   |
| TUXEDO N7x0WU                                         | 1         | 0.18%   |
| TUXEDO InfinityBook Pro 14 Gen6                       | 1         | 0.18%   |
| Toshiba TECRA R940                                    | 1         | 0.18%   |
| Toshiba Satellite U920T                               | 1         | 0.18%   |
| Toshiba Satellite Pro S300                            | 1         | 0.18%   |
| Toshiba Satellite Pro L650                            | 1         | 0.18%   |
| Toshiba Satellite Pro C850-1GU                        | 1         | 0.18%   |
| Toshiba Satellite L755                                | 1         | 0.18%   |
| Toshiba Satellite L655                                | 1         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 50        | 9.21%   |
| Dell Latitude               | 35        | 6.45%   |
| Dell XPS                    | 30        | 5.52%   |
| Lenovo IdeaPad              | 28        | 5.16%   |
| Dell Inspiron               | 27        | 4.97%   |
| HP Pavilion                 | 23        | 4.24%   |
| Acer Aspire                 | 23        | 4.24%   |
| HP ProBook                  | 22        | 4.05%   |
| Acer Swift                  | 19        | 3.5%    |
| HP EliteBook                | 14        | 2.58%   |
| HP Laptop                   | 12        | 2.21%   |
| Toshiba Satellite           | 11        | 2.03%   |
| ASUS VivoBook               | 9         | 1.66%   |
| Lenovo ThinkBook            | 6         | 1.1%    |
| Fujitsu LIFEBOOK            | 6         | 1.1%    |
| ASUS TUF                    | 6         | 1.1%    |
| ASUS ROG                    | 6         | 1.1%    |
| HUAWEI KLVL-WXX9            | 5         | 0.92%   |
| HP ZBook                    | 5         | 0.92%   |
| Dell Precision              | 5         | 0.92%   |
| Packard Bell EasyNote       | 4         | 0.74%   |
| realme RMNBXXXX             | 3         | 0.55%   |
| Razer Blade                 | 3         | 0.55%   |
| Lenovo Legion               | 3         | 0.55%   |
| HP ENVY                     | 3         | 0.55%   |
| HP 15                       | 3         | 0.55%   |
| Dell Vostro                 | 3         | 0.55%   |
| Apple MacBookPro12          | 3         | 0.55%   |
| Timi A35S                   | 2         | 0.37%   |
| MSI GE62                    | 2         | 0.37%   |
| Lenovo G780                 | 2         | 0.37%   |
| HUAWEI NBLK-WAX9X           | 2         | 0.37%   |
| HUAWEI MACHD-WXX9           | 2         | 0.37%   |
| HUAWEI MACH-WX9             | 2         | 0.37%   |
| HUAWEI HVY-WXX9             | 2         | 0.37%   |
| Framework Laptop            | 2         | 0.37%   |
| Dell G15                    | 2         | 0.37%   |
| Avell High Performance B.ON | 2         | 0.37%   |
| Avell High Performance A70  | 2         | 0.37%   |
| ASUS ZenBook                | 2         | 0.37%   |
| ASUS X550VX                 | 2         | 0.37%   |
| Apple MacBookPro8           | 2         | 0.37%   |
| Apple MacBookPro11          | 2         | 0.37%   |
| Acer Nitro                  | 2         | 0.37%   |
| Acer Extensa                | 2         | 0.37%   |
| Acer ConceptD               | 2         | 0.37%   |
| YJKC vBOOK                  | 1         | 0.18%   |
| Wortmann AG 1220679         | 1         | 0.18%   |
| win element MoreFine        | 1         | 0.18%   |
| TUXEDO N7x0WU               | 1         | 0.18%   |
| TUXEDO InfinityBook         | 1         | 0.18%   |
| Toshiba TECRA               | 1         | 0.18%   |
| Toshiba PORTEGE             | 1         | 0.18%   |
| Timi TM1701                 | 1         | 0.18%   |
| Timi RedmiBook              | 1         | 0.18%   |
| Timi A35                    | 1         | 0.18%   |
| Timi A30                    | 1         | 0.18%   |
| Teclast F6                  | 1         | 0.18%   |
| System76 Gazelle            | 1         | 0.18%   |
| Sony VPCF130FD              | 1         | 0.18%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 190       | 34.99%  |
| 2020 | 63        | 11.6%   |
| 2019 | 46        | 8.47%   |
| 2018 | 38        | 7%      |
| 2012 | 33        | 6.08%   |
| 2017 | 27        | 4.97%   |
| 2013 | 26        | 4.79%   |
| 2011 | 23        | 4.24%   |
| 2015 | 22        | 4.05%   |
| 2016 | 20        | 3.68%   |
| 2010 | 18        | 3.31%   |
| 2014 | 14        | 2.58%   |
| 2009 | 12        | 2.21%   |
| 2008 | 10        | 1.84%   |
| 2007 | 1         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 543       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 477       | 87.68%  |
| Enabled  | 67        | 12.32%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 539       | 99.26%  |
| Yes  | 4         | 0.74%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 167       | 30.76%  |
| 16.01-24.0  | 100       | 18.42%  |
| 3.01-4.0    | 99        | 18.23%  |
| 8.01-16.0   | 92        | 16.94%  |
| 32.01-64.0  | 54        | 9.94%   |
| 64.01-256.0 | 12        | 2.21%   |
| 1.01-2.0    | 9         | 1.66%   |
| 2.01-3.0    | 6         | 1.1%    |
| 24.01-32.0  | 3         | 0.55%   |
| 0.51-1.0    | 1         | 0.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 191       | 34.17%  |
| 2.01-3.0   | 151       | 27.01%  |
| 4.01-8.0   | 98        | 17.53%  |
| 3.01-4.0   | 86        | 15.38%  |
| 8.01-16.0  | 22        | 3.94%   |
| 0.51-1.0   | 9         | 1.61%   |
| 16.01-24.0 | 2         | 0.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 404       | 73.99%  |
| 2      | 120       | 21.98%  |
| 3      | 16        | 2.93%   |
| 4      | 3         | 0.55%   |
| 0      | 3         | 0.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 363       | 66.61%  |
| Yes       | 182       | 33.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 401       | 73.71%  |
| No        | 143       | 26.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 536       | 98.71%  |
| No        | 7         | 1.29%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 445       | 81.8%   |
| No        | 99        | 18.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Germany            | 81        | 14.89%  |
| USA                | 69        | 12.68%  |
| France             | 34        | 6.25%   |
| Russia             | 32        | 5.88%   |
| Italy              | 31        | 5.7%    |
| UK                 | 30        | 5.51%   |
| Brazil             | 18        | 3.31%   |
| Czechia            | 17        | 3.13%   |
| India              | 15        | 2.76%   |
| Canada             | 15        | 2.76%   |
| Spain              | 13        | 2.39%   |
| Poland             | 12        | 2.21%   |
| Australia          | 12        | 2.21%   |
| Netherlands        | 10        | 1.84%   |
| Ukraine            | 9         | 1.65%   |
| Switzerland        | 8         | 1.47%   |
| Sweden             | 8         | 1.47%   |
| Mexico             | 7         | 1.29%   |
| Hungary            | 7         | 1.29%   |
| Denmark            | 7         | 1.29%   |
| Austria            | 7         | 1.29%   |
| Turkey             | 6         | 1.1%    |
| Romania            | 6         | 1.1%    |
| Portugal           | 6         | 1.1%    |
| Indonesia          | 6         | 1.1%    |
| Finland            | 6         | 1.1%    |
| Chile              | 5         | 0.92%   |
| Iran               | 4         | 0.74%   |
| China              | 4         | 0.74%   |
| Vietnam            | 3         | 0.55%   |
| South Korea        | 3         | 0.55%   |
| Pakistan           | 3         | 0.55%   |
| New Zealand        | 3         | 0.55%   |
| Tunisia            | 2         | 0.37%   |
| Lebanon            | 2         | 0.37%   |
| Japan              | 2         | 0.37%   |
| Guadeloupe         | 2         | 0.37%   |
| Egypt              | 2         | 0.37%   |
| Dominican Republic | 2         | 0.37%   |
| Cyprus             | 2         | 0.37%   |
| Bulgaria           | 2         | 0.37%   |
| Belgium            | 2         | 0.37%   |
| Argentina          | 2         | 0.37%   |
| Zambia             | 1         | 0.18%   |
| Uzbekistan         | 1         | 0.18%   |
| Uruguay            | 1         | 0.18%   |
| Uganda             | 1         | 0.18%   |
| UAE                | 1         | 0.18%   |
| Tanzania           | 1         | 0.18%   |
| Slovenia           | 1         | 0.18%   |
| Serbia             | 1         | 0.18%   |
| R?©union           | 1         | 0.18%   |
| Puerto Rico        | 1         | 0.18%   |
| Peru               | 1         | 0.18%   |
| Oman               | 1         | 0.18%   |
| Norway             | 1         | 0.18%   |
| Morocco            | 1         | 0.18%   |
| Malaysia           | 1         | 0.18%   |
| Lithuania          | 1         | 0.18%   |
| Latvia             | 1         | 0.18%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 11        | 2%      |
| Berlin            | 11        | 2%      |
| Prague            | 9         | 1.63%   |
| Paris             | 9         | 1.63%   |
| Warsaw            | 6         | 1.09%   |
| Vienna            | 5         | 0.91%   |
| Santiago          | 5         | 0.91%   |
| Helsinki          | 5         | 0.91%   |
| Rome              | 4         | 0.73%   |
| Perth             | 4         | 0.73%   |
| Munich            | 4         | 0.73%   |
| Milan             | 4         | 0.73%   |
| Kyiv              | 4         | 0.73%   |
| Frankfurt am Main | 4         | 0.73%   |
| Vlasikha          | 3         | 0.54%   |
| Vancouver         | 3         | 0.54%   |
| S??o Paulo        | 3         | 0.54%   |
| New York          | 3         | 0.54%   |
| Madrid            | 3         | 0.54%   |
| Lisbon            | 3         | 0.54%   |
| Lahore            | 3         | 0.54%   |
| Krasnodar         | 3         | 0.54%   |
| Krakow            | 3         | 0.54%   |
| Istanbul          | 3         | 0.54%   |
| Frechen           | 3         | 0.54%   |
| Budapest          | 3         | 0.54%   |
| Bucharest         | 3         | 0.54%   |
| Brescia           | 3         | 0.54%   |
| Zurich            | 2         | 0.36%   |
| Turin             | 2         | 0.36%   |
| Toronto           | 2         | 0.36%   |
| Tehran            | 2         | 0.36%   |
| Tatab??nya        | 2         | 0.36%   |
| Surabaya          | 2         | 0.36%   |
| Stuttgart         | 2         | 0.36%   |
| St Petersburg     | 2         | 0.36%   |
| Seattle           | 2         | 0.36%   |
| San Jose          | 2         | 0.36%   |
| Samara            | 2         | 0.36%   |
| Sainte-Anne       | 2         | 0.36%   |
| Saarbr??cken      | 2         | 0.36%   |
| Pune              | 2         | 0.36%   |
| Porto Alegre      | 2         | 0.36%   |
| Omaha             | 2         | 0.36%   |
| Newtown           | 2         | 0.36%   |
| New Delhi         | 2         | 0.36%   |
| Monheim am Rhein  | 2         | 0.36%   |
| Melbourne         | 2         | 0.36%   |
| Leipzig           | 2         | 0.36%   |
| Kingston          | 2         | 0.36%   |
| Kazan?ˆ™          | 2         | 0.36%   |
| Karlsruhe         | 2         | 0.36%   |
| Houston           | 2         | 0.36%   |
| Helsingborg       | 2         | 0.36%   |
| Hanover           | 2         | 0.36%   |
| Hanoi             | 2         | 0.36%   |
| Glasgow           | 2         | 0.36%   |
| Gdynia            | 2         | 0.36%   |
| Denver            | 2         | 0.36%   |
| Cairo             | 2         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 115       | 129    | 17.27%  |
| WDC                            | 77        | 80     | 11.56%  |
| Seagate                        | 77        | 86     | 11.56%  |
| Toshiba                        | 59        | 62     | 8.86%   |
| SanDisk                        | 43        | 47     | 6.46%   |
| SK Hynix                       | 39        | 41     | 5.86%   |
| Kingston                       | 34        | 39     | 5.11%   |
| Unknown                        | 28        | 31     | 4.2%    |
| Micron Technology              | 20        | 20     | 3%      |
| Intel                          | 19        | 21     | 2.85%   |
| HGST                           | 18        | 20     | 2.7%    |
| KIOXIA                         | 16        | 16     | 2.4%    |
| Crucial                        | 14        | 15     | 2.1%    |
| Hitachi                        | 13        | 14     | 1.95%   |
| A-DATA Technology              | 8         | 10     | 1.2%    |
| Phison                         | 7         | 9      | 1.05%   |
| LITEON                         | 7         | 7      | 1.05%   |
| Apple                          | 6         | 9      | 0.9%    |
| SPCC                           | 3         | 4      | 0.45%   |
| Solid State Storage Technology | 3         | 3      | 0.45%   |
| Micron/Crucial Technology      | 3         | 3      | 0.45%   |
| Lexar                          | 3         | 3      | 0.45%   |
| Fujitsu                        | 3         | 3      | 0.45%   |
| YMTC                           | 2         | 2      | 0.3%    |
| Transcend                      | 2         | 2      | 0.3%    |
| SABRENT                        | 2         | 2      | 0.3%    |
| PNY                            | 2         | 2      | 0.3%    |
| LITEONIT                       | 2         | 2      | 0.3%    |
| JMicron                        | 2         | 2      | 0.3%    |
| Intenso                        | 2         | 2      | 0.3%    |
| Corsair                        | 2         | 2      | 0.3%    |
| China                          | 2         | 2      | 0.3%    |
| ASMT                           | 2         | 2      | 0.3%    |
| ADATA Technology               | 2         | 2      | 0.3%    |
| Yangtze Memory Technologies    | 1         | 1      | 0.15%   |
| XPG                            | 1         | 2      | 0.15%   |
| Verbatim                       | 1         | 1      | 0.15%   |
| ValueTech                      | 1         | 1      | 0.15%   |
| Union Memory                   | 1         | 1      | 0.15%   |
| Team                           | 1         | 1      | 0.15%   |
| SSK                            | 1         | 1      | 0.15%   |
| SP                             | 1         | 1      | 0.15%   |
| Realtek Semiconductor          | 1         | 1      | 0.15%   |
| Realtek                        | 1         | 1      | 0.15%   |
| PLEXTOR                        | 1         | 1      | 0.15%   |
| Patriot                        | 1         | 1      | 0.15%   |
| OSCOO                          | 1         | 1      | 0.15%   |
| ORTIAL                         | 1         | 1      | 0.15%   |
| OCZ                            | 1         | 1      | 0.15%   |
| Netac                          | 1         | 1      | 0.15%   |
| Lite-On                        | 1         | 1      | 0.15%   |
| Lenovo                         | 1         | 1      | 0.15%   |
| LDLC                           | 1         | 1      | 0.15%   |
| KingSpec                       | 1         | 1      | 0.15%   |
| KingDian                       | 1         | 1      | 0.15%   |
| HECTRON                        | 1         | 1      | 0.15%   |
| GOODRAM                        | 1         | 1      | 0.15%   |
| Gigabyte Technology            | 1         | 1      | 0.15%   |
| Freecom                        | 1         | 1      | 0.15%   |
| Emtec                          | 1         | 1      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB     | 18        | 2.6%    |
| Samsung NVMe SSD Drive 512GB       | 14        | 2.03%   |
| Kingston SA400S37240G 240GB SSD    | 9         | 1.3%    |
| Sandisk NVMe SSD Drive 512GB       | 7         | 1.01%   |
| Toshiba NVMe SSD Drive 512GB       | 6         | 0.87%   |
| Toshiba MQ04ABF100 1TB             | 6         | 0.87%   |
| Toshiba MQ01ABF050 500GB           | 6         | 0.87%   |
| Toshiba MQ01ABD100 1TB             | 6         | 0.87%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 6         | 0.87%   |
| Seagate Expansion 1TB              | 6         | 0.87%   |
| Sandisk NVMe SSD Drive 256GB       | 6         | 0.87%   |
| HGST HTS721010A9E630 1TB           | 6         | 0.87%   |
| Unknown MMC Card  64GB             | 5         | 0.72%   |
| Samsung SSD 860 EVO 500GB          | 5         | 0.72%   |
| Samsung NVMe SSD Drive 256GB       | 5         | 0.72%   |
| Micron NVMe SSD Drive 512GB        | 5         | 0.72%   |
| Kingston OM8PDP3512B-AA1 512GB     | 5         | 0.72%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 4         | 0.58%   |
| WDC WD10JPVX-22JC3T0 1TB           | 4         | 0.58%   |
| SK Hynix NVMe SSD Drive 1024GB     | 4         | 0.58%   |
| SK Hynix HFM001TD3JX013N 1TB       | 4         | 0.58%   |
| Seagate ST9500325AS 500GB          | 4         | 0.58%   |
| Seagate ST9320423AS 320GB          | 4         | 0.58%   |
| Seagate ST2000LM007-1R8174 2TB     | 4         | 0.58%   |
| Sandisk NVMe SSD Drive 1024GB      | 4         | 0.58%   |
| Samsung SSD 860 EVO 1TB            | 4         | 0.58%   |
| Samsung NVMe SSD Drive 1024GB      | 4         | 0.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 3         | 0.43%   |
| Toshiba NVMe SSD Drive 256GB       | 3         | 0.43%   |
| Toshiba NVMe SSD Drive 1024GB      | 3         | 0.43%   |
| SK Hynix PC711 NVMe 512GB          | 3         | 0.43%   |
| SK Hynix PC401 NVMe 512GB          | 3         | 0.43%   |
| SK Hynix NVMe SSD Drive 512GB      | 3         | 0.43%   |
| Seagate ST9250410AS 250GB          | 3         | 0.43%   |
| Seagate ST320LT020-9YG142 320GB    | 3         | 0.43%   |
| Seagate ST2000LM015-2E8174 2TB     | 3         | 0.43%   |
| Seagate ST1000LM049-2GH172 1TB     | 3         | 0.43%   |
| Samsung SSD 970 EVO Plus 1TB       | 3         | 0.43%   |
| Samsung SSD 970 EVO 500GB          | 3         | 0.43%   |
| Samsung NVMe SSD Drive 500GB       | 3         | 0.43%   |
| Samsung NVMe SSD Drive 1TB         | 3         | 0.43%   |
| Samsung MZVLQ512HBLU-00B00 512GB   | 3         | 0.43%   |
| Micron/Crucial NVMe SSD Drive 1TB  | 3         | 0.43%   |
| KIOXIA KBG40ZNV256G 256GB          | 3         | 0.43%   |
| KIOXIA KBG40ZNS512G NVMe 512GB     | 3         | 0.43%   |
| Kingston NVMe SSD Drive 512GB      | 3         | 0.43%   |
| Hitachi HTS547550A9E384 500GB      | 3         | 0.43%   |
| HGST HTS541010A9E680 1TB           | 3         | 0.43%   |
| YMTC PC005 512GB                   | 2         | 0.29%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 2         | 0.29%   |
| WDC WDS500G2B0B-00YS70 500GB SSD   | 2         | 0.29%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 2         | 0.29%   |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 2         | 0.29%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 2         | 0.29%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 2         | 0.29%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 2         | 0.29%   |
| WDC WD20SPZX-21UA7T0 2TB           | 2         | 0.29%   |
| WDC WD10SPZX-21Z10T0 1TB           | 2         | 0.29%   |
| WDC WD10SPZX-08Z10 1TB             | 2         | 0.29%   |
| WDC WD10JPVT-08A1YT2 1TB           | 2         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 75        | 83     | 38.66%  |
| WDC                 | 45        | 46     | 23.2%   |
| Toshiba             | 34        | 35     | 17.53%  |
| HGST                | 18        | 20     | 9.28%   |
| Hitachi             | 13        | 14     | 6.7%    |
| Samsung Electronics | 3         | 3      | 1.55%   |
| Fujitsu             | 3         | 3      | 1.55%   |
| SABRENT             | 2         | 2      | 1.03%   |
| Unknown             | 1         | 1      | 0.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 39        | 40     | 22.03%  |
| Kingston            | 21        | 24     | 11.86%  |
| SanDisk             | 19        | 20     | 10.73%  |
| Crucial             | 12        | 12     | 6.78%   |
| WDC                 | 11        | 11     | 6.21%   |
| Toshiba             | 9         | 9      | 5.08%   |
| Micron Technology   | 6         | 6      | 3.39%   |
| LITEON              | 6         | 6      | 3.39%   |
| SK Hynix            | 5         | 6      | 2.82%   |
| Apple               | 5         | 5      | 2.82%   |
| Intel               | 4         | 4      | 2.26%   |
| SPCC                | 3         | 4      | 1.69%   |
| Lexar               | 3         | 3      | 1.69%   |
| Transcend           | 2         | 2      | 1.13%   |
| LITEONIT            | 2         | 2      | 1.13%   |
| Intenso             | 2         | 2      | 1.13%   |
| Corsair             | 2         | 2      | 1.13%   |
| China               | 2         | 2      | 1.13%   |
| A-DATA Technology   | 2         | 3      | 1.13%   |
| Verbatim            | 1         | 1      | 0.56%   |
| ValueTech           | 1         | 1      | 0.56%   |
| Team                | 1         | 1      | 0.56%   |
| Seagate             | 1         | 1      | 0.56%   |
| PNY                 | 1         | 1      | 0.56%   |
| PLEXTOR             | 1         | 1      | 0.56%   |
| Patriot             | 1         | 1      | 0.56%   |
| OSCOO               | 1         | 1      | 0.56%   |
| ORTIAL              | 1         | 1      | 0.56%   |
| OCZ                 | 1         | 1      | 0.56%   |
| Netac               | 1         | 1      | 0.56%   |
| LDLC                | 1         | 1      | 0.56%   |
| KingSpec            | 1         | 1      | 0.56%   |
| KingDian            | 1         | 1      | 0.56%   |
| JMicron             | 1         | 1      | 0.56%   |
| GOODRAM             | 1         | 1      | 0.56%   |
| Freecom             | 1         | 1      | 0.56%   |
| Emtec               | 1         | 1      | 0.56%   |
| DRVEO               | 1         | 1      | 0.56%   |
| CT500MX5            | 1         | 1      | 0.56%   |
| ASMT                | 1         | 1      | 0.56%   |
| AMD                 | 1         | 2      | 0.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 250       | 293    | 38.88%  |
| HDD     | 189       | 207    | 29.39%  |
| SSD     | 170       | 186    | 26.44%  |
| MMC     | 27        | 30     | 4.2%    |
| Unknown | 7         | 9      | 1.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 319       | 376    | 51.7%   |
| NVMe | 249       | 291    | 40.36%  |
| MMC  | 27        | 30     | 4.38%   |
| SAS  | 22        | 28     | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 231       | 262    | 65.44%  |
| 0.51-1.0   | 105       | 114    | 29.75%  |
| 1.01-2.0   | 15        | 15     | 4.25%   |
| 4.01-10.0  | 2         | 2      | 0.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 164       | 29.98%  |
| 101-250        | 156       | 28.52%  |
| 501-1000       | 82        | 14.99%  |
| 51-100         | 41        | 7.5%    |
| 1001-2000      | 35        | 6.4%    |
| 1-20           | 28        | 5.12%   |
| 21-50          | 18        | 3.29%   |
| 2001-3000      | 11        | 2.01%   |
| More than 3000 | 6         | 1.1%    |
| Unknown        | 6         | 1.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 199       | 36.25%  |
| 21-50          | 115       | 20.95%  |
| 51-100         | 80        | 14.57%  |
| 101-250        | 76        | 13.84%  |
| 251-500        | 38        | 6.92%   |
| 501-1000       | 22        | 4.01%   |
| 1001-2000      | 8         | 1.46%   |
| Unknown        | 6         | 1.09%   |
| More than 3000 | 3         | 0.55%   |
| 2001-3000      | 2         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB           | 3         | 3      | 10.34%  |
| WDC WD5000BEVT-22A0RT0 500GB             | 2         | 2      | 6.9%    |
| SK Hynix HFS256G39TND-N210A 256GB SSD    | 2         | 2      | 6.9%    |
| WDC WD5000BEVT-26A0RT0 500GB             | 1         | 1      | 3.45%   |
| WDC WD10JPVT-08A1YT2 1TB                 | 1         | 1      | 3.45%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 3.45%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1      | 3.45%   |
| SK Hynix PC401 NVMe 512GB                | 1         | 1      | 3.45%   |
| Seagate ST9500325AS 500GB                | 1         | 1      | 3.45%   |
| Seagate ST500LT012-9WS142 500GB          | 1         | 1      | 3.45%   |
| Seagate ST320LT020-9YG142 320GB          | 1         | 1      | 3.45%   |
| Seagate ST1000LM048-2E7172 1TB           | 1         | 1      | 3.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1      | 3.45%   |
| SanDisk SD7SN3Q-256G-1006 256GB SSD      | 1         | 1      | 3.45%   |
| LITEON CV8-8E128-HP 128GB SSD            | 1         | 1      | 3.45%   |
| Kingston SV300S37A120G 120GB SSD         | 1         | 2      | 3.45%   |
| Hitachi HTS725032A9A364 320GB            | 1         | 1      | 3.45%   |
| Hitachi HTS543232L9A300 320GB            | 1         | 1      | 3.45%   |
| Hitachi HTS543232A7A384 320GB            | 1         | 1      | 3.45%   |
| HGST HTS725050A7E630 500GB               | 1         | 1      | 3.45%   |
| HGST HTS545050A7E680 500GB               | 1         | 1      | 3.45%   |
| HGST HTS541010A9E680 1TB                 | 1         | 1      | 3.45%   |
| Crucial CT1000MX500SSD1 1TB              | 1         | 1      | 3.45%   |
| ASMT 2115 256GB                          | 1         | 1      | 3.45%   |
| A-DATA Technology IM2P33F3A NVMe 256GB   | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 8         | 8      | 27.59%  |
| WDC               | 4         | 4      | 13.79%  |
| SK Hynix          | 3         | 3      | 10.34%  |
| Hitachi           | 3         | 3      | 10.34%  |
| HGST              | 3         | 3      | 10.34%  |
| Toshiba           | 2         | 2      | 6.9%    |
| SanDisk           | 1         | 1      | 3.45%   |
| LITEON            | 1         | 1      | 3.45%   |
| Kingston          | 1         | 2      | 3.45%   |
| Crucial           | 1         | 1      | 3.45%   |
| ASMT              | 1         | 1      | 3.45%   |
| A-DATA Technology | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 8      | 42.11%  |
| WDC     | 4         | 4      | 21.05%  |
| Hitachi | 3         | 3      | 15.79%  |
| HGST    | 3         | 3      | 15.79%  |
| Toshiba | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 19     | 65.52%  |
| SSD  | 8         | 9      | 27.59%  |
| NVMe | 2         | 2      | 6.9%    |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 336       | 443    | 58.13%  |
| Works    | 213       | 252    | 36.85%  |
| Malfunc  | 29        | 30     | 5.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 354       | 52.76%  |
| Samsung Electronics            | 79        | 11.77%  |
| AMD                            | 64        | 9.54%   |
| Sandisk                        | 43        | 6.41%   |
| SK Hynix                       | 34        | 5.07%   |
| Toshiba America Info Systems   | 20        | 2.98%   |
| Micron Technology              | 14        | 2.09%   |
| Kingston Technology Company    | 13        | 1.94%   |
| KIOXIA                         | 11        | 1.64%   |
| Phison Electronics             | 9         | 1.34%   |
| ADATA Technology               | 7         | 1.04%   |
| Nvidia                         | 4         | 0.6%    |
| Micron/Crucial Technology      | 4         | 0.6%    |
| Yangtze Memory Technologies    | 3         | 0.45%   |
| Solid State Storage Technology | 3         | 0.45%   |
| Realtek Semiconductor          | 2         | 0.3%    |
| Marvell Technology Group       | 2         | 0.3%    |
| Lite-On Technology             | 2         | 0.3%    |
| Lenovo                         | 1         | 0.15%   |
| ASMedia Technology             | 1         | 0.15%   |
| Apple                          | 1         | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 57        | 7.99%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 37        | 5.19%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 34        | 4.77%   |
| Intel Volume Management Device NVMe RAID Controller                              | 32        | 4.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 32        | 4.49%   |
| Samsung NVMe SSD Controller 980                                                  | 30        | 4.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 30        | 4.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 28        | 3.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 21        | 2.95%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 18        | 2.52%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 17        | 2.38%   |
| SK Hynix Gold P31 SSD                                                            | 16        | 2.24%   |
| Micron Non-Volatile memory controller                                            | 14        | 1.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 13        | 1.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 12        | 1.68%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 12        | 1.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 12        | 1.68%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 11        | 1.54%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 11        | 1.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 11        | 1.54%   |
| KIOXIA Non-Volatile memory controller                                            | 11        | 1.54%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 11        | 1.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 1.54%   |
| Intel SSD 660P Series                                                            | 9         | 1.26%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 8         | 1.12%   |
| Intel Comet Lake SATA AHCI Controller                                            | 8         | 1.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 8         | 1.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 1.12%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 7         | 0.98%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 7         | 0.98%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 7         | 0.98%   |
| SK Hynix Non-Volatile memory controller                                          | 6         | 0.84%   |
| SK Hynix BC511                                                                   | 6         | 0.84%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 6         | 0.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 0.84%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 0.84%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 0.84%   |
| ADATA Non-Volatile memory controller                                             | 6         | 0.84%   |
| Phison PS5013 E13 NVMe Controller                                                | 5         | 0.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 5         | 0.7%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 5         | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 5         | 0.7%    |
| Sandisk PC SN520 NVMe SSD                                                        | 4         | 0.56%   |
| Intel Non-Volatile memory controller                                             | 4         | 0.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 0.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 4         | 0.56%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 4         | 0.56%   |
| Yangtze Memory Non-Volatile memory controller                                    | 3         | 0.42%   |
| Solid State Storage Non-Volatile memory controller                               | 3         | 0.42%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 3         | 0.42%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 0.42%   |
| Samsung Electronics SATA controller                                              | 3         | 0.42%   |
| Phison E12 NVMe Controller                                                       | 3         | 0.42%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 3         | 0.42%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 0.42%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 2         | 0.28%   |
| Sandisk Non-Volatile memory controller                                           | 2         | 0.28%   |
| Realtek Realtek Non-Volatile memory controller                                   | 2         | 0.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 360       | 52.25%  |
| NVMe | 246       | 35.7%   |
| RAID | 62        | 9%      |
| IDE  | 21        | 3.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 438       | 80.66%  |
| AMD    | 105       | 19.34%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 20        | 3.68%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 12        | 2.21%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 10        | 1.84%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 10        | 1.84%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 9         | 1.66%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 1.66%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 9         | 1.66%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 1.47%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 1.47%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 8         | 1.47%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 8         | 1.47%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 8         | 1.47%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 1.29%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 6         | 1.1%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 6         | 1.1%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 1.1%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 6         | 1.1%    |
| Intel Core i3-2310M CPU @ 2.10GHz             | 6         | 1.1%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 6         | 1.1%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 1.1%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 0.92%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 5         | 0.92%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 5         | 0.92%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 5         | 0.92%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 0.92%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 0.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.92%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 5         | 0.92%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 5         | 0.92%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz       | 5         | 0.92%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 0.92%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 4         | 0.74%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 0.74%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 0.74%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 4         | 0.74%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 0.74%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 0.74%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz       | 4         | 0.74%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 4         | 0.74%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 0.74%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 4         | 0.74%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 3         | 0.55%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 3         | 0.55%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 3         | 0.55%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.55%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 3         | 0.55%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 0.55%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 0.55%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 0.55%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 0.55%   |
| Intel Core i5-5257U CPU @ 2.70GHz             | 3         | 0.55%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 0.55%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.55%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 0.55%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 3         | 0.55%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.55%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 3         | 0.55%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 3         | 0.55%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 3         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 126       | 23.2%   |
| Intel Core i7                  | 116       | 21.36%  |
| Other                          | 75        | 13.81%  |
| Intel Core i3                  | 39        | 7.18%   |
| AMD Ryzen 5                    | 34        | 6.26%   |
| Intel Celeron                  | 26        | 4.79%   |
| AMD Ryzen 7                    | 26        | 4.79%   |
| Intel Core 2 Duo               | 24        | 4.42%   |
| Intel Pentium                  | 10        | 1.84%   |
| Intel Core i9                  | 6         | 1.1%    |
| Intel Pentium Silver           | 5         | 0.92%   |
| Intel Pentium Dual-Core        | 5         | 0.92%   |
| AMD Ryzen 9                    | 5         | 0.92%   |
| AMD Ryzen 7 PRO                | 4         | 0.74%   |
| AMD E2                         | 4         | 0.74%   |
| AMD A6                         | 4         | 0.74%   |
| AMD A10                        | 4         | 0.74%   |
| Intel Core m3                  | 3         | 0.55%   |
| Intel Atom                     | 3         | 0.55%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.37%   |
| AMD Ryzen 5 PRO                | 2         | 0.37%   |
| AMD Ryzen 3                    | 2         | 0.37%   |
| AMD E                          | 2         | 0.37%   |
| AMD A8                         | 2         | 0.37%   |
| AMD A4                         | 2         | 0.37%   |
| Intel Pentium Dual             | 1         | 0.18%   |
| Intel Core m7                  | 1         | 0.18%   |
| Intel Core M                   | 1         | 0.18%   |
| Intel Core 2                   | 1         | 0.18%   |
| Intel Celeron Dual-Core        | 1         | 0.18%   |
| AMD Sempron                    | 1         | 0.18%   |
| AMD PRO A8                     | 1         | 0.18%   |
| AMD PRO A10                    | 1         | 0.18%   |
| AMD Phenom II                  | 1         | 0.18%   |
| AMD FX                         | 1         | 0.18%   |
| AMD E1                         | 1         | 0.18%   |
| AMD Athlon II Dual-Core        | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 236       | 43.46%  |
| 4      | 200       | 36.83%  |
| 8      | 52        | 9.58%   |
| 6      | 50        | 9.21%   |
| 1      | 4         | 0.74%   |
| 3      | 1         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 543       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 429       | 79.01%  |
| 1      | 114       | 20.99%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 543       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 298       | 54.08%  |
| 0x806c1    | 42        | 7.62%   |
| 0xa0652    | 15        | 2.72%   |
| 0x706e5    | 14        | 2.54%   |
| 0x0a50000c | 13        | 2.36%   |
| 0x906ea    | 12        | 2.18%   |
| 0x806d1    | 11        | 2%      |
| 0x08600106 | 11        | 2%      |
| 0x806ec    | 10        | 1.81%   |
| 0x806ea    | 10        | 1.81%   |
| 0x806e9    | 10        | 1.81%   |
| 0x306a9    | 10        | 1.81%   |
| 0x206a7    | 9         | 1.63%   |
| 0x906e9    | 7         | 1.27%   |
| 0x406e3    | 7         | 1.27%   |
| 0x1067a    | 7         | 1.27%   |
| 0x08608102 | 7         | 1.27%   |
| 0x306d4    | 6         | 1.09%   |
| 0x306c3    | 5         | 0.91%   |
| 0x806eb    | 4         | 0.73%   |
| 0x20655    | 4         | 0.73%   |
| 0x08108102 | 4         | 0.73%   |
| 0x506c9    | 3         | 0.54%   |
| 0x08608103 | 3         | 0.54%   |
| 0x08600102 | 3         | 0.54%   |
| 0x906c0    | 2         | 0.36%   |
| 0x706a1    | 2         | 0.36%   |
| 0x406c4    | 2         | 0.36%   |
| 0x406c3    | 2         | 0.36%   |
| 0x20652    | 2         | 0.36%   |
| 0x0a50000b | 2         | 0.36%   |
| 0x06006705 | 2         | 0.36%   |
| 0x706a8    | 1         | 0.18%   |
| 0x506e3    | 1         | 0.18%   |
| 0x40651    | 1         | 0.18%   |
| 0x106ca    | 1         | 0.18%   |
| 0x08600104 | 1         | 0.18%   |
| 0x08108109 | 1         | 0.18%   |
| 0x08101007 | 1         | 0.18%   |
| 0x06006704 | 1         | 0.18%   |
| 0x0600611a | 1         | 0.18%   |
| 0x06006118 | 1         | 0.18%   |
| 0x06006110 | 1         | 0.18%   |
| 0x02000032 | 1         | 0.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 108       | 19.85%  |
| TigerLake       | 55        | 10.11%  |
| SandyBridge     | 43        | 7.9%    |
| IvyBridge       | 32        | 5.88%   |
| Westmere        | 29        | 5.33%   |
| IceLake         | 29        | 5.33%   |
| Penryn          | 27        | 4.96%   |
| Zen 2           | 22        | 4.04%   |
| Skylake         | 22        | 4.04%   |
| Haswell         | 21        | 3.86%   |
| Unknown         | 20        | 3.68%   |
| CometLake       | 18        | 3.31%   |
| Zen 3           | 17        | 3.13%   |
| Broadwell       | 16        | 2.94%   |
| Silvermont      | 15        | 2.76%   |
| Zen+            | 14        | 2.57%   |
| Excavator       | 13        | 2.39%   |
| Goldmont plus   | 6         | 1.1%    |
| Core            | 6         | 1.1%    |
| Zen             | 5         | 0.92%   |
| Goldmont        | 4         | 0.74%   |
| K8 & K10 hybrid | 3         | 0.55%   |
| K10 Llano       | 3         | 0.55%   |
| Jaguar          | 3         | 0.55%   |
| Bobcat          | 3         | 0.55%   |
| Tremont         | 2         | 0.37%   |
| Steamroller     | 2         | 0.37%   |
| Puma            | 2         | 0.37%   |
| K10             | 2         | 0.37%   |
| Piledriver      | 1         | 0.18%   |
| Bonnell         | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 406       | 57.75%  |
| Nvidia | 165       | 23.47%  |
| AMD    | 132       | 18.78%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 51        | 7.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 39        | 5.45%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 29        | 4.06%   |
| Intel UHD Graphics 620                                                                   | 24        | 3.36%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 24        | 3.36%   |
| AMD Renoir                                                                               | 22        | 3.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 20        | 2.8%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 16        | 2.24%   |
| AMD Cezanne                                                                              | 16        | 2.24%   |
| AMD Lucienne                                                                             | 15        | 2.1%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 14        | 1.96%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 14        | 1.96%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 14        | 1.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 1.96%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 1.82%   |
| Intel HD Graphics 630                                                                    | 13        | 1.82%   |
| Intel HD Graphics 620                                                                    | 13        | 1.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 1.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 1.68%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 1.68%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 11        | 1.54%   |
| Intel HD Graphics 5500                                                                   | 11        | 1.54%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 1.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1.26%   |
| Nvidia GP108M [GeForce MX150]                                                            | 8         | 1.12%   |
| Intel HD Graphics 530                                                                    | 8         | 1.12%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 1.12%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 8         | 1.12%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 0.98%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 7         | 0.98%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 6         | 0.84%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 6         | 0.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 0.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 0.84%   |
| Intel Iris Plus Graphics G7                                                              | 6         | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.7%    |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 5         | 0.7%    |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 5         | 0.7%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 5         | 0.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 0.7%    |
| Nvidia TU117M [GeForce MX450]                                                            | 4         | 0.56%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 4         | 0.56%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 4         | 0.56%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 4         | 0.56%   |
| Intel Tiger Lake UHD Graphics                                                            | 4         | 0.56%   |
| Intel HD Graphics 500                                                                    | 4         | 0.56%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 4         | 0.56%   |
| Intel Comet Lake UHD Graphics                                                            | 4         | 0.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 0.56%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 3         | 0.42%   |
| Nvidia GP108M [GeForce MX250]                                                            | 3         | 0.42%   |
| Nvidia GP107M [GeForce MX350]                                                            | 3         | 0.42%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.42%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 3         | 0.42%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 0.42%   |
| Intel Iris Graphics 6100                                                                 | 3         | 0.42%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.42%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 0.42%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 3         | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 258       | 47.51%  |
| Intel + Nvidia | 130       | 23.94%  |
| 1 x AMD        | 99        | 18.23%  |
| 1 x Nvidia     | 22        | 4.05%   |
| Intel + AMD    | 17        | 3.13%   |
| AMD + Nvidia   | 12        | 2.21%   |
| 2 x AMD        | 4         | 0.74%   |
| 2 x Nvidia     | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 448       | 82.05%  |
| Proprietary | 92        | 16.85%  |
| Unknown     | 6         | 1.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 438       | 80.66%  |
| 0.01-0.5   | 44        | 8.1%    |
| 1.01-2.0   | 24        | 4.42%   |
| 3.01-4.0   | 18        | 3.31%   |
| 0.51-1.0   | 8         | 1.47%   |
| 7.01-8.0   | 5         | 0.92%   |
| 5.01-6.0   | 5         | 0.92%   |
| 8.01-16.0  | 1         | 0.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 117       | 18.66%  |
| LG Display              | 89        | 14.19%  |
| Chimei Innolux          | 82        | 13.08%  |
| BOE                     | 82        | 13.08%  |
| Samsung Electronics     | 61        | 9.73%   |
| Sharp                   | 33        | 5.26%   |
| Lenovo                  | 19        | 3.03%   |
| Dell                    | 15        | 2.39%   |
| Apple                   | 14        | 2.23%   |
| Chi Mei Optoelectronics | 11        | 1.75%   |
| Acer                    | 10        | 1.59%   |
| PANDA                   | 9         | 1.44%   |
| Goldstar                | 9         | 1.44%   |
| Philips                 | 8         | 1.28%   |
| Hewlett-Packard         | 7         | 1.12%   |
| InfoVision              | 6         | 0.96%   |
| Ancor Communications    | 6         | 0.96%   |
| LG Philips              | 5         | 0.8%    |
| BenQ                    | 5         | 0.8%    |
| AOC                     | 5         | 0.8%    |
| CSO                     | 4         | 0.64%   |
| Unknown                 | 3         | 0.48%   |
| Sony                    | 3         | 0.48%   |
| Iiyama                  | 3         | 0.48%   |
| KDC                     | 2         | 0.32%   |
| JDI                     | 2         | 0.32%   |
| Westinghouse            | 1         | 0.16%   |
| ViewSonic               | 1         | 0.16%   |
| TIANMA XM               | 1         | 0.16%   |
| TCL                     | 1         | 0.16%   |
| STA                     | 1         | 0.16%   |
| Seiko/Epson             | 1         | 0.16%   |
| Sceptre Tech            | 1         | 0.16%   |
| NEC Computers           | 1         | 0.16%   |
| MStar                   | 1         | 0.16%   |
| Mi                      | 1         | 0.16%   |
| KEB                     | 1         | 0.16%   |
| JXC                     | 1         | 0.16%   |
| GDH                     | 1         | 0.16%   |
| DZX                     | 1         | 0.16%   |
| CVT                     | 1         | 0.16%   |
| CMN                     | 1         | 0.16%   |
| ASUSTek Computer        | 1         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 7         | 1.1%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 7         | 1.1%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 6         | 0.94%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 0.94%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 6         | 0.94%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 5         | 0.78%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch         | 5         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 5         | 0.78%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 5         | 0.78%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 5         | 0.78%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 4         | 0.63%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 4         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch    | 4         | 0.63%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch             | 4         | 0.63%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 4         | 0.63%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                  | 4         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 4         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 4         | 0.63%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 0.63%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 3         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 3         | 0.47%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch        | 3         | 0.47%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch             | 3         | 0.47%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 3         | 0.47%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 3         | 0.47%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 3         | 0.47%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 3         | 0.47%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch           | 3         | 0.47%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch            | 3         | 0.47%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 2         | 0.31%   |
| Sony Nvidia Defaul SNY05FA 1366x768 290x170mm 13.2-inch                  | 2         | 0.31%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                  | 2         | 0.31%   |
| Sharp LCD Monitor SHP14D6 3840x2400 366x229mm 17.0-inch                  | 2         | 0.31%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                  | 2         | 0.31%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch                  | 2         | 0.31%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 2         | 0.31%   |
| Samsung Electronics S34J55x SAM0F71 3440x1440 797x333mm 34.0-inch        | 2         | 0.31%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch        | 2         | 0.31%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch     | 2         | 0.31%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch    | 2         | 0.31%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch        | 2         | 0.31%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.31%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch             | 2         | 0.31%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch             | 2         | 0.31%   |
| LG Display LCD Monitor LGD0596 1920x1080 382x215mm 17.3-inch             | 2         | 0.31%   |
| LG Display LCD Monitor LGD0589 1920x1080 294x165mm 13.3-inch             | 2         | 0.31%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 2         | 0.31%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch              | 2         | 0.31%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 0.31%   |
| LG Display LCD Monitor LGD027A 1600x900 380x210mm 17.1-inch              | 2         | 0.31%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 2         | 0.31%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 2         | 0.31%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 2         | 0.31%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.31%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                    | 2         | 0.31%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch             | 2         | 0.31%   |
| Hewlett-Packard E243i HPN3463 1920x1200 518x324mm 24.1-inch              | 2         | 0.31%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 2         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 2         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 270       | 45.45%  |
| 1366x768 (WXGA)   | 136       | 22.9%   |
| 1600x900 (HD+)    | 34        | 5.72%   |
| 1280x800 (WXGA)   | 23        | 3.87%   |
| 2560x1440 (QHD)   | 21        | 3.54%   |
| 3840x2160 (4K)    | 18        | 3.03%   |
| 1920x1200 (WUXGA) | 16        | 2.69%   |
| 3840x2400         | 11        | 1.85%   |
| 2160x1440         | 11        | 1.85%   |
| 1440x900 (WXGA+)  | 11        | 1.85%   |
| 2560x1600         | 9         | 1.52%   |
| 3440x1440         | 6         | 1.01%   |
| 1280x1024 (SXGA)  | 6         | 1.01%   |
| 3456x2160         | 4         | 0.67%   |
| 3000x2000         | 4         | 0.67%   |
| 2880x1800         | 3         | 0.51%   |
| 2288x1287         | 2         | 0.34%   |
| 2256x1504         | 2         | 0.34%   |
| 3200x1800 (QHD+)  | 1         | 0.17%   |
| 2880x1920         | 1         | 0.17%   |
| 2560x1080         | 1         | 0.17%   |
| 2240x1400         | 1         | 0.17%   |
| 2048x1152         | 1         | 0.17%   |
| 1720x1440         | 1         | 0.17%   |
| 1360x768          | 1         | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 255       | 40.73%  |
| 13      | 100       | 15.97%  |
| 14      | 90        | 14.38%  |
| 17      | 47        | 7.51%   |
| 27      | 25        | 3.99%   |
| 24      | 23        | 3.67%   |
| 12      | 13        | 2.08%   |
| 23      | 9         | 1.44%   |
| 21      | 9         | 1.44%   |
| 19      | 9         | 1.44%   |
| 34      | 7         | 1.12%   |
| 16      | 7         | 1.12%   |
| 32      | 5         | 0.8%    |
| 18      | 5         | 0.8%    |
| Unknown | 5         | 0.8%    |
| 28      | 3         | 0.48%   |
| 142     | 2         | 0.32%   |
| 35      | 2         | 0.32%   |
| 31      | 2         | 0.32%   |
| 11      | 2         | 0.32%   |
| 84      | 1         | 0.16%   |
| 52      | 1         | 0.16%   |
| 26      | 1         | 0.16%   |
| 25      | 1         | 0.16%   |
| 20      | 1         | 0.16%   |
| 10      | 1         | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 380       | 61.19%  |
| 201-300        | 79        | 12.72%  |
| 501-600        | 58        | 9.34%   |
| 351-400        | 57        | 9.18%   |
| 401-500        | 18        | 2.9%    |
| 701-800        | 13        | 2.09%   |
| 601-700        | 6         | 0.97%   |
| Unknown        | 5         | 0.81%   |
| More than 2000 | 2         | 0.32%   |
| 801-900        | 1         | 0.16%   |
| 1501-2000      | 1         | 0.16%   |
| 1001-1500      | 1         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 439       | 78.11%  |
| 16/10   | 81        | 14.41%  |
| 3/2     | 19        | 3.38%   |
| 21/9    | 8         | 1.42%   |
| 5/4     | 7         | 1.25%   |
| Unknown | 4         | 0.71%   |
| 1.00    | 2         | 0.36%   |
| 6/5     | 1         | 0.18%   |
| 2.01    | 1         | 0.18%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 256       | 40.83%  |
| 81-90          | 155       | 24.72%  |
| 121-130        | 38        | 6.06%   |
| 71-80          | 35        | 5.58%   |
| 201-250        | 33        | 5.26%   |
| 301-350        | 25        | 3.99%   |
| 351-500        | 19        | 3.03%   |
| 61-70          | 13        | 2.07%   |
| 151-200        | 13        | 2.07%   |
| 141-150        | 8         | 1.28%   |
| 251-300        | 7         | 1.12%   |
| 131-140        | 7         | 1.12%   |
| Unknown        | 5         | 0.8%    |
| More than 1000 | 4         | 0.64%   |
| 111-120        | 4         | 0.64%   |
| 51-60          | 2         | 0.32%   |
| 91-100         | 2         | 0.32%   |
| 41-50          | 1         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 254       | 41.17%  |
| 101-120       | 176       | 28.53%  |
| 51-100        | 93        | 15.07%  |
| 161-240       | 54        | 8.75%   |
| More than 240 | 32        | 5.19%   |
| Unknown       | 5         | 0.81%   |
| 1-50          | 3         | 0.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 431       | 78.94%  |
| 2     | 89        | 16.3%   |
| 0     | 15        | 2.75%   |
| 3     | 10        | 1.83%   |
| 6     | 1         | 0.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 310       | 36.51%  |
| Realtek Semiconductor             | 266       | 31.33%  |
| Qualcomm Atheros                  | 117       | 13.78%  |
| Broadcom                          | 40        | 4.71%   |
| MEDIATEK                          | 17        | 2%      |
| Broadcom Limited                  | 16        | 1.88%   |
| Marvell Technology Group          | 14        | 1.65%   |
| Ralink                            | 10        | 1.18%   |
| TP-Link                           | 7         | 0.82%   |
| DisplayLink                       | 6         | 0.71%   |
| Qualcomm                          | 5         | 0.59%   |
| Ericsson Business Mobile Networks | 4         | 0.47%   |
| Xiaomi                            | 3         | 0.35%   |
| Sierra Wireless                   | 3         | 0.35%   |
| Samsung Electronics               | 3         | 0.35%   |
| Nvidia                            | 3         | 0.35%   |
| Lenovo                            | 3         | 0.35%   |
| Dell                              | 3         | 0.35%   |
| Toshiba                           | 2         | 0.24%   |
| OnePlus                           | 2         | 0.24%   |
| Microsoft                         | 2         | 0.24%   |
| Texas Instruments                 | 1         | 0.12%   |
| OPPO Electronics                  | 1         | 0.12%   |
| Motorola PCS                      | 1         | 0.12%   |
| Linksys                           | 1         | 0.12%   |
| LG Electronics                    | 1         | 0.12%   |
| JMicron Technology                | 1         | 0.12%   |
| Hewlett-Packard                   | 1         | 0.12%   |
| Franklin Wireless                 | 1         | 0.12%   |
| Foxconn / Hon Hai                 | 1         | 0.12%   |
| Edimax Technology                 | 1         | 0.12%   |
| D-Link                            | 1         | 0.12%   |
| ASIX Electronics                  | 1         | 0.12%   |
| Aquantia                          | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 165       | 16.67%  |
| Intel Wi-Fi 6 AX201                                               | 43        | 4.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 37        | 3.74%   |
| Intel Wi-Fi 6 AX200                                               | 31        | 3.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 29        | 2.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 23        | 2.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 23        | 2.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21        | 2.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 18        | 1.82%   |
| Intel Wireless 8265 / 8275                                        | 18        | 1.82%   |
| MEDIATEK Network controller                                       | 16        | 1.62%   |
| Intel Wireless 7265                                               | 16        | 1.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 15        | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 14        | 1.41%   |
| Intel Wireless 7260                                               | 13        | 1.31%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 13        | 1.31%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 12        | 1.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 12        | 1.21%   |
| Intel 82577LM Gigabit Network Connection                          | 12        | 1.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 1.11%   |
| Intel Wireless 3165                                               | 11        | 1.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 11        | 1.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 10        | 1.01%   |
| Intel Wireless 8260                                               | 10        | 1.01%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 10        | 1.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 9         | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 9         | 0.91%   |
| Intel Centrino Ultimate-N 6300                                    | 8         | 0.81%   |
| Intel Centrino Advanced-N 6200                                    | 8         | 0.81%   |
| Broadcom BCM43142 802.11b/g/n                                     | 8         | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 0.71%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 6         | 0.61%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 0.61%   |
| Intel WiFi Link 5100                                              | 6         | 0.61%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 0.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 6         | 0.61%   |
| Intel 82567LM Gigabit Network Connection                          | 6         | 0.61%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]       | 5         | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 5         | 0.51%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 5         | 0.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 0.51%   |
| Intel Ethernet Connection (13) I219-LM                            | 5         | 0.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5         | 0.51%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 5         | 0.51%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 5         | 0.51%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 0.51%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 4         | 0.4%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 4         | 0.4%    |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.4%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.4%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 4         | 0.4%    |
| Intel Wireless-AC 9260                                            | 4         | 0.4%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.4%    |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.4%    |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.4%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 4         | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.3%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 295       | 53.06%  |
| Qualcomm Atheros      | 97        | 17.45%  |
| Realtek Semiconductor | 74        | 13.31%  |
| Broadcom              | 30        | 5.4%    |
| MEDIATEK              | 17        | 3.06%   |
| Broadcom Limited      | 11        | 1.98%   |
| Ralink                | 10        | 1.8%    |
| TP-Link               | 6         | 1.08%   |
| Qualcomm              | 5         | 0.9%    |
| Sierra Wireless       | 3         | 0.54%   |
| Microsoft             | 2         | 0.36%   |
| Dell                  | 2         | 0.36%   |
| Linksys               | 1         | 0.18%   |
| Hewlett-Packard       | 1         | 0.18%   |
| Edimax Technology     | 1         | 0.18%   |
| D-Link                | 1         | 0.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 43        | 7.72%   |
| Intel Wi-Fi 6 AX200                                            | 31        | 5.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 23        | 4.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 23        | 4.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 18        | 3.23%   |
| Intel Wireless 8265 / 8275                                     | 18        | 3.23%   |
| MEDIATEK Network controller                                    | 16        | 2.87%   |
| Intel Wireless 7265                                            | 16        | 2.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 15        | 2.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 14        | 2.51%   |
| Intel Wireless 7260                                            | 13        | 2.33%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 13        | 2.33%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 12        | 2.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 12        | 2.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 1.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 11        | 1.97%   |
| Intel Wireless 3165                                            | 11        | 1.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 11        | 1.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10        | 1.8%    |
| Intel Wireless 8260                                            | 10        | 1.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 10        | 1.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 9         | 1.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 9         | 1.62%   |
| Intel Centrino Ultimate-N 6300                                 | 8         | 1.44%   |
| Intel Centrino Advanced-N 6200                                 | 8         | 1.44%   |
| Broadcom BCM43142 802.11b/g/n                                  | 8         | 1.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 6         | 1.08%   |
| Intel WiFi Link 5100                                           | 6         | 1.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 1.08%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]    | 5         | 0.9%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 5         | 0.9%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 5         | 0.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 5         | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 5         | 0.9%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 5         | 0.9%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 5         | 0.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 0.9%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 4         | 0.72%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 4         | 0.72%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 4         | 0.72%   |
| Intel Wireless-AC 9260                                         | 4         | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 4         | 0.72%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 4         | 0.72%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3         | 0.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 0.54%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 3         | 0.54%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 3         | 0.54%   |
| Intel Wireless 3160                                            | 3         | 0.54%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 3         | 0.54%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 0.54%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 0.54%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 0.54%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 3         | 0.54%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 3         | 0.54%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 0.54%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 0.54%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 3         | 0.54%   |
| Sierra Wireless MC8305 Modem                                   | 2         | 0.36%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 2         | 0.36%   |
| Realtek Realtek Network controller                             | 2         | 0.36%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 233       | 55.74%  |
| Intel                    | 96        | 22.97%  |
| Qualcomm Atheros         | 28        | 6.7%    |
| Broadcom                 | 15        | 3.59%   |
| Marvell Technology Group | 14        | 3.35%   |
| DisplayLink              | 6         | 1.44%   |
| Broadcom Limited         | 5         | 1.2%    |
| Xiaomi                   | 3         | 0.72%   |
| Nvidia                   | 3         | 0.72%   |
| Lenovo                   | 3         | 0.72%   |
| Samsung Electronics      | 2         | 0.48%   |
| OnePlus                  | 2         | 0.48%   |
| TP-Link                  | 1         | 0.24%   |
| OPPO Electronics         | 1         | 0.24%   |
| Motorola PCS             | 1         | 0.24%   |
| LG Electronics           | 1         | 0.24%   |
| JMicron Technology       | 1         | 0.24%   |
| Foxconn / Hon Hai        | 1         | 0.24%   |
| ASIX Electronics         | 1         | 0.24%   |
| Aquantia                 | 1         | 0.24%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 165       | 39.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 37        | 8.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 29        | 6.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 21        | 4.96%   |
| Intel 82577LM Gigabit Network Connection                                       | 12        | 2.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 7         | 1.65%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 6         | 1.42%   |
| Intel Ethernet Connection I219-LM                                              | 6         | 1.42%   |
| Intel 82567LM Gigabit Network Connection                                       | 6         | 1.42%   |
| Intel Ethernet Connection (13) I219-LM                                         | 5         | 1.18%   |
| Realtek RTL8125 2.5GbE Controller                                              | 4         | 0.95%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 4         | 0.95%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                                          | 4         | 0.95%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 0.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 0.71%   |
| Intel Ethernet Connection (6) I219-V                                           | 3         | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 0.71%   |
| Intel Ethernet Connection (13) I219-V                                          | 3         | 0.71%   |
| Intel 82579V Gigabit Network Connection                                        | 3         | 0.71%   |
| DisplayLink LAPDOCK                                                            | 3         | 0.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 0.71%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 0.71%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 0.47%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 2         | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.47%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.47%   |
| OnePlus SM8150-MTP _SN:D8D6033B                                                | 2         | 0.47%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.47%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 2         | 0.47%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 0.47%   |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 0.47%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.47%   |
| Intel Ethernet Connection (14) I219-LM                                         | 2         | 0.47%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.47%   |
| Intel Ethernet Connection (10) I219-LM                                         | 2         | 0.47%   |
| Intel 82567LF Gigabit Network Connection                                       | 2         | 0.47%   |
| DisplayLink Dell Universal Dock D6000                                          | 2         | 0.47%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                               | 2         | 0.47%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 2         | 0.47%   |
| TP-Link USB 10/100/1000 LAN                                                    | 1         | 0.24%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.24%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.24%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.24%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.24%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.24%   |
| OPPO realme X50 Pro 5G                                                         | 1         | 0.24%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 0.24%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.24%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.24%   |
| Motorola PCS moto g 5G                                                         | 1         | 0.24%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.24%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.24%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.24%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1         | 0.24%   |
| LG G2 Android Phone [tethering mode]                                           | 1         | 0.24%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 536       | 56.78%  |
| Ethernet | 398       | 42.16%  |
| Modem    | 8         | 0.85%   |
| Unknown  | 2         | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 492       | 67.31%  |
| Ethernet | 237       | 32.42%  |
| Unknown  | 2         | 0.27%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 362       | 66.67%  |
| 1     | 172       | 31.68%  |
| 0     | 6         | 1.1%    |
| 3     | 2         | 0.37%   |
| 4     | 1         | 0.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 391       | 71.61%  |
| Yes  | 155       | 28.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 234       | 52.58%  |
| Qualcomm Atheros Communications | 44        | 9.89%   |
| Realtek Semiconductor           | 38        | 8.54%   |
| Lite-On Technology              | 27        | 6.07%   |
| Broadcom                        | 21        | 4.72%   |
| IMC Networks                    | 17        | 3.82%   |
| Foxconn / Hon Hai               | 12        | 2.7%    |
| Apple                           | 12        | 2.7%    |
| Realtek                         | 10        | 2.25%   |
| Cambridge Silicon Radio         | 8         | 1.8%    |
| Dell                            | 5         | 1.12%   |
| Toshiba                         | 3         | 0.67%   |
| Alps Electric                   | 3         | 0.67%   |
| Ralink Technology               | 2         | 0.45%   |
| Ralink                          | 2         | 0.45%   |
| Hewlett-Packard                 | 2         | 0.45%   |
| ASUSTek Computer                | 2         | 0.45%   |
| Integrated System Solution      | 1         | 0.22%   |
| Foxconn International           | 1         | 0.22%   |
| Askey Computer                  | 1         | 0.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                | 136       | 30.56%  |
| Intel Bluetooth wireless interface                    | 47        | 10.56%  |
| Qualcomm Atheros  Bluetooth Device                    | 30        | 6.74%   |
| Intel AX200 Bluetooth                                 | 29        | 6.52%   |
| Realtek Bluetooth Radio                               | 24        | 5.39%   |
| Realtek Bluetooth Radio                               | 10        | 2.25%   |
| Apple Bluetooth Host Controller                       | 9         | 2.02%   |
| Realtek  Bluetooth 4.2 Adapter                        | 8         | 1.8%    |
| Lite-On Wireless_Device                               | 8         | 1.8%    |
| Lite-On Bluetooth Device                              | 8         | 1.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 8         | 1.8%    |
| Intel Centrino Bluetooth Wireless Transceiver         | 7         | 1.57%   |
| IMC Networks Wireless_Device                          | 7         | 1.57%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 6         | 1.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 6         | 1.35%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 6         | 1.35%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 6         | 1.35%   |
| Broadcom BCM2045B (BDC-2.1)                           | 6         | 1.35%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 5         | 1.12%   |
| Intel Wireless-AC 3168 Bluetooth                      | 5         | 1.12%   |
| IMC Networks Bluetooth Radio                          | 5         | 1.12%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 4         | 0.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 4         | 0.9%    |
| Toshiba Integrated Bluetooth HCI                      | 2         | 0.45%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter          | 2         | 0.45%   |
| Ralink RT3290 Bluetooth                               | 2         | 0.45%   |
| Qualcomm Atheros Bluetooth                            | 2         | 0.45%   |
| Lite-On Bluetooth Radio                               | 2         | 0.45%   |
| Lite-On Atheros AR3012 Bluetooth                      | 2         | 0.45%   |
| IMC Networks Bluetooth Device                         | 2         | 0.45%   |
| IMC Networks Bluetooth                                | 2         | 0.45%   |
| HP Broadcom 2070 Bluetooth Combo                      | 2         | 0.45%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth         | 2         | 0.45%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2         | 0.45%   |
| Foxconn / Hon Hai BCM43142A0                          | 2         | 0.45%   |
| Foxconn / Hon Hai BCM20702A0                          | 2         | 0.45%   |
| Dell DW375 Bluetooth Module                           | 2         | 0.45%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                  | 2         | 0.45%   |
| Apple Bluetooth HCI                                   | 2         | 0.45%   |
| Alps Electric BCM2046 Bluetooth Device                | 2         | 0.45%   |
| Toshiba Askey Bluetooth Module                        | 1         | 0.22%   |
| Realtek RTL8723B Bluetooth                            | 1         | 0.22%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1         | 0.22%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 0.22%   |
| Lite-On BCM43142A0                                    | 1         | 0.22%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.22%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 1         | 0.22%   |
| Foxconn International BCM43142A0 Bluetooth module     | 1         | 0.22%   |
| Foxconn / Hon Hai Wireless_Device                     | 1         | 0.22%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device       | 1         | 0.22%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller       | 1         | 0.22%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth       | 1         | 0.22%   |
| Dell Wireless 365 Bluetooth                           | 1         | 0.22%   |
| Dell Wireless 355 Bluetooth                           | 1         | 0.22%   |
| Dell BCM20702A0 Bluetooth Module                      | 1         | 0.22%   |
| Broadcom HP Portable SoftSailing                      | 1         | 0.22%   |
| Broadcom BCM43142A0 Bluetooth Device                  | 1         | 0.22%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 1         | 0.22%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1         | 0.22%   |
| Broadcom BCM20702A0 Bluetooth                         | 1         | 0.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 434       | 64.97%  |
| AMD                               | 113       | 16.92%  |
| Nvidia                            | 83        | 12.43%  |
| Realtek Semiconductor             | 4         | 0.6%    |
| C-Media Electronics               | 4         | 0.6%    |
| Sennheiser Communications         | 3         | 0.45%   |
| Logitech                          | 3         | 0.45%   |
| Lenovo                            | 3         | 0.45%   |
| Plantronics                       | 2         | 0.3%    |
| GN Netcom                         | 2         | 0.3%    |
| Elitegroup Computer Systems (ECS) | 2         | 0.3%    |
| Dell                              | 2         | 0.3%    |
| Texas Instruments                 | 1         | 0.15%   |
| SAVITECH                          | 1         | 0.15%   |
| Kingston Technology               | 1         | 0.15%   |
| Hewlett-Packard                   | 1         | 0.15%   |
| Google                            | 1         | 0.15%   |
| Generalplus Technology            | 1         | 0.15%   |
| Focusrite-Novation                | 1         | 0.15%   |
| FiiO Electronics Technology       | 1         | 0.15%   |
| ELMCU                             | 1         | 0.15%   |
| Creative Technology               | 1         | 0.15%   |
| Corsair                           | 1         | 0.15%   |
| Conexant Systems                  | 1         | 0.15%   |
| Conexant                          | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 67        | 8.45%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 56        | 7.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 55        | 6.94%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 52        | 6.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 41        | 5.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 33        | 4.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 29        | 3.66%   |
| Intel Cannon Lake PCH cAVS                                                                        | 25        | 3.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 21        | 2.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 18        | 2.27%   |
| Intel Comet Lake PCH cAVS                                                                         | 17        | 2.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 16        | 2.02%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 15        | 1.89%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 15        | 1.89%   |
| Intel Broadwell-U Audio Controller                                                                | 15        | 1.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 14        | 1.77%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 1.77%   |
| Intel CM238 HD Audio Controller                                                                   | 14        | 1.77%   |
| Intel 8 Series HD Audio Controller                                                                | 14        | 1.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 13        | 1.64%   |
| AMD FCH Azalia Controller                                                                         | 12        | 1.51%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 12        | 1.51%   |
| Nvidia Audio device                                                                               | 11        | 1.39%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 1.26%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 10        | 1.26%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 1.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 8         | 1.01%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 1.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 1.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 1.01%   |
| AMD High Definition Audio Controller                                                              | 8         | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 0.88%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 6         | 0.76%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 6         | 0.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 0.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 0.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 0.76%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 0.63%   |
| Realtek Semiconductor USB Audio                                                                   | 4         | 0.5%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.5%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 0.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 0.5%    |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 0.38%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.38%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.38%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 3         | 0.38%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.38%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.38%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 0.38%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 0.38%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 3         | 0.38%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 0.25%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.25%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.25%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.25%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.25%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                                         | 2         | 0.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.25%   |
| Intel Jasper Lake HD Graphics SGPC                                                                | 2         | 0.25%   |
| Elitegroup Computer Systems (ECS) FOSTEX USB AUDIO HP-A4                                          | 2         | 0.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 97        | 29.66%  |
| SK Hynix            | 64        | 19.57%  |
| Micron Technology   | 59        | 18.04%  |
| Unknown             | 25        | 7.65%   |
| Kingston            | 20        | 6.12%   |
| Crucial             | 18        | 5.5%    |
| Ramaxel Technology  | 8         | 2.45%   |
| Nanya Technology    | 6         | 1.83%   |
| A-DATA Technology   | 6         | 1.83%   |
| G.Skill             | 5         | 1.53%   |
| Corsair             | 5         | 1.53%   |
| Unknown (ABCD)      | 2         | 0.61%   |
| Neo Forza           | 2         | 0.61%   |
| Transcend           | 1         | 0.31%   |
| SMART Brazil        | 1         | 0.31%   |
| Sesame              | 1         | 0.31%   |
| Patriot             | 1         | 0.31%   |
| Elpida              | 1         | 0.31%   |
| Avant               | 1         | 0.31%   |
| AMD                 | 1         | 0.31%   |
| 8001000080AD        | 1         | 0.31%   |
| 48spaces            | 1         | 0.31%   |
| Unknown             | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s           | 12        | 3.57%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s       | 9         | 2.68%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s     | 9         | 2.68%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s          | 7         | 2.08%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8192MB SODIMM DDR4 3200MT/s         | 6         | 1.79%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s             | 5         | 1.49%   |
| Samsung RAM U6E3S4AA-MGCR 4GB Row Of Chips LPDDR4 4267MT/s      | 4         | 1.19%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s        | 4         | 1.19%   |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s       | 4         | 1.19%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s       | 3         | 0.89%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s     | 3         | 0.89%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s          | 3         | 0.89%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s        | 3         | 0.89%   |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s         | 3         | 0.89%   |
| Micron RAM 8ATF2G64HZ-3G2E2 16GB SODIMM DDR4 3200MT/s           | 3         | 0.89%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s        | 3         | 0.89%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s           | 3         | 0.89%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s            | 3         | 0.89%   |
| Unknown RAM Module 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.6%    |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s             | 2         | 0.6%    |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s             | 2         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                      | 2         | 0.6%    |
| SK Hynix RAM Module 4GB SODIMM DDR3 1867MT/s                    | 2         | 0.6%    |
| SK Hynix RAM Module 16GB SODIMM DDR4 3200MT/s                   | 2         | 0.6%    |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s      | 2         | 0.6%    |
| SK Hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s         | 2         | 0.6%    |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s          | 2         | 0.6%    |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s    | 2         | 0.6%    |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 2         | 0.6%    |
| SK Hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s      | 2         | 0.6%    |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.6%    |
| Samsung RAM Module 32GB SODIMM DDR4 3200MT/s                    | 2         | 0.6%    |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2         | 0.6%    |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s           | 2         | 0.6%    |
| Samsung RAM M471B5273BH1-CF8 4096MB SODIMM DDR3 1067MT/s        | 2         | 0.6%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 2         | 0.6%    |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.6%    |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s        | 2         | 0.6%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s           | 2         | 0.6%    |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.6%    |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s          | 2         | 0.6%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s           | 2         | 0.6%    |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s        | 2         | 0.6%    |
| Samsung RAM K4F6E3S4HM-MGCJ 4GB SODIMM LPDDR4 3733MT/s          | 2         | 0.6%    |
| Samsung RAM K4EBE304EB-EGCG 8192MB Row Of Chips LPDDR3 2133MT/s | 2         | 0.6%    |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s            | 2         | 0.6%    |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s   | 2         | 0.6%    |
| Micron RAM 8ATF2G64HZ-3G2E1 16384MB SODIMM DDR4 3200MT/s        | 2         | 0.6%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s            | 2         | 0.6%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s            | 2         | 0.6%    |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s     | 2         | 0.6%    |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s     | 2         | 0.6%    |
| Micron RAM 53E1G32D4NQ 2048MB Row Of Chips LPDDR4 4267MT/s      | 2         | 0.6%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s           | 2         | 0.6%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.6%    |
| G.Skill RAM F4-2400C16-8GRS 8GB SODIMM DDR4 2400MT/s            | 2         | 0.6%    |
| Crucial RAM CT8G4SFRA32A.C4FE 8GB SODIMM DDR4 3200MT/s          | 2         | 0.6%    |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s      | 2         | 0.6%    |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s       | 2         | 0.6%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 175       | 61.19%  |
| DDR3   | 52        | 18.18%  |
| LPDDR4 | 39        | 13.64%  |
| LPDDR3 | 12        | 4.2%    |
| DDR2   | 7         | 2.45%   |
| SDRAM  | 1         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 229       | 79.51%  |
| Row Of Chips | 56        | 19.44%  |
| DIMM         | 1         | 0.35%   |
| Chip         | 1         | 0.35%   |
| Unknown      | 1         | 0.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 131       | 42.67%  |
| 4096  | 83        | 27.04%  |
| 16384 | 50        | 16.29%  |
| 2048  | 28        | 9.12%   |
| 32768 | 12        | 3.91%   |
| 1024  | 3         | 0.98%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 95        | 31.35%  |
| 2667    | 60        | 19.8%   |
| 1600    | 38        | 12.54%  |
| 2400    | 25        | 8.25%   |
| 4267    | 23        | 7.59%   |
| 2133    | 14        | 4.62%   |
| 4266    | 8         | 2.64%   |
| 1867    | 7         | 2.31%   |
| 1334    | 6         | 1.98%   |
| 3733    | 4         | 1.32%   |
| 1333    | 4         | 1.32%   |
| 1067    | 4         | 1.32%   |
| 800     | 3         | 0.99%   |
| Unknown | 3         | 0.99%   |
| 3266    | 2         | 0.66%   |
| 975     | 2         | 0.66%   |
| 667     | 2         | 0.66%   |
| 4199    | 1         | 0.33%   |
| 3000    | 1         | 0.33%   |
| 1066    | 1         | 0.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 5         | 62.5%   |
| Hewlett-Packard    | 2         | 25%     |
| Seiko Epson        | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| Brother DCP-7030           | 2         | 25%     |
| Seiko Epson XP-4100 Series | 1         | 12.5%   |
| HP LaserJet 1010           | 1         | 12.5%   |
| HP ENVY Photo 7800 series  | 1         | 12.5%   |
| Brother MFC-J6945DW        | 1         | 12.5%   |
| Brother DCP-1600           | 1         | 12.5%   |
| Brother DCP-1510           | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 50%     |
| Canon CanoScan LiDE 110 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 121       | 23.96%  |
| IMC Networks                           | 54        | 10.69%  |
| Microdia                               | 48        | 9.5%    |
| Realtek Semiconductor                  | 45        | 8.91%   |
| Acer                                   | 43        | 8.51%   |
| Quanta                                 | 32        | 6.34%   |
| Cheng Uei Precision Industry (Foxlink) | 26        | 5.15%   |
| Sunplus Innovation Technology          | 20        | 3.96%   |
| Lite-On Technology                     | 14        | 2.77%   |
| Suyin                                  | 13        | 2.57%   |
| Apple                                  | 11        | 2.18%   |
| Syntek                                 | 10        | 1.98%   |
| Silicon Motion                         | 8         | 1.58%   |
| Luxvisions Innotech Limited            | 8         | 1.58%   |
| Lenovo                                 | 8         | 1.58%   |
| Ricoh                                  | 7         | 1.39%   |
| Logitech                               | 7         | 1.39%   |
| Samsung Electronics                    | 4         | 0.79%   |
| Alcor Micro                            | 4         | 0.79%   |
| SunplusIT                              | 3         | 0.59%   |
| Z-Star Microelectronics                | 2         | 0.4%    |
| DigiTech                               | 2         | 0.4%    |
| USB Camera                             | 1         | 0.2%    |
| Sunplus Technology                     | 1         | 0.2%    |
| Ruision                                | 1         | 0.2%    |
| Primax Electronics                     | 1         | 0.2%    |
| OmniVision Technologies                | 1         | 0.2%    |
| Microsoft                              | 1         | 0.2%    |
| Jieli Technology                       | 1         | 0.2%    |
| Importek                               | 1         | 0.2%    |
| GenesysLogic Technology                | 1         | 0.2%    |
| Generalplus Technology                 | 1         | 0.2%    |
| DLEQNA1G4FA2WJ                         | 1         | 0.2%    |
| Creative Technology                    | 1         | 0.2%    |
| ARC International                      | 1         | 0.2%    |
| ALi                                    | 1         | 0.2%    |
| 8SSC20F27114V1SR0CV12SG                | 1         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                  | 33        | 6.5%    |
| Realtek Integrated_Webcam_HD                                   | 20        | 3.94%   |
| Chicony Integrated Camera                                      | 19        | 3.74%   |
| IMC Networks Integrated Camera                                 | 18        | 3.54%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 17        | 3.35%   |
| Chicony HD Webcam                                              | 17        | 3.35%   |
| Acer Integrated Camera                                         | 17        | 3.35%   |
| Quanta HD User Facing                                          | 15        | 2.95%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera               | 9         | 1.77%   |
| Chicony USB 2.0 Camera                                         | 8         | 1.57%   |
| Chicony HP HD Camera                                           | 8         | 1.57%   |
| Sunplus Integrated_Webcam_HD                                   | 7         | 1.38%   |
| Lite-On HP HD Camera                                           | 7         | 1.38%   |
| Syntek Integrated Camera                                       | 5         | 0.98%   |
| Sunplus Depstech webcam MIC                                    | 5         | 0.98%   |
| Realtek Integrated Webcam                                      | 5         | 0.98%   |
| Quanta HP HD Camera                                            | 5         | 0.98%   |
| Acer EasyCamera                                                | 5         | 0.98%   |
| Samsung Galaxy A5 (MTP)                                        | 4         | 0.79%   |
| Luxvisions Innotech Limited HP HD Camera                       | 4         | 0.79%   |
| Lenovo Integrated Webcam                                       | 4         | 0.79%   |
| IMC Networks XiaoMi Webcam                                     | 4         | 0.79%   |
| IMC Networks HD Camera                                         | 4         | 0.79%   |
| Chicony USB2.0 HD UVC WebCam                                   | 4         | 0.79%   |
| Chicony HP Truevision HD                                       | 4         | 0.79%   |
| Chicony HD User Facing                                         | 4         | 0.79%   |
| Chicony EasyCamera                                             | 4         | 0.79%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 4         | 0.79%   |
| Acer Lenovo Integrated Webcam                                  | 4         | 0.79%   |
| Acer BisonCam,NB Pro                                           | 4         | 0.79%   |
| SunplusIT 720p HD Camera                                       | 3         | 0.59%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 3         | 0.59%   |
| Logitech HD Pro Webcam C920                                    | 3         | 0.59%   |
| Lite-On Integrated Camera                                      | 3         | 0.59%   |
| Lenovo Integrated Webcam [R5U877]                              | 3         | 0.59%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 3         | 0.59%   |
| Chicony VGA Webcam                                             | 3         | 0.59%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 3         | 0.59%   |
| Chicony USB 2.0 Webcam Device                                  | 3         | 0.59%   |
| Chicony TOSHIBA Web Camera - HD                                | 3         | 0.59%   |
| Chicony Lenovo EasyCamera                                      | 3         | 0.59%   |
| Chicony HP Wide Vision HD Camera                               | 3         | 0.59%   |
| Chicony HP Truevision HD camera                                | 3         | 0.59%   |
| Chicony FJ Camera                                              | 3         | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 0.59%   |
| Apple FaceTime HD Camera                                       | 3         | 0.59%   |
| Syntek Lenovo EasyCamera                                       | 2         | 0.39%   |
| Syntek EasyCamera                                              | 2         | 0.39%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 2         | 0.39%   |
| Sunplus Integrated_Webcam_FHD                                  | 2         | 0.39%   |
| Sunplus HP TrueVision HD Camera                                | 2         | 0.39%   |
| Sunplus Dell E5570 integrated webcam                           | 2         | 0.39%   |
| Ricoh Integrated Webcam                                        | 2         | 0.39%   |
| Realtek Laptop Camera                                          | 2         | 0.39%   |
| Realtek Integrated_Webcam_FHD                                  | 2         | 0.39%   |
| Realtek Integrated Webcam HD                                   | 2         | 0.39%   |
| Realtek Integrated Camera                                      | 2         | 0.39%   |
| Realtek Front Camera                                           | 2         | 0.39%   |
| Realtek Acer 640 x 480 laptop camera                           | 2         | 0.39%   |
| Quanta VGA WebCam                                              | 2         | 0.39%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 37        | 31.62%  |
| Validity Sensors           | 33        | 28.21%  |
| Synaptics                  | 22        | 18.8%   |
| LighTuning Technology      | 11        | 9.4%    |
| Upek                       | 7         | 5.98%   |
| AuthenTec                  | 5         | 4.27%   |
| Elan Microelectronics      | 2         | 1.71%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 19        | 16.24%  |
| Shenzhen Goodix FingerPrint                                                | 16        | 13.68%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 9.4%    |
| Unknown                                                                    | 10        | 8.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 9         | 7.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 5.98%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 4.27%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 3.42%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 3.42%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.56%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.56%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 2.56%   |
| Synaptics  WBDI                                                            | 2         | 1.71%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.71%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 1.71%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.71%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.71%   |
| AuthenTec AES1600                                                          | 2         | 1.71%   |
| Validity Sensors VFS491                                                    | 1         | 0.85%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.85%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.85%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 0.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.85%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.85%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 0.85%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.85%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.85%   |
| AuthenTec AES2810                                                          | 1         | 0.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 27        | 62.79%  |
| O2 Micro    | 5         | 11.63%  |
| Lenovo      | 5         | 11.63%  |
| Upek        | 4         | 9.3%    |
| Alcor Micro | 2         | 4.65%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                              | 10        | 23.26%  |
| Broadcom BCM5880 Secure Applications Processor             | 9         | 20.93%  |
| Broadcom 58200                                             | 8         | 18.6%   |
| O2 Micro OZ776 CCID Smartcard Reader                       | 5         | 11.63%  |
| Lenovo Integrated Smart Card Reader                        | 5         | 11.63%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 4         | 9.3%    |
| Alcor Micro AU9540 Smartcard Reader                        | 2         | 4.65%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 332       | 60.81%  |
| 1     | 182       | 33.33%  |
| 2     | 29        | 5.31%   |
| 3     | 3         | 0.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 115       | 47.13%  |
| Chipcard                 | 44        | 18.03%  |
| Graphics card            | 39        | 15.98%  |
| Net/wireless             | 22        | 9.02%   |
| Multimedia controller    | 8         | 3.28%   |
| Card reader              | 3         | 1.23%   |
| Camera                   | 3         | 1.23%   |
| Bluetooth                | 3         | 1.23%   |
| Storage                  | 2         | 0.82%   |
| Sound                    | 1         | 0.41%   |
| Net/ethernet             | 1         | 0.41%   |
| Modem                    | 1         | 0.41%   |
| Dvb card                 | 1         | 0.41%   |
| Communication controller | 1         | 0.41%   |


Linux in Poland - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Poland.

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

Total: 5051

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 7390               | [2386e8641f](https://linux-hardware.org/?probe=2386e8641f) | Feb 02, 2024 |
| Dell          | Latitude 7400               | [ad51cec5ea](https://linux-hardware.org/?probe=ad51cec5ea) | Feb 02, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [47431ad7d9](https://linux-hardware.org/?probe=47431ad7d9) | Feb 02, 2024 |
| Valve         | Galileo                     | [aebc4c73ad](https://linux-hardware.org/?probe=aebc4c73ad) | Feb 01, 2024 |
| HP            | ProBook 450 G8              | [f8d060061c](https://linux-hardware.org/?probe=f8d060061c) | Jan 30, 2024 |
| HP            | ProBook 450 G8              | [4ca13b7d13](https://linux-hardware.org/?probe=4ca13b7d13) | Jan 30, 2024 |
| Dell          | Latitude 3190               | [16f86af47d](https://linux-hardware.org/?probe=16f86af47d) | Jan 30, 2024 |
| Lenovo        | ThinkPad T570 20HAS0NU00    | [39f3b9fb56](https://linux-hardware.org/?probe=39f3b9fb56) | Jan 30, 2024 |
| Dell          | Latitude E5420              | [fe49c198a3](https://linux-hardware.org/?probe=fe49c198a3) | Jan 29, 2024 |
| Dell          | Latitude E5420              | [d76191acac](https://linux-hardware.org/?probe=d76191acac) | Jan 29, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [913338a499](https://linux-hardware.org/?probe=913338a499) | Jan 29, 2024 |
| Lenovo        | G510 20238                  | [12cf7dfeeb](https://linux-hardware.org/?probe=12cf7dfeeb) | Jan 29, 2024 |
| Dell          | Latitude 5511               | [40fad497db](https://linux-hardware.org/?probe=40fad497db) | Jan 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f20816d81d](https://linux-hardware.org/?probe=f20816d81d) | Jan 28, 2024 |
| Apple         | MacBookAir6,1               | [d508f78053](https://linux-hardware.org/?probe=d508f78053) | Jan 28, 2024 |
| eMachines     | eME732ZG                    | [50446e8377](https://linux-hardware.org/?probe=50446e8377) | Jan 28, 2024 |
| Acer          | Aspire A715-42G             | [6e3e887615](https://linux-hardware.org/?probe=6e3e887615) | Jan 27, 2024 |
| Lenovo        | B590 20206                  | [31fa6a22ea](https://linux-hardware.org/?probe=31fa6a22ea) | Jan 27, 2024 |
| HP            | ZBook 15 G5                 | [73e974c084](https://linux-hardware.org/?probe=73e974c084) | Jan 27, 2024 |
| Dell          | Latitude 5520               | [acedcebd94](https://linux-hardware.org/?probe=acedcebd94) | Jan 26, 2024 |
| mPTech        | Techbite ZIN 3              | [57234bbbc3](https://linux-hardware.org/?probe=57234bbbc3) | Jan 26, 2024 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [01dd8556d5](https://linux-hardware.org/?probe=01dd8556d5) | Jan 26, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [3ed9ff642f](https://linux-hardware.org/?probe=3ed9ff642f) | Jan 25, 2024 |
| Dell          | Latitude D620               | [d46bb1fc6b](https://linux-hardware.org/?probe=d46bb1fc6b) | Jan 25, 2024 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [d530eec023](https://linux-hardware.org/?probe=d530eec023) | Jan 25, 2024 |
| HP            | Pavilion dv6                | [073fe44f35](https://linux-hardware.org/?probe=073fe44f35) | Jan 24, 2024 |
| Samsung       | 450R4E/450R5E/450R4V/450... | [0f69d36c02](https://linux-hardware.org/?probe=0f69d36c02) | Jan 24, 2024 |
| Toshiba       | Satellite C650              | [2fa418e377](https://linux-hardware.org/?probe=2fa418e377) | Jan 24, 2024 |
| Apple         | MacBookAir6,1               | [b687521689](https://linux-hardware.org/?probe=b687521689) | Jan 24, 2024 |
| Dell          | Inspiron 7559               | [b82f00532c](https://linux-hardware.org/?probe=b82f00532c) | Jan 24, 2024 |
| Toshiba       | Satellite L40               | [0f0ab308a5](https://linux-hardware.org/?probe=0f0ab308a5) | Jan 23, 2024 |
| Lenovo        | ThinkPad P50 20EQS3B30R     | [27804a7892](https://linux-hardware.org/?probe=27804a7892) | Jan 23, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [7039b3ef95](https://linux-hardware.org/?probe=7039b3ef95) | Jan 23, 2024 |
| Google        | Kefka                       | [6cb0b95d02](https://linux-hardware.org/?probe=6cb0b95d02) | Jan 22, 2024 |
| ASUSTek       | X550VC                      | [90ebdf4197](https://linux-hardware.org/?probe=90ebdf4197) | Jan 22, 2024 |
| Acer          | Swift SFX14-51G             | [ac8dbddf38](https://linux-hardware.org/?probe=ac8dbddf38) | Jan 22, 2024 |
| HP            | ProBook 6560b               | [6d2bbcc556](https://linux-hardware.org/?probe=6d2bbcc556) | Jan 21, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [9a1d16aad2](https://linux-hardware.org/?probe=9a1d16aad2) | Jan 21, 2024 |
| Samsung       | X420/X520                   | [9dae8bd2c2](https://linux-hardware.org/?probe=9dae8bd2c2) | Jan 21, 2024 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [73c6b8874b](https://linux-hardware.org/?probe=73c6b8874b) | Jan 21, 2024 |
| HP            | Pavilion dv7                | [da67ecc7a4](https://linux-hardware.org/?probe=da67ecc7a4) | Jan 18, 2024 |
| Dream Mach... | NS5x_NS7xPU                 | [d4604f53fc](https://linux-hardware.org/?probe=d4604f53fc) | Jan 17, 2024 |
| Acer          | Aspire E1-531G              | [2c64046f89](https://linux-hardware.org/?probe=2c64046f89) | Jan 17, 2024 |
| HP            | 250 G5 Notebook PC          | [d8e4449d99](https://linux-hardware.org/?probe=d8e4449d99) | Jan 16, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [dc21da33ed](https://linux-hardware.org/?probe=dc21da33ed) | Jan 16, 2024 |
| Toshiba       | Satellite L40               | [f5e9dbe1c8](https://linux-hardware.org/?probe=f5e9dbe1c8) | Jan 16, 2024 |
| HP            | EliteBook 830 13 inch G1... | [d462837d11](https://linux-hardware.org/?probe=d462837d11) | Jan 15, 2024 |
| Dell          | Latitude E4310              | [a11f178faf](https://linux-hardware.org/?probe=a11f178faf) | Jan 14, 2024 |
| Toshiba       | Satellite C55-A-1H9         | [7fa6a6c318](https://linux-hardware.org/?probe=7fa6a6c318) | Jan 14, 2024 |
| Dell          | Inspiron 5515               | [6523b11a61](https://linux-hardware.org/?probe=6523b11a61) | Jan 14, 2024 |
| Valve         | Jupiter                     | [51d79bc7e2](https://linux-hardware.org/?probe=51d79bc7e2) | Jan 14, 2024 |
| HP            | Compaq 6720s                | [4b6c283ab3](https://linux-hardware.org/?probe=4b6c283ab3) | Jan 13, 2024 |
| Lenovo        | V15-ADA 82C7                | [9fbe7a7217](https://linux-hardware.org/?probe=9fbe7a7217) | Jan 13, 2024 |
| HP            | EliteBook 820 G1            | [132b261039](https://linux-hardware.org/?probe=132b261039) | Jan 12, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [a7a2eedaec](https://linux-hardware.org/?probe=a7a2eedaec) | Jan 12, 2024 |
| Lenovo        | ThinkPad T430 2349FC4       | [655eb2734a](https://linux-hardware.org/?probe=655eb2734a) | Jan 11, 2024 |
| HP            | 530 Notebook PC(GH634AA#... | [a17c4145f4](https://linux-hardware.org/?probe=a17c4145f4) | Jan 11, 2024 |
| Apple         | MacBookPro11,4              | [7b242e0b03](https://linux-hardware.org/?probe=7b242e0b03) | Jan 11, 2024 |
| Apple         | MacBookPro11,4              | [a4cfa8b935](https://linux-hardware.org/?probe=a4cfa8b935) | Jan 11, 2024 |
| Lenovo        | ThinkPad P16v Gen 1 21FC... | [9066b38bfc](https://linux-hardware.org/?probe=9066b38bfc) | Jan 11, 2024 |
| Lenovo        | G580 20150                  | [bdddc03230](https://linux-hardware.org/?probe=bdddc03230) | Jan 11, 2024 |
| Google        | Phaser360                   | [7402fc6e46](https://linux-hardware.org/?probe=7402fc6e46) | Jan 11, 2024 |
| Dell          | Latitude E7440              | [08decb079c](https://linux-hardware.org/?probe=08decb079c) | Jan 11, 2024 |
| Dell          | Latitude E7240              | [5661525290](https://linux-hardware.org/?probe=5661525290) | Jan 11, 2024 |
| HP            | Victus by Gaming Laptop ... | [fb2aecbc70](https://linux-hardware.org/?probe=fb2aecbc70) | Jan 10, 2024 |
| Dell          | Inspiron 7737               | [ae41cf1d2f](https://linux-hardware.org/?probe=ae41cf1d2f) | Jan 10, 2024 |
| Acer          | Aspire A715-74G             | [4d6e4c3464](https://linux-hardware.org/?probe=4d6e4c3464) | Jan 10, 2024 |
| Acer          | TravelMate 8572G            | [4322118152](https://linux-hardware.org/?probe=4322118152) | Jan 10, 2024 |
| Dell          | Latitude 5521               | [8058baf2cb](https://linux-hardware.org/?probe=8058baf2cb) | Jan 10, 2024 |
| MSI           | Stealth GS66 12UGS          | [302723b72f](https://linux-hardware.org/?probe=302723b72f) | Jan 10, 2024 |
| Toshiba       | Satellite C660              | [34eaf45d7f](https://linux-hardware.org/?probe=34eaf45d7f) | Jan 09, 2024 |
| Valve         | Jupiter                     | [62bf989a58](https://linux-hardware.org/?probe=62bf989a58) | Jan 09, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | [62b2915f0f](https://linux-hardware.org/?probe=62b2915f0f) | Jan 09, 2024 |
| Dell          | Latitude 3190               | [afdd5a1dbe](https://linux-hardware.org/?probe=afdd5a1dbe) | Jan 09, 2024 |
| Lenovo        | IdeaPad Y530                | [344509ac97](https://linux-hardware.org/?probe=344509ac97) | Jan 08, 2024 |
| Toshiba       | Satellite A200              | [4b6c5e1edb](https://linux-hardware.org/?probe=4b6c5e1edb) | Jan 08, 2024 |
| Valve         | Jupiter                     | [bddd9671c1](https://linux-hardware.org/?probe=bddd9671c1) | Jan 08, 2024 |
| Lenovo        | ThinkPad L540 20AUA1E600    | [9d0e13031a](https://linux-hardware.org/?probe=9d0e13031a) | Jan 08, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [a9f2ff1fc3](https://linux-hardware.org/?probe=a9f2ff1fc3) | Jan 07, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [dac2172dc5](https://linux-hardware.org/?probe=dac2172dc5) | Jan 07, 2024 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [770f12c749](https://linux-hardware.org/?probe=770f12c749) | Jan 07, 2024 |
| Lenovo        | B50-70 20384                | [87e302df7b](https://linux-hardware.org/?probe=87e302df7b) | Jan 07, 2024 |
| Lenovo        | ThinkPad X220 Tablet 429... | [db24e06c04](https://linux-hardware.org/?probe=db24e06c04) | Jan 07, 2024 |
| Dell          | G3 3579                     | [5c48d53216](https://linux-hardware.org/?probe=5c48d53216) | Jan 07, 2024 |
| Dell          | G3 3579                     | [6ee6a6d56a](https://linux-hardware.org/?probe=6ee6a6d56a) | Jan 07, 2024 |
| Toshiba       | Satellite C55-A-1H9         | [ab8c5bc566](https://linux-hardware.org/?probe=ab8c5bc566) | Jan 07, 2024 |
| Lenovo        | ThinkPad T430 2349FC4       | [ea07a49b87](https://linux-hardware.org/?probe=ea07a49b87) | Jan 07, 2024 |
| HP            | ZBook 17 G6                 | [89cde2f9d4](https://linux-hardware.org/?probe=89cde2f9d4) | Jan 06, 2024 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [0f5ae64d19](https://linux-hardware.org/?probe=0f5ae64d19) | Jan 06, 2024 |
| Dell          | Latitude 7420               | [7b6c854eaf](https://linux-hardware.org/?probe=7b6c854eaf) | Jan 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3be696b6a2](https://linux-hardware.org/?probe=3be696b6a2) | Jan 06, 2024 |
| HP            | Compaq 6730s                | [1ad2b54c9d](https://linux-hardware.org/?probe=1ad2b54c9d) | Jan 05, 2024 |
| Lenovo        | V15 G3 IAP CTO 83C4         | [050c0c3ac6](https://linux-hardware.org/?probe=050c0c3ac6) | Jan 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [c085db23b6](https://linux-hardware.org/?probe=c085db23b6) | Jan 04, 2024 |
| HP            | Stream Notebook PC 13       | [35597f6ed8](https://linux-hardware.org/?probe=35597f6ed8) | Jan 03, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e98a083e68](https://linux-hardware.org/?probe=e98a083e68) | Jan 03, 2024 |
| Dell          | Inspiron 5502               | [3486d53d60](https://linux-hardware.org/?probe=3486d53d60) | Jan 03, 2024 |
| AMI           | Cherry Trail CR             | [35f5071102](https://linux-hardware.org/?probe=35f5071102) | Jan 03, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [063cb7f7f8](https://linux-hardware.org/?probe=063cb7f7f8) | Jan 02, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [01650ef12d](https://linux-hardware.org/?probe=01650ef12d) | Jan 02, 2024 |
| Dell          | Inspiron 13-5368            | [811a112c63](https://linux-hardware.org/?probe=811a112c63) | Jan 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [de7126bf06](https://linux-hardware.org/?probe=de7126bf06) | Jan 01, 2024 |
| Toshiba       | Satellite A660              | [34dd6e3ec3](https://linux-hardware.org/?probe=34dd6e3ec3) | Jan 01, 2024 |
| Toshiba       | Satellite A660              | [4b00ffd071](https://linux-hardware.org/?probe=4b00ffd071) | Jan 01, 2024 |
| Dell          | Latitude 7420               | [a32d08979b](https://linux-hardware.org/?probe=a32d08979b) | Dec 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [cd2840bccc](https://linux-hardware.org/?probe=cd2840bccc) | Dec 31, 2023 |
| HP            | Laptop 14s-dq1xxx           | [f5f0fa82e5](https://linux-hardware.org/?probe=f5f0fa82e5) | Dec 31, 2023 |
| Dell          | Latitude 7420               | [9bee55a186](https://linux-hardware.org/?probe=9bee55a186) | Dec 31, 2023 |
| Apple         | MacBookPro6,2               | [1a25482d3d](https://linux-hardware.org/?probe=1a25482d3d) | Dec 31, 2023 |
| Lenovo        | IdeaPad 320-14IAP 80XQ      | [1fedc1bf30](https://linux-hardware.org/?probe=1fedc1bf30) | Dec 31, 2023 |
| Dell          | Latitude D630               | [bbae93d767](https://linux-hardware.org/?probe=bbae93d767) | Dec 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [49a4d9cad0](https://linux-hardware.org/?probe=49a4d9cad0) | Dec 31, 2023 |
| HP            | 250 G6 Notebook PC          | [1a5d669774](https://linux-hardware.org/?probe=1a5d669774) | Dec 30, 2023 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [4f95b9d510](https://linux-hardware.org/?probe=4f95b9d510) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f391231013](https://linux-hardware.org/?probe=f391231013) | Dec 30, 2023 |
| Monster       | ABRA A5 V13.4               | [8cb3a2ee0a](https://linux-hardware.org/?probe=8cb3a2ee0a) | Dec 30, 2023 |
| Samsung       | R530/R730/R540              | [c914756956](https://linux-hardware.org/?probe=c914756956) | Dec 30, 2023 |
| Lenovo        | ThinkPad T440p 20AWS4YE0... | [74d75dc18d](https://linux-hardware.org/?probe=74d75dc18d) | Dec 30, 2023 |
| Lenovo        | ThinkPad T440p 20AWS4UD0... | [0305a2f3cf](https://linux-hardware.org/?probe=0305a2f3cf) | Dec 30, 2023 |
| Dell          | Latitude E7440              | [d9fb6a9ead](https://linux-hardware.org/?probe=d9fb6a9ead) | Dec 30, 2023 |
| HP            | Notebook                    | [c5f68d3103](https://linux-hardware.org/?probe=c5f68d3103) | Dec 30, 2023 |
| Acer          | Aspire F5-573G              | [4744ad0a98](https://linux-hardware.org/?probe=4744ad0a98) | Dec 30, 2023 |
| Lenovo        | ThinkPad T430 2349FC4       | [689d3295aa](https://linux-hardware.org/?probe=689d3295aa) | Dec 30, 2023 |
| Monster       | ABRA A5 V13.4               | [274f6e86fc](https://linux-hardware.org/?probe=274f6e86fc) | Dec 29, 2023 |
| Lenovo        | G50-80 80E5                 | [0e612ffdf7](https://linux-hardware.org/?probe=0e612ffdf7) | Dec 29, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [99561c9ed3](https://linux-hardware.org/?probe=99561c9ed3) | Dec 29, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [13e6674db0](https://linux-hardware.org/?probe=13e6674db0) | Dec 29, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [09f37233e4](https://linux-hardware.org/?probe=09f37233e4) | Dec 29, 2023 |
| MSI           | GS70 2OD                    | [13dab050a1](https://linux-hardware.org/?probe=13dab050a1) | Dec 28, 2023 |
| MSI           | GS70 2OD                    | [7092678d3b](https://linux-hardware.org/?probe=7092678d3b) | Dec 28, 2023 |
| HP            | EliteBook 830 G5            | [c9ac7b8022](https://linux-hardware.org/?probe=c9ac7b8022) | Dec 28, 2023 |
| TrekStor      | Notebook Slim S130          | [9fbe38b102](https://linux-hardware.org/?probe=9fbe38b102) | Dec 28, 2023 |
| Dell          | Latitude 5400               | [4c2ddb74c4](https://linux-hardware.org/?probe=4c2ddb74c4) | Dec 27, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [a8871fb21b](https://linux-hardware.org/?probe=a8871fb21b) | Dec 27, 2023 |
| Hampoo        | L1W6_I1101_C Reserved       | [ad4de7dcab](https://linux-hardware.org/?probe=ad4de7dcab) | Dec 26, 2023 |
| Dell          | Latitude E7450              | [84dc5f09e7](https://linux-hardware.org/?probe=84dc5f09e7) | Dec 26, 2023 |
| Dell          | Latitude 5400               | [35adbae547](https://linux-hardware.org/?probe=35adbae547) | Dec 26, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [8b68f422dd](https://linux-hardware.org/?probe=8b68f422dd) | Dec 26, 2023 |
| Kiano         | Elegance 14.2               | [9c32017999](https://linux-hardware.org/?probe=9c32017999) | Dec 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f58bf5fe4c](https://linux-hardware.org/?probe=f58bf5fe4c) | Dec 26, 2023 |
| Dell          | Latitude 3190               | [e0da711bcb](https://linux-hardware.org/?probe=e0da711bcb) | Dec 26, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [ed9f6e6354](https://linux-hardware.org/?probe=ed9f6e6354) | Dec 26, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [b35c9836e7](https://linux-hardware.org/?probe=b35c9836e7) | Dec 26, 2023 |
| Lenovo        | ThinkPad E470 20H1004UIG    | [69efda7672](https://linux-hardware.org/?probe=69efda7672) | Dec 26, 2023 |
| Lenovo        | ThinkPad T500 20828WG       | [a3edf5e69b](https://linux-hardware.org/?probe=a3edf5e69b) | Dec 26, 2023 |
| Acer          | Nitro AN16-41               | [ae0d837def](https://linux-hardware.org/?probe=ae0d837def) | Dec 26, 2023 |
| Acer          | Aspire A515-56              | [a35ed82108](https://linux-hardware.org/?probe=a35ed82108) | Dec 26, 2023 |
| Acer          | Aspire A515-56              | [d9ec9cb0f7](https://linux-hardware.org/?probe=d9ec9cb0f7) | Dec 26, 2023 |
| Dell          | Precision M4500             | [a98dcc4861](https://linux-hardware.org/?probe=a98dcc4861) | Dec 26, 2023 |
| Dell          | Latitude 6430U              | [4c20fee408](https://linux-hardware.org/?probe=4c20fee408) | Dec 25, 2023 |
| Acer          | Extensa 215-55              | [54ca5c9e74](https://linux-hardware.org/?probe=54ca5c9e74) | Dec 25, 2023 |
| Dell          | Latitude 5400               | [7ddd773af2](https://linux-hardware.org/?probe=7ddd773af2) | Dec 25, 2023 |
| Samsung       | NC210/NC110                 | [cba7a81460](https://linux-hardware.org/?probe=cba7a81460) | Dec 25, 2023 |
| Samsung       | NC210/NC110                 | [5820853b65](https://linux-hardware.org/?probe=5820853b65) | Dec 24, 2023 |
| Valve         | Jupiter                     | [4c98f6b6f3](https://linux-hardware.org/?probe=4c98f6b6f3) | Dec 24, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0600... | [07efd36bbe](https://linux-hardware.org/?probe=07efd36bbe) | Dec 24, 2023 |
| HP            | EliteBook 2530p             | [996611fcab](https://linux-hardware.org/?probe=996611fcab) | Dec 23, 2023 |
| Dell          | Latitude E6530              | [2a62f5f318](https://linux-hardware.org/?probe=2a62f5f318) | Dec 23, 2023 |
| Dell          | Latitude E6530              | [2d9ff2bdb9](https://linux-hardware.org/?probe=2d9ff2bdb9) | Dec 23, 2023 |
| Lenovo        | G50-30 80G0                 | [45b0f5ae9a](https://linux-hardware.org/?probe=45b0f5ae9a) | Dec 23, 2023 |
| HP            | EliteBook 745 G6            | [9bf64ae4b7](https://linux-hardware.org/?probe=9bf64ae4b7) | Dec 23, 2023 |
| ASUSTek       | X555LJ                      | [8f1a82681b](https://linux-hardware.org/?probe=8f1a82681b) | Dec 22, 2023 |
| ASUSTek       | X555LJ                      | [44b0b8bd05](https://linux-hardware.org/?probe=44b0b8bd05) | Dec 22, 2023 |
| Dell          | Latitude 5440               | [d7462b97ac](https://linux-hardware.org/?probe=d7462b97ac) | Dec 22, 2023 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | [c6cefd749d](https://linux-hardware.org/?probe=c6cefd749d) | Dec 22, 2023 |
| Dell          | Latitude E6400              | [6e6d4fec11](https://linux-hardware.org/?probe=6e6d4fec11) | Dec 21, 2023 |
| Dell          | Precision M6600             | [5e387ee3ac](https://linux-hardware.org/?probe=5e387ee3ac) | Dec 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [ec0a846182](https://linux-hardware.org/?probe=ec0a846182) | Dec 21, 2023 |
| Lenovo        | ThinkPad SL 2746E9G         | [594a56a070](https://linux-hardware.org/?probe=594a56a070) | Dec 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [5632b47c38](https://linux-hardware.org/?probe=5632b47c38) | Dec 21, 2023 |
| Dell          | Latitude E6320              | [a1e4b48d85](https://linux-hardware.org/?probe=a1e4b48d85) | Dec 20, 2023 |
| Fujitsu       | LIFEBOOK U745               | [a2f7b09b87](https://linux-hardware.org/?probe=a2f7b09b87) | Dec 20, 2023 |
| STONE COMP... | NOTCHA-286                  | [c931f0f65a](https://linux-hardware.org/?probe=c931f0f65a) | Dec 20, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [5615091c1d](https://linux-hardware.org/?probe=5615091c1d) | Dec 20, 2023 |
| Unknown       | Unknown                     | [6f1ca9e563](https://linux-hardware.org/?probe=6f1ca9e563) | Dec 19, 2023 |
| Unknown       | Unknown                     | [13072c9ecc](https://linux-hardware.org/?probe=13072c9ecc) | Dec 19, 2023 |
| Dell          | Latitude 3190               | [a7e488632e](https://linux-hardware.org/?probe=a7e488632e) | Dec 19, 2023 |
| Google        | Phaser360                   | [c739678794](https://linux-hardware.org/?probe=c739678794) | Dec 18, 2023 |
| Dell          | Latitude E6440              | [8d1b130773](https://linux-hardware.org/?probe=8d1b130773) | Dec 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [1a1a04845b](https://linux-hardware.org/?probe=1a1a04845b) | Dec 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [fcc1139818](https://linux-hardware.org/?probe=fcc1139818) | Dec 18, 2023 |
| Fujitsu Si... | LIFEBOOK S6410              | [24edc4b12c](https://linux-hardware.org/?probe=24edc4b12c) | Dec 17, 2023 |
| ASUSTek       | 1215N                       | [9d204d6a41](https://linux-hardware.org/?probe=9d204d6a41) | Dec 17, 2023 |
| ASUSTek       | K84L                        | [3e0ea1ca0a](https://linux-hardware.org/?probe=3e0ea1ca0a) | Dec 17, 2023 |
| Google        | Phaser360                   | [784ed40440](https://linux-hardware.org/?probe=784ed40440) | Dec 16, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [f7ffef008a](https://linux-hardware.org/?probe=f7ffef008a) | Dec 16, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [fc9b36317a](https://linux-hardware.org/?probe=fc9b36317a) | Dec 16, 2023 |
| Dell          | Inspiron 15-3567            | [3907c9bfa3](https://linux-hardware.org/?probe=3907c9bfa3) | Dec 16, 2023 |
| Lenovo        | B590 20206                  | [b6afc3e929](https://linux-hardware.org/?probe=b6afc3e929) | Dec 16, 2023 |
| Lenovo        | G570 20079                  | [7928703207](https://linux-hardware.org/?probe=7928703207) | Dec 16, 2023 |
| Dell          | Latitude E5410              | [ee4251c01c](https://linux-hardware.org/?probe=ee4251c01c) | Dec 15, 2023 |
| Lenovo        | Yoga Slim 6 14IAP8 82WU     | [c2186c6471](https://linux-hardware.org/?probe=c2186c6471) | Dec 14, 2023 |
| MSI           | GT70 2OC/2OD                | [22910f80b0](https://linux-hardware.org/?probe=22910f80b0) | Dec 14, 2023 |
| Dell          | Latitude E6440              | [cf0bb02399](https://linux-hardware.org/?probe=cf0bb02399) | Dec 13, 2023 |
| HP            | Laptop 15s-eq0xxx           | [56e614b2fe](https://linux-hardware.org/?probe=56e614b2fe) | Dec 12, 2023 |
| Dell          | Latitude 3190               | [faf8105e3c](https://linux-hardware.org/?probe=faf8105e3c) | Dec 12, 2023 |
| HP            | Laptop                      | [8bdb6d048e](https://linux-hardware.org/?probe=8bdb6d048e) | Dec 11, 2023 |
| Dell          | Precision 7520              | [d0f203dcb1](https://linux-hardware.org/?probe=d0f203dcb1) | Dec 11, 2023 |
| Dell          | Precision 7520              | [2e02455101](https://linux-hardware.org/?probe=2e02455101) | Dec 11, 2023 |
| HP            | Pavilion Sleekbook 15       | [baec95bb2f](https://linux-hardware.org/?probe=baec95bb2f) | Dec 11, 2023 |
| Apple         | MacBookPro15,1              | [9d882fc801](https://linux-hardware.org/?probe=9d882fc801) | Dec 11, 2023 |
| HP            | Laptop                      | [b5d2cf7074](https://linux-hardware.org/?probe=b5d2cf7074) | Dec 10, 2023 |
| Lenovo        | ThinkPad T410 2522V3S       | [7a6c259421](https://linux-hardware.org/?probe=7a6c259421) | Dec 10, 2023 |
| Acer          | Nitro AN515-54              | [a29797fb65](https://linux-hardware.org/?probe=a29797fb65) | Dec 10, 2023 |
| Toshiba       | Satellite A660              | [441f997be2](https://linux-hardware.org/?probe=441f997be2) | Dec 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [63b05d421b](https://linux-hardware.org/?probe=63b05d421b) | Dec 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1ecb7258d5](https://linux-hardware.org/?probe=1ecb7258d5) | Dec 10, 2023 |
| Dell          | Latitude 7440               | [2aef8e5157](https://linux-hardware.org/?probe=2aef8e5157) | Dec 09, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [87be870a89](https://linux-hardware.org/?probe=87be870a89) | Dec 09, 2023 |
| Lenovo        | V14-IIL 82C4                | [459870519f](https://linux-hardware.org/?probe=459870519f) | Dec 09, 2023 |
| Gigabyte      | AORUS 15 9KF                | [d6386ee775](https://linux-hardware.org/?probe=d6386ee775) | Dec 09, 2023 |
| Dell          | Latitude 7490               | [13759c617a](https://linux-hardware.org/?probe=13759c617a) | Dec 08, 2023 |
| Dell          | Latitude E5550              | [740c338fbe](https://linux-hardware.org/?probe=740c338fbe) | Dec 08, 2023 |
| Dell          | Latitude 5511               | [9f006edcd8](https://linux-hardware.org/?probe=9f006edcd8) | Dec 08, 2023 |
| MSI           | Modern 15 B12M              | [da95a095fa](https://linux-hardware.org/?probe=da95a095fa) | Dec 08, 2023 |
| Dell          | Latitude E6430              | [dee39185ec](https://linux-hardware.org/?probe=dee39185ec) | Dec 08, 2023 |
| Dell          | Latitude E5550              | [52866a9d1a](https://linux-hardware.org/?probe=52866a9d1a) | Dec 08, 2023 |
| Lenovo        | ThinkPad X250 20CLS8C000    | [bff5eac6db](https://linux-hardware.org/?probe=bff5eac6db) | Dec 08, 2023 |
| HP            | EliteBook 840 14 inch G1... | [b2fcb75892](https://linux-hardware.org/?probe=b2fcb75892) | Dec 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [87aa35c45c](https://linux-hardware.org/?probe=87aa35c45c) | Dec 07, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [256fbd42a6](https://linux-hardware.org/?probe=256fbd42a6) | Dec 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [3fce748548](https://linux-hardware.org/?probe=3fce748548) | Dec 06, 2023 |
| Packard Be... | EasyNote TSX66HR            | [8ca6149044](https://linux-hardware.org/?probe=8ca6149044) | Dec 06, 2023 |
| Acer          | Aspire A315-23              | [7d11b1aed9](https://linux-hardware.org/?probe=7d11b1aed9) | Dec 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [fae6162d7b](https://linux-hardware.org/?probe=fae6162d7b) | Dec 06, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [e6657bb173](https://linux-hardware.org/?probe=e6657bb173) | Dec 06, 2023 |
| Valve         | Galileo                     | [4704035dff](https://linux-hardware.org/?probe=4704035dff) | Dec 06, 2023 |
| HUAWEI        | RLEF-XX                     | [519c5e78fc](https://linux-hardware.org/?probe=519c5e78fc) | Dec 06, 2023 |
| ASUSTek       | N76VZ                       | [3d8844bc98](https://linux-hardware.org/?probe=3d8844bc98) | Dec 05, 2023 |
| Lenovo        | ThinkPad E15 20RD003KMH     | [d54efc5833](https://linux-hardware.org/?probe=d54efc5833) | Dec 05, 2023 |
| ASUSTek       | K53U                        | [b76cef4836](https://linux-hardware.org/?probe=b76cef4836) | Dec 05, 2023 |
| Toshiba       | Satellite L750              | [667c6d4e98](https://linux-hardware.org/?probe=667c6d4e98) | Dec 05, 2023 |
| Valve         | Jupiter                     | [63e8b02453](https://linux-hardware.org/?probe=63e8b02453) | Dec 05, 2023 |
| ASUSTek       | X555LJ                      | [bd98f1df4c](https://linux-hardware.org/?probe=bd98f1df4c) | Dec 04, 2023 |
| HP            | ProBook 650 G1              | [b4b71ada44](https://linux-hardware.org/?probe=b4b71ada44) | Dec 04, 2023 |
| Acer          | Extensa 215-55              | [87616f0d71](https://linux-hardware.org/?probe=87616f0d71) | Dec 04, 2023 |
| Dell          | Inspiron MM061              | [0f629c5ee8](https://linux-hardware.org/?probe=0f629c5ee8) | Dec 04, 2023 |
| HUAWEI        | BOD-WXX9                    | [961b00cfbe](https://linux-hardware.org/?probe=961b00cfbe) | Dec 04, 2023 |
| Samsung       | R530/R730/R540              | [7c16c8b9ac](https://linux-hardware.org/?probe=7c16c8b9ac) | Dec 03, 2023 |
| ASUSTek       | 1215N                       | [49eeb946c5](https://linux-hardware.org/?probe=49eeb946c5) | Dec 03, 2023 |
| ASUSTek       | K53SJ                       | [50979ecbd2](https://linux-hardware.org/?probe=50979ecbd2) | Dec 03, 2023 |
| Lenovo        | V14-IIL 82C4                | [848e0dbd37](https://linux-hardware.org/?probe=848e0dbd37) | Dec 03, 2023 |
| Dell          | Latitude E6410              | [bae67b7a50](https://linux-hardware.org/?probe=bae67b7a50) | Dec 03, 2023 |
| Dell          | System Inspiron N7110       | [f0df20f63f](https://linux-hardware.org/?probe=f0df20f63f) | Dec 03, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [9abcd3c636](https://linux-hardware.org/?probe=9abcd3c636) | Dec 03, 2023 |
| Medion        | E6214                       | [f5e38ac376](https://linux-hardware.org/?probe=f5e38ac376) | Dec 03, 2023 |
| HP            | Laptop 15s-eq0xxx           | [bc4c5638a3](https://linux-hardware.org/?probe=bc4c5638a3) | Dec 03, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a18c178195](https://linux-hardware.org/?probe=a18c178195) | Dec 02, 2023 |
| ASUSTek       | F3E                         | [26a960dd12](https://linux-hardware.org/?probe=26a960dd12) | Dec 02, 2023 |
| Dell          | Precision 5520              | [aa1a1feefc](https://linux-hardware.org/?probe=aa1a1feefc) | Dec 02, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [983698f613](https://linux-hardware.org/?probe=983698f613) | Dec 02, 2023 |
| Acer          | Aspire E5-575G              | [561cad738d](https://linux-hardware.org/?probe=561cad738d) | Dec 02, 2023 |
| HP            | EliteBook 8560p             | [186eb0ce63](https://linux-hardware.org/?probe=186eb0ce63) | Dec 02, 2023 |
| HP            | EliteBook 8560p             | [6f6f496558](https://linux-hardware.org/?probe=6f6f496558) | Dec 01, 2023 |
| Lenovo        | G585                        | [a62a35b461](https://linux-hardware.org/?probe=a62a35b461) | Dec 01, 2023 |
| Dell          | Latitude 7440               | [b4179d70c3](https://linux-hardware.org/?probe=b4179d70c3) | Dec 01, 2023 |
| Google        | Fleex                       | [4baac33893](https://linux-hardware.org/?probe=4baac33893) | Dec 01, 2023 |
| Acer          | Aspire A715-74G             | [52a7a60343](https://linux-hardware.org/?probe=52a7a60343) | Dec 01, 2023 |
| Dell          | Inspiron 13-5368            | [ab8935b499](https://linux-hardware.org/?probe=ab8935b499) | Dec 01, 2023 |
| Acer          | Aspire 5750G                | [327582fb65](https://linux-hardware.org/?probe=327582fb65) | Dec 01, 2023 |
| Apple         | MacBook3,1                  | [d536392d03](https://linux-hardware.org/?probe=d536392d03) | Nov 30, 2023 |
| Apple         | MacBook3,1                  | [bfe263dfe0](https://linux-hardware.org/?probe=bfe263dfe0) | Nov 30, 2023 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | [c7a78a1510](https://linux-hardware.org/?probe=c7a78a1510) | Nov 30, 2023 |
| Toshiba       | Satellite C660              | [03de11e5b3](https://linux-hardware.org/?probe=03de11e5b3) | Nov 30, 2023 |
| Dell          | G15 5515                    | [25c732d6aa](https://linux-hardware.org/?probe=25c732d6aa) | Nov 30, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [d416d62cf1](https://linux-hardware.org/?probe=d416d62cf1) | Nov 29, 2023 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | [d0eb22aa03](https://linux-hardware.org/?probe=d0eb22aa03) | Nov 29, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2d1452d207](https://linux-hardware.org/?probe=2d1452d207) | Nov 29, 2023 |
| Fujitsu       | LIFEBOOK E5512              | [9df65d1a3d](https://linux-hardware.org/?probe=9df65d1a3d) | Nov 29, 2023 |
| Acer          | Aspire E5-575G              | [c5dd65037d](https://linux-hardware.org/?probe=c5dd65037d) | Nov 29, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [2a9b640b54](https://linux-hardware.org/?probe=2a9b640b54) | Nov 28, 2023 |
| Dell          | Latitude E5430 non-vPro     | [34f3153910](https://linux-hardware.org/?probe=34f3153910) | Nov 28, 2023 |
| HP            | Laptop 15-db1xxx            | [52a0c464fe](https://linux-hardware.org/?probe=52a0c464fe) | Nov 28, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [b8337b50d8](https://linux-hardware.org/?probe=b8337b50d8) | Nov 28, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [0a4f97781c](https://linux-hardware.org/?probe=0a4f97781c) | Nov 27, 2023 |
| Lenovo        | ThinkPad T520 4243PH3       | [63ba3b10d4](https://linux-hardware.org/?probe=63ba3b10d4) | Nov 27, 2023 |
| Clevo         | M720R                       | [cf202bc2be](https://linux-hardware.org/?probe=cf202bc2be) | Nov 27, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [d36366cac6](https://linux-hardware.org/?probe=d36366cac6) | Nov 27, 2023 |
| Acer          | Nitro AN515-54              | [e4cbe05d6d](https://linux-hardware.org/?probe=e4cbe05d6d) | Nov 27, 2023 |
| Dell          | G15 5515                    | [b33a8c3a2e](https://linux-hardware.org/?probe=b33a8c3a2e) | Nov 27, 2023 |
| HP            | ZBook 17 G2                 | [da3ac19523](https://linux-hardware.org/?probe=da3ac19523) | Nov 26, 2023 |
| Dell          | Latitude D630               | [51af6a8f00](https://linux-hardware.org/?probe=51af6a8f00) | Nov 26, 2023 |
| Valve         | Jupiter                     | [95bd4c2832](https://linux-hardware.org/?probe=95bd4c2832) | Nov 26, 2023 |
| Fujitsu       | LIFEBOOK E4511              | [a849237ab7](https://linux-hardware.org/?probe=a849237ab7) | Nov 26, 2023 |
| Chuwi         | GemiBook Plus               | [6316398e5b](https://linux-hardware.org/?probe=6316398e5b) | Nov 26, 2023 |
| HP            | ProBook 5330m               | [74e3bacd14](https://linux-hardware.org/?probe=74e3bacd14) | Nov 25, 2023 |
| Samsung       | RF510/RF410/RF710           | [a642075264](https://linux-hardware.org/?probe=a642075264) | Nov 25, 2023 |
| HP            | EliteBook 735 G6            | [a0480513dd](https://linux-hardware.org/?probe=a0480513dd) | Nov 25, 2023 |
| HP            | EliteBook 2570p             | [e01ac99a92](https://linux-hardware.org/?probe=e01ac99a92) | Nov 25, 2023 |
| Lenovo        | V14-IIL 82C4                | [eb4379efae](https://linux-hardware.org/?probe=eb4379efae) | Nov 24, 2023 |
| Dell          | Inspiron N5040              | [3b51468cdf](https://linux-hardware.org/?probe=3b51468cdf) | Nov 24, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [2b2ac91a50](https://linux-hardware.org/?probe=2b2ac91a50) | Nov 24, 2023 |
| Packard Be... | EasyNote LJ65               | [50a53cf2b0](https://linux-hardware.org/?probe=50a53cf2b0) | Nov 24, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [2852a62f61](https://linux-hardware.org/?probe=2852a62f61) | Nov 24, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [4b725b7022](https://linux-hardware.org/?probe=4b725b7022) | Nov 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [2c505c0b1e](https://linux-hardware.org/?probe=2c505c0b1e) | Nov 24, 2023 |
| MSI           | Stealth GS66 12UGS          | [080042a410](https://linux-hardware.org/?probe=080042a410) | Nov 23, 2023 |
| MSI           | Stealth GS66 12UGS          | [f82ecf4011](https://linux-hardware.org/?probe=f82ecf4011) | Nov 23, 2023 |
| Lenovo        | B50-10 80QR                 | [ac0bed612a](https://linux-hardware.org/?probe=ac0bed612a) | Nov 22, 2023 |
| Valve         | Jupiter                     | [b73a5b800d](https://linux-hardware.org/?probe=b73a5b800d) | Nov 22, 2023 |
| mPTech        | ARC 11.6 128GB HD           | [56319a6e9d](https://linux-hardware.org/?probe=56319a6e9d) | Nov 21, 2023 |
| Samsung       | 300V3A/300V4A/300V5A        | [5a2df7d067](https://linux-hardware.org/?probe=5a2df7d067) | Nov 21, 2023 |
| Dell          | Latitude 3190               | [3c5b8541c7](https://linux-hardware.org/?probe=3c5b8541c7) | Nov 21, 2023 |
| Dell          | Latitude E6430              | [442654cab6](https://linux-hardware.org/?probe=442654cab6) | Nov 21, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [aeb55b832b](https://linux-hardware.org/?probe=aeb55b832b) | Nov 21, 2023 |
| Acer          | Aspire A315-56              | [b2b85808ca](https://linux-hardware.org/?probe=b2b85808ca) | Nov 20, 2023 |
| HP            | Pavilion dv7                | [b11ea54568](https://linux-hardware.org/?probe=b11ea54568) | Nov 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [a090e73dbf](https://linux-hardware.org/?probe=a090e73dbf) | Nov 20, 2023 |
| Valve         | Jupiter                     | [08b0fccf59](https://linux-hardware.org/?probe=08b0fccf59) | Nov 20, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [e89473830f](https://linux-hardware.org/?probe=e89473830f) | Nov 19, 2023 |
| Dell          | Latitude E6330              | [3c6e547f2a](https://linux-hardware.org/?probe=3c6e547f2a) | Nov 19, 2023 |
| Lenovo        | ThinkPad X60 1707Y91        | [ac0e28ee75](https://linux-hardware.org/?probe=ac0e28ee75) | Nov 19, 2023 |
| Dell          | Latitude E6330              | [078f4227bd](https://linux-hardware.org/?probe=078f4227bd) | Nov 19, 2023 |
| Toshiba       | Satellite L300D             | [87222a31f3](https://linux-hardware.org/?probe=87222a31f3) | Nov 18, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [088efe59ae](https://linux-hardware.org/?probe=088efe59ae) | Nov 18, 2023 |
| Dell          | Latitude D630               | [54e404f085](https://linux-hardware.org/?probe=54e404f085) | Nov 18, 2023 |
| Dell          | Latitude E6400              | [737ee5a8d3](https://linux-hardware.org/?probe=737ee5a8d3) | Nov 18, 2023 |
| Dell          | Latitude 5490               | [b3da1a92d0](https://linux-hardware.org/?probe=b3da1a92d0) | Nov 17, 2023 |
| HP            | EliteBook 850 G6            | [fa0b8c4a6a](https://linux-hardware.org/?probe=fa0b8c4a6a) | Nov 17, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [da6ffb4c35](https://linux-hardware.org/?probe=da6ffb4c35) | Nov 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [6518d0d83e](https://linux-hardware.org/?probe=6518d0d83e) | Nov 17, 2023 |
| Dell          | Inspiron 7566               | [5709fca952](https://linux-hardware.org/?probe=5709fca952) | Nov 17, 2023 |
| Dell          | Latitude E5430 non-vPro     | [6ea69f0699](https://linux-hardware.org/?probe=6ea69f0699) | Nov 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [df8a98ef2c](https://linux-hardware.org/?probe=df8a98ef2c) | Nov 14, 2023 |
| Dell          | System Vostro 3750          | [513485cc8f](https://linux-hardware.org/?probe=513485cc8f) | Nov 14, 2023 |
| MSI           | Modern 14 B11MO             | [2095892205](https://linux-hardware.org/?probe=2095892205) | Nov 14, 2023 |
| ASUSTek       | X550JK                      | [200a783f1a](https://linux-hardware.org/?probe=200a783f1a) | Nov 14, 2023 |
| Dell          | System Vostro 3750          | [3c336ad6e1](https://linux-hardware.org/?probe=3c336ad6e1) | Nov 14, 2023 |
| HP            | ZBook 17 G6                 | [b7d9898316](https://linux-hardware.org/?probe=b7d9898316) | Nov 13, 2023 |
| HUAWEI        | BOD-WXX9                    | [113193bb57](https://linux-hardware.org/?probe=113193bb57) | Nov 13, 2023 |
| HP            | Laptop 14-ck0xxx            | [73a53ca5a4](https://linux-hardware.org/?probe=73a53ca5a4) | Nov 13, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [72639a4231](https://linux-hardware.org/?probe=72639a4231) | Nov 13, 2023 |
| Toshiba       | Satellite L40               | [0d2accfed1](https://linux-hardware.org/?probe=0d2accfed1) | Nov 13, 2023 |
| Timi          | A35S                        | [f225083df7](https://linux-hardware.org/?probe=f225083df7) | Nov 12, 2023 |
| Dell          | Latitude E7440              | [407afcc9d2](https://linux-hardware.org/?probe=407afcc9d2) | Nov 12, 2023 |
| HP            | ProBook 450 G3              | [a749127ad5](https://linux-hardware.org/?probe=a749127ad5) | Nov 11, 2023 |
| HP            | ProBook 450 G3              | [ed70ccc9b1](https://linux-hardware.org/?probe=ed70ccc9b1) | Nov 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5fcb6b8815](https://linux-hardware.org/?probe=5fcb6b8815) | Nov 11, 2023 |
| ASUSTek       | X541NA                      | [951f01b614](https://linux-hardware.org/?probe=951f01b614) | Nov 11, 2023 |
| MSI           | Alpha 17 C7VG               | [99fa1e8cbd](https://linux-hardware.org/?probe=99fa1e8cbd) | Nov 11, 2023 |
| HP            | ZBook 17 G6                 | [c9f63fc134](https://linux-hardware.org/?probe=c9f63fc134) | Nov 11, 2023 |
| HUAWEI        | BOD-WXX9                    | [4e81c16b62](https://linux-hardware.org/?probe=4e81c16b62) | Nov 10, 2023 |
| Dell          | Latitude D630               | [8af88f25f0](https://linux-hardware.org/?probe=8af88f25f0) | Nov 10, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [b299fd1fe9](https://linux-hardware.org/?probe=b299fd1fe9) | Nov 09, 2023 |
| Medion        | Akoya E1318T                | [4e3e62ee88](https://linux-hardware.org/?probe=4e3e62ee88) | Nov 09, 2023 |
| Acer          | Aspire E1-571               | [665ed1538e](https://linux-hardware.org/?probe=665ed1538e) | Nov 09, 2023 |
| HUAWEI        | KPL-W0X                     | [2e06b9e7ff](https://linux-hardware.org/?probe=2e06b9e7ff) | Nov 09, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | [58c681b475](https://linux-hardware.org/?probe=58c681b475) | Nov 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [80431017dc](https://linux-hardware.org/?probe=80431017dc) | Nov 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [9ae1f9c05f](https://linux-hardware.org/?probe=9ae1f9c05f) | Nov 08, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [16cf6c0ede](https://linux-hardware.org/?probe=16cf6c0ede) | Nov 08, 2023 |
| MSI           | Alpha 17 C7VG               | [6ac34aa88a](https://linux-hardware.org/?probe=6ac34aa88a) | Nov 06, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [436bd1729a](https://linux-hardware.org/?probe=436bd1729a) | Nov 06, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [1da691596b](https://linux-hardware.org/?probe=1da691596b) | Nov 06, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [d385d4714c](https://linux-hardware.org/?probe=d385d4714c) | Nov 06, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [d40cc6e0a4](https://linux-hardware.org/?probe=d40cc6e0a4) | Nov 05, 2023 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | [e25bb48957](https://linux-hardware.org/?probe=e25bb48957) | Nov 05, 2023 |
| Dell          | XPS 17 9720                 | [39e8a692ae](https://linux-hardware.org/?probe=39e8a692ae) | Nov 05, 2023 |
| ASUSTek       | X541NA                      | [f0399efc08](https://linux-hardware.org/?probe=f0399efc08) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | [fd9594de89](https://linux-hardware.org/?probe=fd9594de89) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | [a5a8cf5c09](https://linux-hardware.org/?probe=a5a8cf5c09) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | [74099b3a6e](https://linux-hardware.org/?probe=74099b3a6e) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | [bdad71bf99](https://linux-hardware.org/?probe=bdad71bf99) | Nov 05, 2023 |
| HP            | 255 G7 Notebook PC          | [bdd24f60d2](https://linux-hardware.org/?probe=bdd24f60d2) | Nov 05, 2023 |
| Lenovo        | ThinkPad T460 20FMS3YT01    | [89b8df73c1](https://linux-hardware.org/?probe=89b8df73c1) | Nov 04, 2023 |
| Dell          | Inspiron 16 5620            | [04d425d450](https://linux-hardware.org/?probe=04d425d450) | Nov 04, 2023 |
| Lenovo        | 80SY                        | [7c7a6ba82f](https://linux-hardware.org/?probe=7c7a6ba82f) | Nov 04, 2023 |
| Unknown       | Unknown                     | [9999b9fa3d](https://linux-hardware.org/?probe=9999b9fa3d) | Nov 04, 2023 |
| MSI           | GV62 7RE                    | [a6ce21c9de](https://linux-hardware.org/?probe=a6ce21c9de) | Nov 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [db71fb65bf](https://linux-hardware.org/?probe=db71fb65bf) | Nov 03, 2023 |
| Dell          | Latitude E6420              | [43ccf36bf0](https://linux-hardware.org/?probe=43ccf36bf0) | Nov 03, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [4ccd2ef567](https://linux-hardware.org/?probe=4ccd2ef567) | Nov 03, 2023 |
| Acer          | Aspire V3-771               | [3a0023b4ba](https://linux-hardware.org/?probe=3a0023b4ba) | Nov 03, 2023 |
| Acer          | Nitro AN515-54              | [3ddccb994b](https://linux-hardware.org/?probe=3ddccb994b) | Nov 03, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [027a0a96da](https://linux-hardware.org/?probe=027a0a96da) | Nov 02, 2023 |
| Dell          | Latitude E6420              | [cdef3b5f1c](https://linux-hardware.org/?probe=cdef3b5f1c) | Nov 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [0c8b2cd660](https://linux-hardware.org/?probe=0c8b2cd660) | Nov 01, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [45d3b00840](https://linux-hardware.org/?probe=45d3b00840) | Nov 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7dd972fb0d](https://linux-hardware.org/?probe=7dd972fb0d) | Nov 01, 2023 |
| HP            | Pavilion g7                 | [157c592b3a](https://linux-hardware.org/?probe=157c592b3a) | Nov 01, 2023 |
| Dell          | Inspiron 13-5368            | [6d00cda16c](https://linux-hardware.org/?probe=6d00cda16c) | Nov 01, 2023 |
| Dell          | Latitude 3190               | [dc68dc55c9](https://linux-hardware.org/?probe=dc68dc55c9) | Oct 31, 2023 |
| HP            | Laptop 15s-eq0xxx           | [1323e3ad04](https://linux-hardware.org/?probe=1323e3ad04) | Oct 31, 2023 |
| Acer          | Aspire V3-771               | [00ffbda72d](https://linux-hardware.org/?probe=00ffbda72d) | Oct 31, 2023 |
| Apple         | MacBookPro14,1              | [12e8c83970](https://linux-hardware.org/?probe=12e8c83970) | Oct 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [fe7dbb2385](https://linux-hardware.org/?probe=fe7dbb2385) | Oct 29, 2023 |
| Dell          | Precision M6600             | [30e8d1522d](https://linux-hardware.org/?probe=30e8d1522d) | Oct 29, 2023 |
| HUAWEI        | HKD-WXX                     | [101c8c676c](https://linux-hardware.org/?probe=101c8c676c) | Oct 29, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | [f78fcbc612](https://linux-hardware.org/?probe=f78fcbc612) | Oct 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [bbba3e21c7](https://linux-hardware.org/?probe=bbba3e21c7) | Oct 27, 2023 |
| Dell          | Inspiron 1525               | [0a0a08dd5f](https://linux-hardware.org/?probe=0a0a08dd5f) | Oct 26, 2023 |
| MSI           | MS-1688                     | [c3689c0452](https://linux-hardware.org/?probe=c3689c0452) | Oct 26, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | [7f10f1b379](https://linux-hardware.org/?probe=7f10f1b379) | Oct 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [e3c1de1472](https://linux-hardware.org/?probe=e3c1de1472) | Oct 26, 2023 |
| Valve         | Jupiter                     | [38a8824fe8](https://linux-hardware.org/?probe=38a8824fe8) | Oct 25, 2023 |
| HP            | Compaq 610                  | [f449560c8a](https://linux-hardware.org/?probe=f449560c8a) | Oct 25, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | [6c88fcef70](https://linux-hardware.org/?probe=6c88fcef70) | Oct 25, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [3eee01cd16](https://linux-hardware.org/?probe=3eee01cd16) | Oct 24, 2023 |
| Notebook      | P7xxDM(-G)                  | [bb211b2fb4](https://linux-hardware.org/?probe=bb211b2fb4) | Oct 24, 2023 |
| Dell          | Inspiron 5737               | [06247cab2e](https://linux-hardware.org/?probe=06247cab2e) | Oct 24, 2023 |
| Dell          | Inspiron 11 - 3147          | [7be979fc66](https://linux-hardware.org/?probe=7be979fc66) | Oct 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [8da5e9e836](https://linux-hardware.org/?probe=8da5e9e836) | Oct 23, 2023 |
| Lenovo        | ThinkPad A485 20MVS0X62X    | [52661c1969](https://linux-hardware.org/?probe=52661c1969) | Oct 22, 2023 |
| HP            | 250 G8 Notebook PC          | [9538ff99bf](https://linux-hardware.org/?probe=9538ff99bf) | Oct 22, 2023 |
| ASUSTek       | K53SV                       | [66d1164d86](https://linux-hardware.org/?probe=66d1164d86) | Oct 21, 2023 |
| Dell          | Precision 5520              | [79b5c73851](https://linux-hardware.org/?probe=79b5c73851) | Oct 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [dca6ad28b3](https://linux-hardware.org/?probe=dca6ad28b3) | Oct 21, 2023 |
| Lenovo        | G510 20238                  | [d6bd0eda6d](https://linux-hardware.org/?probe=d6bd0eda6d) | Oct 21, 2023 |
| Dell          | Inspiron 5559               | [83811b2a84](https://linux-hardware.org/?probe=83811b2a84) | Oct 21, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [1ff62f5fd7](https://linux-hardware.org/?probe=1ff62f5fd7) | Oct 21, 2023 |
| Dell          | XPS 15 9520                 | [7deca235e3](https://linux-hardware.org/?probe=7deca235e3) | Oct 20, 2023 |
| Dell          | Latitude 5440               | [e3760f51a8](https://linux-hardware.org/?probe=e3760f51a8) | Oct 19, 2023 |
| Dell          | Latitude 5440               | [257850f5d8](https://linux-hardware.org/?probe=257850f5d8) | Oct 18, 2023 |
| Dell          | Latitude 5440               | [2097e4ed5e](https://linux-hardware.org/?probe=2097e4ed5e) | Oct 18, 2023 |
| Unknown       | Unknown                     | [e1751f1726](https://linux-hardware.org/?probe=e1751f1726) | Oct 17, 2023 |
| Dell          | Latitude E6420              | [f703c6bd74](https://linux-hardware.org/?probe=f703c6bd74) | Oct 17, 2023 |
| Acer          | Aspire A315-56              | [9eb823dcdd](https://linux-hardware.org/?probe=9eb823dcdd) | Oct 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | [7b5cf8abfc](https://linux-hardware.org/?probe=7b5cf8abfc) | Oct 17, 2023 |
| Dell          | Latitude 3190               | [6524dff50f](https://linux-hardware.org/?probe=6524dff50f) | Oct 17, 2023 |
| HP            | ProBook 6560b               | [3567f55849](https://linux-hardware.org/?probe=3567f55849) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | [77c1531b00](https://linux-hardware.org/?probe=77c1531b00) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | [2960de2715](https://linux-hardware.org/?probe=2960de2715) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [fd52faa27e](https://linux-hardware.org/?probe=fd52faa27e) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [39d3b3133e](https://linux-hardware.org/?probe=39d3b3133e) | Oct 14, 2023 |
| HP            | ProBook 6560b               | [49ffe8b6c5](https://linux-hardware.org/?probe=49ffe8b6c5) | Oct 14, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [d68359ee50](https://linux-hardware.org/?probe=d68359ee50) | Oct 14, 2023 |
| HP            | EliteBook 830 13 inch G1... | [e9ced529e2](https://linux-hardware.org/?probe=e9ced529e2) | Oct 14, 2023 |
| Lenovo        | ThinkPad T430u 3352A83      | [c5a829d842](https://linux-hardware.org/?probe=c5a829d842) | Oct 14, 2023 |
| Lenovo        | ThinkPad T400 64757D7       | [b374e214af](https://linux-hardware.org/?probe=b374e214af) | Oct 13, 2023 |
| MSI           | GE72 6QF                    | [94f1c85d10](https://linux-hardware.org/?probe=94f1c85d10) | Oct 13, 2023 |
| HP            | Grunt                       | [af80cd9bd6](https://linux-hardware.org/?probe=af80cd9bd6) | Oct 13, 2023 |
| ASUSTek       | X510UQ                      | [0494369566](https://linux-hardware.org/?probe=0494369566) | Oct 12, 2023 |
| Lenovo        | IdeaPad P500 20210          | [ba316cb723](https://linux-hardware.org/?probe=ba316cb723) | Oct 12, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | [c83831e304](https://linux-hardware.org/?probe=c83831e304) | Oct 11, 2023 |
| MSI           | GL75 9SE                    | [bffc7bdfe6](https://linux-hardware.org/?probe=bffc7bdfe6) | Oct 11, 2023 |
| Dell          | Latitude 5511               | [164cc57420](https://linux-hardware.org/?probe=164cc57420) | Oct 10, 2023 |
| Dell          | Latitude 5511               | [9827df8ea8](https://linux-hardware.org/?probe=9827df8ea8) | Oct 10, 2023 |
| Dell          | XPS 15 9520                 | [04fbcfc11b](https://linux-hardware.org/?probe=04fbcfc11b) | Oct 10, 2023 |
| Dell          | Latitude E5530 non-vPro     | [df4f5f4e21](https://linux-hardware.org/?probe=df4f5f4e21) | Oct 09, 2023 |
| Acer          | Aspire 5755G                | [d4efaf21cb](https://linux-hardware.org/?probe=d4efaf21cb) | Oct 08, 2023 |
| Google        | Sasuke                      | [ea2d350776](https://linux-hardware.org/?probe=ea2d350776) | Oct 08, 2023 |
| HP            | EliteBook 745 G4            | [8a9290f8a1](https://linux-hardware.org/?probe=8a9290f8a1) | Oct 08, 2023 |
| Acer          | Aspire 5755G                | [889b36122b](https://linux-hardware.org/?probe=889b36122b) | Oct 08, 2023 |
| Google        | Lindar                      | [75852e1ad7](https://linux-hardware.org/?probe=75852e1ad7) | Oct 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3cfe6c7d0c](https://linux-hardware.org/?probe=3cfe6c7d0c) | Oct 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | [c0a093d7d2](https://linux-hardware.org/?probe=c0a093d7d2) | Oct 08, 2023 |
| Samsung       | 550P5C/550P7C               | [a95183052c](https://linux-hardware.org/?probe=a95183052c) | Oct 08, 2023 |
| HP            | EliteBook 840 G5            | [3ce37336af](https://linux-hardware.org/?probe=3ce37336af) | Oct 06, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [c07c01c9e6](https://linux-hardware.org/?probe=c07c01c9e6) | Oct 06, 2023 |
| Apple         | MacBookAir5,2               | [6c5a7d30f3](https://linux-hardware.org/?probe=6c5a7d30f3) | Oct 06, 2023 |
| HUAWEI        | KLVL-WXX9                   | [3b01422b2a](https://linux-hardware.org/?probe=3b01422b2a) | Oct 05, 2023 |
| Apple         | MacBookAir5,2               | [7ad16296eb](https://linux-hardware.org/?probe=7ad16296eb) | Oct 05, 2023 |
| HP            | EliteBook 735 G6            | [94ac6e4439](https://linux-hardware.org/?probe=94ac6e4439) | Oct 04, 2023 |
| GPU Compan... | GWTN156-11                  | [8a684c7512](https://linux-hardware.org/?probe=8a684c7512) | Oct 04, 2023 |
| Apple         | MacBookPro4,1               | [e31f443ff9](https://linux-hardware.org/?probe=e31f443ff9) | Oct 04, 2023 |
| HP            | EliteBook 840 G2            | [4161bb4b7f](https://linux-hardware.org/?probe=4161bb4b7f) | Oct 04, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [c40f80d33a](https://linux-hardware.org/?probe=c40f80d33a) | Oct 03, 2023 |
| Dell          | Latitude 3190               | [21aac15234](https://linux-hardware.org/?probe=21aac15234) | Oct 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [001368f3a9](https://linux-hardware.org/?probe=001368f3a9) | Oct 03, 2023 |
| HP            | EliteBook 840 G5            | [880b4780ee](https://linux-hardware.org/?probe=880b4780ee) | Oct 03, 2023 |
| Lenovo        | ThinkPad X390 20Q1S5K400    | [4d9d1bf62a](https://linux-hardware.org/?probe=4d9d1bf62a) | Oct 02, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [09b97f9681](https://linux-hardware.org/?probe=09b97f9681) | Oct 02, 2023 |
| Dell          | Inspiron 13-5368            | [b7463e19f8](https://linux-hardware.org/?probe=b7463e19f8) | Oct 02, 2023 |
| HP            | ProBook 6560b               | [ea59e8557f](https://linux-hardware.org/?probe=ea59e8557f) | Oct 01, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [f52bb9587d](https://linux-hardware.org/?probe=f52bb9587d) | Oct 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [34b8e1853b](https://linux-hardware.org/?probe=34b8e1853b) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [6c314cd812](https://linux-hardware.org/?probe=6c314cd812) | Oct 01, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [61a08e5e89](https://linux-hardware.org/?probe=61a08e5e89) | Oct 01, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [0a11dba9ac](https://linux-hardware.org/?probe=0a11dba9ac) | Sep 30, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [48ff113276](https://linux-hardware.org/?probe=48ff113276) | Sep 30, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [d180995f93](https://linux-hardware.org/?probe=d180995f93) | Sep 30, 2023 |
| Acer          | Aspire E5-571G              | [b223d9b4f5](https://linux-hardware.org/?probe=b223d9b4f5) | Sep 30, 2023 |
| Dell          | Latitude 5430               | [eee2a34ff5](https://linux-hardware.org/?probe=eee2a34ff5) | Sep 30, 2023 |
| HP            | ProBook 6560b               | [904f0eb2cb](https://linux-hardware.org/?probe=904f0eb2cb) | Sep 30, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a0e4942d9f](https://linux-hardware.org/?probe=a0e4942d9f) | Sep 30, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [702d68e226](https://linux-hardware.org/?probe=702d68e226) | Sep 30, 2023 |
| HP            | Notebook                    | [193ec8deb3](https://linux-hardware.org/?probe=193ec8deb3) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [6e7e482b2d](https://linux-hardware.org/?probe=6e7e482b2d) | Sep 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [cd9628c344](https://linux-hardware.org/?probe=cd9628c344) | Sep 29, 2023 |
| HP            | EliteBook 745 G5            | [b734ec49e2](https://linux-hardware.org/?probe=b734ec49e2) | Sep 29, 2023 |
| ASUSTek       | K55VJ                       | [4befa6db63](https://linux-hardware.org/?probe=4befa6db63) | Sep 29, 2023 |
| Lenovo        | IdeaPad Y530                | [83a6d1b19b](https://linux-hardware.org/?probe=83a6d1b19b) | Sep 28, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [1d2bd102c6](https://linux-hardware.org/?probe=1d2bd102c6) | Sep 28, 2023 |
| HP            | 620                         | [1bdfd56638](https://linux-hardware.org/?probe=1bdfd56638) | Sep 27, 2023 |
| HUAWEI        | KLVL-WXX9                   | [5646b6da22](https://linux-hardware.org/?probe=5646b6da22) | Sep 27, 2023 |
| HUAWEI        | KLVL-WXXW                   | [4f1f07158b](https://linux-hardware.org/?probe=4f1f07158b) | Sep 26, 2023 |
| Google        | Blorb                       | [efa4ad9e2c](https://linux-hardware.org/?probe=efa4ad9e2c) | Sep 26, 2023 |
| Lenovo        | ThinkPad T590 20N5S31U02    | [d4137582b5](https://linux-hardware.org/?probe=d4137582b5) | Sep 26, 2023 |
| Google        | Phaser360                   | [95686db08c](https://linux-hardware.org/?probe=95686db08c) | Sep 26, 2023 |
| Lenovo        | ThinkPad T590 20N5S31U02    | [aa988ac4df](https://linux-hardware.org/?probe=aa988ac4df) | Sep 26, 2023 |
| Lenovo        | ThinkPad T480s 20L8S77U1... | [4a3185fd78](https://linux-hardware.org/?probe=4a3185fd78) | Sep 26, 2023 |
| HP            | EliteBook 840 G3            | [5ab77e3f48](https://linux-hardware.org/?probe=5ab77e3f48) | Sep 26, 2023 |
| Dell          | Latitude 3190               | [8ebd8669f2](https://linux-hardware.org/?probe=8ebd8669f2) | Sep 26, 2023 |
| Dell          | Inspiron 3581               | [11796876dd](https://linux-hardware.org/?probe=11796876dd) | Sep 25, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [408377c3fd](https://linux-hardware.org/?probe=408377c3fd) | Sep 24, 2023 |
| Dell          | System Vostro 3750          | [3b050c2582](https://linux-hardware.org/?probe=3b050c2582) | Sep 24, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [ff891ca545](https://linux-hardware.org/?probe=ff891ca545) | Sep 24, 2023 |
| HP            | 250 G8 Notebook PC          | [6b3c3ce703](https://linux-hardware.org/?probe=6b3c3ce703) | Sep 23, 2023 |
| HP            | 250 G8 Notebook PC          | [e2dd7767f0](https://linux-hardware.org/?probe=e2dd7767f0) | Sep 23, 2023 |
| Dell          | Precision M6600             | [1cef385aec](https://linux-hardware.org/?probe=1cef385aec) | Sep 23, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [4bf358cd4f](https://linux-hardware.org/?probe=4bf358cd4f) | Sep 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [1d9ae81bf1](https://linux-hardware.org/?probe=1d9ae81bf1) | Sep 22, 2023 |
| Dell          | Latitude 5421               | [fd5892945d](https://linux-hardware.org/?probe=fd5892945d) | Sep 21, 2023 |
| Dell          | Latitude 5421               | [50a3d79521](https://linux-hardware.org/?probe=50a3d79521) | Sep 21, 2023 |
| Lenovo        | ThinkPad X270 20HMS0DF00    | [276048d4f4](https://linux-hardware.org/?probe=276048d4f4) | Sep 20, 2023 |
| HP            | ProBook 6560b               | [a7eae64ec7](https://linux-hardware.org/?probe=a7eae64ec7) | Sep 20, 2023 |
| Lenovo        | ThinkPad E580 20KS001RUK    | [9882734ee2](https://linux-hardware.org/?probe=9882734ee2) | Sep 20, 2023 |
| HP            | EliteBook 735 G6            | [0ad032f320](https://linux-hardware.org/?probe=0ad032f320) | Sep 19, 2023 |
| Dell          | Latitude 3190               | [0a698044d8](https://linux-hardware.org/?probe=0a698044d8) | Sep 19, 2023 |
| HP            | Notebook                    | [c41430992d](https://linux-hardware.org/?probe=c41430992d) | Sep 18, 2023 |
| Dell          | Latitude 5490               | [94eb709dfc](https://linux-hardware.org/?probe=94eb709dfc) | Sep 18, 2023 |
| Lenovo        | ThinkPad T460 20FN003LMS    | [13de66f73a](https://linux-hardware.org/?probe=13de66f73a) | Sep 17, 2023 |
| Dell          | Latitude E5420              | [56c6b73d62](https://linux-hardware.org/?probe=56c6b73d62) | Sep 17, 2023 |
| Dell          | Latitude E5420              | [5931b51b00](https://linux-hardware.org/?probe=5931b51b00) | Sep 17, 2023 |
| HP            | G72                         | [b77f2ba361](https://linux-hardware.org/?probe=b77f2ba361) | Sep 17, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [832c9cf416](https://linux-hardware.org/?probe=832c9cf416) | Sep 17, 2023 |
| Lenovo        | Z51-70 80K6                 | [8368825071](https://linux-hardware.org/?probe=8368825071) | Sep 17, 2023 |
| Dell          | Latitude 5421               | [a42c87b953](https://linux-hardware.org/?probe=a42c87b953) | Sep 17, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [ef3516c115](https://linux-hardware.org/?probe=ef3516c115) | Sep 17, 2023 |
| IGEL Techn... | M330C                       | [ba678c25e1](https://linux-hardware.org/?probe=ba678c25e1) | Sep 17, 2023 |
| IGEL Techn... | M330C                       | [b056244ce9](https://linux-hardware.org/?probe=b056244ce9) | Sep 17, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9915642af4](https://linux-hardware.org/?probe=9915642af4) | Sep 16, 2023 |
| Dell          | Latitude 9420               | [35feb16995](https://linux-hardware.org/?probe=35feb16995) | Sep 15, 2023 |
| Dell          | Latitude 9420               | [da407d0553](https://linux-hardware.org/?probe=da407d0553) | Sep 15, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [d321e5cfc8](https://linux-hardware.org/?probe=d321e5cfc8) | Sep 14, 2023 |
| Acer          | Nitro AN515-42              | [96f4c972a0](https://linux-hardware.org/?probe=96f4c972a0) | Sep 14, 2023 |
| ASUSTek       | P553UJ                      | [3463413300](https://linux-hardware.org/?probe=3463413300) | Sep 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [d4e392a0ad](https://linux-hardware.org/?probe=d4e392a0ad) | Sep 12, 2023 |
| Dell          | Latitude E4200              | [ab13ebe930](https://linux-hardware.org/?probe=ab13ebe930) | Sep 12, 2023 |
| Dell          | Latitude 3190               | [a03ec42023](https://linux-hardware.org/?probe=a03ec42023) | Sep 12, 2023 |
| Lenovo        | G565 20071                  | [34149789e7](https://linux-hardware.org/?probe=34149789e7) | Sep 12, 2023 |
| HP            | 620                         | [59577ac122](https://linux-hardware.org/?probe=59577ac122) | Sep 12, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [27b430aa3f](https://linux-hardware.org/?probe=27b430aa3f) | Sep 11, 2023 |
| Dell          | Precision 5530              | [7e0e7dca27](https://linux-hardware.org/?probe=7e0e7dca27) | Sep 10, 2023 |
| LG Electro... | 15Z990-U.AAS5U1             | [61eed61cd5](https://linux-hardware.org/?probe=61eed61cd5) | Sep 10, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [f01636c129](https://linux-hardware.org/?probe=f01636c129) | Sep 09, 2023 |
| Lenovo        | ThinkPad L390 20NSS04400    | [e35abd1445](https://linux-hardware.org/?probe=e35abd1445) | Sep 09, 2023 |
| HP            | ProBook 6470b               | [1c8817d025](https://linux-hardware.org/?probe=1c8817d025) | Sep 09, 2023 |
| Acer          | Nitro AN515-44              | [032db27cfa](https://linux-hardware.org/?probe=032db27cfa) | Sep 08, 2023 |
| Lenovo        | G565 20071                  | [786aafb0e9](https://linux-hardware.org/?probe=786aafb0e9) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d3e36fc6ea](https://linux-hardware.org/?probe=d3e36fc6ea) | Sep 05, 2023 |
| Dell          | Precision M4800             | [2e40a27b2e](https://linux-hardware.org/?probe=2e40a27b2e) | Sep 04, 2023 |
| Prestigio     | Smartbook PSB116A           | [d70df77a35](https://linux-hardware.org/?probe=d70df77a35) | Sep 04, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1d6a4b4279](https://linux-hardware.org/?probe=1d6a4b4279) | Sep 04, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | [2973871c04](https://linux-hardware.org/?probe=2973871c04) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [2a24e7410f](https://linux-hardware.org/?probe=2a24e7410f) | Sep 03, 2023 |
| Unknown       | Unknown                     | [8585671bfb](https://linux-hardware.org/?probe=8585671bfb) | Sep 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [efd96ce796](https://linux-hardware.org/?probe=efd96ce796) | Sep 03, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [5f73c55303](https://linux-hardware.org/?probe=5f73c55303) | Sep 03, 2023 |
| Lenovo        | ThinkPad X280 20KESAA400    | [461a3a9bc9](https://linux-hardware.org/?probe=461a3a9bc9) | Sep 02, 2023 |
| Valve         | Jupiter                     | [fd0297e4e0](https://linux-hardware.org/?probe=fd0297e4e0) | Sep 01, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [678bbd1366](https://linux-hardware.org/?probe=678bbd1366) | Sep 01, 2023 |
| Lenovo        | ThinkPad X301 2774LEG       | [50f297712d](https://linux-hardware.org/?probe=50f297712d) | Sep 01, 2023 |
| Dell          | Inspiron 13-5368            | [e811db37c5](https://linux-hardware.org/?probe=e811db37c5) | Sep 01, 2023 |
| Lenovo        | ThinkPad S5-S540 20B3006... | [e33b222d6c](https://linux-hardware.org/?probe=e33b222d6c) | Sep 01, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [b900fd0bc7](https://linux-hardware.org/?probe=b900fd0bc7) | Aug 31, 2023 |
| HP            | ProBook 4530s               | [09fddaab4d](https://linux-hardware.org/?probe=09fddaab4d) | Aug 31, 2023 |
| Dell          | Latitude 7390               | [a9c1ad1756](https://linux-hardware.org/?probe=a9c1ad1756) | Aug 31, 2023 |
| HP            | ProBook 645 G1              | [ca7a99ecd9](https://linux-hardware.org/?probe=ca7a99ecd9) | Aug 31, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [76f095d7c2](https://linux-hardware.org/?probe=76f095d7c2) | Aug 31, 2023 |
| Dell          | Inspiron 7520               | [f3e3f12f08](https://linux-hardware.org/?probe=f3e3f12f08) | Aug 30, 2023 |
| Lenovo        | G50-80 80E5                 | [3977e85dce](https://linux-hardware.org/?probe=3977e85dce) | Aug 30, 2023 |
| Dell          | Latitude 5430               | [477898be1f](https://linux-hardware.org/?probe=477898be1f) | Aug 30, 2023 |
| Lenovo        | ThinkPad T470p 20J60014P... | [7690eb9089](https://linux-hardware.org/?probe=7690eb9089) | Aug 30, 2023 |
| Lenovo        | G50-80 80E5                 | [5ba6fd6ca3](https://linux-hardware.org/?probe=5ba6fd6ca3) | Aug 30, 2023 |
| Dell          | Latitude E6520              | [4918e66ad8](https://linux-hardware.org/?probe=4918e66ad8) | Aug 29, 2023 |
| Dell          | Latitude 3190               | [6e16da127a](https://linux-hardware.org/?probe=6e16da127a) | Aug 29, 2023 |
| Dell          | Latitude D630               | [d23ff7e118](https://linux-hardware.org/?probe=d23ff7e118) | Aug 29, 2023 |
| Lenovo        | G570 20079                  | [8741a9bb96](https://linux-hardware.org/?probe=8741a9bb96) | Aug 29, 2023 |
| Lenovo        | G570 20079                  | [7efcdba9ef](https://linux-hardware.org/?probe=7efcdba9ef) | Aug 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [7e48b59643](https://linux-hardware.org/?probe=7e48b59643) | Aug 29, 2023 |
| Acer          | Acadia V1.45                | [4bc36b4d27](https://linux-hardware.org/?probe=4bc36b4d27) | Aug 29, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [9071631c6d](https://linux-hardware.org/?probe=9071631c6d) | Aug 28, 2023 |
| mPTech        | ARC 11.6 128GB HD           | [4167149587](https://linux-hardware.org/?probe=4167149587) | Aug 26, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [3ee57cbdbe](https://linux-hardware.org/?probe=3ee57cbdbe) | Aug 26, 2023 |
| Lenovo        | ThinkPad E520 1143CWG       | [66d9a31686](https://linux-hardware.org/?probe=66d9a31686) | Aug 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [01ae0852df](https://linux-hardware.org/?probe=01ae0852df) | Aug 25, 2023 |
| Dell          | Latitude E6400              | [4526151015](https://linux-hardware.org/?probe=4526151015) | Aug 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [bb854d7896](https://linux-hardware.org/?probe=bb854d7896) | Aug 25, 2023 |
| Dell          | XPS 9320                    | [1ba8e13634](https://linux-hardware.org/?probe=1ba8e13634) | Aug 24, 2023 |
| Dell          | XPS 13 9310                 | [e6c72eb614](https://linux-hardware.org/?probe=e6c72eb614) | Aug 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [12ac0bf5ed](https://linux-hardware.org/?probe=12ac0bf5ed) | Aug 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [097bbaf86a](https://linux-hardware.org/?probe=097bbaf86a) | Aug 24, 2023 |
| Dell          | Latitude 3520               | [92ef936c86](https://linux-hardware.org/?probe=92ef936c86) | Aug 24, 2023 |
| Kiano         | Elegance 14.2               | [71ba491330](https://linux-hardware.org/?probe=71ba491330) | Aug 24, 2023 |
| Dell          | XPS 15 9520                 | [26d59e1060](https://linux-hardware.org/?probe=26d59e1060) | Aug 23, 2023 |
| Dell          | XPS 15 9520                 | [d10b0c4ca0](https://linux-hardware.org/?probe=d10b0c4ca0) | Aug 23, 2023 |
| HP            | Compaq nc8430 (EM741AV)     | [02d656a746](https://linux-hardware.org/?probe=02d656a746) | Aug 22, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [25d163ad9e](https://linux-hardware.org/?probe=25d163ad9e) | Aug 22, 2023 |
| Dell          | Latitude 3190               | [61ddf042df](https://linux-hardware.org/?probe=61ddf042df) | Aug 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c080c15699](https://linux-hardware.org/?probe=c080c15699) | Aug 22, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | [5fa4b8ae13](https://linux-hardware.org/?probe=5fa4b8ae13) | Aug 20, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f5751cb101](https://linux-hardware.org/?probe=f5751cb101) | Aug 19, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [800ad97443](https://linux-hardware.org/?probe=800ad97443) | Aug 19, 2023 |
| Lenovo        | ThinkPad L480 20LTS6S904    | [32ded049ec](https://linux-hardware.org/?probe=32ded049ec) | Aug 17, 2023 |
| Valve         | Jupiter                     | [b2c7c5cb9f](https://linux-hardware.org/?probe=b2c7c5cb9f) | Aug 17, 2023 |
| HP            | Laptop 14-df0xxx            | [7d3c3dc329](https://linux-hardware.org/?probe=7d3c3dc329) | Aug 17, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | [75556aed08](https://linux-hardware.org/?probe=75556aed08) | Aug 16, 2023 |
| Samsung       | RF511/RF411/RF711           | [b9134a5ee3](https://linux-hardware.org/?probe=b9134a5ee3) | Aug 16, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [f3c603341d](https://linux-hardware.org/?probe=f3c603341d) | Aug 16, 2023 |
| Lenovo        | G505s 20255                 | [2486dc323f](https://linux-hardware.org/?probe=2486dc323f) | Aug 16, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [ef53482168](https://linux-hardware.org/?probe=ef53482168) | Aug 16, 2023 |
| Lenovo        | ThinkPad T470 20HES07J00    | [32ec341753](https://linux-hardware.org/?probe=32ec341753) | Aug 16, 2023 |
| Gigabyte      | RC14UD                      | [51b04bf027](https://linux-hardware.org/?probe=51b04bf027) | Aug 16, 2023 |
| Samsung       | 530U4E/540U4E               | [7189151ffc](https://linux-hardware.org/?probe=7189151ffc) | Aug 15, 2023 |
| Dell          | XPS 15 9570                 | [ce22773504](https://linux-hardware.org/?probe=ce22773504) | Aug 15, 2023 |
| Lenovo        | G580                        | [ceeee3c405](https://linux-hardware.org/?probe=ceeee3c405) | Aug 15, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [076c807d2d](https://linux-hardware.org/?probe=076c807d2d) | Aug 14, 2023 |
| Samsung       | 530U4E/540U4E               | [6a886e53b9](https://linux-hardware.org/?probe=6a886e53b9) | Aug 14, 2023 |
| HP            | Pavilion dv7                | [8af14f1aaa](https://linux-hardware.org/?probe=8af14f1aaa) | Aug 13, 2023 |
| ASUSTek       | GL552VW                     | [1d77ac2450](https://linux-hardware.org/?probe=1d77ac2450) | Aug 13, 2023 |
| Acer          | Predator G5-793             | [bb25759563](https://linux-hardware.org/?probe=bb25759563) | Aug 13, 2023 |
| HP            | EliteBook 845 G9            | [cf6dfa50ef](https://linux-hardware.org/?probe=cf6dfa50ef) | Aug 12, 2023 |
| Valve         | Jupiter                     | [b770999baf](https://linux-hardware.org/?probe=b770999baf) | Aug 12, 2023 |
| Lenovo        | G580 20150                  | [b296a33ab3](https://linux-hardware.org/?probe=b296a33ab3) | Aug 12, 2023 |
| Apple         | MacBookPro13,3              | [b43e2738d9](https://linux-hardware.org/?probe=b43e2738d9) | Aug 12, 2023 |
| ASUSTek       | GL552VW                     | [6986ca63da](https://linux-hardware.org/?probe=6986ca63da) | Aug 12, 2023 |
| Fujitsu       | FMVA0800C                   | [1dae7b170b](https://linux-hardware.org/?probe=1dae7b170b) | Aug 12, 2023 |
| HP            | Pavilion dv7                | [7e4a63e58c](https://linux-hardware.org/?probe=7e4a63e58c) | Aug 12, 2023 |
| HP            | Pavilion dv7                | [fc48a936d7](https://linux-hardware.org/?probe=fc48a936d7) | Aug 12, 2023 |
| Lenovo        | ThinkPad T430s 2356LPG      | [97dfe9511b](https://linux-hardware.org/?probe=97dfe9511b) | Aug 10, 2023 |
| Google        | Kip                         | [553df8dcdc](https://linux-hardware.org/?probe=553df8dcdc) | Aug 10, 2023 |
| Dell          | Latitude E6540              | [758d587fbb](https://linux-hardware.org/?probe=758d587fbb) | Aug 10, 2023 |
| HP            | ProBook 450 G6              | [c205f19d5e](https://linux-hardware.org/?probe=c205f19d5e) | Aug 09, 2023 |
| HP            | EliteBook 845 G9            | [1ff8d81e4e](https://linux-hardware.org/?probe=1ff8d81e4e) | Aug 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [81411c1db8](https://linux-hardware.org/?probe=81411c1db8) | Aug 08, 2023 |
| Acer          | Aspire 5732Z                | [5a0ee0b4c0](https://linux-hardware.org/?probe=5a0ee0b4c0) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [f6b63d9967](https://linux-hardware.org/?probe=f6b63d9967) | Aug 08, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [9094c29548](https://linux-hardware.org/?probe=9094c29548) | Aug 07, 2023 |
| HP            | ZBook 15 G3                 | [068b8c5a6f](https://linux-hardware.org/?probe=068b8c5a6f) | Aug 07, 2023 |
| Dell          | Vostro 5471                 | [f4beee823e](https://linux-hardware.org/?probe=f4beee823e) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [08b395f8d6](https://linux-hardware.org/?probe=08b395f8d6) | Aug 07, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [270c9a3ea0](https://linux-hardware.org/?probe=270c9a3ea0) | Aug 06, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [f77c465da0](https://linux-hardware.org/?probe=f77c465da0) | Aug 06, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [db5a797fc0](https://linux-hardware.org/?probe=db5a797fc0) | Aug 06, 2023 |
| ASUSTek       | ROG Strix G731GU_GL731GU    | [b3c77ee42f](https://linux-hardware.org/?probe=b3c77ee42f) | Aug 05, 2023 |
| Dell          | Latitude 5421               | [d01013b679](https://linux-hardware.org/?probe=d01013b679) | Aug 05, 2023 |
| Dell          | Latitude 5421               | [5dfde4e6ac](https://linux-hardware.org/?probe=5dfde4e6ac) | Aug 05, 2023 |
| Gigabyte      | RC14UD                      | [6ad0758102](https://linux-hardware.org/?probe=6ad0758102) | Aug 04, 2023 |
| Lenovo        | G50-45 80E3                 | [34edcb7dae](https://linux-hardware.org/?probe=34edcb7dae) | Aug 04, 2023 |
| Dell          | Vostro 15 3510              | [bd994e4cc6](https://linux-hardware.org/?probe=bd994e4cc6) | Aug 04, 2023 |
| Dell          | Vostro 15 3510              | [ab2f3b8c7b](https://linux-hardware.org/?probe=ab2f3b8c7b) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [8036065591](https://linux-hardware.org/?probe=8036065591) | Aug 03, 2023 |
| Dell          | Inspiron 13-5368            | [695e2dec6b](https://linux-hardware.org/?probe=695e2dec6b) | Aug 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c2c27c3268](https://linux-hardware.org/?probe=c2c27c3268) | Aug 01, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [762d07665a](https://linux-hardware.org/?probe=762d07665a) | Jul 31, 2023 |
| ASUSTek       | E200HA                      | [6ab93e7940](https://linux-hardware.org/?probe=6ab93e7940) | Jul 30, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [60cfcb00e9](https://linux-hardware.org/?probe=60cfcb00e9) | Jul 30, 2023 |
| Google        | Relm                        | [1c8bd1f9dd](https://linux-hardware.org/?probe=1c8bd1f9dd) | Jul 30, 2023 |
| Lenovo        | ThinkPad A285 20MXS0AE00    | [a6ada51a02](https://linux-hardware.org/?probe=a6ada51a02) | Jul 29, 2023 |
| Dell          | Latitude E7240              | [b794bcdde6](https://linux-hardware.org/?probe=b794bcdde6) | Jul 29, 2023 |
| Dell          | Inspiron 7559               | [fad00d6412](https://linux-hardware.org/?probe=fad00d6412) | Jul 29, 2023 |
| ASUSTek       | X555LJ                      | [690e49362b](https://linux-hardware.org/?probe=690e49362b) | Jul 28, 2023 |
| HP            | Pavilion Gaming Laptop      | [b277fcda26](https://linux-hardware.org/?probe=b277fcda26) | Jul 28, 2023 |
| Toshiba       | Satellite C50D-A-11G        | [b67508b754](https://linux-hardware.org/?probe=b67508b754) | Jul 27, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [e882db39b8](https://linux-hardware.org/?probe=e882db39b8) | Jul 27, 2023 |
| Dell          | Inspiron 3583               | [e235fb3a23](https://linux-hardware.org/?probe=e235fb3a23) | Jul 26, 2023 |
| Dell          | Latitude 9420               | [03c3ca79c4](https://linux-hardware.org/?probe=03c3ca79c4) | Jul 26, 2023 |
| Dell          | XPS 15 9520                 | [24f65961ef](https://linux-hardware.org/?probe=24f65961ef) | Jul 26, 2023 |
| Apple         | MacBookPro9,2               | [af0355313e](https://linux-hardware.org/?probe=af0355313e) | Jul 25, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | [346055ca33](https://linux-hardware.org/?probe=346055ca33) | Jul 25, 2023 |
| Dell          | Latitude 3190               | [b1730d834d](https://linux-hardware.org/?probe=b1730d834d) | Jul 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [412bc51f72](https://linux-hardware.org/?probe=412bc51f72) | Jul 24, 2023 |
| Timi          | TM1701                      | [eb1246586e](https://linux-hardware.org/?probe=eb1246586e) | Jul 24, 2023 |
| ASUSTek       | F7E                         | [2aef1cc2c4](https://linux-hardware.org/?probe=2aef1cc2c4) | Jul 24, 2023 |
| Timi          | TM1701                      | [17fefbecba](https://linux-hardware.org/?probe=17fefbecba) | Jul 24, 2023 |
| Lenovo        | G500s 20245                 | [fbfa8af465](https://linux-hardware.org/?probe=fbfa8af465) | Jul 24, 2023 |
| Acer          | Aspire A715-74G             | [b27862dc34](https://linux-hardware.org/?probe=b27862dc34) | Jul 24, 2023 |
| ASUSTek       | X555LD                      | [732fe69d59](https://linux-hardware.org/?probe=732fe69d59) | Jul 23, 2023 |
| HUAWEI        | HVY-WXX9                    | [44958ef86b](https://linux-hardware.org/?probe=44958ef86b) | Jul 23, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [10e8c0d4ad](https://linux-hardware.org/?probe=10e8c0d4ad) | Jul 23, 2023 |
| Google        | Snappy                      | [a3e6774e43](https://linux-hardware.org/?probe=a3e6774e43) | Jul 23, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [467cc30f89](https://linux-hardware.org/?probe=467cc30f89) | Jul 22, 2023 |
| MSI           | PR601/VR603                 | [b982476d84](https://linux-hardware.org/?probe=b982476d84) | Jul 21, 2023 |
| Razer         | Blade 15 Base Model (Mid... | [d2d53e7406](https://linux-hardware.org/?probe=d2d53e7406) | Jul 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [fcdb1fdeed](https://linux-hardware.org/?probe=fcdb1fdeed) | Jul 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [0bd52b9adf](https://linux-hardware.org/?probe=0bd52b9adf) | Jul 20, 2023 |
| Dell          | Latitude 9420               | [750f80b869](https://linux-hardware.org/?probe=750f80b869) | Jul 19, 2023 |
| Dell          | Latitude 9420               | [a4ba4bfde1](https://linux-hardware.org/?probe=a4ba4bfde1) | Jul 19, 2023 |
| Dell          | Latitude E6400              | [7e9ef12f0d](https://linux-hardware.org/?probe=7e9ef12f0d) | Jul 19, 2023 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [17c6866da9](https://linux-hardware.org/?probe=17c6866da9) | Jul 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [35d510901b](https://linux-hardware.org/?probe=35d510901b) | Jul 18, 2023 |
| Teclast       | F6 Pro                      | [d9f3a038e0](https://linux-hardware.org/?probe=d9f3a038e0) | Jul 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | [18f41b2be6](https://linux-hardware.org/?probe=18f41b2be6) | Jul 17, 2023 |
| Lenovo        | ThinkPad X240 20AMS07T00    | [0c460a8007](https://linux-hardware.org/?probe=0c460a8007) | Jul 17, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [111c0b962d](https://linux-hardware.org/?probe=111c0b962d) | Jul 16, 2023 |
| Dell          | Latitude E6440              | [4e40dc49f3](https://linux-hardware.org/?probe=4e40dc49f3) | Jul 16, 2023 |
| HP            | Pavilion HDX9200            | [d893c8a2d1](https://linux-hardware.org/?probe=d893c8a2d1) | Jul 16, 2023 |
| Dell          | Latitude E6330              | [6adb67344f](https://linux-hardware.org/?probe=6adb67344f) | Jul 15, 2023 |
| Lenovo        | ThinkPad T495 20NKS0T101    | [6154504eac](https://linux-hardware.org/?probe=6154504eac) | Jul 15, 2023 |
| ASUSTek       | 1011PX                      | [d91fe40195](https://linux-hardware.org/?probe=d91fe40195) | Jul 15, 2023 |
| MSI           | GE70 2QD                    | [f8ddf3a3a3](https://linux-hardware.org/?probe=f8ddf3a3a3) | Jul 15, 2023 |
| Lenovo        | ThinkPad X240 20AMS07T00    | [8ce6db48b9](https://linux-hardware.org/?probe=8ce6db48b9) | Jul 15, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | [f416cb06c2](https://linux-hardware.org/?probe=f416cb06c2) | Jul 14, 2023 |
| Acer          | Aspire E5-576G              | [0856b48ae7](https://linux-hardware.org/?probe=0856b48ae7) | Jul 13, 2023 |
| Dell          | Latitude E6330              | [58ec0684cd](https://linux-hardware.org/?probe=58ec0684cd) | Jul 13, 2023 |
| Toshiba       | Satellite S75-B             | [ee71e28c8f](https://linux-hardware.org/?probe=ee71e28c8f) | Jul 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS01A0... | [54e51170a1](https://linux-hardware.org/?probe=54e51170a1) | Jul 11, 2023 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [a78428eb21](https://linux-hardware.org/?probe=a78428eb21) | Jul 11, 2023 |
| Dell          | Inspiron 5748               | [ec95cc29fd](https://linux-hardware.org/?probe=ec95cc29fd) | Jul 11, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | [ef1f607a84](https://linux-hardware.org/?probe=ef1f607a84) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [97f39991c3](https://linux-hardware.org/?probe=97f39991c3) | Jul 11, 2023 |
| Dell          | Latitude 3190               | [f067ca0dbf](https://linux-hardware.org/?probe=f067ca0dbf) | Jul 11, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [8b9677cc2a](https://linux-hardware.org/?probe=8b9677cc2a) | Jul 10, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [acdd4ea952](https://linux-hardware.org/?probe=acdd4ea952) | Jul 10, 2023 |
| Lenovo        | ThinkPad Edge 0578P6G       | [e79fbdad2d](https://linux-hardware.org/?probe=e79fbdad2d) | Jul 10, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [d4ca6c4f81](https://linux-hardware.org/?probe=d4ca6c4f81) | Jul 10, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [215d2135b3](https://linux-hardware.org/?probe=215d2135b3) | Jul 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [42aaaa0acb](https://linux-hardware.org/?probe=42aaaa0acb) | Jul 09, 2023 |
| HP            | Compaq Presario CQ60        | [60e671ef49](https://linux-hardware.org/?probe=60e671ef49) | Jul 09, 2023 |
| ASUSTek       | X555LJ                      | [2dfec77944](https://linux-hardware.org/?probe=2dfec77944) | Jul 09, 2023 |
| HP            | Laptop 14s-fq0xxx           | [92feea0533](https://linux-hardware.org/?probe=92feea0533) | Jul 08, 2023 |
| HP            | Laptop 14s-fq0xxx           | [2287c62944](https://linux-hardware.org/?probe=2287c62944) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [9b8e16f852](https://linux-hardware.org/?probe=9b8e16f852) | Jul 08, 2023 |
| Toshiba       | PORTEGE M700                | [6a67dec7ab](https://linux-hardware.org/?probe=6a67dec7ab) | Jul 08, 2023 |
| Toshiba       | PORTEGE M700                | [b735ddd9a6](https://linux-hardware.org/?probe=b735ddd9a6) | Jul 08, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [54ac55c49e](https://linux-hardware.org/?probe=54ac55c49e) | Jul 07, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [296474a1b1](https://linux-hardware.org/?probe=296474a1b1) | Jul 07, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [e4bb31a52c](https://linux-hardware.org/?probe=e4bb31a52c) | Jul 07, 2023 |
| HP            | 255 G7 Notebook PC          | [23a6105e01](https://linux-hardware.org/?probe=23a6105e01) | Jul 06, 2023 |
| Dell          | Latitude 7420               | [44c51e8365](https://linux-hardware.org/?probe=44c51e8365) | Jul 05, 2023 |
| AAEON         | AEC-6637                    | [53f8e37edc](https://linux-hardware.org/?probe=53f8e37edc) | Jul 05, 2023 |
| AAEON         | AEC-6637                    | [a105861e1d](https://linux-hardware.org/?probe=a105861e1d) | Jul 05, 2023 |
| Dell          | Latitude 7420               | [9eae2c6ad4](https://linux-hardware.org/?probe=9eae2c6ad4) | Jul 05, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [3e5dc0c313](https://linux-hardware.org/?probe=3e5dc0c313) | Jul 05, 2023 |
| HP            | 550                         | [f788d05211](https://linux-hardware.org/?probe=f788d05211) | Jul 05, 2023 |
| HP            | 650                         | [a3077996ad](https://linux-hardware.org/?probe=a3077996ad) | Jul 05, 2023 |
| Lenovo        | G500s 20245                 | [1a32b23618](https://linux-hardware.org/?probe=1a32b23618) | Jul 04, 2023 |
| Dell          | Latitude 3190               | [b895b6dced](https://linux-hardware.org/?probe=b895b6dced) | Jul 04, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | [75a8750d34](https://linux-hardware.org/?probe=75a8750d34) | Jul 03, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [f567c6c550](https://linux-hardware.org/?probe=f567c6c550) | Jul 03, 2023 |
| Google        | Relm                        | [ef72648bb6](https://linux-hardware.org/?probe=ef72648bb6) | Jul 02, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [3f2c5d0eb2](https://linux-hardware.org/?probe=3f2c5d0eb2) | Jul 01, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [f923d36676](https://linux-hardware.org/?probe=f923d36676) | Jul 01, 2023 |
| Dell          | Inspiron 7720               | [9d8f40247e](https://linux-hardware.org/?probe=9d8f40247e) | Jul 01, 2023 |
| Packard Be... | EasyNote TSX66HR            | [96253a3da8](https://linux-hardware.org/?probe=96253a3da8) | Jul 01, 2023 |
| HP            | EliteBook 820 G2            | [c99236ef84](https://linux-hardware.org/?probe=c99236ef84) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430s 23554L7      | [501b0860c8](https://linux-hardware.org/?probe=501b0860c8) | Jun 30, 2023 |
| Dell          | Latitude E6540              | [a526c901ee](https://linux-hardware.org/?probe=a526c901ee) | Jun 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [287d7d6f60](https://linux-hardware.org/?probe=287d7d6f60) | Jun 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [723de914e2](https://linux-hardware.org/?probe=723de914e2) | Jun 29, 2023 |
| Acer          | Swift SF314-43              | [363067c171](https://linux-hardware.org/?probe=363067c171) | Jun 29, 2023 |
| Dell          | XPS 15 9570                 | [34df27504f](https://linux-hardware.org/?probe=34df27504f) | Jun 28, 2023 |
| Apple         | MacBookPro7,1               | [5a82f91882](https://linux-hardware.org/?probe=5a82f91882) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [9d6748ef56](https://linux-hardware.org/?probe=9d6748ef56) | Jun 28, 2023 |
| Toshiba       | TECRA R950                  | [cab34ec3dc](https://linux-hardware.org/?probe=cab34ec3dc) | Jun 28, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [ff919014cd](https://linux-hardware.org/?probe=ff919014cd) | Jun 28, 2023 |
| ASUSTek       | K54C                        | [4152d1fcff](https://linux-hardware.org/?probe=4152d1fcff) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [64433a8783](https://linux-hardware.org/?probe=64433a8783) | Jun 27, 2023 |
| Lenovo        | G500s 20245                 | [1aa332e26f](https://linux-hardware.org/?probe=1aa332e26f) | Jun 27, 2023 |
| Valve         | Jupiter                     | [0817dd25ff](https://linux-hardware.org/?probe=0817dd25ff) | Jun 27, 2023 |
| Dell          | Latitude 3190               | [5f68b5235f](https://linux-hardware.org/?probe=5f68b5235f) | Jun 27, 2023 |
| Toshiba       | TECRA R950                  | [f02bb9a43a](https://linux-hardware.org/?probe=f02bb9a43a) | Jun 26, 2023 |
| HP            | 255 G5 Notebook PC          | [cad891675f](https://linux-hardware.org/?probe=cad891675f) | Jun 25, 2023 |
| eMachines     | eME732ZG                    | [4e1d6873ff](https://linux-hardware.org/?probe=4e1d6873ff) | Jun 24, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [0ec7fedf29](https://linux-hardware.org/?probe=0ec7fedf29) | Jun 24, 2023 |
| Packard Be... | EasyNote TK85               | [314e344780](https://linux-hardware.org/?probe=314e344780) | Jun 24, 2023 |
| Lenovo        | ThinkPad T430 2347BS4       | [a8a9689ea6](https://linux-hardware.org/?probe=a8a9689ea6) | Jun 24, 2023 |
| Lenovo        | ThinkPad L390 20NSS04400    | [feced26491](https://linux-hardware.org/?probe=feced26491) | Jun 23, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [c75670186a](https://linux-hardware.org/?probe=c75670186a) | Jun 23, 2023 |
| Lenovo        | G500s 20245                 | [17db397c48](https://linux-hardware.org/?probe=17db397c48) | Jun 22, 2023 |
| Toshiba       | Satellite Pro C70-B         | [f96a1a3552](https://linux-hardware.org/?probe=f96a1a3552) | Jun 21, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | [5de086be7a](https://linux-hardware.org/?probe=5de086be7a) | Jun 21, 2023 |
| Toshiba       | Satellite Pro C70-B         | [52c4c32098](https://linux-hardware.org/?probe=52c4c32098) | Jun 21, 2023 |
| Notebook      | NV4xPZ                      | [873c70b184](https://linux-hardware.org/?probe=873c70b184) | Jun 21, 2023 |
| Lenovo        | B570 HuronRiver Platform    | [b51dda105a](https://linux-hardware.org/?probe=b51dda105a) | Jun 20, 2023 |
| Toshiba       | Satellite A300              | [f37d67a18d](https://linux-hardware.org/?probe=f37d67a18d) | Jun 19, 2023 |
| Razer         | Blade Stealth 13 (Early ... | [e3843be450](https://linux-hardware.org/?probe=e3843be450) | Jun 18, 2023 |
| HP            | Pavilion dv2                | [3f3b0104a4](https://linux-hardware.org/?probe=3f3b0104a4) | Jun 18, 2023 |
| HP            | Notebook                    | [60eebb0602](https://linux-hardware.org/?probe=60eebb0602) | Jun 18, 2023 |
| Dell          | Latitude 5420               | [f7c9224ef1](https://linux-hardware.org/?probe=f7c9224ef1) | Jun 17, 2023 |
| Dell          | Latitude 5420               | [f553a4e5e7](https://linux-hardware.org/?probe=f553a4e5e7) | Jun 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0d47dc3760](https://linux-hardware.org/?probe=0d47dc3760) | Jun 16, 2023 |
| STONE COMP... | NOTCHA-286                  | [9536ebc16b](https://linux-hardware.org/?probe=9536ebc16b) | Jun 16, 2023 |
| Dell          | Latitude E6400              | [7c59595887](https://linux-hardware.org/?probe=7c59595887) | Jun 16, 2023 |
| STONE COMP... | NOTCHA-286                  | [00a14ade70](https://linux-hardware.org/?probe=00a14ade70) | Jun 16, 2023 |
| Valve         | Jupiter                     | [29869b2464](https://linux-hardware.org/?probe=29869b2464) | Jun 15, 2023 |
| Valve         | Jupiter                     | [bdd96d41a7](https://linux-hardware.org/?probe=bdd96d41a7) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [a1c36c44b1](https://linux-hardware.org/?probe=a1c36c44b1) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [8d88084588](https://linux-hardware.org/?probe=8d88084588) | Jun 15, 2023 |
| Lenovo        | ThinkPad T490 20N20032US    | [3df7663e0d](https://linux-hardware.org/?probe=3df7663e0d) | Jun 15, 2023 |
| ASUSTek       | K52N                        | [eb2ec7cb3d](https://linux-hardware.org/?probe=eb2ec7cb3d) | Jun 15, 2023 |
| Lenovo        | G500s 20245                 | [8a04ec65f7](https://linux-hardware.org/?probe=8a04ec65f7) | Jun 15, 2023 |
| Acer          | Nitro AN515-44              | [7670492b40](https://linux-hardware.org/?probe=7670492b40) | Jun 15, 2023 |
| Dell          | Latitude 3190               | [2c8d7ef5b6](https://linux-hardware.org/?probe=2c8d7ef5b6) | Jun 12, 2023 |
| MSI           | GE62 6QC                    | [5581a5c589](https://linux-hardware.org/?probe=5581a5c589) | Jun 12, 2023 |
| Google        | Blorb                       | [0083999b8a](https://linux-hardware.org/?probe=0083999b8a) | Jun 12, 2023 |
| Google        | Blorb                       | [516c0548dc](https://linux-hardware.org/?probe=516c0548dc) | Jun 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [b88dfc7e5c](https://linux-hardware.org/?probe=b88dfc7e5c) | Jun 11, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [67867c022f](https://linux-hardware.org/?probe=67867c022f) | Jun 11, 2023 |
| Dell          | Precision 5520              | [bcbd324c4b](https://linux-hardware.org/?probe=bcbd324c4b) | Jun 11, 2023 |
| Dell          | Precision 5520              | [ab408edcbd](https://linux-hardware.org/?probe=ab408edcbd) | Jun 11, 2023 |
| HP            | Laptop 15-dw1xxx            | [bfde2cf63d](https://linux-hardware.org/?probe=bfde2cf63d) | Jun 10, 2023 |
| HP            | Laptop 15-dw1xxx            | [7c79725474](https://linux-hardware.org/?probe=7c79725474) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | [5e060b53c2](https://linux-hardware.org/?probe=5e060b53c2) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | [0d548e314b](https://linux-hardware.org/?probe=0d548e314b) | Jun 10, 2023 |
| Dell          | Inspiron 3583               | [2627421665](https://linux-hardware.org/?probe=2627421665) | Jun 09, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | [fb9e2f9fc8](https://linux-hardware.org/?probe=fb9e2f9fc8) | Jun 09, 2023 |
| Panasonic     | CF-53ASCZGFG                | [39e04925ee](https://linux-hardware.org/?probe=39e04925ee) | Jun 08, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [c98ac6e82c](https://linux-hardware.org/?probe=c98ac6e82c) | Jun 08, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [7879db73f8](https://linux-hardware.org/?probe=7879db73f8) | Jun 08, 2023 |
| Fujitsu       | CELSIUS H730                | [a1e397f4a7](https://linux-hardware.org/?probe=a1e397f4a7) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [c142d83ce5](https://linux-hardware.org/?probe=c142d83ce5) | Jun 07, 2023 |
| Toshiba       | Satellite L40               | [16c5f74991](https://linux-hardware.org/?probe=16c5f74991) | Jun 06, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [e56988bf8e](https://linux-hardware.org/?probe=e56988bf8e) | Jun 06, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [fc49284b9f](https://linux-hardware.org/?probe=fc49284b9f) | Jun 06, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [83982c1aa9](https://linux-hardware.org/?probe=83982c1aa9) | Jun 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | [38882f47af](https://linux-hardware.org/?probe=38882f47af) | Jun 05, 2023 |
| Dell          | Latitude 3190               | [fa8eba55f0](https://linux-hardware.org/?probe=fa8eba55f0) | Jun 05, 2023 |
| Acer          | Swift SF314-43              | [969354604a](https://linux-hardware.org/?probe=969354604a) | Jun 04, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [514b3788ed](https://linux-hardware.org/?probe=514b3788ed) | Jun 04, 2023 |
| Dell          | Latitude D620               | [0e1b7f4320](https://linux-hardware.org/?probe=0e1b7f4320) | Jun 03, 2023 |
| Acer          | Aspire A114-31              | [7a760e7ad6](https://linux-hardware.org/?probe=7a760e7ad6) | Jun 03, 2023 |
| Lenovo        | ThinkPad L490 20Q5002DMH    | [6d42b7647b](https://linux-hardware.org/?probe=6d42b7647b) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [fa4bd41f4b](https://linux-hardware.org/?probe=fa4bd41f4b) | Jun 02, 2023 |
| Lenovo        | B50-70 20384                | [5e3a2796a9](https://linux-hardware.org/?probe=5e3a2796a9) | Jun 01, 2023 |
| HP            | EliteBook 820 G2            | [c9409c532d](https://linux-hardware.org/?probe=c9409c532d) | Jun 01, 2023 |
| Toshiba       | Satellite L650              | [63eb6978fa](https://linux-hardware.org/?probe=63eb6978fa) | Jun 01, 2023 |
| Lenovo        | B51-80 80LM                 | [69429cb044](https://linux-hardware.org/?probe=69429cb044) | Jun 01, 2023 |
| HP            | EliteBook 840 G4            | [46ccbd2d62](https://linux-hardware.org/?probe=46ccbd2d62) | May 31, 2023 |
| HP            | EliteBook 840 G4            | [b90cb27f97](https://linux-hardware.org/?probe=b90cb27f97) | May 31, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [7fed965224](https://linux-hardware.org/?probe=7fed965224) | May 30, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [3b186c07a2](https://linux-hardware.org/?probe=3b186c07a2) | May 30, 2023 |
| Dell          | Latitude 3190               | [fe4a8422c8](https://linux-hardware.org/?probe=fe4a8422c8) | May 29, 2023 |
| Dell          | Latitude 7480               | [9eb2396796](https://linux-hardware.org/?probe=9eb2396796) | May 28, 2023 |
| Dell          | Vostro 1015                 | [c51af54d34](https://linux-hardware.org/?probe=c51af54d34) | May 28, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [c2408a1885](https://linux-hardware.org/?probe=c2408a1885) | May 28, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | [c8c8087ee8](https://linux-hardware.org/?probe=c8c8087ee8) | May 27, 2023 |
| ASUSTek       | X555LN                      | [8f16767017](https://linux-hardware.org/?probe=8f16767017) | May 26, 2023 |
| Dell          | Latitude E5440              | [4a5501c365](https://linux-hardware.org/?probe=4a5501c365) | May 26, 2023 |
| Notebook      | NV4xPZ                      | [750cb90d83](https://linux-hardware.org/?probe=750cb90d83) | May 26, 2023 |
| ASUSTek       | GL552VW                     | [0466edde83](https://linux-hardware.org/?probe=0466edde83) | May 25, 2023 |
| ASUSTek       | X551MA                      | [d72352c0dc](https://linux-hardware.org/?probe=d72352c0dc) | May 25, 2023 |
| HP            | EliteBook 840 G3            | [06333c9c97](https://linux-hardware.org/?probe=06333c9c97) | May 24, 2023 |
| Lenovo        | G500s 20245                 | [dd15a8197e](https://linux-hardware.org/?probe=dd15a8197e) | May 24, 2023 |
| Acer          | Aspire E5-571G              | [6531b22151](https://linux-hardware.org/?probe=6531b22151) | May 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [ba72bf9d52](https://linux-hardware.org/?probe=ba72bf9d52) | May 24, 2023 |
| Google        | Snappy                      | [8e9ad9e9d3](https://linux-hardware.org/?probe=8e9ad9e9d3) | May 24, 2023 |
| Lenovo        | Unknown                     | [e7148e7a18](https://linux-hardware.org/?probe=e7148e7a18) | May 23, 2023 |
| HP            | 530                         | [70600de142](https://linux-hardware.org/?probe=70600de142) | May 23, 2023 |
| HP            | EliteBook 840 G5            | [74a0ea4304](https://linux-hardware.org/?probe=74a0ea4304) | May 22, 2023 |
| Dell          | Latitude 3190               | [adf9fc9bdb](https://linux-hardware.org/?probe=adf9fc9bdb) | May 22, 2023 |
| ASUSTek       | K84L                        | [5f14f3b293](https://linux-hardware.org/?probe=5f14f3b293) | May 21, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [03b17bc271](https://linux-hardware.org/?probe=03b17bc271) | May 21, 2023 |
| HP            | Unknown                     | [8894bf0f31](https://linux-hardware.org/?probe=8894bf0f31) | May 21, 2023 |
| Valve         | Jupiter                     | [cf5c419d13](https://linux-hardware.org/?probe=cf5c419d13) | May 20, 2023 |
| Lenovo        | G580 20150                  | [87e60904b9](https://linux-hardware.org/?probe=87e60904b9) | May 20, 2023 |
| Lenovo        | G500s 20245                 | [fc125408b5](https://linux-hardware.org/?probe=fc125408b5) | May 20, 2023 |
| Lenovo        | G580 20150                  | [5acf485cbf](https://linux-hardware.org/?probe=5acf485cbf) | May 20, 2023 |
| Apple         | MacBookAir6,2               | [5a0f8e19ee](https://linux-hardware.org/?probe=5a0f8e19ee) | May 19, 2023 |
| Lenovo        | G500s 20245                 | [8c6b9dc52f](https://linux-hardware.org/?probe=8c6b9dc52f) | May 19, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [26e8deafbf](https://linux-hardware.org/?probe=26e8deafbf) | May 19, 2023 |
| MSI           | GL75 9SE                    | [7fd4d531c9](https://linux-hardware.org/?probe=7fd4d531c9) | May 18, 2023 |
| HP            | EliteBook 820 G2            | [200610da74](https://linux-hardware.org/?probe=200610da74) | May 17, 2023 |
| Google        | Snappy                      | [d13d8adaf4](https://linux-hardware.org/?probe=d13d8adaf4) | May 17, 2023 |
| Google        | Snappy                      | [0c095bb37a](https://linux-hardware.org/?probe=0c095bb37a) | May 17, 2023 |
| Dell          | Latitude 3190               | [1d867407a6](https://linux-hardware.org/?probe=1d867407a6) | May 15, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [3466945196](https://linux-hardware.org/?probe=3466945196) | May 15, 2023 |
| Lenovo        | B590 20206                  | [70b604bc30](https://linux-hardware.org/?probe=70b604bc30) | May 14, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5f508efff4](https://linux-hardware.org/?probe=5f508efff4) | May 14, 2023 |
| Lenovo        | B50-70 20384                | [1d3db7b456](https://linux-hardware.org/?probe=1d3db7b456) | May 14, 2023 |
| Fujitsu       | CELSIUS H760                | [5e6faf68dd](https://linux-hardware.org/?probe=5e6faf68dd) | May 14, 2023 |
| Lenovo        | B50-70 20384                | [9459f4eae8](https://linux-hardware.org/?probe=9459f4eae8) | May 14, 2023 |
| Fujitsu       | LIFEBOOK S752               | [97e9f91d90](https://linux-hardware.org/?probe=97e9f91d90) | May 14, 2023 |
| ASUSTek       | K53BR                       | [96a60a2970](https://linux-hardware.org/?probe=96a60a2970) | May 14, 2023 |
| Dell          | Latitude E5530 non-vPro     | [aa5dc9770e](https://linux-hardware.org/?probe=aa5dc9770e) | May 13, 2023 |
| Dell          | Latitude E5530 non-vPro     | [51c66f0f57](https://linux-hardware.org/?probe=51c66f0f57) | May 13, 2023 |
| Lenovo        | G50-30 80G0                 | [31d034ce6e](https://linux-hardware.org/?probe=31d034ce6e) | May 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [55abeba9a3](https://linux-hardware.org/?probe=55abeba9a3) | May 13, 2023 |
| Fujitsu       | CELSIUS H760                | [7bb1e2b54e](https://linux-hardware.org/?probe=7bb1e2b54e) | May 13, 2023 |
| Toshiba       | Satellite C55-A-1KZ         | [37c165fa30](https://linux-hardware.org/?probe=37c165fa30) | May 13, 2023 |
| Dell          | Precision 3571              | [9a20dccb42](https://linux-hardware.org/?probe=9a20dccb42) | May 13, 2023 |
| GPU Compan... | GWTN156-11                  | [afb2844cb4](https://linux-hardware.org/?probe=afb2844cb4) | May 13, 2023 |
| Samsung       | RF510/RF410/RF710           | [4820c25349](https://linux-hardware.org/?probe=4820c25349) | May 12, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [6950584e4c](https://linux-hardware.org/?probe=6950584e4c) | May 12, 2023 |
| HP            | ProBook 4535s               | [0d2f9561ce](https://linux-hardware.org/?probe=0d2f9561ce) | May 12, 2023 |
| Dell          | Latitude 7390               | [cbd8c5fdbe](https://linux-hardware.org/?probe=cbd8c5fdbe) | May 12, 2023 |
| Dell          | Latitude 7390               | [5677bfdac5](https://linux-hardware.org/?probe=5677bfdac5) | May 12, 2023 |
| Toshiba       | Satellite L40               | [9945f20a3a](https://linux-hardware.org/?probe=9945f20a3a) | May 11, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [4ca3ad7158](https://linux-hardware.org/?probe=4ca3ad7158) | May 11, 2023 |
| Valve         | Jupiter                     | [5bfb32e683](https://linux-hardware.org/?probe=5bfb32e683) | May 11, 2023 |
| HP            | EliteBook 745 G3            | [256ad0c4d8](https://linux-hardware.org/?probe=256ad0c4d8) | May 11, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | [8886b2b825](https://linux-hardware.org/?probe=8886b2b825) | May 10, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [d764690667](https://linux-hardware.org/?probe=d764690667) | May 10, 2023 |
| HP            | Laptop 15s-eq0xxx           | [58000b3a57](https://linux-hardware.org/?probe=58000b3a57) | May 09, 2023 |
| Fujitsu Si... | AMILO Pro Series V3525      | [6272f76b0b](https://linux-hardware.org/?probe=6272f76b0b) | May 09, 2023 |
| HP            | EliteBook 840 14 inch G9... | [a3e5adab46](https://linux-hardware.org/?probe=a3e5adab46) | May 08, 2023 |
| Fujitsu Si... | AMILO Pro Series V3525      | [e3cc11d5e4](https://linux-hardware.org/?probe=e3cc11d5e4) | May 08, 2023 |
| Dell          | Latitude 3190               | [fb4df1325b](https://linux-hardware.org/?probe=fb4df1325b) | May 08, 2023 |
| Valve         | Jupiter                     | [e6397e7f9f](https://linux-hardware.org/?probe=e6397e7f9f) | May 08, 2023 |
| HP            | 15                          | [162a4b16ae](https://linux-hardware.org/?probe=162a4b16ae) | May 08, 2023 |
| Dell          | Latitude 5520               | [4d8ef45cbc](https://linux-hardware.org/?probe=4d8ef45cbc) | May 07, 2023 |
| Acer          | TravelMate 6592             | [d655aad3c5](https://linux-hardware.org/?probe=d655aad3c5) | May 07, 2023 |
| Dell          | Latitude 5290               | [255da608b8](https://linux-hardware.org/?probe=255da608b8) | May 07, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | [3cf83f50f0](https://linux-hardware.org/?probe=3cf83f50f0) | May 07, 2023 |
| Toshiba       | Satellite L300D             | [0e2dfb1c74](https://linux-hardware.org/?probe=0e2dfb1c74) | May 06, 2023 |
| ASUSTek       | K75DE                       | [d99045be1c](https://linux-hardware.org/?probe=d99045be1c) | May 05, 2023 |
| Dell          | Inspiron 5770               | [c545869ec5](https://linux-hardware.org/?probe=c545869ec5) | May 05, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [51ae873492](https://linux-hardware.org/?probe=51ae873492) | May 04, 2023 |
| HP            | EliteBook 8540p             | [11b0a5baa1](https://linux-hardware.org/?probe=11b0a5baa1) | May 04, 2023 |
| Google        | Meep                        | [1e5e0e6673](https://linux-hardware.org/?probe=1e5e0e6673) | May 04, 2023 |
| Dell          | Latitude 5490               | [20c5ad2ee2](https://linux-hardware.org/?probe=20c5ad2ee2) | May 03, 2023 |
| Dell          | Latitude E6410              | [8830853258](https://linux-hardware.org/?probe=8830853258) | May 03, 2023 |
| Packard Be... | EasyNote TE69BM             | [fc905a42fb](https://linux-hardware.org/?probe=fc905a42fb) | May 03, 2023 |
| Lenovo        | G500s 20245                 | [560b69d616](https://linux-hardware.org/?probe=560b69d616) | May 03, 2023 |
| Packard Be... | EasyNote LJ65               | [795672236a](https://linux-hardware.org/?probe=795672236a) | May 02, 2023 |
| Packard Be... | EasyNote LJ65               | [77860cab79](https://linux-hardware.org/?probe=77860cab79) | May 02, 2023 |
| Dell          | Vostro 3550                 | [a644bc676e](https://linux-hardware.org/?probe=a644bc676e) | May 01, 2023 |
| HP            | Compaq 6910p                | [a697e756f5](https://linux-hardware.org/?probe=a697e756f5) | May 01, 2023 |
| Dell          | Latitude 3190               | [59c654b2ec](https://linux-hardware.org/?probe=59c654b2ec) | May 01, 2023 |
| Dell          | XPS 15 9500                 | [93fef964a7](https://linux-hardware.org/?probe=93fef964a7) | Apr 30, 2023 |
| Dell          | Latitude XT2                | [3cfd979c60](https://linux-hardware.org/?probe=3cfd979c60) | Apr 30, 2023 |
| Acer          | AO725                       | [03e5f661fb](https://linux-hardware.org/?probe=03e5f661fb) | Apr 30, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [408aa18a63](https://linux-hardware.org/?probe=408aa18a63) | Apr 30, 2023 |
| Lenovo        | IdeaPad L340-17API 81LY     | [44c60dcec2](https://linux-hardware.org/?probe=44c60dcec2) | Apr 30, 2023 |
| Dell          | Inspiron MXC061             | [2d1ab773dd](https://linux-hardware.org/?probe=2d1ab773dd) | Apr 30, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7c378d88a2](https://linux-hardware.org/?probe=7c378d88a2) | Apr 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f502c40867](https://linux-hardware.org/?probe=f502c40867) | Apr 29, 2023 |
| Acer          | Aspire V5-552G              | [07c58a5169](https://linux-hardware.org/?probe=07c58a5169) | Apr 29, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [a8adc86550](https://linux-hardware.org/?probe=a8adc86550) | Apr 28, 2023 |
| Acer          | Aspire VX5-591G             | [2461a8058f](https://linux-hardware.org/?probe=2461a8058f) | Apr 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [f1290d4846](https://linux-hardware.org/?probe=f1290d4846) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [2474e8e580](https://linux-hardware.org/?probe=2474e8e580) | Apr 27, 2023 |
| HP            | 255 G8 Notebook PC          | [adb8f367ea](https://linux-hardware.org/?probe=adb8f367ea) | Apr 27, 2023 |
| HP            | EliteBook 2560p             | [23b5cbfb33](https://linux-hardware.org/?probe=23b5cbfb33) | Apr 27, 2023 |
| Acer          | Aspire 7250                 | [8e8e082e3d](https://linux-hardware.org/?probe=8e8e082e3d) | Apr 26, 2023 |
| Acer          | Aspire 5737Z                | [121eda50b8](https://linux-hardware.org/?probe=121eda50b8) | Apr 26, 2023 |
| HP            | EliteBook 840 G2            | [a3065a1b59](https://linux-hardware.org/?probe=a3065a1b59) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d8088982c3](https://linux-hardware.org/?probe=d8088982c3) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [4cffa55fb1](https://linux-hardware.org/?probe=4cffa55fb1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | [e6380a2186](https://linux-hardware.org/?probe=e6380a2186) | Apr 26, 2023 |
| HP            | Laptop 15                   | [34a2ebf6a1](https://linux-hardware.org/?probe=34a2ebf6a1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | [872138980a](https://linux-hardware.org/?probe=872138980a) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2122bd37a5](https://linux-hardware.org/?probe=2122bd37a5) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [af7b14d259](https://linux-hardware.org/?probe=af7b14d259) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7fbd802154](https://linux-hardware.org/?probe=7fbd802154) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ffe6065419](https://linux-hardware.org/?probe=ffe6065419) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [94ddc76aae](https://linux-hardware.org/?probe=94ddc76aae) | Apr 26, 2023 |
| Lenovo        | ThinkPad X200 7459KM3       | [cbea785e27](https://linux-hardware.org/?probe=cbea785e27) | Apr 25, 2023 |
| Dell          | Latitude E5470              | [3eb401d939](https://linux-hardware.org/?probe=3eb401d939) | Apr 25, 2023 |
| Dell          | Latitude E5470              | [37fabb89aa](https://linux-hardware.org/?probe=37fabb89aa) | Apr 25, 2023 |
| Lenovo        | G700                        | [75ee4cf99d](https://linux-hardware.org/?probe=75ee4cf99d) | Apr 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [9649423c20](https://linux-hardware.org/?probe=9649423c20) | Apr 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [af486ae4ae](https://linux-hardware.org/?probe=af486ae4ae) | Apr 24, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [de3ad583ab](https://linux-hardware.org/?probe=de3ad583ab) | Apr 24, 2023 |
| Medion        | X681X                       | [d72837ad07](https://linux-hardware.org/?probe=d72837ad07) | Apr 24, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [78686e5784](https://linux-hardware.org/?probe=78686e5784) | Apr 24, 2023 |
| Dell          | Vostro 5402                 | [b6cb9c9140](https://linux-hardware.org/?probe=b6cb9c9140) | Apr 24, 2023 |
| Dell          | Latitude 3190               | [2c21a51932](https://linux-hardware.org/?probe=2c21a51932) | Apr 24, 2023 |
| Samsung       | R510/P510                   | [4b58936ad7](https://linux-hardware.org/?probe=4b58936ad7) | Apr 23, 2023 |
| Dell          | Inspiron 5559               | [e959cc70fa](https://linux-hardware.org/?probe=e959cc70fa) | Apr 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [18306b3af6](https://linux-hardware.org/?probe=18306b3af6) | Apr 23, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [bee909cfcd](https://linux-hardware.org/?probe=bee909cfcd) | Apr 23, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [c101faa12e](https://linux-hardware.org/?probe=c101faa12e) | Apr 23, 2023 |
| Lenovo        | Z51-70 80K6                 | [3d51a6183c](https://linux-hardware.org/?probe=3d51a6183c) | Apr 23, 2023 |
| Dell          | Precision 7550              | [31830a82c6](https://linux-hardware.org/?probe=31830a82c6) | Apr 22, 2023 |
| Dell          | Latitude D620               | [7b0c5ec6f2](https://linux-hardware.org/?probe=7b0c5ec6f2) | Apr 22, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [510237facd](https://linux-hardware.org/?probe=510237facd) | Apr 22, 2023 |
| Gigabyte      | AORUS 15P XD                | [22925aa0c9](https://linux-hardware.org/?probe=22925aa0c9) | Apr 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [c1139db413](https://linux-hardware.org/?probe=c1139db413) | Apr 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [3056a65306](https://linux-hardware.org/?probe=3056a65306) | Apr 22, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [87d3a8b29f](https://linux-hardware.org/?probe=87d3a8b29f) | Apr 20, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [b7f138b04c](https://linux-hardware.org/?probe=b7f138b04c) | Apr 20, 2023 |
| Dell          | Precision M6600             | [e71bf9e7bb](https://linux-hardware.org/?probe=e71bf9e7bb) | Apr 20, 2023 |
| ASUSTek       | K50IJ                       | [3b07dc847f](https://linux-hardware.org/?probe=3b07dc847f) | Apr 20, 2023 |
| MSI           | Creator Z17 A12UHST         | [1396746fba](https://linux-hardware.org/?probe=1396746fba) | Apr 20, 2023 |
| HP            | 255 G7 Notebook PC          | [b2f977f4a1](https://linux-hardware.org/?probe=b2f977f4a1) | Apr 19, 2023 |
| Acer          | Aspire A715-71G             | [83b48fff59](https://linux-hardware.org/?probe=83b48fff59) | Apr 19, 2023 |
| Dell          | Latitude 7410               | [36e2aea9ea](https://linux-hardware.org/?probe=36e2aea9ea) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [09a37b3301](https://linux-hardware.org/?probe=09a37b3301) | Apr 19, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [1548cc4309](https://linux-hardware.org/?probe=1548cc4309) | Apr 19, 2023 |
| Dell          | Precision M6800             | [b39d3f31df](https://linux-hardware.org/?probe=b39d3f31df) | Apr 18, 2023 |
| Lenovo        | Y50-70 20378                | [af6c719754](https://linux-hardware.org/?probe=af6c719754) | Apr 18, 2023 |
| Gigabyte      | G5 GE                       | [f1baab4be4](https://linux-hardware.org/?probe=f1baab4be4) | Apr 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [a0b6c23c0b](https://linux-hardware.org/?probe=a0b6c23c0b) | Apr 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [35ec02005f](https://linux-hardware.org/?probe=35ec02005f) | Apr 17, 2023 |
| Acer          | Swift SFA16-41              | [1232f86e3e](https://linux-hardware.org/?probe=1232f86e3e) | Apr 17, 2023 |
| Dell          | Latitude D830               | [3da091adc2](https://linux-hardware.org/?probe=3da091adc2) | Apr 17, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [7ca92cfada](https://linux-hardware.org/?probe=7ca92cfada) | Apr 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8SF1X0... | [d567c29052](https://linux-hardware.org/?probe=d567c29052) | Apr 17, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [c59c5c0cdf](https://linux-hardware.org/?probe=c59c5c0cdf) | Apr 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [391b43ba8c](https://linux-hardware.org/?probe=391b43ba8c) | Apr 16, 2023 |
| Dell          | Inspiron 5559               | [b74080b280](https://linux-hardware.org/?probe=b74080b280) | Apr 16, 2023 |
| Dell          | Latitude E6330              | [1a75476b96](https://linux-hardware.org/?probe=1a75476b96) | Apr 16, 2023 |
| Acer          | AO722                       | [af4e100c16](https://linux-hardware.org/?probe=af4e100c16) | Apr 15, 2023 |
| Kiano         | Elegance 14.2               | [34062f30df](https://linux-hardware.org/?probe=34062f30df) | Apr 15, 2023 |
| Acer          | Aspire 5336                 | [7613566248](https://linux-hardware.org/?probe=7613566248) | Apr 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [9206720811](https://linux-hardware.org/?probe=9206720811) | Apr 14, 2023 |
| Valve         | Jupiter                     | [c1558fbc72](https://linux-hardware.org/?probe=c1558fbc72) | Apr 14, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | [9cb53e6d6f](https://linux-hardware.org/?probe=9cb53e6d6f) | Apr 13, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [9341670151](https://linux-hardware.org/?probe=9341670151) | Apr 13, 2023 |
| Lenovo        | ThinkPad X220 4291AY8       | [b2bc70473d](https://linux-hardware.org/?probe=b2bc70473d) | Apr 13, 2023 |
| Fujitsu Si... | AMILO PRO V3515             | [be2d8594c3](https://linux-hardware.org/?probe=be2d8594c3) | Apr 13, 2023 |
| Dell          | Latitude E6230              | [a7cce7ebde](https://linux-hardware.org/?probe=a7cce7ebde) | Apr 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460C... | [f1999ee14e](https://linux-hardware.org/?probe=f1999ee14e) | Apr 11, 2023 |
| Dell          | Latitude 7390               | [9361f06955](https://linux-hardware.org/?probe=9361f06955) | Apr 11, 2023 |
| Lenovo        | ThinkPad T480 20L5S12H00    | [c550410c5b](https://linux-hardware.org/?probe=c550410c5b) | Apr 11, 2023 |
| HP            | Pavilion dv7                | [000c77d7d5](https://linux-hardware.org/?probe=000c77d7d5) | Apr 10, 2023 |
| HP            | Pavilion dv7                | [08e5108cda](https://linux-hardware.org/?probe=08e5108cda) | Apr 10, 2023 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | [90d7e2bb21](https://linux-hardware.org/?probe=90d7e2bb21) | Apr 09, 2023 |
| Lenovo        | ThinkPad X220 4291LR6       | [ea86227d59](https://linux-hardware.org/?probe=ea86227d59) | Apr 09, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Poland/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 352       | 9.56%   |
| Ubuntu 22.04                 | 213       | 5.78%   |
| OpenMandriva 4.2             | 187       | 5.08%   |
| Ubuntu 18.04                 | 166       | 4.51%   |
| OpenMandriva 4.3             | 111       | 3.01%   |
| Debian 11                    | 101       | 2.74%   |
| Arch Rolling                 | 91        | 2.47%   |
| OpenMandriva 23.03           | 67        | 1.82%   |
| Linux Mint 21.1              | 57        | 1.55%   |
| OpenMandriva 23.01           | 56        | 1.52%   |
| Zorin 16                     | 50        | 1.36%   |
| ROSA R10                     | 50        | 1.36%   |
| Linux Mint 20.3              | 47        | 1.28%   |
| Fedora 38                    | 46        | 1.25%   |
| Linux Mint 20.1              | 42        | 1.14%   |
| Arch                         | 42        | 1.14%   |
| OpenMandriva 23.08           | 41        | 1.11%   |
| Fedora 37                    | 41        | 1.11%   |
| Debian 12                    | 41        | 1.11%   |
| KDE neon 20.04               | 40        | 1.09%   |
| ROSA R9                      | 39        | 1.06%   |
| ROSA R11.1                   | 39        | 1.06%   |
| Pop!_OS 22.04                | 38        | 1.03%   |
| Manjaro                      | 38        | 1.03%   |
| Fedora 39                    | 36        | 0.98%   |
| Fedora 36                    | 36        | 0.98%   |
| Linux Mint 20.2              | 34        | 0.92%   |
| Ubuntu 20.10                 | 33        | 0.9%    |
| Ubuntu 21.04                 | 32        | 0.87%   |
| Linux Mint 19.3              | 32        | 0.87%   |
| Ubuntu 22.10                 | 31        | 0.84%   |
| Linux Mint 21.2              | 30        | 0.81%   |
| ROSA R11                     | 29        | 0.79%   |
| Linux Mint 21                | 29        | 0.79%   |
| openSUSE Tumbleweed-XXXXXXXX | 28        | 0.76%   |
| Zorin 15                     | 27        | 0.73%   |
| Ubuntu 19.10                 | 27        | 0.73%   |
| Linux Mint 20                | 27        | 0.73%   |
| Ubuntu 21.10                 | 26        | 0.71%   |
| Xubuntu 20.04                | 25        | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 901       | 26.15%  |
| OpenMandriva  | 491       | 14.25%  |
| Linux Mint    | 293       | 8.51%   |
| Fedora        | 258       | 7.49%   |
| ROSA          | 192       | 5.57%   |
| Debian        | 188       | 5.46%   |
| Arch          | 129       | 3.74%   |
| Manjaro       | 125       | 3.63%   |
| Pop!_OS       | 91        | 2.64%   |
| Zorin         | 85        | 2.47%   |
| Kubuntu       | 67        | 1.94%   |
| KDE neon      | 59        | 1.71%   |
| Xubuntu       | 53        | 1.54%   |
| Kali          | 45        | 1.31%   |
| SteamOS       | 36        | 1.04%   |
| openSUSE      | 35        | 1.02%   |
| Lubuntu       | 29        | 0.84%   |
| Elementary    | 27        | 0.78%   |
| LMDE          | 25        | 0.73%   |
| ArcoLinux     | 25        | 0.73%   |
| Gentoo        | 24        | 0.7%    |
| Endless       | 24        | 0.7%    |
| EndeavourOS   | 23        | 0.67%   |
| Xero          | 14        | 0.41%   |
| Nobara        | 14        | 0.41%   |
| MX            | 13        | 0.38%   |
| Garuda Linux  | 13        | 0.38%   |
| Clear Linux   | 13        | 0.38%   |
| Ubuntu Unity  | 11        | 0.32%   |
| Ubuntu MATE   | 11        | 0.32%   |
| Ubuntu Budgie | 9         | 0.26%   |
| Peppermint    | 8         | 0.23%   |
| LinuxFX       | 8         | 0.23%   |
| BlackPanther  | 7         | 0.2%    |
| EuroLinux     | 6         | 0.17%   |
| Parrot        | 5         | 0.15%   |
| NixOS         | 5         | 0.15%   |
| CentOS        | 5         | 0.15%   |
| Artix         | 5         | 0.15%   |
| Sparky        | 4         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 177       | 4.39%   |
| 5.16.7-desktop-1omv4003         | 108       | 2.68%   |
| 6.2.6-desktop-1omv2390          | 65        | 1.61%   |
| 6.1.1-desktop-1omv2290          | 53        | 1.31%   |
| 5.4.0-42-generic                | 44        | 1.09%   |
| 5.15.0-56-generic               | 43        | 1.07%   |
| 6.4.11-desktop-1omv2390         | 38        | 0.94%   |
| 6.6.2-desktop-1omv2390          | 29        | 0.72%   |
| 5.15.0-58-generic               | 27        | 0.67%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 26        | 0.64%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 24        | 0.6%    |
| 5.15.0-43-generic               | 23        | 0.57%   |
| 5.4.0-52-generic                | 22        | 0.55%   |
| 5.4.0-48-generic                | 22        | 0.55%   |
| 5.19.0-35-generic               | 21        | 0.52%   |
| 5.15.0-52-generic               | 21        | 0.52%   |
| 5.4.0-29-generic                | 20        | 0.5%    |
| 5.4.0-58-generic                | 19        | 0.47%   |
| 5.4.0-26-generic                | 19        | 0.47%   |
| 5.3.0-46-generic                | 18        | 0.45%   |
| 5.19.0-32-generic               | 18        | 0.45%   |
| 5.15.0-53-generic               | 18        | 0.45%   |
| 5.4.0-33-generic                | 17        | 0.42%   |
| 5.11.0-37-generic               | 17        | 0.42%   |
| 5.0.0-37-generic                | 17        | 0.42%   |
| 5.8.0-43-generic                | 16        | 0.4%    |
| 5.4.0-54-generic                | 16        | 0.4%    |
| 5.15.0-48-generic               | 16        | 0.4%    |
| 4.15.0-desktop-45.1rosa-x86_64  | 16        | 0.4%    |
| 4.1.34-nrj-desktop-2rosa-x86_64 | 16        | 0.4%    |
| 5.15.0-91-generic               | 15        | 0.37%   |
| 6.1.0-13-amd64                  | 14        | 0.35%   |
| 5.4.0-40-generic                | 14        | 0.35%   |
| 5.4.0-37-generic                | 14        | 0.35%   |
| 5.3.0-40-generic                | 14        | 0.35%   |
| 5.11.0-43-generic               | 14        | 0.35%   |
| 6.2.0-26-generic                | 13        | 0.32%   |
| 5.4.0-91-generic                | 13        | 0.32%   |
| 5.3.0-42-generic                | 13        | 0.32%   |
| 5.15.0-60-generic               | 13        | 0.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 451       | 11.77%  |
| 5.15.0  | 320       | 8.35%   |
| 5.10.14 | 178       | 4.65%   |
| 4.15.0  | 151       | 3.94%   |
| 5.11.0  | 145       | 3.78%   |
| 5.8.0   | 129       | 3.37%   |
| 5.13.0  | 126       | 3.29%   |
| 5.10.0  | 120       | 3.13%   |
| 5.16.7  | 109       | 2.84%   |
| 5.19.0  | 108       | 2.82%   |
| 5.3.0   | 103       | 2.69%   |
| 6.2.0   | 87        | 2.27%   |
| 6.2.6   | 80        | 2.09%   |
| 5.0.0   | 61        | 1.59%   |
| 6.1.0   | 60        | 1.57%   |
| 4.18.0  | 59        | 1.54%   |
| 6.1.1   | 54        | 1.41%   |
| 6.4.11  | 41        | 1.07%   |
| 6.5.0   | 36        | 0.94%   |
| 4.9.20  | 35        | 0.91%   |
| 6.6.2   | 33        | 0.86%   |
| 5.14.0  | 32        | 0.84%   |
| 4.9.60  | 32        | 0.84%   |
| 4.19.0  | 31        | 0.81%   |
| 4.1.34  | 22        | 0.57%   |
| 6.0.0   | 18        | 0.47%   |
| 5.11.12 | 14        | 0.37%   |
| 4.1.38  | 14        | 0.37%   |
| 6.6.8   | 12        | 0.31%   |
| 6.5.5   | 12        | 0.31%   |
| 5.4.32  | 12        | 0.31%   |
| 5.17.0  | 12        | 0.31%   |
| 6.0.7   | 11        | 0.29%   |
| 5.9.0   | 11        | 0.29%   |
| 5.17.5  | 11        | 0.29%   |
| 6.6.9   | 10        | 0.26%   |
| 6.6.7   | 10        | 0.26%   |
| 6.1.52  | 10        | 0.26%   |
| 6.5.9   | 9         | 0.23%   |
| 6.5.6   | 9         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 512       | 13.64%  |
| 5.15    | 387       | 10.31%  |
| 5.10    | 352       | 9.38%   |
| 6.2     | 220       | 5.86%   |
| 6.1     | 196       | 5.22%   |
| 5.11    | 183       | 4.88%   |
| 5.16    | 164       | 4.37%   |
| 5.8     | 160       | 4.26%   |
| 4.15    | 151       | 4.02%   |
| 5.19    | 144       | 3.84%   |
| 5.13    | 143       | 3.81%   |
| 5.3     | 116       | 3.09%   |
| 4.9     | 101       | 2.69%   |
| 6.5     | 95        | 2.53%   |
| 6.6     | 90        | 2.4%    |
| 6.4     | 79        | 2.1%    |
| 6.0     | 74        | 1.97%   |
| 5.14    | 67        | 1.79%   |
| 5.0     | 67        | 1.79%   |
| 4.18    | 62        | 1.65%   |
| 5.17    | 51        | 1.36%   |
| 5.9     | 42        | 1.12%   |
| 5.6     | 42        | 1.12%   |
| 6.3     | 40        | 1.07%   |
| 5.18    | 40        | 1.07%   |
| 4.19    | 37        | 0.99%   |
| 4.1     | 35        | 0.93%   |
| 5.12    | 25        | 0.67%   |
| 5.5     | 23        | 0.61%   |
| 5.7     | 20        | 0.53%   |
| 4.4     | 8         | 0.21%   |
| 5.1     | 6         | 0.16%   |
| 5.2     | 4         | 0.11%   |
| 3.10    | 4         | 0.11%   |
| 6.7     | 3         | 0.08%   |
| 4.20    | 2         | 0.05%   |
| 4.13    | 2         | 0.05%   |
| 4.10    | 2         | 0.05%   |
| 4.17    | 1         | 0.03%   |
| 4.14    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 3186      | 96.55%  |
| i686    | 113       | 3.42%   |
| aarch64 | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 1303      | 37.55%  |
| KDE5             | 907       | 26.14%  |
| Unknown          | 269       | 7.75%   |
| XFCE             | 242       | 6.97%   |
| X-Cinnamon       | 219       | 6.31%   |
| KDE4             | 99        | 2.85%   |
| MATE             | 79        | 2.28%   |
| KDE              | 72        | 2.07%   |
| LXQt             | 60        | 1.73%   |
| Cinnamon         | 46        | 1.33%   |
| LXDE             | 38        | 1.1%    |
| Pantheon         | 26        | 0.75%   |
| i3               | 20        | 0.58%   |
| Budgie           | 17        | 0.49%   |
| Unity            | 13        | 0.37%   |
| GNOME Flashback  | 9         | 0.26%   |
| Deepin           | 9         | 0.26%   |
| Hyprland         | 7         | 0.2%    |
| sway             | 5         | 0.14%   |
| awesome          | 4         | 0.12%   |
| lightdm-xsession | 3         | 0.09%   |
| GNOME Classic    | 3         | 0.09%   |
| trinity          | 2         | 0.06%   |
| qtile            | 2         | 0.06%   |
| icewm            | 2         | 0.06%   |
| GNUstep          | 2         | 0.06%   |
| fluxbox          | 2         | 0.06%   |
| DWM              | 2         | 0.06%   |
| stumpwm          | 1         | 0.03%   |
| ratflow          | 1         | 0.03%   |
| qt5ct            | 1         | 0.03%   |
| openbox          | 1         | 0.03%   |
| MakuluGameR      | 1         | 0.03%   |
| gamescope        | 1         | 0.03%   |
| Endless:GNOME    | 1         | 0.03%   |
| BunsenLabs       | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 2541      | 74.36%  |
| Wayland     | 702       | 20.54%  |
| Unknown     | 136       | 3.98%   |
| Tty         | 37        | 1.08%   |
| Unspecified | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1301      | 37.68%  |
| SDDM    | 838       | 24.27%  |
| GDM     | 397       | 11.5%   |
| GDM3    | 373       | 10.8%   |
| LightDM | 332       | 9.61%   |
| KDM     | 101       | 2.92%   |
| TDM     | 95        | 2.75%   |
| XDM     | 6         | 0.17%   |
| Ly      | 3         | 0.09%   |
| NODM    | 2         | 0.06%   |
| SU      | 1         | 0.03%   |
| SLIMSKI | 1         | 0.03%   |
| SLiM    | 1         | 0.03%   |
| MDM     | 1         | 0.03%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| pl_PL       | 1815      | 53.24%  |
| en_US       | 966       | 28.34%  |
| Unknown     | 375       | 11%     |
| en_GB       | 90        | 2.64%   |
| C           | 70        | 2.05%   |
| ru_RU       | 27        | 0.79%   |
| uk_UA       | 9         | 0.26%   |
| szl_PL      | 9         | 0.26%   |
| ru_UA       | 7         | 0.21%   |
| de_DE       | 7         | 0.21%   |
| en_IE       | 4         | 0.12%   |
| fr_FR       | 3         | 0.09%   |
| en_DK       | 3         | 0.09%   |
| POSIX       | 2         | 0.06%   |
| nl_NL       | 2         | 0.06%   |
| it_IT       | 2         | 0.06%   |
| hu_HU       | 2         | 0.06%   |
| es_ES       | 2         | 0.06%   |
| C.UTF8      | 2         | 0.06%   |
| sk_SK       | 1         | 0.03%   |
| es_AR       | 1         | 0.03%   |
| en_US.UTF.8 | 1         | 0.03%   |
| en_US.utf-8 | 1         | 0.03%   |
| en_IN       | 1         | 0.03%   |
| en_CA       | 1         | 0.03%   |
| en_AU       | 1         | 0.03%   |
| en_AG       | 1         | 0.03%   |
| Default     | 1         | 0.03%   |
| be_BY       | 1         | 0.03%   |
| af_ZA       | 1         | 0.03%   |
| aa_DJ       | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1691      | 50.09%  |
| BIOS | 1685      | 49.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 2298      | 67.09%  |
| Overlay  | 435       | 12.7%   |
| Btrfs    | 353       | 10.31%  |
| Unknown  | 173       | 5.05%   |
| Tmpfs    | 71        | 2.07%   |
| Xfs      | 49        | 1.43%   |
| Zfs      | 24        | 0.7%    |
| F2fs     | 9         | 0.26%   |
| Rootfs   | 3         | 0.09%   |
| Ext3     | 3         | 0.09%   |
| Ext2     | 3         | 0.09%   |
| Bcachefs | 2         | 0.06%   |
| XXXXX    | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1434      | 42.18%  |
| GPT     | 1425      | 41.91%  |
| MBR     | 541       | 15.91%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2863      | 84.83%  |
| Yes       | 512       | 15.17%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2274      | 67.74%  |
| Yes       | 1083      | 32.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 863       | 26.19%  |
| Dell                | 686       | 20.82%  |
| Hewlett-Packard     | 507       | 15.39%  |
| ASUSTek Computer    | 376       | 11.41%  |
| Acer                | 207       | 6.28%   |
| Toshiba             | 90        | 2.73%   |
| Samsung Electronics | 89        | 2.7%    |
| MSI                 | 72        | 2.19%   |
| HUAWEI              | 40        | 1.21%   |
| Sony                | 37        | 1.12%   |
| Apple               | 34        | 1.03%   |
| Valve               | 32        | 0.97%   |
| Google              | 28        | 0.85%   |
| Fujitsu             | 28        | 0.85%   |
| Fujitsu Siemens     | 22        | 0.67%   |
| Packard Bell        | 16        | 0.49%   |
| Notebook            | 16        | 0.49%   |
| Kiano               | 12        | 0.36%   |
| Medion              | 11        | 0.33%   |
| eMachines           | 11        | 0.33%   |
| Timi                | 10        | 0.3%    |
| Gigabyte Technology | 8         | 0.24%   |
| Unknown             | 8         | 0.24%   |
| mPTech              | 6         | 0.18%   |
| Kruger&Matz         | 4         | 0.12%   |
| GPU Company         | 4         | 0.12%   |
| Clevo               | 4         | 0.12%   |
| Chuwi               | 4         | 0.12%   |
| Alienware           | 4         | 0.12%   |
| TUXEDO              | 3         | 0.09%   |
| TrekStor            | 3         | 0.09%   |
| Teclast             | 3         | 0.09%   |
| Panasonic           | 3         | 0.09%   |
| XIAOMI              | 2         | 0.06%   |
| System76            | 2         | 0.06%   |
| STONE COMPUTERS     | 2         | 0.06%   |
| Star Labs           | 2         | 0.06%   |
| Schenker            | 2         | 0.06%   |
| Razer               | 2         | 0.06%   |
| Monster             | 2         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Dell Inspiron 3451                  | 31        | 0.94%   |
| Unknown                             | 31        | 0.94%   |
| Valve Jupiter                       | 30        | 0.91%   |
| Dell Latitude E6400                 | 19        | 0.58%   |
| Dell Latitude E6540                 | 15        | 0.46%   |
| Lenovo G50-30 80G0                  | 14        | 0.42%   |
| HP Pavilion dv7                     | 13        | 0.39%   |
| Dell Latitude E6430                 | 13        | 0.39%   |
| ASUS X555LJ                         | 13        | 0.39%   |
| Dell Latitude E7440                 | 12        | 0.36%   |
| Dell Latitude D630                  | 12        | 0.36%   |
| Dell Latitude 5490                  | 12        | 0.36%   |
| Dell Latitude 5480                  | 12        | 0.36%   |
| Lenovo G580 20150                   | 11        | 0.33%   |
| Lenovo Legion Y530-15ICH 81FV       | 10        | 0.3%    |
| Lenovo G510 20238                   | 10        | 0.3%    |
| HP Notebook                         | 10        | 0.3%    |
| Dell Latitude E6420                 | 10        | 0.3%    |
| Dell Latitude E6330                 | 10        | 0.3%    |
| HP Pavilion Gaming Laptop 15-ec1xxx | 9         | 0.27%   |
| HP Pavilion dv6                     | 9         | 0.27%   |
| HP 15                               | 9         | 0.27%   |
| Dell Latitude E6440                 | 9         | 0.27%   |
| Dell Latitude E5430 non-vPro        | 9         | 0.27%   |
| Dell Latitude 5420                  | 9         | 0.27%   |
| Lenovo Legion Y540-15IRH 81SX       | 8         | 0.24%   |
| Lenovo IdeaPad Y700-15ISK 80NV      | 8         | 0.24%   |
| Lenovo G50-80 80E5                  | 8         | 0.24%   |
| HP Laptop 15-db1xxx                 | 8         | 0.24%   |
| HP 250 G6 Notebook PC               | 8         | 0.24%   |
| Dell Latitude E7450                 | 8         | 0.24%   |
| Dell Latitude 5511                  | 8         | 0.24%   |
| Toshiba Satellite A300              | 7         | 0.21%   |
| Samsung 550P5C/550P7C               | 7         | 0.21%   |
| Lenovo Z51-70 80K6                  | 7         | 0.21%   |
| Lenovo Legion 5 15ARH05 82B5        | 7         | 0.21%   |
| Lenovo IdeaPad 100-15IBD 80QQ       | 7         | 0.21%   |
| HUAWEI HVY-WXX9                     | 7         | 0.21%   |
| HP EliteBook 840 G3                 | 7         | 0.21%   |
| HP EliteBook 6930p                  | 7         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 390       | 11.84%  |
| Dell Latitude         | 364       | 11.05%  |
| Lenovo IdeaPad        | 173       | 5.25%   |
| Dell Inspiron         | 171       | 5.19%   |
| Acer Aspire           | 129       | 3.92%   |
| HP EliteBook          | 115       | 3.49%   |
| HP Pavilion           | 107       | 3.25%   |
| Toshiba Satellite     | 74        | 2.25%   |
| HP ProBook            | 73        | 2.22%   |
| Lenovo Legion         | 65        | 1.97%   |
| Dell Precision        | 47        | 1.43%   |
| ASUS VivoBook         | 47        | 1.43%   |
| HP Laptop             | 42        | 1.27%   |
| Dell XPS              | 35        | 1.06%   |
| Dell Vostro           | 34        | 1.03%   |
| Unknown               | 31        | 0.94%   |
| Valve Jupiter         | 30        | 0.91%   |
| ASUS ASUS             | 29        | 0.88%   |
| HP Compaq             | 27        | 0.82%   |
| Fujitsu LIFEBOOK      | 24        | 0.73%   |
| HP 250                | 23        | 0.7%    |
| ASUS TUF              | 21        | 0.64%   |
| ASUS ROG              | 20        | 0.61%   |
| Lenovo ThinkBook      | 19        | 0.58%   |
| HP ZBook              | 19        | 0.58%   |
| Acer Extensa          | 17        | 0.52%   |
| Packard Bell EasyNote | 16        | 0.49%   |
| ASUS Zenbook          | 16        | 0.49%   |
| Acer Nitro            | 16        | 0.49%   |
| Lenovo Yoga           | 14        | 0.42%   |
| Lenovo G50-30         | 14        | 0.42%   |
| Lenovo G580           | 13        | 0.39%   |
| HP OMEN               | 13        | 0.39%   |
| ASUS X555LJ           | 13        | 0.39%   |
| Acer TravelMate       | 13        | 0.39%   |
| Acer Swift            | 13        | 0.39%   |
| HP 255                | 12        | 0.36%   |
| Lenovo G510           | 10        | 0.3%    |
| Lenovo G50-80         | 10        | 0.3%    |
| HP Notebook           | 10        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 274       | 8.32%   |
| 2019    | 271       | 8.22%   |
| 2020    | 270       | 8.19%   |
| 2013    | 268       | 8.13%   |
| 2011    | 258       | 7.83%   |
| 2018    | 230       | 6.98%   |
| 2014    | 206       | 6.25%   |
| 2008    | 204       | 6.19%   |
| 2021    | 198       | 6.01%   |
| 2015    | 194       | 5.89%   |
| 2017    | 178       | 5.4%    |
| 2010    | 170       | 5.16%   |
| 2016    | 144       | 4.37%   |
| 2007    | 114       | 3.46%   |
| 2022    | 113       | 3.43%   |
| 2009    | 105       | 3.19%   |
| 2023    | 54        | 1.64%   |
| 2006    | 37        | 1.12%   |
| 2005    | 3         | 0.09%   |
| 2004    | 2         | 0.06%   |
| Unknown | 2         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3295      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3043      | 91.57%  |
| Enabled  | 280       | 8.43%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3264      | 99.06%  |
| Yes  | 31        | 0.94%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 820       | 24.5%   |
| 3.01-4.0    | 795       | 23.75%  |
| 8.01-16.0   | 567       | 16.94%  |
| 16.01-24.0  | 550       | 16.43%  |
| 32.01-64.0  | 287       | 8.57%   |
| 1.01-2.0    | 135       | 4.03%   |
| 2.01-3.0    | 98        | 2.93%   |
| 24.01-32.0  | 39        | 1.17%   |
| 64.01-256.0 | 33        | 0.99%   |
| 0.51-1.0    | 23        | 0.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1306      | 35.35%  |
| 2.01-3.0   | 846       | 22.9%   |
| 4.01-8.0   | 554       | 14.99%  |
| 3.01-4.0   | 476       | 12.88%  |
| 0.51-1.0   | 283       | 7.66%   |
| 8.01-16.0  | 168       | 4.55%   |
| 0.01-0.5   | 33        | 0.89%   |
| 16.01-24.0 | 20        | 0.54%   |
| 24.01-32.0 | 9         | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2457      | 72.67%  |
| 2      | 774       | 22.89%  |
| 3      | 91        | 2.69%   |
| 0      | 44        | 1.3%    |
| 4      | 12        | 0.35%   |
| 5      | 3         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2030      | 61.03%  |
| Yes       | 1296      | 38.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2811      | 84.92%  |
| No        | 499       | 15.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3248      | 98.48%  |
| No        | 50        | 1.52%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2573      | 76.76%  |
| No        | 779       | 23.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Poland  | 3295      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Warsaw                 | 788       | 21.97%  |
| Krakow                 | 279       | 7.78%   |
| Wroclaw                | 210       | 5.86%   |
| Poznan                 | 207       | 5.77%   |
| Lodz                   | 127       | 3.54%   |
| Gdansk                 | 124       | 3.46%   |
| Katowice               | 92        | 2.57%   |
| Lublin                 | 52        | 1.45%   |
| Szczecin               | 43        | 1.2%    |
| Gdynia                 | 43        | 1.2%    |
| Bydgoszcz              | 30        | 0.84%   |
| Bialystok              | 30        | 0.84%   |
| Gliwice                | 29        | 0.81%   |
| Rzeszów               | 26        | 0.73%   |
| Częstochowa           | 26        | 0.73%   |
| Torun                  | 24        | 0.67%   |
| Ruda Śląska          | 24        | 0.67%   |
| Zabrze                 | 21        | 0.59%   |
| Elblag                 | 20        | 0.56%   |
| Bytom                  | 19        | 0.53%   |
| Płock                 | 18        | 0.5%    |
| Olsztyn                | 18        | 0.5%    |
| Kielce                 | 18        | 0.5%    |
| Sosnowiec              | 16        | 0.45%   |
| Opole                  | 16        | 0.45%   |
| Chorzów               | 14        | 0.39%   |
| Tarnów                | 12        | 0.33%   |
| Bielsko-Biala          | 12        | 0.33%   |
| Siemianowice Śląskie | 11        | 0.31%   |
| Rybnik                 | 11        | 0.31%   |
| Blizniew               | 11        | 0.31%   |
| Tarnowskie Gory        | 10        | 0.28%   |
| Pruszków              | 10        | 0.28%   |
| Kalisz                 | 10        | 0.28%   |
| Chorzele               | 10        | 0.28%   |
| Zielona Góra          | 9         | 0.25%   |
| Tychy                  | 9         | 0.25%   |
| Skierniewice           | 9         | 0.25%   |
| Piaseczno              | 9         | 0.25%   |
| Wejherowo              | 8         | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 606       | 805    | 14.64%  |
| Seagate                     | 456       | 566    | 11.02%  |
| WDC                         | 419       | 519    | 10.12%  |
| Toshiba                     | 258       | 316    | 6.23%   |
| GOODRAM                     | 257       | 328    | 6.21%   |
| Unknown                     | 208       | 263    | 5.03%   |
| SanDisk                     | 192       | 244    | 4.64%   |
| SK hynix                    | 159       | 198    | 3.84%   |
| Hitachi                     | 157       | 183    | 3.79%   |
| A-DATA Technology           | 151       | 181    | 3.65%   |
| Intel                       | 145       | 193    | 3.5%    |
| Kingston                    | 144       | 201    | 3.48%   |
| Crucial                     | 137       | 212    | 3.31%   |
| Micron Technology           | 109       | 138    | 2.63%   |
| HGST                        | 81        | 99     | 1.96%   |
| KIOXIA                      | 51        | 56     | 1.23%   |
| Patriot                     | 37        | 46     | 0.89%   |
| SPCC                        | 35        | 41     | 0.85%   |
| PNY                         | 32        | 34     | 0.77%   |
| Plextor                     | 28        | 41     | 0.68%   |
| Phison Electronics          | 24        | 24     | 0.58%   |
| Fujitsu                     | 24        | 26     | 0.58%   |
| LITEON                      | 21        | 25     | 0.51%   |
| Transcend                   | 20        | 24     | 0.48%   |
| Phison                      | 19        | 25     | 0.46%   |
| China                       | 19        | 26     | 0.46%   |
| LITEONIT                    | 16        | 18     | 0.39%   |
| Unknown                     | 16        | 20     | 0.39%   |
| Silicon Motion              | 15        | 19     | 0.36%   |
| Apple                       | 14        | 18     | 0.34%   |
| Apacer                      | 14        | 25     | 0.34%   |
| KIOXIA-EXCERIA              | 13        | 15     | 0.31%   |
| Kingston Technology Company | 13        | 13     | 0.31%   |
| ADATA Technology            | 12        | 17     | 0.29%   |
| Lexar                       | 11        | 11     | 0.27%   |
| Lenovo                      | 10        | 12     | 0.24%   |
| JMicron Technology          | 9         | 9      | 0.22%   |
| OCZ                         | 8         | 8      | 0.19%   |
| Micron/Crucial Technology   | 8         | 10     | 0.19%   |
| Gigabyte Technology         | 8         | 9      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB                    | 60        | 1.4%    |
| Seagate ST1000LM035-1RK172 1TB                     | 50        | 1.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 49        | 1.14%   |
| Unknown MMC Card  32GB                             | 35        | 0.82%   |
| GOODRAM SSDPR-CX400-256-G2 256GB                   | 35        | 0.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 34        | 0.79%   |
| Crucial CT500MX500SSD1 500GB                       | 28        | 0.65%   |
| Seagate ST9500325AS 500GB                          | 27        | 0.63%   |
| Unknown MMC Card  64GB                             | 25        | 0.58%   |
| Toshiba MQ01ABD100 1TB                             | 25        | 0.58%   |
| Intel NVMe SSD Drive 512GB                         | 25        | 0.58%   |
| HGST HTS721010A9E630 1TB                           | 24        | 0.56%   |
| Kingston SA400S37240G 240GB SSD                    | 23        | 0.54%   |
| GOODRAM SSD 120GB                                  | 23        | 0.54%   |
| Toshiba MQ01ABF050 500GB                           | 22        | 0.51%   |
| Samsung NVMe SSD Drive 512GB                       | 21        | 0.49%   |
| SanDisk NVMe SSD Drive 512GB                       | 20        | 0.47%   |
| Samsung SSD 850 EVO 250GB                          | 20        | 0.47%   |
| GOODRAM SSD 240GB                                  | 20        | 0.47%   |
| Crucial CT1000MX500SSD1 1TB                        | 20        | 0.47%   |
| Unknown MMC Card  128GB                            | 19        | 0.44%   |
| Samsung SSD 860 EVO 500GB                          | 19        | 0.44%   |
| Intel SSDPEKNW512G8H 512GB                         | 19        | 0.44%   |
| GOODRAM SSDPR-CX400-512-G2 512GB                   | 19        | 0.44%   |
| Samsung SSD 980 1TB                                | 18        | 0.42%   |
| Seagate Expansion 1TB                              | 17        | 0.4%    |
| Crucial CT240BX500SSD1 240GB                       | 17        | 0.4%    |
| HGST HTS725050A7E630 500GB                         | 16        | 0.37%   |
| GOODRAM SSDPR-CX400-512 512GB                      | 16        | 0.37%   |
| GOODRAM SSDPR-CX400-256 256GB                      | 16        | 0.37%   |
| A-DATA SU800 256GB SSD                             | 16        | 0.37%   |
| Unknown                                            | 16        | 0.37%   |
| WDC WD10JPCX-24UE4T0 1TB                           | 15        | 0.35%   |
| Samsung SSD 980 500GB                              | 15        | 0.35%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 15        | 0.35%   |
| Samsung HM321HI 320GB                              | 15        | 0.35%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 14        | 0.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 14        | 0.33%   |
| Phison PS5013 E13 NVMe Controller 256GB            | 14        | 0.33%   |
| Patriot Burst 120GB SSD                            | 14        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 451       | 558    | 36.7%   |
| WDC                 | 284       | 344    | 23.11%  |
| Toshiba             | 169       | 207    | 13.75%  |
| Hitachi             | 157       | 183    | 12.77%  |
| HGST                | 81        | 99     | 6.59%   |
| Samsung Electronics | 39        | 42     | 3.17%   |
| Fujitsu             | 24        | 26     | 1.95%   |
| JMicron Technology  | 8         | 8      | 0.65%   |
| Unknown             | 5         | 5      | 0.41%   |
| ASMT                | 3         | 3      | 0.24%   |
| StoreJet            | 2         | 2      | 0.16%   |
| SAGE                | 1         | 1      | 0.08%   |
| LaCie               | 1         | 2      | 0.08%   |
| Initio              | 1         | 1      | 0.08%   |
| IBM/Hitachi         | 1         | 1      | 0.08%   |
| ASMedia             | 1         | 1      | 0.08%   |
| Apple               | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 259       | 335    | 16.94%  |
| GOODRAM             | 248       | 319    | 16.22%  |
| Crucial             | 133       | 207    | 8.7%    |
| A-DATA Technology   | 131       | 159    | 8.57%   |
| Kingston            | 108       | 147    | 7.06%   |
| SanDisk             | 106       | 136    | 6.93%   |
| WDC                 | 60        | 71     | 3.92%   |
| SK hynix            | 41        | 51     | 2.68%   |
| Micron Technology   | 41        | 50     | 2.68%   |
| Intel               | 39        | 45     | 2.55%   |
| Toshiba             | 36        | 39     | 2.35%   |
| Patriot             | 34        | 43     | 2.22%   |
| SPCC                | 33        | 39     | 2.16%   |
| PNY                 | 25        | 27     | 1.64%   |
| Plextor             | 25        | 38     | 1.64%   |
| LITEON              | 21        | 25     | 1.37%   |
| Transcend           | 19        | 23     | 1.24%   |
| China               | 19        | 26     | 1.24%   |
| LITEONIT            | 16        | 18     | 1.05%   |
| KIOXIA-EXCERIA      | 12        | 14     | 0.78%   |
| Apacer              | 11        | 20     | 0.72%   |
| OCZ                 | 8         | 8      | 0.52%   |
| Apple               | 8         | 9      | 0.52%   |
| KingSpec            | 7         | 8      | 0.46%   |
| Team                | 6         | 6      | 0.39%   |
| Gigabyte Technology | 5         | 6      | 0.33%   |
| USB3.0              | 4         | 4      | 0.26%   |
| Biostar             | 4         | 4      | 0.26%   |
| Unknown             | 4         | 4      | 0.26%   |
| POLION              | 3         | 3      | 0.2%    |
| Netac               | 3         | 4      | 0.2%    |
| Corsair             | 3         | 3      | 0.2%    |
| 2-Power             | 3         | 3      | 0.2%    |
| Union Memory        | 2         | 3      | 0.13%   |
| Ramaxel Technology  | 2         | 3      | 0.13%   |
| Phison              | 2         | 2      | 0.13%   |
| OWC                 | 2         | 2      | 0.13%   |
| Micron_1            | 2         | 2      | 0.13%   |
| Intenso             | 2         | 2      | 0.13%   |
| HS-SSD-C100         | 2         | 4      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1397      | 1955   | 35.94%  |
| HDD     | 1180      | 1484   | 30.36%  |
| NVMe    | 1062      | 1480   | 27.32%  |
| MMC     | 207       | 259    | 5.33%   |
| Unknown | 41        | 55     | 1.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2276      | 3320   | 61.7%   |
| NVMe | 1062      | 1470   | 28.79%  |
| MMC  | 207       | 259    | 5.61%   |
| SAS  | 144       | 184    | 3.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1842      | 2532   | 73.01%  |
| 0.51-1.0   | 625       | 838    | 24.77%  |
| 1.01-2.0   | 47        | 57     | 1.86%   |
| 4.01-10.0  | 4         | 4      | 0.16%   |
| 3.01-4.0   | 3         | 3      | 0.12%   |
| 2.01-3.0   | 2         | 5      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1039      | 29.33%  |
| 251-500        | 785       | 22.16%  |
| 1-20           | 454       | 12.82%  |
| 501-1000       | 399       | 11.26%  |
| 51-100         | 301       | 8.5%    |
| 1001-2000      | 175       | 4.94%   |
| 21-50          | 165       | 4.66%   |
| Unknown        | 131       | 3.7%    |
| 2001-3000      | 52        | 1.47%   |
| More than 3000 | 41        | 1.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1570      | 42.94%  |
| 21-50          | 579       | 15.84%  |
| 101-250        | 485       | 13.27%  |
| 51-100         | 457       | 12.5%   |
| 251-500        | 217       | 5.94%   |
| 501-1000       | 137       | 3.75%   |
| Unknown        | 131       | 3.58%   |
| 1001-2000      | 59        | 1.61%   |
| 2001-3000      | 12        | 0.33%   |
| More than 3000 | 7         | 0.19%   |
| 0              | 2         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB            | 11        | 11     | 3.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 9         | 10     | 2.49%   |
| Seagate ST500LT012-9WS142 500GB      | 8         | 27     | 2.21%   |
| Seagate ST500LT012-1DG142 500GB      | 7         | 10     | 1.93%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 6         | 7      | 1.66%   |
| Seagate ST1000LM014-1EJ164 1TB       | 5         | 6      | 1.38%   |
| HGST HTS545050A7E680 500GB           | 5         | 5      | 1.38%   |
| WDC WD5000BEVT-22ZAT0 500GB          | 4         | 4      | 1.1%    |
| WDC WD10JPVX-22JC3T0 1TB             | 4         | 4      | 1.1%    |
| Seagate ST980811AS 80GB              | 4         | 4      | 1.1%    |
| Seagate ST1000LM014-SSHD-8GB         | 4         | 4      | 1.1%    |
| Hitachi HTS543225L9SA00 250GB        | 4         | 4      | 1.1%    |
| Hitachi HTS541612J9SA00 120GB        | 4         | 5      | 1.1%    |
| WDC WD3200BPVT-80ZEST0 320GB         | 3         | 3      | 0.83%   |
| WDC WD1600BEVT-75A23T0 160GB         | 3         | 3      | 0.83%   |
| Toshiba MQ01ABD100 1TB               | 3         | 4      | 0.83%   |
| Toshiba MK1246GSX 120GB              | 3         | 3      | 0.83%   |
| Seagate ST9500420AS 500GB            | 3         | 3      | 0.83%   |
| Seagate ST9320325AS 320GB            | 3         | 3      | 0.83%   |
| Seagate ST9250827AS 250GB            | 3         | 4      | 0.83%   |
| Seagate ST9250410AS 250GB            | 3         | 3      | 0.83%   |
| Seagate ST320LT020-9YG142 320GB      | 3         | 3      | 0.83%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD  | 3         | 3      | 0.83%   |
| Hitachi HTS543232A7A384 320GB        | 3         | 4      | 0.83%   |
| Hitachi HTS542516K9SA00 160GB        | 3         | 3      | 0.83%   |
| Hitachi HTS541680J9SA00 80GB         | 3         | 3      | 0.83%   |
| HGST HTS541010A9E680 1TB             | 3         | 3      | 0.83%   |
| A-DATA Technology SU650 240GB SSD    | 3         | 3      | 0.83%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 2      | 0.55%   |
| WDC WD7500BPKT-22PK4T0 752GB         | 2         | 2      | 0.55%   |
| WDC WD3200BEVT-80A0RT0 320GB         | 2         | 2      | 0.55%   |
| WDC WD1600BEVT-22A23T0 160GB         | 2         | 2      | 0.55%   |
| Toshiba MK5075GSX 500GB              | 2         | 2      | 0.55%   |
| Toshiba MK3265GSX 320GB              | 2         | 2      | 0.55%   |
| Toshiba MK1646GSX 160GB              | 2         | 2      | 0.55%   |
| Toshiba MK1637GSX 160GB              | 2         | 2      | 0.55%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 2         | 2      | 0.55%   |
| Seagate ST9250410ASG 250GB           | 2         | 2      | 0.55%   |
| Seagate ST9250315AS 250GB            | 2         | 2      | 0.55%   |
| Seagate ST9160821AS 160GB            | 2         | 3      | 0.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 92        | 124    | 25.48%  |
| Hitachi             | 48        | 53     | 13.3%   |
| WDC                 | 45        | 46     | 12.47%  |
| Toshiba             | 38        | 48     | 10.53%  |
| A-DATA Technology   | 21        | 23     | 5.82%   |
| Samsung Electronics | 18        | 21     | 4.99%   |
| SK hynix            | 16        | 17     | 4.43%   |
| HGST                | 16        | 17     | 4.43%   |
| SanDisk             | 9         | 10     | 2.49%   |
| Micron Technology   | 7         | 7      | 1.94%   |
| Kingston            | 7         | 8      | 1.94%   |
| Intel               | 7         | 7      | 1.94%   |
| Fujitsu             | 6         | 7      | 1.66%   |
| Crucial             | 5         | 16     | 1.39%   |
| LITEONIT            | 3         | 3      | 0.83%   |
| LITEON              | 3         | 3      | 0.83%   |
| ASMedia             | 3         | 3      | 0.83%   |
| Patriot             | 2         | 4      | 0.55%   |
| OCZ                 | 2         | 2      | 0.55%   |
| China               | 2         | 3      | 0.55%   |
| SPCC                | 1         | 1      | 0.28%   |
| RENICE              | 1         | 1      | 0.28%   |
| POLION              | 1         | 1      | 0.28%   |
| Plextor             | 1         | 1      | 0.28%   |
| Platinet            | 1         | 1      | 0.28%   |
| OWC                 | 1         | 1      | 0.28%   |
| Lexar               | 1         | 1      | 0.28%   |
| Lenovo              | 1         | 1      | 0.28%   |
| KingSpec            | 1         | 1      | 0.28%   |
| Apple               | 1         | 1      | 0.28%   |
| Apacer              | 1         | 1      | 0.28%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 92        | 124    | 36.8%   |
| Hitachi             | 48        | 53     | 19.2%   |
| WDC                 | 42        | 43     | 16.8%   |
| Toshiba             | 35        | 45     | 14%     |
| HGST                | 16        | 17     | 6.4%    |
| Samsung Electronics | 10        | 11     | 4%      |
| Fujitsu             | 6         | 7      | 2.4%    |
| ASMedia             | 1         | 1      | 0.4%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 244       | 301    | 69.32%  |
| SSD  | 88        | 109    | 25%     |
| NVMe | 20        | 23     | 5.68%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD800BEVS-75RST0 80GB       | 1         | 1      | 20%     |
| WDC WD3200BEKT-75PVMT1 320GB    | 1         | 1      | 20%     |
| WDC WD2500BEVS-22UST0 250GB     | 1         | 1      | 20%     |
| Toshiba MK3265GSXN 320GB        | 1         | 1      | 20%     |
| Seagate ST320LT020-9YG142 320GB | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 60%     |
| Toshiba | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1626      | 2579   | 46.08%  |
| Works    | 1551      | 2216   | 43.95%  |
| Malfunc  | 347       | 433    | 9.83%   |
| Failed   | 5         | 5      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2437      | 63.4%   |
| Samsung Electronics              | 327       | 8.51%   |
| AMD                              | 317       | 8.25%   |
| SanDisk                          | 153       | 3.98%   |
| SK hynix                         | 118       | 3.07%   |
| Micron Technology                | 68        | 1.77%   |
| Phison Electronics               | 62        | 1.61%   |
| Toshiba America Info Systems     | 59        | 1.53%   |
| KIOXIA                           | 51        | 1.33%   |
| Kingston Technology Company      | 48        | 1.25%   |
| ADATA Technology                 | 33        | 0.86%   |
| Silicon Motion                   | 28        | 0.73%   |
| Nvidia                           | 22        | 0.57%   |
| Union Memory (Shenzhen)          | 16        | 0.42%   |
| Micron/Crucial Technology        | 12        | 0.31%   |
| Silicon Integrated Systems [SiS] | 11        | 0.29%   |
| Shenzhen Longsys Electronics     | 11        | 0.29%   |
| Realtek Semiconductor            | 10        | 0.26%   |
| Lite-On Technology               | 9         | 0.23%   |
| Lenovo                           | 9         | 0.23%   |
| Solid State Storage Technology   | 8         | 0.21%   |
| VIA Technologies                 | 7         | 0.18%   |
| MAXIO Technology (Hangzhou)      | 7         | 0.18%   |
| JMicron Technology               | 5         | 0.13%   |
| O2 Micro                         | 4         | 0.1%    |
| Apple                            | 4         | 0.1%    |
| Yangtze Memory Technologies      | 2         | 0.05%   |
| Marvell Technology Group         | 2         | 0.05%   |
| Silicon Image                    | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |
| ASMedia Technology               | 1         | 0.03%   |
| Unknown                          | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 267       | 6.35%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 265       | 6.3%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 222       | 5.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 193       | 4.59%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 192       | 4.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 147       | 3.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 139       | 3.31%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 130       | 3.09%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 114       | 2.71%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 114       | 2.71%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 113       | 2.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 112       | 2.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 102       | 2.43%   |
| Intel Volume Management Device NVMe RAID Controller                            | 98        | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 85        | 2.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 81        | 1.93%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 80        | 1.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 79        | 1.88%   |
| Intel SSD 660P Series                                                          | 67        | 1.59%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 59        | 1.4%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 53        | 1.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 41        | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 41        | 0.98%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 39        | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 38        | 0.9%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 35        | 0.83%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 33        | 0.78%   |
| Intel Tiger Lake-LP SATA Controller                                            | 33        | 0.78%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 32        | 0.76%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 31        | 0.74%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 31        | 0.74%   |
| SK hynix BC511 NVMe SSD                                                        | 27        | 0.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 27        | 0.64%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 27        | 0.64%   |
| Intel Comet Lake SATA AHCI Controller                                          | 26        | 0.62%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 25        | 0.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 24        | 0.57%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 24        | 0.57%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 23        | 0.55%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 22        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2287      | 57.18%  |
| NVMe | 1071      | 26.78%  |
| IDE  | 338       | 8.45%   |
| RAID | 304       | 7.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2749      | 83.43%  |
| AMD          | 543       | 16.48%  |
| CentaurHauls | 2         | 0.06%   |
| QUALCOMM     | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 53        | 1.61%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 50        | 1.52%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 48        | 1.45%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 47        | 1.42%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 47        | 1.42%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 42        | 1.27%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 42        | 1.27%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 41        | 1.24%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 38        | 1.15%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 34        | 1.03%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 33        | 1%      |
| Intel Core i7-8750H CPU @ 2.20GHz             | 33        | 1%      |
| Intel Core i7-8550U CPU @ 1.80GHz             | 32        | 0.97%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 32        | 0.97%   |
| AMD Custom APU 0405                           | 32        | 0.97%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 30        | 0.91%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 30        | 0.91%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 30        | 0.91%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 29        | 0.88%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 27        | 0.82%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 26        | 0.79%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 26        | 0.79%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 25        | 0.76%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 24        | 0.73%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 24        | 0.73%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 24        | 0.73%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 23        | 0.7%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 23        | 0.7%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 22        | 0.67%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 22        | 0.67%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 22        | 0.67%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 21        | 0.64%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 21        | 0.64%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 21        | 0.64%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 20        | 0.61%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 20        | 0.61%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 19        | 0.58%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 19        | 0.58%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 19        | 0.58%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 19        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 911       | 27.62%  |
| Intel Core i7                  | 600       | 18.19%  |
| Intel Core i3                  | 257       | 7.79%   |
| Other                          | 254       | 7.7%    |
| Intel Core 2 Duo               | 244       | 7.4%    |
| Intel Celeron                  | 187       | 5.67%   |
| AMD Ryzen 5                    | 163       | 4.94%   |
| AMD Ryzen 7                    | 118       | 3.58%   |
| Intel Pentium                  | 103       | 3.12%   |
| Intel Atom                     | 61        | 1.85%   |
| Intel Pentium Dual-Core        | 41        | 1.24%   |
| AMD A6                         | 29        | 0.88%   |
| Intel Core 2                   | 23        | 0.7%    |
| Intel Pentium Dual             | 21        | 0.64%   |
| AMD Ryzen 7 PRO                | 21        | 0.64%   |
| AMD A8                         | 21        | 0.64%   |
| Intel Genuine                  | 17        | 0.52%   |
| AMD A4                         | 16        | 0.49%   |
| AMD E1                         | 13        | 0.39%   |
| AMD E                          | 13        | 0.39%   |
| Intel Celeron M                | 12        | 0.36%   |
| AMD Ryzen 9                    | 12        | 0.36%   |
| AMD A10                        | 12        | 0.36%   |
| Intel Xeon                     | 11        | 0.33%   |
| AMD Ryzen 5 PRO                | 10        | 0.3%    |
| AMD Ryzen 3                    | 9         | 0.27%   |
| Intel Pentium M                | 8         | 0.24%   |
| AMD E2                         | 8         | 0.24%   |
| AMD Athlon X2                  | 8         | 0.24%   |
| Intel Core Duo                 | 7         | 0.21%   |
| AMD Turion 64 X2 Mobile        | 7         | 0.21%   |
| AMD C-60                       | 6         | 0.18%   |
| Intel Core i9                  | 5         | 0.15%   |
| Intel Celeron Dual-Core        | 5         | 0.15%   |
| AMD Athlon II                  | 5         | 0.15%   |
| Intel Pentium Silver           | 4         | 0.12%   |
| AMD Turion X2 Dual-Core Mobile | 4         | 0.12%   |
| AMD Phenom II                  | 4         | 0.12%   |
| Intel Core m3                  | 3         | 0.09%   |
| Intel Core M                   | 3         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1781      | 53.97%  |
| 4       | 961       | 29.12%  |
| 6       | 223       | 6.76%   |
| 8       | 163       | 4.94%   |
| 1       | 76        | 2.3%    |
| 10      | 25        | 0.76%   |
| 14      | 23        | 0.7%    |
| 12      | 21        | 0.64%   |
| Unknown | 21        | 0.64%   |
| 16      | 2         | 0.06%   |
| 3       | 2         | 0.06%   |
| 192     | 1         | 0.03%   |
| 5       | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 3292      | 99.91%  |
| Unknown | 2         | 0.06%   |
| 2       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2359      | 71.33%  |
| 1       | 925       | 27.97%  |
| Unknown | 21        | 0.64%   |
| 8       | 1         | 0.03%   |
| 4       | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3211      | 97.3%   |
| 32-bit         | 49        | 1.48%   |
| Unknown        | 39        | 1.18%   |
| 64-bit         | 1         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 942       | 27.4%   |
| 0x206a7    | 206       | 5.99%   |
| 0x306a9    | 197       | 5.73%   |
| 0x1067a    | 118       | 3.43%   |
| 0x40651    | 106       | 3.08%   |
| 0x20655    | 93        | 2.71%   |
| 0x306c3    | 89        | 2.59%   |
| 0x906ea    | 88        | 2.56%   |
| 0x806ec    | 88        | 2.56%   |
| 0x306d4    | 88        | 2.56%   |
| 0x806c1    | 84        | 2.44%   |
| 0x30678    | 83        | 2.41%   |
| 0x406e3    | 79        | 2.3%    |
| 0x806ea    | 78        | 2.27%   |
| 0x6fd      | 74        | 2.15%   |
| 0x806e9    | 64        | 1.86%   |
| 0x506e3    | 55        | 1.6%    |
| 0x10676    | 52        | 1.51%   |
| 0x0a50000c | 51        | 1.48%   |
| 0x906e9    | 44        | 1.28%   |
| 0x08600106 | 41        | 1.19%   |
| 0xa0652    | 33        | 0.96%   |
| 0x20652    | 32        | 0.93%   |
| 0x08108109 | 31        | 0.9%    |
| 0x08108102 | 28        | 0.81%   |
| 0x806eb    | 25        | 0.73%   |
| 0x706e5    | 24        | 0.7%    |
| 0x6fb      | 20        | 0.58%   |
| 0x08600103 | 20        | 0.58%   |
| 0x08600104 | 19        | 0.55%   |
| 0x906ed    | 18        | 0.52%   |
| 0x906a3    | 18        | 0.52%   |
| 0x806d1    | 18        | 0.52%   |
| 0x6f6      | 18        | 0.52%   |
| 0x06001119 | 18        | 0.52%   |
| 0x506c9    | 17        | 0.49%   |
| 0x406c4    | 17        | 0.49%   |
| 0x106ca    | 17        | 0.49%   |
| 0x08608103 | 16        | 0.47%   |
| 0x406c3    | 15        | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 548       | 16.62%  |
| Haswell          | 270       | 8.19%   |
| SandyBridge      | 267       | 8.1%    |
| IvyBridge        | 265       | 8.04%   |
| Penryn           | 201       | 6.1%    |
| Skylake          | 186       | 5.64%   |
| Core             | 158       | 4.79%   |
| Westmere         | 155       | 4.7%    |
| Silvermont       | 142       | 4.31%   |
| Broadwell        | 123       | 3.73%   |
| TigerLake        | 121       | 3.67%   |
| Zen 2            | 111       | 3.37%   |
| Unknown          | 105       | 3.18%   |
| Zen 3            | 77        | 2.34%   |
| Zen+             | 76        | 2.31%   |
| Alderlake Hybrid | 63        | 1.91%   |
| IceLake          | 50        | 1.52%   |
| CometLake        | 47        | 1.43%   |
| Bonnell          | 37        | 1.12%   |
| Bobcat           | 36        | 1.09%   |
| P6               | 33        | 1%      |
| Goldmont plus    | 30        | 0.91%   |
| Piledriver       | 26        | 0.79%   |
| Goldmont         | 25        | 0.76%   |
| Zen              | 24        | 0.73%   |
| Excavator        | 21        | 0.64%   |
| Puma             | 16        | 0.49%   |
| K8 & K10 hybrid  | 16        | 0.49%   |
| K8 Hammer        | 14        | 0.42%   |
| K10              | 14        | 0.42%   |
| Jaguar           | 14        | 0.42%   |
| K10 Llano        | 12        | 0.36%   |
| Nehalem          | 7         | 0.21%   |
| Steamroller      | 4         | 0.12%   |
| Tremont          | 2         | 0.06%   |
| Gracemont        | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2470      | 57.87%  |
| Nvidia                           | 997       | 23.36%  |
| AMD                              | 788       | 18.46%  |
| VIA Technologies                 | 7         | 0.16%   |
| Silicon Integrated Systems [SiS] | 6         | 0.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 256       | 5.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 246       | 5.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 140       | 3.15%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 120       | 2.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 119       | 2.68%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 115       | 2.59%   |
| Intel UHD Graphics 620                                                                   | 114       | 2.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 110       | 2.48%   |
| Intel HD Graphics 5500                                                                   | 110       | 2.48%   |
| Intel Core Processor Integrated Graphics Controller                                      | 107       | 2.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 104       | 2.34%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 104       | 2.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 99        | 2.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 85        | 1.91%   |
| Intel HD Graphics 620                                                                    | 84        | 1.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 79        | 1.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 79        | 1.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 77        | 1.73%   |
| Intel HD Graphics 530                                                                    | 63        | 1.42%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 62        | 1.4%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 60        | 1.35%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 56        | 1.26%   |
| Intel HD Graphics 630                                                                    | 56        | 1.26%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 52        | 1.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 50        | 1.13%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 45        | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 43        | 0.97%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 41        | 0.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 40        | 0.9%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 37        | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 33        | 0.74%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 31        | 0.7%    |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 30        | 0.68%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 29        | 0.65%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 28        | 0.63%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 28        | 0.63%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 27        | 0.61%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 27        | 0.61%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 26        | 0.59%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 25        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1573      | 47.51%  |
| Intel + Nvidia           | 690       | 20.84%  |
| 1 x AMD                  | 458       | 13.83%  |
| 1 x Nvidia               | 207       | 6.25%   |
| Intel + AMD              | 179       | 5.41%   |
| AMD + Nvidia             | 97        | 2.93%   |
| 2 x AMD                  | 51        | 1.54%   |
| 2 x Intel                | 31        | 0.94%   |
| Other                    | 8         | 0.24%   |
| 1 x VIA                  | 7         | 0.21%   |
| 1 x SiS                  | 6         | 0.18%   |
| 2 x Intel + 1 x Nvidia   | 2         | 0.06%   |
| 2 x Nvidia               | 1         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2810      | 84.03%  |
| Proprietary | 451       | 13.49%  |
| Unknown     | 83        | 2.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2053      | 60.69%  |
| 1.01-2.0   | 424       | 12.53%  |
| 0.01-0.5   | 421       | 12.44%  |
| 0.51-1.0   | 204       | 6.03%   |
| 3.01-4.0   | 197       | 5.82%   |
| 5.01-6.0   | 52        | 1.54%   |
| 7.01-8.0   | 22        | 0.65%   |
| 2.01-3.0   | 6         | 0.18%   |
| 8.01-16.0  | 4         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 676       | 17.78%  |
| LG Display              | 576       | 15.15%  |
| BOE                     | 467       | 12.29%  |
| Samsung Electronics     | 463       | 12.18%  |
| Chimei Innolux          | 419       | 11.02%  |
| Dell                    | 137       | 3.6%    |
| Chi Mei Optoelectronics | 123       | 3.24%   |
| Lenovo                  | 110       | 2.89%   |
| Goldstar                | 74        | 1.95%   |
| Iiyama                  | 67        | 1.76%   |
| Sharp                   | 60        | 1.58%   |
| PANDA                   | 53        | 1.39%   |
| LG Philips              | 49        | 1.29%   |
| Philips                 | 37        | 0.97%   |
| BenQ                    | 37        | 0.97%   |
| InfoVision              | 35        | 0.92%   |
| Hewlett-Packard         | 30        | 0.79%   |
| Apple                   | 30        | 0.79%   |
| AOC                     | 30        | 0.79%   |
| Acer                    | 28        | 0.74%   |
| Valve                   | 24        | 0.63%   |
| NEC Computers           | 23        | 0.61%   |
| HannStar                | 18        | 0.47%   |
| Ancor Communications    | 18        | 0.47%   |
| Eizo                    | 17        | 0.45%   |
| CSO                     | 17        | 0.45%   |
| CPT                     | 16        | 0.42%   |
| ASUSTek Computer        | 10        | 0.26%   |
| Toshiba                 | 9         | 0.24%   |
| TMX                     | 9         | 0.24%   |
| Sony                    | 9         | 0.24%   |
| Mi                      | 9         | 0.24%   |
| LGD                     | 9         | 0.24%   |
| Seiko/Epson             | 8         | 0.21%   |
| MSI                     | 8         | 0.21%   |
| Panasonic               | 6         | 0.16%   |
| InnoLux Display         | 6         | 0.16%   |
| Fujitsu Siemens         | 6         | 0.16%   |
| IBM                     | 5         | 0.13%   |
| Vestel Elektronik       | 4         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 34        | 0.88%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 33        | 0.85%   |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 31        | 0.8%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 29        | 0.75%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 29        | 0.75%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 28        | 0.72%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 27        | 0.7%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 22        | 0.57%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 22        | 0.57%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 21        | 0.54%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 20        | 0.52%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 19        | 0.49%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 18        | 0.46%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 17        | 0.44%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 17        | 0.44%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 17        | 0.44%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 16        | 0.41%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 15        | 0.39%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 14        | 0.36%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 14        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 14        | 0.36%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 14        | 0.36%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 13        | 0.33%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 13        | 0.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 13        | 0.33%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 13        | 0.33%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 12        | 0.31%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 12        | 0.31%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 12        | 0.31%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 11        | 0.28%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 11        | 0.28%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 11        | 0.28%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 11        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 11        | 0.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 11        | 0.28%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch     | 10        | 0.26%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 10        | 0.26%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 10        | 0.26%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 10        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 10        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1469      | 41.59%  |
| 1366x768 (WXGA)    | 933       | 26.42%  |
| 1600x900 (HD+)     | 228       | 6.46%   |
| 1280x800 (WXGA)    | 205       | 5.8%    |
| 3840x2160 (4K)     | 108       | 3.06%   |
| 2560x1440 (QHD)    | 106       | 3%      |
| 1920x1200 (WUXGA)  | 98        | 2.77%   |
| 1440x900 (WXGA+)   | 75        | 2.12%   |
| 1680x1050 (WSXGA+) | 55        | 1.56%   |
| 2560x1600          | 29        | 0.82%   |
| 800x1280           | 27        | 0.76%   |
| 1024x600           | 27        | 0.76%   |
| 3440x1440          | 24        | 0.68%   |
| 1280x1024 (SXGA)   | 23        | 0.65%   |
| 2880x1800          | 14        | 0.4%    |
| 2560x1080          | 12        | 0.34%   |
| 2160x1440          | 12        | 0.34%   |
| 3840x2400          | 11        | 0.31%   |
| Unknown            | 10        | 0.28%   |
| 1024x768 (XGA)     | 7         | 0.2%    |
| 3200x1800 (QHD+)   | 5         | 0.14%   |
| 3840x1080          | 4         | 0.11%   |
| 3200x2000          | 4         | 0.11%   |
| 1680x945           | 4         | 0.11%   |
| 3456x2160          | 3         | 0.08%   |
| 3286x1080          | 3         | 0.08%   |
| 2288x1287          | 3         | 0.08%   |
| 2240x1400          | 3         | 0.08%   |
| 1400x1050          | 3         | 0.08%   |
| 1360x768           | 3         | 0.08%   |
| 1280x768           | 3         | 0.08%   |
| 3840x1600          | 2         | 0.06%   |
| 3000x2000          | 2         | 0.06%   |
| 2520x1680          | 2         | 0.06%   |
| 2256x1504          | 2         | 0.06%   |
| 1920x540           | 2         | 0.06%   |
| 1600x1200          | 2         | 0.06%   |
| 1280x720 (HD)      | 2         | 0.06%   |
| 6400x1600          | 1         | 0.03%   |
| 5120x1600          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1620      | 42.55%  |
| 13      | 443       | 11.64%  |
| 14      | 428       | 11.24%  |
| 17      | 277       | 7.28%   |
| 24      | 166       | 4.36%   |
| 23      | 120       | 3.15%   |
| 27      | 118       | 3.1%    |
| 12      | 118       | 3.1%    |
| 21      | 76        | 2%      |
| 11      | 56        | 1.47%   |
| Unknown | 56        | 1.47%   |
| 16      | 44        | 1.16%   |
| 34      | 39        | 1.02%   |
| 10      | 30        | 0.79%   |
| 19      | 26        | 0.68%   |
| 22      | 25        | 0.66%   |
| 18      | 24        | 0.63%   |
| 7       | 24        | 0.63%   |
| 31      | 23        | 0.6%    |
| 25      | 11        | 0.29%   |
| 48      | 10        | 0.26%   |
| 20      | 10        | 0.26%   |
| 40      | 9         | 0.24%   |
| 84      | 8         | 0.21%   |
| 72      | 6         | 0.16%   |
| 32      | 5         | 0.13%   |
| 3       | 5         | 0.13%   |
| 43      | 4         | 0.11%   |
| 37      | 4         | 0.11%   |
| 54      | 3         | 0.08%   |
| 28      | 3         | 0.08%   |
| 142     | 2         | 0.05%   |
| 65      | 2         | 0.05%   |
| 46      | 2         | 0.05%   |
| 26      | 2         | 0.05%   |
| 86      | 1         | 0.03%   |
| 60      | 1         | 0.03%   |
| 52      | 1         | 0.03%   |
| 49      | 1         | 0.03%   |
| 35      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2277      | 60.61%  |
| 201-300        | 389       | 10.35%  |
| 501-600        | 380       | 10.11%  |
| 351-400        | 345       | 9.18%   |
| 401-500        | 145       | 3.86%   |
| Unknown        | 56        | 1.49%   |
| 701-800        | 45        | 1.2%    |
| 601-700        | 36        | 0.96%   |
| 1-100          | 28        | 0.75%   |
| 1001-1500      | 21        | 0.56%   |
| 801-900        | 14        | 0.37%   |
| 1501-2000      | 14        | 0.37%   |
| 901-1000       | 4         | 0.11%   |
| More than 2000 | 2         | 0.05%   |
| 101-200        | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2664      | 79.71%  |
| 16/10   | 478       | 14.3%   |
| Unknown | 46        | 1.38%   |
| 21/9    | 41        | 1.23%   |
| 3/2     | 38        | 1.14%   |
| 5/4     | 25        | 0.75%   |
| 0.67    | 22        | 0.66%   |
| 4/3     | 14        | 0.42%   |
| 6/5     | 5         | 0.15%   |
| 32/9    | 3         | 0.09%   |
| 0.62    | 3         | 0.09%   |
| 1.00    | 2         | 0.06%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1617      | 42.66%  |
| 81-90          | 714       | 18.84%  |
| 201-250        | 296       | 7.81%   |
| 121-130        | 221       | 5.83%   |
| 71-80          | 148       | 3.91%   |
| 301-350        | 120       | 3.17%   |
| 61-70          | 117       | 3.09%   |
| 251-300        | 80        | 2.11%   |
| 351-500        | 69        | 1.82%   |
| 51-60          | 56        | 1.48%   |
| Unknown        | 56        | 1.48%   |
| 131-140        | 50        | 1.32%   |
| 151-200        | 48        | 1.27%   |
| 111-120        | 34        | 0.9%    |
| More than 1000 | 32        | 0.84%   |
| 141-150        | 31        | 0.82%   |
| 41-50          | 30        | 0.79%   |
| 1-40           | 29        | 0.77%   |
| 501-1000       | 22        | 0.58%   |
| 91-100         | 20        | 0.53%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1544      | 41.51%  |
| 101-120       | 1063      | 28.58%  |
| 51-100        | 725       | 19.49%  |
| 161-240       | 223       | 5.99%   |
| More than 240 | 79        | 2.12%   |
| Unknown       | 56        | 1.51%   |
| 1-50          | 30        | 0.81%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2680      | 78.78%  |
| 2     | 554       | 16.28%  |
| 3     | 81        | 2.38%   |
| 0     | 76        | 2.23%   |
| 4     | 9         | 0.26%   |
| 6     | 1         | 0.03%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1904      | 35.32%  |
| Realtek Semiconductor             | 1549      | 28.74%  |
| Qualcomm Atheros                  | 766       | 14.21%  |
| Broadcom                          | 363       | 6.73%   |
| Broadcom Limited                  | 103       | 1.91%   |
| Dell                              | 88        | 1.63%   |
| MediaTek                          | 74        | 1.37%   |
| Marvell Technology Group          | 74        | 1.37%   |
| Huawei Technologies               | 61        | 1.13%   |
| Ralink                            | 38        | 0.71%   |
| TP-Link                           | 37        | 0.69%   |
| Ericsson Business Mobile Networks | 34        | 0.63%   |
| Samsung Electronics               | 29        | 0.54%   |
| Hewlett-Packard                   | 28        | 0.52%   |
| Xiaomi                            | 21        | 0.39%   |
| ASIX Electronics                  | 21        | 0.39%   |
| Sierra Wireless                   | 19        | 0.35%   |
| JMicron Technology                | 17        | 0.32%   |
| Lenovo                            | 15        | 0.28%   |
| DisplayLink                       | 14        | 0.26%   |
| Ralink Technology                 | 12        | 0.22%   |
| Nvidia                            | 12        | 0.22%   |
| Qualcomm                          | 11        | 0.2%    |
| Qualcomm Atheros Communications   | 10        | 0.19%   |
| Fibocom                           | 10        | 0.19%   |
| Silicon Integrated Systems [SiS]  | 9         | 0.17%   |
| ASUSTek Computer                  | 8         | 0.15%   |
| ZTE WCDMA Technologies MSM        | 7         | 0.13%   |
| Motorola PCS                      | 6         | 0.11%   |
| VIA Technologies                  | 5         | 0.09%   |
| NetGear                           | 5         | 0.09%   |
| Attansic Technology               | 5         | 0.09%   |
| Microsoft                         | 3         | 0.06%   |
| HTC (High Tech Computer)          | 3         | 0.06%   |
| Edimax Technology                 | 3         | 0.06%   |
| Sigma Designs                     | 2         | 0.04%   |
| OPPO Electronics                  | 2         | 0.04%   |
| Unknown                           | 2         | 0.04%   |
| ZyXEL Communications              | 1         | 0.02%   |
| Uniden                            | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 1000      | 15.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 263       | 4.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 179       | 2.73%   |
| Intel Wireless 8265 / 8275                                              | 146       | 2.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 138       | 2.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 133       | 2.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 122       | 1.86%   |
| Intel Wi-Fi 6 AX200                                                     | 122       | 1.86%   |
| Intel Wireless 7260                                                     | 116       | 1.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 115       | 1.76%   |
| Intel Wireless 8260                                                     | 98        | 1.5%    |
| Intel Wi-Fi 6 AX201                                                     | 95        | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 94        | 1.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 93        | 1.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 92        | 1.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 90        | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 86        | 1.31%   |
| Intel Wireless 7265                                                     | 79        | 1.21%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 77        | 1.18%   |
| Intel Wireless 3160                                                     | 68        | 1.04%   |
| Intel Wireless 3165                                                     | 66        | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 61        | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 59        | 0.9%    |
| Intel 82567LM Gigabit Network Connection                                | 59        | 0.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 58        | 0.89%   |
| Broadcom BCM43142 802.11b/g/n                                           | 57        | 0.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 56        | 0.86%   |
| Intel Ethernet Connection (4) I219-LM                                   | 53        | 0.81%   |
| Intel Centrino Ultimate-N 6300                                          | 53        | 0.81%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 51        | 0.78%   |
| Intel Ethernet Connection I218-LM                                       | 50        | 0.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 49        | 0.75%   |
| Intel Ethernet Connection I217-LM                                       | 48        | 0.73%   |
| Intel WiFi Link 5100                                                    | 47        | 0.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 47        | 0.72%   |
| Intel 82577LM Gigabit Network Connection                                | 46        | 0.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 44        | 0.67%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 41        | 0.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 40        | 0.61%   |
| Intel Centrino Advanced-N 6235                                          | 39        | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1812      | 52.32%  |
| Qualcomm Atheros                  | 640       | 18.48%  |
| Realtek Semiconductor             | 400       | 11.55%  |
| Broadcom                          | 257       | 7.42%   |
| MediaTek                          | 70        | 2.02%   |
| Broadcom Limited                  | 57        | 1.65%   |
| Dell                              | 53        | 1.53%   |
| Ralink                            | 38        | 1.1%    |
| TP-Link                           | 33        | 0.95%   |
| Sierra Wireless                   | 19        | 0.55%   |
| Ralink Technology                 | 12        | 0.35%   |
| Ericsson Business Mobile Networks | 11        | 0.32%   |
| Qualcomm Atheros Communications   | 10        | 0.29%   |
| Fibocom                           | 10        | 0.29%   |
| Qualcomm                          | 9         | 0.26%   |
| Hewlett-Packard                   | 8         | 0.23%   |
| ASUSTek Computer                  | 8         | 0.23%   |
| Microsoft                         | 3         | 0.09%   |
| Edimax Technology                 | 3         | 0.09%   |
| NetGear                           | 2         | 0.06%   |
| Unknown                           | 2         | 0.06%   |
| ZyXEL Communications              | 1         | 0.03%   |
| Tenda                             | 1         | 0.03%   |
| Sweex                             | 1         | 0.03%   |
| Sagem                             | 1         | 0.03%   |
| Linksys                           | 1         | 0.03%   |
| Belkin Components                 | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 146       | 4.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 138       | 3.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 133       | 3.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 122       | 3.52%   |
| Intel Wi-Fi 6 AX200                                                     | 122       | 3.52%   |
| Intel Wireless 7260                                                     | 116       | 3.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 115       | 3.32%   |
| Intel Wireless 8260                                                     | 98        | 2.83%   |
| Intel Wi-Fi 6 AX201                                                     | 95        | 2.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 94        | 2.71%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 92        | 2.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 90        | 2.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 86        | 2.48%   |
| Intel Wireless 7265                                                     | 79        | 2.28%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 77        | 2.22%   |
| Intel Wireless 3160                                                     | 68        | 1.96%   |
| Intel Wireless 3165                                                     | 66        | 1.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 61        | 1.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 59        | 1.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 58        | 1.67%   |
| Broadcom BCM43142 802.11b/g/n                                           | 57        | 1.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 56        | 1.62%   |
| Intel Centrino Ultimate-N 6300                                          | 53        | 1.53%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 51        | 1.47%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 49        | 1.41%   |
| Intel WiFi Link 5100                                                    | 47        | 1.36%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 47        | 1.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 44        | 1.27%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 41        | 1.18%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 40        | 1.15%   |
| Intel Centrino Advanced-N 6235                                          | 39        | 1.12%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 38        | 1.1%    |
| Intel Centrino Advanced-N 6200                                          | 37        | 1.07%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 35        | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 33        | 0.95%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 31        | 0.89%   |
| Intel Centrino Wireless-N 2230                                          | 29        | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 26        | 0.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 25        | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 22        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1387      | 47.16%  |
| Intel                            | 829       | 28.19%  |
| Qualcomm Atheros                 | 229       | 7.79%   |
| Broadcom                         | 149       | 5.07%   |
| Marvell Technology Group         | 74        | 2.52%   |
| Broadcom Limited                 | 47        | 1.6%    |
| Huawei Technologies              | 43        | 1.46%   |
| Samsung Electronics              | 27        | 0.92%   |
| ASIX Electronics                 | 21        | 0.71%   |
| Xiaomi                           | 20        | 0.68%   |
| JMicron Technology               | 17        | 0.58%   |
| Lenovo                           | 15        | 0.51%   |
| DisplayLink                      | 14        | 0.48%   |
| Nvidia                           | 12        | 0.41%   |
| Silicon Integrated Systems [SiS] | 9         | 0.31%   |
| ZTE WCDMA Technologies MSM       | 6         | 0.2%    |
| Motorola PCS                     | 6         | 0.2%    |
| VIA Technologies                 | 5         | 0.17%   |
| Attansic Technology              | 5         | 0.17%   |
| TP-Link                          | 4         | 0.14%   |
| Hewlett-Packard                  | 4         | 0.14%   |
| NetGear                          | 3         | 0.1%    |
| MediaTek                         | 3         | 0.1%    |
| HTC (High Tech Computer)         | 3         | 0.1%    |
| Qualcomm                         | 2         | 0.07%   |
| OPPO Electronics                 | 2         | 0.07%   |
| QinHeng Electronics              | 1         | 0.03%   |
| LG Electronics                   | 1         | 0.03%   |
| ICS Advent                       | 1         | 0.03%   |
| HMD Global                       | 1         | 0.03%   |
| Apple                            | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1000      | 33.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 263       | 8.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 179       | 6.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 93        | 3.14%   |
| Intel 82567LM Gigabit Network Connection                               | 59        | 1.99%   |
| Intel Ethernet Connection (4) I219-LM                                  | 53        | 1.79%   |
| Intel Ethernet Connection I218-LM                                      | 50        | 1.69%   |
| Intel Ethernet Connection I217-LM                                      | 48        | 1.62%   |
| Intel 82577LM Gigabit Network Connection                               | 46        | 1.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 37        | 1.25%   |
| Huawei E353/E3131                                                      | 37        | 1.25%   |
| Intel Ethernet Connection (3) I218-LM                                  | 35        | 1.18%   |
| Intel Ethernet Connection (6) I219-V                                   | 34        | 1.15%   |
| Intel Ethernet Connection I219-LM                                      | 33        | 1.11%   |
| Intel Ethernet Connection (7) I219-LM                                  | 27        | 0.91%   |
| Intel Ethernet Connection (4) I219-V                                   | 27        | 0.91%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 26        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 24        | 0.81%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 23        | 0.78%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 22        | 0.74%   |
| Intel 82579V Gigabit Network Connection                                | 20        | 0.67%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 19        | 0.64%   |
| ASIX AX88179 Gigabit Ethernet                                          | 18        | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 17        | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                                  | 17        | 0.57%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 17        | 0.57%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 17        | 0.57%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 16        | 0.54%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 16        | 0.54%   |
| Intel Ethernet Connection I219-V                                       | 16        | 0.54%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 16        | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 15        | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 15        | 0.51%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 15        | 0.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 15        | 0.51%   |
| Intel Ethernet Connection (5) I219-LM                                  | 15        | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 14        | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 14        | 0.47%   |
| Intel Ethernet Connection (11) I219-LM                                 | 14        | 0.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 13        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3250      | 52.65%  |
| Ethernet | 2808      | 45.49%  |
| Modem    | 108       | 1.75%   |
| Unknown  | 7         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2668      | 77.83%  |
| Ethernet | 759       | 22.14%  |
| Modem    | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2620      | 79.42%  |
| 1     | 625       | 18.95%  |
| 0     | 43        | 1.3%    |
| 3     | 11        | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3052      | 91.73%  |
| Yes  | 275       | 8.27%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1237      | 47.71%  |
| Qualcomm Atheros Communications | 262       | 10.1%   |
| Realtek Semiconductor           | 196       | 7.56%   |
| Broadcom                        | 182       | 7.02%   |
| IMC Networks                    | 152       | 5.86%   |
| Dell                            | 100       | 3.86%   |
| Foxconn / Hon Hai               | 95        | 3.66%   |
| Lite-On Technology              | 78        | 3.01%   |
| Hewlett-Packard                 | 67        | 2.58%   |
| Toshiba                         | 33        | 1.27%   |
| Cambridge Silicon Radio         | 31        | 1.2%    |
| ASUSTek Computer                | 31        | 1.2%    |
| Apple                           | 28        | 1.08%   |
| Ralink                          | 21        | 0.81%   |
| Foxconn International           | 19        | 0.73%   |
| Realtek                         | 15        | 0.58%   |
| Alps Electric                   | 8         | 0.31%   |
| Chicony Electronics             | 7         | 0.27%   |
| Taiyo Yuden                     | 5         | 0.19%   |
| MediaTek                        | 5         | 0.19%   |
| USI                             | 3         | 0.12%   |
| Ralink Technology               | 3         | 0.12%   |
| Integrated System Solution      | 3         | 0.12%   |
| Opticis                         | 2         | 0.08%   |
| Micro Star International        | 2         | 0.08%   |
| Askey Computer                  | 2         | 0.08%   |
| TP-Link                         | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| Creative Technology             | 1         | 0.04%   |
| AboCom Systems                  | 1         | 0.04%   |
| Unknown                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 563       | 21.7%   |
| Intel AX201 Bluetooth                               | 198       | 7.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 161       | 6.21%   |
| Realtek Bluetooth Radio                             | 131       | 5.05%   |
| Intel AX200 Bluetooth                               | 116       | 4.47%   |
| Qualcomm Atheros  Bluetooth Device                  | 114       | 4.39%   |
| Intel Bluetooth Device                              | 74        | 2.85%   |
| IMC Networks Bluetooth Radio                        | 68        | 2.62%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 65        | 2.51%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 62        | 2.39%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 44        | 1.7%    |
| Realtek  Bluetooth 4.2 Adapter                      | 41        | 1.58%   |
| Broadcom BCM2045B (BDC-2.1)                         | 41        | 1.58%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 37        | 1.43%   |
| Dell BCM20702A0 Bluetooth Module                    | 34        | 1.31%   |
| Intel Wireless-AC 3168 Bluetooth                    | 32        | 1.23%   |
| IMC Networks Wireless_Device                        | 31        | 1.2%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 31        | 1.2%    |
| Dell DW375 Bluetooth Module                         | 30        | 1.16%   |
| HP Broadcom 2070 Bluetooth Combo                    | 29        | 1.12%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 26        | 1%      |
| Foxconn / Hon Hai Wireless_Device                   | 25        | 0.96%   |
| IMC Networks Bluetooth Device                       | 24        | 0.93%   |
| Lite-On Bluetooth Device                            | 22        | 0.85%   |
| Ralink RT3290 Bluetooth                             | 21        | 0.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 21        | 0.81%   |
| Realtek RTL8723B Bluetooth                          | 20        | 0.77%   |
| Broadcom BCM2070 Bluetooth Device                   | 20        | 0.77%   |
| Foxconn International BCM43142A0 Bluetooth module   | 19        | 0.73%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 17        | 0.66%   |
| Lite-On Atheros AR3012 Bluetooth                    | 17        | 0.66%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 17        | 0.66%   |
| Realtek Bluetooth Radio                             | 15        | 0.58%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 15        | 0.58%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 15        | 0.58%   |
| Foxconn / Hon Hai Bluetooth Device                  | 15        | 0.58%   |
| Broadcom HP Portable SoftSailing                    | 14        | 0.54%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 14        | 0.54%   |
| Apple Bluetooth Host Controller                     | 14        | 0.54%   |
| Toshiba Integrated Bluetooth HCI                    | 13        | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2697      | 66.41%  |
| AMD                                          | 606       | 14.92%  |
| Nvidia                                       | 512       | 12.61%  |
| C-Media Electronics                          | 25        | 0.62%   |
| Lenovo                                       | 19        | 0.47%   |
| Realtek Semiconductor                        | 18        | 0.44%   |
| Creative Technology                          | 18        | 0.44%   |
| Logitech                                     | 16        | 0.39%   |
| GN Netcom                                    | 16        | 0.39%   |
| Plantronics                                  | 12        | 0.3%    |
| Silicon Integrated Systems [SiS]             | 11        | 0.27%   |
| Hewlett-Packard                              | 10        | 0.25%   |
| VIA Technologies                             | 7         | 0.17%   |
| SteelSeries ApS                              | 7         | 0.17%   |
| Texas Instruments                            | 6         | 0.15%   |
| JMTek                                        | 6         | 0.15%   |
| Generalplus Technology                       | 6         | 0.15%   |
| Dell                                         | 6         | 0.15%   |
| Kingston Technology                          | 4         | 0.1%    |
| Focusrite-Novation                           | 4         | 0.1%    |
| ASUSTek Computer                             | 4         | 0.1%    |
| Sony                                         | 3         | 0.07%   |
| Sennheiser Communications                    | 3         | 0.07%   |
| Samson Technologies                          | 3         | 0.07%   |
| BEHRINGER International                      | 3         | 0.07%   |
| TTGK Technology                              | 2         | 0.05%   |
| M-Audio                                      | 2         | 0.05%   |
| KTMicro                                      | 2         | 0.05%   |
| DSEA A/S                                     | 2         | 0.05%   |
| AudioQuest                                   | 2         | 0.05%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.02%   |
| Yamaha                                       | 1         | 0.02%   |
| Turtle Beach                                 | 1         | 0.02%   |
| Trust                                        | 1         | 0.02%   |
| THX                                          | 1         | 0.02%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.02%   |
| Stadium USB microphone                       | 1         | 0.02%   |
| Silicon Motion                               | 1         | 0.02%   |
| SAVITECH                                     | 1         | 0.02%   |
| RODE Microphones                             | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 325       | 6.7%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 320       | 6.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 310       | 6.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 220       | 4.53%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 189       | 3.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 162       | 3.34%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 152       | 3.13%   |
| Intel 8 Series HD Audio Controller                                                                | 146       | 3.01%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 144       | 2.97%   |
| Intel Cannon Lake PCH cAVS                                                                        | 144       | 2.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 125       | 2.58%   |
| Intel Broadwell-U Audio Controller                                                                | 123       | 2.53%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 123       | 2.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 122       | 2.51%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 121       | 2.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 111       | 2.29%   |
| AMD FCH Azalia Controller                                                                         | 90        | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 88        | 1.81%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 86        | 1.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 84        | 1.73%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 79        | 1.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 77        | 1.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 67        | 1.38%   |
| Intel CM238 HD Audio Controller                                                                   | 65        | 1.34%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 60        | 1.24%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 60        | 1.24%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 52        | 1.07%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 52        | 1.07%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 51        | 1.05%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 49        | 1.01%   |
| Intel Comet Lake PCH cAVS                                                                         | 45        | 0.93%   |
| AMD Kabini HDMI/DP Audio                                                                          | 37        | 0.76%   |
| AMD Wrestler HDMI Audio                                                                           | 34        | 0.7%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 32        | 0.66%   |
| Nvidia Audio device                                                                               | 31        | 0.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 31        | 0.64%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 30        | 0.62%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 30        | 0.62%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 28        | 0.58%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 27        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 740       | 28.13%  |
| SK hynix                     | 548       | 20.83%  |
| Micron Technology            | 296       | 11.25%  |
| Kingston                     | 264       | 10.03%  |
| Unknown                      | 181       | 6.88%   |
| GOODRAM                      | 135       | 5.13%   |
| Crucial                      | 106       | 4.03%   |
| Ramaxel Technology           | 68        | 2.58%   |
| A-DATA Technology            | 53        | 2.01%   |
| Nanya Technology             | 46        | 1.75%   |
| Elpida                       | 45        | 1.71%   |
| Patriot                      | 19        | 0.72%   |
| Unknown (ABCD)               | 16        | 0.61%   |
| Unknown                      | 16        | 0.61%   |
| Corsair                      | 12        | 0.46%   |
| Wilk                         | 11        | 0.42%   |
| Qimonda                      | 10        | 0.38%   |
| G.Skill                      | 7         | 0.27%   |
| ASint Technology             | 7         | 0.27%   |
| 48spaces                     | 5         | 0.19%   |
| ff                           | 4         | 0.15%   |
| fef5                         | 4         | 0.15%   |
| 4ea5                         | 4         | 0.15%   |
| Unifosa                      | 3         | 0.11%   |
| Transcend                    | 3         | 0.11%   |
| Apacer                       | 3         | 0.11%   |
| Toshiba                      | 2         | 0.08%   |
| SHARETRONIC                  | 2         | 0.08%   |
| Patriot Memory (PDP Systems) | 2         | 0.08%   |
| ChangXin Memory              | 2         | 0.08%   |
| Unknown (8A02)               | 1         | 0.04%   |
| Unknown (768A)               | 1         | 0.04%   |
| Unknown (0x0E9D)             | 1         | 0.04%   |
| Team                         | 1         | 0.04%   |
| Swissbit                     | 1         | 0.04%   |
| Smart                        | 1         | 0.04%   |
| Silicon Power                | 1         | 0.04%   |
| PUSKILL                      | 1         | 0.04%   |
| PNY                          | 1         | 0.04%   |
| Netlist                      | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 39        | 1.38%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 38        | 1.35%   |
| Samsung RAM M471B5173BH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 37        | 1.31%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 32        | 1.13%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 30        | 1.06%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 29        | 1.03%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 29        | 1.03%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 29        | 1.03%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 29        | 1.03%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 29        | 1.03%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 28        | 0.99%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 28        | 0.99%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 27        | 0.96%   |
| GOODRAM RAM GR2666S464L19/16G 16GB SODIMM DDR4 2667MT/s             | 27        | 0.96%   |
| GOODRAM RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s             | 25        | 0.89%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 22        | 0.78%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 19        | 0.67%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 18        | 0.64%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 18        | 0.64%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s             | 17        | 0.6%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 17        | 0.6%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 17        | 0.6%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 17        | 0.6%    |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s               | 16        | 0.57%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 16        | 0.57%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s               | 16        | 0.57%   |
| Unknown                                                             | 16        | 0.57%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 15        | 0.53%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 15        | 0.53%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 15        | 0.53%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 15        | 0.53%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 14        | 0.5%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 14        | 0.5%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 14        | 0.5%    |
| GOODRAM RAM GR1600S3V64L11/8G 8GB SODIMM DDR3 1600MT/s              | 14        | 0.5%    |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 14        | 0.5%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 13        | 0.46%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s            | 13        | 0.46%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 12        | 0.43%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 12        | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 857       | 39.69%  |
| DDR3    | 827       | 38.3%   |
| DDR2    | 182       | 8.43%   |
| SDRAM   | 88        | 4.08%   |
| LPDDR4  | 79        | 3.66%   |
| LPDDR3  | 39        | 1.81%   |
| DDR5    | 29        | 1.34%   |
| LPDDR5  | 24        | 1.11%   |
| Unknown | 18        | 0.83%   |
| DDR     | 11        | 0.51%   |
| DRAM    | 5         | 0.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1961      | 92.59%  |
| Row Of Chips    | 121       | 5.71%   |
| Unknown         | 15        | 0.71%   |
| Chip            | 11        | 0.52%   |
| DIMM            | 9         | 0.42%   |
| Proprietary Car | 1         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 767       | 32.25%  |
| 4096    | 699       | 29.39%  |
| 2048    | 363       | 15.26%  |
| 16384   | 354       | 14.89%  |
| 1024    | 126       | 5.3%    |
| 32768   | 52        | 2.19%   |
| 512     | 10        | 0.42%   |
| Unknown | 4         | 0.17%   |
| 131072  | 1         | 0.04%   |
| 1536    | 1         | 0.04%   |
| 256     | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 598       | 25.39%  |
| 2667    | 400       | 16.99%  |
| 3200    | 356       | 15.12%  |
| 1334    | 152       | 6.45%   |
| 2400    | 138       | 5.86%   |
| 2133    | 102       | 4.33%   |
| 667     | 90        | 3.82%   |
| 1333    | 78        | 3.31%   |
| Unknown | 56        | 2.38%   |
| 4199    | 50        | 2.12%   |
| 1067    | 45        | 1.91%   |
| 800     | 44        | 1.87%   |
| 2048    | 30        | 1.27%   |
| 975     | 30        | 1.27%   |
| 6400    | 24        | 1.02%   |
| 4800    | 24        | 1.02%   |
| 533     | 24        | 1.02%   |
| 4267    | 23        | 0.98%   |
| 3266    | 18        | 0.76%   |
| 1867    | 15        | 0.64%   |
| 8400    | 11        | 0.47%   |
| 1066    | 10        | 0.42%   |
| 4266    | 8         | 0.34%   |
| 5600    | 6         | 0.25%   |
| 3733    | 6         | 0.25%   |
| 400     | 4         | 0.17%   |
| 333     | 4         | 0.17%   |
| 2933    | 3         | 0.13%   |
| 1639    | 2         | 0.08%   |
| 2134    | 1         | 0.04%   |
| 1777    | 1         | 0.04%   |
| 1776    | 1         | 0.04%   |
| 933     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 11        | 44%     |
| Samsung Electronics   | 5         | 20%     |
| Canon                 | 3         | 12%     |
| Seiko Epson           | 2         | 8%      |
| Zebra                 | 1         | 4%      |
| Xerox                 | 1         | 4%      |
| Lexmark International | 1         | 4%      |
| Brother Industries    | 1         | 4%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung M2020 Series                    | 2         | 8%      |
| HP Deskjet F2280 series                 | 2         | 8%      |
| Zebra ZTC GX420t                        | 1         | 4%      |
| Xerox Phaser 6000B                      | 1         | 4%      |
| Seiko Epson ET-2600 Series              | 1         | 4%      |
| Seiko Epson AL-M310DN                   | 1         | 4%      |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 4%      |
| Samsung SCX-6545 Series                 | 1         | 4%      |
| Samsung SCX-3400 Series                 | 1         | 4%      |
| Lexmark International E260dn            | 1         | 4%      |
| HP LaserJet P1102                       | 1         | 4%      |
| HP LaserJet P1005                       | 1         | 4%      |
| HP LaserJet 1020                        | 1         | 4%      |
| HP LaserJet 1018                        | 1         | 4%      |
| HP Ink Tank Wireless 410 series         | 1         | 4%      |
| HP Deskjet Ink Advant K209a-z           | 1         | 4%      |
| HP Deskjet D1500 series                 | 1         | 4%      |
| HP Deskjet 3540 series                  | 1         | 4%      |
| HP Deskjet 2540 series                  | 1         | 4%      |
| Canon PIXMA MG5600 Series               | 1         | 4%      |
| Canon PIXMA MG3000 series               | 1         | 4%      |
| Canon LiDE 400                          | 1         | 4%      |
| Brother DCP-1610W                       | 1         | 4%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Canon                  | 2         | 50%     |
| Plustek                | 1         | 25%     |
| Microtek International | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Plustek OpticSlim 1200 Scanner         | 1         | 25%     |
| Microtek International USB1200 Scanner | 1         | 25%     |
| Canon CanoScan N670U/N676U/LiDE 20     | 1         | 25%     |
| Canon CanoScan N1240U/LiDE 30          | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 691       | 24.26%  |
| IMC Networks                           | 285       | 10.01%  |
| Microdia                               | 283       | 9.94%   |
| Realtek Semiconductor                  | 262       | 9.2%    |
| Sunplus Innovation Technology          | 160       | 5.62%   |
| Bison Electronics                      | 156       | 5.48%   |
| Quanta                                 | 136       | 4.78%   |
| Suyin                                  | 119       | 4.18%   |
| Cheng Uei Precision Industry (Foxlink) | 94        | 3.3%    |
| Syntek                                 | 91        | 3.2%    |
| Acer                                   | 90        | 3.16%   |
| Lite-On Technology                     | 67        | 2.35%   |
| Silicon Motion                         | 63        | 2.21%   |
| Luxvisions Innotech Limited            | 37        | 1.3%    |
| Ricoh                                  | 35        | 1.23%   |
| Logitech                               | 33        | 1.16%   |
| Apple                                  | 31        | 1.09%   |
| Alcor Micro                            | 31        | 1.09%   |
| Lenovo                                 | 29        | 1.02%   |
| Sonix Technology                       | 18        | 0.63%   |
| Z-Star Microelectronics                | 16        | 0.56%   |
| DigiTech                               | 13        | 0.46%   |
| Intel                                  | 11        | 0.39%   |
| Primax Electronics                     | 10        | 0.35%   |
| Creative Technology                    | 10        | 0.35%   |
| ALi                                    | 10        | 0.35%   |
| Samsung Electronics                    | 9         | 0.32%   |
| Importek                               | 6         | 0.21%   |
| SunplusIT                              | 5         | 0.18%   |
| Microsoft                              | 5         | 0.18%   |
| Generalplus Technology                 | 5         | 0.18%   |
| Sunplus Technology                     | 3         | 0.11%   |
| Alpha Imaging Technology               | 3         | 0.11%   |
| USB Camera                             | 2         | 0.07%   |
| Trust                                  | 2         | 0.07%   |
| OmniVision Technologies                | 2         | 0.07%   |
| MacroSilicon                           | 2         | 0.07%   |
| Foxconn / Hon Hai                      | 2         | 0.07%   |
| Cubeternet                             | 2         | 0.07%   |
| Xiaomi                                 | 1         | 0.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 138       | 4.83%   |
| Microdia Integrated_Webcam_HD                       | 103       | 3.6%    |
| Realtek Integrated_Webcam_HD                        | 92        | 3.22%   |
| IMC Networks Integrated Camera                      | 77        | 2.69%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 71        | 2.48%   |
| Sunplus Integrated_Webcam_HD                        | 59        | 2.06%   |
| Chicony Lenovo EasyCamera                           | 50        | 1.75%   |
| Microdia Integrated Webcam                          | 48        | 1.68%   |
| Chicony HD WebCam                                   | 47        | 1.64%   |
| Bison Lenovo EasyCamera                             | 42        | 1.47%   |
| Syntek Integrated Camera                            | 38        | 1.33%   |
| Suyin Integrated_Webcam_HD                          | 36        | 1.26%   |
| Syntek Lenovo EasyCamera                            | 33        | 1.15%   |
| Chicony HP HD Camera                                | 33        | 1.15%   |
| Bison Integrated Camera                             | 33        | 1.15%   |
| Realtek USB Camera                                  | 32        | 1.12%   |
| Realtek Lenovo EasyCamera                           | 31        | 1.08%   |
| Lite-On Integrated Camera                           | 31        | 1.08%   |
| Quanta HP TrueVision HD Camera                      | 28        | 0.98%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 23        | 0.8%    |
| Acer Integrated Camera                              | 23        | 0.8%    |
| Chicony USB2.0 HD UVC WebCam                        | 22        | 0.77%   |
| Bison Lenovo Integrated Webcam                      | 22        | 0.77%   |
| Quanta HD User Facing                               | 21        | 0.73%   |
| Microdia Laptop_Integrated_Webcam_HD                | 21        | 0.73%   |
| Acer SunplusIT Integrated Camera                    | 21        | 0.73%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 20        | 0.7%    |
| Realtek Integrated Webcam                           | 20        | 0.7%    |
| Chicony USB2.0 VGA UVC WebCam                       | 18        | 0.63%   |
| Chicony USB 2.0 Camera                              | 18        | 0.63%   |
| Chicony Integrated Camera (1280x720@30)             | 18        | 0.63%   |
| IMC Networks Integrated Webcam                      | 17        | 0.59%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 17        | 0.59%   |
| Sonix USB2.0 HD UVC WebCam                          | 16        | 0.56%   |
| Lite-On HP HD Camera                                | 16        | 0.56%   |
| Alcor Micro USB 2.0 Camera                          | 16        | 0.56%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 15        | 0.52%   |
| IMC Networks UVC VGA Webcam                         | 15        | 0.52%   |
| Sunplus HD WebCam                                   | 14        | 0.49%   |
| Chicony VGA WebCam                                  | 14        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 218       | 37.39%  |
| Synaptics                          | 134       | 22.98%  |
| Shenzhen Goodix Technology         | 72        | 12.35%  |
| AuthenTec                          | 64        | 10.98%  |
| Upek                               | 38        | 6.52%   |
| Elan Microelectronics              | 24        | 4.12%   |
| LighTuning Technology              | 18        | 3.09%   |
| STMicroelectronics                 | 13        | 2.23%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.34%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 45        | 7.72%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 44        | 7.55%   |
| Shenzhen Goodix  FingerPrint Device                                        | 43        | 7.38%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 36        | 6.17%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 34        | 5.83%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 28        | 4.8%    |
| AuthenTec AES2810                                                          | 27        | 4.63%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 25        | 4.29%   |
| Shenzhen Goodix Fingerprint Reader                                         | 22        | 3.77%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 18        | 3.09%   |
| Elan ELAN:Fingerprint                                                      | 16        | 2.74%   |
| Synaptics Fingerprint reader [HP G6]                                       | 15        | 2.57%   |
| Validity Sensors VFS491                                                    | 14        | 2.4%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 2.4%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 13        | 2.23%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 13        | 2.23%   |
| STMicroelectronics Fingerprint Reader                                      | 13        | 2.23%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 12        | 2.06%   |
| Validity Sensors Synaptics WBDI                                            | 12        | 2.06%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 1.89%   |
| Validity Sensors Fingerprint scanner                                       | 11        | 1.89%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 9         | 1.54%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 1.37%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 1.37%   |
| Elan ELAN:ARM-M4                                                           | 8         | 1.37%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 1.2%    |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.2%    |
| AuthenTec AES1600                                                          | 7         | 1.2%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.86%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 0.86%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 0.86%   |
| LighTuning Fingerprint Reader                                              | 5         | 0.86%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 0.86%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.69%   |
| Synaptics WBDI                                                             | 4         | 0.69%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.69%   |
| Synaptics  WBDI                                                            | 4         | 0.69%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 0.69%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 0.51%   |
| Synaptics WBDI Device                                                      | 3         | 0.51%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 258       | 58.24%  |
| Alcor Micro               | 89        | 20.09%  |
| O2 Micro                  | 46        | 10.38%  |
| Upek                      | 22        | 4.97%   |
| Lenovo                    | 21        | 4.74%   |
| Gemalto (was Gemplus)     | 4         | 0.9%    |
| SCM Microsystems          | 1         | 0.23%   |
| Clay Logic                | 1         | 0.23%   |
| Aladdin Knowledge Systems | 1         | 0.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 87        | 19.64%  |
| Broadcom BCM5880 Secure Applications Processor                               | 82        | 18.51%  |
| Broadcom 58200                                                               | 69        | 15.58%  |
| Broadcom 5880                                                                | 59        | 13.32%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 47        | 10.61%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 39        | 8.8%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 22        | 4.97%   |
| Lenovo Integrated Smart Card Reader                                          | 21        | 4.74%   |
| O2 Micro Oz776 SmartCard Reader                                              | 7         | 1.58%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.68%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.23%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.23%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.23%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.23%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.23%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.23%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1946      | 57.44%  |
| 1     | 1127      | 33.26%  |
| 2     | 263       | 7.76%   |
| 3     | 42        | 1.24%   |
| 5     | 3         | 0.09%   |
| 4     | 3         | 0.09%   |
| 7     | 2         | 0.06%   |
| 6     | 2         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 576       | 32.84%  |
| Chipcard                 | 400       | 22.81%  |
| Graphics card            | 359       | 20.47%  |
| Net/wireless             | 119       | 6.78%   |
| Multimedia controller    | 59        | 3.36%   |
| Storage                  | 53        | 3.02%   |
| Bluetooth                | 51        | 2.91%   |
| Camera                   | 37        | 2.11%   |
| Communication controller | 29        | 1.65%   |
| Card reader              | 18        | 1.03%   |
| Sound                    | 15        | 0.86%   |
| Modem                    | 9         | 0.51%   |
| Firewire controller      | 8         | 0.46%   |
| Net/ethernet             | 6         | 0.34%   |
| Flash memory             | 5         | 0.29%   |
| Dvb card                 | 3         | 0.17%   |
| Network                  | 2         | 0.11%   |
| Wireless                 | 1         | 0.06%   |
| Unclassified device      | 1         | 0.06%   |
| Tv card                  | 1         | 0.06%   |
| Storage/raid             | 1         | 0.06%   |
| Storage/ide              | 1         | 0.06%   |


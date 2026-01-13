Linux in Uruguay - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Uruguay.

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

Total: 379

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | OMEN by Laptop              | [0bd5286a7b](https://linux-hardware.org/?probe=0bd5286a7b) | Dec 26, 2025 |
| HP            | Laptop 17-ca1xxx            | [3d419fcada](https://linux-hardware.org/?probe=3d419fcada) | Nov 30, 2025 |
| HP            | Laptop 17-ca1xxx            | [06ebe83264](https://linux-hardware.org/?probe=06ebe83264) | Nov 29, 2025 |
| HP            | OMEN by Laptop 15t-dc100    | [0c8c8897cd](https://linux-hardware.org/?probe=0c8c8897cd) | Nov 25, 2025 |
| Acer          | Aspire 5736Z                | [a1f8c828e4](https://linux-hardware.org/?probe=a1f8c828e4) | Nov 23, 2025 |
| Dell          | Latitude E6420              | [b2fc183035](https://linux-hardware.org/?probe=b2fc183035) | Nov 13, 2025 |
| HP            | Laptop 17z-cp300            | [c0dc830c0e](https://linux-hardware.org/?probe=c0dc830c0e) | Oct 28, 2025 |
| HP            | Laptop 17z-cp300            | [80b34c767f](https://linux-hardware.org/?probe=80b34c767f) | Oct 28, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [9b656f44e8](https://linux-hardware.org/?probe=9b656f44e8) | Oct 24, 2025 |
| ASUSTek       | ZenBook UX434FLC_UX433FL... | [813d8cbb49](https://linux-hardware.org/?probe=813d8cbb49) | Oct 19, 2025 |
| Apple         | MacBookAir6,2               | [14a2c7e967](https://linux-hardware.org/?probe=14a2c7e967) | Oct 17, 2025 |
| HP            | Compaq Presario CQ40        | [06fa762ed5](https://linux-hardware.org/?probe=06fa762ed5) | Oct 15, 2025 |
| JP-IK         | T140J_Sargas_2025           | [53844ab999](https://linux-hardware.org/?probe=53844ab999) | Oct 14, 2025 |
| ASUSTek       | ZenBook UX434FLC_UX433FL... | [7a2d4bbfcc](https://linux-hardware.org/?probe=7a2d4bbfcc) | Oct 08, 2025 |
| Acer          | AOA110                      | [f94c7585be](https://linux-hardware.org/?probe=f94c7585be) | Oct 07, 2025 |
| HP            | Laptop 17-ca1xxx            | [77bb292fd1](https://linux-hardware.org/?probe=77bb292fd1) | Oct 04, 2025 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [637b1aa13a](https://linux-hardware.org/?probe=637b1aa13a) | Oct 03, 2025 |
| Apple         | MacBookAir6,2               | [695f6312db](https://linux-hardware.org/?probe=695f6312db) | Oct 01, 2025 |
| HP            | Stream Laptop 14-ax1xxx     | [cc9cb53cc6](https://linux-hardware.org/?probe=cc9cb53cc6) | Sep 28, 2025 |
| Lenovo        | Y50-70 20378                | [2dbf085806](https://linux-hardware.org/?probe=2dbf085806) | Sep 22, 2025 |
| ECS           | SF20PA2                     | [acf2b0e1ee](https://linux-hardware.org/?probe=acf2b0e1ee) | Sep 21, 2025 |
| Dell          | Latitude 5414               | [8e97fe3379](https://linux-hardware.org/?probe=8e97fe3379) | Sep 09, 2025 |
| ECS           | SF20GM3                     | [bef6128257](https://linux-hardware.org/?probe=bef6128257) | Aug 21, 2025 |
| Unknown       | H719-Acrab                  | [6e1a61db62](https://linux-hardware.org/?probe=6e1a61db62) | Aug 21, 2025 |
| Positivo      | 11Cle2-N2840 V1.0           | [71cbce8939](https://linux-hardware.org/?probe=71cbce8939) | Aug 19, 2025 |
| Dell          | Latitude 5420               | [8d40a3eef5](https://linux-hardware.org/?probe=8d40a3eef5) | Aug 16, 2025 |
| Dell          | Latitude 5420               | [213dd91e0a](https://linux-hardware.org/?probe=213dd91e0a) | Aug 16, 2025 |
| HP            | Laptop 15-bw0xx             | [088d3d5a46](https://linux-hardware.org/?probe=088d3d5a46) | Aug 13, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [4f51734688](https://linux-hardware.org/?probe=4f51734688) | Aug 04, 2025 |
| Lenovo        | Unknown                     | [f3da4bd328](https://linux-hardware.org/?probe=f3da4bd328) | Aug 04, 2025 |
| HP            | Laptop 14-dq1xxx            | [8418059ec1](https://linux-hardware.org/?probe=8418059ec1) | Aug 02, 2025 |
| HP            | Laptop 17-ca1xxx            | [1d96ad3429](https://linux-hardware.org/?probe=1d96ad3429) | Jul 31, 2025 |
| HP            | Laptop 17-ca1xxx            | [ee3f956ec4](https://linux-hardware.org/?probe=ee3f956ec4) | Jul 31, 2025 |
| Toshiba       | Satellite C55-C             | [7c309f6e91](https://linux-hardware.org/?probe=7c309f6e91) | Jul 08, 2025 |
| Dell          | Inspiron 15-7568            | [201fe1ec71](https://linux-hardware.org/?probe=201fe1ec71) | Jun 26, 2025 |
| Dell          | Inspiron 15-7568            | [014f834099](https://linux-hardware.org/?probe=014f834099) | Jun 26, 2025 |
| HP            | Casablanca H710             | [b8efd38b1f](https://linux-hardware.org/?probe=b8efd38b1f) | Jun 24, 2025 |
| HP            | Casablanca H710             | [16148a0270](https://linux-hardware.org/?probe=16148a0270) | Jun 24, 2025 |
| ASUSTek       | ASUS Vivobook S 14 S5406... | [a1c0fb52f6](https://linux-hardware.org/?probe=a1c0fb52f6) | Jun 07, 2025 |
| Toshiba       | Satellite B40-A             | [b8abf8dc1b](https://linux-hardware.org/?probe=b8abf8dc1b) | Jun 07, 2025 |
| Toshiba       | Satellite B40-A             | [491c21c514](https://linux-hardware.org/?probe=491c21c514) | Jun 07, 2025 |
| Acer          | Swift SF314-54              | [e0e15b04f9](https://linux-hardware.org/?probe=e0e15b04f9) | Jun 04, 2025 |
| Acer          | Swift SF314-54              | [57c318855f](https://linux-hardware.org/?probe=57c318855f) | Jun 04, 2025 |
| Dell          | G16 7620                    | [2a1ef16376](https://linux-hardware.org/?probe=2a1ef16376) | May 25, 2025 |
| Dell          | G16 7620                    | [102110ffb7](https://linux-hardware.org/?probe=102110ffb7) | May 25, 2025 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [1142416d54](https://linux-hardware.org/?probe=1142416d54) | May 11, 2025 |
| Acer          | Aspire 5736Z                | [47c8b608b1](https://linux-hardware.org/?probe=47c8b608b1) | May 08, 2025 |
| MSI           | Delta 15 A5EFK              | [921f6813c9](https://linux-hardware.org/?probe=921f6813c9) | May 06, 2025 |
| MSI           | Delta 15 A5EFK              | [57b8a4c1d3](https://linux-hardware.org/?probe=57b8a4c1d3) | May 06, 2025 |
| ASUSTek       | X550CA                      | [d4f47ba8c1](https://linux-hardware.org/?probe=d4f47ba8c1) | Apr 29, 2025 |
| HP            | EliteBook 820 G3            | [13861ad53e](https://linux-hardware.org/?probe=13861ad53e) | Apr 28, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [f15b63d1e6](https://linux-hardware.org/?probe=f15b63d1e6) | Apr 25, 2025 |
| HP            | Pavilion dm1                | [9cabc1f3cd](https://linux-hardware.org/?probe=9cabc1f3cd) | Apr 23, 2025 |
| Toshiba       | Satellite P55W-C            | [bb22092e1a](https://linux-hardware.org/?probe=bb22092e1a) | Apr 20, 2025 |
| Lenovo        | 0B98401 PRO                 | [7f4b27be29](https://linux-hardware.org/?probe=7f4b27be29) | Apr 06, 2025 |
| HP            | Stream Notebook PC 11       | [d5d92fe1a4](https://linux-hardware.org/?probe=d5d92fe1a4) | Mar 14, 2025 |
| Lenovo        | ThinkPad A275 20KCS08300    | [5ac7159c57](https://linux-hardware.org/?probe=5ac7159c57) | Feb 18, 2025 |
| ASUSTek       | K84L                        | [6cac2213fa](https://linux-hardware.org/?probe=6cac2213fa) | Feb 17, 2025 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [05245028f4](https://linux-hardware.org/?probe=05245028f4) | Feb 16, 2025 |
| Lenovo        | G405 20239                  | [6d50623b26](https://linux-hardware.org/?probe=6d50623b26) | Feb 15, 2025 |
| Lenovo        | G405 20239                  | [3e072dbeae](https://linux-hardware.org/?probe=3e072dbeae) | Feb 15, 2025 |
| HP            | Laptop 15-ef2xxx            | [5028af90ab](https://linux-hardware.org/?probe=5028af90ab) | Feb 14, 2025 |
| HP            | Dragonfly Pro ONE           | [7da644cb5b](https://linux-hardware.org/?probe=7da644cb5b) | Jan 18, 2025 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [6093c31e0a](https://linux-hardware.org/?probe=6093c31e0a) | Jan 13, 2025 |
| ECS           | SF20PA2                     | [2c29a0d94a](https://linux-hardware.org/?probe=2c29a0d94a) | Jan 13, 2025 |
| Dell          | Latitude 3340               | [458695801e](https://linux-hardware.org/?probe=458695801e) | Jan 07, 2025 |
| Dell          | Latitude 3340               | [083c2f79ec](https://linux-hardware.org/?probe=083c2f79ec) | Jan 05, 2025 |
| HP            | Dragonfly Pro ONE           | [b5d99e3a51](https://linux-hardware.org/?probe=b5d99e3a51) | Dec 14, 2024 |
| Dell          | Inspiron 15-3567            | [e1b919328b](https://linux-hardware.org/?probe=e1b919328b) | Dec 13, 2024 |
| Dell          | Inspiron 15-3567            | [618266a26d](https://linux-hardware.org/?probe=618266a26d) | Dec 12, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [49f7b2645e](https://linux-hardware.org/?probe=49f7b2645e) | Nov 28, 2024 |
| HP            | Dragonfly Pro ONE           | [dbd0482a3f](https://linux-hardware.org/?probe=dbd0482a3f) | Nov 26, 2024 |
| HP            | Laptop 17z-cp300            | [be49e0c290](https://linux-hardware.org/?probe=be49e0c290) | Nov 23, 2024 |
| HP            | Laptop 17z-cp300            | [4090b82a10](https://linux-hardware.org/?probe=4090b82a10) | Nov 23, 2024 |
| HP            | Dragonfly Pro ONE           | [fa88478d29](https://linux-hardware.org/?probe=fa88478d29) | Nov 21, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [2ba55cd21c](https://linux-hardware.org/?probe=2ba55cd21c) | Nov 12, 2024 |
| Acer          | Aspire A515-52G             | [9493eace9d](https://linux-hardware.org/?probe=9493eace9d) | Nov 11, 2024 |
| HP            | EliteBook 820 G3            | [abbc44e591](https://linux-hardware.org/?probe=abbc44e591) | Nov 06, 2024 |
| GMKtec        | NucBox5                     | [3d6b2c6fe2](https://linux-hardware.org/?probe=3d6b2c6fe2) | Oct 23, 2024 |
| Chuwi         | CoreBook X                  | [1cdcd982f9](https://linux-hardware.org/?probe=1cdcd982f9) | Oct 13, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0126b569bf](https://linux-hardware.org/?probe=0126b569bf) | Oct 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [95bc0c90e1](https://linux-hardware.org/?probe=95bc0c90e1) | Sep 23, 2024 |
| Chuwi         | Unknown                     | [45922bbe51](https://linux-hardware.org/?probe=45922bbe51) | Sep 19, 2024 |
| HP            | Dragonfly Pro ONE           | [ea5a903bc7](https://linux-hardware.org/?probe=ea5a903bc7) | Sep 13, 2024 |
| HP            | Dragonfly Pro ONE           | [816005b8fa](https://linux-hardware.org/?probe=816005b8fa) | Sep 10, 2024 |
| Google        | Dragonair                   | [0d92bf03a8](https://linux-hardware.org/?probe=0d92bf03a8) | Sep 06, 2024 |
| HP            | Dragonfly Pro ONE           | [24e3709aa5](https://linux-hardware.org/?probe=24e3709aa5) | Aug 29, 2024 |
| Toshiba       | Satellite L755              | [87f617e4d9](https://linux-hardware.org/?probe=87f617e4d9) | Aug 25, 2024 |
| HP            | Laptop 15-bw0xx             | [08d216ac0e](https://linux-hardware.org/?probe=08d216ac0e) | Aug 20, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [5a5474a9d8](https://linux-hardware.org/?probe=5a5474a9d8) | Aug 19, 2024 |
| HP            | Dragonfly Pro ONE           | [1728bcdfbe](https://linux-hardware.org/?probe=1728bcdfbe) | Aug 16, 2024 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [8c59185bfa](https://linux-hardware.org/?probe=8c59185bfa) | Aug 16, 2024 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [9153a53950](https://linux-hardware.org/?probe=9153a53950) | Aug 16, 2024 |
| JP-IK         | T140J_Sargas_2024           | [1e8afe45e8](https://linux-hardware.org/?probe=1e8afe45e8) | Aug 16, 2024 |
| JP-IK         | T140J_Sargas_2024           | [db3b8125ed](https://linux-hardware.org/?probe=db3b8125ed) | Aug 15, 2024 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [e7ab69fde0](https://linux-hardware.org/?probe=e7ab69fde0) | Aug 11, 2024 |
| HP            | Dragonfly Pro ONE           | [49b1242209](https://linux-hardware.org/?probe=49b1242209) | Aug 08, 2024 |
| Acer          | Aspire 5715Z                | [32b3360c63](https://linux-hardware.org/?probe=32b3360c63) | Aug 07, 2024 |
| Acer          | Aspire 5715Z                | [387c8e5fe4](https://linux-hardware.org/?probe=387c8e5fe4) | Aug 07, 2024 |
| HP            | Dragonfly Pro ONE           | [5ff11d8bb4](https://linux-hardware.org/?probe=5ff11d8bb4) | Aug 06, 2024 |
| Acer          | Aspire A315-59              | [1dfe36ecd9](https://linux-hardware.org/?probe=1dfe36ecd9) | Jul 26, 2024 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [73cc6974f3](https://linux-hardware.org/?probe=73cc6974f3) | Jul 13, 2024 |
| Dell          | Inspiron 15 3520            | [d721bec9c8](https://linux-hardware.org/?probe=d721bec9c8) | Jul 06, 2024 |
| Lenovo        | ThinkPad T61 7660A25        | [d9474a6035](https://linux-hardware.org/?probe=d9474a6035) | Jul 06, 2024 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [02da08cbf1](https://linux-hardware.org/?probe=02da08cbf1) | Jul 02, 2024 |
| Lenovo        | ThinkPad T420 4236NUG       | [bd25a31252](https://linux-hardware.org/?probe=bd25a31252) | Jun 30, 2024 |
| Lenovo        | ThinkPad T61 7660A25        | [e8e9fb2bf7](https://linux-hardware.org/?probe=e8e9fb2bf7) | Jun 24, 2024 |
| HP            | Pavilion dv2000 (GM691LA... | [de1b028bbb](https://linux-hardware.org/?probe=de1b028bbb) | Jun 24, 2024 |
| Dell          | Inspiron 14 5425            | [3fb17595e8](https://linux-hardware.org/?probe=3fb17595e8) | Jun 16, 2024 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [36a8060749](https://linux-hardware.org/?probe=36a8060749) | Jun 03, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | [58495c89d8](https://linux-hardware.org/?probe=58495c89d8) | May 25, 2024 |
| Dell          | Latitude 5531               | [e562f11ed3](https://linux-hardware.org/?probe=e562f11ed3) | May 20, 2024 |
| Google        | Phaser                      | [feb45bf2a2](https://linux-hardware.org/?probe=feb45bf2a2) | May 02, 2024 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [859396f855](https://linux-hardware.org/?probe=859396f855) | Apr 30, 2024 |
| Samsung       | RV411/RV511/E3511/S3511/... | [4d6a9bb700](https://linux-hardware.org/?probe=4d6a9bb700) | Apr 12, 2024 |
| Samsung       | RV411/RV511/E3511/S3511/... | [e108ca29d2](https://linux-hardware.org/?probe=e108ca29d2) | Apr 12, 2024 |
| HP            | Presario V6000 (GH918EA#... | [19c9124453](https://linux-hardware.org/?probe=19c9124453) | Apr 10, 2024 |
| MSI           | Unknown                     | [a975d469da](https://linux-hardware.org/?probe=a975d469da) | Mar 19, 2024 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [0e8d4b681b](https://linux-hardware.org/?probe=0e8d4b681b) | Mar 11, 2024 |
| HP            | Pavilion Sleekbook 14 PC    | [225e16d7af](https://linux-hardware.org/?probe=225e16d7af) | Mar 05, 2024 |
| Valve         | Jupiter                     | [30c94fd159](https://linux-hardware.org/?probe=30c94fd159) | Feb 29, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [0973b9cfb2](https://linux-hardware.org/?probe=0973b9cfb2) | Feb 29, 2024 |
| Lenovo        | G480 20156                  | [8ffe1342b1](https://linux-hardware.org/?probe=8ffe1342b1) | Feb 16, 2024 |
| Acer          | Aspire A315-59              | [51886537be](https://linux-hardware.org/?probe=51886537be) | Feb 09, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1fcf02a6c3](https://linux-hardware.org/?probe=1fcf02a6c3) | Feb 06, 2024 |
| HP            | Stream Laptop 14-ax0XX      | [d83dd7b361](https://linux-hardware.org/?probe=d83dd7b361) | Feb 05, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [33e55cd5c5](https://linux-hardware.org/?probe=33e55cd5c5) | Feb 03, 2024 |
| HP            | Laptop 15-bw0xx             | [118dcfd484](https://linux-hardware.org/?probe=118dcfd484) | Jan 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [88f29ebedf](https://linux-hardware.org/?probe=88f29ebedf) | Jan 24, 2024 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [da8a8d5994](https://linux-hardware.org/?probe=da8a8d5994) | Dec 28, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [418992da4d](https://linux-hardware.org/?probe=418992da4d) | Dec 27, 2023 |
| Dell          | Inspiron 1564               | [a1945990cc](https://linux-hardware.org/?probe=a1945990cc) | Dec 24, 2023 |
| Dell          | Inspiron 1564               | [e02428db4a](https://linux-hardware.org/?probe=e02428db4a) | Dec 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [0f2cad4391](https://linux-hardware.org/?probe=0f2cad4391) | Dec 22, 2023 |
| Standard      | SF20BA2                     | [431580b18d](https://linux-hardware.org/?probe=431580b18d) | Dec 19, 2023 |
| HP            | Pavilion Notebook           | [81baeeb4c6](https://linux-hardware.org/?probe=81baeeb4c6) | Dec 12, 2023 |
| ASUSTek       | UX305CA                     | [6bac81f943](https://linux-hardware.org/?probe=6bac81f943) | Dec 06, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [248ac55d99](https://linux-hardware.org/?probe=248ac55d99) | Nov 29, 2023 |
| HP            | Laptop 15-dy2xxx            | [858c641fcf](https://linux-hardware.org/?probe=858c641fcf) | Nov 26, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [2188d0c4b8](https://linux-hardware.org/?probe=2188d0c4b8) | Nov 25, 2023 |
| Samsung       | 550P5C/550P7C               | [b7294ed55c](https://linux-hardware.org/?probe=b7294ed55c) | Nov 20, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [eb4b6a5c65](https://linux-hardware.org/?probe=eb4b6a5c65) | Nov 15, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [339062b95b](https://linux-hardware.org/?probe=339062b95b) | Nov 15, 2023 |
| Lenovo        | ThinkPad T420 42361H7       | [0f1bd55fbf](https://linux-hardware.org/?probe=0f1bd55fbf) | Nov 09, 2023 |
| Razer         | Blade                       | [e9ad529ed4](https://linux-hardware.org/?probe=e9ad529ed4) | Nov 01, 2023 |
| HP            | Laptop 14-ck0xxx            | [8ef0f47332](https://linux-hardware.org/?probe=8ef0f47332) | Oct 20, 2023 |
| GPU Compan... | GWTN156-2BK                 | [f4eec82fb9](https://linux-hardware.org/?probe=f4eec82fb9) | Oct 09, 2023 |
| Razer         | Blade                       | [b3b2eb7db8](https://linux-hardware.org/?probe=b3b2eb7db8) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4398558915](https://linux-hardware.org/?probe=4398558915) | Sep 19, 2023 |
| ASUSTek       | X542UQ                      | [6793d8c052](https://linux-hardware.org/?probe=6793d8c052) | Sep 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [a51361ebb2](https://linux-hardware.org/?probe=a51361ebb2) | Sep 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [00cbde2fb9](https://linux-hardware.org/?probe=00cbde2fb9) | Sep 12, 2023 |
| GPU Compan... | GWTN156-9                   | [4c8ea16ab2](https://linux-hardware.org/?probe=4c8ea16ab2) | Aug 30, 2023 |
| Chuwi         | GemiBook Pro                | [62b31c86bb](https://linux-hardware.org/?probe=62b31c86bb) | Aug 22, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [a435538cb2](https://linux-hardware.org/?probe=a435538cb2) | Aug 20, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [0dc75dae26](https://linux-hardware.org/?probe=0dc75dae26) | Aug 18, 2023 |
| HP            | 14                          | [8692626574](https://linux-hardware.org/?probe=8692626574) | Aug 09, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [46ca3ef1f4](https://linux-hardware.org/?probe=46ca3ef1f4) | Aug 01, 2023 |
| HP            | Laptop 15-dy2xxx            | [bbe4e49261](https://linux-hardware.org/?probe=bbe4e49261) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [d16a211675](https://linux-hardware.org/?probe=d16a211675) | Jul 21, 2023 |
| Dell          | Latitude E5420              | [be15c1e3d1](https://linux-hardware.org/?probe=be15c1e3d1) | Jul 20, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [0fc498ccfb](https://linux-hardware.org/?probe=0fc498ccfb) | Jul 06, 2023 |
| Acer          | Aspire E1-571               | [d0258b4ca5](https://linux-hardware.org/?probe=d0258b4ca5) | Jul 06, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | [ad76ecf5a9](https://linux-hardware.org/?probe=ad76ecf5a9) | Jul 01, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | [b8bab5a2e6](https://linux-hardware.org/?probe=b8bab5a2e6) | Jul 01, 2023 |
| Acer          | One S1002                   | [f7b8d25603](https://linux-hardware.org/?probe=f7b8d25603) | Jun 21, 2023 |
| Fujitsu       | LIFEBOOK E734               | [3742e80123](https://linux-hardware.org/?probe=3742e80123) | Jun 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [3cfa2bccb7](https://linux-hardware.org/?probe=3cfa2bccb7) | Jun 08, 2023 |
| HP            | Pavilion g6                 | [12b1174ce8](https://linux-hardware.org/?probe=12b1174ce8) | Jun 08, 2023 |
| Toshiba       | Satellite C645D             | [085994472d](https://linux-hardware.org/?probe=085994472d) | May 28, 2023 |
| HP            | Stream Notebook             | [74d40533fc](https://linux-hardware.org/?probe=74d40533fc) | May 24, 2023 |
| Apple         | MacBookPro9,2               | [6855a79270](https://linux-hardware.org/?probe=6855a79270) | May 23, 2023 |
| Acer          | Aspire 4315                 | [8a25a16dfa](https://linux-hardware.org/?probe=8a25a16dfa) | May 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [7af74c5864](https://linux-hardware.org/?probe=7af74c5864) | May 18, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [0fd753db6d](https://linux-hardware.org/?probe=0fd753db6d) | May 16, 2023 |
| HP            | Notebook                    | [c14e7a41cf](https://linux-hardware.org/?probe=c14e7a41cf) | May 13, 2023 |
| HP            | Notebook                    | [726fa4fcd1](https://linux-hardware.org/?probe=726fa4fcd1) | May 13, 2023 |
| Dell          | Latitude 5530               | [ade218e4fa](https://linux-hardware.org/?probe=ade218e4fa) | May 11, 2023 |
| Toshiba       | Satellite L45-B             | [8f1db96b6f](https://linux-hardware.org/?probe=8f1db96b6f) | Apr 29, 2023 |
| HP            | 240 G4                      | [997e6e6a0b](https://linux-hardware.org/?probe=997e6e6a0b) | Apr 24, 2023 |
| HP            | 240 G4                      | [887b406c56](https://linux-hardware.org/?probe=887b406c56) | Apr 22, 2023 |
| Standard      | SF20BA2                     | [17763324b6](https://linux-hardware.org/?probe=17763324b6) | Apr 08, 2023 |
| Intel         | EF20                        | [120257faca](https://linux-hardware.org/?probe=120257faca) | Apr 04, 2023 |
| Acer          | Aspire 4315                 | [0bf18c8c90](https://linux-hardware.org/?probe=0bf18c8c90) | Mar 26, 2023 |
| Toshiba       | Satellite C75D-B            | [1ff56ed31f](https://linux-hardware.org/?probe=1ff56ed31f) | Mar 19, 2023 |
| Dell          | Latitude 7310               | [6b5de5fe3c](https://linux-hardware.org/?probe=6b5de5fe3c) | Mar 17, 2023 |
| Standard      | SF20BA                      | [e85dc022b5](https://linux-hardware.org/?probe=e85dc022b5) | Mar 15, 2023 |
| HP            | Laptop 17-ak0xx             | [7d35815562](https://linux-hardware.org/?probe=7d35815562) | Mar 13, 2023 |
| HP            | EliteBook 840 G3            | [41bf4fb877](https://linux-hardware.org/?probe=41bf4fb877) | Mar 10, 2023 |
| Dell          | Latitude 3150               | [f1554a5df0](https://linux-hardware.org/?probe=f1554a5df0) | Mar 05, 2023 |
| Acer          | Swift SF314-54              | [62defb89e3](https://linux-hardware.org/?probe=62defb89e3) | Mar 02, 2023 |
| ECS           | SF20PA2                     | [f0ad83686f](https://linux-hardware.org/?probe=f0ad83686f) | Feb 21, 2023 |
| HP            | 15 Notebook PC              | [c5256638eb](https://linux-hardware.org/?probe=c5256638eb) | Feb 20, 2023 |
| Lenovo        | ThinkPad P50 20EQS14H00     | [de5c7ac3f6](https://linux-hardware.org/?probe=de5c7ac3f6) | Feb 19, 2023 |
| Unknown       | Unknown                     | [e8183bc042](https://linux-hardware.org/?probe=e8183bc042) | Feb 16, 2023 |
| Lenovo        | 14w 81MQ00AVCL              | [bd59f68ce8](https://linux-hardware.org/?probe=bd59f68ce8) | Feb 03, 2023 |
| ECS           | SF20PA2                     | [30df19ca2e](https://linux-hardware.org/?probe=30df19ca2e) | Feb 02, 2023 |
| Gateway       | LT41P                       | [1684d937e7](https://linux-hardware.org/?probe=1684d937e7) | Feb 02, 2023 |
| HP            | 3115-AEC13432GR1            | [98eb70341a](https://linux-hardware.org/?probe=98eb70341a) | Jan 30, 2023 |
| Valve         | Jupiter                     | [4bda80131d](https://linux-hardware.org/?probe=4bda80131d) | Jan 15, 2023 |
| Valve         | Jupiter                     | [dc137d0d08](https://linux-hardware.org/?probe=dc137d0d08) | Jan 09, 2023 |
| Toshiba       | Satellite C75D-B            | [d5380976a2](https://linux-hardware.org/?probe=d5380976a2) | Jan 03, 2023 |
| Toshiba       | Satellite C75D-B            | [04282775ba](https://linux-hardware.org/?probe=04282775ba) | Dec 24, 2022 |
| ECS           | SF20PA2                     | [2e0892ec48](https://linux-hardware.org/?probe=2e0892ec48) | Nov 18, 2022 |
| Acer          | Aspire one 1-431            | [c27978fdc4](https://linux-hardware.org/?probe=c27978fdc4) | Nov 18, 2022 |
| Apple         | MacBookPro9,2               | [e974c2ceff](https://linux-hardware.org/?probe=e974c2ceff) | Nov 12, 2022 |
| Alienware     | 14                          | [0c11295ebe](https://linux-hardware.org/?probe=0c11295ebe) | Nov 03, 2022 |
| Toshiba       | Satellite L45-B             | [e2f30e0f1e](https://linux-hardware.org/?probe=e2f30e0f1e) | Oct 26, 2022 |
| HP            | Laptop 17-ak0xx             | [67fbbc4074](https://linux-hardware.org/?probe=67fbbc4074) | Oct 11, 2022 |
| Acer          | Aspire ES1-572              | [1bd18c9a15](https://linux-hardware.org/?probe=1bd18c9a15) | Oct 04, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | [5e91cc6f07](https://linux-hardware.org/?probe=5e91cc6f07) | Sep 21, 2022 |
| Toshiba       | Satellite C855              | [bd34f35e50](https://linux-hardware.org/?probe=bd34f35e50) | Sep 15, 2022 |
| Dell          | Latitude 3150               | [6bc88c696c](https://linux-hardware.org/?probe=6bc88c696c) | Sep 04, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [1e79d17c85](https://linux-hardware.org/?probe=1e79d17c85) | Aug 23, 2022 |
| ECS           | SF20PA2                     | [67dd8af18f](https://linux-hardware.org/?probe=67dd8af18f) | Aug 23, 2022 |
| Lenovo        | IdeaPad 500S-14ISK 80Q3     | [fdbec5aab2](https://linux-hardware.org/?probe=fdbec5aab2) | Aug 22, 2022 |
| Gateway       | NV55C                       | [cc3c8d23e4](https://linux-hardware.org/?probe=cc3c8d23e4) | Aug 03, 2022 |
| Dell          | Latitude 3150               | [aecf1fe543](https://linux-hardware.org/?probe=aecf1fe543) | Aug 01, 2022 |
| HP            | Laptop 14-dk1xxx            | [4eb7e0d085](https://linux-hardware.org/?probe=4eb7e0d085) | Jul 22, 2022 |
| GPU Compan... | GWTN156-9                   | [df5c4b480d](https://linux-hardware.org/?probe=df5c4b480d) | Jul 15, 2022 |
| Acer          | Swift SF314-54              | [47420af7dc](https://linux-hardware.org/?probe=47420af7dc) | Jun 23, 2022 |
| iClever       | IC-T01                      | [f82c34c612](https://linux-hardware.org/?probe=f82c34c612) | Jun 17, 2022 |
| HP            | Pavilion g4                 | [193875edcc](https://linux-hardware.org/?probe=193875edcc) | Jun 15, 2022 |
| Acer          | Swift SF314-54              | [06bccc3696](https://linux-hardware.org/?probe=06bccc3696) | Jun 14, 2022 |
| Dell          | XPS 15 7590                 | [482ed9f535](https://linux-hardware.org/?probe=482ed9f535) | May 29, 2022 |
| Acer          | Swift SF314-54              | [39f85b46d7](https://linux-hardware.org/?probe=39f85b46d7) | May 23, 2022 |
| Acer          | Swift SF314-54              | [fc1233f258](https://linux-hardware.org/?probe=fc1233f258) | May 22, 2022 |
| Acer          | Swift SF314-54              | [478550abf1](https://linux-hardware.org/?probe=478550abf1) | May 21, 2022 |
| Acer          | Swift SF314-54              | [a31c36956a](https://linux-hardware.org/?probe=a31c36956a) | May 13, 2022 |
| Acer          | Swift SF314-54              | [cc3411e0b4](https://linux-hardware.org/?probe=cc3411e0b4) | May 10, 2022 |
| HP            | Laptop 14-dk1xxx            | [fa6da4906f](https://linux-hardware.org/?probe=fa6da4906f) | May 07, 2022 |
| Toshiba       | Satellite C645D             | [53153cb65d](https://linux-hardware.org/?probe=53153cb65d) | May 04, 2022 |
| Acer          | Aspire ES1-572              | [25f9b83c30](https://linux-hardware.org/?probe=25f9b83c30) | Apr 28, 2022 |
| Lenovo        | B50-45 20388                | [7ad45f257f](https://linux-hardware.org/?probe=7ad45f257f) | Apr 20, 2022 |
| HP            | EliteBook 840 G1            | [d2e2811388](https://linux-hardware.org/?probe=d2e2811388) | Apr 20, 2022 |
| Dell          | Inspiron 5585               | [2c6e96d91f](https://linux-hardware.org/?probe=2c6e96d91f) | Apr 18, 2022 |
| Dell          | Inspiron 15-3567            | [73be944f6c](https://linux-hardware.org/?probe=73be944f6c) | Apr 14, 2022 |
| Dell          | Precision 7550              | [4619da9502](https://linux-hardware.org/?probe=4619da9502) | Apr 14, 2022 |
| Lenovo        | G405 20239                  | [ab55cb1e13](https://linux-hardware.org/?probe=ab55cb1e13) | Apr 13, 2022 |
| HP            | Laptop 14-dq1xxx            | [7d203f8bc0](https://linux-hardware.org/?probe=7d203f8bc0) | Apr 02, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [d895af2b46](https://linux-hardware.org/?probe=d895af2b46) | Mar 29, 2022 |
| HP            | Laptop 14-dq1xxx            | [9bf7ed495b](https://linux-hardware.org/?probe=9bf7ed495b) | Mar 28, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [d9afd858b4](https://linux-hardware.org/?probe=d9afd858b4) | Mar 23, 2022 |
| HP            | ZBook 14u G4                | [cc637b12de](https://linux-hardware.org/?probe=cc637b12de) | Mar 10, 2022 |
| HP            | Pavilion dv5                | [81371d4535](https://linux-hardware.org/?probe=81371d4535) | Mar 04, 2022 |
| GPU Compan... | GWTN156-4                   | [89e7b9fa39](https://linux-hardware.org/?probe=89e7b9fa39) | Mar 02, 2022 |
| ECS           | SF20PA2                     | [3bddc7e08a](https://linux-hardware.org/?probe=3bddc7e08a) | Feb 11, 2022 |
| MSI           | GS63VR 6RF                  | [4873365af6](https://linux-hardware.org/?probe=4873365af6) | Jan 30, 2022 |
| Sony          | SVF14211CLB                 | [d25b1846ff](https://linux-hardware.org/?probe=d25b1846ff) | Dec 07, 2021 |
| Sony          | SVF14211CLB                 | [41bfe6e292](https://linux-hardware.org/?probe=41bfe6e292) | Dec 06, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [5fb4f1b6a6](https://linux-hardware.org/?probe=5fb4f1b6a6) | Nov 29, 2021 |
| HP            | Stream Laptop 14-ax0XX      | [a664218f29](https://linux-hardware.org/?probe=a664218f29) | Nov 28, 2021 |
| Acer          | Aspire 5733Z                | [324f0d898e](https://linux-hardware.org/?probe=324f0d898e) | Nov 16, 2021 |
| Acer          | Swift SF314-54              | [b506625dc2](https://linux-hardware.org/?probe=b506625dc2) | Nov 05, 2021 |
| Acer          | Swift SF314-54              | [4e606c817f](https://linux-hardware.org/?probe=4e606c817f) | Nov 04, 2021 |
| Samsung       | N102SP/N100SP/N101SP        | [c04d448530](https://linux-hardware.org/?probe=c04d448530) | Oct 21, 2021 |
| Lenovo        | B51-30 80LK                 | [dea10156c6](https://linux-hardware.org/?probe=dea10156c6) | Sep 20, 2021 |
| Haitech       | H7141A                      | [496c0eb316](https://linux-hardware.org/?probe=496c0eb316) | Sep 18, 2021 |
| ECS           | SF20PA2                     | [6d17cf08ad](https://linux-hardware.org/?probe=6d17cf08ad) | Sep 12, 2021 |
| Panasonic     | CF-31JEGAX1M                | [c5acecef3a](https://linux-hardware.org/?probe=c5acecef3a) | Aug 22, 2021 |
| Lenovo        | ThinkPad L490 20Q6S0NF00    | [a8f222614b](https://linux-hardware.org/?probe=a8f222614b) | Aug 11, 2021 |
| Lenovo        | ThinkPad T450 20BUS0G91F    | [8db659cf12](https://linux-hardware.org/?probe=8db659cf12) | Aug 09, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20CDS02... | [4781e962e7](https://linux-hardware.org/?probe=4781e962e7) | Aug 09, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [393c8e4faa](https://linux-hardware.org/?probe=393c8e4faa) | Aug 05, 2021 |
| HP            | Pavilion 15                 | [ec0019224a](https://linux-hardware.org/?probe=ec0019224a) | Jul 28, 2021 |
| ECS           | SF20PA2                     | [2016dfe42c](https://linux-hardware.org/?probe=2016dfe42c) | Jul 26, 2021 |
| HP            | Laptop 15-bs0xx             | [c84d445008](https://linux-hardware.org/?probe=c84d445008) | Jul 18, 2021 |
| Acer          | Aspire E5-521               | [d4629ecbed](https://linux-hardware.org/?probe=d4629ecbed) | Jul 18, 2021 |
| Lenovo        | ThinkPad E15 20RES31K00     | [6d359d339e](https://linux-hardware.org/?probe=6d359d339e) | Jul 02, 2021 |
| HP            | Laptop 15-bs0xx             | [27582e9e17](https://linux-hardware.org/?probe=27582e9e17) | Jun 21, 2021 |
| Acer          | TravelMate 5730             | [4a21735ce1](https://linux-hardware.org/?probe=4a21735ce1) | Jun 17, 2021 |
| Acer          | Acadia V1.45                | [9357025bc9](https://linux-hardware.org/?probe=9357025bc9) | Jun 01, 2021 |
| HP            | ENVY TS 15                  | [8369c42ce2](https://linux-hardware.org/?probe=8369c42ce2) | May 31, 2021 |
| Positivo      | Serie AT300                 | [38a0173a4a](https://linux-hardware.org/?probe=38a0173a4a) | May 28, 2021 |
| HP            | Pavilion 17                 | [f12450cc62](https://linux-hardware.org/?probe=f12450cc62) | May 28, 2021 |
| Lenovo        | ThinkPad T590 20N5S2GP05    | [2444839350](https://linux-hardware.org/?probe=2444839350) | May 25, 2021 |
| Dell          | Latitude E5470              | [212d434e24](https://linux-hardware.org/?probe=212d434e24) | May 25, 2021 |
| Positivo      | Serie AT300                 | [a021ecf0dd](https://linux-hardware.org/?probe=a021ecf0dd) | May 24, 2021 |
| Acer          | Aspire 5715Z                | [24040eecb6](https://linux-hardware.org/?probe=24040eecb6) | May 23, 2021 |
| Toshiba       | Satellite C45-A             | [cb57bbefd0](https://linux-hardware.org/?probe=cb57bbefd0) | May 22, 2021 |
| Toshiba       | Satellite C45-A             | [297e5b458a](https://linux-hardware.org/?probe=297e5b458a) | May 21, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [883f67612b](https://linux-hardware.org/?probe=883f67612b) | May 19, 2021 |
| Standard      | SF20BA2                     | [e0fdbc36a2](https://linux-hardware.org/?probe=e0fdbc36a2) | May 16, 2021 |
| Acer          | Acadia V1.45                | [321e5159ac](https://linux-hardware.org/?probe=321e5159ac) | May 15, 2021 |
| ECS           | SF20PA2                     | [f3cc58b0e4](https://linux-hardware.org/?probe=f3cc58b0e4) | May 13, 2021 |
| Dell          | Inspiron N5110              | [6f67fbb9d4](https://linux-hardware.org/?probe=6f67fbb9d4) | May 08, 2021 |
| ECS           | SF20PA2                     | [cfbd36f40b](https://linux-hardware.org/?probe=cfbd36f40b) | May 07, 2021 |
| Acer          | Aspire E5-521               | [d1c6c7309a](https://linux-hardware.org/?probe=d1c6c7309a) | May 03, 2021 |
| ASUSTek       | N46VJ                       | [0d6e007969](https://linux-hardware.org/?probe=0d6e007969) | Apr 28, 2021 |
| Standard      | SF20BA2                     | [d51e9f653f](https://linux-hardware.org/?probe=d51e9f653f) | Apr 26, 2021 |
| Standard      | SF20BA2                     | [a568b21782](https://linux-hardware.org/?probe=a568b21782) | Apr 23, 2021 |
| Standard      | SF20BA2                     | [e454415213](https://linux-hardware.org/?probe=e454415213) | Apr 23, 2021 |
| Lenovo        | G50-70 20351                | [44e6cc36ce](https://linux-hardware.org/?probe=44e6cc36ce) | Apr 20, 2021 |
| Lenovo        | V15-ADA 82C7                | [9065c52996](https://linux-hardware.org/?probe=9065c52996) | Apr 17, 2021 |
| Dell          | Inspiron 5565               | [8f75eda1de](https://linux-hardware.org/?probe=8f75eda1de) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [4e23f3b6b5](https://linux-hardware.org/?probe=4e23f3b6b5) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [18ee0d2d64](https://linux-hardware.org/?probe=18ee0d2d64) | Apr 16, 2021 |
| HP            | 240 G7                      | [721c4c3dbd](https://linux-hardware.org/?probe=721c4c3dbd) | Apr 14, 2021 |
| Apple         | MacBookAir7,1               | [2296b37506](https://linux-hardware.org/?probe=2296b37506) | Apr 12, 2021 |
| Acer          | Aspire 5715Z                | [9a7aa83895](https://linux-hardware.org/?probe=9a7aa83895) | Apr 07, 2021 |
| Acer          | Aspire 5715Z                | [30729baf7a](https://linux-hardware.org/?probe=30729baf7a) | Apr 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [118abf533e](https://linux-hardware.org/?probe=118abf533e) | Mar 28, 2021 |
| Panasonic     | CF-31JEGAX1M                | [4636e611d8](https://linux-hardware.org/?probe=4636e611d8) | Mar 14, 2021 |
| MSI           | GL65 Leopard 10SCXR         | [8497db47ab](https://linux-hardware.org/?probe=8497db47ab) | Mar 09, 2021 |
| HP            | Laptop 14-df0xxx            | [c1d21b6940](https://linux-hardware.org/?probe=c1d21b6940) | Mar 01, 2021 |
| Dell          | XPS 13 9370                 | [f51dac04a1](https://linux-hardware.org/?probe=f51dac04a1) | Feb 17, 2021 |
| Dell          | XPS 13 9370                 | [bea8cc11d5](https://linux-hardware.org/?probe=bea8cc11d5) | Feb 17, 2021 |
| MSI           | GL65 Leopard 10SCXR         | [ac71737361](https://linux-hardware.org/?probe=ac71737361) | Jan 16, 2021 |
| Acer          | Aspire 5733                 | [1f4e4d7fbc](https://linux-hardware.org/?probe=1f4e4d7fbc) | Jan 08, 2021 |
| Toshiba       | Satellite L55t-B            | [ab3b576bd1](https://linux-hardware.org/?probe=ab3b576bd1) | Jan 07, 2021 |
| Toshiba       | Satellite L55t-B            | [6fc9533a15](https://linux-hardware.org/?probe=6fc9533a15) | Jan 06, 2021 |
| ECS           | SF20PA2                     | [f26e0bf23f](https://linux-hardware.org/?probe=f26e0bf23f) | Jan 04, 2021 |
| HP            | 2000                        | [99481f08e3](https://linux-hardware.org/?probe=99481f08e3) | Dec 31, 2020 |
| Panasonic     | CF-31JEGAX1M                | [c0745f5a94](https://linux-hardware.org/?probe=c0745f5a94) | Dec 31, 2020 |
| HP            | Notebook                    | [213a94eab7](https://linux-hardware.org/?probe=213a94eab7) | Dec 28, 2020 |
| HP            | Notebook                    | [bb3749dd61](https://linux-hardware.org/?probe=bb3749dd61) | Dec 28, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f55e2642ef](https://linux-hardware.org/?probe=f55e2642ef) | Dec 15, 2020 |
| Toshiba       | Satellite C75D-C            | [f158fc821a](https://linux-hardware.org/?probe=f158fc821a) | Nov 10, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [5a8d4603be](https://linux-hardware.org/?probe=5a8d4603be) | Nov 03, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [19081a3c58](https://linux-hardware.org/?probe=19081a3c58) | Oct 27, 2020 |
| Dell          | Latitude E6430              | [8ea63ec090](https://linux-hardware.org/?probe=8ea63ec090) | Oct 23, 2020 |
| HP            | Pavilion dm4                | [21a3ef42e0](https://linux-hardware.org/?probe=21a3ef42e0) | Oct 13, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [64e95b4174](https://linux-hardware.org/?probe=64e95b4174) | Oct 10, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0ffffb855b](https://linux-hardware.org/?probe=0ffffb855b) | Oct 04, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7ddfb80220](https://linux-hardware.org/?probe=7ddfb80220) | Oct 04, 2020 |
| Toshiba       | Satellite C75D-C            | [12c65e3222](https://linux-hardware.org/?probe=12c65e3222) | Sep 25, 2020 |
| MSI           | GE62 6QD                    | [cf444064fc](https://linux-hardware.org/?probe=cf444064fc) | Sep 03, 2020 |
| HP            | Casablanca H710             | [2061828542](https://linux-hardware.org/?probe=2061828542) | Aug 26, 2020 |
| HP            | Casablanca H710             | [f566c52ffd](https://linux-hardware.org/?probe=f566c52ffd) | Aug 26, 2020 |
| Samsung       | NC208/NC108                 | [f425b1dc48](https://linux-hardware.org/?probe=f425b1dc48) | Aug 17, 2020 |
| Samsung       | NC208/NC108                 | [759ee832fb](https://linux-hardware.org/?probe=759ee832fb) | Aug 17, 2020 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [3c55f58986](https://linux-hardware.org/?probe=3c55f58986) | Jul 03, 2020 |
| HP            | Presario CQ43               | [bba4f49ed1](https://linux-hardware.org/?probe=bba4f49ed1) | Jun 23, 2020 |
| Acer          | Aspire A715-72G             | [70acf4ea22](https://linux-hardware.org/?probe=70acf4ea22) | Jun 18, 2020 |
| HP            | Presario CQ43               | [3af51e5df2](https://linux-hardware.org/?probe=3af51e5df2) | Jun 13, 2020 |
| ECS           | SF20PA2                     | [fc1653c118](https://linux-hardware.org/?probe=fc1653c118) | Jun 10, 2020 |
| Dell          | Inspiron 5748               | [d7010adabe](https://linux-hardware.org/?probe=d7010adabe) | Jun 09, 2020 |
| OEM           | V40SI2                      | [e2ad8d9479](https://linux-hardware.org/?probe=e2ad8d9479) | Jun 06, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [13b3a46069](https://linux-hardware.org/?probe=13b3a46069) | May 27, 2020 |
| ASUSTek       | X555LAB                     | [7e4107b1b4](https://linux-hardware.org/?probe=7e4107b1b4) | May 26, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | [7e4e3c078f](https://linux-hardware.org/?probe=7e4e3c078f) | May 20, 2020 |
| MSI           | GL63 8RD                    | [7e41ab8d71](https://linux-hardware.org/?probe=7e41ab8d71) | May 15, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [3b397b64f7](https://linux-hardware.org/?probe=3b397b64f7) | May 06, 2020 |
| HP            | Laptop 15-bs0xx             | [a9832cd92e](https://linux-hardware.org/?probe=a9832cd92e) | May 05, 2020 |
| HP            | Laptop 15-bs0xx             | [a8857822b2](https://linux-hardware.org/?probe=a8857822b2) | May 03, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [8609a3503d](https://linux-hardware.org/?probe=8609a3503d) | May 02, 2020 |
| HP            | Laptop 15-bs0xx             | [7fdc3c7af9](https://linux-hardware.org/?probe=7fdc3c7af9) | May 02, 2020 |
| Lenovo        | ThinkPad X240 20AMS72901    | [ad1e10654b](https://linux-hardware.org/?probe=ad1e10654b) | Apr 30, 2020 |
| Standard      | EF20EA                      | [11882357e0](https://linux-hardware.org/?probe=11882357e0) | Apr 26, 2020 |
| Dell          | Inspiron N5110              | [3be039900b](https://linux-hardware.org/?probe=3be039900b) | Apr 17, 2020 |
| Dell          | Inspiron N5110              | [cf6e400de0](https://linux-hardware.org/?probe=cf6e400de0) | Apr 17, 2020 |
| Dell          | Inspiron N5110              | [bb8bd669f6](https://linux-hardware.org/?probe=bb8bd669f6) | Apr 17, 2020 |
| Dell          | Inspiron N5110              | [f1caefcea5](https://linux-hardware.org/?probe=f1caefcea5) | Apr 17, 2020 |
| HP            | 620                         | [812b274fd4](https://linux-hardware.org/?probe=812b274fd4) | Apr 13, 2020 |
| HP            | 620                         | [ca26b96168](https://linux-hardware.org/?probe=ca26b96168) | Apr 13, 2020 |
| ECS           | SF20PA2                     | [d685560200](https://linux-hardware.org/?probe=d685560200) | Feb 01, 2020 |
| ECS           | SF20PA2                     | [e6212ece14](https://linux-hardware.org/?probe=e6212ece14) | Nov 27, 2019 |
| ECS           | SF20PA2                     | [1d4a07f181](https://linux-hardware.org/?probe=1d4a07f181) | Nov 19, 2019 |
| Toshiba       | Satellite C55-B             | [1fab0cb871](https://linux-hardware.org/?probe=1fab0cb871) | Nov 16, 2019 |
| ECS           | SF20PA2                     | [063490d972](https://linux-hardware.org/?probe=063490d972) | Nov 03, 2019 |
| HP            | Laptop 14-dk0xxx            | [623c96ec6e](https://linux-hardware.org/?probe=623c96ec6e) | Oct 07, 2019 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | [0925f5642c](https://linux-hardware.org/?probe=0925f5642c) | Sep 24, 2019 |
| ECS           | SF20PA2                     | [3c9b29c0c7](https://linux-hardware.org/?probe=3c9b29c0c7) | Sep 20, 2019 |
| ECS           | SF20PA2                     | [6d35e092fa](https://linux-hardware.org/?probe=6d35e092fa) | Sep 16, 2019 |
| Dell          | Inspiron 13-5368            | [0dab5b3510](https://linux-hardware.org/?probe=0dab5b3510) | Sep 15, 2019 |
| ECS           | SF20PA2                     | [80d3b6b8cf](https://linux-hardware.org/?probe=80d3b6b8cf) | Aug 04, 2019 |
| ECS           | SF20PA2                     | [a7b095e2f0](https://linux-hardware.org/?probe=a7b095e2f0) | Jul 30, 2019 |
| ECS           | SF20PA2                     | [01cad0b14a](https://linux-hardware.org/?probe=01cad0b14a) | Jul 10, 2019 |
| Acer          | TravelMate P249-G2-M        | [0e1338db33](https://linux-hardware.org/?probe=0e1338db33) | Jul 01, 2019 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | [08c0f291e9](https://linux-hardware.org/?probe=08c0f291e9) | Jun 13, 2019 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | [5619d594fa](https://linux-hardware.org/?probe=5619d594fa) | Jun 10, 2019 |
| Dell          | Inspiron N5040              | [b8f0a4691d](https://linux-hardware.org/?probe=b8f0a4691d) | May 17, 2019 |
| Samsung       | 700T                        | [dcf693f16f](https://linux-hardware.org/?probe=dcf693f16f) | May 11, 2019 |
| HP            | Pavilion dv6                | [36299cef92](https://linux-hardware.org/?probe=36299cef92) | Apr 17, 2019 |
| HP            | Laptop 15-db0xxx            | [b26531074c](https://linux-hardware.org/?probe=b26531074c) | Apr 16, 2019 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | [7d9905cfe7](https://linux-hardware.org/?probe=7d9905cfe7) | Mar 27, 2019 |
| ASUSTek       | TP300LAB                    | [538b5e5d24](https://linux-hardware.org/?probe=538b5e5d24) | Mar 26, 2019 |
| HP            | Pavilion 15                 | [7376903dca](https://linux-hardware.org/?probe=7376903dca) | May 13, 2018 |
| HP            | Pavilion 15                 | [2cc0124d5d](https://linux-hardware.org/?probe=2cc0124d5d) | May 13, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 26        | 9.03%   |
| Ubuntu 18.04       | 20        | 6.94%   |
| Ubuntu 22.04       | 14        | 4.86%   |
| Manjaro            | 10        | 3.47%   |
| Arch Rolling       | 10        | 3.47%   |
| Debian 12          | 8         | 2.78%   |
| Fedora 40          | 7         | 2.43%   |
| OpenMandriva 4.2   | 6         | 2.08%   |
| KDE neon 20.04     | 6         | 2.08%   |
| Zorin 17           | 5         | 1.74%   |
| OpenMandriva 4.3   | 5         | 1.74%   |
| OpenMandriva 25.90 | 5         | 1.74%   |
| Zorin 16           | 4         | 1.39%   |
| Ubuntu 24.04       | 4         | 1.39%   |
| OpenMandriva 23.03 | 4         | 1.39%   |
| Linux Mint 21.2    | 4         | 1.39%   |
| Fedora 42          | 4         | 1.39%   |
| Fedora 38          | 4         | 1.39%   |
| Ubuntu 21.10       | 3         | 1.04%   |
| Ubuntu 19.04       | 3         | 1.04%   |
| Linux Mint 21.3    | 3         | 1.04%   |
| Linux Mint 21.1    | 3         | 1.04%   |
| Linux Mint 19.3    | 3         | 1.04%   |
| Fedora 39          | 3         | 1.04%   |
| Fedora 36          | 3         | 1.04%   |
| Debian 11          | 3         | 1.04%   |
| ArcoLinux Rolling  | 3         | 1.04%   |
| Zorin 18           | 2         | 0.69%   |
| Xubuntu 18.04      | 2         | 0.69%   |
| Void Linux Rolling | 2         | 0.69%   |
| Ubuntu 23.10       | 2         | 0.69%   |
| Ubuntu 23.04       | 2         | 0.69%   |
| Ubuntu 21.04       | 2         | 0.69%   |
| Ubuntu 18.10       | 2         | 0.69%   |
| Pop!_OS 22.04      | 2         | 0.69%   |
| OpenMandriva 25.06 | 2         | 0.69%   |
| OpenMandriva 23.08 | 2         | 0.69%   |
| OpenMandriva 23.01 | 2         | 0.69%   |
| Lubuntu 24.04      | 2         | 0.69%   |
| Linux Mint 20.3    | 2         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 79        | 28.94%  |
| OpenMandriva | 28        | 10.26%  |
| Linux Mint   | 26        | 9.52%   |
| Fedora       | 25        | 9.16%   |
| Zorin        | 12        | 4.4%    |
| Manjaro      | 12        | 4.4%    |
| Debian       | 11        | 4.03%   |
| Arch         | 10        | 3.66%   |
| KDE neon     | 8         | 2.93%   |
| Xubuntu      | 6         | 2.2%    |
| Kubuntu      | 5         | 1.83%   |
| Endless      | 5         | 1.83%   |
| NixOS        | 4         | 1.47%   |
| Lubuntu      | 4         | 1.47%   |
| ArcoLinux    | 4         | 1.47%   |
| Kali         | 3         | 1.1%    |
| Elementary   | 3         | 1.1%    |
| Void Linux   | 2         | 0.73%   |
| SteamOS      | 2         | 0.73%   |
| ROSA         | 2         | 0.73%   |
| Pop!_OS      | 2         | 0.73%   |
| openSUSE     | 2         | 0.73%   |
| EndeavourOS  | 2         | 0.73%   |
| Bazzite      | 2         | 0.73%   |
| Archcraft    | 2         | 0.73%   |
| antiX        | 2         | 0.73%   |
| UbuntuDDE    | 1         | 0.37%   |
| Ubuntu MATE  | 1         | 0.37%   |
| MX           | 1         | 0.37%   |
| LMDE         | 1         | 0.37%   |
| Gentoo       | 1         | 0.37%   |
| Garuda Linux | 1         | 0.37%   |
| Feren OS     | 1         | 0.37%   |
| blendOS      | 1         | 0.37%   |
| BlackPanther | 1         | 0.37%   |
| Artix        | 1         | 0.37%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 6.14.2-desktop-3omv2590  | 8         | 2.59%   |
| 5.10.14-desktop-1omv4002 | 6         | 1.94%   |
| 4.16.18-pa2-2bp1         | 6         | 1.94%   |
| 4.16.18-pa2-1bp5         | 5         | 1.62%   |
| 6.2.6-desktop-1omv2390   | 4         | 1.29%   |
| 5.8.0-53-generic         | 4         | 1.29%   |
| 5.5.19-bp0               | 4         | 1.29%   |
| 5.16.7-desktop-1omv4003  | 4         | 1.29%   |
| 5.13.0-39-generic        | 4         | 1.29%   |
| 5.4.0-73-generic         | 3         | 0.97%   |
| 5.4.0-58-generic         | 3         | 0.97%   |
| 5.4.0-52-generic         | 3         | 0.97%   |
| 5.11.0-38-generic        | 3         | 0.97%   |
| 6.9.12-3-MANJARO         | 2         | 0.65%   |
| 6.8.0-53-generic         | 2         | 0.65%   |
| 6.8.0-40-generic         | 2         | 0.65%   |
| 6.5.12-300.fc39.x86_64   | 2         | 0.65%   |
| 6.5.0-45-generic         | 2         | 0.65%   |
| 6.5.0-41-generic         | 2         | 0.65%   |
| 6.5.0-17-generic         | 2         | 0.65%   |
| 6.5.0-15-generic         | 2         | 0.65%   |
| 6.4.8-desktop-2omv2390   | 2         | 0.65%   |
| 6.4.7-arch1-1            | 2         | 0.65%   |
| 6.3.9-zen1-1-zen         | 2         | 0.65%   |
| 6.2.0-39-generic         | 2         | 0.65%   |
| 6.14.0-29-generic        | 2         | 0.65%   |
| 6.12.25-amd64            | 2         | 0.65%   |
| 6.10.4-200.fc40.x86_64   | 2         | 0.65%   |
| 6.1.1-desktop-1omv2290   | 2         | 0.65%   |
| 6.1.0-26-amd64           | 2         | 0.65%   |
| 6.1.0-18-amd64           | 2         | 0.65%   |
| 5.8.0-50-generic         | 2         | 0.65%   |
| 5.8.0-43-generic         | 2         | 0.65%   |
| 5.4.0-72-generic         | 2         | 0.65%   |
| 5.4.0-42-generic         | 2         | 0.65%   |
| 5.3.0-28-generic         | 2         | 0.65%   |
| 5.19.0-41-generic        | 2         | 0.65%   |
| 5.19.0-35-generic        | 2         | 0.65%   |
| 5.16.13-desktop-1omv4003 | 2         | 0.65%   |
| 5.15.0-46-generic        | 2         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 25        | 8.36%   |
| 5.15.0  | 15        | 5.02%   |
| 5.8.0   | 13        | 4.35%   |
| 6.8.0   | 12        | 4.01%   |
| 5.13.0  | 12        | 4.01%   |
| 6.5.0   | 11        | 3.68%   |
| 4.16.18 | 11        | 3.68%   |
| 6.14.2  | 10        | 3.34%   |
| 4.15.0  | 9         | 3.01%   |
| 6.1.0   | 8         | 2.68%   |
| 6.2.0   | 6         | 2.01%   |
| 6.14.0  | 6         | 2.01%   |
| 5.11.0  | 6         | 2.01%   |
| 5.10.14 | 6         | 2.01%   |
| 5.0.0   | 6         | 2.01%   |
| 5.3.0   | 5         | 1.67%   |
| 5.19.0  | 5         | 1.67%   |
| 6.2.6   | 4         | 1.34%   |
| 5.5.19  | 4         | 1.34%   |
| 5.16.7  | 4         | 1.34%   |
| 5.10.0  | 4         | 1.34%   |
| 4.18.0  | 4         | 1.34%   |
| 6.9.12  | 3         | 1%      |
| 6.11.0  | 3         | 1%      |
| 6.5.12  | 2         | 0.67%   |
| 6.4.8   | 2         | 0.67%   |
| 6.4.7   | 2         | 0.67%   |
| 6.3.9   | 2         | 0.67%   |
| 6.3.4   | 2         | 0.67%   |
| 6.15.0  | 2         | 0.67%   |
| 6.12.9  | 2         | 0.67%   |
| 6.12.25 | 2         | 0.67%   |
| 6.10.4  | 2         | 0.67%   |
| 6.1.1   | 2         | 0.67%   |
| 5.19.12 | 2         | 0.67%   |
| 5.16.13 | 2         | 0.67%   |
| 5.11.12 | 2         | 0.67%   |
| 6.9.7   | 1         | 0.33%   |
| 6.8.5   | 1         | 0.33%   |
| 6.8.12  | 1         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 27        | 9.22%   |
| 6.14    | 19        | 6.48%   |
| 5.15    | 18        | 6.14%   |
| 6.5     | 17        | 5.8%    |
| 6.1     | 15        | 5.12%   |
| 5.8     | 15        | 5.12%   |
| 5.10    | 15        | 5.12%   |
| 6.8     | 14        | 4.78%   |
| 6.2     | 12        | 4.1%    |
| 5.13    | 12        | 4.1%    |
| 4.16    | 12        | 4.1%    |
| 5.11    | 10        | 3.41%   |
| 4.15    | 9         | 3.07%   |
| 5.16    | 8         | 2.73%   |
| 6.4     | 7         | 2.39%   |
| 5.19    | 7         | 2.39%   |
| 6.6     | 6         | 2.05%   |
| 6.12    | 6         | 2.05%   |
| 6.11    | 6         | 2.05%   |
| 5.0     | 6         | 2.05%   |
| 6.15    | 5         | 1.71%   |
| 5.3     | 5         | 1.71%   |
| 4.18    | 5         | 1.71%   |
| 6.9     | 4         | 1.37%   |
| 6.3     | 4         | 1.37%   |
| 6.17    | 4         | 1.37%   |
| 5.5     | 4         | 1.37%   |
| 6.10    | 3         | 1.02%   |
| 6.0     | 3         | 1.02%   |
| 5.17    | 3         | 1.02%   |
| 6.13    | 2         | 0.68%   |
| 5.18    | 2         | 0.68%   |
| 6.7     | 1         | 0.34%   |
| 5.6     | 1         | 0.34%   |
| 5.2     | 1         | 0.34%   |
| 5.14    | 1         | 0.34%   |
| 4.9     | 1         | 0.34%   |
| 4.17    | 1         | 0.34%   |
| 4.13    | 1         | 0.34%   |
| 4.12    | 1         | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 258       | 98.85%  |
| i686   | 3         | 1.15%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 94        | 34.18%  |
| KDE5            | 40        | 14.55%  |
| XFCE            | 29        | 10.55%  |
| Unknown         | 26        | 9.45%   |
| X-Cinnamon      | 21        | 7.64%   |
| KDE6            | 18        | 6.55%   |
| GNOME Flashback | 13        | 4.73%   |
| KDE             | 7         | 2.55%   |
| LXQt            | 6         | 2.18%   |
| Pantheon        | 3         | 1.09%   |
| MATE            | 3         | 1.09%   |
| openbox         | 2         | 0.73%   |
| LXDE            | 2         | 0.73%   |
| i3              | 2         | 0.73%   |
| Cinnamon        | 2         | 0.73%   |
| sway            | 1         | 0.36%   |
| LeftWM          | 1         | 0.36%   |
| icewm           | 1         | 0.36%   |
| Hyprland        | 1         | 0.36%   |
| Enlightenment   | 1         | 0.36%   |
| Endless:GNOME   | 1         | 0.36%   |
| Deepin          | 1         | 0.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 180       | 67.16%  |
| Wayland | 73        | 27.24%  |
| Unknown | 12        | 4.48%   |
| Tty     | 3         | 1.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 120       | 44.12%  |
| SDDM    | 51        | 18.75%  |
| LightDM | 34        | 12.5%   |
| GDM3    | 32        | 11.76%  |
| GDM     | 29        | 10.66%  |
| TDM     | 3         | 1.1%    |
| XDM     | 1         | 0.37%   |
| SLIMSKI | 1         | 0.37%   |
| GREETD  | 1         | 0.37%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| es_UY      | 137       | 50%     |
| en_US      | 71        | 25.91%  |
| es_ES      | 20        | 7.3%    |
| Unknown    | 20        | 7.3%    |
| es_AR      | 9         | 3.28%   |
| es_MX      | 8         | 2.92%   |
| C          | 3         | 1.09%   |
| en_GB      | 2         | 0.73%   |
| en_CA      | 2         | 0.73%   |
| pt_BR      | 1         | 0.36%   |
| es_UY.UTF8 | 1         | 0.36%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 144       | 53.93%  |
| BIOS | 123       | 46.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 196       | 71.79%  |
| Btrfs   | 34        | 12.45%  |
| Overlay | 20        | 7.33%   |
| Tmpfs   | 17        | 6.23%   |
| Unknown | 4         | 1.47%   |
| Xfs     | 1         | 0.37%   |
| Ext3    | 1         | 0.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 131       | 49.06%  |
| GPT     | 113       | 42.32%  |
| MBR     | 23        | 8.61%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 223       | 84.79%  |
| Yes       | 40        | 15.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 211       | 78.73%  |
| Yes       | 57        | 21.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 56        | 21.46%  |
| Lenovo              | 47        | 18.01%  |
| ASUSTek Computer    | 31        | 11.88%  |
| Dell                | 27        | 10.34%  |
| ECS                 | 19        | 7.28%   |
| Acer                | 19        | 7.28%   |
| Toshiba             | 13        | 4.98%   |
| Standard            | 6         | 2.3%    |
| Samsung Electronics | 6         | 2.3%    |
| MSI                 | 6         | 2.3%    |
| GPU Company         | 3         | 1.15%   |
| Chuwi               | 3         | 1.15%   |
| Apple               | 3         | 1.15%   |
| Valve               | 2         | 0.77%   |
| Positivo            | 2         | 0.77%   |
| JP-IK               | 2         | 0.77%   |
| Google              | 2         | 0.77%   |
| Gateway             | 2         | 0.77%   |
| Unknown             | 2         | 0.77%   |
| Sony                | 1         | 0.38%   |
| Razer               | 1         | 0.38%   |
| Panasonic           | 1         | 0.38%   |
| OEM                 | 1         | 0.38%   |
| Intel               | 1         | 0.38%   |
| iClever             | 1         | 0.38%   |
| Haitech             | 1         | 0.38%   |
| GMKtec              | 1         | 0.38%   |
| Fujitsu             | 1         | 0.38%   |
| Alienware           | 1         | 0.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| ECS SF20PA2                                 | 18        | 6.9%    |
| Unknown                                     | 5         | 1.92%   |
| Standard SF20BA2                            | 4         | 1.53%   |
| HP Dragonfly Pro ONE                        | 3         | 1.15%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV       | 3         | 1.15%   |
| Valve Jupiter                               | 2         | 0.77%   |
| Toshiba Satellite L55t-B                    | 2         | 0.77%   |
| Lenovo G405 20239                           | 2         | 0.77%   |
| HP Stream Laptop 14-ax0XX                   | 2         | 0.77%   |
| HP Pavilion 15                              | 2         | 0.77%   |
| HP Notebook                                 | 2         | 0.77%   |
| HP Laptop 15-bw0xx                          | 2         | 0.77%   |
| HP Laptop 15-bs0xx                          | 2         | 0.77%   |
| HP Laptop 14-dq1xxx                         | 2         | 0.77%   |
| Dell Inspiron 15-3567                       | 2         | 0.77%   |
| ASUS ZenBook UX434FLC_UX433FLC              | 2         | 0.77%   |
| ASUS ZenBook UX325EA_UX325EA                | 2         | 0.77%   |
| Acer Aspire A315-59                         | 2         | 0.77%   |
| Toshiba Satellite P55W-C                    | 1         | 0.38%   |
| Toshiba Satellite L755                      | 1         | 0.38%   |
| Toshiba Satellite L45-B                     | 1         | 0.38%   |
| Toshiba Satellite C855                      | 1         | 0.38%   |
| Toshiba Satellite C75D-C                    | 1         | 0.38%   |
| Toshiba Satellite C75D-B                    | 1         | 0.38%   |
| Toshiba Satellite C645D                     | 1         | 0.38%   |
| Toshiba Satellite C55-C                     | 1         | 0.38%   |
| Toshiba Satellite C55-B                     | 1         | 0.38%   |
| Toshiba Satellite C45-A                     | 1         | 0.38%   |
| Toshiba Satellite B40-A                     | 1         | 0.38%   |
| Standard SF20BA                             | 1         | 0.38%   |
| Standard EF20EA                             | 1         | 0.38%   |
| Sony SVF14211CLB                            | 1         | 0.38%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 0.38%   |
| Samsung NC208/NC108                         | 1         | 0.38%   |
| Samsung N102SP/N100SP/N101SP                | 1         | 0.38%   |
| Samsung 700T                                | 1         | 0.38%   |
| Samsung 550P5C/550P7C                       | 1         | 0.38%   |
| Samsung 300E4C/300E5C/300E7C                | 1         | 0.38%   |
| Razer Blade                                 | 1         | 0.38%   |
| Positivo Serie AT300                        | 1         | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 21        | 8.05%   |
| ECS SF20PA2       | 18        | 6.9%    |
| HP Laptop         | 16        | 6.13%   |
| Acer Aspire       | 14        | 5.36%   |
| Toshiba Satellite | 13        | 4.98%   |
| HP Pavilion       | 12        | 4.6%    |
| Dell Inspiron     | 12        | 4.6%    |
| Lenovo IdeaPad    | 11        | 4.21%   |
| Dell Latitude     | 11        | 4.21%   |
| ASUS VivoBook     | 8         | 3.07%   |
| ASUS Zenbook      | 7         | 2.68%   |
| HP Stream         | 5         | 1.92%   |
| ASUS ROG          | 5         | 1.92%   |
| Unknown           | 5         | 1.92%   |
| Standard SF20BA2  | 4         | 1.53%   |
| HP EliteBook      | 3         | 1.15%   |
| HP Dragonfly      | 3         | 1.15%   |
| ASUS ASUS         | 3         | 1.15%   |
| Valve Jupiter     | 2         | 0.77%   |
| Lenovo ThinkBook  | 2         | 0.77%   |
| Lenovo Legion     | 2         | 0.77%   |
| Lenovo G405       | 2         | 0.77%   |
| JP-IK T140J       | 2         | 0.77%   |
| HP Presario       | 2         | 0.77%   |
| HP OMEN           | 2         | 0.77%   |
| HP Notebook       | 2         | 0.77%   |
| HP 240            | 2         | 0.77%   |
| Dell XPS          | 2         | 0.77%   |
| Acer TravelMate   | 2         | 0.77%   |
| Standard SF20BA   | 1         | 0.38%   |
| Standard EF20EA   | 1         | 0.38%   |
| Sony SVF14211CLB  | 1         | 0.38%   |
| Samsung RV411     | 1         | 0.38%   |
| Samsung NC208     | 1         | 0.38%   |
| Samsung N102SP    | 1         | 0.38%   |
| Samsung 700T      | 1         | 0.38%   |
| Samsung 550P5C    | 1         | 0.38%   |
| Samsung 300E4C    | 1         | 0.38%   |
| Razer Blade       | 1         | 0.38%   |
| Positivo Serie    | 1         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2017 | 32        | 12.26%  |
| 2020 | 23        | 8.81%   |
| 2019 | 23        | 8.81%   |
| 2015 | 21        | 8.05%   |
| 2013 | 21        | 8.05%   |
| 2018 | 18        | 6.9%    |
| 2011 | 18        | 6.9%    |
| 2016 | 16        | 6.13%   |
| 2014 | 16        | 6.13%   |
| 2021 | 14        | 5.36%   |
| 2012 | 13        | 4.98%   |
| 2022 | 10        | 3.83%   |
| 2023 | 9         | 3.45%   |
| 2024 | 7         | 2.68%   |
| 2008 | 6         | 2.3%    |
| 2010 | 5         | 1.92%   |
| 2007 | 5         | 1.92%   |
| 2009 | 3         | 1.15%   |
| 2025 | 1         | 0.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 261       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 237       | 89.43%  |
| Enabled  | 28        | 10.57%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 258       | 98.85%  |
| Yes  | 3         | 1.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 60        | 22.64%  |
| 3.01-4.0    | 59        | 22.26%  |
| 8.01-16.0   | 40        | 15.09%  |
| 16.01-24.0  | 38        | 14.34%  |
| 1.01-2.0    | 37        | 13.96%  |
| 32.01-64.0  | 18        | 6.79%   |
| 24.01-32.0  | 8         | 3.02%   |
| 2.01-3.0    | 2         | 0.75%   |
| 64.01-256.0 | 2         | 0.75%   |
| 0.01-0.5    | 1         | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 102       | 34.93%  |
| 2.01-3.0   | 83        | 28.42%  |
| 3.01-4.0   | 35        | 11.99%  |
| 4.01-8.0   | 33        | 11.3%   |
| 0.51-1.0   | 19        | 6.51%   |
| 8.01-16.0  | 13        | 4.45%   |
| 16.01-24.0 | 5         | 1.71%   |
| 0.01-0.5   | 2         | 0.68%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 219       | 82.95%  |
| 2      | 44        | 16.67%  |
| 0      | 1         | 0.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 193       | 73.11%  |
| Yes       | 71        | 26.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 167       | 63.74%  |
| No        | 95        | 36.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 249       | 95.4%   |
| No        | 12        | 4.6%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 206       | 78.93%  |
| No        | 55        | 21.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Uruguay | 261       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Montevideo             | 200       | 72.2%   |
| Maldonado              | 15        | 5.42%   |
| Canelones              | 9         | 3.25%   |
| Punta del Este         | 4         | 1.44%   |
| Paysandú              | 4         | 1.44%   |
| Minas                  | 3         | 1.08%   |
| Buceo                  | 3         | 1.08%   |
| Sayago                 | 2         | 0.72%   |
| San Jose de Mayo       | 2         | 0.72%   |
| Salto                  | 2         | 0.72%   |
| Rocha                  | 2         | 0.72%   |
| Punta Gorda            | 2         | 0.72%   |
| Pocitos                | 2         | 0.72%   |
| Las Piedras            | 2         | 0.72%   |
| El Pinar               | 2         | 0.72%   |
| Ciudad del Plata       | 2         | 0.72%   |
| Chui                   | 2         | 0.72%   |
| Centro                 | 2         | 0.72%   |
| Solymar                | 1         | 0.36%   |
| Pinamar                | 1         | 0.36%   |
| Parque Rodo            | 1         | 0.36%   |
| Nueva Helvecia         | 1         | 0.36%   |
| Melilla                | 1         | 0.36%   |
| Maronas                | 1         | 0.36%   |
| Las Flores             | 1         | 0.36%   |
| La Paz                 | 1         | 0.36%   |
| Joaquin Suarez         | 1         | 0.36%   |
| El Tesoro              | 1         | 0.36%   |
| Durazno                | 1         | 0.36%   |
| Colonia Rosario        | 1         | 0.36%   |
| Colonia Nicolich       | 1         | 0.36%   |
| Castellanos            | 1         | 0.36%   |
| Barrancas Coloradas    | 1         | 0.36%   |
| Atlantida              | 1         | 0.36%   |
| Arenas de Jose Ignacio | 1         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Unknown                     | 36        | 44     | 12.37%  |
| Kingston                    | 36        | 48     | 12.37%  |
| Toshiba                     | 32        | 39     | 11%     |
| WDC                         | 26        | 32     | 8.93%   |
| Seagate                     | 24        | 29     | 8.25%   |
| SanDisk                     | 22        | 29     | 7.56%   |
| Samsung Electronics         | 19        | 20     | 6.53%   |
| SK hynix                    | 11        | 14     | 3.78%   |
| Hitachi                     | 10        | 14     | 3.44%   |
| Intel                       | 9         | 10     | 3.09%   |
| Micron Technology           | 8         | 8      | 2.75%   |
| HGST                        | 8         | 9      | 2.75%   |
| Netac                       | 6         | 7      | 2.06%   |
| China                       | 4         | 4      | 1.37%   |
| Realtek Semiconductor       | 3         | 3      | 1.03%   |
| Phison                      | 3         | 7      | 1.03%   |
| KIOXIA                      | 3         | 5      | 1.03%   |
| Kingston Technology Company | 3         | 4      | 1.03%   |
| Hewlett-Packard             | 3         | 3      | 1.03%   |
| Crucial                     | 3         | 4      | 1.03%   |
| Silicon Motion              | 2         | 2      | 0.69%   |
| LITEON                      | 2         | 3      | 0.69%   |
| Dahua                       | 2         | 4      | 0.69%   |
| Apple                       | 2         | 2      | 0.69%   |
| W800SH                      | 1         | 1      | 0.34%   |
| Union Memory (Shenzhen)     | 1         | 2      | 0.34%   |
| SAGE                        | 1         | 2      | 0.34%   |
| Phison Electronics          | 1         | 1      | 0.34%   |
| Patriot                     | 1         | 1      | 0.34%   |
| KingFast                    | 1         | 1      | 0.34%   |
| JMicron Technology          | 1         | 2      | 0.34%   |
| Hikvision                   | 1         | 1      | 0.34%   |
| Gigabyte Technology         | 1         | 1      | 0.34%   |
| Gateway                     | 1         | 1      | 0.34%   |
| BIWIN                       | 1         | 1      | 0.34%   |
| BHT                         | 1         | 1      | 0.34%   |
| AirDisk                     | 1         | 1      | 0.34%   |
| A-DATA Technology           | 1         | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                                | 17        | 5.65%   |
| Kingston SA400S37480G 480GB SSD                       | 12        | 3.99%   |
| Kingston SA400S37240G 240GB SSD                       | 9         | 2.99%   |
| Unknown DA4032  32GB                                  | 5         | 1.66%   |
| Toshiba MQ01ABF050 500GB                              | 5         | 1.66%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 5         | 1.66%   |
| Unknown MMC Card  64GB                                | 4         | 1.33%   |
| Toshiba MQ01ABD075 752GB                              | 4         | 1.33%   |
| Toshiba HDWK105 500GB                                 | 4         | 1.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB                   | 4         | 1.33%   |
| Seagate ST1000LM035-1RK172 1TB                        | 4         | 1.33%   |
| SanDisk DF4032  32GB                                  | 4         | 1.33%   |
| Unknown MMC Card  128GB                               | 3         | 1%      |
| Toshiba MQ01ABD100 1TB                                | 3         | 1%      |
| SanDisk NVMe SSD Drive 1TB                            | 3         | 1%      |
| Phison PSEIB001TABBMC0 1TB                            | 3         | 1%      |
| Netac SSD 256GB                                       | 3         | 1%      |
| WDC WDS500G2B0B-00YS70 500GB SSD                      | 2         | 0.66%   |
| WDC WD5000BEKT-60KA9T0 500GB                          | 2         | 0.66%   |
| Unknown SD/MMC/MS PRO 2GB                             | 2         | 0.66%   |
| Unknown DA4064  64GB                                  | 2         | 0.66%   |
| Toshiba MQ04ABF100 1TB                                | 2         | 0.66%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB                | 2         | 0.66%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 2         | 0.66%   |
| SanDisk SSD U100 8GB                                  | 2         | 0.66%   |
| SanDisk NVMe SSD Drive 256GB                          | 2         | 0.66%   |
| SanDisk NVMe SSD Drive 1024GB                         | 2         | 0.66%   |
| Realtek Patriot M.2 P300 1024GB                       | 2         | 0.66%   |
| Netac SSD 480GB                                       | 2         | 0.66%   |
| Micron 2450_MTFDKBA512TFK 512GB                       | 2         | 0.66%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB               | 2         | 0.66%   |
| Kingston SA400S37960G 960GB SSD                       | 2         | 0.66%   |
| Intel SSD 660P Series 512GB                           | 2         | 0.66%   |
| Hitachi HTS547564A9E384 640GB                         | 2         | 0.66%   |
| Hitachi HTS545032B9A300 320GB                         | 2         | 0.66%   |
| HGST HTS545050A7E680 500GB                            | 2         | 0.66%   |
| WDC WDS250G2X0C-00L350 250GB                          | 1         | 0.33%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 1         | 0.33%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                      | 1         | 0.33%   |
| WDC WD7500BPVX-22JC3T0 752GB                          | 1         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Toshiba            | 26        | 33     | 28.57%  |
| Seagate            | 24        | 29     | 26.37%  |
| WDC                | 19        | 25     | 20.88%  |
| Hitachi            | 10        | 14     | 10.99%  |
| HGST               | 8         | 9      | 8.79%   |
| Unknown            | 2         | 2      | 2.2%    |
| SAGE               | 1         | 2      | 1.1%    |
| JMicron Technology | 1         | 2      | 1.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 30        | 37     | 37.5%   |
| Samsung Electronics | 7         | 7      | 8.75%   |
| Netac               | 6         | 7      | 7.5%    |
| SanDisk             | 5         | 7      | 6.25%   |
| WDC                 | 4         | 4      | 5%      |
| China               | 4         | 4      | 5%      |
| Intel               | 3         | 3      | 3.75%   |
| Hewlett-Packard     | 3         | 3      | 3.75%   |
| Toshiba             | 2         | 2      | 2.5%    |
| SK hynix            | 2         | 2      | 2.5%    |
| Dahua               | 2         | 4      | 2.5%    |
| Crucial             | 2         | 3      | 2.5%    |
| W800SH              | 1         | 1      | 1.25%   |
| Patriot             | 1         | 1      | 1.25%   |
| Micron Technology   | 1         | 1      | 1.25%   |
| LITEON              | 1         | 1      | 1.25%   |
| Hikvision           | 1         | 1      | 1.25%   |
| Gateway             | 1         | 1      | 1.25%   |
| BIWIN               | 1         | 1      | 1.25%   |
| BHT                 | 1         | 1      | 1.25%   |
| Apple               | 1         | 1      | 1.25%   |
| A-DATA Technology   | 1         | 1      | 1.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 89        | 116    | 31.56%  |
| NVMe    | 77        | 103    | 27.3%   |
| SSD     | 76        | 93     | 26.95%  |
| MMC     | 39        | 48     | 13.83%  |
| Unknown | 1         | 1      | 0.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 151       | 201    | 55.31%  |
| NVMe | 77        | 103    | 28.21%  |
| MMC  | 39        | 48     | 14.29%  |
| SAS  | 6         | 9      | 2.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 118       | 151    | 72.39%  |
| 0.51-1.0   | 42        | 55     | 25.77%  |
| 1.01-2.0   | 2         | 2      | 1.23%   |
| 3.01-4.0   | 1         | 1      | 0.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 73        | 26.16%  |
| 101-250        | 65        | 23.3%   |
| 501-1000       | 39        | 13.98%  |
| 21-50          | 27        | 9.68%   |
| 1-20           | 25        | 8.96%   |
| 51-100         | 18        | 6.45%   |
| 1001-2000      | 17        | 6.09%   |
| Unknown        | 8         | 2.87%   |
| 2001-3000      | 4         | 1.43%   |
| More than 3000 | 3         | 1.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 123       | 41.84%  |
| 21-50          | 56        | 19.05%  |
| 51-100         | 37        | 12.59%  |
| 101-250        | 31        | 10.54%  |
| 251-500        | 23        | 7.82%   |
| 501-1000       | 8         | 2.72%   |
| Unknown        | 8         | 2.72%   |
| 1001-2000      | 3         | 1.02%   |
| More than 3000 | 2         | 0.68%   |
| 0              | 2         | 0.68%   |
| 2001-3000      | 1         | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                         | Notebooks | Drives | Percent |
|---------------------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEKT-60KA9T0 500GB                                  | 2         | 2      | 11.11%  |
| WDC WD5000LPCX-24C6HT0 500GB                                  | 1         | 1      | 5.56%   |
| WDC WD3200BEVT-26ZCT0 320GB                                   | 1         | 1      | 5.56%   |
| WDC WD10SPCX-24HWST1 1TB                                      | 1         | 1      | 5.56%   |
| Toshiba MK5059GSXP 500GB                                      | 1         | 2      | 5.56%   |
| Toshiba MK3265GSX 320GB                                       | 1         | 1      | 5.56%   |
| Toshiba MK3259GSXP 320GB                                      | 1         | 1      | 5.56%   |
| Toshiba MK2555GSX 250GB                                       | 1         | 1      | 5.56%   |
| Seagate ST980811AS 80GB                                       | 1         | 2      | 5.56%   |
| Seagate ST9120821AS 120GB                                     | 1         | 1      | 5.56%   |
| Seagate ST320LT012-1DG14C 320GB                               | 1         | 1      | 5.56%   |
| Seagate ST1000LM035-1RK172 1TB                                | 1         | 1      | 5.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                            | 1         | 1      | 5.56%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD                           | 1         | 1      | 5.56%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 1TB | 1         | 2      | 5.56%   |
| Hitachi HTS547564A9E384 640GB                                 | 1         | 1      | 5.56%   |
| HGST HTS545032A7E380 320GB                                    | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 6      | 29.41%  |
| WDC                 | 4         | 5      | 23.53%  |
| Toshiba             | 4         | 5      | 23.53%  |
| SanDisk             | 1         | 1      | 5.88%   |
| Samsung Electronics | 1         | 2      | 5.88%   |
| Hitachi             | 1         | 1      | 5.88%   |
| HGST                | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 6      | 33.33%  |
| WDC     | 4         | 5      | 26.67%  |
| Toshiba | 4         | 5      | 26.67%  |
| Hitachi | 1         | 1      | 6.67%   |
| HGST    | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 18     | 88.24%  |
| NVMe | 1         | 2      | 5.88%   |
| SSD  | 1         | 1      | 5.88%   |

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
| Detected | 163       | 216    | 61.05%  |
| Works    | 87        | 124    | 32.58%  |
| Malfunc  | 17        | 21     | 6.37%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 177       | 61.25%  |
| AMD                              | 37        | 12.8%   |
| SanDisk                          | 16        | 5.54%   |
| Samsung Electronics              | 12        | 4.15%   |
| SK hynix                         | 8         | 2.77%   |
| Kingston Technology Company      | 8         | 2.77%   |
| Micron Technology                | 7         | 2.42%   |
| Toshiba America Info Systems     | 5         | 1.73%   |
| Phison Electronics               | 5         | 1.73%   |
| Silicon Motion                   | 3         | 1.04%   |
| Realtek Semiconductor            | 3         | 1.04%   |
| KIOXIA                           | 2         | 0.69%   |
| Union Memory (Shenzhen)          | 1         | 0.35%   |
| Silicon Integrated Systems [SiS] | 1         | 0.35%   |
| Micron/Crucial Technology        | 1         | 0.35%   |
| Marvell Technology Group         | 1         | 0.35%   |
| Lite-On Technology               | 1         | 0.35%   |
| Apple                            | 1         | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 33        | 10.78%  |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 19        | 6.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 18        | 5.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 12        | 3.92%   |
| Intel Volume Management Device NVMe RAID Controller                              | 11        | 3.59%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 11        | 3.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 3.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 8         | 2.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 2.61%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 7         | 2.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 1.96%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 5         | 1.63%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 5         | 1.63%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 5         | 1.63%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 5         | 1.63%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 1.63%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 1.63%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 5         | 1.63%   |
| Intel SSD 660P Series                                                            | 4         | 1.31%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 1.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 1.31%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 0.98%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 3         | 0.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 0.98%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3         | 0.98%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                | 3         | 0.98%   |
| Phison E18 PCIe4 NVMe Controller                                                 | 3         | 0.98%   |
| Micron 2400 NVMe SSD (DRAM-less)                                                 | 3         | 0.98%   |
| Intel Tiger Lake-LP SATA Controller                                              | 3         | 0.98%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 3         | 0.98%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 0.98%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 0.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 0.98%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 2         | 0.65%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                            | 2         | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.65%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 2         | 0.65%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 2         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 188       | 62.67%  |
| NVMe | 77        | 25.67%  |
| RAID | 23        | 7.67%   |
| IDE  | 12        | 4%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 204       | 78.16%  |
| AMD    | 57        | 21.84%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Celeron CPU N3350 @ 1.10GHz       | 19        | 7.25%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 5         | 1.91%   |
| Intel 12th Gen Core i7-1255U            | 5         | 1.91%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 1.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 1.53%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 4         | 1.53%   |
| Intel Celeron CPU N3160 @ 1.60GHz       | 4         | 1.53%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 1.15%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 3         | 1.15%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 3         | 1.15%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 1.15%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 3         | 1.15%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 1.15%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 3         | 1.15%   |
| Intel Celeron N4500 @ 1.10GHz           | 3         | 1.15%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 3         | 1.15%   |
| Intel Celeron N4000 CPU @ 1.10GHz       | 3         | 1.15%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 3         | 1.15%   |
| Intel Celeron CPU N3050 @ 1.60GHz       | 3         | 1.15%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 1.15%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 1.15%   |
| AMD Ryzen 9 4900HS with Radeon Graphics | 3         | 1.15%   |
| AMD Ryzen 7 7736U with Radeon Graphics  | 3         | 1.15%   |
| AMD E-300 APU with Radeon HD Graphics   | 3         | 1.15%   |
| Intel Pentium CPU P6200 @ 2.13GHz       | 2         | 0.76%   |
| Intel Pentium CPU N3710 @ 1.60GHz       | 2         | 0.76%   |
| Intel Pentium CPU 2117U @ 1.80GHz       | 2         | 0.76%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 0.76%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 2         | 0.76%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 0.76%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 0.76%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 2         | 0.76%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 2         | 0.76%   |
| Intel Core i5-4200M CPU @ 2.50GHz       | 2         | 0.76%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 2         | 0.76%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 0.76%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz      | 2         | 0.76%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 2         | 0.76%   |
| Intel Core i3-7100U CPU @ 2.40GHz       | 2         | 0.76%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 2         | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 52        | 19.85%  |
| Intel Core i7           | 43        | 16.41%  |
| Intel Core i5           | 40        | 15.27%  |
| Other                   | 22        | 8.4%    |
| Intel Core i3           | 20        | 7.63%   |
| AMD Ryzen 7             | 11        | 4.2%    |
| Intel Pentium           | 9         | 3.44%   |
| Intel Atom              | 8         | 3.05%   |
| AMD A6                  | 7         | 2.67%   |
| AMD Ryzen 5             | 6         | 2.29%   |
| AMD Ryzen 9             | 5         | 1.91%   |
| Intel Core 2 Duo        | 4         | 1.53%   |
| AMD E                   | 4         | 1.53%   |
| Intel Core              | 3         | 1.15%   |
| AMD Ryzen 3             | 3         | 1.15%   |
| AMD E2                  | 3         | 1.15%   |
| AMD E1                  | 3         | 1.15%   |
| Intel Genuine           | 2         | 0.76%   |
| Intel Core 2            | 2         | 0.76%   |
| AMD Ryzen 5 PRO         | 2         | 0.76%   |
| AMD A8                  | 2         | 0.76%   |
| Intel Pentium Dual-Core | 1         | 0.38%   |
| Intel Pentium Dual      | 1         | 0.38%   |
| Intel Core m3           | 1         | 0.38%   |
| Intel Celeron Dual-Core | 1         | 0.38%   |
| AMD PRO A10             | 1         | 0.38%   |
| AMD Phenom II           | 1         | 0.38%   |
| AMD FX                  | 1         | 0.38%   |
| AMD Athlon II           | 1         | 0.38%   |
| AMD Athlon              | 1         | 0.38%   |
| AMD A4                  | 1         | 0.38%   |
| AMD A10                 | 1         | 0.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 142       | 54.41%  |
| 4      | 74        | 28.35%  |
| 6      | 15        | 5.75%   |
| 8      | 14        | 5.36%   |
| 10     | 6         | 2.3%    |
| 1      | 5         | 1.92%   |
| 14     | 2         | 0.77%   |
| 12     | 2         | 0.77%   |
| 16     | 1         | 0.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 261       | 99.62%  |
| 2      | 1         | 0.38%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 158       | 60.54%  |
| 1      | 103       | 39.46%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 257       | 98.47%  |
| Unknown        | 3         | 1.15%   |
| 32-bit         | 1         | 0.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 132       | 48.89%  |
| 0x406c4    | 7         | 2.59%   |
| 0x40651    | 7         | 2.59%   |
| 0x206a7    | 7         | 2.59%   |
| 0x506c9    | 6         | 2.22%   |
| 0x20655    | 6         | 2.22%   |
| 0x806ec    | 5         | 1.85%   |
| 0x406e3    | 5         | 1.85%   |
| 0x306d4    | 5         | 1.85%   |
| 0x806ea    | 4         | 1.48%   |
| 0x806e9    | 4         | 1.48%   |
| 0x406c3    | 4         | 1.48%   |
| 0x30678    | 4         | 1.48%   |
| 0x08108109 | 4         | 1.48%   |
| 0x06006705 | 4         | 1.48%   |
| 0x906ea    | 3         | 1.11%   |
| 0x806c1    | 3         | 1.11%   |
| 0x706e5    | 3         | 1.11%   |
| 0x706a1    | 3         | 1.11%   |
| 0x6fd      | 3         | 1.11%   |
| 0x306c3    | 3         | 1.11%   |
| 0x306a9    | 3         | 1.11%   |
| 0x806eb    | 2         | 0.74%   |
| 0x506e3    | 2         | 0.74%   |
| 0x1067a    | 2         | 0.74%   |
| 0x0a50000c | 2         | 0.74%   |
| 0x08600104 | 2         | 0.74%   |
| 0x0810100b | 2         | 0.74%   |
| 0x07030105 | 2         | 0.74%   |
| 0x07030104 | 2         | 0.74%   |
| 0x0700010f | 2         | 0.74%   |
| 0x05000119 | 2         | 0.74%   |
| 0xa0652    | 1         | 0.37%   |
| 0x906a4    | 1         | 0.37%   |
| 0x706a8    | 1         | 0.37%   |
| 0x6f2      | 1         | 0.37%   |
| 0x30673    | 1         | 0.37%   |
| 0x30661    | 1         | 0.37%   |
| 0x106e5    | 1         | 0.37%   |
| 0x106ca    | 1         | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 30        | 11.45%  |
| Silvermont        | 24        | 9.16%   |
| Goldmont          | 19        | 7.25%   |
| Haswell           | 17        | 6.49%   |
| Unknown           | 17        | 6.49%   |
| Skylake           | 16        | 6.11%   |
| SandyBridge       | 14        | 5.34%   |
| IvyBridge         | 11        | 4.2%    |
| TigerLake         | 9         | 3.44%   |
| Excavator         | 9         | 3.44%   |
| Broadwell         | 8         | 3.05%   |
| Zen 3             | 7         | 2.67%   |
| Zen 2             | 7         | 2.67%   |
| Westmere          | 7         | 2.67%   |
| IceLake           | 7         | 2.67%   |
| Goldmont plus     | 7         | 2.67%   |
| Core              | 7         | 2.67%   |
| Zen+              | 6         | 2.29%   |
| Puma              | 6         | 2.29%   |
| Bobcat            | 5         | 1.91%   |
| Alderlake Hybrid  | 5         | 1.91%   |
| Penryn            | 4         | 1.53%   |
| Tremont           | 3         | 1.15%   |
| Jaguar            | 3         | 1.15%   |
| CometLake         | 3         | 1.15%   |
| Bonnell           | 3         | 1.15%   |
| Zen               | 2         | 0.76%   |
| Piledriver        | 2         | 0.76%   |
| K10               | 2         | 0.76%   |
| Nehalem           | 1         | 0.38%   |
| Meteorlake Hybrid | 1         | 0.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 201       | 66.12%  |
| AMD                              | 66        | 21.71%  |
| Nvidia                           | 36        | 11.84%  |
| Silicon Integrated Systems [SiS] | 1         | 0.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 19        | 6.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16        | 5.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 4.46%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 3.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 3.18%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 9         | 2.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 2.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 2.23%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 2.23%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 2.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 2.23%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 7         | 2.23%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 7         | 2.23%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 6         | 1.91%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 6         | 1.91%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 1.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1.91%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.59%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 5         | 1.59%   |
| Intel JasperLake [UHD Graphics]                                                          | 5         | 1.59%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.59%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 5         | 1.59%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.59%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 1.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 1.27%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.27%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 4         | 1.27%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 1.27%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 1.27%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.27%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.96%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 3         | 0.96%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.96%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.96%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 0.96%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.96%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.96%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.96%   |
| AMD Rembrandt [Radeon 680M]                                                              | 3         | 0.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 165       | 63.22%  |
| 1 x AMD        | 45        | 17.24%  |
| Intel + Nvidia | 25        | 9.58%   |
| Intel + AMD    | 9         | 3.45%   |
| AMD + Nvidia   | 9         | 3.45%   |
| 2 x AMD        | 3         | 1.15%   |
| 2 x Intel      | 2         | 0.77%   |
| 1 x Nvidia     | 2         | 0.77%   |
| 1 x SiS        | 1         | 0.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 239       | 90.87%  |
| Proprietary | 13        | 4.94%   |
| Unknown     | 11        | 4.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 200       | 75.47%  |
| 0.01-0.5   | 27        | 10.19%  |
| 1.01-2.0   | 13        | 4.91%   |
| 0.51-1.0   | 11        | 4.15%   |
| 3.01-4.0   | 7         | 2.64%   |
| 5.01-6.0   | 4         | 1.51%   |
| 7.01-8.0   | 2         | 0.75%   |
| 8.01-16.0  | 1         | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 43        | 15.03%  |
| LG Display              | 42        | 14.69%  |
| Chimei Innolux          | 39        | 13.64%  |
| AU Optronics            | 39        | 13.64%  |
| Samsung Electronics     | 35        | 12.24%  |
| PANDA                   | 8         | 2.8%    |
| KDC                     | 8         | 2.8%    |
| InfoVision              | 8         | 2.8%    |
| ViewSonic               | 6         | 2.1%    |
| Sharp                   | 5         | 1.75%   |
| Chi Mei Optoelectronics | 5         | 1.75%   |
| Philips                 | 4         | 1.4%    |
| Dell                    | 4         | 1.4%    |
| Apple                   | 4         | 1.4%    |
| Toshiba                 | 3         | 1.05%   |
| Acer                    | 3         | 1.05%   |
| Valve                   | 2         | 0.7%    |
| Mi                      | 2         | 0.7%    |
| LG Philips              | 2         | 0.7%    |
| Lenovo                  | 2         | 0.7%    |
| KTC                     | 2         | 0.7%    |
| HSI                     | 2         | 0.7%    |
| Hewlett-Packard         | 2         | 0.7%    |
| Goldstar                | 2         | 0.7%    |
| TopView                 | 1         | 0.35%   |
| TMX                     | 1         | 0.35%   |
| Sun                     | 1         | 0.35%   |
| Sony                    | 1         | 0.35%   |
| Quanta Display          | 1         | 0.35%   |
| Konka                   | 1         | 0.35%   |
| JDI                     | 1         | 0.35%   |
| InnoLux Display         | 1         | 0.35%   |
| HKC                     | 1         | 0.35%   |
| Hitachi                 | 1         | 0.35%   |
| CPT                     | 1         | 0.35%   |
| AOC                     | 1         | 0.35%   |
| Ancor Communications    | 1         | 0.35%   |
| AGO                     | 1         | 0.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| KDC LCD Monitor KDC05F1 1366x768 344x193mm 15.5-inch                  | 6         | 2.06%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch          | 6         | 2.06%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 4         | 1.37%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                 | 3         | 1.03%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 3         | 1.03%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 1.03%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch       | 3         | 1.03%   |
| AU Optronics LCD Monitor AUOA49A 1920x1200 301x188mm 14.0-inch        | 3         | 1.03%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 1.03%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch         | 2         | 0.69%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 2         | 0.69%   |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch               | 2         | 0.69%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch     | 2         | 0.69%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 2         | 0.69%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 2         | 0.69%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch  | 2         | 0.69%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch  | 2         | 0.69%   |
| Samsung Electronics LCD Monitor SDC41A0 1920x1200 302x189mm 14.0-inch | 2         | 0.69%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 2         | 0.69%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch  | 2         | 0.69%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 0.69%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.69%   |
| Philips FTV PHL04C3 1920x1080 1440x810mm 65.0-inch                    | 2         | 0.69%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 2         | 0.69%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.69%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch           | 2         | 0.69%   |
| LG Display LCD Monitor LGD0396 1600x900 382x215mm 17.3-inch           | 2         | 0.69%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 2         | 0.69%   |
| HSI HiTV HSI0001 1920x1080 708x398mm 32.0-inch                        | 2         | 0.69%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                     | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch       | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch       | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch       | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 2         | 0.69%   |
| BOE LCD Monitor BOE0A56 1920x1080 344x194mm 15.5-inch                 | 2         | 0.69%   |
| BOE LCD Monitor BOE08C2 1920x1080 344x194mm 15.5-inch                 | 2         | 0.69%   |
| BOE LCD Monitor BOE0731 1366x768 256x144mm 11.6-inch                  | 2         | 0.69%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 2         | 0.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 117       | 44.83%  |
| 1920x1080 (FHD)   | 80        | 30.65%  |
| 1920x1200 (WUXGA) | 14        | 5.36%   |
| 1600x900 (HD+)    | 10        | 3.83%   |
| 3840x2160 (4K)    | 9         | 3.45%   |
| 1280x800 (WXGA)   | 7         | 2.68%   |
| 2560x1600         | 5         | 1.92%   |
| 2560x1440 (QHD)   | 4         | 1.53%   |
| 800x1280          | 2         | 0.77%   |
| 2160x1440         | 2         | 0.77%   |
| 1440x900 (WXGA+)  | 2         | 0.77%   |
| 1024x600          | 2         | 0.77%   |
| 3440x1440         | 1         | 0.38%   |
| 3200x1800 (QHD+)  | 1         | 0.38%   |
| 2880x1800         | 1         | 0.38%   |
| 2288x1287         | 1         | 0.38%   |
| 1920x540          | 1         | 0.38%   |
| 1680x945          | 1         | 0.38%   |
| 1360x768          | 1         | 0.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 111       | 38.54%  |
| 14     | 55        | 19.1%   |
| 13     | 34        | 11.81%  |
| 11     | 16        | 5.56%   |
| 21     | 11        | 3.82%   |
| 17     | 11        | 3.82%   |
| 23     | 9         | 3.13%   |
| 24     | 5         | 1.74%   |
| 12     | 5         | 1.74%   |
| 18     | 4         | 1.39%   |
| 86     | 3         | 1.04%   |
| 34     | 3         | 1.04%   |
| 65     | 2         | 0.69%   |
| 40     | 2         | 0.69%   |
| 27     | 2         | 0.69%   |
| 16     | 2         | 0.69%   |
| 10     | 2         | 0.69%   |
| 7      | 2         | 0.69%   |
| 57     | 1         | 0.35%   |
| 52     | 1         | 0.35%   |
| 48     | 1         | 0.35%   |
| 47     | 1         | 0.35%   |
| 46     | 1         | 0.35%   |
| 29     | 1         | 0.35%   |
| 26     | 1         | 0.35%   |
| 20     | 1         | 0.35%   |
| 8      | 1         | 0.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 187       | 65.61%  |
| 201-300     | 33        | 11.58%  |
| 501-600     | 17        | 5.96%   |
| 401-500     | 16        | 5.61%   |
| 351-400     | 13        | 4.56%   |
| 1001-1500   | 10        | 3.51%   |
| 701-800     | 3         | 1.05%   |
| 801-900     | 2         | 0.7%    |
| 1-100       | 2         | 0.7%    |
| 601-700     | 1         | 0.35%   |
| 101-200     | 1         | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 214       | 85.26%  |
| 16/10 | 25        | 9.96%   |
| 21/9  | 3         | 1.2%    |
| 0.56  | 3         | 1.2%    |
| 3/2   | 2         | 0.8%    |
| 0.67  | 2         | 0.8%    |
| 4/3   | 1         | 0.4%    |
| 1.96  | 1         | 0.4%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 111       | 38.54%  |
| 81-90          | 81        | 28.13%  |
| 201-250        | 23        | 7.99%   |
| 51-60          | 16        | 5.56%   |
| 121-130        | 10        | 3.47%   |
| 71-80          | 9         | 3.13%   |
| More than 1000 | 7         | 2.43%   |
| 501-1000       | 5         | 1.74%   |
| 351-500        | 4         | 1.39%   |
| 151-200        | 4         | 1.39%   |
| 141-150        | 4         | 1.39%   |
| 61-70          | 3         | 1.04%   |
| 1-40           | 3         | 1.04%   |
| 301-350        | 3         | 1.04%   |
| 41-50          | 2         | 0.69%   |
| 111-120        | 2         | 0.69%   |
| 131-140        | 1         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 123       | 43.31%  |
| 121-160       | 85        | 29.93%  |
| 51-100        | 37        | 13.03%  |
| 161-240       | 24        | 8.45%   |
| 1-50          | 10        | 3.52%   |
| More than 240 | 5         | 1.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 214       | 80.15%  |
| 2     | 44        | 16.48%  |
| 0     | 5         | 1.87%   |
| 3     | 4         | 1.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 126       | 32.64%  |
| Intel                            | 125       | 32.38%  |
| Qualcomm Atheros                 | 48        | 12.44%  |
| Broadcom                         | 27        | 6.99%   |
| MediaTek                         | 13        | 3.37%   |
| Broadcom Limited                 | 6         | 1.55%   |
| TP-Link                          | 5         | 1.3%    |
| Ralink Technology                | 5         | 1.3%    |
| Ralink                           | 5         | 1.3%    |
| Samsung Electronics              | 4         | 1.04%   |
| ASIX Electronics                 | 4         | 1.04%   |
| Qualcomm Technologies            | 3         | 0.78%   |
| Huawei Technologies              | 3         | 0.78%   |
| Xiaomi                           | 2         | 0.52%   |
| Qualcomm Atheros Communications  | 2         | 0.52%   |
| T & A Mobile Phones              | 1         | 0.26%   |
| Silicon Integrated Systems [SiS] | 1         | 0.26%   |
| Sierra Wireless                  | 1         | 0.26%   |
| Shenzhen Goodix Technology       | 1         | 0.26%   |
| Motorola PCS                     | 1         | 0.26%   |
| Marvell Technology Group         | 1         | 0.26%   |
| Lenovo                           | 1         | 0.26%   |
| DisplayLink                      | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 61        | 13.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 34        | 7.62%   |
| Intel Wireless 3165                                                     | 29        | 6.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 13        | 2.91%   |
| Intel Wireless 7265                                                     | 11        | 2.47%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 2.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 2.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 2.02%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 2.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 1.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.57%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 7         | 1.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 1.57%   |
| Intel Wireless 7260                                                     | 7         | 1.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 1.57%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 6         | 1.35%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 6         | 1.35%   |
| Intel Wireless 8260                                                     | 6         | 1.35%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 1.35%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 1.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 1.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 0.9%    |
| Ralink MT7601U Wireless Adapter                                         | 4         | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 0.9%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 3         | 0.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.67%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 3         | 0.67%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 3         | 0.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.67%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]    | 3         | 0.67%   |
| Intel Wireless 8265 / 8275                                              | 3         | 0.67%   |
| Intel Wireless 3160                                                     | 3         | 0.67%   |
| Intel Ethernet Connection I219-LM                                       | 3         | 0.67%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 0.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 0.67%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 120       | 45.11%  |
| Realtek Semiconductor           | 54        | 20.3%   |
| Qualcomm Atheros                | 37        | 13.91%  |
| Broadcom                        | 21        | 7.89%   |
| MediaTek                        | 11        | 4.14%   |
| Ralink Technology               | 5         | 1.88%   |
| Ralink                          | 5         | 1.88%   |
| Broadcom Limited                | 4         | 1.5%    |
| TP-Link                         | 3         | 1.13%   |
| Qualcomm Technologies           | 3         | 1.13%   |
| Qualcomm Atheros Communications | 2         | 0.75%   |
| Sierra Wireless                 | 1         | 0.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                                     | 29        | 10.86%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 13        | 4.87%   |
| Intel Wireless 7265                                                     | 11        | 4.12%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 3.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 3.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 3.37%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 3.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 3%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.62%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 7         | 2.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 2.62%   |
| Intel Wireless 7260                                                     | 7         | 2.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 2.62%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 6         | 2.25%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 6         | 2.25%   |
| Intel Wireless 8260                                                     | 6         | 2.25%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 2.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 1.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.5%    |
| Ralink MT7601U Wireless Adapter                                         | 4         | 1.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 1.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.12%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.12%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 3         | 1.12%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.12%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]    | 3         | 1.12%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.12%   |
| Intel Wireless 3160                                                     | 3         | 1.12%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.12%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.12%   |
| TP-Link 802.11ac NIC                                                    | 2         | 0.75%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.75%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.75%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.75%   |
| Intel Meteor Lake PCH CNVi WiFi                                         | 2         | 0.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 100       | 56.5%   |
| Intel                            | 31        | 17.51%  |
| Qualcomm Atheros                 | 14        | 7.91%   |
| Broadcom                         | 8         | 4.52%   |
| ASIX Electronics                 | 4         | 2.26%   |
| Samsung Electronics              | 3         | 1.69%   |
| Huawei Technologies              | 3         | 1.69%   |
| Xiaomi                           | 2         | 1.13%   |
| TP-Link                          | 2         | 1.13%   |
| MediaTek                         | 2         | 1.13%   |
| Broadcom Limited                 | 2         | 1.13%   |
| T & A Mobile Phones              | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] | 1         | 0.56%   |
| Motorola PCS                     | 1         | 0.56%   |
| Marvell Technology Group         | 1         | 0.56%   |
| Lenovo                           | 1         | 0.56%   |
| DisplayLink                      | 1         | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 61        | 34.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 34        | 19.21%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 2.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 1.69%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 1.69%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 1.69%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 1.69%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 1.69%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 1.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 1.13%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 2         | 1.13%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 1.13%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 2         | 1.13%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 1.13%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 1.13%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 1.13%   |
| Intel PRO/100 VE Network Connection                                    | 2         | 1.13%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 1.13%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 1.13%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 1.13%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 1.13%   |
| Intel Ethernet Connection (13) I219-V                                  | 2         | 1.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 1.13%   |
| Huawei E353/E3131                                                      | 2         | 1.13%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 2         | 1.13%   |
| T & A Mobile Phones TCL 50 XL 5G                                       | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.56%   |
| Realtek PCIe GbE Family Controller                                     | 1         | 0.56%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.56%   |
| Motorola PCS motorola one 5G ace                                       | 1         | 0.56%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1         | 0.56%   |
| MediaTek Infinix HOT 50i                                               | 1         | 0.56%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                   | 1         | 0.56%   |
| Lenovo Lenovo USB-C to LAN                                             | 1         | 0.56%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.56%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 249       | 59.57%  |
| Ethernet | 167       | 39.95%  |
| Modem    | 2         | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 219       | 84.23%  |
| Ethernet | 41        | 15.77%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 144       | 54.96%  |
| 1     | 109       | 41.6%   |
| 0     | 7         | 2.67%   |
| 3     | 2         | 0.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 161       | 59.63%  |
| Yes  | 109       | 40.37%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 107       | 51.44%  |
| Realtek Semiconductor           | 29        | 13.94%  |
| IMC Networks                    | 17        | 8.17%   |
| Qualcomm Atheros Communications | 14        | 6.73%   |
| Toshiba                         | 8         | 3.85%   |
| Foxconn / Hon Hai               | 6         | 2.88%   |
| Broadcom                        | 6         | 2.88%   |
| Lite-On Technology              | 5         | 2.4%    |
| USI                             | 3         | 1.44%   |
| Ralink                          | 3         | 1.44%   |
| Cambridge Silicon Radio         | 3         | 1.44%   |
| Apple                           | 3         | 1.44%   |
| Ralink Technology               | 2         | 0.96%   |
| Foxconn International           | 1         | 0.48%   |
| Alps Electric                   | 1         | 0.48%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 58        | 27.88%  |
| Intel AX201 Bluetooth                               | 15        | 7.21%   |
| Realtek  Bluetooth 4.2 Adapter                      | 14        | 6.73%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 12        | 5.77%   |
| Realtek Bluetooth Radio                             | 10        | 4.81%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 4.33%   |
| Intel AX200 Bluetooth                               | 8         | 3.85%   |
| IMC Networks Wireless_Device                        | 7         | 3.37%   |
| Intel Bluetooth Device                              | 6         | 2.88%   |
| IMC Networks Bluetooth Radio                        | 6         | 2.88%   |
| Toshiba BCM43142A0                                  | 4         | 1.92%   |
| USI Bluetooth Device                                | 3         | 1.44%   |
| Toshiba Bluetooth Device                            | 3         | 1.44%   |
| Ralink RT3290 Bluetooth                             | 3         | 1.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.44%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.44%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.44%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.44%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.96%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 0.96%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.96%   |
| Lite-On Bluetooth Device                            | 2         | 0.96%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.96%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.96%   |
| Intel AX210 Bluetooth                               | 2         | 0.96%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 0.96%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.96%   |
| Toshiba Bluetooth Radio                             | 1         | 0.48%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.48%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.48%   |
| Ralink CSR BS8510                                   | 1         | 0.48%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.48%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.48%   |
| IMC Networks Bluetooth Device                       | 1         | 0.48%   |
| IMC Networks Bluetooth                              | 1         | 0.48%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.48%   |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 0.48%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.48%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.48%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth         | 1         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 198       | 66.44%  |
| AMD                                          | 57        | 19.13%  |
| Nvidia                                       | 24        | 8.05%   |
| Logitech                                     | 6         | 2.01%   |
| Generalplus Technology                       | 2         | 0.67%   |
| C-Media Electronics                          | 2         | 0.67%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.34%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.34%   |
| Texas Instruments                            | 1         | 0.34%   |
| Tenx Technology                              | 1         | 0.34%   |
| Sony                                         | 1         | 0.34%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.34%   |
| Kingston Technology                          | 1         | 0.34%   |
| DSEA A/S                                     | 1         | 0.34%   |
| ASUSTek Computer                             | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 25        | 6.72%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 5.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 19        | 5.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 15        | 4.03%   |
| AMD FCH Azalia Controller                                                                         | 14        | 3.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 13        | 3.49%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 13        | 3.49%   |
| AMD Kabini HDMI/DP Audio                                                                          | 12        | 3.23%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 2.69%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 2.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 2.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 2.42%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 9         | 2.42%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 9         | 2.42%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 2.15%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 2.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 2.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 1.88%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 1.88%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 1.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 1.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 1.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 1.88%   |
| AMD Radeon High Definition Audio Controller                                                       | 7         | 1.88%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 6         | 1.61%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 1.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 1.61%   |
| AMD High Definition Audio Controller                                                              | 6         | 1.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 1.34%   |
| Intel Jasper Lake HD Audio                                                                        | 5         | 1.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.34%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.08%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 1.08%   |
| AMD Wrestler HDMI Audio                                                                           | 4         | 1.08%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.81%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.81%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 45        | 27.27%  |
| SK hynix            | 24        | 14.55%  |
| Micron Technology   | 19        | 11.52%  |
| Kingston            | 13        | 7.88%   |
| Unknown             | 12        | 7.27%   |
| Ramaxel Technology  | 12        | 7.27%   |
| Goldkey             | 8         | 4.85%   |
| A-DATA Technology   | 8         | 4.85%   |
| Crucial             | 7         | 4.24%   |
| Elpida              | 5         | 3.03%   |
| Nanya Technology    | 2         | 1.21%   |
| Unknown (8AD6)      | 1         | 0.61%   |
| Unknown (2C0B)      | 1         | 0.61%   |
| Team                | 1         | 0.61%   |
| Patriot             | 1         | 0.61%   |
| Mushkin             | 1         | 0.61%   |
| Hikvision           | 1         | 0.61%   |
| ff                  | 1         | 0.61%   |
| Corsair             | 1         | 0.61%   |
| 4ea5                | 1         | 0.61%   |
| Unknown             | 1         | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Goldkey RAM GKH200SO25608-1600 2GB SODIMM DDR3 1600MT/s       | 5         | 2.91%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 4         | 2.33%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                   | 3         | 1.74%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 3         | 1.74%   |
| Samsung RAM K3LK6K60BM-BGCP 8GB LPDDR5 6400MT/s               | 3         | 1.74%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s       | 3         | 1.74%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s          | 3         | 1.74%   |
| Goldkey RAM GKH400SO25608-1600 4GB SODIMM DDR3 1600MT/s       | 3         | 1.74%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                | 2         | 1.16%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                  | 2         | 1.16%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s    | 2         | 1.16%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                   | 2         | 1.16%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s         | 2         | 1.16%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s         | 2         | 1.16%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 2         | 1.16%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s         | 2         | 1.16%   |
| Samsung RAM K4EBE304ED-EGCG 8GB Row Of Chips LPDDR3 2133MT/s  | 2         | 1.16%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s     | 2         | 1.16%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.16%   |
| Kingston RAM 9905700-101.A00G 16GB SODIMM DDR4 3200MT/s       | 2         | 1.16%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s         | 2         | 1.16%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                   | 1         | 0.58%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                   | 1         | 0.58%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                   | 1         | 0.58%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2400MT/s                 | 1         | 0.58%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                    | 1         | 0.58%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                  | 1         | 0.58%   |
| Unknown (8AD6) RAM FD4AS3200CQGZZ 16GB SODIMM DDR4 3200MT/s   | 1         | 0.58%   |
| Unknown (2C0B) RAM Module 16GB SODIMM DDR4 2133MT/s           | 1         | 0.58%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s          | 1         | 0.58%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                 | 1         | 0.58%   |
| SK hynix RAM Module 1GB SODIMM DDR2 533MT/s                   | 1         | 0.58%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 0.58%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s        | 1         | 0.58%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 0.58%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s        | 1         | 0.58%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s         | 1         | 0.58%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s       | 1         | 0.58%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 1         | 0.58%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 55        | 41.35%  |
| DDR3   | 50        | 37.59%  |
| LPDDR4 | 8         | 6.02%   |
| LPDDR3 | 5         | 3.76%   |
| DDR2   | 5         | 3.76%   |
| LPDDR5 | 4         | 3.01%   |
| SDRAM  | 3         | 2.26%   |
| DDR5   | 3         | 2.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 111       | 83.46%  |
| Row Of Chips | 15        | 11.28%  |
| Unknown      | 4         | 3.01%   |
| DIMM         | 3         | 2.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 52        | 32.5%   |
| 4096  | 44        | 27.5%   |
| 16384 | 25        | 15.63%  |
| 2048  | 23        | 14.38%  |
| 32768 | 9         | 5.63%   |
| 1024  | 4         | 2.5%    |
| 512   | 3         | 1.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 43        | 29.66%  |
| 3200  | 28        | 19.31%  |
| 2667  | 22        | 15.17%  |
| 2400  | 11        | 7.59%   |
| 2133  | 7         | 4.83%   |
| 1334  | 5         | 3.45%   |
| 1333  | 5         | 3.45%   |
| 533   | 5         | 3.45%   |
| 6400  | 3         | 2.07%   |
| 4800  | 3         | 2.07%   |
| 3266  | 3         | 2.07%   |
| 4267  | 2         | 1.38%   |
| 4199  | 2         | 1.38%   |
| 7500  | 1         | 0.69%   |
| 4266  | 1         | 0.69%   |
| 3733  | 1         | 0.69%   |
| 2048  | 1         | 0.69%   |
| 1867  | 1         | 0.69%   |
| 1067  | 1         | 0.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Samsung M2020 Series | 1         | 100%    |

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
| Chicony Electronics                    | 61        | 25.52%  |
| Sunplus Innovation Technology          | 20        | 8.37%   |
| Realtek Semiconductor                  | 19        | 7.95%   |
| Bison Electronics                      | 18        | 7.53%   |
| IMC Networks                           | 15        | 6.28%   |
| Cheng Uei Precision Industry (Foxlink) | 15        | 6.28%   |
| Microdia                               | 14        | 5.86%   |
| Quanta                                 | 11        | 4.6%    |
| Suyin                                  | 10        | 4.18%   |
| Silicon Motion                         | 6         | 2.51%   |
| Lite-On Technology                     | 6         | 2.51%   |
| Unknown                                | 5         | 2.09%   |
| Syntek                                 | 5         | 2.09%   |
| Sonix Technology                       | 5         | 2.09%   |
| Luxvisions Innotech Limited            | 4         | 1.67%   |
| Importek                               | 4         | 1.67%   |
| Alcor Micro                            | 4         | 1.67%   |
| Samsung Electronics                    | 3         | 1.26%   |
| SunplusIT                              | 2         | 0.84%   |
| Shinetech                              | 2         | 0.84%   |
| Logitech                               | 2         | 0.84%   |
| Apple                                  | 2         | 0.84%   |
| Acer                                   | 2         | 0.84%   |
| Primax Electronics                     | 1         | 0.42%   |
| OYT Tech                               | 1         | 0.42%   |
| Novatek Microelectronics               | 1         | 0.42%   |
| DigiTech                               | 1         | 0.42%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD camera                                              | 19        | 7.95%   |
| Chicony Integrated Camera                                      | 11        | 4.6%    |
| Chicony HP TrueVision HD                                       | 7         | 2.93%   |
| Bison Integrated Camera                                        | 7         | 2.93%   |
| Realtek Integrated_Webcam_HD                                   | 6         | 2.51%   |
| Chicony TOSHIBA Web Camera - HD                                | 6         | 2.51%   |
| Unknown USB Camera                                             | 5         | 2.09%   |
| Microdia Integrated_Webcam_HD                                  | 5         | 2.09%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 5         | 2.09%   |
| Sunplus Integrated_Webcam_HD                                   | 4         | 1.67%   |
| Realtek Lenovo EasyCamera                                      | 4         | 1.67%   |
| Quanta HD Webcam                                               | 4         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 4         | 1.67%   |
| Bison HD Webcam                                                | 4         | 1.67%   |
| Sunplus HP X Camera                                            | 3         | 1.26%   |
| Sonix USB2.0 HD UVC WebCam                                     | 3         | 1.26%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 3         | 1.26%   |
| Quanta HP TrueVision HD Camera                                 | 3         | 1.26%   |
| Lite-On HP Webcam                                              | 3         | 1.26%   |
| IMC Networks USB2.0 HD IR UVC WebCam                           | 3         | 1.26%   |
| IMC Networks Integrated Camera                                 | 3         | 1.26%   |
| Chicony HP Webcam                                              | 3         | 1.26%   |
| Chicony HD WebCam                                              | 3         | 1.26%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 1.26%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 3         | 1.26%   |
| Alcor Micro USB 2.0 Camera                                     | 3         | 1.26%   |
| Syntek Integrated Camera                                       | 2         | 0.84%   |
| Suyin HP Truevision HD                                         | 2         | 0.84%   |
| Suyin Asus Integrated Webcam                                   | 2         | 0.84%   |
| Sunplus SPCA2281 Web Camera                                    | 2         | 0.84%   |
| Sunplus Laptop Integrated Webcam HD                            | 2         | 0.84%   |
| Sonix USB2.0 FHD UVC WebCam                                    | 2         | 0.84%   |
| Silicon Motion WebCam SC-13HDL11939N                           | 2         | 0.84%   |
| Silicon Motion WebCam SC-0311139N                              | 2         | 0.84%   |
| Shinetech USB2.0 FHD UVC WebCam                                | 2         | 0.84%   |
| Realtek Integrated Webcam HD                                   | 2         | 0.84%   |
| Quanta USB2.0 HD UVC WebCam                                    | 2         | 0.84%   |
| Luxvisions Innotech Limited Integrated Camera                  | 2         | 0.84%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 0.84%   |
| Logitech Webcam C270                                           | 2         | 0.84%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 36%     |
| Synaptics                  | 6         | 24%     |
| Shenzhen Goodix Technology | 4         | 16%     |
| Upek                       | 2         | 8%      |
| LighTuning Technology      | 1         | 4%      |
| Focal-systems.Corp         | 1         | 4%      |
| Elan Microelectronics      | 1         | 4%      |
| AuthenTec                  | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 4         | 16%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 4         | 16%     |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 12%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 8%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 4%      |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4%      |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 4%      |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 4%      |
| Validity Sensors Fingerprint scanner                   | 1         | 4%      |
| Synaptics UWP WBDI Device                              | 1         | 4%      |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 4%      |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 4%      |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 4%      |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 4%      |
| Elan ELAN:Fingerprint                                  | 1         | 4%      |
| AuthenTec Fingerprint Sensor                           | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 57.14%  |
| Alcor Micro | 2         | 28.57%  |
| Lenovo      | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                               | 2         | 28.57%  |
| Alcor Micro AU9540 Smartcard Reader                                         | 2         | 28.57%  |
| Lenovo Integrated Smart Card Reader                                         | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor                              | 1         | 14.29%  |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard) | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 195       | 73.03%  |
| 1     | 63        | 23.6%   |
| 2     | 6         | 2.25%   |
| 3     | 3         | 1.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 24        | 29.63%  |
| Graphics card            | 18        | 22.22%  |
| Net/wireless             | 11        | 13.58%  |
| Multimedia controller    | 7         | 8.64%   |
| Chipcard                 | 6         | 7.41%   |
| Storage                  | 3         | 3.7%    |
| Sound                    | 3         | 3.7%    |
| Bluetooth                | 3         | 3.7%    |
| Communication controller | 2         | 2.47%   |
| Camera                   | 2         | 2.47%   |
| Storage/ide              | 1         | 1.23%   |
| Modem                    | 1         | 1.23%   |


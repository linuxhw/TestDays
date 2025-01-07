Linux in Uruguay - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Uruguay.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Uruguay/Desktop/README.md) and [notebooks](/Location/Uruguay/Notebook/README.md).

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

Total: 519

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 3340               | Notebook    | [083c2f79ec](https://linux-hardware.org/?probe=083c2f79ec) | Jan 05, 2025 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [d8587c000b](https://linux-hardware.org/?probe=d8587c000b) | Dec 14, 2024 |
| HP            | Dragonfly Pro ONE           | Notebook    | [b5d99e3a51](https://linux-hardware.org/?probe=b5d99e3a51) | Dec 14, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [e1b919328b](https://linux-hardware.org/?probe=e1b919328b) | Dec 13, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [618266a26d](https://linux-hardware.org/?probe=618266a26d) | Dec 12, 2024 |
| Dell          | 0HC3G4 A00                  | Mini pc     | [b779fddaf2](https://linux-hardware.org/?probe=b779fddaf2) | Dec 07, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [49f7b2645e](https://linux-hardware.org/?probe=49f7b2645e) | Nov 28, 2024 |
| HP            | Dragonfly Pro ONE           | Notebook    | [dbd0482a3f](https://linux-hardware.org/?probe=dbd0482a3f) | Nov 26, 2024 |
| HP            | Laptop 17z-cp300            | Notebook    | [be49e0c290](https://linux-hardware.org/?probe=be49e0c290) | Nov 23, 2024 |
| HP            | Laptop 17z-cp300            | Notebook    | [4090b82a10](https://linux-hardware.org/?probe=4090b82a10) | Nov 23, 2024 |
| HP            | Dragonfly Pro ONE           | Notebook    | [fa88478d29](https://linux-hardware.org/?probe=fa88478d29) | Nov 21, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [2ba55cd21c](https://linux-hardware.org/?probe=2ba55cd21c) | Nov 12, 2024 |
| Acer          | Aspire A515-52G             | Notebook    | [9493eace9d](https://linux-hardware.org/?probe=9493eace9d) | Nov 11, 2024 |
| MSI           | 760GM-P23                   | Desktop     | [2729dc6c3e](https://linux-hardware.org/?probe=2729dc6c3e) | Nov 08, 2024 |
| HP            | EliteBook 820 G3            | Notebook    | [abbc44e591](https://linux-hardware.org/?probe=abbc44e591) | Nov 06, 2024 |
| MSI           | B350 PC MATE                | Desktop     | [768d4c8ec6](https://linux-hardware.org/?probe=768d4c8ec6) | Nov 03, 2024 |
| GMKtec        | NucBox5                     | Notebook    | [3d6b2c6fe2](https://linux-hardware.org/?probe=3d6b2c6fe2) | Oct 23, 2024 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [84f8b8a516](https://linux-hardware.org/?probe=84f8b8a516) | Oct 19, 2024 |
| Chuwi         | CoreBook X                  | Notebook    | [1cdcd982f9](https://linux-hardware.org/?probe=1cdcd982f9) | Oct 13, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [0126b569bf](https://linux-hardware.org/?probe=0126b569bf) | Oct 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [95bc0c90e1](https://linux-hardware.org/?probe=95bc0c90e1) | Sep 23, 2024 |
| Chuwi         | Unknown                     | Notebook    | [45922bbe51](https://linux-hardware.org/?probe=45922bbe51) | Sep 19, 2024 |
| HP            | Dragonfly Pro ONE           | Notebook    | [ea5a903bc7](https://linux-hardware.org/?probe=ea5a903bc7) | Sep 13, 2024 |
| HP            | Dragonfly Pro ONE           | Notebook    | [816005b8fa](https://linux-hardware.org/?probe=816005b8fa) | Sep 10, 2024 |
| Google        | Dragonair                   | Notebook    | [0d92bf03a8](https://linux-hardware.org/?probe=0d92bf03a8) | Sep 06, 2024 |
| Pegatron      | JESSE                       | Desktop     | [1e3f996dc4](https://linux-hardware.org/?probe=1e3f996dc4) | Aug 30, 2024 |
| HP            | Dragonfly Pro ONE           | Notebook    | [24e3709aa5](https://linux-hardware.org/?probe=24e3709aa5) | Aug 29, 2024 |
| Gigabyte      | B450 GAMING X               | Desktop     | [587cdb384a](https://linux-hardware.org/?probe=587cdb384a) | Aug 25, 2024 |
| Toshiba       | Satellite L755              | Notebook    | [87f617e4d9](https://linux-hardware.org/?probe=87f617e4d9) | Aug 25, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [08d216ac0e](https://linux-hardware.org/?probe=08d216ac0e) | Aug 20, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [5a5474a9d8](https://linux-hardware.org/?probe=5a5474a9d8) | Aug 19, 2024 |
| Lenovo        | 0x36C4 SDK0J40679 WIN 32... | All in one  | [321fd04e93](https://linux-hardware.org/?probe=321fd04e93) | Aug 19, 2024 |
| HP            | Dragonfly Pro ONE           | Notebook    | [1728bcdfbe](https://linux-hardware.org/?probe=1728bcdfbe) | Aug 16, 2024 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [8c59185bfa](https://linux-hardware.org/?probe=8c59185bfa) | Aug 16, 2024 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [9153a53950](https://linux-hardware.org/?probe=9153a53950) | Aug 16, 2024 |
| JP-IK         | T140J_Sargas_2024           | Notebook    | [1e8afe45e8](https://linux-hardware.org/?probe=1e8afe45e8) | Aug 16, 2024 |
| JP-IK         | T140J_Sargas_2024           | Notebook    | [db3b8125ed](https://linux-hardware.org/?probe=db3b8125ed) | Aug 15, 2024 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [e7ab69fde0](https://linux-hardware.org/?probe=e7ab69fde0) | Aug 11, 2024 |
| HP            | Dragonfly Pro ONE           | Notebook    | [49b1242209](https://linux-hardware.org/?probe=49b1242209) | Aug 08, 2024 |
| Acer          | Aspire 5715Z                | Notebook    | [32b3360c63](https://linux-hardware.org/?probe=32b3360c63) | Aug 07, 2024 |
| Acer          | Aspire 5715Z                | Notebook    | [387c8e5fe4](https://linux-hardware.org/?probe=387c8e5fe4) | Aug 07, 2024 |
| HP            | Dragonfly Pro ONE           | Notebook    | [5ff11d8bb4](https://linux-hardware.org/?probe=5ff11d8bb4) | Aug 06, 2024 |
| HP            | EliteBook x360 1030 G2      | Convertible | [ea0f9e742e](https://linux-hardware.org/?probe=ea0f9e742e) | Aug 02, 2024 |
| Dell          | 0V8WGR A02                  | Desktop     | [3799a88355](https://linux-hardware.org/?probe=3799a88355) | Jul 31, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [1dfe36ecd9](https://linux-hardware.org/?probe=1dfe36ecd9) | Jul 26, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [0498a1fafd](https://linux-hardware.org/?probe=0498a1fafd) | Jul 18, 2024 |
| Dell          | 040DDP A01                  | Desktop     | [bf9438a172](https://linux-hardware.org/?probe=bf9438a172) | Jul 17, 2024 |
| Intel         | H81                         | Desktop     | [22d5bf41a9](https://linux-hardware.org/?probe=22d5bf41a9) | Jul 17, 2024 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [73cc6974f3](https://linux-hardware.org/?probe=73cc6974f3) | Jul 13, 2024 |
| Dell          | Inspiron 15 3520            | Notebook    | [d721bec9c8](https://linux-hardware.org/?probe=d721bec9c8) | Jul 06, 2024 |
| Lenovo        | ThinkPad T61 7660A25        | Notebook    | [d9474a6035](https://linux-hardware.org/?probe=d9474a6035) | Jul 06, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [e9ba7d256e](https://linux-hardware.org/?probe=e9ba7d256e) | Jul 05, 2024 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [02da08cbf1](https://linux-hardware.org/?probe=02da08cbf1) | Jul 02, 2024 |
| Lenovo        | ThinkPad T420 4236NUG       | Notebook    | [bd25a31252](https://linux-hardware.org/?probe=bd25a31252) | Jun 30, 2024 |
| Lenovo        | ThinkPad T61 7660A25        | Notebook    | [e8e9fb2bf7](https://linux-hardware.org/?probe=e8e9fb2bf7) | Jun 24, 2024 |
| HP            | Pavilion dv2000 (GM691LA... | Notebook    | [de1b028bbb](https://linux-hardware.org/?probe=de1b028bbb) | Jun 24, 2024 |
| Dell          | Inspiron 14 5425            | Notebook    | [3fb17595e8](https://linux-hardware.org/?probe=3fb17595e8) | Jun 16, 2024 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [fdb14858e0](https://linux-hardware.org/?probe=fdb14858e0) | Jun 05, 2024 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [36a8060749](https://linux-hardware.org/?probe=36a8060749) | Jun 03, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [58495c89d8](https://linux-hardware.org/?probe=58495c89d8) | May 25, 2024 |
| Dell          | Latitude 5531               | Notebook    | [e562f11ed3](https://linux-hardware.org/?probe=e562f11ed3) | May 20, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [97cf40bd89](https://linux-hardware.org/?probe=97cf40bd89) | May 11, 2024 |
| Google        | Phaser                      | Notebook    | [feb45bf2a2](https://linux-hardware.org/?probe=feb45bf2a2) | May 02, 2024 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | Notebook    | [859396f855](https://linux-hardware.org/?probe=859396f855) | Apr 30, 2024 |
| ASRock        | Z68 Pro3 Gen3               | Desktop     | [2e1897982e](https://linux-hardware.org/?probe=2e1897982e) | Apr 24, 2024 |
| ASRock        | Z68 Pro3 Gen3               | Desktop     | [2383a2962f](https://linux-hardware.org/?probe=2383a2962f) | Apr 24, 2024 |
| ASUSTek       | H81M-E                      | Desktop     | [7af65eace4](https://linux-hardware.org/?probe=7af65eace4) | Apr 13, 2024 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [5b213df28c](https://linux-hardware.org/?probe=5b213df28c) | Apr 12, 2024 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [4d6a9bb700](https://linux-hardware.org/?probe=4d6a9bb700) | Apr 12, 2024 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [e108ca29d2](https://linux-hardware.org/?probe=e108ca29d2) | Apr 12, 2024 |
| HP            | Presario V6000 (GH918EA#... | Notebook    | [19c9124453](https://linux-hardware.org/?probe=19c9124453) | Apr 10, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [75f2fd247a](https://linux-hardware.org/?probe=75f2fd247a) | Apr 08, 2024 |
| Dell          | 0V8WGR A02                  | Desktop     | [c8eb38c52c](https://linux-hardware.org/?probe=c8eb38c52c) | Apr 07, 2024 |
| Dell          | 0CU395                      | Desktop     | [0ba3773be8](https://linux-hardware.org/?probe=0ba3773be8) | Apr 03, 2024 |
| Dell          | 0XFWHV A00                  | Desktop     | [ea24de6920](https://linux-hardware.org/?probe=ea24de6920) | Apr 02, 2024 |
| ASRock        | B75M                        | Desktop     | [de41218e15](https://linux-hardware.org/?probe=de41218e15) | Mar 30, 2024 |
| Lenovo        | MAHOBAY                     | Desktop     | [e55de04b3d](https://linux-hardware.org/?probe=e55de04b3d) | Mar 28, 2024 |
| MSI           | Unknown                     | Notebook    | [a975d469da](https://linux-hardware.org/?probe=a975d469da) | Mar 19, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [40f761e062](https://linux-hardware.org/?probe=40f761e062) | Mar 14, 2024 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [d74df494d7](https://linux-hardware.org/?probe=d74df494d7) | Mar 12, 2024 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [0e8d4b681b](https://linux-hardware.org/?probe=0e8d4b681b) | Mar 11, 2024 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [e31b3a8c12](https://linux-hardware.org/?probe=e31b3a8c12) | Mar 08, 2024 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [225e16d7af](https://linux-hardware.org/?probe=225e16d7af) | Mar 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [30c94fd159](https://linux-hardware.org/?probe=30c94fd159) | Feb 29, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [0973b9cfb2](https://linux-hardware.org/?probe=0973b9cfb2) | Feb 29, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [cc638a70e5](https://linux-hardware.org/?probe=cc638a70e5) | Feb 21, 2024 |
| Lenovo        | G480 20156                  | Notebook    | [8ffe1342b1](https://linux-hardware.org/?probe=8ffe1342b1) | Feb 16, 2024 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [a78e0bbe6b](https://linux-hardware.org/?probe=a78e0bbe6b) | Feb 10, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [51886537be](https://linux-hardware.org/?probe=51886537be) | Feb 09, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1fcf02a6c3](https://linux-hardware.org/?probe=1fcf02a6c3) | Feb 06, 2024 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [d83dd7b361](https://linux-hardware.org/?probe=d83dd7b361) | Feb 05, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | Notebook    | [33e55cd5c5](https://linux-hardware.org/?probe=33e55cd5c5) | Feb 03, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [118dcfd484](https://linux-hardware.org/?probe=118dcfd484) | Jan 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [88f29ebedf](https://linux-hardware.org/?probe=88f29ebedf) | Jan 24, 2024 |
| Gigabyte      | B550M K                     | Desktop     | [39f7c51de0](https://linux-hardware.org/?probe=39f7c51de0) | Jan 05, 2024 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [da8a8d5994](https://linux-hardware.org/?probe=da8a8d5994) | Dec 28, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [418992da4d](https://linux-hardware.org/?probe=418992da4d) | Dec 27, 2023 |
| Dell          | Inspiron 1564               | Notebook    | [a1945990cc](https://linux-hardware.org/?probe=a1945990cc) | Dec 24, 2023 |
| Dell          | Inspiron 1564               | Notebook    | [e02428db4a](https://linux-hardware.org/?probe=e02428db4a) | Dec 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [0f2cad4391](https://linux-hardware.org/?probe=0f2cad4391) | Dec 22, 2023 |
| Standard      | SF20BA2                     | Notebook    | [431580b18d](https://linux-hardware.org/?probe=431580b18d) | Dec 19, 2023 |
| Gigabyte      | H310M A-CF                  | Desktop     | [cdf7a1ffd4](https://linux-hardware.org/?probe=cdf7a1ffd4) | Dec 15, 2023 |
| ASRock        | 760GM-HDV                   | Desktop     | [c1403f5d52](https://linux-hardware.org/?probe=c1403f5d52) | Dec 15, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [81baeeb4c6](https://linux-hardware.org/?probe=81baeeb4c6) | Dec 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [58e1501577](https://linux-hardware.org/?probe=58e1501577) | Dec 06, 2023 |
| ASUSTek       | UX305CA                     | Notebook    | [6bac81f943](https://linux-hardware.org/?probe=6bac81f943) | Dec 06, 2023 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [21e6cb8e9b](https://linux-hardware.org/?probe=21e6cb8e9b) | Dec 05, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [248ac55d99](https://linux-hardware.org/?probe=248ac55d99) | Nov 29, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [858c641fcf](https://linux-hardware.org/?probe=858c641fcf) | Nov 26, 2023 |
| Dell          | 0V8WGR A01                  | Desktop     | [b44e627796](https://linux-hardware.org/?probe=b44e627796) | Nov 26, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [6cdf6e663e](https://linux-hardware.org/?probe=6cdf6e663e) | Nov 26, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [2188d0c4b8](https://linux-hardware.org/?probe=2188d0c4b8) | Nov 25, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [b7294ed55c](https://linux-hardware.org/?probe=b7294ed55c) | Nov 20, 2023 |
| HP            | 1495                        | Desktop     | [9f7eca2710](https://linux-hardware.org/?probe=9f7eca2710) | Nov 17, 2023 |
| HP            | 1495                        | Desktop     | [9a299e543d](https://linux-hardware.org/?probe=9a299e543d) | Nov 16, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [eb4b6a5c65](https://linux-hardware.org/?probe=eb4b6a5c65) | Nov 15, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [339062b95b](https://linux-hardware.org/?probe=339062b95b) | Nov 15, 2023 |
| Lenovo        | ThinkPad T420 42361H7       | Notebook    | [0f1bd55fbf](https://linux-hardware.org/?probe=0f1bd55fbf) | Nov 09, 2023 |
| Razer         | Blade                       | Notebook    | [e9ad529ed4](https://linux-hardware.org/?probe=e9ad529ed4) | Nov 01, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [8ef0f47332](https://linux-hardware.org/?probe=8ef0f47332) | Oct 20, 2023 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [f4eec82fb9](https://linux-hardware.org/?probe=f4eec82fb9) | Oct 09, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [a775bc4b08](https://linux-hardware.org/?probe=a775bc4b08) | Oct 05, 2023 |
| Razer         | Blade                       | Notebook    | [b3b2eb7db8](https://linux-hardware.org/?probe=b3b2eb7db8) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4398558915](https://linux-hardware.org/?probe=4398558915) | Sep 19, 2023 |
| ASUSTek       | X542UQ                      | Notebook    | [6793d8c052](https://linux-hardware.org/?probe=6793d8c052) | Sep 16, 2023 |
| MSI           | B85M-E45                    | Desktop     | [d454b67226](https://linux-hardware.org/?probe=d454b67226) | Sep 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | Notebook    | [a51361ebb2](https://linux-hardware.org/?probe=a51361ebb2) | Sep 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | Notebook    | [00cbde2fb9](https://linux-hardware.org/?probe=00cbde2fb9) | Sep 12, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [213b7c59de](https://linux-hardware.org/?probe=213b7c59de) | Sep 02, 2023 |
| GPU Compan... | GWTN156-9                   | Notebook    | [4c8ea16ab2](https://linux-hardware.org/?probe=4c8ea16ab2) | Aug 30, 2023 |
| Dell          | 0V8WGR A01                  | Desktop     | [9e5ed52b45](https://linux-hardware.org/?probe=9e5ed52b45) | Aug 29, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [62b31c86bb](https://linux-hardware.org/?probe=62b31c86bb) | Aug 22, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [a435538cb2](https://linux-hardware.org/?probe=a435538cb2) | Aug 20, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [0dc75dae26](https://linux-hardware.org/?probe=0dc75dae26) | Aug 18, 2023 |
| HP            | 14                          | Notebook    | [8692626574](https://linux-hardware.org/?probe=8692626574) | Aug 09, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX DDR4    | Desktop     | [025bd1edae](https://linux-hardware.org/?probe=025bd1edae) | Aug 04, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [46ca3ef1f4](https://linux-hardware.org/?probe=46ca3ef1f4) | Aug 01, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [bbe4e49261](https://linux-hardware.org/?probe=bbe4e49261) | Aug 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a4d7919584](https://linux-hardware.org/?probe=a4d7919584) | Jul 29, 2023 |
| HP            | 1497                        | Desktop     | [370799b635](https://linux-hardware.org/?probe=370799b635) | Jul 26, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [01cfac81b4](https://linux-hardware.org/?probe=01cfac81b4) | Jul 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [d16a211675](https://linux-hardware.org/?probe=d16a211675) | Jul 21, 2023 |
| Dell          | Latitude E5420              | Notebook    | [be15c1e3d1](https://linux-hardware.org/?probe=be15c1e3d1) | Jul 20, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [cacf2d88c9](https://linux-hardware.org/?probe=cacf2d88c9) | Jul 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6776e11ac9](https://linux-hardware.org/?probe=6776e11ac9) | Jul 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [0fc498ccfb](https://linux-hardware.org/?probe=0fc498ccfb) | Jul 06, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [d0258b4ca5](https://linux-hardware.org/?probe=d0258b4ca5) | Jul 06, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [7d1d71b0fe](https://linux-hardware.org/?probe=7d1d71b0fe) | Jul 06, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | Notebook    | [ad76ecf5a9](https://linux-hardware.org/?probe=ad76ecf5a9) | Jul 01, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | Notebook    | [b8bab5a2e6](https://linux-hardware.org/?probe=b8bab5a2e6) | Jul 01, 2023 |
| Acer          | One S1002                   | Notebook    | [f7b8d25603](https://linux-hardware.org/?probe=f7b8d25603) | Jun 21, 2023 |
| Intel         | H61                         | Desktop     | [ac2b137243](https://linux-hardware.org/?probe=ac2b137243) | Jun 15, 2023 |
| Dell          | 0V8WGR A02                  | Desktop     | [448fd1711d](https://linux-hardware.org/?probe=448fd1711d) | Jun 12, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [3742e80123](https://linux-hardware.org/?probe=3742e80123) | Jun 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [3cfa2bccb7](https://linux-hardware.org/?probe=3cfa2bccb7) | Jun 08, 2023 |
| HP            | Pavilion g6                 | Notebook    | [12b1174ce8](https://linux-hardware.org/?probe=12b1174ce8) | Jun 08, 2023 |
| HP            | 0A60h                       | Desktop     | [f0498c1a54](https://linux-hardware.org/?probe=f0498c1a54) | Jun 07, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [624a84a2fc](https://linux-hardware.org/?probe=624a84a2fc) | Jun 06, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [75c4e47bea](https://linux-hardware.org/?probe=75c4e47bea) | Jun 01, 2023 |
| Toshiba       | Satellite C645D             | Notebook    | [085994472d](https://linux-hardware.org/?probe=085994472d) | May 28, 2023 |
| HP            | Stream Notebook             | Notebook    | [74d40533fc](https://linux-hardware.org/?probe=74d40533fc) | May 24, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6855a79270](https://linux-hardware.org/?probe=6855a79270) | May 23, 2023 |
| Acer          | Aspire 4315                 | Notebook    | [8a25a16dfa](https://linux-hardware.org/?probe=8a25a16dfa) | May 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [7af74c5864](https://linux-hardware.org/?probe=7af74c5864) | May 18, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | Notebook    | [0fd753db6d](https://linux-hardware.org/?probe=0fd753db6d) | May 16, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [970443eea3](https://linux-hardware.org/?probe=970443eea3) | May 14, 2023 |
| HP            | Notebook                    | Notebook    | [c14e7a41cf](https://linux-hardware.org/?probe=c14e7a41cf) | May 13, 2023 |
| HP            | Notebook                    | Notebook    | [726fa4fcd1](https://linux-hardware.org/?probe=726fa4fcd1) | May 13, 2023 |
| Dell          | Latitude 5530               | Notebook    | [ade218e4fa](https://linux-hardware.org/?probe=ade218e4fa) | May 11, 2023 |
| ASRock        | N68-S3 UCC                  | Desktop     | [8a1fbe8e3c](https://linux-hardware.org/?probe=8a1fbe8e3c) | May 09, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [97cc4e0a84](https://linux-hardware.org/?probe=97cc4e0a84) | May 01, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [cf6a478eb1](https://linux-hardware.org/?probe=cf6a478eb1) | May 01, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [8f1db96b6f](https://linux-hardware.org/?probe=8f1db96b6f) | Apr 29, 2023 |
| HP            | 240 G4                      | Notebook    | [997e6e6a0b](https://linux-hardware.org/?probe=997e6e6a0b) | Apr 24, 2023 |
| HP            | 240 G4                      | Notebook    | [887b406c56](https://linux-hardware.org/?probe=887b406c56) | Apr 22, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [e0b2a066ee](https://linux-hardware.org/?probe=e0b2a066ee) | Apr 15, 2023 |
| Standard      | SF20BA2                     | Notebook    | [17763324b6](https://linux-hardware.org/?probe=17763324b6) | Apr 08, 2023 |
| Intel         | EF20                        | Notebook    | [120257faca](https://linux-hardware.org/?probe=120257faca) | Apr 04, 2023 |
| Lenovo        | 0x36C4 SDK0J40679 WIN 32... | All in one  | [5d5eb8d675](https://linux-hardware.org/?probe=5d5eb8d675) | Apr 01, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [9af85c78cb](https://linux-hardware.org/?probe=9af85c78cb) | Mar 28, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [1531761af6](https://linux-hardware.org/?probe=1531761af6) | Mar 26, 2023 |
| Acer          | Aspire 4315                 | Notebook    | [0bf18c8c90](https://linux-hardware.org/?probe=0bf18c8c90) | Mar 26, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f0f20a06ef](https://linux-hardware.org/?probe=f0f20a06ef) | Mar 19, 2023 |
| Toshiba       | Satellite C75D-B            | Notebook    | [1ff56ed31f](https://linux-hardware.org/?probe=1ff56ed31f) | Mar 19, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [2a1291ac22](https://linux-hardware.org/?probe=2a1291ac22) | Mar 18, 2023 |
| Dell          | Latitude 7310               | Notebook    | [6b5de5fe3c](https://linux-hardware.org/?probe=6b5de5fe3c) | Mar 17, 2023 |
| Standard      | SF20BA                      | Notebook    | [e85dc022b5](https://linux-hardware.org/?probe=e85dc022b5) | Mar 15, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [b94932937e](https://linux-hardware.org/?probe=b94932937e) | Mar 14, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [7d35815562](https://linux-hardware.org/?probe=7d35815562) | Mar 13, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [41bf4fb877](https://linux-hardware.org/?probe=41bf4fb877) | Mar 10, 2023 |
| AZW           | MINI S                      | Desktop     | [cb0b08973d](https://linux-hardware.org/?probe=cb0b08973d) | Mar 06, 2023 |
| Dell          | Latitude 3150               | Notebook    | [f1554a5df0](https://linux-hardware.org/?probe=f1554a5df0) | Mar 05, 2023 |
| Acer          | Swift SF314-54              | Notebook    | [62defb89e3](https://linux-hardware.org/?probe=62defb89e3) | Mar 02, 2023 |
| ECS           | SF20PA2                     | Notebook    | [f0ad83686f](https://linux-hardware.org/?probe=f0ad83686f) | Feb 21, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [c5256638eb](https://linux-hardware.org/?probe=c5256638eb) | Feb 20, 2023 |
| Lenovo        | ThinkPad P50 20EQS14H00     | Notebook    | [de5c7ac3f6](https://linux-hardware.org/?probe=de5c7ac3f6) | Feb 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [e8183bc042](https://linux-hardware.org/?probe=e8183bc042) | Feb 16, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [163991dfae](https://linux-hardware.org/?probe=163991dfae) | Feb 03, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [a08e60bb31](https://linux-hardware.org/?probe=a08e60bb31) | Feb 03, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [d6829621d7](https://linux-hardware.org/?probe=d6829621d7) | Feb 03, 2023 |
| Lenovo        | 14w 81MQ00AVCL              | Notebook    | [bd59f68ce8](https://linux-hardware.org/?probe=bd59f68ce8) | Feb 03, 2023 |
| ECS           | SF20PA2                     | Notebook    | [30df19ca2e](https://linux-hardware.org/?probe=30df19ca2e) | Feb 02, 2023 |
| Gateway       | LT41P                       | Notebook    | [1684d937e7](https://linux-hardware.org/?probe=1684d937e7) | Feb 02, 2023 |
| HP            | 3115-AEC13432GR1            | Notebook    | [98eb70341a](https://linux-hardware.org/?probe=98eb70341a) | Jan 30, 2023 |
| HP            | 339A                        | Desktop     | [5d86fd4411](https://linux-hardware.org/?probe=5d86fd4411) | Jan 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [4bda80131d](https://linux-hardware.org/?probe=4bda80131d) | Jan 15, 2023 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [4cf36f7404](https://linux-hardware.org/?probe=4cf36f7404) | Jan 13, 2023 |
| Valve         | Jupiter                     | Notebook    | [dc137d0d08](https://linux-hardware.org/?probe=dc137d0d08) | Jan 09, 2023 |
| Toshiba       | Satellite C75D-B            | Notebook    | [d5380976a2](https://linux-hardware.org/?probe=d5380976a2) | Jan 03, 2023 |
| Toshiba       | Satellite C75D-B            | Notebook    | [04282775ba](https://linux-hardware.org/?probe=04282775ba) | Dec 24, 2022 |
| MSI           | 2A9C                        | Desktop     | [57c14b82bd](https://linux-hardware.org/?probe=57c14b82bd) | Nov 23, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [733140c078](https://linux-hardware.org/?probe=733140c078) | Nov 20, 2022 |
| ECS           | SF20PA2                     | Notebook    | [2e0892ec48](https://linux-hardware.org/?probe=2e0892ec48) | Nov 18, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [c27978fdc4](https://linux-hardware.org/?probe=c27978fdc4) | Nov 18, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [e974c2ceff](https://linux-hardware.org/?probe=e974c2ceff) | Nov 12, 2022 |
| Alienware     | 14                          | Notebook    | [0c11295ebe](https://linux-hardware.org/?probe=0c11295ebe) | Nov 03, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [e2f30e0f1e](https://linux-hardware.org/?probe=e2f30e0f1e) | Oct 26, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [afe54b52c9](https://linux-hardware.org/?probe=afe54b52c9) | Oct 21, 2022 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [cb86d1ba99](https://linux-hardware.org/?probe=cb86d1ba99) | Oct 18, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [2426012acb](https://linux-hardware.org/?probe=2426012acb) | Oct 18, 2022 |
| Dell          | 0XFWHV A00                  | Desktop     | [4a5716d169](https://linux-hardware.org/?probe=4a5716d169) | Oct 16, 2022 |
| MSI           | 2A9C                        | Desktop     | [74482fb396](https://linux-hardware.org/?probe=74482fb396) | Oct 16, 2022 |
| HP            | Laptop 17-ak0xx             | Notebook    | [67fbbc4074](https://linux-hardware.org/?probe=67fbbc4074) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d006fa9a19](https://linux-hardware.org/?probe=d006fa9a19) | Oct 11, 2022 |
| MSI           | 2A9C                        | Desktop     | [1c1d20a1ac](https://linux-hardware.org/?probe=1c1d20a1ac) | Oct 09, 2022 |
| MSI           | 2A9C                        | Desktop     | [98ff35e2a7](https://linux-hardware.org/?probe=98ff35e2a7) | Oct 09, 2022 |
| Acer          | Aspire ES1-572              | Notebook    | [1bd18c9a15](https://linux-hardware.org/?probe=1bd18c9a15) | Oct 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [adde8098e4](https://linux-hardware.org/?probe=adde8098e4) | Oct 04, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Corei... | Desktop     | [a40d59533c](https://linux-hardware.org/?probe=a40d59533c) | Sep 29, 2022 |
| Biostar       | H410MH S2                   | Desktop     | [b03e32f37d](https://linux-hardware.org/?probe=b03e32f37d) | Sep 29, 2022 |
| Biostar       | H410MH S2                   | Desktop     | [fbba79fc43](https://linux-hardware.org/?probe=fbba79fc43) | Sep 28, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [5e91cc6f07](https://linux-hardware.org/?probe=5e91cc6f07) | Sep 21, 2022 |
| Toshiba       | Satellite C855              | Notebook    | [bd34f35e50](https://linux-hardware.org/?probe=bd34f35e50) | Sep 15, 2022 |
| HP            | 8265                        | Desktop     | [2b74e032bd](https://linux-hardware.org/?probe=2b74e032bd) | Sep 06, 2022 |
| HP            | 8265                        | Desktop     | [f7f460fb43](https://linux-hardware.org/?probe=f7f460fb43) | Sep 05, 2022 |
| Dell          | Latitude 3150               | Notebook    | [6bc88c696c](https://linux-hardware.org/?probe=6bc88c696c) | Sep 04, 2022 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [8ffe312747](https://linux-hardware.org/?probe=8ffe312747) | Sep 04, 2022 |
| ASRock        | N68-S                       | Desktop     | [df5d34428a](https://linux-hardware.org/?probe=df5d34428a) | Sep 01, 2022 |
| ASRock        | N68-S                       | Desktop     | [6aabf89438](https://linux-hardware.org/?probe=6aabf89438) | Aug 30, 2022 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [422af9d6b5](https://linux-hardware.org/?probe=422af9d6b5) | Aug 29, 2022 |
| ASRock        | N68-S                       | Desktop     | [4fff0a6104](https://linux-hardware.org/?probe=4fff0a6104) | Aug 29, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [1e79d17c85](https://linux-hardware.org/?probe=1e79d17c85) | Aug 23, 2022 |
| ECS           | SF20PA2                     | Notebook    | [67dd8af18f](https://linux-hardware.org/?probe=67dd8af18f) | Aug 23, 2022 |
| Lenovo        | IdeaPad 500S-14ISK 80Q3     | Notebook    | [fdbec5aab2](https://linux-hardware.org/?probe=fdbec5aab2) | Aug 22, 2022 |
| HP            | 3048h                       | Desktop     | [34e0bbc168](https://linux-hardware.org/?probe=34e0bbc168) | Aug 20, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [2b97e09efa](https://linux-hardware.org/?probe=2b97e09efa) | Aug 17, 2022 |
| Biostar       | B550MH                      | Desktop     | [228a44e3f0](https://linux-hardware.org/?probe=228a44e3f0) | Aug 06, 2022 |
| ASRock        | B75M                        | Desktop     | [78fbdcd0f7](https://linux-hardware.org/?probe=78fbdcd0f7) | Aug 05, 2022 |
| Gateway       | NV55C                       | Notebook    | [cc3c8d23e4](https://linux-hardware.org/?probe=cc3c8d23e4) | Aug 03, 2022 |
| Dell          | Latitude 3150               | Notebook    | [aecf1fe543](https://linux-hardware.org/?probe=aecf1fe543) | Aug 01, 2022 |
| MACHINIST     | X79 (INTEL Xeon E5/Corei... | Desktop     | [e83fe522d7](https://linux-hardware.org/?probe=e83fe522d7) | Jul 31, 2022 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [a3c2fdccfc](https://linux-hardware.org/?probe=a3c2fdccfc) | Jul 27, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [4eb7e0d085](https://linux-hardware.org/?probe=4eb7e0d085) | Jul 22, 2022 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [04affeedf7](https://linux-hardware.org/?probe=04affeedf7) | Jul 18, 2022 |
| GPU Compan... | GWTN156-9                   | Notebook    | [df5c4b480d](https://linux-hardware.org/?probe=df5c4b480d) | Jul 15, 2022 |
| HP            | 1632                        | Desktop     | [d2582aff1d](https://linux-hardware.org/?probe=d2582aff1d) | Jul 12, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [0d26f198ff](https://linux-hardware.org/?probe=0d26f198ff) | Jul 06, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [5fa355f7ec](https://linux-hardware.org/?probe=5fa355f7ec) | Jun 26, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [47420af7dc](https://linux-hardware.org/?probe=47420af7dc) | Jun 23, 2022 |
| iClever       | IC-T01                      | Notebook    | [f82c34c612](https://linux-hardware.org/?probe=f82c34c612) | Jun 17, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [6abbac5ca2](https://linux-hardware.org/?probe=6abbac5ca2) | Jun 15, 2022 |
| HP            | Pavilion g4                 | Notebook    | [193875edcc](https://linux-hardware.org/?probe=193875edcc) | Jun 15, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [06bccc3696](https://linux-hardware.org/?probe=06bccc3696) | Jun 14, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [34e884bb50](https://linux-hardware.org/?probe=34e884bb50) | Jun 08, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [482ed9f535](https://linux-hardware.org/?probe=482ed9f535) | May 29, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [39f85b46d7](https://linux-hardware.org/?probe=39f85b46d7) | May 23, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [fc1233f258](https://linux-hardware.org/?probe=fc1233f258) | May 22, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [478550abf1](https://linux-hardware.org/?probe=478550abf1) | May 21, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [95ac26b654](https://linux-hardware.org/?probe=95ac26b654) | May 19, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [a31c36956a](https://linux-hardware.org/?probe=a31c36956a) | May 13, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [cc3411e0b4](https://linux-hardware.org/?probe=cc3411e0b4) | May 10, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [fa6da4906f](https://linux-hardware.org/?probe=fa6da4906f) | May 07, 2022 |
| Toshiba       | Satellite C645D             | Notebook    | [53153cb65d](https://linux-hardware.org/?probe=53153cb65d) | May 04, 2022 |
| Acer          | Aspire ES1-572              | Notebook    | [25f9b83c30](https://linux-hardware.org/?probe=25f9b83c30) | Apr 28, 2022 |
| Lenovo        | B50-45 20388                | Notebook    | [7ad45f257f](https://linux-hardware.org/?probe=7ad45f257f) | Apr 20, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [d2e2811388](https://linux-hardware.org/?probe=d2e2811388) | Apr 20, 2022 |
| Dell          | Inspiron 5585               | Notebook    | [2c6e96d91f](https://linux-hardware.org/?probe=2c6e96d91f) | Apr 18, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [73be944f6c](https://linux-hardware.org/?probe=73be944f6c) | Apr 14, 2022 |
| Dell          | Precision 7550              | Notebook    | [4619da9502](https://linux-hardware.org/?probe=4619da9502) | Apr 14, 2022 |
| Lenovo        | G405 20239                  | Notebook    | [ab55cb1e13](https://linux-hardware.org/?probe=ab55cb1e13) | Apr 13, 2022 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [7d203f8bc0](https://linux-hardware.org/?probe=7d203f8bc0) | Apr 02, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [d895af2b46](https://linux-hardware.org/?probe=d895af2b46) | Mar 29, 2022 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [9bf7ed495b](https://linux-hardware.org/?probe=9bf7ed495b) | Mar 28, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | Notebook    | [d9afd858b4](https://linux-hardware.org/?probe=d9afd858b4) | Mar 23, 2022 |
| Foxconn       | G31MX Series                | Desktop     | [911987151a](https://linux-hardware.org/?probe=911987151a) | Mar 23, 2022 |
| Foxconn       | G31MX Series                | Desktop     | [7d9cc6ac07](https://linux-hardware.org/?probe=7d9cc6ac07) | Mar 22, 2022 |
| HP            | ZBook 14u G4                | Notebook    | [cc637b12de](https://linux-hardware.org/?probe=cc637b12de) | Mar 10, 2022 |
| HP            | Pavilion dv5                | Notebook    | [81371d4535](https://linux-hardware.org/?probe=81371d4535) | Mar 04, 2022 |
| GPU Compan... | GWTN156-4                   | Notebook    | [89e7b9fa39](https://linux-hardware.org/?probe=89e7b9fa39) | Mar 02, 2022 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [9699b8889c](https://linux-hardware.org/?probe=9699b8889c) | Feb 27, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [37231251ed](https://linux-hardware.org/?probe=37231251ed) | Feb 21, 2022 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [52ca8c0d7c](https://linux-hardware.org/?probe=52ca8c0d7c) | Feb 13, 2022 |
| ECS           | SF20PA2                     | Notebook    | [3bddc7e08a](https://linux-hardware.org/?probe=3bddc7e08a) | Feb 11, 2022 |
| HP            | 3047h                       | Desktop     | [ee6260c5f4](https://linux-hardware.org/?probe=ee6260c5f4) | Feb 10, 2022 |
| MSI           | GS63VR 6RF                  | Notebook    | [4873365af6](https://linux-hardware.org/?probe=4873365af6) | Jan 30, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [0fe418c7b1](https://linux-hardware.org/?probe=0fe418c7b1) | Jan 07, 2022 |
| HP            | 0AA8h                       | Desktop     | [9abf55a71f](https://linux-hardware.org/?probe=9abf55a71f) | Jan 05, 2022 |
| HP            | 0AA8h                       | Desktop     | [44c9ba4231](https://linux-hardware.org/?probe=44c9ba4231) | Jan 03, 2022 |
| Biostar       | Z490A-SILVER                | Desktop     | [b5e7622be0](https://linux-hardware.org/?probe=b5e7622be0) | Jan 02, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [90f509fc24](https://linux-hardware.org/?probe=90f509fc24) | Dec 09, 2021 |
| Sony          | SVF14211CLB                 | Notebook    | [d25b1846ff](https://linux-hardware.org/?probe=d25b1846ff) | Dec 07, 2021 |
| Sony          | SVF14211CLB                 | Notebook    | [41bfe6e292](https://linux-hardware.org/?probe=41bfe6e292) | Dec 06, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [5fb4f1b6a6](https://linux-hardware.org/?probe=5fb4f1b6a6) | Nov 29, 2021 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [a664218f29](https://linux-hardware.org/?probe=a664218f29) | Nov 28, 2021 |
| Acer          | Aspire 5733Z                | Notebook    | [324f0d898e](https://linux-hardware.org/?probe=324f0d898e) | Nov 16, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [44b341f68d](https://linux-hardware.org/?probe=44b341f68d) | Nov 10, 2021 |
| Acer          | Swift SF314-54              | Notebook    | [b506625dc2](https://linux-hardware.org/?probe=b506625dc2) | Nov 05, 2021 |
| Acer          | Swift SF314-54              | Notebook    | [4e606c817f](https://linux-hardware.org/?probe=4e606c817f) | Nov 04, 2021 |
| ASRock        | N68-S                       | Desktop     | [eac798f714](https://linux-hardware.org/?probe=eac798f714) | Nov 01, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [174875a3d4](https://linux-hardware.org/?probe=174875a3d4) | Oct 25, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [357ea9ab5d](https://linux-hardware.org/?probe=357ea9ab5d) | Oct 22, 2021 |
| Samsung       | N102SP/N100SP/N101SP        | Notebook    | [c04d448530](https://linux-hardware.org/?probe=c04d448530) | Oct 21, 2021 |
| ASUSTek       | Q324UAK                     | Convertible | [a8334894c5](https://linux-hardware.org/?probe=a8334894c5) | Oct 19, 2021 |
| Lenovo        | B51-30 80LK                 | Notebook    | [dea10156c6](https://linux-hardware.org/?probe=dea10156c6) | Sep 20, 2021 |
| Haitech       | H7141A                      | Notebook    | [496c0eb316](https://linux-hardware.org/?probe=496c0eb316) | Sep 18, 2021 |
| ECS           | SF20PA2                     | Notebook    | [6d17cf08ad](https://linux-hardware.org/?probe=6d17cf08ad) | Sep 12, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [fea193c839](https://linux-hardware.org/?probe=fea193c839) | Sep 10, 2021 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [dbeb8785e6](https://linux-hardware.org/?probe=dbeb8785e6) | Sep 01, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [c2e1837665](https://linux-hardware.org/?probe=c2e1837665) | Aug 24, 2021 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [fef0710fbd](https://linux-hardware.org/?probe=fef0710fbd) | Aug 24, 2021 |
| Panasonic     | CF-31JEGAX1M                | Notebook    | [c5acecef3a](https://linux-hardware.org/?probe=c5acecef3a) | Aug 22, 2021 |
| Lenovo        | ThinkPad L490 20Q6S0NF00    | Notebook    | [a8f222614b](https://linux-hardware.org/?probe=a8f222614b) | Aug 11, 2021 |
| Lenovo        | ThinkPad T450 20BUS0G91F    | Notebook    | [8db659cf12](https://linux-hardware.org/?probe=8db659cf12) | Aug 09, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20CDS02... | Notebook    | [4781e962e7](https://linux-hardware.org/?probe=4781e962e7) | Aug 09, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [393c8e4faa](https://linux-hardware.org/?probe=393c8e4faa) | Aug 05, 2021 |
| HP            | Pavilion 15                 | Notebook    | [ec0019224a](https://linux-hardware.org/?probe=ec0019224a) | Jul 28, 2021 |
| ECS           | SF20PA2                     | Notebook    | [2016dfe42c](https://linux-hardware.org/?probe=2016dfe42c) | Jul 26, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [c84d445008](https://linux-hardware.org/?probe=c84d445008) | Jul 18, 2021 |
| Acer          | Aspire E5-521               | Notebook    | [d4629ecbed](https://linux-hardware.org/?probe=d4629ecbed) | Jul 18, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [b6c401b55e](https://linux-hardware.org/?probe=b6c401b55e) | Jul 15, 2021 |
| Lenovo        | ThinkPad E15 20RES31K00     | Notebook    | [6d359d339e](https://linux-hardware.org/?probe=6d359d339e) | Jul 02, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [27582e9e17](https://linux-hardware.org/?probe=27582e9e17) | Jun 21, 2021 |
| Acer          | TravelMate 5730             | Notebook    | [4a21735ce1](https://linux-hardware.org/?probe=4a21735ce1) | Jun 17, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [38ee95b416](https://linux-hardware.org/?probe=38ee95b416) | Jun 02, 2021 |
| Acer          | Acadia V1.45                | Notebook    | [9357025bc9](https://linux-hardware.org/?probe=9357025bc9) | Jun 01, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [ab4b1b7a15](https://linux-hardware.org/?probe=ab4b1b7a15) | May 31, 2021 |
| HP            | ENVY TS 15                  | Notebook    | [8369c42ce2](https://linux-hardware.org/?probe=8369c42ce2) | May 31, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [d9065ac8d1](https://linux-hardware.org/?probe=d9065ac8d1) | May 30, 2021 |
| Positivo      | Serie AT300                 | Notebook    | [38a0173a4a](https://linux-hardware.org/?probe=38a0173a4a) | May 28, 2021 |
| HP            | Pavilion 17                 | Notebook    | [f12450cc62](https://linux-hardware.org/?probe=f12450cc62) | May 28, 2021 |
| Lenovo        | ThinkPad T590 20N5S2GP05    | Notebook    | [2444839350](https://linux-hardware.org/?probe=2444839350) | May 25, 2021 |
| Dell          | Latitude E5470              | Notebook    | [212d434e24](https://linux-hardware.org/?probe=212d434e24) | May 25, 2021 |
| Positivo      | Serie AT300                 | Notebook    | [a021ecf0dd](https://linux-hardware.org/?probe=a021ecf0dd) | May 24, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [24040eecb6](https://linux-hardware.org/?probe=24040eecb6) | May 23, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [cb57bbefd0](https://linux-hardware.org/?probe=cb57bbefd0) | May 22, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [297e5b458a](https://linux-hardware.org/?probe=297e5b458a) | May 21, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [883f67612b](https://linux-hardware.org/?probe=883f67612b) | May 19, 2021 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [0ed78505e8](https://linux-hardware.org/?probe=0ed78505e8) | May 19, 2021 |
| Standard      | SF20BA2                     | Notebook    | [e0fdbc36a2](https://linux-hardware.org/?probe=e0fdbc36a2) | May 16, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [41e6c088d2](https://linux-hardware.org/?probe=41e6c088d2) | May 16, 2021 |
| Acer          | Acadia V1.45                | Notebook    | [321e5159ac](https://linux-hardware.org/?probe=321e5159ac) | May 15, 2021 |
| ECS           | SF20PA2                     | Notebook    | [f3cc58b0e4](https://linux-hardware.org/?probe=f3cc58b0e4) | May 13, 2021 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [ada1c4a259](https://linux-hardware.org/?probe=ada1c4a259) | May 12, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [6f67fbb9d4](https://linux-hardware.org/?probe=6f67fbb9d4) | May 08, 2021 |
| ECS           | SF20PA2                     | Notebook    | [cfbd36f40b](https://linux-hardware.org/?probe=cfbd36f40b) | May 07, 2021 |
| Acer          | Aspire E5-521               | Notebook    | [d1c6c7309a](https://linux-hardware.org/?probe=d1c6c7309a) | May 03, 2021 |
| ASUSTek       | N46VJ                       | Notebook    | [0d6e007969](https://linux-hardware.org/?probe=0d6e007969) | Apr 28, 2021 |
| Standard      | SF20BA2                     | Notebook    | [d51e9f653f](https://linux-hardware.org/?probe=d51e9f653f) | Apr 26, 2021 |
| ASRock        | N68-VS3 FX                  | Desktop     | [bcee870f79](https://linux-hardware.org/?probe=bcee870f79) | Apr 24, 2021 |
| ASRock        | N68-VS3 FX                  | Desktop     | [b92a431094](https://linux-hardware.org/?probe=b92a431094) | Apr 24, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [7d28bb0ba2](https://linux-hardware.org/?probe=7d28bb0ba2) | Apr 23, 2021 |
| Standard      | SF20BA2                     | Notebook    | [a568b21782](https://linux-hardware.org/?probe=a568b21782) | Apr 23, 2021 |
| Standard      | SF20BA2                     | Notebook    | [e454415213](https://linux-hardware.org/?probe=e454415213) | Apr 23, 2021 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [5042e6d421](https://linux-hardware.org/?probe=5042e6d421) | Apr 20, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [44e6cc36ce](https://linux-hardware.org/?probe=44e6cc36ce) | Apr 20, 2021 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [9065c52996](https://linux-hardware.org/?probe=9065c52996) | Apr 17, 2021 |
| Dell          | Inspiron 5565               | Notebook    | [8f75eda1de](https://linux-hardware.org/?probe=8f75eda1de) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [4e23f3b6b5](https://linux-hardware.org/?probe=4e23f3b6b5) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [18ee0d2d64](https://linux-hardware.org/?probe=18ee0d2d64) | Apr 16, 2021 |
| HP            | 240 G7                      | Notebook    | [721c4c3dbd](https://linux-hardware.org/?probe=721c4c3dbd) | Apr 14, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2296b37506](https://linux-hardware.org/?probe=2296b37506) | Apr 12, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [9a7aa83895](https://linux-hardware.org/?probe=9a7aa83895) | Apr 07, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [30729baf7a](https://linux-hardware.org/?probe=30729baf7a) | Apr 07, 2021 |
| ASUSTek       | P8H77-V                     | Desktop     | [9b0d9c1623](https://linux-hardware.org/?probe=9b0d9c1623) | Apr 05, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [118abf533e](https://linux-hardware.org/?probe=118abf533e) | Mar 28, 2021 |
| Supermicro    | P4DMS                       | Desktop     | [34867ad122](https://linux-hardware.org/?probe=34867ad122) | Mar 22, 2021 |
| Panasonic     | CF-31JEGAX1M                | Notebook    | [4636e611d8](https://linux-hardware.org/?probe=4636e611d8) | Mar 14, 2021 |
| Supermicro    | P4DMS                       | Desktop     | [9de21bc6ec](https://linux-hardware.org/?probe=9de21bc6ec) | Mar 14, 2021 |
| MSI           | GL65 Leopard 10SCXR         | Notebook    | [8497db47ab](https://linux-hardware.org/?probe=8497db47ab) | Mar 09, 2021 |
| HP            | Laptop 14-df0xxx            | Notebook    | [c1d21b6940](https://linux-hardware.org/?probe=c1d21b6940) | Mar 01, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [901fd74eaa](https://linux-hardware.org/?probe=901fd74eaa) | Feb 20, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [7f1fc20897](https://linux-hardware.org/?probe=7f1fc20897) | Feb 19, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [9527a6802e](https://linux-hardware.org/?probe=9527a6802e) | Feb 19, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [f51dac04a1](https://linux-hardware.org/?probe=f51dac04a1) | Feb 17, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [bea8cc11d5](https://linux-hardware.org/?probe=bea8cc11d5) | Feb 17, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [9473725930](https://linux-hardware.org/?probe=9473725930) | Feb 15, 2021 |
| Unknown       | Unknown                     | Phone       | [d561348222](https://linux-hardware.org/?probe=d561348222) | Feb 14, 2021 |
| Dell          | 0C522T A03                  | Desktop     | [0b52890aaf](https://linux-hardware.org/?probe=0b52890aaf) | Jan 29, 2021 |
| Dell          | 0C522T A03                  | Desktop     | [3a777180a1](https://linux-hardware.org/?probe=3a777180a1) | Jan 29, 2021 |
| Intel         | H61M-DS2                    | Desktop     | [930418d2da](https://linux-hardware.org/?probe=930418d2da) | Jan 23, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [4b7df9598e](https://linux-hardware.org/?probe=4b7df9598e) | Jan 20, 2021 |
| MSI           | GL65 Leopard 10SCXR         | Notebook    | [ac71737361](https://linux-hardware.org/?probe=ac71737361) | Jan 16, 2021 |
| Intel         | H61M-DS2                    | Desktop     | [53bde98202](https://linux-hardware.org/?probe=53bde98202) | Jan 09, 2021 |
| Acer          | Aspire 5733                 | Notebook    | [1f4e4d7fbc](https://linux-hardware.org/?probe=1f4e4d7fbc) | Jan 08, 2021 |
| Toshiba       | Satellite L55t-B            | Notebook    | [ab3b576bd1](https://linux-hardware.org/?probe=ab3b576bd1) | Jan 07, 2021 |
| Toshiba       | Satellite L55t-B            | Notebook    | [6fc9533a15](https://linux-hardware.org/?probe=6fc9533a15) | Jan 06, 2021 |
| ECS           | SF20PA2                     | Notebook    | [f26e0bf23f](https://linux-hardware.org/?probe=f26e0bf23f) | Jan 04, 2021 |
| HP            | 2000                        | Notebook    | [99481f08e3](https://linux-hardware.org/?probe=99481f08e3) | Dec 31, 2020 |
| Panasonic     | CF-31JEGAX1M                | Notebook    | [c0745f5a94](https://linux-hardware.org/?probe=c0745f5a94) | Dec 31, 2020 |
| HP            | Notebook                    | Notebook    | [213a94eab7](https://linux-hardware.org/?probe=213a94eab7) | Dec 28, 2020 |
| HP            | Notebook                    | Notebook    | [bb3749dd61](https://linux-hardware.org/?probe=bb3749dd61) | Dec 28, 2020 |
| MSI           | A55M-P33                    | Desktop     | [43267cc6f4](https://linux-hardware.org/?probe=43267cc6f4) | Dec 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f55e2642ef](https://linux-hardware.org/?probe=f55e2642ef) | Dec 15, 2020 |
| ASRock        | H310CM-HDV                  | Desktop     | [729161e56a](https://linux-hardware.org/?probe=729161e56a) | Dec 08, 2020 |
| ASRock        | H310CM-HDV                  | Desktop     | [37f7b460d4](https://linux-hardware.org/?probe=37f7b460d4) | Dec 08, 2020 |
| Toshiba       | Satellite C75D-C            | Notebook    | [f158fc821a](https://linux-hardware.org/?probe=f158fc821a) | Nov 10, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [5a8d4603be](https://linux-hardware.org/?probe=5a8d4603be) | Nov 03, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [19081a3c58](https://linux-hardware.org/?probe=19081a3c58) | Oct 27, 2020 |
| Dell          | Latitude E6430              | Notebook    | [8ea63ec090](https://linux-hardware.org/?probe=8ea63ec090) | Oct 23, 2020 |
| ASRock        | A320M-HDV                   | Desktop     | [912852805f](https://linux-hardware.org/?probe=912852805f) | Oct 22, 2020 |
| HP            | Pavilion dm4                | Notebook    | [21a3ef42e0](https://linux-hardware.org/?probe=21a3ef42e0) | Oct 13, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [64e95b4174](https://linux-hardware.org/?probe=64e95b4174) | Oct 10, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0ffffb855b](https://linux-hardware.org/?probe=0ffffb855b) | Oct 04, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7ddfb80220](https://linux-hardware.org/?probe=7ddfb80220) | Oct 04, 2020 |
| Dell          | 0C27VV A00                  | Desktop     | [fd9547e219](https://linux-hardware.org/?probe=fd9547e219) | Oct 01, 2020 |
| Toshiba       | Satellite C75D-C            | Notebook    | [12c65e3222](https://linux-hardware.org/?probe=12c65e3222) | Sep 25, 2020 |
| Unknown       | Unknown                     | Phone       | [6ff556bf54](https://linux-hardware.org/?probe=6ff556bf54) | Sep 06, 2020 |
| MSI           | GE62 6QD                    | Notebook    | [cf444064fc](https://linux-hardware.org/?probe=cf444064fc) | Sep 03, 2020 |
| Acer          | One S1003                   | Tablet      | [c89be38d5c](https://linux-hardware.org/?probe=c89be38d5c) | Aug 29, 2020 |
| HP            | Casablanca H710             | Notebook    | [2061828542](https://linux-hardware.org/?probe=2061828542) | Aug 26, 2020 |
| HP            | Casablanca H710             | Notebook    | [f566c52ffd](https://linux-hardware.org/?probe=f566c52ffd) | Aug 26, 2020 |
| Samsung       | NC208/NC108                 | Notebook    | [f425b1dc48](https://linux-hardware.org/?probe=f425b1dc48) | Aug 17, 2020 |
| Samsung       | NC208/NC108                 | Notebook    | [759ee832fb](https://linux-hardware.org/?probe=759ee832fb) | Aug 17, 2020 |
| Gigabyte      | H310M A-CF                  | Desktop     | [ff30e910c4](https://linux-hardware.org/?probe=ff30e910c4) | Aug 12, 2020 |
| Intel         | DP35DP AAD81073-208         | Desktop     | [0009968f3b](https://linux-hardware.org/?probe=0009968f3b) | Aug 05, 2020 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [71c07410ee](https://linux-hardware.org/?probe=71c07410ee) | Jul 25, 2020 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [3c55f58986](https://linux-hardware.org/?probe=3c55f58986) | Jul 03, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d4c35c226e](https://linux-hardware.org/?probe=d4c35c226e) | Jul 01, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [178da315d2](https://linux-hardware.org/?probe=178da315d2) | Jul 01, 2020 |
| Fujitsu       | D3064-A1 S26361-D3064-A1    | Desktop     | [6a4b069ed8](https://linux-hardware.org/?probe=6a4b069ed8) | Jun 30, 2020 |
| HP            | Presario CQ43               | Notebook    | [bba4f49ed1](https://linux-hardware.org/?probe=bba4f49ed1) | Jun 23, 2020 |
| Acer          | Aspire A715-72G             | Notebook    | [70acf4ea22](https://linux-hardware.org/?probe=70acf4ea22) | Jun 18, 2020 |
| HP            | Presario CQ43               | Notebook    | [3af51e5df2](https://linux-hardware.org/?probe=3af51e5df2) | Jun 13, 2020 |
| MSI           | H81M-E33                    | Desktop     | [9f2577531a](https://linux-hardware.org/?probe=9f2577531a) | Jun 10, 2020 |
| ECS           | SF20PA2                     | Notebook    | [fc1653c118](https://linux-hardware.org/?probe=fc1653c118) | Jun 10, 2020 |
| Dell          | Inspiron 5748               | Notebook    | [d7010adabe](https://linux-hardware.org/?probe=d7010adabe) | Jun 09, 2020 |
| OEM           | V40SI2                      | Notebook    | [e2ad8d9479](https://linux-hardware.org/?probe=e2ad8d9479) | Jun 06, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [13b3a46069](https://linux-hardware.org/?probe=13b3a46069) | May 27, 2020 |
| ASUSTek       | X555LAB                     | Notebook    | [7e4107b1b4](https://linux-hardware.org/?probe=7e4107b1b4) | May 26, 2020 |
| MSI           | B85-G43 GAMING              | Desktop     | [0a5437ade3](https://linux-hardware.org/?probe=0a5437ade3) | May 22, 2020 |
| ASUSTek       | P8H67-M LX                  | Desktop     | [0ba192cc01](https://linux-hardware.org/?probe=0ba192cc01) | May 22, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [7e4e3c078f](https://linux-hardware.org/?probe=7e4e3c078f) | May 20, 2020 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [627fed813d](https://linux-hardware.org/?probe=627fed813d) | May 18, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [493ce118d1](https://linux-hardware.org/?probe=493ce118d1) | May 16, 2020 |
| ASUSTek       | K8V-X SE                    | Desktop     | [154224ff78](https://linux-hardware.org/?probe=154224ff78) | May 16, 2020 |
| ASUSTek       | K8V-X SE                    | Desktop     | [173008c9ff](https://linux-hardware.org/?probe=173008c9ff) | May 16, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [98a86c1397](https://linux-hardware.org/?probe=98a86c1397) | May 15, 2020 |
| MSI           | GL63 8RD                    | Notebook    | [7e41ab8d71](https://linux-hardware.org/?probe=7e41ab8d71) | May 15, 2020 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [1beb748dc0](https://linux-hardware.org/?probe=1beb748dc0) | May 12, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [3b397b64f7](https://linux-hardware.org/?probe=3b397b64f7) | May 06, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [a9832cd92e](https://linux-hardware.org/?probe=a9832cd92e) | May 05, 2020 |
| HP            | 090Ch                       | Desktop     | [c471684991](https://linux-hardware.org/?probe=c471684991) | May 04, 2020 |
| HP            | 090Ch                       | Desktop     | [6f88fbc1ad](https://linux-hardware.org/?probe=6f88fbc1ad) | May 04, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [a8857822b2](https://linux-hardware.org/?probe=a8857822b2) | May 03, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [8609a3503d](https://linux-hardware.org/?probe=8609a3503d) | May 02, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [7fdc3c7af9](https://linux-hardware.org/?probe=7fdc3c7af9) | May 02, 2020 |
| MSI           | B85-G43 GAMING              | Desktop     | [1532d55ba0](https://linux-hardware.org/?probe=1532d55ba0) | May 01, 2020 |
| MSI           | B85-G43 GAMING              | Desktop     | [c931341a8c](https://linux-hardware.org/?probe=c931341a8c) | May 01, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [e52c07ce77](https://linux-hardware.org/?probe=e52c07ce77) | May 01, 2020 |
| Lenovo        | ThinkPad X240 20AMS72901    | Notebook    | [ad1e10654b](https://linux-hardware.org/?probe=ad1e10654b) | Apr 30, 2020 |
| Gateway       | DX4375                      | Desktop     | [1470b063f3](https://linux-hardware.org/?probe=1470b063f3) | Apr 28, 2020 |
| Standard      | EF20EA                      | Notebook    | [11882357e0](https://linux-hardware.org/?probe=11882357e0) | Apr 26, 2020 |
| ECS           | H310H5-M2                   | Desktop     | [b1aaebf57b](https://linux-hardware.org/?probe=b1aaebf57b) | Apr 19, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [3be039900b](https://linux-hardware.org/?probe=3be039900b) | Apr 17, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [cf6e400de0](https://linux-hardware.org/?probe=cf6e400de0) | Apr 17, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [bb8bd669f6](https://linux-hardware.org/?probe=bb8bd669f6) | Apr 17, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [f1caefcea5](https://linux-hardware.org/?probe=f1caefcea5) | Apr 17, 2020 |
| ASRock        | ALiveNF6P-VSTA              | Desktop     | [3036b319ab](https://linux-hardware.org/?probe=3036b319ab) | Apr 16, 2020 |
| ASRock        | ALiveNF6P-VSTA              | Desktop     | [ebd210c2af](https://linux-hardware.org/?probe=ebd210c2af) | Apr 16, 2020 |
| HP            | 620                         | Notebook    | [812b274fd4](https://linux-hardware.org/?probe=812b274fd4) | Apr 13, 2020 |
| HP            | 620                         | Notebook    | [ca26b96168](https://linux-hardware.org/?probe=ca26b96168) | Apr 13, 2020 |
| Acer          | One S1003                   | Tablet      | [f1cf80584b](https://linux-hardware.org/?probe=f1cf80584b) | Apr 07, 2020 |
| ASRock        | Z68 Pro3 Gen3               | Desktop     | [7534350893](https://linux-hardware.org/?probe=7534350893) | Mar 28, 2020 |
| HP            | 1497                        | Desktop     | [973b170ac6](https://linux-hardware.org/?probe=973b170ac6) | Mar 23, 2020 |
| Lenovo        | 312D NOK                    | Mini pc     | [36cb7c6a75](https://linux-hardware.org/?probe=36cb7c6a75) | Mar 23, 2020 |
| HP            | 1497                        | Desktop     | [26d8104c5e](https://linux-hardware.org/?probe=26d8104c5e) | Mar 02, 2020 |
| ECS           | SF20PA2                     | Notebook    | [d685560200](https://linux-hardware.org/?probe=d685560200) | Feb 01, 2020 |
| MSI           | A68HM-E33 V2                | Desktop     | [743f3ff81c](https://linux-hardware.org/?probe=743f3ff81c) | Dec 22, 2019 |
| MSI           | A68HM-E33 V2                | Desktop     | [1d3a9ef0d2](https://linux-hardware.org/?probe=1d3a9ef0d2) | Dec 22, 2019 |
| MSI           | A68HM-E33 V2                | Desktop     | [806c1e6d78](https://linux-hardware.org/?probe=806c1e6d78) | Dec 22, 2019 |
| ECS           | SF20PA2                     | Notebook    | [e6212ece14](https://linux-hardware.org/?probe=e6212ece14) | Nov 27, 2019 |
| ECS           | SF20PA2                     | Notebook    | [1d4a07f181](https://linux-hardware.org/?probe=1d4a07f181) | Nov 19, 2019 |
| Toshiba       | Satellite C55-B             | Notebook    | [1fab0cb871](https://linux-hardware.org/?probe=1fab0cb871) | Nov 16, 2019 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [c28821415f](https://linux-hardware.org/?probe=c28821415f) | Nov 15, 2019 |
| ECS           | SF20PA2                     | Notebook    | [063490d972](https://linux-hardware.org/?probe=063490d972) | Nov 03, 2019 |
| Gigabyte      | H81M-DS2                    | Desktop     | [273463747b](https://linux-hardware.org/?probe=273463747b) | Oct 29, 2019 |
| Gigabyte      | H81M-DS2                    | Desktop     | [dfda14135d](https://linux-hardware.org/?probe=dfda14135d) | Oct 28, 2019 |
| Gigabyte      | H81M-DS2                    | Desktop     | [3418011c79](https://linux-hardware.org/?probe=3418011c79) | Oct 27, 2019 |
| Gigabyte      | H81M-DS2                    | Desktop     | [cb622d3902](https://linux-hardware.org/?probe=cb622d3902) | Oct 27, 2019 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [623c96ec6e](https://linux-hardware.org/?probe=623c96ec6e) | Oct 07, 2019 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | Notebook    | [0925f5642c](https://linux-hardware.org/?probe=0925f5642c) | Sep 24, 2019 |
| ECS           | SF20PA2                     | Notebook    | [3c9b29c0c7](https://linux-hardware.org/?probe=3c9b29c0c7) | Sep 20, 2019 |
| ECS           | SF20PA2                     | Notebook    | [6d35e092fa](https://linux-hardware.org/?probe=6d35e092fa) | Sep 16, 2019 |
| Dell          | Inspiron 13-5368            | Notebook    | [0dab5b3510](https://linux-hardware.org/?probe=0dab5b3510) | Sep 15, 2019 |
| Lenovo        | 0x36C4 SDK0J40679 WIN 32... | All in one  | [00a1738003](https://linux-hardware.org/?probe=00a1738003) | Aug 14, 2019 |
| ECS           | SF20PA2                     | Notebook    | [80d3b6b8cf](https://linux-hardware.org/?probe=80d3b6b8cf) | Aug 04, 2019 |
| ECS           | SF20PA2                     | Notebook    | [a7b095e2f0](https://linux-hardware.org/?probe=a7b095e2f0) | Jul 30, 2019 |
| Intel         | NUC5CPYB H61145-404         | Mini pc     | [001551b002](https://linux-hardware.org/?probe=001551b002) | Jul 22, 2019 |
| ECS           | SF20PA2                     | Notebook    | [01cad0b14a](https://linux-hardware.org/?probe=01cad0b14a) | Jul 10, 2019 |
| Acer          | TravelMate P249-G2-M        | Notebook    | [0e1338db33](https://linux-hardware.org/?probe=0e1338db33) | Jul 01, 2019 |
| Lenovo        | 0x36C4 SDK0J40679 WIN 32... | All in one  | [30ff6dab9f](https://linux-hardware.org/?probe=30ff6dab9f) | Jun 13, 2019 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | Notebook    | [08c0f291e9](https://linux-hardware.org/?probe=08c0f291e9) | Jun 13, 2019 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | Notebook    | [5619d594fa](https://linux-hardware.org/?probe=5619d594fa) | Jun 10, 2019 |
| ASUSTek       | M5A87                       | Desktop     | [cead36d312](https://linux-hardware.org/?probe=cead36d312) | May 18, 2019 |
| ASUSTek       | M5A87                       | Desktop     | [6dfdec0635](https://linux-hardware.org/?probe=6dfdec0635) | May 18, 2019 |
| Dell          | Inspiron N5040              | Notebook    | [b8f0a4691d](https://linux-hardware.org/?probe=b8f0a4691d) | May 17, 2019 |
| HP            | 1998                        | Desktop     | [0ae1b2ac01](https://linux-hardware.org/?probe=0ae1b2ac01) | May 13, 2019 |
| Samsung       | 700T                        | Notebook    | [dcf693f16f](https://linux-hardware.org/?probe=dcf693f16f) | May 11, 2019 |
| HP            | Pavilion dv6                | Notebook    | [36299cef92](https://linux-hardware.org/?probe=36299cef92) | Apr 17, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b26531074c](https://linux-hardware.org/?probe=b26531074c) | Apr 16, 2019 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [547801f07c](https://linux-hardware.org/?probe=547801f07c) | Apr 15, 2019 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | Notebook    | [7d9905cfe7](https://linux-hardware.org/?probe=7d9905cfe7) | Mar 27, 2019 |
| ASUSTek       | TP300LAB                    | Notebook    | [538b5e5d24](https://linux-hardware.org/?probe=538b5e5d24) | Mar 26, 2019 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [859c76fdf7](https://linux-hardware.org/?probe=859c76fdf7) | Mar 17, 2019 |
| ASRock        | ALiveNF6P-VSTA              | Desktop     | [4684e2d239](https://linux-hardware.org/?probe=4684e2d239) | Dec 04, 2018 |
| ASRock        | ALiveNF6P-VSTA              | Desktop     | [a26c805e14](https://linux-hardware.org/?probe=a26c805e14) | Dec 04, 2018 |
| MSI           | G41M-P26                    | Desktop     | [59c7d54670](https://linux-hardware.org/?probe=59c7d54670) | Nov 10, 2018 |
| HP            | Pavilion 15                 | Notebook    | [7376903dca](https://linux-hardware.org/?probe=7376903dca) | May 13, 2018 |
| HP            | Pavilion 15                 | Notebook    | [2cc0124d5d](https://linux-hardware.org/?probe=2cc0124d5d) | May 13, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Uruguay/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 38        | 9.62%   |
| Ubuntu 18.04       | 30        | 7.59%   |
| Ubuntu 22.04       | 19        | 4.81%   |
| Manjaro            | 18        | 4.56%   |
| OpenMandriva 4.3   | 16        | 4.05%   |
| ArcoLinux Rolling  | 11        | 2.78%   |
| Arch Rolling       | 10        | 2.53%   |
| Linux Mint 21.2    | 8         | 2.03%   |
| KDE neon 20.04     | 8         | 2.03%   |
| Debian 12          | 8         | 2.03%   |
| OpenMandriva 4.2   | 7         | 1.77%   |
| OpenMandriva 23.03 | 7         | 1.77%   |
| Fedora 40          | 7         | 1.77%   |
| Linux Mint 19.3    | 6         | 1.52%   |
| Debian 11          | 6         | 1.52%   |
| Zorin 16           | 5         | 1.27%   |
| Xubuntu 20.04      | 5         | 1.27%   |
| Ubuntu 19.04       | 5         | 1.27%   |
| OpenMandriva 23.01 | 5         | 1.27%   |
| Linux Mint 21.3    | 5         | 1.27%   |
| Fedora 39          | 5         | 1.27%   |
| Zorin 17           | 4         | 1.01%   |
| Ubuntu 21.10       | 4         | 1.01%   |
| Ubuntu 18.10       | 4         | 1.01%   |
| Pop!_OS 22.04      | 4         | 1.01%   |
| OpenMandriva 23.08 | 4         | 1.01%   |
| Linux Mint 21.1    | 4         | 1.01%   |
| Linux Mint 19.1    | 4         | 1.01%   |
| Fedora 38          | 4         | 1.01%   |
| Fedora 36          | 4         | 1.01%   |
| Xubuntu 18.04      | 3         | 0.76%   |
| Ubuntu 23.10       | 3         | 0.76%   |
| ROSA R11.1         | 3         | 0.76%   |
| Linux Mint 20.3    | 3         | 0.76%   |
| Linux Mint 20      | 3         | 0.76%   |
| BlackPanther 18.1  | 3         | 0.76%   |
| Arch               | 3         | 0.76%   |
| Zorin 15           | 2         | 0.51%   |
| Ubuntu 24.04       | 2         | 0.51%   |
| Ubuntu 23.04       | 2         | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 110       | 29.65%  |
| Linux Mint   | 43        | 11.59%  |
| OpenMandriva | 39        | 10.51%  |
| Fedora       | 27        | 7.28%   |
| Manjaro      | 20        | 5.39%   |
| Debian       | 14        | 3.77%   |
| ArcoLinux    | 12        | 3.23%   |
| Arch         | 12        | 3.23%   |
| Zorin        | 11        | 2.96%   |
| Xubuntu      | 11        | 2.96%   |
| KDE neon     | 10        | 2.7%    |
| Pop!_OS      | 7         | 1.89%   |
| Kubuntu      | 6         | 1.62%   |
| Endless      | 6         | 1.62%   |
| ROSA         | 4         | 1.08%   |
| Lubuntu      | 4         | 1.08%   |
| openSUSE     | 3         | 0.81%   |
| LMDE         | 3         | 0.81%   |
| EndeavourOS  | 3         | 0.81%   |
| Elementary   | 3         | 0.81%   |
| BlackPanther | 3         | 0.81%   |
| Ubuntu MATE  | 2         | 0.54%   |
| SteamOS      | 2         | 0.54%   |
| NixOS        | 2         | 0.54%   |
| Archcraft    | 2         | 0.54%   |
| Android      | 2         | 0.54%   |
| Void Linux   | 1         | 0.27%   |
| UbuntuDDE    | 1         | 0.27%   |
| Nobara       | 1         | 0.27%   |
| MX           | 1         | 0.27%   |
| LinuxFX      | 1         | 0.27%   |
| Gentoo       | 1         | 0.27%   |
| Feren OS     | 1         | 0.27%   |
| blendOS      | 1         | 0.27%   |
| antiX        | 1         | 0.27%   |
| Alpine       | 1         | 0.27%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 15        | 3.56%   |
| 6.2.6-desktop-1omv2390   | 7         | 1.66%   |
| 5.10.14-desktop-1omv4002 | 7         | 1.66%   |
| 5.4.0-42-generic         | 6         | 1.43%   |
| 4.16.18-pa2-2bp1         | 6         | 1.43%   |
| 6.1.1-desktop-1omv2290   | 5         | 1.19%   |
| 5.11.0-38-generic        | 5         | 1.19%   |
| 4.16.18-pa2-1bp5         | 5         | 1.19%   |
| 6.5.0-41-generic         | 4         | 0.95%   |
| 5.8.0-53-generic         | 4         | 0.95%   |
| 5.5.19-bp0               | 4         | 0.95%   |
| 5.4.0-52-generic         | 4         | 0.95%   |
| 5.3.0-46-generic         | 4         | 0.95%   |
| 5.13.0-39-generic        | 4         | 0.95%   |
| 6.4.11-desktop-1omv2390  | 3         | 0.71%   |
| 6.1.0-26-amd64           | 3         | 0.71%   |
| 5.4.0-73-generic         | 3         | 0.71%   |
| 5.4.0-72-generic         | 3         | 0.71%   |
| 5.4.0-65-generic         | 3         | 0.71%   |
| 5.4.0-58-generic         | 3         | 0.71%   |
| 5.15.0-67-generic        | 3         | 0.71%   |
| 5.15.0-46-generic        | 3         | 0.71%   |
| 5.10.0-21-amd64          | 3         | 0.71%   |
| 5.0.0-32-generic         | 3         | 0.71%   |
| 4.18.16-desktop-1bP      | 3         | 0.71%   |
| 6.9.12-3-MANJARO         | 2         | 0.48%   |
| 6.8.0-45-generic         | 2         | 0.48%   |
| 6.8.0-40-generic         | 2         | 0.48%   |
| 6.6.2-desktop-1omv2390   | 2         | 0.48%   |
| 6.5.12-300.fc39.x86_64   | 2         | 0.48%   |
| 6.5.0-45-generic         | 2         | 0.48%   |
| 6.5.0-17-generic         | 2         | 0.48%   |
| 6.5.0-15-generic         | 2         | 0.48%   |
| 6.4.7-arch1-1            | 2         | 0.48%   |
| 6.3.9-zen1-1-zen         | 2         | 0.48%   |
| 6.2.0-39-generic         | 2         | 0.48%   |
| 6.2.0-34-generic         | 2         | 0.48%   |
| 6.10.4-200.fc40.x86_64   | 2         | 0.48%   |
| 6.1.26-1-MANJARO         | 2         | 0.48%   |
| 6.1.0-18-amd64           | 2         | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 43        | 10.54%  |
| 5.15.0  | 25        | 6.13%   |
| 4.15.0  | 20        | 4.9%    |
| 6.5.0   | 17        | 4.17%   |
| 5.16.7  | 15        | 3.68%   |
| 5.13.0  | 15        | 3.68%   |
| 5.8.0   | 13        | 3.19%   |
| 5.11.0  | 12        | 2.94%   |
| 5.3.0   | 11        | 2.7%    |
| 4.16.18 | 11        | 2.7%    |
| 5.0.0   | 10        | 2.45%   |
| 6.8.0   | 9         | 2.21%   |
| 6.2.0   | 8         | 1.96%   |
| 6.1.0   | 8         | 1.96%   |
| 4.18.0  | 8         | 1.96%   |
| 6.2.6   | 7         | 1.72%   |
| 5.19.0  | 7         | 1.72%   |
| 5.10.14 | 7         | 1.72%   |
| 5.10.0  | 7         | 1.72%   |
| 6.1.1   | 5         | 1.23%   |
| 6.4.11  | 4         | 0.98%   |
| 5.5.19  | 4         | 0.98%   |
| 6.9.12  | 3         | 0.74%   |
| 5.17.5  | 3         | 0.74%   |
| 4.18.16 | 3         | 0.74%   |
| 6.8.5   | 2         | 0.49%   |
| 6.7.9   | 2         | 0.49%   |
| 6.6.2   | 2         | 0.49%   |
| 6.5.5   | 2         | 0.49%   |
| 6.5.12  | 2         | 0.49%   |
| 6.4.7   | 2         | 0.49%   |
| 6.3.9   | 2         | 0.49%   |
| 6.3.4   | 2         | 0.49%   |
| 6.2.12  | 2         | 0.49%   |
| 6.10.4  | 2         | 0.49%   |
| 6.1.26  | 2         | 0.49%   |
| 6.1.11  | 2         | 0.49%   |
| 5.4.83  | 2         | 0.49%   |
| 5.19.12 | 2         | 0.49%   |
| 5.18.12 | 2         | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 47        | 11.69%  |
| 5.15    | 31        | 7.71%   |
| 6.5     | 25        | 6.22%   |
| 6.1     | 22        | 5.47%   |
| 4.15    | 20        | 4.98%   |
| 6.2     | 19        | 4.73%   |
| 5.16    | 19        | 4.73%   |
| 5.10    | 19        | 4.73%   |
| 5.11    | 18        | 4.48%   |
| 6.6     | 16        | 3.98%   |
| 5.13    | 16        | 3.98%   |
| 5.8     | 15        | 3.73%   |
| 6.8     | 14        | 3.48%   |
| 5.3     | 12        | 2.99%   |
| 4.16    | 12        | 2.99%   |
| 4.18    | 11        | 2.74%   |
| 6.4     | 10        | 2.49%   |
| 5.19    | 10        | 2.49%   |
| 5.0     | 10        | 2.49%   |
| 6.3     | 6         | 1.49%   |
| 5.17    | 6         | 1.49%   |
| 6.0     | 5         | 1.24%   |
| 5.18    | 5         | 1.24%   |
| 6.9     | 4         | 1%      |
| 6.10    | 4         | 1%      |
| 5.5     | 4         | 1%      |
| 5.12    | 4         | 1%      |
| 6.11    | 3         | 0.75%   |
| 6.7     | 2         | 0.5%    |
| 5.6     | 2         | 0.5%    |
| 5.14    | 2         | 0.5%    |
| 4.9     | 2         | 0.5%    |
| 6.12    | 1         | 0.25%   |
| 5.2     | 1         | 0.25%   |
| 4.8     | 1         | 0.25%   |
| 4.4     | 1         | 0.25%   |
| 4.17    | 1         | 0.25%   |
| 4.13    | 1         | 0.25%   |
| 4.12    | 1         | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 347       | 98.02%  |
| i686   | 5         | 1.41%   |
| armv8l | 2         | 0.56%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 123       | 33.15%  |
| KDE5            | 76        | 20.49%  |
| Unknown         | 41        | 11.05%  |
| X-Cinnamon      | 34        | 9.16%   |
| XFCE            | 33        | 8.89%   |
| GNOME Flashback | 13        | 3.5%    |
| KDE             | 8         | 2.16%   |
| MATE            | 7         | 1.89%   |
| LXDE            | 5         | 1.35%   |
| Cinnamon        | 5         | 1.35%   |
| LXQt            | 4         | 1.08%   |
| Pantheon        | 3         | 0.81%   |
| KDE6            | 3         | 0.81%   |
| i3              | 3         | 0.81%   |
| openbox         | 2         | 0.54%   |
| KDE4            | 2         | 0.54%   |
| bspwm           | 2         | 0.54%   |
| sway            | 1         | 0.27%   |
| qtile           | 1         | 0.27%   |
| LeftWM          | 1         | 0.27%   |
| ICEWM           | 1         | 0.27%   |
| Enlightenment   | 1         | 0.27%   |
| Endless:GNOME   | 1         | 0.27%   |
| Deepin          | 1         | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 269       | 72.51%  |
| Wayland | 79        | 21.29%  |
| Unknown | 19        | 5.12%   |
| Tty     | 4         | 1.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 172       | 46.49%  |
| SDDM    | 72        | 19.46%  |
| LightDM | 46        | 12.43%  |
| GDM3    | 36        | 9.73%   |
| GDM     | 34        | 9.19%   |
| TDM     | 4         | 1.08%   |
| LY-DM   | 2         | 0.54%   |
| KDM     | 2         | 0.54%   |
| XDM     | 1         | 0.27%   |
| GREETD  | 1         | 0.27%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| es_UY      | 191       | 50.8%   |
| en_US      | 89        | 23.67%  |
| es_ES      | 34        | 9.04%   |
| Unknown    | 32        | 8.51%   |
| es_MX      | 8         | 2.13%   |
| es_AR      | 8         | 2.13%   |
| C          | 7         | 1.86%   |
| es_UY.UTF8 | 2         | 0.53%   |
| en_CA      | 2         | 0.53%   |
| pt_BR      | 1         | 0.27%   |
| POSIX      | 1         | 0.27%   |
| en_GB      | 1         | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 184       | 50.41%  |
| EFI  | 181       | 49.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 266       | 72.09%  |
| Overlay | 39        | 10.57%  |
| Btrfs   | 33        | 8.94%   |
| Tmpfs   | 19        | 5.15%   |
| Unknown | 8         | 2.17%   |
| Xfs     | 3         | 0.81%   |
| Ext3    | 1         | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 186       | 50.82%  |
| GPT     | 144       | 39.34%  |
| MBR     | 36        | 9.84%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 291       | 80.83%  |
| Yes       | 69        | 19.17%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 266       | 73.08%  |
| Yes       | 98        | 26.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 61        | 17.23%  |
| Lenovo              | 47        | 13.28%  |
| ASUSTek Computer    | 42        | 11.86%  |
| Dell                | 32        | 9.04%   |
| Gigabyte Technology | 25        | 7.06%   |
| ASRock              | 24        | 6.78%   |
| MSI                 | 19        | 5.37%   |
| Acer                | 18        | 5.08%   |
| ECS                 | 17        | 4.8%    |
| Toshiba             | 10        | 2.82%   |
| Standard            | 6         | 1.69%   |
| Samsung Electronics | 6         | 1.69%   |
| Intel               | 6         | 1.69%   |
| GPU Company         | 3         | 0.85%   |
| Gateway             | 3         | 0.85%   |
| Chuwi               | 3         | 0.85%   |
| Biostar             | 3         | 0.85%   |
| Apple               | 3         | 0.85%   |
| Unknown             | 3         | 0.85%   |
| Valve               | 2         | 0.56%   |
| Google              | 2         | 0.56%   |
| Fujitsu             | 2         | 0.56%   |
| Supermicro          | 1         | 0.28%   |
| Sony                | 1         | 0.28%   |
| Razer               | 1         | 0.28%   |
| Positivo            | 1         | 0.28%   |
| Pegatron            | 1         | 0.28%   |
| Panasonic           | 1         | 0.28%   |
| OEM                 | 1         | 0.28%   |
| Microsoft           | 1         | 0.28%   |
| MACHINIST           | 1         | 0.28%   |
| JP-IK               | 1         | 0.28%   |
| iClever             | 1         | 0.28%   |
| Huanan              | 1         | 0.28%   |
| Haitech             | 1         | 0.28%   |
| GMKtec              | 1         | 0.28%   |
| Foxconn             | 1         | 0.28%   |
| AZW                 | 1         | 0.28%   |
| Alienware           | 1         | 0.28%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ECS SF20PA2                                | 16        | 4.52%   |
| Unknown                                    | 5         | 1.41%   |
| Standard SF20BA2                           | 4         | 1.13%   |
| Lenovo IdeaCentre AIO 310-20IAP F0CL0014LD | 3         | 0.85%   |
| HP Dragonfly Pro ONE                       | 3         | 0.85%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV      | 3         | 0.85%   |
| Valve Jupiter                              | 2         | 0.56%   |
| Toshiba Satellite L55t-B                   | 2         | 0.56%   |
| MSI MS-7C37                                | 2         | 0.56%   |
| MSI MS-7817                                | 2         | 0.56%   |
| MSI MS-7721                                | 2         | 0.56%   |
| HP Stream Laptop 14-ax0XX                  | 2         | 0.56%   |
| HP Pavilion 15                             | 2         | 0.56%   |
| HP Notebook                                | 2         | 0.56%   |
| HP Laptop 15-bw0xx                         | 2         | 0.56%   |
| HP Laptop 15-bs0xx                         | 2         | 0.56%   |
| HP Compaq 6200 Pro SFF PC                  | 2         | 0.56%   |
| Gigabyte Z390 AORUS ELITE                  | 2         | 0.56%   |
| Gigabyte Z370 AORUS Gaming 7               | 2         | 0.56%   |
| Gigabyte H61M-S1                           | 2         | 0.56%   |
| Gigabyte H310M A                           | 2         | 0.56%   |
| Gigabyte B450 GAMING X                     | 2         | 0.56%   |
| Dell OptiPlex 7010                         | 2         | 0.56%   |
| Dell Inspiron 15-3567                      | 2         | 0.56%   |
| ASUS TUF Gaming B650M-PLUS WIFI            | 2         | 0.56%   |
| ASUS PRIME A320M-K                         | 2         | 0.56%   |
| ASUS All Series                            | 2         | 0.56%   |
| ASRock N68-S                               | 2         | 0.56%   |
| ASRock H310CM-HDV                          | 2         | 0.56%   |
| ASRock FM2A58M-VG3+ R2.0                   | 2         | 0.56%   |
| ASRock ALiveNF6P-VSTA                      | 2         | 0.56%   |
| ASRock A320M-HDV R4.0                      | 2         | 0.56%   |
| Acer Aspire A315-59                        | 2         | 0.56%   |
| Toshiba Satellite L755                     | 1         | 0.28%   |
| Toshiba Satellite L45-B                    | 1         | 0.28%   |
| Toshiba Satellite C855                     | 1         | 0.28%   |
| Toshiba Satellite C75D-C                   | 1         | 0.28%   |
| Toshiba Satellite C75D-B                   | 1         | 0.28%   |
| Toshiba Satellite C645D                    | 1         | 0.28%   |
| Toshiba Satellite C55-B                    | 1         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 19        | 5.37%   |
| ECS SF20PA2        | 16        | 4.52%   |
| HP Laptop          | 13        | 3.67%   |
| Acer Aspire        | 13        | 3.67%   |
| Lenovo IdeaPad     | 11        | 3.11%   |
| HP Pavilion        | 11        | 3.11%   |
| Dell Inspiron      | 11        | 3.11%   |
| Toshiba Satellite  | 10        | 2.82%   |
| HP Compaq          | 8         | 2.26%   |
| Dell Latitude      | 8         | 2.26%   |
| Dell OptiPlex      | 7         | 1.98%   |
| ASUS VivoBook      | 6         | 1.69%   |
| ASUS ROG           | 6         | 1.69%   |
| Unknown            | 5         | 1.41%   |
| Standard SF20BA2   | 4         | 1.13%   |
| Lenovo ThinkCentre | 4         | 1.13%   |
| HP EliteBook       | 4         | 1.13%   |
| ASUS ZenBook       | 4         | 1.13%   |
| ASUS TUF           | 4         | 1.13%   |
| ASUS PRIME         | 4         | 1.13%   |
| ASRock A320M-HDV   | 4         | 1.13%   |
| Lenovo IdeaCentre  | 3         | 0.85%   |
| HP Stream          | 3         | 0.85%   |
| HP Dragonfly       | 3         | 0.85%   |
| Valve Jupiter      | 2         | 0.56%   |
| MSI MS-7C37        | 2         | 0.56%   |
| MSI MS-7817        | 2         | 0.56%   |
| MSI MS-7721        | 2         | 0.56%   |
| Lenovo Legion      | 2         | 0.56%   |
| HP Presario        | 2         | 0.56%   |
| HP Notebook        | 2         | 0.56%   |
| HP ENVY            | 2         | 0.56%   |
| HP EliteDesk       | 2         | 0.56%   |
| HP 240             | 2         | 0.56%   |
| Gigabyte Z390      | 2         | 0.56%   |
| Gigabyte Z370      | 2         | 0.56%   |
| Gigabyte H61M-S1   | 2         | 0.56%   |
| Gigabyte H310M     | 2         | 0.56%   |
| Gigabyte B450M     | 2         | 0.56%   |
| Gigabyte B450      | 2         | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2017    | 40        | 11.3%   |
| 2011    | 30        | 8.47%   |
| 2019    | 29        | 8.19%   |
| 2018    | 28        | 7.91%   |
| 2013    | 28        | 7.91%   |
| 2012    | 27        | 7.63%   |
| 2015    | 25        | 7.06%   |
| 2020    | 24        | 6.78%   |
| 2014    | 21        | 5.93%   |
| 2016    | 20        | 5.65%   |
| 2022    | 15        | 4.24%   |
| 2021    | 15        | 4.24%   |
| 2009    | 10        | 2.82%   |
| 2023    | 9         | 2.54%   |
| 2007    | 9         | 2.54%   |
| 2010    | 8         | 2.26%   |
| 2024    | 5         | 1.41%   |
| 2008    | 5         | 1.41%   |
| Unknown | 2         | 0.56%   |
| 2006    | 1         | 0.28%   |
| 2005    | 1         | 0.28%   |
| 2004    | 1         | 0.28%   |
| 2003    | 1         | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 217       | 61.3%   |
| Desktop     | 123       | 34.75%  |
| Mini pc     | 4         | 1.13%   |
| Convertible | 3         | 0.85%   |
| All in one  | 3         | 0.85%   |
| Phone       | 2         | 0.56%   |
| Tablet      | 2         | 0.56%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 331       | 92.46%  |
| Enabled  | 27        | 7.54%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 351       | 99.15%  |
| Yes  | 3         | 0.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 90        | 24.66%  |
| 3.01-4.0    | 71        | 19.45%  |
| 16.01-24.0  | 60        | 16.44%  |
| 8.01-16.0   | 55        | 15.07%  |
| 1.01-2.0    | 37        | 10.14%  |
| 32.01-64.0  | 29        | 7.95%   |
| 24.01-32.0  | 13        | 3.56%   |
| 64.01-256.0 | 4         | 1.1%    |
| 2.01-3.0    | 3         | 0.82%   |
| 0.01-0.5    | 2         | 0.55%   |
| 0.51-1.0    | 1         | 0.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 145       | 36.71%  |
| 2.01-3.0   | 101       | 25.57%  |
| 3.01-4.0   | 50        | 12.66%  |
| 4.01-8.0   | 46        | 11.65%  |
| 0.51-1.0   | 24        | 6.08%   |
| 8.01-16.0  | 18        | 4.56%   |
| 0.01-0.5   | 7         | 1.77%   |
| 16.01-24.0 | 4         | 1.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 252       | 69.42%  |
| 2      | 78        | 21.49%  |
| 3      | 16        | 4.41%   |
| 4      | 11        | 3.03%   |
| 5      | 3         | 0.83%   |
| 0      | 2         | 0.55%   |
| 7      | 1         | 0.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 246       | 68.33%  |
| Yes       | 114       | 31.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 266       | 75.14%  |
| No        | 88        | 24.86%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 268       | 74.86%  |
| No        | 90        | 25.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 204       | 57.46%  |
| No        | 151       | 42.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Uruguay | 354       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Montevideo             | 282       | 75.4%   |
| Maldonado              | 18        | 4.81%   |
| Canelones              | 9         | 2.41%   |
| Punta del Este         | 5         | 1.34%   |
| San Jose de Mayo       | 4         | 1.07%   |
| Las Piedras            | 4         | 1.07%   |
| Florida                | 3         | 0.8%    |
| Ciudad del Plata       | 3         | 0.8%    |
| Buceo                  | 3         | 0.8%    |
| Salto                  | 2         | 0.53%   |
| Rocha                  | 2         | 0.53%   |
| Punta Gorda            | 2         | 0.53%   |
| Paysandú              | 2         | 0.53%   |
| Parque Rodo            | 2         | 0.53%   |
| Nueva Helvecia         | 2         | 0.53%   |
| Minas                  | 2         | 0.53%   |
| La Paz                 | 2         | 0.53%   |
| El Pinar               | 2         | 0.53%   |
| Durazno                | 2         | 0.53%   |
| Centro                 | 2         | 0.53%   |
| Solymar                | 1         | 0.27%   |
| Sayago                 | 1         | 0.27%   |
| Pocitos                | 1         | 0.27%   |
| Pinamar                | 1         | 0.27%   |
| Nuevo Paris            | 1         | 0.27%   |
| Melo                   | 1         | 0.27%   |
| Melilla                | 1         | 0.27%   |
| Maronas                | 1         | 0.27%   |
| Malvin Norte           | 1         | 0.27%   |
| Las Flores             | 1         | 0.27%   |
| La Barra               | 1         | 0.27%   |
| Joaquin Suarez         | 1         | 0.27%   |
| El Tesoro              | 1         | 0.27%   |
| Cordon                 | 1         | 0.27%   |
| Colonia Rosario        | 1         | 0.27%   |
| Colonia Nicolich       | 1         | 0.27%   |
| Chui                   | 1         | 0.27%   |
| Barrancas Coloradas    | 1         | 0.27%   |
| Atlantida              | 1         | 0.27%   |
| Arenas de Jose Ignacio | 1         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 88        | 114    | 18.68%  |
| Kingston                    | 60        | 78     | 12.74%  |
| Seagate                     | 55        | 73     | 11.68%  |
| Toshiba                     | 49        | 61     | 10.4%   |
| Samsung Electronics         | 36        | 39     | 7.64%   |
| Unknown                     | 35        | 46     | 7.43%   |
| SanDisk                     | 20        | 27     | 4.25%   |
| Hitachi                     | 12        | 19     | 2.55%   |
| SK hynix                    | 11        | 14     | 2.34%   |
| Micron Technology           | 9         | 10     | 1.91%   |
| Crucial                     | 9         | 14     | 1.91%   |
| HGST                        | 8         | 8      | 1.7%    |
| Netac                       | 7         | 9      | 1.49%   |
| Intel                       | 6         | 7      | 1.27%   |
| Biostar                     | 6         | 7      | 1.27%   |
| Hewlett-Packard             | 5         | 5      | 1.06%   |
| Phison                      | 4         | 7      | 0.85%   |
| Kingston Technology Company | 4         | 4      | 0.85%   |
| Dahua                       | 4         | 5      | 0.85%   |
| China                       | 4         | 4      | 0.85%   |
| Phison Electronics          | 3         | 3      | 0.64%   |
| Maxtor                      | 3         | 4      | 0.64%   |
| KIOXIA                      | 3         | 5      | 0.64%   |
| HS-SSD-C100                 | 3         | 5      | 0.64%   |
| Gigabyte Technology         | 3         | 4      | 0.64%   |
| Realtek Semiconductor       | 2         | 2      | 0.42%   |
| Patriot                     | 2         | 3      | 0.42%   |
| Micron/Crucial Technology   | 2         | 3      | 0.42%   |
| W800SH                      | 1         | 1      | 0.21%   |
| Union Memory (Shenzhen)     | 1         | 2      | 0.21%   |
| Silicon Motion              | 1         | 1      | 0.21%   |
| SAGE                        | 1         | 2      | 0.21%   |
| NGFF                        | 1         | 1      | 0.21%   |
| MAXIO Technology (Hangzhou) | 1         | 2      | 0.21%   |
| LITEON                      | 1         | 2      | 0.21%   |
| KingFast                    | 1         | 1      | 0.21%   |
| JMicron Technology          | 1         | 2      | 0.21%   |
| IBM-ESXS                    | 1         | 1      | 0.21%   |
| Hikvision                   | 1         | 1      | 0.21%   |
| Gateway                     | 1         | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 16        | 3.19%   |
| Kingston SA400S37240G 240GB SSD     | 16        | 3.19%   |
| Kingston SA400S37480G 480GB SSD     | 14        | 2.79%   |
| WDC WD10EZEX-08WN4A0 1TB            | 6         | 1.2%    |
| Toshiba DT01ACA300 3TB              | 6         | 1.2%    |
| Toshiba DT01ACA100 1TB              | 6         | 1.2%    |
| Seagate ST1000LM035-1RK172 1TB      | 6         | 1.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 6         | 1.2%    |
| Unknown DA4032  32GB                | 5         | 1%      |
| Toshiba MQ01ABD075 752GB            | 5         | 1%      |
| Seagate ST500LM012 HN-M500MBB 500GB | 5         | 1%      |
| Samsung HD161HJ 160GB               | 5         | 1%      |
| WDC WD5000AAKX-00ERMA0 500GB        | 4         | 0.8%    |
| Toshiba MQ01ABF050 500GB            | 4         | 0.8%    |
| Toshiba MQ01ABD100 1TB              | 4         | 0.8%    |
| Toshiba HDWK105 500GB               | 4         | 0.8%    |
| Seagate ST1000DM010-2EP102 1TB      | 4         | 0.8%    |
| Kingston SV300S37A120G 120GB SSD    | 4         | 0.8%    |
| Kingston SA400S37120G 120GB SSD     | 4         | 0.8%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 3         | 0.6%    |
| WDC WD5000BEKT-60KA9T0 500GB        | 3         | 0.6%    |
| WDC WD10EZEX-21WN4A0 1TB            | 3         | 0.6%    |
| Seagate ST500DM002-1BD142 500GB     | 3         | 0.6%    |
| Seagate ST250DM000-1BD141 250GB     | 3         | 0.6%    |
| SanDisk DF4032  32GB                | 3         | 0.6%    |
| Samsung SSD 860 EVO 500GB           | 3         | 0.6%    |
| Phison PSEIB001TABBMC0 1TB          | 3         | 0.6%    |
| Netac SSD 256GB                     | 3         | 0.6%    |
| Kingston SV300S37A480G 480GB SSD    | 3         | 0.6%    |
| Dahua C800 2.5 inch SATA 512GB SSD  | 3         | 0.6%    |
| Biostar S100-120GB                  | 3         | 0.6%    |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 2         | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2         | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 2         | 0.4%    |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 0.4%    |
| WDC WD5000LPVT-24G33T1 500GB        | 2         | 0.4%    |
| WDC WD5000AZLX-00ZR6A0 500GB        | 2         | 0.4%    |
| WDC WD5000AAKX-75U6AA0 500GB        | 2         | 0.4%    |
| WDC WD10EZEX-60WN4A1 1TB            | 2         | 0.4%    |
| WDC WD10EZEX-00BBHA0 1TB            | 2         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 74        | 95     | 34.26%  |
| Seagate             | 55        | 73     | 25.46%  |
| Toshiba             | 44        | 56     | 20.37%  |
| Samsung Electronics | 15        | 16     | 6.94%   |
| Hitachi             | 12        | 19     | 5.56%   |
| HGST                | 8         | 8      | 3.7%    |
| Maxtor              | 3         | 4      | 1.39%   |
| Unknown             | 2         | 2      | 0.93%   |
| SAGE                | 1         | 2      | 0.46%   |
| JMicron Technology  | 1         | 2      | 0.46%   |
| ExcelStor           | 1         | 1      | 0.46%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 47        | 55     | 37.01%  |
| WDC                 | 11        | 12     | 8.66%   |
| Samsung Electronics | 10        | 11     | 7.87%   |
| Netac               | 7         | 9      | 5.51%   |
| Crucial             | 7         | 10     | 5.51%   |
| SanDisk             | 6         | 8      | 4.72%   |
| Biostar             | 6         | 7      | 4.72%   |
| Hewlett-Packard     | 4         | 4      | 3.15%   |
| Dahua               | 4         | 5      | 3.15%   |
| China               | 4         | 4      | 3.15%   |
| SK hynix            | 3         | 3      | 2.36%   |
| Micron Technology   | 3         | 4      | 2.36%   |
| Gigabyte Technology | 3         | 4      | 2.36%   |
| Intel               | 2         | 2      | 1.57%   |
| W800SH              | 1         | 1      | 0.79%   |
| Toshiba             | 1         | 1      | 0.79%   |
| Patriot             | 1         | 2      | 0.79%   |
| NGFF                | 1         | 1      | 0.79%   |
| HS-SSD-C100         | 1         | 1      | 0.79%   |
| Hikvision           | 1         | 1      | 0.79%   |
| Gateway             | 1         | 1      | 0.79%   |
| BIWIN               | 1         | 1      | 0.79%   |
| BHT                 | 1         | 1      | 0.79%   |
| A-DATA Technology   | 1         | 1      | 0.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 179       | 278    | 42.12%  |
| SSD     | 121       | 149    | 28.47%  |
| NVMe    | 84        | 121    | 19.76%  |
| MMC     | 36        | 46     | 8.47%   |
| Unknown | 5         | 9      | 1.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 254       | 424    | 66.49%  |
| NVMe | 84        | 121    | 21.99%  |
| MMC  | 36        | 46     | 9.42%   |
| SAS  | 8         | 12     | 2.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 196       | 272    | 64.69%  |
| 0.51-1.0   | 89        | 133    | 29.37%  |
| 2.01-3.0   | 8         | 10     | 2.64%   |
| 1.01-2.0   | 7         | 8      | 2.31%   |
| 3.01-4.0   | 3         | 4      | 0.99%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 91        | 23.88%  |
| 101-250        | 90        | 23.62%  |
| 501-1000       | 56        | 14.7%   |
| 1-20           | 38        | 9.97%   |
| 21-50          | 30        | 7.87%   |
| 1001-2000      | 29        | 7.61%   |
| 51-100         | 22        | 5.77%   |
| Unknown        | 12        | 3.15%   |
| 2001-3000      | 7         | 1.84%   |
| More than 3000 | 6         | 1.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 156       | 39.49%  |
| 21-50          | 71        | 17.97%  |
| 101-250        | 46        | 11.65%  |
| 51-100         | 44        | 11.14%  |
| 251-500        | 31        | 7.85%   |
| 501-1000       | 21        | 5.32%   |
| Unknown        | 12        | 3.04%   |
| 1001-2000      | 9         | 2.28%   |
| 2001-3000      | 3         | 0.76%   |
| More than 3000 | 2         | 0.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEKT-60KA9T0 500GB                                    | 3         | 3      | 7.14%   |
| Seagate ST250DM000-1BD141 250GB                                 | 3         | 3      | 7.14%   |
| Toshiba MK5059GSXP 500GB                                        | 2         | 3      | 4.76%   |
| Seagate ST500DM002-1BD142 500GB                                 | 2         | 2      | 4.76%   |
| Seagate ST3750640NS 752GB                                       | 2         | 7      | 4.76%   |
| WDC WD800BD-00LRA1 80GB                                         | 1         | 1      | 2.38%   |
| WDC WD5000LPCX-24C6HT0 500GB                                    | 1         | 1      | 2.38%   |
| WDC WD5000AAKX-75U6AA0 500GB                                    | 1         | 2      | 2.38%   |
| WDC WD5000AAJS-00A8B0 500GB                                     | 1         | 1      | 2.38%   |
| WDC WD3200BEVT-26ZCT0 320GB                                     | 1         | 1      | 2.38%   |
| WDC WD2500AVJS-63B6A0 250GB                                     | 1         | 1      | 2.38%   |
| WDC WD10SPCX-24HWST1 1TB                                        | 1         | 1      | 2.38%   |
| WDC WD10EZEX-08WN4A0 1TB                                        | 1         | 1      | 2.38%   |
| WDC WD10EARS-22Y5B1 1TB                                         | 1         | 1      | 2.38%   |
| Toshiba MQ01ABD075 752GB                                        | 1         | 1      | 2.38%   |
| Toshiba MK3276GSX 320GB                                         | 1         | 1      | 2.38%   |
| Toshiba MK3265GSX 320GB                                         | 1         | 1      | 2.38%   |
| Toshiba MK3259GSXP 320GB                                        | 1         | 1      | 2.38%   |
| Toshiba MK2555GSX 250GB                                         | 1         | 1      | 2.38%   |
| Toshiba DT01ACA100 1TB                                          | 1         | 1      | 2.38%   |
| Seagate ST980811AS 80GB                                         | 1         | 2      | 2.38%   |
| Seagate ST9120821AS 120GB                                       | 1         | 1      | 2.38%   |
| Seagate ST500LM021-1KJ152 500GB                                 | 1         | 1      | 2.38%   |
| Seagate ST500DM005 HD502HJ 500GB                                | 1         | 1      | 2.38%   |
| Seagate ST3250310CS 250GB                                       | 1         | 1      | 2.38%   |
| Seagate ST3200827AS 200GB                                       | 1         | 1      | 2.38%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 1         | 1      | 2.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 1         | 1      | 2.38%   |
| Seagate ST1000DM010-2EP102 1TB                                  | 1         | 1      | 2.38%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD                             | 1         | 1      | 2.38%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 512GB | 1         | 2      | 2.38%   |
| Kingston SA400S37480G 480GB SSD                                 | 1         | 2      | 2.38%   |
| HS-SSD-C100 SSD 240G                                            | 1         | 1      | 2.38%   |
| Hitachi HTS547564A9E384 640GB                                   | 1         | 1      | 2.38%   |
| HGST HTS545032A7E380 320GB                                      | 1         | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 22     | 37.5%   |
| WDC                 | 11        | 13     | 27.5%   |
| Toshiba             | 8         | 9      | 20%     |
| SanDisk             | 1         | 1      | 2.5%    |
| Samsung Electronics | 1         | 2      | 2.5%    |
| Kingston            | 1         | 2      | 2.5%    |
| HS-SSD-C100         | 1         | 1      | 2.5%    |
| Hitachi             | 1         | 1      | 2.5%    |
| HGST                | 1         | 1      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 15        | 22     | 41.67%  |
| WDC     | 11        | 13     | 30.56%  |
| Toshiba | 8         | 9      | 22.22%  |
| Hitachi | 1         | 1      | 2.78%   |
| HGST    | 1         | 1      | 2.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 35        | 46     | 89.74%  |
| SSD  | 3         | 4      | 7.69%   |
| NVMe | 1         | 2      | 2.56%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 218       | 352    | 57.82%  |
| Works    | 120       | 199    | 31.83%  |
| Malfunc  | 39        | 52     | 10.34%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 229       | 56.27%  |
| AMD                              | 77        | 18.92%  |
| SanDisk                          | 17        | 4.18%   |
| Kingston Technology Company      | 16        | 3.93%   |
| Samsung Electronics              | 11        | 2.7%    |
| SK hynix                         | 7         | 1.72%   |
| Phison Electronics               | 7         | 1.72%   |
| Nvidia                           | 6         | 1.47%   |
| Micron Technology                | 6         | 1.47%   |
| Toshiba America Info Systems     | 5         | 1.23%   |
| ASMedia Technology               | 5         | 1.23%   |
| Silicon Motion                   | 4         | 0.98%   |
| Micron/Crucial Technology        | 4         | 0.98%   |
| Realtek Semiconductor            | 2         | 0.49%   |
| Marvell Technology Group         | 2         | 0.49%   |
| KIOXIA                           | 2         | 0.49%   |
| VIA Technologies                 | 1         | 0.25%   |
| Union Memory (Shenzhen)          | 1         | 0.25%   |
| Silicon Integrated Systems [SiS] | 1         | 0.25%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.25%   |
| Lite-On Technology               | 1         | 0.25%   |
| Apple                            | 1         | 0.25%   |
| Adaptec                          | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 53        | 11.13%  |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 20        | 4.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 17        | 3.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 14        | 2.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 12        | 2.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 10        | 2.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 9         | 1.89%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 9         | 1.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9         | 1.89%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 1.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 8         | 1.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8         | 1.68%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 7         | 1.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 7         | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7         | 1.47%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7         | 1.47%   |
| Nvidia MCP61 SATA Controller                                                            | 6         | 1.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6         | 1.26%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6         | 1.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6         | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6         | 1.26%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 1.26%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 6         | 1.26%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 5         | 1.05%   |
| Nvidia MCP61 IDE                                                                        | 5         | 1.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 5         | 1.05%   |
| Intel Alder Lake-P SATA AHCI Controller                                                 | 5         | 1.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 1.05%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 5         | 1.05%   |
| AMD FCH IDE Controller                                                                  | 5         | 1.05%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 4         | 0.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 0.84%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 0.84%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 4         | 0.84%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 4         | 0.84%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4         | 0.84%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 4         | 0.84%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4         | 0.84%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 271       | 63.76%  |
| NVMe | 84        | 19.76%  |
| IDE  | 49        | 11.53%  |
| RAID | 20        | 4.71%   |
| SCSI | 1         | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 255       | 72.03%  |
| AMD      | 97        | 27.4%   |
| QUALCOMM | 1         | 0.28%   |
| ARM      | 1         | 0.28%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Celeron CPU N3350 @ 1.10GHz       | 17        | 4.78%   |
| Intel 12th Gen Core i7-1255U            | 5         | 1.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 1.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 4         | 1.12%   |
| Intel Celeron CPU N3160 @ 1.60GHz       | 4         | 1.12%   |
| Intel Celeron CPU N3050 @ 1.60GHz       | 4         | 1.12%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 0.84%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 3         | 0.84%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 3         | 0.84%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 3         | 0.84%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 3         | 0.84%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 3         | 0.84%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 0.84%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 3         | 0.84%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 0.84%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3         | 0.84%   |
| Intel Core i3-4170 CPU @ 3.70GHz        | 3         | 0.84%   |
| Intel Core i3-2120 CPU @ 3.30GHz        | 3         | 0.84%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 3         | 0.84%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 3         | 0.84%   |
| Intel Celeron CPU J3355 @ 2.00GHz       | 3         | 0.84%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 3         | 0.84%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 0.84%   |
| AMD Ryzen 9 4900HS with Radeon Graphics | 3         | 0.84%   |
| AMD Ryzen 7 7736U with Radeon Graphics  | 3         | 0.84%   |
| AMD Ryzen 5 1600 Six-Core Processor     | 3         | 0.84%   |
| AMD E-300 APU with Radeon HD Graphics   | 3         | 0.84%   |
| Intel Pentium CPU P6200 @ 2.13GHz       | 2         | 0.56%   |
| Intel Pentium CPU N3710 @ 1.60GHz       | 2         | 0.56%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 0.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 2         | 0.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 0.56%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 0.56%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 2         | 0.56%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 2         | 0.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 2         | 0.56%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 2         | 0.56%   |
| Intel Core i5-4200M CPU @ 2.50GHz       | 2         | 0.56%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 2         | 0.56%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 60        | 16.85%  |
| Intel Core i7        | 50        | 14.04%  |
| Intel Celeron        | 50        | 14.04%  |
| Intel Core i3        | 35        | 9.83%   |
| Other                | 19        | 5.34%   |
| AMD Ryzen 5          | 16        | 4.49%   |
| AMD Ryzen 7          | 14        | 3.93%   |
| Intel Pentium        | 11        | 3.09%   |
| Intel Core 2 Duo     | 10        | 2.81%   |
| AMD A6               | 9         | 2.53%   |
| Intel Atom           | 8         | 2.25%   |
| AMD Ryzen 3          | 6         | 1.69%   |
| AMD Athlon II X2     | 6         | 1.69%   |
| AMD Ryzen 9          | 5         | 1.4%    |
| AMD FX               | 5         | 1.4%    |
| Intel Xeon           | 4         | 1.12%   |
| AMD A10              | 4         | 1.12%   |
| Intel Genuine        | 3         | 0.84%   |
| Intel Core 2 Quad    | 3         | 0.84%   |
| AMD Phenom II X6     | 3         | 0.84%   |
| AMD E2               | 3         | 0.84%   |
| AMD E                | 3         | 0.84%   |
| AMD Athlon           | 3         | 0.84%   |
| AMD A8               | 3         | 0.84%   |
| AMD A4               | 3         | 0.84%   |
| Intel Core 2         | 2         | 0.56%   |
| AMD E1               | 2         | 0.56%   |
| QUALCOMM AArch64     | 1         | 0.28%   |
| Intel Pentium Silver | 1         | 0.28%   |
| Intel Pentium Dual   | 1         | 0.28%   |
| Intel Pentium 4      | 1         | 0.28%   |
| Intel Core m3        | 1         | 0.28%   |
| Intel Core i9        | 1         | 0.28%   |
| Intel Core           | 1         | 0.28%   |
| ARM AArch64          | 1         | 0.28%   |
| AMD Ryzen 5 PRO      | 1         | 0.28%   |
| AMD Ryzen 3 PRO      | 1         | 0.28%   |
| AMD PRO A10          | 1         | 0.28%   |
| AMD Phenom II        | 1         | 0.28%   |
| AMD Phenom           | 1         | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 172       | 48.45%  |
| 4      | 104       | 29.3%   |
| 6      | 37        | 10.42%  |
| 8      | 24        | 6.76%   |
| 1      | 8         | 2.25%   |
| 10     | 6         | 1.69%   |
| 12     | 2         | 0.56%   |
| 16     | 1         | 0.28%   |
| 14     | 1         | 0.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 351       | 99.15%  |
| 2      | 3         | 0.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 207       | 58.47%  |
| 1      | 147       | 41.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 346       | 97.74%  |
| Unknown        | 6         | 1.69%   |
| 32-bit         | 2         | 0.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 150       | 40.21%  |
| 0x206a7    | 14        | 3.75%   |
| 0x306c3    | 9         | 2.41%   |
| 0x306a9    | 9         | 2.41%   |
| 0x906ea    | 8         | 2.14%   |
| 0x506c9    | 8         | 2.14%   |
| 0x406c4    | 8         | 2.14%   |
| 0x20655    | 8         | 2.14%   |
| 0x40651    | 7         | 1.88%   |
| 0x806e9    | 6         | 1.61%   |
| 0x1067a    | 6         | 1.61%   |
| 0x08108109 | 6         | 1.61%   |
| 0x806ec    | 5         | 1.34%   |
| 0x406e3    | 5         | 1.34%   |
| 0x406c3    | 5         | 1.34%   |
| 0x306d4    | 5         | 1.34%   |
| 0x806ea    | 4         | 1.07%   |
| 0x6fd      | 4         | 1.07%   |
| 0x506e3    | 4         | 1.07%   |
| 0x30678    | 4         | 1.07%   |
| 0x08701021 | 4         | 1.07%   |
| 0x06006705 | 4         | 1.07%   |
| 0x806c1    | 3         | 0.8%    |
| 0x706e5    | 3         | 0.8%    |
| 0x706a1    | 3         | 0.8%    |
| 0x0a50000d | 3         | 0.8%    |
| 0x0a50000c | 3         | 0.8%    |
| 0x06001119 | 3         | 0.8%    |
| 0x06000852 | 3         | 0.8%    |
| 0xa0655    | 2         | 0.54%   |
| 0xa0653    | 2         | 0.54%   |
| 0x906eb    | 2         | 0.54%   |
| 0x806eb    | 2         | 0.54%   |
| 0x206d7    | 2         | 0.54%   |
| 0x10676    | 2         | 0.54%   |
| 0x08600104 | 2         | 0.54%   |
| 0x0810100b | 2         | 0.54%   |
| 0x0800820d | 2         | 0.54%   |
| 0x08001138 | 2         | 0.54%   |
| 0x07030105 | 2         | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 42        | 11.8%   |
| Haswell           | 25        | 7.02%   |
| Silvermont        | 24        | 6.74%   |
| SandyBridge       | 24        | 6.74%   |
| IvyBridge         | 24        | 6.74%   |
| Goldmont          | 20        | 5.62%   |
| Unknown           | 17        | 4.78%   |
| Skylake           | 16        | 4.49%   |
| Zen 2             | 13        | 3.65%   |
| K10               | 12        | 3.37%   |
| Zen+              | 11        | 3.09%   |
| Zen 3             | 10        | 2.81%   |
| Core              | 10        | 2.81%   |
| Westmere          | 9         | 2.53%   |
| Penryn            | 9         | 2.53%   |
| Excavator         | 9         | 2.53%   |
| CometLake         | 9         | 2.53%   |
| Piledriver        | 8         | 2.25%   |
| Broadwell         | 8         | 2.25%   |
| Zen               | 6         | 1.69%   |
| TigerLake         | 6         | 1.69%   |
| Puma              | 6         | 1.69%   |
| Goldmont plus     | 6         | 1.69%   |
| IceLake           | 5         | 1.4%    |
| Steamroller       | 4         | 1.12%   |
| Bobcat            | 4         | 1.12%   |
| Alderlake Hybrid  | 4         | 1.12%   |
| Tremont           | 3         | 0.84%   |
| Jaguar            | 3         | 0.84%   |
| NetBurst          | 2         | 0.56%   |
| K8 Hammer         | 2         | 0.56%   |
| Bonnell           | 2         | 0.56%   |
| Nehalem           | 1         | 0.28%   |
| Meteorlake Hybrid | 1         | 0.28%   |
| K10 Llano         | 1         | 0.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 221       | 55.81%  |
| AMD                              | 96        | 24.24%  |
| Nvidia                           | 78        | 19.7%   |
| Silicon Integrated Systems [SiS] | 1         | 0.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 500                                                                    | 20        | 4.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 18        | 4.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 4.16%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11        | 2.69%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 2.44%   |
| Intel HD Graphics 620                                                                    | 8         | 1.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 1.96%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 1.96%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 8         | 1.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 1.71%   |
| Intel HD Graphics 5500                                                                   | 7         | 1.71%   |
| Intel HD Graphics 530                                                                    | 7         | 1.71%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 1.71%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 1.71%   |
| Intel UHD Graphics 620                                                                   | 6         | 1.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.47%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 1.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 1.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.22%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.22%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.22%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 1.22%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 5         | 1.22%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 0.98%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 0.98%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 0.98%   |
| Intel JasperLake [UHD Graphics]                                                          | 4         | 0.98%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 0.98%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 0.98%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 0.98%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4         | 0.98%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 0.98%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.73%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 3         | 0.73%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 3         | 0.73%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 0.73%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 3         | 0.73%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 0.73%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 187       | 52.38%  |
| 1 x AMD        | 75        | 21.01%  |
| 1 x Nvidia     | 49        | 13.73%  |
| Intel + Nvidia | 21        | 5.88%   |
| Intel + AMD    | 8         | 2.24%   |
| AMD + Nvidia   | 8         | 2.24%   |
| 2 x AMD        | 5         | 1.4%    |
| Other          | 3         | 0.84%   |
| 1 x SiS        | 1         | 0.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 307       | 85.04%  |
| Proprietary | 38        | 10.53%  |
| Unknown     | 16        | 4.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 233       | 63.49%  |
| 0.01-0.5   | 38        | 10.35%  |
| 1.01-2.0   | 31        | 8.45%   |
| 0.51-1.0   | 26        | 7.08%   |
| 3.01-4.0   | 21        | 5.72%   |
| 7.01-8.0   | 7         | 1.91%   |
| 5.01-6.0   | 7         | 1.91%   |
| 8.01-16.0  | 3         | 0.82%   |
| 2.01-3.0   | 1         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 46        | 12.53%  |
| BOE                     | 37        | 10.08%  |
| LG Display              | 36        | 9.81%   |
| Chimei Innolux          | 35        | 9.54%   |
| AU Optronics            | 33        | 8.99%   |
| ViewSonic               | 25        | 6.81%   |
| AOC                     | 23        | 6.27%   |
| KTC                     | 11        | 3%      |
| Goldstar                | 11        | 3%      |
| KDC                     | 8         | 2.18%   |
| InfoVision              | 8         | 2.18%   |
| Hewlett-Packard         | 8         | 2.18%   |
| Acer                    | 8         | 2.18%   |
| PANDA                   | 7         | 1.91%   |
| Lenovo                  | 7         | 1.91%   |
| Dell                    | 6         | 1.63%   |
| Unknown                 | 5         | 1.36%   |
| Chi Mei Optoelectronics | 5         | 1.36%   |
| Sharp                   | 4         | 1.09%   |
| JRY                     | 3         | 0.82%   |
| Ancor Communications    | 3         | 0.82%   |
| Valve                   | 2         | 0.54%   |
| Sony                    | 2         | 0.54%   |
| Philips                 | 2         | 0.54%   |
| LG Philips              | 2         | 0.54%   |
| HSI                     | 2         | 0.54%   |
| HKC                     | 2         | 0.54%   |
| Hitachi                 | 2         | 0.54%   |
| Apple                   | 2         | 0.54%   |
| TXD                     | 1         | 0.27%   |
| Toshiba                 | 1         | 0.27%   |
| TopView                 | 1         | 0.27%   |
| TMX                     | 1         | 0.27%   |
| Sun                     | 1         | 0.27%   |
| RIS                     | 1         | 0.27%   |
| Quanta Display          | 1         | 0.27%   |
| Panasonic               | 1         | 0.27%   |
| MYS                     | 1         | 0.27%   |
| Mi                      | 1         | 0.27%   |
| LG Electronics          | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch            | 6         | 1.59%   |
| KDC LCD Monitor KDC05F1 1366x768 344x193mm 15.5-inch                     | 6         | 1.59%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch             | 6         | 1.59%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch        | 4         | 1.06%   |
| KTC 23L13-H-AN KTC2302 1920x1080 510x287mm 23.0-inch                     | 4         | 1.06%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 4         | 1.06%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                           | 4         | 1.06%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 3         | 0.79%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 3         | 0.79%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.79%   |
| Lenovo LEN-A3/V1-E LEN0017 1440x900 420x270mm 19.7-inch                  | 3         | 0.79%   |
| JRY VIZTA JRY2700 1920x1080 598x336mm 27.0-inch                          | 3         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 0.79%   |
| AU Optronics LCD Monitor AUOA49A 1920x1200 301x188mm 14.0-inch           | 3         | 0.79%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.79%   |
| ViewSonic VA2405-FHD VSCA939 1920x1080 527x296mm 23.8-inch               | 2         | 0.53%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 2         | 0.53%   |
| Unknown MS306 0030 1920x1080 708x398mm 32.0-inch                         | 2         | 0.53%   |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch                  | 2         | 0.53%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch      | 2         | 0.53%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 480x270mm 21.7-inch        | 2         | 0.53%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch        | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch     | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch     | 2         | 0.53%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 2         | 0.53%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch              | 2         | 0.53%   |
| LG Display LCD Monitor LGD0396 1600x900 382x215mm 17.3-inch              | 2         | 0.53%   |
| Lenovo LEN C32q-20 LEN65F8 2560x1440 700x390mm 31.5-inch                 | 2         | 0.53%   |
| KTC W9023S5 KTC1852 1360x768 410x230mm 18.5-inch                         | 2         | 0.53%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                     | 2         | 0.53%   |
| HSI LED-TV HSI0001 1920x1200 708x398mm 32.0-inch                         | 2         | 0.53%   |
| HKC Monitor HKC1850 1366x768 409x230mm 18.5-inch                         | 2         | 0.53%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                         | 2         | 0.53%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                        | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch          | 2         | 0.53%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.53%   |
| BOE LCD Monitor BOE0A56 1920x1080 344x194mm 15.5-inch                    | 2         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 119       | 34.69%  |
| 1920x1080 (FHD)    | 113       | 32.94%  |
| 1600x900 (HD+)     | 18        | 5.25%   |
| 3840x2160 (4K)     | 12        | 3.5%    |
| 1920x1200 (WUXGA)  | 12        | 3.5%    |
| 1440x900 (WXGA+)   | 11        | 3.21%   |
| 2560x1440 (QHD)    | 8         | 2.33%   |
| 1280x800 (WXGA)    | 6         | 1.75%   |
| 1280x1024 (SXGA)   | 6         | 1.75%   |
| 1360x768           | 5         | 1.46%   |
| Unknown            | 5         | 1.46%   |
| 1680x1050 (WSXGA+) | 4         | 1.17%   |
| 2560x1600          | 3         | 0.87%   |
| 800x1280           | 2         | 0.58%   |
| 2960x900           | 2         | 0.58%   |
| 2288x1287          | 2         | 0.58%   |
| 2160x1440          | 2         | 0.58%   |
| 1280x720 (HD)      | 2         | 0.58%   |
| 3600x1080          | 1         | 0.29%   |
| 3440x1440          | 1         | 0.29%   |
| 3200x1800 (QHD+)   | 1         | 0.29%   |
| 2944x1080          | 1         | 0.29%   |
| 2880x1800          | 1         | 0.29%   |
| 2736x1824          | 1         | 0.29%   |
| 2560x1080          | 1         | 0.29%   |
| 1920x540           | 1         | 0.29%   |
| 1680x945           | 1         | 0.29%   |
| 1280x768           | 1         | 0.29%   |
| 1024x600           | 1         | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 106       | 28.88%  |
| 14      | 44        | 11.99%  |
| 13      | 32        | 8.72%   |
| 21      | 25        | 6.81%   |
| 23      | 24        | 6.54%   |
| 18      | 20        | 5.45%   |
| 24      | 15        | 4.09%   |
| 17      | 14        | 3.81%   |
| 11      | 11        | 3%      |
| 19      | 10        | 2.72%   |
| Unknown | 10        | 2.72%   |
| 27      | 8         | 2.18%   |
| 20      | 6         | 1.63%   |
| 40      | 5         | 1.36%   |
| 12      | 5         | 1.36%   |
| 34      | 4         | 1.09%   |
| 31      | 4         | 1.09%   |
| 32      | 3         | 0.82%   |
| 84      | 2         | 0.54%   |
| 48      | 2         | 0.54%   |
| 44      | 2         | 0.54%   |
| 22      | 2         | 0.54%   |
| 10      | 2         | 0.54%   |
| 7       | 2         | 0.54%   |
| 142     | 1         | 0.27%   |
| 86      | 1         | 0.27%   |
| 57      | 1         | 0.27%   |
| 52      | 1         | 0.27%   |
| 47      | 1         | 0.27%   |
| 46      | 1         | 0.27%   |
| 29      | 1         | 0.27%   |
| 26      | 1         | 0.27%   |
| 16      | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 171       | 47.24%  |
| 401-500        | 59        | 16.3%   |
| 501-600        | 46        | 12.71%  |
| 201-300        | 28        | 7.73%   |
| 351-400        | 17        | 4.7%    |
| Unknown        | 10        | 2.76%   |
| 701-800        | 7         | 1.93%   |
| 1001-1500      | 7         | 1.93%   |
| 801-900        | 5         | 1.38%   |
| 601-700        | 5         | 1.38%   |
| 1501-2000      | 2         | 0.55%   |
| 901-1000       | 2         | 0.55%   |
| 1-100          | 2         | 0.55%   |
| More than 2000 | 1         | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 263       | 80.92%  |
| 16/10   | 32        | 9.85%   |
| Unknown | 10        | 3.08%   |
| 5/4     | 6         | 1.85%   |
| 3/2     | 4         | 1.23%   |
| 21/9    | 4         | 1.23%   |
| 0.67    | 2         | 0.62%   |
| 4/3     | 1         | 0.31%   |
| 1.96    | 1         | 0.31%   |
| 1.00    | 1         | 0.31%   |
| 0.56    | 1         | 0.31%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 105       | 28.93%  |
| 81-90          | 68        | 18.73%  |
| 201-250        | 52        | 14.33%  |
| 151-200        | 27        | 7.44%   |
| 141-150        | 20        | 5.51%   |
| 51-60          | 11        | 3.03%   |
| 351-500        | 11        | 3.03%   |
| 501-1000       | 10        | 2.75%   |
| Unknown        | 10        | 2.75%   |
| 71-80          | 9         | 2.48%   |
| 301-350        | 9         | 2.48%   |
| 121-130        | 9         | 2.48%   |
| More than 1000 | 7         | 1.93%   |
| 251-300        | 4         | 1.1%    |
| 61-70          | 3         | 0.83%   |
| 131-140        | 3         | 0.83%   |
| 41-50          | 2         | 0.55%   |
| 1-40           | 2         | 0.55%   |
| 91-100         | 1         | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 130       | 36.52%  |
| 51-100        | 111       | 31.18%  |
| 121-160       | 68        | 19.1%   |
| 161-240       | 22        | 6.18%   |
| 1-50          | 11        | 3.09%   |
| Unknown       | 10        | 2.81%   |
| More than 240 | 4         | 1.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 288       | 78.9%   |
| 2     | 53        | 14.52%  |
| 0     | 18        | 4.93%   |
| 3     | 5         | 1.37%   |
| 4     | 1         | 0.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 186       | 36.76%  |
| Intel                            | 148       | 29.25%  |
| Qualcomm Atheros                 | 57        | 11.26%  |
| Broadcom                         | 28        | 5.53%   |
| Ralink Technology                | 12        | 2.37%   |
| MediaTek                         | 12        | 2.37%   |
| TP-Link                          | 10        | 1.98%   |
| Broadcom Limited                 | 7         | 1.38%   |
| Ralink                           | 6         | 1.19%   |
| Nvidia                           | 6         | 1.19%   |
| Samsung Electronics              | 5         | 0.99%   |
| Huawei Technologies              | 4         | 0.79%   |
| Xiaomi                           | 3         | 0.59%   |
| Qualcomm Technologies            | 3         | 0.59%   |
| Mercucys                         | 3         | 0.59%   |
| ASIX Electronics                 | 3         | 0.59%   |
| Qualcomm Atheros Communications  | 2         | 0.4%    |
| Marvell Technology Group         | 2         | 0.4%    |
| VIA Technologies                 | 1         | 0.2%    |
| Texas Instruments                | 1         | 0.2%    |
| T & A Mobile Phones              | 1         | 0.2%    |
| Silicon Integrated Systems [SiS] | 1         | 0.2%    |
| Sierra Wireless                  | 1         | 0.2%    |
| Qualcomm                         | 1         | 0.2%    |
| Motorola PCS                     | 1         | 0.2%    |
| Lenovo                           | 1         | 0.2%    |
| DisplayLink                      | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 119       | 20.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 32        | 5.48%   |
| Intel Wireless 3165                                                    | 28        | 4.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 14        | 2.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 12        | 2.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 11        | 1.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 11        | 1.88%   |
| Intel Wi-Fi 6 AX200                                                    | 10        | 1.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 9         | 1.54%   |
| Intel Wireless 7265                                                    | 9         | 1.54%   |
| Broadcom BCM43142 802.11b/g/n                                          | 8         | 1.37%   |
| Ralink MT7601U Wireless Adapter                                        | 7         | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 7         | 1.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 7         | 1.2%    |
| Intel Wireless 8260                                                    | 7         | 1.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 7         | 1.2%    |
| Realtek RTL8723DE Wireless Network Adapter                             | 6         | 1.03%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 6         | 1.03%   |
| Nvidia MCP61 Ethernet                                                  | 6         | 1.03%   |
| Intel Wireless 7260                                                    | 6         | 1.03%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5         | 0.86%   |
| Intel Ethernet Connection (7) I219-V                                   | 5         | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 5         | 0.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 5         | 0.86%   |
| TP-Link 802.11ac NIC                                                   | 4         | 0.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 4         | 0.68%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 4         | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 4         | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 4         | 0.68%   |
| Intel Wireless 8265 / 8275                                             | 4         | 0.68%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 0.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 4         | 0.68%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.51%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 3         | 0.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 0.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 3         | 0.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 3         | 0.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 0.51%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 3         | 0.51%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 3         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 113       | 39.24%  |
| Realtek Semiconductor           | 64        | 22.22%  |
| Qualcomm Atheros                | 40        | 13.89%  |
| Broadcom                        | 20        | 6.94%   |
| Ralink Technology               | 12        | 4.17%   |
| MediaTek                        | 11        | 3.82%   |
| TP-Link                         | 9         | 3.13%   |
| Ralink                          | 6         | 2.08%   |
| Qualcomm Technologies           | 3         | 1.04%   |
| Mercucys                        | 3         | 1.04%   |
| Broadcom Limited                | 3         | 1.04%   |
| Qualcomm Atheros Communications | 2         | 0.69%   |
| Sierra Wireless                 | 1         | 0.35%   |
| Marvell Technology Group        | 1         | 0.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                           | 28        | 9.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 12        | 4.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 11        | 3.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 11        | 3.81%   |
| Intel Wi-Fi 6 AX200                                           | 10        | 3.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 9         | 3.11%   |
| Intel Wireless 7265                                           | 9         | 3.11%   |
| Broadcom BCM43142 802.11b/g/n                                 | 8         | 2.77%   |
| Ralink MT7601U Wireless Adapter                               | 7         | 2.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 7         | 2.42%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 7         | 2.42%   |
| Intel Wireless 8260                                           | 7         | 2.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 7         | 2.42%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 6         | 2.08%   |
| Realtek RTL8188EE Wireless Network Adapter                    | 6         | 2.08%   |
| Intel Wireless 7260                                           | 6         | 2.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 5         | 1.73%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 5         | 1.73%   |
| TP-Link 802.11ac NIC                                          | 4         | 1.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 4         | 1.38%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 4         | 1.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 4         | 1.38%   |
| Intel Wireless 8265 / 8275                                    | 4         | 1.38%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 4         | 1.38%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 3         | 1.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 3         | 1.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 3         | 1.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 3         | 1.04%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                     | 3         | 1.04%   |
| Qualcomm QCNFA765 Wireless Network Adapter                    | 3         | 1.04%   |
| Mercucys 802.11n NIC                                          | 3         | 1.04%   |
| Intel Wi-Fi 6 AX201                                           | 3         | 1.04%   |
| Intel Comet Lake PCH CNVi WiFi                                | 3         | 1.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 3         | 1.04%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 2         | 0.69%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter      | 2         | 0.69%   |
| Realtek 802.11ac NIC                                          | 2         | 0.69%   |
| Ralink RT2870/RT3070 Wireless Adapter                         | 2         | 0.69%   |
| Qualcomm Atheros AR9271 802.11n                               | 2         | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 2         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 162       | 56.45%  |
| Intel                            | 62        | 21.6%   |
| Qualcomm Atheros                 | 20        | 6.97%   |
| Broadcom                         | 11        | 3.83%   |
| Nvidia                           | 6         | 2.09%   |
| Huawei Technologies              | 4         | 1.39%   |
| Broadcom Limited                 | 4         | 1.39%   |
| Xiaomi                           | 3         | 1.05%   |
| ASIX Electronics                 | 3         | 1.05%   |
| Samsung Electronics              | 2         | 0.7%    |
| VIA Technologies                 | 1         | 0.35%   |
| TP-Link                          | 1         | 0.35%   |
| T & A Mobile Phones              | 1         | 0.35%   |
| Silicon Integrated Systems [SiS] | 1         | 0.35%   |
| Qualcomm                         | 1         | 0.35%   |
| Motorola PCS                     | 1         | 0.35%   |
| MediaTek                         | 1         | 0.35%   |
| Marvell Technology Group         | 1         | 0.35%   |
| Lenovo                           | 1         | 0.35%   |
| DisplayLink                      | 1         | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 119       | 41.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 32        | 11.03%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 14        | 4.83%   |
| Nvidia MCP61 Ethernet                                                  | 6         | 2.07%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5         | 1.72%   |
| Intel Ethernet Connection (7) I219-V                                   | 5         | 1.72%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 4         | 1.38%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 1.38%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 1.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 1.03%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3         | 1.03%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 1.03%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 1.03%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 1.03%   |
| Huawei E353/E3131                                                      | 3         | 1.03%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 1.03%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.69%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 0.69%   |
| Intel PRO/100 VE Network Connection                                    | 2         | 0.69%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 0.69%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.69%   |
| Intel Ethernet Connection I217-V                                       | 2         | 0.69%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.69%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 0.69%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.69%   |
| Intel Ethernet Connection (13) I219-V                                  | 2         | 0.69%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 0.69%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                   | 2         | 0.69%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 2         | 0.69%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 0.69%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.34%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.34%   |
| T & A Mobile Phones TCL 30 Z                                           | 1         | 0.34%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.34%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R]     | 1         | 0.34%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.34%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 268       | 49.72%  |
| Ethernet | 266       | 49.35%  |
| Modem    | 5         | 0.93%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 227       | 64.31%  |
| Ethernet | 126       | 35.69%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 188       | 53.11%  |
| 2     | 153       | 43.22%  |
| 0     | 10        | 2.82%   |
| 3     | 3         | 0.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 222       | 60.99%  |
| Yes  | 142       | 39.01%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 99        | 48.06%  |
| Realtek Semiconductor           | 25        | 12.14%  |
| Qualcomm Atheros Communications | 17        | 8.25%   |
| IMC Networks                    | 17        | 8.25%   |
| Cambridge Silicon Radio         | 11        | 5.34%   |
| Toshiba                         | 7         | 3.4%    |
| Foxconn / Hon Hai               | 6         | 2.91%   |
| Broadcom                        | 6         | 2.91%   |
| Lite-On Technology              | 5         | 2.43%   |
| USI                             | 3         | 1.46%   |
| Ralink                          | 3         | 1.46%   |
| Apple                           | 3         | 1.46%   |
| TP-Link                         | 1         | 0.49%   |
| Ralink Technology               | 1         | 0.49%   |
| Foxconn International           | 1         | 0.49%   |
| Alps Electric                   | 1         | 0.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 56        | 27.18%  |
| Realtek  Bluetooth 4.2 Adapter                      | 12        | 5.83%   |
| Realtek Bluetooth Radio                             | 11        | 5.34%   |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 5.34%   |
| Intel AX201 Bluetooth                               | 11        | 5.34%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11        | 5.34%   |
| Intel AX200 Bluetooth                               | 10        | 4.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 9         | 4.37%   |
| IMC Networks Wireless_Device                        | 7         | 3.4%    |
| IMC Networks Bluetooth Radio                        | 6         | 2.91%   |
| Intel AX211 Bluetooth                               | 5         | 2.43%   |
| USI Bluetooth Device                                | 3         | 1.46%   |
| Toshiba Bluetooth Device                            | 3         | 1.46%   |
| Toshiba BCM43142A0                                  | 3         | 1.46%   |
| Ralink RT3290 Bluetooth                             | 3         | 1.46%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.46%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.46%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.46%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.97%   |
| Lite-On Bluetooth Device                            | 2         | 0.97%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.97%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.97%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.97%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 0.97%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.97%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 1         | 0.49%   |
| Toshiba Bluetooth Radio                             | 1         | 0.49%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.49%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.49%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.49%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.49%   |
| Intel AX210 Bluetooth                               | 1         | 0.49%   |
| IMC Networks Bluetooth Device                       | 1         | 0.49%   |
| IMC Networks Bluetooth                              | 1         | 0.49%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.49%   |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 0.49%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.49%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.49%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth         | 1         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 246       | 54.67%  |
| AMD                                          | 96        | 21.33%  |
| Nvidia                                       | 65        | 14.44%  |
| Logitech                                     | 9         | 2%      |
| C-Media Electronics                          | 6         | 1.33%   |
| VIA Technologies                             | 2         | 0.44%   |
| Texas Instruments                            | 2         | 0.44%   |
| Samson Technologies                          | 2         | 0.44%   |
| Razer USA                                    | 2         | 0.44%   |
| Kingston Technology                          | 2         | 0.44%   |
| Generalplus Technology                       | 2         | 0.44%   |
| Focusrite-Novation                           | 2         | 0.44%   |
| Creative Labs                                | 2         | 0.44%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.22%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.22%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.22%   |
| Rockwell International                       | 1         | 0.22%   |
| KTMicro                                      | 1         | 0.22%   |
| JMTek                                        | 1         | 0.22%   |
| HECATE G2 II GAMING HEAD                     | 1         | 0.22%   |
| GN Netcom                                    | 1         | 0.22%   |
| Elgato Systems                               | 1         | 0.22%   |
| DSEA A/S                                     | 1         | 0.22%   |
| Creative Technology                          | 1         | 0.22%   |
| ASUSTek Computer                             | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 31        | 5.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 24        | 4.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 23        | 4.14%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 22        | 3.96%   |
| AMD FCH Azalia Controller                                                                         | 21        | 3.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 20        | 3.6%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 16        | 2.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15        | 2.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 14        | 2.52%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 13        | 2.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 2.16%   |
| AMD Kabini HDMI/DP Audio                                                                          | 12        | 2.16%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 1.98%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 1.8%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 1.62%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 9         | 1.62%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 9         | 1.62%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 1.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 1.44%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 1.44%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 1.44%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 8         | 1.44%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 1.44%   |
| Nvidia High Definition Audio Controller                                                           | 7         | 1.26%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 1.26%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 7         | 1.26%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7         | 1.26%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 6         | 1.08%   |
| Nvidia MCP61 High Definition Audio                                                                | 6         | 1.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 1.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.08%   |
| AMD High Definition Audio Controller                                                              | 6         | 1.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6         | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 0.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 0.9%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 0.9%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 0.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 0.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 0.9%    |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 0.9%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 47        | 20.7%   |
| Kingston                     | 31        | 13.66%  |
| SK hynix                     | 22        | 9.69%   |
| Micron Technology            | 22        | 9.69%   |
| Unknown                      | 20        | 8.81%   |
| Crucial                      | 19        | 8.37%   |
| Ramaxel Technology           | 10        | 4.41%   |
| A-DATA Technology            | 8         | 3.52%   |
| Goldkey                      | 7         | 3.08%   |
| Hikvision                    | 6         | 2.64%   |
| Elpida                       | 5         | 2.2%    |
| Nanya Technology             | 4         | 1.76%   |
| Team                         | 3         | 1.32%   |
| Patriot                      | 3         | 1.32%   |
| Unknown (89F7)               | 2         | 0.88%   |
| Unknown (2C0B)               | 2         | 0.88%   |
| Corsair                      | 2         | 0.88%   |
| Avant                        | 2         | 0.88%   |
| Unknown                      | 2         | 0.88%   |
| Unknown (8AD6)               | 1         | 0.44%   |
| Unknown (0x5846)             | 1         | 0.44%   |
| Smart                        | 1         | 0.44%   |
| Patriot Memory (PDP Systems) | 1         | 0.44%   |
| Netac                        | 1         | 0.44%   |
| KLEVV                        | 1         | 0.44%   |
| Infineon                     | 1         | 0.44%   |
| GeIL                         | 1         | 0.44%   |
| ff                           | 1         | 0.44%   |
| 4ea5                         | 1         | 0.44%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Goldkey RAM GKH200SO25608-1600 2GB SODIMM DDR3 1600MT/s       | 4         | 1.68%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 3         | 1.26%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 3         | 1.26%   |
| Samsung RAM K3LK6K60BM-BGCP 8GB LPDDR5 6400MT/s               | 3         | 1.26%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s        | 3         | 1.26%   |
| Goldkey RAM GKH400SO25608-1600 4GB SODIMM DDR3 1600MT/s       | 3         | 1.26%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s         | 3         | 1.26%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                | 2         | 0.84%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                  | 2         | 0.84%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                   | 2         | 0.84%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                  | 2         | 0.84%   |
| Unknown (89F7) RAM Module 8GB DIMM DDR3 1600MT/s              | 2         | 0.84%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s     | 2         | 0.84%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                   | 2         | 0.84%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s         | 2         | 0.84%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s         | 2         | 0.84%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 2         | 0.84%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s       | 2         | 0.84%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s     | 2         | 0.84%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.84%   |
| Micron RAM 8JTF25664AZ-1G4M1 2GB DIMM DDR3 1333MT/s           | 2         | 0.84%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s          | 2         | 0.84%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s             | 2         | 0.84%   |
| Kingston RAM KF552C40-16 16GB DIMM DDR5 5200MT/s              | 2         | 0.84%   |
| Kingston RAM 9905700-101.A00G 16GB SODIMM DDR4 3200MT/s       | 2         | 0.84%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1333MT/s         | 2         | 0.84%   |
| Unknown                                                       | 2         | 0.84%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                     | 1         | 0.42%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                     | 1         | 0.42%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                          | 1         | 0.42%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                   | 1         | 0.42%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                   | 1         | 0.42%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                          | 1         | 0.42%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                  | 1         | 0.42%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                       | 1         | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                    | 1         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                | 1         | 0.42%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                       | 1         | 0.42%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                      | 1         | 0.42%   |
| Unknown RAM Module 16GB DIMM DDR4 2666MT/s                    | 1         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 75        | 41.44%  |
| DDR3    | 75        | 41.44%  |
| LPDDR4  | 6         | 3.31%   |
| DDR2    | 5         | 2.76%   |
| LPDDR5  | 4         | 2.21%   |
| LPDDR3  | 4         | 2.21%   |
| DDR5    | 4         | 2.21%   |
| SDRAM   | 3         | 1.66%   |
| Unknown | 3         | 1.66%   |
| DDR     | 2         | 1.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 98        | 54.75%  |
| DIMM         | 64        | 35.75%  |
| Row Of Chips | 12        | 6.7%    |
| Unknown      | 4         | 2.23%   |
| RIMM         | 1         | 0.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 70        | 31.96%  |
| 4096  | 60        | 27.4%   |
| 16384 | 41        | 18.72%  |
| 2048  | 32        | 14.61%  |
| 32768 | 9         | 4.11%   |
| 1024  | 4         | 1.83%   |
| 512   | 2         | 0.91%   |
| 256   | 1         | 0.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 54        | 26.87%  |
| 2667  | 28        | 13.93%  |
| 3200  | 24        | 11.94%  |
| 1333  | 17        | 8.46%   |
| 2400  | 12        | 5.97%   |
| 2133  | 10        | 4.98%   |
| 1334  | 7         | 3.48%   |
| 533   | 5         | 2.49%   |
| 3600  | 4         | 1.99%   |
| 6400  | 3         | 1.49%   |
| 3266  | 3         | 1.49%   |
| 3000  | 3         | 1.49%   |
| 1867  | 3         | 1.49%   |
| 5200  | 2         | 1%      |
| 4800  | 2         | 1%      |
| 4199  | 2         | 1%      |
| 3800  | 2         | 1%      |
| 3733  | 2         | 1%      |
| 3466  | 2         | 1%      |
| 2666  | 2         | 1%      |
| 1067  | 2         | 1%      |
| 7500  | 1         | 0.5%    |
| 4267  | 1         | 0.5%    |
| 4266  | 1         | 0.5%    |
| 3500  | 1         | 0.5%    |
| 3400  | 1         | 0.5%    |
| 2473  | 1         | 0.5%    |
| 1866  | 1         | 0.5%    |
| 1800  | 1         | 0.5%    |
| 1066  | 1         | 0.5%    |
| 667   | 1         | 0.5%    |
| 333   | 1         | 0.5%    |
| 266   | 1         | 0.5%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 28.57%  |
| Brother Industries  | 2         | 28.57%  |
| Xerox               | 1         | 14.29%  |
| Hewlett-Packard     | 1         | 14.29%  |
| Canon               | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Xerox Phaser 3040    | 1         | 12.5%   |
| Samsung M288x Series | 1         | 12.5%   |
| Samsung M2020 Series | 1         | 12.5%   |
| HP HP Laser 107w     | 1         | 12.5%   |
| Canon PIXMA MP250    | 1         | 12.5%   |
| Brother DCP-T500W    | 1         | 12.5%   |
| Brother DCP-T420W    | 1         | 12.5%   |
| Brother DCP-J152W    | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 2         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 53        | 23.56%  |
| Realtek Semiconductor                  | 18        | 8%      |
| Bison Electronics                      | 18        | 8%      |
| Cheng Uei Precision Industry (Foxlink) | 17        | 7.56%   |
| Sunplus Innovation Technology          | 16        | 7.11%   |
| Microdia                               | 15        | 6.67%   |
| Logitech                               | 11        | 4.89%   |
| Quanta                                 | 9         | 4%      |
| Suyin                                  | 8         | 3.56%   |
| IMC Networks                           | 8         | 3.56%   |
| Unknown                                | 6         | 2.67%   |
| Silicon Motion                         | 6         | 2.67%   |
| Sonix Technology                       | 5         | 2.22%   |
| Lite-On Technology                     | 5         | 2.22%   |
| Samsung Electronics                    | 4         | 1.78%   |
| Alcor Micro                            | 4         | 1.78%   |
| Syntek                                 | 3         | 1.33%   |
| Luxvisions Innotech Limited            | 3         | 1.33%   |
| Importek                               | 3         | 1.33%   |
| Apple                                  | 3         | 1.33%   |
| Acer                                   | 2         | 0.89%   |
| SunplusIT                              | 1         | 0.44%   |
| Sony                                   | 1         | 0.44%   |
| Primax Electronics                     | 1         | 0.44%   |
| Novatek Microelectronics               | 1         | 0.44%   |
| GEMBIRD                                | 1         | 0.44%   |
| DigiTech                               | 1         | 0.44%   |
| Aveo Technology                        | 1         | 0.44%   |
| A4Tech                                 | 1         | 0.44%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD camera                                              | 17        | 7.52%   |
| Chicony Integrated Camera                                      | 10        | 4.42%   |
| Bison Integrated Camera                                        | 9         | 3.98%   |
| Realtek Integrated_Webcam_HD                                   | 6         | 2.65%   |
| Chicony HP Truevision HD                                       | 6         | 2.65%   |
| Unknown USB Camera                                             | 5         | 2.21%   |
| Logitech Webcam C270                                           | 5         | 2.21%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 4         | 1.77%   |
| Microdia Integrated_Webcam_HD                                  | 4         | 1.77%   |
| Chicony TOSHIBA Web Camera - HD                                | 4         | 1.77%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 4         | 1.77%   |
| Sunplus Integrated_Webcam_HD                                   | 3         | 1.33%   |
| Sunplus HP X Camera                                            | 3         | 1.33%   |
| Sonix USB2.0 HD UVC WebCam                                     | 3         | 1.33%   |
| Realtek Lenovo EasyCamera                                      | 3         | 1.33%   |
| Microdia USB 2.0 Camera                                        | 3         | 1.33%   |
| Chicony HD WebCam                                              | 3         | 1.33%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 1.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 3         | 1.33%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 3         | 1.33%   |
| Bison HD Webcam                                                | 3         | 1.33%   |
| Syntek Integrated Camera                                       | 2         | 0.88%   |
| Suyin Asus Integrated Webcam                                   | 2         | 0.88%   |
| Sunplus HD WebCam                                              | 2         | 0.88%   |
| Silicon Motion WebCam SC-13HDL11939N                           | 2         | 0.88%   |
| Silicon Motion WebCam SC-0311139N                              | 2         | 0.88%   |
| Realtek Integrated Webcam HD                                   | 2         | 0.88%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 0.88%   |
| Quanta HD Webcam                                               | 2         | 0.88%   |
| Quanta ACER HD User Facing                                     | 2         | 0.88%   |
| Luxvisions Innotech Limited Integrated Camera                  | 2         | 0.88%   |
| Lite-On Integrated Camera                                      | 2         | 0.88%   |
| Lite-On HP Webcam                                              | 2         | 0.88%   |
| Importek TOSHIBA Web Camera                                    | 2         | 0.88%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 2         | 0.88%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 2         | 0.88%   |
| IMC Networks Integrated Camera                                 | 2         | 0.88%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 2         | 0.88%   |
| Chicony Lenovo EasyCamera                                      | 2         | 0.88%   |
| Chicony HP Webcam                                              | 2         | 0.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 38.46%  |
| Synaptics                  | 5         | 19.23%  |
| Shenzhen Goodix Technology | 4         | 15.38%  |
| Upek                       | 2         | 7.69%   |
| Elan Microelectronics      | 2         | 7.69%   |
| LighTuning Technology      | 1         | 3.85%   |
| Focal-systems.Corp         | 1         | 3.85%   |
| AuthenTec                  | 1         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                  | 4         | 15.38%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 3         | 11.54%  |
| Shenzhen Goodix Fingerprint Reader                          | 3         | 11.54%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 2         | 7.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor           | 1         | 3.85%   |
| Validity Sensors VFS5011 Fingerprint Reader                 | 1         | 3.85%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 1         | 3.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 3.85%   |
| Validity Sensors Swipe Fingerprint Sensor                   | 1         | 3.85%   |
| Validity Sensors Fingerprint scanner                        | 1         | 3.85%   |
| Synaptics UWP WBDI Device                                   | 1         | 3.85%   |
| Synaptics Metallica MIS Touch Fingerprint Reader            | 1         | 3.85%   |
| Shenzhen Goodix  FingerPrint Device                         | 1         | 3.85%   |
| LighTuning EgisTec Touch Fingerprint Sensor                 | 1         | 3.85%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                   | 1         | 3.85%   |
| Elan WBF Fingerprint Sensor                                 | 1         | 3.85%   |
| Elan ELAN:Fingerprint                                       | 1         | 3.85%   |
| AuthenTec Fingerprint Sensor                                | 1         | 3.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 40%     |
| Alcor Micro | 2         | 40%     |
| Lenovo      | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 2         | 40%     |
| Lenovo Integrated Smart Card Reader | 1         | 20%     |
| Broadcom 5880                       | 1         | 20%     |
| Broadcom 58200                      | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 284       | 78.02%  |
| 1     | 72        | 19.78%  |
| 2     | 5         | 1.37%   |
| 3     | 3         | 0.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 25        | 28.74%  |
| Graphics card            | 20        | 22.99%  |
| Net/wireless             | 17        | 19.54%  |
| Multimedia controller    | 6         | 6.9%    |
| Chipcard                 | 4         | 4.6%    |
| Sound                    | 3         | 3.45%   |
| Bluetooth                | 3         | 3.45%   |
| Unassigned class         | 2         | 2.3%    |
| Storage                  | 2         | 2.3%    |
| Camera                   | 2         | 2.3%    |
| Storage/ide              | 1         | 1.15%   |
| Modem                    | 1         | 1.15%   |
| Communication controller | 1         | 1.15%   |


Linux in Bosnia and Herzegovina - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Bosnia and Herzegovina.

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

Total: 139

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [4a8b2ebf8a](https://linux-hardware.org/?probe=4a8b2ebf8a) | Apr 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [5fb905227b](https://linux-hardware.org/?probe=5fb905227b) | Apr 25, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [bb2041a761](https://linux-hardware.org/?probe=bb2041a761) | Apr 11, 2023 |
| HP            | ZBook 15 G4                 | [816bb7a55c](https://linux-hardware.org/?probe=816bb7a55c) | Apr 06, 2023 |
| Dell          | Latitude 7280               | [e0fcb10ef5](https://linux-hardware.org/?probe=e0fcb10ef5) | Apr 04, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [71d058eb0e](https://linux-hardware.org/?probe=71d058eb0e) | Mar 24, 2023 |
| HP            | ZBook 15 G4                 | [ebd974c40f](https://linux-hardware.org/?probe=ebd974c40f) | Mar 23, 2023 |
| HP            | 250 G7 Notebook PC          | [149a0b40c6](https://linux-hardware.org/?probe=149a0b40c6) | Mar 09, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [59bddb27c4](https://linux-hardware.org/?probe=59bddb27c4) | Mar 08, 2023 |
| HP            | ZBook 15 G4                 | [0f1c657481](https://linux-hardware.org/?probe=0f1c657481) | Mar 07, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [bbbf4112e4](https://linux-hardware.org/?probe=bbbf4112e4) | Mar 06, 2023 |
| HP            | ZBook 15 G4                 | [94f5848c13](https://linux-hardware.org/?probe=94f5848c13) | Mar 05, 2023 |
| HP            | ZBook 15 G4                 | [fa70608ed8](https://linux-hardware.org/?probe=fa70608ed8) | Mar 05, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [68ea374074](https://linux-hardware.org/?probe=68ea374074) | Mar 02, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [9b4ed72eaa](https://linux-hardware.org/?probe=9b4ed72eaa) | Mar 02, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [cc8c299b5d](https://linux-hardware.org/?probe=cc8c299b5d) | Mar 01, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [2e22d32463](https://linux-hardware.org/?probe=2e22d32463) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [85bfcb35ff](https://linux-hardware.org/?probe=85bfcb35ff) | Jan 23, 2023 |
| HP            | ZBook 15 G4                 | [81ec9ba8b3](https://linux-hardware.org/?probe=81ec9ba8b3) | Jan 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [d6243ec239](https://linux-hardware.org/?probe=d6243ec239) | Jan 23, 2023 |
| HP            | ZBook 15 G4                 | [9816a244b2](https://linux-hardware.org/?probe=9816a244b2) | Jan 16, 2023 |
| HP            | ZBook 15 G4                 | [3325b8ab60](https://linux-hardware.org/?probe=3325b8ab60) | Jan 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [143bdba9bc](https://linux-hardware.org/?probe=143bdba9bc) | Jan 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [ea19c0ace0](https://linux-hardware.org/?probe=ea19c0ace0) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | [76f2ef98b9](https://linux-hardware.org/?probe=76f2ef98b9) | Jan 04, 2023 |
| HP            | ZBook 15 G4                 | [669d7e74a2](https://linux-hardware.org/?probe=669d7e74a2) | Dec 19, 2022 |
| HP            | ZBook 15 G4                 | [91391127d1](https://linux-hardware.org/?probe=91391127d1) | Dec 18, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [4825bcbe78](https://linux-hardware.org/?probe=4825bcbe78) | Nov 27, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [47d808147c](https://linux-hardware.org/?probe=47d808147c) | Nov 23, 2022 |
| HP            | ZBook 15 G4                 | [3378343bab](https://linux-hardware.org/?probe=3378343bab) | Nov 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [0cdd3b10fc](https://linux-hardware.org/?probe=0cdd3b10fc) | Nov 18, 2022 |
| HP            | ZBook 15 G4                 | [775987aacb](https://linux-hardware.org/?probe=775987aacb) | Nov 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [512acddb70](https://linux-hardware.org/?probe=512acddb70) | Oct 30, 2022 |
| ASUSTek       | X540NA                      | [73799d57b3](https://linux-hardware.org/?probe=73799d57b3) | Oct 22, 2022 |
| ASUSTek       | X540NA                      | [bef64e98af](https://linux-hardware.org/?probe=bef64e98af) | Oct 21, 2022 |
| HP            | ZBook Firefly 14 inch G8... | [b7a5ca0670](https://linux-hardware.org/?probe=b7a5ca0670) | Oct 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [03a74f0a7b](https://linux-hardware.org/?probe=03a74f0a7b) | Oct 06, 2022 |
| HP            | ProBook 650 G1              | [bdcb5090f0](https://linux-hardware.org/?probe=bdcb5090f0) | Sep 26, 2022 |
| HP            | ProBook 6560b               | [96637a94a6](https://linux-hardware.org/?probe=96637a94a6) | Sep 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [bbc3c68696](https://linux-hardware.org/?probe=bbc3c68696) | Sep 14, 2022 |
| Dell          | XPS 15 9520                 | [7311161548](https://linux-hardware.org/?probe=7311161548) | Aug 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [fc99c10d57](https://linux-hardware.org/?probe=fc99c10d57) | Jul 13, 2022 |
| Dell          | Latitude E6410              | [cde668d556](https://linux-hardware.org/?probe=cde668d556) | Jul 12, 2022 |
| Dell          | Latitude E6410              | [a15b38ef5e](https://linux-hardware.org/?probe=a15b38ef5e) | Jul 12, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [b7d2767b67](https://linux-hardware.org/?probe=b7d2767b67) | Jun 23, 2022 |
| HP            | EliteBook 2560p             | [cf8d972149](https://linux-hardware.org/?probe=cf8d972149) | Jun 09, 2022 |
| Lenovo        | ThinkPad X301 277418G       | [0d9a530751](https://linux-hardware.org/?probe=0d9a530751) | May 24, 2022 |
| Acer          | Aspire E5-575G              | [654d58c254](https://linux-hardware.org/?probe=654d58c254) | May 07, 2022 |
| Acer          | Aspire F5-573G              | [26ac9971a3](https://linux-hardware.org/?probe=26ac9971a3) | Apr 13, 2022 |
| Lenovo        | ThinkPad T420 4180WAP       | [1e90438c11](https://linux-hardware.org/?probe=1e90438c11) | Apr 06, 2022 |
| Lenovo        | ThinkPad T420 4180WAP       | [f72ea7fb49](https://linux-hardware.org/?probe=f72ea7fb49) | Apr 06, 2022 |
| Dell          | Inspiron 5323               | [0f8594072f](https://linux-hardware.org/?probe=0f8594072f) | Feb 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d606848435](https://linux-hardware.org/?probe=d606848435) | Feb 27, 2022 |
| Toshiba       | Satellite C850-1GF          | [9ace91eeb9](https://linux-hardware.org/?probe=9ace91eeb9) | Feb 24, 2022 |
| Lenovo        | ThinkPad T430 2349G2G       | [14f905c347](https://linux-hardware.org/?probe=14f905c347) | Feb 19, 2022 |
| HP            | 550                         | [7e286dd830](https://linux-hardware.org/?probe=7e286dd830) | Feb 08, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [b09926b5fc](https://linux-hardware.org/?probe=b09926b5fc) | Jan 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [de0a100d06](https://linux-hardware.org/?probe=de0a100d06) | Jan 24, 2022 |
| HP            | EliteBook 8470p             | [1a04f6b354](https://linux-hardware.org/?probe=1a04f6b354) | Dec 26, 2021 |
| Fujitsu Si... | AMILO Li 2727               | [531a29caeb](https://linux-hardware.org/?probe=531a29caeb) | Dec 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f6f5b0f374](https://linux-hardware.org/?probe=f6f5b0f374) | Dec 01, 2021 |
| HP            | EliteBook 840 G1            | [b99fd7100e](https://linux-hardware.org/?probe=b99fd7100e) | Nov 28, 2021 |
| Fujitsu Si... | AMILO Li 2727               | [a86286c5da](https://linux-hardware.org/?probe=a86286c5da) | Nov 24, 2021 |
| Acer          | Okinawa                     | [2953f32ed9](https://linux-hardware.org/?probe=2953f32ed9) | Nov 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [9f4e86b760](https://linux-hardware.org/?probe=9f4e86b760) | Nov 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [07d8d5b1ae](https://linux-hardware.org/?probe=07d8d5b1ae) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6c7411070d](https://linux-hardware.org/?probe=6c7411070d) | Nov 19, 2021 |
| HP            | ProBook 470 G0              | [e2c740a317](https://linux-hardware.org/?probe=e2c740a317) | Nov 01, 2021 |
| Acer          | AO725                       | [f6819a066a](https://linux-hardware.org/?probe=f6819a066a) | Oct 31, 2021 |
| ASUSTek       | X540SAA                     | [2ce3b8f43c](https://linux-hardware.org/?probe=2ce3b8f43c) | Oct 27, 2021 |
| Lenovo        | IdeaPad Y570 20091          | [5d292b28e6](https://linux-hardware.org/?probe=5d292b28e6) | Oct 23, 2021 |
| Dell          | G3 3590                     | [caaab11f09](https://linux-hardware.org/?probe=caaab11f09) | Sep 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [1f7bf82ef4](https://linux-hardware.org/?probe=1f7bf82ef4) | Aug 10, 2021 |
| eMachines     | eME728                      | [30f7a1ede8](https://linux-hardware.org/?probe=30f7a1ede8) | Jul 27, 2021 |
| eMachines     | eME728                      | [41f6735286](https://linux-hardware.org/?probe=41f6735286) | Jul 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [fb1170efa6](https://linux-hardware.org/?probe=fb1170efa6) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [19f5976aa3](https://linux-hardware.org/?probe=19f5976aa3) | Jul 25, 2021 |
| Dell          | Latitude E7470              | [09cc29de1a](https://linux-hardware.org/?probe=09cc29de1a) | Jun 27, 2021 |
| HP            | EliteBook 8560p             | [c425b0dc44](https://linux-hardware.org/?probe=c425b0dc44) | Jun 01, 2021 |
| HP            | 250 G7 Notebook PC          | [035b3cdc60](https://linux-hardware.org/?probe=035b3cdc60) | May 31, 2021 |
| HP            | 250 G7 Notebook PC          | [e9148788a7](https://linux-hardware.org/?probe=e9148788a7) | May 30, 2021 |
| Acer          | Aspire 8950G                | [7955f23581](https://linux-hardware.org/?probe=7955f23581) | May 18, 2021 |
| HP            | ProBook 4710s               | [7c743eff61](https://linux-hardware.org/?probe=7c743eff61) | May 17, 2021 |
| HP            | ProBook 4710s               | [e0c66c6a52](https://linux-hardware.org/?probe=e0c66c6a52) | May 16, 2021 |
| Dell          | System Inspiron N7110       | [57a865992b](https://linux-hardware.org/?probe=57a865992b) | May 10, 2021 |
| HP            | ProBook 470 G2              | [fc85d1a891](https://linux-hardware.org/?probe=fc85d1a891) | May 08, 2021 |
| HP            | EliteBook 8460p             | [dba745086d](https://linux-hardware.org/?probe=dba745086d) | Apr 09, 2021 |
| HP            | EliteBook 8460p             | [54a2c5f349](https://linux-hardware.org/?probe=54a2c5f349) | Apr 09, 2021 |
| HP            | EliteBook 850 G3            | [f4c0a5e9a8](https://linux-hardware.org/?probe=f4c0a5e9a8) | Mar 25, 2021 |
| Dell          | G3 3590                     | [3576fa9deb](https://linux-hardware.org/?probe=3576fa9deb) | Feb 26, 2021 |
| Dell          | G3 3590                     | [c5592b0bc0](https://linux-hardware.org/?probe=c5592b0bc0) | Feb 26, 2021 |
| Acer          | AO756                       | [d734ecb46e](https://linux-hardware.org/?probe=d734ecb46e) | Jan 05, 2021 |
| Acer          | AO756                       | [be84cd377c](https://linux-hardware.org/?probe=be84cd377c) | Jan 05, 2021 |
| HP            | EliteBook 8460p             | [4914bab0b2](https://linux-hardware.org/?probe=4914bab0b2) | Jan 03, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [1cfdffe4cb](https://linux-hardware.org/?probe=1cfdffe4cb) | Dec 22, 2020 |
| Acer          | Aspire 5349                 | [e52d1fe780](https://linux-hardware.org/?probe=e52d1fe780) | Dec 01, 2020 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | [3cd2e0b42b](https://linux-hardware.org/?probe=3cd2e0b42b) | Nov 29, 2020 |
| Dell          | Inspiron 3521               | [d5cb1091b6](https://linux-hardware.org/?probe=d5cb1091b6) | Nov 21, 2020 |
| Dell          | Inspiron 3521               | [092c6bbcaa](https://linux-hardware.org/?probe=092c6bbcaa) | Nov 17, 2020 |
| Dell          | Inspiron 3521               | [2fbaebc961](https://linux-hardware.org/?probe=2fbaebc961) | Nov 16, 2020 |
| Acer          | Aspire 8950G                | [47e8b425f8](https://linux-hardware.org/?probe=47e8b425f8) | Nov 15, 2020 |
| Dell          | Inspiron 3521               | [986307a038](https://linux-hardware.org/?probe=986307a038) | Nov 15, 2020 |
| Acer          | Aspire 8950G                | [bae73407d5](https://linux-hardware.org/?probe=bae73407d5) | Nov 11, 2020 |
| Dell          | XPS 15 9570                 | [78a6736f7b](https://linux-hardware.org/?probe=78a6736f7b) | Nov 07, 2020 |
| Dell          | XPS 15 9570                 | [61f58ab0e6](https://linux-hardware.org/?probe=61f58ab0e6) | Nov 07, 2020 |
| HP            | Laptop 15-rb0xx             | [aaa00c2c2f](https://linux-hardware.org/?probe=aaa00c2c2f) | Nov 05, 2020 |
| Acer          | Aspire 7741                 | [a87b79b8e8](https://linux-hardware.org/?probe=a87b79b8e8) | Oct 01, 2020 |
| Lenovo        | Legion 7 15IMHg05 81YU      | [e8a84ca3be](https://linux-hardware.org/?probe=e8a84ca3be) | Oct 01, 2020 |
| Unknown       | Unknown                     | [c24817ee80](https://linux-hardware.org/?probe=c24817ee80) | Sep 15, 2020 |
| ASUSTek       | X75VBP                      | [2556ede7e8](https://linux-hardware.org/?probe=2556ede7e8) | Aug 14, 2020 |
| Lenovo        | G505 20240                  | [828da8bdbe](https://linux-hardware.org/?probe=828da8bdbe) | Aug 10, 2020 |
| HP            | ENVY 6                      | [a703adc052](https://linux-hardware.org/?probe=a703adc052) | Aug 08, 2020 |
| HP            | ENVY 6                      | [d64f914478](https://linux-hardware.org/?probe=d64f914478) | Aug 08, 2020 |
| HP            | ENVY TS 15                  | [bd072980c8](https://linux-hardware.org/?probe=bd072980c8) | Jun 02, 2020 |
| NEC Comput... | VERSAP550 NN951700753       | [ccd46d5757](https://linux-hardware.org/?probe=ccd46d5757) | May 29, 2020 |
| HP            | EliteBook 8470p             | [05094356e1](https://linux-hardware.org/?probe=05094356e1) | May 22, 2020 |
| HP            | EliteBook 8470p             | [9f6782d583](https://linux-hardware.org/?probe=9f6782d583) | May 14, 2020 |
| HP            | EliteBook 8470p             | [a8fb846d8b](https://linux-hardware.org/?probe=a8fb846d8b) | May 14, 2020 |
| HP            | EliteBook 8470p             | [6935018ae2](https://linux-hardware.org/?probe=6935018ae2) | May 14, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [31f5dfadff](https://linux-hardware.org/?probe=31f5dfadff) | May 04, 2020 |
| HP            | Compaq CQ58                 | [82172cc7b5](https://linux-hardware.org/?probe=82172cc7b5) | Apr 21, 2020 |
| ASUSTek       | X550ZE                      | [c3165ccdcd](https://linux-hardware.org/?probe=c3165ccdcd) | Apr 21, 2020 |
| HP            | 255 G2                      | [2e24d05e40](https://linux-hardware.org/?probe=2e24d05e40) | Apr 19, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [6e83174540](https://linux-hardware.org/?probe=6e83174540) | Apr 18, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [878a9628b9](https://linux-hardware.org/?probe=878a9628b9) | Apr 18, 2020 |
| Acer          | Aspire 9300                 | [de8a03d251](https://linux-hardware.org/?probe=de8a03d251) | Mar 26, 2020 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [e8e644cb4c](https://linux-hardware.org/?probe=e8e644cb4c) | Mar 09, 2020 |
| ASUSTek       | X751MD                      | [cdb3c77ebd](https://linux-hardware.org/?probe=cdb3c77ebd) | Feb 07, 2020 |
| Dell          | Inspiron 3521               | [815e8a2b8e](https://linux-hardware.org/?probe=815e8a2b8e) | Jan 04, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [5dd5ad47e3](https://linux-hardware.org/?probe=5dd5ad47e3) | Sep 06, 2019 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [8bce9c814b](https://linux-hardware.org/?probe=8bce9c814b) | Sep 05, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1db130e5eb](https://linux-hardware.org/?probe=1db130e5eb) | Aug 30, 2019 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [761fad2410](https://linux-hardware.org/?probe=761fad2410) | Aug 06, 2019 |
| Sony          | VGN-BX41VN                  | [3a190d628a](https://linux-hardware.org/?probe=3a190d628a) | Dec 02, 2018 |
| Sony          | VGN-BX41VN                  | [7f3d5f5bf2](https://linux-hardware.org/?probe=7f3d5f5bf2) | Dec 02, 2018 |
| Acer          | Aspire A315-31              | [e67c4f6668](https://linux-hardware.org/?probe=e67c4f6668) | Nov 18, 2018 |
| Acer          | Aspire A315-31              | [a46cebd58a](https://linux-hardware.org/?probe=a46cebd58a) | Nov 18, 2018 |
| HP            | 250 G6 Notebook PC          | [e8386ee291](https://linux-hardware.org/?probe=e8386ee291) | Sep 22, 2018 |
| HP            | 250 G6 Notebook PC          | [fa8425dcca](https://linux-hardware.org/?probe=fa8425dcca) | Aug 12, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 14        | 15.38%  |
| Pop!_OS 21.04       | 6         | 6.59%   |
| Ubuntu 22.04        | 5         | 5.49%   |
| Ubuntu 18.04        | 4         | 4.4%    |
| Linux Mint 20.2     | 4         | 4.4%    |
| Zorin 16            | 3         | 3.3%    |
| Manjaro             | 3         | 3.3%    |
| Ubuntu 20.10        | 2         | 2.2%    |
| Ubuntu 19.04        | 2         | 2.2%    |
| Pop!_OS 20.04       | 2         | 2.2%    |
| OpenMandriva 4.3    | 2         | 2.2%    |
| Lubuntu 19.10       | 2         | 2.2%    |
| Linux Mint 19.3     | 2         | 2.2%    |
| Kubuntu 22.04       | 2         | 2.2%    |
| Fedora 37           | 2         | 2.2%    |
| ArcoLinux Rolling   | 2         | 2.2%    |
| Arch Rolling        | 2         | 2.2%    |
| Zorin 15            | 1         | 1.1%    |
| Xubuntu 20.04       | 1         | 1.1%    |
| Xubuntu 18.04       | 1         | 1.1%    |
| Xero Rolling        | 1         | 1.1%    |
| Ubuntu Budgie 21.10 | 1         | 1.1%    |
| Ubuntu 23.04        | 1         | 1.1%    |
| Ubuntu 22.10        | 1         | 1.1%    |
| Ubuntu 21.10        | 1         | 1.1%    |
| Ubuntu 21.04        | 1         | 1.1%    |
| Ubuntu 16.04        | 1         | 1.1%    |
| ROSA R10            | 1         | 1.1%    |
| PureOS 9.0          | 1         | 1.1%    |
| Pop!_OS 21.10       | 1         | 1.1%    |
| Pop!_OS 20.10       | 1         | 1.1%    |
| OpenMandriva 23.03  | 1         | 1.1%    |
| Manjaro 21.2.5      | 1         | 1.1%    |
| Manjaro 21.0.7      | 1         | 1.1%    |
| LMDE 5              | 1         | 1.1%    |
| Linux Mint 21.1     | 1         | 1.1%    |
| Linux Mint 21       | 1         | 1.1%    |
| Linux Mint 20       | 1         | 1.1%    |
| KDE neon 20.04      | 1         | 1.1%    |
| Fedora 36           | 1         | 1.1%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 29        | 33.33%  |
| Pop!_OS       | 10        | 11.49%  |
| Linux Mint    | 8         | 9.2%    |
| Manjaro       | 5         | 5.75%   |
| Zorin         | 4         | 4.6%    |
| Fedora        | 4         | 4.6%    |
| Endless       | 4         | 4.6%    |
| OpenMandriva  | 3         | 3.45%   |
| Arch          | 3         | 3.45%   |
| Xubuntu       | 2         | 2.3%    |
| Lubuntu       | 2         | 2.3%    |
| Kubuntu       | 2         | 2.3%    |
| Debian        | 2         | 2.3%    |
| ArcoLinux     | 2         | 2.3%    |
| Xero          | 1         | 1.15%   |
| Ubuntu Budgie | 1         | 1.15%   |
| ROSA          | 1         | 1.15%   |
| PureOS        | 1         | 1.15%   |
| LMDE          | 1         | 1.15%   |
| KDE neon      | 1         | 1.15%   |
| Elementary    | 1         | 1.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.3.0-46-generic        | 3         | 3.16%   |
| 5.3.0-28-generic        | 3         | 3.16%   |
| 5.15.0-48-generic       | 3         | 3.16%   |
| 5.4.0-89-generic        | 2         | 2.11%   |
| 5.4.0-52-generic        | 2         | 2.11%   |
| 5.16.7-desktop-1omv4003 | 2         | 2.11%   |
| 5.15.0-39-generic       | 2         | 2.11%   |
| 5.13.0-7620-generic     | 2         | 2.11%   |
| 5.13.0-7614-generic     | 2         | 2.11%   |
| 5.13.0-39-generic       | 2         | 2.11%   |
| 5.11.0-40-generic       | 2         | 2.11%   |
| 6.2.6-desktop-1omv2390  | 1         | 1.05%   |
| 6.2.0-20-generic        | 1         | 1.05%   |
| 6.1.26-1-lts            | 1         | 1.05%   |
| 6.0.8-arch1-1           | 1         | 1.05%   |
| 6.0.8-300.fc37.x86_64   | 1         | 1.05%   |
| 6.0.15-300.fc37.x86_64  | 1         | 1.05%   |
| 6.0.12-arch1-1          | 1         | 1.05%   |
| 5.9.0-3-amd64           | 1         | 1.05%   |
| 5.8.9-200.fc32.x86_64   | 1         | 1.05%   |
| 5.8.0-7630-generic      | 1         | 1.05%   |
| 5.8.0-53-generic        | 1         | 1.05%   |
| 5.8.0-49-generic        | 1         | 1.05%   |
| 5.8.0-44-generic        | 1         | 1.05%   |
| 5.8.0-34-generic        | 1         | 1.05%   |
| 5.8.0-26-generic        | 1         | 1.05%   |
| 5.7.0-1-librem5         | 1         | 1.05%   |
| 5.4.52-1-MANJARO        | 1         | 1.05%   |
| 5.4.33-3-MANJARO        | 1         | 1.05%   |
| 5.4.23-1-MANJARO        | 1         | 1.05%   |
| 5.4.0-90-generic        | 1         | 1.05%   |
| 5.4.0-80-generic        | 1         | 1.05%   |
| 5.4.0-7625-generic      | 1         | 1.05%   |
| 5.4.0-72-generic        | 1         | 1.05%   |
| 5.4.0-67-generic        | 1         | 1.05%   |
| 5.4.0-58-generic        | 1         | 1.05%   |
| 5.4.0-54-generic        | 1         | 1.05%   |
| 5.4.0-48-generic        | 1         | 1.05%   |
| 5.4.0-33-generic        | 1         | 1.05%   |
| 5.4.0-26-generic        | 1         | 1.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 14        | 14.89%  |
| 5.13.0  | 11        | 11.7%   |
| 5.15.0  | 9         | 9.57%   |
| 5.3.0   | 7         | 7.45%   |
| 5.11.0  | 7         | 7.45%   |
| 5.8.0   | 6         | 6.38%   |
| 4.15.0  | 4         | 4.26%   |
| 5.19.0  | 3         | 3.19%   |
| 5.0.0   | 3         | 3.19%   |
| 6.0.8   | 2         | 2.13%   |
| 5.16.7  | 2         | 2.13%   |
| 5.10.0  | 2         | 2.13%   |
| 6.2.6   | 1         | 1.06%   |
| 6.2.0   | 1         | 1.06%   |
| 6.1.26  | 1         | 1.06%   |
| 6.0.15  | 1         | 1.06%   |
| 6.0.12  | 1         | 1.06%   |
| 5.9.0   | 1         | 1.06%   |
| 5.8.9   | 1         | 1.06%   |
| 5.7.0   | 1         | 1.06%   |
| 5.4.52  | 1         | 1.06%   |
| 5.4.33  | 1         | 1.06%   |
| 5.4.23  | 1         | 1.06%   |
| 5.19.8  | 1         | 1.06%   |
| 5.16.14 | 1         | 1.06%   |
| 5.16.11 | 1         | 1.06%   |
| 5.15.94 | 1         | 1.06%   |
| 5.15.89 | 1         | 1.06%   |
| 5.15.23 | 1         | 1.06%   |
| 5.15.11 | 1         | 1.06%   |
| 5.13.9  | 1         | 1.06%   |
| 5.11.18 | 1         | 1.06%   |
| 5.10.42 | 1         | 1.06%   |
| 5.10.37 | 1         | 1.06%   |
| 4.9.60  | 1         | 1.06%   |
| 4.18.0  | 1         | 1.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 17        | 18.48%  |
| 5.15    | 12        | 13.04%  |
| 5.13    | 12        | 13.04%  |
| 5.11    | 8         | 8.7%    |
| 5.8     | 7         | 7.61%   |
| 5.3     | 7         | 7.61%   |
| 5.19    | 4         | 4.35%   |
| 5.16    | 4         | 4.35%   |
| 5.10    | 4         | 4.35%   |
| 4.15    | 4         | 4.35%   |
| 6.0     | 3         | 3.26%   |
| 5.0     | 3         | 3.26%   |
| 6.2     | 2         | 2.17%   |
| 6.1     | 1         | 1.09%   |
| 5.9     | 1         | 1.09%   |
| 5.7     | 1         | 1.09%   |
| 4.9     | 1         | 1.09%   |
| 4.18    | 1         | 1.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 78        | 95.12%  |
| i686    | 3         | 3.66%   |
| aarch64 | 1         | 1.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 49        | 57.65%  |
| XFCE       | 9         | 10.59%  |
| KDE5       | 9         | 10.59%  |
| Unknown    | 6         | 7.06%   |
| X-Cinnamon | 4         | 4.71%   |
| LXQt       | 2         | 2.35%   |
| Pantheon   | 1         | 1.18%   |
| MATE       | 1         | 1.18%   |
| KDE4       | 1         | 1.18%   |
| KDE        | 1         | 1.18%   |
| Budgie     | 1         | 1.18%   |
| bspwm      | 1         | 1.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 66        | 79.52%  |
| Wayland | 12        | 14.46%  |
| Unknown | 5         | 6.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 50        | 57.47%  |
| SDDM    | 11        | 12.64%  |
| GDM     | 11        | 12.64%  |
| LightDM | 7         | 8.05%   |
| GDM3    | 7         | 8.05%   |
| KDM     | 1         | 1.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 64        | 77.11%  |
| Unknown | 6         | 7.23%   |
| hr_HR   | 4         | 4.82%   |
| bs_BA   | 4         | 4.82%   |
| C       | 2         | 2.41%   |
| en_GB   | 1         | 1.2%    |
| en_AU   | 1         | 1.2%    |
| de_CH   | 1         | 1.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 50        | 60.24%  |
| EFI  | 33        | 39.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 71        | 85.54%  |
| Btrfs   | 6         | 7.23%   |
| Overlay | 3         | 3.61%   |
| Unknown | 3         | 3.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 57        | 67.06%  |
| GPT     | 22        | 25.88%  |
| MBR     | 6         | 7.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 78        | 95.12%  |
| Yes       | 4         | 4.88%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 66        | 80.49%  |
| Yes       | 16        | 19.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 26        | 31.71%  |
| Lenovo           | 17        | 20.73%  |
| ASUSTek Computer | 12        | 14.63%  |
| Dell             | 10        | 12.2%   |
| Acer             | 10        | 12.2%   |
| Toshiba          | 1         | 1.22%   |
| Sony             | 1         | 1.22%   |
| NEC Computers    | 1         | 1.22%   |
| HUAWEI           | 1         | 1.22%   |
| Fujitsu Siemens  | 1         | 1.22%   |
| eMachines        | 1         | 1.22%   |
| Unknown          | 1         | 1.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Lenovo Legion 5 Pro 16IAH7H 82RF                  | 2         | 2.44%   |
| Lenovo IdeaPad 330-15IKB 81DE                     | 2         | 2.44%   |
| HP EliteBook 8460p                                | 2         | 2.44%   |
| HP 250 G7 Notebook PC                             | 2         | 2.44%   |
| Dell G3 3590                                      | 2         | 2.44%   |
| ASUS VivoBook_ASUSLaptop X509DA_D509DA            | 2         | 2.44%   |
| Toshiba Satellite C850-1GF                        | 1         | 1.22%   |
| Sony VGN-BX41VN                                   | 1         | 1.22%   |
| NEC Computers VERSAP550 NN951700753               | 1         | 1.22%   |
| Lenovo ThinkPad X301 277418G                      | 1         | 1.22%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A7008AMZ          | 1         | 1.22%   |
| Lenovo ThinkPad T430 2349G2G                      | 1         | 1.22%   |
| Lenovo ThinkPad T420 4180WAP                      | 1         | 1.22%   |
| Lenovo ThinkPad T14s Gen 1 20UH0056SC             | 1         | 1.22%   |
| Lenovo ThinkPad S1 Yoga 20CD0038MZ                | 1         | 1.22%   |
| Lenovo ThinkPad E15 Gen 2 20TD003LSC              | 1         | 1.22%   |
| Lenovo Legion 7 15IMHg05 81YU                     | 1         | 1.22%   |
| Lenovo IdeaPad Y570 20091                         | 1         | 1.22%   |
| Lenovo IdeaPad L340-15IWL 81LG                    | 1         | 1.22%   |
| Lenovo IdeaPad 320-15IKB 81BG                     | 1         | 1.22%   |
| Lenovo IdeaPad 110S-11IBR 80WG                    | 1         | 1.22%   |
| Lenovo G505 20240                                 | 1         | 1.22%   |
| HUAWEI BOHK-WAX9X                                 | 1         | 1.22%   |
| HP ZBook Firefly 14 inch G8 Mobile Workstation PC | 1         | 1.22%   |
| HP ZBook 15 G4                                    | 1         | 1.22%   |
| HP ProBook 6560b                                  | 1         | 1.22%   |
| HP ProBook 650 G1                                 | 1         | 1.22%   |
| HP ProBook 4710s                                  | 1         | 1.22%   |
| HP ProBook 470 G2                                 | 1         | 1.22%   |
| HP ProBook 470 G0                                 | 1         | 1.22%   |
| HP Pavilion Gaming Laptop 15-dk2xxx               | 1         | 1.22%   |
| HP Laptop 15-rb0xx                                | 1         | 1.22%   |
| HP ENVY TS 15                                     | 1         | 1.22%   |
| HP ENVY 6                                         | 1         | 1.22%   |
| HP EliteBook 8560p                                | 1         | 1.22%   |
| HP EliteBook 850 G8 Notebook PC                   | 1         | 1.22%   |
| HP EliteBook 850 G3                               | 1         | 1.22%   |
| HP EliteBook 8470p                                | 1         | 1.22%   |
| HP EliteBook 840 G3                               | 1         | 1.22%   |
| HP EliteBook 840 G1                               | 1         | 1.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| HP EliteBook            | 9         | 10.98%  |
| Lenovo ThinkPad         | 7         | 8.54%   |
| Acer Aspire             | 7         | 8.54%   |
| Lenovo IdeaPad          | 6         | 7.32%   |
| HP ProBook              | 5         | 6.1%    |
| ASUS VivoBook           | 4         | 4.88%   |
| Lenovo Legion           | 3         | 3.66%   |
| HP 250                  | 3         | 3.66%   |
| Dell Latitude           | 3         | 3.66%   |
| HP ZBook                | 2         | 2.44%   |
| HP ENVY                 | 2         | 2.44%   |
| Dell XPS                | 2         | 2.44%   |
| Dell Inspiron           | 2         | 2.44%   |
| Dell G3                 | 2         | 2.44%   |
| Toshiba Satellite       | 1         | 1.22%   |
| Sony VGN-BX41VN         | 1         | 1.22%   |
| NEC Computers VERSAP550 | 1         | 1.22%   |
| Lenovo G505             | 1         | 1.22%   |
| HUAWEI BOHK-WAX9X       | 1         | 1.22%   |
| HP Pavilion             | 1         | 1.22%   |
| HP Laptop               | 1         | 1.22%   |
| HP Compaq               | 1         | 1.22%   |
| HP 550                  | 1         | 1.22%   |
| HP 255                  | 1         | 1.22%   |
| Fujitsu Siemens AMILO   | 1         | 1.22%   |
| eMachines eME728        | 1         | 1.22%   |
| Dell System             | 1         | 1.22%   |
| ASUS ZenBook            | 1         | 1.22%   |
| ASUS X75VBP             | 1         | 1.22%   |
| ASUS X751MD             | 1         | 1.22%   |
| ASUS X550ZE             | 1         | 1.22%   |
| ASUS X540SAA            | 1         | 1.22%   |
| ASUS X540NA             | 1         | 1.22%   |
| ASUS TUF                | 1         | 1.22%   |
| ASUS ROG                | 1         | 1.22%   |
| Acer Switch             | 1         | 1.22%   |
| Acer AO756              | 1         | 1.22%   |
| Acer AO725              | 1         | 1.22%   |
| Unknown                 | 1         | 1.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 11        | 13.41%  |
| 2016    | 8         | 9.76%   |
| 2012    | 8         | 9.76%   |
| 2019    | 7         | 8.54%   |
| 2018    | 7         | 8.54%   |
| 2013    | 7         | 8.54%   |
| 2017    | 6         | 7.32%   |
| 2020    | 5         | 6.1%    |
| 2014    | 5         | 6.1%    |
| 2022    | 3         | 3.66%   |
| 2021    | 3         | 3.66%   |
| 2010    | 3         | 3.66%   |
| 2009    | 2         | 2.44%   |
| 2007    | 2         | 2.44%   |
| 2015    | 1         | 1.22%   |
| 2008    | 1         | 1.22%   |
| 2006    | 1         | 1.22%   |
| 2005    | 1         | 1.22%   |
| Unknown | 1         | 1.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 82        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 78        | 93.98%  |
| Enabled  | 5         | 6.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 82        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 26        | 31.71%  |
| 3.01-4.0    | 17        | 20.73%  |
| 16.01-24.0  | 13        | 15.85%  |
| 1.01-2.0    | 9         | 10.98%  |
| 8.01-16.0   | 9         | 10.98%  |
| 32.01-64.0  | 3         | 3.66%   |
| 2.01-3.0    | 2         | 2.44%   |
| 64.01-256.0 | 2         | 2.44%   |
| 0.51-1.0    | 1         | 1.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 31        | 36.05%  |
| 2.01-3.0  | 24        | 27.91%  |
| 3.01-4.0  | 11        | 12.79%  |
| 4.01-8.0  | 8         | 9.3%    |
| 0.51-1.0  | 8         | 9.3%    |
| 8.01-16.0 | 3         | 3.49%   |
| 0.01-0.5  | 1         | 1.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 64        | 78.05%  |
| 2      | 18        | 21.95%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 48        | 58.54%  |
| Yes       | 34        | 41.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 80.72%  |
| No        | 16        | 19.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 95.12%  |
| No        | 4         | 4.88%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 73.49%  |
| No        | 22        | 26.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| Bosnia and Herzegovina | 82        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Sarajevo          | 29        | 34.12%  |
| Banja Luka        | 14        | 16.47%  |
| Tuzla             | 7         | 8.24%   |
| Zenica            | 3         | 3.53%   |
| Gracanica         | 3         | 3.53%   |
| Srebrenik         | 2         | 2.35%   |
| Maglaj            | 2         | 2.35%   |
| Banovici          | 2         | 2.35%   |
| Zivinice          | 1         | 1.18%   |
| Zepce             | 1         | 1.18%   |
| Velika KladuÅ¡a | 1         | 1.18%   |
| Trebinje          | 1         | 1.18%   |
| Teslic            | 1         | 1.18%   |
| Stjepan-Polje     | 1         | 1.18%   |
| Solina            | 1         | 1.18%   |
| Prijedor          | 1         | 1.18%   |
| Posusje           | 1         | 1.18%   |
| Pale              | 1         | 1.18%   |
| Orahovica Donja   | 1         | 1.18%   |
| Novi Travnik      | 1         | 1.18%   |
| Nevesinje         | 1         | 1.18%   |
| Mostar            | 1         | 1.18%   |
| Lukavica          | 1         | 1.18%   |
| Lukavac           | 1         | 1.18%   |
| Ljubuski          | 1         | 1.18%   |
| Kakanj            | 1         | 1.18%   |
| Ilidza            | 1         | 1.18%   |
| Grude             | 1         | 1.18%   |
| Gradacac          | 1         | 1.18%   |
| Doboj             | 1         | 1.18%   |
| Brcko             | 1         | 1.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 22     | 15.31%  |
| Kingston            | 12        | 16     | 12.24%  |
| Toshiba             | 11        | 11     | 11.22%  |
| SanDisk             | 9         | 11     | 9.18%   |
| WDC                 | 8         | 9      | 8.16%   |
| SK hynix            | 8         | 11     | 8.16%   |
| Hitachi             | 8         | 8      | 8.16%   |
| Seagate             | 7         | 10     | 7.14%   |
| Unknown             | 3         | 3      | 3.06%   |
| Intel               | 3         | 3      | 3.06%   |
| Micron Technology   | 2         | 6      | 2.04%   |
| A-DATA Technology   | 2         | 2      | 2.04%   |
| Vaseky              | 1         | 1      | 1.02%   |
| Team                | 1         | 1      | 1.02%   |
| Patriot             | 1         | 1      | 1.02%   |
| OCZ                 | 1         | 2      | 1.02%   |
| LITEON              | 1         | 1      | 1.02%   |
| KIOXIA              | 1         | 1      | 1.02%   |
| Intenso             | 1         | 1      | 1.02%   |
| HGST                | 1         | 1      | 1.02%   |
| GOODRAM             | 1         | 1      | 1.02%   |
| Crucial             | 1         | 1      | 1.02%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                 | 5         | 4.9%    |
| SK hynix NVMe SSD Drive 512GB          | 3         | 2.94%   |
| Kingston SA400S37240G 240GB SSD        | 3         | 2.94%   |
| Unknown MMC Card  32GB                 | 2         | 1.96%   |
| SanDisk NVMe SSD Drive 256GB           | 2         | 1.96%   |
| Kingston SHFS37A240G 240GB SSD         | 2         | 1.96%   |
| Kingston SHFS37A120G 120GB SSD         | 2         | 1.96%   |
| WDC WDS240G1G0A-00SS50 240GB SSD       | 1         | 0.98%   |
| WDC WD7500BPVT-75HXZT3 752GB           | 1         | 0.98%   |
| WDC WD7500BPVT-24HXZT3 752GB           | 1         | 0.98%   |
| WDC WD5000LPVT-75G33T0 500GB           | 1         | 0.98%   |
| WDC WD5000BEKT-22KA9T0 500GB           | 1         | 0.98%   |
| WDC WD1600BEVT-22ZCT0 160GB            | 1         | 0.98%   |
| WDC WD10SPZX-60Z10T0 1TB               | 1         | 0.98%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB   | 1         | 0.98%   |
| Vaseky V800/128G 128GB                 | 1         | 0.98%   |
| Unknown SD/MMC/MS PRO 249GB            | 1         | 0.98%   |
| Toshiba MQ04ABF100 1TB                 | 1         | 0.98%   |
| Toshiba MQ01ABF050 500GB               | 1         | 0.98%   |
| Toshiba MK3263GSX 320GB                | 1         | 0.98%   |
| Toshiba MK3261GSYN 320GB               | 1         | 0.98%   |
| Toshiba MK3259GSXP 320GB               | 1         | 0.98%   |
| Toshiba KXG60ZNV512G 512GB             | 1         | 0.98%   |
| Team T253X1120G 120GB SSD              | 1         | 0.98%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB | 1         | 0.98%   |
| SK hynix SC311 SATA 256GB SSD          | 1         | 0.98%   |
| SK hynix SC300 M.2 2280 256GB SSD      | 1         | 0.98%   |
| SK hynix PC801 NVMe 1TB                | 1         | 0.98%   |
| SK hynix HFM001TD3JX013N 1024GB        | 1         | 0.98%   |
| SK hynix BC501 NVMe 512GB              | 1         | 0.98%   |
| Seagate ST9120817AS 120GB              | 1         | 0.98%   |
| Seagate ST500LT012-9WS142 500GB        | 1         | 0.98%   |
| Seagate ST500LM030-1RK17D 500GB        | 1         | 0.98%   |
| Seagate ST500LM000-1EJ162 500GB        | 1         | 0.98%   |
| Seagate ST2000LM007-1R8174 2TB         | 1         | 0.98%   |
| Seagate ST1000LM035-1RK172 970GB       | 1         | 0.98%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 1         | 0.98%   |
| SanDisk SSD PLUS 120GB                 | 1         | 0.98%   |
| SanDisk SD9SB8W256G1002 256GB SSD      | 1         | 0.98%   |
| SanDisk SD8SBAT128G1002 128GB SSD      | 1         | 0.98%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 10        | 10     | 30.3%   |
| Hitachi | 8         | 8      | 24.24%  |
| Seagate | 7         | 10     | 21.21%  |
| WDC     | 6         | 7      | 18.18%  |
| Unknown | 1         | 1      | 3.03%   |
| HGST    | 1         | 1      | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 10        | 10     | 26.32%  |
| Samsung Electronics | 9         | 9      | 23.68%  |
| SanDisk             | 4         | 5      | 10.53%  |
| SK hynix            | 2         | 4      | 5.26%   |
| Intel               | 2         | 2      | 5.26%   |
| A-DATA Technology   | 2         | 2      | 5.26%   |
| WDC                 | 1         | 1      | 2.63%   |
| Vaseky              | 1         | 1      | 2.63%   |
| Team                | 1         | 1      | 2.63%   |
| Patriot             | 1         | 1      | 2.63%   |
| OCZ                 | 1         | 2      | 2.63%   |
| Micron Technology   | 1         | 1      | 2.63%   |
| LITEON              | 1         | 1      | 2.63%   |
| Intenso             | 1         | 1      | 2.63%   |
| GOODRAM             | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 37        | 42     | 38.54%  |
| HDD  | 33        | 37     | 34.38%  |
| NVMe | 23        | 41     | 23.96%  |
| MMC  | 3         | 3      | 3.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 59        | 78     | 68.6%   |
| NVMe | 23        | 41     | 26.74%  |
| MMC  | 3         | 3      | 3.49%   |
| SAS  | 1         | 1      | 1.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 53        | 64     | 79.1%   |
| 0.51-1.0   | 13        | 13     | 19.4%   |
| 1.01-2.0   | 1         | 2      | 1.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 30        | 35.71%  |
| 251-500        | 25        | 29.76%  |
| 21-50          | 9         | 10.71%  |
| 501-1000       | 8         | 9.52%   |
| 51-100         | 5         | 5.95%   |
| 2001-3000      | 2         | 2.38%   |
| 1-20           | 2         | 2.38%   |
| Unknown        | 2         | 2.38%   |
| More than 3000 | 1         | 1.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 33        | 36.26%  |
| 21-50     | 29        | 31.87%  |
| 51-100    | 15        | 16.48%  |
| 101-250   | 6         | 6.59%   |
| 501-1000  | 3         | 3.3%    |
| 251-500   | 2         | 2.2%    |
| Unknown   | 2         | 2.2%    |
| 1001-2000 | 1         | 1.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 500GB | 1         | 1      | 25%     |
| Samsung Electronics MZVKW512HMJP-000H1 512GB                    | 1         | 1      | 25%     |
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD                   | 1         | 1      | 25%     |
| Crucial CT500P1SSD8 500GB                                       | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 66.67%  |
| Crucial             | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 2         | 3      | 66.67%  |
| SSD  | 1         | 1      | 33.33%  |

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
| Detected | 58        | 88     | 67.44%  |
| Works    | 25        | 31     | 29.07%  |
| Malfunc  | 3         | 4      | 3.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 64        | 65.98%  |
| AMD                          | 8         | 8.25%   |
| SK hynix                     | 6         | 6.19%   |
| Samsung Electronics          | 6         | 6.19%   |
| SanDisk                      | 5         | 5.15%   |
| Kingston Technology Company  | 2         | 2.06%   |
| Toshiba America Info Systems | 1         | 1.03%   |
| Nvidia                       | 1         | 1.03%   |
| Micron/Crucial Technology    | 1         | 1.03%   |
| Micron Technology            | 1         | 1.03%   |
| KIOXIA                       | 1         | 1.03%   |
| JMicron Technology           | 1         | 1.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 10.58%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 9.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 7.69%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 7.69%   |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 4.81%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 4.81%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 3.85%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 2.88%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 2.88%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 2         | 1.92%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 1.92%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.92%   |
| SanDisk PC SN520 NVMe SSD                                                        | 2         | 1.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.92%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.96%   |
| SK hynix Platinum P41 NVMe Solid State Drive 2TB                                 | 1         | 0.96%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.96%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 0.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.96%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 0.96%   |
| Nvidia MCP51 IDE                                                                 | 1         | 0.96%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1         | 0.96%   |
| Micron NVMe Storage Controller                                                   | 1         | 0.96%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 0.96%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.96%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 0.96%   |
| JMicron JMB363 SATA/IDE Controller                                               | 1         | 0.96%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 0.96%   |
| Intel SSD 600P Series                                                            | 1         | 0.96%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.96%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 60        | 60%     |
| NVMe | 23        | 23%     |
| RAID | 11        | 11%     |
| IDE  | 6         | 6%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 68        | 82.93%  |
| AMD    | 13        | 15.85%  |
| ARM    | 1         | 1.22%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 3.66%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 3         | 3.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 2.44%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 2.44%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 2.44%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 2.44%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 2.44%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 2.44%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 2.44%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 2         | 2.44%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 2.44%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 2.44%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 2.44%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2.44%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 2         | 2.44%   |
| Intel Pentium M processor 1.73GHz             | 1         | 1.22%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 1.22%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 1.22%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 1.22%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.22%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 1.22%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.22%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 1.22%   |
| Intel Core i7-4550U CPU @ 1.50GHz             | 1         | 1.22%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 1.22%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 1.22%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 1.22%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 1.22%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.22%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.22%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 1.22%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.22%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.22%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 1         | 1.22%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 1.22%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.22%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.22%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.22%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 1.22%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 1.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 21        | 25.61%  |
| Intel Core i5           | 19        | 23.17%  |
| Other                   | 8         | 9.76%   |
| Intel Celeron           | 7         | 8.54%   |
| Intel Core i3           | 5         | 6.1%    |
| Intel Core 2 Duo        | 4         | 4.88%   |
| AMD Ryzen 5             | 3         | 3.66%   |
| AMD E1                  | 3         | 3.66%   |
| Intel Pentium M         | 1         | 1.22%   |
| Intel Pentium Dual-Core | 1         | 1.22%   |
| Intel Pentium Dual      | 1         | 1.22%   |
| Intel Pentium           | 1         | 1.22%   |
| Intel Atom              | 1         | 1.22%   |
| AMD Turion 64 Mobile    | 1         | 1.22%   |
| AMD Ryzen 9             | 1         | 1.22%   |
| AMD Ryzen 7             | 1         | 1.22%   |
| AMD Ryzen 5 PRO         | 1         | 1.22%   |
| AMD E2                  | 1         | 1.22%   |
| AMD C-60                | 1         | 1.22%   |
| AMD A10                 | 1         | 1.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 44        | 53.66%  |
| 4      | 27        | 32.93%  |
| 6      | 4         | 4.88%   |
| 14     | 3         | 3.66%   |
| 8      | 2         | 2.44%   |
| 1      | 2         | 2.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 82        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 59        | 71.08%  |
| 1      | 24        | 28.92%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 78        | 95.12%  |
| Unknown        | 3         | 3.66%   |
| 32-bit         | 1         | 1.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 27.71%  |
| 0x206a7    | 8         | 9.64%   |
| 0x306a9    | 7         | 8.43%   |
| 0x406e3    | 4         | 4.82%   |
| 0x806ea    | 3         | 3.61%   |
| 0x806c1    | 3         | 3.61%   |
| 0x40651    | 3         | 3.61%   |
| 0x906a3    | 2         | 2.41%   |
| 0x806ec    | 2         | 2.41%   |
| 0x506c9    | 2         | 2.41%   |
| 0x306c3    | 2         | 2.41%   |
| 0x10676    | 2         | 2.41%   |
| 0x05000119 | 2         | 2.41%   |
| 0xa0652    | 1         | 1.2%    |
| 0x906ea    | 1         | 1.2%    |
| 0x906e9    | 1         | 1.2%    |
| 0x806eb    | 1         | 1.2%    |
| 0x806e9    | 1         | 1.2%    |
| 0x706e5    | 1         | 1.2%    |
| 0x6fd      | 1         | 1.2%    |
| 0x6fa      | 1         | 1.2%    |
| 0x6d8      | 1         | 1.2%    |
| 0x406c4    | 1         | 1.2%    |
| 0x406c3    | 1         | 1.2%    |
| 0x30678    | 1         | 1.2%    |
| 0x20655    | 1         | 1.2%    |
| 0x106e5    | 1         | 1.2%    |
| 0x1067a    | 1         | 1.2%    |
| 0x0a50000c | 1         | 1.2%    |
| 0x08600106 | 1         | 1.2%    |
| 0x08108109 | 1         | 1.2%    |
| 0x08108102 | 1         | 1.2%    |
| 0x0700010f | 1         | 1.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 15        | 18.29%  |
| SandyBridge      | 11        | 13.41%  |
| IvyBridge        | 8         | 9.76%   |
| Haswell          | 6         | 7.32%   |
| Zen+             | 4         | 4.88%   |
| TigerLake        | 4         | 4.88%   |
| Skylake          | 4         | 4.88%   |
| Silvermont       | 4         | 4.88%   |
| Penryn           | 3         | 3.66%   |
| Core             | 3         | 3.66%   |
| Jaguar           | 2         | 2.44%   |
| Goldmont         | 2         | 2.44%   |
| Bobcat           | 2         | 2.44%   |
| Alderlake Hybrid | 2         | 2.44%   |
| Unknown          | 2         | 2.44%   |
| Zen 3            | 1         | 1.22%   |
| Zen 2            | 1         | 1.22%   |
| Westmere         | 1         | 1.22%   |
| Steamroller      | 1         | 1.22%   |
| P6               | 1         | 1.22%   |
| Nehalem          | 1         | 1.22%   |
| K8 Hammer        | 1         | 1.22%   |
| IceLake          | 1         | 1.22%   |
| Excavator        | 1         | 1.22%   |
| CometLake        | 1         | 1.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 57        | 53.27%  |
| Nvidia | 26        | 24.3%   |
| AMD    | 24        | 22.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 7.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 6.36%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 3.64%   |
| Intel UHD Graphics 620                                                                   | 4         | 3.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 3.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 3.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 3.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 3.64%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 2.73%   |
| Nvidia GM108M [GeForce MX110]                                                            | 3         | 2.73%   |
| Intel HD Graphics 620                                                                    | 3         | 2.73%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 2.73%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 1.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.82%   |
| Intel HD Graphics 500                                                                    | 2         | 1.82%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 1.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.82%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 1.82%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.82%   |
| AMD Kabini [Radeon HD 8210]                                                              | 2         | 1.82%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                     | 1         | 0.91%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile]                                                 | 1         | 0.91%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.91%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.91%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.91%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 0.91%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.91%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 0.91%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.91%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 1         | 0.91%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.91%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.91%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.91%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 0.91%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.91%   |
| Nvidia GA104M [Geforce RTX 3070 Ti Laptop GPU]                                           | 1         | 0.91%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 0.91%   |
| Nvidia C51 [GeForce Go 6100]                                                             | 1         | 0.91%   |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                                | 1         | 0.91%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 32        | 38.55%  |
| Intel + Nvidia | 21        | 25.3%   |
| 1 x AMD        | 17        | 20.48%  |
| 1 x Nvidia     | 5         | 6.02%   |
| Intel + AMD    | 4         | 4.82%   |
| 2 x AMD        | 2         | 2.41%   |
| Other          | 1         | 1.2%    |
| AMD + Nvidia   | 1         | 1.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 64        | 77.11%  |
| Proprietary | 16        | 19.28%  |
| Unknown     | 3         | 3.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 55.81%  |
| 1.01-2.0   | 12        | 13.95%  |
| 0.01-0.5   | 9         | 10.47%  |
| 0.51-1.0   | 7         | 8.14%   |
| 3.01-4.0   | 5         | 5.81%   |
| 7.01-8.0   | 3         | 3.49%   |
| 5.01-6.0   | 2         | 2.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 19        | 22.09%  |
| AU Optronics            | 19        | 22.09%  |
| BOE                     | 13        | 15.12%  |
| Chimei Innolux          | 9         | 10.47%  |
| Samsung Electronics     | 6         | 6.98%   |
| AOC                     | 3         | 3.49%   |
| Sharp                   | 2         | 2.33%   |
| LG Philips              | 2         | 2.33%   |
| Dell                    | 2         | 2.33%   |
| Chi Mei Optoelectronics | 2         | 2.33%   |
| Philips                 | 1         | 1.16%   |
| PANDA                   | 1         | 1.16%   |
| NEC Computers           | 1         | 1.16%   |
| Mi                      | 1         | 1.16%   |
| LGD                     | 1         | 1.16%   |
| Lenovo                  | 1         | 1.16%   |
| InfoVision              | 1         | 1.16%   |
| Goldstar                | 1         | 1.16%   |
| CSO                     | 1         | 1.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 4         | 4.49%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch          | 3         | 3.37%   |
| LG Display LCD Monitor LGD05E4 1920x1080 344x194mm 15.5-inch         | 2         | 2.25%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch          | 2         | 2.25%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 2         | 2.25%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                | 2         | 2.25%   |
| AU Optronics LCD Monitor AUO35ED 1920x1080 344x193mm 15.5-inch       | 2         | 2.25%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch       | 2         | 2.25%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch              | 1         | 1.12%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch              | 1         | 1.12%   |
| Samsung Electronics SyncMaster SAM0579 1920x1080                     | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC3554 1600x900 382x215mm 17.3-inch | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch | 1         | 1.12%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 1         | 1.12%   |
| PANDA LCD Monitor NCP0058 1920x1080 344x194mm 15.5-inch              | 1         | 1.12%   |
| NEC Computers LCD1770NX NEC6664 1280x1024 338x270mm 17.0-inch        | 1         | 1.12%   |
| Mi Monitor XMI3446 3440x1440 797x334mm 34.0-inch                     | 1         | 1.12%   |
| Mi Monitor XMI3445 3440x1440 797x334mm 34.0-inch                     | 1         | 1.12%   |
| LGD LCD Monitor 1920x1080                                            | 1         | 1.12%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch          | 1         | 1.12%   |
| LG Philips LCD Monitor LPL1E01 1280x800 331x207mm 15.4-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch         | 1         | 1.12%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch         | 1         | 1.12%   |
| LG Display LCD Monitor LGD04B3 1920x1080 345x194mm 15.6-inch         | 1         | 1.12%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x174mm 14.0-inch         | 1         | 1.12%   |
| LG Display LCD Monitor LGD0414 1920x1080 276x156mm 12.5-inch         | 1         | 1.12%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD034C 1366x768 293x165mm 13.2-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD0257 1440x900 304x190mm 14.1-inch          | 1         | 1.12%   |
| Lenovo LCD Monitor LEN4074 1440x900 287x180mm 13.3-inch              | 1         | 1.12%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 1         | 1.12%   |
| Goldstar ULTRAGEAR GSM5BB1 1920x1080 527x296mm 23.8-inch             | 1         | 1.12%   |
| Dell S3422DWG DELD12C 3440x1440 797x334mm 34.0-inch                  | 1         | 1.12%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 37        | 44.58%  |
| 1366x768 (WXGA)  | 21        | 25.3%   |
| 1600x900 (HD+)   | 11        | 13.25%  |
| 1440x900 (WXGA+) | 3         | 3.61%   |
| 3440x1440        | 2         | 2.41%   |
| 2560x1600        | 2         | 2.41%   |
| 2560x1440 (QHD)  | 2         | 2.41%   |
| 1280x800 (WXGA)  | 2         | 2.41%   |
| 1280x1024 (SXGA) | 2         | 2.41%   |
| 3840x2160 (4K)   | 1         | 1.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 42        | 48.28%  |
| 17      | 10        | 11.49%  |
| 14      | 10        | 11.49%  |
| 13      | 7         | 8.05%   |
| 11      | 3         | 3.45%   |
| 34      | 2         | 2.3%    |
| 23      | 2         | 2.3%    |
| 16      | 2         | 2.3%    |
| 12      | 2         | 2.3%    |
| Unknown | 2         | 2.3%    |
| 33      | 1         | 1.15%   |
| 27      | 1         | 1.15%   |
| 24      | 1         | 1.15%   |
| 21      | 1         | 1.15%   |
| 18      | 1         | 1.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 59        | 68.6%   |
| 351-400     | 8         | 9.3%    |
| 201-300     | 8         | 9.3%    |
| 501-600     | 4         | 4.65%   |
| 701-800     | 3         | 3.49%   |
| 401-500     | 2         | 2.33%   |
| Unknown     | 2         | 2.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 68        | 85%     |
| 16/10   | 7         | 8.75%   |
| 5/4     | 2         | 2.5%    |
| 21/9    | 2         | 2.5%    |
| Unknown | 1         | 1.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 41        | 47.67%  |
| 81-90          | 14        | 16.28%  |
| 121-130        | 6         | 6.98%   |
| 71-80          | 4         | 4.65%   |
| 51-60          | 3         | 3.49%   |
| 351-500        | 3         | 3.49%   |
| 201-250        | 3         | 3.49%   |
| 141-150        | 2         | 2.33%   |
| 131-140        | 2         | 2.33%   |
| 111-120        | 2         | 2.33%   |
| Unknown        | 2         | 2.33%   |
| 61-70          | 1         | 1.16%   |
| 301-350        | 1         | 1.16%   |
| 151-200        | 1         | 1.16%   |
| 91-100         | 1         | 1.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 41        | 47.67%  |
| 101-120 | 27        | 31.4%   |
| 51-100  | 11        | 12.79%  |
| 161-240 | 5         | 5.81%   |
| Unknown | 2         | 2.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 71        | 84.52%  |
| 2     | 9         | 10.71%  |
| 0     | 3         | 3.57%   |
| 3     | 1         | 1.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 39        | 31.45%  |
| Intel                           | 35        | 28.23%  |
| Qualcomm Atheros                | 24        | 19.35%  |
| Broadcom                        | 9         | 7.26%   |
| Ralink                          | 3         | 2.42%   |
| Ralink Technology               | 2         | 1.61%   |
| Marvell Technology Group        | 2         | 1.61%   |
| Hewlett-Packard                 | 2         | 1.61%   |
| TP-Link                         | 1         | 0.81%   |
| Sierra Wireless                 | 1         | 0.81%   |
| Qualcomm Atheros Communications | 1         | 0.81%   |
| Nvidia                          | 1         | 0.81%   |
| MediaTek                        | 1         | 0.81%   |
| HTC (High Tech Computer)        | 1         | 0.81%   |
| D-Link                          | 1         | 0.81%   |
| Broadcom Limited                | 1         | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 26        | 16.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 8         | 5.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 5.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 4.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 4.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 3.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 2.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 1.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 1.92%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.92%   |
| Intel Wireless 8260                                                     | 3         | 1.92%   |
| Intel Wireless 7260                                                     | 3         | 1.92%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.92%   |
| Intel Ethernet Connection I219-LM                                       | 3         | 1.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 1.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 1.28%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.28%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.28%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.64%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.64%   |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                          | 1         | 0.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.64%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.64%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1         | 0.64%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.64%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.64%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.64%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 1         | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1         | 0.64%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 1         | 0.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.64%   |
| Nvidia MCP51 Ethernet Controller                                        | 1         | 0.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 38.55%  |
| Qualcomm Atheros                | 22        | 26.51%  |
| Realtek Semiconductor           | 12        | 14.46%  |
| Broadcom                        | 8         | 9.64%   |
| Ralink                          | 3         | 3.61%   |
| Ralink Technology               | 2         | 2.41%   |
| TP-Link                         | 1         | 1.2%    |
| Qualcomm Atheros Communications | 1         | 1.2%    |
| MediaTek                        | 1         | 1.2%    |
| D-Link                          | 1         | 1.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 9.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 8.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 7.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 4.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 3.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 3.61%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 3.61%   |
| Intel Wireless 8265 / 8275                                              | 3         | 3.61%   |
| Intel Wireless 8260                                                     | 3         | 3.61%   |
| Intel Wireless 7260                                                     | 3         | 3.61%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 3.61%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 3.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 3.61%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 2.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.41%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 2.41%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 1.2%    |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                          | 1         | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.2%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.2%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 1.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.2%    |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.2%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.2%    |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.2%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.2%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.2%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.2%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.2%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.2%    |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.2%    |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.2%    |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.2%    |
| D-Link GO-USB-N150 N Adapter                                            | 1         | 1.2%    |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.2%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 1.2%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 37        | 52.86%  |
| Intel                    | 19        | 27.14%  |
| Qualcomm Atheros         | 5         | 7.14%   |
| Marvell Technology Group | 2         | 2.86%   |
| Broadcom                 | 2         | 2.86%   |
| Sierra Wireless          | 1         | 1.43%   |
| Nvidia                   | 1         | 1.43%   |
| HTC (High Tech Computer) | 1         | 1.43%   |
| Hewlett-Packard          | 1         | 1.43%   |
| Broadcom Limited         | 1         | 1.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26        | 36.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 11.27%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 9.86%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 4.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.82%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 1.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.41%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.41%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 1.41%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.41%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.41%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.41%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.41%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.41%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.41%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.41%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.41%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.41%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 1.41%   |
| HTC (High Tech Computer) Desire HD (modem mode)                   | 1         | 1.41%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 1.41%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.41%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.41%   |
| Broadcom Limited NetLink BCM57781 Gigabit Ethernet PCIe           | 1         | 1.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 78        | 53.06%  |
| Ethernet | 67        | 45.58%  |
| Modem    | 2         | 1.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 69        | 81.18%  |
| Ethernet | 16        | 18.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 64        | 77.11%  |
| 1     | 16        | 19.28%  |
| 0     | 3         | 3.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 78        | 95.12%  |
| Yes  | 4         | 4.88%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 29.51%  |
| Qualcomm Atheros Communications | 10        | 16.39%  |
| IMC Networks                    | 7         | 11.48%  |
| Realtek Semiconductor           | 5         | 8.2%    |
| Broadcom                        | 5         | 8.2%    |
| Lite-On Technology              | 4         | 6.56%   |
| Ralink                          | 3         | 4.92%   |
| Hewlett-Packard                 | 2         | 3.28%   |
| Foxconn / Hon Hai               | 2         | 3.28%   |
| Toshiba                         | 1         | 1.64%   |
| Realtek                         | 1         | 1.64%   |
| Dell                            | 1         | 1.64%   |
| Cambridge Silicon Radio         | 1         | 1.64%   |
| Alps Electric                   | 1         | 1.64%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                  | 7         | 11.48%  |
| Intel Bluetooth wireless interface                  | 7         | 11.48%  |
| Intel AX201 Bluetooth                               | 4         | 6.56%   |
| IMC Networks Bluetooth Radio                        | 4         | 6.56%   |
| Realtek Bluetooth Radio                             | 3         | 4.92%   |
| Ralink RT3290 Bluetooth                             | 3         | 4.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 4.92%   |
| Intel Bluetooth Device                              | 3         | 4.92%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 3.28%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 3.28%   |
| IMC Networks Bluetooth Device                       | 2         | 3.28%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 3.28%   |
| Toshiba RT Bluetooth Radio                          | 1         | 1.64%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 1.64%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.64%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.64%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.64%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.64%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 1.64%   |
| Intel AX200 Bluetooth                               | 1         | 1.64%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.64%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.64%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 1.64%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.64%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.64%   |
| Broadcom HP Portable Valentine                      | 1         | 1.64%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.64%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.64%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.64%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 1.64%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 67        | 67%     |
| AMD                 | 18        | 18%     |
| Nvidia              | 11        | 11%     |
| Logitech            | 2         | 2%      |
| Texas Instruments   | 1         | 1%      |
| C-Media Electronics | 1         | 1%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 9.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 8.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 7.63%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 5.08%   |
| AMD FCH Azalia Controller                                                                         | 5         | 4.24%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 3.39%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 3.39%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 3.39%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 3.39%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 3.39%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.54%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 2.54%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2.54%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 2.54%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.69%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 1.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.69%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.69%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.69%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.69%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 1.69%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1         | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.85%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.85%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.85%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.85%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.85%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.85%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.85%   |
| Logitech H390 headset with microphone                                                             | 1         | 0.85%   |
| Logitech 960 Headset                                                                              | 1         | 0.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.85%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.85%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.85%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 12        | 30.77%  |
| Micron Technology   | 10        | 25.64%  |
| Samsung Electronics | 8         | 20.51%  |
| Kingston            | 4         | 10.26%  |
| Crucial             | 2         | 5.13%   |
| A-DATA Technology   | 2         | 5.13%   |
| Corsair             | 1         | 2.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 4.65%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 4.65%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s         | 2         | 4.65%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                  | 1         | 2.33%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2133MT/s               | 1         | 2.33%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 2.33%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 2.33%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 2.33%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s         | 1         | 2.33%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s         | 1         | 2.33%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s   | 1         | 2.33%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 1         | 2.33%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 2.33%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 2.33%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 2.33%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 2.33%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 2.33%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                | 1         | 2.33%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 1         | 2.33%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 2.33%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 1         | 2.33%   |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM DDR5 4800MT/s       | 1         | 2.33%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s        | 1         | 2.33%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 2.33%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 2.33%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 1         | 2.33%   |
| Micron RAM 8JTF51264HZ-1G6D 1 4GB SODIMM DDR3 1600MT/s         | 1         | 2.33%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s          | 1         | 2.33%   |
| Micron RAM 16KTF51264HZ-1G4M1 4GB SODIMM DDR3 1333MT/s         | 1         | 2.33%   |
| Micron RAM 16JSF25664HY-1G1D1 2GB SODIMM DDR3 1067MT/s         | 1         | 2.33%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s          | 1         | 2.33%   |
| Kingston RAM KKN2NM-MIE 4GB SODIMM DDR4 2667MT/s               | 1         | 2.33%   |
| Kingston RAM HP16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s          | 1         | 2.33%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s        | 1         | 2.33%   |
| Kingston RAM 99U5428-017.A00LF 8GB SODIMM DDR3 1600MT/s        | 1         | 2.33%   |
| Crucial RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s        | 1         | 2.33%   |
| Crucial RAM CT16G4SFD8266.M16FE 16GB SODIMM DDR4 2667MT/s      | 1         | 2.33%   |
| Corsair RAM CMSX4GX3M1A1600C9 4096MB SODIMM DDR3 1600MT/s      | 1         | 2.33%   |
| A-DATA RAM AO1P24HC8T1-BQXS 8GB SODIMM DDR4 2400MT/s           | 1         | 2.33%   |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s           | 1         | 2.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 16        | 47.06%  |
| DDR3   | 14        | 41.18%  |
| DDR5   | 2         | 5.88%   |
| LPDDR4 | 1         | 2.94%   |
| LPDDR3 | 1         | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 32        | 94.12%  |
| Row Of Chips | 2         | 5.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 16        | 44.44%  |
| 8192  | 13        | 36.11%  |
| 16384 | 4         | 11.11%  |
| 2048  | 2         | 5.56%   |
| 32768 | 1         | 2.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 12        | 33.33%  |
| 2667  | 7         | 19.44%  |
| 3200  | 5         | 13.89%  |
| 2133  | 4         | 11.11%  |
| 4800  | 2         | 5.56%   |
| 2400  | 2         | 5.56%   |
| 1334  | 2         | 5.56%   |
| 1333  | 1         | 2.78%   |
| 1067  | 1         | 2.78%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lexmark International | 1         | 50%     |
| Hewlett-Packard       | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lexmark International InkJet Color Printer | 1         | 50%     |
| HP LaserJet 1000                           | 1         | 50%     |

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
| Chicony Electronics                    | 16        | 22.86%  |
| Realtek Semiconductor                  | 8         | 11.43%  |
| IMC Networks                           | 8         | 11.43%  |
| Microdia                               | 5         | 7.14%   |
| Sunplus Innovation Technology          | 4         | 5.71%   |
| Quanta                                 | 4         | 5.71%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5.71%   |
| Suyin                                  | 3         | 4.29%   |
| Lite-On Technology                     | 3         | 4.29%   |
| Bison Electronics                      | 3         | 4.29%   |
| Syntek                                 | 2         | 2.86%   |
| Ricoh                                  | 2         | 2.86%   |
| Acer                                   | 2         | 2.86%   |
| Samsung Electronics                    | 1         | 1.43%   |
| Primax Electronics                     | 1         | 1.43%   |
| Luxvisions Innotech Limited            | 1         | 1.43%   |
| Lenovo                                 | 1         | 1.43%   |
| Apple                                  | 1         | 1.43%   |
| ALi                                    | 1         | 1.43%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                               | 5         | 7.14%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 5         | 7.14%   |
| Bison EasyCamera                                            | 3         | 4.29%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 2.86%   |
| Realtek HD WebCam                                           | 2         | 2.86%   |
| Lite-On HP HD Webcam                                        | 2         | 2.86%   |
| Chicony Integrated Camera                                   | 2         | 2.86%   |
| Chicony HP Truevision HD                                    | 2         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 2         | 2.86%   |
| Syntek Lenovo EasyCamera                                    | 1         | 1.43%   |
| Syntek Integrated Camera                                    | 1         | 1.43%   |
| Suyin HP TrueVision HD                                      | 1         | 1.43%   |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 1.43%   |
| Sunplus HP Universal Camera                                 | 1         | 1.43%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 1.43%   |
| Sunplus HD WebCam                                           | 1         | 1.43%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 1         | 1.43%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870]         | 1         | 1.43%   |
| Ricoh Laptop_Integrated_Webcam_3M                           | 1         | 1.43%   |
| Realtek VGA WebCam                                          | 1         | 1.43%   |
| Realtek USB Camera                                          | 1         | 1.43%   |
| Realtek Laptop_Integrated_Webcam_HD                         | 1         | 1.43%   |
| Realtek Integrated_Webcam_HD                                | 1         | 1.43%   |
| Realtek Integrated Webcam HD                                | 1         | 1.43%   |
| Realtek HP Wide Vision FHD Camera                           | 1         | 1.43%   |
| Quanta HP Wide Vision HD Camera                             | 1         | 1.43%   |
| Quanta HP Webcam                                            | 1         | 1.43%   |
| Quanta HP TrueVision HD Camera                              | 1         | 1.43%   |
| Quanta HP HD Camera                                         | 1         | 1.43%   |
| Primax HP HD Webcam [Fixed]                                 | 1         | 1.43%   |
| Luxvisions Innotech Limited HP HD Camera                    | 1         | 1.43%   |
| Lite-On HP Webcam                                           | 1         | 1.43%   |
| Lenovo UVC Camera                                           | 1         | 1.43%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 1.43%   |
| IMC Networks USB2.0 HD IR UVC WebCam                        | 1         | 1.43%   |
| IMC Networks ov9734_azurewave_camera                        | 1         | 1.43%   |
| Chicony UVC 1.00 device HD UVC WebCam                       | 1         | 1.43%   |
| Chicony USB2.0 VGA UVC WebCam                               | 1         | 1.43%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 1.43%   |
| Chicony thinkpad t430s camera                               | 1         | 1.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 61.11%  |
| Synaptics                  | 3         | 16.67%  |
| Shenzhen Goodix Technology | 2         | 11.11%  |
| LighTuning Technology      | 1         | 5.56%   |
| AuthenTec                  | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader               | 5         | 27.78%  |
| Validity Sensors VFS471 Fingerprint Reader               | 4         | 22.22%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 11.11%  |
| Shenzhen Goodix  FingerPrint Device                      | 2         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 5.56%   |
| Validity Sensors Swipe Fingerprint Sensor                | 1         | 5.56%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 5.56%   |
| LighTuning Fingerprint Reader                            | 1         | 5.56%   |
| AuthenTec AES2810                                        | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 60%     |
| Upek        | 1         | 20%     |
| Alcor Micro | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 2         | 40%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 47        | 55.95%  |
| 1     | 32        | 38.1%   |
| 2     | 4         | 4.76%   |
| 3     | 1         | 1.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 18        | 43.9%   |
| Graphics card         | 6         | 14.63%  |
| Net/wireless          | 5         | 12.2%   |
| Chipcard              | 5         | 12.2%   |
| Bluetooth             | 3         | 7.32%   |
| Sound                 | 2         | 4.88%   |
| Multimedia controller | 1         | 2.44%   |
| Modem                 | 1         | 2.44%   |


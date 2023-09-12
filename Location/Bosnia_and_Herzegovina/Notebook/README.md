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

Total: 154

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 8540p             | [ac307135fa](https://linux-hardware.org/?probe=ac307135fa) | Sep 02, 2023 |
| Fujitsu       | LIFEBOOK U904               | [7cf4986142](https://linux-hardware.org/?probe=7cf4986142) | Aug 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [194ec12831](https://linux-hardware.org/?probe=194ec12831) | Aug 09, 2023 |
| HP            | EliteBook 8460p             | [db336dcf75](https://linux-hardware.org/?probe=db336dcf75) | Aug 05, 2023 |
| MSI           | Pulse GL66 12UDK            | [8c9a9eb310](https://linux-hardware.org/?probe=8c9a9eb310) | Jun 06, 2023 |
| Lenovo        | ThinkPad W530 24411M9       | [1094884573](https://linux-hardware.org/?probe=1094884573) | May 19, 2023 |
| Toshiba       | Satellite L850-1HQ          | [d16c26b474](https://linux-hardware.org/?probe=d16c26b474) | May 18, 2023 |
| Dell          | Precision 5570              | [c9e52e6e8c](https://linux-hardware.org/?probe=c9e52e6e8c) | May 18, 2023 |
| HP            | EliteBook 8540p             | [4f5efbc9fe](https://linux-hardware.org/?probe=4f5efbc9fe) | May 16, 2023 |
| HP            | EliteBook 8540p             | [8041b17525](https://linux-hardware.org/?probe=8041b17525) | May 16, 2023 |
| Lenovo        | ThinkPad L440 20ASA09T06    | [48009f1be4](https://linux-hardware.org/?probe=48009f1be4) | May 15, 2023 |
| Lenovo        | ThinkPad L440 20ASA09T06    | [49e6d93eb1](https://linux-hardware.org/?probe=49e6d93eb1) | May 15, 2023 |
| Dell          | Vostro 3500                 | [81f86e6678](https://linux-hardware.org/?probe=81f86e6678) | May 11, 2023 |
| Toshiba       | PORTEGE Z930                | [f87cd6e36c](https://linux-hardware.org/?probe=f87cd6e36c) | May 07, 2023 |
| Toshiba       | Satellite C855              | [775c7346eb](https://linux-hardware.org/?probe=775c7346eb) | May 06, 2023 |
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


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Ubuntu 20.04                | 14        | 13.59%  |
| Ubuntu 22.04                | 6         | 5.83%   |
| Pop!_OS 21.04               | 6         | 5.83%   |
| Zorin 16                    | 4         | 3.88%   |
| Ubuntu 18.04                | 4         | 3.88%   |
| Linux Mint 20.2             | 4         | 3.88%   |
| Ubuntu 23.04                | 3         | 2.91%   |
| OpenMandriva 23.03          | 3         | 2.91%   |
| Manjaro                     | 3         | 2.91%   |
| Arch Rolling                | 3         | 2.91%   |
| Ubuntu 20.10                | 2         | 1.94%   |
| Ubuntu 19.04                | 2         | 1.94%   |
| Pop!_OS 20.04               | 2         | 1.94%   |
| OpenMandriva 4.3            | 2         | 1.94%   |
| Lubuntu 19.10               | 2         | 1.94%   |
| Linux Mint 21.1             | 2         | 1.94%   |
| Linux Mint 19.3             | 2         | 1.94%   |
| Kubuntu 22.04               | 2         | 1.94%   |
| Fedora 37                   | 2         | 1.94%   |
| ArcoLinux Rolling           | 2         | 1.94%   |
| Zorin 15                    | 1         | 0.97%   |
| Xubuntu 20.04               | 1         | 0.97%   |
| Xubuntu 18.04               | 1         | 0.97%   |
| Xero Rolling                | 1         | 0.97%   |
| Ubuntu Budgie 21.10         | 1         | 0.97%   |
| Ubuntu 22.10                | 1         | 0.97%   |
| Ubuntu 21.10                | 1         | 0.97%   |
| Ubuntu 21.04                | 1         | 0.97%   |
| Ubuntu 16.04                | 1         | 0.97%   |
| ROSA R10                    | 1         | 0.97%   |
| PureOS 9.0                  | 1         | 0.97%   |
| Pop!_OS 21.10               | 1         | 0.97%   |
| Pop!_OS 20.10               | 1         | 0.97%   |
| org.kde.Platform 5.15-21.08 | 1         | 0.97%   |
| Manjaro 21.2.5              | 1         | 0.97%   |
| Manjaro 21.0.7              | 1         | 0.97%   |
| LMDE 5                      | 1         | 0.97%   |
| Linux Mint 21               | 1         | 0.97%   |
| Linux Mint 20               | 1         | 0.97%   |
| KDE neon 20.04              | 1         | 0.97%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 32        | 32.32%  |
| Pop!_OS          | 10        | 10.1%   |
| Linux Mint       | 9         | 9.09%   |
| Zorin            | 5         | 5.05%   |
| OpenMandriva     | 5         | 5.05%   |
| Manjaro          | 5         | 5.05%   |
| Fedora           | 5         | 5.05%   |
| Endless          | 4         | 4.04%   |
| Arch             | 4         | 4.04%   |
| Debian           | 3         | 3.03%   |
| Xubuntu          | 2         | 2.02%   |
| Lubuntu          | 2         | 2.02%   |
| Kubuntu          | 2         | 2.02%   |
| ArcoLinux        | 2         | 2.02%   |
| Xero             | 1         | 1.01%   |
| Ubuntu Budgie    | 1         | 1.01%   |
| ROSA             | 1         | 1.01%   |
| PureOS           | 1         | 1.01%   |
| org.kde.Platform | 1         | 1.01%   |
| LMDE             | 1         | 1.01%   |
| KDE neon         | 1         | 1.01%   |
| EndeavourOS      | 1         | 1.01%   |
| Elementary       | 1         | 1.01%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.2.6-desktop-1omv2390  | 3         | 2.78%   |
| 6.2.0-20-generic        | 3         | 2.78%   |
| 5.3.0-46-generic        | 3         | 2.78%   |
| 5.3.0-28-generic        | 3         | 2.78%   |
| 5.15.0-48-generic       | 3         | 2.78%   |
| 5.4.0-89-generic        | 2         | 1.85%   |
| 5.4.0-52-generic        | 2         | 1.85%   |
| 5.16.7-desktop-1omv4003 | 2         | 1.85%   |
| 5.15.0-56-generic       | 2         | 1.85%   |
| 5.15.0-39-generic       | 2         | 1.85%   |
| 5.13.0-7620-generic     | 2         | 1.85%   |
| 5.13.0-7614-generic     | 2         | 1.85%   |
| 5.13.0-39-generic       | 2         | 1.85%   |
| 5.11.0-40-generic       | 2         | 1.85%   |
| 6.4.8                   | 1         | 0.93%   |
| 6.4.12-arch1-1          | 1         | 0.93%   |
| 6.3.1-arch1-1           | 1         | 0.93%   |
| 6.2.15-300.fc38.x86_64  | 1         | 0.93%   |
| 6.2.0-26-generic        | 1         | 0.93%   |
| 6.1.26-1-lts            | 1         | 0.93%   |
| 6.1.0-0.deb11.7-amd64   | 1         | 0.93%   |
| 6.0.8-arch1-1           | 1         | 0.93%   |
| 6.0.8-300.fc37.x86_64   | 1         | 0.93%   |
| 6.0.15-300.fc37.x86_64  | 1         | 0.93%   |
| 6.0.12-arch1-1          | 1         | 0.93%   |
| 5.9.0-3-amd64           | 1         | 0.93%   |
| 5.8.9-200.fc32.x86_64   | 1         | 0.93%   |
| 5.8.0-7630-generic      | 1         | 0.93%   |
| 5.8.0-53-generic        | 1         | 0.93%   |
| 5.8.0-49-generic        | 1         | 0.93%   |
| 5.8.0-44-generic        | 1         | 0.93%   |
| 5.8.0-34-generic        | 1         | 0.93%   |
| 5.8.0-26-generic        | 1         | 0.93%   |
| 5.7.0-1-librem5         | 1         | 0.93%   |
| 5.4.52-1-MANJARO        | 1         | 0.93%   |
| 5.4.33-3-MANJARO        | 1         | 0.93%   |
| 5.4.23-1-MANJARO        | 1         | 0.93%   |
| 5.4.0-90-generic        | 1         | 0.93%   |
| 5.4.0-80-generic        | 1         | 0.93%   |
| 5.4.0-7625-generic      | 1         | 0.93%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 14        | 13.21%  |
| 5.15.0  | 11        | 10.38%  |
| 5.13.0  | 11        | 10.38%  |
| 5.3.0   | 7         | 6.6%    |
| 5.11.0  | 7         | 6.6%    |
| 5.8.0   | 6         | 5.66%   |
| 5.19.0  | 4         | 3.77%   |
| 4.15.0  | 4         | 3.77%   |
| 6.2.6   | 3         | 2.83%   |
| 6.2.0   | 3         | 2.83%   |
| 5.0.0   | 3         | 2.83%   |
| 6.0.8   | 2         | 1.89%   |
| 5.16.7  | 2         | 1.89%   |
| 5.10.0  | 2         | 1.89%   |
| 6.4.8   | 1         | 0.94%   |
| 6.4.12  | 1         | 0.94%   |
| 6.3.1   | 1         | 0.94%   |
| 6.2.15  | 1         | 0.94%   |
| 6.1.26  | 1         | 0.94%   |
| 6.1.0   | 1         | 0.94%   |
| 6.0.15  | 1         | 0.94%   |
| 6.0.12  | 1         | 0.94%   |
| 5.9.0   | 1         | 0.94%   |
| 5.8.9   | 1         | 0.94%   |
| 5.7.0   | 1         | 0.94%   |
| 5.4.52  | 1         | 0.94%   |
| 5.4.33  | 1         | 0.94%   |
| 5.4.23  | 1         | 0.94%   |
| 5.19.8  | 1         | 0.94%   |
| 5.16.14 | 1         | 0.94%   |
| 5.16.11 | 1         | 0.94%   |
| 5.15.94 | 1         | 0.94%   |
| 5.15.89 | 1         | 0.94%   |
| 5.15.23 | 1         | 0.94%   |
| 5.15.11 | 1         | 0.94%   |
| 5.13.9  | 1         | 0.94%   |
| 5.11.18 | 1         | 0.94%   |
| 5.10.42 | 1         | 0.94%   |
| 5.10.37 | 1         | 0.94%   |
| 4.9.60  | 1         | 0.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 17        | 16.35%  |
| 5.15    | 14        | 13.46%  |
| 5.13    | 12        | 11.54%  |
| 5.11    | 8         | 7.69%   |
| 6.2     | 7         | 6.73%   |
| 5.8     | 7         | 6.73%   |
| 5.3     | 7         | 6.73%   |
| 5.19    | 5         | 4.81%   |
| 5.16    | 4         | 3.85%   |
| 5.10    | 4         | 3.85%   |
| 4.15    | 4         | 3.85%   |
| 6.0     | 3         | 2.88%   |
| 5.0     | 3         | 2.88%   |
| 6.4     | 2         | 1.92%   |
| 6.1     | 2         | 1.92%   |
| 6.3     | 1         | 0.96%   |
| 5.9     | 1         | 0.96%   |
| 5.7     | 1         | 0.96%   |
| 4.9     | 1         | 0.96%   |
| 4.18    | 1         | 0.96%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 89        | 95.7%   |
| i686    | 3         | 3.23%   |
| aarch64 | 1         | 1.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 54        | 56.25%  |
| KDE5       | 12        | 12.5%   |
| XFCE       | 11        | 11.46%  |
| Unknown    | 6         | 6.25%   |
| X-Cinnamon | 5         | 5.21%   |
| LXQt       | 2         | 2.08%   |
| Pantheon   | 1         | 1.04%   |
| MATE       | 1         | 1.04%   |
| KDE4       | 1         | 1.04%   |
| KDE        | 1         | 1.04%   |
| Budgie     | 1         | 1.04%   |
| bspwm      | 1         | 1.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 74        | 78.72%  |
| Wayland | 15        | 15.96%  |
| Unknown | 5         | 5.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 54        | 55.1%   |
| SDDM    | 13        | 13.27%  |
| GDM     | 12        | 12.24%  |
| LightDM | 9         | 9.18%   |
| GDM3    | 9         | 9.18%   |
| KDM     | 1         | 1.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 74        | 78.72%  |
| Unknown | 6         | 6.38%   |
| hr_HR   | 4         | 4.26%   |
| bs_BA   | 4         | 4.26%   |
| de_CH   | 2         | 2.13%   |
| C       | 2         | 2.13%   |
| en_GB   | 1         | 1.06%   |
| en_AU   | 1         | 1.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 54        | 56.84%  |
| EFI  | 41        | 43.16%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 79        | 84.04%  |
| Btrfs   | 7         | 7.45%   |
| Overlay | 5         | 5.32%   |
| Unknown | 3         | 3.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 61        | 63.54%  |
| GPT     | 29        | 30.21%  |
| MBR     | 6         | 6.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 87        | 93.55%  |
| Yes       | 6         | 6.45%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 75        | 80.65%  |
| Yes       | 18        | 19.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 28        | 30.11%  |
| Lenovo           | 19        | 20.43%  |
| Dell             | 12        | 12.9%   |
| ASUSTek Computer | 12        | 12.9%   |
| Acer             | 10        | 10.75%  |
| Toshiba          | 4         | 4.3%    |
| Sony             | 1         | 1.08%   |
| NEC Computers    | 1         | 1.08%   |
| MSI              | 1         | 1.08%   |
| HUAWEI           | 1         | 1.08%   |
| Fujitsu Siemens  | 1         | 1.08%   |
| Fujitsu          | 1         | 1.08%   |
| eMachines        | 1         | 1.08%   |
| Unknown          | 1         | 1.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| HP EliteBook 8460p                                | 3         | 3.23%   |
| Lenovo Legion 5 Pro 16IAH7H 82RF                  | 2         | 2.15%   |
| Lenovo IdeaPad 330-15IKB 81DE                     | 2         | 2.15%   |
| HP 250 G7 Notebook PC                             | 2         | 2.15%   |
| Dell G3 3590                                      | 2         | 2.15%   |
| ASUS VivoBook_ASUSLaptop X509DA_D509DA            | 2         | 2.15%   |
| Toshiba Satellite L850-1HQ                        | 1         | 1.08%   |
| Toshiba Satellite C855                            | 1         | 1.08%   |
| Toshiba Satellite C850-1GF                        | 1         | 1.08%   |
| Toshiba PORTEGE Z930                              | 1         | 1.08%   |
| Sony VGN-BX41VN                                   | 1         | 1.08%   |
| NEC Computers VERSAP550 NN951700753               | 1         | 1.08%   |
| MSI Pulse GL66 12UDK                              | 1         | 1.08%   |
| Lenovo ThinkPad X301 277418G                      | 1         | 1.08%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A7008AMZ          | 1         | 1.08%   |
| Lenovo ThinkPad W530 24411M9                      | 1         | 1.08%   |
| Lenovo ThinkPad T430 2349G2G                      | 1         | 1.08%   |
| Lenovo ThinkPad T420 4180WAP                      | 1         | 1.08%   |
| Lenovo ThinkPad T14s Gen 1 20UH0056SC             | 1         | 1.08%   |
| Lenovo ThinkPad S1 Yoga 20CD0038MZ                | 1         | 1.08%   |
| Lenovo ThinkPad L440 20ASA09T06                   | 1         | 1.08%   |
| Lenovo ThinkPad E15 Gen 2 20TD003LSC              | 1         | 1.08%   |
| Lenovo Legion 7 15IMHg05 81YU                     | 1         | 1.08%   |
| Lenovo IdeaPad Y570 20091                         | 1         | 1.08%   |
| Lenovo IdeaPad L340-15IWL 81LG                    | 1         | 1.08%   |
| Lenovo IdeaPad 320-15IKB 81BG                     | 1         | 1.08%   |
| Lenovo IdeaPad 110S-11IBR 80WG                    | 1         | 1.08%   |
| Lenovo G505 20240                                 | 1         | 1.08%   |
| HUAWEI BOHK-WAX9X                                 | 1         | 1.08%   |
| HP ZBook Firefly 14 inch G8 Mobile Workstation PC | 1         | 1.08%   |
| HP ZBook 15 G4                                    | 1         | 1.08%   |
| HP ProBook 6560b                                  | 1         | 1.08%   |
| HP ProBook 650 G1                                 | 1         | 1.08%   |
| HP ProBook 4710s                                  | 1         | 1.08%   |
| HP ProBook 470 G2                                 | 1         | 1.08%   |
| HP ProBook 470 G0                                 | 1         | 1.08%   |
| HP Pavilion Gaming Laptop 15-dk2xxx               | 1         | 1.08%   |
| HP Laptop 15-rb0xx                                | 1         | 1.08%   |
| HP ENVY TS 15                                     | 1         | 1.08%   |
| HP ENVY 6                                         | 1         | 1.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| HP EliteBook            | 11        | 11.83%  |
| Lenovo ThinkPad         | 9         | 9.68%   |
| Acer Aspire             | 7         | 7.53%   |
| Lenovo IdeaPad          | 6         | 6.45%   |
| HP ProBook              | 5         | 5.38%   |
| ASUS VivoBook           | 4         | 4.3%    |
| Toshiba Satellite       | 3         | 3.23%   |
| Lenovo Legion           | 3         | 3.23%   |
| HP 250                  | 3         | 3.23%   |
| Dell Latitude           | 3         | 3.23%   |
| HP ZBook                | 2         | 2.15%   |
| HP ENVY                 | 2         | 2.15%   |
| Dell XPS                | 2         | 2.15%   |
| Dell Inspiron           | 2         | 2.15%   |
| Dell G3                 | 2         | 2.15%   |
| Toshiba PORTEGE         | 1         | 1.08%   |
| Sony VGN-BX41VN         | 1         | 1.08%   |
| NEC Computers VERSAP550 | 1         | 1.08%   |
| MSI Pulse               | 1         | 1.08%   |
| Lenovo G505             | 1         | 1.08%   |
| HUAWEI BOHK-WAX9X       | 1         | 1.08%   |
| HP Pavilion             | 1         | 1.08%   |
| HP Laptop               | 1         | 1.08%   |
| HP Compaq               | 1         | 1.08%   |
| HP 550                  | 1         | 1.08%   |
| HP 255                  | 1         | 1.08%   |
| Fujitsu Siemens AMILO   | 1         | 1.08%   |
| Fujitsu LIFEBOOK        | 1         | 1.08%   |
| eMachines eME728        | 1         | 1.08%   |
| Dell Vostro             | 1         | 1.08%   |
| Dell System             | 1         | 1.08%   |
| Dell Precision          | 1         | 1.08%   |
| ASUS ZenBook            | 1         | 1.08%   |
| ASUS X75VBP             | 1         | 1.08%   |
| ASUS X751MD             | 1         | 1.08%   |
| ASUS X550ZE             | 1         | 1.08%   |
| ASUS X540SAA            | 1         | 1.08%   |
| ASUS X540NA             | 1         | 1.08%   |
| ASUS TUF                | 1         | 1.08%   |
| ASUS ROG                | 1         | 1.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 12        | 12.9%   |
| 2012    | 11        | 11.83%  |
| 2013    | 9         | 9.68%   |
| 2016    | 8         | 8.6%    |
| 2019    | 7         | 7.53%   |
| 2018    | 7         | 7.53%   |
| 2017    | 6         | 6.45%   |
| 2014    | 6         | 6.45%   |
| 2022    | 5         | 5.38%   |
| 2020    | 5         | 5.38%   |
| 2010    | 5         | 5.38%   |
| 2021    | 3         | 3.23%   |
| 2009    | 2         | 2.15%   |
| 2007    | 2         | 2.15%   |
| 2015    | 1         | 1.08%   |
| 2008    | 1         | 1.08%   |
| 2006    | 1         | 1.08%   |
| 2005    | 1         | 1.08%   |
| Unknown | 1         | 1.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 93        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 89        | 94.68%  |
| Enabled  | 5         | 5.32%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 93        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 31        | 33.33%  |
| 3.01-4.0    | 17        | 18.28%  |
| 16.01-24.0  | 15        | 16.13%  |
| 8.01-16.0   | 12        | 12.9%   |
| 1.01-2.0    | 9         | 9.68%   |
| 32.01-64.0  | 4         | 4.3%    |
| 2.01-3.0    | 2         | 2.15%   |
| 64.01-256.0 | 2         | 2.15%   |
| 0.51-1.0    | 1         | 1.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 33        | 34.02%  |
| 2.01-3.0  | 28        | 28.87%  |
| 3.01-4.0  | 14        | 14.43%  |
| 4.01-8.0  | 10        | 10.31%  |
| 0.51-1.0  | 8         | 8.25%   |
| 8.01-16.0 | 3         | 3.09%   |
| 0.01-0.5  | 1         | 1.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 73        | 78.49%  |
| 2      | 20        | 21.51%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 54        | 58.06%  |
| Yes       | 39        | 41.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 82.98%  |
| No        | 16        | 17.02%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 95.7%   |
| No        | 4         | 4.3%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 72.34%  |
| No        | 26        | 27.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| Bosnia and Herzegovina | 93        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Sarajevo          | 35        | 36.08%  |
| Banja Luka        | 15        | 15.46%  |
| Tuzla             | 8         | 8.25%   |
| Zenica            | 3         | 3.09%   |
| Gracanica         | 3         | 3.09%   |
| Srebrenik         | 2         | 2.06%   |
| Prijedor          | 2         | 2.06%   |
| Pale              | 2         | 2.06%   |
| Maglaj            | 2         | 2.06%   |
| Banovici          | 2         | 2.06%   |
| Zivinice          | 1         | 1.03%   |
| Zepce             | 1         | 1.03%   |
| Visoko            | 1         | 1.03%   |
| Velika KladuÅ¡a | 1         | 1.03%   |
| Trebinje          | 1         | 1.03%   |
| Teslic            | 1         | 1.03%   |
| Stjepan-Polje     | 1         | 1.03%   |
| Solina            | 1         | 1.03%   |
| Posusje           | 1         | 1.03%   |
| Orahovica Donja   | 1         | 1.03%   |
| Novi Travnik      | 1         | 1.03%   |
| Nevesinje         | 1         | 1.03%   |
| Mostar            | 1         | 1.03%   |
| Lukavica          | 1         | 1.03%   |
| Lukavac           | 1         | 1.03%   |
| Ljubuski          | 1         | 1.03%   |
| Ilidza            | 1         | 1.03%   |
| Grude             | 1         | 1.03%   |
| Gradacac          | 1         | 1.03%   |
| Doboj             | 1         | 1.03%   |
| Brcko             | 1         | 1.03%   |
| Bijeljina         | 1         | 1.03%   |
| Bihać            | 1         | 1.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 27     | 16.36%  |
| Kingston            | 14        | 18     | 12.73%  |
| Toshiba             | 12        | 12     | 10.91%  |
| Hitachi             | 10        | 10     | 9.09%   |
| WDC                 | 9         | 10     | 8.18%   |
| SK hynix            | 9         | 12     | 8.18%   |
| SanDisk             | 9         | 11     | 8.18%   |
| Seagate             | 7         | 10     | 6.36%   |
| Unknown             | 3         | 3      | 2.73%   |
| Micron Technology   | 3         | 7      | 2.73%   |
| Intel               | 3         | 3      | 2.73%   |
| A-DATA Technology   | 2         | 2      | 1.82%   |
| Vaseky              | 1         | 1      | 0.91%   |
| Team                | 1         | 1      | 0.91%   |
| Patriot             | 1         | 1      | 0.91%   |
| OCZ                 | 1         | 2      | 0.91%   |
| LITEON              | 1         | 1      | 0.91%   |
| KIOXIA              | 1         | 1      | 0.91%   |
| Intenso             | 1         | 1      | 0.91%   |
| HGST                | 1         | 1      | 0.91%   |
| GOODRAM             | 1         | 1      | 0.91%   |
| Crucial             | 1         | 1      | 0.91%   |
| China               | 1         | 1      | 0.91%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                 | 5         | 4.39%   |
| SK hynix NVMe SSD Drive 512GB          | 3         | 2.63%   |
| Kingston SA400S37240G 240GB SSD        | 3         | 2.63%   |
| Unknown MMC Card  32GB                 | 2         | 1.75%   |
| SanDisk NVMe SSD Drive 256GB           | 2         | 1.75%   |
| Kingston SHFS37A240G 240GB SSD         | 2         | 1.75%   |
| Kingston SHFS37A120G 120GB SSD         | 2         | 1.75%   |
| Hitachi HTS723232A7A364 320GB          | 2         | 1.75%   |
| Hitachi HTS547575A9E384 752GB          | 2         | 1.75%   |
| WDC WDS240G1G0A-00SS50 240GB SSD       | 1         | 0.88%   |
| WDC WD7500BPVT-75HXZT3 752GB           | 1         | 0.88%   |
| WDC WD7500BPVT-24HXZT3 752GB           | 1         | 0.88%   |
| WDC WD5000LPVT-75G33T0 500GB           | 1         | 0.88%   |
| WDC WD5000BEKT-22KA9T0 500GB           | 1         | 0.88%   |
| WDC WD3200BEKT-60V5T1 320GB            | 1         | 0.88%   |
| WDC WD1600BEVT-22ZCT0 160GB            | 1         | 0.88%   |
| WDC WD10SPZX-60Z10T0 1TB               | 1         | 0.88%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB   | 1         | 0.88%   |
| Vaseky V800/128G 120GB SSD             | 1         | 0.88%   |
| Unknown SD/MMC/MS PRO 1GB              | 1         | 0.88%   |
| Toshiba THNSNS256GMCP 256GB SSD        | 1         | 0.88%   |
| Toshiba MQ04ABF100 1TB                 | 1         | 0.88%   |
| Toshiba MQ01ABF050 500GB               | 1         | 0.88%   |
| Toshiba MK3263GSX 320GB                | 1         | 0.88%   |
| Toshiba MK3261GSYN 320GB               | 1         | 0.88%   |
| Toshiba MK3259GSXP 320GB               | 1         | 0.88%   |
| Toshiba KXG60ZNV512G 512GB             | 1         | 0.88%   |
| Team T253X1120G 120GB SSD              | 1         | 0.88%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB | 1         | 0.88%   |
| SK hynix SC311 SATA 256GB SSD          | 1         | 0.88%   |
| SK hynix SC300 M.2 2280 256GB SSD      | 1         | 0.88%   |
| SK hynix PC801 NVMe 1TB                | 1         | 0.88%   |
| SK hynix HFM001TD3JX013N 1TB           | 1         | 0.88%   |
| SK hynix BC711 NVMe 256GB              | 1         | 0.88%   |
| SK hynix BC501 NVMe 512GB              | 1         | 0.88%   |
| Seagate ST9120817AS 120GB              | 1         | 0.88%   |
| Seagate ST500LT012-9WS142 500GB        | 1         | 0.88%   |
| Seagate ST500LM030-1RK17D 500GB        | 1         | 0.88%   |
| Seagate ST500LM000-1EJ162 500GB        | 1         | 0.88%   |
| Seagate ST2000LM007-1R8174 2TB         | 1         | 0.88%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 10        | 10     | 27.78%  |
| Hitachi | 10        | 10     | 27.78%  |
| WDC     | 7         | 8      | 19.44%  |
| Seagate | 7         | 10     | 19.44%  |
| Unknown | 1         | 1      | 2.78%   |
| HGST    | 1         | 1      | 2.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 13     | 27.27%  |
| Kingston            | 11        | 11     | 25%     |
| SanDisk             | 4         | 5      | 9.09%   |
| SK hynix            | 2         | 4      | 4.55%   |
| Intel               | 2         | 2      | 4.55%   |
| A-DATA Technology   | 2         | 2      | 4.55%   |
| WDC                 | 1         | 1      | 2.27%   |
| Vaseky              | 1         | 1      | 2.27%   |
| Toshiba             | 1         | 1      | 2.27%   |
| Team                | 1         | 1      | 2.27%   |
| Patriot             | 1         | 1      | 2.27%   |
| OCZ                 | 1         | 2      | 2.27%   |
| Micron Technology   | 1         | 1      | 2.27%   |
| LITEON              | 1         | 1      | 2.27%   |
| Intenso             | 1         | 1      | 2.27%   |
| GOODRAM             | 1         | 1      | 2.27%   |
| China               | 1         | 1      | 2.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 43        | 49     | 39.81%  |
| HDD  | 36        | 40     | 33.33%  |
| NVMe | 26        | 45     | 24.07%  |
| MMC  | 3         | 3      | 2.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 67        | 88     | 69.07%  |
| NVMe | 26        | 45     | 26.8%   |
| MMC  | 3         | 3      | 3.09%   |
| SAS  | 1         | 1      | 1.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 59        | 72     | 78.67%  |
| 0.51-1.0   | 15        | 15     | 20%     |
| 1.01-2.0   | 1         | 2      | 1.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 35        | 36.46%  |
| 251-500        | 28        | 29.17%  |
| 21-50          | 9         | 9.38%   |
| 501-1000       | 9         | 9.38%   |
| 51-100         | 5         | 5.21%   |
| 1-20           | 4         | 4.17%   |
| Unknown        | 3         | 3.13%   |
| 2001-3000      | 2         | 2.08%   |
| More than 3000 | 1         | 1.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 39        | 37.86%  |
| 21-50     | 30        | 29.13%  |
| 51-100    | 18        | 17.48%  |
| 101-250   | 6         | 5.83%   |
| 501-1000  | 4         | 3.88%   |
| Unknown   | 3         | 2.91%   |
| 251-500   | 2         | 1.94%   |
| 1001-2000 | 1         | 0.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                            | Notebooks | Drives | Percent |
|------------------------------------------------------------------|-----------|--------|---------|
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 1024GB | 1         | 1      | 20%     |
| Samsung Electronics MZVKW512HMJP-000H1 512GB                     | 1         | 1      | 20%     |
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD                    | 1         | 1      | 20%     |
| Crucial CT500P1SSD8 500GB                                        | 1         | 1      | 20%     |
| China SSD 128GB                                                  | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 50%     |
| Crucial             | 1         | 1      | 25%     |
| China               | 1         | 1      | 25%     |

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
| NVMe | 2         | 3      | 50%     |
| SSD  | 2         | 2      | 50%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD3200BEKT-60V5T1 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 62        | 94     | 63.27%  |
| Works    | 31        | 37     | 31.63%  |
| Malfunc  | 4         | 5      | 4.08%   |
| Failed   | 1         | 1      | 1.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 74        | 67.27%  |
| AMD                          | 8         | 7.27%   |
| SK hynix                     | 7         | 6.36%   |
| Samsung Electronics          | 6         | 5.45%   |
| SanDisk                      | 5         | 4.55%   |
| Kingston Technology Company  | 3         | 2.73%   |
| Micron Technology            | 2         | 1.82%   |
| Toshiba America Info Systems | 1         | 0.91%   |
| Nvidia                       | 1         | 0.91%   |
| Micron/Crucial Technology    | 1         | 0.91%   |
| KIOXIA                       | 1         | 0.91%   |
| JMicron Technology           | 1         | 0.91%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 12        | 10.26%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 9.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 11        | 9.4%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 6.84%   |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 4.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 4.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 4.27%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 3         | 2.56%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 2.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 2.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 2.56%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 1.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.71%   |
| SanDisk PC SN520 NVMe SSD                                                        | 2         | 1.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.71%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 1.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.71%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.71%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.85%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                               | 1         | 0.85%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.85%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 0.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.85%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 0.85%   |
| Nvidia MCP51 IDE                                                                 | 1         | 0.85%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                        | 1         | 0.85%   |
| Micron 3400 NVMe SSD [Hendrix]                                                   | 1         | 0.85%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 1         | 0.85%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 1         | 0.85%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.85%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 0.85%   |
| Kingston Company NVMe Controller                                                 | 1         | 0.85%   |
| JMicron JMB363 SATA/IDE Controller                                               | 1         | 0.85%   |
| Intel SSD 600P Series                                                            | 1         | 0.85%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 70        | 61.95%  |
| NVMe | 26        | 23.01%  |
| RAID | 11        | 9.73%   |
| IDE  | 6         | 5.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 79        | 84.95%  |
| AMD    | 13        | 13.98%  |
| ARM    | 1         | 1.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-2540M CPU @ 2.60GHz             | 4         | 4.3%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 3.23%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 3.23%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 2.15%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 2.15%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 2.15%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 2.15%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 2.15%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 2.15%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 2.15%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 2.15%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 2         | 2.15%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 2.15%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 2.15%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 2.15%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2.15%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 2         | 2.15%   |
| Intel Pentium M processor 1.73GHz             | 1         | 1.08%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 1.08%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 1.08%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 1.08%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.08%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 1.08%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.08%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 1.08%   |
| Intel Core i7-4550U CPU @ 1.50GHz             | 1         | 1.08%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 1.08%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 1.08%   |
| Intel Core i7-3667U CPU @ 2.00GHz             | 1         | 1.08%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 1.08%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 1.08%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 1.08%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.08%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 1.08%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.08%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 1.08%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.08%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.08%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 1         | 1.08%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 24        | 25.81%  |
| Intel Core i5           | 23        | 24.73%  |
| Other                   | 11        | 11.83%  |
| Intel Celeron           | 7         | 7.53%   |
| Intel Core i3           | 6         | 6.45%   |
| Intel Core 2 Duo        | 4         | 4.3%    |
| AMD Ryzen 5             | 3         | 3.23%   |
| AMD E1                  | 3         | 3.23%   |
| Intel Pentium M         | 1         | 1.08%   |
| Intel Pentium Dual-Core | 1         | 1.08%   |
| Intel Pentium Dual      | 1         | 1.08%   |
| Intel Pentium           | 1         | 1.08%   |
| Intel Atom              | 1         | 1.08%   |
| AMD Turion 64 Mobile    | 1         | 1.08%   |
| AMD Ryzen 9             | 1         | 1.08%   |
| AMD Ryzen 7             | 1         | 1.08%   |
| AMD Ryzen 5 PRO         | 1         | 1.08%   |
| AMD E2                  | 1         | 1.08%   |
| AMD C-60                | 1         | 1.08%   |
| AMD A10                 | 1         | 1.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 51        | 54.84%  |
| 4      | 29        | 31.18%  |
| 14     | 5         | 5.38%   |
| 6      | 4         | 4.3%    |
| 8      | 2         | 2.15%   |
| 1      | 2         | 2.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 93        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 69        | 73.4%   |
| 1      | 25        | 26.6%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 89        | 95.7%   |
| Unknown        | 3         | 3.23%   |
| 32-bit         | 1         | 1.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 32.98%  |
| 0x206a7    | 9         | 9.57%   |
| 0x306a9    | 8         | 8.51%   |
| 0x406e3    | 4         | 4.26%   |
| 0x906a3    | 3         | 3.19%   |
| 0x806ea    | 3         | 3.19%   |
| 0x806c1    | 3         | 3.19%   |
| 0x40651    | 3         | 3.19%   |
| 0x806ec    | 2         | 2.13%   |
| 0x506c9    | 2         | 2.13%   |
| 0x306c3    | 2         | 2.13%   |
| 0x10676    | 2         | 2.13%   |
| 0x05000119 | 2         | 2.13%   |
| 0xa0652    | 1         | 1.06%   |
| 0x906ea    | 1         | 1.06%   |
| 0x906e9    | 1         | 1.06%   |
| 0x806eb    | 1         | 1.06%   |
| 0x806e9    | 1         | 1.06%   |
| 0x706e5    | 1         | 1.06%   |
| 0x6fd      | 1         | 1.06%   |
| 0x6fa      | 1         | 1.06%   |
| 0x6d8      | 1         | 1.06%   |
| 0x406c4    | 1         | 1.06%   |
| 0x406c3    | 1         | 1.06%   |
| 0x30678    | 1         | 1.06%   |
| 0x20655    | 1         | 1.06%   |
| 0x106e5    | 1         | 1.06%   |
| 0x1067a    | 1         | 1.06%   |
| 0x0a50000c | 1         | 1.06%   |
| 0x08600106 | 1         | 1.06%   |
| 0x08108109 | 1         | 1.06%   |
| 0x08108102 | 1         | 1.06%   |
| 0x0700010f | 1         | 1.06%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 15        | 16.13%  |
| SandyBridge      | 12        | 12.9%   |
| IvyBridge        | 12        | 12.9%   |
| Haswell          | 8         | 8.6%    |
| TigerLake        | 5         | 5.38%   |
| Zen+             | 4         | 4.3%    |
| Skylake          | 4         | 4.3%    |
| Silvermont       | 4         | 4.3%    |
| Alderlake Hybrid | 4         | 4.3%    |
| Penryn           | 3         | 3.23%   |
| Core             | 3         | 3.23%   |
| Westmere         | 2         | 2.15%   |
| Jaguar           | 2         | 2.15%   |
| Goldmont         | 2         | 2.15%   |
| Bobcat           | 2         | 2.15%   |
| Unknown          | 2         | 2.15%   |
| Zen 3            | 1         | 1.08%   |
| Zen 2            | 1         | 1.08%   |
| Steamroller      | 1         | 1.08%   |
| P6               | 1         | 1.08%   |
| Nehalem          | 1         | 1.08%   |
| K8 Hammer        | 1         | 1.08%   |
| IceLake          | 1         | 1.08%   |
| Excavator        | 1         | 1.08%   |
| CometLake        | 1         | 1.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 66        | 54.1%   |
| Nvidia | 31        | 25.41%  |
| AMD    | 25        | 20.49%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 8%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 7.2%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 4%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 4%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 3.2%    |
| Intel UHD Graphics 620                                                                   | 4         | 3.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 3.2%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 4         | 3.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 3.2%    |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 2.4%    |
| Nvidia GM108M [GeForce MX110]                                                            | 3         | 2.4%    |
| Intel HD Graphics 620                                                                    | 3         | 2.4%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 2.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.4%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 2.4%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 1.6%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 1.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.6%    |
| Intel HD Graphics 500                                                                    | 2         | 1.6%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.6%    |
| AMD Kabini [Radeon HD 8210]                                                              | 2         | 1.6%    |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                     | 1         | 0.8%    |
| Nvidia TU106BM [GeForce RTX 2070 Mobile]                                                 | 1         | 0.8%    |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.8%    |
| Nvidia GT216M [NVS 5100M]                                                                | 1         | 0.8%    |
| Nvidia GP108M [GeForce MX330]                                                            | 1         | 0.8%    |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.8%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.8%    |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 0.8%    |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.8%    |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 0.8%    |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.8%    |
| Nvidia GK107M [GeForce GT 750M]                                                          | 1         | 0.8%    |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 0.8%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.8%    |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.8%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 0.8%    |
| Nvidia GA107GLM [RTX A1000 Laptop GPU]                                                   | 1         | 0.8%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.8%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 37        | 39.36%  |
| Intel + Nvidia | 25        | 26.6%   |
| 1 x AMD        | 18        | 19.15%  |
| 1 x Nvidia     | 6         | 6.38%   |
| Intel + AMD    | 4         | 4.26%   |
| 2 x AMD        | 2         | 2.13%   |
| Other          | 1         | 1.06%   |
| AMD + Nvidia   | 1         | 1.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 74        | 78.72%  |
| Proprietary | 17        | 18.09%  |
| Unknown     | 3         | 3.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 55        | 56.7%   |
| 1.01-2.0   | 14        | 14.43%  |
| 0.01-0.5   | 9         | 9.28%   |
| 0.51-1.0   | 8         | 8.25%   |
| 3.01-4.0   | 6         | 6.19%   |
| 7.01-8.0   | 3         | 3.09%   |
| 5.01-6.0   | 2         | 2.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 22        | 22.22%  |
| LG Display              | 20        | 20.2%   |
| BOE                     | 14        | 14.14%  |
| Chimei Innolux          | 9         | 9.09%   |
| Samsung Electronics     | 7         | 7.07%   |
| Dell                    | 5         | 5.05%   |
| Sharp                   | 4         | 4.04%   |
| Chi Mei Optoelectronics | 3         | 3.03%   |
| AOC                     | 3         | 3.03%   |
| Philips                 | 2         | 2.02%   |
| LG Philips              | 2         | 2.02%   |
| PANDA                   | 1         | 1.01%   |
| NEC Computers           | 1         | 1.01%   |
| Mi                      | 1         | 1.01%   |
| LGD                     | 1         | 1.01%   |
| Lenovo                  | 1         | 1.01%   |
| InfoVision              | 1         | 1.01%   |
| Goldstar                | 1         | 1.01%   |
| CSO                     | 1         | 1.01%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 4         | 3.92%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch          | 3         | 2.94%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch | 2         | 1.96%   |
| LG Display LCD Monitor LGD05E4 1920x1080 344x194mm 15.5-inch         | 2         | 1.96%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch          | 2         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 2         | 1.96%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                | 2         | 1.96%   |
| AU Optronics LCD Monitor AUO35ED 1920x1080 344x193mm 15.5-inch       | 2         | 1.96%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch       | 2         | 1.96%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch              | 1         | 0.98%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch              | 1         | 0.98%   |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch              | 1         | 0.98%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch              | 1         | 0.98%   |
| Samsung Electronics SyncMaster SAM0579 1920x1080                     | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC3554 1600x900 382x215mm 17.3-inch | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch | 1         | 0.98%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch              | 1         | 0.98%   |
| Philips 221V PHL0888 1920x1080 477x268mm 21.5-inch                   | 1         | 0.98%   |
| PANDA LCD Monitor NCP0058 1920x1080 344x194mm 15.5-inch              | 1         | 0.98%   |
| NEC Computers LCD1770NX NEC6664 1280x1024 338x270mm 17.0-inch        | 1         | 0.98%   |
| Mi Monitor XMI3446 3440x1440 797x334mm 34.0-inch                     | 1         | 0.98%   |
| Mi Monitor XMI3445 3440x1440 797x334mm 34.0-inch                     | 1         | 0.98%   |
| LGD LCD Monitor 1920x1080                                            | 1         | 0.98%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch          | 1         | 0.98%   |
| LG Philips LCD Monitor LPL1E01 1280x800 331x207mm 15.4-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch         | 1         | 0.98%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch         | 1         | 0.98%   |
| LG Display LCD Monitor LGD04B3 1920x1080 345x194mm 15.6-inch         | 1         | 0.98%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x174mm 14.0-inch         | 1         | 0.98%   |
| LG Display LCD Monitor LGD0414 1920x1080 276x156mm 12.5-inch         | 1         | 0.98%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD034C 1366x768 293x165mm 13.2-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD0257 1440x900 304x190mm 14.1-inch          | 1         | 0.98%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 41        | 42.27%  |
| 1366x768 (WXGA)   | 24        | 24.74%  |
| 1600x900 (HD+)    | 12        | 12.37%  |
| 2560x1440 (QHD)   | 5         | 5.15%   |
| 1440x900 (WXGA+)  | 3         | 3.09%   |
| 3840x2160 (4K)    | 2         | 2.06%   |
| 3440x1440         | 2         | 2.06%   |
| 2560x1600         | 2         | 2.06%   |
| 1280x800 (WXGA)   | 2         | 2.06%   |
| 1280x1024 (SXGA)  | 2         | 2.06%   |
| 3200x1800 (QHD+)  | 1         | 1.03%   |
| 1920x1200 (WUXGA) | 1         | 1.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 48        | 48%     |
| 14      | 12        | 12%     |
| 17      | 10        | 10%     |
| 13      | 8         | 8%      |
| 27      | 3         | 3%      |
| 11      | 3         | 3%      |
| 34      | 2         | 2%      |
| 23      | 2         | 2%      |
| 21      | 2         | 2%      |
| 16      | 2         | 2%      |
| 12      | 2         | 2%      |
| Unknown | 2         | 2%      |
| 33      | 1         | 1%      |
| 31      | 1         | 1%      |
| 24      | 1         | 1%      |
| 18      | 1         | 1%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 68        | 68.69%  |
| 351-400     | 8         | 8.08%   |
| 201-300     | 8         | 8.08%   |
| 501-600     | 6         | 6.06%   |
| 701-800     | 3         | 3.03%   |
| 401-500     | 3         | 3.03%   |
| Unknown     | 2         | 2.02%   |
| 601-700     | 1         | 1.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 77        | 85.56%  |
| 16/10   | 8         | 8.89%   |
| 5/4     | 2         | 2.22%   |
| 21/9    | 2         | 2.22%   |
| Unknown | 1         | 1.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 46        | 46.46%  |
| 81-90          | 17        | 17.17%  |
| 121-130        | 6         | 6.06%   |
| 71-80          | 4         | 4.04%   |
| 351-500        | 4         | 4.04%   |
| 201-250        | 4         | 4.04%   |
| 51-60          | 3         | 3.03%   |
| 301-350        | 3         | 3.03%   |
| 111-120        | 3         | 3.03%   |
| 141-150        | 2         | 2.02%   |
| 131-140        | 2         | 2.02%   |
| Unknown        | 2         | 2.02%   |
| 61-70          | 1         | 1.01%   |
| 151-200        | 1         | 1.01%   |
| 91-100         | 1         | 1.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 46        | 46.94%  |
| 101-120       | 33        | 33.67%  |
| 51-100        | 11        | 11.22%  |
| 161-240       | 5         | 5.1%    |
| Unknown       | 2         | 2.04%   |
| More than 240 | 1         | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 78        | 82.11%  |
| 2     | 13        | 13.68%  |
| 0     | 3         | 3.16%   |
| 3     | 1         | 1.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 45        | 31.03%  |
| Intel                             | 43        | 29.66%  |
| Qualcomm Atheros                  | 27        | 18.62%  |
| Broadcom                          | 9         | 6.21%   |
| Ralink                            | 3         | 2.07%   |
| Hewlett-Packard                   | 3         | 2.07%   |
| Sierra Wireless                   | 2         | 1.38%   |
| Ralink Technology                 | 2         | 1.38%   |
| Marvell Technology Group          | 2         | 1.38%   |
| TP-Link                           | 1         | 0.69%   |
| Toshiba                           | 1         | 0.69%   |
| Qualcomm Atheros Communications   | 1         | 0.69%   |
| Nvidia                            | 1         | 0.69%   |
| MediaTek                          | 1         | 0.69%   |
| HTC (High Tech Computer)          | 1         | 0.69%   |
| Ericsson Business Mobile Networks | 1         | 0.69%   |
| D-Link                            | 1         | 0.69%   |
| Broadcom Limited                  | 1         | 0.69%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29        | 15.85%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 5.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 4.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 4.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 3.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 3.28%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 2.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 2.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 2.19%   |
| Intel Wireless 7260                                               | 4         | 2.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 1.64%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3         | 1.64%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.64%   |
| Intel Wireless 8260                                               | 3         | 1.64%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.64%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.64%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 1.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.64%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 1.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 1.09%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.09%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.09%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.09%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 1.09%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.09%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 1.09%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1         | 0.55%   |
| Toshiba H5321 gw                                                  | 1         | 0.55%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.55%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.55%   |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                    | 1         | 0.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.55%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.55%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.55%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.55%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 39        | 40.63%  |
| Qualcomm Atheros                | 24        | 25%     |
| Realtek Semiconductor           | 14        | 14.58%  |
| Broadcom                        | 8         | 8.33%   |
| Ralink                          | 3         | 3.13%   |
| Sierra Wireless                 | 2         | 2.08%   |
| Ralink Technology               | 2         | 2.08%   |
| TP-Link                         | 1         | 1.04%   |
| Qualcomm Atheros Communications | 1         | 1.04%   |
| MediaTek                        | 1         | 1.04%   |
| D-Link                          | 1         | 1.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 9.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 7.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 6.19%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 5.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 4.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 4.12%   |
| Intel Wireless 7260                                                     | 4         | 4.12%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 3.09%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 3.09%   |
| Intel Wireless 8265 / 8275                                              | 3         | 3.09%   |
| Intel Wireless 8260                                                     | 3         | 3.09%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 3.09%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 3.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 3.09%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 2.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.06%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 2.06%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 2.06%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 1.03%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 1.03%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 1.03%   |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                          | 1         | 1.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.03%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.03%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 1.03%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1         | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.03%   |
| Realtek 802.11ac NIC                                                    | 1         | 1.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.03%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.03%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.03%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.03%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.03%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.03%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 41        | 51.25%  |
| Intel                    | 25        | 31.25%  |
| Qualcomm Atheros         | 6         | 7.5%    |
| Marvell Technology Group | 2         | 2.5%    |
| Broadcom                 | 2         | 2.5%    |
| Nvidia                   | 1         | 1.25%   |
| HTC (High Tech Computer) | 1         | 1.25%   |
| Hewlett-Packard          | 1         | 1.25%   |
| Broadcom Limited         | 1         | 1.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29        | 35.8%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 12.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 9.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 3.7%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 3.7%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 2.47%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.47%   |
| Intel Ethernet Connection I217-V                                  | 2         | 2.47%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.23%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.23%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.23%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.23%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.23%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.23%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 1.23%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.23%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.23%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.23%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.23%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.23%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.23%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.23%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 1.23%   |
| HTC (High Tech Computer) Desire HD (modem mode)                   | 1         | 1.23%   |
| HP HP lt4120 Snapdragon X5 LTE                                    | 1         | 1.23%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.23%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.23%   |
| Broadcom Limited NetLink BCM57781 Gigabit Ethernet PCIe           | 1         | 1.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 89        | 51.74%  |
| Ethernet | 78        | 45.35%  |
| Modem    | 5         | 2.91%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 79        | 82.29%  |
| Ethernet | 17        | 17.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 74        | 78.72%  |
| 1     | 17        | 18.09%  |
| 0     | 3         | 3.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 89        | 95.7%   |
| Yes  | 4         | 4.3%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 30.88%  |
| Qualcomm Atheros Communications | 11        | 16.18%  |
| IMC Networks                    | 7         | 10.29%  |
| Realtek Semiconductor           | 6         | 8.82%   |
| Broadcom                        | 5         | 7.35%   |
| Lite-On Technology              | 4         | 5.88%   |
| Ralink                          | 3         | 4.41%   |
| Hewlett-Packard                 | 3         | 4.41%   |
| Toshiba                         | 2         | 2.94%   |
| Foxconn / Hon Hai               | 2         | 2.94%   |
| Realtek                         | 1         | 1.47%   |
| Dell                            | 1         | 1.47%   |
| Cambridge Silicon Radio         | 1         | 1.47%   |
| Alps Electric                   | 1         | 1.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 11.76%  |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 10.29%  |
| Intel Bluetooth Device                              | 5         | 7.35%   |
| Intel AX201 Bluetooth                               | 5         | 7.35%   |
| Realtek Bluetooth Radio                             | 4         | 5.88%   |
| IMC Networks Bluetooth Radio                        | 4         | 5.88%   |
| Ralink RT3290 Bluetooth                             | 3         | 4.41%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 4.41%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 2.94%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 2.94%   |
| IMC Networks Bluetooth Device                       | 2         | 2.94%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 2.94%   |
| Toshiba RT Bluetooth Radio                          | 1         | 1.47%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 1.47%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 1.47%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.47%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.47%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.47%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.47%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 1.47%   |
| Intel AX200 Bluetooth                               | 1         | 1.47%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.47%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.47%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 1.47%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 1.47%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.47%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.47%   |
| Broadcom HP Portable Valentine                      | 1         | 1.47%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.47%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.47%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.47%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 1.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 78        | 68.42%  |
| AMD                 | 19        | 16.67%  |
| Nvidia              | 13        | 11.4%   |
| Logitech            | 2         | 1.75%   |
| Texas Instruments   | 1         | 0.88%   |
| C-Media Electronics | 1         | 0.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 9.7%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 8.21%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 8.21%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 4.48%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 3.73%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 3.73%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 3.73%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 3.73%   |
| AMD FCH Azalia Controller                                                                         | 5         | 3.73%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 2.99%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.24%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2.24%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 2.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.24%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 2.24%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.49%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 1.49%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.49%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.49%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.49%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.49%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.49%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 1.49%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1         | 0.75%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.75%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.75%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.75%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.75%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.75%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.75%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.75%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.75%   |
| Logitech H390 headset with microphone                                                             | 1         | 0.75%   |
| Logitech 960 Headset                                                                              | 1         | 0.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.75%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 14        | 28.57%  |
| Samsung Electronics | 14        | 28.57%  |
| Micron Technology   | 10        | 20.41%  |
| Kingston            | 6         | 12.24%  |
| Crucial             | 2         | 4.08%   |
| A-DATA Technology   | 2         | 4.08%   |
| Corsair             | 1         | 2.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 3.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 3.7%    |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s         | 2         | 3.7%    |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                  | 1         | 1.85%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2133MT/s               | 1         | 1.85%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.85%   |
| SK hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s         | 1         | 1.85%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.85%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 1         | 1.85%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s         | 1         | 1.85%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s         | 1         | 1.85%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s          | 1         | 1.85%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s   | 1         | 1.85%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 1         | 1.85%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 1.85%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 1.85%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 1.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 1.85%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 1.85%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                | 1         | 1.85%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s          | 1         | 1.85%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1.85%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 1         | 1.85%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1.85%   |
| Samsung RAM M471B5173BH0-CK0 4GB DDR3 1600MT/s                 | 1         | 1.85%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 1.85%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 1         | 1.85%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 1.85%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 1.85%   |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM DDR5 4800MT/s       | 1         | 1.85%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s        | 1         | 1.85%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s        | 1         | 1.85%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.85%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 1.85%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 1         | 1.85%   |
| Micron RAM 8JTF51264HZ-1G6D 1 4GB SODIMM DDR3 1600MT/s         | 1         | 1.85%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s          | 1         | 1.85%   |
| Micron RAM 16KTF51264HZ-1G4M1 4GB SODIMM DDR3 1334MT/s         | 1         | 1.85%   |
| Micron RAM 16JSF25664HY-1G1D1 2GB SODIMM DDR3 1067MT/s         | 1         | 1.85%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s          | 1         | 1.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 18        | 42.86%  |
| DDR3   | 18        | 42.86%  |
| DDR5   | 3         | 7.14%   |
| SDRAM  | 1         | 2.38%   |
| LPDDR4 | 1         | 2.38%   |
| LPDDR3 | 1         | 2.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 39        | 92.86%  |
| Row Of Chips | 2         | 4.76%   |
| Unknown      | 1         | 2.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 19        | 42.22%  |
| 4096  | 17        | 37.78%  |
| 16384 | 4         | 8.89%   |
| 2048  | 3         | 6.67%   |
| 32768 | 2         | 4.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 15        | 34.09%  |
| 3200  | 8         | 18.18%  |
| 2667  | 7         | 15.91%  |
| 2133  | 4         | 9.09%   |
| 4800  | 3         | 6.82%   |
| 1334  | 3         | 6.82%   |
| 4199  | 1         | 2.27%   |
| 2400  | 1         | 2.27%   |
| 1333  | 1         | 2.27%   |
| 1067  | 1         | 2.27%   |

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
| Chicony Electronics                    | 19        | 23.46%  |
| Realtek Semiconductor                  | 9         | 11.11%  |
| IMC Networks                           | 8         | 9.88%   |
| Microdia                               | 7         | 8.64%   |
| Bison Electronics                      | 7         | 8.64%   |
| Sunplus Innovation Technology          | 6         | 7.41%   |
| Quanta                                 | 4         | 4.94%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.94%   |
| Suyin                                  | 3         | 3.7%    |
| Lite-On Technology                     | 3         | 3.7%    |
| Syntek                                 | 2         | 2.47%   |
| Ricoh                                  | 2         | 2.47%   |
| Samsung Electronics                    | 1         | 1.23%   |
| Primax Electronics                     | 1         | 1.23%   |
| Luxvisions Innotech Limited            | 1         | 1.23%   |
| Lenovo                                 | 1         | 1.23%   |
| Importek                               | 1         | 1.23%   |
| Apple                                  | 1         | 1.23%   |
| ALi                                    | 1         | 1.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                               | 7         | 8.64%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 5         | 6.17%   |
| Chicony Integrated Camera                                   | 3         | 3.7%    |
| Bison EasyCamera                                            | 3         | 3.7%    |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 2.47%   |
| Sunplus HP Universal Camera                                 | 2         | 2.47%   |
| Realtek HD WebCam                                           | 2         | 2.47%   |
| Lite-On HP HD Webcam                                        | 2         | 2.47%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 2.47%   |
| Chicony HP Truevision HD                                    | 2         | 2.47%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 2         | 2.47%   |
| Syntek Lenovo EasyCamera                                    | 1         | 1.23%   |
| Syntek Integrated Camera                                    | 1         | 1.23%   |
| Suyin HP Truevision HD                                      | 1         | 1.23%   |
| Sunplus TOSHIBA Web Camera - HD                             | 1         | 1.23%   |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 1.23%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 1.23%   |
| Sunplus HD WebCam                                           | 1         | 1.23%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 1         | 1.23%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870]         | 1         | 1.23%   |
| Ricoh Laptop_Integrated_Webcam_3M                           | 1         | 1.23%   |
| Realtek VGA WebCam                                          | 1         | 1.23%   |
| Realtek USB Camera                                          | 1         | 1.23%   |
| Realtek Laptop_Integrated_Webcam_HD                         | 1         | 1.23%   |
| Realtek Integrated_Webcam_HD                                | 1         | 1.23%   |
| Realtek Integrated Webcam HD                                | 1         | 1.23%   |
| Realtek HP Wide Vision FHD Camera                           | 1         | 1.23%   |
| Realtek FJ Camera                                           | 1         | 1.23%   |
| Quanta HP Wide Vision HD Camera                             | 1         | 1.23%   |
| Quanta HP Webcam                                            | 1         | 1.23%   |
| Quanta HP TrueVision HD Camera                              | 1         | 1.23%   |
| Quanta HP HD Camera                                         | 1         | 1.23%   |
| Primax HP HD Webcam [Fixed]                                 | 1         | 1.23%   |
| Luxvisions Innotech Limited HP HD Camera                    | 1         | 1.23%   |
| Lite-On HP Webcam                                           | 1         | 1.23%   |
| Lenovo UVC Camera                                           | 1         | 1.23%   |
| Importek TOSHIBA Web Camera - HD                            | 1         | 1.23%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 1.23%   |
| IMC Networks USB2.0 HD IR UVC WebCam                        | 1         | 1.23%   |
| IMC Networks ov9734_azurewave_camera                        | 1         | 1.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 13        | 61.9%   |
| Synaptics                  | 3         | 14.29%  |
| Shenzhen Goodix Technology | 2         | 9.52%   |
| AuthenTec                  | 2         | 9.52%   |
| LighTuning Technology      | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader               | 5         | 23.81%  |
| Validity Sensors VFS471 Fingerprint Reader               | 5         | 23.81%  |
| Validity Sensors Swipe Fingerprint Sensor                | 2         | 9.52%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 9.52%   |
| Shenzhen Goodix  FingerPrint Device                      | 2         | 9.52%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 4.76%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 4.76%   |
| LighTuning Fingerprint Reader                            | 1         | 4.76%   |
| AuthenTec Fingerprint Sensor                             | 1         | 4.76%   |
| AuthenTec AES2810                                        | 1         | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 50%     |
| Upek        | 1         | 16.67%  |
| Lenovo      | 1         | 16.67%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 2         | 33.33%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 16.67%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 50        | 52.08%  |
| 1     | 40        | 41.67%  |
| 2     | 5         | 5.21%   |
| 3     | 1         | 1.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 21        | 41.18%  |
| Graphics card         | 10        | 19.61%  |
| Net/wireless          | 6         | 11.76%  |
| Chipcard              | 6         | 11.76%  |
| Bluetooth             | 3         | 5.88%   |
| Sound                 | 2         | 3.92%   |
| Multimedia controller | 1         | 1.96%   |
| Modem                 | 1         | 1.96%   |
| Firewire controller   | 1         | 1.96%   |


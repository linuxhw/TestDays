Linux in Bosnia and Herzegovina - Tested Hardware & Statistics
--------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Bosnia and Herzegovina.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Bosnia_and_Herzegovina/Desktop/README.md) and [notebooks](/Location/Bosnia_and_Herzegovina/Notebook/README.md).

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

Total: 204

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | H61M-S2PV                   | Desktop     | [319d6a8bc3](https://linux-hardware.org/?probe=319d6a8bc3) | Mar 01, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [ce63d81075](https://linux-hardware.org/?probe=ce63d81075) | Mar 01, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [2e22d32463](https://linux-hardware.org/?probe=2e22d32463) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [85bfcb35ff](https://linux-hardware.org/?probe=85bfcb35ff) | Jan 23, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [81ec9ba8b3](https://linux-hardware.org/?probe=81ec9ba8b3) | Jan 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [d6243ec239](https://linux-hardware.org/?probe=d6243ec239) | Jan 23, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [9816a244b2](https://linux-hardware.org/?probe=9816a244b2) | Jan 16, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [3325b8ab60](https://linux-hardware.org/?probe=3325b8ab60) | Jan 14, 2023 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [c219f70324](https://linux-hardware.org/?probe=c219f70324) | Jan 11, 2023 |
| Gigabyte      | B85M-D2V                    | Desktop     | [03dd6fafbb](https://linux-hardware.org/?probe=03dd6fafbb) | Jan 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [143bdba9bc](https://linux-hardware.org/?probe=143bdba9bc) | Jan 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [ea19c0ace0](https://linux-hardware.org/?probe=ea19c0ace0) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [76f2ef98b9](https://linux-hardware.org/?probe=76f2ef98b9) | Jan 04, 2023 |
| HP            | 1495                        | Desktop     | [681abdb8a2](https://linux-hardware.org/?probe=681abdb8a2) | Dec 25, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [669d7e74a2](https://linux-hardware.org/?probe=669d7e74a2) | Dec 19, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [91391127d1](https://linux-hardware.org/?probe=91391127d1) | Dec 18, 2022 |
| ASUSTek       | P5LD2-VM                    | Desktop     | [b2ae663fec](https://linux-hardware.org/?probe=b2ae663fec) | Dec 16, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [4825bcbe78](https://linux-hardware.org/?probe=4825bcbe78) | Nov 27, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [47d808147c](https://linux-hardware.org/?probe=47d808147c) | Nov 23, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [3378343bab](https://linux-hardware.org/?probe=3378343bab) | Nov 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [0cdd3b10fc](https://linux-hardware.org/?probe=0cdd3b10fc) | Nov 18, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [775987aacb](https://linux-hardware.org/?probe=775987aacb) | Nov 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [512acddb70](https://linux-hardware.org/?probe=512acddb70) | Oct 30, 2022 |
| ASUSTek       | X540NA                      | Notebook    | [73799d57b3](https://linux-hardware.org/?probe=73799d57b3) | Oct 22, 2022 |
| ASUSTek       | X540NA                      | Notebook    | [bef64e98af](https://linux-hardware.org/?probe=bef64e98af) | Oct 21, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [4241008f07](https://linux-hardware.org/?probe=4241008f07) | Oct 16, 2022 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [b7a5ca0670](https://linux-hardware.org/?probe=b7a5ca0670) | Oct 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [03a74f0a7b](https://linux-hardware.org/?probe=03a74f0a7b) | Oct 06, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [bdcb5090f0](https://linux-hardware.org/?probe=bdcb5090f0) | Sep 26, 2022 |
| HP            | ProBook 6560b               | Notebook    | [96637a94a6](https://linux-hardware.org/?probe=96637a94a6) | Sep 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [bbc3c68696](https://linux-hardware.org/?probe=bbc3c68696) | Sep 14, 2022 |
| ASRock        | H61M-HVGS                   | Desktop     | [f646dceb7c](https://linux-hardware.org/?probe=f646dceb7c) | Aug 10, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [7311161548](https://linux-hardware.org/?probe=7311161548) | Aug 07, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [eeb9068dca](https://linux-hardware.org/?probe=eeb9068dca) | Jul 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [fc99c10d57](https://linux-hardware.org/?probe=fc99c10d57) | Jul 13, 2022 |
| Dell          | Latitude E6410              | Notebook    | [cde668d556](https://linux-hardware.org/?probe=cde668d556) | Jul 12, 2022 |
| Dell          | Latitude E6410              | Notebook    | [a15b38ef5e](https://linux-hardware.org/?probe=a15b38ef5e) | Jul 12, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [b7d2767b67](https://linux-hardware.org/?probe=b7d2767b67) | Jun 23, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [cf8d972149](https://linux-hardware.org/?probe=cf8d972149) | Jun 09, 2022 |
| Lenovo        | ThinkPad X301 277418G       | Notebook    | [0d9a530751](https://linux-hardware.org/?probe=0d9a530751) | May 24, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [654d58c254](https://linux-hardware.org/?probe=654d58c254) | May 07, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [3fff5f40c3](https://linux-hardware.org/?probe=3fff5f40c3) | Apr 24, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [090b87ad9b](https://linux-hardware.org/?probe=090b87ad9b) | Apr 24, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [26ac9971a3](https://linux-hardware.org/?probe=26ac9971a3) | Apr 13, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [f26ffb9177](https://linux-hardware.org/?probe=f26ffb9177) | Apr 11, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [636817086a](https://linux-hardware.org/?probe=636817086a) | Apr 08, 2022 |
| Lenovo        | ThinkPad T420 4180WAP       | Notebook    | [1e90438c11](https://linux-hardware.org/?probe=1e90438c11) | Apr 06, 2022 |
| Lenovo        | ThinkPad T420 4180WAP       | Notebook    | [f72ea7fb49](https://linux-hardware.org/?probe=f72ea7fb49) | Apr 06, 2022 |
| HP            | 0A54h                       | Desktop     | [0efed10555](https://linux-hardware.org/?probe=0efed10555) | Mar 29, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [076c89e071](https://linux-hardware.org/?probe=076c89e071) | Mar 22, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [565a9dc93c](https://linux-hardware.org/?probe=565a9dc93c) | Mar 22, 2022 |
| Dell          | Inspiron 5323               | Notebook    | [0f8594072f](https://linux-hardware.org/?probe=0f8594072f) | Feb 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d606848435](https://linux-hardware.org/?probe=d606848435) | Feb 27, 2022 |
| Toshiba       | Satellite C850-1GF          | Notebook    | [9ace91eeb9](https://linux-hardware.org/?probe=9ace91eeb9) | Feb 24, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [456ab60c06](https://linux-hardware.org/?probe=456ab60c06) | Feb 22, 2022 |
| Lenovo        | ThinkPad T430 2349G2G       | Notebook    | [14f905c347](https://linux-hardware.org/?probe=14f905c347) | Feb 19, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [95ccf112af](https://linux-hardware.org/?probe=95ccf112af) | Feb 14, 2022 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | Desktop     | [bc32230a7f](https://linux-hardware.org/?probe=bc32230a7f) | Feb 09, 2022 |
| HP            | 550                         | Notebook    | [7e286dd830](https://linux-hardware.org/?probe=7e286dd830) | Feb 08, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [b09926b5fc](https://linux-hardware.org/?probe=b09926b5fc) | Jan 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [de0a100d06](https://linux-hardware.org/?probe=de0a100d06) | Jan 24, 2022 |
| HP            | 3396                        | Desktop     | [97720dddd1](https://linux-hardware.org/?probe=97720dddd1) | Jan 10, 2022 |
| MSI           | B150 GAMING M3              | Desktop     | [3514e82b43](https://linux-hardware.org/?probe=3514e82b43) | Jan 07, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [1a04f6b354](https://linux-hardware.org/?probe=1a04f6b354) | Dec 26, 2021 |
| MSI           | MS-AA1511                   | All in one  | [ef477f6784](https://linux-hardware.org/?probe=ef477f6784) | Dec 24, 2021 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [531a29caeb](https://linux-hardware.org/?probe=531a29caeb) | Dec 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f6f5b0f374](https://linux-hardware.org/?probe=f6f5b0f374) | Dec 01, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [b99fd7100e](https://linux-hardware.org/?probe=b99fd7100e) | Nov 28, 2021 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [a86286c5da](https://linux-hardware.org/?probe=a86286c5da) | Nov 24, 2021 |
| Acer          | Okinawa                     | Notebook    | [2953f32ed9](https://linux-hardware.org/?probe=2953f32ed9) | Nov 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [9f4e86b760](https://linux-hardware.org/?probe=9f4e86b760) | Nov 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [07d8d5b1ae](https://linux-hardware.org/?probe=07d8d5b1ae) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [6c7411070d](https://linux-hardware.org/?probe=6c7411070d) | Nov 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [52eb9930ad](https://linux-hardware.org/?probe=52eb9930ad) | Nov 14, 2021 |
| Medion        | MS-7366                     | Desktop     | [da9961f1ee](https://linux-hardware.org/?probe=da9961f1ee) | Nov 04, 2021 |
| HP            | ProBook 470 G0              | Notebook    | [e2c740a317](https://linux-hardware.org/?probe=e2c740a317) | Nov 01, 2021 |
| Acer          | AO725                       | Notebook    | [f6819a066a](https://linux-hardware.org/?probe=f6819a066a) | Oct 31, 2021 |
| ASUSTek       | X540SAA                     | Notebook    | [2ce3b8f43c](https://linux-hardware.org/?probe=2ce3b8f43c) | Oct 27, 2021 |
| Lenovo        | IdeaPad Y570 20091          | Notebook    | [5d292b28e6](https://linux-hardware.org/?probe=5d292b28e6) | Oct 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [63b6ade950](https://linux-hardware.org/?probe=63b6ade950) | Sep 13, 2021 |
| Dell          | G3 3590                     | Notebook    | [caaab11f09](https://linux-hardware.org/?probe=caaab11f09) | Sep 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [1f7bf82ef4](https://linux-hardware.org/?probe=1f7bf82ef4) | Aug 10, 2021 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [4206886abb](https://linux-hardware.org/?probe=4206886abb) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [d244dc6763](https://linux-hardware.org/?probe=d244dc6763) | Jul 28, 2021 |
| eMachines     | eME728                      | Notebook    | [30f7a1ede8](https://linux-hardware.org/?probe=30f7a1ede8) | Jul 27, 2021 |
| eMachines     | eME728                      | Notebook    | [41f6735286](https://linux-hardware.org/?probe=41f6735286) | Jul 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [fb1170efa6](https://linux-hardware.org/?probe=fb1170efa6) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [19f5976aa3](https://linux-hardware.org/?probe=19f5976aa3) | Jul 25, 2021 |
| HP            | 1497                        | Desktop     | [e68557fd01](https://linux-hardware.org/?probe=e68557fd01) | Jul 07, 2021 |
| Dell          | Latitude E7470              | Notebook    | [09cc29de1a](https://linux-hardware.org/?probe=09cc29de1a) | Jun 27, 2021 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [bc2d293d15](https://linux-hardware.org/?probe=bc2d293d15) | Jun 18, 2021 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [ef21ac93c3](https://linux-hardware.org/?probe=ef21ac93c3) | Jun 18, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [c425b0dc44](https://linux-hardware.org/?probe=c425b0dc44) | Jun 01, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [035b3cdc60](https://linux-hardware.org/?probe=035b3cdc60) | May 31, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e9148788a7](https://linux-hardware.org/?probe=e9148788a7) | May 30, 2021 |
| Acer          | Aspire 8950G                | Notebook    | [7955f23581](https://linux-hardware.org/?probe=7955f23581) | May 18, 2021 |
| HP            | ProBook 4710s               | Notebook    | [7c743eff61](https://linux-hardware.org/?probe=7c743eff61) | May 17, 2021 |
| HP            | ProBook 4710s               | Notebook    | [e0c66c6a52](https://linux-hardware.org/?probe=e0c66c6a52) | May 16, 2021 |
| ASRock        | H61M-HVGS                   | Desktop     | [3f3962df59](https://linux-hardware.org/?probe=3f3962df59) | May 16, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [10dd12b38c](https://linux-hardware.org/?probe=10dd12b38c) | May 15, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [30aeb41807](https://linux-hardware.org/?probe=30aeb41807) | May 14, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [57a865992b](https://linux-hardware.org/?probe=57a865992b) | May 10, 2021 |
| HP            | ProBook 470 G2              | Notebook    | [fc85d1a891](https://linux-hardware.org/?probe=fc85d1a891) | May 08, 2021 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [19df1ffb17](https://linux-hardware.org/?probe=19df1ffb17) | Apr 27, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [dba745086d](https://linux-hardware.org/?probe=dba745086d) | Apr 09, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [54a2c5f349](https://linux-hardware.org/?probe=54a2c5f349) | Apr 09, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [f4c0a5e9a8](https://linux-hardware.org/?probe=f4c0a5e9a8) | Mar 25, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [bee3da385c](https://linux-hardware.org/?probe=bee3da385c) | Mar 23, 2021 |
| HP            | 198E                        | Desktop     | [85ba542969](https://linux-hardware.org/?probe=85ba542969) | Mar 10, 2021 |
| HP            | 198E                        | Desktop     | [8a79f9e398](https://linux-hardware.org/?probe=8a79f9e398) | Mar 10, 2021 |
| Dell          | G3 3590                     | Notebook    | [3576fa9deb](https://linux-hardware.org/?probe=3576fa9deb) | Feb 26, 2021 |
| Dell          | G3 3590                     | Notebook    | [c5592b0bc0](https://linux-hardware.org/?probe=c5592b0bc0) | Feb 26, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [9b37eaa9f8](https://linux-hardware.org/?probe=9b37eaa9f8) | Feb 02, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [7d18048067](https://linux-hardware.org/?probe=7d18048067) | Jan 26, 2021 |
| Acer          | AO756                       | Notebook    | [d734ecb46e](https://linux-hardware.org/?probe=d734ecb46e) | Jan 05, 2021 |
| Acer          | AO756                       | Notebook    | [be84cd377c](https://linux-hardware.org/?probe=be84cd377c) | Jan 05, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [4914bab0b2](https://linux-hardware.org/?probe=4914bab0b2) | Jan 03, 2021 |
| HP            | 1496                        | Desktop     | [7d2d9cd210](https://linux-hardware.org/?probe=7d2d9cd210) | Dec 22, 2020 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [1cfdffe4cb](https://linux-hardware.org/?probe=1cfdffe4cb) | Dec 22, 2020 |
| Acer          | Aspire 5349                 | Notebook    | [e52d1fe780](https://linux-hardware.org/?probe=e52d1fe780) | Dec 01, 2020 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | Notebook    | [3cd2e0b42b](https://linux-hardware.org/?probe=3cd2e0b42b) | Nov 29, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [d5cb1091b6](https://linux-hardware.org/?probe=d5cb1091b6) | Nov 21, 2020 |
| ASUSTek       | H97-PRO                     | Desktop     | [5532ead8e7](https://linux-hardware.org/?probe=5532ead8e7) | Nov 21, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [092c6bbcaa](https://linux-hardware.org/?probe=092c6bbcaa) | Nov 17, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [2fbaebc961](https://linux-hardware.org/?probe=2fbaebc961) | Nov 16, 2020 |
| Acer          | Aspire 8950G                | Notebook    | [47e8b425f8](https://linux-hardware.org/?probe=47e8b425f8) | Nov 15, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [986307a038](https://linux-hardware.org/?probe=986307a038) | Nov 15, 2020 |
| Acer          | Aspire 8950G                | Notebook    | [bae73407d5](https://linux-hardware.org/?probe=bae73407d5) | Nov 11, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [78a6736f7b](https://linux-hardware.org/?probe=78a6736f7b) | Nov 07, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [61f58ab0e6](https://linux-hardware.org/?probe=61f58ab0e6) | Nov 07, 2020 |
| HP            | Laptop 15-rb0xx             | Notebook    | [aaa00c2c2f](https://linux-hardware.org/?probe=aaa00c2c2f) | Nov 05, 2020 |
| HP            | 3032h                       | Desktop     | [63d3c61c19](https://linux-hardware.org/?probe=63d3c61c19) | Nov 03, 2020 |
| HP            | 3032h                       | Desktop     | [d8cfe55684](https://linux-hardware.org/?probe=d8cfe55684) | Nov 03, 2020 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [1f8e16d74f](https://linux-hardware.org/?probe=1f8e16d74f) | Oct 25, 2020 |
| Acer          | Aspire 7741                 | Notebook    | [a87b79b8e8](https://linux-hardware.org/?probe=a87b79b8e8) | Oct 01, 2020 |
| Lenovo        | Legion 7 15IMHg05 81YU      | Notebook    | [e8a84ca3be](https://linux-hardware.org/?probe=e8a84ca3be) | Oct 01, 2020 |
| ASUSTek       | Z170-P                      | Desktop     | [188328b998](https://linux-hardware.org/?probe=188328b998) | Sep 27, 2020 |
| HP            | 8446                        | All in one  | [a12a0781b1](https://linux-hardware.org/?probe=a12a0781b1) | Sep 25, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [35560a3a70](https://linux-hardware.org/?probe=35560a3a70) | Sep 16, 2020 |
| Unknown       | Unknown                     | Notebook    | [c24817ee80](https://linux-hardware.org/?probe=c24817ee80) | Sep 15, 2020 |
| ECS           | G31T-M7                     | Desktop     | [70c5208ec6](https://linux-hardware.org/?probe=70c5208ec6) | Sep 13, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2726ac41f8](https://linux-hardware.org/?probe=2726ac41f8) | Sep 07, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [92e454c839](https://linux-hardware.org/?probe=92e454c839) | Sep 07, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cac26af0fc](https://linux-hardware.org/?probe=cac26af0fc) | Sep 07, 2020 |
| ASUSTek       | X75VBP                      | Notebook    | [2556ede7e8](https://linux-hardware.org/?probe=2556ede7e8) | Aug 14, 2020 |
| Dell          | 0M858N A01                  | Desktop     | [5b7ae4f768](https://linux-hardware.org/?probe=5b7ae4f768) | Aug 13, 2020 |
| Lenovo        | G505 20240                  | Notebook    | [828da8bdbe](https://linux-hardware.org/?probe=828da8bdbe) | Aug 10, 2020 |
| HP            | ENVY 6                      | Notebook    | [a703adc052](https://linux-hardware.org/?probe=a703adc052) | Aug 08, 2020 |
| HP            | ENVY 6                      | Notebook    | [d64f914478](https://linux-hardware.org/?probe=d64f914478) | Aug 08, 2020 |
| Dell          | 0RF703                      | Desktop     | [e23b194d28](https://linux-hardware.org/?probe=e23b194d28) | Jul 25, 2020 |
| ASUSTek       | Z97-P                       | Desktop     | [d0375fe030](https://linux-hardware.org/?probe=d0375fe030) | Jul 15, 2020 |
| Acer          | Aspire M1200                | Desktop     | [9311c4fa37](https://linux-hardware.org/?probe=9311c4fa37) | Jun 27, 2020 |
| Acer          | Aspire M1200                | Desktop     | [8d9a1aefd5](https://linux-hardware.org/?probe=8d9a1aefd5) | Jun 27, 2020 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [1a6102d9f3](https://linux-hardware.org/?probe=1a6102d9f3) | Jun 17, 2020 |
| HP            | ENVY TS 15                  | Notebook    | [bd072980c8](https://linux-hardware.org/?probe=bd072980c8) | Jun 02, 2020 |
| NEC Comput... | VERSAP550 NN951700753       | Notebook    | [ccd46d5757](https://linux-hardware.org/?probe=ccd46d5757) | May 29, 2020 |
| Acer          | Aspire M1200                | Desktop     | [2cbc71cc6f](https://linux-hardware.org/?probe=2cbc71cc6f) | May 24, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [05094356e1](https://linux-hardware.org/?probe=05094356e1) | May 22, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [9f6782d583](https://linux-hardware.org/?probe=9f6782d583) | May 14, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [a8fb846d8b](https://linux-hardware.org/?probe=a8fb846d8b) | May 14, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [6935018ae2](https://linux-hardware.org/?probe=6935018ae2) | May 14, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [31f5dfadff](https://linux-hardware.org/?probe=31f5dfadff) | May 04, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [c668c517d8](https://linux-hardware.org/?probe=c668c517d8) | Apr 24, 2020 |
| HP            | Compaq CQ58                 | Notebook    | [82172cc7b5](https://linux-hardware.org/?probe=82172cc7b5) | Apr 21, 2020 |
| ASUSTek       | X550ZE                      | Notebook    | [c3165ccdcd](https://linux-hardware.org/?probe=c3165ccdcd) | Apr 21, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [4e3e7a0cca](https://linux-hardware.org/?probe=4e3e7a0cca) | Apr 20, 2020 |
| HP            | 255 G2                      | Notebook    | [2e24d05e40](https://linux-hardware.org/?probe=2e24d05e40) | Apr 19, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [6e83174540](https://linux-hardware.org/?probe=6e83174540) | Apr 18, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [878a9628b9](https://linux-hardware.org/?probe=878a9628b9) | Apr 18, 2020 |
| Gigabyte      | nForce                      | Desktop     | [46e8276491](https://linux-hardware.org/?probe=46e8276491) | Apr 03, 2020 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [fa5624c697](https://linux-hardware.org/?probe=fa5624c697) | Mar 27, 2020 |
| Acer          | Aspire 9300                 | Notebook    | [de8a03d251](https://linux-hardware.org/?probe=de8a03d251) | Mar 26, 2020 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [0dbb663114](https://linux-hardware.org/?probe=0dbb663114) | Mar 26, 2020 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [ce73a67dba](https://linux-hardware.org/?probe=ce73a67dba) | Mar 26, 2020 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [84bed079c2](https://linux-hardware.org/?probe=84bed079c2) | Mar 23, 2020 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [10793053f1](https://linux-hardware.org/?probe=10793053f1) | Mar 23, 2020 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [e8e644cb4c](https://linux-hardware.org/?probe=e8e644cb4c) | Mar 09, 2020 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [7121b34b5e](https://linux-hardware.org/?probe=7121b34b5e) | Feb 21, 2020 |
| ASUSTek       | X751MD                      | Notebook    | [cdb3c77ebd](https://linux-hardware.org/?probe=cdb3c77ebd) | Feb 07, 2020 |
| MSI           | GF615M-P33                  | Desktop     | [34605f2e7f](https://linux-hardware.org/?probe=34605f2e7f) | Feb 06, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [815e8a2b8e](https://linux-hardware.org/?probe=815e8a2b8e) | Jan 04, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [64c7222709](https://linux-hardware.org/?probe=64c7222709) | Dec 22, 2019 |
| Dell          | 0RF703                      | Desktop     | [3cc8664913](https://linux-hardware.org/?probe=3cc8664913) | Nov 09, 2019 |
| Pegatron      | Eureka3                     | Desktop     | [5d42e73d08](https://linux-hardware.org/?probe=5d42e73d08) | Oct 20, 2019 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [5dd5ad47e3](https://linux-hardware.org/?probe=5dd5ad47e3) | Sep 06, 2019 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [8bce9c814b](https://linux-hardware.org/?probe=8bce9c814b) | Sep 05, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1db130e5eb](https://linux-hardware.org/?probe=1db130e5eb) | Aug 30, 2019 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [761fad2410](https://linux-hardware.org/?probe=761fad2410) | Aug 06, 2019 |
| Dell          | 0RF703                      | Desktop     | [e97de552d8](https://linux-hardware.org/?probe=e97de552d8) | Jul 29, 2019 |
| Dell          | 0RF703                      | Desktop     | [08019d8b5f](https://linux-hardware.org/?probe=08019d8b5f) | Jul 29, 2019 |
| Dell          | 0MM599                      | Desktop     | [0b9fef01ec](https://linux-hardware.org/?probe=0b9fef01ec) | Jun 19, 2019 |
| Dell          | 0MM599                      | Desktop     | [8376d2c77c](https://linux-hardware.org/?probe=8376d2c77c) | Jun 19, 2019 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [aa5f7a836b](https://linux-hardware.org/?probe=aa5f7a836b) | May 04, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3aed29ae25](https://linux-hardware.org/?probe=3aed29ae25) | Apr 27, 2019 |
| HP            | 0A64h                       | Desktop     | [ab563902ff](https://linux-hardware.org/?probe=ab563902ff) | Apr 22, 2019 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [3ce6d97f47](https://linux-hardware.org/?probe=3ce6d97f47) | Apr 21, 2019 |
| Gigabyte      | Z390 UD                     | Desktop     | [48041296ca](https://linux-hardware.org/?probe=48041296ca) | Mar 15, 2019 |
| Sony          | VGN-BX41VN                  | Notebook    | [3a190d628a](https://linux-hardware.org/?probe=3a190d628a) | Dec 02, 2018 |
| Sony          | VGN-BX41VN                  | Notebook    | [7f3d5f5bf2](https://linux-hardware.org/?probe=7f3d5f5bf2) | Dec 02, 2018 |
| Acer          | Aspire A315-31              | Notebook    | [e67c4f6668](https://linux-hardware.org/?probe=e67c4f6668) | Nov 18, 2018 |
| Acer          | Aspire A315-31              | Notebook    | [a46cebd58a](https://linux-hardware.org/?probe=a46cebd58a) | Nov 18, 2018 |
| HP            | 250 G6 Notebook PC          | Notebook    | [e8386ee291](https://linux-hardware.org/?probe=e8386ee291) | Sep 22, 2018 |
| HP            | 250 G6 Notebook PC          | Notebook    | [fa8425dcca](https://linux-hardware.org/?probe=fa8425dcca) | Aug 12, 2018 |
| ASUSTek       | M2N-SLI                     | Desktop     | [77800cbaf6](https://linux-hardware.org/?probe=77800cbaf6) | Mar 30, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 21        | 14.89%  |
| Ubuntu 18.04        | 9         | 6.38%   |
| Pop!_OS 21.04       | 6         | 4.26%   |
| OpenMandriva 4.3    | 6         | 4.26%   |
| Ubuntu 22.04        | 5         | 3.55%   |
| Manjaro             | 4         | 2.84%   |
| Linux Mint 20.2     | 4         | 2.84%   |
| Linux Mint 19.3     | 4         | 2.84%   |
| Zorin 16            | 3         | 2.13%   |
| Xubuntu 20.04       | 3         | 2.13%   |
| Ubuntu 20.10        | 3         | 2.13%   |
| Pop!_OS 20.04       | 3         | 2.13%   |
| Linux Mint 19.1     | 3         | 2.13%   |
| KDE neon 20.04      | 3         | 2.13%   |
| Fedora 32           | 3         | 2.13%   |
| Debian 10           | 3         | 2.13%   |
| ArcoLinux Rolling   | 3         | 2.13%   |
| Zorin 15            | 2         | 1.42%   |
| Ubuntu 22.10        | 2         | 1.42%   |
| Ubuntu 21.10        | 2         | 1.42%   |
| Ubuntu 19.04        | 2         | 1.42%   |
| ROSA R10            | 2         | 1.42%   |
| Pop!_OS 20.10       | 2         | 1.42%   |
| OpenMandriva 23.01  | 2         | 1.42%   |
| Lubuntu 19.10       | 2         | 1.42%   |
| Linux Mint 21.1     | 2         | 1.42%   |
| Linux Mint 21       | 2         | 1.42%   |
| Linux Mint 20.1     | 2         | 1.42%   |
| Fedora 37           | 2         | 1.42%   |
| Fedora 33           | 2         | 1.42%   |
| Endless 3.7.8       | 2         | 1.42%   |
| Arch Rolling        | 2         | 1.42%   |
| Xubuntu 18.04       | 1         | 0.71%   |
| Xero Rolling        | 1         | 0.71%   |
| Ubuntu Unity 21.10  | 1         | 0.71%   |
| Ubuntu Unity 18.04  | 1         | 0.71%   |
| Ubuntu Studio 20.04 | 1         | 0.71%   |
| Ubuntu 21.04        | 1         | 0.71%   |
| Ubuntu 16.04        | 1         | 0.71%   |
| PureOS 9.0          | 1         | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 42        | 30.88%  |
| Linux Mint    | 17        | 12.5%   |
| Pop!_OS       | 12        | 8.82%   |
| OpenMandriva  | 8         | 5.88%   |
| Fedora        | 8         | 5.88%   |
| Manjaro       | 7         | 5.15%   |
| Debian        | 6         | 4.41%   |
| Zorin         | 5         | 3.68%   |
| Endless       | 5         | 3.68%   |
| Xubuntu       | 4         | 2.94%   |
| KDE neon      | 4         | 2.94%   |
| Lubuntu       | 3         | 2.21%   |
| ArcoLinux     | 3         | 2.21%   |
| Arch          | 3         | 2.21%   |
| Ubuntu Unity  | 2         | 1.47%   |
| ROSA          | 2         | 1.47%   |
| Xero          | 1         | 0.74%   |
| Ubuntu Studio | 1         | 0.74%   |
| PureOS        | 1         | 0.74%   |
| Kubuntu       | 1         | 0.74%   |
| Elementary    | 1         | 0.74%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 6         | 3.97%   |
| 5.3.0-28-generic                | 5         | 3.31%   |
| 5.4.0-52-generic                | 4         | 2.65%   |
| 5.3.0-46-generic                | 3         | 1.99%   |
| 5.15.0-56-generic               | 3         | 1.99%   |
| 5.15.0-48-generic               | 3         | 1.99%   |
| 5.13.0-39-generic               | 3         | 1.99%   |
| 6.1.1-desktop-1omv2290          | 2         | 1.32%   |
| 5.8.0-7630-generic              | 2         | 1.32%   |
| 5.8.0-59-generic                | 2         | 1.32%   |
| 5.4.0-89-generic                | 2         | 1.32%   |
| 5.4.0-67-generic                | 2         | 1.32%   |
| 5.3.0-42-generic                | 2         | 1.32%   |
| 5.15.0-50-generic               | 2         | 1.32%   |
| 5.15.0-39-generic               | 2         | 1.32%   |
| 5.15.0-25-generic               | 2         | 1.32%   |
| 5.13.0-7620-generic             | 2         | 1.32%   |
| 5.13.0-7614-generic             | 2         | 1.32%   |
| 5.11.0-40-generic               | 2         | 1.32%   |
| 5.11.0-38-generic               | 2         | 1.32%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 1.32%   |
| 4.19.0-13-amd64                 | 2         | 1.32%   |
| 4.18.0-15-generic               | 2         | 1.32%   |
| 4.15.0-94-generic               | 2         | 1.32%   |
| 4.15.0-47-generic               | 2         | 1.32%   |
| 4.15.0-20-generic               | 2         | 1.32%   |
| 6.0.8-arch1-1                   | 1         | 0.66%   |
| 6.0.8-300.fc37.x86_64           | 1         | 0.66%   |
| 6.0.15-300.fc37.x86_64          | 1         | 0.66%   |
| 6.0.12-arch1-1                  | 1         | 0.66%   |
| 5.9.8-2-MANJARO                 | 1         | 0.66%   |
| 5.9.0-3-amd64                   | 1         | 0.66%   |
| 5.8.9-200.fc32.x86_64           | 1         | 0.66%   |
| 5.8.11-200.fc32.x86_64          | 1         | 0.66%   |
| 5.8.0-53-generic                | 1         | 0.66%   |
| 5.8.0-49-generic                | 1         | 0.66%   |
| 5.8.0-44-generic                | 1         | 0.66%   |
| 5.8.0-34-generic                | 1         | 0.66%   |
| 5.8.0-26-generic                | 1         | 0.66%   |
| 5.8.0-19-generic                | 1         | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 25        | 17.12%  |
| 5.13.0  | 13        | 8.9%    |
| 5.15.0  | 12        | 8.22%   |
| 5.3.0   | 11        | 7.53%   |
| 5.8.0   | 10        | 6.85%   |
| 4.15.0  | 10        | 6.85%   |
| 5.11.0  | 9         | 6.16%   |
| 5.16.7  | 6         | 4.11%   |
| 5.0.0   | 5         | 3.42%   |
| 4.18.0  | 4         | 2.74%   |
| 6.1.1   | 2         | 1.37%   |
| 6.0.8   | 2         | 1.37%   |
| 5.19.0  | 2         | 1.37%   |
| 5.10.0  | 2         | 1.37%   |
| 4.9.60  | 2         | 1.37%   |
| 4.19.0  | 2         | 1.37%   |
| 6.0.15  | 1         | 0.68%   |
| 6.0.12  | 1         | 0.68%   |
| 5.9.8   | 1         | 0.68%   |
| 5.9.0   | 1         | 0.68%   |
| 5.8.9   | 1         | 0.68%   |
| 5.8.11  | 1         | 0.68%   |
| 5.7.0   | 1         | 0.68%   |
| 5.6.6   | 1         | 0.68%   |
| 5.4.52  | 1         | 0.68%   |
| 5.4.33  | 1         | 0.68%   |
| 5.4.23  | 1         | 0.68%   |
| 5.19.8  | 1         | 0.68%   |
| 5.16.14 | 1         | 0.68%   |
| 5.16.11 | 1         | 0.68%   |
| 5.15.94 | 1         | 0.68%   |
| 5.15.89 | 1         | 0.68%   |
| 5.15.23 | 1         | 0.68%   |
| 5.15.11 | 1         | 0.68%   |
| 5.15.10 | 1         | 0.68%   |
| 5.14.18 | 1         | 0.68%   |
| 5.13.9  | 1         | 0.68%   |
| 5.11.19 | 1         | 0.68%   |
| 5.11.18 | 1         | 0.68%   |
| 5.11.16 | 1         | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 28        | 19.58%  |
| 5.15    | 16        | 11.19%  |
| 5.13    | 14        | 9.79%   |
| 5.8     | 12        | 8.39%   |
| 5.11    | 12        | 8.39%   |
| 5.3     | 11        | 7.69%   |
| 4.15    | 10        | 6.99%   |
| 5.16    | 8         | 5.59%   |
| 5.10    | 5         | 3.5%    |
| 5.0     | 5         | 3.5%    |
| 4.18    | 4         | 2.8%    |
| 6.0     | 3         | 2.1%    |
| 5.19    | 3         | 2.1%    |
| 4.9     | 3         | 2.1%    |
| 6.1     | 2         | 1.4%    |
| 5.9     | 2         | 1.4%    |
| 4.19    | 2         | 1.4%    |
| 5.7     | 1         | 0.7%    |
| 5.6     | 1         | 0.7%    |
| 5.14    | 1         | 0.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 124       | 93.94%  |
| i686    | 7         | 5.3%    |
| aarch64 | 1         | 0.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 69        | 50.36%  |
| XFCE       | 16        | 11.68%  |
| Unknown    | 15        | 10.95%  |
| KDE5       | 14        | 10.22%  |
| X-Cinnamon | 8         | 5.84%   |
| KDE        | 3         | 2.19%   |
| Unity      | 2         | 1.46%   |
| MATE       | 2         | 1.46%   |
| LXQt       | 2         | 1.46%   |
| KDE4       | 2         | 1.46%   |
| Pantheon   | 1         | 0.73%   |
| LXDE       | 1         | 0.73%   |
| Cinnamon   | 1         | 0.73%   |
| bspwm      | 1         | 0.73%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 108       | 80.6%   |
| Wayland | 20        | 14.93%  |
| Unknown | 6         | 4.48%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 82        | 59.42%  |
| SDDM    | 17        | 12.32%  |
| GDM     | 14        | 10.14%  |
| LightDM | 10        | 7.25%   |
| GDM3    | 9         | 6.52%   |
| TDM     | 4         | 2.9%    |
| KDM     | 2         | 1.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 95        | 70.37%  |
| Unknown | 16        | 11.85%  |
| bs_BA   | 8         | 5.93%   |
| hr_HR   | 6         | 4.44%   |
| sr_RS   | 2         | 1.48%   |
| en_AU   | 2         | 1.48%   |
| C       | 2         | 1.48%   |
| it_IT   | 1         | 0.74%   |
| en_GB   | 1         | 0.74%   |
| en_CA   | 1         | 0.74%   |
| de_CH   | 1         | 0.74%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 86        | 64.66%  |
| EFI  | 47        | 35.34%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 108       | 81.2%   |
| Overlay | 9         | 6.77%   |
| Btrfs   | 8         | 6.02%   |
| Unknown | 7         | 5.26%   |
| Ext2    | 1         | 0.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 92        | 68.15%  |
| GPT     | 32        | 23.7%   |
| MBR     | 11        | 8.15%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 119       | 90.84%  |
| Yes       | 12        | 9.16%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 101       | 77.1%   |
| Yes       | 30        | 22.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 35        | 26.72%  |
| ASUSTek Computer    | 30        | 22.9%   |
| Lenovo              | 18        | 13.74%  |
| Dell                | 13        | 9.92%   |
| Acer                | 11        | 8.4%    |
| Gigabyte Technology | 7         | 5.34%   |
| MSI                 | 3         | 2.29%   |
| Fujitsu Siemens     | 2         | 1.53%   |
| Wistron             | 1         | 0.76%   |
| Toshiba             | 1         | 0.76%   |
| Sony                | 1         | 0.76%   |
| Pegatron            | 1         | 0.76%   |
| NEC Computers       | 1         | 0.76%   |
| Microsoft           | 1         | 0.76%   |
| Medion              | 1         | 0.76%   |
| HUAWEI              | 1         | 0.76%   |
| eMachines           | 1         | 0.76%   |
| ECS                 | 1         | 0.76%   |
| ASRock              | 1         | 0.76%   |
| Unknown             | 1         | 0.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| ASUS All Series                                   | 4         | 3.05%   |
| HP EliteBook 8460p                                | 2         | 1.53%   |
| Dell OptiPlex 745                                 | 2         | 1.53%   |
| Dell G3 3590                                      | 2         | 1.53%   |
| ASUS VivoBook_ASUSLaptop X509DA_D509DA            | 2         | 1.53%   |
| ASUS P8H61-M LX3 R2.0                             | 2         | 1.53%   |
| ASUS P5KPL-AM SE                                  | 2         | 1.53%   |
| Wistron ProLiant ML110 G5                         | 1         | 0.76%   |
| Toshiba Satellite C850-1GF                        | 1         | 0.76%   |
| Sony VGN-BX41VN                                   | 1         | 0.76%   |
| Pegatron VS170AA-UUZ p6244ch                      | 1         | 0.76%   |
| NEC Computers VERSAP550 NN951700753               | 1         | 0.76%   |
| MSI MS-AA1511                                     | 1         | 0.76%   |
| MSI MS-7978                                       | 1         | 0.76%   |
| MSI MS-7597                                       | 1         | 0.76%   |
| Microsoft Surface Pro 4                           | 1         | 0.76%   |
| Medion MS-7366                                    | 1         | 0.76%   |
| Lenovo Yoga 920-13IKB 80Y7                        | 1         | 0.76%   |
| Lenovo Yoga 910-13IKB 80VF                        | 1         | 0.76%   |
| Lenovo ThinkPad X301 277418G                      | 1         | 0.76%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A7008AMZ          | 1         | 0.76%   |
| Lenovo ThinkPad T430 2349G2G                      | 1         | 0.76%   |
| Lenovo ThinkPad T420 4180WAP                      | 1         | 0.76%   |
| Lenovo ThinkPad T14s Gen 1 20UH0056SC             | 1         | 0.76%   |
| Lenovo ThinkPad S1 Yoga 20CD0038MZ                | 1         | 0.76%   |
| Lenovo ThinkPad E15 Gen 2 20TD003LSC              | 1         | 0.76%   |
| Lenovo Legion 7 15IMHg05 81YU                     | 1         | 0.76%   |
| Lenovo Legion 5 Pro 16IAH7H 82RF                  | 1         | 0.76%   |
| Lenovo IdeaPad Y570 20091                         | 1         | 0.76%   |
| Lenovo IdeaPad L340-15IWL 81LG                    | 1         | 0.76%   |
| Lenovo IdeaPad C340-14IWL 81N4                    | 1         | 0.76%   |
| Lenovo IdeaPad 330-15IKB 81DE                     | 1         | 0.76%   |
| Lenovo IdeaPad 320-15IKB 81BG                     | 1         | 0.76%   |
| Lenovo IdeaPad 110S-11IBR 80WG                    | 1         | 0.76%   |
| Lenovo G505 20240                                 | 1         | 0.76%   |
| HUAWEI BOHK-WAX9X                                 | 1         | 0.76%   |
| HP ZBook Firefly 14 inch G8 Mobile Workstation PC | 1         | 0.76%   |
| HP ZBook 15 G4                                    | 1         | 0.76%   |
| HP ProDesk 400 G2 MT (TPM DP)                     | 1         | 0.76%   |
| HP ProBook 6560b                                  | 1         | 0.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| HP EliteBook            | 9         | 6.87%   |
| HP Compaq               | 8         | 6.11%   |
| Acer Aspire             | 8         | 6.11%   |
| Lenovo ThinkPad         | 7         | 5.34%   |
| Lenovo IdeaPad          | 6         | 4.58%   |
| HP ProBook              | 5         | 3.82%   |
| ASUS VivoBook           | 4         | 3.05%   |
| ASUS All                | 4         | 3.05%   |
| HP ENVY                 | 3         | 2.29%   |
| Dell OptiPlex           | 3         | 2.29%   |
| Dell Latitude           | 3         | 2.29%   |
| Lenovo Yoga             | 2         | 1.53%   |
| Lenovo Legion           | 2         | 1.53%   |
| HP ZBook                | 2         | 1.53%   |
| HP 250                  | 2         | 1.53%   |
| Dell XPS                | 2         | 1.53%   |
| Dell Inspiron           | 2         | 1.53%   |
| Dell G3                 | 2         | 1.53%   |
| ASUS TUF                | 2         | 1.53%   |
| ASUS PRIME              | 2         | 1.53%   |
| ASUS P8H61-M            | 2         | 1.53%   |
| ASUS P5KPL-AM           | 2         | 1.53%   |
| ASUS P5G41T-M           | 2         | 1.53%   |
| Wistron ProLiant        | 1         | 0.76%   |
| Toshiba Satellite       | 1         | 0.76%   |
| Sony VGN-BX41VN         | 1         | 0.76%   |
| Pegatron VS170AA-UUZ    | 1         | 0.76%   |
| NEC Computers VERSAP550 | 1         | 0.76%   |
| MSI MS-AA1511           | 1         | 0.76%   |
| MSI MS-7978             | 1         | 0.76%   |
| MSI MS-7597             | 1         | 0.76%   |
| Microsoft Surface       | 1         | 0.76%   |
| Medion MS-7366          | 1         | 0.76%   |
| Lenovo G505             | 1         | 0.76%   |
| HUAWEI BOHK-WAX9X       | 1         | 0.76%   |
| HP ProDesk              | 1         | 0.76%   |
| HP Pavilion             | 1         | 0.76%   |
| HP Laptop               | 1         | 0.76%   |
| HP All-in-One           | 1         | 0.76%   |
| HP 550                  | 1         | 0.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 15        | 11.45%  |
| 2019    | 12        | 9.16%   |
| 2012    | 12        | 9.16%   |
| 2016    | 11        | 8.4%    |
| 2013    | 10        | 7.63%   |
| 2014    | 9         | 6.87%   |
| 2009    | 9         | 6.87%   |
| 2018    | 8         | 6.11%   |
| 2017    | 8         | 6.11%   |
| 2020    | 6         | 4.58%   |
| 2008    | 6         | 4.58%   |
| 2007    | 6         | 4.58%   |
| 2010    | 4         | 3.05%   |
| 2021    | 3         | 2.29%   |
| 2015    | 3         | 2.29%   |
| 2006    | 3         | 2.29%   |
| 2005    | 3         | 2.29%   |
| 2022    | 2         | 1.53%   |
| Unknown | 1         | 0.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 78        | 59.54%  |
| Desktop     | 45        | 34.35%  |
| Convertible | 5         | 3.82%   |
| All in one  | 2         | 1.53%   |
| Tablet      | 1         | 0.76%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 125       | 94.7%   |
| Enabled  | 7         | 5.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 131       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 39        | 29.32%  |
| 3.01-4.0    | 25        | 18.8%   |
| 16.01-24.0  | 20        | 15.04%  |
| 8.01-16.0   | 19        | 14.29%  |
| 1.01-2.0    | 16        | 12.03%  |
| 2.01-3.0    | 6         | 4.51%   |
| 32.01-64.0  | 3         | 2.26%   |
| 64.01-256.0 | 2         | 1.5%    |
| 0.51-1.0    | 2         | 1.5%    |
| 0.01-0.5    | 1         | 0.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 58        | 40.85%  |
| 2.01-3.0  | 34        | 23.94%  |
| 4.01-8.0  | 15        | 10.56%  |
| 0.51-1.0  | 15        | 10.56%  |
| 3.01-4.0  | 14        | 9.86%   |
| 8.01-16.0 | 4         | 2.82%   |
| 0.01-0.5  | 2         | 1.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 96        | 71.11%  |
| 2      | 32        | 23.7%   |
| 3      | 4         | 2.96%   |
| 5      | 1         | 0.74%   |
| 4      | 1         | 0.74%   |
| 0      | 1         | 0.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 54.89%  |
| Yes       | 60        | 45.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 111       | 83.46%  |
| No        | 22        | 16.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 72.52%  |
| No        | 36        | 27.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 51.52%  |
| No        | 64        | 48.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| Bosnia and Herzegovina | 131       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sarajevo          | 41        | 30.37%  |
| Banja Luka        | 23        | 17.04%  |
| Tuzla             | 7         | 5.19%   |
| Gracanica         | 5         | 3.7%    |
| Zenica            | 4         | 2.96%   |
| Doboj             | 4         | 2.96%   |
| Teslic            | 3         | 2.22%   |
| Prijedor          | 3         | 2.22%   |
| Novi Travnik      | 3         | 2.22%   |
| Brcko             | 3         | 2.22%   |
| Zepce             | 2         | 1.48%   |
| Srebrenik         | 2         | 1.48%   |
| Prnjavor          | 2         | 1.48%   |
| Maglaj            | 2         | 1.48%   |
| Lukavac           | 2         | 1.48%   |
| Gradacac          | 2         | 1.48%   |
| Bijeljina         | 2         | 1.48%   |
| Banovici          | 2         | 1.48%   |
| Zvornik           | 1         | 0.74%   |
| Zivinice          | 1         | 0.74%   |
| Vitez             | 1         | 0.74%   |
| Velika KladuÅ¡a | 1         | 0.74%   |
| Trebinje          | 1         | 0.74%   |
| Tarcin            | 1         | 0.74%   |
| Stjepan-Polje     | 1         | 0.74%   |
| Solina            | 1         | 0.74%   |
| Posusje           | 1         | 0.74%   |
| Pale              | 1         | 0.74%   |
| Orahovica Donja   | 1         | 0.74%   |
| Nova Topola       | 1         | 0.74%   |
| Nevesinje         | 1         | 0.74%   |
| Mostar            | 1         | 0.74%   |
| Lukavica          | 1         | 0.74%   |
| Ljubuski          | 1         | 0.74%   |
| Kobilja Glava     | 1         | 0.74%   |
| Jablanica         | 1         | 0.74%   |
| Ilidza            | 1         | 0.74%   |
| Grude             | 1         | 0.74%   |
| Goražde          | 1         | 0.74%   |
| Foca              | 1         | 0.74%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 25        | 36     | 14.88%  |
| Kingston            | 23        | 27     | 13.69%  |
| Samsung Electronics | 22        | 29     | 13.1%   |
| Seagate             | 20        | 27     | 11.9%   |
| Toshiba             | 17        | 18     | 10.12%  |
| Hitachi             | 14        | 14     | 8.33%   |
| SanDisk             | 9         | 11     | 5.36%   |
| SK hynix            | 8         | 9      | 4.76%   |
| Unknown             | 4         | 4      | 2.38%   |
| Intel               | 4         | 4      | 2.38%   |
| China               | 3         | 5      | 1.79%   |
| Micron Technology   | 2         | 4      | 1.19%   |
| A-DATA Technology   | 2         | 2      | 1.19%   |
| Vaseky              | 1         | 1      | 0.6%    |
| Transcend           | 1         | 2      | 0.6%    |
| Team                | 1         | 1      | 0.6%    |
| Patriot             | 1         | 1      | 0.6%    |
| ORGE                | 1         | 1      | 0.6%    |
| OCZ                 | 1         | 2      | 0.6%    |
| Maxtor              | 1         | 1      | 0.6%    |
| LITEON              | 1         | 1      | 0.6%    |
| KIOXIA              | 1         | 1      | 0.6%    |
| Intenso             | 1         | 1      | 0.6%    |
| HGST                | 1         | 1      | 0.6%    |
| GOODRAM             | 1         | 1      | 0.6%    |
| Fujitsu             | 1         | 1      | 0.6%    |
| Crucial             | 1         | 1      | 0.6%    |
| ASMT                | 1         | 1      | 0.6%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB           | 5         | 2.81%   |
| Kingston SA400S37240G 240GB SSD  | 5         | 2.81%   |
| SK hynix NVMe SSD Drive 512GB    | 3         | 1.69%   |
| Kingston SHFS37A120G 120GB SSD   | 3         | 1.69%   |
| Kingston SA400S37120G 120GB SSD  | 3         | 1.69%   |
| Hitachi HDS721050CLA362 500GB    | 3         | 1.69%   |
| WDC WD800JD-00MSA1 80GB          | 2         | 1.12%   |
| WDC WD3200AAJS-00L7A0 320GB      | 2         | 1.12%   |
| Unknown SD/MMC/MS PRO 16GB       | 2         | 1.12%   |
| Unknown MMC Card  32GB           | 2         | 1.12%   |
| Toshiba DT01ACA100 1TB           | 2         | 1.12%   |
| Toshiba DT01ACA050 500GB         | 2         | 1.12%   |
| Seagate ST3500413AS 500GB        | 2         | 1.12%   |
| Seagate ST250LT021-1AF14C 250GB  | 2         | 1.12%   |
| SanDisk NVMe SSD Drive 256GB     | 2         | 1.12%   |
| Samsung NVMe SSD Drive 512GB     | 2         | 1.12%   |
| Kingston SHFS37A240G 240GB SSD   | 2         | 1.12%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1         | 0.56%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 0.56%   |
| WDC WDS240G1G0A-00SS50 240GB SSD | 1         | 0.56%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD | 1         | 0.56%   |
| WDC WD800JD-75MSA3 80GB          | 1         | 0.56%   |
| WDC WD800JD-60LSA5 80GB          | 1         | 0.56%   |
| WDC WD7500BPVX-22JC3T0 752GB     | 1         | 0.56%   |
| WDC WD7500BPVT-75HXZT3 752GB     | 1         | 0.56%   |
| WDC WD7500BPVT-24HXZT3 752GB     | 1         | 0.56%   |
| WDC WD7500AACS-00D6B0 752GB      | 1         | 0.56%   |
| WDC WD5000LPVT-75G33T0 500GB     | 1         | 0.56%   |
| WDC WD5000LPVT-22G33T0 500GB     | 1         | 0.56%   |
| WDC WD5000BEKT-22KA9T0 500GB     | 1         | 0.56%   |
| WDC WD5000AZLX-60K2TA0 500GB     | 1         | 0.56%   |
| WDC WD5000AVDS-73U7B1 500GB      | 1         | 0.56%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1         | 0.56%   |
| WDC WD40EZRZ-75GXCB0 4TB         | 1         | 0.56%   |
| WDC WD40EZAZ-00ZGHB0 4TB         | 1         | 0.56%   |
| WDC WD3200SD-01KNB0 320GB        | 1         | 0.56%   |
| WDC WD20EARX-00PASB0 2TB         | 1         | 0.56%   |
| WDC WD2000JD-00HBB0 200GB        | 1         | 0.56%   |
| WDC WD1600BEVT-22ZCT0 160GB      | 1         | 0.56%   |
| WDC WD1600AAJS-00B4A0 160GB      | 1         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 32     | 28.21%  |
| Seagate             | 20        | 27     | 25.64%  |
| Toshiba             | 14        | 14     | 17.95%  |
| Hitachi             | 14        | 14     | 17.95%  |
| Samsung Electronics | 3         | 3      | 3.85%   |
| Unknown             | 2         | 2      | 2.56%   |
| Maxtor              | 1         | 1      | 1.28%   |
| HGST                | 1         | 1      | 1.28%   |
| Fujitsu             | 1         | 1      | 1.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 19        | 21     | 33.33%  |
| Samsung Electronics | 10        | 12     | 17.54%  |
| WDC                 | 4         | 4      | 7.02%   |
| SanDisk             | 4         | 5      | 7.02%   |
| Intel               | 3         | 3      | 5.26%   |
| China               | 3         | 5      | 5.26%   |
| SK hynix            | 2         | 2      | 3.51%   |
| A-DATA Technology   | 2         | 2      | 3.51%   |
| Vaseky              | 1         | 1      | 1.75%   |
| Transcend           | 1         | 2      | 1.75%   |
| Team                | 1         | 1      | 1.75%   |
| Patriot             | 1         | 1      | 1.75%   |
| OCZ                 | 1         | 2      | 1.75%   |
| Micron Technology   | 1         | 1      | 1.75%   |
| LITEON              | 1         | 1      | 1.75%   |
| Intenso             | 1         | 1      | 1.75%   |
| GOODRAM             | 1         | 1      | 1.75%   |
| ASMT                | 1         | 1      | 1.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 71        | 95     | 45.22%  |
| SSD     | 53        | 66     | 33.76%  |
| NVMe    | 29        | 42     | 18.47%  |
| MMC     | 3         | 3      | 1.91%   |
| Unknown | 1         | 1      | 0.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 101       | 158    | 73.72%  |
| NVMe | 29        | 42     | 21.17%  |
| SAS  | 4         | 4      | 2.92%   |
| MMC  | 3         | 3      | 2.19%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 94        | 132    | 78.99%  |
| 0.51-1.0   | 20        | 21     | 16.81%  |
| 1.01-2.0   | 2         | 3      | 1.68%   |
| 3.01-4.0   | 1         | 2      | 0.84%   |
| 2.01-3.0   | 1         | 2      | 0.84%   |
| 4.01-10.0  | 1         | 1      | 0.84%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 40        | 29.41%  |
| 251-500        | 33        | 24.26%  |
| 51-100         | 16        | 11.76%  |
| 501-1000       | 15        | 11.03%  |
| 21-50          | 12        | 8.82%   |
| 1-20           | 10        | 7.35%   |
| More than 3000 | 3         | 2.21%   |
| 1001-2000      | 3         | 2.21%   |
| Unknown        | 3         | 2.21%   |
| 2001-3000      | 1         | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 59        | 40.14%  |
| 21-50     | 41        | 27.89%  |
| 51-100    | 19        | 12.93%  |
| 101-250   | 13        | 8.84%   |
| 501-1000  | 6         | 4.08%   |
| 251-500   | 5         | 3.4%    |
| Unknown   | 3         | 2.04%   |
| 2001-3000 | 1         | 0.68%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 1         | 1      | 10%     |
| WDC WD3200AAJS-00L7A0 320GB                                     | 1         | 1      | 10%     |
| Seagate ST3120813AS 120GB                                       | 1         | 1      | 10%     |
| Seagate ST3000DM001-1CH166 3TB                                  | 1         | 2      | 10%     |
| Seagate ST250LT021-1AF14C 250GB                                 | 1         | 1      | 10%     |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 512GB | 1         | 1      | 10%     |
| Samsung Electronics MZVKW512HMJP-000H1 512GB                    | 1         | 1      | 10%     |
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD                   | 1         | 1      | 10%     |
| Hitachi HDS721050CLA362 500GB                                   | 1         | 1      | 10%     |
| Crucial CT500P1SSD8 500GB                                       | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 4      | 33.33%  |
| WDC                 | 2         | 2      | 22.22%  |
| Samsung Electronics | 2         | 3      | 22.22%  |
| Hitachi             | 1         | 1      | 11.11%  |
| Crucial             | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 60%     |
| WDC     | 1         | 1      | 20%     |
| Hitachi | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 6      | 50%     |
| NVMe | 2         | 3      | 25%     |
| SSD  | 2         | 2      | 25%     |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 96        | 151    | 70.07%  |
| Works    | 33        | 45     | 24.09%  |
| Malfunc  | 8         | 11     | 5.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 97        | 65.54%  |
| AMD                          | 15        | 10.14%  |
| Samsung Electronics          | 9         | 6.08%   |
| SK hynix                     | 6         | 4.05%   |
| Nvidia                       | 6         | 4.05%   |
| SanDisk                      | 4         | 2.7%    |
| Kingston Technology Company  | 4         | 2.7%    |
| Toshiba America Info Systems | 3         | 2.03%   |
| Micron/Crucial Technology    | 1         | 0.68%   |
| Micron Technology            | 1         | 0.68%   |
| KIOXIA                       | 1         | 0.68%   |
| JMicron Technology           | 1         | 0.68%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 12        | 6.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 10        | 5.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 9         | 5.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 4.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6         | 3.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6         | 3.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 2.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 5         | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 2.82%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4         | 2.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 2.26%   |
| Samsung NVMe SSD Controller 980                                                         | 3         | 1.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 1.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 1.69%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3         | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 1.69%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 2         | 1.13%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 2         | 1.13%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 2         | 1.13%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2         | 1.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.13%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2         | 1.13%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 2         | 1.13%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 1.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 1.13%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 2         | 1.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 1.13%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2         | 1.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 1.13%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2         | 1.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 1.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 1.13%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 0.56%   |
| SK hynix Platinum P41 NVMe Solid State Drive 2TB                                        | 1         | 0.56%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                             | 1         | 0.56%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.56%   |
| SanDisk PC SN520 NVMe SSD                                                               | 1         | 0.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 84        | 54.55%  |
| IDE  | 30        | 19.48%  |
| NVMe | 29        | 18.83%  |
| RAID | 11        | 7.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 107       | 81.68%  |
| AMD    | 23        | 17.56%  |
| ARM    | 1         | 0.76%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 2.29%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 2.29%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 3         | 2.29%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3         | 2.29%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 1.53%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 2         | 1.53%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 2         | 1.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.53%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.53%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 1.53%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 1.53%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 1.53%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.53%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.53%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 2         | 1.53%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 1.53%   |
| Intel Celeron CPU 430 @ 1.80GHz               | 2         | 1.53%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 1.53%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.53%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.53%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 2         | 1.53%   |
| Intel Xeon CPU X3210 @ 2.13GHz                | 1         | 0.76%   |
| Intel Pentium M processor 1.73GHz             | 1         | 0.76%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 1         | 0.76%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz   | 1         | 0.76%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.76%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.76%   |
| Intel Pentium 4 CPU 3.00GHz                   | 1         | 0.76%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 1         | 0.76%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.76%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.76%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1         | 0.76%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 1         | 0.76%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 0.76%   |
| Intel Core i7-4550U CPU @ 1.50GHz             | 1         | 0.76%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.76%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 0.76%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 0.76%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 33        | 25.19%  |
| Intel Core i7           | 25        | 19.08%  |
| Intel Core i3           | 9         | 6.87%   |
| Intel Celeron           | 9         | 6.87%   |
| Other                   | 7         | 5.34%   |
| Intel Pentium Dual-Core | 6         | 4.58%   |
| Intel Core 2 Duo        | 6         | 4.58%   |
| AMD Ryzen 5             | 5         | 3.82%   |
| Intel Pentium           | 3         | 2.29%   |
| AMD E1                  | 3         | 2.29%   |
| Intel Core 2 Quad       | 2         | 1.53%   |
| Intel Core 2            | 2         | 1.53%   |
| AMD Ryzen 9             | 2         | 1.53%   |
| AMD Athlon 64 X2        | 2         | 1.53%   |
| Intel Xeon              | 1         | 0.76%   |
| Intel Pentium M         | 1         | 0.76%   |
| Intel Pentium Dual      | 1         | 0.76%   |
| Intel Pentium 4         | 1         | 0.76%   |
| Intel Celeron D         | 1         | 0.76%   |
| Intel Atom              | 1         | 0.76%   |
| AMD Turion 64 Mobile    | 1         | 0.76%   |
| AMD Ryzen 7             | 1         | 0.76%   |
| AMD Ryzen 5 PRO         | 1         | 0.76%   |
| AMD Phenom              | 1         | 0.76%   |
| AMD FX                  | 1         | 0.76%   |
| AMD E2                  | 1         | 0.76%   |
| AMD C-60                | 1         | 0.76%   |
| AMD Athlon X4           | 1         | 0.76%   |
| AMD Athlon II X3        | 1         | 0.76%   |
| AMD Athlon 64           | 1         | 0.76%   |
| AMD A10                 | 1         | 0.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 63        | 48.09%  |
| 4      | 47        | 35.88%  |
| 1      | 7         | 5.34%   |
| 6      | 6         | 4.58%   |
| 8      | 3         | 2.29%   |
| 14     | 2         | 1.53%   |
| 3      | 2         | 1.53%   |
| 12     | 1         | 0.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 131       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 72        | 54.55%  |
| 1      | 60        | 45.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 124       | 94.66%  |
| Unknown        | 6         | 4.58%   |
| 32-bit         | 1         | 0.76%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 24.06%  |
| 0x206a7    | 13        | 9.77%   |
| 0x306a9    | 10        | 7.52%   |
| 0x306c3    | 8         | 6.02%   |
| 0x1067a    | 8         | 6.02%   |
| 0x406e3    | 5         | 3.76%   |
| 0x806ec    | 3         | 2.26%   |
| 0x806ea    | 3         | 2.26%   |
| 0x806c1    | 3         | 2.26%   |
| 0x506e3    | 3         | 2.26%   |
| 0x40651    | 3         | 2.26%   |
| 0x10676    | 3         | 2.26%   |
| 0x806eb    | 2         | 1.5%    |
| 0x806e9    | 2         | 1.5%    |
| 0x506c9    | 2         | 1.5%    |
| 0x08108109 | 2         | 1.5%    |
| 0x05000119 | 2         | 1.5%    |
| 0xf65      | 1         | 0.75%   |
| 0xf43      | 1         | 0.75%   |
| 0xa0652    | 1         | 0.75%   |
| 0x906ec    | 1         | 0.75%   |
| 0x906eb    | 1         | 0.75%   |
| 0x906ea    | 1         | 0.75%   |
| 0x906e9    | 1         | 0.75%   |
| 0x906a3    | 1         | 0.75%   |
| 0x706e5    | 1         | 0.75%   |
| 0x6fd      | 1         | 0.75%   |
| 0x6fb      | 1         | 0.75%   |
| 0x6fa      | 1         | 0.75%   |
| 0x6f6      | 1         | 0.75%   |
| 0x6f2      | 1         | 0.75%   |
| 0x6d8      | 1         | 0.75%   |
| 0x406c4    | 1         | 0.75%   |
| 0x406c3    | 1         | 0.75%   |
| 0x30678    | 1         | 0.75%   |
| 0x20655    | 1         | 0.75%   |
| 0x106e5    | 1         | 0.75%   |
| 0x10661    | 1         | 0.75%   |
| 0x0a50000c | 1         | 0.75%   |
| 0x08701021 | 1         | 0.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 20        | 15.27%  |
| SandyBridge      | 17        | 12.98%  |
| Penryn           | 12        | 9.16%   |
| Haswell          | 12        | 9.16%   |
| IvyBridge        | 11        | 8.4%    |
| Skylake          | 8         | 6.11%   |
| Core             | 8         | 6.11%   |
| Zen+             | 6         | 4.58%   |
| TigerLake        | 4         | 3.05%   |
| Silvermont       | 4         | 3.05%   |
| K8 Hammer        | 4         | 3.05%   |
| Zen 2            | 2         | 1.53%   |
| NetBurst         | 2         | 1.53%   |
| K10              | 2         | 1.53%   |
| Jaguar           | 2         | 1.53%   |
| Goldmont         | 2         | 1.53%   |
| Excavator        | 2         | 1.53%   |
| Bobcat           | 2         | 1.53%   |
| Unknown          | 2         | 1.53%   |
| Zen 3            | 1         | 0.76%   |
| Westmere         | 1         | 0.76%   |
| Steamroller      | 1         | 0.76%   |
| P6               | 1         | 0.76%   |
| Nehalem          | 1         | 0.76%   |
| IceLake          | 1         | 0.76%   |
| CometLake        | 1         | 0.76%   |
| Bulldozer        | 1         | 0.76%   |
| Alderlake Hybrid | 1         | 0.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 79        | 49.38%  |
| Nvidia                     | 40        | 25%     |
| AMD                        | 40        | 25%     |
| Matrox Electronics Systems | 1         | 0.63%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 7.83%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 4.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 3.61%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 3.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 3.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 2.41%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 2.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 2.41%   |
| Nvidia GM108M [GeForce MX110]                                                            | 3         | 1.81%   |
| Intel HD Graphics 620                                                                    | 3         | 1.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.81%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 1.2%    |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 1.2%    |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 1.2%    |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 1.2%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.2%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.2%    |
| Intel HD Graphics 500                                                                    | 2         | 1.2%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.2%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 1.2%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 1.2%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.2%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 1.2%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.2%    |
| AMD Kabini [Radeon HD 8210]                                                              | 2         | 1.2%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 1.2%    |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                     | 1         | 0.6%    |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 0.6%    |
| Nvidia TU106BM [GeForce RTX 2070 Mobile]                                                 | 1         | 0.6%    |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1         | 0.6%    |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.6%    |
| Nvidia GT216 [GeForce GT 220]                                                            | 1         | 0.6%    |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.6%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.6%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.6%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.6%    |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 51        | 38.64%  |
| 1 x AMD        | 31        | 23.48%  |
| Intel + Nvidia | 23        | 17.42%  |
| 1 x Nvidia     | 16        | 12.12%  |
| Intel + AMD    | 4         | 3.03%   |
| 2 x AMD        | 3         | 2.27%   |
| Other          | 1         | 0.76%   |
| 3 x AMD        | 1         | 0.76%   |
| 1 x Matrox     | 1         | 0.76%   |
| AMD + Nvidia   | 1         | 0.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 105       | 78.95%  |
| Proprietary | 22        | 16.54%  |
| Unknown     | 6         | 4.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 51.85%  |
| 1.01-2.0   | 22        | 16.3%   |
| 0.01-0.5   | 17        | 12.59%  |
| 0.51-1.0   | 13        | 9.63%   |
| 3.01-4.0   | 7         | 5.19%   |
| 7.01-8.0   | 3         | 2.22%   |
| 5.01-6.0   | 3         | 2.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 20        | 15.15%  |
| AU Optronics            | 19        | 14.39%  |
| Samsung Electronics     | 18        | 13.64%  |
| BOE                     | 12        | 9.09%   |
| Chimei Innolux          | 10        | 7.58%   |
| Goldstar                | 7         | 5.3%    |
| AOC                     | 6         | 4.55%   |
| Philips                 | 4         | 3.03%   |
| Dell                    | 4         | 3.03%   |
| Sharp                   | 3         | 2.27%   |
| Unknown                 | 2         | 1.52%   |
| Sony                    | 2         | 1.52%   |
| LG Philips              | 2         | 1.52%   |
| IBM                     | 2         | 1.52%   |
| Hewlett-Packard         | 2         | 1.52%   |
| Fujitsu Siemens         | 2         | 1.52%   |
| Chi Mei Optoelectronics | 2         | 1.52%   |
| BenQ                    | 2         | 1.52%   |
| Ancor Communications    | 2         | 1.52%   |
| ViewSonic               | 1         | 0.76%   |
| Vestel Elektronik       | 1         | 0.76%   |
| PANDA                   | 1         | 0.76%   |
| NEC Computers           | 1         | 0.76%   |
| MSI                     | 1         | 0.76%   |
| Mi                      | 1         | 0.76%   |
| Lenovo                  | 1         | 0.76%   |
| InfoVision              | 1         | 0.76%   |
| CTV                     | 1         | 0.76%   |
| Belinea                 | 1         | 0.76%   |
| ASUSTek Computer        | 1         | 0.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 4         | 2.9%    |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch            | 3         | 2.17%   |
| LG Display LCD Monitor LGD05E4 1920x1080 344x194mm 15.5-inch           | 2         | 1.45%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch            | 2         | 1.45%   |
| IBM C170 CRT IBM1A51 1280x1024 310x230mm 15.2-inch                     | 2         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 2         | 1.45%   |
| AU Optronics LCD Monitor AUO35ED 1920x1080 344x193mm 15.5-inch         | 2         | 1.45%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch         | 2         | 1.45%   |
| AOC 917W AOC1917 1440x900 410x256mm 19.0-inch                          | 2         | 1.45%   |
| ViewSonic VA702 VSC1C1C 1280x1024 338x270mm 17.0-inch                  | 1         | 0.72%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                       | 1         | 0.72%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                   | 1         | 0.72%   |
| Unknown LCD Monitor Maxdata/XXXXXXX B_101920 1280x1024                 | 1         | 0.72%   |
| Sony TV SNY4D04 1920x1080 1600x900mm 72.3-inch                         | 1         | 0.72%   |
| Sony TV  *00 SNY4904 3840x2160                                         | 1         | 0.72%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                | 1         | 0.72%   |
| Sharp LCD Monitor SHP14A2 1920x1080 309x174mm 14.0-inch                | 1         | 0.72%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.72%   |
| Samsung Electronics SyncMaster SAM0579 1920x1080                       | 1         | 0.72%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch    | 1         | 0.72%   |
| Samsung Electronics SyncMaster SAM03E2 1680x1050 433x271mm 20.1-inch   | 1         | 0.72%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch   | 1         | 0.72%   |
| Samsung Electronics SyncMaster SAM0169 1280x1024 376x301mm 19.0-inch   | 1         | 0.72%   |
| Samsung Electronics SAMTRON 50X/V STN0011 1024x768 304x228mm 15.0-inch | 1         | 0.72%   |
| Samsung Electronics S27D590 SAM0B49 1920x1080 598x336mm 27.0-inch      | 1         | 0.72%   |
| Samsung Electronics S24D391 SAM0B87 1920x1080 521x293mm 23.5-inch      | 1         | 0.72%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch      | 1         | 0.72%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch      | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                   | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch   | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch   | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3554 1600x900 382x215mm 17.3-inch   | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch   | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch   | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch   | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 1         | 0.72%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1         | 0.72%   |
| Philips LCD Monitor FTV                                                | 1         | 0.72%   |
| Philips LCD Monitor 170S 3200x1080                                     | 1         | 0.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 55        | 42.64%  |
| 1366x768 (WXGA)    | 23        | 17.83%  |
| 1600x900 (HD+)     | 13        | 10.08%  |
| 1280x1024 (SXGA)   | 10        | 7.75%   |
| 1680x1050 (WSXGA+) | 6         | 4.65%   |
| 3840x2160 (4K)     | 5         | 3.88%   |
| 1440x900 (WXGA+)   | 5         | 3.88%   |
| 2560x1440 (QHD)    | 2         | 1.55%   |
| 1280x800 (WXGA)    | 2         | 1.55%   |
| 3440x1440          | 1         | 0.78%   |
| 3200x1080          | 1         | 0.78%   |
| 2736x1824          | 1         | 0.78%   |
| 2560x1600          | 1         | 0.78%   |
| 1920x1200 (WUXGA)  | 1         | 0.78%   |
| 1360x768           | 1         | 0.78%   |
| 1024x768 (XGA)     | 1         | 0.78%   |
| Unknown            | 1         | 0.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 44        | 32.84%  |
| 17      | 13        | 9.7%    |
| 14      | 13        | 9.7%    |
| 13      | 8         | 5.97%   |
| Unknown | 8         | 5.97%   |
| 21      | 7         | 5.22%   |
| 24      | 6         | 4.48%   |
| 23      | 6         | 4.48%   |
| 27      | 4         | 2.99%   |
| 19      | 4         | 2.99%   |
| 22      | 3         | 2.24%   |
| 18      | 3         | 2.24%   |
| 11      | 3         | 2.24%   |
| 72      | 2         | 1.49%   |
| 31      | 2         | 1.49%   |
| 20      | 2         | 1.49%   |
| 12      | 2         | 1.49%   |
| 84      | 1         | 0.75%   |
| 34      | 1         | 0.75%   |
| 33      | 1         | 0.75%   |
| 16      | 1         | 0.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 67        | 51.15%  |
| 401-500     | 17        | 12.98%  |
| 501-600     | 14        | 10.69%  |
| 351-400     | 10        | 7.63%   |
| 201-300     | 8         | 6.11%   |
| Unknown     | 8         | 6.11%   |
| 1501-2000   | 3         | 2.29%   |
| 701-800     | 2         | 1.53%   |
| 601-700     | 2         | 1.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 91        | 73.98%  |
| 16/10   | 13        | 10.57%  |
| 5/4     | 7         | 5.69%   |
| Unknown | 6         | 4.88%   |
| 4/3     | 3         | 2.44%   |
| 3/2     | 2         | 1.63%   |
| 21/9    | 1         | 0.81%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 41        | 31.3%   |
| 81-90          | 18        | 13.74%  |
| 201-250        | 16        | 12.21%  |
| 151-200        | 9         | 6.87%   |
| Unknown        | 8         | 6.11%   |
| 141-150        | 7         | 5.34%   |
| 121-130        | 6         | 4.58%   |
| 351-500        | 4         | 3.05%   |
| 301-350        | 4         | 3.05%   |
| More than 1000 | 3         | 2.29%   |
| 71-80          | 3         | 2.29%   |
| 51-60          | 3         | 2.29%   |
| 111-120        | 3         | 2.29%   |
| 61-70          | 2         | 1.53%   |
| 131-140        | 2         | 1.53%   |
| 251-300        | 1         | 0.76%   |
| 91-100         | 1         | 0.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 43        | 33.33%  |
| 51-100        | 36        | 27.91%  |
| 101-120       | 33        | 25.58%  |
| Unknown       | 8         | 6.2%    |
| 161-240       | 5         | 3.88%   |
| More than 240 | 2         | 1.55%   |
| 1-50          | 2         | 1.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 111       | 83.46%  |
| 2     | 15        | 11.28%  |
| 0     | 5         | 3.76%   |
| 3     | 2         | 1.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 61        | 32.62%  |
| Intel                                  | 47        | 25.13%  |
| Qualcomm Atheros                       | 29        | 15.51%  |
| Broadcom                               | 11        | 5.88%   |
| Ralink Technology                      | 6         | 3.21%   |
| TP-Link                                | 4         | 2.14%   |
| Ralink                                 | 4         | 2.14%   |
| Qualcomm Atheros Communications        | 4         | 2.14%   |
| Nvidia                                 | 4         | 2.14%   |
| Marvell Technology Group               | 4         | 2.14%   |
| Broadcom Limited                       | 3         | 1.6%    |
| Sony Ericsson Mobile Communications AB | 2         | 1.07%   |
| Hewlett-Packard                        | 2         | 1.07%   |
| Sierra Wireless                        | 1         | 0.53%   |
| Mercucys                               | 1         | 0.53%   |
| MediaTek                               | 1         | 0.53%   |
| ICS Advent                             | 1         | 0.53%   |
| HTC (High Tech Computer)               | 1         | 0.53%   |
| D-Link                                 | 1         | 0.53%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 43        | 19.55%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 5%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 3.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 3.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 3.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 2.73%   |
| Ralink MT7601U Wireless Adapter                                   | 5         | 2.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 1.82%   |
| Qualcomm Atheros AR9271 802.11n                                   | 4         | 1.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.36%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 1.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.36%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3         | 1.36%   |
| Intel Wireless 8260                                               | 3         | 1.36%   |
| Intel Wireless 7260                                               | 3         | 1.36%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.36%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.36%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 1.36%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.36%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.91%   |
| Sony Ericsson Mobile AB D2005                                     | 2         | 0.91%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2         | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.91%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.91%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.91%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 0.91%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2         | 0.91%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 0.91%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.45%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1         | 0.45%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.45%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.45%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.45%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 34        | 33.66%  |
| Qualcomm Atheros                | 23        | 22.77%  |
| Realtek Semiconductor           | 15        | 14.85%  |
| Broadcom                        | 8         | 7.92%   |
| Ralink Technology               | 6         | 5.94%   |
| Ralink                          | 4         | 3.96%   |
| Qualcomm Atheros Communications | 4         | 3.96%   |
| TP-Link                         | 3         | 2.97%   |
| Sierra Wireless                 | 1         | 0.99%   |
| Mercucys                        | 1         | 0.99%   |
| Marvell Technology Group        | 1         | 0.99%   |
| D-Link                          | 1         | 0.99%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 6.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 6.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 5.94%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 4.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 3.96%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 3.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 2.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 2.97%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 2.97%   |
| Intel Wireless 8260                                                     | 3         | 2.97%   |
| Intel Wireless 7260                                                     | 3         | 2.97%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 2.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 2.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 2.97%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.98%   |
| Intel Wireless 8265 / 8275                                              | 2         | 1.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.98%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.98%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.99%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.99%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.99%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.99%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.99%   |
| Realtek Realtek Network controller                                      | 1         | 0.99%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.99%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.99%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 1         | 0.99%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.99%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1         | 0.99%   |
| Mercucys 802.11n NIC                                                    | 1         | 0.99%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 0.99%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.99%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 0.99%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.99%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 57        | 49.14%  |
| Intel                                  | 29        | 25%     |
| Qualcomm Atheros                       | 9         | 7.76%   |
| Nvidia                                 | 4         | 3.45%   |
| Broadcom                               | 4         | 3.45%   |
| Marvell Technology Group               | 3         | 2.59%   |
| Broadcom Limited                       | 3         | 2.59%   |
| Sony Ericsson Mobile Communications AB | 2         | 1.72%   |
| TP-Link                                | 1         | 0.86%   |
| MediaTek                               | 1         | 0.86%   |
| ICS Advent                             | 1         | 0.86%   |
| HTC (High Tech Computer)               | 1         | 0.86%   |
| Hewlett-Packard                        | 1         | 0.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 43        | 36.75%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 9.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 6.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.56%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.56%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 2.56%   |
| Sony Ericsson Mobile AB D2005                                     | 2         | 1.71%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2         | 1.71%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.71%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2         | 1.71%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.85%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.85%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.85%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.85%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.85%   |
| Nvidia MCP73 Ethernet                                             | 1         | 0.85%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.85%   |
| Nvidia CK8S Ethernet Controller                                   | 1         | 0.85%   |
| Nvidia CK804 Ethernet Controller                                  | 1         | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.85%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.85%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.85%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.85%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.85%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.85%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.85%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.85%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.85%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.85%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.85%   |
| Intel 82573V Gigabit Ethernet Controller (Copper)                 | 1         | 0.85%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.85%   |
| Intel 82566DM Gigabit Network Connection                          | 1         | 0.85%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 0.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 111       | 53.37%  |
| WiFi     | 95        | 45.67%  |
| Modem    | 2         | 0.96%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 82        | 61.19%  |
| Ethernet | 52        | 38.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 67        | 50.76%  |
| 1     | 58        | 43.94%  |
| 0     | 7         | 5.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 128       | 97.71%  |
| Yes  | 3         | 2.29%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 27.94%  |
| Qualcomm Atheros Communications | 10        | 14.71%  |
| IMC Networks                    | 7         | 10.29%  |
| Realtek Semiconductor           | 6         | 8.82%   |
| Broadcom                        | 6         | 8.82%   |
| Lite-On Technology              | 4         | 5.88%   |
| Ralink                          | 3         | 4.41%   |
| Cambridge Silicon Radio         | 3         | 4.41%   |
| Hewlett-Packard                 | 2         | 2.94%   |
| Foxconn / Hon Hai               | 2         | 2.94%   |
| Toshiba                         | 1         | 1.47%   |
| Realtek                         | 1         | 1.47%   |
| Marvell Semiconductor           | 1         | 1.47%   |
| Integrated System Solution      | 1         | 1.47%   |
| Dell                            | 1         | 1.47%   |
| Alps Electric                   | 1         | 1.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 8.82%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 7.35%   |
| Intel AX201 Bluetooth                               | 4         | 5.88%   |
| IMC Networks Bluetooth Radio                        | 4         | 5.88%   |
| Realtek Bluetooth Radio                             | 3         | 4.41%   |
| Ralink RT3290 Bluetooth                             | 3         | 4.41%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 4.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 4.41%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 2.94%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 2.94%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 2.94%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.94%   |
| Intel Bluetooth Device                              | 2         | 2.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 2.94%   |
| IMC Networks Bluetooth Device                       | 2         | 2.94%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 2.94%   |
| Toshiba RT Bluetooth Radio                          | 1         | 1.47%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.47%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 1.47%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.47%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 1.47%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.47%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.47%   |
| Intel AX200 Bluetooth                               | 1         | 1.47%   |
| Integrated System Solution Bluetooth Device         | 1         | 1.47%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.47%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.47%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 1.47%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.47%   |
| Broadcom HP Portable Valentine                      | 1         | 1.47%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.47%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.47%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 UHE Dongle | 1         | 1.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.47%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.47%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 1.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 103       | 60.23%  |
| AMD                 | 35        | 20.47%  |
| Nvidia              | 25        | 14.62%  |
| Logitech            | 3         | 1.75%   |
| VIA Technologies    | 1         | 0.58%   |
| Texas Instruments   | 1         | 0.58%   |
| JMTek               | 1         | 0.58%   |
| Creative Labs       | 1         | 0.58%   |
| C-Media Electronics | 1         | 0.58%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 18        | 9.23%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 6.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 5.13%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 3.59%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 3.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 3.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 3.08%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 2.56%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 2.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 2.56%   |
| AMD FCH Azalia Controller                                                                         | 5         | 2.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.05%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 2.05%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 2.05%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 2.05%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 1.54%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.54%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 1.54%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.54%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 1.54%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.03%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.03%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2         | 1.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.03%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.03%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.03%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.03%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.03%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 1.03%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 1.03%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.03%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.03%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 1.03%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 1.03%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 1.03%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller                                | 1         | 0.51%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1         | 0.51%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 15        | 24.59%  |
| Kingston            | 15        | 24.59%  |
| Micron Technology   | 10        | 16.39%  |
| Samsung Electronics | 9         | 14.75%  |
| Unknown             | 4         | 6.56%   |
| A-DATA Technology   | 3         | 4.92%   |
| Crucial             | 2         | 3.28%   |
| Corsair             | 2         | 3.28%   |
| Apacer              | 1         | 1.64%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 2.86%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 2.86%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 2         | 2.86%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s                 | 2         | 2.86%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s            | 2         | 2.86%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s               | 2         | 2.86%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                            | 1         | 1.43%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                         | 1         | 1.43%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                             | 1         | 1.43%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                            | 1         | 1.43%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                          | 1         | 1.43%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                       | 1         | 1.43%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB DIMM SDRAM 2048MT/s               | 1         | 1.43%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB DIMM SDRAM 2048MT/s               | 1         | 1.43%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.43%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1         | 1.43%   |
| SK hynix RAM HMT351U6CFR8C 4GB DIMM DDR3 1333MT/s                   | 1         | 1.43%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.43%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.43%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 1.43%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 1.43%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s                | 1         | 1.43%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 1         | 1.43%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 1.43%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 1.43%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 1.43%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4096MB Row Of Chips LPDDR3 2133MT/s | 1         | 1.43%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 1         | 1.43%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                     | 1         | 1.43%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 1.43%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 1         | 1.43%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 1         | 1.43%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 1.43%   |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM DDR5 4800MT/s            | 1         | 1.43%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s      | 1         | 1.43%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                          | 1         | 1.43%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s               | 1         | 1.43%   |
| Micron RAM 8JTF51264HZ-1G6D 1 4GB SODIMM DDR3 1600MT/s              | 1         | 1.43%   |
| Micron RAM 4ATF51264HZ-2G3B1 4096MB SODIMM DDR4 2400MT/s            | 1         | 1.43%   |
| Micron RAM 16KTF51264HZ-1G4M1 4GB SODIMM DDR3 1333MT/s              | 1         | 1.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 24        | 44.44%  |
| DDR4    | 19        | 35.19%  |
| DDR2    | 4         | 7.41%   |
| LPDDR3  | 2         | 3.7%    |
| SDRAM   | 1         | 1.85%   |
| LPDDR4  | 1         | 1.85%   |
| DDR5    | 1         | 1.85%   |
| DDR     | 1         | 1.85%   |
| Unknown | 1         | 1.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 31        | 58.49%  |
| DIMM         | 19        | 35.85%  |
| Row Of Chips | 3         | 5.66%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 24        | 40.68%  |
| 8192  | 19        | 32.2%   |
| 2048  | 8         | 13.56%  |
| 1024  | 4         | 6.78%   |
| 16384 | 3         | 5.08%   |
| 32768 | 1         | 1.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 17        | 28.33%  |
| 2667  | 6         | 10%     |
| 3200  | 5         | 8.33%   |
| 2133  | 5         | 8.33%   |
| 1333  | 4         | 6.67%   |
| 800   | 4         | 6.67%   |
| 2400  | 3         | 5%      |
| 1867  | 2         | 3.33%   |
| 1866  | 2         | 3.33%   |
| 1334  | 2         | 3.33%   |
| 4800  | 1         | 1.67%   |
| 3600  | 1         | 1.67%   |
| 3400  | 1         | 1.67%   |
| 3266  | 1         | 1.67%   |
| 2800  | 1         | 1.67%   |
| 2048  | 1         | 1.67%   |
| 1800  | 1         | 1.67%   |
| 1067  | 1         | 1.67%   |
| 1066  | 1         | 1.67%   |
| 333   | 1         | 1.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 2         | 66.67%  |
| Lexmark International | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lexmark International InkJet Color Printer | 1         | 33.33%  |
| HP LaserJet 1000                           | 1         | 33.33%  |
| HP DeskJet F2100 Printer series            | 1         | 33.33%  |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 18        | 22.5%   |
| Realtek Semiconductor                  | 9         | 11.25%  |
| IMC Networks                           | 8         | 10%     |
| Acer                                   | 6         | 7.5%    |
| Logitech                               | 5         | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 6.25%   |
| Sunplus Innovation Technology          | 4         | 5%      |
| Quanta                                 | 4         | 5%      |
| Microdia                               | 4         | 5%      |
| Suyin                                  | 3         | 3.75%   |
| Lite-On Technology                     | 3         | 3.75%   |
| Syntek                                 | 2         | 2.5%    |
| Ricoh                                  | 2         | 2.5%    |
| Samsung Electronics                    | 1         | 1.25%   |
| Primax Electronics                     | 1         | 1.25%   |
| Luxvisions Innotech Limited            | 1         | 1.25%   |
| Lenovo                                 | 1         | 1.25%   |
| Guillemot                              | 1         | 1.25%   |
| Apple                                  | 1         | 1.25%   |
| ALi                                    | 1         | 1.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                          | 5         | 6.25%   |
| Microdia Integrated_Webcam_HD                               | 4         | 5%      |
| Chicony Integrated Camera                                   | 3         | 3.75%   |
| Acer EasyCamera                                             | 3         | 3.75%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 2.5%    |
| Realtek Integrated_Webcam_HD                                | 2         | 2.5%    |
| Realtek HD WebCam                                           | 2         | 2.5%    |
| Lite-On HP HD Webcam                                        | 2         | 2.5%    |
| Chicony HP Truevision HD                                    | 2         | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 2         | 2.5%    |
| Syntek Lenovo EasyCamera                                    | 1         | 1.25%   |
| Syntek Integrated Camera                                    | 1         | 1.25%   |
| Suyin HP TrueVision HD                                      | 1         | 1.25%   |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 1.25%   |
| Sunplus HP Universal Camera                                 | 1         | 1.25%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 1.25%   |
| Sunplus HD WebCam                                           | 1         | 1.25%   |
| Samsung Galaxy A5 (MTP)                                     | 1         | 1.25%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870]         | 1         | 1.25%   |
| Ricoh Laptop_Integrated_Webcam_3M                           | 1         | 1.25%   |
| Realtek VGA WebCam                                          | 1         | 1.25%   |
| Realtek USB Camera                                          | 1         | 1.25%   |
| Realtek Laptop_Integrated_Webcam_HD                         | 1         | 1.25%   |
| Realtek Integrated Webcam HD                                | 1         | 1.25%   |
| Realtek HP Wide Vision FHD Camera                           | 1         | 1.25%   |
| Quanta HP Wide Vision HD Camera                             | 1         | 1.25%   |
| Quanta HP Webcam                                            | 1         | 1.25%   |
| Quanta HP TrueVision HD Camera                              | 1         | 1.25%   |
| Quanta HP HD Camera                                         | 1         | 1.25%   |
| Primax HP HD Webcam [Fixed]                                 | 1         | 1.25%   |
| Luxvisions Innotech Limited HP HD Camera                    | 1         | 1.25%   |
| Logitech Webcam C270                                        | 1         | 1.25%   |
| Logitech Webcam C210                                        | 1         | 1.25%   |
| Logitech Webcam C170                                        | 1         | 1.25%   |
| Logitech QuickCam Vision Pro                                | 1         | 1.25%   |
| Logitech HD Webcam C510                                     | 1         | 1.25%   |
| Lite-On HP Wide Vision HD Camera                            | 1         | 1.25%   |
| Lenovo UVC Camera                                           | 1         | 1.25%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 1.25%   |
| IMC Networks USB2.0 HD IR UVC WebCam                        | 1         | 1.25%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 12        | 54.55%  |
| Synaptics                  | 6         | 27.27%  |
| Shenzhen Goodix Technology | 2         | 9.09%   |
| LighTuning Technology      | 1         | 4.55%   |
| AuthenTec                  | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 5         | 22.73%  |
| Validity Sensors VFS471 Fingerprint Reader        | 4         | 18.18%  |
| Unknown                                           | 4         | 18.18%  |
| Shenzhen Goodix  FingerPrint Device               | 2         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 4.55%   |
| Validity Sensors Synaptics WBDI                   | 1         | 4.55%   |
| Validity Sensors Swipe Fingerprint Sensor         | 1         | 4.55%   |
| Synaptics  WBDI                                   | 1         | 4.55%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 4.55%   |
| LighTuning Fingerprint Reader                     | 1         | 4.55%   |
| AuthenTec AES2810                                 | 1         | 4.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 60%     |
| Upek        | 1         | 20%     |
| Alcor Micro | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |
| Broadcom 5880                                                                | 1         | 20%     |
| Broadcom 58200                                                               | 1         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 90        | 67.16%  |
| 1     | 39        | 29.1%   |
| 2     | 4         | 2.99%   |
| 3     | 1         | 0.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 22        | 46.81%  |
| Graphics card         | 9         | 19.15%  |
| Net/wireless          | 5         | 10.64%  |
| Chipcard              | 5         | 10.64%  |
| Bluetooth             | 3         | 6.38%   |
| Sound                 | 1         | 2.13%   |
| Multimedia controller | 1         | 2.13%   |
| Modem                 | 1         | 2.13%   |


Fedora 36 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 36.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_36/Desktop/README.md) and [notebooks](/Dist/Fedora_36/Notebook/README.md).

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

Total: 2823

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | 3000 N200 0769BAG           | Notebook    | [f8f410eb2a](https://linux-hardware.org/?probe=f8f410eb2a) | Jan 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [47246aa8b5](https://linux-hardware.org/?probe=47246aa8b5) | Jan 29, 2023 |
| Lenovo        | IdeaPad S340-14IML 81N9     | Notebook    | [58e620077b](https://linux-hardware.org/?probe=58e620077b) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ff5e2b673e](https://linux-hardware.org/?probe=ff5e2b673e) | Jan 27, 2023 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [6d4ecb5a00](https://linux-hardware.org/?probe=6d4ecb5a00) | Jan 27, 2023 |
| Gigabyte      | Z87-D3HP-CF                 | Desktop     | [812c00440c](https://linux-hardware.org/?probe=812c00440c) | Jan 26, 2023 |
| Dell          | Latitude 7480               | Notebook    | [3cb61c5b71](https://linux-hardware.org/?probe=3cb61c5b71) | Jan 26, 2023 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [3386aa1dce](https://linux-hardware.org/?probe=3386aa1dce) | Jan 25, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d1c6e3c96f](https://linux-hardware.org/?probe=d1c6e3c96f) | Jan 24, 2023 |
| Dell          | Latitude 3420               | Notebook    | [d2a8b9657a](https://linux-hardware.org/?probe=d2a8b9657a) | Jan 23, 2023 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [17b4a2466c](https://linux-hardware.org/?probe=17b4a2466c) | Jan 20, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [7f36411ac1](https://linux-hardware.org/?probe=7f36411ac1) | Jan 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [440ff298e7](https://linux-hardware.org/?probe=440ff298e7) | Jan 19, 2023 |
| ASRock        | Z690 PG Riptide             | Desktop     | [582e3e3026](https://linux-hardware.org/?probe=582e3e3026) | Jan 19, 2023 |
| HP            | ENVY Laptop 17-ce0xxx       | Notebook    | [1a0f3869dd](https://linux-hardware.org/?probe=1a0f3869dd) | Jan 18, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [8da5286795](https://linux-hardware.org/?probe=8da5286795) | Jan 18, 2023 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [0d7c3e0009](https://linux-hardware.org/?probe=0d7c3e0009) | Jan 17, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [9f280d24f5](https://linux-hardware.org/?probe=9f280d24f5) | Jan 17, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [f26dbd644c](https://linux-hardware.org/?probe=f26dbd644c) | Jan 17, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [84d86434e8](https://linux-hardware.org/?probe=84d86434e8) | Jan 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8fb168e741](https://linux-hardware.org/?probe=8fb168e741) | Jan 16, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | Notebook    | [dd953776aa](https://linux-hardware.org/?probe=dd953776aa) | Jan 16, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [7e67b2b3a0](https://linux-hardware.org/?probe=7e67b2b3a0) | Jan 14, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [ea080033f1](https://linux-hardware.org/?probe=ea080033f1) | Jan 14, 2023 |
| HP            | 8753                        | Desktop     | [5cdf3ef632](https://linux-hardware.org/?probe=5cdf3ef632) | Jan 14, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c94f291c81](https://linux-hardware.org/?probe=c94f291c81) | Jan 13, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3128a21a3a](https://linux-hardware.org/?probe=3128a21a3a) | Jan 13, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2R40... | Notebook    | [e78a057172](https://linux-hardware.org/?probe=e78a057172) | Jan 13, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [f9846c0e18](https://linux-hardware.org/?probe=f9846c0e18) | Jan 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4236e82f21](https://linux-hardware.org/?probe=4236e82f21) | Jan 13, 2023 |
| Lenovo        | ThinkPad T430 2347B85       | Notebook    | [01fce134df](https://linux-hardware.org/?probe=01fce134df) | Jan 12, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [eec3fcf9ff](https://linux-hardware.org/?probe=eec3fcf9ff) | Jan 11, 2023 |
| HP            | ProBook 4520s               | Notebook    | [8e1eba4ad4](https://linux-hardware.org/?probe=8e1eba4ad4) | Jan 09, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [9eac6e2b97](https://linux-hardware.org/?probe=9eac6e2b97) | Jan 09, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [b8ac11cfd3](https://linux-hardware.org/?probe=b8ac11cfd3) | Jan 08, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [9f84e9b911](https://linux-hardware.org/?probe=9f84e9b911) | Jan 07, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [153f5dbeb5](https://linux-hardware.org/?probe=153f5dbeb5) | Jan 07, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [c8a281879a](https://linux-hardware.org/?probe=c8a281879a) | Jan 07, 2023 |
| ASUSTek       | H61M-C                      | Desktop     | [494e552521](https://linux-hardware.org/?probe=494e552521) | Jan 07, 2023 |
| HP            | 240 G8                      | Notebook    | [efc7e61483](https://linux-hardware.org/?probe=efc7e61483) | Jan 06, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [94d61ca559](https://linux-hardware.org/?probe=94d61ca559) | Jan 06, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [01b93cba09](https://linux-hardware.org/?probe=01b93cba09) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | Notebook    | [4853686d6c](https://linux-hardware.org/?probe=4853686d6c) | Jan 05, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [72f8edfe5b](https://linux-hardware.org/?probe=72f8edfe5b) | Jan 04, 2023 |
| Toshiba       | Satellite C75D-B            | Notebook    | [d5380976a2](https://linux-hardware.org/?probe=d5380976a2) | Jan 03, 2023 |
| HP            | 8459                        | Desktop     | [18f44a4e07](https://linux-hardware.org/?probe=18f44a4e07) | Jan 03, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | Notebook    | [373efc41b0](https://linux-hardware.org/?probe=373efc41b0) | Jan 03, 2023 |
| Lenovo        | ThinkPad T530 24296FG       | Notebook    | [303cb1bd6f](https://linux-hardware.org/?probe=303cb1bd6f) | Jan 02, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [63c7138092](https://linux-hardware.org/?probe=63c7138092) | Jan 02, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1229c65c83](https://linux-hardware.org/?probe=1229c65c83) | Jan 02, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [7ef67aea7b](https://linux-hardware.org/?probe=7ef67aea7b) | Jan 02, 2023 |
| Dell          | Inspiron 5580               | Notebook    | [c6a044c898](https://linux-hardware.org/?probe=c6a044c898) | Jan 01, 2023 |
| Dell          | Latitude E7240              | Notebook    | [ca82922df4](https://linux-hardware.org/?probe=ca82922df4) | Jan 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [178dcba2a5](https://linux-hardware.org/?probe=178dcba2a5) | Jan 01, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [f871c26332](https://linux-hardware.org/?probe=f871c26332) | Jan 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [8582096251](https://linux-hardware.org/?probe=8582096251) | Dec 31, 2022 |
| MAXSUN        | MS-TZZ A320M.2-VH           | Desktop     | [8f06578f10](https://linux-hardware.org/?probe=8f06578f10) | Dec 31, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [4393041949](https://linux-hardware.org/?probe=4393041949) | Dec 30, 2022 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [4e6065532f](https://linux-hardware.org/?probe=4e6065532f) | Dec 30, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [3b0d4e8973](https://linux-hardware.org/?probe=3b0d4e8973) | Dec 30, 2022 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [1c46a3fdd3](https://linux-hardware.org/?probe=1c46a3fdd3) | Dec 29, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [1e7182cb70](https://linux-hardware.org/?probe=1e7182cb70) | Dec 29, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [daf7777113](https://linux-hardware.org/?probe=daf7777113) | Dec 29, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [47f95e17c5](https://linux-hardware.org/?probe=47f95e17c5) | Dec 28, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [7c6adb6279](https://linux-hardware.org/?probe=7c6adb6279) | Dec 28, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [59b38f9b63](https://linux-hardware.org/?probe=59b38f9b63) | Dec 28, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [2d572d06d7](https://linux-hardware.org/?probe=2d572d06d7) | Dec 28, 2022 |
| MSI           | GT60                        | Notebook    | [3917ca13e3](https://linux-hardware.org/?probe=3917ca13e3) | Dec 26, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [cbe4c82d15](https://linux-hardware.org/?probe=cbe4c82d15) | Dec 26, 2022 |
| HP            | 3397                        | Desktop     | [c546bb007b](https://linux-hardware.org/?probe=c546bb007b) | Dec 26, 2022 |
| HP            | 3397                        | Desktop     | [4286520907](https://linux-hardware.org/?probe=4286520907) | Dec 26, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [8636b69474](https://linux-hardware.org/?probe=8636b69474) | Dec 25, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [a375cc62c7](https://linux-hardware.org/?probe=a375cc62c7) | Dec 24, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [4ea620705d](https://linux-hardware.org/?probe=4ea620705d) | Dec 24, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [04282775ba](https://linux-hardware.org/?probe=04282775ba) | Dec 24, 2022 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [a67d24c9f9](https://linux-hardware.org/?probe=a67d24c9f9) | Dec 23, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [6b2cd55178](https://linux-hardware.org/?probe=6b2cd55178) | Dec 23, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [c36553b2b8](https://linux-hardware.org/?probe=c36553b2b8) | Dec 23, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [c603811f9a](https://linux-hardware.org/?probe=c603811f9a) | Dec 22, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [bfe7b1ec1d](https://linux-hardware.org/?probe=bfe7b1ec1d) | Dec 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [47ac3ac319](https://linux-hardware.org/?probe=47ac3ac319) | Dec 21, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [3832e7e0af](https://linux-hardware.org/?probe=3832e7e0af) | Dec 21, 2022 |
| Acer          | Aspire A515-52              | Notebook    | [b052f8434a](https://linux-hardware.org/?probe=b052f8434a) | Dec 20, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [8a7ee1147b](https://linux-hardware.org/?probe=8a7ee1147b) | Dec 20, 2022 |
| MSI           | Boston                      | Desktop     | [8587c9cf45](https://linux-hardware.org/?probe=8587c9cf45) | Dec 19, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [900fd62aaf](https://linux-hardware.org/?probe=900fd62aaf) | Dec 19, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [b34721e6cb](https://linux-hardware.org/?probe=b34721e6cb) | Dec 19, 2022 |
| MSI           | GL63 8RC                    | Notebook    | [6a5bc85513](https://linux-hardware.org/?probe=6a5bc85513) | Dec 18, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [b4d6964157](https://linux-hardware.org/?probe=b4d6964157) | Dec 18, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [0a7621cb40](https://linux-hardware.org/?probe=0a7621cb40) | Dec 17, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [be93cca77c](https://linux-hardware.org/?probe=be93cca77c) | Dec 17, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [9caae58821](https://linux-hardware.org/?probe=9caae58821) | Dec 16, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [5a071587fb](https://linux-hardware.org/?probe=5a071587fb) | Dec 15, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e647deca28](https://linux-hardware.org/?probe=e647deca28) | Dec 14, 2022 |
| MSI           | X370 SLI PLUS               | Desktop     | [7c32d0f453](https://linux-hardware.org/?probe=7c32d0f453) | Dec 14, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [c8ffea5473](https://linux-hardware.org/?probe=c8ffea5473) | Dec 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [5ea80edee8](https://linux-hardware.org/?probe=5ea80edee8) | Dec 14, 2022 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [72b3306c33](https://linux-hardware.org/?probe=72b3306c33) | Dec 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [6fc042d213](https://linux-hardware.org/?probe=6fc042d213) | Dec 13, 2022 |
| MSI           | MEG B550 UNIFY              | Desktop     | [e9a996b54a](https://linux-hardware.org/?probe=e9a996b54a) | Dec 12, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [8111a18c7c](https://linux-hardware.org/?probe=8111a18c7c) | Dec 12, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [b7b1ed9d8b](https://linux-hardware.org/?probe=b7b1ed9d8b) | Dec 12, 2022 |
| Samsung       | 930X5J/910S5J/940X5J        | Notebook    | [deb721084b](https://linux-hardware.org/?probe=deb721084b) | Dec 11, 2022 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [01decbbb6d](https://linux-hardware.org/?probe=01decbbb6d) | Dec 10, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [6f97813144](https://linux-hardware.org/?probe=6f97813144) | Dec 10, 2022 |
| Dell          | G5 5505                     | Notebook    | [60053b5d4b](https://linux-hardware.org/?probe=60053b5d4b) | Dec 10, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | Notebook    | [ad87e1559a](https://linux-hardware.org/?probe=ad87e1559a) | Dec 09, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [ea91fc57ae](https://linux-hardware.org/?probe=ea91fc57ae) | Dec 09, 2022 |
| Lenovo        | ThinkPad T520 4243CJ2       | Notebook    | [93e5e0ca9b](https://linux-hardware.org/?probe=93e5e0ca9b) | Dec 08, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [1c73b61db3](https://linux-hardware.org/?probe=1c73b61db3) | Dec 08, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [2d35fb5bbb](https://linux-hardware.org/?probe=2d35fb5bbb) | Dec 08, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [6844d4578b](https://linux-hardware.org/?probe=6844d4578b) | Dec 07, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [82d49749a2](https://linux-hardware.org/?probe=82d49749a2) | Dec 07, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [3e50ee3f94](https://linux-hardware.org/?probe=3e50ee3f94) | Dec 07, 2022 |
| HP            | Laptop 17-ak0xx             | Notebook    | [9fb5c9d094](https://linux-hardware.org/?probe=9fb5c9d094) | Dec 06, 2022 |
| Dell          | Latitude 7490               | Notebook    | [7377ad6d99](https://linux-hardware.org/?probe=7377ad6d99) | Dec 05, 2022 |
| Lenovo        | ThinkPad neo 14 21DN0009... | Notebook    | [80c8d84387](https://linux-hardware.org/?probe=80c8d84387) | Dec 05, 2022 |
| HP            | 245 G7                      | Notebook    | [57ed16df1f](https://linux-hardware.org/?probe=57ed16df1f) | Dec 05, 2022 |
| MSI           | X370 SLI PLUS               | Desktop     | [e6941ba491](https://linux-hardware.org/?probe=e6941ba491) | Dec 05, 2022 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [41a365e56e](https://linux-hardware.org/?probe=41a365e56e) | Dec 04, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [db7cd6f0dc](https://linux-hardware.org/?probe=db7cd6f0dc) | Dec 04, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [cbb4692837](https://linux-hardware.org/?probe=cbb4692837) | Dec 04, 2022 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [8dd6905ba5](https://linux-hardware.org/?probe=8dd6905ba5) | Dec 03, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3807efd1f4](https://linux-hardware.org/?probe=3807efd1f4) | Dec 03, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [77651c30c5](https://linux-hardware.org/?probe=77651c30c5) | Dec 03, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [38d691df3b](https://linux-hardware.org/?probe=38d691df3b) | Dec 03, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [56a2d42adc](https://linux-hardware.org/?probe=56a2d42adc) | Dec 02, 2022 |
| Dell          | Inspiron 16 5625            | Notebook    | [6e1523c2e8](https://linux-hardware.org/?probe=6e1523c2e8) | Dec 02, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [8b85688e36](https://linux-hardware.org/?probe=8b85688e36) | Dec 02, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [2414a84e4f](https://linux-hardware.org/?probe=2414a84e4f) | Dec 02, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [0e87a76042](https://linux-hardware.org/?probe=0e87a76042) | Dec 01, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [a4ae0cdd6a](https://linux-hardware.org/?probe=a4ae0cdd6a) | Dec 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [0aa3ec7616](https://linux-hardware.org/?probe=0aa3ec7616) | Nov 30, 2022 |
| Unknown       | X99H                        | Desktop     | [b9e2236de7](https://linux-hardware.org/?probe=b9e2236de7) | Nov 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [a6a71120f2](https://linux-hardware.org/?probe=a6a71120f2) | Nov 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d7025eb475](https://linux-hardware.org/?probe=d7025eb475) | Nov 30, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [f4fa3a4e7f](https://linux-hardware.org/?probe=f4fa3a4e7f) | Nov 30, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [3f19147b70](https://linux-hardware.org/?probe=3f19147b70) | Nov 29, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [6bb64e8108](https://linux-hardware.org/?probe=6bb64e8108) | Nov 29, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [bc3188dd75](https://linux-hardware.org/?probe=bc3188dd75) | Nov 29, 2022 |
| Acer          | Nitro AN515-51              | Notebook    | [ba6d4f20e7](https://linux-hardware.org/?probe=ba6d4f20e7) | Nov 29, 2022 |
| Dell          | Inspiron 16 5625            | Notebook    | [50912d5fa9](https://linux-hardware.org/?probe=50912d5fa9) | Nov 29, 2022 |
| Dell          | Inspiron 16 5625            | Notebook    | [22da2f8729](https://linux-hardware.org/?probe=22da2f8729) | Nov 28, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [624e6b243c](https://linux-hardware.org/?probe=624e6b243c) | Nov 28, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [54e985a956](https://linux-hardware.org/?probe=54e985a956) | Nov 28, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [68e68e1e01](https://linux-hardware.org/?probe=68e68e1e01) | Nov 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [8fa53292bf](https://linux-hardware.org/?probe=8fa53292bf) | Nov 27, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [d95233ff31](https://linux-hardware.org/?probe=d95233ff31) | Nov 26, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [20015fb913](https://linux-hardware.org/?probe=20015fb913) | Nov 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [07363955de](https://linux-hardware.org/?probe=07363955de) | Nov 26, 2022 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [0c97f1e481](https://linux-hardware.org/?probe=0c97f1e481) | Nov 25, 2022 |
| Biostar       | H310MHC2                    | Desktop     | [49e09047c4](https://linux-hardware.org/?probe=49e09047c4) | Nov 25, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [45dc299d52](https://linux-hardware.org/?probe=45dc299d52) | Nov 25, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [1c648060f6](https://linux-hardware.org/?probe=1c648060f6) | Nov 25, 2022 |
| MSI           | H81M-E33                    | Desktop     | [80ec8663ac](https://linux-hardware.org/?probe=80ec8663ac) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ccf106edce](https://linux-hardware.org/?probe=ccf106edce) | Nov 24, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [b154300490](https://linux-hardware.org/?probe=b154300490) | Nov 24, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [43fe4ed852](https://linux-hardware.org/?probe=43fe4ed852) | Nov 24, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | Notebook    | [10e706472c](https://linux-hardware.org/?probe=10e706472c) | Nov 24, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [0f96032f10](https://linux-hardware.org/?probe=0f96032f10) | Nov 24, 2022 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [a5005bf517](https://linux-hardware.org/?probe=a5005bf517) | Nov 24, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [c1e62a557c](https://linux-hardware.org/?probe=c1e62a557c) | Nov 24, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [ced8851dc3](https://linux-hardware.org/?probe=ced8851dc3) | Nov 23, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [990ff088e8](https://linux-hardware.org/?probe=990ff088e8) | Nov 22, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [a5dcbbbacd](https://linux-hardware.org/?probe=a5dcbbbacd) | Nov 22, 2022 |
| Dell          | Precision 5510              | Notebook    | [63c0b8aa0c](https://linux-hardware.org/?probe=63c0b8aa0c) | Nov 21, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [ac4a817e75](https://linux-hardware.org/?probe=ac4a817e75) | Nov 21, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [3b9a05e385](https://linux-hardware.org/?probe=3b9a05e385) | Nov 21, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [489ded27aa](https://linux-hardware.org/?probe=489ded27aa) | Nov 21, 2022 |
| ASUSTek       | X45C                        | Notebook    | [02a232c4ef](https://linux-hardware.org/?probe=02a232c4ef) | Nov 21, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [09e98d8c02](https://linux-hardware.org/?probe=09e98d8c02) | Nov 21, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [8478dece38](https://linux-hardware.org/?probe=8478dece38) | Nov 21, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [4d903aa73b](https://linux-hardware.org/?probe=4d903aa73b) | Nov 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b41f6ec236](https://linux-hardware.org/?probe=b41f6ec236) | Nov 21, 2022 |
| HP            | 18E7                        | Desktop     | [0b963b44fb](https://linux-hardware.org/?probe=0b963b44fb) | Nov 21, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [a890ae6d6c](https://linux-hardware.org/?probe=a890ae6d6c) | Nov 20, 2022 |
| HASEE Comp... | V1x0PNPx                    | Notebook    | [e75868724e](https://linux-hardware.org/?probe=e75868724e) | Nov 19, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [f5cbe0bfa2](https://linux-hardware.org/?probe=f5cbe0bfa2) | Nov 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [f10fc36516](https://linux-hardware.org/?probe=f10fc36516) | Nov 19, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [1755321c80](https://linux-hardware.org/?probe=1755321c80) | Nov 19, 2022 |
| HP            | Elite Dragonfly             | Convertible | [2630af5372](https://linux-hardware.org/?probe=2630af5372) | Nov 19, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [806ac66c75](https://linux-hardware.org/?probe=806ac66c75) | Nov 19, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [1af696c23c](https://linux-hardware.org/?probe=1af696c23c) | Nov 19, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [587db1b08f](https://linux-hardware.org/?probe=587db1b08f) | Nov 19, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [7de2db4d3a](https://linux-hardware.org/?probe=7de2db4d3a) | Nov 18, 2022 |
| Gigabyte      | H61M-USB3V                  | Desktop     | [e034e5bbb2](https://linux-hardware.org/?probe=e034e5bbb2) | Nov 18, 2022 |
| Lenovo        | Legion 5 82B5               | Notebook    | [907810c0ac](https://linux-hardware.org/?probe=907810c0ac) | Nov 18, 2022 |
| Dell          | 03GCPM A01                  | Server      | [396bc50b1c](https://linux-hardware.org/?probe=396bc50b1c) | Nov 18, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [a8847bb3ad](https://linux-hardware.org/?probe=a8847bb3ad) | Nov 18, 2022 |
| Dell          | 03GCPM A01                  | Server      | [53b560a9a9](https://linux-hardware.org/?probe=53b560a9a9) | Nov 18, 2022 |
| Dell          | 0X30MX A00                  | Desktop     | [c3657c7f97](https://linux-hardware.org/?probe=c3657c7f97) | Nov 18, 2022 |
| Exo           | Smart XS1                   | Notebook    | [d51bf05ac5](https://linux-hardware.org/?probe=d51bf05ac5) | Nov 17, 2022 |
| Dell          | Latitude 5530               | Notebook    | [35a6ba0a9f](https://linux-hardware.org/?probe=35a6ba0a9f) | Nov 17, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [e9eb63ca62](https://linux-hardware.org/?probe=e9eb63ca62) | Nov 17, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [5d1e2af2ea](https://linux-hardware.org/?probe=5d1e2af2ea) | Nov 17, 2022 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | Desktop     | [cd01bd7dad](https://linux-hardware.org/?probe=cd01bd7dad) | Nov 16, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [69b281a787](https://linux-hardware.org/?probe=69b281a787) | Nov 16, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [6b14e6a41b](https://linux-hardware.org/?probe=6b14e6a41b) | Nov 16, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [620dbe0a8f](https://linux-hardware.org/?probe=620dbe0a8f) | Nov 16, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [2d0fb1c5d1](https://linux-hardware.org/?probe=2d0fb1c5d1) | Nov 16, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [2455b541f5](https://linux-hardware.org/?probe=2455b541f5) | Nov 16, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [9cd3d86efc](https://linux-hardware.org/?probe=9cd3d86efc) | Nov 16, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [76d056b728](https://linux-hardware.org/?probe=76d056b728) | Nov 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1472f0a14e](https://linux-hardware.org/?probe=1472f0a14e) | Nov 15, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [5e6c94e04c](https://linux-hardware.org/?probe=5e6c94e04c) | Nov 15, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [699ea2cc17](https://linux-hardware.org/?probe=699ea2cc17) | Nov 15, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ea39f5300c](https://linux-hardware.org/?probe=ea39f5300c) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [d6b19cfd9d](https://linux-hardware.org/?probe=d6b19cfd9d) | Nov 15, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [459c5879e6](https://linux-hardware.org/?probe=459c5879e6) | Nov 15, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [74cfc7d01e](https://linux-hardware.org/?probe=74cfc7d01e) | Nov 15, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [ecdad4661a](https://linux-hardware.org/?probe=ecdad4661a) | Nov 15, 2022 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [07d6aa9adc](https://linux-hardware.org/?probe=07d6aa9adc) | Nov 14, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [4a19565db2](https://linux-hardware.org/?probe=4a19565db2) | Nov 14, 2022 |
| ASUSTek       | CM6870                      | Desktop     | [c050452a72](https://linux-hardware.org/?probe=c050452a72) | Nov 14, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [5b9f10af19](https://linux-hardware.org/?probe=5b9f10af19) | Nov 14, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [c332019d7e](https://linux-hardware.org/?probe=c332019d7e) | Nov 14, 2022 |
| Samsung       | 730QDA                      | Convertible | [169bdd2f71](https://linux-hardware.org/?probe=169bdd2f71) | Nov 13, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [9d942ddc9c](https://linux-hardware.org/?probe=9d942ddc9c) | Nov 13, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [2c896d28a8](https://linux-hardware.org/?probe=2c896d28a8) | Nov 13, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [97bfce0a04](https://linux-hardware.org/?probe=97bfce0a04) | Nov 13, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [be61d3792c](https://linux-hardware.org/?probe=be61d3792c) | Nov 13, 2022 |
| Dell          | G3 3579                     | Notebook    | [a2e410da57](https://linux-hardware.org/?probe=a2e410da57) | Nov 12, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [aea8b4a908](https://linux-hardware.org/?probe=aea8b4a908) | Nov 12, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [4aa0411587](https://linux-hardware.org/?probe=4aa0411587) | Nov 12, 2022 |
| Alienware     | Area-51m                    | Notebook    | [11c59a838f](https://linux-hardware.org/?probe=11c59a838f) | Nov 12, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [256503ef7e](https://linux-hardware.org/?probe=256503ef7e) | Nov 12, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [eb533b483e](https://linux-hardware.org/?probe=eb533b483e) | Nov 12, 2022 |
| Dell          | Latitude E6420              | Notebook    | [056daa7806](https://linux-hardware.org/?probe=056daa7806) | Nov 12, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [c73b422075](https://linux-hardware.org/?probe=c73b422075) | Nov 12, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [cedb086e46](https://linux-hardware.org/?probe=cedb086e46) | Nov 12, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [eb5ece0bb3](https://linux-hardware.org/?probe=eb5ece0bb3) | Nov 12, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [6eedcdeb01](https://linux-hardware.org/?probe=6eedcdeb01) | Nov 11, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [adf09c8455](https://linux-hardware.org/?probe=adf09c8455) | Nov 11, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [270045ffa3](https://linux-hardware.org/?probe=270045ffa3) | Nov 11, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [022a97b52e](https://linux-hardware.org/?probe=022a97b52e) | Nov 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [3f11ca7016](https://linux-hardware.org/?probe=3f11ca7016) | Nov 11, 2022 |
| ASUSTek       | X550JD                      | Notebook    | [9c88cc6c32](https://linux-hardware.org/?probe=9c88cc6c32) | Nov 11, 2022 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [07bae444fc](https://linux-hardware.org/?probe=07bae444fc) | Nov 11, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [68e5509696](https://linux-hardware.org/?probe=68e5509696) | Nov 11, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [2db7764d25](https://linux-hardware.org/?probe=2db7764d25) | Nov 11, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [2b59844827](https://linux-hardware.org/?probe=2b59844827) | Nov 11, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [578b9c0e61](https://linux-hardware.org/?probe=578b9c0e61) | Nov 11, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [0bd2321bee](https://linux-hardware.org/?probe=0bd2321bee) | Nov 11, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [ea30d00f9a](https://linux-hardware.org/?probe=ea30d00f9a) | Nov 10, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [f927960881](https://linux-hardware.org/?probe=f927960881) | Nov 10, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [b995c794aa](https://linux-hardware.org/?probe=b995c794aa) | Nov 10, 2022 |
| Monster       | ABRA A5 V15.6               | Notebook    | [3bf45390cc](https://linux-hardware.org/?probe=3bf45390cc) | Nov 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [fc22f217b3](https://linux-hardware.org/?probe=fc22f217b3) | Nov 10, 2022 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [7973c1467f](https://linux-hardware.org/?probe=7973c1467f) | Nov 10, 2022 |
| ASUSTek       | N752VX                      | Notebook    | [a5b6d827b2](https://linux-hardware.org/?probe=a5b6d827b2) | Nov 10, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [009f3d82e9](https://linux-hardware.org/?probe=009f3d82e9) | Nov 10, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [7638b6abf6](https://linux-hardware.org/?probe=7638b6abf6) | Nov 09, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [4366631db8](https://linux-hardware.org/?probe=4366631db8) | Nov 09, 2022 |
| Lenovo        | ThinkPad P53 20QQS44Q00     | Notebook    | [29ddbee669](https://linux-hardware.org/?probe=29ddbee669) | Nov 09, 2022 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [5bccf91e38](https://linux-hardware.org/?probe=5bccf91e38) | Nov 09, 2022 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [faf531627e](https://linux-hardware.org/?probe=faf531627e) | Nov 09, 2022 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [17c345f111](https://linux-hardware.org/?probe=17c345f111) | Nov 09, 2022 |
| MSI           | Modern 15 A11MU             | Notebook    | [b10bd50d9c](https://linux-hardware.org/?probe=b10bd50d9c) | Nov 09, 2022 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [b8dae15ebf](https://linux-hardware.org/?probe=b8dae15ebf) | Nov 09, 2022 |
| Dell          | Vostro 3401                 | Notebook    | [0b1b8bf15d](https://linux-hardware.org/?probe=0b1b8bf15d) | Nov 09, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [f49624457d](https://linux-hardware.org/?probe=f49624457d) | Nov 09, 2022 |
| Dell          | 0RW203 A00                  | Desktop     | [67fa42f70a](https://linux-hardware.org/?probe=67fa42f70a) | Nov 09, 2022 |
| Lenovo        | Legion 7 16IAX7 82TD        | Notebook    | [d224ed7da8](https://linux-hardware.org/?probe=d224ed7da8) | Nov 09, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [73c9a3d81e](https://linux-hardware.org/?probe=73c9a3d81e) | Nov 09, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [226409c98f](https://linux-hardware.org/?probe=226409c98f) | Nov 09, 2022 |
| Foxconn       | H61M-S/H61M                 | Desktop     | [81b2006fd3](https://linux-hardware.org/?probe=81b2006fd3) | Nov 09, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [423a8f624c](https://linux-hardware.org/?probe=423a8f624c) | Nov 08, 2022 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [3900976672](https://linux-hardware.org/?probe=3900976672) | Nov 08, 2022 |
| Lenovo        | ThinkPad T480 20L6S24N00    | Notebook    | [0b17fc5246](https://linux-hardware.org/?probe=0b17fc5246) | Nov 08, 2022 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [3a4a75d603](https://linux-hardware.org/?probe=3a4a75d603) | Nov 08, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [0b65e26932](https://linux-hardware.org/?probe=0b65e26932) | Nov 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [0144bb5a89](https://linux-hardware.org/?probe=0144bb5a89) | Nov 08, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [33b2dbfcc2](https://linux-hardware.org/?probe=33b2dbfcc2) | Nov 08, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [265707c6a3](https://linux-hardware.org/?probe=265707c6a3) | Nov 08, 2022 |
| HP            | Notebook                    | Notebook    | [5cbade7533](https://linux-hardware.org/?probe=5cbade7533) | Nov 08, 2022 |
| Intel         | NUC11TNBi3 M11908-403       | Mini pc     | [c949ec23ce](https://linux-hardware.org/?probe=c949ec23ce) | Nov 07, 2022 |
| Intel         | NUC11TNBi3 M11908-403       | Mini pc     | [02610c1e36](https://linux-hardware.org/?probe=02610c1e36) | Nov 07, 2022 |
| Dell          | Latitude 3410               | Notebook    | [f6532fe0ee](https://linux-hardware.org/?probe=f6532fe0ee) | Nov 07, 2022 |
| MSI           | MPG Z590 GAMING CARBON W... | Desktop     | [6987230f73](https://linux-hardware.org/?probe=6987230f73) | Nov 07, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [d87a3e023a](https://linux-hardware.org/?probe=d87a3e023a) | Nov 07, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3f207bc4c3](https://linux-hardware.org/?probe=3f207bc4c3) | Nov 07, 2022 |
| ASUSTek       | FX503VD                     | Notebook    | [0373b83f63](https://linux-hardware.org/?probe=0373b83f63) | Nov 06, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [5505ec9b09](https://linux-hardware.org/?probe=5505ec9b09) | Nov 06, 2022 |
| HP            | Pavilion g6                 | Notebook    | [43eefaca07](https://linux-hardware.org/?probe=43eefaca07) | Nov 06, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [38d24e4b4a](https://linux-hardware.org/?probe=38d24e4b4a) | Nov 06, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [47ca2c5cb7](https://linux-hardware.org/?probe=47ca2c5cb7) | Nov 06, 2022 |
| Quanta        | TWS                         | Notebook    | [1ad872afcd](https://linux-hardware.org/?probe=1ad872afcd) | Nov 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [af69f66287](https://linux-hardware.org/?probe=af69f66287) | Nov 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [256002ea80](https://linux-hardware.org/?probe=256002ea80) | Nov 06, 2022 |
| Lenovo        | ThinkPad A275 20KDS01S00    | Notebook    | [a8eacd4e3a](https://linux-hardware.org/?probe=a8eacd4e3a) | Nov 06, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [12c49f9e36](https://linux-hardware.org/?probe=12c49f9e36) | Nov 05, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [55b349ab41](https://linux-hardware.org/?probe=55b349ab41) | Nov 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [d9952c90a5](https://linux-hardware.org/?probe=d9952c90a5) | Nov 05, 2022 |
| Dell          | Inspiron 15 3510            | Notebook    | [fb8bc290d6](https://linux-hardware.org/?probe=fb8bc290d6) | Nov 05, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [e8a62297a5](https://linux-hardware.org/?probe=e8a62297a5) | Nov 05, 2022 |
| TUXEDO        | Stellaris Intel Gen4        | Notebook    | [2b4987c9e8](https://linux-hardware.org/?probe=2b4987c9e8) | Nov 05, 2022 |
| ASUSTek       | Zenbook UX5401EA_UX5401E... | Notebook    | [84bf8d9578](https://linux-hardware.org/?probe=84bf8d9578) | Nov 05, 2022 |
| ASUSTek       | PRO H410T                   | Desktop     | [66a809ab24](https://linux-hardware.org/?probe=66a809ab24) | Nov 05, 2022 |
| ASUSTek       | FX503VD                     | Notebook    | [f80b5eaa0b](https://linux-hardware.org/?probe=f80b5eaa0b) | Nov 05, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [e29a593971](https://linux-hardware.org/?probe=e29a593971) | Nov 05, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [56db615f30](https://linux-hardware.org/?probe=56db615f30) | Nov 05, 2022 |
| Timi          | RedmiBook 14 II             | Notebook    | [374be77f36](https://linux-hardware.org/?probe=374be77f36) | Nov 05, 2022 |
| Dell          | Inspiron 15 3510            | Notebook    | [f0f862d5c5](https://linux-hardware.org/?probe=f0f862d5c5) | Nov 05, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [3c8b130af7](https://linux-hardware.org/?probe=3c8b130af7) | Nov 05, 2022 |
| Dell          | Latitude 5591               | Notebook    | [e0e1ffe014](https://linux-hardware.org/?probe=e0e1ffe014) | Nov 05, 2022 |
| Dell          | Latitude 5591               | Notebook    | [b649030512](https://linux-hardware.org/?probe=b649030512) | Nov 05, 2022 |
| Acer          | Aspire 4820T                | Notebook    | [300aa32e45](https://linux-hardware.org/?probe=300aa32e45) | Nov 04, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [02a767e075](https://linux-hardware.org/?probe=02a767e075) | Nov 04, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [2c605465bb](https://linux-hardware.org/?probe=2c605465bb) | Nov 04, 2022 |
| HP            | 339A                        | Desktop     | [77ddeeda51](https://linux-hardware.org/?probe=77ddeeda51) | Nov 04, 2022 |
| HP            | 339A                        | Desktop     | [8ebb8b6522](https://linux-hardware.org/?probe=8ebb8b6522) | Nov 04, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [3614ee4149](https://linux-hardware.org/?probe=3614ee4149) | Nov 04, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [4e666fbb8f](https://linux-hardware.org/?probe=4e666fbb8f) | Nov 04, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [c58816cb3d](https://linux-hardware.org/?probe=c58816cb3d) | Nov 04, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [af85812864](https://linux-hardware.org/?probe=af85812864) | Nov 04, 2022 |
| Packard Be... | EasyNote LX                 | Notebook    | [41070f6bfe](https://linux-hardware.org/?probe=41070f6bfe) | Nov 04, 2022 |
| HP            | 2B05                        | Desktop     | [5c0a96cd5b](https://linux-hardware.org/?probe=5c0a96cd5b) | Nov 04, 2022 |
| HP            | 2B05                        | Desktop     | [95b5255056](https://linux-hardware.org/?probe=95b5255056) | Nov 04, 2022 |
| GEO           | GEOBOOK 2E                  | Notebook    | [2a802edc5a](https://linux-hardware.org/?probe=2a802edc5a) | Nov 04, 2022 |
| GEO           | GEOBOOK 2E                  | Notebook    | [80e1206b6d](https://linux-hardware.org/?probe=80e1206b6d) | Nov 04, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [c39a19fa2f](https://linux-hardware.org/?probe=c39a19fa2f) | Nov 04, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [775987aacb](https://linux-hardware.org/?probe=775987aacb) | Nov 04, 2022 |
| Lenovo        | ThinkPad Yoga 11e 5th Ge... | Convertible | [876fc02284](https://linux-hardware.org/?probe=876fc02284) | Nov 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [0c186f330b](https://linux-hardware.org/?probe=0c186f330b) | Nov 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [2d53ffb628](https://linux-hardware.org/?probe=2d53ffb628) | Nov 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | Desktop     | [f027f3a4e2](https://linux-hardware.org/?probe=f027f3a4e2) | Nov 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | Desktop     | [cb9374e939](https://linux-hardware.org/?probe=cb9374e939) | Nov 04, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [41e941e3ca](https://linux-hardware.org/?probe=41e941e3ca) | Nov 03, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [3480a7be5a](https://linux-hardware.org/?probe=3480a7be5a) | Nov 03, 2022 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | Notebook    | [7a2dab8dde](https://linux-hardware.org/?probe=7a2dab8dde) | Nov 03, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [24eea2c3f7](https://linux-hardware.org/?probe=24eea2c3f7) | Nov 03, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [ec0599883c](https://linux-hardware.org/?probe=ec0599883c) | Nov 03, 2022 |
| Acer          | Predator G9-591             | Notebook    | [ca65bba88a](https://linux-hardware.org/?probe=ca65bba88a) | Nov 03, 2022 |
| Intel         | NUC5i5MYBE H47797-202       | Mini pc     | [01381d41de](https://linux-hardware.org/?probe=01381d41de) | Nov 03, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [a189602082](https://linux-hardware.org/?probe=a189602082) | Nov 03, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [98e419a04d](https://linux-hardware.org/?probe=98e419a04d) | Nov 03, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [921a646464](https://linux-hardware.org/?probe=921a646464) | Nov 03, 2022 |
| Toshiba       | Satellite S55-A             | Notebook    | [cfc6040185](https://linux-hardware.org/?probe=cfc6040185) | Nov 03, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [03447f0763](https://linux-hardware.org/?probe=03447f0763) | Nov 03, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [457cdcf84a](https://linux-hardware.org/?probe=457cdcf84a) | Nov 03, 2022 |
| MSI           | Katana GF76 12UE            | Notebook    | [4359d2a528](https://linux-hardware.org/?probe=4359d2a528) | Nov 02, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [2a280dc7df](https://linux-hardware.org/?probe=2a280dc7df) | Nov 02, 2022 |
| Lenovo        | ThinkPad T61 6464A13        | Notebook    | [5f850cbab6](https://linux-hardware.org/?probe=5f850cbab6) | Nov 02, 2022 |
| Intel         | NUC5i5MYBE H47797-202       | Mini pc     | [41a93c4dfa](https://linux-hardware.org/?probe=41a93c4dfa) | Nov 02, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [c9041d22be](https://linux-hardware.org/?probe=c9041d22be) | Nov 02, 2022 |
| ASUSTek       | Z590 WIFI GUNDAM EDITION    | Desktop     | [74f8de9f71](https://linux-hardware.org/?probe=74f8de9f71) | Nov 02, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [2069a0e7fc](https://linux-hardware.org/?probe=2069a0e7fc) | Nov 02, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [4fa32ec6af](https://linux-hardware.org/?probe=4fa32ec6af) | Nov 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2d931f9e99](https://linux-hardware.org/?probe=2d931f9e99) | Nov 02, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [335af8b89b](https://linux-hardware.org/?probe=335af8b89b) | Nov 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [22b32d9bac](https://linux-hardware.org/?probe=22b32d9bac) | Nov 02, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [ec359017a2](https://linux-hardware.org/?probe=ec359017a2) | Nov 02, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [d4ac3a5f04](https://linux-hardware.org/?probe=d4ac3a5f04) | Nov 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [63bf11c696](https://linux-hardware.org/?probe=63bf11c696) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a156a7484d](https://linux-hardware.org/?probe=a156a7484d) | Nov 02, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [7b51138a0b](https://linux-hardware.org/?probe=7b51138a0b) | Nov 02, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [d3beec5427](https://linux-hardware.org/?probe=d3beec5427) | Nov 02, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [9b093574b9](https://linux-hardware.org/?probe=9b093574b9) | Nov 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [24c2a01761](https://linux-hardware.org/?probe=24c2a01761) | Nov 02, 2022 |
| Dell          | Latitude 5591               | Notebook    | [bcd8aef9a0](https://linux-hardware.org/?probe=bcd8aef9a0) | Nov 02, 2022 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [dfe5dc3d95](https://linux-hardware.org/?probe=dfe5dc3d95) | Nov 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [c90b358eb5](https://linux-hardware.org/?probe=c90b358eb5) | Nov 01, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [379443a5d6](https://linux-hardware.org/?probe=379443a5d6) | Nov 01, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [9b61195a2a](https://linux-hardware.org/?probe=9b61195a2a) | Nov 01, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [5e099af04c](https://linux-hardware.org/?probe=5e099af04c) | Nov 01, 2022 |
| HP            | 829E                        | Mini pc     | [f568895fbb](https://linux-hardware.org/?probe=f568895fbb) | Nov 01, 2022 |
| Gigabyte      | B550 UD AC                  | Desktop     | [c5a5219cf3](https://linux-hardware.org/?probe=c5a5219cf3) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [e101d9d50a](https://linux-hardware.org/?probe=e101d9d50a) | Nov 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [766e7fb0d0](https://linux-hardware.org/?probe=766e7fb0d0) | Nov 01, 2022 |
| Unknown       | Unknown                     | Notebook    | [9608724116](https://linux-hardware.org/?probe=9608724116) | Nov 01, 2022 |
| MSI           | H81M-E33                    | Desktop     | [ee4c33d7b1](https://linux-hardware.org/?probe=ee4c33d7b1) | Nov 01, 2022 |
| Dell          | Venue 8 Pro 5830            | Notebook    | [8890410dfc](https://linux-hardware.org/?probe=8890410dfc) | Nov 01, 2022 |
| HP            | 339A                        | Desktop     | [68392c18c9](https://linux-hardware.org/?probe=68392c18c9) | Nov 01, 2022 |
| Dell          | Latitude 3420               | Notebook    | [9c2b9ab298](https://linux-hardware.org/?probe=9c2b9ab298) | Nov 01, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [d63c5de91b](https://linux-hardware.org/?probe=d63c5de91b) | Nov 01, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [f6b6afc8a3](https://linux-hardware.org/?probe=f6b6afc8a3) | Nov 01, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [274a3383db](https://linux-hardware.org/?probe=274a3383db) | Oct 31, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [0424e08b3d](https://linux-hardware.org/?probe=0424e08b3d) | Oct 31, 2022 |
| Samsung       | 800G5M/800G5W               | Notebook    | [c91800e8c1](https://linux-hardware.org/?probe=c91800e8c1) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | Notebook    | [46f1da66b6](https://linux-hardware.org/?probe=46f1da66b6) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | Notebook    | [1409a7f78d](https://linux-hardware.org/?probe=1409a7f78d) | Oct 31, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [71cf98e6e8](https://linux-hardware.org/?probe=71cf98e6e8) | Oct 31, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [a2a8473e4b](https://linux-hardware.org/?probe=a2a8473e4b) | Oct 31, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [fffb5288e0](https://linux-hardware.org/?probe=fffb5288e0) | Oct 31, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ce4bda1df2](https://linux-hardware.org/?probe=ce4bda1df2) | Oct 31, 2022 |
| ASUSTek       | X541UVK                     | Notebook    | [15bdbbf952](https://linux-hardware.org/?probe=15bdbbf952) | Oct 31, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7433eae90a](https://linux-hardware.org/?probe=7433eae90a) | Oct 31, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [479fdd085d](https://linux-hardware.org/?probe=479fdd085d) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [dfde89926c](https://linux-hardware.org/?probe=dfde89926c) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [135f93d663](https://linux-hardware.org/?probe=135f93d663) | Oct 31, 2022 |
| Dell          | Precision M6700             | Notebook    | [aa4b5e4400](https://linux-hardware.org/?probe=aa4b5e4400) | Oct 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [4ac9bf1711](https://linux-hardware.org/?probe=4ac9bf1711) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [002ab67e5e](https://linux-hardware.org/?probe=002ab67e5e) | Oct 31, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [76906648cb](https://linux-hardware.org/?probe=76906648cb) | Oct 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1deed25a21](https://linux-hardware.org/?probe=1deed25a21) | Oct 30, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [cf460716f9](https://linux-hardware.org/?probe=cf460716f9) | Oct 30, 2022 |
| Dell          | Inspiron 14 7425 2-in-1     | Convertible | [e427e48710](https://linux-hardware.org/?probe=e427e48710) | Oct 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3f69e984d1](https://linux-hardware.org/?probe=3f69e984d1) | Oct 30, 2022 |
| Sony          | VAIO                        | All in one  | [b295b1cb6f](https://linux-hardware.org/?probe=b295b1cb6f) | Oct 30, 2022 |
| MSI           | B250M GAMING PRO            | Desktop     | [98979beea7](https://linux-hardware.org/?probe=98979beea7) | Oct 30, 2022 |
| HP            | 15                          | Notebook    | [c356a2b0cd](https://linux-hardware.org/?probe=c356a2b0cd) | Oct 30, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [cfe35367bf](https://linux-hardware.org/?probe=cfe35367bf) | Oct 30, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [c52b1fe5fa](https://linux-hardware.org/?probe=c52b1fe5fa) | Oct 30, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [f1478df888](https://linux-hardware.org/?probe=f1478df888) | Oct 30, 2022 |
| HP            | EliteBook x360 1040 G6      | Convertible | [197c77e88c](https://linux-hardware.org/?probe=197c77e88c) | Oct 30, 2022 |
| HP            | EliteBook x360 1040 G6      | Convertible | [12e08a7d27](https://linux-hardware.org/?probe=12e08a7d27) | Oct 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [df654ca0b1](https://linux-hardware.org/?probe=df654ca0b1) | Oct 30, 2022 |
| Dell          | Latitude E7450              | Notebook    | [32a6333f4b](https://linux-hardware.org/?probe=32a6333f4b) | Oct 30, 2022 |
| Aquarius      | Cmp NS765                   | Notebook    | [5e519edbee](https://linux-hardware.org/?probe=5e519edbee) | Oct 30, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [60ba0bc2dd](https://linux-hardware.org/?probe=60ba0bc2dd) | Oct 29, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [1925c8ce1f](https://linux-hardware.org/?probe=1925c8ce1f) | Oct 29, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [b3dd383a83](https://linux-hardware.org/?probe=b3dd383a83) | Oct 29, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [da3e45d6c3](https://linux-hardware.org/?probe=da3e45d6c3) | Oct 29, 2022 |
| ASUSTek       | Q550LF                      | Notebook    | [383c45edce](https://linux-hardware.org/?probe=383c45edce) | Oct 29, 2022 |
| Dell          | Latitude E7450              | Notebook    | [012cd7214b](https://linux-hardware.org/?probe=012cd7214b) | Oct 29, 2022 |
| Dell          | Latitude E7450              | Notebook    | [635a60671d](https://linux-hardware.org/?probe=635a60671d) | Oct 29, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [ce9a718851](https://linux-hardware.org/?probe=ce9a718851) | Oct 28, 2022 |
| HP            | 82A5                        | Mini pc     | [c0be7985c0](https://linux-hardware.org/?probe=c0be7985c0) | Oct 28, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [2e4153161f](https://linux-hardware.org/?probe=2e4153161f) | Oct 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [2f6e4235f7](https://linux-hardware.org/?probe=2f6e4235f7) | Oct 28, 2022 |
| Lenovo        | ThinkPad P52 20M9S1EM00     | Notebook    | [40de74c5c5](https://linux-hardware.org/?probe=40de74c5c5) | Oct 28, 2022 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [e06398e1bc](https://linux-hardware.org/?probe=e06398e1bc) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [83179a6cea](https://linux-hardware.org/?probe=83179a6cea) | Oct 28, 2022 |
| Lenovo        | 3172 NOK                    | Mini pc     | [1ddbbf71eb](https://linux-hardware.org/?probe=1ddbbf71eb) | Oct 28, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [72102d6890](https://linux-hardware.org/?probe=72102d6890) | Oct 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [38135da604](https://linux-hardware.org/?probe=38135da604) | Oct 28, 2022 |
| Sony          | VPCCB3S1R                   | Notebook    | [ee5b1465a1](https://linux-hardware.org/?probe=ee5b1465a1) | Oct 28, 2022 |
| Microsoft     | Surface Go 3                | Tablet      | [85019658e9](https://linux-hardware.org/?probe=85019658e9) | Oct 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1d64fb48e7](https://linux-hardware.org/?probe=1d64fb48e7) | Oct 27, 2022 |
| Timi          | TM1701                      | Notebook    | [f246345845](https://linux-hardware.org/?probe=f246345845) | Oct 27, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [3a9f97607d](https://linux-hardware.org/?probe=3a9f97607d) | Oct 27, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [36b663cec7](https://linux-hardware.org/?probe=36b663cec7) | Oct 27, 2022 |
| MSI           | H81M-E33                    | Desktop     | [f0613bfce8](https://linux-hardware.org/?probe=f0613bfce8) | Oct 27, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [e00fd51503](https://linux-hardware.org/?probe=e00fd51503) | Oct 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [99152f7783](https://linux-hardware.org/?probe=99152f7783) | Oct 27, 2022 |
| Lenovo        | Yoga 720-13IKB              | Convertible | [1ca9551d4d](https://linux-hardware.org/?probe=1ca9551d4d) | Oct 27, 2022 |
| MSI           | Prestige 14 A10SC           | Notebook    | [263d47772c](https://linux-hardware.org/?probe=263d47772c) | Oct 27, 2022 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [aa2345213b](https://linux-hardware.org/?probe=aa2345213b) | Oct 27, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [7d30f96368](https://linux-hardware.org/?probe=7d30f96368) | Oct 27, 2022 |
| Lenovo        | ThinkPad X260 20F5S2WX05    | Notebook    | [710f95eab8](https://linux-hardware.org/?probe=710f95eab8) | Oct 27, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [d2debd1dab](https://linux-hardware.org/?probe=d2debd1dab) | Oct 26, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [85b4bc70fa](https://linux-hardware.org/?probe=85b4bc70fa) | Oct 26, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [3b9a4fb8f4](https://linux-hardware.org/?probe=3b9a4fb8f4) | Oct 26, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [6c7c7fa216](https://linux-hardware.org/?probe=6c7c7fa216) | Oct 26, 2022 |
| LincPlus      | P1                          | Notebook    | [cc97e9ec36](https://linux-hardware.org/?probe=cc97e9ec36) | Oct 26, 2022 |
| Lenovo        | 1048 SDK0Q40104 WIN 3915... | Desktop     | [2bed8fe9b1](https://linux-hardware.org/?probe=2bed8fe9b1) | Oct 26, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [0a658be9fc](https://linux-hardware.org/?probe=0a658be9fc) | Oct 26, 2022 |
| HP            | ProLiant ML350 G6           | Desktop     | [d080f0956b](https://linux-hardware.org/?probe=d080f0956b) | Oct 26, 2022 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | Desktop     | [958c0a2ae7](https://linux-hardware.org/?probe=958c0a2ae7) | Oct 25, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [b35333d9c0](https://linux-hardware.org/?probe=b35333d9c0) | Oct 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [a8c29545e6](https://linux-hardware.org/?probe=a8c29545e6) | Oct 25, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [6764a6860f](https://linux-hardware.org/?probe=6764a6860f) | Oct 25, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [c9123810fd](https://linux-hardware.org/?probe=c9123810fd) | Oct 25, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [6896f337ab](https://linux-hardware.org/?probe=6896f337ab) | Oct 25, 2022 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [0eb9c3ebff](https://linux-hardware.org/?probe=0eb9c3ebff) | Oct 25, 2022 |
| Dell          | Latitude 5500               | Notebook    | [6e1b321740](https://linux-hardware.org/?probe=6e1b321740) | Oct 25, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [29dd6b053b](https://linux-hardware.org/?probe=29dd6b053b) | Oct 25, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [0c63b974e1](https://linux-hardware.org/?probe=0c63b974e1) | Oct 25, 2022 |
| ASRock        | FM2A88M-HD+ R2.0            | Desktop     | [10e0a497e9](https://linux-hardware.org/?probe=10e0a497e9) | Oct 25, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [82fb357322](https://linux-hardware.org/?probe=82fb357322) | Oct 25, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [88e45a4e65](https://linux-hardware.org/?probe=88e45a4e65) | Oct 25, 2022 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [4474edfd79](https://linux-hardware.org/?probe=4474edfd79) | Oct 25, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [1537796302](https://linux-hardware.org/?probe=1537796302) | Oct 25, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [b14c37f999](https://linux-hardware.org/?probe=b14c37f999) | Oct 25, 2022 |
| MSI           | MAG A520M VECTOR WIFI       | Desktop     | [91a8a52c4a](https://linux-hardware.org/?probe=91a8a52c4a) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [4ffd604fea](https://linux-hardware.org/?probe=4ffd604fea) | Oct 25, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [a515dd93cd](https://linux-hardware.org/?probe=a515dd93cd) | Oct 25, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Core ... | Desktop     | [601e080563](https://linux-hardware.org/?probe=601e080563) | Oct 25, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [42647c28ba](https://linux-hardware.org/?probe=42647c28ba) | Oct 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [e4d7dc5f38](https://linux-hardware.org/?probe=e4d7dc5f38) | Oct 25, 2022 |
| System76      | Galago UltraPro             | Notebook    | [caf6a992bb](https://linux-hardware.org/?probe=caf6a992bb) | Oct 24, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [ad6b09bddc](https://linux-hardware.org/?probe=ad6b09bddc) | Oct 24, 2022 |
| Acer          | Aspire ES1-520              | Notebook    | [44375f0b06](https://linux-hardware.org/?probe=44375f0b06) | Oct 24, 2022 |
| ASRock        | Z170 Gaming K4              | Desktop     | [184139e7bc](https://linux-hardware.org/?probe=184139e7bc) | Oct 24, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | Desktop     | [3f6368ca5a](https://linux-hardware.org/?probe=3f6368ca5a) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [95ad909dc8](https://linux-hardware.org/?probe=95ad909dc8) | Oct 24, 2022 |
| HP            | 3048h                       | Desktop     | [3c3f7eda5e](https://linux-hardware.org/?probe=3c3f7eda5e) | Oct 24, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [aea737fcab](https://linux-hardware.org/?probe=aea737fcab) | Oct 24, 2022 |
| ASRock        | X370 Gaming K4              | Desktop     | [5658dbff1b](https://linux-hardware.org/?probe=5658dbff1b) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [0ca2dff493](https://linux-hardware.org/?probe=0ca2dff493) | Oct 24, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [2a57a65990](https://linux-hardware.org/?probe=2a57a65990) | Oct 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [5010a8ef47](https://linux-hardware.org/?probe=5010a8ef47) | Oct 24, 2022 |
| Dell          | Latitude E6420              | Notebook    | [eb53f0d580](https://linux-hardware.org/?probe=eb53f0d580) | Oct 24, 2022 |
| ASUSTek       | UX310UQ                     | Notebook    | [5a928ace3b](https://linux-hardware.org/?probe=5a928ace3b) | Oct 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [fe9ec739e2](https://linux-hardware.org/?probe=fe9ec739e2) | Oct 24, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | Notebook    | [c1a4fde481](https://linux-hardware.org/?probe=c1a4fde481) | Oct 24, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | Notebook    | [80bf151a4d](https://linux-hardware.org/?probe=80bf151a4d) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [8922b0767c](https://linux-hardware.org/?probe=8922b0767c) | Oct 24, 2022 |
| Lenovo        | ThinkPad X240 20AMS56K00    | Notebook    | [efa84f3716](https://linux-hardware.org/?probe=efa84f3716) | Oct 24, 2022 |
| Acer          | Nitro AN515-46              | Notebook    | [cb2480b22c](https://linux-hardware.org/?probe=cb2480b22c) | Oct 23, 2022 |
| Acer          | Nitro AN515-46              | Notebook    | [846cfe5273](https://linux-hardware.org/?probe=846cfe5273) | Oct 23, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [b9e4b934ee](https://linux-hardware.org/?probe=b9e4b934ee) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [22ea226b97](https://linux-hardware.org/?probe=22ea226b97) | Oct 23, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [41dce71fbf](https://linux-hardware.org/?probe=41dce71fbf) | Oct 23, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [b6b5c1468c](https://linux-hardware.org/?probe=b6b5c1468c) | Oct 23, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [22a96186fa](https://linux-hardware.org/?probe=22a96186fa) | Oct 23, 2022 |
| Dell          | Inspiron 1564               | Notebook    | [754b4a0f04](https://linux-hardware.org/?probe=754b4a0f04) | Oct 23, 2022 |
| HP            | Notebook                    | Notebook    | [d713217453](https://linux-hardware.org/?probe=d713217453) | Oct 23, 2022 |
| HP            | 86EE                        | All in one  | [4c631cdc18](https://linux-hardware.org/?probe=4c631cdc18) | Oct 22, 2022 |
| HP            | Notebook                    | Notebook    | [ef9adb0e8a](https://linux-hardware.org/?probe=ef9adb0e8a) | Oct 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b42893c91e](https://linux-hardware.org/?probe=b42893c91e) | Oct 22, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [b633b478aa](https://linux-hardware.org/?probe=b633b478aa) | Oct 22, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [b7ad660d88](https://linux-hardware.org/?probe=b7ad660d88) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [312828c6a3](https://linux-hardware.org/?probe=312828c6a3) | Oct 22, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [3e2bd05f56](https://linux-hardware.org/?probe=3e2bd05f56) | Oct 22, 2022 |
| MSI           | MAG B460M BAZOOKA           | Desktop     | [9cfe9f3c51](https://linux-hardware.org/?probe=9cfe9f3c51) | Oct 22, 2022 |
| Dell          | 0PP150 A00                  | Desktop     | [0e07990bda](https://linux-hardware.org/?probe=0e07990bda) | Oct 22, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [27c047341d](https://linux-hardware.org/?probe=27c047341d) | Oct 21, 2022 |
| Purism        | Librem 13 v2                | Notebook    | [5296ed1e19](https://linux-hardware.org/?probe=5296ed1e19) | Oct 21, 2022 |
| Unknown       | X79                         | Desktop     | [fd8f23bc70](https://linux-hardware.org/?probe=fd8f23bc70) | Oct 21, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [1ab730c85c](https://linux-hardware.org/?probe=1ab730c85c) | Oct 21, 2022 |
| Google        | Swanky                      | Notebook    | [19efb3ecc5](https://linux-hardware.org/?probe=19efb3ecc5) | Oct 21, 2022 |
| HP            | 8459                        | Desktop     | [c2ebcf9e20](https://linux-hardware.org/?probe=c2ebcf9e20) | Oct 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [60d4787bb7](https://linux-hardware.org/?probe=60d4787bb7) | Oct 21, 2022 |
| ASUSTek       | Q550LF                      | Notebook    | [0d24151944](https://linux-hardware.org/?probe=0d24151944) | Oct 21, 2022 |
| Itautec       | Infoway N8755               | Notebook    | [7eaba382a5](https://linux-hardware.org/?probe=7eaba382a5) | Oct 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [b374c2dff6](https://linux-hardware.org/?probe=b374c2dff6) | Oct 20, 2022 |
| Acer          | One S1003                   | Tablet      | [304c23119d](https://linux-hardware.org/?probe=304c23119d) | Oct 20, 2022 |
| Lenovo        | B560                        | Notebook    | [3a61700f49](https://linux-hardware.org/?probe=3a61700f49) | Oct 20, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [33a4634aab](https://linux-hardware.org/?probe=33a4634aab) | Oct 20, 2022 |
| Dell          | Inspiron 7460               | Notebook    | [879fabd350](https://linux-hardware.org/?probe=879fabd350) | Oct 20, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | Desktop     | [f03f1bb041](https://linux-hardware.org/?probe=f03f1bb041) | Oct 20, 2022 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [be48cfe3be](https://linux-hardware.org/?probe=be48cfe3be) | Oct 20, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [f966d5d584](https://linux-hardware.org/?probe=f966d5d584) | Oct 20, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [e3265d4cdc](https://linux-hardware.org/?probe=e3265d4cdc) | Oct 20, 2022 |
| HP            | 8433 11                     | Desktop     | [7e28f54181](https://linux-hardware.org/?probe=7e28f54181) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7d35a56915](https://linux-hardware.org/?probe=7d35a56915) | Oct 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [f81a40a71c](https://linux-hardware.org/?probe=f81a40a71c) | Oct 20, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [f91d8722f9](https://linux-hardware.org/?probe=f91d8722f9) | Oct 20, 2022 |
| Dell          | Precision 5510              | Notebook    | [bb7788ce01](https://linux-hardware.org/?probe=bb7788ce01) | Oct 20, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [9594fcc1e0](https://linux-hardware.org/?probe=9594fcc1e0) | Oct 20, 2022 |
| ASUSTek       | K43SJ                       | Notebook    | [4c27c4945c](https://linux-hardware.org/?probe=4c27c4945c) | Oct 20, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [502ae94f8f](https://linux-hardware.org/?probe=502ae94f8f) | Oct 20, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [d0dcb7e6e3](https://linux-hardware.org/?probe=d0dcb7e6e3) | Oct 20, 2022 |
| NZXT          | N7 B550                     | Desktop     | [f699b7e1d2](https://linux-hardware.org/?probe=f699b7e1d2) | Oct 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [866d0f49a2](https://linux-hardware.org/?probe=866d0f49a2) | Oct 20, 2022 |
| HP            | 8459                        | Desktop     | [d8ec2e7ee9](https://linux-hardware.org/?probe=d8ec2e7ee9) | Oct 20, 2022 |
| Framework     | Laptop                      | Notebook    | [ade55fca33](https://linux-hardware.org/?probe=ade55fca33) | Oct 19, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [76c0902958](https://linux-hardware.org/?probe=76c0902958) | Oct 19, 2022 |
| Gigabyte      | P67A-UD3                    | Desktop     | [96b72bfa8a](https://linux-hardware.org/?probe=96b72bfa8a) | Oct 19, 2022 |
| Framework     | Laptop                      | Notebook    | [57af01b405](https://linux-hardware.org/?probe=57af01b405) | Oct 19, 2022 |
| Shuttle       | FH67H                       | Desktop     | [6679449225](https://linux-hardware.org/?probe=6679449225) | Oct 19, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [980d0d7bb2](https://linux-hardware.org/?probe=980d0d7bb2) | Oct 19, 2022 |
| Dell          | Precision 7760              | Notebook    | [a5ab2793ae](https://linux-hardware.org/?probe=a5ab2793ae) | Oct 19, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [aeedc0bfd0](https://linux-hardware.org/?probe=aeedc0bfd0) | Oct 19, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [680823db07](https://linux-hardware.org/?probe=680823db07) | Oct 19, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [71734a9abe](https://linux-hardware.org/?probe=71734a9abe) | Oct 19, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [2cd92a7da8](https://linux-hardware.org/?probe=2cd92a7da8) | Oct 19, 2022 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [8665ee6ba6](https://linux-hardware.org/?probe=8665ee6ba6) | Oct 19, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d267c64062](https://linux-hardware.org/?probe=d267c64062) | Oct 19, 2022 |
| Lenovo        | Yoga 900-13ISK2 80UE        | Notebook    | [efadc96c65](https://linux-hardware.org/?probe=efadc96c65) | Oct 19, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [41d2e6298d](https://linux-hardware.org/?probe=41d2e6298d) | Oct 19, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [eab0779b74](https://linux-hardware.org/?probe=eab0779b74) | Oct 19, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [95a75ab35b](https://linux-hardware.org/?probe=95a75ab35b) | Oct 19, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [495c7fdc3d](https://linux-hardware.org/?probe=495c7fdc3d) | Oct 18, 2022 |
| Lenovo        | Legion S7 16ARHA7 82UG      | Notebook    | [28a1d15220](https://linux-hardware.org/?probe=28a1d15220) | Oct 18, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [33c0e4861e](https://linux-hardware.org/?probe=33c0e4861e) | Oct 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [d51ba4a008](https://linux-hardware.org/?probe=d51ba4a008) | Oct 18, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [70d12e710f](https://linux-hardware.org/?probe=70d12e710f) | Oct 18, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [aaa41de825](https://linux-hardware.org/?probe=aaa41de825) | Oct 18, 2022 |
| Lenovo        | B560                        | Notebook    | [717af973da](https://linux-hardware.org/?probe=717af973da) | Oct 18, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [026a7a8cd3](https://linux-hardware.org/?probe=026a7a8cd3) | Oct 18, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [5c2590f03f](https://linux-hardware.org/?probe=5c2590f03f) | Oct 18, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [df0afd4326](https://linux-hardware.org/?probe=df0afd4326) | Oct 18, 2022 |
| ASRock        | Z97E-ITX/ac                 | Desktop     | [2ae712a746](https://linux-hardware.org/?probe=2ae712a746) | Oct 18, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [527c4e0728](https://linux-hardware.org/?probe=527c4e0728) | Oct 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [76f9929a9c](https://linux-hardware.org/?probe=76f9929a9c) | Oct 17, 2022 |
| MSI           | Summit E16Flip A11UCT       | Notebook    | [f1ec40e34d](https://linux-hardware.org/?probe=f1ec40e34d) | Oct 17, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [9e1f6ae49e](https://linux-hardware.org/?probe=9e1f6ae49e) | Oct 17, 2022 |
| Dell          | Latitude 9420               | Convertible | [319c3b9f03](https://linux-hardware.org/?probe=319c3b9f03) | Oct 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7f9219a85f](https://linux-hardware.org/?probe=7f9219a85f) | Oct 17, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [c80df2b63c](https://linux-hardware.org/?probe=c80df2b63c) | Oct 17, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [2fd734cbfb](https://linux-hardware.org/?probe=2fd734cbfb) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [d78ecde0a2](https://linux-hardware.org/?probe=d78ecde0a2) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [adda30ef79](https://linux-hardware.org/?probe=adda30ef79) | Oct 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [528fc3c5ec](https://linux-hardware.org/?probe=528fc3c5ec) | Oct 17, 2022 |
| Dell          | Inspiron 5759               | Notebook    | [f93d1bc535](https://linux-hardware.org/?probe=f93d1bc535) | Oct 17, 2022 |
| Dell          | Inspiron 13 5320            | Notebook    | [9ac52708ad](https://linux-hardware.org/?probe=9ac52708ad) | Oct 17, 2022 |
| Notebook      | W230SS                      | Notebook    | [abb5e7fda8](https://linux-hardware.org/?probe=abb5e7fda8) | Oct 16, 2022 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [50fe9fcad5](https://linux-hardware.org/?probe=50fe9fcad5) | Oct 16, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [f98ff2b890](https://linux-hardware.org/?probe=f98ff2b890) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [f20a72be72](https://linux-hardware.org/?probe=f20a72be72) | Oct 16, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [6a9b93fdeb](https://linux-hardware.org/?probe=6a9b93fdeb) | Oct 16, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [77c8619d03](https://linux-hardware.org/?probe=77c8619d03) | Oct 16, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [c78fae026e](https://linux-hardware.org/?probe=c78fae026e) | Oct 16, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [834248c556](https://linux-hardware.org/?probe=834248c556) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [0cceedcb07](https://linux-hardware.org/?probe=0cceedcb07) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [665763812f](https://linux-hardware.org/?probe=665763812f) | Oct 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [dce51f4ce7](https://linux-hardware.org/?probe=dce51f4ce7) | Oct 16, 2022 |
| Lenovo        | ThinkPad X230 23257BG       | Notebook    | [6c8a42718a](https://linux-hardware.org/?probe=6c8a42718a) | Oct 16, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [156e3942e5](https://linux-hardware.org/?probe=156e3942e5) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [77f04d4628](https://linux-hardware.org/?probe=77f04d4628) | Oct 16, 2022 |
| Notebook      | N2x0WU                      | Notebook    | [bc1072e527](https://linux-hardware.org/?probe=bc1072e527) | Oct 16, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [ee436e327b](https://linux-hardware.org/?probe=ee436e327b) | Oct 16, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [86e01f1479](https://linux-hardware.org/?probe=86e01f1479) | Oct 16, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [d73a82b798](https://linux-hardware.org/?probe=d73a82b798) | Oct 15, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [5d60b980ca](https://linux-hardware.org/?probe=5d60b980ca) | Oct 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [1993500f68](https://linux-hardware.org/?probe=1993500f68) | Oct 15, 2022 |
| Dell          | Latitude E5450              | Notebook    | [68e2c17e2f](https://linux-hardware.org/?probe=68e2c17e2f) | Oct 15, 2022 |
| Acer          | Aspire A314-22              | Notebook    | [eff5a7242e](https://linux-hardware.org/?probe=eff5a7242e) | Oct 15, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [8557c8b501](https://linux-hardware.org/?probe=8557c8b501) | Oct 15, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [7979753fa9](https://linux-hardware.org/?probe=7979753fa9) | Oct 15, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [bf6d77aefd](https://linux-hardware.org/?probe=bf6d77aefd) | Oct 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ab212a80b4](https://linux-hardware.org/?probe=ab212a80b4) | Oct 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [e1bc46388d](https://linux-hardware.org/?probe=e1bc46388d) | Oct 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [49821787e4](https://linux-hardware.org/?probe=49821787e4) | Oct 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6de814388c](https://linux-hardware.org/?probe=6de814388c) | Oct 14, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [1200f4104f](https://linux-hardware.org/?probe=1200f4104f) | Oct 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [79eba98b95](https://linux-hardware.org/?probe=79eba98b95) | Oct 14, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [f9c2c298c4](https://linux-hardware.org/?probe=f9c2c298c4) | Oct 14, 2022 |
| Acer          | Spin SP315-51               | Convertible | [28103297c2](https://linux-hardware.org/?probe=28103297c2) | Oct 14, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2fb7882f4a](https://linux-hardware.org/?probe=2fb7882f4a) | Oct 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f4d190e864](https://linux-hardware.org/?probe=f4d190e864) | Oct 13, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [60b21aed9a](https://linux-hardware.org/?probe=60b21aed9a) | Oct 13, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [5985f3564a](https://linux-hardware.org/?probe=5985f3564a) | Oct 13, 2022 |
| Lenovo        | ThinkPad X270 20HMS2R900    | Notebook    | [38739fd54f](https://linux-hardware.org/?probe=38739fd54f) | Oct 13, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [a6083f4dfe](https://linux-hardware.org/?probe=a6083f4dfe) | Oct 13, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [47394cb2b5](https://linux-hardware.org/?probe=47394cb2b5) | Oct 13, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [0c7961c445](https://linux-hardware.org/?probe=0c7961c445) | Oct 13, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [7af879de72](https://linux-hardware.org/?probe=7af879de72) | Oct 13, 2022 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [2be4dc3fc2](https://linux-hardware.org/?probe=2be4dc3fc2) | Oct 13, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [4a4b8d42fc](https://linux-hardware.org/?probe=4a4b8d42fc) | Oct 13, 2022 |
| Gigabyte      | P65Q                        | Notebook    | [8e83936c53](https://linux-hardware.org/?probe=8e83936c53) | Oct 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d0d2949fd3](https://linux-hardware.org/?probe=d0d2949fd3) | Oct 12, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [8437ac2ffc](https://linux-hardware.org/?probe=8437ac2ffc) | Oct 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [f20c990c1f](https://linux-hardware.org/?probe=f20c990c1f) | Oct 12, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [ce1dbed861](https://linux-hardware.org/?probe=ce1dbed861) | Oct 12, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [f58608a000](https://linux-hardware.org/?probe=f58608a000) | Oct 11, 2022 |
| HP            | 82A5                        | Mini pc     | [5a8ea35493](https://linux-hardware.org/?probe=5a8ea35493) | Oct 11, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [56fc798c2e](https://linux-hardware.org/?probe=56fc798c2e) | Oct 11, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [0355b3f7b8](https://linux-hardware.org/?probe=0355b3f7b8) | Oct 11, 2022 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [60b02deb7f](https://linux-hardware.org/?probe=60b02deb7f) | Oct 11, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [dde4a94108](https://linux-hardware.org/?probe=dde4a94108) | Oct 11, 2022 |
| Gigabyte      | H410M DS2V                  | Desktop     | [bd9d9e10c7](https://linux-hardware.org/?probe=bd9d9e10c7) | Oct 11, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [11f3146366](https://linux-hardware.org/?probe=11f3146366) | Oct 11, 2022 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | Notebook    | [71c926fc14](https://linux-hardware.org/?probe=71c926fc14) | Oct 11, 2022 |
| Lenovo        | ThinkPad P50 20EQS5MP00     | Notebook    | [83858a99c3](https://linux-hardware.org/?probe=83858a99c3) | Oct 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [5caff1861e](https://linux-hardware.org/?probe=5caff1861e) | Oct 10, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [cae3279751](https://linux-hardware.org/?probe=cae3279751) | Oct 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e2d9db1022](https://linux-hardware.org/?probe=e2d9db1022) | Oct 10, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [dc3347c309](https://linux-hardware.org/?probe=dc3347c309) | Oct 10, 2022 |
| Lenovo        | ThinkPad L450 20DTCTO1WW    | Notebook    | [2209173803](https://linux-hardware.org/?probe=2209173803) | Oct 10, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [49fff6123f](https://linux-hardware.org/?probe=49fff6123f) | Oct 10, 2022 |
| ASRock        | X570 PG Velocita            | Desktop     | [ec3a819326](https://linux-hardware.org/?probe=ec3a819326) | Oct 10, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [59f6b7653c](https://linux-hardware.org/?probe=59f6b7653c) | Oct 10, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [7b6f3fcf28](https://linux-hardware.org/?probe=7b6f3fcf28) | Oct 10, 2022 |
| Intel         | DG41TY AAE47335-302         | Desktop     | [c0d07ec775](https://linux-hardware.org/?probe=c0d07ec775) | Oct 10, 2022 |
| MSI           | B450 GAMING PLUS            | Desktop     | [6f95e1591a](https://linux-hardware.org/?probe=6f95e1591a) | Oct 10, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [cab829a52b](https://linux-hardware.org/?probe=cab829a52b) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [6c2f880759](https://linux-hardware.org/?probe=6c2f880759) | Oct 09, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [5d882bd47f](https://linux-hardware.org/?probe=5d882bd47f) | Oct 09, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [edb6e4180f](https://linux-hardware.org/?probe=edb6e4180f) | Oct 09, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [6a56a66eae](https://linux-hardware.org/?probe=6a56a66eae) | Oct 09, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [4aa8b37ac5](https://linux-hardware.org/?probe=4aa8b37ac5) | Oct 09, 2022 |
| Framework     | Laptop                      | Notebook    | [3d25e7f96c](https://linux-hardware.org/?probe=3d25e7f96c) | Oct 09, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [01abf75c2e](https://linux-hardware.org/?probe=01abf75c2e) | Oct 09, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [6b62586012](https://linux-hardware.org/?probe=6b62586012) | Oct 09, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [30ff2d0e8f](https://linux-hardware.org/?probe=30ff2d0e8f) | Oct 09, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [19ad61d9c7](https://linux-hardware.org/?probe=19ad61d9c7) | Oct 09, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [cc8b98a2ff](https://linux-hardware.org/?probe=cc8b98a2ff) | Oct 09, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [d7379a41e9](https://linux-hardware.org/?probe=d7379a41e9) | Oct 08, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [0f4a711f6a](https://linux-hardware.org/?probe=0f4a711f6a) | Oct 08, 2022 |
| Lenovo        | ThinkPad L470 20J4CTO1WW    | Notebook    | [3aee91df8c](https://linux-hardware.org/?probe=3aee91df8c) | Oct 08, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [126b7b85f2](https://linux-hardware.org/?probe=126b7b85f2) | Oct 08, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3d968cc61a](https://linux-hardware.org/?probe=3d968cc61a) | Oct 08, 2022 |
| Lenovo        | Legion S7 16IAH7 82TF       | Notebook    | [9836cb655c](https://linux-hardware.org/?probe=9836cb655c) | Oct 08, 2022 |
| HP            | 3647h                       | Desktop     | [ddffa21a6e](https://linux-hardware.org/?probe=ddffa21a6e) | Oct 07, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [973605d3af](https://linux-hardware.org/?probe=973605d3af) | Oct 07, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [74f6e9db69](https://linux-hardware.org/?probe=74f6e9db69) | Oct 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8895a815c6](https://linux-hardware.org/?probe=8895a815c6) | Oct 07, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [812ed8c396](https://linux-hardware.org/?probe=812ed8c396) | Oct 07, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [fdab72c478](https://linux-hardware.org/?probe=fdab72c478) | Oct 07, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [26dfdb5aed](https://linux-hardware.org/?probe=26dfdb5aed) | Oct 07, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [d67006c592](https://linux-hardware.org/?probe=d67006c592) | Oct 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [08e98e28c2](https://linux-hardware.org/?probe=08e98e28c2) | Oct 07, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [b1ff49ff0f](https://linux-hardware.org/?probe=b1ff49ff0f) | Oct 07, 2022 |
| Dell          | Latitude 5580               | Notebook    | [4bcae73c95](https://linux-hardware.org/?probe=4bcae73c95) | Oct 07, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [6a9f611fd5](https://linux-hardware.org/?probe=6a9f611fd5) | Oct 07, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [d5247cbbc3](https://linux-hardware.org/?probe=d5247cbbc3) | Oct 06, 2022 |
| Unknown       | Intel X79                   | Desktop     | [9c0ffde822](https://linux-hardware.org/?probe=9c0ffde822) | Oct 06, 2022 |
| Dell          | Latitude 5400               | Notebook    | [00789b23c6](https://linux-hardware.org/?probe=00789b23c6) | Oct 06, 2022 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [8b0ed3f04c](https://linux-hardware.org/?probe=8b0ed3f04c) | Oct 06, 2022 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [17d5aa4f87](https://linux-hardware.org/?probe=17d5aa4f87) | Oct 06, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [c8c6a428db](https://linux-hardware.org/?probe=c8c6a428db) | Oct 06, 2022 |
| ASUSTek       | X550LA                      | Notebook    | [c0c98c2051](https://linux-hardware.org/?probe=c0c98c2051) | Oct 06, 2022 |
| HP            | 0AECh D                     | Desktop     | [8fd13e9017](https://linux-hardware.org/?probe=8fd13e9017) | Oct 06, 2022 |
| MSI           | X370 SLI PLUS               | Desktop     | [ea7dc6a41a](https://linux-hardware.org/?probe=ea7dc6a41a) | Oct 06, 2022 |
| HP            | 15                          | Notebook    | [9f0981ed52](https://linux-hardware.org/?probe=9f0981ed52) | Oct 06, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [3ea8d4d25e](https://linux-hardware.org/?probe=3ea8d4d25e) | Oct 06, 2022 |
| LG Electro... | 14Z990-V.AR52A2             | Notebook    | [4fe1810c2c](https://linux-hardware.org/?probe=4fe1810c2c) | Oct 06, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [20b6b5f918](https://linux-hardware.org/?probe=20b6b5f918) | Oct 06, 2022 |
| HP            | Spectre x360 Convertible    | Convertible | [b0fa4fab35](https://linux-hardware.org/?probe=b0fa4fab35) | Oct 05, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [7f2b63950d](https://linux-hardware.org/?probe=7f2b63950d) | Oct 05, 2022 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [368530a660](https://linux-hardware.org/?probe=368530a660) | Oct 05, 2022 |
| Dell          | Latitude 5400               | Notebook    | [14ed107028](https://linux-hardware.org/?probe=14ed107028) | Oct 05, 2022 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [a60e3c519e](https://linux-hardware.org/?probe=a60e3c519e) | Oct 05, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [77176ee82a](https://linux-hardware.org/?probe=77176ee82a) | Oct 05, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [7590ca8bff](https://linux-hardware.org/?probe=7590ca8bff) | Oct 05, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [99f16967b2](https://linux-hardware.org/?probe=99f16967b2) | Oct 05, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [ca81117136](https://linux-hardware.org/?probe=ca81117136) | Oct 05, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [3d5136540e](https://linux-hardware.org/?probe=3d5136540e) | Oct 05, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [b78c69e096](https://linux-hardware.org/?probe=b78c69e096) | Oct 04, 2022 |
| Lenovo        | ThinkPad E480 20KNS0E200    | Notebook    | [cb204abf9b](https://linux-hardware.org/?probe=cb204abf9b) | Oct 04, 2022 |
| Dell          | Inspiron 13 5310            | Notebook    | [128725bb4d](https://linux-hardware.org/?probe=128725bb4d) | Oct 04, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [dc80de33ee](https://linux-hardware.org/?probe=dc80de33ee) | Oct 04, 2022 |
| HP            | Laptop                      | Notebook    | [3a26ec874f](https://linux-hardware.org/?probe=3a26ec874f) | Oct 04, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [07d4cf95ec](https://linux-hardware.org/?probe=07d4cf95ec) | Oct 04, 2022 |
| Acer          | TravelMate Spin P614RN-5... | Convertible | [3a515cdda0](https://linux-hardware.org/?probe=3a515cdda0) | Oct 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [923a579655](https://linux-hardware.org/?probe=923a579655) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | Notebook    | [a9c2a1eca0](https://linux-hardware.org/?probe=a9c2a1eca0) | Oct 03, 2022 |
| Gigabyte      | B85M-D2V                    | Desktop     | [4e6047ec5b](https://linux-hardware.org/?probe=4e6047ec5b) | Oct 03, 2022 |
| Intel         | NUC10i3FNB K61362-306       | Mini pc     | [e8130be6f2](https://linux-hardware.org/?probe=e8130be6f2) | Oct 03, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [2f9e023d1e](https://linux-hardware.org/?probe=2f9e023d1e) | Oct 03, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [45a46cdb72](https://linux-hardware.org/?probe=45a46cdb72) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [48e867fba8](https://linux-hardware.org/?probe=48e867fba8) | Oct 02, 2022 |
| Acer          | Veriton X6620G v1.0         | Desktop     | [80e98d9053](https://linux-hardware.org/?probe=80e98d9053) | Oct 02, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [92aca0d081](https://linux-hardware.org/?probe=92aca0d081) | Oct 02, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [253e143d94](https://linux-hardware.org/?probe=253e143d94) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [8f24127ac0](https://linux-hardware.org/?probe=8f24127ac0) | Oct 02, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [bce5ab0354](https://linux-hardware.org/?probe=bce5ab0354) | Oct 02, 2022 |
| Zinox Tech... | x64-Based PC                | Tablet      | [de64a1e585](https://linux-hardware.org/?probe=de64a1e585) | Oct 02, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6121fee541](https://linux-hardware.org/?probe=6121fee541) | Oct 02, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [9e5ab25f54](https://linux-hardware.org/?probe=9e5ab25f54) | Oct 02, 2022 |
| Dell          | Inspiron 17-7779            | Notebook    | [5bd534e938](https://linux-hardware.org/?probe=5bd534e938) | Oct 02, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [6d8ed9f182](https://linux-hardware.org/?probe=6d8ed9f182) | Oct 02, 2022 |
| ASRock        | X570 Phantom Gaming 4S      | Desktop     | [2215129a47](https://linux-hardware.org/?probe=2215129a47) | Oct 02, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [b902f5d873](https://linux-hardware.org/?probe=b902f5d873) | Oct 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [ee22a244e2](https://linux-hardware.org/?probe=ee22a244e2) | Oct 01, 2022 |
| MICROMAX      | Canvas Lapbook L1161        | Notebook    | [9efe9e89d6](https://linux-hardware.org/?probe=9efe9e89d6) | Oct 01, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4a8d27ad0f](https://linux-hardware.org/?probe=4a8d27ad0f) | Oct 01, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [1fade0f247](https://linux-hardware.org/?probe=1fade0f247) | Oct 01, 2022 |
| Dell          | Vostro 5568                 | Notebook    | [44bf0dbbce](https://linux-hardware.org/?probe=44bf0dbbce) | Oct 01, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [4275ef3653](https://linux-hardware.org/?probe=4275ef3653) | Oct 01, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [d60b15ea91](https://linux-hardware.org/?probe=d60b15ea91) | Oct 01, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [4662cb1d99](https://linux-hardware.org/?probe=4662cb1d99) | Oct 01, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9f64b9ed3d](https://linux-hardware.org/?probe=9f64b9ed3d) | Oct 01, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0DK0... | Notebook    | [49bd2b0248](https://linux-hardware.org/?probe=49bd2b0248) | Oct 01, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [af9b794734](https://linux-hardware.org/?probe=af9b794734) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [d5407763a0](https://linux-hardware.org/?probe=d5407763a0) | Sep 30, 2022 |
| Dell          | Latitude E4300              | Notebook    | [a860d9a446](https://linux-hardware.org/?probe=a860d9a446) | Sep 30, 2022 |
| GPD           | G1621-02                    | Notebook    | [6ae9fc596e](https://linux-hardware.org/?probe=6ae9fc596e) | Sep 30, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [162334ac1e](https://linux-hardware.org/?probe=162334ac1e) | Sep 30, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [0d466bc2f7](https://linux-hardware.org/?probe=0d466bc2f7) | Sep 30, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [02c5cd53e9](https://linux-hardware.org/?probe=02c5cd53e9) | Sep 30, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c06e7e3586](https://linux-hardware.org/?probe=c06e7e3586) | Sep 30, 2022 |
| HP            | ProBook 6570b               | Notebook    | [d9be946342](https://linux-hardware.org/?probe=d9be946342) | Sep 30, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d658b9dcbe](https://linux-hardware.org/?probe=d658b9dcbe) | Sep 30, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [ed76eeb703](https://linux-hardware.org/?probe=ed76eeb703) | Sep 30, 2022 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [b15bae8e77](https://linux-hardware.org/?probe=b15bae8e77) | Sep 30, 2022 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [126b8dd3ec](https://linux-hardware.org/?probe=126b8dd3ec) | Sep 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0DK0... | Notebook    | [33353fc67c](https://linux-hardware.org/?probe=33353fc67c) | Sep 30, 2022 |
| SK hynix      | HyBook                      | Notebook    | [38b5f704a1](https://linux-hardware.org/?probe=38b5f704a1) | Sep 30, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [d2a3575975](https://linux-hardware.org/?probe=d2a3575975) | Sep 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [9015ce1da8](https://linux-hardware.org/?probe=9015ce1da8) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [2c6b161d0f](https://linux-hardware.org/?probe=2c6b161d0f) | Sep 29, 2022 |
| Avell High... | A60 MUV                     | Notebook    | [888e375356](https://linux-hardware.org/?probe=888e375356) | Sep 29, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [18afdc2116](https://linux-hardware.org/?probe=18afdc2116) | Sep 29, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [99f729e814](https://linux-hardware.org/?probe=99f729e814) | Sep 29, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [cc7ad91815](https://linux-hardware.org/?probe=cc7ad91815) | Sep 29, 2022 |
| Fujitsu       | LIFEBOOK P771               | Notebook    | [7325511d27](https://linux-hardware.org/?probe=7325511d27) | Sep 29, 2022 |
| ASUSTek       | X555LA                      | Notebook    | [5ec700ea0a](https://linux-hardware.org/?probe=5ec700ea0a) | Sep 29, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [c6ae2f8a45](https://linux-hardware.org/?probe=c6ae2f8a45) | Sep 29, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [354a9c2bc2](https://linux-hardware.org/?probe=354a9c2bc2) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [067b155d9b](https://linux-hardware.org/?probe=067b155d9b) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [058aa145d3](https://linux-hardware.org/?probe=058aa145d3) | Sep 29, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [a674def12d](https://linux-hardware.org/?probe=a674def12d) | Sep 29, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [23c809d2a7](https://linux-hardware.org/?probe=23c809d2a7) | Sep 29, 2022 |
| Dell          | Precision 7550              | Notebook    | [75f2949521](https://linux-hardware.org/?probe=75f2949521) | Sep 29, 2022 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | Notebook    | [9ac63cdce6](https://linux-hardware.org/?probe=9ac63cdce6) | Sep 29, 2022 |
| Biostar       | H410MH S2                   | Desktop     | [fbba79fc43](https://linux-hardware.org/?probe=fbba79fc43) | Sep 28, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [d137298cb5](https://linux-hardware.org/?probe=d137298cb5) | Sep 28, 2022 |
| Dell          | Inspiron 5447               | Notebook    | [b30346135b](https://linux-hardware.org/?probe=b30346135b) | Sep 28, 2022 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [513d236a1f](https://linux-hardware.org/?probe=513d236a1f) | Sep 28, 2022 |
| Lenovo        | IdeaPad 3 15ARE 81W4        | Notebook    | [b784552e84](https://linux-hardware.org/?probe=b784552e84) | Sep 28, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [89253de6f0](https://linux-hardware.org/?probe=89253de6f0) | Sep 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [84187f87ed](https://linux-hardware.org/?probe=84187f87ed) | Sep 28, 2022 |
| Medion        | Unknown                     | Notebook    | [821c3c8fed](https://linux-hardware.org/?probe=821c3c8fed) | Sep 28, 2022 |
| Alienware     | 14                          | Notebook    | [2d46ecc50e](https://linux-hardware.org/?probe=2d46ecc50e) | Sep 28, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [a4b44081c2](https://linux-hardware.org/?probe=a4b44081c2) | Sep 27, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [a6347449b3](https://linux-hardware.org/?probe=a6347449b3) | Sep 27, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [c31e327867](https://linux-hardware.org/?probe=c31e327867) | Sep 27, 2022 |
| MSI           | GS66 Stealth 10SGS          | Notebook    | [644efb07cf](https://linux-hardware.org/?probe=644efb07cf) | Sep 27, 2022 |
| HONOR         | HGE-WX6                     | Notebook    | [5c61df4d20](https://linux-hardware.org/?probe=5c61df4d20) | Sep 27, 2022 |
| Dell          | 0YGYJY A01                  | Desktop     | [73e69debd9](https://linux-hardware.org/?probe=73e69debd9) | Sep 27, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6677830ce4](https://linux-hardware.org/?probe=6677830ce4) | Sep 27, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [3d86bcf1b7](https://linux-hardware.org/?probe=3d86bcf1b7) | Sep 27, 2022 |
| HP            | 829A                        | Mini pc     | [1e26c7813f](https://linux-hardware.org/?probe=1e26c7813f) | Sep 27, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [c60d7e3375](https://linux-hardware.org/?probe=c60d7e3375) | Sep 27, 2022 |
| Gigabyte      | Z690I AORUS ULTRA DDR4      | Desktop     | [7af967061b](https://linux-hardware.org/?probe=7af967061b) | Sep 27, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [4308420b28](https://linux-hardware.org/?probe=4308420b28) | Sep 27, 2022 |
| MSI           | GT72 6QE                    | Notebook    | [5535b3367e](https://linux-hardware.org/?probe=5535b3367e) | Sep 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [6373bf42ef](https://linux-hardware.org/?probe=6373bf42ef) | Sep 26, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [ed657bfbb6](https://linux-hardware.org/?probe=ed657bfbb6) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | Notebook    | [2154b531c9](https://linux-hardware.org/?probe=2154b531c9) | Sep 26, 2022 |
| Dell          | XPS 17 9700                 | Notebook    | [76166adede](https://linux-hardware.org/?probe=76166adede) | Sep 26, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [f1d78ca455](https://linux-hardware.org/?probe=f1d78ca455) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | Notebook    | [6b3be4af70](https://linux-hardware.org/?probe=6b3be4af70) | Sep 26, 2022 |
| HP            | Tablet 11m-be0xxx           | Tablet      | [d644aedbdd](https://linux-hardware.org/?probe=d644aedbdd) | Sep 26, 2022 |
| MSI           | GT72 6QE                    | Notebook    | [d739812ce7](https://linux-hardware.org/?probe=d739812ce7) | Sep 26, 2022 |
| MSI           | GT72S 6QE                   | Notebook    | [7ec3a25453](https://linux-hardware.org/?probe=7ec3a25453) | Sep 26, 2022 |
| HP            | Laptop                      | Notebook    | [6d8fc869e4](https://linux-hardware.org/?probe=6d8fc869e4) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [52a86d0701](https://linux-hardware.org/?probe=52a86d0701) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [683aa83ea4](https://linux-hardware.org/?probe=683aa83ea4) | Sep 26, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [64fd780b2f](https://linux-hardware.org/?probe=64fd780b2f) | Sep 26, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [d557cdbe1c](https://linux-hardware.org/?probe=d557cdbe1c) | Sep 26, 2022 |
| HP            | Laptop                      | Notebook    | [be59fc7a97](https://linux-hardware.org/?probe=be59fc7a97) | Sep 26, 2022 |
| HP            | EliteBook Folio 9480m       | Notebook    | [e2232c49ca](https://linux-hardware.org/?probe=e2232c49ca) | Sep 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [f8b76ec5f4](https://linux-hardware.org/?probe=f8b76ec5f4) | Sep 25, 2022 |
| AZW           | SEi                         | Notebook    | [063c3cc52e](https://linux-hardware.org/?probe=063c3cc52e) | Sep 25, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [778f7340fa](https://linux-hardware.org/?probe=778f7340fa) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [67040d9a5e](https://linux-hardware.org/?probe=67040d9a5e) | Sep 25, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [850b486cff](https://linux-hardware.org/?probe=850b486cff) | Sep 25, 2022 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [e9205da026](https://linux-hardware.org/?probe=e9205da026) | Sep 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [be1d17baa4](https://linux-hardware.org/?probe=be1d17baa4) | Sep 25, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [982d41c1eb](https://linux-hardware.org/?probe=982d41c1eb) | Sep 25, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [0f6ea5edfa](https://linux-hardware.org/?probe=0f6ea5edfa) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [82b73270ca](https://linux-hardware.org/?probe=82b73270ca) | Sep 25, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [b26f7bf9f5](https://linux-hardware.org/?probe=b26f7bf9f5) | Sep 25, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [a5d5950e29](https://linux-hardware.org/?probe=a5d5950e29) | Sep 25, 2022 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [cedbd8909f](https://linux-hardware.org/?probe=cedbd8909f) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [a1f261d09d](https://linux-hardware.org/?probe=a1f261d09d) | Sep 25, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [66b5b65077](https://linux-hardware.org/?probe=66b5b65077) | Sep 25, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [a35dda8c10](https://linux-hardware.org/?probe=a35dda8c10) | Sep 25, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [f5e9524bff](https://linux-hardware.org/?probe=f5e9524bff) | Sep 25, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [6e7d310781](https://linux-hardware.org/?probe=6e7d310781) | Sep 25, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B7402FEA... | Convertible | [593ef93760](https://linux-hardware.org/?probe=593ef93760) | Sep 25, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [be92ff8ffc](https://linux-hardware.org/?probe=be92ff8ffc) | Sep 25, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [4f9ff1b402](https://linux-hardware.org/?probe=4f9ff1b402) | Sep 24, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [307a3c2848](https://linux-hardware.org/?probe=307a3c2848) | Sep 24, 2022 |
| ASRock        | Z170M Extreme4              | Desktop     | [bd1e98639b](https://linux-hardware.org/?probe=bd1e98639b) | Sep 24, 2022 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [2bdc1228a1](https://linux-hardware.org/?probe=2bdc1228a1) | Sep 24, 2022 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [eef9de3daf](https://linux-hardware.org/?probe=eef9de3daf) | Sep 24, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ae43d0bbce](https://linux-hardware.org/?probe=ae43d0bbce) | Sep 24, 2022 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [542249f675](https://linux-hardware.org/?probe=542249f675) | Sep 24, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0170bcbb42](https://linux-hardware.org/?probe=0170bcbb42) | Sep 24, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [08843e7c7c](https://linux-hardware.org/?probe=08843e7c7c) | Sep 24, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [2082a8668b](https://linux-hardware.org/?probe=2082a8668b) | Sep 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [89a1a3179d](https://linux-hardware.org/?probe=89a1a3179d) | Sep 24, 2022 |
| Lenovo        | ThinkPad X270 20HMS1QT0E    | Notebook    | [72caf18b5f](https://linux-hardware.org/?probe=72caf18b5f) | Sep 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [2bb811e308](https://linux-hardware.org/?probe=2bb811e308) | Sep 23, 2022 |
| AZW           | GTR V01                     | Mini pc     | [927faa3232](https://linux-hardware.org/?probe=927faa3232) | Sep 23, 2022 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [c4c88d72ae](https://linux-hardware.org/?probe=c4c88d72ae) | Sep 23, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [c30d8893ca](https://linux-hardware.org/?probe=c30d8893ca) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [31f1acf273](https://linux-hardware.org/?probe=31f1acf273) | Sep 23, 2022 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [2e45736b42](https://linux-hardware.org/?probe=2e45736b42) | Sep 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a4ce7c179e](https://linux-hardware.org/?probe=a4ce7c179e) | Sep 23, 2022 |
| Gigabyte      | B660I AORUS PRO DDR4        | Desktop     | [810c7883d4](https://linux-hardware.org/?probe=810c7883d4) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [7d69f0c6c6](https://linux-hardware.org/?probe=7d69f0c6c6) | Sep 23, 2022 |
| HONOR         | HGE-WX6                     | Notebook    | [337c1097ef](https://linux-hardware.org/?probe=337c1097ef) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [f72f370511](https://linux-hardware.org/?probe=f72f370511) | Sep 23, 2022 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [79509e063b](https://linux-hardware.org/?probe=79509e063b) | Sep 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [a5e851730c](https://linux-hardware.org/?probe=a5e851730c) | Sep 23, 2022 |
| Acer          | Aspire A715-43G             | Notebook    | [5ecaaef0b1](https://linux-hardware.org/?probe=5ecaaef0b1) | Sep 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [accc831d30](https://linux-hardware.org/?probe=accc831d30) | Sep 23, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [c916654073](https://linux-hardware.org/?probe=c916654073) | Sep 22, 2022 |
| VALE          | Notebook Classic C140       | Notebook    | [5a8e431c98](https://linux-hardware.org/?probe=5a8e431c98) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [4d47a6bfcf](https://linux-hardware.org/?probe=4d47a6bfcf) | Sep 22, 2022 |
| Foxconn       | H61M-S/H61M                 | Desktop     | [039b5cff54](https://linux-hardware.org/?probe=039b5cff54) | Sep 22, 2022 |
| Dell          | Precision 5540              | Notebook    | [0f09e447ea](https://linux-hardware.org/?probe=0f09e447ea) | Sep 22, 2022 |
| Dell          | Vostro 3558                 | Notebook    | [61f6c99c88](https://linux-hardware.org/?probe=61f6c99c88) | Sep 22, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [efaa235d34](https://linux-hardware.org/?probe=efaa235d34) | Sep 22, 2022 |
| MSI           | H310M PRO-VH                | Desktop     | [c11e067cb5](https://linux-hardware.org/?probe=c11e067cb5) | Sep 22, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [2250b3380d](https://linux-hardware.org/?probe=2250b3380d) | Sep 22, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [11ea16f0d6](https://linux-hardware.org/?probe=11ea16f0d6) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [ba5fdd39e6](https://linux-hardware.org/?probe=ba5fdd39e6) | Sep 21, 2022 |
| Framework     | Laptop                      | Notebook    | [8e2d92c817](https://linux-hardware.org/?probe=8e2d92c817) | Sep 21, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [9515dd24c0](https://linux-hardware.org/?probe=9515dd24c0) | Sep 21, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [3f33a64102](https://linux-hardware.org/?probe=3f33a64102) | Sep 21, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [0d8e7f2e92](https://linux-hardware.org/?probe=0d8e7f2e92) | Sep 21, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [62a9723eb7](https://linux-hardware.org/?probe=62a9723eb7) | Sep 21, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [2e5553125e](https://linux-hardware.org/?probe=2e5553125e) | Sep 21, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [85cab20988](https://linux-hardware.org/?probe=85cab20988) | Sep 21, 2022 |
| Razer         | Blade                       | Notebook    | [c835fe2f90](https://linux-hardware.org/?probe=c835fe2f90) | Sep 21, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [59219d6ded](https://linux-hardware.org/?probe=59219d6ded) | Sep 21, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [20d37d51bd](https://linux-hardware.org/?probe=20d37d51bd) | Sep 21, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [cabebaa0e6](https://linux-hardware.org/?probe=cabebaa0e6) | Sep 21, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [deb8b0ca78](https://linux-hardware.org/?probe=deb8b0ca78) | Sep 21, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [d5b4924a7b](https://linux-hardware.org/?probe=d5b4924a7b) | Sep 20, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [015c8dd353](https://linux-hardware.org/?probe=015c8dd353) | Sep 20, 2022 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [360e860fb1](https://linux-hardware.org/?probe=360e860fb1) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [41cb2444c5](https://linux-hardware.org/?probe=41cb2444c5) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [a93242008f](https://linux-hardware.org/?probe=a93242008f) | Sep 20, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [a491827753](https://linux-hardware.org/?probe=a491827753) | Sep 20, 2022 |
| Dell          | Latitude 9420               | Convertible | [e8c592b354](https://linux-hardware.org/?probe=e8c592b354) | Sep 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [7561f24877](https://linux-hardware.org/?probe=7561f24877) | Sep 20, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [32120dfcd4](https://linux-hardware.org/?probe=32120dfcd4) | Sep 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b72e23e590](https://linux-hardware.org/?probe=b72e23e590) | Sep 20, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [98771092de](https://linux-hardware.org/?probe=98771092de) | Sep 20, 2022 |
| TUXEDO        | InfinityBook Pro 14 v4      | Notebook    | [20c7b9dcf9](https://linux-hardware.org/?probe=20c7b9dcf9) | Sep 20, 2022 |
| Notebook      | NH55RGQ                     | Notebook    | [f4aade3998](https://linux-hardware.org/?probe=f4aade3998) | Sep 20, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [21617c5cff](https://linux-hardware.org/?probe=21617c5cff) | Sep 20, 2022 |
| ASUSTek       | Z97-AR                      | Desktop     | [5cf4494f07](https://linux-hardware.org/?probe=5cf4494f07) | Sep 20, 2022 |
| Lenovo        | ThinkPad T410 2518Q6G       | Notebook    | [b0568eadf2](https://linux-hardware.org/?probe=b0568eadf2) | Sep 20, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [5b55138f5d](https://linux-hardware.org/?probe=5b55138f5d) | Sep 20, 2022 |
| Notebook      | NH55RGQ                     | Notebook    | [95c8201663](https://linux-hardware.org/?probe=95c8201663) | Sep 20, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [80d61eb345](https://linux-hardware.org/?probe=80d61eb345) | Sep 20, 2022 |
| Lenovo        | ThinkPad T420 4180PBG       | Notebook    | [857b2acef0](https://linux-hardware.org/?probe=857b2acef0) | Sep 20, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [acf36b1555](https://linux-hardware.org/?probe=acf36b1555) | Sep 20, 2022 |
| HP            | ENVY 15                     | Notebook    | [6921f93893](https://linux-hardware.org/?probe=6921f93893) | Sep 20, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [75854836f7](https://linux-hardware.org/?probe=75854836f7) | Sep 20, 2022 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [4ae5282199](https://linux-hardware.org/?probe=4ae5282199) | Sep 20, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [3f82789198](https://linux-hardware.org/?probe=3f82789198) | Sep 20, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [b6ce2720e2](https://linux-hardware.org/?probe=b6ce2720e2) | Sep 20, 2022 |
| ASRock        | H610M-HDV/M.2               | Desktop     | [02a5a10d7a](https://linux-hardware.org/?probe=02a5a10d7a) | Sep 20, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [3c51417d8f](https://linux-hardware.org/?probe=3c51417d8f) | Sep 19, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [d44ac0cc2a](https://linux-hardware.org/?probe=d44ac0cc2a) | Sep 19, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [8027be6f7e](https://linux-hardware.org/?probe=8027be6f7e) | Sep 19, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a681a7cab8](https://linux-hardware.org/?probe=a681a7cab8) | Sep 19, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [e728637650](https://linux-hardware.org/?probe=e728637650) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [f8bf8fd596](https://linux-hardware.org/?probe=f8bf8fd596) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [de718ac983](https://linux-hardware.org/?probe=de718ac983) | Sep 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [7a1dbe2204](https://linux-hardware.org/?probe=7a1dbe2204) | Sep 19, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [bed329dab4](https://linux-hardware.org/?probe=bed329dab4) | Sep 19, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [8072b6c0e0](https://linux-hardware.org/?probe=8072b6c0e0) | Sep 19, 2022 |
| ASUSTek       | P8Q77-M2                    | Desktop     | [1e067b7c4f](https://linux-hardware.org/?probe=1e067b7c4f) | Sep 19, 2022 |
| Lenovo        | ThinkPad T540p 20BFS0RK0... | Notebook    | [eaaf80509b](https://linux-hardware.org/?probe=eaaf80509b) | Sep 19, 2022 |
| Toshiba       | Satellite L40t-A            | Notebook    | [b09254248d](https://linux-hardware.org/?probe=b09254248d) | Sep 19, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [7c52790345](https://linux-hardware.org/?probe=7c52790345) | Sep 19, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [9b14ec4438](https://linux-hardware.org/?probe=9b14ec4438) | Sep 19, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [6fd34fa73b](https://linux-hardware.org/?probe=6fd34fa73b) | Sep 19, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [bf7318e65e](https://linux-hardware.org/?probe=bf7318e65e) | Sep 19, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [ede9aab3fb](https://linux-hardware.org/?probe=ede9aab3fb) | Sep 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [db46d34737](https://linux-hardware.org/?probe=db46d34737) | Sep 19, 2022 |
| ASUSTek       | ROG Flow X16 GV601RE_GV6... | Convertible | [ad99d47a5e](https://linux-hardware.org/?probe=ad99d47a5e) | Sep 19, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [37f0f7b888](https://linux-hardware.org/?probe=37f0f7b888) | Sep 19, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [75be2db65c](https://linux-hardware.org/?probe=75be2db65c) | Sep 19, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [9776f2c20c](https://linux-hardware.org/?probe=9776f2c20c) | Sep 19, 2022 |
| Dell          | 02M8NY A01                  | Desktop     | [498286eb91](https://linux-hardware.org/?probe=498286eb91) | Sep 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [474f619a29](https://linux-hardware.org/?probe=474f619a29) | Sep 19, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ac5b5a53a2](https://linux-hardware.org/?probe=ac5b5a53a2) | Sep 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [3da12828c0](https://linux-hardware.org/?probe=3da12828c0) | Sep 19, 2022 |
| Dell          | Precision 5560              | Notebook    | [5e70cfd82f](https://linux-hardware.org/?probe=5e70cfd82f) | Sep 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [bb8fdeb489](https://linux-hardware.org/?probe=bb8fdeb489) | Sep 19, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [6c63c03b9f](https://linux-hardware.org/?probe=6c63c03b9f) | Sep 19, 2022 |
| Dell          | Latitude 5420               | Notebook    | [1e5a1652cc](https://linux-hardware.org/?probe=1e5a1652cc) | Sep 19, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [7c89dc4342](https://linux-hardware.org/?probe=7c89dc4342) | Sep 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [8d2c35d5f2](https://linux-hardware.org/?probe=8d2c35d5f2) | Sep 19, 2022 |
| Lenovo        | ThinkPad T430 2349S4D       | Notebook    | [0c4d98868f](https://linux-hardware.org/?probe=0c4d98868f) | Sep 19, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [27d1f0c593](https://linux-hardware.org/?probe=27d1f0c593) | Sep 19, 2022 |
| ASUSTek       | P8Q77-M2                    | Desktop     | [171e24a5c1](https://linux-hardware.org/?probe=171e24a5c1) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [798bb8eda6](https://linux-hardware.org/?probe=798bb8eda6) | Sep 18, 2022 |
| HP            | 84EF 01100                  | All in one  | [2cde64548f](https://linux-hardware.org/?probe=2cde64548f) | Sep 18, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [f114799ded](https://linux-hardware.org/?probe=f114799ded) | Sep 18, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5364b3d032](https://linux-hardware.org/?probe=5364b3d032) | Sep 18, 2022 |
| ASUSTek       | PRIME H410M-K R2.0          | Desktop     | [7d18b85f33](https://linux-hardware.org/?probe=7d18b85f33) | Sep 18, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [b9bb35af47](https://linux-hardware.org/?probe=b9bb35af47) | Sep 18, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [2032e77931](https://linux-hardware.org/?probe=2032e77931) | Sep 18, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [21da8441d5](https://linux-hardware.org/?probe=21da8441d5) | Sep 18, 2022 |
| Casper        | NIRVANA DESKTOP             | Desktop     | [7cdffad4a2](https://linux-hardware.org/?probe=7cdffad4a2) | Sep 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [751df30316](https://linux-hardware.org/?probe=751df30316) | Sep 18, 2022 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [1f27376b8e](https://linux-hardware.org/?probe=1f27376b8e) | Sep 18, 2022 |
| Acer          | Aspire TC-780               | Desktop     | [936ece435c](https://linux-hardware.org/?probe=936ece435c) | Sep 18, 2022 |
| Acer          | A75F2-M2 P21-A1             | Desktop     | [2d00ba463b](https://linux-hardware.org/?probe=2d00ba463b) | Sep 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECC... | Notebook    | [e09b077e89](https://linux-hardware.org/?probe=e09b077e89) | Sep 18, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [1f9f8ee511](https://linux-hardware.org/?probe=1f9f8ee511) | Sep 18, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [0760539d3d](https://linux-hardware.org/?probe=0760539d3d) | Sep 18, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [fa2122b6ee](https://linux-hardware.org/?probe=fa2122b6ee) | Sep 18, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f27404a984](https://linux-hardware.org/?probe=f27404a984) | Sep 18, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [1c3c64ca91](https://linux-hardware.org/?probe=1c3c64ca91) | Sep 17, 2022 |
| Acer          | Spin SP111-31               | Convertible | [fbeb9df498](https://linux-hardware.org/?probe=fbeb9df498) | Sep 17, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [a171efb42c](https://linux-hardware.org/?probe=a171efb42c) | Sep 17, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [ba54a7bf0c](https://linux-hardware.org/?probe=ba54a7bf0c) | Sep 17, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [fd0bcfd41d](https://linux-hardware.org/?probe=fd0bcfd41d) | Sep 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [3b0169723f](https://linux-hardware.org/?probe=3b0169723f) | Sep 17, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [5a541fecce](https://linux-hardware.org/?probe=5a541fecce) | Sep 17, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [379aaf7b61](https://linux-hardware.org/?probe=379aaf7b61) | Sep 16, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [467d4c60c0](https://linux-hardware.org/?probe=467d4c60c0) | Sep 16, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [c5474e5fe3](https://linux-hardware.org/?probe=c5474e5fe3) | Sep 16, 2022 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [e191511194](https://linux-hardware.org/?probe=e191511194) | Sep 16, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [88481ce853](https://linux-hardware.org/?probe=88481ce853) | Sep 16, 2022 |
| Dell          | G3 3779                     | Notebook    | [5c24653999](https://linux-hardware.org/?probe=5c24653999) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [70a944e816](https://linux-hardware.org/?probe=70a944e816) | Sep 16, 2022 |
| Lenovo        | ThinkPad T480 20L5S1S000    | Notebook    | [50669d6ff9](https://linux-hardware.org/?probe=50669d6ff9) | Sep 16, 2022 |
| Acidanther... | iMac19,2                    | Notebook    | [94b79ac6e5](https://linux-hardware.org/?probe=94b79ac6e5) | Sep 16, 2022 |
| Dell          | Latitude 5511               | Notebook    | [9a2faa8d22](https://linux-hardware.org/?probe=9a2faa8d22) | Sep 16, 2022 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [07dd87b76b](https://linux-hardware.org/?probe=07dd87b76b) | Sep 16, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [a29728a871](https://linux-hardware.org/?probe=a29728a871) | Sep 16, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [4d460404c8](https://linux-hardware.org/?probe=4d460404c8) | Sep 16, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [1cbebfbe09](https://linux-hardware.org/?probe=1cbebfbe09) | Sep 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [9bfc1472d1](https://linux-hardware.org/?probe=9bfc1472d1) | Sep 16, 2022 |
| ASUSTek       | X550JK                      | Notebook    | [5c399f4fb0](https://linux-hardware.org/?probe=5c399f4fb0) | Sep 15, 2022 |
| ASUSTek       | X550JK                      | Notebook    | [59df382a23](https://linux-hardware.org/?probe=59df382a23) | Sep 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [80638ed98f](https://linux-hardware.org/?probe=80638ed98f) | Sep 15, 2022 |
| ASRock        | X370 Gaming K4              | Desktop     | [0858e80da7](https://linux-hardware.org/?probe=0858e80da7) | Sep 15, 2022 |
| Gigabyte      | Z97P-D3                     | Desktop     | [ca9e537823](https://linux-hardware.org/?probe=ca9e537823) | Sep 15, 2022 |
| ASUSTek       | P5PL2-E                     | Desktop     | [84bfb7d319](https://linux-hardware.org/?probe=84bfb7d319) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [c70951aae5](https://linux-hardware.org/?probe=c70951aae5) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [4b19ce2aab](https://linux-hardware.org/?probe=4b19ce2aab) | Sep 15, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [f566a009c8](https://linux-hardware.org/?probe=f566a009c8) | Sep 15, 2022 |
| HP            | Snappy                      | Notebook    | [d890c80994](https://linux-hardware.org/?probe=d890c80994) | Sep 15, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [6d4adb2a44](https://linux-hardware.org/?probe=6d4adb2a44) | Sep 14, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [d34c655d2b](https://linux-hardware.org/?probe=d34c655d2b) | Sep 14, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [efb36530f1](https://linux-hardware.org/?probe=efb36530f1) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [bbc3c68696](https://linux-hardware.org/?probe=bbc3c68696) | Sep 14, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [55216d250b](https://linux-hardware.org/?probe=55216d250b) | Sep 14, 2022 |
| HP            | 805D                        | Desktop     | [8acaebbd42](https://linux-hardware.org/?probe=8acaebbd42) | Sep 14, 2022 |
| Dell          | Latitude 5521               | Notebook    | [c342e3ab13](https://linux-hardware.org/?probe=c342e3ab13) | Sep 14, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [23c756841a](https://linux-hardware.org/?probe=23c756841a) | Sep 14, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [e7cb70c141](https://linux-hardware.org/?probe=e7cb70c141) | Sep 14, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [754d0f3a2b](https://linux-hardware.org/?probe=754d0f3a2b) | Sep 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [3f34e5ed01](https://linux-hardware.org/?probe=3f34e5ed01) | Sep 14, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_36/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.17.5-300.fc36.x86_64       | 173       | 7.52%   |
| 6.0.5-200.fc36.x86_64        | 116       | 5.04%   |
| 5.18.13-200.fc36.x86_64      | 112       | 4.87%   |
| 5.19.16-200.fc36.x86_64      | 93        | 4.04%   |
| 5.18.11-200.fc36.x86_64      | 90        | 3.91%   |
| 5.19.9-200.fc36.x86_64       | 87        | 3.78%   |
| 5.18.16-200.fc36.x86_64      | 85        | 3.7%    |
| 5.18.5-200.fc36.x86_64       | 75        | 3.26%   |
| 5.17.6-300.fc36.x86_64       | 74        | 3.22%   |
| 5.17.11-300.fc36.x86_64      | 72        | 3.13%   |
| 5.19.8-200.fc36.x86_64       | 67        | 2.91%   |
| 5.19.6-200.fc36.x86_64       | 65        | 2.83%   |
| 5.18.17-200.fc36.x86_64      | 54        | 2.35%   |
| 5.17.13-300.fc36.x86_64      | 54        | 2.35%   |
| 5.19.4-200.fc36.x86_64       | 52        | 2.26%   |
| 5.19.15-201.fc36.x86_64      | 48        | 2.09%   |
| 5.19.11-200.fc36.x86_64      | 47        | 2.04%   |
| 5.18.9-200.fc36.x86_64       | 47        | 2.04%   |
| 5.18.19-200.fc36.x86_64      | 47        | 2.04%   |
| 5.17.12-300.fc36.x86_64      | 47        | 2.04%   |
| 5.18.18-200.fc36.x86_64      | 46        | 2%      |
| 5.18.10-200.fc36.x86_64      | 46        | 2%      |
| 5.17.8-300.fc36.x86_64       | 44        | 1.91%   |
| 5.19.14-200.fc36.x86_64      | 42        | 1.83%   |
| 5.18.6-200.fc36.x86_64       | 39        | 1.7%    |
| 5.19.13-200.fc36.x86_64      | 38        | 1.65%   |
| 5.19.12-200.fc36.x86_64      | 36        | 1.57%   |
| 5.18.7-200.fc36.x86_64       | 36        | 1.57%   |
| 5.17.7-300.fc36.x86_64       | 33        | 1.43%   |
| 5.17.9-300.fc36.x86_64       | 29        | 1.26%   |
| 5.17.1-300.fc36.x86_64       | 29        | 1.26%   |
| 6.0.7-200.fc36.x86_64        | 25        | 1.09%   |
| 5.17.2-300.fc36.x86_64       | 25        | 1.09%   |
| 5.19.10-200.fc36.x86_64      | 21        | 0.91%   |
| 5.17.3-302.fc36.x86_64       | 20        | 0.87%   |
| 5.17.0-0.rc7.116.fc36.x86_64 | 18        | 0.78%   |
| 6.0.9-200.fc36.x86_64        | 16        | 0.7%    |
| 6.0.8-200.fc36.x86_64        | 16        | 0.7%    |
| 5.18.15-200.fc36.x86_64      | 16        | 0.7%    |
| 6.0.10-200.fc36.x86_64       | 15        | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.5  | 176       | 7.66%   |
| 6.0.5   | 116       | 5.05%   |
| 5.18.13 | 113       | 4.92%   |
| 5.19.16 | 94        | 4.09%   |
| 5.18.11 | 90        | 3.91%   |
| 5.19.9  | 88        | 3.83%   |
| 5.18.16 | 86        | 3.74%   |
| 5.18.5  | 81        | 3.52%   |
| 5.17.6  | 77        | 3.35%   |
| 5.17.11 | 75        | 3.26%   |
| 5.19.8  | 68        | 2.96%   |
| 5.19.6  | 67        | 2.91%   |
| 5.18.17 | 54        | 2.35%   |
| 5.17.13 | 54        | 2.35%   |
| 5.19.4  | 53        | 2.31%   |
| 5.18.9  | 50        | 2.17%   |
| 5.18.10 | 50        | 2.17%   |
| 5.19.15 | 49        | 2.13%   |
| 5.18.18 | 49        | 2.13%   |
| 5.17.12 | 49        | 2.13%   |
| 5.19.11 | 47        | 2.04%   |
| 5.18.19 | 47        | 2.04%   |
| 5.17.8  | 44        | 1.91%   |
| 5.19.14 | 42        | 1.83%   |
| 5.18.6  | 42        | 1.83%   |
| 5.19.13 | 39        | 1.7%    |
| 5.19.12 | 38        | 1.65%   |
| 5.18.7  | 37        | 1.61%   |
| 5.17.7  | 35        | 1.52%   |
| 5.17.9  | 32        | 1.39%   |
| 5.17.1  | 30        | 1.3%    |
| 5.17.0  | 27        | 1.17%   |
| 5.17.2  | 26        | 1.13%   |
| 6.0.7   | 25        | 1.09%   |
| 5.17.3  | 22        | 0.96%   |
| 5.19.10 | 21        | 0.91%   |
| 6.0.9   | 17        | 0.74%   |
| 6.0.8   | 17        | 0.74%   |
| 5.19.7  | 16        | 0.7%    |
| 5.18.15 | 16        | 0.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.18    | 696       | 31.45%  |
| 5.17    | 638       | 28.83%  |
| 5.19    | 610       | 27.56%  |
| 6.0     | 233       | 10.53%  |
| 6.1     | 15        | 0.68%   |
| 5.15    | 8         | 0.36%   |
| 5.16    | 7         | 0.32%   |
| 5.14    | 4         | 0.18%   |
| 5.4     | 1         | 0.05%   |
| 5.11    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2059      | 99.85%  |
| aarch64 | 3         | 0.15%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 1537      | 74%     |
| KDE5          | 346       | 16.66%  |
| Unknown       | 49        | 2.36%   |
| XFCE          | 41        | 1.97%   |
| X-Cinnamon    | 27        | 1.3%    |
| Cinnamon      | 20        | 0.96%   |
| MATE          | 15        | 0.72%   |
| i3            | 11        | 0.53%   |
| LXQt          | 8         | 0.39%   |
| GNOME Classic | 7         | 0.34%   |
| sway          | 4         | 0.19%   |
| awesome       | 3         | 0.14%   |
| Deepin        | 2         | 0.1%    |
| Pantheon      | 1         | 0.05%   |
| openbox       | 1         | 0.05%   |
| LXDE          | 1         | 0.05%   |
| KDE:old       | 1         | 0.05%   |
| KDE           | 1         | 0.05%   |
| fluxbox       | 1         | 0.05%   |
| bspwm         | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 1481      | 71%     |
| X11     | 544       | 26.08%  |
| Tty     | 37        | 1.77%   |
| Unknown | 22        | 1.05%   |
| Web     | 2         | 0.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1082      | 52.04%  |
| GDM     | 697       | 33.53%  |
| SDDM    | 180       | 8.66%   |
| LightDM | 118       | 5.68%   |
| Ly      | 1         | 0.05%   |
| KDM     | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1112      | 53.8%   |
| ru_RU   | 124       | 6%      |
| en_GB   | 124       | 6%      |
| it_IT   | 89        | 4.31%   |
| de_DE   | 82        | 3.97%   |
| pt_BR   | 78        | 3.77%   |
| en_AU   | 57        | 2.76%   |
| fr_FR   | 49        | 2.37%   |
| es_ES   | 38        | 1.84%   |
| en_CA   | 38        | 1.84%   |
| pl_PL   | 34        | 1.64%   |
| en_IN   | 25        | 1.21%   |
| es_MX   | 17        | 0.82%   |
| en_NZ   | 14        | 0.68%   |
| tr_TR   | 10        | 0.48%   |
| nl_NL   | 10        | 0.48%   |
| hu_HU   | 9         | 0.44%   |
| es_AR   | 9         | 0.44%   |
| cs_CZ   | 9         | 0.44%   |
| nl_BE   | 8         | 0.39%   |
| es_CL   | 8         | 0.39%   |
| pt_PT   | 7         | 0.34%   |
| Unknown | 7         | 0.34%   |
| zh_CN   | 6         | 0.29%   |
| sv_SE   | 6         | 0.29%   |
| en_IE   | 6         | 0.29%   |
| de_AT   | 6         | 0.29%   |
| ru_UA   | 5         | 0.24%   |
| fr_BE   | 5         | 0.24%   |
| es_CO   | 5         | 0.24%   |
| da_DK   | 5         | 0.24%   |
| ja_JP   | 4         | 0.19%   |
| en_ZA   | 4         | 0.19%   |
| de_CH   | 4         | 0.19%   |
| C       | 4         | 0.19%   |
| nb_NO   | 3         | 0.15%   |
| en_IL   | 3         | 0.15%   |
| en_DK   | 3         | 0.15%   |
| ca_ES   | 3         | 0.15%   |
| sr_RS   | 2         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1687      | 81.46%  |
| BIOS | 384       | 18.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 1648      | 79.77%  |
| Ext4    | 366       | 17.72%  |
| Xfs     | 48        | 2.32%   |
| F2fs    | 2         | 0.1%    |
| Overlay | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1076      | 51.73%  |
| GPT     | 889       | 42.74%  |
| MBR     | 115       | 5.53%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1842      | 88.81%  |
| Yes       | 232       | 11.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1629      | 78.43%  |
| Yes       | 448       | 21.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 412       | 19.98%  |
| ASUSTek Computer       | 362       | 17.56%  |
| Hewlett-Packard        | 276       | 13.39%  |
| Dell                   | 256       | 12.42%  |
| MSI                    | 142       | 6.89%   |
| Gigabyte Technology    | 136       | 6.6%    |
| Acer                   | 83        | 4.03%   |
| ASRock                 | 61        | 2.96%   |
| Apple                  | 52        | 2.52%   |
| HUAWEI                 | 26        | 1.26%   |
| Intel                  | 19        | 0.92%   |
| Microsoft              | 15        | 0.73%   |
| Samsung Electronics    | 13        | 0.63%   |
| Framework              | 13        | 0.63%   |
| Toshiba                | 12        | 0.58%   |
| Unknown                | 12        | 0.58%   |
| Timi                   | 10        | 0.48%   |
| BESSTAR Tech           | 10        | 0.48%   |
| Sony                   | 9         | 0.44%   |
| Notebook               | 9         | 0.44%   |
| Chuwi                  | 7         | 0.34%   |
| Foxconn                | 6         | 0.29%   |
| TUXEDO                 | 5         | 0.24%   |
| Positivo               | 5         | 0.24%   |
| Alienware              | 5         | 0.24%   |
| System76               | 4         | 0.19%   |
| Huanan                 | 4         | 0.19%   |
| Fujitsu                | 4         | 0.19%   |
| VALE                   | 3         | 0.15%   |
| Pegatron               | 3         | 0.15%   |
| Panasonic              | 3         | 0.15%   |
| LG Electronics         | 3         | 0.15%   |
| HONOR                  | 3         | 0.15%   |
| GPU Company            | 3         | 0.15%   |
| Google                 | 3         | 0.15%   |
| Biostar                | 3         | 0.15%   |
| Avell High Performance | 3         | 0.15%   |
| Acidanthera            | 3         | 0.15%   |
| ZOTAC                  | 2         | 0.1%    |
| UNOWHY                 | 2         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 20        | 0.97%   |
| ASUS All Series                        | 14        | 0.68%   |
| Framework Laptop                       | 9         | 0.44%   |
| MSI MS-7C37                            | 8         | 0.39%   |
| Dell XPS 15 9570                       | 8         | 0.39%   |
| MSI MS-7A38                            | 7         | 0.34%   |
| HP Notebook                            | 7         | 0.34%   |
| ASUS ROG STRIX B550-F GAMING           | 7         | 0.34%   |
| MSI MS-7C91                            | 6         | 0.29%   |
| MSI MS-7B86                            | 6         | 0.29%   |
| Lenovo IdeaPad 3 15ITL6 82H8           | 6         | 0.29%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 5         | 0.24%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY   | 5         | 0.24%   |
| Lenovo IdeaPad 5 15ARE05 81YQ          | 5         | 0.24%   |
| HP Pavilion g6                         | 5         | 0.24%   |
| HP EliteBook 8470p                     | 5         | 0.24%   |
| Dell XPS 15 9510                       | 5         | 0.24%   |
| Dell Latitude E6420                    | 5         | 0.24%   |
| ASUS TUF Gaming X570-PLUS              | 5         | 0.24%   |
| ASUS TUF Gaming B550M-PLUS             | 5         | 0.24%   |
| ASUS ROG Zephyrus G14 GA402RJ_GA402RJ  | 5         | 0.24%   |
| ASUS ROG STRIX X570-F GAMING           | 5         | 0.24%   |
| Apple MacBookPro12,1                   | 5         | 0.24%   |
| MSI MS-7B79                            | 4         | 0.19%   |
| Lenovo IdeaPad 5 14ARE05 81YM          | 4         | 0.19%   |
| HP Pavilion Aero Laptop 13-be0xxx      | 4         | 0.19%   |
| HP ENVY x360 2-in-1 Laptop 15-ey0xxx   | 4         | 0.19%   |
| Gigabyte B550I AORUS PRO AX            | 4         | 0.19%   |
| Gigabyte B450M DS3H                    | 4         | 0.19%   |
| Gigabyte B450 AORUS ELITE              | 4         | 0.19%   |
| Framework Laptop (12th Gen Intel Core) | 4         | 0.19%   |
| Dell XPS 13 9310                       | 4         | 0.19%   |
| Dell OptiPlex 9020                     | 4         | 0.19%   |
| ASUS TUF Gaming B550-PLUS              | 4         | 0.19%   |
| ASUS ROG Strix G513QY_G513QY           | 4         | 0.19%   |
| ASUS PRIME Z370-A                      | 4         | 0.19%   |
| ASUS PRIME B450-PLUS                   | 4         | 0.19%   |
| ASRock B450M Pro4                      | 4         | 0.19%   |
| Apple MacBookPro9,2                    | 4         | 0.19%   |
| Timi Redmi Book Pro 15 2022            | 3         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 198       | 9.6%    |
| ASUS ROG           | 94        | 4.56%   |
| Lenovo IdeaPad     | 89        | 4.32%   |
| Dell Inspiron      | 72        | 3.49%   |
| Dell XPS           | 59        | 2.86%   |
| Dell Latitude      | 56        | 2.72%   |
| HP Pavilion        | 50        | 2.42%   |
| ASUS PRIME         | 46        | 2.23%   |
| Acer Aspire        | 41        | 1.99%   |
| ASUS TUF           | 39        | 1.89%   |
| HP EliteBook       | 36        | 1.75%   |
| ASUS VivoBook      | 34        | 1.65%   |
| HP Laptop          | 32        | 1.55%   |
| Dell Precision     | 30        | 1.45%   |
| HP ENVY            | 29        | 1.41%   |
| HP ProBook         | 27        | 1.31%   |
| Lenovo Yoga        | 25        | 1.21%   |
| Lenovo ThinkBook   | 23        | 1.12%   |
| Lenovo Legion      | 20        | 0.97%   |
| Unknown            | 20        | 0.97%   |
| Dell OptiPlex      | 17        | 0.82%   |
| ASUS ASUS          | 16        | 0.78%   |
| Microsoft Surface  | 15        | 0.73%   |
| ASUS All           | 14        | 0.68%   |
| HP ZBook           | 13        | 0.63%   |
| Framework Laptop   | 13        | 0.63%   |
| Acer Nitro         | 13        | 0.63%   |
| Lenovo IdeaPadFlex | 12        | 0.58%   |
| HP Compaq          | 11        | 0.53%   |
| Dell Vostro        | 11        | 0.53%   |
| Toshiba Satellite  | 10        | 0.48%   |
| Lenovo ThinkCentre | 10        | 0.48%   |
| Acer Swift         | 10        | 0.48%   |
| MSI Modern         | 9         | 0.44%   |
| MSI MS-7C37        | 8         | 0.39%   |
| Gigabyte B450      | 8         | 0.39%   |
| ASUS Zenbook       | 8         | 0.39%   |
| MSI MS-7A38        | 7         | 0.34%   |
| HP ProDesk         | 7         | 0.34%   |
| HP Notebook        | 7         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 369       | 17.9%   |
| 2020    | 325       | 15.76%  |
| 2019    | 235       | 11.4%   |
| 2018    | 208       | 10.09%  |
| 2022    | 136       | 6.6%    |
| 2017    | 133       | 6.45%   |
| 2012    | 102       | 4.95%   |
| 2016    | 95        | 4.61%   |
| 2014    | 95        | 4.61%   |
| 2015    | 94        | 4.56%   |
| 2013    | 91        | 4.41%   |
| 2011    | 72        | 3.49%   |
| 2010    | 39        | 1.89%   |
| 2009    | 31        | 1.5%    |
| 2008    | 22        | 1.07%   |
| 2007    | 8         | 0.39%   |
| 2006    | 5         | 0.24%   |
| 2005    | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1199      | 58.15%  |
| Desktop        | 655       | 31.77%  |
| Convertible    | 115       | 5.58%   |
| Tablet         | 34        | 1.65%   |
| Mini pc        | 27        | 1.31%   |
| All in one     | 24        | 1.16%   |
| Server         | 5         | 0.24%   |
| System on chip | 3         | 0.15%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1691      | 81.65%  |
| Enabled  | 380       | 18.35%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2056      | 99.71%  |
| Yes  | 6         | 0.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 524       | 25.24%  |
| 4.01-8.0        | 490       | 23.6%   |
| 8.01-16.0       | 387       | 18.64%  |
| 32.01-64.0      | 348       | 16.76%  |
| 3.01-4.0        | 165       | 7.95%   |
| 64.01-256.0     | 93        | 4.48%   |
| 24.01-32.0      | 37        | 1.78%   |
| 1.01-2.0        | 25        | 1.2%    |
| 2.01-3.0        | 5         | 0.24%   |
| More than 256.0 | 1         | 0.05%   |
| 0.51-1.0        | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 658       | 30.14%  |
| 2.01-3.0    | 559       | 25.61%  |
| 3.01-4.0    | 508       | 23.27%  |
| 1.01-2.0    | 221       | 10.12%  |
| 8.01-16.0   | 181       | 8.29%   |
| 16.01-24.0  | 23        | 1.05%   |
| 0.51-1.0    | 19        | 0.87%   |
| 24.01-32.0  | 6         | 0.27%   |
| 0.01-0.5    | 4         | 0.18%   |
| 32.01-64.0  | 3         | 0.14%   |
| 64.01-256.0 | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1212      | 58.1%   |
| 2      | 549       | 26.32%  |
| 3      | 171       | 8.2%    |
| 4      | 81        | 3.88%   |
| 5      | 30        | 1.44%   |
| 6      | 20        | 0.96%   |
| 7      | 10        | 0.48%   |
| 0      | 6         | 0.29%   |
| 11     | 2         | 0.1%    |
| 10     | 2         | 0.1%    |
| 13     | 1         | 0.05%   |
| 12     | 1         | 0.05%   |
| 9      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1646      | 79.59%  |
| Yes       | 422       | 20.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1578      | 76.27%  |
| No        | 491       | 23.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1740      | 84.3%   |
| No        | 324       | 15.7%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1532      | 74.01%  |
| No        | 538       | 25.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 431       | 20.82%  |
| Germany     | 155       | 7.49%   |
| Russia      | 146       | 7.05%   |
| Italy       | 146       | 7.05%   |
| Brazil      | 117       | 5.65%   |
| India       | 68        | 3.29%   |
| UK          | 65        | 3.14%   |
| Australia   | 65        | 3.14%   |
| France      | 63        | 3.04%   |
| Poland      | 59        | 2.85%   |
| Spain       | 53        | 2.56%   |
| Netherlands | 50        | 2.42%   |
| Canada      | 48        | 2.32%   |
| Mexico      | 41        | 1.98%   |
| Turkey      | 34        | 1.64%   |
| Belgium     | 30        | 1.45%   |
| Argentina   | 24        | 1.16%   |
| Sweden      | 22        | 1.06%   |
| Indonesia   | 21        | 1.01%   |
| Hungary     | 19        | 0.92%   |
| Finland     | 19        | 0.92%   |
| Norway      | 17        | 0.82%   |
| Czechia     | 17        | 0.82%   |
| Switzerland | 16        | 0.77%   |
| Portugal    | 15        | 0.72%   |
| Belarus     | 15        | 0.72%   |
| Austria     | 15        | 0.72%   |
| Romania     | 14        | 0.68%   |
| New Zealand | 12        | 0.58%   |
| Colombia    | 11        | 0.53%   |
| Japan       | 10        | 0.48%   |
| Israel      | 10        | 0.48%   |
| Ireland     | 10        | 0.48%   |
| Chile       | 10        | 0.48%   |
| Philippines | 9         | 0.43%   |
| Denmark     | 9         | 0.43%   |
| Greece      | 8         | 0.39%   |
| China       | 8         | 0.39%   |
| Ukraine     | 7         | 0.34%   |
| Kenya       | 7         | 0.34%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Moscow         | 41        | 1.93%   |
| St Petersburg  | 27        | 1.27%   |
| Sao Paulo      | 20        | 0.94%   |
| Warsaw         | 18        | 0.85%   |
| Melbourne      | 18        | 0.85%   |
| Berlin         | 18        | 0.85%   |
| Brisbane       | 16        | 0.75%   |
| Milan          | 15        | 0.71%   |
| Rome           | 14        | 0.66%   |
| Istanbul       | 13        | 0.61%   |
| Chicago        | 13        | 0.61%   |
| Sydney         | 11        | 0.52%   |
| Paris          | 11        | 0.52%   |
| Minsk          | 11        | 0.52%   |
| Mexico City    | 11        | 0.52%   |
| Helsinki       | 11        | 0.52%   |
| New York       | 9         | 0.42%   |
| Munich         | 9         | 0.42%   |
| Launceston     | 9         | 0.42%   |
| Budapest       | 9         | 0.42%   |
| Auckland       | 9         | 0.42%   |
| Verona         | 8         | 0.38%   |
| Prague         | 8         | 0.38%   |
| Oslo           | 8         | 0.38%   |
| Kolkata        | 8         | 0.38%   |
| Bengaluru      | 8         | 0.38%   |
| Stockholm      | 7         | 0.33%   |
| Los Angeles    | 7         | 0.33%   |
| Jakarta        | 7         | 0.33%   |
| Izmir          | 7         | 0.33%   |
| Bucharest      | 7         | 0.33%   |
| Amsterdam      | 7         | 0.33%   |
| Vienna         | 6         | 0.28%   |
| Santiago       | 6         | 0.28%   |
| San Jose       | 6         | 0.28%   |
| Rio de Janeiro | 6         | 0.28%   |
| Porto Alegre   | 6         | 0.28%   |
| Portland       | 6         | 0.28%   |
| Novosibirsk    | 6         | 0.28%   |
| Nairobi        | 6         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 611       | 837    | 19.68%  |
| WDC                       | 395       | 555    | 12.73%  |
| Seagate                   | 324       | 451    | 10.44%  |
| SanDisk                   | 202       | 242    | 6.51%   |
| Kingston                  | 177       | 203    | 5.7%    |
| Toshiba                   | 152       | 180    | 4.9%    |
| SK hynix                  | 126       | 138    | 4.06%   |
| Crucial                   | 125       | 162    | 4.03%   |
| Intel                     | 103       | 137    | 3.32%   |
| Unknown                   | 97        | 119    | 3.13%   |
| Micron Technology         | 89        | 100    | 2.87%   |
| KIOXIA                    | 50        | 65     | 1.61%   |
| Phison                    | 45        | 48     | 1.45%   |
| A-DATA Technology         | 45        | 49     | 1.45%   |
| Hitachi                   | 40        | 55     | 1.29%   |
| HGST                      | 33        | 40     | 1.06%   |
| Apple                     | 27        | 29     | 0.87%   |
| Silicon Motion            | 26        | 26     | 0.84%   |
| China                     | 26        | 30     | 0.84%   |
| Micron/Crucial Technology | 21        | 26     | 0.68%   |
| Unknown                   | 19        | 19     | 0.61%   |
| PNY                       | 18        | 22     | 0.58%   |
| SPCC                      | 17        | 22     | 0.55%   |
| Phison Electronics        | 17        | 19     | 0.55%   |
| Patriot                   | 16        | 18     | 0.52%   |
| XPG                       | 14        | 18     | 0.45%   |
| LITEON                    | 14        | 14     | 0.45%   |
| ADATA Technology          | 11        | 11     | 0.35%   |
| UMIS                      | 10        | 14     | 0.32%   |
| Transcend                 | 10        | 13     | 0.32%   |
| Netac                     | 10        | 10     | 0.32%   |
| Intenso                   | 10        | 12     | 0.32%   |
| SABRENT                   | 9         | 11     | 0.29%   |
| Team                      | 8         | 11     | 0.26%   |
| SSSTC                     | 8         | 8      | 0.26%   |
| Corsair                   | 8         | 10     | 0.26%   |
| Realtek Semiconductor     | 7         | 7      | 0.23%   |
| LITEONIT                  | 7         | 7      | 0.23%   |
| Hewlett-Packard           | 7         | 15     | 0.23%   |
| Gigabyte Technology       | 7         | 11     | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB  | 42        | 1.23%   |
| Kingston SA400S37240G 240GB SSD                      | 40        | 1.17%   |
| Samsung NVMe SSD Drive 1TB                           | 36        | 1.05%   |
| SanDisk NVMe SSD Drive 512GB                         | 29        | 0.85%   |
| Samsung NVMe SSD Drive 512GB                         | 27        | 0.79%   |
| Seagate ST1000LM035-1RK172 1TB                       | 26        | 0.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 25        | 0.73%   |
| Samsung SSD 850 EVO 250GB                            | 25        | 0.73%   |
| Samsung NVMe SSD Drive 500GB                         | 25        | 0.73%   |
| Samsung SSD 860 EVO 500GB                            | 24        | 0.7%    |
| SanDisk NVMe SSD Drive 1TB                           | 23        | 0.67%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB               | 22        | 0.64%   |
| Samsung NVMe SSD Drive 1024GB                        | 20        | 0.59%   |
| Unknown MMC Card  64GB                               | 19        | 0.56%   |
| Seagate ST1000DM010-2EP102 1TB                       | 19        | 0.56%   |
| Intel NVMe SSD Drive 512GB                           | 19        | 0.56%   |
| HGST HTS721010A9E630 1TB                             | 19        | 0.56%   |
| Unknown                                              | 19        | 0.56%   |
| Seagate ST500DM002-1BD142 500GB                      | 18        | 0.53%   |
| Kingston SA400S37120G 120GB SSD                      | 18        | 0.53%   |
| Crucial CT500MX500SSD1 500GB                         | 18        | 0.53%   |
| Crucial CT1000MX500SSD1 1TB                          | 18        | 0.53%   |
| Samsung SSD 980 PRO 1TB                              | 16        | 0.47%   |
| Samsung SSD 850 EVO 500GB                            | 16        | 0.47%   |
| Samsung NVMe SSD Drive 2TB                           | 16        | 0.47%   |
| SK hynix NVMe SSD Drive 512GB                        | 15        | 0.44%   |
| SanDisk NVMe SSD Drive 500GB                         | 15        | 0.44%   |
| Samsung SSD 860 EVO 250GB                            | 15        | 0.44%   |
| Seagate ST2000DM008-2FR102 2TB                       | 14        | 0.41%   |
| Samsung SSD 860 EVO 1TB                              | 14        | 0.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 14        | 0.41%   |
| Micron NVMe SSD Drive 512GB                          | 14        | 0.41%   |
| KIOXIA NVMe SSD Drive 512GB                          | 14        | 0.41%   |
| Kingston SA400S37480G 480GB SSD                      | 14        | 0.41%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 13        | 0.38%   |
| Seagate ST1000DM003-1ER162 1TB                       | 13        | 0.38%   |
| Samsung SSD 970 EVO Plus 500GB                       | 13        | 0.38%   |
| Samsung SSD 970 EVO Plus 2TB                         | 13        | 0.38%   |
| Crucial CT480BX500SSD1 480GB                         | 13        | 0.38%   |
| Samsung SSD 970 EVO Plus 1TB                         | 12        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 313       | 433    | 39.72%  |
| WDC                 | 255       | 371    | 32.36%  |
| Toshiba             | 89        | 100    | 11.29%  |
| Hitachi             | 40        | 55     | 5.08%   |
| HGST                | 33        | 40     | 4.19%   |
| Samsung Electronics | 11        | 20     | 1.4%    |
| SABRENT             | 8         | 10     | 1.02%   |
| Apple               | 8         | 8      | 1.02%   |
| Unknown             | 7         | 8      | 0.89%   |
| Fujitsu             | 5         | 6      | 0.63%   |
| Hewlett-Packard     | 4         | 12     | 0.51%   |
| USB3.0              | 2         | 2      | 0.25%   |
| USB                 | 2         | 2      | 0.25%   |
| ASMT                | 2         | 2      | 0.25%   |
| SAGE                | 1         | 1      | 0.13%   |
| RSH-339             | 1         | 1      | 0.13%   |
| Maxtor              | 1         | 3      | 0.13%   |
| JMicron Technology  | 1         | 1      | 0.13%   |
| Intenso             | 1         | 1      | 0.13%   |
| IB-AC703            | 1         | 1      | 0.13%   |
| ExcelStor           | 1         | 1      | 0.13%   |
| ASMT106x            | 1         | 1      | 0.13%   |
| Unknown             | 1         | 1      | 0.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 233       | 301    | 24.92%  |
| Kingston            | 123       | 141    | 13.16%  |
| Crucial             | 110       | 146    | 11.76%  |
| SanDisk             | 76        | 90     | 8.13%   |
| WDC                 | 61        | 80     | 6.52%   |
| Intel               | 28        | 39     | 2.99%   |
| China               | 25        | 29     | 2.67%   |
| A-DATA Technology   | 24        | 25     | 2.57%   |
| Micron Technology   | 22        | 23     | 2.35%   |
| PNY                 | 17        | 20     | 1.82%   |
| Apple               | 15        | 15     | 1.6%    |
| SPCC                | 14        | 19     | 1.5%    |
| SK hynix            | 14        | 15     | 1.5%    |
| Patriot             | 14        | 16     | 1.5%    |
| LITEON              | 12        | 12     | 1.28%   |
| Transcend           | 10        | 13     | 1.07%   |
| Toshiba             | 9         | 11     | 0.96%   |
| Netac               | 8         | 8      | 0.86%   |
| LITEONIT            | 7         | 7      | 0.75%   |
| Intenso             | 7         | 9      | 0.75%   |
| Gigabyte Technology | 7         | 11     | 0.75%   |
| Team                | 6         | 9      | 0.64%   |
| OCZ                 | 6         | 10     | 0.64%   |
| Lexar               | 6         | 7      | 0.64%   |
| GOODRAM             | 6         | 10     | 0.64%   |
| Seagate             | 5         | 5      | 0.53%   |
| Corsair             | 5         | 6      | 0.53%   |
| KingDian            | 4         | 4      | 0.43%   |
| Apacer              | 4         | 4      | 0.43%   |
| Plextor             | 3         | 5      | 0.32%   |
| KIOXIA-EXCERIA      | 3         | 3      | 0.32%   |
| KingSpec            | 3         | 3      | 0.32%   |
| GALAX               | 3         | 3      | 0.32%   |
| Unknown             | 3         | 3      | 0.32%   |
| Verbatim            | 2         | 4      | 0.21%   |
| Mushkin             | 2         | 3      | 0.21%   |
| Leven               | 2         | 2      | 0.21%   |
| JMicron Technology  | 2         | 3      | 0.21%   |
| GLOWAY              | 2         | 2      | 0.21%   |
| XSTAR               | 1         | 1      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1201      | 1555   | 42.88%  |
| SSD     | 792       | 1153   | 28.28%  |
| HDD     | 669       | 1080   | 23.88%  |
| MMC     | 92        | 118    | 3.28%   |
| Unknown | 47        | 54     | 1.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1201      | 1553   | 46.9%   |
| SATA | 1151      | 2131   | 44.94%  |
| SAS  | 117       | 158    | 4.57%   |
| MMC  | 92        | 118    | 3.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 788       | 1180   | 50.81%  |
| 0.51-1.0   | 504       | 676    | 32.5%   |
| 1.01-2.0   | 133       | 197    | 8.58%   |
| 3.01-4.0   | 60        | 79     | 3.87%   |
| 4.01-10.0  | 37        | 62     | 2.39%   |
| 2.01-3.0   | 25        | 33     | 1.61%   |
| 10.01-20.0 | 4         | 6      | 0.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 446       | 21.16%  |
| 251-500        | 366       | 17.36%  |
| 1001-2000      | 312       | 14.8%   |
| 101-250        | 280       | 13.28%  |
| 1-20           | 221       | 10.48%  |
| More than 3000 | 161       | 7.64%   |
| Unknown        | 135       | 6.4%    |
| 2001-3000      | 90        | 4.27%   |
| 51-100         | 72        | 3.42%   |
| 21-50          | 25        | 1.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 617       | 28.46%  |
| 21-50          | 337       | 15.54%  |
| 101-250        | 280       | 12.92%  |
| 51-100         | 256       | 11.81%  |
| 251-500        | 214       | 9.87%   |
| 501-1000       | 166       | 7.66%   |
| Unknown        | 135       | 6.23%   |
| 1001-2000      | 88        | 4.06%   |
| More than 3000 | 47        | 2.17%   |
| 2001-3000      | 28        | 1.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 5         | 11     | 3.94%   |
| Seagate ST500LT012-1DG142 500GB     | 4         | 4      | 3.15%   |
| Seagate ST3500418AS 500GB           | 4         | 4      | 3.15%   |
| Samsung Electronics SSD 870 EVO 1TB | 4         | 4      | 3.15%   |
| HGST HTS721010A9E630 1TB            | 4         | 4      | 3.15%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 5      | 2.36%   |
| Toshiba MK3275GSX 320GB             | 2         | 3      | 1.57%   |
| Seagate ST500LM021-1KJ152 500GB     | 2         | 2      | 1.57%   |
| Samsung Electronics HD322HJ 320GB   | 2         | 2      | 1.57%   |
| Intel SSDSC2CT120A3 120GB           | 2         | 7      | 1.57%   |
| Intel SSDSC2BF180A4H 180GB          | 2         | 2      | 1.57%   |
| Hitachi HTS545032B9A300 320GB       | 2         | 2      | 1.57%   |
| WDC WD800JD-75MSA3 80GB             | 1         | 1      | 0.79%   |
| WDC WD6400BPVT-75HXZT3 640GB        | 1         | 1      | 0.79%   |
| WDC WD6400BEVT-22A0RT0 640GB        | 1         | 1      | 0.79%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 0.79%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 1         | 1      | 0.79%   |
| WDC WD5000LPCX-00VHAT0 500GB        | 1         | 1      | 0.79%   |
| WDC WD5000AAKX-08ERMA0 500GB        | 1         | 1      | 0.79%   |
| WDC WD5000AAKX-003CA0 500GB         | 1         | 1      | 0.79%   |
| WDC WD5000AADS-00S9B0 500GB         | 1         | 1      | 0.79%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1         | 1      | 0.79%   |
| WDC WD4001FAEX-00MJRA0 4TB          | 1         | 1      | 0.79%   |
| WDC WD3200AAKS-75B3A0 320GB         | 1         | 1      | 0.79%   |
| WDC WD3200AAJS-65M0A0 320GB         | 1         | 1      | 0.79%   |
| WDC WD30EZRX-00SPEB0 3TB            | 1         | 1      | 0.79%   |
| WDC WD2500AAKX-753CA1 250GB         | 1         | 1      | 0.79%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1         | 1      | 0.79%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1         | 1      | 0.79%   |
| WDC WD2003FYYS-02W0B1 2TB           | 1         | 6      | 0.79%   |
| WDC WD10JPVX-60JC3T0 1TB            | 1         | 1      | 0.79%   |
| WDC WD10EZEX-60ZF5A0 1TB            | 1         | 1      | 0.79%   |
| WDC WD10EZEX-22MFCA0 1TB            | 1         | 1      | 0.79%   |
| WDC WD10EZEX-00MFCA0 1TB            | 1         | 1      | 0.79%   |
| WDC WD10EARS-22Y5B1 1TB             | 1         | 1      | 0.79%   |
| WDC WD10EARS-00Y5B1 1TB             | 1         | 1      | 0.79%   |
| WDC WD10EADS-65M2B1 1TB             | 1         | 1      | 0.79%   |
| WDC WD1003FBYX-01Y7B1 1TB           | 1         | 2      | 0.79%   |
| walram SSD 120G                     | 1         | 1      | 0.79%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 0.79%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 43     | 24.17%  |
| WDC                 | 25        | 32     | 20.83%  |
| Samsung Electronics | 14        | 24     | 11.67%  |
| Toshiba             | 8         | 10     | 6.67%   |
| Hitachi             | 8         | 8      | 6.67%   |
| Intel               | 7         | 13     | 5.83%   |
| HGST                | 5         | 5      | 4.17%   |
| SK hynix            | 3         | 3      | 2.5%    |
| SanDisk             | 3         | 4      | 2.5%    |
| Crucial             | 3         | 4      | 2.5%    |
| LITEON              | 2         | 2      | 1.67%   |
| Kingston            | 2         | 2      | 1.67%   |
| walram              | 1         | 1      | 0.83%   |
| SPCC                | 1         | 2      | 0.83%   |
| PNY                 | 1         | 1      | 0.83%   |
| Origin              | 1         | 1      | 0.83%   |
| OCZ-VERTEX3         | 1         | 1      | 0.83%   |
| Micron Technology   | 1         | 1      | 0.83%   |
| LITEONIT            | 1         | 1      | 0.83%   |
| Lenovo              | 1         | 2      | 0.83%   |
| Fujitsu             | 1         | 1      | 0.83%   |
| Apple               | 1         | 1      | 0.83%   |
| A-DATA Technology   | 1         | 1      | 0.83%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 43     | 36.25%  |
| WDC                 | 25        | 32     | 31.25%  |
| Toshiba             | 8         | 10     | 10%     |
| Hitachi             | 8         | 8      | 10%     |
| HGST                | 5         | 5      | 6.25%   |
| Samsung Electronics | 4         | 13     | 5%      |
| Fujitsu             | 1         | 1      | 1.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 77        | 112    | 66.38%  |
| SSD  | 33        | 43     | 28.45%  |
| NVMe | 6         | 8      | 5.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB    | 1         | 1      | 50%     |
| Samsung Electronics SSD 980 500GB | 1         | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1193      | 2291   | 53.62%  |
| Works    | 916       | 1503   | 41.17%  |
| Malfunc  | 114       | 163    | 5.12%   |
| Failed   | 2         | 3      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1136      | 39.1%   |
| AMD                                     | 452       | 15.56%  |
| Samsung Electronics                     | 423       | 14.56%  |
| SanDisk                                 | 213       | 7.33%   |
| SK hynix                                | 111       | 3.82%   |
| Phison Electronics                      | 69        | 2.38%   |
| Micron Technology                       | 66        | 2.27%   |
| Kingston Technology Company             | 59        | 2.03%   |
| Toshiba America Info Systems            | 56        | 1.93%   |
| KIOXIA                                  | 50        | 1.72%   |
| ASMedia Technology                      | 40        | 1.38%   |
| ADATA Technology                        | 39        | 1.34%   |
| Micron/Crucial Technology               | 36        | 1.24%   |
| Silicon Motion                          | 32        | 1.1%    |
| Marvell Technology Group                | 16        | 0.55%   |
| Nvidia                                  | 13        | 0.45%   |
| Union Memory (Shenzhen)                 | 11        | 0.38%   |
| Solid State Storage Technology          | 11        | 0.38%   |
| JMicron Technology                      | 11        | 0.38%   |
| Realtek Semiconductor                   | 9         | 0.31%   |
| Seagate Technology                      | 6         | 0.21%   |
| MAXIO Technology (Hangzhou)             | 5         | 0.17%   |
| LSI Logic / Symbios Logic               | 5         | 0.17%   |
| Lite-On Technology                      | 5         | 0.17%   |
| Apple                                   | 5         | 0.17%   |
| Lenovo                                  | 4         | 0.14%   |
| Silicon Image                           | 3         | 0.1%    |
| INNOGRIT                                | 3         | 0.1%    |
| Hewlett-Packard                         | 3         | 0.1%    |
| Broadcom / LSI                          | 3         | 0.1%    |
| Adaptec                                 | 2         | 0.07%   |
| Yangtze Memory Technologies             | 1         | 0.03%   |
| VIA Technologies                        | 1         | 0.03%   |
| ULi Electronics                         | 1         | 0.03%   |
| Shenzhen Unionmemory Information System | 1         | 0.03%   |
| Netac Technology                        | 1         | 0.03%   |
| Integrated Technology Express           | 1         | 0.03%   |
| Biwin Storage Technology                | 1         | 0.03%   |
| Unknown                                 | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 323       | 10.14%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 195       | 6.12%   |
| Intel Volume Management Device NVMe RAID Controller                            | 110       | 3.45%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 99        | 3.11%   |
| Samsung NVMe SSD Controller 980                                                | 98        | 3.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 79        | 2.48%   |
| AMD 400 Series Chipset SATA Controller                                         | 75        | 2.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 74        | 2.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 74        | 2.32%   |
| AMD 500 Series Chipset SATA Controller                                         | 71        | 2.23%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 70        | 2.2%    |
| Micron Non-Volatile memory controller                                          | 66        | 2.07%   |
| SanDisk Non-Volatile memory controller                                         | 54        | 1.69%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 53        | 1.66%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 53        | 1.66%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 49        | 1.54%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 45        | 1.41%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 44        | 1.38%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 43        | 1.35%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 41        | 1.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 41        | 1.29%   |
| Intel Comet Lake SATA AHCI Controller                                          | 39        | 1.22%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 39        | 1.22%   |
| Intel Tiger Lake-LP SATA Controller                                            | 38        | 1.19%   |
| Phison E12 NVMe Controller                                                     | 36        | 1.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 35        | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 32        | 1%      |
| Intel Non-Volatile memory controller                                           | 30        | 0.94%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 30        | 0.94%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 29        | 0.91%   |
| Intel SSD 660P Series                                                          | 29        | 0.91%   |
| Intel SATA Controller [RAID mode]                                              | 28        | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 26        | 0.82%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 26        | 0.82%   |
| Kingston Company Company Non-Volatile memory controller                        | 25        | 0.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 25        | 0.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 24        | 0.75%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 24        | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 24        | 0.75%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 23        | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1351      | 46.91%  |
| NVMe | 1195      | 41.49%  |
| RAID | 234       | 8.13%   |
| IDE  | 93        | 3.23%   |
| SAS  | 4         | 0.14%   |
| SCSI | 3         | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 1426      | 69.16%  |
| AMD     | 632       | 30.65%  |
| ARM     | 2         | 0.1%    |
| Unknown | 2         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 52        | 2.52%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 52        | 2.52%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 33        | 1.6%    |
| AMD Ryzen 5 3600 6-Core Processor             | 30        | 1.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 29        | 1.41%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 29        | 1.41%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 23        | 1.11%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 23        | 1.11%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 22        | 1.07%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 22        | 1.07%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 21        | 1.02%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 21        | 1.02%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 19        | 0.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 19        | 0.92%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 19        | 0.92%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 18        | 0.87%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 18        | 0.87%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 17        | 0.82%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 16        | 0.78%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 15        | 0.73%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 15        | 0.73%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 15        | 0.73%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 15        | 0.73%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 15        | 0.73%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 0.68%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 14        | 0.68%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 14        | 0.68%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 13        | 0.63%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 13        | 0.63%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 13        | 0.63%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 12        | 0.58%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 12        | 0.58%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 12        | 0.58%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 12        | 0.58%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 12        | 0.58%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 12        | 0.58%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 11        | 0.53%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 11        | 0.53%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 11        | 0.53%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 11        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 421       | 20.41%  |
| Intel Core i7                  | 420       | 20.36%  |
| Other                          | 273       | 13.23%  |
| AMD Ryzen 5                    | 231       | 11.2%   |
| AMD Ryzen 7                    | 177       | 8.58%   |
| Intel Core i3                  | 100       | 4.85%   |
| AMD Ryzen 9                    | 86        | 4.17%   |
| Intel Celeron                  | 53        | 2.57%   |
| Intel Xeon                     | 38        | 1.84%   |
| Intel Core 2 Duo               | 32        | 1.55%   |
| Intel Core i9                  | 22        | 1.07%   |
| Intel Atom                     | 22        | 1.07%   |
| AMD Ryzen 7 PRO                | 21        | 1.02%   |
| Intel Pentium                  | 20        | 0.97%   |
| AMD Ryzen 3                    | 17        | 0.82%   |
| AMD FX                         | 17        | 0.82%   |
| AMD A10                        | 13        | 0.63%   |
| AMD Ryzen 5 PRO                | 11        | 0.53%   |
| Intel Pentium Silver           | 10        | 0.48%   |
| AMD A6                         | 9         | 0.44%   |
| Intel Core 2 Quad              | 8         | 0.39%   |
| AMD A8                         | 7         | 0.34%   |
| AMD Phenom II X4               | 5         | 0.24%   |
| AMD A4                         | 5         | 0.24%   |
| Intel Pentium Gold             | 3         | 0.15%   |
| Intel Pentium Dual-Core        | 3         | 0.15%   |
| Intel Genuine                  | 3         | 0.15%   |
| AMD Phenom II X2               | 3         | 0.15%   |
| AMD E1                         | 3         | 0.15%   |
| Intel Core m3                  | 2         | 0.1%    |
| Intel Core 2                   | 2         | 0.1%    |
| AMD PRO A10                    | 2         | 0.1%    |
| AMD Phenom II X6               | 2         | 0.1%    |
| AMD Opteron                    | 2         | 0.1%    |
| AMD Athlon Dual Core           | 2         | 0.1%    |
| AMD Athlon 64 X2               | 2         | 0.1%    |
| AMD Athlon                     | 2         | 0.1%    |
| Intel Core m5                  | 1         | 0.05%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.05%   |
| AMD Turion 64 X2 Mobile        | 1         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 785       | 38.05%  |
| 2       | 502       | 24.33%  |
| 6       | 336       | 16.29%  |
| 8       | 279       | 13.52%  |
| 12      | 75        | 3.64%   |
| 16      | 26        | 1.26%   |
| 10      | 22        | 1.07%   |
| 14      | 20        | 0.97%   |
| 3       | 8         | 0.39%   |
| 1       | 5         | 0.24%   |
| Unknown | 3         | 0.15%   |
| 20      | 1         | 0.05%   |
| 18      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2049      | 99.37%  |
| 2       | 10        | 0.48%   |
| Unknown | 3         | 0.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1704      | 82.6%   |
| 1       | 356       | 17.26%  |
| Unknown | 3         | 0.15%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2061      | 99.95%  |
| 64-bit         | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806c1    | 140       | 6.76%   |
| 0x306a9    | 95        | 4.59%   |
| Unknown    | 89        | 4.3%    |
| 0x306c3    | 85        | 4.11%   |
| 0x0a50000c | 84        | 4.06%   |
| 0x906ea    | 77        | 3.72%   |
| 0x806ea    | 76        | 3.67%   |
| 0x206a7    | 76        | 3.67%   |
| 0x806ec    | 74        | 3.57%   |
| 0x506e3    | 61        | 2.95%   |
| 0x806e9    | 60        | 2.9%    |
| 0x08701021 | 58        | 2.8%    |
| 0x40651    | 47        | 2.27%   |
| 0x906e9    | 45        | 2.17%   |
| 0x08600106 | 45        | 2.17%   |
| 0x08108109 | 45        | 2.17%   |
| 0x0a201016 | 38        | 1.84%   |
| 0x08608103 | 38        | 1.84%   |
| 0xa0652    | 37        | 1.79%   |
| 0x406e3    | 37        | 1.79%   |
| 0x906a3    | 35        | 1.69%   |
| 0x706e5    | 34        | 1.64%   |
| 0x306d4    | 33        | 1.59%   |
| 0x0800820d | 28        | 1.35%   |
| 0x1067a    | 25        | 1.21%   |
| 0x806d1    | 23        | 1.11%   |
| 0x90672    | 22        | 1.06%   |
| 0xa0653    | 20        | 0.97%   |
| 0x706a8    | 19        | 0.92%   |
| 0xa0655    | 18        | 0.87%   |
| 0x0a404101 | 18        | 0.87%   |
| 0x906ed    | 17        | 0.82%   |
| 0x806eb    | 15        | 0.72%   |
| 0x20655    | 15        | 0.72%   |
| 0x08600104 | 15        | 0.72%   |
| 0x08108102 | 15        | 0.72%   |
| 0x0a404102 | 14        | 0.68%   |
| 0x806c2    | 13        | 0.63%   |
| 0x506c9    | 12        | 0.58%   |
| 0x406c4    | 12        | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 389       | 18.85%  |
| Zen 3            | 190       | 9.21%   |
| TigerLake        | 157       | 7.61%   |
| Haswell          | 151       | 7.32%   |
| Zen 2            | 143       | 6.93%   |
| Skylake          | 107       | 5.18%   |
| IvyBridge        | 103       | 4.99%   |
| Zen+             | 96        | 4.65%   |
| Unknown          | 96        | 4.65%   |
| SandyBridge      | 86        | 4.17%   |
| CometLake        | 82        | 3.97%   |
| Icelake          | 70        | 3.39%   |
| Alderlake Hybrid | 69        | 3.34%   |
| Penryn           | 40        | 1.94%   |
| Zen              | 38        | 1.84%   |
| Broadwell        | 38        | 1.84%   |
| Silvermont       | 31        | 1.5%    |
| Westmere         | 28        | 1.36%   |
| Goldmont plus    | 27        | 1.31%   |
| Piledriver       | 20        | 0.97%   |
| Excavator        | 18        | 0.87%   |
| K10              | 16        | 0.78%   |
| Goldmont         | 13        | 0.63%   |
| Tremont          | 8         | 0.39%   |
| Core             | 8         | 0.39%   |
| Nehalem          | 6         | 0.29%   |
| K8 Hammer        | 6         | 0.29%   |
| Jaguar           | 6         | 0.29%   |
| Bulldozer        | 5         | 0.24%   |
| Bonnell          | 5         | 0.24%   |
| Steamroller      | 4         | 0.19%   |
| Puma             | 4         | 0.19%   |
| K10 Llano        | 2         | 0.1%    |
| K8 & K10 hybrid  | 1         | 0.05%   |
| Bobcat           | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1151      | 45.4%   |
| Nvidia                     | 706       | 27.85%  |
| AMD                        | 672       | 26.51%  |
| Matrox Electronics Systems | 5         | 0.2%    |
| ASPEED Technology          | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 143       | 5.52%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 86        | 3.32%   |
| Intel UHD Graphics 620                                                                   | 76        | 2.93%   |
| AMD Renoir                                                                               | 74        | 2.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 63        | 2.43%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 60        | 2.32%   |
| Intel HD Graphics 620                                                                    | 58        | 2.24%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 58        | 2.24%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 55        | 2.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 50        | 1.93%   |
| AMD Lucienne                                                                             | 50        | 1.93%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 47        | 1.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 46        | 1.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 43        | 1.66%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 37        | 1.43%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 37        | 1.43%   |
| Intel HD Graphics 530                                                                    | 36        | 1.39%   |
| AMD Rembrandt [Radeon 680M]                                                              | 33        | 1.27%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 32        | 1.24%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 31        | 1.2%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 30        | 1.16%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 29        | 1.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 28        | 1.08%   |
| Intel HD Graphics 630                                                                    | 27        | 1.04%   |
| Intel HD Graphics 5500                                                                   | 27        | 1.04%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 23        | 0.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 23        | 0.89%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 22        | 0.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 20        | 0.77%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 20        | 0.77%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 18        | 0.69%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 18        | 0.69%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 18        | 0.69%   |
| Intel Core Processor Integrated Graphics Controller                                      | 18        | 0.69%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 18        | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 18        | 0.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 18        | 0.69%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 17        | 0.66%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 17        | 0.66%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 17        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 757       | 36.64%  |
| 1 x AMD         | 510       | 24.69%  |
| Intel + Nvidia  | 319       | 15.44%  |
| 1 x Nvidia      | 303       | 14.67%  |
| AMD + Nvidia    | 76        | 3.68%   |
| Intel + AMD     | 44        | 2.13%   |
| 2 x AMD         | 40        | 1.94%   |
| Other           | 4         | 0.19%   |
| 2 x Nvidia      | 4         | 0.19%   |
| 2 x Intel       | 2         | 0.1%    |
| Nvidia + Matrox | 2         | 0.1%    |
| 1 x Matrox      | 2         | 0.1%    |
| Intel + 2 x AMD | 1         | 0.05%   |
| 1 x ASPEED      | 1         | 0.05%   |
| AMD + Matrox    | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1668      | 80.46%  |
| Proprietary | 361       | 17.41%  |
| Unknown     | 44        | 2.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1048      | 50.34%  |
| 1.01-2.0   | 259       | 12.44%  |
| 0.01-0.5   | 233       | 11.19%  |
| 3.01-4.0   | 177       | 8.5%    |
| 7.01-8.0   | 137       | 6.58%   |
| 0.51-1.0   | 109       | 5.24%   |
| 5.01-6.0   | 55        | 2.64%   |
| 8.01-16.0  | 55        | 2.64%   |
| 2.01-3.0   | 9         | 0.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 308       | 12.68%  |
| BOE                     | 290       | 11.94%  |
| Chimei Innolux          | 213       | 8.77%   |
| Samsung Electronics     | 211       | 8.69%   |
| LG Display              | 191       | 7.86%   |
| Goldstar                | 163       | 6.71%   |
| Dell                    | 153       | 6.3%    |
| Hewlett-Packard         | 70        | 2.88%   |
| Sharp                   | 69        | 2.84%   |
| Acer                    | 65        | 2.68%   |
| BenQ                    | 63        | 2.59%   |
| AOC                     | 62        | 2.55%   |
| Philips                 | 58        | 2.39%   |
| Lenovo                  | 50        | 2.06%   |
| Apple                   | 50        | 2.06%   |
| Ancor Communications    | 38        | 1.56%   |
| PANDA                   | 34        | 1.4%    |
| ViewSonic               | 28        | 1.15%   |
| CSO                     | 26        | 1.07%   |
| Iiyama                  | 22        | 0.91%   |
| InfoVision              | 21        | 0.86%   |
| ASUSTek Computer        | 21        | 0.86%   |
| MSI                     | 17        | 0.7%    |
| Chi Mei Optoelectronics | 15        | 0.62%   |
| Gigabyte Technology     | 12        | 0.49%   |
| TMX                     | 11        | 0.45%   |
| Sceptre Tech            | 11        | 0.45%   |
| Vizio                   | 9         | 0.37%   |
| Eizo                    | 8         | 0.33%   |
| Sony                    | 7         | 0.29%   |
| Unknown                 | 6         | 0.25%   |
| Mi                      | 6         | 0.25%   |
| HUAWEI                  | 5         | 0.21%   |
| HannStar                | 5         | 0.21%   |
| Toshiba                 | 4         | 0.16%   |
| Panasonic               | 4         | 0.16%   |
| NEC Computers           | 4         | 0.16%   |
| Fujitsu Siemens         | 4         | 0.16%   |
| RTK                     | 3         | 0.12%   |
| ONN                     | 3         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch  | 17        | 0.68%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch    | 15        | 0.6%    |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch             | 13        | 0.52%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 12        | 0.48%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch | 11        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch  | 11        | 0.44%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch             | 11        | 0.44%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                | 10        | 0.4%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch           | 9         | 0.36%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch             | 9         | 0.36%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch    | 9         | 0.36%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch       | 8         | 0.32%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 8         | 0.32%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch             | 8         | 0.32%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch  | 8         | 0.32%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch    | 8         | 0.32%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch      | 7         | 0.28%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch           | 7         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch  | 7         | 0.28%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch  | 7         | 0.28%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch  | 7         | 0.28%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch             | 7         | 0.28%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch             | 7         | 0.28%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch    | 7         | 0.28%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch    | 7         | 0.28%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch    | 7         | 0.28%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch         | 6         | 0.24%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch | 6         | 0.24%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch          | 6         | 0.24%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch      | 6         | 0.24%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch  | 6         | 0.24%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch  | 6         | 0.24%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch             | 6         | 0.24%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch             | 6         | 0.24%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch              | 6         | 0.24%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch    | 6         | 0.24%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch    | 6         | 0.24%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                  | 6         | 0.24%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch           | 5         | 0.2%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch | 5         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1146      | 50.15%  |
| 1366x768 (WXGA)    | 267       | 11.68%  |
| 3840x2160 (4K)     | 193       | 8.45%   |
| 2560x1440 (QHD)    | 167       | 7.31%   |
| 1920x1200 (WUXGA)  | 74        | 3.24%   |
| 3440x1440          | 60        | 2.63%   |
| 1600x900 (HD+)     | 59        | 2.58%   |
| 2560x1600          | 44        | 1.93%   |
| 1280x1024 (SXGA)   | 31        | 1.36%   |
| 2560x1080          | 29        | 1.27%   |
| 1440x900 (WXGA+)   | 25        | 1.09%   |
| 1680x1050 (WSXGA+) | 20        | 0.88%   |
| 3840x2400          | 19        | 0.83%   |
| 2880x1800          | 18        | 0.79%   |
| 1280x800 (WXGA)    | 18        | 0.79%   |
| 2256x1504          | 14        | 0.61%   |
| 2160x1440          | 11        | 0.48%   |
| 1360x768           | 11        | 0.48%   |
| 2736x1824          | 10        | 0.44%   |
| 1600x1200          | 7         | 0.31%   |
| 2288x1287          | 6         | 0.26%   |
| 3840x1080          | 5         | 0.22%   |
| 3456x2160          | 5         | 0.22%   |
| 1920x540           | 5         | 0.22%   |
| 3840x1600          | 4         | 0.18%   |
| 3200x2000          | 4         | 0.18%   |
| 3000x2000          | 4         | 0.18%   |
| 2240x1400          | 4         | 0.18%   |
| 1920x1280          | 4         | 0.18%   |
| 3072x1920          | 3         | 0.13%   |
| 2520x1680          | 3         | 0.13%   |
| 1024x768 (XGA)     | 3         | 0.13%   |
| 3200x1800 (QHD+)   | 2         | 0.09%   |
| 2560x2880          | 1         | 0.04%   |
| 2400x1600          | 1         | 0.04%   |
| 2304x1440          | 1         | 0.04%   |
| 2200x1650          | 1         | 0.04%   |
| 2160x1200          | 1         | 0.04%   |
| 1920x550           | 1         | 0.04%   |
| 1640x2048          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 576       | 23.56%  |
| 13      | 289       | 11.82%  |
| 14      | 266       | 10.88%  |
| 27      | 250       | 10.22%  |
| 24      | 182       | 7.44%   |
| 23      | 144       | 5.89%   |
| 21      | 140       | 5.73%   |
| 17      | 93        | 3.8%    |
| 34      | 76        | 3.11%   |
| 31      | 76        | 3.11%   |
| 12      | 44        | 1.8%    |
| 18      | 35        | 1.43%   |
| 16      | 35        | 1.43%   |
| 19      | 27        | 1.1%    |
| 20      | 25        | 1.02%   |
| 22      | 19        | 0.78%   |
| Unknown | 18        | 0.74%   |
| 11      | 17        | 0.7%    |
| 32      | 14        | 0.57%   |
| 40      | 13        | 0.53%   |
| 84      | 11        | 0.45%   |
| 72      | 8         | 0.33%   |
| 25      | 8         | 0.33%   |
| 26      | 7         | 0.29%   |
| 142     | 6         | 0.25%   |
| 54      | 6         | 0.25%   |
| 48      | 6         | 0.25%   |
| 42      | 6         | 0.25%   |
| 29      | 6         | 0.25%   |
| 52      | 5         | 0.2%    |
| 37      | 5         | 0.2%    |
| 35      | 5         | 0.2%    |
| 10      | 5         | 0.2%    |
| 69      | 3         | 0.12%   |
| 39      | 3         | 0.12%   |
| 100     | 2         | 0.08%   |
| 75      | 2         | 0.08%   |
| 58      | 2         | 0.08%   |
| 46      | 2         | 0.08%   |
| 55      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1009      | 42.06%  |
| 501-600        | 524       | 21.84%  |
| 401-500        | 225       | 9.38%   |
| 201-300        | 219       | 9.13%   |
| 601-700        | 114       | 4.75%   |
| 351-400        | 109       | 4.54%   |
| 701-800        | 91        | 3.79%   |
| 801-900        | 26        | 1.08%   |
| 1501-2000      | 24        | 1%      |
| 1001-1500      | 23        | 0.96%   |
| Unknown        | 18        | 0.75%   |
| 901-1000       | 9         | 0.38%   |
| More than 2000 | 8         | 0.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1670      | 78.55%  |
| 16/10   | 254       | 11.95%  |
| 21/9    | 90        | 4.23%   |
| 3/2     | 47        | 2.21%   |
| 5/4     | 28        | 1.32%   |
| 4/3     | 12        | 0.56%   |
| 32/9    | 7         | 0.33%   |
| 1.00    | 6         | 0.28%   |
| Unknown | 6         | 0.28%   |
| 6/5     | 3         | 0.14%   |
| 1.96    | 1         | 0.05%   |
| 0.89    | 1         | 0.05%   |
| 0.80    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 578       | 23.89%  |
| 81-90          | 436       | 18.02%  |
| 201-250        | 372       | 15.38%  |
| 301-350        | 257       | 10.62%  |
| 351-500        | 175       | 7.23%   |
| 71-80          | 124       | 5.13%   |
| 151-200        | 98        | 4.05%   |
| 121-130        | 75        | 3.1%    |
| 251-300        | 62        | 2.56%   |
| More than 1000 | 48        | 1.98%   |
| 141-150        | 41        | 1.69%   |
| 501-1000       | 36        | 1.49%   |
| 61-70          | 34        | 1.41%   |
| 111-120        | 33        | 1.36%   |
| 51-60          | 18        | 0.74%   |
| Unknown        | 18        | 0.74%   |
| 131-140        | 6         | 0.25%   |
| 41-50          | 4         | 0.17%   |
| 91-100         | 4         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 811       | 34.36%  |
| 51-100        | 633       | 26.82%  |
| 101-120       | 496       | 21.02%  |
| 161-240       | 268       | 11.36%  |
| More than 240 | 95        | 4.03%   |
| 1-50          | 39        | 1.65%   |
| Unknown       | 18        | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1554      | 74.28%  |
| 2     | 420       | 20.08%  |
| 3     | 54        | 2.58%   |
| 0     | 54        | 2.58%   |
| 4     | 9         | 0.43%   |
| 5     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1191      | 39.18%  |
| Realtek Semiconductor             | 1081      | 35.56%  |
| Qualcomm Atheros                  | 219       | 7.2%    |
| Broadcom                          | 110       | 3.62%   |
| MediaTek                          | 93        | 3.06%   |
| TP-Link                           | 42        | 1.38%   |
| Broadcom Limited                  | 22        | 0.72%   |
| Ralink                            | 18        | 0.59%   |
| Ralink Technology                 | 15        | 0.49%   |
| Lenovo                            | 15        | 0.49%   |
| ASIX Electronics                  | 14        | 0.46%   |
| Nvidia                            | 13        | 0.43%   |
| Microsoft                         | 13        | 0.43%   |
| Marvell Technology Group          | 13        | 0.43%   |
| DisplayLink                       | 13        | 0.43%   |
| Samsung Electronics               | 11        | 0.36%   |
| Qualcomm Atheros Communications   | 11        | 0.36%   |
| Xiaomi                            | 10        | 0.33%   |
| Sierra Wireless                   | 10        | 0.33%   |
| Qualcomm                          | 10        | 0.33%   |
| Huawei Technologies               | 8         | 0.26%   |
| D-Link                            | 7         | 0.23%   |
| Aquantia                          | 7         | 0.23%   |
| Apple                             | 7         | 0.23%   |
| ASUSTek Computer                  | 6         | 0.2%    |
| Hewlett-Packard                   | 5         | 0.16%   |
| Ericsson Business Mobile Networks | 5         | 0.16%   |
| Edimax Technology                 | 5         | 0.16%   |
| Dell                              | 5         | 0.16%   |
| T & A Mobile Phones               | 4         | 0.13%   |
| NetGear                           | 4         | 0.13%   |
| Mellanox Technologies             | 4         | 0.13%   |
| Fibocom                           | 4         | 0.13%   |
| OnePlus Technology (Shenzhen)     | 3         | 0.1%    |
| Microchip Technology              | 3         | 0.1%    |
| Linksys                           | 3         | 0.1%    |
| Google                            | 3         | 0.1%    |
| Belkin Components                 | 3         | 0.1%    |
| OPPO Electronics                  | 2         | 0.07%   |
| Motorola PCS                      | 2         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 665       | 18.4%   |
| Intel Wi-Fi 6 AX200                                               | 173       | 4.79%   |
| Intel Wi-Fi 6 AX201                                               | 122       | 3.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 89        | 2.46%   |
| Realtek RTL8125 2.5GbE Controller                                 | 88        | 2.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 88        | 2.43%   |
| Intel Wireless 8265 / 8275                                        | 81        | 2.24%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 68        | 1.88%   |
| Intel I211 Gigabit Network Connection                             | 68        | 1.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 64        | 1.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 62        | 1.72%   |
| Intel Ethernet Controller I225-V                                  | 57        | 1.58%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 53        | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 52        | 1.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 49        | 1.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 46        | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 43        | 1.19%   |
| Intel Wireless 7265                                               | 42        | 1.16%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 39        | 1.08%   |
| Intel Wireless 8260                                               | 38        | 1.05%   |
| Intel Ethernet Connection (2) I219-V                              | 36        | 1%      |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 35        | 0.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 33        | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 29        | 0.8%    |
| Intel Wireless 7260                                               | 29        | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 29        | 0.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 29        | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 28        | 0.77%   |
| Intel Wireless-AC 9260                                            | 28        | 0.77%   |
| Intel Wireless 3165                                               | 27        | 0.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 27        | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 23        | 0.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 23        | 0.64%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 22        | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                             | 21        | 0.58%   |
| Intel Centrino Ultimate-N 6300                                    | 21        | 0.58%   |
| Intel Ethernet Connection (7) I219-V                              | 20        | 0.55%   |
| Intel Ethernet Connection (4) I219-LM                             | 20        | 0.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 20        | 0.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 19        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 988       | 54.35%  |
| Realtek Semiconductor             | 289       | 15.9%   |
| Qualcomm Atheros                  | 187       | 10.29%  |
| MediaTek                          | 92        | 5.06%   |
| Broadcom                          | 85        | 4.68%   |
| TP-Link                           | 39        | 2.15%   |
| Broadcom Limited                  | 19        | 1.05%   |
| Ralink                            | 18        | 0.99%   |
| Ralink Technology                 | 15        | 0.83%   |
| Microsoft                         | 13        | 0.72%   |
| Qualcomm Atheros Communications   | 11        | 0.61%   |
| Sierra Wireless                   | 10        | 0.55%   |
| Qualcomm                          | 8         | 0.44%   |
| Marvell Technology Group          | 8         | 0.44%   |
| Edimax Technology                 | 5         | 0.28%   |
| ASUSTek Computer                  | 5         | 0.28%   |
| Fibocom                           | 4         | 0.22%   |
| D-Link                            | 4         | 0.22%   |
| NetGear                           | 3         | 0.17%   |
| Linksys                           | 3         | 0.17%   |
| Dell                              | 3         | 0.17%   |
| Belkin Components                 | 3         | 0.17%   |
| Sitecom Europe                    | 1         | 0.06%   |
| PLANEX                            | 1         | 0.06%   |
| IMC Networks                      | 1         | 0.06%   |
| Ericsson Business Mobile Networks | 1         | 0.06%   |
| D-Link System                     | 1         | 0.06%   |
| BUFFALO                           | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 173       | 9.5%    |
| Intel Wi-Fi 6 AX201                                            | 122       | 6.7%    |
| Intel Wireless 8265 / 8275                                     | 81        | 4.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 68        | 3.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 62        | 3.4%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 53        | 2.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 52        | 2.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 49        | 2.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 46        | 2.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 43        | 2.36%   |
| Intel Wireless 7265                                            | 42        | 2.31%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 39        | 2.14%   |
| Intel Wireless 8260                                            | 38        | 2.09%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 35        | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 33        | 1.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 29        | 1.59%   |
| Intel Wireless 7260                                            | 29        | 1.59%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 29        | 1.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 29        | 1.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 28        | 1.54%   |
| Intel Wireless-AC 9260                                         | 28        | 1.54%   |
| Intel Wireless 3165                                            | 27        | 1.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 27        | 1.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 23        | 1.26%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 23        | 1.26%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 22        | 1.21%   |
| Intel Centrino Ultimate-N 6300                                 | 21        | 1.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 20        | 1.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 19        | 1.04%   |
| Intel Wireless 3160                                            | 16        | 0.88%   |
| MediaTek WLAN controller                                       | 14        | 0.77%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 13        | 0.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 13        | 0.71%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 13        | 0.71%   |
| Realtek 802.11ac NIC                                           | 12        | 0.66%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 12        | 0.66%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 12        | 0.66%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 12        | 0.66%   |
| Broadcom BCM43142 802.11b/g/n                                  | 12        | 0.66%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 11        | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 950       | 55.26%  |
| Intel                             | 536       | 31.18%  |
| Qualcomm Atheros                  | 50        | 2.91%   |
| Broadcom                          | 43        | 2.5%    |
| Lenovo                            | 14        | 0.81%   |
| ASIX Electronics                  | 14        | 0.81%   |
| Nvidia                            | 13        | 0.76%   |
| DisplayLink                       | 13        | 0.76%   |
| Samsung Electronics               | 11        | 0.64%   |
| Xiaomi                            | 10        | 0.58%   |
| Aquantia                          | 7         | 0.41%   |
| Apple                             | 7         | 0.41%   |
| Huawei Technologies               | 6         | 0.35%   |
| Marvell Technology Group          | 5         | 0.29%   |
| TP-Link                           | 4         | 0.23%   |
| Mellanox Technologies             | 3         | 0.17%   |
| Google                            | 3         | 0.17%   |
| D-Link                            | 3         | 0.17%   |
| Broadcom Limited                  | 3         | 0.17%   |
| Qualcomm                          | 2         | 0.12%   |
| OPPO Electronics                  | 2         | 0.12%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.12%   |
| Motorola PCS                      | 2         | 0.12%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.06%   |
| T & A Mobile Phones               | 1         | 0.06%   |
| Sundance Technology Inc / IC Plus | 1         | 0.06%   |
| QNAP System                       | 1         | 0.06%   |
| NetGear                           | 1         | 0.06%   |
| MosChip Semiconductor             | 1         | 0.06%   |
| Microchip Technology              | 1         | 0.06%   |
| MediaTek                          | 1         | 0.06%   |
| LG Electronics                    | 1         | 0.06%   |
| Insyde Software                   | 1         | 0.06%   |
| ICS Advent                        | 1         | 0.06%   |
| HMD Global                        | 1         | 0.06%   |
| Hewlett-Packard                   | 1         | 0.06%   |
| Davicom Semiconductor             | 1         | 0.06%   |
| ASUSTek Computer                  | 1         | 0.06%   |
| ADMtek                            | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 665       | 37.78%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 89        | 5.06%   |
| Realtek RTL8125 2.5GbE Controller                                 | 88        | 5%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 88        | 5%      |
| Intel I211 Gigabit Network Connection                             | 68        | 3.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 64        | 3.64%   |
| Intel Ethernet Controller I225-V                                  | 57        | 3.24%   |
| Intel Ethernet Connection (2) I219-V                              | 36        | 2.05%   |
| Intel Ethernet Connection (2) I219-LM                             | 21        | 1.19%   |
| Intel Ethernet Connection (7) I219-V                              | 20        | 1.14%   |
| Intel Ethernet Connection (4) I219-LM                             | 20        | 1.14%   |
| Intel Ethernet Connection I217-LM                                 | 18        | 1.02%   |
| Intel Ethernet Connection (4) I219-V                              | 18        | 1.02%   |
| Intel Ethernet Connection (13) I219-V                             | 16        | 0.91%   |
| Intel Ethernet Connection (10) I219-V                             | 15        | 0.85%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 14        | 0.8%    |
| Intel Ethernet Connection (7) I219-LM                             | 14        | 0.8%    |
| ASIX AX88179 Gigabit Ethernet                                     | 14        | 0.8%    |
| Intel Ethernet Connection (2) I218-V                              | 12        | 0.68%   |
| Intel Ethernet Connection I219-LM                                 | 11        | 0.63%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 11        | 0.63%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 10        | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 9         | 0.51%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 9         | 0.51%   |
| Realtek Killer E3000 2.5GbE Controller                            | 9         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9         | 0.51%   |
| Intel Ethernet Connection (6) I219-V                              | 9         | 0.51%   |
| Intel Ethernet Connection (5) I219-LM                             | 9         | 0.51%   |
| Intel Ethernet Connection (11) I219-LM                            | 9         | 0.51%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 9         | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 0.45%   |
| Intel 82579V Gigabit Network Connection                           | 8         | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 0.4%    |
| Nvidia MCP79 Ethernet                                             | 7         | 0.4%    |
| Intel Ethernet Connection (3) I218-LM                             | 7         | 0.4%    |
| Intel 82577LM Gigabit Network Connection                          | 7         | 0.4%    |
| Intel 82574L Gigabit Network Connection                           | 7         | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 0.34%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 6         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1743      | 52.08%  |
| Ethernet | 1573      | 47%     |
| Modem    | 25        | 0.75%   |
| Unknown  | 6         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1400      | 64.81%  |
| Ethernet | 759       | 35.14%  |
| Modem    | 1         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1057      | 51.24%  |
| 1     | 909       | 44.06%  |
| 3     | 61        | 2.96%   |
| 0     | 31        | 1.5%    |
| 4     | 5         | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1537      | 73.97%  |
| Yes  | 541       | 26.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 868       | 55.89%  |
| Realtek Semiconductor           | 181       | 11.65%  |
| Qualcomm Atheros Communications | 96        | 6.18%   |
| IMC Networks                    | 67        | 4.31%   |
| Cambridge Silicon Radio         | 62        | 3.99%   |
| Broadcom                        | 53        | 3.41%   |
| Foxconn / Hon Hai               | 52        | 3.35%   |
| Apple                           | 48        | 3.09%   |
| Lite-On Technology              | 35        | 2.25%   |
| ASUSTek Computer                | 19        | 1.22%   |
| MediaTek                        | 12        | 0.77%   |
| Realtek                         | 11        | 0.71%   |
| Marvell Semiconductor           | 9         | 0.58%   |
| TP-Link                         | 8         | 0.52%   |
| Ralink                          | 7         | 0.45%   |
| Toshiba                         | 6         | 0.39%   |
| Hewlett-Packard                 | 5         | 0.32%   |
| Dell                            | 4         | 0.26%   |
| Opticis                         | 2         | 0.13%   |
| Edimax Technology               | 2         | 0.13%   |
| USI                             | 1         | 0.06%   |
| SIN                             | 1         | 0.06%   |
| Qcom                            | 1         | 0.06%   |
| Micro Star International        | 1         | 0.06%   |
| HTC (High Tech Computer)        | 1         | 0.06%   |
| BUFFALO                         | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 239       | 15.38%  |
| Intel Bluetooth wireless interface                  | 218       | 14.03%  |
| Intel AX200 Bluetooth                               | 166       | 10.68%  |
| Realtek Bluetooth Radio                             | 128       | 8.24%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 114       | 7.34%   |
| Intel AX210 Bluetooth                               | 66        | 4.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 62        | 3.99%   |
| Qualcomm Atheros  Bluetooth Device                  | 48        | 3.09%   |
| IMC Networks Wireless_Device                        | 37        | 2.38%   |
| Realtek  Bluetooth 4.2 Adapter                      | 33        | 2.12%   |
| Foxconn / Hon Hai Wireless_Device                   | 33        | 2.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 27        | 1.74%   |
| Intel Wireless-AC 3168 Bluetooth                    | 25        | 1.61%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 22        | 1.42%   |
| Apple Bluetooth Host Controller                     | 22        | 1.42%   |
| Apple Bluetooth USB Host Controller                 | 19        | 1.22%   |
| Lite-On Bluetooth Device                            | 18        | 1.16%   |
| IMC Networks Bluetooth Radio                        | 15        | 0.97%   |
| MediaTek Wireless_Device                            | 12        | 0.77%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 12        | 0.77%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 11        | 0.71%   |
| Realtek Bluetooth Radio                             | 11        | 0.71%   |
| Broadcom BCM2045B (BDC-2.1)                         | 11        | 0.71%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 0.64%   |
| TP-Link TPuLink UB500 Adapter                       | 8         | 0.51%   |
| Foxconn / Hon Hai Bluetooth Device                  | 8         | 0.51%   |
| Ralink RT3290 Bluetooth                             | 7         | 0.45%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 7         | 0.45%   |
| Marvell Bluetooth and Wireless LAN Composite        | 7         | 0.45%   |
| Lite-On Wireless_Device                             | 7         | 0.45%   |
| IMC Networks Bluetooth Device                       | 7         | 0.45%   |
| Broadcom HP Portable SoftSailing                    | 7         | 0.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 6         | 0.39%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 6         | 0.39%   |
| Realtek RTL8723B Bluetooth                          | 5         | 0.32%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 0.32%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.32%   |
| ASUS Bluetooth Radio                                | 5         | 0.32%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.26%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1386      | 44.8%   |
| AMD                                  | 730       | 23.59%  |
| Nvidia                               | 513       | 16.58%  |
| C-Media Electronics                  | 65        | 2.1%    |
| Logitech                             | 32        | 1.03%   |
| Realtek Semiconductor                | 21        | 0.68%   |
| Lenovo                               | 21        | 0.68%   |
| GN Netcom                            | 16        | 0.52%   |
| Creative Technology                  | 15        | 0.48%   |
| Texas Instruments                    | 14        | 0.45%   |
| JMTek                                | 14        | 0.45%   |
| Corsair                              | 14        | 0.45%   |
| Creative Labs                        | 13        | 0.42%   |
| Kingston Technology                  | 12        | 0.39%   |
| SteelSeries ApS                      | 11        | 0.36%   |
| Samson Technologies                  | 11        | 0.36%   |
| Plantronics                          | 11        | 0.36%   |
| XMOS                                 | 10        | 0.32%   |
| Razer USA                            | 10        | 0.32%   |
| Generalplus Technology               | 10        | 0.32%   |
| Focusrite-Novation                   | 10        | 0.32%   |
| ASUSTek Computer                     | 9         | 0.29%   |
| Hewlett-Packard                      | 8         | 0.26%   |
| Sony                                 | 7         | 0.23%   |
| Conexant Systems                     | 6         | 0.19%   |
| Micro Star International             | 5         | 0.16%   |
| Blue Microphones                     | 5         | 0.16%   |
| Apple                                | 5         | 0.16%   |
| Sennheiser Communications            | 4         | 0.13%   |
| PreSonus Audio Electronics           | 4         | 0.13%   |
| FiiO Electronics Technology          | 4         | 0.13%   |
| Dell                                 | 4         | 0.13%   |
| Yamaha                               | 3         | 0.1%    |
| Thesycon Systemsoftware & Consulting | 3         | 0.1%    |
| Samsung Electronics                  | 3         | 0.1%    |
| Elgato Systems                       | 3         | 0.1%    |
| DSEA A/S                             | 3         | 0.1%    |
| ZOOM                                 | 2         | 0.06%   |
| USB MICROPHONE                       | 2         | 0.06%   |
| Tenx Technology                      | 2         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 340       | 9.04%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 212       | 5.63%   |
| Intel Sunrise Point-LP HD Audio                                            | 180       | 4.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 157       | 4.17%   |
| AMD Starship/Matisse HD Audio Controller                                   | 143       | 3.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 107       | 2.84%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 84        | 2.23%   |
| Intel Cannon Lake PCH cAVS                                                 | 83        | 2.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 81        | 2.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 77        | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 71        | 1.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 64        | 1.7%    |
| Intel Comet Lake PCH cAVS                                                  | 58        | 1.54%   |
| Intel Comet Lake PCH-LP cAVS                                               | 55        | 1.46%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 55        | 1.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 54        | 1.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 50        | 1.33%   |
| Nvidia GP107GL High Definition Audio Controller                            | 49        | 1.3%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 49        | 1.3%    |
| Intel Haswell-ULT HD Audio Controller                                      | 47        | 1.25%   |
| Intel 8 Series HD Audio Controller                                         | 47        | 1.25%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 46        | 1.22%   |
| Nvidia GA104 High Definition Audio Controller                              | 44        | 1.17%   |
| Intel 200 Series PCH HD Audio                                              | 42        | 1.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 39        | 1.04%   |
| Nvidia GA106 High Definition Audio Controller                              | 38        | 1.01%   |
| Nvidia TU116 High Definition Audio Controller                              | 37        | 0.98%   |
| Intel Broadwell-U Audio Controller                                         | 37        | 0.98%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 36        | 0.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 34        | 0.9%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 34        | 0.9%    |
| Intel Alder Lake-S HD Audio Controller                                     | 31        | 0.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 31        | 0.82%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 31        | 0.82%   |
| Nvidia GP106 High Definition Audio Controller                              | 29        | 0.77%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 29        | 0.77%   |
| Nvidia TU106 High Definition Audio Controller                              | 27        | 0.72%   |
| Nvidia GP104 High Definition Audio Controller                              | 27        | 0.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 27        | 0.72%   |
| AMD Navi 10 HDMI Audio                                                     | 27        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 290       | 24.05%  |
| SK hynix                                         | 213       | 17.66%  |
| Micron Technology                                | 160       | 13.27%  |
| Kingston                                         | 119       | 9.87%   |
| Crucial                                          | 84        | 6.97%   |
| Unknown                                          | 65        | 5.39%   |
| Corsair                                          | 54        | 4.48%   |
| G.Skill                                          | 49        | 4.06%   |
| A-DATA Technology                                | 27        | 2.24%   |
| Ramaxel Technology                               | 26        | 2.16%   |
| Patriot                                          | 20        | 1.66%   |
| Unknown (ABCD)                                   | 15        | 1.24%   |
| Team                                             | 15        | 1.24%   |
| Unknown                                          | 12        | 1%      |
| Nanya Technology                                 | 9         | 0.75%   |
| Elpida                                           | 8         | 0.66%   |
| Smart                                            | 7         | 0.58%   |
| Silicon Power                                    | 3         | 0.25%   |
| PNY                                              | 3         | 0.25%   |
| V-GeN                                            | 2         | 0.17%   |
| Goldkey                                          | 2         | 0.17%   |
| ChangXin Memory                                  | 2         | 0.17%   |
| Atermiter                                        | 2         | 0.17%   |
| AMD                                              | 2         | 0.17%   |
| Unknown (0x4E41324D3030314733374455202020202020) | 1         | 0.08%   |
| Unknown (0x4D342037305432393533455A332D43453620) | 1         | 0.08%   |
| Timetec                                          | 1         | 0.08%   |
| Smart Brazil                                     | 1         | 0.08%   |
| Sesame                                           | 1         | 0.08%   |
| Samsung 1                                        | 1         | 0.08%   |
| Qimonda                                          | 1         | 0.08%   |
| PUSKILL                                          | 1         | 0.08%   |
| Neo Forza                                        | 1         | 0.08%   |
| Mushkin                                          | 1         | 0.08%   |
| Mircon                                           | 1         | 0.08%   |
| Kllisre                                          | 1         | 0.08%   |
| Hikvision                                        | 1         | 0.08%   |
| Hewlett-Packard                                  | 1         | 0.08%   |
| GOODRAM                                          | 1         | 0.08%   |
| Exceleram                                        | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 18        | 1.43%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 15        | 1.19%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 1.19%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 14        | 1.11%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 13        | 1.03%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 1.03%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 13        | 1.03%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.95%   |
| Unknown                                                          | 12        | 0.95%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 10        | 0.79%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.79%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 10        | 0.79%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 0.71%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 9         | 0.71%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.64%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.64%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 7         | 0.56%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 6         | 0.48%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.48%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 6         | 0.48%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 6         | 0.48%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 6         | 0.48%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 6         | 0.48%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 6         | 0.48%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 6         | 0.48%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.4%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 0.4%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 5         | 0.4%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.4%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 0.4%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.4%    |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 5         | 0.4%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.4%    |
| Patriot RAM 3200 C16 Series 32GB DIMM DDR4 3266MT/s              | 5         | 0.4%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 4         | 0.32%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 4         | 0.32%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 4         | 0.32%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 4         | 0.32%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 4         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 637       | 61.37%  |
| DDR3    | 222       | 21.39%  |
| LPDDR4  | 73        | 7.03%   |
| LPDDR3  | 34        | 3.28%   |
| Unknown | 22        | 2.12%   |
| DDR5    | 16        | 1.54%   |
| LPDDR5  | 15        | 1.45%   |
| DDR2    | 11        | 1.06%   |
| SDRAM   | 6         | 0.58%   |
| DDR     | 2         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 616       | 58.5%   |
| DIMM         | 283       | 26.88%  |
| Row Of Chips | 145       | 13.77%  |
| Chip         | 5         | 0.47%   |
| RIMM         | 2         | 0.19%   |
| Unknown      | 2         | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 468       | 42.31%  |
| 4096  | 272       | 24.59%  |
| 16384 | 216       | 19.53%  |
| 2048  | 75        | 6.78%   |
| 32768 | 60        | 5.42%   |
| 1024  | 13        | 1.18%   |
| 3072  | 2         | 0.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 302       | 27.4%   |
| 2667    | 168       | 15.25%  |
| 1600    | 164       | 14.88%  |
| 2400    | 67        | 6.08%   |
| 2133    | 64        | 5.81%   |
| 3600    | 43        | 3.9%    |
| 4267    | 38        | 3.45%   |
| 1333    | 30        | 2.72%   |
| 1867    | 27        | 2.45%   |
| 4800    | 19        | 1.72%   |
| 6400    | 17        | 1.54%   |
| 1334    | 16        | 1.45%   |
| 3266    | 15        | 1.36%   |
| 3733    | 11        | 1%      |
| 3466    | 10        | 0.91%   |
| 1067    | 10        | 0.91%   |
| 667     | 8         | 0.73%   |
| Unknown | 8         | 0.73%   |
| 3000    | 7         | 0.64%   |
| 8400    | 6         | 0.54%   |
| 4266    | 6         | 0.54%   |
| 3400    | 6         | 0.54%   |
| 2933    | 6         | 0.54%   |
| 2666    | 6         | 0.54%   |
| 3800    | 5         | 0.45%   |
| 2800    | 5         | 0.45%   |
| 800     | 5         | 0.45%   |
| 3866    | 4         | 0.36%   |
| 1066    | 4         | 0.36%   |
| 3333    | 3         | 0.27%   |
| 400     | 3         | 0.27%   |
| 3100    | 2         | 0.18%   |
| 2048    | 2         | 0.18%   |
| 1866    | 2         | 0.18%   |
| 1800    | 2         | 0.18%   |
| 49926   | 1         | 0.09%   |
| 5200    | 1         | 0.09%   |
| 3666    | 1         | 0.09%   |
| 3467    | 1         | 0.09%   |
| 2733    | 1         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 8         | 23.53%  |
| Brother Industries    | 8         | 23.53%  |
| Canon                 | 7         | 20.59%  |
| Seiko Epson           | 3         | 8.82%   |
| Samsung Electronics   | 2         | 5.88%   |
| Prolific Technology   | 2         | 5.88%   |
| NXP Semiconductors    | 1         | 2.94%   |
| Lexmark International | 1         | 2.94%   |
| Kyocera               | 1         | 2.94%   |
| Graphtec America      | 1         | 2.94%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port        | 2         | 5.88%   |
| Seiko Epson Printer                  | 1         | 2.94%   |
| Seiko Epson L3110 Series             | 1         | 2.94%   |
| Seiko Epson L300 Series              | 1         | 2.94%   |
| Samsung ML-1640 Series Laser Printer | 1         | 2.94%   |
| Samsung M2070 Series                 | 1         | 2.94%   |
| NXP Semiconductors Printer-80        | 1         | 2.94%   |
| Lexmark International 2200 series    | 1         | 2.94%   |
| Kyocera ECOSYS M5521cdw              | 1         | 2.94%   |
| HP Officejet 4630 series             | 1         | 2.94%   |
| HP Neverstop Laser 100x              | 1         | 2.94%   |
| HP LaserJet Pro M148-M149            | 1         | 2.94%   |
| HP LaserJet 1150                     | 1         | 2.94%   |
| HP Ink Tank 310 series               | 1         | 2.94%   |
| HP DeskJet 3700 series               | 1         | 2.94%   |
| HP DeskJet 3630 series               | 1         | 2.94%   |
| HP DeskJet 2700 series               | 1         | 2.94%   |
| Graphtec America Graphtec Printer    | 1         | 2.94%   |
| Canon TS3100 series                  | 1         | 2.94%   |
| Canon TR4500 series                  | 1         | 2.94%   |
| Canon TR150 series                   | 1         | 2.94%   |
| Canon PIXMA MG3600 Series            | 1         | 2.94%   |
| Canon PIXMA MG3500 Series            | 1         | 2.94%   |
| Canon MF3110                         | 1         | 2.94%   |
| Canon CanoScan LiDE 300              | 1         | 2.94%   |
| Brother Printer                      | 1         | 2.94%   |
| Brother MFC-9330CDW                  | 1         | 2.94%   |
| Brother HL-2230 series               | 1         | 2.94%   |
| Brother HL-1110 series               | 1         | 2.94%   |
| Brother DCP-T510W                    | 1         | 2.94%   |
| Brother DCP-T220                     | 1         | 2.94%   |
| Brother DCP-L2530DW series           | 1         | 2.94%   |
| Brother DCP-7055W                    | 1         | 2.94%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 6         | 66.67%  |
| Seiko Epson | 3         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 100                                 | 2         | 22.22%  |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1         | 11.11%  |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 11.11%  |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 11.11%  |
| Canon CanoScan LiDE 70                                  | 1         | 11.11%  |
| Canon CanoScan LiDE 220                                 | 1         | 11.11%  |
| Canon CanoScan LiDE 210                                 | 1         | 11.11%  |
| Canon CanoScan LiDE 200                                 | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 298       | 20.5%   |
| IMC Networks                           | 168       | 11.55%  |
| Microdia                               | 119       | 8.18%   |
| Acer                                   | 112       | 7.7%    |
| Realtek Semiconductor                  | 110       | 7.57%   |
| Logitech                               | 103       | 7.08%   |
| Quanta                                 | 86        | 5.91%   |
| Sunplus Innovation Technology          | 66        | 4.54%   |
| Cheng Uei Precision Industry (Foxlink) | 54        | 3.71%   |
| Apple                                  | 47        | 3.23%   |
| Syntek                                 | 43        | 2.96%   |
| Luxvisions Innotech Limited            | 43        | 2.96%   |
| Lite-On Technology                     | 27        | 1.86%   |
| Suyin                                  | 16        | 1.1%    |
| Microsoft                              | 16        | 1.1%    |
| Ricoh                                  | 12        | 0.83%   |
| Silicon Motion                         | 11        | 0.76%   |
| Samsung Electronics                    | 11        | 0.76%   |
| KYE Systems (Mouse Systems)            | 11        | 0.76%   |
| Lenovo                                 | 8         | 0.55%   |
| Alcor Micro                            | 8         | 0.55%   |
| SunplusIT                              | 7         | 0.48%   |
| Primax Electronics                     | 7         | 0.48%   |
| Hewlett-Packard                        | 6         | 0.41%   |
| Sonix Technology                       | 5         | 0.34%   |
| Razer USA                              | 5         | 0.34%   |
| icSpring                               | 4         | 0.28%   |
| Generalplus Technology                 | 4         | 0.28%   |
| ARC International                      | 4         | 0.28%   |
| Unknown                                | 3         | 0.21%   |
| Jieli Technology                       | 3         | 0.21%   |
| Cubeternet                             | 3         | 0.21%   |
| Creative Technology                    | 3         | 0.21%   |
| Z-Star Microelectronics                | 2         | 0.14%   |
| MacroSilicon                           | 2         | 0.14%   |
| Linux Foundation                       | 2         | 0.14%   |
| Intel                                  | 2         | 0.14%   |
| BKX-210918                             | 2         | 0.14%   |
| Asuscom Network                        | 2         | 0.14%   |
| 2M UVC CAMERA                          | 2         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 102       | 6.91%   |
| Microdia Integrated_Webcam_HD                        | 74        | 5.01%   |
| IMC Networks Integrated Camera                       | 65        | 4.4%    |
| IMC Networks USB2.0 HD UVC WebCam                    | 58        | 3.93%   |
| Realtek Integrated_Webcam_HD                         | 46        | 3.12%   |
| Acer Integrated Camera                               | 44        | 2.98%   |
| Syntek Integrated Camera                             | 32        | 2.17%   |
| Chicony HD Webcam                                    | 31        | 2.1%    |
| Logitech HD Pro Webcam C920                          | 29        | 1.96%   |
| Sunplus Integrated_Webcam_HD                         | 22        | 1.49%   |
| Logitech Webcam C270                                 | 18        | 1.22%   |
| Quanta HD User Facing                                | 17        | 1.15%   |
| Chicony Integrated Camera (1280x720@30)              | 16        | 1.08%   |
| Chicony HP Wide Vision HD Camera                     | 16        | 1.08%   |
| Apple FaceTime HD Camera (Built-in)                  | 16        | 1.08%   |
| Acer HD Webcam                                       | 16        | 1.08%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 15        | 1.02%   |
| Chicony HP HD Camera                                 | 14        | 0.95%   |
| Quanta HP TrueVision HD Camera                       | 12        | 0.81%   |
| Quanta HP HD Camera                                  | 12        | 0.81%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 12        | 0.81%   |
| Lite-On Integrated Camera                            | 12        | 0.81%   |
| Apple iPhone 5/5C/5S/6/SE                            | 12        | 0.81%   |
| Samsung Galaxy A5 (MTP)                              | 11        | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 11        | 0.75%   |
| Microdia USB 2.0 Camera                              | 10        | 0.68%   |
| Chicony HP TrueVision HD Camera                      | 10        | 0.68%   |
| Apple Built-in iSight                                | 9         | 0.61%   |
| Acer Lenovo EasyCamera                               | 9         | 0.61%   |
| Microdia Webcam Vitade AF                            | 8         | 0.54%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 8         | 0.54%   |
| Logitech C920 PRO HD Webcam                          | 8         | 0.54%   |
| IMC Networks HD Camera                               | 8         | 0.54%   |
| Chicony EasyCamera                                   | 8         | 0.54%   |
| Sunplus HD 720P webcam                               | 7         | 0.47%   |
| Realtek USB Camera                                   | 7         | 0.47%   |
| Quanta USB2.0 HD UVC WebCam                          | 7         | 0.47%   |
| Primax HP HD Webcam [Fixed]                          | 7         | 0.47%   |
| Luxvisions Innotech Limited Integrated RGB Camera    | 7         | 0.47%   |
| Luxvisions Innotech Limited Integrated Camera        | 7         | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 135       | 39.82%  |
| Validity Sensors           | 72        | 21.24%  |
| Shenzhen Goodix Technology | 71        | 20.94%  |
| Elan Microelectronics      | 23        | 6.78%   |
| LighTuning Technology      | 13        | 3.83%   |
| Upek                       | 10        | 2.95%   |
| AuthenTec                  | 7         | 2.06%   |
| Focal-systems.Corp         | 3         | 0.88%   |
| DigitalPersona             | 2         | 0.59%   |
| STMicroelectronics         | 1         | 0.29%   |
| Samsung Electronics        | 1         | 0.29%   |
| Dell                       | 1         | 0.29%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 50        | 14.75%  |
| Unknown                                                                    | 43        | 12.68%  |
| Shenzhen Goodix  Fingerprint Device                                        | 37        | 10.91%  |
| Shenzhen Goodix Fingerprint Reader                                         | 23        | 6.78%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 19        | 5.6%    |
| Elan ELAN:ARM-M4                                                           | 14        | 4.13%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 3.83%   |
| Shenzhen Goodix FingerPrint                                                | 11        | 3.24%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 2.95%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 2.95%   |
| Validity Sensors VFS491                                                    | 9         | 2.65%   |
| Elan ELAN:Fingerprint                                                      | 9         | 2.65%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 2.36%   |
| Synaptics  WBDI                                                            | 8         | 2.36%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 2.06%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 7         | 2.06%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 2.06%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 1.47%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.47%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.47%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.88%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.88%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 0.88%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 0.88%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 0.88%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.59%   |
| Synaptics WBDI Device                                                      | 2         | 0.59%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.59%   |
| DigitalPersona Fingerprint Reader                                          | 2         | 0.59%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 0.59%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.59%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.29%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.29%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.29%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.29%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.29%   |
| Dell MS819 Wired Mouse With Fingerprint Reader                             | 1         | 0.29%   |
| AuthenTec AES2810                                                          | 1         | 0.29%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.29%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 51        | 44.74%  |
| Broadcom                   | 38        | 33.33%  |
| Upek                       | 7         | 6.14%   |
| Lenovo                     | 6         | 5.26%   |
| SCM Microsystems           | 3         | 2.63%   |
| OmniKey                    | 2         | 1.75%   |
| O2 Micro                   | 2         | 1.75%   |
| Yubico.com                 | 1         | 0.88%   |
| Realtek Semiconductor      | 1         | 0.88%   |
| Gemalto (was Gemplus)      | 1         | 0.88%   |
| Athena Smartcard Solutions | 1         | 0.88%   |
| Aktiv                      | 1         | 0.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 49        | 42.98%  |
| Broadcom 58200                                                               | 16        | 14.04%  |
| Broadcom 5880                                                                | 8         | 7.02%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 6.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 6.14%   |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 6.14%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 4.39%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 1.75%   |
| OmniKey CardMan 1021                                                         | 2         | 1.75%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.88%   |
| SCM Microsystems CLOUD 2900 R Smart Card Reader                              | 1         | 0.88%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.88%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.88%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 0.88%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.88%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.88%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 0.88%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.88%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.88%   |
| Aktiv Rutoken lite                                                           | 1         | 0.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1346      | 64.4%   |
| 1     | 606       | 29%     |
| 2     | 114       | 5.45%   |
| 3     | 16        | 0.77%   |
| 4     | 3         | 0.14%   |
| 7     | 2         | 0.1%    |
| 8     | 1         | 0.05%   |
| 6     | 1         | 0.05%   |
| 5     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 333       | 38.06%  |
| Graphics card            | 186       | 21.26%  |
| Multimedia controller    | 96        | 10.97%  |
| Net/wireless             | 90        | 10.29%  |
| Camera                   | 46        | 5.26%   |
| Chipcard                 | 24        | 2.74%   |
| Bluetooth                | 23        | 2.63%   |
| Sound                    | 13        | 1.49%   |
| Card reader              | 11        | 1.26%   |
| Network                  | 10        | 1.14%   |
| Communication controller | 10        | 1.14%   |
| Storage                  | 9         | 1.03%   |
| Unassigned class         | 7         | 0.8%    |
| Modem                    | 6         | 0.69%   |
| Storage/raid             | 4         | 0.46%   |
| Net/ethernet             | 4         | 0.46%   |
| Wireless                 | 1         | 0.11%   |
| Tv card                  | 1         | 0.11%   |
| Firewire controller      | 1         | 0.11%   |


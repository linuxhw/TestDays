Gentoo 2.14 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for Gentoo 2.14.

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

Total: 170

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Razer         | Blade 14 - RZ09-0482        | [49f14f0aae](https://linux-hardware.org/?probe=49f14f0aae) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [afbbc9ebf0](https://linux-hardware.org/?probe=afbbc9ebf0) | Jan 31, 2024 |
| Star Labs     | StarBook                    | [a324d865a6](https://linux-hardware.org/?probe=a324d865a6) | Jan 24, 2024 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [07799fb2f9](https://linux-hardware.org/?probe=07799fb2f9) | Jan 19, 2024 |
| HP            | ZBook Studio 16 inch G9 ... | [e736cc5c9a](https://linux-hardware.org/?probe=e736cc5c9a) | Jan 18, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [18a0aeeddf](https://linux-hardware.org/?probe=18a0aeeddf) | Jan 18, 2024 |
| HP            | Laptop 15t-dy100            | [68c23a7bd3](https://linux-hardware.org/?probe=68c23a7bd3) | Jan 17, 2024 |
| HP            | EliteBook 830 G6            | [dc433d32e3](https://linux-hardware.org/?probe=dc433d32e3) | Jan 13, 2024 |
| MSI           | Pulse 15 B13VFK             | [75dde9eefd](https://linux-hardware.org/?probe=75dde9eefd) | Jan 12, 2024 |
| HP            | Laptop 15 da0018nk          | [11c54a0e5b](https://linux-hardware.org/?probe=11c54a0e5b) | Jan 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [a249210b7f](https://linux-hardware.org/?probe=a249210b7f) | Jan 11, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [d3f6265673](https://linux-hardware.org/?probe=d3f6265673) | Jan 10, 2024 |
| DEXP          | Aquilon C14                 | [d38932d74f](https://linux-hardware.org/?probe=d38932d74f) | Jan 10, 2024 |
| HP            | Laptop 15s-eq2xxx           | [36dc56b0ed](https://linux-hardware.org/?probe=36dc56b0ed) | Jan 09, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [ac39f0a923](https://linux-hardware.org/?probe=ac39f0a923) | Jan 08, 2024 |
| Star Labs     | StarLite                    | [751432d737](https://linux-hardware.org/?probe=751432d737) | Jan 07, 2024 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [33b192a7d0](https://linux-hardware.org/?probe=33b192a7d0) | Jan 06, 2024 |
| Acer          | Aspire A514-54              | [513f1c7737](https://linux-hardware.org/?probe=513f1c7737) | Jan 06, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1ecec883dd](https://linux-hardware.org/?probe=1ecec883dd) | Jan 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [98da18a6c0](https://linux-hardware.org/?probe=98da18a6c0) | Jan 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [2602d65d52](https://linux-hardware.org/?probe=2602d65d52) | Jan 06, 2024 |
| HP            | Victus by Laptop 16-e0xx... | [94b30c5116](https://linux-hardware.org/?probe=94b30c5116) | Jan 06, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [8d63c2ea2b](https://linux-hardware.org/?probe=8d63c2ea2b) | Jan 06, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [90b8ceb64c](https://linux-hardware.org/?probe=90b8ceb64c) | Jan 05, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | [42bd246eae](https://linux-hardware.org/?probe=42bd246eae) | Jan 05, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [f7ad5f683a](https://linux-hardware.org/?probe=f7ad5f683a) | Jan 04, 2024 |
| Star Labs     | StarLite                    | [9f0fae17e5](https://linux-hardware.org/?probe=9f0fae17e5) | Jan 02, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | [ab04c74157](https://linux-hardware.org/?probe=ab04c74157) | Jan 02, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | [8250c46efe](https://linux-hardware.org/?probe=8250c46efe) | Jan 02, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | [57cd074cfd](https://linux-hardware.org/?probe=57cd074cfd) | Jan 02, 2024 |
| Acer          | Aspire A517-52G             | [fb86c6f71c](https://linux-hardware.org/?probe=fb86c6f71c) | Jan 01, 2024 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [6826d7c88d](https://linux-hardware.org/?probe=6826d7c88d) | Jan 01, 2024 |
| Dell          | Latitude D630               | [bbae93d767](https://linux-hardware.org/?probe=bbae93d767) | Dec 31, 2023 |
| MSI           | Stealth 16Studio A13VF      | [04acb5230d](https://linux-hardware.org/?probe=04acb5230d) | Dec 30, 2023 |
| MSI           | Stealth 16Studio A13VF      | [1fd1d2e727](https://linux-hardware.org/?probe=1fd1d2e727) | Dec 30, 2023 |
| Dell          | Precision 5560              | [3555a4c2fa](https://linux-hardware.org/?probe=3555a4c2fa) | Dec 29, 2023 |
| ASUSTek       | G750JX                      | [2b867b6af5](https://linux-hardware.org/?probe=2b867b6af5) | Dec 28, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [3d96eb6f36](https://linux-hardware.org/?probe=3d96eb6f36) | Dec 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d1cd9acaf0](https://linux-hardware.org/?probe=d1cd9acaf0) | Dec 26, 2023 |
| MSI           | Delta 15 A5EFK              | [af7c011930](https://linux-hardware.org/?probe=af7c011930) | Dec 25, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [2394204218](https://linux-hardware.org/?probe=2394204218) | Dec 24, 2023 |
| TULPAR        | A5 V20.3                    | [c1abfa26d5](https://linux-hardware.org/?probe=c1abfa26d5) | Dec 24, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [6b0368fd61](https://linux-hardware.org/?probe=6b0368fd61) | Dec 23, 2023 |
| TULPAR        | A5 V20.3                    | [83c6679958](https://linux-hardware.org/?probe=83c6679958) | Dec 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [87b9f04878](https://linux-hardware.org/?probe=87b9f04878) | Dec 23, 2023 |
| Dell          | Precision 5480              | [7cc190b5c0](https://linux-hardware.org/?probe=7cc190b5c0) | Dec 22, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b14bdf4602](https://linux-hardware.org/?probe=b14bdf4602) | Dec 20, 2023 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | [8e419e7090](https://linux-hardware.org/?probe=8e419e7090) | Dec 16, 2023 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | [042bbde845](https://linux-hardware.org/?probe=042bbde845) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [4c6cd4453d](https://linux-hardware.org/?probe=4c6cd4453d) | Dec 10, 2023 |
| Dell          | XPS 9320                    | [60c734eb9c](https://linux-hardware.org/?probe=60c734eb9c) | Dec 08, 2023 |
| BANGHO        | MAX L4                      | [d1306fe54f](https://linux-hardware.org/?probe=d1306fe54f) | Dec 03, 2023 |
| BANGHO        | MAX L4                      | [a0f107fc92](https://linux-hardware.org/?probe=a0f107fc92) | Dec 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [426263e458](https://linux-hardware.org/?probe=426263e458) | Dec 03, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [d95358436c](https://linux-hardware.org/?probe=d95358436c) | Nov 30, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [d4c90a615f](https://linux-hardware.org/?probe=d4c90a615f) | Nov 29, 2023 |
| Unknown       | Unknown                     | [b6ebeab524](https://linux-hardware.org/?probe=b6ebeab524) | Nov 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [2b2bb98701](https://linux-hardware.org/?probe=2b2bb98701) | Nov 29, 2023 |
| Dell          | Latitude E6540              | [ae3c1282c2](https://linux-hardware.org/?probe=ae3c1282c2) | Nov 29, 2023 |
| Unknown       | Unknown                     | [d7d0f11ab2](https://linux-hardware.org/?probe=d7d0f11ab2) | Nov 28, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [f5949df300](https://linux-hardware.org/?probe=f5949df300) | Nov 28, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [ee929504ae](https://linux-hardware.org/?probe=ee929504ae) | Nov 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [9d3e14a9ba](https://linux-hardware.org/?probe=9d3e14a9ba) | Nov 27, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [83d5ded7d9](https://linux-hardware.org/?probe=83d5ded7d9) | Nov 27, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [8ef4fb91ac](https://linux-hardware.org/?probe=8ef4fb91ac) | Nov 27, 2023 |
| Dell          | Latitude D630               | [51af6a8f00](https://linux-hardware.org/?probe=51af6a8f00) | Nov 26, 2023 |
| HP            | EliteBook 840 G5            | [320763e400](https://linux-hardware.org/?probe=320763e400) | Nov 25, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [b305b3da28](https://linux-hardware.org/?probe=b305b3da28) | Nov 22, 2023 |
| Acer          | Aspire A315-34              | [336fe65e03](https://linux-hardware.org/?probe=336fe65e03) | Nov 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [360ad65af8](https://linux-hardware.org/?probe=360ad65af8) | Nov 21, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [3a8da808e0](https://linux-hardware.org/?probe=3a8da808e0) | Nov 20, 2023 |
| HP            | Victus by Gaming Laptop ... | [d46bf1bcb4](https://linux-hardware.org/?probe=d46bf1bcb4) | Nov 18, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CMC... | [e25caef1f8](https://linux-hardware.org/?probe=e25caef1f8) | Nov 18, 2023 |
| HP            | Pavilion Notebook           | [85f5d912da](https://linux-hardware.org/?probe=85f5d912da) | Nov 18, 2023 |
| Dell          | Latitude D630               | [54e404f085](https://linux-hardware.org/?probe=54e404f085) | Nov 18, 2023 |
| Dell          | Precision 5480              | [ee10103325](https://linux-hardware.org/?probe=ee10103325) | Nov 18, 2023 |
| Notebook      | NS5x_NS7xPU                 | [c26f7106c6](https://linux-hardware.org/?probe=c26f7106c6) | Nov 15, 2023 |
| Acer          | Aspire A315-34              | [8179414a49](https://linux-hardware.org/?probe=8179414a49) | Nov 14, 2023 |
| Dell          | G5 5505                     | [be553804bd](https://linux-hardware.org/?probe=be553804bd) | Nov 13, 2023 |
| ASUSTek       | ROG G703GI_G7BI             | [f1e3e6eb2c](https://linux-hardware.org/?probe=f1e3e6eb2c) | Nov 13, 2023 |
| Dell          | G5 5505                     | [574ccd4e6f](https://linux-hardware.org/?probe=574ccd4e6f) | Nov 13, 2023 |
| Lenovo        | G50-30 80G0                 | [51cd292a70](https://linux-hardware.org/?probe=51cd292a70) | Nov 12, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [8415697290](https://linux-hardware.org/?probe=8415697290) | Nov 12, 2023 |
| Lenovo        | ThinkPad T420 4236QE0       | [16d356b88c](https://linux-hardware.org/?probe=16d356b88c) | Nov 12, 2023 |
| Lenovo        | ThinkPad T420 4236QE0       | [bce581924a](https://linux-hardware.org/?probe=bce581924a) | Nov 12, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [6996973cde](https://linux-hardware.org/?probe=6996973cde) | Nov 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [4aae90aee9](https://linux-hardware.org/?probe=4aae90aee9) | Nov 11, 2023 |
| Notebook      | NS5x_NS7xPU                 | [4b53c4e9da](https://linux-hardware.org/?probe=4b53c4e9da) | Nov 10, 2023 |
| HP            | Victus by Gaming Laptop ... | [aa17167e95](https://linux-hardware.org/?probe=aa17167e95) | Nov 09, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [379584ba47](https://linux-hardware.org/?probe=379584ba47) | Nov 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [c0f28da2b7](https://linux-hardware.org/?probe=c0f28da2b7) | Nov 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [24cd0b58d3](https://linux-hardware.org/?probe=24cd0b58d3) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [503b6e943c](https://linux-hardware.org/?probe=503b6e943c) | Nov 06, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [cff5d02cde](https://linux-hardware.org/?probe=cff5d02cde) | Nov 05, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [0ce0a4d87a](https://linux-hardware.org/?probe=0ce0a4d87a) | Nov 04, 2023 |
| Dell          | XPS 15 9530                 | [148857cc51](https://linux-hardware.org/?probe=148857cc51) | Oct 31, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [b553bb2a36](https://linux-hardware.org/?probe=b553bb2a36) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [0a990e1165](https://linux-hardware.org/?probe=0a990e1165) | Oct 31, 2023 |
| Dell          | Latitude 7320               | [efc40122bf](https://linux-hardware.org/?probe=efc40122bf) | Oct 30, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [de3f77c938](https://linux-hardware.org/?probe=de3f77c938) | Oct 30, 2023 |
| HP            | EliteBook 840 G6            | [b113709ec2](https://linux-hardware.org/?probe=b113709ec2) | Oct 29, 2023 |
| Acer          | Swift SFX14-41G             | [63b5c65c01](https://linux-hardware.org/?probe=63b5c65c01) | Oct 28, 2023 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | [5c169fe4ed](https://linux-hardware.org/?probe=5c169fe4ed) | Oct 27, 2023 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | [1c1d7bd2b1](https://linux-hardware.org/?probe=1c1d7bd2b1) | Oct 27, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [47e99a1356](https://linux-hardware.org/?probe=47e99a1356) | Oct 26, 2023 |
| HP            | EliteBook 845 14 inch G1... | [ba2a49fbef](https://linux-hardware.org/?probe=ba2a49fbef) | Oct 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [f4a0aca53d](https://linux-hardware.org/?probe=f4a0aca53d) | Oct 24, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [f2b15bc2f1](https://linux-hardware.org/?probe=f2b15bc2f1) | Oct 23, 2023 |
| Lenovo        | G50-30 80G0                 | [2a00efe761](https://linux-hardware.org/?probe=2a00efe761) | Oct 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [3368da4a2b](https://linux-hardware.org/?probe=3368da4a2b) | Oct 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [e794aa4113](https://linux-hardware.org/?probe=e794aa4113) | Oct 18, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [98ebe6766d](https://linux-hardware.org/?probe=98ebe6766d) | Oct 14, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [4f5f1c9eea](https://linux-hardware.org/?probe=4f5f1c9eea) | Oct 11, 2023 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [af06968ae1](https://linux-hardware.org/?probe=af06968ae1) | Oct 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [da869ee2ba](https://linux-hardware.org/?probe=da869ee2ba) | Oct 04, 2023 |
| HP            | EliteBook 830 G6            | [e684c274a6](https://linux-hardware.org/?probe=e684c274a6) | Oct 03, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | [40f87e9874](https://linux-hardware.org/?probe=40f87e9874) | Oct 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [6fb4d2a754](https://linux-hardware.org/?probe=6fb4d2a754) | Oct 01, 2023 |
| HP            | EliteBook 830 G6            | [154150aa88](https://linux-hardware.org/?probe=154150aa88) | Sep 30, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [2a507c567b](https://linux-hardware.org/?probe=2a507c567b) | Sep 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [b6acaf4c61](https://linux-hardware.org/?probe=b6acaf4c61) | Sep 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [f1623258a8](https://linux-hardware.org/?probe=f1623258a8) | Sep 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [7d4c2dc8f6](https://linux-hardware.org/?probe=7d4c2dc8f6) | Sep 25, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [8a581a8a85](https://linux-hardware.org/?probe=8a581a8a85) | Sep 24, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [7732f1eb9b](https://linux-hardware.org/?probe=7732f1eb9b) | Sep 22, 2023 |
| HP            | ProBook 450 G5              | [e1b56bb588](https://linux-hardware.org/?probe=e1b56bb588) | Sep 19, 2023 |
| HP            | EliteBook 830 G6            | [8dcd49002d](https://linux-hardware.org/?probe=8dcd49002d) | Sep 18, 2023 |
| Lenovo        | ThinkPad P43s 20RHCTO1WW    | [4b1c4ae225](https://linux-hardware.org/?probe=4b1c4ae225) | Sep 18, 2023 |
| Timi          | RedmiBook Pro 15S           | [3306655fb2](https://linux-hardware.org/?probe=3306655fb2) | Sep 17, 2023 |
| Timi          | RedmiBook Pro 15S           | [75a8af42cd](https://linux-hardware.org/?probe=75a8af42cd) | Sep 17, 2023 |
| Acer          | Aspire A515-45              | [7cd5acacf7](https://linux-hardware.org/?probe=7cd5acacf7) | Sep 16, 2023 |
| HP            | EliteBook 8540w             | [ec5b4aeb84](https://linux-hardware.org/?probe=ec5b4aeb84) | Sep 15, 2023 |
| HP            | ProBook 450 G5              | [077f5b81b8](https://linux-hardware.org/?probe=077f5b81b8) | Sep 14, 2023 |
| Apple         | MacBookPro11,2              | [e38a2e668b](https://linux-hardware.org/?probe=e38a2e668b) | Sep 12, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [de7acf45a6](https://linux-hardware.org/?probe=de7acf45a6) | Sep 12, 2023 |
| HP            | Laptop 14s-dq2xxx           | [f24f476710](https://linux-hardware.org/?probe=f24f476710) | Sep 11, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [5ac44fe5ec](https://linux-hardware.org/?probe=5ac44fe5ec) | Sep 11, 2023 |
| Apple         | MacBookPro11,2              | [830ca674bb](https://linux-hardware.org/?probe=830ca674bb) | Sep 10, 2023 |
| Dell          | Precision M4800             | [ea570fedac](https://linux-hardware.org/?probe=ea570fedac) | Sep 09, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [a6bbf0ac50](https://linux-hardware.org/?probe=a6bbf0ac50) | Sep 08, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [7be90edf82](https://linux-hardware.org/?probe=7be90edf82) | Sep 08, 2023 |
| System76      | Pangolin                    | [43dbf49440](https://linux-hardware.org/?probe=43dbf49440) | Sep 06, 2023 |
| System76      | Pangolin                    | [461b8d48ba](https://linux-hardware.org/?probe=461b8d48ba) | Sep 05, 2023 |
| Gigabyte      | AORUS 17 XE4                | [7987abcc44](https://linux-hardware.org/?probe=7987abcc44) | Sep 04, 2023 |
| Dell          | Inspiron 16 5625            | [f3cbaf1a86](https://linux-hardware.org/?probe=f3cbaf1a86) | Sep 04, 2023 |
| Dell          | Inspiron 16 5625            | [b0e01251ca](https://linux-hardware.org/?probe=b0e01251ca) | Sep 04, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [ba5eecca4c](https://linux-hardware.org/?probe=ba5eecca4c) | Sep 03, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [6f9a36245f](https://linux-hardware.org/?probe=6f9a36245f) | Sep 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [efd96ce796](https://linux-hardware.org/?probe=efd96ce796) | Sep 03, 2023 |
| HP            | ProBook 430 G5              | [1785af95b8](https://linux-hardware.org/?probe=1785af95b8) | Sep 02, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [5032531f3e](https://linux-hardware.org/?probe=5032531f3e) | Sep 02, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [678bbd1366](https://linux-hardware.org/?probe=678bbd1366) | Sep 01, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [cb84df3a99](https://linux-hardware.org/?probe=cb84df3a99) | Aug 31, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [96d825f112](https://linux-hardware.org/?probe=96d825f112) | Aug 31, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [b4eb252e8f](https://linux-hardware.org/?probe=b4eb252e8f) | Aug 31, 2023 |
| Dell          | Inspiron 15 3511            | [d53deba94a](https://linux-hardware.org/?probe=d53deba94a) | Aug 31, 2023 |
| Dell          | Latitude E6510              | [ccc08ed4ed](https://linux-hardware.org/?probe=ccc08ed4ed) | Aug 30, 2023 |
| Dell          | Latitude E6510              | [dcf1be6cbe](https://linux-hardware.org/?probe=dcf1be6cbe) | Aug 30, 2023 |
| Dell          | G5 5505                     | [a96b02c261](https://linux-hardware.org/?probe=a96b02c261) | Aug 28, 2023 |
| Dell          | G5 5505                     | [01201d16aa](https://linux-hardware.org/?probe=01201d16aa) | Aug 28, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [19433fe76f](https://linux-hardware.org/?probe=19433fe76f) | Aug 24, 2023 |
| HP            | ProBook 430 G7              | [b8a468626b](https://linux-hardware.org/?probe=b8a468626b) | Aug 24, 2023 |
| MSI           | Modern 14 C12M              | [86efcd3eb7](https://linux-hardware.org/?probe=86efcd3eb7) | Aug 21, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [6f1a280aa5](https://linux-hardware.org/?probe=6f1a280aa5) | Aug 21, 2023 |
| Timi          | RedmiBook Pro 15S           | [3223b9a4bb](https://linux-hardware.org/?probe=3223b9a4bb) | Aug 19, 2023 |
| HP            | Laptop 14-df0xxx            | [7d3c3dc329](https://linux-hardware.org/?probe=7d3c3dc329) | Aug 17, 2023 |
| A-DATA Tec... | XENIA 15                    | [73f0314b31](https://linux-hardware.org/?probe=73f0314b31) | Aug 12, 2023 |
| A-DATA Tec... | XENIA 15                    | [d1a19f992d](https://linux-hardware.org/?probe=d1a19f992d) | Aug 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [839698eb4c](https://linux-hardware.org/?probe=839698eb4c) | Aug 01, 2023 |
| Dell          | XPS 15 9520                 | [54377b2911](https://linux-hardware.org/?probe=54377b2911) | Jul 25, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 6.1.57-gentoo-x86_64      | 7         | 5.65%   |
| 6.1.67-gentoo-dist        | 5         | 4.03%   |
| 6.1.57-gentoo             | 5         | 4.03%   |
| 6.1.46-gentoo             | 5         | 4.03%   |
| 6.1.57-gentoo-dist        | 4         | 3.23%   |
| 6.6.9-gentoo              | 3         | 2.42%   |
| 6.6.8-gentoo              | 3         | 2.42%   |
| 6.6.0-gentoo              | 3         | 2.42%   |
| 6.1.67-gentoo             | 3         | 2.42%   |
| 6.1.46-gentoo-x86_64      | 3         | 2.42%   |
| 6.7.0-gentoo              | 2         | 1.61%   |
| 6.6.8-gentoo-x86_64       | 2         | 1.61%   |
| 6.5.8-gentoo-r1           | 2         | 1.61%   |
| 6.5.1-gentoo              | 2         | 1.61%   |
| 6.1.60-gentoo-dist        | 2         | 1.61%   |
| 6.1.57-gentoo-gentoo-dist | 2         | 1.61%   |
| 6.1.53-gentoo-r1-x86_64   | 2         | 1.61%   |
| 6.1.53-gentoo-r1          | 2         | 1.61%   |
| 6.7.0-rc5                 | 1         | 0.81%   |
| 6.7.0-rc1                 | 1         | 0.81%   |
| 6.7.0-gentoox64.efi       | 1         | 0.81%   |
| 6.6.8                     | 1         | 0.81%   |
| 6.6.7-gentoo-md-a15       | 1         | 0.81%   |
| 6.6.7-gentoo-dist         | 1         | 0.81%   |
| 6.6.3-gentoo-r1           | 1         | 0.81%   |
| 6.6.2-gentoo-#136         | 1         | 0.81%   |
| 6.6.2-gentoo              | 1         | 0.81%   |
| 6.6.13-gentoo-dist        | 1         | 0.81%   |
| 6.6.13-gentoo             | 1         | 0.81%   |
| 6.6.11-gentoo-x86_64      | 1         | 0.81%   |
| 6.6.10-gentoo-dist        | 1         | 0.81%   |
| 6.6.1-gentoo-dist         | 1         | 0.81%   |
| 6.6.1-gentoo-dark         | 1         | 0.81%   |
| 6.6.1-gentoo-122          | 1         | 0.81%   |
| 6.6.1-gentoo              | 1         | 0.81%   |
| 6.6.0-waltercool          | 1         | 0.81%   |
| 6.6.0-gentoo-x86_64       | 1         | 0.81%   |
| 6.5.9-perfection          | 1         | 0.81%   |
| 6.5.9-gentoo              | 1         | 0.81%   |
| 6.5.8-gentoo-r1-x86_64    | 1         | 0.81%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1.57  | 19        | 15.57%  |
| 6.1.46  | 11        | 9.02%   |
| 6.1.67  | 10        | 8.2%    |
| 6.6.8   | 6         | 4.92%   |
| 6.1.53  | 6         | 4.92%   |
| 6.6.0   | 5         | 4.1%    |
| 6.7.0   | 4         | 3.28%   |
| 6.6.1   | 4         | 3.28%   |
| 6.5.8   | 4         | 3.28%   |
| 6.6.9   | 3         | 2.46%   |
| 6.5.7   | 3         | 2.46%   |
| 6.5.1   | 3         | 2.46%   |
| 6.4.11  | 3         | 2.46%   |
| 6.1.41  | 3         | 2.46%   |
| 6.6.7   | 2         | 1.64%   |
| 6.6.2   | 2         | 1.64%   |
| 6.6.13  | 2         | 1.64%   |
| 6.5.9   | 2         | 1.64%   |
| 6.5.4   | 2         | 1.64%   |
| 6.5.3   | 2         | 1.64%   |
| 6.5.0   | 2         | 1.64%   |
| 6.4.4   | 2         | 1.64%   |
| 6.1.60  | 2         | 1.64%   |
| 6.6.3   | 1         | 0.82%   |
| 6.6.11  | 1         | 0.82%   |
| 6.6.10  | 1         | 0.82%   |
| 6.5.5   | 1         | 0.82%   |
| 6.5.2   | 1         | 0.82%   |
| 6.5.10  | 1         | 0.82%   |
| 6.4.9   | 1         | 0.82%   |
| 6.4.14  | 1         | 0.82%   |
| 6.4.13  | 1         | 0.82%   |
| 6.4.12  | 1         | 0.82%   |
| 6.4.10  | 1         | 0.82%   |
| 6.2.5   | 1         | 0.82%   |
| 6.1.69  | 1         | 0.82%   |
| 6.1.66  | 1         | 0.82%   |
| 6.1.55  | 1         | 0.82%   |
| 6.1.31  | 1         | 0.82%   |
| 6.1.28  | 1         | 0.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 53        | 45.3%   |
| 6.6     | 27        | 23.08%  |
| 6.5     | 20        | 17.09%  |
| 6.4     | 10        | 8.55%   |
| 6.7     | 4         | 3.42%   |
| 6.2     | 1         | 0.85%   |
| 5.19    | 1         | 0.85%   |
| 5.15    | 1         | 0.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 110       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KDE5          | 32        | 28.83%  |
| Unknown       | 30        | 27.03%  |
| GNOME         | 11        | 9.91%   |
| XFCE          | 10        | 9.01%   |
| Hyprland      | 9         | 8.11%   |
| DWM           | 5         | 4.5%    |
| MATE          | 3         | 2.7%    |
| LXQt          | 3         | 2.7%    |
| i3            | 2         | 1.8%    |
| LXDE          | 1         | 0.9%    |
| KDE6          | 1         | 0.9%    |
| ICEWM         | 1         | 0.9%    |
| GNOME Classic | 1         | 0.9%    |
| bspwm         | 1         | 0.9%    |
| awesome       | 1         | 0.9%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 43        | 37.72%  |
| Wayland | 43        | 37.72%  |
| Unknown | 15        | 13.16%  |
| Tty     | 13        | 11.4%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 41        | 36.28%  |
| SDDM    | 40        | 35.4%   |
| LightDM | 17        | 15.04%  |
| GDM     | 7         | 6.19%   |
| GREETD  | 4         | 3.54%   |
| SLiM    | 3         | 2.65%   |
| Ly      | 1         | 0.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Notebooks | Percent |
|----------------|-----------|---------|
| en_US          | 43        | 38.74%  |
| Unknown        | 15        | 13.51%  |
| C.UTF8         | 13        | 11.71%  |
| fr_FR          | 5         | 4.5%    |
| en_GB          | 5         | 4.5%    |
| C              | 5         | 4.5%    |
| ru_RU          | 4         | 3.6%    |
| de_DE          | 4         | 3.6%    |
| cs_CZ          | 3         | 2.7%    |
| zh_CN          | 2         | 1.8%    |
| de_CH          | 2         | 1.8%    |
| uk_UA          | 1         | 0.9%    |
| pl_PL          | 1         | 0.9%    |
| ja_JP          | 1         | 0.9%    |
| it_IT.iso88591 | 1         | 0.9%    |
| fi_FI          | 1         | 0.9%    |
| es_MX          | 1         | 0.9%    |
| es_CL          | 1         | 0.9%    |
| es_AR          | 1         | 0.9%    |
| en_IE          | 1         | 0.9%    |
| el_GR          | 1         | 0.9%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 100       | 90.91%  |
| BIOS | 10        | 9.09%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 47        | 42.73%  |
| Btrfs    | 38        | 34.55%  |
| Xfs      | 16        | 14.55%  |
| Zfs      | 4         | 3.64%   |
| F2fs     | 3         | 2.73%   |
| XXXXXXX  | 1         | 0.91%   |
| Bcachefs | 1         | 0.91%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 104       | 94.55%  |
| MBR     | 4         | 3.64%   |
| Unknown | 2         | 1.82%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 91        | 81.98%  |
| Yes       | 20        | 18.02%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 83        | 74.11%  |
| Yes       | 29        | 25.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 28        | 25.45%  |
| Hewlett-Packard     | 21        | 19.09%  |
| ASUSTek Computer    | 17        | 15.45%  |
| Dell                | 14        | 12.73%  |
| Framework           | 7         | 6.36%   |
| Acer                | 5         | 4.55%   |
| MSI                 | 4         | 3.64%   |
| Star Labs           | 2         | 1.82%   |
| TULPAR              | 1         | 0.91%   |
| Timi                | 1         | 0.91%   |
| System76            | 1         | 0.91%   |
| Razer               | 1         | 0.91%   |
| Notebook            | 1         | 0.91%   |
| HUAWEI              | 1         | 0.91%   |
| Gigabyte Technology | 1         | 0.91%   |
| DEXP                | 1         | 0.91%   |
| BANGHO              | 1         | 0.91%   |
| Apple               | 1         | 0.91%   |
| A-DATA Technology   | 1         | 0.91%   |
| Unknown             | 1         | 0.91%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Framework Laptop (13th Gen Intel Core)     | 4         | 3.64%   |
| Framework Laptop 13 (AMD Ryzen 7040Series) | 3         | 2.73%   |
| Dell Precision 5480                        | 2         | 1.82%   |
| TULPAR A5 V20.3                            | 1         | 0.91%   |
| Timi RedmiBook Pro 15S                     | 1         | 0.91%   |
| System76 Pangolin                          | 1         | 0.91%   |
| Star Labs StarLite                         | 1         | 0.91%   |
| Star Labs StarBook                         | 1         | 0.91%   |
| Razer Blade 14 - RZ09-0482                 | 1         | 0.91%   |
| Notebook NS5x_NS7xPU                       | 1         | 0.91%   |
| MSI Stealth 16Studio A13VF                 | 1         | 0.91%   |
| MSI Pulse 15 B13VFK                        | 1         | 0.91%   |
| MSI Modern 14 C12M                         | 1         | 0.91%   |
| MSI Delta 15 A5EFK                         | 1         | 0.91%   |
| Lenovo V14 G2 ALC 82KC                     | 1         | 0.91%   |
| Lenovo ThinkPad X395 20NLCTO1WW            | 1         | 0.91%   |
| Lenovo ThinkPad X13 Gen 3 21CMCTO1WW       | 1         | 0.91%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVS10E00  | 1         | 0.91%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES01M00   | 1         | 0.91%   |
| Lenovo ThinkPad T460 20FNCTO1WW            | 1         | 0.91%   |
| Lenovo ThinkPad T420 4236QE0               | 1         | 0.91%   |
| Lenovo ThinkPad T410 2518C3U               | 1         | 0.91%   |
| Lenovo ThinkPad T16 Gen 1 21CHCTO1WW       | 1         | 0.91%   |
| Lenovo ThinkPad T15p Gen 3 21DACTO1WW      | 1         | 0.91%   |
| Lenovo ThinkPad T14 Gen 1 20UES1Y200       | 1         | 0.91%   |
| Lenovo ThinkPad P43s 20RHCTO1WW            | 1         | 0.91%   |
| Lenovo ThinkPad P16s Gen 2 21K9CTO1WW      | 1         | 0.91%   |
| Lenovo ThinkPad L15 Gen 1 20U70029UK       | 1         | 0.91%   |
| Lenovo ThinkPad Edge E330 3354AMG          | 1         | 0.91%   |
| Lenovo ThinkPad E15 Gen 4 21EDCTO1WW       | 1         | 0.91%   |
| Lenovo ThinkPad E15 Gen 2 20TD00GSGE       | 1         | 0.91%   |
| Lenovo ThinkPad E15 Gen 2 20T8000MPB       | 1         | 0.91%   |
| Lenovo ThinkPad E14 Gen 4 21EBCTO1WW       | 1         | 0.91%   |
| Lenovo ThinkPad E14 Gen 2 20TA0028RT       | 1         | 0.91%   |
| Lenovo ThinkBook 16 G6 ABP 21KK            | 1         | 0.91%   |
| Lenovo Legion R9000P2021H 82JQ             | 1         | 0.91%   |
| Lenovo Legion Pro 5 16ARX8 82WM            | 1         | 0.91%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ           | 1         | 0.91%   |
| Lenovo Legion 5 15ACH6H 82JU               | 1         | 0.91%   |
| Lenovo IdeaPad 5 15ABA7 82SG               | 1         | 0.91%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 19        | 17.27%  |
| ASUS VivoBook      | 8         | 7.27%   |
| Framework Laptop   | 7         | 6.36%   |
| HP EliteBook       | 6         | 5.45%   |
| HP Laptop          | 5         | 4.55%   |
| Lenovo Legion      | 4         | 3.64%   |
| HP ProBook         | 4         | 3.64%   |
| Dell Precision     | 4         | 3.64%   |
| Dell Latitude      | 4         | 3.64%   |
| ASUS ROG           | 4         | 3.64%   |
| Acer Aspire        | 4         | 3.64%   |
| HP Victus          | 3         | 2.73%   |
| Dell XPS           | 3         | 2.73%   |
| ASUS ZenBook       | 3         | 2.73%   |
| Lenovo IdeaPad     | 2         | 1.82%   |
| HP Pavilion        | 2         | 1.82%   |
| Dell Inspiron      | 2         | 1.82%   |
| TULPAR A5          | 1         | 0.91%   |
| Timi RedmiBook     | 1         | 0.91%   |
| System76 Pangolin  | 1         | 0.91%   |
| Star Labs StarLite | 1         | 0.91%   |
| Star Labs StarBook | 1         | 0.91%   |
| Razer Blade        | 1         | 0.91%   |
| Notebook NS5x      | 1         | 0.91%   |
| MSI Stealth        | 1         | 0.91%   |
| MSI Pulse          | 1         | 0.91%   |
| MSI Modern         | 1         | 0.91%   |
| MSI Delta          | 1         | 0.91%   |
| Lenovo V14         | 1         | 0.91%   |
| Lenovo ThinkBook   | 1         | 0.91%   |
| Lenovo G50-30      | 1         | 0.91%   |
| HUAWEI NBLK-WAX9X  | 1         | 0.91%   |
| HP ZBook           | 1         | 0.91%   |
| Gigabyte AORUS     | 1         | 0.91%   |
| DEXP Aquilon       | 1         | 0.91%   |
| Dell G5            | 1         | 0.91%   |
| BANGHO MAX         | 1         | 0.91%   |
| ASUS G750JX        | 1         | 0.91%   |
| ASUS ASUS          | 1         | 0.91%   |
| Apple MacBookPro11 | 1         | 0.91%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2023    | 26        | 23.64%  |
| 2022    | 20        | 18.18%  |
| 2021    | 20        | 18.18%  |
| 2019    | 13        | 11.82%  |
| 2020    | 11        | 10%     |
| 2018    | 4         | 3.64%   |
| 2013    | 4         | 3.64%   |
| 2017    | 2         | 1.82%   |
| 2014    | 2         | 1.82%   |
| 2010    | 2         | 1.82%   |
| 2016    | 1         | 0.91%   |
| 2012    | 1         | 0.91%   |
| 2011    | 1         | 0.91%   |
| 2009    | 1         | 0.91%   |
| 2007    | 1         | 0.91%   |
| Unknown | 1         | 0.91%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 110       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 106       | 95.5%   |
| Enabled  | 5         | 4.5%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 110       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 31        | 27.93%  |
| 8.01-16.0   | 31        | 27.93%  |
| 4.01-8.0    | 17        | 15.32%  |
| 16.01-24.0  | 14        | 12.61%  |
| 64.01-256.0 | 8         | 7.21%   |
| 24.01-32.0  | 6         | 5.41%   |
| 3.01-4.0    | 4         | 3.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 31        | 26.27%  |
| 4.01-8.0   | 23        | 19.49%  |
| 2.01-3.0   | 20        | 16.95%  |
| 3.01-4.0   | 18        | 15.25%  |
| 0.51-1.0   | 10        | 8.47%   |
| 8.01-16.0  | 8         | 6.78%   |
| 0.01-0.5   | 6         | 5.08%   |
| 16.01-24.0 | 2         | 1.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 79        | 71.82%  |
| 2      | 28        | 25.45%  |
| 3      | 3         | 2.73%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 100       | 90.91%  |
| Yes       | 10        | 9.09%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 69.09%  |
| No        | 34        | 30.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 99.09%  |
| No        | 1         | 0.91%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 100       | 90.91%  |
| No        | 10        | 9.09%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Notebooks | Percent |
|-----------------|-----------|---------|
| USA             | 21        | 18.92%  |
| Germany         | 14        | 12.61%  |
| Russia          | 12        | 10.81%  |
| France          | 5         | 4.5%    |
| Czechia         | 5         | 4.5%    |
| UK              | 4         | 3.6%    |
| Spain           | 4         | 3.6%    |
| Netherlands     | 4         | 3.6%    |
| Switzerland     | 3         | 2.7%    |
| Poland          | 3         | 2.7%    |
| Italy           | 3         | 2.7%    |
| China           | 3         | 2.7%    |
| Canada          | 3         | 2.7%    |
| Ukraine         | 2         | 1.8%    |
| New Zealand     | 2         | 1.8%    |
| Indonesia       | 2         | 1.8%    |
| Bulgaria        | 2         | 1.8%    |
| Belgium         | 2         | 1.8%    |
| Turkey          | 1         | 0.9%    |
| The Netherlands | 1         | 0.9%    |
| Sweden          | 1         | 0.9%    |
| Slovakia        | 1         | 0.9%    |
| Portugal        | 1         | 0.9%    |
| Paraguay        | 1         | 0.9%    |
| Mexico          | 1         | 0.9%    |
| Malaysia        | 1         | 0.9%    |
| Japan           | 1         | 0.9%    |
| Ireland         | 1         | 0.9%    |
| Iran            | 1         | 0.9%    |
| Greece          | 1         | 0.9%    |
| Finland         | 1         | 0.9%    |
| Chile           | 1         | 0.9%    |
| Brazil          | 1         | 0.9%    |
| Argentina       | 1         | 0.9%    |
| Algeria         | 1         | 0.9%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Moscow                | 4         | 3.36%   |
| St Petersburg         | 3         | 2.52%   |
| New York              | 3         | 2.52%   |
| Madrid                | 3         | 2.52%   |
| Berlin                | 3         | 2.52%   |
| Toulouse              | 2         | 1.68%   |
| Šlapanice            | 2         | 1.68%   |
| Samarinda             | 2         | 1.68%   |
| Cieszyn               | 2         | 1.68%   |
| Christchurch          | 2         | 1.68%   |
| Amsterdam             | 2         | 1.68%   |
| Xiaolou               | 1         | 0.84%   |
| Wetzlar               | 1         | 0.84%   |
| West Orange           | 1         | 0.84%   |
| Vitkov                | 1         | 0.84%   |
| Verviers              | 1         | 0.84%   |
| Turku                 | 1         | 0.84%   |
| Sun Prairie           | 1         | 0.84%   |
| Stockholm             | 1         | 0.84%   |
| St. John's            | 1         | 0.84%   |
| St Laurent des Arbres | 1         | 0.84%   |
| Sofia                 | 1         | 0.84%   |
| Shenzhen              | 1         | 0.84%   |
| Santana de Parnaiba   | 1         | 0.84%   |
| San Antonio           | 1         | 0.84%   |
| Rottweil              | 1         | 0.84%   |
| Rostov-on-Don         | 1         | 0.84%   |
| Rocky Mount           | 1         | 0.84%   |
| Riemerling            | 1         | 0.84%   |
| Ravenstein            | 1         | 0.84%   |
| Quillota              | 1         | 0.84%   |
| Purmerend             | 1         | 0.84%   |
| Pickering             | 1         | 0.84%   |
| Pforzheim             | 1         | 0.84%   |
| Pfaeffikon            | 1         | 0.84%   |
| Pelhrimov             | 1         | 0.84%   |
| Pau                   | 1         | 0.84%   |
| Overijse              | 1         | 0.84%   |
| Olympia               | 1         | 0.84%   |
| Nuremberg             | 1         | 0.84%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 31        | 34     | 22.3%   |
| SK hynix                    | 16        | 18     | 11.51%  |
| Sandisk                     | 16        | 20     | 11.51%  |
| Micron Technology           | 12        | 15     | 8.63%   |
| Intel                       | 9         | 14     | 6.47%   |
| KIOXIA                      | 8         | 10     | 5.76%   |
| Kingston                    | 6         | 11     | 4.32%   |
| Seagate                     | 5         | 5      | 3.6%    |
| WDC                         | 3         | 3      | 2.16%   |
| Phison Electronics          | 3         | 3      | 2.16%   |
| Unknown                     | 2         | 4      | 1.44%   |
| Toshiba                     | 2         | 2      | 1.44%   |
| Kingston Technology Company | 2         | 2      | 1.44%   |
| Crucial                     | 2         | 2      | 1.44%   |
| XPG                         | 1         | 1      | 0.72%   |
| Verbatim                    | 1         | 1      | 0.72%   |
| Union Memory                | 1         | 1      | 0.72%   |
| Transcend                   | 1         | 1      | 0.72%   |
| Teleplan                    | 1         | 1      | 0.72%   |
| StoreJet                    | 1         | 1      | 0.72%   |
| Star                        | 1         | 1      | 0.72%   |
| Solid State Storage         | 1         | 1      | 0.72%   |
| Seagate Technology          | 1         | 1      | 0.72%   |
| Phison                      | 1         | 1      | 0.72%   |
| Micron/Crucial Technology   | 1         | 1      | 0.72%   |
| LITEONIT                    | 1         | 1      | 0.72%   |
| LITEON                      | 1         | 1      | 0.72%   |
| Lexar                       | 1         | 1      | 0.72%   |
| HGST                        | 1         | 1      | 0.72%   |
| Fujitsu                     | 1         | 1      | 0.72%   |
| EYOTA                       | 1         | 1      | 0.72%   |
| Corsair                     | 1         | 1      | 0.72%   |
| China                       | 1         | 2      | 0.72%   |
| ADATA Technology            | 1         | 1      | 0.72%   |
| A-DATA Technology           | 1         | 1      | 0.72%   |
| Unknown                     | 1         | 1      | 0.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 11        | 7.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 9         | 6.29%   |
| Intel SSD 660P Series 1024GB                       | 4         | 2.8%    |
| Sandisk WD_BLACK SN850X 2000GB                     | 3         | 2.1%    |
| Sandisk WD Blue SN550 NVMe SSD 512GB               | 3         | 2.1%    |
| Micron 2400_MTFDKBA1T0QFM 1TB                      | 3         | 2.1%    |
| SK hynix SKHynix_HFS001TDE9X081N 1TB               | 2         | 1.4%    |
| SK hynix PC801 NVMe 1TB                            | 2         | 1.4%    |
| SK hynix BC501 NVMe Solid State Drive 512GB        | 2         | 1.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 2         | 1.4%    |
| Sandisk WD Black SN850 1024GB                      | 2         | 1.4%    |
| Samsung SSD 860 EVO 500GB                          | 2         | 1.4%    |
| Phison E12 NVMe Controller 1TB                     | 2         | 1.4%    |
| KIOXIA KXG80ZNV512G NVMe 512GB                     | 2         | 1.4%    |
| KIOXIA KBG40ZNV512G 512GB                          | 2         | 1.4%    |
| Kingston OM8PCP3512F-AB 512GB                      | 2         | 1.4%    |
| Intel SSDPEKNU512GZ 512GB                          | 2         | 1.4%    |
| XPG GAMMIX S70 2TB                                 | 1         | 0.7%    |
| WDC WDS500G2B0B 500GB SSD                          | 1         | 0.7%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1         | 0.7%    |
| WDC WD Green 2.5 240GB SSD                         | 1         | 0.7%    |
| Verbatim Vi560 S3 256GB SSD                        | 1         | 0.7%    |
| Unknown MMC Card  32GB                             | 1         | 0.7%    |
| Unknown MMC Card  128GB                            | 1         | 0.7%    |
| Union Memory UMIS RPJTJ512MEE1OWX 512GB            | 1         | 0.7%    |
| Transcend TS1TMTE400S 1TB                          | 1         | 0.7%    |
| Toshiba TR200 240GB SSD                            | 1         | 0.7%    |
| Toshiba MQ04ABF100 1TB                             | 1         | 0.7%    |
| Teleplan TP1000G 1TB                               | 1         | 0.7%    |
| StoreJet Transcend 752GB                           | 1         | 0.7%    |
| Star Drive SATA SSD 480GB                          | 1         | 0.7%    |
| Solid State Storage SSSTC CL1-8D256-HP 256GB       | 1         | 0.7%    |
| SK hynix SKHynix_HFS512GDE9X084N 512GB             | 1         | 0.7%    |
| SK hynix SKHynix_HFS512GD9TNG-L5B0B 512GB          | 1         | 0.7%    |
| SK hynix SKHynix_HFS001TEJ9X162N 1024GB            | 1         | 0.7%    |
| SK hynix SKHynix_HFS001TDE9X084N 1024GB            | 1         | 0.7%    |
| SK hynix SHGP31-2000GM 2TB                         | 1         | 0.7%    |
| SK hynix PC801 NVMe 2TB                            | 1         | 0.7%    |
| SK hynix PC711 HFS512GDE9X073N 512GB               | 1         | 0.7%    |
| SK hynix PC601 SED NVMe 1TB                        | 1         | 0.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 5         | 5      | 50%     |
| Toshiba  | 1         | 1      | 10%     |
| Teleplan | 1         | 1      | 10%     |
| StoreJet | 1         | 1      | 10%     |
| HGST     | 1         | 1      | 10%     |
| Fujitsu  | 1         | 1      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 20%     |
| WDC                 | 3         | 3      | 12%     |
| Kingston            | 3         | 5      | 12%     |
| SanDisk             | 2         | 2      | 8%      |
| Crucial             | 2         | 2      | 8%      |
| Verbatim            | 1         | 1      | 4%      |
| Toshiba             | 1         | 1      | 4%      |
| Star                | 1         | 1      | 4%      |
| LITEONIT            | 1         | 1      | 4%      |
| LITEON              | 1         | 1      | 4%      |
| Lexar               | 1         | 1      | 4%      |
| EYOTA               | 1         | 1      | 4%      |
| Corsair             | 1         | 1      | 4%      |
| China               | 1         | 2      | 4%      |
| Unknown             | 1         | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 90        | 124    | 72.58%  |
| SSD  | 22        | 28     | 17.74%  |
| HDD  | 10        | 10     | 8.06%   |
| MMC  | 2         | 4      | 1.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 90        | 124    | 73.77%  |
| SATA | 26        | 34     | 21.31%  |
| SAS  | 4         | 4      | 3.28%   |
| MMC  | 2         | 4      | 1.64%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 19        | 25     | 59.38%  |
| 0.51-1.0   | 11        | 11     | 34.38%  |
| 1.01-2.0   | 2         | 2      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 31        | 26.96%  |
| 501-1000       | 26        | 22.61%  |
| 101-250        | 15        | 13.04%  |
| 1001-2000      | 13        | 11.3%   |
| 1-20           | 11        | 9.57%   |
| Unknown        | 9         | 7.83%   |
| More than 3000 | 7         | 6.09%   |
| 51-100         | 2         | 1.74%   |
| 2001-3000      | 1         | 0.87%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 26        | 22.41%  |
| 1-20           | 25        | 21.55%  |
| 21-50          | 19        | 16.38%  |
| 251-500        | 13        | 11.21%  |
| 501-1000       | 11        | 9.48%   |
| Unknown        | 9         | 7.76%   |
| 51-100         | 8         | 6.9%    |
| More than 3000 | 2         | 1.72%   |
| 2001-3000      | 2         | 1.72%   |
| 1001-2000      | 1         | 0.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                          | Notebooks | Drives | Percent |
|----------------------------------------------------------------|-----------|--------|---------|
| WDC WD Green 2.5 240GB SSD                                     | 1         | 1      | 14.29%  |
| SK hynix PC711 HFS512GDE9X073N 512GB                           | 1         | 1      | 14.29%  |
| SK hynix BC501 NVMe Solid State Drive 512GB                    | 1         | 1      | 14.29%  |
| Seagate ST1000LM024 HN-M101MBB 1TB                             | 1         | 1      | 14.29%  |
| Samsung Electronics NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 1         | 1      | 14.29%  |
| LITEON CV8-8E128-HP 128GB SSD                                  | 1         | 1      | 14.29%  |
| HGST HTS725050A7E630 500GB                                     | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SK hynix            | 2         | 2      | 28.57%  |
| WDC                 | 1         | 1      | 14.29%  |
| Seagate             | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| LITEON              | 1         | 1      | 14.29%  |
| HGST                | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| HGST    | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 3         | 3      | 42.86%  |
| SSD  | 2         | 2      | 28.57%  |
| HDD  | 2         | 2      | 28.57%  |

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
| Works    | 106       | 151    | 89.83%  |
| Malfunc  | 7         | 7      | 5.93%   |
| Detected | 5         | 8      | 4.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 43        | 28.67%  |
| Samsung Electronics            | 26        | 17.33%  |
| SK hynix                       | 16        | 10.67%  |
| SanDisk                        | 14        | 9.33%   |
| AMD                            | 13        | 8.67%   |
| Micron Technology              | 12        | 8%      |
| KIOXIA                         | 8         | 5.33%   |
| Kingston Technology Company    | 6         | 4%      |
| Phison Electronics             | 4         | 2.67%   |
| ADATA Technology               | 2         | 1.33%   |
| Union Memory (Shenzhen)        | 1         | 0.67%   |
| Transcend                      | 1         | 0.67%   |
| Solid State Storage Technology | 1         | 0.67%   |
| Seagate Technology             | 1         | 0.67%   |
| Micron/Crucial Technology      | 1         | 0.67%   |
| INNOGRIT                       | 1         | 0.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 13        | 8.07%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 11        | 6.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 5.59%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 7         | 4.35%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 7         | 4.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 4.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 3.73%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 5         | 3.11%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 4         | 2.48%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 4         | 2.48%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 4         | 2.48%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 2.48%   |
| Intel SSD 660P Series                                                          | 4         | 2.48%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 3         | 1.86%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 3         | 1.86%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.86%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 2         | 1.24%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 1.24%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.24%   |
| Sandisk WD PC SN740 NVMe SSD 512GB (DRAM-less)                                 | 2         | 1.24%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 2         | 1.24%   |
| Phison E18 PCIe4 NVMe Controller                                               | 2         | 1.24%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.24%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 2         | 1.24%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 1.24%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 2         | 1.24%   |
| KIOXIA NVMe SSD Controller XG8                                                 | 2         | 1.24%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 2         | 1.24%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 2         | 1.24%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 2         | 1.24%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 1.24%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.24%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 512GB                          | 1         | 0.62%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)    | 1         | 0.62%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 1         | 0.62%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.62%   |
| Seagate FireCuda 520 SSD                                                       | 1         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 90        | 62.07%  |
| SATA | 36        | 24.83%  |
| RAID | 18        | 12.41%  |
| IDE  | 1         | 0.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 64        | 58.18%  |
| AMD    | 46        | 41.82%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics        | 7         | 6.36%   |
| Intel 12th Gen Core i7-12700H                 | 4         | 3.64%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 3.64%   |
| AMD Ryzen 7 5825U with Radeon Graphics        | 4         | 3.64%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 2.73%   |
| Intel 13th Gen Core i9-13900H                 | 3         | 2.73%   |
| Intel 13th Gen Core i7-1370P                  | 3         | 2.73%   |
| Intel 13th Gen Core i7-13700H                 | 3         | 2.73%   |
| AMD Ryzen 7 7840U w/ Radeon 780M Graphics     | 3         | 2.73%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 2.73%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.82%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.82%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 2         | 1.82%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 1.82%   |
| Intel 12th Gen Core i7-1260P                  | 2         | 1.82%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.82%   |
| AMD Ryzen 7 PRO 6850U with Radeon Graphics    | 2         | 1.82%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.82%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.82%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 2         | 1.82%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.82%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.91%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.91%   |
| Intel Pentium CPU B980 @ 2.40GHz              | 1         | 0.91%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.91%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.91%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.91%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.91%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 0.91%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 0.91%   |
| Intel Core i7-4750HQ CPU @ 2.00GHz            | 1         | 0.91%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.91%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.91%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 0.91%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 0.91%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 0.91%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.91%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 0.91%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 0.91%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 0.91%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Other                | 30        | 27.27%  |
| AMD Ryzen 7          | 26        | 23.64%  |
| Intel Core i7        | 13        | 11.82%  |
| Intel Core i5        | 12        | 10.91%  |
| AMD Ryzen 5          | 11        | 10%     |
| AMD Ryzen 7 PRO      | 6         | 5.45%   |
| Intel Pentium        | 2         | 1.82%   |
| Intel Core i3        | 2         | 1.82%   |
| Intel Celeron        | 2         | 1.82%   |
| AMD Ryzen 9          | 2         | 1.82%   |
| Intel Pentium Silver | 1         | 0.91%   |
| Intel Core i9        | 1         | 0.91%   |
| Intel Core 2 Duo     | 1         | 0.91%   |
| AMD Ryzen 5 PRO      | 1         | 0.91%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 33        | 30%     |
| 8      | 32        | 29.09%  |
| 14     | 13        | 11.82%  |
| 6      | 13        | 11.82%  |
| 2      | 10        | 9.09%   |
| 12     | 4         | 3.64%   |
| 10     | 2         | 1.82%   |
| 24     | 1         | 0.91%   |
| 16     | 1         | 0.91%   |
| 1      | 1         | 0.91%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 110       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 100       | 90.91%  |
| 1      | 9         | 8.18%   |
| 4      | 1         | 0.91%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 110       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 31.53%  |
| 0xb06a2    | 10        | 9.01%   |
| 0x0a50000c | 9         | 8.11%   |
| 0x0a50000d | 7         | 6.31%   |
| 0x0a704103 | 6         | 5.41%   |
| 0x0a404102 | 5         | 4.5%    |
| 0x806ec    | 4         | 3.6%    |
| 0x806c1    | 4         | 3.6%    |
| 0x08600106 | 4         | 3.6%    |
| 0x806ea    | 3         | 2.7%    |
| 0x906a3    | 2         | 1.8%    |
| 0x706a8    | 2         | 1.8%    |
| 0x306c3    | 2         | 1.8%    |
| 0x20652    | 2         | 1.8%    |
| 0x0a601203 | 2         | 1.8%    |
| 0x08608103 | 2         | 1.8%    |
| 0x08108109 | 2         | 1.8%    |
| 0xb0671    | 1         | 0.9%    |
| 0xa0652    | 1         | 0.9%    |
| 0x706e5    | 1         | 0.9%    |
| 0x406e3    | 1         | 0.9%    |
| 0x206a7    | 1         | 0.9%    |
| 0x08608104 | 1         | 0.9%    |
| 0x08608102 | 1         | 0.9%    |
| 0x08600109 | 1         | 0.9%    |
| 0x08600104 | 1         | 0.9%    |
| 0x08600103 | 1         | 0.9%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Alderlake Hybrid | 20        | 18.02%  |
| Unknown          | 19        | 17.12%  |
| Zen 3            | 17        | 15.32%  |
| KabyLake         | 15        | 13.51%  |
| Zen 2            | 7         | 6.31%   |
| TigerLake        | 7         | 6.31%   |
| Zen+             | 5         | 4.5%    |
| Haswell          | 4         | 3.6%    |
| Westmere         | 3         | 2.7%    |
| Icelake          | 3         | 2.7%    |
| Goldmont plus    | 3         | 2.7%    |
| SandyBridge      | 2         | 1.8%    |
| CometLake        | 2         | 1.8%    |
| Skylake          | 1         | 0.9%    |
| Silvermont       | 1         | 0.9%    |
| Core             | 1         | 0.9%    |
| Broadwell        | 1         | 0.9%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 58        | 39.73%  |
| AMD    | 46        | 31.51%  |
| Nvidia | 42        | 28.77%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 11        | 7.28%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 9         | 5.96%   |
| Intel UHD Graphics 620                                                    | 7         | 4.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 7         | 4.64%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 7         | 4.64%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 6         | 3.97%   |
| AMD Phoenix1                                                              | 6         | 3.97%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                           | 5         | 3.31%   |
| AMD Rembrandt [Radeon 680M]                                               | 5         | 3.31%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 3.31%   |
| AMD Barcelo                                                               | 5         | 3.31%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 2.65%   |
| AMD Lucienne                                                              | 4         | 2.65%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 3         | 1.99%   |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                           | 3         | 1.99%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                           | 3         | 1.99%   |
| Intel Raptor Lake-P [UHD Graphics]                                        | 3         | 1.99%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 2         | 1.32%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 1.32%   |
| Nvidia GA107GLM [RTX A1000 6GB Laptop GPU]                                | 2         | 1.32%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 2         | 1.32%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 1.32%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.32%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.32%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.32%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 1.32%   |
| AMD Raphael                                                               | 2         | 1.32%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 0.66%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.66%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.66%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                        | 1         | 0.66%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.66%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                   | 1         | 0.66%   |
| Nvidia GT216GLM [Quadro FX 880M]                                          | 1         | 0.66%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.66%   |
| Nvidia GP108GLM [Quadro P520]                                             | 1         | 0.66%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                  | 1         | 0.66%   |
| Nvidia GN20-P0-R-K2 [GeForce RTX 3050 6GB Laptop GPU]                     | 1         | 0.66%   |
| Nvidia GM108M [GeForce MX130]                                             | 1         | 0.66%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 32        | 28.83%  |
| 1 x AMD        | 32        | 28.83%  |
| Intel + Nvidia | 25        | 22.52%  |
| AMD + Nvidia   | 10        | 9.01%   |
| 1 x Nvidia     | 7         | 6.31%   |
| 2 x AMD        | 3         | 2.7%    |
| 2 x Intel      | 1         | 0.9%    |
| Intel + AMD    | 1         | 0.9%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 77        | 68.14%  |
| Proprietary | 31        | 27.43%  |
| Unknown     | 5         | 4.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 54.05%  |
| 0.01-0.5   | 25        | 22.52%  |
| 1.01-2.0   | 11        | 9.91%   |
| 0.51-1.0   | 5         | 4.5%    |
| 7.01-8.0   | 3         | 2.7%    |
| 5.01-6.0   | 3         | 2.7%    |
| 3.01-4.0   | 3         | 2.7%    |
| 8.01-16.0  | 1         | 0.9%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 29        | 21.17%  |
| BOE                     | 21        | 15.33%  |
| Chimei Innolux          | 20        | 14.6%   |
| LG Display              | 13        | 9.49%   |
| Samsung Electronics     | 10        | 7.3%    |
| Goldstar                | 7         | 5.11%   |
| Dell                    | 7         | 5.11%   |
| Sharp                   | 6         | 4.38%   |
| PANDA                   | 3         | 2.19%   |
| Lenovo                  | 3         | 2.19%   |
| CSO                     | 3         | 2.19%   |
| TMX                     | 2         | 1.46%   |
| BenQ                    | 2         | 1.46%   |
| ViewSonic               | 1         | 0.73%   |
| Toshiba                 | 1         | 0.73%   |
| Philips                 | 1         | 0.73%   |
| NEC Computers           | 1         | 0.73%   |
| Iiyama                  | 1         | 0.73%   |
| HUAWEI                  | 1         | 0.73%   |
| HKC                     | 1         | 0.73%   |
| Chi Mei Optoelectronics | 1         | 0.73%   |
| ASUSTek Computer        | 1         | 0.73%   |
| Apple                   | 1         | 0.73%   |
| AOC                     | 1         | 0.73%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                 | 6         | 4.29%   |
| Samsung Electronics LCD Monitor SDC4180 2880x1620 344x194mm 15.5-inch | 2         | 1.43%   |
| LG Display LCD Monitor LGD06CA 1920x1080 309x174mm 14.0-inch          | 2         | 1.43%   |
| Goldstar HDR 4K GSM774F 3840x2160 697x392mm 31.5-inch                 | 2         | 1.43%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 2         | 1.43%   |
| Dell U2410 DELF016 1920x1200 520x320mm 24.0-inch                      | 2         | 1.43%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 1.43%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 2         | 1.43%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.43%   |
| AU Optronics LCD Monitor AUOF99A 1920x1200 301x188mm 14.0-inch        | 2         | 1.43%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 2         | 1.43%   |
| AU Optronics LCD Monitor AUO2992 1920x1080 344x193mm 15.5-inch        | 2         | 1.43%   |
| ViewSonic VX2458 Series VSC36AF 1920x1080 521x293mm 23.5-inch         | 1         | 0.71%   |
| Toshiba TV TSB0206 1920x1080                                          | 1         | 0.71%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 0.71%   |
| TMX TL140ADXP04-0 TMX0003 2560x1600 301x188mm 14.0-inch               | 1         | 0.71%   |
| Sharp LQ173M1JW12 SHP1563 1920x1080 380x210mm 17.1-inch               | 1         | 0.71%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch               | 1         | 0.71%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.71%   |
| Sharp LCD Monitor SHP1548 1920x1200 288x180mm 13.4-inch               | 1         | 0.71%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch               | 1         | 0.71%   |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch               | 1         | 0.71%   |
| Samsung Electronics SyncMaster SAM01D0 1600x1200 432x324mm 21.3-inch  | 1         | 0.71%   |
| Samsung Electronics S22C200 SAM09B6 1920x1080 477x268mm 21.5-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4178 3200x2000 344x215mm 16.0-inch | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch | 1         | 0.71%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 1         | 0.71%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch               | 1         | 0.71%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 0.71%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.71%   |
| NEC Computers LCD190V NEC66D3 1280x1024 376x301mm 19.0-inch           | 1         | 0.71%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch           | 1         | 0.71%   |
| LG Display LCD Monitor LGD06FF 1920x1080 344x194mm 15.5-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD06C4 1920x1080 294x165mm 13.3-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD0685 1920x1080 309x174mm 14.0-inch          | 1         | 0.71%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 61        | 49.59%  |
| 1920x1200 (WUXGA) | 14        | 11.38%  |
| 1366x768 (WXGA)   | 10        | 8.13%   |
| 2256x1504         | 7         | 5.69%   |
| 3840x2160 (4K)    | 6         | 4.88%   |
| 2560x1600         | 6         | 4.88%   |
| 2560x1440 (QHD)   | 5         | 4.07%   |
| 3200x2000         | 2         | 1.63%   |
| 2880x1620         | 2         | 1.63%   |
| 3840x2400         | 1         | 0.81%   |
| 3456x2160         | 1         | 0.81%   |
| 3440x1440         | 1         | 0.81%   |
| 2880x1800         | 1         | 0.81%   |
| 2560x1080         | 1         | 0.81%   |
| 1600x900 (HD+)    | 1         | 0.81%   |
| 1600x1200         | 1         | 0.81%   |
| 1440x900 (WXGA+)  | 1         | 0.81%   |
| 1280x800 (WXGA)   | 1         | 0.81%   |
| 1280x1024 (SXGA)  | 1         | 0.81%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 45        | 32.61%  |
| 13     | 25        | 18.12%  |
| 14     | 21        | 15.22%  |
| 16     | 12        | 8.7%    |
| 24     | 7         | 5.07%   |
| 21     | 6         | 4.35%   |
| 17     | 6         | 4.35%   |
| 23     | 5         | 3.62%   |
| 31     | 3         | 2.17%   |
| 34     | 2         | 1.45%   |
| 27     | 2         | 1.45%   |
| 74     | 1         | 0.72%   |
| 36     | 1         | 0.72%   |
| 19     | 1         | 0.72%   |
| 18     | 1         | 0.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 87        | 63.5%   |
| 501-600     | 14        | 10.22%  |
| 201-300     | 14        | 10.22%  |
| 351-400     | 9         | 6.57%   |
| 401-500     | 6         | 4.38%   |
| 701-800     | 3         | 2.19%   |
| 601-700     | 3         | 2.19%   |
| 1501-2000   | 1         | 0.73%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 81        | 67.5%   |
| 16/10 | 28        | 23.33%  |
| 3/2   | 7         | 5.83%   |
| 21/9  | 2         | 1.67%   |
| 5/4   | 1         | 0.83%   |
| 4/3   | 1         | 0.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 44        | 31.88%  |
| 81-90          | 39        | 28.26%  |
| 201-250        | 13        | 9.42%   |
| 111-120        | 13        | 9.42%   |
| 71-80          | 7         | 5.07%   |
| 121-130        | 6         | 4.35%   |
| 351-500        | 5         | 3.62%   |
| 251-300        | 4         | 2.9%    |
| 301-350        | 2         | 1.45%   |
| 151-200        | 2         | 1.45%   |
| More than 1000 | 1         | 0.72%   |
| 141-150        | 1         | 0.72%   |
| 501-1000       | 1         | 0.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 69        | 51.11%  |
| 161-240       | 26        | 19.26%  |
| 101-120       | 21        | 15.56%  |
| 51-100        | 14        | 10.37%  |
| More than 240 | 4         | 2.96%   |
| 1-50          | 1         | 0.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 88        | 77.19%  |
| 2     | 19        | 16.67%  |
| 3     | 6         | 5.26%   |
| 0     | 1         | 0.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 65        | 38.46%  |
| Realtek Semiconductor | 62        | 36.69%  |
| MediaTek              | 18        | 10.65%  |
| Qualcomm              | 4         | 2.37%   |
| Broadcom              | 4         | 2.37%   |
| ASIX Electronics      | 4         | 2.37%   |
| Qualcomm Atheros      | 3         | 1.78%   |
| Xiaomi                | 2         | 1.18%   |
| Samsung Electronics   | 2         | 1.18%   |
| Ralink Technology     | 2         | 1.18%   |
| Lenovo                | 2         | 1.18%   |
| Texas Instruments     | 1         | 0.59%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 44        | 21.89%  |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 10        | 4.98%   |
| Intel Wi-Fi 6 AX200                                                    | 10        | 4.98%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 8         | 3.98%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 7         | 3.48%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 7         | 3.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 2.99%   |
| Intel Wireless 8265 / 8275                                             | 6         | 2.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 5         | 2.49%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5         | 2.49%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 4         | 1.99%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 1.99%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 3         | 1.49%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 3         | 1.49%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 3         | 1.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 1.49%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 1.49%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 1.49%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 3         | 1.49%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.49%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 1%      |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 1%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 1%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2         | 1%      |
| Intel Tiger Lake PCH CNVi WiFi                                         | 2         | 1%      |
| Intel Gemini Lake PCH CNVi WiFi                                        | 2         | 1%      |
| Intel Ethernet Connection I217-LM                                      | 2         | 1%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 1%      |
| Intel Centrino Ultimate-N 6300                                         | 2         | 1%      |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.5%    |
| Texas Instruments XDS2xx USB Emulator - Composit                       | 1         | 0.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1         | 0.5%    |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 1         | 0.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1         | 0.5%    |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 0.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 0.5%    |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.5%    |
| Realtek 802.11n WLAN Adapter                                           | 1         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 65        | 57.52%  |
| Realtek Semiconductor | 20        | 17.7%   |
| MediaTek              | 17        | 15.04%  |
| Qualcomm              | 4         | 3.54%   |
| Broadcom              | 3         | 2.65%   |
| Ralink Technology     | 2         | 1.77%   |
| Qualcomm Atheros      | 2         | 1.77%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 10        | 8.85%   |
| Intel Wi-Fi 6 AX200                                           | 10        | 8.85%   |
| Intel Raptor Lake PCH CNVi WiFi                               | 8         | 7.08%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 7         | 6.19%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 7         | 6.19%   |
| Intel Wireless 8265 / 8275                                    | 6         | 5.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 5         | 4.42%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 5         | 4.42%   |
| Qualcomm QCNFA765 Wireless Network Adapter                    | 4         | 3.54%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 3         | 2.65%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 3         | 2.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 3         | 2.65%   |
| Intel Wi-Fi 6 AX201                                           | 3         | 2.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 3         | 2.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 2         | 1.77%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 1.77%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 2         | 1.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 1.77%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 1.77%   |
| Intel Centrino Ultimate-N 6300                                | 2         | 1.77%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 1         | 0.88%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller   | 1         | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 1         | 0.88%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 0.88%   |
| Realtek 802.11n WLAN Adapter                                  | 1         | 0.88%   |
| Ralink RT5572 Wireless Adapter                                | 1         | 0.88%   |
| Ralink RT5370 Wireless Adapter                                | 1         | 0.88%   |
| MediaTek WiFi                                                 | 1         | 0.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1         | 0.88%   |
| Intel Wireless 8260                                           | 1         | 0.88%   |
| Intel Wireless 7265                                           | 1         | 0.88%   |
| Intel Wireless 7260                                           | 1         | 0.88%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 1         | 0.88%   |
| Intel Raptor Lake-S PCH CNVi WiFi                             | 1         | 0.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection         | 1         | 0.88%   |
| Intel Centrino Wireless-N 2230                                | 1         | 0.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 1         | 0.88%   |
| Intel Centrino Advanced-N 6200                                | 1         | 0.88%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]          | 1         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 55        | 65.48%  |
| Intel                 | 16        | 19.05%  |
| ASIX Electronics      | 4         | 4.76%   |
| Xiaomi                | 2         | 2.38%   |
| Samsung Electronics   | 2         | 2.38%   |
| Lenovo                | 2         | 2.38%   |
| Qualcomm Atheros      | 1         | 1.19%   |
| MediaTek              | 1         | 1.19%   |
| Broadcom              | 1         | 1.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 44        | 50.57%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 6.9%    |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 4.6%    |
| Realtek USB 10/100/1G/2.5G LAN                                         | 3         | 3.45%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 3.45%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 3.45%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 2.3%    |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 2.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 2.3%    |
| Intel Ethernet Connection I217-LM                                      | 2         | 2.3%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.15%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 1.15%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 1.15%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.15%   |
| MediaTek File-CD Gadget                                                | 1         | 1.15%   |
| Lenovo USB-C Dock Ethernet                                             | 1         | 1.15%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 1         | 1.15%   |
| Intel I210 Gigabit Network Connection                                  | 1         | 1.15%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.15%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.15%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 1.15%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 1.15%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.15%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 1.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1         | 1.15%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 1         | 1.15%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 109       | 58.6%   |
| Ethernet | 76        | 40.86%  |
| Modem    | 1         | 0.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 91        | 79.13%  |
| Ethernet | 24        | 20.87%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 66        | 60%     |
| 1     | 41        | 37.27%  |
| 0     | 2         | 1.82%   |
| 3     | 1         | 0.91%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 81        | 71.68%  |
| Yes  | 32        | 28.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 55        | 55%     |
| Realtek Semiconductor | 13        | 13%     |
| IMC Networks          | 9         | 9%      |
| Foxconn / Hon Hai     | 6         | 6%      |
| MediaTek              | 4         | 4%      |
| Lite-On Technology    | 4         | 4%      |
| USI                   | 3         | 3%      |
| Broadcom              | 2         | 2%      |
| Realtek               | 1         | 1%      |
| Foxconn International | 1         | 1%      |
| Dell                  | 1         | 1%      |
| Apple                 | 1         | 1%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                            | 13        | 13%     |
| Realtek Bluetooth Radio                           | 10        | 10%     |
| Intel AX201 Bluetooth                             | 10        | 10%     |
| Intel Bluetooth wireless interface                | 8         | 8%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 8         | 8%      |
| Intel AX210 Bluetooth                             | 7         | 7%      |
| Intel AX200 Bluetooth                             | 7         | 7%      |
| Foxconn / Hon Hai Wireless_Device                 | 5         | 5%      |
| MediaTek Wireless_Device                          | 4         | 4%      |
| USI Bluetooth Device                              | 3         | 3%      |
| Realtek  Bluetooth 4.2 Adapter                    | 3         | 3%      |
| Lite-On Wireless_Device                           | 3         | 3%      |
| IMC Networks Wireless_Device                      | 3         | 3%      |
| IMC Networks Bluetooth Radio                      | 3         | 3%      |
| IMC Networks Bluetooth Device                     | 2         | 2%      |
| Broadcom BCM2045B (BDC-2.1)                       | 2         | 2%      |
| Realtek Bluetooth Radio                           | 1         | 1%      |
| Lite-On Bluetooth Device                          | 1         | 1%      |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 1%      |
| Intel Centrino Bluetooth Wireless Transceiver     | 1         | 1%      |
| IMC Networks BCM20702A0                           | 1         | 1%      |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 1%      |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth       | 1         | 1%      |
| Dell DW375 Bluetooth Module                       | 1         | 1%      |
| Apple Bluetooth Host Controller                   | 1         | 1%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 64        | 41.56%  |
| AMD                   | 46        | 29.87%  |
| Nvidia                | 25        | 16.23%  |
| SteelSeries ApS       | 2         | 1.3%    |
| Logitech              | 2         | 1.3%    |
| Lenovo                | 2         | 1.3%    |
| JBL                   | 2         | 1.3%    |
| Hewlett-Packard       | 2         | 1.3%    |
| Creative Technology   | 2         | 1.3%    |
| C-Media Electronics   | 2         | 1.3%    |
| Realtek Semiconductor | 1         | 0.65%   |
| Razer USA             | 1         | 0.65%   |
| Plantronics           | 1         | 0.65%   |
| No brand              | 1         | 0.65%   |
| Kingston Technology   | 1         | 0.65%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                              | 46        | 22.89%  |
| AMD Renoir Radeon High Definition Audio Controller                  | 25        | 12.44%  |
| Nvidia Audio device                                                 | 13        | 6.47%   |
| Intel Raptor Lake-P/U/H cAVS                                        | 13        | 6.47%   |
| AMD Rembrandt Radeon High Definition Audio Controller               | 11        | 5.47%   |
| Intel Sunrise Point-LP HD Audio                                     | 8         | 3.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 7         | 3.48%   |
| Intel Alder Lake PCH-P High Definition Audio Controller             | 7         | 3.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 5         | 2.49%   |
| Nvidia GA104 High Definition Audio Controller                       | 4         | 1.99%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 4         | 1.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 4         | 1.99%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 3         | 1.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio            | 3         | 1.49%   |
| Nvidia GK106 HDMI Audio Controller                                  | 2         | 1%      |
| JBL Quantum 400                                                     | 2         | 1%      |
| Intel Tiger Lake-H HD Audio Controller                              | 2         | 1%      |
| Intel Comet Lake PCH-LP cAVS                                        | 2         | 1%      |
| Intel Comet Lake PCH cAVS                                           | 2         | 1%      |
| Intel Cannon Lake PCH cAVS                                          | 2         | 1%      |
| AMD Navi 21/23 HDMI/DP Audio Controller                             | 2         | 1%      |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                       | 1         | 0.5%    |
| SteelSeries ApS Arctis Nova Pro Wireless                            | 1         | 0.5%    |
| Realtek Semiconductor USB Audio                                     | 1         | 0.5%    |
| Razer USA Kraken Tournament Edition                                 | 1         | 0.5%    |
| Plantronics EncorePro 545 USB                                       | 1         | 0.5%    |
| Nvidia TU116 High Definition Audio Controller                       | 1         | 0.5%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 1         | 0.5%    |
| Nvidia TU106 High Definition Audio Controller                       | 1         | 0.5%    |
| Nvidia GT216 HDMI Audio Controller                                  | 1         | 0.5%    |
| Nvidia GP104 High Definition Audio Controller                       | 1         | 0.5%    |
| Nvidia GA106 High Definition Audio Controller                       | 1         | 0.5%    |
| No brand CalDigit Thunderbolt 3 Audio                               | 1         | 0.5%    |
| Logitech G435 Wireless Gaming Headset                               | 1         | 0.5%    |
| Logitech G432 Gaming Headset                                        | 1         | 0.5%    |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                           | 1         | 0.5%    |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                        | 1         | 0.5%    |
| Kingston Technology HyperX 7.1 Audio                                | 1         | 0.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 0.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller             | 1         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 42        | 33.07%  |
| SK hynix            | 22        | 17.32%  |
| Micron Technology   | 18        | 14.17%  |
| Crucial             | 12        | 9.45%   |
| Kingston            | 8         | 6.3%    |
| A-DATA Technology   | 5         | 3.94%   |
| Unknown             | 4         | 3.15%   |
| Elpida              | 3         | 2.36%   |
| Corsair             | 3         | 2.36%   |
| Unknown (ABCD)      | 2         | 1.57%   |
| Ramaxel Technology  | 2         | 1.57%   |
| Unknown             | 1         | 0.79%   |
| Team                | 1         | 0.79%   |
| Kimtigo             | 1         | 0.79%   |
| G.Skill             | 1         | 0.79%   |
| CSX                 | 1         | 0.79%   |
| Apacer              | 1         | 0.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 5         | 3.7%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 4         | 2.96%   |
| Unknown                                                             | 4         | 2.96%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 3         | 2.22%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 2.22%   |
| Crucial RAM CT16G4SFRA32A.C8FE 16GB SODIMM DDR4 3200MT/s            | 3         | 2.22%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 1.48%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                        | 2         | 1.48%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                        | 2         | 1.48%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.48%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 1.48%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.48%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 1.48%   |
| Samsung RAM M471A1G44BB0-CWE 8192MB Row Of Chips DDR4 3200MT/s      | 2         | 1.48%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 1.48%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s             | 2         | 1.48%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s             | 2         | 1.48%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB SODIMM LPDDR5 6400MT/s          | 2         | 1.48%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                | 2         | 1.48%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s                | 2         | 1.48%   |
| Kingston RAM KF556S40-32 32GB SODIMM DDR5 5600MT/s                  | 2         | 1.48%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s               | 2         | 1.48%   |
| Crucial RAM CT16G4SFRA32A.M16FR 16GB SODIMM DDR4 3200MT/s           | 2         | 1.48%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 2         | 1.48%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                         | 1         | 0.74%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s                | 1         | 0.74%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s                        | 1         | 0.74%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                | 1         | 0.74%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2400MT/s                       | 1         | 0.74%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.74%   |
| SK hynix RAM HMCG78AGBSA095N 16GB SODIMM DDR5 5600MT/s              | 1         | 0.74%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s              | 1         | 0.74%   |
| SK hynix RAM HMCG66AGBSA092N 8GB SODIMM DDR5 5600MT/s               | 1         | 0.74%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 0.74%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 0.74%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 0.74%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 1         | 0.74%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s          | 1         | 0.74%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8192MB SODIMM LPDDR4 4266MT/s       | 1         | 0.74%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                         | 1         | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 63        | 58.88%  |
| DDR5   | 17        | 15.89%  |
| DDR3   | 12        | 11.21%  |
| LPDDR5 | 8         | 7.48%   |
| LPDDR4 | 5         | 4.67%   |
| LPDDR3 | 1         | 0.93%   |
| DDR2   | 1         | 0.93%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 96        | 89.72%  |
| Row Of Chips | 11        | 10.28%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 55        | 45.08%  |
| 16384 | 28        | 22.95%  |
| 4096  | 20        | 16.39%  |
| 32768 | 14        | 11.48%  |
| 2048  | 4         | 3.28%   |
| 49152 | 1         | 0.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 44        | 38.26%  |
| 2667  | 13        | 11.3%   |
| 5600  | 9         | 7.83%   |
| 4800  | 9         | 7.83%   |
| 2400  | 9         | 7.83%   |
| 6400  | 7         | 6.09%   |
| 1600  | 7         | 6.09%   |
| 3266  | 5         | 4.35%   |
| 1334  | 3         | 2.61%   |
| 4266  | 2         | 1.74%   |
| 1333  | 2         | 1.74%   |
| 8400  | 1         | 0.87%   |
| 7500  | 1         | 0.87%   |
| 4267  | 1         | 0.87%   |
| 2133  | 1         | 0.87%   |
| 667   | 1         | 0.87%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 21        | 22.11%  |
| IMC Networks                           | 17        | 17.89%  |
| Realtek Semiconductor                  | 7         | 7.37%   |
| Quanta                                 | 7         | 7.37%   |
| Microdia                               | 7         | 7.37%   |
| Bison Electronics                      | 7         | 7.37%   |
| Luxvisions Innotech Limited            | 6         | 6.32%   |
| Sonix Technology                       | 4         | 4.21%   |
| Lite-On Technology                     | 4         | 4.21%   |
| Syntek                                 | 2         | 2.11%   |
| Sunplus Innovation Technology          | 2         | 2.11%   |
| Logitech                               | 2         | 2.11%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.11%   |
| Silicon Motion                         | 1         | 1.05%   |
| Ricoh                                  | 1         | 1.05%   |
| Lenovo                                 | 1         | 1.05%   |
| kingcome                               | 1         | 1.05%   |
| Hy-UXGA(B5M2)-Camera                   | 1         | 1.05%   |
| Goodong                                | 1         | 1.05%   |
| Acer                                   | 1         | 1.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 11        | 11.58%  |
| Realtek Laptop Camera                                | 5         | 5.26%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 5         | 5.26%   |
| Lite-On HP HD Camera                                 | 4         | 4.21%   |
| IMC Networks Integrated Camera                       | 4         | 4.21%   |
| Quanta HD User Facing                                | 3         | 3.16%   |
| Microdia Integrated_Webcam_HD                        | 3         | 3.16%   |
| Bison Integrated Camera                              | 3         | 3.16%   |
| Syntek Integrated Camera                             | 2         | 2.11%   |
| Sonix USB2.0 HD UVC WebCam                           | 2         | 2.11%   |
| Sonix USB2.0 FHD UVC WebCam                          | 2         | 2.11%   |
| Quanta HP TrueVision HD Camera                       | 2         | 2.11%   |
| Microdia USB 2.0 Camera                              | 2         | 2.11%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 2.11%   |
| Luxvisions Innotech Limited HP HD Camera             | 2         | 2.11%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 2         | 2.11%   |
| Chicony HP Wide Vision HD Camera                     | 2         | 2.11%   |
| Chicony HP HD Camera                                 | 2         | 2.11%   |
| Chicony HD User Facing                               | 2         | 2.11%   |
| Bison HD Webcam                                      | 2         | 2.11%   |
| Sunplus XiaoMi USB 2.0 Webcam                        | 1         | 1.05%   |
| Sunplus Integrated_Webcam_FHD                        | 1         | 1.05%   |
| Silicon Motion 300k Pixel Camera                     | 1         | 1.05%   |
| Ricoh HD Webcam                                      | 1         | 1.05%   |
| Realtek Lenovo EasyCamera                            | 1         | 1.05%   |
| Realtek Bluetooth Radio                              | 1         | 1.05%   |
| Quanta USB2.0 HD UVC WebCam                          | 1         | 1.05%   |
| Quanta HP Wide Vision HD Camera                      | 1         | 1.05%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 1         | 1.05%   |
| Microdia Integrated_Webcam_FHD                       | 1         | 1.05%   |
| Luxvisions Innotech Limited Integrated Camera        | 1         | 1.05%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 1         | 1.05%   |
| Logitech HD Webcam C525                              | 1         | 1.05%   |
| Logitech BRIO Ultra HD Webcam                        | 1         | 1.05%   |
| Lenovo Integrated Webcam [R5U877]                    | 1         | 1.05%   |
| kingcome HD Webcam                                   | 1         | 1.05%   |
| IMC Networks USB2.0 UVC HD Webcam                    | 1         | 1.05%   |
| IMC Networks USB2.0 HD IR UVC WebCam                 | 1         | 1.05%   |
| IMC Networks USB2.0 FHD UVC WebCam                   | 1         | 1.05%   |
| IMC Networks ov9734_azurewave_camera                 | 1         | 1.05%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 10        | 55.56%  |
| Validity Sensors                   | 3         | 16.67%  |
| Shenzhen Goodix Technology         | 3         | 16.67%  |
| Realtek USB2.0 Finger Print Bridge | 1         | 5.56%   |
| Elan Microelectronics              | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 33.33%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 11.11%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 11.11%  |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 11.11%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.56%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 5.56%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 5.56%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 5.56%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 5.56%   |
| Elan ELAN:Fingerprint                                                      | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 36.36%  |
| Alcor Micro | 4         | 36.36%  |
| OmniKey     | 1         | 9.09%   |
| O2 Micro    | 1         | 9.09%   |
| Lenovo      | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 4         | 36.36%  |
| Broadcom BCM5880 Secure Applications Processor | 2         | 18.18%  |
| Broadcom 58200                                 | 2         | 18.18%  |
| OmniKey CardMan 3021 / 3121                    | 1         | 9.09%   |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 9.09%   |
| Lenovo Integrated Smart Card Reader            | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 56        | 47.86%  |
| 1     | 27        | 23.08%  |
| 2     | 12        | 10.26%  |
| 5     | 8         | 6.84%   |
| 3     | 8         | 6.84%   |
| 4     | 4         | 3.42%   |
| 6     | 2         | 1.71%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 18        | 14.63%  |
| Bluetooth                | 16        | 13.01%  |
| Graphics card            | 15        | 12.2%   |
| Camera                   | 15        | 12.2%   |
| Multimedia controller    | 12        | 9.76%   |
| Communication controller | 12        | 9.76%   |
| Net/wireless             | 11        | 8.94%   |
| Chipcard                 | 11        | 8.94%   |
| Card reader              | 4         | 3.25%   |
| Network                  | 3         | 2.44%   |
| Sound                    | 2         | 1.63%   |
| Firewire controller      | 2         | 1.63%   |
| Storage/ata              | 1         | 0.81%   |
| Net/ethernet             | 1         | 0.81%   |


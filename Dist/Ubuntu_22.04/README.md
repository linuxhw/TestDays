Ubuntu 22.04 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Ubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Ubuntu_22.04/Notebook/README.md).

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

Total: 13295

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | F2A85-V PRO                 | Desktop     | [43991c533e](https://linux-hardware.org/?probe=43991c533e) | Jun 10, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [b9eb9677f5](https://linux-hardware.org/?probe=b9eb9677f5) | Jun 10, 2023 |
| Lenovo        | ThinkPad T480 20L50010US    | Notebook    | [aa44c2c8b9](https://linux-hardware.org/?probe=aa44c2c8b9) | Jun 10, 2023 |
| Acer          | Aspire E5-574G              | Notebook    | [8ca78da386](https://linux-hardware.org/?probe=8ca78da386) | Jun 10, 2023 |
| Intel         | DH55TC AAE70932-302         | Desktop     | [6090a53f8a](https://linux-hardware.org/?probe=6090a53f8a) | Jun 10, 2023 |
| Beelink       | Gemini X                    | Notebook    | [adcb5e774d](https://linux-hardware.org/?probe=adcb5e774d) | Jun 10, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d6be89e452](https://linux-hardware.org/?probe=d6be89e452) | Jun 10, 2023 |
| Lenovo        | ThinkPad T480 20L50010US    | Notebook    | [398d708c85](https://linux-hardware.org/?probe=398d708c85) | Jun 10, 2023 |
| HP            | EliteBook 1040 G4           | Notebook    | [98aa06475b](https://linux-hardware.org/?probe=98aa06475b) | Jun 10, 2023 |
| Lenovo        | ThinkPad X240 20AMS5XY00    | Notebook    | [3b98c592e0](https://linux-hardware.org/?probe=3b98c592e0) | Jun 10, 2023 |
| Gigabyte      | B650M GAMING X AX           | Desktop     | [5affc12294](https://linux-hardware.org/?probe=5affc12294) | Jun 10, 2023 |
| Dell          | Latitude 9420               | Convertible | [354adf0653](https://linux-hardware.org/?probe=354adf0653) | Jun 10, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [421ff52b0b](https://linux-hardware.org/?probe=421ff52b0b) | Jun 10, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [c23450b0df](https://linux-hardware.org/?probe=c23450b0df) | Jun 10, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [1f8c419c47](https://linux-hardware.org/?probe=1f8c419c47) | Jun 10, 2023 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [873975925d](https://linux-hardware.org/?probe=873975925d) | Jun 10, 2023 |
| Pegatron      | Benicia                     | Desktop     | [c57fee6ea0](https://linux-hardware.org/?probe=c57fee6ea0) | Jun 10, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [6adee93e47](https://linux-hardware.org/?probe=6adee93e47) | Jun 10, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [e3cb803f4e](https://linux-hardware.org/?probe=e3cb803f4e) | Jun 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7c9662b5eb](https://linux-hardware.org/?probe=7c9662b5eb) | Jun 10, 2023 |
| Unknown       | Unknown                     | Tablet      | [f9d086b77c](https://linux-hardware.org/?probe=f9d086b77c) | Jun 10, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [47d37facfc](https://linux-hardware.org/?probe=47d37facfc) | Jun 10, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [0c4db9b922](https://linux-hardware.org/?probe=0c4db9b922) | Jun 10, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [86f646e00f](https://linux-hardware.org/?probe=86f646e00f) | Jun 10, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [1bb9178df2](https://linux-hardware.org/?probe=1bb9178df2) | Jun 10, 2023 |
| Intel         | NUC11ATBC2 M53055-202       | Mini pc     | [81aee70d12](https://linux-hardware.org/?probe=81aee70d12) | Jun 10, 2023 |
| Exo           | Smart Serie LT              | Notebook    | [bbecad1cea](https://linux-hardware.org/?probe=bbecad1cea) | Jun 10, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f502f89e9d](https://linux-hardware.org/?probe=f502f89e9d) | Jun 10, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [fc025a599d](https://linux-hardware.org/?probe=fc025a599d) | Jun 10, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [f32fbdf6ea](https://linux-hardware.org/?probe=f32fbdf6ea) | Jun 10, 2023 |
| HP            | ProBook 6360b               | Notebook    | [cdef37cb2d](https://linux-hardware.org/?probe=cdef37cb2d) | Jun 09, 2023 |
| Dell          | 0PU052                      | Desktop     | [84db4b658c](https://linux-hardware.org/?probe=84db4b658c) | Jun 09, 2023 |
| Dell          | 0PU052                      | Desktop     | [145d296b59](https://linux-hardware.org/?probe=145d296b59) | Jun 09, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [a4d08407bb](https://linux-hardware.org/?probe=a4d08407bb) | Jun 09, 2023 |
| Dell          | Latitude 9420               | Convertible | [593403cb67](https://linux-hardware.org/?probe=593403cb67) | Jun 09, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [a1877cb5b3](https://linux-hardware.org/?probe=a1877cb5b3) | Jun 09, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [15185698e7](https://linux-hardware.org/?probe=15185698e7) | Jun 09, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [6f26f51ef6](https://linux-hardware.org/?probe=6f26f51ef6) | Jun 09, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9cb24f9445](https://linux-hardware.org/?probe=9cb24f9445) | Jun 09, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [fb9e2f9fc8](https://linux-hardware.org/?probe=fb9e2f9fc8) | Jun 09, 2023 |
| HP            | ProBook 4510s               | Notebook    | [43a29ea83e](https://linux-hardware.org/?probe=43a29ea83e) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [92fd36b27a](https://linux-hardware.org/?probe=92fd36b27a) | Jun 09, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [c93d52343c](https://linux-hardware.org/?probe=c93d52343c) | Jun 09, 2023 |
| Google        | Akali 360                   | Notebook    | [1f7d5f8bc5](https://linux-hardware.org/?probe=1f7d5f8bc5) | Jun 09, 2023 |
| Dell          | Latitude E7470              | Notebook    | [c5457da74f](https://linux-hardware.org/?probe=c5457da74f) | Jun 09, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [adcb3b193a](https://linux-hardware.org/?probe=adcb3b193a) | Jun 09, 2023 |
| IBM           | 00J6244 08                  | Server      | [1543d47492](https://linux-hardware.org/?probe=1543d47492) | Jun 09, 2023 |
| MSI           | H81I                        | Desktop     | [c7c19346a2](https://linux-hardware.org/?probe=c7c19346a2) | Jun 09, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [aa0b439e8d](https://linux-hardware.org/?probe=aa0b439e8d) | Jun 09, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [5833483fe2](https://linux-hardware.org/?probe=5833483fe2) | Jun 09, 2023 |
| Lenovo        | ThinkPad T460s 20FAS11X0... | Notebook    | [23568da401](https://linux-hardware.org/?probe=23568da401) | Jun 09, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [40f18ae1f4](https://linux-hardware.org/?probe=40f18ae1f4) | Jun 09, 2023 |
| ECS           | H81H3-M4                    | Desktop     | [b457e63434](https://linux-hardware.org/?probe=b457e63434) | Jun 09, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [09344fa63e](https://linux-hardware.org/?probe=09344fa63e) | Jun 09, 2023 |
| Unknown       | GSUO H61V10C                | Desktop     | [0daf816953](https://linux-hardware.org/?probe=0daf816953) | Jun 09, 2023 |
| HP            | 2B35                        | Desktop     | [5921b94b60](https://linux-hardware.org/?probe=5921b94b60) | Jun 09, 2023 |
| HP            | Elite Dragonfly G2          | Convertible | [f36fbdace7](https://linux-hardware.org/?probe=f36fbdace7) | Jun 09, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [585c31e8d3](https://linux-hardware.org/?probe=585c31e8d3) | Jun 08, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [092cd038fc](https://linux-hardware.org/?probe=092cd038fc) | Jun 08, 2023 |
| Dell          | 0K83V0 A00                  | Desktop     | [fc7fa0850a](https://linux-hardware.org/?probe=fc7fa0850a) | Jun 08, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [20092d99e6](https://linux-hardware.org/?probe=20092d99e6) | Jun 08, 2023 |
| Supermicro    | X8DTU                       | Server      | [8c9992144c](https://linux-hardware.org/?probe=8c9992144c) | Jun 08, 2023 |
| Dell          | 08GXHX A06                  | Server      | [e4ef5b4ff9](https://linux-hardware.org/?probe=e4ef5b4ff9) | Jun 08, 2023 |
| Supermicro    | X8DTU                       | Server      | [afa1204a2d](https://linux-hardware.org/?probe=afa1204a2d) | Jun 08, 2023 |
| Supermicro    | X8DTU                       | Server      | [71e863c1a8](https://linux-hardware.org/?probe=71e863c1a8) | Jun 08, 2023 |
| Supermicro    | X8DTU                       | Server      | [5033e3aef3](https://linux-hardware.org/?probe=5033e3aef3) | Jun 08, 2023 |
| Supermicro    | X9DRW                       | Server      | [0f8167210a](https://linux-hardware.org/?probe=0f8167210a) | Jun 08, 2023 |
| Supermicro    | X8DTU                       | Server      | [ab8024c378](https://linux-hardware.org/?probe=ab8024c378) | Jun 08, 2023 |
| Supermicro    | X9DRW                       | Server      | [6845342901](https://linux-hardware.org/?probe=6845342901) | Jun 08, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [a94d257f7f](https://linux-hardware.org/?probe=a94d257f7f) | Jun 08, 2023 |
| Supermicro    | X8DTL                       | Server      | [b261675cb7](https://linux-hardware.org/?probe=b261675cb7) | Jun 08, 2023 |
| Supermicro    | X8DTU                       | Server      | [605dfce92c](https://linux-hardware.org/?probe=605dfce92c) | Jun 08, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [8c84a543bf](https://linux-hardware.org/?probe=8c84a543bf) | Jun 08, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [5d8df77ade](https://linux-hardware.org/?probe=5d8df77ade) | Jun 08, 2023 |
| HP            | ENVY 15                     | Notebook    | [3776ac93b3](https://linux-hardware.org/?probe=3776ac93b3) | Jun 08, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [65f988a0c3](https://linux-hardware.org/?probe=65f988a0c3) | Jun 08, 2023 |
| HJS           | OPSH110D4                   | Desktop     | [bfb0ead991](https://linux-hardware.org/?probe=bfb0ead991) | Jun 08, 2023 |
| Samsung       | 910S3L                      | Notebook    | [f8e59b4c0f](https://linux-hardware.org/?probe=f8e59b4c0f) | Jun 08, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [c98ac6e82c](https://linux-hardware.org/?probe=c98ac6e82c) | Jun 08, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [d6a8e02362](https://linux-hardware.org/?probe=d6a8e02362) | Jun 08, 2023 |
| AZW           | SEi                         | Desktop     | [399b4a7add](https://linux-hardware.org/?probe=399b4a7add) | Jun 08, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [829912d683](https://linux-hardware.org/?probe=829912d683) | Jun 08, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [4789561d79](https://linux-hardware.org/?probe=4789561d79) | Jun 08, 2023 |
| Dell          | 088DT1 A01                  | Desktop     | [173e9a0e0c](https://linux-hardware.org/?probe=173e9a0e0c) | Jun 08, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [f995c68d61](https://linux-hardware.org/?probe=f995c68d61) | Jun 08, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [fdb80f6e89](https://linux-hardware.org/?probe=fdb80f6e89) | Jun 08, 2023 |
| Unknown       | Unknown                     | Tablet      | [072c85039e](https://linux-hardware.org/?probe=072c85039e) | Jun 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3444C... | Notebook    | [4e5e1d4052](https://linux-hardware.org/?probe=4e5e1d4052) | Jun 08, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [7879db73f8](https://linux-hardware.org/?probe=7879db73f8) | Jun 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [f4e1a7a712](https://linux-hardware.org/?probe=f4e1a7a712) | Jun 08, 2023 |
| Acer          | Aspire ES1-711              | Notebook    | [79bb8d8e39](https://linux-hardware.org/?probe=79bb8d8e39) | Jun 08, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [f78a07f792](https://linux-hardware.org/?probe=f78a07f792) | Jun 08, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [697f2b18e8](https://linux-hardware.org/?probe=697f2b18e8) | Jun 08, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a91f24af7a](https://linux-hardware.org/?probe=a91f24af7a) | Jun 08, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [96e1e7ea7e](https://linux-hardware.org/?probe=96e1e7ea7e) | Jun 08, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [292625f2da](https://linux-hardware.org/?probe=292625f2da) | Jun 08, 2023 |
| HP            | 2000                        | Notebook    | [4ae1384345](https://linux-hardware.org/?probe=4ae1384345) | Jun 07, 2023 |
| ASRock        | B85M-HDS                    | Desktop     | [e563fa3fe2](https://linux-hardware.org/?probe=e563fa3fe2) | Jun 07, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [8bfed00d06](https://linux-hardware.org/?probe=8bfed00d06) | Jun 07, 2023 |
| Beelink       | Gemini X                    | Notebook    | [49aca69972](https://linux-hardware.org/?probe=49aca69972) | Jun 07, 2023 |
| Dell          | Latitude 3350               | Notebook    | [ef85473c50](https://linux-hardware.org/?probe=ef85473c50) | Jun 07, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [8b82994313](https://linux-hardware.org/?probe=8b82994313) | Jun 07, 2023 |
| Dell          | XPS 9320                    | Notebook    | [ff5fc17acc](https://linux-hardware.org/?probe=ff5fc17acc) | Jun 07, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [f70195a177](https://linux-hardware.org/?probe=f70195a177) | Jun 07, 2023 |
| ECS           | GF8100VM-M5                 | Desktop     | [6aa065057f](https://linux-hardware.org/?probe=6aa065057f) | Jun 07, 2023 |
| Onda TLC      | ONDA Oliver                 | Notebook    | [bbfcf4a3be](https://linux-hardware.org/?probe=bbfcf4a3be) | Jun 07, 2023 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [a692e30aea](https://linux-hardware.org/?probe=a692e30aea) | Jun 07, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [1b491bcfeb](https://linux-hardware.org/?probe=1b491bcfeb) | Jun 07, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [f1060e2b5d](https://linux-hardware.org/?probe=f1060e2b5d) | Jun 07, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [99b42755e8](https://linux-hardware.org/?probe=99b42755e8) | Jun 07, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [7775c4c871](https://linux-hardware.org/?probe=7775c4c871) | Jun 07, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [3a43778152](https://linux-hardware.org/?probe=3a43778152) | Jun 07, 2023 |
| Lenovo        | 3704 SDK0J40700 WIN 3258... | Desktop     | [b18ffc5311](https://linux-hardware.org/?probe=b18ffc5311) | Jun 07, 2023 |
| Dell          | Latitude E7250              | Notebook    | [a80182e728](https://linux-hardware.org/?probe=a80182e728) | Jun 06, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [bd4156867b](https://linux-hardware.org/?probe=bd4156867b) | Jun 06, 2023 |
| Foxconn       | H55M-S                      | Desktop     | [83b86844c0](https://linux-hardware.org/?probe=83b86844c0) | Jun 06, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | Desktop     | [8f3282c700](https://linux-hardware.org/?probe=8f3282c700) | Jun 06, 2023 |
| Sony          | VPCEH3N6E                   | Notebook    | [788ddd35a8](https://linux-hardware.org/?probe=788ddd35a8) | Jun 06, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [dbde8636bb](https://linux-hardware.org/?probe=dbde8636bb) | Jun 06, 2023 |
| Acer          | Aspire A315-31              | Notebook    | [d5da1b4b30](https://linux-hardware.org/?probe=d5da1b4b30) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [e4335c33f6](https://linux-hardware.org/?probe=e4335c33f6) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [bf403bb6d8](https://linux-hardware.org/?probe=bf403bb6d8) | Jun 06, 2023 |
| Samsung       | 910S3L                      | Notebook    | [2db0ae25d8](https://linux-hardware.org/?probe=2db0ae25d8) | Jun 06, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [326a620bbd](https://linux-hardware.org/?probe=326a620bbd) | Jun 06, 2023 |
| ASRock        | H310M-HG4                   | Desktop     | [47b2817d31](https://linux-hardware.org/?probe=47b2817d31) | Jun 06, 2023 |
| Fujitsu       | LIFEBOOK U9310X             | Convertible | [81b1cf6660](https://linux-hardware.org/?probe=81b1cf6660) | Jun 06, 2023 |
| Lenovo        | ThinkPad T590 20N5000AMH    | Notebook    | [91c0d99427](https://linux-hardware.org/?probe=91c0d99427) | Jun 06, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [9cfd61dae7](https://linux-hardware.org/?probe=9cfd61dae7) | Jun 06, 2023 |
| Dell          | Latitude 7400               | Notebook    | [9968377d89](https://linux-hardware.org/?probe=9968377d89) | Jun 06, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [82aba8957b](https://linux-hardware.org/?probe=82aba8957b) | Jun 06, 2023 |
| ASRock        | G41C-GS R2.0                | Desktop     | [6e4835c7bc](https://linux-hardware.org/?probe=6e4835c7bc) | Jun 06, 2023 |
| HP            | 2820h                       | Desktop     | [eb7322ad95](https://linux-hardware.org/?probe=eb7322ad95) | Jun 06, 2023 |
| Microsoft     | Surface Laptop 2            | Tablet      | [769eb5078e](https://linux-hardware.org/?probe=769eb5078e) | Jun 06, 2023 |
| Chuwi         | RZBOX                       | Desktop     | [f395c0f429](https://linux-hardware.org/?probe=f395c0f429) | Jun 06, 2023 |
| HP            | 3397                        | Desktop     | [f85e642ee3](https://linux-hardware.org/?probe=f85e642ee3) | Jun 06, 2023 |
| Dell          | Latitude E6400              | Notebook    | [ced90af89e](https://linux-hardware.org/?probe=ced90af89e) | Jun 06, 2023 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [602e1c8875](https://linux-hardware.org/?probe=602e1c8875) | Jun 06, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [503bc1f4cc](https://linux-hardware.org/?probe=503bc1f4cc) | Jun 06, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [31a814cd0e](https://linux-hardware.org/?probe=31a814cd0e) | Jun 06, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [5159be9e2b](https://linux-hardware.org/?probe=5159be9e2b) | Jun 06, 2023 |
| Inspur        | H61H2-TI2                   | All in one  | [2e0c1fbe0d](https://linux-hardware.org/?probe=2e0c1fbe0d) | Jun 06, 2023 |
| Inspur        | H61H2-TI2                   | All in one  | [5832b8b801](https://linux-hardware.org/?probe=5832b8b801) | Jun 06, 2023 |
| Intel         | DP55WB AAE64798-204         | Desktop     | [fe09edbecc](https://linux-hardware.org/?probe=fe09edbecc) | Jun 06, 2023 |
| Gigabyte      | Z590 VISION G               | Desktop     | [ee1abb360e](https://linux-hardware.org/?probe=ee1abb360e) | Jun 06, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [fc49284b9f](https://linux-hardware.org/?probe=fc49284b9f) | Jun 06, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [53cb8df21f](https://linux-hardware.org/?probe=53cb8df21f) | Jun 06, 2023 |
| Dell          | Precision 3571              | Notebook    | [35f408bce4](https://linux-hardware.org/?probe=35f408bce4) | Jun 06, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [de614b2bc7](https://linux-hardware.org/?probe=de614b2bc7) | Jun 05, 2023 |
| Dell          | Latitude 5530               | Notebook    | [a302ecd3cd](https://linux-hardware.org/?probe=a302ecd3cd) | Jun 05, 2023 |
| HP            | 3397                        | Desktop     | [ea59ba572e](https://linux-hardware.org/?probe=ea59ba572e) | Jun 05, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [450d20f29d](https://linux-hardware.org/?probe=450d20f29d) | Jun 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a06e6ab7ad](https://linux-hardware.org/?probe=a06e6ab7ad) | Jun 05, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [e3738c1f5a](https://linux-hardware.org/?probe=e3738c1f5a) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c8ca6e8787](https://linux-hardware.org/?probe=c8ca6e8787) | Jun 05, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [cc575f0073](https://linux-hardware.org/?probe=cc575f0073) | Jun 05, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [cdb3539c93](https://linux-hardware.org/?probe=cdb3539c93) | Jun 05, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [5bc28b7062](https://linux-hardware.org/?probe=5bc28b7062) | Jun 05, 2023 |
| ASRock        | G41M-GS3                    | Desktop     | [f8789775fe](https://linux-hardware.org/?probe=f8789775fe) | Jun 05, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [aff6da41b8](https://linux-hardware.org/?probe=aff6da41b8) | Jun 05, 2023 |
| Dell          | 0DF42J A00                  | Desktop     | [c68dff0dd7](https://linux-hardware.org/?probe=c68dff0dd7) | Jun 05, 2023 |
| HP            | 83E2                        | Desktop     | [522273fe60](https://linux-hardware.org/?probe=522273fe60) | Jun 05, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [ceab55a00c](https://linux-hardware.org/?probe=ceab55a00c) | Jun 05, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [02614f184c](https://linux-hardware.org/?probe=02614f184c) | Jun 05, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [0cf4dfc5e4](https://linux-hardware.org/?probe=0cf4dfc5e4) | Jun 05, 2023 |
| Infinix       | INBOOK X2                   | Notebook    | [0a82b1aed3](https://linux-hardware.org/?probe=0a82b1aed3) | Jun 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ea07821e39](https://linux-hardware.org/?probe=ea07821e39) | Jun 05, 2023 |
| HP            | Pavilion dm4                | Notebook    | [63bd248ea6](https://linux-hardware.org/?probe=63bd248ea6) | Jun 05, 2023 |
| HP            | 3397                        | Desktop     | [e9dd850e23](https://linux-hardware.org/?probe=e9dd850e23) | Jun 05, 2023 |
| Pegatron      | 2AC2                        | Desktop     | [6182103d25](https://linux-hardware.org/?probe=6182103d25) | Jun 05, 2023 |
| MSI           | Boston                      | Desktop     | [9f5efc29ad](https://linux-hardware.org/?probe=9f5efc29ad) | Jun 04, 2023 |
| Lenovo        | ThinkCentre Edge 91Z 707... | Desktop     | [a6804d8ca1](https://linux-hardware.org/?probe=a6804d8ca1) | Jun 04, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [d9dba3ffdf](https://linux-hardware.org/?probe=d9dba3ffdf) | Jun 04, 2023 |
| Intel         | DH55HC AAE70933-503         | Desktop     | [b3d5e112eb](https://linux-hardware.org/?probe=b3d5e112eb) | Jun 04, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [ba0e7c7d59](https://linux-hardware.org/?probe=ba0e7c7d59) | Jun 04, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [1b9656a4a1](https://linux-hardware.org/?probe=1b9656a4a1) | Jun 04, 2023 |
| ASRock        | A75M-HVS                    | Desktop     | [69bc52dc4f](https://linux-hardware.org/?probe=69bc52dc4f) | Jun 04, 2023 |
| Acer          | Predator G3-710             | Desktop     | [7193d24262](https://linux-hardware.org/?probe=7193d24262) | Jun 04, 2023 |
| Acer          | Predator G3-710             | Desktop     | [96834ea12b](https://linux-hardware.org/?probe=96834ea12b) | Jun 04, 2023 |
| HP            | 83E2                        | Desktop     | [3684f8562d](https://linux-hardware.org/?probe=3684f8562d) | Jun 04, 2023 |
| Acer          | Predator G3-710             | Desktop     | [c200dbb9cf](https://linux-hardware.org/?probe=c200dbb9cf) | Jun 04, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [f492ab6829](https://linux-hardware.org/?probe=f492ab6829) | Jun 04, 2023 |
| HP            | 2000                        | Notebook    | [7b24eaf0d9](https://linux-hardware.org/?probe=7b24eaf0d9) | Jun 04, 2023 |
| HP            | 2000                        | Notebook    | [dfee85b8e7](https://linux-hardware.org/?probe=dfee85b8e7) | Jun 04, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [5713168678](https://linux-hardware.org/?probe=5713168678) | Jun 04, 2023 |
| IP3 Tech      | AP1                         | Notebook    | [d24ecf10e2](https://linux-hardware.org/?probe=d24ecf10e2) | Jun 04, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [8fa7afa4a1](https://linux-hardware.org/?probe=8fa7afa4a1) | Jun 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [a00b8e7d13](https://linux-hardware.org/?probe=a00b8e7d13) | Jun 04, 2023 |
| Apple         | MacBookPro13,3              | Notebook    | [885709a33f](https://linux-hardware.org/?probe=885709a33f) | Jun 04, 2023 |
| Lenovo        | ThinkPad T450 20BU000FUS    | Notebook    | [a0181fbf52](https://linux-hardware.org/?probe=a0181fbf52) | Jun 04, 2023 |
| Dell          | 0F0XJ6 A02                  | Server      | [a63e1bbe8a](https://linux-hardware.org/?probe=a63e1bbe8a) | Jun 04, 2023 |
| Samsung       | 950XED                      | Notebook    | [185834c02e](https://linux-hardware.org/?probe=185834c02e) | Jun 04, 2023 |
| Lanix         | AL V9                       | Notebook    | [3bd23fdde7](https://linux-hardware.org/?probe=3bd23fdde7) | Jun 04, 2023 |
| MSI           | Modern 14 B5M               | Notebook    | [da21766a5c](https://linux-hardware.org/?probe=da21766a5c) | Jun 04, 2023 |
| Dell          | XPS 13 9315 2-in-1          | Tablet      | [1a71f40098](https://linux-hardware.org/?probe=1a71f40098) | Jun 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [8c2d7ce6e2](https://linux-hardware.org/?probe=8c2d7ce6e2) | Jun 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [dc8f67bb03](https://linux-hardware.org/?probe=dc8f67bb03) | Jun 03, 2023 |
| Schenker      | XMG FOCUS (M22)             | Notebook    | [31203c3645](https://linux-hardware.org/?probe=31203c3645) | Jun 03, 2023 |
| Dell          | 0N4NF7 A00                  | Desktop     | [e1348eb2c2](https://linux-hardware.org/?probe=e1348eb2c2) | Jun 03, 2023 |
| Dell          | 0N4NF7 A00                  | Desktop     | [6ff177257b](https://linux-hardware.org/?probe=6ff177257b) | Jun 03, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [33bb0f34df](https://linux-hardware.org/?probe=33bb0f34df) | Jun 03, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [d07b3215b1](https://linux-hardware.org/?probe=d07b3215b1) | Jun 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [2745284306](https://linux-hardware.org/?probe=2745284306) | Jun 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f12b791748](https://linux-hardware.org/?probe=f12b791748) | Jun 03, 2023 |
| ASUSTek       | K52Je                       | Notebook    | [c6f78ba2aa](https://linux-hardware.org/?probe=c6f78ba2aa) | Jun 03, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [9e1fe43cf9](https://linux-hardware.org/?probe=9e1fe43cf9) | Jun 03, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [7a760e7ad6](https://linux-hardware.org/?probe=7a760e7ad6) | Jun 03, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [e9b164885c](https://linux-hardware.org/?probe=e9b164885c) | Jun 03, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ba2dfac7ae](https://linux-hardware.org/?probe=ba2dfac7ae) | Jun 03, 2023 |
| Dell          | Latitude E7450              | Notebook    | [fe7cb1e53f](https://linux-hardware.org/?probe=fe7cb1e53f) | Jun 03, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [1e4ffa48ce](https://linux-hardware.org/?probe=1e4ffa48ce) | Jun 03, 2023 |
| Dell          | 0D6H9T A01                  | Desktop     | [1ebbe353ba](https://linux-hardware.org/?probe=1ebbe353ba) | Jun 03, 2023 |
| Dell          | 0D6H9T A01                  | Desktop     | [0bb2080b31](https://linux-hardware.org/?probe=0bb2080b31) | Jun 03, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [e459d2654f](https://linux-hardware.org/?probe=e459d2654f) | Jun 03, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [a0cc355293](https://linux-hardware.org/?probe=a0cc355293) | Jun 03, 2023 |
| Dell          | G15 5520                    | Notebook    | [b77b760dfe](https://linux-hardware.org/?probe=b77b760dfe) | Jun 03, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [983a81f19e](https://linux-hardware.org/?probe=983a81f19e) | Jun 03, 2023 |
| NCS-Tech      | B300                        | Notebook    | [895395765b](https://linux-hardware.org/?probe=895395765b) | Jun 03, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [de331bfb5c](https://linux-hardware.org/?probe=de331bfb5c) | Jun 02, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [9b83a4575b](https://linux-hardware.org/?probe=9b83a4575b) | Jun 02, 2023 |
| Biostar       | TA970XE                     | Desktop     | [11936a0f0f](https://linux-hardware.org/?probe=11936a0f0f) | Jun 02, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [c8fca2b92d](https://linux-hardware.org/?probe=c8fca2b92d) | Jun 02, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [47b838db36](https://linux-hardware.org/?probe=47b838db36) | Jun 02, 2023 |
| Dell          | Latitude 6430U              | Notebook    | [3104417f5e](https://linux-hardware.org/?probe=3104417f5e) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [a6d6fdfe4f](https://linux-hardware.org/?probe=a6d6fdfe4f) | Jun 02, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [35fff15a30](https://linux-hardware.org/?probe=35fff15a30) | Jun 02, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [54fcb811b8](https://linux-hardware.org/?probe=54fcb811b8) | Jun 02, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [664282cc84](https://linux-hardware.org/?probe=664282cc84) | Jun 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4d170e024e](https://linux-hardware.org/?probe=4d170e024e) | Jun 02, 2023 |
| IBM           | 00J6244 08                  | Server      | [81b4c3fd14](https://linux-hardware.org/?probe=81b4c3fd14) | Jun 02, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [7739f949e1](https://linux-hardware.org/?probe=7739f949e1) | Jun 02, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [16d662673f](https://linux-hardware.org/?probe=16d662673f) | Jun 02, 2023 |
| ASUSTek       | Maximus Formula             | Desktop     | [6a70fa0a86](https://linux-hardware.org/?probe=6a70fa0a86) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [b8c8f96b56](https://linux-hardware.org/?probe=b8c8f96b56) | Jun 02, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [c87d784c98](https://linux-hardware.org/?probe=c87d784c98) | Jun 02, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [a7c067f896](https://linux-hardware.org/?probe=a7c067f896) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [6b1168349b](https://linux-hardware.org/?probe=6b1168349b) | Jun 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [302ae0e2dc](https://linux-hardware.org/?probe=302ae0e2dc) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [3da98cc9bb](https://linux-hardware.org/?probe=3da98cc9bb) | Jun 02, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [b27125a1e2](https://linux-hardware.org/?probe=b27125a1e2) | Jun 02, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [1a4437e831](https://linux-hardware.org/?probe=1a4437e831) | Jun 02, 2023 |
| Intel         | AB2L .A003                  | Mini pc     | [25fb11cde7](https://linux-hardware.org/?probe=25fb11cde7) | Jun 01, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [29c4ba7312](https://linux-hardware.org/?probe=29c4ba7312) | Jun 01, 2023 |
| Samsung       | 950QED                      | Convertible | [cec979ab11](https://linux-hardware.org/?probe=cec979ab11) | Jun 01, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [6c86bd69e0](https://linux-hardware.org/?probe=6c86bd69e0) | Jun 01, 2023 |
| ASRock        | Z77M                        | Desktop     | [eae1adee21](https://linux-hardware.org/?probe=eae1adee21) | Jun 01, 2023 |
| HP            | 18E5                        | Desktop     | [9d89c3065b](https://linux-hardware.org/?probe=9d89c3065b) | Jun 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [fa6344a8eb](https://linux-hardware.org/?probe=fa6344a8eb) | Jun 01, 2023 |
| Lenovo        | ThinkPad T530 2392AHG       | Notebook    | [05c41c8464](https://linux-hardware.org/?probe=05c41c8464) | Jun 01, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [98b0b355db](https://linux-hardware.org/?probe=98b0b355db) | Jun 01, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [42b1507aa8](https://linux-hardware.org/?probe=42b1507aa8) | Jun 01, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [fcc2d0ed39](https://linux-hardware.org/?probe=fcc2d0ed39) | Jun 01, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [c9409c532d](https://linux-hardware.org/?probe=c9409c532d) | Jun 01, 2023 |
| HP            | 1906                        | Desktop     | [ac98480bd2](https://linux-hardware.org/?probe=ac98480bd2) | Jun 01, 2023 |
| Lenovo        | G400s VILG1                 | Notebook    | [fee541ee18](https://linux-hardware.org/?probe=fee541ee18) | Jun 01, 2023 |
| HP            | 18E7                        | Desktop     | [a3f557389e](https://linux-hardware.org/?probe=a3f557389e) | Jun 01, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [33e440f44f](https://linux-hardware.org/?probe=33e440f44f) | Jun 01, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [02d5f4b511](https://linux-hardware.org/?probe=02d5f4b511) | Jun 01, 2023 |
| MSI           | Prestige 15 A12UC           | Notebook    | [9324563727](https://linux-hardware.org/?probe=9324563727) | Jun 01, 2023 |
| MSI           | Prestige 15 A12UC           | Notebook    | [778e78d2a5](https://linux-hardware.org/?probe=778e78d2a5) | Jun 01, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [af2f742bc5](https://linux-hardware.org/?probe=af2f742bc5) | Jun 01, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [835a44b010](https://linux-hardware.org/?probe=835a44b010) | Jun 01, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [fe31674f48](https://linux-hardware.org/?probe=fe31674f48) | Jun 01, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [0afa6e53d0](https://linux-hardware.org/?probe=0afa6e53d0) | Jun 01, 2023 |
| Dell          | 03NVJ6 A00                  | Desktop     | [1f295f3ec2](https://linux-hardware.org/?probe=1f295f3ec2) | Jun 01, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [996b318420](https://linux-hardware.org/?probe=996b318420) | Jun 01, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [3e49e329d3](https://linux-hardware.org/?probe=3e49e329d3) | Jun 01, 2023 |
| Packard Be... | EasyNote LJ75               | Notebook    | [95c733d00f](https://linux-hardware.org/?probe=95c733d00f) | May 31, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [b7032438d2](https://linux-hardware.org/?probe=b7032438d2) | May 31, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [cfd38fc71a](https://linux-hardware.org/?probe=cfd38fc71a) | May 31, 2023 |
| MSI           | GE70 2QE                    | Notebook    | [a075b8b77d](https://linux-hardware.org/?probe=a075b8b77d) | May 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [bfcb7f950d](https://linux-hardware.org/?probe=bfcb7f950d) | May 31, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [2c315764a9](https://linux-hardware.org/?probe=2c315764a9) | May 31, 2023 |
| Dell          | Inspiron 3502               | Notebook    | [3c734d2900](https://linux-hardware.org/?probe=3c734d2900) | May 31, 2023 |
| Toshiba       | Satellite L850              | Notebook    | [cee0a13d3f](https://linux-hardware.org/?probe=cee0a13d3f) | May 31, 2023 |
| Dell          | Precision 7670              | Notebook    | [77b039b486](https://linux-hardware.org/?probe=77b039b486) | May 31, 2023 |
| AXIOO         | Mybook-14E                  | Notebook    | [cb04b551d8](https://linux-hardware.org/?probe=cb04b551d8) | May 31, 2023 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [c76d767402](https://linux-hardware.org/?probe=c76d767402) | May 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [6c3655186f](https://linux-hardware.org/?probe=6c3655186f) | May 31, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [75cde40262](https://linux-hardware.org/?probe=75cde40262) | May 31, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2c6c547437](https://linux-hardware.org/?probe=2c6c547437) | May 31, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [7210e5c07e](https://linux-hardware.org/?probe=7210e5c07e) | May 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [0ead50ad49](https://linux-hardware.org/?probe=0ead50ad49) | May 31, 2023 |
| Jumper        | EZbook                      | Notebook    | [3ccf2e1365](https://linux-hardware.org/?probe=3ccf2e1365) | May 31, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [1d0c56937c](https://linux-hardware.org/?probe=1d0c56937c) | May 31, 2023 |
| System76      | Thelio Mira                 | Desktop     | [d5fe3a3749](https://linux-hardware.org/?probe=d5fe3a3749) | May 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [742ae62ba6](https://linux-hardware.org/?probe=742ae62ba6) | May 30, 2023 |
| ASUSTek       | T102HA                      | Tablet      | [71bd8f1212](https://linux-hardware.org/?probe=71bd8f1212) | May 30, 2023 |
| Acer          | Aspire V3-574G              | Notebook    | [728459dd4a](https://linux-hardware.org/?probe=728459dd4a) | May 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [ada20f1f6a](https://linux-hardware.org/?probe=ada20f1f6a) | May 30, 2023 |
| Intel         | STK2M3W64CC H89289-504      | Desktop     | [a7e599b1f5](https://linux-hardware.org/?probe=a7e599b1f5) | May 30, 2023 |
| ASRock        | H110M-DS/Hyper              | Desktop     | [a29a16d74c](https://linux-hardware.org/?probe=a29a16d74c) | May 30, 2023 |
| Intel         | STK2M3W64CC H89289-504      | Desktop     | [c471536b99](https://linux-hardware.org/?probe=c471536b99) | May 30, 2023 |
| AZW           | SER                         | Mini pc     | [fa1f0ff1b4](https://linux-hardware.org/?probe=fa1f0ff1b4) | May 30, 2023 |
| ASRock        | H110M-DS/Hyper              | Desktop     | [05e7ed23f3](https://linux-hardware.org/?probe=05e7ed23f3) | May 30, 2023 |
| HP            | ENVY 15                     | Notebook    | [5acbfb03f4](https://linux-hardware.org/?probe=5acbfb03f4) | May 30, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [5271bd0b88](https://linux-hardware.org/?probe=5271bd0b88) | May 30, 2023 |
| Toshiba       | Satellite C665              | Notebook    | [c6149a6430](https://linux-hardware.org/?probe=c6149a6430) | May 30, 2023 |
| IBM           | 00J6244 08                  | Server      | [cee2891b60](https://linux-hardware.org/?probe=cee2891b60) | May 30, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [de30e713bf](https://linux-hardware.org/?probe=de30e713bf) | May 30, 2023 |
| Supermicro    | X13SAN-L                    | Server      | [e0b7939357](https://linux-hardware.org/?probe=e0b7939357) | May 30, 2023 |
| Pegatron      | 2AC2                        | Desktop     | [a8873fdeab](https://linux-hardware.org/?probe=a8873fdeab) | May 30, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [b881639bef](https://linux-hardware.org/?probe=b881639bef) | May 30, 2023 |
| HP            | Pavilion 15                 | Notebook    | [ca18fafda8](https://linux-hardware.org/?probe=ca18fafda8) | May 29, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [e9f91331b2](https://linux-hardware.org/?probe=e9f91331b2) | May 29, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [afb02cee29](https://linux-hardware.org/?probe=afb02cee29) | May 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [d98102f69a](https://linux-hardware.org/?probe=d98102f69a) | May 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [509bb7aae7](https://linux-hardware.org/?probe=509bb7aae7) | May 29, 2023 |
| MSI           | Katana GF76 12UD            | Notebook    | [b1b1816b59](https://linux-hardware.org/?probe=b1b1816b59) | May 29, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [7a52f09646](https://linux-hardware.org/?probe=7a52f09646) | May 29, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [6fdc7285f2](https://linux-hardware.org/?probe=6fdc7285f2) | May 29, 2023 |
| Fujitsu       | D3402-A1 S26361-D3402-A1    | Desktop     | [0ae3ea958a](https://linux-hardware.org/?probe=0ae3ea958a) | May 29, 2023 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | Notebook    | [202bf4f657](https://linux-hardware.org/?probe=202bf4f657) | May 29, 2023 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | Notebook    | [bb60c42e07](https://linux-hardware.org/?probe=bb60c42e07) | May 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S42000    | Notebook    | [ea6330526c](https://linux-hardware.org/?probe=ea6330526c) | May 29, 2023 |
| HP            | 1497                        | Desktop     | [5f1886622a](https://linux-hardware.org/?probe=5f1886622a) | May 29, 2023 |
| Sony          | VPCEA45FG                   | Notebook    | [873ca04445](https://linux-hardware.org/?probe=873ca04445) | May 29, 2023 |
| MSI           | Raider GE76 12UE            | Notebook    | [5e8f375846](https://linux-hardware.org/?probe=5e8f375846) | May 29, 2023 |
| HP            | 2B43                        | Desktop     | [fb2841cfa4](https://linux-hardware.org/?probe=fb2841cfa4) | May 29, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [227930e25d](https://linux-hardware.org/?probe=227930e25d) | May 29, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [4353f50548](https://linux-hardware.org/?probe=4353f50548) | May 28, 2023 |
| Lenovo        | ThinkPad T540p 20BE00AKZ... | Notebook    | [f9bc4694e4](https://linux-hardware.org/?probe=f9bc4694e4) | May 28, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [d993490e5a](https://linux-hardware.org/?probe=d993490e5a) | May 28, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [bf0674c0f0](https://linux-hardware.org/?probe=bf0674c0f0) | May 28, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [4ae997cf6b](https://linux-hardware.org/?probe=4ae997cf6b) | May 28, 2023 |
| Lenovo        | 3730 SDK0T76463 WIN 3422... | Desktop     | [7467436de2](https://linux-hardware.org/?probe=7467436de2) | May 28, 2023 |
| HP            | 1495                        | Desktop     | [15b94cba50](https://linux-hardware.org/?probe=15b94cba50) | May 28, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [25c6965a47](https://linux-hardware.org/?probe=25c6965a47) | May 28, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [e950caa0ce](https://linux-hardware.org/?probe=e950caa0ce) | May 28, 2023 |
| ECS           | H81H3-M4                    | Desktop     | [21261aa270](https://linux-hardware.org/?probe=21261aa270) | May 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [95793a85de](https://linux-hardware.org/?probe=95793a85de) | May 28, 2023 |
| Dell          | 048DY8 A01                  | Desktop     | [9bfe61714e](https://linux-hardware.org/?probe=9bfe61714e) | May 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [7c9addaf1c](https://linux-hardware.org/?probe=7c9addaf1c) | May 28, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [9178413d40](https://linux-hardware.org/?probe=9178413d40) | May 28, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [c5b13d6ea2](https://linux-hardware.org/?probe=c5b13d6ea2) | May 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [960ddf4eaf](https://linux-hardware.org/?probe=960ddf4eaf) | May 28, 2023 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [e50700f8be](https://linux-hardware.org/?probe=e50700f8be) | May 28, 2023 |
| HP            | 0B54h D                     | Desktop     | [f9634b51b9](https://linux-hardware.org/?probe=f9634b51b9) | May 28, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [a1aa06298d](https://linux-hardware.org/?probe=a1aa06298d) | May 28, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [dbb348e8bf](https://linux-hardware.org/?probe=dbb348e8bf) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [86876e9715](https://linux-hardware.org/?probe=86876e9715) | May 28, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [412b42ae92](https://linux-hardware.org/?probe=412b42ae92) | May 28, 2023 |
| Shuttle       | X50V5                       | Notebook    | [277cc7ca36](https://linux-hardware.org/?probe=277cc7ca36) | May 28, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [4d8767d94b](https://linux-hardware.org/?probe=4d8767d94b) | May 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [c2125f60d2](https://linux-hardware.org/?probe=c2125f60d2) | May 28, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [cc1c8b2941](https://linux-hardware.org/?probe=cc1c8b2941) | May 28, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [5a39bd1d78](https://linux-hardware.org/?probe=5a39bd1d78) | May 28, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [a36d2b541a](https://linux-hardware.org/?probe=a36d2b541a) | May 28, 2023 |
| Apple         | MacBookAir8,1               | Notebook    | [47b2ee3c0d](https://linux-hardware.org/?probe=47b2ee3c0d) | May 28, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [41a9c1dcf2](https://linux-hardware.org/?probe=41a9c1dcf2) | May 28, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [bb842bc2d8](https://linux-hardware.org/?probe=bb842bc2d8) | May 28, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [183ee8e37a](https://linux-hardware.org/?probe=183ee8e37a) | May 27, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [8dda5ffa6f](https://linux-hardware.org/?probe=8dda5ffa6f) | May 27, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [76a357994a](https://linux-hardware.org/?probe=76a357994a) | May 27, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [c6309fc374](https://linux-hardware.org/?probe=c6309fc374) | May 27, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [1eecbd5808](https://linux-hardware.org/?probe=1eecbd5808) | May 27, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | Desktop     | [ccf71ca66c](https://linux-hardware.org/?probe=ccf71ca66c) | May 27, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | Desktop     | [1a3a921775](https://linux-hardware.org/?probe=1a3a921775) | May 27, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [ee0a9f666c](https://linux-hardware.org/?probe=ee0a9f666c) | May 27, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [3f6fc3ec0c](https://linux-hardware.org/?probe=3f6fc3ec0c) | May 27, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [9605e313ac](https://linux-hardware.org/?probe=9605e313ac) | May 27, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [0a8ae92c13](https://linux-hardware.org/?probe=0a8ae92c13) | May 27, 2023 |
| MSI           | A55M-E33                    | Desktop     | [c25cb7cbb6](https://linux-hardware.org/?probe=c25cb7cbb6) | May 27, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [8311d009bd](https://linux-hardware.org/?probe=8311d009bd) | May 27, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [8b2266868a](https://linux-hardware.org/?probe=8b2266868a) | May 27, 2023 |
| HP            | 829A                        | Mini pc     | [bca6d6c12f](https://linux-hardware.org/?probe=bca6d6c12f) | May 27, 2023 |
| HP            | 829A                        | Mini pc     | [d24e18a488](https://linux-hardware.org/?probe=d24e18a488) | May 27, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [9cb2973f2f](https://linux-hardware.org/?probe=9cb2973f2f) | May 27, 2023 |
| Dell          | Latitude 7490               | Notebook    | [fbad4c1a53](https://linux-hardware.org/?probe=fbad4c1a53) | May 27, 2023 |
| Dell          | Latitude 7490               | Notebook    | [00c44ed00c](https://linux-hardware.org/?probe=00c44ed00c) | May 27, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [f1b7ea69ea](https://linux-hardware.org/?probe=f1b7ea69ea) | May 27, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [cc9d03264f](https://linux-hardware.org/?probe=cc9d03264f) | May 27, 2023 |
| Lenovo        | 31900058 STD                | Desktop     | [d09ae4f1a2](https://linux-hardware.org/?probe=d09ae4f1a2) | May 27, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [2cea143017](https://linux-hardware.org/?probe=2cea143017) | May 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [b82f4b77f4](https://linux-hardware.org/?probe=b82f4b77f4) | May 26, 2023 |
| Samsung       | 910S3G/910S3T               | Notebook    | [e041a5365e](https://linux-hardware.org/?probe=e041a5365e) | May 26, 2023 |
| MSI           | Raider GE76 12UE            | Notebook    | [25bcdc17b0](https://linux-hardware.org/?probe=25bcdc17b0) | May 26, 2023 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [ebc73bb225](https://linux-hardware.org/?probe=ebc73bb225) | May 26, 2023 |
| Dell          | Inspiron N4020              | Notebook    | [6350805cd6](https://linux-hardware.org/?probe=6350805cd6) | May 26, 2023 |
| Dell          | Inspiron N4020              | Notebook    | [801ec6309f](https://linux-hardware.org/?probe=801ec6309f) | May 26, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [07be92d6f3](https://linux-hardware.org/?probe=07be92d6f3) | May 26, 2023 |
| ASUSTek       | K52Je                       | Notebook    | [3b40aeae90](https://linux-hardware.org/?probe=3b40aeae90) | May 26, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [1c67718bdb](https://linux-hardware.org/?probe=1c67718bdb) | May 26, 2023 |
| Dell          | Latitude E7450              | Notebook    | [4a88622321](https://linux-hardware.org/?probe=4a88622321) | May 26, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [3aebf9eb7c](https://linux-hardware.org/?probe=3aebf9eb7c) | May 26, 2023 |
| ASUSTek       | Z77-A                       | Desktop     | [0c22362cc0](https://linux-hardware.org/?probe=0c22362cc0) | May 26, 2023 |
| Dell          | 0XCR8D A03                  | Desktop     | [25867f7c36](https://linux-hardware.org/?probe=25867f7c36) | May 26, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | Notebook    | [98308c882b](https://linux-hardware.org/?probe=98308c882b) | May 26, 2023 |
| Dell          | 0HRDCV A00                  | Mini pc     | [6e0d5f0d9b](https://linux-hardware.org/?probe=6e0d5f0d9b) | May 25, 2023 |
| Toshiba       | Satellite S55-A             | Notebook    | [2b9beaf4a6](https://linux-hardware.org/?probe=2b9beaf4a6) | May 25, 2023 |
| Clevo         | P150HMx                     | Notebook    | [d6c90a2c0c](https://linux-hardware.org/?probe=d6c90a2c0c) | May 25, 2023 |
| MSI           | GE75 Raider 10SF            | Notebook    | [5ee0afea25](https://linux-hardware.org/?probe=5ee0afea25) | May 25, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [a49bd1dd26](https://linux-hardware.org/?probe=a49bd1dd26) | May 25, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [8405400374](https://linux-hardware.org/?probe=8405400374) | May 25, 2023 |
| ASUSTek       | N75SF                       | Notebook    | [38840055c8](https://linux-hardware.org/?probe=38840055c8) | May 25, 2023 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [936b06e11f](https://linux-hardware.org/?probe=936b06e11f) | May 25, 2023 |
| Dell          | Latitude 5480               | Notebook    | [adb6ba25f1](https://linux-hardware.org/?probe=adb6ba25f1) | May 25, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [945b06d022](https://linux-hardware.org/?probe=945b06d022) | May 25, 2023 |
| Gigabyte      | P43-ES3G                    | Desktop     | [b9af05a16f](https://linux-hardware.org/?probe=b9af05a16f) | May 25, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [270540781d](https://linux-hardware.org/?probe=270540781d) | May 25, 2023 |
| Dell          | G15 5510                    | Notebook    | [325fcf6e78](https://linux-hardware.org/?probe=325fcf6e78) | May 25, 2023 |
| Dell          | Latitude 5440               | Notebook    | [5a27bd40e7](https://linux-hardware.org/?probe=5a27bd40e7) | May 25, 2023 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [7080c87654](https://linux-hardware.org/?probe=7080c87654) | May 25, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [08a1ae22b7](https://linux-hardware.org/?probe=08a1ae22b7) | May 25, 2023 |
| Samsung       | 900X5T                      | Notebook    | [9f1d226c85](https://linux-hardware.org/?probe=9f1d226c85) | May 25, 2023 |
| Dell          | Latitude 5480               | Notebook    | [45b63ce664](https://linux-hardware.org/?probe=45b63ce664) | May 25, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [589112cb44](https://linux-hardware.org/?probe=589112cb44) | May 25, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [161ed53585](https://linux-hardware.org/?probe=161ed53585) | May 25, 2023 |
| Acer          | Aspire A514-55              | Notebook    | [17996395f4](https://linux-hardware.org/?probe=17996395f4) | May 25, 2023 |
| PCWare        | IPMH110G                    | Desktop     | [33b6fce5ff](https://linux-hardware.org/?probe=33b6fce5ff) | May 25, 2023 |
| ASUSTek       | P5QPL-VM EPU                | Desktop     | [63ba811050](https://linux-hardware.org/?probe=63ba811050) | May 25, 2023 |
| ASUSTek       | P5QPL-VM EPU                | Desktop     | [380b9a5005](https://linux-hardware.org/?probe=380b9a5005) | May 25, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [5d83c85225](https://linux-hardware.org/?probe=5d83c85225) | May 25, 2023 |
| ASUSTek       | F2A85-V                     | Desktop     | [c166f91030](https://linux-hardware.org/?probe=c166f91030) | May 25, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [c885a13922](https://linux-hardware.org/?probe=c885a13922) | May 25, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [897b688aba](https://linux-hardware.org/?probe=897b688aba) | May 25, 2023 |
| Dell          | Latitude 5420               | Notebook    | [a4690b7476](https://linux-hardware.org/?probe=a4690b7476) | May 25, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [6e9287cc5c](https://linux-hardware.org/?probe=6e9287cc5c) | May 25, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [dddde1dc45](https://linux-hardware.org/?probe=dddde1dc45) | May 25, 2023 |
| Dell          | 0654JC A01                  | Desktop     | [d3a2957b45](https://linux-hardware.org/?probe=d3a2957b45) | May 24, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [cb6f15c567](https://linux-hardware.org/?probe=cb6f15c567) | May 24, 2023 |
| HP            | Pavilion 17                 | Notebook    | [792ac6919d](https://linux-hardware.org/?probe=792ac6919d) | May 24, 2023 |
| AZW           | SEi                         | Desktop     | [bc0c7a512f](https://linux-hardware.org/?probe=bc0c7a512f) | May 24, 2023 |
| Alienware     | 17 R3                       | Notebook    | [a567b379a1](https://linux-hardware.org/?probe=a567b379a1) | May 24, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [bce76b90ef](https://linux-hardware.org/?probe=bce76b90ef) | May 24, 2023 |
| congatec      | conga-TA7 A.4               | Mini pc     | [686699557a](https://linux-hardware.org/?probe=686699557a) | May 24, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [6858db4f73](https://linux-hardware.org/?probe=6858db4f73) | May 24, 2023 |
| MSI           | GF63 Thin 9RC               | Notebook    | [aef2c48b64](https://linux-hardware.org/?probe=aef2c48b64) | May 24, 2023 |
| EPSON DIRE... | MR7200E-L                   | Desktop     | [a436b49a11](https://linux-hardware.org/?probe=a436b49a11) | May 24, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [2b12b33767](https://linux-hardware.org/?probe=2b12b33767) | May 24, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [d8261039f8](https://linux-hardware.org/?probe=d8261039f8) | May 24, 2023 |
| Intel         | NUC11DBBi9 M17026-403       | Mini pc     | [61970448fa](https://linux-hardware.org/?probe=61970448fa) | May 24, 2023 |
| Dell          | Precision 5520              | Notebook    | [a5e0cc8586](https://linux-hardware.org/?probe=a5e0cc8586) | May 24, 2023 |
| Lenovo        | ThinkPad W530 24472BG       | Notebook    | [6431c2bb45](https://linux-hardware.org/?probe=6431c2bb45) | May 24, 2023 |
| Dell          | G15 5510                    | Notebook    | [730985e467](https://linux-hardware.org/?probe=730985e467) | May 24, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [587ab1857a](https://linux-hardware.org/?probe=587ab1857a) | May 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [44861be08c](https://linux-hardware.org/?probe=44861be08c) | May 24, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LHS... | Convertible | [285332e926](https://linux-hardware.org/?probe=285332e926) | May 24, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [f0e96b17d7](https://linux-hardware.org/?probe=f0e96b17d7) | May 24, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [02d5fa9cc3](https://linux-hardware.org/?probe=02d5fa9cc3) | May 24, 2023 |
| AZW           | SEi                         | Desktop     | [825fbaebcd](https://linux-hardware.org/?probe=825fbaebcd) | May 23, 2023 |
| Lenovo        | Unknown                     | Notebook    | [e7148e7a18](https://linux-hardware.org/?probe=e7148e7a18) | May 23, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [0c665ebdd8](https://linux-hardware.org/?probe=0c665ebdd8) | May 23, 2023 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | Notebook    | [a81e627367](https://linux-hardware.org/?probe=a81e627367) | May 23, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [af5b849c20](https://linux-hardware.org/?probe=af5b849c20) | May 23, 2023 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [ed20b84824](https://linux-hardware.org/?probe=ed20b84824) | May 23, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [9e96bcdbef](https://linux-hardware.org/?probe=9e96bcdbef) | May 23, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [3e2ccc8b5e](https://linux-hardware.org/?probe=3e2ccc8b5e) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | Notebook    | [47c0ef11d2](https://linux-hardware.org/?probe=47c0ef11d2) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | Notebook    | [0f7e3e95a2](https://linux-hardware.org/?probe=0f7e3e95a2) | May 23, 2023 |
| Lenovo        | ThinkPad T470s 20HGS4RU0... | Notebook    | [ac8df81694](https://linux-hardware.org/?probe=ac8df81694) | May 23, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [f2477906c7](https://linux-hardware.org/?probe=f2477906c7) | May 23, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [a11fdd0361](https://linux-hardware.org/?probe=a11fdd0361) | May 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [d704fd9efd](https://linux-hardware.org/?probe=d704fd9efd) | May 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [4e817c1abf](https://linux-hardware.org/?probe=4e817c1abf) | May 23, 2023 |
| Medion        | H110H4-EM                   | Desktop     | [218e19be02](https://linux-hardware.org/?probe=218e19be02) | May 23, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [4400f1205b](https://linux-hardware.org/?probe=4400f1205b) | May 23, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [362ad8bcaf](https://linux-hardware.org/?probe=362ad8bcaf) | May 23, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [69f5bff4c0](https://linux-hardware.org/?probe=69f5bff4c0) | May 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [2fffd70abb](https://linux-hardware.org/?probe=2fffd70abb) | May 23, 2023 |
| Dell          | 0JC6JH A00                  | Desktop     | [91d6d0d2da](https://linux-hardware.org/?probe=91d6d0d2da) | May 23, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [e9c0ee4659](https://linux-hardware.org/?probe=e9c0ee4659) | May 23, 2023 |
| Apple         | MacBookPro13,2              | Notebook    | [8b87a13f50](https://linux-hardware.org/?probe=8b87a13f50) | May 23, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [7d93944943](https://linux-hardware.org/?probe=7d93944943) | May 23, 2023 |
| Apple         | MacBookPro13,2              | Notebook    | [f0ef45dcf3](https://linux-hardware.org/?probe=f0ef45dcf3) | May 23, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [00a6f60d75](https://linux-hardware.org/?probe=00a6f60d75) | May 23, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [724db856f3](https://linux-hardware.org/?probe=724db856f3) | May 23, 2023 |
| ASRock        | X399 Professional Gaming    | Desktop     | [72cd126fc6](https://linux-hardware.org/?probe=72cd126fc6) | May 23, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [c77cb59a5c](https://linux-hardware.org/?probe=c77cb59a5c) | May 23, 2023 |
| Lenovo        | ThinkPad T540p 20BF001NU... | Notebook    | [2a770d2eac](https://linux-hardware.org/?probe=2a770d2eac) | May 23, 2023 |
| Dell          | Latitude E5570              | Notebook    | [3b1aaa683d](https://linux-hardware.org/?probe=3b1aaa683d) | May 23, 2023 |
| HP            | 0AECh D                     | Desktop     | [06f56df636](https://linux-hardware.org/?probe=06f56df636) | May 23, 2023 |
| Lenovo        | ThinkPad T450 20BUS0100G    | Notebook    | [069d442d0d](https://linux-hardware.org/?probe=069d442d0d) | May 22, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [39bb190ac7](https://linux-hardware.org/?probe=39bb190ac7) | May 22, 2023 |
| eMachines     | EL1360                      | Desktop     | [0821a0d29b](https://linux-hardware.org/?probe=0821a0d29b) | May 22, 2023 |
| Biostar       | A880GZ                      | Desktop     | [097e118b3a](https://linux-hardware.org/?probe=097e118b3a) | May 22, 2023 |
| ASUSTek       | X555LNB                     | Notebook    | [a1aa3cf4b2](https://linux-hardware.org/?probe=a1aa3cf4b2) | May 22, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [6ca579ee78](https://linux-hardware.org/?probe=6ca579ee78) | May 22, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [5838a30c8b](https://linux-hardware.org/?probe=5838a30c8b) | May 22, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [b38d6399b4](https://linux-hardware.org/?probe=b38d6399b4) | May 22, 2023 |
| ASUSTek       | UX301LAB                    | Notebook    | [69f7b4ae4f](https://linux-hardware.org/?probe=69f7b4ae4f) | May 22, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [895bca272b](https://linux-hardware.org/?probe=895bca272b) | May 22, 2023 |
| HP            | 1791                        | Desktop     | [7fa95d1b7b](https://linux-hardware.org/?probe=7fa95d1b7b) | May 22, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [7978c97691](https://linux-hardware.org/?probe=7978c97691) | May 22, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [14b20068ca](https://linux-hardware.org/?probe=14b20068ca) | May 22, 2023 |
| Gigabyte      | F2A55M-S1                   | Desktop     | [59ede76205](https://linux-hardware.org/?probe=59ede76205) | May 22, 2023 |
| Gigabyte      | F2A55M-S1                   | Desktop     | [a5c1b4eecd](https://linux-hardware.org/?probe=a5c1b4eecd) | May 22, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [012c721256](https://linux-hardware.org/?probe=012c721256) | May 22, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [a942d99205](https://linux-hardware.org/?probe=a942d99205) | May 22, 2023 |
| Apple         | MacBookPro15,1              | Notebook    | [f1d994fa47](https://linux-hardware.org/?probe=f1d994fa47) | May 22, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [406014a766](https://linux-hardware.org/?probe=406014a766) | May 22, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [dc846ba2e5](https://linux-hardware.org/?probe=dc846ba2e5) | May 22, 2023 |
| Dell          | XPS 9315                    | Notebook    | [6c3fdbf590](https://linux-hardware.org/?probe=6c3fdbf590) | May 22, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [eeca18ff12](https://linux-hardware.org/?probe=eeca18ff12) | May 22, 2023 |
| HP            | Pavilion g4                 | Notebook    | [3324fbbbaa](https://linux-hardware.org/?probe=3324fbbbaa) | May 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [dedcc1bb3f](https://linux-hardware.org/?probe=dedcc1bb3f) | May 22, 2023 |
| Medion        | B360H4-EM V1.0              | Desktop     | [ae4f01f58e](https://linux-hardware.org/?probe=ae4f01f58e) | May 22, 2023 |
| MSI           | Z87-G43                     | Desktop     | [2fa7c1d81d](https://linux-hardware.org/?probe=2fa7c1d81d) | May 21, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [536b91dce1](https://linux-hardware.org/?probe=536b91dce1) | May 21, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [d27d5d547e](https://linux-hardware.org/?probe=d27d5d547e) | May 21, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [7db2aa27dc](https://linux-hardware.org/?probe=7db2aa27dc) | May 21, 2023 |
| Dell          | 033FF6 A00                  | Desktop     | [086dd9367e](https://linux-hardware.org/?probe=086dd9367e) | May 21, 2023 |
| Sony          | VPCF120FD                   | Notebook    | [a438459d06](https://linux-hardware.org/?probe=a438459d06) | May 21, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [5309c41b94](https://linux-hardware.org/?probe=5309c41b94) | May 21, 2023 |
| MSI           | PS63 Modern 8MO             | Notebook    | [5d6f78bfbb](https://linux-hardware.org/?probe=5d6f78bfbb) | May 21, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [e4adcd71f1](https://linux-hardware.org/?probe=e4adcd71f1) | May 21, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [09f37f2540](https://linux-hardware.org/?probe=09f37f2540) | May 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [32e623c724](https://linux-hardware.org/?probe=32e623c724) | May 21, 2023 |
| Intel         | NUC11ATBC2 M53055-202       | Mini pc     | [6f50de46aa](https://linux-hardware.org/?probe=6f50de46aa) | May 21, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a6f95de398](https://linux-hardware.org/?probe=a6f95de398) | May 21, 2023 |
| HP            | Pavilion 15                 | Notebook    | [7afbe545bc](https://linux-hardware.org/?probe=7afbe545bc) | May 21, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [313fb9c88a](https://linux-hardware.org/?probe=313fb9c88a) | May 21, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [d404dc5e03](https://linux-hardware.org/?probe=d404dc5e03) | May 21, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [7e0b1e1cdf](https://linux-hardware.org/?probe=7e0b1e1cdf) | May 21, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [f20160cf5b](https://linux-hardware.org/?probe=f20160cf5b) | May 21, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [1b8a739f9a](https://linux-hardware.org/?probe=1b8a739f9a) | May 21, 2023 |
| ASUSTek       | UX430UAR                    | Notebook    | [7815f47a45](https://linux-hardware.org/?probe=7815f47a45) | May 21, 2023 |
| ASUSTek       | K56CA                       | Notebook    | [6ae76c1553](https://linux-hardware.org/?probe=6ae76c1553) | May 21, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [3a448141db](https://linux-hardware.org/?probe=3a448141db) | May 21, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [867806192a](https://linux-hardware.org/?probe=867806192a) | May 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [62b86acadc](https://linux-hardware.org/?probe=62b86acadc) | May 21, 2023 |
| Dell          | 0H28RR A07                  | Server      | [1dd21b89e9](https://linux-hardware.org/?probe=1dd21b89e9) | May 21, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [b2c9a1cd71](https://linux-hardware.org/?probe=b2c9a1cd71) | May 21, 2023 |
| Dell          | 0VNP2H A00                  | Desktop     | [298317e388](https://linux-hardware.org/?probe=298317e388) | May 21, 2023 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [27c48503ad](https://linux-hardware.org/?probe=27c48503ad) | May 21, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [dda7ad1c16](https://linux-hardware.org/?probe=dda7ad1c16) | May 21, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [520bb3be3c](https://linux-hardware.org/?probe=520bb3be3c) | May 21, 2023 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [ec34d9c9c5](https://linux-hardware.org/?probe=ec34d9c9c5) | May 20, 2023 |
| Unknown       | GSUO H61V10C                | Desktop     | [8e1037e4c1](https://linux-hardware.org/?probe=8e1037e4c1) | May 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [b08ca84ea8](https://linux-hardware.org/?probe=b08ca84ea8) | May 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [2d705adeaa](https://linux-hardware.org/?probe=2d705adeaa) | May 20, 2023 |
| Dell          | G3 3500                     | Notebook    | [29f1b0fbda](https://linux-hardware.org/?probe=29f1b0fbda) | May 20, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [cce6eaa028](https://linux-hardware.org/?probe=cce6eaa028) | May 20, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [6bce5f1ff0](https://linux-hardware.org/?probe=6bce5f1ff0) | May 20, 2023 |
| Dell          | Latitude E7450              | Notebook    | [51f34cd446](https://linux-hardware.org/?probe=51f34cd446) | May 20, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [c5fee7bb50](https://linux-hardware.org/?probe=c5fee7bb50) | May 20, 2023 |
| Acer          | Aspire S3                   | Notebook    | [b6841c9aeb](https://linux-hardware.org/?probe=b6841c9aeb) | May 20, 2023 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [a547a22c01](https://linux-hardware.org/?probe=a547a22c01) | May 20, 2023 |
| Medion        | BTDD-LT                     | Desktop     | [3b5eac782c](https://linux-hardware.org/?probe=3b5eac782c) | May 20, 2023 |
| Acer          | Aspire S3                   | Notebook    | [3fafb0df5d](https://linux-hardware.org/?probe=3fafb0df5d) | May 20, 2023 |
| MSI           | H97M-G43                    | Desktop     | [2e31a2b7e0](https://linux-hardware.org/?probe=2e31a2b7e0) | May 20, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [7d4516eff2](https://linux-hardware.org/?probe=7d4516eff2) | May 20, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [e197af6a9f](https://linux-hardware.org/?probe=e197af6a9f) | May 20, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [a4a766a9e1](https://linux-hardware.org/?probe=a4a766a9e1) | May 20, 2023 |
| Daten Tecn... | DA320MXV DC                 | Desktop     | [0b7e1e51b9](https://linux-hardware.org/?probe=0b7e1e51b9) | May 20, 2023 |
| HP            | ProBook 450 G4              | Notebook    | [054ec4f1cb](https://linux-hardware.org/?probe=054ec4f1cb) | May 20, 2023 |
| Dell          | Latitude 7280               | Notebook    | [9b98a88e3d](https://linux-hardware.org/?probe=9b98a88e3d) | May 19, 2023 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [6f6b65d0ed](https://linux-hardware.org/?probe=6f6b65d0ed) | May 19, 2023 |
| Pegatron      | Benicia                     | Desktop     | [24fc512198](https://linux-hardware.org/?probe=24fc512198) | May 19, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [b6336515aa](https://linux-hardware.org/?probe=b6336515aa) | May 19, 2023 |
| Dell          | Latitude E7450              | Notebook    | [e844aeb177](https://linux-hardware.org/?probe=e844aeb177) | May 19, 2023 |
| Acer          | TDPS05                      | Desktop     | [ed5384ee4d](https://linux-hardware.org/?probe=ed5384ee4d) | May 19, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [665ac2defe](https://linux-hardware.org/?probe=665ac2defe) | May 19, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [03c6d7a815](https://linux-hardware.org/?probe=03c6d7a815) | May 19, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [f69b95b887](https://linux-hardware.org/?probe=f69b95b887) | May 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [3ad05eed61](https://linux-hardware.org/?probe=3ad05eed61) | May 19, 2023 |
| ASRock        | H110M-DS/Hyper              | Desktop     | [b208edbf01](https://linux-hardware.org/?probe=b208edbf01) | May 19, 2023 |
| ECS           | PB02CF                      | Server      | [ae43167b8a](https://linux-hardware.org/?probe=ae43167b8a) | May 19, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [db9774a799](https://linux-hardware.org/?probe=db9774a799) | May 19, 2023 |
| ASRock        | H110M-DS/Hyper              | Desktop     | [c90642a42c](https://linux-hardware.org/?probe=c90642a42c) | May 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [73aafcfb9c](https://linux-hardware.org/?probe=73aafcfb9c) | May 19, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [09cc939f04](https://linux-hardware.org/?probe=09cc939f04) | May 19, 2023 |
| Acer          | Aspire E5-771G              | Notebook    | [0dadbeca5b](https://linux-hardware.org/?probe=0dadbeca5b) | May 19, 2023 |
| Gigabyte      | H310M S2                    | Desktop     | [61f60c8a7d](https://linux-hardware.org/?probe=61f60c8a7d) | May 19, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [c0e3ea54c0](https://linux-hardware.org/?probe=c0e3ea54c0) | May 19, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [b0ed659e7d](https://linux-hardware.org/?probe=b0ed659e7d) | May 19, 2023 |
| Lenovo        | ThinkPad E590 20NB0029GE    | Notebook    | [749d31d44a](https://linux-hardware.org/?probe=749d31d44a) | May 19, 2023 |
| Lenovo        | ThinkPad E590 20NB0029GE    | Notebook    | [85da505294](https://linux-hardware.org/?probe=85da505294) | May 19, 2023 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [0d337f6d69](https://linux-hardware.org/?probe=0d337f6d69) | May 19, 2023 |
| Intel         | NUC5i5RYB H40999-503        | Mini pc     | [41342ea0f6](https://linux-hardware.org/?probe=41342ea0f6) | May 19, 2023 |
| Dell          | 0MGK50 A02                  | Desktop     | [7b98244b73](https://linux-hardware.org/?probe=7b98244b73) | May 19, 2023 |
| ECS           | PB02CF                      | Server      | [b2830721b2](https://linux-hardware.org/?probe=b2830721b2) | May 19, 2023 |
| MSI           | GE75 Raider 10SF            | Notebook    | [8aaec63d14](https://linux-hardware.org/?probe=8aaec63d14) | May 19, 2023 |
| Pegatron      | Benicia                     | Desktop     | [6bb420fe9a](https://linux-hardware.org/?probe=6bb420fe9a) | May 19, 2023 |
| ASRock        | B365M Pro4                  | Desktop     | [0df5d6f44e](https://linux-hardware.org/?probe=0df5d6f44e) | May 19, 2023 |
| Lenovo        | IdeaPad U530 Touch 20289    | Notebook    | [72e254e4ee](https://linux-hardware.org/?probe=72e254e4ee) | May 19, 2023 |
| Dell          | 0VNP2H A01                  | Desktop     | [6e51bd033e](https://linux-hardware.org/?probe=6e51bd033e) | May 19, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [916931d01a](https://linux-hardware.org/?probe=916931d01a) | May 19, 2023 |
| MSI           | GE75 Raider 10SF            | Notebook    | [f3724cb7da](https://linux-hardware.org/?probe=f3724cb7da) | May 19, 2023 |
| Dell          | Latitude 3310 2-in-1        | Convertible | [b5ab4dfdf6](https://linux-hardware.org/?probe=b5ab4dfdf6) | May 19, 2023 |
| MSI           | Z97-G55 SLI                 | Desktop     | [a17ed55b13](https://linux-hardware.org/?probe=a17ed55b13) | May 19, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LHS... | Convertible | [39c5d96c08](https://linux-hardware.org/?probe=39c5d96c08) | May 18, 2023 |
| Dell          | 0D881F A06                  | Desktop     | [2d5184956b](https://linux-hardware.org/?probe=2d5184956b) | May 18, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [75ca7ed17e](https://linux-hardware.org/?probe=75ca7ed17e) | May 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [49c702a8c9](https://linux-hardware.org/?probe=49c702a8c9) | May 18, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [839536ab43](https://linux-hardware.org/?probe=839536ab43) | May 18, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C2C... | Notebook    | [a0f983e519](https://linux-hardware.org/?probe=a0f983e519) | May 18, 2023 |
| Lenovo        | Legion 5 15ITH6H 82JH       | Notebook    | [7f35aa414f](https://linux-hardware.org/?probe=7f35aa414f) | May 18, 2023 |
| MSI           | Z97-G55 SLI                 | Desktop     | [0883ceb18c](https://linux-hardware.org/?probe=0883ceb18c) | May 18, 2023 |
| ASUSTek       | CROSSBLADE RANGER           | Desktop     | [afd85b3621](https://linux-hardware.org/?probe=afd85b3621) | May 18, 2023 |
| Dell          | Latitude E6500              | Notebook    | [27213adbe8](https://linux-hardware.org/?probe=27213adbe8) | May 18, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [c7f7f8758b](https://linux-hardware.org/?probe=c7f7f8758b) | May 18, 2023 |
| Sony          | SVF1521A6EW                 | Notebook    | [49a9f77ea9](https://linux-hardware.org/?probe=49a9f77ea9) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [6141537b7b](https://linux-hardware.org/?probe=6141537b7b) | May 18, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [e5e7213107](https://linux-hardware.org/?probe=e5e7213107) | May 18, 2023 |
| Toshiba       | PORTEGE Z830                | Notebook    | [f4548ca81b](https://linux-hardware.org/?probe=f4548ca81b) | May 18, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [bc571d8c3f](https://linux-hardware.org/?probe=bc571d8c3f) | May 18, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [c09d32ebc2](https://linux-hardware.org/?probe=c09d32ebc2) | May 18, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [62e064b7d0](https://linux-hardware.org/?probe=62e064b7d0) | May 18, 2023 |
| Acer          | Aspire 7535                 | Notebook    | [32b02980a7](https://linux-hardware.org/?probe=32b02980a7) | May 18, 2023 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [215d88c8b6](https://linux-hardware.org/?probe=215d88c8b6) | May 18, 2023 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [d452669f4a](https://linux-hardware.org/?probe=d452669f4a) | May 18, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [ba813a3367](https://linux-hardware.org/?probe=ba813a3367) | May 18, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [e33e3678c6](https://linux-hardware.org/?probe=e33e3678c6) | May 18, 2023 |
| Sony          | VPCEB4Z1E                   | Notebook    | [d1cca131ad](https://linux-hardware.org/?probe=d1cca131ad) | May 18, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [5153a2be0d](https://linux-hardware.org/?probe=5153a2be0d) | May 18, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c73e482b69](https://linux-hardware.org/?probe=c73e482b69) | May 18, 2023 |
| Gigabyte      | H310M S2                    | Desktop     | [b8a04e73b8](https://linux-hardware.org/?probe=b8a04e73b8) | May 18, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [45888dea42](https://linux-hardware.org/?probe=45888dea42) | May 18, 2023 |
| Clevo         | P150HMx                     | Notebook    | [17e11751ef](https://linux-hardware.org/?probe=17e11751ef) | May 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [c152120c9e](https://linux-hardware.org/?probe=c152120c9e) | May 18, 2023 |
| Clevo         | P150HMx                     | Notebook    | [f749300168](https://linux-hardware.org/?probe=f749300168) | May 18, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [cf1d4ac757](https://linux-hardware.org/?probe=cf1d4ac757) | May 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [be46da6480](https://linux-hardware.org/?probe=be46da6480) | May 18, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [a23a2d1c6c](https://linux-hardware.org/?probe=a23a2d1c6c) | May 18, 2023 |
| Dell          | 0VNP2H A00                  | Desktop     | [85da02478a](https://linux-hardware.org/?probe=85da02478a) | May 17, 2023 |
| Dell          | 0RY007                      | Desktop     | [c2b8174064](https://linux-hardware.org/?probe=c2b8174064) | May 17, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6e519b78e9](https://linux-hardware.org/?probe=6e519b78e9) | May 17, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [a167afa608](https://linux-hardware.org/?probe=a167afa608) | May 17, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [ad477b9698](https://linux-hardware.org/?probe=ad477b9698) | May 17, 2023 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [0982e8a637](https://linux-hardware.org/?probe=0982e8a637) | May 17, 2023 |
| Acer          | Swift SF316-51              | Notebook    | [663e7fe745](https://linux-hardware.org/?probe=663e7fe745) | May 17, 2023 |
| ASUSTek       | TP300LA                     | Notebook    | [e2e6bc0209](https://linux-hardware.org/?probe=e2e6bc0209) | May 17, 2023 |
| Acer          | TravelMate P215-53G         | Notebook    | [d07aa12d74](https://linux-hardware.org/?probe=d07aa12d74) | May 17, 2023 |
| Acer          | TravelMate P215-53G         | Notebook    | [d2908ee6a9](https://linux-hardware.org/?probe=d2908ee6a9) | May 17, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [9372615767](https://linux-hardware.org/?probe=9372615767) | May 17, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [874dcebbaa](https://linux-hardware.org/?probe=874dcebbaa) | May 17, 2023 |
| Dell          | Inspiron 5580               | Notebook    | [7ced5f9473](https://linux-hardware.org/?probe=7ced5f9473) | May 17, 2023 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [d17610915a](https://linux-hardware.org/?probe=d17610915a) | May 17, 2023 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [ddc3152cbc](https://linux-hardware.org/?probe=ddc3152cbc) | May 17, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [c9d2b44907](https://linux-hardware.org/?probe=c9d2b44907) | May 17, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [af16278f1e](https://linux-hardware.org/?probe=af16278f1e) | May 17, 2023 |
| ASUSTek       | P7H55D-M PRO                | Desktop     | [2c423cf3e9](https://linux-hardware.org/?probe=2c423cf3e9) | May 17, 2023 |
| Intel         | D54250WYK H13922-302        | Desktop     | [0829603c60](https://linux-hardware.org/?probe=0829603c60) | May 17, 2023 |
| ASRock        | Z97 Professional            | Desktop     | [7d0ecd3359](https://linux-hardware.org/?probe=7d0ecd3359) | May 17, 2023 |
| EPSON DIRE... | MR7200E-L                   | Desktop     | [fed1ba2b90](https://linux-hardware.org/?probe=fed1ba2b90) | May 17, 2023 |
| ASUSTek       | P5E WS Pro                  | Desktop     | [97a221407d](https://linux-hardware.org/?probe=97a221407d) | May 17, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [04a6fe63c1](https://linux-hardware.org/?probe=04a6fe63c1) | May 17, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [76e48382f5](https://linux-hardware.org/?probe=76e48382f5) | May 17, 2023 |
| Acer          | TDPS05                      | Desktop     | [2cfc303d36](https://linux-hardware.org/?probe=2cfc303d36) | May 17, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [cb196c4c37](https://linux-hardware.org/?probe=cb196c4c37) | May 17, 2023 |
| Dell          | Latitude 3310 2-in-1        | Convertible | [bdc1f46f44](https://linux-hardware.org/?probe=bdc1f46f44) | May 17, 2023 |
| EPSON DIRE... | MR7200E-L                   | Desktop     | [b0710623f7](https://linux-hardware.org/?probe=b0710623f7) | May 17, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [c6d11a2f8e](https://linux-hardware.org/?probe=c6d11a2f8e) | May 17, 2023 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [777f8ccab0](https://linux-hardware.org/?probe=777f8ccab0) | May 17, 2023 |
| Packard Be... | EasyNote TV43CM             | Notebook    | [66dbc844c7](https://linux-hardware.org/?probe=66dbc844c7) | May 17, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [5af33dbbbc](https://linux-hardware.org/?probe=5af33dbbbc) | May 17, 2023 |
| Google        | Samus                       | Notebook    | [d627862e56](https://linux-hardware.org/?probe=d627862e56) | May 16, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [5ae0ed6f5a](https://linux-hardware.org/?probe=5ae0ed6f5a) | May 16, 2023 |
| ASUSTek       | UX305FA                     | Notebook    | [36cb231f34](https://linux-hardware.org/?probe=36cb231f34) | May 16, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [c7c487333a](https://linux-hardware.org/?probe=c7c487333a) | May 16, 2023 |
| HP            | Pavilion dv6                | Notebook    | [bc505434f7](https://linux-hardware.org/?probe=bc505434f7) | May 16, 2023 |
| Positivo      | W2150G                      | All in one  | [abe3331aac](https://linux-hardware.org/?probe=abe3331aac) | May 16, 2023 |
| Dell          | Latitude 5420               | Notebook    | [ddd072b69c](https://linux-hardware.org/?probe=ddd072b69c) | May 16, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [afbef25815](https://linux-hardware.org/?probe=afbef25815) | May 16, 2023 |
| Acer          | Aspire 5050                 | Notebook    | [44f9abca04](https://linux-hardware.org/?probe=44f9abca04) | May 16, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [2bfe226026](https://linux-hardware.org/?probe=2bfe226026) | May 16, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [467ffa6773](https://linux-hardware.org/?probe=467ffa6773) | May 16, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [146d4e4aff](https://linux-hardware.org/?probe=146d4e4aff) | May 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [546f6e95e9](https://linux-hardware.org/?probe=546f6e95e9) | May 16, 2023 |
| MSI           | GF63 Thin 9RC               | Notebook    | [b8f2e92853](https://linux-hardware.org/?probe=b8f2e92853) | May 16, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [c2ccca0208](https://linux-hardware.org/?probe=c2ccca0208) | May 16, 2023 |
| Toshiba       | Satellite C805D             | Notebook    | [21ee852978](https://linux-hardware.org/?probe=21ee852978) | May 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [54fc8d0489](https://linux-hardware.org/?probe=54fc8d0489) | May 16, 2023 |
| Dell          | Precision 5530              | Notebook    | [16366ef886](https://linux-hardware.org/?probe=16366ef886) | May 16, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [05441101a8](https://linux-hardware.org/?probe=05441101a8) | May 16, 2023 |
| AZW           | GT-R                        | Notebook    | [e156c5b105](https://linux-hardware.org/?probe=e156c5b105) | May 16, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [6094f7a191](https://linux-hardware.org/?probe=6094f7a191) | May 16, 2023 |
| ASUSTek       | V241EA                      | All in one  | [e4f05ea74b](https://linux-hardware.org/?probe=e4f05ea74b) | May 16, 2023 |
| SHANGZHAOY... | X99-D8-MAX V1.0             | Desktop     | [b77555d36f](https://linux-hardware.org/?probe=b77555d36f) | May 16, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [cce2c46f1e](https://linux-hardware.org/?probe=cce2c46f1e) | May 16, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [b2b220a903](https://linux-hardware.org/?probe=b2b220a903) | May 16, 2023 |
| HP            | ENVY 4                      | Notebook    | [ddc467f053](https://linux-hardware.org/?probe=ddc467f053) | May 16, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [3f5bade9b8](https://linux-hardware.org/?probe=3f5bade9b8) | May 16, 2023 |
| Lenovo        | ThinkPad L480 20LTSAK70R    | Notebook    | [551d238ad3](https://linux-hardware.org/?probe=551d238ad3) | May 16, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [bdaec355df](https://linux-hardware.org/?probe=bdaec355df) | May 16, 2023 |
| VIT           | M2400-01                    | Mini pc     | [64e5a3aa50](https://linux-hardware.org/?probe=64e5a3aa50) | May 16, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [e01dbddbd0](https://linux-hardware.org/?probe=e01dbddbd0) | May 16, 2023 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [d2fbc01926](https://linux-hardware.org/?probe=d2fbc01926) | May 15, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [72db5ccefc](https://linux-hardware.org/?probe=72db5ccefc) | May 15, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [040fb99c20](https://linux-hardware.org/?probe=040fb99c20) | May 15, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [996d19a70c](https://linux-hardware.org/?probe=996d19a70c) | May 15, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [f5ef3c16c5](https://linux-hardware.org/?probe=f5ef3c16c5) | May 15, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [2fa63538ef](https://linux-hardware.org/?probe=2fa63538ef) | May 15, 2023 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [1bf9f3a0df](https://linux-hardware.org/?probe=1bf9f3a0df) | May 15, 2023 |
| Supermicro    | H12DSU-iN                   | Desktop     | [05b2b86f35](https://linux-hardware.org/?probe=05b2b86f35) | May 15, 2023 |
| Dell          | G3 3590                     | Notebook    | [75a6a8a107](https://linux-hardware.org/?probe=75a6a8a107) | May 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [33a9b42068](https://linux-hardware.org/?probe=33a9b42068) | May 15, 2023 |
| ASUSTek       | PN50-E1                     | Mini pc     | [b595a4a849](https://linux-hardware.org/?probe=b595a4a849) | May 15, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [755f1920f2](https://linux-hardware.org/?probe=755f1920f2) | May 15, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [26c3a1e5cf](https://linux-hardware.org/?probe=26c3a1e5cf) | May 15, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [3bd39e50a8](https://linux-hardware.org/?probe=3bd39e50a8) | May 15, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [3e34d3a71c](https://linux-hardware.org/?probe=3e34d3a71c) | May 15, 2023 |
| Dell          | G3 3590                     | Notebook    | [b19462038d](https://linux-hardware.org/?probe=b19462038d) | May 15, 2023 |
| Lenovo        | ThinkPad T440p 20AN0079M... | Notebook    | [ec0250b092](https://linux-hardware.org/?probe=ec0250b092) | May 15, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [6a8a2f481e](https://linux-hardware.org/?probe=6a8a2f481e) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [b4e8e5504e](https://linux-hardware.org/?probe=b4e8e5504e) | May 15, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [e67567bd2a](https://linux-hardware.org/?probe=e67567bd2a) | May 15, 2023 |
| Fujitsu       | JIB75Y3                     | Desktop     | [31146fe86e](https://linux-hardware.org/?probe=31146fe86e) | May 15, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [47430a463a](https://linux-hardware.org/?probe=47430a463a) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | Notebook    | [1573285475](https://linux-hardware.org/?probe=1573285475) | May 15, 2023 |
| Dell          | Inspiron 5405               | Notebook    | [9d3ae56a5e](https://linux-hardware.org/?probe=9d3ae56a5e) | May 15, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [06e1ef84b3](https://linux-hardware.org/?probe=06e1ef84b3) | May 15, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [61665ffc1a](https://linux-hardware.org/?probe=61665ffc1a) | May 15, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [b21029ef65](https://linux-hardware.org/?probe=b21029ef65) | May 15, 2023 |
| Dell          | Latitude 5520               | Notebook    | [721000195d](https://linux-hardware.org/?probe=721000195d) | May 15, 2023 |
| Medion        | B360H4-EM V1.0              | Desktop     | [1efefa9214](https://linux-hardware.org/?probe=1efefa9214) | May 15, 2023 |
| Quanta        | S6Q-MB-MPS 31S6QMB0010      | Server      | [c2f51116fa](https://linux-hardware.org/?probe=c2f51116fa) | May 15, 2023 |
| Dell          | Latitude 5401               | Notebook    | [4304efbed6](https://linux-hardware.org/?probe=4304efbed6) | May 15, 2023 |
| Lenovo        | ThinkPad L440 20ASA09T06    | Notebook    | [48009f1be4](https://linux-hardware.org/?probe=48009f1be4) | May 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [6e8f0dd2b9](https://linux-hardware.org/?probe=6e8f0dd2b9) | May 15, 2023 |
| Lenovo        | ThinkPad L440 20ASA09T06    | Notebook    | [49e6d93eb1](https://linux-hardware.org/?probe=49e6d93eb1) | May 15, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [f48f5f9eaa](https://linux-hardware.org/?probe=f48f5f9eaa) | May 15, 2023 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [9492267a05](https://linux-hardware.org/?probe=9492267a05) | May 15, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [d7e4640b82](https://linux-hardware.org/?probe=d7e4640b82) | May 15, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [61eeca9cec](https://linux-hardware.org/?probe=61eeca9cec) | May 15, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [fb4bda01b7](https://linux-hardware.org/?probe=fb4bda01b7) | May 15, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [17b9d54da0](https://linux-hardware.org/?probe=17b9d54da0) | May 15, 2023 |
| SHANGZHAOY... | X99-D8-MAX V1.0             | Desktop     | [6e21010553](https://linux-hardware.org/?probe=6e21010553) | May 15, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [36f918cce7](https://linux-hardware.org/?probe=36f918cce7) | May 15, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [1ba0adc2ba](https://linux-hardware.org/?probe=1ba0adc2ba) | May 15, 2023 |
| TEXA          | NEMO MINI                   | Tablet      | [81fc17efec](https://linux-hardware.org/?probe=81fc17efec) | May 14, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [7fa26c56fe](https://linux-hardware.org/?probe=7fa26c56fe) | May 14, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [64b813a7dc](https://linux-hardware.org/?probe=64b813a7dc) | May 14, 2023 |
| Lenovo        | 310B SDK0J40705 WIN 3425... | Desktop     | [94d901f023](https://linux-hardware.org/?probe=94d901f023) | May 14, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [b43ec1363a](https://linux-hardware.org/?probe=b43ec1363a) | May 14, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [b80a472c1a](https://linux-hardware.org/?probe=b80a472c1a) | May 14, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [c585628bc8](https://linux-hardware.org/?probe=c585628bc8) | May 14, 2023 |
| Intel         | NUC5CPYB H61145-407         | Mini pc     | [8e867c3cce](https://linux-hardware.org/?probe=8e867c3cce) | May 14, 2023 |
| Pegatron      | 2AC2                        | Desktop     | [510047e597](https://linux-hardware.org/?probe=510047e597) | May 14, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [8e0efa6d0a](https://linux-hardware.org/?probe=8e0efa6d0a) | May 14, 2023 |
| eMachines     | EL1360                      | Desktop     | [74745ea02b](https://linux-hardware.org/?probe=74745ea02b) | May 14, 2023 |
| TEXA          | NEMO MINI                   | Tablet      | [4b0f306d78](https://linux-hardware.org/?probe=4b0f306d78) | May 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [bb119829d0](https://linux-hardware.org/?probe=bb119829d0) | May 14, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | Notebook    | [d200313f91](https://linux-hardware.org/?probe=d200313f91) | May 14, 2023 |
| Biostar       | N61PB-M2S                   | Desktop     | [4ac75a003b](https://linux-hardware.org/?probe=4ac75a003b) | May 14, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [bf3ff003f9](https://linux-hardware.org/?probe=bf3ff003f9) | May 14, 2023 |
| HP            | ZBook 15u G5                | Notebook    | [4f1f52ce64](https://linux-hardware.org/?probe=4f1f52ce64) | May 14, 2023 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [61370dd5d3](https://linux-hardware.org/?probe=61370dd5d3) | May 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | Notebook    | [0ea14cadea](https://linux-hardware.org/?probe=0ea14cadea) | May 14, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [dc1d9d7e15](https://linux-hardware.org/?probe=dc1d9d7e15) | May 14, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [bf551b2767](https://linux-hardware.org/?probe=bf551b2767) | May 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [8747e49a83](https://linux-hardware.org/?probe=8747e49a83) | May 14, 2023 |
| ASUSTek       | N76VZ                       | Notebook    | [fc6d34934a](https://linux-hardware.org/?probe=fc6d34934a) | May 14, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [df19e8413c](https://linux-hardware.org/?probe=df19e8413c) | May 14, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [64237b5d6e](https://linux-hardware.org/?probe=64237b5d6e) | May 14, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [091a42a1c0](https://linux-hardware.org/?probe=091a42a1c0) | May 14, 2023 |
| Intel         | DH77DF AAG40293-301         | Desktop     | [f35c753afd](https://linux-hardware.org/?probe=f35c753afd) | May 14, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [2381fb0c55](https://linux-hardware.org/?probe=2381fb0c55) | May 14, 2023 |
| Intel         | DH77DF AAG40293-301         | Desktop     | [65ad7c5ad5](https://linux-hardware.org/?probe=65ad7c5ad5) | May 13, 2023 |
| HP            | Notebook                    | Notebook    | [c14e7a41cf](https://linux-hardware.org/?probe=c14e7a41cf) | May 13, 2023 |
| Samsung       | 730QED                      | Convertible | [d1dc669b1f](https://linux-hardware.org/?probe=d1dc669b1f) | May 13, 2023 |
| HP            | Notebook                    | Notebook    | [726fa4fcd1](https://linux-hardware.org/?probe=726fa4fcd1) | May 13, 2023 |
| Fujitsu       | D3011-A1 S26361-D3011-A1    | Desktop     | [ede664c4ca](https://linux-hardware.org/?probe=ede664c4ca) | May 13, 2023 |
| Fujitsu       | D3011-A1 S26361-D3011-A1    | Desktop     | [4849aadd59](https://linux-hardware.org/?probe=4849aadd59) | May 13, 2023 |
| Intel         | NUC5CPYB H61145-407         | Mini pc     | [bbb7537d59](https://linux-hardware.org/?probe=bbb7537d59) | May 13, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [a60326fa0a](https://linux-hardware.org/?probe=a60326fa0a) | May 13, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [ed72b68c39](https://linux-hardware.org/?probe=ed72b68c39) | May 13, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [a15b90ff4b](https://linux-hardware.org/?probe=a15b90ff4b) | May 13, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [0239277ed2](https://linux-hardware.org/?probe=0239277ed2) | May 13, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [ef37458c10](https://linux-hardware.org/?probe=ef37458c10) | May 13, 2023 |
| Gateway       | DX4840                      | Desktop     | [b96adf8863](https://linux-hardware.org/?probe=b96adf8863) | May 13, 2023 |
| ASUSTek       | K55DR                       | Notebook    | [e4f7010e78](https://linux-hardware.org/?probe=e4f7010e78) | May 13, 2023 |
| ASUSTek       | K55DR                       | Notebook    | [0d4d8571bf](https://linux-hardware.org/?probe=0d4d8571bf) | May 13, 2023 |
| Intel         | B75                         | Desktop     | [da0a89cf17](https://linux-hardware.org/?probe=da0a89cf17) | May 13, 2023 |
| Samsung       | 550XDA                      | Notebook    | [5f562807be](https://linux-hardware.org/?probe=5f562807be) | May 13, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [79db0c9b3c](https://linux-hardware.org/?probe=79db0c9b3c) | May 13, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [6ade055af7](https://linux-hardware.org/?probe=6ade055af7) | May 13, 2023 |
| Toshiba       | STI 007567                  | Desktop     | [579ec5bb2b](https://linux-hardware.org/?probe=579ec5bb2b) | May 13, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [48c5ff757c](https://linux-hardware.org/?probe=48c5ff757c) | May 13, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [f720713dda](https://linux-hardware.org/?probe=f720713dda) | May 13, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [26beee94a9](https://linux-hardware.org/?probe=26beee94a9) | May 12, 2023 |
| MSI           | GL73 8RC                    | Notebook    | [4eb76264f2](https://linux-hardware.org/?probe=4eb76264f2) | May 12, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [62aab97f35](https://linux-hardware.org/?probe=62aab97f35) | May 12, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | Notebook    | [29e584b980](https://linux-hardware.org/?probe=29e584b980) | May 12, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | Notebook    | [22673e3f0c](https://linux-hardware.org/?probe=22673e3f0c) | May 12, 2023 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [2acd6e02ea](https://linux-hardware.org/?probe=2acd6e02ea) | May 12, 2023 |
| Dell          | Precision 5550              | Notebook    | [f6d4846655](https://linux-hardware.org/?probe=f6d4846655) | May 12, 2023 |
| ASRock        | H510M-ITX/ac                | Desktop     | [9a8da03c1e](https://linux-hardware.org/?probe=9a8da03c1e) | May 12, 2023 |
| Medion        | BTDD-LT                     | Desktop     | [86a5697c9c](https://linux-hardware.org/?probe=86a5697c9c) | May 12, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [29b8cfc7e6](https://linux-hardware.org/?probe=29b8cfc7e6) | May 12, 2023 |
| HP            | ENVY 17                     | Notebook    | [9f71f0b3e1](https://linux-hardware.org/?probe=9f71f0b3e1) | May 12, 2023 |
| MSI           | Stealth GS77 12UH           | Notebook    | [08fdf9cb20](https://linux-hardware.org/?probe=08fdf9cb20) | May 12, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [971b7bfcd1](https://linux-hardware.org/?probe=971b7bfcd1) | May 12, 2023 |
| Panasonic     | CF-19-8                     | Notebook    | [1aa7d4071a](https://linux-hardware.org/?probe=1aa7d4071a) | May 12, 2023 |
| Gigabyte      | MW51-HP0-00                 | Desktop     | [ed263fdd1b](https://linux-hardware.org/?probe=ed263fdd1b) | May 12, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [01b1668378](https://linux-hardware.org/?probe=01b1668378) | May 12, 2023 |
| Biostar       | A68N-5600E                  | Desktop     | [55db0c720e](https://linux-hardware.org/?probe=55db0c720e) | May 12, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [b054e28875](https://linux-hardware.org/?probe=b054e28875) | May 12, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [703faeb982](https://linux-hardware.org/?probe=703faeb982) | May 12, 2023 |
| Toshiba       | STI NA 1401                 | Notebook    | [c9aa3a7539](https://linux-hardware.org/?probe=c9aa3a7539) | May 12, 2023 |
| ASUSTek       | PN51-S1                     | Mini pc     | [18e6ede132](https://linux-hardware.org/?probe=18e6ede132) | May 12, 2023 |
| Samsung       | R430/R480                   | Notebook    | [076f13d198](https://linux-hardware.org/?probe=076f13d198) | May 12, 2023 |
| Intel         | DH87RL AAG74240-403         | Desktop     | [888f0a2923](https://linux-hardware.org/?probe=888f0a2923) | May 12, 2023 |
| Dell          | Latitude 5300               | Notebook    | [917bfc93a5](https://linux-hardware.org/?probe=917bfc93a5) | May 12, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [7b966568cc](https://linux-hardware.org/?probe=7b966568cc) | May 12, 2023 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [c9ad858393](https://linux-hardware.org/?probe=c9ad858393) | May 12, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [40d2790e0a](https://linux-hardware.org/?probe=40d2790e0a) | May 12, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [a47136c4d8](https://linux-hardware.org/?probe=a47136c4d8) | May 12, 2023 |
| ASUSTek       | P8P67 LE                    | Desktop     | [cae9bea146](https://linux-hardware.org/?probe=cae9bea146) | May 12, 2023 |
| Digma         | Pro Magnus M DN16R7-ADXW... | Notebook    | [4e4a1278e9](https://linux-hardware.org/?probe=4e4a1278e9) | May 12, 2023 |
| Intel         | NUC5i7RYB H73774-104        | Mini pc     | [2438860233](https://linux-hardware.org/?probe=2438860233) | May 12, 2023 |
| MSI           | H61M-P20/W8                 | Desktop     | [b727300be6](https://linux-hardware.org/?probe=b727300be6) | May 11, 2023 |
| Biostar       | B450MH                      | Desktop     | [e5dac06f4e](https://linux-hardware.org/?probe=e5dac06f4e) | May 11, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [9495c6ca84](https://linux-hardware.org/?probe=9495c6ca84) | May 11, 2023 |
| Biostar       | B450MH                      | Desktop     | [12659ad2e2](https://linux-hardware.org/?probe=12659ad2e2) | May 11, 2023 |
| Dell          | Latitude 5530               | Notebook    | [ade218e4fa](https://linux-hardware.org/?probe=ade218e4fa) | May 11, 2023 |
| Gigabyte      | Z270N-Gaming 5              | Desktop     | [c056fdd9a8](https://linux-hardware.org/?probe=c056fdd9a8) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TN34... | Convertible | [b3342e7343](https://linux-hardware.org/?probe=b3342e7343) | May 11, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [e18646482f](https://linux-hardware.org/?probe=e18646482f) | May 11, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [f56ecb2642](https://linux-hardware.org/?probe=f56ecb2642) | May 11, 2023 |
| Lenovo        | Slim 9 14IAP7 82T1          | Notebook    | [6c391cd64d](https://linux-hardware.org/?probe=6c391cd64d) | May 11, 2023 |
| HP            | Pavilion Laptop 15-eg1xx... | Notebook    | [9ed9aa95e8](https://linux-hardware.org/?probe=9ed9aa95e8) | May 11, 2023 |
| Lenovo        | Slim 9 14IAP7 82T1          | Notebook    | [4d2b811352](https://linux-hardware.org/?probe=4d2b811352) | May 11, 2023 |
| Dell          | 0X8DXD A00                  | Desktop     | [1e8359a02c](https://linux-hardware.org/?probe=1e8359a02c) | May 11, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [1f22322c4a](https://linux-hardware.org/?probe=1f22322c4a) | May 11, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f55f75ca7d](https://linux-hardware.org/?probe=f55f75ca7d) | May 11, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [8c58684afd](https://linux-hardware.org/?probe=8c58684afd) | May 11, 2023 |
| TUXEDO        | Book_XA1510                 | Notebook    | [9aed9e823a](https://linux-hardware.org/?probe=9aed9e823a) | May 11, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [328d899b1c](https://linux-hardware.org/?probe=328d899b1c) | May 11, 2023 |
| Dell          | 0T10XW A02                  | Desktop     | [a488bed661](https://linux-hardware.org/?probe=a488bed661) | May 11, 2023 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [c26f143862](https://linux-hardware.org/?probe=c26f143862) | May 11, 2023 |
| Lenovo        | 310B SDK0J40705 WIN 3425... | Desktop     | [53d9e318f6](https://linux-hardware.org/?probe=53d9e318f6) | May 11, 2023 |
| Biostar       | H110MHV3                    | Desktop     | [e1ce381308](https://linux-hardware.org/?probe=e1ce381308) | May 11, 2023 |
| Biostar       | H110MHV3                    | Desktop     | [5b0f8f8419](https://linux-hardware.org/?probe=5b0f8f8419) | May 11, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [a7178f5792](https://linux-hardware.org/?probe=a7178f5792) | May 11, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [3df5f7ec7e](https://linux-hardware.org/?probe=3df5f7ec7e) | May 11, 2023 |
| Dell          | 0Y958C A00                  | Desktop     | [fb1b987ad5](https://linux-hardware.org/?probe=fb1b987ad5) | May 10, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [1b20151b4c](https://linux-hardware.org/?probe=1b20151b4c) | May 10, 2023 |
| Dell          | 076VHM A02                  | Desktop     | [7f1984ec16](https://linux-hardware.org/?probe=7f1984ec16) | May 10, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [e9e13fa531](https://linux-hardware.org/?probe=e9e13fa531) | May 10, 2023 |
| Digma         | EVE 11 C422 ES1068EW        | Notebook    | [6c6b40d9de](https://linux-hardware.org/?probe=6c6b40d9de) | May 10, 2023 |
| HP            | Pavilion g6                 | Notebook    | [2eaacf14f6](https://linux-hardware.org/?probe=2eaacf14f6) | May 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [554b258b3c](https://linux-hardware.org/?probe=554b258b3c) | May 10, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [d21ea25d7a](https://linux-hardware.org/?probe=d21ea25d7a) | May 10, 2023 |
| Dell          | Inspiron 5590               | Notebook    | [117a2b318d](https://linux-hardware.org/?probe=117a2b318d) | May 10, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [4d0b606423](https://linux-hardware.org/?probe=4d0b606423) | May 10, 2023 |
| Radxa         | ROCK 5B                     | Soc         | [8784f07eed](https://linux-hardware.org/?probe=8784f07eed) | May 10, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [7a97d5d5ab](https://linux-hardware.org/?probe=7a97d5d5ab) | May 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [3ea46668c4](https://linux-hardware.org/?probe=3ea46668c4) | May 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [601a09abf6](https://linux-hardware.org/?probe=601a09abf6) | May 10, 2023 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [66fe960f10](https://linux-hardware.org/?probe=66fe960f10) | May 10, 2023 |
| Dell          | 0GM819                      | Desktop     | [ccd99ab6c3](https://linux-hardware.org/?probe=ccd99ab6c3) | May 10, 2023 |
| Sony          | SVE1713K1EB                 | Notebook    | [96244b73e7](https://linux-hardware.org/?probe=96244b73e7) | May 10, 2023 |
| Fujitsu Si... | AMILO Pa 2548               | Notebook    | [d5d7d8308f](https://linux-hardware.org/?probe=d5d7d8308f) | May 10, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [7b956abe69](https://linux-hardware.org/?probe=7b956abe69) | May 10, 2023 |
| Intel         | NUC6i3SYB H81132-505        | Mini pc     | [a96034cf9a](https://linux-hardware.org/?probe=a96034cf9a) | May 10, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [35750a650a](https://linux-hardware.org/?probe=35750a650a) | May 10, 2023 |
| ASUSTek       | P8Z68-M PRO                 | Desktop     | [37b88384a5](https://linux-hardware.org/?probe=37b88384a5) | May 10, 2023 |
| AZW           | MINI S 10                   | Desktop     | [c64432906e](https://linux-hardware.org/?probe=c64432906e) | May 10, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [46015ea246](https://linux-hardware.org/?probe=46015ea246) | May 10, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [02c4a35621](https://linux-hardware.org/?probe=02c4a35621) | May 10, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [a9df4bc7fb](https://linux-hardware.org/?probe=a9df4bc7fb) | May 10, 2023 |
| Lenovo        | 371C WIN SDK0J40709 3259... | All in one  | [501c674a9e](https://linux-hardware.org/?probe=501c674a9e) | May 10, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [6fd3dea188](https://linux-hardware.org/?probe=6fd3dea188) | May 10, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [e55b8813e3](https://linux-hardware.org/?probe=e55b8813e3) | May 10, 2023 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [184f099d28](https://linux-hardware.org/?probe=184f099d28) | May 10, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [9caca8f4cc](https://linux-hardware.org/?probe=9caca8f4cc) | May 10, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [ab5b69b742](https://linux-hardware.org/?probe=ab5b69b742) | May 10, 2023 |
| ASUSTek       | H170-PRO                    | Desktop     | [8f41b17a9b](https://linux-hardware.org/?probe=8f41b17a9b) | May 10, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JW... | Notebook    | [0308c5d0c5](https://linux-hardware.org/?probe=0308c5d0c5) | May 10, 2023 |
| Dell          | 0YTPH7 A01                  | All in one  | [e84bcda5c6](https://linux-hardware.org/?probe=e84bcda5c6) | May 10, 2023 |
| eMachines     | E625                        | Notebook    | [1271e33078](https://linux-hardware.org/?probe=1271e33078) | May 10, 2023 |
| Dell          | Inspiron 5590               | Notebook    | [9c53d54cae](https://linux-hardware.org/?probe=9c53d54cae) | May 10, 2023 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [da9df7e3c6](https://linux-hardware.org/?probe=da9df7e3c6) | May 10, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [966821ec0d](https://linux-hardware.org/?probe=966821ec0d) | May 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [6ddb2fa975](https://linux-hardware.org/?probe=6ddb2fa975) | May 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [16bdfe6490](https://linux-hardware.org/?probe=16bdfe6490) | May 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [813acd1225](https://linux-hardware.org/?probe=813acd1225) | May 10, 2023 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [fbe7b6d2bf](https://linux-hardware.org/?probe=fbe7b6d2bf) | May 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1bd26fc56f](https://linux-hardware.org/?probe=1bd26fc56f) | May 10, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [afde593648](https://linux-hardware.org/?probe=afde593648) | May 10, 2023 |
| eMachines     | E625                        | Notebook    | [3160c872b8](https://linux-hardware.org/?probe=3160c872b8) | May 10, 2023 |
| Gateway       | P-7805u                     | Notebook    | [2713d979c4](https://linux-hardware.org/?probe=2713d979c4) | May 10, 2023 |
| Gateway       | P-7805u                     | Notebook    | [bdf7e6c628](https://linux-hardware.org/?probe=bdf7e6c628) | May 10, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [18afa7a07b](https://linux-hardware.org/?probe=18afa7a07b) | May 10, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5c616bbd80](https://linux-hardware.org/?probe=5c616bbd80) | May 10, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [89d87ca773](https://linux-hardware.org/?probe=89d87ca773) | May 09, 2023 |
| Thomson       | WWNEO14C-4BK32F             | Notebook    | [28a4468d2d](https://linux-hardware.org/?probe=28a4468d2d) | May 09, 2023 |
| Intel         | DQ57TM AAE70931-402         | Desktop     | [df02c1cce7](https://linux-hardware.org/?probe=df02c1cce7) | May 09, 2023 |
| HP            | 18E5                        | Desktop     | [09eb27d0c5](https://linux-hardware.org/?probe=09eb27d0c5) | May 09, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [d01779a93b](https://linux-hardware.org/?probe=d01779a93b) | May 09, 2023 |
| HP            | Pavilion g6                 | Notebook    | [fc978d0a03](https://linux-hardware.org/?probe=fc978d0a03) | May 09, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [745096932c](https://linux-hardware.org/?probe=745096932c) | May 09, 2023 |
| Toshiba       | Satellite P500              | Notebook    | [16472912d5](https://linux-hardware.org/?probe=16472912d5) | May 09, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [3ad22447bb](https://linux-hardware.org/?probe=3ad22447bb) | May 09, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [575bffc7a9](https://linux-hardware.org/?probe=575bffc7a9) | May 09, 2023 |
| MSI           | Katana 17 B12UCXK           | Notebook    | [15b9d97c10](https://linux-hardware.org/?probe=15b9d97c10) | May 09, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [20365b7b02](https://linux-hardware.org/?probe=20365b7b02) | May 09, 2023 |
| HP            | 3398                        | Desktop     | [360aa1ac89](https://linux-hardware.org/?probe=360aa1ac89) | May 09, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [e7ffe2585f](https://linux-hardware.org/?probe=e7ffe2585f) | May 09, 2023 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [588003adc9](https://linux-hardware.org/?probe=588003adc9) | May 09, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [6c5da31f8b](https://linux-hardware.org/?probe=6c5da31f8b) | May 09, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [32fba9e487](https://linux-hardware.org/?probe=32fba9e487) | May 09, 2023 |
| Dell          | G5 5590                     | Notebook    | [c07c29d5de](https://linux-hardware.org/?probe=c07c29d5de) | May 09, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [58a9b45939](https://linux-hardware.org/?probe=58a9b45939) | May 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [0225c3c300](https://linux-hardware.org/?probe=0225c3c300) | May 09, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [bcccbb24de](https://linux-hardware.org/?probe=bcccbb24de) | May 09, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [ff3919b7f3](https://linux-hardware.org/?probe=ff3919b7f3) | May 09, 2023 |
| Dell          | 0KYJ8C A02                  | Desktop     | [ce4726c253](https://linux-hardware.org/?probe=ce4726c253) | May 09, 2023 |
| Lenovo        | ThinkCentre M71z 1782W14    | Desktop     | [f5a1b23281](https://linux-hardware.org/?probe=f5a1b23281) | May 09, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [db93afa653](https://linux-hardware.org/?probe=db93afa653) | May 09, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [228e778389](https://linux-hardware.org/?probe=228e778389) | May 09, 2023 |
| Lanix Amer... | A V19                       | Notebook    | [31e64dbd5d](https://linux-hardware.org/?probe=31e64dbd5d) | May 08, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [c8ab230418](https://linux-hardware.org/?probe=c8ab230418) | May 08, 2023 |
| Samsung       | 950XED                      | Notebook    | [15e2cfcac7](https://linux-hardware.org/?probe=15e2cfcac7) | May 08, 2023 |
| Dell          | Latitude E5440              | Notebook    | [6db42a9acc](https://linux-hardware.org/?probe=6db42a9acc) | May 08, 2023 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [0a758d5a5d](https://linux-hardware.org/?probe=0a758d5a5d) | May 08, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [1f7840b315](https://linux-hardware.org/?probe=1f7840b315) | May 08, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [e44f7dfac5](https://linux-hardware.org/?probe=e44f7dfac5) | May 08, 2023 |
| ASRock        | J4125M                      | Desktop     | [a702df382b](https://linux-hardware.org/?probe=a702df382b) | May 08, 2023 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [ddf0cb8a28](https://linux-hardware.org/?probe=ddf0cb8a28) | May 08, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [995e6d9580](https://linux-hardware.org/?probe=995e6d9580) | May 08, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [08df3c35ee](https://linux-hardware.org/?probe=08df3c35ee) | May 08, 2023 |
| Avell High... | 1513                        | Notebook    | [6e383641d6](https://linux-hardware.org/?probe=6e383641d6) | May 08, 2023 |
| HP            | EliteBook 725 G4            | Notebook    | [bf3ce4741e](https://linux-hardware.org/?probe=bf3ce4741e) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [f4d1f788e1](https://linux-hardware.org/?probe=f4d1f788e1) | May 08, 2023 |
| Intel         | NUC11TNBi5 M61235-402       | Mini pc     | [b85a510a03](https://linux-hardware.org/?probe=b85a510a03) | May 08, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [dc43e4a7e3](https://linux-hardware.org/?probe=dc43e4a7e3) | May 08, 2023 |
| HP            | 1998                        | Desktop     | [2ed500d3e9](https://linux-hardware.org/?probe=2ed500d3e9) | May 08, 2023 |
| HP            | 1998                        | Desktop     | [558c305af2](https://linux-hardware.org/?probe=558c305af2) | May 08, 2023 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [f79b5c8672](https://linux-hardware.org/?probe=f79b5c8672) | May 08, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [0458d9f44b](https://linux-hardware.org/?probe=0458d9f44b) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X432... | Notebook    | [395097d3a3](https://linux-hardware.org/?probe=395097d3a3) | May 08, 2023 |
| Dell          | Latitude 7390               | Notebook    | [dc5c96e431](https://linux-hardware.org/?probe=dc5c96e431) | May 08, 2023 |
| Sony          | VPCZ12C5E                   | Notebook    | [512da95fb0](https://linux-hardware.org/?probe=512da95fb0) | May 08, 2023 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [223431f202](https://linux-hardware.org/?probe=223431f202) | May 08, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [78e63b3bd3](https://linux-hardware.org/?probe=78e63b3bd3) | May 07, 2023 |
| Dell          | Inspiron 13-7359            | Notebook    | [30bd232e19](https://linux-hardware.org/?probe=30bd232e19) | May 07, 2023 |
| Dell          | Inspiron 13-7359            | Notebook    | [923397bc88](https://linux-hardware.org/?probe=923397bc88) | May 07, 2023 |
| Dell          | Latitude 5310               | Notebook    | [d72db172f0](https://linux-hardware.org/?probe=d72db172f0) | May 07, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7e003cf7a9](https://linux-hardware.org/?probe=7e003cf7a9) | May 07, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [5b5eba537a](https://linux-hardware.org/?probe=5b5eba537a) | May 07, 2023 |
| Dell          | MXG061                      | Notebook    | [8ef701b61d](https://linux-hardware.org/?probe=8ef701b61d) | May 07, 2023 |
| NEC Comput... | IH81M                       | Desktop     | [407098c17f](https://linux-hardware.org/?probe=407098c17f) | May 07, 2023 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [c174fcc2d8](https://linux-hardware.org/?probe=c174fcc2d8) | May 07, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [6089dfdeab](https://linux-hardware.org/?probe=6089dfdeab) | May 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [816f9e047a](https://linux-hardware.org/?probe=816f9e047a) | May 07, 2023 |
| ASUSTek       | STRIX B250I GAMING          | Desktop     | [536e6e7cc9](https://linux-hardware.org/?probe=536e6e7cc9) | May 07, 2023 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | Desktop     | [94ab5e431c](https://linux-hardware.org/?probe=94ab5e431c) | May 07, 2023 |
| Sony          | VPCZ12C5E                   | Notebook    | [67e1fdf9c2](https://linux-hardware.org/?probe=67e1fdf9c2) | May 07, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [020041a666](https://linux-hardware.org/?probe=020041a666) | May 07, 2023 |
| HP            | x2 210                      | Notebook    | [f7a174063f](https://linux-hardware.org/?probe=f7a174063f) | May 07, 2023 |
| HP            | x2 210                      | Notebook    | [b3c5b71d27](https://linux-hardware.org/?probe=b3c5b71d27) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [25c4b5fe60](https://linux-hardware.org/?probe=25c4b5fe60) | May 07, 2023 |
| MSI           | 2A9C                        | Desktop     | [4acb37f728](https://linux-hardware.org/?probe=4acb37f728) | May 07, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [dce7e41a72](https://linux-hardware.org/?probe=dce7e41a72) | May 07, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [64db3d70f1](https://linux-hardware.org/?probe=64db3d70f1) | May 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b1b0fa7485](https://linux-hardware.org/?probe=b1b0fa7485) | May 07, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [efb597952f](https://linux-hardware.org/?probe=efb597952f) | May 07, 2023 |
| Datto         | SSD                         | Desktop     | [c086218bd4](https://linux-hardware.org/?probe=c086218bd4) | May 07, 2023 |
| Toshiba       | Satellite C855D             | Notebook    | [7cdcc71b4e](https://linux-hardware.org/?probe=7cdcc71b4e) | May 07, 2023 |
| ASUSTek       | Z77-A                       | Desktop     | [92b5951471](https://linux-hardware.org/?probe=92b5951471) | May 07, 2023 |
| ASRock        | J4125M                      | Desktop     | [57865d6cea](https://linux-hardware.org/?probe=57865d6cea) | May 07, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | Notebook    | [845c2112be](https://linux-hardware.org/?probe=845c2112be) | May 06, 2023 |
| Intel         | H61                         | Desktop     | [cd89c5b708](https://linux-hardware.org/?probe=cd89c5b708) | May 06, 2023 |
| HP            | ENVY TS 17                  | Notebook    | [d18f9c3e77](https://linux-hardware.org/?probe=d18f9c3e77) | May 06, 2023 |
| Gateway       | DX4870                      | Desktop     | [dcd0bbb01a](https://linux-hardware.org/?probe=dcd0bbb01a) | May 06, 2023 |
| Dell          | Studio 1749                 | Notebook    | [43eb37cfd7](https://linux-hardware.org/?probe=43eb37cfd7) | May 06, 2023 |
| Dell          | Inspiron 3537               | Notebook    | [5b49eec8c6](https://linux-hardware.org/?probe=5b49eec8c6) | May 06, 2023 |
| HP            | Notebook                    | Notebook    | [cb89261339](https://linux-hardware.org/?probe=cb89261339) | May 06, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [3014e7989f](https://linux-hardware.org/?probe=3014e7989f) | May 06, 2023 |
| ASRock        | N3150-NUC                   | Desktop     | [5775b2c94f](https://linux-hardware.org/?probe=5775b2c94f) | May 06, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [00794346db](https://linux-hardware.org/?probe=00794346db) | May 06, 2023 |
| ASUSTek       | X441BA                      | Notebook    | [326309c1f1](https://linux-hardware.org/?probe=326309c1f1) | May 06, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [eb774628af](https://linux-hardware.org/?probe=eb774628af) | May 06, 2023 |
| Unknown       | Unknown                     | Soc         | [2fedff1d10](https://linux-hardware.org/?probe=2fedff1d10) | May 06, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [20461b100d](https://linux-hardware.org/?probe=20461b100d) | May 06, 2023 |
| ASUSTek       | X441BA                      | Notebook    | [dee3bc2cdb](https://linux-hardware.org/?probe=dee3bc2cdb) | May 06, 2023 |
| Google        | Samus                       | Notebook    | [aed9bd140f](https://linux-hardware.org/?probe=aed9bd140f) | May 06, 2023 |
| Notebook      | N7x0WU                      | Notebook    | [985f971691](https://linux-hardware.org/?probe=985f971691) | May 06, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [ee58ce6d9c](https://linux-hardware.org/?probe=ee58ce6d9c) | May 06, 2023 |
| Acer          | EG43M                       | Desktop     | [50ee9c3423](https://linux-hardware.org/?probe=50ee9c3423) | May 06, 2023 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [f9d2b57c91](https://linux-hardware.org/?probe=f9d2b57c91) | May 06, 2023 |
| Dell          | 0X6H47 A01                  | Server      | [6a0af69b4a](https://linux-hardware.org/?probe=6a0af69b4a) | May 06, 2023 |
| ASRock        | 945GCM-S                    | Desktop     | [940d88bfce](https://linux-hardware.org/?probe=940d88bfce) | May 06, 2023 |
| ASUSTek       | ZenBook UX434FL_UX434FL     | Notebook    | [21ef45e81c](https://linux-hardware.org/?probe=21ef45e81c) | May 06, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [e12a1d28ba](https://linux-hardware.org/?probe=e12a1d28ba) | May 06, 2023 |
| Dell          | Inspiron 7558               | Notebook    | [aab9b575d7](https://linux-hardware.org/?probe=aab9b575d7) | May 06, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [b0464a0b99](https://linux-hardware.org/?probe=b0464a0b99) | May 06, 2023 |
| Packard Be... | EasyNote TE69HW             | Notebook    | [fff5650658](https://linux-hardware.org/?probe=fff5650658) | May 05, 2023 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [870a49d90c](https://linux-hardware.org/?probe=870a49d90c) | May 05, 2023 |
| Fujitsu Si... | AMILO Pa 2548               | Notebook    | [449779fbe4](https://linux-hardware.org/?probe=449779fbe4) | May 05, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [50fba20da2](https://linux-hardware.org/?probe=50fba20da2) | May 05, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [ec3e2f4be9](https://linux-hardware.org/?probe=ec3e2f4be9) | May 05, 2023 |
| Fujitsu Si... | AMILO Pa 2548               | Notebook    | [ffce6dd6d5](https://linux-hardware.org/?probe=ffce6dd6d5) | May 05, 2023 |
| Biostar       | G41D3C                      | Desktop     | [15680367e1](https://linux-hardware.org/?probe=15680367e1) | May 05, 2023 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [db330cab38](https://linux-hardware.org/?probe=db330cab38) | May 05, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [14c71828ca](https://linux-hardware.org/?probe=14c71828ca) | May 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [8774a893d6](https://linux-hardware.org/?probe=8774a893d6) | May 05, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [5491fd5858](https://linux-hardware.org/?probe=5491fd5858) | May 05, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [55e2b9f062](https://linux-hardware.org/?probe=55e2b9f062) | May 05, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [70f39dc2df](https://linux-hardware.org/?probe=70f39dc2df) | May 05, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [2e4e7c801d](https://linux-hardware.org/?probe=2e4e7c801d) | May 05, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [d27392828f](https://linux-hardware.org/?probe=d27392828f) | May 05, 2023 |
| ASUSTek       | P5KPL-AM/PS                 | Desktop     | [a5c1634444](https://linux-hardware.org/?probe=a5c1634444) | May 05, 2023 |
| MSI           | Z170A GAMING M5             | Desktop     | [3f515702d2](https://linux-hardware.org/?probe=3f515702d2) | May 05, 2023 |
| Medion        | Akoya E1317T                | Notebook    | [e8eb05a52a](https://linux-hardware.org/?probe=e8eb05a52a) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 4174W2X      | Notebook    | [082029ecf5](https://linux-hardware.org/?probe=082029ecf5) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 4174W2X      | Notebook    | [e2f37d94cd](https://linux-hardware.org/?probe=e2f37d94cd) | May 05, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [867e98f955](https://linux-hardware.org/?probe=867e98f955) | May 05, 2023 |
| HP            | 21EF                        | Desktop     | [6dd5a8409e](https://linux-hardware.org/?probe=6dd5a8409e) | May 05, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 784       | 7.57%   |
| 5.15.0-52-generic | 676       | 6.53%   |
| 5.15.0-58-generic | 638       | 6.16%   |
| 5.15.0-43-generic | 539       | 5.21%   |
| 5.19.0-35-generic | 527       | 5.09%   |
| 5.15.0-48-generic | 527       | 5.09%   |
| 5.15.0-47-generic | 490       | 4.73%   |
| 5.19.0-32-generic | 452       | 4.37%   |
| 5.19.0-41-generic | 441       | 4.26%   |
| 5.15.0-46-generic | 405       | 3.91%   |
| 5.15.0-53-generic | 392       | 3.79%   |
| 5.19.0-38-generic | 374       | 3.61%   |
| 5.15.0-25-generic | 331       | 3.2%    |
| 5.15.0-27-generic | 308       | 2.97%   |
| 5.15.0-40-generic | 282       | 2.72%   |
| 5.15.0-41-generic | 278       | 2.68%   |
| 5.15.0-50-generic | 242       | 2.34%   |
| 5.15.0-60-generic | 236       | 2.28%   |
| 5.15.0-57-generic | 201       | 1.94%   |
| 5.15.0-33-generic | 178       | 1.72%   |
| 5.19.0-40-generic | 167       | 1.61%   |
| 5.15.0-30-generic | 157       | 1.52%   |
| 5.19.0-43-generic | 154       | 1.49%   |
| 5.15.0-39-generic | 134       | 1.29%   |
| 5.19.0-42-generic | 124       | 1.2%    |
| 5.15.0-37-generic | 107       | 1.03%   |
| 5.15.0-35-generic | 101       | 0.98%   |
| 5.15.0-67-generic | 96        | 0.93%   |
| 5.15.0-69-generic | 80        | 0.77%   |
| 5.15.0-71-generic | 60        | 0.58%   |
| 5.15.0-23-generic | 37        | 0.36%   |
| 5.15.0-72-generic | 26        | 0.25%   |
| 5.15.0-18-generic | 26        | 0.25%   |
| 5.15.0-70-generic | 18        | 0.17%   |
| 5.15.0-73-generic | 17        | 0.16%   |
| 5.15.0-1006-raspi | 16        | 0.15%   |
| 5.15.0-59-generic | 13        | 0.13%   |
| 5.15.0-54-generic | 13        | 0.13%   |
| 5.15.0-32-generic | 13        | 0.13%   |
| 5.15.0-1012-raspi | 13        | 0.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.0   | 7010      | 72.75%  |
| 5.19.0   | 2137      | 22.18%  |
| 5.17.0   | 86        | 0.89%   |
| 5.14.0   | 31        | 0.32%   |
| 5.13.0   | 29        | 0.3%    |
| 6.0.0    | 26        | 0.27%   |
| 6.1.0    | 18        | 0.19%   |
| 5.18.0   | 17        | 0.18%   |
| 5.19.5   | 10        | 0.1%    |
| 6.2.11   | 9         | 0.09%   |
| 6.2.0    | 9         | 0.09%   |
| 6.0.9    | 9         | 0.09%   |
| 5.17.5   | 8         | 0.08%   |
| 5.17.1   | 8         | 0.08%   |
| 6.2.8    | 7         | 0.07%   |
| 6.2.2    | 7         | 0.07%   |
| 6.3.1    | 6         | 0.06%   |
| 5.10.110 | 6         | 0.06%   |
| 6.2.10   | 5         | 0.05%   |
| 6.0.1    | 5         | 0.05%   |
| 5.18.10  | 5         | 0.05%   |
| 5.17.9   | 5         | 0.05%   |
| 6.2.9    | 4         | 0.04%   |
| 6.1.12   | 4         | 0.04%   |
| 6.1.11   | 4         | 0.04%   |
| 6.0.6    | 4         | 0.04%   |
| 5.4.0    | 4         | 0.04%   |
| 5.19.17  | 4         | 0.04%   |
| 5.18.8   | 4         | 0.04%   |
| 5.17.8   | 4         | 0.04%   |
| 5.17.2   | 4         | 0.04%   |
| 5.17.15  | 4         | 0.04%   |
| 5.16.0   | 4         | 0.04%   |
| 5.13.19  | 4         | 0.04%   |
| 6.3.3    | 3         | 0.03%   |
| 6.2.6    | 3         | 0.03%   |
| 6.2.1    | 3         | 0.03%   |
| 6.1.9    | 3         | 0.03%   |
| 6.1.6    | 3         | 0.03%   |
| 6.0.8    | 3         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 7031      | 73.05%  |
| 5.19    | 2161      | 22.45%  |
| 5.17    | 128       | 1.33%   |
| 6.0     | 59        | 0.61%   |
| 6.2     | 52        | 0.54%   |
| 5.18    | 44        | 0.46%   |
| 6.1     | 43        | 0.45%   |
| 5.13    | 33        | 0.34%   |
| 5.14    | 31        | 0.32%   |
| 6.3     | 12        | 0.12%   |
| 5.10    | 8         | 0.08%   |
| 5.16    | 7         | 0.07%   |
| 5.4     | 6         | 0.06%   |
| 5.8     | 3         | 0.03%   |
| 5.11    | 3         | 0.03%   |
| 6       | 1         | 0.01%   |
| 4.9     | 1         | 0.01%   |
| 3.16    | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 9296      | 98.98%  |
| aarch64 | 89        | 0.95%   |
| armv7l  | 6         | 0.06%   |
| Unknown | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 8780      | 93.31%  |
| Unknown           | 381       | 4.05%   |
| X-Cinnamon        | 74        | 0.79%   |
| GNUstep           | 73        | 0.78%   |
| GNOME Flashback   | 48        | 0.51%   |
| i3                | 15        | 0.16%   |
| GNOME Classic     | 15        | 0.16%   |
| sway              | 4         | 0.04%   |
| Cinnamon          | 4         | 0.04%   |
| awesome           | 4         | 0.04%   |
| DWM               | 2         | 0.02%   |
| Yaru:ubuntu:GNOME | 1         | 0.01%   |
| xsession          | 1         | 0.01%   |
| ubuntu=GNOME      | 1         | 0.01%   |
| ubuntu            | 1         | 0.01%   |
| ratflow           | 1         | 0.01%   |
| Pantheon          | 1         | 0.01%   |
| INPT              | 1         | 0.01%   |
| i3-with-shmlog    | 1         | 0.01%   |
| fluxbox           | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 5991      | 62.75%  |
| X11     | 3028      | 31.72%  |
| Tty     | 325       | 3.4%    |
| Unknown | 202       | 2.12%   |
| Web     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM3    | 8434      | 89.49%  |
| Unknown | 710       | 7.53%   |
| LightDM | 200       | 2.12%   |
| GDM     | 37        | 0.39%   |
| SDDM    | 32        | 0.34%   |
| SLiM    | 9         | 0.1%    |
| XDM     | 1         | 0.01%   |
| LXDM    | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 4375      | 46.45%  |
| de_DE   | 807       | 8.57%   |
| fr_FR   | 542       | 5.75%   |
| en_GB   | 473       | 5.02%   |
| pt_BR   | 358       | 3.8%    |
| it_IT   | 313       | 3.32%   |
| en_IN   | 244       | 2.59%   |
| ru_RU   | 237       | 2.52%   |
| en_CA   | 226       | 2.4%    |
| es_ES   | 219       | 2.33%   |
| en_AU   | 125       | 1.33%   |
| pl_PL   | 122       | 1.3%    |
| C       | 104       | 1.1%    |
| nl_NL   | 94        | 1%      |
| Unknown | 76        | 0.81%   |
| cs_CZ   | 68        | 0.72%   |
| es_MX   | 62        | 0.66%   |
| zh_CN   | 58        | 0.62%   |
| es_AR   | 53        | 0.56%   |
| hu_HU   | 52        | 0.55%   |
| en_ZA   | 52        | 0.55%   |
| sv_SE   | 50        | 0.53%   |
| de_AT   | 49        | 0.52%   |
| ja_JP   | 41        | 0.44%   |
| pt_PT   | 37        | 0.39%   |
| de_CH   | 36        | 0.38%   |
| tr_TR   | 32        | 0.34%   |
| en_NZ   | 30        | 0.32%   |
| en_PH   | 29        | 0.31%   |
| fi_FI   | 27        | 0.29%   |
| es_CO   | 27        | 0.29%   |
| fr_BE   | 25        | 0.27%   |
| ko_KR   | 21        | 0.22%   |
| el_GR   | 20        | 0.21%   |
| es_CL   | 18        | 0.19%   |
| da_DK   | 17        | 0.18%   |
| nb_NO   | 16        | 0.17%   |
| ro_RO   | 15        | 0.16%   |
| nl_BE   | 15        | 0.16%   |
| fr_CA   | 13        | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 5643      | 59.48%  |
| EFI  | 3844      | 40.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type          | Computers | Percent |
|---------------|-----------|---------|
| Ext4          | 8351      | 87.88%  |
| Tmpfs         | 487       | 5.12%   |
| Overlay       | 277       | 2.91%   |
| Zfs           | 219       | 2.3%    |
| Btrfs         | 102       | 1.07%   |
| Xfs           | 36        | 0.38%   |
| Ext2          | 14        | 0.15%   |
| Ext3          | 9         | 0.09%   |
| Unknown       | 4         | 0.04%   |
| XXXX          | 1         | 0.01%   |
| XXX4          | 1         | 0.01%   |
| Jfs           | 1         | 0.01%   |
| Fuse.snapfuse | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 6474      | 67.4%   |
| Unknown | 2364      | 24.61%  |
| MBR     | 767       | 7.99%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 8374      | 88.39%  |
| Yes       | 1100      | 11.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5890      | 62.27%  |
| Yes       | 3569      | 37.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1435      | 15.28%  |
| Hewlett-Packard         | 1351      | 14.38%  |
| Dell                    | 1323      | 14.09%  |
| Lenovo                  | 1322      | 14.08%  |
| MSI                     | 551       | 5.87%   |
| Gigabyte Technology     | 511       | 5.44%   |
| Acer                    | 483       | 5.14%   |
| Apple                   | 266       | 2.83%   |
| ASRock                  | 252       | 2.68%   |
| Intel                   | 177       | 1.88%   |
| HUAWEI                  | 126       | 1.34%   |
| Toshiba                 | 109       | 1.16%   |
| Samsung Electronics     | 96        | 1.02%   |
| Fujitsu                 | 95        | 1.01%   |
| Unknown                 | 83        | 0.88%   |
| Raspberry Pi Foundation | 73        | 0.78%   |
| Sony                    | 57        | 0.61%   |
| Medion                  | 56        | 0.6%    |
| Alienware               | 45        | 0.48%   |
| Microsoft               | 44        | 0.47%   |
| Notebook                | 42        | 0.45%   |
| Supermicro              | 41        | 0.44%   |
| Timi                    | 36        | 0.38%   |
| Google                  | 35        | 0.37%   |
| Pegatron                | 34        | 0.36%   |
| Packard Bell            | 29        | 0.31%   |
| Chuwi                   | 29        | 0.31%   |
| Positivo                | 28        | 0.3%    |
| Foxconn                 | 27        | 0.29%   |
| AZW                     | 27        | 0.29%   |
| LG Electronics          | 26        | 0.28%   |
| Biostar                 | 24        | 0.26%   |
| Gateway                 | 19        | 0.2%    |
| ECS                     | 19        | 0.2%    |
| BESSTAR Tech            | 18        | 0.19%   |
| TUXEDO                  | 17        | 0.18%   |
| Shuttle                 | 17        | 0.18%   |
| System76                | 15        | 0.16%   |
| AMI                     | 15        | 0.16%   |
| Avell High Performance  | 13        | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 105       | 1.12%   |
| ASUS All Series                 | 88        | 0.94%   |
| RPi Raspberry Pi                | 48        | 0.51%   |
| Dell OptiPlex 7010              | 29        | 0.31%   |
| HP Notebook                     | 25        | 0.27%   |
| ASUS PRIME A320M-K              | 23        | 0.24%   |
| Dell OptiPlex 9020              | 21        | 0.22%   |
| ASUS TUF Gaming X570-PLUS       | 21        | 0.22%   |
| MSI MS-7C37                     | 18        | 0.19%   |
| MSI MS-7721                     | 18        | 0.19%   |
| ASUS PRIME Z590-P               | 18        | 0.19%   |
| Dell Latitude 5420              | 17        | 0.18%   |
| Dell XPS 15 9520                | 16        | 0.17%   |
| Dell OptiPlex 3020              | 16        | 0.17%   |
| HUAWEI HVY-WXX9                 | 15        | 0.16%   |
| HP EliteBook 840 G8 Notebook PC | 15        | 0.16%   |
| ASUS ROG STRIX B550-F GAMING    | 15        | 0.16%   |
| HP Pavilion Notebook            | 14        | 0.15%   |
| HP Pavilion g6                  | 14        | 0.15%   |
| HP Pavilion dv7                 | 14        | 0.15%   |
| ASUS PRIME X570-PRO             | 14        | 0.15%   |
| Supermicro Super Server         | 13        | 0.14%   |
| MSI MS-7C91                     | 13        | 0.14%   |
| HP EliteBook 840 G5             | 13        | 0.14%   |
| HP 15                           | 13        | 0.14%   |
| Dell OptiPlex 790               | 13        | 0.14%   |
| ASUS PRIME B550M-A              | 13        | 0.14%   |
| HP Pavilion 15                  | 12        | 0.13%   |
| HP EliteBook 840 G3             | 12        | 0.13%   |
| HP Compaq 8200 Elite SFF PC     | 12        | 0.13%   |
| MSI MS-7C52                     | 11        | 0.12%   |
| MSI MS-7C02                     | 11        | 0.12%   |
| HUAWEI NBLK-WAX9X               | 11        | 0.12%   |
| HUAWEI BOM-WXX9                 | 11        | 0.12%   |
| HUAWEI BOHB-WAX9                | 11        | 0.12%   |
| HUAWEI BOD-WXX9                 | 11        | 0.12%   |
| HP Pavilion g7                  | 11        | 0.12%   |
| HP Pavilion dv6                 | 11        | 0.12%   |
| HP EliteBook 8470p              | 11        | 0.12%   |
| Dell XPS 15 9500                | 11        | 0.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 548       | 5.83%   |
| Dell Latitude      | 326       | 3.47%   |
| Acer Aspire        | 318       | 3.39%   |
| Dell Inspiron      | 282       | 3%      |
| Lenovo IdeaPad     | 258       | 2.75%   |
| Dell OptiPlex      | 222       | 2.36%   |
| HP Pavilion        | 214       | 2.28%   |
| HP EliteBook       | 195       | 2.08%   |
| ASUS PRIME         | 194       | 2.07%   |
| Dell XPS           | 169       | 1.8%    |
| ASUS ROG           | 159       | 1.69%   |
| ASUS VivoBook      | 153       | 1.63%   |
| HP ProBook         | 147       | 1.57%   |
| HP Laptop          | 139       | 1.48%   |
| Dell Precision     | 132       | 1.41%   |
| Unknown            | 105       | 1.12%   |
| ASUS TUF           | 101       | 1.08%   |
| HP Compaq          | 96        | 1.02%   |
| HP ENVY            | 89        | 0.95%   |
| Dell Vostro        | 88        | 0.94%   |
| ASUS All           | 88        | 0.94%   |
| Toshiba Satellite  | 85        | 0.91%   |
| RPi Raspberry      | 73        | 0.78%   |
| Lenovo ThinkCentre | 71        | 0.76%   |
| Lenovo ThinkBook   | 67        | 0.71%   |
| Lenovo Yoga        | 64        | 0.68%   |
| ASUS ZenBook       | 58        | 0.62%   |
| Lenovo Legion      | 54        | 0.57%   |
| HP ZBook           | 47        | 0.5%    |
| HP EliteDesk       | 45        | 0.48%   |
| Acer Swift         | 45        | 0.48%   |
| Microsoft Surface  | 44        | 0.47%   |
| ASUS ASUS          | 42        | 0.45%   |
| Acer Nitro         | 37        | 0.39%   |
| HP Spectre         | 34        | 0.36%   |
| Lenovo IdeaPadFlex | 33        | 0.35%   |
| Fujitsu ESPRIMO    | 33        | 0.35%   |
| HP ProDesk         | 32        | 0.34%   |
| Fujitsu LIFEBOOK   | 30        | 0.32%   |
| Dell PowerEdge     | 29        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 1235      | 13.15%  |
| 2020    | 1015      | 10.81%  |
| 2019    | 831       | 8.85%   |
| 2018    | 753       | 8.02%   |
| 2022    | 677       | 7.21%   |
| 2013    | 623       | 6.63%   |
| 2012    | 611       | 6.51%   |
| 2017    | 578       | 6.15%   |
| 2011    | 554       | 5.9%    |
| 2014    | 514       | 5.47%   |
| 2015    | 488       | 5.2%    |
| 2016    | 409       | 4.35%   |
| 2010    | 392       | 4.17%   |
| 2009    | 239       | 2.54%   |
| 2008    | 207       | 2.2%    |
| 2007    | 99        | 1.05%   |
| Unknown | 98        | 1.04%   |
| 2023    | 33        | 0.35%   |
| 2006    | 30        | 0.32%   |
| 2005    | 6         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 5144      | 54.77%  |
| Desktop        | 3293      | 35.06%  |
| Convertible    | 319       | 3.4%    |
| Mini pc        | 193       | 2.05%   |
| All in one     | 145       | 1.54%   |
| Server         | 111       | 1.18%   |
| Tablet         | 94        | 1%      |
| System on chip | 93        | 0.99%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 8469      | 89.77%  |
| Enabled  | 965       | 10.23%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 9346      | 99.51%  |
| Yes  | 46        | 0.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 2343      | 24.83%  |
| 16.01-24.0      | 2203      | 23.35%  |
| 8.01-16.0       | 1571      | 16.65%  |
| 3.01-4.0        | 1388      | 14.71%  |
| 32.01-64.0      | 1103      | 11.69%  |
| 64.01-256.0     | 365       | 3.87%   |
| 24.01-32.0      | 187       | 1.98%   |
| 1.01-2.0        | 164       | 1.74%   |
| 2.01-3.0        | 68        | 0.72%   |
| More than 256.0 | 34        | 0.36%   |
| 0.51-1.0        | 8         | 0.08%   |
| 0.01-0.5        | 1         | 0.01%   |
| Unknown         | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 3065      | 30.97%  |
| 1.01-2.0    | 2836      | 28.66%  |
| 4.01-8.0    | 1688      | 17.06%  |
| 3.01-4.0    | 1525      | 15.41%  |
| 8.01-16.0   | 489       | 4.94%   |
| 0.51-1.0    | 144       | 1.46%   |
| 16.01-24.0  | 67        | 0.68%   |
| 0.01-0.5    | 40        | 0.4%    |
| 24.01-32.0  | 22        | 0.22%   |
| 32.01-64.0  | 14        | 0.14%   |
| 64.01-256.0 | 5         | 0.05%   |
| Unknown     | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 5975      | 62.76%  |
| 2      | 2257      | 23.71%  |
| 3      | 635       | 6.67%   |
| 4      | 268       | 2.81%   |
| 5      | 125       | 1.31%   |
| 0      | 100       | 1.05%   |
| 6      | 62        | 0.65%   |
| 7      | 39        | 0.41%   |
| 8      | 17        | 0.18%   |
| 9      | 15        | 0.16%   |
| 11     | 9         | 0.09%   |
| 10     | 5         | 0.05%   |
| 13     | 4         | 0.04%   |
| 12     | 3         | 0.03%   |
| 25     | 2         | 0.02%   |
| 38     | 1         | 0.01%   |
| 26     | 1         | 0.01%   |
| 20     | 1         | 0.01%   |
| 17     | 1         | 0.01%   |
| 14     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 6393      | 67.79%  |
| Yes       | 3037      | 32.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7692      | 81.77%  |
| No        | 1715      | 18.23%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7272      | 77.23%  |
| No        | 2144      | 22.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5979      | 63.26%  |
| No        | 3472      | 36.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1779      | 18.89%  |
| Germany      | 1018      | 10.81%  |
| France       | 626       | 6.65%   |
| Brazil       | 498       | 5.29%   |
| Italy        | 430       | 4.57%   |
| UK           | 409       | 4.34%   |
| Russia       | 363       | 3.85%   |
| Canada       | 278       | 2.95%   |
| India        | 275       | 2.92%   |
| Spain        | 255       | 2.71%   |
| Poland       | 222       | 2.36%   |
| Netherlands  | 217       | 2.3%    |
| Switzerland  | 204       | 2.17%   |
| Australia    | 131       | 1.39%   |
| Sweden       | 127       | 1.35%   |
| Mexico       | 120       | 1.27%   |
| Turkey       | 103       | 1.09%   |
| Austria      | 102       | 1.08%   |
| Czechia      | 101       | 1.07%   |
| Belgium      | 97        | 1.03%   |
| Argentina    | 96        | 1.02%   |
| Hungary      | 91        | 0.97%   |
| Greece       | 71        | 0.75%   |
| Romania      | 70        | 0.74%   |
| Finland      | 70        | 0.74%   |
| Portugal     | 68        | 0.72%   |
| China        | 67        | 0.71%   |
| Japan        | 64        | 0.68%   |
| South Africa | 57        | 0.61%   |
| Indonesia    | 57        | 0.61%   |
| Denmark      | 52        | 0.55%   |
| Colombia     | 50        | 0.53%   |
| Bulgaria     | 48        | 0.51%   |
| Norway       | 44        | 0.47%   |
| South Korea  | 43        | 0.46%   |
| Serbia       | 41        | 0.44%   |
| Chile        | 39        | 0.41%   |
| New Zealand  | 37        | 0.39%   |
| Iran         | 36        | 0.38%   |
| Egypt        | 35        | 0.37%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Zurich            | 101       | 1.04%   |
| Berlin            | 98        | 1.01%   |
| Moscow            | 95        | 0.98%   |
| Paris             | 93        | 0.96%   |
| Milan             | 74        | 0.76%   |
| Madrid            | 63        | 0.65%   |
| Vienna            | 57        | 0.59%   |
| St Petersburg     | 56        | 0.58%   |
| Sao Paulo         | 53        | 0.55%   |
| Warsaw            | 52        | 0.54%   |
| Sydney            | 47        | 0.48%   |
| Rome              | 47        | 0.48%   |
| Budapest          | 47        | 0.48%   |
| Istanbul          | 43        | 0.44%   |
| Rio de Janeiro    | 41        | 0.42%   |
| Prague            | 41        | 0.42%   |
| Munich            | 40        | 0.41%   |
| Hamburg           | 38        | 0.39%   |
| Helsinki          | 37        | 0.38%   |
| New York          | 34        | 0.35%   |
| London            | 34        | 0.35%   |
| Athens            | 34        | 0.35%   |
| Amsterdam         | 34        | 0.35%   |
| Bengaluru         | 33        | 0.34%   |
| Los Angeles       | 32        | 0.33%   |
| Frankfurt am Main | 31        | 0.32%   |
| Barcelona         | 31        | 0.32%   |
| Toronto           | 28        | 0.29%   |
| Stockholm         | 27        | 0.28%   |
| Belgrade          | 27        | 0.28%   |
| Seattle           | 26        | 0.27%   |
| Dallas            | 26        | 0.27%   |
| Singapore         | 25        | 0.26%   |
| Nairobi           | 25        | 0.26%   |
| Bogotá           | 25        | 0.26%   |
| Tehran            | 24        | 0.25%   |
| Sofia             | 24        | 0.25%   |
| San Jose          | 24        | 0.25%   |
| Mexico City       | 24        | 0.25%   |
| Cheboksary        | 24        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 2176      | 2915   | 16.6%   |
| WDC                         | 1763      | 2567   | 13.45%  |
| Seagate                     | 1682      | 2456   | 12.83%  |
| Toshiba                     | 750       | 894    | 5.72%   |
| SanDisk                     | 737       | 931    | 5.62%   |
| Kingston                    | 707       | 826    | 5.39%   |
| Unknown                     | 518       | 658    | 3.95%   |
| Crucial                     | 471       | 624    | 3.59%   |
| SK hynix                    | 426       | 469    | 3.25%   |
| Intel                       | 370       | 475    | 2.82%   |
| Hitachi                     | 342       | 415    | 2.61%   |
| Micron Technology           | 311       | 351    | 2.37%   |
| HGST                        | 219       | 267    | 1.67%   |
| KIOXIA                      | 187       | 215    | 1.43%   |
| A-DATA Technology           | 184       | 213    | 1.4%    |
| Apple                       | 144       | 171    | 1.1%    |
| China                       | 120       | 139    | 0.92%   |
| Phison                      | 100       | 120    | 0.76%   |
| Unknown                     | 92        | 96     | 0.7%    |
| Intenso                     | 83        | 100    | 0.63%   |
| Silicon Motion              | 81        | 97     | 0.62%   |
| Phison Electronics          | 77        | 99     | 0.59%   |
| SPCC                        | 70        | 99     | 0.53%   |
| Micron/Crucial Technology   | 65        | 81     | 0.5%    |
| PNY                         | 64        | 75     | 0.49%   |
| Kingston Technology Company | 62        | 72     | 0.47%   |
| LITEON                      | 53        | 56     | 0.4%    |
| Transcend                   | 38        | 40     | 0.29%   |
| Netac                       | 38        | 42     | 0.29%   |
| Patriot                     | 36        | 43     | 0.27%   |
| Hewlett-Packard             | 36        | 100    | 0.27%   |
| Gigabyte Technology         | 35        | 43     | 0.27%   |
| OCZ                         | 34        | 50     | 0.26%   |
| Lexar                       | 33        | 33     | 0.25%   |
| ADATA Technology            | 31        | 40     | 0.24%   |
| Team                        | 30        | 41     | 0.23%   |
| Fujitsu                     | 29        | 36     | 0.22%   |
| Corsair                     | 29        | 32     | 0.22%   |
| Maxtor                      | 27        | 36     | 0.21%   |
| JMicron Technology          | 27        | 29     | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 164       | 1.14%   |
| Kingston SA400S37240G 240GB SSD                     | 136       | 0.95%   |
| Seagate ST1000LM035-1RK172 1TB                      | 95        | 0.66%   |
| Unknown                                             | 92        | 0.64%   |
| Samsung SSD 860 EVO 500GB                           | 91        | 0.63%   |
| Samsung SSD 850 EVO 500GB                           | 89        | 0.62%   |
| Seagate ST500DM002-1BD142 500GB                     | 88        | 0.61%   |
| Seagate ST1000DM010-2EP102 1TB                      | 85        | 0.59%   |
| Kingston SA400S37480G 480GB SSD                     | 82        | 0.57%   |
| Unknown MMC Card  64GB                              | 81        | 0.56%   |
| Samsung SSD 850 EVO 250GB                           | 79        | 0.55%   |
| Unknown MMC Card  32GB                              | 78        | 0.54%   |
| Seagate ST2000DM008-2FR102 2TB                      | 78        | 0.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 76        | 0.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 75        | 0.52%   |
| Crucial CT500MX500SSD1 500GB                        | 74        | 0.51%   |
| Toshiba MQ01ABD100 1TB                              | 72        | 0.5%    |
| Samsung SSD 980 PRO 1TB                             | 70        | 0.49%   |
| Crucial CT1000MX500SSD1 1TB                         | 63        | 0.44%   |
| Toshiba MQ04ABF100 1TB                              | 62        | 0.43%   |
| Crucial CT240BX500SSD1 240GB                        | 59        | 0.41%   |
| Samsung SSD 980 1TB                                 | 57        | 0.4%    |
| Unknown SD/MMC/MS PRO 64GB                          | 56        | 0.39%   |
| Kingston SA400S37120G 120GB SSD                     | 54        | 0.38%   |
| SanDisk NVMe SSD Drive 1TB                          | 53        | 0.37%   |
| Samsung NVMe SSD Drive 512GB                        | 50        | 0.35%   |
| Toshiba MQ01ABF050 500GB                            | 47        | 0.33%   |
| Seagate ST500LT012-1DG142 500GB                     | 47        | 0.33%   |
| HGST HTS721010A9E630 1TB                            | 47        | 0.33%   |
| Unknown MMC Card  128GB                             | 46        | 0.32%   |
| Toshiba DT01ACA100 1TB                              | 46        | 0.32%   |
| Seagate ST1000DM003-1CH162 1TB                      | 46        | 0.32%   |
| Seagate ST4000DM004-2CV104 4TB                      | 45        | 0.31%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 256GB    | 45        | 0.31%   |
| Samsung NVMe SSD Drive 1TB                          | 45        | 0.31%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 44        | 0.31%   |
| Samsung SSD 970 EVO Plus 1TB                        | 43        | 0.3%    |
| Toshiba DT01ACA050 500GB                            | 41        | 0.29%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 40        | 0.28%   |
| Seagate ST9500325AS 500GB                           | 40        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1629      | 2370   | 36.36%  |
| WDC                 | 1338      | 2003   | 29.87%  |
| Toshiba             | 536       | 635    | 11.96%  |
| Hitachi             | 340       | 413    | 7.59%   |
| HGST                | 219       | 263    | 4.89%   |
| Samsung Electronics | 179       | 246    | 4%      |
| Unknown             | 61        | 76     | 1.36%   |
| Apple               | 45        | 50     | 1%      |
| Fujitsu             | 29        | 36     | 0.65%   |
| Maxtor              | 21        | 28     | 0.47%   |
| Intenso             | 17        | 18     | 0.38%   |
| ASMT                | 9         | 13     | 0.2%    |
| Hewlett-Packard     | 7         | 39     | 0.16%   |
| USB3.0              | 6         | 7      | 0.13%   |
| ASMedia             | 6         | 6      | 0.13%   |
| WD MediaMax         | 4         | 4      | 0.09%   |
| SSK                 | 4         | 5      | 0.09%   |
| External            | 4         | 6      | 0.09%   |
| Inateck             | 3         | 3      | 0.07%   |
| HPE                 | 3         | 4      | 0.07%   |
| LaCie               | 2         | 2      | 0.04%   |
| HGST HTS            | 2         | 3      | 0.04%   |
| USB                 | 1         | 1      | 0.02%   |
| StoreJet            | 1         | 1      | 0.02%   |
| SAGE                | 1         | 1      | 0.02%   |
| SABRENT             | 1         | 2      | 0.02%   |
| RSH-339             | 1         | 1      | 0.02%   |
| QUANTUM             | 1         | 1      | 0.02%   |
| PHD 3.0             | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 1      | 0.02%   |
| MARSHAL             | 1         | 1      | 0.02%   |
| Lenovo              | 1         | 2      | 0.02%   |
| JMicron Technology  | 1         | 1      | 0.02%   |
| IBM-ESXS            | 1         | 1      | 0.02%   |
| ExcelStor           | 1         | 1      | 0.02%   |
| DellEMC             | 1         | 8      | 0.02%   |
| DELLBOSS            | 1         | 1      | 0.02%   |
| DAS                 | 1         | 3      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 868       | 1096   | 21.46%  |
| Kingston            | 531       | 628    | 13.13%  |
| Crucial             | 422       | 559    | 10.44%  |
| SanDisk             | 354       | 456    | 8.75%   |
| WDC                 | 237       | 290    | 5.86%   |
| A-DATA Technology   | 122       | 141    | 3.02%   |
| China               | 117       | 132    | 2.89%   |
| Intel               | 108       | 120    | 2.67%   |
| Micron Technology   | 85        | 103    | 2.1%    |
| Toshiba             | 78        | 86     | 1.93%   |
| SK hynix            | 78        | 96     | 1.93%   |
| SPCC                | 64        | 92     | 1.58%   |
| PNY                 | 57        | 67     | 1.41%   |
| Apple               | 53        | 55     | 1.31%   |
| LITEON              | 49        | 52     | 1.21%   |
| Intenso             | 46        | 56     | 1.14%   |
| Transcend           | 36        | 38     | 0.89%   |
| Patriot             | 35        | 42     | 0.87%   |
| Netac               | 35        | 38     | 0.87%   |
| Unknown             | 33        | 34     | 0.82%   |
| OCZ                 | 32        | 36     | 0.79%   |
| Team                | 27        | 36     | 0.67%   |
| Gigabyte Technology | 26        | 33     | 0.64%   |
| KingSpec            | 25        | 25     | 0.62%   |
| GOODRAM             | 25        | 32     | 0.62%   |
| Lexar               | 24        | 24     | 0.59%   |
| LITEONIT            | 22        | 28     | 0.54%   |
| Hewlett-Packard     | 22        | 31     | 0.54%   |
| Apacer              | 21        | 21     | 0.52%   |
| Corsair             | 20        | 22     | 0.49%   |
| JMicron Technology  | 19        | 19     | 0.47%   |
| SABRENT             | 16        | 19     | 0.4%    |
| ASMT                | 14        | 25     | 0.35%   |
| Seagate             | 13        | 17     | 0.32%   |
| Emtec               | 13        | 13     | 0.32%   |
| Teclast             | 11        | 12     | 0.27%   |
| Plextor             | 9         | 9      | 0.22%   |
| FORESEE             | 9         | 9      | 0.22%   |
| Verbatim            | 8         | 9      | 0.2%    |
| Fanxiang            | 8         | 10     | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 3836      | 4894   | 32.02%  |
| HDD     | 3808      | 6257   | 31.79%  |
| SSD     | 3619      | 4925   | 30.21%  |
| MMC     | 483       | 598    | 4.03%   |
| Unknown | 234       | 342    | 1.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6062      | 10735  | 55.53%  |
| NVMe | 3832      | 4880   | 35.1%   |
| SAS  | 540       | 803    | 4.95%   |
| MMC  | 483       | 598    | 4.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4241      | 5950   | 54.58%  |
| 0.51-1.0   | 2335      | 3195   | 30.05%  |
| 1.01-2.0   | 621       | 948    | 7.99%   |
| 3.01-4.0   | 246       | 401    | 3.17%   |
| 4.01-10.0  | 149       | 372    | 1.92%   |
| 2.01-3.0   | 118       | 173    | 1.52%   |
| 10.01-20.0 | 60        | 143    | 0.77%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2722      | 28.32%  |
| 251-500        | 2425      | 25.23%  |
| 501-1000       | 1606      | 16.71%  |
| 1001-2000      | 670       | 6.97%   |
| 51-100         | 578       | 6.01%   |
| 1-20           | 461       | 4.8%    |
| More than 3000 | 429       | 4.46%   |
| 21-50          | 338       | 3.52%   |
| 2001-3000      | 247       | 2.57%   |
| Unknown        | 135       | 1.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3514      | 35.7%   |
| 21-50          | 2001      | 20.33%  |
| 51-100         | 1308      | 13.29%  |
| 101-250        | 1271      | 12.91%  |
| 251-500        | 695       | 7.06%   |
| 501-1000       | 445       | 4.52%   |
| 1001-2000      | 218       | 2.21%   |
| More than 3000 | 181       | 1.84%   |
| Unknown        | 135       | 1.37%   |
| 2001-3000      | 74        | 0.75%   |
| 0              | 2         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 8         | 8      | 1.42%   |
| Seagate ST1000LM035-1RK172 1TB        | 8         | 8      | 1.42%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 8         | 11     | 1.42%   |
| WDC WD40EFRX-68WT0N0 4TB              | 7         | 8      | 1.24%   |
| Toshiba MQ01ABD100 1TB                | 6         | 6      | 1.07%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 6         | 6      | 1.07%   |
| Seagate ST9500325AS 500GB             | 6         | 6      | 1.07%   |
| Seagate ST500LT012-9WS142 500GB       | 5         | 5      | 0.89%   |
| Seagate ST1000LM014-1EJ164 1TB        | 5         | 6      | 0.89%   |
| SanDisk SSD PLUS 480GB                | 5         | 5      | 0.89%   |
| WDC WD10EARS-00Y5B1 1TB               | 4         | 5      | 0.71%   |
| Toshiba MQ04ABF100 1TB                | 4         | 4      | 0.71%   |
| Seagate ST500LT012-1DG142 500GB       | 4         | 4      | 0.71%   |
| Seagate ST3500418AS 500GB             | 4         | 5      | 0.71%   |
| Seagate ST1000LX015-1U7172 1TB        | 4         | 4      | 0.71%   |
| Kingston SV300S37A120G 120GB SSD      | 4         | 5      | 0.71%   |
| Hitachi HTS545050A7E380 500GB         | 4         | 4      | 0.71%   |
| Hitachi HTS543232A7A384 320GB         | 4         | 4      | 0.71%   |
| HGST HTS725050A7E630 500GB            | 4         | 4      | 0.71%   |
| HGST HTS721010A9E630 1TB              | 4         | 5      | 0.71%   |
| HGST HTS541010A9E680 1TB              | 4         | 4      | 0.71%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 3         | 3      | 0.53%   |
| WDC WD10JPVX-60JC3T0 1TB              | 3         | 3      | 0.53%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 3         | 3      | 0.53%   |
| Seagate ST9320325AS 320GB             | 3         | 3      | 0.53%   |
| Seagate ST3250310AS 250GB             | 3         | 3      | 0.53%   |
| Seagate ST2000DM001-1CH164 2TB        | 3         | 3      | 0.53%   |
| Seagate ST1000LM014-SSHD-8GB          | 3         | 3      | 0.53%   |
| SanDisk SSD PLUS 1000GB               | 3         | 4      | 0.53%   |
| Samsung Electronics SSD 870 EVO 1TB   | 3         | 3      | 0.53%   |
| Micron Technology 1100 SATA 256GB SSD | 3         | 3      | 0.53%   |
| Kingston SA400S37240G 240GB SSD       | 3         | 3      | 0.53%   |
| HGST HTS545050A7E680 500GB            | 3         | 3      | 0.53%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 2         | 2      | 0.36%   |
| WDC WD5000AAKX-08ERMA0 500GB          | 2         | 2      | 0.36%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 2         | 2      | 0.36%   |
| WDC WD4003FZEX-00Z4SA0 4TB            | 2         | 4      | 0.36%   |
| WDC WD30EZRX-00MMMB0 3TB              | 2         | 6      | 0.36%   |
| WDC WD2003FYYS-02W0B1 2TB             | 2         | 2      | 0.36%   |
| WDC WD10JPVX-22JC3T0 1TB              | 2         | 2      | 0.36%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 132       | 152    | 23.83%  |
| WDC                 | 122       | 143    | 22.02%  |
| Samsung Electronics | 47        | 52     | 8.48%   |
| Toshiba             | 38        | 44     | 6.86%   |
| Hitachi             | 37        | 38     | 6.68%   |
| SK hynix            | 26        | 26     | 4.69%   |
| HGST                | 22        | 24     | 3.97%   |
| Intel               | 17        | 17     | 3.07%   |
| SanDisk             | 15        | 17     | 2.71%   |
| Kingston            | 13        | 15     | 2.35%   |
| Micron Technology   | 12        | 18     | 2.17%   |
| Crucial             | 10        | 11     | 1.81%   |
| A-DATA Technology   | 10        | 10     | 1.81%   |
| China               | 6         | 6      | 1.08%   |
| Maxtor              | 5         | 6      | 0.9%    |
| LITEON              | 5         | 5      | 0.9%    |
| Apple               | 4         | 6      | 0.72%   |
| LITEONIT            | 3         | 3      | 0.54%   |
| Intenso             | 3         | 3      | 0.54%   |
| Netac               | 2         | 2      | 0.36%   |
| LDLC                | 2         | 2      | 0.36%   |
| KingSpec            | 2         | 2      | 0.36%   |
| YS                  | 1         | 1      | 0.18%   |
| XPG                 | 1         | 1      | 0.18%   |
| WD MediaMax         | 1         | 1      | 0.18%   |
| WALRAM              | 1         | 1      | 0.18%   |
| VISIPRO             | 1         | 1      | 0.18%   |
| tecmiyo             | 1         | 1      | 0.18%   |
| SSSTC               | 1         | 1      | 0.18%   |
| Silicon Motion      | 1         | 1      | 0.18%   |
| ShiJi               | 1         | 1      | 0.18%   |
| RX7                 | 1         | 1      | 0.18%   |
| PNY                 | 1         | 1      | 0.18%   |
| Patriot             | 1         | 1      | 0.18%   |
| OCZ                 | 1         | 1      | 0.18%   |
| Mushkin             | 1         | 1      | 0.18%   |
| HS-SSD-E100         | 1         | 1      | 0.18%   |
| Gigabyte Technology | 1         | 1      | 0.18%   |
| Fujitsu             | 1         | 1      | 0.18%   |
| Corsair             | 1         | 1      | 0.18%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 132       | 152    | 35.39%  |
| WDC                 | 113       | 134    | 30.29%  |
| Hitachi             | 37        | 38     | 9.92%   |
| Toshiba             | 36        | 42     | 9.65%   |
| HGST                | 22        | 24     | 5.9%    |
| Samsung Electronics | 21        | 23     | 5.63%   |
| Maxtor              | 5         | 6      | 1.34%   |
| Apple               | 4         | 6      | 1.07%   |
| WD MediaMax         | 1         | 1      | 0.27%   |
| Fujitsu             | 1         | 1      | 0.27%   |
| ASMedia             | 1         | 1      | 0.27%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 358       | 428    | 66.42%  |
| SSD  | 136       | 148    | 25.23%  |
| NVMe | 45        | 47     | 8.35%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 500GB                               | 2         | 2      | 16.67%  |
| WDC WD7500BPVT-22HXZT1 752GB                                    | 1         | 1      | 8.33%   |
| WDC WD5000BEVT-22A0RT0 500GB                                    | 1         | 1      | 8.33%   |
| WDC WD3200AAJS-22VWA0 320GB                                     | 1         | 1      | 8.33%   |
| Seagate ST3300657SS 304GB                                       | 1         | 2      | 8.33%   |
| Samsung Electronics SSD 960 EVO 250GB                           | 1         | 1      | 8.33%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 8.33%   |
| Intel SSDPEKKW256G7 256GB                                       | 1         | 1      | 8.33%   |
| HGST HTS721010A9E630 1TB                                        | 1         | 1      | 8.33%   |
| Hewlett-Packard EF0450FARMV 450GB                               | 1         | 4      | 8.33%   |
| Crucial M4-CT256M4SSD3 256GB                                    | 1         | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 33.33%  |
| WDC                 | 3         | 3      | 25%     |
| Seagate             | 1         | 2      | 8.33%   |
| Intel               | 1         | 1      | 8.33%   |
| HGST                | 1         | 1      | 8.33%   |
| Hewlett-Packard     | 1         | 4      | 8.33%   |
| Crucial             | 1         | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 5825      | 10867  | 58.73%  |
| Works    | 3566      | 5509   | 35.95%  |
| Malfunc  | 514       | 623    | 5.18%   |
| Failed   | 12        | 16     | 0.12%   |
| Fixed    | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 6089      | 49.83%  |
| AMD                            | 1636      | 13.39%  |
| Samsung Electronics            | 1293      | 10.58%  |
| SanDisk                        | 601       | 4.92%   |
| SK hynix                       | 340       | 2.78%   |
| Kingston Technology Company    | 239       | 1.96%   |
| Micron Technology              | 228       | 1.87%   |
| Phison Electronics             | 194       | 1.59%   |
| ASMedia Technology             | 194       | 1.59%   |
| KIOXIA                         | 180       | 1.47%   |
| Toshiba America Info Systems   | 164       | 1.34%   |
| Nvidia                         | 119       | 0.97%   |
| Micron/Crucial Technology      | 119       | 0.97%   |
| Marvell Technology Group       | 118       | 0.97%   |
| Silicon Motion                 | 107       | 0.88%   |
| ADATA Technology               | 92        | 0.75%   |
| JMicron Technology             | 91        | 0.74%   |
| LSI Logic / Symbios Logic      | 50        | 0.41%   |
| Solid State Storage Technology | 48        | 0.39%   |
| Apple                          | 46        | 0.38%   |
| Union Memory (Shenzhen)        | 34        | 0.28%   |
| Broadcom / LSI                 | 33        | 0.27%   |
| Realtek Semiconductor          | 28        | 0.23%   |
| Seagate Technology             | 18        | 0.15%   |
| Shenzhen Longsys Electronics   | 17        | 0.14%   |
| MAXIO Technology (Hangzhou)    | 17        | 0.14%   |
| Yangtze Memory Technologies    | 16        | 0.13%   |
| Silicon Image                  | 16        | 0.13%   |
| VIA Technologies               | 14        | 0.11%   |
| Hewlett-Packard                | 13        | 0.11%   |
| Lite-On Technology             | 12        | 0.1%    |
| Adaptec                        | 11        | 0.09%   |
| Lenovo                         | 6         | 0.05%   |
| INNOGRIT                       | 5         | 0.04%   |
| Biwin Storage Technology       | 4         | 0.03%   |
| Unknown                        | 4         | 0.03%   |
| Transcend                      | 2         | 0.02%   |
| Solidigm                       | 2         | 0.02%   |
| OCZ Technology Group           | 2         | 0.02%   |
| Integrated Technology Express  | 2         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1115      | 8.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 493       | 3.6%    |
| Intel Volume Management Device NVMe RAID Controller                            | 476       | 3.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 456       | 3.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 437       | 3.19%   |
| Samsung NVMe SSD Controller 980                                                | 338       | 2.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 336       | 2.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 324       | 2.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 292       | 2.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 233       | 1.7%    |
| Micron NVMe Storage Controller                                                 | 222       | 1.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 218       | 1.59%   |
| Intel SATA Controller [RAID mode]                                              | 192       | 1.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 190       | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 190       | 1.39%   |
| AMD 400 Series Chipset SATA Controller                                         | 188       | 1.37%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 183       | 1.34%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 179       | 1.31%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 170       | 1.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 158       | 1.15%   |
| Intel Comet Lake SATA AHCI Controller                                          | 156       | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 156       | 1.14%   |
| AMD 500 Series Chipset SATA Controller                                         | 155       | 1.13%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 154       | 1.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 152       | 1.11%   |
| Intel Tiger Lake-LP SATA Controller                                            | 150       | 1.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 148       | 1.08%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 143       | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 136       | 0.99%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 128       | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 127       | 0.93%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 125       | 0.91%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 125       | 0.91%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 114       | 0.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 108       | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 97        | 0.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 92        | 0.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 91        | 0.66%   |
| Intel SSD 660P Series                                                          | 89        | 0.65%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 89        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 6453      | 52.41%  |
| NVMe | 3828      | 31.09%  |
| RAID | 1135      | 9.22%   |
| IDE  | 822       | 6.68%   |
| SAS  | 56        | 0.45%   |
| SCSI | 18        | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 7181      | 76.46%  |
| AMD          | 2115      | 22.52%  |
| ARM          | 94        | 1%      |
| Phytium      | 1         | 0.01%   |
| CentaurHauls | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 189       | 2.01%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 177       | 1.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 97        | 1.03%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 88        | 0.94%   |
| ARM Processor                                 | 88        | 0.94%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 84        | 0.89%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 78        | 0.83%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 74        | 0.79%   |
| Intel 12th Gen Core i7-12700H                 | 73        | 0.78%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 72        | 0.77%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 71        | 0.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 70        | 0.74%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 68        | 0.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 64        | 0.68%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 62        | 0.66%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 61        | 0.65%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 60        | 0.64%   |
| AMD Ryzen 5 3600 6-Core Processor             | 60        | 0.64%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 59        | 0.63%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 57        | 0.61%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 56        | 0.6%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 55        | 0.58%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 54        | 0.57%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 51        | 0.54%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 50        | 0.53%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 49        | 0.52%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 48        | 0.51%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 47        | 0.5%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 46        | 0.49%   |
| Intel 12th Gen Core i7-1260P                  | 45        | 0.48%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 44        | 0.47%   |
| Intel 12th Gen Core i7-1255U                  | 44        | 0.47%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 42        | 0.45%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 42        | 0.45%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 40        | 0.43%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 40        | 0.43%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 40        | 0.43%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 39        | 0.41%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 38        | 0.4%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 37        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 2053      | 21.85%  |
| Intel Core i7           | 1677      | 17.85%  |
| Other                   | 1306      | 13.9%   |
| Intel Core i3           | 677       | 7.2%    |
| AMD Ryzen 5             | 557       | 5.93%   |
| Intel Celeron           | 471       | 5.01%   |
| AMD Ryzen 7             | 456       | 4.85%   |
| Intel Xeon              | 290       | 3.09%   |
| Intel Core 2 Duo        | 222       | 2.36%   |
| Intel Pentium           | 199       | 2.12%   |
| AMD Ryzen 9             | 167       | 1.78%   |
| AMD FX                  | 116       | 1.23%   |
| AMD Ryzen 3             | 105       | 1.12%   |
| Intel Atom              | 90        | 0.96%   |
| Intel Core 2 Quad       | 77        | 0.82%   |
| AMD A6                  | 71        | 0.76%   |
| AMD A8                  | 67        | 0.71%   |
| AMD A10                 | 66        | 0.7%    |
| Intel Pentium Dual-Core | 61        | 0.65%   |
| Intel Core i9           | 53        | 0.56%   |
| AMD A4                  | 48        | 0.51%   |
| AMD Ryzen 7 PRO         | 40        | 0.43%   |
| AMD Phenom II X4        | 32        | 0.34%   |
| AMD Athlon II X2        | 29        | 0.31%   |
| AMD Ryzen Threadripper  | 28        | 0.3%    |
| AMD Athlon              | 28        | 0.3%    |
| AMD E2                  | 27        | 0.29%   |
| Intel Pentium Dual      | 25        | 0.27%   |
| Intel Core 2            | 24        | 0.26%   |
| Intel Pentium Silver    | 23        | 0.24%   |
| AMD Ryzen 5 PRO         | 22        | 0.23%   |
| AMD Athlon 64 X2        | 20        | 0.21%   |
| AMD E1                  | 16        | 0.17%   |
| AMD E                   | 16        | 0.17%   |
| AMD Athlon II X4        | 16        | 0.17%   |
| AMD Phenom II X6        | 15        | 0.16%   |
| AMD Sempron             | 11        | 0.12%   |
| AMD EPYC                | 10        | 0.11%   |
| Intel Pentium Gold      | 9         | 0.1%    |
| Intel Genuine           | 9         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 3633      | 38.65%  |
| 2       | 3130      | 33.3%   |
| 6       | 952       | 10.13%  |
| 8       | 852       | 9.06%   |
| 12      | 237       | 2.52%   |
| 14      | 140       | 1.49%   |
| 10      | 116       | 1.23%   |
| 16      | 110       | 1.17%   |
| 1       | 90        | 0.96%   |
| 3       | 49        | 0.52%   |
| Unknown | 21        | 0.22%   |
| 24      | 18        | 0.19%   |
| 32      | 13        | 0.14%   |
| 20      | 9         | 0.1%    |
| 28      | 6         | 0.06%   |
| 64      | 5         | 0.05%   |
| 48      | 4         | 0.04%   |
| 40      | 3         | 0.03%   |
| 18      | 3         | 0.03%   |
| 128     | 2         | 0.02%   |
| 104     | 2         | 0.02%   |
| 5       | 2         | 0.02%   |
| 80      | 1         | 0.01%   |
| 52      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 9246      | 98.45%  |
| 2       | 122       | 1.3%    |
| Unknown | 21        | 0.22%   |
| 4       | 3         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 6620      | 70.43%  |
| 1       | 2756      | 29.32%  |
| Unknown | 21        | 0.22%   |
| 6       | 1         | 0.01%   |
| 4       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 9324      | 99.27%  |
| Unknown        | 66        | 0.7%    |
| 64-bit         | 3         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5214      | 54.38%  |
| 0x806c1    | 361       | 3.77%   |
| 0x306a9    | 229       | 2.39%   |
| 0x806ec    | 212       | 2.21%   |
| 0x306c3    | 196       | 2.04%   |
| 0x806ea    | 169       | 1.76%   |
| 0x206a7    | 169       | 1.76%   |
| 0x906a3    | 153       | 1.6%    |
| 0x906ea    | 147       | 1.53%   |
| 0x0a50000c | 133       | 1.39%   |
| 0x506e3    | 120       | 1.25%   |
| 0x906e9    | 95        | 0.99%   |
| 0x08608103 | 94        | 0.98%   |
| 0x40651    | 90        | 0.94%   |
| 0x406e3    | 87        | 0.91%   |
| 0x806e9    | 84        | 0.88%   |
| 0x706e5    | 83        | 0.87%   |
| 0x306d4    | 83        | 0.87%   |
| 0xa0652    | 81        | 0.84%   |
| 0x706a8    | 79        | 0.82%   |
| 0x806d1    | 71        | 0.74%   |
| 0x08108109 | 69        | 0.72%   |
| 0x08600106 | 60        | 0.63%   |
| 0x906a4    | 57        | 0.59%   |
| 0x1067a    | 57        | 0.59%   |
| 0x08701021 | 57        | 0.59%   |
| 0x20655    | 49        | 0.51%   |
| 0x906ed    | 47        | 0.49%   |
| 0x90672    | 40        | 0.42%   |
| 0x806eb    | 38        | 0.4%    |
| 0x0a201016 | 36        | 0.38%   |
| 0x506c9    | 33        | 0.34%   |
| 0xa0671    | 32        | 0.33%   |
| 0xa0653    | 32        | 0.33%   |
| 0x306f2    | 32        | 0.33%   |
| 0x0800820d | 30        | 0.31%   |
| 0x06000852 | 30        | 0.31%   |
| 0x30678    | 29        | 0.3%    |
| 0x0a50000d | 29        | 0.3%    |
| 0x010000c8 | 28        | 0.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1482      | 15.76%  |
| Haswell          | 838       | 8.91%   |
| IvyBridge        | 623       | 6.63%   |
| Unknown          | 612       | 6.51%   |
| TigerLake        | 560       | 5.96%   |
| SandyBridge      | 553       | 5.88%   |
| Skylake          | 510       | 5.42%   |
| Zen 3            | 440       | 4.68%   |
| Zen 2            | 349       | 3.71%   |
| Penryn           | 309       | 3.29%   |
| Westmere         | 282       | 3%      |
| Alderlake Hybrid | 272       | 2.89%   |
| Zen+             | 265       | 2.82%   |
| Icelake          | 257       | 2.73%   |
| CometLake        | 238       | 2.53%   |
| Silvermont       | 220       | 2.34%   |
| Broadwell        | 220       | 2.34%   |
| Goldmont plus    | 197       | 2.1%    |
| Piledriver       | 174       | 1.85%   |
| K10              | 149       | 1.58%   |
| Core             | 143       | 1.52%   |
| Zen              | 124       | 1.32%   |
| Excavator        | 110       | 1.17%   |
| Goldmont         | 90        | 0.96%   |
| Nehalem          | 84        | 0.89%   |
| Steamroller      | 49        | 0.52%   |
| Puma             | 49        | 0.52%   |
| K8 Hammer        | 44        | 0.47%   |
| Bobcat           | 40        | 0.43%   |
| Bulldozer        | 25        | 0.27%   |
| K10 Llano        | 24        | 0.26%   |
| Jaguar           | 22        | 0.23%   |
| Tremont          | 20        | 0.21%   |
| NetBurst         | 10        | 0.11%   |
| K8 & K10 hybrid  | 10        | 0.11%   |
| Bonnell          | 8         | 0.09%   |
| Sapphire Rapids  | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 5656      | 50.79%  |
| Nvidia                                       | 3074      | 27.6%   |
| AMD                                          | 2281      | 20.48%  |
| Matrox Electronics Systems                   | 70        | 0.63%   |
| ASPEED Technology                            | 47        | 0.42%   |
| ATI Technologies                             | 5         | 0.04%   |
| Zhaoxin                                      | 1         | 0.01%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| VIA Technologies                             | 1         | 0.01%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 513       | 4.53%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 409       | 3.61%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 318       | 2.81%   |
| Intel UHD Graphics 620                                                                   | 260       | 2.3%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 219       | 1.93%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 216       | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 213       | 1.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 211       | 1.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 203       | 1.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 195       | 1.72%   |
| Intel HD Graphics 620                                                                    | 191       | 1.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 190       | 1.68%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 177       | 1.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 176       | 1.55%   |
| AMD Lucienne                                                                             | 165       | 1.46%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 158       | 1.4%    |
| Intel HD Graphics 530                                                                    | 153       | 1.35%   |
| AMD Renoir                                                                               | 153       | 1.35%   |
| Intel HD Graphics 5500                                                                   | 148       | 1.31%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 143       | 1.26%   |
| Intel Core Processor Integrated Graphics Controller                                      | 134       | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 124       | 1.1%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 116       | 1.02%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 113       | 1%      |
| Intel HD Graphics 630                                                                    | 112       | 0.99%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 112       | 0.99%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 107       | 0.95%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 105       | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 96        | 0.85%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 93        | 0.82%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 92        | 0.81%   |
| Intel HD Graphics 500                                                                    | 79        | 0.7%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 76        | 0.67%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 73        | 0.64%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 70        | 0.62%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 67        | 0.59%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 62        | 0.55%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 61        | 0.54%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 60        | 0.53%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 59        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 4048      | 42.98%  |
| 1 x AMD                  | 1787      | 18.97%  |
| 1 x Nvidia               | 1569      | 16.66%  |
| Intel + Nvidia           | 1270      | 13.48%  |
| Intel + AMD              | 211       | 2.24%   |
| AMD + Nvidia             | 180       | 1.91%   |
| Other                    | 104       | 1.1%    |
| 2 x AMD                  | 98        | 1.04%   |
| 1 x Matrox               | 57        | 0.61%   |
| 1 x ASPEED               | 32        | 0.34%   |
| 2 x Nvidia               | 25        | 0.27%   |
| Nvidia + ASPEED          | 12        | 0.13%   |
| Nvidia + Matrox          | 9         | 0.1%    |
| AMD + Matrox             | 4         | 0.04%   |
| AMD + ASPEED             | 3         | 0.03%   |
| 2 x Intel                | 2         | 0.02%   |
| 3 x AMD                  | 1         | 0.01%   |
| 1 x Zhaoxin              | 1         | 0.01%   |
| 1 x XGI                  | 1         | 0.01%   |
| 1 x VIA                  | 1         | 0.01%   |
| 1 x SiS                  | 1         | 0.01%   |
| Intel + 2 x Nvidia       | 1         | 0.01%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.01%   |
| AMD + 2 x Nvidia         | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 7309      | 77.15%  |
| Proprietary | 1775      | 18.74%  |
| Unknown     | 390       | 4.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7495      | 78.99%  |
| 1.01-2.0   | 526       | 5.54%   |
| 0.01-0.5   | 450       | 4.74%   |
| 0.51-1.0   | 312       | 3.29%   |
| 3.01-4.0   | 290       | 3.06%   |
| 7.01-8.0   | 179       | 1.89%   |
| 5.01-6.0   | 93        | 0.98%   |
| 8.01-16.0  | 83        | 0.87%   |
| 2.01-3.0   | 33        | 0.35%   |
| 16.01-24.0 | 23        | 0.24%   |
| 4.01-5.0   | 5         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1258      | 12.32%  |
| AU Optronics            | 1172      | 11.48%  |
| BOE                     | 1076      | 10.54%  |
| Chimei Innolux          | 865       | 8.47%   |
| LG Display              | 814       | 7.97%   |
| Dell                    | 634       | 6.21%   |
| Goldstar                | 471       | 4.61%   |
| Hewlett-Packard         | 348       | 3.41%   |
| Acer                    | 315       | 3.09%   |
| Sharp                   | 221       | 2.16%   |
| Philips                 | 220       | 2.15%   |
| Apple                   | 220       | 2.15%   |
| BenQ                    | 217       | 2.13%   |
| AOC                     | 211       | 2.07%   |
| Lenovo                  | 185       | 1.81%   |
| Ancor Communications    | 183       | 1.79%   |
| Iiyama                  | 112       | 1.1%    |
| PANDA                   | 111       | 1.09%   |
| Chi Mei Optoelectronics | 109       | 1.07%   |
| ViewSonic               | 96        | 0.94%   |
| ASUSTek Computer        | 87        | 0.85%   |
| Sony                    | 83        | 0.81%   |
| InfoVision              | 78        | 0.76%   |
| CSO                     | 63        | 0.62%   |
| Vizio                   | 47        | 0.46%   |
| Panasonic               | 42        | 0.41%   |
| Fujitsu Siemens         | 38        | 0.37%   |
| MSI                     | 35        | 0.34%   |
| Eizo                    | 32        | 0.31%   |
| LG Electronics          | 31        | 0.3%    |
| NEC Computers           | 30        | 0.29%   |
| Unknown                 | 29        | 0.28%   |
| Sceptre Tech            | 29        | 0.28%   |
| Toshiba                 | 26        | 0.25%   |
| HannStar                | 24        | 0.24%   |
| Medion                  | 22        | 0.22%   |
| RTK                     | 21        | 0.21%   |
| LG Philips              | 21        | 0.21%   |
| Mi                      | 20        | 0.2%    |
| Unknown                 | 20        | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 49        | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 44        | 0.42%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 38        | 0.36%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 37        | 0.35%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 36        | 0.34%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 32        | 0.3%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 32        | 0.3%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 29        | 0.28%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 27        | 0.26%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 26        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 26        | 0.25%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 25        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 24        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 24        | 0.23%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                        | 24        | 0.23%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 23        | 0.22%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 23        | 0.22%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch         | 22        | 0.21%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 21        | 0.2%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 20        | 0.19%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 20        | 0.19%   |
| Unknown                                                                  | 20        | 0.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 19        | 0.18%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 19        | 0.18%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 19        | 0.18%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 19        | 0.18%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 18        | 0.17%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                    | 18        | 0.17%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 17        | 0.16%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 17        | 0.16%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 17        | 0.16%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 17        | 0.16%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                       | 17        | 0.16%   |
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch     | 16        | 0.15%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                  | 16        | 0.15%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 16        | 0.15%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 16        | 0.15%   |
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                    | 16        | 0.15%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 16        | 0.15%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 16        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 4585      | 47.17%  |
| 1366x768 (WXGA)    | 1541      | 15.85%  |
| 3840x2160 (4K)     | 702       | 7.22%   |
| 2560x1440 (QHD)    | 484       | 4.98%   |
| 1600x900 (HD+)     | 389       | 4%      |
| 1920x1200 (WUXGA)  | 273       | 2.81%   |
| 1280x1024 (SXGA)   | 225       | 2.31%   |
| 1680x1050 (WSXGA+) | 219       | 2.25%   |
| 1440x900 (WXGA+)   | 172       | 1.77%   |
| 2560x1600          | 131       | 1.35%   |
| 1280x800 (WXGA)    | 130       | 1.34%   |
| 3440x1440          | 99        | 1.02%   |
| 2560x1080          | 95        | 0.98%   |
| 2880x1800          | 78        | 0.8%    |
| 1360x768           | 70        | 0.72%   |
| Unknown            | 55        | 0.57%   |
| 3840x2400          | 54        | 0.56%   |
| 1920x540           | 45        | 0.46%   |
| 2160x1440          | 41        | 0.42%   |
| 3840x1080          | 38        | 0.39%   |
| 1024x768 (XGA)     | 33        | 0.34%   |
| 1280x720 (HD)      | 23        | 0.24%   |
| 1600x1200          | 18        | 0.19%   |
| 2256x1504          | 15        | 0.15%   |
| 2736x1824          | 12        | 0.12%   |
| 2288x1287          | 12        | 0.12%   |
| 3200x1800 (QHD+)   | 11        | 0.11%   |
| 3840x1600          | 10        | 0.1%    |
| 3000x2000          | 10        | 0.1%    |
| 3200x2000          | 9         | 0.09%   |
| 2520x1680          | 9         | 0.09%   |
| 3072x1920          | 8         | 0.08%   |
| 1920x1280          | 8         | 0.08%   |
| 3456x2160          | 7         | 0.07%   |
| 2160x1350          | 7         | 0.07%   |
| 1280x960           | 7         | 0.07%   |
| 2880x1620          | 6         | 0.06%   |
| 2048x1152          | 6         | 0.06%   |
| 1400x1050          | 6         | 0.06%   |
| 3840x1200          | 5         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2549      | 24.98%  |
| 13      | 1037      | 10.16%  |
| 14      | 847       | 8.3%    |
| 27      | 790       | 7.74%   |
| 24      | 735       | 7.2%    |
| 23      | 626       | 6.13%   |
| 17      | 557       | 5.46%   |
| 21      | 549       | 5.38%   |
| Unknown | 307       | 3.01%   |
| 31      | 257       | 2.52%   |
| 19      | 243       | 2.38%   |
| 34      | 159       | 1.56%   |
| 18      | 157       | 1.54%   |
| 16      | 153       | 1.5%    |
| 20      | 150       | 1.47%   |
| 22      | 138       | 1.35%   |
| 12      | 129       | 1.26%   |
| 11      | 110       | 1.08%   |
| 84      | 86        | 0.84%   |
| 32      | 68        | 0.67%   |
| 72      | 64        | 0.63%   |
| 40      | 58        | 0.57%   |
| 54      | 48        | 0.47%   |
| 25      | 44        | 0.43%   |
| 26      | 32        | 0.31%   |
| 28      | 29        | 0.28%   |
| 10      | 24        | 0.24%   |
| 65      | 19        | 0.19%   |
| 52      | 17        | 0.17%   |
| 46      | 17        | 0.17%   |
| 37      | 17        | 0.17%   |
| 29      | 17        | 0.17%   |
| 48      | 16        | 0.16%   |
| 43      | 16        | 0.16%   |
| 42      | 14        | 0.14%   |
| 49      | 13        | 0.13%   |
| 36      | 13        | 0.13%   |
| 47      | 11        | 0.11%   |
| 35      | 8         | 0.08%   |
| 38      | 7         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 4015      | 39.89%  |
| 501-600        | 2025      | 20.12%  |
| 401-500        | 1105      | 10.98%  |
| 201-300        | 831       | 8.26%   |
| 351-400        | 674       | 6.7%    |
| 601-700        | 390       | 3.87%   |
| Unknown        | 307       | 3.05%   |
| 701-800        | 245       | 2.43%   |
| 1001-1500      | 170       | 1.69%   |
| 1501-2000      | 164       | 1.63%   |
| 801-900        | 94        | 0.93%   |
| 901-1000       | 34        | 0.34%   |
| More than 2000 | 7         | 0.07%   |
| 101-200        | 5         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 7119      | 77.72%  |
| 16/10   | 1127      | 12.3%   |
| Unknown | 227       | 2.48%   |
| 5/4     | 215       | 2.35%   |
| 21/9    | 199       | 2.17%   |
| 3/2     | 133       | 1.45%   |
| 4/3     | 74        | 0.81%   |
| 32/9    | 31        | 0.34%   |
| 6/5     | 12        | 0.13%   |
| 1.00    | 8         | 0.09%   |
| 2.12    | 3         | 0.03%   |
| 2.00    | 2         | 0.02%   |
| 1.96    | 2         | 0.02%   |
| 0.62    | 2         | 0.02%   |
| 0.56    | 2         | 0.02%   |
| 3.73    | 1         | 0.01%   |
| 3.33    | 1         | 0.01%   |
| 3.20    | 1         | 0.01%   |
| 0.89    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2546      | 25.13%  |
| 201-250        | 1611      | 15.9%   |
| 81-90          | 1430      | 14.11%  |
| 301-350        | 818       | 8.07%   |
| 151-200        | 572       | 5.64%   |
| 351-500        | 517       | 5.1%    |
| 71-80          | 454       | 4.48%   |
| 121-130        | 406       | 4.01%   |
| Unknown        | 307       | 3.03%   |
| More than 1000 | 292       | 2.88%   |
| 251-300        | 289       | 2.85%   |
| 141-150        | 233       | 2.3%    |
| 501-1000       | 183       | 1.81%   |
| 111-120        | 137       | 1.35%   |
| 51-60          | 112       | 1.11%   |
| 61-70          | 110       | 1.09%   |
| 131-140        | 56        | 0.55%   |
| 91-100         | 33        | 0.33%   |
| 41-50          | 23        | 0.23%   |
| 1-40           | 4         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 3078      | 31.19%  |
| 121-160       | 2863      | 29.01%  |
| 101-120       | 2268      | 22.98%  |
| 161-240       | 803       | 8.14%   |
| Unknown       | 307       | 3.11%   |
| More than 240 | 290       | 2.94%   |
| 1-50          | 261       | 2.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 7210      | 75.75%  |
| 2     | 1573      | 16.53%  |
| 0     | 521       | 5.47%   |
| 3     | 192       | 2.02%   |
| 4     | 18        | 0.19%   |
| 6     | 2         | 0.02%   |
| 5     | 2         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4983      | 36.04%  |
| Intel                             | 4876      | 35.27%  |
| Qualcomm Atheros                  | 1261      | 9.12%   |
| Broadcom                          | 715       | 5.17%   |
| MediaTek                          | 270       | 1.95%   |
| Broadcom Limited                  | 158       | 1.14%   |
| TP-Link                           | 151       | 1.09%   |
| Ralink Technology                 | 129       | 0.93%   |
| Ralink                            | 121       | 0.88%   |
| Marvell Technology Group          | 107       | 0.77%   |
| Nvidia                            | 96        | 0.69%   |
| ASIX Electronics                  | 96        | 0.69%   |
| Samsung Electronics               | 65        | 0.47%   |
| DisplayLink                       | 56        | 0.41%   |
| NetGear                           | 52        | 0.38%   |
| Xiaomi                            | 39        | 0.28%   |
| Dell                              | 37        | 0.27%   |
| Qualcomm Atheros Communications   | 34        | 0.25%   |
| Qualcomm                          | 34        | 0.25%   |
| Aquantia                          | 33        | 0.24%   |
| Microsoft                         | 30        | 0.22%   |
| Lenovo                            | 29        | 0.21%   |
| Sierra Wireless                   | 26        | 0.19%   |
| D-Link System                     | 25        | 0.18%   |
| D-Link                            | 25        | 0.18%   |
| JMicron Technology                | 20        | 0.14%   |
| Ericsson Business Mobile Networks | 20        | 0.14%   |
| Hewlett-Packard                   | 19        | 0.14%   |
| Edimax Technology                 | 18        | 0.13%   |
| Apple                             | 17        | 0.12%   |
| OPPO Electronics                  | 16        | 0.12%   |
| Huawei Technologies               | 16        | 0.12%   |
| ICS Advent                        | 15        | 0.11%   |
| Linksys                           | 14        | 0.1%    |
| Google                            | 14        | 0.1%    |
| ASUSTek Computer                  | 14        | 0.1%    |
| IMC Networks                      | 11        | 0.08%   |
| Motorola PCS                      | 10        | 0.07%   |
| Fibocom                           | 7         | 0.05%   |
| Belkin Components                 | 7         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3213      | 19.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 445       | 2.74%   |
| Intel Wi-Fi 6 AX201                                               | 441       | 2.72%   |
| Intel Wi-Fi 6 AX200                                               | 405       | 2.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 335       | 2.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 307       | 1.89%   |
| Intel Wireless 8265 / 8275                                        | 297       | 1.83%   |
| Realtek RTL8125 2.5GbE Controller                                 | 281       | 1.73%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 261       | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 225       | 1.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 208       | 1.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 207       | 1.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 197       | 1.21%   |
| Intel Wireless 7265                                               | 184       | 1.13%   |
| Intel I211 Gigabit Network Connection                             | 170       | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 166       | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 163       | 1%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 160       | 0.99%   |
| Intel Wireless 8260                                               | 160       | 0.99%   |
| Intel Ethernet Connection I217-LM                                 | 158       | 0.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 157       | 0.97%   |
| Intel Wireless 7260                                               | 155       | 0.95%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 145       | 0.89%   |
| Intel Ethernet Controller I225-V                                  | 130       | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 126       | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 123       | 0.76%   |
| Intel Ethernet Connection (2) I219-V                              | 120       | 0.74%   |
| Intel Wireless 3165                                               | 118       | 0.73%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 118       | 0.73%   |
| Intel Ethernet Connection (4) I219-LM                             | 108       | 0.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 104       | 0.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 92        | 0.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 90        | 0.55%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 88        | 0.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 87        | 0.54%   |
| Intel 82579V Gigabit Network Connection                           | 87        | 0.54%   |
| Realtek 802.11ac NIC                                              | 85        | 0.52%   |
| ASIX AX88179 Gigabit Ethernet                                     | 84        | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 82        | 0.5%    |
| Intel Wireless-AC 9260                                            | 80        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3681      | 48.33%  |
| Realtek Semiconductor                 | 1347      | 17.68%  |
| Qualcomm Atheros                      | 1018      | 13.36%  |
| Broadcom                              | 477       | 6.26%   |
| MediaTek                              | 255       | 3.35%   |
| Ralink Technology                     | 129       | 1.69%   |
| Ralink                                | 121       | 1.59%   |
| TP-Link                               | 120       | 1.58%   |
| Broadcom Limited                      | 104       | 1.37%   |
| NetGear                               | 51        | 0.67%   |
| Qualcomm Atheros Communications       | 34        | 0.45%   |
| Sierra Wireless                       | 26        | 0.34%   |
| Microsoft                             | 25        | 0.33%   |
| Marvell Technology Group              | 24        | 0.32%   |
| D-Link                                | 24        | 0.32%   |
| Dell                                  | 23        | 0.3%    |
| Qualcomm                              | 22        | 0.29%   |
| D-Link System                         | 20        | 0.26%   |
| Edimax Technology                     | 18        | 0.24%   |
| ASUSTek Computer                      | 14        | 0.18%   |
| Linksys                               | 12        | 0.16%   |
| IMC Networks                          | 11        | 0.14%   |
| Fibocom                               | 7         | 0.09%   |
| Belkin Components                     | 7         | 0.09%   |
| Sitecom Europe                        | 6         | 0.08%   |
| Hewlett-Packard                       | 6         | 0.08%   |
| ZyDAS                                 | 4         | 0.05%   |
| Wilocity                              | 4         | 0.05%   |
| AVM                                   | 4         | 0.05%   |
| TRENDnet                              | 2         | 0.03%   |
| Micro Star International              | 2         | 0.03%   |
| Mercucys                              | 2         | 0.03%   |
| Encore Electronics                    | 2         | 0.03%   |
| BUFFALO                               | 2         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.03%   |
| Wacom                                 | 1         | 0.01%   |
| U.S. Robotics                         | 1         | 0.01%   |
| Sagem                                 | 1         | 0.01%   |
| Quectel Wireless Solutions            | 1         | 0.01%   |
| Philips (or NXP)                      | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 441       | 5.74%   |
| Intel Wi-Fi 6 AX200                                            | 405       | 5.27%   |
| Intel Wireless 8265 / 8275                                     | 297       | 3.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 261       | 3.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 225       | 2.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 208       | 2.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 207       | 2.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 197       | 2.56%   |
| Intel Wireless 7265                                            | 184       | 2.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 166       | 2.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 163       | 2.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 160       | 2.08%   |
| Intel Wireless 8260                                            | 160       | 2.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 157       | 2.04%   |
| Intel Wireless 7260                                            | 155       | 2.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 145       | 1.89%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 126       | 1.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 123       | 1.6%    |
| Intel Wireless 3165                                            | 118       | 1.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 118       | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 104       | 1.35%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 92        | 1.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 90        | 1.17%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 88        | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 87        | 1.13%   |
| Realtek 802.11ac NIC                                           | 85        | 1.11%   |
| Intel Wireless-AC 9260                                         | 80        | 1.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 78        | 1.01%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 76        | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 72        | 0.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 72        | 0.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 70        | 0.91%   |
| Broadcom BCM43142 802.11b/g/n                                  | 65        | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 60        | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 55        | 0.72%   |
| Intel Wireless 3160                                            | 55        | 0.72%   |
| Intel Centrino Wireless-N 2230                                 | 53        | 0.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 52        | 0.68%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 50        | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 50        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 4367      | 53.25%  |
| Intel                                  | 2366      | 28.85%  |
| Broadcom                               | 362       | 4.41%   |
| Qualcomm Atheros                       | 348       | 4.24%   |
| Nvidia                                 | 96        | 1.17%   |
| ASIX Electronics                       | 96        | 1.17%   |
| Marvell Technology Group               | 83        | 1.01%   |
| DisplayLink                            | 56        | 0.68%   |
| Broadcom Limited                       | 56        | 0.68%   |
| Samsung Electronics                    | 46        | 0.56%   |
| Xiaomi                                 | 39        | 0.48%   |
| Aquantia                               | 33        | 0.4%    |
| TP-Link                                | 32        | 0.39%   |
| Lenovo                                 | 29        | 0.35%   |
| JMicron Technology                     | 20        | 0.24%   |
| Apple                                  | 17        | 0.21%   |
| OPPO Electronics                       | 16        | 0.2%    |
| ICS Advent                             | 15        | 0.18%   |
| MediaTek                               | 13        | 0.16%   |
| Google                                 | 13        | 0.16%   |
| Qualcomm                               | 11        | 0.13%   |
| Huawei Technologies                    | 10        | 0.12%   |
| Motorola PCS                           | 6         | 0.07%   |
| Hewlett-Packard                        | 6         | 0.07%   |
| IBM                                    | 5         | 0.06%   |
| D-Link System                          | 5         | 0.06%   |
| VIA Technologies                       | 4         | 0.05%   |
| Microsoft                              | 4         | 0.05%   |
| Insyde Software                        | 4         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 3         | 0.04%   |
| Mellanox Technologies                  | 3         | 0.04%   |
| Dell                                   | 3         | 0.04%   |
| Chelsio Communications                 | 3         | 0.04%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.02%   |
| Tehuti Networks                        | 2         | 0.02%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.02%   |
| Spreadtrum Communications              | 2         | 0.02%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.02%   |
| Linksys                                | 2         | 0.02%   |
| LG Electronics                         | 2         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3213      | 38.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 445       | 5.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 335       | 3.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 307       | 3.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 281       | 3.34%   |
| Intel I211 Gigabit Network Connection                             | 170       | 2.02%   |
| Intel Ethernet Connection I217-LM                                 | 158       | 1.88%   |
| Intel Ethernet Controller I225-V                                  | 130       | 1.55%   |
| Intel Ethernet Connection (2) I219-V                              | 120       | 1.43%   |
| Intel Ethernet Connection (4) I219-LM                             | 108       | 1.28%   |
| Intel 82579V Gigabit Network Connection                           | 87        | 1.03%   |
| ASIX AX88179 Gigabit Ethernet                                     | 84        | 1%      |
| Intel Ethernet Connection (2) I219-LM                             | 82        | 0.97%   |
| Intel Ethernet Connection I219-LM                                 | 79        | 0.94%   |
| Intel Ethernet Connection (7) I219-V                              | 68        | 0.81%   |
| Intel Ethernet Connection I217-V                                  | 64        | 0.76%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 59        | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 56        | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                             | 56        | 0.67%   |
| Intel 82577LM Gigabit Network Connection                          | 52        | 0.62%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 49        | 0.58%   |
| Intel Ethernet Connection I218-LM                                 | 48        | 0.57%   |
| Intel 82574L Gigabit Network Connection                           | 48        | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 46        | 0.55%   |
| Intel Ethernet Connection (6) I219-V                              | 45        | 0.53%   |
| Intel Ethernet Connection (4) I219-V                              | 45        | 0.53%   |
| Intel Ethernet Connection (2) I218-V                              | 45        | 0.53%   |
| Realtek Killer E3000 2.5GbE Controller                            | 44        | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 44        | 0.52%   |
| Intel I210 Gigabit Network Connection                             | 43        | 0.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 42        | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                             | 41        | 0.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 38        | 0.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 37        | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 36        | 0.43%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 36        | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 34        | 0.4%    |
| Intel Ethernet Connection (5) I219-LM                             | 34        | 0.4%    |
| Nvidia MCP61 Ethernet                                             | 32        | 0.38%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 32        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 7672      | 50.84%  |
| WiFi     | 7279      | 48.23%  |
| Modem    | 121       | 0.8%    |
| Unknown  | 19        | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 5679      | 58.19%  |
| Ethernet | 4078      | 41.79%  |
| Modem    | 2         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 4810      | 51.13%  |
| 1     | 4092      | 43.49%  |
| 0     | 222       | 2.36%   |
| 3     | 205       | 2.18%   |
| 4     | 58        | 0.62%   |
| 5     | 11        | 0.12%   |
| 8     | 3         | 0.03%   |
| 10    | 2         | 0.02%   |
| 7     | 2         | 0.02%   |
| 6     | 2         | 0.02%   |
| 12    | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6560      | 69.26%  |
| Yes  | 2912      | 30.74%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3201      | 52.95%  |
| Realtek Semiconductor           | 630       | 10.42%  |
| Qualcomm Atheros Communications | 396       | 6.55%   |
| IMC Networks                    | 287       | 4.75%   |
| Cambridge Silicon Radio         | 266       | 4.4%    |
| Apple                           | 213       | 3.52%   |
| Broadcom                        | 198       | 3.28%   |
| Foxconn / Hon Hai               | 191       | 3.16%   |
| Lite-On Technology              | 190       | 3.14%   |
| ASUSTek Computer                | 87        | 1.44%   |
| Dell                            | 65        | 1.08%   |
| Realtek                         | 54        | 0.89%   |
| Hewlett-Packard                 | 41        | 0.68%   |
| MediaTek                        | 34        | 0.56%   |
| Ralink                          | 33        | 0.55%   |
| Toshiba                         | 27        | 0.45%   |
| Marvell Semiconductor           | 26        | 0.43%   |
| TP-Link                         | 18        | 0.3%    |
| Alps Electric                   | 11        | 0.18%   |
| Foxconn International           | 10        | 0.17%   |
| USI                             | 8         | 0.13%   |
| Ralink Technology               | 8         | 0.13%   |
| Belkin Components               | 6         | 0.1%    |
| Micro Star International        | 5         | 0.08%   |
| Logitech                        | 5         | 0.08%   |
| Integrated System Solution      | 5         | 0.08%   |
| Edimax Technology               | 5         | 0.08%   |
| Askey Computer                  | 5         | 0.08%   |
| Opticis                         | 4         | 0.07%   |
| Mobile Action Technology        | 2         | 0.03%   |
| D-Link System                   | 2         | 0.03%   |
| Conwise Technology              | 2         | 0.03%   |
| Unknown                         | 2         | 0.03%   |
| TRENDnet                        | 1         | 0.02%   |
| Roper                           | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| ISSC                            | 1         | 0.02%   |
| HTC (High Tech Computer)        | 1         | 0.02%   |
| Fujitsu Siemens Computers       | 1         | 0.02%   |
| Dynex                           | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 955       | 15.79%  |
| Intel AX201 Bluetooth                               | 818       | 13.52%  |
| Realtek Bluetooth Radio                             | 457       | 7.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 420       | 6.94%   |
| Intel AX200 Bluetooth                               | 378       | 6.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 266       | 4.4%    |
| Intel Bluetooth Device                              | 252       | 4.17%   |
| Qualcomm Atheros  Bluetooth Device                  | 193       | 3.19%   |
| Intel AX210 Bluetooth                               | 139       | 2.3%    |
| Realtek  Bluetooth 4.2 Adapter                      | 120       | 1.98%   |
| IMC Networks Wireless_Device                        | 104       | 1.72%   |
| Apple Bluetooth Host Controller                     | 101       | 1.67%   |
| IMC Networks Bluetooth Radio                        | 87        | 1.44%   |
| Intel Wireless-AC 3168 Bluetooth                    | 84        | 1.39%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 84        | 1.39%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 74        | 1.22%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 63        | 1.04%   |
| Apple Bluetooth USB Host Controller                 | 60        | 0.99%   |
| Foxconn / Hon Hai Bluetooth Device                  | 59        | 0.98%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 58        | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 58        | 0.96%   |
| IMC Networks Bluetooth Device                       | 57        | 0.94%   |
| Realtek Bluetooth Radio                             | 54        | 0.89%   |
| Lite-On Bluetooth Device                            | 43        | 0.71%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 41        | 0.68%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 38        | 0.63%   |
| Lite-On Atheros AR3012 Bluetooth                    | 35        | 0.58%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 35        | 0.58%   |
| MediaTek Wireless_Device                            | 34        | 0.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 34        | 0.56%   |
| Ralink RT3290 Bluetooth                             | 33        | 0.55%   |
| ASUS ASUS USB-BT500                                 | 30        | 0.5%    |
| Foxconn / Hon Hai Wireless_Device                   | 29        | 0.48%   |
| HP Broadcom 2070 Bluetooth Combo                    | 26        | 0.43%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 25        | 0.41%   |
| Lite-On Wireless_Device                             | 25        | 0.41%   |
| Dell DW375 Bluetooth Module                         | 24        | 0.4%    |
| Broadcom BCM2045B (BDC-2.1)                         | 22        | 0.36%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 21        | 0.35%   |
| Realtek RTL8723B Bluetooth                          | 20        | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 6878      | 53.58%  |
| AMD                                          | 2516      | 19.6%   |
| Nvidia                                       | 2255      | 17.57%  |
| C-Media Electronics                          | 162       | 1.26%   |
| Logitech                                     | 98        | 0.76%   |
| GN Netcom                                    | 65        | 0.51%   |
| Creative Labs                                | 57        | 0.44%   |
| Realtek Semiconductor                        | 53        | 0.41%   |
| Plantronics                                  | 40        | 0.31%   |
| ASUSTek Computer                             | 39        | 0.3%    |
| Apple                                        | 39        | 0.3%    |
| JMTek                                        | 37        | 0.29%   |
| Hewlett-Packard                              | 37        | 0.29%   |
| Texas Instruments                            | 36        | 0.28%   |
| Lenovo                                       | 34        | 0.26%   |
| Kingston Technology                          | 30        | 0.23%   |
| Generalplus Technology                       | 30        | 0.23%   |
| Razer USA                                    | 28        | 0.22%   |
| Corsair                                      | 28        | 0.22%   |
| Micro Star International                     | 24        | 0.19%   |
| Creative Technology                          | 24        | 0.19%   |
| Focusrite-Novation                           | 20        | 0.16%   |
| SteelSeries ApS                              | 19        | 0.15%   |
| DSEA A/S                                     | 12        | 0.09%   |
| Tenx Technology                              | 10        | 0.08%   |
| Dell                                         | 10        | 0.08%   |
| Sennheiser Communications                    | 9         | 0.07%   |
| Zoran Co. Personal Media Division (Nogatech) | 8         | 0.06%   |
| Sony                                         | 8         | 0.06%   |
| Blue Microphones                             | 8         | 0.06%   |
| RODE Microphones                             | 7         | 0.05%   |
| M-Audio                                      | 7         | 0.05%   |
| Giga-Byte Technology                         | 7         | 0.05%   |
| DCMT Technology                              | 7         | 0.05%   |
| BR23                                         | 7         | 0.05%   |
| BEHRINGER International                      | 7         | 0.05%   |
| VIA Technologies                             | 6         | 0.05%   |
| Microsoft                                    | 6         | 0.05%   |
| Samson Technologies                          | 5         | 0.04%   |
| KTMicro                                      | 5         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 876       | 5.8%    |
| Intel Sunrise Point-LP HD Audio                                            | 719       | 4.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 586       | 3.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 558       | 3.69%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 544       | 3.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 507       | 3.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 498       | 3.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 371       | 2.45%   |
| AMD Starship/Matisse HD Audio Controller                                   | 352       | 2.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 312       | 2.06%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 309       | 2.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 271       | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 267       | 1.77%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 262       | 1.73%   |
| AMD FCH Azalia Controller                                                  | 245       | 1.62%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 232       | 1.54%   |
| Intel Haswell-ULT HD Audio Controller                                      | 216       | 1.43%   |
| Intel 8 Series HD Audio Controller                                         | 215       | 1.42%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 213       | 1.41%   |
| Intel Comet Lake PCH-LP cAVS                                               | 212       | 1.4%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 197       | 1.3%    |
| Intel Broadwell-U Audio Controller                                         | 189       | 1.25%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 184       | 1.22%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 177       | 1.17%   |
| Intel 200 Series PCH HD Audio                                              | 174       | 1.15%   |
| Intel Comet Lake PCH cAVS                                                  | 157       | 1.04%   |
| Nvidia GA104 High Definition Audio Controller                              | 156       | 1.03%   |
| Nvidia GP107GL High Definition Audio Controller                            | 152       | 1.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 152       | 1.01%   |
| Nvidia GA106 High Definition Audio Controller                              | 151       | 1%      |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 142       | 0.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 140       | 0.93%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 134       | 0.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 127       | 0.84%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 124       | 0.82%   |
| Nvidia TU106 High Definition Audio Controller                              | 110       | 0.73%   |
| Nvidia High Definition Audio Controller                                    | 109       | 0.72%   |
| Nvidia Audio device                                                        | 107       | 0.71%   |
| Nvidia GF108 High Definition Audio Controller                              | 105       | 0.69%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 104       | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 1417      | 24.98%  |
| SK hynix                                | 1100      | 19.39%  |
| Micron Technology                       | 632       | 11.14%  |
| Kingston                                | 611       | 10.77%  |
| Crucial                                 | 339       | 5.98%   |
| Corsair                                 | 299       | 5.27%   |
| Unknown                                 | 274       | 4.83%   |
| G.Skill                                 | 160       | 2.82%   |
| A-DATA Technology                       | 130       | 2.29%   |
| Unknown (ABCD)                          | 99        | 1.75%   |
| Ramaxel Technology                      | 89        | 1.57%   |
| Unknown                                 | 59        | 1.04%   |
| Nanya Technology                        | 55        | 0.97%   |
| Team                                    | 49        | 0.86%   |
| Elpida                                  | 41        | 0.72%   |
| Smart                                   | 33        | 0.58%   |
| Patriot                                 | 32        | 0.56%   |
| Transcend                               | 16        | 0.28%   |
| GOODRAM                                 | 13        | 0.23%   |
| PNY                                     | 10        | 0.18%   |
| Apacer                                  | 10        | 0.18%   |
| AMD                                     | 10        | 0.18%   |
| Hewlett-Packard                         | 9         | 0.16%   |
| Smart Brazil                            | 8         | 0.14%   |
| Silicon Power                           | 8         | 0.14%   |
| ChangXin Memory                         | 7         | 0.12%   |
| ASint Technology                        | 7         | 0.12%   |
| Goldkey                                 | 6         | 0.11%   |
| Avant                                   | 6         | 0.11%   |
| Timetec                                 | 5         | 0.09%   |
| Neo Forza                               | 5         | 0.09%   |
| GeIL                                    | 5         | 0.09%   |
| Wilk                                    | 4         | 0.07%   |
| Teikon                                  | 4         | 0.07%   |
| Silicon Power Computer & Communications | 4         | 0.07%   |
| KLEVV                                   | 4         | 0.07%   |
| KETECH                                  | 4         | 0.07%   |
| Atermiter                               | 4         | 0.07%   |
| Asgard                                  | 4         | 0.07%   |
| Toshiba                                 | 3         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 84        | 1.4%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 75        | 1.25%   |
| Unknown                                                          | 59        | 0.98%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 45        | 0.75%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 44        | 0.73%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 43        | 0.72%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 42        | 0.7%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 40        | 0.67%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 39        | 0.65%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 38        | 0.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 38        | 0.63%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 36        | 0.6%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 32        | 0.53%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 31        | 0.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 30        | 0.5%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 29        | 0.48%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 29        | 0.48%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 28        | 0.47%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 27        | 0.45%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 26        | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 24        | 0.4%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 24        | 0.4%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 23        | 0.38%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 23        | 0.38%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 22        | 0.37%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 22        | 0.37%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 22        | 0.37%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 21        | 0.35%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 21        | 0.35%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 21        | 0.35%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 21        | 0.35%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 0.33%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 20        | 0.33%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 20        | 0.33%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 20        | 0.33%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 20        | 0.33%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 20        | 0.33%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 19        | 0.32%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 19        | 0.32%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 18        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2717      | 55.02%  |
| DDR3    | 1266      | 25.64%  |
| LPDDR4  | 351       | 7.11%   |
| DDR5    | 161       | 3.26%   |
| LPDDR3  | 151       | 3.06%   |
| DDR2    | 82        | 1.66%   |
| Unknown | 71        | 1.44%   |
| SDRAM   | 63        | 1.28%   |
| LPDDR5  | 58        | 1.17%   |
| DDR     | 13        | 0.26%   |
| DRAM    | 5         | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 2813      | 56.81%  |
| DIMM            | 1486      | 30.01%  |
| Row Of Chips    | 601       | 12.14%  |
| Chip            | 20        | 0.4%    |
| Unknown         | 19        | 0.38%   |
| RIMM            | 9         | 0.18%   |
| Proprietary Car | 2         | 0.04%   |
| FB-DIMM         | 2         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 2187      | 41.36%  |
| 4096   | 1298      | 24.55%  |
| 16384  | 1064      | 20.12%  |
| 2048   | 393       | 7.43%   |
| 32768  | 258       | 4.88%   |
| 1024   | 72        | 1.36%   |
| 65536  | 10        | 0.19%   |
| 131072 | 2         | 0.04%   |
| 6144   | 2         | 0.04%   |
| 1536   | 1         | 0.02%   |
| 512    | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 1240      | 23.41%  |
| 1600    | 864       | 16.31%  |
| 2667    | 784       | 14.8%   |
| 2400    | 441       | 8.33%   |
| 2133    | 262       | 4.95%   |
| 1333    | 253       | 4.78%   |
| 4267    | 151       | 2.85%   |
| 4800    | 142       | 2.68%   |
| 3600    | 128       | 2.42%   |
| 1334    | 102       | 1.93%   |
| 1867    | 101       | 1.91%   |
| 6400    | 66        | 1.25%   |
| 3266    | 55        | 1.04%   |
| 667     | 49        | 0.93%   |
| 800     | 48        | 0.91%   |
| 3000    | 46        | 0.87%   |
| 1067    | 41        | 0.77%   |
| 2666    | 39        | 0.74%   |
| 3733    | 36        | 0.68%   |
| Unknown | 36        | 0.68%   |
| 1066    | 32        | 0.6%    |
| 2933    | 30        | 0.57%   |
| 4266    | 29        | 0.55%   |
| 3400    | 23        | 0.43%   |
| 1866    | 23        | 0.43%   |
| 1800    | 22        | 0.42%   |
| 3800    | 21        | 0.4%    |
| 3533    | 18        | 0.34%   |
| 4199    | 16        | 0.3%    |
| 8400    | 12        | 0.23%   |
| 3534    | 10        | 0.19%   |
| 3466    | 10        | 0.19%   |
| 5600    | 8         | 0.15%   |
| 3666    | 8         | 0.15%   |
| 3500    | 8         | 0.15%   |
| 2800    | 8         | 0.15%   |
| 5200    | 7         | 0.13%   |
| 3866    | 7         | 0.13%   |
| 2048    | 7         | 0.13%   |
| 2000    | 7         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 75        | 32.19%  |
| Brother Industries    | 48        | 20.6%   |
| Canon                 | 33        | 14.16%  |
| Samsung Electronics   | 26        | 11.16%  |
| Seiko Epson           | 23        | 9.87%   |
| STMicroelectronics    | 4         | 1.72%   |
| QinHeng Electronics   | 3         | 1.29%   |
| Prolific Technology   | 3         | 1.29%   |
| Lexmark International | 3         | 1.29%   |
| Kyocera               | 3         | 1.29%   |
| Dymo-CoStar           | 3         | 1.29%   |
| Zebra                 | 1         | 0.43%   |
| Xiaomi                | 1         | 0.43%   |
| Xerox                 | 1         | 0.43%   |
| Pantum                | 1         | 0.43%   |
| Oki Data              | 1         | 0.43%   |
| Fuji Xerox            | 1         | 0.43%   |
| BESTEASY              | 1         | 0.43%   |
| Apple                 | 1         | 0.43%   |
| Unknown               | 1         | 0.43%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2300 series                                    | 6         | 2.52%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 3         | 1.26%   |
| Seiko Epson L220 Series                                   | 3         | 1.26%   |
| Seiko Epson ET-2720 Series                                | 3         | 1.26%   |
| Samsung ML-216x Series Laser Printer                      | 3         | 1.26%   |
| Samsung Composite Device                                  | 3         | 1.26%   |
| QinHeng CH340S                                            | 3         | 1.26%   |
| Prolific PL2305 Parallel Port                             | 3         | 1.26%   |
| HP OfficeJet 5600 (USBHUB)                                | 3         | 1.26%   |
| HP Officejet 4500 G510n-z                                 | 3         | 1.26%   |
| HP OfficeJet 3830 series                                  | 3         | 1.26%   |
| HP LaserJet M14-M17                                       | 3         | 1.26%   |
| HP LaserJet 4250                                          | 3         | 1.26%   |
| HP DeskJet 2700 series                                    | 3         | 1.26%   |
| HP DeskJet 2600 series                                    | 3         | 1.26%   |
| HP DeskJet 2130 series                                    | 3         | 1.26%   |
| Canon LBP2900                                             | 3         | 1.26%   |
| Brother Printer                                           | 3         | 1.26%   |
| Brother HL-1440 Laser Printer                             | 3         | 1.26%   |
| Seiko Epson XP-2100 Series                                | 2         | 0.84%   |
| Seiko Epson L3110 Series                                  | 2         | 0.84%   |
| Seiko Epson ET-2810 Series                                | 2         | 0.84%   |
| Samsung SCX-472x Series                                   | 2         | 0.84%   |
| Samsung M2070 Series                                      | 2         | 0.84%   |
| Samsung C460 Series                                       | 2         | 0.84%   |
| Samsung C43x Series                                       | 2         | 0.84%   |
| HP OfficeJet Pro 8020 series                              | 2         | 0.84%   |
| HP LaserJet P1005                                         | 2         | 0.84%   |
| HP LaserJet 3015                                          | 2         | 0.84%   |
| HP DeskJet 4100 series                                    | 2         | 0.84%   |
| HP DeskJet 1110 series                                    | 2         | 0.84%   |
| HP Color LaserJet CP1215                                  | 2         | 0.84%   |
| Dymo-CoStar LabelWriter 400                               | 2         | 0.84%   |
| Canon TS3100 series                                       | 2         | 0.84%   |
| Canon PIXMA MG2500 Series                                 | 2         | 0.84%   |
| Brother MFC-L2700DW                                       | 2         | 0.84%   |
| Brother HL-L2375DW series                                 | 2         | 0.84%   |
| Brother HL-L2350DW series                                 | 2         | 0.84%   |
| Brother HL-2270DW Laser Printer                           | 2         | 0.84%   |
| Brother DCP-J105                                          | 2         | 0.84%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 24        | 61.54%  |
| Seiko Epson                 | 7         | 17.95%  |
| Hewlett-Packard             | 7         | 17.95%  |
| Acer Peripherals (now BenQ) | 1         | 2.56%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 120                             | 5         | 12.82%  |
| Canon CanoScan LiDE 100                             | 4         | 10.26%  |
| Canon CanoScan LiDE 110                             | 3         | 7.69%   |
| Canon CanoScan LIDE 25                              | 2         | 5.13%   |
| Canon CanoScan LiDE 220                             | 2         | 5.13%   |
| Canon CanoScan 4200F                                | 2         | 5.13%   |
| Seiko Epson GT-X770 [Perfection V500]               | 1         | 2.56%   |
| Seiko Epson GT-F700 [Perfection V350]               | 1         | 2.56%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO] | 1         | 2.56%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]  | 1         | 2.56%   |
| Seiko Epson GT-7700U [Perfection 1240U]             | 1         | 2.56%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]   | 1         | 2.56%   |
| Seiko Epson ES-D200 [GT-S50]                        | 1         | 2.56%   |
| HP Scanjet N6010                                    | 1         | 2.56%   |
| HP ScanJet G4010                                    | 1         | 2.56%   |
| HP Scanjet G2710                                    | 1         | 2.56%   |
| HP ScanJet 4850C/4890C                              | 1         | 2.56%   |
| HP ScanJet 3970c                                    | 1         | 2.56%   |
| HP ScanJet 3400cse                                  | 1         | 2.56%   |
| HP OfficeJet 6110                                   | 1         | 2.56%   |
| Canon CanoScan N670U/N676U/LiDE 20                  | 1         | 2.56%   |
| Canon CanoScan N1240U/LiDE 30                       | 1         | 2.56%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40              | 1         | 2.56%   |
| Canon CanoScan LiDE 200                             | 1         | 2.56%   |
| Canon CanoScan 9000F Mark II                        | 1         | 2.56%   |
| Canon CanoScan 1220U                                | 1         | 2.56%   |
| Acer Peripherals (now BenQ) Benq 5000               | 1         | 2.56%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1080      | 18.52%  |
| IMC Networks                           | 581       | 9.96%   |
| Microdia                               | 546       | 9.36%   |
| Realtek Semiconductor                  | 442       | 7.58%   |
| Sunplus Innovation Technology          | 353       | 6.05%   |
| Quanta                                 | 352       | 6.04%   |
| Logitech                               | 311       | 5.33%   |
| Cheng Uei Precision Industry (Foxlink) | 213       | 3.65%   |
| Apple                                  | 208       | 3.57%   |
| Bison Electronics                      | 200       | 3.43%   |
| Acer                                   | 192       | 3.29%   |
| Syntek                                 | 158       | 2.71%   |
| Luxvisions Innotech Limited            | 156       | 2.67%   |
| Suyin                                  | 134       | 2.3%    |
| Lite-On Technology                     | 117       | 2.01%   |
| Microsoft                              | 70        | 1.2%    |
| Alcor Micro                            | 63        | 1.08%   |
| Samsung Electronics                    | 62        | 1.06%   |
| Silicon Motion                         | 56        | 0.96%   |
| Sonix Technology                       | 49        | 0.84%   |
| Ricoh                                  | 37        | 0.63%   |
| SunplusIT                              | 31        | 0.53%   |
| Z-Star Microelectronics                | 30        | 0.51%   |
| Lenovo                                 | 23        | 0.39%   |
| icSpring                               | 23        | 0.39%   |
| Generalplus Technology                 | 21        | 0.36%   |
| Primax Electronics                     | 20        | 0.34%   |
| Importek                               | 19        | 0.33%   |
| ARC International                      | 17        | 0.29%   |
| Y Media                                | 14        | 0.24%   |
| ALi                                    | 14        | 0.24%   |
| Creative Technology                    | 10        | 0.17%   |
| Trust                                  | 9         | 0.15%   |
| webcam                                 | 8         | 0.14%   |
| Razer USA                              | 8         | 0.14%   |
| Sunplus Technology                     | 7         | 0.12%   |
| OmniVision Technologies                | 7         | 0.12%   |
| MacroSilicon                           | 7         | 0.12%   |
| GEMBIRD                                | 7         | 0.12%   |
| Cubeternet                             | 7         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 272       | 4.62%   |
| Chicony Integrated Camera                           | 242       | 4.11%   |
| Realtek Integrated_Webcam_HD                        | 166       | 2.82%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 160       | 2.72%   |
| IMC Networks Integrated Camera                      | 157       | 2.67%   |
| Syntek Integrated Camera                            | 109       | 1.85%   |
| Chicony HD WebCam                                   | 98        | 1.66%   |
| Sunplus Integrated_Webcam_HD                        | 97        | 1.65%   |
| Logitech Webcam C270                                | 73        | 1.24%   |
| Logitech HD Pro Webcam C920                         | 69        | 1.17%   |
| Chicony HP HD Camera                                | 68        | 1.15%   |
| Bison Integrated Camera                             | 67        | 1.14%   |
| Apple FaceTime HD Camera (Built-in)                 | 67        | 1.14%   |
| Acer Integrated Camera                              | 65        | 1.1%    |
| Samsung Galaxy series, misc. (MTP mode)             | 62        | 1.05%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 62        | 1.05%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 58        | 0.98%   |
| Quanta HP HD Camera                                 | 54        | 0.92%   |
| Quanta HD User Facing                               | 52        | 0.88%   |
| Realtek USB Camera                                  | 48        | 0.81%   |
| Apple Built-in iSight                               | 47        | 0.8%    |
| IMC Networks HD Camera                              | 46        | 0.78%   |
| Sunplus HD WebCam                                   | 45        | 0.76%   |
| Quanta HP TrueVision HD Camera                      | 41        | 0.7%    |
| Microdia Webcam Vitade AF                           | 40        | 0.68%   |
| Quanta HP Wide Vision HD Camera                     | 39        | 0.66%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 38        | 0.65%   |
| Chicony HP Wide Vision HD Camera                    | 38        | 0.65%   |
| Chicony HD User Facing                              | 36        | 0.61%   |
| Acer HD Webcam                                      | 36        | 0.61%   |
| Lite-On Integrated Camera                           | 35        | 0.59%   |
| Luxvisions Innotech Limited Integrated Camera       | 34        | 0.58%   |
| Chicony USB2.0 Camera                               | 34        | 0.58%   |
| Chicony TOSHIBA Web Camera - HD                     | 34        | 0.58%   |
| Luxvisions Innotech Limited HP HD Camera            | 32        | 0.54%   |
| Logitech C922 Pro Stream Webcam                     | 31        | 0.53%   |
| Chicony HP TrueVision HD Camera                     | 31        | 0.53%   |
| Alcor Micro USB 2.0 Camera                          | 31        | 0.53%   |
| Sonix USB2.0 HD UVC WebCam                          | 30        | 0.51%   |
| Bison SunplusIT Integrated Camera                   | 30        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 368       | 30.44%  |
| Validity Sensors                   | 348       | 28.78%  |
| Shenzhen Goodix Technology         | 258       | 21.34%  |
| Elan Microelectronics              | 100       | 8.27%   |
| Upek                               | 39        | 3.23%   |
| AuthenTec                          | 31        | 2.56%   |
| LighTuning Technology              | 30        | 2.48%   |
| Realtek USB2.0 Finger Print Bridge | 14        | 1.16%   |
| STMicroelectronics                 | 5         | 0.41%   |
| Samsung Electronics                | 5         | 0.41%   |
| HOLTEK                             | 3         | 0.25%   |
| Focal-systems.Corp                 | 3         | 0.25%   |
| DigitalPersona                     | 2         | 0.17%   |
| Dell                               | 2         | 0.17%   |
| Microsoft                          | 1         | 0.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 176       | 14.56%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 87        | 7.2%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 81        | 6.7%    |
| Elan ELAN:ARM-M4                                                           | 60        | 4.96%   |
| Shenzhen Goodix Fingerprint Reader                                         | 51        | 4.22%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 47        | 3.89%   |
| Elan ELAN:Fingerprint                                                      | 39        | 3.23%   |
| Synaptics UWP WBDI                                                         | 36        | 2.98%   |
| Synaptics WBDI                                                             | 35        | 2.89%   |
| Validity Sensors Synaptics WBDI                                            | 34        | 2.81%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 34        | 2.81%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 32        | 2.65%   |
| Shenzhen Goodix FingerPrint                                                | 31        | 2.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 30        | 2.48%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 29        | 2.4%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 28        | 2.32%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 28        | 2.32%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 24        | 1.99%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 22        | 1.82%   |
| Validity Sensors VFS491                                                    | 21        | 1.74%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 19        | 1.57%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 18        | 1.49%   |
| Validity Sensors Fingerprint scanner                                       | 18        | 1.49%   |
| Synaptics UWP WBDI Device                                                  | 16        | 1.32%   |
| Synaptics  WBDI                                                            | 16        | 1.32%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 15        | 1.24%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 15        | 1.24%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 15        | 1.24%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 14        | 1.16%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 13        | 1.08%   |
| AuthenTec Fingerprint Sensor                                               | 13        | 1.08%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 11        | 0.91%   |
| Unknown                                                                    | 10        | 0.83%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 7         | 0.58%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 0.58%   |
| AuthenTec AES2810                                                          | 7         | 0.58%   |
| Validity Sensors VFS Fingerprint sensor                                    | 6         | 0.5%    |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 6         | 0.5%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 0.5%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 0.41%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 236       | 51.64%  |
| Alcor Micro               | 121       | 26.48%  |
| O2 Micro                  | 21        | 4.6%    |
| Upek                      | 17        | 3.72%   |
| Gemalto (was Gemplus)     | 13        | 2.84%   |
| Lenovo                    | 8         | 1.75%   |
| Advanced Card Systems     | 7         | 1.53%   |
| SCM Microsystems          | 6         | 1.31%   |
| Chicony Electronics       | 5         | 1.09%   |
| Realtek Semiconductor     | 4         | 0.88%   |
| Aladdin Knowledge Systems | 3         | 0.66%   |
| Watchdata                 | 2         | 0.44%   |
| Reiner SCT Kartensysteme  | 2         | 0.44%   |
| OmniKey                   | 2         | 0.44%   |
| Giesecke & Devrient       | 2         | 0.44%   |
| Fujitsu Siemens Computers | 2         | 0.44%   |
| Cherry                    | 2         | 0.44%   |
| NXP Semiconductors        | 1         | 0.22%   |
| C3PO                      | 1         | 0.22%   |
| BIT4ID                    | 1         | 0.22%   |
| Aktiv                     | 1         | 0.22%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 120       | 26.26%  |
| Broadcom 58200                                                               | 90        | 19.69%  |
| Broadcom BCM5880 Secure Applications Processor                               | 65        | 14.22%  |
| Broadcom 5880                                                                | 53        | 11.6%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 28        | 6.13%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 20        | 4.38%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 17        | 3.72%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 11        | 2.41%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 1.53%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 6         | 1.31%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 5         | 1.09%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 4         | 0.88%   |
| Aladdin Knowledge Systems Token JC                                           | 3         | 0.66%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 3         | 0.66%   |
| Watchdata USB Key                                                            | 2         | 0.44%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.44%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 2         | 0.44%   |
| Advanced Card Systems ACR122U                                                | 2         | 0.44%   |
| OmniKey CardMan 4321                                                         | 1         | 0.22%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 0.22%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.22%   |
| NXP Semiconductors PR533                                                     | 1         | 0.22%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.22%   |
| Giesecke & Devrient StarSign CUT S                                           | 1         | 0.22%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.22%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.22%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.22%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.22%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.22%   |
| C3PO LTC31v2                                                                 | 1         | 0.22%   |
| BIT4ID miniLector EVO                                                        | 1         | 0.22%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.22%   |
| Aktiv Rutoken lite                                                           | 1         | 0.22%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.22%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.22%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 6387      | 67.2%   |
| 1     | 2485      | 26.14%  |
| 2     | 524       | 5.51%   |
| 3     | 76        | 0.8%    |
| 4     | 13        | 0.14%   |
| 5     | 11        | 0.12%   |
| 8     | 3         | 0.03%   |
| 6     | 3         | 0.03%   |
| 7     | 2         | 0.02%   |
| 9     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1183      | 31.14%  |
| Graphics card            | 932       | 24.53%  |
| Chipcard                 | 419       | 11.03%  |
| Net/wireless             | 413       | 10.87%  |
| Camera                   | 189       | 4.97%   |
| Multimedia controller    | 132       | 3.47%   |
| Communication controller | 102       | 2.68%   |
| Unassigned class         | 96        | 2.53%   |
| Sound                    | 85        | 2.24%   |
| Bluetooth                | 83        | 2.18%   |
| Storage                  | 37        | 0.97%   |
| Net/ethernet             | 32        | 0.84%   |
| Card reader              | 30        | 0.79%   |
| Network                  | 24        | 0.63%   |
| Storage/raid             | 13        | 0.34%   |
| Dvb card                 | 7         | 0.18%   |
| Modem                    | 6         | 0.16%   |
| Storage/ata              | 4         | 0.11%   |
| Storage/nvme             | 3         | 0.08%   |
| Flash memory             | 3         | 0.08%   |
| Wireless                 | 2         | 0.05%   |
| Tv card                  | 2         | 0.05%   |
| Unclassified device      | 1         | 0.03%   |
| Firewire controller      | 1         | 0.03%   |


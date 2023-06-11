EndeavourOS - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for EndeavourOS.

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

Total: 761

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6510              | [e7c1e59ac7](https://linux-hardware.org/?probe=e7c1e59ac7) | Jun 10, 2023 |
| Dell          | Inspiron 3583               | [2627421665](https://linux-hardware.org/?probe=2627421665) | Jun 09, 2023 |
| Sony          | SVE1713X1EB                 | [f1c10c92b3](https://linux-hardware.org/?probe=f1c10c92b3) | Jun 09, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [ab95a219f5](https://linux-hardware.org/?probe=ab95a219f5) | Jun 09, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [2f0f8eb596](https://linux-hardware.org/?probe=2f0f8eb596) | Jun 09, 2023 |
| VIT           | P2402                       | [5ea93f652a](https://linux-hardware.org/?probe=5ea93f652a) | Jun 09, 2023 |
| Acer          | Aspire A315-51              | [9bcc99d434](https://linux-hardware.org/?probe=9bcc99d434) | Jun 08, 2023 |
| Acer          | Aspire A315-51              | [3013e9caf2](https://linux-hardware.org/?probe=3013e9caf2) | Jun 08, 2023 |
| Dell          | Vostro 1015                 | [3e38c53463](https://linux-hardware.org/?probe=3e38c53463) | Jun 07, 2023 |
| Dell          | Vostro 1015                 | [0e24e0ad6c](https://linux-hardware.org/?probe=0e24e0ad6c) | Jun 07, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [33fb312b6d](https://linux-hardware.org/?probe=33fb312b6d) | Jun 05, 2023 |
| Sony          | SVE1713X1EB                 | [6a50598ca6](https://linux-hardware.org/?probe=6a50598ca6) | Jun 04, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [cadfadec0e](https://linux-hardware.org/?probe=cadfadec0e) | Jun 03, 2023 |
| Sony          | SVE1713X1EB                 | [fc0097b52f](https://linux-hardware.org/?probe=fc0097b52f) | Jun 03, 2023 |
| TUXEDO        | InfinityBook Pro 15 v5      | [1b01df33d2](https://linux-hardware.org/?probe=1b01df33d2) | Jun 03, 2023 |
| HP            | Laptop 15-db0xxx            | [04830d213f](https://linux-hardware.org/?probe=04830d213f) | Jun 03, 2023 |
| Acer          | Aspire E5-575G              | [c4cd05b00f](https://linux-hardware.org/?probe=c4cd05b00f) | Jun 01, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [3de415ea72](https://linux-hardware.org/?probe=3de415ea72) | Jun 01, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c198463bc3](https://linux-hardware.org/?probe=c198463bc3) | May 31, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [87d9c3f3a1](https://linux-hardware.org/?probe=87d9c3f3a1) | May 31, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [3b186c07a2](https://linux-hardware.org/?probe=3b186c07a2) | May 30, 2023 |
| ASUSTek       | GL553VD                     | [a1f825f4e5](https://linux-hardware.org/?probe=a1f825f4e5) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23252UU       | [7819b88c10](https://linux-hardware.org/?probe=7819b88c10) | May 29, 2023 |
| Lenovo        | ThinkPad T480 20L5A00PCD    | [0b04d3bf20](https://linux-hardware.org/?probe=0b04d3bf20) | May 28, 2023 |
| ASUSTek       | X455LF                      | [b90c1083ca](https://linux-hardware.org/?probe=b90c1083ca) | May 28, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [574e88c4f3](https://linux-hardware.org/?probe=574e88c4f3) | May 28, 2023 |
| Acer          | Aspire E5-575G              | [af33101302](https://linux-hardware.org/?probe=af33101302) | May 28, 2023 |
| Sony          | SVE1713X1EB                 | [2695d0a6c8](https://linux-hardware.org/?probe=2695d0a6c8) | May 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [8621305f75](https://linux-hardware.org/?probe=8621305f75) | May 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4362f979b8](https://linux-hardware.org/?probe=4362f979b8) | May 26, 2023 |
| Acer          | Aspire E5-573G              | [4c22ef876f](https://linux-hardware.org/?probe=4c22ef876f) | May 26, 2023 |
| Apple         | MacBookPro16,2              | [46cb91a74d](https://linux-hardware.org/?probe=46cb91a74d) | May 25, 2023 |
| Dell          | Inspiron 3583               | [7f5d36cc34](https://linux-hardware.org/?probe=7f5d36cc34) | May 23, 2023 |
| Lenovo        | Yoga 710-11IKB 80V6         | [a48977a871](https://linux-hardware.org/?probe=a48977a871) | May 22, 2023 |
| HP            | Laptop 14s-dk1xxx           | [d9f9d8c907](https://linux-hardware.org/?probe=d9f9d8c907) | May 22, 2023 |
| HUAWEI        | CREM-WXX9                   | [73dfd22efc](https://linux-hardware.org/?probe=73dfd22efc) | May 21, 2023 |
| ASUSTek       | N56VB                       | [b7655822d2](https://linux-hardware.org/?probe=b7655822d2) | May 19, 2023 |
| Acer          | Aspire A315-42G             | [1125a4111e](https://linux-hardware.org/?probe=1125a4111e) | May 19, 2023 |
| Dell          | Inspiron 3583               | [1edee9f902](https://linux-hardware.org/?probe=1edee9f902) | May 18, 2023 |
| Dell          | Inspiron 5577               | [e4bfe14f2d](https://linux-hardware.org/?probe=e4bfe14f2d) | May 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [35d056f8bd](https://linux-hardware.org/?probe=35d056f8bd) | May 11, 2023 |
| ASUSTek       | N56VB                       | [e914b76fef](https://linux-hardware.org/?probe=e914b76fef) | May 10, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [d764690667](https://linux-hardware.org/?probe=d764690667) | May 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | [b81c403545](https://linux-hardware.org/?probe=b81c403545) | May 09, 2023 |
| Lenovo        | G560 0679                   | [a916fc6080](https://linux-hardware.org/?probe=a916fc6080) | May 08, 2023 |
| Timi          | TM1701                      | [c41d566374](https://linux-hardware.org/?probe=c41d566374) | May 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [acd4c4af90](https://linux-hardware.org/?probe=acd4c4af90) | May 07, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7aeb31c7f1](https://linux-hardware.org/?probe=7aeb31c7f1) | May 05, 2023 |
| MSI           | Modern 14 B11MOL            | [d6bc185f4e](https://linux-hardware.org/?probe=d6bc185f4e) | May 05, 2023 |
| Dell          | Inspiron 5402               | [bac25fa124](https://linux-hardware.org/?probe=bac25fa124) | May 04, 2023 |
| Lenovo        | ThinkPad W530 24473F2       | [937dddbff0](https://linux-hardware.org/?probe=937dddbff0) | May 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [4aec6123b0](https://linux-hardware.org/?probe=4aec6123b0) | May 04, 2023 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [9984dd7707](https://linux-hardware.org/?probe=9984dd7707) | May 03, 2023 |
| Notebook      | NS5x_NS7xPU                 | [c775137d4f](https://linux-hardware.org/?probe=c775137d4f) | May 02, 2023 |
| Apple         | MacBookAir7,2               | [1a343a4622](https://linux-hardware.org/?probe=1a343a4622) | Apr 30, 2023 |
| Dell          | Latitude 5580               | [556abc1561](https://linux-hardware.org/?probe=556abc1561) | Apr 30, 2023 |
| Dell          | Inspiron 15 3520            | [f767bfff00](https://linux-hardware.org/?probe=f767bfff00) | Apr 29, 2023 |
| Apple         | MacBookAir7,2               | [c1e0f0fa03](https://linux-hardware.org/?probe=c1e0f0fa03) | Apr 29, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [a8adc86550](https://linux-hardware.org/?probe=a8adc86550) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f1d5d361d5](https://linux-hardware.org/?probe=f1d5d361d5) | Apr 27, 2023 |
| MSI           | Modern 14 C7M               | [5946c9a0d2](https://linux-hardware.org/?probe=5946c9a0d2) | Apr 27, 2023 |
| Acer          | Aspire A515-45              | [496934207f](https://linux-hardware.org/?probe=496934207f) | Apr 25, 2023 |
| Acer          | Aspire A515-45              | [0466417666](https://linux-hardware.org/?probe=0466417666) | Apr 25, 2023 |
| Notebook      | NH5x_NH7xHP                 | [6f1c24d844](https://linux-hardware.org/?probe=6f1c24d844) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | [47ac6239d5](https://linux-hardware.org/?probe=47ac6239d5) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | [a05c41b44d](https://linux-hardware.org/?probe=a05c41b44d) | Apr 24, 2023 |
| Sony          | SVE1713X1EB                 | [b935ad65e3](https://linux-hardware.org/?probe=b935ad65e3) | Apr 22, 2023 |
| Apple         | MacBookAir7,2               | [17ae2e245a](https://linux-hardware.org/?probe=17ae2e245a) | Apr 22, 2023 |
| Notebook      | W65_W67RB                   | [f34e442b8b](https://linux-hardware.org/?probe=f34e442b8b) | Apr 22, 2023 |
| MSI           | GP60 2QE                    | [550a1cee3b](https://linux-hardware.org/?probe=550a1cee3b) | Apr 22, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [00f7379c8f](https://linux-hardware.org/?probe=00f7379c8f) | Apr 21, 2023 |
| MSI           | Stealth 15M B12UE           | [d26a12b2e3](https://linux-hardware.org/?probe=d26a12b2e3) | Apr 21, 2023 |
| ASUSTek       | X55A                        | [c5386929ba](https://linux-hardware.org/?probe=c5386929ba) | Apr 17, 2023 |
| Lenovo        | ThinkPad T490 20N20008US    | [f365509651](https://linux-hardware.org/?probe=f365509651) | Apr 15, 2023 |
| HUAWEI        | HLYL-WXX9                   | [8eaac4a62d](https://linux-hardware.org/?probe=8eaac4a62d) | Apr 13, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [abf6dd7200](https://linux-hardware.org/?probe=abf6dd7200) | Apr 13, 2023 |
| Apple         | MacBookAir7,2               | [47f2ba894b](https://linux-hardware.org/?probe=47f2ba894b) | Apr 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d9f95c9169](https://linux-hardware.org/?probe=d9f95c9169) | Apr 11, 2023 |
| Sony          | SVE1713X1EB                 | [ccf16cae6a](https://linux-hardware.org/?probe=ccf16cae6a) | Apr 10, 2023 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | [90d7e2bb21](https://linux-hardware.org/?probe=90d7e2bb21) | Apr 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [ea22560713](https://linux-hardware.org/?probe=ea22560713) | Apr 09, 2023 |
| Acer          | Aspire E5-575               | [15d7d40bed](https://linux-hardware.org/?probe=15d7d40bed) | Apr 09, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C6S... | [aee22ee8b3](https://linux-hardware.org/?probe=aee22ee8b3) | Apr 08, 2023 |
| HP            | 250 G4                      | [3e85d0e3ef](https://linux-hardware.org/?probe=3e85d0e3ef) | Apr 06, 2023 |
| HP            | Unknown                     | [0af30fd642](https://linux-hardware.org/?probe=0af30fd642) | Apr 06, 2023 |
| Sony          | SVE1713X1EB                 | [c31fccd9d8](https://linux-hardware.org/?probe=c31fccd9d8) | Apr 05, 2023 |
| HP            | ZBook 17 G2                 | [258f32d502](https://linux-hardware.org/?probe=258f32d502) | Apr 05, 2023 |
| MSI           | Modern 15 A11SBU            | [269c7d638e](https://linux-hardware.org/?probe=269c7d638e) | Apr 05, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [546e8e3742](https://linux-hardware.org/?probe=546e8e3742) | Apr 04, 2023 |
| Dell          | Inspiron 5402               | [5035f094da](https://linux-hardware.org/?probe=5035f094da) | Apr 03, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [9ba99b597e](https://linux-hardware.org/?probe=9ba99b597e) | Apr 03, 2023 |
| Apple         | MacBookAir6,2               | [d64af320d7](https://linux-hardware.org/?probe=d64af320d7) | Apr 02, 2023 |
| Apple         | MacBookAir6,2               | [3400bd9412](https://linux-hardware.org/?probe=3400bd9412) | Apr 02, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2R40... | [edb6e927bd](https://linux-hardware.org/?probe=edb6e927bd) | Apr 02, 2023 |
| PC Special... | Elimina Iv 17               | [0681af5346](https://linux-hardware.org/?probe=0681af5346) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | [bfba694531](https://linux-hardware.org/?probe=bfba694531) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | [4169f13182](https://linux-hardware.org/?probe=4169f13182) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [016ddeab52](https://linux-hardware.org/?probe=016ddeab52) | Mar 31, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [3ac0a9cc94](https://linux-hardware.org/?probe=3ac0a9cc94) | Mar 31, 2023 |
| GPD           | G1621-02                    | [7d000ab41b](https://linux-hardware.org/?probe=7d000ab41b) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [008eb6ad60](https://linux-hardware.org/?probe=008eb6ad60) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4dd142ab8f](https://linux-hardware.org/?probe=4dd142ab8f) | Mar 31, 2023 |
| Sony          | SVE1713X1EB                 | [8953aa2e04](https://linux-hardware.org/?probe=8953aa2e04) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [d1295d9d1e](https://linux-hardware.org/?probe=d1295d9d1e) | Mar 30, 2023 |
| AWOW          | AL34                        | [19f60f27c8](https://linux-hardware.org/?probe=19f60f27c8) | Mar 29, 2023 |
| HP            | EliteBook 840 G5            | [65671e15cb](https://linux-hardware.org/?probe=65671e15cb) | Mar 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [c1f1d2bcc8](https://linux-hardware.org/?probe=c1f1d2bcc8) | Mar 28, 2023 |
| Sony          | SVE1713X1EB                 | [fa77641b57](https://linux-hardware.org/?probe=fa77641b57) | Mar 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [d80388d7ef](https://linux-hardware.org/?probe=d80388d7ef) | Mar 27, 2023 |
| ASUSTek       | N76VM                       | [0a05b4b5ce](https://linux-hardware.org/?probe=0a05b4b5ce) | Mar 26, 2023 |
| Samsung       | 550XDA                      | [058982f7d8](https://linux-hardware.org/?probe=058982f7d8) | Mar 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [18cd806803](https://linux-hardware.org/?probe=18cd806803) | Mar 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E6C... | [3042a430c0](https://linux-hardware.org/?probe=3042a430c0) | Mar 24, 2023 |
| HP            | EliteBook 850 G1            | [a27ad7df2d](https://linux-hardware.org/?probe=a27ad7df2d) | Mar 22, 2023 |
| GPD           | G1619-04                    | [c69bb703ae](https://linux-hardware.org/?probe=c69bb703ae) | Mar 21, 2023 |
| HP            | EliteBook 8460p             | [e0ec2e73be](https://linux-hardware.org/?probe=e0ec2e73be) | Mar 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [a0ebd92c60](https://linux-hardware.org/?probe=a0ebd92c60) | Mar 21, 2023 |
| Acer          | Swift SF315-52G             | [f6042580d0](https://linux-hardware.org/?probe=f6042580d0) | Mar 20, 2023 |
| Notebook      | N150ZU                      | [4b7d1e249f](https://linux-hardware.org/?probe=4b7d1e249f) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [b82aade579](https://linux-hardware.org/?probe=b82aade579) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [361ca1537d](https://linux-hardware.org/?probe=361ca1537d) | Mar 19, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [a911c14f22](https://linux-hardware.org/?probe=a911c14f22) | Mar 19, 2023 |
| Samsung       | 550XDA                      | [5f14b733bb](https://linux-hardware.org/?probe=5f14b733bb) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [6dda9bae81](https://linux-hardware.org/?probe=6dda9bae81) | Mar 18, 2023 |
| ASUSTek       | UX301LAA                    | [882d4d095b](https://linux-hardware.org/?probe=882d4d095b) | Mar 18, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [809d9ecb40](https://linux-hardware.org/?probe=809d9ecb40) | Mar 18, 2023 |
| Apple         | MacBookAir5,2               | [ae4d8ba68c](https://linux-hardware.org/?probe=ae4d8ba68c) | Mar 18, 2023 |
| Toshiba       | Satellite C55-C             | [9d2c56bf69](https://linux-hardware.org/?probe=9d2c56bf69) | Mar 17, 2023 |
| TUXEDO        | Aura 15 Gen1                | [066f0cd17b](https://linux-hardware.org/?probe=066f0cd17b) | Mar 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [daa3d3869e](https://linux-hardware.org/?probe=daa3d3869e) | Mar 14, 2023 |
| Lenovo        | ThinkPad T430 23426QU       | [b588252431](https://linux-hardware.org/?probe=b588252431) | Mar 14, 2023 |
| Dell          | XPS 15 9520                 | [0f3b7bd317](https://linux-hardware.org/?probe=0f3b7bd317) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7f58d0d0a0](https://linux-hardware.org/?probe=7f58d0d0a0) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0c58b8ebad](https://linux-hardware.org/?probe=0c58b8ebad) | Mar 13, 2023 |
| Chuwi         | GemiBook Pro                | [fc04961aef](https://linux-hardware.org/?probe=fc04961aef) | Mar 11, 2023 |
| Dell          | Precision 7720              | [6132f690aa](https://linux-hardware.org/?probe=6132f690aa) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [8a33917a89](https://linux-hardware.org/?probe=8a33917a89) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [f4d71dcbd0](https://linux-hardware.org/?probe=f4d71dcbd0) | Mar 09, 2023 |
| Dell          | Precision 7720              | [e4a1149bcb](https://linux-hardware.org/?probe=e4a1149bcb) | Mar 08, 2023 |
| Timi          | TM1701                      | [3a94d06b73](https://linux-hardware.org/?probe=3a94d06b73) | Mar 07, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [54ad36532c](https://linux-hardware.org/?probe=54ad36532c) | Mar 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [314cad4a2f](https://linux-hardware.org/?probe=314cad4a2f) | Mar 07, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [be24c7e178](https://linux-hardware.org/?probe=be24c7e178) | Mar 07, 2023 |
| HP            | EliteBook 8460p             | [3519073f46](https://linux-hardware.org/?probe=3519073f46) | Mar 07, 2023 |
| Dell          | Latitude 5289               | [dcac5b8ebc](https://linux-hardware.org/?probe=dcac5b8ebc) | Mar 06, 2023 |
| Google        | Rammus                      | [0d905c6981](https://linux-hardware.org/?probe=0d905c6981) | Mar 05, 2023 |
| HP            | EliteBook 8570p             | [1ac55121cf](https://linux-hardware.org/?probe=1ac55121cf) | Mar 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [a4941ea70f](https://linux-hardware.org/?probe=a4941ea70f) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f27119aef2](https://linux-hardware.org/?probe=f27119aef2) | Mar 03, 2023 |
| HP            | EliteBook 8460p             | [83cb442ad5](https://linux-hardware.org/?probe=83cb442ad5) | Feb 27, 2023 |
| Lenovo        | Y50-70 20378                | [005749f4ef](https://linux-hardware.org/?probe=005749f4ef) | Feb 26, 2023 |
| Dell          | Inspiron N4010              | [612418b6e7](https://linux-hardware.org/?probe=612418b6e7) | Feb 25, 2023 |
| Medion        | Akoya E6412T                | [2915d1c409](https://linux-hardware.org/?probe=2915d1c409) | Feb 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [8a638dd3a7](https://linux-hardware.org/?probe=8a638dd3a7) | Feb 23, 2023 |
| ASUSTek       | X555LA                      | [e62c134a68](https://linux-hardware.org/?probe=e62c134a68) | Feb 22, 2023 |
| Apple         | MacBookPro14,1              | [f7f94aa827](https://linux-hardware.org/?probe=f7f94aa827) | Feb 22, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | [05ce3a9038](https://linux-hardware.org/?probe=05ce3a9038) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | [661017eb0b](https://linux-hardware.org/?probe=661017eb0b) | Feb 20, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [f55697d9b3](https://linux-hardware.org/?probe=f55697d9b3) | Feb 19, 2023 |
| ASUSTek       | S551LN                      | [ff5df2cf03](https://linux-hardware.org/?probe=ff5df2cf03) | Feb 19, 2023 |
| HUAWEI        | BOM-WXX9                    | [6234395029](https://linux-hardware.org/?probe=6234395029) | Feb 18, 2023 |
| Chuwi         | GemiBook Pro                | [7af4d238e8](https://linux-hardware.org/?probe=7af4d238e8) | Feb 18, 2023 |
| Google        | Helios                      | [4505c27d12](https://linux-hardware.org/?probe=4505c27d12) | Feb 16, 2023 |
| HP            | EliteBook 8460p             | [6c7f73c4a5](https://linux-hardware.org/?probe=6c7f73c4a5) | Feb 16, 2023 |
| GPD           | G1621-02                    | [5d584fa1cf](https://linux-hardware.org/?probe=5d584fa1cf) | Feb 14, 2023 |
| HP            | Laptop 15s-fq4xxx           | [9d1c8bca14](https://linux-hardware.org/?probe=9d1c8bca14) | Feb 13, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM    | [9e0e0bef82](https://linux-hardware.org/?probe=9e0e0bef82) | Feb 13, 2023 |
| Acer          | Aspire A515-54G             | [632c139c4b](https://linux-hardware.org/?probe=632c139c4b) | Feb 12, 2023 |
| HP            | Compaq 6820s                | [6c67866714](https://linux-hardware.org/?probe=6c67866714) | Feb 12, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [0c6da36f9d](https://linux-hardware.org/?probe=0c6da36f9d) | Feb 11, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [059d515c3c](https://linux-hardware.org/?probe=059d515c3c) | Feb 09, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [96d63ff41b](https://linux-hardware.org/?probe=96d63ff41b) | Feb 08, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2LN0... | [4fdb5d662c](https://linux-hardware.org/?probe=4fdb5d662c) | Feb 08, 2023 |
| HP            | ZBook 15 G4                 | [f2a6af1f7e](https://linux-hardware.org/?probe=f2a6af1f7e) | Feb 06, 2023 |
| HP            | Setzer                      | [bd65b300ae](https://linux-hardware.org/?probe=bd65b300ae) | Feb 06, 2023 |
| HP            | ZBook 15 G4                 | [e523dbd162](https://linux-hardware.org/?probe=e523dbd162) | Feb 02, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [bcaa2e6b1a](https://linux-hardware.org/?probe=bcaa2e6b1a) | Jan 30, 2023 |
| Dell          | Latitude 5400               | [80651273e4](https://linux-hardware.org/?probe=80651273e4) | Jan 29, 2023 |
| Dell          | Latitude 5400               | [eb97e73f08](https://linux-hardware.org/?probe=eb97e73f08) | Jan 29, 2023 |
| HP            | Laptop 15s-eq2xxx           | [096eede9c5](https://linux-hardware.org/?probe=096eede9c5) | Jan 28, 2023 |
| HP            | ZBook 15 G4                 | [3e957e185d](https://linux-hardware.org/?probe=3e957e185d) | Jan 28, 2023 |
| HP            | ZBook 15 G4                 | [849d901314](https://linux-hardware.org/?probe=849d901314) | Jan 28, 2023 |
| Toshiba       | Satellite L755              | [b15899ef80](https://linux-hardware.org/?probe=b15899ef80) | Jan 27, 2023 |
| Toshiba       | Satellite L755              | [357a0cd22d](https://linux-hardware.org/?probe=357a0cd22d) | Jan 27, 2023 |
| HUAWEI        | KLVC-WXX9                   | [8fa82c8684](https://linux-hardware.org/?probe=8fa82c8684) | Jan 26, 2023 |
| Dell          | Latitude E5410              | [22df8731a9](https://linux-hardware.org/?probe=22df8731a9) | Jan 26, 2023 |
| Google        | Magpie                      | [34506f260e](https://linux-hardware.org/?probe=34506f260e) | Jan 26, 2023 |
| HP            | Laptop 15s-eq2xxx           | [cb29f724a0](https://linux-hardware.org/?probe=cb29f724a0) | Jan 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ec369b35a4](https://linux-hardware.org/?probe=ec369b35a4) | Jan 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [56a9b7ad32](https://linux-hardware.org/?probe=56a9b7ad32) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [be73748546](https://linux-hardware.org/?probe=be73748546) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [7595deef91](https://linux-hardware.org/?probe=7595deef91) | Jan 24, 2023 |
| Dell          | XPS 13 9343                 | [f371c1c8b6](https://linux-hardware.org/?probe=f371c1c8b6) | Jan 23, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [76955052a7](https://linux-hardware.org/?probe=76955052a7) | Jan 22, 2023 |
| Acer          | Aspire E5-575G              | [1153793fd9](https://linux-hardware.org/?probe=1153793fd9) | Jan 22, 2023 |
| ASUSTek       | GL753VE                     | [10796ad8f6](https://linux-hardware.org/?probe=10796ad8f6) | Jan 21, 2023 |
| Positivo      | S14BW01                     | [241b637096](https://linux-hardware.org/?probe=241b637096) | Jan 21, 2023 |
| Positivo      | S14BW01                     | [c818b70b5b](https://linux-hardware.org/?probe=c818b70b5b) | Jan 21, 2023 |
| HP            | Laptop 15s-eq2xxx           | [bbc2c32eee](https://linux-hardware.org/?probe=bbc2c32eee) | Jan 19, 2023 |
| HP            | Pavilion x2 Detachable      | [8a13d31503](https://linux-hardware.org/?probe=8a13d31503) | Jan 19, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [3967a4560b](https://linux-hardware.org/?probe=3967a4560b) | Jan 15, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | [8b1ccef51d](https://linux-hardware.org/?probe=8b1ccef51d) | Jan 15, 2023 |
| Acer          | Aspire E5-575G              | [1681bdc38e](https://linux-hardware.org/?probe=1681bdc38e) | Jan 14, 2023 |
| Dell          | Precision M4800             | [c5deb205c7](https://linux-hardware.org/?probe=c5deb205c7) | Jan 14, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c82f19c656](https://linux-hardware.org/?probe=c82f19c656) | Jan 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [cef6a9db45](https://linux-hardware.org/?probe=cef6a9db45) | Jan 05, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [8defa5d641](https://linux-hardware.org/?probe=8defa5d641) | Jan 05, 2023 |
| Dell          | XPS 9320                    | [8684c6d86b](https://linux-hardware.org/?probe=8684c6d86b) | Jan 04, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [be6730b67b](https://linux-hardware.org/?probe=be6730b67b) | Jan 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [bc57a904f7](https://linux-hardware.org/?probe=bc57a904f7) | Jan 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1be42c9032](https://linux-hardware.org/?probe=1be42c9032) | Jan 02, 2023 |
| Toshiba       | EQUIUM A100                 | [424904034a](https://linux-hardware.org/?probe=424904034a) | Jan 01, 2023 |
| MSI           | Modern 15 A5M               | [e0cb4d278d](https://linux-hardware.org/?probe=e0cb4d278d) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ce45aaceaf](https://linux-hardware.org/?probe=ce45aaceaf) | Dec 29, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [bb1b612416](https://linux-hardware.org/?probe=bb1b612416) | Dec 29, 2022 |
| Acer          | Swift SFX14-41G             | [e422b934d0](https://linux-hardware.org/?probe=e422b934d0) | Dec 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [b8099c7a94](https://linux-hardware.org/?probe=b8099c7a94) | Dec 28, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [0f15c0b801](https://linux-hardware.org/?probe=0f15c0b801) | Dec 28, 2022 |
| HP            | EliteBook 845 14 inch G9... | [475b76e98a](https://linux-hardware.org/?probe=475b76e98a) | Dec 28, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [098390e03e](https://linux-hardware.org/?probe=098390e03e) | Dec 25, 2022 |
| Lenovo        | ThinkPad X230 2324KP1       | [628adc89bf](https://linux-hardware.org/?probe=628adc89bf) | Dec 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [244ad65a78](https://linux-hardware.org/?probe=244ad65a78) | Dec 24, 2022 |
| HP            | ProBook 450 G7              | [f47d3ce638](https://linux-hardware.org/?probe=f47d3ce638) | Dec 24, 2022 |
| Sony          | VGN-FW11E                   | [2d57afaa38](https://linux-hardware.org/?probe=2d57afaa38) | Dec 19, 2022 |
| HP            | 15                          | [cce5eb4078](https://linux-hardware.org/?probe=cce5eb4078) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [54e81a596c](https://linux-hardware.org/?probe=54e81a596c) | Dec 18, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [0a486ca67b](https://linux-hardware.org/?probe=0a486ca67b) | Dec 18, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [8c87fc340b](https://linux-hardware.org/?probe=8c87fc340b) | Dec 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [57ecebdc0f](https://linux-hardware.org/?probe=57ecebdc0f) | Dec 15, 2022 |
| PC Special... | Elimina Iv 17               | [66a5d6dd6a](https://linux-hardware.org/?probe=66a5d6dd6a) | Dec 13, 2022 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [2a1d9a153b](https://linux-hardware.org/?probe=2a1d9a153b) | Dec 11, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [6ae6d710b7](https://linux-hardware.org/?probe=6ae6d710b7) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [b56f450d6d](https://linux-hardware.org/?probe=b56f450d6d) | Dec 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [de42f36422](https://linux-hardware.org/?probe=de42f36422) | Dec 10, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [ebf5cc9d6e](https://linux-hardware.org/?probe=ebf5cc9d6e) | Dec 06, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [a4bdd8b19d](https://linux-hardware.org/?probe=a4bdd8b19d) | Dec 05, 2022 |
| MSI           | GS75 Stealth 8SG            | [8741c9175e](https://linux-hardware.org/?probe=8741c9175e) | Dec 02, 2022 |
| MSI           | GS75 Stealth 8SG            | [c3b6dada9d](https://linux-hardware.org/?probe=c3b6dada9d) | Dec 02, 2022 |
| MSI           | GS75 Stealth 8SG            | [70be467762](https://linux-hardware.org/?probe=70be467762) | Dec 01, 2022 |
| Dell          | Inspiron 15-3567            | [eff3d877bc](https://linux-hardware.org/?probe=eff3d877bc) | Nov 30, 2022 |
| HP            | ENVY 17                     | [4a784f4642](https://linux-hardware.org/?probe=4a784f4642) | Nov 27, 2022 |
| Acer          | Aspire A517-52              | [3ce1a2c42a](https://linux-hardware.org/?probe=3ce1a2c42a) | Nov 27, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [4e7809f7f6](https://linux-hardware.org/?probe=4e7809f7f6) | Nov 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [123efdf4df](https://linux-hardware.org/?probe=123efdf4df) | Nov 26, 2022 |
| Dell          | Inspiron 15-3567            | [f05943013c](https://linux-hardware.org/?probe=f05943013c) | Nov 25, 2022 |
| Lenovo        | ThinkPad T440s 20ARA12UM... | [5e1b88160e](https://linux-hardware.org/?probe=5e1b88160e) | Nov 25, 2022 |
| Acer          | TravelMate 5730             | [0200afcfb3](https://linux-hardware.org/?probe=0200afcfb3) | Nov 24, 2022 |
| Acer          | TravelMate 5730             | [077cd77583](https://linux-hardware.org/?probe=077cd77583) | Nov 24, 2022 |
| MSI           | Modern 14 B5M               | [18b7141401](https://linux-hardware.org/?probe=18b7141401) | Nov 22, 2022 |
| Dell          | Inspiron 15-3567            | [415fd12650](https://linux-hardware.org/?probe=415fd12650) | Nov 22, 2022 |
| Dell          | Inspiron 15-3567            | [aca01ed633](https://linux-hardware.org/?probe=aca01ed633) | Nov 21, 2022 |
| HP            | 15                          | [ab7c1e3bfd](https://linux-hardware.org/?probe=ab7c1e3bfd) | Nov 21, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [8e7aa30e4e](https://linux-hardware.org/?probe=8e7aa30e4e) | Nov 19, 2022 |
| HP            | EliteBook 840 G2            | [6c896ef17e](https://linux-hardware.org/?probe=6c896ef17e) | Nov 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0b0d1f6427](https://linux-hardware.org/?probe=0b0d1f6427) | Nov 19, 2022 |
| Apple         | MacBookPro16,2              | [8c63644200](https://linux-hardware.org/?probe=8c63644200) | Nov 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [7aeba8b69a](https://linux-hardware.org/?probe=7aeba8b69a) | Nov 10, 2022 |
| Acer          | Aspire A315-22              | [cde0b24cde](https://linux-hardware.org/?probe=cde0b24cde) | Nov 10, 2022 |
| Lenovo        | ThinkPad X250 20CLS3AJ00    | [ec16a4b3c5](https://linux-hardware.org/?probe=ec16a4b3c5) | Nov 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fba0c1a99c](https://linux-hardware.org/?probe=fba0c1a99c) | Nov 09, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [0527a7a983](https://linux-hardware.org/?probe=0527a7a983) | Nov 07, 2022 |
| Lenovo        | ThinkPad T520 42406AG       | [1038487513](https://linux-hardware.org/?probe=1038487513) | Nov 06, 2022 |
| Timi          | RedmiBook Pro 15            | [226d8de9bb](https://linux-hardware.org/?probe=226d8de9bb) | Nov 04, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [08a8e0079a](https://linux-hardware.org/?probe=08a8e0079a) | Nov 03, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0235661dbe](https://linux-hardware.org/?probe=0235661dbe) | Nov 03, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU    | [9e1b981f01](https://linux-hardware.org/?probe=9e1b981f01) | Nov 03, 2022 |
| MSI           | Prestige 15 A11SCX          | [973b498b3f](https://linux-hardware.org/?probe=973b498b3f) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [690e088c8e](https://linux-hardware.org/?probe=690e088c8e) | Nov 02, 2022 |
| Lenovo        | ThinkPad T480 20L6S3H108    | [1ed803ae94](https://linux-hardware.org/?probe=1ed803ae94) | Nov 01, 2022 |
| Apple         | MacBookPro16,1              | [025e3e7e4e](https://linux-hardware.org/?probe=025e3e7e4e) | Nov 01, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [bd9909fff8](https://linux-hardware.org/?probe=bd9909fff8) | Oct 30, 2022 |
| MSI           | Prestige 14Evo A12M         | [5e32f7b38b](https://linux-hardware.org/?probe=5e32f7b38b) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [ed6d5efa84](https://linux-hardware.org/?probe=ed6d5efa84) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [6263763f01](https://linux-hardware.org/?probe=6263763f01) | Oct 27, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [264d164669](https://linux-hardware.org/?probe=264d164669) | Oct 27, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [7e1a95e569](https://linux-hardware.org/?probe=7e1a95e569) | Oct 26, 2022 |
| Acer          | Extensa 2540                | [367660309f](https://linux-hardware.org/?probe=367660309f) | Oct 26, 2022 |
| HP            | 650                         | [d7b73bebc7](https://linux-hardware.org/?probe=d7b73bebc7) | Oct 25, 2022 |
| HP            | 340S G7 Notebook PC         | [95707c7cd5](https://linux-hardware.org/?probe=95707c7cd5) | Oct 25, 2022 |
| Timi          | RedmiBook Pro 14S           | [f81e674faf](https://linux-hardware.org/?probe=f81e674faf) | Oct 21, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [d6275970a0](https://linux-hardware.org/?probe=d6275970a0) | Oct 21, 2022 |
| HP            | Laptop 15-bs2xx             | [0fd75382e9](https://linux-hardware.org/?probe=0fd75382e9) | Oct 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [facb462239](https://linux-hardware.org/?probe=facb462239) | Oct 20, 2022 |
| MSI           | GE75 Raider 10SF            | [dd4102e2e7](https://linux-hardware.org/?probe=dd4102e2e7) | Oct 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [5e31cc470c](https://linux-hardware.org/?probe=5e31cc470c) | Oct 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [00fece9d77](https://linux-hardware.org/?probe=00fece9d77) | Oct 18, 2022 |
| ASUSTek       | X441SA                      | [31e3f95d58](https://linux-hardware.org/?probe=31e3f95d58) | Oct 18, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [0e827df91b](https://linux-hardware.org/?probe=0e827df91b) | Oct 18, 2022 |
| Google        | Liara                       | [8e2b131f8f](https://linux-hardware.org/?probe=8e2b131f8f) | Oct 14, 2022 |
| HP            | 340S G7 Notebook PC         | [1927ae6949](https://linux-hardware.org/?probe=1927ae6949) | Oct 12, 2022 |
| Lenovo        | V110-15AST 80TD             | [9d4b6fafb6](https://linux-hardware.org/?probe=9d4b6fafb6) | Oct 12, 2022 |
| ASUSTek       | S550CA                      | [261f171b10](https://linux-hardware.org/?probe=261f171b10) | Oct 12, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [930887578f](https://linux-hardware.org/?probe=930887578f) | Oct 11, 2022 |
| Acer          | Aspire A315-22              | [07870a3cde](https://linux-hardware.org/?probe=07870a3cde) | Oct 11, 2022 |
| Acer          | Swift SF314-51              | [cfc56878f0](https://linux-hardware.org/?probe=cfc56878f0) | Oct 07, 2022 |
| Toshiba       | Satellite L500              | [90c1d12ca3](https://linux-hardware.org/?probe=90c1d12ca3) | Oct 07, 2022 |
| Packard Be... | EasyNote TJ65               | [bb815f037b](https://linux-hardware.org/?probe=bb815f037b) | Oct 06, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [986a405690](https://linux-hardware.org/?probe=986a405690) | Oct 06, 2022 |
| HP            | 250 G4                      | [7c892fab7a](https://linux-hardware.org/?probe=7c892fab7a) | Oct 03, 2022 |
| HP            | 255 G8 Notebook PC          | [1a2e047ca1](https://linux-hardware.org/?probe=1a2e047ca1) | Oct 03, 2022 |
| MSI           | GF65 Thin 9SD               | [a761de487d](https://linux-hardware.org/?probe=a761de487d) | Oct 01, 2022 |
| HP            | Laptop 15-da0xxx            | [176695aa20](https://linux-hardware.org/?probe=176695aa20) | Sep 30, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [d547ed6f83](https://linux-hardware.org/?probe=d547ed6f83) | Sep 30, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [9781419cc1](https://linux-hardware.org/?probe=9781419cc1) | Sep 30, 2022 |
| MSI           | Modern 14 B5M               | [1914cf579b](https://linux-hardware.org/?probe=1914cf579b) | Sep 29, 2022 |
| ASUSTek       | GL753VE                     | [456ff5f9a7](https://linux-hardware.org/?probe=456ff5f9a7) | Sep 29, 2022 |
| HP            | EliteBook 745 G6            | [f9eecf6781](https://linux-hardware.org/?probe=f9eecf6781) | Sep 28, 2022 |
| HP            | Pavilion Laptop 15-eg2xx... | [658f9b891f](https://linux-hardware.org/?probe=658f9b891f) | Sep 27, 2022 |
| Apple         | MacBookPro8,1               | [c0d2617a28](https://linux-hardware.org/?probe=c0d2617a28) | Sep 27, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [28631c9681](https://linux-hardware.org/?probe=28631c9681) | Sep 27, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | [2b3c66f0ee](https://linux-hardware.org/?probe=2b3c66f0ee) | Sep 24, 2022 |
| HP            | 250 G4                      | [5d4c56fe14](https://linux-hardware.org/?probe=5d4c56fe14) | Sep 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8e7a7a914c](https://linux-hardware.org/?probe=8e7a7a914c) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [031f4bb4f1](https://linux-hardware.org/?probe=031f4bb4f1) | Sep 23, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [d852d9e0dd](https://linux-hardware.org/?probe=d852d9e0dd) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [6f43da7fb4](https://linux-hardware.org/?probe=6f43da7fb4) | Sep 22, 2022 |
| ASUSTek       | GL553VD                     | [e6cb381fd2](https://linux-hardware.org/?probe=e6cb381fd2) | Sep 21, 2022 |
| ASUSTek       | G74Sx                       | [e8f0a018c9](https://linux-hardware.org/?probe=e8f0a018c9) | Sep 19, 2022 |
| Acer          | Aspire A515-41G             | [434b1869d7](https://linux-hardware.org/?probe=434b1869d7) | Sep 16, 2022 |
| MSI           | Summit E13FlipEvo A12MT     | [465e8d2c86](https://linux-hardware.org/?probe=465e8d2c86) | Sep 15, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [13cd2039a1](https://linux-hardware.org/?probe=13cd2039a1) | Sep 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S58700    | [9d9d51e924](https://linux-hardware.org/?probe=9d9d51e924) | Sep 14, 2022 |
| Acer          | Aspire A715-72G             | [60cbc2fb39](https://linux-hardware.org/?probe=60cbc2fb39) | Sep 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | [98ae2af06f](https://linux-hardware.org/?probe=98ae2af06f) | Sep 14, 2022 |
| Gigabyte      | AORUS 15G XC                | [4b0e97e947](https://linux-hardware.org/?probe=4b0e97e947) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [fcf2ccb1d2](https://linux-hardware.org/?probe=fcf2ccb1d2) | Sep 12, 2022 |
| MSI           | Alpha 15 B5EEK              | [cf9447ce8c](https://linux-hardware.org/?probe=cf9447ce8c) | Sep 10, 2022 |
| Acer          | Aspire A315-22              | [82058771f7](https://linux-hardware.org/?probe=82058771f7) | Sep 09, 2022 |
| Timi          | TM1703                      | [5c30ece6ff](https://linux-hardware.org/?probe=5c30ece6ff) | Sep 08, 2022 |
| HP            | ProBook 450 G0              | [07dfc865cf](https://linux-hardware.org/?probe=07dfc865cf) | Sep 08, 2022 |
| Acer          | Aspire A315-22              | [49d54ac5c5](https://linux-hardware.org/?probe=49d54ac5c5) | Sep 07, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [cc40453955](https://linux-hardware.org/?probe=cc40453955) | Sep 06, 2022 |
| Timi          | TM1703                      | [fb7386017f](https://linux-hardware.org/?probe=fb7386017f) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [dd3b771e55](https://linux-hardware.org/?probe=dd3b771e55) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [e8887916fa](https://linux-hardware.org/?probe=e8887916fa) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | [a75fed8b3f](https://linux-hardware.org/?probe=a75fed8b3f) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | [cd613ebcd2](https://linux-hardware.org/?probe=cd613ebcd2) | Sep 05, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | [6ce8accfb1](https://linux-hardware.org/?probe=6ce8accfb1) | Sep 04, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [0e4f12b377](https://linux-hardware.org/?probe=0e4f12b377) | Sep 04, 2022 |
| Lenovo        | ThinkPad X200T 7449G6G      | [2667cd1609](https://linux-hardware.org/?probe=2667cd1609) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [05221c6c18](https://linux-hardware.org/?probe=05221c6c18) | Sep 03, 2022 |
| ASUSTek       | X580VN                      | [fe8f1a7e6f](https://linux-hardware.org/?probe=fe8f1a7e6f) | Sep 03, 2022 |
| HP            | OMEN by Laptop 16z-c000     | [edc4a4ce85](https://linux-hardware.org/?probe=edc4a4ce85) | Sep 03, 2022 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | [3a8cfc8781](https://linux-hardware.org/?probe=3a8cfc8781) | Sep 01, 2022 |
| HP            | OMEN by Laptop 16-b0xxx     | [94b00f5da5](https://linux-hardware.org/?probe=94b00f5da5) | Aug 27, 2022 |
| Google        | Peppy                       | [be4ecba4dc](https://linux-hardware.org/?probe=be4ecba4dc) | Aug 26, 2022 |
| Google        | Auron_Yuna                  | [de2984c01a](https://linux-hardware.org/?probe=de2984c01a) | Aug 26, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [788397e7ae](https://linux-hardware.org/?probe=788397e7ae) | Aug 22, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [6eadd1ec75](https://linux-hardware.org/?probe=6eadd1ec75) | Aug 17, 2022 |
| HUAWEI        | KLVL-WXX9                   | [b74ab22c1f](https://linux-hardware.org/?probe=b74ab22c1f) | Aug 16, 2022 |
| HP            | Elite x2 1012 G1            | [94fb37c745](https://linux-hardware.org/?probe=94fb37c745) | Aug 14, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [b391d570ba](https://linux-hardware.org/?probe=b391d570ba) | Aug 12, 2022 |
| Apple         | MacBookPro14,2              | [9e297d5dde](https://linux-hardware.org/?probe=9e297d5dde) | Aug 11, 2022 |
| ASUSTek       | GL502VT                     | [5e95e514a4](https://linux-hardware.org/?probe=5e95e514a4) | Aug 11, 2022 |
| HP            | Elite x2 1012 G1            | [a76e460266](https://linux-hardware.org/?probe=a76e460266) | Aug 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [d76760ffa4](https://linux-hardware.org/?probe=d76760ffa4) | Aug 11, 2022 |
| Dell          | Inspiron 5402               | [5373247b06](https://linux-hardware.org/?probe=5373247b06) | Aug 05, 2022 |
| Apple         | MacBookPro14,2              | [d1079f3fba](https://linux-hardware.org/?probe=d1079f3fba) | Aug 04, 2022 |
| Positivo      | S14BW01                     | [28c70dfa85](https://linux-hardware.org/?probe=28c70dfa85) | Aug 04, 2022 |
| HP            | EliteBook 745 G6            | [0bcc9863e3](https://linux-hardware.org/?probe=0bcc9863e3) | Jul 31, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [b41ce610a4](https://linux-hardware.org/?probe=b41ce610a4) | Jul 22, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [dca2e009f0](https://linux-hardware.org/?probe=dca2e009f0) | Jul 20, 2022 |
| Acer          | Nitro AN515-43              | [4e33f5e902](https://linux-hardware.org/?probe=4e33f5e902) | Jul 19, 2022 |
| Lenovo        | ThinkPad T460p 20FXS0550... | [1a394fdf59](https://linux-hardware.org/?probe=1a394fdf59) | Jul 18, 2022 |
| Lenovo        | ThinkPad E595 20NF001HGE    | [9d3a54dbcf](https://linux-hardware.org/?probe=9d3a54dbcf) | Jul 17, 2022 |
| ASUSTek       | GL753VE                     | [df383e16e9](https://linux-hardware.org/?probe=df383e16e9) | Jul 07, 2022 |
| HP            | Laptop 14-fq1xxx            | [9aa0a38b17](https://linux-hardware.org/?probe=9aa0a38b17) | Jul 01, 2022 |
| HP            | Laptop 14-fq1xxx            | [b9b09609b8](https://linux-hardware.org/?probe=b9b09609b8) | Jul 01, 2022 |
| HUAWEI        | MACH-WX9                    | [329e3a150f](https://linux-hardware.org/?probe=329e3a150f) | Jun 30, 2022 |
| HONOR         | BBR-WAX9                    | [0cffb17bc7](https://linux-hardware.org/?probe=0cffb17bc7) | Jun 25, 2022 |
| Lenovo        | V330-14ARR 81B1             | [9816b1d616](https://linux-hardware.org/?probe=9816b1d616) | Jun 23, 2022 |
| Acer          | Aspire E5-575G              | [dc04d6eb1a](https://linux-hardware.org/?probe=dc04d6eb1a) | Jun 18, 2022 |
| ASUSTek       | N56VB                       | [a87c22baee](https://linux-hardware.org/?probe=a87c22baee) | Jun 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | [999d96890c](https://linux-hardware.org/?probe=999d96890c) | Jun 16, 2022 |
| Dell          | Latitude XT                 | [6ca0e5ca92](https://linux-hardware.org/?probe=6ca0e5ca92) | Jun 14, 2022 |
| Dell          | Latitude E6440              | [63238f8fe9](https://linux-hardware.org/?probe=63238f8fe9) | Jun 09, 2022 |
| Acer          | Aspire A515-43              | [343315ec17](https://linux-hardware.org/?probe=343315ec17) | Jun 06, 2022 |
| ASUSTek       | GL753VE                     | [a96aa73dd6](https://linux-hardware.org/?probe=a96aa73dd6) | Jun 01, 2022 |
| Dell          | Latitude 5289               | [f9e3e0fa57](https://linux-hardware.org/?probe=f9e3e0fa57) | May 30, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [53dc0937af](https://linux-hardware.org/?probe=53dc0937af) | May 26, 2022 |
| Sony          | VPCCA17FX                   | [4ced9d5222](https://linux-hardware.org/?probe=4ced9d5222) | May 26, 2022 |
| Dell          | Latitude E6510              | [52b94e68a9](https://linux-hardware.org/?probe=52b94e68a9) | May 23, 2022 |
| Timi          | A35S                        | [8278281113](https://linux-hardware.org/?probe=8278281113) | May 20, 2022 |
| Lenovo        | ThinkPad X270 20HMS12K00    | [c4e15012d5](https://linux-hardware.org/?probe=c4e15012d5) | May 15, 2022 |
| Dell          | Inspiron 3580               | [33dbac4352](https://linux-hardware.org/?probe=33dbac4352) | May 15, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [5dea5cd6ff](https://linux-hardware.org/?probe=5dea5cd6ff) | May 14, 2022 |
| HP            | Notebook                    | [e672632acf](https://linux-hardware.org/?probe=e672632acf) | May 13, 2022 |
| Unknown       | Unknown                     | [fac14402be](https://linux-hardware.org/?probe=fac14402be) | May 11, 2022 |
| Acer          | Nitro AN515-45              | [34272a60d1](https://linux-hardware.org/?probe=34272a60d1) | May 10, 2022 |
| HP            | ProBook 440 G4              | [1f0811673a](https://linux-hardware.org/?probe=1f0811673a) | May 09, 2022 |
| Chuwi         | GemiBook Pro                | [b5145fe094](https://linux-hardware.org/?probe=b5145fe094) | May 08, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | [6a3cbcae26](https://linux-hardware.org/?probe=6a3cbcae26) | May 06, 2022 |
| Acer          | Swift SF314-41              | [3dbf93ec7f](https://linux-hardware.org/?probe=3dbf93ec7f) | May 06, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [c08f733706](https://linux-hardware.org/?probe=c08f733706) | May 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [5838cd4268](https://linux-hardware.org/?probe=5838cd4268) | Apr 30, 2022 |
| ASUSTek       | X71Vn                       | [b31a7dce8b](https://linux-hardware.org/?probe=b31a7dce8b) | Apr 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [af3efcde26](https://linux-hardware.org/?probe=af3efcde26) | Apr 29, 2022 |
| HUAWEI        | MACH-WX9                    | [0199a1bcec](https://linux-hardware.org/?probe=0199a1bcec) | Apr 24, 2022 |
| Dell          | Latitude 7280               | [e64ba65609](https://linux-hardware.org/?probe=e64ba65609) | Apr 22, 2022 |
| Google        | Celes                       | [a1a2262b88](https://linux-hardware.org/?probe=a1a2262b88) | Apr 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | [5a58c1f799](https://linux-hardware.org/?probe=5a58c1f799) | Apr 18, 2022 |
| ASUSTek       | Zephyrus M GU502GV_GU502... | [10a97e42a3](https://linux-hardware.org/?probe=10a97e42a3) | Apr 17, 2022 |
| Google        | Candy                       | [77b6731597](https://linux-hardware.org/?probe=77b6731597) | Apr 17, 2022 |
| HP            | 250 G7 Notebook PC          | [2b3ac63766](https://linux-hardware.org/?probe=2b3ac63766) | Apr 16, 2022 |
| HP            | Laptop 14-dq4xxx            | [a892a2412c](https://linux-hardware.org/?probe=a892a2412c) | Apr 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [8350598ef6](https://linux-hardware.org/?probe=8350598ef6) | Apr 15, 2022 |
| Dell          | Latitude E6540              | [939dbc38d3](https://linux-hardware.org/?probe=939dbc38d3) | Apr 15, 2022 |
| HP            | Pavilion Notebook           | [8ea3af9aca](https://linux-hardware.org/?probe=8ea3af9aca) | Apr 14, 2022 |
| HP            | Pavilion Notebook           | [e2a600db96](https://linux-hardware.org/?probe=e2a600db96) | Apr 14, 2022 |
| Acer          | Swift SF314-57G             | [b9b31b0528](https://linux-hardware.org/?probe=b9b31b0528) | Apr 14, 2022 |
| Dell          | XPS 15 7590                 | [d90283da2d](https://linux-hardware.org/?probe=d90283da2d) | Apr 13, 2022 |
| MSI           | Modern 15 A11M              | [c3202f68fc](https://linux-hardware.org/?probe=c3202f68fc) | Apr 13, 2022 |
| ILLEGEAR      | ROGUE                       | [441caeb4e6](https://linux-hardware.org/?probe=441caeb4e6) | Apr 12, 2022 |
| Packard Be... | EasyNote ENTG71BM           | [44520b705b](https://linux-hardware.org/?probe=44520b705b) | Apr 11, 2022 |
| TrekStor      | Notebook Slim S130          | [febbb5b9a2](https://linux-hardware.org/?probe=febbb5b9a2) | Apr 06, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [3327822265](https://linux-hardware.org/?probe=3327822265) | Apr 06, 2022 |
| HP            | 250 G7 Notebook PC          | [9170392920](https://linux-hardware.org/?probe=9170392920) | Apr 04, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [376167460b](https://linux-hardware.org/?probe=376167460b) | Apr 01, 2022 |
| ASUSTek       | X555LF                      | [35cceb0f0a](https://linux-hardware.org/?probe=35cceb0f0a) | Mar 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [d895af2b46](https://linux-hardware.org/?probe=d895af2b46) | Mar 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [ee491ed7f4](https://linux-hardware.org/?probe=ee491ed7f4) | Mar 29, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [921004463e](https://linux-hardware.org/?probe=921004463e) | Mar 23, 2022 |
| HP            | Laptop 15-bw0xx             | [3500cd92bf](https://linux-hardware.org/?probe=3500cd92bf) | Mar 19, 2022 |
| Acer          | Extensa 2520                | [f070f33060](https://linux-hardware.org/?probe=f070f33060) | Mar 19, 2022 |
| Acer          | Extensa 2520                | [f2003c1f90](https://linux-hardware.org/?probe=f2003c1f90) | Mar 19, 2022 |
| ASUSTek       | G752VT                      | [632814d6a3](https://linux-hardware.org/?probe=632814d6a3) | Mar 18, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [7e64ef177c](https://linux-hardware.org/?probe=7e64ef177c) | Mar 18, 2022 |
| Lenovo        | V330-14IKB 81B0             | [06a3e2150b](https://linux-hardware.org/?probe=06a3e2150b) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | [73e48f6dc4](https://linux-hardware.org/?probe=73e48f6dc4) | Mar 16, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [d742a1c2fa](https://linux-hardware.org/?probe=d742a1c2fa) | Mar 16, 2022 |
| Toshiba       | Satellite Pro C50-A-1E6     | [ad8e612da5](https://linux-hardware.org/?probe=ad8e612da5) | Mar 15, 2022 |
| Google        | Akemi                       | [6a52c103e9](https://linux-hardware.org/?probe=6a52c103e9) | Mar 14, 2022 |
| Dell          | Precision M6800             | [239dd5797a](https://linux-hardware.org/?probe=239dd5797a) | Mar 10, 2022 |
| ASUSTek       | G751JT                      | [32556e3c15](https://linux-hardware.org/?probe=32556e3c15) | Mar 09, 2022 |
| Unknown       | Unknown                     | [23c7cd9c12](https://linux-hardware.org/?probe=23c7cd9c12) | Mar 09, 2022 |
| Acer          | Aspire E5-575               | [bc5e48379d](https://linux-hardware.org/?probe=bc5e48379d) | Mar 07, 2022 |
| Lenovo        | ThinkPad Edge 0578BBA       | [cf314fb57a](https://linux-hardware.org/?probe=cf314fb57a) | Mar 07, 2022 |
| Dell          | Latitude E5430 non-vPro     | [2d2bd57c8b](https://linux-hardware.org/?probe=2d2bd57c8b) | Mar 06, 2022 |
| HP            | ZBook 17 G2                 | [d9773ef48d](https://linux-hardware.org/?probe=d9773ef48d) | Mar 06, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [d3cc5d36be](https://linux-hardware.org/?probe=d3cc5d36be) | Feb 27, 2022 |
| Eluktronic... | Prometheus XVII             | [0797cebf2d](https://linux-hardware.org/?probe=0797cebf2d) | Feb 26, 2022 |
| Dell          | Latitude 3420               | [fb586744c3](https://linux-hardware.org/?probe=fb586744c3) | Feb 22, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [655c17b9ff](https://linux-hardware.org/?probe=655c17b9ff) | Feb 20, 2022 |
| Radxa         | ROCK Pi X v1.4              | [dd6d9dc630](https://linux-hardware.org/?probe=dd6d9dc630) | Feb 19, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [973e1c8d91](https://linux-hardware.org/?probe=973e1c8d91) | Feb 19, 2022 |
| Acer          | Aspire E1-572G              | [c75a02af0d](https://linux-hardware.org/?probe=c75a02af0d) | Feb 18, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [d98a594e28](https://linux-hardware.org/?probe=d98a594e28) | Feb 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0U50... | [a114b7030f](https://linux-hardware.org/?probe=a114b7030f) | Feb 17, 2022 |
| Eluktronic... | Prometheus XVII             | [36436d1aff](https://linux-hardware.org/?probe=36436d1aff) | Feb 17, 2022 |
| HUAWEI        | HLYL-WXX9                   | [5c8d71134e](https://linux-hardware.org/?probe=5c8d71134e) | Feb 16, 2022 |
| ASUSTek       | UX490UA                     | [5e40078555](https://linux-hardware.org/?probe=5e40078555) | Feb 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [2afbdea066](https://linux-hardware.org/?probe=2afbdea066) | Feb 13, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [f84892675f](https://linux-hardware.org/?probe=f84892675f) | Feb 12, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [dda932e1ae](https://linux-hardware.org/?probe=dda932e1ae) | Feb 11, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [c79fe1743d](https://linux-hardware.org/?probe=c79fe1743d) | Feb 10, 2022 |
| Dell          | G3 3500                     | [92ee625013](https://linux-hardware.org/?probe=92ee625013) | Feb 09, 2022 |
| HP            | Pavilion 10 TS              | [1228be8404](https://linux-hardware.org/?probe=1228be8404) | Feb 08, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [f2719a9d26](https://linux-hardware.org/?probe=f2719a9d26) | Feb 07, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [a39c608f4c](https://linux-hardware.org/?probe=a39c608f4c) | Feb 07, 2022 |
| Dell          | Latitude E4310              | [ef92697af7](https://linux-hardware.org/?probe=ef92697af7) | Feb 07, 2022 |
| Dell          | Latitude E6400              | [919eb44cc5](https://linux-hardware.org/?probe=919eb44cc5) | Feb 07, 2022 |
| Acer          | Aspire V5-471               | [9bbd70f06c](https://linux-hardware.org/?probe=9bbd70f06c) | Feb 06, 2022 |
| HP            | Pavilion dv7                | [28bb1241de](https://linux-hardware.org/?probe=28bb1241de) | Feb 06, 2022 |
| Notebook      | NH5x_7xDPx                  | [a43204a8d7](https://linux-hardware.org/?probe=a43204a8d7) | Feb 02, 2022 |
| HUAWEI        | MACH-WX9                    | [4998bf6630](https://linux-hardware.org/?probe=4998bf6630) | Feb 02, 2022 |
| HP            | Pavilion g6                 | [c2b7d7cdd1](https://linux-hardware.org/?probe=c2b7d7cdd1) | Feb 02, 2022 |
| Acer          | Aspire E1-572G              | [3deec16346](https://linux-hardware.org/?probe=3deec16346) | Feb 02, 2022 |
| HP            | 250 G7 Notebook PC          | [b8f0614b9c](https://linux-hardware.org/?probe=b8f0614b9c) | Feb 01, 2022 |
| HP            | Pavilion g6                 | [be25fc4f46](https://linux-hardware.org/?probe=be25fc4f46) | Feb 01, 2022 |
| Lenovo        | Yoga 700-14ISK 80QD         | [de0d67e8c4](https://linux-hardware.org/?probe=de0d67e8c4) | Jan 31, 2022 |
| HP            | Laptop 15-db0xxx            | [8c455b3274](https://linux-hardware.org/?probe=8c455b3274) | Jan 30, 2022 |
| Dell          | Inspiron 3542               | [1dfd5b5461](https://linux-hardware.org/?probe=1dfd5b5461) | Jan 23, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [cc0c86531b](https://linux-hardware.org/?probe=cc0c86531b) | Jan 22, 2022 |
| ASUSTek       | K45VD                       | [206ce8c174](https://linux-hardware.org/?probe=206ce8c174) | Jan 18, 2022 |
| ASUSTek       | K45VD                       | [6eafcfd89d](https://linux-hardware.org/?probe=6eafcfd89d) | Jan 18, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [caa528d6e0](https://linux-hardware.org/?probe=caa528d6e0) | Jan 15, 2022 |
| Acer          | Swift SF514-54T             | [dffa1b1708](https://linux-hardware.org/?probe=dffa1b1708) | Jan 14, 2022 |
| Acer          | Swift SF514-54T             | [cf529c7ad0](https://linux-hardware.org/?probe=cf529c7ad0) | Jan 14, 2022 |
| HUAWEI        | MACH-WX9                    | [1c3636c882](https://linux-hardware.org/?probe=1c3636c882) | Jan 11, 2022 |
| HUAWEI        | MACH-WX9                    | [2e91b4b88c](https://linux-hardware.org/?probe=2e91b4b88c) | Jan 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [568c503df0](https://linux-hardware.org/?probe=568c503df0) | Jan 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fb627691ce](https://linux-hardware.org/?probe=fb627691ce) | Jan 07, 2022 |
| Lenovo        | ThinkPad X240 20AMA2F8MS    | [7b5c7a047a](https://linux-hardware.org/?probe=7b5c7a047a) | Jan 06, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c22ba841f6](https://linux-hardware.org/?probe=c22ba841f6) | Jan 06, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [be129c3a7a](https://linux-hardware.org/?probe=be129c3a7a) | Jan 05, 2022 |
| Lenovo        | ThinkPad T560 20FJS4FV00    | [4bd9bb5f20](https://linux-hardware.org/?probe=4bd9bb5f20) | Jan 05, 2022 |
| MSI           | GP66 Leopard 10UH           | [e9689e292c](https://linux-hardware.org/?probe=e9689e292c) | Jan 05, 2022 |
| Dell          | Inspiron 5520               | [5ce6cac5cb](https://linux-hardware.org/?probe=5ce6cac5cb) | Jan 04, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [c10faa4e15](https://linux-hardware.org/?probe=c10faa4e15) | Jan 04, 2022 |
| ASUSTek       | N43SL                       | [8468a0ab83](https://linux-hardware.org/?probe=8468a0ab83) | Jan 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [d770cc3fe5](https://linux-hardware.org/?probe=d770cc3fe5) | Jan 04, 2022 |
| Timi          | A35S                        | [2dafd53d09](https://linux-hardware.org/?probe=2dafd53d09) | Jan 04, 2022 |
| HP            | EliteBook 2540p             | [12ce36d52f](https://linux-hardware.org/?probe=12ce36d52f) | Jan 03, 2022 |
| Acer          | Aspire A315-56              | [2edffdea76](https://linux-hardware.org/?probe=2edffdea76) | Jan 03, 2022 |
| Dell          | Inspiron 3542               | [a611e12778](https://linux-hardware.org/?probe=a611e12778) | Dec 31, 2021 |
| Dell          | Precision 5560              | [04cb5954e9](https://linux-hardware.org/?probe=04cb5954e9) | Dec 31, 2021 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [e4d3f29412](https://linux-hardware.org/?probe=e4d3f29412) | Dec 30, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | [b608797946](https://linux-hardware.org/?probe=b608797946) | Dec 28, 2021 |
| HP            | Laptop 14-fq0xxx            | [756df875af](https://linux-hardware.org/?probe=756df875af) | Dec 23, 2021 |
| HP            | Laptop 14-fq0xxx            | [cd01eec1a8](https://linux-hardware.org/?probe=cd01eec1a8) | Dec 23, 2021 |
| HP            | Laptop 14-fq0xxx            | [4d153ddb81](https://linux-hardware.org/?probe=4d153ddb81) | Dec 23, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [deb1a17957](https://linux-hardware.org/?probe=deb1a17957) | Dec 23, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [ca89ed6eab](https://linux-hardware.org/?probe=ca89ed6eab) | Dec 23, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | [384617e5a7](https://linux-hardware.org/?probe=384617e5a7) | Dec 22, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | [8c9fc05c39](https://linux-hardware.org/?probe=8c9fc05c39) | Dec 22, 2021 |
| Unknown       | Unknown                     | [a1b24f9ab7](https://linux-hardware.org/?probe=a1b24f9ab7) | Dec 21, 2021 |
| Unknown       | Unknown                     | [0fb793d2a7](https://linux-hardware.org/?probe=0fb793d2a7) | Dec 21, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [7a6594a954](https://linux-hardware.org/?probe=7a6594a954) | Dec 19, 2021 |
| MSI           | Modern 14 B5M               | [3e8138c5b4](https://linux-hardware.org/?probe=3e8138c5b4) | Dec 18, 2021 |
| Lenovo        | ThinkPad T440s 20ARS0LU0... | [ab6c683160](https://linux-hardware.org/?probe=ab6c683160) | Dec 16, 2021 |
| Dell          | Inspiron 5558               | [16daa16444](https://linux-hardware.org/?probe=16daa16444) | Dec 16, 2021 |
| Acer          | Aspire 5250                 | [b4a48e5350](https://linux-hardware.org/?probe=b4a48e5350) | Dec 15, 2021 |
| HP            | 255 G7 Notebook PC          | [a34aa5357b](https://linux-hardware.org/?probe=a34aa5357b) | Dec 14, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [93957ddac1](https://linux-hardware.org/?probe=93957ddac1) | Dec 13, 2021 |
| Lenovo        | V14 G2 ITL 82NM             | [939be3ba51](https://linux-hardware.org/?probe=939be3ba51) | Dec 10, 2021 |
| MSI           | Prestige 15 A10SC           | [706fc926ca](https://linux-hardware.org/?probe=706fc926ca) | Dec 08, 2021 |
| Dell          | Latitude 7480               | [480ad981d9](https://linux-hardware.org/?probe=480ad981d9) | Dec 07, 2021 |
| Unknown       | Unknown                     | [2070780ca9](https://linux-hardware.org/?probe=2070780ca9) | Dec 07, 2021 |
| Framework     | Laptop                      | [c1a31372f4](https://linux-hardware.org/?probe=c1a31372f4) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [41dec8d290](https://linux-hardware.org/?probe=41dec8d290) | Dec 04, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [b49088935d](https://linux-hardware.org/?probe=b49088935d) | Dec 04, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [7cdf0f8f44](https://linux-hardware.org/?probe=7cdf0f8f44) | Dec 04, 2021 |
| Apple         | MacBookAir6,2               | [c5ba70d401](https://linux-hardware.org/?probe=c5ba70d401) | Nov 24, 2021 |
| MSI           | Bravo 15 B5DD               | [fc7c1ff3c8](https://linux-hardware.org/?probe=fc7c1ff3c8) | Nov 24, 2021 |
| Unknown       | Unknown                     | [b862ee20d9](https://linux-hardware.org/?probe=b862ee20d9) | Nov 24, 2021 |
| Unknown       | Unknown                     | [0555569b70](https://linux-hardware.org/?probe=0555569b70) | Nov 24, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [2b67e46016](https://linux-hardware.org/?probe=2b67e46016) | Nov 24, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [d0d56860bb](https://linux-hardware.org/?probe=d0d56860bb) | Nov 24, 2021 |
| MSI           | GS63VR 6RF                  | [2d9061c72e](https://linux-hardware.org/?probe=2d9061c72e) | Nov 23, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [85338e8b09](https://linux-hardware.org/?probe=85338e8b09) | Nov 23, 2021 |
| Apple         | MacBookAir7,2               | [df651ff7ad](https://linux-hardware.org/?probe=df651ff7ad) | Nov 23, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [e6eb602b05](https://linux-hardware.org/?probe=e6eb602b05) | Nov 22, 2021 |
| HP            | 15 TS                       | [50a260e4dc](https://linux-hardware.org/?probe=50a260e4dc) | Nov 21, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [a3d3e0eecd](https://linux-hardware.org/?probe=a3d3e0eecd) | Nov 20, 2021 |
| Dell          | XPS 13 9350                 | [ec54ffae7a](https://linux-hardware.org/?probe=ec54ffae7a) | Nov 18, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [778d32ce4b](https://linux-hardware.org/?probe=778d32ce4b) | Nov 17, 2021 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [9fc3f12603](https://linux-hardware.org/?probe=9fc3f12603) | Nov 16, 2021 |
| HUAWEI        | HN-WX9X                     | [22c7f120ab](https://linux-hardware.org/?probe=22c7f120ab) | Nov 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [c11672a55e](https://linux-hardware.org/?probe=c11672a55e) | Nov 11, 2021 |
| ASUSTek       | G751JT                      | [d2d03753ee](https://linux-hardware.org/?probe=d2d03753ee) | Nov 09, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [e95d2fa980](https://linux-hardware.org/?probe=e95d2fa980) | Nov 05, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [85dff2829f](https://linux-hardware.org/?probe=85dff2829f) | Nov 03, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [222ce004da](https://linux-hardware.org/?probe=222ce004da) | Nov 01, 2021 |
| ASUSTek       | G751JT                      | [b4c3816a33](https://linux-hardware.org/?probe=b4c3816a33) | Oct 30, 2021 |
| HUAWEI        | KLVL-WXX9                   | [3fcea4d382](https://linux-hardware.org/?probe=3fcea4d382) | Oct 29, 2021 |
| Acer          | Aspire E5-573G              | [cce67d37aa](https://linux-hardware.org/?probe=cce67d37aa) | Oct 28, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6a546c5681](https://linux-hardware.org/?probe=6a546c5681) | Oct 23, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [689f9368f1](https://linux-hardware.org/?probe=689f9368f1) | Oct 23, 2021 |
| Apple         | MacBookPro16,2              | [7b3cdda6e2](https://linux-hardware.org/?probe=7b3cdda6e2) | Oct 20, 2021 |
| HP            | ENVY 6                      | [94471889b0](https://linux-hardware.org/?probe=94471889b0) | Oct 20, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [ff566c77ce](https://linux-hardware.org/?probe=ff566c77ce) | Oct 17, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [2d3f367fa7](https://linux-hardware.org/?probe=2d3f367fa7) | Oct 17, 2021 |
| Apple         | MacBookPro16,2              | [6e745a1ec9](https://linux-hardware.org/?probe=6e745a1ec9) | Oct 17, 2021 |
| Dell          | Latitude E6410              | [68d7531397](https://linux-hardware.org/?probe=68d7531397) | Oct 17, 2021 |
| Apple         | MacBookPro16,2              | [8d0e93e90f](https://linux-hardware.org/?probe=8d0e93e90f) | Oct 16, 2021 |
| Lenovo        | Z50-70 20354                | [a852927b57](https://linux-hardware.org/?probe=a852927b57) | Oct 13, 2021 |
| Dell          | Precision M4400             | [bae8becab1](https://linux-hardware.org/?probe=bae8becab1) | Oct 11, 2021 |
| Google        | Kindred                     | [9420945432](https://linux-hardware.org/?probe=9420945432) | Oct 10, 2021 |
| Dell          | Latitude E4300              | [c486155f48](https://linux-hardware.org/?probe=c486155f48) | Oct 10, 2021 |
| Dell          | Latitude E4300              | [52e0d626fa](https://linux-hardware.org/?probe=52e0d626fa) | Oct 10, 2021 |
| Dell          | Latitude E6410              | [ebfe78c927](https://linux-hardware.org/?probe=ebfe78c927) | Oct 08, 2021 |
| Dell          | G3 3500                     | [b4e985bcba](https://linux-hardware.org/?probe=b4e985bcba) | Oct 08, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [e570cc15cd](https://linux-hardware.org/?probe=e570cc15cd) | Oct 06, 2021 |
| Lenovo        | Z50-70 20354                | [beda62c6f4](https://linux-hardware.org/?probe=beda62c6f4) | Oct 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0923a8b728](https://linux-hardware.org/?probe=0923a8b728) | Oct 05, 2021 |
| Dell          | Precision M4400             | [ab43bad624](https://linux-hardware.org/?probe=ab43bad624) | Oct 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9c8bc954a7](https://linux-hardware.org/?probe=9c8bc954a7) | Oct 02, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [dc91b564a8](https://linux-hardware.org/?probe=dc91b564a8) | Sep 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [86c4b5769f](https://linux-hardware.org/?probe=86c4b5769f) | Sep 28, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [263233be76](https://linux-hardware.org/?probe=263233be76) | Sep 28, 2021 |
| HP            | Pavilion dv6                | [2a6a76f702](https://linux-hardware.org/?probe=2a6a76f702) | Sep 26, 2021 |
| Lenovo        | ThinkPad T480 20L6S3S500    | [067f3cf110](https://linux-hardware.org/?probe=067f3cf110) | Sep 26, 2021 |
| Lenovo        | ThinkPad T470 20HES2SF00    | [9cf10e22a6](https://linux-hardware.org/?probe=9cf10e22a6) | Sep 25, 2021 |
| Lenovo        | ThinkPad E460 20ET004LGE    | [b64e2c4a07](https://linux-hardware.org/?probe=b64e2c4a07) | Sep 25, 2021 |
| Dell          | Precision 3560              | [d9b527db16](https://linux-hardware.org/?probe=d9b527db16) | Sep 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [1e1e40ce8b](https://linux-hardware.org/?probe=1e1e40ce8b) | Sep 22, 2021 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [711e2e3960](https://linux-hardware.org/?probe=711e2e3960) | Sep 22, 2021 |
| Dell          | XPS 15 7590                 | [3a7231ce53](https://linux-hardware.org/?probe=3a7231ce53) | Sep 17, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [8dfad66767](https://linux-hardware.org/?probe=8dfad66767) | Sep 16, 2021 |
| HP            | ENVY Laptop 13-ba0xxx       | [3e845646c9](https://linux-hardware.org/?probe=3e845646c9) | Sep 15, 2021 |
| Dynabook      | Satellite Pro C50-E-109     | [0fe0fa66d6](https://linux-hardware.org/?probe=0fe0fa66d6) | Sep 14, 2021 |
| Dynabook      | Satellite Pro C50-E-109     | [d5e170957e](https://linux-hardware.org/?probe=d5e170957e) | Sep 14, 2021 |
| Acer          | Nitro AN515-54              | [8f215120c2](https://linux-hardware.org/?probe=8f215120c2) | Sep 13, 2021 |
| AMI           | Intel                       | [49dd022241](https://linux-hardware.org/?probe=49dd022241) | Sep 10, 2021 |
| Razer         | Blade 15 Advanced Model ... | [0c83ae1e11](https://linux-hardware.org/?probe=0c83ae1e11) | Sep 10, 2021 |
| Lenovo        | Legion Y545 81Q6            | [167df4c15e](https://linux-hardware.org/?probe=167df4c15e) | Sep 09, 2021 |
| Dell          | Latitude E4310              | [34c3815468](https://linux-hardware.org/?probe=34c3815468) | Sep 02, 2021 |
| TrekStor      | Primebook P14               | [026e7277ee](https://linux-hardware.org/?probe=026e7277ee) | Sep 02, 2021 |
| HP            | Laptop 15s-fq2xxx           | [87b688768a](https://linux-hardware.org/?probe=87b688768a) | Sep 02, 2021 |
| Dell          | Precision M4400             | [289a2606bd](https://linux-hardware.org/?probe=289a2606bd) | Sep 02, 2021 |
| Apple         | MacBookAir7,2               | [581b1be43c](https://linux-hardware.org/?probe=581b1be43c) | Aug 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [d3ab28e58e](https://linux-hardware.org/?probe=d3ab28e58e) | Aug 30, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [24a34a526e](https://linux-hardware.org/?probe=24a34a526e) | Aug 28, 2021 |
| Lenovo        | IdeaPad 510S-14IKB 80UV     | [146390e85e](https://linux-hardware.org/?probe=146390e85e) | Aug 25, 2021 |
| ASUSTek       | G752VT                      | [23dea85a93](https://linux-hardware.org/?probe=23dea85a93) | Aug 24, 2021 |
| Dell          | Latitude E7440              | [0de5415ad7](https://linux-hardware.org/?probe=0de5415ad7) | Aug 22, 2021 |
| Dell          | Inspiron 5577               | [ae8d8171a7](https://linux-hardware.org/?probe=ae8d8171a7) | Aug 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [71645376f3](https://linux-hardware.org/?probe=71645376f3) | Aug 13, 2021 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | [5d560f16cc](https://linux-hardware.org/?probe=5d560f16cc) | Aug 12, 2021 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | [9be95b3419](https://linux-hardware.org/?probe=9be95b3419) | Aug 12, 2021 |
| HP            | EliteBook 745 G6            | [d3ed4611f3](https://linux-hardware.org/?probe=d3ed4611f3) | Aug 10, 2021 |
| Dell          | Inspiron 5570               | [9adf19d9c0](https://linux-hardware.org/?probe=9adf19d9c0) | Aug 10, 2021 |
| HP            | ENVY Laptop 13-aq1xxx       | [52118232ff](https://linux-hardware.org/?probe=52118232ff) | Aug 10, 2021 |
| Notebook      | W65_67SZ                    | [ddd6f26db4](https://linux-hardware.org/?probe=ddd6f26db4) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | [1ccf2e3d28](https://linux-hardware.org/?probe=1ccf2e3d28) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [b5b8bac74a](https://linux-hardware.org/?probe=b5b8bac74a) | Jul 26, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | [12d6be24d7](https://linux-hardware.org/?probe=12d6be24d7) | Jul 25, 2021 |
| Apple         | MacBookAir7,2               | [a5959b657f](https://linux-hardware.org/?probe=a5959b657f) | Jul 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [f8f9bf0717](https://linux-hardware.org/?probe=f8f9bf0717) | Jul 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [7cdf389d4c](https://linux-hardware.org/?probe=7cdf389d4c) | Jul 22, 2021 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [4421b175f7](https://linux-hardware.org/?probe=4421b175f7) | Jul 16, 2021 |
| Acer          | Predator G9-792             | [e0f2c7b0c5](https://linux-hardware.org/?probe=e0f2c7b0c5) | Jul 12, 2021 |
| Acer          | Aspire A515-43              | [c79cfacd5e](https://linux-hardware.org/?probe=c79cfacd5e) | Jul 05, 2021 |
| Apple         | MacBookPro9,2               | [282a2e2926](https://linux-hardware.org/?probe=282a2e2926) | Jul 04, 2021 |
| Acer          | Nitro AN515-54              | [3be93cbc0c](https://linux-hardware.org/?probe=3be93cbc0c) | Jul 03, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [fd48c4cd51](https://linux-hardware.org/?probe=fd48c4cd51) | Jul 02, 2021 |
| HP            | ENVY Laptop 13-ba0xxx       | [181cfa9437](https://linux-hardware.org/?probe=181cfa9437) | Jul 01, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [a92028f13a](https://linux-hardware.org/?probe=a92028f13a) | Jul 01, 2021 |
| Lenovo        | ThinkPad T450s 20BW0007U... | [56a361debf](https://linux-hardware.org/?probe=56a361debf) | Jul 01, 2021 |
| Lenovo        | ThinkPad T450s 20BW0007U... | [431df4bc98](https://linux-hardware.org/?probe=431df4bc98) | Jul 01, 2021 |
| Dell          | G7 7588                     | [259694c4a1](https://linux-hardware.org/?probe=259694c4a1) | Jun 27, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [d2f1ec957f](https://linux-hardware.org/?probe=d2f1ec957f) | Jun 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [4b70691f2e](https://linux-hardware.org/?probe=4b70691f2e) | Jun 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [397e22935b](https://linux-hardware.org/?probe=397e22935b) | Jun 25, 2021 |
| HP            | 255 G7 Notebook PC          | [2762be36c4](https://linux-hardware.org/?probe=2762be36c4) | Jun 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [48bda0fbd3](https://linux-hardware.org/?probe=48bda0fbd3) | Jun 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [117372a8ff](https://linux-hardware.org/?probe=117372a8ff) | Jun 05, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [6b6205bc5d](https://linux-hardware.org/?probe=6b6205bc5d) | May 31, 2021 |
| HP            | EliteBook Revolve 810       | [24758ed5b3](https://linux-hardware.org/?probe=24758ed5b3) | May 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cad013a6a5](https://linux-hardware.org/?probe=cad013a6a5) | May 31, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3490... | [4c600416f9](https://linux-hardware.org/?probe=4c600416f9) | May 28, 2021 |
| ASUSTek       | K45DR                       | [b86bb4b6c9](https://linux-hardware.org/?probe=b86bb4b6c9) | May 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [99ab618bee](https://linux-hardware.org/?probe=99ab618bee) | May 25, 2021 |
| Schenker      | XMG NEO 15(E20, RTX 20xx... | [684dfb967f](https://linux-hardware.org/?probe=684dfb967f) | May 22, 2021 |
| Schenker      | XMG NEO 15(E20, RTX 20xx... | [c18360d17e](https://linux-hardware.org/?probe=c18360d17e) | May 22, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [c1b869c13a](https://linux-hardware.org/?probe=c1b869c13a) | May 22, 2021 |
| Acer          | Swift SF314-51              | [a666be1df5](https://linux-hardware.org/?probe=a666be1df5) | May 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [457597b9d1](https://linux-hardware.org/?probe=457597b9d1) | May 21, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [e18030e5f0](https://linux-hardware.org/?probe=e18030e5f0) | May 20, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [7e5dbc86b9](https://linux-hardware.org/?probe=7e5dbc86b9) | May 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [14b3851754](https://linux-hardware.org/?probe=14b3851754) | May 20, 2021 |
| Notebook      | NS50MU                      | [8e08645823](https://linux-hardware.org/?probe=8e08645823) | May 19, 2021 |
| Lenovo        | ThinkPad P51 20HHCT01WW     | [3f42eaf28b](https://linux-hardware.org/?probe=3f42eaf28b) | May 19, 2021 |
| MSI           | GE72 6QD                    | [7637f1ad9c](https://linux-hardware.org/?probe=7637f1ad9c) | May 19, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [634c63d316](https://linux-hardware.org/?probe=634c63d316) | May 15, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [17af51e9b1](https://linux-hardware.org/?probe=17af51e9b1) | May 14, 2021 |
| HP            | EliteBook 2170p             | [6e4a5f9c76](https://linux-hardware.org/?probe=6e4a5f9c76) | May 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9048b606d2](https://linux-hardware.org/?probe=9048b606d2) | May 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f02e90a00f](https://linux-hardware.org/?probe=f02e90a00f) | May 11, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [ec0cb83241](https://linux-hardware.org/?probe=ec0cb83241) | May 10, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3490... | [b3a5056cbf](https://linux-hardware.org/?probe=b3a5056cbf) | May 07, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [365c656e4a](https://linux-hardware.org/?probe=365c656e4a) | May 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [fca3b0c89b](https://linux-hardware.org/?probe=fca3b0c89b) | May 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9e8b256742](https://linux-hardware.org/?probe=9e8b256742) | May 03, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [e7cd00034c](https://linux-hardware.org/?probe=e7cd00034c) | May 02, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [39f6decf99](https://linux-hardware.org/?probe=39f6decf99) | May 02, 2021 |
| HP            | 255 G4                      | [9070448ace](https://linux-hardware.org/?probe=9070448ace) | May 01, 2021 |
| Lenovo        | ThinkPad T61 7659W1W        | [c366a3e7a2](https://linux-hardware.org/?probe=c366a3e7a2) | May 01, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [3d3ef81b3b](https://linux-hardware.org/?probe=3d3ef81b3b) | Apr 29, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | [d90f10abcd](https://linux-hardware.org/?probe=d90f10abcd) | Apr 29, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | [b27160a3cb](https://linux-hardware.org/?probe=b27160a3cb) | Apr 29, 2021 |
| Acer          | Extensa 2510                | [1f257d3f4e](https://linux-hardware.org/?probe=1f257d3f4e) | Apr 25, 2021 |
| Lenovo        | E31-80 80MX                 | [8aedfd9f4c](https://linux-hardware.org/?probe=8aedfd9f4c) | Apr 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [764390758a](https://linux-hardware.org/?probe=764390758a) | Apr 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [eabc0fa5e5](https://linux-hardware.org/?probe=eabc0fa5e5) | Apr 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [fae6227cfc](https://linux-hardware.org/?probe=fae6227cfc) | Apr 19, 2021 |
| Toshiba       | Satellite P750              | [d248a5f049](https://linux-hardware.org/?probe=d248a5f049) | Apr 11, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [2c17afdb0a](https://linux-hardware.org/?probe=2c17afdb0a) | Apr 08, 2021 |
| Dell          | Inspiron 5391               | [80bf268441](https://linux-hardware.org/?probe=80bf268441) | Apr 08, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [9e5b4c92f4](https://linux-hardware.org/?probe=9e5b4c92f4) | Apr 01, 2021 |
| Toshiba       | Satellite L50D-B            | [6fdb3a7d9e](https://linux-hardware.org/?probe=6fdb3a7d9e) | Mar 31, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [269185aba1](https://linux-hardware.org/?probe=269185aba1) | Mar 28, 2021 |
| Dell          | G7 7588                     | [95e0518b2c](https://linux-hardware.org/?probe=95e0518b2c) | Mar 25, 2021 |
| Dell          | Latitude 5300               | [efd4a051e5](https://linux-hardware.org/?probe=efd4a051e5) | Mar 23, 2021 |
| Lenovo        | ThinkPad L460 20FV002EBR    | [f19448d66f](https://linux-hardware.org/?probe=f19448d66f) | Mar 19, 2021 |
| Lenovo        | ThinkPad T520 4239CTO       | [e03adb0720](https://linux-hardware.org/?probe=e03adb0720) | Mar 17, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [13dfc4a9af](https://linux-hardware.org/?probe=13dfc4a9af) | Mar 17, 2021 |
| Dell          | G5 5505                     | [e8e38279d3](https://linux-hardware.org/?probe=e8e38279d3) | Mar 11, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [062dfb8010](https://linux-hardware.org/?probe=062dfb8010) | Mar 09, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [eec4ef3dce](https://linux-hardware.org/?probe=eec4ef3dce) | Mar 07, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [bd3a730b32](https://linux-hardware.org/?probe=bd3a730b32) | Mar 03, 2021 |
| HP            | Laptop 15-da0xxx            | [88635c9f76](https://linux-hardware.org/?probe=88635c9f76) | Feb 23, 2021 |
| Gigabyte      | AERO 15XV8                  | [c4ecc96eae](https://linux-hardware.org/?probe=c4ecc96eae) | Feb 19, 2021 |
| Apple         | MacBookPro7,1               | [93115f0746](https://linux-hardware.org/?probe=93115f0746) | Feb 14, 2021 |
| Apple         | MacBookPro7,1               | [1bd84f7c03](https://linux-hardware.org/?probe=1bd84f7c03) | Feb 13, 2021 |
| HP            | ZBook 15                    | [dc1d23b1c6](https://linux-hardware.org/?probe=dc1d23b1c6) | Feb 12, 2021 |
| ASUSTek       | GL503VM                     | [72f95227fd](https://linux-hardware.org/?probe=72f95227fd) | Feb 11, 2021 |
| ASUSTek       | GL503VM                     | [130e9bdb5c](https://linux-hardware.org/?probe=130e9bdb5c) | Feb 11, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [43bb3ec644](https://linux-hardware.org/?probe=43bb3ec644) | Feb 08, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [5856d93198](https://linux-hardware.org/?probe=5856d93198) | Feb 07, 2021 |
| HP            | ENVY Notebook               | [4f20314e69](https://linux-hardware.org/?probe=4f20314e69) | Feb 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4f64a771ff](https://linux-hardware.org/?probe=4f64a771ff) | Feb 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4d8f4f66c7](https://linux-hardware.org/?probe=4d8f4f66c7) | Jan 31, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [311f54d837](https://linux-hardware.org/?probe=311f54d837) | Jan 28, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [a0c3014b22](https://linux-hardware.org/?probe=a0c3014b22) | Jan 17, 2021 |
| Lenovo        | ThinkPad T510 4384FF3       | [9fd64a3945](https://linux-hardware.org/?probe=9fd64a3945) | Jan 11, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [929b0edb33](https://linux-hardware.org/?probe=929b0edb33) | Jan 11, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [6499961dbf](https://linux-hardware.org/?probe=6499961dbf) | Jan 09, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [2df429a577](https://linux-hardware.org/?probe=2df429a577) | Jan 06, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [f2b808bdd1](https://linux-hardware.org/?probe=f2b808bdd1) | Dec 24, 2020 |
| MSI           | GL75 Leopard 10SDK          | [8b792fe096](https://linux-hardware.org/?probe=8b792fe096) | Dec 23, 2020 |
| HP            | Laptop 15-db1xxx            | [c7807b04ff](https://linux-hardware.org/?probe=c7807b04ff) | Dec 20, 2020 |
| HP            | EliteBook Revolve 810       | [b6b29c8237](https://linux-hardware.org/?probe=b6b29c8237) | Dec 17, 2020 |
| Apple         | MacBookAir4,2               | [a3ebd820e2](https://linux-hardware.org/?probe=a3ebd820e2) | Dec 17, 2020 |
| Alienware     | 14                          | [3211a0e18d](https://linux-hardware.org/?probe=3211a0e18d) | Dec 12, 2020 |
| HP            | 255 G7 Notebook PC          | [75384533dc](https://linux-hardware.org/?probe=75384533dc) | Dec 06, 2020 |
| Dell          | Precision M6600             | [c3eafadf96](https://linux-hardware.org/?probe=c3eafadf96) | Dec 05, 2020 |
| HP            | 255 G7 Notebook PC          | [7e7ad00d75](https://linux-hardware.org/?probe=7e7ad00d75) | Dec 01, 2020 |
| HP            | 255 G7 Notebook PC          | [7e75c8dc00](https://linux-hardware.org/?probe=7e75c8dc00) | Dec 01, 2020 |
| HP            | 255 G7 Notebook PC          | [2381ec1bad](https://linux-hardware.org/?probe=2381ec1bad) | Nov 30, 2020 |
| MSI           | GT80S 6QE                   | [a938950688](https://linux-hardware.org/?probe=a938950688) | Nov 28, 2020 |
| MSI           | GT80S 6QE                   | [a07d34dcff](https://linux-hardware.org/?probe=a07d34dcff) | Nov 28, 2020 |
| Dell          | Precision M6600             | [990be59736](https://linux-hardware.org/?probe=990be59736) | Nov 21, 2020 |
| ASUSTek       | X550CL                      | [5315051a75](https://linux-hardware.org/?probe=5315051a75) | Nov 21, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2a4a52111f](https://linux-hardware.org/?probe=2a4a52111f) | Nov 21, 2020 |
| Acer          | Aspire V3-575G              | [56c2638b77](https://linux-hardware.org/?probe=56c2638b77) | Nov 18, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [1a46306857](https://linux-hardware.org/?probe=1a46306857) | Nov 16, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [9737ecaee9](https://linux-hardware.org/?probe=9737ecaee9) | Nov 06, 2020 |
| Timi          | TM1607                      | [dbe64c3d75](https://linux-hardware.org/?probe=dbe64c3d75) | Nov 02, 2020 |
| Lenovo        | IdeaPad Yoga 13 20175       | [518c70a58e](https://linux-hardware.org/?probe=518c70a58e) | Nov 02, 2020 |
| HP            | Laptop 14-dk1xxx            | [5cdfdbceae](https://linux-hardware.org/?probe=5cdfdbceae) | Oct 26, 2020 |
| HP            | Laptop 14-dk1xxx            | [130d636b9e](https://linux-hardware.org/?probe=130d636b9e) | Oct 26, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [3e19ade739](https://linux-hardware.org/?probe=3e19ade739) | Oct 25, 2020 |
| HP            | Notebook                    | [fe4c2b1ca0](https://linux-hardware.org/?probe=fe4c2b1ca0) | Oct 25, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [1e6190a4f2](https://linux-hardware.org/?probe=1e6190a4f2) | Oct 21, 2020 |
| Dell          | Inspiron 7559               | [d3265c616b](https://linux-hardware.org/?probe=d3265c616b) | Oct 21, 2020 |
| Dell          | Inspiron 7559               | [01f75c41ed](https://linux-hardware.org/?probe=01f75c41ed) | Oct 20, 2020 |
| Dell          | Inspiron 3493               | [502cfa6428](https://linux-hardware.org/?probe=502cfa6428) | Oct 15, 2020 |
| Dell          | Inspiron 3493               | [459870a593](https://linux-hardware.org/?probe=459870a593) | Oct 14, 2020 |
| ASUSTek       | GL702ZC                     | [c90edc1b80](https://linux-hardware.org/?probe=c90edc1b80) | Oct 12, 2020 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [2abc472e43](https://linux-hardware.org/?probe=2abc472e43) | Oct 08, 2020 |
| Acer          | Aspire E5-573               | [89237e04fc](https://linux-hardware.org/?probe=89237e04fc) | Oct 04, 2020 |
| Unknown       | Unknown                     | [e50c3910d9](https://linux-hardware.org/?probe=e50c3910d9) | Oct 02, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [4ec2f0a6cc](https://linux-hardware.org/?probe=4ec2f0a6cc) | Sep 29, 2020 |
| Dell          | G3 3579                     | [6853280510](https://linux-hardware.org/?probe=6853280510) | Sep 28, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | [f12775338c](https://linux-hardware.org/?probe=f12775338c) | Sep 27, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | [41b9e8cb16](https://linux-hardware.org/?probe=41b9e8cb16) | Sep 15, 2020 |
| Acer          | TravelMate P633-M           | [a7fdf21400](https://linux-hardware.org/?probe=a7fdf21400) | Sep 11, 2020 |
| Dell          | Latitude E6440              | [ddd1e2f728](https://linux-hardware.org/?probe=ddd1e2f728) | Sep 03, 2020 |
| ASUSTek       | UX310UA                     | [90e38ace34](https://linux-hardware.org/?probe=90e38ace34) | Sep 03, 2020 |
| HP            | EliteBook 840 G5            | [c020f92165](https://linux-hardware.org/?probe=c020f92165) | Aug 30, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [82736e9fa5](https://linux-hardware.org/?probe=82736e9fa5) | Aug 23, 2020 |
| Dell          | Latitude E6430              | [8dab7d4223](https://linux-hardware.org/?probe=8dab7d4223) | Aug 15, 2020 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [935afc3dde](https://linux-hardware.org/?probe=935afc3dde) | Jul 27, 2020 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | [fd00cb49a3](https://linux-hardware.org/?probe=fd00cb49a3) | Jul 27, 2020 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | [4830a55da9](https://linux-hardware.org/?probe=4830a55da9) | Jul 27, 2020 |
| Dell          | Latitude 7400               | [69e41d5126](https://linux-hardware.org/?probe=69e41d5126) | Jul 20, 2020 |
| Dell          | Latitude 7400               | [42561b6e01](https://linux-hardware.org/?probe=42561b6e01) | Jul 20, 2020 |
| Dell          | Latitude 7400               | [606ef1afa8](https://linux-hardware.org/?probe=606ef1afa8) | Jul 17, 2020 |
| Lenovo        | ThinkPad E595 20NFS0TD00    | [7fbac3cf0a](https://linux-hardware.org/?probe=7fbac3cf0a) | Jul 16, 2020 |
| Lenovo        | ThinkPad T460 20FMS2J000    | [ed0f57c08d](https://linux-hardware.org/?probe=ed0f57c08d) | Jul 14, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [fc1d360821](https://linux-hardware.org/?probe=fc1d360821) | Jun 29, 2020 |
| Dell          | Inspiron 5559               | [a2e2a6cf66](https://linux-hardware.org/?probe=a2e2a6cf66) | May 12, 2020 |
| Lenovo        | G505s 20255                 | [21f31cf2d0](https://linux-hardware.org/?probe=21f31cf2d0) | Apr 21, 2020 |
| HP            | EliteBook 8770w             | [44b687a5ef](https://linux-hardware.org/?probe=44b687a5ef) | Jan 31, 2020 |
| HP            | EliteBook 830 G6            | [c4078ad25e](https://linux-hardware.org/?probe=c4078ad25e) | Jan 25, 2020 |
| Acer          | Aspire ES1-520              | [12a0136c2d](https://linux-hardware.org/?probe=12a0136c2d) | Jan 20, 2020 |
| Shinelon C... | W65KJ1_KK1                  | [924a887f7d](https://linux-hardware.org/?probe=924a887f7d) | Dec 09, 2019 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [d5c741f8df](https://linux-hardware.org/?probe=d5c741f8df) | Dec 08, 2019 |
| Dell          | Inspiron 7520               | [3477d2f29e](https://linux-hardware.org/?probe=3477d2f29e) | Sep 10, 2019 |
| Dell          | Inspiron 7520               | [80bdb92976](https://linux-hardware.org/?probe=80bdb92976) | Sep 10, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/EndeavourOS/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| EndeavourOS Rolling | 470       | 84.68%  |
| EndeavourOS         | 85        | 15.32%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| EndeavourOS | 549       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 6.2.8-arch1-1     | 13        | 2.12%   |
| 6.2.10-arch1-1    | 8         | 1.31%   |
| 5.19.7-arch1-1    | 8         | 1.31%   |
| 5.15.12-arch1-1   | 8         | 1.31%   |
| 6.3.1-arch1-1     | 7         | 1.14%   |
| 6.2.9-arch1-1     | 7         | 1.14%   |
| 6.1.12-arch1-1    | 7         | 1.14%   |
| 5.13.13-arch1-1   | 7         | 1.14%   |
| 6.3.4-arch1-1     | 6         | 0.98%   |
| 6.2.2-arch1-1     | 6         | 0.98%   |
| 6.1.1-arch1-1     | 6         | 0.98%   |
| 6.0.9-arch1-1     | 6         | 0.98%   |
| 5.15.10-arch1-1   | 6         | 0.98%   |
| 6.2.13-arch1-1    | 5         | 0.82%   |
| 6.2.12-arch1-1    | 5         | 0.82%   |
| 6.0.2-arch1-1     | 5         | 0.82%   |
| 6.0.12-arch1-1    | 5         | 0.82%   |
| 5.9.14-arch1-1    | 5         | 0.82%   |
| 5.19.13-arch1-1   | 5         | 0.82%   |
| 5.19.11-arch1-1   | 5         | 0.82%   |
| 5.18.16-arch1-1   | 5         | 0.82%   |
| 5.15.4-arch1-1    | 5         | 0.82%   |
| 6.2.7-arch1-1     | 4         | 0.65%   |
| 6.2.5-arch1-1     | 4         | 0.65%   |
| 6.1.8-arch1-1     | 4         | 0.65%   |
| 6.1.7-arch1-1     | 4         | 0.65%   |
| 6.1.4-arch1-1     | 4         | 0.65%   |
| 6.1.11-arch1-1    | 4         | 0.65%   |
| 6.0.7-arch1-1     | 4         | 0.65%   |
| 6.0.10-arch2-1    | 4         | 0.65%   |
| 5.9.1-arch1-1     | 4         | 0.65%   |
| 5.7.8-arch1-1     | 4         | 0.65%   |
| 5.19.6-zen1-1-zen | 4         | 0.65%   |
| 5.19.12-arch1-1   | 4         | 0.65%   |
| 5.17.9-arch1-1    | 4         | 0.65%   |
| 5.17.5-arch1-1    | 4         | 0.65%   |
| 5.17.1-arch1-1    | 4         | 0.65%   |
| 5.16.8-arch1-1    | 4         | 0.65%   |
| 5.16.4-arch1-1    | 4         | 0.65%   |
| 5.16.10-arch1-1   | 4         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.8   | 14        | 2.29%   |
| 6.3.1   | 12        | 1.96%   |
| 5.15.12 | 11        | 1.8%    |
| 6.1.1   | 10        | 1.63%   |
| 6.0.2   | 10        | 1.63%   |
| 5.19.7  | 10        | 1.63%   |
| 5.13.13 | 10        | 1.63%   |
| 6.1.12  | 9         | 1.47%   |
| 6.0.9   | 9         | 1.47%   |
| 6.3.4   | 8         | 1.31%   |
| 6.2.9   | 8         | 1.31%   |
| 6.2.10  | 8         | 1.31%   |
| 5.15.4  | 8         | 1.31%   |
| 6.2.2   | 7         | 1.14%   |
| 6.0.12  | 7         | 1.14%   |
| 5.19.13 | 7         | 1.14%   |
| 5.15.2  | 7         | 1.14%   |
| 5.12.13 | 7         | 1.14%   |
| 5.11.16 | 7         | 1.14%   |
| 6.2.13  | 6         | 0.98%   |
| 6.2.12  | 6         | 0.98%   |
| 6.0.6   | 6         | 0.98%   |
| 5.19.6  | 6         | 0.98%   |
| 5.19.11 | 6         | 0.98%   |
| 5.17.5  | 6         | 0.98%   |
| 5.17.1  | 6         | 0.98%   |
| 5.15.10 | 6         | 0.98%   |
| 5.14.9  | 6         | 0.98%   |
| 6.3.6   | 5         | 0.82%   |
| 6.3.5   | 5         | 0.82%   |
| 6.3.2   | 5         | 0.82%   |
| 6.2.7   | 5         | 0.82%   |
| 6.2.5   | 5         | 0.82%   |
| 6.1.9   | 5         | 0.82%   |
| 6.1.8   | 5         | 0.82%   |
| 6.1.7   | 5         | 0.82%   |
| 6.0.7   | 5         | 0.82%   |
| 5.9.14  | 5         | 0.82%   |
| 5.9.1   | 5         | 0.82%   |
| 5.19.9  | 5         | 0.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 72        | 12.12%  |
| 6.2     | 66        | 11.11%  |
| 6.1     | 65        | 10.94%  |
| 5.19    | 52        | 8.75%   |
| 6.0     | 46        | 7.74%   |
| 5.16    | 37        | 6.23%   |
| 6.3     | 35        | 5.89%   |
| 5.14    | 30        | 5.05%   |
| 5.17    | 29        | 4.88%   |
| 5.18    | 24        | 4.04%   |
| 5.13    | 24        | 4.04%   |
| 5.12    | 24        | 4.04%   |
| 5.9     | 21        | 3.54%   |
| 5.11    | 21        | 3.54%   |
| 5.10    | 20        | 3.37%   |
| 5.8     | 9         | 1.52%   |
| 5.7     | 8         | 1.35%   |
| 5.4     | 6         | 1.01%   |
| 5.6     | 2         | 0.34%   |
| 4.19    | 2         | 0.34%   |
| 5.17.1  | 1         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 548       | 99.82%  |
| aarch64 | 1         | 0.18%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KDE5            | 191       | 33.69%  |
| GNOME           | 135       | 23.81%  |
| XFCE            | 115       | 20.28%  |
| X-Cinnamon      | 22        | 3.88%   |
| i3              | 20        | 3.53%   |
| KDE             | 13        | 2.29%   |
| Budgie          | 12        | 2.12%   |
| Unknown         | 12        | 2.12%   |
| MATE            | 7         | 1.23%   |
| Cinnamon        | 7         | 1.23%   |
| sway            | 6         | 1.06%   |
| LXQt            | 5         | 0.88%   |
| openbox         | 3         | 0.53%   |
| GNOME Flashback | 3         | 0.53%   |
| bspwm           | 3         | 0.53%   |
| qtile           | 2         | 0.35%   |
| LXDE            | 2         | 0.35%   |
| Hyprland        | 2         | 0.35%   |
| Deepin          | 2         | 0.35%   |
| awesome         | 2         | 0.35%   |
| xmonad          | 1         | 0.18%   |
| LeftWM          | 1         | 0.18%   |
| GNOME Classic   | 1         | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 403       | 72.22%  |
| Wayland | 127       | 22.76%  |
| Tty     | 19        | 3.41%   |
| Unknown | 9         | 1.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 184       | 32.62%  |
| Unknown | 137       | 24.29%  |
| SDDM    | 133       | 23.58%  |
| GDM     | 82        | 14.54%  |
| TDM     | 26        | 4.61%   |
| GREETD  | 2         | 0.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 283       | 51.27%  |
| en_GB   | 44        | 7.97%   |
| it_IT   | 34        | 6.16%   |
| de_DE   | 23        | 4.17%   |
| en_CA   | 22        | 3.99%   |
| fr_FR   | 13        | 2.36%   |
| en_IN   | 13        | 2.36%   |
| ru_RU   | 9         | 1.63%   |
| en_AU   | 9         | 1.63%   |
| pt_BR   | 8         | 1.45%   |
| nl_NL   | 7         | 1.27%   |
| es_ES   | 7         | 1.27%   |
| Unknown | 7         | 1.27%   |
| fi_FI   | 6         | 1.09%   |
| tr_TR   | 5         | 0.91%   |
| pl_PL   | 5         | 0.91%   |
| es_MX   | 5         | 0.91%   |
| en_NZ   | 5         | 0.91%   |
| es_AR   | 4         | 0.72%   |
| en_PH   | 4         | 0.72%   |
| sv_SE   | 3         | 0.54%   |
| pt_PT   | 3         | 0.54%   |
| en_DK   | 3         | 0.54%   |
| de_AT   | 3         | 0.54%   |
| zh_CN   | 2         | 0.36%   |
| ru_UA   | 2         | 0.36%   |
| en_SG   | 2         | 0.36%   |
| en_AG   | 2         | 0.36%   |
| sr_RS   | 1         | 0.18%   |
| nl_BE   | 1         | 0.18%   |
| ko_KR   | 1         | 0.18%   |
| id_ID   | 1         | 0.18%   |
| hu_HU   | 1         | 0.18%   |
| hr_HR   | 1         | 0.18%   |
| es_US   | 1         | 0.18%   |
| es_PY   | 1         | 0.18%   |
| es_CO   | 1         | 0.18%   |
| en_ZA   | 1         | 0.18%   |
| en_MY   | 1         | 0.18%   |
| en_IL   | 1         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 370       | 66.67%  |
| BIOS | 185       | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 388       | 70.29%  |
| Btrfs   | 136       | 24.64%  |
| Overlay | 14        | 2.54%   |
| Xfs     | 7         | 1.27%   |
| Tmpfs   | 3         | 0.54%   |
| F2fs    | 2         | 0.36%   |
| Ext2    | 1         | 0.18%   |
| Unknown | 1         | 0.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 376       | 67.63%  |
| Unknown | 136       | 24.46%  |
| MBR     | 44        | 7.91%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 488       | 88.25%  |
| Yes       | 65        | 11.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 400       | 71.68%  |
| Yes       | 158       | 28.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 150       | 27.32%  |
| ASUSTek Computer    | 84        | 15.3%   |
| Hewlett-Packard     | 83        | 15.12%  |
| Dell                | 62        | 11.29%  |
| Acer                | 38        | 6.92%   |
| MSI                 | 23        | 4.19%   |
| Apple               | 19        | 3.46%   |
| HUAWEI              | 14        | 2.55%   |
| Timi                | 10        | 1.82%   |
| Google              | 9         | 1.64%   |
| Toshiba             | 7         | 1.28%   |
| Notebook            | 6         | 1.09%   |
| Samsung Electronics | 4         | 0.73%   |
| TUXEDO              | 3         | 0.55%   |
| Sony                | 3         | 0.55%   |
| Schenker            | 3         | 0.55%   |
| Gigabyte Technology | 3         | 0.55%   |
| Unknown             | 3         | 0.55%   |
| TrekStor            | 2         | 0.36%   |
| Razer               | 2         | 0.36%   |
| Positivo            | 2         | 0.36%   |
| Packard Bell        | 2         | 0.36%   |
| GPD                 | 2         | 0.36%   |
| Chuwi               | 2         | 0.36%   |
| VIT                 | 1         | 0.18%   |
| Shinelon Computer   | 1         | 0.18%   |
| Radxa               | 1         | 0.18%   |
| Pine Microsystems   | 1         | 0.18%   |
| PC Specialist       | 1         | 0.18%   |
| ILLEGEAR            | 1         | 0.18%   |
| HONOR               | 1         | 0.18%   |
| Framework           | 1         | 0.18%   |
| Eluktronics         | 1         | 0.18%   |
| Dynabook            | 1         | 0.18%   |
| AWOW                | 1         | 0.18%   |
| AMI                 | 1         | 0.18%   |
| Alienware           | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBookAir7,2                   | 6         | 1.09%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 4         | 0.73%   |
| Unknown                               | 4         | 0.73%   |
| MSI Modern 14 B5M                     | 3         | 0.55%   |
| Lenovo ThinkPad X140e 20BL000BUS      | 3         | 0.55%   |
| Lenovo ThinkBook 15 G2 ITL 20VE       | 3         | 0.55%   |
| Lenovo Legion 5 15ACH6H 82JU          | 3         | 0.55%   |
| Lenovo IdeaPad 3 15ITL6 82H8          | 3         | 0.55%   |
| HUAWEI KLVL-WXX9                      | 3         | 0.55%   |
| HP Pavilion Gaming Laptop 15-cx0xxx   | 3         | 0.55%   |
| Acer Aspire E5-575G                   | 3         | 0.55%   |
| Timi TM1701                           | 2         | 0.36%   |
| Timi A35S                             | 2         | 0.36%   |
| Samsung 340XAA/350XAA/550XAA          | 2         | 0.36%   |
| Positivo S14BW01                      | 2         | 0.36%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS    | 2         | 0.36%   |
| Lenovo ThinkPad T14 Gen 3 21CFCTO1WW  | 2         | 0.36%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013MB  | 2         | 0.36%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY  | 2         | 0.36%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2   | 2         | 0.36%   |
| Lenovo IdeaPad Flex-14API 81SS        | 2         | 0.36%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5      | 2         | 0.36%   |
| Lenovo IdeaPad 5 15ARE05 81YQ         | 2         | 0.36%   |
| Lenovo IdeaPad 330-15IKB 81DE         | 2         | 0.36%   |
| Lenovo IdeaPad 320-15ISK 80XH         | 2         | 0.36%   |
| HUAWEI MACH-WX9                       | 2         | 0.36%   |
| HUAWEI HLYL-WXX9                      | 2         | 0.36%   |
| HP ZBook 15 G4                        | 2         | 0.36%   |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 2         | 0.36%   |
| HP Notebook                           | 2         | 0.36%   |
| HP Laptop 15s-eq2xxx                  | 2         | 0.36%   |
| HP Laptop 15-db0xxx                   | 2         | 0.36%   |
| HP Laptop 15-da0xxx                   | 2         | 0.36%   |
| HP ENVY Laptop 13-ba0xxx              | 2         | 0.36%   |
| HP EliteBook 840 G5                   | 2         | 0.36%   |
| HP EliteBook 745 G6                   | 2         | 0.36%   |
| HP 255 G7 Notebook PC                 | 2         | 0.36%   |
| HP 250 G7 Notebook PC                 | 2         | 0.36%   |
| Dell XPS 15 7590                      | 2         | 0.36%   |
| Dell Latitude E6510                   | 2         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 75        | 13.66%  |
| Lenovo IdeaPad     | 38        | 6.92%   |
| ASUS ROG           | 25        | 4.55%   |
| Acer Aspire        | 24        | 4.37%   |
| Dell Latitude      | 22        | 4.01%   |
| Dell Inspiron      | 20        | 3.64%   |
| HP Pavilion        | 18        | 3.28%   |
| HP EliteBook       | 16        | 2.91%   |
| HP Laptop          | 15        | 2.73%   |
| Lenovo Legion      | 11        | 2%      |
| Lenovo ThinkBook   | 10        | 1.82%   |
| ASUS VivoBook      | 10        | 1.82%   |
| MSI Modern         | 8         | 1.46%   |
| Dell Precision     | 7         | 1.28%   |
| ASUS TUF           | 7         | 1.28%   |
| ASUS ASUS          | 7         | 1.28%   |
| Toshiba Satellite  | 6         | 1.09%   |
| Lenovo Yoga        | 6         | 1.09%   |
| HP ENVY            | 6         | 1.09%   |
| Apple MacBookAir7  | 6         | 1.09%   |
| Acer Swift         | 6         | 1.09%   |
| HP 255             | 5         | 0.91%   |
| Dell XPS           | 5         | 0.91%   |
| ASUS ZenBook       | 5         | 0.91%   |
| HP ZBook           | 4         | 0.73%   |
| Unknown            | 4         | 0.73%   |
| Schenker XMG       | 3         | 0.55%   |
| MSI Prestige       | 3         | 0.55%   |
| HUAWEI KLVL-WXX9   | 3         | 0.55%   |
| HP ProBook         | 3         | 0.55%   |
| HP 250             | 3         | 0.55%   |
| Dell G3            | 3         | 0.55%   |
| Apple MacBookPro16 | 3         | 0.55%   |
| Apple MacBookPro14 | 3         | 0.55%   |
| Acer Extensa       | 3         | 0.55%   |
| Timi TM1701        | 2         | 0.36%   |
| Timi RedmiBook     | 2         | 0.36%   |
| Timi A35S          | 2         | 0.36%   |
| Samsung 340XAA     | 2         | 0.36%   |
| Razer Blade        | 2         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 86        | 15.66%  |
| 2020    | 77        | 14.03%  |
| 2019    | 57        | 10.38%  |
| 2022    | 48        | 8.74%   |
| 2018    | 48        | 8.74%   |
| 2017    | 43        | 7.83%   |
| 2015    | 37        | 6.74%   |
| 2016    | 31        | 5.65%   |
| 2013    | 31        | 5.65%   |
| 2012    | 25        | 4.55%   |
| 2014    | 21        | 3.83%   |
| 2011    | 16        | 2.91%   |
| 2010    | 11        | 2%      |
| 2008    | 8         | 1.46%   |
| 2009    | 5         | 0.91%   |
| 2007    | 3         | 0.55%   |
| 2023    | 1         | 0.18%   |
| Unknown | 1         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 549       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 549       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 539       | 98.18%  |
| Yes  | 10        | 1.82%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 165       | 29.95%  |
| 8.01-16.0   | 136       | 24.68%  |
| 16.01-24.0  | 108       | 19.6%   |
| 3.01-4.0    | 61        | 11.07%  |
| 32.01-64.0  | 54        | 9.8%    |
| 24.01-32.0  | 14        | 2.54%   |
| 64.01-256.0 | 7         | 1.27%   |
| 2.01-3.0    | 3         | 0.54%   |
| 1.01-2.0    | 3         | 0.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 160       | 27.12%  |
| 1.01-2.0   | 145       | 24.58%  |
| 4.01-8.0   | 117       | 19.83%  |
| 3.01-4.0   | 111       | 18.81%  |
| 8.01-16.0  | 29        | 4.92%   |
| 0.51-1.0   | 21        | 3.56%   |
| 16.01-24.0 | 4         | 0.68%   |
| 0.01-0.5   | 2         | 0.34%   |
| 24.01-32.0 | 1         | 0.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 389       | 69.71%  |
| 2      | 149       | 26.7%   |
| 3      | 15        | 2.69%   |
| 4      | 3         | 0.54%   |
| 0      | 2         | 0.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 436       | 79.27%  |
| Yes       | 114       | 20.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 406       | 73.55%  |
| No        | 146       | 26.45%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 545       | 99.09%  |
| No        | 5         | 0.91%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 502       | 90.94%  |
| No        | 50        | 9.06%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 117       | 21.16%  |
| Italy       | 51        | 9.22%   |
| Germany     | 41        | 7.41%   |
| Canada      | 23        | 4.16%   |
| Netherlands | 19        | 3.44%   |
| India       | 19        | 3.44%   |
| France      | 18        | 3.25%   |
| UK          | 17        | 3.07%   |
| Poland      | 17        | 3.07%   |
| Brazil      | 17        | 3.07%   |
| Finland     | 15        | 2.71%   |
| Russia      | 14        | 2.53%   |
| Turkey      | 12        | 2.17%   |
| Spain       | 12        | 2.17%   |
| Australia   | 9         | 1.63%   |
| Sweden      | 7         | 1.27%   |
| Mexico      | 7         | 1.27%   |
| Indonesia   | 7         | 1.27%   |
| Ukraine     | 6         | 1.08%   |
| Romania     | 6         | 1.08%   |
| Austria     | 6         | 1.08%   |
| Argentina   | 6         | 1.08%   |
| New Zealand | 5         | 0.9%    |
| Greece      | 5         | 0.9%    |
| Belgium     | 5         | 0.9%    |
| Bangladesh  | 5         | 0.9%    |
| Vietnam     | 4         | 0.72%   |
| Portugal    | 4         | 0.72%   |
| Philippines | 4         | 0.72%   |
| Malaysia    | 4         | 0.72%   |
| Hong Kong   | 4         | 0.72%   |
| Denmark     | 4         | 0.72%   |
| Singapore   | 3         | 0.54%   |
| Serbia      | 3         | 0.54%   |
| Norway      | 3         | 0.54%   |
| Croatia     | 3         | 0.54%   |
| Colombia    | 3         | 0.54%   |
| Bulgaria    | 3         | 0.54%   |
| Bahrain     | 3         | 0.54%   |
| Taiwan      | 2         | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Helsinki          | 11        | 1.91%   |
| Toms River        | 7         | 1.22%   |
| Amsterdam         | 7         | 1.22%   |
| Montreal          | 6         | 1.04%   |
| Sydney            | 5         | 0.87%   |
| Moscow            | 5         | 0.87%   |
| Istanbul          | 5         | 0.87%   |
| Berlin            | 5         | 0.87%   |
| Barberton         | 5         | 0.87%   |
| Warsaw            | 4         | 0.69%   |
| Victoria          | 4         | 0.69%   |
| St Petersburg     | 4         | 0.69%   |
| Rome              | 4         | 0.69%   |
| Portland          | 4         | 0.69%   |
| Paris             | 4         | 0.69%   |
| Milan             | 4         | 0.69%   |
| London            | 4         | 0.69%   |
| Frankfurt am Main | 4         | 0.69%   |
| Singapore         | 3         | 0.52%   |
| Mesa              | 3         | 0.52%   |
| Manama            | 3         | 0.52%   |
| Madrid            | 3         | 0.52%   |
| Jacksonville      | 3         | 0.52%   |
| Ho Chi Minh City  | 3         | 0.52%   |
| Hamburg           | 3         | 0.52%   |
| Greeley           | 3         | 0.52%   |
| Florence          | 3         | 0.52%   |
| Dhaka             | 3         | 0.52%   |
| Dallas            | 3         | 0.52%   |
| Central           | 3         | 0.52%   |
| Brussels          | 3         | 0.52%   |
| Belgrade          | 3         | 0.52%   |
| Bandung           | 3         | 0.52%   |
| Auckland          | 3         | 0.52%   |
| Ankara            | 3         | 0.52%   |
| Zurich            | 2         | 0.35%   |
| Wroclaw           | 2         | 0.35%   |
| Villa Ballester   | 2         | 0.35%   |
| Vienna            | 2         | 0.35%   |
| Turku             | 2         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 161       | 201    | 22.55%  |
| SanDisk                        | 61        | 66     | 8.54%   |
| Seagate                        | 60        | 64     | 8.4%    |
| WDC                            | 48        | 56     | 6.72%   |
| SK hynix                       | 41        | 49     | 5.74%   |
| Kingston                       | 39        | 44     | 5.46%   |
| Micron Technology              | 29        | 29     | 4.06%   |
| Toshiba                        | 25        | 27     | 3.5%    |
| Unknown                        | 24        | 32     | 3.36%   |
| Crucial                        | 21        | 23     | 2.94%   |
| Intel                          | 20        | 22     | 2.8%    |
| HGST                           | 18        | 22     | 2.52%   |
| KIOXIA                         | 16        | 17     | 2.24%   |
| Apple                          | 16        | 20     | 2.24%   |
| A-DATA Technology              | 11        | 13     | 1.54%   |
| Kingston Technology Company    | 8         | 10     | 1.12%   |
| Phison Electronics             | 6         | 6      | 0.84%   |
| Phison                         | 6         | 6      | 0.84%   |
| LITEONIT                       | 6         | 7      | 0.84%   |
| Hitachi                        | 6         | 6      | 0.84%   |
| China                          | 5         | 5      | 0.7%    |
| Mushkin                        | 4         | 4      | 0.56%   |
| Union Memory (Shenzhen)        | 3         | 3      | 0.42%   |
| Transcend                      | 3         | 3      | 0.42%   |
| Solid State Storage Technology | 3         | 4      | 0.42%   |
| PNY                            | 3         | 4      | 0.42%   |
| OCZ                            | 3         | 3      | 0.42%   |
| LITEON                         | 3         | 5      | 0.42%   |
| Lenovo                         | 3         | 3      | 0.42%   |
| Fujitsu                        | 3         | 3      | 0.42%   |
| WDC WDS                        | 2         | 2      | 0.28%   |
| SSSTC                          | 2         | 2      | 0.28%   |
| Silicon Motion                 | 2         | 2      | 0.28%   |
| Shenzhen Longsys Electronics   | 2         | 3      | 0.28%   |
| Patriot                        | 2         | 2      | 0.28%   |
| Netac                          | 2         | 3      | 0.28%   |
| Micron/Crucial Technology      | 2         | 2      | 0.28%   |
| Maxone                         | 2         | 2      | 0.28%   |
| KingSpec                       | 2         | 2      | 0.28%   |
| HFS256G3                       | 2         | 2      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 21        | 2.85%   |
| Seagate ST1000LM035-1RK172 1TB                      | 17        | 2.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 14        | 1.9%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 256GB    | 10        | 1.36%   |
| HGST HTS721010A9E630 1TB                            | 9         | 1.22%   |
| Seagate ST500LT012-1DG142 500GB                     | 7         | 0.95%   |
| Unknown MMC Card  64GB                              | 6         | 0.81%   |
| SK hynix HFM001TD3JX013N 1TB                        | 6         | 0.81%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 6         | 0.81%   |
| Samsung SSD 870 QVO 1TB                             | 6         | 0.81%   |
| Samsung NVMe SSD Drive 512GB                        | 6         | 0.81%   |
| Kingston SA400S37240G 240GB SSD                     | 6         | 0.81%   |
| Apple SSD SM0128G 121GB                             | 6         | 0.81%   |
| Toshiba MQ01ABD100 1TB                              | 5         | 0.68%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB     | 5         | 0.68%   |
| Samsung SSD 970 EVO 500GB                           | 5         | 0.68%   |
| Samsung SSD 870 EVO 250GB                           | 5         | 0.68%   |
| Samsung SSD 860 EVO 500GB                           | 5         | 0.68%   |
| Samsung SSD 860 EVO 250GB                           | 5         | 0.68%   |
| Samsung SSD 860 EVO 1TB                             | 5         | 0.68%   |
| Samsung SSD 850 EVO 500GB                           | 5         | 0.68%   |
| KIOXIA KBG40ZNV512G 512GB                           | 5         | 0.68%   |
| Kingston OM8PCP3512F-AI1 512GB                      | 5         | 0.68%   |
| Unknown MMC Card  128GB                             | 4         | 0.54%   |
| Seagate ST1000LM049-2GH172 1TB                      | 4         | 0.54%   |
| Samsung MZVLQ512HBLU-00B00 512GB                    | 4         | 0.54%   |
| Samsung MZVLQ512HALU-000H1 512GB                    | 4         | 0.54%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB             | 4         | 0.54%   |
| Kingston SA400S37480G 480GB SSD                     | 4         | 0.54%   |
| Kingston OM8PCP3512F-AB 512GB                       | 4         | 0.54%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 3         | 0.41%   |
| WDC WD10SPZX-24Z10 1TB                              | 3         | 0.41%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 3         | 0.41%   |
| Unknown MMC Card  32GB                              | 3         | 0.41%   |
| Unknown MMC Card  16GB                              | 3         | 0.41%   |
| Transcend TS240GMTS420S 240GB SSD                   | 3         | 0.41%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB              | 3         | 0.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 0.41%   |
| SanDisk NVMe SSD Drive 256GB                        | 3         | 0.41%   |
| Samsung SSD 850 EVO 250GB                           | 3         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 56     | 43.09%  |
| WDC                 | 24        | 27     | 19.51%  |
| HGST                | 18        | 22     | 14.63%  |
| Toshiba             | 12        | 12     | 9.76%   |
| Hitachi             | 6         | 6      | 4.88%   |
| Fujitsu             | 3         | 3      | 2.44%   |
| Unknown             | 2         | 2      | 1.63%   |
| Maxone              | 2         | 2      | 1.63%   |
| USB3.0              | 1         | 1      | 0.81%   |
| Samsung Electronics | 1         | 1      | 0.81%   |
| Generic-            | 1         | 1      | 0.81%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 70        | 88     | 28.57%  |
| Kingston            | 25        | 30     | 10.2%   |
| Crucial             | 19        | 20     | 7.76%   |
| SanDisk             | 18        | 19     | 7.35%   |
| WDC                 | 14        | 18     | 5.71%   |
| Apple               | 10        | 10     | 4.08%   |
| A-DATA Technology   | 8         | 9      | 3.27%   |
| SK hynix            | 7         | 8      | 2.86%   |
| Micron Technology   | 6         | 6      | 2.45%   |
| LITEONIT            | 6         | 7      | 2.45%   |
| Toshiba             | 5         | 5      | 2.04%   |
| China               | 5         | 5      | 2.04%   |
| Seagate             | 4         | 4      | 1.63%   |
| Intel               | 4         | 4      | 1.63%   |
| Transcend           | 3         | 3      | 1.22%   |
| OCZ                 | 3         | 3      | 1.22%   |
| Mushkin             | 3         | 3      | 1.22%   |
| WDC WDS             | 2         | 2      | 0.82%   |
| PNY                 | 2         | 3      | 0.82%   |
| Patriot             | 2         | 2      | 0.82%   |
| Netac               | 2         | 3      | 0.82%   |
| LITEON              | 2         | 3      | 0.82%   |
| KingSpec            | 2         | 2      | 0.82%   |
| Gigabyte Technology | 2         | 3      | 0.82%   |
| Corsair             | 2         | 2      | 0.82%   |
| Zheino              | 1         | 1      | 0.41%   |
| WALTON              | 1         | 2      | 0.41%   |
| V-GeN               | 1         | 1      | 0.41%   |
| Unknown             | 1         | 2      | 0.41%   |
| Teclast             | 1         | 3      | 0.41%   |
| Team                | 1         | 2      | 0.41%   |
| StoreJet            | 1         | 1      | 0.41%   |
| SPCC                | 1         | 1      | 0.41%   |
| OCZ-VERTEX          | 1         | 1      | 0.41%   |
| KingFast            | 1         | 1      | 0.41%   |
| KingDian            | 1         | 1      | 0.41%   |
| KINGBANK            | 1         | 1      | 0.41%   |
| HS-SSD-C100         | 1         | 1      | 0.41%   |
| GOODRAM             | 1         | 1      | 0.41%   |
| FORESEE             | 1         | 1      | 0.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 294       | 368    | 44.82%  |
| SSD     | 213       | 286    | 32.47%  |
| HDD     | 119       | 133    | 18.14%  |
| MMC     | 23        | 30     | 3.51%   |
| Unknown | 7         | 7      | 1.07%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 294       | 365    | 46.45%  |
| SATA | 287       | 390    | 45.34%  |
| SAS  | 29        | 39     | 4.58%   |
| MMC  | 23        | 30     | 3.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 212       | 288    | 64.44%  |
| 0.51-1.0   | 105       | 118    | 31.91%  |
| 1.01-2.0   | 11        | 12     | 3.34%   |
| 4.01-10.0  | 1         | 1      | 0.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 141       | 24.87%  |
| 251-500        | 116       | 20.46%  |
| 501-1000       | 78        | 13.76%  |
| 1001-2000      | 74        | 13.05%  |
| Unknown        | 40        | 7.05%   |
| 1-20           | 34        | 6%      |
| 51-100         | 28        | 4.94%   |
| More than 3000 | 26        | 4.59%   |
| 21-50          | 16        | 2.82%   |
| 2001-3000      | 14        | 2.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 153       | 26.11%  |
| 21-50          | 108       | 18.43%  |
| 101-250        | 95        | 16.21%  |
| 51-100         | 76        | 12.97%  |
| 251-500        | 52        | 8.87%   |
| Unknown        | 40        | 6.83%   |
| 501-1000       | 31        | 5.29%   |
| 1001-2000      | 21        | 3.58%   |
| More than 3000 | 4         | 0.68%   |
| 0              | 4         | 0.68%   |
| 2001-3000      | 2         | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                                        | 3         | 3      | 7.69%   |
| HGST HTS545050A7E680 500GB                                      | 3         | 5      | 7.69%   |
| Hitachi HTS545050A7E380 500GB                                   | 2         | 2      | 5.13%   |
| WDC WD5000LPVT-22G33T0 500GB                                    | 1         | 1      | 2.56%   |
| WDC WD10SPZX-24Z10T0 1TB                                        | 1         | 1      | 2.56%   |
| WDC WD10JPVX-22JC3T0 1TB                                        | 1         | 1      | 2.56%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB                            | 1         | 1      | 2.56%   |
| Transcend TS240GMTS420S 240GB SSD                               | 1         | 1      | 2.56%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD                        | 1         | 1      | 2.56%   |
| Toshiba MQ01ABD100 1TB                                          | 1         | 1      | 2.56%   |
| Toshiba MK5055GSXF 500GB                                        | 1         | 1      | 2.56%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD                         | 1         | 1      | 2.56%   |
| SK hynix SC308 SATA 128GB SSD                                   | 1         | 1      | 2.56%   |
| SK hynix HFS512G39TND-N210A 512GB SSD                           | 1         | 1      | 2.56%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                           | 1         | 1      | 2.56%   |
| Seagate ST9320325AS 320GB                                       | 1         | 1      | 2.56%   |
| Seagate ST500LX012-SSHD-8GB                                     | 1         | 1      | 2.56%   |
| Seagate ST500LT012-1DG142 500GB                                 | 1         | 1      | 2.56%   |
| Seagate ST2000LX001-1RG174 2TB                                  | 1         | 1      | 2.56%   |
| Seagate ST1000LM049-2GH172 1TB                                  | 1         | 1      | 2.56%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 1         | 1      | 2.56%   |
| SanDisk SSD PLUS 240GB                                          | 1         | 1      | 2.56%   |
| SanDisk SD8SNAT128G1002 128GB SSD                               | 1         | 1      | 2.56%   |
| Samsung Electronics SSD 980 1TB                                 | 1         | 1      | 2.56%   |
| Samsung Electronics SSD 970 EVO 500GB                           | 1         | 1      | 2.56%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 2.56%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD                | 1         | 1      | 2.56%   |
| Kingston SNS4151S332GD 32GB SSD                                 | 1         | 1      | 2.56%   |
| Intel SSDSCKKF256H6 SATA 256GB                                  | 1         | 1      | 2.56%   |
| Intel SSDSCKJF180A5L 180GB                                      | 1         | 1      | 2.56%   |
| Fujitsu MHZ2320BH G2 320GB                                      | 1         | 1      | 2.56%   |
| Apple SSD TS128E 121GB                                          | 1         | 1      | 2.56%   |
| Apple SSD SM256C 256GB                                          | 1         | 1      | 2.56%   |
| A-DATA Technology SP900 256GB SSD                               | 1         | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 15.38%  |
| HGST                | 6         | 8      | 15.38%  |
| WDC                 | 4         | 4      | 10.26%  |
| Toshiba             | 4         | 4      | 10.26%  |
| Samsung Electronics | 4         | 4      | 10.26%  |
| SK hynix            | 3         | 3      | 7.69%   |
| SanDisk             | 2         | 2      | 5.13%   |
| Intel               | 2         | 2      | 5.13%   |
| Hitachi             | 2         | 2      | 5.13%   |
| Apple               | 2         | 2      | 5.13%   |
| Transcend           | 1         | 1      | 2.56%   |
| Kingston            | 1         | 1      | 2.56%   |
| Fujitsu             | 1         | 1      | 2.56%   |
| A-DATA Technology   | 1         | 1      | 2.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 30%     |
| HGST    | 6         | 8      | 30%     |
| WDC     | 3         | 3      | 15%     |
| Toshiba | 2         | 2      | 10%     |
| Hitachi | 2         | 2      | 10%     |
| Fujitsu | 1         | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 22     | 51.28%  |
| SSD  | 16        | 16     | 41.03%  |
| NVMe | 3         | 3      | 7.69%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                  | Notebooks | Drives | Percent |
|------------------------|-----------|--------|---------|
| LITEON CA3-8D512 512GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| LITEON | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 379       | 516    | 63.7%   |
| Detected | 177       | 265    | 29.75%  |
| Malfunc  | 38        | 41     | 6.39%   |
| Failed   | 1         | 2      | 0.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 305       | 43.88%  |
| Samsung Electronics            | 103       | 14.82%  |
| AMD                            | 79        | 11.37%  |
| SanDisk                        | 51        | 7.34%   |
| SK hynix                       | 33        | 4.75%   |
| Micron Technology              | 23        | 3.31%   |
| Kingston Technology Company    | 22        | 3.17%   |
| KIOXIA                         | 19        | 2.73%   |
| Phison Electronics             | 13        | 1.87%   |
| Solid State Storage Technology | 6         | 0.86%   |
| Apple                          | 6         | 0.86%   |
| Toshiba America Info Systems   | 5         | 0.72%   |
| Micron/Crucial Technology      | 4         | 0.58%   |
| ADATA Technology               | 4         | 0.58%   |
| Union Memory (Shenzhen)        | 3         | 0.43%   |
| Seagate Technology             | 3         | 0.43%   |
| Lenovo                         | 3         | 0.43%   |
| Silicon Motion                 | 2         | 0.29%   |
| Shenzhen Longsys Electronics   | 2         | 0.29%   |
| Lite-On Technology             | 2         | 0.29%   |
| Yangtze Memory Technologies    | 1         | 0.14%   |
| Realtek Semiconductor          | 1         | 0.14%   |
| Nvidia                         | 1         | 0.14%   |
| Marvell Technology Group       | 1         | 0.14%   |
| JMicron Technology             | 1         | 0.14%   |
| INNOGRIT                       | 1         | 0.14%   |
| Biwin Storage Technology       | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 77        | 10.69%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 52        | 7.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 47        | 6.53%   |
| Samsung NVMe SSD Controller 980                                                | 28        | 3.89%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 26        | 3.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 25        | 3.47%   |
| Micron NVMe Storage Controller                                                 | 21        | 2.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 21        | 2.92%   |
| Intel Volume Management Device NVMe RAID Controller                            | 19        | 2.64%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 18        | 2.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 17        | 2.36%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 16        | 2.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 15        | 2.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 15        | 2.08%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 14        | 1.94%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 14        | 1.94%   |
| Intel Tiger Lake-LP SATA Controller                                            | 13        | 1.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13        | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 1.81%   |
| Kingston Company Company Non-Volatile memory controller                        | 12        | 1.67%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 10        | 1.39%   |
| Intel SSD 660P Series                                                          | 10        | 1.39%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 10        | 1.39%   |
| Intel Comet Lake SATA AHCI Controller                                          | 9         | 1.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 0.97%   |
| Solid State Storage Non-Volatile memory controller                             | 6         | 0.83%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 6         | 0.83%   |
| SanDisk Non-Volatile memory controller                                         | 6         | 0.83%   |
| Samsung Electronics SATA controller                                            | 6         | 0.83%   |
| Phison E12 NVMe Controller                                                     | 6         | 0.83%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 6         | 0.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 6         | 0.83%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 0.83%   |
| SK hynix Non-Volatile memory controller                                        | 5         | 0.69%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 5         | 0.69%   |
| SanDisk NVMe Controller                                                        | 5         | 0.69%   |
| KIOXIA Non-Volatile memory controller                                          | 5         | 0.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 0.69%   |
| SK hynix BC511                                                                 | 4         | 0.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 343       | 49.85%  |
| NVMe | 292       | 42.44%  |
| RAID | 47        | 6.83%   |
| IDE  | 6         | 0.87%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 383       | 69.76%  |
| AMD    | 165       | 30.05%  |
| ARM    | 1         | 0.18%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 11        | 2%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 11        | 2%      |
| AMD Ryzen 7 5800H with Radeon Graphics        | 11        | 2%      |
| AMD Ryzen 7 4800H with Radeon Graphics        | 11        | 2%      |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 1.82%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 1.64%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 9         | 1.64%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 9         | 1.64%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 9         | 1.64%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 1.64%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 8         | 1.46%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 1.46%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 1.46%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 1.28%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 1.28%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 1.28%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 1.28%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 7         | 1.28%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 7         | 1.28%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 1.09%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 1.09%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 1.09%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 6         | 1.09%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 6         | 1.09%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 6         | 1.09%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 5         | 0.91%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.91%   |
| Intel 12th Gen Core i7-12700H                 | 5         | 0.91%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 5         | 0.91%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 5         | 0.91%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 5         | 0.91%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 0.91%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 5         | 0.91%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 4         | 0.73%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 0.73%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 4         | 0.73%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 0.73%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 4         | 0.73%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 0.73%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 4         | 0.73%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 138       | 25.14%  |
| Intel Core i7           | 116       | 21.13%  |
| Other                   | 60        | 10.93%  |
| AMD Ryzen 7             | 57        | 10.38%  |
| AMD Ryzen 5             | 46        | 8.38%   |
| Intel Core i3           | 29        | 5.28%   |
| Intel Celeron           | 20        | 3.64%   |
| AMD Ryzen 9             | 16        | 2.91%   |
| AMD Ryzen 7 PRO         | 13        | 2.37%   |
| Intel Core 2 Duo        | 12        | 2.19%   |
| AMD A4                  | 8         | 1.46%   |
| AMD Ryzen 3             | 5         | 0.91%   |
| Intel Pentium           | 4         | 0.73%   |
| AMD Ryzen 5 PRO         | 3         | 0.55%   |
| AMD A8                  | 3         | 0.55%   |
| AMD A10                 | 3         | 0.55%   |
| Intel Xeon              | 2         | 0.36%   |
| Intel Core m3           | 2         | 0.36%   |
| Intel Atom              | 2         | 0.36%   |
| AMD E1                  | 2         | 0.36%   |
| AMD Athlon              | 2         | 0.36%   |
| Intel Pentium Dual-Core | 1         | 0.18%   |
| Intel Core m5           | 1         | 0.18%   |
| Intel Core 2 Extreme    | 1         | 0.18%   |
| Intel Core 2            | 1         | 0.18%   |
| AMD E                   | 1         | 0.18%   |
| AMD Athlon II           | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 201       | 36.61%  |
| 4      | 186       | 33.88%  |
| 8      | 91        | 16.58%  |
| 6      | 56        | 10.2%   |
| 14     | 9         | 1.64%   |
| 12     | 3         | 0.55%   |
| 10     | 2         | 0.36%   |
| 1      | 1         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 548       | 99.82%  |
| 2      | 1         | 0.18%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 471       | 85.79%  |
| 1      | 78        | 14.21%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 547       | 99.64%  |
| 64-bit         | 1         | 0.18%   |
| Unknown        | 1         | 0.18%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 198       | 35.48%  |
| 0x0a50000c | 26        | 4.66%   |
| 0x806ec    | 18        | 3.23%   |
| 0x406e3    | 18        | 3.23%   |
| 0x306a9    | 16        | 2.87%   |
| 0x806ea    | 15        | 2.69%   |
| 0x806c1    | 15        | 2.69%   |
| 0x40651    | 15        | 2.69%   |
| 0x08600106 | 14        | 2.51%   |
| 0x906ea    | 13        | 2.33%   |
| 0x806e9    | 13        | 2.33%   |
| 0x08600104 | 13        | 2.33%   |
| 0x306c3    | 12        | 2.15%   |
| 0x08108109 | 12        | 2.15%   |
| 0x08608103 | 10        | 1.79%   |
| 0x906e9    | 9         | 1.61%   |
| 0x506e3    | 9         | 1.61%   |
| 0x306d4    | 9         | 1.61%   |
| 0x206a7    | 9         | 1.61%   |
| 0x08108102 | 9         | 1.61%   |
| 0x706e5    | 7         | 1.25%   |
| 0xa0652    | 6         | 1.08%   |
| 0x906a3    | 6         | 1.08%   |
| 0x806d1    | 6         | 1.08%   |
| 0x406c4    | 6         | 1.08%   |
| 0x1067a    | 6         | 1.08%   |
| 0x0a404102 | 6         | 1.08%   |
| 0x706a1    | 5         | 0.9%    |
| 0x20655    | 5         | 0.9%    |
| 0x0a50000d | 5         | 0.9%    |
| 0x06006705 | 5         | 0.9%    |
| 0x0a404101 | 3         | 0.54%   |
| 0x906ed    | 2         | 0.36%   |
| 0x906c0    | 2         | 0.36%   |
| 0x806eb    | 2         | 0.36%   |
| 0x406c3    | 2         | 0.36%   |
| 0x10676    | 2         | 0.36%   |
| 0x0a50000b | 2         | 0.36%   |
| 0x08608102 | 2         | 0.36%   |
| 0x08600103 | 2         | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 119       | 21.68%  |
| Zen 2            | 42        | 7.65%   |
| Zen 3            | 40        | 7.29%   |
| Haswell          | 40        | 7.29%   |
| Skylake          | 36        | 6.56%   |
| Unknown          | 36        | 6.56%   |
| TigerLake        | 30        | 5.46%   |
| Zen+             | 28        | 5.1%    |
| IvyBridge        | 28        | 5.1%    |
| Broadwell        | 21        | 3.83%   |
| IceLake          | 17        | 3.1%    |
| SandyBridge      | 15        | 2.73%   |
| Alderlake Hybrid | 13        | 2.37%   |
| Silvermont       | 12        | 2.19%   |
| Penryn           | 12        | 2.19%   |
| CometLake        | 12        | 2.19%   |
| Westmere         | 10        | 1.82%   |
| Excavator        | 10        | 1.82%   |
| Jaguar           | 6         | 1.09%   |
| Goldmont plus    | 6         | 1.09%   |
| Piledriver       | 3         | 0.55%   |
| Core             | 3         | 0.55%   |
| Zen              | 2         | 0.36%   |
| Tremont          | 2         | 0.36%   |
| Puma             | 2         | 0.36%   |
| Goldmont         | 2         | 0.36%   |
| K10              | 1         | 0.18%   |
| Bobcat           | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 358       | 49.65%  |
| AMD    | 182       | 25.24%  |
| Nvidia | 181       | 25.1%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 41        | 5.54%   |
| Intel UHD Graphics 620                                                                   | 29        | 3.92%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 29        | 3.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 28        | 3.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 26        | 3.51%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 25        | 3.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 3.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 22        | 2.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 21        | 2.84%   |
| Intel HD Graphics 620                                                                    | 18        | 2.43%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 16        | 2.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 16        | 2.16%   |
| Intel HD Graphics 5500                                                                   | 15        | 2.03%   |
| AMD Rembrandt [Radeon 680M]                                                              | 15        | 2.03%   |
| AMD Lucienne                                                                             | 15        | 2.03%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 13        | 1.76%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 1.76%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 12        | 1.62%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 12        | 1.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 1.62%   |
| Intel HD Graphics 630                                                                    | 11        | 1.49%   |
| Nvidia GP108M [GeForce MX150]                                                            | 10        | 1.35%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 1.35%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 1.35%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 1.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1.22%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 8         | 1.08%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 8         | 1.08%   |
| Intel HD Graphics 530                                                                    | 8         | 1.08%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 8         | 1.08%   |
| AMD Barcelo                                                                              | 7         | 0.95%   |
| Nvidia GM108M [GeForce 940M]                                                             | 6         | 0.81%   |
| Intel HD Graphics 6000                                                                   | 6         | 0.81%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.81%   |
| Nvidia TU117M                                                                            | 5         | 0.68%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.68%   |
| Nvidia GP108M [GeForce MX250]                                                            | 5         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 0.68%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 5         | 0.68%   |
| Intel Iris Plus Graphics G7                                                              | 5         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 218       | 39.71%  |
| Intel + Nvidia | 124       | 22.59%  |
| 1 x AMD        | 117       | 21.31%  |
| AMD + Nvidia   | 34        | 6.19%   |
| 1 x Nvidia     | 22        | 4.01%   |
| 2 x AMD        | 17        | 3.1%    |
| Intel + AMD    | 14        | 2.55%   |
| 2 x Intel      | 2         | 0.36%   |
| Other          | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 421       | 76.55%  |
| Proprietary | 128       | 23.27%  |
| Unknown     | 1         | 0.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 366       | 65.83%  |
| 0.01-0.5   | 80        | 14.39%  |
| 1.01-2.0   | 43        | 7.73%   |
| 3.01-4.0   | 24        | 4.32%   |
| 0.51-1.0   | 17        | 3.06%   |
| 7.01-8.0   | 10        | 1.8%    |
| 5.01-6.0   | 9         | 1.62%   |
| 2.01-3.0   | 6         | 1.08%   |
| 8.01-16.0  | 1         | 0.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 132       | 20.12%  |
| BOE                     | 99        | 15.09%  |
| Chimei Innolux          | 93        | 14.18%  |
| LG Display              | 73        | 11.13%  |
| Samsung Electronics     | 47        | 7.16%   |
| PANDA                   | 22        | 3.35%   |
| Apple                   | 19        | 2.9%    |
| Sharp                   | 17        | 2.59%   |
| Goldstar                | 17        | 2.59%   |
| Dell                    | 16        | 2.44%   |
| Lenovo                  | 13        | 1.98%   |
| Acer                    | 11        | 1.68%   |
| InfoVision              | 9         | 1.37%   |
| AOC                     | 9         | 1.37%   |
| Philips                 | 8         | 1.22%   |
| BenQ                    | 7         | 1.07%   |
| TMX                     | 6         | 0.91%   |
| Ancor Communications    | 6         | 0.91%   |
| CSO                     | 5         | 0.76%   |
| Chi Mei Optoelectronics | 5         | 0.76%   |
| ViewSonic               | 4         | 0.61%   |
| Sony                    | 3         | 0.46%   |
| Pixio                   | 3         | 0.46%   |
| LG Philips              | 3         | 0.46%   |
| JDI                     | 3         | 0.46%   |
| Hewlett-Packard         | 3         | 0.46%   |
| Toshiba                 | 2         | 0.3%    |
| InnoLux Display         | 2         | 0.3%    |
| Iiyama                  | 2         | 0.3%    |
| ASUSTek Computer        | 2         | 0.3%    |
| Vizio                   | 1         | 0.15%   |
| Unknown (XXX)           | 1         | 0.15%   |
| Unknown                 | 1         | 0.15%   |
| Sun                     | 1         | 0.15%   |
| RTK                     | 1         | 0.15%   |
| Panasonic               | 1         | 0.15%   |
| MSI                     | 1         | 0.15%   |
| HUAWEI                  | 1         | 0.15%   |
| HKC                     | 1         | 0.15%   |
| Hitachi                 | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 8         | 1.21%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 1.21%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 7         | 1.06%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 7         | 1.06%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 6         | 0.9%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 6         | 0.9%    |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 5         | 0.75%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 4         | 0.6%    |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 4         | 0.6%    |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 4         | 0.6%    |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 4         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 4         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 4         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 4         | 0.6%    |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 4         | 0.6%    |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch               | 3         | 0.45%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 3         | 0.45%   |
| Pixio U29I WAM2900 2560x1080 690x260mm 29.0-inch                      | 3         | 0.45%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 3         | 0.45%   |
| LG Display LCD Monitor LGD065B 1920x1080 382x215mm 17.3-inch          | 3         | 0.45%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 3         | 0.45%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 3         | 0.45%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3         | 0.45%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch      | 3         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 3         | 0.45%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 3         | 0.45%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 0.45%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 3         | 0.45%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 3         | 0.45%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                 | 3         | 0.45%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 3         | 0.45%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 3         | 0.45%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 3         | 0.45%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO499F 1920x1080 344x194mm 15.5-inch        | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch         | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch         | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 3         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 318       | 51.71%  |
| 1366x768 (WXGA)    | 127       | 20.65%  |
| 2560x1440 (QHD)    | 29        | 4.72%   |
| 3840x2160 (4K)     | 23        | 3.74%   |
| 2560x1600          | 20        | 3.25%   |
| 1440x900 (WXGA+)   | 16        | 2.6%    |
| 2880x1800          | 11        | 1.79%   |
| 1920x1200 (WUXGA)  | 9         | 1.46%   |
| 1280x800 (WXGA)    | 8         | 1.3%    |
| 2160x1440          | 7         | 1.14%   |
| 1600x900 (HD+)     | 7         | 1.14%   |
| 2560x1080          | 6         | 0.98%   |
| 3840x2400          | 5         | 0.81%   |
| 3440x1440          | 4         | 0.65%   |
| 3200x2000          | 4         | 0.65%   |
| 1680x1050 (WSXGA+) | 3         | 0.49%   |
| 3456x2160          | 2         | 0.33%   |
| 3200x1800 (QHD+)   | 2         | 0.33%   |
| 3000x2000          | 2         | 0.33%   |
| 1360x768           | 2         | 0.33%   |
| 1280x1024 (SXGA)   | 2         | 0.33%   |
| 3840x1100          | 1         | 0.16%   |
| 3840x1080          | 1         | 0.16%   |
| 3072x1920          | 1         | 0.16%   |
| 2520x1680          | 1         | 0.16%   |
| 2256x1504          | 1         | 0.16%   |
| 2240x1400          | 1         | 0.16%   |
| 1920x1280          | 1         | 0.16%   |
| Unknown            | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 256       | 38.67%  |
| 13      | 102       | 15.41%  |
| 14      | 87        | 13.14%  |
| 17      | 37        | 5.59%   |
| 27      | 29        | 4.38%   |
| 24      | 20        | 3.02%   |
| 16      | 17        | 2.57%   |
| 23      | 16        | 2.42%   |
| 12      | 15        | 2.27%   |
| 21      | 13        | 1.96%   |
| 31      | 10        | 1.51%   |
| 11      | 10        | 1.51%   |
| 18      | 7         | 1.06%   |
| 34      | 5         | 0.76%   |
| 54      | 3         | 0.45%   |
| 29      | 3         | 0.45%   |
| Unknown | 3         | 0.45%   |
| 58      | 2         | 0.3%    |
| 40      | 2         | 0.3%    |
| 35      | 2         | 0.3%    |
| 26      | 2         | 0.3%    |
| 25      | 2         | 0.3%    |
| 22      | 2         | 0.3%    |
| 20      | 2         | 0.3%    |
| 10      | 2         | 0.3%    |
| 84      | 1         | 0.15%   |
| 74      | 1         | 0.15%   |
| 72      | 1         | 0.15%   |
| 65      | 1         | 0.15%   |
| 57      | 1         | 0.15%   |
| 52      | 1         | 0.15%   |
| 49      | 1         | 0.15%   |
| 46      | 1         | 0.15%   |
| 42      | 1         | 0.15%   |
| 32      | 1         | 0.15%   |
| 28      | 1         | 0.15%   |
| 19      | 1         | 0.15%   |
| 8       | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 400       | 61.07%  |
| 201-300     | 80        | 12.21%  |
| 501-600     | 66        | 10.08%  |
| 351-400     | 45        | 6.87%   |
| 401-500     | 24        | 3.66%   |
| 601-700     | 14        | 2.14%   |
| 1001-1500   | 8         | 1.22%   |
| 701-800     | 6         | 0.92%   |
| 801-900     | 4         | 0.61%   |
| 1501-2000   | 3         | 0.46%   |
| Unknown     | 3         | 0.46%   |
| 101-200     | 1         | 0.15%   |
| 901-1000    | 1         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 462       | 81.34%  |
| 16/10   | 76        | 13.38%  |
| 3/2     | 13        | 2.29%   |
| 21/9    | 7         | 1.23%   |
| 2.65    | 3         | 0.53%   |
| 4/3     | 2         | 0.35%   |
| Unknown | 2         | 0.35%   |
| 5/4     | 1         | 0.18%   |
| 3.40    | 1         | 0.18%   |
| 0.62    | 1         | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 256       | 38.96%  |
| 81-90          | 150       | 22.83%  |
| 201-250        | 41        | 6.24%   |
| 71-80          | 38        | 5.78%   |
| 121-130        | 33        | 5.02%   |
| 301-350        | 31        | 4.72%   |
| 351-500        | 19        | 2.89%   |
| 111-120        | 17        | 2.59%   |
| 61-70          | 13        | 1.98%   |
| 51-60          | 11        | 1.67%   |
| More than 1000 | 10        | 1.52%   |
| 251-300        | 9         | 1.37%   |
| 141-150        | 7         | 1.07%   |
| 151-200        | 6         | 0.91%   |
| 131-140        | 4         | 0.61%   |
| 501-1000       | 4         | 0.61%   |
| Unknown        | 3         | 0.46%   |
| 41-50          | 2         | 0.3%    |
| 91-100         | 2         | 0.3%    |
| 1-40           | 1         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 306       | 47.52%  |
| 101-120       | 141       | 21.89%  |
| 51-100        | 79        | 12.27%  |
| 161-240       | 73        | 11.34%  |
| More than 240 | 32        | 4.97%   |
| 1-50          | 10        | 1.55%   |
| Unknown       | 3         | 0.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 440       | 78.85%  |
| 2     | 108       | 19.35%  |
| 3     | 8         | 1.43%   |
| 0     | 2         | 0.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 324       | 37.41%  |
| Realtek Semiconductor             | 311       | 35.91%  |
| Qualcomm Atheros                  | 85        | 9.82%   |
| MediaTek                          | 36        | 4.16%   |
| Broadcom                          | 29        | 3.35%   |
| Broadcom Limited                  | 11        | 1.27%   |
| ASIX Electronics                  | 10        | 1.15%   |
| TP-Link                           | 7         | 0.81%   |
| D-Link                            | 7         | 0.81%   |
| Lenovo                            | 4         | 0.46%   |
| Hewlett-Packard                   | 4         | 0.46%   |
| Sierra Wireless                   | 3         | 0.35%   |
| Ralink                            | 3         | 0.35%   |
| DisplayLink                       | 3         | 0.35%   |
| Cypress Semiconductor             | 3         | 0.35%   |
| Apple                             | 3         | 0.35%   |
| Samsung Electronics               | 2         | 0.23%   |
| Qualcomm                          | 2         | 0.23%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.23%   |
| Huawei Technologies               | 2         | 0.23%   |
| Ericsson Business Mobile Networks | 2         | 0.23%   |
| Dell                              | 2         | 0.23%   |
| ZyXEL Communications              | 1         | 0.12%   |
| OPPO Electronics                  | 1         | 0.12%   |
| NetGear                           | 1         | 0.12%   |
| Microsoft                         | 1         | 0.12%   |
| Marvell Technology Group          | 1         | 0.12%   |
| Linksys                           | 1         | 0.12%   |
| ICS Advent                        | 1         | 0.12%   |
| Google                            | 1         | 0.12%   |
| Fibocom                           | 1         | 0.12%   |
| D-Link System                     | 1         | 0.12%   |
| Belkin Components                 | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 212       | 20.68%  |
| Intel Wi-Fi 6 AX200                                               | 50        | 4.88%   |
| Intel Wireless 8265 / 8275                                        | 31        | 3.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 2.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 29        | 2.83%   |
| Intel Wireless 7265                                               | 23        | 2.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 22        | 2.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 21        | 2.05%   |
| Intel Wireless 7260                                               | 21        | 2.05%   |
| Intel Wi-Fi 6 AX201                                               | 21        | 2.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19        | 1.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 17        | 1.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 15        | 1.46%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 14        | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 14        | 1.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 1.37%   |
| Intel Wireless 8260                                               | 13        | 1.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 13        | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 12        | 1.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 1.07%   |
| Intel Wireless 3165                                               | 11        | 1.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 0.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 10        | 0.98%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 9         | 0.88%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 0.88%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                             | 9         | 0.88%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 0.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 8         | 0.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8         | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 0.78%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 8         | 0.78%   |
| Broadcom BCM43142 802.11b/g/n                                     | 8         | 0.78%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 7         | 0.68%   |
| Realtek 802.11ac NIC                                              | 7         | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 7         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 6         | 0.59%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 0.59%   |
| Intel Wireless-AC 9260                                            | 6         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 320       | 55.36%  |
| Realtek Semiconductor | 89        | 15.4%   |
| Qualcomm Atheros      | 73        | 12.63%  |
| MediaTek              | 35        | 6.06%   |
| Broadcom              | 23        | 3.98%   |
| Broadcom Limited      | 11        | 1.9%    |
| D-Link                | 7         | 1.21%   |
| TP-Link               | 5         | 0.87%   |
| Sierra Wireless       | 3         | 0.52%   |
| Ralink                | 3         | 0.52%   |
| Qualcomm              | 2         | 0.35%   |
| ZyXEL Communications  | 1         | 0.17%   |
| Microsoft             | 1         | 0.17%   |
| Linksys               | 1         | 0.17%   |
| Fibocom               | 1         | 0.17%   |
| Dell                  | 1         | 0.17%   |
| D-Link System         | 1         | 0.17%   |
| Belkin Components     | 1         | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 50        | 8.56%   |
| Intel Wireless 8265 / 8275                                     | 31        | 5.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 29        | 4.97%   |
| Intel Wireless 7265                                            | 23        | 3.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 22        | 3.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 21        | 3.6%    |
| Intel Wireless 7260                                            | 21        | 3.6%    |
| Intel Wi-Fi 6 AX201                                            | 21        | 3.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 17        | 2.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 15        | 2.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 14        | 2.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 14        | 2.4%    |
| Intel Wireless 8260                                            | 13        | 2.23%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 13        | 2.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 12        | 2.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 1.88%   |
| Intel Wireless 3165                                            | 11        | 1.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 10        | 1.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 10        | 1.71%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 9         | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 9         | 1.54%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 8         | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 1.37%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 8         | 1.37%   |
| Broadcom BCM43142 802.11b/g/n                                  | 8         | 1.37%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 7         | 1.2%    |
| Realtek 802.11ac NIC                                           | 7         | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 7         | 1.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 1.03%   |
| Intel Wireless-AC 9260                                         | 6         | 1.03%   |
| Intel Wireless 3160                                            | 6         | 1.03%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 6         | 1.03%   |
| D-Link 802.11ac NIC                                            | 6         | 1.03%   |
| TP-Link 802.11ac NIC                                           | 5         | 0.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 0.86%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 5         | 0.86%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 5         | 0.86%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 0.86%   |
| Intel Centrino Advanced-N 6200                                 | 5         | 0.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 271       | 63.92%  |
| Intel                         | 89        | 20.99%  |
| Qualcomm Atheros              | 22        | 5.19%   |
| ASIX Electronics              | 10        | 2.36%   |
| Broadcom                      | 9         | 2.12%   |
| Lenovo                        | 3         | 0.71%   |
| DisplayLink                   | 3         | 0.71%   |
| Cypress Semiconductor         | 3         | 0.71%   |
| Apple                         | 3         | 0.71%   |
| TP-Link                       | 2         | 0.47%   |
| Samsung Electronics           | 1         | 0.24%   |
| OPPO Electronics              | 1         | 0.24%   |
| OnePlus Technology (Shenzhen) | 1         | 0.24%   |
| NetGear                       | 1         | 0.24%   |
| MediaTek                      | 1         | 0.24%   |
| Marvell Technology Group      | 1         | 0.24%   |
| ICS Advent                    | 1         | 0.24%   |
| Hewlett-Packard               | 1         | 0.24%   |
| Google                        | 1         | 0.24%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 212       | 49.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 6.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19        | 4.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 3.26%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 2.09%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 2.09%   |
| Intel Ethernet Connection (4) I219-LM                             | 9         | 2.09%   |
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 2.09%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8         | 1.86%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 1.4%    |
| Intel Ethernet Connection (4) I219-V                              | 6         | 1.4%    |
| Intel 82577LM Gigabit Network Connection                          | 6         | 1.4%    |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.16%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.93%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.93%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.93%   |
| Realtek PCIe GbE Family Controller                                | 3         | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.7%    |
| Intel Ethernet Connection (16) I219-V                             | 3         | 0.7%    |
| Cypress K38231_03                                                 | 3         | 0.7%    |
| Apple iBridge                                                     | 3         | 0.7%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.47%   |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]       | 2         | 0.47%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.47%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.47%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.47%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.47%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 0.47%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.47%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 0.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.47%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.47%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.23%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1         | 0.23%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.23%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 545       | 56.83%  |
| Ethernet | 403       | 42.02%  |
| Modem    | 10        | 1.04%   |
| Unknown  | 1         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 489       | 84.17%  |
| Ethernet | 92        | 15.83%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 364       | 66.18%  |
| 1     | 176       | 32%     |
| 3     | 6         | 1.09%   |
| 0     | 4         | 0.73%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 436       | 78.28%  |
| Yes  | 121       | 21.72%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 282       | 54.86%  |
| Realtek Semiconductor           | 57        | 11.09%  |
| Qualcomm Atheros Communications | 34        | 6.61%   |
| IMC Networks                    | 25        | 4.86%   |
| Lite-On Technology              | 23        | 4.47%   |
| Foxconn / Hon Hai               | 22        | 4.28%   |
| Broadcom                        | 19        | 3.7%    |
| Apple                           | 13        | 2.53%   |
| Realtek                         | 7         | 1.36%   |
| Cambridge Silicon Radio         | 6         | 1.17%   |
| MediaTek                        | 5         | 0.97%   |
| Dell                            | 5         | 0.97%   |
| Toshiba                         | 3         | 0.58%   |
| Ralink                          | 3         | 0.58%   |
| USI                             | 2         | 0.39%   |
| Opticis                         | 2         | 0.39%   |
| Hewlett-Packard                 | 2         | 0.39%   |
| TP-Link                         | 1         | 0.19%   |
| Foxconn International           | 1         | 0.19%   |
| ASUSTek Computer                | 1         | 0.19%   |
| Alps Electric                   | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 113       | 21.94%  |
| Intel AX201 Bluetooth                               | 51        | 9.9%    |
| Intel AX200 Bluetooth                               | 50        | 9.71%   |
| Realtek Bluetooth Radio                             | 37        | 7.18%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 32        | 6.21%   |
| Qualcomm Atheros  Bluetooth Device                  | 20        | 3.88%   |
| Realtek  Bluetooth 4.2 Adapter                      | 14        | 2.72%   |
| Intel AX210 Bluetooth                               | 14        | 2.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 1.94%   |
| IMC Networks Wireless_Device                        | 10        | 1.94%   |
| Intel Bluetooth Device                              | 9         | 1.75%   |
| Apple Bluetooth USB Host Controller                 | 9         | 1.75%   |
| IMC Networks Bluetooth Radio                        | 8         | 1.55%   |
| Realtek Bluetooth Radio                             | 7         | 1.36%   |
| Foxconn / Hon Hai Wireless_Device                   | 7         | 1.36%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 7         | 1.36%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 1.17%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 0.97%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 0.97%   |
| MediaTek Wireless_Device                            | 5         | 0.97%   |
| Lite-On Bluetooth Device                            | 5         | 0.97%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 0.97%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 0.97%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 0.97%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 0.78%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.78%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.58%   |
| Realtek RTL8821A Bluetooth                          | 3         | 0.58%   |
| Ralink RT3290 Bluetooth                             | 3         | 0.58%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.58%   |
| IMC Networks Bluetooth Device                       | 3         | 0.58%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 0.58%   |
| USI Bluetooth Device                                | 2         | 0.39%   |
| Toshiba BCM43142A0                                  | 2         | 0.39%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.39%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.39%   |
| Opticis Bluetooth Radio                             | 2         | 0.39%   |
| Lite-On Wireless_Device                             | 2         | 0.39%   |
| Lite-On Bluetooth Radio                             | 2         | 0.39%   |
| IMC Networks Bluetooth                              | 2         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 379       | 51.42%  |
| AMD                                             | 173       | 23.47%  |
| Nvidia                                          | 104       | 14.11%  |
| C-Media Electronics                             | 10        | 1.36%   |
| Texas Instruments                               | 8         | 1.09%   |
| Lenovo                                          | 6         | 0.81%   |
| KORG                                            | 6         | 0.81%   |
| AKAI                                            | 5         | 0.68%   |
| Realtek Semiconductor                           | 4         | 0.54%   |
| Corsair                                         | 4         | 0.54%   |
| Sony                                            | 3         | 0.41%   |
| Logitech                                        | 3         | 0.41%   |
| Kingston Technology                             | 3         | 0.41%   |
| Creative Technology                             | 3         | 0.41%   |
| Apple                                           | 3         | 0.41%   |
| Samson Technologies                             | 2         | 0.27%   |
| JMTek                                           | 2         | 0.27%   |
| GYROCOM C&C                                     | 2         | 0.27%   |
| Generalplus Technology                          | 2         | 0.27%   |
| YZ Technology                                   | 1         | 0.14%   |
| XMOS                                            | 1         | 0.14%   |
| Tenx Technology                                 | 1         | 0.14%   |
| Tdlasunnic                                      | 1         | 0.14%   |
| ROCCAT                                          | 1         | 0.14%   |
| NAD Electronics                                 | 1         | 0.14%   |
| Micro Star International                        | 1         | 0.14%   |
| M-Audio                                         | 1         | 0.14%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.14%   |
| Focusrite-Novation                              | 1         | 0.14%   |
| Conexant Systems                                | 1         | 0.14%   |
| Beyerdynamic                                    | 1         | 0.14%   |
| Asahi Kasei Microsystems                        | 1         | 0.14%   |
| Anlya.cn                                        | 1         | 0.14%   |
| AKAI Professional M.I.                          | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 136       | 14.32%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 84        | 8.84%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 78        | 8.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 30        | 3.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 29        | 3.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 26        | 2.74%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 23        | 2.42%   |
| Intel 8 Series HD Audio Controller                                                                | 23        | 2.42%   |
| Intel Cannon Lake PCH cAVS                                                                        | 22        | 2.32%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 21        | 2.21%   |
| Intel Broadwell-U Audio Controller                                                                | 21        | 2.21%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 17        | 1.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 17        | 1.79%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 16        | 1.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 14        | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 1.47%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 14        | 1.47%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 13        | 1.37%   |
| Intel CM238 HD Audio Controller                                                                   | 13        | 1.37%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 13        | 1.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 12        | 1.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 11        | 1.16%   |
| Intel Comet Lake PCH cAVS                                                                         | 11        | 1.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 11        | 1.16%   |
| AMD FCH Azalia Controller                                                                         | 11        | 1.16%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 10        | 1.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 1.05%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 1.05%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 9         | 0.95%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 0.95%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 9         | 0.95%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 8         | 0.84%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 8         | 0.84%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 0.84%   |
| AMD High Definition Audio Controller                                                              | 8         | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 0.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 0.63%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 6         | 0.63%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 5         | 0.53%   |
| KORG nanoKONTROL2 MIDI Controller                                                                 | 5         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 164       | 32.67%  |
| SK hynix            | 124       | 24.7%   |
| Micron Technology   | 76        | 15.14%  |
| Kingston            | 29        | 5.78%   |
| Crucial             | 22        | 4.38%   |
| Unknown             | 15        | 2.99%   |
| Ramaxel Technology  | 10        | 1.99%   |
| A-DATA Technology   | 9         | 1.79%   |
| Corsair             | 8         | 1.59%   |
| Elpida              | 6         | 1.2%    |
| G.Skill             | 5         | 1%      |
| Unknown (ABCD)      | 4         | 0.8%    |
| Unknown             | 4         | 0.8%    |
| Team                | 3         | 0.6%    |
| Nanya Technology    | 3         | 0.6%    |
| Kllisre             | 3         | 0.6%    |
| Teikon              | 2         | 0.4%    |
| Shenzhen Mic        | 2         | 0.4%    |
| Hikvision           | 2         | 0.4%    |
| V-GeN               | 1         | 0.2%    |
| Toshiba             | 1         | 0.2%    |
| Smart Brazil        | 1         | 0.2%    |
| Sesame              | 1         | 0.2%    |
| Qimonda             | 1         | 0.2%    |
| Patriot             | 1         | 0.2%    |
| Magnum Tech         | 1         | 0.2%    |
| Juhor               | 1         | 0.2%    |
| GOODRAM             | 1         | 0.2%    |
| CSX                 | 1         | 0.2%    |
| Apacer              | 1         | 0.2%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 15        | 2.78%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 10        | 1.85%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 1.48%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 1.48%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 1.3%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 1.3%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 7         | 1.3%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 1.3%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 7         | 1.3%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 7         | 1.3%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 7         | 1.3%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 6         | 1.11%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 1.11%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 1.11%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 6         | 1.11%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 1.11%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.93%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.93%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.93%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 0.93%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.74%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 4         | 0.74%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 0.74%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.74%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.74%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.74%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 4         | 0.74%   |
| Unknown                                                          | 4         | 0.74%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.56%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.56%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.56%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.56%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.56%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.56%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.56%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.56%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2667MT/s            | 3         | 0.56%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 3         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 250       | 58.82%  |
| DDR3   | 107       | 25.18%  |
| LPDDR4 | 22        | 5.18%   |
| LPDDR3 | 17        | 4%      |
| LPDDR5 | 8         | 1.88%   |
| DDR5   | 8         | 1.88%   |
| DDR2   | 8         | 1.88%   |
| SDRAM  | 5         | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 367       | 85.35%  |
| Row Of Chips | 52        | 12.09%  |
| Chip         | 7         | 1.63%   |
| DIMM         | 2         | 0.47%   |
| Unknown      | 2         | 0.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 224       | 48.8%   |
| 4096  | 122       | 26.58%  |
| 16384 | 71        | 15.47%  |
| 2048  | 28        | 6.1%    |
| 32768 | 11        | 2.4%    |
| 1024  | 3         | 0.65%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 129       | 28.73%  |
| 1600    | 93        | 20.71%  |
| 2667    | 91        | 20.27%  |
| 2400    | 28        | 6.24%   |
| 2133    | 21        | 4.68%   |
| 3266    | 15        | 3.34%   |
| 4800    | 10        | 2.23%   |
| 1867    | 10        | 2.23%   |
| 6400    | 8         | 1.78%   |
| 1334    | 8         | 1.78%   |
| 4267    | 5         | 1.11%   |
| 1333    | 4         | 0.89%   |
| 667     | 4         | 0.89%   |
| 4266    | 3         | 0.67%   |
| 1067    | 3         | 0.67%   |
| Unknown | 3         | 0.67%   |
| 4199    | 2         | 0.45%   |
| 3733    | 2         | 0.45%   |
| 2048    | 2         | 0.45%   |
| 800     | 2         | 0.45%   |
| 3000    | 1         | 0.22%   |
| 2933    | 1         | 0.22%   |
| 1776    | 1         | 0.22%   |
| 1639    | 1         | 0.22%   |
| 1200    | 1         | 0.22%   |
| 1066    | 1         | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Xerox               | 1         | 33.33%  |
| Prolific Technology | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Xerox B210                    | 1         | 33.33%  |
| Prolific PL2305 Parallel Port | 1         | 33.33%  |
| HP DeskJet 2130 series        | 1         | 33.33%  |

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
| Chicony Electronics                    | 118       | 23.89%  |
| IMC Networks                           | 79        | 15.99%  |
| Microdia                               | 31        | 6.28%   |
| Realtek Semiconductor                  | 28        | 5.67%   |
| Acer                                   | 28        | 5.67%   |
| Quanta                                 | 26        | 5.26%   |
| Bison Electronics                      | 26        | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 25        | 5.06%   |
| Sunplus Innovation Technology          | 24        | 4.86%   |
| Lite-On Technology                     | 19        | 3.85%   |
| Apple                                  | 15        | 3.04%   |
| Syntek                                 | 14        | 2.83%   |
| Luxvisions Innotech Limited            | 12        | 2.43%   |
| Logitech                               | 12        | 2.43%   |
| Suyin                                  | 5         | 1.01%   |
| Sonix Technology                       | 4         | 0.81%   |
| Silicon Motion                         | 4         | 0.81%   |
| Primax Electronics                     | 3         | 0.61%   |
| Lenovo                                 | 3         | 0.61%   |
| Alcor Micro                            | 3         | 0.61%   |
| Samsung Electronics                    | 2         | 0.4%    |
| Ricoh                                  | 2         | 0.4%    |
| MacroSilicon                           | 2         | 0.4%    |
| Intel                                  | 2         | 0.4%    |
| Tripath Technology                     | 1         | 0.2%    |
| ShineTech                              | 1         | 0.2%    |
| GRANDSTREAM GUV3100                    | 1         | 0.2%    |
| Google                                 | 1         | 0.2%    |
| Generalplus Technology                 | 1         | 0.2%    |
| GEMBIRD                                | 1         | 0.2%    |
| ALi                                    | 1         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 34        | 6.87%   |
| IMC Networks Integrated Camera                               | 30        | 6.06%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 29        | 5.86%   |
| Chicony HD WebCam                                            | 17        | 3.43%   |
| Microdia Integrated_Webcam_HD                                | 12        | 2.42%   |
| Bison Integrated Camera                                      | 12        | 2.42%   |
| Acer HD Webcam                                               | 10        | 2.02%   |
| Realtek Integrated_Webcam_HD                                 | 9         | 1.82%   |
| Syntek Integrated Camera                                     | 8         | 1.62%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                              | 8         | 1.62%   |
| Sunplus Integrated_Webcam_HD                                 | 7         | 1.41%   |
| Lite-On Integrated Camera                                    | 7         | 1.41%   |
| Acer Integrated Camera                                       | 7         | 1.41%   |
| Quanta USB2.0 HD UVC WebCam                                  | 6         | 1.21%   |
| Microdia Integrated Webcam                                   | 6         | 1.21%   |
| Chicony USB2.0 HD UVC WebCam                                 | 6         | 1.21%   |
| Sunplus HD WebCam                                            | 5         | 1.01%   |
| Quanta HP TrueVision HD Camera                               | 5         | 1.01%   |
| Quanta HP HD Camera                                          | 5         | 1.01%   |
| IMC Networks ov9734_azurewave_camera                         | 5         | 1.01%   |
| Chicony VGA WebCam                                           | 5         | 1.01%   |
| Chicony HP TrueVision HD Camera                              | 5         | 1.01%   |
| Chicony HD User Facing                                       | 5         | 1.01%   |
| Syntek Lenovo EasyCamera                                     | 4         | 0.81%   |
| Sunplus Asus Webcam                                          | 4         | 0.81%   |
| Sonix USB2.0 HD UVC WebCam                                   | 4         | 0.81%   |
| Logitech HD Pro Webcam C920                                  | 4         | 0.81%   |
| Lite-On HP Webcam                                            | 4         | 0.81%   |
| IMC Networks HD Camera                                       | 4         | 0.81%   |
| Chicony USB2.0 VGA UVC WebCam                                | 4         | 0.81%   |
| Chicony HP Wide Vision HD Camera                             | 4         | 0.81%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 4         | 0.81%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera             | 4         | 0.81%   |
| Bison SunplusIT Integrated Camera                            | 4         | 0.81%   |
| Apple FaceTime HD Camera (Built-in)                          | 4         | 0.81%   |
| Acer BisonCam,NB Pro                                         | 4         | 0.81%   |
| Sunplus XiaoMi USB 2.0 Webcam                                | 3         | 0.61%   |
| Realtek USB2.0 HD UVC WebCam                                 | 3         | 0.61%   |
| Quanta VGA WebCam                                            | 3         | 0.61%   |
| Microdia Webcam Vitade AF                                    | 3         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 33        | 31.73%  |
| Validity Sensors                   | 28        | 26.92%  |
| Shenzhen Goodix Technology         | 18        | 17.31%  |
| Elan Microelectronics              | 13        | 12.5%   |
| LighTuning Technology              | 6         | 5.77%   |
| Upek                               | 3         | 2.88%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 1.92%   |
| AuthenTec                          | 1         | 0.96%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 11        | 10.58%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 10        | 9.62%   |
| Elan ELAN:Fingerprint                                                      | 8         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 6.73%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 5.77%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 5.77%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 5.77%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 4.81%   |
| Elan ELAN:ARM-M4                                                           | 5         | 4.81%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 3.85%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 2.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 2.88%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 2.88%   |
| Synaptics UWP WBDI                                                         | 3         | 2.88%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.92%   |
| Validity Sensors VFS491                                                    | 2         | 1.92%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.92%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.92%   |
| Synaptics WBDI                                                             | 2         | 1.92%   |
| Synaptics  WBDI                                                            | 2         | 1.92%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 1.92%   |
| Unknown                                                                    | 2         | 1.92%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.96%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.96%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.96%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.96%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.96%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.96%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.96%   |
| AuthenTec AES2810                                                          | 1         | 0.96%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 18        | 51.43%  |
| Alcor Micro | 10        | 28.57%  |
| Lenovo      | 3         | 8.57%   |
| Upek        | 2         | 5.71%   |
| O2 Micro    | 2         | 5.71%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 11        | 30.56%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 27.78%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 8.33%   |
| Broadcom 58200                                                               | 3         | 8.33%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 5.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 5.56%   |
| Broadcom 5880                                                                | 2         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 325       | 57.73%  |
| 1     | 194       | 34.46%  |
| 2     | 43        | 7.64%   |
| 3     | 1         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 104       | 38.38%  |
| Net/ethernet             | 37        | 13.65%  |
| Chipcard                 | 34        | 12.55%  |
| Multimedia controller    | 31        | 11.44%  |
| Graphics card            | 25        | 9.23%   |
| Net/wireless             | 18        | 6.64%   |
| Camera                   | 10        | 3.69%   |
| Bluetooth                | 8         | 2.95%   |
| Storage                  | 2         | 0.74%   |
| Modem                    | 1         | 0.37%   |
| Communication controller | 1         | 0.37%   |


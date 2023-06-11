Debian 11 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Debian 11.

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

Total: 4498

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 7440               | [f63ada6c61](https://linux-hardware.org/?probe=f63ada6c61) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | [a62438daef](https://linux-hardware.org/?probe=a62438daef) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | [fab548c31e](https://linux-hardware.org/?probe=fab548c31e) | Jun 10, 2023 |
| IT Channel... | N8xEJEK                     | [51a7e3f5b4](https://linux-hardware.org/?probe=51a7e3f5b4) | Jun 10, 2023 |
| Acidanther... | MacBookPro15,2              | [fb30b2eb35](https://linux-hardware.org/?probe=fb30b2eb35) | Jun 10, 2023 |
| Intel         | powered classmate PC        | [e530f037c6](https://linux-hardware.org/?probe=e530f037c6) | Jun 09, 2023 |
| Digibras      | NH4CU03                     | [c66d30943e](https://linux-hardware.org/?probe=c66d30943e) | Jun 09, 2023 |
| Acer          | TravelMate P215-53          | [9536bf547a](https://linux-hardware.org/?probe=9536bf547a) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK U7411              | [ab35c95b72](https://linux-hardware.org/?probe=ab35c95b72) | Jun 09, 2023 |
| Acer          | TravelMate P449-G2-M        | [6b42200bee](https://linux-hardware.org/?probe=6b42200bee) | Jun 09, 2023 |
| HP            | G42                         | [fe8d2be276](https://linux-hardware.org/?probe=fe8d2be276) | Jun 08, 2023 |
| HP            | G42                         | [4f33462d46](https://linux-hardware.org/?probe=4f33462d46) | Jun 08, 2023 |
| Acer          | TravelMate P449-G2-M        | [0fa009ad04](https://linux-hardware.org/?probe=0fa009ad04) | Jun 08, 2023 |
| MSI           | GE60 2PL                    | [e1d118e2d2](https://linux-hardware.org/?probe=e1d118e2d2) | Jun 08, 2023 |
| Acer          | Aspire 7741                 | [09b2301e59](https://linux-hardware.org/?probe=09b2301e59) | Jun 08, 2023 |
| Lenovo        | ThinkPad X131e 3374A17      | [d992393271](https://linux-hardware.org/?probe=d992393271) | Jun 08, 2023 |
| Lenovo        | ThinkPad X131e 3374A17      | [dd385507aa](https://linux-hardware.org/?probe=dd385507aa) | Jun 08, 2023 |
| HP            | Pavilion 17                 | [da809f90cc](https://linux-hardware.org/?probe=da809f90cc) | Jun 07, 2023 |
| Dell          | Latitude 5530               | [1e3452635f](https://linux-hardware.org/?probe=1e3452635f) | Jun 07, 2023 |
| HP            | ProBook 4530s               | [bdb6739deb](https://linux-hardware.org/?probe=bdb6739deb) | Jun 07, 2023 |
| Intel         | HURONRIVER                  | [57035a777c](https://linux-hardware.org/?probe=57035a777c) | Jun 07, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [490ae0bc1c](https://linux-hardware.org/?probe=490ae0bc1c) | Jun 07, 2023 |
| MSI           | Pulse GL66 12UDK            | [8c9a9eb310](https://linux-hardware.org/?probe=8c9a9eb310) | Jun 06, 2023 |
| HP            | Pavilion g7                 | [f8cccf0fec](https://linux-hardware.org/?probe=f8cccf0fec) | Jun 06, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [be9987ca28](https://linux-hardware.org/?probe=be9987ca28) | Jun 06, 2023 |
| HP            | ENVY Laptop 13-ba0xxx       | [22143d333a](https://linux-hardware.org/?probe=22143d333a) | Jun 05, 2023 |
| Dell          | Latitude 3410               | [820e62c9d3](https://linux-hardware.org/?probe=820e62c9d3) | Jun 04, 2023 |
| MSI           | GL75 Leopard 10SER          | [24111ade43](https://linux-hardware.org/?probe=24111ade43) | Jun 04, 2023 |
| Dell          | Latitude 3410               | [12515d41c8](https://linux-hardware.org/?probe=12515d41c8) | Jun 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [1352a1d7c7](https://linux-hardware.org/?probe=1352a1d7c7) | Jun 04, 2023 |
| ASUSTek       | Q502LA                      | [679a477085](https://linux-hardware.org/?probe=679a477085) | Jun 04, 2023 |
| Clevo         | M670SRU                     | [0935f74d34](https://linux-hardware.org/?probe=0935f74d34) | Jun 04, 2023 |
| Clevo         | M670SRU                     | [e163d57d56](https://linux-hardware.org/?probe=e163d57d56) | Jun 04, 2023 |
| AVITA         | NS14A8                      | [a576b4d5cc](https://linux-hardware.org/?probe=a576b4d5cc) | Jun 04, 2023 |
| Toshiba       | WT8-A                       | [01e8918ef6](https://linux-hardware.org/?probe=01e8918ef6) | Jun 04, 2023 |
| Acer          | Aspire 5738                 | [138d22e03e](https://linux-hardware.org/?probe=138d22e03e) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [a10a42a44d](https://linux-hardware.org/?probe=a10a42a44d) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [e58b2a1237](https://linux-hardware.org/?probe=e58b2a1237) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [ce54d0192d](https://linux-hardware.org/?probe=ce54d0192d) | Jun 04, 2023 |
| Lenovo        | ThinkPad E420 1141R79       | [7f66bf0045](https://linux-hardware.org/?probe=7f66bf0045) | Jun 03, 2023 |
| Acer          | Aspire V3-372               | [1200863830](https://linux-hardware.org/?probe=1200863830) | Jun 03, 2023 |
| Apple         | MacBookPro7,1               | [b1513dc005](https://linux-hardware.org/?probe=b1513dc005) | Jun 03, 2023 |
| Acer          | Aspire E5-772G              | [5bd684bed6](https://linux-hardware.org/?probe=5bd684bed6) | Jun 02, 2023 |
| Acer          | Aspire E5-772G              | [f454cdf394](https://linux-hardware.org/?probe=f454cdf394) | Jun 02, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [b546b2e7f1](https://linux-hardware.org/?probe=b546b2e7f1) | Jun 02, 2023 |
| Apple         | MacBookPro5,5               | [9bf36ef4a5](https://linux-hardware.org/?probe=9bf36ef4a5) | Jun 02, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [174ffa62e4](https://linux-hardware.org/?probe=174ffa62e4) | Jun 02, 2023 |
| Dell          | Latitude E6430              | [b129765265](https://linux-hardware.org/?probe=b129765265) | Jun 02, 2023 |
| HP            | EliteBook 840 G6            | [81ec1cc134](https://linux-hardware.org/?probe=81ec1cc134) | Jun 01, 2023 |
| Dell          | Latitude E5510              | [4a0bc9e53f](https://linux-hardware.org/?probe=4a0bc9e53f) | Jun 01, 2023 |
| Dell          | System Inspiron N4110       | [ea09e45a4f](https://linux-hardware.org/?probe=ea09e45a4f) | Jun 01, 2023 |
| Dell          | Latitude E5510              | [9457826049](https://linux-hardware.org/?probe=9457826049) | Jun 01, 2023 |
| Positivo      | C500                        | [8dba4589fe](https://linux-hardware.org/?probe=8dba4589fe) | Jun 01, 2023 |
| ASUSTek       | X200LA                      | [ae3925153d](https://linux-hardware.org/?probe=ae3925153d) | May 31, 2023 |
| ASUSTek       | 1225B                       | [769a6736f1](https://linux-hardware.org/?probe=769a6736f1) | May 31, 2023 |
| Fujitsu       | LIFEBOOK E780               | [8459f7cfee](https://linux-hardware.org/?probe=8459f7cfee) | May 31, 2023 |
| HP            | EliteBook 840 G4            | [46ccbd2d62](https://linux-hardware.org/?probe=46ccbd2d62) | May 31, 2023 |
| HP            | EliteBook 840 G4            | [b90cb27f97](https://linux-hardware.org/?probe=b90cb27f97) | May 31, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [5f8bd19e3d](https://linux-hardware.org/?probe=5f8bd19e3d) | May 31, 2023 |
| Acer          | TravelMate P449-G2-M        | [41177ef027](https://linux-hardware.org/?probe=41177ef027) | May 31, 2023 |
| Dell          | Latitude 5411               | [8583aa2091](https://linux-hardware.org/?probe=8583aa2091) | May 31, 2023 |
| ASUSTek       | K52Jc                       | [ad0b57d7c6](https://linux-hardware.org/?probe=ad0b57d7c6) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | [e065b72b88](https://linux-hardware.org/?probe=e065b72b88) | May 31, 2023 |
| ASUSTek       | K52Jc                       | [7709d9fd16](https://linux-hardware.org/?probe=7709d9fd16) | May 31, 2023 |
| Dell          | Latitude E5510              | [52e1023195](https://linux-hardware.org/?probe=52e1023195) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | [52047d2230](https://linux-hardware.org/?probe=52047d2230) | May 31, 2023 |
| Dell          | Latitude E5510              | [aa0f6a81b6](https://linux-hardware.org/?probe=aa0f6a81b6) | May 30, 2023 |
| HP            | Laptop 17-ca0xxx            | [3222c41173](https://linux-hardware.org/?probe=3222c41173) | May 30, 2023 |
| Lenovo        | ThinkPad T460 20FMS4LL00    | [7519448ca8](https://linux-hardware.org/?probe=7519448ca8) | May 30, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [ad3464fd76](https://linux-hardware.org/?probe=ad3464fd76) | May 30, 2023 |
| Fujitsu       | LIFEBOOK E780               | [aac95cf765](https://linux-hardware.org/?probe=aac95cf765) | May 29, 2023 |
| Dell          | Latitude E5470              | [77d85b619e](https://linux-hardware.org/?probe=77d85b619e) | May 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [deaa4b357c](https://linux-hardware.org/?probe=deaa4b357c) | May 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [af312b5e91](https://linux-hardware.org/?probe=af312b5e91) | May 29, 2023 |
| Dell          | Latitude E6530              | [26f783c383](https://linux-hardware.org/?probe=26f783c383) | May 29, 2023 |
| Lenovo        | ThinkPad W530 2447GH2       | [f902d43115](https://linux-hardware.org/?probe=f902d43115) | May 29, 2023 |
| Dell          | Latitude E6530              | [a47a934500](https://linux-hardware.org/?probe=a47a934500) | May 29, 2023 |
| HP            | Laptop 17-ca0xxx            | [4b53ed4ede](https://linux-hardware.org/?probe=4b53ed4ede) | May 29, 2023 |
| Lenovo        | Edge 15 80H1                | [75fdd71ca1](https://linux-hardware.org/?probe=75fdd71ca1) | May 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d5a3141562](https://linux-hardware.org/?probe=d5a3141562) | May 28, 2023 |
| HP            | EliteBook 840 G1            | [c256cd6942](https://linux-hardware.org/?probe=c256cd6942) | May 28, 2023 |
| HP            | Mini 110-3700               | [0f9528a8d2](https://linux-hardware.org/?probe=0f9528a8d2) | May 28, 2023 |
| HP            | G42                         | [7b9612a51a](https://linux-hardware.org/?probe=7b9612a51a) | May 27, 2023 |
| ASUSTek       | X550CA                      | [3ad8935a92](https://linux-hardware.org/?probe=3ad8935a92) | May 27, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JU... | [0696598319](https://linux-hardware.org/?probe=0696598319) | May 26, 2023 |
| ASUSTek       | K53SV                       | [357c1fd091](https://linux-hardware.org/?probe=357c1fd091) | May 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [4c3aa6334b](https://linux-hardware.org/?probe=4c3aa6334b) | May 26, 2023 |
| Acer          | Aspire A315-42              | [d229a8eb01](https://linux-hardware.org/?probe=d229a8eb01) | May 26, 2023 |
| Acer          | Aspire V3-551               | [316db578fe](https://linux-hardware.org/?probe=316db578fe) | May 25, 2023 |
| Dell          | Latitude 7220 Rugged Ext... | [442b7239c8](https://linux-hardware.org/?probe=442b7239c8) | May 24, 2023 |
| Dell          | Latitude E5430 non-vPro     | [278fefa10a](https://linux-hardware.org/?probe=278fefa10a) | May 24, 2023 |
| Notebook      | W54_55SU1,SUW               | [25b79c51e2](https://linux-hardware.org/?probe=25b79c51e2) | May 23, 2023 |
| HP            | 530                         | [70600de142](https://linux-hardware.org/?probe=70600de142) | May 23, 2023 |
| Dell          | Latitude E5430 non-vPro     | [6ab7e9c82d](https://linux-hardware.org/?probe=6ab7e9c82d) | May 23, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [44b6477648](https://linux-hardware.org/?probe=44b6477648) | May 22, 2023 |
| ASUSTek       | N56VB                       | [0e982abd6b](https://linux-hardware.org/?probe=0e982abd6b) | May 22, 2023 |
| Unknown       | Unknown                     | [2b3ef0afc4](https://linux-hardware.org/?probe=2b3ef0afc4) | May 22, 2023 |
| HP            | Laptop 15-da0xxx            | [82f235bfbb](https://linux-hardware.org/?probe=82f235bfbb) | May 22, 2023 |
| HP            | Laptop 14-dq0xxx            | [4438fdd9b2](https://linux-hardware.org/?probe=4438fdd9b2) | May 22, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [0ab3a9817b](https://linux-hardware.org/?probe=0ab3a9817b) | May 21, 2023 |
| Dell          | Inspiron 5570               | [ca85d5aafa](https://linux-hardware.org/?probe=ca85d5aafa) | May 21, 2023 |
| Dell          | Inspiron 3451               | [e69cefc8da](https://linux-hardware.org/?probe=e69cefc8da) | May 21, 2023 |
| Lenovo        | ThinkPad W510 4391DK3       | [ac8db768ce](https://linux-hardware.org/?probe=ac8db768ce) | May 20, 2023 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | [e6e79ac2ca](https://linux-hardware.org/?probe=e6e79ac2ca) | May 20, 2023 |
| Dell          | Latitude 5411               | [8929285bca](https://linux-hardware.org/?probe=8929285bca) | May 19, 2023 |
| Dell          | Vostro 15 3515              | [6b5bc55aeb](https://linux-hardware.org/?probe=6b5bc55aeb) | May 18, 2023 |
| Dell          | Vostro 15 3515              | [e26f4ecf2f](https://linux-hardware.org/?probe=e26f4ecf2f) | May 18, 2023 |
| Lenovo        | ThinkPad X200s 7470WUB      | [e5ad235f60](https://linux-hardware.org/?probe=e5ad235f60) | May 18, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [5d69cc1112](https://linux-hardware.org/?probe=5d69cc1112) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | [0c6bb22a24](https://linux-hardware.org/?probe=0c6bb22a24) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | [e042bb19ba](https://linux-hardware.org/?probe=e042bb19ba) | May 18, 2023 |
| Acer          | Aspire A514-54              | [26dc842484](https://linux-hardware.org/?probe=26dc842484) | May 18, 2023 |
| Dell          | Latitude E7450              | [3000905b05](https://linux-hardware.org/?probe=3000905b05) | May 18, 2023 |
| Dell          | Latitude E7450              | [10f138711f](https://linux-hardware.org/?probe=10f138711f) | May 18, 2023 |
| Apple         | MacBookPro12,1              | [4aadc89f41](https://linux-hardware.org/?probe=4aadc89f41) | May 17, 2023 |
| Dell          | Latitude E5430 non-vPro     | [a1fb71ff2f](https://linux-hardware.org/?probe=a1fb71ff2f) | May 17, 2023 |
| Apple         | MacBookPro12,1              | [8aef05613d](https://linux-hardware.org/?probe=8aef05613d) | May 17, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | [0f9a26db5f](https://linux-hardware.org/?probe=0f9a26db5f) | May 16, 2023 |
| Lenovo        | ThinkPad T490 20N2004JAD    | [c765eed46d](https://linux-hardware.org/?probe=c765eed46d) | May 16, 2023 |
| Dell          | Latitude 5521               | [9f671f21c1](https://linux-hardware.org/?probe=9f671f21c1) | May 16, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | [56056f7c9a](https://linux-hardware.org/?probe=56056f7c9a) | May 15, 2023 |
| Acer          | AO532h                      | [6cfe2a58cc](https://linux-hardware.org/?probe=6cfe2a58cc) | May 15, 2023 |
| Acer          | Aspire 7745G                | [c1bcc07617](https://linux-hardware.org/?probe=c1bcc07617) | May 15, 2023 |
| Acer          | Aspire 7745G                | [7b0f6f3dc2](https://linux-hardware.org/?probe=7b0f6f3dc2) | May 15, 2023 |
| Dell          | G15 5510                    | [5624d414be](https://linux-hardware.org/?probe=5624d414be) | May 15, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | [c82f72f0e2](https://linux-hardware.org/?probe=c82f72f0e2) | May 15, 2023 |
| Lenovo        | ThinkPad Edge E530 3259C... | [cd0a78ce39](https://linux-hardware.org/?probe=cd0a78ce39) | May 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7978974828](https://linux-hardware.org/?probe=7978974828) | May 14, 2023 |
| ASUSTek       | N56VB                       | [87d2f8b907](https://linux-hardware.org/?probe=87d2f8b907) | May 14, 2023 |
| ASUSTek       | N56VB                       | [7e2caae7ea](https://linux-hardware.org/?probe=7e2caae7ea) | May 14, 2023 |
| Lenovo        | B50-70 20384                | [1d3db7b456](https://linux-hardware.org/?probe=1d3db7b456) | May 14, 2023 |
| Lenovo        | B50-70 20384                | [9459f4eae8](https://linux-hardware.org/?probe=9459f4eae8) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [2be4ad0e3d](https://linux-hardware.org/?probe=2be4ad0e3d) | May 14, 2023 |
| Dell          | Latitude 7410               | [542e1d7f7b](https://linux-hardware.org/?probe=542e1d7f7b) | May 14, 2023 |
| AMI           | Intel                       | [958f5ffc92](https://linux-hardware.org/?probe=958f5ffc92) | May 14, 2023 |
| AMI           | Intel                       | [0c9a68a20c](https://linux-hardware.org/?probe=0c9a68a20c) | May 13, 2023 |
| Fujitsu       | LIFEBOOK E5410              | [c62a002948](https://linux-hardware.org/?probe=c62a002948) | May 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [bf54c69e0c](https://linux-hardware.org/?probe=bf54c69e0c) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [b9b6adb18a](https://linux-hardware.org/?probe=b9b6adb18a) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [80dc4be517](https://linux-hardware.org/?probe=80dc4be517) | May 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [9201edcfb8](https://linux-hardware.org/?probe=9201edcfb8) | May 12, 2023 |
| Toshiba       | Satellite Pro C660          | [848eedb681](https://linux-hardware.org/?probe=848eedb681) | May 12, 2023 |
| Lenovo        | ThinkPad T470 20HD0001MX    | [65b165e2f1](https://linux-hardware.org/?probe=65b165e2f1) | May 12, 2023 |
| Apple         | MacBook10,1                 | [d26983a399](https://linux-hardware.org/?probe=d26983a399) | May 12, 2023 |
| HP            | ProBook 450 G7              | [ba542c09f2](https://linux-hardware.org/?probe=ba542c09f2) | May 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [f02c2abaab](https://linux-hardware.org/?probe=f02c2abaab) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7d19994aa2](https://linux-hardware.org/?probe=7d19994aa2) | May 11, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [eb6941b1b8](https://linux-hardware.org/?probe=eb6941b1b8) | May 10, 2023 |
| HP            | 250 G6 Notebook PC          | [f612c54f9c](https://linux-hardware.org/?probe=f612c54f9c) | May 09, 2023 |
| HP            | 250 G6 Notebook PC          | [9c14434a99](https://linux-hardware.org/?probe=9c14434a99) | May 09, 2023 |
| Unknown       | Unknown                     | [4a0ccb88d2](https://linux-hardware.org/?probe=4a0ccb88d2) | May 09, 2023 |
| Lenovo        | ThinkPad T530 2394CE2       | [d232fefed2](https://linux-hardware.org/?probe=d232fefed2) | May 09, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [967e39a2d3](https://linux-hardware.org/?probe=967e39a2d3) | May 08, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYFR    | [f945ec106e](https://linux-hardware.org/?probe=f945ec106e) | May 07, 2023 |
| HP            | 255 G3                      | [d95f6211dc](https://linux-hardware.org/?probe=d95f6211dc) | May 07, 2023 |
| ASUSTek       | K73SJ                       | [13b8c8be10](https://linux-hardware.org/?probe=13b8c8be10) | May 07, 2023 |
| Dell          | Vostro 15-3568              | [08b1152328](https://linux-hardware.org/?probe=08b1152328) | May 07, 2023 |
| Acer          | Aspire AV15-51              | [9d7736a816](https://linux-hardware.org/?probe=9d7736a816) | May 06, 2023 |
| Lenovo        | IdeaPad Y480 20131          | [d625664bee](https://linux-hardware.org/?probe=d625664bee) | May 06, 2023 |
| Unknown       | Unknown                     | [dd406112de](https://linux-hardware.org/?probe=dd406112de) | May 06, 2023 |
| HP            | Laptop 15s-fq5xxx           | [8ce0b92713](https://linux-hardware.org/?probe=8ce0b92713) | May 06, 2023 |
| Lenovo        | Mixx-700-12ISK 80QL         | [14bc666ec3](https://linux-hardware.org/?probe=14bc666ec3) | May 06, 2023 |
| Acer          | Aspire 7741                 | [25f9d02593](https://linux-hardware.org/?probe=25f9d02593) | May 06, 2023 |
| Lenovo        | ThinkPad T410 2537CC5       | [10de9f17e1](https://linux-hardware.org/?probe=10de9f17e1) | May 06, 2023 |
| Acer          | TravelMate P215-53          | [f7c7c572e4](https://linux-hardware.org/?probe=f7c7c572e4) | May 05, 2023 |
| Dell          | Inspiron 5770               | [c545869ec5](https://linux-hardware.org/?probe=c545869ec5) | May 05, 2023 |
| Lenovo        | ThinkPad T15p Gen 2i 21A... | [064df1260c](https://linux-hardware.org/?probe=064df1260c) | May 05, 2023 |
| Dell          | Latitude D630               | [0bef13413f](https://linux-hardware.org/?probe=0bef13413f) | May 05, 2023 |
| Acer          | Aspire A515-52G             | [4f2fbcc26f](https://linux-hardware.org/?probe=4f2fbcc26f) | May 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2660b0df6d](https://linux-hardware.org/?probe=2660b0df6d) | May 04, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [b68f20e323](https://linux-hardware.org/?probe=b68f20e323) | May 04, 2023 |
| Notebook      | W54_55SU1,SUW               | [fbcadee14f](https://linux-hardware.org/?probe=fbcadee14f) | May 03, 2023 |
| Notebook      | W54_55SU1,SUW               | [f9071ed10e](https://linux-hardware.org/?probe=f9071ed10e) | May 03, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f636b7c230](https://linux-hardware.org/?probe=f636b7c230) | May 03, 2023 |
| HP            | EliteBook 640 14 inch G9... | [fc1bd7fffc](https://linux-hardware.org/?probe=fc1bd7fffc) | May 03, 2023 |
| HP            | EliteBook 640 14 inch G9... | [c8373114ef](https://linux-hardware.org/?probe=c8373114ef) | May 03, 2023 |
| Lenovo        | ThinkPad T470 20HES63400    | [6628ac6681](https://linux-hardware.org/?probe=6628ac6681) | May 03, 2023 |
| HP            | Notebook                    | [c6316b5a64](https://linux-hardware.org/?probe=c6316b5a64) | May 03, 2023 |
| Dell          | Precision 7510              | [1e73564cf9](https://linux-hardware.org/?probe=1e73564cf9) | May 03, 2023 |
| Dell          | Latitude 5414               | [6922f7db46](https://linux-hardware.org/?probe=6922f7db46) | May 03, 2023 |
| Dell          | Latitude D630               | [d8ee0e7ca8](https://linux-hardware.org/?probe=d8ee0e7ca8) | May 02, 2023 |
| Dell          | Latitude 7370               | [c984360af7](https://linux-hardware.org/?probe=c984360af7) | May 02, 2023 |
| Dell          | Latitude 7370               | [295b50d5b2](https://linux-hardware.org/?probe=295b50d5b2) | May 02, 2023 |
| MSI           | Katana GF76 12UEK           | [5af5d6aec3](https://linux-hardware.org/?probe=5af5d6aec3) | May 01, 2023 |
| AXDIA Inte... | MYBOOK 14 PRO               | [3174c98e9c](https://linux-hardware.org/?probe=3174c98e9c) | May 01, 2023 |
| Acer          | Aspire E1-571               | [e03d5ff056](https://linux-hardware.org/?probe=e03d5ff056) | Apr 30, 2023 |
| HP            | ProBook 655 G3              | [07e2cc77f8](https://linux-hardware.org/?probe=07e2cc77f8) | Apr 30, 2023 |
| HP            | ProBook 655 G3              | [638e747fb1](https://linux-hardware.org/?probe=638e747fb1) | Apr 30, 2023 |
| HP            | Compaq Mini CQ10-500        | [9a1134210f](https://linux-hardware.org/?probe=9a1134210f) | Apr 30, 2023 |
| Positivo      | Q464C                       | [8e41593bd3](https://linux-hardware.org/?probe=8e41593bd3) | Apr 30, 2023 |
| Dell          | Inspiron MXC061             | [2d1ab773dd](https://linux-hardware.org/?probe=2d1ab773dd) | Apr 30, 2023 |
| COPELION I... | QX-250 Series               | [409821566f](https://linux-hardware.org/?probe=409821566f) | Apr 29, 2023 |
| Lenovo        | ThinkPad X280 20KESBC402    | [0d5b86146e](https://linux-hardware.org/?probe=0d5b86146e) | Apr 29, 2023 |
| Dell          | Latitude E7450              | [6afa2ff009](https://linux-hardware.org/?probe=6afa2ff009) | Apr 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [69d1f17b35](https://linux-hardware.org/?probe=69d1f17b35) | Apr 27, 2023 |
| ARDOR GAMI... | PD5x_7xPNP_PNR_PNN_PNT      | [e61f528ba5](https://linux-hardware.org/?probe=e61f528ba5) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [73141c5006](https://linux-hardware.org/?probe=73141c5006) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [0cb164ac2f](https://linux-hardware.org/?probe=0cb164ac2f) | Apr 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | [198fa6162e](https://linux-hardware.org/?probe=198fa6162e) | Apr 27, 2023 |
| IGEL Techn... | M340C                       | [40970f0528](https://linux-hardware.org/?probe=40970f0528) | Apr 26, 2023 |
| ARDOR GAMI... | PD5x_7xPNP_PNR_PNN_PNT      | [cec3a72c8a](https://linux-hardware.org/?probe=cec3a72c8a) | Apr 26, 2023 |
| Google        | Terra                       | [b22deb9f09](https://linux-hardware.org/?probe=b22deb9f09) | Apr 26, 2023 |
| Dell          | Latitude E6440              | [f5cdf825fa](https://linux-hardware.org/?probe=f5cdf825fa) | Apr 26, 2023 |
| HP            | ENVY 15                     | [1f50420c44](https://linux-hardware.org/?probe=1f50420c44) | Apr 26, 2023 |
| HP            | 250 G6 Notebook PC          | [90e4883dca](https://linux-hardware.org/?probe=90e4883dca) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | [c3c972facf](https://linux-hardware.org/?probe=c3c972facf) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | [f993513cd3](https://linux-hardware.org/?probe=f993513cd3) | Apr 26, 2023 |
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
| Lenovo        | ThinkPad T530 23594ZC       | [7aec73dfa1](https://linux-hardware.org/?probe=7aec73dfa1) | Apr 25, 2023 |
| Lenovo        | ThinkPad X200 7459KM3       | [cbea785e27](https://linux-hardware.org/?probe=cbea785e27) | Apr 25, 2023 |
| Acer          | Aspire E5-576G              | [9ca5902786](https://linux-hardware.org/?probe=9ca5902786) | Apr 25, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [aa1b58a2a2](https://linux-hardware.org/?probe=aa1b58a2a2) | Apr 24, 2023 |
| Apple         | MacBookPro5,5               | [de825a326c](https://linux-hardware.org/?probe=de825a326c) | Apr 24, 2023 |
| Dell          | Inspiron 5537               | [971055139b](https://linux-hardware.org/?probe=971055139b) | Apr 24, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | [32546113c8](https://linux-hardware.org/?probe=32546113c8) | Apr 24, 2023 |
| HP            | 15                          | [fd68fb06af](https://linux-hardware.org/?probe=fd68fb06af) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | [45d7bd0907](https://linux-hardware.org/?probe=45d7bd0907) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | [c7367bfdff](https://linux-hardware.org/?probe=c7367bfdff) | Apr 23, 2023 |
| Toshiba       | Satellite C70D-A            | [adee59c351](https://linux-hardware.org/?probe=adee59c351) | Apr 23, 2023 |
| Toshiba       | Satellite C70D-A            | [c5c43186bc](https://linux-hardware.org/?probe=c5c43186bc) | Apr 23, 2023 |
| Dell          | G15 5520                    | [07751c950a](https://linux-hardware.org/?probe=07751c950a) | Apr 22, 2023 |
| HP            | Laptop 15s-du3xxx           | [45af810de1](https://linux-hardware.org/?probe=45af810de1) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5f61e3a174](https://linux-hardware.org/?probe=5f61e3a174) | Apr 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [3caa3d5076](https://linux-hardware.org/?probe=3caa3d5076) | Apr 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [8c8d2eb3b5](https://linux-hardware.org/?probe=8c8d2eb3b5) | Apr 21, 2023 |
| Dell          | Precision 3550              | [7434822402](https://linux-hardware.org/?probe=7434822402) | Apr 21, 2023 |
| Toshiba       | Satellite Pro NB10-A-125    | [3a77f344af](https://linux-hardware.org/?probe=3a77f344af) | Apr 20, 2023 |
| ASUSTek       | X550CA                      | [cb5f73ff63](https://linux-hardware.org/?probe=cb5f73ff63) | Apr 20, 2023 |
| Acer          | Aspire E3-111               | [9af253f4e0](https://linux-hardware.org/?probe=9af253f4e0) | Apr 20, 2023 |
| HP            | Laptop 15-db0xxx            | [9ab965fcb8](https://linux-hardware.org/?probe=9ab965fcb8) | Apr 19, 2023 |
| Lenovo        | ThinkPad T500 2055WAB       | [4e293261bb](https://linux-hardware.org/?probe=4e293261bb) | Apr 19, 2023 |
| HP            | ProBook 450 G2              | [3b8c115c1a](https://linux-hardware.org/?probe=3b8c115c1a) | Apr 19, 2023 |
| Toshiba       | Satellite Pro A100          | [4240870be8](https://linux-hardware.org/?probe=4240870be8) | Apr 19, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [f691871296](https://linux-hardware.org/?probe=f691871296) | Apr 19, 2023 |
| Acer          | Swift SF314-57              | [5fc25cc033](https://linux-hardware.org/?probe=5fc25cc033) | Apr 19, 2023 |
| HP            | 255 G8 Notebook PC          | [699e2a2a80](https://linux-hardware.org/?probe=699e2a2a80) | Apr 18, 2023 |
| Toshiba       | Satellite Pro C850-1J2      | [e5c63957a2](https://linux-hardware.org/?probe=e5c63957a2) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [94f62c41e5](https://linux-hardware.org/?probe=94f62c41e5) | Apr 17, 2023 |
| LG Electro... | P530-KE6BK                  | [b1f0863c79](https://linux-hardware.org/?probe=b1f0863c79) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [d5db24c28d](https://linux-hardware.org/?probe=d5db24c28d) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [89eb2b2c32](https://linux-hardware.org/?probe=89eb2b2c32) | Apr 17, 2023 |
| Dell          | Latitude 5420               | [4f3345aced](https://linux-hardware.org/?probe=4f3345aced) | Apr 16, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | [d532f6fdbd](https://linux-hardware.org/?probe=d532f6fdbd) | Apr 16, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [c622c73721](https://linux-hardware.org/?probe=c622c73721) | Apr 16, 2023 |
| HP            | Notebook                    | [7614984f1d](https://linux-hardware.org/?probe=7614984f1d) | Apr 15, 2023 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [8ca60a45fe](https://linux-hardware.org/?probe=8ca60a45fe) | Apr 15, 2023 |
| HP            | EliteBook 850 G4            | [984cf8fd47](https://linux-hardware.org/?probe=984cf8fd47) | Apr 14, 2023 |
| Acer          | Aspire E5-575G              | [39afaea9e3](https://linux-hardware.org/?probe=39afaea9e3) | Apr 14, 2023 |
| HP            | Laptop 17-cp0xxx            | [6fdb6931f0](https://linux-hardware.org/?probe=6fdb6931f0) | Apr 14, 2023 |
| Acer          | Extensa 5635Z               | [b3c99bf352](https://linux-hardware.org/?probe=b3c99bf352) | Apr 14, 2023 |
| Notebook      | N7x0WU                      | [5d37070bf0](https://linux-hardware.org/?probe=5d37070bf0) | Apr 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [6af1f492c4](https://linux-hardware.org/?probe=6af1f492c4) | Apr 14, 2023 |
| Lenovo        | Flex 2-14 20404             | [c76a516113](https://linux-hardware.org/?probe=c76a516113) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | [9ab8e04a20](https://linux-hardware.org/?probe=9ab8e04a20) | Apr 14, 2023 |
| Acer          | AO756                       | [58efd2f87f](https://linux-hardware.org/?probe=58efd2f87f) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | [1a327ce647](https://linux-hardware.org/?probe=1a327ce647) | Apr 13, 2023 |
| Dell          | Inspiron 1525               | [bc3ccff50c](https://linux-hardware.org/?probe=bc3ccff50c) | Apr 13, 2023 |
| Acer          | Aspire A315-51              | [c3962286cb](https://linux-hardware.org/?probe=c3962286cb) | Apr 13, 2023 |
| Apple         | MacBookPro5,5               | [401c4d8143](https://linux-hardware.org/?probe=401c4d8143) | Apr 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | [abedf2741f](https://linux-hardware.org/?probe=abedf2741f) | Apr 12, 2023 |
| HP            | ZBook 15 G3                 | [5411d789c3](https://linux-hardware.org/?probe=5411d789c3) | Apr 12, 2023 |
| HP            | Pavilion dv6                | [09b80dd551](https://linux-hardware.org/?probe=09b80dd551) | Apr 12, 2023 |
| HP            | Pavilion dv7                | [4363479bf0](https://linux-hardware.org/?probe=4363479bf0) | Apr 12, 2023 |
| Lenovo        | ThinkPad E470 20H2S00700    | [ea2aa5245d](https://linux-hardware.org/?probe=ea2aa5245d) | Apr 11, 2023 |
| Samsung       | 550XCJ/550XCR               | [c074d665d9](https://linux-hardware.org/?probe=c074d665d9) | Apr 11, 2023 |
| Samsung       | 550XCJ/550XCR               | [845a04c326](https://linux-hardware.org/?probe=845a04c326) | Apr 11, 2023 |
| Packard Be... | EasyNote_MX45               | [95935443c0](https://linux-hardware.org/?probe=95935443c0) | Apr 11, 2023 |
| ASUSTek       | X550JF                      | [dff4654bd2](https://linux-hardware.org/?probe=dff4654bd2) | Apr 11, 2023 |
| Acer          | Aspire 5738                 | [c039220e20](https://linux-hardware.org/?probe=c039220e20) | Apr 11, 2023 |
| Dell          | Inspiron 15 5510            | [5d84a5a711](https://linux-hardware.org/?probe=5d84a5a711) | Apr 10, 2023 |
| Apple         | MacBookAir7,2               | [94efe20a0f](https://linux-hardware.org/?probe=94efe20a0f) | Apr 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S0CE1M    | [eb794b0dc7](https://linux-hardware.org/?probe=eb794b0dc7) | Apr 10, 2023 |
| Lenovo        | ThinkPad L470 20J4000LGE    | [fec574fe0d](https://linux-hardware.org/?probe=fec574fe0d) | Apr 10, 2023 |
| Lenovo        | ThinkPad L470 20J4000LGE    | [f97c4e6d47](https://linux-hardware.org/?probe=f97c4e6d47) | Apr 10, 2023 |
| Samsung       | RF511/RF411/RF711           | [ea4fdd80e6](https://linux-hardware.org/?probe=ea4fdd80e6) | Apr 09, 2023 |
| ASUSTek       | X756UQ                      | [bff5545041](https://linux-hardware.org/?probe=bff5545041) | Apr 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [fc28f6d3f0](https://linux-hardware.org/?probe=fc28f6d3f0) | Apr 08, 2023 |
| HP            | ENVY dv6                    | [0d89a1797e](https://linux-hardware.org/?probe=0d89a1797e) | Apr 08, 2023 |
| MSI           | GL65 Leopard 10SCSR         | [3063414a8c](https://linux-hardware.org/?probe=3063414a8c) | Apr 08, 2023 |
| Lenovo        | ThinkPad T450 20BUA05900    | [e771177cca](https://linux-hardware.org/?probe=e771177cca) | Apr 07, 2023 |
| Acer          | TravelMate 5735Z            | [6d50e55675](https://linux-hardware.org/?probe=6d50e55675) | Apr 07, 2023 |
| HP            | Pavilion dv7                | [3ec1e98abd](https://linux-hardware.org/?probe=3ec1e98abd) | Apr 07, 2023 |
| Google        | Reks                        | [25341f2040](https://linux-hardware.org/?probe=25341f2040) | Apr 07, 2023 |
| Google        | Reks                        | [21c7e0c282](https://linux-hardware.org/?probe=21c7e0c282) | Apr 07, 2023 |
| Google        | Terra                       | [09a6a1ca8f](https://linux-hardware.org/?probe=09a6a1ca8f) | Apr 07, 2023 |
| Acer          | TravelMate 5735Z            | [a74c66fc15](https://linux-hardware.org/?probe=a74c66fc15) | Apr 07, 2023 |
| Acer          | TravelMate 5735Z            | [46990342e8](https://linux-hardware.org/?probe=46990342e8) | Apr 06, 2023 |
| Acer          | TravelMate 5735Z            | [6d0065dea2](https://linux-hardware.org/?probe=6d0065dea2) | Apr 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [d5c75a0967](https://linux-hardware.org/?probe=d5c75a0967) | Apr 06, 2023 |
| Dell          | Latitude E7250              | [e5fe0c7962](https://linux-hardware.org/?probe=e5fe0c7962) | Apr 06, 2023 |
| Toshiba       | Satellite C855D-12J         | [cb3dedf5e8](https://linux-hardware.org/?probe=cb3dedf5e8) | Apr 05, 2023 |
| Acer          | Aspire E1-532               | [ba90a2c123](https://linux-hardware.org/?probe=ba90a2c123) | Apr 05, 2023 |
| Dell          | Precision M4700             | [1e2be52d80](https://linux-hardware.org/?probe=1e2be52d80) | Apr 05, 2023 |
| Acer          | TravelMate P215-53          | [0808bd0d17](https://linux-hardware.org/?probe=0808bd0d17) | Apr 04, 2023 |
| Apple         | MacBookPro10,2              | [ad5d8f611a](https://linux-hardware.org/?probe=ad5d8f611a) | Apr 04, 2023 |
| Dell          | Latitude 5430               | [6494113c9b](https://linux-hardware.org/?probe=6494113c9b) | Apr 04, 2023 |
| HP            | EliteBook 840 G3            | [36f4574fd4](https://linux-hardware.org/?probe=36f4574fd4) | Apr 03, 2023 |
| Lenovo        | ThinkPad T530 242962G       | [58d0ea734d](https://linux-hardware.org/?probe=58d0ea734d) | Apr 03, 2023 |
| Toshiba       | Satellite Pro C850-1K0      | [893534249a](https://linux-hardware.org/?probe=893534249a) | Apr 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [0f4881cccf](https://linux-hardware.org/?probe=0f4881cccf) | Apr 03, 2023 |
| HP            | EliteBook 850 G6            | [1af731cc92](https://linux-hardware.org/?probe=1af731cc92) | Apr 03, 2023 |
| Clevo         | P170HMx                     | [c963b350fc](https://linux-hardware.org/?probe=c963b350fc) | Apr 03, 2023 |
| Apple         | MacBookAir6,1               | [423c5d2481](https://linux-hardware.org/?probe=423c5d2481) | Apr 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [3034a3d11a](https://linux-hardware.org/?probe=3034a3d11a) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [89d4ef9333](https://linux-hardware.org/?probe=89d4ef9333) | Apr 02, 2023 |
| Acer          | Aspire A515-45              | [8fa60907d5](https://linux-hardware.org/?probe=8fa60907d5) | Apr 02, 2023 |
| Dell          | Precision M4700             | [aea1cc51a5](https://linux-hardware.org/?probe=aea1cc51a5) | Apr 02, 2023 |
| HP            | EliteBook Folio 1040 G3     | [9e25dfd6bb](https://linux-hardware.org/?probe=9e25dfd6bb) | Apr 02, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [e42bc1dd05](https://linux-hardware.org/?probe=e42bc1dd05) | Apr 02, 2023 |
| Acer          | TravelMate P215-53          | [bd1d2b4102](https://linux-hardware.org/?probe=bd1d2b4102) | Apr 02, 2023 |
| Google        | Snappy                      | [16dda325bf](https://linux-hardware.org/?probe=16dda325bf) | Apr 02, 2023 |
| Dell          | Precision 5540              | [f25b25b590](https://linux-hardware.org/?probe=f25b25b590) | Apr 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | [2f2326e574](https://linux-hardware.org/?probe=2f2326e574) | Apr 02, 2023 |
| HP            | Notebook                    | [348d80772f](https://linux-hardware.org/?probe=348d80772f) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | [4787e68a9c](https://linux-hardware.org/?probe=4787e68a9c) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | [12e105f6da](https://linux-hardware.org/?probe=12e105f6da) | Apr 01, 2023 |
| Lenovo        | G50-45 80E3                 | [f75af97954](https://linux-hardware.org/?probe=f75af97954) | Apr 01, 2023 |
| HP            | Pavilion dv7                | [00bbec023a](https://linux-hardware.org/?probe=00bbec023a) | Apr 01, 2023 |
| ASUSTek       | X202E                       | [cdcccb09e7](https://linux-hardware.org/?probe=cdcccb09e7) | Mar 31, 2023 |
| ASUSTek       | X202E                       | [ac12ec53a3](https://linux-hardware.org/?probe=ac12ec53a3) | Mar 31, 2023 |
| Lenovo        | Yoga 3 11 80J8              | [fce7483fa0](https://linux-hardware.org/?probe=fce7483fa0) | Mar 31, 2023 |
| Dell          | Latitude E6330              | [ae7a7254b8](https://linux-hardware.org/?probe=ae7a7254b8) | Mar 31, 2023 |
| Dell          | Latitude E6330              | [2239e12384](https://linux-hardware.org/?probe=2239e12384) | Mar 31, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [3399c2f210](https://linux-hardware.org/?probe=3399c2f210) | Mar 31, 2023 |
| Dell          | Precision M4700             | [7c93bc178e](https://linux-hardware.org/?probe=7c93bc178e) | Mar 31, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [2ca1607b80](https://linux-hardware.org/?probe=2ca1607b80) | Mar 30, 2023 |
| Dell          | XPS 13 7390                 | [990f324256](https://linux-hardware.org/?probe=990f324256) | Mar 30, 2023 |
| Dell          | XPS 13 7390                 | [b6226ae481](https://linux-hardware.org/?probe=b6226ae481) | Mar 30, 2023 |
| Fujitsu       | LIFEBOOK S752               | [bf3d484605](https://linux-hardware.org/?probe=bf3d484605) | Mar 30, 2023 |
| Fujitsu       | LIFEBOOK S752               | [3e4d9fac89](https://linux-hardware.org/?probe=3e4d9fac89) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e85544a3d7](https://linux-hardware.org/?probe=e85544a3d7) | Mar 30, 2023 |
| Dell          | Precision M4800             | [ebd0442adc](https://linux-hardware.org/?probe=ebd0442adc) | Mar 30, 2023 |
| Lenovo        | ThinkPad T60 195143U        | [4de196550b](https://linux-hardware.org/?probe=4de196550b) | Mar 30, 2023 |
| OEGStone      | W54_55SU1,SUW               | [a771622660](https://linux-hardware.org/?probe=a771622660) | Mar 29, 2023 |
| OEGStone      | W54_55SU1,SUW               | [1e0c5a90c9](https://linux-hardware.org/?probe=1e0c5a90c9) | Mar 29, 2023 |
| Unknown       | Unknown                     | [7d3374d52b](https://linux-hardware.org/?probe=7d3374d52b) | Mar 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [77e01c9b12](https://linux-hardware.org/?probe=77e01c9b12) | Mar 29, 2023 |
| Lenovo        | G50-45 80E3                 | [7bfed0aedd](https://linux-hardware.org/?probe=7bfed0aedd) | Mar 29, 2023 |
| Acer          | Aspire A315-23G             | [5c6734f5e6](https://linux-hardware.org/?probe=5c6734f5e6) | Mar 29, 2023 |
| Medion        | P7641 MD99856               | [7347a28d53](https://linux-hardware.org/?probe=7347a28d53) | Mar 28, 2023 |
| HP            | Pavilion dv5000 (EW771EA... | [db28f35ce0](https://linux-hardware.org/?probe=db28f35ce0) | Mar 28, 2023 |
| ASUSTek       | X541SA                      | [f281edd494](https://linux-hardware.org/?probe=f281edd494) | Mar 28, 2023 |
| HP            | EliteBook 840 G3            | [58d5e99cd1](https://linux-hardware.org/?probe=58d5e99cd1) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [9fd0ee0183](https://linux-hardware.org/?probe=9fd0ee0183) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [d0f84e1bd4](https://linux-hardware.org/?probe=d0f84e1bd4) | Mar 27, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [dd84425bc7](https://linux-hardware.org/?probe=dd84425bc7) | Mar 27, 2023 |
| Lenovo        | G50-45 80E3                 | [279d3659a9](https://linux-hardware.org/?probe=279d3659a9) | Mar 26, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [d1f406ffe7](https://linux-hardware.org/?probe=d1f406ffe7) | Mar 26, 2023 |
| Acer          | Nitro AN515-52              | [d2f95decbe](https://linux-hardware.org/?probe=d2f95decbe) | Mar 26, 2023 |
| Acer          | Nitro AN515-52              | [1377a2ea15](https://linux-hardware.org/?probe=1377a2ea15) | Mar 26, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0C40... | [39b2a59543](https://linux-hardware.org/?probe=39b2a59543) | Mar 25, 2023 |
| HUAWEI        | NBD-WXX9                    | [7eb3d40bd8](https://linux-hardware.org/?probe=7eb3d40bd8) | Mar 25, 2023 |
| Packard Be... | H17HV                       | [c4bddccbd8](https://linux-hardware.org/?probe=c4bddccbd8) | Mar 24, 2023 |
| Lenovo        | Z50-75 80EC                 | [d6783c57a6](https://linux-hardware.org/?probe=d6783c57a6) | Mar 24, 2023 |
| Lenovo        | Z50-75 80EC                 | [353666c217](https://linux-hardware.org/?probe=353666c217) | Mar 24, 2023 |
| Dell          | Inspiron 7348               | [4011322039](https://linux-hardware.org/?probe=4011322039) | Mar 24, 2023 |
| HP            | EliteBook 850 G5            | [cde421908c](https://linux-hardware.org/?probe=cde421908c) | Mar 24, 2023 |
| ASUSTek       | N56VJ                       | [da2c5d6ff1](https://linux-hardware.org/?probe=da2c5d6ff1) | Mar 24, 2023 |
| Dell          | Inspiron 15 3511            | [7aa41dd248](https://linux-hardware.org/?probe=7aa41dd248) | Mar 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [32a4fc1880](https://linux-hardware.org/?probe=32a4fc1880) | Mar 23, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [5e97d4fdf3](https://linux-hardware.org/?probe=5e97d4fdf3) | Mar 22, 2023 |
| Apple         | MacBookPro11,2              | [92208949d5](https://linux-hardware.org/?probe=92208949d5) | Mar 22, 2023 |
| Apple         | MacBookPro11,2              | [aa71c25dba](https://linux-hardware.org/?probe=aa71c25dba) | Mar 22, 2023 |
| Unknown       | Unknown                     | [ef5bf53c45](https://linux-hardware.org/?probe=ef5bf53c45) | Mar 22, 2023 |
| Dell          | G3 3579                     | [b6f8dd5ffe](https://linux-hardware.org/?probe=b6f8dd5ffe) | Mar 22, 2023 |
| Unknown       | Unknown                     | [b96104604a](https://linux-hardware.org/?probe=b96104604a) | Mar 22, 2023 |
| Apple         | MacBookPro5,5               | [849f9d23c7](https://linux-hardware.org/?probe=849f9d23c7) | Mar 21, 2023 |
| Lenovo        | ThinkPad X230s 20AHS0070... | [9d86eaf558](https://linux-hardware.org/?probe=9d86eaf558) | Mar 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [4c7add7cd1](https://linux-hardware.org/?probe=4c7add7cd1) | Mar 21, 2023 |
| Dell          | Inspiron 5570               | [e311e9a53a](https://linux-hardware.org/?probe=e311e9a53a) | Mar 21, 2023 |
| HP            | EliteBook 850 G5            | [5ca3a1b044](https://linux-hardware.org/?probe=5ca3a1b044) | Mar 21, 2023 |
| Lenovo        | G570 20079                  | [8657b8d645](https://linux-hardware.org/?probe=8657b8d645) | Mar 21, 2023 |
| ASUSTek       | S551LB                      | [da9a9373a6](https://linux-hardware.org/?probe=da9a9373a6) | Mar 20, 2023 |
| Dell          | Latitude E6420              | [e564f25125](https://linux-hardware.org/?probe=e564f25125) | Mar 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [7bc035af43](https://linux-hardware.org/?probe=7bc035af43) | Mar 20, 2023 |
| Fujitsu       | LIFEBOOK E734               | [0c4119f8b3](https://linux-hardware.org/?probe=0c4119f8b3) | Mar 20, 2023 |
| Samsung       | RF511/RF411/RF711           | [bff0b1d8a4](https://linux-hardware.org/?probe=bff0b1d8a4) | Mar 20, 2023 |
| Dell          | Latitude 7480               | [00d8228ec6](https://linux-hardware.org/?probe=00d8228ec6) | Mar 20, 2023 |
| TUXEDO        | N13xWU                      | [e9614af654](https://linux-hardware.org/?probe=e9614af654) | Mar 19, 2023 |
| Dell          | Latitude 7480               | [bbdb75bdce](https://linux-hardware.org/?probe=bbdb75bdce) | Mar 19, 2023 |
| HP            | Pavilion g7                 | [e591ea2173](https://linux-hardware.org/?probe=e591ea2173) | Mar 19, 2023 |
| Lenovo        | ThinkPad T540p 20BE00B8M... | [4cb81db618](https://linux-hardware.org/?probe=4cb81db618) | Mar 19, 2023 |
| Acer          | Aspire V5-552PG             | [d895f0f391](https://linux-hardware.org/?probe=d895f0f391) | Mar 19, 2023 |
| Toshiba       | Satellite C655              | [229dcc2cb0](https://linux-hardware.org/?probe=229dcc2cb0) | Mar 19, 2023 |
| Toshiba       | Satellite C655              | [5037090da8](https://linux-hardware.org/?probe=5037090da8) | Mar 19, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [eea214ee38](https://linux-hardware.org/?probe=eea214ee38) | Mar 18, 2023 |
| HP            | Laptop 14-cm0xxx            | [b939c61b5a](https://linux-hardware.org/?probe=b939c61b5a) | Mar 18, 2023 |
| Samsung       | RF511/RF411/RF711           | [f3a832587b](https://linux-hardware.org/?probe=f3a832587b) | Mar 18, 2023 |
| HP            | ProBook 470 G3              | [3cdb0bbdf6](https://linux-hardware.org/?probe=3cdb0bbdf6) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [2020cf3584](https://linux-hardware.org/?probe=2020cf3584) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [e7ebc0ec0e](https://linux-hardware.org/?probe=e7ebc0ec0e) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [c343e79a84](https://linux-hardware.org/?probe=c343e79a84) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [5391c84cf4](https://linux-hardware.org/?probe=5391c84cf4) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [8fcb466fab](https://linux-hardware.org/?probe=8fcb466fab) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [7aa3efb2fd](https://linux-hardware.org/?probe=7aa3efb2fd) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [8319fcb9da](https://linux-hardware.org/?probe=8319fcb9da) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [6bf9694348](https://linux-hardware.org/?probe=6bf9694348) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [c3c0ef4a31](https://linux-hardware.org/?probe=c3c0ef4a31) | Mar 17, 2023 |
| HP            | 255 G3                      | [3e5f860704](https://linux-hardware.org/?probe=3e5f860704) | Mar 17, 2023 |
| Samsung       | RF511/RF411/RF711           | [ecb08b3c5e](https://linux-hardware.org/?probe=ecb08b3c5e) | Mar 17, 2023 |
| Dell          | Latitude 7480               | [ee6015f962](https://linux-hardware.org/?probe=ee6015f962) | Mar 17, 2023 |
| MSI           | GF72 8RE                    | [4610dffdcc](https://linux-hardware.org/?probe=4610dffdcc) | Mar 17, 2023 |
| HP            | Notebook                    | [e901631805](https://linux-hardware.org/?probe=e901631805) | Mar 17, 2023 |
| Dell          | Precision M6800             | [db62a370ed](https://linux-hardware.org/?probe=db62a370ed) | Mar 16, 2023 |
| HP            | EliteBook 8460p             | [e8d00684ac](https://linux-hardware.org/?probe=e8d00684ac) | Mar 16, 2023 |
| PC Special... | P65_67RSRP                  | [71a45943c1](https://linux-hardware.org/?probe=71a45943c1) | Mar 16, 2023 |
| HP            | EliteBook 840 G6            | [57f2de5da4](https://linux-hardware.org/?probe=57f2de5da4) | Mar 16, 2023 |
| HP            | EliteBook 840 G6            | [2a316e6d03](https://linux-hardware.org/?probe=2a316e6d03) | Mar 16, 2023 |
| Dell          | Latitude 7480               | [72069037ca](https://linux-hardware.org/?probe=72069037ca) | Mar 16, 2023 |
| Samsung       | 550XBE/350XBE               | [3f7d27d637](https://linux-hardware.org/?probe=3f7d27d637) | Mar 16, 2023 |
| HP            | Laptop 14-cf3xxx            | [bdb510861b](https://linux-hardware.org/?probe=bdb510861b) | Mar 16, 2023 |
| HP            | Laptop 14-cf3xxx            | [75a93c0ac6](https://linux-hardware.org/?probe=75a93c0ac6) | Mar 16, 2023 |
| Samsung       | 550XBE/350XBE               | [e670ea3583](https://linux-hardware.org/?probe=e670ea3583) | Mar 16, 2023 |
| Acer          | Aspire ES1-521              | [b78130eae1](https://linux-hardware.org/?probe=b78130eae1) | Mar 16, 2023 |
| Acer          | Aspire ES1-521              | [8ea6223dc5](https://linux-hardware.org/?probe=8ea6223dc5) | Mar 16, 2023 |
| Acer          | AO756                       | [21ba8b2996](https://linux-hardware.org/?probe=21ba8b2996) | Mar 15, 2023 |
| Apple         | MacBook5,2                  | [c8c6ab5fce](https://linux-hardware.org/?probe=c8c6ab5fce) | Mar 15, 2023 |
| Acer          | Aspire 7720                 | [0f040d8292](https://linux-hardware.org/?probe=0f040d8292) | Mar 15, 2023 |
| HP            | Mini 210-1000               | [cccfcdba22](https://linux-hardware.org/?probe=cccfcdba22) | Mar 15, 2023 |
| Apple         | MacBook5,2                  | [634ae1ae2b](https://linux-hardware.org/?probe=634ae1ae2b) | Mar 14, 2023 |
| ASUSTek       | ZenBook UX534FAC_UX533FA... | [83351958e6](https://linux-hardware.org/?probe=83351958e6) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [a897cf713a](https://linux-hardware.org/?probe=a897cf713a) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [63cbbd1f57](https://linux-hardware.org/?probe=63cbbd1f57) | Mar 14, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | [f5cbc232d7](https://linux-hardware.org/?probe=f5cbc232d7) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [aeb56fbebc](https://linux-hardware.org/?probe=aeb56fbebc) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [ee034131c0](https://linux-hardware.org/?probe=ee034131c0) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [438caf3588](https://linux-hardware.org/?probe=438caf3588) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [57d173995a](https://linux-hardware.org/?probe=57d173995a) | Mar 14, 2023 |
| Acer          | Aspire 7739G                | [aeff2df11c](https://linux-hardware.org/?probe=aeff2df11c) | Mar 14, 2023 |
| Lenovo        | Flex 2-14 20404             | [812104dae3](https://linux-hardware.org/?probe=812104dae3) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [27c3c24dfc](https://linux-hardware.org/?probe=27c3c24dfc) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [714f8e1321](https://linux-hardware.org/?probe=714f8e1321) | Mar 14, 2023 |
| Acer          | Aspire 7720                 | [b80fa5f7ff](https://linux-hardware.org/?probe=b80fa5f7ff) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [500bee4bb7](https://linux-hardware.org/?probe=500bee4bb7) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [189b1a8ec7](https://linux-hardware.org/?probe=189b1a8ec7) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [9be2c9ee2b](https://linux-hardware.org/?probe=9be2c9ee2b) | Mar 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [054bb62a67](https://linux-hardware.org/?probe=054bb62a67) | Mar 14, 2023 |
| Lenovo        | Z710 20250                  | [3a99fb6400](https://linux-hardware.org/?probe=3a99fb6400) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [5c4b7a9754](https://linux-hardware.org/?probe=5c4b7a9754) | Mar 13, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [6c76af84cb](https://linux-hardware.org/?probe=6c76af84cb) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [481073d13f](https://linux-hardware.org/?probe=481073d13f) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [497a7bdef5](https://linux-hardware.org/?probe=497a7bdef5) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [07ceb1e102](https://linux-hardware.org/?probe=07ceb1e102) | Mar 13, 2023 |
| ASUSTek       | GL753VE                     | [8100c63113](https://linux-hardware.org/?probe=8100c63113) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [79fdcb1951](https://linux-hardware.org/?probe=79fdcb1951) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [73e4261a63](https://linux-hardware.org/?probe=73e4261a63) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [44784531d4](https://linux-hardware.org/?probe=44784531d4) | Mar 13, 2023 |
| Acer          | Aspire E5-511               | [5343f73c67](https://linux-hardware.org/?probe=5343f73c67) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [e58e88f5fd](https://linux-hardware.org/?probe=e58e88f5fd) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [267c6693a0](https://linux-hardware.org/?probe=267c6693a0) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [bdb4c28449](https://linux-hardware.org/?probe=bdb4c28449) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [d9226f0ad6](https://linux-hardware.org/?probe=d9226f0ad6) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [906f70a5e9](https://linux-hardware.org/?probe=906f70a5e9) | Mar 13, 2023 |
| Acer          | Aspire 5738                 | [bd231fbff6](https://linux-hardware.org/?probe=bd231fbff6) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [fc75288cce](https://linux-hardware.org/?probe=fc75288cce) | Mar 12, 2023 |
| HP            | ZBook 17 G3                 | [f69ef4ff89](https://linux-hardware.org/?probe=f69ef4ff89) | Mar 12, 2023 |
| Lenovo        | ThinkPad X131e 3367AG9      | [0ff86711d1](https://linux-hardware.org/?probe=0ff86711d1) | Mar 12, 2023 |
| Dell          | Latitude 3510               | [13ed29770d](https://linux-hardware.org/?probe=13ed29770d) | Mar 12, 2023 |
| Dell          | Inspiron 5593               | [631b554e46](https://linux-hardware.org/?probe=631b554e46) | Mar 12, 2023 |
| HP            | ProBook 4415s               | [8b974a2717](https://linux-hardware.org/?probe=8b974a2717) | Mar 12, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | [f066472937](https://linux-hardware.org/?probe=f066472937) | Mar 11, 2023 |
| Dell          | Latitude E6430              | [080ad6aa2a](https://linux-hardware.org/?probe=080ad6aa2a) | Mar 11, 2023 |
| Acer          | Swift SF314-43              | [dc1a94966b](https://linux-hardware.org/?probe=dc1a94966b) | Mar 11, 2023 |
| Apple         | MacBook5,2                  | [ffb66872c2](https://linux-hardware.org/?probe=ffb66872c2) | Mar 10, 2023 |
| Apple         | MacBook5,2                  | [9736a383d7](https://linux-hardware.org/?probe=9736a383d7) | Mar 10, 2023 |
| Apple         | MacBook5,2                  | [f9bd57cf06](https://linux-hardware.org/?probe=f9bd57cf06) | Mar 10, 2023 |
| Apple         | MacBook5,2                  | [a71d5d0d96](https://linux-hardware.org/?probe=a71d5d0d96) | Mar 10, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [87aa621d6a](https://linux-hardware.org/?probe=87aa621d6a) | Mar 10, 2023 |
| Dell          | Latitude 7285               | [dfc4961010](https://linux-hardware.org/?probe=dfc4961010) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | [91985ffa00](https://linux-hardware.org/?probe=91985ffa00) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | [40499e56d1](https://linux-hardware.org/?probe=40499e56d1) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | [3abbf961d5](https://linux-hardware.org/?probe=3abbf961d5) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | [734afe2673](https://linux-hardware.org/?probe=734afe2673) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | [364b9159c4](https://linux-hardware.org/?probe=364b9159c4) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3daf833362](https://linux-hardware.org/?probe=3daf833362) | Mar 09, 2023 |
| HP            | Compaq nx9420 (ES446EA#A... | [b876c92a6e](https://linux-hardware.org/?probe=b876c92a6e) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK U7312              | [74bbf2c865](https://linux-hardware.org/?probe=74bbf2c865) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7f3075e65e](https://linux-hardware.org/?probe=7f3075e65e) | Mar 08, 2023 |
| Medion        | E122X                       | [dad02f1ac7](https://linux-hardware.org/?probe=dad02f1ac7) | Mar 08, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [07f425d57f](https://linux-hardware.org/?probe=07f425d57f) | Mar 08, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f62ef69dcc](https://linux-hardware.org/?probe=f62ef69dcc) | Mar 08, 2023 |
| HP            | ZBook Studio G3             | [d059dad473](https://linux-hardware.org/?probe=d059dad473) | Mar 08, 2023 |
| Apple         | MacBook5,2                  | [e6cbad4861](https://linux-hardware.org/?probe=e6cbad4861) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [6fa1bc8547](https://linux-hardware.org/?probe=6fa1bc8547) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [ce9ba5580b](https://linux-hardware.org/?probe=ce9ba5580b) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [9a8f396913](https://linux-hardware.org/?probe=9a8f396913) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [07709f5f79](https://linux-hardware.org/?probe=07709f5f79) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [8bbc04cb55](https://linux-hardware.org/?probe=8bbc04cb55) | Mar 07, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [a3682a5cb6](https://linux-hardware.org/?probe=a3682a5cb6) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [7b1918ab47](https://linux-hardware.org/?probe=7b1918ab47) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [0d996d4041](https://linux-hardware.org/?probe=0d996d4041) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [eb4c28b498](https://linux-hardware.org/?probe=eb4c28b498) | Mar 07, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [124045e654](https://linux-hardware.org/?probe=124045e654) | Mar 07, 2023 |
| HP            | ZBook 15 G3                 | [b00f87c99b](https://linux-hardware.org/?probe=b00f87c99b) | Mar 06, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [119a07048d](https://linux-hardware.org/?probe=119a07048d) | Mar 06, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [91db409270](https://linux-hardware.org/?probe=91db409270) | Mar 06, 2023 |
| Acer          | Aspire E1-571               | [2194ce4568](https://linux-hardware.org/?probe=2194ce4568) | Mar 06, 2023 |
| MSI           | PS42 8RB                    | [57231416e1](https://linux-hardware.org/?probe=57231416e1) | Mar 06, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [fc381c78e7](https://linux-hardware.org/?probe=fc381c78e7) | Mar 05, 2023 |
| Apple         | MacBookPro6,2               | [308b516329](https://linux-hardware.org/?probe=308b516329) | Mar 05, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [ca566e314e](https://linux-hardware.org/?probe=ca566e314e) | Mar 05, 2023 |
| Acer          | Aspire A315-54              | [cadbbe841e](https://linux-hardware.org/?probe=cadbbe841e) | Mar 05, 2023 |
| Dell          | G5 5500                     | [7da5494dea](https://linux-hardware.org/?probe=7da5494dea) | Mar 05, 2023 |
| HP            | G42                         | [7dee433139](https://linux-hardware.org/?probe=7dee433139) | Mar 05, 2023 |
| HP            | EliteBook 840 G3            | [14211fd55f](https://linux-hardware.org/?probe=14211fd55f) | Mar 04, 2023 |
| Dell          | Latitude E5450              | [2f16482775](https://linux-hardware.org/?probe=2f16482775) | Mar 04, 2023 |
| Intel         | powered classmate PC        | [bfd724fd2f](https://linux-hardware.org/?probe=bfd724fd2f) | Mar 04, 2023 |
| SANTECH       | NHx0DB,DE                   | [9ebc94ec48](https://linux-hardware.org/?probe=9ebc94ec48) | Mar 04, 2023 |
| HP            | EliteBook 830 G5            | [82acbe37f7](https://linux-hardware.org/?probe=82acbe37f7) | Mar 04, 2023 |
| Dell          | Inspiron 3593               | [4e2f59d17e](https://linux-hardware.org/?probe=4e2f59d17e) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | [1bfad93a1e](https://linux-hardware.org/?probe=1bfad93a1e) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | [f782f8e288](https://linux-hardware.org/?probe=f782f8e288) | Mar 04, 2023 |
| HP            | Laptop 14s-dq1xxx           | [29fa7c0b23](https://linux-hardware.org/?probe=29fa7c0b23) | Mar 04, 2023 |
| HP            | 255 G8 Notebook PC          | [7dc484b236](https://linux-hardware.org/?probe=7dc484b236) | Mar 03, 2023 |
| HP            | 255 G8 Notebook PC          | [b7e4822b00](https://linux-hardware.org/?probe=b7e4822b00) | Mar 03, 2023 |
| HUAWEI        | BOHB-WAX9                   | [cdaf43afa8](https://linux-hardware.org/?probe=cdaf43afa8) | Mar 03, 2023 |
| Acer          | Aspire E1-522               | [f102669f1f](https://linux-hardware.org/?probe=f102669f1f) | Mar 03, 2023 |
| Unknown       | Unknown                     | [7afe06d070](https://linux-hardware.org/?probe=7afe06d070) | Mar 03, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [54a92cd736](https://linux-hardware.org/?probe=54a92cd736) | Mar 03, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [916405bd1c](https://linux-hardware.org/?probe=916405bd1c) | Mar 03, 2023 |
| HP            | 635                         | [108b9443ea](https://linux-hardware.org/?probe=108b9443ea) | Mar 03, 2023 |
| Dell          | Latitude E7440              | [36439d1a64](https://linux-hardware.org/?probe=36439d1a64) | Mar 03, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [180f5c9379](https://linux-hardware.org/?probe=180f5c9379) | Mar 03, 2023 |
| Dell          | Vostro1710                  | [c24eab7e3d](https://linux-hardware.org/?probe=c24eab7e3d) | Mar 02, 2023 |
| Acer          | Aspire 1640Z                | [915a8900d0](https://linux-hardware.org/?probe=915a8900d0) | Mar 02, 2023 |
| Dell          | Latitude E7440              | [b84f760e8e](https://linux-hardware.org/?probe=b84f760e8e) | Mar 02, 2023 |
| ASUSTek       | X556UR                      | [70c4807d21](https://linux-hardware.org/?probe=70c4807d21) | Mar 02, 2023 |
| MSI           | Creator 15M A9SD            | [b19d8d936c](https://linux-hardware.org/?probe=b19d8d936c) | Mar 02, 2023 |
| Dell          | Latitude 3510               | [0bad8d504d](https://linux-hardware.org/?probe=0bad8d504d) | Mar 02, 2023 |
| PC Special... | 14 Fusion IV                | [e465178d82](https://linux-hardware.org/?probe=e465178d82) | Mar 02, 2023 |
| Dell          | XPS 15 9520                 | [2894a5929b](https://linux-hardware.org/?probe=2894a5929b) | Mar 02, 2023 |
| HUAWEI        | NBD-WXX9                    | [9036fa2ef1](https://linux-hardware.org/?probe=9036fa2ef1) | Mar 02, 2023 |
| GMKtec        | NucBox5                     | [fc11280fe6](https://linux-hardware.org/?probe=fc11280fe6) | Mar 02, 2023 |
| Acer          | TravelMate 5720             | [2e0c5ff8f1](https://linux-hardware.org/?probe=2e0c5ff8f1) | Mar 01, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [da2fc6826a](https://linux-hardware.org/?probe=da2fc6826a) | Mar 01, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [52ecc1a9fb](https://linux-hardware.org/?probe=52ecc1a9fb) | Mar 01, 2023 |
| HP            | ProBook 4415s               | [4e909ec0ad](https://linux-hardware.org/?probe=4e909ec0ad) | Mar 01, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [1165717061](https://linux-hardware.org/?probe=1165717061) | Feb 28, 2023 |
| TUXEDO        | Aura 15 Gen2                | [26a7db2ed8](https://linux-hardware.org/?probe=26a7db2ed8) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [3fa4d926e0](https://linux-hardware.org/?probe=3fa4d926e0) | Feb 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | [b4bfab8974](https://linux-hardware.org/?probe=b4bfab8974) | Feb 28, 2023 |
| HP            | ProBook 6570b               | [3692011e3f](https://linux-hardware.org/?probe=3692011e3f) | Feb 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [83a611b1ab](https://linux-hardware.org/?probe=83a611b1ab) | Feb 27, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [ccac327e17](https://linux-hardware.org/?probe=ccac327e17) | Feb 27, 2023 |
| Dell          | Latitude 5400               | [b788c61c95](https://linux-hardware.org/?probe=b788c61c95) | Feb 27, 2023 |
| Dell          | Latitude 3510               | [de938c4962](https://linux-hardware.org/?probe=de938c4962) | Feb 27, 2023 |
| ASUSTek       | K52F                        | [fa30ea101a](https://linux-hardware.org/?probe=fa30ea101a) | Feb 27, 2023 |
| HP            | Pavilion g6                 | [41e4ef16e4](https://linux-hardware.org/?probe=41e4ef16e4) | Feb 26, 2023 |
| Panasonic     | CF-31WEUEEBE                | [40782ba0a7](https://linux-hardware.org/?probe=40782ba0a7) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430 2349GUU       | [95cc420bd5](https://linux-hardware.org/?probe=95cc420bd5) | Feb 26, 2023 |
| Medion        | BEAST X25                   | [3263e2862a](https://linux-hardware.org/?probe=3263e2862a) | Feb 26, 2023 |
| HP            | 250 G7 Notebook PC          | [9e587033a4](https://linux-hardware.org/?probe=9e587033a4) | Feb 26, 2023 |
| HP            | Compaq 6730b (FU594ES#AB... | [810cdb1ad1](https://linux-hardware.org/?probe=810cdb1ad1) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | [28bb1541b4](https://linux-hardware.org/?probe=28bb1541b4) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | [8906540d72](https://linux-hardware.org/?probe=8906540d72) | Feb 26, 2023 |
| Lenovo        | ThinkPad X13s Gen 1 21BX... | [633fb08804](https://linux-hardware.org/?probe=633fb08804) | Feb 26, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [3b2a19c835](https://linux-hardware.org/?probe=3b2a19c835) | Feb 26, 2023 |
| HP            | ProBook 445 G7              | [f2671a0f62](https://linux-hardware.org/?probe=f2671a0f62) | Feb 25, 2023 |
| ASUSTek       | X551CA                      | [c8ead0e580](https://linux-hardware.org/?probe=c8ead0e580) | Feb 25, 2023 |
| Unknown       | T3 MRD                      | [ae88920ea5](https://linux-hardware.org/?probe=ae88920ea5) | Feb 25, 2023 |
| Acer          | Nitro AN517-55              | [76e7c1c236](https://linux-hardware.org/?probe=76e7c1c236) | Feb 25, 2023 |
| HUAWEI        | WRT-WX9                     | [d49316c5e8](https://linux-hardware.org/?probe=d49316c5e8) | Feb 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [67e31f8e42](https://linux-hardware.org/?probe=67e31f8e42) | Feb 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [2bb4e30118](https://linux-hardware.org/?probe=2bb4e30118) | Feb 25, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [f1db9ad466](https://linux-hardware.org/?probe=f1db9ad466) | Feb 25, 2023 |
| Acer          | Aspire A315-54              | [ff08a846b0](https://linux-hardware.org/?probe=ff08a846b0) | Feb 25, 2023 |
| Unknown       | Unknown                     | [2c5d6ab621](https://linux-hardware.org/?probe=2c5d6ab621) | Feb 25, 2023 |
| HP            | Pavilion g6                 | [5cde621e0a](https://linux-hardware.org/?probe=5cde621e0a) | Feb 24, 2023 |
| Acer          | AO756                       | [ca83ee78ec](https://linux-hardware.org/?probe=ca83ee78ec) | Feb 24, 2023 |
| Lenovo        | KaiTian N70z G1d            | [cbc8e4e008](https://linux-hardware.org/?probe=cbc8e4e008) | Feb 24, 2023 |
| ASUSTek       | X551CA                      | [62b46afbb8](https://linux-hardware.org/?probe=62b46afbb8) | Feb 24, 2023 |
| Toshiba       | IS 1412                     | [c2ca1fb2f3](https://linux-hardware.org/?probe=c2ca1fb2f3) | Feb 24, 2023 |
| HP            | Presario CQ57               | [b41de6d094](https://linux-hardware.org/?probe=b41de6d094) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | [3f28f459bf](https://linux-hardware.org/?probe=3f28f459bf) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | [8ed4158090](https://linux-hardware.org/?probe=8ed4158090) | Feb 24, 2023 |
| Dell          | Latitude D620               | [fba80b099d](https://linux-hardware.org/?probe=fba80b099d) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [5da2f709bb](https://linux-hardware.org/?probe=5da2f709bb) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [bf32299a30](https://linux-hardware.org/?probe=bf32299a30) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [54279e4e30](https://linux-hardware.org/?probe=54279e4e30) | Feb 24, 2023 |
| HP            | EliteBook Folio 9480m       | [788e0929de](https://linux-hardware.org/?probe=788e0929de) | Feb 24, 2023 |
| Samsung       | N150P                       | [662488621d](https://linux-hardware.org/?probe=662488621d) | Feb 24, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [885478dd47](https://linux-hardware.org/?probe=885478dd47) | Feb 23, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [53eb80a44b](https://linux-hardware.org/?probe=53eb80a44b) | Feb 23, 2023 |
| Lenovo        | ThinkPad T410 2537CS0       | [8d4b399341](https://linux-hardware.org/?probe=8d4b399341) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [53d46c67f9](https://linux-hardware.org/?probe=53d46c67f9) | Feb 23, 2023 |
| LincPlus      | P2                          | [5d4e528621](https://linux-hardware.org/?probe=5d4e528621) | Feb 23, 2023 |
| Lenovo        | ThinkPad E14 20RA0036HV     | [eef601ff61](https://linux-hardware.org/?probe=eef601ff61) | Feb 23, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [09070f52bb](https://linux-hardware.org/?probe=09070f52bb) | Feb 23, 2023 |
| Dell          | Inspiron 5566               | [0233d7525d](https://linux-hardware.org/?probe=0233d7525d) | Feb 22, 2023 |
| Fujitsu       | LIFEBOOK E753               | [8fa3315cca](https://linux-hardware.org/?probe=8fa3315cca) | Feb 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [8227fec538](https://linux-hardware.org/?probe=8227fec538) | Feb 22, 2023 |
| Acer          | Aspire A315-54              | [7cf8754a48](https://linux-hardware.org/?probe=7cf8754a48) | Feb 22, 2023 |
| Acer          | AO756                       | [58f52941c7](https://linux-hardware.org/?probe=58f52941c7) | Feb 22, 2023 |
| ASUSTek       | X556UQ                      | [8f645fa6fc](https://linux-hardware.org/?probe=8f645fa6fc) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470 20HDS1DL03    | [25e1a3f801](https://linux-hardware.org/?probe=25e1a3f801) | Feb 21, 2023 |
| Dell          | Latitude E6430              | [80c9785ef0](https://linux-hardware.org/?probe=80c9785ef0) | Feb 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | [1c0772ccd7](https://linux-hardware.org/?probe=1c0772ccd7) | Feb 21, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [6ab7953740](https://linux-hardware.org/?probe=6ab7953740) | Feb 20, 2023 |
| Notebook      | PB50_70RF,RD,RC             | [b24f005b1d](https://linux-hardware.org/?probe=b24f005b1d) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | [19d29283ed](https://linux-hardware.org/?probe=19d29283ed) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | [8d1bb46519](https://linux-hardware.org/?probe=8d1bb46519) | Feb 20, 2023 |
| Acer          | Extensa 2520G               | [823c5829a9](https://linux-hardware.org/?probe=823c5829a9) | Feb 20, 2023 |
| Lenovo        | ThinkPad T430 2349PZG       | [7bd3c5a555](https://linux-hardware.org/?probe=7bd3c5a555) | Feb 20, 2023 |
| Acer          | Aspire V5-573G              | [376b35f5b6](https://linux-hardware.org/?probe=376b35f5b6) | Feb 20, 2023 |
| Dell          | Latitude E7270              | [4eb17c846c](https://linux-hardware.org/?probe=4eb17c846c) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | [234358d23e](https://linux-hardware.org/?probe=234358d23e) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | [1b75d34b95](https://linux-hardware.org/?probe=1b75d34b95) | Feb 20, 2023 |
| Notebook      | W54_55SU1,SUW               | [5a296bed7f](https://linux-hardware.org/?probe=5a296bed7f) | Feb 19, 2023 |
| Acer          | Nitro AN515-55              | [3158f1e0d5](https://linux-hardware.org/?probe=3158f1e0d5) | Feb 18, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [8907f179e9](https://linux-hardware.org/?probe=8907f179e9) | Feb 18, 2023 |
| Lenovo        | ThinkPad E480 20KN001QGE    | [008f40a707](https://linux-hardware.org/?probe=008f40a707) | Feb 18, 2023 |
| Dell          | Latitude E5450              | [56827b29dc](https://linux-hardware.org/?probe=56827b29dc) | Feb 18, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | [32f5d5e200](https://linux-hardware.org/?probe=32f5d5e200) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [4bf1ccfe74](https://linux-hardware.org/?probe=4bf1ccfe74) | Feb 17, 2023 |
| Apple         | MacBookPro9,1               | [4ab4c99cab](https://linux-hardware.org/?probe=4ab4c99cab) | Feb 17, 2023 |
| Dell          | System XPS L702X            | [81f9738975](https://linux-hardware.org/?probe=81f9738975) | Feb 16, 2023 |
| Apple         | MacBookAir6,2               | [46aafc59c4](https://linux-hardware.org/?probe=46aafc59c4) | Feb 16, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [a4fd7cdaa8](https://linux-hardware.org/?probe=a4fd7cdaa8) | Feb 16, 2023 |
| HP            | EliteBook 2530p             | [5398361b68](https://linux-hardware.org/?probe=5398361b68) | Feb 16, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [73787e9141](https://linux-hardware.org/?probe=73787e9141) | Feb 16, 2023 |
| Google        | Grunt                       | [89c633c2c1](https://linux-hardware.org/?probe=89c633c2c1) | Feb 15, 2023 |
| ASUSTek       | K53U                        | [e9a6a69e01](https://linux-hardware.org/?probe=e9a6a69e01) | Feb 15, 2023 |
| Unknown       | T3 MRD                      | [df134a8199](https://linux-hardware.org/?probe=df134a8199) | Feb 14, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [e9faf4ce80](https://linux-hardware.org/?probe=e9faf4ce80) | Feb 14, 2023 |
| Acer          | Aspire V5-572G              | [7f360258ff](https://linux-hardware.org/?probe=7f360258ff) | Feb 14, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [977650806e](https://linux-hardware.org/?probe=977650806e) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [f6bcdb7c6b](https://linux-hardware.org/?probe=f6bcdb7c6b) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [345021f7f6](https://linux-hardware.org/?probe=345021f7f6) | Feb 14, 2023 |
| Lenovo        | ThinkPad P51 20HJS0AR16     | [ad0f22fe34](https://linux-hardware.org/?probe=ad0f22fe34) | Feb 14, 2023 |
| HP            | Laptop 15s-du3xxx           | [4750f3ad3a](https://linux-hardware.org/?probe=4750f3ad3a) | Feb 13, 2023 |
| Dell          | Latitude D630               | [04c083db36](https://linux-hardware.org/?probe=04c083db36) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | [6fe738fa6d](https://linux-hardware.org/?probe=6fe738fa6d) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | [122eded37e](https://linux-hardware.org/?probe=122eded37e) | Feb 13, 2023 |
| Google        | Droid                       | [435ab67598](https://linux-hardware.org/?probe=435ab67598) | Feb 12, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [89c31e6f8c](https://linux-hardware.org/?probe=89c31e6f8c) | Feb 12, 2023 |
| Unknown       | Unknown                     | [72ce8d1929](https://linux-hardware.org/?probe=72ce8d1929) | Feb 12, 2023 |
| HP            | EliteBook 850 G1            | [54e092f58f](https://linux-hardware.org/?probe=54e092f58f) | Feb 12, 2023 |
| HUAWEI        | CREM-WXX9                   | [09266b8b06](https://linux-hardware.org/?probe=09266b8b06) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | [a541cb52eb](https://linux-hardware.org/?probe=a541cb52eb) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | [35563886e8](https://linux-hardware.org/?probe=35563886e8) | Feb 12, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [b54b603772](https://linux-hardware.org/?probe=b54b603772) | Feb 12, 2023 |
| Apple         | MacBookPro10,2              | [4a6ea9bd99](https://linux-hardware.org/?probe=4a6ea9bd99) | Feb 12, 2023 |
| Apple         | MacBookPro10,2              | [063d6eb482](https://linux-hardware.org/?probe=063d6eb482) | Feb 12, 2023 |
| Lenovo        | Z50-70 20354                | [3932889971](https://linux-hardware.org/?probe=3932889971) | Feb 11, 2023 |
| Notebook      | MAM2120                     | [300a622d96](https://linux-hardware.org/?probe=300a622d96) | Feb 11, 2023 |
| Lenovo        | Z710 20250                  | [94ee6da4d3](https://linux-hardware.org/?probe=94ee6da4d3) | Feb 11, 2023 |
| HP            | Pavilion g6                 | [27323a90bb](https://linux-hardware.org/?probe=27323a90bb) | Feb 11, 2023 |
| Acer          | Predator G9-793             | [8c11736bf0](https://linux-hardware.org/?probe=8c11736bf0) | Feb 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [20a75bea61](https://linux-hardware.org/?probe=20a75bea61) | Feb 11, 2023 |
| HP            | Pavilion g6                 | [35b93693a5](https://linux-hardware.org/?probe=35b93693a5) | Feb 10, 2023 |
| Dell          | Latitude 7370               | [30c62c9e44](https://linux-hardware.org/?probe=30c62c9e44) | Feb 10, 2023 |
| Dell          | Latitude 7370               | [b4e7a5cb63](https://linux-hardware.org/?probe=b4e7a5cb63) | Feb 10, 2023 |
| ASUSTek       | N751JX                      | [fd591a3e67](https://linux-hardware.org/?probe=fd591a3e67) | Feb 10, 2023 |
| Novatech      | NL40_50CU                   | [cca307c7db](https://linux-hardware.org/?probe=cca307c7db) | Feb 10, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [7ac6f508b2](https://linux-hardware.org/?probe=7ac6f508b2) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [8239d80ae0](https://linux-hardware.org/?probe=8239d80ae0) | Feb 10, 2023 |
| IBM           | ThinkPad T43 18714AG        | [0730c9228d](https://linux-hardware.org/?probe=0730c9228d) | Feb 10, 2023 |
| Acer          | Aspire ES1-111M             | [82eea49fcd](https://linux-hardware.org/?probe=82eea49fcd) | Feb 09, 2023 |
| Acer          | Aspire ES1-111M             | [accbac47d5](https://linux-hardware.org/?probe=accbac47d5) | Feb 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [02adcb8587](https://linux-hardware.org/?probe=02adcb8587) | Feb 09, 2023 |
| Acer          | Aspire E1-571               | [fe1dac78bb](https://linux-hardware.org/?probe=fe1dac78bb) | Feb 09, 2023 |
| Dell          | Latitude E7250              | [e3c1b1e038](https://linux-hardware.org/?probe=e3c1b1e038) | Feb 09, 2023 |
| Lenovo        | Legion Y520-15IKBN 80WK     | [ec17af9e06](https://linux-hardware.org/?probe=ec17af9e06) | Feb 09, 2023 |
| AMI           | Cherry Trail CR             | [e7eab93323](https://linux-hardware.org/?probe=e7eab93323) | Feb 09, 2023 |
| Dell          | Latitude E6330              | [291e0fd64f](https://linux-hardware.org/?probe=291e0fd64f) | Feb 08, 2023 |
| HUAWEI        | CREM-WXX9                   | [965758f3ea](https://linux-hardware.org/?probe=965758f3ea) | Feb 08, 2023 |
| Acer          | Aspire A515-52G             | [e521c55b1a](https://linux-hardware.org/?probe=e521c55b1a) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [cc897fe72d](https://linux-hardware.org/?probe=cc897fe72d) | Feb 08, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | [9f6079baf2](https://linux-hardware.org/?probe=9f6079baf2) | Feb 08, 2023 |
| Dell          | Inspiron 5555               | [f5aeb173ba](https://linux-hardware.org/?probe=f5aeb173ba) | Feb 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [def4679f84](https://linux-hardware.org/?probe=def4679f84) | Feb 07, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | [db2f72084a](https://linux-hardware.org/?probe=db2f72084a) | Feb 07, 2023 |
| Panasonic     | CF-54-1                     | [32a2acc07e](https://linux-hardware.org/?probe=32a2acc07e) | Feb 07, 2023 |
| Samsung       | R530/R730                   | [f212e58647](https://linux-hardware.org/?probe=f212e58647) | Feb 07, 2023 |
| Samsung       | R530/R730                   | [9ccb976ccd](https://linux-hardware.org/?probe=9ccb976ccd) | Feb 07, 2023 |
| Dell          | Latitude E7250              | [b4a7701aa4](https://linux-hardware.org/?probe=b4a7701aa4) | Feb 07, 2023 |
| Dell          | Precision 5570              | [d279e97c00](https://linux-hardware.org/?probe=d279e97c00) | Feb 07, 2023 |
| Toshiba       | Satellite C655              | [a0c2eb7db1](https://linux-hardware.org/?probe=a0c2eb7db1) | Feb 07, 2023 |
| Google        | Terra                       | [edfe00266c](https://linux-hardware.org/?probe=edfe00266c) | Feb 06, 2023 |
| SLIMBOOK      | Essential15L                | [e2af97d5d3](https://linux-hardware.org/?probe=e2af97d5d3) | Feb 06, 2023 |
| ASUSTek       | X71Q                        | [c89b078e8f](https://linux-hardware.org/?probe=c89b078e8f) | Feb 06, 2023 |
| Aquarius      | NS585                       | [e9deef3f9e](https://linux-hardware.org/?probe=e9deef3f9e) | Feb 06, 2023 |
| Lenovo        | ThinkPad X250 20CLS2TQ22    | [112a65a03e](https://linux-hardware.org/?probe=112a65a03e) | Feb 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [413341361a](https://linux-hardware.org/?probe=413341361a) | Feb 05, 2023 |
| Toshiba       | Satellite C660              | [b2247eafed](https://linux-hardware.org/?probe=b2247eafed) | Feb 05, 2023 |
| Acer          | Aspire A317-53              | [2f56f41681](https://linux-hardware.org/?probe=2f56f41681) | Feb 05, 2023 |
| Google        | Ampton                      | [74d5b6aa4d](https://linux-hardware.org/?probe=74d5b6aa4d) | Feb 05, 2023 |
| Google        | Ampton                      | [2785bde3f9](https://linux-hardware.org/?probe=2785bde3f9) | Feb 05, 2023 |
| HP            | 255 G3                      | [dfa2e96880](https://linux-hardware.org/?probe=dfa2e96880) | Feb 05, 2023 |
| Apple         | MacBookAir7,2               | [29d133e858](https://linux-hardware.org/?probe=29d133e858) | Feb 05, 2023 |
| Acer          | Aspire E1-772               | [147ad71a27](https://linux-hardware.org/?probe=147ad71a27) | Feb 05, 2023 |
| Notebook      | W65_67SJ                    | [870af12011](https://linux-hardware.org/?probe=870af12011) | Feb 05, 2023 |
| Lenovo        | G50-45 80E3                 | [229050fbe5](https://linux-hardware.org/?probe=229050fbe5) | Feb 05, 2023 |
| ASUSTek       | F5SL                        | [1e5bb7661e](https://linux-hardware.org/?probe=1e5bb7661e) | Feb 04, 2023 |
| Lenovo        | G50-45 80E3                 | [885ad2ae95](https://linux-hardware.org/?probe=885ad2ae95) | Feb 04, 2023 |
| Toshiba       | Satellite P775              | [df8aa8c06a](https://linux-hardware.org/?probe=df8aa8c06a) | Feb 04, 2023 |
| Lenovo        | ThinkPad T440p 20ANS09W0... | [17f9df8f2c](https://linux-hardware.org/?probe=17f9df8f2c) | Feb 03, 2023 |
| Lenovo        | V310-15IKB 80T3             | [a39fb673c7](https://linux-hardware.org/?probe=a39fb673c7) | Feb 03, 2023 |
| HP            | Pavilion 15                 | [5909dd08e7](https://linux-hardware.org/?probe=5909dd08e7) | Feb 03, 2023 |
| Aquarius      | NS585                       | [7e944d88b3](https://linux-hardware.org/?probe=7e944d88b3) | Feb 03, 2023 |
| HP            | ProBook 450 G7              | [ae290fa64e](https://linux-hardware.org/?probe=ae290fa64e) | Feb 03, 2023 |
| HP            | ProBook 450 G7              | [7820377760](https://linux-hardware.org/?probe=7820377760) | Feb 03, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [2f2c8adb0c](https://linux-hardware.org/?probe=2f2c8adb0c) | Feb 02, 2023 |
| Apple         | MacBook5,2                  | [6d7a27b213](https://linux-hardware.org/?probe=6d7a27b213) | Feb 02, 2023 |
| Google        | Babymega                    | [2a8b81c6f4](https://linux-hardware.org/?probe=2a8b81c6f4) | Feb 02, 2023 |
| Dell          | Vostro 3580                 | [7efc294bac](https://linux-hardware.org/?probe=7efc294bac) | Feb 02, 2023 |
| Lenovo        | ThinkPad E495 20NE001GMX    | [29660bbd04](https://linux-hardware.org/?probe=29660bbd04) | Feb 02, 2023 |
| Dell          | Latitude 7480               | [8a7e0b16d5](https://linux-hardware.org/?probe=8a7e0b16d5) | Feb 02, 2023 |
| Dell          | Latitude E6520              | [548b13cd43](https://linux-hardware.org/?probe=548b13cd43) | Feb 02, 2023 |
| Timi          | Mi Laptop Pro 15            | [9deaff7467](https://linux-hardware.org/?probe=9deaff7467) | Feb 02, 2023 |
| Lenovo        | ThinkPad 13 20J10046US      | [85b9d54087](https://linux-hardware.org/?probe=85b9d54087) | Feb 02, 2023 |
| Apple         | MacBook5,2                  | [b8c8ed32e5](https://linux-hardware.org/?probe=b8c8ed32e5) | Feb 01, 2023 |
| Samsung       | 600B4B/600B5B               | [d3cf4446d5](https://linux-hardware.org/?probe=d3cf4446d5) | Feb 01, 2023 |
| Apple         | MacBookAir7,2               | [352c998936](https://linux-hardware.org/?probe=352c998936) | Feb 01, 2023 |
| Toshiba       | Satellite P775              | [c03f7668ac](https://linux-hardware.org/?probe=c03f7668ac) | Feb 01, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | [ac78478b3b](https://linux-hardware.org/?probe=ac78478b3b) | Feb 01, 2023 |
| HP            | Notebook                    | [3cea0a0519](https://linux-hardware.org/?probe=3cea0a0519) | Jan 31, 2023 |
| Fujitsu       | LIFEBOOK S751               | [35948f3b5e](https://linux-hardware.org/?probe=35948f3b5e) | Jan 31, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [3f17be7a85](https://linux-hardware.org/?probe=3f17be7a85) | Jan 30, 2023 |
| MSI           | GE60 0NC/GE60 0ND           | [a7ef98ea02](https://linux-hardware.org/?probe=a7ef98ea02) | Jan 30, 2023 |
| Acer          | Aspire 5552                 | [f1168775a7](https://linux-hardware.org/?probe=f1168775a7) | Jan 30, 2023 |
| Sony          | PCG-Z1VA(UC)                | [db4f48132e](https://linux-hardware.org/?probe=db4f48132e) | Jan 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [933e5a5b96](https://linux-hardware.org/?probe=933e5a5b96) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | [7017fcf775](https://linux-hardware.org/?probe=7017fcf775) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | [9afa780018](https://linux-hardware.org/?probe=9afa780018) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 42915CG       | [d058eeaad5](https://linux-hardware.org/?probe=d058eeaad5) | Jan 29, 2023 |
| HP            | ZBook 17 G3                 | [a1b5cdf1db](https://linux-hardware.org/?probe=a1b5cdf1db) | Jan 28, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a88e343a83](https://linux-hardware.org/?probe=a88e343a83) | Jan 28, 2023 |
| ASUSTek       | UX410UAR                    | [e9ac16c8ef](https://linux-hardware.org/?probe=e9ac16c8ef) | Jan 28, 2023 |
| Dell          | Inspiron 3581               | [8c8db10ac2](https://linux-hardware.org/?probe=8c8db10ac2) | Jan 28, 2023 |
| HP            | ProBook 430 G6              | [24fd7df5b6](https://linux-hardware.org/?probe=24fd7df5b6) | Jan 28, 2023 |
| HP            | EliteBook 640 14 inch G9... | [bbdf827cef](https://linux-hardware.org/?probe=bbdf827cef) | Jan 27, 2023 |
| Acer          | Aspire 7750G                | [0b05244a15](https://linux-hardware.org/?probe=0b05244a15) | Jan 27, 2023 |
| Dell          | Latitude E7440              | [9ba078f6ab](https://linux-hardware.org/?probe=9ba078f6ab) | Jan 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | [c83903fdc8](https://linux-hardware.org/?probe=c83903fdc8) | Jan 27, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [376c580dcb](https://linux-hardware.org/?probe=376c580dcb) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [d3adeb692c](https://linux-hardware.org/?probe=d3adeb692c) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [46b1227255](https://linux-hardware.org/?probe=46b1227255) | Jan 27, 2023 |
| MSI           | Creator 17 B11UE            | [fcf56cfe4d](https://linux-hardware.org/?probe=fcf56cfe4d) | Jan 27, 2023 |
| Dell          | Latitude 5420               | [379a2dc9ab](https://linux-hardware.org/?probe=379a2dc9ab) | Jan 26, 2023 |
| Dell          | Latitude 5420               | [eec8ef8ddb](https://linux-hardware.org/?probe=eec8ef8ddb) | Jan 26, 2023 |
| Google        | Careena                     | [75ca1a25dd](https://linux-hardware.org/?probe=75ca1a25dd) | Jan 26, 2023 |
| Apple         | MacBookPro10,1              | [4643f751cf](https://linux-hardware.org/?probe=4643f751cf) | Jan 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [3b96eac8a9](https://linux-hardware.org/?probe=3b96eac8a9) | Jan 25, 2023 |
| Panasonic     | FZ55-2                      | [dd9ddb12b6](https://linux-hardware.org/?probe=dd9ddb12b6) | Jan 25, 2023 |
| Lenovo        | ThinkPad X220 4291IR6       | [cc41fa5174](https://linux-hardware.org/?probe=cc41fa5174) | Jan 25, 2023 |
| Samsung       | R710                        | [17a3e2ddd9](https://linux-hardware.org/?probe=17a3e2ddd9) | Jan 25, 2023 |
| HP            | ZBook 15 G3                 | [0bde1ca99a](https://linux-hardware.org/?probe=0bde1ca99a) | Jan 24, 2023 |
| Packard Be... | EasyNote MH36               | [07ba548a55](https://linux-hardware.org/?probe=07ba548a55) | Jan 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [fd6d2ec3c2](https://linux-hardware.org/?probe=fd6d2ec3c2) | Jan 23, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [c8ec385a88](https://linux-hardware.org/?probe=c8ec385a88) | Jan 23, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [5648fbf4a0](https://linux-hardware.org/?probe=5648fbf4a0) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [62ac206f7e](https://linux-hardware.org/?probe=62ac206f7e) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [5c7625e3f8](https://linux-hardware.org/?probe=5c7625e3f8) | Jan 23, 2023 |
| Fujitsu       | LIFEBOOK S751               | [ff727a3560](https://linux-hardware.org/?probe=ff727a3560) | Jan 22, 2023 |
| Fujitsu       | LIFEBOOK S751               | [df0676ac87](https://linux-hardware.org/?probe=df0676ac87) | Jan 22, 2023 |
| Dell          | G3 3579                     | [63298dcee9](https://linux-hardware.org/?probe=63298dcee9) | Jan 22, 2023 |
| Danew         | Dbook 131                   | [08911c133e](https://linux-hardware.org/?probe=08911c133e) | Jan 22, 2023 |
| Clevo         | W150ER                      | [ba5d06437c](https://linux-hardware.org/?probe=ba5d06437c) | Jan 21, 2023 |
| Google        | Phaser                      | [557e69c5f1](https://linux-hardware.org/?probe=557e69c5f1) | Jan 21, 2023 |
| HP            | EliteBook Folio 9480m       | [cf1b67c224](https://linux-hardware.org/?probe=cf1b67c224) | Jan 21, 2023 |
| HP            | EliteBook 840 G3            | [06f6499264](https://linux-hardware.org/?probe=06f6499264) | Jan 21, 2023 |
| Dell          | Latitude 5501               | [d31f972a20](https://linux-hardware.org/?probe=d31f972a20) | Jan 20, 2023 |
| Lenovo        | G505 20240                  | [c591d80181](https://linux-hardware.org/?probe=c591d80181) | Jan 20, 2023 |
| UMAX          | VisionBook 12Wr             | [0707d617f7](https://linux-hardware.org/?probe=0707d617f7) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490s 20NYS3SX0... | [3e08ab25c6](https://linux-hardware.org/?probe=3e08ab25c6) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [80cb1c8239](https://linux-hardware.org/?probe=80cb1c8239) | Jan 19, 2023 |
| Lenovo        | ThinkPad E470 20H1004SMX    | [0d8528f0d2](https://linux-hardware.org/?probe=0d8528f0d2) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0efa802a32](https://linux-hardware.org/?probe=0efa802a32) | Jan 19, 2023 |
| Dell          | XPS 15 9500                 | [606ba17221](https://linux-hardware.org/?probe=606ba17221) | Jan 19, 2023 |
| Insyde        | Braswell                    | [18526fdbe2](https://linux-hardware.org/?probe=18526fdbe2) | Jan 19, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [20749dc72f](https://linux-hardware.org/?probe=20749dc72f) | Jan 19, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [db998abdae](https://linux-hardware.org/?probe=db998abdae) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [368ed9c856](https://linux-hardware.org/?probe=368ed9c856) | Jan 18, 2023 |
| Novatech      | NL40_50CU                   | [395dab7c43](https://linux-hardware.org/?probe=395dab7c43) | Jan 18, 2023 |
| HP            | Compaq 6910p                | [61d820a040](https://linux-hardware.org/?probe=61d820a040) | Jan 18, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [7b62e27d7a](https://linux-hardware.org/?probe=7b62e27d7a) | Jan 18, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | [393e6cd6d2](https://linux-hardware.org/?probe=393e6cd6d2) | Jan 18, 2023 |
| HP            | EliteBook 820 G4            | [430b938694](https://linux-hardware.org/?probe=430b938694) | Jan 18, 2023 |
| HP            | EliteBook 2170p             | [46705d578e](https://linux-hardware.org/?probe=46705d578e) | Jan 18, 2023 |
| HP            | EliteBook 840 G4            | [952c81c314](https://linux-hardware.org/?probe=952c81c314) | Jan 18, 2023 |
| Dell          | Latitude 5500               | [e0ae9cb026](https://linux-hardware.org/?probe=e0ae9cb026) | Jan 17, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [99e10e5d0f](https://linux-hardware.org/?probe=99e10e5d0f) | Jan 17, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [624f47d1e3](https://linux-hardware.org/?probe=624f47d1e3) | Jan 17, 2023 |
| HP            | Compaq 6730b (GW687AV)      | [e967b291d5](https://linux-hardware.org/?probe=e967b291d5) | Jan 17, 2023 |
| Dell          | Inspiron 5502               | [43c4f532aa](https://linux-hardware.org/?probe=43c4f532aa) | Jan 17, 2023 |
| Positivo      | CHT14B                      | [ab4518f121](https://linux-hardware.org/?probe=ab4518f121) | Jan 16, 2023 |
| Dell          | Inspiron 15-3567            | [020e19b05d](https://linux-hardware.org/?probe=020e19b05d) | Jan 16, 2023 |
| Lenovo        | ThinkPad T490s 20NX0076M... | [4c896e2c0e](https://linux-hardware.org/?probe=4c896e2c0e) | Jan 16, 2023 |
| Dell          | Inspiron 5502               | [9403074843](https://linux-hardware.org/?probe=9403074843) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [47d090108d](https://linux-hardware.org/?probe=47d090108d) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [219091b4e0](https://linux-hardware.org/?probe=219091b4e0) | Jan 15, 2023 |
| Apple         | MacBookAir5,1               | [f316bddcf2](https://linux-hardware.org/?probe=f316bddcf2) | Jan 15, 2023 |
| Acer          | Swift SF314-510G            | [b929f53536](https://linux-hardware.org/?probe=b929f53536) | Jan 15, 2023 |
| Dell          | Inspiron 15-3567            | [5426686264](https://linux-hardware.org/?probe=5426686264) | Jan 15, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [0ec206a07d](https://linux-hardware.org/?probe=0ec206a07d) | Jan 15, 2023 |
| HP            | EliteBook 8570w             | [53eb92efda](https://linux-hardware.org/?probe=53eb92efda) | Jan 15, 2023 |
| Lenovo        | ThinkPad T470 20HES0MV00    | [7e3b019181](https://linux-hardware.org/?probe=7e3b019181) | Jan 14, 2023 |
| HP            | Pavilion g6                 | [7d44980bca](https://linux-hardware.org/?probe=7d44980bca) | Jan 14, 2023 |
| Lenovo        | ThinkPad W520 4284W2U       | [576a509224](https://linux-hardware.org/?probe=576a509224) | Jan 14, 2023 |
| HP            | Laptop 14s-dk0xxx           | [6efb68b8da](https://linux-hardware.org/?probe=6efb68b8da) | Jan 14, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [0899d995dd](https://linux-hardware.org/?probe=0899d995dd) | Jan 14, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [f862a7e702](https://linux-hardware.org/?probe=f862a7e702) | Jan 14, 2023 |
| HP            | Pavilion g6                 | [7672e1178a](https://linux-hardware.org/?probe=7672e1178a) | Jan 14, 2023 |
| Unknown       | Unknown                     | [ce69bfd81b](https://linux-hardware.org/?probe=ce69bfd81b) | Jan 13, 2023 |
| HP            | ProBook 445 G7              | [baf20b6914](https://linux-hardware.org/?probe=baf20b6914) | Jan 13, 2023 |
| ASUSTek       | X450LD                      | [859eb05149](https://linux-hardware.org/?probe=859eb05149) | Jan 13, 2023 |
| HP            | Compaq 6735b                | [01878ee027](https://linux-hardware.org/?probe=01878ee027) | Jan 12, 2023 |
| Dell          | Inspiron 3521               | [694d5be301](https://linux-hardware.org/?probe=694d5be301) | Jan 12, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [d4691b9969](https://linux-hardware.org/?probe=d4691b9969) | Jan 12, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [2316d5dc8b](https://linux-hardware.org/?probe=2316d5dc8b) | Jan 12, 2023 |
| Lenovo        | ThinkPad T470p 20J7S1JT0... | [856d91c1ca](https://linux-hardware.org/?probe=856d91c1ca) | Jan 12, 2023 |
| Dell          | Precision M4400             | [27da7825fb](https://linux-hardware.org/?probe=27da7825fb) | Jan 12, 2023 |
| Dell          | Inspiron 3421               | [055d61383e](https://linux-hardware.org/?probe=055d61383e) | Jan 12, 2023 |
| Acer          | Swift SF314-56              | [46aebbe972](https://linux-hardware.org/?probe=46aebbe972) | Jan 11, 2023 |
| SLIMBOOK      | PRO                         | [551a4bd378](https://linux-hardware.org/?probe=551a4bd378) | Jan 11, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [6c67fc3995](https://linux-hardware.org/?probe=6c67fc3995) | Jan 11, 2023 |
| Aquarius      | NS585                       | [6fbcdf4d2f](https://linux-hardware.org/?probe=6fbcdf4d2f) | Jan 10, 2023 |
| HP            | Mini 110-1000               | [05c4656700](https://linux-hardware.org/?probe=05c4656700) | Jan 10, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [8367c27d81](https://linux-hardware.org/?probe=8367c27d81) | Jan 10, 2023 |
| HP            | 15                          | [f6b287dae1](https://linux-hardware.org/?probe=f6b287dae1) | Jan 10, 2023 |
| Acer          | Nitro AN517-54              | [8ea20821c8](https://linux-hardware.org/?probe=8ea20821c8) | Jan 10, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | [8d0b4a504d](https://linux-hardware.org/?probe=8d0b4a504d) | Jan 09, 2023 |
| Acer          | Aspire A515-54G             | [dea6736468](https://linux-hardware.org/?probe=dea6736468) | Jan 09, 2023 |
| Acer          | Aspire one 1-131            | [06c3411258](https://linux-hardware.org/?probe=06c3411258) | Jan 08, 2023 |
| HP            | ZBook 15 G3                 | [648dcae4c6](https://linux-hardware.org/?probe=648dcae4c6) | Jan 08, 2023 |
| ASUSTek       | K53U                        | [63849b1b5a](https://linux-hardware.org/?probe=63849b1b5a) | Jan 08, 2023 |
| Apple         | MacBookAir7,2               | [a4e777ea7d](https://linux-hardware.org/?probe=a4e777ea7d) | Jan 08, 2023 |
| Acer          | Aspire 7745G                | [9119962d1f](https://linux-hardware.org/?probe=9119962d1f) | Jan 07, 2023 |
| Gigabyte      | G5 GE                       | [d6a4584809](https://linux-hardware.org/?probe=d6a4584809) | Jan 07, 2023 |
| Dell          | Latitude 2110               | [9910f8985b](https://linux-hardware.org/?probe=9910f8985b) | Jan 07, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [9776545fc4](https://linux-hardware.org/?probe=9776545fc4) | Jan 06, 2023 |
| Toshiba       | Satellite C55Dt-A           | [f3cfb5dbb5](https://linux-hardware.org/?probe=f3cfb5dbb5) | Jan 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [9b0a8d487e](https://linux-hardware.org/?probe=9b0a8d487e) | Jan 06, 2023 |
| &#er &&       | Aspire 5100                 | [26da9e8ee1](https://linux-hardware.org/?probe=26da9e8ee1) | Jan 06, 2023 |
| Google        | Stout                       | [5ef816b9a6](https://linux-hardware.org/?probe=5ef816b9a6) | Jan 05, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [3245d27cb7](https://linux-hardware.org/?probe=3245d27cb7) | Jan 05, 2023 |
| HP            | EliteBook 840 Aero G8 No... | [b9f4ca82d2](https://linux-hardware.org/?probe=b9f4ca82d2) | Jan 05, 2023 |
| Acer          | Extensa 2540                | [4442f2c14a](https://linux-hardware.org/?probe=4442f2c14a) | Jan 05, 2023 |
| Acer          | Extensa 2540                | [ec8b49d7b0](https://linux-hardware.org/?probe=ec8b49d7b0) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | [0042419ccb](https://linux-hardware.org/?probe=0042419ccb) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | [82e42c0d42](https://linux-hardware.org/?probe=82e42c0d42) | Jan 04, 2023 |
| Lenovo        | ThinkPad T430s 2356BQ5      | [fdf6545b20](https://linux-hardware.org/?probe=fdf6545b20) | Jan 04, 2023 |
| HP            | 255 G8 Notebook PC          | [b876c5797a](https://linux-hardware.org/?probe=b876c5797a) | Jan 03, 2023 |
| Dell          | Inspiron 5566               | [258412ac0a](https://linux-hardware.org/?probe=258412ac0a) | Jan 03, 2023 |
| ASUSTek       | F5SL                        | [67882c0f69](https://linux-hardware.org/?probe=67882c0f69) | Jan 02, 2023 |
| ASUSTek       | F5SL                        | [42ef1fbf40](https://linux-hardware.org/?probe=42ef1fbf40) | Jan 02, 2023 |
| Acer          | Aspire ES1-711              | [735e062168](https://linux-hardware.org/?probe=735e062168) | Jan 02, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [90603e4ab3](https://linux-hardware.org/?probe=90603e4ab3) | Jan 02, 2023 |
| MSI           | GE75 Raider 8SG             | [b6fa9be350](https://linux-hardware.org/?probe=b6fa9be350) | Jan 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [b54f3aab7b](https://linux-hardware.org/?probe=b54f3aab7b) | Jan 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0D    | [a1f966e5e8](https://linux-hardware.org/?probe=a1f966e5e8) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [08fb8de608](https://linux-hardware.org/?probe=08fb8de608) | Jan 02, 2023 |
| Lenovo        | ThinkPad T430u 33519LC      | [87af3fa7f0](https://linux-hardware.org/?probe=87af3fa7f0) | Jan 02, 2023 |
| ASUSTek       | T100TA                      | [2c33e446d4](https://linux-hardware.org/?probe=2c33e446d4) | Jan 02, 2023 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [3f68b8438c](https://linux-hardware.org/?probe=3f68b8438c) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [bca75efbe5](https://linux-hardware.org/?probe=bca75efbe5) | Jan 02, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [2396307897](https://linux-hardware.org/?probe=2396307897) | Jan 02, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [13df46e700](https://linux-hardware.org/?probe=13df46e700) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [f9db70d551](https://linux-hardware.org/?probe=f9db70d551) | Jan 01, 2023 |
| Lenovo        | G565 20071                  | [e974b446ae](https://linux-hardware.org/?probe=e974b446ae) | Jan 01, 2023 |
| Panasonic     | CF-54-2                     | [dfe3d2e06b](https://linux-hardware.org/?probe=dfe3d2e06b) | Jan 01, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7474151c7e](https://linux-hardware.org/?probe=7474151c7e) | Jan 01, 2023 |
| Dell          | Inspiron 5566               | [9eadf42d31](https://linux-hardware.org/?probe=9eadf42d31) | Jan 01, 2023 |
| Samsung       | 940XFG                      | [8d33275e7b](https://linux-hardware.org/?probe=8d33275e7b) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fb22f9430c](https://linux-hardware.org/?probe=fb22f9430c) | Dec 31, 2022 |
| Lenovo        | IdeaPad Y560                | [c9d3a1d0a3](https://linux-hardware.org/?probe=c9d3a1d0a3) | Dec 31, 2022 |
| Acer          | Aspire A514-54              | [5775c77a91](https://linux-hardware.org/?probe=5775c77a91) | Dec 31, 2022 |
| HP            | Compaq 6710b (KE207ES#AB... | [d7d0be3872](https://linux-hardware.org/?probe=d7d0be3872) | Dec 30, 2022 |
| Dell          | Inspiron 5490               | [c8a80649d2](https://linux-hardware.org/?probe=c8a80649d2) | Dec 30, 2022 |
| HP            | 255 G3                      | [89d6bd459c](https://linux-hardware.org/?probe=89d6bd459c) | Dec 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S1JT0... | [4b7bbb186f](https://linux-hardware.org/?probe=4b7bbb186f) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | [5bf3ff5c0e](https://linux-hardware.org/?probe=5bf3ff5c0e) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | [4f63c4474c](https://linux-hardware.org/?probe=4f63c4474c) | Dec 29, 2022 |
| HP            | EliteBook Folio 1040 G3     | [6aad572cd5](https://linux-hardware.org/?probe=6aad572cd5) | Dec 29, 2022 |
| HP            | ZBook 15 G6                 | [af1655497e](https://linux-hardware.org/?probe=af1655497e) | Dec 29, 2022 |
| HP            | ProBook 6570b               | [46fd918b7c](https://linux-hardware.org/?probe=46fd918b7c) | Dec 29, 2022 |
| Dell          | Inspiron 5490               | [457c2ae4ae](https://linux-hardware.org/?probe=457c2ae4ae) | Dec 28, 2022 |
| Dell          | Inspiron 5490               | [fdfd0f21c7](https://linux-hardware.org/?probe=fdfd0f21c7) | Dec 28, 2022 |
| Toshiba       | Satellite L455D             | [35c085aa82](https://linux-hardware.org/?probe=35c085aa82) | Dec 28, 2022 |
| Dell          | Vostro 3400                 | [27f58a8ad1](https://linux-hardware.org/?probe=27f58a8ad1) | Dec 28, 2022 |
| Acer          | Aspire ES1-531              | [c29088a63f](https://linux-hardware.org/?probe=c29088a63f) | Dec 28, 2022 |
| HP            | ProBook 6470b               | [055705b3f2](https://linux-hardware.org/?probe=055705b3f2) | Dec 28, 2022 |
| Apple         | MacBookAir7,2               | [10dce91da1](https://linux-hardware.org/?probe=10dce91da1) | Dec 27, 2022 |
| Apple         | MacBookAir7,1               | [d174ffb318](https://linux-hardware.org/?probe=d174ffb318) | Dec 27, 2022 |
| MSI           | GE62 2QC                    | [dbd69d70ac](https://linux-hardware.org/?probe=dbd69d70ac) | Dec 27, 2022 |
| Panasonic     | FZ55-2                      | [1699b7c3b2](https://linux-hardware.org/?probe=1699b7c3b2) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [78c6c15502](https://linux-hardware.org/?probe=78c6c15502) | Dec 27, 2022 |
| Notebook      | L14xMU                      | [7644bc65e2](https://linux-hardware.org/?probe=7644bc65e2) | Dec 27, 2022 |
| Dell          | Inspiron 1012               | [3dd6b8a416](https://linux-hardware.org/?probe=3dd6b8a416) | Dec 26, 2022 |
| Exo           | Smart Serie M               | [942ee3b035](https://linux-hardware.org/?probe=942ee3b035) | Dec 26, 2022 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [3bb1c5cc47](https://linux-hardware.org/?probe=3bb1c5cc47) | Dec 26, 2022 |
| Acer          | Aspire ES1-533              | [3b5fa6d85a](https://linux-hardware.org/?probe=3b5fa6d85a) | Dec 26, 2022 |
| Lenovo        | ThinkPad X250 20CLS1UB00    | [fc8b2899fa](https://linux-hardware.org/?probe=fc8b2899fa) | Dec 25, 2022 |
| SANTECH       | NHx0DB,DE                   | [a0996d42bd](https://linux-hardware.org/?probe=a0996d42bd) | Dec 25, 2022 |
| HP            | 470 G8 Notebook PC          | [6d77c48324](https://linux-hardware.org/?probe=6d77c48324) | Dec 25, 2022 |
| ASUSTek       | G751JT                      | [16e989ff99](https://linux-hardware.org/?probe=16e989ff99) | Dec 25, 2022 |
| Dell          | Latitude E6520              | [33a51c934d](https://linux-hardware.org/?probe=33a51c934d) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | [ea09a6daa8](https://linux-hardware.org/?probe=ea09a6daa8) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | [45737153e4](https://linux-hardware.org/?probe=45737153e4) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | [42221f61fb](https://linux-hardware.org/?probe=42221f61fb) | Dec 25, 2022 |
| Medion        | E122X                       | [6e4e34bcc3](https://linux-hardware.org/?probe=6e4e34bcc3) | Dec 24, 2022 |
| Medion        | E122X                       | [bf41c45a7d](https://linux-hardware.org/?probe=bf41c45a7d) | Dec 24, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [096d4fc8c2](https://linux-hardware.org/?probe=096d4fc8c2) | Dec 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c5f2f2db53](https://linux-hardware.org/?probe=c5f2f2db53) | Dec 24, 2022 |
| Lenovo        | ThinkPad X270 20HMS16200    | [6ac6e552a8](https://linux-hardware.org/?probe=6ac6e552a8) | Dec 24, 2022 |
| Dell          | Inspiron 5570               | [1c7e7f8dd2](https://linux-hardware.org/?probe=1c7e7f8dd2) | Dec 24, 2022 |
| Dell          | Latitude E7440              | [baae52327d](https://linux-hardware.org/?probe=baae52327d) | Dec 23, 2022 |
| Dell          | Latitude E7440              | [bc5d48b831](https://linux-hardware.org/?probe=bc5d48b831) | Dec 23, 2022 |
| Dell          | Latitude E7440              | [fde483d476](https://linux-hardware.org/?probe=fde483d476) | Dec 23, 2022 |
| Dell          | Latitude E7440              | [a746012ffd](https://linux-hardware.org/?probe=a746012ffd) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [9e5c4705fa](https://linux-hardware.org/?probe=9e5c4705fa) | Dec 23, 2022 |
| Dell          | Latitude D630               | [8175d003ce](https://linux-hardware.org/?probe=8175d003ce) | Dec 23, 2022 |
| Google        | Reks                        | [ecee690e6e](https://linux-hardware.org/?probe=ecee690e6e) | Dec 23, 2022 |
| Toshiba       | Satellite L10W-B-101        | [54d5cca493](https://linux-hardware.org/?probe=54d5cca493) | Dec 23, 2022 |
| Google        | Reks                        | [58b1b4cac1](https://linux-hardware.org/?probe=58b1b4cac1) | Dec 23, 2022 |
| Dell          | Inspiron 3501               | [297651d437](https://linux-hardware.org/?probe=297651d437) | Dec 23, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [79b015dcea](https://linux-hardware.org/?probe=79b015dcea) | Dec 23, 2022 |
| Dell          | Inspiron 3501               | [958ee9d145](https://linux-hardware.org/?probe=958ee9d145) | Dec 23, 2022 |
| Dell          | G3 3590                     | [d75d9e6663](https://linux-hardware.org/?probe=d75d9e6663) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [5f75bb423d](https://linux-hardware.org/?probe=5f75bb423d) | Dec 23, 2022 |
| Acer          | Aspire 4750                 | [3256c282db](https://linux-hardware.org/?probe=3256c282db) | Dec 23, 2022 |
| HP            | 255 G7 Notebook PC          | [5bedf1557b](https://linux-hardware.org/?probe=5bedf1557b) | Dec 23, 2022 |
| Dell          | Inspiron 5490               | [1c424b5f55](https://linux-hardware.org/?probe=1c424b5f55) | Dec 23, 2022 |
| Unknown       | Unknown                     | [f9c4fecaf4](https://linux-hardware.org/?probe=f9c4fecaf4) | Dec 23, 2022 |
| Unknown       | Unknown                     | [3832db2827](https://linux-hardware.org/?probe=3832db2827) | Dec 23, 2022 |
| Toshiba       | Satellite C55Dt-A           | [67294324c5](https://linux-hardware.org/?probe=67294324c5) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [c6d28912f0](https://linux-hardware.org/?probe=c6d28912f0) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [1a14f26bd3](https://linux-hardware.org/?probe=1a14f26bd3) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [db77bb7a3f](https://linux-hardware.org/?probe=db77bb7a3f) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [d2278ed94d](https://linux-hardware.org/?probe=d2278ed94d) | Dec 22, 2022 |
| Apple         | MacBookAir7,1               | [09ba8ccf48](https://linux-hardware.org/?probe=09ba8ccf48) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [f4e79df709](https://linux-hardware.org/?probe=f4e79df709) | Dec 22, 2022 |
| Apple         | MacBookAir7,1               | [2c3febf6fa](https://linux-hardware.org/?probe=2c3febf6fa) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [cddffa9123](https://linux-hardware.org/?probe=cddffa9123) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [5f911806c8](https://linux-hardware.org/?probe=5f911806c8) | Dec 22, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [844f589d20](https://linux-hardware.org/?probe=844f589d20) | Dec 22, 2022 |
| Dell          | Latitude D630               | [e1106d8868](https://linux-hardware.org/?probe=e1106d8868) | Dec 22, 2022 |
| HP            | Stream Notebook PC 13       | [b049c64ff7](https://linux-hardware.org/?probe=b049c64ff7) | Dec 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [5f132c928b](https://linux-hardware.org/?probe=5f132c928b) | Dec 22, 2022 |
| Dell          | G3 3590                     | [8038491eb0](https://linux-hardware.org/?probe=8038491eb0) | Dec 22, 2022 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [16cae3015a](https://linux-hardware.org/?probe=16cae3015a) | Dec 21, 2022 |
| Apple         | MacBookAir7,2               | [b4e828bef3](https://linux-hardware.org/?probe=b4e828bef3) | Dec 21, 2022 |
| Dell          | Vostro 3583                 | [cf3c6eb18b](https://linux-hardware.org/?probe=cf3c6eb18b) | Dec 21, 2022 |
| Apple         | MacBookAir7,2               | [056d76bae8](https://linux-hardware.org/?probe=056d76bae8) | Dec 21, 2022 |
| Sony          | SVE1112M1EB                 | [74e100e63b](https://linux-hardware.org/?probe=74e100e63b) | Dec 21, 2022 |
| HP            | ZBook Power 15.6 inch G8... | [6b202d6cc2](https://linux-hardware.org/?probe=6b202d6cc2) | Dec 21, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [9438c80c85](https://linux-hardware.org/?probe=9438c80c85) | Dec 21, 2022 |
| Dell          | Inspiron 3501               | [449e38a14d](https://linux-hardware.org/?probe=449e38a14d) | Dec 21, 2022 |
| Dell          | G3 3590                     | [8272655600](https://linux-hardware.org/?probe=8272655600) | Dec 21, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [cd4fa20e66](https://linux-hardware.org/?probe=cd4fa20e66) | Dec 20, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e676fe186f](https://linux-hardware.org/?probe=e676fe186f) | Dec 20, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [1e53c20bdd](https://linux-hardware.org/?probe=1e53c20bdd) | Dec 20, 2022 |
| ASUSTek       | T100TA                      | [1dc546e14a](https://linux-hardware.org/?probe=1dc546e14a) | Dec 20, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [2aeb8fd0cd](https://linux-hardware.org/?probe=2aeb8fd0cd) | Dec 19, 2022 |
| ASUSTek       | 900SD                       | [43d2c88062](https://linux-hardware.org/?probe=43d2c88062) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | [956aaecbb9](https://linux-hardware.org/?probe=956aaecbb9) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | [d5ceb48450](https://linux-hardware.org/?probe=d5ceb48450) | Dec 18, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [756263bf48](https://linux-hardware.org/?probe=756263bf48) | Dec 18, 2022 |
| EUROCOM       | SCORPIUS 3D                 | [4fdf299276](https://linux-hardware.org/?probe=4fdf299276) | Dec 18, 2022 |
| Dell          | Latitude E6530              | [198a9bc936](https://linux-hardware.org/?probe=198a9bc936) | Dec 18, 2022 |
| Lenovo        | ThinkPad T470 20HES3JR02    | [f9e4638f19](https://linux-hardware.org/?probe=f9e4638f19) | Dec 18, 2022 |
| Dell          | Inspiron N5110              | [9e4f7a69c9](https://linux-hardware.org/?probe=9e4f7a69c9) | Dec 18, 2022 |
| Dell          | Latitude E4310              | [ace267f47c](https://linux-hardware.org/?probe=ace267f47c) | Dec 18, 2022 |
| Acer          | Aspire E5-573G              | [937a672cb0](https://linux-hardware.org/?probe=937a672cb0) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1e2531fdf1](https://linux-hardware.org/?probe=1e2531fdf1) | Dec 17, 2022 |
| Lenovo        | K14 Gen 1 21CUS02600        | [218654b079](https://linux-hardware.org/?probe=218654b079) | Dec 17, 2022 |
| HP            | Notebook                    | [844d855f78](https://linux-hardware.org/?probe=844d855f78) | Dec 17, 2022 |
| Unknown       | Unknown                     | [208016df07](https://linux-hardware.org/?probe=208016df07) | Dec 17, 2022 |
| Dell          | Inspiron 7590               | [e8fb837cf5](https://linux-hardware.org/?probe=e8fb837cf5) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | [5cc0ff812b](https://linux-hardware.org/?probe=5cc0ff812b) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | [062a6ed428](https://linux-hardware.org/?probe=062a6ed428) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [db670caadd](https://linux-hardware.org/?probe=db670caadd) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d5cf351351](https://linux-hardware.org/?probe=d5cf351351) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e2056deb8a](https://linux-hardware.org/?probe=e2056deb8a) | Dec 16, 2022 |
| Intel         | powered classmate PC        | [e0401225a2](https://linux-hardware.org/?probe=e0401225a2) | Dec 15, 2022 |
| Unknown       | T3 MRD                      | [909e1a1604](https://linux-hardware.org/?probe=909e1a1604) | Dec 15, 2022 |
| Google        | Cyan                        | [2b9f20b7da](https://linux-hardware.org/?probe=2b9f20b7da) | Dec 15, 2022 |
| Lenovo        | ThinkPad T430 2349I62       | [f7590c1a07](https://linux-hardware.org/?probe=f7590c1a07) | Dec 15, 2022 |
| Dell          | Latitude 3490               | [af008f69f1](https://linux-hardware.org/?probe=af008f69f1) | Dec 14, 2022 |
| Acer          | Aspire 5738                 | [c0c4581310](https://linux-hardware.org/?probe=c0c4581310) | Dec 14, 2022 |
| Apple         | MacBook6,1                  | [f19d464a26](https://linux-hardware.org/?probe=f19d464a26) | Dec 14, 2022 |
| ASUSTek       | X302LA                      | [8404a0b0c6](https://linux-hardware.org/?probe=8404a0b0c6) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [14f87b8695](https://linux-hardware.org/?probe=14f87b8695) | Dec 13, 2022 |
| Dell          | Latitude 5520               | [7e5d86eaaf](https://linux-hardware.org/?probe=7e5d86eaaf) | Dec 13, 2022 |
| ASUSTek       | G75VW                       | [8d2a0ec4e4](https://linux-hardware.org/?probe=8d2a0ec4e4) | Dec 13, 2022 |
| Exo           | Smart Serie M               | [7fcf3d09bb](https://linux-hardware.org/?probe=7fcf3d09bb) | Dec 13, 2022 |
| Google        | Terra                       | [765deab389](https://linux-hardware.org/?probe=765deab389) | Dec 12, 2022 |
| HP            | EliteBook 8460p             | [95dc27194a](https://linux-hardware.org/?probe=95dc27194a) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [dc916ac78c](https://linux-hardware.org/?probe=dc916ac78c) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [2bfcc16f6b](https://linux-hardware.org/?probe=2bfcc16f6b) | Dec 12, 2022 |
| Google        | Enguarde                    | [60cce42479](https://linux-hardware.org/?probe=60cce42479) | Dec 12, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_11/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.10.0-8-amd64         | 578       | 16.04%  |
| 5.10.0-10-amd64        | 490       | 13.6%   |
| 5.10.0-20-amd64        | 237       | 6.58%   |
| 5.10.0-21-amd64        | 234       | 6.49%   |
| 5.10.0-18-amd64        | 176       | 4.88%   |
| 5.10.0-9-amd64         | 172       | 4.77%   |
| 5.10.0-7-amd64         | 171       | 4.75%   |
| 5.10.0-16-amd64        | 166       | 4.61%   |
| 5.10.0-19-amd64        | 161       | 4.47%   |
| 5.10.0-13-amd64        | 150       | 4.16%   |
| 5.10.0-11-amd64        | 103       | 2.86%   |
| 5.10.0-14-amd64        | 79        | 2.19%   |
| 5.10.0-17-amd64        | 73        | 2.03%   |
| 5.10.0-23-amd64        | 60        | 1.67%   |
| 5.10.0-15-amd64        | 49        | 1.36%   |
| 5.10.0-2-amd64         | 42        | 1.17%   |
| 5.10.0-12-amd64        | 41        | 1.14%   |
| 5.10.0-22-amd64        | 36        | 1%      |
| 5.10.0-6-amd64         | 28        | 0.78%   |
| 5.10.0-13-686-pae      | 26        | 0.72%   |
| 5.18.0-0.deb11.4-amd64 | 22        | 0.61%   |
| 6.0.0-0.deb11.6-amd64  | 21        | 0.58%   |
| 6.0.0-0.deb11.2-amd64  | 19        | 0.53%   |
| 5.14.0-0.bpo.2-amd64   | 17        | 0.47%   |
| 6.1.0-0.deb11.5-amd64  | 15        | 0.42%   |
| 5.16.0-0.bpo.4-amd64   | 15        | 0.42%   |
| 5.15.0-2-amd64         | 14        | 0.39%   |
| 5.19.0-0.deb11.2-amd64 | 13        | 0.36%   |
| 5.10.0-3-amd64         | 13        | 0.36%   |
| 5.10.0-9-686-pae       | 9         | 0.25%   |
| 5.10.0-8-686-pae       | 9         | 0.25%   |
| 5.10.0-21-686-pae      | 9         | 0.25%   |
| 5.10.0-13-686          | 9         | 0.25%   |
| 5.18.0-0.bpo.1-amd64   | 8         | 0.22%   |
| 5.15.0-0.bpo.2-amd64   | 8         | 0.22%   |
| 5.19.0-2-amd64         | 7         | 0.19%   |
| 5.10.0-9-686           | 7         | 0.19%   |
| 6.0.0-6mx-amd64        | 6         | 0.17%   |
| 5.19.0-1-amd64         | 6         | 0.17%   |
| 5.18.0-2-amd64         | 6         | 0.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 2963      | 88.77%  |
| 6.0.0    | 49        | 1.47%   |
| 5.18.0   | 41        | 1.23%   |
| 5.15.0   | 37        | 1.11%   |
| 5.16.0   | 35        | 1.05%   |
| 5.19.0   | 31        | 0.93%   |
| 6.1.0    | 27        | 0.81%   |
| 5.14.0   | 24        | 0.72%   |
| 5.17.0   | 13        | 0.39%   |
| 4.19.0   | 8         | 0.24%   |
| 6.3.4    | 3         | 0.09%   |
| 5.13.19  | 3         | 0.09%   |
| 5.12.0   | 3         | 0.09%   |
| 5.10.60  | 3         | 0.09%   |
| 6.2.8    | 2         | 0.06%   |
| 6.1.15   | 2         | 0.06%   |
| 6.0.2    | 2         | 0.06%   |
| 5.17.5   | 2         | 0.06%   |
| 5.17.11  | 2         | 0.06%   |
| 5.15.35  | 2         | 0.06%   |
| 5.15.107 | 2         | 0.06%   |
| 5.13.8   | 2         | 0.06%   |
| 5.11.0   | 2         | 0.06%   |
| 5.10.92  | 2         | 0.06%   |
| 5.10.109 | 2         | 0.06%   |
| 4.9.0    | 2         | 0.06%   |
| 6.3.5    | 1         | 0.03%   |
| 6.3.0    | 1         | 0.03%   |
| 6.2.6    | 1         | 0.03%   |
| 6.2.16   | 1         | 0.03%   |
| 6.2.14   | 1         | 0.03%   |
| 6.2.11   | 1         | 0.03%   |
| 6.1.9    | 1         | 0.03%   |
| 6.1.5    | 1         | 0.03%   |
| 6.1.31   | 1         | 0.03%   |
| 6.1.12   | 1         | 0.03%   |
| 6.0.9    | 1         | 0.03%   |
| 6.0.12   | 1         | 0.03%   |
| 6.0.11   | 1         | 0.03%   |
| 5.4.157  | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 2979      | 89.38%  |
| 5.15    | 56        | 1.68%   |
| 6.0     | 54        | 1.62%   |
| 5.18    | 43        | 1.29%   |
| 5.16    | 37        | 1.11%   |
| 5.19    | 35        | 1.05%   |
| 6.1     | 31        | 0.93%   |
| 5.14    | 29        | 0.87%   |
| 5.17    | 19        | 0.57%   |
| 4.19    | 10        | 0.3%    |
| 5.13    | 9         | 0.27%   |
| 6.2     | 6         | 0.18%   |
| 5.12    | 6         | 0.18%   |
| 5.11    | 6         | 0.18%   |
| 6.3     | 4         | 0.12%   |
| 5.1     | 2         | 0.06%   |
| 4.9     | 2         | 0.06%   |
| 5.4     | 1         | 0.03%   |
| 5.15.6  | 1         | 0.03%   |
| 4.14    | 1         | 0.03%   |
| 3.8     | 1         | 0.03%   |
| 3.10    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 3133      | 95.84%  |
| i686    | 132       | 4.04%   |
| armv7l  | 3         | 0.09%   |
| aarch64 | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Unknown           | 1031      | 30.98%  |
| GNOME             | 853       | 25.63%  |
| KDE5              | 418       | 12.56%  |
| XFCE              | 399       | 11.99%  |
| MATE              | 120       | 3.61%   |
| X-Cinnamon        | 103       | 3.09%   |
| LXDE              | 101       | 3.03%   |
| Cinnamon          | 84        | 2.52%   |
| LXQt              | 43        | 1.29%   |
| i3                | 41        | 1.23%   |
| KDE               | 35        | 1.05%   |
| GNOME Flashback   | 27        | 0.81%   |
| lightdm-xsession  | 14        | 0.42%   |
| openbox           | 13        | 0.39%   |
| Trinity           | 8         | 0.24%   |
| GNOME Classic     | 7         | 0.21%   |
| Budgie            | 4         | 0.12%   |
| Cutefish          | 3         | 0.09%   |
| BunsenLabs        | 3         | 0.09%   |
| x-session-manager | 2         | 0.06%   |
| sway              | 2         | 0.06%   |
| ICEWM             | 2         | 0.06%   |
| Enlightenment     | 2         | 0.06%   |
| DWM               | 2         | 0.06%   |
| awesome           | 2         | 0.06%   |
| xmonad            | 1         | 0.03%   |
| wmaker-common     | 1         | 0.03%   |
| mwm               | 1         | 0.03%   |
| matchbox          | 1         | 0.03%   |
| jwm               | 1         | 0.03%   |
| GNUstep           | 1         | 0.03%   |
| fluxbox           | 1         | 0.03%   |
| default           | 1         | 0.03%   |
| Deepin            | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 1612      | 48.66%  |
| Unknown     | 947       | 28.58%  |
| Wayland     | 632       | 19.08%  |
| Tty         | 117       | 3.53%   |
| Unspecified | 4         | 0.12%   |
| Web         | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1404      | 42.37%  |
| GDM     | 728       | 21.97%  |
| LightDM | 653       | 19.7%   |
| SDDM    | 372       | 11.23%  |
| TDM     | 70        | 2.11%   |
| GDM3    | 68        | 2.05%   |
| XDM     | 7         | 0.21%   |
| LXDM    | 4         | 0.12%   |
| SLiM    | 3         | 0.09%   |
| Ly      | 2         | 0.06%   |
| SU      | 1         | 0.03%   |
| NODM    | 1         | 0.03%   |
| KDM     | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 971       | 29.42%  |
| Unknown | 755       | 22.87%  |
| ru_RU   | 257       | 7.79%   |
| de_DE   | 200       | 6.06%   |
| fr_FR   | 175       | 5.3%    |
| en_GB   | 140       | 4.24%   |
| es_ES   | 106       | 3.21%   |
| it_IT   | 88        | 2.67%   |
| pt_BR   | 79        | 2.39%   |
| pl_PL   | 73        | 2.21%   |
| en_CA   | 34        | 1.03%   |
| es_MX   | 32        | 0.97%   |
| en_AU   | 29        | 0.88%   |
| es_AR   | 24        | 0.73%   |
| zh_CN   | 20        | 0.61%   |
| en_IN   | 20        | 0.61%   |
| C       | 20        | 0.61%   |
| hu_HU   | 15        | 0.45%   |
| en_IE   | 13        | 0.39%   |
| fi_FI   | 12        | 0.36%   |
| es_CL   | 12        | 0.36%   |
| sv_SE   | 11        | 0.33%   |
| es_VE   | 11        | 0.33%   |
| de_CH   | 11        | 0.33%   |
| de_AT   | 11        | 0.33%   |
| nl_NL   | 10        | 0.3%    |
| pt_PT   | 9         | 0.27%   |
| ja_JP   | 9         | 0.27%   |
| tr_TR   | 8         | 0.24%   |
| fr_BE   | 8         | 0.24%   |
| es_CO   | 8         | 0.24%   |
| cs_CZ   | 8         | 0.24%   |
| nb_NO   | 7         | 0.21%   |
| ko_KR   | 7         | 0.21%   |
| en_SG   | 7         | 0.21%   |
| zh_TW   | 6         | 0.18%   |
| sk_SK   | 5         | 0.15%   |
| en_ZA   | 5         | 0.15%   |
| en_NZ   | 5         | 0.15%   |
| uk_UA   | 4         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2230      | 67.72%  |
| BIOS | 1063      | 32.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2085      | 63.59%  |
| Overlay | 1048      | 31.96%  |
| Btrfs   | 87        | 2.65%   |
| Xfs     | 27        | 0.82%   |
| Zfs     | 12        | 0.37%   |
| Tmpfs   | 10        | 0.3%    |
| Ext2    | 3         | 0.09%   |
| Unknown | 3         | 0.09%   |
| Ext3    | 2         | 0.06%   |
| Rootfs  | 1         | 0.03%   |
| Aufs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2247      | 68.09%  |
| MBR     | 610       | 18.48%  |
| Unknown | 443       | 13.42%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2628      | 79.68%  |
| Yes       | 670       | 20.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2466      | 74.8%   |
| Yes       | 831       | 25.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 657       | 20.1%   |
| Apple                          | 626       | 19.16%  |
| Hewlett-Packard                | 470       | 14.38%  |
| Dell                           | 407       | 12.45%  |
| ASUSTek Computer               | 276       | 8.45%   |
| Acer                           | 203       | 6.21%   |
| Google                         | 134       | 4.1%    |
| MSI                            | 50        | 1.53%   |
| Toshiba                        | 49        | 1.5%    |
| Aquarius                       | 44        | 1.35%   |
| Samsung Electronics            | 41        | 1.25%   |
| Unknown                        | 28        | 0.86%   |
| HUAWEI                         | 27        | 0.83%   |
| Notebook                       | 19        | 0.58%   |
| Fujitsu                        | 19        | 0.58%   |
| Sony                           | 18        | 0.55%   |
| Packard Bell                   | 12        | 0.37%   |
| Panasonic                      | 9         | 0.28%   |
| Clevo                          | 9         | 0.28%   |
| TUXEDO                         | 7         | 0.21%   |
| Medion                         | 7         | 0.21%   |
| Intel                          | 7         | 0.21%   |
| Timi                           | 6         | 0.18%   |
| Positivo                       | 6         | 0.18%   |
| IBM                            | 6         | 0.18%   |
| GPU Company                    | 6         | 0.18%   |
| SLIMBOOK                       | 5         | 0.15%   |
| LG Electronics                 | 5         | 0.15%   |
| Gigabyte Technology            | 5         | 0.15%   |
| HONOR                          | 4         | 0.12%   |
| Fujitsu Siemens                | 4         | 0.12%   |
| Alienware                      | 4         | 0.12%   |
| System76                       | 3         | 0.09%   |
| SmbiosType1_SystemManufacturer | 3         | 0.09%   |
| Pegatron                       | 3         | 0.09%   |
| PC Specialist                  | 3         | 0.09%   |
| Avell High Performance         | 3         | 0.09%   |
| AMI                            | 3         | 0.09%   |
| Shanghai Zhaoxin Semiconductor | 2         | 0.06%   |
| Razer                          | 2         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBook5,2                      | 353       | 10.8%   |
| Apple MacBookAir7,1                   | 77        | 2.36%   |
| Apple MacBookAir7,2                   | 76        | 2.33%   |
| Google Enguarde                       | 74        | 2.26%   |
| Apple MacBook2,1                      | 55        | 1.68%   |
| Aquarius NS585                        | 44        | 1.35%   |
| Unknown                               | 33        | 1.01%   |
| Lenovo ThinkPad E475 20H40006US       | 24        | 0.73%   |
| Google Terra                          | 23        | 0.7%    |
| Apple MacBook4,1                      | 21        | 0.64%   |
| HP Notebook                           | 18        | 0.55%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US | 16        | 0.49%   |
| Acer Aspire A315-23                   | 15        | 0.46%   |
| ASUS 1005HA                           | 14        | 0.43%   |
| Google Reks                           | 13        | 0.4%    |
| HP Pavilion g6                        | 12        | 0.37%   |
| HP Laptop 15-db0xxx                   | 10        | 0.31%   |
| HP EliteBook 8460p                    | 9         | 0.28%   |
| Dell Latitude E7440                   | 9         | 0.28%   |
| HP Pavilion Gaming Laptop 15-ec2xxx   | 8         | 0.24%   |
| Samsung 300E4C/300E5C/300E7C          | 7         | 0.21%   |
| HP Laptop 15-db1xxx                   | 7         | 0.21%   |
| HP Laptop 15-bw0xx                    | 7         | 0.21%   |
| HP EliteBook 840 G3                   | 7         | 0.21%   |
| HP 255 G8 Notebook PC                 | 7         | 0.21%   |
| Dell Latitude E6330                   | 7         | 0.21%   |
| Dell Latitude 7480                    | 7         | 0.21%   |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 6         | 0.18%   |
| HP 250 G7 Notebook PC                 | 6         | 0.18%   |
| Dell XPS 13 9310                      | 6         | 0.18%   |
| Dell Latitude E6420                   | 6         | 0.18%   |
| Dell Latitude E5430 non-vPro          | 6         | 0.18%   |
| Dell Latitude 5420                    | 6         | 0.18%   |
| Dell Inspiron 5100                    | 6         | 0.18%   |
| Apple MacBook7,1                      | 6         | 0.18%   |
| HUAWEI NBLK-WAX9X                     | 5         | 0.15%   |
| HP Laptop 15s-eq2xxx                  | 5         | 0.15%   |
| HP EliteBook 840 G8 Notebook PC       | 5         | 0.15%   |
| Dell Latitude E7450                   | 5         | 0.15%   |
| Dell Latitude E6520                   | 5         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 443       | 13.56%  |
| Apple MacBook5    | 353       | 10.8%   |
| Dell Latitude     | 170       | 5.2%    |
| Apple MacBookAir7 | 153       | 4.68%   |
| Acer Aspire       | 135       | 4.13%   |
| Dell Inspiron     | 117       | 3.58%   |
| Lenovo IdeaPad    | 104       | 3.18%   |
| HP EliteBook      | 92        | 2.82%   |
| Google Enguarde   | 74        | 2.26%   |
| HP Pavilion       | 71        | 2.17%   |
| HP Laptop         | 71        | 2.17%   |
| HP ProBook        | 57        | 1.74%   |
| Apple MacBook2    | 55        | 1.68%   |
| Aquarius NS585    | 44        | 1.35%   |
| ASUS VivoBook     | 43        | 1.32%   |
| Toshiba Satellite | 40        | 1.22%   |
| Dell XPS          | 40        | 1.22%   |
| Unknown           | 33        | 1.01%   |
| Dell Precision    | 31        | 0.95%   |
| HP Compaq         | 30        | 0.92%   |
| Dell Vostro       | 30        | 0.92%   |
| HP ZBook          | 23        | 0.7%    |
| Google Terra      | 23        | 0.7%    |
| ASUS ASUS         | 23        | 0.7%    |
| ASUS ZenBook      | 22        | 0.67%   |
| Apple MacBook4    | 21        | 0.64%   |
| HP 250            | 20        | 0.61%   |
| Acer TravelMate   | 19        | 0.58%   |
| HP Notebook       | 18        | 0.55%   |
| Fujitsu LIFEBOOK  | 17        | 0.52%   |
| Lenovo Legion     | 15        | 0.46%   |
| Acer Swift        | 15        | 0.46%   |
| Acer Nitro        | 15        | 0.46%   |
| Lenovo ThinkBook  | 14        | 0.43%   |
| HP ENVY           | 14        | 0.43%   |
| HP 255            | 14        | 0.43%   |
| ASUS ROG          | 14        | 0.43%   |
| ASUS 1005HA       | 14        | 0.43%   |
| Google Reks       | 13        | 0.4%    |
| HP Stream         | 11        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2009    | 429       | 13.13%  |
| 2021    | 329       | 10.07%  |
| 2019    | 313       | 9.58%   |
| 2020    | 306       | 9.36%   |
| 2016    | 205       | 6.27%   |
| 2015    | 202       | 6.18%   |
| 2012    | 193       | 5.91%   |
| 2018    | 179       | 5.48%   |
| 2017    | 170       | 5.2%    |
| 2011    | 164       | 5.02%   |
| 2013    | 151       | 4.62%   |
| 2022    | 138       | 4.22%   |
| 2014    | 132       | 4.04%   |
| 2010    | 101       | 3.09%   |
| 2007    | 99        | 3.03%   |
| 2008    | 85        | 2.6%    |
| 2006    | 27        | 0.83%   |
| 2005    | 18        | 0.55%   |
| 2003    | 9         | 0.28%   |
| 2023    | 8         | 0.24%   |
| 2004    | 6         | 0.18%   |
| Unknown | 3         | 0.09%   |
| 2002    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3268      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3007      | 91.68%  |
| Enabled  | 273       | 8.32%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3130      | 95.75%  |
| Yes  | 139       | 4.25%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 889       | 27.05%  |
| 3.01-4.0    | 666       | 20.26%  |
| 16.01-24.0  | 480       | 14.6%   |
| 1.01-2.0    | 477       | 14.51%  |
| 8.01-16.0   | 406       | 12.35%  |
| 32.01-64.0  | 165       | 5.02%   |
| 2.01-3.0    | 69        | 2.1%    |
| 0.51-1.0    | 56        | 1.7%    |
| 64.01-256.0 | 36        | 1.1%    |
| 24.01-32.0  | 31        | 0.94%   |
| 0.01-0.5    | 11        | 0.33%   |
| Unknown     | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1516      | 44.07%  |
| 2.01-3.0   | 668       | 19.42%  |
| 4.01-8.0   | 370       | 10.76%  |
| 0.51-1.0   | 366       | 10.64%  |
| 3.01-4.0   | 315       | 9.16%   |
| 8.01-16.0  | 99        | 2.88%   |
| 0.01-0.5   | 92        | 2.67%   |
| 16.01-24.0 | 8         | 0.23%   |
| 32.01-64.0 | 2         | 0.06%   |
| 24.01-32.0 | 2         | 0.06%   |
| Unknown    | 2         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2674      | 80.93%  |
| 2      | 535       | 16.19%  |
| 3      | 54        | 1.63%   |
| 0      | 25        | 0.76%   |
| 4      | 12        | 0.36%   |
| 5      | 3         | 0.09%   |
| 7      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2090      | 63.82%  |
| Yes       | 1185      | 36.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2636      | 80.49%  |
| No        | 639       | 19.51%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3211      | 98.2%   |
| No        | 59        | 1.8%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2696      | 82.12%  |
| No        | 587       | 17.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 1089      | 33.21%  |
| Germany     | 276       | 8.42%   |
| Russia      | 273       | 8.33%   |
| France      | 208       | 6.34%   |
| Spain       | 133       | 4.06%   |
| Brazil      | 107       | 3.26%   |
| Italy       | 106       | 3.23%   |
| Poland      | 96        | 2.93%   |
| UK          | 74        | 2.26%   |
| Netherlands | 53        | 1.62%   |
| Canada      | 48        | 1.46%   |
| Mexico      | 44        | 1.34%   |
| Argentina   | 36        | 1.1%    |
| Switzerland | 35        | 1.07%   |
| Australia   | 34        | 1.04%   |
| China       | 33        | 1.01%   |
| Sweden      | 32        | 0.98%   |
| India       | 28        | 0.85%   |
| Turkey      | 26        | 0.79%   |
| Ukraine     | 25        | 0.76%   |
| Hungary     | 25        | 0.76%   |
| Belgium     | 25        | 0.76%   |
| Finland     | 23        | 0.7%    |
| Austria     | 22        | 0.67%   |
| Portugal    | 21        | 0.64%   |
| Norway      | 20        | 0.61%   |
| Czechia     | 19        | 0.58%   |
| Romania     | 17        | 0.52%   |
| Greece      | 17        | 0.52%   |
| Japan       | 14        | 0.43%   |
| Colombia    | 14        | 0.43%   |
| Chile       | 14        | 0.43%   |
| Venezuela   | 13        | 0.4%    |
| Indonesia   | 13        | 0.4%    |
| Ireland     | 12        | 0.37%   |
| Croatia     | 12        | 0.37%   |
| Bulgaria    | 12        | 0.37%   |
| Denmark     | 10        | 0.3%    |
| Thailand    | 9         | 0.27%   |
| Taiwan      | 9         | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Bangor            | 619       | 18.04%  |
| Dover-Foxcroft    | 229       | 6.67%   |
| Voronezh          | 143       | 4.17%   |
| Seville           | 36        | 1.05%   |
| Paris             | 33        | 0.96%   |
| St Petersburg     | 30        | 0.87%   |
| Madrid            | 26        | 0.76%   |
| Berlin            | 26        | 0.76%   |
| Warsaw            | 24        | 0.7%    |
| Moscow            | 22        | 0.64%   |
| Munich            | 19        | 0.55%   |
| Barcelona         | 17        | 0.5%    |
| Amsterdam         | 16        | 0.47%   |
| Vienna            | 15        | 0.44%   |
| Milan             | 14        | 0.41%   |
| Sao Paulo         | 12        | 0.35%   |
| London            | 12        | 0.35%   |
| Hamburg           | 12        | 0.35%   |
| Istanbul          | 11        | 0.32%   |
| Blizniew          | 11        | 0.32%   |
| Prague            | 10        | 0.29%   |
| Perm              | 10        | 0.29%   |
| Helsinki          | 10        | 0.29%   |
| Frankfurt am Main | 10        | 0.29%   |
| Zagreb            | 9         | 0.26%   |
| Toronto           | 9         | 0.26%   |
| Sydney            | 9         | 0.26%   |
| Dublin            | 9         | 0.26%   |
| Chorzele          | 9         | 0.26%   |
| Athens            | 9         | 0.26%   |
| San Jose          | 8         | 0.23%   |
| Mexico City       | 8         | 0.23%   |
| Mesa              | 8         | 0.23%   |
| Lyon              | 8         | 0.23%   |
| Iasi              | 8         | 0.23%   |
| Cologne           | 8         | 0.23%   |
| Buenos Aires      | 8         | 0.23%   |
| Budapest          | 8         | 0.23%   |
| Brisbane          | 8         | 0.23%   |
| Rome              | 7         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 518       | 634    | 13.51%  |
| WDC                 | 387       | 469    | 10.09%  |
| Seagate             | 308       | 359    | 8.03%   |
| Toshiba             | 298       | 317    | 7.77%   |
| Fujitsu             | 277       | 281    | 7.22%   |
| Unknown             | 264       | 329    | 6.89%   |
| Kingston            | 206       | 254    | 5.37%   |
| Apple               | 174       | 206    | 4.54%   |
| SanDisk             | 172       | 208    | 4.49%   |
| Crucial             | 151       | 175    | 3.94%   |
| SK hynix            | 139       | 155    | 3.63%   |
| Hitachi             | 106       | 121    | 2.76%   |
| A-DATA Technology   | 95        | 180    | 2.48%   |
| Intel               | 89        | 107    | 2.32%   |
| Micron Technology   | 85        | 90     | 2.22%   |
| HGST                | 61        | 76     | 1.59%   |
| KIOXIA              | 48        | 52     | 1.25%   |
| China               | 29        | 30     | 0.76%   |
| Unknown             | 27        | 28     | 0.7%    |
| LITEON              | 25        | 29     | 0.65%   |
| Transcend           | 17        | 23     | 0.44%   |
| SABRENT             | 17        | 18     | 0.44%   |
| Phison              | 16        | 20     | 0.42%   |
| SPCC                | 15        | 16     | 0.39%   |
| LITEONIT            | 15        | 18     | 0.39%   |
| Intenso             | 15        | 19     | 0.39%   |
| Silicon Motion      | 14        | 17     | 0.37%   |
| PNY                 | 14        | 16     | 0.37%   |
| Team                | 11        | 11     | 0.29%   |
| Patriot             | 11        | 11     | 0.29%   |
| JMicron Technology  | 11        | 11     | 0.29%   |
| GOODRAM             | 11        | 12     | 0.29%   |
| SSSTC               | 8         | 8      | 0.21%   |
| Apacer              | 8         | 8      | 0.21%   |
| Netac               | 7         | 8      | 0.18%   |
| Lenovo              | 7         | 8      | 0.18%   |
| UMIS                | 6         | 10     | 0.16%   |
| ASMT                | 6         | 8      | 0.16%   |
| ADATA Technology    | 6         | 6      | 0.16%   |
| Phison Electronics  | 5         | 5      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB     | 237       | 6.06%   |
| Apple SSD AP0128H 121GB            | 77        | 1.97%   |
| Apple SSD SM0128G 121GB            | 70        | 1.79%   |
| Toshiba MK1655GSXF 160GB           | 52        | 1.33%   |
| A-DATA SU800 512GB SSD             | 44        | 1.12%   |
| Toshiba MK1653GSX 160GB            | 43        | 1.1%    |
| Seagate ST1000LM035-1RK172 1TB     | 43        | 1.1%    |
| Kingston SA400S37240G 240GB SSD    | 41        | 1.05%   |
| Unknown AGND3R  16GB               | 39        | 1%      |
| Kingston SA400S37120G 120GB SSD    | 37        | 0.95%   |
| Unknown HAG2e  16GB                | 30        | 0.77%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 28        | 0.72%   |
| Unknown                            | 27        | 0.69%   |
| Unknown SDW16G  16GB               | 25        | 0.64%   |
| Toshiba MQ04ABF100 1TB             | 25        | 0.64%   |
| Toshiba MQ01ABF050 500GB           | 24        | 0.61%   |
| Crucial CT500MX500SSD1 500GB       | 24        | 0.61%   |
| Crucial CT1000MX500SSD1 1TB        | 23        | 0.59%   |
| Samsung SSD 860 EVO 500GB          | 22        | 0.56%   |
| Toshiba MQ01ABD100 1TB             | 21        | 0.54%   |
| Samsung SSD 970 EVO Plus 1TB       | 21        | 0.54%   |
| HGST HTS721010A9E630 1TB           | 20        | 0.51%   |
| Unknown MMC Card  32GB             | 19        | 0.49%   |
| Seagate ST500LT012-1DG142 500GB    | 18        | 0.46%   |
| SABRENT Disk 14TB                  | 17        | 0.43%   |
| Kingston SV300S37A120G 120GB SSD   | 17        | 0.43%   |
| WDC WD1600BUDT-63DPZY0 160GB       | 16        | 0.41%   |
| Samsung SSD 850 EVO 500GB          | 15        | 0.38%   |
| SanDisk SD8SBAT128G1122 128GB SSD  | 14        | 0.36%   |
| HGST HTS541010A9E680 1TB           | 14        | 0.36%   |
| Samsung SSD 850 EVO 250GB          | 13        | 0.33%   |
| Kingston SA400S37480G 480GB SSD    | 13        | 0.33%   |
| Samsung SSD 980 1TB                | 12        | 0.31%   |
| Samsung SSD 860 EVO 250GB          | 12        | 0.31%   |
| Intel SSDPEKNW512G8 512GB          | 12        | 0.31%   |
| Hitachi HTS543216L9SA02 160GB      | 12        | 0.31%   |
| HGST HTS725050A7E630 500GB         | 12        | 0.31%   |
| WDC WD10SPZX-24Z10 1TB             | 11        | 0.28%   |
| Unknown SD/MMC/MS PRO 64GB         | 11        | 0.28%   |
| Seagate ST980811AS 80GB            | 11        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 296       | 345    | 24.1%   |
| Fujitsu             | 277       | 281    | 22.56%  |
| Toshiba             | 241       | 254    | 19.63%  |
| WDC                 | 211       | 240    | 17.18%  |
| Hitachi             | 106       | 121    | 8.63%   |
| HGST                | 61        | 76     | 4.97%   |
| Samsung Electronics | 15        | 16     | 1.22%   |
| Unknown             | 12        | 15     | 0.98%   |
| Intenso             | 2         | 2      | 0.16%   |
| USB3.0              | 1         | 1      | 0.08%   |
| Unknown (CF)        | 1         | 1      | 0.08%   |
| SILICONMOTION       | 1         | 1      | 0.08%   |
| Maxone              | 1         | 1      | 0.08%   |
| IBM/Hitachi         | 1         | 1      | 0.08%   |
| External            | 1         | 1      | 0.08%   |
| ASMT                | 1         | 2      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 229       | 274    | 18.57%  |
| Kingston            | 161       | 207    | 13.06%  |
| Crucial             | 130       | 151    | 10.54%  |
| SanDisk             | 118       | 147    | 9.57%   |
| Apple               | 91        | 100    | 7.38%   |
| A-DATA Technology   | 70        | 142    | 5.68%   |
| WDC                 | 43        | 60     | 3.49%   |
| Micron Technology   | 29        | 32     | 2.35%   |
| China               | 29        | 30     | 2.35%   |
| SK hynix            | 25        | 30     | 2.03%   |
| Intel               | 25        | 27     | 2.03%   |
| LITEON              | 21        | 23     | 1.7%    |
| SABRENT             | 17        | 18     | 1.38%   |
| Transcend           | 15        | 21     | 1.22%   |
| Toshiba             | 15        | 16     | 1.22%   |
| LITEONIT            | 15        | 18     | 1.22%   |
| PNY                 | 13        | 15     | 1.05%   |
| Intenso             | 12        | 16     | 0.97%   |
| SPCC                | 11        | 12     | 0.89%   |
| Patriot             | 11        | 11     | 0.89%   |
| Team                | 10        | 10     | 0.81%   |
| JMicron Technology  | 8         | 8      | 0.65%   |
| GOODRAM             | 8         | 9      | 0.65%   |
| Netac               | 7         | 8      | 0.57%   |
| Apacer              | 7         | 7      | 0.57%   |
| Unknown             | 6         | 6      | 0.49%   |
| Lexar               | 5         | 6      | 0.41%   |
| ASMT                | 5         | 6      | 0.41%   |
| Seagate             | 4         | 4      | 0.32%   |
| Plextor             | 4         | 4      | 0.32%   |
| ZTC                 | 3         | 4      | 0.24%   |
| OCZ                 | 3         | 3      | 0.24%   |
| KIOXIA-EXCERIA      | 3         | 4      | 0.24%   |
| KingDian            | 3         | 3      | 0.24%   |
| FORESEE             | 3         | 3      | 0.24%   |
| Dogfish             | 3         | 5      | 0.24%   |
| Corsair             | 3         | 3      | 0.24%   |
| XrayDisk            | 2         | 2      | 0.16%   |
| Unknown             | 2         | 2      | 0.16%   |
| TO Exter            | 2         | 2      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1207      | 1358   | 32.67%  |
| SSD     | 1156      | 1524   | 31.29%  |
| NVMe    | 1016      | 1264   | 27.5%   |
| MMC     | 283       | 346    | 7.66%   |
| Unknown | 33        | 36     | 0.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2151      | 2767   | 60.29%  |
| NVMe | 1016      | 1263   | 28.48%  |
| MMC  | 283       | 346    | 7.93%   |
| SAS  | 118       | 152    | 3.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1737      | 2105   | 74.39%  |
| 0.51-1.0   | 523       | 686    | 22.4%   |
| 1.01-2.0   | 44        | 56     | 1.88%   |
| 10.01-20.0 | 17        | 18     | 0.73%   |
| 4.01-10.0  | 9         | 11     | 0.39%   |
| 3.01-4.0   | 4         | 5      | 0.17%   |
| 2.01-3.0   | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 935       | 27.77%  |
| Unknown        | 739       | 21.95%  |
| 251-500        | 601       | 17.85%  |
| 501-1000       | 365       | 10.84%  |
| 1-20           | 205       | 6.09%   |
| 51-100         | 195       | 5.79%   |
| 1001-2000      | 147       | 4.37%   |
| 21-50          | 110       | 3.27%   |
| 2001-3000      | 38        | 1.13%   |
| More than 3000 | 32        | 0.95%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1297      | 37.66%  |
| Unknown        | 739       | 21.46%  |
| 21-50          | 376       | 10.92%  |
| 101-250        | 334       | 9.7%    |
| 51-100         | 312       | 9.06%   |
| 251-500        | 201       | 5.84%   |
| 501-1000       | 117       | 3.4%    |
| 1001-2000      | 40        | 1.16%   |
| More than 3000 | 11        | 0.32%   |
| 0              | 10        | 0.29%   |
| 2001-3000      | 7         | 0.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB        | 25        | 25     | 7.37%   |
| Hitachi HTS543216L9SA02 160GB         | 11        | 11     | 3.24%   |
| Toshiba MK1653GSX 160GB               | 9         | 9      | 2.65%   |
| Toshiba MK1655GSXF 160GB              | 8         | 8      | 2.36%   |
| Seagate ST9500325AS 500GB             | 8         | 8      | 2.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 7         | 8      | 2.06%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 6         | 7      | 1.77%   |
| Seagate ST9500420AS 500GB             | 6         | 6      | 1.77%   |
| HGST HTS541010A9E680 1TB              | 6         | 6      | 1.77%   |
| Hitachi HTS542512K9SA00 120GB         | 5         | 6      | 1.47%   |
| WDC WD1600BUDT-63DPZY0 160GB          | 4         | 4      | 1.18%   |
| Toshiba MQ01ABD100 1TB                | 4         | 4      | 1.18%   |
| Seagate ST500LM021-1KJ152 500GB       | 4         | 4      | 1.18%   |
| Hitachi HTS545050B9A300 500GB         | 4         | 4      | 1.18%   |
| Seagate ST9320325AS 320GB             | 3         | 3      | 0.88%   |
| Seagate ST500LT012-9WS142 500GB       | 3         | 3      | 0.88%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 0.88%   |
| Seagate ST500LM000-SSHD-8GB           | 3         | 3      | 0.88%   |
| Seagate ST1000LM035-1RK172 1TB        | 3         | 3      | 0.88%   |
| Kingston SV300S37A120G 120GB SSD      | 3         | 3      | 0.88%   |
| Hitachi HTS547575A9E384 752GB         | 3         | 3      | 0.88%   |
| HGST HTS725050A7E630 500GB            | 3         | 4      | 0.88%   |
| Crucial CT275MX300SSD1 275GB          | 3         | 3      | 0.88%   |
| WDC WD5000LPVX-75V0TT0 500GB          | 2         | 2      | 0.59%   |
| WDC WD10SPZX-60Z10T0 1TB              | 2         | 4      | 0.59%   |
| WDC WD10JPVX-22JC3T0 1TB              | 2         | 2      | 0.59%   |
| Toshiba MQ04ABF100 1TB                | 2         | 2      | 0.59%   |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 0.59%   |
| SK hynix SH920 mSATA 128GB SSD        | 2         | 2      | 0.59%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 2         | 2      | 0.59%   |
| SK hynix HFS256G39MND-2300A 256GB SSD | 2         | 2      | 0.59%   |
| Seagate ST980811AS 80GB               | 2         | 2      | 0.59%   |
| Seagate ST94811A 40GB                 | 2         | 2      | 0.59%   |
| Seagate ST9320423AS 320GB             | 2         | 2      | 0.59%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 2         | 2      | 0.59%   |
| Seagate ST2000LX001-1RG174 2TB        | 2         | 2      | 0.59%   |
| Seagate ST1000LM049-2GH172 1TB        | 2         | 2      | 0.59%   |
| SanDisk SD9TN8W-256G-1006 256GB SSD   | 2         | 2      | 0.59%   |
| SanDisk SD6SP1M256G1012 256GB SSD     | 2         | 2      | 0.59%   |
| Samsung Electronics HM100JC 100GB     | 2         | 2      | 0.59%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 71        | 75     | 21.01%  |
| Hitachi             | 54        | 60     | 15.98%  |
| Toshiba             | 41        | 42     | 12.13%  |
| Fujitsu             | 33        | 33     | 9.76%   |
| WDC                 | 27        | 31     | 7.99%   |
| SK hynix            | 17        | 18     | 5.03%   |
| HGST                | 17        | 19     | 5.03%   |
| Samsung Electronics | 15        | 16     | 4.44%   |
| Kingston            | 13        | 13     | 3.85%   |
| Micron Technology   | 10        | 10     | 2.96%   |
| Intel               | 8         | 9      | 2.37%   |
| SanDisk             | 7         | 8      | 2.07%   |
| Crucial             | 6         | 6      | 1.78%   |
| A-DATA Technology   | 4         | 4      | 1.18%   |
| LITEONIT            | 3         | 4      | 0.89%   |
| LITEON              | 3         | 3      | 0.89%   |
| Unknown             | 2         | 2      | 0.59%   |
| ShiJi               | 1         | 1      | 0.3%    |
| Plextor             | 1         | 1      | 0.3%    |
| Lenovo              | 1         | 1      | 0.3%    |
| KingSpec            | 1         | 1      | 0.3%    |
| IBM/Hitachi         | 1         | 1      | 0.3%    |
| GOODRAM             | 1         | 1      | 0.3%    |
| DGM                 | 1         | 1      | 0.3%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 71        | 75     | 28.4%   |
| Hitachi             | 54        | 60     | 21.6%   |
| Toshiba             | 41        | 42     | 16.4%   |
| Fujitsu             | 33        | 33     | 13.2%   |
| WDC                 | 27        | 31     | 10.8%   |
| HGST                | 17        | 19     | 6.8%    |
| Samsung Electronics | 6         | 6      | 2.4%    |
| IBM/Hitachi         | 1         | 1      | 0.4%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 250       | 267    | 73.96%  |
| SSD  | 72        | 76     | 21.3%   |
| NVMe | 16        | 17     | 4.73%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 12.5%   |
| Toshiba MQ04ABF100 1TB                          | 1         | 1      | 12.5%   |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 12.5%   |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 12.5%   |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 12.5%   |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 12.5%   |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 12.5%   |
| Crucial CT500P2SSD8 500GB                       | 1         | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 25%     |
| Samsung Electronics | 2         | 2      | 25%     |
| WDC                 | 1         | 1      | 12.5%   |
| Toshiba             | 1         | 1      | 12.5%   |
| Hitachi             | 1         | 2      | 12.5%   |
| Crucial             | 1         | 1      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2357      | 3031   | 67.93%  |
| Detected | 768       | 1127   | 22.13%  |
| Malfunc  | 336       | 360    | 9.68%   |
| Failed   | 8         | 9      | 0.23%   |
| Limited  | 1         | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1827      | 50.62%  |
| Nvidia                           | 368       | 10.2%   |
| Samsung Electronics              | 362       | 10.03%  |
| AMD                              | 314       | 8.7%    |
| SanDisk                          | 180       | 4.99%   |
| SK hynix                         | 109       | 3.02%   |
| Apple                            | 83        | 2.3%    |
| Micron Technology                | 56        | 1.55%   |
| Toshiba America Info Systems     | 47        | 1.3%    |
| KIOXIA                           | 47        | 1.3%    |
| Kingston Technology Company      | 47        | 1.3%    |
| ADATA Technology                 | 29        | 0.8%    |
| Phison Electronics               | 26        | 0.72%   |
| Micron/Crucial Technology        | 24        | 0.67%   |
| Silicon Motion                   | 23        | 0.64%   |
| Solid State Storage Technology   | 13        | 0.36%   |
| Union Memory (Shenzhen)          | 9         | 0.25%   |
| Realtek Semiconductor            | 7         | 0.19%   |
| Shenzhen Longsys Electronics     | 4         | 0.11%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.11%   |
| Lite-On Technology               | 4         | 0.11%   |
| Lenovo                           | 4         | 0.11%   |
| ULi Electronics                  | 3         | 0.08%   |
| Silicon Integrated Systems [SiS] | 3         | 0.08%   |
| Marvell Technology Group         | 3         | 0.08%   |
| VIA Technologies                 | 2         | 0.06%   |
| Jiangsu Huacun Elec.             | 2         | 0.06%   |
| ASMedia Technology               | 2         | 0.06%   |
| Yangtze Memory Technologies      | 1         | 0.03%   |
| Transcend                        | 1         | 0.03%   |
| Silicon Image                    | 1         | 0.03%   |
| JMicron Technology               | 1         | 0.03%   |
| INNOGRIT                         | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |
| Unknown                          | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Nvidia MCP79 AHCI Controller                                                   | 359       | 9.28%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 282       | 7.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 221       | 5.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 204       | 5.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 138       | 3.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 136       | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 111       | 2.87%   |
| Intel Volume Management Device NVMe RAID Controller                            | 108       | 2.79%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 90        | 2.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 87        | 2.25%   |
| Samsung NVMe SSD Controller 980                                                | 85        | 2.2%    |
| Samsung Electronics SATA controller                                            | 79        | 2.04%   |
| Apple S1X NVMe Controller                                                      | 78        | 2.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 75        | 1.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 70        | 1.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 62        | 1.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 61        | 1.58%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 57        | 1.47%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 56        | 1.45%   |
| Micron NVMe Storage Controller                                                 | 56        | 1.45%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 54        | 1.4%    |
| Intel Tiger Lake-LP SATA Controller                                            | 52        | 1.34%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 51        | 1.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 48        | 1.24%   |
| Intel Comet Lake SATA AHCI Controller                                          | 47        | 1.21%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 45        | 1.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 44        | 1.14%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 43        | 1.11%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 40        | 1.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 36        | 0.93%   |
| Intel SSD 660P Series                                                          | 34        | 0.88%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 34        | 0.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 30        | 0.78%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 29        | 0.75%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 28        | 0.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 27        | 0.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 27        | 0.7%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 24        | 0.62%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 24        | 0.62%   |
| SanDisk Non-Volatile memory controller                                         | 23        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2241      | 59.41%  |
| NVMe | 1016      | 26.94%  |
| IDE  | 265       | 7.03%   |
| RAID | 250       | 6.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2807      | 85.87%  |
| AMD          | 455       | 13.92%  |
| ARM          | 4         | 0.12%   |
| CentaurHauls | 3         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 355       | 10.85%  |
| Intel Core i5-5250U CPU @ 1.60GHz             | 146       | 4.46%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 90        | 2.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 66        | 2.02%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 59        | 1.8%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 58        | 1.77%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 56        | 1.71%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 45        | 1.38%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 44        | 1.35%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 43        | 1.31%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 41        | 1.25%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 36        | 1.1%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 36        | 1.1%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 35        | 1.07%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 31        | 0.95%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 29        | 0.89%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 28        | 0.86%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 27        | 0.83%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 26        | 0.79%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 25        | 0.76%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 25        | 0.76%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 24        | 0.73%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 24        | 0.73%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 24        | 0.73%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 24        | 0.73%   |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G    | 24        | 0.73%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 23        | 0.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 21        | 0.64%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 20        | 0.61%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 20        | 0.61%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 19        | 0.58%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 18        | 0.55%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 18        | 0.55%   |
| Intel Celeron CPU 3865U @ 1.80GHz             | 18        | 0.55%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 16        | 0.49%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 16        | 0.49%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 16        | 0.49%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 16        | 0.49%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 15        | 0.46%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 15        | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 781       | 23.89%  |
| Intel Core i7           | 500       | 15.3%   |
| Intel Core 2 Duo        | 469       | 14.35%  |
| Intel Celeron           | 283       | 8.66%   |
| Other                   | 280       | 8.57%   |
| Intel Core i3           | 210       | 6.42%   |
| AMD Ryzen 5             | 142       | 4.34%   |
| Intel Atom              | 82        | 2.51%   |
| AMD Ryzen 7             | 70        | 2.14%   |
| Intel Core 2            | 64        | 1.96%   |
| Intel Pentium           | 58        | 1.77%   |
| AMD A6                  | 30        | 0.92%   |
| AMD Ryzen 7 PRO         | 29        | 0.89%   |
| Intel Pentium M         | 22        | 0.67%   |
| Intel Genuine           | 18        | 0.55%   |
| AMD A4                  | 17        | 0.52%   |
| Intel Pentium Dual-Core | 16        | 0.49%   |
| AMD Ryzen 9             | 15        | 0.46%   |
| AMD Ryzen 3             | 13        | 0.4%    |
| AMD Ryzen 5 PRO         | 12        | 0.37%   |
| AMD A8                  | 12        | 0.37%   |
| AMD A10                 | 11        | 0.34%   |
| Intel Pentium Dual      | 10        | 0.31%   |
| Intel Celeron M         | 10        | 0.31%   |
| AMD E1                  | 9         | 0.28%   |
| Intel Pentium 4         | 7         | 0.21%   |
| Intel Core i9           | 7         | 0.21%   |
| AMD E2                  | 7         | 0.21%   |
| AMD A12                 | 6         | 0.18%   |
| Intel Pentium Silver    | 5         | 0.15%   |
| AMD E                   | 5         | 0.15%   |
| Intel Xeon              | 4         | 0.12%   |
| Intel Core m7           | 4         | 0.12%   |
| Intel Core m3           | 4         | 0.12%   |
| AMD PRO A10             | 4         | 0.12%   |
| AMD C-50                | 4         | 0.12%   |
| Intel Pentium Gold      | 3         | 0.09%   |
| Intel Mobile Pentium 4  | 3         | 0.09%   |
| Intel Core Duo          | 3         | 0.09%   |
| AMD Turion 64 Mobile    | 3         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1889      | 57.79%  |
| 4      | 893       | 27.32%  |
| 6      | 167       | 5.11%   |
| 8      | 140       | 4.28%   |
| 1      | 137       | 4.19%   |
| 10     | 22        | 0.67%   |
| 14     | 13        | 0.4%    |
| 12     | 7         | 0.21%   |
| 16     | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3268      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2020      | 61.79%  |
| 1      | 1248      | 38.18%  |
| 4      | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3176      | 97.18%  |
| 32-bit         | 87        | 2.66%   |
| Unknown        | 5         | 0.15%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 527       | 15.9%   |
| 0x1067a    | 412       | 12.43%  |
| 0x306d4    | 215       | 6.49%   |
| 0x306a9    | 155       | 4.68%   |
| 0x806c1    | 136       | 4.1%    |
| 0x206a7    | 127       | 3.83%   |
| 0x806ec    | 112       | 3.38%   |
| 0x30678    | 102       | 3.08%   |
| 0x806e9    | 93        | 2.81%   |
| 0x406e3    | 80        | 2.41%   |
| 0x40651    | 80        | 2.41%   |
| 0x806ea    | 75        | 2.26%   |
| 0x6f6      | 64        | 1.93%   |
| 0x406c4    | 61        | 1.84%   |
| 0xa0652    | 55        | 1.66%   |
| 0x306c3    | 52        | 1.57%   |
| 0x08108109 | 45        | 1.36%   |
| 0x906eb    | 44        | 1.33%   |
| 0x20655    | 44        | 1.33%   |
| 0x08600106 | 41        | 1.24%   |
| 0x906ea    | 40        | 1.21%   |
| 0x0a50000c | 40        | 1.21%   |
| 0x08608103 | 38        | 1.15%   |
| 0x706e5    | 34        | 1.03%   |
| 0x10676    | 34        | 1.03%   |
| 0x0600611a | 31        | 0.94%   |
| 0x706a8    | 29        | 0.88%   |
| 0x06006705 | 28        | 0.84%   |
| 0x6fd      | 26        | 0.78%   |
| 0x106c2    | 26        | 0.78%   |
| 0x806eb    | 23        | 0.69%   |
| 0x506e3    | 23        | 0.69%   |
| 0x506c9    | 23        | 0.69%   |
| 0x106ca    | 22        | 0.66%   |
| 0x08108102 | 21        | 0.63%   |
| 0x6d8      | 20        | 0.6%    |
| 0x906e9    | 19        | 0.57%   |
| 0x906a4    | 19        | 0.57%   |
| 0x806d1    | 19        | 0.57%   |
| 0x906a3    | 16        | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 516       | 15.77%  |
| Penryn           | 457       | 13.97%  |
| Broadwell        | 234       | 7.15%   |
| IvyBridge        | 198       | 6.05%   |
| Silvermont       | 194       | 5.93%   |
| TigerLake        | 173       | 5.29%   |
| Haswell          | 171       | 5.23%   |
| SandyBridge      | 165       | 5.04%   |
| Skylake          | 133       | 4.06%   |
| Core             | 115       | 3.51%   |
| Unknown          | 94        | 2.87%   |
| Zen+             | 88        | 2.69%   |
| Excavator        | 76        | 2.32%   |
| Zen 2            | 75        | 2.29%   |
| Westmere         | 74        | 2.26%   |
| CometLake        | 70        | 2.14%   |
| Zen 3            | 57        | 1.74%   |
| IceLake          | 56        | 1.71%   |
| Bonnell          | 54        | 1.65%   |
| P6               | 49        | 1.5%    |
| Goldmont plus    | 46        | 1.41%   |
| Goldmont         | 28        | 0.86%   |
| Bobcat           | 21        | 0.64%   |
| Puma             | 19        | 0.58%   |
| Zen              | 18        | 0.55%   |
| Alderlake Hybrid | 16        | 0.49%   |
| Jaguar           | 13        | 0.4%    |
| Tremont          | 11        | 0.34%   |
| NetBurst         | 10        | 0.31%   |
| Piledriver       | 9         | 0.28%   |
| K10 Llano        | 9         | 0.28%   |
| K8 Hammer        | 7         | 0.21%   |
| K10              | 6         | 0.18%   |
| Nehalem          | 4         | 0.12%   |
| K8 & K10 hybrid  | 4         | 0.12%   |
| Steamroller      | 2         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2297      | 59.4%   |
| Nvidia                           | 965       | 24.95%  |
| AMD                              | 598       | 15.46%  |
| Zhaoxin                          | 3         | 0.08%   |
| Silicon Integrated Systems [SiS] | 2         | 0.05%   |
| VIA Technologies                 | 1         | 0.03%   |
| S3 Graphics                      | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 353       | 8.69%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 181       | 4.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 153       | 3.77%   |
| Intel HD Graphics 6000                                                                   | 153       | 3.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 149       | 3.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 117       | 2.88%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 102       | 2.51%   |
| Intel UHD Graphics 620                                                                   | 99        | 2.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 97        | 2.39%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 93        | 2.29%   |
| Intel HD Graphics 620                                                                    | 91        | 2.24%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 90        | 2.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 82        | 2.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 80        | 1.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 76        | 1.87%   |
| AMD Renoir                                                                               | 75        | 1.85%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 74        | 1.82%   |
| Intel HD Graphics 5500                                                                   | 72        | 1.77%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 61        | 1.5%    |
| Intel Core Processor Integrated Graphics Controller                                      | 59        | 1.45%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 57        | 1.4%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 55        | 1.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 55        | 1.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 55        | 1.35%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 53        | 1.3%    |
| AMD Lucienne                                                                             | 47        | 1.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 45        | 1.11%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 44        | 1.08%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 42        | 1.03%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 42        | 1.03%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 34        | 0.84%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 30        | 0.74%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 29        | 0.71%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 28        | 0.69%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 25        | 0.62%   |
| Intel HD Graphics 630                                                                    | 25        | 0.62%   |
| Intel HD Graphics 530                                                                    | 25        | 0.62%   |
| Nvidia TU117M                                                                            | 23        | 0.57%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 23        | 0.57%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 23        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1746      | 53.36%  |
| Intel + Nvidia  | 462       | 14.12%  |
| 1 x Nvidia      | 444       | 13.57%  |
| 1 x AMD         | 423       | 12.93%  |
| Intel + AMD     | 80        | 2.44%   |
| AMD + Nvidia    | 60        | 1.83%   |
| 2 x AMD         | 35        | 1.07%   |
| Other           | 14        | 0.43%   |
| 1 x Zhaoxin     | 3         | 0.09%   |
| 1 x SiS         | 2         | 0.06%   |
| 2 x Intel       | 1         | 0.03%   |
| 1 x VIA         | 1         | 0.03%   |
| 1 x S3 Graphics | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2836      | 86.23%  |
| Unknown     | 266       | 8.09%   |
| Proprietary | 187       | 5.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 2340      | 71.04%  |
| 0.01-0.5       | 600       | 18.21%  |
| 1.01-2.0       | 135       | 4.1%    |
| 3.01-4.0       | 91        | 2.76%   |
| 0.51-1.0       | 88        | 2.67%   |
| 5.01-6.0       | 21        | 0.64%   |
| 7.01-8.0       | 11        | 0.33%   |
| 2.01-3.0       | 6         | 0.18%   |
| More than 64.0 | 1         | 0.03%   |
| 8.01-16.0      | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Apple                   | 626       | 18.37%  |
| AU Optronics            | 538       | 15.79%  |
| BOE                     | 446       | 13.09%  |
| LG Display              | 386       | 11.33%  |
| Chimei Innolux          | 370       | 10.86%  |
| Samsung Electronics     | 236       | 6.93%   |
| Lenovo                  | 77        | 2.26%   |
| Dell                    | 66        | 1.94%   |
| Sharp                   | 64        | 1.88%   |
| Chi Mei Optoelectronics | 59        | 1.73%   |
| Goldstar                | 52        | 1.53%   |
| InfoVision              | 47        | 1.38%   |
| BenQ                    | 35        | 1.03%   |
| PANDA                   | 34        | 1%      |
| Hewlett-Packard         | 34        | 1%      |
| Philips                 | 26        | 0.76%   |
| HannStar                | 26        | 0.76%   |
| Unknown                 | 24        | 0.7%    |
| AOC                     | 23        | 0.68%   |
| LG Philips              | 22        | 0.65%   |
| Ancor Communications    | 20        | 0.59%   |
| Iiyama                  | 18        | 0.53%   |
| ViewSonic               | 17        | 0.5%    |
| CSO                     | 16        | 0.47%   |
| Acer                    | 16        | 0.47%   |
| Sony                    | 7         | 0.21%   |
| Eizo                    | 7         | 0.21%   |
| CPT                     | 7         | 0.21%   |
| Quanta Display          | 6         | 0.18%   |
| Panasonic               | 6         | 0.18%   |
| NEC Computers           | 6         | 0.18%   |
| MSI                     | 6         | 0.18%   |
| Pixio                   | 5         | 0.15%   |
| TMX                     | 4         | 0.12%   |
| Toshiba                 | 3         | 0.09%   |
| SLD                     | 3         | 0.09%   |
| LGD                     | 3         | 0.09%   |
| AGO                     | 3         | 0.09%   |
| ___                     | 2         | 0.06%   |
| Vestel Elektronik       | 2         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                      | 209       | 6.08%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                    | 187       | 5.44%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                      | 54        | 1.57%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 42        | 1.22%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch             | 41        | 1.19%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                      | 41        | 1.19%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                      | 38        | 1.11%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 27        | 0.79%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                      | 25        | 0.73%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 25        | 0.73%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 24        | 0.7%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch           | 22        | 0.64%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                      | 22        | 0.64%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 21        | 0.61%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                  | 20        | 0.58%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 19        | 0.55%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 18        | 0.52%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 17        | 0.49%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 15        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 14        | 0.41%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                      | 13        | 0.38%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch      | 12        | 0.35%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 12        | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 11        | 0.32%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                      | 11        | 0.32%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 10        | 0.29%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 10        | 0.29%   |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                         | 10        | 0.29%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 10        | 0.29%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch     | 9         | 0.26%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 9         | 0.26%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 9         | 0.26%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch              | 9         | 0.26%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x165mm 13.2-inch               | 9         | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 9         | 0.26%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                     | 9         | 0.26%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch            | 9         | 0.26%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 9         | 0.26%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch             | 9         | 0.26%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 9         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1150      | 35.55%  |
| 1366x768 (WXGA)    | 875       | 27.05%  |
| 1280x800 (WXGA)    | 520       | 16.07%  |
| 1600x900 (HD+)     | 122       | 3.77%   |
| 1440x900 (WXGA+)   | 119       | 3.68%   |
| 3840x2160 (4K)     | 78        | 2.41%   |
| 2560x1440 (QHD)    | 61        | 1.89%   |
| 1920x1200 (WUXGA)  | 59        | 1.82%   |
| 1024x600           | 47        | 1.45%   |
| 1280x1024 (SXGA)   | 23        | 0.71%   |
| 2288x1287          | 21        | 0.65%   |
| 2560x1600          | 20        | 0.62%   |
| 1680x1050 (WSXGA+) | 17        | 0.53%   |
| 1024x768 (XGA)     | 15        | 0.46%   |
| 3840x2400          | 13        | 0.4%    |
| 2560x1080          | 12        | 0.37%   |
| 1360x768           | 12        | 0.37%   |
| 2880x1800          | 10        | 0.31%   |
| 3440x1440          | 9         | 0.28%   |
| 2160x1440          | 7         | 0.22%   |
| Unknown            | 5         | 0.15%   |
| 3840x1080          | 4         | 0.12%   |
| 1400x1050          | 4         | 0.12%   |
| 3200x1800 (QHD+)   | 3         | 0.09%   |
| 1600x1200          | 3         | 0.09%   |
| 1024x576           | 3         | 0.09%   |
| 3840x1200          | 2         | 0.06%   |
| 3840x1100          | 2         | 0.06%   |
| 2880x1920          | 2         | 0.06%   |
| 2304x1440          | 2         | 0.06%   |
| 2256x1504          | 2         | 0.06%   |
| 1920x540           | 2         | 0.06%   |
| 1920x1280          | 2         | 0.06%   |
| 1280x720 (HD)      | 2         | 0.06%   |
| 3840x1600          | 1         | 0.03%   |
| 3520x1080          | 1         | 0.03%   |
| 3072x1920          | 1         | 0.03%   |
| 2520x1680          | 1         | 0.03%   |
| 2048x1152          | 1         | 0.03%   |
| 1920x515           | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 966       | 28.35%  |
| 13      | 922       | 27.06%  |
| 14      | 386       | 11.33%  |
| 11      | 257       | 7.54%   |
| 17      | 174       | 5.11%   |
| 24      | 111       | 3.26%   |
| 12      | 111       | 3.26%   |
| 27      | 73        | 2.14%   |
| 23      | 70        | 2.05%   |
| 21      | 61        | 1.79%   |
| 10      | 48        | 1.41%   |
| 18      | 29        | 0.85%   |
| 19      | 23        | 0.68%   |
| Unknown | 22        | 0.65%   |
| 142     | 21        | 0.62%   |
| 31      | 21        | 0.62%   |
| 16      | 20        | 0.59%   |
| 34      | 15        | 0.44%   |
| 32      | 9         | 0.26%   |
| 25      | 9         | 0.26%   |
| 22      | 8         | 0.23%   |
| 40      | 7         | 0.21%   |
| 20      | 6         | 0.18%   |
| 84      | 5         | 0.15%   |
| 72      | 5         | 0.15%   |
| 29      | 5         | 0.15%   |
| 54      | 4         | 0.12%   |
| 8       | 3         | 0.09%   |
| 52      | 2         | 0.06%   |
| 49      | 2         | 0.06%   |
| 46      | 2         | 0.06%   |
| 43      | 2         | 0.06%   |
| 28      | 2         | 0.06%   |
| 55      | 1         | 0.03%   |
| 48      | 1         | 0.03%   |
| 47      | 1         | 0.03%   |
| 37      | 1         | 0.03%   |
| 33      | 1         | 0.03%   |
| 26      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1596      | 47.23%  |
| 201-300        | 1089      | 32.23%  |
| 501-600        | 234       | 6.93%   |
| 351-400        | 198       | 5.86%   |
| 401-500        | 118       | 3.49%   |
| 601-700        | 41        | 1.21%   |
| 701-800        | 24        | 0.71%   |
| Unknown        | 22        | 0.65%   |
| More than 2000 | 21        | 0.62%   |
| 1001-1500      | 15        | 0.44%   |
| 1501-2000      | 10        | 0.3%    |
| 801-900        | 8         | 0.24%   |
| 101-200        | 3         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2191      | 70.95%  |
| 16/10   | 766       | 24.81%  |
| 4/3     | 24        | 0.78%   |
| 5/4     | 23        | 0.74%   |
| 3/2     | 21        | 0.68%   |
| 1.00    | 21        | 0.68%   |
| 21/9    | 18        | 0.58%   |
| Unknown | 13        | 0.42%   |
| 2.65    | 4         | 0.13%   |
| 3.40    | 2         | 0.06%   |
| 3.20    | 2         | 0.06%   |
| 32/9    | 1         | 0.03%   |
| 3.73    | 1         | 0.03%   |
| 1.96    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 1107      | 32.58%  |
| 101-110        | 967       | 28.46%  |
| 51-60          | 259       | 7.62%   |
| 71-80          | 195       | 5.74%   |
| 201-250        | 191       | 5.62%   |
| 121-130        | 135       | 3.97%   |
| 61-70          | 107       | 3.15%   |
| 301-350        | 73        | 2.15%   |
| 251-300        | 51        | 1.5%    |
| 351-500        | 48        | 1.41%   |
| 41-50          | 48        | 1.41%   |
| 151-200        | 47        | 1.38%   |
| 141-150        | 40        | 1.18%   |
| More than 1000 | 39        | 1.15%   |
| 131-140        | 25        | 0.74%   |
| Unknown        | 22        | 0.65%   |
| 111-120        | 16        | 0.47%   |
| 501-1000       | 14        | 0.41%   |
| 91-100         | 11        | 0.32%   |
| 1-40           | 3         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1421      | 42.52%  |
| 101-120       | 1196      | 35.79%  |
| 51-100        | 433       | 12.96%  |
| 161-240       | 173       | 5.18%   |
| More than 240 | 54        | 1.62%   |
| 1-50          | 43        | 1.29%   |
| Unknown       | 22        | 0.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2594      | 78.2%   |
| 2     | 411       | 12.39%  |
| 0     | 265       | 7.99%   |
| 3     | 46        | 1.39%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1541      | 29.12%  |
| Realtek Semiconductor             | 1379      | 26.06%  |
| Qualcomm Atheros                  | 609       | 11.51%  |
| Broadcom                          | 603       | 11.39%  |
| Nvidia                            | 365       | 6.9%    |
| Broadcom Limited                  | 223       | 4.21%   |
| Marvell Technology Group          | 108       | 2.04%   |
| MediaTek                          | 59        | 1.11%   |
| ASIX Electronics                  | 37        | 0.7%    |
| Ralink                            | 35        | 0.66%   |
| TP-Link                           | 27        | 0.51%   |
| Dell                              | 27        | 0.51%   |
| Sierra Wireless                   | 25        | 0.47%   |
| Samsung Electronics               | 25        | 0.47%   |
| Ralink Technology                 | 20        | 0.38%   |
| Xiaomi                            | 19        | 0.36%   |
| Qualcomm                          | 16        | 0.3%    |
| DisplayLink                       | 15        | 0.28%   |
| JMicron Technology                | 13        | 0.25%   |
| Ericsson Business Mobile Networks | 13        | 0.25%   |
| Lenovo                            | 12        | 0.23%   |
| Hewlett-Packard                   | 10        | 0.19%   |
| Huawei Technologies               | 8         | 0.15%   |
| OPPO Electronics                  | 6         | 0.11%   |
| NetGear                           | 6         | 0.11%   |
| Fibocom                           | 6         | 0.11%   |
| Cypress Semiconductor             | 6         | 0.11%   |
| Qualcomm Atheros Communications   | 5         | 0.09%   |
| ICS Advent                        | 5         | 0.09%   |
| ASUSTek Computer                  | 5         | 0.09%   |
| AMD                               | 5         | 0.09%   |
| Microchip Technology              | 4         | 0.08%   |
| Attansic Technology               | 4         | 0.08%   |
| ULi Electronics                   | 3         | 0.06%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.06%   |
| Motorola PCS                      | 3         | 0.06%   |
| D-Link                            | 3         | 0.06%   |
| Apple                             | 3         | 0.06%   |
| Winbond Electronics               | 2         | 0.04%   |
| VIA Technologies                  | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 850       | 13.63%  |
| Nvidia MCP79 Ethernet                                                                 | 359       | 5.76%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 358       | 5.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 217       | 3.48%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 159       | 2.55%   |
| Intel Wireless 7260                                                                   | 150       | 2.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 147       | 2.36%   |
| Intel Wireless 8265 / 8275                                                            | 131       | 2.1%    |
| Intel Wi-Fi 6 AX201                                                                   | 122       | 1.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 119       | 1.91%   |
| Intel Wireless 7265                                                                   | 119       | 1.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 117       | 1.88%   |
| Intel Wi-Fi 6 AX200                                                                   | 104       | 1.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 84        | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 81        | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 79        | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 75        | 1.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 73        | 1.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 71        | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 69        | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 69        | 1.11%   |
| Intel Wireless 8260                                                                   | 69        | 1.11%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 56        | 0.9%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 56        | 0.9%    |
| Intel Comet Lake PCH CNVi WiFi                                                        | 55        | 0.88%   |
| Intel Ethernet Connection (4) I219-V                                                  | 49        | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 45        | 0.72%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 45        | 0.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 44        | 0.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 44        | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 41        | 0.66%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 37        | 0.59%   |
| Intel Ethernet Connection I218-LM                                                     | 37        | 0.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 37        | 0.59%   |
| Intel Ethernet Connection I219-LM                                                     | 35        | 0.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 35        | 0.56%   |
| Intel Wireless 3165                                                                   | 34        | 0.55%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 33        | 0.53%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 33        | 0.53%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 33        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1465      | 43.76%  |
| Qualcomm Atheros                      | 554       | 16.55%  |
| Broadcom                              | 522       | 15.59%  |
| Realtek Semiconductor                 | 406       | 12.13%  |
| Broadcom Limited                      | 196       | 5.85%   |
| MediaTek                              | 54        | 1.61%   |
| Ralink                                | 35        | 1.05%   |
| Sierra Wireless                       | 25        | 0.75%   |
| Ralink Technology                     | 20        | 0.6%    |
| Dell                                  | 18        | 0.54%   |
| TP-Link                               | 13        | 0.39%   |
| Qualcomm                              | 7         | 0.21%   |
| NetGear                               | 6         | 0.18%   |
| Fibocom                               | 6         | 0.18%   |
| Qualcomm Atheros Communications       | 5         | 0.15%   |
| ASUSTek Computer                      | 5         | 0.15%   |
| Edimax Technology                     | 2         | 0.06%   |
| Z-Com                                 | 1         | 0.03%   |
| Winbond Electronics                   | 1         | 0.03%   |
| Wilocity                              | 1         | 0.03%   |
| Hewlett-Packard                       | 1         | 0.03%   |
| D-Link System                         | 1         | 0.03%   |
| D-Link                                | 1         | 0.03%   |
| Belkin Components                     | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |
| 3Com                                  | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 358       | 10.65%  |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 159       | 4.73%   |
| Intel Wireless 7260                                                                   | 150       | 4.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 147       | 4.37%   |
| Intel Wireless 8265 / 8275                                                            | 131       | 3.9%    |
| Intel Wi-Fi 6 AX201                                                                   | 122       | 3.63%   |
| Intel Wireless 7265                                                                   | 119       | 3.54%   |
| Intel Wi-Fi 6 AX200                                                                   | 104       | 3.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 84        | 2.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 81        | 2.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 79        | 2.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 75        | 2.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 73        | 2.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 71        | 2.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 69        | 2.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 69        | 2.05%   |
| Intel Wireless 8260                                                                   | 69        | 2.05%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 56        | 1.67%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 55        | 1.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 45        | 1.34%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 45        | 1.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 44        | 1.31%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 44        | 1.31%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 37        | 1.1%    |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 37        | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 35        | 1.04%   |
| Intel Wireless 3165                                                                   | 34        | 1.01%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 33        | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 33        | 0.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 32        | 0.95%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 28        | 0.83%   |
| Intel Wireless 3160                                                                   | 25        | 0.74%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 25        | 0.74%   |
| Intel Centrino Ultimate-N 6300                                                        | 25        | 0.74%   |
| Intel Centrino Advanced-N 6200                                                        | 23        | 0.68%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 23        | 0.68%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 22        | 0.65%   |
| Intel Wireless-AC 9260                                                                | 22        | 0.65%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 20        | 0.6%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 19        | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1224      | 44.36%  |
| Intel                            | 607       | 22%     |
| Nvidia                           | 365       | 13.23%  |
| Qualcomm Atheros                 | 123       | 4.46%   |
| Marvell Technology Group         | 108       | 3.91%   |
| Broadcom                         | 102       | 3.7%    |
| ASIX Electronics                 | 37        | 1.34%   |
| Broadcom Limited                 | 30        | 1.09%   |
| Xiaomi                           | 19        | 0.69%   |
| Samsung Electronics              | 15        | 0.54%   |
| DisplayLink                      | 15        | 0.54%   |
| TP-Link                          | 14        | 0.51%   |
| JMicron Technology               | 13        | 0.47%   |
| Lenovo                           | 12        | 0.43%   |
| Qualcomm                         | 9         | 0.33%   |
| OPPO Electronics                 | 6         | 0.22%   |
| Cypress Semiconductor            | 6         | 0.22%   |
| MediaTek                         | 5         | 0.18%   |
| ICS Advent                       | 5         | 0.18%   |
| Huawei Technologies              | 5         | 0.18%   |
| Microchip Technology             | 4         | 0.14%   |
| Attansic Technology              | 4         | 0.14%   |
| Silicon Integrated Systems [SiS] | 3         | 0.11%   |
| Motorola PCS                     | 3         | 0.11%   |
| Apple                            | 3         | 0.11%   |
| VIA Technologies                 | 2         | 0.07%   |
| Spreadtrum Communications        | 2         | 0.07%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.07%   |
| National Semiconductor           | 2         | 0.07%   |
| Hewlett-Packard                  | 2         | 0.07%   |
| D-Link                           | 2         | 0.07%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.04%   |
| ULi Electronics                  | 1         | 0.04%   |
| MosChip Semiconductor            | 1         | 0.04%   |
| Linksys                          | 1         | 0.04%   |
| LG Electronics                   | 1         | 0.04%   |
| LeEco                            | 1         | 0.04%   |
| Google                           | 1         | 0.04%   |
| Digitech Systems                 | 1         | 0.04%   |
| Davicom Semiconductor            | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 850       | 30.5%   |
| Nvidia MCP79 Ethernet                                             | 359       | 12.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 217       | 7.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 119       | 4.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 117       | 4.2%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 56        | 2.01%   |
| Intel Ethernet Connection (4) I219-V                              | 49        | 1.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 41        | 1.47%   |
| Intel Ethernet Connection I218-LM                                 | 37        | 1.33%   |
| Intel Ethernet Connection I219-LM                                 | 35        | 1.26%   |
| Intel Ethernet Connection (3) I218-LM                             | 33        | 1.18%   |
| ASIX AX88179 Gigabit Ethernet                                     | 30        | 1.08%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 26        | 0.93%   |
| Intel 82577LM Gigabit Network Connection                          | 25        | 0.9%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 22        | 0.79%   |
| Intel Ethernet Connection (6) I219-V                              | 22        | 0.79%   |
| Intel Ethernet Connection (13) I219-V                             | 22        | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20        | 0.72%   |
| Intel Ethernet Connection I219-V                                  | 19        | 0.68%   |
| Intel Ethernet Connection I217-LM                                 | 19        | 0.68%   |
| Intel 82567LM Gigabit Network Connection                          | 18        | 0.65%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 17        | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 15        | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 15        | 0.54%   |
| Intel Ethernet Connection (10) I219-V                             | 15        | 0.54%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 15        | 0.54%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 13        | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 12        | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12        | 0.43%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 11        | 0.39%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 11        | 0.39%   |
| Intel Ethernet Connection (2) I219-LM                             | 11        | 0.39%   |
| Intel Ethernet Connection (13) I219-LM                            | 11        | 0.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 0.36%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 10        | 0.36%   |
| Intel 82579V Gigabit Network Connection                           | 10        | 0.36%   |
| Intel 82566MM Gigabit Network Connection                          | 10        | 0.36%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 9         | 0.32%   |
| Intel Ethernet Connection (6) I219-LM                             | 9         | 0.32%   |
| Intel Ethernet Connection (11) I219-LM                            | 9         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3214      | 54.15%  |
| Ethernet | 2633      | 44.36%  |
| Modem    | 84        | 1.42%   |
| Unknown  | 4         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2437      | 71.05%  |
| Ethernet | 993       | 28.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2383      | 72.85%  |
| 1     | 810       | 24.76%  |
| 0     | 43        | 1.31%   |
| 3     | 34        | 1.04%   |
| 4     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2679      | 81.38%  |
| Yes  | 613       | 18.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1116      | 41.1%   |
| Apple                           | 615       | 22.65%  |
| Realtek Semiconductor           | 230       | 8.47%   |
| Qualcomm Atheros Communications | 204       | 7.51%   |
| Broadcom                        | 110       | 4.05%   |
| Lite-On Technology              | 101       | 3.72%   |
| IMC Networks                    | 100       | 3.68%   |
| Foxconn / Hon Hai               | 60        | 2.21%   |
| Dell                            | 39        | 1.44%   |
| Cambridge Silicon Radio         | 33        | 1.22%   |
| Hewlett-Packard                 | 26        | 0.96%   |
| Toshiba                         | 15        | 0.55%   |
| Realtek                         | 15        | 0.55%   |
| ASUSTek Computer                | 12        | 0.44%   |
| Ralink                          | 11        | 0.41%   |
| Ralink Technology               | 6         | 0.22%   |
| Foxconn International           | 4         | 0.15%   |
| Taiyo Yuden                     | 3         | 0.11%   |
| MediaTek                        | 3         | 0.11%   |
| Alps Electric                   | 3         | 0.11%   |
| Fujitsu                         | 2         | 0.07%   |
| Qcom                            | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| Corsair                         | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| Askey Computer                  | 1         | 0.04%   |
| Unknown                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 492       | 18.11%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 349       | 12.85%  |
| Intel AX201 Bluetooth                               | 229       | 8.43%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 173       | 6.37%   |
| Apple Bluetooth USB Host Controller                 | 158       | 5.82%   |
| Realtek Bluetooth Radio                             | 146       | 5.38%   |
| Qualcomm Atheros  Bluetooth Device                  | 129       | 4.75%   |
| Intel AX200 Bluetooth                               | 101       | 3.72%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 2.8%    |
| Realtek  Bluetooth 4.2 Adapter                      | 55        | 2.03%   |
| Intel Bluetooth Device                              | 44        | 1.62%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 39        | 1.44%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 33        | 1.22%   |
| Apple Bluetooth Host Controller                     | 29        | 1.07%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 28        | 1.03%   |
| IMC Networks Bluetooth Radio                        | 28        | 1.03%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 25        | 0.92%   |
| Lite-On Bluetooth Device                            | 24        | 0.88%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 24        | 0.88%   |
| IMC Networks Bluetooth Device                       | 22        | 0.81%   |
| IMC Networks Wireless_Device                        | 21        | 0.77%   |
| Foxconn / Hon Hai Bluetooth Device                  | 21        | 0.77%   |
| Broadcom BCM2045B (BDC-2.1)                         | 19        | 0.7%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 0.66%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 18        | 0.66%   |
| Intel AX210 Bluetooth                               | 18        | 0.66%   |
| Realtek RTL8723B Bluetooth                          | 16        | 0.59%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 16        | 0.59%   |
| Intel Wireless-AC 3168 Bluetooth                    | 16        | 0.59%   |
| Dell BCM20702A0 Bluetooth Module                    | 16        | 0.59%   |
| Realtek Bluetooth Radio                             | 15        | 0.55%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 14        | 0.52%   |
| Lite-On Atheros AR3012 Bluetooth                    | 13        | 0.48%   |
| Lite-On Wireless_Device                             | 12        | 0.44%   |
| HP Broadcom 2070 Bluetooth Combo                    | 12        | 0.44%   |
| Ralink RT3290 Bluetooth                             | 11        | 0.41%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 9         | 0.33%   |
| Dell DW375 Bluetooth Module                         | 9         | 0.33%   |
| Broadcom HP Portable SoftSailing                    | 9         | 0.33%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 9         | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2400      | 64.27%  |
| Nvidia                                       | 668       | 17.89%  |
| AMD                                          | 487       | 13.04%  |
| C-Media Electronics                          | 23        | 0.62%   |
| Realtek Semiconductor                        | 14        | 0.37%   |
| Logitech                                     | 14        | 0.37%   |
| Lenovo                                       | 11        | 0.29%   |
| Texas Instruments                            | 10        | 0.27%   |
| Generalplus Technology                       | 10        | 0.27%   |
| Plantronics                                  | 9         | 0.24%   |
| GN Netcom                                    | 8         | 0.21%   |
| Hewlett-Packard                              | 7         | 0.19%   |
| Zoran Co. Personal Media Division (Nogatech) | 6         | 0.16%   |
| Creative Technology                          | 5         | 0.13%   |
| ASUSTek Computer                             | 5         | 0.13%   |
| JMTek                                        | 4         | 0.11%   |
| Zhaoxin                                      | 3         | 0.08%   |
| ULi Electronics                              | 3         | 0.08%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.08%   |
| VIA Technologies                             | 2         | 0.05%   |
| Sennheiser Communications                    | 2         | 0.05%   |
| SAVITECH                                     | 2         | 0.05%   |
| RODE Microphones                             | 2         | 0.05%   |
| Razer USA                                    | 2         | 0.05%   |
| Microsoft                                    | 2         | 0.05%   |
| Kingston Technology                          | 2         | 0.05%   |
| CMX Systems                                  | 2         | 0.05%   |
| XMOS                                         | 1         | 0.03%   |
| Toshiba                                      | 1         | 0.03%   |
| Thomann                                      | 1         | 0.03%   |
| Tenx Technology                              | 1         | 0.03%   |
| Syntek                                       | 1         | 0.03%   |
| SteelSeries ApS                              | 1         | 0.03%   |
| Sony                                         | 1         | 0.03%   |
| Samsung Electronics                          | 1         | 0.03%   |
| Pixart Imaging                               | 1         | 0.03%   |
| Phoenix Audio Technologies                   | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)                | 1         | 0.03%   |
| Microdia                                     | 1         | 0.03%   |
| M-Audio                                      | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia MCP79 High Definition Audio                                                                | 361       | 7.94%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 319       | 7.02%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 284       | 6.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 237       | 5.21%   |
| Intel Broadwell-U Audio Controller                                                                | 234       | 5.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 231       | 5.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 172       | 3.78%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 145       | 3.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 136       | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 126       | 2.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 106       | 2.33%   |
| Intel Cannon Lake PCH cAVS                                                                        | 105       | 2.31%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 104       | 2.29%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 101       | 2.22%   |
| Intel 8 Series HD Audio Controller                                                                | 101       | 2.22%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 89        | 1.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 83        | 1.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 77        | 1.69%   |
| AMD Kabini HDMI/DP Audio                                                                          | 74        | 1.63%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 73        | 1.61%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 70        | 1.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 70        | 1.54%   |
| Intel Comet Lake PCH cAVS                                                                         | 65        | 1.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 65        | 1.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 63        | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 62        | 1.36%   |
| AMD FCH Azalia Controller                                                                         | 61        | 1.34%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 54        | 1.19%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 46        | 1.01%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 39        | 0.86%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 38        | 0.84%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 37        | 0.81%   |
| AMD High Definition Audio Controller                                                              | 34        | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 28        | 0.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 28        | 0.62%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 27        | 0.59%   |
| Intel CM238 HD Audio Controller                                                                   | 27        | 0.59%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 26        | 0.57%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 23        | 0.51%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 21        | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 972       | 29.72%  |
| Samsung Electronics | 848       | 25.92%  |
| Micron Technology   | 360       | 11.01%  |
| Kingston            | 215       | 6.57%   |
| Unknown             | 207       | 6.33%   |
| Crucial             | 172       | 5.26%   |
| Elpida              | 100       | 3.06%   |
| A-DATA Technology   | 63        | 1.93%   |
| Ramaxel Technology  | 56        | 1.71%   |
| Nanya Technology    | 36        | 1.1%    |
| Corsair             | 34        | 1.04%   |
| Unknown (ABCD)      | 24        | 0.73%   |
| GOODRAM             | 23        | 0.7%    |
| Smart               | 20        | 0.61%   |
| Unknown             | 15        | 0.46%   |
| Transcend           | 13        | 0.4%    |
| Team                | 13        | 0.4%    |
| G.Skill             | 10        | 0.31%   |
| Silicon Power       | 6         | 0.18%   |
| Patriot             | 6         | 0.18%   |
| ASint Technology    | 5         | 0.15%   |
| Apacer              | 5         | 0.15%   |
| Wilk                | 3         | 0.09%   |
| Timetec             | 3         | 0.09%   |
| Smart Brazil        | 3         | 0.09%   |
| Qimonda             | 3         | 0.09%   |
| PNY                 | 3         | 0.09%   |
| Infineon            | 3         | 0.09%   |
| fef5                | 3         | 0.09%   |
| AMD                 | 3         | 0.09%   |
| 48spaces            | 3         | 0.09%   |
| Unknown (89F7)      | 2         | 0.06%   |
| Unifosa             | 2         | 0.06%   |
| Teikon              | 2         | 0.06%   |
| Shenzhen WODPOSIT   | 2         | 0.06%   |
| SHARETRONIC         | 2         | 0.06%   |
| Neo Forza           | 2         | 0.06%   |
| Kllisre             | 2         | 0.06%   |
| Goldkey             | 2         | 0.06%   |
| ff                  | 2         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 264       | 7.74%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 1.99%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 63        | 1.85%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 60        | 1.76%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 44        | 1.29%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 40        | 1.17%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 32        | 0.94%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 31        | 0.91%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 30        | 0.88%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 30        | 0.88%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 29        | 0.85%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.85%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 27        | 0.79%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 26        | 0.76%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 26        | 0.76%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 25        | 0.73%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 25        | 0.73%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 25        | 0.73%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 25        | 0.73%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 25        | 0.73%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.73%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 23        | 0.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 23        | 0.67%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 23        | 0.67%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 22        | 0.64%   |
| Micron RAM EDF8132A3MA-GD-F 2GB LPDDR3 1600MT/s                  | 21        | 0.62%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 19        | 0.56%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 18        | 0.53%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 18        | 0.53%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.5%    |
| Micron RAM Module 2GB SODIMM DDR2 800MT/s                        | 17        | 0.5%    |
| Micron RAM 4KTF25664HZ-1G6E 2GB SODIMM DDR3 1333MT/s             | 16        | 0.47%   |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                       | 16        | 0.47%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 15        | 0.44%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 15        | 0.44%   |
| Unknown                                                          | 15        | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 14        | 0.41%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 0.41%   |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s            | 14        | 0.41%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 13        | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1067      | 37.1%   |
| DDR3    | 953       | 33.14%  |
| DDR2    | 536       | 18.64%  |
| LPDDR4  | 95        | 3.3%    |
| LPDDR3  | 93        | 3.23%   |
| SDRAM   | 60        | 2.09%   |
| DDR     | 34        | 1.18%   |
| Unknown | 19        | 0.66%   |
| DDR5    | 8         | 0.28%   |
| DRAM    | 6         | 0.21%   |
| LPDDR5  | 5         | 0.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2642      | 91.7%   |
| Row Of Chips | 153       | 5.31%   |
| Unknown      | 51        | 1.77%   |
| Chip         | 23        | 0.8%    |
| DIMM         | 12        | 0.42%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 877       | 28.46%  |
| 4096  | 775       | 25.15%  |
| 2048  | 514       | 16.68%  |
| 1024  | 497       | 16.13%  |
| 16384 | 310       | 10.06%  |
| 32768 | 61        | 1.98%   |
| 512   | 34        | 1.1%    |
| 256   | 11        | 0.36%   |
| 8072  | 1         | 0.03%   |
| 384   | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 744       | 24.39%  |
| 2667    | 478       | 15.67%  |
| 3200    | 463       | 15.18%  |
| 800     | 371       | 12.16%  |
| 2400    | 171       | 5.61%   |
| 667     | 144       | 4.72%   |
| 1334    | 112       | 3.67%   |
| 2133    | 106       | 3.48%   |
| 1333    | 88        | 2.89%   |
| Unknown | 66        | 2.16%   |
| 1067    | 41        | 1.34%   |
| 1867    | 39        | 1.28%   |
| 4267    | 34        | 1.11%   |
| 3266    | 30        | 0.98%   |
| 4199    | 22        | 0.72%   |
| 1066    | 20        | 0.66%   |
| 533     | 16        | 0.52%   |
| 4800    | 12        | 0.39%   |
| 2048    | 11        | 0.36%   |
| 8400    | 10        | 0.33%   |
| 975     | 10        | 0.33%   |
| 4266    | 8         | 0.26%   |
| 333     | 8         | 0.26%   |
| 3733    | 7         | 0.23%   |
| 266     | 7         | 0.23%   |
| 6400    | 6         | 0.2%    |
| 1866    | 5         | 0.16%   |
| 400     | 5         | 0.16%   |
| 2666    | 3         | 0.1%    |
| 933     | 3         | 0.1%    |
| 2933    | 2         | 0.07%   |
| 1639    | 2         | 0.07%   |
| 3000    | 1         | 0.03%   |
| 1596    | 1         | 0.03%   |
| 200     | 1         | 0.03%   |
| 166     | 1         | 0.03%   |
| 133     | 1         | 0.03%   |
| 100     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 7         | 33.33%  |
| Canon               | 5         | 23.81%  |
| Xerox               | 4         | 19.05%  |
| Brother Industries  | 3         | 14.29%  |
| Seiko Epson         | 1         | 4.76%   |
| Samsung Electronics | 1         | 4.76%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Xerox B205                          | 4         | 19.05%  |
| Seiko Epson L120 Series             | 1         | 4.76%   |
| Samsung ML-2010P Mono Laser Printer | 1         | 4.76%   |
| HP LaserJet P1005                   | 1         | 4.76%   |
| HP LaserJet 1160 series             | 1         | 4.76%   |
| HP LaserJet 1150                    | 1         | 4.76%   |
| HP LaserJet 1022                    | 1         | 4.76%   |
| HP Ink Tank 110 series              | 1         | 4.76%   |
| HP DeskJet 2600 series              | 1         | 4.76%   |
| HP DeskJet 2130 series              | 1         | 4.76%   |
| Canon PIXMA MX920 Series            | 1         | 4.76%   |
| Canon LiDE 300                      | 1         | 4.76%   |
| Canon LBP3010/LBP3018/LBP3050       | 1         | 4.76%   |
| Canon LBP2900                       | 1         | 4.76%   |
| Canon G3010 series                  | 1         | 4.76%   |
| Brother PT-9500PC                   | 1         | 4.76%   |
| Brother MFC-L2707DW                 | 1         | 4.76%   |
| Brother HL-L2340D series            | 1         | 4.76%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Canon          | 4         | 57.14%  |
| Seiko Epson    | 2         | 28.57%  |
| Mustek Systems | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 120                       | 2         | 28.57%  |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 14.29%  |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 14.29%  |
| Mustek Systems BearPaw 2400 CU Plus           | 1         | 14.29%  |
| Canon CanoScan LIDE 25                        | 1         | 14.29%  |
| Canon CanoScan LiDE 220                       | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 572       | 24.08%  |
| IMC Networks                           | 266       | 11.2%   |
| Quanta                                 | 225       | 9.47%   |
| Microdia                               | 179       | 7.54%   |
| Realtek Semiconductor                  | 173       | 7.28%   |
| Acer                                   | 144       | 6.06%   |
| Bison Electronics                      | 109       | 4.59%   |
| Sunplus Innovation Technology          | 107       | 4.51%   |
| Cheng Uei Precision Industry (Foxlink) | 84        | 3.54%   |
| Suyin                                  | 72        | 3.03%   |
| Lite-On Technology                     | 63        | 2.65%   |
| Syntek                                 | 52        | 2.19%   |
| Luxvisions Innotech Limited            | 52        | 2.19%   |
| Apple                                  | 45        | 1.89%   |
| Logitech                               | 28        | 1.18%   |
| Silicon Motion                         | 26        | 1.09%   |
| Alcor Micro                            | 23        | 0.97%   |
| Lenovo                                 | 22        | 0.93%   |
| Sonix Technology                       | 13        | 0.55%   |
| Ricoh                                  | 12        | 0.51%   |
| Z-Star Microelectronics                | 10        | 0.42%   |
| Primax Electronics                     | 10        | 0.42%   |
| Importek                               | 8         | 0.34%   |
| ALi                                    | 6         | 0.25%   |
| SunplusIT                              | 5         | 0.21%   |
| Intel                                  | 5         | 0.21%   |
| icSpring                               | 5         | 0.21%   |
| Genesys Logic                          | 5         | 0.21%   |
| Y Media                                | 4         | 0.17%   |
| Samsung Electronics                    | 4         | 0.17%   |
| OmniVision Technologies                | 3         | 0.13%   |
| MacroSilicon                           | 3         | 0.13%   |
| Sunplus Technology                     | 2         | 0.08%   |
| Pixart Imaging                         | 2         | 0.08%   |
| Mimaki Engineering                     | 2         | 0.08%   |
| Microsoft                              | 2         | 0.08%   |
| Huawei Technologies                    | 2         | 0.08%   |
| Generalplus Technology                 | 2         | 0.08%   |
| ARC International                      | 2         | 0.08%   |
| Alpha Imaging Technology               | 2         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 166       | 6.97%   |
| Microdia Integrated_Webcam_HD                       | 94        | 3.94%   |
| IMC Networks Integrated Camera                      | 81        | 3.4%    |
| Quanta Chromebook HD Camera                         | 69        | 2.9%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 63        | 2.64%   |
| Realtek Integrated_Webcam_HD                        | 60        | 2.52%   |
| Chicony HD WebCam                                   | 50        | 2.1%    |
| Acer BisonCam, NB Pro                               | 50        | 2.1%    |
| Sunplus Integrated_Webcam_HD                        | 38        | 1.59%   |
| Chicony USB2.0 HD UVC WebCam                        | 35        | 1.47%   |
| Bison Integrated Camera                             | 34        | 1.43%   |
| Chicony HP HD Camera                                | 33        | 1.38%   |
| Acer Integrated Camera                              | 32        | 1.34%   |
| Quanta HP TrueVision HD Camera                      | 29        | 1.22%   |
| Quanta HD User Facing                               | 28        | 1.17%   |
| Syntek Integrated Camera                            | 27        | 1.13%   |
| Quanta VGA WebCam                                   | 27        | 1.13%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 27        | 1.13%   |
| Lite-On Integrated Camera                           | 22        | 0.92%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 21        | 0.88%   |
| Bison SunplusIT Integrated Camera                   | 21        | 0.88%   |
| Realtek USB Camera                                  | 20        | 0.84%   |
| Lite-On HP HD Camera                                | 20        | 0.84%   |
| Microdia Integrated Webcam                          | 19        | 0.8%    |
| Quanta HP HD Camera                                 | 18        | 0.76%   |
| Chicony HP Truevision HD camera                     | 17        | 0.71%   |
| Chicony HD User Facing                              | 17        | 0.71%   |
| Acer HD Webcam                                      | 16        | 0.67%   |
| Luxvisions Innotech Limited HP HD Camera            | 15        | 0.63%   |
| Chicony Chromebook HD Camera                        | 15        | 0.63%   |
| Realtek Integrated Webcam                           | 14        | 0.59%   |
| Chicony Lenovo EasyCamera                           | 14        | 0.59%   |
| Chicony Integrated Camera (1280x720@30)             | 14        | 0.59%   |
| Chicony HP Webcam                                   | 14        | 0.59%   |
| Chicony HP Truevision HD                            | 14        | 0.59%   |
| Apple Built-in iSight                               | 14        | 0.59%   |
| Sunplus HD WebCam                                   | 13        | 0.55%   |
| IMC Networks USB 2.0 Camera                         | 13        | 0.55%   |
| Acer BisonCam,NB Pro                                | 13        | 0.55%   |
| Suyin HP TrueVision HD                              | 12        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 172       | 35.32%  |
| Synaptics                          | 146       | 29.98%  |
| Shenzhen Goodix Technology         | 68        | 13.96%  |
| Upek                               | 28        | 5.75%   |
| AuthenTec                          | 24        | 4.93%   |
| Elan Microelectronics              | 21        | 4.31%   |
| LighTuning Technology              | 17        | 3.49%   |
| STMicroelectronics                 | 9         | 1.85%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.21%   |
| Focal-systems.Corp                 | 1         | 0.21%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 62        | 12.73%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 42        | 8.62%   |
| Shenzhen Goodix  Fingerprint Device                                        | 40        | 8.21%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 32        | 6.57%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 32        | 6.57%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 25        | 5.13%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 23        | 4.72%   |
| Validity Sensors Synaptics WBDI                                            | 17        | 3.49%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 17        | 3.49%   |
| Shenzhen Goodix FingerPrint                                                | 15        | 3.08%   |
| Shenzhen Goodix Fingerprint Reader                                         | 13        | 2.67%   |
| Elan ELAN:Fingerprint                                                      | 12        | 2.46%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 11        | 2.26%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 2.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 10        | 2.05%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 9         | 1.85%   |
| Elan ELAN:ARM-M4                                                           | 9         | 1.85%   |
| Validity Sensors VFS491                                                    | 8         | 1.64%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 1.44%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.44%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.23%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.23%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 1.23%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.23%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 1.23%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.23%   |
| AuthenTec AES2810                                                          | 6         | 1.23%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.82%   |
| Synaptics UWP WBDI                                                         | 4         | 0.82%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.62%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.62%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.62%   |
| Synaptics WBDI                                                             | 3         | 0.62%   |
| Synaptics  WBDI                                                            | 3         | 0.62%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.62%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.41%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.41%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.41%   |
| STMicroelectronics TouchChipÂ Fingerprint Reader                          | 2         | 0.41%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.41%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 99        | 37.08%  |
| Alcor Micro               | 93        | 34.83%  |
| Upek                      | 24        | 8.99%   |
| O2 Micro                  | 21        | 7.87%   |
| Lenovo                    | 16        | 5.99%   |
| Gemalto (was Gemplus)     | 3         | 1.12%   |
| Yubico.com                | 2         | 0.75%   |
| SCM Microsystems          | 2         | 0.75%   |
| Aladdin Knowledge Systems | 2         | 0.75%   |
| OmniKey                   | 1         | 0.37%   |
| Clay Logic                | 1         | 0.37%   |
| Cherry                    | 1         | 0.37%   |
| C3PO                      | 1         | 0.37%   |
| Advanced Card Systems     | 1         | 0.37%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 92        | 34.46%  |
| Broadcom 58200                                                               | 33        | 12.36%  |
| Broadcom BCM5880 Secure Applications Processor                               | 28        | 10.49%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 24        | 8.99%   |
| Broadcom 5880                                                                | 21        | 7.87%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 6.74%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 5.99%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 15        | 5.62%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 1.12%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.75%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.75%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.75%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.75%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.37%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.37%   |
| OmniKey CardMan 4321                                                         | 1         | 0.37%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.37%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.37%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.37%   |
| C3PO LTC31v2                                                                 | 1         | 0.37%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.37%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.37%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1925      | 58.28%  |
| 1     | 1053      | 31.88%  |
| 2     | 254       | 7.69%   |
| 3     | 62        | 1.88%   |
| 4     | 5         | 0.15%   |
| 5     | 3         | 0.09%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 485       | 28.18%  |
| Graphics card            | 462       | 26.84%  |
| Chipcard                 | 249       | 14.47%  |
| Multimedia controller    | 202       | 11.74%  |
| Net/wireless             | 170       | 9.88%   |
| Bluetooth                | 32        | 1.86%   |
| Communication controller | 26        | 1.51%   |
| Storage                  | 22        | 1.28%   |
| Card reader              | 19        | 1.1%    |
| Camera                   | 19        | 1.1%    |
| Sound                    | 10        | 0.58%   |
| Net/ethernet             | 9         | 0.52%   |
| Network                  | 4         | 0.23%   |
| Modem                    | 4         | 0.23%   |
| Flash memory             | 4         | 0.23%   |
| Unassigned class         | 2         | 0.12%   |
| Tv card                  | 1         | 0.06%   |
| Firewire controller      | 1         | 0.06%   |


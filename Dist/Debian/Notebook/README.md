Debian - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Debian.

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

Total: 7079

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 7440               | [f63ada6c61](https://linux-hardware.org/?probe=f63ada6c61) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | [a62438daef](https://linux-hardware.org/?probe=a62438daef) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | [fab548c31e](https://linux-hardware.org/?probe=fab548c31e) | Jun 10, 2023 |
| IT Channel... | N8xEJEK                     | [51a7e3f5b4](https://linux-hardware.org/?probe=51a7e3f5b4) | Jun 10, 2023 |
| Acidanther... | MacBookPro15,2              | [fb30b2eb35](https://linux-hardware.org/?probe=fb30b2eb35) | Jun 10, 2023 |
| Intel         | powered classmate PC        | [e530f037c6](https://linux-hardware.org/?probe=e530f037c6) | Jun 09, 2023 |
| Dell          | Latitude 5480               | [5b3fb0b4f8](https://linux-hardware.org/?probe=5b3fb0b4f8) | Jun 09, 2023 |
| Digibras      | NH4CU03                     | [c66d30943e](https://linux-hardware.org/?probe=c66d30943e) | Jun 09, 2023 |
| Acer          | TravelMate P215-53          | [9536bf547a](https://linux-hardware.org/?probe=9536bf547a) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK U7411              | [ab35c95b72](https://linux-hardware.org/?probe=ab35c95b72) | Jun 09, 2023 |
| Acer          | TravelMate P449-G2-M        | [6b42200bee](https://linux-hardware.org/?probe=6b42200bee) | Jun 09, 2023 |
| HP            | G42                         | [fe8d2be276](https://linux-hardware.org/?probe=fe8d2be276) | Jun 08, 2023 |
| HP            | Laptop 14-cm0xxx            | [f1100ce875](https://linux-hardware.org/?probe=f1100ce875) | Jun 08, 2023 |
| HP            | G42                         | [4f33462d46](https://linux-hardware.org/?probe=4f33462d46) | Jun 08, 2023 |
| Acer          | TravelMate P449-G2-M        | [0fa009ad04](https://linux-hardware.org/?probe=0fa009ad04) | Jun 08, 2023 |
| MSI           | GE60 2PL                    | [e1d118e2d2](https://linux-hardware.org/?probe=e1d118e2d2) | Jun 08, 2023 |
| HP            | G62                         | [fb9522ceac](https://linux-hardware.org/?probe=fb9522ceac) | Jun 08, 2023 |
| Acer          | Aspire 7741                 | [09b2301e59](https://linux-hardware.org/?probe=09b2301e59) | Jun 08, 2023 |
| Lenovo        | ThinkPad X131e 3374A17      | [d992393271](https://linux-hardware.org/?probe=d992393271) | Jun 08, 2023 |
| Lenovo        | ThinkPad X131e 3374A17      | [dd385507aa](https://linux-hardware.org/?probe=dd385507aa) | Jun 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ef71a1641b](https://linux-hardware.org/?probe=ef71a1641b) | Jun 08, 2023 |
| HP            | Pavilion 17                 | [da809f90cc](https://linux-hardware.org/?probe=da809f90cc) | Jun 07, 2023 |
| Dell          | Latitude 5530               | [1e3452635f](https://linux-hardware.org/?probe=1e3452635f) | Jun 07, 2023 |
| HP            | ProBook 4530s               | [bdb6739deb](https://linux-hardware.org/?probe=bdb6739deb) | Jun 07, 2023 |
| Intel         | HURONRIVER                  | [57035a777c](https://linux-hardware.org/?probe=57035a777c) | Jun 07, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [490ae0bc1c](https://linux-hardware.org/?probe=490ae0bc1c) | Jun 07, 2023 |
| MSI           | Pulse GL66 12UDK            | [8c9a9eb310](https://linux-hardware.org/?probe=8c9a9eb310) | Jun 06, 2023 |
| HP            | Pavilion g7                 | [f8cccf0fec](https://linux-hardware.org/?probe=f8cccf0fec) | Jun 06, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [be9987ca28](https://linux-hardware.org/?probe=be9987ca28) | Jun 06, 2023 |
| Fujitsu       | FMVNA4NE-                   | [626a677331](https://linux-hardware.org/?probe=626a677331) | Jun 06, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [c20dd8572a](https://linux-hardware.org/?probe=c20dd8572a) | Jun 05, 2023 |
| HP            | ENVY Laptop 13-ba0xxx       | [22143d333a](https://linux-hardware.org/?probe=22143d333a) | Jun 05, 2023 |
| Aquarius      | NS585                       | [b3f11e4a53](https://linux-hardware.org/?probe=b3f11e4a53) | Jun 05, 2023 |
| Fujitsu       | FMVNA4NE-                   | [b1c1176a5b](https://linux-hardware.org/?probe=b1c1176a5b) | Jun 05, 2023 |
| Dell          | Latitude 3410               | [820e62c9d3](https://linux-hardware.org/?probe=820e62c9d3) | Jun 04, 2023 |
| MSI           | GL75 Leopard 10SER          | [24111ade43](https://linux-hardware.org/?probe=24111ade43) | Jun 04, 2023 |
| Dell          | Latitude 3410               | [12515d41c8](https://linux-hardware.org/?probe=12515d41c8) | Jun 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [1352a1d7c7](https://linux-hardware.org/?probe=1352a1d7c7) | Jun 04, 2023 |
| ASUSTek       | Q502LA                      | [679a477085](https://linux-hardware.org/?probe=679a477085) | Jun 04, 2023 |
| Clevo         | M670SRU                     | [0935f74d34](https://linux-hardware.org/?probe=0935f74d34) | Jun 04, 2023 |
| Clevo         | M670SRU                     | [e163d57d56](https://linux-hardware.org/?probe=e163d57d56) | Jun 04, 2023 |
| AVITA         | NS14A8                      | [a576b4d5cc](https://linux-hardware.org/?probe=a576b4d5cc) | Jun 04, 2023 |
| Dell          | Latitude 5420               | [9085f3c8f7](https://linux-hardware.org/?probe=9085f3c8f7) | Jun 04, 2023 |
| Toshiba       | WT8-A                       | [01e8918ef6](https://linux-hardware.org/?probe=01e8918ef6) | Jun 04, 2023 |
| Acer          | Aspire 5738                 | [138d22e03e](https://linux-hardware.org/?probe=138d22e03e) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [a10a42a44d](https://linux-hardware.org/?probe=a10a42a44d) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [e58b2a1237](https://linux-hardware.org/?probe=e58b2a1237) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [ce54d0192d](https://linux-hardware.org/?probe=ce54d0192d) | Jun 04, 2023 |
| Lenovo        | ThinkPad E420 1141R79       | [7f66bf0045](https://linux-hardware.org/?probe=7f66bf0045) | Jun 03, 2023 |
| Apple         | MacBookPro9,2               | [eb51cb6dcf](https://linux-hardware.org/?probe=eb51cb6dcf) | Jun 03, 2023 |
| Acer          | Aspire V3-372               | [1200863830](https://linux-hardware.org/?probe=1200863830) | Jun 03, 2023 |
| Acer          | Aspire A115-31              | [338f025bce](https://linux-hardware.org/?probe=338f025bce) | Jun 03, 2023 |
| Apple         | MacBookPro7,1               | [b1513dc005](https://linux-hardware.org/?probe=b1513dc005) | Jun 03, 2023 |
| HP            | Laptop 14-cm0xxx            | [8933e1b0ad](https://linux-hardware.org/?probe=8933e1b0ad) | Jun 03, 2023 |
| Acer          | Aspire E5-772G              | [5bd684bed6](https://linux-hardware.org/?probe=5bd684bed6) | Jun 02, 2023 |
| Acer          | Aspire E5-772G              | [f454cdf394](https://linux-hardware.org/?probe=f454cdf394) | Jun 02, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [b546b2e7f1](https://linux-hardware.org/?probe=b546b2e7f1) | Jun 02, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2a67b74a26](https://linux-hardware.org/?probe=2a67b74a26) | Jun 02, 2023 |
| Apple         | MacBookPro5,5               | [9bf36ef4a5](https://linux-hardware.org/?probe=9bf36ef4a5) | Jun 02, 2023 |
| HP            | ZBook 15 G6                 | [2f7bb21988](https://linux-hardware.org/?probe=2f7bb21988) | Jun 02, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [174ffa62e4](https://linux-hardware.org/?probe=174ffa62e4) | Jun 02, 2023 |
| Aquarius      | NS585                       | [6f93385917](https://linux-hardware.org/?probe=6f93385917) | Jun 02, 2023 |
| Dell          | Inspiron 5567               | [bd3a6c5bd8](https://linux-hardware.org/?probe=bd3a6c5bd8) | Jun 02, 2023 |
| Aquarius      | NS585                       | [091267ec3a](https://linux-hardware.org/?probe=091267ec3a) | Jun 02, 2023 |
| Aquarius      | NS585                       | [7534819f94](https://linux-hardware.org/?probe=7534819f94) | Jun 02, 2023 |
| Lenovo        | S40-70 80GQ                 | [9a3fbc7388](https://linux-hardware.org/?probe=9a3fbc7388) | Jun 02, 2023 |
| Dell          | Latitude E6430              | [b129765265](https://linux-hardware.org/?probe=b129765265) | Jun 02, 2023 |
| HP            | EliteBook 840 G6            | [81ec1cc134](https://linux-hardware.org/?probe=81ec1cc134) | Jun 01, 2023 |
| Dell          | Latitude E5510              | [4a0bc9e53f](https://linux-hardware.org/?probe=4a0bc9e53f) | Jun 01, 2023 |
| Dell          | System Inspiron N4110       | [ea09e45a4f](https://linux-hardware.org/?probe=ea09e45a4f) | Jun 01, 2023 |
| Aquarius      | NS585                       | [ffa7425b95](https://linux-hardware.org/?probe=ffa7425b95) | Jun 01, 2023 |
| Aquarius      | NS585                       | [fafcbbe90e](https://linux-hardware.org/?probe=fafcbbe90e) | Jun 01, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [ffc6b5e345](https://linux-hardware.org/?probe=ffc6b5e345) | Jun 01, 2023 |
| Dell          | Latitude E5510              | [9457826049](https://linux-hardware.org/?probe=9457826049) | Jun 01, 2023 |
| Positivo      | C500                        | [8dba4589fe](https://linux-hardware.org/?probe=8dba4589fe) | Jun 01, 2023 |
| ASUSTek       | X200LA                      | [ae3925153d](https://linux-hardware.org/?probe=ae3925153d) | May 31, 2023 |
| ASUSTek       | 1225B                       | [769a6736f1](https://linux-hardware.org/?probe=769a6736f1) | May 31, 2023 |
| Unknown       | Unknown                     | [412c6d4af8](https://linux-hardware.org/?probe=412c6d4af8) | May 31, 2023 |
| Fujitsu       | LIFEBOOK E780               | [8459f7cfee](https://linux-hardware.org/?probe=8459f7cfee) | May 31, 2023 |
| Apple         | MacBookPro16,1              | [717c7884c8](https://linux-hardware.org/?probe=717c7884c8) | May 31, 2023 |
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
| Chuwi         | HeroBook Air                | [80afc31c99](https://linux-hardware.org/?probe=80afc31c99) | May 30, 2023 |
| Lenovo        | ThinkPad T460 20FMS4LL00    | [7519448ca8](https://linux-hardware.org/?probe=7519448ca8) | May 30, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [ad3464fd76](https://linux-hardware.org/?probe=ad3464fd76) | May 30, 2023 |
| Acer          | Aspire A315-58              | [66de62e958](https://linux-hardware.org/?probe=66de62e958) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [c8e0efc288](https://linux-hardware.org/?probe=c8e0efc288) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [da399dc7cc](https://linux-hardware.org/?probe=da399dc7cc) | May 29, 2023 |
| Fujitsu       | LIFEBOOK E780               | [aac95cf765](https://linux-hardware.org/?probe=aac95cf765) | May 29, 2023 |
| Dell          | Latitude E5470              | [77d85b619e](https://linux-hardware.org/?probe=77d85b619e) | May 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [deaa4b357c](https://linux-hardware.org/?probe=deaa4b357c) | May 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [af312b5e91](https://linux-hardware.org/?probe=af312b5e91) | May 29, 2023 |
| Dell          | Latitude E6530              | [26f783c383](https://linux-hardware.org/?probe=26f783c383) | May 29, 2023 |
| HP            | EliteBook 735 G6            | [18b33e6fc7](https://linux-hardware.org/?probe=18b33e6fc7) | May 29, 2023 |
| Lenovo        | ThinkPad W530 2447GH2       | [f902d43115](https://linux-hardware.org/?probe=f902d43115) | May 29, 2023 |
| Acer          | Aspire A515-56              | [108833c92b](https://linux-hardware.org/?probe=108833c92b) | May 29, 2023 |
| Dell          | Latitude E6530              | [a47a934500](https://linux-hardware.org/?probe=a47a934500) | May 29, 2023 |
| HP            | Laptop 17-ca0xxx            | [4b53ed4ede](https://linux-hardware.org/?probe=4b53ed4ede) | May 29, 2023 |
| Dell          | Latitude 7480               | [9eb2396796](https://linux-hardware.org/?probe=9eb2396796) | May 28, 2023 |
| Lenovo        | Edge 15 80H1                | [75fdd71ca1](https://linux-hardware.org/?probe=75fdd71ca1) | May 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d5a3141562](https://linux-hardware.org/?probe=d5a3141562) | May 28, 2023 |
| HP            | EliteBook 840 G1            | [c256cd6942](https://linux-hardware.org/?probe=c256cd6942) | May 28, 2023 |
| HP            | Mini 110-3700               | [0f9528a8d2](https://linux-hardware.org/?probe=0f9528a8d2) | May 28, 2023 |
| HP            | G42                         | [7b9612a51a](https://linux-hardware.org/?probe=7b9612a51a) | May 27, 2023 |
| ASUSTek       | X550CA                      | [3ad8935a92](https://linux-hardware.org/?probe=3ad8935a92) | May 27, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [447ea38d26](https://linux-hardware.org/?probe=447ea38d26) | May 27, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [57dcd55314](https://linux-hardware.org/?probe=57dcd55314) | May 27, 2023 |
| Aquarius      | NS585                       | [a87c8d46b6](https://linux-hardware.org/?probe=a87c8d46b6) | May 27, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [9b93292db9](https://linux-hardware.org/?probe=9b93292db9) | May 26, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JU... | [0696598319](https://linux-hardware.org/?probe=0696598319) | May 26, 2023 |
| ASUSTek       | K53SV                       | [357c1fd091](https://linux-hardware.org/?probe=357c1fd091) | May 26, 2023 |
| Dell          | Latitude 3520               | [bfa8a18cb5](https://linux-hardware.org/?probe=bfa8a18cb5) | May 26, 2023 |
| Fujitsu       | FMVA42ERKS                  | [91fa73184c](https://linux-hardware.org/?probe=91fa73184c) | May 26, 2023 |
| eMachines     | E725                        | [a4be8012a8](https://linux-hardware.org/?probe=a4be8012a8) | May 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [4c3aa6334b](https://linux-hardware.org/?probe=4c3aa6334b) | May 26, 2023 |
| Acer          | Aspire A315-42              | [d229a8eb01](https://linux-hardware.org/?probe=d229a8eb01) | May 26, 2023 |
| Acer          | Aspire V3-551               | [316db578fe](https://linux-hardware.org/?probe=316db578fe) | May 25, 2023 |
| Aquarius      | NS585                       | [82a0d45251](https://linux-hardware.org/?probe=82a0d45251) | May 25, 2023 |
| Acer          | Aspire E5-575               | [45ac56e70c](https://linux-hardware.org/?probe=45ac56e70c) | May 25, 2023 |
| Dell          | Latitude 7220 Rugged Ext... | [442b7239c8](https://linux-hardware.org/?probe=442b7239c8) | May 24, 2023 |
| Dell          | Latitude E5430 non-vPro     | [278fefa10a](https://linux-hardware.org/?probe=278fefa10a) | May 24, 2023 |
| Notebook      | W54_55SU1,SUW               | [25b79c51e2](https://linux-hardware.org/?probe=25b79c51e2) | May 23, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [f8ef460648](https://linux-hardware.org/?probe=f8ef460648) | May 23, 2023 |
| HP            | 530                         | [70600de142](https://linux-hardware.org/?probe=70600de142) | May 23, 2023 |
| Dell          | Latitude E5430 non-vPro     | [6ab7e9c82d](https://linux-hardware.org/?probe=6ab7e9c82d) | May 23, 2023 |
| Acer          | Nitro AN515-45              | [d784b0822d](https://linux-hardware.org/?probe=d784b0822d) | May 22, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [44b6477648](https://linux-hardware.org/?probe=44b6477648) | May 22, 2023 |
| ASUSTek       | N56VB                       | [0e982abd6b](https://linux-hardware.org/?probe=0e982abd6b) | May 22, 2023 |
| Unknown       | Unknown                     | [2b3ef0afc4](https://linux-hardware.org/?probe=2b3ef0afc4) | May 22, 2023 |
| HP            | Laptop 15-da0xxx            | [82f235bfbb](https://linux-hardware.org/?probe=82f235bfbb) | May 22, 2023 |
| HP            | Laptop 14-dq0xxx            | [4438fdd9b2](https://linux-hardware.org/?probe=4438fdd9b2) | May 22, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [0ab3a9817b](https://linux-hardware.org/?probe=0ab3a9817b) | May 21, 2023 |
| Dell          | Inspiron 5570               | [ca85d5aafa](https://linux-hardware.org/?probe=ca85d5aafa) | May 21, 2023 |
| Lenovo        | ThinkPad T410s 2904FAG      | [742f2c09c5](https://linux-hardware.org/?probe=742f2c09c5) | May 21, 2023 |
| Terrans Fo... | AMD                         | [8087d42d0e](https://linux-hardware.org/?probe=8087d42d0e) | May 21, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [473ea193d5](https://linux-hardware.org/?probe=473ea193d5) | May 21, 2023 |
| Dell          | Inspiron 3451               | [e69cefc8da](https://linux-hardware.org/?probe=e69cefc8da) | May 21, 2023 |
| Acer          | Aspire 5253                 | [f28727e594](https://linux-hardware.org/?probe=f28727e594) | May 21, 2023 |
| Acer          | Aspire 5739G                | [23a84a79ed](https://linux-hardware.org/?probe=23a84a79ed) | May 20, 2023 |
| Lenovo        | ThinkPad W510 4391DK3       | [ac8db768ce](https://linux-hardware.org/?probe=ac8db768ce) | May 20, 2023 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | [e6e79ac2ca](https://linux-hardware.org/?probe=e6e79ac2ca) | May 20, 2023 |
| Acer          | Aspire 5739G                | [2ae6c83437](https://linux-hardware.org/?probe=2ae6c83437) | May 20, 2023 |
| Dell          | Latitude E5430 non-vPro     | [51827f5ae5](https://linux-hardware.org/?probe=51827f5ae5) | May 19, 2023 |
| Dell          | Latitude 5411               | [8929285bca](https://linux-hardware.org/?probe=8929285bca) | May 19, 2023 |
| Acer          | Aspire 5253                 | [fa328bbd9c](https://linux-hardware.org/?probe=fa328bbd9c) | May 19, 2023 |
| Avell High... | A40 LIV                     | [d1e00e62c4](https://linux-hardware.org/?probe=d1e00e62c4) | May 19, 2023 |
| Dell          | Vostro 15 3515              | [6b5bc55aeb](https://linux-hardware.org/?probe=6b5bc55aeb) | May 18, 2023 |
| Dell          | Vostro 15 3515              | [e26f4ecf2f](https://linux-hardware.org/?probe=e26f4ecf2f) | May 18, 2023 |
| Lenovo        | ThinkPad X200s 7470WUB      | [e5ad235f60](https://linux-hardware.org/?probe=e5ad235f60) | May 18, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [5d69cc1112](https://linux-hardware.org/?probe=5d69cc1112) | May 18, 2023 |
| Toshiba       | Satellite C855-22N          | [f5ccfb46ea](https://linux-hardware.org/?probe=f5ccfb46ea) | May 18, 2023 |
| Aquarius      | NS585                       | [dc2b351b40](https://linux-hardware.org/?probe=dc2b351b40) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | [0c6bb22a24](https://linux-hardware.org/?probe=0c6bb22a24) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | [e042bb19ba](https://linux-hardware.org/?probe=e042bb19ba) | May 18, 2023 |
| Acer          | Aspire A514-54              | [26dc842484](https://linux-hardware.org/?probe=26dc842484) | May 18, 2023 |
| Dell          | Latitude E7450              | [3000905b05](https://linux-hardware.org/?probe=3000905b05) | May 18, 2023 |
| Dell          | Latitude E7450              | [10f138711f](https://linux-hardware.org/?probe=10f138711f) | May 18, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [66f184855c](https://linux-hardware.org/?probe=66f184855c) | May 17, 2023 |
| Apple         | MacBookPro12,1              | [4aadc89f41](https://linux-hardware.org/?probe=4aadc89f41) | May 17, 2023 |
| Acer          | TravelMate X514-51          | [24465d2184](https://linux-hardware.org/?probe=24465d2184) | May 17, 2023 |
| Dell          | Latitude E5430 non-vPro     | [a1fb71ff2f](https://linux-hardware.org/?probe=a1fb71ff2f) | May 17, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAA... | [5e4e802b87](https://linux-hardware.org/?probe=5e4e802b87) | May 17, 2023 |
| Apple         | MacBookPro12,1              | [8aef05613d](https://linux-hardware.org/?probe=8aef05613d) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [966e89afc3](https://linux-hardware.org/?probe=966e89afc3) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [b4bd4b7d23](https://linux-hardware.org/?probe=b4bd4b7d23) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [3089c7ab46](https://linux-hardware.org/?probe=3089c7ab46) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [a587179a2f](https://linux-hardware.org/?probe=a587179a2f) | May 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [0fd753db6d](https://linux-hardware.org/?probe=0fd753db6d) | May 16, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | [0f9a26db5f](https://linux-hardware.org/?probe=0f9a26db5f) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [8ab7fe837d](https://linux-hardware.org/?probe=8ab7fe837d) | May 16, 2023 |
| Lenovo        | ThinkPad T490 20N2004JAD    | [c765eed46d](https://linux-hardware.org/?probe=c765eed46d) | May 16, 2023 |
| Dell          | Latitude 5521               | [9f671f21c1](https://linux-hardware.org/?probe=9f671f21c1) | May 16, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | [56056f7c9a](https://linux-hardware.org/?probe=56056f7c9a) | May 15, 2023 |
| Acer          | AO532h                      | [6cfe2a58cc](https://linux-hardware.org/?probe=6cfe2a58cc) | May 15, 2023 |
| Acer          | Aspire 7745G                | [c1bcc07617](https://linux-hardware.org/?probe=c1bcc07617) | May 15, 2023 |
| Acer          | Aspire 7745G                | [7b0f6f3dc2](https://linux-hardware.org/?probe=7b0f6f3dc2) | May 15, 2023 |
| Dell          | G15 5510                    | [5624d414be](https://linux-hardware.org/?probe=5624d414be) | May 15, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | [c82f72f0e2](https://linux-hardware.org/?probe=c82f72f0e2) | May 15, 2023 |
| Lenovo        | B590 20206                  | [70b604bc30](https://linux-hardware.org/?probe=70b604bc30) | May 14, 2023 |
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
| HP            | EliteBook 840 G5            | [7b8c68cfcf](https://linux-hardware.org/?probe=7b8c68cfcf) | May 13, 2023 |
| Fujitsu       | LIFEBOOK E5410              | [c62a002948](https://linux-hardware.org/?probe=c62a002948) | May 13, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [a25f9e8d93](https://linux-hardware.org/?probe=a25f9e8d93) | May 13, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [d2ba323017](https://linux-hardware.org/?probe=d2ba323017) | May 13, 2023 |
| HUAWEI        | BOHB-WAX9                   | [89747b6213](https://linux-hardware.org/?probe=89747b6213) | May 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [bf54c69e0c](https://linux-hardware.org/?probe=bf54c69e0c) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [17510fcd4f](https://linux-hardware.org/?probe=17510fcd4f) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [b9b6adb18a](https://linux-hardware.org/?probe=b9b6adb18a) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [80dc4be517](https://linux-hardware.org/?probe=80dc4be517) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [6eb320d381](https://linux-hardware.org/?probe=6eb320d381) | May 12, 2023 |
| HP            | ProBook 640 G1              | [4bbb20185b](https://linux-hardware.org/?probe=4bbb20185b) | May 12, 2023 |
| HP            | ProBook 640 G1              | [f89a68e432](https://linux-hardware.org/?probe=f89a68e432) | May 12, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E02    | [d90b0e6626](https://linux-hardware.org/?probe=d90b0e6626) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [a07acb448b](https://linux-hardware.org/?probe=a07acb448b) | May 12, 2023 |
| Lenovo        | ThinkPad X260 20F600A7MS    | [67daafed56](https://linux-hardware.org/?probe=67daafed56) | May 12, 2023 |
| HP            | ProBook 6470b               | [7f1a6e0d48](https://linux-hardware.org/?probe=7f1a6e0d48) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [f4df381f0e](https://linux-hardware.org/?probe=f4df381f0e) | May 12, 2023 |
| Lenovo        | ThinkPad T440 20B7S2SM00    | [8f6bd394c4](https://linux-hardware.org/?probe=8f6bd394c4) | May 12, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [ba177fa007](https://linux-hardware.org/?probe=ba177fa007) | May 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [9201edcfb8](https://linux-hardware.org/?probe=9201edcfb8) | May 12, 2023 |
| Toshiba       | Satellite Pro C660          | [848eedb681](https://linux-hardware.org/?probe=848eedb681) | May 12, 2023 |
| Lenovo        | ThinkPad T470 20HD0001MX    | [65b165e2f1](https://linux-hardware.org/?probe=65b165e2f1) | May 12, 2023 |
| HUAWEI        | MACHD-WXX9                  | [f5d0a04a09](https://linux-hardware.org/?probe=f5d0a04a09) | May 12, 2023 |
| Apple         | MacBook10,1                 | [d26983a399](https://linux-hardware.org/?probe=d26983a399) | May 12, 2023 |
| HP            | ProBook 450 G7              | [ba542c09f2](https://linux-hardware.org/?probe=ba542c09f2) | May 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [f02c2abaab](https://linux-hardware.org/?probe=f02c2abaab) | May 11, 2023 |
| Dell          | XPS 9315                    | [d53e7f5d92](https://linux-hardware.org/?probe=d53e7f5d92) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7d19994aa2](https://linux-hardware.org/?probe=7d19994aa2) | May 11, 2023 |
| Dell          | Precision 5520              | [5dfdbeff37](https://linux-hardware.org/?probe=5dfdbeff37) | May 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [eb6941b1b8](https://linux-hardware.org/?probe=eb6941b1b8) | May 10, 2023 |
| Dell          | XPS 15 9560                 | [b904defc14](https://linux-hardware.org/?probe=b904defc14) | May 09, 2023 |
| HP            | 250 G6 Notebook PC          | [f612c54f9c](https://linux-hardware.org/?probe=f612c54f9c) | May 09, 2023 |
| HP            | 250 G6 Notebook PC          | [9c14434a99](https://linux-hardware.org/?probe=9c14434a99) | May 09, 2023 |
| Unknown       | Unknown                     | [4a0ccb88d2](https://linux-hardware.org/?probe=4a0ccb88d2) | May 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [9b21cbbca0](https://linux-hardware.org/?probe=9b21cbbca0) | May 09, 2023 |
| Lenovo        | ThinkPad T530 2394CE2       | [d232fefed2](https://linux-hardware.org/?probe=d232fefed2) | May 09, 2023 |
| Avell High... | A40 LIV                     | [c4c4a1fe74](https://linux-hardware.org/?probe=c4c4a1fe74) | May 09, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [1f874eaf6d](https://linux-hardware.org/?probe=1f874eaf6d) | May 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [36334e327a](https://linux-hardware.org/?probe=36334e327a) | May 08, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [967e39a2d3](https://linux-hardware.org/?probe=967e39a2d3) | May 08, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYFR    | [f945ec106e](https://linux-hardware.org/?probe=f945ec106e) | May 07, 2023 |
| HP            | 255 G3                      | [d95f6211dc](https://linux-hardware.org/?probe=d95f6211dc) | May 07, 2023 |
| ASUSTek       | K73SJ                       | [13b8c8be10](https://linux-hardware.org/?probe=13b8c8be10) | May 07, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [7998abcdcd](https://linux-hardware.org/?probe=7998abcdcd) | May 07, 2023 |
| Dell          | Vostro 15-3568              | [08b1152328](https://linux-hardware.org/?probe=08b1152328) | May 07, 2023 |
| Acer          | Aspire AV15-51              | [9d7736a816](https://linux-hardware.org/?probe=9d7736a816) | May 06, 2023 |
| Lenovo        | IdeaPad Y480 20131          | [d625664bee](https://linux-hardware.org/?probe=d625664bee) | May 06, 2023 |
| Unknown       | Unknown                     | [dd406112de](https://linux-hardware.org/?probe=dd406112de) | May 06, 2023 |
| HP            | Laptop 15s-fq5xxx           | [8ce0b92713](https://linux-hardware.org/?probe=8ce0b92713) | May 06, 2023 |
| Lenovo        | Mixx-700-12ISK 80QL         | [14bc666ec3](https://linux-hardware.org/?probe=14bc666ec3) | May 06, 2023 |
| Acer          | Aspire 7741                 | [25f9d02593](https://linux-hardware.org/?probe=25f9d02593) | May 06, 2023 |
| Lenovo        | ThinkPad T410 2537CC5       | [10de9f17e1](https://linux-hardware.org/?probe=10de9f17e1) | May 06, 2023 |
| Acer          | TravelMate P215-53          | [f7c7c572e4](https://linux-hardware.org/?probe=f7c7c572e4) | May 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e0357a19f3](https://linux-hardware.org/?probe=e0357a19f3) | May 05, 2023 |
| Dell          | Inspiron 5770               | [c545869ec5](https://linux-hardware.org/?probe=c545869ec5) | May 05, 2023 |
| Lenovo        | ThinkPad T15p Gen 2i 21A... | [064df1260c](https://linux-hardware.org/?probe=064df1260c) | May 05, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [d016282342](https://linux-hardware.org/?probe=d016282342) | May 05, 2023 |
| Dell          | Latitude D630               | [0bef13413f](https://linux-hardware.org/?probe=0bef13413f) | May 05, 2023 |
| Avell High... | A40 LIV                     | [5745ae021d](https://linux-hardware.org/?probe=5745ae021d) | May 05, 2023 |
| Acer          | Aspire A515-52G             | [4f2fbcc26f](https://linux-hardware.org/?probe=4f2fbcc26f) | May 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2660b0df6d](https://linux-hardware.org/?probe=2660b0df6d) | May 04, 2023 |
| Aquarius      | NS585                       | [817d9a6b62](https://linux-hardware.org/?probe=817d9a6b62) | May 04, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [b68f20e323](https://linux-hardware.org/?probe=b68f20e323) | May 04, 2023 |
| Notebook      | W54_55SU1,SUW               | [fbcadee14f](https://linux-hardware.org/?probe=fbcadee14f) | May 03, 2023 |
| Notebook      | W54_55SU1,SUW               | [f9071ed10e](https://linux-hardware.org/?probe=f9071ed10e) | May 03, 2023 |
| Aquarius      | NS585                       | [c629501448](https://linux-hardware.org/?probe=c629501448) | May 03, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f636b7c230](https://linux-hardware.org/?probe=f636b7c230) | May 03, 2023 |
| HP            | EliteBook 640 14 inch G9... | [fc1bd7fffc](https://linux-hardware.org/?probe=fc1bd7fffc) | May 03, 2023 |
| HP            | EliteBook 640 14 inch G9... | [c8373114ef](https://linux-hardware.org/?probe=c8373114ef) | May 03, 2023 |
| Lenovo        | ThinkPad T495 20NK000XBR    | [c7ca4b1477](https://linux-hardware.org/?probe=c7ca4b1477) | May 03, 2023 |
| Lenovo        | ThinkPad T470 20HES63400    | [6628ac6681](https://linux-hardware.org/?probe=6628ac6681) | May 03, 2023 |
| HP            | Notebook                    | [c6316b5a64](https://linux-hardware.org/?probe=c6316b5a64) | May 03, 2023 |
| Dell          | Precision 7510              | [1e73564cf9](https://linux-hardware.org/?probe=1e73564cf9) | May 03, 2023 |
| MSI           | Unknown                     | [917d7a7fc9](https://linux-hardware.org/?probe=917d7a7fc9) | May 03, 2023 |
| Dell          | Latitude 5414               | [6922f7db46](https://linux-hardware.org/?probe=6922f7db46) | May 03, 2023 |
| HP            | OMEN by Laptop              | [a60578cfe2](https://linux-hardware.org/?probe=a60578cfe2) | May 02, 2023 |
| Aquarius      | NS585                       | [e6922e974c](https://linux-hardware.org/?probe=e6922e974c) | May 02, 2023 |
| Dell          | Latitude D630               | [d8ee0e7ca8](https://linux-hardware.org/?probe=d8ee0e7ca8) | May 02, 2023 |
| Toshiba       | Satellite X200              | [e1674b1234](https://linux-hardware.org/?probe=e1674b1234) | May 02, 2023 |
| Dell          | Latitude 7370               | [c984360af7](https://linux-hardware.org/?probe=c984360af7) | May 02, 2023 |
| Dell          | Latitude 7370               | [295b50d5b2](https://linux-hardware.org/?probe=295b50d5b2) | May 02, 2023 |
| MSI           | Katana GF76 12UEK           | [5af5d6aec3](https://linux-hardware.org/?probe=5af5d6aec3) | May 01, 2023 |
| AXDIA Inte... | MYBOOK 14 PRO               | [3174c98e9c](https://linux-hardware.org/?probe=3174c98e9c) | May 01, 2023 |
| Sony          | VPCF13WFX                   | [6500c354c7](https://linux-hardware.org/?probe=6500c354c7) | May 01, 2023 |
| Lenovo        | Slim 9 14IAP7 82T1          | [fe1b421c9d](https://linux-hardware.org/?probe=fe1b421c9d) | May 01, 2023 |
| Acer          | Aspire E1-571               | [e03d5ff056](https://linux-hardware.org/?probe=e03d5ff056) | Apr 30, 2023 |
| HP            | ProBook 655 G3              | [07e2cc77f8](https://linux-hardware.org/?probe=07e2cc77f8) | Apr 30, 2023 |
| HP            | ProBook 655 G3              | [638e747fb1](https://linux-hardware.org/?probe=638e747fb1) | Apr 30, 2023 |
| HP            | Compaq Mini CQ10-500        | [9a1134210f](https://linux-hardware.org/?probe=9a1134210f) | Apr 30, 2023 |
| Positivo      | Q464C                       | [8e41593bd3](https://linux-hardware.org/?probe=8e41593bd3) | Apr 30, 2023 |
| HP            | 255 G8 Notebook PC          | [7262375294](https://linux-hardware.org/?probe=7262375294) | Apr 30, 2023 |
| Dell          | Inspiron MXC061             | [2d1ab773dd](https://linux-hardware.org/?probe=2d1ab773dd) | Apr 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [0a9a85f5f0](https://linux-hardware.org/?probe=0a9a85f5f0) | Apr 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [83b10185e8](https://linux-hardware.org/?probe=83b10185e8) | Apr 29, 2023 |
| COPELION I... | QX-250 Series               | [409821566f](https://linux-hardware.org/?probe=409821566f) | Apr 29, 2023 |
| Lenovo        | ThinkPad X280 20KESBC402    | [0d5b86146e](https://linux-hardware.org/?probe=0d5b86146e) | Apr 29, 2023 |
| Aquarius      | NS585                       | [b23696ca41](https://linux-hardware.org/?probe=b23696ca41) | Apr 28, 2023 |
| Dell          | Latitude E7450              | [6afa2ff009](https://linux-hardware.org/?probe=6afa2ff009) | Apr 28, 2023 |
| Dell          | Latitude D630               | [a3c3e09675](https://linux-hardware.org/?probe=a3c3e09675) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [2474e8e580](https://linux-hardware.org/?probe=2474e8e580) | Apr 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [69d1f17b35](https://linux-hardware.org/?probe=69d1f17b35) | Apr 27, 2023 |
| ARDOR GAMI... | PD5x_7xPNP_PNR_PNN_PNT      | [e61f528ba5](https://linux-hardware.org/?probe=e61f528ba5) | Apr 27, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [2093399e21](https://linux-hardware.org/?probe=2093399e21) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [73141c5006](https://linux-hardware.org/?probe=73141c5006) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [0cb164ac2f](https://linux-hardware.org/?probe=0cb164ac2f) | Apr 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | [198fa6162e](https://linux-hardware.org/?probe=198fa6162e) | Apr 27, 2023 |
| IGEL Techn... | M340C                       | [40970f0528](https://linux-hardware.org/?probe=40970f0528) | Apr 26, 2023 |
| ARDOR GAMI... | PD5x_7xPNP_PNR_PNN_PNT      | [cec3a72c8a](https://linux-hardware.org/?probe=cec3a72c8a) | Apr 26, 2023 |
| Dell          | Latitude D630               | [850df6e76f](https://linux-hardware.org/?probe=850df6e76f) | Apr 26, 2023 |
| Google        | Terra                       | [b22deb9f09](https://linux-hardware.org/?probe=b22deb9f09) | Apr 26, 2023 |
| Dell          | Latitude E6440              | [f5cdf825fa](https://linux-hardware.org/?probe=f5cdf825fa) | Apr 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M640... | [0234325d36](https://linux-hardware.org/?probe=0234325d36) | Apr 26, 2023 |
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
| Aquarius      | NS585                       | [a0983c89d8](https://linux-hardware.org/?probe=a0983c89d8) | Apr 25, 2023 |
| Aquarius      | NS585                       | [5d9edb6ed4](https://linux-hardware.org/?probe=5d9edb6ed4) | Apr 25, 2023 |
| Aquarius      | NS585                       | [972d7f6e4a](https://linux-hardware.org/?probe=972d7f6e4a) | Apr 25, 2023 |
| Aquarius      | NS585                       | [c89bbd8bc0](https://linux-hardware.org/?probe=c89bbd8bc0) | Apr 25, 2023 |
| Aquarius      | NS585                       | [a6e5a5f3d1](https://linux-hardware.org/?probe=a6e5a5f3d1) | Apr 25, 2023 |
| Aquarius      | NS585                       | [b6dac5b058](https://linux-hardware.org/?probe=b6dac5b058) | Apr 25, 2023 |
| Aquarius      | NS585                       | [1563889dac](https://linux-hardware.org/?probe=1563889dac) | Apr 25, 2023 |
| Aquarius      | NS585                       | [9bdbad2ab7](https://linux-hardware.org/?probe=9bdbad2ab7) | Apr 25, 2023 |
| Aquarius      | NS585                       | [e30d7dde7b](https://linux-hardware.org/?probe=e30d7dde7b) | Apr 25, 2023 |
| Aquarius      | NS585                       | [68527a900f](https://linux-hardware.org/?probe=68527a900f) | Apr 25, 2023 |
| Aquarius      | NS585                       | [ce99b27fb4](https://linux-hardware.org/?probe=ce99b27fb4) | Apr 25, 2023 |
| Aquarius      | NS585                       | [fc377acae2](https://linux-hardware.org/?probe=fc377acae2) | Apr 25, 2023 |
| Aquarius      | NS585                       | [ed32f24d6e](https://linux-hardware.org/?probe=ed32f24d6e) | Apr 25, 2023 |
| Aquarius      | NS585                       | [ea60267a5b](https://linux-hardware.org/?probe=ea60267a5b) | Apr 25, 2023 |
| Aquarius      | NS585                       | [f71897bf76](https://linux-hardware.org/?probe=f71897bf76) | Apr 25, 2023 |
| Aquarius      | NS585                       | [7aa4561ca5](https://linux-hardware.org/?probe=7aa4561ca5) | Apr 25, 2023 |
| Aquarius      | NS585                       | [385ce8cd93](https://linux-hardware.org/?probe=385ce8cd93) | Apr 25, 2023 |
| Aquarius      | NS585                       | [3fc8926a1a](https://linux-hardware.org/?probe=3fc8926a1a) | Apr 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [9e6ce2eb71](https://linux-hardware.org/?probe=9e6ce2eb71) | Apr 25, 2023 |
| Aquarius      | NS585                       | [58306d0266](https://linux-hardware.org/?probe=58306d0266) | Apr 25, 2023 |
| Acer          | Aspire E5-576G              | [9ca5902786](https://linux-hardware.org/?probe=9ca5902786) | Apr 25, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [aa1b58a2a2](https://linux-hardware.org/?probe=aa1b58a2a2) | Apr 24, 2023 |
| HP            | ProBook 4520s               | [b680525b61](https://linux-hardware.org/?probe=b680525b61) | Apr 24, 2023 |
| HP            | ProBook 4520s               | [e4ce7aed55](https://linux-hardware.org/?probe=e4ce7aed55) | Apr 24, 2023 |
| Apple         | MacBookPro5,5               | [de825a326c](https://linux-hardware.org/?probe=de825a326c) | Apr 24, 2023 |
| Dell          | Inspiron 5537               | [971055139b](https://linux-hardware.org/?probe=971055139b) | Apr 24, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | [32546113c8](https://linux-hardware.org/?probe=32546113c8) | Apr 24, 2023 |
| Hampoo        | Cherry Trail CR V200        | [f3d90b0d4a](https://linux-hardware.org/?probe=f3d90b0d4a) | Apr 23, 2023 |
| HP            | 15                          | [fd68fb06af](https://linux-hardware.org/?probe=fd68fb06af) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | [45d7bd0907](https://linux-hardware.org/?probe=45d7bd0907) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | [c7367bfdff](https://linux-hardware.org/?probe=c7367bfdff) | Apr 23, 2023 |
| Acer          | Aspire E1-571G              | [0e2671ee2e](https://linux-hardware.org/?probe=0e2671ee2e) | Apr 23, 2023 |
| Toshiba       | Satellite C70D-A            | [adee59c351](https://linux-hardware.org/?probe=adee59c351) | Apr 23, 2023 |
| Toshiba       | Satellite C70D-A            | [c5c43186bc](https://linux-hardware.org/?probe=c5c43186bc) | Apr 23, 2023 |
| Dell          | G15 5520                    | [238c8f53aa](https://linux-hardware.org/?probe=238c8f53aa) | Apr 22, 2023 |
| Dell          | Latitude E6330              | [b532a9756c](https://linux-hardware.org/?probe=b532a9756c) | Apr 22, 2023 |
| Dell          | G15 5520                    | [07751c950a](https://linux-hardware.org/?probe=07751c950a) | Apr 22, 2023 |
| HP            | Laptop 15s-du3xxx           | [45af810de1](https://linux-hardware.org/?probe=45af810de1) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5f61e3a174](https://linux-hardware.org/?probe=5f61e3a174) | Apr 21, 2023 |
| Acer          | Nitro AN515-45              | [91f538e2ab](https://linux-hardware.org/?probe=91f538e2ab) | Apr 21, 2023 |
| Lenovo        | IdeaPad S510p 20298         | [8a1e6b7f32](https://linux-hardware.org/?probe=8a1e6b7f32) | Apr 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [036616c992](https://linux-hardware.org/?probe=036616c992) | Apr 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [3caa3d5076](https://linux-hardware.org/?probe=3caa3d5076) | Apr 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [8c8d2eb3b5](https://linux-hardware.org/?probe=8c8d2eb3b5) | Apr 21, 2023 |
| HP            | ZBook Power 15.6 inch G8... | [cb40e046d8](https://linux-hardware.org/?probe=cb40e046d8) | Apr 21, 2023 |
| Dell          | Precision 3550              | [7434822402](https://linux-hardware.org/?probe=7434822402) | Apr 21, 2023 |
| Toshiba       | Satellite X200              | [15035835d0](https://linux-hardware.org/?probe=15035835d0) | Apr 20, 2023 |
| Toshiba       | Satellite Pro NB10-A-125    | [3a77f344af](https://linux-hardware.org/?probe=3a77f344af) | Apr 20, 2023 |
| ASUSTek       | X550CA                      | [cb5f73ff63](https://linux-hardware.org/?probe=cb5f73ff63) | Apr 20, 2023 |
| HP            | Notebook                    | [7174065ed3](https://linux-hardware.org/?probe=7174065ed3) | Apr 20, 2023 |
| Aquarius      | NS585                       | [753222f54f](https://linux-hardware.org/?probe=753222f54f) | Apr 20, 2023 |
| Aquarius      | NS585                       | [be0bc2be01](https://linux-hardware.org/?probe=be0bc2be01) | Apr 20, 2023 |
| Acer          | Aspire E3-111               | [9af253f4e0](https://linux-hardware.org/?probe=9af253f4e0) | Apr 20, 2023 |
| HP            | EliteBook 830 G5            | [6090be709d](https://linux-hardware.org/?probe=6090be709d) | Apr 20, 2023 |
| Aquarius      | NS585                       | [f7f0464c39](https://linux-hardware.org/?probe=f7f0464c39) | Apr 20, 2023 |
| Aquarius      | NS585                       | [8393642230](https://linux-hardware.org/?probe=8393642230) | Apr 20, 2023 |
| Aquarius      | NS585                       | [a5b9a09e63](https://linux-hardware.org/?probe=a5b9a09e63) | Apr 20, 2023 |
| Medion        | P17605                      | [b68359f3d1](https://linux-hardware.org/?probe=b68359f3d1) | Apr 20, 2023 |
| HP            | Laptop 15-db0xxx            | [9ab965fcb8](https://linux-hardware.org/?probe=9ab965fcb8) | Apr 19, 2023 |
| Lenovo        | ThinkPad T500 2055WAB       | [4e293261bb](https://linux-hardware.org/?probe=4e293261bb) | Apr 19, 2023 |
| HP            | ProBook 450 G2              | [3b8c115c1a](https://linux-hardware.org/?probe=3b8c115c1a) | Apr 19, 2023 |
| Toshiba       | Satellite Pro A100          | [4240870be8](https://linux-hardware.org/?probe=4240870be8) | Apr 19, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [f691871296](https://linux-hardware.org/?probe=f691871296) | Apr 19, 2023 |
| Acer          | Swift SF314-57              | [5fc25cc033](https://linux-hardware.org/?probe=5fc25cc033) | Apr 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [d669bcc680](https://linux-hardware.org/?probe=d669bcc680) | Apr 19, 2023 |
| HP            | 255 G8 Notebook PC          | [699e2a2a80](https://linux-hardware.org/?probe=699e2a2a80) | Apr 18, 2023 |
| Tactus        | GeoBook 140                 | [704da241f5](https://linux-hardware.org/?probe=704da241f5) | Apr 18, 2023 |
| Dell          | Vostro 5402                 | [e492c87b46](https://linux-hardware.org/?probe=e492c87b46) | Apr 18, 2023 |
| Dell          | Vostro 5402                 | [b15f47258b](https://linux-hardware.org/?probe=b15f47258b) | Apr 18, 2023 |
| PC Special... | NV4XMB,ME,MZ                | [65c0a28c58](https://linux-hardware.org/?probe=65c0a28c58) | Apr 18, 2023 |
| Lenovo        | IdeaPad S510p 20298         | [7f0be1868e](https://linux-hardware.org/?probe=7f0be1868e) | Apr 18, 2023 |
| MSI           | Prestige 15 A12UC           | [0f4c1e1ac3](https://linux-hardware.org/?probe=0f4c1e1ac3) | Apr 18, 2023 |
| Toshiba       | Satellite Pro C850-1J2      | [e5c63957a2](https://linux-hardware.org/?probe=e5c63957a2) | Apr 18, 2023 |
| ASUSTek       | G551JW                      | [65f6143e36](https://linux-hardware.org/?probe=65f6143e36) | Apr 18, 2023 |
| Lenovo        | ThinkPad L540 20AUA39QJP    | [180ef53338](https://linux-hardware.org/?probe=180ef53338) | Apr 18, 2023 |
| Lenovo        | ThinkPad L540 20AUA39QJP    | [fd3b20c292](https://linux-hardware.org/?probe=fd3b20c292) | Apr 18, 2023 |
| LG Electro... | 17Z90Q-K.AA78A1             | [594a7fa16b](https://linux-hardware.org/?probe=594a7fa16b) | Apr 18, 2023 |
| IBM           | ThinkPad R51 1836Q4U        | [ebec8b53eb](https://linux-hardware.org/?probe=ebec8b53eb) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [94f62c41e5](https://linux-hardware.org/?probe=94f62c41e5) | Apr 17, 2023 |
| LG Electro... | P530-KE6BK                  | [b1f0863c79](https://linux-hardware.org/?probe=b1f0863c79) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [d5db24c28d](https://linux-hardware.org/?probe=d5db24c28d) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [89eb2b2c32](https://linux-hardware.org/?probe=89eb2b2c32) | Apr 17, 2023 |
| Dell          | Latitude 5420               | [4f3345aced](https://linux-hardware.org/?probe=4f3345aced) | Apr 16, 2023 |
| Acer          | Swift SF314-41              | [8c42a0aba8](https://linux-hardware.org/?probe=8c42a0aba8) | Apr 16, 2023 |
| Dell          | XPS 13 9305                 | [838519057f](https://linux-hardware.org/?probe=838519057f) | Apr 16, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | [d532f6fdbd](https://linux-hardware.org/?probe=d532f6fdbd) | Apr 16, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [c622c73721](https://linux-hardware.org/?probe=c622c73721) | Apr 16, 2023 |
| HP            | Notebook                    | [7614984f1d](https://linux-hardware.org/?probe=7614984f1d) | Apr 15, 2023 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [8ca60a45fe](https://linux-hardware.org/?probe=8ca60a45fe) | Apr 15, 2023 |
| HP            | EliteBook 850 G4            | [984cf8fd47](https://linux-hardware.org/?probe=984cf8fd47) | Apr 14, 2023 |
| Acer          | Aspire E5-575G              | [39afaea9e3](https://linux-hardware.org/?probe=39afaea9e3) | Apr 14, 2023 |
| HP            | Laptop 17-cp0xxx            | [6fdb6931f0](https://linux-hardware.org/?probe=6fdb6931f0) | Apr 14, 2023 |
| HP            | 255 G8 Notebook PC          | [58ec498e8f](https://linux-hardware.org/?probe=58ec498e8f) | Apr 14, 2023 |
| Acer          | Extensa 5635Z               | [b3c99bf352](https://linux-hardware.org/?probe=b3c99bf352) | Apr 14, 2023 |
| Notebook      | N7x0WU                      | [5d37070bf0](https://linux-hardware.org/?probe=5d37070bf0) | Apr 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [6af1f492c4](https://linux-hardware.org/?probe=6af1f492c4) | Apr 14, 2023 |
| Lenovo        | Flex 2-14 20404             | [c76a516113](https://linux-hardware.org/?probe=c76a516113) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | [9ab8e04a20](https://linux-hardware.org/?probe=9ab8e04a20) | Apr 14, 2023 |
| Acer          | AO756                       | [58efd2f87f](https://linux-hardware.org/?probe=58efd2f87f) | Apr 14, 2023 |
| Toshiba       | Satellite L850              | [15de4db91b](https://linux-hardware.org/?probe=15de4db91b) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | [1a327ce647](https://linux-hardware.org/?probe=1a327ce647) | Apr 13, 2023 |
| Dell          | G15 5510                    | [6b4ef54307](https://linux-hardware.org/?probe=6b4ef54307) | Apr 13, 2023 |
| Dell          | Inspiron 1525               | [bc3ccff50c](https://linux-hardware.org/?probe=bc3ccff50c) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [60f7db51fa](https://linux-hardware.org/?probe=60f7db51fa) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e9708d65e9](https://linux-hardware.org/?probe=e9708d65e9) | Apr 13, 2023 |
| Acer          | Aspire A315-51              | [c3962286cb](https://linux-hardware.org/?probe=c3962286cb) | Apr 13, 2023 |
| Apple         | MacBookPro5,5               | [401c4d8143](https://linux-hardware.org/?probe=401c4d8143) | Apr 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | [abedf2741f](https://linux-hardware.org/?probe=abedf2741f) | Apr 12, 2023 |
| HP            | ZBook 15 G3                 | [5411d789c3](https://linux-hardware.org/?probe=5411d789c3) | Apr 12, 2023 |
| Dell          | Latitude 5490               | [38ebdedf58](https://linux-hardware.org/?probe=38ebdedf58) | Apr 12, 2023 |
| HP            | Pavilion dv6                | [09b80dd551](https://linux-hardware.org/?probe=09b80dd551) | Apr 12, 2023 |
| HP            | Pavilion dv7                | [4363479bf0](https://linux-hardware.org/?probe=4363479bf0) | Apr 12, 2023 |
| Dell          | Inspiron 15-3567            | [23c158b19b](https://linux-hardware.org/?probe=23c158b19b) | Apr 12, 2023 |
| Lenovo        | ThinkPad E470 20H2S00700    | [ea2aa5245d](https://linux-hardware.org/?probe=ea2aa5245d) | Apr 11, 2023 |
| Samsung       | 550XCJ/550XCR               | [c074d665d9](https://linux-hardware.org/?probe=c074d665d9) | Apr 11, 2023 |
| Samsung       | 550XCJ/550XCR               | [845a04c326](https://linux-hardware.org/?probe=845a04c326) | Apr 11, 2023 |
| Packard Be... | EasyNote_MX45               | [95935443c0](https://linux-hardware.org/?probe=95935443c0) | Apr 11, 2023 |
| ASUSTek       | X550JF                      | [dff4654bd2](https://linux-hardware.org/?probe=dff4654bd2) | Apr 11, 2023 |
| Acer          | Aspire E1-571G              | [45a3503764](https://linux-hardware.org/?probe=45a3503764) | Apr 11, 2023 |
| Acer          | Aspire 5738                 | [c039220e20](https://linux-hardware.org/?probe=c039220e20) | Apr 11, 2023 |
| Aquarius      | NS585                       | [6f4b987640](https://linux-hardware.org/?probe=6f4b987640) | Apr 11, 2023 |
| Samsung       | 550XDA                      | [e1d5d2f193](https://linux-hardware.org/?probe=e1d5d2f193) | Apr 11, 2023 |
| Dell          | Inspiron 15 5510            | [5d84a5a711](https://linux-hardware.org/?probe=5d84a5a711) | Apr 10, 2023 |
| Apple         | MacBookAir7,2               | [94efe20a0f](https://linux-hardware.org/?probe=94efe20a0f) | Apr 10, 2023 |
| Dell          | Latitude 3320               | [b7c2bb88b3](https://linux-hardware.org/?probe=b7c2bb88b3) | Apr 10, 2023 |
| Dell          | Latitude 3320               | [436e7b8903](https://linux-hardware.org/?probe=436e7b8903) | Apr 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S0CE1M    | [eb794b0dc7](https://linux-hardware.org/?probe=eb794b0dc7) | Apr 10, 2023 |
| Lenovo        | ThinkPad L470 20J4000LGE    | [fec574fe0d](https://linux-hardware.org/?probe=fec574fe0d) | Apr 10, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | [885fff9ddb](https://linux-hardware.org/?probe=885fff9ddb) | Apr 10, 2023 |
| Lenovo        | ThinkPad L470 20J4000LGE    | [f97c4e6d47](https://linux-hardware.org/?probe=f97c4e6d47) | Apr 10, 2023 |
| Samsung       | RF511/RF411/RF711           | [ea4fdd80e6](https://linux-hardware.org/?probe=ea4fdd80e6) | Apr 09, 2023 |
| Lenovo        | ThinkPad X220 4291LR6       | [ea86227d59](https://linux-hardware.org/?probe=ea86227d59) | Apr 09, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [8d4288ca33](https://linux-hardware.org/?probe=8d4288ca33) | Apr 09, 2023 |
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
| eMachines     | eME728                      | [aff08e7f2d](https://linux-hardware.org/?probe=aff08e7f2d) | Apr 05, 2023 |
| eMachines     | eMachiens G443              | [58c297218a](https://linux-hardware.org/?probe=58c297218a) | Apr 05, 2023 |
| Toshiba       | Satellite C855D-12J         | [cb3dedf5e8](https://linux-hardware.org/?probe=cb3dedf5e8) | Apr 05, 2023 |
| System76      | Lemur Pro                   | [2232424d5a](https://linux-hardware.org/?probe=2232424d5a) | Apr 05, 2023 |
| Acer          | Aspire E1-532               | [ba90a2c123](https://linux-hardware.org/?probe=ba90a2c123) | Apr 05, 2023 |
| Dell          | Precision M4700             | [1e2be52d80](https://linux-hardware.org/?probe=1e2be52d80) | Apr 05, 2023 |
| HONOR         | NMH-WCX9                    | [9ea45909a2](https://linux-hardware.org/?probe=9ea45909a2) | Apr 05, 2023 |
| Acer          | TravelMate P215-53          | [0808bd0d17](https://linux-hardware.org/?probe=0808bd0d17) | Apr 04, 2023 |
| Apple         | MacBookPro10,2              | [ad5d8f611a](https://linux-hardware.org/?probe=ad5d8f611a) | Apr 04, 2023 |
| Dell          | Latitude 5430               | [6494113c9b](https://linux-hardware.org/?probe=6494113c9b) | Apr 04, 2023 |
| Framework     | Laptop                      | [5bb187865d](https://linux-hardware.org/?probe=5bb187865d) | Apr 04, 2023 |
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
| Packard Be... | EasyNote TJ65               | [cd6a05149d](https://linux-hardware.org/?probe=cd6a05149d) | Apr 02, 2023 |
| Acer          | TravelMate P215-53          | [bd1d2b4102](https://linux-hardware.org/?probe=bd1d2b4102) | Apr 02, 2023 |
| Google        | Snappy                      | [16dda325bf](https://linux-hardware.org/?probe=16dda325bf) | Apr 02, 2023 |
| Dell          | Precision 5540              | [f25b25b590](https://linux-hardware.org/?probe=f25b25b590) | Apr 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | [2f2326e574](https://linux-hardware.org/?probe=2f2326e574) | Apr 02, 2023 |
| Schenker      | XMG CORE (REN/M20)          | [50e9dee7b1](https://linux-hardware.org/?probe=50e9dee7b1) | Apr 01, 2023 |
| HP            | Notebook                    | [348d80772f](https://linux-hardware.org/?probe=348d80772f) | Apr 01, 2023 |
| HP            | EliteBook 840 G5            | [3c509a7075](https://linux-hardware.org/?probe=3c509a7075) | Apr 01, 2023 |
| Tactus        | GeoBook 140                 | [0ceb5a3b7c](https://linux-hardware.org/?probe=0ceb5a3b7c) | Apr 01, 2023 |
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
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [a9e7ad7ecd](https://linux-hardware.org/?probe=a9e7ad7ecd) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | [fc06b01f31](https://linux-hardware.org/?probe=fc06b01f31) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | [5ac693dbd4](https://linux-hardware.org/?probe=5ac693dbd4) | Mar 29, 2023 |
| Acer          | Nitro AN515-43              | [47c758c261](https://linux-hardware.org/?probe=47c758c261) | Mar 29, 2023 |
| Unknown       | Unknown                     | [7d3374d52b](https://linux-hardware.org/?probe=7d3374d52b) | Mar 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [77e01c9b12](https://linux-hardware.org/?probe=77e01c9b12) | Mar 29, 2023 |
| Lenovo        | G50-45 80E3                 | [7bfed0aedd](https://linux-hardware.org/?probe=7bfed0aedd) | Mar 29, 2023 |
| Acer          | Aspire A315-23G             | [5c6734f5e6](https://linux-hardware.org/?probe=5c6734f5e6) | Mar 29, 2023 |
| Medion        | P7641 MD99856               | [7347a28d53](https://linux-hardware.org/?probe=7347a28d53) | Mar 28, 2023 |
| HP            | Pavilion dv5000 (EW771EA... | [db28f35ce0](https://linux-hardware.org/?probe=db28f35ce0) | Mar 28, 2023 |
| Acer          | Aspire V3-571G              | [289bd8c2fd](https://linux-hardware.org/?probe=289bd8c2fd) | Mar 28, 2023 |
| THUNDEROBO... | 911 Plus                    | [6617ad47b7](https://linux-hardware.org/?probe=6617ad47b7) | Mar 28, 2023 |
| Google        | Swanky                      | [0f32e48b38](https://linux-hardware.org/?probe=0f32e48b38) | Mar 28, 2023 |
| ASUSTek       | X541SA                      | [f281edd494](https://linux-hardware.org/?probe=f281edd494) | Mar 28, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B9C... | [0744b26f5c](https://linux-hardware.org/?probe=0744b26f5c) | Mar 27, 2023 |
| HP            | EliteBook 840 G3            | [58d5e99cd1](https://linux-hardware.org/?probe=58d5e99cd1) | Mar 27, 2023 |
| GPD           | P3 MAX                      | [b3627909f1](https://linux-hardware.org/?probe=b3627909f1) | Mar 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | [17794caffa](https://linux-hardware.org/?probe=17794caffa) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [9fd0ee0183](https://linux-hardware.org/?probe=9fd0ee0183) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [d0f84e1bd4](https://linux-hardware.org/?probe=d0f84e1bd4) | Mar 27, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [7cd7234999](https://linux-hardware.org/?probe=7cd7234999) | Mar 27, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [dd84425bc7](https://linux-hardware.org/?probe=dd84425bc7) | Mar 27, 2023 |
| Lenovo        | G50-45 80E3                 | [279d3659a9](https://linux-hardware.org/?probe=279d3659a9) | Mar 26, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [d1f406ffe7](https://linux-hardware.org/?probe=d1f406ffe7) | Mar 26, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [2d83ebd124](https://linux-hardware.org/?probe=2d83ebd124) | Mar 26, 2023 |
| Acer          | Nitro AN515-52              | [d2f95decbe](https://linux-hardware.org/?probe=d2f95decbe) | Mar 26, 2023 |
| Dell          | Precision 5570              | [454590a1a8](https://linux-hardware.org/?probe=454590a1a8) | Mar 26, 2023 |
| Acer          | Nitro AN515-52              | [1377a2ea15](https://linux-hardware.org/?probe=1377a2ea15) | Mar 26, 2023 |
| Dell          | Latitude E6330              | [32833b4683](https://linux-hardware.org/?probe=32833b4683) | Mar 25, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0C40... | [39b2a59543](https://linux-hardware.org/?probe=39b2a59543) | Mar 25, 2023 |
| HUAWEI        | NBD-WXX9                    | [7eb3d40bd8](https://linux-hardware.org/?probe=7eb3d40bd8) | Mar 25, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [9b9a21b7da](https://linux-hardware.org/?probe=9b9a21b7da) | Mar 24, 2023 |
| Packard Be... | H17HV                       | [c4bddccbd8](https://linux-hardware.org/?probe=c4bddccbd8) | Mar 24, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [58f8d5849a](https://linux-hardware.org/?probe=58f8d5849a) | Mar 24, 2023 |
| Lenovo        | Z50-75 80EC                 | [d6783c57a6](https://linux-hardware.org/?probe=d6783c57a6) | Mar 24, 2023 |
| Lenovo        | Z50-75 80EC                 | [353666c217](https://linux-hardware.org/?probe=353666c217) | Mar 24, 2023 |
| Dell          | Inspiron 7348               | [4011322039](https://linux-hardware.org/?probe=4011322039) | Mar 24, 2023 |
| Toshiba       | Satellite C50-B             | [4b563f19dd](https://linux-hardware.org/?probe=4b563f19dd) | Mar 24, 2023 |
| HP            | EliteBook 850 G5            | [cde421908c](https://linux-hardware.org/?probe=cde421908c) | Mar 24, 2023 |
| Sony          | SVE1512M6ESI                | [db00c70eb7](https://linux-hardware.org/?probe=db00c70eb7) | Mar 24, 2023 |
| ASUSTek       | N56VJ                       | [da2c5d6ff1](https://linux-hardware.org/?probe=da2c5d6ff1) | Mar 24, 2023 |
| Dell          | Inspiron 15 3511            | [7aa41dd248](https://linux-hardware.org/?probe=7aa41dd248) | Mar 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [32a4fc1880](https://linux-hardware.org/?probe=32a4fc1880) | Mar 23, 2023 |
| Acer          | Aspire VN7-791              | [054efde4e8](https://linux-hardware.org/?probe=054efde4e8) | Mar 22, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [5e97d4fdf3](https://linux-hardware.org/?probe=5e97d4fdf3) | Mar 22, 2023 |
| Apple         | MacBookPro11,2              | [92208949d5](https://linux-hardware.org/?probe=92208949d5) | Mar 22, 2023 |
| Apple         | MacBookPro11,2              | [aa71c25dba](https://linux-hardware.org/?probe=aa71c25dba) | Mar 22, 2023 |
| Unknown       | Unknown                     | [ef5bf53c45](https://linux-hardware.org/?probe=ef5bf53c45) | Mar 22, 2023 |
| Dell          | G3 3579                     | [b6f8dd5ffe](https://linux-hardware.org/?probe=b6f8dd5ffe) | Mar 22, 2023 |
| Unknown       | Unknown                     | [b96104604a](https://linux-hardware.org/?probe=b96104604a) | Mar 22, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [1f5d2a057c](https://linux-hardware.org/?probe=1f5d2a057c) | Mar 22, 2023 |
| Lenovo        | ThinkPad T440 20B7S3N304    | [af39e826be](https://linux-hardware.org/?probe=af39e826be) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [de7c628210](https://linux-hardware.org/?probe=de7c628210) | Mar 22, 2023 |
| Apple         | MacBookPro5,5               | [849f9d23c7](https://linux-hardware.org/?probe=849f9d23c7) | Mar 21, 2023 |
| Lenovo        | ThinkPad X230s 20AHS0070... | [9d86eaf558](https://linux-hardware.org/?probe=9d86eaf558) | Mar 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [4c7add7cd1](https://linux-hardware.org/?probe=4c7add7cd1) | Mar 21, 2023 |
| Dell          | Inspiron 5570               | [e311e9a53a](https://linux-hardware.org/?probe=e311e9a53a) | Mar 21, 2023 |
| HP            | EliteBook 850 G5            | [5ca3a1b044](https://linux-hardware.org/?probe=5ca3a1b044) | Mar 21, 2023 |
| Lenovo        | G570 20079                  | [8657b8d645](https://linux-hardware.org/?probe=8657b8d645) | Mar 21, 2023 |
| ASUSTek       | S551LB                      | [da9a9373a6](https://linux-hardware.org/?probe=da9a9373a6) | Mar 20, 2023 |
| Toshiba       | Satellite C50-B             | [b9bf22cc53](https://linux-hardware.org/?probe=b9bf22cc53) | Mar 20, 2023 |
| Dell          | Latitude E6420              | [e564f25125](https://linux-hardware.org/?probe=e564f25125) | Mar 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [7bc035af43](https://linux-hardware.org/?probe=7bc035af43) | Mar 20, 2023 |
| Fujitsu       | LIFEBOOK E734               | [0c4119f8b3](https://linux-hardware.org/?probe=0c4119f8b3) | Mar 20, 2023 |
| Samsung       | RF511/RF411/RF711           | [bff0b1d8a4](https://linux-hardware.org/?probe=bff0b1d8a4) | Mar 20, 2023 |
| Dell          | Latitude 7480               | [00d8228ec6](https://linux-hardware.org/?probe=00d8228ec6) | Mar 20, 2023 |
| Dell          | G3 3590                     | [cba689e7f5](https://linux-hardware.org/?probe=cba689e7f5) | Mar 20, 2023 |
| ASUSTek       | ZenBook 13 UX331UAL         | [9d44bf5769](https://linux-hardware.org/?probe=9d44bf5769) | Mar 20, 2023 |
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
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [d58b6cfe61](https://linux-hardware.org/?probe=d58b6cfe61) | Mar 18, 2023 |
| HP            | ProBook 470 G3              | [3cdb0bbdf6](https://linux-hardware.org/?probe=3cdb0bbdf6) | Mar 17, 2023 |
| Aquarius      | NS585                       | [cd1e92458f](https://linux-hardware.org/?probe=cd1e92458f) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [2020cf3584](https://linux-hardware.org/?probe=2020cf3584) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [e7ebc0ec0e](https://linux-hardware.org/?probe=e7ebc0ec0e) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [c343e79a84](https://linux-hardware.org/?probe=c343e79a84) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [5391c84cf4](https://linux-hardware.org/?probe=5391c84cf4) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [8fcb466fab](https://linux-hardware.org/?probe=8fcb466fab) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [7aa3efb2fd](https://linux-hardware.org/?probe=7aa3efb2fd) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [8319fcb9da](https://linux-hardware.org/?probe=8319fcb9da) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [6bf9694348](https://linux-hardware.org/?probe=6bf9694348) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [c3c0ef4a31](https://linux-hardware.org/?probe=c3c0ef4a31) | Mar 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [66f4a76724](https://linux-hardware.org/?probe=66f4a76724) | Mar 17, 2023 |
| HP            | 255 G3                      | [3e5f860704](https://linux-hardware.org/?probe=3e5f860704) | Mar 17, 2023 |
| Samsung       | RF511/RF411/RF711           | [ecb08b3c5e](https://linux-hardware.org/?probe=ecb08b3c5e) | Mar 17, 2023 |
| Dell          | Latitude 7480               | [ee6015f962](https://linux-hardware.org/?probe=ee6015f962) | Mar 17, 2023 |
| MSI           | GF72 8RE                    | [4610dffdcc](https://linux-hardware.org/?probe=4610dffdcc) | Mar 17, 2023 |
| HP            | Notebook                    | [e901631805](https://linux-hardware.org/?probe=e901631805) | Mar 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [b50b834744](https://linux-hardware.org/?probe=b50b834744) | Mar 16, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f3ee556fb5](https://linux-hardware.org/?probe=f3ee556fb5) | Mar 16, 2023 |
| Dell          | Precision M6800             | [db62a370ed](https://linux-hardware.org/?probe=db62a370ed) | Mar 16, 2023 |
| HP            | EliteBook 8460p             | [e8d00684ac](https://linux-hardware.org/?probe=e8d00684ac) | Mar 16, 2023 |
| PC Special... | P65_67RSRP                  | [71a45943c1](https://linux-hardware.org/?probe=71a45943c1) | Mar 16, 2023 |
| HP            | EliteBook 840 G6            | [57f2de5da4](https://linux-hardware.org/?probe=57f2de5da4) | Mar 16, 2023 |
| HP            | EliteBook 840 G6            | [2a316e6d03](https://linux-hardware.org/?probe=2a316e6d03) | Mar 16, 2023 |
| HP            | EliteBook 830 G5            | [c6aa050dd1](https://linux-hardware.org/?probe=c6aa050dd1) | Mar 16, 2023 |
| Dell          | Latitude 7480               | [72069037ca](https://linux-hardware.org/?probe=72069037ca) | Mar 16, 2023 |
| HP            | ProBook 430 G8 Notebook ... | [ca6ab3c197](https://linux-hardware.org/?probe=ca6ab3c197) | Mar 16, 2023 |
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
| TUXEDO        | Aura 15 Gen2                | [15d4cdae49](https://linux-hardware.org/?probe=15d4cdae49) | Mar 14, 2023 |
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
| Acer          | Aspire E5-551G              | [7a992ff109](https://linux-hardware.org/?probe=7a992ff109) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [d9d4f5649a](https://linux-hardware.org/?probe=d9d4f5649a) | Mar 14, 2023 |
| Schenker      | VIA 15 Pro                  | [ef02f8156e](https://linux-hardware.org/?probe=ef02f8156e) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [5c4b7a9754](https://linux-hardware.org/?probe=5c4b7a9754) | Mar 13, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [6c76af84cb](https://linux-hardware.org/?probe=6c76af84cb) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [481073d13f](https://linux-hardware.org/?probe=481073d13f) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [497a7bdef5](https://linux-hardware.org/?probe=497a7bdef5) | Mar 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cc878090ee](https://linux-hardware.org/?probe=cc878090ee) | Mar 13, 2023 |
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
| Lenovo        | Yoga 2 Pro 20266            | [f762c7cc29](https://linux-hardware.org/?probe=f762c7cc29) | Mar 13, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [9841e70d67](https://linux-hardware.org/?probe=9841e70d67) | Mar 13, 2023 |
| Acer          | Aspire 5738                 | [bd231fbff6](https://linux-hardware.org/?probe=bd231fbff6) | Mar 12, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [fd6d58db15](https://linux-hardware.org/?probe=fd6d58db15) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [fc75288cce](https://linux-hardware.org/?probe=fc75288cce) | Mar 12, 2023 |
| HP            | ZBook 17 G3                 | [f69ef4ff89](https://linux-hardware.org/?probe=f69ef4ff89) | Mar 12, 2023 |
| Lenovo        | ThinkPad X131e 3367AG9      | [0ff86711d1](https://linux-hardware.org/?probe=0ff86711d1) | Mar 12, 2023 |
| Dell          | Latitude 3510               | [13ed29770d](https://linux-hardware.org/?probe=13ed29770d) | Mar 12, 2023 |
| Dell          | Inspiron 5593               | [631b554e46](https://linux-hardware.org/?probe=631b554e46) | Mar 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [55a73e2e07](https://linux-hardware.org/?probe=55a73e2e07) | Mar 12, 2023 |
| HP            | ProBook 4415s               | [8b974a2717](https://linux-hardware.org/?probe=8b974a2717) | Mar 12, 2023 |
| HP            | Pavilion Notebook           | [158d246d65](https://linux-hardware.org/?probe=158d246d65) | Mar 11, 2023 |
| Dell          | Precision 5570              | [470ba58973](https://linux-hardware.org/?probe=470ba58973) | Mar 11, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | [f066472937](https://linux-hardware.org/?probe=f066472937) | Mar 11, 2023 |
| Dell          | Latitude E6430              | [080ad6aa2a](https://linux-hardware.org/?probe=080ad6aa2a) | Mar 11, 2023 |
| Acer          | Swift SF314-43              | [dc1a94966b](https://linux-hardware.org/?probe=dc1a94966b) | Mar 11, 2023 |
| Dell          | Latitude 3320               | [2a58a07005](https://linux-hardware.org/?probe=2a58a07005) | Mar 11, 2023 |
| Dell          | Latitude 3320               | [d17364c0ef](https://linux-hardware.org/?probe=d17364c0ef) | Mar 11, 2023 |
| Dell          | XPS 13 9310                 | [c528b16696](https://linux-hardware.org/?probe=c528b16696) | Mar 10, 2023 |
| System76      | Gazelle Professional        | [42f5755b1d](https://linux-hardware.org/?probe=42f5755b1d) | Mar 10, 2023 |
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
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [276ce8bd7c](https://linux-hardware.org/?probe=276ce8bd7c) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3daf833362](https://linux-hardware.org/?probe=3daf833362) | Mar 09, 2023 |
| HP            | Compaq nx9420 (ES446EA#A... | [b876c92a6e](https://linux-hardware.org/?probe=b876c92a6e) | Mar 09, 2023 |
| Dell          | Latitude E6440              | [b00f44cd46](https://linux-hardware.org/?probe=b00f44cd46) | Mar 09, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [5bc1f5d6d8](https://linux-hardware.org/?probe=5bc1f5d6d8) | Mar 09, 2023 |
| Dell          | Latitude E6440              | [3b9229e07a](https://linux-hardware.org/?probe=3b9229e07a) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK U7312              | [74bbf2c865](https://linux-hardware.org/?probe=74bbf2c865) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7f3075e65e](https://linux-hardware.org/?probe=7f3075e65e) | Mar 08, 2023 |
| Medion        | E122X                       | [dad02f1ac7](https://linux-hardware.org/?probe=dad02f1ac7) | Mar 08, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [07f425d57f](https://linux-hardware.org/?probe=07f425d57f) | Mar 08, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f62ef69dcc](https://linux-hardware.org/?probe=f62ef69dcc) | Mar 08, 2023 |
| Dell          | Precision 3560              | [0873d45206](https://linux-hardware.org/?probe=0873d45206) | Mar 08, 2023 |
| HP            | ZBook Studio G3             | [d059dad473](https://linux-hardware.org/?probe=d059dad473) | Mar 08, 2023 |
| Dell          | XPS 15 9570                 | [fc0152a6de](https://linux-hardware.org/?probe=fc0152a6de) | Mar 08, 2023 |
| Acer          | Nitro AN515-43              | [32d1af5dee](https://linux-hardware.org/?probe=32d1af5dee) | Mar 07, 2023 |
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
| ASUSTek       | VivoBook_ASUSLaptop X150... | [ac92e5ce13](https://linux-hardware.org/?probe=ac92e5ce13) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [92f8093adb](https://linux-hardware.org/?probe=92f8093adb) | Mar 07, 2023 |
| HP            | ZBook 15 G3                 | [b00f87c99b](https://linux-hardware.org/?probe=b00f87c99b) | Mar 06, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [119a07048d](https://linux-hardware.org/?probe=119a07048d) | Mar 06, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | [cee8496315](https://linux-hardware.org/?probe=cee8496315) | Mar 06, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [91db409270](https://linux-hardware.org/?probe=91db409270) | Mar 06, 2023 |
| ASUSTek       | X550JX                      | [a9a82b2395](https://linux-hardware.org/?probe=a9a82b2395) | Mar 06, 2023 |
| Fujitsu       | LIFEBOOK U9312              | [19a72f502b](https://linux-hardware.org/?probe=19a72f502b) | Mar 06, 2023 |
| MSI           | Modern 15 A5M               | [7d708fea96](https://linux-hardware.org/?probe=7d708fea96) | Mar 06, 2023 |
| HUAWEI        | BOHB-WAX9                   | [eb5b9b8cb9](https://linux-hardware.org/?probe=eb5b9b8cb9) | Mar 06, 2023 |
| Acer          | Aspire E1-571               | [2194ce4568](https://linux-hardware.org/?probe=2194ce4568) | Mar 06, 2023 |
| MSI           | PS42 8RB                    | [57231416e1](https://linux-hardware.org/?probe=57231416e1) | Mar 06, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [fc381c78e7](https://linux-hardware.org/?probe=fc381c78e7) | Mar 05, 2023 |
| Apple         | MacBookPro6,2               | [308b516329](https://linux-hardware.org/?probe=308b516329) | Mar 05, 2023 |
| Lenovo        | ThinkPad T440p 20AWS37F0... | [48677f9f86](https://linux-hardware.org/?probe=48677f9f86) | Mar 05, 2023 |
| Toshiba       | Satellite A200              | [b9677c823b](https://linux-hardware.org/?probe=b9677c823b) | Mar 05, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [ca566e314e](https://linux-hardware.org/?probe=ca566e314e) | Mar 05, 2023 |
| Acer          | Aspire A315-54              | [cadbbe841e](https://linux-hardware.org/?probe=cadbbe841e) | Mar 05, 2023 |
| Dell          | G5 5500                     | [7da5494dea](https://linux-hardware.org/?probe=7da5494dea) | Mar 05, 2023 |
| HP            | G42                         | [7dee433139](https://linux-hardware.org/?probe=7dee433139) | Mar 05, 2023 |
| Toshiba       | Satellite A200              | [47f08e4094](https://linux-hardware.org/?probe=47f08e4094) | Mar 04, 2023 |
| HP            | EliteBook 840 G3            | [14211fd55f](https://linux-hardware.org/?probe=14211fd55f) | Mar 04, 2023 |
| Dell          | Latitude E5450              | [2f16482775](https://linux-hardware.org/?probe=2f16482775) | Mar 04, 2023 |
| Intel         | powered classmate PC        | [bfd724fd2f](https://linux-hardware.org/?probe=bfd724fd2f) | Mar 04, 2023 |
| SANTECH       | NHx0DB,DE                   | [9ebc94ec48](https://linux-hardware.org/?probe=9ebc94ec48) | Mar 04, 2023 |
| Dell          | Vostro 3700                 | [ea14c47abb](https://linux-hardware.org/?probe=ea14c47abb) | Mar 04, 2023 |
| HP            | EliteBook 830 G5            | [82acbe37f7](https://linux-hardware.org/?probe=82acbe37f7) | Mar 04, 2023 |
| Dell          | Inspiron 3593               | [4e2f59d17e](https://linux-hardware.org/?probe=4e2f59d17e) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | [1bfad93a1e](https://linux-hardware.org/?probe=1bfad93a1e) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | [f782f8e288](https://linux-hardware.org/?probe=f782f8e288) | Mar 04, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c4def038d9](https://linux-hardware.org/?probe=c4def038d9) | Mar 04, 2023 |
| Dell          | XPS 15 9520                 | [1bef11c91d](https://linux-hardware.org/?probe=1bef11c91d) | Mar 04, 2023 |
| Lenovo        | ThinkPad X220 429035U       | [83266c1006](https://linux-hardware.org/?probe=83266c1006) | Mar 04, 2023 |
| HP            | Laptop 14s-dq1xxx           | [29fa7c0b23](https://linux-hardware.org/?probe=29fa7c0b23) | Mar 04, 2023 |
| HP            | 255 G8 Notebook PC          | [7dc484b236](https://linux-hardware.org/?probe=7dc484b236) | Mar 03, 2023 |
| HP            | 255 G8 Notebook PC          | [b7e4822b00](https://linux-hardware.org/?probe=b7e4822b00) | Mar 03, 2023 |
| Notebook      | NS5x_NS7xPU                 | [55ca2f6ac5](https://linux-hardware.org/?probe=55ca2f6ac5) | Mar 03, 2023 |
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
| HP            | Laptop 17-bs0xx             | [e055e73b69](https://linux-hardware.org/?probe=e055e73b69) | Mar 02, 2023 |
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
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [e56350a1c1](https://linux-hardware.org/?probe=e56350a1c1) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [3fa4d926e0](https://linux-hardware.org/?probe=3fa4d926e0) | Feb 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | [b4bfab8974](https://linux-hardware.org/?probe=b4bfab8974) | Feb 28, 2023 |
| HP            | ProBook 6570b               | [3692011e3f](https://linux-hardware.org/?probe=3692011e3f) | Feb 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [83a611b1ab](https://linux-hardware.org/?probe=83a611b1ab) | Feb 27, 2023 |
| ASUSTek       | UX31A                       | [56654a2659](https://linux-hardware.org/?probe=56654a2659) | Feb 27, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [ccac327e17](https://linux-hardware.org/?probe=ccac327e17) | Feb 27, 2023 |
| Dell          | Latitude 5400               | [b788c61c95](https://linux-hardware.org/?probe=b788c61c95) | Feb 27, 2023 |
| Dell          | Latitude 3510               | [de938c4962](https://linux-hardware.org/?probe=de938c4962) | Feb 27, 2023 |
| ASUSTek       | K52F                        | [fa30ea101a](https://linux-hardware.org/?probe=fa30ea101a) | Feb 27, 2023 |
| Dell          | G3 3590                     | [eb9009fad9](https://linux-hardware.org/?probe=eb9009fad9) | Feb 27, 2023 |
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
| ASUSTek       | Zenbook UX535QE_UM535QE     | [7d7953a826](https://linux-hardware.org/?probe=7d7953a826) | Feb 26, 2023 |
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
| Lenovo        | ThinkPad T440s 20AQ009DG... | [27e2d41750](https://linux-hardware.org/?probe=27e2d41750) | Feb 24, 2023 |
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
| Shanghai Z... | ZXE CRB                     | [478a4b921f](https://linux-hardware.org/?probe=478a4b921f) | Feb 24, 2023 |
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
| Dell          | Latitude 7530               | [4844568edb](https://linux-hardware.org/?probe=4844568edb) | Feb 21, 2023 |
| ASUSTek       | X556UQ                      | [8f645fa6fc](https://linux-hardware.org/?probe=8f645fa6fc) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470 20HDS1DL03    | [25e1a3f801](https://linux-hardware.org/?probe=25e1a3f801) | Feb 21, 2023 |
| Dell          | Inspiron 3468               | [e5977ee094](https://linux-hardware.org/?probe=e5977ee094) | Feb 21, 2023 |
| Dell          | Latitude E6430              | [80c9785ef0](https://linux-hardware.org/?probe=80c9785ef0) | Feb 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | [1c0772ccd7](https://linux-hardware.org/?probe=1c0772ccd7) | Feb 21, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [6ab7953740](https://linux-hardware.org/?probe=6ab7953740) | Feb 20, 2023 |
| Notebook      | PB50_70RF,RD,RC             | [b24f005b1d](https://linux-hardware.org/?probe=b24f005b1d) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | [19d29283ed](https://linux-hardware.org/?probe=19d29283ed) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | [8d1bb46519](https://linux-hardware.org/?probe=8d1bb46519) | Feb 20, 2023 |
| Acer          | Extensa 2520G               | [823c5829a9](https://linux-hardware.org/?probe=823c5829a9) | Feb 20, 2023 |
| HP            | EliteBook 830 G5            | [0cb773d407](https://linux-hardware.org/?probe=0cb773d407) | Feb 20, 2023 |
| Lenovo        | ThinkPad T430 2349PZG       | [7bd3c5a555](https://linux-hardware.org/?probe=7bd3c5a555) | Feb 20, 2023 |
| Acer          | Aspire V5-573G              | [376b35f5b6](https://linux-hardware.org/?probe=376b35f5b6) | Feb 20, 2023 |
| Dell          | Latitude E7270              | [4eb17c846c](https://linux-hardware.org/?probe=4eb17c846c) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | [234358d23e](https://linux-hardware.org/?probe=234358d23e) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | [1b75d34b95](https://linux-hardware.org/?probe=1b75d34b95) | Feb 20, 2023 |
| Notebook      | W54_55SU1,SUW               | [5a296bed7f](https://linux-hardware.org/?probe=5a296bed7f) | Feb 19, 2023 |
| Dell          | XPS 13 9370                 | [e710561f68](https://linux-hardware.org/?probe=e710561f68) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [5300c136fd](https://linux-hardware.org/?probe=5300c136fd) | Feb 19, 2023 |
| Acer          | Nitro AN515-55              | [3158f1e0d5](https://linux-hardware.org/?probe=3158f1e0d5) | Feb 18, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [8907f179e9](https://linux-hardware.org/?probe=8907f179e9) | Feb 18, 2023 |
| Lenovo        | ThinkPad E480 20KN001QGE    | [008f40a707](https://linux-hardware.org/?probe=008f40a707) | Feb 18, 2023 |
| Dell          | Latitude E5450              | [56827b29dc](https://linux-hardware.org/?probe=56827b29dc) | Feb 18, 2023 |
| HP            | Laptop 17-bs0xx             | [cc805e31b0](https://linux-hardware.org/?probe=cc805e31b0) | Feb 17, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | [32f5d5e200](https://linux-hardware.org/?probe=32f5d5e200) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [02e6818311](https://linux-hardware.org/?probe=02e6818311) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [4bf1ccfe74](https://linux-hardware.org/?probe=4bf1ccfe74) | Feb 17, 2023 |
| Apple         | MacBookPro9,1               | [4ab4c99cab](https://linux-hardware.org/?probe=4ab4c99cab) | Feb 17, 2023 |
| Dell          | System XPS L702X            | [81f9738975](https://linux-hardware.org/?probe=81f9738975) | Feb 16, 2023 |
| Dell          | Precision 5570              | [d5f9d13ae3](https://linux-hardware.org/?probe=d5f9d13ae3) | Feb 16, 2023 |
| Apple         | MacBookAir6,2               | [46aafc59c4](https://linux-hardware.org/?probe=46aafc59c4) | Feb 16, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [a4fd7cdaa8](https://linux-hardware.org/?probe=a4fd7cdaa8) | Feb 16, 2023 |
| HP            | EliteBook 2530p             | [5398361b68](https://linux-hardware.org/?probe=5398361b68) | Feb 16, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [73787e9141](https://linux-hardware.org/?probe=73787e9141) | Feb 16, 2023 |
| Dell          | Precision 5570              | [d0f2fa25c3](https://linux-hardware.org/?probe=d0f2fa25c3) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [13866e78a2](https://linux-hardware.org/?probe=13866e78a2) | Feb 15, 2023 |
| Google        | Grunt                       | [89c633c2c1](https://linux-hardware.org/?probe=89c633c2c1) | Feb 15, 2023 |
| ASUSTek       | K53U                        | [e9a6a69e01](https://linux-hardware.org/?probe=e9a6a69e01) | Feb 15, 2023 |
| Unknown       | T3 MRD                      | [df134a8199](https://linux-hardware.org/?probe=df134a8199) | Feb 14, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [e9faf4ce80](https://linux-hardware.org/?probe=e9faf4ce80) | Feb 14, 2023 |
| Acer          | Aspire V5-572G              | [7f360258ff](https://linux-hardware.org/?probe=7f360258ff) | Feb 14, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [977650806e](https://linux-hardware.org/?probe=977650806e) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [f6bcdb7c6b](https://linux-hardware.org/?probe=f6bcdb7c6b) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [345021f7f6](https://linux-hardware.org/?probe=345021f7f6) | Feb 14, 2023 |
| Lenovo        | ThinkPad P51 20HJS0AR16     | [ad0f22fe34](https://linux-hardware.org/?probe=ad0f22fe34) | Feb 14, 2023 |
| ASUSTek       | X505BP                      | [579388a539](https://linux-hardware.org/?probe=579388a539) | Feb 13, 2023 |
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
| Dell          | Latitude E6330              | [1b5cdf846f](https://linux-hardware.org/?probe=1b5cdf846f) | Feb 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [20a75bea61](https://linux-hardware.org/?probe=20a75bea61) | Feb 11, 2023 |
| HP            | Pavilion g6                 | [35b93693a5](https://linux-hardware.org/?probe=35b93693a5) | Feb 10, 2023 |
| Dell          | Latitude 7370               | [30c62c9e44](https://linux-hardware.org/?probe=30c62c9e44) | Feb 10, 2023 |
| Dell          | Latitude 7370               | [b4e7a5cb63](https://linux-hardware.org/?probe=b4e7a5cb63) | Feb 10, 2023 |
| ASUSTek       | N751JX                      | [fd591a3e67](https://linux-hardware.org/?probe=fd591a3e67) | Feb 10, 2023 |
| Novatech      | NL40_50CU                   | [cca307c7db](https://linux-hardware.org/?probe=cca307c7db) | Feb 10, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [7ac6f508b2](https://linux-hardware.org/?probe=7ac6f508b2) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [8239d80ae0](https://linux-hardware.org/?probe=8239d80ae0) | Feb 10, 2023 |
| Lenovo        | ThinkPad SL510 28477MG      | [8f22e1beaa](https://linux-hardware.org/?probe=8f22e1beaa) | Feb 10, 2023 |
| Samsung       | 550XDA                      | [45d947c9f9](https://linux-hardware.org/?probe=45d947c9f9) | Feb 10, 2023 |
| IBM           | ThinkPad T43 18714AG        | [0730c9228d](https://linux-hardware.org/?probe=0730c9228d) | Feb 10, 2023 |
| HP            | Laptop 17-bs0xx             | [84eb5f0ad8](https://linux-hardware.org/?probe=84eb5f0ad8) | Feb 09, 2023 |
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
| Dell          | Precision 5570              | [6c257e667d](https://linux-hardware.org/?probe=6c257e667d) | Feb 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [d37cc19110](https://linux-hardware.org/?probe=d37cc19110) | Feb 08, 2023 |
| Dell          | Precision 5570              | [e81b3de663](https://linux-hardware.org/?probe=e81b3de663) | Feb 08, 2023 |
| Dell          | Inspiron 5555               | [f5aeb173ba](https://linux-hardware.org/?probe=f5aeb173ba) | Feb 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [def4679f84](https://linux-hardware.org/?probe=def4679f84) | Feb 07, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | [db2f72084a](https://linux-hardware.org/?probe=db2f72084a) | Feb 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [eca3a05d41](https://linux-hardware.org/?probe=eca3a05d41) | Feb 07, 2023 |
| Panasonic     | CF-54-1                     | [32a2acc07e](https://linux-hardware.org/?probe=32a2acc07e) | Feb 07, 2023 |
| Samsung       | R530/R730                   | [f212e58647](https://linux-hardware.org/?probe=f212e58647) | Feb 07, 2023 |
| Samsung       | R530/R730                   | [9ccb976ccd](https://linux-hardware.org/?probe=9ccb976ccd) | Feb 07, 2023 |
| Dell          | Latitude E7250              | [b4a7701aa4](https://linux-hardware.org/?probe=b4a7701aa4) | Feb 07, 2023 |
| Dell          | Precision 5570              | [d279e97c00](https://linux-hardware.org/?probe=d279e97c00) | Feb 07, 2023 |
| Toshiba       | Satellite C655              | [a0c2eb7db1](https://linux-hardware.org/?probe=a0c2eb7db1) | Feb 07, 2023 |
| Google        | Terra                       | [edfe00266c](https://linux-hardware.org/?probe=edfe00266c) | Feb 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | [7d2d46a579](https://linux-hardware.org/?probe=7d2d46a579) | Feb 06, 2023 |
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
| HP            | Laptop 17-bs0xx             | [78ca889e8d](https://linux-hardware.org/?probe=78ca889e8d) | Feb 04, 2023 |
| Lenovo        | ThinkPad T440p 20ANS09W0... | [17f9df8f2c](https://linux-hardware.org/?probe=17f9df8f2c) | Feb 03, 2023 |
| Lenovo        | V310-15IKB 80T3             | [a39fb673c7](https://linux-hardware.org/?probe=a39fb673c7) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [4de96841bf](https://linux-hardware.org/?probe=4de96841bf) | Feb 03, 2023 |
| HP            | Pavilion 15                 | [5909dd08e7](https://linux-hardware.org/?probe=5909dd08e7) | Feb 03, 2023 |
| Acer          | Predator PH315-54           | [fe381cbbfe](https://linux-hardware.org/?probe=fe381cbbfe) | Feb 03, 2023 |
| Aquarius      | NS585                       | [7e944d88b3](https://linux-hardware.org/?probe=7e944d88b3) | Feb 03, 2023 |
| HP            | ProBook 450 G7              | [ae290fa64e](https://linux-hardware.org/?probe=ae290fa64e) | Feb 03, 2023 |
| HP            | ProBook 450 G7              | [7820377760](https://linux-hardware.org/?probe=7820377760) | Feb 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [c122070f4f](https://linux-hardware.org/?probe=c122070f4f) | Feb 03, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [2f2c8adb0c](https://linux-hardware.org/?probe=2f2c8adb0c) | Feb 02, 2023 |
| Apple         | MacBook5,2                  | [6d7a27b213](https://linux-hardware.org/?probe=6d7a27b213) | Feb 02, 2023 |
| Google        | Babymega                    | [2a8b81c6f4](https://linux-hardware.org/?probe=2a8b81c6f4) | Feb 02, 2023 |
| Dell          | Vostro 3580                 | [7efc294bac](https://linux-hardware.org/?probe=7efc294bac) | Feb 02, 2023 |
| Lenovo        | ThinkPad E495 20NE001GMX    | [29660bbd04](https://linux-hardware.org/?probe=29660bbd04) | Feb 02, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Debian 11                       | 3268      | 64.02%  |
| Debian 10                       | 854       | 16.73%  |
| Debian Testing                  | 357       | 6.99%   |
| Debian 12                       | 204       | 4%      |
| Debian 9                        | 146       | 2.86%   |
| Debian Unstable                 | 128       | 2.51%   |
| Debian                          | 102       | 2%      |
| Debian 11-updates               | 27        | 0.53%   |
| Debian 8                        | 10        | 0.2%    |
| Debian Sid                      | 4         | 0.08%   |
| Debian Testing/unstable         | 2         | 0.04%   |
| Debian Testing-proposed-updates | 1         | 0.02%   |
| Debian 99                       | 1         | 0.02%   |
| Debian 23                       | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Debian | 4933      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.10.0-8-amd64    | 583       | 10.37%  |
| 5.10.0-10-amd64   | 491       | 8.73%   |
| 5.10.0-20-amd64   | 239       | 4.25%   |
| 5.10.0-21-amd64   | 235       | 4.18%   |
| 5.10.0-18-amd64   | 177       | 3.15%   |
| 5.10.0-9-amd64    | 173       | 3.08%   |
| 5.10.0-7-amd64    | 171       | 3.04%   |
| 5.10.0-16-amd64   | 166       | 2.95%   |
| 5.10.0-19-amd64   | 161       | 2.86%   |
| 5.10.0-13-amd64   | 150       | 2.67%   |
| 5.10.0-11-amd64   | 103       | 1.83%   |
| 4.19.0-9-amd64    | 85        | 1.51%   |
| 4.19.0-6-amd64    | 82        | 1.46%   |
| 5.10.0-14-amd64   | 80        | 1.42%   |
| 5.10.0-17-amd64   | 73        | 1.3%    |
| 4.19.0-13-amd64   | 69        | 1.23%   |
| 4.19.0-8-amd64    | 68        | 1.21%   |
| 5.10.0-23-amd64   | 60        | 1.07%   |
| 4.19.0-16-amd64   | 53        | 0.94%   |
| 4.19.0-10-amd64   | 52        | 0.92%   |
| 6.1.0-7-amd64     | 51        | 0.91%   |
| 5.15.0-2-amd64    | 51        | 0.91%   |
| 5.10.0-15-amd64   | 50        | 0.89%   |
| 5.10.0-2-amd64    | 49        | 0.87%   |
| 4.19.0-12-amd64   | 47        | 0.84%   |
| 4.19.0-14-amd64   | 42        | 0.75%   |
| 5.10.0-6-amd64    | 41        | 0.73%   |
| 5.10.0-12-amd64   | 41        | 0.73%   |
| 4.19.0-17-amd64   | 40        | 0.71%   |
| 4.9.0-8-amd64     | 39        | 0.69%   |
| 6.1.0-4-amd64     | 38        | 0.68%   |
| 5.10.0-22-amd64   | 36        | 0.64%   |
| 6.1.0-9-amd64     | 35        | 0.62%   |
| 5.18.0-2-amd64    | 31        | 0.55%   |
| 5.10.0-3-amd64    | 31        | 0.55%   |
| 6.1.0-6-amd64     | 27        | 0.48%   |
| 6.0.0-6-amd64     | 27        | 0.48%   |
| 5.19.0-1-amd64    | 27        | 0.48%   |
| 5.10.0-13-686-pae | 26        | 0.46%   |
| 5.4.0-4-amd64     | 25        | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 3079      | 58.74%  |
| 4.19.0  | 655       | 12.5%   |
| 6.1.0   | 234       | 4.46%   |
| 6.0.0   | 141       | 2.69%   |
| 4.9.0   | 120       | 2.29%   |
| 5.18.0  | 106       | 2.02%   |
| 5.15.0  | 92        | 1.76%   |
| 5.9.0   | 74        | 1.41%   |
| 5.19.0  | 69        | 1.32%   |
| 5.16.0  | 69        | 1.32%   |
| 5.4.0   | 64        | 1.22%   |
| 5.7.0   | 59        | 1.13%   |
| 5.8.0   | 56        | 1.07%   |
| 5.14.0  | 53        | 1.01%   |
| 5.6.0   | 45        | 0.86%   |
| 5.17.0  | 39        | 0.74%   |
| 5.3.0   | 19        | 0.36%   |
| 5.5.0   | 16        | 0.31%   |
| 5.2.0   | 12        | 0.23%   |
| 4.18.0  | 12        | 0.23%   |
| 3.16.0  | 8         | 0.15%   |
| 5.12.0  | 6         | 0.11%   |
| 5.10.10 | 4         | 0.08%   |
| 6.3.4   | 3         | 0.06%   |
| 6.2.8   | 3         | 0.06%   |
| 5.3.5   | 3         | 0.06%   |
| 5.17.5  | 3         | 0.06%   |
| 5.13.19 | 3         | 0.06%   |
| 5.13.0  | 3         | 0.06%   |
| 5.11.0  | 3         | 0.06%   |
| 5.10.60 | 3         | 0.06%   |
| 5.0.0   | 3         | 0.06%   |
| 6.3.0   | 2         | 0.04%   |
| 6.2.11  | 2         | 0.04%   |
| 6.1.15  | 2         | 0.04%   |
| 6.0.9   | 2         | 0.04%   |
| 6.0.2   | 2         | 0.04%   |
| 5.8.2   | 2         | 0.04%   |
| 5.8.16  | 2         | 0.04%   |
| 5.4.21  | 2         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 3103      | 59.32%  |
| 4.19    | 659       | 12.6%   |
| 6.1     | 240       | 4.59%   |
| 6.0     | 149       | 2.85%   |
| 4.9     | 123       | 2.35%   |
| 5.15    | 115       | 2.2%    |
| 5.18    | 111       | 2.12%   |
| 5.9     | 80        | 1.53%   |
| 5.4     | 76        | 1.45%   |
| 5.19    | 74        | 1.41%   |
| 5.16    | 73        | 1.4%    |
| 5.7     | 62        | 1.19%   |
| 5.8     | 61        | 1.17%   |
| 5.14    | 58        | 1.11%   |
| 5.6     | 49        | 0.94%   |
| 5.17    | 48        | 0.92%   |
| 5.3     | 24        | 0.46%   |
| 5.5     | 19        | 0.36%   |
| 5.2     | 18        | 0.34%   |
| 5.13    | 12        | 0.23%   |
| 4.18    | 12        | 0.23%   |
| 6.2     | 9         | 0.17%   |
| 5.12    | 9         | 0.17%   |
| 5.11    | 9         | 0.17%   |
| 3.16    | 8         | 0.15%   |
| 6.3     | 5         | 0.1%    |
| 3.10    | 4         | 0.08%   |
| 5.1     | 3         | 0.06%   |
| 5.0     | 3         | 0.06%   |
| 4.17    | 2         | 0.04%   |
| 4.15    | 2         | 0.04%   |
| 4.14    | 2         | 0.04%   |
| 5.4.104 | 1         | 0.02%   |
| 5.15.6  | 1         | 0.02%   |
| 4.4     | 1         | 0.02%   |
| 4.20    | 1         | 0.02%   |
| 4.13    | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |
| 4.10    | 1         | 0.02%   |
| 3.8     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 4705      | 95.36%  |
| i686    | 216       | 4.38%   |
| armv7l  | 9         | 0.18%   |
| aarch64 | 3         | 0.06%   |
| i586    | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 1360      | 26.89%  |
| Unknown           | 1244      | 24.6%   |
| XFCE              | 666       | 13.17%  |
| KDE5              | 649       | 12.83%  |
| MATE              | 213       | 4.21%   |
| X-Cinnamon        | 177       | 3.5%    |
| LXDE              | 153       | 3.03%   |
| Cinnamon          | 144       | 2.85%   |
| KDE               | 114       | 2.25%   |
| i3                | 92        | 1.82%   |
| LXQt              | 71        | 1.4%    |
| GNOME Flashback   | 38        | 0.75%   |
| lightdm-xsession  | 25        | 0.49%   |
| openbox           | 16        | 0.32%   |
| Budgie            | 15        | 0.3%    |
| trinity           | 13        | 0.26%   |
| GNOME Classic     | 12        | 0.24%   |
| sway              | 5         | 0.1%    |
| Enlightenment     | 5         | 0.1%    |
| awesome           | 5         | 0.1%    |
| ICEWM             | 4         | 0.08%   |
| Fluxbox           | 4         | 0.08%   |
| bspwm             | 4         | 0.08%   |
| DWM               | 3         | 0.06%   |
| Cutefish          | 3         | 0.06%   |
| BunsenLabs        | 3         | 0.06%   |
| xmonad            | 2         | 0.04%   |
| x-session-manager | 2         | 0.04%   |
| Unity             | 2         | 0.04%   |
| KDE4              | 2         | 0.04%   |
| GNUstep           | 2         | 0.04%   |
| default           | 2         | 0.04%   |
| wmaker-common     | 1         | 0.02%   |
| Pantheon          | 1         | 0.02%   |
| mwm               | 1         | 0.02%   |
| matchbox          | 1         | 0.02%   |
| jwm               | 1         | 0.02%   |
| i3-gaps           | 1         | 0.02%   |
| Deepin            | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 2832      | 56.31%  |
| Unknown     | 1002      | 19.92%  |
| Wayland     | 992       | 19.73%  |
| Tty         | 198       | 3.94%   |
| Unspecified | 4         | 0.08%   |
| Web         | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1954      | 38.62%  |
| GDM     | 986       | 19.49%  |
| LightDM | 850       | 16.8%   |
| SDDM    | 614       | 12.13%  |
| TDM     | 310       | 6.13%   |
| GDM3    | 285       | 5.63%   |
| XDM     | 20        | 0.4%    |
| SLiM    | 13        | 0.26%   |
| NODM    | 10        | 0.2%    |
| KDM     | 8         | 0.16%   |
| LXDM    | 4         | 0.08%   |
| Ly      | 2         | 0.04%   |
| GREETD  | 2         | 0.04%   |
| WDM     | 1         | 0.02%   |
| SU      | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1491      | 29.77%  |
| Unknown | 993       | 19.82%  |
| ru_RU   | 340       | 6.79%   |
| de_DE   | 329       | 6.57%   |
| fr_FR   | 288       | 5.75%   |
| en_GB   | 214       | 4.27%   |
| pt_BR   | 164       | 3.27%   |
| es_ES   | 145       | 2.89%   |
| it_IT   | 137       | 2.74%   |
| pl_PL   | 104       | 2.08%   |
| en_CA   | 56        | 1.12%   |
| C       | 52        | 1.04%   |
| es_MX   | 48        | 0.96%   |
| en_AU   | 44        | 0.88%   |
| zh_CN   | 41        | 0.82%   |
| en_IN   | 40        | 0.8%    |
| es_AR   | 36        | 0.72%   |
| en_IE   | 29        | 0.58%   |
| es_CL   | 28        | 0.56%   |
| sv_SE   | 26        | 0.52%   |
| hu_HU   | 25        | 0.5%    |
| de_CH   | 20        | 0.4%    |
| pt_PT   | 18        | 0.36%   |
| fi_FI   | 18        | 0.36%   |
| nl_NL   | 16        | 0.32%   |
| es_VE   | 16        | 0.32%   |
| cs_CZ   | 16        | 0.32%   |
| de_AT   | 15        | 0.3%    |
| en_NZ   | 14        | 0.28%   |
| ja_JP   | 13        | 0.26%   |
| es_CO   | 13        | 0.26%   |
| tr_TR   | 12        | 0.24%   |
| fr_BE   | 12        | 0.24%   |
| en_ZA   | 11        | 0.22%   |
| ko_KR   | 10        | 0.2%    |
| en_SG   | 10        | 0.2%    |
| ru_UA   | 9         | 0.18%   |
| sk_SK   | 8         | 0.16%   |
| ca_ES   | 8         | 0.16%   |
| zh_TW   | 7         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 3082      | 61.83%  |
| BIOS | 1903      | 38.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 3536      | 71.3%   |
| Overlay | 1082      | 21.82%  |
| Btrfs   | 156       | 3.15%   |
| Unknown | 78        | 1.57%   |
| Xfs     | 46        | 0.93%   |
| Zfs     | 14        | 0.28%   |
| Ext2    | 14        | 0.28%   |
| Tmpfs   | 12        | 0.24%   |
| Rootfs  | 10        | 0.2%    |
| Ext3    | 6         | 0.12%   |
| Aufs    | 4         | 0.08%   |
| F2fs    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 3101      | 61.9%   |
| MBR     | 963       | 19.22%  |
| Unknown | 946       | 18.88%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4123      | 82.51%  |
| Yes       | 874       | 17.49%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3701      | 74.23%  |
| Yes       | 1285      | 25.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1091      | 22.12%  |
| Hewlett-Packard        | 735       | 14.9%   |
| Dell                   | 711       | 14.41%  |
| Apple                  | 649       | 13.16%  |
| ASUSTek Computer       | 446       | 9.04%   |
| Acer                   | 329       | 6.67%   |
| Google                 | 144       | 2.92%   |
| Toshiba                | 87        | 1.76%   |
| MSI                    | 79        | 1.6%    |
| Samsung Electronics    | 74        | 1.5%    |
| Aquarius               | 48        | 0.97%   |
| Sony                   | 41        | 0.83%   |
| HUAWEI                 | 41        | 0.83%   |
| Unknown                | 41        | 0.83%   |
| Notebook               | 30        | 0.61%   |
| Fujitsu                | 27        | 0.55%   |
| Medion                 | 16        | 0.32%   |
| Panasonic              | 14        | 0.28%   |
| Intel                  | 14        | 0.28%   |
| TUXEDO                 | 13        | 0.26%   |
| Positivo               | 13        | 0.26%   |
| Packard Bell           | 13        | 0.26%   |
| IBM                    | 13        | 0.26%   |
| Alienware              | 13        | 0.26%   |
| Timi                   | 11        | 0.22%   |
| Clevo                  | 11        | 0.22%   |
| LG Electronics         | 10        | 0.2%    |
| Fujitsu Siemens        | 8         | 0.16%   |
| Razer                  | 7         | 0.14%   |
| PC Specialist          | 7         | 0.14%   |
| eMachines              | 7         | 0.14%   |
| System76               | 6         | 0.12%   |
| SLIMBOOK               | 6         | 0.12%   |
| HONOR                  | 6         | 0.12%   |
| GPU Company            | 6         | 0.12%   |
| Gigabyte Technology    | 6         | 0.12%   |
| Chuwi                  | 6         | 0.12%   |
| Schenker               | 5         | 0.1%    |
| Avell High Performance | 5         | 0.1%    |
| Insyde                 | 4         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBook5,2                      | 354       | 7.18%   |
| Apple MacBookAir7,2                   | 77        | 1.56%   |
| Apple MacBookAir7,1                   | 77        | 1.56%   |
| Google Enguarde                       | 74        | 1.5%    |
| Apple MacBook2,1                      | 56        | 1.14%   |
| Unknown                               | 54        | 1.09%   |
| Aquarius NS585                        | 48        | 0.97%   |
| HP Notebook                           | 27        | 0.55%   |
| Lenovo ThinkPad E475 20H40006US       | 24        | 0.49%   |
| Google Terra                          | 23        | 0.47%   |
| Apple MacBook4,1                      | 23        | 0.47%   |
| HP Pavilion g6                        | 17        | 0.34%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US | 16        | 0.32%   |
| Acer Aspire A315-23                   | 16        | 0.32%   |
| ASUS 1005HA                           | 15        | 0.3%    |
| Google Reks                           | 13        | 0.26%   |
| Dell Latitude E7440                   | 13        | 0.26%   |
| HP Laptop 15-db0xxx                   | 12        | 0.24%   |
| HP EliteBook 8460p                    | 11        | 0.22%   |
| HP 255 G8 Notebook PC                 | 10        | 0.2%    |
| Dell Latitude E7450                   | 10        | 0.2%    |
| Dell Latitude E6430                   | 10        | 0.2%    |
| Dell Latitude 7480                    | 10        | 0.2%    |
| HP EliteBook 840 G3                   | 9         | 0.18%   |
| HP 250 G7 Notebook PC                 | 9         | 0.18%   |
| Dell XPS 13 9310                      | 9         | 0.18%   |
| Dell Latitude E6420                   | 9         | 0.18%   |
| Dell Latitude 5420                    | 9         | 0.18%   |
| Dell Inspiron 5570                    | 9         | 0.18%   |
| Dell Inspiron 15-3567                 | 9         | 0.18%   |
| Samsung 300E4C/300E5C/300E7C          | 8         | 0.16%   |
| HP Pavilion Notebook                  | 8         | 0.16%   |
| HP Pavilion Gaming Laptop 15-ec2xxx   | 8         | 0.16%   |
| HP Pavilion dv6                       | 8         | 0.16%   |
| HP Laptop 15-db1xxx                   | 8         | 0.16%   |
| Dell Latitude E6330                   | 8         | 0.16%   |
| Lenovo IdeaPad S145-15API 81V7        | 7         | 0.14%   |
| HP Stream Notebook PC 13              | 7         | 0.14%   |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 7         | 0.14%   |
| HP Laptop 15-bw0xx                    | 7         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 727       | 14.74%  |
| Apple MacBook5    | 355       | 7.2%    |
| Dell Latitude     | 278       | 5.64%   |
| Acer Aspire       | 214       | 4.34%   |
| Dell Inspiron     | 210       | 4.26%   |
| Lenovo IdeaPad    | 184       | 3.73%   |
| Apple MacBookAir7 | 154       | 3.12%   |
| HP EliteBook      | 150       | 3.04%   |
| HP Pavilion       | 111       | 2.25%   |
| HP ProBook        | 98        | 1.99%   |
| HP Laptop         | 98        | 1.99%   |
| Google Enguarde   | 74        | 1.5%    |
| Dell XPS          | 72        | 1.46%   |
| Toshiba Satellite | 68        | 1.38%   |
| ASUS VivoBook     | 66        | 1.34%   |
| Dell Vostro       | 59        | 1.2%    |
| Dell Precision    | 57        | 1.16%   |
| Apple MacBook2    | 56        | 1.14%   |
| Unknown           | 54        | 1.09%   |
| Aquarius NS585    | 48        | 0.97%   |
| HP Compaq         | 42        | 0.85%   |
| HP ZBook          | 32        | 0.65%   |
| HP 250            | 32        | 0.65%   |
| ASUS ZenBook      | 31        | 0.63%   |
| Lenovo Legion     | 27        | 0.55%   |
| HP Notebook       | 27        | 0.55%   |
| ASUS ASUS         | 27        | 0.55%   |
| Acer TravelMate   | 26        | 0.53%   |
| Acer Nitro        | 26        | 0.53%   |
| Lenovo ThinkBook  | 24        | 0.49%   |
| Acer Swift        | 24        | 0.49%   |
| HP 255            | 23        | 0.47%   |
| Google Terra      | 23        | 0.47%   |
| Fujitsu LIFEBOOK  | 23        | 0.47%   |
| Apple MacBook4    | 23        | 0.47%   |
| HP ENVY           | 19        | 0.39%   |
| ASUS ROG          | 19        | 0.39%   |
| HP OMEN           | 17        | 0.34%   |
| ASUS 1005HA       | 15        | 0.3%    |
| HP Stream         | 14        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2009    | 495       | 10.03%  |
| 2019    | 486       | 9.85%   |
| 2020    | 450       | 9.12%   |
| 2021    | 424       | 8.6%    |
| 2018    | 312       | 6.32%   |
| 2012    | 312       | 6.32%   |
| 2016    | 306       | 6.2%    |
| 2011    | 304       | 6.16%   |
| 2017    | 301       | 6.1%    |
| 2015    | 292       | 5.92%   |
| 2013    | 249       | 5.05%   |
| 2014    | 226       | 4.58%   |
| 2022    | 205       | 4.16%   |
| 2010    | 188       | 3.81%   |
| 2008    | 146       | 2.96%   |
| 2007    | 130       | 2.64%   |
| 2006    | 36        | 0.73%   |
| 2005    | 24        | 0.49%   |
| Unknown | 14        | 0.28%   |
| 2004    | 11        | 0.22%   |
| 2003    | 11        | 0.22%   |
| 2023    | 9         | 0.18%   |
| 2002    | 2         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4933      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4544      | 91.69%  |
| Enabled  | 412       | 8.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4774      | 96.76%  |
| Yes  | 160       | 3.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1302      | 26.15%  |
| 3.01-4.0    | 964       | 19.36%  |
| 16.01-24.0  | 798       | 16.03%  |
| 8.01-16.0   | 763       | 15.32%  |
| 1.01-2.0    | 564       | 11.33%  |
| 32.01-64.0  | 282       | 5.66%   |
| 2.01-3.0    | 101       | 2.03%   |
| 0.51-1.0    | 81        | 1.63%   |
| 64.01-256.0 | 54        | 1.08%   |
| 24.01-32.0  | 47        | 0.94%   |
| 0.01-0.5    | 21        | 0.42%   |
| Unknown     | 2         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2056      | 38.86%  |
| 2.01-3.0   | 1094      | 20.68%  |
| 4.01-8.0   | 703       | 13.29%  |
| 3.01-4.0   | 548       | 10.36%  |
| 0.51-1.0   | 535       | 10.11%  |
| 8.01-16.0  | 191       | 3.61%   |
| 0.01-0.5   | 133       | 2.51%   |
| 16.01-24.0 | 16        | 0.3%    |
| Unknown    | 7         | 0.13%   |
| 32.01-64.0 | 4         | 0.08%   |
| 24.01-32.0 | 3         | 0.06%   |
| 0          | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3906      | 78.01%  |
| 2      | 937       | 18.71%  |
| 3      | 107       | 2.14%   |
| 0      | 33        | 0.66%   |
| 4      | 17        | 0.34%   |
| 5      | 5         | 0.1%    |
| 7      | 2         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3227      | 65.17%  |
| Yes       | 1725      | 34.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4040      | 81.62%  |
| No        | 910       | 18.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4837      | 97.95%  |
| No        | 101       | 2.05%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3973      | 79.99%  |
| No        | 994       | 20.01%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 1279      | 25.76%  |
| Germany     | 477       | 9.61%   |
| Russia      | 391       | 7.88%   |
| France      | 356       | 7.17%   |
| Brazil      | 243       | 4.89%   |
| Spain       | 204       | 4.11%   |
| Italy       | 187       | 3.77%   |
| Poland      | 146       | 2.94%   |
| UK          | 112       | 2.26%   |
| Netherlands | 82        | 1.65%   |
| Canada      | 77        | 1.55%   |
| Mexico      | 70        | 1.41%   |
| Switzerland | 67        | 1.35%   |
| Sweden      | 61        | 1.23%   |
| India       | 60        | 1.21%   |
| Argentina   | 57        | 1.15%   |
| China       | 56        | 1.13%   |
| Ukraine     | 55        | 1.11%   |
| Australia   | 51        | 1.03%   |
| Turkey      | 43        | 0.87%   |
| Portugal    | 43        | 0.87%   |
| Belgium     | 43        | 0.87%   |
| Hungary     | 42        | 0.85%   |
| Austria     | 37        | 0.75%   |
| Czechia     | 36        | 0.73%   |
| Finland     | 34        | 0.68%   |
| Chile       | 34        | 0.68%   |
| Greece      | 31        | 0.62%   |
| Norway      | 30        | 0.6%    |
| Romania     | 28        | 0.56%   |
| Indonesia   | 24        | 0.48%   |
| Japan       | 23        | 0.46%   |
| Ireland     | 23        | 0.46%   |
| Colombia    | 23        | 0.46%   |
| Venezuela   | 19        | 0.38%   |
| New Zealand | 19        | 0.38%   |
| Denmark     | 18        | 0.36%   |
| Thailand    | 17        | 0.34%   |
| Bulgaria    | 17        | 0.34%   |
| Croatia     | 16        | 0.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Bangor            | 619       | 11.78%  |
| Dover-Foxcroft    | 229       | 4.36%   |
| Voronezh          | 160       | 3.05%   |
| Paris             | 61        | 1.16%   |
| Moscow            | 60        | 1.14%   |
| St Petersburg     | 52        | 0.99%   |
| Berlin            | 47        | 0.89%   |
| Madrid            | 39        | 0.74%   |
| Seville           | 38        | 0.72%   |
| Warsaw            | 36        | 0.69%   |
| Sao Paulo         | 36        | 0.69%   |
| Munich            | 33        | 0.63%   |
| Hamburg           | 27        | 0.51%   |
| Vienna            | 26        | 0.49%   |
| Amsterdam         | 25        | 0.48%   |
| Milan             | 24        | 0.46%   |
| Barcelona         | 22        | 0.42%   |
| Prague            | 20        | 0.38%   |
| Frankfurt am Main | 19        | 0.36%   |
| Zurich            | 18        | 0.34%   |
| London            | 18        | 0.34%   |
| Istanbul          | 18        | 0.34%   |
| Budapest          | 18        | 0.34%   |
| Sydney            | 16        | 0.3%    |
| Mexico City       | 16        | 0.3%    |
| Athens            | 16        | 0.3%    |
| Saltsjoe-Boo      | 15        | 0.29%   |
| Lisbon            | 15        | 0.29%   |
| Helsinki          | 15        | 0.29%   |
| Dublin            | 15        | 0.29%   |
| Brasília         | 15        | 0.29%   |
| Perm              | 14        | 0.27%   |
| Cologne           | 14        | 0.27%   |
| Singapore         | 13        | 0.25%   |
| Rome              | 12        | 0.23%   |
| Leipzig           | 12        | 0.23%   |
| Buenos Aires      | 12        | 0.23%   |
| Zagreb            | 11        | 0.21%   |
| Toronto           | 11        | 0.21%   |
| San Jose          | 11        | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 873       | 1109   | 14.72%  |
| WDC                       | 668       | 823    | 11.26%  |
| Seagate                   | 548       | 652    | 9.24%   |
| Toshiba                   | 460       | 513    | 7.75%   |
| Unknown                   | 390       | 500    | 6.57%   |
| Kingston                  | 324       | 395    | 5.46%   |
| SanDisk                   | 291       | 357    | 4.91%   |
| Fujitsu                   | 290       | 297    | 4.89%   |
| Crucial                   | 228       | 277    | 3.84%   |
| SK hynix                  | 222       | 272    | 3.74%   |
| Apple                     | 187       | 229    | 3.15%   |
| Hitachi                   | 162       | 187    | 2.73%   |
| Intel                     | 137       | 170    | 2.31%   |
| Micron Technology         | 134       | 146    | 2.26%   |
| A-DATA Technology         | 134       | 257    | 2.26%   |
| HGST                      | 117       | 137    | 1.97%   |
| KIOXIA                    | 64        | 77     | 1.08%   |
| LITEON                    | 36        | 43     | 0.61%   |
| China                     | 35        | 38     | 0.59%   |
| Unknown                   | 32        | 34     | 0.54%   |
| Transcend                 | 28        | 35     | 0.47%   |
| Phison                    | 25        | 33     | 0.42%   |
| Intenso                   | 25        | 34     | 0.42%   |
| Silicon Motion            | 24        | 29     | 0.4%    |
| PNY                       | 24        | 29     | 0.4%    |
| SPCC                      | 22        | 26     | 0.37%   |
| Patriot                   | 19        | 21     | 0.32%   |
| SSSTC                     | 18        | 18     | 0.3%    |
| SABRENT                   | 18        | 19     | 0.3%    |
| LITEONIT                  | 18        | 21     | 0.3%    |
| Team                      | 17        | 19     | 0.29%   |
| JMicron Technology        | 17        | 17     | 0.29%   |
| GOODRAM                   | 14        | 16     | 0.24%   |
| OCZ                       | 13        | 15     | 0.22%   |
| Micron/Crucial Technology | 11        | 11     | 0.19%   |
| Netac                     | 10        | 15     | 0.17%   |
| Lenovo                    | 9         | 11     | 0.15%   |
| LDLC                      | 9         | 9      | 0.15%   |
| Hewlett-Packard           | 9         | 10     | 0.15%   |
| ASMT                      | 9         | 16     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB       | 237       | 3.91%   |
| Apple SSD AP0128H 121GB              | 77        | 1.27%   |
| Apple SSD SM0128G 121GB              | 72        | 1.19%   |
| Seagate ST1000LM035-1RK172 1TB       | 69        | 1.14%   |
| Kingston SA400S37240G 240GB SSD      | 63        | 1.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 56        | 0.92%   |
| Kingston SA400S37120G 120GB SSD      | 54        | 0.89%   |
| Toshiba MK1655GSXF 160GB             | 52        | 0.86%   |
| A-DATA SU800 512GB SSD               | 50        | 0.82%   |
| Toshiba MQ01ABD100 1TB               | 45        | 0.74%   |
| Toshiba MK1653GSX 160GB              | 43        | 0.71%   |
| HGST HTS721010A9E630 1TB             | 41        | 0.68%   |
| Unknown AGND3R  16GB                 | 39        | 0.64%   |
| Toshiba MQ04ABF100 1TB               | 38        | 0.63%   |
| Crucial CT500MX500SSD1 500GB         | 37        | 0.61%   |
| Toshiba MQ01ABF050 500GB             | 36        | 0.59%   |
| Unknown MMC Card  32GB               | 34        | 0.56%   |
| Unknown                              | 32        | 0.53%   |
| Unknown HAG2e  16GB                  | 31        | 0.51%   |
| Samsung SSD 970 EVO Plus 1TB         | 30        | 0.49%   |
| Samsung SSD 860 EVO 500GB            | 30        | 0.49%   |
| Samsung SSD 850 EVO 250GB            | 29        | 0.48%   |
| Seagate ST500LT012-1DG142 500GB      | 28        | 0.46%   |
| Kingston SA400S37480G 480GB SSD      | 28        | 0.46%   |
| Crucial CT1000MX500SSD1 1TB          | 28        | 0.46%   |
| Seagate ST1000LM048-2E7172 1TB       | 26        | 0.43%   |
| Unknown SDW16G  16GB                 | 25        | 0.41%   |
| Samsung SSD 860 EVO 1TB              | 24        | 0.4%    |
| Kingston SV300S37A120G 120GB SSD     | 23        | 0.38%   |
| Unknown MMC Card  64GB               | 22        | 0.36%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 22        | 0.36%   |
| Seagate ST9500325AS 500GB            | 21        | 0.35%   |
| Samsung SSD 860 EVO 250GB            | 21        | 0.35%   |
| Samsung SSD 850 EVO 500GB            | 21        | 0.35%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 20        | 0.33%   |
| HGST HTS725050A7E630 500GB           | 20        | 0.33%   |
| Crucial CT240BX500SSD1 240GB         | 20        | 0.33%   |
| WDC WD10SPZX-24Z10 1TB               | 19        | 0.31%   |
| Samsung SSD 980 1TB                  | 19        | 0.31%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 19        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 527       | 627    | 27.88%  |
| WDC                 | 382       | 439    | 20.21%  |
| Toshiba             | 338       | 370    | 17.88%  |
| Fujitsu             | 290       | 297    | 15.34%  |
| Hitachi             | 162       | 187    | 8.57%   |
| HGST                | 117       | 137    | 6.19%   |
| Samsung Electronics | 34        | 36     | 1.8%    |
| Unknown             | 16        | 19     | 0.85%   |
| IBM/Hitachi         | 5         | 6      | 0.26%   |
| Intenso             | 4         | 5      | 0.21%   |
| SILICONMOTION       | 2         | 2      | 0.11%   |
| ASMT                | 2         | 7      | 0.11%   |
| Apple               | 2         | 2      | 0.11%   |
| USB3.0              | 1         | 1      | 0.05%   |
| Unknown (CF)        | 1         | 1      | 0.05%   |
| SAGE                | 1         | 1      | 0.05%   |
| QNAP                | 1         | 2      | 0.05%   |
| PHD 3.0             | 1         | 1      | 0.05%   |
| Maxone              | 1         | 1      | 0.05%   |
| IBM                 | 1         | 1      | 0.05%   |
| Hewlett-Packard     | 1         | 1      | 0.05%   |
| External            | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 386       | 488    | 19.76%  |
| Kingston            | 254       | 320    | 13.01%  |
| SanDisk             | 209       | 264    | 10.7%   |
| Crucial             | 204       | 250    | 10.45%  |
| A-DATA Technology   | 99        | 209    | 5.07%   |
| Apple               | 98        | 107    | 5.02%   |
| WDC                 | 81        | 105    | 4.15%   |
| Micron Technology   | 52        | 57     | 2.66%   |
| SK hynix            | 45        | 53     | 2.3%    |
| Intel               | 42        | 46     | 2.15%   |
| China               | 35        | 38     | 1.79%   |
| Toshiba             | 33        | 37     | 1.69%   |
| LITEON              | 30        | 35     | 1.54%   |
| Transcend           | 25        | 32     | 1.28%   |
| PNY                 | 20        | 24     | 1.02%   |
| Intenso             | 19        | 26     | 0.97%   |
| SABRENT             | 18        | 19     | 0.92%   |
| Patriot             | 18        | 20     | 0.92%   |
| LITEONIT            | 18        | 21     | 0.92%   |
| SPCC                | 17        | 20     | 0.87%   |
| Team                | 16        | 18     | 0.82%   |
| OCZ                 | 13        | 15     | 0.67%   |
| GOODRAM             | 11        | 13     | 0.56%   |
| Netac               | 10        | 15     | 0.51%   |
| JMicron Technology  | 10        | 10     | 0.51%   |
| Plextor             | 8         | 8      | 0.41%   |
| LDLC                | 8         | 8      | 0.41%   |
| KingSpec            | 8         | 8      | 0.41%   |
| Lexar               | 7         | 8      | 0.36%   |
| Apacer              | 7         | 7      | 0.36%   |
| Unknown             | 7         | 7      | 0.36%   |
| Seagate             | 6         | 6      | 0.31%   |
| KingDian            | 6         | 6      | 0.31%   |
| Corsair             | 6         | 6      | 0.31%   |
| ASMT                | 6         | 7      | 0.31%   |
| TO Exter            | 5         | 6      | 0.26%   |
| Hewlett-Packard     | 5         | 7      | 0.26%   |
| Gigabyte Technology | 4         | 4      | 0.2%    |
| FORESEE             | 4         | 4      | 0.2%    |
| Dogfish             | 4         | 7      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1850      | 2144   | 32.5%   |
| SSD     | 1818      | 2468   | 31.93%  |
| NVMe    | 1556      | 2026   | 27.33%  |
| MMC     | 413       | 526    | 7.25%   |
| Unknown | 56        | 63     | 0.98%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3299      | 4442   | 60.55%  |
| NVMe | 1556      | 2021   | 28.56%  |
| MMC  | 413       | 526    | 7.58%   |
| SAS  | 180       | 238    | 3.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2583      | 3236   | 71.31%  |
| 0.51-1.0   | 921       | 1224   | 25.43%  |
| 1.01-2.0   | 79        | 104    | 2.18%   |
| 10.01-20.0 | 18        | 19     | 0.5%    |
| 4.01-10.0  | 14        | 20     | 0.39%   |
| 3.01-4.0   | 5         | 6      | 0.14%   |
| 2.01-3.0   | 2         | 3      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1431      | 28.03%  |
| 251-500        | 1067      | 20.9%   |
| Unknown        | 805       | 15.77%  |
| 501-1000       | 662       | 12.97%  |
| 51-100         | 328       | 6.42%   |
| 1001-2000      | 266       | 5.21%   |
| 1-20           | 251       | 4.92%   |
| 21-50          | 185       | 3.62%   |
| 2001-3000      | 61        | 1.19%   |
| More than 3000 | 50        | 0.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1855      | 35.19%  |
| Unknown        | 805       | 15.27%  |
| 101-250        | 677       | 12.84%  |
| 21-50          | 675       | 12.8%   |
| 51-100         | 548       | 10.39%  |
| 251-500        | 366       | 6.94%   |
| 501-1000       | 222       | 4.21%   |
| 1001-2000      | 79        | 1.5%    |
| More than 3000 | 19        | 0.36%   |
| 2001-3000      | 15        | 0.28%   |
| 0              | 11        | 0.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB        | 25        | 25     | 5.01%   |
| Seagate ST9500325AS 500GB             | 11        | 11     | 2.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 11        | 13     | 2.2%    |
| Hitachi HTS543216L9SA02 160GB         | 11        | 11     | 2.2%    |
| Toshiba MK1653GSX 160GB               | 9         | 9      | 1.8%    |
| Toshiba MQ01ABD100 1TB                | 8         | 8      | 1.6%    |
| Toshiba MK1655GSXF 160GB              | 8         | 8      | 1.6%    |
| Seagate ST9500420AS 500GB             | 8         | 8      | 1.6%    |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 6         | 7      | 1.2%    |
| Seagate ST500LM021-1KJ152 500GB       | 6         | 6      | 1.2%    |
| Seagate ST1000LM035-1RK172 1TB        | 6         | 7      | 1.2%    |
| Hitachi HTS545050B9A300 500GB         | 6         | 6      | 1.2%    |
| HGST HTS541010A9E680 1TB              | 6         | 6      | 1.2%    |
| Toshiba MQ01ABF050 500GB              | 5         | 5      | 1%      |
| Seagate ST500LT012-9WS142 500GB       | 5         | 6      | 1%      |
| Hitachi HTS542512K9SA00 120GB         | 5         | 6      | 1%      |
| HGST HTS725050A7E630 500GB            | 5         | 6      | 1%      |
| WDC WD1600BUDT-63DPZY0 160GB          | 4         | 4      | 0.8%    |
| Seagate ST9320325AS 320GB             | 4         | 4      | 0.8%    |
| Seagate ST500LM000-SSHD-8GB           | 4         | 4      | 0.8%    |
| Seagate ST320LT007-9ZV142 320GB       | 4         | 6      | 0.8%    |
| Kingston SV300S37A120G 120GB SSD      | 4         | 4      | 0.8%    |
| Hitachi HTS547575A9E384 752GB         | 4         | 4      | 0.8%    |
| Crucial CT275MX300SSD1 275GB          | 4         | 4      | 0.8%    |
| Toshiba MQ04ABF100 1TB                | 3         | 3      | 0.6%    |
| SK hynix HFS256G39MND-2300A 256GB SSD | 3         | 4      | 0.6%    |
| Seagate ST9250315AS 250GB             | 3         | 4      | 0.6%    |
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 0.6%    |
| Seagate ST500LM012 HN-M500MBB 500GB   | 3         | 3      | 0.6%    |
| Kingston SA400S37240G 240GB SSD       | 3         | 3      | 0.6%    |
| Kingston SA400S37120G 120GB SSD       | 3         | 4      | 0.6%    |
| Hitachi HTS547550A9E384 500GB         | 3         | 3      | 0.6%    |
| Hitachi HTS543232A7A384 320GB         | 3         | 3      | 0.6%    |
| Hitachi HTS542516K9SA00 160GB         | 3         | 3      | 0.6%    |
| HGST HTS721010A9E630 1TB              | 3         | 4      | 0.6%    |
| WDC WD7500BPVX-22JC3T0 752GB          | 2         | 2      | 0.4%    |
| WDC WD7500BPKT-75PK4T0 752GB          | 2         | 2      | 0.4%    |
| WDC WD5000LPVX-75V0TT0 500GB          | 2         | 2      | 0.4%    |
| WDC WD10SPZX-60Z10T0 1TB              | 2         | 4      | 0.4%    |
| WDC WD10JPVX-22JC3T0 1TB              | 2         | 2      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 105       | 114    | 21.08%  |
| Hitachi             | 75        | 81     | 15.06%  |
| Toshiba             | 63        | 64     | 12.65%  |
| WDC                 | 45        | 49     | 9.04%   |
| Fujitsu             | 39        | 39     | 7.83%   |
| HGST                | 26        | 28     | 5.22%   |
| Samsung Electronics | 25        | 27     | 5.02%   |
| SK hynix            | 21        | 23     | 4.22%   |
| Kingston            | 17        | 18     | 3.41%   |
| SanDisk             | 14        | 16     | 2.81%   |
| Micron Technology   | 13        | 14     | 2.61%   |
| Intel               | 10        | 11     | 2.01%   |
| A-DATA Technology   | 10        | 11     | 2.01%   |
| Crucial             | 9         | 10     | 1.81%   |
| LITEONIT            | 3         | 4      | 0.6%    |
| LITEON              | 3         | 3      | 0.6%    |
| KingSpec            | 2         | 2      | 0.4%    |
| IBM/Hitachi         | 2         | 2      | 0.4%    |
| Corsair             | 2         | 2      | 0.4%    |
| Unknown             | 2         | 2      | 0.4%    |
| Team                | 1         | 1      | 0.2%    |
| SSSTC               | 1         | 1      | 0.2%    |
| ShiJi               | 1         | 2      | 0.2%    |
| Plextor             | 1         | 1      | 0.2%    |
| Lenovo              | 1         | 1      | 0.2%    |
| KingDian            | 1         | 1      | 0.2%    |
| JMicron Technology  | 1         | 1      | 0.2%    |
| IBM                 | 1         | 1      | 0.2%    |
| GOODRAM             | 1         | 1      | 0.2%    |
| DGM                 | 1         | 1      | 0.2%    |
| China               | 1         | 1      | 0.2%    |
| Apple               | 1         | 1      | 0.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 105       | 114    | 28.61%  |
| Hitachi             | 75        | 81     | 20.44%  |
| Toshiba             | 62        | 63     | 16.89%  |
| WDC                 | 44        | 48     | 11.99%  |
| Fujitsu             | 39        | 39     | 10.63%  |
| HGST                | 26        | 28     | 7.08%   |
| Samsung Electronics | 13        | 13     | 3.54%   |
| IBM/Hitachi         | 2         | 2      | 0.54%   |
| IBM                 | 1         | 1      | 0.27%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 364       | 389    | 73.54%  |
| SSD  | 112       | 122    | 22.63%  |
| NVMe | 19        | 22     | 3.84%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 11.11%  |
| Toshiba MQ04ABF100 1TB                          | 1         | 1      | 11.11%  |
| Toshiba MK6465GSX 640GB                         | 1         | 1      | 11.11%  |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 11.11%  |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 11.11%  |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 11.11%  |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 11.11%  |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 11.11%  |
| Crucial CT500P2SSD8 500GB                       | 1         | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 2      | 22.22%  |
| Seagate             | 2         | 2      | 22.22%  |
| Samsung Electronics | 2         | 2      | 22.22%  |
| WDC                 | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 2      | 11.11%  |
| Crucial             | 1         | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3380      | 4553   | 63.8%   |
| Detected | 1416      | 2130   | 26.73%  |
| Malfunc  | 492       | 533    | 9.29%   |
| Failed   | 9         | 10     | 0.17%   |
| Limited  | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2991      | 54.45%  |
| Samsung Electronics              | 554       | 10.09%  |
| AMD                              | 469       | 8.54%   |
| Nvidia                           | 377       | 6.86%   |
| SanDisk                          | 275       | 5.01%   |
| SK hynix                         | 166       | 3.02%   |
| Toshiba America Info Systems     | 96        | 1.75%   |
| Apple                            | 86        | 1.57%   |
| Micron Technology                | 82        | 1.49%   |
| Kingston Technology Company      | 73        | 1.33%   |
| KIOXIA                           | 63        | 1.15%   |
| Phison Electronics               | 44        | 0.8%    |
| ADATA Technology                 | 42        | 0.76%   |
| Silicon Motion                   | 35        | 0.64%   |
| Micron/Crucial Technology        | 34        | 0.62%   |
| Solid State Storage Technology   | 22        | 0.4%    |
| Union Memory (Shenzhen)          | 13        | 0.24%   |
| Silicon Integrated Systems [SiS] | 12        | 0.22%   |
| Realtek Semiconductor            | 8         | 0.15%   |
| Lite-On Technology               | 7         | 0.13%   |
| Shenzhen Longsys Electronics     | 5         | 0.09%   |
| Lenovo                           | 5         | 0.09%   |
| Seagate Technology               | 4         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.07%   |
| VIA Technologies                 | 3         | 0.05%   |
| ULi Electronics                  | 3         | 0.05%   |
| Silicon Image                    | 3         | 0.05%   |
| Marvell Technology Group         | 3         | 0.05%   |
| Jiangsu Huacun Elec.             | 3         | 0.05%   |
| Biwin Storage Technology         | 3         | 0.05%   |
| ASMedia Technology               | 2         | 0.04%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| Transcend                        | 1         | 0.02%   |
| JMicron Technology               | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |
| Adaptec                          | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 408       | 6.94%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 391       | 6.65%   |
| Nvidia MCP79 AHCI Controller                                                   | 362       | 6.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 331       | 5.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 229       | 3.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 226       | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 210       | 3.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 155       | 2.64%   |
| Intel Volume Management Device NVMe RAID Controller                            | 141       | 2.4%    |
| Samsung NVMe SSD Controller 980                                                | 124       | 2.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 124       | 2.11%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 112       | 1.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 100       | 1.7%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 99        | 1.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 92        | 1.57%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 87        | 1.48%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 84        | 1.43%   |
| Samsung Electronics SATA controller                                            | 83        | 1.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 83        | 1.41%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 82        | 1.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 81        | 1.38%   |
| Micron NVMe Storage Controller                                                 | 80        | 1.36%   |
| Apple S1X NVMe Controller                                                      | 78        | 1.33%   |
| Intel Comet Lake SATA AHCI Controller                                          | 74        | 1.26%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 72        | 1.23%   |
| Intel Tiger Lake-LP SATA Controller                                            | 68        | 1.16%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 65        | 1.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 63        | 1.07%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 60        | 1.02%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 59        | 1%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 57        | 0.97%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 52        | 0.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 51        | 0.87%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 50        | 0.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 48        | 0.82%   |
| Intel SSD 660P Series                                                          | 45        | 0.77%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 44        | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 42        | 0.71%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 38        | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 37        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3386      | 59.22%  |
| NVMe | 1563      | 27.33%  |
| IDE  | 393       | 6.87%   |
| RAID | 375       | 6.56%   |
| SCSI | 1         | 0.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 4231      | 85.75%  |
| AMD          | 685       | 13.88%  |
| ARM          | 11        | 0.22%   |
| CentaurHauls | 5         | 0.1%    |
| Unknown      | 2         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 356       | 7.21%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 146       | 2.96%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 95        | 1.92%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 92        | 1.86%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 78        | 1.58%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 74        | 1.5%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 72        | 1.46%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 70        | 1.42%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 70        | 1.42%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 63        | 1.28%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 63        | 1.28%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 61        | 1.24%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 61        | 1.24%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 57        | 1.15%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 54        | 1.09%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 50        | 1.01%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 50        | 1.01%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 48        | 0.97%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 45        | 0.91%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 43        | 0.87%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 41        | 0.83%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 40        | 0.81%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 39        | 0.79%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 38        | 0.77%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 37        | 0.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 34        | 0.69%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 30        | 0.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 30        | 0.61%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 30        | 0.61%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 29        | 0.59%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 29        | 0.59%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 29        | 0.59%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 28        | 0.57%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 26        | 0.53%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 25        | 0.51%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 25        | 0.51%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 25        | 0.51%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 25        | 0.51%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 24        | 0.49%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 24        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1207      | 24.45%  |
| Intel Core i7           | 925       | 18.74%  |
| Intel Core 2 Duo        | 548       | 11.1%   |
| Other                   | 417       | 8.45%   |
| Intel Celeron           | 355       | 7.19%   |
| Intel Core i3           | 334       | 6.77%   |
| AMD Ryzen 5             | 195       | 3.95%   |
| Intel Atom              | 141       | 2.86%   |
| AMD Ryzen 7             | 119       | 2.41%   |
| Intel Pentium           | 90        | 1.82%   |
| Intel Core 2            | 72        | 1.46%   |
| AMD Ryzen 7 PRO         | 46        | 0.93%   |
| AMD A6                  | 37        | 0.75%   |
| Intel Pentium M         | 34        | 0.69%   |
| Intel Pentium Dual-Core | 33        | 0.67%   |
| AMD A4                  | 27        | 0.55%   |
| Intel Genuine           | 25        | 0.51%   |
| AMD Ryzen 3             | 22        | 0.45%   |
| AMD A8                  | 22        | 0.45%   |
| Intel Pentium Dual      | 21        | 0.43%   |
| AMD Ryzen 5 PRO         | 21        | 0.43%   |
| AMD Ryzen 9             | 19        | 0.38%   |
| AMD E1                  | 17        | 0.34%   |
| AMD A10                 | 15        | 0.3%    |
| AMD E                   | 14        | 0.28%   |
| Intel Celeron M         | 13        | 0.26%   |
| AMD E2                  | 13        | 0.26%   |
| Intel Pentium Silver    | 11        | 0.22%   |
| Intel Core i9           | 10        | 0.2%    |
| Intel Pentium 4         | 9         | 0.18%   |
| Intel Core m3           | 8         | 0.16%   |
| AMD A12                 | 7         | 0.14%   |
| Intel Xeon              | 6         | 0.12%   |
| AMD Turion 64 X2 Mobile | 6         | 0.12%   |
| AMD Athlon              | 6         | 0.12%   |
| Intel Core m7           | 5         | 0.1%    |
| Intel Celeron Dual-Core | 5         | 0.1%    |
| ARM ARMv7               | 5         | 0.1%    |
| AMD C-60                | 5         | 0.1%    |
| AMD C-50                | 5         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2727      | 55.24%  |
| 4      | 1445      | 29.27%  |
| 6      | 265       | 5.37%   |
| 8      | 206       | 4.17%   |
| 1      | 200       | 4.05%   |
| 10     | 38        | 0.77%   |
| 14     | 33        | 0.67%   |
| 12     | 21        | 0.43%   |
| 16     | 1         | 0.02%   |
| 3      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4932      | 99.98%  |
| 2      | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3284      | 66.5%   |
| 1      | 1653      | 33.48%  |
| 4      | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4740      | 96.05%  |
| 32-bit         | 122       | 2.47%   |
| Unknown        | 71        | 1.44%   |
| 64-bit         | 2         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1028      | 20.37%  |
| 0x1067a    | 460       | 9.12%   |
| 0x306d4    | 259       | 5.13%   |
| 0x306a9    | 237       | 4.7%    |
| 0x206a7    | 218       | 4.32%   |
| 0x806ec    | 200       | 3.96%   |
| 0x806c1    | 194       | 3.84%   |
| 0x806e9    | 143       | 2.83%   |
| 0x806ea    | 134       | 2.66%   |
| 0x40651    | 132       | 2.62%   |
| 0x406e3    | 123       | 2.44%   |
| 0x30678    | 122       | 2.42%   |
| 0x306c3    | 85        | 1.68%   |
| 0x906ea    | 76        | 1.51%   |
| 0x406c4    | 73        | 1.45%   |
| 0xa0652    | 71        | 1.41%   |
| 0x20655    | 70        | 1.39%   |
| 0x6f6      | 68        | 1.35%   |
| 0x0a50000c | 62        | 1.23%   |
| 0x08600106 | 57        | 1.13%   |
| 0x08108109 | 54        | 1.07%   |
| 0x08608103 | 52        | 1.03%   |
| 0x906a3    | 50        | 0.99%   |
| 0x906eb    | 48        | 0.95%   |
| 0x706e5    | 48        | 0.95%   |
| 0x10676    | 47        | 0.93%   |
| 0x08108102 | 47        | 0.93%   |
| 0x6fd      | 43        | 0.85%   |
| 0x706a8    | 40        | 0.79%   |
| 0x806eb    | 39        | 0.77%   |
| 0x106ca    | 39        | 0.77%   |
| 0x506e3    | 36        | 0.71%   |
| 0x906e9    | 34        | 0.67%   |
| 0x06006705 | 34        | 0.67%   |
| 0x906a4    | 33        | 0.65%   |
| 0x106c2    | 33        | 0.65%   |
| 0x506c9    | 31        | 0.61%   |
| 0x0600611a | 31        | 0.61%   |
| 0x6d8      | 28        | 0.55%   |
| 0x20652    | 26        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 907       | 18.36%  |
| Penryn           | 541       | 10.95%  |
| IvyBridge        | 319       | 6.46%   |
| SandyBridge      | 295       | 5.97%   |
| Broadwell        | 294       | 5.95%   |
| Haswell          | 293       | 5.93%   |
| Silvermont       | 253       | 5.12%   |
| TigerLake        | 237       | 4.8%    |
| Skylake          | 222       | 4.49%   |
| Core             | 155       | 3.14%   |
| Unknown          | 135       | 2.73%   |
| Westmere         | 130       | 2.63%   |
| Zen+             | 127       | 2.57%   |
| Zen 2            | 111       | 2.25%   |
| CometLake        | 97        | 1.96%   |
| Excavator        | 89        | 1.8%    |
| Bonnell          | 89        | 1.8%    |
| Zen 3            | 86        | 1.74%   |
| Icelake          | 75        | 1.52%   |
| P6               | 71        | 1.44%   |
| Goldmont plus    | 68        | 1.38%   |
| Alderlake Hybrid | 63        | 1.28%   |
| Goldmont         | 41        | 0.83%   |
| Bobcat           | 38        | 0.77%   |
| Zen              | 36        | 0.73%   |
| Puma             | 29        | 0.59%   |
| Jaguar           | 22        | 0.45%   |
| K8 Hammer        | 18        | 0.36%   |
| K10 Llano        | 16        | 0.32%   |
| Tremont          | 14        | 0.28%   |
| Piledriver       | 14        | 0.28%   |
| NetBurst         | 14        | 0.28%   |
| Nehalem          | 14        | 0.28%   |
| K10              | 12        | 0.24%   |
| Steamroller      | 7         | 0.14%   |
| K8 & K10 hybrid  | 7         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3593      | 60.45%  |
| Nvidia                           | 1389      | 23.37%  |
| AMD                              | 946       | 15.92%  |
| Silicon Integrated Systems [SiS] | 7         | 0.12%   |
| Zhaoxin                          | 4         | 0.07%   |
| VIA Technologies                 | 2         | 0.03%   |
| S3 Graphics                      | 2         | 0.03%   |
| Neomagic                         | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 354       | 5.71%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 294       | 4.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 265       | 4.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 211       | 3.4%    |
| Intel UHD Graphics 620                                                                   | 196       | 3.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 170       | 2.74%   |
| Intel HD Graphics 620                                                                    | 165       | 2.66%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 158       | 2.55%   |
| Intel HD Graphics 6000                                                                   | 154       | 2.48%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 151       | 2.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 144       | 2.32%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 138       | 2.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 131       | 2.11%   |
| Intel HD Graphics 5500                                                                   | 125       | 2.02%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 116       | 1.87%   |
| AMD Renoir                                                                               | 109       | 1.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 108       | 1.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 105       | 1.69%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 102       | 1.64%   |
| Intel Core Processor Integrated Graphics Controller                                      | 99        | 1.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 97        | 1.56%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 81        | 1.31%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 78        | 1.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 78        | 1.26%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 77        | 1.24%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 76        | 1.23%   |
| AMD Lucienne                                                                             | 64        | 1.03%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 62        | 1%      |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 50        | 0.81%   |
| Intel HD Graphics 630                                                                    | 49        | 0.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 48        | 0.77%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 47        | 0.76%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 47        | 0.76%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 45        | 0.73%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 44        | 0.71%   |
| Intel HD Graphics 530                                                                    | 42        | 0.68%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 39        | 0.63%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 36        | 0.58%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 35        | 0.56%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 35        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2641      | 53.43%  |
| Intel + Nvidia     | 783       | 15.84%  |
| 1 x AMD            | 659       | 13.33%  |
| 1 x Nvidia         | 528       | 10.68%  |
| Intel + AMD        | 156       | 3.16%   |
| AMD + Nvidia       | 76        | 1.54%   |
| 2 x AMD            | 55        | 1.11%   |
| Other              | 23        | 0.47%   |
| 1 x SiS            | 7         | 0.14%   |
| 1 x Zhaoxin        | 4         | 0.08%   |
| 2 x Intel          | 3         | 0.06%   |
| 1 x VIA            | 2         | 0.04%   |
| 1 x S3 Graphics    | 2         | 0.04%   |
| Intel + 2 x Nvidia | 2         | 0.04%   |
| 2 x Nvidia         | 1         | 0.02%   |
| 1 x Neomagic       | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 4293      | 86.33%  |
| Proprietary | 347       | 6.98%   |
| Unknown     | 333       | 6.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 3613      | 72.35%  |
| 0.01-0.5       | 743       | 14.88%  |
| 1.01-2.0       | 270       | 5.41%   |
| 0.51-1.0       | 151       | 3.02%   |
| 3.01-4.0       | 149       | 2.98%   |
| 5.01-6.0       | 32        | 0.64%   |
| 7.01-8.0       | 26        | 0.52%   |
| 2.01-3.0       | 8         | 0.16%   |
| More than 64.0 | 1         | 0.02%   |
| 8.01-16.0      | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 935       | 17.6%   |
| BOE                     | 692       | 13.02%  |
| Apple                   | 648       | 12.2%   |
| LG Display              | 646       | 12.16%  |
| Chimei Innolux          | 597       | 11.24%  |
| Samsung Electronics     | 435       | 8.19%   |
| Dell                    | 142       | 2.67%   |
| Lenovo                  | 126       | 2.37%   |
| Sharp                   | 110       | 2.07%   |
| Goldstar                | 102       | 1.92%   |
| Chi Mei Optoelectronics | 89        | 1.68%   |
| InfoVision              | 72        | 1.36%   |
| Hewlett-Packard         | 61        | 1.15%   |
| PANDA                   | 55        | 1.04%   |
| BenQ                    | 52        | 0.98%   |
| Philips                 | 49        | 0.92%   |
| AOC                     | 40        | 0.75%   |
| Iiyama                  | 35        | 0.66%   |
| HannStar                | 35        | 0.66%   |
| LG Philips              | 34        | 0.64%   |
| Ancor Communications    | 33        | 0.62%   |
| Acer                    | 32        | 0.6%    |
| CSO                     | 30        | 0.56%   |
| Unknown                 | 25        | 0.47%   |
| ViewSonic               | 21        | 0.4%    |
| Sony                    | 19        | 0.36%   |
| CPT                     | 16        | 0.3%    |
| Eizo                    | 14        | 0.26%   |
| Quanta Display          | 10        | 0.19%   |
| ASUSTek Computer        | 9         | 0.17%   |
| Panasonic               | 8         | 0.15%   |
| NEC Computers           | 8         | 0.15%   |
| MSI                     | 7         | 0.13%   |
| LGD                     | 6         | 0.11%   |
| Pixio                   | 5         | 0.09%   |
| InnoLux Display         | 5         | 0.09%   |
| TMX                     | 4         | 0.08%   |
| Fujitsu Siemens         | 4         | 0.08%   |
| AGO                     | 4         | 0.08%   |
| Unknown                 | 4         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                 | 210       | 3.91%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 189       | 3.52%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                 | 54        | 1%      |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 45        | 0.84%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 44        | 0.82%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 43        | 0.8%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 41        | 0.76%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 41        | 0.76%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                 | 38        | 0.71%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                 | 29        | 0.54%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 28        | 0.52%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 27        | 0.5%    |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 26        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 25        | 0.47%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 25        | 0.47%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch             | 24        | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 23        | 0.43%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 23        | 0.43%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                 | 22        | 0.41%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 21        | 0.39%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 20        | 0.37%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 19        | 0.35%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 17        | 0.32%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 17        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 16        | 0.3%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 16        | 0.3%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 16        | 0.3%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 16        | 0.3%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 15        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 14        | 0.26%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 14        | 0.26%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 14        | 0.26%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 14        | 0.26%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                | 13        | 0.24%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 13        | 0.24%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch       | 13        | 0.24%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 12        | 0.22%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch       | 12        | 0.22%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 12        | 0.22%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch        | 12        | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1915      | 38.18%  |
| 1366x768 (WXGA)    | 1385      | 27.61%  |
| 1280x800 (WXGA)    | 579       | 11.54%  |
| 1600x900 (HD+)     | 212       | 4.23%   |
| 1440x900 (WXGA+)   | 143       | 2.85%   |
| 3840x2160 (4K)     | 140       | 2.79%   |
| 1920x1200 (WUXGA)  | 108       | 2.15%   |
| 2560x1440 (QHD)    | 107       | 2.13%   |
| 1024x600           | 69        | 1.38%   |
| 1280x1024 (SXGA)   | 38        | 0.76%   |
| 2560x1600          | 36        | 0.72%   |
| 1680x1050 (WSXGA+) | 34        | 0.68%   |
| 3840x2400          | 26        | 0.52%   |
| 2560x1080          | 26        | 0.52%   |
| 2288x1287          | 21        | 0.42%   |
| 1360x768           | 21        | 0.42%   |
| 3440x1440          | 19        | 0.38%   |
| 2880x1800          | 19        | 0.38%   |
| 1024x768 (XGA)     | 19        | 0.38%   |
| 3200x1800 (QHD+)   | 11        | 0.22%   |
| 2160x1440          | 9         | 0.18%   |
| Unknown            | 9         | 0.18%   |
| 1600x1200          | 8         | 0.16%   |
| 3840x1080          | 6         | 0.12%   |
| 1400x1050          | 5         | 0.1%    |
| 1280x720 (HD)      | 5         | 0.1%    |
| 2256x1504          | 4         | 0.08%   |
| 3840x1200          | 3         | 0.06%   |
| 3840x1100          | 3         | 0.06%   |
| 3072x1920          | 3         | 0.06%   |
| 2880x1920          | 3         | 0.06%   |
| 2304x1440          | 3         | 0.06%   |
| 2240x1400          | 3         | 0.06%   |
| 1920x540           | 3         | 0.06%   |
| 1024x576           | 3         | 0.06%   |
| 1920x1280          | 2         | 0.04%   |
| 800x1280           | 1         | 0.02%   |
| 7680x2160          | 1         | 0.02%   |
| 640x480            | 1         | 0.02%   |
| 3840x1600          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1633      | 30.72%  |
| 13      | 1207      | 22.71%  |
| 14      | 676       | 12.72%  |
| 17      | 294       | 5.53%   |
| 11      | 292       | 5.49%   |
| 12      | 191       | 3.59%   |
| 24      | 189       | 3.56%   |
| 27      | 136       | 2.56%   |
| 23      | 123       | 2.31%   |
| 21      | 109       | 2.05%   |
| 10      | 70        | 1.32%   |
| 18      | 47        | 0.88%   |
| Unknown | 47        | 0.88%   |
| 34      | 39        | 0.73%   |
| 16      | 34        | 0.64%   |
| 19      | 32        | 0.6%    |
| 31      | 30        | 0.56%   |
| 142     | 21        | 0.4%    |
| 22      | 19        | 0.36%   |
| 25      | 15        | 0.28%   |
| 20      | 14        | 0.26%   |
| 40      | 12        | 0.23%   |
| 72      | 11        | 0.21%   |
| 32      | 11        | 0.21%   |
| 54      | 8         | 0.15%   |
| 84      | 7         | 0.13%   |
| 8       | 7         | 0.13%   |
| 29      | 6         | 0.11%   |
| 28      | 5         | 0.09%   |
| 48      | 4         | 0.08%   |
| 46      | 4         | 0.08%   |
| 52      | 3         | 0.06%   |
| 49      | 3         | 0.06%   |
| 43      | 3         | 0.06%   |
| 26      | 3         | 0.06%   |
| 33      | 2         | 0.04%   |
| 65      | 1         | 0.02%   |
| 58      | 1         | 0.02%   |
| 55      | 1         | 0.02%   |
| 47      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2698      | 51.22%  |
| 201-300        | 1355      | 25.73%  |
| 501-600        | 420       | 7.97%   |
| 351-400        | 341       | 6.47%   |
| 401-500        | 202       | 3.84%   |
| 601-700        | 61        | 1.16%   |
| 701-800        | 51        | 0.97%   |
| Unknown        | 47        | 0.89%   |
| 1001-1500      | 29        | 0.55%   |
| More than 2000 | 21        | 0.4%    |
| 1501-2000      | 18        | 0.34%   |
| 801-900        | 14        | 0.27%   |
| 101-200        | 8         | 0.15%   |
| 901-1000       | 1         | 0.02%   |
| 1-100          | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3583      | 75.4%   |
| 16/10   | 952       | 20.03%  |
| 21/9    | 42        | 0.88%   |
| 5/4     | 38        | 0.8%    |
| 4/3     | 37        | 0.78%   |
| 3/2     | 32        | 0.67%   |
| Unknown | 30        | 0.63%   |
| 1.00    | 21        | 0.44%   |
| 32/9    | 4         | 0.08%   |
| 2.65    | 4         | 0.08%   |
| 3.40    | 3         | 0.06%   |
| 3.20    | 3         | 0.06%   |
| 6/5     | 1         | 0.02%   |
| 3.73    | 1         | 0.02%   |
| 1.96    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1624      | 30.64%  |
| 81-90          | 1569      | 29.6%   |
| 201-250        | 336       | 6.34%   |
| 71-80          | 307       | 5.79%   |
| 51-60          | 295       | 5.57%   |
| 121-130        | 233       | 4.4%    |
| 61-70          | 185       | 3.49%   |
| 301-350        | 137       | 2.58%   |
| 351-500        | 88        | 1.66%   |
| 251-300        | 82        | 1.55%   |
| 151-200        | 79        | 1.49%   |
| 41-50          | 70        | 1.32%   |
| 141-150        | 65        | 1.23%   |
| More than 1000 | 56        | 1.06%   |
| Unknown        | 47        | 0.89%   |
| 131-140        | 38        | 0.72%   |
| 111-120        | 33        | 0.62%   |
| 501-1000       | 26        | 0.49%   |
| 91-100         | 21        | 0.4%    |
| 1-40           | 9         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2163      | 41.6%   |
| 101-120       | 1753      | 33.71%  |
| 51-100        | 745       | 14.33%  |
| 161-240       | 321       | 6.17%   |
| More than 240 | 107       | 2.06%   |
| 1-50          | 64        | 1.23%   |
| Unknown       | 47        | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3907      | 77.43%  |
| 2     | 735       | 14.57%  |
| 0     | 323       | 6.4%    |
| 3     | 79        | 1.57%   |
| 5     | 1         | 0.02%   |
| 4     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2479      | 31.12%  |
| Realtek Semiconductor             | 2176      | 27.32%  |
| Qualcomm Atheros                  | 1032      | 12.96%  |
| Broadcom                          | 749       | 9.4%    |
| Nvidia                            | 372       | 4.67%   |
| Broadcom Limited                  | 259       | 3.25%   |
| Marvell Technology Group          | 147       | 1.85%   |
| MediaTek                          | 85        | 1.07%   |
| Ralink                            | 62        | 0.78%   |
| ASIX Electronics                  | 61        | 0.77%   |
| TP-Link                           | 44        | 0.55%   |
| Dell                              | 42        | 0.53%   |
| Sierra Wireless                   | 35        | 0.44%   |
| Samsung Electronics               | 34        | 0.43%   |
| Lenovo                            | 33        | 0.41%   |
| JMicron Technology                | 30        | 0.38%   |
| Xiaomi                            | 27        | 0.34%   |
| Ralink Technology                 | 26        | 0.33%   |
| Ericsson Business Mobile Networks | 26        | 0.33%   |
| Qualcomm                          | 22        | 0.28%   |
| DisplayLink                       | 19        | 0.24%   |
| Huawei Technologies               | 17        | 0.21%   |
| Hewlett-Packard                   | 16        | 0.2%    |
| Fibocom                           | 13        | 0.16%   |
| Silicon Integrated Systems [SiS]  | 11        | 0.14%   |
| Qualcomm Atheros Communications   | 9         | 0.11%   |
| NetGear                           | 9         | 0.11%   |
| OPPO Electronics                  | 8         | 0.1%    |
| Cypress Semiconductor             | 8         | 0.1%    |
| ASUSTek Computer                  | 7         | 0.09%   |
| ICS Advent                        | 6         | 0.08%   |
| Attansic Technology               | 6         | 0.08%   |
| Apple                             | 6         | 0.08%   |
| Motorola PCS                      | 5         | 0.06%   |
| Microchip Technology              | 5         | 0.06%   |
| Edimax Technology                 | 5         | 0.06%   |
| D-Link                            | 5         | 0.06%   |
| AMD                               | 5         | 0.06%   |
| U-Blox                            | 4         | 0.05%   |
| Spreadtrum Communications         | 4         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 1324      | 13.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 379       | 3.99%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 364       | 3.83%   |
| Nvidia MCP79 Ethernet                                                                 | 362       | 3.81%   |
| Intel Wireless 7260                                                                   | 216       | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 215       | 2.26%   |
| Intel Wireless 8265 / 8275                                                            | 201       | 2.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 199       | 2.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 189       | 1.99%   |
| Intel Wi-Fi 6 AX200                                                                   | 179       | 1.88%   |
| Intel Wireless 7265                                                                   | 178       | 1.87%   |
| Intel Wi-Fi 6 AX201                                                                   | 168       | 1.77%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 161       | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 156       | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 138       | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 123       | 1.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 122       | 1.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 118       | 1.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 113       | 1.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 109       | 1.15%   |
| Intel Wireless 8260                                                                   | 108       | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 100       | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 98        | 1.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 85        | 0.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 82        | 0.86%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 77        | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 75        | 0.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 71        | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 70        | 0.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 63        | 0.66%   |
| Intel Wireless 3165                                                                   | 63        | 0.66%   |
| Intel Ethernet Connection (4) I219-V                                                  | 63        | 0.66%   |
| Intel Ethernet Connection I218-LM                                                     | 61        | 0.64%   |
| Intel Ethernet Connection I219-LM                                                     | 60        | 0.63%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 59        | 0.62%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 58        | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 57        | 0.6%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 54        | 0.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 52        | 0.55%   |
| ASIX AX88179 Gigabit Ethernet                                                         | 51        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2340      | 46.34%  |
| Qualcomm Atheros                      | 925       | 18.32%  |
| Broadcom                              | 631       | 12.5%   |
| Realtek Semiconductor                 | 606       | 12%     |
| Broadcom Limited                      | 217       | 4.3%    |
| MediaTek                              | 79        | 1.56%   |
| Ralink                                | 62        | 1.23%   |
| Sierra Wireless                       | 35        | 0.69%   |
| Dell                                  | 27        | 0.53%   |
| Ralink Technology                     | 26        | 0.51%   |
| TP-Link                               | 25        | 0.5%    |
| Fibocom                               | 13        | 0.26%   |
| Qualcomm                              | 11        | 0.22%   |
| Qualcomm Atheros Communications       | 9         | 0.18%   |
| NetGear                               | 9         | 0.18%   |
| ASUSTek Computer                      | 7         | 0.14%   |
| Edimax Technology                     | 5         | 0.1%    |
| Hewlett-Packard                       | 4         | 0.08%   |
| D-Link                                | 3         | 0.06%   |
| Wilocity                              | 2         | 0.04%   |
| Quectel Wireless Solutions            | 2         | 0.04%   |
| D-Link System                         | 2         | 0.04%   |
| Belkin Components                     | 2         | 0.04%   |
| 3Com                                  | 2         | 0.04%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| Z-Com                                 | 1         | 0.02%   |
| Winbond Electronics                   | 1         | 0.02%   |
| Microsoft                             | 1         | 0.02%   |
| Cinterion                             | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 364       | 7.17%   |
| Intel Wireless 7260                                                                   | 216       | 4.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 215       | 4.24%   |
| Intel Wireless 8265 / 8275                                                            | 201       | 3.96%   |
| Intel Wi-Fi 6 AX200                                                                   | 179       | 3.53%   |
| Intel Wireless 7265                                                                   | 178       | 3.51%   |
| Intel Wi-Fi 6 AX201                                                                   | 168       | 3.31%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 161       | 3.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 156       | 3.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 138       | 2.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 123       | 2.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 122       | 2.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 118       | 2.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 113       | 2.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 109       | 2.15%   |
| Intel Wireless 8260                                                                   | 108       | 2.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 100       | 1.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 98        | 1.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 85        | 1.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 82        | 1.62%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 77        | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 75        | 1.48%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 71        | 1.4%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 63        | 1.24%   |
| Intel Wireless 3165                                                                   | 63        | 1.24%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 59        | 1.16%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 54        | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 52        | 1.02%   |
| Intel Wireless-AC 9260                                                                | 48        | 0.95%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 45        | 0.89%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 44        | 0.87%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 43        | 0.85%   |
| Intel Centrino Ultimate-N 6300                                                        | 43        | 0.85%   |
| Intel Wireless 3160                                                                   | 41        | 0.81%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 38        | 0.75%   |
| Intel Centrino Advanced-N 6200                                                        | 34        | 0.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 33        | 0.65%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 33        | 0.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 32        | 0.63%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 32        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1953      | 46.17%  |
| Intel                            | 1013      | 23.95%  |
| Nvidia                           | 372       | 8.79%   |
| Qualcomm Atheros                 | 228       | 5.39%   |
| Broadcom                         | 155       | 3.66%   |
| Marvell Technology Group         | 147       | 3.48%   |
| ASIX Electronics                 | 61        | 1.44%   |
| Broadcom Limited                 | 45        | 1.06%   |
| Lenovo                           | 33        | 0.78%   |
| JMicron Technology               | 30        | 0.71%   |
| Xiaomi                           | 27        | 0.64%   |
| TP-Link                          | 19        | 0.45%   |
| DisplayLink                      | 19        | 0.45%   |
| Samsung Electronics              | 17        | 0.4%    |
| Silicon Integrated Systems [SiS] | 11        | 0.26%   |
| Huawei Technologies              | 11        | 0.26%   |
| Qualcomm                         | 10        | 0.24%   |
| OPPO Electronics                 | 8         | 0.19%   |
| Cypress Semiconductor            | 8         | 0.19%   |
| MediaTek                         | 6         | 0.14%   |
| ICS Advent                       | 6         | 0.14%   |
| Attansic Technology              | 6         | 0.14%   |
| Apple                            | 6         | 0.14%   |
| Microchip Technology             | 5         | 0.12%   |
| Spreadtrum Communications        | 4         | 0.09%   |
| Motorola PCS                     | 4         | 0.09%   |
| Hewlett-Packard                  | 4         | 0.09%   |
| VIA Technologies                 | 2         | 0.05%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.05%   |
| National Semiconductor           | 2         | 0.05%   |
| LG Electronics                   | 2         | 0.05%   |
| D-Link                           | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.02%   |
| ULi Electronics                  | 1         | 0.02%   |
| MosChip Semiconductor            | 1         | 0.02%   |
| Linksys                          | 1         | 0.02%   |
| LeEco                            | 1         | 0.02%   |
| HTC (High Tech Computer)         | 1         | 0.02%   |
| Google                           | 1         | 0.02%   |
| Foxconn / Hon Hai                | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1324      | 30.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 379       | 8.87%   |
| Nvidia MCP79 Ethernet                                             | 362       | 8.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 199       | 4.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 189       | 4.42%   |
| Intel Ethernet Connection (4) I219-LM                             | 70        | 1.64%   |
| Intel Ethernet Connection (4) I219-V                              | 63        | 1.47%   |
| Intel Ethernet Connection I218-LM                                 | 61        | 1.43%   |
| Intel Ethernet Connection I219-LM                                 | 60        | 1.4%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 58        | 1.36%   |
| Intel Ethernet Connection (3) I218-LM                             | 57        | 1.33%   |
| ASIX AX88179 Gigabit Ethernet                                     | 51        | 1.19%   |
| Intel 82577LM Gigabit Network Connection                          | 45        | 1.05%   |
| Intel Ethernet Connection (6) I219-V                              | 41        | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 39        | 0.91%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 37        | 0.87%   |
| Intel 82567LM Gigabit Network Connection                          | 36        | 0.84%   |
| Intel Ethernet Connection (13) I219-V                             | 35        | 0.82%   |
| Intel Ethernet Connection I219-V                                  | 31        | 0.73%   |
| Intel Ethernet Connection I217-LM                                 | 31        | 0.73%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 29        | 0.68%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 28        | 0.66%   |
| Intel Ethernet Connection (10) I219-V                             | 26        | 0.61%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 25        | 0.58%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 24        | 0.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 23        | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 21        | 0.49%   |
| Intel 82579V Gigabit Network Connection                           | 21        | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 20        | 0.47%   |
| Intel Ethernet Connection (6) I219-LM                             | 20        | 0.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 19        | 0.44%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 18        | 0.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 18        | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 17        | 0.4%    |
| Intel Ethernet Connection (16) I219-V                             | 17        | 0.4%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 16        | 0.37%   |
| Intel Ethernet Connection (7) I219-LM                             | 16        | 0.37%   |
| Intel Ethernet Connection (13) I219-LM                            | 16        | 0.37%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 15        | 0.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 15        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4840      | 53.62%  |
| Ethernet | 4036      | 44.72%  |
| Modem    | 142       | 1.57%   |
| Unknown  | 8         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3720      | 71.33%  |
| Ethernet | 1495      | 28.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3651      | 73.88%  |
| 1     | 1167      | 23.61%  |
| 0     | 75        | 1.52%   |
| 3     | 47        | 0.95%   |
| 5     | 1         | 0.02%   |
| 4     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4146      | 82.9%   |
| Yes  | 855       | 17.1%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1772      | 44.2%   |
| Apple                           | 635       | 15.84%  |
| Realtek Semiconductor           | 351       | 8.76%   |
| Qualcomm Atheros Communications | 349       | 8.71%   |
| Broadcom                        | 192       | 4.79%   |
| Lite-On Technology              | 153       | 3.82%   |
| IMC Networks                    | 150       | 3.74%   |
| Foxconn / Hon Hai               | 103       | 2.57%   |
| Dell                            | 67        | 1.67%   |
| Cambridge Silicon Radio         | 47        | 1.17%   |
| Hewlett-Packard                 | 45        | 1.12%   |
| Toshiba                         | 29        | 0.72%   |
| ASUSTek Computer                | 28        | 0.7%    |
| Realtek                         | 24        | 0.6%    |
| Ralink                          | 19        | 0.47%   |
| Foxconn International           | 9         | 0.22%   |
| Ralink Technology               | 8         | 0.2%    |
| Alps Electric                   | 6         | 0.15%   |
| MediaTek                        | 4         | 0.1%    |
| Taiyo Yuden                     | 3         | 0.07%   |
| Fujitsu                         | 2         | 0.05%   |
| Chicony Electronics             | 2         | 0.05%   |
| Askey Computer                  | 2         | 0.05%   |
| USI                             | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |
| Smart Modular Technologies      | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Opticis                         | 1         | 0.02%   |
| Edimax Technology               | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |
| Belkin Components               | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 753       | 18.76%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 351       | 8.74%   |
| Intel AX201 Bluetooth                               | 333       | 8.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 283       | 7.05%   |
| Realtek Bluetooth Radio                             | 220       | 5.48%   |
| Qualcomm Atheros  Bluetooth Device                  | 202       | 5.03%   |
| Intel AX200 Bluetooth                               | 170       | 4.24%   |
| Apple Bluetooth USB Host Controller                 | 160       | 3.99%   |
| Intel Bluetooth Device                              | 89        | 2.22%   |
| Realtek  Bluetooth 4.2 Adapter                      | 85        | 2.12%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 1.89%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 55        | 1.37%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 49        | 1.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 47        | 1.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 45        | 1.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 42        | 1.05%   |
| IMC Networks Bluetooth Radio                        | 41        | 1.02%   |
| Apple Bluetooth Host Controller                     | 41        | 1.02%   |
| Broadcom BCM2045B (BDC-2.1)                         | 40        | 1%      |
| IMC Networks Bluetooth Device                       | 39        | 0.97%   |
| Lite-On Bluetooth Device                            | 38        | 0.95%   |
| Foxconn / Hon Hai Bluetooth Device                  | 38        | 0.95%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 37        | 0.92%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 34        | 0.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 33        | 0.82%   |
| Intel Wireless-AC 3168 Bluetooth                    | 32        | 0.8%    |
| IMC Networks Wireless_Device                        | 28        | 0.7%    |
| Intel AX210 Bluetooth                               | 25        | 0.62%   |
| Realtek Bluetooth Radio                             | 24        | 0.6%    |
| Lite-On Atheros AR3012 Bluetooth                    | 23        | 0.57%   |
| Realtek RTL8723B Bluetooth                          | 21        | 0.52%   |
| Dell DW375 Bluetooth Module                         | 21        | 0.52%   |
| Dell BCM20702A0 Bluetooth Module                    | 21        | 0.52%   |
| HP Broadcom 2070 Bluetooth Combo                    | 20        | 0.5%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 20        | 0.5%    |
| Ralink RT3290 Bluetooth                             | 19        | 0.47%   |
| Lite-On Wireless_Device                             | 17        | 0.42%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 17        | 0.42%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 14        | 0.35%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 14        | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3785      | 65.98%  |
| Nvidia                                       | 848       | 14.78%  |
| AMD                                          | 756       | 13.18%  |
| C-Media Electronics                          | 41        | 0.71%   |
| Logitech                                     | 31        | 0.54%   |
| Lenovo                                       | 30        | 0.52%   |
| Realtek Semiconductor                        | 28        | 0.49%   |
| Texas Instruments                            | 19        | 0.33%   |
| Plantronics                                  | 18        | 0.31%   |
| GN Netcom                                    | 17        | 0.3%    |
| Silicon Integrated Systems [SiS]             | 12        | 0.21%   |
| Hewlett-Packard                              | 12        | 0.21%   |
| Generalplus Technology                       | 10        | 0.17%   |
| ASUSTek Computer                             | 9         | 0.16%   |
| JMTek                                        | 7         | 0.12%   |
| Creative Technology                          | 7         | 0.12%   |
| Zoran Co. Personal Media Division (Nogatech) | 6         | 0.1%    |
| Kingston Technology                          | 5         | 0.09%   |
| Focusrite-Novation                           | 5         | 0.09%   |
| Zhaoxin                                      | 4         | 0.07%   |
| RODE Microphones                             | 4         | 0.07%   |
| Razer USA                                    | 4         | 0.07%   |
| Dell                                         | 4         | 0.07%   |
| VIA Technologies                             | 3         | 0.05%   |
| ULi Electronics                              | 3         | 0.05%   |
| Sennheiser Communications                    | 3         | 0.05%   |
| Microsoft                                    | 3         | 0.05%   |
| BEHRINGER International                      | 3         | 0.05%   |
| Apple                                        | 3         | 0.05%   |
| XMOS                                         | 2         | 0.03%   |
| SteelSeries ApS                              | 2         | 0.03%   |
| Sony                                         | 2         | 0.03%   |
| SAVITECH                                     | 2         | 0.03%   |
| M-Audio                                      | 2         | 0.03%   |
| ESS Technology                               | 2         | 0.03%   |
| Conexant Systems                             | 2         | 0.03%   |
| CMX Systems                                  | 2         | 0.03%   |
| Blue Microphones                             | 2         | 0.03%   |
| Beyerdynamic                                 | 2         | 0.03%   |
| Yamaha                                       | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 565       | 8.16%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 421       | 6.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 376       | 5.43%   |
| Nvidia MCP79 High Definition Audio                                                                | 364       | 5.26%   |
| Intel Broadwell-U Audio Controller                                                                | 294       | 4.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 290       | 4.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 237       | 3.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 235       | 3.39%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 217       | 3.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 179       | 2.59%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 174       | 2.51%   |
| Intel 8 Series HD Audio Controller                                                                | 174       | 2.51%   |
| Intel Cannon Lake PCH cAVS                                                                        | 164       | 2.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 159       | 2.3%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 156       | 2.25%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 149       | 2.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 143       | 2.07%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 138       | 1.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 120       | 1.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 118       | 1.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 103       | 1.49%   |
| AMD FCH Azalia Controller                                                                         | 103       | 1.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 101       | 1.46%   |
| AMD Kabini HDMI/DP Audio                                                                          | 96        | 1.39%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 89        | 1.29%   |
| Intel Comet Lake PCH cAVS                                                                         | 88        | 1.27%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 85        | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 84        | 1.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 68        | 0.98%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 67        | 0.97%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 58        | 0.84%   |
| Intel CM238 HD Audio Controller                                                                   | 54        | 0.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 53        | 0.77%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 50        | 0.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 45        | 0.65%   |
| AMD High Definition Audio Controller                                                              | 44        | 0.64%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 43        | 0.62%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 41        | 0.59%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 34        | 0.49%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 33        | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 1323      | 27.89%  |
| Samsung Electronics | 1256      | 26.48%  |
| Micron Technology   | 540       | 11.39%  |
| Kingston            | 332       | 7%      |
| Unknown             | 327       | 6.89%   |
| Crucial             | 231       | 4.87%   |
| Elpida              | 137       | 2.89%   |
| A-DATA Technology   | 100       | 2.11%   |
| Ramaxel Technology  | 86        | 1.81%   |
| Nanya Technology    | 51        | 1.08%   |
| Corsair             | 49        | 1.03%   |
| Smart               | 38        | 0.8%    |
| Unknown (ABCD)      | 36        | 0.76%   |
| GOODRAM             | 25        | 0.53%   |
| Transcend           | 19        | 0.4%    |
| G.Skill             | 19        | 0.4%    |
| Unknown             | 18        | 0.38%   |
| Team                | 16        | 0.34%   |
| Teikon              | 10        | 0.21%   |
| Silicon Power       | 9         | 0.19%   |
| ASint Technology    | 8         | 0.17%   |
| Apacer              | 8         | 0.17%   |
| 48spaces            | 8         | 0.17%   |
| Patriot             | 7         | 0.15%   |
| Smart Brazil        | 6         | 0.13%   |
| Qimonda             | 4         | 0.08%   |
| PNY                 | 4         | 0.08%   |
| Neo Forza           | 4         | 0.08%   |
| AMD                 | 4         | 0.08%   |
| Wilk                | 3         | 0.06%   |
| Timetec             | 3         | 0.06%   |
| Infineon            | 3         | 0.06%   |
| Goldkey             | 3         | 0.06%   |
| fef5                | 3         | 0.06%   |
| CSX                 | 3         | 0.06%   |
| Avant               | 3         | 0.06%   |
| Unknown (89F7)      | 2         | 0.04%   |
| Unifosa             | 2         | 0.04%   |
| TEXTORM             | 2         | 0.04%   |
| Shenzhen WODPOSIT   | 2         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 264       | 5.28%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 1.36%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 67        | 1.34%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 63        | 1.26%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 48        | 0.96%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 48        | 0.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 47        | 0.94%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 43        | 0.86%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 41        | 0.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 41        | 0.82%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 41        | 0.82%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 40        | 0.8%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 40        | 0.8%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 40        | 0.8%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 39        | 0.78%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 38        | 0.76%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 36        | 0.72%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 33        | 0.66%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 33        | 0.66%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 30        | 0.6%    |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.58%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 28        | 0.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 27        | 0.54%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 27        | 0.54%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 26        | 0.52%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 25        | 0.5%    |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 25        | 0.5%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 25        | 0.5%    |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.5%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 24        | 0.48%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 23        | 0.46%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 0.46%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 0.46%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 23        | 0.46%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 22        | 0.44%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 22        | 0.44%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 21        | 0.42%   |
| Micron RAM EDF8132A3MA-GD-F 2GB LPDDR3 1600MT/s                  | 21        | 0.42%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 0.4%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 20        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1629      | 39.52%  |
| DDR3    | 1384      | 33.58%  |
| DDR2    | 606       | 14.7%   |
| LPDDR4  | 149       | 3.61%   |
| LPDDR3  | 138       | 3.35%   |
| SDRAM   | 86        | 2.09%   |
| DDR     | 44        | 1.07%   |
| Unknown | 29        | 0.7%    |
| DDR5    | 25        | 0.61%   |
| LPDDR5  | 21        | 0.51%   |
| DRAM    | 10        | 0.24%   |
| RAM     | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 3748      | 90.88%  |
| Row Of Chips | 271       | 6.57%   |
| Unknown      | 61        | 1.48%   |
| Chip         | 30        | 0.73%   |
| DIMM         | 14        | 0.34%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1387      | 31.08%  |
| 4096  | 1175      | 26.33%  |
| 2048  | 692       | 15.51%  |
| 1024  | 558       | 12.5%   |
| 16384 | 491       | 11%     |
| 32768 | 94        | 2.11%   |
| 512   | 45        | 1.01%   |
| 256   | 17        | 0.38%   |
| 128   | 2         | 0.04%   |
| 8072  | 1         | 0.02%   |
| 384   | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 1053      | 23.94%  |
| 2667    | 757       | 17.21%  |
| 3200    | 656       | 14.92%  |
| 800     | 391       | 8.89%   |
| 2400    | 270       | 6.14%   |
| 2133    | 187       | 4.25%   |
| 667     | 185       | 4.21%   |
| 1334    | 177       | 4.02%   |
| 1333    | 136       | 3.09%   |
| Unknown | 108       | 2.46%   |
| 1067    | 61        | 1.39%   |
| 4267    | 57        | 1.3%    |
| 1867    | 51        | 1.16%   |
| 3266    | 40        | 0.91%   |
| 4199    | 32        | 0.73%   |
| 1066    | 30        | 0.68%   |
| 4800    | 29        | 0.66%   |
| 533     | 23        | 0.52%   |
| 6400    | 21        | 0.48%   |
| 975     | 20        | 0.45%   |
| 2048    | 19        | 0.43%   |
| 8400    | 16        | 0.36%   |
| 4266    | 13        | 0.3%    |
| 400     | 11        | 0.25%   |
| 3733    | 9         | 0.2%    |
| 333     | 9         | 0.2%    |
| 1866    | 8         | 0.18%   |
| 266     | 8         | 0.18%   |
| 2666    | 4         | 0.09%   |
| 933     | 4         | 0.09%   |
| 2933    | 2         | 0.05%   |
| 1776    | 2         | 0.05%   |
| 1639    | 2         | 0.05%   |
| 3000    | 1         | 0.02%   |
| 2134    | 1         | 0.02%   |
| 1596    | 1         | 0.02%   |
| 200     | 1         | 0.02%   |
| 166     | 1         | 0.02%   |
| 133     | 1         | 0.02%   |
| 100     | 1         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 12        | 37.5%   |
| Canon               | 5         | 15.63%  |
| Xerox               | 4         | 12.5%   |
| Brother Industries  | 3         | 9.38%   |
| Samsung Electronics | 2         | 6.25%   |
| Kyocera             | 2         | 6.25%   |
| Xiaomi              | 1         | 3.13%   |
| STMicroelectronics  | 1         | 3.13%   |
| Seiko Epson         | 1         | 3.13%   |
| Pantum              | 1         | 3.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Xerox B205                                                | 4         | 12.12%  |
| Xiaomi MiMouse 2                                          | 1         | 3.03%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.03%   |
| Seiko Epson L120 Series                                   | 1         | 3.03%   |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 3.03%   |
| Samsung CLX-3300 Series                                   | 1         | 3.03%   |
| Pantum P2500W series                                      | 1         | 3.03%   |
| Kyocera FS-1120MFP                                        | 1         | 3.03%   |
| Kyocera ECOSYS P2335d                                     | 1         | 3.03%   |
| HP OfficeJet 3830 series                                  | 1         | 3.03%   |
| HP LaserJet P1102                                         | 1         | 3.03%   |
| HP LaserJet P1005                                         | 1         | 3.03%   |
| HP LaserJet 1200                                          | 1         | 3.03%   |
| HP LaserJet 1160 series                                   | 1         | 3.03%   |
| HP LaserJet 1150                                          | 1         | 3.03%   |
| HP LaserJet 1022                                          | 1         | 3.03%   |
| HP LaserJet 1020                                          | 1         | 3.03%   |
| HP Ink Tank 110 series                                    | 1         | 3.03%   |
| HP EWS UPD                                                | 1         | 3.03%   |
| HP DeskJet 2600 series                                    | 1         | 3.03%   |
| HP Deskjet 2540 series                                    | 1         | 3.03%   |
| HP DeskJet 2130 series                                    | 1         | 3.03%   |
| Canon PIXMA MX920 Series                                  | 1         | 3.03%   |
| Canon LiDE 300                                            | 1         | 3.03%   |
| Canon LBP3010/LBP3018/LBP3050                             | 1         | 3.03%   |
| Canon LBP2900                                             | 1         | 3.03%   |
| Canon G3010 series                                        | 1         | 3.03%   |
| Brother PT-9500PC                                         | 1         | 3.03%   |
| Brother MFC-L2707DW                                       | 1         | 3.03%   |
| Brother HL-L2340D series                                  | 1         | 3.03%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 41.67%  |
| Seiko Epson     | 4         | 33.33%  |
| Mustek Systems  | 2         | 16.67%  |
| Hewlett-Packard | 1         | 8.33%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 120                           | 2         | 16.67%  |
| Seiko Epson GT-9800F [Perfection 3200]            | 1         | 8.33%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]     | 1         | 8.33%   |
| Seiko Epson GT-7700U [Perfection 1240U]           | 1         | 8.33%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 8.33%   |
| Mustek Systems SNAPSCAN e22                       | 1         | 8.33%   |
| Mustek Systems BearPaw 2400 CU Plus               | 1         | 8.33%   |
| HP Scanjet 200                                    | 1         | 8.33%   |
| Canon CanoScan LIDE 25                            | 1         | 8.33%   |
| Canon CanoScan LiDE 220                           | 1         | 8.33%   |
| Canon CanoScan LiDE 110                           | 1         | 8.33%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 939       | 24.38%  |
| IMC Networks                           | 428       | 11.11%  |
| Microdia                               | 314       | 8.15%   |
| Realtek Semiconductor                  | 313       | 8.13%   |
| Quanta                                 | 284       | 7.37%   |
| Sunplus Innovation Technology          | 209       | 5.43%   |
| Acer                                   | 195       | 5.06%   |
| Bison Electronics                      | 187       | 4.86%   |
| Cheng Uei Precision Industry (Foxlink) | 125       | 3.25%   |
| Suyin                                  | 124       | 3.22%   |
| Lite-On Technology                     | 98        | 2.54%   |
| Syntek                                 | 85        | 2.21%   |
| Luxvisions Innotech Limited            | 73        | 1.9%    |
| Apple                                  | 65        | 1.69%   |
| Silicon Motion                         | 54        | 1.4%    |
| Logitech                               | 52        | 1.35%   |
| Alcor Micro                            | 41        | 1.06%   |
| Lenovo                                 | 35        | 0.91%   |
| Ricoh                                  | 31        | 0.8%    |
| Z-Star Microelectronics                | 19        | 0.49%   |
| Primax Electronics                     | 18        | 0.47%   |
| Sonix Technology                       | 17        | 0.44%   |
| Samsung Electronics                    | 14        | 0.36%   |
| ALi                                    | 11        | 0.29%   |
| Importek                               | 10        | 0.26%   |
| icSpring                               | 10        | 0.26%   |
| Genesys Logic                          | 8         | 0.21%   |
| SunplusIT                              | 7         | 0.18%   |
| OmniVision Technologies                | 5         | 0.13%   |
| MacroSilicon                           | 5         | 0.13%   |
| Intel                                  | 5         | 0.13%   |
| Y Media                                | 4         | 0.1%    |
| Generalplus Technology                 | 4         | 0.1%    |
| GEMBIRD                                | 4         | 0.1%    |
| Sunplus Technology                     | 3         | 0.08%   |
| Pixart Imaging                         | 3         | 0.08%   |
| Microsoft                              | 3         | 0.08%   |
| ARC International                      | 3         | 0.08%   |
| Tobii Technology AB                    | 2         | 0.05%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 254       | 6.56%   |
| Microdia Integrated_Webcam_HD                       | 150       | 3.87%   |
| IMC Networks Integrated Camera                      | 142       | 3.67%   |
| Realtek Integrated_Webcam_HD                        | 117       | 3.02%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 97        | 2.51%   |
| Chicony HD WebCam                                   | 84        | 2.17%   |
| Sunplus Integrated_Webcam_HD                        | 74        | 1.91%   |
| Quanta Chromebook HD Camera                         | 70        | 1.81%   |
| Acer BisonCam, NB Pro                               | 55        | 1.42%   |
| Chicony HP HD Camera                                | 54        | 1.39%   |
| Bison Integrated Camera                             | 53        | 1.37%   |
| Syntek Integrated Camera                            | 45        | 1.16%   |
| Chicony USB2.0 HD UVC WebCam                        | 45        | 1.16%   |
| Acer Integrated Camera                              | 45        | 1.16%   |
| Quanta HP TrueVision HD Camera                      | 41        | 1.06%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 40        | 1.03%   |
| Lite-On Integrated Camera                           | 38        | 0.98%   |
| Quanta HD User Facing                               | 36        | 0.93%   |
| Microdia Integrated Webcam                          | 34        | 0.88%   |
| Bison SunplusIT Integrated Camera                   | 32        | 0.83%   |
| Quanta VGA WebCam                                   | 31        | 0.8%    |
| Quanta HP HD Camera                                 | 30        | 0.77%   |
| Lite-On HP HD Camera                                | 29        | 0.75%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 28        | 0.72%   |
| Chicony Integrated Camera (1280x720@30)             | 27        | 0.7%    |
| Chicony HD User Facing                              | 27        | 0.7%    |
| Realtek USB Camera                                  | 26        | 0.67%   |
| Sunplus HD WebCam                                   | 25        | 0.65%   |
| Chicony USB2.0 Camera                               | 25        | 0.65%   |
| Chicony HP Truevision HD camera                     | 25        | 0.65%   |
| Realtek Integrated Webcam                           | 23        | 0.59%   |
| Bison Lenovo EasyCamera                             | 23        | 0.59%   |
| Acer HD Webcam                                      | 22        | 0.57%   |
| Chicony HP Truevision HD                            | 21        | 0.54%   |
| Chicony EasyCamera                                  | 21        | 0.54%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 21        | 0.54%   |
| Acer BisonCam,NB Pro                                | 21        | 0.54%   |
| Realtek USB2.0 HD UVC WebCam                        | 20        | 0.52%   |
| Chicony USB 2.0 Camera                              | 20        | 0.52%   |
| Chicony Lenovo EasyCamera                           | 20        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 269       | 33.01%  |
| Synaptics                          | 254       | 31.17%  |
| Shenzhen Goodix Technology         | 107       | 13.13%  |
| Upek                               | 49        | 6.01%   |
| AuthenTec                          | 47        | 5.77%   |
| Elan Microelectronics              | 40        | 4.91%   |
| LighTuning Technology              | 26        | 3.19%   |
| STMicroelectronics                 | 17        | 2.09%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.37%   |
| Samsung Electronics                | 1         | 0.12%   |
| Microsoft                          | 1         | 0.12%   |
| Focal-systems.Corp                 | 1         | 0.12%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 114       | 13.99%  |
| Shenzhen Goodix  Fingerprint Device                                        | 65        | 7.98%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 59        | 7.24%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 54        | 6.63%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 50        | 6.13%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 44        | 5.4%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 33        | 4.05%   |
| Shenzhen Goodix Fingerprint Reader                                         | 23        | 2.82%   |
| Elan ELAN:Fingerprint                                                      | 23        | 2.82%   |
| Validity Sensors Synaptics WBDI                                            | 21        | 2.58%   |
| AuthenTec AES2810                                                          | 20        | 2.45%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 19        | 2.33%   |
| Shenzhen Goodix FingerPrint                                                | 19        | 2.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 18        | 2.21%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 17        | 2.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 17        | 2.09%   |
| Elan ELAN:ARM-M4                                                           | 17        | 2.09%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 16        | 1.96%   |
| STMicroelectronics Fingerprint Reader                                      | 15        | 1.84%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 14        | 1.72%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 1.72%   |
| Validity Sensors VFS491                                                    | 12        | 1.47%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 1.23%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 10        | 1.23%   |
| Validity Sensors VFS Fingerprint sensor                                    | 9         | 1.1%    |
| Validity Sensors Fingerprint scanner                                       | 9         | 1.1%    |
| Synaptics  WBDI                                                            | 9         | 1.1%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 0.98%   |
| Synaptics UWP WBDI Device                                                  | 8         | 0.98%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 7         | 0.86%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 0.74%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 0.74%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.61%   |
| Synaptics WBDI                                                             | 5         | 0.61%   |
| Synaptics UWP WBDI                                                         | 5         | 0.61%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.49%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 0.49%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.49%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.37%   |
| Unknown                                                                    | 3         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 166       | 38.16%  |
| Alcor Micro               | 161       | 37.01%  |
| Upek                      | 31        | 7.13%   |
| O2 Micro                  | 29        | 6.67%   |
| Lenovo                    | 29        | 6.67%   |
| Gemalto (was Gemplus)     | 4         | 0.92%   |
| Yubico.com                | 3         | 0.69%   |
| Clay Logic                | 3         | 0.69%   |
| SCM Microsystems          | 2         | 0.46%   |
| Aladdin Knowledge Systems | 2         | 0.46%   |
| Advanced Card Systems     | 2         | 0.46%   |
| OmniKey                   | 1         | 0.23%   |
| Cherry                    | 1         | 0.23%   |
| C3PO                      | 1         | 0.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 158       | 36.32%  |
| Broadcom BCM5880 Secure Applications Processor                               | 50        | 11.49%  |
| Broadcom 58200                                                               | 46        | 10.57%  |
| Broadcom 5880                                                                | 40        | 9.2%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 31        | 7.13%   |
| Lenovo Integrated Smart Card Reader                                          | 29        | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 28        | 6.44%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 25        | 5.75%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 0.92%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 0.69%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 0.69%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.46%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.46%   |
| Clay Logic Nitrokey Start                                                    | 2         | 0.46%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.46%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.46%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.23%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.23%   |
| OmniKey CardMan 4321                                                         | 1         | 0.23%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.23%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.23%   |
| C3PO LTC31v2                                                                 | 1         | 0.23%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.23%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2880      | 57.22%  |
| 1     | 1614      | 32.07%  |
| 2     | 421       | 8.36%   |
| 3     | 102       | 2.03%   |
| 4     | 9         | 0.18%   |
| 5     | 6         | 0.12%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 811       | 30.13%  |
| Graphics card            | 678       | 25.19%  |
| Chipcard                 | 400       | 14.86%  |
| Multimedia controller    | 249       | 9.25%   |
| Net/wireless             | 248       | 9.21%   |
| Bluetooth                | 62        | 2.3%    |
| Camera                   | 61        | 2.27%   |
| Card reader              | 41        | 1.52%   |
| Storage                  | 37        | 1.37%   |
| Communication controller | 37        | 1.37%   |
| Sound                    | 21        | 0.78%   |
| Net/ethernet             | 18        | 0.67%   |
| Network                  | 8         | 0.3%    |
| Modem                    | 7         | 0.26%   |
| Flash memory             | 6         | 0.22%   |
| Wireless                 | 2         | 0.07%   |
| Unassigned class         | 2         | 0.07%   |
| Firewire controller      | 2         | 0.07%   |
| Tv card                  | 1         | 0.04%   |
| Storage/ide              | 1         | 0.04%   |


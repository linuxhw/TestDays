Linux in Brazil - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Brazil.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Brazil/Desktop/README.md) and [notebooks](/Location/Brazil/Notebook/README.md).

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

Total: 20084

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | AO722                       | Notebook    | [ae49a1e9c0](https://linux-hardware.org/?probe=ae49a1e9c0) | Sep 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [db4ba96400](https://linux-hardware.org/?probe=db4ba96400) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e207539e68](https://linux-hardware.org/?probe=e207539e68) | Sep 07, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [a4624a95da](https://linux-hardware.org/?probe=a4624a95da) | Sep 07, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [da21e863a4](https://linux-hardware.org/?probe=da21e863a4) | Sep 07, 2023 |
| Multilaser    | PC31X                       | Notebook    | [96d451c4a5](https://linux-hardware.org/?probe=96d451c4a5) | Sep 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [7410c2416c](https://linux-hardware.org/?probe=7410c2416c) | Sep 07, 2023 |
| Alienware     | m15 R7                      | Notebook    | [9e6b80bbf2](https://linux-hardware.org/?probe=9e6b80bbf2) | Sep 07, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [0be77d9ece](https://linux-hardware.org/?probe=0be77d9ece) | Sep 07, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [f8453df937](https://linux-hardware.org/?probe=f8453df937) | Sep 07, 2023 |
| Toshiba       | STI 006998G                 | Desktop     | [d34aadcc92](https://linux-hardware.org/?probe=d34aadcc92) | Sep 07, 2023 |
| ASRock        | Z97 Killer                  | Desktop     | [a1537a06ee](https://linux-hardware.org/?probe=a1537a06ee) | Sep 07, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [03726302da](https://linux-hardware.org/?probe=03726302da) | Sep 07, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [ef99cba7a5](https://linux-hardware.org/?probe=ef99cba7a5) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [29f1d7759a](https://linux-hardware.org/?probe=29f1d7759a) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [344a00d524](https://linux-hardware.org/?probe=344a00d524) | Sep 06, 2023 |
| Standard      | MB45II/MB45IN               | Notebook    | [1e46c6aa81](https://linux-hardware.org/?probe=1e46c6aa81) | Sep 06, 2023 |
| ASUSTek       | P8H77-M                     | Desktop     | [ebc8d3e851](https://linux-hardware.org/?probe=ebc8d3e851) | Sep 06, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [5d22a61587](https://linux-hardware.org/?probe=5d22a61587) | Sep 06, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [ba05ae3ca2](https://linux-hardware.org/?probe=ba05ae3ca2) | Sep 06, 2023 |
| HP            | 3047h                       | Desktop     | [9b6ecf8471](https://linux-hardware.org/?probe=9b6ecf8471) | Sep 06, 2023 |
| HP            | 3047h                       | Desktop     | [51ba95dc5a](https://linux-hardware.org/?probe=51ba95dc5a) | Sep 06, 2023 |
| Lenovo        | Yoga 520-14IKB 80YM         | Convertible | [a7e1067ce7](https://linux-hardware.org/?probe=a7e1067ce7) | Sep 06, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [299a459ec5](https://linux-hardware.org/?probe=299a459ec5) | Sep 06, 2023 |
| Lenovo        | IdeaPad Z360                | Notebook    | [1bb5ebf339](https://linux-hardware.org/?probe=1bb5ebf339) | Sep 06, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [0deab6fc8b](https://linux-hardware.org/?probe=0deab6fc8b) | Sep 06, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [aa37593b87](https://linux-hardware.org/?probe=aa37593b87) | Sep 06, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [230cd8c32e](https://linux-hardware.org/?probe=230cd8c32e) | Sep 06, 2023 |
| Dell          | G3 3500                     | Notebook    | [5da26d2241](https://linux-hardware.org/?probe=5da26d2241) | Sep 06, 2023 |
| Biostar       | G31M+                       | Desktop     | [24eb0eb2db](https://linux-hardware.org/?probe=24eb0eb2db) | Sep 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [da71ec43ea](https://linux-hardware.org/?probe=da71ec43ea) | Sep 06, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [479d5ea49e](https://linux-hardware.org/?probe=479d5ea49e) | Sep 06, 2023 |
| HP            | 0B54h D                     | Desktop     | [978ff127e9](https://linux-hardware.org/?probe=978ff127e9) | Sep 05, 2023 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [4a055a6f9c](https://linux-hardware.org/?probe=4a055a6f9c) | Sep 05, 2023 |
| Biostar       | A320MH                      | Desktop     | [1907707516](https://linux-hardware.org/?probe=1907707516) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [a64157168e](https://linux-hardware.org/?probe=a64157168e) | Sep 05, 2023 |
| Biostar       | A320MH                      | Desktop     | [f13f5f9fe9](https://linux-hardware.org/?probe=f13f5f9fe9) | Sep 05, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [190675e9f1](https://linux-hardware.org/?probe=190675e9f1) | Sep 05, 2023 |
| Acer          | Aspire 5750Z                | Notebook    | [5bec99a137](https://linux-hardware.org/?probe=5bec99a137) | Sep 05, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [dc22012520](https://linux-hardware.org/?probe=dc22012520) | Sep 05, 2023 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [0576ca20ab](https://linux-hardware.org/?probe=0576ca20ab) | Sep 05, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [0841c5e196](https://linux-hardware.org/?probe=0841c5e196) | Sep 05, 2023 |
| Dell          | G15 5530                    | Notebook    | [91dcc569ee](https://linux-hardware.org/?probe=91dcc569ee) | Sep 05, 2023 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [710c22af52](https://linux-hardware.org/?probe=710c22af52) | Sep 05, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [a658addd87](https://linux-hardware.org/?probe=a658addd87) | Sep 05, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c02fef3ca2](https://linux-hardware.org/?probe=c02fef3ca2) | Sep 05, 2023 |
| ASRock        | E35LM1                      | Desktop     | [663d9ac1e1](https://linux-hardware.org/?probe=663d9ac1e1) | Sep 04, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [bcd06888e4](https://linux-hardware.org/?probe=bcd06888e4) | Sep 04, 2023 |
| Gigabyte      | H55M-S2HP                   | Desktop     | [f2ac0f8904](https://linux-hardware.org/?probe=f2ac0f8904) | Sep 04, 2023 |
| ASRock        | A55M-HVS                    | Desktop     | [eaa27d1ba6](https://linux-hardware.org/?probe=eaa27d1ba6) | Sep 04, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [5cb02e099f](https://linux-hardware.org/?probe=5cb02e099f) | Sep 04, 2023 |
| ASRock        | N68-S3 FX                   | Desktop     | [2b503dd2b6](https://linux-hardware.org/?probe=2b503dd2b6) | Sep 04, 2023 |
| Unknown       | SEI Robotics SEI610         | Soc         | [9b43cf14a3](https://linux-hardware.org/?probe=9b43cf14a3) | Sep 04, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [5139d104cc](https://linux-hardware.org/?probe=5139d104cc) | Sep 04, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [1f090fc4fd](https://linux-hardware.org/?probe=1f090fc4fd) | Sep 04, 2023 |
| Dell          | Inspiron 7580               | Notebook    | [b021fe57a6](https://linux-hardware.org/?probe=b021fe57a6) | Sep 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YD0... | Notebook    | [8253da4d01](https://linux-hardware.org/?probe=8253da4d01) | Sep 04, 2023 |
| Lenovo        | IdeaPad S400 Touch VIUS3    | Notebook    | [d2ac233994](https://linux-hardware.org/?probe=d2ac233994) | Sep 04, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [6046f9d74b](https://linux-hardware.org/?probe=6046f9d74b) | Sep 04, 2023 |
| Compaq        | 430                         | Notebook    | [ac9fb09e14](https://linux-hardware.org/?probe=ac9fb09e14) | Sep 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [aeebc4664f](https://linux-hardware.org/?probe=aeebc4664f) | Sep 04, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [8d52d37e1e](https://linux-hardware.org/?probe=8d52d37e1e) | Sep 04, 2023 |
| HP            | ENVY 14 SPECTRE             | Notebook    | [1f0a26899c](https://linux-hardware.org/?probe=1f0a26899c) | Sep 04, 2023 |
| HP            | 1000                        | Notebook    | [59cd8d1250](https://linux-hardware.org/?probe=59cd8d1250) | Sep 04, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | Desktop     | [908a64b09a](https://linux-hardware.org/?probe=908a64b09a) | Sep 04, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1c048ac799](https://linux-hardware.org/?probe=1c048ac799) | Sep 04, 2023 |
| Dell          | 0CU409                      | Desktop     | [ca461ddc28](https://linux-hardware.org/?probe=ca461ddc28) | Sep 04, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [8d171f78bf](https://linux-hardware.org/?probe=8d171f78bf) | Sep 04, 2023 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [7e0c89dfdb](https://linux-hardware.org/?probe=7e0c89dfdb) | Sep 04, 2023 |
| Samsung       | RV415                       | Notebook    | [dc6aa3101f](https://linux-hardware.org/?probe=dc6aa3101f) | Sep 03, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [b8a2b22a6c](https://linux-hardware.org/?probe=b8a2b22a6c) | Sep 03, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [522a10f139](https://linux-hardware.org/?probe=522a10f139) | Sep 03, 2023 |
| HP            | Folio 13                    | Notebook    | [d5844cc9e8](https://linux-hardware.org/?probe=d5844cc9e8) | Sep 03, 2023 |
| Acer          | Aspire 5750Z                | Notebook    | [f0b466e572](https://linux-hardware.org/?probe=f0b466e572) | Sep 03, 2023 |
| Lenovo        | ThinkPad E490 20N9001RBR    | Notebook    | [b9de538f7e](https://linux-hardware.org/?probe=b9de538f7e) | Sep 03, 2023 |
| Intel         | H61                         | Desktop     | [209644dbc2](https://linux-hardware.org/?probe=209644dbc2) | Sep 03, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [3aa237c8c6](https://linux-hardware.org/?probe=3aa237c8c6) | Sep 03, 2023 |
| LG Electro... | 22V280 FAB1                 | All in one  | [f02e3011d3](https://linux-hardware.org/?probe=f02e3011d3) | Sep 03, 2023 |
| AMD           | A88K                        | Desktop     | [d58c29d4ad](https://linux-hardware.org/?probe=d58c29d4ad) | Sep 03, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e58d4f8405](https://linux-hardware.org/?probe=e58d4f8405) | Sep 03, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [2b257d37b3](https://linux-hardware.org/?probe=2b257d37b3) | Sep 03, 2023 |
| MEGA          | G41T-M7 LGT                 | Desktop     | [8d645686ff](https://linux-hardware.org/?probe=8d645686ff) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [c93a88de93](https://linux-hardware.org/?probe=c93a88de93) | Sep 02, 2023 |
| HP            | 3646h                       | Desktop     | [cd226fee15](https://linux-hardware.org/?probe=cd226fee15) | Sep 02, 2023 |
| Multilaser    | UM125                       | Mini pc     | [a43bdb65de](https://linux-hardware.org/?probe=a43bdb65de) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [76b9023610](https://linux-hardware.org/?probe=76b9023610) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f5f8737b58](https://linux-hardware.org/?probe=f5f8737b58) | Sep 02, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [df01a7432c](https://linux-hardware.org/?probe=df01a7432c) | Sep 02, 2023 |
| Apple         | MacBookAir3,2               | Notebook    | [5ee8cbf433](https://linux-hardware.org/?probe=5ee8cbf433) | Sep 02, 2023 |
| Samsung       | 530XBB                      | Notebook    | [30365848c4](https://linux-hardware.org/?probe=30365848c4) | Sep 02, 2023 |
| Dell          | Latitude 7400               | Notebook    | [c98434cc21](https://linux-hardware.org/?probe=c98434cc21) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [2a9211117f](https://linux-hardware.org/?probe=2a9211117f) | Sep 02, 2023 |
| Lenovo        | Legion 5 15ACH6 82QJ        | Notebook    | [5897684d9e](https://linux-hardware.org/?probe=5897684d9e) | Sep 02, 2023 |
| Samsung       | 500R5L/501R5L/500R5P        | Notebook    | [681c0ca0f9](https://linux-hardware.org/?probe=681c0ca0f9) | Sep 02, 2023 |
| Dell          | Latitude 2120               | Notebook    | [65eed61467](https://linux-hardware.org/?probe=65eed61467) | Sep 02, 2023 |
| Dell          | Latitude 3410               | Notebook    | [695e65a1f0](https://linux-hardware.org/?probe=695e65a1f0) | Sep 02, 2023 |
| Samsung       | 370E4K                      | Notebook    | [19f41e00da](https://linux-hardware.org/?probe=19f41e00da) | Sep 02, 2023 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [1c1b1adcc9](https://linux-hardware.org/?probe=1c1b1adcc9) | Sep 02, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [6953a7b5f2](https://linux-hardware.org/?probe=6953a7b5f2) | Sep 02, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [87e1726495](https://linux-hardware.org/?probe=87e1726495) | Sep 01, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [e73e853358](https://linux-hardware.org/?probe=e73e853358) | Sep 01, 2023 |
| Positivo      | POS-EIH610EX 11189814       | Desktop     | [e6a9006a72](https://linux-hardware.org/?probe=e6a9006a72) | Sep 01, 2023 |
| Dell          | 0XT4CY A01                  | Desktop     | [26665d2c19](https://linux-hardware.org/?probe=26665d2c19) | Sep 01, 2023 |
| Samsung       | 550XED                      | Notebook    | [ba2fe18193](https://linux-hardware.org/?probe=ba2fe18193) | Sep 01, 2023 |
| Dell          | G15 5520                    | Notebook    | [9cfb8ce55a](https://linux-hardware.org/?probe=9cfb8ce55a) | Sep 01, 2023 |
| Positivo      | POS-EIH610EX 11189814       | Desktop     | [e222369e70](https://linux-hardware.org/?probe=e222369e70) | Sep 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1f29e90c7f](https://linux-hardware.org/?probe=1f29e90c7f) | Sep 01, 2023 |
| Intel         | X99H                        | Desktop     | [e020530bc8](https://linux-hardware.org/?probe=e020530bc8) | Sep 01, 2023 |
| Foxconn       | A6VMX 0A                    | Desktop     | [338cdb7d40](https://linux-hardware.org/?probe=338cdb7d40) | Sep 01, 2023 |
| Intel         | H110                        | Desktop     | [05970c6811](https://linux-hardware.org/?probe=05970c6811) | Sep 01, 2023 |
| Positivo      | Mobile                      | Notebook    | [3b32864073](https://linux-hardware.org/?probe=3b32864073) | Sep 01, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [77c6379594](https://linux-hardware.org/?probe=77c6379594) | Sep 01, 2023 |
| ASUSTek       | PRIME H410M-D               | Desktop     | [332e78dfba](https://linux-hardware.org/?probe=332e78dfba) | Sep 01, 2023 |
| Foxconn       | G31MXP FAB:1.1              | Desktop     | [4fc2089efc](https://linux-hardware.org/?probe=4fc2089efc) | Sep 01, 2023 |
| ASUSTek       | M4A78LT-M-LE                | Desktop     | [d3d5887ff3](https://linux-hardware.org/?probe=d3d5887ff3) | Sep 01, 2023 |
| Google        | Barla                       | Notebook    | [1beaca005d](https://linux-hardware.org/?probe=1beaca005d) | Sep 01, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [7fd4c8ad9c](https://linux-hardware.org/?probe=7fd4c8ad9c) | Sep 01, 2023 |
| HP            | 1489                        | All in one  | [c53e87bce8](https://linux-hardware.org/?probe=c53e87bce8) | Sep 01, 2023 |
| HP            | Presario CQ43               | Notebook    | [9a02828a68](https://linux-hardware.org/?probe=9a02828a68) | Sep 01, 2023 |
| AMD           | A88K                        | Desktop     | [08a455504f](https://linux-hardware.org/?probe=08a455504f) | Sep 01, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [42eb5f3ad4](https://linux-hardware.org/?probe=42eb5f3ad4) | Aug 31, 2023 |
| PCWare        | IPX1800E1                   | Desktop     | [bfe03f751b](https://linux-hardware.org/?probe=bfe03f751b) | Aug 31, 2023 |
| Intel         | H61                         | Desktop     | [d0bd2f4cfa](https://linux-hardware.org/?probe=d0bd2f4cfa) | Aug 31, 2023 |
| Intel         | B75                         | Desktop     | [d8367a0977](https://linux-hardware.org/?probe=d8367a0977) | Aug 31, 2023 |
| MSI           | H61M-P20/W8                 | Desktop     | [c35045d386](https://linux-hardware.org/?probe=c35045d386) | Aug 31, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [311af8113f](https://linux-hardware.org/?probe=311af8113f) | Aug 31, 2023 |
| Red Hat       | RHEL RHEL-9.2.0 PC          | Desktop     | [ee06e81f13](https://linux-hardware.org/?probe=ee06e81f13) | Aug 31, 2023 |
| Intel         | H55                         | Desktop     | [955198ab64](https://linux-hardware.org/?probe=955198ab64) | Aug 31, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [fd3c900751](https://linux-hardware.org/?probe=fd3c900751) | Aug 31, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [064705b919](https://linux-hardware.org/?probe=064705b919) | Aug 31, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [b9c66b93e7](https://linux-hardware.org/?probe=b9c66b93e7) | Aug 31, 2023 |
| MACHINIST     | E5-D8-MAX V1.0              | Desktop     | [339734178a](https://linux-hardware.org/?probe=339734178a) | Aug 31, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [6c5da44516](https://linux-hardware.org/?probe=6c5da44516) | Aug 31, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [9e1df9ff88](https://linux-hardware.org/?probe=9e1df9ff88) | Aug 31, 2023 |
| Megaware      | MW-NM70HD-MI 06/11/2012 ... | Desktop     | [7b8812491c](https://linux-hardware.org/?probe=7b8812491c) | Aug 31, 2023 |
| HP            | Pavilion dv4                | Notebook    | [c84d5215be](https://linux-hardware.org/?probe=c84d5215be) | Aug 30, 2023 |
| Dell          | G15 5530                    | Notebook    | [1027c8fe19](https://linux-hardware.org/?probe=1027c8fe19) | Aug 30, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [79783b33ff](https://linux-hardware.org/?probe=79783b33ff) | Aug 30, 2023 |
| Avell High... | C62 MOB                     | Notebook    | [04e247a3d3](https://linux-hardware.org/?probe=04e247a3d3) | Aug 30, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [ebcd50f639](https://linux-hardware.org/?probe=ebcd50f639) | Aug 30, 2023 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | Desktop     | [fbbbe0087a](https://linux-hardware.org/?probe=fbbbe0087a) | Aug 30, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [9cf292357b](https://linux-hardware.org/?probe=9cf292357b) | Aug 30, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [7075df2d62](https://linux-hardware.org/?probe=7075df2d62) | Aug 30, 2023 |
| Intel         | DH67CL AAG10212-206         | Desktop     | [e3f4b109ff](https://linux-hardware.org/?probe=e3f4b109ff) | Aug 30, 2023 |
| Foxconn       | Lucknow                     | Desktop     | [eece5a84ae](https://linux-hardware.org/?probe=eece5a84ae) | Aug 30, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [500ef94276](https://linux-hardware.org/?probe=500ef94276) | Aug 29, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [c392d83e8e](https://linux-hardware.org/?probe=c392d83e8e) | Aug 29, 2023 |
| MSI           | H61M-E22/W8                 | Desktop     | [2439d2ed95](https://linux-hardware.org/?probe=2439d2ed95) | Aug 29, 2023 |
| LG Electro... | V720                        | All in one  | [28f525b5a1](https://linux-hardware.org/?probe=28f525b5a1) | Aug 29, 2023 |
| LG Electro... | V720                        | All in one  | [7fdfb84d04](https://linux-hardware.org/?probe=7fdfb84d04) | Aug 29, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [7094317c17](https://linux-hardware.org/?probe=7094317c17) | Aug 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [2a5afc6557](https://linux-hardware.org/?probe=2a5afc6557) | Aug 29, 2023 |
| MSI           | MAG B460M BAZOOKA           | Desktop     | [dcd9ab0f79](https://linux-hardware.org/?probe=dcd9ab0f79) | Aug 29, 2023 |
| Lenovo        | IdeaPad Z470                | Notebook    | [d3c372d869](https://linux-hardware.org/?probe=d3c372d869) | Aug 29, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | Notebook    | [a5f9c0a211](https://linux-hardware.org/?probe=a5f9c0a211) | Aug 29, 2023 |
| Sony          | VPCEA36FX                   | Notebook    | [174aefbf35](https://linux-hardware.org/?probe=174aefbf35) | Aug 29, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [fd0950b7c1](https://linux-hardware.org/?probe=fd0950b7c1) | Aug 28, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [f94a46ad17](https://linux-hardware.org/?probe=f94a46ad17) | Aug 28, 2023 |
| Unknown       | SEI Robotics SEI610         | Soc         | [9ee073735e](https://linux-hardware.org/?probe=9ee073735e) | Aug 28, 2023 |
| Intel         | H81                         | Desktop     | [9b70a28b25](https://linux-hardware.org/?probe=9b70a28b25) | Aug 28, 2023 |
| Intel         | DX79SR AAG57199-200         | Desktop     | [418a709636](https://linux-hardware.org/?probe=418a709636) | Aug 28, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [a4fe691c36](https://linux-hardware.org/?probe=a4fe691c36) | Aug 28, 2023 |
| Lenovo        | Legion 5 15IMH 82CF         | Notebook    | [4d8ac47399](https://linux-hardware.org/?probe=4d8ac47399) | Aug 28, 2023 |
| AZW           | GK mini                     | Mini pc     | [64b25422b0](https://linux-hardware.org/?probe=64b25422b0) | Aug 28, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | Notebook    | [94f2581f9f](https://linux-hardware.org/?probe=94f2581f9f) | Aug 28, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [40c64b6ec2](https://linux-hardware.org/?probe=40c64b6ec2) | Aug 28, 2023 |
| Acer          | Aspire 5741Z                | Notebook    | [2127326562](https://linux-hardware.org/?probe=2127326562) | Aug 28, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [379728237a](https://linux-hardware.org/?probe=379728237a) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [30006f030a](https://linux-hardware.org/?probe=30006f030a) | Aug 28, 2023 |
| Gigabyte      | B75M-D3P                    | Desktop     | [73562af96c](https://linux-hardware.org/?probe=73562af96c) | Aug 28, 2023 |
| Acer          | Aspire 4738                 | Notebook    | [6051c9190a](https://linux-hardware.org/?probe=6051c9190a) | Aug 28, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [65408b783f](https://linux-hardware.org/?probe=65408b783f) | Aug 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [e02ef868a3](https://linux-hardware.org/?probe=e02ef868a3) | Aug 28, 2023 |
| Positivo      | C14CU51                     | Notebook    | [7fa280c987](https://linux-hardware.org/?probe=7fa280c987) | Aug 28, 2023 |
| Positivo      | POS-PQ45AU                  | Desktop     | [aba45a4f14](https://linux-hardware.org/?probe=aba45a4f14) | Aug 27, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [bf483bc8d3](https://linux-hardware.org/?probe=bf483bc8d3) | Aug 27, 2023 |
| Dell          | Inspiron 5590               | Notebook    | [5036ce79f9](https://linux-hardware.org/?probe=5036ce79f9) | Aug 27, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [c9935dab6b](https://linux-hardware.org/?probe=c9935dab6b) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8b82375189](https://linux-hardware.org/?probe=8b82375189) | Aug 27, 2023 |
| Dell          | Inspiron 5502               | Notebook    | [b2ecdef159](https://linux-hardware.org/?probe=b2ecdef159) | Aug 27, 2023 |
| Dell          | Vostro 3501                 | Notebook    | [0211379a67](https://linux-hardware.org/?probe=0211379a67) | Aug 27, 2023 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [6b9ae23c76](https://linux-hardware.org/?probe=6b9ae23c76) | Aug 27, 2023 |
| LG Electro... | White Tip Mountain FAB3     | All in one  | [91204c1c19](https://linux-hardware.org/?probe=91204c1c19) | Aug 27, 2023 |
| Samsung       | 300E4M/300E4S/300E4L        | Notebook    | [633ddecba0](https://linux-hardware.org/?probe=633ddecba0) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a284c141d8](https://linux-hardware.org/?probe=a284c141d8) | Aug 27, 2023 |
| Timi          | TM1701                      | Notebook    | [2a6a4225a0](https://linux-hardware.org/?probe=2a6a4225a0) | Aug 27, 2023 |
| Timi          | TM1701                      | Notebook    | [8ea7c21e18](https://linux-hardware.org/?probe=8ea7c21e18) | Aug 27, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [8ee437beac](https://linux-hardware.org/?probe=8ee437beac) | Aug 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [7566a0ed19](https://linux-hardware.org/?probe=7566a0ed19) | Aug 27, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [dcb65a221f](https://linux-hardware.org/?probe=dcb65a221f) | Aug 27, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [35fede08aa](https://linux-hardware.org/?probe=35fede08aa) | Aug 26, 2023 |
| Positivo      | CHT14B                      | Notebook    | [81a8519b9e](https://linux-hardware.org/?probe=81a8519b9e) | Aug 26, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | Desktop     | [2eb35196a6](https://linux-hardware.org/?probe=2eb35196a6) | Aug 26, 2023 |
| HP            | 1998                        | Desktop     | [2c6c07a7d3](https://linux-hardware.org/?probe=2c6c07a7d3) | Aug 26, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | Notebook    | [c0957b3538](https://linux-hardware.org/?probe=c0957b3538) | Aug 26, 2023 |
| Intel         | D33217CK G76541-301         | Desktop     | [24b3b7aac4](https://linux-hardware.org/?probe=24b3b7aac4) | Aug 26, 2023 |
| Positivo      | POS-PIG41BA POSITIVO        | Desktop     | [05dc1d19de](https://linux-hardware.org/?probe=05dc1d19de) | Aug 26, 2023 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [01750cc1d8](https://linux-hardware.org/?probe=01750cc1d8) | Aug 26, 2023 |
| Samsung       | RV419/RV420                 | Notebook    | [77e9d34f16](https://linux-hardware.org/?probe=77e9d34f16) | Aug 26, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [1f47bfe737](https://linux-hardware.org/?probe=1f47bfe737) | Aug 26, 2023 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [f0f9f25268](https://linux-hardware.org/?probe=f0f9f25268) | Aug 26, 2023 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [95aa33fc09](https://linux-hardware.org/?probe=95aa33fc09) | Aug 26, 2023 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [6fc7c35bc9](https://linux-hardware.org/?probe=6fc7c35bc9) | Aug 26, 2023 |
| Google        | Kasumi                      | Notebook    | [9af5f77257](https://linux-hardware.org/?probe=9af5f77257) | Aug 25, 2023 |
| Dell          | Latitude E6440              | Notebook    | [759a858fa1](https://linux-hardware.org/?probe=759a858fa1) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [878476c63f](https://linux-hardware.org/?probe=878476c63f) | Aug 25, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [b14dfb0798](https://linux-hardware.org/?probe=b14dfb0798) | Aug 25, 2023 |
| Samsung       | RV419/RV420                 | Notebook    | [275cd1500e](https://linux-hardware.org/?probe=275cd1500e) | Aug 25, 2023 |
| Dell          | 0T656F A01                  | Desktop     | [fe9ddfe6d0](https://linux-hardware.org/?probe=fe9ddfe6d0) | Aug 25, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [49769c9b38](https://linux-hardware.org/?probe=49769c9b38) | Aug 25, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [e3bc104b50](https://linux-hardware.org/?probe=e3bc104b50) | Aug 25, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [decfff1e51](https://linux-hardware.org/?probe=decfff1e51) | Aug 25, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [22187e6de0](https://linux-hardware.org/?probe=22187e6de0) | Aug 25, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [2e62ce7973](https://linux-hardware.org/?probe=2e62ce7973) | Aug 25, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [34e1a0c5c4](https://linux-hardware.org/?probe=34e1a0c5c4) | Aug 24, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [4d99c3a598](https://linux-hardware.org/?probe=4d99c3a598) | Aug 24, 2023 |
| HP            | 3047h                       | Desktop     | [5c415723ef](https://linux-hardware.org/?probe=5c415723ef) | Aug 24, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [09db81cde4](https://linux-hardware.org/?probe=09db81cde4) | Aug 24, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [648f667e11](https://linux-hardware.org/?probe=648f667e11) | Aug 24, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [a7fbf7edf2](https://linux-hardware.org/?probe=a7fbf7edf2) | Aug 24, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [744be89da4](https://linux-hardware.org/?probe=744be89da4) | Aug 24, 2023 |
| Lenovo        | ThinkServer RD450 70DC00... | Server      | [71859969f5](https://linux-hardware.org/?probe=71859969f5) | Aug 24, 2023 |
| Dell          | Inspiron 7572               | Notebook    | [84f4498af0](https://linux-hardware.org/?probe=84f4498af0) | Aug 24, 2023 |
| Unknown       | Unknown                     | Soc         | [ddc3d0b271](https://linux-hardware.org/?probe=ddc3d0b271) | Aug 24, 2023 |
| Colorful T... | A320M-K PRO YV14            | Desktop     | [0cf842e282](https://linux-hardware.org/?probe=0cf842e282) | Aug 24, 2023 |
| Gigabyte      | H310M M.2                   | Desktop     | [9b1205f50a](https://linux-hardware.org/?probe=9b1205f50a) | Aug 24, 2023 |
| Lenovo        | ThinkServer RD450 70DC00... | Server      | [cfeb45f5a1](https://linux-hardware.org/?probe=cfeb45f5a1) | Aug 24, 2023 |
| Lenovo        | ThinkPad T460 20FMA00F00    | Notebook    | [370de86ed7](https://linux-hardware.org/?probe=370de86ed7) | Aug 24, 2023 |
| ASUSTek       | P7H55-M BR                  | Desktop     | [820b86d560](https://linux-hardware.org/?probe=820b86d560) | Aug 24, 2023 |
| Positivo B... | VJFE59F11X-B0411H           | Notebook    | [5e5059f835](https://linux-hardware.org/?probe=5e5059f835) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [fd9fa02e66](https://linux-hardware.org/?probe=fd9fa02e66) | Aug 23, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [d44597af00](https://linux-hardware.org/?probe=d44597af00) | Aug 23, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [f8990a10d8](https://linux-hardware.org/?probe=f8990a10d8) | Aug 23, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [a09e28d1d6](https://linux-hardware.org/?probe=a09e28d1d6) | Aug 23, 2023 |
| Dell          | System XPS L502X            | Notebook    | [a5357a41b4](https://linux-hardware.org/?probe=a5357a41b4) | Aug 23, 2023 |
| Positivo      | POS-PIH110DV                | Desktop     | [75f0f78d6c](https://linux-hardware.org/?probe=75f0f78d6c) | Aug 23, 2023 |
| Dell          | 0WY45N A00                  | Desktop     | [523c93534d](https://linux-hardware.org/?probe=523c93534d) | Aug 23, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [c9896d5610](https://linux-hardware.org/?probe=c9896d5610) | Aug 23, 2023 |
| Positivo      | M7X0S Bottom                | Notebook    | [f78713080f](https://linux-hardware.org/?probe=f78713080f) | Aug 23, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [38849e44bb](https://linux-hardware.org/?probe=38849e44bb) | Aug 23, 2023 |
| Positivo      | C14CU51                     | Notebook    | [b8c9fbc7b7](https://linux-hardware.org/?probe=b8c9fbc7b7) | Aug 23, 2023 |
| Samsung       | 370E4K                      | Notebook    | [074e0669c7](https://linux-hardware.org/?probe=074e0669c7) | Aug 22, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [ac09f27b9d](https://linux-hardware.org/?probe=ac09f27b9d) | Aug 22, 2023 |
| Intel         | H55                         | Desktop     | [8320e0c758](https://linux-hardware.org/?probe=8320e0c758) | Aug 22, 2023 |
| Dell          | G3 3579                     | Notebook    | [49b4227da5](https://linux-hardware.org/?probe=49b4227da5) | Aug 22, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [7d5c45785c](https://linux-hardware.org/?probe=7d5c45785c) | Aug 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [82c63f13d1](https://linux-hardware.org/?probe=82c63f13d1) | Aug 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [1aee954611](https://linux-hardware.org/?probe=1aee954611) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f2d55c9619](https://linux-hardware.org/?probe=f2d55c9619) | Aug 22, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [698fbb24ed](https://linux-hardware.org/?probe=698fbb24ed) | Aug 22, 2023 |
| Intel         | H81                         | Desktop     | [fe1e95123d](https://linux-hardware.org/?probe=fe1e95123d) | Aug 22, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [8812e20762](https://linux-hardware.org/?probe=8812e20762) | Aug 22, 2023 |
| Dell          | 0DT021 A00                  | Server      | [8598fe0d4b](https://linux-hardware.org/?probe=8598fe0d4b) | Aug 22, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [cdef569014](https://linux-hardware.org/?probe=cdef569014) | Aug 22, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [d5350f0d1c](https://linux-hardware.org/?probe=d5350f0d1c) | Aug 22, 2023 |
| ASUSTek       | Z450UAK                     | Notebook    | [68fb2ce5ec](https://linux-hardware.org/?probe=68fb2ce5ec) | Aug 22, 2023 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [04a07b8fa6](https://linux-hardware.org/?probe=04a07b8fa6) | Aug 22, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [6a3c737df2](https://linux-hardware.org/?probe=6a3c737df2) | Aug 22, 2023 |
| Intel         | HuronRiver Platform         | Notebook    | [7cf233eb4d](https://linux-hardware.org/?probe=7cf233eb4d) | Aug 22, 2023 |
| Sony          | SVE14123CBW                 | Notebook    | [b7891b51b2](https://linux-hardware.org/?probe=b7891b51b2) | Aug 21, 2023 |
| Sony          | SVE14123CBW                 | Notebook    | [9730d7f8f5](https://linux-hardware.org/?probe=9730d7f8f5) | Aug 21, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [d8a6683747](https://linux-hardware.org/?probe=d8a6683747) | Aug 21, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [9762e16c0e](https://linux-hardware.org/?probe=9762e16c0e) | Aug 21, 2023 |
| Acer          | Aspire 5750Z                | Notebook    | [8c15b251a7](https://linux-hardware.org/?probe=8c15b251a7) | Aug 21, 2023 |
| AMD           | Inagua CRB                  | Desktop     | [9455337239](https://linux-hardware.org/?probe=9455337239) | Aug 21, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [534e1dc3e5](https://linux-hardware.org/?probe=534e1dc3e5) | Aug 21, 2023 |
| ASUSTek       | X510URR                     | Notebook    | [d1ee285db9](https://linux-hardware.org/?probe=d1ee285db9) | Aug 21, 2023 |
| Packard Be... | EasyNote MZ36               | Notebook    | [d628db6497](https://linux-hardware.org/?probe=d628db6497) | Aug 21, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [feeca36aa9](https://linux-hardware.org/?probe=feeca36aa9) | Aug 21, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [e2c346429e](https://linux-hardware.org/?probe=e2c346429e) | Aug 21, 2023 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [4590ebf626](https://linux-hardware.org/?probe=4590ebf626) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [930d312c36](https://linux-hardware.org/?probe=930d312c36) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [2bc8c24081](https://linux-hardware.org/?probe=2bc8c24081) | Aug 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b86411b8b0](https://linux-hardware.org/?probe=b86411b8b0) | Aug 21, 2023 |
| Dell          | Inspiron 5737               | Notebook    | [665dbda021](https://linux-hardware.org/?probe=665dbda021) | Aug 21, 2023 |
| Sony          | VPCEG15FB                   | Notebook    | [e3b2126509](https://linux-hardware.org/?probe=e3b2126509) | Aug 20, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [ee47d4b6a7](https://linux-hardware.org/?probe=ee47d4b6a7) | Aug 20, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [41edd1a16e](https://linux-hardware.org/?probe=41edd1a16e) | Aug 20, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [5b7f4b5a45](https://linux-hardware.org/?probe=5b7f4b5a45) | Aug 20, 2023 |
| Megaware      | MW-G31T-M7                  | Desktop     | [3bed885307](https://linux-hardware.org/?probe=3bed885307) | Aug 20, 2023 |
| Lenovo        | ThinkPad Edge 0578A66       | Notebook    | [6b3703818a](https://linux-hardware.org/?probe=6b3703818a) | Aug 20, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [03bd8885a0](https://linux-hardware.org/?probe=03bd8885a0) | Aug 20, 2023 |
| EUROCOM       | RACER 2.0                   | Notebook    | [b27f687c16](https://linux-hardware.org/?probe=b27f687c16) | Aug 20, 2023 |
| Alienware     | m15 R4                      | Notebook    | [46f36f26ff](https://linux-hardware.org/?probe=46f36f26ff) | Aug 20, 2023 |
| Bananapi      | BPI-M5                      | Soc         | [0bd2202791](https://linux-hardware.org/?probe=0bd2202791) | Aug 19, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [1c57edc329](https://linux-hardware.org/?probe=1c57edc329) | Aug 19, 2023 |
| Megaware      | MW-G31T-M7                  | Desktop     | [774ca523db](https://linux-hardware.org/?probe=774ca523db) | Aug 19, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | Notebook    | [f75baa8a07](https://linux-hardware.org/?probe=f75baa8a07) | Aug 19, 2023 |
| Alienware     | m15 R4                      | Notebook    | [cf9a9e0729](https://linux-hardware.org/?probe=cf9a9e0729) | Aug 19, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [1d08f612ba](https://linux-hardware.org/?probe=1d08f612ba) | Aug 19, 2023 |
| Dell          | Inspiron 5447               | Notebook    | [07a24f8880](https://linux-hardware.org/?probe=07a24f8880) | Aug 19, 2023 |
| ASUSTek       | UX410UQK                    | Notebook    | [cf7a7946dc](https://linux-hardware.org/?probe=cf7a7946dc) | Aug 19, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [e625280525](https://linux-hardware.org/?probe=e625280525) | Aug 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [f44bc6c057](https://linux-hardware.org/?probe=f44bc6c057) | Aug 19, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [921d699e5d](https://linux-hardware.org/?probe=921d699e5d) | Aug 19, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [bbf0f31c1b](https://linux-hardware.org/?probe=bbf0f31c1b) | Aug 19, 2023 |
| Positivo      | CHT14B                      | Notebook    | [28106aa94b](https://linux-hardware.org/?probe=28106aa94b) | Aug 19, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [3cdfdae368](https://linux-hardware.org/?probe=3cdfdae368) | Aug 19, 2023 |
| Lenovo        | B490 377224P                | Notebook    | [0e516ea22b](https://linux-hardware.org/?probe=0e516ea22b) | Aug 19, 2023 |
| Toshiba       | IS 1422                     | Notebook    | [2ad1bbf471](https://linux-hardware.org/?probe=2ad1bbf471) | Aug 18, 2023 |
| Samsung       | 750QFG                      | Convertible | [ff0b9fb300](https://linux-hardware.org/?probe=ff0b9fb300) | Aug 18, 2023 |
| HP            | 0266                        | Desktop     | [636546711d](https://linux-hardware.org/?probe=636546711d) | Aug 18, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [58af8f5102](https://linux-hardware.org/?probe=58af8f5102) | Aug 18, 2023 |
| ECS           | A55F-M4                     | Desktop     | [93a5944754](https://linux-hardware.org/?probe=93a5944754) | Aug 18, 2023 |
| Acer          | Aspire E1-421               | Notebook    | [bab5968f80](https://linux-hardware.org/?probe=bab5968f80) | Aug 18, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [ae37d9f640](https://linux-hardware.org/?probe=ae37d9f640) | Aug 18, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [cce6cb2878](https://linux-hardware.org/?probe=cce6cb2878) | Aug 18, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [04ebdc3ec0](https://linux-hardware.org/?probe=04ebdc3ec0) | Aug 18, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [55b9d87888](https://linux-hardware.org/?probe=55b9d87888) | Aug 18, 2023 |
| MSI           | X470 GAMING M7 AC           | Desktop     | [92f8391f8f](https://linux-hardware.org/?probe=92f8391f8f) | Aug 18, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [024d9028bb](https://linux-hardware.org/?probe=024d9028bb) | Aug 18, 2023 |
| ASRock        | H61M-HG4                    | Desktop     | [6fbc46fea9](https://linux-hardware.org/?probe=6fbc46fea9) | Aug 17, 2023 |
| Dell          | G3 3579                     | Notebook    | [567acf505b](https://linux-hardware.org/?probe=567acf505b) | Aug 17, 2023 |
| QIYIDA        | X79 (INTEL Xeon E5/Corei... | Desktop     | [1aeba3a6ec](https://linux-hardware.org/?probe=1aeba3a6ec) | Aug 17, 2023 |
| QIYIDA        | X79 (INTEL Xeon E5/Corei... | Desktop     | [b44417fa3d](https://linux-hardware.org/?probe=b44417fa3d) | Aug 17, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [1739e9ff2d](https://linux-hardware.org/?probe=1739e9ff2d) | Aug 17, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [93f7041d2f](https://linux-hardware.org/?probe=93f7041d2f) | Aug 17, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [1f416788fa](https://linux-hardware.org/?probe=1f416788fa) | Aug 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [35b8929f7f](https://linux-hardware.org/?probe=35b8929f7f) | Aug 17, 2023 |
| ASUSTek       | B150M-C/BR                  | Desktop     | [78e12f014e](https://linux-hardware.org/?probe=78e12f014e) | Aug 17, 2023 |
| Intel         | H55                         | Desktop     | [9d45836b3b](https://linux-hardware.org/?probe=9d45836b3b) | Aug 17, 2023 |
| Daten Tecn... | DV3N-4                      | Notebook    | [7a95cb94da](https://linux-hardware.org/?probe=7a95cb94da) | Aug 17, 2023 |
| ASRock        | A320M-HD R4.0               | Desktop     | [f67dd298b1](https://linux-hardware.org/?probe=f67dd298b1) | Aug 16, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [cf9cfddfa5](https://linux-hardware.org/?probe=cf9cfddfa5) | Aug 16, 2023 |
| Acer          | Aspire A315-33              | Notebook    | [a1db467e0a](https://linux-hardware.org/?probe=a1db467e0a) | Aug 16, 2023 |
| Acer          | Aspire 5050                 | Notebook    | [63329f0ff6](https://linux-hardware.org/?probe=63329f0ff6) | Aug 16, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [6c3b1a6ddd](https://linux-hardware.org/?probe=6c3b1a6ddd) | Aug 16, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [ec4afb1917](https://linux-hardware.org/?probe=ec4afb1917) | Aug 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [8733f22b33](https://linux-hardware.org/?probe=8733f22b33) | Aug 16, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [d7ec063f46](https://linux-hardware.org/?probe=d7ec063f46) | Aug 16, 2023 |
| PCWare        | IPMH110G                    | Desktop     | [c07caba6a9](https://linux-hardware.org/?probe=c07caba6a9) | Aug 16, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [a6ad62b671](https://linux-hardware.org/?probe=a6ad62b671) | Aug 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f88687d2f0](https://linux-hardware.org/?probe=f88687d2f0) | Aug 15, 2023 |
| Dell          | Vostro 3501                 | Notebook    | [c36d4d9de0](https://linux-hardware.org/?probe=c36d4d9de0) | Aug 15, 2023 |
| Positivo      | POS-RIQ470EN 11190998       | Desktop     | [1eec60309a](https://linux-hardware.org/?probe=1eec60309a) | Aug 15, 2023 |
| HP            | 3047h                       | Desktop     | [b136128b47](https://linux-hardware.org/?probe=b136128b47) | Aug 15, 2023 |
| Samsung       | 550XDA                      | Notebook    | [5e5606074a](https://linux-hardware.org/?probe=5e5606074a) | Aug 15, 2023 |
| Multilaser    | PC13X                       | Notebook    | [d79767b027](https://linux-hardware.org/?probe=d79767b027) | Aug 15, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [11dafc79e8](https://linux-hardware.org/?probe=11dafc79e8) | Aug 15, 2023 |
| Topstar       | Cantiga & ICH9M Chipset     | Notebook    | [5102056c71](https://linux-hardware.org/?probe=5102056c71) | Aug 15, 2023 |
| Dell          | Latitude E6530              | Notebook    | [9cbe752127](https://linux-hardware.org/?probe=9cbe752127) | Aug 15, 2023 |
| Intel         | B75A                        | Desktop     | [c081fb2ca8](https://linux-hardware.org/?probe=c081fb2ca8) | Aug 15, 2023 |
| Positivo      | S14CT01                     | Notebook    | [e865565207](https://linux-hardware.org/?probe=e865565207) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [f6892c6532](https://linux-hardware.org/?probe=f6892c6532) | Aug 15, 2023 |
| HP            | 3047h                       | Desktop     | [4c2aba9453](https://linux-hardware.org/?probe=4c2aba9453) | Aug 14, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [da3036b8e3](https://linux-hardware.org/?probe=da3036b8e3) | Aug 14, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [8803256d2e](https://linux-hardware.org/?probe=8803256d2e) | Aug 14, 2023 |
| ASUSTek       | H110M-C/BR                  | Desktop     | [e6da28e1fb](https://linux-hardware.org/?probe=e6da28e1fb) | Aug 14, 2023 |
| Positivo      | N1250                       | Notebook    | [8c1d1f89f7](https://linux-hardware.org/?probe=8c1d1f89f7) | Aug 14, 2023 |
| Positivo      | N1250                       | Notebook    | [17ce4f01a7](https://linux-hardware.org/?probe=17ce4f01a7) | Aug 14, 2023 |
| Positivo      | Mobile                      | Notebook    | [4111fa6520](https://linux-hardware.org/?probe=4111fa6520) | Aug 14, 2023 |
| Lenovo        | ThinkCentre Edge71 1577K... | Desktop     | [8127e491dc](https://linux-hardware.org/?probe=8127e491dc) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c342e06960](https://linux-hardware.org/?probe=c342e06960) | Aug 14, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [495c01f301](https://linux-hardware.org/?probe=495c01f301) | Aug 14, 2023 |
| Alienware     | m15 R7                      | Notebook    | [a501a43d37](https://linux-hardware.org/?probe=a501a43d37) | Aug 14, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [e6fe434dfa](https://linux-hardware.org/?probe=e6fe434dfa) | Aug 13, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [f256ce0d84](https://linux-hardware.org/?probe=f256ce0d84) | Aug 13, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [7612329440](https://linux-hardware.org/?probe=7612329440) | Aug 13, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [0afd683e48](https://linux-hardware.org/?probe=0afd683e48) | Aug 13, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [3decac5b92](https://linux-hardware.org/?probe=3decac5b92) | Aug 13, 2023 |
| Intel         | H61                         | Desktop     | [0f81745861](https://linux-hardware.org/?probe=0f81745861) | Aug 13, 2023 |
| HP            | 450                         | Notebook    | [242d41f5e9](https://linux-hardware.org/?probe=242d41f5e9) | Aug 13, 2023 |
| Intel         | H61                         | Desktop     | [cbf83ef64b](https://linux-hardware.org/?probe=cbf83ef64b) | Aug 13, 2023 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [60746f5bad](https://linux-hardware.org/?probe=60746f5bad) | Aug 13, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [7dd490a028](https://linux-hardware.org/?probe=7dd490a028) | Aug 13, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3508d6c711](https://linux-hardware.org/?probe=3508d6c711) | Aug 13, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [d1fddefbb1](https://linux-hardware.org/?probe=d1fddefbb1) | Aug 13, 2023 |
| Daten Tecn... | DT02-M4                     | Notebook    | [39acd7fbd5](https://linux-hardware.org/?probe=39acd7fbd5) | Aug 13, 2023 |
| HP            | Folio 13                    | Notebook    | [62fcebde8c](https://linux-hardware.org/?probe=62fcebde8c) | Aug 13, 2023 |
| Intel         | H55                         | Desktop     | [9eb68ebabb](https://linux-hardware.org/?probe=9eb68ebabb) | Aug 13, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b97fcb7117](https://linux-hardware.org/?probe=b97fcb7117) | Aug 12, 2023 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [d81314b86d](https://linux-hardware.org/?probe=d81314b86d) | Aug 12, 2023 |
| Intel         | B75A                        | Desktop     | [91f9e56ace](https://linux-hardware.org/?probe=91f9e56ace) | Aug 12, 2023 |
| Samsung       | 730QED                      | Convertible | [c6bb6c3646](https://linux-hardware.org/?probe=c6bb6c3646) | Aug 12, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [9aa2cd7b81](https://linux-hardware.org/?probe=9aa2cd7b81) | Aug 12, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [6f230d02c1](https://linux-hardware.org/?probe=6f230d02c1) | Aug 12, 2023 |
| HP            | Compaq nx9420 (RH457EA#A... | Notebook    | [1b7c441369](https://linux-hardware.org/?probe=1b7c441369) | Aug 12, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [ed029dd5e3](https://linux-hardware.org/?probe=ed029dd5e3) | Aug 12, 2023 |
| Multilaser    | PC024                       | Notebook    | [3311e26ac5](https://linux-hardware.org/?probe=3311e26ac5) | Aug 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [53196a01fa](https://linux-hardware.org/?probe=53196a01fa) | Aug 12, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [5bb31ccda3](https://linux-hardware.org/?probe=5bb31ccda3) | Aug 12, 2023 |
| Dell          | G3 3579                     | Notebook    | [09ba53e3c1](https://linux-hardware.org/?probe=09ba53e3c1) | Aug 12, 2023 |
| Intel         | DG31PR AAE58249-301         | Desktop     | [28bc891b6d](https://linux-hardware.org/?probe=28bc891b6d) | Aug 12, 2023 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [5226916c20](https://linux-hardware.org/?probe=5226916c20) | Aug 12, 2023 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [f59a93f116](https://linux-hardware.org/?probe=f59a93f116) | Aug 12, 2023 |
| Intel         | DG31PR AAE58249-301         | Desktop     | [3050db3fbf](https://linux-hardware.org/?probe=3050db3fbf) | Aug 12, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [f8fa12cc07](https://linux-hardware.org/?probe=f8fa12cc07) | Aug 11, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [019f3a6d1f](https://linux-hardware.org/?probe=019f3a6d1f) | Aug 11, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [4daff2c43f](https://linux-hardware.org/?probe=4daff2c43f) | Aug 11, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [3ab135e657](https://linux-hardware.org/?probe=3ab135e657) | Aug 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [8d7674c3b3](https://linux-hardware.org/?probe=8d7674c3b3) | Aug 11, 2023 |
| Positivo      | C4128B-1                    | Convertible | [ef67e885dc](https://linux-hardware.org/?probe=ef67e885dc) | Aug 11, 2023 |
| Dell          | G15 5520                    | Notebook    | [3bec284af8](https://linux-hardware.org/?probe=3bec284af8) | Aug 11, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | Notebook    | [83879b8247](https://linux-hardware.org/?probe=83879b8247) | Aug 11, 2023 |
| Gigabyte      | A520M DS3H AC               | Desktop     | [c53eeb4caf](https://linux-hardware.org/?probe=c53eeb4caf) | Aug 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ea4ae0e0f3](https://linux-hardware.org/?probe=ea4ae0e0f3) | Aug 11, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [053608e18a](https://linux-hardware.org/?probe=053608e18a) | Aug 11, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [4856b9b32f](https://linux-hardware.org/?probe=4856b9b32f) | Aug 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [97e0c46487](https://linux-hardware.org/?probe=97e0c46487) | Aug 11, 2023 |
| Avell High... | A40 LIV                     | Notebook    | [9bc62c7eec](https://linux-hardware.org/?probe=9bc62c7eec) | Aug 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [2db90ee24e](https://linux-hardware.org/?probe=2db90ee24e) | Aug 11, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [30748e95eb](https://linux-hardware.org/?probe=30748e95eb) | Aug 11, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [7fe6adce5e](https://linux-hardware.org/?probe=7fe6adce5e) | Aug 10, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [6c55de5ac8](https://linux-hardware.org/?probe=6c55de5ac8) | Aug 10, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [09000d6461](https://linux-hardware.org/?probe=09000d6461) | Aug 10, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [c05973af65](https://linux-hardware.org/?probe=c05973af65) | Aug 10, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [773b111412](https://linux-hardware.org/?probe=773b111412) | Aug 10, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [70c4f2863b](https://linux-hardware.org/?probe=70c4f2863b) | Aug 10, 2023 |
| ASUSTek       | P8Z68-V                     | Desktop     | [cff11cda6f](https://linux-hardware.org/?probe=cff11cda6f) | Aug 10, 2023 |
| Avell High... | A70 HYB                     | Notebook    | [9b03ae1cd3](https://linux-hardware.org/?probe=9b03ae1cd3) | Aug 10, 2023 |
| HP            | Folio 13                    | Notebook    | [67121fc711](https://linux-hardware.org/?probe=67121fc711) | Aug 10, 2023 |
| Avell         | A70 ION                     | Notebook    | [6ab02a34e4](https://linux-hardware.org/?probe=6ab02a34e4) | Aug 10, 2023 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [d4a16b0b3e](https://linux-hardware.org/?probe=d4a16b0b3e) | Aug 10, 2023 |
| HP            | 2AF9                        | Desktop     | [b31b796804](https://linux-hardware.org/?probe=b31b796804) | Aug 10, 2023 |
| Avell         | A70 ION                     | Notebook    | [b71c176ce3](https://linux-hardware.org/?probe=b71c176ce3) | Aug 10, 2023 |
| Acer          | Nitro AN517-51              | Notebook    | [bd3b7989f0](https://linux-hardware.org/?probe=bd3b7989f0) | Aug 10, 2023 |
| Dell          | Vostro 3501                 | Notebook    | [d606f83745](https://linux-hardware.org/?probe=d606f83745) | Aug 10, 2023 |
| Lenovo        | IdeaPad U430 Touch 20270    | Notebook    | [4446f503d5](https://linux-hardware.org/?probe=4446f503d5) | Aug 10, 2023 |
| Dell          | OptiPlex 755                | Desktop     | [279ed1e2d5](https://linux-hardware.org/?probe=279ed1e2d5) | Aug 10, 2023 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [7acbd56a40](https://linux-hardware.org/?probe=7acbd56a40) | Aug 10, 2023 |
| MSI           | A68HM-E33                   | Desktop     | [be692e44b5](https://linux-hardware.org/?probe=be692e44b5) | Aug 10, 2023 |
| Dell          | 0VXN67 A01                  | Desktop     | [4fbd39d860](https://linux-hardware.org/?probe=4fbd39d860) | Aug 10, 2023 |
| Positivo      | Presley 3                   | Notebook    | [16ddbd1a75](https://linux-hardware.org/?probe=16ddbd1a75) | Aug 10, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | Desktop     | [0c4903c4d2](https://linux-hardware.org/?probe=0c4903c4d2) | Aug 10, 2023 |
| HP            | Folio 13                    | Notebook    | [889aae1772](https://linux-hardware.org/?probe=889aae1772) | Aug 10, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [1e856f651d](https://linux-hardware.org/?probe=1e856f651d) | Aug 09, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [739bc450b8](https://linux-hardware.org/?probe=739bc450b8) | Aug 09, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [e315608a65](https://linux-hardware.org/?probe=e315608a65) | Aug 09, 2023 |
| Huanan        | X99-TF-Q GAMING V1.2        | Desktop     | [da612198cc](https://linux-hardware.org/?probe=da612198cc) | Aug 09, 2023 |
| Positivo      | Presley 3                   | Notebook    | [9edde2ea30](https://linux-hardware.org/?probe=9edde2ea30) | Aug 09, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [e22cd6fdac](https://linux-hardware.org/?probe=e22cd6fdac) | Aug 09, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [2242417727](https://linux-hardware.org/?probe=2242417727) | Aug 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [0b1144add1](https://linux-hardware.org/?probe=0b1144add1) | Aug 09, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [c4ac4952a4](https://linux-hardware.org/?probe=c4ac4952a4) | Aug 09, 2023 |
| ASRock        | H81M-HG4 R4.0               | Notebook    | [26c322239f](https://linux-hardware.org/?probe=26c322239f) | Aug 09, 2023 |
| Biostar       | X370GT3                     | Desktop     | [6c4e484a34](https://linux-hardware.org/?probe=6c4e484a34) | Aug 09, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [62a5817462](https://linux-hardware.org/?probe=62a5817462) | Aug 09, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [dace48c9ec](https://linux-hardware.org/?probe=dace48c9ec) | Aug 09, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [e4c0e430b2](https://linux-hardware.org/?probe=e4c0e430b2) | Aug 09, 2023 |
| Lenovo        | ThinkPad T460 20FMA00F00    | Notebook    | [4bd13ae71d](https://linux-hardware.org/?probe=4bd13ae71d) | Aug 09, 2023 |
| Itautec       | ST 4273 ST-4273 Custom 0... | Desktop     | [2e2f861c7c](https://linux-hardware.org/?probe=2e2f861c7c) | Aug 09, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [eb99d95702](https://linux-hardware.org/?probe=eb99d95702) | Aug 08, 2023 |
| Dell          | 0DT021 A00                  | Server      | [f472313f3a](https://linux-hardware.org/?probe=f472313f3a) | Aug 08, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [cc5ec06f60](https://linux-hardware.org/?probe=cc5ec06f60) | Aug 08, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [7ce5fc846b](https://linux-hardware.org/?probe=7ce5fc846b) | Aug 08, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [14e4cbffd4](https://linux-hardware.org/?probe=14e4cbffd4) | Aug 08, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [13cec81a99](https://linux-hardware.org/?probe=13cec81a99) | Aug 08, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [d6b7da58e7](https://linux-hardware.org/?probe=d6b7da58e7) | Aug 08, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [88c76f027a](https://linux-hardware.org/?probe=88c76f027a) | Aug 08, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [1105c8c2ea](https://linux-hardware.org/?probe=1105c8c2ea) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [dd127ca2df](https://linux-hardware.org/?probe=dd127ca2df) | Aug 08, 2023 |
| ASRock        | H81M-HG4 R4.0               | Notebook    | [788c24d04a](https://linux-hardware.org/?probe=788c24d04a) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [965f96493c](https://linux-hardware.org/?probe=965f96493c) | Aug 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [ec7a911951](https://linux-hardware.org/?probe=ec7a911951) | Aug 08, 2023 |
| Avell High... | A40 LIV                     | Notebook    | [4022d66d9a](https://linux-hardware.org/?probe=4022d66d9a) | Aug 08, 2023 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [b477184f03](https://linux-hardware.org/?probe=b477184f03) | Aug 08, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [f7845429c8](https://linux-hardware.org/?probe=f7845429c8) | Aug 07, 2023 |
| Acer          | Nitro AN517-52              | Notebook    | [d24385ceb8](https://linux-hardware.org/?probe=d24385ceb8) | Aug 07, 2023 |
| Digiboard     | NM70-I                      | Desktop     | [280ee6d8fe](https://linux-hardware.org/?probe=280ee6d8fe) | Aug 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [e2427beca2](https://linux-hardware.org/?probe=e2427beca2) | Aug 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [7e185ae211](https://linux-hardware.org/?probe=7e185ae211) | Aug 07, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [c130dece41](https://linux-hardware.org/?probe=c130dece41) | Aug 06, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [8f33c0cf28](https://linux-hardware.org/?probe=8f33c0cf28) | Aug 06, 2023 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [6875c17337](https://linux-hardware.org/?probe=6875c17337) | Aug 06, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [570d622bb5](https://linux-hardware.org/?probe=570d622bb5) | Aug 06, 2023 |
| Notebook      | 1745                        | Notebook    | [3561a5dbbe](https://linux-hardware.org/?probe=3561a5dbbe) | Aug 06, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [2e8d48f9bc](https://linux-hardware.org/?probe=2e8d48f9bc) | Aug 06, 2023 |
| HP            | Pavilion dm4                | Notebook    | [521b8518ed](https://linux-hardware.org/?probe=521b8518ed) | Aug 06, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | Notebook    | [52b9918d42](https://linux-hardware.org/?probe=52b9918d42) | Aug 06, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [27792f16e2](https://linux-hardware.org/?probe=27792f16e2) | Aug 06, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [af35c9ce49](https://linux-hardware.org/?probe=af35c9ce49) | Aug 05, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [9a45c9f834](https://linux-hardware.org/?probe=9a45c9f834) | Aug 05, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [39140ff7de](https://linux-hardware.org/?probe=39140ff7de) | Aug 05, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [6de5534e97](https://linux-hardware.org/?probe=6de5534e97) | Aug 05, 2023 |
| Dell          | Latitude 5410               | Notebook    | [2838e5d74c](https://linux-hardware.org/?probe=2838e5d74c) | Aug 05, 2023 |
| Dell          | Latitude E5440              | Notebook    | [f6981c56b7](https://linux-hardware.org/?probe=f6981c56b7) | Aug 05, 2023 |
| Multilaser    | PC024                       | Notebook    | [85a4bdd497](https://linux-hardware.org/?probe=85a4bdd497) | Aug 05, 2023 |
| Lenovo        | B330-15IKBR 81M1            | Notebook    | [f03fa524d7](https://linux-hardware.org/?probe=f03fa524d7) | Aug 05, 2023 |
| Multilaser    | PC13X                       | Notebook    | [2f79cffddd](https://linux-hardware.org/?probe=2f79cffddd) | Aug 05, 2023 |
| HP            | Pavilion g4                 | Notebook    | [2094186715](https://linux-hardware.org/?probe=2094186715) | Aug 05, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [da2ada0c83](https://linux-hardware.org/?probe=da2ada0c83) | Aug 05, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [7ffb6822e6](https://linux-hardware.org/?probe=7ffb6822e6) | Aug 05, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [24a5183e69](https://linux-hardware.org/?probe=24a5183e69) | Aug 05, 2023 |
| Dell          | G15 5520                    | Notebook    | [baca0d14f5](https://linux-hardware.org/?probe=baca0d14f5) | Aug 05, 2023 |
| MACHINIST     | X99-MR9D PLUS V1.0          | Desktop     | [29f8d73c0e](https://linux-hardware.org/?probe=29f8d73c0e) | Aug 05, 2023 |
| Intel         | B75                         | Desktop     | [9411dd987c](https://linux-hardware.org/?probe=9411dd987c) | Aug 05, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [17ea53b0c6](https://linux-hardware.org/?probe=17ea53b0c6) | Aug 05, 2023 |
| Intel         | H81                         | Desktop     | [4441a1a1ca](https://linux-hardware.org/?probe=4441a1a1ca) | Aug 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [8292d9f518](https://linux-hardware.org/?probe=8292d9f518) | Aug 04, 2023 |
| Itautec       | Infoway                     | Notebook    | [1708f5baae](https://linux-hardware.org/?probe=1708f5baae) | Aug 04, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [8b6b5ff142](https://linux-hardware.org/?probe=8b6b5ff142) | Aug 04, 2023 |
| Dell          | 0DT021 A00                  | Server      | [354c40df4e](https://linux-hardware.org/?probe=354c40df4e) | Aug 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [92ef92268a](https://linux-hardware.org/?probe=92ef92268a) | Aug 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ca1a97268c](https://linux-hardware.org/?probe=ca1a97268c) | Aug 04, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [de07e937bb](https://linux-hardware.org/?probe=de07e937bb) | Aug 04, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [df3495c01c](https://linux-hardware.org/?probe=df3495c01c) | Aug 04, 2023 |
| MANCER        | A320M-DA 1006               | Desktop     | [573affec7b](https://linux-hardware.org/?probe=573affec7b) | Aug 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [61cb65a2e9](https://linux-hardware.org/?probe=61cb65a2e9) | Aug 04, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [aee5a21c76](https://linux-hardware.org/?probe=aee5a21c76) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [a260479012](https://linux-hardware.org/?probe=a260479012) | Aug 04, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [bd88b4e8fa](https://linux-hardware.org/?probe=bd88b4e8fa) | Aug 04, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [0ffd23b534](https://linux-hardware.org/?probe=0ffd23b534) | Aug 04, 2023 |
| ASUSTek       | UX490UAR                    | Notebook    | [6a305978e3](https://linux-hardware.org/?probe=6a305978e3) | Aug 03, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [21d7f13381](https://linux-hardware.org/?probe=21d7f13381) | Aug 03, 2023 |
| OEM           | B75 Ver:1.44                | Desktop     | [6dcf79b752](https://linux-hardware.org/?probe=6dcf79b752) | Aug 03, 2023 |
| Lenovo        | ThinkPad Edge E431 6277C... | Notebook    | [6c542a6490](https://linux-hardware.org/?probe=6c542a6490) | Aug 03, 2023 |
| Intel         | H61                         | Desktop     | [7b2774c1a1](https://linux-hardware.org/?probe=7b2774c1a1) | Aug 03, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [25dcc9a7c5](https://linux-hardware.org/?probe=25dcc9a7c5) | Aug 03, 2023 |
| Intel         | H61                         | Desktop     | [8d450f7e6e](https://linux-hardware.org/?probe=8d450f7e6e) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [67d851300e](https://linux-hardware.org/?probe=67d851300e) | Aug 03, 2023 |
| Win elemen... | M600                        | Desktop     | [b9537c621c](https://linux-hardware.org/?probe=b9537c621c) | Aug 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [3bb1942723](https://linux-hardware.org/?probe=3bb1942723) | Aug 02, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | Desktop     | [11d27dea01](https://linux-hardware.org/?probe=11d27dea01) | Aug 02, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [518512fe78](https://linux-hardware.org/?probe=518512fe78) | Aug 02, 2023 |
| Positivo      | Q232B                       | Notebook    | [006d77a18c](https://linux-hardware.org/?probe=006d77a18c) | Aug 02, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [e1d2deb748](https://linux-hardware.org/?probe=e1d2deb748) | Aug 02, 2023 |
| Dell          | 0FR6WH A01                  | Desktop     | [38feb4d1f7](https://linux-hardware.org/?probe=38feb4d1f7) | Aug 02, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [af04d8d764](https://linux-hardware.org/?probe=af04d8d764) | Aug 02, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [2ff30156cf](https://linux-hardware.org/?probe=2ff30156cf) | Aug 02, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [d4c5149060](https://linux-hardware.org/?probe=d4c5149060) | Aug 02, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [0ced83ffed](https://linux-hardware.org/?probe=0ced83ffed) | Aug 02, 2023 |
| ASRock        | H410M-HDV/M.2               | Desktop     | [71a11bdffd](https://linux-hardware.org/?probe=71a11bdffd) | Aug 02, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [bdccf9a3db](https://linux-hardware.org/?probe=bdccf9a3db) | Aug 01, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [c4e404738e](https://linux-hardware.org/?probe=c4e404738e) | Aug 01, 2023 |
| Lenovo        | 3188 SDK0J40709 WIN 3259... | Desktop     | [59e7f97f2d](https://linux-hardware.org/?probe=59e7f97f2d) | Aug 01, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [56e2fa207e](https://linux-hardware.org/?probe=56e2fa207e) | Aug 01, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [668eb36a4a](https://linux-hardware.org/?probe=668eb36a4a) | Aug 01, 2023 |
| Itautec       | Infoway a7420               | Notebook    | [da7459a0ea](https://linux-hardware.org/?probe=da7459a0ea) | Aug 01, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [287740b630](https://linux-hardware.org/?probe=287740b630) | Aug 01, 2023 |
| Lenovo        | B330-15IKBR 81M1            | Notebook    | [1f69ed5c1e](https://linux-hardware.org/?probe=1f69ed5c1e) | Aug 01, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | Desktop     | [2e4793aa6c](https://linux-hardware.org/?probe=2e4793aa6c) | Aug 01, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [08e1a2a1e1](https://linux-hardware.org/?probe=08e1a2a1e1) | Aug 01, 2023 |
| ASRock        | H110M-HG4                   | Desktop     | [7584e2db20](https://linux-hardware.org/?probe=7584e2db20) | Jul 31, 2023 |
| Intel         | DH55HC AAE70933-502         | Desktop     | [e849da706a](https://linux-hardware.org/?probe=e849da706a) | Jul 31, 2023 |
| HP            | Pavilion 14                 | Notebook    | [313aedd888](https://linux-hardware.org/?probe=313aedd888) | Jul 31, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [9b9830aedf](https://linux-hardware.org/?probe=9b9830aedf) | Jul 31, 2023 |
| Positivo      | POS-PIH110DV                | Desktop     | [faa5c5cda0](https://linux-hardware.org/?probe=faa5c5cda0) | Jul 31, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [b87690f890](https://linux-hardware.org/?probe=b87690f890) | Jul 31, 2023 |
| Unknown       | Phitronics N68C-M           | Desktop     | [0c596c95da](https://linux-hardware.org/?probe=0c596c95da) | Jul 31, 2023 |
| Dell          | Latitude E5510              | Notebook    | [b9208e8c08](https://linux-hardware.org/?probe=b9208e8c08) | Jul 31, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [67fbb84480](https://linux-hardware.org/?probe=67fbb84480) | Jul 31, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [7890c76098](https://linux-hardware.org/?probe=7890c76098) | Jul 31, 2023 |
| Dell          | Vostro 1510                 | Notebook    | [8e49dde20d](https://linux-hardware.org/?probe=8e49dde20d) | Jul 31, 2023 |
| Dell          | Vostro 1510                 | Notebook    | [8d6d8b9243](https://linux-hardware.org/?probe=8d6d8b9243) | Jul 31, 2023 |
| Dell          | Vostro 1510                 | Notebook    | [13e9f3fa3c](https://linux-hardware.org/?probe=13e9f3fa3c) | Jul 31, 2023 |
| Lenovo        | ThinkPad T460 20FMA00F00    | Notebook    | [9268d1c4f9](https://linux-hardware.org/?probe=9268d1c4f9) | Jul 30, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [9371aa866b](https://linux-hardware.org/?probe=9371aa866b) | Jul 30, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [eedbe7eb59](https://linux-hardware.org/?probe=eedbe7eb59) | Jul 30, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | Desktop     | [42a2df4c91](https://linux-hardware.org/?probe=42a2df4c91) | Jul 30, 2023 |
| Intel         | DG41WV AAE90316-102         | Desktop     | [fa7d425224](https://linux-hardware.org/?probe=fa7d425224) | Jul 30, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [28ff56233b](https://linux-hardware.org/?probe=28ff56233b) | Jul 30, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [f3de23350d](https://linux-hardware.org/?probe=f3de23350d) | Jul 30, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [3be466c09c](https://linux-hardware.org/?probe=3be466c09c) | Jul 30, 2023 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [ae14da63f3](https://linux-hardware.org/?probe=ae14da63f3) | Jul 30, 2023 |
| Lenovo        | B330-15IKBR 81M1            | Notebook    | [2a0777f1fd](https://linux-hardware.org/?probe=2a0777f1fd) | Jul 30, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [fe48f2b4d4](https://linux-hardware.org/?probe=fe48f2b4d4) | Jul 30, 2023 |
| Positivo B... | VJFE59F11X-B0411H           | Notebook    | [24c271e6fd](https://linux-hardware.org/?probe=24c271e6fd) | Jul 30, 2023 |
| Positivo B... | VJFE59F11X-B0411H           | Notebook    | [bb2245d195](https://linux-hardware.org/?probe=bb2245d195) | Jul 30, 2023 |
| MSI           | B85M-E45                    | Desktop     | [dfef6fcff5](https://linux-hardware.org/?probe=dfef6fcff5) | Jul 30, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [0ce1be51b9](https://linux-hardware.org/?probe=0ce1be51b9) | Jul 30, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [1bcc28bd33](https://linux-hardware.org/?probe=1bcc28bd33) | Jul 29, 2023 |
| Unknown       | GSUO H61V10C                | Desktop     | [9fd25cd0ba](https://linux-hardware.org/?probe=9fd25cd0ba) | Jul 29, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [10b634ac99](https://linux-hardware.org/?probe=10b634ac99) | Jul 29, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [393c4b7fd3](https://linux-hardware.org/?probe=393c4b7fd3) | Jul 29, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [96b197dffc](https://linux-hardware.org/?probe=96b197dffc) | Jul 29, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [90c03881ae](https://linux-hardware.org/?probe=90c03881ae) | Jul 29, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [d693783e7a](https://linux-hardware.org/?probe=d693783e7a) | Jul 29, 2023 |
| HP            | Folio 13                    | Notebook    | [baaa648a4b](https://linux-hardware.org/?probe=baaa648a4b) | Jul 29, 2023 |
| Lenovo        | Unknown                     | Notebook    | [a1dac68b95](https://linux-hardware.org/?probe=a1dac68b95) | Jul 29, 2023 |
| Positivo      | POS-EINM70CS POSITIVO       | Desktop     | [bee5e6175b](https://linux-hardware.org/?probe=bee5e6175b) | Jul 29, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [733695ae93](https://linux-hardware.org/?probe=733695ae93) | Jul 29, 2023 |
| Samsung       | 550XDA                      | Notebook    | [c140c9176e](https://linux-hardware.org/?probe=c140c9176e) | Jul 29, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [701402e2a7](https://linux-hardware.org/?probe=701402e2a7) | Jul 29, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [502747dd18](https://linux-hardware.org/?probe=502747dd18) | Jul 29, 2023 |
| Dell          | Latitude 5400               | Notebook    | [9416ce803c](https://linux-hardware.org/?probe=9416ce803c) | Jul 28, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [7509644961](https://linux-hardware.org/?probe=7509644961) | Jul 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [bc88e3dbae](https://linux-hardware.org/?probe=bc88e3dbae) | Jul 28, 2023 |
| ASRock        | H110M-HG4                   | Desktop     | [205f3a047f](https://linux-hardware.org/?probe=205f3a047f) | Jul 28, 2023 |
| Digitron      | G31T-M7                     | Desktop     | [7b926165d9](https://linux-hardware.org/?probe=7b926165d9) | Jul 28, 2023 |
| Dell          | 0FR6WH A01                  | Desktop     | [d20434fd50](https://linux-hardware.org/?probe=d20434fd50) | Jul 28, 2023 |
| Acer          | Aspire 5350                 | Notebook    | [698672b19c](https://linux-hardware.org/?probe=698672b19c) | Jul 28, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [0e3aa83494](https://linux-hardware.org/?probe=0e3aa83494) | Jul 28, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [8ca0357bf1](https://linux-hardware.org/?probe=8ca0357bf1) | Jul 28, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [bca814cbb5](https://linux-hardware.org/?probe=bca814cbb5) | Jul 28, 2023 |
| MSI           | Z270 GAMING PLUS            | Desktop     | [cc489fad92](https://linux-hardware.org/?probe=cc489fad92) | Jul 28, 2023 |
| PCWare        | IPX1800E2                   | Desktop     | [ee17cd82e7](https://linux-hardware.org/?probe=ee17cd82e7) | Jul 27, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [6287e66ff2](https://linux-hardware.org/?probe=6287e66ff2) | Jul 27, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [d91f2ff8ba](https://linux-hardware.org/?probe=d91f2ff8ba) | Jul 27, 2023 |
| A14CR         | Unknown                     | Notebook    | [4ceb4f6761](https://linux-hardware.org/?probe=4ceb4f6761) | Jul 27, 2023 |
| Compaq        | PRESARIOCQ18                | Notebook    | [c528c90b50](https://linux-hardware.org/?probe=c528c90b50) | Jul 27, 2023 |
| Biostar       | B450MHP                     | Notebook    | [bb12598429](https://linux-hardware.org/?probe=bb12598429) | Jul 27, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | Desktop     | [b9bba11373](https://linux-hardware.org/?probe=b9bba11373) | Jul 27, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [23b23d59aa](https://linux-hardware.org/?probe=23b23d59aa) | Jul 27, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [26e141980a](https://linux-hardware.org/?probe=26e141980a) | Jul 27, 2023 |
| Intel         | H55                         | Desktop     | [83f249e836](https://linux-hardware.org/?probe=83f249e836) | Jul 27, 2023 |
| Multilaser    | PC024                       | Notebook    | [fa5b5a3146](https://linux-hardware.org/?probe=fa5b5a3146) | Jul 27, 2023 |
| Toshiba       | STI 005492G                 | Desktop     | [6e73cad7e4](https://linux-hardware.org/?probe=6e73cad7e4) | Jul 27, 2023 |
| Acer          | Aspire A315-23G             | Notebook    | [4d7b874be2](https://linux-hardware.org/?probe=4d7b874be2) | Jul 27, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [ac730fa4ed](https://linux-hardware.org/?probe=ac730fa4ed) | Jul 26, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [57d93857f1](https://linux-hardware.org/?probe=57d93857f1) | Jul 26, 2023 |
| ECS           | G41T-M7                     | Desktop     | [eb7ea6e3f6](https://linux-hardware.org/?probe=eb7ea6e3f6) | Jul 26, 2023 |
| Intel         | B75                         | Desktop     | [492fa4fc25](https://linux-hardware.org/?probe=492fa4fc25) | Jul 26, 2023 |
| HP            | Folio 13                    | Notebook    | [a3269c0930](https://linux-hardware.org/?probe=a3269c0930) | Jul 26, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [8daa291377](https://linux-hardware.org/?probe=8daa291377) | Jul 26, 2023 |
| Dell          | G3 3579                     | Notebook    | [b6b50ffa46](https://linux-hardware.org/?probe=b6b50ffa46) | Jul 26, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [55102fad5b](https://linux-hardware.org/?probe=55102fad5b) | Jul 26, 2023 |
| AZW           | SEi                         | Desktop     | [115142c288](https://linux-hardware.org/?probe=115142c288) | Jul 26, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [959f3b36df](https://linux-hardware.org/?probe=959f3b36df) | Jul 26, 2023 |
| Dell          | Vostro 15 5510              | Notebook    | [2e810b1c93](https://linux-hardware.org/?probe=2e810b1c93) | Jul 26, 2023 |
| Dell          | Vostro 15 5510              | Notebook    | [4171fc8925](https://linux-hardware.org/?probe=4171fc8925) | Jul 26, 2023 |
| Gigabyte      | G31M-S2L                    | Desktop     | [5af2ea35ee](https://linux-hardware.org/?probe=5af2ea35ee) | Jul 26, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [45bc8cd978](https://linux-hardware.org/?probe=45bc8cd978) | Jul 26, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [f67be57cba](https://linux-hardware.org/?probe=f67be57cba) | Jul 26, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [9793da4c20](https://linux-hardware.org/?probe=9793da4c20) | Jul 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [2fa28e6952](https://linux-hardware.org/?probe=2fa28e6952) | Jul 26, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [f6400e37f6](https://linux-hardware.org/?probe=f6400e37f6) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [22b2519a90](https://linux-hardware.org/?probe=22b2519a90) | Jul 26, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [7814bf14ac](https://linux-hardware.org/?probe=7814bf14ac) | Jul 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [8ba9103155](https://linux-hardware.org/?probe=8ba9103155) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [b583a1fbee](https://linux-hardware.org/?probe=b583a1fbee) | Jul 26, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [9878121979](https://linux-hardware.org/?probe=9878121979) | Jul 26, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [5ca26c7da9](https://linux-hardware.org/?probe=5ca26c7da9) | Jul 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [f720b1a032](https://linux-hardware.org/?probe=f720b1a032) | Jul 26, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [6c978ec74d](https://linux-hardware.org/?probe=6c978ec74d) | Jul 26, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [94a5fdec96](https://linux-hardware.org/?probe=94a5fdec96) | Jul 26, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [62bcc903fd](https://linux-hardware.org/?probe=62bcc903fd) | Jul 25, 2023 |
| MSI           | 2A9C                        | Desktop     | [83e6501c96](https://linux-hardware.org/?probe=83e6501c96) | Jul 25, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [787270abee](https://linux-hardware.org/?probe=787270abee) | Jul 25, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [3f39162908](https://linux-hardware.org/?probe=3f39162908) | Jul 25, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [3d3696e8fa](https://linux-hardware.org/?probe=3d3696e8fa) | Jul 25, 2023 |
| Positivo      | S14SL01                     | Notebook    | [7ee0f7e8d1](https://linux-hardware.org/?probe=7ee0f7e8d1) | Jul 25, 2023 |
| Compaq        | Presario CQ-23              | Notebook    | [b78363eeaf](https://linux-hardware.org/?probe=b78363eeaf) | Jul 25, 2023 |
| Toshiba       | IS 1442                     | Notebook    | [3a66df4c2d](https://linux-hardware.org/?probe=3a66df4c2d) | Jul 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [787c6a9252](https://linux-hardware.org/?probe=787c6a9252) | Jul 25, 2023 |
| MAXSUN        | MS-Terminator B660M VER:... | Desktop     | [5cf65783b2](https://linux-hardware.org/?probe=5cf65783b2) | Jul 25, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c675a3feab](https://linux-hardware.org/?probe=c675a3feab) | Jul 25, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [cfdb26e14f](https://linux-hardware.org/?probe=cfdb26e14f) | Jul 25, 2023 |
| Dell          | Latitude 3420               | Notebook    | [18d920dab2](https://linux-hardware.org/?probe=18d920dab2) | Jul 24, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [25f155c61a](https://linux-hardware.org/?probe=25f155c61a) | Jul 24, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [6b80b41fee](https://linux-hardware.org/?probe=6b80b41fee) | Jul 24, 2023 |
| PCWare        | IPMH61R3 8MB                | Desktop     | [dcbde0a01d](https://linux-hardware.org/?probe=dcbde0a01d) | Jul 24, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [2c4dce1245](https://linux-hardware.org/?probe=2c4dce1245) | Jul 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [f1844a5f28](https://linux-hardware.org/?probe=f1844a5f28) | Jul 24, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [858d935d25](https://linux-hardware.org/?probe=858d935d25) | Jul 24, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [ae6caf81d7](https://linux-hardware.org/?probe=ae6caf81d7) | Jul 24, 2023 |
| OEM           | Unknown                     | Notebook    | [d0d59fb363](https://linux-hardware.org/?probe=d0d59fb363) | Jul 24, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [e1de4fabc7](https://linux-hardware.org/?probe=e1de4fabc7) | Jul 24, 2023 |
| Dell          | G15 5510                    | Notebook    | [18ceaecd85](https://linux-hardware.org/?probe=18ceaecd85) | Jul 24, 2023 |
| LG Electro... | R490-G.BR51P1               | Notebook    | [eecedbc045](https://linux-hardware.org/?probe=eecedbc045) | Jul 24, 2023 |
| MACHINIST     | X99-MR9D PLUS V1.0          | Desktop     | [d1ef825b01](https://linux-hardware.org/?probe=d1ef825b01) | Jul 24, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [7f6b8fc2db](https://linux-hardware.org/?probe=7f6b8fc2db) | Jul 23, 2023 |
| OEM           | Unknown                     | Notebook    | [a45e07b803](https://linux-hardware.org/?probe=a45e07b803) | Jul 23, 2023 |
| Intel         | B75                         | Desktop     | [f6b0d91a50](https://linux-hardware.org/?probe=f6b0d91a50) | Jul 23, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [50cf88ae28](https://linux-hardware.org/?probe=50cf88ae28) | Jul 23, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [8982fa467c](https://linux-hardware.org/?probe=8982fa467c) | Jul 23, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [42d8ff9a34](https://linux-hardware.org/?probe=42d8ff9a34) | Jul 23, 2023 |
| Microsoft     | Surface Laptop Go 2         | Tablet      | [e9d3b3fe8e](https://linux-hardware.org/?probe=e9d3b3fe8e) | Jul 23, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [3733be1f95](https://linux-hardware.org/?probe=3733be1f95) | Jul 23, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | Desktop     | [5e02d0f4e4](https://linux-hardware.org/?probe=5e02d0f4e4) | Jul 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [808ae8a334](https://linux-hardware.org/?probe=808ae8a334) | Jul 22, 2023 |
| Sony          | SVF15213CBB                 | Notebook    | [569ed328f7](https://linux-hardware.org/?probe=569ed328f7) | Jul 22, 2023 |
| ECS           | A780LM-M2                   | Desktop     | [b8b1304632](https://linux-hardware.org/?probe=b8b1304632) | Jul 22, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [c361b3b1ac](https://linux-hardware.org/?probe=c361b3b1ac) | Jul 22, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | Desktop     | [a12700ebb8](https://linux-hardware.org/?probe=a12700ebb8) | Jul 22, 2023 |
| Biostar       | B350GT3                     | Desktop     | [41d95e4e81](https://linux-hardware.org/?probe=41d95e4e81) | Jul 22, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | Desktop     | [6285ba6300](https://linux-hardware.org/?probe=6285ba6300) | Jul 22, 2023 |
| Samsung       | 550XDA                      | Notebook    | [c298263c6c](https://linux-hardware.org/?probe=c298263c6c) | Jul 22, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [a9af1efc27](https://linux-hardware.org/?probe=a9af1efc27) | Jul 22, 2023 |
| Intel         | H61                         | Desktop     | [5a977f0aa9](https://linux-hardware.org/?probe=5a977f0aa9) | Jul 21, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [574d6f4393](https://linux-hardware.org/?probe=574d6f4393) | Jul 21, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [306d51185f](https://linux-hardware.org/?probe=306d51185f) | Jul 21, 2023 |
| Kllisre       | X99-B5 V1.1                 | Desktop     | [b132b3f39c](https://linux-hardware.org/?probe=b132b3f39c) | Jul 21, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [55f5c5bd48](https://linux-hardware.org/?probe=55f5c5bd48) | Jul 21, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [031d46c9d0](https://linux-hardware.org/?probe=031d46c9d0) | Jul 21, 2023 |
| Intel         | X99H                        | Desktop     | [474e78b162](https://linux-hardware.org/?probe=474e78b162) | Jul 21, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | Notebook    | [fc45e9b064](https://linux-hardware.org/?probe=fc45e9b064) | Jul 21, 2023 |
| Avell High... | B.ON                        | Notebook    | [8269a683ef](https://linux-hardware.org/?probe=8269a683ef) | Jul 21, 2023 |
| LG Electro... | S425-G.BC31P1               | Notebook    | [2f54821f3f](https://linux-hardware.org/?probe=2f54821f3f) | Jul 21, 2023 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [2269e1f3d7](https://linux-hardware.org/?probe=2269e1f3d7) | Jul 21, 2023 |
| Dell          | Latitude 5290               | Notebook    | [66860827b9](https://linux-hardware.org/?probe=66860827b9) | Jul 21, 2023 |
| Itautec       | Infoway w7535               | Notebook    | [bde95c0c99](https://linux-hardware.org/?probe=bde95c0c99) | Jul 21, 2023 |
| Biostar       | A320MH                      | Desktop     | [5fd84925fd](https://linux-hardware.org/?probe=5fd84925fd) | Jul 20, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [df2bfbf3e1](https://linux-hardware.org/?probe=df2bfbf3e1) | Jul 20, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [e4cc108748](https://linux-hardware.org/?probe=e4cc108748) | Jul 20, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [4f438fcc8b](https://linux-hardware.org/?probe=4f438fcc8b) | Jul 20, 2023 |
| ASRock        | X99M Extreme4               | Desktop     | [caf88d9f9d](https://linux-hardware.org/?probe=caf88d9f9d) | Jul 20, 2023 |
| Lenovo        | Legion 5 15ACH6 82QJ        | Notebook    | [c7e1f17f9e](https://linux-hardware.org/?probe=c7e1f17f9e) | Jul 20, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [413194ce8c](https://linux-hardware.org/?probe=413194ce8c) | Jul 20, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [08fccc55c8](https://linux-hardware.org/?probe=08fccc55c8) | Jul 20, 2023 |
| Alienware     | m15 R6                      | Notebook    | [93d5e98358](https://linux-hardware.org/?probe=93d5e98358) | Jul 20, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [9b44d7bd03](https://linux-hardware.org/?probe=9b44d7bd03) | Jul 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [da1ea699ed](https://linux-hardware.org/?probe=da1ea699ed) | Jul 19, 2023 |
| Gateway       | NV55C                       | Notebook    | [a87e93c2a7](https://linux-hardware.org/?probe=a87e93c2a7) | Jul 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [7ff33d80d7](https://linux-hardware.org/?probe=7ff33d80d7) | Jul 19, 2023 |
| Dell          | 02YRK5 A03                  | Desktop     | [a1f7c7f053](https://linux-hardware.org/?probe=a1f7c7f053) | Jul 19, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [cdad3aa931](https://linux-hardware.org/?probe=cdad3aa931) | Jul 19, 2023 |
| Intel         | H61                         | Desktop     | [10428f5c68](https://linux-hardware.org/?probe=10428f5c68) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [bddb3e26c1](https://linux-hardware.org/?probe=bddb3e26c1) | Jul 19, 2023 |
| Avell High... | B.ON                        | Notebook    | [bf1f683383](https://linux-hardware.org/?probe=bf1f683383) | Jul 18, 2023 |
| LG Electro... | P420-G.BE42P1               | Notebook    | [9dea573574](https://linux-hardware.org/?probe=9dea573574) | Jul 18, 2023 |
| Positivo      | N4340                       | Notebook    | [fdcc9c264b](https://linux-hardware.org/?probe=fdcc9c264b) | Jul 18, 2023 |
| Positivo      | N4340                       | Notebook    | [1a7db9f33d](https://linux-hardware.org/?probe=1a7db9f33d) | Jul 18, 2023 |
| Positivo      | W942SW_SW1                  | Notebook    | [f8f65185cd](https://linux-hardware.org/?probe=f8f65185cd) | Jul 18, 2023 |
| Acer          | One S1003                   | Tablet      | [380ae70fb2](https://linux-hardware.org/?probe=380ae70fb2) | Jul 18, 2023 |
| Positivo      | Mobile                      | Notebook    | [1a6243fc5d](https://linux-hardware.org/?probe=1a6243fc5d) | Jul 18, 2023 |
| Positivo      | Mobile                      | Notebook    | [0c194a9d1d](https://linux-hardware.org/?probe=0c194a9d1d) | Jul 18, 2023 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [c2ac257f6e](https://linux-hardware.org/?probe=c2ac257f6e) | Jul 18, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [d0fff20fb0](https://linux-hardware.org/?probe=d0fff20fb0) | Jul 18, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [4cdb03ec24](https://linux-hardware.org/?probe=4cdb03ec24) | Jul 18, 2023 |
| Multilaser    | PC024                       | Notebook    | [b1220586b0](https://linux-hardware.org/?probe=b1220586b0) | Jul 18, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | Desktop     | [69f0859638](https://linux-hardware.org/?probe=69f0859638) | Jul 18, 2023 |
| ASUSTek       | P8H61-M LE/BR               | Desktop     | [0d9c612141](https://linux-hardware.org/?probe=0d9c612141) | Jul 17, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [0236d26da7](https://linux-hardware.org/?probe=0236d26da7) | Jul 17, 2023 |
| Dell          | 0WKGTH A02                  | Server      | [00c711574a](https://linux-hardware.org/?probe=00c711574a) | Jul 17, 2023 |
| Multilaser    | PC024                       | Notebook    | [04c0168bce](https://linux-hardware.org/?probe=04c0168bce) | Jul 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [86f515ebce](https://linux-hardware.org/?probe=86f515ebce) | Jul 17, 2023 |
| Multilaser    | PC204                       | Notebook    | [35e4b7c5c9](https://linux-hardware.org/?probe=35e4b7c5c9) | Jul 17, 2023 |
| Unknown       | TU-142                      | Notebook    | [d62ade82c2](https://linux-hardware.org/?probe=d62ade82c2) | Jul 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [4abe81669a](https://linux-hardware.org/?probe=4abe81669a) | Jul 17, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [25737bce66](https://linux-hardware.org/?probe=25737bce66) | Jul 17, 2023 |
| PCWare        | APM-A520G                   | Desktop     | [aefd780df7](https://linux-hardware.org/?probe=aefd780df7) | Jul 17, 2023 |
| LG Electro... | A410-G.BC48P1               | Notebook    | [947acba673](https://linux-hardware.org/?probe=947acba673) | Jul 17, 2023 |
| Digibras      | NH4CU53                     | Notebook    | [14efcb6869](https://linux-hardware.org/?probe=14efcb6869) | Jul 17, 2023 |
| Acer          | Aspire A315-23G             | Notebook    | [df26ae3dab](https://linux-hardware.org/?probe=df26ae3dab) | Jul 17, 2023 |
| Biostar       | B450MH                      | Desktop     | [22909715b3](https://linux-hardware.org/?probe=22909715b3) | Jul 16, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [2d896167d8](https://linux-hardware.org/?probe=2d896167d8) | Jul 16, 2023 |
| Acer          | Aspire 5920                 | Notebook    | [f574cf0363](https://linux-hardware.org/?probe=f574cf0363) | Jul 16, 2023 |
| Intel         | powered classmate PC        | Notebook    | [fc6b28eb14](https://linux-hardware.org/?probe=fc6b28eb14) | Jul 16, 2023 |
| Dell          | G15 5520                    | Notebook    | [ed22e67151](https://linux-hardware.org/?probe=ed22e67151) | Jul 16, 2023 |
| Compaq        | 420                         | Notebook    | [e5b8695df7](https://linux-hardware.org/?probe=e5b8695df7) | Jul 16, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [0e3bc07183](https://linux-hardware.org/?probe=0e3bc07183) | Jul 16, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [428df654fb](https://linux-hardware.org/?probe=428df654fb) | Jul 16, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [7278a4ed50](https://linux-hardware.org/?probe=7278a4ed50) | Jul 16, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [46cfd28279](https://linux-hardware.org/?probe=46cfd28279) | Jul 16, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [e46208d592](https://linux-hardware.org/?probe=e46208d592) | Jul 16, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [fd05b31515](https://linux-hardware.org/?probe=fd05b31515) | Jul 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [45c881b739](https://linux-hardware.org/?probe=45c881b739) | Jul 16, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [f81eae6d45](https://linux-hardware.org/?probe=f81eae6d45) | Jul 16, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [19b39ef686](https://linux-hardware.org/?probe=19b39ef686) | Jul 16, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [9b0f9e2480](https://linux-hardware.org/?probe=9b0f9e2480) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [b7992c5de7](https://linux-hardware.org/?probe=b7992c5de7) | Jul 16, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [4767e5dc31](https://linux-hardware.org/?probe=4767e5dc31) | Jul 15, 2023 |
| Acer          | Aspire A515-41G             | Notebook    | [a9cb1108f6](https://linux-hardware.org/?probe=a9cb1108f6) | Jul 15, 2023 |
| Acer          | One S1003                   | Tablet      | [0e200bc1a5](https://linux-hardware.org/?probe=0e200bc1a5) | Jul 15, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [f747d5537e](https://linux-hardware.org/?probe=f747d5537e) | Jul 15, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [d7512ceea8](https://linux-hardware.org/?probe=d7512ceea8) | Jul 15, 2023 |
| Positivo      | Mobile                      | Notebook    | [fdc2d91a25](https://linux-hardware.org/?probe=fdc2d91a25) | Jul 15, 2023 |
| Gigabyte      | Z370M AORUS Gaming-CF       | Desktop     | [64a0d52846](https://linux-hardware.org/?probe=64a0d52846) | Jul 15, 2023 |
| Lenovo        | Legion 5 15IMH05H 82CF      | Notebook    | [804b227bff](https://linux-hardware.org/?probe=804b227bff) | Jul 15, 2023 |
| Gigabyte      | Z490M GAMING X              | Desktop     | [fc51c8fd14](https://linux-hardware.org/?probe=fc51c8fd14) | Jul 15, 2023 |
| Gigabyte      | Z490M GAMING X              | Desktop     | [1222689443](https://linux-hardware.org/?probe=1222689443) | Jul 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [c9cc25539e](https://linux-hardware.org/?probe=c9cc25539e) | Jul 15, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [34871aac58](https://linux-hardware.org/?probe=34871aac58) | Jul 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [5fe3ea6d25](https://linux-hardware.org/?probe=5fe3ea6d25) | Jul 15, 2023 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [92bd2944cb](https://linux-hardware.org/?probe=92bd2944cb) | Jul 15, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [f472934f38](https://linux-hardware.org/?probe=f472934f38) | Jul 15, 2023 |
| Lenovo        | ThinkPad X250 20CL00DHBR    | Notebook    | [dd92f9ce05](https://linux-hardware.org/?probe=dd92f9ce05) | Jul 14, 2023 |
| Alienware     | m15 R7                      | Notebook    | [99e796a389](https://linux-hardware.org/?probe=99e796a389) | Jul 14, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [c58d69659f](https://linux-hardware.org/?probe=c58d69659f) | Jul 14, 2023 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [40a2bef1f0](https://linux-hardware.org/?probe=40a2bef1f0) | Jul 14, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [e34b3f4c71](https://linux-hardware.org/?probe=e34b3f4c71) | Jul 14, 2023 |
| Dell          | 0T656F A02                  | Desktop     | [9455dc5a07](https://linux-hardware.org/?probe=9455dc5a07) | Jul 14, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [c8179fd349](https://linux-hardware.org/?probe=c8179fd349) | Jul 14, 2023 |
| Alienware     | m15 R7                      | Notebook    | [e80cfeb390](https://linux-hardware.org/?probe=e80cfeb390) | Jul 14, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [dc3059f5b9](https://linux-hardware.org/?probe=dc3059f5b9) | Jul 14, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [718dc0f09e](https://linux-hardware.org/?probe=718dc0f09e) | Jul 14, 2023 |
| GALAX         | A320M G10g                  | Desktop     | [730e46d4f0](https://linux-hardware.org/?probe=730e46d4f0) | Jul 14, 2023 |
| Lenovo        | ThinkPad X260 20F5S4NR00    | Notebook    | [281c5a429c](https://linux-hardware.org/?probe=281c5a429c) | Jul 13, 2023 |
| Positivo      | W2150G-V2 11171347          | All in one  | [7aef4523aa](https://linux-hardware.org/?probe=7aef4523aa) | Jul 13, 2023 |
| ASUSTek       | STRIX Z270G GAMING          | Desktop     | [1857fae531](https://linux-hardware.org/?probe=1857fae531) | Jul 13, 2023 |
| Dell          | 0WKGTH A02                  | Server      | [13f3a107dc](https://linux-hardware.org/?probe=13f3a107dc) | Jul 13, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [29a9ad60a6](https://linux-hardware.org/?probe=29a9ad60a6) | Jul 13, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [d63b2efc8b](https://linux-hardware.org/?probe=d63b2efc8b) | Jul 13, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [c347746634](https://linux-hardware.org/?probe=c347746634) | Jul 13, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [adad96c487](https://linux-hardware.org/?probe=adad96c487) | Jul 13, 2023 |
| Positivo      | POS-EAA75DE                 | Desktop     | [3307527ada](https://linux-hardware.org/?probe=3307527ada) | Jul 13, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [f7a66609af](https://linux-hardware.org/?probe=f7a66609af) | Jul 13, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [56b110f152](https://linux-hardware.org/?probe=56b110f152) | Jul 13, 2023 |
| Dell          | Inspiron 5458               | Notebook    | [4760e0c113](https://linux-hardware.org/?probe=4760e0c113) | Jul 13, 2023 |
| Dell          | 04YP6J A03                  | Desktop     | [55d6cad717](https://linux-hardware.org/?probe=55d6cad717) | Jul 13, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [ad9fd505fa](https://linux-hardware.org/?probe=ad9fd505fa) | Jul 13, 2023 |
| Positivo      | A14CR6A                     | Notebook    | [7ad49c61bd](https://linux-hardware.org/?probe=7ad49c61bd) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [392b02a797](https://linux-hardware.org/?probe=392b02a797) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [9cab0f6446](https://linux-hardware.org/?probe=9cab0f6446) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c1a6aea2fc](https://linux-hardware.org/?probe=c1a6aea2fc) | Jul 13, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [fbc602a7b6](https://linux-hardware.org/?probe=fbc602a7b6) | Jul 12, 2023 |
| Positivo      | Mobile                      | Notebook    | [463636c0a2](https://linux-hardware.org/?probe=463636c0a2) | Jul 12, 2023 |
| Unknown       | EA A520M-E                  | Desktop     | [184201d556](https://linux-hardware.org/?probe=184201d556) | Jul 12, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [480fe73577](https://linux-hardware.org/?probe=480fe73577) | Jul 12, 2023 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [38facb34d4](https://linux-hardware.org/?probe=38facb34d4) | Jul 12, 2023 |
| Positivo      | Donatello                   | Notebook    | [c9740822e6](https://linux-hardware.org/?probe=c9740822e6) | Jul 12, 2023 |
| Acer          | Aspire A515-54              | Notebook    | [64e1f03cea](https://linux-hardware.org/?probe=64e1f03cea) | Jul 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8980149c48](https://linux-hardware.org/?probe=8980149c48) | Jul 11, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [e688a998bc](https://linux-hardware.org/?probe=e688a998bc) | Jul 11, 2023 |
| ASUSTek       | M4A78                       | Desktop     | [d9adfecb80](https://linux-hardware.org/?probe=d9adfecb80) | Jul 11, 2023 |
| Positivo      | POS-PIQ77CL POSITIVO        | Desktop     | [bad8c925e6](https://linux-hardware.org/?probe=bad8c925e6) | Jul 11, 2023 |
| Positivo      | POS-PIQ77CL POSITIVO        | Desktop     | [f754f1e59b](https://linux-hardware.org/?probe=f754f1e59b) | Jul 11, 2023 |
| HP            | Folio 13                    | Notebook    | [864b74d611](https://linux-hardware.org/?probe=864b74d611) | Jul 11, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [154a4104b1](https://linux-hardware.org/?probe=154a4104b1) | Jul 11, 2023 |
| OEM           | B75 Ver:1.41                | Desktop     | [68c3f1b61c](https://linux-hardware.org/?probe=68c3f1b61c) | Jul 11, 2023 |
| Pegatron      | IPMH61P1                    | Desktop     | [9aa934f232](https://linux-hardware.org/?probe=9aa934f232) | Jul 11, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [a761bfffd2](https://linux-hardware.org/?probe=a761bfffd2) | Jul 11, 2023 |
| HP            | Folio 13                    | Notebook    | [35d5a3c2a3](https://linux-hardware.org/?probe=35d5a3c2a3) | Jul 11, 2023 |
| HP            | 3047h                       | Desktop     | [1a4c2d4702](https://linux-hardware.org/?probe=1a4c2d4702) | Jul 11, 2023 |
| Dell          | Latitude E5410              | Notebook    | [8d980136c2](https://linux-hardware.org/?probe=8d980136c2) | Jul 10, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [e22f8030d3](https://linux-hardware.org/?probe=e22f8030d3) | Jul 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [0e411803b2](https://linux-hardware.org/?probe=0e411803b2) | Jul 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [8c2add9768](https://linux-hardware.org/?probe=8c2add9768) | Jul 10, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [b5a021ae8a](https://linux-hardware.org/?probe=b5a021ae8a) | Jul 10, 2023 |
| Positivo      | POS-MIH61CF POSITIVO        | Desktop     | [02113d0b75](https://linux-hardware.org/?probe=02113d0b75) | Jul 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [2cc9f44232](https://linux-hardware.org/?probe=2cc9f44232) | Jul 10, 2023 |
| Avell High... | A52 LIV                     | Notebook    | [eeee2d0bf9](https://linux-hardware.org/?probe=eeee2d0bf9) | Jul 10, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [b904121800](https://linux-hardware.org/?probe=b904121800) | Jul 10, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [16aac702d5](https://linux-hardware.org/?probe=16aac702d5) | Jul 10, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [5477254db4](https://linux-hardware.org/?probe=5477254db4) | Jul 10, 2023 |
| Dell          | Latitude 3490               | Notebook    | [6fcb4ace67](https://linux-hardware.org/?probe=6fcb4ace67) | Jul 10, 2023 |
| Compaq        | 420                         | Notebook    | [6f4350d53e](https://linux-hardware.org/?probe=6f4350d53e) | Jul 10, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [b463aaca78](https://linux-hardware.org/?probe=b463aaca78) | Jul 10, 2023 |
| GALAX         | A320M G10g                  | Desktop     | [8ab8387585](https://linux-hardware.org/?probe=8ab8387585) | Jul 10, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [7c3e56e08a](https://linux-hardware.org/?probe=7c3e56e08a) | Jul 10, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [9a2170442d](https://linux-hardware.org/?probe=9a2170442d) | Jul 09, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [49c5ec535d](https://linux-hardware.org/?probe=49c5ec535d) | Jul 09, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [ccc541ee78](https://linux-hardware.org/?probe=ccc541ee78) | Jul 09, 2023 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [5e41313f45](https://linux-hardware.org/?probe=5e41313f45) | Jul 09, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [7790bc9f7b](https://linux-hardware.org/?probe=7790bc9f7b) | Jul 09, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [afc295d4b4](https://linux-hardware.org/?probe=afc295d4b4) | Jul 09, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [065b0237d3](https://linux-hardware.org/?probe=065b0237d3) | Jul 09, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [cc7487e50f](https://linux-hardware.org/?probe=cc7487e50f) | Jul 09, 2023 |
| Dell          | Latitude 5400               | Notebook    | [e8b701bf4e](https://linux-hardware.org/?probe=e8b701bf4e) | Jul 09, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [798f921e70](https://linux-hardware.org/?probe=798f921e70) | Jul 09, 2023 |
| Acer          | Predator G3-572             | Notebook    | [fe7753845c](https://linux-hardware.org/?probe=fe7753845c) | Jul 09, 2023 |
| HP            | G42                         | Notebook    | [e215b464bf](https://linux-hardware.org/?probe=e215b464bf) | Jul 09, 2023 |
| HP            | ProBook 6460b               | Notebook    | [af3006237f](https://linux-hardware.org/?probe=af3006237f) | Jul 09, 2023 |
| HP            | Pavilion dm3                | Notebook    | [a1bc8d5217](https://linux-hardware.org/?probe=a1bc8d5217) | Jul 09, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [b4b1f263a8](https://linux-hardware.org/?probe=b4b1f263a8) | Jul 08, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [502c216e98](https://linux-hardware.org/?probe=502c216e98) | Jul 08, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [e699ffe719](https://linux-hardware.org/?probe=e699ffe719) | Jul 08, 2023 |
| Unknown       | X99-GT                      | Desktop     | [34c4fadab5](https://linux-hardware.org/?probe=34c4fadab5) | Jul 08, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [a2487119a6](https://linux-hardware.org/?probe=a2487119a6) | Jul 08, 2023 |
| GALAX         | A320M G10g                  | Desktop     | [21dab37c75](https://linux-hardware.org/?probe=21dab37c75) | Jul 08, 2023 |
| Unknown       | X99-GT                      | Desktop     | [de745928b7](https://linux-hardware.org/?probe=de745928b7) | Jul 08, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [cf96aafbc0](https://linux-hardware.org/?probe=cf96aafbc0) | Jul 08, 2023 |
| Dell          | 0CU409                      | Desktop     | [196ea8332b](https://linux-hardware.org/?probe=196ea8332b) | Jul 08, 2023 |
| Positivo      | POS-PIG43BC SIM             | Desktop     | [42727a7888](https://linux-hardware.org/?probe=42727a7888) | Jul 08, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [8337bfbb61](https://linux-hardware.org/?probe=8337bfbb61) | Jul 08, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | Desktop     | [e07a2eb978](https://linux-hardware.org/?probe=e07a2eb978) | Jul 08, 2023 |
| HP            | 14                          | Notebook    | [71d49b008d](https://linux-hardware.org/?probe=71d49b008d) | Jul 08, 2023 |
| HP            | 14                          | Notebook    | [ba511c29ac](https://linux-hardware.org/?probe=ba511c29ac) | Jul 08, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [0a2ad7c1a6](https://linux-hardware.org/?probe=0a2ad7c1a6) | Jul 08, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [4bcab5adb1](https://linux-hardware.org/?probe=4bcab5adb1) | Jul 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [28b061f34f](https://linux-hardware.org/?probe=28b061f34f) | Jul 08, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [2f16685519](https://linux-hardware.org/?probe=2f16685519) | Jul 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [dd8bd37036](https://linux-hardware.org/?probe=dd8bd37036) | Jul 08, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [488366cee5](https://linux-hardware.org/?probe=488366cee5) | Jul 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [63669f1312](https://linux-hardware.org/?probe=63669f1312) | Jul 08, 2023 |
| Compaq        | Presario CQ-14              | Desktop     | [9ce9813d5a](https://linux-hardware.org/?probe=9ce9813d5a) | Jul 08, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [f9a1d993b2](https://linux-hardware.org/?probe=f9a1d993b2) | Jul 07, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [d695952680](https://linux-hardware.org/?probe=d695952680) | Jul 07, 2023 |
| HP            | Folio 13                    | Notebook    | [dd1a09fa9d](https://linux-hardware.org/?probe=dd1a09fa9d) | Jul 07, 2023 |
| Positivo      | POS-PIQ77CL POSITIVO        | Desktop     | [c9ccceb765](https://linux-hardware.org/?probe=c9ccceb765) | Jul 07, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [f60025eb2c](https://linux-hardware.org/?probe=f60025eb2c) | Jul 07, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [901c7b45c2](https://linux-hardware.org/?probe=901c7b45c2) | Jul 07, 2023 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [54262c3aeb](https://linux-hardware.org/?probe=54262c3aeb) | Jul 07, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [5ee0aa7d94](https://linux-hardware.org/?probe=5ee0aa7d94) | Jul 07, 2023 |
| Acer          | Mammoth                     | Notebook    | [2cac6d75d0](https://linux-hardware.org/?probe=2cac6d75d0) | Jul 07, 2023 |
| Sony          | VPCSB25FB                   | Notebook    | [fda12b9c70](https://linux-hardware.org/?probe=fda12b9c70) | Jul 07, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [7fca58229c](https://linux-hardware.org/?probe=7fca58229c) | Jul 07, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [fdb4fd8cb4](https://linux-hardware.org/?probe=fdb4fd8cb4) | Jul 07, 2023 |
| Dell          | Inspiron 5447               | Notebook    | [284afde913](https://linux-hardware.org/?probe=284afde913) | Jul 07, 2023 |
| Dell          | Inspiron 5447               | Notebook    | [22e09bd073](https://linux-hardware.org/?probe=22e09bd073) | Jul 07, 2023 |
| HP            | 871A                        | Mini pc     | [f894712890](https://linux-hardware.org/?probe=f894712890) | Jul 06, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [e657049abf](https://linux-hardware.org/?probe=e657049abf) | Jul 06, 2023 |
| HP            | 871A                        | Mini pc     | [b00edd34fb](https://linux-hardware.org/?probe=b00edd34fb) | Jul 06, 2023 |
| Dell          | 0GFYJR A00                  | Server      | [573c8bd5bd](https://linux-hardware.org/?probe=573c8bd5bd) | Jul 06, 2023 |
| Gigabyte      | A520M K V2                  | Desktop     | [7d81f81cce](https://linux-hardware.org/?probe=7d81f81cce) | Jul 06, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | Desktop     | [88649252eb](https://linux-hardware.org/?probe=88649252eb) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f7991ee84b](https://linux-hardware.org/?probe=f7991ee84b) | Jul 06, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [7eb9d089cf](https://linux-hardware.org/?probe=7eb9d089cf) | Jul 06, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [2d20ffc659](https://linux-hardware.org/?probe=2d20ffc659) | Jul 06, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [681a43f02f](https://linux-hardware.org/?probe=681a43f02f) | Jul 06, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [6539d1f91c](https://linux-hardware.org/?probe=6539d1f91c) | Jul 06, 2023 |
| Dell          | Latitude E6420              | Notebook    | [620b3c9397](https://linux-hardware.org/?probe=620b3c9397) | Jul 06, 2023 |
| Dell          | G3 3590                     | Notebook    | [e3cfb2968a](https://linux-hardware.org/?probe=e3cfb2968a) | Jul 06, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [f2a99b72dc](https://linux-hardware.org/?probe=f2a99b72dc) | Jul 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [25ea01643a](https://linux-hardware.org/?probe=25ea01643a) | Jul 06, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [c85ac748f8](https://linux-hardware.org/?probe=c85ac748f8) | Jul 06, 2023 |
| HP            | Pavilion dv4 2055br         | Notebook    | [d06fc3c63a](https://linux-hardware.org/?probe=d06fc3c63a) | Jul 06, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [2943ff2787](https://linux-hardware.org/?probe=2943ff2787) | Jul 06, 2023 |
| Dell          | Latitude 3420               | Notebook    | [346bb9a98d](https://linux-hardware.org/?probe=346bb9a98d) | Jul 06, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [f156a2bbfa](https://linux-hardware.org/?probe=f156a2bbfa) | Jul 06, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [9b01a450b1](https://linux-hardware.org/?probe=9b01a450b1) | Jul 05, 2023 |
| Lenovo        | G405                        | Notebook    | [2246272bf6](https://linux-hardware.org/?probe=2246272bf6) | Jul 05, 2023 |
| Dell          | 0WKGTH A02                  | Server      | [4bbbfd7eb9](https://linux-hardware.org/?probe=4bbbfd7eb9) | Jul 05, 2023 |
| Dell          | Latitude 3490               | Notebook    | [a730cef547](https://linux-hardware.org/?probe=a730cef547) | Jul 05, 2023 |
| Gigabyte      | G1.Sniper H6                | Desktop     | [7592c0cc37](https://linux-hardware.org/?probe=7592c0cc37) | Jul 05, 2023 |
| Gigabyte      | G1.Sniper H6                | Desktop     | [71505f347f](https://linux-hardware.org/?probe=71505f347f) | Jul 05, 2023 |
| Dell          | G3 3590                     | Notebook    | [35906fded9](https://linux-hardware.org/?probe=35906fded9) | Jul 05, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [919f65a256](https://linux-hardware.org/?probe=919f65a256) | Jul 05, 2023 |
| ASUSTek       | VX7SX                       | Notebook    | [2ef4295d22](https://linux-hardware.org/?probe=2ef4295d22) | Jul 05, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [3ec7b573fc](https://linux-hardware.org/?probe=3ec7b573fc) | Jul 05, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [56609b5da2](https://linux-hardware.org/?probe=56609b5da2) | Jul 05, 2023 |
| Lenovo        | Yoga 510-14ISK 80UK         | Notebook    | [7a1c9a74b9](https://linux-hardware.org/?probe=7a1c9a74b9) | Jul 05, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [eef5ee5c9a](https://linux-hardware.org/?probe=eef5ee5c9a) | Jul 05, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [951a1de3df](https://linux-hardware.org/?probe=951a1de3df) | Jul 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [708fb65c2c](https://linux-hardware.org/?probe=708fb65c2c) | Jul 05, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [6b1beb7eeb](https://linux-hardware.org/?probe=6b1beb7eeb) | Jul 05, 2023 |
| Aierben       | NA17                        | Desktop     | [462b502bab](https://linux-hardware.org/?probe=462b502bab) | Jul 05, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [e2706e4472](https://linux-hardware.org/?probe=e2706e4472) | Jul 05, 2023 |
| Megaware      | MW-H61H2-M2                 | Desktop     | [b86248bd97](https://linux-hardware.org/?probe=b86248bd97) | Jul 05, 2023 |
| Positivo      | POS-EIH61CE SIM             | Desktop     | [48b35c757d](https://linux-hardware.org/?probe=48b35c757d) | Jul 05, 2023 |
| Lenovo        | ThinkPad X250 20CL00DHBR    | Notebook    | [e8f0daea94](https://linux-hardware.org/?probe=e8f0daea94) | Jul 04, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | Desktop     | [941c70d512](https://linux-hardware.org/?probe=941c70d512) | Jul 04, 2023 |
| Intel         | H55                         | Desktop     | [8f8ff68380](https://linux-hardware.org/?probe=8f8ff68380) | Jul 04, 2023 |
| Standard      | ECT                         | Notebook    | [42f38309b9](https://linux-hardware.org/?probe=42f38309b9) | Jul 04, 2023 |
| Dell          | Vostro 1000                 | Notebook    | [b83feae6f5](https://linux-hardware.org/?probe=b83feae6f5) | Jul 04, 2023 |
| Unknown       | Unknown                     | Other       | [f49e789b52](https://linux-hardware.org/?probe=f49e789b52) | Jul 04, 2023 |
| Acer          | Aspire ES1-411              | Notebook    | [898ea84872](https://linux-hardware.org/?probe=898ea84872) | Jul 04, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [234e7f985d](https://linux-hardware.org/?probe=234e7f985d) | Jul 04, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [700348835b](https://linux-hardware.org/?probe=700348835b) | Jul 04, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [d3aeb3e580](https://linux-hardware.org/?probe=d3aeb3e580) | Jul 03, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [7ee43d9cad](https://linux-hardware.org/?probe=7ee43d9cad) | Jul 03, 2023 |
| Intel         | H61                         | Desktop     | [e841a13522](https://linux-hardware.org/?probe=e841a13522) | Jul 03, 2023 |
| ECS           | H55H-M2                     | Desktop     | [344ce5bb17](https://linux-hardware.org/?probe=344ce5bb17) | Jul 03, 2023 |
| Multilaser    | M8WPlus                     | Tablet      | [d2ebf8fad9](https://linux-hardware.org/?probe=d2ebf8fad9) | Jul 03, 2023 |
| Dell          | 0X904N A05                  | Server      | [b7335a46c8](https://linux-hardware.org/?probe=b7335a46c8) | Jul 03, 2023 |
| Positivo      | C14CU51                     | Notebook    | [8b8d839dc0](https://linux-hardware.org/?probe=8b8d839dc0) | Jul 03, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [c073941827](https://linux-hardware.org/?probe=c073941827) | Jul 03, 2023 |
| GPD           | MicroPC                     | Notebook    | [f666f4c574](https://linux-hardware.org/?probe=f666f4c574) | Jul 03, 2023 |
| HP            | Folio 13                    | Notebook    | [faf3cb7d1f](https://linux-hardware.org/?probe=faf3cb7d1f) | Jul 03, 2023 |
| Intel         | H55                         | Desktop     | [1ed1ee7e20](https://linux-hardware.org/?probe=1ed1ee7e20) | Jul 03, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7cd68e8f8b](https://linux-hardware.org/?probe=7cd68e8f8b) | Jul 03, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [f78f6977d9](https://linux-hardware.org/?probe=f78f6977d9) | Jul 03, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [cfaaea2608](https://linux-hardware.org/?probe=cfaaea2608) | Jul 03, 2023 |
| Intel         | H61                         | Desktop     | [f18dd431c3](https://linux-hardware.org/?probe=f18dd431c3) | Jul 03, 2023 |
| Lenovo        | ThinkPad T420 4180AG3       | Notebook    | [21fe808c05](https://linux-hardware.org/?probe=21fe808c05) | Jul 02, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [63a0b07325](https://linux-hardware.org/?probe=63a0b07325) | Jul 02, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [8120591fdf](https://linux-hardware.org/?probe=8120591fdf) | Jul 02, 2023 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [4a3acc3b0d](https://linux-hardware.org/?probe=4a3acc3b0d) | Jul 02, 2023 |
| Intel         | H55                         | Desktop     | [446ffab057](https://linux-hardware.org/?probe=446ffab057) | Jul 02, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a66c76ab6c](https://linux-hardware.org/?probe=a66c76ab6c) | Jul 02, 2023 |
| Positivo      | Q464B                       | Notebook    | [9dad5f0aa1](https://linux-hardware.org/?probe=9dad5f0aa1) | Jul 02, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [83da477284](https://linux-hardware.org/?probe=83da477284) | Jul 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d0ab54293f](https://linux-hardware.org/?probe=d0ab54293f) | Jul 02, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [c0fa0d6c73](https://linux-hardware.org/?probe=c0fa0d6c73) | Jul 02, 2023 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [5248df0795](https://linux-hardware.org/?probe=5248df0795) | Jul 01, 2023 |
| Intel         | H61                         | Desktop     | [5b18122404](https://linux-hardware.org/?probe=5b18122404) | Jul 01, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [07f04b7377](https://linux-hardware.org/?probe=07f04b7377) | Jul 01, 2023 |
| Intel         | H61                         | Desktop     | [4664a58c9b](https://linux-hardware.org/?probe=4664a58c9b) | Jul 01, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [65c2a81637](https://linux-hardware.org/?probe=65c2a81637) | Jul 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [8b4c8e0e14](https://linux-hardware.org/?probe=8b4c8e0e14) | Jul 01, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [7797ece08f](https://linux-hardware.org/?probe=7797ece08f) | Jul 01, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [83dd07d2a7](https://linux-hardware.org/?probe=83dd07d2a7) | Jul 01, 2023 |
| Acer          | JM11-MS                     | Notebook    | [ad02c854e0](https://linux-hardware.org/?probe=ad02c854e0) | Jul 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [bd84f79486](https://linux-hardware.org/?probe=bd84f79486) | Jul 01, 2023 |
| Dell          | Inspiron 5457               | Notebook    | [af20c68e45](https://linux-hardware.org/?probe=af20c68e45) | Jul 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [6896f4aafb](https://linux-hardware.org/?probe=6896f4aafb) | Jul 01, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [1df7c65f40](https://linux-hardware.org/?probe=1df7c65f40) | Jul 01, 2023 |
| ZR            | A320M-F 1005                | Desktop     | [c32d8de777](https://linux-hardware.org/?probe=c32d8de777) | Jun 30, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [292b7f6f0f](https://linux-hardware.org/?probe=292b7f6f0f) | Jun 30, 2023 |
| Intel         | X99 V1.x                    | Desktop     | [8e4ce021b1](https://linux-hardware.org/?probe=8e4ce021b1) | Jun 30, 2023 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [69b69e2a09](https://linux-hardware.org/?probe=69b69e2a09) | Jun 30, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [7c3ce62039](https://linux-hardware.org/?probe=7c3ce62039) | Jun 30, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [8386acaa29](https://linux-hardware.org/?probe=8386acaa29) | Jun 30, 2023 |
| AZW           | SEi                         | Desktop     | [37527da518](https://linux-hardware.org/?probe=37527da518) | Jun 30, 2023 |
| Lenovo        | ThinkPad T495 20NK000XBR    | Notebook    | [2b5e40efaa](https://linux-hardware.org/?probe=2b5e40efaa) | Jun 30, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [3e1517b7a7](https://linux-hardware.org/?probe=3e1517b7a7) | Jun 30, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [b95a7c049a](https://linux-hardware.org/?probe=b95a7c049a) | Jun 30, 2023 |
| eMachines     | eME443                      | Notebook    | [0d6808da66](https://linux-hardware.org/?probe=0d6808da66) | Jun 30, 2023 |
| Intel         | B75                         | Desktop     | [73d881c953](https://linux-hardware.org/?probe=73d881c953) | Jun 30, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7cb124d729](https://linux-hardware.org/?probe=7cb124d729) | Jun 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [136060092c](https://linux-hardware.org/?probe=136060092c) | Jun 30, 2023 |
| Positivo      | Mobile                      | Notebook    | [fdaaf6915b](https://linux-hardware.org/?probe=fdaaf6915b) | Jun 30, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [45d5903c62](https://linux-hardware.org/?probe=45d5903c62) | Jun 30, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [3aa4a11068](https://linux-hardware.org/?probe=3aa4a11068) | Jun 30, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [3a8a822af9](https://linux-hardware.org/?probe=3a8a822af9) | Jun 30, 2023 |
| Positivo      | S14CT01                     | Notebook    | [b70845bd08](https://linux-hardware.org/?probe=b70845bd08) | Jun 29, 2023 |
| Intel         | X99 V1.x                    | Desktop     | [1c7ef9ef35](https://linux-hardware.org/?probe=1c7ef9ef35) | Jun 29, 2023 |
| PCWare        | IPMH61R3                    | Desktop     | [e190259144](https://linux-hardware.org/?probe=e190259144) | Jun 29, 2023 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [d0ec676a22](https://linux-hardware.org/?probe=d0ec676a22) | Jun 29, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [cfbc8c8a97](https://linux-hardware.org/?probe=cfbc8c8a97) | Jun 29, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [b9291d6951](https://linux-hardware.org/?probe=b9291d6951) | Jun 29, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [f0fdd509f7](https://linux-hardware.org/?probe=f0fdd509f7) | Jun 29, 2023 |
| Positivo      | H14CU02                     | Notebook    | [d50e6fbbdc](https://linux-hardware.org/?probe=d50e6fbbdc) | Jun 29, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [bb1cb1ef13](https://linux-hardware.org/?probe=bb1cb1ef13) | Jun 29, 2023 |
| Dell          | Inspiron 1440               | Notebook    | [ed9bcaecd2](https://linux-hardware.org/?probe=ed9bcaecd2) | Jun 29, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [25a1aaf938](https://linux-hardware.org/?probe=25a1aaf938) | Jun 29, 2023 |
| HP            | 0B54h D                     | Desktop     | [c13f21ea22](https://linux-hardware.org/?probe=c13f21ea22) | Jun 29, 2023 |
| Dell          | 0T656F A02                  | Desktop     | [bf4264c797](https://linux-hardware.org/?probe=bf4264c797) | Jun 29, 2023 |
| Sony          | SVE17137CXB                 | Notebook    | [ed6f82dc16](https://linux-hardware.org/?probe=ed6f82dc16) | Jun 29, 2023 |
| MSI           | MS-7438 100                 | Desktop     | [4d0d23065e](https://linux-hardware.org/?probe=4d0d23065e) | Jun 29, 2023 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [0e896bc137](https://linux-hardware.org/?probe=0e896bc137) | Jun 29, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [a41ff8c573](https://linux-hardware.org/?probe=a41ff8c573) | Jun 29, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [5683980090](https://linux-hardware.org/?probe=5683980090) | Jun 28, 2023 |
| Dell          | 00X7CK A04                  | Server      | [c59e7b7f26](https://linux-hardware.org/?probe=c59e7b7f26) | Jun 28, 2023 |
| ZR            | A320M-F 1005                | Desktop     | [f70bb41b80](https://linux-hardware.org/?probe=f70bb41b80) | Jun 28, 2023 |
| Huanan        | Unknown                     | Desktop     | [397d33202e](https://linux-hardware.org/?probe=397d33202e) | Jun 28, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [2f12ef933e](https://linux-hardware.org/?probe=2f12ef933e) | Jun 28, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [966b21f9af](https://linux-hardware.org/?probe=966b21f9af) | Jun 28, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [8147961b6c](https://linux-hardware.org/?probe=8147961b6c) | Jun 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [f64ccf77fb](https://linux-hardware.org/?probe=f64ccf77fb) | Jun 28, 2023 |
| Fill By OE... | Q7700                       | Desktop     | [93c7c01ecb](https://linux-hardware.org/?probe=93c7c01ecb) | Jun 28, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 1533      | 10.75%  |
| Ubuntu 18.04       | 1037      | 7.27%   |
| Ubuntu 22.04       | 581       | 4.08%   |
| OpenMandriva 4.2   | 341       | 2.39%   |
| Pop!_OS 20.04      | 319       | 2.24%   |
| Linux Mint 20      | 315       | 2.21%   |
| OpenMandriva 4.3   | 297       | 2.08%   |
| Linux Mint 19.3    | 287       | 2.01%   |
| Pop!_OS 22.04      | 251       | 1.76%   |
| Linux Mint 19.1    | 235       | 1.65%   |
| Linux Mint 20.3    | 224       | 1.57%   |
| Manjaro            | 221       | 1.55%   |
| Zorin 16           | 220       | 1.54%   |
| Ubuntu 19.04       | 218       | 1.53%   |
| KDE neon 20.04     | 215       | 1.51%   |
| Linux Mint 20.1    | 211       | 1.48%   |
| Debian 11          | 199       | 1.4%    |
| Arch               | 189       | 1.33%   |
| Linux Mint 20.2    | 184       | 1.29%   |
| Arch Rolling       | 184       | 1.29%   |
| Ubuntu 19.10       | 173       | 1.21%   |
| Linux Mint 21.1    | 169       | 1.19%   |
| Debian 10          | 155       | 1.09%   |
| Zorin 15           | 152       | 1.07%   |
| Fedora 38          | 151       | 1.06%   |
| OpenMandriva 23.01 | 128       | 0.9%    |
| Pop!_OS 21.04      | 127       | 0.89%   |
| Pop!_OS 20.10      | 127       | 0.89%   |
| Fedora 37          | 124       | 0.87%   |
| OpenMandriva 23.03 | 121       | 0.85%   |
| Fedora 34          | 120       | 0.84%   |
| Fedora 36          | 119       | 0.83%   |
| Xubuntu 20.04      | 118       | 0.83%   |
| Fedora 32          | 111       | 0.78%   |
| Pop!_OS 21.10      | 110       | 0.77%   |
| Fedora 35          | 110       | 0.77%   |
| Linux Mint 21      | 107       | 0.75%   |
| Fedora 33          | 105       | 0.74%   |
| Linux Mint 19.2    | 103       | 0.72%   |
| Ubuntu MATE 20.04  | 101       | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 3916      | 28.87%  |
| Linux Mint    | 1835      | 13.53%  |
| Endless       | 1064      | 7.84%   |
| OpenMandriva  | 992       | 7.31%   |
| Pop!_OS       | 899       | 6.63%   |
| Fedora        | 853       | 6.29%   |
| Debian        | 500       | 3.69%   |
| Manjaro       | 409       | 3.02%   |
| Zorin         | 381       | 2.81%   |
| Arch          | 360       | 2.65%   |
| KDE neon      | 283       | 2.09%   |
| Xubuntu       | 242       | 1.78%   |
| Kubuntu       | 225       | 1.66%   |
| openSUSE      | 143       | 1.05%   |
| Ubuntu MATE   | 141       | 1.04%   |
| ROSA          | 136       | 1%      |
| Lubuntu       | 114       | 0.84%   |
| Elementary    | 102       | 0.75%   |
| Ubuntu Unity  | 89        | 0.66%   |
| LMDE          | 76        | 0.56%   |
| Kali          | 72        | 0.53%   |
| ArcoLinux     | 71        | 0.52%   |
| Deepin        | 47        | 0.35%   |
| Ubuntu Budgie | 45        | 0.33%   |
| BigLinux      | 43        | 0.32%   |
| LinuxFX       | 40        | 0.29%   |
| Clear Linux   | 37        | 0.27%   |
| CentOS        | 33        | 0.24%   |
| BlackPanther  | 30        | 0.22%   |
| EndeavourOS   | 26        | 0.19%   |
| Gentoo        | 21        | 0.15%   |
| Nobara        | 18        | 0.13%   |
| Garuda Linux  | 18        | 0.13%   |
| Parrot        | 17        | 0.13%   |
| SteamOS       | 16        | 0.12%   |
| Peppermint    | 15        | 0.11%   |
| MX            | 14        | 0.1%    |
| Solus         | 13        | 0.1%    |
| UbuntuDDE     | 12        | 0.09%   |
| Linux Lite    | 12        | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 710       | 4.62%   |
| 5.10.14-desktop-1omv4002 | 330       | 2.15%   |
| 5.8.0-14-generic         | 318       | 2.07%   |
| 5.16.7-desktop-1omv4003  | 279       | 1.81%   |
| 4.15.0-46-generic        | 156       | 1.01%   |
| 5.3.0-28-generic         | 146       | 0.95%   |
| 5.4.0-48-generic         | 138       | 0.9%    |
| 5.4.0-19-generic         | 138       | 0.9%    |
| 5.4.0-7634-generic       | 123       | 0.8%    |
| 6.2.6-desktop-1omv2390   | 119       | 0.77%   |
| 6.1.1-desktop-1omv2290   | 118       | 0.77%   |
| 5.15.0-56-generic        | 118       | 0.77%   |
| 5.11.0-35-generic        | 113       | 0.73%   |
| 5.4.0-58-generic         | 111       | 0.72%   |
| 5.4.0-40-generic         | 111       | 0.72%   |
| 5.4.0-26-generic         | 106       | 0.69%   |
| 5.4.0-52-generic         | 101       | 0.66%   |
| 4.18.0-15-generic        | 97        | 0.63%   |
| 5.4.0-47-generic         | 96        | 0.62%   |
| 5.3.0-40-generic         | 89        | 0.58%   |
| 5.11.0-7620-generic      | 78        | 0.51%   |
| 5.0.0-32-generic         | 78        | 0.51%   |
| 5.3.0-46-generic         | 77        | 0.5%    |
| 5.0.0-37-generic         | 72        | 0.47%   |
| 4.15.0-20-generic        | 72        | 0.47%   |
| 5.4.0-70-generic         | 71        | 0.46%   |
| 6.2.6-76060206-generic   | 68        | 0.44%   |
| 5.4.0-72-generic         | 68        | 0.44%   |
| 5.15.0-52-generic        | 68        | 0.44%   |
| 5.15.0-46-generic        | 68        | 0.44%   |
| 5.4.0-91-generic         | 66        | 0.43%   |
| 5.15.0-47-generic        | 66        | 0.43%   |
| 5.4.0-80-generic         | 63        | 0.41%   |
| 5.3.0-23-generic         | 63        | 0.41%   |
| 5.4.0-29-generic         | 62        | 0.4%    |
| 4.18.0-16-generic        | 62        | 0.4%    |
| 5.4.0-65-generic         | 61        | 0.4%    |
| 5.4.0-37-generic         | 61        | 0.4%    |
| 5.15.0-58-generic        | 61        | 0.4%    |
| 5.4.0-39-generic         | 60        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 3051      | 20.92%  |
| 5.15.0  | 1000      | 6.86%   |
| 4.15.0  | 950       | 6.51%   |
| 5.8.0   | 902       | 6.18%   |
| 5.3.0   | 799       | 5.48%   |
| 5.11.0  | 718       | 4.92%   |
| 5.0.0   | 564       | 3.87%   |
| 5.13.0  | 470       | 3.22%   |
| 4.18.0  | 417       | 2.86%   |
| 5.19.0  | 366       | 2.51%   |
| 5.10.14 | 332       | 2.28%   |
| 5.16.7  | 279       | 1.91%   |
| 5.10.0  | 258       | 1.77%   |
| 6.2.6   | 193       | 1.32%   |
| 4.19.0  | 184       | 1.26%   |
| 6.2.0   | 131       | 0.9%    |
| 6.1.1   | 128       | 0.88%   |
| 6.1.0   | 76        | 0.52%   |
| 6.4.11  | 63        | 0.43%   |
| 5.17.5  | 59        | 0.4%    |
| 6.0.12  | 48        | 0.33%   |
| 4.4.0   | 48        | 0.33%   |
| 5.7.9   | 47        | 0.32%   |
| 5.14.0  | 42        | 0.29%   |
| 4.9.0   | 42        | 0.29%   |
| 5.16.11 | 41        | 0.28%   |
| 5.15.5  | 31        | 0.21%   |
| 5.7.0   | 30        | 0.21%   |
| 5.15.15 | 30        | 0.21%   |
| 6.4.8   | 29        | 0.2%    |
| 5.9.16  | 28        | 0.19%   |
| 6.4.6   | 27        | 0.19%   |
| 5.6.19  | 27        | 0.19%   |
| 4.9.60  | 27        | 0.19%   |
| 5.16.13 | 26        | 0.18%   |
| 6.0.0   | 25        | 0.17%   |
| 5.3.18  | 25        | 0.17%   |
| 5.11.12 | 25        | 0.17%   |
| 4.18.16 | 25        | 0.17%   |
| 6.2.9   | 24        | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 3177      | 22.07%  |
| 5.15    | 1284      | 8.92%   |
| 5.8     | 1015      | 7.05%   |
| 4.15    | 950       | 6.6%    |
| 5.3     | 870       | 6.05%   |
| 5.11    | 816       | 5.67%   |
| 5.10    | 785       | 5.45%   |
| 5.0     | 606       | 4.21%   |
| 5.13    | 563       | 3.91%   |
| 6.2     | 480       | 3.34%   |
| 5.16    | 468       | 3.25%   |
| 5.19    | 467       | 3.24%   |
| 4.18    | 450       | 3.13%   |
| 6.1     | 386       | 2.68%   |
| 4.19    | 220       | 1.53%   |
| 6.4     | 206       | 1.43%   |
| 6.0     | 198       | 1.38%   |
| 5.7     | 172       | 1.2%    |
| 5.17    | 156       | 1.08%   |
| 5.14    | 142       | 0.99%   |
| 5.18    | 139       | 0.97%   |
| 5.6     | 126       | 0.88%   |
| 6.3     | 118       | 0.82%   |
| 5.12    | 113       | 0.79%   |
| 5.9     | 111       | 0.77%   |
| 4.9     | 110       | 0.76%   |
| 4.4     | 54        | 0.38%   |
| 5.5     | 50        | 0.35%   |
| 5.1     | 39        | 0.27%   |
| 5.2     | 29        | 0.2%    |
| 3.10    | 19        | 0.13%   |
| 4.13    | 13        | 0.09%   |
| 4.1     | 12        | 0.08%   |
| 4.20    | 10        | 0.07%   |
| 6.5     | 9         | 0.06%   |
| 4.10    | 9         | 0.06%   |
| 4.12    | 6         | 0.04%   |
| 4.14    | 5         | 0.03%   |
| 4.8     | 3         | 0.02%   |
| 4.17    | 2         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 12605     | 97.36%  |
| i686    | 306       | 2.36%   |
| aarch64 | 23        | 0.18%   |
| armv7l  | 13        | 0.1%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 6212      | 45.86%  |
| KDE5                     | 1847      | 13.63%  |
| Unknown                  | 1840      | 13.58%  |
| X-Cinnamon               | 1126      | 8.31%   |
| XFCE                     | 916       | 6.76%   |
| MATE                     | 382       | 2.82%   |
| KDE                      | 312       | 2.3%    |
| Cinnamon                 | 234       | 1.73%   |
| LXQt                     | 123       | 0.91%   |
| Unity                    | 91        | 0.67%   |
| Pantheon                 | 90        | 0.66%   |
| KDE4                     | 66        | 0.49%   |
| Budgie                   | 65        | 0.48%   |
| Deepin                   | 63        | 0.47%   |
| LXDE                     | 55        | 0.41%   |
| i3                       | 36        | 0.27%   |
| GNOME Flashback          | 16        | 0.12%   |
| GNOME Classic            | 16        | 0.12%   |
| awesome                  | 10        | 0.07%   |
| sway                     | 9         | 0.07%   |
| Openbox                  | 6         | 0.04%   |
| Enlightenment            | 6         | 0.04%   |
| Hyprland                 | 5         | 0.04%   |
| bspwm                    | 4         | 0.03%   |
| icewm                    | 3         | 0.02%   |
| qtile                    | 2         | 0.01%   |
| xmonad                   | 1         | 0.01%   |
| Trinity                  | 1         | 0.01%   |
| Phosh:GNOME              | 1         | 0.01%   |
| Lubuntu                  | 1         | 0.01%   |
| jwm                      | 1         | 0.01%   |
| GNUstep                  | 1         | 0.01%   |
| GNOME:Phosh              | 1         | 0.01%   |
| GNOME-Classic            | 1         | 0.01%   |
| fluxbox                  | 1         | 0.01%   |
| DDE                      | 1         | 0.01%   |
| 03WindowMaker            | 1         | 0.01%   |
| /usr/bin/openbox-session | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 10592     | 79.59%  |
| Wayland | 1712      | 12.86%  |
| Unknown | 909       | 6.83%   |
| Tty     | 93        | 0.7%    |
| Web     | 2         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 8153      | 60.68%  |
| SDDM    | 1604      | 11.94%  |
| GDM     | 1305      | 9.71%   |
| GDM3    | 995       | 7.41%   |
| LightDM | 748       | 5.57%   |
| TDM     | 538       | 4%      |
| KDM     | 66        | 0.49%   |
| XDM     | 12        | 0.09%   |
| SLiM    | 7         | 0.05%   |
| LXDM    | 3         | 0.02%   |
| SLIMSKI | 2         | 0.01%   |
| MDM     | 2         | 0.01%   |
| Ly      | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| pt_BR       | 8768      | 66.15%  |
| en_US       | 2399      | 18.1%   |
| Unknown     | 1703      | 12.85%  |
| C           | 194       | 1.46%   |
| en_GB       | 61        | 0.46%   |
| pt_PT       | 56        | 0.42%   |
| es_ES       | 19        | 0.14%   |
| en_CA       | 11        | 0.08%   |
| fr_FR       | 6         | 0.05%   |
| de_DE       | 5         | 0.04%   |
| POSIX       | 3         | 0.02%   |
| C.UTF8      | 3         | 0.02%   |
| pt_BRutf8   | 2         | 0.02%   |
| ja_JP       | 2         | 0.02%   |
| it_IT       | 2         | 0.02%   |
| en_AG       | 2         | 0.02%   |
| UTF-8       | 1         | 0.01%   |
| ru_RU       | 1         | 0.01%   |
| pt_BR~      | 1         | 0.01%   |
| pt_BR.UTF8  | 1         | 0.01%   |
| es_PY       | 1         | 0.01%   |
| es_MX       | 1         | 0.01%   |
| es_CL       | 1         | 0.01%   |
| es_AR       | 1         | 0.01%   |
| eo          | 1         | 0.01%   |
| en_US.UTF8  | 1         | 0.01%   |
| en_US.utf-8 | 1         | 0.01%   |
| en_US.UFT-8 | 1         | 0.01%   |
| en_IN       | 1         | 0.01%   |
| en_IE.UTF8  | 1         | 0.01%   |
| en_DK       | 1         | 0.01%   |
| en-US       | 1         | 0.01%   |
| em_US       | 1         | 0.01%   |
| de_CH       | 1         | 0.01%   |
| ar_EG       | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 7467      | 56.3%   |
| EFI  | 5795      | 43.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 10035     | 75.37%  |
| Overlay | 1083      | 8.13%   |
| Btrfs   | 1079      | 8.1%    |
| Unknown | 707       | 5.31%   |
| Tmpfs   | 186       | 1.4%    |
| Xfs     | 110       | 0.83%   |
| Zfs     | 49        | 0.37%   |
| Ext3    | 22        | 0.17%   |
| Ext2    | 20        | 0.15%   |
| F2fs    | 18        | 0.14%   |
| Aufs    | 4         | 0.03%   |
| XXXXXXX | 1         | 0.01%   |
| Jfs     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 8485      | 63.74%  |
| GPT     | 3324      | 24.97%  |
| MBR     | 1502      | 11.28%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 11584     | 87.99%  |
| Yes       | 1581      | 12.01%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 9764      | 74.11%  |
| Yes       | 3411      | 25.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Dell                   | 2085      | 16.11%  |
| ASUSTek Computer       | 1708      | 13.2%   |
| Acer                   | 1489      | 11.51%  |
| Lenovo                 | 1113      | 8.6%    |
| Gigabyte Technology    | 839       | 6.48%   |
| Positivo               | 734       | 5.67%   |
| Hewlett-Packard        | 696       | 5.38%   |
| Samsung Electronics    | 660       | 5.1%    |
| Intel                  | 497       | 3.84%   |
| ASRock                 | 429       | 3.32%   |
| Unknown                | 242       | 1.87%   |
| MSI                    | 231       | 1.79%   |
| Sony                   | 162       | 1.25%   |
| Apple                  | 143       | 1.11%   |
| LG Electronics         | 134       | 1.04%   |
| Itautec                | 121       | 0.94%   |
| PCWare                 | 119       | 0.92%   |
| Semp Toshiba           | 114       | 0.88%   |
| Biostar                | 103       | 0.8%    |
| Avell High Performance | 89        | 0.69%   |
| Pegatron               | 73        | 0.56%   |
| Digibras               | 72        | 0.56%   |
| ECS                    | 66        | 0.51%   |
| Multilaser             | 57        | 0.44%   |
| OEM                    | 55        | 0.43%   |
| Philco                 | 50        | 0.39%   |
| Compaq                 | 46        | 0.36%   |
| Positivo Bahia - VAIO  | 41        | 0.32%   |
| Huanan                 | 39        | 0.3%    |
| Toshiba                | 36        | 0.28%   |
| Megaware               | 34        | 0.26%   |
| Foxconn                | 31        | 0.24%   |
| Notebook               | 28        | 0.22%   |
| Clevo                  | 25        | 0.19%   |
| Daten Tecnologia       | 23        | 0.18%   |
| Login Informatica      | 22        | 0.17%   |
| Gateway                | 21        | 0.16%   |
| Google                 | 20        | 0.15%   |
| Compal                 | 19        | 0.15%   |
| MACHINIST              | 18        | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 307       | 2.37%   |
| ASUS All Series                             | 151       | 1.17%   |
| Acer Nitro AN515-54                         | 138       | 1.07%   |
| Positivo Mobile                             | 128       | 0.99%   |
| Intel H61                                   | 94        | 0.73%   |
| Acer Nitro AN515-44                         | 87        | 0.67%   |
| Samsung 340XAA/350XAA/550XAA                | 70        | 0.54%   |
| Acer Aspire A315-53                         | 69        | 0.53%   |
| Dell Inspiron 5566                          | 68        | 0.53%   |
| Lenovo IdeaPad S145-15API 81V7              | 64        | 0.49%   |
| ASUS PRIME B450M-GAMING/BR                  | 64        | 0.49%   |
| Dell Inspiron 15-3567                       | 60        | 0.46%   |
| Lenovo IdeaPad 330-15IKB 81FE               | 59        | 0.46%   |
| Dell Inspiron 3583                          | 59        | 0.46%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 56        | 0.43%   |
| ASRock A320M-HD                             | 55        | 0.43%   |
| Intel H55                                   | 54        | 0.42%   |
| Acer Aspire A315-34                         | 54        | 0.42%   |
| Acer Nitro AN517-51                         | 53        | 0.41%   |
| ASUS PRIME A320M-K/BR                       | 52        | 0.4%    |
| ASUS M5A78L-M LX/BR                         | 52        | 0.4%    |
| Acer Aspire A515-51                         | 52        | 0.4%    |
| Samsung 300E5M/300E5L                       | 49        | 0.38%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 49        | 0.38%   |
| Semp Toshiba STI                            | 47        | 0.36%   |
| Acer Nitro AN515-43                         | 46        | 0.36%   |
| Dell Inspiron 3442                          | 43        | 0.33%   |
| Samsung 550XDA                              | 42        | 0.32%   |
| Positivo S14CT01                            | 42        | 0.32%   |
| HP G42                                      | 42        | 0.32%   |
| Gigabyte H61M-S1                            | 40        | 0.31%   |
| Gigabyte A320M-S2H                          | 40        | 0.31%   |
| Dell Inspiron N4050                         | 40        | 0.31%   |
| Lenovo IdeaPad 3 15ALC6 82MF                | 39        | 0.3%    |
| Itautec Infoway                             | 39        | 0.3%    |
| Acer Nitro AN515-52                         | 39        | 0.3%    |
| Dell Inspiron 3421                          | 38        | 0.29%   |
| ASRock B450M Steel Legend                   | 37        | 0.29%   |
| ASUS P8H61-M LX3 R2.0                       | 36        | 0.28%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 35        | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell Inspiron      | 1173      | 9.06%   |
| Acer Aspire        | 960       | 7.42%   |
| Lenovo IdeaPad     | 551       | 4.26%   |
| Acer Nitro         | 415       | 3.21%   |
| Unknown            | 307       | 2.37%   |
| Dell Vostro        | 260       | 2.01%   |
| ASUS PRIME         | 248       | 1.92%   |
| Lenovo ThinkPad    | 219       | 1.69%   |
| HP Pavilion        | 207       | 1.6%    |
| Dell Latitude      | 198       | 1.53%   |
| Dell OptiPlex      | 171       | 1.32%   |
| ASUS All           | 151       | 1.17%   |
| ASUS VivoBook      | 144       | 1.11%   |
| ASUS M5A78L-M      | 130       | 1%      |
| Positivo Mobile    | 128       | 0.99%   |
| ASUS TUF           | 125       | 0.97%   |
| Itautec Infoway    | 114       | 0.88%   |
| HP Compaq          | 112       | 0.87%   |
| Intel H61          | 98        | 0.76%   |
| ASUS P8H61-M       | 91        | 0.7%    |
| Samsung 340XAA     | 70        | 0.54%   |
| Lenovo ThinkCentre | 69        | 0.53%   |
| Dell G3            | 61        | 0.47%   |
| ASUS ROG           | 58        | 0.45%   |
| ASRock A320M-HD    | 57        | 0.44%   |
| Dell XPS           | 56        | 0.43%   |
| Semp Toshiba STI   | 55        | 0.43%   |
| Intel H55          | 54        | 0.42%   |
| HP ProBook         | 51        | 0.39%   |
| Samsung 300E5M     | 49        | 0.38%   |
| Samsung RV411      | 48        | 0.37%   |
| Samsung 550XDA     | 42        | 0.32%   |
| Positivo S14CT01   | 42        | 0.32%   |
| HP G42             | 42        | 0.32%   |
| Gigabyte H61M-S1   | 40        | 0.31%   |
| Gigabyte A320M-S2H | 40        | 0.31%   |
| Dell System        | 40        | 0.31%   |
| ASRock B450M       | 39        | 0.3%    |
| Acer Predator      | 39        | 0.3%    |
| HP EliteBook       | 38        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 1334      | 10.31%  |
| 2012    | 1290      | 9.97%   |
| 2011    | 1202      | 9.29%   |
| 2018    | 1197      | 9.25%   |
| 2017    | 1033      | 7.98%   |
| 2013    | 974       | 7.53%   |
| 2010    | 815       | 6.3%    |
| 2016    | 793       | 6.13%   |
| 2014    | 771       | 5.96%   |
| 2020    | 736       | 5.69%   |
| 2021    | 564       | 4.36%   |
| 2009    | 553       | 4.27%   |
| 2008    | 518       | 4%      |
| 2015    | 475       | 3.67%   |
| 2007    | 299       | 2.31%   |
| 2022    | 166       | 1.28%   |
| 2006    | 102       | 0.79%   |
| Unknown | 60        | 0.46%   |
| 2005    | 26        | 0.2%    |
| 2023    | 22        | 0.17%   |
| 2004    | 9         | 0.07%   |
| 2003    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 7653      | 59.14%  |
| Desktop        | 4918      | 38.01%  |
| All in one     | 110       | 0.85%   |
| Convertible    | 96        | 0.74%   |
| Mini pc        | 54        | 0.42%   |
| Server         | 48        | 0.37%   |
| System on chip | 32        | 0.25%   |
| Tablet         | 25        | 0.19%   |
| Phone          | 2         | 0.02%   |
| Other          | 1         | 0.01%   |
| Firewall       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 11731     | 89.99%  |
| Enabled  | 1305      | 10.01%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 12916     | 99.81%  |
| Yes  | 24        | 0.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 3563      | 26.98%  |
| 3.01-4.0        | 3390      | 25.67%  |
| 8.01-16.0       | 2289      | 17.34%  |
| 16.01-24.0      | 2081      | 15.76%  |
| 1.01-2.0        | 841       | 6.37%   |
| 32.01-64.0      | 450       | 3.41%   |
| 2.01-3.0        | 279       | 2.11%   |
| 24.01-32.0      | 136       | 1.03%   |
| 64.01-256.0     | 101       | 0.76%   |
| 0.51-1.0        | 63        | 0.48%   |
| More than 256.0 | 7         | 0.05%   |
| 0.01-0.5        | 2         | 0.02%   |
| Unknown         | 2         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 5247      | 36.63%  |
| 2.01-3.0    | 3882      | 27.1%   |
| 3.01-4.0    | 1835      | 12.81%  |
| 4.01-8.0    | 1791      | 12.5%   |
| 0.51-1.0    | 1031      | 7.2%    |
| 8.01-16.0   | 350       | 2.44%   |
| 0.01-0.5    | 129       | 0.9%    |
| 16.01-24.0  | 38        | 0.27%   |
| 24.01-32.0  | 8         | 0.06%   |
| 32.01-64.0  | 5         | 0.03%   |
| Unknown     | 5         | 0.03%   |
| 64.01-256.0 | 2         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 8219      | 61.77%  |
| 2       | 3651      | 27.44%  |
| 3       | 809       | 6.08%   |
| 4       | 310       | 2.33%   |
| 0       | 128       | 0.96%   |
| 5       | 99        | 0.74%   |
| 6       | 58        | 0.44%   |
| 7       | 12        | 0.09%   |
| 8       | 8         | 0.06%   |
| 9       | 6         | 0.05%   |
| 18      | 1         | 0.01%   |
| 15      | 1         | 0.01%   |
| 14      | 1         | 0.01%   |
| 10      | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 8212      | 62.93%  |
| Yes       | 4837      | 37.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 11830     | 91.27%  |
| No        | 1132      | 8.73%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 9470      | 72.59%  |
| No        | 3575      | 27.41%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6614      | 50.55%  |
| No        | 6471      | 49.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Brazil  | 12940     | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Sao Paulo             | 1651      | 12.17%  |
| Rio de Janeiro        | 801       | 5.9%    |
| Brasília             | 421       | 3.1%    |
| Curitiba              | 376       | 2.77%   |
| Belo Horizonte        | 375       | 2.76%   |
| Porto Alegre          | 300       | 2.21%   |
| Fortaleza             | 285       | 2.1%    |
| Campinas              | 205       | 1.51%   |
| Salvador              | 192       | 1.42%   |
| Recife                | 174       | 1.28%   |
| Goiânia              | 154       | 1.14%   |
| Florianópolis        | 149       | 1.1%    |
| Santo André          | 145       | 1.07%   |
| Natal                 | 122       | 0.9%    |
| Osasco                | 112       | 0.83%   |
| Manaus                | 109       | 0.8%    |
| Sao José dos Campos  | 105       | 0.77%   |
| Niterói              | 100       | 0.74%   |
| Guarulhos             | 98        | 0.72%   |
| Campo Grande          | 98        | 0.72%   |
| Sao Luís             | 88        | 0.65%   |
| Belém                | 87        | 0.64%   |
| Sorocaba              | 85        | 0.63%   |
| Maringá              | 85        | 0.63%   |
| Joao Pessoa           | 84        | 0.62%   |
| Joinville             | 83        | 0.61%   |
| Londrina              | 80        | 0.59%   |
| Teresina              | 76        | 0.56%   |
| Uberlândia           | 74        | 0.55%   |
| Aracaju               | 73        | 0.54%   |
| Ribeirao Preto        | 72        | 0.53%   |
| Juiz de Fora          | 68        | 0.5%    |
| Maceió               | 67        | 0.49%   |
| Duque de Caxias       | 60        | 0.44%   |
| Serra                 | 59        | 0.43%   |
| Sao Jose              | 59        | 0.43%   |
| Cuiabá               | 58        | 0.43%   |
| Sao Bernardo do Campo | 56        | 0.41%   |
| Sao Carlos            | 55        | 0.41%   |
| Blumenau              | 55        | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 3596      | 4644   | 19.9%   |
| Seagate                        | 3426      | 4859   | 18.96%  |
| Kingston                       | 1868      | 2411   | 10.34%  |
| Samsung Electronics            | 1751      | 2445   | 9.69%   |
| Toshiba                        | 1010      | 1192   | 5.59%   |
| Sandisk                        | 919       | 1247   | 5.09%   |
| Unknown                        | 547       | 751    | 3.03%   |
| A-DATA Technology              | 507       | 647    | 2.81%   |
| China                          | 459       | 553    | 2.54%   |
| Hitachi                        | 399       | 489    | 2.21%   |
| Crucial                        | 340       | 445    | 1.88%   |
| Intel                          | 318       | 393    | 1.76%   |
| ADATA Technology               | 215       | 253    | 1.19%   |
| Silicon Motion                 | 200       | 255    | 1.11%   |
| SK hynix                       | 158       | 216    | 0.87%   |
| HGST                           | 145       | 171    | 0.8%    |
| KingSpec                       | 133       | 151    | 0.74%   |
| LITEON                         | 132       | 154    | 0.73%   |
| Maxtor                         | 124       | 146    | 0.69%   |
| Lexar                          | 98        | 114    | 0.54%   |
| Realtek Semiconductor          | 89        | 113    | 0.49%   |
| JMicron Technology             | 77        | 86     | 0.43%   |
| Netac                          | 73        | 94     | 0.4%    |
| Phison                         | 70        | 92     | 0.39%   |
| Corsair                        | 64        | 76     | 0.35%   |
| XPG                            | 61        | 76     | 0.34%   |
| Fujitsu                        | 58        | 68     | 0.32%   |
| SSSTC                          | 57        | 59     | 0.32%   |
| PNY                            | 54        | 67     | 0.3%    |
| Patriot                        | 51        | 69     | 0.28%   |
| Apple                          | 51        | 71     | 0.28%   |
| Hewlett-Packard                | 50        | 60     | 0.28%   |
| Unknown                        | 50        | 56     | 0.28%   |
| XrayDisk                       | 49        | 66     | 0.27%   |
| Solid State Storage            | 44        | 52     | 0.24%   |
| Kingston Technology Company    | 43        | 47     | 0.24%   |
| Solid State Storage Technology | 39        | 53     | 0.22%   |
| Gigabyte Technology            | 38        | 52     | 0.21%   |
| KIOXIA                         | 37        | 45     | 0.2%    |
| Micron Technology              | 31        | 34     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 641       | 3.32%   |
| WDC WD10SPZX-21Z10T0 1TB            | 491       | 2.54%   |
| Kingston SA400S37480G 480GB SSD     | 326       | 1.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 321       | 1.66%   |
| Kingston SA400S37120G 120GB SSD     | 321       | 1.66%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 310       | 1.61%   |
| Seagate ST500DM002-1BD142 500GB     | 269       | 1.39%   |
| Seagate ST1000DM010-2EP102 1TB      | 235       | 1.22%   |
| Toshiba MQ01ABD100 1TB              | 160       | 0.83%   |
| Unknown MMC Card  32GB              | 154       | 0.8%    |
| Kingston SV300S37A120G 120GB SSD    | 154       | 0.8%    |
| SanDisk SSD PLUS 240GB              | 147       | 0.76%   |
| WDC WD10SPZX-24Z10 1TB              | 146       | 0.76%   |
| Seagate Expansion 2TB               | 132       | 0.68%   |
| Samsung HD322HJ 320GB               | 128       | 0.66%   |
| Seagate ST1000LM035-1RK172 1TB      | 127       | 0.66%   |
| WDC WD10JPVX-22JC3T0 1TB            | 117       | 0.61%   |
| Crucial CT240BX500SSD1 240GB        | 116       | 0.6%    |
| Samsung HD502HJ 500GB               | 113       | 0.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 109       | 0.56%   |
| Samsung HM321HI 320GB               | 109       | 0.56%   |
| Samsung HD161HJ 160GB               | 108       | 0.56%   |
| SanDisk SSD PLUS 120GB              | 104       | 0.54%   |
| Samsung HD502HI 500GB               | 103       | 0.53%   |
| Intel NVMe SSD Drive 512GB          | 103       | 0.53%   |
| Seagate ST1000DM003-1ER162 1TB      | 101       | 0.52%   |
| Seagate ST1000DM003-1CH162 1TB      | 99        | 0.51%   |
| Seagate ST9500325AS 500GB           | 96        | 0.5%    |
| A-DATA IM2S3338-128GD2 128GB SSD    | 93        | 0.48%   |
| WDC WD10SPZX-75Z10T2 1TB            | 86        | 0.45%   |
| Toshiba MQ04ABF100 1TB              | 86        | 0.45%   |
| Toshiba MQ01ABF050 500GB            | 84        | 0.44%   |
| SanDisk SDSSDA240G 240GB            | 82        | 0.42%   |
| WDC WD5000AAKX-003CA0 500GB         | 79        | 0.41%   |
| Seagate ST3500418AS 500GB           | 78        | 0.4%    |
| Seagate ST320LM001 HN-M320MBB 320GB | 74        | 0.38%   |
| WDC WD10JPVX-75JC3T0 1TB            | 73        | 0.38%   |
| SanDisk NVMe SSD Drive 512GB        | 73        | 0.38%   |
| Seagate ST3500312CS 500GB           | 72        | 0.37%   |
| SanDisk SSD PLUS 480GB              | 72        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3410      | 4824   | 35.55%  |
| WDC                 | 3196      | 4012   | 33.32%  |
| Samsung Electronics | 1190      | 1565   | 12.4%   |
| Toshiba             | 957       | 1125   | 9.98%   |
| Hitachi             | 399       | 489    | 4.16%   |
| HGST                | 145       | 171    | 1.51%   |
| Maxtor              | 115       | 135    | 1.2%    |
| Fujitsu             | 57        | 66     | 0.59%   |
| Unknown             | 34        | 39     | 0.35%   |
| Apple               | 20        | 32     | 0.21%   |
| Hewlett-Packard     | 18        | 22     | 0.19%   |
| ExcelStor           | 11        | 12     | 0.11%   |
| SAGE                | 8         | 13     | 0.08%   |
| JMicron Technology  | 5         | 6      | 0.05%   |
| HPE                 | 5         | 5      | 0.05%   |
| USB3.0              | 4         | 4      | 0.04%   |
| External            | 3         | 3      | 0.03%   |
| Initio              | 2         | 2      | 0.02%   |
| WALRAM              | 1         | 1      | 0.01%   |
| SABRENT             | 1         | 1      | 0.01%   |
| Phison              | 1         | 1      | 0.01%   |
| MDT                 | 1         | 1      | 0.01%   |
| Maxtor 6            | 1         | 1      | 0.01%   |
| Lenovo              | 1         | 1      | 0.01%   |
| Intenso             | 1         | 1      | 0.01%   |
| IBM/Hitachi         | 1         | 2      | 0.01%   |
| IBM                 | 1         | 3      | 0.01%   |
| HGST HTS            | 1         | 1      | 0.01%   |
| FEASSO              | 1         | 2      | 0.01%   |
| CLOVER              | 1         | 1      | 0.01%   |
| China               | 1         | 2      | 0.01%   |
| Unknown             | 1         | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 1776      | 2274   | 32.13%  |
| SanDisk             | 669       | 928    | 12.1%   |
| China               | 457       | 550    | 8.27%   |
| WDC                 | 400       | 509    | 7.24%   |
| Samsung Electronics | 351       | 552    | 6.35%   |
| Crucial             | 323       | 422    | 5.84%   |
| A-DATA Technology   | 284       | 345    | 5.14%   |
| KingSpec            | 127       | 145    | 2.3%    |
| LITEON              | 118       | 139    | 2.13%   |
| Lexar               | 95        | 111    | 1.72%   |
| JMicron Technology  | 64        | 72     | 1.16%   |
| Netac               | 54        | 70     | 0.98%   |
| Intel               | 54        | 67     | 0.98%   |
| PNY                 | 52        | 65     | 0.94%   |
| Corsair             | 51        | 60     | 0.92%   |
| Patriot             | 48        | 65     | 0.87%   |
| Gigabyte Technology | 31        | 44     | 0.56%   |
| Unknown             | 31        | 32     | 0.56%   |
| KingDian            | 30        | 38     | 0.54%   |
| Apple               | 28        | 34     | 0.51%   |
| Smart               | 27        | 31     | 0.49%   |
| XrayDisk            | 26        | 30     | 0.47%   |
| Hewlett-Packard     | 24        | 28     | 0.43%   |
| Unknown             | 22        | 24     | 0.4%    |
| SK hynix            | 22        | 26     | 0.4%    |
| Toshiba             | 21        | 28     | 0.38%   |
| Seagate             | 18        | 22     | 0.33%   |
| OCZ                 | 15        | 16     | 0.27%   |
| BHT                 | 14        | 19     | 0.25%   |
| LITEONIT            | 13        | 20     | 0.24%   |
| Team                | 12        | 29     | 0.22%   |
| WALRAM              | 11        | 11     | 0.2%    |
| Micron Technology   | 11        | 14     | 0.2%    |
| HUSKY               | 10        | 12     | 0.18%   |
| Win Memory          | 9         | 10     | 0.16%   |
| Maxtor              | 9         | 11     | 0.16%   |
| HS-SSD-C100         | 9         | 9      | 0.16%   |
| RZX                 | 7         | 14     | 0.13%   |
| Plextor             | 7         | 8      | 0.13%   |
| Pichau              | 7         | 7      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 8498      | 12544  | 51.96%  |
| SSD     | 4959      | 7120   | 30.32%  |
| NVMe    | 2292      | 3150   | 14.01%  |
| MMC     | 427       | 610    | 2.61%   |
| Unknown | 179       | 239    | 1.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 11244     | 19320  | 78.11%  |
| NVMe | 2291      | 3148   | 15.92%  |
| SAS  | 433       | 585    | 3.01%   |
| MMC  | 427       | 610    | 2.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 8546      | 12870  | 63.34%  |
| 0.51-1.0        | 4104      | 5499   | 30.42%  |
| 1.01-2.0        | 640       | 909    | 4.74%   |
| 3.01-4.0        | 87        | 210    | 0.64%   |
| 2.01-3.0        | 73        | 107    | 0.54%   |
| 4.01-10.0       | 36        | 60     | 0.27%   |
| 10.01-20.0      | 5         | 7      | 0.04%   |
| More than 100.0 | 1         | 1      | 0.01%   |
| 0               | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 3827      | 27.87%  |
| 251-500        | 3293      | 23.98%  |
| 501-1000       | 2228      | 16.22%  |
| 1-20           | 1089      | 7.93%   |
| 1001-2000      | 1011      | 7.36%   |
| 51-100         | 875       | 6.37%   |
| 21-50          | 622       | 4.53%   |
| 2001-3000      | 282       | 2.05%   |
| More than 3000 | 254       | 1.85%   |
| Unknown        | 253       | 1.84%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 5403      | 38.08%  |
| 21-50          | 3014      | 21.24%  |
| 101-250        | 1775      | 12.51%  |
| 51-100         | 1713      | 12.07%  |
| 251-500        | 951       | 6.7%    |
| 501-1000       | 656       | 4.62%   |
| 1001-2000      | 286       | 2.02%   |
| Unknown        | 253       | 1.78%   |
| 2001-3000      | 72        | 0.51%   |
| More than 3000 | 66        | 0.47%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 48        | 52     | 3.34%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 45        | 51     | 3.13%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 33        | 35     | 2.3%    |
| Samsung Electronics HD322HJ 320GB   | 26        | 36     | 1.81%   |
| WDC WD5000AAKX-003CA0 500GB         | 25        | 26     | 1.74%   |
| Seagate ST9500325AS 500GB           | 25        | 27     | 1.74%   |
| Samsung Electronics HD161HJ 160GB   | 24        | 25     | 1.67%   |
| Samsung Electronics HD502HI 500GB   | 20        | 24     | 1.39%   |
| Samsung Electronics HD502HJ 500GB   | 16        | 17     | 1.11%   |
| Seagate ST1000LM035-1RK172 1TB      | 15        | 16     | 1.04%   |
| Toshiba MQ01ABD100 1TB              | 14        | 14     | 0.97%   |
| Kingston SV300S37A120G 120GB SSD    | 14        | 15     | 0.97%   |
| Toshiba MQ01ABD050 500GB            | 13        | 13     | 0.9%    |
| Seagate ST500LT012-9WS142 500GB     | 13        | 15     | 0.9%    |
| WDC WD10EARS-00Y5B1 1TB             | 12        | 14     | 0.84%   |
| Seagate ST9320325AS 320GB           | 12        | 12     | 0.84%   |
| Seagate ST1000DM010-2EP102 1TB      | 12        | 15     | 0.84%   |
| Seagate ST3500418AS 500GB           | 11        | 16     | 0.77%   |
| Samsung Electronics HM321HI 320GB   | 11        | 11     | 0.77%   |
| WDC WD3200AAJS-00L7A0 320GB         | 10        | 10     | 0.7%    |
| Samsung Electronics HD080HJ 80GB    | 10        | 12     | 0.7%    |
| Maxtor STM3160215AS 160GB           | 10        | 12     | 0.7%    |
| Seagate ST3320418AS 320GB           | 9         | 13     | 0.63%   |
| Seagate ST31000524AS 1TB            | 9         | 9      | 0.63%   |
| Samsung Electronics HM160HI 160GB   | 9         | 9      | 0.63%   |
| Samsung Electronics HD250HJ 250GB   | 9         | 10     | 0.63%   |
| Samsung Electronics HD103SI 1TB     | 9         | 11     | 0.63%   |
| Kingston SA400S37480G 480GB SSD     | 9         | 10     | 0.63%   |
| Kingston SA400S37240G 240GB SSD     | 9         | 9      | 0.63%   |
| China SSD 120GB                     | 9         | 9      | 0.63%   |
| Seagate ST1000DM003-1CH162 1TB      | 8         | 11     | 0.56%   |
| Samsung Electronics HD103SJ 1TB     | 8         | 10     | 0.56%   |
| Kingston SA400S37120G 120GB SSD     | 8         | 15     | 0.56%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 7         | 8      | 0.49%   |
| Toshiba MQ02ABD100H 1TB             | 7         | 10     | 0.49%   |
| Toshiba MQ01ABF050 500GB            | 7         | 7      | 0.49%   |
| Toshiba MQ01ABD032 320GB            | 7         | 8      | 0.49%   |
| Seagate ST500LT012-1DG142 500GB     | 7         | 8      | 0.49%   |
| Seagate ST3500413AS 500GB           | 7         | 8      | 0.49%   |
| Seagate ST3500312CS 500GB           | 7         | 7      | 0.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 442       | 528    | 32.12%  |
| WDC                   | 306       | 350    | 22.24%  |
| Samsung Electronics   | 211       | 263    | 15.33%  |
| Toshiba               | 111       | 121    | 8.07%   |
| Hitachi               | 69        | 73     | 5.01%   |
| Kingston              | 51        | 62     | 3.71%   |
| China                 | 32        | 35     | 2.33%   |
| Maxtor                | 22        | 25     | 1.6%    |
| SanDisk               | 21        | 23     | 1.53%   |
| HGST                  | 13        | 13     | 0.94%   |
| A-DATA Technology     | 12        | 14     | 0.87%   |
| XPG                   | 7         | 7      | 0.51%   |
| Intel                 | 6         | 6      | 0.44%   |
| Netac                 | 5         | 6      | 0.36%   |
| LITEON                | 5         | 5      | 0.36%   |
| Fujitsu               | 5         | 6      | 0.36%   |
| Crucial               | 5         | 5      | 0.36%   |
| PNY                   | 4         | 6      | 0.29%   |
| KingSpec              | 4         | 4      | 0.29%   |
| Unknown               | 4         | 4      | 0.29%   |
| OCZ                   | 3         | 3      | 0.22%   |
| JMicron Technology    | 3         | 3      | 0.22%   |
| Hewlett-Packard       | 3         | 4      | 0.22%   |
| Apple                 | 3         | 3      | 0.22%   |
| XrayDisk              | 2         | 3      | 0.15%   |
| walram                | 2         | 2      | 0.15%   |
| ExcelStor             | 2         | 3      | 0.15%   |
| Corsair               | 2         | 2      | 0.15%   |
| Team                  | 1         | 1      | 0.07%   |
| SSSTC                 | 1         | 1      | 0.07%   |
| SK hynix              | 1         | 1      | 0.07%   |
| Silicon Motion        | 1         | 1      | 0.07%   |
| ShiJi                 | 1         | 4      | 0.07%   |
| SAGE                  | 1         | 1      | 0.07%   |
| Reeinno               | 1         | 1      | 0.07%   |
| Realtek Semiconductor | 1         | 2      | 0.07%   |
| QIANGHE               | 1         | 1      | 0.07%   |
| Plextor               | 1         | 1      | 0.07%   |
| OCZ-VERTEX3           | 1         | 1      | 0.07%   |
| Mushkin               | 1         | 1      | 0.07%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 442       | 528    | 37.94%  |
| WDC                 | 289       | 331    | 24.81%  |
| Samsung Electronics | 205       | 257    | 17.6%   |
| Toshiba             | 110       | 120    | 9.44%   |
| Hitachi             | 69        | 73     | 5.92%   |
| Maxtor              | 22        | 25     | 1.89%   |
| HGST                | 13        | 13     | 1.12%   |
| Fujitsu             | 5         | 6      | 0.43%   |
| Hewlett-Packard     | 3         | 4      | 0.26%   |
| ExcelStor           | 2         | 3      | 0.17%   |
| Apple               | 2         | 2      | 0.17%   |
| SAGE                | 1         | 1      | 0.09%   |
| Initio              | 1         | 1      | 0.09%   |
| FEASSO              | 1         | 2      | 0.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1067      | 1366   | 83.56%  |
| SSD  | 182       | 206    | 14.25%  |
| NVMe | 28        | 34     | 2.19%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 4         | 4      | 11.11%  |
| Samsung Electronics HD502HJ 500GB                | 3         | 7      | 8.33%   |
| Samsung Electronics HM321HI 320GB                | 2         | 2      | 5.56%   |
| Samsung Electronics HM250HI 250GB                | 2         | 2      | 5.56%   |
| WDC WD5000AAKS-00C8A0 500GB                      | 1         | 1      | 2.78%   |
| WDC WD3200BPVT-22JJ5T0 320GB                     | 1         | 1      | 2.78%   |
| WDC WD3200BPVT-00JJ5T0 320GB                     | 1         | 1      | 2.78%   |
| WDC WD1600BEVT-22ZCT0 160GB                      | 1         | 1      | 2.78%   |
| WDC WD10SPZX-75Z10T1 1TB                         | 1         | 1      | 2.78%   |
| WDC WD10SPZX-22Z10T0 1TB                         | 1         | 1      | 2.78%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 2.78%   |
| Toshiba MK5065GSXN 500GB                         | 1         | 1      | 2.78%   |
| Toshiba DT01ACA100 1TB                           | 1         | 1      | 2.78%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 2.78%   |
| Seagate ST3320613AS 320GB                        | 1         | 1      | 2.78%   |
| Seagate ST3250318AS 250GB                        | 1         | 1      | 2.78%   |
| Seagate ST31000528AS 1TB                         | 1         | 1      | 2.78%   |
| Seagate ST31000340NS 1TB                         | 1         | 1      | 2.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 2.78%   |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 2.78%   |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD  | 1         | 1      | 2.78%   |
| Samsung Electronics HM641JI 640GB                | 1         | 1      | 2.78%   |
| Samsung Electronics HM320JI 320GB                | 1         | 1      | 2.78%   |
| Samsung Electronics HD322GJ 320GB                | 1         | 1      | 2.78%   |
| Samsung Electronics HD103SJ 1TB                  | 1         | 1      | 2.78%   |
| Samsung Electronics HD080HJ 80GB                 | 1         | 1      | 2.78%   |
| Maxtor STM380215AS 80GB                          | 1         | 1      | 2.78%   |
| Hitachi HTS545032B9A300 320GB                    | 1         | 1      | 2.78%   |
| Hitachi HDS721050DLE630 500GB                    | 1         | 1      | 2.78%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 18     | 38.89%  |
| Seagate             | 10        | 10     | 27.78%  |
| WDC                 | 6         | 6      | 16.67%  |
| Toshiba             | 3         | 3      | 8.33%   |
| Hitachi             | 2         | 2      | 5.56%   |
| Maxtor              | 1         | 1      | 2.78%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 9092      | 16268  | 65.64%  |
| Works    | 3491      | 5748   | 25.2%   |
| Malfunc  | 1231      | 1606   | 8.89%   |
| Failed   | 36        | 40     | 0.26%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 9800      | 65.85%  |
| AMD                              | 2134      | 14.34%  |
| ADATA Technology                 | 466       | 3.13%   |
| SanDisk                          | 321       | 2.16%   |
| Nvidia                           | 269       | 1.81%   |
| Samsung Electronics              | 263       | 1.77%   |
| Silicon Motion                   | 225       | 1.51%   |
| Solid State Storage Technology   | 148       | 0.99%   |
| Kingston Technology Company      | 146       | 0.98%   |
| SK hynix                         | 129       | 0.87%   |
| Realtek Semiconductor            | 124       | 0.83%   |
| Phison Electronics               | 115       | 0.77%   |
| Silicon Integrated Systems [SiS] | 107       | 0.72%   |
| Marvell Technology Group         | 94        | 0.63%   |
| JMicron Technology               | 87        | 0.58%   |
| ASMedia Technology               | 79        | 0.53%   |
| VIA Technologies                 | 74        | 0.5%    |
| Micron/Crucial Technology        | 47        | 0.32%   |
| KIOXIA                           | 36        | 0.24%   |
| MAXIO Technology (Hangzhou)      | 31        | 0.21%   |
| Toshiba America Info Systems     | 26        | 0.17%   |
| LSI Logic / Symbios Logic        | 26        | 0.17%   |
| Lite-On Technology               | 26        | 0.17%   |
| Micron Technology                | 20        | 0.13%   |
| Broadcom / LSI                   | 14        | 0.09%   |
| Netac Technology                 | 12        | 0.08%   |
| Union Memory (Shenzhen)          | 9         | 0.06%   |
| Silicon Image                    | 6         | 0.04%   |
| Shenzhen Longsys Electronics     | 6         | 0.04%   |
| Beijing Starblaze Technology     | 6         | 0.04%   |
| Seagate Technology               | 5         | 0.03%   |
| OCZ Technology Group             | 4         | 0.03%   |
| Dell                             | 4         | 0.03%   |
| Apple                            | 4         | 0.03%   |
| Adaptec                          | 4         | 0.03%   |
| INNOGRIT                         | 3         | 0.02%   |
| Hewlett-Packard                  | 3         | 0.02%   |
| TenaFe                           | 2         | 0.01%   |
| Lenovo                           | 2         | 0.01%   |
| ULi Electronics                  | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1298      | 7.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1079      | 5.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 903       | 4.98%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 664       | 3.66%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 620       | 3.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 517       | 2.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 484       | 2.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 444       | 2.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 425       | 2.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 409       | 2.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 349       | 1.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 337       | 1.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 331       | 1.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 324       | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 268       | 1.48%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 258       | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 258       | 1.42%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 253       | 1.4%    |
| AMD FCH SATA Controller D                                                               | 253       | 1.4%    |
| AMD 400 Series Chipset SATA Controller                                                  | 246       | 1.36%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 225       | 1.24%   |
| Intel PROSet/Wireless WiFi Software extension                                           | 207       | 1.14%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 202       | 1.11%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 193       | 1.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 190       | 1.05%   |
| Nvidia MCP61 SATA Controller                                                            | 186       | 1.03%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 171       | 0.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 170       | 0.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 169       | 0.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 160       | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 158       | 0.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 158       | 0.87%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 155       | 0.85%   |
| ADATA IM2P33F3 NVMe SSD (DRAM-less)                                                     | 155       | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 154       | 0.85%   |
| Nvidia MCP61 IDE                                                                        | 152       | 0.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 152       | 0.84%   |
| ADATA IM2P33F8ABR1 NVMe SSD                                                             | 148       | 0.82%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 140       | 0.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 139       | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 9837      | 62.99%  |
| IDE  | 2517      | 16.12%  |
| NVMe | 2304      | 14.75%  |
| RAID | 932       | 5.97%   |
| SCSI | 17        | 0.11%   |
| SAS  | 9         | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 10479     | 80.98%  |
| AMD          | 2420      | 18.7%   |
| ARM          | 33        | 0.26%   |
| CentaurHauls | 5         | 0.04%   |
| Qualcomm     | 2         | 0.02%   |
| Unknown      | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 279       | 2.15%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 166       | 1.28%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 153       | 1.18%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 150       | 1.16%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 148       | 1.14%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 137       | 1.06%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 136       | 1.05%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 135       | 1.04%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 133       | 1.02%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 124       | 0.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 116       | 0.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 106       | 0.82%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 103       | 0.79%   |
| AMD FX-6300 Six-Core Processor                | 101       | 0.78%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 98        | 0.76%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 97        | 0.75%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 97        | 0.75%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 95        | 0.73%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 94        | 0.72%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 92        | 0.71%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 92        | 0.71%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 90        | 0.69%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 88        | 0.68%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 88        | 0.68%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 87        | 0.67%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 86        | 0.66%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 85        | 0.65%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 83        | 0.64%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 82        | 0.63%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 80        | 0.62%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 76        | 0.59%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 75        | 0.58%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 73        | 0.56%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 72        | 0.55%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 71        | 0.55%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 70        | 0.54%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 68        | 0.52%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 67        | 0.52%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 67        | 0.52%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 67        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 3124      | 24.08%  |
| Intel Core i7           | 2025      | 15.61%  |
| Intel Core i3           | 1784      | 13.75%  |
| Intel Celeron           | 881       | 6.79%   |
| AMD Ryzen 5             | 614       | 4.73%   |
| Intel Core 2 Duo        | 552       | 4.26%   |
| Other                   | 442       | 3.41%   |
| AMD Ryzen 7             | 360       | 2.78%   |
| Intel Pentium Dual-Core | 336       | 2.59%   |
| Intel Atom              | 328       | 2.53%   |
| Intel Pentium           | 301       | 2.32%   |
| AMD FX                  | 279       | 2.15%   |
| Intel Xeon              | 276       | 2.13%   |
| Intel Pentium Dual      | 151       | 1.16%   |
| AMD Ryzen 3             | 119       | 0.92%   |
| Intel Core 2 Quad       | 107       | 0.82%   |
| AMD Phenom II X4        | 86        | 0.66%   |
| AMD Athlon II X2        | 77        | 0.59%   |
| AMD A4                  | 71        | 0.55%   |
| AMD E                   | 64        | 0.49%   |
| AMD A10                 | 62        | 0.48%   |
| Intel Core 2            | 59        | 0.45%   |
| AMD A6                  | 55        | 0.42%   |
| AMD Athlon              | 53        | 0.41%   |
| AMD Ryzen 9             | 50        | 0.39%   |
| AMD Athlon 64 X2        | 50        | 0.39%   |
| AMD A8                  | 50        | 0.39%   |
| AMD C-60                | 44        | 0.34%   |
| Intel Genuine           | 42        | 0.32%   |
| AMD E1                  | 37        | 0.29%   |
| AMD Sempron             | 32        | 0.25%   |
| AMD Phenom II X6        | 32        | 0.25%   |
| Intel Pentium 4         | 29        | 0.22%   |
| AMD C-70                | 27        | 0.21%   |
| Intel Pentium Gold      | 24        | 0.19%   |
| Intel Core i9           | 23        | 0.18%   |
| AMD Phenom II X2        | 20        | 0.15%   |
| AMD C-50                | 20        | 0.15%   |
| AMD Athlon II X4        | 18        | 0.14%   |
| Intel Celeron Dual-Core | 17        | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 6785      | 52.32%  |
| 4       | 4116      | 31.74%  |
| 6       | 913       | 7.04%   |
| 8       | 440       | 3.39%   |
| 1       | 358       | 2.76%   |
| 3       | 150       | 1.16%   |
| 12      | 78        | 0.6%    |
| 10      | 42        | 0.32%   |
| 14      | 27        | 0.21%   |
| 16      | 22        | 0.17%   |
| Unknown | 18        | 0.14%   |
| 24      | 6         | 0.05%   |
| 20      | 6         | 0.05%   |
| 28      | 2         | 0.02%   |
| 18      | 2         | 0.02%   |
| 5       | 2         | 0.02%   |
| 32      | 1         | 0.01%   |
| 22      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 12886     | 99.57%  |
| 2       | 48        | 0.37%   |
| Unknown | 5         | 0.04%   |
| 16      | 1         | 0.01%   |
| 4       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 8420      | 64.97%  |
| 1       | 4518      | 34.86%  |
| Unknown | 18        | 0.14%   |
| 4       | 2         | 0.02%   |
| 8       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 12351     | 94.94%  |
| Unknown        | 545       | 4.19%   |
| 32-bit         | 62        | 0.48%   |
| 64-bit         | 51        | 0.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3098      | 23%     |
| 0x306a9    | 1035      | 7.69%   |
| 0x206a7    | 1018      | 7.56%   |
| 0x1067a    | 666       | 4.95%   |
| 0x806e9    | 425       | 3.16%   |
| 0x906ea    | 421       | 3.13%   |
| 0x306c3    | 383       | 2.84%   |
| 0x20655    | 382       | 2.84%   |
| 0x40651    | 353       | 2.62%   |
| 0x806ec    | 335       | 2.49%   |
| 0x306d4    | 292       | 2.17%   |
| 0x406e3    | 282       | 2.09%   |
| 0x806ea    | 258       | 1.92%   |
| 0x6fd      | 255       | 1.89%   |
| 0x906e9    | 220       | 1.63%   |
| 0x806c1    | 204       | 1.51%   |
| 0x406c4    | 192       | 1.43%   |
| 0x08108109 | 182       | 1.35%   |
| 0x06000852 | 157       | 1.17%   |
| 0x010000c8 | 137       | 1.02%   |
| 0x30678    | 131       | 0.97%   |
| 0x20652    | 99        | 0.74%   |
| 0x05000119 | 99        | 0.74%   |
| 0x08600103 | 89        | 0.66%   |
| 0x0800820d | 88        | 0.65%   |
| 0x906ed    | 87        | 0.65%   |
| 0x706e5    | 85        | 0.63%   |
| 0x08108102 | 85        | 0.63%   |
| 0x10676    | 83        | 0.62%   |
| 0x706a1    | 78        | 0.58%   |
| 0x506e3    | 78        | 0.58%   |
| 0x08701021 | 77        | 0.57%   |
| 0x6fb      | 67        | 0.5%    |
| 0x106ca    | 64        | 0.48%   |
| 0x406c3    | 62        | 0.46%   |
| 0x706a8    | 60        | 0.45%   |
| 0x306f2    | 60        | 0.45%   |
| 0x806eb    | 58        | 0.43%   |
| 0x0600611a | 56        | 0.42%   |
| 0x08701013 | 55        | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 2325      | 17.95%  |
| IvyBridge        | 1333      | 10.29%  |
| SandyBridge      | 1263      | 9.75%   |
| Haswell          | 988       | 7.63%   |
| Penryn           | 889       | 6.86%   |
| Westmere         | 602       | 4.65%   |
| Core             | 501       | 3.87%   |
| Silvermont       | 496       | 3.83%   |
| Skylake          | 471       | 3.64%   |
| Zen+             | 451       | 3.48%   |
| Broadwell        | 370       | 2.86%   |
| K10              | 320       | 2.47%   |
| Piledriver       | 301       | 2.32%   |
| Zen 2            | 291       | 2.25%   |
| TigerLake        | 280       | 2.16%   |
| Zen              | 243       | 1.88%   |
| CometLake        | 192       | 1.48%   |
| Unknown          | 191       | 1.47%   |
| Bobcat           | 182       | 1.4%    |
| Goldmont plus    | 171       | 1.32%   |
| IceLake          | 148       | 1.14%   |
| Zen 3            | 141       | 1.09%   |
| Bonnell          | 134       | 1.03%   |
| K8 Hammer        | 112       | 0.86%   |
| Excavator        | 91        | 0.7%    |
| Nehalem          | 83        | 0.64%   |
| NetBurst         | 51        | 0.39%   |
| Goldmont         | 51        | 0.39%   |
| Alderlake Hybrid | 51        | 0.39%   |
| K10 Llano        | 49        | 0.38%   |
| Bulldozer        | 47        | 0.36%   |
| Steamroller      | 45        | 0.35%   |
| Jaguar           | 41        | 0.32%   |
| P6               | 26        | 0.2%    |
| K8 & K10 hybrid  | 11        | 0.08%   |
| Puma             | 7         | 0.05%   |
| Tremont          | 6         | 0.05%   |
| K6               | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 8695      | 56.3%   |
| Nvidia                           | 3777      | 24.46%  |
| AMD                              | 2765      | 17.9%   |
| Silicon Integrated Systems [SiS] | 104       | 0.67%   |
| VIA Technologies                 | 56        | 0.36%   |
| Matrox Electronics Systems       | 28        | 0.18%   |
| ASPEED Technology                | 9         | 0.06%   |
| Silicon Motion                   | 4         | 0.03%   |
| ATI Technologies                 | 4         | 0.03%   |
| S3 Graphics                      | 1         | 0.01%   |
| Red Hat                          | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1047      | 6.62%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 780       | 4.93%   |
| Intel HD Graphics 620                                                                    | 560       | 3.54%   |
| Intel Core Processor Integrated Graphics Controller                                      | 516       | 3.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 427       | 2.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 391       | 2.47%   |
| Intel HD Graphics 5500                                                                   | 328       | 2.07%   |
| Intel UHD Graphics 620                                                                   | 311       | 1.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 310       | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 308       | 1.95%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 304       | 1.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 299       | 1.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 294       | 1.86%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 269       | 1.7%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 266       | 1.68%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 236       | 1.49%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 204       | 1.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 188       | 1.19%   |
| Intel HD Graphics 630                                                                    | 188       | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 188       | 1.19%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 179       | 1.13%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 178       | 1.13%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 172       | 1.09%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 171       | 1.08%   |
| Nvidia GT218 [GeForce 210]                                                               | 153       | 0.97%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 148       | 0.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 142       | 0.9%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 142       | 0.9%    |
| AMD Renoir                                                                               | 115       | 0.73%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 113       | 0.71%   |
| Nvidia TU117M                                                                            | 107       | 0.68%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 105       | 0.66%   |
| Nvidia GP108M [GeForce MX150]                                                            | 103       | 0.65%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 101       | 0.64%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 99        | 0.63%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 98        | 0.62%   |
| Nvidia GM108M [GeForce MX110]                                                            | 96        | 0.61%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 95        | 0.6%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 94        | 0.59%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 94        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 6411      | 49.23%  |
| 1 x AMD                 | 2036      | 15.63%  |
| 1 x Nvidia              | 1808      | 13.88%  |
| Intel + Nvidia          | 1751      | 13.45%  |
| Intel + AMD             | 432       | 3.32%   |
| AMD + Nvidia            | 184       | 1.41%   |
| 2 x AMD                 | 118       | 0.91%   |
| 1 x SiS                 | 104       | 0.8%    |
| 1 x VIA                 | 55        | 0.42%   |
| Other                   | 38        | 0.29%   |
| 1 x Matrox              | 27        | 0.21%   |
| 2 x Intel               | 23        | 0.18%   |
| 2 x Nvidia              | 18        | 0.14%   |
| 1 x ASPEED              | 8         | 0.06%   |
| Intel + Silicon Motion  | 2         | 0.02%   |
| 1 x Silicon Motion      | 1         | 0.01%   |
| 1 x S3 Graphics         | 1         | 0.01%   |
| 1 x Red Hat             | 1         | 0.01%   |
| Nvidia + Silicon Motion | 1         | 0.01%   |
| Nvidia + ASPEED         | 1         | 0.01%   |
| Intel + 2 x AMD         | 1         | 0.01%   |
| AMD + 2 x Nvidia        | 1         | 0.01%   |
| AMD + Matrox            | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 10410     | 79.45%  |
| Proprietary | 2185      | 16.68%  |
| Unknown     | 508       | 3.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 8126      | 61.22%  |
| 1.01-2.0   | 1843      | 13.88%  |
| 0.01-0.5   | 1117      | 8.41%   |
| 0.51-1.0   | 855       | 6.44%   |
| 3.01-4.0   | 819       | 6.17%   |
| 7.01-8.0   | 219       | 1.65%   |
| 5.01-6.0   | 198       | 1.49%   |
| 2.01-3.0   | 67        | 0.5%    |
| 8.01-16.0  | 26        | 0.2%    |
| 4.01-5.0   | 2         | 0.02%   |
| 16.01-24.0 | 2         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 2008      | 14.41%  |
| Goldstar                | 1826      | 13.1%   |
| BOE                     | 1674      | 12.01%  |
| AU Optronics            | 1624      | 11.65%  |
| Chimei Innolux          | 1314      | 9.43%   |
| LG Display              | 1196      | 8.58%   |
| AOC                     | 928       | 6.66%   |
| Dell                    | 579       | 4.15%   |
| Philips                 | 374       | 2.68%   |
| Acer                    | 221       | 1.59%   |
| Chi Mei Optoelectronics | 164       | 1.18%   |
| LG Electronics          | 159       | 1.14%   |
| Hewlett-Packard         | 147       | 1.05%   |
| InfoVision              | 133       | 0.95%   |
| PANDA                   | 127       | 0.91%   |
| Apple                   | 124       | 0.89%   |
| Lenovo                  | 113       | 0.81%   |
| Sony                    | 93        | 0.67%   |
| BenQ                    | 70        | 0.5%    |
| Unknown                 | 65        | 0.47%   |
| RTK                     | 49        | 0.35%   |
| HannStar                | 49        | 0.35%   |
| CPT                     | 49        | 0.35%   |
| Positivo                | 47        | 0.34%   |
| LG Philips              | 43        | 0.31%   |
| Panasonic               | 37        | 0.27%   |
| ASUSTek Computer        | 35        | 0.25%   |
| SLD                     | 33        | 0.24%   |
| InnoLux Display         | 32        | 0.23%   |
| GDH                     | 29        | 0.21%   |
| Ancor Communications    | 27        | 0.19%   |
| Sharp                   | 26        | 0.19%   |
| Unknown (XXX)           | 24        | 0.17%   |
| NCS                     | 21        | 0.15%   |
| VIE                     | 20        | 0.14%   |
| MTD                     | 20        | 0.14%   |
| Toshiba                 | 19        | 0.14%   |
| STA                     | 18        | 0.13%   |
| HB@                     | 17        | 0.12%   |
| SKY                     | 16        | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 184       | 1.28%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 127       | 0.89%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 122       | 0.85%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 120       | 0.84%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 116       | 0.81%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 112       | 0.78%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 107       | 0.75%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 102       | 0.71%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 102       | 0.71%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 100       | 0.7%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 92        | 0.64%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 78        | 0.54%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 78        | 0.54%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 77        | 0.54%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 77        | 0.54%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 76        | 0.53%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 74        | 0.52%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 72        | 0.5%    |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 67        | 0.47%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 67        | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 67        | 0.47%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                | 65        | 0.45%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 60        | 0.42%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch        | 60        | 0.42%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 59        | 0.41%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 798x334mm 34.1-inch             | 58        | 0.4%    |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 57        | 0.4%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 56        | 0.39%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 56        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 56        | 0.39%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 54        | 0.38%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 50        | 0.35%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 50        | 0.35%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                         | 50        | 0.35%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 47        | 0.33%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 47        | 0.33%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 46        | 0.32%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 46        | 0.32%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 44        | 0.31%   |
| Goldstar 2D HD LG TV GSM59CA 1366x768 510x290mm 23.1-inch            | 43        | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 5371      | 39.59%  |
| 1920x1080 (FHD)    | 4307      | 31.75%  |
| 1600x900 (HD+)     | 566       | 4.17%   |
| 1440x900 (WXGA+)   | 445       | 3.28%   |
| 2560x1080          | 439       | 3.24%   |
| 1360x768           | 371       | 2.73%   |
| 1280x1024 (SXGA)   | 359       | 2.65%   |
| 3840x2160 (4K)     | 343       | 2.53%   |
| 1280x800 (WXGA)    | 328       | 2.42%   |
| 1680x1050 (WSXGA+) | 205       | 1.51%   |
| 2560x1440 (QHD)    | 143       | 1.05%   |
| 1024x768 (XGA)     | 124       | 0.91%   |
| Unknown            | 109       | 0.8%    |
| 1920x1200 (WUXGA)  | 73        | 0.54%   |
| 1280x720 (HD)      | 53        | 0.39%   |
| 1920x540           | 43        | 0.32%   |
| 1024x600           | 43        | 0.32%   |
| 3840x1080          | 30        | 0.22%   |
| 2288x1287          | 25        | 0.18%   |
| 3440x1440          | 21        | 0.15%   |
| 2560x1600          | 21        | 0.15%   |
| 1152x864           | 9         | 0.07%   |
| 800x1280           | 8         | 0.06%   |
| 1600x1200          | 7         | 0.05%   |
| 5760x1080          | 6         | 0.04%   |
| 4480x1080          | 6         | 0.04%   |
| 3840x2400          | 6         | 0.04%   |
| 2880x1800          | 6         | 0.04%   |
| 2736x1824          | 6         | 0.04%   |
| 3360x1080          | 5         | 0.04%   |
| 3286x1080          | 5         | 0.04%   |
| 3200x1080          | 5         | 0.04%   |
| 1280x960           | 5         | 0.04%   |
| 3200x1800 (QHD+)   | 4         | 0.03%   |
| 3600x1080          | 3         | 0.02%   |
| 3520x1080          | 3         | 0.02%   |
| 2732x768           | 3         | 0.02%   |
| 6400x1080          | 2         | 0.01%   |
| 3360x1050          | 2         | 0.01%   |
| 2800x900           | 2         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 4060      | 29.02%  |
| 14      | 1676      | 11.98%  |
| 13      | 1458      | 10.42%  |
| 18      | 929       | 6.64%   |
| 21      | 896       | 6.4%    |
| 23      | 835       | 5.97%   |
| 17      | 560       | 4%      |
| Unknown | 534       | 3.82%   |
| 24      | 430       | 3.07%   |
| 34      | 380       | 2.72%   |
| 20      | 350       | 2.5%    |
| 19      | 334       | 2.39%   |
| 27      | 330       | 2.36%   |
| 31      | 154       | 1.1%    |
| 11      | 130       | 0.93%   |
| 22      | 127       | 0.91%   |
| 12      | 84        | 0.6%    |
| 40      | 71        | 0.51%   |
| 54      | 70        | 0.5%    |
| 72      | 68        | 0.49%   |
| 28      | 66        | 0.47%   |
| 32      | 62        | 0.44%   |
| 84      | 56        | 0.4%    |
| 10      | 49        | 0.35%   |
| 16      | 45        | 0.32%   |
| 26      | 43        | 0.31%   |
| 52      | 42        | 0.3%    |
| 46      | 35        | 0.25%   |
| 37      | 15        | 0.11%   |
| 142     | 13        | 0.09%   |
| 48      | 11        | 0.08%   |
| 25      | 10        | 0.07%   |
| 7       | 8         | 0.06%   |
| 58      | 7         | 0.05%   |
| 65      | 6         | 0.04%   |
| 47      | 5         | 0.04%   |
| 43      | 5         | 0.04%   |
| 39      | 5         | 0.04%   |
| 55      | 4         | 0.03%   |
| 41      | 4         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 7077      | 51.32%  |
| 401-500        | 2498      | 18.12%  |
| 501-600        | 1529      | 11.09%  |
| Unknown        | 534       | 3.87%   |
| 201-300        | 514       | 3.73%   |
| 351-400        | 487       | 3.53%   |
| 701-800        | 444       | 3.22%   |
| 601-700        | 263       | 1.91%   |
| 1001-1500      | 188       | 1.36%   |
| 1501-2000      | 125       | 0.91%   |
| 801-900        | 98        | 0.71%   |
| More than 2000 | 13        | 0.09%   |
| 901-1000       | 11        | 0.08%   |
| 1-100          | 8         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 10066     | 79.87%  |
| 16/10   | 1020      | 8.09%   |
| Unknown | 451       | 3.58%   |
| 21/9    | 430       | 3.41%   |
| 5/4     | 356       | 2.82%   |
| 4/3     | 185       | 1.47%   |
| 3/2     | 63        | 0.5%    |
| 1.00    | 15        | 0.12%   |
| 0.67    | 8         | 0.06%   |
| 32/9    | 4         | 0.03%   |
| 2.00    | 2         | 0.02%   |
| 6/5     | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |
| 0.31    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 4020      | 28.89%  |
| 81-90          | 2939      | 21.12%  |
| 201-250        | 1936      | 13.91%  |
| 141-150        | 1118      | 8.04%   |
| 151-200        | 981       | 7.05%   |
| 351-500        | 620       | 4.46%   |
| Unknown        | 534       | 3.84%   |
| 301-350        | 344       | 2.47%   |
| More than 1000 | 284       | 2.04%   |
| 71-80          | 196       | 1.41%   |
| 251-300        | 168       | 1.21%   |
| 121-130        | 156       | 1.12%   |
| 501-1000       | 150       | 1.08%   |
| 131-140        | 134       | 0.96%   |
| 51-60          | 130       | 0.93%   |
| 91-100         | 54        | 0.39%   |
| 41-50          | 49        | 0.35%   |
| 61-70          | 48        | 0.34%   |
| 111-120        | 45        | 0.32%   |
| 1-40           | 8         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 5628      | 41.64%  |
| 51-100        | 4474      | 33.1%   |
| 121-160       | 2262      | 16.74%  |
| Unknown       | 535       | 3.96%   |
| 1-50          | 384       | 2.84%   |
| 161-240       | 203       | 1.5%    |
| More than 240 | 30        | 0.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 10492     | 79.28%  |
| 2     | 2102      | 15.88%  |
| 0     | 527       | 3.98%   |
| 3     | 107       | 0.81%   |
| 4     | 6         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 9245      | 45.11%  |
| Qualcomm Atheros                  | 3913      | 19.09%  |
| Intel                             | 3543      | 17.29%  |
| Broadcom                          | 951       | 4.64%   |
| Ralink Technology                 | 444       | 2.17%   |
| Marvell Technology Group          | 245       | 1.2%    |
| Ralink                            | 238       | 1.16%   |
| JMicron Technology                | 235       | 1.15%   |
| Nvidia                            | 222       | 1.08%   |
| TP-Link                           | 203       | 0.99%   |
| Broadcom Limited                  | 201       | 0.98%   |
| Qualcomm Atheros Communications   | 141       | 0.69%   |
| Samsung Electronics               | 123       | 0.6%    |
| Silicon Integrated Systems [SiS]  | 105       | 0.51%   |
| D-Link                            | 78        | 0.38%   |
| VIA Technologies                  | 72        | 0.35%   |
| MediaTek                          | 62        | 0.3%    |
| Xiaomi                            | 57        | 0.28%   |
| Microsoft                         | 52        | 0.25%   |
| Motorola PCS                      | 49        | 0.24%   |
| ASIX Electronics                  | 44        | 0.21%   |
| D-Link System                     | 42        | 0.2%    |
| ICS Advent                        | 19        | 0.09%   |
| Motorola                          | 14        | 0.07%   |
| DisplayLink                       | 14        | 0.07%   |
| Huawei Technologies               | 12        | 0.06%   |
| Dell                              | 10        | 0.05%   |
| Edimax Technology                 | 9         | 0.04%   |
| LG Electronics                    | 8         | 0.04%   |
| Qualcomm                          | 7         | 0.03%   |
| Microchip Technology              | 7         | 0.03%   |
| ASUSTek Computer                  | 7         | 0.03%   |
| Mercucys                          | 6         | 0.03%   |
| Lenovo                            | 5         | 0.02%   |
| Arduino SA                        | 5         | 0.02%   |
| Accton Technology                 | 5         | 0.02%   |
| 3Com                              | 5         | 0.02%   |
| Sundance Technology Inc / IC Plus | 4         | 0.02%   |
| STMicroelectronics                | 4         | 0.02%   |
| OPPO Electronics                  | 4         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6061      | 27.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1966      | 8.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 912       | 4.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 805       | 3.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 693       | 3.09%   |
| Intel Wi-Fi 6 AX200                                               | 394       | 1.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 342       | 1.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 337       | 1.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 328       | 1.46%   |
| Intel Wi-Fi 6 AX201                                               | 258       | 1.15%   |
| Ralink MT7601U Wireless Adapter                                   | 253       | 1.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 227       | 1.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 193       | 0.86%   |
| Intel Wireless 7265                                               | 192       | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 179       | 0.8%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 167       | 0.74%   |
| Nvidia MCP61 Ethernet                                             | 164       | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 161       | 0.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 144       | 0.64%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 132       | 0.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 131       | 0.58%   |
| Qualcomm Atheros AR9271 802.11n                                   | 126       | 0.56%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 122       | 0.54%   |
| Intel Wireless 7260                                               | 122       | 0.54%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 119       | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 116       | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 116       | 0.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 114       | 0.51%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 113       | 0.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 110       | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 107       | 0.48%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 107       | 0.48%   |
| Intel Wireless 3165                                               | 105       | 0.47%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 98        | 0.44%   |
| Intel Ethernet Connection (2) I219-V                              | 98        | 0.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 96        | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 92        | 0.41%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 91        | 0.41%   |
| Ralink RT5370 Wireless Adapter                                    | 90        | 0.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 90        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Qualcomm Atheros                      | 3421      | 34.67%  |
| Intel                                 | 2743      | 27.8%   |
| Realtek Semiconductor                 | 1730      | 17.53%  |
| Broadcom                              | 580       | 5.88%   |
| Ralink Technology                     | 444       | 4.5%    |
| Ralink                                | 238       | 2.41%   |
| TP-Link                               | 183       | 1.85%   |
| Qualcomm Atheros Communications       | 141       | 1.43%   |
| Broadcom Limited                      | 113       | 1.15%   |
| D-Link                                | 78        | 0.79%   |
| Microsoft                             | 52        | 0.53%   |
| MediaTek                              | 51        | 0.52%   |
| D-Link System                         | 29        | 0.29%   |
| Marvell Technology Group              | 9         | 0.09%   |
| Edimax Technology                     | 9         | 0.09%   |
| Mercucys                              | 6         | 0.06%   |
| Dell                                  | 6         | 0.06%   |
| Micro Star International              | 4         | 0.04%   |
| Encore Electronics                    | 4         | 0.04%   |
| NetGear                               | 3         | 0.03%   |
| Linksys                               | 3         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.03%   |
| Sierra Wireless                       | 2         | 0.02%   |
| Philips (or NXP)                      | 2         | 0.02%   |
| IMC Networks                          | 2         | 0.02%   |
| ASUSTek Computer                      | 2         | 0.02%   |
| Accton Technology                     | 2         | 0.02%   |
| Xiaomi                                | 1         | 0.01%   |
| Texas Instruments                     | 1         | 0.01%   |
| Samsung Electronics                   | 1         | 0.01%   |
| Pegatron                              | 1         | 0.01%   |
| Guillemot                             | 1         | 0.01%   |
| Ericsson Business Mobile Networks     | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 912       | 9.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 805       | 8.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 693       | 6.98%   |
| Intel Wi-Fi 6 AX200                                            | 394       | 3.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 342       | 3.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 337       | 3.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 328       | 3.3%    |
| Intel Wi-Fi 6 AX201                                            | 258       | 2.6%    |
| Ralink MT7601U Wireless Adapter                                | 253       | 2.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 227       | 2.29%   |
| Intel Wireless 7265                                            | 192       | 1.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 179       | 1.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 144       | 1.45%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 132       | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 131       | 1.32%   |
| Qualcomm Atheros AR9271 802.11n                                | 126       | 1.27%   |
| Intel Wireless 7260                                            | 122       | 1.23%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 119       | 1.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 116       | 1.17%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 113       | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 110       | 1.11%   |
| Intel Wireless 3165                                            | 105       | 1.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 96        | 0.97%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 91        | 0.92%   |
| Ralink RT5370 Wireless Adapter                                 | 90        | 0.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 90        | 0.91%   |
| Realtek 802.11ac NIC                                           | 89        | 0.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 88        | 0.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 86        | 0.87%   |
| Intel Wireless 3160                                            | 86        | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 85        | 0.86%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 78        | 0.79%   |
| Intel Wireless 8265 / 8275                                     | 73        | 0.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 73        | 0.73%   |
| Intel Centrino Advanced-N 6235                                 | 71        | 0.71%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 70        | 0.7%    |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 67        | 0.67%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 60        | 0.6%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 60        | 0.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 59        | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 8464      | 69.04%  |
| Intel                             | 1202      | 9.8%    |
| Qualcomm Atheros                  | 752       | 6.13%   |
| Broadcom                          | 462       | 3.77%   |
| Marvell Technology Group          | 236       | 1.92%   |
| JMicron Technology                | 235       | 1.92%   |
| Nvidia                            | 221       | 1.8%    |
| Samsung Electronics               | 122       | 1%      |
| Silicon Integrated Systems [SiS]  | 105       | 0.86%   |
| Broadcom Limited                  | 95        | 0.77%   |
| VIA Technologies                  | 71        | 0.58%   |
| Xiaomi                            | 56        | 0.46%   |
| ASIX Electronics                  | 44        | 0.36%   |
| Motorola PCS                      | 37        | 0.3%    |
| TP-Link                           | 20        | 0.16%   |
| ICS Advent                        | 19        | 0.15%   |
| DisplayLink                       | 14        | 0.11%   |
| D-Link System                     | 13        | 0.11%   |
| MediaTek                          | 10        | 0.08%   |
| Huawei Technologies               | 7         | 0.06%   |
| Qualcomm                          | 6         | 0.05%   |
| LG Electronics                    | 6         | 0.05%   |
| Microchip Technology              | 5         | 0.04%   |
| Lenovo                            | 5         | 0.04%   |
| ASUSTek Computer                  | 5         | 0.04%   |
| 3Com                              | 5         | 0.04%   |
| Sundance Technology Inc / IC Plus | 4         | 0.03%   |
| OPPO Electronics                  | 4         | 0.03%   |
| Attansic Technology               | 4         | 0.03%   |
| Hangzhou Silan Microelectronics   | 3         | 0.02%   |
| Dell                              | 3         | 0.02%   |
| Aquantia                          | 3         | 0.02%   |
| Apple                             | 3         | 0.02%   |
| Accton Technology                 | 3         | 0.02%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.02%   |
| T & A Mobile Phones               | 2         | 0.02%   |
| Spreadtrum Communications         | 2         | 0.02%   |
| IBM                               | 2         | 0.02%   |
| Standard Microsystems             | 1         | 0.01%   |
| SK hynix                          | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6061      | 48.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1966      | 15.83%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 193       | 1.55%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 167       | 1.34%   |
| Nvidia MCP61 Ethernet                                             | 164       | 1.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 161       | 1.3%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 122       | 0.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 116       | 0.93%   |
| Realtek RTL8125 2.5GbE Controller                                 | 114       | 0.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 107       | 0.86%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 107       | 0.86%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 98        | 0.79%   |
| Intel Ethernet Connection (2) I219-V                              | 98        | 0.79%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 92        | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 87        | 0.7%    |
| Intel I211 Gigabit Network Connection                             | 84        | 0.68%   |
| Intel Ethernet Connection (7) I219-V                              | 84        | 0.68%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 81        | 0.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 80        | 0.64%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 73        | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 72        | 0.58%   |
| Intel 82579V Gigabit Network Connection                           | 70        | 0.56%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 68        | 0.55%   |
| Intel Ethernet Connection I217-LM                                 | 64        | 0.52%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 53        | 0.43%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 52        | 0.42%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 52        | 0.42%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 52        | 0.42%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 45        | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 44        | 0.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 42        | 0.34%   |
| Intel 82578DC Gigabit Network Connection                          | 41        | 0.33%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 40        | 0.32%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 38        | 0.31%   |
| Motorola PCS motorola edge 20 lite                                | 37        | 0.3%    |
| ASIX AX88179 Gigabit Ethernet                                     | 37        | 0.3%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 36        | 0.29%   |
| Intel Ethernet Connection (4) I219-LM                             | 35        | 0.28%   |
| Intel Ethernet Connection (2) I218-V                              | 33        | 0.27%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 31        | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 11819     | 55.3%   |
| WiFi     | 9465      | 44.28%  |
| Modem    | 64        | 0.3%    |
| Unknown  | 25        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 7760      | 57.83%  |
| Ethernet | 5656      | 42.15%  |
| Unknown  | 2         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 7449      | 57.29%  |
| 1     | 5039      | 38.75%  |
| 0     | 399       | 3.07%   |
| 3     | 87        | 0.67%   |
| 4     | 21        | 0.16%   |
| 10    | 3         | 0.02%   |
| 5     | 3         | 0.02%   |
| 8     | 1         | 0.01%   |
| 6     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 9978      | 75.03%  |
| Yes  | 3321      | 24.97%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2360      | 35.43%  |
| Qualcomm Atheros Communications | 1668      | 25.04%  |
| Lite-On Technology              | 692       | 10.39%  |
| Cambridge Silicon Radio         | 559       | 8.39%   |
| Realtek Semiconductor           | 293       | 4.4%    |
| Broadcom                        | 232       | 3.48%   |
| IMC Networks                    | 159       | 2.39%   |
| Apple                           | 148       | 2.22%   |
| Foxconn / Hon Hai               | 132       | 1.98%   |
| Dell                            | 81        | 1.22%   |
| Hewlett-Packard                 | 62        | 0.93%   |
| Ralink                          | 55        | 0.83%   |
| Smart Modular Technologies      | 48        | 0.72%   |
| Qcom                            | 28        | 0.42%   |
| ASUSTek Computer                | 23        | 0.35%   |
| Ralink Technology               | 17        | 0.26%   |
| MediaTek                        | 16        | 0.24%   |
| Foxconn International           | 13        | 0.2%    |
| Alps Electric                   | 13        | 0.2%    |
| Askey Computer                  | 10        | 0.15%   |
| Integrated System Solution      | 8         | 0.12%   |
| Toshiba                         | 6         | 0.09%   |
| Micro Star International        | 6         | 0.09%   |
| Opticis                         | 5         | 0.08%   |
| ISSC                            | 4         | 0.06%   |
| Actions                         | 4         | 0.06%   |
| Marvell Semiconductor           | 3         | 0.05%   |
| Conwise Technology              | 3         | 0.05%   |
| Unknown                         | 3         | 0.05%   |
| Syntek                          | 2         | 0.03%   |
| SINO WEALTH                     | 2         | 0.03%   |
| USI                             | 1         | 0.02%   |
| TP-Link                         | 1         | 0.02%   |
| Realtek                         | 1         | 0.02%   |
| Motorola PCS                    | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                                                  | 960       | 14.41%  |
| Intel Bluetooth wireless interface                                                  | 759       | 11.39%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 598       | 8.97%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 559       | 8.39%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 388       | 5.82%   |
| Intel AX200 Bluetooth                                                               | 383       | 5.75%   |
| Intel AX201 Bluetooth                                                               | 268       | 4.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 259       | 3.89%   |
| Realtek Bluetooth Radio                                                             | 228       | 3.42%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 154       | 2.31%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 147       | 2.21%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 129       | 1.94%   |
| Intel Bluetooth Device                                                              | 113       | 1.7%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 102       | 1.53%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 99        | 1.49%   |
| Lite-On Bluetooth Device                                                            | 93        | 1.4%    |
| IMC Networks Bluetooth Radio                                                        | 85        | 1.28%   |
| Apple Bluetooth Host Controller                                                     | 66        | 0.99%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 65        | 0.98%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 61        | 0.92%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 60        | 0.9%    |
| Broadcom BCM2070 Bluetooth Device                                                   | 59        | 0.89%   |
| Ralink RT3290 Bluetooth                                                             | 55        | 0.83%   |
| Smart Modular Bluetooth Device                                                      | 48        | 0.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 45        | 0.68%   |
| Apple Bluetooth USB Host Controller                                                 | 37        | 0.56%   |
| Dell Wireless 365 Bluetooth                                                         | 35        | 0.53%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 34        | 0.51%   |
| Intel AX210 Bluetooth                                                               | 33        | 0.5%    |
| IMC Networks Bluetooth Device                                                       | 33        | 0.5%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 32        | 0.48%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 30        | 0.45%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 25        | 0.38%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 25        | 0.38%   |
| Lite-On Atheros Bluetooth                                                           | 24        | 0.36%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 23        | 0.35%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 22        | 0.33%   |
| Lite-On Wireless_Device                                                             | 21        | 0.32%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 19        | 0.29%   |
| Apple Bluetooth HCI                                                                 | 19        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 9991      | 59.95%  |
| AMD                                             | 2730      | 16.38%  |
| Nvidia                                          | 2568      | 15.41%  |
| C-Media Electronics                             | 278       | 1.67%   |
| Generalplus Technology                          | 138       | 0.83%   |
| Silicon Integrated Systems [SiS]                | 106       | 0.64%   |
| Logitech                                        | 104       | 0.62%   |
| VIA Technologies                                | 77        | 0.46%   |
| JMTek                                           | 72        | 0.43%   |
| Kingston Technology                             | 61        | 0.37%   |
| Texas Instruments                               | 47        | 0.28%   |
| Creative Labs                                   | 41        | 0.25%   |
| Corsair                                         | 31        | 0.19%   |
| Microsoft                                       | 28        | 0.17%   |
| Plantronics                                     | 21        | 0.13%   |
| Razer USA                                       | 19        | 0.11%   |
| GN Netcom                                       | 17        | 0.1%    |
| Realtek Semiconductor                           | 16        | 0.1%    |
| Licensed by Sony Computer Entertainment America | 16        | 0.1%    |
| BEHRINGER International                         | 16        | 0.1%    |
| Tenx Technology                                 | 15        | 0.09%   |
| Sony                                            | 15        | 0.09%   |
| Goldvish                                        | 12        | 0.07%   |
| Dell                                            | 12        | 0.07%   |
| JBL                                             | 9         | 0.05%   |
| Focusrite-Novation                              | 9         | 0.05%   |
| Samson Technologies                             | 8         | 0.05%   |
| M-Audio                                         | 8         | 0.05%   |
| Jieli Technology                                | 8         | 0.05%   |
| HECATE G2 GAMING HEADSET                        | 8         | 0.05%   |
| SteelSeries ApS                                 | 7         | 0.04%   |
| Fry's Electronics                               | 7         | 0.04%   |
| Creative Technology                             | 7         | 0.04%   |
| ASUSTek Computer                                | 7         | 0.04%   |
| Samsung Electronics                             | 6         | 0.04%   |
| Philips (or NXP)                                | 6         | 0.04%   |
| FIFINE Microphones                              | 6         | 0.04%   |
| Tdlasunnic                                      | 5         | 0.03%   |
| KTMicro                                         | 5         | 0.03%   |
| Elite Silicon                                   | 5         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1295      | 6.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1243      | 6.41%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1238      | 6.39%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 739       | 3.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 735       | 3.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 637       | 3.29%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 595       | 3.07%   |
| Intel Cannon Lake PCH cAVS                                                                        | 554       | 2.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 459       | 2.37%   |
| Intel 8 Series HD Audio Controller                                                                | 429       | 2.21%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 425       | 2.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 406       | 2.1%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 396       | 2.04%   |
| Intel Broadwell-U Audio Controller                                                                | 350       | 1.81%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 347       | 1.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 338       | 1.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 323       | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 314       | 1.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 284       | 1.47%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 279       | 1.44%   |
| AMD FCH Azalia Controller                                                                         | 277       | 1.43%   |
| Nvidia High Definition Audio Controller                                                           | 254       | 1.31%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 233       | 1.2%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 226       | 1.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 223       | 1.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 221       | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 199       | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 192       | 0.99%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 184       | 0.95%   |
| Nvidia MCP61 High Definition Audio                                                                | 180       | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 177       | 0.91%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 171       | 0.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 168       | 0.87%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 159       | 0.82%   |
| AMD Wrestler HDMI Audio                                                                           | 159       | 0.82%   |
| Intel 200 Series PCH HD Audio                                                                     | 158       | 0.82%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 157       | 0.81%   |
| Generalplus Technology USB Audio Device                                                           | 138       | 0.71%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 129       | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 126       | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 981       | 17.19%  |
| Kingston            | 912       | 15.98%  |
| Smart               | 767       | 13.44%  |
| Samsung Electronics | 536       | 9.39%   |
| SK hynix            | 381       | 6.67%   |
| A-DATA Technology   | 347       | 6.08%   |
| Corsair             | 251       | 4.4%    |
| Teikon              | 195       | 3.42%   |
| Crucial             | 193       | 3.38%   |
| Micron Technology   | 189       | 3.31%   |
| Smart Brazil        | 121       | 2.12%   |
| High Bridge         | 70        | 1.23%   |
| Unknown             | 69        | 1.21%   |
| Team                | 60        | 1.05%   |
| Elpida              | 52        | 0.91%   |
| Multilaser          | 51        | 0.89%   |
| Unknown (ABCD)      | 43        | 0.75%   |
| G.Skill             | 42        | 0.74%   |
| Apacer              | 31        | 0.54%   |
| Patriot             | 30        | 0.53%   |
| Nanya Technology    | 24        | 0.42%   |
| Kllisre             | 24        | 0.42%   |
| Atermiter           | 23        | 0.4%    |
| Avant               | 18        | 0.32%   |
| PUSKILL             | 15        | 0.26%   |
| Ramaxel Technology  | 14        | 0.25%   |
| HT Micron           | 13        | 0.23%   |
| Kreton              | 12        | 0.21%   |
| Smart Modular       | 11        | 0.19%   |
| HBS                 | 11        | 0.19%   |
| RZX                 | 10        | 0.18%   |
| CSX                 | 10        | 0.18%   |
| GeIL                | 9         | 0.16%   |
| Kingmax             | 8         | 0.14%   |
| Unknown (0x0B5E)    | 7         | 0.12%   |
| Transcend           | 7         | 0.12%   |
| Asgard              | 7         | 0.12%   |
| Walton Chaintech    | 6         | 0.11%   |
| Unknown (82B5)      | 6         | 0.11%   |
| Positivo            | 6         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 83        | 1.33%   |
| Unknown                                                          | 69        | 1.1%    |
| Smart RAM SH564568FH8NZPHSCR 2048MB SODIMM DDR3 1333MT/s         | 56        | 0.89%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 56        | 0.89%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 50        | 0.8%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 49        | 0.78%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 47        | 0.75%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1334MT/s            | 47        | 0.75%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 42        | 0.67%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 41        | 0.66%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 40        | 0.64%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 39        | 0.62%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 37        | 0.59%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 36        | 0.58%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 33        | 0.53%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 33        | 0.53%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 33        | 0.53%   |
| Kingston RAM KHX1600C10D3/8G 4GB DIMM DDR3 1600MT/s              | 33        | 0.53%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 30        | 0.48%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 29        | 0.46%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s            | 28        | 0.45%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s            | 27        | 0.43%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 26        | 0.42%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8GB SODIMM DDR4 2667MT/s             | 26        | 0.42%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 24        | 0.38%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s           | 24        | 0.38%   |
| Smart RAM SH564568FH8NZPHSCG 2GB SODIMM DDR3 1333MT/s            | 24        | 0.38%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 23        | 0.37%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s            | 23        | 0.37%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 22        | 0.35%   |
| A-DATA RAM AE4S240038G17-BHYA 8GB SODIMM DDR4 2400MT/s           | 22        | 0.35%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 21        | 0.34%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 21        | 0.34%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4GB SODIMM DDR4 2400MT/s             | 21        | 0.34%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 20        | 0.32%   |
| Unknown RAM Module 2GB DIMM DDR2                                 | 20        | 0.32%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s            | 20        | 0.32%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 19        | 0.3%    |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s              | 19        | 0.3%    |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 19        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR3         | 2043      | 42.28%  |
| DDR4         | 1796      | 37.17%  |
| DDR2         | 319       | 6.6%    |
| Unknown      | 220       | 4.55%   |
| SDRAM        | 208       | 4.3%    |
| LPDDR4       | 97        | 2.01%   |
| DDR          | 47        | 0.97%   |
| LPDDR3       | 35        | 0.72%   |
| DDR5         | 33        | 0.68%   |
| DRAM         | 24        | 0.5%    |
| LPDDR5       | 7         | 0.14%   |
| RAM          | 2         | 0.04%   |
| DDR2 FB-DIMM | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2619      | 54.54%  |
| DIMM         | 2030      | 42.27%  |
| Row Of Chips | 127       | 2.64%   |
| Unknown      | 16        | 0.33%   |
| RIMM         | 4         | 0.08%   |
| FB-DIMM      | 4         | 0.08%   |
| Chip         | 2         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 1959      | 35.81%  |
| 8192  | 1603      | 29.31%  |
| 2048  | 1072      | 19.6%   |
| 16384 | 504       | 9.21%   |
| 1024  | 172       | 3.14%   |
| 32768 | 136       | 2.49%   |
| 512   | 18        | 0.33%   |
| 256   | 3         | 0.05%   |
| 15616 | 1         | 0.02%   |
| 1536  | 1         | 0.02%   |
| 16    | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1170      | 21.6%   |
| 1333    | 678       | 12.52%  |
| 2667    | 673       | 12.43%  |
| 2400    | 490       | 9.05%   |
| 3200    | 363       | 6.7%    |
| Unknown | 282       | 5.21%   |
| 1334    | 260       | 4.8%    |
| 800     | 178       | 3.29%   |
| 2133    | 169       | 3.12%   |
| 667     | 166       | 3.06%   |
| 1066    | 83        | 1.53%   |
| 3600    | 78        | 1.44%   |
| 3000    | 69        | 1.27%   |
| 3400    | 64        | 1.18%   |
| 1067    | 62        | 1.14%   |
| 1867    | 55        | 1.02%   |
| 4199    | 43        | 0.79%   |
| 3466    | 38        | 0.7%    |
| 533     | 38        | 0.7%    |
| 4267    | 37        | 0.68%   |
| 1866    | 36        | 0.66%   |
| 2800    | 31        | 0.57%   |
| 2933    | 27        | 0.5%    |
| 2666    | 26        | 0.48%   |
| 4800    | 25        | 0.46%   |
| 3733    | 24        | 0.44%   |
| 2048    | 23        | 0.42%   |
| 400     | 23        | 0.42%   |
| 975     | 22        | 0.41%   |
| 3800    | 17        | 0.31%   |
| 3151    | 17        | 0.31%   |
| 333     | 16        | 0.3%    |
| 3266    | 12        | 0.22%   |
| 3334    | 9         | 0.17%   |
| 6400    | 8         | 0.15%   |
| 8400    | 7         | 0.13%   |
| 1800    | 7         | 0.13%   |
| 3333    | 6         | 0.11%   |
| 1200    | 5         | 0.09%   |
| 41632   | 4         | 0.07%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 121       | 42.31%  |
| Seiko Epson           | 81        | 28.32%  |
| Samsung Electronics   | 26        | 9.09%   |
| Canon                 | 25        | 8.74%   |
| Brother Industries    | 19        | 6.64%   |
| Lexmark International | 3         | 1.05%   |
| QinHeng Electronics   | 2         | 0.7%    |
| Apple                 | 2         | 0.7%    |
| Xerox                 | 1         | 0.35%   |
| Ricoh                 | 1         | 0.35%   |
| Prolific Technology   | 1         | 0.35%   |
| Pantum                | 1         | 0.35%   |
| Oki Data              | 1         | 0.35%   |
| MIIIW                 | 1         | 0.35%   |
| ARGOX                 | 1         | 0.35%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                   | 14        | 4.84%   |
| Seiko Epson L396 Series                      | 11        | 3.81%   |
| Seiko Epson L355 Series                      | 9         | 3.11%   |
| HP Ink Tank Wireless 410 series              | 9         | 3.11%   |
| HP DeskJet 2700 series                       | 9         | 3.11%   |
| HP DeskJet 2130 series                       | 9         | 3.11%   |
| Seiko Epson L365 Series                      | 8         | 2.77%   |
| Canon G3010 series                           | 8         | 2.77%   |
| HP Deskjet 3050 J610 series                  | 7         | 2.42%   |
| HP Deskjet 2540 series                       | 7         | 2.42%   |
| HP LaserJet 1020                             | 6         | 2.08%   |
| HP DeskJet F4100 Printer series              | 6         | 2.08%   |
| Samsung SCX-4200 series                      | 5         | 1.73%   |
| Samsung M2070 Series                         | 5         | 1.73%   |
| Samsung M2020 Series                         | 5         | 1.73%   |
| HP LaserJet Professional P1102w              | 5         | 1.73%   |
| HP DeskJet 3630 series                       | 5         | 1.73%   |
| HP Deskjet 2050 J510                         | 5         | 1.73%   |
| Seiko Epson L360 Series                      | 4         | 1.38%   |
| HP LaserJet P1005                            | 4         | 1.38%   |
| HP DeskJet F4200 series                      | 4         | 1.38%   |
| HP DeskJet 2600 series                       | 4         | 1.38%   |
| Seiko Epson XP-240 Series                    | 3         | 1.04%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 3         | 1.04%   |
| Seiko Epson L375 Series                      | 3         | 1.04%   |
| Seiko Epson L3110 Series                     | 3         | 1.04%   |
| Seiko Epson L210 Series                      | 3         | 1.04%   |
| Samsung SCX-3200 Series                      | 3         | 1.04%   |
| HP LaserJet 1018                             | 3         | 1.04%   |
| HP Deskjet F4400 series                      | 3         | 1.04%   |
| Canon PIXMA MG3600 Series                    | 3         | 1.04%   |
| Brother HL-1200 series                       | 3         | 1.04%   |
| Seiko Epson L6160 Series                     | 2         | 0.69%   |
| Seiko Epson L380 Series                      | 2         | 0.69%   |
| Seiko Epson L120 Series                      | 2         | 0.69%   |
| Seiko Epson ET-2810 Series                   | 2         | 0.69%   |
| Seiko Epson ET-2700 Series                   | 2         | 0.69%   |
| Samsung SCX-3400 Series                      | 2         | 0.69%   |
| Samsung ML-216x Series Laser Printer         | 2         | 0.69%   |
| QinHeng CH340S                               | 2         | 0.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 9         | 42.86%  |
| Hewlett-Packard | 8         | 38.1%   |
| Seiko Epson     | 2         | 9.52%   |
| Plustek         | 1         | 4.76%   |
| Mustek Systems  | 1         | 4.76%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| HP ScanJet 2400c                                        | 5         | 23.81%  |
| Canon CanoScan LIDE 25                                  | 4         | 19.05%  |
| Canon CanoScan LiDE 110                                 | 2         | 9.52%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 4.76%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 4.76%   |
| Plustek 1200dpi USB Scanner                             | 1         | 4.76%   |
| Mustek Systems ScanExpress 1200 UB                      | 1         | 4.76%   |
| HP ScanJet G4050                                        | 1         | 4.76%   |
| HP ScanJet 3800c                                        | 1         | 4.76%   |
| HP Scanjet 200                                          | 1         | 4.76%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 4.76%   |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 4.76%   |
| Canon CanoScan LiDE 210                                 | 1         | 4.76%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1538      | 19.25%  |
| Microdia                               | 911       | 11.4%   |
| Realtek Semiconductor                  | 728       | 9.11%   |
| Quanta                                 | 639       | 8%      |
| Silicon Motion                         | 586       | 7.34%   |
| Sunplus Innovation Technology          | 543       | 6.8%    |
| Bison Electronics                      | 399       | 4.99%   |
| IMC Networks                           | 334       | 4.18%   |
| Logitech                               | 301       | 3.77%   |
| Suyin                                  | 295       | 3.69%   |
| Syntek                                 | 239       | 2.99%   |
| Alcor Micro                            | 159       | 1.99%   |
| Apple                                  | 135       | 1.69%   |
| Acer                                   | 110       | 1.38%   |
| Samsung Electronics                    | 99        | 1.24%   |
| Cheng Uei Precision Industry (Foxlink) | 93        | 1.16%   |
| Generalplus Technology                 | 73        | 0.91%   |
| Z-Star Microelectronics                | 64        | 0.8%    |
| Microsoft                              | 62        | 0.78%   |
| Ricoh                                  | 50        | 0.63%   |
| ALi                                    | 49        | 0.61%   |
| Sonix Technology                       | 48        | 0.6%    |
| SunplusIT                              | 31        | 0.39%   |
| GEMBIRD                                | 28        | 0.35%   |
| Aveo Technology                        | 28        | 0.35%   |
| Lite-On Technology                     | 26        | 0.33%   |
| OmniVision Technologies                | 25        | 0.31%   |
| Importek                               | 25        | 0.31%   |
| Jieli Technology                       | 23        | 0.29%   |
| Unknown                                | 22        | 0.28%   |
| Pixart Imaging                         | 21        | 0.26%   |
| icSpring                               | 21        | 0.26%   |
| LG Electronics                         | 19        | 0.24%   |
| Cubeternet                             | 18        | 0.23%   |
| Lenovo                                 | 16        | 0.2%    |
| Y Media                                | 15        | 0.19%   |
| Genesys Logic                          | 12        | 0.15%   |
| Shenzhen Kingcome Optoelectronic       | 11        | 0.14%   |
| Luxvisions Innotech Limited            | 11        | 0.14%   |
| Sunplus Technology                     | 10        | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD             | 340       | 4.25%   |
| Realtek Integrated_Webcam_HD              | 318       | 3.97%   |
| Quanta HD User Facing                     | 280       | 3.5%    |
| Chicony HD WebCam                         | 250       | 3.12%   |
| Chicony HD User Facing                    | 227       | 2.84%   |
| Silicon Motion Web Camera                 | 216       | 2.7%    |
| Sunplus Integrated_Webcam_HD              | 213       | 2.66%   |
| Quanta VGA WebCam                         | 181       | 2.26%   |
| Chicony Integrated Camera                 | 163       | 2.04%   |
| Chicony VGA WebCam                        | 146       | 1.82%   |
| Syntek Integrated Camera                  | 139       | 1.74%   |
| Sunplus HD WebCam                         | 115       | 1.44%   |
| Realtek Integrated Webcam                 | 115       | 1.44%   |
| Quanta HD WebCam                          | 105       | 1.31%   |
| Logitech Webcam C270                      | 105       | 1.31%   |
| Chicony USB 2.0 Camera                    | 99        | 1.24%   |
| Samsung Galaxy series, misc. (MTP mode)   | 98        | 1.22%   |
| Alcor Micro USB 2.0 PC cam                | 96        | 1.2%    |
| Microdia Laptop_Integrated_Webcam_HD      | 79        | 0.99%   |
| Logitech HD Pro Webcam C920               | 76        | 0.95%   |
| Bison BisonCam, NB Pro                    | 70        | 0.87%   |
| Bison EasyCamera                          | 66        | 0.82%   |
| IMC Networks Integrated Camera            | 61        | 0.76%   |
| Microdia Dell Laptop Integrated Webcam HD | 59        | 0.74%   |
| Silicon Motion WebCam SC-10HDD12636N      | 55        | 0.69%   |
| Bison HD Webcam                           | 54        | 0.67%   |
| Microdia Integrated Webcam HD             | 52        | 0.65%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 51        | 0.64%   |
| Realtek USB Camera                        | 49        | 0.61%   |
| Bison Integrated Camera                   | 49        | 0.61%   |
| Generalplus CAMERA - UVC                  | 48        | 0.6%    |
| Suyin Integrated_Webcam_HD                | 47        | 0.59%   |
| IMC Networks USB2.0 HD UVC WebCam         | 47        | 0.59%   |
| Chicony EasyCamera                        | 47        | 0.59%   |
| Bison VGA WebCam                          | 47        | 0.59%   |
| Silicon Motion WebCam SCB-1100N           | 45        | 0.56%   |
| Sonix USB2.0 HD UVC WebCam                | 44        | 0.55%   |
| Silicon Motion WebCam SC-13HDL11939N      | 43        | 0.54%   |
| Silicon Motion WebCam SC-0311139N         | 42        | 0.52%   |
| Realtek HD WebCam                         | 42        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 302       | 46.46%  |
| Synaptics                  | 80        | 12.31%  |
| Shenzhen Goodix Technology | 71        | 10.92%  |
| AuthenTec                  | 63        | 9.69%   |
| Upek                       | 60        | 9.23%   |
| LighTuning Technology      | 33        | 5.08%   |
| Samsung Electronics        | 18        | 2.77%   |
| Elan Microelectronics      | 11        | 1.69%   |
| STMicroelectronics         | 4         | 0.62%   |
| Futronic Technology        | 2         | 0.31%   |
| Focal-systems.Corp         | 2         | 0.31%   |
| Dell                       | 2         | 0.31%   |
| Next Biometrics            | 1         | 0.15%   |
| DigitalPersona             | 1         | 0.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 114       | 17.54%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 50        | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                     | 45        | 6.92%   |
| Validity Sensors VFS495 Fingerprint Reader             | 30        | 4.62%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 28        | 4.31%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 26        | 4%      |
| LighTuning ES603 Swipe Fingerprint Sensor              | 26        | 4%      |
| Validity Sensors VFS471 Fingerprint Reader             | 24        | 3.69%   |
| Validity Sensors Fingerprint scanner                   | 22        | 3.38%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 20        | 3.08%   |
| Validity Sensors VFS301 Fingerprint Reader             | 19        | 2.92%   |
| Shenzhen Goodix  FingerPrint Device                    | 19        | 2.92%   |
| Synaptics  WBDI                                        | 18        | 2.77%   |
| Samsung Fingerprint Device                             | 18        | 2.77%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 15        | 2.31%   |
| Validity Sensors VFS101 Fingerprint Reader             | 14        | 2.15%   |
| AuthenTec AES2810                                      | 14        | 2.15%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 14        | 2.15%   |
| Validity Sensors VFS491                                | 12        | 1.85%   |
| Validity Sensors VFS451 Fingerprint Reader             | 12        | 1.85%   |
| AuthenTec Fingerprint Sensor                           | 11        | 1.69%   |
| Upek TCS5B Fingerprint sensor                          | 9         | 1.38%   |
| Validity Sensors VFS300 Fingerprint Reader             | 8         | 1.23%   |
| Validity Sensors Swipe Fingerprint Sensor              | 8         | 1.23%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 7         | 1.08%   |
| Shenzhen Goodix FingerPrint                            | 7         | 1.08%   |
| Validity Sensors Synaptics WBDI                        | 6         | 0.92%   |
| Synaptics WBDI                                         | 6         | 0.92%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 6         | 0.92%   |
| Elan ELAN:Fingerprint                                  | 6         | 0.92%   |
| Elan WBF Fingerprint Sensor                            | 5         | 0.77%   |
| STMicroelectronics Fingerprint Reader                  | 4         | 0.62%   |
| AuthenTec AES1600                                      | 4         | 0.62%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor      | 3         | 0.46%   |
| Synaptics Fingerprint reader [HP G6]                   | 2         | 0.31%   |
| Futronic FS81 Fingerprint Scanner Module               | 2         | 0.31%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 2         | 0.31%   |
| Dell MS819 Wired Mouse With Fingerprint Reader         | 2         | 0.31%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 0.15%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 0.15%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 89        | 44.06%  |
| Alcor Micro                       | 29        | 14.36%  |
| Gemalto (was Gemplus)             | 16        | 7.92%   |
| Lenovo                            | 14        | 6.93%   |
| Giesecke & Devrient               | 13        | 6.44%   |
| Upek                              | 10        | 4.95%   |
| Watchdata                         | 7         | 3.47%   |
| Aladdin Knowledge Systems         | 6         | 2.97%   |
| SCM Microsystems                  | 4         | 1.98%   |
| OmniKey                           | 3         | 1.49%   |
| O2 Micro                          | 3         | 1.49%   |
| Chicony Electronics               | 3         | 1.49%   |
| Castles Technology                | 2         | 0.99%   |
| VASCO Data Security International | 1         | 0.5%    |
| Realtek Semiconductor             | 1         | 0.5%    |
| Advanced Card Systems             | 1         | 0.5%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 29        | 14.36%  |
| Broadcom 58200                                                               | 26        | 12.87%  |
| Broadcom 5880                                                                | 23        | 11.39%  |
| Broadcom BCM5880 Secure Applications Processor                               | 22        | 10.89%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 18        | 8.91%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 15        | 7.43%   |
| Lenovo Integrated Smart Card Reader                                          | 14        | 6.93%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 10        | 4.95%   |
| Watchdata USB Key                                                            | 7         | 3.47%   |
| Giesecke & Devrient StarSign CUT                                             | 7         | 3.47%   |
| Giesecke & Devrient StarSign CUT S                                           | 6         | 2.97%   |
| Aladdin Knowledge Systems Token JC                                           | 6         | 2.97%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 3         | 1.49%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 2         | 0.99%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 0.99%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.99%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 0.99%   |
| Castles Technology EZCCID Smart Card Reader                                  | 2         | 0.99%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.5%    |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.5%    |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.5%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.5%    |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.5%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.5%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 10450     | 79.33%  |
| 1     | 2350      | 17.84%  |
| 2     | 295       | 2.24%   |
| 3     | 48        | 0.36%   |
| 4     | 20        | 0.15%   |
| 7     | 4         | 0.03%   |
| 5     | 3         | 0.02%   |
| 8     | 2         | 0.02%   |
| 6     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 952       | 30.96%  |
| Fingerprint reader       | 646       | 21.01%  |
| Net/wireless             | 400       | 13.01%  |
| Multimedia controller    | 277       | 9.01%   |
| Chipcard                 | 170       | 5.53%   |
| Communication controller | 128       | 4.16%   |
| Bluetooth                | 101       | 3.28%   |
| Camera                   | 89        | 2.89%   |
| Unassigned class         | 67        | 2.18%   |
| Sound                    | 66        | 2.15%   |
| Storage                  | 45        | 1.46%   |
| Net/ethernet             | 39        | 1.27%   |
| Modem                    | 24        | 0.78%   |
| Flash memory             | 21        | 0.68%   |
| Card reader              | 14        | 0.46%   |
| Network                  | 10        | 0.33%   |
| Storage/ide              | 8         | 0.26%   |
| Firewire controller      | 6         | 0.2%    |
| Storage/raid             | 5         | 0.16%   |
| Storage/nvme             | 3         | 0.1%    |
| Wireless                 | 1         | 0.03%   |
| Video                    | 1         | 0.03%   |
| Storage/ata              | 1         | 0.03%   |
| Dvb card                 | 1         | 0.03%   |


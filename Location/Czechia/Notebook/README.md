Linux in Czechia - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Czechia.

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

Total: 1441

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [5955142015](https://linux-hardware.org/?probe=5955142015) | Dec 01, 2022 |
| HUAWEI        | KLVL-WXX9                   | [ea8b9066f6](https://linux-hardware.org/?probe=ea8b9066f6) | Nov 30, 2022 |
| HP            | 620                         | [5baeeace34](https://linux-hardware.org/?probe=5baeeace34) | Nov 28, 2022 |
| ASUSTek       | UX31E                       | [97c63f232d](https://linux-hardware.org/?probe=97c63f232d) | Nov 28, 2022 |
| Fujitsu       | LIFEBOOK E756               | [9e69bdbaff](https://linux-hardware.org/?probe=9e69bdbaff) | Nov 25, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [53b311f78c](https://linux-hardware.org/?probe=53b311f78c) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | [16acde36ab](https://linux-hardware.org/?probe=16acde36ab) | Nov 25, 2022 |
| HP            | 620                         | [a09882989c](https://linux-hardware.org/?probe=a09882989c) | Nov 23, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [be7a4a88a1](https://linux-hardware.org/?probe=be7a4a88a1) | Nov 23, 2022 |
| MSI           | Modern 14 B5M               | [2bd9abfe2c](https://linux-hardware.org/?probe=2bd9abfe2c) | Nov 20, 2022 |
| ASUSTek       | N73SV                       | [10840bac50](https://linux-hardware.org/?probe=10840bac50) | Nov 20, 2022 |
| ASUSTek       | K50IJ                       | [c57a9ae3d5](https://linux-hardware.org/?probe=c57a9ae3d5) | Nov 19, 2022 |
| ASUSTek       | K50IJ                       | [99ed91b58d](https://linux-hardware.org/?probe=99ed91b58d) | Nov 19, 2022 |
| Dell          | Precision 5510              | [a9467ec69d](https://linux-hardware.org/?probe=a9467ec69d) | Nov 18, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [3050d57edc](https://linux-hardware.org/?probe=3050d57edc) | Nov 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [9c25ade74d](https://linux-hardware.org/?probe=9c25ade74d) | Nov 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [3eaa12ef7a](https://linux-hardware.org/?probe=3eaa12ef7a) | Nov 16, 2022 |
| ASUSTek       | K50IJ                       | [c7ac1636bc](https://linux-hardware.org/?probe=c7ac1636bc) | Nov 15, 2022 |
| ASUSTek       | N61Jv                       | [c8c143ccdd](https://linux-hardware.org/?probe=c8c143ccdd) | Nov 14, 2022 |
| ASUSTek       | N61Jv                       | [bc9518dbad](https://linux-hardware.org/?probe=bc9518dbad) | Nov 13, 2022 |
| ASUSTek       | N61Jv                       | [a7e35fd231](https://linux-hardware.org/?probe=a7e35fd231) | Nov 12, 2022 |
| Dell          | Latitude 7480               | [62d1e401a4](https://linux-hardware.org/?probe=62d1e401a4) | Nov 12, 2022 |
| HP            | Pavilion g6                 | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| Dell          | Latitude 7480               | [350e3f7ee2](https://linux-hardware.org/?probe=350e3f7ee2) | Nov 11, 2022 |
| ASUSTek       | UX31E                       | [fa27762189](https://linux-hardware.org/?probe=fa27762189) | Nov 11, 2022 |
| HP            | Pavilion dv7                | [5b01559647](https://linux-hardware.org/?probe=5b01559647) | Nov 11, 2022 |
| ASUSTek       | K54LY                       | [721020a0fe](https://linux-hardware.org/?probe=721020a0fe) | Nov 11, 2022 |
| ASUSTek       | X550VXK                     | [f752e7959c](https://linux-hardware.org/?probe=f752e7959c) | Nov 10, 2022 |
| HP            | Pavilion g6                 | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Packard Be... | EasyNote TK85               | [8a4f5a2c29](https://linux-hardware.org/?probe=8a4f5a2c29) | Nov 07, 2022 |
| HP            | ProBook 4530s               | [afb0629ea9](https://linux-hardware.org/?probe=afb0629ea9) | Nov 07, 2022 |
| Dell          | Inspiron 5515               | [fcb59bae39](https://linux-hardware.org/?probe=fcb59bae39) | Nov 06, 2022 |
| HP            | ProBook 455 G7              | [4432a70f95](https://linux-hardware.org/?probe=4432a70f95) | Nov 06, 2022 |
| Dell          | Inspiron 5515               | [001308a248](https://linux-hardware.org/?probe=001308a248) | Nov 06, 2022 |
| HP            | Pavilion g6                 | [5ad3928a6d](https://linux-hardware.org/?probe=5ad3928a6d) | Nov 05, 2022 |
| HP            | Pavilion g6                 | [38b8d5a898](https://linux-hardware.org/?probe=38b8d5a898) | Nov 04, 2022 |
| Acer          | Aspire 5738                 | [f5ac63680f](https://linux-hardware.org/?probe=f5ac63680f) | Nov 04, 2022 |
| SLIMBOOK      | Executive                   | [cff86cc921](https://linux-hardware.org/?probe=cff86cc921) | Nov 04, 2022 |
| Sony          | VPCYB1S1E                   | [54d0a26de9](https://linux-hardware.org/?probe=54d0a26de9) | Nov 03, 2022 |
| UMAX          | VisionBook N15G Plus        | [eba9cd6286](https://linux-hardware.org/?probe=eba9cd6286) | Nov 03, 2022 |
| HUAWEI        | MACHC-WAX9                  | [e4f3828910](https://linux-hardware.org/?probe=e4f3828910) | Nov 01, 2022 |
| ASUSTek       | UX31E                       | [6e9cb9c0e0](https://linux-hardware.org/?probe=6e9cb9c0e0) | Oct 29, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [eb22113dae](https://linux-hardware.org/?probe=eb22113dae) | Oct 29, 2022 |
| UMAX          | VisionBook 12Wi 64G         | [9fe98911c1](https://linux-hardware.org/?probe=9fe98911c1) | Oct 27, 2022 |
| Lenovo        | B590 20206                  | [8a8967999b](https://linux-hardware.org/?probe=8a8967999b) | Oct 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d58a7c30a9](https://linux-hardware.org/?probe=d58a7c30a9) | Oct 26, 2022 |
| Dell          | Latitude E6440              | [307356784a](https://linux-hardware.org/?probe=307356784a) | Oct 26, 2022 |
| Apple         | MacBookPro10,1              | [212ce8900d](https://linux-hardware.org/?probe=212ce8900d) | Oct 26, 2022 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [3d86f7ccac](https://linux-hardware.org/?probe=3d86f7ccac) | Oct 25, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [025f4fa8ab](https://linux-hardware.org/?probe=025f4fa8ab) | Oct 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [e3265d4cdc](https://linux-hardware.org/?probe=e3265d4cdc) | Oct 20, 2022 |
| HP            | Pavilion dv7                | [4c6edfec3e](https://linux-hardware.org/?probe=4c6edfec3e) | Oct 18, 2022 |
| HP            | Pavilion dv7                | [22031176a8](https://linux-hardware.org/?probe=22031176a8) | Oct 18, 2022 |
| ASUSTek       | UX31E                       | [bddc33ef5a](https://linux-hardware.org/?probe=bddc33ef5a) | Oct 14, 2022 |
| Dell          | XPS 15 9550                 | [00d5f7c4b1](https://linux-hardware.org/?probe=00d5f7c4b1) | Oct 13, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5074f8e471](https://linux-hardware.org/?probe=5074f8e471) | Oct 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [fb97ad01eb](https://linux-hardware.org/?probe=fb97ad01eb) | Oct 12, 2022 |
| SmbiosType... | SmbiosType1_SystemProduc... | [d105b4c1f7](https://linux-hardware.org/?probe=d105b4c1f7) | Oct 11, 2022 |
| ASUSTek       | UX31E                       | [22cf469faa](https://linux-hardware.org/?probe=22cf469faa) | Oct 10, 2022 |
| Lenovo        | Z50-75 80EC                 | [3837291e33](https://linux-hardware.org/?probe=3837291e33) | Oct 10, 2022 |
| Dell          | Latitude E7250              | [5ecb7bbb6c](https://linux-hardware.org/?probe=5ecb7bbb6c) | Oct 07, 2022 |
| ASUSTek       | 1001PXD                     | [524e4ab046](https://linux-hardware.org/?probe=524e4ab046) | Oct 06, 2022 |
| HP            | EliteBook 1040 G4           | [8a19b834c8](https://linux-hardware.org/?probe=8a19b834c8) | Oct 04, 2022 |
| Timi          | A35S                        | [fe7ad0ac13](https://linux-hardware.org/?probe=fe7ad0ac13) | Oct 03, 2022 |
| ASUSTek       | K54LY                       | [230a36c236](https://linux-hardware.org/?probe=230a36c236) | Oct 03, 2022 |
| ASUSTek       | K54LY                       | [7c19c1f557](https://linux-hardware.org/?probe=7c19c1f557) | Oct 02, 2022 |
| Acer          | Aspire 7540                 | [8e80ccea19](https://linux-hardware.org/?probe=8e80ccea19) | Oct 01, 2022 |
| ASUSTek       | K54LY                       | [98197c818f](https://linux-hardware.org/?probe=98197c818f) | Oct 01, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [92f9efe077](https://linux-hardware.org/?probe=92f9efe077) | Sep 30, 2022 |
| Notebook      | NJ50GU                      | [430d3b2873](https://linux-hardware.org/?probe=430d3b2873) | Sep 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [9015ce1da8](https://linux-hardware.org/?probe=9015ce1da8) | Sep 30, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [9377d23abd](https://linux-hardware.org/?probe=9377d23abd) | Sep 28, 2022 |
| Timi          | A35S                        | [bdb2ba4eab](https://linux-hardware.org/?probe=bdb2ba4eab) | Sep 27, 2022 |
| ASUSTek       | K53SV                       | [d2801f9560](https://linux-hardware.org/?probe=d2801f9560) | Sep 26, 2022 |
| Lenovo        | 3000 V100 076346G           | [0575c1ea4f](https://linux-hardware.org/?probe=0575c1ea4f) | Sep 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| Timi          | RedmiBook 16                | [0a65bab615](https://linux-hardware.org/?probe=0a65bab615) | Sep 25, 2022 |
| Acer          | Aspire VN7-592G             | [cfc28181e5](https://linux-hardware.org/?probe=cfc28181e5) | Sep 25, 2022 |
| HP            | ProBook 450 G5              | [262ff53f6a](https://linux-hardware.org/?probe=262ff53f6a) | Sep 25, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [4f9ff1b402](https://linux-hardware.org/?probe=4f9ff1b402) | Sep 24, 2022 |
| Toshiba       | Satellite A305              | [d1ed6b20cf](https://linux-hardware.org/?probe=d1ed6b20cf) | Sep 24, 2022 |
| Toshiba       | Satellite A305              | [9e04fb330b](https://linux-hardware.org/?probe=9e04fb330b) | Sep 24, 2022 |
| Timi          | A35S                        | [d0f195a77a](https://linux-hardware.org/?probe=d0f195a77a) | Sep 23, 2022 |
| Valve         | Jupiter                     | [0b88f458d2](https://linux-hardware.org/?probe=0b88f458d2) | Sep 22, 2022 |
| Acer          | Nitro AN515-57              | [59219d6ded](https://linux-hardware.org/?probe=59219d6ded) | Sep 21, 2022 |
| Lenovo        | ThinkPad T410 2518Q6G       | [b0568eadf2](https://linux-hardware.org/?probe=b0568eadf2) | Sep 20, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [dce5b5917c](https://linux-hardware.org/?probe=dce5b5917c) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| Acer          | Swift SF314-511             | [a171efb42c](https://linux-hardware.org/?probe=a171efb42c) | Sep 17, 2022 |
| Lenovo        | IdeaPad Y570 20091          | [5e2681360e](https://linux-hardware.org/?probe=5e2681360e) | Sep 15, 2022 |
| Dell          | Latitude 5430               | [617563f7a7](https://linux-hardware.org/?probe=617563f7a7) | Sep 14, 2022 |
| Lenovo        | ThinkPad T540p 20BF002CM... | [3343da6005](https://linux-hardware.org/?probe=3343da6005) | Sep 12, 2022 |
| ASUSTek       | UX31E                       | [910cdee832](https://linux-hardware.org/?probe=910cdee832) | Sep 11, 2022 |
| Lenovo        | ThinkPad T430 23444ZG       | [d83eee9752](https://linux-hardware.org/?probe=d83eee9752) | Sep 11, 2022 |
| UMAX          | VisionBook N14G Plus        | [6d05deca49](https://linux-hardware.org/?probe=6d05deca49) | Sep 11, 2022 |
| UMAX          | VisionBook N15G Plus        | [d17fb4f8f9](https://linux-hardware.org/?probe=d17fb4f8f9) | Sep 11, 2022 |
| Dell          | Latitude 5531               | [66eac260ef](https://linux-hardware.org/?probe=66eac260ef) | Sep 09, 2022 |
| Dell          | Precision 3551              | [78f7c77b35](https://linux-hardware.org/?probe=78f7c77b35) | Sep 09, 2022 |
| Lenovo        | B71-80 80RJ                 | [c16dc3a768](https://linux-hardware.org/?probe=c16dc3a768) | Sep 06, 2022 |
| Dell          | Latitude 5531               | [dff44a5e24](https://linux-hardware.org/?probe=dff44a5e24) | Sep 05, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [459e11c8ba](https://linux-hardware.org/?probe=459e11c8ba) | Sep 05, 2022 |
| Google        | Coral                       | [af898f9be4](https://linux-hardware.org/?probe=af898f9be4) | Sep 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [88392a79f5](https://linux-hardware.org/?probe=88392a79f5) | Sep 04, 2022 |
| ASUSTek       | UX31E                       | [21183dcf00](https://linux-hardware.org/?probe=21183dcf00) | Sep 02, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [60b4add0a0](https://linux-hardware.org/?probe=60b4add0a0) | Sep 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [2a3eb4b772](https://linux-hardware.org/?probe=2a3eb4b772) | Sep 02, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [cc30fbdce2](https://linux-hardware.org/?probe=cc30fbdce2) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [c48154f5f4](https://linux-hardware.org/?probe=c48154f5f4) | Sep 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0ca693e2dd](https://linux-hardware.org/?probe=0ca693e2dd) | Aug 31, 2022 |
| HP            | EliteBook 650 15.6 inch ... | [918418e0fc](https://linux-hardware.org/?probe=918418e0fc) | Aug 29, 2022 |
| ASUSTek       | X553MA                      | [108e0c7803](https://linux-hardware.org/?probe=108e0c7803) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [bddbedffed](https://linux-hardware.org/?probe=bddbedffed) | Aug 29, 2022 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [1ea46f19be](https://linux-hardware.org/?probe=1ea46f19be) | Aug 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [945109f9f8](https://linux-hardware.org/?probe=945109f9f8) | Aug 25, 2022 |
| Valve         | Jupiter                     | [fbef109b91](https://linux-hardware.org/?probe=fbef109b91) | Aug 24, 2022 |
| MSI           | GS73VR 6RF                  | [870534e620](https://linux-hardware.org/?probe=870534e620) | Aug 23, 2022 |
| Dell          | Latitude 5490               | [a37eabe03f](https://linux-hardware.org/?probe=a37eabe03f) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | [29d7ac6ea6](https://linux-hardware.org/?probe=29d7ac6ea6) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | [c8f76780a1](https://linux-hardware.org/?probe=c8f76780a1) | Aug 21, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [2e77015116](https://linux-hardware.org/?probe=2e77015116) | Aug 21, 2022 |
| ASUSTek       | UX31E                       | [84ed4c9d73](https://linux-hardware.org/?probe=84ed4c9d73) | Aug 20, 2022 |
| HP            | ElitePad 1000 G2            | [ed06ba603c](https://linux-hardware.org/?probe=ed06ba603c) | Aug 19, 2022 |
| Lenovo        | ThinkPad Edge E431 62774... | [b7d37d0c4c](https://linux-hardware.org/?probe=b7d37d0c4c) | Aug 18, 2022 |
| HP            | ProBook 450 G5              | [68697e720d](https://linux-hardware.org/?probe=68697e720d) | Aug 18, 2022 |
| HP            | ZBook 15 G3                 | [f89a185aa6](https://linux-hardware.org/?probe=f89a185aa6) | Aug 17, 2022 |
| ASUSTek       | X101CH                      | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| Acer          | Aspire 3100                 | [8ea61dbd3c](https://linux-hardware.org/?probe=8ea61dbd3c) | Aug 14, 2022 |
| Acer          | Aspire A515-56              | [e93f8de88b](https://linux-hardware.org/?probe=e93f8de88b) | Aug 13, 2022 |
| Acer          | Aspire A515-56              | [e429237c05](https://linux-hardware.org/?probe=e429237c05) | Aug 13, 2022 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | [0f367345a0](https://linux-hardware.org/?probe=0f367345a0) | Aug 12, 2022 |
| Notebook      | NJ50GU                      | [59d1efda98](https://linux-hardware.org/?probe=59d1efda98) | Aug 12, 2022 |
| Dell          | XPS 13 9360                 | [a78c885366](https://linux-hardware.org/?probe=a78c885366) | Aug 12, 2022 |
| Lenovo        | ThinkPad E590 20NB0029MC    | [233b3cdd54](https://linux-hardware.org/?probe=233b3cdd54) | Aug 11, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [8b0ede5e40](https://linux-hardware.org/?probe=8b0ede5e40) | Aug 10, 2022 |
| HUAWEI        | BOHB-WAX9                   | [9d55b54de7](https://linux-hardware.org/?probe=9d55b54de7) | Aug 10, 2022 |
| Dell          | Latitude 5421               | [b088f6b599](https://linux-hardware.org/?probe=b088f6b599) | Aug 10, 2022 |
| Dell          | Latitude 5531               | [64998a7d5a](https://linux-hardware.org/?probe=64998a7d5a) | Aug 09, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | [9c945add4e](https://linux-hardware.org/?probe=9c945add4e) | Aug 06, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | [d1ab7d1d36](https://linux-hardware.org/?probe=d1ab7d1d36) | Aug 06, 2022 |
| Lenovo        | ThinkPad X270 20HN0015GE    | [2577ffae50](https://linux-hardware.org/?probe=2577ffae50) | Aug 06, 2022 |
| Dell          | Inspiron 5558               | [2dee8f9fb1](https://linux-hardware.org/?probe=2dee8f9fb1) | Jul 31, 2022 |
| HP            | 250 G5 Notebook PC          | [75477a4d7a](https://linux-hardware.org/?probe=75477a4d7a) | Jul 28, 2022 |
| Dell          | G5 5590                     | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [45e79d015c](https://linux-hardware.org/?probe=45e79d015c) | Jul 23, 2022 |
| ASUSTek       | UX31E                       | [1ae28afad9](https://linux-hardware.org/?probe=1ae28afad9) | Jul 22, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [c000bcc566](https://linux-hardware.org/?probe=c000bcc566) | Jul 20, 2022 |
| HP            | ProBook 450 G5              | [47c85dbefd](https://linux-hardware.org/?probe=47c85dbefd) | Jul 18, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [eb5b940f17](https://linux-hardware.org/?probe=eb5b940f17) | Jul 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [179267a713](https://linux-hardware.org/?probe=179267a713) | Jul 15, 2022 |
| Dell          | G3 3590                     | [86835e6c2b](https://linux-hardware.org/?probe=86835e6c2b) | Jul 15, 2022 |
| ASUSTek       | K54LY                       | [9b66e8ad0e](https://linux-hardware.org/?probe=9b66e8ad0e) | Jul 14, 2022 |
| ASUSTek       | UX31E                       | [004f74eaf4](https://linux-hardware.org/?probe=004f74eaf4) | Jul 13, 2022 |
| HP            | Compaq nx6310 (EY589ES#A... | [613395d2cf](https://linux-hardware.org/?probe=613395d2cf) | Jul 13, 2022 |
| HP            | ProBook 450 G5              | [e3962f34e4](https://linux-hardware.org/?probe=e3962f34e4) | Jul 11, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | [cd5635c63c](https://linux-hardware.org/?probe=cd5635c63c) | Jul 08, 2022 |
| HP            | ProBook 450 G5              | [90f45f2ebc](https://linux-hardware.org/?probe=90f45f2ebc) | Jul 08, 2022 |
| Dell          | XPS 15 9510                 | [d8f1865db2](https://linux-hardware.org/?probe=d8f1865db2) | Jul 08, 2022 |
| Dell          | Latitude E5530 non-vPro     | [6a78826e86](https://linux-hardware.org/?probe=6a78826e86) | Jul 07, 2022 |
| ASUSTek       | X542UQR                     | [04cc10b779](https://linux-hardware.org/?probe=04cc10b779) | Jul 07, 2022 |
| Dell          | Inspiron 3542               | [57fc50a4fb](https://linux-hardware.org/?probe=57fc50a4fb) | Jul 06, 2022 |
| HP            | ProBook 4530s               | [db207530bc](https://linux-hardware.org/?probe=db207530bc) | Jul 06, 2022 |
| HP            | Notebook                    | [9b87d6ee2d](https://linux-hardware.org/?probe=9b87d6ee2d) | Jul 06, 2022 |
| Dell          | Latitude 7520               | [531ccedcf2](https://linux-hardware.org/?probe=531ccedcf2) | Jul 04, 2022 |
| Sony          | VPCSA3M9E                   | [b36435a1fd](https://linux-hardware.org/?probe=b36435a1fd) | Jul 03, 2022 |
| HP            | 625                         | [0acc5581d4](https://linux-hardware.org/?probe=0acc5581d4) | Jul 03, 2022 |
| ASUSTek       | UX31E                       | [7504f06baa](https://linux-hardware.org/?probe=7504f06baa) | Jul 02, 2022 |
| Lenovo        | Z70-80 80FG                 | [eaf34443c7](https://linux-hardware.org/?probe=eaf34443c7) | Jul 01, 2022 |
| ASUSTek       | UX31E                       | [d3f27ab291](https://linux-hardware.org/?probe=d3f27ab291) | Jul 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | [cf313915ab](https://linux-hardware.org/?probe=cf313915ab) | Jun 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [7e2ddf75e5](https://linux-hardware.org/?probe=7e2ddf75e5) | Jun 30, 2022 |
| Lenovo        | Z70-80 80FG                 | [bef849e3d1](https://linux-hardware.org/?probe=bef849e3d1) | Jun 29, 2022 |
| Lenovo        | ThinkPad S5-S540 20B3001... | [d5be9c4fca](https://linux-hardware.org/?probe=d5be9c4fca) | Jun 29, 2022 |
| Valve         | Jupiter                     | [e98c07bc79](https://linux-hardware.org/?probe=e98c07bc79) | Jun 29, 2022 |
| ASUSTek       | UX31E                       | [a346ece8f5](https://linux-hardware.org/?probe=a346ece8f5) | Jun 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | [d2925f529c](https://linux-hardware.org/?probe=d2925f529c) | Jun 25, 2022 |
| Dell          | Precision 5550              | [0811e8c956](https://linux-hardware.org/?probe=0811e8c956) | Jun 23, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [e0da282c48](https://linux-hardware.org/?probe=e0da282c48) | Jun 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| Dell          | Precision 5550              | [0ae65f654e](https://linux-hardware.org/?probe=0ae65f654e) | Jun 23, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | [6ed235813a](https://linux-hardware.org/?probe=6ed235813a) | Jun 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [27fd147a80](https://linux-hardware.org/?probe=27fd147a80) | Jun 19, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | [af51b1d9da](https://linux-hardware.org/?probe=af51b1d9da) | Jun 19, 2022 |
| Dell          | Latitude E5470              | [e18ba2b5d7](https://linux-hardware.org/?probe=e18ba2b5d7) | Jun 18, 2022 |
| HP            | Compaq nc6120 (PN936AV)     | [c1ecdd7b5a](https://linux-hardware.org/?probe=c1ecdd7b5a) | Jun 17, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [4a8b021e76](https://linux-hardware.org/?probe=4a8b021e76) | Jun 11, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | [565722f81e](https://linux-hardware.org/?probe=565722f81e) | Jun 09, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | [c36b6d8e2c](https://linux-hardware.org/?probe=c36b6d8e2c) | Jun 09, 2022 |
| Lenovo        | ThinkPad T460s 20FA003JM... | [417d162cab](https://linux-hardware.org/?probe=417d162cab) | Jun 09, 2022 |
| ASUSTek       | UX31E                       | [4abfa2a1d0](https://linux-hardware.org/?probe=4abfa2a1d0) | Jun 08, 2022 |
| HP            | ProBook 455 G7              | [81335c6978](https://linux-hardware.org/?probe=81335c6978) | Jun 08, 2022 |
| HP            | ProBook 455 G7              | [62d39f4677](https://linux-hardware.org/?probe=62d39f4677) | Jun 08, 2022 |
| ASUSTek       | K54LY                       | [39ad69783e](https://linux-hardware.org/?probe=39ad69783e) | Jun 08, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c6975f2914](https://linux-hardware.org/?probe=c6975f2914) | Jun 07, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0732a60437](https://linux-hardware.org/?probe=0732a60437) | Jun 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [77b282aaaa](https://linux-hardware.org/?probe=77b282aaaa) | Jun 05, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [b320ea6050](https://linux-hardware.org/?probe=b320ea6050) | Jun 05, 2022 |
| MSI           | GP72 7QF                    | [ad0e85dbf9](https://linux-hardware.org/?probe=ad0e85dbf9) | Jun 05, 2022 |
| ASUSTek       | UX31E                       | [250825e17e](https://linux-hardware.org/?probe=250825e17e) | Jun 03, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [ac88b5f927](https://linux-hardware.org/?probe=ac88b5f927) | Jun 03, 2022 |
| HP            | ProBook 450 G7              | [010b492184](https://linux-hardware.org/?probe=010b492184) | May 31, 2022 |
| ASUSTek       | UX31E                       | [201add5732](https://linux-hardware.org/?probe=201add5732) | May 29, 2022 |
| HP            | Pavilion dv6                | [3623a980f8](https://linux-hardware.org/?probe=3623a980f8) | May 28, 2022 |
| HP            | EliteBook 8760w             | [b4066f49b0](https://linux-hardware.org/?probe=b4066f49b0) | May 25, 2022 |
| ASUSTek       | UX31E                       | [3905de150e](https://linux-hardware.org/?probe=3905de150e) | May 24, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [9f202f07cd](https://linux-hardware.org/?probe=9f202f07cd) | May 24, 2022 |
| Lenovo        | ThinkPad T420 42362L0       | [3aa17b879d](https://linux-hardware.org/?probe=3aa17b879d) | May 22, 2022 |
| Toshiba       | Satellite L10W-C            | [a66d178a46](https://linux-hardware.org/?probe=a66d178a46) | May 21, 2022 |
| ASUSTek       | UX31E                       | [12407852be](https://linux-hardware.org/?probe=12407852be) | May 21, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | [baed2325d7](https://linux-hardware.org/?probe=baed2325d7) | May 20, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [2320338e52](https://linux-hardware.org/?probe=2320338e52) | May 19, 2022 |
| Acer          | Swift SF314-52              | [4c199417ea](https://linux-hardware.org/?probe=4c199417ea) | May 19, 2022 |
| Acer          | Aspire 3100                 | [47e42883f4](https://linux-hardware.org/?probe=47e42883f4) | May 18, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [a49d97c9e6](https://linux-hardware.org/?probe=a49d97c9e6) | May 17, 2022 |
| Acer          | Swift SF314-52              | [a532101bbf](https://linux-hardware.org/?probe=a532101bbf) | May 17, 2022 |
| HP            | ProBook 455 G7              | [95daa19596](https://linux-hardware.org/?probe=95daa19596) | May 17, 2022 |
| HP            | ProBook 455 G7              | [a96c7163a5](https://linux-hardware.org/?probe=a96c7163a5) | May 17, 2022 |
| Dell          | Vostro 5568                 | [c7075dab69](https://linux-hardware.org/?probe=c7075dab69) | May 16, 2022 |
| ASUSTek       | X101CH                      | [544536b2d8](https://linux-hardware.org/?probe=544536b2d8) | May 16, 2022 |
| ASUSTek       | X101CH                      | [fbcf200ed5](https://linux-hardware.org/?probe=fbcf200ed5) | May 16, 2022 |
| ASUSTek       | X555LB                      | [2c2e8fcf67](https://linux-hardware.org/?probe=2c2e8fcf67) | May 15, 2022 |
| ASUSTek       | UX31E                       | [85613b8729](https://linux-hardware.org/?probe=85613b8729) | May 14, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [a3b1829dec](https://linux-hardware.org/?probe=a3b1829dec) | May 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [0b0ffcbfee](https://linux-hardware.org/?probe=0b0ffcbfee) | May 13, 2022 |
| ASUSTek       | UX31E                       | [b83f4f894e](https://linux-hardware.org/?probe=b83f4f894e) | May 13, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [ea75711bf8](https://linux-hardware.org/?probe=ea75711bf8) | May 12, 2022 |
| Chuwi         | MiniBook X                  | [541609a32e](https://linux-hardware.org/?probe=541609a32e) | May 12, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [52fa4973d5](https://linux-hardware.org/?probe=52fa4973d5) | May 10, 2022 |
| Lenovo        | ThinkPad T495s 20QJ0012U... | [2add3d77c6](https://linux-hardware.org/?probe=2add3d77c6) | May 09, 2022 |
| HP            | 255 G6 Notebook PC          | [a70f694f0b](https://linux-hardware.org/?probe=a70f694f0b) | May 09, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [badd8c8562](https://linux-hardware.org/?probe=badd8c8562) | May 09, 2022 |
| HP            | 255 G6 Notebook PC          | [73714bdb43](https://linux-hardware.org/?probe=73714bdb43) | May 05, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [dcff76e99c](https://linux-hardware.org/?probe=dcff76e99c) | May 02, 2022 |
| ASUSTek       | UX31E                       | [35c8958673](https://linux-hardware.org/?probe=35c8958673) | May 01, 2022 |
| Dell          | Latitude 3330               | [1843c62895](https://linux-hardware.org/?probe=1843c62895) | Apr 30, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [1ecbcb6b83](https://linux-hardware.org/?probe=1ecbcb6b83) | Apr 29, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [474e572043](https://linux-hardware.org/?probe=474e572043) | Apr 29, 2022 |
| ASUSTek       | UX31E                       | [8f165f54aa](https://linux-hardware.org/?probe=8f165f54aa) | Apr 29, 2022 |
| Lenovo        | ThinkPad T420 4180A21       | [6b5a6e89a2](https://linux-hardware.org/?probe=6b5a6e89a2) | Apr 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [a3ddc714b0](https://linux-hardware.org/?probe=a3ddc714b0) | Apr 28, 2022 |
| Acer          | Nitro AN515-45              | [aee7cca97f](https://linux-hardware.org/?probe=aee7cca97f) | Apr 28, 2022 |
| ASUSTek       | UX31E                       | [ef86b0396a](https://linux-hardware.org/?probe=ef86b0396a) | Apr 27, 2022 |
| Acer          | Aspire 5742G                | [313e7bcf23](https://linux-hardware.org/?probe=313e7bcf23) | Apr 27, 2022 |
| HP            | ZBook 17 G3                 | [133232a304](https://linux-hardware.org/?probe=133232a304) | Apr 26, 2022 |
| Dell          | Latitude 7390 2-in-1        | [8391ca514e](https://linux-hardware.org/?probe=8391ca514e) | Apr 23, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| Lenovo        | ThinkPad E15 20RD001EMC     | [d98ca42427](https://linux-hardware.org/?probe=d98ca42427) | Apr 20, 2022 |
| Dell          | Latitude 5480               | [811930e65e](https://linux-hardware.org/?probe=811930e65e) | Apr 20, 2022 |
| Lenovo        | B50-80 80EW                 | [2d1471986b](https://linux-hardware.org/?probe=2d1471986b) | Apr 19, 2022 |
| Acer          | Aspire V3-112P              | [c27219930e](https://linux-hardware.org/?probe=c27219930e) | Apr 17, 2022 |
| ASUSTek       | UX31E                       | [fa535559e0](https://linux-hardware.org/?probe=fa535559e0) | Apr 17, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [fccfb454e4](https://linux-hardware.org/?probe=fccfb454e4) | Apr 16, 2022 |
| Lenovo        | ThinkPad T400 6474AH2       | [f5e7108c33](https://linux-hardware.org/?probe=f5e7108c33) | Apr 15, 2022 |
| Lenovo        | E31-80 80MX                 | [ea96e85c49](https://linux-hardware.org/?probe=ea96e85c49) | Apr 14, 2022 |
| Lenovo        | B50-80 80EW                 | [d180d3831a](https://linux-hardware.org/?probe=d180d3831a) | Apr 10, 2022 |
| Acer          | TravelMate 4670             | [f5067e581b](https://linux-hardware.org/?probe=f5067e581b) | Apr 09, 2022 |
| ASUSTek       | UX31E                       | [7f4e9c9158](https://linux-hardware.org/?probe=7f4e9c9158) | Apr 09, 2022 |
| ASUSTek       | UX31E                       | [7249da837c](https://linux-hardware.org/?probe=7249da837c) | Apr 06, 2022 |
| Acer          | Extensa 5630                | [7ff131392d](https://linux-hardware.org/?probe=7ff131392d) | Apr 05, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [59eedbbc1b](https://linux-hardware.org/?probe=59eedbbc1b) | Apr 04, 2022 |
| Chuwi         | Hi10 Go                     | [cfa6610288](https://linux-hardware.org/?probe=cfa6610288) | Apr 04, 2022 |
| Dell          | XPS 15 9550                 | [487aa8af18](https://linux-hardware.org/?probe=487aa8af18) | Apr 03, 2022 |
| Acer          | Extensa 5630                | [4c6f7067bc](https://linux-hardware.org/?probe=4c6f7067bc) | Apr 02, 2022 |
| ASUSTek       | UX31E                       | [beb645df2c](https://linux-hardware.org/?probe=beb645df2c) | Apr 02, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [96e4eca691](https://linux-hardware.org/?probe=96e4eca691) | Apr 01, 2022 |
| ASUSTek       | UX31E                       | [54717b42d3](https://linux-hardware.org/?probe=54717b42d3) | Mar 31, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [e69dbda259](https://linux-hardware.org/?probe=e69dbda259) | Mar 31, 2022 |
| Acer          | Aspire E5-573G              | [39d3a3ac9d](https://linux-hardware.org/?probe=39d3a3ac9d) | Mar 30, 2022 |
| Acer          | Aspire P3-171               | [972861cbcc](https://linux-hardware.org/?probe=972861cbcc) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AWA07B0... | [4e67f54e53](https://linux-hardware.org/?probe=4e67f54e53) | Mar 29, 2022 |
| ASUSTek       | UX31E                       | [d83c6588f2](https://linux-hardware.org/?probe=d83c6588f2) | Mar 29, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [677a8dfae3](https://linux-hardware.org/?probe=677a8dfae3) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2f7a9a8ab0](https://linux-hardware.org/?probe=2f7a9a8ab0) | Mar 28, 2022 |
| ASUSTek       | ZenBook UX482EAR_UX482EA... | [649bc1b13a](https://linux-hardware.org/?probe=649bc1b13a) | Mar 28, 2022 |
| ASUSTek       | ZenBook UX482EAR_UX482EA... | [d1638977bc](https://linux-hardware.org/?probe=d1638977bc) | Mar 28, 2022 |
| ASUSTek       | UX31E                       | [67c079dd83](https://linux-hardware.org/?probe=67c079dd83) | Mar 28, 2022 |
| HP            | Compaq 615                  | [77439caf8f](https://linux-hardware.org/?probe=77439caf8f) | Mar 28, 2022 |
| ASUSTek       | UX31E                       | [582d76d560](https://linux-hardware.org/?probe=582d76d560) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| Acer          | Aspire 3000                 | [8f647a08f9](https://linux-hardware.org/?probe=8f647a08f9) | Mar 26, 2022 |
| ASUSTek       | UX31E                       | [6df7f8330c](https://linux-hardware.org/?probe=6df7f8330c) | Mar 25, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [c6ed527183](https://linux-hardware.org/?probe=c6ed527183) | Mar 25, 2022 |
| Lenovo        | ThinkPad X61s 7667CB5       | [05a3f6eba9](https://linux-hardware.org/?probe=05a3f6eba9) | Mar 25, 2022 |
| ASUSTek       | UX31E                       | [ad8feeb6a4](https://linux-hardware.org/?probe=ad8feeb6a4) | Mar 24, 2022 |
| HP            | Compaq 615                  | [c61f5e75c7](https://linux-hardware.org/?probe=c61f5e75c7) | Mar 24, 2022 |
| Dell          | Latitude E6430s             | [8ac18b3ae9](https://linux-hardware.org/?probe=8ac18b3ae9) | Mar 24, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [26443633b7](https://linux-hardware.org/?probe=26443633b7) | Mar 23, 2022 |
| ASUSTek       | UX31E                       | [3f268da44f](https://linux-hardware.org/?probe=3f268da44f) | Mar 22, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [9fb46d3913](https://linux-hardware.org/?probe=9fb46d3913) | Mar 22, 2022 |
| HP            | ProBook 450 G6              | [e8072f850f](https://linux-hardware.org/?probe=e8072f850f) | Mar 22, 2022 |
| ASUSTek       | UX31E                       | [86242fab56](https://linux-hardware.org/?probe=86242fab56) | Mar 21, 2022 |
| Acer          | Aspire E5-521               | [ad4ffeb6d5](https://linux-hardware.org/?probe=ad4ffeb6d5) | Mar 20, 2022 |
| Acer          | Aspire E5-521               | [7f37d7148d](https://linux-hardware.org/?probe=7f37d7148d) | Mar 20, 2022 |
| HP            | Pavilion Notebook 15-dp0... | [4824a016cc](https://linux-hardware.org/?probe=4824a016cc) | Mar 18, 2022 |
| HP            | Pavilion Notebook 15-dp0... | [847871aa63](https://linux-hardware.org/?probe=847871aa63) | Mar 17, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [12249482c6](https://linux-hardware.org/?probe=12249482c6) | Mar 17, 2022 |
| Dell          | Latitude E4200              | [7342f497b4](https://linux-hardware.org/?probe=7342f497b4) | Mar 16, 2022 |
| ASUSTek       | X550VXK                     | [9d51869d37](https://linux-hardware.org/?probe=9d51869d37) | Mar 15, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | [d627d6a6a0](https://linux-hardware.org/?probe=d627d6a6a0) | Mar 14, 2022 |
| ASUSTek       | UX31E                       | [620772c443](https://linux-hardware.org/?probe=620772c443) | Mar 11, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [1f4fadbe2e](https://linux-hardware.org/?probe=1f4fadbe2e) | Mar 11, 2022 |
| Acer          | Aspire 3100                 | [0429db8c01](https://linux-hardware.org/?probe=0429db8c01) | Mar 11, 2022 |
| HP            | Laptop 15-db0xxx            | [1064e67665](https://linux-hardware.org/?probe=1064e67665) | Mar 10, 2022 |
| Toshiba       | Satellite L750D             | [84ccdf8375](https://linux-hardware.org/?probe=84ccdf8375) | Mar 10, 2022 |
| ASUSTek       | UX31E                       | [62f3b41d12](https://linux-hardware.org/?probe=62f3b41d12) | Mar 09, 2022 |
| Acer          | TP-SW5-012-16UW             | [1558c31a17](https://linux-hardware.org/?probe=1558c31a17) | Mar 09, 2022 |
| Toshiba       | Satellite L750D             | [71d5919c2d](https://linux-hardware.org/?probe=71d5919c2d) | Mar 08, 2022 |
| ASUSTek       | UX31E                       | [889c1ad7d2](https://linux-hardware.org/?probe=889c1ad7d2) | Mar 07, 2022 |
| Acer          | Aspire 5349                 | [cd3380a8b4](https://linux-hardware.org/?probe=cd3380a8b4) | Mar 07, 2022 |
| Lenovo        | ThinkPad X250 20CM001XMC    | [3667f5b9e9](https://linux-hardware.org/?probe=3667f5b9e9) | Mar 07, 2022 |
| Acer          | Extensa 5620                | [3104016080](https://linux-hardware.org/?probe=3104016080) | Mar 06, 2022 |
| ASUSTek       | UX31E                       | [885cc74a20](https://linux-hardware.org/?probe=885cc74a20) | Mar 05, 2022 |
| HP            | ProBook 455 G7              | [311c6da8e0](https://linux-hardware.org/?probe=311c6da8e0) | Mar 05, 2022 |
| Dell          | Latitude E5470              | [1ef8a55ede](https://linux-hardware.org/?probe=1ef8a55ede) | Mar 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [3333e54277](https://linux-hardware.org/?probe=3333e54277) | Mar 04, 2022 |
| Dell          | Latitude 7520               | [023fba74f0](https://linux-hardware.org/?probe=023fba74f0) | Mar 04, 2022 |
| ASUSTek       | UX31E                       | [c4106a59b1](https://linux-hardware.org/?probe=c4106a59b1) | Mar 03, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | [6d96f7e645](https://linux-hardware.org/?probe=6d96f7e645) | Mar 02, 2022 |
| Lenovo        | ThinkPad X250 20CM001XMC    | [66cdff8786](https://linux-hardware.org/?probe=66cdff8786) | Mar 02, 2022 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | [21b4f724b8](https://linux-hardware.org/?probe=21b4f724b8) | Mar 02, 2022 |
| Dell          | Latitude 7520               | [d31adbbcad](https://linux-hardware.org/?probe=d31adbbcad) | Mar 02, 2022 |
| ASUSTek       | UX31E                       | [36ea5044b6](https://linux-hardware.org/?probe=36ea5044b6) | Feb 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [cab4f22396](https://linux-hardware.org/?probe=cab4f22396) | Feb 28, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [55773feeee](https://linux-hardware.org/?probe=55773feeee) | Feb 27, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [9ffeec636e](https://linux-hardware.org/?probe=9ffeec636e) | Feb 26, 2022 |
| ASUSTek       | UX31E                       | [477b323b68](https://linux-hardware.org/?probe=477b323b68) | Feb 25, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [4cb3686ee5](https://linux-hardware.org/?probe=4cb3686ee5) | Feb 24, 2022 |
| ASUSTek       | UX31E                       | [a6dae44349](https://linux-hardware.org/?probe=a6dae44349) | Feb 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [245600d3fd](https://linux-hardware.org/?probe=245600d3fd) | Feb 23, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [bedd29ee73](https://linux-hardware.org/?probe=bedd29ee73) | Feb 22, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [56496468de](https://linux-hardware.org/?probe=56496468de) | Feb 21, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [6cb1c24dd7](https://linux-hardware.org/?probe=6cb1c24dd7) | Feb 20, 2022 |
| ASUSTek       | X75A1                       | [232712babb](https://linux-hardware.org/?probe=232712babb) | Feb 19, 2022 |
| ASUSTek       | UX31E                       | [5651fbf2c8](https://linux-hardware.org/?probe=5651fbf2c8) | Feb 18, 2022 |
| Google        | Chell                       | [46b95ce3a4](https://linux-hardware.org/?probe=46b95ce3a4) | Feb 17, 2022 |
| Acer          | Aspire E5-573G              | [e162c17653](https://linux-hardware.org/?probe=e162c17653) | Feb 17, 2022 |
| Lenovo        | IdeaPad Z580                | [26e55e169b](https://linux-hardware.org/?probe=26e55e169b) | Feb 16, 2022 |
| Gigabyte      | GB-BSi7A-6500               | [9cfc09f66c](https://linux-hardware.org/?probe=9cfc09f66c) | Feb 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | [881b6c0f83](https://linux-hardware.org/?probe=881b6c0f83) | Feb 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [f199e025e3](https://linux-hardware.org/?probe=f199e025e3) | Feb 14, 2022 |
| Lenovo        | ThinkPad T480s 20L8S5JW0... | [df9633e08e](https://linux-hardware.org/?probe=df9633e08e) | Feb 13, 2022 |
| ASUSTek       | UX31E                       | [7b2a1e633f](https://linux-hardware.org/?probe=7b2a1e633f) | Feb 11, 2022 |
| Acer          | Swift SF314-43              | [b78e30f502](https://linux-hardware.org/?probe=b78e30f502) | Feb 11, 2022 |
| Dell          | Latitude 5480               | [eddd68780f](https://linux-hardware.org/?probe=eddd68780f) | Feb 09, 2022 |
| ASUSTek       | UX31E                       | [f70763fe0a](https://linux-hardware.org/?probe=f70763fe0a) | Feb 08, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [3fa68165ea](https://linux-hardware.org/?probe=3fa68165ea) | Feb 07, 2022 |
| ASUSTek       | UX31E                       | [4346690bc8](https://linux-hardware.org/?probe=4346690bc8) | Feb 06, 2022 |
| Acer          | Aspire SW3-016              | [6375ec93db](https://linux-hardware.org/?probe=6375ec93db) | Feb 05, 2022 |
| ASUSTek       | UX31E                       | [1eceff18e2](https://linux-hardware.org/?probe=1eceff18e2) | Feb 05, 2022 |
| HP            | ProBook 450 G3              | [7b28e44b0e](https://linux-hardware.org/?probe=7b28e44b0e) | Feb 05, 2022 |
| Lenovo        | G710 20252                  | [ffc1b2ca5a](https://linux-hardware.org/?probe=ffc1b2ca5a) | Feb 04, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [a19b0282f2](https://linux-hardware.org/?probe=a19b0282f2) | Feb 04, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | [9359d0a8af](https://linux-hardware.org/?probe=9359d0a8af) | Feb 04, 2022 |
| Lenovo        | G50-70 20351                | [c31d2c4893](https://linux-hardware.org/?probe=c31d2c4893) | Feb 04, 2022 |
| ASUSTek       | F5RL                        | [09497d2017](https://linux-hardware.org/?probe=09497d2017) | Feb 02, 2022 |
| ASUSTek       | F5RL                        | [77baf7aac1](https://linux-hardware.org/?probe=77baf7aac1) | Feb 02, 2022 |
| Lenovo        | ThinkPad T520 4243W4K       | [449f0842a4](https://linux-hardware.org/?probe=449f0842a4) | Feb 01, 2022 |
| Lenovo        | ThinkPad W530 2441B88       | [9c15c47f51](https://linux-hardware.org/?probe=9c15c47f51) | Feb 01, 2022 |
| Dell          | Latitude 7490               | [d3a6ac321f](https://linux-hardware.org/?probe=d3a6ac321f) | Jan 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [cd876e95b9](https://linux-hardware.org/?probe=cd876e95b9) | Jan 29, 2022 |
| ASUSTek       | X556UQ                      | [b9589b97a3](https://linux-hardware.org/?probe=b9589b97a3) | Jan 28, 2022 |
| HP            | ProBook 445 G7              | [a386252eaa](https://linux-hardware.org/?probe=a386252eaa) | Jan 28, 2022 |
| Unknown       | Unknown                     | [a6e928b122](https://linux-hardware.org/?probe=a6e928b122) | Jan 28, 2022 |
| Dell          | XPS 15 9560                 | [ee50dc0bb1](https://linux-hardware.org/?probe=ee50dc0bb1) | Jan 27, 2022 |
| ASUSTek       | K50ID                       | [fed48cd01d](https://linux-hardware.org/?probe=fed48cd01d) | Jan 27, 2022 |
| ASUSTek       | UX31E                       | [d6d51a7ce7](https://linux-hardware.org/?probe=d6d51a7ce7) | Jan 26, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [e932911cde](https://linux-hardware.org/?probe=e932911cde) | Jan 25, 2022 |
| Lenovo        | ThinkPad T590 20N5S7D300    | [3fcdce23b5](https://linux-hardware.org/?probe=3fcdce23b5) | Jan 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [e9c2ec480a](https://linux-hardware.org/?probe=e9c2ec480a) | Jan 24, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [ab4eb272cb](https://linux-hardware.org/?probe=ab4eb272cb) | Jan 24, 2022 |
| Acer          | NC-E1-572-54208G            | [02d40169ec](https://linux-hardware.org/?probe=02d40169ec) | Jan 23, 2022 |
| UMAX          | MediaBook 14                | [87cb50f680](https://linux-hardware.org/?probe=87cb50f680) | Jan 23, 2022 |
| ASUSTek       | UX31E                       | [c64e8bdde9](https://linux-hardware.org/?probe=c64e8bdde9) | Jan 22, 2022 |
| Lenovo        | ThinkPad X395 20NL000HMC    | [6c07e3f92a](https://linux-hardware.org/?probe=6c07e3f92a) | Jan 21, 2022 |
| ASUSTek       | UX31E                       | [08320d55cd](https://linux-hardware.org/?probe=08320d55cd) | Jan 21, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| Toshiba       | Satellite NB10t-A-103       | [e5d8911653](https://linux-hardware.org/?probe=e5d8911653) | Jan 19, 2022 |
| HP            | EliteBook 8570w             | [3f0a902b2e](https://linux-hardware.org/?probe=3f0a902b2e) | Jan 18, 2022 |
| HP            | EliteBook 8570w             | [0b31274785](https://linux-hardware.org/?probe=0b31274785) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [c76a20872b](https://linux-hardware.org/?probe=c76a20872b) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [11d1f56125](https://linux-hardware.org/?probe=11d1f56125) | Jan 18, 2022 |
| Dell          | Latitude 5420               | [dd45d8465d](https://linux-hardware.org/?probe=dd45d8465d) | Jan 17, 2022 |
| HP            | EliteBook 840 G6            | [c6b20915de](https://linux-hardware.org/?probe=c6b20915de) | Jan 17, 2022 |
| Notebook      | NS50MU                      | [8527a3e637](https://linux-hardware.org/?probe=8527a3e637) | Jan 16, 2022 |
| ASUSTek       | UX31E                       | [77c7eedd86](https://linux-hardware.org/?probe=77c7eedd86) | Jan 15, 2022 |
| Toshiba       | Satellite C55-A-19N         | [b53c0c9b39](https://linux-hardware.org/?probe=b53c0c9b39) | Jan 14, 2022 |
| Lenovo        | IdeaPad Z500 20202          | [ba41989095](https://linux-hardware.org/?probe=ba41989095) | Jan 14, 2022 |
| Toshiba       | Satellite NB10t-A-103       | [9111c65725](https://linux-hardware.org/?probe=9111c65725) | Jan 12, 2022 |
| HP            | ZBook 17 G2                 | [232d1f1cb4](https://linux-hardware.org/?probe=232d1f1cb4) | Jan 12, 2022 |
| HP            | Laptop 15s-eq0xxx           | [94d85b9f5b](https://linux-hardware.org/?probe=94d85b9f5b) | Jan 12, 2022 |
| Dell          | Inspiron 13 5310            | [f45f45197a](https://linux-hardware.org/?probe=f45f45197a) | Jan 11, 2022 |
| HP            | ProBook 6450b               | [73b06fa964](https://linux-hardware.org/?probe=73b06fa964) | Jan 10, 2022 |
| Lenovo        | ThinkPad E590 20NB001WMC    | [f114fe6200](https://linux-hardware.org/?probe=f114fe6200) | Jan 08, 2022 |
| Toshiba       | Satellite C55-A-1NU         | [208f411c99](https://linux-hardware.org/?probe=208f411c99) | Jan 08, 2022 |
| HP            | EliteBook 8540p             | [20b9948e89](https://linux-hardware.org/?probe=20b9948e89) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [13c6bafd04](https://linux-hardware.org/?probe=13c6bafd04) | Jan 08, 2022 |
| ASUSTek       | UX31E                       | [b976b5921e](https://linux-hardware.org/?probe=b976b5921e) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [e50bae67a6](https://linux-hardware.org/?probe=e50bae67a6) | Jan 08, 2022 |
| Lenovo        | Yoga 2 13 20344             | [581a4abb8e](https://linux-hardware.org/?probe=581a4abb8e) | Jan 08, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [945649c354](https://linux-hardware.org/?probe=945649c354) | Jan 07, 2022 |
| HP            | ProBook 4510s               | [50904e6b69](https://linux-hardware.org/?probe=50904e6b69) | Jan 06, 2022 |
| HP            | ProBook 4510s               | [cb983f7833](https://linux-hardware.org/?probe=cb983f7833) | Jan 06, 2022 |
| Dell          | Precision M4500             | [2504901038](https://linux-hardware.org/?probe=2504901038) | Jan 04, 2022 |
| Dell          | Latitude 3470               | [9e4742c283](https://linux-hardware.org/?probe=9e4742c283) | Jan 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [d774f42123](https://linux-hardware.org/?probe=d774f42123) | Jan 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7f5e49e07a](https://linux-hardware.org/?probe=7f5e49e07a) | Jan 04, 2022 |
| Dell          | Inspiron 5570               | [3e6d1befd6](https://linux-hardware.org/?probe=3e6d1befd6) | Jan 03, 2022 |
| Dell          | Latitude 7480               | [24244e5717](https://linux-hardware.org/?probe=24244e5717) | Jan 02, 2022 |
| Acer          | Swift SF114-34              | [94b665863b](https://linux-hardware.org/?probe=94b665863b) | Jan 02, 2022 |
| ASUSTek       | UX31E                       | [926c4f82d1](https://linux-hardware.org/?probe=926c4f82d1) | Jan 01, 2022 |
| HP            | EliteBook 820 G1            | [90deec9056](https://linux-hardware.org/?probe=90deec9056) | Dec 30, 2021 |
| Dell          | Inspiron 7559               | [12ba9454e7](https://linux-hardware.org/?probe=12ba9454e7) | Dec 29, 2021 |
| HP            | ProBook 4540s               | [20af449f2a](https://linux-hardware.org/?probe=20af449f2a) | Dec 29, 2021 |
| HP            | ProBook 4540s               | [99fb3303bb](https://linux-hardware.org/?probe=99fb3303bb) | Dec 29, 2021 |
| Acer          | Aspire ES1-571              | [ae601c56b8](https://linux-hardware.org/?probe=ae601c56b8) | Dec 28, 2021 |
| ASUSTek       | UX31E                       | [cd8cc790a0](https://linux-hardware.org/?probe=cd8cc790a0) | Dec 27, 2021 |
| HP            | Laptop 17-cp0xxx            | [596bdeff81](https://linux-hardware.org/?probe=596bdeff81) | Dec 27, 2021 |
| Lenovo        | ThinkPad X200 2024AY7       | [d3c8923c22](https://linux-hardware.org/?probe=d3c8923c22) | Dec 26, 2021 |
| HUAWEI        | HVY-WXX9                    | [2c33c2931e](https://linux-hardware.org/?probe=2c33c2931e) | Dec 26, 2021 |
| Lenovo        | G710 20252                  | [961341534c](https://linux-hardware.org/?probe=961341534c) | Dec 26, 2021 |
| Acer          | Swift SF315-41              | [92f264978e](https://linux-hardware.org/?probe=92f264978e) | Dec 25, 2021 |
| Acer          | Swift SF315-41              | [d94d38f29b](https://linux-hardware.org/?probe=d94d38f29b) | Dec 25, 2021 |
| ASUSTek       | X705NC                      | [c3cdc81bd8](https://linux-hardware.org/?probe=c3cdc81bd8) | Dec 25, 2021 |
| ASUSTek       | UX31E                       | [62488dea12](https://linux-hardware.org/?probe=62488dea12) | Dec 25, 2021 |
| Dell          | Latitude 5400               | [692bc521a6](https://linux-hardware.org/?probe=692bc521a6) | Dec 20, 2021 |
| Fujitsu Si... | AMILO PRO V8010             | [710a87fb41](https://linux-hardware.org/?probe=710a87fb41) | Dec 18, 2021 |
| HP            | EliteBook 850 G6            | [0f1c42ef5d](https://linux-hardware.org/?probe=0f1c42ef5d) | Dec 18, 2021 |
| ASUSTek       | UX31E                       | [8c6db8aa19](https://linux-hardware.org/?probe=8c6db8aa19) | Dec 17, 2021 |
| Acer          | Aspire A515-56              | [a50b285530](https://linux-hardware.org/?probe=a50b285530) | Dec 17, 2021 |
| Lenovo        | ThinkPad T440 20B7S1MW07    | [21baa9b1cc](https://linux-hardware.org/?probe=21baa9b1cc) | Dec 17, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [a0ec890791](https://linux-hardware.org/?probe=a0ec890791) | Dec 15, 2021 |
| ASUSTek       | X751LN                      | [f7489ee0ae](https://linux-hardware.org/?probe=f7489ee0ae) | Dec 15, 2021 |
| ASUSTek       | UX31E                       | [f5d5138937](https://linux-hardware.org/?probe=f5d5138937) | Dec 13, 2021 |
| HP            | EliteBook 840 G6            | [a20ecb525c](https://linux-hardware.org/?probe=a20ecb525c) | Dec 13, 2021 |
| Acer          | Aspire E5-721               | [53ab8f6179](https://linux-hardware.org/?probe=53ab8f6179) | Dec 12, 2021 |
| HP            | Laptop 14-cf0xxx            | [2f4ec869f9](https://linux-hardware.org/?probe=2f4ec869f9) | Dec 12, 2021 |
| ASUSTek       | UX31E                       | [d48bfc96ce](https://linux-hardware.org/?probe=d48bfc96ce) | Dec 12, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3030cb05b9](https://linux-hardware.org/?probe=3030cb05b9) | Dec 11, 2021 |
| Dell          | Latitude E4300              | [3dd32ae25d](https://linux-hardware.org/?probe=3dd32ae25d) | Dec 10, 2021 |
| Acer          | Extensa 5220                | [2572d3336d](https://linux-hardware.org/?probe=2572d3336d) | Dec 09, 2021 |
| Acer          | Extensa 5220                | [524256971b](https://linux-hardware.org/?probe=524256971b) | Dec 09, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [2694c27280](https://linux-hardware.org/?probe=2694c27280) | Dec 05, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [826435e568](https://linux-hardware.org/?probe=826435e568) | Dec 04, 2021 |
| ASUSTek       | UX31E                       | [04c3a4b6c7](https://linux-hardware.org/?probe=04c3a4b6c7) | Dec 03, 2021 |
| Lenovo        | G770 20089                  | [6a4de555a2](https://linux-hardware.org/?probe=6a4de555a2) | Dec 03, 2021 |
| UMAX          | VisionBook N15G Plus        | [4b16e8ea9d](https://linux-hardware.org/?probe=4b16e8ea9d) | Dec 03, 2021 |
| HP            | EliteBook 820 G2            | [03bb5ecc6a](https://linux-hardware.org/?probe=03bb5ecc6a) | Dec 03, 2021 |
| Google        | Akemi                       | [0867d0658c](https://linux-hardware.org/?probe=0867d0658c) | Dec 01, 2021 |
| Google        | Akemi                       | [2344df2c6b](https://linux-hardware.org/?probe=2344df2c6b) | Nov 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ae6614d6fb](https://linux-hardware.org/?probe=ae6614d6fb) | Nov 29, 2021 |
| ASUSTek       | UX31E                       | [0af8133ca3](https://linux-hardware.org/?probe=0af8133ca3) | Nov 29, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | [9dd7b3ad9b](https://linux-hardware.org/?probe=9dd7b3ad9b) | Nov 29, 2021 |
| Acer          | P4LJ0                       | [0f57f6b606](https://linux-hardware.org/?probe=0f57f6b606) | Nov 27, 2021 |
| HP            | ProBook 4540s               | [f047b9db0a](https://linux-hardware.org/?probe=f047b9db0a) | Nov 27, 2021 |
| HP            | ProBook 4540s               | [d8d17c1820](https://linux-hardware.org/?probe=d8d17c1820) | Nov 27, 2021 |
| Lenovo        | G780                        | [ffeaa607f9](https://linux-hardware.org/?probe=ffeaa607f9) | Nov 27, 2021 |
| Lenovo        | G780                        | [26ea5410e6](https://linux-hardware.org/?probe=26ea5410e6) | Nov 27, 2021 |
| Fujitsu       | LIFEBOOK T901               | [d9b8b1c304](https://linux-hardware.org/?probe=d9b8b1c304) | Nov 27, 2021 |
| ASUSTek       | X751LN                      | [2c8e1bfecd](https://linux-hardware.org/?probe=2c8e1bfecd) | Nov 25, 2021 |
| Dell          | Latitude E5470              | [1e35555998](https://linux-hardware.org/?probe=1e35555998) | Nov 24, 2021 |
| ASUSTek       | X751LN                      | [50d304e970](https://linux-hardware.org/?probe=50d304e970) | Nov 22, 2021 |
| Unknown       | Unknown                     | [81e2289408](https://linux-hardware.org/?probe=81e2289408) | Nov 21, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [6b2b37cfc2](https://linux-hardware.org/?probe=6b2b37cfc2) | Nov 20, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | [c174aa242d](https://linux-hardware.org/?probe=c174aa242d) | Nov 20, 2021 |
| HP            | OMEN by Laptop              | [0b8f3a5da9](https://linux-hardware.org/?probe=0b8f3a5da9) | Nov 19, 2021 |
| ASUSTek       | UX31E                       | [27fde62ce2](https://linux-hardware.org/?probe=27fde62ce2) | Nov 18, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [f3bf7b971f](https://linux-hardware.org/?probe=f3bf7b971f) | Nov 18, 2021 |
| HP            | ProBook 4510s               | [46c61312c4](https://linux-hardware.org/?probe=46c61312c4) | Nov 18, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | [66fd774069](https://linux-hardware.org/?probe=66fd774069) | Nov 17, 2021 |
| HP            | ProBook 4510s               | [cf53b2e2db](https://linux-hardware.org/?probe=cf53b2e2db) | Nov 17, 2021 |
| Fujitsu       | LIFEBOOK E754               | [9569f15e49](https://linux-hardware.org/?probe=9569f15e49) | Nov 16, 2021 |
| Dell          | Latitude E6420              | [71905152a8](https://linux-hardware.org/?probe=71905152a8) | Nov 14, 2021 |
| HP            | ProBook 455 G6              | [2a37f0ed64](https://linux-hardware.org/?probe=2a37f0ed64) | Nov 14, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [bf655cd438](https://linux-hardware.org/?probe=bf655cd438) | Nov 13, 2021 |
| HUAWEI        | HN-WX9X                     | [22c7f120ab](https://linux-hardware.org/?probe=22c7f120ab) | Nov 13, 2021 |
| Lenovo        | Yoga 500-15IBD 80N6         | [1fe63ecbee](https://linux-hardware.org/?probe=1fe63ecbee) | Nov 13, 2021 |
| HP            | ProBook 640 G1              | [72d5b9727b](https://linux-hardware.org/?probe=72d5b9727b) | Nov 12, 2021 |
| HP            | OMEN by Laptop              | [207d9a7985](https://linux-hardware.org/?probe=207d9a7985) | Nov 12, 2021 |
| HP            | Pavilion g6                 | [0332d112e9](https://linux-hardware.org/?probe=0332d112e9) | Nov 12, 2021 |
| HP            | ProBook 455 G6              | [6045aa2b3a](https://linux-hardware.org/?probe=6045aa2b3a) | Nov 12, 2021 |
| Dell          | Latitude E5440              | [310f365903](https://linux-hardware.org/?probe=310f365903) | Nov 10, 2021 |
| Timi          | A35                         | [f8818e4273](https://linux-hardware.org/?probe=f8818e4273) | Nov 10, 2021 |
| Lenovo        | ThinkPad Edge E431 62774... | [2af76d7459](https://linux-hardware.org/?probe=2af76d7459) | Nov 09, 2021 |
| HP            | Compaq nc6320 (RH374EA#A... | [a67ec35b48](https://linux-hardware.org/?probe=a67ec35b48) | Nov 08, 2021 |
| HP            | Pavilion dv6                | [12800ce664](https://linux-hardware.org/?probe=12800ce664) | Nov 06, 2021 |
| HP            | Pavilion dv6                | [9b00744856](https://linux-hardware.org/?probe=9b00744856) | Nov 06, 2021 |
| Dell          | XPS 15 9550                 | [1ae65e25ca](https://linux-hardware.org/?probe=1ae65e25ca) | Nov 06, 2021 |
| HP            | Compaq nc6320 (RH374EA#A... | [91c9beef79](https://linux-hardware.org/?probe=91c9beef79) | Nov 05, 2021 |
| Dell          | XPS 15 9550                 | [3cea241e9d](https://linux-hardware.org/?probe=3cea241e9d) | Nov 04, 2021 |
| ASUSTek       | X555BA                      | [99ef7179aa](https://linux-hardware.org/?probe=99ef7179aa) | Nov 04, 2021 |
| HP            | ProBook 650 G2              | [510bf1ba13](https://linux-hardware.org/?probe=510bf1ba13) | Nov 03, 2021 |
| HP            | OMEN by Laptop              | [d5eda0a4df](https://linux-hardware.org/?probe=d5eda0a4df) | Nov 01, 2021 |
| MSI           | GE76 Raider 11UG            | [cbbe604f22](https://linux-hardware.org/?probe=cbbe604f22) | Nov 01, 2021 |
| ASUSTek       | UX31E                       | [b089d44dc0](https://linux-hardware.org/?probe=b089d44dc0) | Nov 01, 2021 |
| Purism        | librem_15v4                 | [f3e5eba0c2](https://linux-hardware.org/?probe=f3e5eba0c2) | Oct 31, 2021 |
| Purism        | librem_15v4                 | [c74129a618](https://linux-hardware.org/?probe=c74129a618) | Oct 31, 2021 |
| HP            | OMEN by Laptop              | [d55ac505b9](https://linux-hardware.org/?probe=d55ac505b9) | Oct 31, 2021 |
| HP            | OMEN by Laptop              | [65a70acf15](https://linux-hardware.org/?probe=65a70acf15) | Oct 31, 2021 |
| ASUSTek       | F5RL                        | [7a2e7c66e9](https://linux-hardware.org/?probe=7a2e7c66e9) | Oct 31, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | [3802a77d98](https://linux-hardware.org/?probe=3802a77d98) | Oct 29, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [eadbbabab0](https://linux-hardware.org/?probe=eadbbabab0) | Oct 29, 2021 |
| Dell          | Latitude E7240              | [18213a2e29](https://linux-hardware.org/?probe=18213a2e29) | Oct 28, 2021 |
| Lenovo        | ThinkPad E590 20NB0018MC    | [3678e02e46](https://linux-hardware.org/?probe=3678e02e46) | Oct 27, 2021 |
| Lenovo        | ThinkPad E590 20NB0018MC    | [5a44640ff8](https://linux-hardware.org/?probe=5a44640ff8) | Oct 27, 2021 |
| Lenovo        | B50-80 80EW                 | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Sony          | VPCZ13M9E                   | [2d1739dc58](https://linux-hardware.org/?probe=2d1739dc58) | Oct 26, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [6105164e23](https://linux-hardware.org/?probe=6105164e23) | Oct 26, 2021 |
| ASUSTek       | UX31E                       | [62ce68edef](https://linux-hardware.org/?probe=62ce68edef) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Alienware     | 15                          | [5a84b0e8e8](https://linux-hardware.org/?probe=5a84b0e8e8) | Oct 25, 2021 |
| ASUSTek       | UX31E                       | [3783b25b2a](https://linux-hardware.org/?probe=3783b25b2a) | Oct 24, 2021 |
| Acer          | Aspire E5-721               | [0b2ec748f2](https://linux-hardware.org/?probe=0b2ec748f2) | Oct 23, 2021 |
| Acer          | Aspire E5-721               | [46ae1c3c30](https://linux-hardware.org/?probe=46ae1c3c30) | Oct 23, 2021 |
| Sony          | VPCZ13M9E                   | [d727cf6e00](https://linux-hardware.org/?probe=d727cf6e00) | Oct 23, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [fe4aa7e54d](https://linux-hardware.org/?probe=fe4aa7e54d) | Oct 23, 2021 |
| Sony          | VPCZ13M9E                   | [6ccc652e28](https://linux-hardware.org/?probe=6ccc652e28) | Oct 22, 2021 |
| Alienware     | 15                          | [8c4eaaa333](https://linux-hardware.org/?probe=8c4eaaa333) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5c95c74b6c](https://linux-hardware.org/?probe=5c95c74b6c) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f48a449c7a](https://linux-hardware.org/?probe=f48a449c7a) | Oct 21, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [63c9d05f24](https://linux-hardware.org/?probe=63c9d05f24) | Oct 20, 2021 |
| Dell          | Latitude 5400               | [8a880e6565](https://linux-hardware.org/?probe=8a880e6565) | Oct 19, 2021 |
| Dell          | Latitude 5400               | [0a94130eb2](https://linux-hardware.org/?probe=0a94130eb2) | Oct 19, 2021 |
| HP            | Laptop 15-bw0xx             | [f60949a3cc](https://linux-hardware.org/?probe=f60949a3cc) | Oct 18, 2021 |
| Sony          | VPCEB1E1E                   | [1473b3d2ca](https://linux-hardware.org/?probe=1473b3d2ca) | Oct 18, 2021 |
| Acer          | Aspire A515-51G             | [43bfef3bcd](https://linux-hardware.org/?probe=43bfef3bcd) | Oct 17, 2021 |
| Dell          | Latitude E5420              | [a1027f938f](https://linux-hardware.org/?probe=a1027f938f) | Oct 16, 2021 |
| Medion        | E7218                       | [cca261a107](https://linux-hardware.org/?probe=cca261a107) | Oct 16, 2021 |
| Dell          | XPS 13 9310                 | [f04cc5e7a8](https://linux-hardware.org/?probe=f04cc5e7a8) | Oct 15, 2021 |
| Dell          | XPS 13 9300                 | [22029905ac](https://linux-hardware.org/?probe=22029905ac) | Oct 15, 2021 |
| ASUSTek       | UX31E                       | [a20549b1ee](https://linux-hardware.org/?probe=a20549b1ee) | Oct 14, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [fb676e6e3f](https://linux-hardware.org/?probe=fb676e6e3f) | Oct 14, 2021 |
| Dell          | XPS 15 9550                 | [2269836aab](https://linux-hardware.org/?probe=2269836aab) | Oct 13, 2021 |
| HP            | EliteBook 8570w             | [b703149715](https://linux-hardware.org/?probe=b703149715) | Oct 13, 2021 |
| ASUSTek       | UX31E                       | [33cb7873b3](https://linux-hardware.org/?probe=33cb7873b3) | Oct 11, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [fd09df16d9](https://linux-hardware.org/?probe=fd09df16d9) | Oct 10, 2021 |
| Lenovo        | ThinkPad T570 20H90000MC    | [51c709d90c](https://linux-hardware.org/?probe=51c709d90c) | Oct 09, 2021 |
| HP            | Compaq 6530b (GW688AV)      | [13444fc399](https://linux-hardware.org/?probe=13444fc399) | Oct 08, 2021 |
| ASUSTek       | E502SA                      | [7034e6708d](https://linux-hardware.org/?probe=7034e6708d) | Oct 07, 2021 |
| MSI           | GL63 8RD                    | [9f55f25caf](https://linux-hardware.org/?probe=9f55f25caf) | Oct 07, 2021 |
| ASUSTek       | UX31E                       | [3d656a59f6](https://linux-hardware.org/?probe=3d656a59f6) | Oct 06, 2021 |
| ASUSTek       | UX31E                       | [b24ee374eb](https://linux-hardware.org/?probe=b24ee374eb) | Oct 04, 2021 |
| HP            | ProBook 455 G1              | [43115b1585](https://linux-hardware.org/?probe=43115b1585) | Oct 04, 2021 |
| Acer          | Aspire A114-32              | [153c60004b](https://linux-hardware.org/?probe=153c60004b) | Oct 03, 2021 |
| Acer          | Aspire A114-32              | [0c7f8d9bc1](https://linux-hardware.org/?probe=0c7f8d9bc1) | Oct 03, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [c3f376b088](https://linux-hardware.org/?probe=c3f376b088) | Oct 01, 2021 |
| ASUSTek       | UX31E                       | [634508203a](https://linux-hardware.org/?probe=634508203a) | Oct 01, 2021 |
| ASUSTek       | UX31E                       | [ae53a22db8](https://linux-hardware.org/?probe=ae53a22db8) | Sep 30, 2021 |
| ASUSTek       | E502SA                      | [7f17ddd3af](https://linux-hardware.org/?probe=7f17ddd3af) | Sep 30, 2021 |
| Acer          | Extensa 5235                | [aadc334520](https://linux-hardware.org/?probe=aadc334520) | Sep 29, 2021 |
| MSI           | GL72 6QD                    | [4a25280ba6](https://linux-hardware.org/?probe=4a25280ba6) | Sep 28, 2021 |
| ASUSTek       | UX31E                       | [1ce98669cc](https://linux-hardware.org/?probe=1ce98669cc) | Sep 27, 2021 |
| ASUSTek       | UX31E                       | [65594b31db](https://linux-hardware.org/?probe=65594b31db) | Sep 27, 2021 |
| Acer          | Aspire 5738                 | [3a72e534d3](https://linux-hardware.org/?probe=3a72e534d3) | Sep 26, 2021 |
| ASUSTek       | UX31E                       | [61a05f66ef](https://linux-hardware.org/?probe=61a05f66ef) | Sep 24, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [534a4c683f](https://linux-hardware.org/?probe=534a4c683f) | Sep 24, 2021 |
| ASUSTek       | 1015BXO                     | [0f2bd07e92](https://linux-hardware.org/?probe=0f2bd07e92) | Sep 23, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [28cec81520](https://linux-hardware.org/?probe=28cec81520) | Sep 22, 2021 |
| Dell          | XPS 15 7590                 | [7e0c5640af](https://linux-hardware.org/?probe=7e0c5640af) | Sep 21, 2021 |
| HP            | 255 G4                      | [3385bd5e87](https://linux-hardware.org/?probe=3385bd5e87) | Sep 20, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | [3c54753690](https://linux-hardware.org/?probe=3c54753690) | Sep 20, 2021 |
| ASUSTek       | UX31E                       | [02b242903b](https://linux-hardware.org/?probe=02b242903b) | Sep 20, 2021 |
| Acer          | Aspire 5738                 | [01bb66e2a1](https://linux-hardware.org/?probe=01bb66e2a1) | Sep 20, 2021 |
| Toshiba       | Satellite C850-19P          | [be0e0fc39c](https://linux-hardware.org/?probe=be0e0fc39c) | Sep 19, 2021 |
| ASUSTek       | N73SV                       | [4dae78bc6e](https://linux-hardware.org/?probe=4dae78bc6e) | Sep 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [caa2e90160](https://linux-hardware.org/?probe=caa2e90160) | Sep 18, 2021 |
| Lenovo        | B50-80 80EW                 | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| ASUSTek       | UX31E                       | [6d3c0cb595](https://linux-hardware.org/?probe=6d3c0cb595) | Sep 18, 2021 |
| ASUSTek       | UX31E                       | [4771fb2aab](https://linux-hardware.org/?probe=4771fb2aab) | Sep 17, 2021 |
| Lenovo        | B51-80 80LM                 | [320ab41cbb](https://linux-hardware.org/?probe=320ab41cbb) | Sep 17, 2021 |
| ASUSTek       | UX31E                       | [6c54ed5e3e](https://linux-hardware.org/?probe=6c54ed5e3e) | Sep 16, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [10c9991f0b](https://linux-hardware.org/?probe=10c9991f0b) | Sep 16, 2021 |
| ASUSTek       | UX31E                       | [aa60d02a7b](https://linux-hardware.org/?probe=aa60d02a7b) | Sep 15, 2021 |
| Dell          | Vostro 14 5410              | [8bd0f5b675](https://linux-hardware.org/?probe=8bd0f5b675) | Sep 15, 2021 |
| Dell          | Vostro 14 5410              | [e044b5770b](https://linux-hardware.org/?probe=e044b5770b) | Sep 15, 2021 |
| HP            | ProBook 455 G6              | [8c5aa4304c](https://linux-hardware.org/?probe=8c5aa4304c) | Sep 14, 2021 |
| HP            | ProBook 455 G6              | [49a26a21af](https://linux-hardware.org/?probe=49a26a21af) | Sep 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [b1c5ad62b3](https://linux-hardware.org/?probe=b1c5ad62b3) | Sep 13, 2021 |
| ASUSTek       | UX31E                       | [e1b27b035e](https://linux-hardware.org/?probe=e1b27b035e) | Sep 13, 2021 |
| Dell          | Latitude 5400               | [1fed0bdd29](https://linux-hardware.org/?probe=1fed0bdd29) | Sep 13, 2021 |
| ASUSTek       | UX303LA                     | [1a67d956de](https://linux-hardware.org/?probe=1a67d956de) | Sep 11, 2021 |
| Dell          | XPS 15 9550                 | [5ef10e99fc](https://linux-hardware.org/?probe=5ef10e99fc) | Sep 11, 2021 |
| Unknown       | Unknown                     | [bbf81cb33e](https://linux-hardware.org/?probe=bbf81cb33e) | Sep 10, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [53c03e65ce](https://linux-hardware.org/?probe=53c03e65ce) | Sep 09, 2021 |
| ASUSTek       | UX31E                       | [d137a3a584](https://linux-hardware.org/?probe=d137a3a584) | Sep 09, 2021 |
| ASUSTek       | UX31E                       | [4b97784aeb](https://linux-hardware.org/?probe=4b97784aeb) | Sep 08, 2021 |
| Dell          | Latitude 5511               | [75e4394ca1](https://linux-hardware.org/?probe=75e4394ca1) | Sep 07, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | [7d28c4a737](https://linux-hardware.org/?probe=7d28c4a737) | Sep 07, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | [c33f77f320](https://linux-hardware.org/?probe=c33f77f320) | Sep 07, 2021 |
| Lenovo        | B50-30 20382                | [f91b1f41fc](https://linux-hardware.org/?probe=f91b1f41fc) | Sep 06, 2021 |
| ASUSTek       | UX31E                       | [e0160c202c](https://linux-hardware.org/?probe=e0160c202c) | Sep 06, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [96642dc49d](https://linux-hardware.org/?probe=96642dc49d) | Sep 02, 2021 |
| HP            | Pavilion g6                 | [7f23204904](https://linux-hardware.org/?probe=7f23204904) | Sep 02, 2021 |
| ASUSTek       | UX31E                       | [36e2960d9e](https://linux-hardware.org/?probe=36e2960d9e) | Sep 01, 2021 |
| MSI           | GP72MVR 7RFX                | [8bf96cd534](https://linux-hardware.org/?probe=8bf96cd534) | Sep 01, 2021 |
| ASUSTek       | UX31E                       | [f8455be078](https://linux-hardware.org/?probe=f8455be078) | Aug 31, 2021 |
| ASUSTek       | UX31E                       | [715882de9a](https://linux-hardware.org/?probe=715882de9a) | Aug 30, 2021 |
| Dell          | Inspiron 14 5410            | [9ac57ec075](https://linux-hardware.org/?probe=9ac57ec075) | Aug 29, 2021 |
| Dell          | Inspiron 5570               | [47c81ea7a3](https://linux-hardware.org/?probe=47c81ea7a3) | Aug 28, 2021 |
| HP            | ProBook 450 G2              | [8228226f9b](https://linux-hardware.org/?probe=8228226f9b) | Aug 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [44d0412dd3](https://linux-hardware.org/?probe=44d0412dd3) | Aug 27, 2021 |
| ASUSTek       | UX31E                       | [a626915a9b](https://linux-hardware.org/?probe=a626915a9b) | Aug 27, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [b3185cd80d](https://linux-hardware.org/?probe=b3185cd80d) | Aug 26, 2021 |
| ASUSTek       | UX31E                       | [48a1496d43](https://linux-hardware.org/?probe=48a1496d43) | Aug 26, 2021 |
| HP            | Pavilion dv7                | [89e7202467](https://linux-hardware.org/?probe=89e7202467) | Aug 25, 2021 |
| HP            | ProBook 455 G7              | [56da4a55e4](https://linux-hardware.org/?probe=56da4a55e4) | Aug 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [42c87d7154](https://linux-hardware.org/?probe=42c87d7154) | Aug 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b773fc8716](https://linux-hardware.org/?probe=b773fc8716) | Aug 23, 2021 |
| HP            | 250 G6 Notebook PC          | [d0d5aa4d58](https://linux-hardware.org/?probe=d0d5aa4d58) | Aug 23, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [7e6371d41f](https://linux-hardware.org/?probe=7e6371d41f) | Aug 22, 2021 |
| ASUSTek       | UX31E                       | [f11d89cc89](https://linux-hardware.org/?probe=f11d89cc89) | Aug 21, 2021 |
| ASUSTek       | UX31E                       | [36beb5b173](https://linux-hardware.org/?probe=36beb5b173) | Aug 19, 2021 |
| Dell          | Latitude 7320               | [33536a85d3](https://linux-hardware.org/?probe=33536a85d3) | Aug 19, 2021 |
| ASUSTek       | X556UQK                     | [7306b98101](https://linux-hardware.org/?probe=7306b98101) | Aug 18, 2021 |
| ASUSTek       | UX31E                       | [0816a877bd](https://linux-hardware.org/?probe=0816a877bd) | Aug 18, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [4f0fc1bae7](https://linux-hardware.org/?probe=4f0fc1bae7) | Aug 18, 2021 |
| ASUSTek       | UX31E                       | [7b007be9fd](https://linux-hardware.org/?probe=7b007be9fd) | Aug 16, 2021 |
| ASUSTek       | UX31E                       | [f9243be85f](https://linux-hardware.org/?probe=f9243be85f) | Aug 16, 2021 |
| Acer          | Extensa 5630                | [29a71214dd](https://linux-hardware.org/?probe=29a71214dd) | Aug 15, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [465b8fec82](https://linux-hardware.org/?probe=465b8fec82) | Aug 15, 2021 |
| Lenovo        | B50-80 80EW                 | [bd70ed892a](https://linux-hardware.org/?probe=bd70ed892a) | Aug 14, 2021 |
| ASUSTek       | UX31E                       | [80cfc9b687](https://linux-hardware.org/?probe=80cfc9b687) | Aug 12, 2021 |
| Acer          | Extensa 5630                | [43a2f7646a](https://linux-hardware.org/?probe=43a2f7646a) | Aug 12, 2021 |
| Dell          | XPS 15 7590                 | [185cff6125](https://linux-hardware.org/?probe=185cff6125) | Aug 12, 2021 |
| ASUSTek       | X553SA                      | [58875de3c3](https://linux-hardware.org/?probe=58875de3c3) | Aug 12, 2021 |
| ASUSTek       | UX31E                       | [4651e027d9](https://linux-hardware.org/?probe=4651e027d9) | Aug 11, 2021 |
| Dell          | Latitude 5400               | [4f804f2046](https://linux-hardware.org/?probe=4f804f2046) | Aug 11, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [01e55d6021](https://linux-hardware.org/?probe=01e55d6021) | Aug 09, 2021 |
| ASUSTek       | UX31E                       | [28897c5b5f](https://linux-hardware.org/?probe=28897c5b5f) | Aug 09, 2021 |
| HP            | Pavilion g6                 | [a52650a605](https://linux-hardware.org/?probe=a52650a605) | Aug 09, 2021 |
| Dell          | XPS 15 9550                 | [17e8358196](https://linux-hardware.org/?probe=17e8358196) | Aug 08, 2021 |
| ASUSTek       | UX31E                       | [5c64722433](https://linux-hardware.org/?probe=5c64722433) | Aug 07, 2021 |
| ASUSTek       | UX31E                       | [88c691e7f1](https://linux-hardware.org/?probe=88c691e7f1) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [5953bc46ad](https://linux-hardware.org/?probe=5953bc46ad) | Aug 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [fafaeed466](https://linux-hardware.org/?probe=fafaeed466) | Aug 06, 2021 |
| Dell          | Latitude 7490               | [32c82c54b5](https://linux-hardware.org/?probe=32c82c54b5) | Aug 06, 2021 |
| HP            | Pavilion dv6500             | [983611f01f](https://linux-hardware.org/?probe=983611f01f) | Aug 05, 2021 |
| HP            | Pavilion dv6500             | [5e399cedc5](https://linux-hardware.org/?probe=5e399cedc5) | Aug 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [30131c51fb](https://linux-hardware.org/?probe=30131c51fb) | Aug 05, 2021 |
| ASUSTek       | UX31E                       | [1e458b84be](https://linux-hardware.org/?probe=1e458b84be) | Aug 04, 2021 |
| ASUSTek       | UX31E                       | [8951f246ed](https://linux-hardware.org/?probe=8951f246ed) | Aug 04, 2021 |
| ASUSTek       | G55VW                       | [9e7dc8e8cf](https://linux-hardware.org/?probe=9e7dc8e8cf) | Aug 03, 2021 |
| Acer          | Swift SF514-54GT            | [bbe1d82ec7](https://linux-hardware.org/?probe=bbe1d82ec7) | Aug 02, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [b16533813f](https://linux-hardware.org/?probe=b16533813f) | Jul 30, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [0e9fd822a6](https://linux-hardware.org/?probe=0e9fd822a6) | Jul 29, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [1d638fd7ae](https://linux-hardware.org/?probe=1d638fd7ae) | Jul 29, 2021 |
| ASUSTek       | UX31E                       | [44b0620279](https://linux-hardware.org/?probe=44b0620279) | Jul 29, 2021 |
| HP            | ZBook 15 G6                 | [617fd327a3](https://linux-hardware.org/?probe=617fd327a3) | Jul 28, 2021 |
| HP            | Laptop 15-da2xxx            | [b90f06f2eb](https://linux-hardware.org/?probe=b90f06f2eb) | Jul 28, 2021 |
| ASUSTek       | X556UQ                      | [9dee8d2c07](https://linux-hardware.org/?probe=9dee8d2c07) | Jul 27, 2021 |
| ASUSTek       | X556UQ                      | [88b38f3c6b](https://linux-hardware.org/?probe=88b38f3c6b) | Jul 26, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [cea7891e5a](https://linux-hardware.org/?probe=cea7891e5a) | Jul 26, 2021 |
| ASUSTek       | F5RL                        | [1ac5feaf25](https://linux-hardware.org/?probe=1ac5feaf25) | Jul 26, 2021 |
| ASUSTek       | F5RL                        | [3ca5d000c3](https://linux-hardware.org/?probe=3ca5d000c3) | Jul 26, 2021 |
| Dell          | Latitude E5520              | [0d74f57317](https://linux-hardware.org/?probe=0d74f57317) | Jul 25, 2021 |
| Dell          | Latitude E5520              | [5866765bab](https://linux-hardware.org/?probe=5866765bab) | Jul 25, 2021 |
| Lenovo        | ThinkPad X220 429137G       | [ab41516068](https://linux-hardware.org/?probe=ab41516068) | Jul 25, 2021 |
| Acer          | Aspire V3-111P              | [e3aca6b408](https://linux-hardware.org/?probe=e3aca6b408) | Jul 24, 2021 |
| Acer          | Swift SF514-55GT            | [bb95e7c75b](https://linux-hardware.org/?probe=bb95e7c75b) | Jul 24, 2021 |
| Lenovo        | ThinkPad E495 20NE000BMC    | [487f5a67bf](https://linux-hardware.org/?probe=487f5a67bf) | Jul 24, 2021 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | [72cbbe92a0](https://linux-hardware.org/?probe=72cbbe92a0) | Jul 22, 2021 |
| HP            | EliteBook 850 G6            | [d0a8afe992](https://linux-hardware.org/?probe=d0a8afe992) | Jul 20, 2021 |
| Sony          | VPCEB1E1E                   | [b57d8d169b](https://linux-hardware.org/?probe=b57d8d169b) | Jul 20, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | [db3e0c8073](https://linux-hardware.org/?probe=db3e0c8073) | Jul 17, 2021 |
| Dell          | XPS 15 9550                 | [594fbbbb38](https://linux-hardware.org/?probe=594fbbbb38) | Jul 17, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | [4b6bb5e980](https://linux-hardware.org/?probe=4b6bb5e980) | Jul 16, 2021 |
| Dell          | Vostro 5515                 | [f4ae054fc8](https://linux-hardware.org/?probe=f4ae054fc8) | Jul 15, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [d67f028892](https://linux-hardware.org/?probe=d67f028892) | Jul 15, 2021 |
| Toshiba       | Satellite L850              | [1697c7eaf6](https://linux-hardware.org/?probe=1697c7eaf6) | Jul 15, 2021 |
| Lenovo        | 0769BLG                     | [2d8e74d05c](https://linux-hardware.org/?probe=2d8e74d05c) | Jul 15, 2021 |
| Lenovo        | ThinkPad W540 20BHS2LM02    | [6d00312e5e](https://linux-hardware.org/?probe=6d00312e5e) | Jul 12, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [96f87991b2](https://linux-hardware.org/?probe=96f87991b2) | Jul 12, 2021 |
| HP            | Compaq 6730b (GB988EA)      | [ca4426ce30](https://linux-hardware.org/?probe=ca4426ce30) | Jul 11, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [eb84cf8198](https://linux-hardware.org/?probe=eb84cf8198) | Jul 10, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [1cb0058b88](https://linux-hardware.org/?probe=1cb0058b88) | Jul 10, 2021 |
| HP            | EliteBook 840 G3            | [950a407dff](https://linux-hardware.org/?probe=950a407dff) | Jul 08, 2021 |
| Lenovo        | ThinkPad T590 20N5S2NC1V    | [048e092d2f](https://linux-hardware.org/?probe=048e092d2f) | Jul 08, 2021 |
| Apple         | MacBookAir7,2               | [a88a1df2f5](https://linux-hardware.org/?probe=a88a1df2f5) | Jul 07, 2021 |
| Apple         | MacBookAir7,2               | [77f6869d84](https://linux-hardware.org/?probe=77f6869d84) | Jul 07, 2021 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [dcad6f0184](https://linux-hardware.org/?probe=dcad6f0184) | Jul 06, 2021 |
| Packard Be... | EasyNote LS11HR             | [09dbdc286a](https://linux-hardware.org/?probe=09dbdc286a) | Jul 05, 2021 |
| HP            | Pavilion dv7                | [43afdddf0e](https://linux-hardware.org/?probe=43afdddf0e) | Jul 04, 2021 |
| HP            | EliteBook 850 G6            | [27b614c70e](https://linux-hardware.org/?probe=27b614c70e) | Jul 04, 2021 |
| HP            | ProBook 4720s               | [2112bd8af0](https://linux-hardware.org/?probe=2112bd8af0) | Jul 03, 2021 |
| HP            | ProBook 4720s               | [f6be4a39bb](https://linux-hardware.org/?probe=f6be4a39bb) | Jul 03, 2021 |
| Dell          | Latitude E6400              | [18d5b00f71](https://linux-hardware.org/?probe=18d5b00f71) | Jul 03, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [6e5f031c7a](https://linux-hardware.org/?probe=6e5f031c7a) | Jul 03, 2021 |
| HP            | Pavilion x2 Detachable P... | [d917cdea53](https://linux-hardware.org/?probe=d917cdea53) | Jul 02, 2021 |
| Dell          | Latitude E6430              | [43100da49e](https://linux-hardware.org/?probe=43100da49e) | Jul 02, 2021 |
| Dell          | Inspiron 1750               | [2ff81df67a](https://linux-hardware.org/?probe=2ff81df67a) | Jul 02, 2021 |
| Acer          | E1-510                      | [74ed9018a7](https://linux-hardware.org/?probe=74ed9018a7) | Jul 02, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [c19ad895a0](https://linux-hardware.org/?probe=c19ad895a0) | Jul 02, 2021 |
| Acer          | E1-510                      | [1f5fc816d2](https://linux-hardware.org/?probe=1f5fc816d2) | Jul 02, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [0260c559c1](https://linux-hardware.org/?probe=0260c559c1) | Jul 02, 2021 |
| HP            | Laptop 15s-eq0xxx           | [ee813e9b02](https://linux-hardware.org/?probe=ee813e9b02) | Jul 02, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [d26e9b673d](https://linux-hardware.org/?probe=d26e9b673d) | Jul 01, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [858ab16aee](https://linux-hardware.org/?probe=858ab16aee) | Jun 29, 2021 |
| Unknown       | Unknown                     | [4d4040c7bd](https://linux-hardware.org/?probe=4d4040c7bd) | Jun 27, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [b1f8b4df82](https://linux-hardware.org/?probe=b1f8b4df82) | Jun 25, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | [e1fe98a9de](https://linux-hardware.org/?probe=e1fe98a9de) | Jun 23, 2021 |
| Lenovo        | V330-15IKB 81AX             | [e6e76d81ec](https://linux-hardware.org/?probe=e6e76d81ec) | Jun 19, 2021 |
| Acer          | Nitro AN515-54              | [cf48431ab4](https://linux-hardware.org/?probe=cf48431ab4) | Jun 18, 2021 |
| Acer          | Nitro AN515-54              | [0db05d1420](https://linux-hardware.org/?probe=0db05d1420) | Jun 18, 2021 |
| Dell          | XPS 15 9550                 | [8c980bf3ca](https://linux-hardware.org/?probe=8c980bf3ca) | Jun 17, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | [4134764afd](https://linux-hardware.org/?probe=4134764afd) | Jun 09, 2021 |
| Dell          | XPS 15 7590                 | [03514539b0](https://linux-hardware.org/?probe=03514539b0) | Jun 09, 2021 |
| HP            | Pavilion dv5                | [a3ec72db59](https://linux-hardware.org/?probe=a3ec72db59) | Jun 08, 2021 |
| Dell          | Latitude E5510              | [648d4a58e1](https://linux-hardware.org/?probe=648d4a58e1) | Jun 06, 2021 |
| ASUSTek       | X55U                        | [4a44c680de](https://linux-hardware.org/?probe=4a44c680de) | Jun 05, 2021 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | [da76c3ea04](https://linux-hardware.org/?probe=da76c3ea04) | Jun 05, 2021 |
| HP            | Pavilion g6                 | [ca0eb881c4](https://linux-hardware.org/?probe=ca0eb881c4) | Jun 04, 2021 |
| HP            | Pavilion g6                 | [1bbb6d6e34](https://linux-hardware.org/?probe=1bbb6d6e34) | Jun 03, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [e50e7e65b4](https://linux-hardware.org/?probe=e50e7e65b4) | May 28, 2021 |
| Insyde        | Braswell                    | [cedca78b3a](https://linux-hardware.org/?probe=cedca78b3a) | May 28, 2021 |
| HP            | ProBook 455 G7              | [fc1870a101](https://linux-hardware.org/?probe=fc1870a101) | May 28, 2021 |
| HP            | ProBook 455 G7              | [75f763a124](https://linux-hardware.org/?probe=75f763a124) | May 28, 2021 |
| HP            | Pavilion dv7                | [91d0ba53c9](https://linux-hardware.org/?probe=91d0ba53c9) | May 28, 2021 |
| ASUSTek       | K53SV                       | [a8fd68fccc](https://linux-hardware.org/?probe=a8fd68fccc) | May 26, 2021 |
| Dell          | G5 5587                     | [65c1600593](https://linux-hardware.org/?probe=65c1600593) | May 24, 2021 |
| Dell          | Latitude 7420               | [38380cec21](https://linux-hardware.org/?probe=38380cec21) | May 22, 2021 |
| Dell          | Latitude 5511               | [6fdc31e1e9](https://linux-hardware.org/?probe=6fdc31e1e9) | May 21, 2021 |
| MSI           | GE72 7RE                    | [a6a5258971](https://linux-hardware.org/?probe=a6a5258971) | May 20, 2021 |
| Lenovo        | V130-15IKB 81HN             | [3630dfb215](https://linux-hardware.org/?probe=3630dfb215) | May 17, 2021 |
| HP            | ProBook 450 G7              | [cbde33b709](https://linux-hardware.org/?probe=cbde33b709) | May 16, 2021 |
| HP            | ProBook 4520s (WT121EA)     | [af5a9f1662](https://linux-hardware.org/?probe=af5a9f1662) | May 15, 2021 |
| HP            | ProBook 455 G7              | [faeed14705](https://linux-hardware.org/?probe=faeed14705) | May 15, 2021 |
| HP            | ProBook 455 G7              | [5a9153e5cc](https://linux-hardware.org/?probe=5a9153e5cc) | May 14, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | [33069aaebb](https://linux-hardware.org/?probe=33069aaebb) | May 12, 2021 |
| Unknown       | Unknown                     | [a54c655ae8](https://linux-hardware.org/?probe=a54c655ae8) | May 12, 2021 |
| Unknown       | Unknown                     | [e6eed05cc3](https://linux-hardware.org/?probe=e6eed05cc3) | May 12, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [ec0cb83241](https://linux-hardware.org/?probe=ec0cb83241) | May 10, 2021 |
| Acer          | Aspire VN7-591G             | [bc9e6c4910](https://linux-hardware.org/?probe=bc9e6c4910) | May 10, 2021 |
| Acer          | Aspire 5740                 | [ed5c778d4f](https://linux-hardware.org/?probe=ed5c778d4f) | May 09, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [75431661e3](https://linux-hardware.org/?probe=75431661e3) | May 08, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ffaf24e2ab](https://linux-hardware.org/?probe=ffaf24e2ab) | May 06, 2021 |
| ASUSTek       | T100TA                      | [61c9e8ca48](https://linux-hardware.org/?probe=61c9e8ca48) | May 05, 2021 |
| Lenovo        | B70-80 80MR                 | [17bea3da43](https://linux-hardware.org/?probe=17bea3da43) | May 04, 2021 |
| ASUSTek       | UX31E                       | [4acf6ce595](https://linux-hardware.org/?probe=4acf6ce595) | May 04, 2021 |
| ASUSTek       | X540SA                      | [0f79fb429b](https://linux-hardware.org/?probe=0f79fb429b) | May 02, 2021 |
| Dell          | Vostro 3350                 | [9f2372a38c](https://linux-hardware.org/?probe=9f2372a38c) | May 02, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [1707ff6faf](https://linux-hardware.org/?probe=1707ff6faf) | May 02, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [36cd5135b6](https://linux-hardware.org/?probe=36cd5135b6) | May 02, 2021 |
| Sony          | VGN-FW31J                   | [87da15d562](https://linux-hardware.org/?probe=87da15d562) | May 01, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [184bedf2fd](https://linux-hardware.org/?probe=184bedf2fd) | May 01, 2021 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [a6afe0cc34](https://linux-hardware.org/?probe=a6afe0cc34) | May 01, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [0790e842a9](https://linux-hardware.org/?probe=0790e842a9) | May 01, 2021 |
| Dell          | Latitude 5401               | [cd8363b187](https://linux-hardware.org/?probe=cd8363b187) | Apr 27, 2021 |
| Lenovo        | ThinkPad T430 23501F9       | [d855b9bf0f](https://linux-hardware.org/?probe=d855b9bf0f) | Apr 26, 2021 |
| HP            | EliteBook 840 G5            | [266fb405d7](https://linux-hardware.org/?probe=266fb405d7) | Apr 26, 2021 |
| Acer          | TravelMate 6460             | [287952fb68](https://linux-hardware.org/?probe=287952fb68) | Apr 24, 2021 |
| Lenovo        | ThinkPad R500 2714AAG       | [0f62cca304](https://linux-hardware.org/?probe=0f62cca304) | Apr 20, 2021 |
| ASUSTek       | F5SL                        | [e1a84e3bdf](https://linux-hardware.org/?probe=e1a84e3bdf) | Apr 17, 2021 |
| HP            | ProBook 450 G7              | [45189929cc](https://linux-hardware.org/?probe=45189929cc) | Apr 17, 2021 |
| HP            | ProBook 635 Aero G7 Note... | [4cc6403330](https://linux-hardware.org/?probe=4cc6403330) | Apr 15, 2021 |
| ASUSTek       | N73JQ                       | [29398a5494](https://linux-hardware.org/?probe=29398a5494) | Apr 15, 2021 |
| Dell          | XPS 13 9360                 | [4b5e9623a8](https://linux-hardware.org/?probe=4b5e9623a8) | Apr 13, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | [538618720c](https://linux-hardware.org/?probe=538618720c) | Apr 11, 2021 |
| HP            | ProBook 4530s               | [6b62bad9ad](https://linux-hardware.org/?probe=6b62bad9ad) | Apr 11, 2021 |
| HP            | Notebook                    | [b50b4aa14f](https://linux-hardware.org/?probe=b50b4aa14f) | Apr 11, 2021 |
| HP            | EliteBook 850 G5            | [8351e652e0](https://linux-hardware.org/?probe=8351e652e0) | Apr 11, 2021 |
| ASUSTek       | UX31E                       | [22901fcbc7](https://linux-hardware.org/?probe=22901fcbc7) | Apr 11, 2021 |
| HP            | EliteBook 850 G5            | [71a5cf1e09](https://linux-hardware.org/?probe=71a5cf1e09) | Apr 11, 2021 |
| Fujitsu       | LIFEBOOK E5510              | [034e192416](https://linux-hardware.org/?probe=034e192416) | Apr 11, 2021 |
| Dell          | Inspiron 3501               | [cc2dcd8258](https://linux-hardware.org/?probe=cc2dcd8258) | Apr 10, 2021 |
| Sony          | VPCEB1E1E                   | [d73e70bc03](https://linux-hardware.org/?probe=d73e70bc03) | Apr 10, 2021 |
| Toshiba       | Unknown                     | [0c98d143f2](https://linux-hardware.org/?probe=0c98d143f2) | Apr 09, 2021 |
| Dell          | Inspiron 5593               | [f41c784317](https://linux-hardware.org/?probe=f41c784317) | Apr 09, 2021 |
| Lenovo        | ThinkPad T490 20N20009MC    | [4e38c1e886](https://linux-hardware.org/?probe=4e38c1e886) | Apr 09, 2021 |
| Lenovo        | Yoga 300-11IBY 80M0         | [a1481ccf2a](https://linux-hardware.org/?probe=a1481ccf2a) | Apr 07, 2021 |
| Dell          | Inspiron 7348               | [bd1d84d6e7](https://linux-hardware.org/?probe=bd1d84d6e7) | Apr 07, 2021 |
| Lenovo        | ThinkPad E495 20NEA001GE    | [c7a893da2e](https://linux-hardware.org/?probe=c7a893da2e) | Apr 06, 2021 |
| Lenovo        | ThinkPad T490 20N20009MC    | [c40cb2c60f](https://linux-hardware.org/?probe=c40cb2c60f) | Apr 06, 2021 |
| Dell          | Precision 5530              | [64ca23f74b](https://linux-hardware.org/?probe=64ca23f74b) | Apr 06, 2021 |
| Toshiba       | Satellite L300D             | [35514af81d](https://linux-hardware.org/?probe=35514af81d) | Apr 04, 2021 |
| Dell          | Inspiron 5593               | [bf647eb6cd](https://linux-hardware.org/?probe=bf647eb6cd) | Apr 03, 2021 |
| Dell          | Inspiron N5110              | [6fe414f2da](https://linux-hardware.org/?probe=6fe414f2da) | Apr 02, 2021 |
| Acer          | Aspire A515-54G             | [4ceb1f2a16](https://linux-hardware.org/?probe=4ceb1f2a16) | Mar 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [fc6346c32b](https://linux-hardware.org/?probe=fc6346c32b) | Mar 29, 2021 |
| Dell          | Latitude 3400               | [e1cab5dc75](https://linux-hardware.org/?probe=e1cab5dc75) | Mar 29, 2021 |
| Lenovo        | B71-80 80RJ                 | [178235fdc8](https://linux-hardware.org/?probe=178235fdc8) | Mar 28, 2021 |
| HP            | EliteBook 850 G5            | [889d834138](https://linux-hardware.org/?probe=889d834138) | Mar 26, 2021 |
| HP            | 250 G2                      | [54d0d70b5f](https://linux-hardware.org/?probe=54d0d70b5f) | Mar 24, 2021 |
| Dell          | Inspiron 5570               | [4faf6a3407](https://linux-hardware.org/?probe=4faf6a3407) | Mar 23, 2021 |
| HP            | EliteBook 8530p             | [7ee41a2d5d](https://linux-hardware.org/?probe=7ee41a2d5d) | Mar 23, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [e4bd78422e](https://linux-hardware.org/?probe=e4bd78422e) | Mar 22, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [c99d44a48e](https://linux-hardware.org/?probe=c99d44a48e) | Mar 21, 2021 |
| ASUSTek       | X555LD                      | [cf0c496200](https://linux-hardware.org/?probe=cf0c496200) | Mar 20, 2021 |
| Dell          | Latitude E6400              | [ae7a7ffce1](https://linux-hardware.org/?probe=ae7a7ffce1) | Mar 19, 2021 |
| HP            | 250 G6 Notebook PC          | [240e99298f](https://linux-hardware.org/?probe=240e99298f) | Mar 17, 2021 |
| Dell          | Latitude E6420              | [e7f5f57404](https://linux-hardware.org/?probe=e7f5f57404) | Mar 17, 2021 |
| Clevo         | W250ENQ / W270ENQ           | [aad8ca4f6f](https://linux-hardware.org/?probe=aad8ca4f6f) | Mar 17, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [9f125de705](https://linux-hardware.org/?probe=9f125de705) | Mar 16, 2021 |
| Dell          | Latitude 5411               | [e992a2c9e6](https://linux-hardware.org/?probe=e992a2c9e6) | Mar 16, 2021 |
| HP            | ProBook 455 G7              | [c8bdece188](https://linux-hardware.org/?probe=c8bdece188) | Mar 15, 2021 |
| HP            | EliteBook 2570p             | [0072a02a5d](https://linux-hardware.org/?probe=0072a02a5d) | Mar 14, 2021 |
| Lenovo        | ThinkPad T400 6475R1G       | [9a6cc50c52](https://linux-hardware.org/?probe=9a6cc50c52) | Mar 13, 2021 |
| HP            | Pavilion dv6                | [65c8aaa5aa](https://linux-hardware.org/?probe=65c8aaa5aa) | Mar 13, 2021 |
| HP            | Pavilion dv6                | [5eed23aaf7](https://linux-hardware.org/?probe=5eed23aaf7) | Mar 13, 2021 |
| Lenovo        | G500 20236                  | [453b938647](https://linux-hardware.org/?probe=453b938647) | Mar 13, 2021 |
| HP            | 250 G6 Notebook PC          | [ecb1d8ee1d](https://linux-hardware.org/?probe=ecb1d8ee1d) | Mar 11, 2021 |
| Fujitsu Si... | AMILO Li 2727               | [fc3b7d2f2b](https://linux-hardware.org/?probe=fc3b7d2f2b) | Mar 10, 2021 |
| Fujitsu Si... | AMILO Li 2727               | [b1a4fc67b5](https://linux-hardware.org/?probe=b1a4fc67b5) | Mar 10, 2021 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | [da00de06ed](https://linux-hardware.org/?probe=da00de06ed) | Mar 10, 2021 |
| HP            | EliteBook 2170p             | [dc06698753](https://linux-hardware.org/?probe=dc06698753) | Mar 10, 2021 |
| ASUSTek       | UX51VZA                     | [14ae24e6d8](https://linux-hardware.org/?probe=14ae24e6d8) | Mar 07, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [590b33fc27](https://linux-hardware.org/?probe=590b33fc27) | Mar 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [094e63ef62](https://linux-hardware.org/?probe=094e63ef62) | Mar 06, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [fb0bf9134c](https://linux-hardware.org/?probe=fb0bf9134c) | Mar 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [192f0fd756](https://linux-hardware.org/?probe=192f0fd756) | Mar 05, 2021 |
| Dell          | XPS 13 9300                 | [c4265bb6c4](https://linux-hardware.org/?probe=c4265bb6c4) | Mar 04, 2021 |
| Lenovo        | Flex 2 Pro-15 80FL          | [8e5ead087c](https://linux-hardware.org/?probe=8e5ead087c) | Mar 04, 2021 |
| Toshiba       | Satellite L740              | [91b7d3fb4d](https://linux-hardware.org/?probe=91b7d3fb4d) | Mar 02, 2021 |
| HP            | ProBook 470 G4              | [c3d85c83ec](https://linux-hardware.org/?probe=c3d85c83ec) | Feb 28, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [675be05d71](https://linux-hardware.org/?probe=675be05d71) | Feb 27, 2021 |
| Dell          | Latitude E6230              | [c3772d78aa](https://linux-hardware.org/?probe=c3772d78aa) | Feb 26, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [5dcdaebb4e](https://linux-hardware.org/?probe=5dcdaebb4e) | Feb 26, 2021 |
| Dell          | Latitude E6410              | [6f3fa9e9f2](https://linux-hardware.org/?probe=6f3fa9e9f2) | Feb 26, 2021 |
| HP            | ProBook 4540s               | [9ab78f21ad](https://linux-hardware.org/?probe=9ab78f21ad) | Feb 26, 2021 |
| HP            | ProBook 4540s               | [dd4d88de48](https://linux-hardware.org/?probe=dd4d88de48) | Feb 26, 2021 |
| ASUSTek       | X555LD                      | [665cf4701a](https://linux-hardware.org/?probe=665cf4701a) | Feb 25, 2021 |
| ASUSTek       | M50Vc                       | [8abf85e052](https://linux-hardware.org/?probe=8abf85e052) | Feb 24, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [58d3bac346](https://linux-hardware.org/?probe=58d3bac346) | Feb 24, 2021 |
| ASUSTek       | X751SJ                      | [81295695f3](https://linux-hardware.org/?probe=81295695f3) | Feb 24, 2021 |
| Lenovo        | IdeaPad Z580                | [9cd18dc0e4](https://linux-hardware.org/?probe=9cd18dc0e4) | Feb 24, 2021 |
| ASUSTek       | M50Vc                       | [3a9a5e9b7c](https://linux-hardware.org/?probe=3a9a5e9b7c) | Feb 24, 2021 |
| ASUSTek       | M50Vc                       | [295654ca20](https://linux-hardware.org/?probe=295654ca20) | Feb 24, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [f1d7117dc7](https://linux-hardware.org/?probe=f1d7117dc7) | Feb 23, 2021 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [9d65892538](https://linux-hardware.org/?probe=9d65892538) | Feb 22, 2021 |
| Dell          | G5 5587                     | [0b0fc3b694](https://linux-hardware.org/?probe=0b0fc3b694) | Feb 22, 2021 |
| Lenovo        | ThinkPad T490 20N2000CMC    | [b23d98dd6a](https://linux-hardware.org/?probe=b23d98dd6a) | Feb 22, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [db101fb87e](https://linux-hardware.org/?probe=db101fb87e) | Feb 21, 2021 |
| ASUSTek       | K55VM                       | [7e11b6bd85](https://linux-hardware.org/?probe=7e11b6bd85) | Feb 20, 2021 |
| HP            | EliteBook 2170p             | [36d10d9091](https://linux-hardware.org/?probe=36d10d9091) | Feb 16, 2021 |
| Dell          | Latitude 3400               | [38dbd98cd4](https://linux-hardware.org/?probe=38dbd98cd4) | Feb 15, 2021 |
| Lenovo        | Z710 20250                  | [c9694dd19b](https://linux-hardware.org/?probe=c9694dd19b) | Feb 15, 2021 |
| UMAX          | VisionBook 14Wa Plus        | [85de5460d8](https://linux-hardware.org/?probe=85de5460d8) | Feb 15, 2021 |
| ASUSTek       | F5RL                        | [6379e4d092](https://linux-hardware.org/?probe=6379e4d092) | Feb 12, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [4ce0e6df68](https://linux-hardware.org/?probe=4ce0e6df68) | Feb 11, 2021 |
| Dell          | Studio 1747                 | [4ca3a3577f](https://linux-hardware.org/?probe=4ca3a3577f) | Feb 11, 2021 |
| ASUSTek       | X453SA                      | [5e4fcc2492](https://linux-hardware.org/?probe=5e4fcc2492) | Feb 10, 2021 |
| HP            | EliteBook 850 G6            | [40877f0c5d](https://linux-hardware.org/?probe=40877f0c5d) | Feb 10, 2021 |
| HP            | EliteBook 840 G6            | [4caff97f56](https://linux-hardware.org/?probe=4caff97f56) | Feb 08, 2021 |
| Dell          | Latitude E6230              | [6562ca7135](https://linux-hardware.org/?probe=6562ca7135) | Feb 07, 2021 |
| HP            | Stream Laptop 11-y0XX       | [1a6227c6cf](https://linux-hardware.org/?probe=1a6227c6cf) | Feb 07, 2021 |
| Sony          | VGN-FW31J                   | [3ac086a40c](https://linux-hardware.org/?probe=3ac086a40c) | Feb 07, 2021 |
| Dell          | Latitude E5450              | [9b2f037a8e](https://linux-hardware.org/?probe=9b2f037a8e) | Feb 06, 2021 |
| Dell          | Latitude E5450              | [9cce8a2306](https://linux-hardware.org/?probe=9cce8a2306) | Feb 06, 2021 |
| Dell          | Latitude E6410              | [02a7d362ab](https://linux-hardware.org/?probe=02a7d362ab) | Feb 05, 2021 |
| Dell          | Latitude E6400              | [99e1f46388](https://linux-hardware.org/?probe=99e1f46388) | Feb 03, 2021 |
| Acer          | Aspire S3-391               | [c7205a1bc6](https://linux-hardware.org/?probe=c7205a1bc6) | Feb 02, 2021 |
| Lenovo        | G510 20238                  | [29483c03e0](https://linux-hardware.org/?probe=29483c03e0) | Feb 01, 2021 |
| ASUSTek       | X555LD                      | [eb3be3f63f](https://linux-hardware.org/?probe=eb3be3f63f) | Jan 31, 2021 |
| Dell          | Inspiron 7577               | [46453067b0](https://linux-hardware.org/?probe=46453067b0) | Jan 31, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [bbfd58bb17](https://linux-hardware.org/?probe=bbfd58bb17) | Jan 31, 2021 |
| Acer          | Aspire one                  | [596cf5fb05](https://linux-hardware.org/?probe=596cf5fb05) | Jan 30, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [ebe001400f](https://linux-hardware.org/?probe=ebe001400f) | Jan 30, 2021 |
| Acer          | Aspire V7-581G              | [bc8dcae398](https://linux-hardware.org/?probe=bc8dcae398) | Jan 28, 2021 |
| HP            | EliteBook 820 G2            | [655fd94c5b](https://linux-hardware.org/?probe=655fd94c5b) | Jan 27, 2021 |
| Dell          | Precision 5510              | [f548cf6034](https://linux-hardware.org/?probe=f548cf6034) | Jan 27, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | [59a1df6c23](https://linux-hardware.org/?probe=59a1df6c23) | Jan 27, 2021 |
| HP            | EliteBook 820 G2            | [0d9fb09cb0](https://linux-hardware.org/?probe=0d9fb09cb0) | Jan 27, 2021 |
| HP            | 250 G6 Notebook PC          | [e92acb1c9f](https://linux-hardware.org/?probe=e92acb1c9f) | Jan 25, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [a519fed9ad](https://linux-hardware.org/?probe=a519fed9ad) | Jan 25, 2021 |
| Dell          | Latitude E5500              | [bf4f6f14c2](https://linux-hardware.org/?probe=bf4f6f14c2) | Jan 22, 2021 |
| Dell          | Precision 5510              | [023ebcd846](https://linux-hardware.org/?probe=023ebcd846) | Jan 21, 2021 |
| Dell          | Latitude E5440              | [462f80efe3](https://linux-hardware.org/?probe=462f80efe3) | Jan 20, 2021 |
| Dell          | Latitude D430               | [e364de4914](https://linux-hardware.org/?probe=e364de4914) | Jan 19, 2021 |
| Dell          | Latitude D430               | [632ede8190](https://linux-hardware.org/?probe=632ede8190) | Jan 19, 2021 |
| HP            | ProBook 4545s               | [a1361456ee](https://linux-hardware.org/?probe=a1361456ee) | Jan 19, 2021 |
| Lenovo        | ThinkPad T400 6475Y4M       | [e6ea4283a5](https://linux-hardware.org/?probe=e6ea4283a5) | Jan 18, 2021 |
| Lenovo        | ThinkPad T400 6475Y4M       | [af004cce06](https://linux-hardware.org/?probe=af004cce06) | Jan 18, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [8ada2201db](https://linux-hardware.org/?probe=8ada2201db) | Jan 15, 2021 |
| Dell          | XPS 13 9360                 | [0a975a35b9](https://linux-hardware.org/?probe=0a975a35b9) | Jan 13, 2021 |
| Lenovo        | ThinkPad T460 20FN004CMC    | [dc80798934](https://linux-hardware.org/?probe=dc80798934) | Jan 12, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [b5b9926afa](https://linux-hardware.org/?probe=b5b9926afa) | Jan 11, 2021 |
| Sony          | VPCEB1M1E                   | [47b920b10a](https://linux-hardware.org/?probe=47b920b10a) | Jan 10, 2021 |
| HP            | Presario CQ57               | [f87fc12d71](https://linux-hardware.org/?probe=f87fc12d71) | Jan 10, 2021 |
| ASUSTek       | K50IJ                       | [986a4852e5](https://linux-hardware.org/?probe=986a4852e5) | Jan 09, 2021 |
| ASUSTek       | K50IJ                       | [260ee629ec](https://linux-hardware.org/?probe=260ee629ec) | Jan 09, 2021 |
| Dell          | Latitude E6430              | [33c8efc4d3](https://linux-hardware.org/?probe=33c8efc4d3) | Jan 09, 2021 |
| Dell          | Latitude E6430              | [6d373a3972](https://linux-hardware.org/?probe=6d373a3972) | Jan 09, 2021 |
| ASUSTek       | G60JX                       | [e193018885](https://linux-hardware.org/?probe=e193018885) | Jan 03, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [9c7e318dbb](https://linux-hardware.org/?probe=9c7e318dbb) | Jan 01, 2021 |
| Acer          | TravelMate X314-51-MG       | [f2d686d743](https://linux-hardware.org/?probe=f2d686d743) | Jan 01, 2021 |
| Dell          | XPS 15 9550                 | [776e78f155](https://linux-hardware.org/?probe=776e78f155) | Jan 01, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [044a6a709e](https://linux-hardware.org/?probe=044a6a709e) | Dec 31, 2020 |
| ASUSTek       | F3E                         | [76935b8cde](https://linux-hardware.org/?probe=76935b8cde) | Dec 30, 2020 |
| ASUSTek       | F3E                         | [db7f14138d](https://linux-hardware.org/?probe=db7f14138d) | Dec 30, 2020 |
| Lenovo        | ThinkPad T430 23444ZG       | [5904ca74c2](https://linux-hardware.org/?probe=5904ca74c2) | Dec 29, 2020 |
| HP            | EliteBook 840 G3            | [cd80521f36](https://linux-hardware.org/?probe=cd80521f36) | Dec 29, 2020 |
| Acer          | Aspire S3-391               | [cbb35e678a](https://linux-hardware.org/?probe=cbb35e678a) | Dec 29, 2020 |
| Lenovo        | G505s 20255                 | [772dc9d4d7](https://linux-hardware.org/?probe=772dc9d4d7) | Dec 27, 2020 |
| Lenovo        | ThinkPad E15 20RD0011MC     | [e43e83e37e](https://linux-hardware.org/?probe=e43e83e37e) | Dec 26, 2020 |
| Lenovo        | 3000 N100 0768Q4G           | [2352b3bdff](https://linux-hardware.org/?probe=2352b3bdff) | Dec 26, 2020 |
| MSI           | GE60 2QE                    | [57f71a51e7](https://linux-hardware.org/?probe=57f71a51e7) | Dec 25, 2020 |
| Dell          | Latitude E6430s             | [d9e710f80e](https://linux-hardware.org/?probe=d9e710f80e) | Dec 24, 2020 |
| Lenovo        | G780 20138                  | [337ed92b96](https://linux-hardware.org/?probe=337ed92b96) | Dec 21, 2020 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [c904ecb72d](https://linux-hardware.org/?probe=c904ecb72d) | Dec 18, 2020 |
| Dell          | Latitude 7390               | [30de38003f](https://linux-hardware.org/?probe=30de38003f) | Dec 16, 2020 |
| Apple         | MacBookPro6,2               | [d4f9ccd7a6](https://linux-hardware.org/?probe=d4f9ccd7a6) | Dec 16, 2020 |
| Apple         | MacBookPro6,2               | [7faceca969](https://linux-hardware.org/?probe=7faceca969) | Dec 16, 2020 |
| Lenovo        | Flex 2-14 20404             | [8c7c33ba8b](https://linux-hardware.org/?probe=8c7c33ba8b) | Dec 14, 2020 |
| Lenovo        | ThinkPad T470 20HES18R19    | [11ce58f939](https://linux-hardware.org/?probe=11ce58f939) | Dec 13, 2020 |
| HP            | Stream Laptop 11-y0XX       | [ed04aa76f7](https://linux-hardware.org/?probe=ed04aa76f7) | Dec 13, 2020 |
| HP            | Stream Laptop 11-y0XX       | [a45597a09a](https://linux-hardware.org/?probe=a45597a09a) | Dec 13, 2020 |
| MSI           | MS-1688                     | [b56c16909d](https://linux-hardware.org/?probe=b56c16909d) | Dec 12, 2020 |
| Dell          | Precision 3551              | [ffc4c549c8](https://linux-hardware.org/?probe=ffc4c549c8) | Dec 11, 2020 |
| ASUSTek       | X550MJ                      | [66ed5909f8](https://linux-hardware.org/?probe=66ed5909f8) | Dec 10, 2020 |
| HP            | EliteBook 850 G5            | [ac22f08b80](https://linux-hardware.org/?probe=ac22f08b80) | Dec 09, 2020 |
| Dell          | Latitude E6520              | [ae5183024d](https://linux-hardware.org/?probe=ae5183024d) | Dec 08, 2020 |
| ASUSTek       | E502SA                      | [0a25648158](https://linux-hardware.org/?probe=0a25648158) | Dec 05, 2020 |
| Intel         | STCK1A8LFC H67494-302       | [5cd8520aac](https://linux-hardware.org/?probe=5cd8520aac) | Dec 05, 2020 |
| Sony          | VGN-FW31J                   | [f12caf061a](https://linux-hardware.org/?probe=f12caf061a) | Dec 05, 2020 |
| Lenovo        | ThinkPad T440p 20AWS5AD0... | [019dc4a90e](https://linux-hardware.org/?probe=019dc4a90e) | Dec 03, 2020 |
| Acer          | Extensa 5620                | [f2087b24cf](https://linux-hardware.org/?probe=f2087b24cf) | Dec 02, 2020 |
| ASUSTek       | GL552VX                     | [c93b1307eb](https://linux-hardware.org/?probe=c93b1307eb) | Dec 01, 2020 |
| Sony          | VGN-Z21XN_B                 | [155a9f6fa6](https://linux-hardware.org/?probe=155a9f6fa6) | Nov 28, 2020 |
| HP            | Compaq 8510w                | [aa775a9324](https://linux-hardware.org/?probe=aa775a9324) | Nov 28, 2020 |
| HP            | ProBook 6570b               | [679b85fd07](https://linux-hardware.org/?probe=679b85fd07) | Nov 27, 2020 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [db9601a874](https://linux-hardware.org/?probe=db9601a874) | Nov 26, 2020 |
| Dell          | Latitude 7390               | [f95f774a38](https://linux-hardware.org/?probe=f95f774a38) | Nov 26, 2020 |
| Jumper        | EZpad                       | [2c2ae2e061](https://linux-hardware.org/?probe=2c2ae2e061) | Nov 25, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [d39ba59434](https://linux-hardware.org/?probe=d39ba59434) | Nov 24, 2020 |
| HP            | ProBook 450 G7              | [2a3f3bd4a4](https://linux-hardware.org/?probe=2a3f3bd4a4) | Nov 22, 2020 |
| Jumper        | EZpad                       | [807a525352](https://linux-hardware.org/?probe=807a525352) | Nov 21, 2020 |
| HP            | Pavilion TS 11              | [a71dfc4983](https://linux-hardware.org/?probe=a71dfc4983) | Nov 19, 2020 |
| Lenovo        | ThinkPad R61 8935WFB        | [b82d043b71](https://linux-hardware.org/?probe=b82d043b71) | Nov 18, 2020 |
| Dell          | XPS 15 7590                 | [e9b53cc836](https://linux-hardware.org/?probe=e9b53cc836) | Nov 18, 2020 |
| Acer          | Aspire V7-482P              | [c7b8a90092](https://linux-hardware.org/?probe=c7b8a90092) | Nov 17, 2020 |
| In-Sing       | NK81J                       | [2f129a4a67](https://linux-hardware.org/?probe=2f129a4a67) | Nov 16, 2020 |
| In-Sing       | NK81J                       | [a3282a8f65](https://linux-hardware.org/?probe=a3282a8f65) | Nov 16, 2020 |
| Lenovo        | ThinkPad Edge E530 3259B... | [c46ceddde5](https://linux-hardware.org/?probe=c46ceddde5) | Nov 16, 2020 |
| Acer          | Aspire E5-551G              | [8b8a83f80b](https://linux-hardware.org/?probe=8b8a83f80b) | Nov 15, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | [3568e22cde](https://linux-hardware.org/?probe=3568e22cde) | Nov 14, 2020 |
| Acer          | Aspire V7-482P              | [cff0a4d702](https://linux-hardware.org/?probe=cff0a4d702) | Nov 14, 2020 |
| Dell          | XPS 13 9343                 | [4f86cf4cbf](https://linux-hardware.org/?probe=4f86cf4cbf) | Nov 13, 2020 |
| Fujitsu       | LIFEBOOK E734               | [5292c3d1c6](https://linux-hardware.org/?probe=5292c3d1c6) | Nov 13, 2020 |
| Dell          | XPS 13 7390                 | [f816f90302](https://linux-hardware.org/?probe=f816f90302) | Nov 10, 2020 |
| ASUSTek       | X550CC                      | [cb23a45745](https://linux-hardware.org/?probe=cb23a45745) | Nov 10, 2020 |
| ASUSTek       | X550CC                      | [ccdf1d9de6](https://linux-hardware.org/?probe=ccdf1d9de6) | Nov 10, 2020 |
| Lenovo        | ThinkPad T420 4178A9G       | [41f4ce9090](https://linux-hardware.org/?probe=41f4ce9090) | Nov 10, 2020 |
| ASUSTek       | X550CC                      | [11e2a64b37](https://linux-hardware.org/?probe=11e2a64b37) | Nov 07, 2020 |
| HP            | Compaq Mini 110c-1100       | [1adcc4379a](https://linux-hardware.org/?probe=1adcc4379a) | Nov 07, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | [366328b790](https://linux-hardware.org/?probe=366328b790) | Nov 07, 2020 |
| Dell          | Precision 7740              | [887976cf88](https://linux-hardware.org/?probe=887976cf88) | Nov 05, 2020 |
| Toshiba       | Satellite Pro U400          | [e6a9e4a78e](https://linux-hardware.org/?probe=e6a9e4a78e) | Nov 05, 2020 |
| HP            | Compaq 6910p                | [116434c462](https://linux-hardware.org/?probe=116434c462) | Nov 04, 2020 |
| MSI           | PS42 Modern 8RA             | [80629e1f55](https://linux-hardware.org/?probe=80629e1f55) | Nov 03, 2020 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [4b34114e72](https://linux-hardware.org/?probe=4b34114e72) | Nov 03, 2020 |
| Dell          | Latitude E5520              | [59e9f4557e](https://linux-hardware.org/?probe=59e9f4557e) | Nov 02, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | [e49822ee09](https://linux-hardware.org/?probe=e49822ee09) | Nov 02, 2020 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [54079a5e32](https://linux-hardware.org/?probe=54079a5e32) | Nov 02, 2020 |
| ASUSTek       | X510UNR                     | [f97fa98c1f](https://linux-hardware.org/?probe=f97fa98c1f) | Nov 01, 2020 |
| HP            | ProBook 450 G7              | [d6ea9e1cd2](https://linux-hardware.org/?probe=d6ea9e1cd2) | Nov 01, 2020 |
| Lenovo        | 3000 N100 0768Q4G           | [dda213843b](https://linux-hardware.org/?probe=dda213843b) | Nov 01, 2020 |
| ASUSTek       | N73SV                       | [b2d4729f22](https://linux-hardware.org/?probe=b2d4729f22) | Nov 01, 2020 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [f9755b992e](https://linux-hardware.org/?probe=f9755b992e) | Nov 01, 2020 |
| HP            | 255 G4                      | [e841543a23](https://linux-hardware.org/?probe=e841543a23) | Oct 31, 2020 |
| HP            | 255 G4                      | [79d387d0ab](https://linux-hardware.org/?probe=79d387d0ab) | Oct 31, 2020 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [85435abf0b](https://linux-hardware.org/?probe=85435abf0b) | Oct 31, 2020 |
| Fujitsu       | LIFEBOOK U758               | [287e2c5d14](https://linux-hardware.org/?probe=287e2c5d14) | Oct 30, 2020 |
| Lenovo        | 3000 N100 0768Q4G           | [87ff568248](https://linux-hardware.org/?probe=87ff568248) | Oct 29, 2020 |
| Acer          | Extensa 5620                | [e7fab7440e](https://linux-hardware.org/?probe=e7fab7440e) | Oct 29, 2020 |
| Dell          | Inspiron 5593               | [3fbb5a72d7](https://linux-hardware.org/?probe=3fbb5a72d7) | Oct 28, 2020 |
| Toshiba       | Satellite P100              | [ea537c7d93](https://linux-hardware.org/?probe=ea537c7d93) | Oct 28, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [b52e1d7ccf](https://linux-hardware.org/?probe=b52e1d7ccf) | Oct 27, 2020 |
| Acer          | Aspire E5-571G              | [9d695214a4](https://linux-hardware.org/?probe=9d695214a4) | Oct 27, 2020 |
| Lenovo        | B51-80 80LM                 | [c40197b546](https://linux-hardware.org/?probe=c40197b546) | Oct 27, 2020 |
| HP            | EliteBook 830 G5            | [2ca9995218](https://linux-hardware.org/?probe=2ca9995218) | Oct 26, 2020 |
| Acer          | Aspire 8930                 | [fde733b7c7](https://linux-hardware.org/?probe=fde733b7c7) | Oct 25, 2020 |
| HP            | EliteBook 840 G5            | [4bba55301d](https://linux-hardware.org/?probe=4bba55301d) | Oct 24, 2020 |
| Dell          | Inspiron 5593               | [4f0c0f034e](https://linux-hardware.org/?probe=4f0c0f034e) | Oct 22, 2020 |
| Dell          | Inspiron 5593               | [aa31ceeb8f](https://linux-hardware.org/?probe=aa31ceeb8f) | Oct 22, 2020 |
| Dell          | Latitude E5520              | [2a250b5803](https://linux-hardware.org/?probe=2a250b5803) | Oct 22, 2020 |
| Dell          | Vostro 3350                 | [88e849444f](https://linux-hardware.org/?probe=88e849444f) | Oct 22, 2020 |
| HUAWEI        | MACH-WX9                    | [4b7b836641](https://linux-hardware.org/?probe=4b7b836641) | Oct 21, 2020 |
| Dell          | Vostro 1510                 | [dd9a477473](https://linux-hardware.org/?probe=dd9a477473) | Oct 21, 2020 |
| INET          | P201P                       | [644453ac6f](https://linux-hardware.org/?probe=644453ac6f) | Oct 21, 2020 |
| Dell          | Latitude E5540              | [7baf46ea1a](https://linux-hardware.org/?probe=7baf46ea1a) | Oct 21, 2020 |
| Sony          | VGN-FW31J                   | [a2ab2b1bee](https://linux-hardware.org/?probe=a2ab2b1bee) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [30cef457c4](https://linux-hardware.org/?probe=30cef457c4) | Oct 19, 2020 |
| HP            | ProBook 450 G5              | [054a64d6f2](https://linux-hardware.org/?probe=054a64d6f2) | Oct 18, 2020 |
| MSI           | GE60 2QE                    | [246e6f7276](https://linux-hardware.org/?probe=246e6f7276) | Oct 17, 2020 |
| ASUSTek       | K50IJ                       | [0adb1dec20](https://linux-hardware.org/?probe=0adb1dec20) | Oct 16, 2020 |
| ASUSTek       | K50IJ                       | [c20f8b68f4](https://linux-hardware.org/?probe=c20f8b68f4) | Oct 16, 2020 |
| Lenovo        | ThinkPad T420 4178A9G       | [9b67d68beb](https://linux-hardware.org/?probe=9b67d68beb) | Oct 14, 2020 |
| Lenovo        | ThinkPad T420 4178A9G       | [b0407d39c3](https://linux-hardware.org/?probe=b0407d39c3) | Oct 14, 2020 |
| Lenovo        | G510 20238                  | [65aff7828e](https://linux-hardware.org/?probe=65aff7828e) | Oct 13, 2020 |
| Sony          | VGN-FW31J                   | [eee35eb8e9](https://linux-hardware.org/?probe=eee35eb8e9) | Oct 13, 2020 |
| HP            | 250 G6 Notebook PC          | [8bdcdd3b6a](https://linux-hardware.org/?probe=8bdcdd3b6a) | Oct 13, 2020 |
| Lenovo        | G510 20238                  | [93221fbe75](https://linux-hardware.org/?probe=93221fbe75) | Oct 11, 2020 |
| Dell          | XPS 15 9500                 | [1a53ead300](https://linux-hardware.org/?probe=1a53ead300) | Oct 10, 2020 |
| Acer          | Aspire V3-551G              | [30f77b0594](https://linux-hardware.org/?probe=30f77b0594) | Oct 10, 2020 |
| Lenovo        | ThinkPad E15 20RD0011MC     | [a14e9d2839](https://linux-hardware.org/?probe=a14e9d2839) | Oct 10, 2020 |
| Acer          | Aspire E5-551G              | [9911a6b479](https://linux-hardware.org/?probe=9911a6b479) | Oct 09, 2020 |
| Lenovo        | ThinkPad E15 20RD0011MC     | [726bdf3762](https://linux-hardware.org/?probe=726bdf3762) | Oct 08, 2020 |
| HP            | ProBook 455 G7              | [289f93a7e6](https://linux-hardware.org/?probe=289f93a7e6) | Oct 08, 2020 |
| HP            | ProBook 455 G7              | [9649d645a8](https://linux-hardware.org/?probe=9649d645a8) | Oct 08, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [6870ec982e](https://linux-hardware.org/?probe=6870ec982e) | Oct 07, 2020 |
| Dell          | Latitude E5530 non-vPro     | [86aa78e5af](https://linux-hardware.org/?probe=86aa78e5af) | Oct 05, 2020 |
| Dell          | Latitude E5530 non-vPro     | [c535d537e1](https://linux-hardware.org/?probe=c535d537e1) | Oct 05, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4df9440dcd](https://linux-hardware.org/?probe=4df9440dcd) | Oct 04, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Czechia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 156       | 14.39%  |
| Ubuntu 18.04                 | 83        | 7.66%   |
| OpenMandriva 4.2             | 74        | 6.83%   |
| OpenMandriva 4.50            | 54        | 4.98%   |
| Ubuntu 21.10                 | 28        | 2.58%   |
| OpenMandriva 4.3             | 26        | 2.4%    |
| Ubuntu 22.04                 | 25        | 2.31%   |
| Ubuntu 19.10                 | 22        | 2.03%   |
| Fedora 34                    | 22        | 2.03%   |
| Ubuntu 20.10                 | 21        | 1.94%   |
| Ubuntu 21.04                 | 18        | 1.66%   |
| Linux Mint 20                | 17        | 1.57%   |
| Arch                         | 17        | 1.57%   |
| Zorin 15                     | 16        | 1.48%   |
| Linux Mint 20.2              | 16        | 1.48%   |
| Linux Mint 19.3              | 16        | 1.48%   |
| Debian 11                    | 15        | 1.38%   |
| Zorin 16                     | 14        | 1.29%   |
| Fedora 35                    | 14        | 1.29%   |
| Linux Mint 20.1              | 13        | 1.2%    |
| Fedora 33                    | 13        | 1.2%    |
| Fedora 32                    | 13        | 1.2%    |
| Fedora 31                    | 13        | 1.2%    |
| Xubuntu 20.04                | 12        | 1.11%   |
| Ubuntu 19.04                 | 12        | 1.11%   |
| Linux Mint 20.3              | 12        | 1.11%   |
| Arch Rolling                 | 12        | 1.11%   |
| Linux Mint 21                | 11        | 1.01%   |
| Fedora 36                    | 11        | 1.01%   |
| openSUSE Tumbleweed-XXXXXXXX | 10        | 0.92%   |
| Manjaro                      | 10        | 0.92%   |
| Kubuntu 20.04                | 10        | 0.92%   |
| Xubuntu 18.04                | 9         | 0.83%   |
| Debian 10                    | 9         | 0.83%   |
| Pop!_OS 20.04                | 8         | 0.74%   |
| KDE neon 20.04               | 7         | 0.65%   |
| Ubuntu 18.10                 | 6         | 0.55%   |
| Gentoo 2.7                   | 6         | 0.55%   |
| Ubuntu 16.04                 | 5         | 0.46%   |
| ROSA 12.2                    | 5         | 0.46%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 348       | 34.15%  |
| OpenMandriva     | 157       | 15.41%  |
| Fedora           | 92        | 9.03%   |
| Linux Mint       | 87        | 8.54%   |
| Zorin            | 31        | 3.04%   |
| Xubuntu          | 31        | 3.04%   |
| Manjaro          | 29        | 2.85%   |
| Arch             | 29        | 2.85%   |
| Debian           | 28        | 2.75%   |
| Kubuntu          | 21        | 2.06%   |
| Pop!_OS          | 18        | 1.77%   |
| ROSA             | 16        | 1.57%   |
| openSUSE         | 15        | 1.47%   |
| Gentoo           | 13        | 1.28%   |
| Lubuntu          | 10        | 0.98%   |
| KDE neon         | 10        | 0.98%   |
| Kali             | 8         | 0.79%   |
| Elementary       | 8         | 0.79%   |
| Endless          | 7         | 0.69%   |
| ArcoLinux        | 6         | 0.59%   |
| Ubuntu Unity     | 5         | 0.49%   |
| Ubuntu MATE      | 5         | 0.49%   |
| RHEL             | 5         | 0.49%   |
| SteamOS          | 3         | 0.29%   |
| Parrot           | 3         | 0.29%   |
| MX               | 3         | 0.29%   |
| BlackPanther     | 3         | 0.29%   |
| Rocky Linux      | 2         | 0.2%    |
| LinuxFX          | 2         | 0.2%    |
| EndeavourOS      | 2         | 0.2%    |
| Artix            | 2         | 0.2%    |
| Void Linux       | 1         | 0.1%    |
| Ubuntu Budgie    | 1         | 0.1%    |
| SystemRescue     | 1         | 0.1%    |
| Solus            | 1         | 0.1%    |
| Sabayon          | 1         | 0.1%    |
| Reborn OS        | 1         | 0.1%    |
| Peppermint       | 1         | 0.1%    |
| org.kde.Platform | 1         | 0.1%    |
| Nobara           | 1         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 73        | 6.21%   |
| 5.14.7-desktop-1omv4050  | 52        | 4.43%   |
| 5.16.7-desktop-1omv4003  | 26        | 2.21%   |
| 5.4.0-42-generic         | 23        | 1.96%   |
| 5.4.0-52-generic         | 15        | 1.28%   |
| 5.15.0-46-generic        | 15        | 1.28%   |
| 5.4.0-26-generic         | 13        | 1.11%   |
| 5.4.0-58-generic         | 11        | 0.94%   |
| 5.3.0-40-generic         | 11        | 0.94%   |
| 5.4.0-65-generic         | 9         | 0.77%   |
| 5.15.0-48-generic        | 9         | 0.77%   |
| 5.0.0-37-generic         | 9         | 0.77%   |
| 5.8.0-59-generic         | 8         | 0.68%   |
| 5.4.0-48-generic         | 8         | 0.68%   |
| 5.4.0-40-generic         | 8         | 0.68%   |
| 5.15.0-52-generic        | 8         | 0.68%   |
| 5.13.0-21-generic        | 8         | 0.68%   |
| 5.4.0-91-generic         | 7         | 0.6%    |
| 5.11.0-27-generic        | 7         | 0.6%    |
| 5.8.0-53-generic         | 6         | 0.51%   |
| 5.4.0-70-generic         | 6         | 0.51%   |
| 5.4.0-56-generic         | 6         | 0.51%   |
| 5.4.0-37-generic         | 6         | 0.51%   |
| 5.4.0-29-generic         | 6         | 0.51%   |
| 5.3.0-46-generic         | 6         | 0.51%   |
| 5.3.0-42-generic         | 6         | 0.51%   |
| 5.3.0-28-generic         | 6         | 0.51%   |
| 5.13.0-30-generic        | 6         | 0.51%   |
| 5.13.0-22-generic        | 6         | 0.51%   |
| 5.11.0-34-generic        | 6         | 0.51%   |
| 5.11.0-25-generic        | 6         | 0.51%   |
| 5.11.0-22-generic        | 6         | 0.51%   |
| 5.0.0-31-generic         | 6         | 0.51%   |
| 5.0.0-25-generic         | 6         | 0.51%   |
| 5.8.0-48-generic         | 5         | 0.43%   |
| 5.4.0-7642-generic       | 5         | 0.43%   |
| 5.3.0-45-generic         | 5         | 0.43%   |
| 5.3.0-26-generic         | 5         | 0.43%   |
| 5.13.0-19-generic        | 5         | 0.43%   |
| 5.11.0-37-generic        | 5         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 187       | 17%     |
| 5.10.14 | 73        | 6.64%   |
| 5.3.0   | 68        | 6.18%   |
| 5.13.0  | 63        | 5.73%   |
| 5.11.0  | 63        | 5.73%   |
| 5.8.0   | 58        | 5.27%   |
| 4.15.0  | 57        | 5.18%   |
| 5.15.0  | 53        | 4.82%   |
| 5.14.7  | 53        | 4.82%   |
| 5.0.0   | 44        | 4%      |
| 5.16.7  | 27        | 2.45%   |
| 4.18.0  | 26        | 2.36%   |
| 5.10.0  | 23        | 2.09%   |
| 4.19.0  | 8         | 0.73%   |
| 5.15.12 | 5         | 0.45%   |
| 4.13.0  | 5         | 0.45%   |
| 5.9.0   | 4         | 0.36%   |
| 5.6.16  | 4         | 0.36%   |
| 5.3.18  | 4         | 0.36%   |
| 5.16.11 | 4         | 0.36%   |
| 5.14.0  | 4         | 0.36%   |
| 5.11.12 | 4         | 0.36%   |
| 5.10.74 | 4         | 0.36%   |
| 4.4.0   | 4         | 0.36%   |
| 6.0.2   | 3         | 0.27%   |
| 5.9.16  | 3         | 0.27%   |
| 5.8.18  | 3         | 0.27%   |
| 5.17.5  | 3         | 0.27%   |
| 5.17.1  | 3         | 0.27%   |
| 5.16.2  | 3         | 0.27%   |
| 5.14.15 | 3         | 0.27%   |
| 5.13.19 | 3         | 0.27%   |
| 5.11.16 | 3         | 0.27%   |
| 5.10.52 | 3         | 0.27%   |
| 6.0.0   | 2         | 0.18%   |
| 5.9.3   | 2         | 0.18%   |
| 5.8.15  | 2         | 0.18%   |
| 5.8.14  | 2         | 0.18%   |
| 5.7.0   | 2         | 0.18%   |
| 5.6.8   | 2         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 203       | 18.54%  |
| 5.10    | 123       | 11.23%  |
| 5.11    | 84        | 7.67%   |
| 5.15    | 79        | 7.21%   |
| 5.3     | 76        | 6.94%   |
| 5.13    | 76        | 6.94%   |
| 5.8     | 73        | 6.67%   |
| 5.14    | 69        | 6.3%    |
| 4.15    | 59        | 5.39%   |
| 5.0     | 46        | 4.2%    |
| 5.16    | 43        | 3.93%   |
| 4.18    | 28        | 2.56%   |
| 5.17    | 17        | 1.55%   |
| 5.19    | 16        | 1.46%   |
| 5.9     | 15        | 1.37%   |
| 5.6     | 15        | 1.37%   |
| 5.18    | 13        | 1.19%   |
| 4.19    | 12        | 1.1%    |
| 6.0     | 8         | 0.73%   |
| 5.12    | 7         | 0.64%   |
| 4.9     | 7         | 0.64%   |
| 5.7     | 6         | 0.55%   |
| 5.5     | 6         | 0.55%   |
| 4.13    | 5         | 0.46%   |
| 4.4     | 4         | 0.37%   |
| 5.1     | 2         | 0.18%   |
| 4.8     | 1         | 0.09%   |
| 4.17    | 1         | 0.09%   |
| 4.14    | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 966       | 96.31%  |
| i686   | 37        | 3.69%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 415       | 40.02%  |
| KDE5            | 240       | 23.14%  |
| Unknown         | 131       | 12.63%  |
| XFCE            | 81        | 7.81%   |
| X-Cinnamon      | 45        | 4.34%   |
| MATE            | 27        | 2.6%    |
| KDE             | 22        | 2.12%   |
| Cinnamon        | 17        | 1.64%   |
| Pantheon        | 8         | 0.77%   |
| LXQt            | 8         | 0.77%   |
| Unity           | 6         | 0.58%   |
| KDE4            | 6         | 0.58%   |
| GNOME Flashback | 6         | 0.58%   |
| LXDE            | 5         | 0.48%   |
| awesome         | 4         | 0.39%   |
| sway            | 2         | 0.19%   |
| qtile           | 2         | 0.19%   |
| openbox         | 2         | 0.19%   |
| i3              | 2         | 0.19%   |
| Budgie          | 2         | 0.19%   |
| XSession        | 1         | 0.1%    |
| xinitrc         | 1         | 0.1%    |
| GNUstep         | 1         | 0.1%    |
| Enlightenment   | 1         | 0.1%    |
| DWM             | 1         | 0.1%    |
| custom          | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 803       | 78.11%  |
| Wayland | 140       | 13.62%  |
| Unknown | 78        | 7.59%   |
| Tty     | 7         | 0.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 473       | 45.74%  |
| SDDM    | 233       | 22.53%  |
| GDM     | 125       | 12.09%  |
| LightDM | 78        | 7.54%   |
| GDM3    | 72        | 6.96%   |
| TDM     | 39        | 3.77%   |
| KDM     | 5         | 0.48%   |
| XDM     | 4         | 0.39%   |
| LXDM    | 2         | 0.19%   |
| SLiM    | 1         | 0.1%    |
| Ly      | 1         | 0.1%    |
| GREETD  | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| cs_CZ   | 540       | 52.84%  |
| en_US   | 290       | 28.38%  |
| Unknown | 120       | 11.74%  |
| en_GB   | 21        | 2.05%   |
| C       | 18        | 1.76%   |
| ru_RU   | 13        | 1.27%   |
| sk_SK   | 3         | 0.29%   |
| POSIX   | 3         | 0.29%   |
| pl_PL   | 2         | 0.2%    |
| it_IT   | 2         | 0.2%    |
| fr_FR   | 2         | 0.2%    |
| de_DE   | 2         | 0.2%    |
| uk_UA   | 1         | 0.1%    |
| ro_RO   | 1         | 0.1%    |
| es_ES   | 1         | 0.1%    |
| en_NG   | 1         | 0.1%    |
| en_150  | 1         | 0.1%    |
| el_GR   | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 541       | 52.63%  |
| EFI  | 487       | 47.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 693       | 68.34%  |
| Overlay  | 174       | 17.16%  |
| Btrfs    | 76        | 7.5%    |
| Unknown  | 33        | 3.25%   |
| Xfs      | 23        | 2.27%   |
| Zfs      | 4         | 0.39%   |
| Ext3     | 3         | 0.3%    |
| Tmpfs    | 2         | 0.2%    |
| Ext2     | 2         | 0.2%    |
| Aufs     | 2         | 0.2%    |
| Reiserfs | 1         | 0.1%    |
| F2fs     | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 509       | 50.3%   |
| GPT     | 308       | 30.43%  |
| MBR     | 195       | 19.27%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 922       | 91.29%  |
| Yes       | 88        | 8.71%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 639       | 62.59%  |
| Yes       | 382       | 37.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 251       | 25.02%  |
| ASUSTek Computer               | 204       | 20.34%  |
| Hewlett-Packard                | 185       | 18.44%  |
| Dell                           | 143       | 14.26%  |
| Acer                           | 95        | 9.47%   |
| Toshiba                        | 15        | 1.5%    |
| MSI                            | 15        | 1.5%    |
| Sony                           | 14        | 1.4%    |
| UMAX                           | 10        | 1%      |
| Fujitsu                        | 8         | 0.8%    |
| HUAWEI                         | 7         | 0.7%    |
| Apple                          | 5         | 0.5%    |
| Unknown                        | 5         | 0.5%    |
| Timi                           | 4         | 0.4%    |
| Valve                          | 3         | 0.3%    |
| TUXEDO                         | 3         | 0.3%    |
| Packard Bell                   | 3         | 0.3%    |
| Google                         | 3         | 0.3%    |
| Fujitsu Siemens                | 3         | 0.3%    |
| Notebook                       | 2         | 0.2%    |
| Insyde                         | 2         | 0.2%    |
| Chuwi                          | 2         | 0.2%    |
| Alienware                      | 2         | 0.2%    |
| SmbiosType1_SystemManufacturer | 1         | 0.1%    |
| SLIMBOOK                       | 1         | 0.1%    |
| Samsung Electronics            | 1         | 0.1%    |
| Purism                         | 1         | 0.1%    |
| Prestigio                      | 1         | 0.1%    |
| Panasonic                      | 1         | 0.1%    |
| Medion                         | 1         | 0.1%    |
| Jumper                         | 1         | 0.1%    |
| Intel                          | 1         | 0.1%    |
| INET                           | 1         | 0.1%    |
| In-Sing                        | 1         | 0.1%    |
| IBM                            | 1         | 0.1%    |
| Gigabyte Technology            | 1         | 0.1%    |
| EUROCOM                        | 1         | 0.1%    |
| Dynabook                       | 1         | 0.1%    |
| DATABOX                        | 1         | 0.1%    |
| Clevo                          | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| ASUS UX31E                               | 103       | 10.27%  |
| HP ProBook 455 G7                        | 6         | 0.6%    |
| Unknown                                  | 6         | 0.6%    |
| Lenovo ThinkPad E14 20RA001LMC           | 5         | 0.5%    |
| HP ProBook 4530s                         | 5         | 0.5%    |
| HP ProBook 450 G5                        | 5         | 0.5%    |
| Dell Latitude E6400                      | 5         | 0.5%    |
| Dell Latitude 5401                       | 5         | 0.5%    |
| HP ProBook 4540s                         | 4         | 0.4%    |
| HP Pavilion dv7                          | 4         | 0.4%    |
| HP Notebook                              | 4         | 0.4%    |
| HP EliteBook 840 G6                      | 4         | 0.4%    |
| Dell XPS 15 7590                         | 4         | 0.4%    |
| Dell Precision M6500                     | 4         | 0.4%    |
| Acer Extensa 5620                        | 4         | 0.4%    |
| Valve Jupiter                            | 3         | 0.3%    |
| Lenovo Z50-75 80EC                       | 3         | 0.3%    |
| Lenovo ThinkPad T14 Gen 1 20UES2WA00     | 3         | 0.3%    |
| Lenovo IdeaPad L340-17IRH Gaming 81LL    | 3         | 0.3%    |
| HP ProBook 4510s                         | 3         | 0.3%    |
| HP Pavilion dv6                          | 3         | 0.3%    |
| HP EliteBook 855 G7 Notebook PC          | 3         | 0.3%    |
| HP EliteBook 850 G6                      | 3         | 0.3%    |
| HP EliteBook 840 G3                      | 3         | 0.3%    |
| HP 250 G6 Notebook PC                    | 3         | 0.3%    |
| Dell XPS 15 9560                         | 3         | 0.3%    |
| Dell XPS 13 9360                         | 3         | 0.3%    |
| Dell Precision 5510                      | 3         | 0.3%    |
| Dell Latitude E6420                      | 3         | 0.3%    |
| Dell Latitude E5520                      | 3         | 0.3%    |
| Dell Latitude E5470                      | 3         | 0.3%    |
| Dell Latitude 7480                       | 3         | 0.3%    |
| Dell Latitude 5480                       | 3         | 0.3%    |
| ASUS VivoBook_ASUSLaptop X3500PH_K3500PH | 3         | 0.3%    |
| ASUS E502SA                              | 3         | 0.3%    |
| Acer Extensa 5235                        | 3         | 0.3%    |
| Acer Extensa 5220                        | 3         | 0.3%    |
| UMAX VisionBook N15G Plus                | 2         | 0.2%    |
| MSI GE620/GE620DX/FX620DX/FX623          | 2         | 0.2%    |
| Lenovo Yoga 500-15IBD 80N6               | 2         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 136       | 13.56%  |
| ASUS UX31E            | 103       | 10.27%  |
| Dell Latitude         | 74        | 7.38%   |
| Acer Aspire           | 57        | 5.68%   |
| HP ProBook            | 55        | 5.48%   |
| HP EliteBook          | 50        | 4.99%   |
| Lenovo IdeaPad        | 48        | 4.79%   |
| Dell XPS              | 22        | 2.19%   |
| HP Pavilion           | 21        | 2.09%   |
| Dell Inspiron         | 17        | 1.69%   |
| Dell Precision        | 16        | 1.6%    |
| Toshiba Satellite     | 14        | 1.4%    |
| Acer Extensa          | 13        | 1.3%    |
| Lenovo Legion         | 12        | 1.2%    |
| HP Compaq             | 12        | 1.2%    |
| ASUS VivoBook         | 10        | 1%      |
| HP ZBook              | 9         | 0.9%    |
| ASUS ZenBook          | 9         | 0.9%    |
| Acer TravelMate       | 9         | 0.9%    |
| UMAX VisionBook       | 8         | 0.8%    |
| Lenovo Yoga           | 8         | 0.8%    |
| Lenovo ThinkBook      | 8         | 0.8%    |
| HP Laptop             | 8         | 0.8%    |
| Fujitsu LIFEBOOK      | 8         | 0.8%    |
| Acer Swift            | 8         | 0.8%    |
| Dell Vostro           | 7         | 0.7%    |
| HP 250                | 6         | 0.6%    |
| Unknown               | 6         | 0.6%    |
| HP Notebook           | 4         | 0.4%    |
| ASUS ASUS             | 4         | 0.4%    |
| Valve Jupiter         | 3         | 0.3%    |
| Packard Bell EasyNote | 3         | 0.3%    |
| Lenovo Z50-75         | 3         | 0.3%    |
| HP OMEN               | 3         | 0.3%    |
| Fujitsu Siemens AMILO | 3         | 0.3%    |
| Dell G5               | 3         | 0.3%    |
| ASUS ROG              | 3         | 0.3%    |
| ASUS E502SA           | 3         | 0.3%    |
| Acer Nitro            | 3         | 0.3%    |
| MSI GE620             | 2         | 0.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 163       | 16.25%  |
| 2019    | 95        | 9.47%   |
| 2020    | 89        | 8.87%   |
| 2018    | 73        | 7.28%   |
| 2021    | 67        | 6.68%   |
| 2012    | 65        | 6.48%   |
| 2015    | 58        | 5.78%   |
| 2017    | 57        | 5.68%   |
| 2014    | 54        | 5.38%   |
| 2008    | 54        | 5.38%   |
| 2013    | 53        | 5.28%   |
| 2016    | 48        | 4.79%   |
| 2010    | 42        | 4.19%   |
| 2007    | 28        | 2.79%   |
| 2009    | 25        | 2.49%   |
| 2022    | 14        | 1.4%    |
| 2006    | 11        | 1.1%    |
| 2005    | 3         | 0.3%    |
| 2004    | 2         | 0.2%    |
| Unknown | 2         | 0.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1003      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 887       | 87.3%   |
| Enabled  | 129       | 12.7%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 999       | 99.6%   |
| Yes  | 4         | 0.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 299       | 29.34%  |
| 4.01-8.0    | 217       | 21.3%   |
| 8.01-16.0   | 169       | 16.58%  |
| 16.01-24.0  | 150       | 14.72%  |
| 32.01-64.0  | 71        | 6.97%   |
| 1.01-2.0    | 57        | 5.59%   |
| 2.01-3.0    | 17        | 1.67%   |
| 24.01-32.0  | 16        | 1.57%   |
| 0.51-1.0    | 14        | 1.37%   |
| 64.01-256.0 | 8         | 0.79%   |
| 0.01-0.5    | 1         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 420       | 38.18%  |
| 2.01-3.0   | 236       | 21.45%  |
| 4.01-8.0   | 158       | 14.36%  |
| 3.01-4.0   | 132       | 12%     |
| 0.51-1.0   | 69        | 6.27%   |
| 8.01-16.0  | 61        | 5.55%   |
| 0.01-0.5   | 13        | 1.18%   |
| 16.01-24.0 | 8         | 0.73%   |
| 32.01-64.0 | 2         | 0.18%   |
| 24.01-32.0 | 1         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 809       | 78.93%  |
| 2      | 178       | 17.37%  |
| 3      | 24        | 2.34%   |
| 0      | 13        | 1.27%   |
| 4      | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 679       | 67.29%  |
| Yes       | 330       | 32.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 855       | 84.65%  |
| No        | 155       | 15.35%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 985       | 98.11%  |
| No        | 19        | 1.89%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 720       | 70.8%   |
| No        | 297       | 29.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Czechia | 1003      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Prague               | 432       | 41.82%  |
| Brno                 | 98        | 9.49%   |
| Ostrava              | 28        | 2.71%   |
| Pilsen               | 20        | 1.94%   |
| Pardubice            | 13        | 1.26%   |
| Olomouc              | 13        | 1.26%   |
| Liberec              | 13        | 1.26%   |
| České Budějovice  | 12        | 1.16%   |
| Hradec Králové     | 11        | 1.06%   |
| Chomutov             | 9         | 0.87%   |
| Havířov            | 8         | 0.77%   |
| Zlín                | 7         | 0.68%   |
| Most                 | 7         | 0.68%   |
| Karlovy Vary         | 7         | 0.68%   |
| Ústí nad Labem     | 6         | 0.58%   |
| Jihlava              | 6         | 0.58%   |
| Roznov pod Radhostem | 4         | 0.39%   |
| Příbram            | 4         | 0.39%   |
| Přerov              | 4         | 0.39%   |
| Mariánské Lázně  | 4         | 0.39%   |
| Kladno               | 4         | 0.39%   |
| Česká Lípa        | 4         | 0.39%   |
| Ceska Kamenice       | 4         | 0.39%   |
| Znojmo               | 3         | 0.29%   |
| Uvaly                | 3         | 0.29%   |
| Uhlirske Janovice    | 3         | 0.29%   |
| Třebíč            | 3         | 0.29%   |
| Teplice              | 3         | 0.29%   |
| Tábor               | 3         | 0.29%   |
| Slavkov u Brna       | 3         | 0.29%   |
| Praha 10             | 3         | 0.29%   |
| Opava                | 3         | 0.29%   |
| Odolena Voda         | 3         | 0.29%   |
| Mladá Boleslav      | 3         | 0.29%   |
| Kraluv Dvur          | 3         | 0.29%   |
| Kralupy nad Vltavou  | 3         | 0.29%   |
| Jindrichuv Hradec    | 3         | 0.29%   |
| Jablonec nad Nisou   | 3         | 0.29%   |
| Ivancice             | 3         | 0.29%   |
| Bohumin              | 3         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 188       | 249    | 15.84%  |
| SanDisk                        | 156       | 161    | 13.14%  |
| WDC                            | 128       | 153    | 10.78%  |
| Seagate                        | 116       | 161    | 9.77%   |
| Toshiba                        | 97        | 120    | 8.17%   |
| Kingston                       | 67        | 72     | 5.64%   |
| Unknown                        | 62        | 80     | 5.22%   |
| SK hynix                       | 55        | 65     | 4.63%   |
| Hitachi                        | 44        | 52     | 3.71%   |
| HGST                           | 37        | 46     | 3.12%   |
| Micron Technology              | 35        | 43     | 2.95%   |
| Intel                          | 33        | 40     | 2.78%   |
| A-DATA Technology              | 23        | 26     | 1.94%   |
| Crucial                        | 18        | 28     | 1.52%   |
| Patriot                        | 17        | 22     | 1.43%   |
| KIOXIA                         | 11        | 17     | 0.93%   |
| Transcend                      | 7         | 7      | 0.59%   |
| LITEONIT                       | 7         | 9      | 0.59%   |
| Fujitsu                        | 7         | 7      | 0.59%   |
| China                          | 6         | 7      | 0.51%   |
| Phison                         | 5         | 12     | 0.42%   |
| LITEON                         | 5         | 5      | 0.42%   |
| JMicron Technology             | 4         | 4      | 0.34%   |
| Apple                          | 4         | 4      | 0.34%   |
| Apacer                         | 4         | 6      | 0.34%   |
| Unknown                        | 4         | 5      | 0.34%   |
| Silicon Motion                 | 3         | 3      | 0.25%   |
| Phison Electronics             | 3         | 3      | 0.25%   |
| Gigabyte Technology            | 3         | 7      | 0.25%   |
| ASMedia                        | 3         | 5      | 0.25%   |
| Verbatim                       | 2         | 2      | 0.17%   |
| Team                           | 2         | 2      | 0.17%   |
| Solid State Storage Technology | 2         | 2      | 0.17%   |
| Micron/Crucial Technology      | 2         | 2      | 0.17%   |
| Lite-On                        | 2         | 4      | 0.17%   |
| Lenovo                         | 2         | 3      | 0.17%   |
| Corsair                        | 2         | 2      | 0.17%   |
| ASMT                           | 2         | 2      | 0.17%   |
| XrayDisk                       | 1         | 1      | 0.08%   |
| XPG                            | 1         | 1      | 0.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| SanDisk SSD U100 256GB                 | 103       | 8.37%   |
| Samsung NVMe SSD Drive 512GB           | 17        | 1.38%   |
| HGST HTS721010A9E630 1TB               | 14        | 1.14%   |
| Seagate ST1000LM035-1RK172 1TB         | 13        | 1.06%   |
| Samsung SSD 860 EVO 500GB              | 13        | 1.06%   |
| Unknown MMC Card  32GB                 | 10        | 0.81%   |
| Kingston SA400S37480G 480GB SSD        | 9         | 0.73%   |
| Toshiba NVMe SSD Drive 256GB           | 8         | 0.65%   |
| Toshiba MQ01ABD100 1TB                 | 8         | 0.65%   |
| SK hynix NVMe SSD Drive 512GB          | 8         | 0.65%   |
| SanDisk NVMe SSD Drive 512GB           | 8         | 0.65%   |
| Samsung SSD 850 EVO 250GB              | 8         | 0.65%   |
| Samsung MZVLB1T0HBLR-000L2 1TB         | 8         | 0.65%   |
| Kingston SA400S37240G 240GB SSD        | 8         | 0.65%   |
| Unknown MMC Card  64GB                 | 7         | 0.57%   |
| Unknown MMC Card  16GB                 | 7         | 0.57%   |
| Toshiba MQ01ABF050 500GB               | 7         | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 7         | 0.57%   |
| SanDisk NVMe SSD Drive 1024GB          | 7         | 0.57%   |
| Patriot Burst 480GB SSD                | 7         | 0.57%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD    | 7         | 0.57%   |
| HGST HTS725050A7E630 500GB             | 7         | 0.57%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB   | 6         | 0.49%   |
| Unknown MMC Card  128GB                | 6         | 0.49%   |
| Toshiba NVMe SSD Drive 512GB           | 6         | 0.49%   |
| Toshiba MQ04ABF100 1TB                 | 6         | 0.49%   |
| Seagate ST500LT012-1DG142 500GB        | 6         | 0.49%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 6         | 0.49%   |
| Kingston SA400S37120G 120GB SSD        | 6         | 0.49%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 5         | 0.41%   |
| WDC WD10JPVX-22JC3T0 1TB               | 5         | 0.41%   |
| Seagate ST9500420AS 500GB              | 5         | 0.41%   |
| Seagate ST500LM000-1EJ162 500GB        | 5         | 0.41%   |
| Seagate ST2000LM007-1R8174 2TB         | 5         | 0.41%   |
| SanDisk DF4032  32GB                   | 5         | 0.41%   |
| Samsung SSD 970 EVO 1TB                | 5         | 0.41%   |
| Samsung SSD 850 EVO 500GB              | 5         | 0.41%   |
| Intel NVMe SSD Drive 512GB             | 5         | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 4         | 0.32%   |
| WDC WD3200BEVT-22ZCT0 320GB            | 4         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 115       | 160    | 33.72%  |
| WDC                 | 75        | 89     | 21.99%  |
| Toshiba             | 56        | 64     | 16.42%  |
| Hitachi             | 44        | 52     | 12.9%   |
| HGST                | 37        | 46     | 10.85%  |
| Fujitsu             | 7         | 7      | 2.05%   |
| Samsung Electronics | 2         | 2      | 0.59%   |
| ASMedia             | 2         | 3      | 0.59%   |
| Unknown             | 1         | 1      | 0.29%   |
| IBM/Hitachi         | 1         | 1      | 0.29%   |
| ASMT                | 1         | 1      | 0.29%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 128       | 130    | 28.76%  |
| Samsung Electronics | 89        | 112    | 20%     |
| Kingston            | 52        | 57     | 11.69%  |
| WDC                 | 21        | 30     | 4.72%   |
| A-DATA Technology   | 21        | 24     | 4.72%   |
| Patriot             | 17        | 22     | 3.82%   |
| Crucial             | 17        | 27     | 3.82%   |
| Micron Technology   | 15        | 20     | 3.37%   |
| Intel               | 13        | 15     | 2.92%   |
| SK hynix            | 11        | 11     | 2.47%   |
| Toshiba             | 9         | 11     | 2.02%   |
| Transcend           | 7         | 7      | 1.57%   |
| LITEONIT            | 7         | 9      | 1.57%   |
| China               | 6         | 7      | 1.35%   |
| LITEON              | 4         | 4      | 0.9%    |
| Apacer              | 4         | 6      | 0.9%    |
| Apple               | 3         | 3      | 0.67%   |
| Verbatim            | 2         | 2      | 0.45%   |
| JMicron Technology  | 2         | 2      | 0.45%   |
| Gigabyte Technology | 2         | 5      | 0.45%   |
| USB3.0              | 1         | 1      | 0.22%   |
| UMIS                | 1         | 1      | 0.22%   |
| UMAX                | 1         | 1      | 0.22%   |
| TO Exter            | 1         | 2      | 0.22%   |
| Team                | 1         | 1      | 0.22%   |
| ShanDianZhe         | 1         | 1      | 0.22%   |
| Seagate             | 1         | 1      | 0.22%   |
| OCZ                 | 1         | 4      | 0.22%   |
| Netac               | 1         | 1      | 0.22%   |
| Mushkin             | 1         | 1      | 0.22%   |
| Hewlett-Packard     | 1         | 1      | 0.22%   |
| GOODRAM             | 1         | 2      | 0.22%   |
| CT500MX5            | 1         | 1      | 0.22%   |
| ASMT                | 1         | 1      | 0.22%   |
| ADATA SU            | 1         | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 427       | 524    | 37.2%   |
| HDD     | 331       | 426    | 28.83%  |
| NVMe    | 314       | 413    | 27.35%  |
| MMC     | 70        | 92     | 6.1%    |
| Unknown | 6         | 8      | 0.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 690       | 918    | 62.39%  |
| NVMe | 314       | 412    | 28.39%  |
| MMC  | 70        | 92     | 6.33%   |
| SAS  | 32        | 41     | 2.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 561       | 694    | 75.2%   |
| 0.51-1.0   | 169       | 229    | 22.65%  |
| 1.01-2.0   | 15        | 25     | 2.01%   |
| 3.01-4.0   | 1         | 2      | 0.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 262       | 25.22%  |
| 251-500        | 235       | 22.62%  |
| 1-20           | 176       | 16.94%  |
| 501-1000       | 139       | 13.38%  |
| 51-100         | 78        | 7.51%   |
| 1001-2000      | 47        | 4.52%   |
| 21-50          | 45        | 4.33%   |
| Unknown        | 35        | 3.37%   |
| More than 3000 | 16        | 1.54%   |
| 2001-3000      | 6         | 0.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 509       | 46.91%  |
| 21-50          | 140       | 12.9%   |
| 101-250        | 136       | 12.53%  |
| 51-100         | 115       | 10.6%   |
| 251-500        | 88        | 8.11%   |
| 501-1000       | 37        | 3.41%   |
| Unknown        | 35        | 3.23%   |
| 1001-2000      | 15        | 1.38%   |
| More than 3000 | 6         | 0.55%   |
| 2001-3000      | 4         | 0.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB                           | 103       | 103    | 63.58%  |
| HGST HTS725050A7E630 500GB                       | 3         | 3      | 1.85%   |
| Toshiba MQ01ABD075 752GB                         | 2         | 2      | 1.23%   |
| SK hynix BC711 HFM512GD3JX013N 512GB             | 2         | 2      | 1.23%   |
| Seagate ST9500420AS 500GB                        | 2         | 3      | 1.23%   |
| Seagate ST1000LX015-1U7172 1TB                   | 2         | 2      | 1.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 2         | 2      | 1.23%   |
| HGST HTS721010A9E630 1TB                         | 2         | 2      | 1.23%   |
| WDC WD7500BPVT-22HXZT3 752GB                     | 1         | 1      | 0.62%   |
| WDC WD6400BPVT-60HXZT1 640GB                     | 1         | 1      | 0.62%   |
| WDC WD3200BEVT-60ZCT1 320GB                      | 1         | 1      | 0.62%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 0.62%   |
| Toshiba MK8037GSX 80GB                           | 1         | 1      | 0.62%   |
| Toshiba MK6465GSXN 640GB                         | 1         | 1      | 0.62%   |
| Toshiba MK5056GSY 500GB                          | 1         | 1      | 0.62%   |
| Toshiba MK2552GSX 250GB                          | 1         | 1      | 0.62%   |
| Toshiba MK1234GSX 120GB                          | 1         | 1      | 0.62%   |
| SK hynix HFS256G3BTND-N210A 256GB SSD            | 1         | 1      | 0.62%   |
| SK hynix HFS128G39TND-N210A 128GB SSD            | 1         | 1      | 0.62%   |
| Seagate ST980811AS 80GB                          | 1         | 1      | 0.62%   |
| Seagate ST9500420ASG 500GB                       | 1         | 1      | 0.62%   |
| Seagate ST9320423AS 320GB                        | 1         | 1      | 0.62%   |
| Seagate ST9250410ASG 250GB                       | 1         | 1      | 0.62%   |
| Seagate ST9250315AS 250GB                        | 1         | 1      | 0.62%   |
| Seagate ST9200420ASG 200GB                       | 1         | 1      | 0.62%   |
| Seagate ST500LM000-SSHD-8GB                      | 1         | 1      | 0.62%   |
| Seagate ST320LT007-9ZV142 320GB                  | 1         | 1      | 0.62%   |
| Seagate ST2000LM007-1R8174 2TB                   | 1         | 1      | 0.62%   |
| SanDisk SD8SBAT-032G-1006 32GB SSD               | 1         | 1      | 0.62%   |
| SanDisk SD7SB3Q256G1002 256GB SSD                | 1         | 1      | 0.62%   |
| Samsung Electronics SSD 850 EVO 1TB              | 1         | 1      | 0.62%   |
| Samsung Electronics MZVLB1T0HALR-000L2 1TB       | 1         | 1      | 0.62%   |
| Samsung Electronics MZ7TE256HMHP-000L7 256GB SSD | 1         | 1      | 0.62%   |
| Micron Technology 1100 SATA 256GB SSD            | 1         | 1      | 0.62%   |
| LITEONIT LAT-128M2S 128GB SSD                    | 1         | 1      | 0.62%   |
| Kingston SHFS37A120G 120GB SSD                   | 1         | 1      | 0.62%   |
| Intel SSDSCKJF240A5L 240GB                       | 1         | 1      | 0.62%   |
| Intel SSDSA2M160G2LE 160GB                       | 1         | 1      | 0.62%   |
| IBM/Hitachi IC25N060ATMR04-0 64GB                | 1         | 1      | 0.62%   |
| Hitachi HTS725016A9A364 160GB                    | 1         | 1      | 0.62%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 105       | 105    | 64.81%  |
| Seagate             | 15        | 16     | 9.26%   |
| Hitachi             | 9         | 9      | 5.56%   |
| Toshiba             | 8         | 8      | 4.94%   |
| HGST                | 6         | 6      | 3.7%    |
| SK hynix            | 4         | 4      | 2.47%   |
| WDC                 | 3         | 3      | 1.85%   |
| Samsung Electronics | 3         | 3      | 1.85%   |
| Intel               | 2         | 2      | 1.23%   |
| A-DATA Technology   | 2         | 3      | 1.23%   |
| Micron Technology   | 1         | 1      | 0.62%   |
| LITEONIT            | 1         | 1      | 0.62%   |
| Kingston            | 1         | 1      | 0.62%   |
| IBM/Hitachi         | 1         | 1      | 0.62%   |
| Fujitsu             | 1         | 1      | 0.62%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor      | Notebooks | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 15        | 16     | 34.88%  |
| Hitachi     | 9         | 9      | 20.93%  |
| Toshiba     | 8         | 8      | 18.6%   |
| HGST        | 6         | 6      | 13.95%  |
| WDC         | 3         | 3      | 6.98%   |
| IBM/Hitachi | 1         | 1      | 2.33%   |
| Fujitsu     | 1         | 1      | 2.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 116       | 117    | 71.6%   |
| HDD  | 43        | 44     | 26.54%  |
| NVMe | 3         | 3      | 1.85%   |

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
| Detected | 550       | 883    | 52.73%  |
| Works    | 332       | 416    | 31.83%  |
| Malfunc  | 161       | 164    | 15.44%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 717       | 62.46%  |
| AMD                              | 108       | 9.41%   |
| Samsung Electronics              | 105       | 9.15%   |
| SanDisk                          | 53        | 4.62%   |
| SK hynix                         | 41        | 3.57%   |
| Toshiba America Info Systems     | 32        | 2.79%   |
| Micron Technology                | 20        | 1.74%   |
| Kingston Technology Company      | 15        | 1.31%   |
| KIOXIA                           | 13        | 1.13%   |
| Phison Electronics               | 11        | 0.96%   |
| Silicon Motion                   | 5         | 0.44%   |
| Union Memory (Shenzhen)          | 3         | 0.26%   |
| Silicon Integrated Systems [SiS] | 3         | 0.26%   |
| Micron/Crucial Technology        | 3         | 0.26%   |
| Lite-On Technology               | 3         | 0.26%   |
| ADATA Technology                 | 3         | 0.26%   |
| Solid State Storage Technology   | 2         | 0.17%   |
| Nvidia                           | 2         | 0.17%   |
| Lenovo                           | 2         | 0.17%   |
| ASMedia Technology               | 2         | 0.17%   |
| VIA Technologies                 | 1         | 0.09%   |
| Marvell Technology Group         | 1         | 0.09%   |
| JMicron Technology               | 1         | 0.09%   |
| Biwin Storage Technology         | 1         | 0.09%   |
| Apple                            | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 154       | 12.51%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 84        | 6.82%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 67        | 5.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 61        | 4.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 50        | 4.06%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 48        | 3.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 44        | 3.57%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 31        | 2.52%   |
| Samsung NVMe SSD Controller 980                                                  | 30        | 2.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 27        | 2.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 27        | 2.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 25        | 2.03%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 24        | 1.95%   |
| Intel Volume Management Device NVMe RAID Controller                              | 24        | 1.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 21        | 1.71%   |
| Micron Non-Volatile memory controller                                            | 20        | 1.62%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 19        | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 19        | 1.54%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 17        | 1.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 16        | 1.3%    |
| Intel Comet Lake SATA AHCI Controller                                            | 15        | 1.22%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 15        | 1.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 14        | 1.14%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 13        | 1.06%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 13        | 1.06%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 13        | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 13        | 1.06%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 12        | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 12        | 0.97%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 12        | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 11        | 0.89%   |
| SK hynix BC511                                                                   | 9         | 0.73%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 9         | 0.73%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 9         | 0.73%   |
| SK hynix Non-Volatile memory controller                                          | 8         | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 8         | 0.65%   |
| Intel Tiger Lake-LP SATA Controller                                              | 8         | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 8         | 0.65%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 8         | 0.65%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 8         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 720       | 60.66%  |
| NVMe | 317       | 26.71%  |
| IDE  | 76        | 6.4%    |
| RAID | 74        | 6.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 833       | 83.05%  |
| AMD    | 170       | 16.95%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz             | 103       | 10.26%  |
| Intel Core i5-2520M CPU @ 2.50GHz             | 16        | 1.59%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 15        | 1.49%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 15        | 1.49%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 13        | 1.29%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 12        | 1.2%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 12        | 1.2%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 1.2%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 12        | 1.2%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 11        | 1.1%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 10        | 1%      |
| Intel Core i7-9750H CPU @ 2.60GHz             | 9         | 0.9%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.9%    |
| Intel Core i7-10850H CPU @ 2.70GHz            | 9         | 0.9%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 9         | 0.9%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 9         | 0.9%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 0.9%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 0.9%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 0.8%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 0.8%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 8         | 0.8%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 0.8%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 7         | 0.7%    |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 7         | 0.7%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 7         | 0.7%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 7         | 0.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 7         | 0.7%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 7         | 0.7%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 7         | 0.7%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 6         | 0.6%    |
| Intel Core i7-4600U CPU @ 2.10GHz             | 6         | 0.6%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 6         | 0.6%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 6         | 0.6%    |
| Intel Core i3-2310M CPU @ 2.10GHz             | 6         | 0.6%    |
| Intel Celeron N4000 CPU @ 1.10GHz             | 6         | 0.6%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 6         | 0.6%    |
| Intel Core i7-9850H CPU @ 2.60GHz             | 5         | 0.5%    |
| Intel Core i7-8665U CPU @ 1.90GHz             | 5         | 0.5%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 5         | 0.5%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 5         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 318       | 31.67%  |
| Intel Core i5           | 202       | 20.12%  |
| Intel Core 2 Duo        | 67        | 6.67%   |
| Intel Core i3           | 57        | 5.68%   |
| Intel Celeron           | 56        | 5.58%   |
| Other                   | 53        | 5.28%   |
| AMD Ryzen 5             | 37        | 3.69%   |
| AMD Ryzen 7             | 34        | 3.39%   |
| Intel Pentium           | 25        | 2.49%   |
| AMD Ryzen 7 PRO         | 21        | 2.09%   |
| Intel Atom              | 20        | 1.99%   |
| AMD A6                  | 11        | 1.1%    |
| AMD A4                  | 7         | 0.7%    |
| Intel Pentium Dual-Core | 6         | 0.6%    |
| Intel Celeron M         | 6         | 0.6%    |
| AMD A8                  | 6         | 0.6%    |
| Intel Pentium Silver    | 5         | 0.5%    |
| Intel Core 2            | 5         | 0.5%    |
| Intel Celeron Dual-Core | 5         | 0.5%    |
| Intel Pentium M         | 4         | 0.4%    |
| AMD Turion II           | 4         | 0.4%    |
| AMD Ryzen 9             | 4         | 0.4%    |
| AMD Ryzen 5 PRO         | 4         | 0.4%    |
| AMD E                   | 4         | 0.4%    |
| Intel Xeon              | 3         | 0.3%    |
| Intel Pentium Dual      | 3         | 0.3%    |
| Intel Genuine           | 3         | 0.3%    |
| AMD Turion 64 X2 Mobile | 3         | 0.3%    |
| AMD Ryzen 3             | 3         | 0.3%    |
| AMD Mobile Sempron      | 3         | 0.3%    |
| AMD FX                  | 3         | 0.3%    |
| AMD E1                  | 3         | 0.3%    |
| AMD A10                 | 3         | 0.3%    |
| Intel Core i9           | 2         | 0.2%    |
| AMD E2                  | 2         | 0.2%    |
| AMD Athlon X2           | 2         | 0.2%    |
| AMD Athlon II Dual-Core | 2         | 0.2%    |
| AMD A12                 | 2         | 0.2%    |
| Intel Core m5           | 1         | 0.1%    |
| Intel Core Duo          | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 543       | 54.08%  |
| 4       | 299       | 29.78%  |
| 6       | 69        | 6.87%   |
| 8       | 59        | 5.88%   |
| 1       | 28        | 2.79%   |
| 14      | 2         | 0.2%    |
| 10      | 2         | 0.2%    |
| 12      | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1003      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 728       | 72.58%  |
| 1       | 274       | 27.32%  |
| Unknown | 1         | 0.1%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 971       | 96.43%  |
| 32-bit         | 18        | 1.79%   |
| Unknown        | 17        | 1.69%   |
| 64-bit         | 1         | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 169       | 16.33%  |
| 0x206a7    | 156       | 15.07%  |
| 0x306a9    | 47        | 4.54%   |
| 0x806ec    | 37        | 3.57%   |
| 0x806ea    | 37        | 3.57%   |
| 0x1067a    | 35        | 3.38%   |
| 0x406e3    | 32        | 3.09%   |
| 0x906ea    | 27        | 2.61%   |
| 0x806c1    | 27        | 2.61%   |
| 0x40651    | 27        | 2.61%   |
| 0x306c3    | 26        | 2.51%   |
| 0x08600106 | 25        | 2.42%   |
| 0x806e9    | 24        | 2.32%   |
| 0x306d4    | 20        | 1.93%   |
| 0x6fd      | 19        | 1.84%   |
| 0x0a50000c | 16        | 1.55%   |
| 0x30678    | 15        | 1.45%   |
| 0x20655    | 14        | 1.35%   |
| 0xa0652    | 13        | 1.26%   |
| 0x906e9    | 11        | 1.06%   |
| 0x706a1    | 11        | 1.06%   |
| 0x506e3    | 11        | 1.06%   |
| 0x406c3    | 10        | 0.97%   |
| 0x10676    | 10        | 0.97%   |
| 0x08608103 | 10        | 0.97%   |
| 0x08108102 | 10        | 0.97%   |
| 0x906ed    | 9         | 0.87%   |
| 0x406c4    | 9         | 0.87%   |
| 0x506c9    | 8         | 0.77%   |
| 0x806eb    | 7         | 0.68%   |
| 0x706e5    | 7         | 0.68%   |
| 0x20652    | 7         | 0.68%   |
| 0x106e5    | 7         | 0.68%   |
| 0x10661    | 7         | 0.68%   |
| 0x08600104 | 7         | 0.68%   |
| 0x08600103 | 7         | 0.68%   |
| 0x07030105 | 7         | 0.68%   |
| 0x06006705 | 7         | 0.68%   |
| 0x6e8      | 6         | 0.58%   |
| 0x06001119 | 6         | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 180       | 17.95%  |
| SandyBridge      | 166       | 16.55%  |
| Haswell          | 64        | 6.38%   |
| IvyBridge        | 59        | 5.88%   |
| Penryn           | 56        | 5.58%   |
| Skylake          | 49        | 4.89%   |
| Zen 2            | 43        | 4.29%   |
| Silvermont       | 43        | 4.29%   |
| Core             | 38        | 3.79%   |
| TigerLake        | 33        | 3.29%   |
| Westmere         | 28        | 2.79%   |
| Broadwell        | 25        | 2.49%   |
| Zen 3            | 24        | 2.39%   |
| Unknown          | 21        | 2.09%   |
| Zen+             | 17        | 1.69%   |
| CometLake        | 17        | 1.69%   |
| Goldmont plus    | 15        | 1.5%    |
| Excavator        | 14        | 1.4%    |
| P6               | 11        | 1.1%    |
| Icelake          | 11        | 1.1%    |
| Puma             | 9         | 0.9%    |
| Nehalem          | 9         | 0.9%    |
| Goldmont         | 9         | 0.9%    |
| Piledriver       | 8         | 0.8%    |
| Bonnell          | 8         | 0.8%    |
| K10              | 7         | 0.7%    |
| Bobcat           | 7         | 0.7%    |
| K8 Hammer        | 6         | 0.6%    |
| Zen              | 5         | 0.5%    |
| Steamroller      | 5         | 0.5%    |
| Alderlake Hybrid | 5         | 0.5%    |
| Tremont          | 4         | 0.4%    |
| K8 & K10 hybrid  | 3         | 0.3%    |
| Jaguar           | 3         | 0.3%    |
| K10 Llano        | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 746       | 59.97%  |
| Nvidia                           | 250       | 20.1%   |
| AMD                              | 244       | 19.61%  |
| Silicon Integrated Systems [SiS] | 2         | 0.16%   |
| VIA Technologies                 | 1         | 0.08%   |
| ATI Technologies                 | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 158       | 12.15%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 55        | 4.23%   |
| Intel UHD Graphics 620                                                                   | 44        | 3.38%   |
| AMD Renoir                                                                               | 42        | 3.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 33        | 2.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 33        | 2.54%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 32        | 2.46%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 31        | 2.38%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 29        | 2.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 28        | 2.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 27        | 2.08%   |
| Intel HD Graphics 620                                                                    | 26        | 2%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 23        | 1.77%   |
| Intel HD Graphics 5500                                                                   | 22        | 1.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 22        | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 21        | 1.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 19        | 1.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 19        | 1.46%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 18        | 1.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 17        | 1.31%   |
| Intel Core Processor Integrated Graphics Controller                                      | 16        | 1.23%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 14        | 1.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 14        | 1.08%   |
| AMD Lucienne                                                                             | 14        | 1.08%   |
| Intel HD Graphics 630                                                                    | 13        | 1%      |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 13        | 1%      |
| Intel HD Graphics 530                                                                    | 12        | 0.92%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 12        | 0.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 11        | 0.85%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 11        | 0.85%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 11        | 0.85%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 0.77%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 10        | 0.77%   |
| Nvidia GP108M [GeForce MX150]                                                            | 9         | 0.69%   |
| Intel HD Graphics 500                                                                    | 9         | 0.69%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 9         | 0.69%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 8         | 0.62%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 8         | 0.62%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 8         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 519       | 51.74%  |
| Intel + Nvidia | 181       | 18.05%  |
| 1 x AMD        | 163       | 16.25%  |
| 1 x Nvidia     | 55        | 5.48%   |
| Intel + AMD    | 46        | 4.59%   |
| 2 x AMD        | 22        | 2.19%   |
| AMD + Nvidia   | 14        | 1.4%    |
| 1 x SiS        | 2         | 0.2%    |
| 1 x VIA        | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 869       | 86.12%  |
| Proprietary | 112       | 11.1%   |
| Unknown     | 28        | 2.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 661       | 64.42%  |
| 1.01-2.0   | 130       | 12.67%  |
| 0.01-0.5   | 128       | 12.48%  |
| 0.51-1.0   | 53        | 5.17%   |
| 3.01-4.0   | 36        | 3.51%   |
| 5.01-6.0   | 12        | 1.17%   |
| 2.01-3.0   | 3         | 0.29%   |
| 7.01-8.0   | 2         | 0.19%   |
| 8.01-16.0  | 1         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 210       | 17.4%   |
| LG Display              | 156       | 12.92%  |
| Chimei Innolux          | 125       | 10.36%  |
| Samsung Electronics     | 112       | 9.28%   |
| CPT                     | 105       | 8.7%    |
| BOE                     | 103       | 8.53%   |
| Dell                    | 57        | 4.72%   |
| Eizo                    | 39        | 3.23%   |
| Sharp                   | 36        | 2.98%   |
| Lenovo                  | 30        | 2.49%   |
| Chi Mei Optoelectronics | 28        | 2.32%   |
| Hewlett-Packard         | 23        | 1.91%   |
| PANDA                   | 19        | 1.57%   |
| Philips                 | 16        | 1.33%   |
| Goldstar                | 16        | 1.33%   |
| BenQ                    | 16        | 1.33%   |
| LG Philips              | 15        | 1.24%   |
| AOC                     | 10        | 0.83%   |
| Acer                    | 10        | 0.83%   |
| Sony                    | 6         | 0.5%    |
| Quanta Display          | 6         | 0.5%    |
| InfoVision              | 6         | 0.5%    |
| Iiyama                  | 6         | 0.5%    |
| CSO                     | 6         | 0.5%    |
| Panasonic               | 5         | 0.41%   |
| Apple                   | 5         | 0.41%   |
| Ancor Communications    | 5         | 0.41%   |
| Toshiba                 | 4         | 0.33%   |
| HannStar                | 4         | 0.33%   |
| ANX                     | 3         | 0.25%   |
| OEM                     | 2         | 0.17%   |
| NEC Computers           | 2         | 0.17%   |
| JDI                     | 2         | 0.17%   |
| Hitachi                 | 2         | 0.17%   |
| Fujitsu Siemens         | 2         | 0.17%   |
| DENON                   | 2         | 0.17%   |
| ViewSonic               | 1         | 0.08%   |
| Vestel Elektronik       | 1         | 0.08%   |
| TMX                     | 1         | 0.08%   |
| TCL                     | 1         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                      | 103       | 8.31%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                         | 37        | 2.98%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 11        | 0.89%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 10        | 0.81%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 10        | 0.81%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 8         | 0.65%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 7         | 0.56%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 6         | 0.48%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch      | 6         | 0.48%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 6         | 0.48%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                         | 6         | 0.48%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 6         | 0.48%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                   | 5         | 0.4%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 5         | 0.4%    |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 5         | 0.4%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 5         | 0.4%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 5         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 5         | 0.4%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 5         | 0.4%    |
| BOE LCD Monitor BOE07BB 1920x1080 309x173mm 13.9-inch                     | 5         | 0.4%    |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 5         | 0.4%    |
| AU Optronics LCD Monitor AUO34ED 1920x1080 344x193mm 15.5-inch            | 5         | 0.4%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 5         | 0.4%    |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 5         | 0.4%    |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 5         | 0.4%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch         | 4         | 0.32%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                   | 4         | 0.32%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 4         | 0.32%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 4         | 0.32%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch               | 4         | 0.32%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                         | 4         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 4         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 4         | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO1520 1680x1050 331x207mm 15.4-inch | 4         | 0.32%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch             | 4         | 0.32%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch             | 4         | 0.32%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 4         | 0.32%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 4         | 0.32%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch             | 4         | 0.32%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 4         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 466       | 41.42%  |
| 1366x768 (WXGA)    | 206       | 18.31%  |
| 1600x900 (HD+)     | 165       | 14.67%  |
| 3840x2160 (4K)     | 76        | 6.76%   |
| 1280x800 (WXGA)    | 58        | 5.16%   |
| 2560x1440 (QHD)    | 33        | 2.93%   |
| 1920x1200 (WUXGA)  | 28        | 2.49%   |
| 1680x1050 (WSXGA+) | 14        | 1.24%   |
| 1440x900 (WXGA+)   | 13        | 1.16%   |
| 2560x1600          | 8         | 0.71%   |
| 1280x1024 (SXGA)   | 8         | 0.71%   |
| 1024x768 (XGA)     | 5         | 0.44%   |
| 1024x600           | 5         | 0.44%   |
| 1360x768           | 4         | 0.36%   |
| 800x1280           | 3         | 0.27%   |
| 3840x2400          | 3         | 0.27%   |
| 3456x2160          | 3         | 0.27%   |
| 3000x2000          | 3         | 0.27%   |
| 2880x1800          | 3         | 0.27%   |
| 2160x1440          | 3         | 0.27%   |
| 1920x540           | 3         | 0.27%   |
| Unknown            | 3         | 0.27%   |
| 3840x1200          | 2         | 0.18%   |
| 3440x1440          | 2         | 0.18%   |
| 3200x1800 (QHD+)   | 2         | 0.18%   |
| 8320x2160          | 1         | 0.09%   |
| 5760x2160          | 1         | 0.09%   |
| 3840x1080          | 1         | 0.09%   |
| 2160x1350          | 1         | 0.09%   |
| 1920x515           | 1         | 0.09%   |
| 1400x1050          | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 420       | 34.6%   |
| 13      | 235       | 19.36%  |
| 14      | 131       | 10.79%  |
| 17      | 77        | 6.34%   |
| 24      | 68        | 5.6%    |
| 31      | 49        | 4.04%   |
| 27      | 44        | 3.62%   |
| 23      | 35        | 2.88%   |
| 12      | 27        | 2.22%   |
| 21      | 20        | 1.65%   |
| 11      | 20        | 1.65%   |
| Unknown | 15        | 1.24%   |
| 22      | 8         | 0.66%   |
| 16      | 8         | 0.66%   |
| 10      | 7         | 0.58%   |
| 84      | 6         | 0.49%   |
| 18      | 6         | 0.49%   |
| 20      | 5         | 0.41%   |
| 19      | 5         | 0.41%   |
| 25      | 4         | 0.33%   |
| 32      | 3         | 0.25%   |
| 26      | 3         | 0.25%   |
| 72      | 2         | 0.16%   |
| 54      | 2         | 0.16%   |
| 49      | 2         | 0.16%   |
| 43      | 2         | 0.16%   |
| 40      | 2         | 0.16%   |
| 34      | 2         | 0.16%   |
| 33      | 2         | 0.16%   |
| 60      | 1         | 0.08%   |
| 52      | 1         | 0.08%   |
| 46      | 1         | 0.08%   |
| 38      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 617       | 51.72%  |
| 201-300     | 217       | 18.19%  |
| 501-600     | 134       | 11.23%  |
| 351-400     | 90        | 7.54%   |
| 601-700     | 54        | 4.53%   |
| 401-500     | 39        | 3.27%   |
| Unknown     | 15        | 1.26%   |
| 1001-1500   | 9         | 0.75%   |
| 1501-2000   | 8         | 0.67%   |
| 701-800     | 7         | 0.59%   |
| 801-900     | 3         | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 836       | 82.61%  |
| 16/10   | 138       | 13.64%  |
| 5/4     | 8         | 0.79%   |
| 3/2     | 8         | 0.79%   |
| Unknown | 8         | 0.79%   |
| 4/3     | 6         | 0.59%   |
| 0.62    | 3         | 0.3%    |
| 3.20    | 2         | 0.2%    |
| 21/9    | 2         | 0.2%    |
| 3.73    | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 414       | 34.27%  |
| 81-90          | 209       | 17.3%   |
| 71-80          | 156       | 12.91%  |
| 201-250        | 101       | 8.36%   |
| 121-130        | 60        | 4.97%   |
| 351-500        | 56        | 4.64%   |
| 301-350        | 47        | 3.89%   |
| 61-70          | 27        | 2.24%   |
| 251-300        | 27        | 2.24%   |
| 51-60          | 20        | 1.66%   |
| Unknown        | 15        | 1.24%   |
| More than 1000 | 13        | 1.08%   |
| 131-140        | 13        | 1.08%   |
| 151-200        | 12        | 0.99%   |
| 141-150        | 10        | 0.83%   |
| 111-120        | 9         | 0.75%   |
| 41-50          | 7         | 0.58%   |
| 501-1000       | 6         | 0.5%    |
| 91-100         | 6         | 0.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 564       | 49.21%  |
| 101-120       | 242       | 21.12%  |
| 51-100        | 224       | 19.55%  |
| 161-240       | 67        | 5.85%   |
| More than 240 | 24        | 2.09%   |
| Unknown       | 15        | 1.31%   |
| 1-50          | 10        | 0.87%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 756       | 72.9%   |
| 2     | 217       | 20.93%  |
| 0     | 32        | 3.09%   |
| 3     | 31        | 2.99%   |
| 4     | 1         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 530       | 32.22%  |
| Realtek Semiconductor                  | 414       | 25.17%  |
| Qualcomm Atheros                       | 315       | 19.15%  |
| Samsung Electronics                    | 104       | 6.32%   |
| Broadcom                               | 92        | 5.59%   |
| Broadcom Limited                       | 38        | 2.31%   |
| MediaTek                               | 20        | 1.22%   |
| Lenovo                                 | 20        | 1.22%   |
| Marvell Technology Group               | 18        | 1.09%   |
| Dell                                   | 13        | 0.79%   |
| TP-Link                                | 9         | 0.55%   |
| DisplayLink                            | 9         | 0.55%   |
| ASIX Electronics                       | 9         | 0.55%   |
| Sierra Wireless                        | 8         | 0.49%   |
| Ralink                                 | 7         | 0.43%   |
| Ralink Technology                      | 5         | 0.3%    |
| Qualcomm Atheros Communications        | 5         | 0.3%    |
| Attansic Technology                    | 4         | 0.24%   |
| Hewlett-Packard                        | 3         | 0.18%   |
| Ericsson Business Mobile Networks      | 3         | 0.18%   |
| Spreadtrum Communications              | 2         | 0.12%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.12%   |
| Huawei Technologies                    | 2         | 0.12%   |
| D-Link                                 | 2         | 0.12%   |
| Xiaomi                                 | 1         | 0.06%   |
| VIA Technologies                       | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| Qualcomm                               | 1         | 0.06%   |
| ICS Advent                             | 1         | 0.06%   |
| Fujitsu Siemens Computers              | 1         | 0.06%   |
| Foxconn / Hon Hai                      | 1         | 0.06%   |
| Fibocom                                | 1         | 0.06%   |
| ASUSTek Computer                       | 1         | 0.06%   |
| Arduino SA                             | 1         | 0.06%   |
| AMD                                    | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 273       | 13.89%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 125       | 6.36%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 102       | 5.19%   |
| Intel Wi-Fi 6 AX200                                               | 63        | 3.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 56        | 2.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 49        | 2.49%   |
| Intel Wireless 8265 / 8275                                        | 46        | 2.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 40        | 2.04%   |
| Intel Wireless 7260                                               | 39        | 1.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 37        | 1.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 33        | 1.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 31        | 1.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 29        | 1.48%   |
| Intel Wireless 8260                                               | 27        | 1.37%   |
| Intel Wi-Fi 6 AX201                                               | 24        | 1.22%   |
| Intel Ethernet Connection (4) I219-LM                             | 23        | 1.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 23        | 1.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 22        | 1.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 22        | 1.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 20        | 1.02%   |
| Intel Wireless 3165                                               | 20        | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 19        | 0.97%   |
| Intel Wireless 7265                                               | 18        | 0.92%   |
| Intel 82567LM Gigabit Network Connection                          | 18        | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 18        | 0.92%   |
| Intel WiFi Link 5100                                              | 16        | 0.81%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 16        | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 15        | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14        | 0.71%   |
| Intel Wireless 3160                                               | 14        | 0.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 13        | 0.66%   |
| Intel Ethernet Connection I217-LM                                 | 13        | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 13        | 0.66%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 13        | 0.66%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 12        | 0.61%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 0.61%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 0.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 12        | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 11        | 0.56%   |
| Intel Ethernet Connection (6) I219-V                              | 11        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 518       | 50.44%  |
| Qualcomm Atheros                | 280       | 27.26%  |
| Realtek Semiconductor           | 88        | 8.57%   |
| Broadcom                        | 54        | 5.26%   |
| Broadcom Limited                | 21        | 2.04%   |
| MediaTek                        | 19        | 1.85%   |
| TP-Link                         | 8         | 0.78%   |
| Sierra Wireless                 | 8         | 0.78%   |
| Ralink                          | 7         | 0.68%   |
| Dell                            | 7         | 0.68%   |
| Ralink Technology               | 5         | 0.49%   |
| Qualcomm Atheros Communications | 5         | 0.49%   |
| Hewlett-Packard                 | 2         | 0.19%   |
| Qualcomm                        | 1         | 0.1%    |
| Fujitsu Siemens Computers       | 1         | 0.1%    |
| Fibocom                         | 1         | 0.1%    |
| D-Link                          | 1         | 0.1%    |
| ASUSTek Computer                | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 125       | 12.14%  |
| Intel Wi-Fi 6 AX200                                                     | 63        | 6.12%   |
| Intel Wireless 8265 / 8275                                              | 46        | 4.47%   |
| Intel Wireless 7260                                                     | 39        | 3.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 37        | 3.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 33        | 3.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 31        | 3.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 29        | 2.82%   |
| Intel Wireless 8260                                                     | 27        | 2.62%   |
| Intel Wi-Fi 6 AX201                                                     | 24        | 2.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 23        | 2.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 22        | 2.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 22        | 2.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 20        | 1.94%   |
| Intel Wireless 3165                                                     | 20        | 1.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 19        | 1.84%   |
| Intel Wireless 7265                                                     | 18        | 1.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 18        | 1.75%   |
| Intel WiFi Link 5100                                                    | 16        | 1.55%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 16        | 1.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 15        | 1.46%   |
| Intel Wireless 3160                                                     | 14        | 1.36%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 13        | 1.26%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 13        | 1.26%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 12        | 1.17%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 10        | 0.97%   |
| Intel Ultimate N WiFi Link 5300                                         | 10        | 0.97%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 10        | 0.97%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 9         | 0.87%   |
| Intel Centrino Wireless-N 2230                                          | 9         | 0.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.78%   |
| Intel Wireless-AC 9260                                                  | 8         | 0.78%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 8         | 0.78%   |
| Intel Centrino Advanced-N 6235                                          | 8         | 0.78%   |
| Intel Centrino Advanced-N 6200                                          | 8         | 0.78%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 7         | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 7         | 0.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 375       | 41.71%  |
| Intel                            | 216       | 24.03%  |
| Samsung Electronics              | 104       | 11.57%  |
| Qualcomm Atheros                 | 71        | 7.9%    |
| Broadcom                         | 44        | 4.89%   |
| Lenovo                           | 20        | 2.22%   |
| Marvell Technology Group         | 18        | 2%      |
| Broadcom Limited                 | 17        | 1.89%   |
| DisplayLink                      | 9         | 1%      |
| ASIX Electronics                 | 9         | 1%      |
| Attansic Technology              | 4         | 0.44%   |
| Spreadtrum Communications        | 2         | 0.22%   |
| Silicon Integrated Systems [SiS] | 2         | 0.22%   |
| Xiaomi                           | 1         | 0.11%   |
| VIA Technologies                 | 1         | 0.11%   |
| TP-Link                          | 1         | 0.11%   |
| MediaTek                         | 1         | 0.11%   |
| ICS Advent                       | 1         | 0.11%   |
| Huawei Technologies              | 1         | 0.11%   |
| Foxconn / Hon Hai                | 1         | 0.11%   |
| D-Link                           | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 273       | 29.8%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 102       | 11.14%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 56        | 6.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 49        | 5.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 40        | 4.37%   |
| Intel Ethernet Connection (4) I219-LM                                          | 23        | 2.51%   |
| Intel 82567LM Gigabit Network Connection                                       | 18        | 1.97%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 14        | 1.53%   |
| Intel Ethernet Connection I217-LM                                              | 13        | 1.42%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 13        | 1.42%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 12        | 1.31%   |
| Intel Ethernet Connection I219-LM                                              | 12        | 1.31%   |
| Intel Ethernet Connection I218-LM                                              | 12        | 1.31%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 11        | 1.2%    |
| Intel Ethernet Connection (6) I219-V                                           | 11        | 1.2%    |
| Intel Ethernet Connection (7) I219-LM                                          | 10        | 1.09%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 8         | 0.87%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 7         | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 7         | 0.76%   |
| Intel Ethernet Connection (6) I219-LM                                          | 7         | 0.76%   |
| Intel Ethernet Connection (4) I219-V                                           | 7         | 0.76%   |
| Intel Ethernet Connection (3) I218-LM                                          | 7         | 0.76%   |
| Intel 82577LM Gigabit Network Connection                                       | 7         | 0.76%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 7         | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 6         | 0.66%   |
| Intel Ethernet Connection (10) I219-LM                                         | 6         | 0.66%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 5         | 0.55%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 5         | 0.55%   |
| Intel Ethernet Connection I219-V                                               | 5         | 0.55%   |
| Intel Ethernet Connection (11) I219-LM                                         | 5         | 0.55%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 5         | 0.55%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 5         | 0.55%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 4         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 4         | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 4         | 0.44%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 4         | 0.44%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 4         | 0.44%   |
| Intel Ethernet Connection I217-V                                               | 4         | 0.44%   |
| Intel 82566MM Gigabit Network Connection                                       | 4         | 0.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 4         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 985       | 53.1%   |
| Ethernet | 851       | 45.88%  |
| Modem    | 18        | 0.97%   |
| Unknown  | 1         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 732       | 68.86%  |
| Ethernet | 331       | 31.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 688       | 68.46%  |
| 1     | 287       | 28.56%  |
| 0     | 19        | 1.89%   |
| 3     | 11        | 1.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 887       | 87.39%  |
| Yes  | 128       | 12.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 363       | 50.07%  |
| Qualcomm Atheros Communications | 60        | 8.28%   |
| Realtek Semiconductor           | 57        | 7.86%   |
| IMC Networks                    | 51        | 7.03%   |
| Broadcom                        | 47        | 6.48%   |
| Foxconn / Hon Hai               | 33        | 4.55%   |
| Lite-On Technology              | 32        | 4.41%   |
| Hewlett-Packard                 | 22        | 3.03%   |
| Dell                            | 14        | 1.93%   |
| ASUSTek Computer                | 13        | 1.79%   |
| Alps Electric                   | 5         | 0.69%   |
| Realtek                         | 4         | 0.55%   |
| Ralink                          | 4         | 0.55%   |
| MediaTek                        | 4         | 0.55%   |
| Apple                           | 4         | 0.55%   |
| Toshiba                         | 3         | 0.41%   |
| Cambridge Silicon Radio         | 3         | 0.41%   |
| Ralink Technology               | 2         | 0.28%   |
| Micro Star International        | 1         | 0.14%   |
| Fujitsu Siemens Computers       | 1         | 0.14%   |
| Foxconn International           | 1         | 0.14%   |
| Askey Computer                  | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 156       | 21.52%  |
| Intel AX200 Bluetooth                                                               | 63        | 8.69%   |
| Intel AX201 Bluetooth                                                               | 61        | 8.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 45        | 6.21%   |
| Realtek Bluetooth Radio                                                             | 38        | 5.24%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 22        | 3.03%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 18        | 2.48%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 14        | 1.93%   |
| IMC Networks Bluetooth Device                                                       | 14        | 1.93%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 13        | 1.79%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 12        | 1.66%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 12        | 1.66%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 12        | 1.66%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 10        | 1.38%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 10        | 1.38%   |
| Broadcom BCM2045 Bluetooth                                                          | 10        | 1.38%   |
| IMC Networks Wireless_Device                                                        | 9         | 1.24%   |
| IMC Networks Bluetooth Radio                                                        | 9         | 1.24%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 9         | 1.24%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 8         | 1.1%    |
| Dell DW375 Bluetooth Module                                                         | 8         | 1.1%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 8         | 1.1%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 0.97%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 7         | 0.97%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 7         | 0.97%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 7         | 0.97%   |
| Qualcomm Atheros Bluetooth                                                          | 6         | 0.83%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 6         | 0.83%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 6         | 0.83%   |
| Realtek Bluetooth Radio                                                             | 4         | 0.55%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 0.55%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 4         | 0.55%   |
| Lite-On Bluetooth Device                                                            | 4         | 0.55%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 0.55%   |
| Intel AX210 Bluetooth                                                               | 4         | 0.55%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 4         | 0.55%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 0.55%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 4         | 0.55%   |
| Broadcom HP Portable SoftSailing                                                    | 4         | 0.55%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 4         | 0.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 813       | 65.62%  |
| AMD                                  | 200       | 16.14%  |
| Nvidia                               | 108       | 8.72%   |
| Lenovo                               | 21        | 1.69%   |
| C-Media Electronics                  | 18        | 1.45%   |
| Realtek Semiconductor                | 16        | 1.29%   |
| Hewlett-Packard                      | 7         | 0.56%   |
| Logitech                             | 6         | 0.48%   |
| GN Netcom                            | 6         | 0.48%   |
| Plantronics                          | 4         | 0.32%   |
| JMTek                                | 4         | 0.32%   |
| Creative Technology                  | 4         | 0.32%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.24%   |
| RODE Microphones                     | 2         | 0.16%   |
| DSEA A/S                             | 2         | 0.16%   |
| Dell                                 | 2         | 0.16%   |
| BEHRINGER International              | 2         | 0.16%   |
| Yealink Network Technology           | 1         | 0.08%   |
| VIA Technologies                     | 1         | 0.08%   |
| Trust                                | 1         | 0.08%   |
| Toshiba                              | 1         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.08%   |
| Syntek                               | 1         | 0.08%   |
| Samson Technologies                  | 1         | 0.08%   |
| Razer USA                            | 1         | 0.08%   |
| Orbbec 3D Technology International   | 1         | 0.08%   |
| M-Audio                              | 1         | 0.08%   |
| Kingston Technology                  | 1         | 0.08%   |
| Harman                               | 1         | 0.08%   |
| GYROCOM C&C                          | 1         | 0.08%   |
| Generalplus Technology               | 1         | 0.08%   |
| Focusrite-Novation                   | 1         | 0.08%   |
| ELMCU                                | 1         | 0.08%   |
| DigiTech                             | 1         | 0.08%   |
| Datelink Technology                  | 1         | 0.08%   |
| Conexant Systems                     | 1         | 0.08%   |
| AudioQuest                           | 1         | 0.08%   |
| Apple                                | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 159       | 10.82%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 106       | 7.22%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 101       | 6.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 67        | 4.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 65        | 4.42%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 53        | 3.61%   |
| Intel Cannon Lake PCH cAVS                                                                        | 38        | 2.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 37        | 2.52%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 33        | 2.25%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 33        | 2.25%   |
| Intel 8 Series HD Audio Controller                                                                | 33        | 2.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 32        | 2.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 31        | 2.11%   |
| AMD FCH Azalia Controller                                                                         | 29        | 1.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 27        | 1.84%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 27        | 1.84%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 26        | 1.77%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 25        | 1.7%    |
| Intel Broadwell-U Audio Controller                                                                | 25        | 1.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 22        | 1.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 22        | 1.5%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 18        | 1.23%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 17        | 1.16%   |
| Realtek Semiconductor USB Audio                                                                   | 16        | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 16        | 1.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 16        | 1.09%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 15        | 1.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 15        | 1.02%   |
| Intel Comet Lake PCH cAVS                                                                         | 14        | 0.95%   |
| Intel CM238 HD Audio Controller                                                                   | 14        | 0.95%   |
| AMD Kabini HDMI/DP Audio                                                                          | 14        | 0.95%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 14        | 0.95%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 12        | 0.82%   |
| AMD High Definition Audio Controller                                                              | 12        | 0.82%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 11        | 0.75%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 0.61%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 9         | 0.61%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 9         | 0.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 9         | 0.61%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 9         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 157       | 23.54%  |
| SK hynix            | 139       | 20.84%  |
| Elpida              | 116       | 17.39%  |
| Micron Technology   | 86        | 12.89%  |
| Kingston            | 59        | 8.85%   |
| Unknown             | 36        | 5.4%    |
| Crucial             | 19        | 2.85%   |
| Ramaxel Technology  | 17        | 2.55%   |
| A-DATA Technology   | 10        | 1.5%    |
| Corsair             | 8         | 1.2%    |
| Unknown (ABCD)      | 6         | 0.9%    |
| Nanya Technology    | 5         | 0.75%   |
| Patriot             | 3         | 0.45%   |
| Transcend           | 2         | 0.3%    |
| Unknown (AB)        | 1         | 0.15%   |
| OnBoard             | 1         | 0.15%   |
| Nayna               | 1         | 0.15%   |
| Golden Empire       | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 103       | 14.78%  |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 1.58%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 9         | 1.29%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 1%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 7         | 1%      |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 1%      |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 1%      |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 1%      |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 7         | 1%      |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.86%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 5         | 0.72%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.72%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.72%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.72%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.72%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.72%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 5         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.57%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.57%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 4         | 0.57%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 4         | 0.57%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 4         | 0.57%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.57%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.57%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.57%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.57%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s       | 4         | 0.57%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 4         | 0.57%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 4         | 0.57%   |
| Kingston RAM 99U5428-101.A00LF 8GB SODIMM DDR3 1600MT/s          | 4         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 0.43%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.43%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 3200MT/s                  | 3         | 0.43%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 800MT/s          | 3         | 0.43%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.43%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.43%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.43%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 247       | 42.81%  |
| DDR4    | 246       | 42.63%  |
| LPDDR4  | 32        | 5.55%   |
| DDR2    | 22        | 3.81%   |
| LPDDR3  | 17        | 2.95%   |
| SDRAM   | 8         | 1.39%   |
| DDR     | 3         | 0.52%   |
| LPDDR5  | 1         | 0.17%   |
| Unknown | 1         | 0.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 526       | 90.38%  |
| Row Of Chips | 43        | 7.39%   |
| Chip         | 10        | 1.72%   |
| DIMM         | 2         | 0.34%   |
| Unknown      | 1         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 193       | 31.23%  |
| 2048  | 159       | 25.73%  |
| 4096  | 138       | 22.33%  |
| 16384 | 99        | 16.02%  |
| 1024  | 14        | 2.27%   |
| 32768 | 10        | 1.62%   |
| 512   | 2         | 0.32%   |
| 6144  | 1         | 0.16%   |
| 3072  | 1         | 0.16%   |
| 256   | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1333    | 119       | 19.44%  |
| 3200    | 102       | 16.67%  |
| 2667    | 101       | 16.5%   |
| 1600    | 95        | 15.52%  |
| 2400    | 50        | 8.17%   |
| 1334    | 27        | 4.41%   |
| 2133    | 25        | 4.08%   |
| 4267    | 12        | 1.96%   |
| Unknown | 12        | 1.96%   |
| 1867    | 10        | 1.63%   |
| 3266    | 7         | 1.14%   |
| 1067    | 7         | 1.14%   |
| 667     | 7         | 1.14%   |
| 800     | 6         | 0.98%   |
| 1066    | 5         | 0.82%   |
| 4266    | 4         | 0.65%   |
| 4199    | 4         | 0.65%   |
| 975     | 4         | 0.65%   |
| 533     | 4         | 0.65%   |
| 3733    | 3         | 0.49%   |
| 8400    | 2         | 0.33%   |
| 2048    | 2         | 0.33%   |
| 6400    | 1         | 0.16%   |
| 2933    | 1         | 0.16%   |
| 1639    | 1         | 0.16%   |
| 1400    | 1         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 33.33%  |
| Prolific Technology | 1         | 33.33%  |
| Canon               | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Samsung M2070 Series          | 1         | 33.33%  |
| Prolific PL2305 Parallel Port | 1         | 33.33%  |
| Canon LBP3010/LBP3018/LBP3050 | 1         | 33.33%  |

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
| Chicony Electronics                    | 218       | 27.84%  |
| Realtek Semiconductor                  | 83        | 10.6%   |
| Acer                                   | 77        | 9.83%   |
| IMC Networks                           | 72        | 9.2%    |
| Microdia                               | 63        | 8.05%   |
| Sunplus Innovation Technology          | 49        | 6.26%   |
| Lite-On Technology                     | 38        | 4.85%   |
| Cheng Uei Precision Industry (Foxlink) | 31        | 3.96%   |
| Quanta                                 | 29        | 3.7%    |
| Suyin                                  | 28        | 3.58%   |
| Syntek                                 | 20        | 2.55%   |
| Ricoh                                  | 10        | 1.28%   |
| Lenovo                                 | 10        | 1.28%   |
| Alcor Micro                            | 10        | 1.28%   |
| Apple                                  | 8         | 1.02%   |
| Samsung Electronics                    | 5         | 0.64%   |
| Primax Electronics                     | 4         | 0.51%   |
| Logitech                               | 4         | 0.51%   |
| Sonix Technology                       | 2         | 0.26%   |
| Luxvisions Innotech Limited            | 2         | 0.26%   |
| Intel                                  | 2         | 0.26%   |
| Z-Star Microelectronics                | 1         | 0.13%   |
| Unknown                                | 1         | 0.13%   |
| Sunplus Technology                     | 1         | 0.13%   |
| Silicon Motion                         | 1         | 0.13%   |
| Ruision                                | 1         | 0.13%   |
| Pixart Imaging                         | 1         | 0.13%   |
| Orbbec 3D Technology International     | 1         | 0.13%   |
| Microsoft                              | 1         | 0.13%   |
| KYE Systems (Mouse Systems)            | 1         | 0.13%   |
| Goodong Industry                       | 1         | 0.13%   |
| Genesys Logic                          | 1         | 0.13%   |
| GEMBIRD                                | 1         | 0.13%   |
| eMPIA Technology                       | 1         | 0.13%   |
| Elecom                                 | 1         | 0.13%   |
| DJKANA19IDX53W                         | 1         | 0.13%   |
| Creative Technology                    | 1         | 0.13%   |
| ALi                                    | 1         | 0.13%   |
| Unknown                                | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 56        | 7.12%   |
| IMC Networks Integrated Camera                      | 32        | 4.07%   |
| Microdia Integrated_Webcam_HD                       | 31        | 3.94%   |
| Realtek Integrated_Webcam_HD                        | 29        | 3.68%   |
| Chicony HD WebCam                                   | 23        | 2.92%   |
| Chicony HP HD Camera                                | 22        | 2.8%    |
| Acer Lenovo EasyCamera                              | 20        | 2.54%   |
| Lite-On HP HD Camera                                | 17        | 2.16%   |
| Acer Integrated Camera                              | 17        | 2.16%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 14        | 1.78%   |
| Sunplus Integrated_Webcam_HD                        | 12        | 1.52%   |
| Realtek USB Camera                                  | 12        | 1.52%   |
| Chicony Integrated Camera (1280x720@30)             | 12        | 1.52%   |
| Lite-On Integrated Camera                           | 11        | 1.4%    |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 10        | 1.27%   |
| Chicony USB2.0 VGA UVC WebCam                       | 9         | 1.14%   |
| Realtek Integrated Webcam HD                        | 8         | 1.02%   |
| Quanta HP HD Camera                                 | 8         | 1.02%   |
| Quanta HD User Facing                               | 8         | 1.02%   |
| Microdia Integrated Webcam                          | 8         | 1.02%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 8         | 1.02%   |
| Acer SunplusIT Integrated Camera                    | 8         | 1.02%   |
| Syntek Lenovo EasyCamera                            | 7         | 0.89%   |
| Syntek Integrated Camera                            | 7         | 0.89%   |
| Lenovo Integrated Webcam                            | 7         | 0.89%   |
| Chicony Lenovo EasyCamera                           | 7         | 0.89%   |
| Sunplus Laptop Integrated WebCam HD                 | 6         | 0.76%   |
| Sunplus HD WebCam                                   | 6         | 0.76%   |
| Sunplus Asus Webcam                                 | 6         | 0.76%   |
| Realtek USB2.0 VGA UVC WebCam                       | 6         | 0.76%   |
| Chicony HP HD Webcam                                | 6         | 0.76%   |
| Apple iPhone 5/5C/5S/6/SE                           | 6         | 0.76%   |
| Samsung Galaxy series, misc. (MTP mode)             | 5         | 0.64%   |
| Realtek USB2.0 HD UVC WebCam                        | 5         | 0.64%   |
| Chicony FJ Camera                                   | 5         | 0.64%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 5         | 0.64%   |
| Alcor Micro USB 2.0 Camera                          | 5         | 0.64%   |
| Acer Lenovo Integrated Webcam                       | 5         | 0.64%   |
| Suyin 1.3M HD WebCam                                | 4         | 0.51%   |
| Sunplus Integrated_Webcam_FHD                       | 4         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 81        | 34.32%  |
| Synaptics                  | 76        | 32.2%   |
| Shenzhen Goodix Technology | 27        | 11.44%  |
| AuthenTec                  | 26        | 11.02%  |
| Upek                       | 12        | 5.08%   |
| Elan Microelectronics      | 8         | 3.39%   |
| LighTuning Technology      | 5         | 2.12%   |
| Microsoft                  | 1         | 0.42%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 24        | 10.17%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 22        | 9.32%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 17        | 7.2%    |
| Shenzhen Goodix  Fingerprint Device                                        | 16        | 6.78%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 5.51%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 5.08%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 11        | 4.66%   |
| AuthenTec AES2810                                                          | 11        | 4.66%   |
| Unknown                                                                    | 10        | 4.24%   |
| Validity Sensors VFS491                                                    | 8         | 3.39%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 3.39%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 2.97%   |
| AuthenTec AES1600                                                          | 7         | 2.97%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 2.54%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 2.54%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 2.12%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 2.12%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 2.12%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 2.12%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 2.12%   |
| Elan ELAN:Fingerprint                                                      | 5         | 2.12%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.69%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1.27%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.27%   |
| Synaptics  WBDI                                                            | 3         | 1.27%   |
| Elan ELAN:ARM-M4                                                           | 3         | 1.27%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 0.85%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 0.85%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.42%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.42%   |
| Synaptics WBDI Device                                                      | 1         | 0.42%   |
| Microsoft Fingerprint Reader                                               | 1         | 0.42%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.42%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.42%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 52        | 53.61%  |
| Alcor Micro               | 26        | 26.8%   |
| O2 Micro                  | 9         | 9.28%   |
| Lenovo                    | 5         | 5.15%   |
| SCM Microsystems          | 2         | 2.06%   |
| Upek                      | 1         | 1.03%   |
| Purism, SPC               | 1         | 1.03%   |
| Aladdin Knowledge Systems | 1         | 1.03%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 26        | 26.8%   |
| Broadcom 58200                                                               | 16        | 16.49%  |
| Broadcom BCM5880 Secure Applications Processor                               | 14        | 14.43%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 11.34%  |
| Broadcom 5880                                                                | 11        | 11.34%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 8.25%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 5.15%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 2.06%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 1.03%   |
| Purism, SPC Librem Key                                                       | 1         | 1.03%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.03%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.03%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 595       | 58.22%  |
| 1     | 320       | 31.31%  |
| 2     | 84        | 8.22%   |
| 3     | 18        | 1.76%   |
| 4     | 3         | 0.29%   |
| 5     | 2         | 0.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 232       | 42.49%  |
| Graphics card            | 88        | 16.12%  |
| Chipcard                 | 86        | 15.75%  |
| Net/wireless             | 38        | 6.96%   |
| Multimedia controller    | 21        | 3.85%   |
| Storage                  | 16        | 2.93%   |
| Camera                   | 13        | 2.38%   |
| Bluetooth                | 13        | 2.38%   |
| Communication controller | 11        | 2.01%   |
| Card reader              | 7         | 1.28%   |
| Flash memory             | 6         | 1.1%    |
| Net/ethernet             | 5         | 0.92%   |
| Modem                    | 5         | 0.92%   |
| Sound                    | 4         | 0.73%   |
| Storage/ata              | 1         | 0.18%   |


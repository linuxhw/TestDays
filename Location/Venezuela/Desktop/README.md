Linux in Venezuela - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Venezuela.

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

Total: 352

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Foxconn  | P4M900-8237A                | [861a2b8a1d](https://linux-hardware.org/?probe=861a2b8a1d) | Dec 29, 2024 |
| MSI      | 970 GAMING                  | [f54e09e66e](https://linux-hardware.org/?probe=f54e09e66e) | Dec 26, 2024 |
| Biostar  | G41D3                       | [cdc2e02364](https://linux-hardware.org/?probe=cdc2e02364) | Dec 21, 2024 |
| MSI      | H61M-P20                    | [f15424c030](https://linux-hardware.org/?probe=f15424c030) | Dec 19, 2024 |
| HP       | 8054                        | [ab28ff6e7c](https://linux-hardware.org/?probe=ab28ff6e7c) | Dec 19, 2024 |
| Biostar  | H510MHP                     | [6aca496f13](https://linux-hardware.org/?probe=6aca496f13) | Dec 15, 2024 |
| Dell     | 0F6X5P A00                  | [059cf0cd47](https://linux-hardware.org/?probe=059cf0cd47) | Dec 15, 2024 |
| Dell     | 0F6X5P A00                  | [f9eae65d13](https://linux-hardware.org/?probe=f9eae65d13) | Dec 14, 2024 |
| Dell     | 02YYK5 A01                  | [ce9189a198](https://linux-hardware.org/?probe=ce9189a198) | Dec 13, 2024 |
| ASRock   | H61M-DGS                    | [8bec785ad2](https://linux-hardware.org/?probe=8bec785ad2) | Dec 11, 2024 |
| MSI      | Z97 PC Mate                 | [767c9d535d](https://linux-hardware.org/?probe=767c9d535d) | Nov 30, 2024 |
| Foxconn  | 2AB7                        | [974b516304](https://linux-hardware.org/?probe=974b516304) | Nov 05, 2024 |
| Gigabyte | GA-E350N-USB3               | [7225d38fe2](https://linux-hardware.org/?probe=7225d38fe2) | Oct 25, 2024 |
| Gigabyte | GA-E350N-USB3               | [95f022084d](https://linux-hardware.org/?probe=95f022084d) | Oct 25, 2024 |
| HP       | 8056                        | [35e6ca7c18](https://linux-hardware.org/?probe=35e6ca7c18) | Oct 22, 2024 |
| MSI      | MS-7071                     | [6cf8497c89](https://linux-hardware.org/?probe=6cf8497c89) | Oct 16, 2024 |
| ECS      | H61H2-CM                    | [f61d208d37](https://linux-hardware.org/?probe=f61d208d37) | Oct 15, 2024 |
| ECS      | H61H2-CM                    | [ccc66822bb](https://linux-hardware.org/?probe=ccc66822bb) | Oct 15, 2024 |
| Foxconn  | 2AB7                        | [02962e01b7](https://linux-hardware.org/?probe=02962e01b7) | Oct 15, 2024 |
| langchao | IPM41-D3                    | [e4d59a71f7](https://linux-hardware.org/?probe=e4d59a71f7) | Oct 03, 2024 |
| JGINYUE  | H61M-H V2.1                 | [a787ad78be](https://linux-hardware.org/?probe=a787ad78be) | Sep 19, 2024 |
| ASUSTek  | PRIME B560M-A AC            | [39388eabb2](https://linux-hardware.org/?probe=39388eabb2) | Sep 17, 2024 |
| JGINYUE  | H61M-H V2.1                 | [2d83d05c41](https://linux-hardware.org/?probe=2d83d05c41) | Sep 12, 2024 |
| ASUSTek  | Rampage IV EXTREME          | [9fa3766008](https://linux-hardware.org/?probe=9fa3766008) | Sep 04, 2024 |
| langchao | IPM41-D3                    | [04b83f5ac9](https://linux-hardware.org/?probe=04b83f5ac9) | Sep 02, 2024 |
| Lenovo   | ThinkCentre M57e 9482CP1    | [e4fb5c4a3d](https://linux-hardware.org/?probe=e4fb5c4a3d) | Aug 29, 2024 |
| Dell     | 0KV62T A02                  | [1639a61d9e](https://linux-hardware.org/?probe=1639a61d9e) | Aug 20, 2024 |
| ASRock   | G41M-VS3                    | [552d12bdb3](https://linux-hardware.org/?probe=552d12bdb3) | Aug 08, 2024 |
| Gigabyte | GA-A75M-UD2H                | [3476d0940e](https://linux-hardware.org/?probe=3476d0940e) | Jul 30, 2024 |
| Apple    | Mac-F221BEC8                | [86964648e4](https://linux-hardware.org/?probe=86964648e4) | Jul 07, 2024 |
| Apple    | Mac-F221BEC8                | [71135286a0](https://linux-hardware.org/?probe=71135286a0) | Jul 07, 2024 |
| Lenovo   | ThinkServer TS140           | [b3c5f15f82](https://linux-hardware.org/?probe=b3c5f15f82) | Jul 05, 2024 |
| Intel    | H61                         | [b2b27a6e2f](https://linux-hardware.org/?probe=b2b27a6e2f) | Jul 04, 2024 |
| Intel    | H61                         | [dbdd8fce44](https://linux-hardware.org/?probe=dbdd8fce44) | Jul 04, 2024 |
| Intel    | H61                         | [9b38e848e2](https://linux-hardware.org/?probe=9b38e848e2) | Jul 04, 2024 |
| Intel    | H61                         | [53ca9b056d](https://linux-hardware.org/?probe=53ca9b056d) | Jul 04, 2024 |
| Intel    | H61                         | [37c8512569](https://linux-hardware.org/?probe=37c8512569) | Jun 28, 2024 |
| HP       | 805A                        | [7da9603ff0](https://linux-hardware.org/?probe=7da9603ff0) | Jun 26, 2024 |
| Foxconn  | 45GM/45CM/45CM-S            | [8acebd9a23](https://linux-hardware.org/?probe=8acebd9a23) | Jun 20, 2024 |
| ASUSTek  | P8H61-M LE/CSM R2.0         | [0b8369d85f](https://linux-hardware.org/?probe=0b8369d85f) | Jun 18, 2024 |
| Inspur   | ST1020M4                    | [17bafd5383](https://linux-hardware.org/?probe=17bafd5383) | Jun 11, 2024 |
| ASUSTek  | PRIME B550-PLUS             | [8597764147](https://linux-hardware.org/?probe=8597764147) | Jun 04, 2024 |
| HP       | 805D                        | [2da284fffd](https://linux-hardware.org/?probe=2da284fffd) | May 24, 2024 |
| Foxconn  | H61MXE/-S/-V/-K             | [5b9993415a](https://linux-hardware.org/?probe=5b9993415a) | May 20, 2024 |
| Foxconn  | H61MXE/-S/-V/-K             | [2a5e6f7189](https://linux-hardware.org/?probe=2a5e6f7189) | May 16, 2024 |
| HP       | ProLiant MicroServer        | [b281402ccb](https://linux-hardware.org/?probe=b281402ccb) | May 15, 2024 |
| HP       | 8054                        | [29c27e6732](https://linux-hardware.org/?probe=29c27e6732) | May 10, 2024 |
| ECS      | H61H2-CM                    | [65f99c7e8d](https://linux-hardware.org/?probe=65f99c7e8d) | May 08, 2024 |
| Gigabyte | GA-970A-D3                  | [1ee81eb650](https://linux-hardware.org/?probe=1ee81eb650) | May 05, 2024 |
| Gigabyte | GA-970A-D3                  | [4fa09a0b8e](https://linux-hardware.org/?probe=4fa09a0b8e) | May 04, 2024 |
| MSI      | Z97 PC Mate                 | [277b1dc273](https://linux-hardware.org/?probe=277b1dc273) | May 04, 2024 |
| Dell     | 0WR7PY A04                  | [b48e977e84](https://linux-hardware.org/?probe=b48e977e84) | May 03, 2024 |
| Dell     | 040DDP A01                  | [7eea0dc663](https://linux-hardware.org/?probe=7eea0dc663) | Apr 25, 2024 |
| Gigabyte | 970A-DS3P                   | [1cc02514fd](https://linux-hardware.org/?probe=1cc02514fd) | Apr 23, 2024 |
| ASRock   | H61M-VG3                    | [caf43c2754](https://linux-hardware.org/?probe=caf43c2754) | Apr 14, 2024 |
| Pegatron | 2A73h                       | [941a2d0e0d](https://linux-hardware.org/?probe=941a2d0e0d) | Apr 10, 2024 |
| MSI      | NF725M-P43                  | [ff3656c7c8](https://linux-hardware.org/?probe=ff3656c7c8) | Apr 10, 2024 |
| ASRock   | H61M-VG3                    | [82fa2b1397](https://linux-hardware.org/?probe=82fa2b1397) | Apr 04, 2024 |
| Pegatron | 2A73h                       | [193e8e5cb1](https://linux-hardware.org/?probe=193e8e5cb1) | Mar 26, 2024 |
| ASRock   | H510M/ac                    | [37ecfed47c](https://linux-hardware.org/?probe=37ecfed47c) | Mar 25, 2024 |
| Foxconn  | 45GM/45CM/45CM-S            | [4ed069d496](https://linux-hardware.org/?probe=4ed069d496) | Mar 09, 2024 |
| HP       | 18E7                        | [a0f611e1dc](https://linux-hardware.org/?probe=a0f611e1dc) | Mar 04, 2024 |
| ASUSTek  | PRIME B450M-A II            | [e053d06a2d](https://linux-hardware.org/?probe=e053d06a2d) | Mar 04, 2024 |
| HP       | 805D                        | [a4e341ef12](https://linux-hardware.org/?probe=a4e341ef12) | Feb 27, 2024 |
| langchao | IPM41-D3                    | [7f1319de8d](https://linux-hardware.org/?probe=7f1319de8d) | Feb 25, 2024 |
| MSI      | PRO H610M-G DDR4            | [8ba60b265f](https://linux-hardware.org/?probe=8ba60b265f) | Feb 24, 2024 |
| Foxconn  | 45GM/45CM/45CM-S            | [1dab02eb79](https://linux-hardware.org/?probe=1dab02eb79) | Feb 24, 2024 |
| HP       | 805D                        | [bfe43c8f6f](https://linux-hardware.org/?probe=bfe43c8f6f) | Feb 22, 2024 |
| ASRock   | N68-VS3 UCC                 | [24a8cd9e6e](https://linux-hardware.org/?probe=24a8cd9e6e) | Feb 13, 2024 |
| ASRock   | N73V-S                      | [91167398d3](https://linux-hardware.org/?probe=91167398d3) | Feb 11, 2024 |
| ASRock   | H61M-VG3                    | [de284cc9b2](https://linux-hardware.org/?probe=de284cc9b2) | Feb 10, 2024 |
| Biostar  | P4M900-M7 FE Ver:1.0        | [f5699d9598](https://linux-hardware.org/?probe=f5699d9598) | Feb 04, 2024 |
| HP       | 3397                        | [f5180bd918](https://linux-hardware.org/?probe=f5180bd918) | Feb 02, 2024 |
| Dell     | 0YF8P5 A00                  | [c3510619ed](https://linux-hardware.org/?probe=c3510619ed) | Feb 01, 2024 |
| ECS      | H61H2-CM                    | [c439ae84ce](https://linux-hardware.org/?probe=c439ae84ce) | Jan 26, 2024 |
| Gigabyte | H61M-S2-B3                  | [cf56455a29](https://linux-hardware.org/?probe=cf56455a29) | Jan 15, 2024 |
| HP       | 8767 A                      | [88f6719b01](https://linux-hardware.org/?probe=88f6719b01) | Jan 10, 2024 |
| HP       | 8767 A                      | [b8a28f8c5f](https://linux-hardware.org/?probe=b8a28f8c5f) | Jan 10, 2024 |
| HP       | 1998                        | [8eb25518c4](https://linux-hardware.org/?probe=8eb25518c4) | Dec 23, 2023 |
| MSI      | Z97 PC Mate                 | [23a0828c28](https://linux-hardware.org/?probe=23a0828c28) | Dec 07, 2023 |
| ASRock   | H61M-VG3                    | [acf5ffd938](https://linux-hardware.org/?probe=acf5ffd938) | Dec 06, 2023 |
| ASRock   | H61M-VG3                    | [8b7f6c2f5f](https://linux-hardware.org/?probe=8b7f6c2f5f) | Nov 27, 2023 |
| ASRock   | N68C-S UCC                  | [a5b04f6fdb](https://linux-hardware.org/?probe=a5b04f6fdb) | Nov 24, 2023 |
| ASRock   | N68-VS3 FX                  | [2248b23cde](https://linux-hardware.org/?probe=2248b23cde) | Nov 22, 2023 |
| Inspur   | H110H4-EM                   | [cd9931b178](https://linux-hardware.org/?probe=cd9931b178) | Nov 22, 2023 |
| HP       | 3647h                       | [9b0451eab9](https://linux-hardware.org/?probe=9b0451eab9) | Nov 15, 2023 |
| HP       | 3647h                       | [d6de3838ec](https://linux-hardware.org/?probe=d6de3838ec) | Nov 15, 2023 |
| ASRock   | N68-VS3 FX                  | [4d61ab4747](https://linux-hardware.org/?probe=4d61ab4747) | Nov 14, 2023 |
| ASRock   | AM2NF6G-VSTA                | [6ea7323880](https://linux-hardware.org/?probe=6ea7323880) | Nov 11, 2023 |
| ASRock   | AM2NF6G-VSTA                | [71a3f3197c](https://linux-hardware.org/?probe=71a3f3197c) | Nov 11, 2023 |
| ECS      | A890GXM-A2                  | [0b51da062f](https://linux-hardware.org/?probe=0b51da062f) | Nov 06, 2023 |
| ECS      | A890GXM-A2                  | [3e5d819c23](https://linux-hardware.org/?probe=3e5d819c23) | Nov 03, 2023 |
| ECS      | A890GXM-A2                  | [9fb5c6d4d3](https://linux-hardware.org/?probe=9fb5c6d4d3) | Nov 03, 2023 |
| ASRock   | D1800M                      | [d31fadd4a5](https://linux-hardware.org/?probe=d31fadd4a5) | Oct 23, 2023 |
| HP       | 18E5                        | [95cc2c3a9c](https://linux-hardware.org/?probe=95cc2c3a9c) | Oct 22, 2023 |
| Gigabyte | B75M-D3H                    | [eb8522ff13](https://linux-hardware.org/?probe=eb8522ff13) | Oct 21, 2023 |
| Gigabyte | B75M-D3H                    | [deb1dc3eaa](https://linux-hardware.org/?probe=deb1dc3eaa) | Oct 21, 2023 |
| ASRock   | N68-VGS3 FX                 | [2a39f005cb](https://linux-hardware.org/?probe=2a39f005cb) | Oct 17, 2023 |
| Intel    | DH55HC AAE70933-501         | [447110886e](https://linux-hardware.org/?probe=447110886e) | Oct 14, 2023 |
| Lenovo   | ThinkCentre A57 9702AB7     | [3237019933](https://linux-hardware.org/?probe=3237019933) | Oct 07, 2023 |
| ECS      | H61H2-MV                    | [51ec04551f](https://linux-hardware.org/?probe=51ec04551f) | Oct 04, 2023 |
| ASUSTek  | Rampage IV EXTREME          | [def181c0e4](https://linux-hardware.org/?probe=def181c0e4) | Sep 26, 2023 |
| Gigabyte | Z68X-UD3H-B3                | [92e5dde8b3](https://linux-hardware.org/?probe=92e5dde8b3) | Sep 23, 2023 |
| ASUSTek  | PRIME B450M-A II            | [adff9fb2a8](https://linux-hardware.org/?probe=adff9fb2a8) | Sep 14, 2023 |
| Lenovo   | NO DPK                      | [0a25a3d2af](https://linux-hardware.org/?probe=0a25a3d2af) | Sep 12, 2023 |
| Biostar  | G41D3                       | [0d4f48c335](https://linux-hardware.org/?probe=0d4f48c335) | Aug 31, 2023 |
| Pegatron | 2A73h                       | [390b033780](https://linux-hardware.org/?probe=390b033780) | Aug 29, 2023 |
| Intel    | DG41TY AAE47335-301         | [1f8897e1a2](https://linux-hardware.org/?probe=1f8897e1a2) | Aug 29, 2023 |
| langchao | IPM41-D3                    | [a6b482f110](https://linux-hardware.org/?probe=a6b482f110) | Aug 27, 2023 |
| Pegatron | IPM41-D3                    | [b67fbfb529](https://linux-hardware.org/?probe=b67fbfb529) | Aug 26, 2023 |
| ASRock   | Wolfdale1333-D667           | [7dfa16eab4](https://linux-hardware.org/?probe=7dfa16eab4) | Aug 26, 2023 |
| Biostar  | G41D3C                      | [5e2c852104](https://linux-hardware.org/?probe=5e2c852104) | Aug 26, 2023 |
| Lenovo   | ThinkCentre M72e 3597A56    | [6b6d2e95f9](https://linux-hardware.org/?probe=6b6d2e95f9) | Aug 24, 2023 |
| Inspur   | H110H4-EM                   | [75ce94f0f9](https://linux-hardware.org/?probe=75ce94f0f9) | Aug 21, 2023 |
| MSI      | Z97 PC Mate                 | [bee6142eee](https://linux-hardware.org/?probe=bee6142eee) | Aug 17, 2023 |
| ECS      | H61H2-CM                    | [7e33e0f06c](https://linux-hardware.org/?probe=7e33e0f06c) | Aug 13, 2023 |
| ECS      | H61H2-CM                    | [2656581f21](https://linux-hardware.org/?probe=2656581f21) | Aug 13, 2023 |
| ECS      | H61H2-CM                    | [e2b9ff65d7](https://linux-hardware.org/?probe=e2b9ff65d7) | Aug 06, 2023 |
| Dell     | 0NKW6Y A02                  | [09ae57bb9a](https://linux-hardware.org/?probe=09ae57bb9a) | Aug 05, 2023 |
| Dell     | 0NKW6Y A02                  | [21460cac53](https://linux-hardware.org/?probe=21460cac53) | Aug 05, 2023 |
| ASRock   | N68-VS3 UCC                 | [c163ae3710](https://linux-hardware.org/?probe=c163ae3710) | Aug 04, 2023 |
| MSI      | B450M BAZOOKA V2            | [f37f2f707b](https://linux-hardware.org/?probe=f37f2f707b) | Aug 02, 2023 |
| Gigabyte | 970A-DS3P                   | [566421a903](https://linux-hardware.org/?probe=566421a903) | Jul 21, 2023 |
| Gigabyte | 970A-DS3P                   | [be9d638406](https://linux-hardware.org/?probe=be9d638406) | Jul 21, 2023 |
| Gigabyte | B450M DS3H V2               | [67db76ffed](https://linux-hardware.org/?probe=67db76ffed) | Jul 19, 2023 |
| Foxconn  | A74MX-S/A74MX-K             | [90a2c4e2d0](https://linux-hardware.org/?probe=90a2c4e2d0) | Jul 18, 2023 |
| HP       | 0A80h                       | [54635d0b1b](https://linux-hardware.org/?probe=54635d0b1b) | Jul 05, 2023 |
| Foxconn  | G41S/G41S-K                 | [21adb87fbd](https://linux-hardware.org/?probe=21adb87fbd) | Jul 04, 2023 |
| HP       | 0A80h                       | [83691b49d2](https://linux-hardware.org/?probe=83691b49d2) | Jul 03, 2023 |
| Intel    | D845GRG AAA84341-206        | [1863434dc7](https://linux-hardware.org/?probe=1863434dc7) | Jul 01, 2023 |
| Intel    | D845GRG AAA84341-206        | [7734dda00e](https://linux-hardware.org/?probe=7734dda00e) | Jun 30, 2023 |
| Pegatron | IPMIP-H55-INSPUR            | [176a1c3e01](https://linux-hardware.org/?probe=176a1c3e01) | Jun 21, 2023 |
| ECS      | A890GXM-A2                  | [722b363829](https://linux-hardware.org/?probe=722b363829) | Jun 17, 2023 |
| ASRock   | N68C-S UCC                  | [ef4a96955c](https://linux-hardware.org/?probe=ef4a96955c) | Jun 01, 2023 |
| ASRock   | N68C-S UCC                  | [a106c6a98a](https://linux-hardware.org/?probe=a106c6a98a) | Jun 01, 2023 |
| ECS      | A890GXM-A2                  | [c207b5f41c](https://linux-hardware.org/?probe=c207b5f41c) | May 31, 2023 |
| ASRock   | G41M-VS3                    | [166031ba4d](https://linux-hardware.org/?probe=166031ba4d) | May 31, 2023 |
| ASRock   | G41M-VS3                    | [8f55c9aa98](https://linux-hardware.org/?probe=8f55c9aa98) | May 31, 2023 |
| Foxconn  | G41MXE-V                    | [ffc74ae329](https://linux-hardware.org/?probe=ffc74ae329) | May 21, 2023 |
| langchao | IPM41-D3                    | [2f659faa92](https://linux-hardware.org/?probe=2f659faa92) | May 20, 2023 |
| Lenovo   | ThinkCentre A57 9702AB7     | [f045709958](https://linux-hardware.org/?probe=f045709958) | May 12, 2023 |
| Intel    | H55AD17                     | [7d393c3814](https://linux-hardware.org/?probe=7d393c3814) | May 11, 2023 |
| ASRock   | N68-VS3 FX                  | [974c00cb61](https://linux-hardware.org/?probe=974c00cb61) | May 09, 2023 |
| ASRock   | 945GCM-S                    | [940d88bfce](https://linux-hardware.org/?probe=940d88bfce) | May 06, 2023 |
| Foxconn  | G41S/G41S-K                 | [946a95c594](https://linux-hardware.org/?probe=946a95c594) | Apr 30, 2023 |
| Foxconn  | G41S/G41S-K                 | [58cebf39d1](https://linux-hardware.org/?probe=58cebf39d1) | Apr 30, 2023 |
| HP       | 18E7                        | [26ca79a633](https://linux-hardware.org/?probe=26ca79a633) | Apr 26, 2023 |
| Dell     | 0D6H9T A00                  | [fa6f088b8d](https://linux-hardware.org/?probe=fa6f088b8d) | Apr 24, 2023 |
| ECS      | H61H2-CM                    | [4396b0b045](https://linux-hardware.org/?probe=4396b0b045) | Apr 19, 2023 |
| ASRock   | H61M-DGS R2.0               | [695446a864](https://linux-hardware.org/?probe=695446a864) | Apr 17, 2023 |
| HP       | 1998                        | [8f0fef0b77](https://linux-hardware.org/?probe=8f0fef0b77) | Apr 12, 2023 |
| Biostar  | H61MHV                      | [13b4632c72](https://linux-hardware.org/?probe=13b4632c72) | Apr 10, 2023 |
| Dell     | 0KC9NP A01                  | [fdb331baab](https://linux-hardware.org/?probe=fdb331baab) | Apr 10, 2023 |
| Pegatron | 2A73h                       | [5de48bf7df](https://linux-hardware.org/?probe=5de48bf7df) | Apr 09, 2023 |
| Biostar  | G41D3                       | [969695eafd](https://linux-hardware.org/?probe=969695eafd) | Apr 06, 2023 |
| ASUSTek  | P8H61-M LX                  | [df6a8a3453](https://linux-hardware.org/?probe=df6a8a3453) | Apr 06, 2023 |
| ASRock   | A55M-HVS                    | [426d150c30](https://linux-hardware.org/?probe=426d150c30) | Apr 03, 2023 |
| Dell     | 0J3C2F A02                  | [cb6e3973c8](https://linux-hardware.org/?probe=cb6e3973c8) | Mar 23, 2023 |
| Intel    | DH67BL AAG10189-208         | [420f476f82](https://linux-hardware.org/?probe=420f476f82) | Mar 19, 2023 |
| Soncview | G41D3C                      | [877ff67a70](https://linux-hardware.org/?probe=877ff67a70) | Mar 13, 2023 |
| Gigabyte | Z690 AERO G DDR4            | [615409e462](https://linux-hardware.org/?probe=615409e462) | Mar 12, 2023 |
| Gigabyte | Z690 AERO G DDR4            | [cc778f466a](https://linux-hardware.org/?probe=cc778f466a) | Mar 11, 2023 |
| HP       | 18E5                        | [d94d167f13](https://linux-hardware.org/?probe=d94d167f13) | Mar 11, 2023 |
| ASRock   | Wolfdale1333-D667           | [7dd4939e64](https://linux-hardware.org/?probe=7dd4939e64) | Mar 03, 2023 |
| Gigabyte | A520M DS3H                  | [9a9f442174](https://linux-hardware.org/?probe=9a9f442174) | Mar 03, 2023 |
| ASRock   | N68-VGS3 FX                 | [b9fbaca53d](https://linux-hardware.org/?probe=b9fbaca53d) | Feb 23, 2023 |
| HP       | 1495                        | [627c584065](https://linux-hardware.org/?probe=627c584065) | Feb 09, 2023 |
| Dell     | 0YF8P5 A00                  | [4bb4dd8a98](https://linux-hardware.org/?probe=4bb4dd8a98) | Feb 06, 2023 |
| ASRock   | G41M-VS3                    | [d6cea67f50](https://linux-hardware.org/?probe=d6cea67f50) | Feb 05, 2023 |
| Dell     | 0J3C2F A02                  | [7cd66ad148](https://linux-hardware.org/?probe=7cd66ad148) | Feb 03, 2023 |
| ECS      | G31T-M7                     | [76be6a1404](https://linux-hardware.org/?probe=76be6a1404) | Feb 01, 2023 |
| ECS      | G31T-M7                     | [9b0f53b46c](https://linux-hardware.org/?probe=9b0f53b46c) | Feb 01, 2023 |
| Gigabyte | EP35-DS3L                   | [5be0362f3e](https://linux-hardware.org/?probe=5be0362f3e) | Jan 23, 2023 |
| Dell     | 0KC9NP A01                  | [c48a8fe525](https://linux-hardware.org/?probe=c48a8fe525) | Jan 17, 2023 |
| HP       | 1495                        | [28c3cf967d](https://linux-hardware.org/?probe=28c3cf967d) | Jan 16, 2023 |
| ASUSTek  | P5G41T-M LX V2              | [36a8e226c5](https://linux-hardware.org/?probe=36a8e226c5) | Jan 12, 2023 |
| Gigabyte | Z68XP-UD3                   | [e2f62062de](https://linux-hardware.org/?probe=e2f62062de) | Jan 09, 2023 |
| ASUSTek  | PRIME A320M-K               | [61b7eaac72](https://linux-hardware.org/?probe=61b7eaac72) | Dec 22, 2022 |
| ASRock   | N68C-S UCC                  | [279e1eacf6](https://linux-hardware.org/?probe=279e1eacf6) | Dec 22, 2022 |
| ASRock   | N68C-S UCC                  | [8d8716cdca](https://linux-hardware.org/?probe=8d8716cdca) | Dec 21, 2022 |
| ASUSTek  | PRIME A320M-K               | [de0a127527](https://linux-hardware.org/?probe=de0a127527) | Dec 16, 2022 |
| ASUSTek  | PRIME A320M-K               | [515785c9c4](https://linux-hardware.org/?probe=515785c9c4) | Dec 16, 2022 |
| ASUSTek  | PRIME A320M-K               | [a656b96d5f](https://linux-hardware.org/?probe=a656b96d5f) | Dec 05, 2022 |
| SIRAGON  | AIO-5150                    | [90476603fa](https://linux-hardware.org/?probe=90476603fa) | Dec 04, 2022 |
| ASUSTek  | PRIME A320M-K               | [6275a6ee8f](https://linux-hardware.org/?probe=6275a6ee8f) | Dec 02, 2022 |
| ASUSTek  | PRIME A320M-K               | [e1a4335a71](https://linux-hardware.org/?probe=e1a4335a71) | Dec 01, 2022 |
| ASUSTek  | PRIME A320M-K               | [906ad9a3c1](https://linux-hardware.org/?probe=906ad9a3c1) | Nov 25, 2022 |
| Biostar  | H61MGV3                     | [b252a902f4](https://linux-hardware.org/?probe=b252a902f4) | Nov 24, 2022 |
| Gigabyte | GA-78LMT-USB3               | [3469b1e624](https://linux-hardware.org/?probe=3469b1e624) | Nov 07, 2022 |
| Gigabyte | B560M DS3H V2               | [36612b5e01](https://linux-hardware.org/?probe=36612b5e01) | Nov 02, 2022 |
| Intel    | H61                         | [326fa40958](https://linux-hardware.org/?probe=326fa40958) | Nov 01, 2022 |
| ECS      | H61H2-CM                    | [792ce0e34e](https://linux-hardware.org/?probe=792ce0e34e) | Oct 31, 2022 |
| ASRock   | N68-VS3 UCC                 | [82afa0e5bc](https://linux-hardware.org/?probe=82afa0e5bc) | Oct 24, 2022 |
| Dell     | 0200DY A02                  | [8fd4b48b80](https://linux-hardware.org/?probe=8fd4b48b80) | Oct 23, 2022 |
| ECS      | A890GXM-A2                  | [d6f77b12c2](https://linux-hardware.org/?probe=d6f77b12c2) | Oct 09, 2022 |
| ECS      | H61H2-CM                    | [13ad69a13e](https://linux-hardware.org/?probe=13ad69a13e) | Sep 23, 2022 |
| ASRock   | G41M-VS3                    | [21cfcdcbdd](https://linux-hardware.org/?probe=21cfcdcbdd) | Sep 23, 2022 |
| ASRock   | 960GM-VGS3 FX               | [7c89dc4342](https://linux-hardware.org/?probe=7c89dc4342) | Sep 19, 2022 |
| ASRock   | H61M-DGS                    | [51b15f6d34](https://linux-hardware.org/?probe=51b15f6d34) | Sep 06, 2022 |
| Gigabyte | M68MT-S2                    | [b3b173a476](https://linux-hardware.org/?probe=b3b173a476) | Sep 04, 2022 |
| ASRock   | N68-VS3 UCC                 | [688dcf88c9](https://linux-hardware.org/?probe=688dcf88c9) | Aug 30, 2022 |
| ASRock   | N68-VS3 UCC                 | [4ccef99860](https://linux-hardware.org/?probe=4ccef99860) | Aug 30, 2022 |
| HP       | 0A60h                       | [d801f7cb0c](https://linux-hardware.org/?probe=d801f7cb0c) | Aug 30, 2022 |
| ASUSTek  | P5G41T-M LX V2              | [3c63953ca6](https://linux-hardware.org/?probe=3c63953ca6) | Aug 27, 2022 |
| HP       | 1497                        | [82e518a338](https://linux-hardware.org/?probe=82e518a338) | Aug 26, 2022 |
| ASUSTek  | P8H77-V LE                  | [4bd2fabdc7](https://linux-hardware.org/?probe=4bd2fabdc7) | Aug 26, 2022 |
| ASRock   | G41M-VS3                    | [659ccaca6e](https://linux-hardware.org/?probe=659ccaca6e) | Aug 22, 2022 |
| Biostar  | A780L3B                     | [62782d600f](https://linux-hardware.org/?probe=62782d600f) | Aug 14, 2022 |
| ECS      | H61H2-MV                    | [6b2a77a281](https://linux-hardware.org/?probe=6b2a77a281) | Aug 02, 2022 |
| HP       | 339A                        | [c19f3d1361](https://linux-hardware.org/?probe=c19f3d1361) | Jul 29, 2022 |
| Lenovo   | ThinkCentre M91 7516AD1     | [19660ae71a](https://linux-hardware.org/?probe=19660ae71a) | Jul 11, 2022 |
| MSI      | H81M-E33                    | [737e14fea7](https://linux-hardware.org/?probe=737e14fea7) | Jul 01, 2022 |
| Pegatron | IPPSB-DB                    | [a63cdffc5b](https://linux-hardware.org/?probe=a63cdffc5b) | Jun 26, 2022 |
| ECS      | H61H2-MV                    | [6035d3cf75](https://linux-hardware.org/?probe=6035d3cf75) | Jun 22, 2022 |
| ASRock   | H370M-HDV                   | [4d6a88cd74](https://linux-hardware.org/?probe=4d6a88cd74) | Jun 16, 2022 |
| langchao | IPM41-D3                    | [bb1a55c140](https://linux-hardware.org/?probe=bb1a55c140) | Jun 13, 2022 |
| Dell     | 0N4YC8 A00                  | [5d8aa17afc](https://linux-hardware.org/?probe=5d8aa17afc) | Jun 10, 2022 |
| Dell     | 0N4YC8 A00                  | [a502ed154f](https://linux-hardware.org/?probe=a502ed154f) | Jun 10, 2022 |
| Lenovo   | 11051CS ThinkServer TS13... | [48e6a5501d](https://linux-hardware.org/?probe=48e6a5501d) | May 26, 2022 |
| ECS      | H61H2-MV                    | [13918cd2b7](https://linux-hardware.org/?probe=13918cd2b7) | May 23, 2022 |
| IP3 Tech | TB20                        | [1cf2be0840](https://linux-hardware.org/?probe=1cf2be0840) | May 16, 2022 |
| Intel    | H61                         | [28277b5d5a](https://linux-hardware.org/?probe=28277b5d5a) | May 10, 2022 |
| ECS      | H61H2-CM                    | [00620504c7](https://linux-hardware.org/?probe=00620504c7) | Apr 27, 2022 |
| ASRock   | A320M-DGS                   | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock   | A320M-DGS                   | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| Intel    | MAHOBAY                     | [47119856f6](https://linux-hardware.org/?probe=47119856f6) | Apr 09, 2022 |
| ASRock   | G31M-S                      | [33737ec5ba](https://linux-hardware.org/?probe=33737ec5ba) | Apr 01, 2022 |
| Intel    | D945GCCR AAD78647-300       | [c3d1b55376](https://linux-hardware.org/?probe=c3d1b55376) | Mar 27, 2022 |
| ASRock   | H370M-HDV                   | [9945efc3fa](https://linux-hardware.org/?probe=9945efc3fa) | Mar 20, 2022 |
| Inspur   | Computer All in one PC V... | [5c419895c5](https://linux-hardware.org/?probe=5c419895c5) | Mar 18, 2022 |
| MSI      | 3664h                       | [e5eaec6553](https://linux-hardware.org/?probe=e5eaec6553) | Mar 08, 2022 |
| Pegatron | IPM41-D3                    | [0e8fbc26f1](https://linux-hardware.org/?probe=0e8fbc26f1) | Mar 01, 2022 |
| Pegatron | 2ACC                        | [c1127626c5](https://linux-hardware.org/?probe=c1127626c5) | Mar 01, 2022 |
| Dell     | 0PTTT9 A01                  | [89cecb62bc](https://linux-hardware.org/?probe=89cecb62bc) | Feb 17, 2022 |
| ECS      | KAM1-I                      | [be38f855ff](https://linux-hardware.org/?probe=be38f855ff) | Feb 10, 2022 |
| ASRock   | A55M-HVS                    | [c4c68e7dd1](https://linux-hardware.org/?probe=c4c68e7dd1) | Feb 08, 2022 |
| ASUSTek  | P6X58-E PRO                 | [9ee8e1ecdf](https://linux-hardware.org/?probe=9ee8e1ecdf) | Jan 30, 2022 |
| Intel    | DG41TY AAE47335-203         | [01ec1ff569](https://linux-hardware.org/?probe=01ec1ff569) | Jan 26, 2022 |
| Dell     | 0GDG8Y A00                  | [8700fd1193](https://linux-hardware.org/?probe=8700fd1193) | Jan 11, 2022 |
| ASRock   | N68-VS3 UCC                 | [b6cffe86a0](https://linux-hardware.org/?probe=b6cffe86a0) | Dec 23, 2021 |
| Gigabyte | H110M-H-CF                  | [8d19cd079a](https://linux-hardware.org/?probe=8d19cd079a) | Dec 09, 2021 |
| Gigabyte | H110M-H-CF                  | [ecd0add9b3](https://linux-hardware.org/?probe=ecd0add9b3) | Dec 09, 2021 |
| HP       | 3398                        | [5ae73e1468](https://linux-hardware.org/?probe=5ae73e1468) | Dec 07, 2021 |
| ECS      | H61H2-CM                    | [525be50825](https://linux-hardware.org/?probe=525be50825) | Nov 28, 2021 |
| Intel    | DG35EC AAE29266-205         | [89c665e43d](https://linux-hardware.org/?probe=89c665e43d) | Nov 02, 2021 |
| Intel    | DG35EC AAE29266-205         | [1046b28a41](https://linux-hardware.org/?probe=1046b28a41) | Nov 02, 2021 |
| Biostar  | P4M90-M7A Ver:1.0           | [d8875918ac](https://linux-hardware.org/?probe=d8875918ac) | Oct 16, 2021 |
| Gigabyte | Z97N-WIFI                   | [1ec421714e](https://linux-hardware.org/?probe=1ec421714e) | Oct 02, 2021 |
| HP       | 1495                        | [64cbb112e2](https://linux-hardware.org/?probe=64cbb112e2) | Oct 01, 2021 |
| ECS      | H61H2-CM                    | [4571e36b80](https://linux-hardware.org/?probe=4571e36b80) | Sep 26, 2021 |
| Foxconn  | M61PMV FAB                  | [290d3e0fd5](https://linux-hardware.org/?probe=290d3e0fd5) | Sep 14, 2021 |
| ASRock   | N68C-S UCC                  | [3da0d57fd5](https://linux-hardware.org/?probe=3da0d57fd5) | Aug 01, 2021 |
| ECS      | H61H2-M12                   | [42050ab984](https://linux-hardware.org/?probe=42050ab984) | Jul 28, 2021 |
| Foxconn  | ELA01                       | [13bcd06d5f](https://linux-hardware.org/?probe=13bcd06d5f) | Jul 23, 2021 |
| Foxconn  | ELA01                       | [a73982649a](https://linux-hardware.org/?probe=a73982649a) | Jul 22, 2021 |
| ASUSTek  | Rampage III GENE            | [ab44db5647](https://linux-hardware.org/?probe=ab44db5647) | Jul 18, 2021 |
| Lenovo   | ThinkCentre M71e 3157G6S    | [89217c2643](https://linux-hardware.org/?probe=89217c2643) | Jul 14, 2021 |
| ASUSTek  | Rampage III GENE            | [60c62c33f8](https://linux-hardware.org/?probe=60c62c33f8) | Jul 14, 2021 |
| Biostar  | G41D3                       | [673d4faa98](https://linux-hardware.org/?probe=673d4faa98) | Jul 12, 2021 |
| HP       | 3397                        | [f1a6d10d78](https://linux-hardware.org/?probe=f1a6d10d78) | Jul 08, 2021 |
| HP       | 3397                        | [e087e03e0b](https://linux-hardware.org/?probe=e087e03e0b) | Jul 08, 2021 |
| ASRock   | G41M-S3                     | [a57f28921c](https://linux-hardware.org/?probe=a57f28921c) | Jul 05, 2021 |
| ECS      | Livermore                   | [b471a4666c](https://linux-hardware.org/?probe=b471a4666c) | Jun 30, 2021 |
| Biostar  | P4M900-M7 FE Ver:1.0        | [a82bafec08](https://linux-hardware.org/?probe=a82bafec08) | Jun 29, 2021 |
| ECS      | Livermore                   | [91b29dad17](https://linux-hardware.org/?probe=91b29dad17) | Jun 23, 2021 |
| ASRock   | H61M-VS                     | [cb1c07fa68](https://linux-hardware.org/?probe=cb1c07fa68) | Jun 17, 2021 |
| langchao | IPM41-D3                    | [512537c402](https://linux-hardware.org/?probe=512537c402) | Jun 17, 2021 |
| langchao | IPM41-D3                    | [9773736b0f](https://linux-hardware.org/?probe=9773736b0f) | Jun 17, 2021 |
| ECS      | G31T-M7                     | [01ed8410e9](https://linux-hardware.org/?probe=01ed8410e9) | Jun 15, 2021 |
| Lenovo   | ThinkCentre M55E 9645BN2    | [ef91279611](https://linux-hardware.org/?probe=ef91279611) | Jun 15, 2021 |
| Biostar  | G41D3C                      | [263491c02a](https://linux-hardware.org/?probe=263491c02a) | Jun 07, 2021 |
| ECS      | H61H2-CM                    | [42960896cb](https://linux-hardware.org/?probe=42960896cb) | May 20, 2021 |
| ECS      | H61H2-CM                    | [4856303cbe](https://linux-hardware.org/?probe=4856303cbe) | May 20, 2021 |
| ASRock   | H61M-VS                     | [9e701873b1](https://linux-hardware.org/?probe=9e701873b1) | May 09, 2021 |
| ASRock   | H61M-VS                     | [59a6774cd5](https://linux-hardware.org/?probe=59a6774cd5) | May 09, 2021 |
| Pegatron | 2A73h                       | [8d84f6dc9e](https://linux-hardware.org/?probe=8d84f6dc9e) | Apr 25, 2021 |
| ASUSTek  | P5Q                         | [db04624ac3](https://linux-hardware.org/?probe=db04624ac3) | Apr 20, 2021 |
| Intel    | DG31PR AAD97573-302         | [330f034c61](https://linux-hardware.org/?probe=330f034c61) | Apr 04, 2021 |
| Intel    | DG31PR AAD97573-302         | [4cf71fac35](https://linux-hardware.org/?probe=4cf71fac35) | Apr 04, 2021 |
| Gigabyte | Z68X-UD3H-B3                | [7f2618efb7](https://linux-hardware.org/?probe=7f2618efb7) | Mar 12, 2021 |
| HP       | 1495                        | [248af9611e](https://linux-hardware.org/?probe=248af9611e) | Mar 11, 2021 |
| Dell     | 0GX297                      | [6ac3da669a](https://linux-hardware.org/?probe=6ac3da669a) | Mar 09, 2021 |
| langchao | IPM41-D3                    | [543e8d3501](https://linux-hardware.org/?probe=543e8d3501) | Mar 07, 2021 |
| langchao | IPM41-D3                    | [892f3e6658](https://linux-hardware.org/?probe=892f3e6658) | Mar 07, 2021 |
| Pegatron | NARRA5                      | [e7550259a4](https://linux-hardware.org/?probe=e7550259a4) | Mar 06, 2021 |
| Pegatron | NARRA5                      | [294b1c19fb](https://linux-hardware.org/?probe=294b1c19fb) | Feb 20, 2021 |
| ASRock   | G41M-VS3                    | [9e6a12d9e1](https://linux-hardware.org/?probe=9e6a12d9e1) | Feb 15, 2021 |
| Gigabyte | G1.Sniper B5-CF             | [e4d1cc65bc](https://linux-hardware.org/?probe=e4d1cc65bc) | Jan 27, 2021 |
| HP       | 1493                        | [febb5aee31](https://linux-hardware.org/?probe=febb5aee31) | Jan 15, 2021 |
| ASRock   | G41M-VS3                    | [e1217b1871](https://linux-hardware.org/?probe=e1217b1871) | Jan 02, 2021 |
| Pegatron | IPM41-D3                    | [4e0489bdb0](https://linux-hardware.org/?probe=4e0489bdb0) | Dec 05, 2020 |
| ASRock   | AM2NF6G-VSTA                | [5751926628](https://linux-hardware.org/?probe=5751926628) | Nov 23, 2020 |
| ASRock   | AM2NF6G-VSTA                | [812b2188d4](https://linux-hardware.org/?probe=812b2188d4) | Nov 23, 2020 |
| Biostar  | A55MLC2                     | [e195f622e4](https://linux-hardware.org/?probe=e195f622e4) | Nov 22, 2020 |
| Biostar  | A55MLC2                     | [a0456b9ad3](https://linux-hardware.org/?probe=a0456b9ad3) | Nov 22, 2020 |
| HP       | 1495                        | [72bdee2784](https://linux-hardware.org/?probe=72bdee2784) | Nov 19, 2020 |
| Foxconn  | M61PMV FAB A1               | [cb7568786f](https://linux-hardware.org/?probe=cb7568786f) | Oct 05, 2020 |
| ASUSTek  | P5G41T-M LX                 | [db328c3c01](https://linux-hardware.org/?probe=db328c3c01) | Sep 29, 2020 |
| ECS      | H61H2-CM                    | [8ae7ffac0b](https://linux-hardware.org/?probe=8ae7ffac0b) | Sep 28, 2020 |
| Unknown  | 4CoreDX90-VSTA              | [31dbedff45](https://linux-hardware.org/?probe=31dbedff45) | Sep 10, 2020 |
| Pegatron | 2A73h                       | [5f5f0bd2cf](https://linux-hardware.org/?probe=5f5f0bd2cf) | Aug 29, 2020 |
| Biostar  | N68S3B                      | [1e4d89cafe](https://linux-hardware.org/?probe=1e4d89cafe) | Aug 27, 2020 |
| MSI      | FM2-A75MA-E35               | [7f40a96159](https://linux-hardware.org/?probe=7f40a96159) | Aug 20, 2020 |
| Gigabyte | 970A-DS3P                   | [8445b18759](https://linux-hardware.org/?probe=8445b18759) | Aug 20, 2020 |
| ECS      | H61H2-CM                    | [43d0144f0a](https://linux-hardware.org/?probe=43d0144f0a) | Aug 06, 2020 |
| MSI      | K9N2 Diamond                | [07a001660f](https://linux-hardware.org/?probe=07a001660f) | Aug 04, 2020 |
| Intel    | DG31PR AAD97573-302         | [56ad5a6a22](https://linux-hardware.org/?probe=56ad5a6a22) | Jul 29, 2020 |
| ASRock   | G41M-VS3                    | [a2e742ec36](https://linux-hardware.org/?probe=a2e742ec36) | Jul 27, 2020 |
| ASRock   | G41M-VS3                    | [6786c103d7](https://linux-hardware.org/?probe=6786c103d7) | Jul 27, 2020 |
| Intel    | DG31PR AAD97573-302         | [8081f20c91](https://linux-hardware.org/?probe=8081f20c91) | Jul 25, 2020 |
| ASRock   | G41M-VS3                    | [39510acc74](https://linux-hardware.org/?probe=39510acc74) | Jul 06, 2020 |
| ASRock   | G41M-VS3                    | [eff9ad2c7d](https://linux-hardware.org/?probe=eff9ad2c7d) | Jul 05, 2020 |
| langchao | IPM41-D3                    | [a1e610807e](https://linux-hardware.org/?probe=a1e610807e) | Jun 30, 2020 |
| langchao | IPM41-D3                    | [e8c521f7e8](https://linux-hardware.org/?probe=e8c521f7e8) | Jun 25, 2020 |
| Intel    | DG33BU AAD79951-407         | [cd52689b0a](https://linux-hardware.org/?probe=cd52689b0a) | May 25, 2020 |
| Intel    | DG33BU AAD79951-407         | [d48d360c14](https://linux-hardware.org/?probe=d48d360c14) | May 25, 2020 |
| Lenovo   | ThinkCentre A55 8705AV4     | [18c81b7e8b](https://linux-hardware.org/?probe=18c81b7e8b) | May 19, 2020 |
| Lenovo   | ThinkCentre A55 8705AV4     | [cce631f67b](https://linux-hardware.org/?probe=cce631f67b) | May 19, 2020 |
| Intel    | DG41TX AAE78178-303         | [084641dbc1](https://linux-hardware.org/?probe=084641dbc1) | May 17, 2020 |
| Gigabyte | 970A-DS3P                   | [97e5a8c8da](https://linux-hardware.org/?probe=97e5a8c8da) | Apr 26, 2020 |
| Pegatron | 2A73h                       | [b3436f0ec6](https://linux-hardware.org/?probe=b3436f0ec6) | Apr 11, 2020 |
| langchao | IPM41-D3                    | [841ded939f](https://linux-hardware.org/?probe=841ded939f) | Mar 31, 2020 |
| Lenovo   | ThinkCentre A58 7515A33     | [75be0ab7ac](https://linux-hardware.org/?probe=75be0ab7ac) | Mar 26, 2020 |
| Pegatron | 2A73h                       | [1d140aa76c](https://linux-hardware.org/?probe=1d140aa76c) | Mar 07, 2020 |
| ASUSTek  | M5A99X EVO                  | [2859756e56](https://linux-hardware.org/?probe=2859756e56) | Feb 29, 2020 |
| Lenovo   | ThinkCentre XXXX 8705A84    | [b824441963](https://linux-hardware.org/?probe=b824441963) | Feb 23, 2020 |
| Lenovo   | ThinkServer TS140           | [33fc6022df](https://linux-hardware.org/?probe=33fc6022df) | Feb 06, 2020 |
| ASUSTek  | Leonite2                    | [d0d56d5609](https://linux-hardware.org/?probe=d0d56d5609) | Jan 23, 2020 |
| Lenovo   | ThinkCentre M55E 9632BU8    | [209a9171b1](https://linux-hardware.org/?probe=209a9171b1) | Dec 04, 2019 |
| Pegatron | 2A73h                       | [2371d130d0](https://linux-hardware.org/?probe=2371d130d0) | Nov 30, 2019 |
| IBM      | 8188LS4                     | [3d775f418d](https://linux-hardware.org/?probe=3d775f418d) | Oct 08, 2019 |
| Foxconn  | 8657MF-series               | [8ce7f69a15](https://linux-hardware.org/?probe=8ce7f69a15) | Oct 05, 2019 |
| IBM      | 8188LS4                     | [3fc14db446](https://linux-hardware.org/?probe=3fc14db446) | Oct 05, 2019 |
| IBM      | 8188LS4                     | [af840eb366](https://linux-hardware.org/?probe=af840eb366) | Oct 04, 2019 |
| Pegatron | 2AAE                        | [f80cb4a7f2](https://linux-hardware.org/?probe=f80cb4a7f2) | Aug 17, 2019 |
| Dell     | 0RK936                      | [060c60558b](https://linux-hardware.org/?probe=060c60558b) | Aug 08, 2019 |
| ASUSTek  | P8H61-M PRO                 | [e107cafe33](https://linux-hardware.org/?probe=e107cafe33) | Jun 07, 2019 |
| ASRock   | H67M-GE                     | [65dd091a6f](https://linux-hardware.org/?probe=65dd091a6f) | May 13, 2019 |
| Pegatron | 2AF0                        | [bebc187dbd](https://linux-hardware.org/?probe=bebc187dbd) | May 05, 2019 |
| Intel    | DG35EC AAE29266-205         | [1ddb0e459f](https://linux-hardware.org/?probe=1ddb0e459f) | Apr 26, 2019 |
| Pegatron | IPPEL-DB                    | [c73b25ed21](https://linux-hardware.org/?probe=c73b25ed21) | Apr 24, 2019 |
| Pegatron | IPPEL-DB                    | [d1941d4619](https://linux-hardware.org/?probe=d1941d4619) | Apr 24, 2019 |
| Lenovo   | H220 10028                  | [9b6593e8c6](https://linux-hardware.org/?probe=9b6593e8c6) | Apr 21, 2019 |
| ASRock   | N68C-S UCC                  | [ac39e69311](https://linux-hardware.org/?probe=ac39e69311) | Apr 21, 2019 |
| ASRock   | H67M-GE                     | [282ee52768](https://linux-hardware.org/?probe=282ee52768) | Apr 19, 2019 |
| Intel    | DH77EB AAG39073-304         | [e054fab57c](https://linux-hardware.org/?probe=e054fab57c) | Nov 24, 2018 |
| Intel    | DH77EB AAG39073-304         | [d3d5ff2e54](https://linux-hardware.org/?probe=d3d5ff2e54) | Nov 24, 2018 |
| Intel    | D946GZIS AAD66165-302       | [8d884b92fa](https://linux-hardware.org/?probe=8d884b92fa) | Sep 16, 2017 |
| Intel    | D946GZIS AAD66165-302       | [17af4fce47](https://linux-hardware.org/?probe=17af4fce47) | Sep 03, 2017 |
| Intel    | D946GZIS AAD66165-302       | [c501aaa553](https://linux-hardware.org/?probe=c501aaa553) | Sep 01, 2017 |
| ASRock   | 945GCM-S                    | [009791bef2](https://linux-hardware.org/?probe=009791bef2) | Jun 25, 2017 |
| ASRock   | ALiveNF6P-VSTA              | [270499b92c](https://linux-hardware.org/?probe=270499b92c) | Dec 29, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Debian 11          | 15       | 5.7%    |
| Ubuntu 20.04       | 14       | 5.32%   |
| Debian 12          | 12       | 4.56%   |
| Ubuntu 22.04       | 11       | 4.18%   |
| Ubuntu 18.04       | 10       | 3.8%    |
| OpenMandriva 4.3   | 10       | 3.8%    |
| OpenMandriva 23.08 | 10       | 3.8%    |
| OpenMandriva 23.03 | 9        | 3.42%   |
| Zorin 16           | 7        | 2.66%   |
| OpenMandriva 4.2   | 7        | 2.66%   |
| OpenMandriva 23.01 | 5        | 1.9%    |
| Linux Mint 21.1    | 5        | 1.9%    |
| Linux Mint 20.3    | 5        | 1.9%    |
| Arch Rolling       | 5        | 1.9%    |
| Xubuntu 18.04      | 4        | 1.52%   |
| ROSA R11           | 4        | 1.52%   |
| Linux Mint 21.3    | 4        | 1.52%   |
| Linux Mint 21.2    | 4        | 1.52%   |
| Linux Mint 20.1    | 4        | 1.52%   |
| Ubuntu 24.04       | 3        | 1.14%   |
| OpenMandriva 4.50  | 3        | 1.14%   |
| MX 21              | 3        | 1.14%   |
| Manjaro            | 3        | 1.14%   |
| Linux Mint 20      | 3        | 1.14%   |
| Linux Mint 19.3    | 3        | 1.14%   |
| Kubuntu 22.04      | 3        | 1.14%   |
| KDE neon 20.04     | 3        | 1.14%   |
| Fedora 40          | 3        | 1.14%   |
| Fedora 38          | 3        | 1.14%   |
| Debian 10          | 3        | 1.14%   |
| ArcoLinux Rolling  | 3        | 1.14%   |
| Zorin 17           | 2        | 0.76%   |
| Zorin 15           | 2        | 0.76%   |
| Xubuntu 16.04      | 2        | 0.76%   |
| Ubuntu 20.10       | 2        | 0.76%   |
| ROSA R9            | 2        | 0.76%   |
| MX 23              | 2        | 0.76%   |
| Lubuntu 22.04      | 2        | 0.76%   |
| Linux Mint 22      | 2        | 0.76%   |
| Kubuntu 20.04      | 2        | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| OpenMandriva | 47       | 18.58%  |
| Ubuntu       | 44       | 17.39%  |
| Debian       | 35       | 13.83%  |
| Linux Mint   | 31       | 12.25%  |
| ROSA         | 12       | 4.74%   |
| Zorin        | 11       | 4.35%   |
| Fedora       | 11       | 4.35%   |
| KDE neon     | 7        | 2.77%   |
| Xubuntu      | 6        | 2.37%   |
| Arch         | 6        | 2.37%   |
| Kubuntu      | 5        | 1.98%   |
| Elementary   | 5        | 1.98%   |
| Nobara       | 4        | 1.58%   |
| MX           | 4        | 1.58%   |
| Manjaro      | 4        | 1.58%   |
| ArcoLinux    | 3        | 1.19%   |
| Ubuntu MATE  | 2        | 0.79%   |
| Lubuntu      | 2        | 0.79%   |
| Xero         | 1        | 0.4%    |
| Ubuntu Unity | 1        | 0.4%    |
| Sparky       | 1        | 0.4%    |
| Solus        | 1        | 0.4%    |
| Q4OS         | 1        | 0.4%    |
| Pop!_OS      | 1        | 0.4%    |
| Pikaos       | 1        | 0.4%    |
| PCLinuxOS    | 1        | 0.4%    |
| LMDE         | 1        | 0.4%    |
| Kali         | 1        | 0.4%    |
| Garuda Linux | 1        | 0.4%    |
| Frnsf        | 1        | 0.4%    |
| Feren OS     | 1        | 0.4%    |
| Endless      | 1        | 0.4%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Desktops | Percent |
|------------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003            | 10       | 3.57%   |
| 6.2.6-desktop-1omv2390             | 9        | 3.21%   |
| 5.10.14-desktop-1omv4002           | 7        | 2.5%    |
| 6.4.8-desktop-2omv2390             | 6        | 2.14%   |
| 6.1.1-desktop-1omv2290             | 5        | 1.79%   |
| 6.4.11-desktop-1omv2390            | 4        | 1.43%   |
| 5.4.0-42-generic                   | 4        | 1.43%   |
| 6.8.0-40-generic                   | 2        | 0.71%   |
| 6.6.2-desktop-1omv2390             | 2        | 0.71%   |
| 6.5.0-28-generic                   | 2        | 0.71%   |
| 6.5.0-21-generic                   | 2        | 0.71%   |
| 6.2.0-32-generic                   | 2        | 0.71%   |
| 6.2.0-26-generic                   | 2        | 0.71%   |
| 6.1.0-26-amd64                     | 2        | 0.71%   |
| 6.1.0-21-amd64                     | 2        | 0.71%   |
| 6.1.0-18-amd64                     | 2        | 0.71%   |
| 5.8.0-55-generic                   | 2        | 0.71%   |
| 5.4.0-77-generic                   | 2        | 0.71%   |
| 5.4.0-74-generic                   | 2        | 0.71%   |
| 5.4.0-54-generic                   | 2        | 0.71%   |
| 5.4.0-26-generic                   | 2        | 0.71%   |
| 5.4.0-166-generic                  | 2        | 0.71%   |
| 5.3.0-40-generic                   | 2        | 0.71%   |
| 5.19.0-41-generic                  | 2        | 0.71%   |
| 5.19.0-35-generic                  | 2        | 0.71%   |
| 5.15.0-89-generic                  | 2        | 0.71%   |
| 5.15.0-76-generic                  | 2        | 0.71%   |
| 5.15.0-71-generic                  | 2        | 0.71%   |
| 5.15.0-67-generic                  | 2        | 0.71%   |
| 5.15.0-58-generic                  | 2        | 0.71%   |
| 5.15.0-56-generic                  | 2        | 0.71%   |
| 5.15.0-53-generic                  | 2        | 0.71%   |
| 5.15.0-46-generic                  | 2        | 0.71%   |
| 5.13.0-27-generic                  | 2        | 0.71%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 2        | 0.71%   |
| 5.10.0-8-amd64                     | 2        | 0.71%   |
| 5.10.0-16-amd64                    | 2        | 0.71%   |
| 5.10.0-14-amd64                    | 2        | 0.71%   |
| 5.10.0-11-amd64                    | 2        | 0.71%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 2        | 0.71%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 28       | 10.53%  |
| 5.15.0  | 28       | 10.53%  |
| 5.10.0  | 19       | 7.14%   |
| 4.15.0  | 19       | 7.14%   |
| 6.1.0   | 11       | 4.14%   |
| 5.16.7  | 10       | 3.76%   |
| 6.2.6   | 9        | 3.38%   |
| 6.8.0   | 8        | 3.01%   |
| 6.5.0   | 7        | 2.63%   |
| 5.10.14 | 7        | 2.63%   |
| 6.4.8   | 6        | 2.26%   |
| 5.8.0   | 6        | 2.26%   |
| 5.13.0  | 6        | 2.26%   |
| 6.2.0   | 5        | 1.88%   |
| 6.1.1   | 5        | 1.88%   |
| 5.3.0   | 5        | 1.88%   |
| 5.19.0  | 5        | 1.88%   |
| 6.4.11  | 4        | 1.5%    |
| 5.11.0  | 3        | 1.13%   |
| 5.0.0   | 3        | 1.13%   |
| 4.19.0  | 3        | 1.13%   |
| 6.6.2   | 2        | 0.75%   |
| 6.4.6   | 2        | 0.75%   |
| 6.4.3   | 2        | 0.75%   |
| 6.2.12  | 2        | 0.75%   |
| 5.10.74 | 2        | 0.75%   |
| 4.9.20  | 2        | 0.75%   |
| 4.9.0   | 2        | 0.75%   |
| 6.9.7   | 1        | 0.38%   |
| 6.9.3   | 1        | 0.38%   |
| 6.9.12  | 1        | 0.38%   |
| 6.8.9   | 1        | 0.38%   |
| 6.8.5   | 1        | 0.38%   |
| 6.8.3   | 1        | 0.38%   |
| 6.8.12  | 1        | 0.38%   |
| 6.7.4   | 1        | 0.38%   |
| 6.6.4   | 1        | 0.38%   |
| 6.6.30  | 1        | 0.38%   |
| 6.6.3   | 1        | 0.38%   |
| 6.6.25  | 1        | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 32       | 12.21%  |
| 5.15    | 30       | 11.45%  |
| 5.4     | 28       | 10.69%  |
| 4.15    | 19       | 7.25%   |
| 6.2     | 16       | 6.11%   |
| 6.1     | 16       | 6.11%   |
| 6.4     | 15       | 5.73%   |
| 6.8     | 11       | 4.2%    |
| 5.16    | 11       | 4.2%    |
| 6.5     | 9        | 3.44%   |
| 6.6     | 8        | 3.05%   |
| 5.8     | 8        | 3.05%   |
| 5.19    | 8        | 3.05%   |
| 5.13    | 8        | 3.05%   |
| 5.3     | 5        | 1.91%   |
| 4.9     | 4        | 1.53%   |
| 6.9     | 3        | 1.15%   |
| 6.11    | 3        | 1.15%   |
| 6.10    | 3        | 1.15%   |
| 5.11    | 3        | 1.15%   |
| 5.0     | 3        | 1.15%   |
| 4.19    | 3        | 1.15%   |
| 6.3     | 2        | 0.76%   |
| 6.12    | 2        | 0.76%   |
| 6.0     | 2        | 0.76%   |
| 6.7     | 1        | 0.38%   |
| 5.9     | 1        | 0.38%   |
| 5.6     | 1        | 0.38%   |
| 5.18    | 1        | 0.38%   |
| 5.14    | 1        | 0.38%   |
| 5.12    | 1        | 0.38%   |
| 4.4     | 1        | 0.38%   |
| 4.18    | 1        | 0.38%   |
| 4.13    | 1        | 0.38%   |
| 4.1     | 1        | 0.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 229      | 92.71%  |
| i686   | 18       | 7.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| KDE5            | 72       | 27.8%   |
| GNOME           | 70       | 27.03%  |
| XFCE            | 24       | 9.27%   |
| X-Cinnamon      | 21       | 8.11%   |
| Unknown         | 17       | 6.56%   |
| MATE            | 10       | 3.86%   |
| KDE             | 7        | 2.7%    |
| LXQt            | 6        | 2.32%   |
| LXDE            | 6        | 2.32%   |
| KDE6            | 6        | 2.32%   |
| Pantheon        | 4        | 1.54%   |
| KDE4            | 4        | 1.54%   |
| Cinnamon        | 3        | 1.16%   |
| xmonad          | 1        | 0.39%   |
| Unity           | 1        | 0.39%   |
| Trinity         | 1        | 0.39%   |
| i3              | 1        | 0.39%   |
| GNOME Flashback | 1        | 0.39%   |
| GNOME Classic   | 1        | 0.39%   |
| Budgie          | 1        | 0.39%   |
| bspwm           | 1        | 0.39%   |
| awesome         | 1        | 0.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 190      | 74.8%   |
| Wayland | 59       | 23.23%  |
| Unknown | 4        | 1.57%   |
| Tty     | 1        | 0.39%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 100      | 39.53%  |
| SDDM    | 70       | 27.67%  |
| LightDM | 28       | 11.07%  |
| GDM3    | 24       | 9.49%   |
| GDM     | 18       | 7.11%   |
| TDM     | 7        | 2.77%   |
| KDM     | 4        | 1.58%   |
| SLiM    | 2        | 0.79%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_VE   | 152      | 59.84%  |
| en_US   | 50       | 19.69%  |
| Unknown | 17       | 6.69%   |
| es_ES   | 14       | 5.51%   |
| es_MX   | 9        | 3.54%   |
| C       | 6        | 2.36%   |
| es_CO   | 3        | 1.18%   |
| es_US   | 2        | 0.79%   |
| de_DE   | 1        | 0.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 203      | 82.19%  |
| EFI  | 44       | 17.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 174      | 68.24%  |
| Overlay | 38       | 14.9%   |
| Btrfs   | 23       | 9.02%   |
| Tmpfs   | 9        | 3.53%   |
| Unknown | 5        | 1.96%   |
| Xfs     | 3        | 1.18%   |
| Ext3    | 2        | 0.78%   |
| Ext2    | 1        | 0.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 108      | 42.69%  |
| MBR     | 84       | 33.2%   |
| GPT     | 61       | 24.11%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 199      | 80.24%  |
| Yes       | 49       | 19.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 158      | 62.95%  |
| Yes       | 93       | 37.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASRock              | 43       | 17.55%  |
| Hewlett-Packard     | 25       | 10.2%   |
| ECS                 | 21       | 8.57%   |
| Gigabyte Technology | 20       | 8.16%   |
| Intel               | 17       | 6.94%   |
| Dell                | 17       | 6.94%   |
| Lenovo              | 16       | 6.53%   |
| ASUSTek Computer    | 16       | 6.53%   |
| Pegatron            | 15       | 6.12%   |
| Biostar             | 14       | 5.71%   |
| MSI                 | 11       | 4.49%   |
| Foxconn             | 11       | 4.49%   |
| langchao            | 8        | 3.27%   |
| Inspur              | 4        | 1.63%   |
| Soncview            | 1        | 0.41%   |
| SIRAGON             | 1        | 0.41%   |
| JGINYUE             | 1        | 0.41%   |
| IP3 Tech            | 1        | 0.41%   |
| IBM                 | 1        | 0.41%   |
| Apple               | 1        | 0.41%   |
| Unknown             | 1        | 0.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ECS H61H2-CM                         | 13       | 5.31%   |
| langchao 12345                       | 8        | 3.27%   |
| ASRock G41M-VS3                      | 8        | 3.27%   |
| Pegatron Compaq dx2400 Microtower    | 4        | 1.63%   |
| ASRock N68C-S UCC                    | 4        | 1.63%   |
| ASRock N68-VS3 UCC                   | 4        | 1.63%   |
| ASRock H61M-VG3                      | 4        | 1.63%   |
| Intel H61                            | 3        | 1.22%   |
| HP Compaq 8200 Elite SFF PC          | 3        | 1.22%   |
| Gigabyte 970A-DS3P                   | 3        | 1.22%   |
| Biostar G41D3                        | 3        | 1.22%   |
| Pegatron IPM41-D3                    | 2        | 0.82%   |
| Lenovo ThinkCentre A57 9702AB7       | 2        | 0.82%   |
| Lenovo 70A4000HUX ThinkServer TS140  | 2        | 0.82%   |
| Inspur VIT E2250                     | 2        | 0.82%   |
| HP ProDesk 600 G1 SFF                | 2        | 0.82%   |
| HP EliteDesk 800 G2 SFF              | 2        | 0.82%   |
| HP EliteDesk 800 G1 USDT             | 2        | 0.82%   |
| HP EliteDesk 800 G1 SFF              | 2        | 0.82%   |
| HP Compaq Elite 8300 SFF             | 2        | 0.82%   |
| ECS H61H2-MV                         | 2        | 0.82%   |
| ECS G31T-M7                          | 2        | 0.82%   |
| Dell OptiPlex 9020                   | 2        | 0.82%   |
| Dell OptiPlex 790                    | 2        | 0.82%   |
| Dell Inspiron 3891                   | 2        | 0.82%   |
| Biostar P4M900-M7 FE                 | 2        | 0.82%   |
| Biostar G41D3C                       | 2        | 0.82%   |
| ASRock Wolfdale1333-D667             | 2        | 0.82%   |
| ASRock H61M-DGS                      | 2        | 0.82%   |
| ASRock AM2NF6G-VSTA                  | 2        | 0.82%   |
| ASRock 945GCM-S                      | 2        | 0.82%   |
| Soncview G41D3C                      | 1        | 0.41%   |
| SIRAGON AIO-5150                     | 1        | 0.41%   |
| Pegatron PEGATRON                    | 1        | 0.41%   |
| Pegatron IPPEL-DB                    | 1        | 0.41%   |
| Pegatron IPMIP-H55-INSPUR            | 1        | 0.41%   |
| Pegatron CQ1507LA                    | 1        | 0.41%   |
| Pegatron Compaq dx2400 Microtower PC | 1        | 0.41%   |
| Pegatron BM411AA-ABA CQ5600F         | 1        | 0.41%   |
| Pegatron 2A73h                       | 1        | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| ECS H61H2-CM              | 13       | 5.31%   |
| Lenovo ThinkCentre        | 12       | 4.9%    |
| Dell OptiPlex             | 12       | 4.9%    |
| HP Compaq                 | 11       | 4.49%   |
| langchao 12345            | 8        | 3.27%   |
| HP EliteDesk              | 8        | 3.27%   |
| ASRock G41M-VS3           | 8        | 3.27%   |
| Pegatron Compaq           | 5        | 2.04%   |
| ASRock N68-VS3            | 5        | 2.04%   |
| ASUS PRIME                | 4        | 1.63%   |
| ASRock N68C-S             | 4        | 1.63%   |
| ASRock H61M-VG3           | 4        | 1.63%   |
| Intel H61                 | 3        | 1.22%   |
| HP ProDesk                | 3        | 1.22%   |
| Gigabyte 970A-DS3P        | 3        | 1.22%   |
| Biostar G41D3             | 3        | 1.22%   |
| ASUS P8H61-M              | 3        | 1.22%   |
| ASRock H61M-DGS           | 3        | 1.22%   |
| Pegatron IPM41-D3         | 2        | 0.82%   |
| Lenovo 70A4000HUX         | 2        | 0.82%   |
| Intel DG41TY              | 2        | 0.82%   |
| Inspur VIT                | 2        | 0.82%   |
| ECS H61H2-MV              | 2        | 0.82%   |
| ECS G31T-M7               | 2        | 0.82%   |
| Dell Vostro               | 2        | 0.82%   |
| Dell Inspiron             | 2        | 0.82%   |
| Biostar P4M900-M7         | 2        | 0.82%   |
| Biostar G41D3C            | 2        | 0.82%   |
| ASUS Rampage              | 2        | 0.82%   |
| ASUS P5G41T-M             | 2        | 0.82%   |
| ASRock Wolfdale1333-D667  | 2        | 0.82%   |
| ASRock AM2NF6G-VSTA       | 2        | 0.82%   |
| ASRock 945GCM-S           | 2        | 0.82%   |
| Soncview G41D3C           | 1        | 0.41%   |
| SIRAGON AIO-5150          | 1        | 0.41%   |
| Pegatron PEGATRON         | 1        | 0.41%   |
| Pegatron IPPEL-DB         | 1        | 0.41%   |
| Pegatron IPMIP-H55-INSPUR | 1        | 0.41%   |
| Pegatron CQ1507LA         | 1        | 0.41%   |
| Pegatron BM411AA-ABA      | 1        | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 54       | 22.04%  |
| 2010 | 41       | 16.73%  |
| 2012 | 28       | 11.43%  |
| 2008 | 22       | 8.98%   |
| 2013 | 16       | 6.53%   |
| 2007 | 15       | 6.12%   |
| 2014 | 12       | 4.9%    |
| 2009 | 10       | 4.08%   |
| 2006 | 9        | 3.67%   |
| 2021 | 8        | 3.27%   |
| 2020 | 7        | 2.86%   |
| 2015 | 6        | 2.45%   |
| 2017 | 5        | 2.04%   |
| 2016 | 5        | 2.04%   |
| 2022 | 2        | 0.82%   |
| 2019 | 2        | 0.82%   |
| 2005 | 1        | 0.41%   |
| 2004 | 1        | 0.41%   |
| 2002 | 1        | 0.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 245      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 243      | 99.18%  |
| Enabled  | 2        | 0.82%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 245      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 66       | 25.78%  |
| 4.01-8.0    | 55       | 21.48%  |
| 8.01-16.0   | 45       | 17.58%  |
| 16.01-24.0  | 33       | 12.89%  |
| 1.01-2.0    | 32       | 12.5%   |
| 2.01-3.0    | 10       | 3.91%   |
| 32.01-64.0  | 5        | 1.95%   |
| 24.01-32.0  | 4        | 1.56%   |
| 64.01-256.0 | 3        | 1.17%   |
| 0.51-1.0    | 3        | 1.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 109      | 40.52%  |
| 2.01-3.0  | 64       | 23.79%  |
| 4.01-8.0  | 33       | 12.27%  |
| 0.51-1.0  | 30       | 11.15%  |
| 3.01-4.0  | 27       | 10.04%  |
| 0.01-0.5  | 5        | 1.86%   |
| 8.01-16.0 | 1        | 0.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 136      | 52.92%  |
| 2      | 79       | 30.74%  |
| 3      | 30       | 11.67%  |
| 4      | 9        | 3.5%    |
| 5      | 2        | 0.78%   |
| 0      | 1        | 0.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 152      | 60.56%  |
| Yes       | 99       | 39.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 240      | 97.96%  |
| No        | 5        | 2.04%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 129      | 51.81%  |
| Yes       | 120      | 48.19%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 217      | 87.85%  |
| Yes       | 30       | 12.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Venezuela | 245      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Desktops | Percent |
|----------------------------|----------|---------|
| Caracas                    | 101      | 38.26%  |
| Maracaibo                  | 19       | 7.2%    |
| San Cristóbal             | 13       | 4.92%   |
| Valencia                   | 12       | 4.55%   |
| Mérida                    | 11       | 4.17%   |
| Barquisimeto               | 11       | 4.17%   |
| Maracay                    | 10       | 3.79%   |
| San Carlos del Zulia       | 7        | 2.65%   |
| Barcelona                  | 6        | 2.27%   |
| Maturín                   | 5        | 1.89%   |
| Barinas                    | 5        | 1.89%   |
| Vigia                      | 4        | 1.52%   |
| Ciudad Guayana             | 4        | 1.52%   |
| San Antonio de Los Altos   | 3        | 1.14%   |
| Porlamar                   | 3        | 1.14%   |
| Los Teques                 | 3        | 1.14%   |
| Ciudad Bolívar            | 3        | 1.14%   |
| Carrizal                   | 3        | 1.14%   |
| San Carlos                 | 2        | 0.76%   |
| Lecherias                  | 2        | 0.76%   |
| Cumaná                    | 2        | 0.76%   |
| Cabimas                    | 2        | 0.76%   |
| Araure                     | 2        | 0.76%   |
| Acarigua                   | 2        | 0.76%   |
| Zulia                      | 1        | 0.38%   |
| Valle de La Pascua         | 1        | 0.38%   |
| Turmero                    | 1        | 0.38%   |
| Tucupita                   | 1        | 0.38%   |
| Santa Teresa del Tuy       | 1        | 0.38%   |
| San Juan Bautista          | 1        | 0.38%   |
| San Francisco              | 1        | 0.38%   |
| Puerto Ordaz and San Felix | 1        | 0.38%   |
| Petare                     | 1        | 0.38%   |
| Parroquia El Recreo        | 1        | 0.38%   |
| Ocumare                    | 1        | 0.38%   |
| Miranda                    | 1        | 0.38%   |
| Mene Grande                | 1        | 0.38%   |
| Los Palos Grandes          | 1        | 0.38%   |
| Las Vegas                  | 1        | 0.38%   |
| Las Tienditas              | 1        | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 107      | 155    | 29.32%  |
| Seagate                     | 78       | 110    | 21.37%  |
| Hitachi                     | 40       | 47     | 10.96%  |
| Samsung Electronics         | 33       | 38     | 9.04%   |
| Kingston                    | 23       | 27     | 6.3%    |
| Toshiba                     | 20       | 23     | 5.48%   |
| Maxtor                      | 7        | 7      | 1.92%   |
| Patriot                     | 6        | 8      | 1.64%   |
| PNY                         | 5        | 8      | 1.37%   |
| addlink                     | 4        | 6      | 1.1%    |
| SK hynix                    | 3        | 3      | 0.82%   |
| Sandisk                     | 3        | 4      | 0.82%   |
| Micron Technology           | 3        | 5      | 0.82%   |
| Crucial                     | 3        | 5      | 0.82%   |
| Team                        | 2        | 3      | 0.55%   |
| SPCC                        | 2        | 3      | 0.55%   |
| JMicron Technology          | 2        | 2      | 0.55%   |
| HGST                        | 2        | 2      | 0.55%   |
| Fujitsu                     | 2        | 2      | 0.55%   |
| ExcelStor                   | 2        | 2      | 0.55%   |
| A-DATA Technology           | 2        | 2      | 0.55%   |
| Unknown                     | 1        | 1      | 0.27%   |
| Silicon Motion              | 1        | 1      | 0.27%   |
| RRINTEC                     | 1        | 1      | 0.27%   |
| REECHO                      | 1        | 2      | 0.27%   |
| Phison Electronics          | 1        | 1      | 0.27%   |
| Netac                       | 1        | 1      | 0.27%   |
| Mushkin                     | 1        | 1      | 0.27%   |
| Kingston Technology Company | 1        | 1      | 0.27%   |
| IBM/Hitachi                 | 1        | 2      | 0.27%   |
| HPE                         | 1        | 2      | 0.27%   |
| Hewlett-Packard             | 1        | 1      | 0.27%   |
| Gigabyte Technology         | 1        | 1      | 0.27%   |
| G535S                       | 1        | 1      | 0.27%   |
| Emtec                       | 1        | 1      | 0.27%   |
| Dogfish                     | 1        | 1      | 0.27%   |
| Dahua                       | 1        | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST320LT012-1DG14C 320GB     | 12       | 2.93%   |
| Toshiba DT01ACA050 500GB            | 11       | 2.69%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 10       | 2.44%   |
| Seagate ST500DM002-1BD142 500GB     | 8        | 1.96%   |
| Kingston SA400S37240G 240GB SSD     | 7        | 1.71%   |
| Samsung HD502HJ 500GB               | 6        | 1.47%   |
| WDC WD3200AAJS-00L7A0 320GB         | 5        | 1.22%   |
| Seagate ST3320418AS 320GB           | 5        | 1.22%   |
| Kingston SA400S37120G 120GB SSD     | 5        | 1.22%   |
| WDC WD5000AAKX-221CA1 500GB         | 4        | 0.98%   |
| WDC WD5000AAKX-001CA0 500GB         | 4        | 0.98%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 4        | 0.98%   |
| WDC WD3200AAJS-08L7A0 320GB         | 4        | 0.98%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 4        | 0.98%   |
| Seagate ST320LM000 HM321HI 320GB    | 4        | 0.98%   |
| Samsung HD322HJ 320GB               | 4        | 0.98%   |
| Samsung HD161HJ 160GB               | 4        | 0.98%   |
| Hitachi HTS543225L9A300 250GB       | 4        | 0.98%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 3        | 0.73%   |
| WDC WD5000AAKS-00A7B0 500GB         | 3        | 0.73%   |
| WDC WD1600AABS-00PRA0 160GB         | 3        | 0.73%   |
| WDC WD10EZEX-60ZF5A0 1TB            | 3        | 0.73%   |
| Seagate ST500DM002-1BC142 500GB     | 3        | 0.73%   |
| Seagate ST4000DM000-1F2168 4TB      | 3        | 0.73%   |
| Samsung HD161GJ 160GB               | 3        | 0.73%   |
| Maxtor STM3160215AS 160GB           | 3        | 0.73%   |
| Kingston SA400S37480G 480GB SSD     | 3        | 0.73%   |
| Hitachi HTS542580K9SA00 80GB        | 3        | 0.73%   |
| Hitachi HDS728080PLA380 82GB        | 3        | 0.73%   |
| Hitachi HDS721616PLA380 160GB       | 3        | 0.73%   |
| Hitachi HDS5C1050CLA382 500GB       | 3        | 0.73%   |
| addlink SATA SSD 512GB              | 3        | 0.73%   |
| WDC WD800BD-22MRA1 80GB             | 2        | 0.49%   |
| WDC WD800BB-22JHC0 80GB             | 2        | 0.49%   |
| WDC WD5000AZLX-60K2TA0 500GB        | 2        | 0.49%   |
| WDC WD5000AAKX-753CA1 500GB         | 2        | 0.49%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 2        | 0.49%   |
| WDC WD3200AAJS-60M0A0 320GB         | 2        | 0.49%   |
| WDC WD3200AAJS-22L7A0 320GB         | 2        | 0.49%   |
| WDC WD2500AAJS-60B4A0 250GB         | 2        | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 106      | 154    | 36.93%  |
| Seagate             | 78       | 109    | 27.18%  |
| Hitachi             | 40       | 47     | 13.94%  |
| Samsung Electronics | 26       | 30     | 9.06%   |
| Toshiba             | 20       | 23     | 6.97%   |
| Maxtor              | 7        | 7      | 2.44%   |
| JMicron Technology  | 2        | 2      | 0.7%    |
| HGST                | 2        | 2      | 0.7%    |
| Fujitsu             | 2        | 2      | 0.7%    |
| ExcelStor           | 2        | 2      | 0.7%    |
| IBM/Hitachi         | 1        | 2      | 0.35%   |
| HPE                 | 1        | 1      | 0.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 22       | 25     | 33.85%  |
| Patriot             | 6        | 8      | 9.23%   |
| Samsung Electronics | 5        | 6      | 7.69%   |
| PNY                 | 5        | 8      | 7.69%   |
| addlink             | 4        | 6      | 6.15%   |
| Crucial             | 3        | 5      | 4.62%   |
| Team                | 2        | 3      | 3.08%   |
| SPCC                | 2        | 3      | 3.08%   |
| SK hynix            | 2        | 2      | 3.08%   |
| SanDisk             | 2        | 2      | 3.08%   |
| Micron Technology   | 2        | 4      | 3.08%   |
| A-DATA Technology   | 2        | 2      | 3.08%   |
| WDC                 | 1        | 1      | 1.54%   |
| RRINTEC             | 1        | 1      | 1.54%   |
| Netac               | 1        | 1      | 1.54%   |
| Hewlett-Packard     | 1        | 1      | 1.54%   |
| Gigabyte Technology | 1        | 1      | 1.54%   |
| Emtec               | 1        | 1      | 1.54%   |
| Dogfish             | 1        | 1      | 1.54%   |
| Dahua               | 1        | 1      | 1.54%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 214      | 381    | 74.05%  |
| SSD     | 59       | 82     | 20.42%  |
| NVMe    | 12       | 13     | 4.15%   |
| Unknown | 4        | 5      | 1.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 240      | 463    | 93.39%  |
| NVMe | 12       | 13     | 4.67%   |
| SAS  | 5        | 5      | 1.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 221      | 379    | 78.37%  |
| 0.51-1.0   | 44       | 61     | 15.6%   |
| 1.01-2.0   | 9        | 10     | 3.19%   |
| 3.01-4.0   | 4        | 8      | 1.42%   |
| 2.01-3.0   | 2        | 3      | 0.71%   |
| 10.01-20.0 | 1        | 1      | 0.35%   |
| 4.01-10.0  | 1        | 1      | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 78       | 29.55%  |
| 101-250        | 57       | 21.59%  |
| 501-1000       | 36       | 13.64%  |
| 1-20           | 31       | 11.74%  |
| 51-100         | 20       | 7.58%   |
| 1001-2000      | 19       | 7.2%    |
| 21-50          | 9        | 3.41%   |
| Unknown        | 6        | 2.27%   |
| More than 3000 | 4        | 1.52%   |
| 2001-3000      | 4        | 1.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 111      | 41.89%  |
| 21-50          | 44       | 16.6%   |
| 101-250        | 34       | 12.83%  |
| 251-500        | 28       | 10.57%  |
| 51-100         | 22       | 8.3%    |
| 501-1000       | 11       | 4.15%   |
| 1001-2000      | 6        | 2.26%   |
| Unknown        | 6        | 2.26%   |
| 2001-3000      | 2        | 0.75%   |
| More than 3000 | 1        | 0.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST320LT012-1DG14C 320GB   | 7        | 8      | 6.86%   |
| WDC WD5000AAKX-22ERMA0 500GB      | 6        | 8      | 5.88%   |
| Toshiba DT01ACA050 500GB          | 4        | 5      | 3.92%   |
| Hitachi HTS543225L9A300 250GB     | 4        | 4      | 3.92%   |
| Hitachi HDS721616PLA380 160GB     | 3        | 3      | 2.94%   |
| WDC WD5000AAKX-221CA1 500GB       | 2        | 2      | 1.96%   |
| WDC WD5000AAKS-00A7B0 500GB       | 2        | 2      | 1.96%   |
| WDC WD3200AAJS-08L7A0 320GB       | 2        | 3      | 1.96%   |
| Seagate ST500DM002-1BD142 500GB   | 2        | 2      | 1.96%   |
| Seagate ST3500312CS 500GB         | 2        | 2      | 1.96%   |
| Samsung Electronics HD161GJ 160GB | 2        | 3      | 1.96%   |
| Maxtor STM3160215AS 160GB         | 2        | 2      | 1.96%   |
| Hitachi HDS728080PLA380 82GB      | 2        | 2      | 1.96%   |
| WDC WD800JD-75JNA0 80GB           | 1        | 1      | 0.98%   |
| WDC WD800BD-08MRA1 80GB           | 1        | 1      | 0.98%   |
| WDC WD800BB-22JHC0 80GB           | 1        | 1      | 0.98%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 1        | 1      | 0.98%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1        | 1      | 0.98%   |
| WDC WD5000AAKX-08U6AA0 500GB      | 1        | 1      | 0.98%   |
| WDC WD5000AAKX-08ERMA0 500GB      | 1        | 2      | 0.98%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 0.98%   |
| WDC WD5000AAKS-00UU3A0 500GB      | 1        | 1      | 0.98%   |
| WDC WD5000AACS-00ZUB0 500GB       | 1        | 1      | 0.98%   |
| WDC WD3200LPVX-22V0TT0 320GB      | 1        | 1      | 0.98%   |
| WDC WD3200BEKT-22F3T0 320GB       | 1        | 1      | 0.98%   |
| WDC WD3200BEKT-08PVMT1 320GB      | 1        | 1      | 0.98%   |
| WDC WD2500BEVT-60ZCT1 250GB       | 1        | 1      | 0.98%   |
| WDC WD2003FYPS-27Y2B0 2TB         | 1        | 1      | 0.98%   |
| WDC WD1600AABS-00H4A0 160GB       | 1        | 1      | 0.98%   |
| WDC WD10EZEX-60ZF5A0 1TB          | 1        | 1      | 0.98%   |
| WDC WD10EZEX-22RKKA0 1TB          | 1        | 1      | 0.98%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 1        | 1      | 0.98%   |
| Toshiba MQ01ABF032 320GB          | 1        | 1      | 0.98%   |
| Toshiba MK3275GSX 320GB           | 1        | 1      | 0.98%   |
| Toshiba MK3259GSXP 320GB          | 1        | 1      | 0.98%   |
| Toshiba MK2561GSYN 250GB          | 1        | 1      | 0.98%   |
| Seagate ST500DM005 HD502HJ 500GB  | 1        | 1      | 0.98%   |
| Seagate ST3500630AS 500GB         | 1        | 1      | 0.98%   |
| Seagate ST3500418AS 500GB         | 1        | 1      | 0.98%   |
| Seagate ST3500413AS 500GB         | 1        | 1      | 0.98%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 27       | 30     | 29.35%  |
| WDC                 | 24       | 35     | 26.09%  |
| Hitachi             | 19       | 19     | 20.65%  |
| Toshiba             | 6        | 9      | 6.52%   |
| Samsung Electronics | 6        | 8      | 6.52%   |
| Maxtor              | 3        | 3      | 3.26%   |
| PNY                 | 1        | 2      | 1.09%   |
| Micron Technology   | 1        | 1      | 1.09%   |
| Kingston            | 1        | 1      | 1.09%   |
| JMicron Technology  | 1        | 1      | 1.09%   |
| IBM/Hitachi         | 1        | 2      | 1.09%   |
| HGST                | 1        | 1      | 1.09%   |
| ExcelStor           | 1        | 1      | 1.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 27       | 30     | 30.34%  |
| WDC                 | 24       | 35     | 26.97%  |
| Hitachi             | 19       | 19     | 21.35%  |
| Toshiba             | 6        | 9      | 6.74%   |
| Samsung Electronics | 6        | 8      | 6.74%   |
| Maxtor              | 3        | 3      | 3.37%   |
| JMicron Technology  | 1        | 1      | 1.12%   |
| IBM/Hitachi         | 1        | 2      | 1.12%   |
| HGST                | 1        | 1      | 1.12%   |
| ExcelStor           | 1        | 1      | 1.12%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 72       | 109    | 96%     |
| SSD  | 3        | 4      | 4%      |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Toshiba DT01ACA050 500GB  | 2        | 2      | 50%     |
| WDC WD800JD-00MSA1 80GB   | 1        | 1      | 25%     |
| Seagate ST9320423AS 320GB | 1        | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 2        | 2      | 50%     |
| WDC     | 1        | 1      | 25%     |
| Seagate | 1        | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 125      | 245    | 44.96%  |
| Malfunc  | 75       | 113    | 26.98%  |
| Works    | 74       | 119    | 26.62%  |
| Failed   | 4        | 4      | 1.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 189      | 69.23%  |
| AMD                         | 29       | 10.62%  |
| Nvidia                      | 21       | 7.69%   |
| VIA Technologies            | 6        | 2.2%    |
| Marvell Technology Group    | 6        | 2.2%    |
| JMicron Technology          | 6        | 2.2%    |
| ASMedia Technology          | 3        | 1.1%    |
| Silicon Motion              | 2        | 0.73%   |
| SanDisk                     | 2        | 0.73%   |
| Samsung Electronics         | 2        | 0.73%   |
| Kingston Technology Company | 2        | 0.73%   |
| SK hynix                    | 1        | 0.37%   |
| Phison Electronics          | 1        | 0.37%   |
| Micron Technology           | 1        | 0.37%   |
| Jiangsu Huacun Elec.        | 1        | 0.37%   |
| Adaptec                     | 1        | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 54       | 13.43%  |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 41       | 10.2%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 35       | 8.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 21       | 5.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 21       | 5.22%   |
| Nvidia MCP61 SATA Controller                                                            | 19       | 4.73%   |
| Nvidia MCP61 IDE                                                                        | 17       | 4.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 14       | 3.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 10       | 2.49%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 9        | 2.24%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 9        | 2.24%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8        | 1.99%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 8        | 1.99%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 8        | 1.99%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 6        | 1.49%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 1.49%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 6        | 1.49%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 1.24%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 1.24%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 5        | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 1.24%   |
| VIA Serial ATA Controller                                                               | 4        | 1%      |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3        | 0.75%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3        | 0.75%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 0.75%   |
| JMicron JMB368 IDE controller                                                           | 2        | 0.5%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.5%    |
| JMicron JMB362 SATA Controller                                                          | 2        | 0.5%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.5%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 0.5%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 0.5%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.5%    |
| Intel 82801EB (ICH5) SATA Controller                                                    | 2        | 0.5%    |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 0.5%    |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 0.5%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 0.5%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 0.5%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 2        | 0.5%    |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 0.5%    |
| AMD FCH IDE Controller                                                                  | 2        | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 139      | 49.82%  |
| SATA | 117      | 41.94%  |
| NVMe | 12       | 4.3%    |
| RAID | 9        | 3.23%   |
| SAS  | 1        | 0.36%   |
| SCSI | 1        | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 196      | 80%     |
| AMD    | 49       | 20%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 11       | 4.49%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 9        | 3.67%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 8        | 3.27%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 7        | 2.86%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 5        | 2.04%   |
| Intel Pentium 4 CPU 3.00GHz                 | 5        | 2.04%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 5        | 2.04%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 4        | 1.63%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 4        | 1.63%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 1.63%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 1.63%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 4        | 1.63%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 3        | 1.22%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 3        | 1.22%   |
| Intel Pentium CPU G640 @ 2.80GHz            | 3        | 1.22%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 3        | 1.22%   |
| Intel Pentium CPU G2010 @ 2.80GHz           | 3        | 1.22%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 1.22%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 3        | 1.22%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 3        | 1.22%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 1.22%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 3        | 1.22%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.22%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 1.22%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 1.22%   |
| AMD Sempron 145 Processor                   | 3        | 1.22%   |
| AMD FX-6300 Six-Core Processor              | 3        | 1.22%   |
| AMD FX-6100 Six-Core Processor              | 3        | 1.22%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 0.82%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 2        | 0.82%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz      | 2        | 0.82%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 2        | 0.82%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 2        | 0.82%   |
| Intel Pentium 4 CPU 3.20GHz                 | 2        | 0.82%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 0.82%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 0.82%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 0.82%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 0.82%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2        | 0.82%   |
| Intel Core 2 CPU 4400 @ 2.00GHz             | 2        | 0.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 50       | 20.41%  |
| Intel Pentium Dual-Core | 34       | 13.88%  |
| Intel Pentium           | 18       | 7.35%   |
| Intel Core i7           | 18       | 7.35%   |
| Intel Core 2 Duo        | 14       | 5.71%   |
| Intel Core i3           | 13       | 5.31%   |
| Intel Pentium Dual      | 9        | 3.67%   |
| Other                   | 8        | 3.27%   |
| Intel Pentium 4         | 8        | 3.27%   |
| Intel Core 2 Quad       | 7        | 2.86%   |
| AMD Sempron             | 7        | 2.86%   |
| AMD FX                  | 7        | 2.86%   |
| Intel Xeon              | 6        | 2.45%   |
| Intel Core 2            | 5        | 2.04%   |
| AMD Athlon II X2        | 5        | 2.04%   |
| AMD Ryzen 5             | 4        | 1.63%   |
| Intel Celeron           | 3        | 1.22%   |
| AMD Phenom II X4        | 3        | 1.22%   |
| AMD Athlon II X4        | 3        | 1.22%   |
| AMD Athlon 64 X2        | 3        | 1.22%   |
| Intel Pentium D         | 2        | 0.82%   |
| AMD Phenom              | 2        | 0.82%   |
| AMD Athlon              | 2        | 0.82%   |
| AMD A8                  | 2        | 0.82%   |
| Intel Genuine           | 1        | 0.41%   |
| Intel Atom              | 1        | 0.41%   |
| AMD Turion II Neo       | 1        | 0.41%   |
| AMD Ryzen 7             | 1        | 0.41%   |
| AMD Ryzen 3             | 1        | 0.41%   |
| AMD Phenom II X6        | 1        | 0.41%   |
| AMD Phenom II X2        | 1        | 0.41%   |
| AMD E1                  | 1        | 0.41%   |
| AMD E                   | 1        | 0.41%   |
| AMD Athlon II           | 1        | 0.41%   |
| AMD A6                  | 1        | 0.41%   |
| AMD A4                  | 1        | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 115      | 46.94%  |
| 4       | 87       | 35.51%  |
| 1       | 18       | 7.35%   |
| 6       | 12       | 4.9%    |
| 3       | 7        | 2.86%   |
| 8       | 4        | 1.63%   |
| Unknown | 2        | 0.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 244      | 99.59%  |
| 2      | 1        | 0.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 178      | 72.65%  |
| 2       | 65       | 26.53%  |
| Unknown | 2        | 0.82%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 240      | 97.96%  |
| 64-bit         | 2        | 0.82%   |
| 32-bit         | 2        | 0.82%   |
| Unknown        | 1        | 0.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 89       | 35.32%  |
| 0x1067a    | 32       | 12.7%   |
| 0x206a7    | 22       | 8.73%   |
| 0x306a9    | 14       | 5.56%   |
| 0x306c3    | 8        | 3.17%   |
| 0x6fd      | 7        | 2.78%   |
| 0x010000c8 | 6        | 2.38%   |
| 0x6fb      | 5        | 1.98%   |
| 0xf65      | 4        | 1.59%   |
| 0x506e3    | 4        | 1.59%   |
| 0x010000b6 | 4        | 1.59%   |
| 0xa0671    | 3        | 1.19%   |
| 0x6f2      | 3        | 1.19%   |
| 0x10676    | 3        | 1.19%   |
| 0x06000852 | 3        | 1.19%   |
| 0x0600063e | 3        | 1.19%   |
| 0x03000027 | 3        | 1.19%   |
| 0x010000c7 | 3        | 1.19%   |
| 0xf41      | 2        | 0.79%   |
| 0x206d7    | 2        | 0.79%   |
| 0x106a5    | 2        | 0.79%   |
| 0x010000db | 2        | 0.79%   |
| 0xf49      | 1        | 0.4%    |
| 0xf47      | 1        | 0.4%    |
| 0xf43      | 1        | 0.4%    |
| 0xf12      | 1        | 0.4%    |
| 0xa0653    | 1        | 0.4%    |
| 0x906eb    | 1        | 0.4%    |
| 0x906e9    | 1        | 0.4%    |
| 0x806c1    | 1        | 0.4%    |
| 0x6f6      | 1        | 0.4%    |
| 0x20652    | 1        | 0.4%    |
| 0x106e5    | 1        | 0.4%    |
| 0x106ca    | 1        | 0.4%    |
| 0x10661    | 1        | 0.4%    |
| 0x0a50000f | 1        | 0.4%    |
| 0x0a50000d | 1        | 0.4%    |
| 0x0a50000c | 1        | 0.4%    |
| 0x08701030 | 1        | 0.4%    |
| 0x0810100b | 1        | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 51       | 20.82%  |
| SandyBridge      | 35       | 14.29%  |
| IvyBridge        | 33       | 13.47%  |
| Core             | 23       | 9.39%   |
| K10              | 22       | 8.98%   |
| Haswell          | 17       | 6.94%   |
| NetBurst         | 10       | 4.08%   |
| Skylake          | 7        | 2.86%   |
| K8 Hammer        | 5        | 2.04%   |
| Piledriver       | 4        | 1.63%   |
| Bulldozer        | 4        | 1.63%   |
| Zen 3            | 3        | 1.22%   |
| Westmere         | 3        | 1.22%   |
| Nehalem          | 3        | 1.22%   |
| K10 Llano        | 3        | 1.22%   |
| CometLake        | 3        | 1.22%   |
| Unknown          | 3        | 1.22%   |
| Zen+             | 2        | 0.82%   |
| KabyLake         | 2        | 0.82%   |
| Icelake          | 2        | 0.82%   |
| Bobcat           | 2        | 0.82%   |
| Zen 2            | 1        | 0.41%   |
| Zen              | 1        | 0.41%   |
| TigerLake        | 1        | 0.41%   |
| Steamroller      | 1        | 0.41%   |
| Silvermont       | 1        | 0.41%   |
| Jaguar           | 1        | 0.41%   |
| Bonnell          | 1        | 0.41%   |
| Alderlake Hybrid | 1        | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 139      | 52.85%  |
| Nvidia            | 63       | 23.95%  |
| AMD               | 55       | 20.91%  |
| VIA Technologies  | 5        | 1.9%    |
| ASPEED Technology | 1        | 0.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 27       | 10.11%  |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 25       | 9.36%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 16       | 5.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 14       | 5.24%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 13       | 4.87%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 8        | 3%      |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 6        | 2.25%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 6        | 2.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 2.25%   |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 1.87%   |
| Nvidia GF119 [GeForce GT 610]                                               | 5        | 1.87%   |
| Intel HD Graphics 530                                                       | 5        | 1.87%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 5        | 1.87%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 5        | 1.87%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 4        | 1.5%    |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 1.5%    |
| Nvidia GF119 [GeForce GT 520]                                               | 4        | 1.5%    |
| Intel 82946GZ/GL Integrated Graphics Controller                             | 4        | 1.5%    |
| Nvidia GF106 [GeForce GTS 450]                                              | 3        | 1.12%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 3        | 1.12%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 3        | 1.12%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 3        | 1.12%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 3        | 1.12%   |
| AMD RS780L [Radeon 3000]                                                    | 3        | 1.12%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 3        | 1.12%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3        | 1.12%   |
| Nvidia GM107GL [Quadro K620]                                                | 2        | 0.75%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 0.75%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 2        | 0.75%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 2        | 0.75%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 0.75%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 2        | 0.75%   |
| Intel 82865G Integrated Graphics Controller                                 | 2        | 0.75%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 0.75%   |
| AMD RV670 [Radeon HD 3870]                                                  | 2        | 0.75%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 0.75%   |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                          | 1        | 0.37%   |
| Nvidia NV44 [GeForce 7100 GS]                                               | 1        | 0.37%   |
| Nvidia NV44 [GeForce 6200 TurboCache]                                       | 1        | 0.37%   |
| Nvidia NV44 [GeForce 6200 LE]                                               | 1        | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Intel       | 128      | 51.61%  |
| 1 x Nvidia      | 57       | 22.98%  |
| 1 x AMD         | 45       | 18.15%  |
| 1 x VIA         | 5        | 2.02%   |
| AMD + Nvidia    | 4        | 1.61%   |
| 2 x AMD         | 3        | 1.21%   |
| Intel + AMD     | 3        | 1.21%   |
| Intel + Nvidia  | 2        | 0.81%   |
| Nvidia + ASPEED | 1        | 0.4%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 205      | 83%     |
| Proprietary | 23       | 9.31%   |
| Unknown     | 19       | 7.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 151      | 59.68%  |
| 0.51-1.0   | 41       | 16.21%  |
| 0.01-0.5   | 30       | 11.86%  |
| 1.01-2.0   | 24       | 9.49%   |
| 3.01-4.0   | 5        | 1.98%   |
| 7.01-8.0   | 2        | 0.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung Electronics                   | 48       | 22.43%  |
| Goldstar                              | 26       | 12.15%  |
| Hewlett-Packard                       | 19       | 8.88%   |
| Toshiba                               | 18       | 8.41%   |
| Dell                                  | 14       | 6.54%   |
| AOC                                   | 12       | 5.61%   |
| Acer                                  | 12       | 5.61%   |
| Lenovo                                | 10       | 4.67%   |
| Vita                                  | 5        | 2.34%   |
| BenQ                                  | 5        | 2.34%   |
| Unknown (XXX)                         | 3        | 1.4%    |
| Sony                                  | 3        | 1.4%    |
| MSI                                   | 3        | 1.4%    |
| LG Electronics                        | 3        | 1.4%    |
| ViewSonic                             | 2        | 0.93%   |
| NEC Computers                         | 2        | 0.93%   |
| KTC                                   | 2        | 0.93%   |
| Envision                              | 2        | 0.93%   |
| Ancor Communications                  | 2        | 0.93%   |
| ___                                   | 1        | 0.47%   |
| Unknown                               | 1        | 0.47%   |
| Toshiba Matsushita Display Technology | 1        | 0.47%   |
| TCL                                   | 1        | 0.47%   |
| RGT                                   | 1        | 0.47%   |
| PXO                                   | 1        | 0.47%   |
| Plain Tree Systems                    | 1        | 0.47%   |
| Philips                               | 1        | 0.47%   |
| PEGA                                  | 1        | 0.47%   |
| Parker                                | 1        | 0.47%   |
| MStar                                 | 1        | 0.47%   |
| Mi                                    | 1        | 0.47%   |
| LSC                                   | 1        | 0.47%   |
| LED                                   | 1        | 0.47%   |
| IBM                                   | 1        | 0.47%   |
| HKC                                   | 1        | 0.47%   |
| HJW                                   | 1        | 0.47%   |
| HannStar                              | 1        | 0.47%   |
| Haier                                 | 1        | 0.47%   |
| eMachines                             | 1        | 0.47%   |
| CVT                                   | 1        | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch             | 15       | 6.76%   |
| Vita V195EW-W VIT1950 1600x900 432x240mm 19.5-inch                   | 5        | 2.25%   |
| Lenovo LEN L171 LEN240B 1280x1024 340x270mm 17.1-inch                | 5        | 2.25%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                  | 5        | 2.25%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 4        | 1.8%    |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                   | 3        | 1.35%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch          | 3        | 1.35%   |
| Unknown (XXX) L9W XXX076E 1440x900 410x256mm 19.0-inch               | 2        | 0.9%    |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch  | 2        | 0.9%    |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch  | 2        | 0.9%    |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch | 2        | 0.9%    |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 2        | 0.9%    |
| Samsung Electronics S19A10N SAM083E 1366x768 410x230mm 18.5-inch     | 2        | 0.9%    |
| MSI G273 MSI3CA7 1920x1080 597x336mm 27.0-inch                       | 2        | 0.9%    |
| Lenovo LEN L151 LEN23CD 1024x768 304x228mm 15.0-inch                 | 2        | 0.9%    |
| Lenovo L197 Wide LEN1152 1440x900 410x257mm 19.1-inch                | 2        | 0.9%    |
| Hewlett-Packard S1933 HWP2933 1366x768 413x234mm 18.7-inch           | 2        | 0.9%    |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 2        | 0.9%    |
| Goldstar L194W GSM4B6A 1440x900 408x255mm 18.9-inch                  | 2        | 0.9%    |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                 | 2        | 0.9%    |
| Acer V246HQL ACR0424 1920x1080 521x293mm 23.5-inch                   | 2        | 0.9%    |
| Acer B193W ACR001E 1440x900 408x255mm 18.9-inch                      | 2        | 0.9%    |
| ___ LCD TV ___9000 1360x768                                          | 1        | 0.45%   |
| ViewSonic VX2245wm VSCBB1E 1680x1050 474x296mm 22.0-inch             | 1        | 0.45%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch        | 1        | 0.45%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                   | 1        | 0.45%   |
| Unknown (XXX) 1772ED XXX1772 1280x1024 320x250mm 16.0-inch           | 1        | 0.45%   |
| Unknown (XXX) 1772E XXX1772 1280x1024 320x250mm 16.0-inch            | 1        | 0.45%   |
| Toshiba Matsushita Display Technology LCD Monitor LCD-MONITOR        | 1        | 0.45%   |
| TCL T-7005L TCL1770 1280x1024 338x270mm 17.0-inch                    | 1        | 0.45%   |
| Sony TV SNYEB01 1360x768                                             | 1        | 0.45%   |
| Sony TV SNYEA01 1920x1080                                            | 1        | 0.45%   |
| Sony TV SNYDC01 1360x768                                             | 1        | 0.45%   |
| Sony TV SNY4502 1920x1080                                            | 1        | 0.45%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch    | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM05D5 1360x768                      | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM058D 1600x900 443x249mm 20.0-inch  | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch  | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM055E 1920x1080 510x290mm 23.1-inch | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM049C 1920x1080 477x268mm 21.5-inch | 1        | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 49       | 22.79%  |
| 1366x768 (WXGA)    | 38       | 17.67%  |
| 1280x1024 (SXGA)   | 36       | 16.74%  |
| 1440x900 (WXGA+)   | 35       | 16.28%  |
| 1600x900 (HD+)     | 16       | 7.44%   |
| 1360x768           | 11       | 5.12%   |
| 1680x1050 (WSXGA+) | 8        | 3.72%   |
| 1024x768 (XGA)     | 8        | 3.72%   |
| 2560x1440 (QHD)    | 3        | 1.4%    |
| 1280x720 (HD)      | 3        | 1.4%    |
| 3840x2160 (4K)     | 2        | 0.93%   |
| 1920x1200 (WUXGA)  | 2        | 0.93%   |
| Unknown            | 2        | 0.93%   |
| 3840x1080          | 1        | 0.47%   |
| 1600x1200          | 1        | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 53       | 24.65%  |
| 19      | 29       | 13.49%  |
| 17      | 28       | 13.02%  |
| 21      | 19       | 8.84%   |
| Unknown | 15       | 6.98%   |
| 23      | 14       | 6.51%   |
| 15      | 13       | 6.05%   |
| 20      | 11       | 5.12%   |
| 22      | 6        | 2.79%   |
| 72      | 4        | 1.86%   |
| 74      | 3        | 1.4%    |
| 32      | 3        | 1.4%    |
| 31      | 3        | 1.4%    |
| 27      | 3        | 1.4%    |
| 16      | 3        | 1.4%    |
| 24      | 2        | 0.93%   |
| 13      | 2        | 0.93%   |
| 52      | 1        | 0.47%   |
| 42      | 1        | 0.47%   |
| 39      | 1        | 0.47%   |
| 25      | 1        | 0.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 109      | 51.66%  |
| 301-350     | 38       | 18.01%  |
| 501-600     | 20       | 9.48%   |
| Unknown     | 15       | 7.11%   |
| 351-400     | 11       | 5.21%   |
| 1501-2000   | 7        | 3.32%   |
| 701-800     | 3        | 1.42%   |
| 601-700     | 3        | 1.42%   |
| 201-300     | 2        | 0.95%   |
| 801-900     | 1        | 0.47%   |
| 1001-1500   | 1        | 0.47%   |
| 901-1000    | 1        | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 104      | 50.49%  |
| 16/10   | 47       | 22.82%  |
| 5/4     | 32       | 15.53%  |
| 4/3     | 11       | 5.34%   |
| Unknown | 11       | 5.34%   |
| 3/2     | 1        | 0.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 61       | 28.5%   |
| 141-150        | 61       | 28.5%   |
| 201-250        | 35       | 16.36%  |
| Unknown        | 15       | 7.01%   |
| 101-110        | 11       | 5.14%   |
| More than 1000 | 8        | 3.74%   |
| 351-500        | 6        | 2.8%    |
| 301-350        | 3        | 1.4%    |
| 131-140        | 3        | 1.4%    |
| 121-130        | 3        | 1.4%    |
| 251-300        | 2        | 0.93%   |
| 111-120        | 2        | 0.93%   |
| 501-1000       | 2        | 0.93%   |
| 81-90          | 1        | 0.47%   |
| 91-100         | 1        | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 154      | 74.04%  |
| 101-120 | 28       | 13.46%  |
| Unknown | 15       | 7.21%   |
| 1-50    | 10       | 4.81%   |
| 121-160 | 1        | 0.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 202      | 82.45%  |
| 0     | 24       | 9.8%    |
| 2     | 17       | 6.94%   |
| 3     | 2        | 0.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 145      | 39.51%  |
| Intel                             | 62       | 16.89%  |
| Qualcomm Atheros                  | 47       | 12.81%  |
| Ralink                            | 20       | 5.45%   |
| Nvidia                            | 20       | 5.45%   |
| Broadcom                          | 13       | 3.54%   |
| Ralink Technology                 | 12       | 3.27%   |
| Xiaomi                            | 6        | 1.63%   |
| TP-Link                           | 6        | 1.63%   |
| VIA Technologies                  | 5        | 1.36%   |
| Qualcomm Atheros Communications   | 5        | 1.36%   |
| Marvell Technology Group          | 4        | 1.09%   |
| D-Link System                     | 3        | 0.82%   |
| Sundance Technology Inc / IC Plus | 2        | 0.54%   |
| Mercucys                          | 2        | 0.54%   |
| Broadcom Limited                  | 2        | 0.54%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.27%   |
| Trendchip Technologies            | 1        | 0.27%   |
| Samsung Electronics               | 1        | 0.27%   |
| National Semiconductor            | 1        | 0.27%   |
| Motorola PCS                      | 1        | 0.27%   |
| Motorola BCS                      | 1        | 0.27%   |
| MediaTek                          | 1        | 0.27%   |
| JMicron Technology                | 1        | 0.27%   |
| ICS Advent                        | 1        | 0.27%   |
| Davicom Semiconductor             | 1        | 0.27%   |
| ASIX Electronics                  | 1        | 0.27%   |
| ADMtek                            | 1        | 0.27%   |
| Accton Technology                 | 1        | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 97       | 24.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 24       | 6.08%   |
| Nvidia MCP61 Ethernet                                                          | 18       | 4.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16       | 4.05%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 11       | 2.78%   |
| Intel Ethernet Connection I217-LM                                              | 11       | 2.78%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 9        | 2.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 7        | 1.77%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 7        | 1.77%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 6        | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 6        | 1.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 6        | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 6        | 1.52%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 5        | 1.27%   |
| Ralink MT7601U Wireless Adapter                                                | 5        | 1.27%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 5        | 1.27%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 5        | 1.27%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5        | 1.27%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4        | 1.01%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 4        | 1.01%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 4        | 1.01%   |
| Qualcomm Atheros AR9271 802.11n                                                | 4        | 1.01%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                          | 4        | 1.01%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 3        | 0.76%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 3        | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3        | 0.76%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3        | 0.76%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 3        | 0.76%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 3        | 0.76%   |
| Intel Ethernet Connection (14) I219-V                                          | 3        | 0.76%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 2        | 0.51%   |
| TP-Link 802.11n NIC                                                            | 2        | 0.51%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 2        | 0.51%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 2        | 0.51%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                      | 2        | 0.51%   |
| Realtek 802.11ac NIC                                                           | 2        | 0.51%   |
| Ralink RT2561/RT61 802.11g PCI                                                 | 2        | 0.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2        | 0.51%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                               | 2        | 0.51%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                               | 2        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 31       | 24.8%   |
| Qualcomm Atheros                | 31       | 24.8%   |
| Ralink                          | 20       | 16%     |
| Ralink Technology               | 12       | 9.6%    |
| Intel                           | 9        | 7.2%    |
| TP-Link                         | 6        | 4.8%    |
| Qualcomm Atheros Communications | 5        | 4%      |
| Broadcom                        | 4        | 3.2%    |
| D-Link System                   | 3        | 2.4%    |
| Mercucys                        | 2        | 1.6%    |
| Xiaomi                          | 1        | 0.8%    |
| Broadcom Limited                | 1        | 0.8%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 9        | 7.2%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 7        | 5.6%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 6        | 4.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 6        | 4.8%    |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 6        | 4.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 6        | 4.8%    |
| Ralink MT7601U Wireless Adapter                                                | 5        | 4%      |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 5        | 4%      |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 5        | 4%      |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 4        | 3.2%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 4        | 3.2%    |
| Qualcomm Atheros AR9271 802.11n                                                | 4        | 3.2%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 3        | 2.4%    |
| Realtek RTL8188EE Wireless Network Adapter                                     | 3        | 2.4%    |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3        | 2.4%    |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 3        | 2.4%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 2        | 1.6%    |
| TP-Link 802.11n NIC                                                            | 2        | 1.6%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 2        | 1.6%    |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                      | 2        | 1.6%    |
| Realtek 802.11ac NIC                                                           | 2        | 1.6%    |
| Ralink RT2561/RT61 802.11g PCI                                                 | 2        | 1.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2        | 1.6%    |
| Qualcomm Atheros AR922X Wireless Network Adapter                               | 2        | 1.6%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                               | 2        | 1.6%    |
| Mercucys MW300UM RTL8192EU wifi                                                | 2        | 1.6%    |
| Intel Wi-Fi 6 AX200                                                            | 2        | 1.6%    |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]              | 2        | 1.6%    |
| Broadcom BCM43225 802.11b/g/n                                                  | 2        | 1.6%    |
| Xiaomi MediaTek MT7601U [MI WiFi]                                              | 1        | 0.8%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                    | 1        | 0.8%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                         | 1        | 0.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 1        | 0.8%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                | 1        | 0.8%    |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)                      | 1        | 0.8%    |
| Ralink RT5372 Wireless Adapter                                                 | 1        | 0.8%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                         | 1        | 0.8%    |
| Ralink RT2800 802.11n PCI                                                      | 1        | 0.8%    |
| Qualcomm Atheros AR5523                                                        | 1        | 0.8%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 1        | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 130      | 49.62%  |
| Intel                             | 56       | 21.37%  |
| Qualcomm Atheros                  | 20       | 7.63%   |
| Nvidia                            | 20       | 7.63%   |
| Broadcom                          | 9        | 3.44%   |
| Xiaomi                            | 5        | 1.91%   |
| VIA Technologies                  | 5        | 1.91%   |
| Marvell Technology Group          | 4        | 1.53%   |
| Sundance Technology Inc / IC Plus | 2        | 0.76%   |
| Trendchip Technologies            | 1        | 0.38%   |
| National Semiconductor            | 1        | 0.38%   |
| Motorola PCS                      | 1        | 0.38%   |
| Motorola BCS                      | 1        | 0.38%   |
| MediaTek                          | 1        | 0.38%   |
| JMicron Technology                | 1        | 0.38%   |
| ICS Advent                        | 1        | 0.38%   |
| Davicom Semiconductor             | 1        | 0.38%   |
| Broadcom Limited                  | 1        | 0.38%   |
| ASIX Electronics                  | 1        | 0.38%   |
| ADMtek                            | 1        | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 97       | 36.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 24       | 8.99%   |
| Nvidia MCP61 Ethernet                                                      | 18       | 6.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 16       | 5.99%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 11       | 4.12%   |
| Intel Ethernet Connection I217-LM                                          | 11       | 4.12%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 7        | 2.62%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 5        | 1.87%   |
| Intel Ethernet Connection (2) I219-LM                                      | 5        | 1.87%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 4        | 1.5%    |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                      | 4        | 1.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 3        | 1.12%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 3        | 1.12%   |
| Intel Ethernet Connection (14) I219-V                                      | 3        | 1.12%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 2        | 0.75%   |
| Intel PRO/100 VE Network Connection                                        | 2        | 0.75%   |
| Intel Ethernet Connection I217-V                                           | 2        | 0.75%   |
| Intel 82579V Gigabit Network Connection                                    | 2        | 0.75%   |
| Intel 82567V-2 Gigabit Network Connection                                  | 2        | 0.75%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 2        | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1        | 0.37%   |
| Trendchip Ethernet controller                                              | 1        | 0.37%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1        | 0.37%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.37%   |
| Realtek RTL8125 2.5GbE Controller                                          | 1        | 0.37%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 0.37%   |
| Realtek Realtek Ethernet controller                                        | 1        | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 1        | 0.37%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 1        | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 1        | 0.37%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 1        | 0.37%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1        | 0.37%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.37%   |
| Nvidia MCP77 Ethernet                                                      | 1        | 0.37%   |
| Nvidia MCP73 Ethernet                                                      | 1        | 0.37%   |
| National DP83815 (MacPhyter) Ethernet Controller                           | 1        | 0.37%   |
| Motorola PCS moto g84 5G                                                   | 1        | 0.37%   |
| Motorola BCS SurfBoard SB5100 Cable Modem                                  | 1        | 0.37%   |
| MediaTek Infinix SMART 5                                                   | 1        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 240      | 66.12%  |
| WiFi     | 120      | 33.06%  |
| Modem    | 2        | 0.55%   |
| Unknown  | 1        | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 180      | 71.15%  |
| WiFi     | 73       | 28.85%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 163      | 65.73%  |
| 2     | 78       | 31.45%  |
| 3     | 4        | 1.61%   |
| 0     | 2        | 0.81%   |
| 33    | 1        | 0.4%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 243      | 98.78%  |
| Yes  | 3        | 1.22%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 15       | 50%     |
| Intel                   | 7        | 23.33%  |
| Broadcom                | 3        | 10%     |
| IMC Networks            | 2        | 6.67%   |
| ASUSTek Computer        | 2        | 6.67%   |
| Apple                   | 1        | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 15       | 50%     |
| Intel AX201 Bluetooth                               | 3        | 10%     |
| Intel AX200 Bluetooth                               | 2        | 6.67%   |
| IMC Networks Bluetooth Module                       | 2        | 6.67%   |
| Intel Bluetooth wireless interface                  | 1        | 3.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 3.33%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 UHE Dongle | 1        | 3.33%   |
| Broadcom BCM2070 Bluetooth Device                   | 1        | 3.33%   |
| Broadcom BCM2035B3 Bluetooth Adapter                | 1        | 3.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 3.33%   |
| ASUS Bluetooth Adapter                              | 1        | 3.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 184      | 54.28%  |
| AMD                    | 60       | 17.7%   |
| Nvidia                 | 54       | 15.93%  |
| C-Media Electronics    | 9        | 2.65%   |
| VIA Technologies       | 8        | 2.36%   |
| Creative Labs          | 6        | 1.77%   |
| Generalplus Technology | 4        | 1.18%   |
| JMTek                  | 3        | 0.88%   |
| Logitech               | 2        | 0.59%   |
| Unknown                | 1        | 0.29%   |
| Microsoft              | 1        | 0.29%   |
| Megawin Technology     | 1        | 0.29%   |
| M-Audio                | 1        | 0.29%   |
| Jieli Technology       | 1        | 0.29%   |
| Giga-Byte Technology   | 1        | 0.29%   |
| Corsair                | 1        | 0.29%   |
| Cirrus Logic           | 1        | 0.29%   |
| Aureal Semiconductor   | 1        | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 56       | 14.85%  |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 54       | 14.32%  |
| Nvidia MCP61 High Definition Audio                                                | 17       | 4.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 16       | 4.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 15       | 3.98%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 13       | 3.45%   |
| Nvidia GF119 HDMI Audio Controller                                                | 10       | 2.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 10       | 2.65%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 10       | 2.65%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 8        | 2.12%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 7        | 1.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 7        | 1.86%   |
| AMD FCH Azalia Controller                                                         | 7        | 1.86%   |
| Nvidia High Definition Audio Controller                                           | 6        | 1.59%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 6        | 1.59%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 6        | 1.59%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 6        | 1.59%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                    | 5        | 1.33%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                        | 5        | 1.33%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 4        | 1.06%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 4        | 1.06%   |
| Generalplus Technology USB Audio Device                                           | 4        | 1.06%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 4        | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                                     | 3        | 0.8%    |
| Nvidia GF106 High Definition Audio Controller                                     | 3        | 0.8%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 3        | 0.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 0.8%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 3        | 0.8%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 0.8%    |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller       | 2        | 0.53%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 0.53%   |
| Nvidia GK107 HDMI Audio Controller                                                | 2        | 0.53%   |
| Nvidia GF116 High Definition Audio Controller                                     | 2        | 0.53%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 2        | 0.53%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 0.53%   |
| Intel Alder Lake-S HD Audio Controller                                            | 2        | 0.53%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2        | 0.53%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                              | 2        | 0.53%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 2        | 0.53%   |
| C-Media Electronics Cmedia Audio                                                  | 2        | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 60       | 30.3%   |
| Samsung Electronics        | 21       | 10.61%  |
| Kingston                   | 21       | 10.61%  |
| SK hynix                   | 17       | 8.59%   |
| Ramaxel Technology         | 17       | 8.59%   |
| Micron Technology          | 11       | 5.56%   |
| Corsair                    | 11       | 5.56%   |
| Crucial                    | 10       | 5.05%   |
| A-DATA Technology          | 4        | 2.02%   |
| Team                       | 3        | 1.52%   |
| PNY                        | 3        | 1.52%   |
| Nanya Technology           | 3        | 1.52%   |
| Avant                      | 3        | 1.52%   |
| Mushkin                    | 2        | 1.01%   |
| Kreton                     | 2        | 1.01%   |
| Elpida                     | 2        | 1.01%   |
| Unknown                    | 2        | 1.01%   |
| Unknown (FFFF000000000000) | 1        | 0.51%   |
| Unknown (7F7F7F7F7F7F7F83) | 1        | 0.51%   |
| Unknown (0x0CBA)           | 1        | 0.51%   |
| Super Talent               | 1        | 0.51%   |
| Qimonda                    | 1        | 0.51%   |
| OCZ                        | 1        | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                     | 8        | 3.59%   |
| Unknown RAM Module 2GB DIMM DDR2                      | 6        | 2.69%   |
| Unknown RAM Module 4GB DIMM SDRAM                     | 5        | 2.24%   |
| Unknown RAM Module 4GB DIMM 400MT/s                   | 4        | 1.79%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s | 4        | 1.79%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 3        | 1.35%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s             | 3        | 1.35%   |
| Unknown RAM Module 2048MB DIMM DDR2                   | 3        | 1.35%   |
| Unknown RAM Module 1024MB DIMM DDR2                   | 3        | 1.35%   |
| Ramaxel RAM RMR5030ED58E8W1600 2GB DIMM DDR3 1600MT/s | 3        | 1.35%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                  | 2        | 0.9%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s             | 2        | 0.9%    |
| Unknown RAM Module 4GB DIMM 1066MT/s                  | 2        | 0.9%    |
| Unknown RAM Module 2GB DIMM 400MT/s                   | 2        | 0.9%    |
| Unknown RAM Module 2048MB DIMM SDRAM                  | 2        | 0.9%    |
| Unknown RAM Module 1024MB DIMM SDRAM                  | 2        | 0.9%    |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s           | 2        | 0.9%    |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s  | 2        | 0.9%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s  | 2        | 0.9%    |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s             | 2        | 0.9%    |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s   | 2        | 0.9%    |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3            | 2        | 0.9%    |
| Ramaxel RAM RMR5030ME68F9F1600 4GB DIMM DDR3 1600MT/s | 2        | 0.9%    |
| Ramaxel RAM RMR5030EF68F9W1600 4GB DIMM DDR3 1600MT/s | 2        | 0.9%    |
| Ramaxel RAM RMR1870EF48E8W1333 2GB DIMM DDR3 1333MT/s | 2        | 0.9%    |
| Ramaxel RAM RMR1870EC58E9F1333 4GB DIMM DDR3 1333MT/s | 2        | 0.9%    |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s    | 2        | 0.9%    |
| Mushkin RAM MRX4U320NNNF16G 16GB DIMM DDR4 3200MT/s   | 2        | 0.9%    |
| Micron RAM 4ATF51264AZ-3G2R1 4GB DIMM DDR4 3200MT/s   | 2        | 0.9%    |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s   | 2        | 0.9%    |
| Crucial RAM BLS4G3D1609DS 4096MB DIMM DDR3 1600MT/s   | 2        | 0.9%    |
| Unknown                                               | 2        | 0.9%    |
| Unknown RAM Module 8GB DIMM 1600MT/s                  | 1        | 0.45%   |
| Unknown RAM Module 512MB DIMM DDR2                    | 1        | 0.45%   |
| Unknown RAM Module 4GB DIMM 667MT/s                   | 1        | 0.45%   |
| Unknown RAM Module 4096MB DIMM SDRAM                  | 1        | 0.45%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s          | 1        | 0.45%   |
| Unknown RAM Module 4096MB DIMM                        | 1        | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s              | 1        | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s              | 1        | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 66       | 42.58%  |
| DDR2    | 29       | 18.71%  |
| SDRAM   | 22       | 14.19%  |
| Unknown | 18       | 11.61%  |
| DDR4    | 15       | 9.68%   |
| DDR     | 5        | 3.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 144      | 96%     |
| SODIMM | 6        | 4%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 65       | 36.11%  |
| 4096  | 60       | 33.33%  |
| 8192  | 26       | 14.44%  |
| 1024  | 21       | 11.67%  |
| 16384 | 4        | 2.22%   |
| 32768 | 2        | 1.11%   |
| 512   | 2        | 1.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 36       | 20.22%  |
| 1600    | 35       | 19.66%  |
| Unknown | 28       | 15.73%  |
| 667     | 9        | 5.06%   |
| 800     | 8        | 4.49%   |
| 1066    | 7        | 3.93%   |
| 400     | 6        | 3.37%   |
| 3200    | 5        | 2.81%   |
| 533     | 5        | 2.81%   |
| 2133    | 4        | 2.25%   |
| 1800    | 4        | 2.25%   |
| 1639    | 4        | 2.25%   |
| 3733    | 3        | 1.69%   |
| 1867    | 3        | 1.69%   |
| 133     | 3        | 1.69%   |
| 3600    | 2        | 1.12%   |
| 2667    | 2        | 1.12%   |
| 2400    | 2        | 1.12%   |
| 2048    | 2        | 1.12%   |
| 1067    | 2        | 1.12%   |
| 3800    | 1        | 0.56%   |
| 2933    | 1        | 0.56%   |
| 2000    | 1        | 0.56%   |
| 1866    | 1        | 0.56%   |
| 1648    | 1        | 0.56%   |
| 1334    | 1        | 0.56%   |
| 1024    | 1        | 0.56%   |
| 266     | 1        | 0.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 5        | 55.56%  |
| Seiko Epson         | 3        | 33.33%  |
| Samsung Electronics | 1        | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 11.11%  |
| Seiko Epson L210 Series                      | 1        | 11.11%  |
| Seiko Epson ET-3750 Series                   | 1        | 11.11%  |
| Samsung ML-216x Series Laser Printer         | 1        | 11.11%  |
| HP LaserJet P1006                            | 1        | 11.11%  |
| HP LaserJet P1005                            | 1        | 11.11%  |
| HP DeskJet F4100 Printer series              | 1        | 11.11%  |
| HP Deskjet 2050 J510                         | 1        | 11.11%  |
| HP Color LaserJet CP1215                     | 1        | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| KYE Systems (Mouse Systems) | 1        | 33.33%  |
| Hewlett-Packard             | 1        | 33.33%  |
| Canon                       | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| KYE Systems (Mouse Systems) ColorPage-Vivid 1200 XE | 1        | 33.33%  |
| HP Scanjet 200                                      | 1        | 33.33%  |
| Canon CanoScan LiDE 110                             | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 7        | 23.33%  |
| Microsoft                   | 4        | 13.33%  |
| Samsung Electronics         | 3        | 10%     |
| IMC Networks                | 2        | 6.67%   |
| Cubeternet                  | 2        | 6.67%   |
| Z-Star Microelectronics     | 1        | 3.33%   |
| Suyin                       | 1        | 3.33%   |
| SN0002                      | 1        | 3.33%   |
| SiGma Micro                 | 1        | 3.33%   |
| Realtek Semiconductor       | 1        | 3.33%   |
| Microdia                    | 1        | 3.33%   |
| LG Electronics              | 1        | 3.33%   |
| KYE Systems (Mouse Systems) | 1        | 3.33%   |
| KYE Systems                 | 1        | 3.33%   |
| Jieli Technology            | 1        | 3.33%   |
| Chicony Electronics         | 1        | 3.33%   |
| Aveo Technology             | 1        | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode)               | 3        | 10%     |
| Logitech Webcam C270                                  | 3        | 10%     |
| Logitech QuickCam Communicate MP/S5500                | 2        | 6.67%   |
| Cubeternet USB2.0 Camera                              | 2        | 6.67%   |
| Z-Star Venus USB2.0 Camera                            | 1        | 3.33%   |
| Suyin HP Webcam                                       | 1        | 3.33%   |
| SN0002 1080P Web Camera                               | 1        | 3.33%   |
| SiGma Micro WebCam SiGma Micro                        | 1        | 3.33%   |
| Realtek HP 1.0MP High Definition Webcam               | 1        | 3.33%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks   | 1        | 3.33%   |
| Microsoft LifeCam VX-5000                             | 1        | 3.33%   |
| Microsoft LifeCam Studio                              | 1        | 3.33%   |
| Microsoft LifeCam HD-3000                             | 1        | 3.33%   |
| Microdia Webcam Vitade AF                             | 1        | 3.33%   |
| Logitech HD Pro Webcam C920                           | 1        | 3.33%   |
| Logitech C922 Pro Stream Webcam                       | 1        | 3.33%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 3.33%   |
| KYE Systems FaceCam 1320                              | 1        | 3.33%   |
| KYE Systems (Mouse Systems) eFace 2025                | 1        | 3.33%   |
| Jieli USB PHY 2.0                                     | 1        | 3.33%   |
| IMC Networks USB2.0 UVC 1.3M WebCam                   | 1        | 3.33%   |
| IMC Networks USB 2.0 Camera                           | 1        | 3.33%   |
| Chicony HD Webcam                                     | 1        | 3.33%   |
| Aveo USB2.0 Camera                                    | 1        | 3.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Suprema | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Suprema SUP-SFR400(A) BioMini Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 192      | 78.05%  |
| 1     | 48       | 19.51%  |
| 2     | 4        | 1.63%   |
| 6     | 1        | 0.41%   |
| 3     | 1        | 0.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 27       | 45%     |
| Communication controller | 10       | 16.67%  |
| Net/wireless             | 7        | 11.67%  |
| Sound                    | 4        | 6.67%   |
| Multimedia controller    | 4        | 6.67%   |
| Firewire controller      | 2        | 3.33%   |
| Video                    | 1        | 1.67%   |
| Storage/ide              | 1        | 1.67%   |
| Net/ethernet             | 1        | 1.67%   |
| Fingerprint reader       | 1        | 1.67%   |
| Card reader              | 1        | 1.67%   |
| Camera                   | 1        | 1.67%   |


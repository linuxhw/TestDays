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

Total: 280

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 14       | 6.7%    |
| Debian 11          | 14       | 6.7%    |
| Ubuntu 18.04       | 10       | 4.78%   |
| OpenMandriva 4.3   | 10       | 4.78%   |
| OpenMandriva 23.03 | 9        | 4.31%   |
| Ubuntu 22.04       | 8        | 3.83%   |
| Zorin 16           | 7        | 3.35%   |
| OpenMandriva 4.2   | 7        | 3.35%   |
| OpenMandriva 23.08 | 7        | 3.35%   |
| OpenMandriva 23.01 | 5        | 2.39%   |
| Linux Mint 21.1    | 5        | 2.39%   |
| Linux Mint 20.3    | 5        | 2.39%   |
| Xubuntu 18.04      | 4        | 1.91%   |
| ROSA R11           | 4        | 1.91%   |
| Linux Mint 21.2    | 4        | 1.91%   |
| Arch Rolling       | 4        | 1.91%   |
| OpenMandriva 4.50  | 3        | 1.44%   |
| Linux Mint 20.1    | 3        | 1.44%   |
| Linux Mint 20      | 3        | 1.44%   |
| Linux Mint 19.3    | 3        | 1.44%   |
| KDE neon 20.04     | 3        | 1.44%   |
| Fedora 38          | 3        | 1.44%   |
| Debian 12          | 3        | 1.44%   |
| Debian 10          | 3        | 1.44%   |
| ArcoLinux Rolling  | 3        | 1.44%   |
| Zorin 15           | 2        | 0.96%   |
| Xubuntu 16.04      | 2        | 0.96%   |
| Ubuntu 20.10       | 2        | 0.96%   |
| ROSA R9            | 2        | 0.96%   |
| MX 21              | 2        | 0.96%   |
| Manjaro            | 2        | 0.96%   |
| Kubuntu 22.04      | 2        | 0.96%   |
| Kubuntu 20.04      | 2        | 0.96%   |
| Elementary 7       | 2        | 0.96%   |
| Xubuntu 20.04      | 1        | 0.48%   |
| Xero Rolling       | 1        | 0.48%   |
| Ubuntu Unity 18.04 | 1        | 0.48%   |
| Ubuntu MATE 22.04  | 1        | 0.48%   |
| Ubuntu MATE 19.10  | 1        | 0.48%   |
| Ubuntu 22.10       | 1        | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| OpenMandriva | 40       | 19.61%  |
| Ubuntu       | 37       | 18.14%  |
| Linux Mint   | 26       | 12.75%  |
| Debian       | 24       | 11.76%  |
| ROSA         | 11       | 5.39%   |
| Zorin        | 9        | 4.41%   |
| Xubuntu      | 6        | 2.94%   |
| Fedora       | 6        | 2.94%   |
| KDE neon     | 5        | 2.45%   |
| Arch         | 5        | 2.45%   |
| Kubuntu      | 4        | 1.96%   |
| Elementary   | 4        | 1.96%   |
| Nobara       | 3        | 1.47%   |
| Manjaro      | 3        | 1.47%   |
| ArcoLinux    | 3        | 1.47%   |
| Ubuntu MATE  | 2        | 0.98%   |
| MX           | 2        | 0.98%   |
| Xero         | 1        | 0.49%   |
| Ubuntu Unity | 1        | 0.49%   |
| Sparky       | 1        | 0.49%   |
| Solus        | 1        | 0.49%   |
| Q4OS         | 1        | 0.49%   |
| Pop!_OS      | 1        | 0.49%   |
| PCLinuxOS    | 1        | 0.49%   |
| Lubuntu      | 1        | 0.49%   |
| LMDE         | 1        | 0.49%   |
| Kali         | 1        | 0.49%   |
| Garuda Linux | 1        | 0.49%   |
| Frnsf        | 1        | 0.49%   |
| Feren OS     | 1        | 0.49%   |
| Endless      | 1        | 0.49%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003        | 10       | 4.46%   |
| 6.2.6-desktop-1omv2390         | 9        | 4.02%   |
| 5.10.14-desktop-1omv4002       | 7        | 3.13%   |
| 6.1.1-desktop-1omv2290         | 5        | 2.23%   |
| 6.4.11-desktop-1omv2390        | 4        | 1.79%   |
| 5.4.0-42-generic               | 4        | 1.79%   |
| 6.4.8-desktop-2omv2390         | 3        | 1.34%   |
| 6.2.0-32-generic               | 2        | 0.89%   |
| 6.2.0-26-generic               | 2        | 0.89%   |
| 5.8.0-55-generic               | 2        | 0.89%   |
| 5.4.0-77-generic               | 2        | 0.89%   |
| 5.4.0-74-generic               | 2        | 0.89%   |
| 5.4.0-54-generic               | 2        | 0.89%   |
| 5.4.0-26-generic               | 2        | 0.89%   |
| 5.4.0-166-generic              | 2        | 0.89%   |
| 5.3.0-40-generic               | 2        | 0.89%   |
| 5.19.0-41-generic              | 2        | 0.89%   |
| 5.19.0-35-generic              | 2        | 0.89%   |
| 5.15.0-76-generic              | 2        | 0.89%   |
| 5.15.0-71-generic              | 2        | 0.89%   |
| 5.15.0-67-generic              | 2        | 0.89%   |
| 5.15.0-58-generic              | 2        | 0.89%   |
| 5.15.0-56-generic              | 2        | 0.89%   |
| 5.15.0-53-generic              | 2        | 0.89%   |
| 5.15.0-46-generic              | 2        | 0.89%   |
| 5.13.0-27-generic              | 2        | 0.89%   |
| 5.10.0-8-amd64                 | 2        | 0.89%   |
| 5.10.0-16-amd64                | 2        | 0.89%   |
| 5.10.0-14-amd64                | 2        | 0.89%   |
| 5.10.0-11-amd64                | 2        | 0.89%   |
| 4.15.0-desktop-45.1rosa-x86_64 | 2        | 0.89%   |
| 4.15.0-48-generic              | 2        | 0.89%   |
| 4.15.0-112-generic             | 2        | 0.89%   |
| 6.6.4-200.fsync.fc38.x86_64    | 1        | 0.45%   |
| 6.6.3-arch1-1                  | 1        | 0.45%   |
| 6.6.2-desktop-1omv2390         | 1        | 0.45%   |
| 6.6.1-arch1-1                  | 1        | 0.45%   |
| 6.5.7-200.fc38.x86_64          | 1        | 0.45%   |
| 6.5.11-1-MANJARO               | 1        | 0.45%   |
| 6.5.0-14-generic               | 1        | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 27       | 12.8%   |
| 5.15.0  | 24       | 11.37%  |
| 4.15.0  | 19       | 9%      |
| 5.10.0  | 17       | 8.06%   |
| 5.16.7  | 10       | 4.74%   |
| 6.2.6   | 9        | 4.27%   |
| 5.10.14 | 7        | 3.32%   |
| 5.8.0   | 6        | 2.84%   |
| 5.13.0  | 6        | 2.84%   |
| 6.2.0   | 5        | 2.37%   |
| 6.1.1   | 5        | 2.37%   |
| 5.3.0   | 5        | 2.37%   |
| 5.19.0  | 5        | 2.37%   |
| 6.4.11  | 4        | 1.9%    |
| 6.1.0   | 4        | 1.9%    |
| 6.4.8   | 3        | 1.42%   |
| 5.11.0  | 3        | 1.42%   |
| 5.0.0   | 3        | 1.42%   |
| 4.19.0  | 3        | 1.42%   |
| 6.4.6   | 2        | 0.95%   |
| 6.4.3   | 2        | 0.95%   |
| 6.2.12  | 2        | 0.95%   |
| 4.9.20  | 2        | 0.95%   |
| 4.9.0   | 2        | 0.95%   |
| 6.6.4   | 1        | 0.47%   |
| 6.6.3   | 1        | 0.47%   |
| 6.6.2   | 1        | 0.47%   |
| 6.6.1   | 1        | 0.47%   |
| 6.5.7   | 1        | 0.47%   |
| 6.5.11  | 1        | 0.47%   |
| 6.5.0   | 1        | 0.47%   |
| 6.4.7   | 1        | 0.47%   |
| 6.3.8   | 1        | 0.47%   |
| 6.1.20  | 1        | 0.47%   |
| 6.0.5   | 1        | 0.47%   |
| 6.0.0   | 1        | 0.47%   |
| 5.9.16  | 1        | 0.47%   |
| 5.8.11  | 1        | 0.47%   |
| 5.8.10  | 1        | 0.47%   |
| 5.6.0   | 1        | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 28       | 13.4%   |
| 5.4     | 27       | 12.92%  |
| 5.15    | 26       | 12.44%  |
| 4.15    | 19       | 9.09%   |
| 6.2     | 16       | 7.66%   |
| 6.4     | 12       | 5.74%   |
| 5.16    | 11       | 5.26%   |
| 6.1     | 9        | 4.31%   |
| 5.8     | 8        | 3.83%   |
| 5.19    | 8        | 3.83%   |
| 5.13    | 8        | 3.83%   |
| 5.3     | 5        | 2.39%   |
| 6.6     | 4        | 1.91%   |
| 4.9     | 4        | 1.91%   |
| 6.5     | 3        | 1.44%   |
| 5.11    | 3        | 1.44%   |
| 5.0     | 3        | 1.44%   |
| 4.19    | 3        | 1.44%   |
| 6.0     | 2        | 0.96%   |
| 6.3     | 1        | 0.48%   |
| 5.9     | 1        | 0.48%   |
| 5.6     | 1        | 0.48%   |
| 5.18    | 1        | 0.48%   |
| 5.14    | 1        | 0.48%   |
| 5.12    | 1        | 0.48%   |
| 4.4     | 1        | 0.48%   |
| 4.18    | 1        | 0.48%   |
| 4.13    | 1        | 0.48%   |
| 4.1     | 1        | 0.48%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 183      | 91.5%   |
| i686   | 17       | 8.5%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| KDE5            | 63       | 30.43%  |
| GNOME           | 55       | 26.57%  |
| XFCE            | 19       | 9.18%   |
| X-Cinnamon      | 15       | 7.25%   |
| Unknown         | 15       | 7.25%   |
| MATE            | 7        | 3.38%   |
| KDE             | 6        | 2.9%    |
| LXQt            | 5        | 2.42%   |
| LXDE            | 5        | 2.42%   |
| KDE4            | 4        | 1.93%   |
| Pantheon        | 3        | 1.45%   |
| Cinnamon        | 3        | 1.45%   |
| xmonad          | 1        | 0.48%   |
| Unity           | 1        | 0.48%   |
| Trinity         | 1        | 0.48%   |
| i3              | 1        | 0.48%   |
| GNOME Flashback | 1        | 0.48%   |
| Budgie          | 1        | 0.48%   |
| awesome         | 1        | 0.48%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 164      | 80.39%  |
| Wayland | 35       | 17.16%  |
| Unknown | 4        | 1.96%   |
| Tty     | 1        | 0.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 82       | 40.39%  |
| SDDM    | 60       | 29.56%  |
| LightDM | 19       | 9.36%   |
| GDM     | 15       | 7.39%   |
| GDM3    | 14       | 6.9%    |
| TDM     | 7        | 3.45%   |
| KDM     | 4        | 1.97%   |
| SLiM    | 2        | 0.99%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_VE   | 123      | 60.29%  |
| en_US   | 40       | 19.61%  |
| Unknown | 17       | 8.33%   |
| es_ES   | 10       | 4.9%    |
| es_MX   | 7        | 3.43%   |
| es_US   | 2        | 0.98%   |
| es_CO   | 2        | 0.98%   |
| C       | 2        | 0.98%   |
| de_DE   | 1        | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 163      | 81.91%  |
| EFI  | 36       | 18.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 145      | 71.08%  |
| Overlay | 29       | 14.22%  |
| Btrfs   | 15       | 7.35%   |
| Tmpfs   | 5        | 2.45%   |
| Unknown | 5        | 2.45%   |
| Xfs     | 3        | 1.47%   |
| Ext3    | 1        | 0.49%   |
| Ext2    | 1        | 0.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 90       | 44.33%  |
| MBR     | 71       | 34.98%  |
| GPT     | 42       | 20.69%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 161      | 80.5%   |
| Yes       | 39       | 19.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 123      | 60.89%  |
| Yes       | 79       | 39.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASRock              | 37       | 18.69%  |
| ECS                 | 19       | 9.6%    |
| Hewlett-Packard     | 18       | 9.09%   |
| Intel               | 16       | 8.08%   |
| Gigabyte Technology | 16       | 8.08%   |
| Pegatron            | 14       | 7.07%   |
| Lenovo              | 14       | 7.07%   |
| ASUSTek Computer    | 13       | 6.57%   |
| Dell                | 12       | 6.06%   |
| Biostar             | 12       | 6.06%   |
| Foxconn             | 7        | 3.54%   |
| MSI                 | 6        | 3.03%   |
| langchao            | 6        | 3.03%   |
| Inspur              | 3        | 1.52%   |
| Soncview            | 1        | 0.51%   |
| SIRAGON             | 1        | 0.51%   |
| IP3 Tech            | 1        | 0.51%   |
| IBM                 | 1        | 0.51%   |
| Unknown             | 1        | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ECS H61H2-CM                         | 11       | 5.56%   |
| ASRock G41M-VS3                      | 7        | 3.54%   |
| langchao 12345                       | 6        | 3.03%   |
| ASRock N68C-S UCC                    | 4        | 2.02%   |
| ASRock N68-VS3 UCC                   | 4        | 2.02%   |
| Pegatron Compaq dx2400 Microtower    | 3        | 1.52%   |
| HP Compaq 8200 Elite SFF PC          | 3        | 1.52%   |
| Biostar G41D3                        | 3        | 1.52%   |
| Pegatron IPM41-D3                    | 2        | 1.01%   |
| Lenovo ThinkCentre A57 9702AB7       | 2        | 1.01%   |
| Intel H61                            | 2        | 1.01%   |
| Inspur VIT E2250                     | 2        | 1.01%   |
| HP EliteDesk 800 G1 USDT             | 2        | 1.01%   |
| HP EliteDesk 800 G1 SFF              | 2        | 1.01%   |
| HP Compaq Elite 8300 SFF             | 2        | 1.01%   |
| Gigabyte 970A-DS3P                   | 2        | 1.01%   |
| ECS H61H2-MV                         | 2        | 1.01%   |
| ECS G31T-M7                          | 2        | 1.01%   |
| Dell OptiPlex 9020                   | 2        | 1.01%   |
| Dell OptiPlex 790                    | 2        | 1.01%   |
| Dell Inspiron 3891                   | 2        | 1.01%   |
| Biostar G41D3C                       | 2        | 1.01%   |
| ASRock Wolfdale1333-D667             | 2        | 1.01%   |
| ASRock H61M-VG3                      | 2        | 1.01%   |
| ASRock AM2NF6G-VSTA                  | 2        | 1.01%   |
| ASRock 945GCM-S                      | 2        | 1.01%   |
| Soncview G41D3C                      | 1        | 0.51%   |
| SIRAGON AIO-5150                     | 1        | 0.51%   |
| Pegatron PEGATRON                    | 1        | 0.51%   |
| Pegatron IPPEL-DB                    | 1        | 0.51%   |
| Pegatron IPMIP-H55-INSPUR            | 1        | 0.51%   |
| Pegatron CQ1507LA                    | 1        | 0.51%   |
| Pegatron Compaq dx2400 Microtower PC | 1        | 0.51%   |
| Pegatron BM411AA-ABA CQ5600F         | 1        | 0.51%   |
| Pegatron 2A73h                       | 1        | 0.51%   |
| Pegatron 20-b010                     | 1        | 0.51%   |
| Pegatron 100-5010la                  | 1        | 0.51%   |
| MSI Pro 3000 Microtower PC           | 1        | 0.51%   |
| MSI MS-7A38                          | 1        | 0.51%   |
| MSI MS-7850                          | 1        | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| Lenovo ThinkCentre        | 11       | 5.56%   |
| HP Compaq                 | 11       | 5.56%   |
| ECS H61H2-CM              | 11       | 5.56%   |
| Dell OptiPlex             | 7        | 3.54%   |
| ASRock G41M-VS3           | 7        | 3.54%   |
| langchao 12345            | 6        | 3.03%   |
| ASRock N68-VS3            | 5        | 2.53%   |
| Pegatron Compaq           | 4        | 2.02%   |
| HP EliteDesk              | 4        | 2.02%   |
| ASRock N68C-S             | 4        | 2.02%   |
| Biostar G41D3             | 3        | 1.52%   |
| Pegatron IPM41-D3         | 2        | 1.01%   |
| Intel H61                 | 2        | 1.01%   |
| Intel DG41TY              | 2        | 1.01%   |
| Inspur VIT                | 2        | 1.01%   |
| Gigabyte 970A-DS3P        | 2        | 1.01%   |
| ECS H61H2-MV              | 2        | 1.01%   |
| ECS G31T-M7               | 2        | 1.01%   |
| Dell Vostro               | 2        | 1.01%   |
| Dell Inspiron             | 2        | 1.01%   |
| Biostar G41D3C            | 2        | 1.01%   |
| ASUS Rampage              | 2        | 1.01%   |
| ASUS PRIME                | 2        | 1.01%   |
| ASUS P8H61-M              | 2        | 1.01%   |
| ASUS P5G41T-M             | 2        | 1.01%   |
| ASRock Wolfdale1333-D667  | 2        | 1.01%   |
| ASRock H61M-VG3           | 2        | 1.01%   |
| ASRock H61M-DGS           | 2        | 1.01%   |
| ASRock AM2NF6G-VSTA       | 2        | 1.01%   |
| ASRock 945GCM-S           | 2        | 1.01%   |
| Soncview G41D3C           | 1        | 0.51%   |
| SIRAGON AIO-5150          | 1        | 0.51%   |
| Pegatron PEGATRON         | 1        | 0.51%   |
| Pegatron IPPEL-DB         | 1        | 0.51%   |
| Pegatron IPMIP-H55-INSPUR | 1        | 0.51%   |
| Pegatron CQ1507LA         | 1        | 0.51%   |
| Pegatron BM411AA-ABA      | 1        | 0.51%   |
| Pegatron 2A73h            | 1        | 0.51%   |
| Pegatron 20-b010          | 1        | 0.51%   |
| Pegatron 100-5010la       | 1        | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 45       | 22.73%  |
| 2010 | 37       | 18.69%  |
| 2012 | 22       | 11.11%  |
| 2008 | 20       | 10.1%   |
| 2007 | 13       | 6.57%   |
| 2013 | 12       | 6.06%   |
| 2014 | 9        | 4.55%   |
| 2009 | 9        | 4.55%   |
| 2006 | 8        | 4.04%   |
| 2020 | 6        | 3.03%   |
| 2021 | 5        | 2.53%   |
| 2017 | 4        | 2.02%   |
| 2016 | 3        | 1.52%   |
| 2019 | 2        | 1.01%   |
| 2015 | 1        | 0.51%   |
| 2005 | 1        | 0.51%   |
| 2002 | 1        | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 198      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 197      | 99.49%  |
| Enabled  | 1        | 0.51%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 198      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 56       | 27.32%  |
| 4.01-8.0    | 46       | 22.44%  |
| 8.01-16.0   | 35       | 17.07%  |
| 1.01-2.0    | 28       | 13.66%  |
| 16.01-24.0  | 20       | 9.76%   |
| 2.01-3.0    | 8        | 3.9%    |
| 32.01-64.0  | 4        | 1.95%   |
| 24.01-32.0  | 4        | 1.95%   |
| 64.01-256.0 | 2        | 0.98%   |
| 0.51-1.0    | 2        | 0.98%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 91       | 42.33%  |
| 2.01-3.0 | 50       | 23.26%  |
| 0.51-1.0 | 28       | 13.02%  |
| 4.01-8.0 | 21       | 9.77%   |
| 3.01-4.0 | 20       | 9.3%    |
| 0.01-0.5 | 5        | 2.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 111      | 54.41%  |
| 2      | 68       | 33.33%  |
| 3      | 20       | 9.8%    |
| 4      | 5        | 2.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 121      | 59.31%  |
| Yes       | 83       | 40.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 194      | 97.98%  |
| No        | 4        | 2.02%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 101      | 50.25%  |
| No        | 100      | 49.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 176      | 88.44%  |
| Yes       | 23       | 11.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Venezuela | 198      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Desktops | Percent |
|----------------------------|----------|---------|
| Caracas                    | 84       | 39.81%  |
| Maracaibo                  | 14       | 6.64%   |
| San Cristóbal             | 11       | 5.21%   |
| Barquisimeto               | 10       | 4.74%   |
| Valencia                   | 9        | 4.27%   |
| Maracay                    | 9        | 4.27%   |
| San Carlos del Zulia       | 7        | 3.32%   |
| Maturín                   | 5        | 2.37%   |
| Barcelona                  | 5        | 2.37%   |
| Vigia                      | 4        | 1.9%    |
| Ciudad Guayana             | 4        | 1.9%    |
| Mérida                    | 3        | 1.42%   |
| Ciudad Bolívar            | 3        | 1.42%   |
| Carrizal                   | 3        | 1.42%   |
| Barinas                    | 3        | 1.42%   |
| San Antonio de Los Altos   | 2        | 0.95%   |
| Porlamar                   | 2        | 0.95%   |
| Los Teques                 | 2        | 0.95%   |
| Lecherias                  | 2        | 0.95%   |
| Acarigua                   | 2        | 0.95%   |
| Zulia                      | 1        | 0.47%   |
| Valle de La Pascua         | 1        | 0.47%   |
| Tucupita                   | 1        | 0.47%   |
| San Juan Bautista          | 1        | 0.47%   |
| San Francisco              | 1        | 0.47%   |
| Puerto Ordaz and San Felix | 1        | 0.47%   |
| Petare                     | 1        | 0.47%   |
| Parroquia El Recreo        | 1        | 0.47%   |
| Miranda                    | 1        | 0.47%   |
| Mene Grande                | 1        | 0.47%   |
| Los Palos Grandes          | 1        | 0.47%   |
| Las Vegas                  | 1        | 0.47%   |
| La Guaira                  | 1        | 0.47%   |
| Guatire                    | 1        | 0.47%   |
| Guarenas                   | 1        | 0.47%   |
| Distrito Federal           | 1        | 0.47%   |
| Cumaná                    | 1        | 0.47%   |
| Cua                        | 1        | 0.47%   |
| Coro                       | 1        | 0.47%   |
| Ciudad Ojeda               | 1        | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 84       | 116    | 28.87%  |
| Seagate             | 64       | 87     | 21.99%  |
| Hitachi             | 37       | 44     | 12.71%  |
| Samsung Electronics | 29       | 33     | 9.97%   |
| Kingston            | 19       | 21     | 6.53%   |
| Toshiba             | 16       | 18     | 5.5%    |
| Maxtor              | 7        | 7      | 2.41%   |
| SK hynix            | 3        | 3      | 1.03%   |
| PNY                 | 3        | 5      | 1.03%   |
| Patriot             | 3        | 3      | 1.03%   |
| Crucial             | 3        | 4      | 1.03%   |
| Team                | 2        | 3      | 0.69%   |
| SPCC                | 2        | 2      | 0.69%   |
| Sandisk             | 2        | 3      | 0.69%   |
| HGST                | 2        | 2      | 0.69%   |
| Fujitsu             | 2        | 2      | 0.69%   |
| addlink             | 2        | 2      | 0.69%   |
| Unknown             | 1        | 1      | 0.34%   |
| Phison Electronics  | 1        | 1      | 0.34%   |
| Netac               | 1        | 1      | 0.34%   |
| JMicron Technology  | 1        | 1      | 0.34%   |
| IBM/Hitachi         | 1        | 2      | 0.34%   |
| HPE                 | 1        | 2      | 0.34%   |
| ExcelStor           | 1        | 1      | 0.34%   |
| Emtec               | 1        | 1      | 0.34%   |
| Dogfish             | 1        | 1      | 0.34%   |
| Dahua               | 1        | 1      | 0.34%   |
| A-DATA Technology   | 1        | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST320LT012-1DG14C 320GB     | 11       | 3.41%   |
| Toshiba DT01ACA050 500GB            | 10       | 3.1%    |
| WDC WD5000AAKX-22ERMA0 500GB        | 8        | 2.48%   |
| Kingston SA400S37240G 240GB SSD     | 7        | 2.17%   |
| Seagate ST500DM002-1BD142 500GB     | 6        | 1.86%   |
| Samsung HD502HJ 500GB               | 6        | 1.86%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 4        | 1.24%   |
| WDC WD3200AAJS-08L7A0 320GB         | 4        | 1.24%   |
| WDC WD3200AAJS-00L7A0 320GB         | 4        | 1.24%   |
| Seagate ST3320418AS 320GB           | 4        | 1.24%   |
| Seagate ST320LM000 HM321HI 320GB    | 4        | 1.24%   |
| Samsung HD161HJ 160GB               | 4        | 1.24%   |
| Kingston SA400S37120G 120GB SSD     | 4        | 1.24%   |
| Hitachi HTS543225L9A300 250GB       | 4        | 1.24%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 3        | 0.93%   |
| WDC WD5000AAKX-221CA1 500GB         | 3        | 0.93%   |
| WDC WD5000AAKX-001CA0 500GB         | 3        | 0.93%   |
| WDC WD5000AAKS-00A7B0 500GB         | 3        | 0.93%   |
| WDC WD1600AABS-00PRA0 160GB         | 3        | 0.93%   |
| WDC WD10EZEX-60ZF5A0 1TB            | 3        | 0.93%   |
| Seagate ST4000DM000-1F2168 4TB      | 3        | 0.93%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 3        | 0.93%   |
| Samsung HD322HJ 320GB               | 3        | 0.93%   |
| Samsung HD161GJ 160GB               | 3        | 0.93%   |
| Maxtor STM3160215AS 160GB           | 3        | 0.93%   |
| Hitachi HTS542580K9SA00 80GB        | 3        | 0.93%   |
| Hitachi HDS728080PLA380 82GB        | 3        | 0.93%   |
| Hitachi HDS5C1050CLA382 500GB       | 3        | 0.93%   |
| WDC WD800BD-22MRA1 80GB             | 2        | 0.62%   |
| WDC WD800BB-22JHC0 80GB             | 2        | 0.62%   |
| WDC WD5000AAKX-753CA1 500GB         | 2        | 0.62%   |
| WDC WD2500AAJS-60B4A0 250GB         | 2        | 0.62%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 2        | 0.62%   |
| WDC WD10EZEX-22RKKA0 1TB            | 2        | 0.62%   |
| WDC WD10EZEX-22MFCA0 1TB            | 2        | 0.62%   |
| SK hynix C2S3T/256G 256GB           | 2        | 0.62%   |
| Seagate ST500DM005 HD502HJ 500GB    | 2        | 0.62%   |
| Seagate ST500DM002-1BC142 500GB     | 2        | 0.62%   |
| Seagate ST3500413AS 500GB           | 2        | 0.62%   |
| Seagate ST3500312CS 500GB           | 2        | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 83       | 115    | 34.73%  |
| Seagate             | 64       | 87     | 26.78%  |
| Hitachi             | 37       | 44     | 15.48%  |
| Samsung Electronics | 24       | 27     | 10.04%  |
| Toshiba             | 16       | 18     | 6.69%   |
| Maxtor              | 7        | 7      | 2.93%   |
| HGST                | 2        | 2      | 0.84%   |
| Fujitsu             | 2        | 2      | 0.84%   |
| JMicron Technology  | 1        | 1      | 0.42%   |
| IBM/Hitachi         | 1        | 2      | 0.42%   |
| HPE                 | 1        | 1      | 0.42%   |
| ExcelStor           | 1        | 1      | 0.42%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 18       | 20     | 40%     |
| Samsung Electronics | 3        | 4      | 6.67%   |
| PNY                 | 3        | 5      | 6.67%   |
| Patriot             | 3        | 3      | 6.67%   |
| Crucial             | 3        | 4      | 6.67%   |
| Team                | 2        | 3      | 4.44%   |
| SPCC                | 2        | 2      | 4.44%   |
| SK hynix            | 2        | 2      | 4.44%   |
| addlink             | 2        | 2      | 4.44%   |
| WDC                 | 1        | 1      | 2.22%   |
| SanDisk             | 1        | 1      | 2.22%   |
| Netac               | 1        | 1      | 2.22%   |
| Emtec               | 1        | 1      | 2.22%   |
| Dogfish             | 1        | 1      | 2.22%   |
| Dahua               | 1        | 1      | 2.22%   |
| A-DATA Technology   | 1        | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 176      | 307    | 77.88%  |
| SSD     | 41       | 52     | 18.14%  |
| NVMe    | 8        | 8      | 3.54%   |
| Unknown | 1        | 1      | 0.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 195      | 359    | 95.59%  |
| NVMe | 8        | 8      | 3.92%   |
| SAS  | 1        | 1      | 0.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 178      | 298    | 78.76%  |
| 0.51-1.0   | 32       | 39     | 14.16%  |
| 1.01-2.0   | 9        | 10     | 3.98%   |
| 3.01-4.0   | 4        | 8      | 1.77%   |
| 2.01-3.0   | 2        | 3      | 0.88%   |
| 4.01-10.0  | 1        | 1      | 0.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 64       | 30.19%  |
| 101-250        | 47       | 22.17%  |
| 501-1000       | 29       | 13.68%  |
| 1-20           | 23       | 10.85%  |
| 51-100         | 17       | 8.02%   |
| 1001-2000      | 14       | 6.6%    |
| 21-50          | 8        | 3.77%   |
| 2001-3000      | 4        | 1.89%   |
| Unknown        | 4        | 1.89%   |
| More than 3000 | 2        | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 93       | 44.08%  |
| 21-50          | 35       | 16.59%  |
| 101-250        | 25       | 11.85%  |
| 251-500        | 20       | 9.48%   |
| 51-100         | 16       | 7.58%   |
| 501-1000       | 10       | 4.74%   |
| 1001-2000      | 5        | 2.37%   |
| Unknown        | 4        | 1.9%    |
| 2001-3000      | 2        | 0.95%   |
| More than 3000 | 1        | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST320LT012-1DG14C 320GB   | 6        | 7      | 6.9%    |
| WDC WD5000AAKX-22ERMA0 500GB      | 5        | 6      | 5.75%   |
| Toshiba DT01ACA050 500GB          | 4        | 5      | 4.6%    |
| Hitachi HTS543225L9A300 250GB     | 4        | 4      | 4.6%    |
| WDC WD5000AAKX-221CA1 500GB       | 2        | 2      | 2.3%    |
| WDC WD5000AAKS-00A7B0 500GB       | 2        | 2      | 2.3%    |
| WDC WD3200AAJS-08L7A0 320GB       | 2        | 3      | 2.3%    |
| Seagate ST500DM002-1BD142 500GB   | 2        | 2      | 2.3%    |
| Seagate ST3500312CS 500GB         | 2        | 2      | 2.3%    |
| Samsung Electronics HD161GJ 160GB | 2        | 2      | 2.3%    |
| Maxtor STM3160215AS 160GB         | 2        | 2      | 2.3%    |
| Hitachi HDS728080PLA380 82GB      | 2        | 2      | 2.3%    |
| Hitachi HDS721616PLA380 160GB     | 2        | 2      | 2.3%    |
| WDC WD800BD-08MRA1 80GB           | 1        | 1      | 1.15%   |
| WDC WD800BB-22JHC0 80GB           | 1        | 1      | 1.15%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 1        | 1      | 1.15%   |
| WDC WD5000AAKX-08U6AA0 500GB      | 1        | 1      | 1.15%   |
| WDC WD5000AAKX-08ERMA0 500GB      | 1        | 2      | 1.15%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 1.15%   |
| WDC WD5000AAKS-00UU3A0 500GB      | 1        | 1      | 1.15%   |
| WDC WD5000AACS-00ZUB0 500GB       | 1        | 1      | 1.15%   |
| WDC WD3200BEKT-22F3T0 320GB       | 1        | 1      | 1.15%   |
| WDC WD3200BEKT-08PVMT1 320GB      | 1        | 1      | 1.15%   |
| WDC WD2003FYPS-27Y2B0 2TB         | 1        | 1      | 1.15%   |
| WDC WD10EZEX-60ZF5A0 1TB          | 1        | 1      | 1.15%   |
| WDC WD10EZEX-22RKKA0 1TB          | 1        | 1      | 1.15%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 1        | 1      | 1.15%   |
| Toshiba MK3275GSX 320GB           | 1        | 1      | 1.15%   |
| Seagate ST500DM005 HD502HJ 500GB  | 1        | 1      | 1.15%   |
| Seagate ST3500630AS 500GB         | 1        | 1      | 1.15%   |
| Seagate ST3500418AS 500GB         | 1        | 1      | 1.15%   |
| Seagate ST3500413AS 500GB         | 1        | 1      | 1.15%   |
| Seagate ST340014AS 40GB           | 1        | 1      | 1.15%   |
| Seagate ST3320418AS 320GB         | 1        | 2      | 1.15%   |
| Seagate ST3250318AS 250GB         | 1        | 1      | 1.15%   |
| Seagate ST3250310AS 250GB         | 1        | 1      | 1.15%   |
| Seagate ST3160815AS 160GB         | 1        | 1      | 1.15%   |
| Seagate ST3160215ACE 160GB        | 1        | 1      | 1.15%   |
| Seagate ST3160212SCE 160GB        | 1        | 1      | 1.15%   |
| Seagate ST31000528AS 1TB          | 1        | 1      | 1.15%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 24       | 27     | 30.38%  |
| WDC                 | 19       | 28     | 24.05%  |
| Hitachi             | 18       | 18     | 22.78%  |
| Samsung Electronics | 6        | 7      | 7.59%   |
| Toshiba             | 4        | 6      | 5.06%   |
| Maxtor              | 3        | 3      | 3.8%    |
| Kingston            | 1        | 1      | 1.27%   |
| JMicron Technology  | 1        | 1      | 1.27%   |
| IBM/Hitachi         | 1        | 2      | 1.27%   |
| HGST                | 1        | 1      | 1.27%   |
| ExcelStor           | 1        | 1      | 1.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 24       | 27     | 30.77%  |
| WDC                 | 19       | 28     | 24.36%  |
| Hitachi             | 18       | 18     | 23.08%  |
| Samsung Electronics | 6        | 7      | 7.69%   |
| Toshiba             | 4        | 6      | 5.13%   |
| Maxtor              | 3        | 3      | 3.85%   |
| JMicron Technology  | 1        | 1      | 1.28%   |
| IBM/Hitachi         | 1        | 2      | 1.28%   |
| HGST                | 1        | 1      | 1.28%   |
| ExcelStor           | 1        | 1      | 1.28%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 62       | 94     | 98.41%  |
| SSD  | 1        | 1      | 1.59%   |

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
| Detected | 101      | 190    | 45.09%  |
| Malfunc  | 63       | 95     | 28.13%  |
| Works    | 56       | 79     | 25%     |
| Failed   | 4        | 4      | 1.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 156      | 70.27%  |
| AMD                         | 20       | 9.01%   |
| Nvidia                      | 19       | 8.56%   |
| Marvell Technology Group    | 6        | 2.7%    |
| JMicron Technology          | 6        | 2.7%    |
| VIA Technologies            | 3        | 1.35%   |
| ASMedia Technology          | 3        | 1.35%   |
| SanDisk                     | 2        | 0.9%    |
| Samsung Electronics         | 2        | 0.9%    |
| SK hynix                    | 1        | 0.45%   |
| Phison Electronics          | 1        | 0.45%   |
| Kingston Technology Company | 1        | 0.45%   |
| Jiangsu Huacun Elec.        | 1        | 0.45%   |
| Adaptec                     | 1        | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 49       | 14.58%  |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 39       | 11.61%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 27       | 8.04%   |
| Nvidia MCP61 SATA Controller                                                            | 18       | 5.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 18       | 5.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 18       | 5.36%   |
| Nvidia MCP61 IDE                                                                        | 16       | 4.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10       | 2.98%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 7        | 2.08%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 7        | 2.08%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 7        | 2.08%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 1.79%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 1.49%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 5        | 1.49%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 1.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 1.49%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 1.19%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3        | 0.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 0.89%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3        | 0.89%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3        | 0.89%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.89%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 0.89%   |
| VIA Serial ATA Controller                                                               | 2        | 0.6%    |
| JMicron JMB368 IDE controller                                                           | 2        | 0.6%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.6%    |
| JMicron JMB362 SATA Controller                                                          | 2        | 0.6%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.6%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 0.6%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.6%    |
| Intel 82801EB (ICH5) SATA Controller                                                    | 2        | 0.6%    |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 0.6%    |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 0.6%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 0.6%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 0.6%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 2        | 0.6%    |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 0.6%    |
| AMD FCH SATA Controller D                                                               | 2        | 0.6%    |
| AMD FCH IDE Controller                                                                  | 2        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 122      | 54.46%  |
| SATA | 86       | 38.39%  |
| NVMe | 8        | 3.57%   |
| RAID | 6        | 2.68%   |
| SAS  | 1        | 0.45%   |
| SCSI | 1        | 0.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 159      | 80.3%   |
| AMD    | 39       | 19.7%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 9        | 4.55%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 7        | 3.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 7        | 3.54%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 6        | 3.03%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 4        | 2.02%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 4        | 2.02%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 4        | 2.02%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 4        | 2.02%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 3        | 1.52%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 3        | 1.52%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 3        | 1.52%   |
| Intel Pentium 4 CPU 3.00GHz                 | 3        | 1.52%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 3        | 1.52%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 1.52%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.52%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 1.52%   |
| AMD Sempron 145 Processor                   | 3        | 1.52%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 1.01%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz      | 2        | 1.01%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 2        | 1.01%   |
| Intel Pentium CPU G640 @ 2.80GHz            | 2        | 1.01%   |
| Intel Pentium CPU G2010 @ 2.80GHz           | 2        | 1.01%   |
| Intel Pentium 4 CPU 3.20GHz                 | 2        | 1.01%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.01%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.01%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.01%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.01%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2        | 1.01%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 1.01%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2        | 1.01%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2        | 1.01%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2        | 1.01%   |
| Intel Core 2 CPU 4400 @ 2.00GHz             | 2        | 1.01%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2        | 1.01%   |
| AMD Sempron 140 Processor                   | 2        | 1.01%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.01%   |
| AMD FX-6300 Six-Core Processor              | 2        | 1.01%   |
| AMD FX-6100 Six-Core Processor              | 2        | 1.01%   |
| AMD Athlon II X2 250 Processor              | 2        | 1.01%   |
| Intel Xeon CPU X3220 @ 2.40GHz              | 1        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 35       | 17.68%  |
| Intel Pentium Dual-Core | 31       | 15.66%  |
| Intel Pentium           | 16       | 8.08%   |
| Intel Core i7           | 14       | 7.07%   |
| Intel Core 2 Duo        | 12       | 6.06%   |
| Intel Core i3           | 11       | 5.56%   |
| Intel Pentium Dual      | 8        | 4.04%   |
| AMD Sempron             | 7        | 3.54%   |
| Intel Pentium 4         | 6        | 3.03%   |
| Intel Core 2 Quad       | 6        | 3.03%   |
| Other                   | 5        | 2.53%   |
| Intel Core 2            | 5        | 2.53%   |
| Intel Xeon              | 4        | 2.02%   |
| AMD Ryzen 5             | 4        | 2.02%   |
| AMD FX                  | 4        | 2.02%   |
| AMD Athlon II X2        | 4        | 2.02%   |
| Intel Celeron           | 3        | 1.52%   |
| AMD Phenom II X4        | 3        | 1.52%   |
| AMD Athlon 64 X2        | 3        | 1.52%   |
| Intel Pentium D         | 2        | 1.01%   |
| AMD Phenom              | 2        | 1.01%   |
| AMD Athlon II X4        | 2        | 1.01%   |
| AMD Athlon              | 2        | 1.01%   |
| Intel Atom              | 1        | 0.51%   |
| AMD Ryzen 3             | 1        | 0.51%   |
| AMD Phenom II X6        | 1        | 0.51%   |
| AMD Phenom II X2        | 1        | 0.51%   |
| AMD E1                  | 1        | 0.51%   |
| AMD Athlon II           | 1        | 0.51%   |
| AMD A8                  | 1        | 0.51%   |
| AMD A6                  | 1        | 0.51%   |
| AMD A4                  | 1        | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 100      | 50.51%  |
| 4       | 66       | 33.33%  |
| 1       | 15       | 7.58%   |
| 6       | 9        | 4.55%   |
| 3       | 5        | 2.53%   |
| Unknown | 2        | 1.01%   |
| 8       | 1        | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 198      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 149      | 75.25%  |
| 2       | 47       | 23.74%  |
| Unknown | 2        | 1.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 193      | 97.47%  |
| 64-bit         | 2        | 1.01%   |
| 32-bit         | 2        | 1.01%   |
| Unknown        | 1        | 0.51%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 57       | 28.08%  |
| 0x1067a    | 31       | 15.27%  |
| 0x206a7    | 21       | 10.34%  |
| 0x306a9    | 12       | 5.91%   |
| 0x306c3    | 8        | 3.94%   |
| 0x6fd      | 6        | 2.96%   |
| 0x6fb      | 5        | 2.46%   |
| 0x010000c8 | 5        | 2.46%   |
| 0xf65      | 4        | 1.97%   |
| 0xa0671    | 3        | 1.48%   |
| 0x6f2      | 3        | 1.48%   |
| 0x10676    | 3        | 1.48%   |
| 0x010000c7 | 3        | 1.48%   |
| 0x010000b6 | 3        | 1.48%   |
| 0x506e3    | 2        | 0.99%   |
| 0x206d7    | 2        | 0.99%   |
| 0x106a5    | 2        | 0.99%   |
| 0x06000852 | 2        | 0.99%   |
| 0x0600063e | 2        | 0.99%   |
| 0x03000027 | 2        | 0.99%   |
| 0x010000db | 2        | 0.99%   |
| 0xf47      | 1        | 0.49%   |
| 0xf43      | 1        | 0.49%   |
| 0xf41      | 1        | 0.49%   |
| 0xf12      | 1        | 0.49%   |
| 0x906eb    | 1        | 0.49%   |
| 0x906e9    | 1        | 0.49%   |
| 0x806c1    | 1        | 0.49%   |
| 0x6f6      | 1        | 0.49%   |
| 0x20652    | 1        | 0.49%   |
| 0x106e5    | 1        | 0.49%   |
| 0x106ca    | 1        | 0.49%   |
| 0x10661    | 1        | 0.49%   |
| 0x0a50000d | 1        | 0.49%   |
| 0x0a50000c | 1        | 0.49%   |
| 0x08701030 | 1        | 0.49%   |
| 0x0810100b | 1        | 0.49%   |
| 0x0800820d | 1        | 0.49%   |
| 0x0700010b | 1        | 0.49%   |
| 0x06001119 | 1        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 45       | 22.73%  |
| SandyBridge | 30       | 15.15%  |
| IvyBridge   | 25       | 12.63%  |
| Core        | 21       | 10.61%  |
| K10         | 19       | 9.6%    |
| Haswell     | 13       | 6.57%   |
| NetBurst    | 8        | 4.04%   |
| K8 Hammer   | 5        | 2.53%   |
| Piledriver  | 3        | 1.52%   |
| Nehalem     | 3        | 1.52%   |
| Zen+        | 2        | 1.01%   |
| Zen 3       | 2        | 1.01%   |
| Westmere    | 2        | 1.01%   |
| Skylake     | 2        | 1.01%   |
| KabyLake    | 2        | 1.01%   |
| K10 Llano   | 2        | 1.01%   |
| Icelake     | 2        | 1.01%   |
| Bulldozer   | 2        | 1.01%   |
| Unknown     | 2        | 1.01%   |
| Zen 2       | 1        | 0.51%   |
| Zen         | 1        | 0.51%   |
| TigerLake   | 1        | 0.51%   |
| Silvermont  | 1        | 0.51%   |
| Jaguar      | 1        | 0.51%   |
| CometLake   | 1        | 0.51%   |
| Bonnell     | 1        | 0.51%   |
| Bobcat      | 1        | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 114      | 54.29%  |
| Nvidia           | 51       | 24.29%  |
| AMD              | 42       | 20%     |
| VIA Technologies | 3        | 1.43%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 24       | 11.21%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 24       | 11.21%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 5.14%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 11       | 5.14%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 11       | 5.14%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 7        | 3.27%   |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 2.34%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 5        | 2.34%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 1.87%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 1.87%   |
| Nvidia GF119 [GeForce GT 520]                                               | 4        | 1.87%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 1.87%   |
| Intel 82946GZ/GL Integrated Graphics Controller                             | 4        | 1.87%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 4        | 1.87%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 1.87%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 3        | 1.4%    |
| Nvidia GF106 [GeForce GTS 450]                                              | 3        | 1.4%    |
| Nvidia G86 [GeForce 8500 GT]                                                | 3        | 1.4%    |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 3        | 1.4%    |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 3        | 1.4%    |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 3        | 1.4%    |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 0.93%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 2        | 0.93%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 2        | 0.93%   |
| Intel 82865G Integrated Graphics Controller                                 | 2        | 0.93%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 0.93%   |
| AMD RV670 [Radeon HD 3870]                                                  | 2        | 0.93%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 0.93%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 0.93%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 0.93%   |
| Nvidia NV44 [GeForce 7100 GS]                                               | 1        | 0.47%   |
| Nvidia NV44 [GeForce 6200 TurboCache]                                       | 1        | 0.47%   |
| Nvidia NV44 [GeForce 6200 LE]                                               | 1        | 0.47%   |
| Nvidia GT218 [GeForce 405]                                                  | 1        | 0.47%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.47%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 0.47%   |
| Nvidia GK104GL [Quadro K4200]                                               | 1        | 0.47%   |
| Nvidia GF119 [GeForce 605]                                                  | 1        | 0.47%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 0.47%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                       | 1        | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 106      | 53%     |
| 1 x Nvidia     | 49       | 24.5%   |
| 1 x AMD        | 35       | 17.5%   |
| 2 x AMD        | 3        | 1.5%    |
| 1 x VIA        | 3        | 1.5%    |
| AMD + Nvidia   | 2        | 1%      |
| Intel + Nvidia | 1        | 0.5%    |
| Intel + AMD    | 1        | 0.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 168      | 84%     |
| Proprietary | 19       | 9.5%    |
| Unknown     | 13       | 6.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 117      | 57.35%  |
| 0.51-1.0   | 34       | 16.67%  |
| 0.01-0.5   | 28       | 13.73%  |
| 1.01-2.0   | 19       | 9.31%   |
| 3.01-4.0   | 5        | 2.45%   |
| 7.01-8.0   | 1        | 0.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung Electronics                   | 41       | 23.7%   |
| Goldstar                              | 20       | 11.56%  |
| Hewlett-Packard                       | 17       | 9.83%   |
| Toshiba                               | 14       | 8.09%   |
| Acer                                  | 12       | 6.94%   |
| AOC                                   | 11       | 6.36%   |
| Lenovo                                | 10       | 5.78%   |
| Dell                                  | 10       | 5.78%   |
| Vita                                  | 4        | 2.31%   |
| BenQ                                  | 4        | 2.31%   |
| LG Electronics                        | 3        | 1.73%   |
| Unknown (XXX)                         | 2        | 1.16%   |
| Sony                                  | 2        | 1.16%   |
| NEC Computers                         | 2        | 1.16%   |
| Envision                              | 2        | 1.16%   |
| ViewSonic                             | 1        | 0.58%   |
| Toshiba Matsushita Display Technology | 1        | 0.58%   |
| TCL                                   | 1        | 0.58%   |
| PXO                                   | 1        | 0.58%   |
| Plain Tree Systems                    | 1        | 0.58%   |
| PEGA                                  | 1        | 0.58%   |
| Parker                                | 1        | 0.58%   |
| MStar                                 | 1        | 0.58%   |
| MSI                                   | 1        | 0.58%   |
| LSC                                   | 1        | 0.58%   |
| KTC                                   | 1        | 0.58%   |
| IBM                                   | 1        | 0.58%   |
| HKC                                   | 1        | 0.58%   |
| Haier                                 | 1        | 0.58%   |
| eMachines                             | 1        | 0.58%   |
| CVT                                   | 1        | 0.58%   |
| Changhong Electric                    | 1        | 0.58%   |
| AOpen                                 | 1        | 0.58%   |
| Ancor Communications                  | 1        | 0.58%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch             | 11       | 6.11%   |
| Lenovo LEN L174 LEN240B 1280x1024 340x270mm 17.1-inch                | 5        | 2.78%   |
| Vita V195EW-W VIT1950 1600x900 432x240mm 19.5-inch                   | 4        | 2.22%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 4        | 2.22%   |
| Toshiba TV TSB0206 1920x1080                                         | 3        | 1.67%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch          | 3        | 1.67%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                  | 3        | 1.67%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch | 2        | 1.11%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 2        | 1.11%   |
| Samsung Electronics S19A10N SAM083E 1366x768 410x230mm 18.5-inch     | 2        | 1.11%   |
| Lenovo LEN L151 LEN23CD 1024x768 304x228mm 15.0-inch                 | 2        | 1.11%   |
| Lenovo L197 Wide LEN1152 1440x900 410x257mm 19.1-inch                | 2        | 1.11%   |
| Hewlett-Packard S1933 HWP2933 1366x768 413x234mm 18.7-inch           | 2        | 1.11%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 2        | 1.11%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                 | 2        | 1.11%   |
| Acer V246HQL ACR0424 1920x1080 521x293mm 23.5-inch                   | 2        | 1.11%   |
| Acer B193W ACR001E 1440x900 408x255mm 18.9-inch                      | 2        | 1.11%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch        | 1        | 0.56%   |
| Unknown (XXX) L9W XXX076E 1440x900 410x256mm 19.0-inch               | 1        | 0.56%   |
| Unknown (XXX) 1772ED XXX1772 1280x1024 320x250mm 16.0-inch           | 1        | 0.56%   |
| Unknown (XXX) 1772E XXX1772 1280x1024 320x250mm 16.0-inch            | 1        | 0.56%   |
| Toshiba Matsushita Display Technology LCD Monitor LCD-MONITOR        | 1        | 0.56%   |
| TCL T-7005L TCL1770 1280x1024 338x270mm 17.0-inch                    | 1        | 0.56%   |
| Sony TV SNYEB01 1360x768                                             | 1        | 0.56%   |
| Sony TV SNYEA01 1920x1080                                            | 1        | 0.56%   |
| Sony TV SNYDC01 1360x768                                             | 1        | 0.56%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch    | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM05D5 1360x768                      | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch  | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch  | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM055E 1920x1080 510x290mm 23.1-inch | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM049C 1920x1080 477x268mm 21.5-inch | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM0499 1600x900 443x249mm 20.0-inch  | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch  | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM03F5 1920x1200                     | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM03F4 1920x1200 518x324mm 24.1-inch | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 344x194mm 15.5-inch  | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch  | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch  | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch  | 1        | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 37       | 21.14%  |
| 1366x768 (WXGA)    | 34       | 19.43%  |
| 1280x1024 (SXGA)   | 31       | 17.71%  |
| 1440x900 (WXGA+)   | 25       | 14.29%  |
| 1600x900 (HD+)     | 13       | 7.43%   |
| 1360x768           | 9        | 5.14%   |
| 1024x768 (XGA)     | 8        | 4.57%   |
| 1680x1050 (WSXGA+) | 6        | 3.43%   |
| 1280x720 (HD)      | 3        | 1.71%   |
| 3840x2160 (4K)     | 2        | 1.14%   |
| 2560x1440 (QHD)    | 2        | 1.14%   |
| 1920x1200 (WUXGA)  | 2        | 1.14%   |
| Unknown            | 2        | 1.14%   |
| 3840x1080          | 1        | 0.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 45       | 25.71%  |
| 17      | 25       | 14.29%  |
| 19      | 22       | 12.57%  |
| 21      | 16       | 9.14%   |
| Unknown | 13       | 7.43%   |
| 23      | 11       | 6.29%   |
| 15      | 11       | 6.29%   |
| 20      | 8        | 4.57%   |
| 22      | 4        | 2.29%   |
| 74      | 3        | 1.71%   |
| 16      | 3        | 1.71%   |
| 72      | 2        | 1.14%   |
| 32      | 2        | 1.14%   |
| 27      | 2        | 1.14%   |
| 24      | 2        | 1.14%   |
| 13      | 2        | 1.14%   |
| 52      | 1        | 0.57%   |
| 42      | 1        | 0.57%   |
| 39      | 1        | 0.57%   |
| 31      | 1        | 0.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 89       | 51.45%  |
| 301-350     | 34       | 19.65%  |
| 501-600     | 15       | 8.67%   |
| Unknown     | 13       | 7.51%   |
| 351-400     | 9        | 5.2%    |
| 1501-2000   | 5        | 2.89%   |
| 701-800     | 2        | 1.16%   |
| 201-300     | 2        | 1.16%   |
| 801-900     | 1        | 0.58%   |
| 601-700     | 1        | 0.58%   |
| 1001-1500   | 1        | 0.58%   |
| 901-1000    | 1        | 0.58%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 86       | 50.59%  |
| 16/10   | 36       | 21.18%  |
| 5/4     | 29       | 17.06%  |
| Unknown | 10       | 5.88%   |
| 4/3     | 8        | 4.71%   |
| 3/2     | 1        | 0.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 141-150        | 55       | 31.61%  |
| 151-200        | 47       | 27.01%  |
| 201-250        | 27       | 15.52%  |
| Unknown        | 13       | 7.47%   |
| 101-110        | 11       | 6.32%   |
| More than 1000 | 6        | 3.45%   |
| 351-500        | 3        | 1.72%   |
| 121-130        | 3        | 1.72%   |
| 301-350        | 2        | 1.15%   |
| 131-140        | 2        | 1.15%   |
| 501-1000       | 2        | 1.15%   |
| 81-90          | 1        | 0.57%   |
| 251-300        | 1        | 0.57%   |
| 91-100         | 1        | 0.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 128      | 74.85%  |
| 101-120 | 22       | 12.87%  |
| Unknown | 13       | 7.6%    |
| 1-50    | 7        | 4.09%   |
| 121-160 | 1        | 0.58%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 169      | 85.35%  |
| 0     | 17       | 8.59%   |
| 2     | 10       | 5.05%   |
| 3     | 2        | 1.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 119      | 39.27%  |
| Intel                             | 46       | 15.18%  |
| Qualcomm Atheros                  | 44       | 14.52%  |
| Ralink                            | 19       | 6.27%   |
| Nvidia                            | 19       | 6.27%   |
| Ralink Technology                 | 11       | 3.63%   |
| Broadcom                          | 10       | 3.3%    |
| Xiaomi                            | 5        | 1.65%   |
| Qualcomm Atheros Communications   | 4        | 1.32%   |
| VIA Technologies                  | 3        | 0.99%   |
| TP-Link                           | 3        | 0.99%   |
| Marvell Technology Group          | 3        | 0.99%   |
| Sundance Technology Inc / IC Plus | 2        | 0.66%   |
| Mercucys                          | 2        | 0.66%   |
| D-Link System                     | 2        | 0.66%   |
| Broadcom Limited                  | 2        | 0.66%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.33%   |
| Trendchip Technologies            | 1        | 0.33%   |
| Samsung Electronics               | 1        | 0.33%   |
| National Semiconductor            | 1        | 0.33%   |
| Motorola PCS                      | 1        | 0.33%   |
| Motorola BCS                      | 1        | 0.33%   |
| JMicron Technology                | 1        | 0.33%   |
| ICS Advent                        | 1        | 0.33%   |
| Davicom Semiconductor             | 1        | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 81       | 25.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 20       | 6.19%   |
| Nvidia MCP61 Ethernet                                                          | 18       | 5.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 14       | 4.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 10       | 3.1%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 9        | 2.79%   |
| Intel Ethernet Connection I217-LM                                              | 8        | 2.48%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 7        | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 6        | 1.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 5        | 1.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 5        | 1.55%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 5        | 1.55%   |
| Ralink MT7601U Wireless Adapter                                                | 5        | 1.55%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 5        | 1.55%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 4        | 1.24%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 4        | 1.24%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                          | 4        | 1.24%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3        | 0.93%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 3        | 0.93%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 3        | 0.93%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 3        | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 3        | 0.93%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 3        | 0.93%   |
| Qualcomm Atheros AR9271 802.11n                                                | 3        | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3        | 0.93%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3        | 0.93%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 2        | 0.62%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 2        | 0.62%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 2        | 0.62%   |
| Realtek 802.11ac NIC                                                           | 2        | 0.62%   |
| Ralink RT2561/RT61 802.11g PCI                                                 | 2        | 0.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2        | 0.62%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                               | 2        | 0.62%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                               | 2        | 0.62%   |
| Mercucys MW300UM RTL8192EU wifi                                                | 2        | 0.62%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 2        | 0.62%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 2        | 0.62%   |
| Intel PRO/100 VE Network Connection                                            | 2        | 0.62%   |
| Intel Ethernet Connection I217-V                                               | 2        | 0.62%   |
| Intel 82579V Gigabit Network Connection                                        | 2        | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros                | 30       | 28.3%   |
| Realtek Semiconductor           | 23       | 21.7%   |
| Ralink                          | 19       | 17.92%  |
| Ralink Technology               | 11       | 10.38%  |
| Intel                           | 7        | 6.6%    |
| Qualcomm Atheros Communications | 4        | 3.77%   |
| TP-Link                         | 3        | 2.83%   |
| Broadcom                        | 3        | 2.83%   |
| Mercucys                        | 2        | 1.89%   |
| D-Link System                   | 2        | 1.89%   |
| Xiaomi                          | 1        | 0.94%   |
| Broadcom Limited                | 1        | 0.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 9        | 8.49%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 7        | 6.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 6        | 5.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 5        | 4.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 5        | 4.72%   |
| Ralink MT7601U Wireless Adapter                                                | 5        | 4.72%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 5        | 4.72%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 4        | 3.77%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 4        | 3.77%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 3        | 2.83%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 3        | 2.83%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 3        | 2.83%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 3        | 2.83%   |
| Qualcomm Atheros AR9271 802.11n                                                | 3        | 2.83%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3        | 2.83%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 2        | 1.89%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 2        | 1.89%   |
| Realtek 802.11ac NIC                                                           | 2        | 1.89%   |
| Ralink RT2561/RT61 802.11g PCI                                                 | 2        | 1.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2        | 1.89%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                               | 2        | 1.89%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                               | 2        | 1.89%   |
| Mercucys MW300UM RTL8192EU wifi                                                | 2        | 1.89%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 2        | 1.89%   |
| Broadcom BCM43225 802.11b/g/n                                                  | 2        | 1.89%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                              | 1        | 0.94%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                    | 1        | 0.94%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                      | 1        | 0.94%   |
| Ralink RT5372 Wireless Adapter                                                 | 1        | 0.94%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                         | 1        | 0.94%   |
| Ralink RT2800 802.11n PCI                                                      | 1        | 0.94%   |
| Qualcomm Atheros AR5523                                                        | 1        | 0.94%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 1        | 0.94%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]            | 1        | 0.94%   |
| Intel Wireless 7265                                                            | 1        | 0.94%   |
| Intel Wireless 7260                                                            | 1        | 0.94%   |
| Intel Wi-Fi 6 AX200                                                            | 1        | 0.94%   |
| Intel Centrino Wireless-N 105                                                  | 1        | 0.94%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 1        | 0.94%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]           | 1        | 0.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 107      | 50.23%  |
| Intel                             | 41       | 19.25%  |
| Nvidia                            | 19       | 8.92%   |
| Qualcomm Atheros                  | 18       | 8.45%   |
| Broadcom                          | 7        | 3.29%   |
| Xiaomi                            | 4        | 1.88%   |
| VIA Technologies                  | 3        | 1.41%   |
| Marvell Technology Group          | 3        | 1.41%   |
| Sundance Technology Inc / IC Plus | 2        | 0.94%   |
| Trendchip Technologies            | 1        | 0.47%   |
| Samsung Electronics               | 1        | 0.47%   |
| National Semiconductor            | 1        | 0.47%   |
| Motorola PCS                      | 1        | 0.47%   |
| Motorola BCS                      | 1        | 0.47%   |
| JMicron Technology                | 1        | 0.47%   |
| ICS Advent                        | 1        | 0.47%   |
| Davicom Semiconductor             | 1        | 0.47%   |
| Broadcom Limited                  | 1        | 0.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 81       | 37.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 20       | 9.26%   |
| Nvidia MCP61 Ethernet                                                      | 18       | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 14       | 6.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 10       | 4.63%   |
| Intel Ethernet Connection I217-LM                                          | 8        | 3.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 5        | 2.31%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                      | 4        | 1.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 3        | 1.39%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 3        | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 3        | 1.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 2        | 0.93%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2        | 0.93%   |
| Intel PRO/100 VE Network Connection                                        | 2        | 0.93%   |
| Intel Ethernet Connection I217-V                                           | 2        | 0.93%   |
| Intel 82579V Gigabit Network Connection                                    | 2        | 0.93%   |
| Intel 82567V-2 Gigabit Network Connection                                  | 2        | 0.93%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 2        | 0.93%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1        | 0.46%   |
| Trendchip Ethernet controller                                              | 1        | 0.46%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1        | 0.46%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.46%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.46%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 0.46%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 1        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 1        | 0.46%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 1        | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1        | 0.46%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.46%   |
| Nvidia MCP77 Ethernet                                                      | 1        | 0.46%   |
| National DP83815 (MacPhyter) Ethernet Controller                           | 1        | 0.46%   |
| Motorola PCS moto g52                                                      | 1        | 0.46%   |
| Motorola BCS SurfBoard SB5100 Cable Modem                                  | 1        | 0.46%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                    | 1        | 0.46%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                     | 1        | 0.46%   |
| Intel NM10/ICH7 Family LAN Controller                                      | 1        | 0.46%   |
| Intel Ethernet Controller I225-V                                           | 1        | 0.46%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                         | 1        | 0.46%   |
| Intel 82578DC Gigabit Network Connection                                   | 1        | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 194      | 65.54%  |
| WiFi     | 101      | 34.12%  |
| Modem    | 1        | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 142      | 68.93%  |
| WiFi     | 64       | 31.07%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 128      | 63.68%  |
| 2     | 68       | 33.83%  |
| 3     | 3        | 1.49%   |
| 33    | 1        | 0.5%    |
| 0     | 1        | 0.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 198      | 99.5%   |
| Yes  | 1        | 0.5%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 11       | 47.83%  |
| Intel                   | 5        | 21.74%  |
| Broadcom                | 3        | 13.04%  |
| IMC Networks            | 2        | 8.7%    |
| ASUSTek Computer        | 2        | 8.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11       | 47.83%  |
| Intel AX201 Bluetooth                               | 3        | 13.04%  |
| IMC Networks Bluetooth Module                       | 2        | 8.7%    |
| Intel Bluetooth wireless interface                  | 1        | 4.35%   |
| Intel AX200 Bluetooth                               | 1        | 4.35%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 UHE Dongle | 1        | 4.35%   |
| Broadcom BCM2070 Bluetooth Device                   | 1        | 4.35%   |
| Broadcom BCM2035B3 Bluetooth Adapter                | 1        | 4.35%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 4.35%   |
| ASUS Bluetooth Adapter                              | 1        | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 152      | 54.87%  |
| Nvidia                 | 46       | 16.61%  |
| AMD                    | 46       | 16.61%  |
| C-Media Electronics    | 8        | 2.89%   |
| VIA Technologies       | 5        | 1.81%   |
| Creative Labs          | 5        | 1.81%   |
| JMTek                  | 3        | 1.08%   |
| Generalplus Technology | 3        | 1.08%   |
| Logitech               | 2        | 0.72%   |
| Unknown                | 1        | 0.36%   |
| Microsoft              | 1        | 0.36%   |
| Megawin Technology     | 1        | 0.36%   |
| M-Audio                | 1        | 0.36%   |
| Giga-Byte Technology   | 1        | 0.36%   |
| Corsair                | 1        | 0.36%   |
| Aureal Semiconductor   | 1        | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 49       | 16.12%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 45       | 14.8%   |
| Nvidia MCP61 High Definition Audio                                                | 16       | 5.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 12       | 3.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 11       | 3.62%   |
| Nvidia GF119 HDMI Audio Controller                                                | 9        | 2.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 8        | 2.63%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 8        | 2.63%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 8        | 2.63%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 7        | 2.3%    |
| Nvidia High Definition Audio Controller                                           | 6        | 1.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 6        | 1.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 6        | 1.97%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 5        | 1.64%   |
| AMD FCH Azalia Controller                                                         | 5        | 1.64%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 4        | 1.32%   |
| AMD Family 17h/19h HD Audio Controller                                            | 4        | 1.32%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 4        | 1.32%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                    | 3        | 0.99%   |
| Nvidia GF106 High Definition Audio Controller                                     | 3        | 0.99%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3        | 0.99%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 3        | 0.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 0.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 3        | 0.99%   |
| Generalplus Technology USB Audio Device                                           | 3        | 0.99%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 0.99%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller       | 2        | 0.66%   |
| Nvidia GF116 High Definition Audio Controller                                     | 2        | 0.66%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 0.66%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 0.66%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2        | 0.66%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                              | 2        | 0.66%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 2        | 0.66%   |
| C-Media Electronics Cmedia Audio                                                  | 2        | 0.66%   |
| C-Media Electronics CM108 Audio Controller                                        | 2        | 0.66%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2        | 0.66%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 0.66%   |
| AMD RV670/680 HDMI Audio [Radeon HD 3690/3800 Series]                             | 2        | 0.66%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2        | 0.66%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 49       | 30.06%  |
| Kingston                   | 18       | 11.04%  |
| Samsung Electronics        | 16       | 9.82%   |
| SK hynix                   | 14       | 8.59%   |
| Ramaxel Technology         | 14       | 8.59%   |
| Corsair                    | 11       | 6.75%   |
| Crucial                    | 9        | 5.52%   |
| Micron Technology          | 7        | 4.29%   |
| Team                       | 3        | 1.84%   |
| Nanya Technology           | 3        | 1.84%   |
| A-DATA Technology          | 3        | 1.84%   |
| PNY                        | 2        | 1.23%   |
| Kreton                     | 2        | 1.23%   |
| Elpida                     | 2        | 1.23%   |
| Avant                      | 2        | 1.23%   |
| Unknown                    | 2        | 1.23%   |
| Unknown (FFFF000000000000) | 1        | 0.61%   |
| Unknown (7F7F7F7F7F7F7F83) | 1        | 0.61%   |
| Unknown (0x0CBA)           | 1        | 0.61%   |
| Super Talent               | 1        | 0.61%   |
| Qimonda                    | 1        | 0.61%   |
| OCZ                        | 1        | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                      | 6        | 3.28%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 4        | 2.19%   |
| Unknown RAM Module 4GB DIMM 400MT/s                    | 4        | 2.19%   |
| Unknown RAM Module 2GB DIMM DDR2                       | 3        | 1.64%   |
| Unknown RAM Module 2048MB DIMM DDR2                    | 3        | 1.64%   |
| Unknown RAM Module 1024MB DIMM DDR2                    | 3        | 1.64%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s  | 3        | 1.64%   |
| Ramaxel RAM RMR5030ED58E8W1600 2GB DIMM DDR3 1600MT/s  | 3        | 1.64%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 2        | 1.09%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                   | 2        | 1.09%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s              | 2        | 1.09%   |
| Unknown RAM Module 2GB DIMM 400MT/s                    | 2        | 1.09%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 2        | 1.09%   |
| Unknown RAM Module 1024MB DIMM SDRAM                   | 2        | 1.09%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s            | 2        | 1.09%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s              | 2        | 1.09%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR2 2133MT/s | 2        | 1.09%   |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3 1600MT/s    | 2        | 1.09%   |
| Ramaxel RAM RMR5030ME68F9F1600 4GB DIMM DDR3 1600MT/s  | 2        | 1.09%   |
| Ramaxel RAM RMR5030EF68F9W1600 4GB DIMM DDR3 1600MT/s  | 2        | 1.09%   |
| Ramaxel RAM RMR1870EC58E9F1333 4GB DIMM DDR3 1333MT/s  | 2        | 1.09%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s     | 2        | 1.09%   |
| Micron RAM 4ATF51264AZ-3G2R1 4GB DIMM DDR4 3200MT/s    | 2        | 1.09%   |
| Unknown                                                | 2        | 1.09%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                   | 1        | 0.55%   |
| Unknown RAM Module 512MB DIMM DDR2                     | 1        | 0.55%   |
| Unknown RAM Module 4GB DIMM 667MT/s                    | 1        | 0.55%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 1        | 0.55%   |
| Unknown RAM Module 4096MB DIMM SDRAM                   | 1        | 0.55%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s           | 1        | 0.55%   |
| Unknown RAM Module 4096MB DIMM                         | 1        | 0.55%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 1        | 0.55%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s               | 1        | 0.55%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                | 1        | 0.55%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 1        | 0.55%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s           | 1        | 0.55%   |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s           | 1        | 0.55%   |
| Unknown RAM Module 2048MB DIMM DDR2 533MT/s            | 1        | 0.55%   |
| Unknown RAM Module 2048MB DIMM DDR2 1639MT/s           | 1        | 0.55%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s             | 1        | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 53       | 41.73%  |
| DDR2    | 25       | 19.69%  |
| SDRAM   | 19       | 14.96%  |
| Unknown | 14       | 11.02%  |
| DDR4    | 11       | 8.66%   |
| DDR     | 5        | 3.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 118      | 95.93%  |
| SODIMM | 5        | 4.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 56       | 37.58%  |
| 4096  | 50       | 33.56%  |
| 8192  | 20       | 13.42%  |
| 1024  | 17       | 11.41%  |
| 32768 | 2        | 1.34%   |
| 16384 | 2        | 1.34%   |
| 512   | 2        | 1.34%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 31       | 21.23%  |
| 1333    | 26       | 17.81%  |
| Unknown | 22       | 15.07%  |
| 800     | 9        | 6.16%   |
| 667     | 8        | 5.48%   |
| 400     | 6        | 4.11%   |
| 1066    | 5        | 3.42%   |
| 533     | 4        | 2.74%   |
| 3733    | 3        | 2.05%   |
| 3200    | 3        | 2.05%   |
| 2133    | 3        | 2.05%   |
| 1639    | 3        | 2.05%   |
| 133     | 3        | 2.05%   |
| 3600    | 2        | 1.37%   |
| 2667    | 2        | 1.37%   |
| 2048    | 2        | 1.37%   |
| 1867    | 2        | 1.37%   |
| 1800    | 2        | 1.37%   |
| 1067    | 2        | 1.37%   |
| 3800    | 1        | 0.68%   |
| 2933    | 1        | 0.68%   |
| 2400    | 1        | 0.68%   |
| 2000    | 1        | 0.68%   |
| 1648    | 1        | 0.68%   |
| 1334    | 1        | 0.68%   |
| 1024    | 1        | 0.68%   |
| 266     | 1        | 0.68%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 4        | 50%     |
| Seiko Epson         | 3        | 37.5%   |
| Samsung Electronics | 1        | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 12.5%   |
| Seiko Epson L6160 Series                     | 1        | 12.5%   |
| Seiko Epson L210 Series                      | 1        | 12.5%   |
| Samsung ML-216x Series Laser Printer         | 1        | 12.5%   |
| HP LaserJet P1006                            | 1        | 12.5%   |
| HP LaserJet P1005                            | 1        | 12.5%   |
| HP DeskJet F4100 Printer series              | 1        | 12.5%   |
| HP Color LaserJet CP1215                     | 1        | 12.5%   |

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
| Logitech                    | 5        | 19.23%  |
| Microsoft                   | 4        | 15.38%  |
| Samsung Electronics         | 3        | 11.54%  |
| IMC Networks                | 2        | 7.69%   |
| Cubeternet                  | 2        | 7.69%   |
| Z-Star Microelectronics     | 1        | 3.85%   |
| Suyin                       | 1        | 3.85%   |
| SiGma Micro                 | 1        | 3.85%   |
| Realtek Semiconductor       | 1        | 3.85%   |
| LG Electronics              | 1        | 3.85%   |
| KYE Systems (Mouse Systems) | 1        | 3.85%   |
| KYE Systems                 | 1        | 3.85%   |
| Chicony Electronics         | 1        | 3.85%   |
| Aveo Technology             | 1        | 3.85%   |
| 04004000_P040200_SN0002     | 1        | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode)               | 3        | 11.54%  |
| Logitech Webcam C270                                  | 3        | 11.54%  |
| Cubeternet USB2.0 Camera                              | 2        | 7.69%   |
| Z-Star Venus USB2.0 Camera                            | 1        | 3.85%   |
| Suyin HP Webcam                                       | 1        | 3.85%   |
| SiGma Micro WebCam SiGma Micro                        | 1        | 3.85%   |
| Realtek HP 1.0MP High Definition Webcam               | 1        | 3.85%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks   | 1        | 3.85%   |
| Microsoft LifeCam VX-5000                             | 1        | 3.85%   |
| Microsoft LifeCam Studio                              | 1        | 3.85%   |
| Microsoft LifeCam HD-3000                             | 1        | 3.85%   |
| Logitech QuickCam Communicate MP/S5500                | 1        | 3.85%   |
| Logitech C922 Pro Stream Webcam                       | 1        | 3.85%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 3.85%   |
| KYE Systems FaceCam 1320                              | 1        | 3.85%   |
| KYE Systems (Mouse Systems) eFace 2025                | 1        | 3.85%   |
| IMC Networks USB2.0 UVC 1.3M WebCam                   | 1        | 3.85%   |
| IMC Networks USB 2.0 Camera                           | 1        | 3.85%   |
| Chicony HD Webcam                                     | 1        | 3.85%   |
| Aveo USB2.0 Camera                                    | 1        | 3.85%   |
| 04004000_P040200_SN0002 1080P Web Camera              | 1        | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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
| 0     | 159      | 79.9%   |
| 1     | 36       | 18.09%  |
| 2     | 3        | 1.51%   |
| 3     | 1        | 0.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 21       | 47.73%  |
| Communication controller | 10       | 22.73%  |
| Sound                    | 3        | 6.82%   |
| Net/wireless             | 3        | 6.82%   |
| Multimedia controller    | 3        | 6.82%   |
| Video                    | 1        | 2.27%   |
| Storage/ide              | 1        | 2.27%   |
| Firewire controller      | 1        | 2.27%   |
| Camera                   | 1        | 2.27%   |


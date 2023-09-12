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

Total: 247

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Debian 11          | 14       | 7.49%   |
| Ubuntu 20.04       | 13       | 6.95%   |
| Ubuntu 18.04       | 10       | 5.35%   |
| OpenMandriva 4.3   | 10       | 5.35%   |
| OpenMandriva 23.03 | 9        | 4.81%   |
| Ubuntu 22.04       | 7        | 3.74%   |
| OpenMandriva 4.2   | 7        | 3.74%   |
| Zorin 16           | 6        | 3.21%   |
| OpenMandriva 23.08 | 5        | 2.67%   |
| Linux Mint 21.1    | 5        | 2.67%   |
| Linux Mint 20.3    | 5        | 2.67%   |
| Xubuntu 18.04      | 4        | 2.14%   |
| ROSA R11           | 4        | 2.14%   |
| OpenMandriva 23.01 | 4        | 2.14%   |
| Linux Mint 20.1    | 3        | 1.6%    |
| Linux Mint 20      | 3        | 1.6%    |
| Linux Mint 19.3    | 3        | 1.6%    |
| KDE neon 20.04     | 3        | 1.6%    |
| Debian 10          | 3        | 1.6%    |
| ArcoLinux Rolling  | 3        | 1.6%    |
| Arch Rolling       | 3        | 1.6%    |
| Zorin 15           | 2        | 1.07%   |
| Xubuntu 16.04      | 2        | 1.07%   |
| Ubuntu 20.10       | 2        | 1.07%   |
| ROSA R9            | 2        | 1.07%   |
| OpenMandriva 4.50  | 2        | 1.07%   |
| MX 21              | 2        | 1.07%   |
| Kubuntu 20.04      | 2        | 1.07%   |
| Fedora 38          | 2        | 1.07%   |
| Debian 12          | 2        | 1.07%   |
| Xubuntu 20.04      | 1        | 0.53%   |
| Xero Rolling       | 1        | 0.53%   |
| Ubuntu Unity 18.04 | 1        | 0.53%   |
| Ubuntu MATE 19.10  | 1        | 0.53%   |
| Ubuntu 22.10       | 1        | 0.53%   |
| Ubuntu 21.10       | 1        | 0.53%   |
| Ubuntu 19.10       | 1        | 0.53%   |
| Ubuntu 19.04       | 1        | 0.53%   |
| Sparky 5.12        | 1        | 0.53%   |
| Solus 4.3          | 1        | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| OpenMandriva | 36       | 19.67%  |
| Ubuntu       | 35       | 19.13%  |
| Debian       | 23       | 12.57%  |
| Linux Mint   | 22       | 12.02%  |
| ROSA         | 11       | 6.01%   |
| Zorin        | 8        | 4.37%   |
| Xubuntu      | 6        | 3.28%   |
| Fedora       | 5        | 2.73%   |
| KDE neon     | 4        | 2.19%   |
| Arch         | 4        | 2.19%   |
| Kubuntu      | 3        | 1.64%   |
| Elementary   | 3        | 1.64%   |
| ArcoLinux    | 3        | 1.64%   |
| Nobara       | 2        | 1.09%   |
| MX           | 2        | 1.09%   |
| Manjaro      | 2        | 1.09%   |
| Xero         | 1        | 0.55%   |
| Ubuntu Unity | 1        | 0.55%   |
| Ubuntu MATE  | 1        | 0.55%   |
| Sparky       | 1        | 0.55%   |
| Solus        | 1        | 0.55%   |
| Q4OS         | 1        | 0.55%   |
| Pop!_OS      | 1        | 0.55%   |
| PCLinuxOS    | 1        | 0.55%   |
| Lubuntu      | 1        | 0.55%   |
| LMDE         | 1        | 0.55%   |
| Kali         | 1        | 0.55%   |
| Garuda Linux | 1        | 0.55%   |
| Feren OS     | 1        | 0.55%   |
| Endless      | 1        | 0.55%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                           | Desktops | Percent |
|-----------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003           | 10       | 5.03%   |
| 6.2.6-desktop-1omv2390            | 9        | 4.52%   |
| 5.10.14-desktop-1omv4002          | 7        | 3.52%   |
| 6.4.11-desktop-1omv2390           | 4        | 2.01%   |
| 6.1.1-desktop-1omv2290            | 4        | 2.01%   |
| 5.4.0-42-generic                  | 4        | 2.01%   |
| 5.8.0-55-generic                  | 2        | 1.01%   |
| 5.4.0-77-generic                  | 2        | 1.01%   |
| 5.4.0-74-generic                  | 2        | 1.01%   |
| 5.4.0-54-generic                  | 2        | 1.01%   |
| 5.4.0-26-generic                  | 2        | 1.01%   |
| 5.3.0-40-generic                  | 2        | 1.01%   |
| 5.19.0-41-generic                 | 2        | 1.01%   |
| 5.19.0-35-generic                 | 2        | 1.01%   |
| 5.15.0-76-generic                 | 2        | 1.01%   |
| 5.15.0-71-generic                 | 2        | 1.01%   |
| 5.15.0-67-generic                 | 2        | 1.01%   |
| 5.15.0-58-generic                 | 2        | 1.01%   |
| 5.15.0-56-generic                 | 2        | 1.01%   |
| 5.15.0-53-generic                 | 2        | 1.01%   |
| 5.15.0-46-generic                 | 2        | 1.01%   |
| 5.13.0-27-generic                 | 2        | 1.01%   |
| 5.10.0-8-amd64                    | 2        | 1.01%   |
| 5.10.0-16-amd64                   | 2        | 1.01%   |
| 5.10.0-14-amd64                   | 2        | 1.01%   |
| 5.10.0-11-amd64                   | 2        | 1.01%   |
| 4.15.0-desktop-45.1rosa-x86_64    | 2        | 1.01%   |
| 4.15.0-48-generic                 | 2        | 1.01%   |
| 4.15.0-112-generic                | 2        | 1.01%   |
| 6.4.8-desktop-2omv2390            | 1        | 0.5%    |
| 6.4.7-arch1-1                     | 1        | 0.5%    |
| 6.4.6-arch1-1                     | 1        | 0.5%    |
| 6.4.6-200.fc38.x86_64             | 1        | 0.5%    |
| 6.4.3-x64v3-xanmod1               | 1        | 0.5%    |
| 6.4.3-arch1-2                     | 1        | 0.5%    |
| 6.3.8-200.fc38.x86_64             | 1        | 0.5%    |
| 6.2.12-zen1-1-zen                 | 1        | 0.5%    |
| 6.2.12-200.fsync.fc37.x86_64      | 1        | 0.5%    |
| 6.2.0-26-generic                  | 1        | 0.5%    |
| 6.1.20-generic-2rosa2021.1-x86_64 | 1        | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 27       | 14.36%  |
| 4.15.0  | 19       | 10.11%  |
| 5.15.0  | 18       | 9.57%   |
| 5.10.0  | 17       | 9.04%   |
| 5.16.7  | 10       | 5.32%   |
| 6.2.6   | 9        | 4.79%   |
| 5.10.14 | 7        | 3.72%   |
| 5.8.0   | 6        | 3.19%   |
| 5.13.0  | 6        | 3.19%   |
| 5.3.0   | 5        | 2.66%   |
| 5.19.0  | 5        | 2.66%   |
| 6.4.11  | 4        | 2.13%   |
| 6.1.1   | 4        | 2.13%   |
| 5.11.0  | 3        | 1.6%    |
| 5.0.0   | 3        | 1.6%    |
| 4.19.0  | 3        | 1.6%    |
| 6.4.6   | 2        | 1.06%   |
| 6.4.3   | 2        | 1.06%   |
| 6.2.12  | 2        | 1.06%   |
| 6.1.0   | 2        | 1.06%   |
| 4.9.20  | 2        | 1.06%   |
| 4.9.0   | 2        | 1.06%   |
| 6.4.8   | 1        | 0.53%   |
| 6.4.7   | 1        | 0.53%   |
| 6.3.8   | 1        | 0.53%   |
| 6.2.0   | 1        | 0.53%   |
| 6.1.20  | 1        | 0.53%   |
| 6.0.5   | 1        | 0.53%   |
| 6.0.0   | 1        | 0.53%   |
| 5.9.16  | 1        | 0.53%   |
| 5.8.11  | 1        | 0.53%   |
| 5.8.10  | 1        | 0.53%   |
| 5.6.0   | 1        | 0.53%   |
| 5.19.9  | 1        | 0.53%   |
| 5.19.5  | 1        | 0.53%   |
| 5.18.7  | 1        | 0.53%   |
| 5.16.14 | 1        | 0.53%   |
| 5.15.6  | 1        | 0.53%   |
| 5.15.57 | 1        | 0.53%   |
| 5.15.48 | 1        | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 28       | 15.05%  |
| 5.4     | 27       | 14.52%  |
| 5.15    | 20       | 10.75%  |
| 4.15    | 19       | 10.22%  |
| 6.2     | 12       | 6.45%   |
| 5.16    | 11       | 5.91%   |
| 6.4     | 10       | 5.38%   |
| 5.8     | 8        | 4.3%    |
| 5.13    | 8        | 4.3%    |
| 5.19    | 7        | 3.76%   |
| 6.1     | 6        | 3.23%   |
| 5.3     | 5        | 2.69%   |
| 4.9     | 4        | 2.15%   |
| 5.11    | 3        | 1.61%   |
| 5.0     | 3        | 1.61%   |
| 4.19    | 3        | 1.61%   |
| 6.0     | 2        | 1.08%   |
| 6.3     | 1        | 0.54%   |
| 5.9     | 1        | 0.54%   |
| 5.6     | 1        | 0.54%   |
| 5.18    | 1        | 0.54%   |
| 5.14    | 1        | 0.54%   |
| 5.12    | 1        | 0.54%   |
| 4.4     | 1        | 0.54%   |
| 4.18    | 1        | 0.54%   |
| 4.13    | 1        | 0.54%   |
| 4.1     | 1        | 0.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 162      | 90.5%   |
| i686   | 17       | 9.5%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| KDE5            | 55       | 29.57%  |
| GNOME           | 52       | 27.96%  |
| XFCE            | 18       | 9.68%   |
| Unknown         | 15       | 8.06%   |
| X-Cinnamon      | 12       | 6.45%   |
| MATE            | 6        | 3.23%   |
| LXDE            | 5        | 2.69%   |
| KDE             | 5        | 2.69%   |
| KDE4            | 4        | 2.15%   |
| LXQt            | 3        | 1.61%   |
| Cinnamon        | 3        | 1.61%   |
| Pantheon        | 2        | 1.08%   |
| xmonad          | 1        | 0.54%   |
| Unity           | 1        | 0.54%   |
| Trinity         | 1        | 0.54%   |
| GNOME Flashback | 1        | 0.54%   |
| Budgie          | 1        | 0.54%   |
| awesome         | 1        | 0.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 148      | 81.32%  |
| Wayland | 29       | 15.93%  |
| Unknown | 4        | 2.2%    |
| Tty     | 1        | 0.55%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 73       | 40.11%  |
| SDDM    | 54       | 29.67%  |
| LightDM | 15       | 8.24%   |
| GDM     | 15       | 8.24%   |
| GDM3    | 12       | 6.59%   |
| TDM     | 7        | 3.85%   |
| KDM     | 4        | 2.2%    |
| SLiM    | 2        | 1.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_VE   | 108      | 59.67%  |
| en_US   | 36       | 19.89%  |
| Unknown | 17       | 9.39%   |
| es_ES   | 9        | 4.97%   |
| es_MX   | 5        | 2.76%   |
| es_US   | 2        | 1.1%    |
| C       | 2        | 1.1%    |
| es_CO   | 1        | 0.55%   |
| de_DE   | 1        | 0.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 151      | 85.31%  |
| EFI  | 26       | 14.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 131      | 71.98%  |
| Overlay | 27       | 14.84%  |
| Btrfs   | 12       | 6.59%   |
| Unknown | 5        | 2.75%   |
| Xfs     | 3        | 1.65%   |
| Tmpfs   | 3        | 1.65%   |
| Ext2    | 1        | 0.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 81       | 45.25%  |
| MBR     | 65       | 36.31%  |
| GPT     | 33       | 18.44%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 144      | 80.9%   |
| Yes       | 34       | 19.1%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 108      | 60%     |
| Yes       | 72       | 40%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASRock              | 32       | 18.08%  |
| ECS                 | 17       | 9.6%    |
| Intel               | 15       | 8.47%   |
| Pegatron            | 14       | 7.91%   |
| Gigabyte Technology | 14       | 7.91%   |
| Hewlett-Packard     | 13       | 7.34%   |
| Lenovo              | 12       | 6.78%   |
| Biostar             | 12       | 6.78%   |
| Dell                | 11       | 6.21%   |
| ASUSTek Computer    | 11       | 6.21%   |
| Foxconn             | 7        | 3.95%   |
| MSI                 | 6        | 3.39%   |
| langchao            | 6        | 3.39%   |
| Inspur              | 2        | 1.13%   |
| Soncview            | 1        | 0.56%   |
| SIRAGON             | 1        | 0.56%   |
| IP3 Tech            | 1        | 0.56%   |
| IBM                 | 1        | 0.56%   |
| Unknown             | 1        | 0.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ECS H61H2-CM                         | 10       | 5.65%   |
| ASRock G41M-VS3                      | 7        | 3.95%   |
| langchao 12345                       | 6        | 3.39%   |
| ASRock N68-VS3 UCC                   | 4        | 2.26%   |
| Pegatron Compaq dx2400 Microtower    | 3        | 1.69%   |
| HP Compaq 8200 Elite SFF PC          | 3        | 1.69%   |
| Biostar G41D3                        | 3        | 1.69%   |
| ASRock N68C-S UCC                    | 3        | 1.69%   |
| Pegatron IPM41-D3                    | 2        | 1.13%   |
| Intel H61                            | 2        | 1.13%   |
| Gigabyte 970A-DS3P                   | 2        | 1.13%   |
| ECS G31T-M7                          | 2        | 1.13%   |
| Dell OptiPlex 9020                   | 2        | 1.13%   |
| Dell OptiPlex 790                    | 2        | 1.13%   |
| Biostar G41D3C                       | 2        | 1.13%   |
| ASRock Wolfdale1333-D667             | 2        | 1.13%   |
| ASRock 945GCM-S                      | 2        | 1.13%   |
| Soncview G41D3C                      | 1        | 0.56%   |
| SIRAGON AIO-5150                     | 1        | 0.56%   |
| Pegatron PEGATRON                    | 1        | 0.56%   |
| Pegatron IPPEL-DB                    | 1        | 0.56%   |
| Pegatron IPMIP-H55-INSPUR            | 1        | 0.56%   |
| Pegatron CQ1507LA                    | 1        | 0.56%   |
| Pegatron Compaq dx2400 Microtower PC | 1        | 0.56%   |
| Pegatron BM411AA-ABA CQ5600F         | 1        | 0.56%   |
| Pegatron 2A73h                       | 1        | 0.56%   |
| Pegatron 20-b010                     | 1        | 0.56%   |
| Pegatron 100-5010la                  | 1        | 0.56%   |
| MSI Pro 3000 Microtower PC           | 1        | 0.56%   |
| MSI MS-7A38                          | 1        | 0.56%   |
| MSI MS-7850                          | 1        | 0.56%   |
| MSI MS-7817                          | 1        | 0.56%   |
| MSI MS-7721                          | 1        | 0.56%   |
| MSI MS-7375                          | 1        | 0.56%   |
| Lenovo ThinkCentre XXXX 8705A84      | 1        | 0.56%   |
| Lenovo ThinkCentre M91 7516AD1       | 1        | 0.56%   |
| Lenovo ThinkCentre M72e 3597A56      | 1        | 0.56%   |
| Lenovo ThinkCentre M71e 3157G6S      | 1        | 0.56%   |
| Lenovo ThinkCentre M55E 9645BN2      | 1        | 0.56%   |
| Lenovo ThinkCentre M55E 9632BU8      | 1        | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| ECS H61H2-CM              | 10       | 5.65%   |
| Lenovo ThinkCentre        | 9        | 5.08%   |
| HP Compaq                 | 9        | 5.08%   |
| Dell OptiPlex             | 7        | 3.95%   |
| ASRock G41M-VS3           | 7        | 3.95%   |
| langchao 12345            | 6        | 3.39%   |
| ASRock N68-VS3            | 5        | 2.82%   |
| Pegatron Compaq           | 4        | 2.26%   |
| Biostar G41D3             | 3        | 1.69%   |
| ASRock N68C-S             | 3        | 1.69%   |
| Pegatron IPM41-D3         | 2        | 1.13%   |
| Intel H61                 | 2        | 1.13%   |
| Intel DG41TY              | 2        | 1.13%   |
| HP EliteDesk              | 2        | 1.13%   |
| Gigabyte 970A-DS3P        | 2        | 1.13%   |
| ECS G31T-M7               | 2        | 1.13%   |
| Dell Vostro               | 2        | 1.13%   |
| Biostar G41D3C            | 2        | 1.13%   |
| ASUS P8H61-M              | 2        | 1.13%   |
| ASUS P5G41T-M             | 2        | 1.13%   |
| ASRock Wolfdale1333-D667  | 2        | 1.13%   |
| ASRock H61M-DGS           | 2        | 1.13%   |
| ASRock 945GCM-S           | 2        | 1.13%   |
| Soncview G41D3C           | 1        | 0.56%   |
| SIRAGON AIO-5150          | 1        | 0.56%   |
| Pegatron PEGATRON         | 1        | 0.56%   |
| Pegatron IPPEL-DB         | 1        | 0.56%   |
| Pegatron IPMIP-H55-INSPUR | 1        | 0.56%   |
| Pegatron CQ1507LA         | 1        | 0.56%   |
| Pegatron BM411AA-ABA      | 1        | 0.56%   |
| Pegatron 2A73h            | 1        | 0.56%   |
| Pegatron 20-b010          | 1        | 0.56%   |
| Pegatron 100-5010la       | 1        | 0.56%   |
| MSI Pro                   | 1        | 0.56%   |
| MSI MS-7A38               | 1        | 0.56%   |
| MSI MS-7850               | 1        | 0.56%   |
| MSI MS-7817               | 1        | 0.56%   |
| MSI MS-7721               | 1        | 0.56%   |
| MSI MS-7375               | 1        | 0.56%   |
| Lenovo H220               | 1        | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 42       | 23.73%  |
| 2010 | 36       | 20.34%  |
| 2008 | 19       | 10.73%  |
| 2012 | 18       | 10.17%  |
| 2007 | 13       | 7.34%   |
| 2013 | 9        | 5.08%   |
| 2014 | 7        | 3.95%   |
| 2009 | 7        | 3.95%   |
| 2006 | 7        | 3.95%   |
| 2021 | 4        | 2.26%   |
| 2020 | 4        | 2.26%   |
| 2017 | 4        | 2.26%   |
| 2019 | 2        | 1.13%   |
| 2016 | 2        | 1.13%   |
| 2015 | 1        | 0.56%   |
| 2005 | 1        | 0.56%   |
| 2002 | 1        | 0.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 177      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 177      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 177      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 54       | 29.67%  |
| 4.01-8.0    | 39       | 21.43%  |
| 8.01-16.0   | 28       | 15.38%  |
| 1.01-2.0    | 26       | 14.29%  |
| 16.01-24.0  | 17       | 9.34%   |
| 2.01-3.0    | 7        | 3.85%   |
| 32.01-64.0  | 4        | 2.2%    |
| 24.01-32.0  | 3        | 1.65%   |
| 64.01-256.0 | 2        | 1.1%    |
| 0.51-1.0    | 2        | 1.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 81       | 42.19%  |
| 2.01-3.0 | 47       | 24.48%  |
| 0.51-1.0 | 25       | 13.02%  |
| 3.01-4.0 | 18       | 9.38%   |
| 4.01-8.0 | 16       | 8.33%   |
| 0.01-0.5 | 5        | 2.6%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 102      | 55.74%  |
| 2      | 60       | 32.79%  |
| 3      | 16       | 8.74%   |
| 4      | 5        | 2.73%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 109      | 59.89%  |
| Yes       | 73       | 40.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 174      | 98.31%  |
| No        | 3        | 1.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 90       | 50%     |
| No        | 90       | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 159      | 89.33%  |
| Yes       | 19       | 10.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Venezuela | 177      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Caracas                  | 77       | 40.96%  |
| San Cristóbal           | 10       | 5.32%   |
| Valencia                 | 9        | 4.79%   |
| Maracay                  | 9        | 4.79%   |
| Maracaibo                | 9        | 4.79%   |
| Barquisimeto             | 9        | 4.79%   |
| San Carlos del Zulia     | 5        | 2.66%   |
| Maturín                 | 5        | 2.66%   |
| Barcelona                | 5        | 2.66%   |
| Ciudad Guayana           | 4        | 2.13%   |
| Vigia                    | 3        | 1.6%    |
| Mérida                  | 3        | 1.6%    |
| Ciudad Bolívar          | 3        | 1.6%    |
| Carrizal                 | 3        | 1.6%    |
| Barinas                  | 3        | 1.6%    |
| San Antonio de Los Altos | 2        | 1.06%   |
| Porlamar                 | 2        | 1.06%   |
| Los Teques               | 2        | 1.06%   |
| Acarigua                 | 2        | 1.06%   |
| Valle de La Pascua       | 1        | 0.53%   |
| Tucupita                 | 1        | 0.53%   |
| San Juan Bautista        | 1        | 0.53%   |
| San Francisco            | 1        | 0.53%   |
| Petare                   | 1        | 0.53%   |
| Parroquia El Recreo      | 1        | 0.53%   |
| Mene Grande              | 1        | 0.53%   |
| Los Palos Grandes        | 1        | 0.53%   |
| Lecherias                | 1        | 0.53%   |
| Las Vegas                | 1        | 0.53%   |
| La Guaira                | 1        | 0.53%   |
| Guatire                  | 1        | 0.53%   |
| Guarenas                 | 1        | 0.53%   |
| Distrito Federal         | 1        | 0.53%   |
| Cumaná                  | 1        | 0.53%   |
| Cua                      | 1        | 0.53%   |
| Ciudad Ojeda             | 1        | 0.53%   |
| Carora                   | 1        | 0.53%   |
| Cambural                 | 1        | 0.53%   |
| Cabimas                  | 1        | 0.53%   |
| Baruta                   | 1        | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 75       | 104    | 29.41%  |
| Seagate             | 60       | 82     | 23.53%  |
| Hitachi             | 35       | 42     | 13.73%  |
| Samsung Electronics | 23       | 27     | 9.02%   |
| Toshiba             | 16       | 18     | 6.27%   |
| Kingston            | 11       | 13     | 4.31%   |
| Maxtor              | 7        | 7      | 2.75%   |
| PNY                 | 3        | 4      | 1.18%   |
| Team                | 2        | 2      | 0.78%   |
| Sandisk             | 2        | 3      | 0.78%   |
| Patriot             | 2        | 2      | 0.78%   |
| HGST                | 2        | 2      | 0.78%   |
| Fujitsu             | 2        | 2      | 0.78%   |
| addlink             | 2        | 2      | 0.78%   |
| Unknown             | 1        | 1      | 0.39%   |
| SPCC                | 1        | 1      | 0.39%   |
| SK hynix            | 1        | 1      | 0.39%   |
| Phison Electronics  | 1        | 1      | 0.39%   |
| Netac               | 1        | 1      | 0.39%   |
| JMicron Technology  | 1        | 1      | 0.39%   |
| IBM/Hitachi         | 1        | 2      | 0.39%   |
| HPE                 | 1        | 2      | 0.39%   |
| ExcelStor           | 1        | 1      | 0.39%   |
| Emtec               | 1        | 1      | 0.39%   |
| Dogfish             | 1        | 1      | 0.39%   |
| Crucial             | 1        | 1      | 0.39%   |
| A-DATA Technology   | 1        | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST320LT012-1DG14C 320GB     | 11       | 3.83%   |
| Toshiba DT01ACA050 500GB            | 10       | 3.48%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 7        | 2.44%   |
| Seagate ST500DM002-1BD142 500GB     | 6        | 2.09%   |
| Samsung HD502HJ 500GB               | 6        | 2.09%   |
| Kingston SA400S37240G 240GB SSD     | 5        | 1.74%   |
| WDC WD3200AAJS-08L7A0 320GB         | 4        | 1.39%   |
| WDC WD3200AAJS-00L7A0 320GB         | 4        | 1.39%   |
| Seagate ST3320418AS 320GB           | 4        | 1.39%   |
| Seagate ST320LM000 HM321HI 320GB    | 4        | 1.39%   |
| Samsung HD161HJ 160GB               | 4        | 1.39%   |
| Hitachi HTS543225L9A300 250GB       | 4        | 1.39%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 3        | 1.05%   |
| WDC WD5000AAKX-221CA1 500GB         | 3        | 1.05%   |
| WDC WD5000AAKX-001CA0 500GB         | 3        | 1.05%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 3        | 1.05%   |
| WDC WD5000AAKS-00A7B0 500GB         | 3        | 1.05%   |
| Seagate ST4000DM000-1F2168 4TB      | 3        | 1.05%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 3        | 1.05%   |
| Samsung HD161GJ 160GB               | 3        | 1.05%   |
| Maxtor STM3160215AS 160GB           | 3        | 1.05%   |
| Kingston SA400S37120G 120GB SSD     | 3        | 1.05%   |
| Hitachi HTS542580K9SA00 80GB        | 3        | 1.05%   |
| Hitachi HDS728080PLA380 82GB        | 3        | 1.05%   |
| Hitachi HDS5C1050CLA382 500GB       | 3        | 1.05%   |
| WDC WD800BD-22MRA1 80GB             | 2        | 0.7%    |
| WDC WD800BB-22JHC0 80GB             | 2        | 0.7%    |
| WDC WD5000AAKX-753CA1 500GB         | 2        | 0.7%    |
| WDC WD2500AAJS-60B4A0 250GB         | 2        | 0.7%    |
| WDC WD1600BEVT-22ZCT0 160GB         | 2        | 0.7%    |
| WDC WD1600AABS-00PRA0 160GB         | 2        | 0.7%    |
| WDC WD10EZEX-22RKKA0 1TB            | 2        | 0.7%    |
| Seagate ST500DM005 HD502HJ 500GB    | 2        | 0.7%    |
| Seagate ST500DM002-1BC142 500GB     | 2        | 0.7%    |
| Seagate ST3500413AS 500GB           | 2        | 0.7%    |
| Seagate ST3250310AS 250GB           | 2        | 0.7%    |
| Seagate ST3160215ACE 160GB          | 2        | 0.7%    |
| Seagate ST2000DM001-1CH164 2TB      | 2        | 0.7%    |
| Hitachi HTS545032B9A300 320GB       | 2        | 0.7%    |
| Hitachi HDS721616PLA380 160GB       | 2        | 0.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 75       | 104    | 34.09%  |
| Seagate             | 60       | 82     | 27.27%  |
| Hitachi             | 35       | 42     | 15.91%  |
| Samsung Electronics | 20       | 23     | 9.09%   |
| Toshiba             | 16       | 18     | 7.27%   |
| Maxtor              | 7        | 7      | 3.18%   |
| HGST                | 2        | 2      | 0.91%   |
| Fujitsu             | 2        | 2      | 0.91%   |
| IBM/Hitachi         | 1        | 2      | 0.45%   |
| HPE                 | 1        | 1      | 0.45%   |
| ExcelStor           | 1        | 1      | 0.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 11       | 13     | 36.67%  |
| PNY                 | 3        | 4      | 10%     |
| Team                | 2        | 2      | 6.67%   |
| Samsung Electronics | 2        | 3      | 6.67%   |
| Patriot             | 2        | 2      | 6.67%   |
| addlink             | 2        | 2      | 6.67%   |
| SPCC                | 1        | 1      | 3.33%   |
| SanDisk             | 1        | 1      | 3.33%   |
| Netac               | 1        | 1      | 3.33%   |
| JMicron Technology  | 1        | 1      | 3.33%   |
| Emtec               | 1        | 1      | 3.33%   |
| Dogfish             | 1        | 1      | 3.33%   |
| Crucial             | 1        | 1      | 3.33%   |
| A-DATA Technology   | 1        | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 161      | 284    | 82.56%  |
| SSD     | 27       | 34     | 13.85%  |
| NVMe    | 6        | 6      | 3.08%   |
| Unknown | 1        | 1      | 0.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 174      | 318    | 96.13%  |
| NVMe | 6        | 6      | 3.31%   |
| SAS  | 1        | 1      | 0.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 160      | 264    | 78.43%  |
| 0.51-1.0   | 28       | 32     | 13.73%  |
| 1.01-2.0   | 9        | 10     | 4.41%   |
| 3.01-4.0   | 4        | 8      | 1.96%   |
| 2.01-3.0   | 2        | 3      | 0.98%   |
| 4.01-10.0  | 1        | 1      | 0.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 62       | 32.63%  |
| 101-250        | 41       | 21.58%  |
| 1-20           | 22       | 11.58%  |
| 501-1000       | 22       | 11.58%  |
| 51-100         | 16       | 8.42%   |
| 1001-2000      | 10       | 5.26%   |
| 21-50          | 7        | 3.68%   |
| 2001-3000      | 4        | 2.11%   |
| Unknown        | 4        | 2.11%   |
| More than 3000 | 2        | 1.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 83       | 43.92%  |
| 21-50          | 33       | 17.46%  |
| 101-250        | 22       | 11.64%  |
| 251-500        | 18       | 9.52%   |
| 51-100         | 14       | 7.41%   |
| 501-1000       | 8        | 4.23%   |
| 1001-2000      | 4        | 2.12%   |
| Unknown        | 4        | 2.12%   |
| 2001-3000      | 2        | 1.06%   |
| More than 3000 | 1        | 0.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST320LT012-1DG14C 320GB   | 6        | 7      | 7.5%    |
| WDC WD5000AAKX-22ERMA0 500GB      | 4        | 5      | 5%      |
| Toshiba DT01ACA050 500GB          | 4        | 5      | 5%      |
| Hitachi HTS543225L9A300 250GB     | 4        | 4      | 5%      |
| WDC WD5000AAKX-221CA1 500GB       | 2        | 2      | 2.5%    |
| WDC WD5000AAKS-00A7B0 500GB       | 2        | 2      | 2.5%    |
| WDC WD3200AAJS-08L7A0 320GB       | 2        | 3      | 2.5%    |
| Seagate ST500DM002-1BD142 500GB   | 2        | 2      | 2.5%    |
| Samsung Electronics HD161GJ 160GB | 2        | 2      | 2.5%    |
| Maxtor STM3160215AS 160GB         | 2        | 2      | 2.5%    |
| Hitachi HDS728080PLA380 82GB      | 2        | 2      | 2.5%    |
| Hitachi HDS721616PLA380 160GB     | 2        | 2      | 2.5%    |
| WDC WD800BD-08MRA1 80GB           | 1        | 1      | 1.25%   |
| WDC WD800BB-22JHC0 80GB           | 1        | 1      | 1.25%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 1        | 1      | 1.25%   |
| WDC WD5000AAKX-08U6AA0 500GB      | 1        | 1      | 1.25%   |
| WDC WD5000AAKX-08ERMA0 500GB      | 1        | 2      | 1.25%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 1.25%   |
| WDC WD5000AACS-00ZUB0 500GB       | 1        | 1      | 1.25%   |
| WDC WD3200BEKT-22F3T0 320GB       | 1        | 1      | 1.25%   |
| WDC WD3200BEKT-08PVMT1 320GB      | 1        | 1      | 1.25%   |
| WDC WD2003FYPS-27Y2B0 2TB         | 1        | 1      | 1.25%   |
| WDC WD10EZEX-22RKKA0 1TB          | 1        | 1      | 1.25%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 1        | 1      | 1.25%   |
| Toshiba MK3275GSX 320GB           | 1        | 1      | 1.25%   |
| Seagate ST500DM005 HD502HJ 500GB  | 1        | 1      | 1.25%   |
| Seagate ST3500630AS 500GB         | 1        | 1      | 1.25%   |
| Seagate ST3500418AS 500GB         | 1        | 1      | 1.25%   |
| Seagate ST3500413AS 500GB         | 1        | 1      | 1.25%   |
| Seagate ST3500312CS 500GB         | 1        | 1      | 1.25%   |
| Seagate ST340014AS 40GB           | 1        | 1      | 1.25%   |
| Seagate ST3320418AS 320GB         | 1        | 2      | 1.25%   |
| Seagate ST3250318AS 250GB         | 1        | 1      | 1.25%   |
| Seagate ST3250310AS 250GB         | 1        | 1      | 1.25%   |
| Seagate ST3160215ACE 160GB        | 1        | 1      | 1.25%   |
| Seagate ST3160212SCE 160GB        | 1        | 1      | 1.25%   |
| Seagate ST31000528AS 1TB          | 1        | 1      | 1.25%   |
| Seagate ST31000525SV 1TB          | 1        | 1      | 1.25%   |
| Seagate ST2000DM001-1CH164 2TB    | 1        | 1      | 1.25%   |
| Seagate ST1000DM003-9YN162 1TB    | 1        | 1      | 1.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 22       | 25     | 30.56%  |
| Hitachi             | 17       | 17     | 23.61%  |
| WDC                 | 16       | 25     | 22.22%  |
| Samsung Electronics | 6        | 7      | 8.33%   |
| Toshiba             | 4        | 6      | 5.56%   |
| Maxtor              | 3        | 3      | 4.17%   |
| JMicron Technology  | 1        | 1      | 1.39%   |
| IBM/Hitachi         | 1        | 2      | 1.39%   |
| HGST                | 1        | 1      | 1.39%   |
| ExcelStor           | 1        | 1      | 1.39%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 22       | 25     | 30.99%  |
| Hitachi             | 17       | 17     | 23.94%  |
| WDC                 | 16       | 25     | 22.54%  |
| Samsung Electronics | 6        | 7      | 8.45%   |
| Toshiba             | 4        | 6      | 5.63%   |
| Maxtor              | 3        | 3      | 4.23%   |
| IBM/Hitachi         | 1        | 2      | 1.41%   |
| HGST                | 1        | 1      | 1.41%   |
| ExcelStor           | 1        | 1      | 1.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 57       | 87     | 98.28%  |
| SSD  | 1        | 1      | 1.72%   |

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
| Detected | 90       | 169    | 45.92%  |
| Malfunc  | 57       | 88     | 29.08%  |
| Works    | 45       | 64     | 22.96%  |
| Failed   | 4        | 4      | 2.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 138      | 69.7%   |
| AMD                      | 19       | 9.6%    |
| Nvidia                   | 17       | 8.59%   |
| Marvell Technology Group | 6        | 3.03%   |
| JMicron Technology       | 6        | 3.03%   |
| VIA Technologies         | 3        | 1.52%   |
| SanDisk                  | 2        | 1.01%   |
| ASMedia Technology       | 2        | 1.01%   |
| SK hynix                 | 1        | 0.51%   |
| Samsung Electronics      | 1        | 0.51%   |
| Phison Electronics       | 1        | 0.51%   |
| Jiangsu Huacun Elec.     | 1        | 0.51%   |
| Adaptec                  | 1        | 0.51%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 48       | 15.89%  |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 38       | 12.58%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 22       | 7.28%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 17       | 5.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 17       | 5.63%   |
| Nvidia MCP61 SATA Controller                                                            | 16       | 5.3%    |
| Nvidia MCP61 IDE                                                                        | 14       | 4.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 2.65%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 7        | 2.32%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 7        | 2.32%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 1.99%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 6        | 1.99%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 1.66%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 5        | 1.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 1.66%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 1.32%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3        | 0.99%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 0.99%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3        | 0.99%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3        | 0.99%   |
| VIA Serial ATA Controller                                                               | 2        | 0.66%   |
| JMicron JMB368 IDE controller                                                           | 2        | 0.66%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.66%   |
| JMicron JMB362 SATA Controller                                                          | 2        | 0.66%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 0.66%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 0.66%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.66%   |
| Intel 82801EB (ICH5) SATA Controller                                                    | 2        | 0.66%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.66%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 0.66%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 0.66%   |
| AMD FCH SATA Controller D                                                               | 2        | 0.66%   |
| AMD FCH IDE Controller                                                                  | 2        | 0.66%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 0.66%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 1        | 0.33%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 1        | 0.33%   |
| SanDisk WD Blue SN570 NVMe SSD 2TB                                                      | 1        | 0.33%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 115      | 57.5%   |
| SATA | 72       | 36%     |
| NVMe | 6        | 3%      |
| RAID | 5        | 2.5%    |
| SAS  | 1        | 0.5%    |
| SCSI | 1        | 0.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 141      | 79.66%  |
| AMD    | 36       | 20.34%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 9        | 5.08%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 7        | 3.95%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 5        | 2.82%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 4        | 2.26%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 4        | 2.26%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 4        | 2.26%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 4        | 2.26%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 3        | 1.69%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 3        | 1.69%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 3        | 1.69%   |
| Intel Pentium 4 CPU 3.00GHz                 | 3        | 1.69%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 1.69%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 1.69%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.69%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 1.69%   |
| AMD Sempron 145 Processor                   | 3        | 1.69%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 1.13%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz      | 2        | 1.13%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 2        | 1.13%   |
| Intel Pentium CPU G640 @ 2.80GHz            | 2        | 1.13%   |
| Intel Pentium 4 CPU 3.20GHz                 | 2        | 1.13%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.13%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.13%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.13%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 1.13%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2        | 1.13%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 1.13%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2        | 1.13%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2        | 1.13%   |
| Intel Core 2 CPU 4400 @ 2.00GHz             | 2        | 1.13%   |
| AMD Sempron 140 Processor                   | 2        | 1.13%   |
| AMD FX-6300 Six-Core Processor              | 2        | 1.13%   |
| AMD FX-6100 Six-Core Processor              | 2        | 1.13%   |
| AMD Athlon II X2 250 Processor              | 2        | 1.13%   |
| Intel Xeon CPU X3220 @ 2.40GHz              | 1        | 0.56%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.56%   |
| Intel Xeon CPU E5-1607 0 @ 3.00GHz          | 1        | 0.56%   |
| Intel Xeon CPU E31225 @ 3.10GHz             | 1        | 0.56%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 1        | 0.56%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Pentium Dual-Core | 31       | 17.51%  |
| Intel Core i5           | 26       | 14.69%  |
| Intel Pentium           | 15       | 8.47%   |
| Intel Core i7           | 11       | 6.21%   |
| Intel Core i3           | 10       | 5.65%   |
| Intel Core 2 Duo        | 10       | 5.65%   |
| Intel Pentium Dual      | 8        | 4.52%   |
| AMD Sempron             | 7        | 3.95%   |
| Intel Pentium 4         | 6        | 3.39%   |
| Intel Core 2 Quad       | 6        | 3.39%   |
| Intel Core 2            | 5        | 2.82%   |
| Other                   | 4        | 2.26%   |
| Intel Xeon              | 4        | 2.26%   |
| AMD FX                  | 4        | 2.26%   |
| AMD Athlon II X2        | 4        | 2.26%   |
| AMD Ryzen 5             | 3        | 1.69%   |
| AMD Phenom II X4        | 3        | 1.69%   |
| Intel Pentium D         | 2        | 1.13%   |
| Intel Celeron           | 2        | 1.13%   |
| AMD Phenom              | 2        | 1.13%   |
| AMD Athlon II X4        | 2        | 1.13%   |
| AMD Athlon 64 X2        | 2        | 1.13%   |
| AMD Athlon              | 2        | 1.13%   |
| Intel Atom              | 1        | 0.56%   |
| AMD Ryzen 3             | 1        | 0.56%   |
| AMD Phenom II X2        | 1        | 0.56%   |
| AMD E1                  | 1        | 0.56%   |
| AMD Athlon II           | 1        | 0.56%   |
| AMD A8                  | 1        | 0.56%   |
| AMD A6                  | 1        | 0.56%   |
| AMD A4                  | 1        | 0.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 94       | 53.11%  |
| 4       | 55       | 31.07%  |
| 1       | 15       | 8.47%   |
| 6       | 5        | 2.82%   |
| 3       | 5        | 2.82%   |
| Unknown | 2        | 1.13%   |
| 8       | 1        | 0.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 177      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 135      | 76.27%  |
| 2       | 40       | 22.6%   |
| Unknown | 2        | 1.13%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 172      | 97.18%  |
| 64-bit         | 2        | 1.13%   |
| 32-bit         | 2        | 1.13%   |
| Unknown        | 1        | 0.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 45       | 25%     |
| 0x1067a    | 31       | 17.22%  |
| 0x206a7    | 20       | 11.11%  |
| 0x306a9    | 10       | 5.56%   |
| 0x306c3    | 7        | 3.89%   |
| 0x6fd      | 6        | 3.33%   |
| 0x010000c8 | 5        | 2.78%   |
| 0xf65      | 4        | 2.22%   |
| 0x6fb      | 4        | 2.22%   |
| 0x6f2      | 3        | 1.67%   |
| 0x10676    | 3        | 1.67%   |
| 0x010000c7 | 3        | 1.67%   |
| 0x010000b6 | 3        | 1.67%   |
| 0xa0671    | 2        | 1.11%   |
| 0x106a5    | 2        | 1.11%   |
| 0x06000852 | 2        | 1.11%   |
| 0x0600063e | 2        | 1.11%   |
| 0x03000027 | 2        | 1.11%   |
| 0xf47      | 1        | 0.56%   |
| 0xf43      | 1        | 0.56%   |
| 0xf41      | 1        | 0.56%   |
| 0xf12      | 1        | 0.56%   |
| 0x906eb    | 1        | 0.56%   |
| 0x906e9    | 1        | 0.56%   |
| 0x806c1    | 1        | 0.56%   |
| 0x6f6      | 1        | 0.56%   |
| 0x506e3    | 1        | 0.56%   |
| 0x206d7    | 1        | 0.56%   |
| 0x20652    | 1        | 0.56%   |
| 0x106ca    | 1        | 0.56%   |
| 0x10661    | 1        | 0.56%   |
| 0x0a50000c | 1        | 0.56%   |
| 0x08701030 | 1        | 0.56%   |
| 0x0810100b | 1        | 0.56%   |
| 0x0800820d | 1        | 0.56%   |
| 0x0700010b | 1        | 0.56%   |
| 0x06001119 | 1        | 0.56%   |
| 0x05000119 | 1        | 0.56%   |
| 0x03000014 | 1        | 0.56%   |
| 0x010000dc | 1        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 44       | 24.86%  |
| SandyBridge | 28       | 15.82%  |
| Core        | 20       | 11.3%   |
| K10         | 18       | 10.17%  |
| IvyBridge   | 18       | 10.17%  |
| Haswell     | 11       | 6.21%   |
| NetBurst    | 8        | 4.52%   |
| K8 Hammer   | 4        | 2.26%   |
| Piledriver  | 3        | 1.69%   |
| Zen+        | 2        | 1.13%   |
| Westmere    | 2        | 1.13%   |
| Nehalem     | 2        | 1.13%   |
| KabyLake    | 2        | 1.13%   |
| K10 Llano   | 2        | 1.13%   |
| Bulldozer   | 2        | 1.13%   |
| Unknown     | 2        | 1.13%   |
| Zen 3       | 1        | 0.56%   |
| Zen 2       | 1        | 0.56%   |
| Zen         | 1        | 0.56%   |
| TigerLake   | 1        | 0.56%   |
| Skylake     | 1        | 0.56%   |
| Jaguar      | 1        | 0.56%   |
| Icelake     | 1        | 0.56%   |
| Bonnell     | 1        | 0.56%   |
| Bobcat      | 1        | 0.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 103      | 55.08%  |
| Nvidia           | 44       | 23.53%  |
| AMD              | 37       | 19.79%  |
| VIA Technologies | 3        | 1.6%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 23       | 12.11%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 23       | 12.11%  |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 10       | 5.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9        | 4.74%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 8        | 4.21%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 7        | 3.68%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 2.11%   |
| Nvidia GF119 [GeForce GT 520]                                               | 4        | 2.11%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 4        | 2.11%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 2.11%   |
| Intel 82946GZ/GL Integrated Graphics Controller                             | 4        | 2.11%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 4        | 2.11%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 3        | 1.58%   |
| Nvidia GF119 [GeForce GT 610]                                               | 3        | 1.58%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 3        | 1.58%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 3        | 1.58%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 3        | 1.58%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 3        | 1.58%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 1.05%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.05%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 2        | 1.05%   |
| Intel 82865G Integrated Graphics Controller                                 | 2        | 1.05%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 1.05%   |
| AMD RV670 [Radeon HD 3870]                                                  | 2        | 1.05%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 1.05%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 2        | 1.05%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 1.05%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 1.05%   |
| Nvidia NV44 [GeForce 7100 GS]                                               | 1        | 0.53%   |
| Nvidia NV44 [GeForce 6200 LE]                                               | 1        | 0.53%   |
| Nvidia GT218 [GeForce 405]                                                  | 1        | 0.53%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.53%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 0.53%   |
| Nvidia GK104GL [Quadro K4200]                                               | 1        | 0.53%   |
| Nvidia GF119 [GeForce 605]                                                  | 1        | 0.53%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 0.53%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                       | 1        | 0.53%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 0.53%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 0.53%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Intel    | 96       | 53.93%  |
| 1 x Nvidia   | 42       | 23.6%   |
| 1 x AMD      | 31       | 17.42%  |
| 2 x AMD      | 3        | 1.69%   |
| 1 x VIA      | 3        | 1.69%   |
| AMD + Nvidia | 2        | 1.12%   |
| Intel + AMD  | 1        | 0.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 146      | 82.02%  |
| Proprietary | 19       | 10.67%  |
| Unknown     | 13       | 7.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 102      | 56.04%  |
| 0.51-1.0   | 33       | 18.13%  |
| 0.01-0.5   | 26       | 14.29%  |
| 1.01-2.0   | 16       | 8.79%   |
| 3.01-4.0   | 5        | 2.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung Electronics                   | 39       | 26%     |
| Hewlett-Packard                       | 16       | 10.67%  |
| Goldstar                              | 16       | 10.67%  |
| Toshiba                               | 11       | 7.33%   |
| Dell                                  | 10       | 6.67%   |
| Lenovo                                | 9        | 6%      |
| AOC                                   | 9        | 6%      |
| Acer                                  | 9        | 6%      |
| BenQ                                  | 4        | 2.67%   |
| Vita                                  | 3        | 2%      |
| LG Electronics                        | 3        | 2%      |
| Unknown (XXX)                         | 2        | 1.33%   |
| Sony                                  | 2        | 1.33%   |
| Envision                              | 2        | 1.33%   |
| ViewSonic                             | 1        | 0.67%   |
| Toshiba Matsushita Display Technology | 1        | 0.67%   |
| TCL                                   | 1        | 0.67%   |
| Plain Tree Systems                    | 1        | 0.67%   |
| PEGA                                  | 1        | 0.67%   |
| Parker                                | 1        | 0.67%   |
| NEC Computers                         | 1        | 0.67%   |
| MStar                                 | 1        | 0.67%   |
| MSI                                   | 1        | 0.67%   |
| LSC                                   | 1        | 0.67%   |
| IBM                                   | 1        | 0.67%   |
| Haier                                 | 1        | 0.67%   |
| eMachines                             | 1        | 0.67%   |
| CVT                                   | 1        | 0.67%   |
| AOpen                                 | 1        | 0.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch             | 8        | 5.13%   |
| Lenovo LEN L174 LEN240B 1280x1024 340x270mm 17.1-inch                | 5        | 3.21%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 4        | 2.56%   |
| Vita V195EW-W VIT1950 1600x900 430x240mm 19.4-inch                   | 3        | 1.92%   |
| Toshiba TV TSB0206 1920x1080                                         | 3        | 1.92%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch          | 3        | 1.92%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch | 2        | 1.28%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 2        | 1.28%   |
| Samsung Electronics S19A10N SAM083E 1366x768 410x230mm 18.5-inch     | 2        | 1.28%   |
| Lenovo LEN L151 LEN23CD 1024x768 304x228mm 15.0-inch                 | 2        | 1.28%   |
| Hewlett-Packard S1933 HWP2933 1366x768 413x234mm 18.7-inch           | 2        | 1.28%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 2        | 1.28%   |
| Acer B193W ACR001E 1440x900 408x255mm 18.9-inch                      | 2        | 1.28%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch        | 1        | 0.64%   |
| Unknown (XXX) L9W XXX076E 1440x900 410x256mm 19.0-inch               | 1        | 0.64%   |
| Unknown (XXX) 1772ED XXX1772 1280x1024 320x250mm 16.0-inch           | 1        | 0.64%   |
| Unknown (XXX) 1772E XXX1772 1280x1024 320x250mm 16.0-inch            | 1        | 0.64%   |
| Toshiba Matsushita Display Technology LCD Monitor LCD-MONITOR        | 1        | 0.64%   |
| TCL T-7005L TCL1770 1280x1024 338x270mm 17.0-inch                    | 1        | 0.64%   |
| Sony TV SNYEB01 1360x768                                             | 1        | 0.64%   |
| Sony TV SNYEA01 1920x1080                                            | 1        | 0.64%   |
| Sony TV SNYDC01 1360x768                                             | 1        | 0.64%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch    | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch  | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch  | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM055E 1920x1080 510x290mm 23.1-inch | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM049C 1920x1080 477x268mm 21.5-inch | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0499 1600x900 443x249mm 20.0-inch  | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch  | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM03F5 1920x1200                     | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM03F4 1920x1200 518x324mm 24.1-inch | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 344x194mm 15.5-inch  | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch  | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch  | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch  | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0004 1024x768 304x228mm 15.0-inch  | 1        | 0.64%   |
| Samsung Electronics SMBX2050N SAM0719 1600x900 443x249mm 20.0-inch   | 1        | 0.64%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch   | 1        | 0.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 30       | 19.74%  |
| 1366x768 (WXGA)    | 30       | 19.74%  |
| 1280x1024 (SXGA)   | 30       | 19.74%  |
| 1440x900 (WXGA+)   | 21       | 13.82%  |
| 1600x900 (HD+)     | 11       | 7.24%   |
| 1024x768 (XGA)     | 8        | 5.26%   |
| 1360x768           | 7        | 4.61%   |
| 1680x1050 (WSXGA+) | 5        | 3.29%   |
| 1280x720 (HD)      | 3        | 1.97%   |
| 3840x2160 (4K)     | 2        | 1.32%   |
| 1920x1200 (WUXGA)  | 2        | 1.32%   |
| Unknown            | 2        | 1.32%   |
| 3840x1080          | 1        | 0.66%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 36       | 23.84%  |
| 17      | 24       | 15.89%  |
| 19      | 18       | 11.92%  |
| 21      | 16       | 10.6%   |
| Unknown | 12       | 7.95%   |
| 15      | 11       | 7.28%   |
| 23      | 8        | 5.3%    |
| 20      | 7        | 4.64%   |
| 74      | 3        | 1.99%   |
| 22      | 3        | 1.99%   |
| 16      | 3        | 1.99%   |
| 72      | 2        | 1.32%   |
| 13      | 2        | 1.32%   |
| 52      | 1        | 0.66%   |
| 42      | 1        | 0.66%   |
| 39      | 1        | 0.66%   |
| 31      | 1        | 0.66%   |
| 27      | 1        | 0.66%   |
| 24      | 1        | 0.66%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 75       | 50%     |
| 301-350     | 33       | 22%     |
| Unknown     | 12       | 8%      |
| 501-600     | 10       | 6.67%   |
| 351-400     | 9        | 6%      |
| 1501-2000   | 5        | 3.33%   |
| 201-300     | 2        | 1.33%   |
| 801-900     | 1        | 0.67%   |
| 601-700     | 1        | 0.67%   |
| 1001-1500   | 1        | 0.67%   |
| 901-1000    | 1        | 0.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 71       | 47.65%  |
| 16/10   | 31       | 20.81%  |
| 5/4     | 28       | 18.79%  |
| Unknown | 10       | 6.71%   |
| 4/3     | 8        | 5.37%   |
| 3/2     | 1        | 0.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 141-150        | 48       | 31.79%  |
| 151-200        | 40       | 26.49%  |
| 201-250        | 22       | 14.57%  |
| Unknown        | 12       | 7.95%   |
| 101-110        | 11       | 7.28%   |
| More than 1000 | 6        | 3.97%   |
| 121-130        | 3        | 1.99%   |
| 131-140        | 2        | 1.32%   |
| 501-1000       | 2        | 1.32%   |
| 81-90          | 1        | 0.66%   |
| 351-500        | 1        | 0.66%   |
| 301-350        | 1        | 0.66%   |
| 251-300        | 1        | 0.66%   |
| 91-100         | 1        | 0.66%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 109      | 73.15%  |
| 101-120 | 20       | 13.42%  |
| Unknown | 12       | 8.05%   |
| 1-50    | 7        | 4.7%    |
| 121-160 | 1        | 0.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 150      | 84.75%  |
| 0     | 17       | 9.6%    |
| 2     | 9        | 5.08%   |
| 3     | 1        | 0.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 107      | 39.19%  |
| Qualcomm Atheros                  | 40       | 14.65%  |
| Intel                             | 39       | 14.29%  |
| Ralink                            | 17       | 6.23%   |
| Nvidia                            | 17       | 6.23%   |
| Ralink Technology                 | 10       | 3.66%   |
| Broadcom                          | 10       | 3.66%   |
| Xiaomi                            | 5        | 1.83%   |
| Qualcomm Atheros Communications   | 4        | 1.47%   |
| VIA Technologies                  | 3        | 1.1%    |
| TP-Link                           | 3        | 1.1%    |
| Sundance Technology Inc / IC Plus | 2        | 0.73%   |
| Mercucys                          | 2        | 0.73%   |
| Marvell Technology Group          | 2        | 0.73%   |
| D-Link System                     | 2        | 0.73%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.37%   |
| Trendchip Technologies            | 1        | 0.37%   |
| Samsung Electronics               | 1        | 0.37%   |
| National Semiconductor            | 1        | 0.37%   |
| Motorola PCS                      | 1        | 0.37%   |
| Motorola BCS                      | 1        | 0.37%   |
| JMicron Technology                | 1        | 0.37%   |
| ICS Advent                        | 1        | 0.37%   |
| Davicom Semiconductor             | 1        | 0.37%   |
| Broadcom Limited                  | 1        | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 71       | 24.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 20       | 6.85%   |
| Nvidia MCP61 Ethernet                                                          | 16       | 5.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 13       | 4.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 10       | 3.42%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 8        | 2.74%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 7        | 2.4%    |
| Intel Ethernet Connection I217-LM                                              | 6        | 2.05%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 5        | 1.71%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 5        | 1.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 5        | 1.71%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 4        | 1.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 4        | 1.37%   |
| Ralink MT7601U Wireless Adapter                                                | 4        | 1.37%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 4        | 1.37%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 4        | 1.37%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                          | 4        | 1.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3        | 1.03%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 3        | 1.03%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 3        | 1.03%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 3        | 1.03%   |
| Qualcomm Atheros AR9271 802.11n                                                | 3        | 1.03%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3        | 1.03%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 2        | 0.68%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 2        | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 2        | 0.68%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 2        | 0.68%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 2        | 0.68%   |
| Realtek 802.11ac NIC                                                           | 2        | 0.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2        | 0.68%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                               | 2        | 0.68%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                               | 2        | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2        | 0.68%   |
| Mercucys MW300UM RTL8192EU wifi                                                | 2        | 0.68%   |
| Intel PRO/100 VE Network Connection                                            | 2        | 0.68%   |
| Intel Ethernet Connection I217-V                                               | 2        | 0.68%   |
| Intel 82567V-2 Gigabit Network Connection                                      | 2        | 0.68%   |
| Broadcom BCM43225 802.11b/g/n                                                  | 2        | 0.68%   |
| ZTE WCDMA MSM ZXIC Mobile Boardband                                            | 1        | 0.34%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros                | 27       | 28.42%  |
| Realtek Semiconductor           | 20       | 21.05%  |
| Ralink                          | 17       | 17.89%  |
| Ralink Technology               | 10       | 10.53%  |
| Intel                           | 6        | 6.32%   |
| Qualcomm Atheros Communications | 4        | 4.21%   |
| TP-Link                         | 3        | 3.16%   |
| Broadcom                        | 3        | 3.16%   |
| Mercucys                        | 2        | 2.11%   |
| D-Link System                   | 2        | 2.11%   |
| Xiaomi                          | 1        | 1.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 8        | 8.42%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 7        | 7.37%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 5        | 5.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 5        | 5.26%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 4        | 4.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 4        | 4.21%   |
| Ralink MT7601U Wireless Adapter                                                | 4        | 4.21%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 4        | 4.21%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 4        | 4.21%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 3        | 3.16%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 3        | 3.16%   |
| Qualcomm Atheros AR9271 802.11n                                                | 3        | 3.16%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3        | 3.16%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 2        | 2.11%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 2        | 2.11%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 2        | 2.11%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 2        | 2.11%   |
| Realtek 802.11ac NIC                                                           | 2        | 2.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2        | 2.11%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                               | 2        | 2.11%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                               | 2        | 2.11%   |
| Mercucys MW300UM RTL8192EU wifi                                                | 2        | 2.11%   |
| Broadcom BCM43225 802.11b/g/n                                                  | 2        | 2.11%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                              | 1        | 1.05%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                    | 1        | 1.05%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                      | 1        | 1.05%   |
| Ralink RT5372 Wireless Adapter                                                 | 1        | 1.05%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                         | 1        | 1.05%   |
| Ralink RT2800 802.11n PCI                                                      | 1        | 1.05%   |
| Ralink RT2561/RT61 802.11g PCI                                                 | 1        | 1.05%   |
| Qualcomm Atheros AR5523                                                        | 1        | 1.05%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]            | 1        | 1.05%   |
| Intel Wireless 7265                                                            | 1        | 1.05%   |
| Intel Wireless 7260                                                            | 1        | 1.05%   |
| Intel Wi-Fi 6 AX200                                                            | 1        | 1.05%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 1        | 1.05%   |
| Intel Centrino Wireless-N 105                                                  | 1        | 1.05%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 1        | 1.05%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]           | 1        | 1.05%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]              | 1        | 1.05%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 97       | 50.26%  |
| Intel                             | 35       | 18.13%  |
| Qualcomm Atheros                  | 17       | 8.81%   |
| Nvidia                            | 17       | 8.81%   |
| Broadcom                          | 7        | 3.63%   |
| Xiaomi                            | 4        | 2.07%   |
| VIA Technologies                  | 3        | 1.55%   |
| Sundance Technology Inc / IC Plus | 2        | 1.04%   |
| Marvell Technology Group          | 2        | 1.04%   |
| Trendchip Technologies            | 1        | 0.52%   |
| Samsung Electronics               | 1        | 0.52%   |
| National Semiconductor            | 1        | 0.52%   |
| Motorola PCS                      | 1        | 0.52%   |
| Motorola BCS                      | 1        | 0.52%   |
| JMicron Technology                | 1        | 0.52%   |
| ICS Advent                        | 1        | 0.52%   |
| Davicom Semiconductor             | 1        | 0.52%   |
| Broadcom Limited                  | 1        | 0.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 71       | 36.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 20       | 10.2%   |
| Nvidia MCP61 Ethernet                                                      | 16       | 8.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 13       | 6.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 10       | 5.1%    |
| Intel Ethernet Connection I217-LM                                          | 6        | 3.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 5        | 2.55%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                      | 4        | 2.04%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 3        | 1.53%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 3        | 1.53%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 2        | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 1.02%   |
| Intel PRO/100 VE Network Connection                                        | 2        | 1.02%   |
| Intel Ethernet Connection I217-V                                           | 2        | 1.02%   |
| Intel 82567V-2 Gigabit Network Connection                                  | 2        | 1.02%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1        | 0.51%   |
| Trendchip Ethernet controller                                              | 1        | 0.51%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1        | 0.51%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.51%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.51%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 0.51%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 1        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 1        | 0.51%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 1        | 0.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1        | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.51%   |
| Nvidia MCP77 Ethernet                                                      | 1        | 0.51%   |
| National DP83815 (MacPhyter) Ethernet Controller                           | 1        | 0.51%   |
| Motorola PCS motorola edge 20 lite                                         | 1        | 0.51%   |
| Motorola BCS SurfBoard SB5100 Cable Modem                                  | 1        | 0.51%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                    | 1        | 0.51%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 1        | 0.51%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                     | 1        | 0.51%   |
| Intel NM10/ICH7 Family LAN Controller                                      | 1        | 0.51%   |
| Intel Ethernet Controller I225-V                                           | 1        | 0.51%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                         | 1        | 0.51%   |
| Intel 82579V Gigabit Network Connection                                    | 1        | 0.51%   |
| Intel 82567V-4 Gigabit Network Connection                                  | 1        | 0.51%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 1        | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 174      | 65.66%  |
| WiFi     | 90       | 33.96%  |
| Modem    | 1        | 0.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 127      | 69.02%  |
| WiFi     | 57       | 30.98%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 114      | 63.33%  |
| 2     | 61       | 33.89%  |
| 3     | 3        | 1.67%   |
| 33    | 1        | 0.56%   |
| 0     | 1        | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 177      | 99.44%  |
| Yes  | 1        | 0.56%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 8        | 42.11%  |
| Intel                   | 4        | 21.05%  |
| Broadcom                | 3        | 15.79%  |
| IMC Networks            | 2        | 10.53%  |
| ASUSTek Computer        | 2        | 10.53%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8        | 42.11%  |
| Intel AX201 Bluetooth                               | 2        | 10.53%  |
| IMC Networks Bluetooth Module                       | 2        | 10.53%  |
| Intel Bluetooth wireless interface                  | 1        | 5.26%   |
| Intel AX200 Bluetooth                               | 1        | 5.26%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 UHE Dongle | 1        | 5.26%   |
| Broadcom BCM2070 Bluetooth Device                   | 1        | 5.26%   |
| Broadcom BCM2035B3 Bluetooth Adapter                | 1        | 5.26%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 5.26%   |
| ASUS Bluetooth Adapter                              | 1        | 5.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 134      | 54.92%  |
| AMD                    | 41       | 16.8%   |
| Nvidia                 | 40       | 16.39%  |
| C-Media Electronics    | 6        | 2.46%   |
| VIA Technologies       | 5        | 2.05%   |
| Creative Labs          | 5        | 2.05%   |
| JMTek                  | 3        | 1.23%   |
| Generalplus Technology | 3        | 1.23%   |
| Logitech               | 2        | 0.82%   |
| Unknown                | 1        | 0.41%   |
| Microsoft              | 1        | 0.41%   |
| Megawin Technology     | 1        | 0.41%   |
| Giga-Byte Technology   | 1        | 0.41%   |
| Aureal Semiconductor   | 1        | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 48       | 17.91%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 39       | 14.55%  |
| Nvidia MCP61 High Definition Audio                                                | 14       | 5.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 10       | 3.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 9        | 3.36%   |
| Nvidia GF119 HDMI Audio Controller                                                | 8        | 2.99%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 8        | 2.99%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 7        | 2.61%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 7        | 2.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 6        | 2.24%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 6        | 2.24%   |
| Nvidia High Definition Audio Controller                                           | 5        | 1.87%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 5        | 1.87%   |
| AMD FCH Azalia Controller                                                         | 5        | 1.87%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 4        | 1.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 4        | 1.49%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                    | 3        | 1.12%   |
| Nvidia GF106 High Definition Audio Controller                                     | 3        | 1.12%   |
| Generalplus Technology USB Audio Device                                           | 3        | 1.12%   |
| AMD Family 17h/19h HD Audio Controller                                            | 3        | 1.12%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 1.12%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller       | 2        | 0.75%   |
| Nvidia GF116 High Definition Audio Controller                                     | 2        | 0.75%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 0.75%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2        | 0.75%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2        | 0.75%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 2        | 0.75%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                              | 2        | 0.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2        | 0.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2        | 0.75%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 2        | 0.75%   |
| C-Media Electronics CM108 Audio Controller                                        | 2        | 0.75%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2        | 0.75%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 0.75%   |
| AMD RV670/680 HDMI Audio [Radeon HD 3690/3800 Series]                             | 2        | 0.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 0.75%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2        | 0.75%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]               | 2        | 0.75%   |
| Unknown Audio device                                                              | 1        | 0.37%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 1        | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 48       | 33.1%   |
| Kingston                   | 16       | 11.03%  |
| Samsung Electronics        | 15       | 10.34%  |
| SK hynix                   | 11       | 7.59%   |
| Ramaxel Technology         | 10       | 6.9%    |
| Corsair                    | 9        | 6.21%   |
| Crucial                    | 8        | 5.52%   |
| Micron Technology          | 6        | 4.14%   |
| Team                       | 3        | 2.07%   |
| Nanya Technology           | 3        | 2.07%   |
| Elpida                     | 2        | 1.38%   |
| Avant                      | 2        | 1.38%   |
| A-DATA Technology          | 2        | 1.38%   |
| Unknown                    | 2        | 1.38%   |
| Unknown (FFFF000000000000) | 1        | 0.69%   |
| Unknown (7F7F7F7F7F7F7F83) | 1        | 0.69%   |
| Unknown (0x0CBA)           | 1        | 0.69%   |
| Super Talent               | 1        | 0.69%   |
| Qimonda                    | 1        | 0.69%   |
| PNY                        | 1        | 0.69%   |
| OCZ                        | 1        | 0.69%   |
| Kreton                     | 1        | 0.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                     | 6        | 3.66%   |
| Unknown RAM Module 4GB DIMM SDRAM                     | 4        | 2.44%   |
| Unknown RAM Module 4GB DIMM 400MT/s                   | 4        | 2.44%   |
| Unknown RAM Module 2GB DIMM DDR2                      | 3        | 1.83%   |
| Unknown RAM Module 2048MB DIMM DDR2                   | 3        | 1.83%   |
| Unknown RAM Module 1024MB DIMM DDR2                   | 3        | 1.83%   |
| Ramaxel RAM RMR5030ED58E8W1600 2GB DIMM DDR3 1600MT/s | 3        | 1.83%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s             | 2        | 1.22%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                  | 2        | 1.22%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s             | 2        | 1.22%   |
| Unknown RAM Module 2GB DIMM 400MT/s                   | 2        | 1.22%   |
| Unknown RAM Module 2048MB DIMM SDRAM                  | 2        | 1.22%   |
| Unknown RAM Module 1024MB DIMM SDRAM                  | 2        | 1.22%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s           | 2        | 1.22%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s             | 2        | 1.22%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s   | 2        | 1.22%   |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3 1600MT/s   | 2        | 1.22%   |
| Ramaxel RAM RMR5030ME68F9F1600 4GB DIMM DDR3 1600MT/s | 2        | 1.22%   |
| Ramaxel RAM RMR1870EC58E9F1333 4GB DIMM DDR3 1333MT/s | 2        | 1.22%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s    | 2        | 1.22%   |
| Unknown                                               | 2        | 1.22%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                  | 1        | 0.61%   |
| Unknown RAM Module 512MB DIMM DDR2                    | 1        | 0.61%   |
| Unknown RAM Module 4GB DIMM 667MT/s                   | 1        | 0.61%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 1        | 0.61%   |
| Unknown RAM Module 4096MB DIMM SDRAM                  | 1        | 0.61%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s          | 1        | 0.61%   |
| Unknown RAM Module 4096MB DIMM                        | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s              | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s               | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM 800MT/s                   | 1        | 0.61%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s          | 1        | 0.61%   |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s          | 1        | 0.61%   |
| Unknown RAM Module 2048MB DIMM DDR2 533MT/s           | 1        | 0.61%   |
| Unknown RAM Module 2048MB DIMM DDR2 1639MT/s          | 1        | 0.61%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s            | 1        | 0.61%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s            | 1        | 0.61%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s               | 1        | 0.61%   |
| Unknown RAM Module 1GB DIMM DDR 133MT/s               | 1        | 0.61%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s            | 1        | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 46       | 39.66%  |
| DDR2    | 24       | 20.69%  |
| SDRAM   | 19       | 16.38%  |
| Unknown | 14       | 12.07%  |
| DDR4    | 8        | 6.9%    |
| DDR     | 5        | 4.31%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 108      | 96.43%  |
| SODIMM | 4        | 3.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 51       | 38.35%  |
| 4096  | 43       | 32.33%  |
| 1024  | 17       | 12.78%  |
| 8192  | 16       | 12.03%  |
| 32768 | 2        | 1.5%    |
| 16384 | 2        | 1.5%    |
| 512   | 2        | 1.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 26       | 20%     |
| 1333    | 23       | 17.69%  |
| Unknown | 22       | 16.92%  |
| 800     | 8        | 6.15%   |
| 667     | 8        | 6.15%   |
| 400     | 6        | 4.62%   |
| 1066    | 5        | 3.85%   |
| 533     | 4        | 3.08%   |
| 2133    | 3        | 2.31%   |
| 1639    | 3        | 2.31%   |
| 133     | 3        | 2.31%   |
| 3733    | 2        | 1.54%   |
| 3600    | 2        | 1.54%   |
| 3200    | 2        | 1.54%   |
| 2048    | 2        | 1.54%   |
| 1867    | 2        | 1.54%   |
| 1800    | 2        | 1.54%   |
| 3800    | 1        | 0.77%   |
| 2667    | 1        | 0.77%   |
| 2400    | 1        | 0.77%   |
| 2000    | 1        | 0.77%   |
| 1067    | 1        | 0.77%   |
| 1024    | 1        | 0.77%   |
| 266     | 1        | 0.77%   |

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
| Logitech                    | 5        | 20.83%  |
| Microsoft                   | 4        | 16.67%  |
| Samsung Electronics         | 3        | 12.5%   |
| KYE Systems (Mouse Systems) | 2        | 8.33%   |
| IMC Networks                | 2        | 8.33%   |
| Cubeternet                  | 2        | 8.33%   |
| Suyin                       | 1        | 4.17%   |
| SiGma Micro                 | 1        | 4.17%   |
| Realtek Semiconductor       | 1        | 4.17%   |
| LG Electronics              | 1        | 4.17%   |
| Chicony Electronics         | 1        | 4.17%   |
| Aveo Technology             | 1        | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode)               | 3        | 12.5%   |
| Logitech Webcam C270                                  | 3        | 12.5%   |
| Cubeternet USB2.0 Camera                              | 2        | 8.33%   |
| Suyin HP Webcam                                       | 1        | 4.17%   |
| SiGma Micro WebCam SiGma Micro                        | 1        | 4.17%   |
| Realtek HP 1.0MP High Definition Webcam               | 1        | 4.17%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks   | 1        | 4.17%   |
| Microsoft LifeCam VX-5000                             | 1        | 4.17%   |
| Microsoft LifeCam Studio                              | 1        | 4.17%   |
| Microsoft LifeCam HD-3000                             | 1        | 4.17%   |
| Logitech QuickCam Communicate MP/S5500                | 1        | 4.17%   |
| Logitech C922 Pro Stream Webcam                       | 1        | 4.17%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 4.17%   |
| KYE Systems (Mouse Systems) FaceCam 1320              | 1        | 4.17%   |
| KYE Systems (Mouse Systems) eFace 2025                | 1        | 4.17%   |
| IMC Networks USB2.0 UVC 1.3M WebCam                   | 1        | 4.17%   |
| IMC Networks USB 2.0 Camera                           | 1        | 4.17%   |
| Chicony HD Webcam                                     | 1        | 4.17%   |
| Aveo USB2.0 Camera                                    | 1        | 4.17%   |

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
| 0     | 143      | 80.79%  |
| 1     | 32       | 18.08%  |
| 2     | 2        | 1.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 16       | 45.71%  |
| Communication controller | 10       | 28.57%  |
| Sound                    | 3        | 8.57%   |
| Net/wireless             | 3        | 8.57%   |
| Storage/ide              | 1        | 2.86%   |
| Multimedia controller    | 1        | 2.86%   |
| Camera                   | 1        | 2.86%   |


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

Total: 235

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 13       | 7.39%   |
| Debian 11          | 13       | 7.39%   |
| Ubuntu 18.04       | 10       | 5.68%   |
| OpenMandriva 4.3   | 10       | 5.68%   |
| OpenMandriva 23.03 | 8        | 4.55%   |
| Ubuntu 22.04       | 7        | 3.98%   |
| OpenMandriva 4.2   | 7        | 3.98%   |
| Zorin 16           | 6        | 3.41%   |
| Linux Mint 21.1    | 5        | 2.84%   |
| Linux Mint 20.3    | 5        | 2.84%   |
| Xubuntu 18.04      | 4        | 2.27%   |
| ROSA R11           | 4        | 2.27%   |
| OpenMandriva 23.01 | 4        | 2.27%   |
| Linux Mint 20.1    | 3        | 1.7%    |
| Linux Mint 20      | 3        | 1.7%    |
| Linux Mint 19.3    | 3        | 1.7%    |
| KDE neon 20.04     | 3        | 1.7%    |
| Debian 10          | 3        | 1.7%    |
| Arch Rolling       | 3        | 1.7%    |
| Zorin 15           | 2        | 1.14%   |
| Xubuntu 16.04      | 2        | 1.14%   |
| Ubuntu 20.10       | 2        | 1.14%   |
| ROSA R9            | 2        | 1.14%   |
| OpenMandriva 4.50  | 2        | 1.14%   |
| MX 21              | 2        | 1.14%   |
| Kubuntu 20.04      | 2        | 1.14%   |
| Fedora 38          | 2        | 1.14%   |
| ArcoLinux Rolling  | 2        | 1.14%   |
| Xubuntu 20.04      | 1        | 0.57%   |
| Xero Rolling       | 1        | 0.57%   |
| Ubuntu Unity 18.04 | 1        | 0.57%   |
| Ubuntu MATE 19.10  | 1        | 0.57%   |
| Ubuntu 22.10       | 1        | 0.57%   |
| Ubuntu 21.10       | 1        | 0.57%   |
| Ubuntu 19.10       | 1        | 0.57%   |
| Ubuntu 19.04       | 1        | 0.57%   |
| Sparky 5.12        | 1        | 0.57%   |
| Solus 4.3          | 1        | 0.57%   |
| ROSA R8            | 1        | 0.57%   |
| ROSA R11.1         | 1        | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 35       | 20.35%  |
| OpenMandriva | 30       | 17.44%  |
| Linux Mint   | 22       | 12.79%  |
| Debian       | 19       | 11.05%  |
| ROSA         | 11       | 6.4%    |
| Zorin        | 8        | 4.65%   |
| Xubuntu      | 6        | 3.49%   |
| Fedora       | 5        | 2.91%   |
| KDE neon     | 4        | 2.33%   |
| Arch         | 4        | 2.33%   |
| Kubuntu      | 3        | 1.74%   |
| Elementary   | 3        | 1.74%   |
| Nobara       | 2        | 1.16%   |
| MX           | 2        | 1.16%   |
| Manjaro      | 2        | 1.16%   |
| ArcoLinux    | 2        | 1.16%   |
| Xero         | 1        | 0.58%   |
| Ubuntu Unity | 1        | 0.58%   |
| Ubuntu MATE  | 1        | 0.58%   |
| Sparky       | 1        | 0.58%   |
| Solus        | 1        | 0.58%   |
| Q4OS         | 1        | 0.58%   |
| Pop!_OS      | 1        | 0.58%   |
| PCLinuxOS    | 1        | 0.58%   |
| Lubuntu      | 1        | 0.58%   |
| LMDE         | 1        | 0.58%   |
| Kali         | 1        | 0.58%   |
| Garuda Linux | 1        | 0.58%   |
| Feren OS     | 1        | 0.58%   |
| Endless      | 1        | 0.58%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                           | Desktops | Percent |
|-----------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003           | 10       | 5.32%   |
| 6.2.6-desktop-1omv2390            | 8        | 4.26%   |
| 5.10.14-desktop-1omv4002          | 7        | 3.72%   |
| 6.1.1-desktop-1omv2290            | 4        | 2.13%   |
| 5.4.0-42-generic                  | 4        | 2.13%   |
| 5.8.0-55-generic                  | 2        | 1.06%   |
| 5.4.0-77-generic                  | 2        | 1.06%   |
| 5.4.0-74-generic                  | 2        | 1.06%   |
| 5.4.0-54-generic                  | 2        | 1.06%   |
| 5.4.0-26-generic                  | 2        | 1.06%   |
| 5.3.0-40-generic                  | 2        | 1.06%   |
| 5.19.0-41-generic                 | 2        | 1.06%   |
| 5.19.0-35-generic                 | 2        | 1.06%   |
| 5.15.0-76-generic                 | 2        | 1.06%   |
| 5.15.0-71-generic                 | 2        | 1.06%   |
| 5.15.0-67-generic                 | 2        | 1.06%   |
| 5.15.0-58-generic                 | 2        | 1.06%   |
| 5.15.0-56-generic                 | 2        | 1.06%   |
| 5.15.0-53-generic                 | 2        | 1.06%   |
| 5.15.0-46-generic                 | 2        | 1.06%   |
| 5.13.0-27-generic                 | 2        | 1.06%   |
| 5.10.0-8-amd64                    | 2        | 1.06%   |
| 5.10.0-16-amd64                   | 2        | 1.06%   |
| 5.10.0-14-amd64                   | 2        | 1.06%   |
| 5.10.0-11-amd64                   | 2        | 1.06%   |
| 4.15.0-desktop-45.1rosa-x86_64    | 2        | 1.06%   |
| 4.15.0-48-generic                 | 2        | 1.06%   |
| 4.15.0-112-generic                | 2        | 1.06%   |
| 6.4.6-arch1-1                     | 1        | 0.53%   |
| 6.4.6-200.fc38.x86_64             | 1        | 0.53%   |
| 6.4.3-x64v3-xanmod1               | 1        | 0.53%   |
| 6.4.3-arch1-2                     | 1        | 0.53%   |
| 6.3.8-200.fc38.x86_64             | 1        | 0.53%   |
| 6.2.12-zen1-1-zen                 | 1        | 0.53%   |
| 6.2.12-200.fsync.fc37.x86_64      | 1        | 0.53%   |
| 6.2.0-26-generic                  | 1        | 0.53%   |
| 6.1.20-generic-2rosa2021.1-x86_64 | 1        | 0.53%   |
| 6.0.5-201.fsync.fc36.x86_64       | 1        | 0.53%   |
| 6.0.0-2-amd64                     | 1        | 0.53%   |
| 5.9.16-1-MANJARO                  | 1        | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 27       | 15.25%  |
| 4.15.0  | 19       | 10.73%  |
| 5.15.0  | 18       | 10.17%  |
| 5.10.0  | 16       | 9.04%   |
| 5.16.7  | 10       | 5.65%   |
| 6.2.6   | 8        | 4.52%   |
| 5.10.14 | 7        | 3.95%   |
| 5.8.0   | 6        | 3.39%   |
| 5.13.0  | 6        | 3.39%   |
| 5.3.0   | 5        | 2.82%   |
| 5.19.0  | 5        | 2.82%   |
| 6.1.1   | 4        | 2.26%   |
| 5.11.0  | 3        | 1.69%   |
| 5.0.0   | 3        | 1.69%   |
| 4.19.0  | 3        | 1.69%   |
| 6.4.6   | 2        | 1.13%   |
| 6.4.3   | 2        | 1.13%   |
| 6.2.12  | 2        | 1.13%   |
| 4.9.20  | 2        | 1.13%   |
| 4.9.0   | 2        | 1.13%   |
| 6.3.8   | 1        | 0.56%   |
| 6.2.0   | 1        | 0.56%   |
| 6.1.20  | 1        | 0.56%   |
| 6.0.5   | 1        | 0.56%   |
| 6.0.0   | 1        | 0.56%   |
| 5.9.16  | 1        | 0.56%   |
| 5.8.11  | 1        | 0.56%   |
| 5.8.10  | 1        | 0.56%   |
| 5.6.0   | 1        | 0.56%   |
| 5.19.9  | 1        | 0.56%   |
| 5.19.5  | 1        | 0.56%   |
| 5.18.7  | 1        | 0.56%   |
| 5.16.14 | 1        | 0.56%   |
| 5.15.6  | 1        | 0.56%   |
| 5.15.57 | 1        | 0.56%   |
| 5.15.48 | 1        | 0.56%   |
| 5.14.10 | 1        | 0.56%   |
| 5.13.16 | 1        | 0.56%   |
| 5.13.1  | 1        | 0.56%   |
| 5.12.4  | 1        | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 27       | 15.43%  |
| 5.10    | 26       | 14.86%  |
| 5.15    | 20       | 11.43%  |
| 4.15    | 19       | 10.86%  |
| 6.2     | 11       | 6.29%   |
| 5.16    | 11       | 6.29%   |
| 5.8     | 8        | 4.57%   |
| 5.13    | 8        | 4.57%   |
| 5.19    | 7        | 4%      |
| 5.3     | 5        | 2.86%   |
| 6.4     | 4        | 2.29%   |
| 6.1     | 4        | 2.29%   |
| 4.9     | 4        | 2.29%   |
| 5.11    | 3        | 1.71%   |
| 5.0     | 3        | 1.71%   |
| 4.19    | 3        | 1.71%   |
| 6.0     | 2        | 1.14%   |
| 6.3     | 1        | 0.57%   |
| 5.9     | 1        | 0.57%   |
| 5.6     | 1        | 0.57%   |
| 5.18    | 1        | 0.57%   |
| 5.14    | 1        | 0.57%   |
| 5.12    | 1        | 0.57%   |
| 4.4     | 1        | 0.57%   |
| 4.18    | 1        | 0.57%   |
| 4.13    | 1        | 0.57%   |
| 4.1     | 1        | 0.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 151      | 89.88%  |
| i686   | 17       | 10.12%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 51       | 29.14%  |
| KDE5            | 46       | 26.29%  |
| XFCE            | 18       | 10.29%  |
| Unknown         | 15       | 8.57%   |
| X-Cinnamon      | 12       | 6.86%   |
| MATE            | 6        | 3.43%   |
| KDE             | 5        | 2.86%   |
| LXDE            | 4        | 2.29%   |
| KDE4            | 4        | 2.29%   |
| LXQt            | 3        | 1.71%   |
| Cinnamon        | 3        | 1.71%   |
| Pantheon        | 2        | 1.14%   |
| xmonad          | 1        | 0.57%   |
| Unity           | 1        | 0.57%   |
| Trinity         | 1        | 0.57%   |
| GNOME Flashback | 1        | 0.57%   |
| Budgie          | 1        | 0.57%   |
| awesome         | 1        | 0.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 143      | 83.63%  |
| Wayland | 23       | 13.45%  |
| Unknown | 4        | 2.34%   |
| Tty     | 1        | 0.58%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 70       | 40.94%  |
| SDDM    | 47       | 27.49%  |
| LightDM | 15       | 8.77%   |
| GDM     | 15       | 8.77%   |
| GDM3    | 11       | 6.43%   |
| TDM     | 7        | 4.09%   |
| KDM     | 4        | 2.34%   |
| SLiM    | 2        | 1.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_VE   | 99       | 58.24%  |
| en_US   | 35       | 20.59%  |
| Unknown | 17       | 10%     |
| es_ES   | 9        | 5.29%   |
| es_MX   | 4        | 2.35%   |
| es_US   | 2        | 1.18%   |
| C       | 2        | 1.18%   |
| es_CO   | 1        | 0.59%   |
| de_DE   | 1        | 0.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 141      | 84.94%  |
| EFI  | 25       | 15.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 122      | 71.35%  |
| Overlay | 26       | 15.2%   |
| Btrfs   | 11       | 6.43%   |
| Unknown | 5        | 2.92%   |
| Xfs     | 3        | 1.75%   |
| Tmpfs   | 3        | 1.75%   |
| Ext2    | 1        | 0.58%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 78       | 46.43%  |
| MBR     | 62       | 36.9%   |
| GPT     | 28       | 16.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 133      | 79.64%  |
| Yes       | 34       | 20.36%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 102      | 60.36%  |
| Yes       | 67       | 39.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASRock              | 31       | 18.67%  |
| ECS                 | 16       | 9.64%   |
| Intel               | 14       | 8.43%   |
| Gigabyte Technology | 14       | 8.43%   |
| Hewlett-Packard     | 13       | 7.83%   |
| Pegatron            | 12       | 7.23%   |
| Lenovo              | 11       | 6.63%   |
| Dell                | 11       | 6.63%   |
| ASUSTek Computer    | 11       | 6.63%   |
| Biostar             | 10       | 6.02%   |
| Foxconn             | 7        | 4.22%   |
| MSI                 | 5        | 3.01%   |
| langchao            | 5        | 3.01%   |
| Soncview            | 1        | 0.6%    |
| SIRAGON             | 1        | 0.6%    |
| IP3 Tech            | 1        | 0.6%    |
| Inspur              | 1        | 0.6%    |
| IBM                 | 1        | 0.6%    |
| Unknown             | 1        | 0.6%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ECS H61H2-CM                         | 9        | 5.42%   |
| ASRock G41M-VS3                      | 7        | 4.22%   |
| langchao 12345                       | 5        | 3.01%   |
| ASRock N68-VS3 UCC                   | 4        | 2.41%   |
| Pegatron Compaq dx2400 Microtower    | 3        | 1.81%   |
| HP Compaq 8200 Elite SFF PC          | 3        | 1.81%   |
| ASRock N68C-S UCC                    | 3        | 1.81%   |
| Intel H61                            | 2        | 1.2%    |
| Gigabyte 970A-DS3P                   | 2        | 1.2%    |
| ECS G31T-M7                          | 2        | 1.2%    |
| Dell OptiPlex 9020                   | 2        | 1.2%    |
| Dell OptiPlex 790                    | 2        | 1.2%    |
| Biostar G41D3                        | 2        | 1.2%    |
| ASRock 945GCM-S                      | 2        | 1.2%    |
| Soncview G41D3C                      | 1        | 0.6%    |
| SIRAGON AIO-5150                     | 1        | 0.6%    |
| Pegatron PEGATRON                    | 1        | 0.6%    |
| Pegatron IPPEL-DB                    | 1        | 0.6%    |
| Pegatron IPMIP-H55-INSPUR            | 1        | 0.6%    |
| Pegatron IPM41-D3                    | 1        | 0.6%    |
| Pegatron CQ1507LA                    | 1        | 0.6%    |
| Pegatron Compaq dx2400 Microtower PC | 1        | 0.6%    |
| Pegatron BM411AA-ABA CQ5600F         | 1        | 0.6%    |
| Pegatron 20-b010                     | 1        | 0.6%    |
| Pegatron 100-5010la                  | 1        | 0.6%    |
| MSI Pro 3000 Microtower PC           | 1        | 0.6%    |
| MSI MS-7A38                          | 1        | 0.6%    |
| MSI MS-7817                          | 1        | 0.6%    |
| MSI MS-7721                          | 1        | 0.6%    |
| MSI MS-7375                          | 1        | 0.6%    |
| Lenovo ThinkCentre XXXX 8705A84      | 1        | 0.6%    |
| Lenovo ThinkCentre M91 7516AD1       | 1        | 0.6%    |
| Lenovo ThinkCentre M71e 3157G6S      | 1        | 0.6%    |
| Lenovo ThinkCentre M55E 9645BN2      | 1        | 0.6%    |
| Lenovo ThinkCentre M55E 9632BU8      | 1        | 0.6%    |
| Lenovo ThinkCentre A58 7515A33       | 1        | 0.6%    |
| Lenovo ThinkCentre A57 9702AB7       | 1        | 0.6%    |
| Lenovo ThinkCentre A55 8705AV4       | 1        | 0.6%    |
| Lenovo H220 10028                    | 1        | 0.6%    |
| Lenovo 70A4000HUX ThinkServer TS140  | 1        | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| HP Compaq                 | 9        | 5.42%   |
| ECS H61H2-CM              | 9        | 5.42%   |
| Lenovo ThinkCentre        | 8        | 4.82%   |
| Dell OptiPlex             | 7        | 4.22%   |
| ASRock G41M-VS3           | 7        | 4.22%   |
| langchao 12345            | 5        | 3.01%   |
| ASRock N68-VS3            | 5        | 3.01%   |
| Pegatron Compaq           | 4        | 2.41%   |
| ASRock N68C-S             | 3        | 1.81%   |
| Intel H61                 | 2        | 1.2%    |
| HP EliteDesk              | 2        | 1.2%    |
| Gigabyte 970A-DS3P        | 2        | 1.2%    |
| ECS G31T-M7               | 2        | 1.2%    |
| Dell Vostro               | 2        | 1.2%    |
| Biostar G41D3             | 2        | 1.2%    |
| ASUS P8H61-M              | 2        | 1.2%    |
| ASUS P5G41T-M             | 2        | 1.2%    |
| ASRock H61M-DGS           | 2        | 1.2%    |
| ASRock 945GCM-S           | 2        | 1.2%    |
| Soncview G41D3C           | 1        | 0.6%    |
| SIRAGON AIO-5150          | 1        | 0.6%    |
| Pegatron PEGATRON         | 1        | 0.6%    |
| Pegatron IPPEL-DB         | 1        | 0.6%    |
| Pegatron IPMIP-H55-INSPUR | 1        | 0.6%    |
| Pegatron IPM41-D3         | 1        | 0.6%    |
| Pegatron CQ1507LA         | 1        | 0.6%    |
| Pegatron BM411AA-ABA      | 1        | 0.6%    |
| Pegatron 20-b010          | 1        | 0.6%    |
| Pegatron 100-5010la       | 1        | 0.6%    |
| MSI Pro                   | 1        | 0.6%    |
| MSI MS-7A38               | 1        | 0.6%    |
| MSI MS-7817               | 1        | 0.6%    |
| MSI MS-7721               | 1        | 0.6%    |
| MSI MS-7375               | 1        | 0.6%    |
| Lenovo H220               | 1        | 0.6%    |
| Lenovo 70A4000HUX         | 1        | 0.6%    |
| Lenovo 11051CS            | 1        | 0.6%    |
| IP3 Tech TB20             | 1        | 0.6%    |
| Intel MAHOBAY             | 1        | 0.6%    |
| Intel H55AD17             | 1        | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 41       | 24.7%   |
| 2010 | 34       | 20.48%  |
| 2008 | 19       | 11.45%  |
| 2012 | 17       | 10.24%  |
| 2007 | 12       | 7.23%   |
| 2013 | 9        | 5.42%   |
| 2006 | 7        | 4.22%   |
| 2014 | 6        | 3.61%   |
| 2021 | 4        | 2.41%   |
| 2020 | 4        | 2.41%   |
| 2017 | 4        | 2.41%   |
| 2009 | 3        | 1.81%   |
| 2019 | 2        | 1.2%    |
| 2016 | 1        | 0.6%    |
| 2015 | 1        | 0.6%    |
| 2005 | 1        | 0.6%    |
| 2002 | 1        | 0.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 166      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 166      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 166      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 52       | 30.41%  |
| 4.01-8.0    | 37       | 21.64%  |
| 8.01-16.0   | 26       | 15.2%   |
| 1.01-2.0    | 23       | 13.45%  |
| 16.01-24.0  | 16       | 9.36%   |
| 2.01-3.0    | 6        | 3.51%   |
| 32.01-64.0  | 4        | 2.34%   |
| 24.01-32.0  | 3        | 1.75%   |
| 64.01-256.0 | 2        | 1.17%   |
| 0.51-1.0    | 2        | 1.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 74       | 40.88%  |
| 2.01-3.0 | 46       | 25.41%  |
| 0.51-1.0 | 25       | 13.81%  |
| 3.01-4.0 | 17       | 9.39%   |
| 4.01-8.0 | 15       | 8.29%   |
| 0.01-0.5 | 4        | 2.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 95       | 55.23%  |
| 2      | 58       | 33.72%  |
| 3      | 14       | 8.14%   |
| 4      | 5        | 2.91%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 100      | 58.48%  |
| Yes       | 71       | 41.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 163      | 98.19%  |
| No        | 3        | 1.81%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 85       | 50.3%   |
| Yes       | 84       | 49.7%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 149      | 89.22%  |
| Yes       | 18       | 10.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Venezuela | 166      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Caracas                  | 76       | 42.94%  |
| Valencia                 | 9        | 5.08%   |
| Maracay                  | 9        | 5.08%   |
| Maracaibo                | 9        | 5.08%   |
| Barquisimeto             | 7        | 3.95%   |
| San Cristóbal           | 5        | 2.82%   |
| San Carlos del Zulia     | 5        | 2.82%   |
| Maturín                 | 5        | 2.82%   |
| Barcelona                | 5        | 2.82%   |
| Ciudad Guayana           | 4        | 2.26%   |
| Mérida                  | 3        | 1.69%   |
| Ciudad Bolívar          | 3        | 1.69%   |
| Carrizal                 | 3        | 1.69%   |
| Vigia                    | 2        | 1.13%   |
| San Antonio de Los Altos | 2        | 1.13%   |
| Porlamar                 | 2        | 1.13%   |
| Los Teques               | 2        | 1.13%   |
| Barinas                  | 2        | 1.13%   |
| Acarigua                 | 2        | 1.13%   |
| Valle de La Pascua       | 1        | 0.56%   |
| Tucupita                 | 1        | 0.56%   |
| San Juan Bautista        | 1        | 0.56%   |
| San Francisco            | 1        | 0.56%   |
| Petare                   | 1        | 0.56%   |
| Parroquia El Recreo      | 1        | 0.56%   |
| Mene Grande              | 1        | 0.56%   |
| Los Palos Grandes        | 1        | 0.56%   |
| Lecherias                | 1        | 0.56%   |
| Las Vegas                | 1        | 0.56%   |
| La Guaira                | 1        | 0.56%   |
| Guatire                  | 1        | 0.56%   |
| Guarenas                 | 1        | 0.56%   |
| Distrito Federal         | 1        | 0.56%   |
| Cua                      | 1        | 0.56%   |
| Ciudad Ojeda             | 1        | 0.56%   |
| Carora                   | 1        | 0.56%   |
| Cambural                 | 1        | 0.56%   |
| Cabimas                  | 1        | 0.56%   |
| Baruta                   | 1        | 0.56%   |
| Araure                   | 1        | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 71       | 100    | 29.71%  |
| Seagate             | 59       | 81     | 24.69%  |
| Hitachi             | 30       | 37     | 12.55%  |
| Samsung Electronics | 22       | 26     | 9.21%   |
| Toshiba             | 14       | 15     | 5.86%   |
| Kingston            | 11       | 13     | 4.6%    |
| Maxtor              | 6        | 6      | 2.51%   |
| PNY                 | 3        | 4      | 1.26%   |
| Team                | 2        | 2      | 0.84%   |
| SanDisk             | 2        | 3      | 0.84%   |
| Patriot             | 2        | 2      | 0.84%   |
| HGST                | 2        | 2      | 0.84%   |
| Fujitsu             | 2        | 2      | 0.84%   |
| Unknown             | 1        | 1      | 0.42%   |
| SPCC                | 1        | 1      | 0.42%   |
| SK hynix            | 1        | 1      | 0.42%   |
| Phison Electronics  | 1        | 1      | 0.42%   |
| Netac               | 1        | 1      | 0.42%   |
| JMicron Technology  | 1        | 1      | 0.42%   |
| IBM/Hitachi         | 1        | 2      | 0.42%   |
| HPE                 | 1        | 2      | 0.42%   |
| ExcelStor           | 1        | 1      | 0.42%   |
| Dogfish             | 1        | 1      | 0.42%   |
| Crucial             | 1        | 1      | 0.42%   |
| addlink             | 1        | 1      | 0.42%   |
| A-DATA Technology   | 1        | 1      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST320LT012-1DG14C 320GB     | 11       | 4.07%   |
| Toshiba DT01ACA050 500GB            | 8        | 2.96%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 7        | 2.59%   |
| Seagate ST500DM002-1BD142 500GB     | 6        | 2.22%   |
| Samsung HD502HJ 500GB               | 5        | 1.85%   |
| Kingston SA400S37240G 240GB SSD     | 5        | 1.85%   |
| WDC WD3200AAJS-08L7A0 320GB         | 4        | 1.48%   |
| WDC WD3200AAJS-00L7A0 320GB         | 4        | 1.48%   |
| Seagate ST3320418AS 320GB           | 4        | 1.48%   |
| Seagate ST320LM000 HM321HI 320GB    | 4        | 1.48%   |
| Samsung HD161HJ 160GB               | 4        | 1.48%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 3        | 1.11%   |
| WDC WD5000AAKX-221CA1 500GB         | 3        | 1.11%   |
| WDC WD5000AAKX-001CA0 500GB         | 3        | 1.11%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 3        | 1.11%   |
| WDC WD5000AAKS-00A7B0 500GB         | 3        | 1.11%   |
| Seagate ST4000DM000-1F2168 4TB      | 3        | 1.11%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 3        | 1.11%   |
| Samsung HD161GJ 160GB               | 3        | 1.11%   |
| Kingston SA400S37120G 120GB SSD     | 3        | 1.11%   |
| Hitachi HTS542580K9SA00 80GB        | 3        | 1.11%   |
| Hitachi HDS728080PLA380 82GB        | 3        | 1.11%   |
| WDC WD800BD-22MRA1 80GB             | 2        | 0.74%   |
| WDC WD800BB-22JHC0 80GB             | 2        | 0.74%   |
| WDC WD5000AAKX-753CA1 500GB         | 2        | 0.74%   |
| WDC WD2500AAJS-60B4A0 250GB         | 2        | 0.74%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 2        | 0.74%   |
| WDC WD1600AABS-00PRA0 160GB         | 2        | 0.74%   |
| Seagate ST500DM005 HD502HJ 500GB    | 2        | 0.74%   |
| Seagate ST500DM002-1BC142 500GB     | 2        | 0.74%   |
| Seagate ST3500413AS 500GB           | 2        | 0.74%   |
| Seagate ST3250310AS 250GB           | 2        | 0.74%   |
| Seagate ST2000DM001-1CH164 2TB      | 2        | 0.74%   |
| Maxtor STM3160215AS 160GB           | 2        | 0.74%   |
| Hitachi HTS545032B9A300 320GB       | 2        | 0.74%   |
| Hitachi HDS721616PLA380 160GB       | 2        | 0.74%   |
| Hitachi HDS721050CLA662 500GB       | 2        | 0.74%   |
| Hitachi HDS721032CLA362 320GB       | 2        | 0.74%   |
| Hitachi HDS5C1050CLA382 500GB       | 2        | 0.74%   |
| WDC WD800JD-60LSA5 80GB             | 1        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 71       | 100    | 34.3%   |
| Seagate             | 59       | 81     | 28.5%   |
| Hitachi             | 30       | 37     | 14.49%  |
| Samsung Electronics | 19       | 22     | 9.18%   |
| Toshiba             | 14       | 15     | 6.76%   |
| Maxtor              | 6        | 6      | 2.9%    |
| HGST                | 2        | 2      | 0.97%   |
| Fujitsu             | 2        | 2      | 0.97%   |
| JMicron Technology  | 1        | 1      | 0.48%   |
| IBM/Hitachi         | 1        | 2      | 0.48%   |
| HPE                 | 1        | 1      | 0.48%   |
| ExcelStor           | 1        | 1      | 0.48%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 11       | 13     | 40.74%  |
| PNY                 | 3        | 4      | 11.11%  |
| Team                | 2        | 2      | 7.41%   |
| Samsung Electronics | 2        | 3      | 7.41%   |
| Patriot             | 2        | 2      | 7.41%   |
| SPCC                | 1        | 1      | 3.7%    |
| SanDisk             | 1        | 1      | 3.7%    |
| Netac               | 1        | 1      | 3.7%    |
| Dogfish             | 1        | 1      | 3.7%    |
| Crucial             | 1        | 1      | 3.7%    |
| addlink             | 1        | 1      | 3.7%    |
| A-DATA Technology   | 1        | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 150      | 270    | 82.42%  |
| SSD     | 25       | 31     | 13.74%  |
| NVMe    | 6        | 6      | 3.3%    |
| Unknown | 1        | 1      | 0.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 163      | 301    | 95.88%  |
| NVMe | 6        | 6      | 3.53%   |
| SAS  | 1        | 1      | 0.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 151      | 250    | 78.65%  |
| 0.51-1.0   | 25       | 29     | 13.02%  |
| 1.01-2.0   | 9        | 10     | 4.69%   |
| 3.01-4.0   | 4        | 8      | 2.08%   |
| 2.01-3.0   | 2        | 3      | 1.04%   |
| 4.01-10.0  | 1        | 1      | 0.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 60       | 33.52%  |
| 101-250        | 38       | 21.23%  |
| 1-20           | 21       | 11.73%  |
| 501-1000       | 21       | 11.73%  |
| 51-100         | 16       | 8.94%   |
| 1001-2000      | 8        | 4.47%   |
| 21-50          | 5        | 2.79%   |
| 2001-3000      | 4        | 2.23%   |
| Unknown        | 4        | 2.23%   |
| More than 3000 | 2        | 1.12%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 79       | 44.38%  |
| 21-50          | 31       | 17.42%  |
| 101-250        | 22       | 12.36%  |
| 251-500        | 16       | 8.99%   |
| 51-100         | 14       | 7.87%   |
| 501-1000       | 5        | 2.81%   |
| 1001-2000      | 4        | 2.25%   |
| Unknown        | 4        | 2.25%   |
| 2001-3000      | 2        | 1.12%   |
| More than 3000 | 1        | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST320LT012-1DG14C 320GB   | 6        | 7      | 8.22%   |
| WDC WD5000AAKX-22ERMA0 500GB      | 4        | 5      | 5.48%   |
| Toshiba DT01ACA050 500GB          | 3        | 4      | 4.11%   |
| WDC WD5000AAKX-221CA1 500GB       | 2        | 2      | 2.74%   |
| WDC WD5000AAKS-00A7B0 500GB       | 2        | 2      | 2.74%   |
| WDC WD3200AAJS-08L7A0 320GB       | 2        | 3      | 2.74%   |
| Seagate ST500DM002-1BD142 500GB   | 2        | 2      | 2.74%   |
| Samsung Electronics HD161GJ 160GB | 2        | 2      | 2.74%   |
| Maxtor STM3160215AS 160GB         | 2        | 2      | 2.74%   |
| Hitachi HDS728080PLA380 82GB      | 2        | 2      | 2.74%   |
| Hitachi HDS721616PLA380 160GB     | 2        | 2      | 2.74%   |
| WDC WD800BD-08MRA1 80GB           | 1        | 1      | 1.37%   |
| WDC WD800BB-22JHC0 80GB           | 1        | 1      | 1.37%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 1        | 1      | 1.37%   |
| WDC WD5000AAKX-08U6AA0 500GB      | 1        | 1      | 1.37%   |
| WDC WD5000AAKX-08ERMA0 500GB      | 1        | 2      | 1.37%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 1.37%   |
| WDC WD5000AACS-00ZUB0 500GB       | 1        | 1      | 1.37%   |
| WDC WD3200BEKT-22F3T0 320GB       | 1        | 1      | 1.37%   |
| WDC WD3200BEKT-08PVMT1 320GB      | 1        | 1      | 1.37%   |
| WDC WD2003FYPS-27Y2B0 2TB         | 1        | 1      | 1.37%   |
| WDC WD10EZEX-22RKKA0 1TB          | 1        | 1      | 1.37%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 1        | 1      | 1.37%   |
| Seagate ST500DM005 HD502HJ 500GB  | 1        | 1      | 1.37%   |
| Seagate ST3500630AS 500GB         | 1        | 1      | 1.37%   |
| Seagate ST3500418AS 500GB         | 1        | 1      | 1.37%   |
| Seagate ST3500413AS 500GB         | 1        | 1      | 1.37%   |
| Seagate ST3500312CS 500GB         | 1        | 1      | 1.37%   |
| Seagate ST340014AS 40GB           | 1        | 1      | 1.37%   |
| Seagate ST3320418AS 320GB         | 1        | 2      | 1.37%   |
| Seagate ST3250318AS 250GB         | 1        | 1      | 1.37%   |
| Seagate ST3250310AS 250GB         | 1        | 1      | 1.37%   |
| Seagate ST3160215ACE 160GB        | 1        | 1      | 1.37%   |
| Seagate ST3160212SCE 160GB        | 1        | 1      | 1.37%   |
| Seagate ST31000528AS 1TB          | 1        | 1      | 1.37%   |
| Seagate ST31000525SV 1TB          | 1        | 1      | 1.37%   |
| Seagate ST2000DM001-1CH164 2TB    | 1        | 1      | 1.37%   |
| Seagate ST1000DM003-9YN162 1TB    | 1        | 1      | 1.37%   |
| Samsung Electronics HM321HI 320GB | 1        | 1      | 1.37%   |
| Samsung Electronics HD161HJ 160GB | 1        | 2      | 1.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 22       | 25     | 33.33%  |
| WDC                 | 16       | 25     | 24.24%  |
| Hitachi             | 13       | 13     | 19.7%   |
| Samsung Electronics | 5        | 6      | 7.58%   |
| Toshiba             | 3        | 4      | 4.55%   |
| Maxtor              | 3        | 3      | 4.55%   |
| JMicron Technology  | 1        | 1      | 1.52%   |
| IBM/Hitachi         | 1        | 2      | 1.52%   |
| HGST                | 1        | 1      | 1.52%   |
| ExcelStor           | 1        | 1      | 1.52%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 22       | 25     | 33.33%  |
| WDC                 | 16       | 25     | 24.24%  |
| Hitachi             | 13       | 13     | 19.7%   |
| Samsung Electronics | 5        | 6      | 7.58%   |
| Toshiba             | 3        | 4      | 4.55%   |
| Maxtor              | 3        | 3      | 4.55%   |
| JMicron Technology  | 1        | 1      | 1.52%   |
| IBM/Hitachi         | 1        | 2      | 1.52%   |
| HGST                | 1        | 1      | 1.52%   |
| ExcelStor           | 1        | 1      | 1.52%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 52       | 81     | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Toshiba DT01ACA050 500GB  | 2        | 2      | 66.67%  |
| Seagate ST9320423AS 320GB | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 2        | 2      | 66.67%  |
| Seagate | 1        | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 87       | 162    | 47.03%  |
| Malfunc  | 52       | 81     | 28.11%  |
| Works    | 43       | 62     | 23.24%  |
| Failed   | 3        | 3      | 1.62%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 127      | 67.91%  |
| AMD                      | 19       | 10.16%  |
| Nvidia                   | 17       | 9.09%   |
| Marvell Technology Group | 6        | 3.21%   |
| JMicron Technology       | 6        | 3.21%   |
| VIA Technologies         | 3        | 1.6%    |
| SanDisk                  | 2        | 1.07%   |
| ASMedia Technology       | 2        | 1.07%   |
| SK hynix                 | 1        | 0.53%   |
| Samsung Electronics      | 1        | 0.53%   |
| Phison Electronics       | 1        | 0.53%   |
| Jiangsu Huacun Elec.     | 1        | 0.53%   |
| Adaptec                  | 1        | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 42       | 14.69%  |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 34       | 11.89%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 20       | 6.99%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 17       | 5.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 17       | 5.94%   |
| Nvidia MCP61 SATA Controller                                                            | 16       | 5.59%   |
| Nvidia MCP61 IDE                                                                        | 14       | 4.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 2.8%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 6        | 2.1%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 6        | 2.1%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 2.1%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 6        | 2.1%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 1.75%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 5        | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 1.75%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 1.4%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 1.4%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3        | 1.05%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.05%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3        | 1.05%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3        | 1.05%   |
| VIA Serial ATA Controller                                                               | 2        | 0.7%    |
| JMicron JMB368 IDE controller                                                           | 2        | 0.7%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.7%    |
| JMicron JMB362 SATA Controller                                                          | 2        | 0.7%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.7%    |
| Intel 82801EB (ICH5) SATA Controller                                                    | 2        | 0.7%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 0.7%    |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 0.7%    |
| AMD FCH SATA Controller D                                                               | 2        | 0.7%    |
| AMD FCH IDE Controller                                                                  | 2        | 0.7%    |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 0.7%    |
| VIA VT8237A SATA 2-Port Controller                                                      | 1        | 0.35%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 1        | 0.35%   |
| SanDisk WD Blue SN570 NVMe SSD 2TB                                                      | 1        | 0.35%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.35%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.35%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 1        | 0.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 108      | 57.14%  |
| SATA | 68       | 35.98%  |
| NVMe | 6        | 3.17%   |
| RAID | 5        | 2.65%   |
| SAS  | 1        | 0.53%   |
| SCSI | 1        | 0.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 130      | 78.31%  |
| AMD    | 36       | 21.69%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 8        | 4.82%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 7        | 4.22%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 5        | 3.01%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 4        | 2.41%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 4        | 2.41%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 4        | 2.41%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 4        | 2.41%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 3        | 1.81%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 3        | 1.81%   |
| Intel Pentium 4 CPU 3.00GHz                 | 3        | 1.81%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 1.81%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 1.81%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.81%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 1.81%   |
| AMD Sempron 145 Processor                   | 3        | 1.81%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 2        | 1.2%    |
| Intel Pentium Dual CPU E2220 @ 2.40GHz      | 2        | 1.2%    |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 2        | 1.2%    |
| Intel Pentium CPU G640 @ 2.80GHz            | 2        | 1.2%    |
| Intel Pentium 4 CPU 3.20GHz                 | 2        | 1.2%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.2%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.2%    |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.2%    |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 1.2%    |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2        | 1.2%    |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 1.2%    |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2        | 1.2%    |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2        | 1.2%    |
| AMD Sempron 140 Processor                   | 2        | 1.2%    |
| AMD FX-6300 Six-Core Processor              | 2        | 1.2%    |
| AMD FX-6100 Six-Core Processor              | 2        | 1.2%    |
| AMD Athlon II X2 250 Processor              | 2        | 1.2%    |
| Intel Xeon CPU X3220 @ 2.40GHz              | 1        | 0.6%    |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.6%    |
| Intel Xeon CPU E5-1607 0 @ 3.00GHz          | 1        | 0.6%    |
| Intel Xeon CPU E31225 @ 3.10GHz             | 1        | 0.6%    |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.6%    |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 0.6%    |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 1        | 0.6%    |
| Intel Pentium D CPU 3.00GHz                 | 1        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Pentium Dual-Core | 27       | 16.27%  |
| Intel Core i5           | 24       | 14.46%  |
| Intel Pentium           | 14       | 8.43%   |
| Intel Core i7           | 10       | 6.02%   |
| Intel Core i3           | 10       | 6.02%   |
| Intel Core 2 Duo        | 9        | 5.42%   |
| Intel Pentium Dual      | 8        | 4.82%   |
| AMD Sempron             | 7        | 4.22%   |
| Intel Pentium 4         | 6        | 3.61%   |
| Intel Core 2 Quad       | 5        | 3.01%   |
| Other                   | 4        | 2.41%   |
| Intel Xeon              | 4        | 2.41%   |
| Intel Core 2            | 4        | 2.41%   |
| AMD FX                  | 4        | 2.41%   |
| AMD Athlon II X2        | 4        | 2.41%   |
| AMD Ryzen 5             | 3        | 1.81%   |
| AMD Phenom II X4        | 3        | 1.81%   |
| Intel Pentium D         | 2        | 1.2%    |
| Intel Celeron           | 2        | 1.2%    |
| AMD Phenom              | 2        | 1.2%    |
| AMD Athlon II X4        | 2        | 1.2%    |
| AMD Athlon 64 X2        | 2        | 1.2%    |
| AMD Athlon              | 2        | 1.2%    |
| Intel Atom              | 1        | 0.6%    |
| AMD Ryzen 3             | 1        | 0.6%    |
| AMD Phenom II X2        | 1        | 0.6%    |
| AMD E1                  | 1        | 0.6%    |
| AMD Athlon II           | 1        | 0.6%    |
| AMD A8                  | 1        | 0.6%    |
| AMD A6                  | 1        | 0.6%    |
| AMD A4                  | 1        | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 87       | 52.41%  |
| 4       | 51       | 30.72%  |
| 1       | 15       | 9.04%   |
| 6       | 5        | 3.01%   |
| 3       | 5        | 3.01%   |
| Unknown | 2        | 1.2%    |
| 8       | 1        | 0.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 166      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 125      | 75.3%   |
| 2       | 39       | 23.49%  |
| Unknown | 2        | 1.2%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 161      | 96.99%  |
| 64-bit         | 2        | 1.2%    |
| 32-bit         | 2        | 1.2%    |
| Unknown        | 1        | 0.6%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 36       | 21.3%   |
| 0x1067a    | 31       | 18.34%  |
| 0x206a7    | 20       | 11.83%  |
| 0x306a9    | 9        | 5.33%   |
| 0x306c3    | 7        | 4.14%   |
| 0x6fd      | 6        | 3.55%   |
| 0x010000c8 | 5        | 2.96%   |
| 0xf65      | 4        | 2.37%   |
| 0x6fb      | 4        | 2.37%   |
| 0x6f2      | 3        | 1.78%   |
| 0x10676    | 3        | 1.78%   |
| 0x010000c7 | 3        | 1.78%   |
| 0x010000b6 | 3        | 1.78%   |
| 0xa0671    | 2        | 1.18%   |
| 0x106a5    | 2        | 1.18%   |
| 0x06000852 | 2        | 1.18%   |
| 0x0600063e | 2        | 1.18%   |
| 0x03000027 | 2        | 1.18%   |
| 0xf47      | 1        | 0.59%   |
| 0xf43      | 1        | 0.59%   |
| 0xf41      | 1        | 0.59%   |
| 0xf12      | 1        | 0.59%   |
| 0x906eb    | 1        | 0.59%   |
| 0x906e9    | 1        | 0.59%   |
| 0x806c1    | 1        | 0.59%   |
| 0x6f6      | 1        | 0.59%   |
| 0x206d7    | 1        | 0.59%   |
| 0x20652    | 1        | 0.59%   |
| 0x106ca    | 1        | 0.59%   |
| 0x10661    | 1        | 0.59%   |
| 0x0a50000c | 1        | 0.59%   |
| 0x08701030 | 1        | 0.59%   |
| 0x0810100b | 1        | 0.59%   |
| 0x0800820d | 1        | 0.59%   |
| 0x0700010b | 1        | 0.59%   |
| 0x06001119 | 1        | 0.59%   |
| 0x05000119 | 1        | 0.59%   |
| 0x03000014 | 1        | 0.59%   |
| 0x010000dc | 1        | 0.59%   |
| 0x010000db | 1        | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 39       | 23.49%  |
| SandyBridge | 28       | 16.87%  |
| K10         | 18       | 10.84%  |
| Core        | 18       | 10.84%  |
| IvyBridge   | 16       | 9.64%   |
| Haswell     | 10       | 6.02%   |
| NetBurst    | 8        | 4.82%   |
| K8 Hammer   | 4        | 2.41%   |
| Piledriver  | 3        | 1.81%   |
| Zen+        | 2        | 1.2%    |
| Westmere    | 2        | 1.2%    |
| Nehalem     | 2        | 1.2%    |
| KabyLake    | 2        | 1.2%    |
| K10 Llano   | 2        | 1.2%    |
| Bulldozer   | 2        | 1.2%    |
| Unknown     | 2        | 1.2%    |
| Zen 3       | 1        | 0.6%    |
| Zen 2       | 1        | 0.6%    |
| Zen         | 1        | 0.6%    |
| TigerLake   | 1        | 0.6%    |
| Jaguar      | 1        | 0.6%    |
| Icelake     | 1        | 0.6%    |
| Bonnell     | 1        | 0.6%    |
| Bobcat      | 1        | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 97       | 55.11%  |
| Nvidia           | 40       | 22.73%  |
| AMD              | 36       | 20.45%  |
| VIA Technologies | 3        | 1.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 23       | 12.85%  |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 20       | 11.17%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9        | 5.03%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 9        | 5.03%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 3.91%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 7        | 3.91%   |
| Nvidia GF119 [GeForce GT 520]                                               | 4        | 2.23%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 4        | 2.23%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 2.23%   |
| Intel 82946GZ/GL Integrated Graphics Controller                             | 4        | 2.23%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 3        | 1.68%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.68%   |
| Nvidia GF119 [GeForce GT 610]                                               | 3        | 1.68%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 3        | 1.68%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 3        | 1.68%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 3        | 1.68%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 3        | 1.68%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.12%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 2        | 1.12%   |
| Intel 82865G Integrated Graphics Controller                                 | 2        | 1.12%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 1.12%   |
| AMD RV670 [Radeon HD 3870]                                                  | 2        | 1.12%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 1.12%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 2        | 1.12%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 2        | 1.12%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 1.12%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 1.12%   |
| Nvidia NV44 [GeForce 7100 GS]                                               | 1        | 0.56%   |
| Nvidia NV44 [GeForce 6200 LE]                                               | 1        | 0.56%   |
| Nvidia GT218 [GeForce 405]                                                  | 1        | 0.56%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 0.56%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 0.56%   |
| Nvidia GK104GL [Quadro K4200]                                               | 1        | 0.56%   |
| Nvidia GF119 [GeForce 605]                                                  | 1        | 0.56%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 0.56%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 0.56%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 0.56%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 0.56%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 1        | 0.56%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Intel    | 90       | 53.89%  |
| 1 x Nvidia   | 38       | 22.75%  |
| 1 x AMD      | 30       | 17.96%  |
| 2 x AMD      | 3        | 1.8%    |
| 1 x VIA      | 3        | 1.8%    |
| AMD + Nvidia | 2        | 1.2%    |
| Intel + AMD  | 1        | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 137      | 82.04%  |
| Proprietary | 17       | 10.18%  |
| Unknown     | 13       | 7.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 95       | 55.56%  |
| 0.51-1.0   | 31       | 18.13%  |
| 0.01-0.5   | 26       | 15.2%   |
| 1.01-2.0   | 14       | 8.19%   |
| 3.01-4.0   | 5        | 2.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung Electronics                   | 37       | 25.52%  |
| Hewlett-Packard                       | 16       | 11.03%  |
| Goldstar                              | 15       | 10.34%  |
| Toshiba                               | 11       | 7.59%   |
| Dell                                  | 10       | 6.9%    |
| Lenovo                                | 9        | 6.21%   |
| AOC                                   | 9        | 6.21%   |
| Acer                                  | 9        | 6.21%   |
| LG Electronics                        | 3        | 2.07%   |
| BenQ                                  | 3        | 2.07%   |
| Vita                                  | 2        | 1.38%   |
| Unknown (XXX)                         | 2        | 1.38%   |
| Sony                                  | 2        | 1.38%   |
| Envision                              | 2        | 1.38%   |
| ViewSonic                             | 1        | 0.69%   |
| Toshiba Matsushita Display Technology | 1        | 0.69%   |
| TCL                                   | 1        | 0.69%   |
| Plain Tree Systems                    | 1        | 0.69%   |
| PEGA                                  | 1        | 0.69%   |
| Parker                                | 1        | 0.69%   |
| NEC Computers                         | 1        | 0.69%   |
| MStar                                 | 1        | 0.69%   |
| MSI                                   | 1        | 0.69%   |
| LSC                                   | 1        | 0.69%   |
| IBM                                   | 1        | 0.69%   |
| Haier                                 | 1        | 0.69%   |
| eMachines                             | 1        | 0.69%   |
| CVT                                   | 1        | 0.69%   |
| AOpen                                 | 1        | 0.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch              | 8        | 5.3%    |
| Lenovo LEN L174 LEN240B 1280x1024 340x270mm 17.1-inch                 | 5        | 3.31%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 4        | 2.65%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                    | 3        | 1.99%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch           | 3        | 1.99%   |
| Vita V195EW-W VIT1950 1600x900 432x240mm 19.5-inch                    | 2        | 1.32%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch  | 2        | 1.32%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 2        | 1.32%   |
| Samsung Electronics S19A10N SAM083E 1366x768 410x230mm 18.5-inch      | 2        | 1.32%   |
| Lenovo LEN L151 LEN23CD 1024x768 304x228mm 15.0-inch                  | 2        | 1.32%   |
| Hewlett-Packard S1933 HWP2933 1366x768 413x234mm 18.7-inch            | 2        | 1.32%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 2        | 1.32%   |
| Acer B193W ACR001E 1440x900 408x255mm 18.9-inch                       | 2        | 1.32%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch         | 1        | 0.66%   |
| Unknown (XXX) L9W XXX076E 1440x900 410x256mm 19.0-inch                | 1        | 0.66%   |
| Unknown (XXX) 1772ED XXX1772 1280x1024 320x250mm 16.0-inch            | 1        | 0.66%   |
| Unknown (XXX) 1772E XXX1772 1280x1024 320x250mm 16.0-inch             | 1        | 0.66%   |
| Toshiba Matsushita Display Technology LCD Monitor LCD-MONITOR         | 1        | 0.66%   |
| TCL T-7005L TCL1770 1280x1024 338x270mm 17.0-inch                     | 1        | 0.66%   |
| Sony TV SNYEB01 1360x768                                              | 1        | 0.66%   |
| Sony TV SNYEA01 1920x1080                                             | 1        | 0.66%   |
| Sony TV SNYDC01 1360x768                                              | 1        | 0.66%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch     | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch   | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch   | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM049C 1920x1080 477x268mm 21.5-inch  | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM0499 1600x900 443x249mm 20.0-inch   | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch   | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM03F5 1920x1200                      | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM03F4 1920x1200 518x324mm 24.1-inch  | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 344x194mm 15.5-inch   | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch   | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch   | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch  | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 1        | 0.66%   |
| Samsung Electronics SMBX2050N SAM0719 1600x900 443x249mm 20.0-inch    | 1        | 0.66%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch    | 1        | 0.66%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1        | 0.66%   |
| Samsung Electronics SA300/SA350 SAM0849 1920x1080 477x268mm 21.5-inch | 1        | 0.66%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1280x1024 (SXGA)   | 30       | 20.41%  |
| 1920x1080 (FHD)    | 29       | 19.73%  |
| 1366x768 (WXGA)    | 29       | 19.73%  |
| 1440x900 (WXGA+)   | 21       | 14.29%  |
| 1600x900 (HD+)     | 10       | 6.8%    |
| 1360x768           | 7        | 4.76%   |
| 1024x768 (XGA)     | 6        | 4.08%   |
| 1680x1050 (WSXGA+) | 5        | 3.4%    |
| 1280x720 (HD)      | 3        | 2.04%   |
| 3840x2160 (4K)     | 2        | 1.36%   |
| 1920x1200 (WUXGA)  | 2        | 1.36%   |
| Unknown            | 2        | 1.36%   |
| 3840x1080          | 1        | 0.68%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 35       | 23.97%  |
| 17      | 24       | 16.44%  |
| 19      | 17       | 11.64%  |
| 21      | 16       | 10.96%  |
| Unknown | 12       | 8.22%   |
| 15      | 10       | 6.85%   |
| 23      | 7        | 4.79%   |
| 20      | 7        | 4.79%   |
| 74      | 3        | 2.05%   |
| 22      | 3        | 2.05%   |
| 16      | 3        | 2.05%   |
| 72      | 2        | 1.37%   |
| 52      | 1        | 0.68%   |
| 42      | 1        | 0.68%   |
| 39      | 1        | 0.68%   |
| 31      | 1        | 0.68%   |
| 27      | 1        | 0.68%   |
| 24      | 1        | 0.68%   |
| 13      | 1        | 0.68%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 73       | 50.34%  |
| 301-350     | 32       | 22.07%  |
| Unknown     | 12       | 8.28%   |
| 501-600     | 9        | 6.21%   |
| 351-400     | 9        | 6.21%   |
| 1501-2000   | 5        | 3.45%   |
| 801-900     | 1        | 0.69%   |
| 601-700     | 1        | 0.69%   |
| 201-300     | 1        | 0.69%   |
| 1001-1500   | 1        | 0.69%   |
| 901-1000    | 1        | 0.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 68       | 47.22%  |
| 16/10   | 31       | 21.53%  |
| 5/4     | 28       | 19.44%  |
| Unknown | 10       | 6.94%   |
| 4/3     | 6        | 4.17%   |
| 3/2     | 1        | 0.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 141-150        | 47       | 32.19%  |
| 151-200        | 39       | 26.71%  |
| 201-250        | 21       | 14.38%  |
| Unknown        | 12       | 8.22%   |
| 101-110        | 10       | 6.85%   |
| More than 1000 | 6        | 4.11%   |
| 121-130        | 3        | 2.05%   |
| 131-140        | 2        | 1.37%   |
| 501-1000       | 2        | 1.37%   |
| 351-500        | 1        | 0.68%   |
| 301-350        | 1        | 0.68%   |
| 251-300        | 1        | 0.68%   |
| 91-100         | 1        | 0.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 104      | 72.22%  |
| 101-120 | 20       | 13.89%  |
| Unknown | 12       | 8.33%   |
| 1-50    | 7        | 4.86%   |
| 121-160 | 1        | 0.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 142      | 85.54%  |
| 0     | 14       | 8.43%   |
| 2     | 9        | 5.42%   |
| 3     | 1        | 0.6%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 97       | 37.74%  |
| Intel                             | 39       | 15.18%  |
| Qualcomm Atheros                  | 36       | 14.01%  |
| Nvidia                            | 17       | 6.61%   |
| Ralink                            | 16       | 6.23%   |
| Ralink Technology                 | 10       | 3.89%   |
| Broadcom                          | 10       | 3.89%   |
| Xiaomi                            | 4        | 1.56%   |
| Qualcomm Atheros Communications   | 4        | 1.56%   |
| VIA Technologies                  | 3        | 1.17%   |
| TP-Link                           | 3        | 1.17%   |
| Sundance Technology Inc / IC Plus | 2        | 0.78%   |
| Mercucys                          | 2        | 0.78%   |
| Marvell Technology Group          | 2        | 0.78%   |
| D-Link System                     | 2        | 0.78%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.39%   |
| Trendchip Technologies            | 1        | 0.39%   |
| Samsung Electronics               | 1        | 0.39%   |
| National Semiconductor            | 1        | 0.39%   |
| Motorola PCS                      | 1        | 0.39%   |
| Motorola BCS                      | 1        | 0.39%   |
| JMicron Technology                | 1        | 0.39%   |
| ICS Advent                        | 1        | 0.39%   |
| Davicom Semiconductor             | 1        | 0.39%   |
| Broadcom Limited                  | 1        | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 63       | 22.99%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 18       | 6.57%   |
| Nvidia MCP61 Ethernet                                                          | 16       | 5.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 13       | 4.74%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 9        | 3.28%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 7        | 2.55%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 6        | 2.19%   |
| Intel Ethernet Connection I217-LM                                              | 6        | 2.19%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 5        | 1.82%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 4        | 1.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 4        | 1.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 4        | 1.46%   |
| Ralink MT7601U Wireless Adapter                                                | 4        | 1.46%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 4        | 1.46%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 4        | 1.46%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                          | 4        | 1.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3        | 1.09%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 3        | 1.09%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 3        | 1.09%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 3        | 1.09%   |
| Qualcomm Atheros AR9271 802.11n                                                | 3        | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 3        | 1.09%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3        | 1.09%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 2        | 0.73%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 2        | 0.73%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 2        | 0.73%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 2        | 0.73%   |
| Realtek 802.11ac NIC                                                           | 2        | 0.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2        | 0.73%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                               | 2        | 0.73%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                               | 2        | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2        | 0.73%   |
| Mercucys MW300UM RTL8192EU wifi                                                | 2        | 0.73%   |
| Intel PRO/100 VE Network Connection                                            | 2        | 0.73%   |
| Intel Ethernet Connection I217-V                                               | 2        | 0.73%   |
| Intel 82567V-2 Gigabit Network Connection                                      | 2        | 0.73%   |
| Broadcom BCM43225 802.11b/g/n                                                  | 2        | 0.73%   |
| ZTE WCDMA MSM ZXIC Mobile Boardband                                            | 1        | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1        | 0.36%   |
| Trendchip Ethernet controller                                                  | 1        | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros                | 24       | 26.97%  |
| Realtek Semiconductor           | 19       | 21.35%  |
| Ralink                          | 16       | 17.98%  |
| Ralink Technology               | 10       | 11.24%  |
| Intel                           | 6        | 6.74%   |
| Qualcomm Atheros Communications | 4        | 4.49%   |
| TP-Link                         | 3        | 3.37%   |
| Broadcom                        | 3        | 3.37%   |
| Mercucys                        | 2        | 2.25%   |
| D-Link System                   | 2        | 2.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 7        | 7.87%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 6        | 6.74%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 5        | 5.62%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 4        | 4.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 4        | 4.49%   |
| Ralink MT7601U Wireless Adapter                                                | 4        | 4.49%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 4        | 4.49%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 4        | 4.49%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 3        | 3.37%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 3        | 3.37%   |
| Qualcomm Atheros AR9271 802.11n                                                | 3        | 3.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 3        | 3.37%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3        | 3.37%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 2        | 2.25%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 2        | 2.25%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 2        | 2.25%   |
| Realtek 802.11ac NIC                                                           | 2        | 2.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2        | 2.25%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                               | 2        | 2.25%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                               | 2        | 2.25%   |
| Mercucys MW300UM RTL8192EU wifi                                                | 2        | 2.25%   |
| Broadcom BCM43225 802.11b/g/n                                                  | 2        | 2.25%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                    | 1        | 1.12%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1        | 1.12%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                      | 1        | 1.12%   |
| Ralink RT5372 Wireless Adapter                                                 | 1        | 1.12%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                         | 1        | 1.12%   |
| Ralink RT2800 802.11n PCI                                                      | 1        | 1.12%   |
| Ralink RT2561/RT61 802.11g PCI                                                 | 1        | 1.12%   |
| Qualcomm Atheros AR5523                                                        | 1        | 1.12%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]            | 1        | 1.12%   |
| Intel Wireless 7265                                                            | 1        | 1.12%   |
| Intel Wireless 7260                                                            | 1        | 1.12%   |
| Intel Wi-Fi 6 AX200                                                            | 1        | 1.12%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 1        | 1.12%   |
| Intel Centrino Wireless-N 105                                                  | 1        | 1.12%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 1        | 1.12%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]           | 1        | 1.12%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]              | 1        | 1.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 1        | 1.12%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 87       | 48.07%  |
| Intel                             | 35       | 19.34%  |
| Nvidia                            | 17       | 9.39%   |
| Qualcomm Atheros                  | 16       | 8.84%   |
| Broadcom                          | 7        | 3.87%   |
| Xiaomi                            | 4        | 2.21%   |
| VIA Technologies                  | 3        | 1.66%   |
| Sundance Technology Inc / IC Plus | 2        | 1.1%    |
| Marvell Technology Group          | 2        | 1.1%    |
| Trendchip Technologies            | 1        | 0.55%   |
| National Semiconductor            | 1        | 0.55%   |
| Motorola PCS                      | 1        | 0.55%   |
| Motorola BCS                      | 1        | 0.55%   |
| JMicron Technology                | 1        | 0.55%   |
| ICS Advent                        | 1        | 0.55%   |
| Davicom Semiconductor             | 1        | 0.55%   |
| Broadcom Limited                  | 1        | 0.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 63       | 34.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 18       | 9.84%   |
| Nvidia MCP61 Ethernet                                                      | 16       | 8.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 13       | 7.1%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 9        | 4.92%   |
| Intel Ethernet Connection I217-LM                                          | 6        | 3.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 4        | 2.19%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                      | 4        | 2.19%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 3        | 1.64%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 3        | 1.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 2        | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 1.09%   |
| Intel PRO/100 VE Network Connection                                        | 2        | 1.09%   |
| Intel Ethernet Connection I217-V                                           | 2        | 1.09%   |
| Intel 82567V-2 Gigabit Network Connection                                  | 2        | 1.09%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1        | 0.55%   |
| Trendchip Ethernet controller                                              | 1        | 0.55%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1        | 0.55%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.55%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 0.55%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 1        | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 1        | 0.55%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 1        | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1        | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.55%   |
| Nvidia MCP77 Ethernet                                                      | 1        | 0.55%   |
| National DP83815 (MacPhyter) Ethernet Controller                           | 1        | 0.55%   |
| Motorola PCS XT1032                                                        | 1        | 0.55%   |
| Motorola BCS SurfBoard SB5100 Cable Modem                                  | 1        | 0.55%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                    | 1        | 0.55%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 1        | 0.55%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                     | 1        | 0.55%   |
| Intel NM10/ICH7 Family LAN Controller                                      | 1        | 0.55%   |
| Intel Ethernet Controller I225-V                                           | 1        | 0.55%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                         | 1        | 0.55%   |
| Intel 82579V Gigabit Network Connection                                    | 1        | 0.55%   |
| Intel 82567V-4 Gigabit Network Connection                                  | 1        | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 1        | 0.55%   |
| Intel 82566DC-2 Gigabit Network Connection                                 | 1        | 0.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 163      | 65.46%  |
| WiFi     | 84       | 33.73%  |
| Modem    | 2        | 0.8%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 118      | 68.21%  |
| WiFi     | 55       | 31.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 109      | 64.5%   |
| 2     | 56       | 33.14%  |
| 3     | 3        | 1.78%   |
| 0     | 1        | 0.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 166      | 99.4%   |
| Yes  | 1        | 0.6%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 7        | 38.89%  |
| Intel                   | 4        | 22.22%  |
| Broadcom                | 3        | 16.67%  |
| IMC Networks            | 2        | 11.11%  |
| ASUSTek Computer        | 2        | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 38.89%  |
| Intel AX201 Bluetooth                               | 2        | 11.11%  |
| IMC Networks Bluetooth Module                       | 2        | 11.11%  |
| Intel Bluetooth wireless interface                  | 1        | 5.56%   |
| Intel AX200 Bluetooth                               | 1        | 5.56%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 UHE Dongle | 1        | 5.56%   |
| Broadcom BCM2070 Bluetooth Device                   | 1        | 5.56%   |
| Broadcom BCM2035B3 Bluetooth Adapter                | 1        | 5.56%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 5.56%   |
| ASUS Bluetooth Adapter                              | 1        | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 123      | 53.95%  |
| AMD                    | 40       | 17.54%  |
| Nvidia                 | 36       | 15.79%  |
| C-Media Electronics    | 6        | 2.63%   |
| VIA Technologies       | 5        | 2.19%   |
| Creative Labs          | 5        | 2.19%   |
| JMTek                  | 3        | 1.32%   |
| Generalplus Technology | 3        | 1.32%   |
| Logitech               | 2        | 0.88%   |
| Unknown                | 1        | 0.44%   |
| Microsoft              | 1        | 0.44%   |
| Megawin Technology     | 1        | 0.44%   |
| Giga-Byte Technology   | 1        | 0.44%   |
| Aureal Semiconductor   | 1        | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 42       | 16.67%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 37       | 14.68%  |
| Nvidia MCP61 High Definition Audio                                                | 14       | 5.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 10       | 3.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 9        | 3.57%   |
| Nvidia GF119 HDMI Audio Controller                                                | 8        | 3.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 8        | 3.17%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 7        | 2.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 6        | 2.38%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 6        | 2.38%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 5        | 1.98%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 5        | 1.98%   |
| AMD FCH Azalia Controller                                                         | 5        | 1.98%   |
| Nvidia High Definition Audio Controller                                           | 4        | 1.59%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 4        | 1.59%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                    | 3        | 1.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3        | 1.19%   |
| Nvidia GF106 High Definition Audio Controller                                     | 3        | 1.19%   |
| Generalplus Technology USB Audio Device                                           | 3        | 1.19%   |
| AMD Family 17h/19h HD Audio Controller                                            | 3        | 1.19%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 1.19%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller       | 2        | 0.79%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 0.79%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2        | 0.79%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 2        | 0.79%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                              | 2        | 0.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2        | 0.79%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 2        | 0.79%   |
| C-Media Electronics CM108 Audio Controller                                        | 2        | 0.79%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2        | 0.79%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 0.79%   |
| AMD RV670/680 HDMI Audio [Radeon HD 3690/3800 Series]                             | 2        | 0.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 0.79%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2        | 0.79%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]               | 2        | 0.79%   |
| Unknown Audio device                                                              | 1        | 0.4%    |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 1        | 0.4%    |
| Nvidia GK107 HDMI Audio Controller                                                | 1        | 0.4%    |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 0.4%    |
| Nvidia GF116 High Definition Audio Controller                                     | 1        | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 45       | 32.85%  |
| Samsung Electronics        | 15       | 10.95%  |
| Kingston                   | 15       | 10.95%  |
| SK hynix                   | 11       | 8.03%   |
| Ramaxel Technology         | 10       | 7.3%    |
| Crucial                    | 8        | 5.84%   |
| Corsair                    | 7        | 5.11%   |
| Micron Technology          | 6        | 4.38%   |
| Team                       | 3        | 2.19%   |
| Nanya Technology           | 3        | 2.19%   |
| Elpida                     | 2        | 1.46%   |
| Avant                      | 2        | 1.46%   |
| A-DATA Technology          | 2        | 1.46%   |
| Unknown                    | 2        | 1.46%   |
| Unknown (7F7F7F7F7F7F7F83) | 1        | 0.73%   |
| Unknown (0x0CBA)           | 1        | 0.73%   |
| Qimonda                    | 1        | 0.73%   |
| PNY                        | 1        | 0.73%   |
| OCZ                        | 1        | 0.73%   |
| Kreton                     | 1        | 0.73%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM SDRAM                     | 4        | 2.56%   |
| Unknown RAM Module 4GB DIMM 400MT/s                   | 4        | 2.56%   |
| Unknown RAM Module 2GB DIMM SDRAM                     | 4        | 2.56%   |
| Unknown RAM Module 2048MB DIMM DDR2                   | 3        | 1.92%   |
| Unknown RAM Module 1024MB DIMM DDR2                   | 3        | 1.92%   |
| Ramaxel RAM RMR5030ED58E8W1600 2GB DIMM DDR3 1600MT/s | 3        | 1.92%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s             | 2        | 1.28%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                  | 2        | 1.28%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s             | 2        | 1.28%   |
| Unknown RAM Module 2GB DIMM DDR2                      | 2        | 1.28%   |
| Unknown RAM Module 2GB DIMM 400MT/s                   | 2        | 1.28%   |
| Unknown RAM Module 2048MB DIMM SDRAM                  | 2        | 1.28%   |
| Unknown RAM Module 1024MB DIMM SDRAM                  | 2        | 1.28%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s           | 2        | 1.28%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s             | 2        | 1.28%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s   | 2        | 1.28%   |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3 1600MT/s   | 2        | 1.28%   |
| Ramaxel RAM RMR5030ME68F9F1600 4GB DIMM DDR3 1600MT/s | 2        | 1.28%   |
| Ramaxel RAM RMR1870EC58E9F1333 4GB DIMM DDR3 1333MT/s | 2        | 1.28%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s    | 2        | 1.28%   |
| Unknown                                               | 2        | 1.28%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                  | 1        | 0.64%   |
| Unknown RAM Module 512MB DIMM DDR2                    | 1        | 0.64%   |
| Unknown RAM Module 4GB DIMM 667MT/s                   | 1        | 0.64%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 1        | 0.64%   |
| Unknown RAM Module 4096MB DIMM SDRAM                  | 1        | 0.64%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s          | 1        | 0.64%   |
| Unknown RAM Module 4096MB DIMM                        | 1        | 0.64%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s              | 1        | 0.64%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s               | 1        | 0.64%   |
| Unknown RAM Module 2GB DIMM 800MT/s                   | 1        | 0.64%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s          | 1        | 0.64%   |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s          | 1        | 0.64%   |
| Unknown RAM Module 2048MB DIMM DDR2 533MT/s           | 1        | 0.64%   |
| Unknown RAM Module 2048MB DIMM DDR2 1639MT/s          | 1        | 0.64%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s            | 1        | 0.64%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s            | 1        | 0.64%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s               | 1        | 0.64%   |
| Unknown RAM Module 1GB DIMM DDR 133MT/s               | 1        | 0.64%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s            | 1        | 0.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 43       | 39.45%  |
| DDR2    | 22       | 20.18%  |
| SDRAM   | 17       | 15.6%   |
| Unknown | 14       | 12.84%  |
| DDR4    | 8        | 7.34%   |
| DDR     | 5        | 4.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 101      | 96.19%  |
| SODIMM | 4        | 3.81%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 47       | 37.3%   |
| 4096  | 42       | 33.33%  |
| 1024  | 17       | 13.49%  |
| 8192  | 14       | 11.11%  |
| 32768 | 2        | 1.59%   |
| 16384 | 2        | 1.59%   |
| 512   | 2        | 1.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 25       | 20.33%  |
| 1333    | 23       | 18.7%   |
| Unknown | 19       | 15.45%  |
| 800     | 8        | 6.5%    |
| 667     | 7        | 5.69%   |
| 400     | 6        | 4.88%   |
| 1066    | 5        | 4.07%   |
| 533     | 4        | 3.25%   |
| 1639    | 3        | 2.44%   |
| 133     | 3        | 2.44%   |
| 3733    | 2        | 1.63%   |
| 3600    | 2        | 1.63%   |
| 3200    | 2        | 1.63%   |
| 2133    | 2        | 1.63%   |
| 2048    | 2        | 1.63%   |
| 1867    | 2        | 1.63%   |
| 3800    | 1        | 0.81%   |
| 2667    | 1        | 0.81%   |
| 2400    | 1        | 0.81%   |
| 2000    | 1        | 0.81%   |
| 1800    | 1        | 0.81%   |
| 1067    | 1        | 0.81%   |
| 1024    | 1        | 0.81%   |
| 266     | 1        | 0.81%   |

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
| Logitech                    | 5        | 21.74%  |
| Microsoft                   | 4        | 17.39%  |
| Samsung Electronics         | 3        | 13.04%  |
| KYE Systems (Mouse Systems) | 2        | 8.7%    |
| IMC Networks                | 2        | 8.7%    |
| Suyin                       | 1        | 4.35%   |
| SiGma Micro                 | 1        | 4.35%   |
| Realtek Semiconductor       | 1        | 4.35%   |
| LG Electronics              | 1        | 4.35%   |
| Cubeternet                  | 1        | 4.35%   |
| Chicony Electronics         | 1        | 4.35%   |
| Aveo Technology             | 1        | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode)               | 3        | 13.04%  |
| Logitech Webcam C270                                  | 3        | 13.04%  |
| Suyin HP Webcam                                       | 1        | 4.35%   |
| SiGma Micro WebCam SiGma Micro                        | 1        | 4.35%   |
| Realtek HP 1.0MP High Definition Webcam               | 1        | 4.35%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks   | 1        | 4.35%   |
| Microsoft LifeCam VX-5000                             | 1        | 4.35%   |
| Microsoft LifeCam Studio                              | 1        | 4.35%   |
| Microsoft LifeCam HD-3000                             | 1        | 4.35%   |
| Logitech QuickCam Communicate MP/S5500                | 1        | 4.35%   |
| Logitech C922 Pro Stream Webcam                       | 1        | 4.35%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 4.35%   |
| KYE Systems (Mouse Systems) FaceCam 1320              | 1        | 4.35%   |
| KYE Systems (Mouse Systems) eFace 2025                | 1        | 4.35%   |
| IMC Networks USB2.0 UVC 1.3M WebCam                   | 1        | 4.35%   |
| IMC Networks USB 2.0 Camera                           | 1        | 4.35%   |
| Cubeternet USB2.0 Camera                              | 1        | 4.35%   |
| Chicony HD Webcam                                     | 1        | 4.35%   |
| Aveo USB2.0 Camera                                    | 1        | 4.35%   |

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
| 0     | 134      | 80.72%  |
| 1     | 30       | 18.07%  |
| 2     | 2        | 1.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 16       | 48.48%  |
| Communication controller | 10       | 30.3%   |
| Net/wireless             | 3        | 9.09%   |
| Sound                    | 2        | 6.06%   |
| Storage/ide              | 1        | 3.03%   |
| Camera                   | 1        | 3.03%   |


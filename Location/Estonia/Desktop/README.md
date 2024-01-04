Linux in Estonia - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Estonia.

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

Total: 182

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | M5A97 LE R2.0               | [0863d91cdc](https://linux-hardware.org/?probe=0863d91cdc) | Dec 25, 2023 |
| Fujitsu  | D3161-A1 S26361-D3161-A1    | [c1069bda0b](https://linux-hardware.org/?probe=c1069bda0b) | Dec 23, 2023 |
| ASUSTek  | M5A97 LE R2.0               | [e222a97c0b](https://linux-hardware.org/?probe=e222a97c0b) | Dec 21, 2023 |
| Fujitsu  | D3161-A1 S26361-D3161-A1    | [9c4f708056](https://linux-hardware.org/?probe=9c4f708056) | Dec 10, 2023 |
| Fujitsu  | D3161-A1 S26361-D3161-A1    | [be768fb273](https://linux-hardware.org/?probe=be768fb273) | Dec 06, 2023 |
| HP       | 8619                        | [a33e273f33](https://linux-hardware.org/?probe=a33e273f33) | Dec 04, 2023 |
| MSI      | MPG B550 GAMING EDGE WIF... | [bb0ded92ef](https://linux-hardware.org/?probe=bb0ded92ef) | Dec 03, 2023 |
| ASUSTek  | PRIME B550M-K               | [a1ab0858a6](https://linux-hardware.org/?probe=a1ab0858a6) | Dec 01, 2023 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [78e9bae926](https://linux-hardware.org/?probe=78e9bae926) | Nov 26, 2023 |
| ASUSTek  | ROG STRIX B650E-I GAMING... | [2ab108f743](https://linux-hardware.org/?probe=2ab108f743) | Nov 22, 2023 |
| Intel    | DH61DL AAG14066-205         | [be33944c69](https://linux-hardware.org/?probe=be33944c69) | Nov 05, 2023 |
| ECS      | H61H2-M12                   | [885cbf522c](https://linux-hardware.org/?probe=885cbf522c) | Oct 28, 2023 |
| MSI      | PRO B660-A DDR4             | [506accae39](https://linux-hardware.org/?probe=506accae39) | Oct 16, 2023 |
| Gigabyte | B75M-D3H                    | [d78e4ab87d](https://linux-hardware.org/?probe=d78e4ab87d) | Aug 08, 2023 |
| ASUSTek  | PRIME Z790M-PLUS            | [ea7090722f](https://linux-hardware.org/?probe=ea7090722f) | Jun 22, 2023 |
| HP       | 8643 SMVB                   | [961a04643c](https://linux-hardware.org/?probe=961a04643c) | May 25, 2023 |
| Lenovo   | ThinkStation D20 4158GK1    | [44d9536051](https://linux-hardware.org/?probe=44d9536051) | Apr 14, 2023 |
| HP       | 304Ah                       | [14d92e85a2](https://linux-hardware.org/?probe=14d92e85a2) | Apr 01, 2023 |
| ASUSTek  | TUF Gaming B550-PLUS        | [6694c9279d](https://linux-hardware.org/?probe=6694c9279d) | Mar 31, 2023 |
| ASUSTek  | P8Z77-V LK                  | [6b088adaf9](https://linux-hardware.org/?probe=6b088adaf9) | Mar 27, 2023 |
| ASRock   | B660M-ITX/ac                | [95687a223c](https://linux-hardware.org/?probe=95687a223c) | Mar 22, 2023 |
| HP       | 304Ah                       | [49adbe8acf](https://linux-hardware.org/?probe=49adbe8acf) | Mar 20, 2023 |
| ASUSTek  | ROG STRIX B650E-E GAMING... | [37bf97e9b3](https://linux-hardware.org/?probe=37bf97e9b3) | Mar 16, 2023 |
| MSI      | B450-A PRO MAX              | [ec707b621c](https://linux-hardware.org/?probe=ec707b621c) | Mar 05, 2023 |
| MSI      | B450-A PRO MAX              | [36699f94c9](https://linux-hardware.org/?probe=36699f94c9) | Mar 05, 2023 |
| ASRock   | H81M-DGS R2.0               | [396ad2d6aa](https://linux-hardware.org/?probe=396ad2d6aa) | Mar 04, 2023 |
| ASRock   | B660M-ITX/ac                | [c2e600e445](https://linux-hardware.org/?probe=c2e600e445) | Feb 28, 2023 |
| ASRock   | B660M-ITX/ac                | [1efc15e2cc](https://linux-hardware.org/?probe=1efc15e2cc) | Feb 28, 2023 |
| ASUSTek  | H81M-K                      | [6f09d6cd6c](https://linux-hardware.org/?probe=6f09d6cd6c) | Feb 05, 2023 |
| Fujitsu  | D3161-A1 S26361-D3161-A1    | [07d496ada9](https://linux-hardware.org/?probe=07d496ada9) | Feb 04, 2023 |
| ASUSTek  | PRIME H310M-K               | [146f307b8e](https://linux-hardware.org/?probe=146f307b8e) | Jan 10, 2023 |
| ASUSTek  | PRIME B360M-C               | [aa21c2b75f](https://linux-hardware.org/?probe=aa21c2b75f) | Jan 06, 2023 |
| Fujitsu  | D3161-A1 S26361-D3161-A1    | [efa2d6986f](https://linux-hardware.org/?probe=efa2d6986f) | Dec 28, 2022 |
| Fujitsu  | D3161-A1 S26361-D3161-A1    | [70436ae3c3](https://linux-hardware.org/?probe=70436ae3c3) | Dec 15, 2022 |
| Fujitsu  | D3161-A1 S26361-D3161-A1    | [4c5bac90eb](https://linux-hardware.org/?probe=4c5bac90eb) | Dec 15, 2022 |
| ASRock   | Z490M Pro4                  | [2ace77f72c](https://linux-hardware.org/?probe=2ace77f72c) | Dec 14, 2022 |
| ASRock   | Z490M Pro4                  | [0b91c8c70f](https://linux-hardware.org/?probe=0b91c8c70f) | Dec 14, 2022 |
| MSI      | MAG B660M BAZOOKA DDR4      | [280f28a486](https://linux-hardware.org/?probe=280f28a486) | Dec 11, 2022 |
| MSI      | Z490-A PRO                  | [9154fdbc9e](https://linux-hardware.org/?probe=9154fdbc9e) | Nov 24, 2022 |
| ASUSTek  | M4A78                       | [8eb1316a14](https://linux-hardware.org/?probe=8eb1316a14) | Oct 31, 2022 |
| ASUSTek  | M4A78                       | [81374a561c](https://linux-hardware.org/?probe=81374a561c) | Oct 31, 2022 |
| ASUSTek  | M4A78                       | [d88d101a3c](https://linux-hardware.org/?probe=d88d101a3c) | Oct 29, 2022 |
| Gigabyte | B550 GAMING X V2            | [5405caf9dc](https://linux-hardware.org/?probe=5405caf9dc) | Oct 28, 2022 |
| Gigabyte | GA-MA770-UD3                | [dbb72f4c00](https://linux-hardware.org/?probe=dbb72f4c00) | Oct 26, 2022 |
| MSI      | B450 TOMAHAWK MAX           | [8b459ac79b](https://linux-hardware.org/?probe=8b459ac79b) | Oct 20, 2022 |
| ASRock   | B460 Steel Legend           | [ca98840e23](https://linux-hardware.org/?probe=ca98840e23) | Oct 14, 2022 |
| Unknown  | Seagate Personal Cloud (... | [40ea197650](https://linux-hardware.org/?probe=40ea197650) | Oct 09, 2022 |
| Gigabyte | GA-MA770T-UD3               | [f6c6b627f7](https://linux-hardware.org/?probe=f6c6b627f7) | Aug 28, 2022 |
| ASUSTek  | TUF Gaming B450-PLUS II     | [7332174749](https://linux-hardware.org/?probe=7332174749) | Aug 24, 2022 |
| Gigabyte | Q87M-D2H                    | [8c56960243](https://linux-hardware.org/?probe=8c56960243) | Aug 19, 2022 |
| MSI      | MAG B460M BAZOOKA           | [5dae076f42](https://linux-hardware.org/?probe=5dae076f42) | Jul 27, 2022 |
| ECS      | G41T-M7                     | [a531a754a8](https://linux-hardware.org/?probe=a531a754a8) | Jul 23, 2022 |
| HP       | 3646h                       | [88b38da161](https://linux-hardware.org/?probe=88b38da161) | Jul 11, 2022 |
| Gigabyte | B550 GAMING X V2            | [cdb4149eba](https://linux-hardware.org/?probe=cdb4149eba) | Jun 27, 2022 |
| MSI      | Z77A-G41                    | [d0f55f3c0b](https://linux-hardware.org/?probe=d0f55f3c0b) | Jun 22, 2022 |
| Dell     | 0VHWTR A02                  | [d8f9374e6c](https://linux-hardware.org/?probe=d8f9374e6c) | Jun 22, 2022 |
| Dell     | 0VHWTR A02                  | [00495646c1](https://linux-hardware.org/?probe=00495646c1) | Jun 22, 2022 |
| Dell     | 0VHWTR A02                  | [208e447fe1](https://linux-hardware.org/?probe=208e447fe1) | Jun 17, 2022 |
| Dell     | 088DT1 A00                  | [b585cb1f70](https://linux-hardware.org/?probe=b585cb1f70) | Jun 07, 2022 |
| Intel    | DP67BG AAG10491-305         | [714722d24b](https://linux-hardware.org/?probe=714722d24b) | Jun 01, 2022 |
| Intel    | DP67BG AAG10491-305         | [966ab11802](https://linux-hardware.org/?probe=966ab11802) | May 31, 2022 |
| ASRock   | AB350 Pro4                  | [49223fe44b](https://linux-hardware.org/?probe=49223fe44b) | May 21, 2022 |
| ASRock   | AB350 Pro4                  | [40cb336486](https://linux-hardware.org/?probe=40cb336486) | May 21, 2022 |
| Gigabyte | H55M-S2                     | [4d68acc78c](https://linux-hardware.org/?probe=4d68acc78c) | May 18, 2022 |
| Lenovo   | ThinkCentre M58 7360WQK     | [9002375046](https://linux-hardware.org/?probe=9002375046) | May 13, 2022 |
| Gigabyte | B560 HD3                    | [34fd3f60c4](https://linux-hardware.org/?probe=34fd3f60c4) | May 11, 2022 |
| ASUSTek  | H97M-PLUS                   | [ccf4457b51](https://linux-hardware.org/?probe=ccf4457b51) | Mar 28, 2022 |
| HP       | 18E9                        | [5a223b8722](https://linux-hardware.org/?probe=5a223b8722) | Mar 23, 2022 |
| Lenovo   | 31900058 STD                | [d34e3c79a0](https://linux-hardware.org/?probe=d34e3c79a0) | Mar 01, 2022 |
| ECS      | G41T-M7                     | [c4aca5bc12](https://linux-hardware.org/?probe=c4aca5bc12) | Feb 20, 2022 |
| MSI      | B150M PRO-VD                | [b46943492e](https://linux-hardware.org/?probe=b46943492e) | Feb 15, 2022 |
| HP       | 304Ah                       | [078b605c39](https://linux-hardware.org/?probe=078b605c39) | Feb 09, 2022 |
| MSI      | Z390-A PRO                  | [c9b246d9a8](https://linux-hardware.org/?probe=c9b246d9a8) | Jan 12, 2022 |
| MSI      | Z390-A PRO                  | [49234f883d](https://linux-hardware.org/?probe=49234f883d) | Jan 12, 2022 |
| Huanan   | X79 V2.47                   | [a27e7cdbef](https://linux-hardware.org/?probe=a27e7cdbef) | Jan 09, 2022 |
| Dell     | 0KH290                      | [e8c0e16dfb](https://linux-hardware.org/?probe=e8c0e16dfb) | Dec 28, 2021 |
| ASUSTek  | TUF Gaming B560M-PLUS       | [5c0550c1e8](https://linux-hardware.org/?probe=5c0550c1e8) | Dec 09, 2021 |
| ASUSTek  | ProArt X570-CREATOR WIFI    | [db552307a3](https://linux-hardware.org/?probe=db552307a3) | Dec 07, 2021 |
| Gigabyte | X570 UD                     | [79c117738b](https://linux-hardware.org/?probe=79c117738b) | Dec 01, 2021 |
| Gigabyte | GA-790XTA-UD4               | [6eb5a4107e](https://linux-hardware.org/?probe=6eb5a4107e) | Nov 10, 2021 |
| Intel    | D33217GKE G69901-205        | [a922d5f3fc](https://linux-hardware.org/?probe=a922d5f3fc) | Nov 10, 2021 |
| Intel    | D33217GKE G69901-205        | [dd1ddaf74f](https://linux-hardware.org/?probe=dd1ddaf74f) | Nov 09, 2021 |
| MSI      | MAG Z390 TOMAHAWK           | [201bc8d044](https://linux-hardware.org/?probe=201bc8d044) | Oct 17, 2021 |
| Huanan   | X79 V2.47                   | [326b3f5892](https://linux-hardware.org/?probe=326b3f5892) | Oct 07, 2021 |
| Huanan   | X79 V2.47                   | [c2c6287186](https://linux-hardware.org/?probe=c2c6287186) | Oct 07, 2021 |
| Lenovo   | 318E SDK0J40697 WIN 3305... | [9cd559605c](https://linux-hardware.org/?probe=9cd559605c) | Sep 27, 2021 |
| Lenovo   | 318E SDK0J40697 WIN 3305... | [68f4ff7431](https://linux-hardware.org/?probe=68f4ff7431) | Sep 27, 2021 |
| Dell     | 0NW6H5 A00                  | [bf81c78371](https://linux-hardware.org/?probe=bf81c78371) | Aug 26, 2021 |
| Gigabyte | Z87X-D3H-CF                 | [b40ad47903](https://linux-hardware.org/?probe=b40ad47903) | Aug 25, 2021 |
| Dell     | 0NW6H5 A00                  | [559742f4d7](https://linux-hardware.org/?probe=559742f4d7) | Aug 19, 2021 |
| Dell     | 0NW6H5 A00                  | [d28cc83aed](https://linux-hardware.org/?probe=d28cc83aed) | Aug 17, 2021 |
| Dell     | 0NW6H5 A00                  | [be5db43316](https://linux-hardware.org/?probe=be5db43316) | Aug 17, 2021 |
| Gigabyte | F2A68HM-S1                  | [286d06cd5e](https://linux-hardware.org/?probe=286d06cd5e) | Aug 15, 2021 |
| Gigabyte | B250M-D2V-CF                | [b2db3ea0a9](https://linux-hardware.org/?probe=b2db3ea0a9) | Aug 10, 2021 |
| Gigabyte | B250M-D2V-CF                | [c086b1441c](https://linux-hardware.org/?probe=c086b1441c) | Aug 09, 2021 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [2a9fe5f63c](https://linux-hardware.org/?probe=2a9fe5f63c) | Jul 31, 2021 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [1c5dccfd22](https://linux-hardware.org/?probe=1c5dccfd22) | Jul 31, 2021 |
| ASUSTek  | M3N78                       | [810e386d8b](https://linux-hardware.org/?probe=810e386d8b) | Jul 26, 2021 |
| Gigabyte | Q87M-D2H                    | [4f26f93184](https://linux-hardware.org/?probe=4f26f93184) | Jul 26, 2021 |
| Gigabyte | X570 AORUS PRO              | [932c4de6ce](https://linux-hardware.org/?probe=932c4de6ce) | Jul 18, 2021 |
| ASUSTek  | N3050I-C                    | [e9cd0640f7](https://linux-hardware.org/?probe=e9cd0640f7) | Jun 30, 2021 |
| MSI      | MAG B550 TOMAHAWK           | [7a01d3d232](https://linux-hardware.org/?probe=7a01d3d232) | Jun 28, 2021 |
| ASUSTek  | N3050I-C                    | [c42e493962](https://linux-hardware.org/?probe=c42e493962) | Jun 26, 2021 |
| ASUSTek  | N3050I-C                    | [9834731c15](https://linux-hardware.org/?probe=9834731c15) | Jun 26, 2021 |
| MSI      | B250M PRO-VD                | [20ff770033](https://linux-hardware.org/?probe=20ff770033) | Apr 07, 2021 |
| ASUSTek  | P5LD2                       | [72b40a39d4](https://linux-hardware.org/?probe=72b40a39d4) | Mar 25, 2021 |
| MSI      | B450 TOMAHAWK MAX           | [f555918663](https://linux-hardware.org/?probe=f555918663) | Mar 24, 2021 |
| OEM      | Intel H81                   | [385b6ee448](https://linux-hardware.org/?probe=385b6ee448) | Mar 19, 2021 |
| MSI      | MPG X570 GAMING PLUS        | [9b991380f9](https://linux-hardware.org/?probe=9b991380f9) | Mar 17, 2021 |
| MSI      | B450 TOMAHAWK MAX           | [273fba9fd2](https://linux-hardware.org/?probe=273fba9fd2) | Mar 14, 2021 |
| MSI      | B450 TOMAHAWK MAX           | [75a661f9f8](https://linux-hardware.org/?probe=75a661f9f8) | Mar 14, 2021 |
| Gigabyte | Z370 AORUS Gaming 5-CF      | [ff698cacf3](https://linux-hardware.org/?probe=ff698cacf3) | Feb 27, 2021 |
| Gigabyte | Z370 AORUS Gaming 5-CF      | [116202ee88](https://linux-hardware.org/?probe=116202ee88) | Feb 27, 2021 |
| MSI      | MS-7267                     | [b987c1ad14](https://linux-hardware.org/?probe=b987c1ad14) | Feb 15, 2021 |
| ASUSTek  | PRIME B350-PLUS             | [e1dc5a8ea7](https://linux-hardware.org/?probe=e1dc5a8ea7) | Feb 14, 2021 |
| ASRock   | B450M Steel Legend          | [d3004980ee](https://linux-hardware.org/?probe=d3004980ee) | Feb 09, 2021 |
| MSI      | Z77A-G41                    | [171be87aa0](https://linux-hardware.org/?probe=171be87aa0) | Dec 27, 2020 |
| MSI      | H81I                        | [772ce7ff24](https://linux-hardware.org/?probe=772ce7ff24) | Dec 03, 2020 |
| MSI      | Boston                      | [9843e15faa](https://linux-hardware.org/?probe=9843e15faa) | Dec 01, 2020 |
| Gigabyte | F2A68HM-S1                  | [1280ebbedf](https://linux-hardware.org/?probe=1280ebbedf) | Nov 17, 2020 |
| ASUSTek  | P8H61-M LX3 R2.0            | [f61cacc391](https://linux-hardware.org/?probe=f61cacc391) | Oct 05, 2020 |
| MSI      | X470 GAMING PRO             | [6b818c1352](https://linux-hardware.org/?probe=6b818c1352) | Sep 28, 2020 |
| ASUSTek  | PRIME X370-PRO              | [3255a17583](https://linux-hardware.org/?probe=3255a17583) | Sep 28, 2020 |
| MSI      | Z170-A PRO                  | [bcf22d328e](https://linux-hardware.org/?probe=bcf22d328e) | Sep 28, 2020 |
| Intel    | DX79TO AAG28805-400         | [d4cdc0726f](https://linux-hardware.org/?probe=d4cdc0726f) | Sep 26, 2020 |
| MSI      | MPG X570 GAMING PLUS        | [118729faeb](https://linux-hardware.org/?probe=118729faeb) | Sep 23, 2020 |
| ASUSTek  | PRIME B550M-K               | [0dd7682249](https://linux-hardware.org/?probe=0dd7682249) | Sep 08, 2020 |
| ASRock   | P45DE3                      | [3fce267079](https://linux-hardware.org/?probe=3fce267079) | Aug 11, 2020 |
| Lenovo   | 0x36A017AA SDK0J40700 WI... | [5b48876c88](https://linux-hardware.org/?probe=5b48876c88) | Aug 11, 2020 |
| Lenovo   | 0x36A017AA SDK0J40700 WI... | [420e531d0c](https://linux-hardware.org/?probe=420e531d0c) | Aug 11, 2020 |
| Gigabyte | X570 I AORUS PRO WIFI       | [fd8d68081e](https://linux-hardware.org/?probe=fd8d68081e) | Aug 08, 2020 |
| Gigabyte | X570 I AORUS PRO WIFI       | [30d102a39e](https://linux-hardware.org/?probe=30d102a39e) | Aug 07, 2020 |
| Gigabyte | X570 AORUS PRO              | [f6f1267e91](https://linux-hardware.org/?probe=f6f1267e91) | Jul 23, 2020 |
| ASRock   | B250M Pro4                  | [3ad9bafdc1](https://linux-hardware.org/?probe=3ad9bafdc1) | Jul 19, 2020 |
| MSI      | MPG X570 GAMING PLUS        | [43684f5ded](https://linux-hardware.org/?probe=43684f5ded) | Jul 15, 2020 |
| ASUSTek  | P5LD2                       | [caa5d2a038](https://linux-hardware.org/?probe=caa5d2a038) | Jul 13, 2020 |
| Gigabyte | H310M S2H x.x               | [751ba49889](https://linux-hardware.org/?probe=751ba49889) | Jul 09, 2020 |
| ASRock   | Z170 Pro4S                  | [71665893c0](https://linux-hardware.org/?probe=71665893c0) | Jul 08, 2020 |
| ASRock   | Z170 Pro4S                  | [2d7a70bd54](https://linux-hardware.org/?probe=2d7a70bd54) | Jul 06, 2020 |
| Gigabyte | H310M S2H x.x               | [3149f0037a](https://linux-hardware.org/?probe=3149f0037a) | Jul 03, 2020 |
| Gigabyte | H310M S2H x.x               | [9bd5a64d0d](https://linux-hardware.org/?probe=9bd5a64d0d) | Jun 25, 2020 |
| ASUSTek  | WS X299 SAGE                | [bfc9505d4b](https://linux-hardware.org/?probe=bfc9505d4b) | Jun 05, 2020 |
| MSI      | Boston                      | [48a3bf1932](https://linux-hardware.org/?probe=48a3bf1932) | Jun 02, 2020 |
| ASUSTek  | Z97-A                       | [32fc505cab](https://linux-hardware.org/?probe=32fc505cab) | May 17, 2020 |
| MSI      | Z170A GAMING M3             | [369ce228c3](https://linux-hardware.org/?probe=369ce228c3) | May 16, 2020 |
| MSI      | B360-A PRO                  | [c42cb75770](https://linux-hardware.org/?probe=c42cb75770) | Apr 24, 2020 |
| ASUSTek  | PRIME X570-PRO              | [61c4420d0e](https://linux-hardware.org/?probe=61c4420d0e) | Mar 22, 2020 |
| Gigabyte | Z77X-D3H                    | [76af4a7e0b](https://linux-hardware.org/?probe=76af4a7e0b) | Mar 21, 2020 |
| ASRock   | P45DE3                      | [fffef664cd](https://linux-hardware.org/?probe=fffef664cd) | Mar 18, 2020 |
| MSI      | B75A-G43                    | [9683ec9bd4](https://linux-hardware.org/?probe=9683ec9bd4) | Mar 16, 2020 |
| ASUSTek  | PRIME X570-PRO              | [95eb08349e](https://linux-hardware.org/?probe=95eb08349e) | Mar 15, 2020 |
| ASUSTek  | PRIME X570-PRO              | [e30b449cc4](https://linux-hardware.org/?probe=e30b449cc4) | Mar 08, 2020 |
| ASUSTek  | Z97-A                       | [8bc7b7979a](https://linux-hardware.org/?probe=8bc7b7979a) | Mar 01, 2020 |
| MSI      | 990FXA-GD65                 | [adc15c7147](https://linux-hardware.org/?probe=adc15c7147) | Feb 24, 2020 |
| Gigabyte | B450 AORUS ELITE            | [b17f2abd3e](https://linux-hardware.org/?probe=b17f2abd3e) | Feb 20, 2020 |
| Gigabyte | H81M-S1                     | [754bdf88c1](https://linux-hardware.org/?probe=754bdf88c1) | Jan 26, 2020 |
| ASUSTek  | ROG STRIX Z390-F GAMING     | [1eb5f177d1](https://linux-hardware.org/?probe=1eb5f177d1) | Jan 13, 2020 |
| Dell     | 0D28YY A01                  | [be51211fe3](https://linux-hardware.org/?probe=be51211fe3) | Dec 09, 2019 |
| Gigabyte | H81M-S1                     | [57524ab581](https://linux-hardware.org/?probe=57524ab581) | Dec 03, 2019 |
| ASUSTek  | VM60                        | [4842363a0b](https://linux-hardware.org/?probe=4842363a0b) | Nov 14, 2019 |
| ASRock   | B250M Pro4                  | [8beb57338d](https://linux-hardware.org/?probe=8beb57338d) | Oct 02, 2019 |
| ASUSTek  | A8N32-SLI-Deluxe            | [abc398724a](https://linux-hardware.org/?probe=abc398724a) | Sep 16, 2019 |
| ASUSTek  | A8N32-SLI-Deluxe            | [f6acac9fc8](https://linux-hardware.org/?probe=f6acac9fc8) | Sep 15, 2019 |
| ASUSTek  | A8N32-SLI-Deluxe            | [d2b5c32d2f](https://linux-hardware.org/?probe=d2b5c32d2f) | Sep 15, 2019 |
| HP       | 1495                        | [3d9e77ae8a](https://linux-hardware.org/?probe=3d9e77ae8a) | Jul 23, 2019 |
| Lenovo   | MAHOBAY 0B98401 PRO         | [46e1a9fc55](https://linux-hardware.org/?probe=46e1a9fc55) | Jul 04, 2019 |
| ASRock   | B250M Pro4                  | [3a8d19c8fc](https://linux-hardware.org/?probe=3a8d19c8fc) | Jun 22, 2019 |
| Gigabyte | 970-GAMING                  | [aa1385d100](https://linux-hardware.org/?probe=aa1385d100) | Jun 03, 2019 |
| Intel    | DQ35JO AAD82085-807         | [7f57ad053d](https://linux-hardware.org/?probe=7f57ad053d) | May 20, 2019 |
| Dell     | 0KP561                      | [bba0fe2672](https://linux-hardware.org/?probe=bba0fe2672) | Apr 05, 2019 |
| Dell     | 0KP561                      | [f3085d1ae9](https://linux-hardware.org/?probe=f3085d1ae9) | Apr 04, 2019 |
| ASRock   | H370M-ITX/ac                | [ba39531b87](https://linux-hardware.org/?probe=ba39531b87) | Mar 31, 2019 |
| HP       | 18E7                        | [19df4fb560](https://linux-hardware.org/?probe=19df4fb560) | Feb 22, 2019 |
| ABIT     | KN9 Series                  | [10015b723b](https://linux-hardware.org/?probe=10015b723b) | Feb 04, 2019 |
| ASRock   | B250M Pro4                  | [b702949950](https://linux-hardware.org/?probe=b702949950) | Dec 19, 2018 |
| Gigabyte | AX370M-Gaming 3-CF          | [158fb83dcc](https://linux-hardware.org/?probe=158fb83dcc) | Nov 13, 2018 |
| ASRock   | B250M Pro4                  | [a00ad66604](https://linux-hardware.org/?probe=a00ad66604) | Oct 24, 2018 |
| ASRock   | B250M Pro4                  | [9c47ffacd5](https://linux-hardware.org/?probe=9c47ffacd5) | Oct 24, 2018 |
| ECS      | H55H-3.8L                   | [7e782321c8](https://linux-hardware.org/?probe=7e782321c8) | Mar 31, 2018 |
| ASUSTek  | M2N-MX SE                   | [78791d4918](https://linux-hardware.org/?probe=78791d4918) | Sep 13, 2017 |
| ASUSTek  | P8H67                       | [e36d00c6f9](https://linux-hardware.org/?probe=e36d00c6f9) | Jul 21, 2017 |
| ECS      | nVidia-nForce               | [db8fd734f9](https://linux-hardware.org/?probe=db8fd734f9) | May 16, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 10       | 7.69%   |
| Arch Rolling                 | 9        | 6.92%   |
| Ubuntu 22.04                 | 6        | 4.62%   |
| Ubuntu 18.04                 | 6        | 4.62%   |
| ROSA R11                     | 6        | 4.62%   |
| OpenMandriva 4.3             | 6        | 4.62%   |
| ROSA R8.1                    | 4        | 3.08%   |
| Manjaro                      | 4        | 3.08%   |
| Kubuntu 20.04                | 4        | 3.08%   |
| Ubuntu 21.10                 | 3        | 2.31%   |
| ROSA 12.2                    | 3        | 2.31%   |
| Gentoo 2.6                   | 3        | 2.31%   |
| Fedora 34                    | 3        | 2.31%   |
| Fedora 31                    | 3        | 2.31%   |
| Debian 12                    | 3        | 2.31%   |
| Pop!_OS 22.04                | 2        | 1.54%   |
| Pop!_OS 21.04                | 2        | 1.54%   |
| OpenMandriva 4.2             | 2        | 1.54%   |
| OpenMandriva 23.03           | 2        | 1.54%   |
| Nobara 37                    | 2        | 1.54%   |
| KDE neon 20.04               | 2        | 1.54%   |
| Fedora 36                    | 2        | 1.54%   |
| Debian Testing               | 2        | 1.54%   |
| Arch                         | 2        | 1.54%   |
| Zorin 16                     | 1        | 0.77%   |
| Xubuntu 18.04                | 1        | 0.77%   |
| Ubuntu MATE 22.04            | 1        | 0.77%   |
| Ubuntu MATE 20.04            | 1        | 0.77%   |
| Ubuntu 23.04                 | 1        | 0.77%   |
| Ubuntu 21.04                 | 1        | 0.77%   |
| Ubuntu 19.10                 | 1        | 0.77%   |
| Ubuntu 19.04                 | 1        | 0.77%   |
| Ubuntu 16.04                 | 1        | 0.77%   |
| ROSA R9                      | 1        | 0.77%   |
| ROSA R11.1                   | 1        | 0.77%   |
| ROSA R10                     | 1        | 0.77%   |
| ROSA 12.4                    | 1        | 0.77%   |
| ROSA 12                      | 1        | 0.77%   |
| Pop!_OS 21.10                | 1        | 0.77%   |
| openSUSE Tumbleweed-XXXXXXXX | 1        | 0.77%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 30       | 23.62%  |
| ROSA         | 18       | 14.17%  |
| OpenMandriva | 11       | 8.66%   |
| Arch         | 11       | 8.66%   |
| Fedora       | 10       | 7.87%   |
| Debian       | 8        | 6.3%    |
| Manjaro      | 7        | 5.51%   |
| Kubuntu      | 5        | 3.94%   |
| Pop!_OS      | 4        | 3.15%   |
| Gentoo       | 4        | 3.15%   |
| Nobara       | 3        | 2.36%   |
| Ubuntu MATE  | 2        | 1.57%   |
| openSUSE     | 2        | 1.57%   |
| Linux Mint   | 2        | 1.57%   |
| KDE neon     | 2        | 1.57%   |
| Zorin        | 1        | 0.79%   |
| Xubuntu      | 1        | 0.79%   |
| MX           | 1        | 0.79%   |
| LMDE         | 1        | 0.79%   |
| EndeavourOS  | 1        | 0.79%   |
| Elementary   | 1        | 0.79%   |
| Clear Linux  | 1        | 0.79%   |
| ArcoLinux    | 1        | 0.79%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003             | 6        | 4.26%   |
| 6.1.0-13-amd64                      | 3        | 2.13%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 3        | 2.13%   |
| 6.2.6-desktop-1omv2390              | 2        | 1.42%   |
| 5.5.2-1-MANJARO                     | 2        | 1.42%   |
| 5.4.0-53-generic                    | 2        | 1.42%   |
| 5.4.0-42-generic                    | 2        | 1.42%   |
| 5.4.0-26-generic                    | 2        | 1.42%   |
| 5.11.0-25-generic                   | 2        | 1.42%   |
| 5.10.14-desktop-1omv4002            | 2        | 1.42%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 2        | 1.42%   |
| 6.6.3-arch1-1                       | 1        | 0.71%   |
| 6.6.2-201.fc39.x86_64               | 1        | 0.71%   |
| 6.5.6-76060506-generic              | 1        | 0.71%   |
| 6.5.0-14-generic                    | 1        | 0.71%   |
| 6.4.10-202.fsync.fc38.x86_64        | 1        | 0.71%   |
| 6.2.6-201.fsync.fc37.x86_64         | 1        | 0.71%   |
| 6.2.6-1-default                     | 1        | 0.71%   |
| 6.2.0-23-generic                    | 1        | 0.71%   |
| 6.1.9-200.fsync.fc37.x86_64         | 1        | 0.71%   |
| 6.1.68-1-lts                        | 1        | 0.71%   |
| 6.1.38-generic-1rosa2021.1-x86_64   | 1        | 0.71%   |
| 6.1.29-1-lts                        | 1        | 0.71%   |
| 6.1.14-201.fsync.fc37.x86_64        | 1        | 0.71%   |
| 6.1.12-1-MANJARO                    | 1        | 0.71%   |
| 6.1.1-desktop-1omv2290              | 1        | 0.71%   |
| 6.0.12-76060006-generic             | 1        | 0.71%   |
| 6.0.11-x64v1-xanmod1-1              | 1        | 0.71%   |
| 6.0.11-arch1-1                      | 1        | 0.71%   |
| 6.0.1-zen2-1-zen                    | 1        | 0.71%   |
| 5.8.10-zen1-1-zen                   | 1        | 0.71%   |
| 5.8.10-arch1-1                      | 1        | 0.71%   |
| 5.8.0-63-generic                    | 1        | 0.71%   |
| 5.8.0-1-tkg-pds                     | 1        | 0.71%   |
| 5.7.0-2-amd64                       | 1        | 0.71%   |
| 5.6.11-gentoo                       | 1        | 0.71%   |
| 5.6.10-947.native                   | 1        | 0.71%   |
| 5.5.9-200.fc31.x86_64               | 1        | 0.71%   |
| 5.4.8-200.fc31.x86_64               | 1        | 0.71%   |
| 5.4.48-gentoo                       | 1        | 0.71%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 15       | 11.11%  |
| 4.15.0   | 12       | 8.89%   |
| 5.15.0   | 8        | 5.93%   |
| 5.16.7   | 6        | 4.44%   |
| 5.13.0   | 5        | 3.7%    |
| 5.11.0   | 5        | 3.7%    |
| 6.2.6    | 4        | 2.96%   |
| 6.1.0    | 3        | 2.22%   |
| 5.10.118 | 3        | 2.22%   |
| 5.10.0   | 3        | 2.22%   |
| 6.0.11   | 2        | 1.48%   |
| 5.8.10   | 2        | 1.48%   |
| 5.8.0    | 2        | 1.48%   |
| 5.5.2    | 2        | 1.48%   |
| 5.3.0    | 2        | 1.48%   |
| 5.19.0   | 2        | 1.48%   |
| 5.10.14  | 2        | 1.48%   |
| 5.0.0    | 2        | 1.48%   |
| 4.9.9    | 2        | 1.48%   |
| 6.6.3    | 1        | 0.74%   |
| 6.6.2    | 1        | 0.74%   |
| 6.5.6    | 1        | 0.74%   |
| 6.5.0    | 1        | 0.74%   |
| 6.4.10   | 1        | 0.74%   |
| 6.2.0    | 1        | 0.74%   |
| 6.1.9    | 1        | 0.74%   |
| 6.1.68   | 1        | 0.74%   |
| 6.1.38   | 1        | 0.74%   |
| 6.1.29   | 1        | 0.74%   |
| 6.1.14   | 1        | 0.74%   |
| 6.1.12   | 1        | 0.74%   |
| 6.1.1    | 1        | 0.74%   |
| 6.0.12   | 1        | 0.74%   |
| 6.0.1    | 1        | 0.74%   |
| 5.7.0    | 1        | 0.74%   |
| 5.6.11   | 1        | 0.74%   |
| 5.6.10   | 1        | 0.74%   |
| 5.5.9    | 1        | 0.74%   |
| 5.4.8    | 1        | 0.74%   |
| 5.4.48   | 1        | 0.74%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 20       | 14.93%  |
| 4.15    | 12       | 8.96%   |
| 5.15    | 11       | 8.21%   |
| 5.10    | 11       | 8.21%   |
| 6.1     | 10       | 7.46%   |
| 5.13    | 8        | 5.97%   |
| 5.16    | 7        | 5.22%   |
| 5.11    | 7        | 5.22%   |
| 4.9     | 6        | 4.48%   |
| 6.2     | 5        | 3.73%   |
| 6.0     | 4        | 2.99%   |
| 5.8     | 4        | 2.99%   |
| 5.3     | 4        | 2.99%   |
| 5.5     | 3        | 2.24%   |
| 5.18    | 3        | 2.24%   |
| 6.6     | 2        | 1.49%   |
| 6.5     | 2        | 1.49%   |
| 5.6     | 2        | 1.49%   |
| 5.19    | 2        | 1.49%   |
| 5.14    | 2        | 1.49%   |
| 5.0     | 2        | 1.49%   |
| 4.19    | 2        | 1.49%   |
| 6.4     | 1        | 0.75%   |
| 5.7     | 1        | 0.75%   |
| 5.17    | 1        | 0.75%   |
| 5.1     | 1        | 0.75%   |
| 4.1     | 1        | 0.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 116      | 94.31%  |
| i686   | 6        | 4.88%   |
| armv7l | 1        | 0.81%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 47       | 36.72%  |
| KDE5       | 31       | 24.22%  |
| Unknown    | 15       | 11.72%  |
| KDE4       | 11       | 8.59%   |
| XFCE       | 6        | 4.69%   |
| X-Cinnamon | 5        | 3.91%   |
| MATE       | 4        | 3.13%   |
| sway       | 2        | 1.56%   |
| LXQt       | 2        | 1.56%   |
| i3         | 2        | 1.56%   |
| Pantheon   | 1        | 0.78%   |
| KDE        | 1        | 0.78%   |
| Budgie     | 1        | 0.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 95       | 76%     |
| Wayland | 23       | 18.4%   |
| Unknown | 5        | 4%      |
| Web     | 1        | 0.8%    |
| Tty     | 1        | 0.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 52       | 41.6%   |
| SDDM    | 25       | 20%     |
| GDM     | 15       | 12%     |
| GDM3    | 12       | 9.6%    |
| KDM     | 11       | 8.8%    |
| LightDM | 7        | 5.6%    |
| TDM     | 3        | 2.4%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 58       | 46.03%  |
| Unknown | 24       | 19.05%  |
| et_EE   | 20       | 15.87%  |
| ru_RU   | 13       | 10.32%  |
| en_GB   | 5        | 3.97%   |
| pl_PL   | 2        | 1.59%   |
| fr_FR   | 1        | 0.79%   |
| en_IE   | 1        | 0.79%   |
| de_DE   | 1        | 0.79%   |
| C       | 1        | 0.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 73       | 58.4%   |
| EFI  | 52       | 41.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 87       | 69.6%   |
| Btrfs   | 18       | 14.4%   |
| Overlay | 12       | 9.6%    |
| Unknown | 6        | 4.8%    |
| Xfs     | 1        | 0.8%    |
| Ext3    | 1        | 0.8%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 51       | 41.13%  |
| GPT     | 50       | 40.32%  |
| MBR     | 23       | 18.55%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 90       | 71.43%  |
| Yes       | 36       | 28.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 82       | 65.6%   |
| Yes       | 43       | 34.4%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 32       | 26.02%  |
| MSI                 | 24       | 19.51%  |
| Gigabyte Technology | 23       | 18.7%   |
| ASRock              | 10       | 8.13%   |
| Hewlett-Packard     | 8        | 6.5%    |
| Lenovo              | 6        | 4.88%   |
| Dell                | 6        | 4.88%   |
| Intel               | 5        | 4.07%   |
| ECS                 | 4        | 3.25%   |
| OEM                 | 1        | 0.81%   |
| Huanan              | 1        | 0.81%   |
| Fujitsu             | 1        | 0.81%   |
| ABIT                | 1        | 0.81%   |
| Unknown             | 1        | 0.81%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| ASUS All Series                          | 4        | 3.25%   |
| MSI MS-7C91                              | 2        | 1.63%   |
| MSI MS-7C02                              | 2        | 1.63%   |
| MSI MS-7758                              | 2        | 1.63%   |
| HP Compaq 8100 Elite SFF PC              | 2        | 1.63%   |
| Gigabyte X570 AORUS PRO                  | 2        | 1.63%   |
| Gigabyte Q87M-D2H                        | 2        | 1.63%   |
| ASUS ROG STRIX B550-F GAMING             | 2        | 1.63%   |
| ASUS PRIME B550M-K                       | 2        | 1.63%   |
| OEM Intel H81                            | 1        | 0.81%   |
| MSI MS-7D59                              | 1        | 0.81%   |
| MSI MS-7D43                              | 1        | 0.81%   |
| MSI MS-7C83                              | 1        | 0.81%   |
| MSI MS-7C75                              | 1        | 0.81%   |
| MSI MS-7C37                              | 1        | 0.81%   |
| MSI MS-7B98                              | 1        | 0.81%   |
| MSI MS-7B86                              | 1        | 0.81%   |
| MSI MS-7B79                              | 1        | 0.81%   |
| MSI MS-7B22                              | 1        | 0.81%   |
| MSI MS-7B18                              | 1        | 0.81%   |
| MSI MS-7A74                              | 1        | 0.81%   |
| MSI MS-7996                              | 1        | 0.81%   |
| MSI MS-7978                              | 1        | 0.81%   |
| MSI MS-7971                              | 1        | 0.81%   |
| MSI MS-7851                              | 1        | 0.81%   |
| MSI MS-7640                              | 1        | 0.81%   |
| MSI MS-7267                              | 1        | 0.81%   |
| MSI FJ418AA-UUW a6522.SC                 | 1        | 0.81%   |
| Lenovo ThinkStation D20 4158GK1          | 1        | 0.81%   |
| Lenovo ThinkCentre M75s Gen 2 11JB002GPB | 1        | 0.81%   |
| Lenovo ThinkCentre M72z 3543C8G          | 1        | 0.81%   |
| Lenovo ThinkCentre M58 7360WQK           | 1        | 0.81%   |
| Lenovo H50-55 90BF005SMW                 | 1        | 0.81%   |
| Lenovo Erazer X310 90AV000CMT            | 1        | 0.81%   |
| Intel DX79TO AAG28805-400                | 1        | 0.81%   |
| Intel DQ35JO AAD82085-807                | 1        | 0.81%   |
| Intel DP67BG AAG10491-305                | 1        | 0.81%   |
| Intel DH61DL AAG14066-205                | 1        | 0.81%   |
| Intel D33217GKE G69901-205               | 1        | 0.81%   |
| Huanan X79 V2.47                         | 1        | 0.81%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 8        | 6.5%    |
| Dell OptiPlex       | 5        | 4.07%   |
| ASUS ROG            | 5        | 4.07%   |
| HP Compaq           | 4        | 3.25%   |
| Gigabyte X570       | 4        | 3.25%   |
| ASUS All            | 4        | 3.25%   |
| Lenovo ThinkCentre  | 3        | 2.44%   |
| ASUS TUF            | 3        | 2.44%   |
| MSI MS-7C91         | 2        | 1.63%   |
| MSI MS-7C02         | 2        | 1.63%   |
| MSI MS-7758         | 2        | 1.63%   |
| HP ProDesk          | 2        | 1.63%   |
| Gigabyte Q87M-D2H   | 2        | 1.63%   |
| OEM Intel           | 1        | 0.81%   |
| MSI MS-7D59         | 1        | 0.81%   |
| MSI MS-7D43         | 1        | 0.81%   |
| MSI MS-7C83         | 1        | 0.81%   |
| MSI MS-7C75         | 1        | 0.81%   |
| MSI MS-7C37         | 1        | 0.81%   |
| MSI MS-7B98         | 1        | 0.81%   |
| MSI MS-7B86         | 1        | 0.81%   |
| MSI MS-7B79         | 1        | 0.81%   |
| MSI MS-7B22         | 1        | 0.81%   |
| MSI MS-7B18         | 1        | 0.81%   |
| MSI MS-7A74         | 1        | 0.81%   |
| MSI MS-7996         | 1        | 0.81%   |
| MSI MS-7978         | 1        | 0.81%   |
| MSI MS-7971         | 1        | 0.81%   |
| MSI MS-7851         | 1        | 0.81%   |
| MSI MS-7640         | 1        | 0.81%   |
| MSI MS-7267         | 1        | 0.81%   |
| MSI FJ418AA-UUW     | 1        | 0.81%   |
| Lenovo ThinkStation | 1        | 0.81%   |
| Lenovo H50-55       | 1        | 0.81%   |
| Lenovo Erazer       | 1        | 0.81%   |
| Intel DX79TO        | 1        | 0.81%   |
| Intel DQ35JO        | 1        | 0.81%   |
| Intel DP67BG        | 1        | 0.81%   |
| Intel DH61DL        | 1        | 0.81%   |
| Intel D33217GKE     | 1        | 0.81%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 15       | 12.2%   |
| 2018    | 14       | 11.38%  |
| 2012    | 12       | 9.76%   |
| 2019    | 10       | 8.13%   |
| 2013    | 9        | 7.32%   |
| 2009    | 8        | 6.5%    |
| 2016    | 7        | 5.69%   |
| 2015    | 6        | 4.88%   |
| 2014    | 6        | 4.88%   |
| 2022    | 5        | 4.07%   |
| 2021    | 5        | 4.07%   |
| 2017    | 5        | 4.07%   |
| 2010    | 5        | 4.07%   |
| 2011    | 4        | 3.25%   |
| 2008    | 3        | 2.44%   |
| 2006    | 3        | 2.44%   |
| 2007    | 2        | 1.63%   |
| 2005    | 2        | 1.63%   |
| 2004    | 1        | 0.81%   |
| Unknown | 1        | 0.81%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 123      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 121      | 97.58%  |
| Enabled  | 3        | 2.42%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 123      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 31       | 25%     |
| 32.01-64.0  | 28       | 22.58%  |
| 8.01-16.0   | 17       | 13.71%  |
| 4.01-8.0    | 15       | 12.1%   |
| 3.01-4.0    | 15       | 12.1%   |
| 64.01-256.0 | 6        | 4.84%   |
| 1.01-2.0    | 4        | 3.23%   |
| 24.01-32.0  | 3        | 2.42%   |
| 2.01-3.0    | 2        | 1.61%   |
| 0.51-1.0    | 2        | 1.61%   |
| 0.01-0.5    | 1        | 0.81%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 33       | 25%     |
| 2.01-3.0   | 29       | 21.97%  |
| 4.01-8.0   | 24       | 18.18%  |
| 0.51-1.0   | 17       | 12.88%  |
| 8.01-16.0  | 11       | 8.33%   |
| 3.01-4.0   | 10       | 7.58%   |
| 0.01-0.5   | 4        | 3.03%   |
| 24.01-32.0 | 2        | 1.52%   |
| 16.01-24.0 | 2        | 1.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 43       | 33.59%  |
| 2      | 35       | 27.34%  |
| 3      | 25       | 19.53%  |
| 4      | 11       | 8.59%   |
| 6      | 8        | 6.25%   |
| 5      | 4        | 3.13%   |
| 7      | 1        | 0.78%   |
| 0      | 1        | 0.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 68       | 55.28%  |
| Yes       | 55       | 44.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 121      | 97.58%  |
| No        | 3        | 2.42%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 80       | 65.04%  |
| Yes       | 43       | 34.96%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 88       | 70.4%   |
| Yes       | 37       | 29.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Estonia | 123      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Tallinn       | 76       | 59.84%  |
| Tartu         | 16       | 12.6%   |
| Haapsalu      | 5        | 3.94%   |
| Rapla         | 3        | 2.36%   |
| Pärnu        | 3        | 2.36%   |
| Tapa          | 2        | 1.57%   |
| Rakvere       | 2        | 1.57%   |
| Paldiski      | 2        | 1.57%   |
| Kohtla-Järve | 2        | 1.57%   |
| Viljandi      | 1        | 0.79%   |
| Valga         | 1        | 0.79%   |
| Vaidasoo      | 1        | 0.79%   |
| Türi         | 1        | 0.79%   |
| Sindi         | 1        | 0.79%   |
| Põlva        | 1        | 0.79%   |
| Maardu        | 1        | 0.79%   |
| Lohkva        | 1        | 0.79%   |
| Kuressaare    | 1        | 0.79%   |
| Kose          | 1        | 0.79%   |
| Kiviõli      | 1        | 0.79%   |
| Kadrina       | 1        | 0.79%   |
| Jõhvi        | 1        | 0.79%   |
| Jaerva vald   | 1        | 0.79%   |
| Hiiumaa       | 1        | 0.79%   |
| Haabneeme     | 1        | 0.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 52       | 80     | 21.85%  |
| WDC                         | 35       | 58     | 14.71%  |
| Seagate                     | 33       | 49     | 13.87%  |
| Kingston                    | 25       | 39     | 10.5%   |
| Crucial                     | 14       | 23     | 5.88%   |
| Toshiba                     | 12       | 12     | 5.04%   |
| Hitachi                     | 10       | 14     | 4.2%    |
| SanDisk                     | 7        | 7      | 2.94%   |
| HGST                        | 6        | 9      | 2.52%   |
| A-DATA Technology           | 6        | 12     | 2.52%   |
| Apacer                      | 3        | 4      | 1.26%   |
| XPG                         | 2        | 2      | 0.84%   |
| Unknown                     | 2        | 2      | 0.84%   |
| Silicon Motion              | 2        | 3      | 0.84%   |
| Patriot                     | 2        | 2      | 0.84%   |
| Maxtor                      | 2        | 2      | 0.84%   |
| KingSpec                    | 2        | 3      | 0.84%   |
| Intel                       | 2        | 3      | 0.84%   |
| Gigabyte Technology         | 2        | 2      | 0.84%   |
| Corsair                     | 2        | 2      | 0.84%   |
| China                       | 2        | 2      | 0.84%   |
| ADATA Technology            | 2        | 2      | 0.84%   |
| ZADAK                       | 1        | 1      | 0.42%   |
| Team                        | 1        | 2      | 0.42%   |
| SPCC                        | 1        | 1      | 0.42%   |
| SK hynix                    | 1        | 1      | 0.42%   |
| Plextor                     | 1        | 1      | 0.42%   |
| Micron/Crucial Technology   | 1        | 1      | 0.42%   |
| KIOXIA-EXCERIA              | 1        | 1      | 0.42%   |
| Kingston Technology Company | 1        | 1      | 0.42%   |
| Integral                    | 1        | 1      | 0.42%   |
| Inateck                     | 1        | 1      | 0.42%   |
| i-FlashDisk                 | 1        | 1      | 0.42%   |
| ASMT                        | 1        | 1      | 0.42%   |
| Apple                       | 1        | 1      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                                         | 7        | 2.46%   |
| Seagate ST2000DM008-2FR102 2TB                                    | 5        | 1.75%   |
| Seagate ST1000DM010-2EP102 1TB                                    | 5        | 1.75%   |
| Kingston SA400S37240G 240GB SSD                                   | 5        | 1.75%   |
| Samsung SSD 860 EVO 250GB                                         | 4        | 1.4%    |
| Samsung NVMe SSD Drive 1TB                                        | 4        | 1.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB               | 4        | 1.4%    |
| Samsung HD103SJ 1TB                                               | 4        | 1.4%    |
| Seagate ST500LT012-9WS142 500GB                                   | 3        | 1.05%   |
| Seagate ST500DM002-1BD142 500GB                                   | 3        | 1.05%   |
| Samsung SSD 960 PRO 512GB                                         | 3        | 1.05%   |
| Samsung SSD 850 EVO 500GB                                         | 3        | 1.05%   |
| Samsung MZ7TY128HDHP-000L1 128GB SSD                              | 3        | 1.05%   |
| Samsung HD080HJ 80GB                                              | 3        | 1.05%   |
| Kingston SA400S37120G 120GB SSD                                   | 3        | 1.05%   |
| Crucial CT500MX500SSD1 500GB                                      | 3        | 1.05%   |
| A-DATA SX8200PNP 512GB                                            | 3        | 1.05%   |
| WDC WD10EADS-00M2B0 1TB                                           | 2        | 0.7%    |
| Unknown ArtisanTribute-512GB                                      | 2        | 0.7%    |
| Toshiba HDWD130 3TB                                               | 2        | 0.7%    |
| Toshiba DT01ACA100 1TB                                            | 2        | 0.7%    |
| Seagate ST3250318AS 250GB                                         | 2        | 0.7%    |
| Seagate ST1000DM003-1SB102 1TB                                    | 2        | 0.7%    |
| Seagate ST1000DM003-1ER162 1TB                                    | 2        | 0.7%    |
| Sandisk WD Blue SN570 1TB                                         | 2        | 0.7%    |
| Samsung SSD 970 EVO Plus 500GB                                    | 2        | 0.7%    |
| Samsung SSD 870 QVO 1TB                                           | 2        | 0.7%    |
| Samsung SSD 860 EVO 500GB                                         | 2        | 0.7%    |
| Samsung SSD 850 PRO 256GB                                         | 2        | 0.7%    |
| Samsung SSD 840 PRO Series 128GB                                  | 2        | 0.7%    |
| Samsung SP0802N 80GB                                              | 2        | 0.7%    |
| Kingston SUV400S37240G 240GB SSD                                  | 2        | 0.7%    |
| Kingston SA400S37480G 480GB SSD                                   | 2        | 0.7%    |
| Hitachi HTS723225L9A360 250GB                                     | 2        | 0.7%    |
| HGST HTS541010A9E680 1TB                                          | 2        | 0.7%    |
| Crucial CT2000MX500SSD1 2TB                                       | 2        | 0.7%    |
| Crucial CT128MX100SSD1 128GB                                      | 2        | 0.7%    |
| Crucial CT1000MX500SSD1 1TB                                       | 2        | 0.7%    |
| Apacer AS350 512GB SSD                                            | 2        | 0.7%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 512GB | 2        | 0.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 33       | 49     | 29.73%  |
| WDC                 | 32       | 49     | 28.83%  |
| Samsung Electronics | 16       | 20     | 14.41%  |
| Toshiba             | 11       | 11     | 9.91%   |
| Hitachi             | 10       | 14     | 9.01%   |
| HGST                | 6        | 9      | 5.41%   |
| Maxtor              | 2        | 2      | 1.8%    |
| Apple               | 1        | 1      | 0.9%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 30       | 38     | 31.25%  |
| Kingston            | 19       | 29     | 19.79%  |
| Crucial             | 14       | 23     | 14.58%  |
| WDC                 | 5        | 7      | 5.21%   |
| SanDisk             | 5        | 5      | 5.21%   |
| A-DATA Technology   | 4        | 9      | 4.17%   |
| Apacer              | 3        | 4      | 3.13%   |
| Patriot             | 2        | 2      | 2.08%   |
| KingSpec            | 2        | 3      | 2.08%   |
| Corsair             | 2        | 2      | 2.08%   |
| China               | 2        | 2      | 2.08%   |
| Team                | 1        | 2      | 1.04%   |
| SPCC                | 1        | 1      | 1.04%   |
| Plextor             | 1        | 1      | 1.04%   |
| Intel               | 1        | 1      | 1.04%   |
| Integral            | 1        | 1      | 1.04%   |
| i-FlashDisk         | 1        | 1      | 1.04%   |
| Gigabyte Technology | 1        | 1      | 1.04%   |
| ASMT                | 1        | 1      | 1.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 83       | 155    | 42.13%  |
| SSD     | 71       | 133    | 36.04%  |
| NVMe    | 39       | 54     | 19.8%   |
| Unknown | 4        | 4      | 2.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 114      | 287    | 72.15%  |
| NVMe | 39       | 54     | 24.68%  |
| SAS  | 5        | 5      | 3.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 93       | 175    | 54.07%  |
| 0.51-1.0   | 46       | 67     | 26.74%  |
| 1.01-2.0   | 17       | 23     | 9.88%   |
| 3.01-4.0   | 5        | 5      | 2.91%   |
| 2.01-3.0   | 5        | 12     | 2.91%   |
| 4.01-10.0  | 5        | 5      | 2.91%   |
| 10.01-20.0 | 1        | 1      | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 26       | 19.85%  |
| 101-250        | 24       | 18.32%  |
| 1001-2000      | 17       | 12.98%  |
| More than 3000 | 15       | 11.45%  |
| 501-1000       | 14       | 10.69%  |
| 1-20           | 13       | 9.92%   |
| 51-100         | 7        | 5.34%   |
| 2001-3000      | 6        | 4.58%   |
| Unknown        | 5        | 3.82%   |
| 21-50          | 4        | 3.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 48       | 36.36%  |
| 21-50          | 17       | 12.88%  |
| 101-250        | 16       | 12.12%  |
| 501-1000       | 11       | 8.33%   |
| 1001-2000      | 10       | 7.58%   |
| 251-500        | 9        | 6.82%   |
| 51-100         | 8        | 6.06%   |
| More than 3000 | 7        | 5.3%    |
| Unknown        | 5        | 3.79%   |
| 2001-3000      | 1        | 0.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| Crucial CT128MX100SSD1 128GB                 | 2        | 3      | 6.9%    |
| WDC WD60EFRX-68MYMN1 6TB                     | 1        | 1      | 3.45%   |
| WDC WD5002AALX-00J37A0 500GB                 | 1        | 1      | 3.45%   |
| WDC WD5000BPVT-00HXZT1 500GB                 | 1        | 1      | 3.45%   |
| WDC WD5000AAKX-00ERMA0 500GB                 | 1        | 1      | 3.45%   |
| WDC WD20EZRX-00DC0B0 2TB                     | 1        | 2      | 3.45%   |
| WDC WD20EARX-00PASB0 2TB                     | 1        | 1      | 3.45%   |
| WDC WD10PURX-64E5EY0 1TB                     | 1        | 1      | 3.45%   |
| WDC WD10EAVS-00D7B1 1TB                      | 1        | 1      | 3.45%   |
| WDC WD10EADS-00M2B0 1TB                      | 1        | 2      | 3.45%   |
| Toshiba MK6475GSX 640GB                      | 1        | 1      | 3.45%   |
| Toshiba MK3261GSYN 320GB                     | 1        | 1      | 3.45%   |
| Seagate ST500DM002-1BD142 500GB              | 1        | 1      | 3.45%   |
| Seagate ST340016A 40GB                       | 1        | 2      | 3.45%   |
| Seagate ST31000528AS 1TB                     | 1        | 1      | 3.45%   |
| Seagate ST1000DM010-2EP102 1TB               | 1        | 1      | 3.45%   |
| Samsung Electronics SSD 840 PRO Series 128GB | 1        | 1      | 3.45%   |
| Samsung Electronics SP0802N 80GB             | 1        | 1      | 3.45%   |
| Samsung Electronics HD642JJ 640GB            | 1        | 1      | 3.45%   |
| Samsung Electronics HD501LJ 500GB            | 1        | 1      | 3.45%   |
| Samsung Electronics HD103SJ 1TB              | 1        | 1      | 3.45%   |
| Samsung Electronics HD080HJ 80GB             | 1        | 1      | 3.45%   |
| Patriot P210 256GB SSD                       | 1        | 1      | 3.45%   |
| Patriot Burst 480GB SSD                      | 1        | 1      | 3.45%   |
| Maxtor STM3250310AS 250GB                    | 1        | 1      | 3.45%   |
| Hitachi HDS721680PLA380 80GB                 | 1        | 1      | 3.45%   |
| Hitachi HDS721010DLE630 1TB                  | 1        | 1      | 3.45%   |
| Crucial CT256MX100SSD1 256GB                 | 1        | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 11     | 29.63%  |
| Samsung Electronics | 5        | 6      | 18.52%  |
| Seagate             | 4        | 5      | 14.81%  |
| Crucial             | 3        | 4      | 11.11%  |
| Toshiba             | 2        | 2      | 7.41%   |
| Patriot             | 2        | 2      | 7.41%   |
| Hitachi             | 2        | 2      | 7.41%   |
| Maxtor              | 1        | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 11     | 38.1%   |
| Seagate             | 4        | 5      | 19.05%  |
| Samsung Electronics | 4        | 5      | 19.05%  |
| Toshiba             | 2        | 2      | 9.52%   |
| Hitachi             | 2        | 2      | 9.52%   |
| Maxtor              | 1        | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 26     | 79.17%  |
| SSD  | 5        | 7      | 20.83%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 63       | 145    | 43.45%  |
| Detected | 57       | 167    | 39.31%  |
| Malfunc  | 24       | 33     | 16.55%  |
| Failed   | 1        | 1      | 0.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 77       | 42.54%  |
| AMD                          | 40       | 22.1%   |
| Samsung Electronics          | 17       | 9.39%   |
| Kingston Technology Company  | 8        | 4.42%   |
| Marvell Technology Group     | 6        | 3.31%   |
| ADATA Technology             | 6        | 3.31%   |
| Nvidia                       | 5        | 2.76%   |
| SanDisk                      | 4        | 2.21%   |
| ASMedia Technology           | 4        | 2.21%   |
| Silicon Motion               | 3        | 1.66%   |
| VIA Technologies             | 2        | 1.1%    |
| JMicron Technology           | 2        | 1.1%    |
| Toshiba America Info Systems | 1        | 0.55%   |
| SK hynix                     | 1        | 0.55%   |
| Silicon Image                | 1        | 0.55%   |
| Phison Electronics           | 1        | 0.55%   |
| Micron/Crucial Technology    | 1        | 0.55%   |
| KIOXIA                       | 1        | 0.55%   |
| Adaptec                      | 1        | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 22       | 10.14%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 12       | 5.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12       | 5.53%   |
| AMD 500 Series Chipset SATA Controller                                                  | 9        | 4.15%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9        | 4.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 3.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 3.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 2.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 2.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5        | 2.3%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 2.3%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 2.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 2.3%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 5        | 2.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 1.84%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 1.84%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 1.84%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 3        | 1.38%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 1.38%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 1.38%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 2        | 0.92%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 0.92%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 2        | 0.92%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 2        | 0.92%   |
| Nvidia CK804 Serial ATA Controller                                                      | 2        | 0.92%   |
| Nvidia CK804 IDE                                                                        | 2        | 0.92%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                          | 2        | 0.92%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.92%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.92%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 0.92%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2        | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 0.92%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.92%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.92%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 0.92%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 0.92%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)                     | 1        | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 106      | 60.92%  |
| NVMe | 39       | 22.41%  |
| IDE  | 24       | 13.79%  |
| RAID | 4        | 2.3%    |
| SCSI | 1        | 0.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 77       | 62.6%   |
| AMD                   | 45       | 36.59%  |
| Marvell Semiconductor | 1        | 0.81%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor                                  | 6        | 4.88%   |
| AMD Ryzen 5 3600 6-Core Processor                                   | 4        | 3.25%   |
| Intel Core i3-4130 CPU @ 3.40GHz                                    | 3        | 2.44%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz                                | 3        | 2.44%   |
| Intel Core i7-7700 CPU @ 3.60GHz                                    | 2        | 1.63%   |
| Intel Core i7-4790 CPU @ 3.60GHz                                    | 2        | 1.63%   |
| Intel Core i5-9600K CPU @ 3.70GHz                                   | 2        | 1.63%   |
| Intel Core i5-4690K CPU @ 3.50GHz                                   | 2        | 1.63%   |
| Intel Core i5-4590 CPU @ 3.30GHz                                    | 2        | 1.63%   |
| Intel Core i5-2500 CPU @ 3.30GHz                                    | 2        | 1.63%   |
| Intel Core i3-3217U CPU @ 1.80GHz                                   | 2        | 1.63%   |
| AMD Ryzen 9 7950X 16-Core Processor                                 | 2        | 1.63%   |
| AMD Ryzen 9 3900X 12-Core Processor                                 | 2        | 1.63%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics                          | 2        | 1.63%   |
| AMD Ryzen 5 5600X 6-Core Processor                                  | 2        | 1.63%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+                          | 2        | 1.63%   |
| Marvell Semiconductor Marvell Armada 370/XP (Device Tree) Processor | 1        | 0.81%   |
| Intel Xeon CPU E5620 @ 2.40GHz                                      | 1        | 0.81%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz                                  | 1        | 0.81%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz                                 | 1        | 0.81%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz                                 | 1        | 0.81%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz                              | 1        | 0.81%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz                         | 1        | 0.81%   |
| Intel Pentium D CPU 2.80GHz                                         | 1        | 0.81%   |
| Intel Pentium CPU G850 @ 2.90GHz                                    | 1        | 0.81%   |
| Intel Pentium CPU G4560T @ 2.90GHz                                  | 1        | 0.81%   |
| Intel Pentium CPU G2120 @ 3.10GHz                                   | 1        | 0.81%   |
| Intel Pentium CPU G2030 @ 3.00GHz                                   | 1        | 0.81%   |
| Intel Pentium 4 CPU 3.00GHz                                         | 1        | 0.81%   |
| Intel Core i9-9900K CPU @ 3.60GHz                                   | 1        | 0.81%   |
| Intel Core i9-7940X CPU @ 3.10GHz                                   | 1        | 0.81%   |
| Intel Core i7-8700K CPU @ 3.70GHz                                   | 1        | 0.81%   |
| Intel Core i7-8700 CPU @ 3.20GHz                                    | 1        | 0.81%   |
| Intel Core i7-6700K CPU @ 4.00GHz                                   | 1        | 0.81%   |
| Intel Core i7-3820 CPU @ 3.60GHz                                    | 1        | 0.81%   |
| Intel Core i7-3770K CPU @ 3.50GHz                                   | 1        | 0.81%   |
| Intel Core i7-10700 CPU @ 2.90GHz                                   | 1        | 0.81%   |
| Intel Core i5-9500 CPU @ 3.00GHz                                    | 1        | 0.81%   |
| Intel Core i5-8400 CPU @ 2.80GHz                                    | 1        | 0.81%   |
| Intel Core i5-7600K CPU @ 3.80GHz                                   | 1        | 0.81%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 26       | 21.14%  |
| AMD Ryzen 7             | 12       | 9.76%   |
| Intel Core i3           | 11       | 8.94%   |
| Intel Core i7           | 10       | 8.13%   |
| AMD Ryzen 5             | 10       | 8.13%   |
| Other                   | 7        | 5.69%   |
| AMD Ryzen 9             | 6        | 4.88%   |
| Intel Core 2 Duo        | 5        | 4.07%   |
| Intel Celeron           | 5        | 4.07%   |
| Intel Xeon              | 4        | 3.25%   |
| Intel Pentium           | 4        | 3.25%   |
| AMD Phenom II X4        | 4        | 3.25%   |
| AMD FX                  | 3        | 2.44%   |
| AMD Athlon 64 X2        | 3        | 2.44%   |
| Intel Core i9           | 2        | 1.63%   |
| AMD Ryzen 7 PRO         | 2        | 1.63%   |
| AMD A10                 | 2        | 1.63%   |
| Intel Pentium Gold      | 1        | 0.81%   |
| Intel Pentium Dual-Core | 1        | 0.81%   |
| Intel Pentium D         | 1        | 0.81%   |
| Intel Pentium 4         | 1        | 0.81%   |
| AMD Ryzen 3 PRO         | 1        | 0.81%   |
| AMD Phenom II X6        | 1        | 0.81%   |
| AMD Athlon XP           | 1        | 0.81%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 38       | 30.89%  |
| 2       | 31       | 25.2%   |
| 6       | 20       | 16.26%  |
| 8       | 19       | 15.45%  |
| 12      | 4        | 3.25%   |
| 1       | 4        | 3.25%   |
| 16      | 3        | 2.44%   |
| 14      | 2        | 1.63%   |
| 3       | 1        | 0.81%   |
| Unknown | 1        | 0.81%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 122      | 99.19%  |
| 2      | 1        | 0.81%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 70       | 56.91%  |
| 1       | 52       | 42.28%  |
| Unknown | 1        | 0.81%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 120      | 97.56%  |
| Unknown        | 2        | 1.63%   |
| 32-bit         | 1        | 0.81%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 38       | 29.23%  |
| 0x306c3    | 10       | 7.69%   |
| 0x306a9    | 9        | 6.92%   |
| 0x08701021 | 7        | 5.38%   |
| 0x206a7    | 5        | 3.85%   |
| 0x08701013 | 5        | 3.85%   |
| 0x906ea    | 4        | 3.08%   |
| 0x906e9    | 4        | 3.08%   |
| 0x1067a    | 4        | 3.08%   |
| 0xa0655    | 3        | 2.31%   |
| 0x90672    | 3        | 2.31%   |
| 0x06000852 | 3        | 2.31%   |
| 0xa0671    | 2        | 1.54%   |
| 0x506e3    | 2        | 1.54%   |
| 0x20655    | 2        | 1.54%   |
| 0x08001138 | 2        | 1.54%   |
| 0x06003106 | 2        | 1.54%   |
| 0x010000db | 2        | 1.54%   |
| 0xf64      | 1        | 0.77%   |
| 0xf4a      | 1        | 0.77%   |
| 0xa0653    | 1        | 0.77%   |
| 0x906ed    | 1        | 0.77%   |
| 0x906eb    | 1        | 0.77%   |
| 0x6fd      | 1        | 0.77%   |
| 0x6fb      | 1        | 0.77%   |
| 0x50654    | 1        | 0.77%   |
| 0x406c3    | 1        | 0.77%   |
| 0x206d7    | 1        | 0.77%   |
| 0x20652    | 1        | 0.77%   |
| 0x10676    | 1        | 0.77%   |
| 0x10661    | 1        | 0.77%   |
| 0x0a601206 | 1        | 0.77%   |
| 0x0a601203 | 1        | 0.77%   |
| 0x0a201016 | 1        | 0.77%   |
| 0x0a201009 | 1        | 0.77%   |
| 0x08600106 | 1        | 0.77%   |
| 0x08600103 | 1        | 0.77%   |
| 0x08108109 | 1        | 0.77%   |
| 0x0810100b | 1        | 0.77%   |
| 0x0800820d | 1        | 0.77%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 18       | 14.63%  |
| Haswell          | 15       | 12.2%   |
| KabyLake         | 14       | 11.38%  |
| IvyBridge        | 10       | 8.13%   |
| SandyBridge      | 8        | 6.5%    |
| Zen 3            | 5        | 4.07%   |
| Westmere         | 5        | 4.07%   |
| Penryn           | 5        | 4.07%   |
| K10              | 5        | 4.07%   |
| Skylake          | 4        | 3.25%   |
| CometLake        | 4        | 3.25%   |
| Alderlake Hybrid | 4        | 3.25%   |
| Zen+             | 3        | 2.44%   |
| Zen              | 3        | 2.44%   |
| Piledriver       | 3        | 2.44%   |
| K8 Hammer        | 3        | 2.44%   |
| Core             | 3        | 2.44%   |
| Unknown          | 3        | 2.44%   |
| Steamroller      | 2        | 1.63%   |
| NetBurst         | 2        | 1.63%   |
| Icelake          | 2        | 1.63%   |
| Silvermont       | 1        | 0.81%   |
| K6               | 1        | 0.81%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 66       | 47.14%  |
| Intel  | 38       | 27.14%  |
| AMD    | 36       | 25.71%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 12       | 8.39%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 4.2%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 2.8%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 2.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 2.8%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 2.8%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 2.1%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 2.1%    |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 2.1%    |
| Intel Core Processor Integrated Graphics Controller                         | 3        | 2.1%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 2.1%    |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 1.4%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 1.4%    |
| Nvidia TU106 [GeForce RTX 2070]                                             | 2        | 1.4%    |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 1.4%    |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 1.4%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.4%    |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 1.4%    |
| Intel HD Graphics 630                                                       | 2        | 1.4%    |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 1.4%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.4%    |
| Intel 3rd Gen Core processor Graphics Controller                            | 2        | 1.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.4%    |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 2        | 1.4%    |
| AMD RV610 [Radeon HD 2400 PRO]                                              | 2        | 1.4%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 2        | 1.4%    |
| AMD Raphael                                                                 | 2        | 1.4%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.4%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.7%    |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.7%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.7%    |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 0.7%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.7%    |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.7%    |
| Nvidia NV43GL [Quadro FX 540]                                               | 1        | 0.7%    |
| Nvidia NV43 [GeForce 6600 GT]                                               | 1        | 0.7%    |
| Nvidia NV34 [GeForce FX 5200]                                               | 1        | 0.7%    |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.7%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.7%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 57       | 45.97%  |
| 1 x Intel      | 27       | 21.77%  |
| 1 x AMD        | 27       | 21.77%  |
| Intel + Nvidia | 4        | 3.23%   |
| Intel + AMD    | 3        | 2.42%   |
| AMD + Nvidia   | 3        | 2.42%   |
| 2 x AMD        | 2        | 1.61%   |
| Other          | 1        | 0.81%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 75       | 59.06%  |
| Proprietary | 43       | 33.86%  |
| Unknown     | 9        | 7.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 47       | 37.01%  |
| 7.01-8.0   | 17       | 13.39%  |
| 1.01-2.0   | 16       | 12.6%   |
| 3.01-4.0   | 12       | 9.45%   |
| 0.01-0.5   | 11       | 8.66%   |
| 0.51-1.0   | 8        | 6.3%    |
| 8.01-16.0  | 7        | 5.51%   |
| 5.01-6.0   | 6        | 4.72%   |
| 4.01-5.0   | 1        | 0.79%   |
| 2.01-3.0   | 1        | 0.79%   |
| 16.01-24.0 | 1        | 0.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 25       | 19.23%  |
| Samsung Electronics  | 24       | 18.46%  |
| Goldstar             | 18       | 13.85%  |
| AOC                  | 10       | 7.69%   |
| ViewSonic            | 8        | 6.15%   |
| Philips              | 8        | 6.15%   |
| Hewlett-Packard      | 8        | 6.15%   |
| BenQ                 | 4        | 3.08%   |
| Ancor Communications | 4        | 3.08%   |
| Hitachi              | 3        | 2.31%   |
| Unknown              | 2        | 1.54%   |
| RoverScan            | 2        | 1.54%   |
| Lenovo               | 2        | 1.54%   |
| ASUSTek Computer     | 2        | 1.54%   |
| Tech Concepts        | 1        | 0.77%   |
| Plain Tree Systems   | 1        | 0.77%   |
| LG Electronics       | 1        | 0.77%   |
| Lenovo Group Limited | 1        | 0.77%   |
| Gigabyte Technology  | 1        | 0.77%   |
| Fujitsu Siemens      | 1        | 0.77%   |
| Eizo                 | 1        | 0.77%   |
| Belinea              | 1        | 0.77%   |
| Acer                 | 1        | 0.77%   |
| Unknown              | 1        | 0.77%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 340x270mm 17.1-inch          | 2        | 1.41%   |
| Samsung Electronics S32D850 SAM0BCB 2560x1440 708x398mm 32.0-inch      | 2        | 1.41%   |
| Samsung Electronics S24C650 SAM0B18 1920x1200 518x324mm 24.1-inch      | 2        | 1.41%   |
| Hitachi HDMI HEC0030 1920x1080 1150x650mm 52.0-inch                    | 2        | 1.41%   |
| Hewlett-Packard ZR24w HWP2869 1920x1200 546x352mm 25.6-inch            | 2        | 1.41%   |
| Goldstar ULTRAGEAR GSM5B80 2560x1440 597x336mm 27.0-inch               | 2        | 1.41%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                   | 2        | 1.41%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2        | 1.41%   |
| Dell U2719D DEL415A 2560x1440 597x336mm 27.0-inch                      | 2        | 1.41%   |
| Dell U2312HM DEL4073 1920x1080 510x287mm 23.0-inch                     | 2        | 1.41%   |
| Dell P2314H DEL4098 1920x1080 509x286mm 23.0-inch                      | 2        | 1.41%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                    | 2        | 1.41%   |
| ViewSonic XG2405 VSC0D39 1920x1080 527x296mm 23.8-inch                 | 1        | 0.7%    |
| ViewSonic VP920 Series VSCB01C 1280x1024 376x301mm 19.0-inch           | 1        | 0.7%    |
| ViewSonic VG2428wm VSCA426 1920x1080 520x290mm 23.4-inch               | 1        | 0.7%    |
| ViewSonic VG170m VSCBF0C 1280x1024 338x270mm 17.0-inch                 | 1        | 0.7%    |
| ViewSonic VE902m VSC491B 1280x1024 376x301mm 19.0-inch                 | 1        | 0.7%    |
| ViewSonic VA2445 SERIES VSC712E 1920x1080 521x293mm 23.5-inch          | 1        | 0.7%    |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 1        | 0.7%    |
| Unknown LCD Monitor GBT G34WQC 3440x1440                               | 1        | 0.7%    |
| Tech Concepts LCD Monitor MT5531 1920x1080                             | 1        | 0.7%    |
| Samsung Electronics U28H75x SAM0E00 3840x2160 607x345mm 27.5-inch      | 1        | 0.7%    |
| Samsung Electronics U28H75x SAM0DFF 3840x2160 608x345mm 27.5-inch      | 1        | 0.7%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 1        | 0.7%    |
| Samsung Electronics TV SAM0289 1280x720                                | 1        | 0.7%    |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch   | 1        | 0.7%    |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch    | 1        | 0.7%    |
| Samsung Electronics SyncMaster SAM027D 1680x1050 433x271mm 20.1-inch   | 1        | 0.7%    |
| Samsung Electronics SyncMaster SAM027C 1680x1050 433x271mm 20.1-inch   | 1        | 0.7%    |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch   | 1        | 0.7%    |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch   | 1        | 0.7%    |
| Samsung Electronics SyncMaster SAM0193 1280x1024 376x301mm 19.0-inch   | 1        | 0.7%    |
| Samsung Electronics SyncMaster SAM011F 1280x1024 376x301mm 19.0-inch   | 1        | 0.7%    |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch   | 1        | 0.7%    |
| Samsung Electronics S24C450 SAM09CB 1920x1080 531x299mm 24.0-inch      | 1        | 0.7%    |
| Samsung Electronics S22R35x SAM103A 1920x1080 476x268mm 21.5-inch      | 1        | 0.7%    |
| Samsung Electronics S22B350 SAM08D4 1920x1080 477x268mm 21.5-inch      | 1        | 0.7%    |
| Samsung Electronics LS28AG700N SAM7177 3840x2160 632x360mm 28.6-inch   | 1        | 0.7%    |
| Samsung Electronics LS27R75 SAM102E 2560x1440 598x336mm 27.0-inch      | 1        | 0.7%    |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 1210x680mm 54.6-inch | 1        | 0.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 47       | 37.9%   |
| 1280x1024 (SXGA)   | 19       | 15.32%  |
| 3840x2160 (4K)     | 17       | 13.71%  |
| 2560x1440 (QHD)    | 16       | 12.9%   |
| 1920x1200 (WUXGA)  | 11       | 8.87%   |
| 3440x1440          | 5        | 4.03%   |
| 1440x900 (WXGA+)   | 3        | 2.42%   |
| 1680x1050 (WSXGA+) | 2        | 1.61%   |
| 1600x900 (HD+)     | 2        | 1.61%   |
| 1920x540           | 1        | 0.81%   |
| 1366x768 (WXGA)    | 1        | 0.81%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 20       | 15.15%  |
| 27      | 19       | 14.39%  |
| 23      | 18       | 13.64%  |
| 17      | 13       | 9.85%   |
| 21      | 12       | 9.09%   |
| Unknown | 11       | 8.33%   |
| 19      | 7        | 5.3%    |
| 31      | 5        | 3.79%   |
| 84      | 3        | 2.27%   |
| 40      | 3        | 2.27%   |
| 34      | 3        | 2.27%   |
| 32      | 3        | 2.27%   |
| 25      | 3        | 2.27%   |
| 20      | 3        | 2.27%   |
| 18      | 3        | 2.27%   |
| 33      | 2        | 1.52%   |
| 54      | 1        | 0.76%   |
| 43      | 1        | 0.76%   |
| 28      | 1        | 0.76%   |
| 15      | 1        | 0.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 50       | 39.37%  |
| 401-500     | 20       | 15.75%  |
| 301-350     | 14       | 11.02%  |
| 601-700     | 11       | 8.66%   |
| Unknown     | 11       | 8.66%   |
| 701-800     | 8        | 6.3%    |
| 351-400     | 5        | 3.94%   |
| 801-900     | 3        | 2.36%   |
| 1501-2000   | 3        | 2.36%   |
| 1001-1500   | 1        | 0.79%   |
| 901-1000    | 1        | 0.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 66       | 55.93%  |
| 16/10   | 19       | 16.1%   |
| 5/4     | 16       | 13.56%  |
| Unknown | 10       | 8.47%   |
| 21/9    | 3        | 2.54%   |
| 6/5     | 2        | 1.69%   |
| 4/3     | 1        | 0.85%   |
| 32/9    | 1        | 0.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 33       | 25.38%  |
| 301-350        | 19       | 14.62%  |
| 251-300        | 17       | 13.08%  |
| 141-150        | 15       | 11.54%  |
| 351-500        | 14       | 10.77%  |
| 151-200        | 12       | 9.23%   |
| Unknown        | 11       | 8.46%   |
| More than 1000 | 4        | 3.08%   |
| 501-1000       | 4        | 3.08%   |
| 101-110        | 1        | 0.77%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 77       | 63.11%  |
| 101-120 | 24       | 19.67%  |
| Unknown | 11       | 9.02%   |
| 121-160 | 9        | 7.38%   |
| 1-50    | 1        | 0.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 92       | 73.6%   |
| 2     | 22       | 17.6%   |
| 0     | 8        | 6.4%    |
| 3     | 2        | 1.6%    |
| 4     | 1        | 0.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 69       | 42.59%  |
| Intel                           | 48       | 29.63%  |
| TP-Link                         | 7        | 4.32%   |
| Qualcomm Atheros                | 6        | 3.7%    |
| Ralink Technology               | 5        | 3.09%   |
| Nvidia                          | 5        | 3.09%   |
| Ralink                          | 3        | 1.85%   |
| MediaTek                        | 3        | 1.85%   |
| Samsung Electronics             | 2        | 1.23%   |
| Microsoft                       | 2        | 1.23%   |
| Marvell Technology Group        | 2        | 1.23%   |
| D-Link System                   | 2        | 1.23%   |
| Broadcom Limited                | 2        | 1.23%   |
| Broadcom                        | 2        | 1.23%   |
| Qualcomm Atheros Communications | 1        | 0.62%   |
| D-Link                          | 1        | 0.62%   |
| Aquantia                        | 1        | 0.62%   |
| Apple                           | 1        | 0.62%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 55       | 30.39%  |
| Realtek RTL8125 2.5GbE Controller                                 | 7        | 3.87%   |
| Intel I211 Gigabit Network Connection                             | 7        | 3.87%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 3.31%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4        | 2.21%   |
| Intel Ethernet Controller I225-V                                  | 4        | 2.21%   |
| Intel Wi-Fi 6 AX200                                               | 3        | 1.66%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.66%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.66%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 1.66%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                         | 2        | 1.1%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2        | 1.1%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.1%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.1%    |
| Ralink RT5370 Wireless Adapter                                    | 2        | 1.1%    |
| Ralink MT7601U Wireless Adapter                                   | 2        | 1.1%    |
| Ralink RT2500 Wireless 802.11bg                                   | 2        | 1.1%    |
| Nvidia CK804 Ethernet Controller                                  | 2        | 1.1%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2        | 1.1%    |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.1%    |
| Intel 82578DM Gigabit Network Connection                          | 2        | 1.1%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.1%    |
| TP-Link TL-WN821N Version 5 RTL8192EU                             | 1        | 0.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 0.55%   |
| TP-Link Archer T4U ver.3                                          | 1        | 0.55%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 0.55%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1        | 0.55%   |
| TP-Link 802.11ac NIC                                              | 1        | 0.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.55%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.55%   |
| Ralink RT2770 Wireless Adapter                                    | 1        | 0.55%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 0.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.55%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1        | 0.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 10       | 22.73%  |
| Realtek Semiconductor           | 9        | 20.45%  |
| TP-Link                         | 7        | 15.91%  |
| Ralink Technology               | 5        | 11.36%  |
| Ralink                          | 3        | 6.82%   |
| Qualcomm Atheros                | 3        | 6.82%   |
| Microsoft                       | 2        | 4.55%   |
| MediaTek                        | 2        | 4.55%   |
| Qualcomm Atheros Communications | 1        | 2.27%   |
| D-Link System                   | 1        | 2.27%   |
| D-Link                          | 1        | 2.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 4        | 8.7%    |
| Intel Wi-Fi 6 AX200                                                  | 3        | 6.52%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                            | 2        | 4.35%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 2        | 4.35%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 2        | 4.35%   |
| Ralink RT5370 Wireless Adapter                                       | 2        | 4.35%   |
| Ralink MT7601U Wireless Adapter                                      | 2        | 4.35%   |
| Ralink RT2500 Wireless 802.11bg                                      | 2        | 4.35%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 2        | 4.35%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                | 1        | 2.17%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 1        | 2.17%   |
| TP-Link Archer T4U ver.3                                             | 1        | 2.17%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                  | 1        | 2.17%   |
| TP-Link 802.11ac WLAN Adapter                                        | 1        | 2.17%   |
| TP-Link 802.11ac NIC                                                 | 1        | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1        | 2.17%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 1        | 2.17%   |
| Ralink RT2770 Wireless Adapter                                       | 1        | 2.17%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1        | 2.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1        | 2.17%   |
| Qualcomm Atheros AR9271 802.11n                                      | 1        | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 2.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 1        | 2.17%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 1        | 2.17%   |
| Microsoft Wireless XBox Controller Dongle                            | 1        | 2.17%   |
| Intel Wireless 3165                                                  | 1        | 2.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 1        | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1        | 2.17%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 1        | 2.17%   |
| Intel Centrino Wireless-N 2230                                       | 1        | 2.17%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                        | 1        | 2.17%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 1        | 2.17%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1        | 2.17%   |
| D-Link DWA-171                                                       | 1        | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 65       | 51.18%  |
| Intel                    | 44       | 34.65%  |
| Nvidia                   | 5        | 3.94%   |
| Qualcomm Atheros         | 3        | 2.36%   |
| Marvell Technology Group | 2        | 1.57%   |
| Broadcom Limited         | 2        | 1.57%   |
| Broadcom                 | 2        | 1.57%   |
| MediaTek                 | 1        | 0.79%   |
| D-Link System            | 1        | 0.79%   |
| Aquantia                 | 1        | 0.79%   |
| Apple                    | 1        | 0.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 55       | 41.35%  |
| Realtek RTL8125 2.5GbE Controller                                             | 7        | 5.26%   |
| Intel I211 Gigabit Network Connection                                         | 7        | 5.26%   |
| Intel Ethernet Connection (7) I219-V                                          | 6        | 4.51%   |
| Intel Ethernet Controller I225-V                                              | 4        | 3.01%   |
| Intel Ethernet Connection I217-LM                                             | 3        | 2.26%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 2.26%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 2.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3        | 2.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2        | 1.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 1.5%    |
| Nvidia CK804 Ethernet Controller                                              | 2        | 1.5%    |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 1.5%    |
| Intel 82578DM Gigabit Network Connection                                      | 2        | 1.5%    |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 1.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.75%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 1        | 0.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1        | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.75%   |
| Nvidia nForce2 Ethernet Controller                                            | 1        | 0.75%   |
| Nvidia MCP77 Ethernet                                                         | 1        | 0.75%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 0.75%   |
| MediaTek M40Air_EEA                                                           | 1        | 0.75%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1        | 0.75%   |
| Marvell Group 88E8052 PCI-E ASF Gigabit Ethernet Controller                   | 1        | 0.75%   |
| Intel I350 Gigabit Network Connection                                         | 1        | 0.75%   |
| Intel I210 Gigabit Network Connection                                         | 1        | 0.75%   |
| Intel Ethernet Controller I219-V                                              | 1        | 0.75%   |
| Intel Ethernet Connection I217-V                                              | 1        | 0.75%   |
| Intel Ethernet Connection (5) I219-LM                                         | 1        | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 0.75%   |
| Intel Ethernet Connection (17) I219-V                                         | 1        | 0.75%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.75%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 0.75%   |
| Intel 82574L Gigabit Network Connection                                       | 1        | 0.75%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.75%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1        | 0.75%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1        | 0.75%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 1        | 0.75%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 1        | 0.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 120      | 72.73%  |
| WiFi     | 43       | 26.06%  |
| Modem    | 2        | 1.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 98       | 81.67%  |
| WiFi     | 22       | 18.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 91       | 73.98%  |
| 2     | 26       | 21.14%  |
| 0     | 3        | 2.44%   |
| 3     | 2        | 1.63%   |
| 6     | 1        | 0.81%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 99       | 80.49%  |
| Yes  | 24       | 19.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 13       | 34.21%  |
| Intel                           | 9        | 23.68%  |
| TP-Link                         | 3        | 7.89%   |
| Realtek Semiconductor           | 3        | 7.89%   |
| ASUSTek Computer                | 3        | 7.89%   |
| Foxconn / Hon Hai               | 2        | 5.26%   |
| Edimax Technology               | 2        | 5.26%   |
| Qualcomm Atheros Communications | 1        | 2.63%   |
| Integrated System Solution      | 1        | 2.63%   |
| Broadcom                        | 1        | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 13       | 34.21%  |
| TP-Link UB500 Adapter                                 | 3        | 7.89%   |
| Intel AX200 Bluetooth                                 | 3        | 7.89%   |
| Foxconn / Hon Hai Wireless_Device                     | 2        | 5.26%   |
| Edimax Edimax Bluetooth Adapter                       | 2        | 5.26%   |
| ASUS Bluetooth Device                                 | 2        | 5.26%   |
| Realtek RTL8821A Bluetooth                            | 1        | 2.63%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 2.63%   |
| Realtek Bluetooth Radio                               | 1        | 2.63%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 2.63%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 2.63%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 2.63%   |
| Intel Bluetooth wireless interface                    | 1        | 2.63%   |
| Intel Bluetooth Device                                | 1        | 2.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 2.63%   |
| Intel AX210 Bluetooth                                 | 1        | 2.63%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 2.63%   |
| Broadcom Bluetooth 3.0+HS USB Adapter                 | 1        | 2.63%   |
| ASUS Bluetooth Radio                                  | 1        | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 75       | 32.89%  |
| Nvidia                  | 63       | 27.63%  |
| AMD                     | 56       | 24.56%  |
| C-Media Electronics     | 7        | 3.07%   |
| Kingston Technology     | 5        | 2.19%   |
| Logitech                | 3        | 1.32%   |
| SteelSeries ApS         | 2        | 0.88%   |
| Razer USA               | 2        | 0.88%   |
| Focusrite-Novation      | 2        | 0.88%   |
| Creative Labs           | 2        | 0.88%   |
| ASUSTek Computer        | 2        | 0.88%   |
| TerraTec Electronic     | 1        | 0.44%   |
| Syntek                  | 1        | 0.44%   |
| Samson Technologies     | 1        | 0.44%   |
| M-Audio                 | 1        | 0.44%   |
| JMTek                   | 1        | 0.44%   |
| GYROCOM C&C             | 1        | 0.44%   |
| Generalplus Technology  | 1        | 0.44%   |
| DSEA A/S                | 1        | 0.44%   |
| BEHRINGER International | 1        | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 18       | 7.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12       | 4.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12       | 4.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9        | 3.61%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8        | 3.21%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 2.81%   |
| Intel 200 Series PCH HD Audio                                              | 7        | 2.81%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7        | 2.81%   |
| Nvidia TU116 High Definition Audio Controller                              | 6        | 2.41%   |
| Nvidia TU106 High Definition Audio Controller                              | 6        | 2.41%   |
| Nvidia GP104 High Definition Audio Controller                              | 6        | 2.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 2.41%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6        | 2.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 2.01%   |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 1.61%   |
| Kingston Technology HyperX 7.1 Audio                                       | 4        | 1.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 1.61%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 1.2%    |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.2%    |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.2%    |
| Nvidia GP102 HDMI Audio Controller                                         | 3        | 1.2%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 1.2%    |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 1.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 1.2%    |
| C-Media Electronics Blue Snowball                                          | 3        | 1.2%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 1.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 1.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 1.2%    |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.8%    |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 0.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 0.8%    |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 0.8%    |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 0.8%    |
| Nvidia CK804 AC'97 Audio Controller                                        | 2        | 0.8%    |
| Nvidia Audio device                                                        | 2        | 0.8%    |
| Logitech Logitech G PRO X Gaming Headset                                   | 2        | 0.8%    |
| Intel Comet Lake PCH-V cAVS                                                | 2        | 0.8%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 0.8%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 0.8%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2        | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 18       | 20%     |
| G.Skill             | 16       | 17.78%  |
| Unknown             | 15       | 16.67%  |
| Crucial             | 8        | 8.89%   |
| Samsung Electronics | 7        | 7.78%   |
| SK hynix            | 6        | 6.67%   |
| Corsair             | 5        | 5.56%   |
| Patriot             | 2        | 2.22%   |
| Apacer              | 2        | 2.22%   |
| Wilk                | 1        | 1.11%   |
| Team                | 1        | 1.11%   |
| Silicon Power       | 1        | 1.11%   |
| Ramaxel Technology  | 1        | 1.11%   |
| Micron Technology   | 1        | 1.11%   |
| GOODRAM             | 1        | 1.11%   |
| Elpida              | 1        | 1.11%   |
| AMD                 | 1        | 1.11%   |
| Aeneon              | 1        | 1.11%   |
| A-DATA Technology   | 1        | 1.11%   |
| Unknown             | 1        | 1.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 512MB DIMM SDRAM                       | 2        | 1.96%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 2        | 1.96%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 2        | 1.96%   |
| Crucial RAM BLS8G4D240FSB.16FBR2 8GB DIMM DDR4 2400MT/s   | 2        | 1.96%   |
| Wilk RAM IRX3200D464L16SA/8G 8GB DIMM DDR4 3200MT/s       | 1        | 0.98%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                 | 1        | 0.98%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s              | 1        | 0.98%   |
| Unknown RAM Module 512MB DIMM                             | 1        | 0.98%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                    | 1        | 0.98%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1        | 0.98%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                  | 1        | 0.98%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                      | 1        | 0.98%   |
| Unknown RAM Module 256MB DIMM                             | 1        | 0.98%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 1        | 0.98%   |
| Unknown RAM Module 1GB DIMM SDRAM                         | 1        | 0.98%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s               | 1        | 0.98%   |
| Unknown RAM Module 1024MB DIMM                            | 1        | 0.98%   |
| Unknown RAM 1600 CL9 Series 8192MB DIMM DDR3 1066MT/s     | 1        | 0.98%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s        | 1        | 0.98%   |
| SK hynix RAM Module 8192MB DIMM DDR3 1333MT/s             | 1        | 0.98%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 0.98%   |
| SK hynix RAM HMT351U7BFR8C-H9 4GB DIMM DDR3 1333MT/s      | 1        | 0.98%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 1        | 0.98%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s      | 1        | 0.98%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s      | 1        | 0.98%   |
| SK hynix RAM HMT125U6TFR8C-G7 2GB DIMM DDR3 1067MT/s      | 1        | 0.98%   |
| Silicon Power RAM SP008GBLTU160N02 8GB DIMM DDR3 1600MT/s | 1        | 0.98%   |
| Silicon Power RAM DCLT8GN128S 8192MB DIMM DDR3 1600MT/s   | 1        | 0.98%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s  | 1        | 0.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 1        | 0.98%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s       | 1        | 0.98%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR2 2133MT/s    | 1        | 0.98%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s       | 1        | 0.98%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s       | 1        | 0.98%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s       | 1        | 0.98%   |
| Ramaxel RAM RMR1870EC58E9F133 4GB DIMM DDR3 1333MT/s      | 1        | 0.98%   |
| Patriot RAM PSD48G240082 8GB DIMM DDR4 2400MT/s           | 1        | 0.98%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3600MT/s        | 1        | 0.98%   |
| Micron RAM 8ATF2G64AZ-3G2E1 16GB DIMM DDR4 3200MT/s       | 1        | 0.98%   |
| Kingston RAM KP223C-ELD 2GB DIMM DDR3 1600MT/s            | 1        | 0.98%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 38       | 48.72%  |
| DDR3    | 24       | 30.77%  |
| SDRAM   | 6        | 7.69%   |
| Unknown | 5        | 6.41%   |
| DDR2    | 3        | 3.85%   |
| DDR5    | 1        | 1.28%   |
| DDR     | 1        | 1.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 75       | 97.4%   |
| SODIMM | 2        | 2.6%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 32       | 38.1%   |
| 4096  | 14       | 16.67%  |
| 16384 | 13       | 15.48%  |
| 2048  | 13       | 15.48%  |
| 1024  | 4        | 4.76%   |
| 512   | 4        | 4.76%   |
| 32768 | 3        | 3.57%   |
| 256   | 1        | 1.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 17       | 19.32%  |
| 3200    | 11       | 12.5%   |
| 1333    | 9        | 10.23%  |
| 3600    | 7        | 7.95%   |
| Unknown | 6        | 6.82%   |
| 2667    | 4        | 4.55%   |
| 2400    | 4        | 4.55%   |
| 3666    | 3        | 3.41%   |
| 2133    | 3        | 3.41%   |
| 3733    | 2        | 2.27%   |
| 2666    | 2        | 2.27%   |
| 800     | 2        | 2.27%   |
| 667     | 2        | 2.27%   |
| 6000    | 1        | 1.14%   |
| 4199    | 1        | 1.14%   |
| 4133    | 1        | 1.14%   |
| 3800    | 1        | 1.14%   |
| 3334    | 1        | 1.14%   |
| 3266    | 1        | 1.14%   |
| 3000    | 1        | 1.14%   |
| 2933    | 1        | 1.14%   |
| 2733    | 1        | 1.14%   |
| 2134    | 1        | 1.14%   |
| 1867    | 1        | 1.14%   |
| 1866    | 1        | 1.14%   |
| 1800    | 1        | 1.14%   |
| 1632    | 1        | 1.14%   |
| 1067    | 1        | 1.14%   |
| 533     | 1        | 1.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Seiko Epson         | 1        | 20%     |
| Samsung Electronics | 1        | 20%     |
| Konica Minolta      | 1        | 20%     |
| Hewlett-Packard     | 1        | 20%     |
| Brother Industries  | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Seiko Epson Thermal Receipt Printer [TM-T20] | 1        | 20%     |
| Samsung SCX-3400 Series                      | 1        | 20%     |
| Konica Minolta Printer                       | 1        | 20%     |
| HP Smart Tank 750 series                     | 1        | 20%     |
| Brother HL-4140CN series                     | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Seiko Epson Perfection 660 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 8        | 40%     |
| Microdia                      | 2        | 10%     |
| Arkmicro Technologies         | 2        | 10%     |
| Apple                         | 2        | 10%     |
| Z-Star Microelectronics       | 1        | 5%      |
| Sunplus Innovation Technology | 1        | 5%      |
| Samsung Electronics           | 1        | 5%      |
| Microsoft                     | 1        | 5%      |
| Lenovo                        | 1        | 5%      |
| Creative Technology           | 1        | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech HD Webcam C525                 | 3        | 15%     |
| Logitech Webcam C930e                   | 2        | 10%     |
| Arkmicro USB2.0 PC CAMERA               | 2        | 10%     |
| Apple iPhone 5/5C/5S/6/SE               | 2        | 10%     |
| Z-Star A4 TECH USB2.0 PC Camera E       | 1        | 5%      |
| Sunplus USB Camera                      | 1        | 5%      |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 5%      |
| Microsoft LifeCam HD-3000               | 1        | 5%      |
| Microdia Webcam Vitade AF               | 1        | 5%      |
| Microdia USB Camera                     | 1        | 5%      |
| Logitech Webcam C270                    | 1        | 5%      |
| Logitech HD Pro Webcam C920             | 1        | 5%      |
| Logitech B525 HD Webcam                 | 1        | 5%      |
| Lenovo Lenovo 500 RGB Camera            | 1        | 5%      |
| Creative Live! Cam Chat HD [VF0700]     | 1        | 5%      |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| OmniKey               | 12       | 52.17%  |
| Gemalto (was Gemplus) | 4        | 17.39%  |
| Alcor Micro           | 4        | 17.39%  |
| SCM Microsystems      | 1        | 4.35%   |
| Clay Logic            | 1        | 4.35%   |
| Chicony Electronics   | 1        | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| OmniKey CardMan 1021                                   | 12       | 52.17%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader      | 4        | 17.39%  |
| Alcor Micro Watchdata W 1981                           | 4        | 17.39%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 4.35%   |
| Clay Logic Nitrokey Start                              | 1        | 4.35%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard   | 1        | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 100      | 77.52%  |
| 1     | 26       | 20.16%  |
| 2     | 3        | 2.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 15       | 46.88%  |
| Chipcard                 | 11       | 34.38%  |
| Net/wireless             | 2        | 6.25%   |
| Sound                    | 1        | 3.13%   |
| Net/ethernet             | 1        | 3.13%   |
| Multimedia controller    | 1        | 3.13%   |
| Communication controller | 1        | 3.13%   |


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

Total: 191

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte | H81M-S                      | [d18c354852](https://linux-hardware.org/?probe=d18c354852) | Mar 31, 2024 |
| Intel    | DB85FL AAG89861-201         | [15f1dac527](https://linux-hardware.org/?probe=15f1dac527) | Mar 21, 2024 |
| ASRock   | H310M-HDV                   | [4e2f714f49](https://linux-hardware.org/?probe=4e2f714f49) | Mar 16, 2024 |
| ASRock   | H310M-HDV                   | [8d62cae785](https://linux-hardware.org/?probe=8d62cae785) | Mar 15, 2024 |
| MSI      | B85M-G43                    | [c1b1061c0d](https://linux-hardware.org/?probe=c1b1061c0d) | Mar 14, 2024 |
| Gigabyte | 970A-DS3P                   | [66295fb0e8](https://linux-hardware.org/?probe=66295fb0e8) | Mar 04, 2024 |
| Gigabyte | X570S AORUS PRO AX          | [9dbfe4a6eb](https://linux-hardware.org/?probe=9dbfe4a6eb) | Mar 04, 2024 |
| MSI      | X570-A PRO                  | [779b399243](https://linux-hardware.org/?probe=779b399243) | Feb 09, 2024 |
| ASUSTek  | PRIME B550M-K               | [7536a68c05](https://linux-hardware.org/?probe=7536a68c05) | Jan 06, 2024 |
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


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 10       | 7.25%   |
| Arch Rolling       | 10       | 7.25%   |
| Ubuntu 22.04       | 6        | 4.35%   |
| Ubuntu 18.04       | 6        | 4.35%   |
| ROSA R11           | 6        | 4.35%   |
| OpenMandriva 4.3   | 6        | 4.35%   |
| ROSA R8.1          | 4        | 2.9%    |
| Manjaro            | 4        | 2.9%    |
| Kubuntu 20.04      | 4        | 2.9%    |
| Debian 12          | 4        | 2.9%    |
| Ubuntu 21.10       | 3        | 2.17%   |
| ROSA 12.2          | 3        | 2.17%   |
| Gentoo 2.6         | 3        | 2.17%   |
| Fedora 34          | 3        | 2.17%   |
| Fedora 31          | 3        | 2.17%   |
| Pop!_OS 22.04      | 2        | 1.45%   |
| Pop!_OS 21.04      | 2        | 1.45%   |
| OpenMandriva 4.2   | 2        | 1.45%   |
| OpenMandriva 23.03 | 2        | 1.45%   |
| Nobara 37          | 2        | 1.45%   |
| KDE neon 20.04     | 2        | 1.45%   |
| Fedora 39          | 2        | 1.45%   |
| Fedora 36          | 2        | 1.45%   |
| Debian Testing     | 2        | 1.45%   |
| Debian 11          | 2        | 1.45%   |
| ArcoLinux Rolling  | 2        | 1.45%   |
| Arch               | 2        | 1.45%   |
| Zorin 16           | 1        | 0.72%   |
| Xubuntu 18.04      | 1        | 0.72%   |
| Ubuntu MATE 22.04  | 1        | 0.72%   |
| Ubuntu MATE 20.04  | 1        | 0.72%   |
| Ubuntu 23.04       | 1        | 0.72%   |
| Ubuntu 21.04       | 1        | 0.72%   |
| Ubuntu 19.10       | 1        | 0.72%   |
| Ubuntu 19.04       | 1        | 0.72%   |
| Ubuntu 16.04       | 1        | 0.72%   |
| ROSA R9            | 1        | 0.72%   |
| ROSA R11.1         | 1        | 0.72%   |
| ROSA R10           | 1        | 0.72%   |
| ROSA 12.4          | 1        | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 30       | 22.22%  |
| ROSA         | 18       | 13.33%  |
| OpenMandriva | 12       | 8.89%   |
| Arch         | 12       | 8.89%   |
| Fedora       | 11       | 8.15%   |
| Debian       | 10       | 7.41%   |
| Manjaro      | 7        | 5.19%   |
| Kubuntu      | 5        | 3.7%    |
| Pop!_OS      | 4        | 2.96%   |
| Gentoo       | 4        | 2.96%   |
| Nobara       | 3        | 2.22%   |
| KDE neon     | 3        | 2.22%   |
| Ubuntu MATE  | 2        | 1.48%   |
| openSUSE     | 2        | 1.48%   |
| Linux Mint   | 2        | 1.48%   |
| ArcoLinux    | 2        | 1.48%   |
| Zorin        | 1        | 0.74%   |
| Xubuntu      | 1        | 0.74%   |
| Reborn OS    | 1        | 0.74%   |
| MX           | 1        | 0.74%   |
| LMDE         | 1        | 0.74%   |
| EndeavourOS  | 1        | 0.74%   |
| Elementary   | 1        | 0.74%   |
| Clear Linux  | 1        | 0.74%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003             | 6        | 4.03%   |
| 6.1.0-13-amd64                      | 3        | 2.01%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 3        | 2.01%   |
| 6.2.6-desktop-1omv2390              | 2        | 1.34%   |
| 5.5.2-1-MANJARO                     | 2        | 1.34%   |
| 5.4.0-53-generic                    | 2        | 1.34%   |
| 5.4.0-42-generic                    | 2        | 1.34%   |
| 5.4.0-26-generic                    | 2        | 1.34%   |
| 5.11.0-25-generic                   | 2        | 1.34%   |
| 5.10.14-desktop-1omv4002            | 2        | 1.34%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 2        | 1.34%   |
| 6.7.8-zen1-1-zen                    | 1        | 0.67%   |
| 6.7.4-arch1-1                       | 1        | 0.67%   |
| 6.7.10-200.fc39.x86_64              | 1        | 0.67%   |
| 6.6.3-arch1-1                       | 1        | 0.67%   |
| 6.6.21-1-lts                        | 1        | 0.67%   |
| 6.6.2-201.fc39.x86_64               | 1        | 0.67%   |
| 6.5.6-76060506-generic              | 1        | 0.67%   |
| 6.5.0-21-generic                    | 1        | 0.67%   |
| 6.5.0-14-generic                    | 1        | 0.67%   |
| 6.4.8-desktop-2omv2390              | 1        | 0.67%   |
| 6.4.10-202.fsync.fc38.x86_64        | 1        | 0.67%   |
| 6.2.6-201.fsync.fc37.x86_64         | 1        | 0.67%   |
| 6.2.6-1-default                     | 1        | 0.67%   |
| 6.2.0-23-generic                    | 1        | 0.67%   |
| 6.1.9-200.fsync.fc37.x86_64         | 1        | 0.67%   |
| 6.1.68-1-lts                        | 1        | 0.67%   |
| 6.1.38-generic-1rosa2021.1-x86_64   | 1        | 0.67%   |
| 6.1.29-1-lts                        | 1        | 0.67%   |
| 6.1.14-201.fsync.fc37.x86_64        | 1        | 0.67%   |
| 6.1.12-1-MANJARO                    | 1        | 0.67%   |
| 6.1.1-desktop-1omv2290              | 1        | 0.67%   |
| 6.1.0-17-amd64                      | 1        | 0.67%   |
| 6.0.12-76060006-generic             | 1        | 0.67%   |
| 6.0.11-x64v1-xanmod1-1              | 1        | 0.67%   |
| 6.0.11-arch1-1                      | 1        | 0.67%   |
| 6.0.1-zen2-1-zen                    | 1        | 0.67%   |
| 5.8.10-zen1-1-zen                   | 1        | 0.67%   |
| 5.8.10-arch1-1                      | 1        | 0.67%   |
| 5.8.0-63-generic                    | 1        | 0.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 15       | 10.49%  |
| 4.15.0   | 12       | 8.39%   |
| 5.15.0   | 8        | 5.59%   |
| 5.16.7   | 6        | 4.2%    |
| 5.13.0   | 5        | 3.5%    |
| 5.11.0   | 5        | 3.5%    |
| 6.2.6    | 4        | 2.8%    |
| 6.1.0    | 4        | 2.8%    |
| 5.10.0   | 4        | 2.8%    |
| 5.10.118 | 3        | 2.1%    |
| 6.5.0    | 2        | 1.4%    |
| 6.0.11   | 2        | 1.4%    |
| 5.8.10   | 2        | 1.4%    |
| 5.8.0    | 2        | 1.4%    |
| 5.5.2    | 2        | 1.4%    |
| 5.3.0    | 2        | 1.4%    |
| 5.19.0   | 2        | 1.4%    |
| 5.10.14  | 2        | 1.4%    |
| 5.0.0    | 2        | 1.4%    |
| 4.9.9    | 2        | 1.4%    |
| 6.7.8    | 1        | 0.7%    |
| 6.7.4    | 1        | 0.7%    |
| 6.7.10   | 1        | 0.7%    |
| 6.6.3    | 1        | 0.7%    |
| 6.6.21   | 1        | 0.7%    |
| 6.6.2    | 1        | 0.7%    |
| 6.5.6    | 1        | 0.7%    |
| 6.4.8    | 1        | 0.7%    |
| 6.4.10   | 1        | 0.7%    |
| 6.2.0    | 1        | 0.7%    |
| 6.1.9    | 1        | 0.7%    |
| 6.1.68   | 1        | 0.7%    |
| 6.1.38   | 1        | 0.7%    |
| 6.1.29   | 1        | 0.7%    |
| 6.1.14   | 1        | 0.7%    |
| 6.1.12   | 1        | 0.7%    |
| 6.1.1    | 1        | 0.7%    |
| 6.0.12   | 1        | 0.7%    |
| 6.0.1    | 1        | 0.7%    |
| 5.7.0    | 1        | 0.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 20       | 14.08%  |
| 5.10    | 12       | 8.45%   |
| 4.15    | 12       | 8.45%   |
| 6.1     | 11       | 7.75%   |
| 5.15    | 11       | 7.75%   |
| 5.13    | 8        | 5.63%   |
| 5.16    | 7        | 4.93%   |
| 5.11    | 7        | 4.93%   |
| 4.9     | 6        | 4.23%   |
| 6.2     | 5        | 3.52%   |
| 6.0     | 4        | 2.82%   |
| 5.8     | 4        | 2.82%   |
| 5.3     | 4        | 2.82%   |
| 6.7     | 3        | 2.11%   |
| 6.6     | 3        | 2.11%   |
| 6.5     | 3        | 2.11%   |
| 5.5     | 3        | 2.11%   |
| 5.18    | 3        | 2.11%   |
| 6.4     | 2        | 1.41%   |
| 5.6     | 2        | 1.41%   |
| 5.19    | 2        | 1.41%   |
| 5.14    | 2        | 1.41%   |
| 5.0     | 2        | 1.41%   |
| 4.19    | 2        | 1.41%   |
| 5.7     | 1        | 0.7%    |
| 5.17    | 1        | 0.7%    |
| 5.1     | 1        | 0.7%    |
| 4.1     | 1        | 0.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 123      | 94.62%  |
| i686   | 6        | 4.62%   |
| armv7l | 1        | 0.77%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 48       | 35.29%  |
| KDE5       | 35       | 25.74%  |
| Unknown    | 15       | 11.03%  |
| KDE4       | 11       | 8.09%   |
| XFCE       | 6        | 4.41%   |
| X-Cinnamon | 5        | 3.68%   |
| MATE       | 5        | 3.68%   |
| sway       | 2        | 1.47%   |
| LXQt       | 2        | 1.47%   |
| KDE6       | 2        | 1.47%   |
| i3         | 2        | 1.47%   |
| Pantheon   | 1        | 0.74%   |
| KDE        | 1        | 0.74%   |
| Budgie     | 1        | 0.74%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 98       | 73.68%  |
| Wayland | 27       | 20.3%   |
| Unknown | 5        | 3.76%   |
| Tty     | 2        | 1.5%    |
| Web     | 1        | 0.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 54       | 40.91%  |
| SDDM    | 29       | 21.97%  |
| GDM     | 15       | 11.36%  |
| GDM3    | 12       | 9.09%   |
| KDM     | 11       | 8.33%   |
| LightDM | 8        | 6.06%   |
| TDM     | 3        | 2.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 61       | 45.86%  |
| Unknown | 24       | 18.05%  |
| et_EE   | 20       | 15.04%  |
| ru_RU   | 14       | 10.53%  |
| en_GB   | 6        | 4.51%   |
| pl_PL   | 2        | 1.5%    |
| en_IE   | 2        | 1.5%    |
| fr_FR   | 1        | 0.75%   |
| en_BW   | 1        | 0.75%   |
| de_DE   | 1        | 0.75%   |
| C       | 1        | 0.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 76       | 57.14%  |
| EFI  | 57       | 42.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 90       | 68.18%  |
| Btrfs   | 20       | 15.15%  |
| Overlay | 13       | 9.85%   |
| Unknown | 6        | 4.55%   |
| Zfs     | 1        | 0.76%   |
| Xfs     | 1        | 0.76%   |
| Ext3    | 1        | 0.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 54       | 41.22%  |
| Unknown | 52       | 39.69%  |
| MBR     | 25       | 19.08%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 94       | 70.68%  |
| Yes       | 39       | 29.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 86       | 65.15%  |
| Yes       | 46       | 34.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 32       | 24.62%  |
| MSI                 | 26       | 20%     |
| Gigabyte Technology | 26       | 20%     |
| ASRock              | 11       | 8.46%   |
| Hewlett-Packard     | 8        | 6.15%   |
| Lenovo              | 6        | 4.62%   |
| Intel               | 6        | 4.62%   |
| Dell                | 6        | 4.62%   |
| ECS                 | 4        | 3.08%   |
| OEM                 | 1        | 0.77%   |
| Huanan              | 1        | 0.77%   |
| Fujitsu             | 1        | 0.77%   |
| ABIT                | 1        | 0.77%   |
| Unknown             | 1        | 0.77%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| ASUS All Series                          | 4        | 3.08%   |
| MSI MS-7C91                              | 2        | 1.54%   |
| MSI MS-7C37                              | 2        | 1.54%   |
| MSI MS-7C02                              | 2        | 1.54%   |
| MSI MS-7758                              | 2        | 1.54%   |
| HP Compaq 8100 Elite SFF PC              | 2        | 1.54%   |
| Gigabyte X570 AORUS PRO                  | 2        | 1.54%   |
| Gigabyte Q87M-D2H                        | 2        | 1.54%   |
| ASUS ROG STRIX B550-F GAMING             | 2        | 1.54%   |
| ASUS PRIME B550M-K                       | 2        | 1.54%   |
| OEM Intel H81                            | 1        | 0.77%   |
| MSI MS-7D59                              | 1        | 0.77%   |
| MSI MS-7D43                              | 1        | 0.77%   |
| MSI MS-7C83                              | 1        | 0.77%   |
| MSI MS-7C75                              | 1        | 0.77%   |
| MSI MS-7B98                              | 1        | 0.77%   |
| MSI MS-7B86                              | 1        | 0.77%   |
| MSI MS-7B79                              | 1        | 0.77%   |
| MSI MS-7B22                              | 1        | 0.77%   |
| MSI MS-7B18                              | 1        | 0.77%   |
| MSI MS-7A74                              | 1        | 0.77%   |
| MSI MS-7996                              | 1        | 0.77%   |
| MSI MS-7978                              | 1        | 0.77%   |
| MSI MS-7971                              | 1        | 0.77%   |
| MSI MS-7851                              | 1        | 0.77%   |
| MSI MS-7823                              | 1        | 0.77%   |
| MSI MS-7640                              | 1        | 0.77%   |
| MSI MS-7267                              | 1        | 0.77%   |
| MSI FJ418AA-UUW a6522.SC                 | 1        | 0.77%   |
| Lenovo ThinkStation D20 4158GK1          | 1        | 0.77%   |
| Lenovo ThinkCentre M75s Gen 2 11JB002GPB | 1        | 0.77%   |
| Lenovo ThinkCentre M72z 3543C8G          | 1        | 0.77%   |
| Lenovo ThinkCentre M58 7360WQK           | 1        | 0.77%   |
| Lenovo H50-55 90BF005SMW                 | 1        | 0.77%   |
| Lenovo Erazer X310 90AV000CMT            | 1        | 0.77%   |
| Intel DX79TO AAG28805-400                | 1        | 0.77%   |
| Intel DQ35JO AAD82085-807                | 1        | 0.77%   |
| Intel DP67BG AAG10491-305                | 1        | 0.77%   |
| Intel DH61DL AAG14066-205                | 1        | 0.77%   |
| Intel DB85FL AAG89861-201                | 1        | 0.77%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 8        | 6.15%   |
| Dell OptiPlex       | 5        | 3.85%   |
| ASUS ROG            | 5        | 3.85%   |
| HP Compaq           | 4        | 3.08%   |
| Gigabyte X570       | 4        | 3.08%   |
| ASUS All            | 4        | 3.08%   |
| Lenovo ThinkCentre  | 3        | 2.31%   |
| ASUS TUF            | 3        | 2.31%   |
| MSI MS-7C91         | 2        | 1.54%   |
| MSI MS-7C37         | 2        | 1.54%   |
| MSI MS-7C02         | 2        | 1.54%   |
| MSI MS-7758         | 2        | 1.54%   |
| HP ProDesk          | 2        | 1.54%   |
| Gigabyte Q87M-D2H   | 2        | 1.54%   |
| OEM Intel           | 1        | 0.77%   |
| MSI MS-7D59         | 1        | 0.77%   |
| MSI MS-7D43         | 1        | 0.77%   |
| MSI MS-7C83         | 1        | 0.77%   |
| MSI MS-7C75         | 1        | 0.77%   |
| MSI MS-7B98         | 1        | 0.77%   |
| MSI MS-7B86         | 1        | 0.77%   |
| MSI MS-7B79         | 1        | 0.77%   |
| MSI MS-7B22         | 1        | 0.77%   |
| MSI MS-7B18         | 1        | 0.77%   |
| MSI MS-7A74         | 1        | 0.77%   |
| MSI MS-7996         | 1        | 0.77%   |
| MSI MS-7978         | 1        | 0.77%   |
| MSI MS-7971         | 1        | 0.77%   |
| MSI MS-7851         | 1        | 0.77%   |
| MSI MS-7823         | 1        | 0.77%   |
| MSI MS-7640         | 1        | 0.77%   |
| MSI MS-7267         | 1        | 0.77%   |
| MSI FJ418AA-UUW     | 1        | 0.77%   |
| Lenovo ThinkStation | 1        | 0.77%   |
| Lenovo H50-55       | 1        | 0.77%   |
| Lenovo Erazer       | 1        | 0.77%   |
| Intel DX79TO        | 1        | 0.77%   |
| Intel DQ35JO        | 1        | 0.77%   |
| Intel DP67BG        | 1        | 0.77%   |
| Intel DH61DL        | 1        | 0.77%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 15       | 11.54%  |
| 2018    | 15       | 11.54%  |
| 2012    | 12       | 9.23%   |
| 2019    | 11       | 8.46%   |
| 2013    | 11       | 8.46%   |
| 2014    | 8        | 6.15%   |
| 2009    | 8        | 6.15%   |
| 2016    | 7        | 5.38%   |
| 2021    | 6        | 4.62%   |
| 2015    | 6        | 4.62%   |
| 2022    | 5        | 3.85%   |
| 2017    | 5        | 3.85%   |
| 2010    | 5        | 3.85%   |
| 2011    | 4        | 3.08%   |
| 2008    | 3        | 2.31%   |
| 2006    | 3        | 2.31%   |
| 2007    | 2        | 1.54%   |
| 2005    | 2        | 1.54%   |
| 2004    | 1        | 0.77%   |
| Unknown | 1        | 0.77%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 130      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 128      | 97.71%  |
| Enabled  | 3        | 2.29%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 130      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 33       | 25.19%  |
| 32.01-64.0  | 30       | 22.9%   |
| 4.01-8.0    | 17       | 12.98%  |
| 8.01-16.0   | 17       | 12.98%  |
| 3.01-4.0    | 15       | 11.45%  |
| 64.01-256.0 | 7        | 5.34%   |
| 1.01-2.0    | 4        | 3.05%   |
| 24.01-32.0  | 3        | 2.29%   |
| 2.01-3.0    | 2        | 1.53%   |
| 0.51-1.0    | 2        | 1.53%   |
| 0.01-0.5    | 1        | 0.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 35       | 25%     |
| 2.01-3.0   | 29       | 20.71%  |
| 4.01-8.0   | 28       | 20%     |
| 0.51-1.0   | 17       | 12.14%  |
| 8.01-16.0  | 12       | 8.57%   |
| 3.01-4.0   | 11       | 7.86%   |
| 0.01-0.5   | 4        | 2.86%   |
| 24.01-32.0 | 2        | 1.43%   |
| 16.01-24.0 | 2        | 1.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 48       | 35.56%  |
| 2      | 35       | 25.93%  |
| 3      | 26       | 19.26%  |
| 4      | 11       | 8.15%   |
| 6      | 9        | 6.67%   |
| 5      | 4        | 2.96%   |
| 7      | 1        | 0.74%   |
| 0      | 1        | 0.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 72       | 55.38%  |
| Yes       | 58       | 44.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 128      | 97.71%  |
| No        | 3        | 2.29%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 84       | 64.62%  |
| Yes       | 46       | 35.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 93       | 70.45%  |
| Yes       | 39       | 29.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Estonia | 130      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Tallinn       | 80       | 59.7%   |
| Tartu         | 18       | 13.43%  |
| Haapsalu      | 5        | 3.73%   |
| Rapla         | 3        | 2.24%   |
| Pärnu        | 3        | 2.24%   |
| Tapa          | 2        | 1.49%   |
| Rakvere       | 2        | 1.49%   |
| Paldiski      | 2        | 1.49%   |
| Kohtla-Järve | 2        | 1.49%   |
| Viljandi      | 1        | 0.75%   |
| Valga         | 1        | 0.75%   |
| Vaidasoo      | 1        | 0.75%   |
| Türi         | 1        | 0.75%   |
| Tabasalu      | 1        | 0.75%   |
| Sindi         | 1        | 0.75%   |
| Põlva        | 1        | 0.75%   |
| Maardu        | 1        | 0.75%   |
| Lohkva        | 1        | 0.75%   |
| Kuressaare    | 1        | 0.75%   |
| Kose          | 1        | 0.75%   |
| Kiviõli      | 1        | 0.75%   |
| Kadrina       | 1        | 0.75%   |
| Jõhvi        | 1        | 0.75%   |
| Jaerva vald   | 1        | 0.75%   |
| Hiiumaa       | 1        | 0.75%   |
| Haabneeme     | 1        | 0.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 53       | 82     | 21.12%  |
| WDC                         | 36       | 59     | 14.34%  |
| Seagate                     | 35       | 51     | 13.94%  |
| Kingston                    | 25       | 39     | 9.96%   |
| Crucial                     | 16       | 26     | 6.37%   |
| Toshiba                     | 14       | 14     | 5.58%   |
| Hitachi                     | 10       | 14     | 3.98%   |
| Sandisk                     | 7        | 7      | 2.79%   |
| HGST                        | 7        | 10     | 2.79%   |
| A-DATA Technology           | 6        | 12     | 2.39%   |
| Patriot                     | 3        | 3      | 1.2%    |
| Intel                       | 3        | 4      | 1.2%    |
| Apacer                      | 3        | 4      | 1.2%    |
| XPG                         | 2        | 2      | 0.8%    |
| Unknown                     | 2        | 2      | 0.8%    |
| Silicon Motion              | 2        | 4      | 0.8%    |
| Maxtor                      | 2        | 2      | 0.8%    |
| KingSpec                    | 2        | 3      | 0.8%    |
| Gigabyte Technology         | 2        | 2      | 0.8%    |
| Corsair                     | 2        | 2      | 0.8%    |
| China                       | 2        | 2      | 0.8%    |
| ADATA Technology            | 2        | 2      | 0.8%    |
| ZADAK                       | 1        | 1      | 0.4%    |
| Team                        | 1        | 2      | 0.4%    |
| SPCC                        | 1        | 1      | 0.4%    |
| SK hynix                    | 1        | 1      | 0.4%    |
| Plextor                     | 1        | 1      | 0.4%    |
| Phison Electronics          | 1        | 1      | 0.4%    |
| Micron/Crucial Technology   | 1        | 1      | 0.4%    |
| KIOXIA-EXCERIA              | 1        | 1      | 0.4%    |
| Kingston Technology Company | 1        | 1      | 0.4%    |
| Intenso                     | 1        | 1      | 0.4%    |
| Integral                    | 1        | 1      | 0.4%    |
| Inateck                     | 1        | 1      | 0.4%    |
| i-FlashDisk                 | 1        | 1      | 0.4%    |
| ASMT                        | 1        | 1      | 0.4%    |
| Apple                       | 1        | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                         | 7        | 2.34%   |
| Seagate ST2000DM008-2FR102 2TB                    | 5        | 1.67%   |
| Seagate ST1000DM010-2EP102 1TB                    | 5        | 1.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 5        | 1.67%   |
| Kingston SA400S37240G 240GB SSD                   | 5        | 1.67%   |
| Toshiba DT01ACA100 1TB                            | 4        | 1.34%   |
| Samsung SSD 860 EVO 250GB                         | 4        | 1.34%   |
| Samsung NVMe SSD Drive 1TB                        | 4        | 1.34%   |
| Samsung HD103SJ 1TB                               | 4        | 1.34%   |
| Seagate ST500LT012-9WS142 500GB                   | 3        | 1%      |
| Seagate ST500DM002-1BD142 500GB                   | 3        | 1%      |
| Samsung SSD 960 PRO 512GB                         | 3        | 1%      |
| Samsung SSD 850 EVO 500GB                         | 3        | 1%      |
| Samsung MZ7TY128HDHP-000L1 128GB SSD              | 3        | 1%      |
| Samsung HD080HJ 80GB                              | 3        | 1%      |
| Kingston SA400S37120G 120GB SSD                   | 3        | 1%      |
| Crucial CT500MX500SSD1 500GB                      | 3        | 1%      |
| A-DATA SX8200PNP 512GB                            | 3        | 1%      |
| WDC WD10EZRZ-00HTKB0 1TB                          | 2        | 0.67%   |
| WDC WD10EADS-00M2B0 1TB                           | 2        | 0.67%   |
| Unknown ArtisanTribute-512GB                      | 2        | 0.67%   |
| Toshiba HDWD130 3TB                               | 2        | 0.67%   |
| Seagate ST3250318AS 250GB                         | 2        | 0.67%   |
| Seagate ST1000DM003-1SB102 1TB                    | 2        | 0.67%   |
| Seagate ST1000DM003-1ER162 1TB                    | 2        | 0.67%   |
| Sandisk WD Blue SN570 1TB                         | 2        | 0.67%   |
| Samsung SSD 970 EVO Plus 500GB                    | 2        | 0.67%   |
| Samsung SSD 870 QVO 1TB                           | 2        | 0.67%   |
| Samsung SSD 860 EVO 500GB                         | 2        | 0.67%   |
| Samsung SSD 850 PRO 256GB                         | 2        | 0.67%   |
| Samsung SSD 840 PRO Series 128GB                  | 2        | 0.67%   |
| Samsung SP0802N 80GB                              | 2        | 0.67%   |
| Kingston SUV400S37240G 240GB SSD                  | 2        | 0.67%   |
| Kingston SA400S37480G 480GB SSD                   | 2        | 0.67%   |
| Hitachi HTS723225L9A360 250GB                     | 2        | 0.67%   |
| HGST HTS541010A9E680 1TB                          | 2        | 0.67%   |
| Crucial CT2000MX500SSD1 2TB                       | 2        | 0.67%   |
| Crucial CT128MX100SSD1 128GB                      | 2        | 0.67%   |
| Crucial CT1000MX500SSD1 1TB                       | 2        | 0.67%   |
| Apacer AS350 512GB SSD                            | 2        | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 34       | 50     | 29.31%  |
| WDC                 | 33       | 50     | 28.45%  |
| Samsung Electronics | 16       | 20     | 13.79%  |
| Toshiba             | 13       | 13     | 11.21%  |
| Hitachi             | 10       | 14     | 8.62%   |
| HGST                | 7        | 10     | 6.03%   |
| Maxtor              | 2        | 2      | 1.72%   |
| Apple               | 1        | 1      | 0.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 29       | 38     | 29%     |
| Kingston            | 19       | 29     | 19%     |
| Crucial             | 16       | 26     | 16%     |
| WDC                 | 5        | 7      | 5%      |
| SanDisk             | 5        | 5      | 5%      |
| A-DATA Technology   | 4        | 9      | 4%      |
| Patriot             | 3        | 3      | 3%      |
| Apacer              | 3        | 4      | 3%      |
| KingSpec            | 2        | 3      | 2%      |
| Intel               | 2        | 2      | 2%      |
| Corsair             | 2        | 2      | 2%      |
| China               | 2        | 2      | 2%      |
| Team                | 1        | 2      | 1%      |
| SPCC                | 1        | 1      | 1%      |
| Plextor             | 1        | 1      | 1%      |
| Intenso             | 1        | 1      | 1%      |
| Integral            | 1        | 1      | 1%      |
| i-FlashDisk         | 1        | 1      | 1%      |
| Gigabyte Technology | 1        | 1      | 1%      |
| ASMT                | 1        | 1      | 1%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 87       | 160    | 42.03%  |
| SSD     | 75       | 139    | 36.23%  |
| NVMe    | 41       | 59     | 19.81%  |
| Unknown | 4        | 4      | 1.93%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 120      | 299    | 72.29%  |
| NVMe | 41       | 58     | 24.7%   |
| SAS  | 5        | 5      | 3.01%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 97       | 182    | 53.89%  |
| 0.51-1.0   | 48       | 69     | 26.67%  |
| 1.01-2.0   | 17       | 23     | 9.44%   |
| 3.01-4.0   | 6        | 6      | 3.33%   |
| 2.01-3.0   | 6        | 13     | 3.33%   |
| 4.01-10.0  | 5        | 5      | 2.78%   |
| 10.01-20.0 | 1        | 1      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 26       | 18.84%  |
| 101-250        | 25       | 18.12%  |
| 1001-2000      | 18       | 13.04%  |
| More than 3000 | 17       | 12.32%  |
| 501-1000       | 15       | 10.87%  |
| 1-20           | 14       | 10.14%  |
| 51-100         | 7        | 5.07%   |
| 2001-3000      | 6        | 4.35%   |
| Unknown        | 6        | 4.35%   |
| 21-50          | 4        | 2.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 50       | 35.71%  |
| 21-50          | 17       | 12.14%  |
| 101-250        | 17       | 12.14%  |
| 1001-2000      | 11       | 7.86%   |
| 501-1000       | 11       | 7.86%   |
| 51-100         | 10       | 7.14%   |
| 251-500        | 9        | 6.43%   |
| More than 3000 | 8        | 5.71%   |
| Unknown        | 6        | 4.29%   |
| 2001-3000      | 1        | 0.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| Crucial CT128MX100SSD1 128GB                 | 2        | 3      | 6.67%   |
| WDC WD60EFRX-68MYMN1 6TB                     | 1        | 1      | 3.33%   |
| WDC WD5002AALX-00J37A0 500GB                 | 1        | 1      | 3.33%   |
| WDC WD5000BPVT-00HXZT1 500GB                 | 1        | 1      | 3.33%   |
| WDC WD5000AAKX-00ERMA0 500GB                 | 1        | 1      | 3.33%   |
| WDC WD20EZRX-00DC0B0 2TB                     | 1        | 2      | 3.33%   |
| WDC WD20EARX-00PASB0 2TB                     | 1        | 1      | 3.33%   |
| WDC WD10PURX-64E5EY0 1TB                     | 1        | 1      | 3.33%   |
| WDC WD10EAVS-00D7B1 1TB                      | 1        | 1      | 3.33%   |
| WDC WD10EADS-00M2B0 1TB                      | 1        | 2      | 3.33%   |
| Toshiba MK6475GSX 640GB                      | 1        | 1      | 3.33%   |
| Toshiba MK3261GSYN 320GB                     | 1        | 1      | 3.33%   |
| Seagate ST500DM002-1BD142 500GB              | 1        | 1      | 3.33%   |
| Seagate ST340016A 40GB                       | 1        | 2      | 3.33%   |
| Seagate ST31000528AS 1TB                     | 1        | 1      | 3.33%   |
| Seagate ST3000DM008-2DM166 3TB               | 1        | 1      | 3.33%   |
| Seagate ST1000DM010-2EP102 1TB               | 1        | 1      | 3.33%   |
| Samsung Electronics SSD 840 PRO Series 128GB | 1        | 1      | 3.33%   |
| Samsung Electronics SP0802N 80GB             | 1        | 1      | 3.33%   |
| Samsung Electronics HD642JJ 640GB            | 1        | 1      | 3.33%   |
| Samsung Electronics HD501LJ 500GB            | 1        | 1      | 3.33%   |
| Samsung Electronics HD103SJ 1TB              | 1        | 1      | 3.33%   |
| Samsung Electronics HD080HJ 80GB             | 1        | 1      | 3.33%   |
| Patriot P210 256GB SSD                       | 1        | 1      | 3.33%   |
| Patriot Burst 480GB SSD                      | 1        | 1      | 3.33%   |
| Maxtor STM3250310AS 250GB                    | 1        | 1      | 3.33%   |
| Hitachi HDS721680PLA380 80GB                 | 1        | 1      | 3.33%   |
| Hitachi HDS721010DLE630 1TB                  | 1        | 1      | 3.33%   |
| Crucial CT256MX100SSD1 256GB                 | 1        | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 11     | 28.57%  |
| Seagate             | 5        | 6      | 17.86%  |
| Samsung Electronics | 5        | 6      | 17.86%  |
| Crucial             | 3        | 4      | 10.71%  |
| Toshiba             | 2        | 2      | 7.14%   |
| Patriot             | 2        | 2      | 7.14%   |
| Hitachi             | 2        | 2      | 7.14%   |
| Maxtor              | 1        | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 11     | 36.36%  |
| Seagate             | 5        | 6      | 22.73%  |
| Samsung Electronics | 4        | 5      | 18.18%  |
| Toshiba             | 2        | 2      | 9.09%   |
| Hitachi             | 2        | 2      | 9.09%   |
| Maxtor              | 1        | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 20       | 27     | 80%     |
| SSD  | 5        | 7      | 20%     |

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
| Works    | 69       | 157    | 45.1%   |
| Detected | 58       | 170    | 37.91%  |
| Malfunc  | 25       | 34     | 16.34%  |
| Failed   | 1        | 1      | 0.65%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 81       | 42.19%  |
| AMD                          | 43       | 22.4%   |
| Samsung Electronics          | 18       | 9.38%   |
| Kingston Technology Company  | 8        | 4.17%   |
| Marvell Technology Group     | 6        | 3.13%   |
| ADATA Technology             | 6        | 3.13%   |
| Nvidia                       | 5        | 2.6%    |
| ASMedia Technology           | 5        | 2.6%    |
| SanDisk                      | 4        | 2.08%   |
| Silicon Motion               | 3        | 1.56%   |
| VIA Technologies             | 2        | 1.04%   |
| Phison Electronics           | 2        | 1.04%   |
| JMicron Technology           | 2        | 1.04%   |
| Toshiba America Info Systems | 1        | 0.52%   |
| SK hynix                     | 1        | 0.52%   |
| Silicon Image                | 1        | 0.52%   |
| Seagate Technology           | 1        | 0.52%   |
| Micron/Crucial Technology    | 1        | 0.52%   |
| KIOXIA                       | 1        | 0.52%   |
| Adaptec                      | 1        | 0.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 22       | 9.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15       | 6.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 13       | 5.68%   |
| AMD 500 Series Chipset SATA Controller                                                  | 9        | 3.93%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9        | 3.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 3.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 3.06%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 3.06%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 2.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5        | 2.18%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 2.18%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 2.18%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 5        | 2.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 2.18%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 2.18%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 5        | 2.18%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 1.75%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 3        | 1.31%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 1.31%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.31%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 2        | 0.87%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 0.87%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 2        | 0.87%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 2        | 0.87%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.87%   |
| Nvidia CK804 Serial ATA Controller                                                      | 2        | 0.87%   |
| Nvidia CK804 IDE                                                                        | 2        | 0.87%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                          | 2        | 0.87%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.87%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 0.87%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.87%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2        | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 0.87%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.87%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.87%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 0.87%   |
| AMD 600 Series Chipset SATA Controller                                                  | 2        | 0.87%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 113      | 61.41%  |
| NVMe | 41       | 22.28%  |
| IDE  | 25       | 13.59%  |
| RAID | 4        | 2.17%   |
| SCSI | 1        | 0.54%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 81       | 62.31%  |
| AMD                   | 48       | 36.92%  |
| Marvell Semiconductor | 1        | 0.77%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor                                  | 6        | 4.62%   |
| AMD Ryzen 5 3600 6-Core Processor                                   | 4        | 3.08%   |
| Intel Core i7-4790 CPU @ 3.60GHz                                    | 3        | 2.31%   |
| Intel Core i3-4130 CPU @ 3.40GHz                                    | 3        | 2.31%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz                                | 3        | 2.31%   |
| AMD Ryzen 9 5900X 12-Core Processor                                 | 3        | 2.31%   |
| Intel Core i7-7700 CPU @ 3.60GHz                                    | 2        | 1.54%   |
| Intel Core i5-9600K CPU @ 3.70GHz                                   | 2        | 1.54%   |
| Intel Core i5-4690K CPU @ 3.50GHz                                   | 2        | 1.54%   |
| Intel Core i5-4590 CPU @ 3.30GHz                                    | 2        | 1.54%   |
| Intel Core i5-4460 CPU @ 3.20GHz                                    | 2        | 1.54%   |
| Intel Core i5-2500 CPU @ 3.30GHz                                    | 2        | 1.54%   |
| Intel Core i3-3217U CPU @ 1.80GHz                                   | 2        | 1.54%   |
| AMD Ryzen 9 7950X 16-Core Processor                                 | 2        | 1.54%   |
| AMD Ryzen 9 3900X 12-Core Processor                                 | 2        | 1.54%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics                          | 2        | 1.54%   |
| AMD Ryzen 5 5600X 6-Core Processor                                  | 2        | 1.54%   |
| AMD FX-8350 Eight-Core Processor                                    | 2        | 1.54%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+                          | 2        | 1.54%   |
| Marvell Semiconductor Marvell Armada 370/XP (Device Tree) Processor | 1        | 0.77%   |
| Intel Xeon CPU E5620 @ 2.40GHz                                      | 1        | 0.77%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz                                  | 1        | 0.77%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz                                 | 1        | 0.77%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz                                 | 1        | 0.77%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz                              | 1        | 0.77%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz                         | 1        | 0.77%   |
| Intel Pentium D CPU 2.80GHz                                         | 1        | 0.77%   |
| Intel Pentium CPU G850 @ 2.90GHz                                    | 1        | 0.77%   |
| Intel Pentium CPU G4560T @ 2.90GHz                                  | 1        | 0.77%   |
| Intel Pentium CPU G2120 @ 3.10GHz                                   | 1        | 0.77%   |
| Intel Pentium CPU G2030 @ 3.00GHz                                   | 1        | 0.77%   |
| Intel Pentium 4 CPU 3.00GHz                                         | 1        | 0.77%   |
| Intel Core i9-9900K CPU @ 3.60GHz                                   | 1        | 0.77%   |
| Intel Core i9-7940X CPU @ 3.10GHz                                   | 1        | 0.77%   |
| Intel Core i7-8700K CPU @ 3.70GHz                                   | 1        | 0.77%   |
| Intel Core i7-8700 CPU @ 3.20GHz                                    | 1        | 0.77%   |
| Intel Core i7-6700K CPU @ 4.00GHz                                   | 1        | 0.77%   |
| Intel Core i7-4770 CPU @ 3.40GHz                                    | 1        | 0.77%   |
| Intel Core i7-3820 CPU @ 3.60GHz                                    | 1        | 0.77%   |
| Intel Core i7-3770K CPU @ 3.50GHz                                   | 1        | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 27       | 20.77%  |
| Intel Core i7           | 12       | 9.23%   |
| Intel Core i3           | 12       | 9.23%   |
| AMD Ryzen 7             | 12       | 9.23%   |
| AMD Ryzen 5             | 10       | 7.69%   |
| AMD Ryzen 9             | 8        | 6.15%   |
| Other                   | 7        | 5.38%   |
| Intel Core 2 Duo        | 5        | 3.85%   |
| Intel Celeron           | 5        | 3.85%   |
| Intel Xeon              | 4        | 3.08%   |
| Intel Pentium           | 4        | 3.08%   |
| AMD Phenom II X4        | 4        | 3.08%   |
| AMD FX                  | 4        | 3.08%   |
| AMD Athlon 64 X2        | 3        | 2.31%   |
| Intel Core i9           | 2        | 1.54%   |
| AMD Ryzen 7 PRO         | 2        | 1.54%   |
| AMD A10                 | 2        | 1.54%   |
| Intel Pentium Gold      | 1        | 0.77%   |
| Intel Pentium Dual-Core | 1        | 0.77%   |
| Intel Pentium D         | 1        | 0.77%   |
| Intel Pentium 4         | 1        | 0.77%   |
| AMD Ryzen 3 PRO         | 1        | 0.77%   |
| AMD Phenom II X6        | 1        | 0.77%   |
| AMD Athlon XP           | 1        | 0.77%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 43       | 33.08%  |
| 2       | 31       | 23.85%  |
| 6       | 20       | 15.38%  |
| 8       | 19       | 14.62%  |
| 12      | 6        | 4.62%   |
| 1       | 4        | 3.08%   |
| 16      | 3        | 2.31%   |
| 14      | 2        | 1.54%   |
| 3       | 1        | 0.77%   |
| Unknown | 1        | 0.77%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 129      | 99.23%  |
| 2      | 1        | 0.77%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 75       | 57.69%  |
| 1       | 54       | 41.54%  |
| Unknown | 1        | 0.77%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 127      | 97.69%  |
| Unknown        | 2        | 1.54%   |
| 32-bit         | 1        | 0.77%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 44       | 32.12%  |
| 0x306c3    | 11       | 8.03%   |
| 0x306a9    | 9        | 6.57%   |
| 0x08701021 | 7        | 5.11%   |
| 0x206a7    | 5        | 3.65%   |
| 0x08701013 | 5        | 3.65%   |
| 0x906ea    | 4        | 2.92%   |
| 0x906e9    | 4        | 2.92%   |
| 0x1067a    | 4        | 2.92%   |
| 0xa0655    | 3        | 2.19%   |
| 0x90672    | 3        | 2.19%   |
| 0x06000852 | 3        | 2.19%   |
| 0xa0671    | 2        | 1.46%   |
| 0x506e3    | 2        | 1.46%   |
| 0x20655    | 2        | 1.46%   |
| 0x08001138 | 2        | 1.46%   |
| 0x06003106 | 2        | 1.46%   |
| 0x010000db | 2        | 1.46%   |
| 0xf64      | 1        | 0.73%   |
| 0xf4a      | 1        | 0.73%   |
| 0xa0653    | 1        | 0.73%   |
| 0x906ed    | 1        | 0.73%   |
| 0x906eb    | 1        | 0.73%   |
| 0x6fd      | 1        | 0.73%   |
| 0x6fb      | 1        | 0.73%   |
| 0x50654    | 1        | 0.73%   |
| 0x406c3    | 1        | 0.73%   |
| 0x206d7    | 1        | 0.73%   |
| 0x20652    | 1        | 0.73%   |
| 0x10676    | 1        | 0.73%   |
| 0x10661    | 1        | 0.73%   |
| 0x0a601206 | 1        | 0.73%   |
| 0x0a601203 | 1        | 0.73%   |
| 0x0a201016 | 1        | 0.73%   |
| 0x0a201009 | 1        | 0.73%   |
| 0x08600106 | 1        | 0.73%   |
| 0x08600103 | 1        | 0.73%   |
| 0x08108109 | 1        | 0.73%   |
| 0x0810100b | 1        | 0.73%   |
| 0x0800820d | 1        | 0.73%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 18       | 13.85%  |
| Haswell          | 18       | 13.85%  |
| KabyLake         | 15       | 11.54%  |
| IvyBridge        | 10       | 7.69%   |
| SandyBridge      | 8        | 6.15%   |
| Zen 3            | 7        | 5.38%   |
| Westmere         | 5        | 3.85%   |
| Penryn           | 5        | 3.85%   |
| K10              | 5        | 3.85%   |
| Skylake          | 4        | 3.08%   |
| Piledriver       | 4        | 3.08%   |
| CometLake        | 4        | 3.08%   |
| Alderlake Hybrid | 4        | 3.08%   |
| Zen+             | 3        | 2.31%   |
| Zen              | 3        | 2.31%   |
| K8 Hammer        | 3        | 2.31%   |
| Core             | 3        | 2.31%   |
| Unknown          | 3        | 2.31%   |
| Steamroller      | 2        | 1.54%   |
| NetBurst         | 2        | 1.54%   |
| Icelake          | 2        | 1.54%   |
| Silvermont       | 1        | 0.77%   |
| K6               | 1        | 0.77%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 69       | 46.31%  |
| Intel  | 41       | 27.52%  |
| AMD    | 39       | 26.17%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 12       | 7.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 4.61%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 3.95%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 3.29%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 2.63%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 2.63%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 1.97%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 1.97%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.97%   |
| Intel Core Processor Integrated Graphics Controller                         | 3        | 1.97%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 1.97%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 1.32%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 1.32%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 2        | 1.32%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 1.32%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 1.32%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.32%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 1.32%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 1.32%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 2        | 1.32%   |
| Intel HD Graphics 630                                                       | 2        | 1.32%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 1.32%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.32%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 2        | 1.32%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.32%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 2        | 1.32%   |
| AMD RV610 [Radeon HD 2400 PRO]                                              | 2        | 1.32%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 2        | 1.32%   |
| AMD Raphael                                                                 | 2        | 1.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.32%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 1.32%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.66%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.66%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.66%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 0.66%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.66%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.66%   |
| Nvidia NV43GL [Quadro FX 540]                                               | 1        | 0.66%   |
| Nvidia NV43 [GeForce 6600 GT]                                               | 1        | 0.66%   |
| Nvidia NV34 [GeForce FX 5200]                                               | 1        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 59       | 44.7%   |
| 1 x AMD        | 30       | 22.73%  |
| 1 x Intel      | 29       | 21.97%  |
| Intel + Nvidia | 5        | 3.79%   |
| Intel + AMD    | 3        | 2.27%   |
| AMD + Nvidia   | 3        | 2.27%   |
| 2 x AMD        | 2        | 1.52%   |
| Other          | 1        | 0.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 81       | 60%     |
| Proprietary | 45       | 33.33%  |
| Unknown     | 9        | 6.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 51       | 37.78%  |
| 7.01-8.0   | 17       | 12.59%  |
| 1.01-2.0   | 17       | 12.59%  |
| 3.01-4.0   | 14       | 10.37%  |
| 0.01-0.5   | 11       | 8.15%   |
| 8.01-16.0  | 8        | 5.93%   |
| 0.51-1.0   | 8        | 5.93%   |
| 5.01-6.0   | 5        | 3.7%    |
| 16.01-24.0 | 2        | 1.48%   |
| 4.01-5.0   | 1        | 0.74%   |
| 2.01-3.0   | 1        | 0.74%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 27       | 19.42%  |
| Dell                 | 26       | 18.71%  |
| Goldstar             | 19       | 13.67%  |
| AOC                  | 11       | 7.91%   |
| Philips              | 9        | 6.47%   |
| Hewlett-Packard      | 9        | 6.47%   |
| ViewSonic            | 8        | 5.76%   |
| BenQ                 | 5        | 3.6%    |
| Ancor Communications | 4        | 2.88%   |
| Hitachi              | 3        | 2.16%   |
| Unknown              | 2        | 1.44%   |
| RoverScan            | 2        | 1.44%   |
| Lenovo               | 2        | 1.44%   |
| ASUSTek Computer     | 2        | 1.44%   |
| Tech Concepts        | 1        | 0.72%   |
| Plain Tree Systems   | 1        | 0.72%   |
| LG Electronics       | 1        | 0.72%   |
| Lenovo Group Limited | 1        | 0.72%   |
| Gigabyte Technology  | 1        | 0.72%   |
| Fujitsu Siemens      | 1        | 0.72%   |
| Eizo                 | 1        | 0.72%   |
| Belinea              | 1        | 0.72%   |
| Acer                 | 1        | 0.72%   |
| Unknown              | 1        | 0.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 340x270mm 17.1-inch        | 2        | 1.32%   |
| Samsung Electronics S32D850 SAM0BCB 2560x1440 708x398mm 32.0-inch    | 2        | 1.32%   |
| Samsung Electronics S24C650 SAM0B18 1920x1200 518x324mm 24.1-inch    | 2        | 1.32%   |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch              | 2        | 1.32%   |
| Hewlett-Packard ZR24w HWP2869 1920x1200 546x352mm 25.6-inch          | 2        | 1.32%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                 | 2        | 1.32%   |
| Goldstar LG ULTRAGEAR GSM5B80 2560x1440 600x340mm 27.2-inch          | 2        | 1.32%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 2        | 1.32%   |
| Dell U2719D DEL415A 2560x1440 597x336mm 27.0-inch                    | 2        | 1.32%   |
| Dell U2312HM DEL4073 1920x1080 510x287mm 23.0-inch                   | 2        | 1.32%   |
| Dell P2314H DEL4098 1920x1080 509x286mm 23.0-inch                    | 2        | 1.32%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                  | 2        | 1.32%   |
| AOC G2460PG AOC2460 1920x1080 531x299mm 24.0-inch                    | 2        | 1.32%   |
| ViewSonic XG2405 VSC0D39 1920x1080 527x296mm 23.8-inch               | 1        | 0.66%   |
| ViewSonic VP920 Series VSCB01C 1280x1024 376x301mm 19.0-inch         | 1        | 0.66%   |
| ViewSonic VG2428wm VSCA426 1920x1080 520x290mm 23.4-inch             | 1        | 0.66%   |
| ViewSonic VG170m VSCBF0C 1280x1024 338x270mm 17.0-inch               | 1        | 0.66%   |
| ViewSonic VE902m VSC491B 1280x1024 376x301mm 19.0-inch               | 1        | 0.66%   |
| ViewSonic VA2445 SERIES VSC712E 1920x1080 521x293mm 23.5-inch        | 1        | 0.66%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                | 1        | 0.66%   |
| Unknown LCD Monitor GBT G34WQC 3440x1440                             | 1        | 0.66%   |
| Tech Concepts LCD Monitor MT5531 1920x1080                           | 1        | 0.66%   |
| Samsung Electronics U28H75x SAM0E00 3840x2160 607x345mm 27.5-inch    | 1        | 0.66%   |
| Samsung Electronics U28H75x SAM0DFF 3840x2160 608x345mm 27.5-inch    | 1        | 0.66%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 1        | 0.66%   |
| Samsung Electronics TV SAM0289 1280x720                              | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch  | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM027D 1680x1050 433x271mm 20.1-inch | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM027C 1680x1050 433x271mm 20.1-inch | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 380x300mm 19.1-inch | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM0193 1280x1024 376x301mm 19.0-inch | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 376x301mm 19.0-inch | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch | 1        | 0.66%   |
| Samsung Electronics S24E390 SAM0C1A 1920x1080 521x293mm 23.5-inch    | 1        | 0.66%   |
| Samsung Electronics S24C450 SAM09CB 1920x1080 531x299mm 24.0-inch    | 1        | 0.66%   |
| Samsung Electronics S22R35x SAM103A 1920x1080 476x268mm 21.5-inch    | 1        | 0.66%   |
| Samsung Electronics S22B350 SAM08D4 1920x1080 477x268mm 21.5-inch    | 1        | 0.66%   |
| Samsung Electronics LS28AG700N SAM7177 3840x2160 632x360mm 28.6-inch | 1        | 0.66%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 51       | 38.06%  |
| 1280x1024 (SXGA)   | 19       | 14.18%  |
| 2560x1440 (QHD)    | 18       | 13.43%  |
| 3840x2160 (4K)     | 17       | 12.69%  |
| 1920x1200 (WUXGA)  | 12       | 8.96%   |
| 3440x1440          | 5        | 3.73%   |
| 1680x1050 (WSXGA+) | 3        | 2.24%   |
| 1440x900 (WXGA+)   | 3        | 2.24%   |
| 1600x900 (HD+)     | 2        | 1.49%   |
| 1366x768 (WXGA)    | 2        | 1.49%   |
| 1920x540           | 1        | 0.75%   |
| 1360x768           | 1        | 0.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 23       | 16.2%   |
| 27      | 20       | 14.08%  |
| 23      | 20       | 14.08%  |
| 17      | 13       | 9.15%   |
| 21      | 12       | 8.45%   |
| Unknown | 12       | 8.45%   |
| 19      | 8        | 5.63%   |
| 31      | 5        | 3.52%   |
| 32      | 4        | 2.82%   |
| 20      | 4        | 2.82%   |
| 84      | 3        | 2.11%   |
| 40      | 3        | 2.11%   |
| 34      | 3        | 2.11%   |
| 25      | 3        | 2.11%   |
| 18      | 3        | 2.11%   |
| 33      | 2        | 1.41%   |
| 54      | 1        | 0.7%    |
| 43      | 1        | 0.7%    |
| 28      | 1        | 0.7%    |
| 15      | 1        | 0.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 55       | 40.74%  |
| 401-500     | 21       | 15.56%  |
| 301-350     | 14       | 10.37%  |
| Unknown     | 12       | 8.89%   |
| 601-700     | 11       | 8.15%   |
| 701-800     | 9        | 6.67%   |
| 351-400     | 5        | 3.7%    |
| 801-900     | 3        | 2.22%   |
| 1501-2000   | 3        | 2.22%   |
| 1001-1500   | 1        | 0.74%   |
| 901-1000    | 1        | 0.74%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 71       | 55.47%  |
| 16/10   | 23       | 17.97%  |
| 5/4     | 16       | 12.5%   |
| Unknown | 11       | 8.59%   |
| 21/9    | 3        | 2.34%   |
| 6/5     | 2        | 1.56%   |
| 4/3     | 1        | 0.78%   |
| 32/9    | 1        | 0.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 35       | 25%     |
| 301-350        | 20       | 14.29%  |
| 251-300        | 20       | 14.29%  |
| 351-500        | 15       | 10.71%  |
| 141-150        | 15       | 10.71%  |
| 151-200        | 14       | 10%     |
| Unknown        | 12       | 8.57%   |
| More than 1000 | 4        | 2.86%   |
| 501-1000       | 4        | 2.86%   |
| 101-110        | 1        | 0.71%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 83       | 63.36%  |
| 101-120 | 25       | 19.08%  |
| Unknown | 12       | 9.16%   |
| 121-160 | 9        | 6.87%   |
| 1-50    | 2        | 1.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 96       | 72.73%  |
| 2     | 25       | 18.94%  |
| 0     | 8        | 6.06%   |
| 3     | 2        | 1.52%   |
| 4     | 1        | 0.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 74       | 43.02%  |
| Intel                           | 50       | 29.07%  |
| TP-Link                         | 7        | 4.07%   |
| Qualcomm Atheros                | 6        | 3.49%   |
| Ralink Technology               | 5        | 2.91%   |
| Nvidia                          | 5        | 2.91%   |
| MediaTek                        | 4        | 2.33%   |
| Ralink                          | 3        | 1.74%   |
| Microsoft                       | 3        | 1.74%   |
| Broadcom                        | 3        | 1.74%   |
| Samsung Electronics             | 2        | 1.16%   |
| Marvell Technology Group        | 2        | 1.16%   |
| D-Link System                   | 2        | 1.16%   |
| Broadcom Limited                | 2        | 1.16%   |
| Qualcomm Atheros Communications | 1        | 0.58%   |
| D-Link                          | 1        | 0.58%   |
| Aquantia                        | 1        | 0.58%   |
| Apple                           | 1        | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 60       | 31.41%  |
| Realtek RTL8125 2.5GbE Controller                                      | 7        | 3.66%   |
| Intel I211 Gigabit Network Connection                                  | 7        | 3.66%   |
| Intel Ethernet Connection (7) I219-V                                   | 6        | 3.14%   |
| Intel Ethernet Controller I225-V                                       | 5        | 2.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 4        | 2.09%   |
| Intel Wi-Fi 6 AX200                                                    | 3        | 1.57%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 1.57%   |
| Intel Ethernet Connection (2) I219-V                                   | 3        | 1.57%   |
| Intel 82579V Gigabit Network Connection                                | 3        | 1.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 1.57%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                              | 2        | 1.05%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2        | 1.05%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 2        | 1.05%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 2        | 1.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2        | 1.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 1.05%   |
| Ralink RT5370 Wireless Adapter                                         | 2        | 1.05%   |
| Ralink MT7601U Wireless Adapter                                        | 2        | 1.05%   |
| Ralink RT2500 Wireless 802.11bg                                        | 2        | 1.05%   |
| Nvidia CK804 Ethernet Controller                                       | 2        | 1.05%   |
| Microsoft Xbox 360 Wireless Adapter                                    | 2        | 1.05%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2        | 1.05%   |
| Intel Ethernet Connection I217-V                                       | 2        | 1.05%   |
| Intel Ethernet Connection (2) I218-V                                   | 2        | 1.05%   |
| Intel 82578DM Gigabit Network Connection                               | 2        | 1.05%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2        | 1.05%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 1        | 0.52%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1        | 0.52%   |
| TP-Link Archer T4U ver.3                                               | 1        | 0.52%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 1        | 0.52%   |
| TP-Link 802.11ac WLAN Adapter                                          | 1        | 0.52%   |
| TP-Link 802.11ac NIC                                                   | 1        | 0.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1        | 0.52%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 1        | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 0.52%   |
| Ralink RT2770 Wireless Adapter                                         | 1        | 0.52%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                              | 1        | 0.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1        | 0.52%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 10       | 21.28%  |
| Realtek Semiconductor           | 9        | 19.15%  |
| TP-Link                         | 7        | 14.89%  |
| Ralink Technology               | 5        | 10.64%  |
| Ralink                          | 3        | 6.38%   |
| Qualcomm Atheros                | 3        | 6.38%   |
| Microsoft                       | 3        | 6.38%   |
| MediaTek                        | 3        | 6.38%   |
| Qualcomm Atheros Communications | 1        | 2.13%   |
| D-Link System                   | 1        | 2.13%   |
| D-Link                          | 1        | 2.13%   |
| Broadcom                        | 1        | 2.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 4        | 8.16%   |
| Intel Wi-Fi 6 AX200                                                  | 3        | 6.12%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                            | 2        | 4.08%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 2        | 4.08%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 2        | 4.08%   |
| Ralink RT5370 Wireless Adapter                                       | 2        | 4.08%   |
| Ralink MT7601U Wireless Adapter                                      | 2        | 4.08%   |
| Ralink RT2500 Wireless 802.11bg                                      | 2        | 4.08%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 2        | 4.08%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 2        | 4.08%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1        | 2.04%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 1        | 2.04%   |
| TP-Link Archer T4U ver.3                                             | 1        | 2.04%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                  | 1        | 2.04%   |
| TP-Link 802.11ac WLAN Adapter                                        | 1        | 2.04%   |
| TP-Link 802.11ac NIC                                                 | 1        | 2.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1        | 2.04%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 1        | 2.04%   |
| Ralink RT2770 Wireless Adapter                                       | 1        | 2.04%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1        | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1        | 2.04%   |
| Qualcomm Atheros AR9271 802.11n                                      | 1        | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 2.04%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 1        | 2.04%   |
| Microsoft Xbox Wireless Adapter for Windows                          | 1        | 2.04%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 1        | 2.04%   |
| Intel Wireless 3165                                                  | 1        | 2.04%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 1        | 2.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1        | 2.04%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 1        | 2.04%   |
| Intel Centrino Wireless-N 2230                                       | 1        | 2.04%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                        | 1        | 2.04%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 1        | 2.04%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1        | 2.04%   |
| D-Link DWA-171                                                       | 1        | 2.04%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 1        | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 70       | 51.47%  |
| Intel                    | 46       | 33.82%  |
| Nvidia                   | 5        | 3.68%   |
| Qualcomm Atheros         | 3        | 2.21%   |
| Samsung Electronics      | 2        | 1.47%   |
| Marvell Technology Group | 2        | 1.47%   |
| Broadcom Limited         | 2        | 1.47%   |
| Broadcom                 | 2        | 1.47%   |
| MediaTek                 | 1        | 0.74%   |
| D-Link System            | 1        | 0.74%   |
| Aquantia                 | 1        | 0.74%   |
| Apple                    | 1        | 0.74%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 60       | 42.25%  |
| Realtek RTL8125 2.5GbE Controller                                             | 7        | 4.93%   |
| Intel I211 Gigabit Network Connection                                         | 7        | 4.93%   |
| Intel Ethernet Connection (7) I219-V                                          | 6        | 4.23%   |
| Intel Ethernet Controller I225-V                                              | 5        | 3.52%   |
| Intel Ethernet Connection I217-LM                                             | 3        | 2.11%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 2.11%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 2.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3        | 2.11%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 2        | 1.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2        | 1.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 1.41%   |
| Nvidia CK804 Ethernet Controller                                              | 2        | 1.41%   |
| Intel Ethernet Connection I217-V                                              | 2        | 1.41%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 1.41%   |
| Intel 82578DM Gigabit Network Connection                                      | 2        | 1.41%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 1.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 1        | 0.7%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1        | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.7%    |
| Nvidia nForce2 Ethernet Controller                                            | 1        | 0.7%    |
| Nvidia MCP77 Ethernet                                                         | 1        | 0.7%    |
| Nvidia MCP61 Ethernet                                                         | 1        | 0.7%    |
| MediaTek RMX3085                                                              | 1        | 0.7%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1        | 0.7%    |
| Marvell Group 88E8052 PCI-E ASF Gigabit Ethernet Controller                   | 1        | 0.7%    |
| Intel I350 Gigabit Network Connection                                         | 1        | 0.7%    |
| Intel I210 Gigabit Network Connection                                         | 1        | 0.7%    |
| Intel Ethernet Controller I219-V                                              | 1        | 0.7%    |
| Intel Ethernet Connection (5) I219-LM                                         | 1        | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 0.7%    |
| Intel Ethernet Connection (17) I219-V                                         | 1        | 0.7%    |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.7%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 0.7%    |
| Intel 82574L Gigabit Network Connection                                       | 1        | 0.7%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.7%    |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1        | 0.7%    |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1        | 0.7%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 1        | 0.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 127      | 73.41%  |
| WiFi     | 46       | 26.59%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 105      | 82.68%  |
| WiFi     | 22       | 17.32%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 96       | 73.85%  |
| 2     | 28       | 21.54%  |
| 0     | 3        | 2.31%   |
| 3     | 2        | 1.54%   |
| 6     | 1        | 0.77%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 105      | 80.77%  |
| Yes  | 25       | 19.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 13       | 32.5%   |
| Intel                           | 9        | 22.5%   |
| TP-Link                         | 4        | 10%     |
| Realtek Semiconductor           | 3        | 7.5%    |
| ASUSTek Computer                | 3        | 7.5%    |
| Foxconn / Hon Hai               | 2        | 5%      |
| Edimax Technology               | 2        | 5%      |
| Qualcomm Atheros Communications | 1        | 2.5%    |
| MediaTek                        | 1        | 2.5%    |
| Integrated System Solution      | 1        | 2.5%    |
| Broadcom                        | 1        | 2.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 13       | 32.5%   |
| TP-Link UB500 Adapter                                 | 4        | 10%     |
| Intel AX200 Bluetooth                                 | 3        | 7.5%    |
| Foxconn / Hon Hai Wireless_Device                     | 2        | 5%      |
| Edimax Edimax Bluetooth Adapter                       | 2        | 5%      |
| ASUS ASUS USB-BT500                                   | 2        | 5%      |
| Realtek RTL8821A Bluetooth                            | 1        | 2.5%    |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 2.5%    |
| Realtek Bluetooth Radio                               | 1        | 2.5%    |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 2.5%    |
| MediaTek Wireless_Device                              | 1        | 2.5%    |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 2.5%    |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 2.5%    |
| Intel Bluetooth wireless interface                    | 1        | 2.5%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 2.5%    |
| Intel AX211 Bluetooth                                 | 1        | 2.5%    |
| Intel AX210 Bluetooth                                 | 1        | 2.5%    |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 2.5%    |
| Broadcom Bluetooth 3.0+HS USB Adapter                 | 1        | 2.5%    |
| ASUS Bluetooth Radio                                  | 1        | 2.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 79       | 32.92%  |
| Nvidia                  | 66       | 27.5%   |
| AMD                     | 59       | 24.58%  |
| C-Media Electronics     | 7        | 2.92%   |
| Kingston Technology     | 6        | 2.5%    |
| Logitech                | 3        | 1.25%   |
| SteelSeries ApS         | 2        | 0.83%   |
| Razer USA               | 2        | 0.83%   |
| Focusrite-Novation      | 2        | 0.83%   |
| Creative Labs           | 2        | 0.83%   |
| ASUSTek Computer        | 2        | 0.83%   |
| TerraTec Electronic     | 1        | 0.42%   |
| Syntek                  | 1        | 0.42%   |
| Samson Technologies     | 1        | 0.42%   |
| M-Audio                 | 1        | 0.42%   |
| JMTek                   | 1        | 0.42%   |
| GYROCOM C&C             | 1        | 0.42%   |
| Generalplus Technology  | 1        | 0.42%   |
| DSEA A/S                | 1        | 0.42%   |
| DCMT Technology         | 1        | 0.42%   |
| BEHRINGER International | 1        | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 20       | 7.49%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15       | 5.62%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12       | 4.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9        | 3.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9        | 3.37%   |
| Intel Cannon Lake PCH cAVS                                                 | 8        | 3%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8        | 3%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 8        | 3%      |
| Intel 200 Series PCH HD Audio                                              | 7        | 2.62%   |
| Nvidia TU116 High Definition Audio Controller                              | 6        | 2.25%   |
| Nvidia TU106 High Definition Audio Controller                              | 6        | 2.25%   |
| Nvidia GP104 High Definition Audio Controller                              | 6        | 2.25%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6        | 2.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 1.87%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 1.5%    |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 1.5%    |
| Kingston Technology HyperX 7.1 Audio                                       | 4        | 1.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 1.5%    |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 1.12%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.12%   |
| Nvidia GP102 HDMI Audio Controller                                         | 3        | 1.12%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 1.12%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3        | 1.12%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 1.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 1.12%   |
| C-Media Electronics Blue Snowball                                          | 3        | 1.12%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 1.12%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3        | 1.12%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 1.12%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.75%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 0.75%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 0.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 0.75%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 0.75%   |
| Nvidia CK804 AC'97 Audio Controller                                        | 2        | 0.75%   |
| Nvidia Audio device                                                        | 2        | 0.75%   |
| Logitech Logitech G PRO X Gaming Headset                                   | 2        | 0.75%   |
| Kingston Technology HyperX Cloud Revolver S                                | 2        | 0.75%   |
| Intel Comet Lake PCH-V cAVS                                                | 2        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 20       | 20.62%  |
| G.Skill             | 18       | 18.56%  |
| Unknown             | 15       | 15.46%  |
| Crucial             | 9        | 9.28%   |
| SK hynix            | 7        | 7.22%   |
| Samsung Electronics | 7        | 7.22%   |
| Corsair             | 6        | 6.19%   |
| Patriot             | 2        | 2.06%   |
| Apacer              | 2        | 2.06%   |
| Wilk                | 1        | 1.03%   |
| Team                | 1        | 1.03%   |
| Silicon Power       | 1        | 1.03%   |
| Ramaxel Technology  | 1        | 1.03%   |
| Micron Technology   | 1        | 1.03%   |
| GOODRAM             | 1        | 1.03%   |
| Elpida              | 1        | 1.03%   |
| AMD                 | 1        | 1.03%   |
| Aeneon              | 1        | 1.03%   |
| A-DATA Technology   | 1        | 1.03%   |
| Unknown             | 1        | 1.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 512MB DIMM SDRAM                       | 2        | 1.82%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 2        | 1.82%   |
| SK hynix RAM HMT125U6TFR8C-G7 2GB DIMM DDR3 1067MT/s      | 2        | 1.82%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 2        | 1.82%   |
| Crucial RAM CT51264BA160BJ.C8 4GB DIMM DDR3 1632MT/s      | 2        | 1.82%   |
| Crucial RAM BLS8G4D240FSB.16FBR2 8GB DIMM DDR4 2400MT/s   | 2        | 1.82%   |
| Wilk RAM IRX3200D464L16SA/8G 8GB DIMM DDR4 3200MT/s       | 1        | 0.91%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                 | 1        | 0.91%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s              | 1        | 0.91%   |
| Unknown RAM Module 512MB DIMM                             | 1        | 0.91%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                    | 1        | 0.91%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1        | 0.91%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                  | 1        | 0.91%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                      | 1        | 0.91%   |
| Unknown RAM Module 256MB DIMM                             | 1        | 0.91%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 1        | 0.91%   |
| Unknown RAM Module 1GB DIMM SDRAM                         | 1        | 0.91%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s               | 1        | 0.91%   |
| Unknown RAM Module 1024MB DIMM                            | 1        | 0.91%   |
| Unknown RAM 1600 CL9 Series 8192MB DIMM DDR3 1066MT/s     | 1        | 0.91%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s       | 1        | 0.91%   |
| SK hynix RAM Module 8192MB DIMM DDR3 1333MT/s             | 1        | 0.91%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 0.91%   |
| SK hynix RAM HMT351U7BFR8C-H9 4GB DIMM DDR3 1333MT/s      | 1        | 0.91%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 1        | 0.91%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s      | 1        | 0.91%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s      | 1        | 0.91%   |
| Silicon Power RAM SP008GBLTU160N02 8GB DIMM DDR3 1600MT/s | 1        | 0.91%   |
| Silicon Power RAM DCLT8GN128S 8192MB DIMM DDR3 1600MT/s   | 1        | 0.91%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s  | 1        | 0.91%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 1        | 0.91%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s       | 1        | 0.91%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s    | 1        | 0.91%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s       | 1        | 0.91%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s       | 1        | 0.91%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s       | 1        | 0.91%   |
| Ramaxel RAM RMR1870EC58E9F133 4GB DIMM DDR3 1333MT/s      | 1        | 0.91%   |
| Patriot RAM PSD48G240082 8GB DIMM DDR4 2400MT/s           | 1        | 0.91%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3600MT/s        | 1        | 0.91%   |
| Micron RAM 8ATF2G64AZ-3G2E1 16GB DIMM DDR4 3200MT/s       | 1        | 0.91%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 41       | 48.81%  |
| DDR3    | 27       | 32.14%  |
| SDRAM   | 6        | 7.14%   |
| Unknown | 5        | 5.95%   |
| DDR2    | 3        | 3.57%   |
| DDR5    | 1        | 1.19%   |
| DDR     | 1        | 1.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 81       | 97.59%  |
| SODIMM | 2        | 2.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 34       | 37.78%  |
| 16384 | 16       | 17.78%  |
| 4096  | 14       | 15.56%  |
| 2048  | 14       | 15.56%  |
| 1024  | 4        | 4.44%   |
| 512   | 4        | 4.44%   |
| 32768 | 3        | 3.33%   |
| 256   | 1        | 1.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 18       | 18.95%  |
| 3200    | 13       | 13.68%  |
| 1333    | 9        | 9.47%   |
| 3600    | 7        | 7.37%   |
| Unknown | 6        | 6.32%   |
| 2667    | 5        | 5.26%   |
| 2400    | 4        | 4.21%   |
| 3666    | 3        | 3.16%   |
| 2133    | 3        | 3.16%   |
| 3733    | 2        | 2.11%   |
| 2666    | 2        | 2.11%   |
| 1632    | 2        | 2.11%   |
| 1067    | 2        | 2.11%   |
| 800     | 2        | 2.11%   |
| 667     | 2        | 2.11%   |
| 6000    | 1        | 1.05%   |
| 4199    | 1        | 1.05%   |
| 4133    | 1        | 1.05%   |
| 3800    | 1        | 1.05%   |
| 3334    | 1        | 1.05%   |
| 3266    | 1        | 1.05%   |
| 3000    | 1        | 1.05%   |
| 2933    | 1        | 1.05%   |
| 2733    | 1        | 1.05%   |
| 2134    | 1        | 1.05%   |
| 1867    | 1        | 1.05%   |
| 1866    | 1        | 1.05%   |
| 1800    | 1        | 1.05%   |
| 1334    | 1        | 1.05%   |
| 533     | 1        | 1.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 2        | 33.33%  |
| Seiko Epson         | 1        | 16.67%  |
| Samsung Electronics | 1        | 16.67%  |
| Konica Minolta      | 1        | 16.67%  |
| Hewlett-Packard     | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Seiko Epson Thermal Receipt Printer [TM-T20] | 1        | 16.67%  |
| Samsung SCX-3400 Series                      | 1        | 16.67%  |
| Konica Minolta Printer                       | 1        | 16.67%  |
| HP Smart Tank 750 series                     | 1        | 16.67%  |
| Brother HL-4140CN series                     | 1        | 16.67%  |
| Brother DCP-J152W                            | 1        | 16.67%  |

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
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 2        | 10%     |
| Z-Star Vimicro USB Camera (Altair)      | 1        | 5%      |
| Sunplus 5Mega Webcam                    | 1        | 5%      |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 5%      |
| Microsoft LifeCam HD-3000               | 1        | 5%      |
| Microdia Webcam Vitade AF               | 1        | 5%      |
| Microdia USB 2.0 Camera                 | 1        | 5%      |
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
| OmniKey               | 12       | 50%     |
| Alcor Micro           | 5        | 20.83%  |
| Gemalto (was Gemplus) | 4        | 16.67%  |
| SCM Microsystems      | 1        | 4.17%   |
| Clay Logic            | 1        | 4.17%   |
| Chicony Electronics   | 1        | 4.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| OmniKey CardMan 1021                                   | 12       | 50%     |
| Alcor Micro Watchdata W 1981                           | 5        | 20.83%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader      | 4        | 16.67%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 4.17%   |
| Clay Logic Nitrokey Start                              | 1        | 4.17%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard   | 1        | 4.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 106      | 77.94%  |
| 1     | 27       | 19.85%  |
| 2     | 3        | 2.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 15       | 45.45%  |
| Chipcard                 | 12       | 36.36%  |
| Net/wireless             | 2        | 6.06%   |
| Sound                    | 1        | 3.03%   |
| Net/ethernet             | 1        | 3.03%   |
| Multimedia controller    | 1        | 3.03%   |
| Communication controller | 1        | 3.03%   |

